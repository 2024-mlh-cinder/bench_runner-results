
# Results vs. 3.10.4

- fork: python
- ref: v3.12.0b3
- machine: linux-x86_64
- commit hash: f992a60
- commit date: 2023-06-19
- overall geometric mean: 1.30x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.23x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230619-pythonperf2-x86_64-python-v3.12.0b3-3.12.0b3-f992a60 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| 2to3           | 349 ms                                                       | 283 ms: 1.24x faster                                             |
| docutils       | 3.42 sec                                                     | 2.87 sec: 1.19x faster                                           |
| tornado_http   | 157 ms                                                       | 118 ms: 1.32x faster                                             |
| Geometric mean | (ref)                                                        | 1.25x faster                                                     |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230619-pythonperf2-x86_64-python-v3.12.0b3-3.12.0b3-f992a60 |
|-------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| async_tree_none         | 700 ms                                                       | 457 ms: 1.53x faster                                             |
| async_tree_io           | 1.61 sec                                                     | 1.06 sec: 1.52x faster                                           |
| async_tree_memoization  | 827 ms                                                       | 551 ms: 1.50x faster                                             |
| async_tree_cpu_io_mixed | 946 ms                                                       | 704 ms: 1.34x faster                                             |
| Geometric mean          | (ref)                                                        | 1.47x faster                                                     |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230619-pythonperf2-x86_64-python-v3.12.0b3-3.12.0b3-f992a60 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| nbody          | 134 ms                                                       | 84.2 ms: 1.59x faster                                            |
| float          | 109 ms                                                       | 78.8 ms: 1.38x faster                                            |
| pidigits       | 270 ms                                                       | 260 ms: 1.04x faster                                             |
| Geometric mean | (ref)                                                        | 1.32x faster                                                     |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230619-pythonperf2-x86_64-python-v3.12.0b3-3.12.0b3-f992a60 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| regex_compile  | 192 ms                                                       | 144 ms: 1.34x faster                                             |
| regex_v8       | 27.1 ms                                                      | 23.9 ms: 1.13x faster                                            |
| regex_dna      | 260 ms                                                       | 238 ms: 1.09x faster                                             |
| regex_effbot   | 3.10 ms                                                      | 3.48 ms: 1.12x slower                                            |
| Geometric mean | (ref)                                                        | 1.10x faster                                                     |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230619-pythonperf2-x86_64-python-v3.12.0b3-3.12.0b3-f992a60 |
|----------------------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| unpickle_pure_python | 315 us                                                       | 209 us: 1.51x faster                                             |
| pickle_pure_python   | 453 us                                                       | 326 us: 1.39x faster                                             |
| json_dumps           | 14.2 ms                                                      | 10.4 ms: 1.37x faster                                            |
| tomli_loads          | 2.96 sec                                                     | 2.17 sec: 1.36x faster                                           |
| xml_etree_process    | 76.4 ms                                                      | 58.2 ms: 1.31x faster                                            |
| json_loads           | 30.0 us                                                      | 24.7 us: 1.21x faster                                            |
| xml_etree_generate   | 93.1 ms                                                      | 85.3 ms: 1.09x faster                                            |
| xml_etree_parse      | 159 ms                                                       | 150 ms: 1.06x faster                                             |
| xml_etree_iterparse  | 110 ms                                                       | 106 ms: 1.03x faster                                             |
| pickle               | 10.1 us                                                      | 10.3 us: 1.02x slower                                            |
| unpickle_list        | 4.45 us                                                      | 4.65 us: 1.05x slower                                            |
| unpickle             | 13.9 us                                                      | 14.6 us: 1.05x slower                                            |
| pickle_list          | 4.23 us                                                      | 4.43 us: 1.05x slower                                            |
| pickle_dict          | 30.4 us                                                      | 33.6 us: 1.11x slower                                            |
| Geometric mean       | (ref)                                                        | 1.13x faster                                                     |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230619-pythonperf2-x86_64-python-v3.12.0b3-3.12.0b3-f992a60 |
|------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| python_startup         | 11.5 ms                                                      | 11.4 ms: 1.01x faster                                            |
| python_startup_no_site | 7.35 ms                                                      | 8.43 ms: 1.15x slower                                            |
| Geometric mean         | (ref)                                                        | 1.06x slower                                                     |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230619-pythonperf2-x86_64-python-v3.12.0b3-3.12.0b3-f992a60 |
|-----------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| mako      | 14.7 ms                                                      | 10.0 ms: 1.47x faster                                            |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230619-pythonperf2-x86_64-python-v3.12.0b3-3.12.0b3-f992a60 |
|--------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| typing_runtime_protocols | 533 us                                                       | 152 us: 3.51x faster                                             |
| deltablue                | 7.43 ms                                                      | 3.21 ms: 2.31x faster                                            |
| asyncio_tcp              | 785 ms                                                       | 377 ms: 2.08x faster                                             |
| asyncio_tcp_ssl          | 3.13 sec                                                     | 1.56 sec: 2.00x faster                                           |
| richards_super           | 93.0 ms                                                      | 50.8 ms: 1.83x faster                                            |
| logging_silent           | 168 ns                                                       | 91.8 ns: 1.83x faster                                            |
| go                       | 258 ms                                                       | 145 ms: 1.77x faster                                             |
| scimark_sor              | 183 ms                                                       | 107 ms: 1.71x faster                                             |
| richards                 | 76.3 ms                                                      | 44.7 ms: 1.71x faster                                            |
| scimark_lu               | 165 ms                                                       | 96.7 ms: 1.70x faster                                            |
| chaos                    | 106 ms                                                       | 63.4 ms: 1.67x faster                                            |
| raytrace                 | 497 ms                                                       | 300 ms: 1.66x faster                                             |
| hexiom                   | 9.46 ms                                                      | 5.79 ms: 1.63x faster                                            |
| sqlglot_parse            | 2.27 ms                                                      | 1.39 ms: 1.63x faster                                            |
| scimark_monte_carlo      | 109 ms                                                       | 67.8 ms: 1.61x faster                                            |
| nbody                    | 134 ms                                                       | 84.2 ms: 1.59x faster                                            |
| pyflate                  | 698 ms                                                       | 439 ms: 1.59x faster                                             |
| generators               | 57.7 ms                                                      | 36.7 ms: 1.57x faster                                            |
| async_tree_none          | 700 ms                                                       | 457 ms: 1.53x faster                                             |
| async_tree_io            | 1.61 sec                                                     | 1.06 sec: 1.52x faster                                           |
| sqlglot_transpile        | 2.73 ms                                                      | 1.80 ms: 1.52x faster                                            |
| spectral_norm            | 141 ms                                                       | 93.4 ms: 1.51x faster                                            |
| unpickle_pure_python     | 315 us                                                       | 209 us: 1.51x faster                                             |
| async_tree_memoization   | 827 ms                                                       | 551 ms: 1.50x faster                                             |
| mako                     | 14.7 ms                                                      | 10.0 ms: 1.47x faster                                            |
| crypto_pyaes             | 118 ms                                                       | 80.9 ms: 1.46x faster                                            |
| fannkuch                 | 488 ms                                                       | 343 ms: 1.42x faster                                             |
| logging_simple           | 9.06 us                                                      | 6.49 us: 1.40x faster                                            |
| pickle_pure_python       | 453 us                                                       | 326 us: 1.39x faster                                             |
| coroutines               | 30.9 ms                                                      | 22.4 ms: 1.38x faster                                            |
| float                    | 109 ms                                                       | 78.8 ms: 1.38x faster                                            |
| logging_format           | 9.82 us                                                      | 7.13 us: 1.38x faster                                            |
| json_dumps               | 14.2 ms                                                      | 10.4 ms: 1.37x faster                                            |
| tomli_loads              | 2.96 sec                                                     | 2.17 sec: 1.36x faster                                           |
| deepcopy_memo            | 50.5 us                                                      | 37.4 us: 1.35x faster                                            |
| bench_mp_pool            | 6.82 ms                                                      | 5.05 ms: 1.35x faster                                            |
| async_tree_cpu_io_mixed  | 946 ms                                                       | 704 ms: 1.34x faster                                             |
| regex_compile            | 192 ms                                                       | 144 ms: 1.34x faster                                             |
| tornado_http             | 157 ms                                                       | 118 ms: 1.32x faster                                             |
| pprint_pformat           | 2.15 sec                                                     | 1.63 sec: 1.32x faster                                           |
| xml_etree_process        | 76.4 ms                                                      | 58.2 ms: 1.31x faster                                            |
| pprint_safe_repr         | 1.04 sec                                                     | 799 ms: 1.30x faster                                             |
| pycparser                | 1.65 sec                                                     | 1.27 sec: 1.29x faster                                           |
| sqlglot_normalize        | 146 ms                                                       | 116 ms: 1.26x faster                                             |
| comprehensions           | 27.0 us                                                      | 21.7 us: 1.25x faster                                            |
| nqueens                  | 112 ms                                                       | 90.2 ms: 1.24x faster                                            |
| 2to3                     | 349 ms                                                       | 283 ms: 1.24x faster                                             |
| deepcopy                 | 459 us                                                       | 376 us: 1.22x faster                                             |
| unpack_sequence          | 60.3 ns                                                      | 49.4 ns: 1.22x faster                                            |
| sqlglot_optimize         | 69.9 ms                                                      | 57.4 ms: 1.22x faster                                            |
| json_loads               | 30.0 us                                                      | 24.7 us: 1.21x faster                                            |
| dulwich_log              | 80.0 ms                                                      | 66.1 ms: 1.21x faster                                            |
| scimark_fft              | 363 ms                                                       | 304 ms: 1.19x faster                                             |
| bench_thread_pool        | 1.13 ms                                                      | 953 us: 1.19x faster                                             |
| docutils                 | 3.42 sec                                                     | 2.87 sec: 1.19x faster                                           |
| mdp                      | 2.94 sec                                                     | 2.49 sec: 1.18x faster                                           |
| scimark_sparse_mat_mult  | 5.21 ms                                                      | 4.43 ms: 1.18x faster                                            |
| deepcopy_reduce          | 4.00 us                                                      | 3.41 us: 1.17x faster                                            |
| json                     | 5.91 ms                                                      | 5.18 ms: 1.14x faster                                            |
| regex_v8                 | 27.1 ms                                                      | 23.9 ms: 1.13x faster                                            |
| pathlib                  | 21.2 ms                                                      | 19.2 ms: 1.10x faster                                            |
| meteor_contest           | 138 ms                                                       | 125 ms: 1.10x faster                                             |
| async_generators         | 418 ms                                                       | 382 ms: 1.10x faster                                             |
| create_gc_cycles         | 1.79 ms                                                      | 1.64 ms: 1.09x faster                                            |
| regex_dna                | 260 ms                                                       | 238 ms: 1.09x faster                                             |
| xml_etree_generate       | 93.1 ms                                                      | 85.3 ms: 1.09x faster                                            |
| sqlite_synth             | 2.97 us                                                      | 2.72 us: 1.09x faster                                            |
| xml_etree_parse          | 159 ms                                                       | 150 ms: 1.06x faster                                             |
| pidigits                 | 270 ms                                                       | 260 ms: 1.04x faster                                             |
| xml_etree_iterparse      | 110 ms                                                       | 106 ms: 1.03x faster                                             |
| telco                    | 7.21 ms                                                      | 7.07 ms: 1.02x faster                                            |
| python_startup           | 11.5 ms                                                      | 11.4 ms: 1.01x faster                                            |
| pickle                   | 10.1 us                                                      | 10.3 us: 1.02x slower                                            |
| unpickle_list            | 4.45 us                                                      | 4.65 us: 1.05x slower                                            |
| unpickle                 | 13.9 us                                                      | 14.6 us: 1.05x slower                                            |
| pickle_list              | 4.23 us                                                      | 4.43 us: 1.05x slower                                            |
| pickle_dict              | 30.4 us                                                      | 33.6 us: 1.11x slower                                            |
| gc_traversal             | 3.63 ms                                                      | 4.06 ms: 1.12x slower                                            |
| regex_effbot             | 3.10 ms                                                      | 3.48 ms: 1.12x slower                                            |
| python_startup_no_site   | 7.35 ms                                                      | 8.43 ms: 1.15x slower                                            |
| dask                     | 469 ms                                                       | 562 ms: 1.20x slower                                             |
| coverage                 | 65.9 ms                                                      | 89.0 ms: 1.35x slower                                            |
| Geometric mean           | (ref)                                                        | 1.30x faster                                                     |

Benchmark hidden because not significant (1): mypy2
Ignored benchmarks (17) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, asyncio_websockets, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.28x
- 95% likely to have a speedup of 1.26x
- 99% likely to have a speedup of 1.23x
