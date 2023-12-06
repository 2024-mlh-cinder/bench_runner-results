
# Results vs. 3.11.0

- fork: python
- ref: 3.12
- machine: linux-x86_64
- commit hash: af83d1e
- commit date: 2023-09-08
- overall geometric mean: 1.07x faster
- HPT reliability: 99.88%
- HPT 99th percentile: 1.01x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230908-pythonperf2-x86_64-python-3.12-3.12.0rc2+-af83d1e |
|----------------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| 2to3           | 288 ms                                                       | 287 ms: 1.00x faster                                          |
| docutils       | 2.86 sec                                                     | 2.89 sec: 1.01x slower                                        |
| Geometric mean | (ref)                                                        | 1.00x slower                                                  |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230908-pythonperf2-x86_64-python-3.12-3.12.0rc2+-af83d1e |
|----------------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| nbody          | 90.7 ms                                                      | 85.4 ms: 1.06x faster                                         |
| pidigits       | 251 ms                                                       | 264 ms: 1.05x slower                                          |
| float          | 74.2 ms                                                      | 79.3 ms: 1.07x slower                                         |
| Geometric mean | (ref)                                                        | 1.02x slower                                                  |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230908-pythonperf2-x86_64-python-3.12-3.12.0rc2+-af83d1e |
|----------------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| regex_compile  | 158 ms                                                       | 146 ms: 1.08x faster                                          |
| regex_v8       | 23.9 ms                                                      | 23.3 ms: 1.03x faster                                         |
| regex_effbot   | 3.50 ms                                                      | 3.57 ms: 1.02x slower                                         |
| regex_dna      | 227 ms                                                       | 238 ms: 1.05x slower                                          |
| Geometric mean | (ref)                                                        | 1.01x faster                                                  |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230908-pythonperf2-x86_64-python-3.12-3.12.0rc2+-af83d1e |
|----------------------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| json_dumps           | 13.4 ms                                                      | 10.2 ms: 1.32x faster                                         |
| json_loads           | 28.7 us                                                      | 24.3 us: 1.18x faster                                         |
| unpickle_pure_python | 241 us                                                       | 211 us: 1.14x faster                                          |
| xml_etree_parse      | 158 ms                                                       | 145 ms: 1.08x faster                                          |
| tomli_loads          | 2.26 sec                                                     | 2.14 sec: 1.06x faster                                        |
| xml_etree_iterparse  | 104 ms                                                       | 102 ms: 1.02x faster                                          |
| pickle_pure_python   | 319 us                                                       | 326 us: 1.02x slower                                          |
| pickle_dict          | 30.8 us                                                      | 31.9 us: 1.04x slower                                         |
| xml_etree_process    | 56.5 ms                                                      | 59.0 ms: 1.05x slower                                         |
| pickle               | 9.64 us                                                      | 10.1 us: 1.05x slower                                         |
| unpickle_list        | 4.53 us                                                      | 4.76 us: 1.05x slower                                         |
| xml_etree_generate   | 80.5 ms                                                      | 86.8 ms: 1.08x slower                                         |
| unpickle             | 13.4 us                                                      | 15.0 us: 1.11x slower                                         |
| pickle_list          | 3.83 us                                                      | 4.41 us: 1.15x slower                                         |
| Geometric mean       | (ref)                                                        | 1.01x faster                                                  |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230908-pythonperf2-x86_64-python-3.12-3.12.0rc2+-af83d1e |
|------------------------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| python_startup         | 10.8 ms                                                      | 11.7 ms: 1.09x slower                                         |
| python_startup_no_site | 7.76 ms                                                      | 8.68 ms: 1.12x slower                                         |
| Geometric mean         | (ref)                                                        | 1.10x slower                                                  |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230908-pythonperf2-x86_64-python-3.12-3.12.0rc2+-af83d1e |
|-----------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| mako      | 11.0 ms                                                      | 9.87 ms: 1.11x faster                                         |

All benchmarks:
===============

