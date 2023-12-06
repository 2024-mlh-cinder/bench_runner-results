
# Results vs. 3.11.0

- fork: python
- ref: 3.12
- machine: linux-x86_64
- commit hash: dcaacd9
- commit date: 2023-09-03
- overall geometric mean: 1.07x faster
- HPT reliability: 99.67%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230903-pythonperf2-x86_64-python-3.12-3.12.0rc1+-dcaacd9 |
|----------------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| 2to3           | 288 ms                                                       | 285 ms: 1.01x faster                                          |
| docutils       | 2.86 sec                                                     | 2.90 sec: 1.01x slower                                        |
| tornado_http   | 122 ms                                                       | 120 ms: 1.01x faster                                          |
| Geometric mean | (ref)                                                        | 1.00x faster                                                  |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230903-pythonperf2-x86_64-python-3.12-3.12.0rc1+-dcaacd9 |
|----------------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| pidigits       | 251 ms                                                       | 264 ms: 1.05x slower                                          |
| nbody          | 90.7 ms                                                      | 95.9 ms: 1.06x slower                                         |
| float          | 74.2 ms                                                      | 79.1 ms: 1.07x slower                                         |
| Geometric mean | (ref)                                                        | 1.06x slower                                                  |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230903-pythonperf2-x86_64-python-3.12-3.12.0rc1+-dcaacd9 |
|----------------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| regex_compile  | 158 ms                                                       | 145 ms: 1.08x faster                                          |
| regex_effbot   | 3.50 ms                                                      | 3.45 ms: 1.01x faster                                         |
| regex_v8       | 23.9 ms                                                      | 24.6 ms: 1.03x slower                                         |
| regex_dna      | 227 ms                                                       | 245 ms: 1.08x slower                                          |
| Geometric mean | (ref)                                                        | 1.00x slower                                                  |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230903-pythonperf2-x86_64-python-3.12-3.12.0rc1+-dcaacd9 |
|----------------------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| json_dumps           | 13.4 ms                                                      | 10.2 ms: 1.32x faster                                         |
| json_loads           | 28.7 us                                                      | 24.4 us: 1.18x faster                                         |
| unpickle_pure_python | 241 us                                                       | 206 us: 1.17x faster                                          |
| xml_etree_parse      | 158 ms                                                       | 151 ms: 1.05x faster                                          |
| tomli_loads          | 2.26 sec                                                     | 2.16 sec: 1.05x faster                                        |
| xml_etree_iterparse  | 104 ms                                                       | 105 ms: 1.01x slower                                          |
| pickle_pure_python   | 319 us                                                       | 325 us: 1.02x slower                                          |
| pickle               | 9.64 us                                                      | 9.83 us: 1.02x slower                                         |
| pickle_dict          | 30.8 us                                                      | 31.5 us: 1.03x slower                                         |
| xml_etree_process    | 56.5 ms                                                      | 59.5 ms: 1.05x slower                                         |
| unpickle_list        | 4.53 us                                                      | 4.79 us: 1.06x slower                                         |
| xml_etree_generate   | 80.5 ms                                                      | 87.4 ms: 1.09x slower                                         |
| unpickle             | 13.4 us                                                      | 14.6 us: 1.09x slower                                         |
| pickle_list          | 3.83 us                                                      | 4.21 us: 1.10x slower                                         |
| Geometric mean       | (ref)                                                        | 1.02x faster                                                  |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230903-pythonperf2-x86_64-python-3.12-3.12.0rc1+-dcaacd9 |
|------------------------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| python_startup         | 10.8 ms                                                      | 11.7 ms: 1.09x slower                                         |
| python_startup_no_site | 7.76 ms                                                      | 8.66 ms: 1.12x slower                                         |
| Geometric mean         | (ref)                                                        | 1.10x slower                                                  |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230903-pythonperf2-x86_64-python-3.12-3.12.0rc1+-dcaacd9 |
|-----------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| mako      | 11.0 ms                                                      | 9.93 ms: 1.11x faster                                         |

All benchmarks:
===============

