
# Results vs. 3.10.4

- fork: python
- ref: 8deb8bc2e5af0e229df8
- machine: darwin-arm64
- commit hash: 8deb8bc
- commit date: 2023-11-20
- overall geometric mean: 1.17x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.12x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-darwin-arm64-python-8deb8bc2e5af0e229df8-3.13.0a1+-8deb8bc |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| 2to3           | 189 ms                                                 | 174 ms: 1.09x faster                                                   |
| chameleon      | 5.95 ms                                                | 4.83 ms: 1.23x faster                                                  |
| docutils       | 1.73 sec                                               | 1.49 sec: 1.16x faster                                                 |
| tornado_http   | 89.9 ms                                                | 70.7 ms: 1.27x faster                                                  |
| Geometric mean | (ref)                                                  | 1.19x faster                                                           |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-darwin-arm64-python-8deb8bc2e5af0e229df8-3.13.0a1+-8deb8bc |
|-------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| async_tree_none         | 384 ms                                                 | 255 ms: 1.51x faster                                                   |
| async_tree_memoization  | 473 ms                                                 | 331 ms: 1.43x faster                                                   |
| async_tree_io           | 984 ms                                                 | 702 ms: 1.40x faster                                                   |
| async_tree_cpu_io_mixed | 646 ms                                                 | 527 ms: 1.23x faster                                                   |
| Geometric mean          | (ref)                                                  | 1.39x faster                                                           |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-darwin-arm64-python-8deb8bc2e5af0e229df8-3.13.0a1+-8deb8bc |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| float          | 66.8 ms                                                | 58.4 ms: 1.14x faster                                                  |
| nbody          | 88.1 ms                                                | 79.0 ms: 1.12x faster                                                  |
| pidigits       | 282 ms                                                 | 282 ms: 1.00x faster                                                   |
| Geometric mean | (ref)                                                  | 1.08x faster                                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-darwin-arm64-python-8deb8bc2e5af0e229df8-3.13.0a1+-8deb8bc |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| regex_compile  | 92.3 ms                                                | 78.7 ms: 1.17x faster                                                  |
| regex_dna      | 174 ms                                                 | 149 ms: 1.17x faster                                                   |
| regex_v8       | 17.2 ms                                                | 16.9 ms: 1.02x faster                                                  |
| regex_effbot   | 2.46 ms                                                | 2.57 ms: 1.04x slower                                                  |
| Geometric mean | (ref)                                                  | 1.08x faster                                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-darwin-arm64-python-8deb8bc2e5af0e229df8-3.13.0a1+-8deb8bc |
|----------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| pickle_pure_python   | 272 us                                                 | 203 us: 1.34x faster                                                   |
| json_dumps           | 8.00 ms                                                | 6.56 ms: 1.22x faster                                                  |
| unpickle_pure_python | 191 us                                                 | 161 us: 1.19x faster                                                   |
| xml_etree_process    | 45.6 ms                                                | 40.2 ms: 1.13x faster                                                  |
| tomli_loads          | 1.65 sec                                               | 1.58 sec: 1.04x faster                                                 |
| xml_etree_parse      | 111 ms                                                 | 107 ms: 1.04x faster                                                   |
| unpickle             | 8.86 us                                                | 9.19 us: 1.04x slower                                                  |
| json_loads           | 16.7 us                                                | 17.4 us: 1.04x slower                                                  |
| pickle               | 7.04 us                                                | 7.35 us: 1.04x slower                                                  |
| xml_etree_iterparse  | 72.7 ms                                                | 76.2 ms: 1.05x slower                                                  |
| pickle_dict          | 17.0 us                                                | 18.0 us: 1.06x slower                                                  |
| pickle_list          | 2.72 us                                                | 2.90 us: 1.07x slower                                                  |
| xml_etree_generate   | 53.2 ms                                                | 58.4 ms: 1.10x slower                                                  |
| unpickle_list        | 2.79 us                                                | 3.15 us: 1.13x slower                                                  |
| Geometric mean       | (ref)                                                  | 1.03x faster                                                           |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-darwin-arm64-python-8deb8bc2e5af0e229df8-3.13.0a1+-8deb8bc |
|------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| python_startup         | 11.7 ms                                                | 11.6 ms: 1.00x faster                                                  |
| python_startup_no_site | 8.64 ms                                                | 10.3 ms: 1.19x slower                                                  |
| Geometric mean         | (ref)                                                  | 1.09x slower                                                           |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-darwin-arm64-python-8deb8bc2e5af0e229df8-3.13.0a1+-8deb8bc |
|-----------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| mako      | 9.86 ms                                                | 7.78 ms: 1.27x faster                                                  |

All benchmarks:
===============

