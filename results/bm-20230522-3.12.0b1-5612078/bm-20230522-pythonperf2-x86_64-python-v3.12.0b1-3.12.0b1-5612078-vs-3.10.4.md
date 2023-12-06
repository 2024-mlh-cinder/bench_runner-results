
# Results vs. 3.10.4

- fork: python
- ref: v3.12.0b1
- machine: linux-x86_64
- commit hash: 5612078
- commit date: 2023-05-22
- overall geometric mean: 1.30x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.23x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230522-pythonperf2-x86_64-python-v3.12.0b1-3.12.0b1-5612078 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| 2to3           | 349 ms                                                       | 284 ms: 1.23x faster                                             |
| docutils       | 3.42 sec                                                     | 2.87 sec: 1.19x faster                                           |
| tornado_http   | 157 ms                                                       | 115 ms: 1.36x faster                                             |
| Geometric mean | (ref)                                                        | 1.26x faster                                                     |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230522-pythonperf2-x86_64-python-v3.12.0b1-3.12.0b1-5612078 |
|-------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| async_tree_none         | 700 ms                                                       | 453 ms: 1.55x faster                                             |
| async_tree_io           | 1.61 sec                                                     | 1.05 sec: 1.54x faster                                           |
| async_tree_memoization  | 827 ms                                                       | 544 ms: 1.52x faster                                             |
| async_tree_cpu_io_mixed | 946 ms                                                       | 696 ms: 1.36x faster                                             |
| Geometric mean          | (ref)                                                        | 1.49x faster                                                     |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230522-pythonperf2-x86_64-python-v3.12.0b1-3.12.0b1-5612078 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| nbody          | 134 ms                                                       | 84.7 ms: 1.58x faster                                            |
| float          | 109 ms                                                       | 78.6 ms: 1.38x faster                                            |
| pidigits       | 270 ms                                                       | 261 ms: 1.04x faster                                             |
| Geometric mean | (ref)                                                        | 1.31x faster                                                     |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230522-pythonperf2-x86_64-python-v3.12.0b1-3.12.0b1-5612078 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| regex_compile  | 192 ms                                                       | 143 ms: 1.34x faster                                             |
| regex_v8       | 27.1 ms                                                      | 22.8 ms: 1.19x faster                                            |
| regex_dna      | 260 ms                                                       | 237 ms: 1.10x faster                                             |
| regex_effbot   | 3.10 ms                                                      | 3.49 ms: 1.13x slower                                            |
| Geometric mean | (ref)                                                        | 1.11x faster                                                     |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230522-pythonperf2-x86_64-python-v3.12.0b1-3.12.0b1-5612078 |
|----------------------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| unpickle_pure_python | 315 us                                                       | 204 us: 1.55x faster                                             |
| json_dumps           | 14.2 ms                                                      | 10.2 ms: 1.40x faster                                            |
| tomli_loads          | 2.96 sec                                                     | 2.12 sec: 1.39x faster                                           |
| pickle_pure_python   | 453 us                                                       | 325 us: 1.39x faster                                             |
| xml_etree_process    | 76.4 ms                                                      | 59.0 ms: 1.30x faster                                            |
| json_loads           | 30.0 us                                                      | 24.2 us: 1.24x faster                                            |
| xml_etree_parse      | 159 ms                                                       | 147 ms: 1.09x faster                                             |
| xml_etree_generate   | 93.1 ms                                                      | 86.8 ms: 1.07x faster                                            |
| xml_etree_iterparse  | 110 ms                                                       | 106 ms: 1.03x faster                                             |
| pickle               | 10.1 us                                                      | 10.1 us: 1.00x faster                                            |
| pickle_list          | 4.23 us                                                      | 4.37 us: 1.03x slower                                            |
| unpickle             | 13.9 us                                                      | 14.4 us: 1.04x slower                                            |
| unpickle_list        | 4.45 us                                                      | 4.72 us: 1.06x slower                                            |
| pickle_dict          | 30.4 us                                                      | 33.2 us: 1.09x slower                                            |
| Geometric mean       | (ref)                                                        | 1.14x faster                                                     |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230522-pythonperf2-x86_64-python-v3.12.0b1-3.12.0b1-5612078 |
|------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| python_startup         | 11.5 ms                                                      | 11.5 ms: 1.00x faster                                            |
| python_startup_no_site | 7.35 ms                                                      | 8.50 ms: 1.16x slower                                            |
| Geometric mean         | (ref)                                                        | 1.07x slower                                                     |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230522-pythonperf2-x86_64-python-v3.12.0b1-3.12.0b1-5612078 |
|-----------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| mako      | 14.7 ms                                                      | 9.94 ms: 1.48x faster                                            |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230522-pythonperf2-x86_64-python-v3.12.0b1-3.12.0b1-5612078 |
|--------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| typing_runtime_protocols | 533 us                                                       | 149 us: 3.58x faster                                             |
| deltablue                | 7.43 ms                                                      | 3.22 ms: 2.31x faster                                            |
| asyncio_tcp              | 785 ms                                                       | 380 ms: 2.07x faster                                             |
| asyncio_tcp_ssl          | 3.13 sec                                                     | 1.57 sec: 1.99x faster                                           |
| richards_super           | 93.0 ms                                                      | 51.1 ms: 1.82x faster                                            |
| logging_silent           | 168 ns                                                       | 93.0 ns: 1.80x faster                                            |
| go                       | 258 ms                                                       | 148 ms: 1.75x faster                                             |
| richards                 | 76.3 ms                                                      | 45.0 ms: 1.69x faster                                            |
| scimark_sor              | 183 ms                                                       | 109 ms: 1.68x faster                                             |
| scimark_lu               | 165 ms                                                       | 98.0 ms: 1.68x faster                                            |
| raytrace                 | 497 ms                                                       | 297 ms: 1.68x faster                                             |
| chaos                    | 106 ms                                                       | 64.0 ms: 1.66x faster                                            |
| sqlglot_parse            | 2.27 ms                                                      | 1.38 ms: 1.64x faster                                            |
| generators               | 57.7 ms                                                      | 35.1 ms: 1.64x faster                                            |
| hexiom                   | 9.46 ms                                                      | 5.88 ms: 1.61x faster                                            |
| scimark_monte_carlo      | 109 ms                                                       | 68.2 ms: 1.60x faster                                            |
| nbody                    | 134 ms                                                       | 84.7 ms: 1.58x faster                                            |
| pyflate                  | 698 ms                                                       | 443 ms: 1.58x faster                                             |
| unpickle_pure_python     | 315 us                                                       | 204 us: 1.55x faster                                             |
| async_tree_none          | 700 ms                                                       | 453 ms: 1.55x faster                                             |
| async_tree_io            | 1.61 sec                                                     | 1.05 sec: 1.54x faster                                           |
| sqlglot_transpile        | 2.73 ms                                                      | 1.79 ms: 1.53x faster                                            |
| async_tree_memoization   | 827 ms                                                       | 544 ms: 1.52x faster                                             |
| spectral_norm            | 141 ms                                                       | 94.5 ms: 1.49x faster                                            |
| mako                     | 14.7 ms                                                      | 9.94 ms: 1.48x faster                                            |
| crypto_pyaes             | 118 ms                                                       | 82.5 ms: 1.43x faster                                            |
| json_dumps               | 14.2 ms                                                      | 10.2 ms: 1.40x faster                                            |
| tomli_loads              | 2.96 sec                                                     | 2.12 sec: 1.39x faster                                           |
| pickle_pure_python       | 453 us                                                       | 325 us: 1.39x faster                                             |
| coroutines               | 30.9 ms                                                      | 22.3 ms: 1.38x faster                                            |
| deepcopy_memo            | 50.5 us                                                      | 36.5 us: 1.38x faster                                            |
| float                    | 109 ms                                                       | 78.6 ms: 1.38x faster                                            |
| fannkuch                 | 488 ms                                                       | 355 ms: 1.38x faster                                             |
| logging_format           | 9.82 us                                                      | 7.14 us: 1.38x faster                                            |
| logging_simple           | 9.06 us                                                      | 6.60 us: 1.37x faster                                            |
| async_tree_cpu_io_mixed  | 946 ms                                                       | 696 ms: 1.36x faster                                             |
| tornado_http             | 157 ms                                                       | 115 ms: 1.36x faster                                             |
| regex_compile            | 192 ms                                                       | 143 ms: 1.34x faster                                             |
| pprint_pformat           | 2.15 sec                                                     | 1.65 sec: 1.30x faster                                           |
| pycparser                | 1.65 sec                                                     | 1.27 sec: 1.30x faster                                           |
| xml_etree_process        | 76.4 ms                                                      | 59.0 ms: 1.30x faster                                            |
| pprint_safe_repr         | 1.04 sec                                                     | 809 ms: 1.29x faster                                             |
| sqlglot_normalize        | 146 ms                                                       | 115 ms: 1.28x faster                                             |
| comprehensions           | 27.0 us                                                      | 21.6 us: 1.25x faster                                            |
| unpack_sequence          | 60.3 ns                                                      | 48.1 ns: 1.25x faster                                            |
| deepcopy                 | 459 us                                                       | 370 us: 1.24x faster                                             |
| nqueens                  | 112 ms                                                       | 90.2 ms: 1.24x faster                                            |
| json_loads               | 30.0 us                                                      | 24.2 us: 1.24x faster                                            |
| 2to3                     | 349 ms                                                       | 284 ms: 1.23x faster                                             |
| sqlglot_optimize         | 69.9 ms                                                      | 57.2 ms: 1.22x faster                                            |
| dulwich_log              | 80.0 ms                                                      | 66.1 ms: 1.21x faster                                            |
| bench_thread_pool        | 1.13 ms                                                      | 943 us: 1.20x faster                                             |
| scimark_sparse_mat_mult  | 5.21 ms                                                      | 4.38 ms: 1.19x faster                                            |
| scimark_fft              | 363 ms                                                       | 305 ms: 1.19x faster                                             |
| docutils                 | 3.42 sec                                                     | 2.87 sec: 1.19x faster                                           |
| deepcopy_reduce          | 4.00 us                                                      | 3.37 us: 1.19x faster                                            |
| regex_v8                 | 27.1 ms                                                      | 22.8 ms: 1.19x faster                                            |
| mdp                      | 2.94 sec                                                     | 2.53 sec: 1.16x faster                                           |
| json                     | 5.91 ms                                                      | 5.16 ms: 1.14x faster                                            |
| sqlite_synth             | 2.97 us                                                      | 2.68 us: 1.11x faster                                            |
| async_generators         | 418 ms                                                       | 379 ms: 1.10x faster                                             |
| pathlib                  | 21.2 ms                                                      | 19.3 ms: 1.10x faster                                            |
| regex_dna                | 260 ms                                                       | 237 ms: 1.10x faster                                             |
| xml_etree_parse          | 159 ms                                                       | 147 ms: 1.09x faster                                             |
| meteor_contest           | 138 ms                                                       | 127 ms: 1.08x faster                                             |
| xml_etree_generate       | 93.1 ms                                                      | 86.8 ms: 1.07x faster                                            |
| create_gc_cycles         | 1.79 ms                                                      | 1.68 ms: 1.07x faster                                            |
| pidigits                 | 270 ms                                                       | 261 ms: 1.04x faster                                             |
| xml_etree_iterparse      | 110 ms                                                       | 106 ms: 1.03x faster                                             |
| telco                    | 7.21 ms                                                      | 7.11 ms: 1.02x faster                                            |
| python_startup           | 11.5 ms                                                      | 11.5 ms: 1.00x faster                                            |
| pickle                   | 10.1 us                                                      | 10.1 us: 1.00x faster                                            |
| pickle_list              | 4.23 us                                                      | 4.37 us: 1.03x slower                                            |
| unpickle                 | 13.9 us                                                      | 14.4 us: 1.04x slower                                            |
| gc_traversal             | 3.63 ms                                                      | 3.79 ms: 1.04x slower                                            |
| unpickle_list            | 4.45 us                                                      | 4.72 us: 1.06x slower                                            |
| pickle_dict              | 30.4 us                                                      | 33.2 us: 1.09x slower                                            |
| regex_effbot             | 3.10 ms                                                      | 3.49 ms: 1.13x slower                                            |
| python_startup_no_site   | 7.35 ms                                                      | 8.50 ms: 1.16x slower                                            |
| dask                     | 469 ms                                                       | 551 ms: 1.17x slower                                             |
| bench_mp_pool            | 6.82 ms                                                      | 8.65 ms: 1.27x slower                                            |
| coverage                 | 65.9 ms                                                      | 88.0 ms: 1.34x slower                                            |
| Geometric mean           | (ref)                                                        | 1.30x faster                                                     |

Benchmark hidden because not significant (1): mypy2
Ignored benchmarks (17) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, asyncio_websockets, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.27x
- 95% likely to have a speedup of 1.26x
- 99% likely to have a speedup of 1.23x
