
# Results vs. 3.11.0

- fork: python
- ref: 3.12
- machine: linux-x86_64
- commit hash: e9a9052
- commit date: 2023-09-15
- overall geometric mean: 1.06x faster
- HPT reliability: 99.60%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230915-pythonperf2-x86_64-python-3.12-3.12.0rc2+-e9a9052 |
|----------------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| 2to3           | 288 ms                                                       | 285 ms: 1.01x faster                                          |
| docutils       | 2.86 sec                                                     | 2.88 sec: 1.01x slower                                        |
| Geometric mean | (ref)                                                        | 1.00x slower                                                  |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230915-pythonperf2-x86_64-python-3.12-3.12.0rc2+-e9a9052 |
|----------------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| pidigits       | 251 ms                                                       | 264 ms: 1.05x slower                                          |
| float          | 74.2 ms                                                      | 78.1 ms: 1.05x slower                                         |
| Geometric mean | (ref)                                                        | 1.03x slower                                                  |

Benchmark hidden because not significant (1): nbody

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230915-pythonperf2-x86_64-python-3.12-3.12.0rc2+-e9a9052 |
|----------------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| regex_compile  | 158 ms                                                       | 145 ms: 1.09x faster                                          |
| regex_v8       | 23.9 ms                                                      | 23.2 ms: 1.03x faster                                         |
| regex_effbot   | 3.50 ms                                                      | 3.62 ms: 1.03x slower                                         |
| regex_dna      | 227 ms                                                       | 237 ms: 1.04x slower                                          |
| Geometric mean | (ref)                                                        | 1.01x faster                                                  |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230915-pythonperf2-x86_64-python-3.12-3.12.0rc2+-e9a9052 |
|----------------------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| json_dumps           | 13.4 ms                                                      | 10.3 ms: 1.30x faster                                         |
| json_loads           | 28.7 us                                                      | 24.5 us: 1.17x faster                                         |
| unpickle_pure_python | 241 us                                                       | 207 us: 1.16x faster                                          |
| xml_etree_parse      | 158 ms                                                       | 148 ms: 1.06x faster                                          |
| tomli_loads          | 2.26 sec                                                     | 2.13 sec: 1.06x faster                                        |
| pickle_pure_python   | 319 us                                                       | 318 us: 1.00x faster                                          |
| xml_etree_iterparse  | 104 ms                                                       | 106 ms: 1.02x slower                                          |
| xml_etree_process    | 56.5 ms                                                      | 59.0 ms: 1.04x slower                                         |
| pickle_dict          | 30.8 us                                                      | 32.4 us: 1.05x slower                                         |
| unpickle_list        | 4.53 us                                                      | 4.82 us: 1.06x slower                                         |
| xml_etree_generate   | 80.5 ms                                                      | 86.1 ms: 1.07x slower                                         |
| pickle               | 9.64 us                                                      | 10.3 us: 1.07x slower                                         |
| unpickle             | 13.4 us                                                      | 14.5 us: 1.08x slower                                         |
| pickle_list          | 3.83 us                                                      | 4.51 us: 1.18x slower                                         |
| Geometric mean       | (ref)                                                        | 1.01x faster                                                  |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230915-pythonperf2-x86_64-python-3.12-3.12.0rc2+-e9a9052 |
|------------------------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| python_startup         | 10.8 ms                                                      | 11.7 ms: 1.09x slower                                         |
| python_startup_no_site | 7.76 ms                                                      | 8.69 ms: 1.12x slower                                         |
| Geometric mean         | (ref)                                                        | 1.11x slower                                                  |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230915-pythonperf2-x86_64-python-3.12-3.12.0rc2+-e9a9052 |
|-----------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| mako      | 11.0 ms                                                      | 9.97 ms: 1.10x faster                                         |

All benchmarks:
===============

