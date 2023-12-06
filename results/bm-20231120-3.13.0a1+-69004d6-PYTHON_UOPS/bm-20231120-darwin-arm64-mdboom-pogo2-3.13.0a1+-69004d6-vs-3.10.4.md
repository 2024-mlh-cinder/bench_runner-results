
# Results vs. 3.10.4

- fork: mdboom
- ref: pogo2
- machine: darwin-arm64
- commit hash: 69004d6
- commit date: 2023-11-20
- overall geometric mean: 1.08x faster \*
- HPT reliability: 99.88%
- HPT 99th percentile: 1.01x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-darwin-arm64-mdboom-pogo2-3.13.0a1+-69004d6 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| 2to3           | 189 ms                                                 | 183 ms: 1.03x faster                                    |
| chameleon      | 5.95 ms                                                | 5.06 ms: 1.18x faster                                   |
| docutils       | 1.73 sec                                               | 1.55 sec: 1.12x faster                                  |
| tornado_http   | 89.9 ms                                                | 74.2 ms: 1.21x faster                                   |
| Geometric mean | (ref)                                                  | 1.13x faster                                            |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-darwin-arm64-mdboom-pogo2-3.13.0a1+-69004d6 |
|-------------------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| async_tree_none         | 384 ms                                                 | 265 ms: 1.45x faster                                    |
| async_tree_memoization  | 473 ms                                                 | 342 ms: 1.38x faster                                    |
| async_tree_io           | 984 ms                                                 | 719 ms: 1.37x faster                                    |
| async_tree_cpu_io_mixed | 646 ms                                                 | 535 ms: 1.21x faster                                    |
| Geometric mean          | (ref)                                                  | 1.35x faster                                            |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-darwin-arm64-mdboom-pogo2-3.13.0a1+-69004d6 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| pidigits       | 282 ms                                                 | 283 ms: 1.01x slower                                    |
| float          | 66.8 ms                                                | 72.9 ms: 1.09x slower                                   |
| nbody          | 88.1 ms                                                | 97.7 ms: 1.11x slower                                   |
| Geometric mean | (ref)                                                  | 1.07x slower                                            |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-darwin-arm64-mdboom-pogo2-3.13.0a1+-69004d6 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| regex_dna      | 174 ms                                                 | 149 ms: 1.16x faster                                    |
| regex_compile  | 92.3 ms                                                | 90.8 ms: 1.02x faster                                   |
| regex_v8       | 17.2 ms                                                | 17.0 ms: 1.01x faster                                   |
| regex_effbot   | 2.46 ms                                                | 2.56 ms: 1.04x slower                                   |
| Geometric mean | (ref)                                                  | 1.04x faster                                            |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-darwin-arm64-mdboom-pogo2-3.13.0a1+-69004d6 |
|----------------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| pickle_pure_python   | 272 us                                                 | 204 us: 1.33x faster                                    |
| json_dumps           | 8.00 ms                                                | 6.62 ms: 1.21x faster                                   |
| unpickle_pure_python | 191 us                                                 | 175 us: 1.09x faster                                    |
| xml_etree_process    | 45.6 ms                                                | 42.7 ms: 1.07x faster                                   |
| xml_etree_parse      | 111 ms                                                 | 107 ms: 1.03x faster                                    |
| unpickle             | 8.86 us                                                | 9.08 us: 1.02x slower                                   |
| json_loads           | 16.7 us                                                | 17.2 us: 1.03x slower                                   |
| pickle               | 7.04 us                                                | 7.34 us: 1.04x slower                                   |
| pickle_dict          | 17.0 us                                                | 17.9 us: 1.05x slower                                   |
| tomli_loads          | 1.65 sec                                               | 1.81 sec: 1.09x slower                                  |
| pickle_list          | 2.72 us                                                | 2.98 us: 1.09x slower                                   |
| unpickle_list        | 2.79 us                                                | 3.15 us: 1.13x slower                                   |
| xml_etree_iterparse  | 72.7 ms                                                | 82.9 ms: 1.14x slower                                   |
| xml_etree_generate   | 53.2 ms                                                | 62.3 ms: 1.17x slower                                   |
| Geometric mean       | (ref)                                                  | 1.01x slower                                            |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-darwin-arm64-mdboom-pogo2-3.13.0a1+-69004d6 |
|------------------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| python_startup         | 11.7 ms                                                | 12.2 ms: 1.04x slower                                   |
| python_startup_no_site | 8.64 ms                                                | 10.7 ms: 1.23x slower                                   |
| Geometric mean         | (ref)                                                  | 1.13x slower                                            |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-darwin-arm64-mdboom-pogo2-3.13.0a1+-69004d6 |
|-----------|:------------------------------------------------------:|:-------------------------------------------------------:|
| mako      | 9.86 ms                                                | 10.7 ms: 1.09x slower                                   |

