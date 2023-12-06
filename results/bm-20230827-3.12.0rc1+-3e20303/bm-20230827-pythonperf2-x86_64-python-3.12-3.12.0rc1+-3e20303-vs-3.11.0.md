
# Results vs. 3.11.0

- fork: python
- ref: 3.12
- machine: linux-x86_64
- commit hash: 3e20303
- commit date: 2023-08-27
- overall geometric mean: 1.07x faster
- HPT reliability: 99.94%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230827-pythonperf2-x86_64-python-3.12-3.12.0rc1+-3e20303 |
|----------------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| 2to3           | 288 ms                                                       | 284 ms: 1.01x faster                                          |
| docutils       | 2.86 sec                                                     | 2.91 sec: 1.02x slower                                        |
| Geometric mean | (ref)                                                        | 1.00x slower                                                  |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230827-pythonperf2-x86_64-python-3.12-3.12.0rc1+-3e20303 |
|----------------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| nbody          | 90.7 ms                                                      | 88.2 ms: 1.03x faster                                         |
| pidigits       | 251 ms                                                       | 259 ms: 1.03x slower                                          |
| float          | 74.2 ms                                                      | 78.3 ms: 1.06x slower                                         |
| Geometric mean | (ref)                                                        | 1.02x slower                                                  |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230827-pythonperf2-x86_64-python-3.12-3.12.0rc1+-3e20303 |
|----------------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| regex_compile  | 158 ms                                                       | 145 ms: 1.09x faster                                          |
| regex_v8       | 23.9 ms                                                      | 23.6 ms: 1.01x faster                                         |
| regex_effbot   | 3.50 ms                                                      | 3.51 ms: 1.00x slower                                         |
| regex_dna      | 227 ms                                                       | 239 ms: 1.05x slower                                          |
| Geometric mean | (ref)                                                        | 1.01x faster                                                  |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230827-pythonperf2-x86_64-python-3.12-3.12.0rc1+-3e20303 |
|----------------------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| json_dumps           | 13.4 ms                                                      | 10.3 ms: 1.30x faster                                         |
| json_loads           | 28.7 us                                                      | 24.9 us: 1.15x faster                                         |
| unpickle_pure_python | 241 us                                                       | 211 us: 1.14x faster                                          |
| xml_etree_parse      | 158 ms                                                       | 148 ms: 1.06x faster                                          |
| tomli_loads          | 2.26 sec                                                     | 2.19 sec: 1.03x faster                                        |
| xml_etree_iterparse  | 104 ms                                                       | 104 ms: 1.01x faster                                          |
| pickle               | 9.64 us                                                      | 9.90 us: 1.03x slower                                         |
| unpickle_list        | 4.53 us                                                      | 4.67 us: 1.03x slower                                         |
| xml_etree_process    | 56.5 ms                                                      | 58.5 ms: 1.04x slower                                         |
| xml_etree_generate   | 80.5 ms                                                      | 85.7 ms: 1.06x slower                                         |
| pickle_dict          | 30.8 us                                                      | 33.4 us: 1.08x slower                                         |
| pickle_list          | 3.83 us                                                      | 4.17 us: 1.09x slower                                         |
| unpickle             | 13.4 us                                                      | 14.8 us: 1.10x slower                                         |
| Geometric mean       | (ref)                                                        | 1.02x faster                                                  |

Benchmark hidden because not significant (1): pickle_pure_python

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230827-pythonperf2-x86_64-python-3.12-3.12.0rc1+-3e20303 |
|------------------------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| python_startup         | 10.8 ms                                                      | 11.5 ms: 1.07x slower                                         |
| python_startup_no_site | 7.76 ms                                                      | 8.51 ms: 1.10x slower                                         |
| Geometric mean         | (ref)                                                        | 1.08x slower                                                  |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230827-pythonperf2-x86_64-python-3.12-3.12.0rc1+-3e20303 |
|-----------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| mako      | 11.0 ms                                                      | 9.88 ms: 1.11x faster                                         |

All benchmarks:
===============