| Benchmark                | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230908-pythonperf2-x86_64-python-3.12-3.12.0rc2+-af83d1e |
|--------------------------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| typing_runtime_protocols | 523 us                                                       | 155 us: 3.38x faster                                          |
| asyncio_tcp              | 753 ms                                                       | 383 ms: 1.96x faster                                          |
| asyncio_tcp_ssl          | 3.08 sec                                                     | 1.57 sec: 1.96x faster                                        |
| generators               | 56.0 ms                                                      | 36.7 ms: 1.53x faster                                         |
| json_dumps               | 13.4 ms                                                      | 10.2 ms: 1.32x faster                                         |
| chaos                    | 80.9 ms                                                      | 63.5 ms: 1.27x faster                                         |
| fannkuch                 | 429 ms                                                       | 344 ms: 1.25x faster                                          |
| deltablue                | 4.00 ms                                                      | 3.26 ms: 1.23x faster                                         |
| mypy2                    | 451 ms                                                       | 368 ms: 1.23x faster                                          |
| coroutines               | 27.6 ms                                                      | 22.8 ms: 1.21x faster                                         |
| richards_super           | 61.0 ms                                                      | 50.8 ms: 1.20x faster                                         |
| hexiom                   | 7.13 ms                                                      | 5.95 ms: 1.20x faster                                         |
| json_loads               | 28.7 us                                                      | 24.3 us: 1.18x faster                                         |
| scimark_lu               | 115 ms                                                       | 99.0 ms: 1.16x faster                                         |
| async_tree_memoization   | 630 ms                                                       | 548 ms: 1.15x faster                                          |
| async_tree_none          | 519 ms                                                       | 455 ms: 1.14x faster                                          |
| unpickle_pure_python     | 241 us                                                       | 211 us: 1.14x faster                                          |
| nqueens                  | 103 ms                                                       | 90.4 ms: 1.14x faster                                         |
| comprehensions           | 24.6 us                                                      | 21.9 us: 1.12x faster                                         |
| async_tree_io            | 1.17 sec                                                     | 1.05 sec: 1.12x faster                                        |
| mako                     | 11.0 ms                                                      | 9.87 ms: 1.11x faster                                         |
| json                     | 5.65 ms                                                      | 5.11 ms: 1.11x faster                                         |
| go                       | 164 ms                                                       | 150 ms: 1.10x faster                                          |
| sqlglot_parse            | 1.53 ms                                                      | 1.40 ms: 1.09x faster                                         |
| richards                 | 48.3 ms                                                      | 44.2 ms: 1.09x faster                                         |
| xml_etree_parse          | 158 ms                                                       | 145 ms: 1.08x faster                                          |
| logging_format           | 8.11 us                                                      | 7.51 us: 1.08x faster                                         |
| regex_compile            | 158 ms                                                       | 146 ms: 1.08x faster                                          |
| mdp                      | 2.75 sec                                                     | 2.56 sec: 1.07x faster                                        |
| pycparser                | 1.32 sec                                                     | 1.24 sec: 1.07x faster                                        |
| sqlglot_transpile        | 1.92 ms                                                      | 1.80 ms: 1.07x faster                                         |
| async_tree_cpu_io_mixed  | 749 ms                                                       | 701 ms: 1.07x faster                                          |
| nbody                    | 90.7 ms                                                      | 85.4 ms: 1.06x faster                                         |
| sqlglot_normalize        | 126 ms                                                       | 119 ms: 1.06x faster                                          |
| tomli_loads              | 2.26 sec                                                     | 2.14 sec: 1.06x faster                                        |
| logging_silent           | 101 ns                                                       | 95.8 ns: 1.05x faster                                         |
| logging_simple           | 7.19 us                                                      | 6.89 us: 1.04x faster                                         |
| bench_thread_pool        | 1.01 ms                                                      | 973 us: 1.04x faster                                          |
| dulwich_log              | 68.4 ms                                                      | 65.9 ms: 1.04x faster                                         |
| raytrace                 | 317 ms                                                       | 305 ms: 1.04x faster                                          |
| crypto_pyaes             | 83.4 ms                                                      | 80.5 ms: 1.04x faster                                         |
| deepcopy                 | 399 us                                                       | 385 us: 1.04x faster                                          |
| meteor_contest           | 131 ms                                                       | 126 ms: 1.03x faster                                          |
| sqlglot_optimize         | 59.8 ms                                                      | 58.1 ms: 1.03x faster                                         |
| deepcopy_memo            | 38.8 us                                                      | 37.8 us: 1.03x faster                                         |
| regex_v8                 | 23.9 ms                                                      | 23.3 ms: 1.03x faster                                         |
| gc_traversal             | 3.85 ms                                                      | 3.76 ms: 1.02x faster                                         |
| xml_etree_iterparse      | 104 ms                                                       | 102 ms: 1.02x faster                                          |
| spectral_norm            | 93.3 ms                                                      | 91.9 ms: 1.02x faster                                         |
| scimark_sor              | 111 ms                                                       | 109 ms: 1.02x faster                                          |
| deepcopy_reduce          | 3.51 us                                                      | 3.47 us: 1.01x faster                                         |
| 2to3                     | 288 ms                                                       | 287 ms: 1.00x faster                                          |
| docutils                 | 2.86 sec                                                     | 2.89 sec: 1.01x slower                                        |
| telco                    | 6.86 ms                                                      | 6.99 ms: 1.02x slower                                         |
| regex_effbot             | 3.50 ms                                                      | 3.57 ms: 1.02x slower                                         |
| pickle_pure_python       | 319 us                                                       | 326 us: 1.02x slower                                          |
| scimark_monte_carlo      | 68.2 ms                                                      | 70.0 ms: 1.03x slower                                         |
| pprint_pformat           | 1.63 sec                                                     | 1.67 sec: 1.03x slower                                        |
| unpack_sequence          | 45.6 ns                                                      | 47.3 ns: 1.04x slower                                         |
| pickle_dict              | 30.8 us                                                      | 31.9 us: 1.04x slower                                         |
| pyflate                  | 449 ms                                                       | 466 ms: 1.04x slower                                          |
| pathlib                  | 19.1 ms                                                      | 19.9 ms: 1.04x slower                                         |
| xml_etree_process        | 56.5 ms                                                      | 59.0 ms: 1.05x slower                                         |
| coverage                 | 84.8 ms                                                      | 88.7 ms: 1.05x slower                                         |
| pickle                   | 9.64 us                                                      | 10.1 us: 1.05x slower                                         |
| regex_dna                | 227 ms                                                       | 238 ms: 1.05x slower                                          |
| unpickle_list            | 4.53 us                                                      | 4.76 us: 1.05x slower                                         |
| pidigits                 | 251 ms                                                       | 264 ms: 1.05x slower                                          |
| pprint_safe_repr         | 784 ms                                                       | 825 ms: 1.05x slower                                          |
| scimark_fft              | 285 ms                                                       | 304 ms: 1.07x slower                                          |
| float                    | 74.2 ms                                                      | 79.3 ms: 1.07x slower                                         |
| xml_etree_generate       | 80.5 ms                                                      | 86.8 ms: 1.08x slower                                         |
| sqlite_synth             | 2.50 us                                                      | 2.71 us: 1.09x slower                                         |
| python_startup           | 10.8 ms                                                      | 11.7 ms: 1.09x slower                                         |
| scimark_sparse_mat_mult  | 4.05 ms                                                      | 4.44 ms: 1.10x slower                                         |
| unpickle                 | 13.4 us                                                      | 15.0 us: 1.11x slower                                         |
| python_startup_no_site   | 7.76 ms                                                      | 8.68 ms: 1.12x slower                                         |
| pickle_list              | 3.83 us                                                      | 4.41 us: 1.15x slower                                         |
| async_generators         | 316 ms                                                       | 381 ms: 1.21x slower                                          |
| dask                     | 410 ms                                                       | 567 ms: 1.38x slower                                          |
| Geometric mean           | (ref)                                                        | 1.07x faster                                                  |

Benchmark hidden because not significant (3): bench_mp_pool, tornado_http, create_gc_cycles
Ignored benchmarks (16) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 99.88% likely to be faster
- 90% likely to have a speedup of 1.02x
- 95% likely to have a speedup of 1.02x
- 99% likely to have a speedup of 1.01x