| Benchmark                | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-darwin-arm64-python-8deb8bc2e5af0e229df8-3.13.0a1+-8deb8bc |
|--------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| typing_runtime_protocols | 336 us                                                 | 76.4 us: 4.41x faster                                                  |
| deltablue                | 4.94 ms                                                | 2.48 ms: 2.00x faster                                                  |
| asyncio_tcp              | 667 ms                                                 | 407 ms: 1.64x faster                                                   |
| logging_silent           | 115 ns                                                 | 73.3 ns: 1.57x faster                                                  |
| raytrace                 | 293 ms                                                 | 189 ms: 1.55x faster                                                   |
| async_tree_none          | 384 ms                                                 | 255 ms: 1.51x faster                                                   |
| richards_super           | 57.1 ms                                                | 38.4 ms: 1.49x faster                                                  |
| chaos                    | 64.1 ms                                                | 43.7 ms: 1.47x faster                                                  |
| async_tree_memoization   | 473 ms                                                 | 331 ms: 1.43x faster                                                   |
| crypto_pyaes             | 70.8 ms                                                | 49.7 ms: 1.42x faster                                                  |
| sqlglot_parse            | 1.20 ms                                                | 852 us: 1.41x faster                                                   |
| async_tree_io            | 984 ms                                                 | 702 ms: 1.40x faster                                                   |
| go                       | 148 ms                                                 | 107 ms: 1.39x faster                                                   |
| richards                 | 47.6 ms                                                | 34.5 ms: 1.38x faster                                                  |
| sqlglot_transpile        | 1.40 ms                                                | 1.04 ms: 1.35x faster                                                  |
| scimark_lu               | 102 ms                                                 | 75.9 ms: 1.34x faster                                                  |
| pickle_pure_python       | 272 us                                                 | 203 us: 1.34x faster                                                   |
| comprehensions           | 16.8 us                                                | 12.6 us: 1.34x faster                                                  |
| asyncio_websockets       | 544 ms                                                 | 408 ms: 1.33x faster                                                   |
| deepcopy_memo            | 33.1 us                                                | 25.2 us: 1.31x faster                                                  |
| unpack_sequence          | 36.7 ns                                                | 28.0 ns: 1.31x faster                                                  |
| scimark_monte_carlo      | 62.8 ms                                                | 48.4 ms: 1.30x faster                                                  |
| generators               | 32.6 ms                                                | 25.6 ms: 1.28x faster                                                  |
| tornado_http             | 89.9 ms                                                | 70.7 ms: 1.27x faster                                                  |
| mako                     | 9.86 ms                                                | 7.78 ms: 1.27x faster                                                  |
| asyncio_tcp_ssl          | 1.64 sec                                               | 1.30 sec: 1.26x faster                                                 |
| scimark_sor              | 134 ms                                                 | 107 ms: 1.25x faster                                                   |
| pathlib                  | 29.4 ms                                                | 23.6 ms: 1.25x faster                                                  |
| pycparser                | 878 ms                                                 | 710 ms: 1.24x faster                                                   |
| create_gc_cycles         | 865 us                                                 | 701 us: 1.23x faster                                                   |
| chameleon                | 5.95 ms                                                | 4.83 ms: 1.23x faster                                                  |
| spectral_norm            | 92.1 ms                                                | 75.0 ms: 1.23x faster                                                  |
| async_tree_cpu_io_mixed  | 646 ms                                                 | 527 ms: 1.23x faster                                                   |
| hexiom                   | 6.07 ms                                                | 4.96 ms: 1.22x faster                                                  |
| sympy_sum                | 92.4 ms                                                | 75.6 ms: 1.22x faster                                                  |
| json_dumps               | 8.00 ms                                                | 6.56 ms: 1.22x faster                                                  |
| pyflate                  | 419 ms                                                 | 346 ms: 1.21x faster                                                   |
| pprint_pformat           | 1.27 sec                                               | 1.06 sec: 1.20x faster                                                 |
| pprint_safe_repr         | 628 ms                                                 | 524 ms: 1.20x faster                                                   |
| unpickle_pure_python     | 191 us                                                 | 161 us: 1.19x faster                                                   |
| dulwich_log              | 35.6 ms                                                | 30.0 ms: 1.19x faster                                                  |
| sympy_integrate          | 13.2 ms                                                | 11.1 ms: 1.18x faster                                                  |
| logging_format           | 4.62 us                                                | 3.94 us: 1.17x faster                                                  |
| regex_compile            | 92.3 ms                                                | 78.7 ms: 1.17x faster                                                  |
| logging_simple           | 4.25 us                                                | 3.63 us: 1.17x faster                                                  |
| regex_dna                | 174 ms                                                 | 149 ms: 1.17x faster                                                   |
| deepcopy                 | 269 us                                                 | 230 us: 1.17x faster                                                   |
| mypy2                    | 300 ms                                                 | 259 ms: 1.16x faster                                                   |
| docutils                 | 1.73 sec                                               | 1.49 sec: 1.16x faster                                                 |
| float                    | 66.8 ms                                                | 58.4 ms: 1.14x faster                                                  |
| mdp                      | 1.87 sec                                               | 1.64 sec: 1.14x faster                                                 |
| xml_etree_process        | 45.6 ms                                                | 40.2 ms: 1.13x faster                                                  |
| dask                     | 254 ms                                                 | 226 ms: 1.12x faster                                                   |
| sympy_str                | 164 ms                                                 | 147 ms: 1.12x faster                                                   |
| nbody                    | 88.1 ms                                                | 79.0 ms: 1.12x faster                                                  |
| deepcopy_reduce          | 2.28 us                                                | 2.05 us: 1.11x faster                                                  |
| 2to3                     | 189 ms                                                 | 174 ms: 1.09x faster                                                   |
| sympy_expand             | 267 ms                                                 | 255 ms: 1.05x faster                                                   |
| tomli_loads              | 1.65 sec                                               | 1.58 sec: 1.04x faster                                                 |
| coroutines               | 19.6 ms                                                | 18.8 ms: 1.04x faster                                                  |
| xml_etree_parse          | 111 ms                                                 | 107 ms: 1.04x faster                                                   |
| scimark_fft              | 216 ms                                                 | 208 ms: 1.04x faster                                                   |
| meteor_contest           | 77.9 ms                                                | 74.9 ms: 1.04x faster                                                  |
| scimark_sparse_mat_mult  | 3.26 ms                                                | 3.16 ms: 1.03x faster                                                  |
| nqueens                  | 62.4 ms                                                | 60.6 ms: 1.03x faster                                                  |
| fannkuch                 | 294 ms                                                 | 287 ms: 1.03x faster                                                   |
| sqlglot_optimize         | 36.3 ms                                                | 35.4 ms: 1.02x faster                                                  |
| regex_v8                 | 17.2 ms                                                | 16.9 ms: 1.02x faster                                                  |
| json                     | 3.06 ms                                                | 3.03 ms: 1.01x faster                                                  |
| python_startup           | 11.7 ms                                                | 11.6 ms: 1.00x faster                                                  |
| bench_thread_pool        | 516 us                                                 | 514 us: 1.00x faster                                                   |
| pidigits                 | 282 ms                                                 | 282 ms: 1.00x faster                                                   |
| gc_traversal             | 2.37 ms                                                | 2.39 ms: 1.01x slower                                                  |
| sqlglot_normalize        | 187 ms                                                 | 191 ms: 1.02x slower                                                   |
| unpickle                 | 8.86 us                                                | 9.19 us: 1.04x slower                                                  |
| json_loads               | 16.7 us                                                | 17.4 us: 1.04x slower                                                  |
| regex_effbot             | 2.46 ms                                                | 2.57 ms: 1.04x slower                                                  |
| pickle                   | 7.04 us                                                | 7.35 us: 1.04x slower                                                  |
| xml_etree_iterparse      | 72.7 ms                                                | 76.2 ms: 1.05x slower                                                  |
| pickle_dict              | 17.0 us                                                | 18.0 us: 1.06x slower                                                  |
| pickle_list              | 2.72 us                                                | 2.90 us: 1.07x slower                                                  |
| xml_etree_generate       | 53.2 ms                                                | 58.4 ms: 1.10x slower                                                  |
| bench_mp_pool            | 39.0 ms                                                | 43.6 ms: 1.12x slower                                                  |
| unpickle_list            | 2.79 us                                                | 3.15 us: 1.13x slower                                                  |
| sqlite_synth             | 1.43 us                                                | 1.65 us: 1.16x slower                                                  |
| coverage                 | 41.1 ms                                                | 48.4 ms: 1.18x slower                                                  |
| python_startup_no_site   | 8.64 ms                                                | 10.3 ms: 1.19x slower                                                  |
| async_generators         | 233 ms                                                 | 304 ms: 1.31x slower                                                   |
| telco                    | 3.42 ms                                                | 4.64 ms: 1.36x slower                                                  |
| Geometric mean           | (ref)                                                  | 1.17x faster                                                           |
Ignored benchmarks (11) of results/bm-20220323-3.10.4-9d38120/bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
Ignored benchmarks (4) of results/bm-20231120-3.13.0a1+-8deb8bc/bm-20231120-darwin-arm64-python-8deb8bc2e5af0e229df8-3.13.0a1+-8deb8bc.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.14x
- 95% likely to have a speedup of 1.14x
- 99% likely to have a speedup of 1.12x