| Benchmark                | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230903-pythonperf2-x86_64-python-3.12-3.12.0rc1+-dcaacd9 |
|--------------------------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| typing_runtime_protocols | 523 us                                                       | 151 us: 3.47x faster                                          |
| asyncio_tcp_ssl          | 3.08 sec                                                     | 1.58 sec: 1.95x faster                                        |
| asyncio_tcp              | 753 ms                                                       | 387 ms: 1.95x faster                                          |
| generators               | 56.0 ms                                                      | 37.0 ms: 1.52x faster                                         |
| json_dumps               | 13.4 ms                                                      | 10.2 ms: 1.32x faster                                         |
| chaos                    | 80.9 ms                                                      | 62.2 ms: 1.30x faster                                         |
| fannkuch                 | 429 ms                                                       | 347 ms: 1.24x faster                                          |
| deltablue                | 4.00 ms                                                      | 3.23 ms: 1.24x faster                                         |
| mypy2                    | 451 ms                                                       | 366 ms: 1.23x faster                                          |
| hexiom                   | 7.13 ms                                                      | 5.83 ms: 1.22x faster                                         |
| richards_super           | 61.0 ms                                                      | 50.8 ms: 1.20x faster                                         |
| coroutines               | 27.6 ms                                                      | 23.0 ms: 1.20x faster                                         |
| scimark_lu               | 115 ms                                                       | 97.0 ms: 1.18x faster                                         |
| json_loads               | 28.7 us                                                      | 24.4 us: 1.18x faster                                         |
| unpickle_pure_python     | 241 us                                                       | 206 us: 1.17x faster                                          |
| nqueens                  | 103 ms                                                       | 89.3 ms: 1.15x faster                                         |
| async_tree_memoization   | 630 ms                                                       | 549 ms: 1.15x faster                                          |
| async_tree_none          | 519 ms                                                       | 456 ms: 1.14x faster                                          |
| comprehensions           | 24.6 us                                                      | 21.8 us: 1.13x faster                                         |
| go                       | 164 ms                                                       | 146 ms: 1.12x faster                                          |
| async_tree_io            | 1.17 sec                                                     | 1.05 sec: 1.12x faster                                        |
| json                     | 5.65 ms                                                      | 5.08 ms: 1.11x faster                                         |
| mako                     | 11.0 ms                                                      | 9.93 ms: 1.11x faster                                         |
| richards                 | 48.3 ms                                                      | 43.9 ms: 1.10x faster                                         |
| logging_format           | 8.11 us                                                      | 7.39 us: 1.10x faster                                         |
| sqlglot_parse            | 1.53 ms                                                      | 1.40 ms: 1.10x faster                                         |
| logging_silent           | 101 ns                                                       | 92.1 ns: 1.10x faster                                         |
| mdp                      | 2.75 sec                                                     | 2.53 sec: 1.09x faster                                        |
| regex_compile            | 158 ms                                                       | 145 ms: 1.08x faster                                          |
| sqlglot_normalize        | 126 ms                                                       | 117 ms: 1.07x faster                                          |
| logging_simple           | 7.19 us                                                      | 6.71 us: 1.07x faster                                         |
| sqlglot_transpile        | 1.92 ms                                                      | 1.80 ms: 1.07x faster                                         |
| raytrace                 | 317 ms                                                       | 297 ms: 1.07x faster                                          |
| async_tree_cpu_io_mixed  | 749 ms                                                       | 702 ms: 1.07x faster                                          |
| dulwich_log              | 68.4 ms                                                      | 65.2 ms: 1.05x faster                                         |
| xml_etree_parse          | 158 ms                                                       | 151 ms: 1.05x faster                                          |
| tomli_loads              | 2.26 sec                                                     | 2.16 sec: 1.05x faster                                        |
| bench_thread_pool        | 1.01 ms                                                      | 967 us: 1.05x faster                                          |
| deepcopy_memo            | 38.8 us                                                      | 37.1 us: 1.04x faster                                         |
| meteor_contest           | 131 ms                                                       | 126 ms: 1.04x faster                                          |
| deepcopy                 | 399 us                                                       | 385 us: 1.04x faster                                          |
| scimark_sor              | 111 ms                                                       | 107 ms: 1.04x faster                                          |
| pycparser                | 1.32 sec                                                     | 1.28 sec: 1.03x faster                                        |
| spectral_norm            | 93.3 ms                                                      | 90.4 ms: 1.03x faster                                         |
| sqlglot_optimize         | 59.8 ms                                                      | 58.0 ms: 1.03x faster                                         |
| crypto_pyaes             | 83.4 ms                                                      | 81.1 ms: 1.03x faster                                         |
| gc_traversal             | 3.85 ms                                                      | 3.78 ms: 1.02x faster                                         |
| regex_effbot             | 3.50 ms                                                      | 3.45 ms: 1.01x faster                                         |
| deepcopy_reduce          | 3.51 us                                                      | 3.47 us: 1.01x faster                                         |
| pyflate                  | 449 ms                                                       | 443 ms: 1.01x faster                                          |
| tornado_http             | 122 ms                                                       | 120 ms: 1.01x faster                                          |
| 2to3                     | 288 ms                                                       | 285 ms: 1.01x faster                                          |
| pathlib                  | 19.1 ms                                                      | 19.2 ms: 1.01x slower                                         |
| pprint_pformat           | 1.63 sec                                                     | 1.64 sec: 1.01x slower                                        |
| xml_etree_iterparse      | 104 ms                                                       | 105 ms: 1.01x slower                                          |
| docutils                 | 2.86 sec                                                     | 2.90 sec: 1.01x slower                                        |
| pickle_pure_python       | 319 us                                                       | 325 us: 1.02x slower                                          |
| pickle                   | 9.64 us                                                      | 9.83 us: 1.02x slower                                         |
| pickle_dict              | 30.8 us                                                      | 31.5 us: 1.03x slower                                         |
| regex_v8                 | 23.9 ms                                                      | 24.6 ms: 1.03x slower                                         |
| pprint_safe_repr         | 784 ms                                                       | 805 ms: 1.03x slower                                          |
| telco                    | 6.86 ms                                                      | 7.05 ms: 1.03x slower                                         |
| scimark_monte_carlo      | 68.2 ms                                                      | 70.5 ms: 1.03x slower                                         |
| coverage                 | 84.8 ms                                                      | 88.3 ms: 1.04x slower                                         |
| scimark_fft              | 285 ms                                                       | 298 ms: 1.04x slower                                          |
| pidigits                 | 251 ms                                                       | 264 ms: 1.05x slower                                          |
| xml_etree_process        | 56.5 ms                                                      | 59.5 ms: 1.05x slower                                         |
| unpickle_list            | 4.53 us                                                      | 4.79 us: 1.06x slower                                         |
| nbody                    | 90.7 ms                                                      | 95.9 ms: 1.06x slower                                         |
| scimark_sparse_mat_mult  | 4.05 ms                                                      | 4.29 ms: 1.06x slower                                         |
| float                    | 74.2 ms                                                      | 79.1 ms: 1.07x slower                                         |
| unpack_sequence          | 45.6 ns                                                      | 49.1 ns: 1.08x slower                                         |
| regex_dna                | 227 ms                                                       | 245 ms: 1.08x slower                                          |
| sqlite_synth             | 2.50 us                                                      | 2.70 us: 1.08x slower                                         |
| xml_etree_generate       | 80.5 ms                                                      | 87.4 ms: 1.09x slower                                         |
| python_startup           | 10.8 ms                                                      | 11.7 ms: 1.09x slower                                         |
| unpickle                 | 13.4 us                                                      | 14.6 us: 1.09x slower                                         |
| pickle_list              | 3.83 us                                                      | 4.21 us: 1.10x slower                                         |
| python_startup_no_site   | 7.76 ms                                                      | 8.66 ms: 1.12x slower                                         |
| async_generators         | 316 ms                                                       | 382 ms: 1.21x slower                                          |
| dask                     | 410 ms                                                       | 565 ms: 1.38x slower                                          |
| Geometric mean           | (ref)                                                        | 1.07x faster                                                  |

Benchmark hidden because not significant (2): create_gc_cycles, bench_mp_pool
Ignored benchmarks (16) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 99.67% likely to be faster
- 90% likely to have a speedup of 1.02x
- 95% likely to have a speedup of 1.02x
- 99% likely to have a speedup of 1.00x
