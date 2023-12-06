
# Results vs. 3.10.4

- fork: mdboom
- ref: alternative_workarou
- machine: darwin-arm64
- commit hash: d452c37
- commit date: 2023-11-20
- overall geometric mean: 1.16x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.11x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-darwin-arm64-mdboom-alternative_workarou-3.13.0a1+-d452c37 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| 2to3           | 189 ms                                                 | 174 ms: 1.09x faster                                                   |
| chameleon      | 5.95 ms                                                | 4.86 ms: 1.22x faster                                                  |
| docutils       | 1.73 sec                                               | 1.51 sec: 1.15x faster                                                 |
| tornado_http   | 89.9 ms                                                | 71.7 ms: 1.25x faster                                                  |
| Geometric mean | (ref)                                                  | 1.18x faster                                                           |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-darwin-arm64-mdboom-alternative_workarou-3.13.0a1+-d452c37 |
|-------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| async_tree_none         | 384 ms                                                 | 254 ms: 1.51x faster                                                   |
| async_tree_memoization  | 473 ms                                                 | 331 ms: 1.43x faster                                                   |
| async_tree_io           | 984 ms                                                 | 703 ms: 1.40x faster                                                   |
| async_tree_cpu_io_mixed | 646 ms                                                 | 527 ms: 1.23x faster                                                   |
| Geometric mean          | (ref)                                                  | 1.39x faster                                                           |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-darwin-arm64-mdboom-alternative_workarou-3.13.0a1+-d452c37 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| float          | 66.8 ms                                                | 58.4 ms: 1.14x faster                                                  |
| nbody          | 88.1 ms                                                | 79.2 ms: 1.11x faster                                                  |
| pidigits       | 282 ms                                                 | 282 ms: 1.00x faster                                                   |
| Geometric mean | (ref)                                                  | 1.08x faster                                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-darwin-arm64-mdboom-alternative_workarou-3.13.0a1+-d452c37 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| regex_compile  | 92.3 ms                                                | 78.9 ms: 1.17x faster                                                  |
| regex_dna      | 174 ms                                                 | 149 ms: 1.17x faster                                                   |
| regex_v8       | 17.2 ms                                                | 16.9 ms: 1.02x faster                                                  |
| regex_effbot   | 2.46 ms                                                | 2.58 ms: 1.05x slower                                                  |
| Geometric mean | (ref)                                                  | 1.07x faster                                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-darwin-arm64-mdboom-alternative_workarou-3.13.0a1+-d452c37 |
|----------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| pickle_pure_python   | 272 us                                                 | 205 us: 1.33x faster                                                   |
| json_dumps           | 8.00 ms                                                | 6.59 ms: 1.21x faster                                                  |
| unpickle_pure_python | 191 us                                                 | 161 us: 1.19x faster                                                   |
| xml_etree_process    | 45.6 ms                                                | 40.4 ms: 1.13x faster                                                  |
| tomli_loads          | 1.65 sec                                               | 1.58 sec: 1.05x faster                                                 |
| xml_etree_parse      | 111 ms                                                 | 108 ms: 1.03x faster                                                   |
| unpickle             | 8.86 us                                                | 9.15 us: 1.03x slower                                                  |
| json_loads           | 16.7 us                                                | 17.4 us: 1.04x slower                                                  |
| pickle               | 7.04 us                                                | 7.37 us: 1.05x slower                                                  |
| pickle_dict          | 17.0 us                                                | 17.9 us: 1.05x slower                                                  |
| xml_etree_iterparse  | 72.7 ms                                                | 76.8 ms: 1.06x slower                                                  |
| pickle_list          | 2.72 us                                                | 2.94 us: 1.08x slower                                                  |
| xml_etree_generate   | 53.2 ms                                                | 58.2 ms: 1.09x slower                                                  |
| unpickle_list        | 2.79 us                                                | 3.14 us: 1.13x slower                                                  |
| Geometric mean       | (ref)                                                  | 1.02x faster                                                           |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-darwin-arm64-mdboom-alternative_workarou-3.13.0a1+-d452c37 |
|------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| python_startup         | 11.7 ms                                                | 12.3 ms: 1.05x slower                                                  |
| python_startup_no_site | 8.64 ms                                                | 10.8 ms: 1.25x slower                                                  |
| Geometric mean         | (ref)                                                  | 1.15x slower                                                           |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-darwin-arm64-mdboom-alternative_workarou-3.13.0a1+-d452c37 |
|-----------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| mako      | 9.86 ms                                                | 7.79 ms: 1.27x faster                                                  |

All benchmarks:
===============

