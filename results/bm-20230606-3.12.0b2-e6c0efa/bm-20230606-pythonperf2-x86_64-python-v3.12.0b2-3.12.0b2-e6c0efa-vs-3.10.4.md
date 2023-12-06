
# Results vs. 3.10.4

- fork: python
- ref: v3.12.0b2
- machine: linux-x86_64
- commit hash: e6c0efa
- commit date: 2023-06-06
- overall geometric mean: 1.31x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.23x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230606-pythonperf2-x86_64-python-v3.12.0b2-3.12.0b2-e6c0efa |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| 2to3           | 349 ms                                                       | 285 ms: 1.23x faster                                             |
| docutils       | 3.42 sec                                                     | 2.88 sec: 1.19x faster                                           |
| tornado_http   | 157 ms                                                       | 121 ms: 1.30x faster                                             |
| Geometric mean | (ref)                                                        | 1.24x faster                                                     |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230606-pythonperf2-x86_64-python-v3.12.0b2-3.12.0b2-e6c0efa |
|-------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| async_tree_none         | 700 ms                                                       | 452 ms: 1.55x faster                                             |
| async_tree_io           | 1.61 sec                                                     | 1.04 sec: 1.54x faster                                           |
| async_tree_memoization  | 827 ms                                                       | 546 ms: 1.51x faster                                             |
| async_tree_cpu_io_mixed | 946 ms                                                       | 697 ms: 1.36x faster                                             |
| Geometric mean          | (ref)                                                        | 1.49x faster                                                     |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230606-pythonperf2-x86_64-python-v3.12.0b2-3.12.0b2-e6c0efa |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| nbody          | 134 ms                                                       | 83.7 ms: 1.60x faster                                            |
| float          | 109 ms                                                       | 77.3 ms: 1.40x faster                                            |
| pidigits       | 270 ms                                                       | 259 ms: 1.04x faster                                             |
| Geometric mean | (ref)                                                        | 1.33x faster                                                     |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230606-pythonperf2-x86_64-python-v3.12.0b2-3.12.0b2-e6c0efa |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| regex_compile  | 192 ms                                                       | 144 ms: 1.33x faster                                             |
| regex_v8       | 27.1 ms                                                      | 23.6 ms: 1.15x faster                                            |
| regex_dna      | 260 ms                                                       | 245 ms: 1.06x faster                                             |
| regex_effbot   | 3.10 ms                                                      | 3.55 ms: 1.15x slower                                            |
| Geometric mean | (ref)                                                        | 1.09x faster                                                     |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230606-pythonperf2-x86_64-python-v3.12.0b2-3.12.0b2-e6c0efa |
|----------------------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| unpickle_pure_python | 315 us                                                       | 205 us: 1.54x faster                                             |
| pickle_pure_python   | 453 us                                                       | 324 us: 1.40x faster                                             |
| json_dumps           | 14.2 ms                                                      | 10.2 ms: 1.39x faster                                            |
| tomli_loads          | 2.96 sec                                                     | 2.19 sec: 1.35x faster                                           |
| xml_etree_process    | 76.4 ms                                                      | 58.8 ms: 1.30x faster                                            |
| json_loads           | 30.0 us                                                      | 24.5 us: 1.23x faster                                            |
| xml_etree_generate   | 93.1 ms                                                      | 85.6 ms: 1.09x faster                                            |
| xml_etree_parse      | 159 ms                                                       | 148 ms: 1.08x faster                                             |
| xml_etree_iterparse  | 110 ms                                                       | 104 ms: 1.06x faster                                             |
| pickle               | 10.1 us                                                      | 10.0 us: 1.00x faster                                            |
| pickle_list          | 4.23 us                                                      | 4.27 us: 1.01x slower                                            |
| pickle_dict          | 30.4 us                                                      | 31.2 us: 1.02x slower                                            |
| unpickle             | 13.9 us                                                      | 14.6 us: 1.05x slower                                            |
| unpickle_list        | 4.45 us                                                      | 4.71 us: 1.06x slower                                            |
| Geometric mean       | (ref)                                                        | 1.15x faster                                                     |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230606-pythonperf2-x86_64-python-v3.12.0b2-3.12.0b2-e6c0efa |
|------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| python_startup         | 11.5 ms                                                      | 11.4 ms: 1.01x faster                                            |
| python_startup_no_site | 7.35 ms                                                      | 8.45 ms: 1.15x slower                                            |
| Geometric mean         | (ref)                                                        | 1.07x slower                                                     |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230606-pythonperf2-x86_64-python-v3.12.0b2-3.12.0b2-e6c0efa |
|-----------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| mako      | 14.7 ms                                                      | 9.93 ms: 1.48x faster                                            |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230606-pythonperf2-x86_64-python-v3.12.0b2-3.12.0b2-e6c0efa |
|--------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| typing_runtime_protocols | 533 us                                                       | 150 us: 3.55x faster                                             |
| deltablue                | 7.43 ms                                                      | 3.25 ms: 2.29x faster                                            |
| asyncio_tcp              | 785 ms                                                       | 379 ms: 2.07x faster                                             |
| asyncio_tcp_ssl          | 3.13 sec                                                     | 1.57 sec: 2.00x faster                                           |
| richards_super           | 93.0 ms                                                      | 51.0 ms: 1.82x faster                                            |
| logging_silent           | 168 ns                                                       | 93.8 ns: 1.79x faster                                            |
| go                       | 258 ms                                                       | 147 ms: 1.76x faster                                             |
| scimark_sor              | 183 ms                                                       | 107 ms: 1.72x faster                                             |
| scimark_lu               | 165 ms                                                       | 96.3 ms: 1.71x faster                                            |
| richards                 | 76.3 ms                                                      | 45.5 ms: 1.68x faster                                            |
| chaos                    | 106 ms                                                       | 63.6 ms: 1.67x faster                                            |
| sqlglot_parse            | 2.27 ms                                                      | 1.40 ms: 1.63x faster                                            |
| generators               | 57.7 ms                                                      | 35.5 ms: 1.63x faster                                            |
| raytrace                 | 497 ms                                                       | 307 ms: 1.62x faster                                             |
| nbody                    | 134 ms                                                       | 83.7 ms: 1.60x faster                                            |
| hexiom                   | 9.46 ms                                                      | 5.95 ms: 1.59x faster                                            |
| pyflate                  | 698 ms                                                       | 441 ms: 1.58x faster                                             |
| scimark_monte_carlo      | 109 ms                                                       | 69.2 ms: 1.58x faster                                            |
| async_tree_none          | 700 ms                                                       | 452 ms: 1.55x faster                                             |
| spectral_norm            | 141 ms                                                       | 91.6 ms: 1.54x faster                                            |
| unpickle_pure_python     | 315 us                                                       | 205 us: 1.54x faster                                             |
| async_tree_io            | 1.61 sec                                                     | 1.04 sec: 1.54x faster                                           |
| sqlglot_transpile        | 2.73 ms                                                      | 1.80 ms: 1.52x faster                                            |
| async_tree_memoization   | 827 ms                                                       | 546 ms: 1.51x faster                                             |
| mako                     | 14.7 ms                                                      | 9.93 ms: 1.48x faster                                            |
| crypto_pyaes             | 118 ms                                                       | 81.2 ms: 1.45x faster                                            |
| fannkuch                 | 488 ms                                                       | 343 ms: 1.43x faster                                             |
| deepcopy_memo            | 50.5 us                                                      | 36.0 us: 1.40x faster                                            |
| float                    | 109 ms                                                       | 77.3 ms: 1.40x faster                                            |
| pickle_pure_python       | 453 us                                                       | 324 us: 1.40x faster                                             |
| json_dumps               | 14.2 ms                                                      | 10.2 ms: 1.39x faster                                            |
| coroutines               | 30.9 ms                                                      | 22.3 ms: 1.38x faster                                            |
| async_tree_cpu_io_mixed  | 946 ms                                                       | 697 ms: 1.36x faster                                             |
| tomli_loads              | 2.96 sec                                                     | 2.19 sec: 1.35x faster                                           |
| logging_simple           | 9.06 us                                                      | 6.73 us: 1.35x faster                                            |
| logging_format           | 9.82 us                                                      | 7.35 us: 1.34x faster                                            |
| regex_compile            | 192 ms                                                       | 144 ms: 1.33x faster                                             |
| pprint_pformat           | 2.15 sec                                                     | 1.62 sec: 1.33x faster                                           |
| pycparser                | 1.65 sec                                                     | 1.24 sec: 1.33x faster                                           |
| pprint_safe_repr         | 1.04 sec                                                     | 792 ms: 1.31x faster                                             |
| xml_etree_process        | 76.4 ms                                                      | 58.8 ms: 1.30x faster                                            |
| tornado_http             | 157 ms                                                       | 121 ms: 1.30x faster                                             |
| bench_mp_pool            | 6.82 ms                                                      | 5.41 ms: 1.26x faster                                            |
| sqlglot_normalize        | 146 ms                                                       | 116 ms: 1.26x faster                                             |
| comprehensions           | 27.0 us                                                      | 21.6 us: 1.25x faster                                            |
| nqueens                  | 112 ms                                                       | 89.5 ms: 1.25x faster                                            |
| deepcopy                 | 459 us                                                       | 369 us: 1.24x faster                                             |
| 2to3                     | 349 ms                                                       | 285 ms: 1.23x faster                                             |
| json_loads               | 30.0 us                                                      | 24.5 us: 1.23x faster                                            |
| scimark_fft              | 363 ms                                                       | 296 ms: 1.22x faster                                             |
| sqlglot_optimize         | 69.9 ms                                                      | 57.5 ms: 1.21x faster                                            |
| dulwich_log              | 80.0 ms                                                      | 65.9 ms: 1.21x faster                                            |
| scimark_sparse_mat_mult  | 5.21 ms                                                      | 4.29 ms: 1.21x faster                                            |
| unpack_sequence          | 60.3 ns                                                      | 49.8 ns: 1.21x faster                                            |
| docutils                 | 3.42 sec                                                     | 2.88 sec: 1.19x faster                                           |
| bench_thread_pool        | 1.13 ms                                                      | 960 us: 1.18x faster                                             |
| deepcopy_reduce          | 4.00 us                                                      | 3.40 us: 1.17x faster                                            |
| mdp                      | 2.94 sec                                                     | 2.51 sec: 1.17x faster                                           |
| regex_v8                 | 27.1 ms                                                      | 23.6 ms: 1.15x faster                                            |
| json                     | 5.91 ms                                                      | 5.19 ms: 1.14x faster                                            |
| create_gc_cycles         | 1.79 ms                                                      | 1.62 ms: 1.10x faster                                            |
| pathlib                  | 21.2 ms                                                      | 19.3 ms: 1.10x faster                                            |
| sqlite_synth             | 2.97 us                                                      | 2.71 us: 1.09x faster                                            |
| xml_etree_generate       | 93.1 ms                                                      | 85.6 ms: 1.09x faster                                            |
| meteor_contest           | 138 ms                                                       | 127 ms: 1.08x faster                                             |
| xml_etree_parse          | 159 ms                                                       | 148 ms: 1.08x faster                                             |
| async_generators         | 418 ms                                                       | 389 ms: 1.07x faster                                             |
| regex_dna                | 260 ms                                                       | 245 ms: 1.06x faster                                             |
| xml_etree_iterparse      | 110 ms                                                       | 104 ms: 1.06x faster                                             |
| pidigits                 | 270 ms                                                       | 259 ms: 1.04x faster                                             |
| telco                    | 7.21 ms                                                      | 7.08 ms: 1.02x faster                                            |
| python_startup           | 11.5 ms                                                      | 11.4 ms: 1.01x faster                                            |
| pickle                   | 10.1 us                                                      | 10.0 us: 1.00x faster                                            |
| pickle_list              | 4.23 us                                                      | 4.27 us: 1.01x slower                                            |
| pickle_dict              | 30.4 us                                                      | 31.2 us: 1.02x slower                                            |
| gc_traversal             | 3.63 ms                                                      | 3.79 ms: 1.05x slower                                            |
| unpickle                 | 13.9 us                                                      | 14.6 us: 1.05x slower                                            |
| unpickle_list            | 4.45 us                                                      | 4.71 us: 1.06x slower                                            |
| regex_effbot             | 3.10 ms                                                      | 3.55 ms: 1.15x slower                                            |
| python_startup_no_site   | 7.35 ms                                                      | 8.45 ms: 1.15x slower                                            |
| dask                     | 469 ms                                                       | 563 ms: 1.20x slower                                             |
| coverage                 | 65.9 ms                                                      | 88.5 ms: 1.34x slower                                            |
| Geometric mean           | (ref)                                                        | 1.31x faster                                                     |

Benchmark hidden because not significant (1): mypy2
Ignored benchmarks (17) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, asyncio_websockets, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.28x
- 95% likely to have a speedup of 1.26x
- 99% likely to have a speedup of 1.23x