| Benchmark                | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230915-pythonperf2-x86_64-python-3.12-3.12.0rc2+-e9a9052 |
|--------------------------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| typing_runtime_protocols | 523 us                                                       | 156 us: 3.34x faster                                          |
| asyncio_tcp              | 753 ms                                                       | 382 ms: 1.97x faster                                          |
| asyncio_tcp_ssl          | 3.08 sec                                                     | 1.58 sec: 1.95x faster                                        |
| generators               | 56.0 ms                                                      | 36.6 ms: 1.53x faster                                         |
| json_dumps               | 13.4 ms                                                      | 10.3 ms: 1.30x faster                                         |
| chaos                    | 80.9 ms                                                      | 63.2 ms: 1.28x faster                                         |
| fannkuch                 | 429 ms                                                       | 348 ms: 1.23x faster                                          |
| mypy2                    | 451 ms                                                       | 367 ms: 1.23x faster                                          |
| hexiom                   | 7.13 ms                                                      | 5.89 ms: 1.21x faster                                         |
| coroutines               | 27.6 ms                                                      | 23.0 ms: 1.20x faster                                         |
| deltablue                | 4.00 ms                                                      | 3.34 ms: 1.20x faster                                         |
| richards_super           | 61.0 ms                                                      | 51.6 ms: 1.18x faster                                         |
| json_loads               | 28.7 us                                                      | 24.5 us: 1.17x faster                                         |
| scimark_lu               | 115 ms                                                       | 98.2 ms: 1.17x faster                                         |
| unpickle_pure_python     | 241 us                                                       | 207 us: 1.16x faster                                          |
| nqueens                  | 103 ms                                                       | 89.4 ms: 1.15x faster                                         |
| comprehensions           | 24.6 us                                                      | 21.9 us: 1.12x faster                                         |
| async_tree_memoization   | 630 ms                                                       | 561 ms: 1.12x faster                                          |
| async_tree_none          | 519 ms                                                       | 466 ms: 1.11x faster                                          |
| mako                     | 11.0 ms                                                      | 9.97 ms: 1.10x faster                                         |
| go                       | 164 ms                                                       | 149 ms: 1.10x faster                                          |
| sqlglot_parse            | 1.53 ms                                                      | 1.39 ms: 1.10x faster                                         |
| json                     | 5.65 ms                                                      | 5.15 ms: 1.10x faster                                         |
| mdp                      | 2.75 sec                                                     | 2.50 sec: 1.10x faster                                        |
| async_tree_io            | 1.17 sec                                                     | 1.07 sec: 1.09x faster                                        |
| deepcopy                 | 399 us                                                       | 367 us: 1.09x faster                                          |
| regex_compile            | 158 ms                                                       | 145 ms: 1.09x faster                                          |
| richards                 | 48.3 ms                                                      | 45.0 ms: 1.07x faster                                         |
| sqlglot_normalize        | 126 ms                                                       | 118 ms: 1.07x faster                                          |
| sqlglot_transpile        | 1.92 ms                                                      | 1.79 ms: 1.07x faster                                         |
| xml_etree_parse          | 158 ms                                                       | 148 ms: 1.06x faster                                          |
| tomli_loads              | 2.26 sec                                                     | 2.13 sec: 1.06x faster                                        |
| logging_silent           | 101 ns                                                       | 95.1 ns: 1.06x faster                                         |
| deepcopy_memo            | 38.8 us                                                      | 36.7 us: 1.06x faster                                         |
| logging_format           | 8.11 us                                                      | 7.70 us: 1.05x faster                                         |
| pycparser                | 1.32 sec                                                     | 1.26 sec: 1.05x faster                                        |
| async_tree_cpu_io_mixed  | 749 ms                                                       | 715 ms: 1.05x faster                                          |
| bench_thread_pool        | 1.01 ms                                                      | 966 us: 1.05x faster                                          |
| deepcopy_reduce          | 3.51 us                                                      | 3.38 us: 1.04x faster                                         |
| dulwich_log              | 68.4 ms                                                      | 65.9 ms: 1.04x faster                                         |
| sqlglot_optimize         | 59.8 ms                                                      | 57.8 ms: 1.03x faster                                         |
| meteor_contest           | 131 ms                                                       | 126 ms: 1.03x faster                                          |
| regex_v8                 | 23.9 ms                                                      | 23.2 ms: 1.03x faster                                         |
| crypto_pyaes             | 83.4 ms                                                      | 81.4 ms: 1.03x faster                                         |
| spectral_norm            | 93.3 ms                                                      | 91.1 ms: 1.02x faster                                         |
| scimark_sor              | 111 ms                                                       | 109 ms: 1.02x faster                                          |
| logging_simple           | 7.19 us                                                      | 7.04 us: 1.02x faster                                         |
| 2to3                     | 288 ms                                                       | 285 ms: 1.01x faster                                          |
| pickle_pure_python       | 319 us                                                       | 318 us: 1.00x faster                                          |
| docutils                 | 2.86 sec                                                     | 2.88 sec: 1.01x slower                                        |
| pprint_pformat           | 1.63 sec                                                     | 1.66 sec: 1.02x slower                                        |
| xml_etree_iterparse      | 104 ms                                                       | 106 ms: 1.02x slower                                          |
| telco                    | 6.86 ms                                                      | 7.07 ms: 1.03x slower                                         |
| scimark_monte_carlo      | 68.2 ms                                                      | 70.5 ms: 1.03x slower                                         |
| regex_effbot             | 3.50 ms                                                      | 3.62 ms: 1.03x slower                                         |
| gc_traversal             | 3.85 ms                                                      | 3.98 ms: 1.04x slower                                         |
| pathlib                  | 19.1 ms                                                      | 19.7 ms: 1.04x slower                                         |
| pprint_safe_repr         | 784 ms                                                       | 813 ms: 1.04x slower                                          |
| regex_dna                | 227 ms                                                       | 237 ms: 1.04x slower                                          |
| xml_etree_process        | 56.5 ms                                                      | 59.0 ms: 1.04x slower                                         |
| create_gc_cycles         | 1.61 ms                                                      | 1.69 ms: 1.05x slower                                         |
| pidigits                 | 251 ms                                                       | 264 ms: 1.05x slower                                          |
| float                    | 74.2 ms                                                      | 78.1 ms: 1.05x slower                                         |
| scimark_fft              | 285 ms                                                       | 300 ms: 1.05x slower                                          |
| pickle_dict              | 30.8 us                                                      | 32.4 us: 1.05x slower                                         |
| unpickle_list            | 4.53 us                                                      | 4.82 us: 1.06x slower                                         |
| xml_etree_generate       | 80.5 ms                                                      | 86.1 ms: 1.07x slower                                         |
| pickle                   | 9.64 us                                                      | 10.3 us: 1.07x slower                                         |
| unpickle                 | 13.4 us                                                      | 14.5 us: 1.08x slower                                         |
| scimark_sparse_mat_mult  | 4.05 ms                                                      | 4.37 ms: 1.08x slower                                         |
| coverage                 | 84.8 ms                                                      | 91.8 ms: 1.08x slower                                         |
| python_startup           | 10.8 ms                                                      | 11.7 ms: 1.09x slower                                         |
| sqlite_synth             | 2.50 us                                                      | 2.73 us: 1.09x slower                                         |
| python_startup_no_site   | 7.76 ms                                                      | 8.69 ms: 1.12x slower                                         |
| pickle_list              | 3.83 us                                                      | 4.51 us: 1.18x slower                                         |
| unpack_sequence          | 45.6 ns                                                      | 55.2 ns: 1.21x slower                                         |
| async_generators         | 316 ms                                                       | 387 ms: 1.22x slower                                          |
| dask                     | 410 ms                                                       | 565 ms: 1.38x slower                                          |
| Geometric mean           | (ref)                                                        | 1.06x faster                                                  |

Benchmark hidden because not significant (5): nbody, bench_mp_pool, pyflate, raytrace, tornado_http
Ignored benchmarks (16) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 99.60% likely to be faster
- 90% likely to have a speedup of 1.02x
- 95% likely to have a speedup of 1.01x
- 99% likely to have a speedup of 1.00x