| Benchmark                | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-darwin-arm64-mdboom-alternative_workarou-3.13.0a1+-d452c37 |
|--------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| typing_runtime_protocols | 336 us                                                 | 75.9 us: 4.43x faster                                                  |
| deltablue                | 4.94 ms                                                | 2.49 ms: 1.98x faster                                                  |
| asyncio_tcp              | 667 ms                                                 | 424 ms: 1.57x faster                                                   |
| logging_silent           | 115 ns                                                 | 73.2 ns: 1.57x faster                                                  |
| raytrace                 | 293 ms                                                 | 189 ms: 1.54x faster                                                   |
| async_tree_none          | 384 ms                                                 | 254 ms: 1.51x faster                                                   |
| richards_super           | 57.1 ms                                                | 38.4 ms: 1.49x faster                                                  |
| chaos                    | 64.1 ms                                                | 43.5 ms: 1.47x faster                                                  |
| crypto_pyaes             | 70.8 ms                                                | 49.4 ms: 1.43x faster                                                  |
| async_tree_memoization   | 473 ms                                                 | 331 ms: 1.43x faster                                                   |
| sqlglot_parse            | 1.20 ms                                                | 851 us: 1.41x faster                                                   |
| async_tree_io            | 984 ms                                                 | 703 ms: 1.40x faster                                                   |
| go                       | 148 ms                                                 | 107 ms: 1.39x faster                                                   |
| richards                 | 47.6 ms                                                | 34.8 ms: 1.37x faster                                                  |
| scimark_lu               | 102 ms                                                 | 74.8 ms: 1.36x faster                                                  |
| sqlglot_transpile        | 1.40 ms                                                | 1.03 ms: 1.36x faster                                                  |
| comprehensions           | 16.8 us                                                | 12.6 us: 1.33x faster                                                  |
| asyncio_websockets       | 544 ms                                                 | 409 ms: 1.33x faster                                                   |
| pickle_pure_python       | 272 us                                                 | 205 us: 1.33x faster                                                   |
| unpack_sequence          | 36.7 ns                                                | 27.9 ns: 1.32x faster                                                  |
| deepcopy_memo            | 33.1 us                                                | 25.3 us: 1.31x faster                                                  |
| scimark_monte_carlo      | 62.8 ms                                                | 48.5 ms: 1.30x faster                                                  |
| generators               | 32.6 ms                                                | 25.6 ms: 1.27x faster                                                  |
| asyncio_tcp_ssl          | 1.64 sec                                               | 1.29 sec: 1.27x faster                                                 |
| mako                     | 9.86 ms                                                | 7.79 ms: 1.27x faster                                                  |
| tornado_http             | 89.9 ms                                                | 71.7 ms: 1.25x faster                                                  |
| scimark_sor              | 134 ms                                                 | 107 ms: 1.25x faster                                                   |
| pycparser                | 878 ms                                                 | 710 ms: 1.24x faster                                                   |
| create_gc_cycles         | 865 us                                                 | 700 us: 1.24x faster                                                   |
| async_tree_cpu_io_mixed  | 646 ms                                                 | 527 ms: 1.23x faster                                                   |
| chameleon                | 5.95 ms                                                | 4.86 ms: 1.22x faster                                                  |
| spectral_norm            | 92.1 ms                                                | 75.3 ms: 1.22x faster                                                  |
| sympy_sum                | 92.4 ms                                                | 75.6 ms: 1.22x faster                                                  |
| hexiom                   | 6.07 ms                                                | 4.97 ms: 1.22x faster                                                  |
| json_dumps               | 8.00 ms                                                | 6.59 ms: 1.21x faster                                                  |
| pathlib                  | 29.4 ms                                                | 24.3 ms: 1.21x faster                                                  |
| pyflate                  | 419 ms                                                 | 346 ms: 1.21x faster                                                   |
| pprint_safe_repr         | 628 ms                                                 | 525 ms: 1.20x faster                                                   |
| pprint_pformat           | 1.27 sec                                               | 1.07 sec: 1.19x faster                                                 |
| unpickle_pure_python     | 191 us                                                 | 161 us: 1.19x faster                                                   |
| dulwich_log              | 35.6 ms                                                | 30.0 ms: 1.19x faster                                                  |
| sympy_integrate          | 13.2 ms                                                | 11.2 ms: 1.18x faster                                                  |
| logging_format           | 4.62 us                                                | 3.93 us: 1.18x faster                                                  |
| regex_compile            | 92.3 ms                                                | 78.9 ms: 1.17x faster                                                  |
| logging_simple           | 4.25 us                                                | 3.64 us: 1.17x faster                                                  |
| regex_dna                | 174 ms                                                 | 149 ms: 1.17x faster                                                   |
| deepcopy                 | 269 us                                                 | 232 us: 1.16x faster                                                   |
| mypy2                    | 300 ms                                                 | 259 ms: 1.16x faster                                                   |
| docutils                 | 1.73 sec                                               | 1.51 sec: 1.15x faster                                                 |
| float                    | 66.8 ms                                                | 58.4 ms: 1.14x faster                                                  |
| mdp                      | 1.87 sec                                               | 1.65 sec: 1.14x faster                                                 |
| xml_etree_process        | 45.6 ms                                                | 40.4 ms: 1.13x faster                                                  |
| sympy_str                | 164 ms                                                 | 147 ms: 1.12x faster                                                   |
| dask                     | 254 ms                                                 | 228 ms: 1.11x faster                                                   |
| nbody                    | 88.1 ms                                                | 79.2 ms: 1.11x faster                                                  |
| deepcopy_reduce          | 2.28 us                                                | 2.08 us: 1.10x faster                                                  |
| 2to3                     | 189 ms                                                 | 174 ms: 1.09x faster                                                   |
| sympy_expand             | 267 ms                                                 | 254 ms: 1.05x faster                                                   |
| coroutines               | 19.6 ms                                                | 18.8 ms: 1.05x faster                                                  |
| tomli_loads              | 1.65 sec                                               | 1.58 sec: 1.05x faster                                                 |
| meteor_contest           | 77.9 ms                                                | 75.4 ms: 1.03x faster                                                  |
| scimark_fft              | 216 ms                                                 | 210 ms: 1.03x faster                                                   |
| scimark_sparse_mat_mult  | 3.26 ms                                                | 3.16 ms: 1.03x faster                                                  |
| xml_etree_parse          | 111 ms                                                 | 108 ms: 1.03x faster                                                   |
| nqueens                  | 62.4 ms                                                | 60.7 ms: 1.03x faster                                                  |
| fannkuch                 | 294 ms                                                 | 288 ms: 1.02x faster                                                   |
| sqlglot_optimize         | 36.3 ms                                                | 35.5 ms: 1.02x faster                                                  |
| regex_v8                 | 17.2 ms                                                | 16.9 ms: 1.02x faster                                                  |
| json                     | 3.06 ms                                                | 3.01 ms: 1.01x faster                                                  |
| pidigits                 | 282 ms                                                 | 282 ms: 1.00x faster                                                   |
| gc_traversal             | 2.37 ms                                                | 2.39 ms: 1.01x slower                                                  |
| sqlglot_normalize        | 187 ms                                                 | 191 ms: 1.02x slower                                                   |
| unpickle                 | 8.86 us                                                | 9.15 us: 1.03x slower                                                  |
| json_loads               | 16.7 us                                                | 17.4 us: 1.04x slower                                                  |
| pickle                   | 7.04 us                                                | 7.37 us: 1.05x slower                                                  |
| python_startup           | 11.7 ms                                                | 12.3 ms: 1.05x slower                                                  |
| regex_effbot             | 2.46 ms                                                | 2.58 ms: 1.05x slower                                                  |
| pickle_dict              | 17.0 us                                                | 17.9 us: 1.05x slower                                                  |
| xml_etree_iterparse      | 72.7 ms                                                | 76.8 ms: 1.06x slower                                                  |
| pickle_list              | 2.72 us                                                | 2.94 us: 1.08x slower                                                  |
| xml_etree_generate       | 53.2 ms                                                | 58.2 ms: 1.09x slower                                                  |
| unpickle_list            | 2.79 us                                                | 3.14 us: 1.13x slower                                                  |
| bench_mp_pool            | 39.0 ms                                                | 44.5 ms: 1.14x slower                                                  |
| coverage                 | 41.1 ms                                                | 47.5 ms: 1.16x slower                                                  |
| sqlite_synth             | 1.43 us                                                | 1.67 us: 1.17x slower                                                  |
| python_startup_no_site   | 8.64 ms                                                | 10.8 ms: 1.25x slower                                                  |
| async_generators         | 233 ms                                                 | 306 ms: 1.31x slower                                                   |
| telco                    | 3.42 ms                                                | 4.76 ms: 1.39x slower                                                  |
| Geometric mean           | (ref)                                                  | 1.16x faster                                                           |

Benchmark hidden because not significant (1): bench_thread_pool
Ignored benchmarks (11) of results/bm-20220323-3.10.4-9d38120/bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
Ignored benchmarks (4) of results/bm-20231120-3.13.0a1+-d452c37/bm-20231120-darwin-arm64-mdboom-alternative_workarou-3.13.0a1+-d452c37.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.14x
- 95% likely to have a speedup of 1.13x
- 99% likely to have a speedup of 1.11x