All benchmarks:
===============

| Benchmark                | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-darwin-arm64-mdboom-pogo2-3.13.0a1+-69004d6 |
|--------------------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| typing_runtime_protocols | 336 us                                                 | 80.6 us: 4.17x faster                                   |
| logging_silent           | 115 ns                                                 | 74.3 ns: 1.55x faster                                   |
| richards_super           | 57.1 ms                                                | 38.1 ms: 1.50x faster                                   |
| asyncio_tcp              | 667 ms                                                 | 452 ms: 1.48x faster                                    |
| async_tree_none          | 384 ms                                                 | 265 ms: 1.45x faster                                    |
| raytrace                 | 293 ms                                                 | 207 ms: 1.42x faster                                    |
| richards                 | 47.6 ms                                                | 34.4 ms: 1.39x faster                                   |
| async_tree_memoization   | 473 ms                                                 | 342 ms: 1.38x faster                                    |
| async_tree_io            | 984 ms                                                 | 719 ms: 1.37x faster                                    |
| sqlglot_parse            | 1.20 ms                                                | 892 us: 1.35x faster                                    |
| asyncio_websockets       | 544 ms                                                 | 409 ms: 1.33x faster                                    |
| pickle_pure_python       | 272 us                                                 | 204 us: 1.33x faster                                    |
| unpack_sequence          | 36.7 ns                                                | 28.2 ns: 1.30x faster                                   |
| sqlglot_transpile        | 1.40 ms                                                | 1.08 ms: 1.29x faster                                   |
| scimark_lu               | 102 ms                                                 | 78.9 ms: 1.29x faster                                   |
| deltablue                | 4.94 ms                                                | 3.84 ms: 1.29x faster                                   |
| go                       | 148 ms                                                 | 115 ms: 1.28x faster                                    |
| generators               | 32.6 ms                                                | 25.5 ms: 1.28x faster                                   |
| asyncio_tcp_ssl          | 1.64 sec                                               | 1.30 sec: 1.26x faster                                  |
| create_gc_cycles         | 865 us                                                 | 699 us: 1.24x faster                                    |
| chaos                    | 64.1 ms                                                | 51.9 ms: 1.24x faster                                   |
| pathlib                  | 29.4 ms                                                | 23.9 ms: 1.23x faster                                   |
| deepcopy_memo            | 33.1 us                                                | 27.1 us: 1.22x faster                                   |
| scimark_sor              | 134 ms                                                 | 110 ms: 1.22x faster                                    |
| pycparser                | 878 ms                                                 | 719 ms: 1.22x faster                                    |
| crypto_pyaes             | 70.8 ms                                                | 58.2 ms: 1.22x faster                                   |
| tornado_http             | 89.9 ms                                                | 74.2 ms: 1.21x faster                                   |
| json_dumps               | 8.00 ms                                                | 6.62 ms: 1.21x faster                                   |
| async_tree_cpu_io_mixed  | 646 ms                                                 | 535 ms: 1.21x faster                                    |
| chameleon                | 5.95 ms                                                | 5.06 ms: 1.18x faster                                   |
| dulwich_log              | 35.6 ms                                                | 30.5 ms: 1.17x faster                                   |
| regex_dna                | 174 ms                                                 | 149 ms: 1.16x faster                                    |
| deepcopy                 | 269 us                                                 | 234 us: 1.15x faster                                    |
| logging_format           | 4.62 us                                                | 4.03 us: 1.15x faster                                   |
| logging_simple           | 4.25 us                                                | 3.72 us: 1.14x faster                                   |
| mypy2                    | 300 ms                                                 | 266 ms: 1.13x faster                                    |
| docutils                 | 1.73 sec                                               | 1.55 sec: 1.12x faster                                  |
| dask                     | 254 ms                                                 | 231 ms: 1.10x faster                                    |
| unpickle_pure_python     | 191 us                                                 | 175 us: 1.09x faster                                    |
| deepcopy_reduce          | 2.28 us                                                | 2.09 us: 1.09x faster                                   |
| sympy_sum                | 92.4 ms                                                | 84.8 ms: 1.09x faster                                   |
| mdp                      | 1.87 sec                                               | 1.73 sec: 1.08x faster                                  |
| pyflate                  | 419 ms                                                 | 389 ms: 1.08x faster                                    |
| sympy_integrate          | 13.2 ms                                                | 12.2 ms: 1.07x faster                                   |
| xml_etree_process        | 45.6 ms                                                | 42.7 ms: 1.07x faster                                   |
| pprint_safe_repr         | 628 ms                                                 | 601 ms: 1.04x faster                                    |
| coroutines               | 19.6 ms                                                | 18.8 ms: 1.04x faster                                   |
| xml_etree_parse          | 111 ms                                                 | 107 ms: 1.03x faster                                    |
| 2to3                     | 189 ms                                                 | 183 ms: 1.03x faster                                    |
| pprint_pformat           | 1.27 sec                                               | 1.24 sec: 1.03x faster                                  |
| sympy_str                | 164 ms                                                 | 160 ms: 1.03x faster                                    |
| sympy_expand             | 267 ms                                                 | 263 ms: 1.02x faster                                    |
| regex_compile            | 92.3 ms                                                | 90.8 ms: 1.02x faster                                   |
| scimark_monte_carlo      | 62.8 ms                                                | 61.9 ms: 1.01x faster                                   |
| regex_v8                 | 17.2 ms                                                | 17.0 ms: 1.01x faster                                   |
| json                     | 3.06 ms                                                | 3.03 ms: 1.01x faster                                   |
| pidigits                 | 282 ms                                                 | 283 ms: 1.01x slower                                    |
| gc_traversal             | 2.37 ms                                                | 2.40 ms: 1.01x slower                                   |
| unpickle                 | 8.86 us                                                | 9.08 us: 1.02x slower                                   |
| json_loads               | 16.7 us                                                | 17.2 us: 1.03x slower                                   |
| comprehensions           | 16.8 us                                                | 17.3 us: 1.03x slower                                   |
| bench_thread_pool        | 516 us                                                 | 535 us: 1.04x slower                                    |
| regex_effbot             | 2.46 ms                                                | 2.56 ms: 1.04x slower                                   |
| python_startup           | 11.7 ms                                                | 12.2 ms: 1.04x slower                                   |
| pickle                   | 7.04 us                                                | 7.34 us: 1.04x slower                                   |
| pickle_dict              | 17.0 us                                                | 17.9 us: 1.05x slower                                   |
| sqlglot_optimize         | 36.3 ms                                                | 38.2 ms: 1.05x slower                                   |
| meteor_contest           | 77.9 ms                                                | 83.3 ms: 1.07x slower                                   |
| sqlglot_normalize        | 187 ms                                                 | 203 ms: 1.09x slower                                    |
| mako                     | 9.86 ms                                                | 10.7 ms: 1.09x slower                                   |
| hexiom                   | 6.07 ms                                                | 6.61 ms: 1.09x slower                                   |
| float                    | 66.8 ms                                                | 72.9 ms: 1.09x slower                                   |
| tomli_loads              | 1.65 sec                                               | 1.81 sec: 1.09x slower                                  |
| pickle_list              | 2.72 us                                                | 2.98 us: 1.09x slower                                   |
| nbody                    | 88.1 ms                                                | 97.7 ms: 1.11x slower                                   |
| unpickle_list            | 2.79 us                                                | 3.15 us: 1.13x slower                                   |
| xml_etree_iterparse      | 72.7 ms                                                | 82.9 ms: 1.14x slower                                   |
| bench_mp_pool            | 39.0 ms                                                | 44.8 ms: 1.15x slower                                   |
| coverage                 | 41.1 ms                                                | 47.6 ms: 1.16x slower                                   |
| xml_etree_generate       | 53.2 ms                                                | 62.3 ms: 1.17x slower                                   |
| nqueens                  | 62.4 ms                                                | 73.2 ms: 1.17x slower                                   |
| sqlite_synth             | 1.43 us                                                | 1.72 us: 1.20x slower                                   |
| fannkuch                 | 294 ms                                                 | 363 ms: 1.23x slower                                    |
| python_startup_no_site   | 8.64 ms                                                | 10.7 ms: 1.23x slower                                   |
| spectral_norm            | 92.1 ms                                                | 115 ms: 1.25x slower                                    |
| scimark_fft              | 216 ms                                                 | 279 ms: 1.29x slower                                    |
| scimark_sparse_mat_mult  | 3.26 ms                                                | 4.39 ms: 1.35x slower                                   |
| async_generators         | 233 ms                                                 | 314 ms: 1.35x slower                                    |
| telco                    | 3.42 ms                                                | 4.89 ms: 1.43x slower                                   |
| Geometric mean           | (ref)                                                  | 1.08x faster                                            |
Ignored benchmarks (11) of results/bm-20220323-3.10.4-9d38120/bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
Ignored benchmarks (4) of results/bm-20231120-3.13.0a1+-69004d6-PYTHON_UOPS/bm-20231120-darwin-arm64-mdboom-pogo2-3.13.0a1+-69004d6.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 99.88% likely to be faster
- 90% likely to have a speedup of 1.03x
- 95% likely to have a speedup of 1.02x
- 99% likely to have a speedup of 1.01x