| Benchmark                | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230827-pythonperf2-x86_64-python-3.12-3.12.0rc1+-3e20303 |
|--------------------------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| typing_runtime_protocols | 523 us                                                       | 152 us: 3.44x faster                                          |
| asyncio_tcp              | 753 ms                                                       | 383 ms: 1.97x faster                                          |
| asyncio_tcp_ssl          | 3.08 sec                                                     | 1.57 sec: 1.96x faster                                        |
| generators               | 56.0 ms                                                      | 36.3 ms: 1.54x faster                                         |
| json_dumps               | 13.4 ms                                                      | 10.3 ms: 1.30x faster                                         |
| chaos                    | 80.9 ms                                                      | 62.7 ms: 1.29x faster                                         |
| mypy2                    | 451 ms                                                       | 367 ms: 1.23x faster                                          |
| coroutines               | 27.6 ms                                                      | 22.6 ms: 1.22x faster                                         |
| deltablue                | 4.00 ms                                                      | 3.29 ms: 1.21x faster                                         |
| hexiom                   | 7.13 ms                                                      | 5.89 ms: 1.21x faster                                         |
| richards_super           | 61.0 ms                                                      | 51.1 ms: 1.19x faster                                         |
| fannkuch                 | 429 ms                                                       | 363 ms: 1.18x faster                                          |
| json_loads               | 28.7 us                                                      | 24.9 us: 1.15x faster                                         |
| scimark_lu               | 115 ms                                                       | 99.6 ms: 1.15x faster                                         |
| unpickle_pure_python     | 241 us                                                       | 211 us: 1.14x faster                                          |
| nqueens                  | 103 ms                                                       | 90.2 ms: 1.14x faster                                         |
| async_tree_memoization   | 630 ms                                                       | 553 ms: 1.14x faster                                          |
| async_tree_none          | 519 ms                                                       | 460 ms: 1.13x faster                                          |
| comprehensions           | 24.6 us                                                      | 21.9 us: 1.12x faster                                         |
| mako                     | 11.0 ms                                                      | 9.88 ms: 1.11x faster                                         |
| go                       | 164 ms                                                       | 148 ms: 1.11x faster                                          |
| async_tree_io            | 1.17 sec                                                     | 1.06 sec: 1.11x faster                                        |
| sqlglot_parse            | 1.53 ms                                                      | 1.39 ms: 1.10x faster                                         |
| json                     | 5.65 ms                                                      | 5.16 ms: 1.10x faster                                         |
| logging_format           | 8.11 us                                                      | 7.41 us: 1.10x faster                                         |
| logging_silent           | 101 ns                                                       | 92.3 ns: 1.09x faster                                         |
| regex_compile            | 158 ms                                                       | 145 ms: 1.09x faster                                          |
| sqlglot_normalize        | 126 ms                                                       | 116 ms: 1.09x faster                                          |
| mdp                      | 2.75 sec                                                     | 2.55 sec: 1.08x faster                                        |
| sqlglot_transpile        | 1.92 ms                                                      | 1.80 ms: 1.07x faster                                         |
| async_tree_cpu_io_mixed  | 749 ms                                                       | 704 ms: 1.06x faster                                          |
| deepcopy_memo            | 38.8 us                                                      | 36.5 us: 1.06x faster                                         |
| xml_etree_parse          | 158 ms                                                       | 148 ms: 1.06x faster                                          |
| pycparser                | 1.32 sec                                                     | 1.25 sec: 1.06x faster                                        |
| raytrace                 | 317 ms                                                       | 299 ms: 1.06x faster                                          |
| bench_thread_pool        | 1.01 ms                                                      | 954 us: 1.06x faster                                          |
| richards                 | 48.3 ms                                                      | 45.6 ms: 1.06x faster                                         |
| deepcopy                 | 399 us                                                       | 377 us: 1.06x faster                                          |
| logging_simple           | 7.19 us                                                      | 6.80 us: 1.06x faster                                         |
| sqlglot_optimize         | 59.8 ms                                                      | 57.5 ms: 1.04x faster                                         |
| dulwich_log              | 68.4 ms                                                      | 65.9 ms: 1.04x faster                                         |
| gc_traversal             | 3.85 ms                                                      | 3.71 ms: 1.04x faster                                         |
| tomli_loads              | 2.26 sec                                                     | 2.19 sec: 1.03x faster                                        |
| meteor_contest           | 131 ms                                                       | 127 ms: 1.03x faster                                          |
| nbody                    | 90.7 ms                                                      | 88.2 ms: 1.03x faster                                         |
| deepcopy_reduce          | 3.51 us                                                      | 3.45 us: 1.02x faster                                         |
| spectral_norm            | 93.3 ms                                                      | 91.8 ms: 1.02x faster                                         |
| regex_v8                 | 23.9 ms                                                      | 23.6 ms: 1.01x faster                                         |
| 2to3                     | 288 ms                                                       | 284 ms: 1.01x faster                                          |
| crypto_pyaes             | 83.4 ms                                                      | 82.9 ms: 1.01x faster                                         |
| xml_etree_iterparse      | 104 ms                                                       | 104 ms: 1.01x faster                                          |
| pprint_pformat           | 1.63 sec                                                     | 1.62 sec: 1.01x faster                                        |
| pathlib                  | 19.1 ms                                                      | 19.0 ms: 1.00x faster                                         |
| scimark_sor              | 111 ms                                                       | 112 ms: 1.00x slower                                          |
| regex_effbot             | 3.50 ms                                                      | 3.51 ms: 1.00x slower                                         |
| docutils                 | 2.86 sec                                                     | 2.91 sec: 1.02x slower                                        |
| pprint_safe_repr         | 784 ms                                                       | 800 ms: 1.02x slower                                          |
| pickle                   | 9.64 us                                                      | 9.90 us: 1.03x slower                                         |
| unpickle_list            | 4.53 us                                                      | 4.67 us: 1.03x slower                                         |
| pidigits                 | 251 ms                                                       | 259 ms: 1.03x slower                                          |
| telco                    | 6.86 ms                                                      | 7.10 ms: 1.03x slower                                         |
| xml_etree_process        | 56.5 ms                                                      | 58.5 ms: 1.04x slower                                         |
| coverage                 | 84.8 ms                                                      | 88.2 ms: 1.04x slower                                         |
| unpack_sequence          | 45.6 ns                                                      | 47.6 ns: 1.04x slower                                         |
| pyflate                  | 449 ms                                                       | 469 ms: 1.05x slower                                          |
| scimark_monte_carlo      | 68.2 ms                                                      | 71.4 ms: 1.05x slower                                         |
| regex_dna                | 227 ms                                                       | 239 ms: 1.05x slower                                          |
| float                    | 74.2 ms                                                      | 78.3 ms: 1.06x slower                                         |
| scimark_fft              | 285 ms                                                       | 302 ms: 1.06x slower                                          |
| xml_etree_generate       | 80.5 ms                                                      | 85.7 ms: 1.06x slower                                         |
| python_startup           | 10.8 ms                                                      | 11.5 ms: 1.07x slower                                         |
| pickle_dict              | 30.8 us                                                      | 33.4 us: 1.08x slower                                         |
| sqlite_synth             | 2.50 us                                                      | 2.71 us: 1.09x slower                                         |
| pickle_list              | 3.83 us                                                      | 4.17 us: 1.09x slower                                         |
| scimark_sparse_mat_mult  | 4.05 ms                                                      | 4.43 ms: 1.09x slower                                         |
| python_startup_no_site   | 7.76 ms                                                      | 8.51 ms: 1.10x slower                                         |
| bench_mp_pool            | 4.62 ms                                                      | 5.09 ms: 1.10x slower                                         |
| unpickle                 | 13.4 us                                                      | 14.8 us: 1.10x slower                                         |
| async_generators         | 316 ms                                                       | 382 ms: 1.21x slower                                          |
| dask                     | 410 ms                                                       | 567 ms: 1.38x slower                                          |
| Geometric mean           | (ref)                                                        | 1.07x faster                                                  |

Benchmark hidden because not significant (3): tornado_http, pickle_pure_python, create_gc_cycles
Ignored benchmarks (16) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 99.94% likely to be faster
- 90% likely to have a speedup of 1.02x
- 95% likely to have a speedup of 1.01x
- 99% likely to have a speedup of 1.00x
