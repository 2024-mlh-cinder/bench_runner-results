
# Results vs. 3.11.0

- fork: python
- ref: v3.12.0rc1
- machine: linux-x86_64
- commit hash: 63bcd91
- commit date: 2023-08-05
- overall geometric mean: 1.07x faster
- HPT reliability: 99.90%
- HPT 99th percentile: 1.01x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230805-pythonperf2-x86_64-python-v3.12.0rc1-3.12.0rc1-63bcd91 |
|----------------|:------------------------------------------------------------:|:------------------------------------------------------------------:|
| docutils       | 2.86 sec                                                     | 2.88 sec: 1.01x slower                                             |
| Geometric mean | (ref)                                                        | 1.00x slower                                                       |

Benchmark hidden because not significant (2): 2to3, tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230805-pythonperf2-x86_64-python-v3.12.0rc1-3.12.0rc1-63bcd91 |
|----------------|:------------------------------------------------------------:|:------------------------------------------------------------------:|
| nbody          | 90.7 ms                                                      | 86.7 ms: 1.05x faster                                              |
| pidigits       | 251 ms                                                       | 260 ms: 1.03x slower                                               |
| float          | 74.2 ms                                                      | 77.8 ms: 1.05x slower                                              |
| Geometric mean | (ref)                                                        | 1.01x slower                                                       |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230805-pythonperf2-x86_64-python-v3.12.0rc1-3.12.0rc1-63bcd91 |
|----------------|:------------------------------------------------------------:|:------------------------------------------------------------------:|
| regex_compile  | 158 ms                                                       | 145 ms: 1.09x faster                                               |
| regex_effbot   | 3.50 ms                                                      | 3.38 ms: 1.03x faster                                              |
| regex_v8       | 23.9 ms                                                      | 24.0 ms: 1.00x slower                                              |
| regex_dna      | 227 ms                                                       | 236 ms: 1.04x slower                                               |
| Geometric mean | (ref)                                                        | 1.02x faster                                                       |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230805-pythonperf2-x86_64-python-v3.12.0rc1-3.12.0rc1-63bcd91 |
|----------------------|:------------------------------------------------------------:|:------------------------------------------------------------------:|
| json_dumps           | 13.4 ms                                                      | 10.4 ms: 1.28x faster                                              |
| json_loads           | 28.7 us                                                      | 24.5 us: 1.17x faster                                              |
| unpickle_pure_python | 241 us                                                       | 209 us: 1.15x faster                                               |
| xml_etree_parse      | 158 ms                                                       | 149 ms: 1.06x faster                                               |
| tomli_loads          | 2.26 sec                                                     | 2.18 sec: 1.04x faster                                             |
| pickle_pure_python   | 319 us                                                       | 325 us: 1.02x slower                                               |
| pickle_dict          | 30.8 us                                                      | 31.6 us: 1.03x slower                                              |
| unpickle_list        | 4.53 us                                                      | 4.67 us: 1.03x slower                                              |
| xml_etree_process    | 56.5 ms                                                      | 58.6 ms: 1.04x slower                                              |
| pickle               | 9.64 us                                                      | 10.0 us: 1.04x slower                                              |
| xml_etree_generate   | 80.5 ms                                                      | 84.2 ms: 1.05x slower                                              |
| unpickle             | 13.4 us                                                      | 14.3 us: 1.06x slower                                              |
| pickle_list          | 3.83 us                                                      | 4.35 us: 1.14x slower                                              |
| Geometric mean       | (ref)                                                        | 1.02x faster                                                       |

Benchmark hidden because not significant (1): xml_etree_iterparse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230805-pythonperf2-x86_64-python-v3.12.0rc1-3.12.0rc1-63bcd91 |
|------------------------|:------------------------------------------------------------:|:------------------------------------------------------------------:|
| python_startup         | 10.8 ms                                                      | 11.5 ms: 1.07x slower                                              |
| python_startup_no_site | 7.76 ms                                                      | 8.50 ms: 1.10x slower                                              |
| Geometric mean         | (ref)                                                        | 1.08x slower                                                       |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230805-pythonperf2-x86_64-python-v3.12.0rc1-3.12.0rc1-63bcd91 |
|-----------|:------------------------------------------------------------:|:------------------------------------------------------------------:|
| mako      | 11.0 ms                                                      | 9.91 ms: 1.11x faster                                              |

All benchmarks:
===============

| Benchmark                | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230805-pythonperf2-x86_64-python-v3.12.0rc1-3.12.0rc1-63bcd91 |
|--------------------------|:------------------------------------------------------------:|:------------------------------------------------------------------:|
| typing_runtime_protocols | 523 us                                                       | 151 us: 3.47x faster                                               |
| asyncio_tcp_ssl          | 3.08 sec                                                     | 1.57 sec: 1.96x faster                                             |
| asyncio_tcp              | 753 ms                                                       | 384 ms: 1.96x faster                                               |
| generators               | 56.0 ms                                                      | 36.4 ms: 1.54x faster                                              |
| json_dumps               | 13.4 ms                                                      | 10.4 ms: 1.28x faster                                              |
| chaos                    | 80.9 ms                                                      | 63.5 ms: 1.27x faster                                              |
| deltablue                | 4.00 ms                                                      | 3.21 ms: 1.24x faster                                              |
| hexiom                   | 7.13 ms                                                      | 5.81 ms: 1.23x faster                                              |
| mypy2                    | 451 ms                                                       | 369 ms: 1.22x faster                                               |
| coroutines               | 27.6 ms                                                      | 22.6 ms: 1.22x faster                                              |
| fannkuch                 | 429 ms                                                       | 361 ms: 1.19x faster                                               |
| richards_super           | 61.0 ms                                                      | 52.1 ms: 1.17x faster                                              |
| json_loads               | 28.7 us                                                      | 24.5 us: 1.17x faster                                              |
| scimark_lu               | 115 ms                                                       | 98.0 ms: 1.17x faster                                              |
| unpickle_pure_python     | 241 us                                                       | 209 us: 1.15x faster                                               |
| nqueens                  | 103 ms                                                       | 89.9 ms: 1.14x faster                                              |
| async_tree_memoization   | 630 ms                                                       | 554 ms: 1.14x faster                                               |
| comprehensions           | 24.6 us                                                      | 21.7 us: 1.13x faster                                              |
| async_tree_none          | 519 ms                                                       | 459 ms: 1.13x faster                                               |
| go                       | 164 ms                                                       | 146 ms: 1.13x faster                                               |
| mako                     | 11.0 ms                                                      | 9.91 ms: 1.11x faster                                              |
| async_tree_io            | 1.17 sec                                                     | 1.06 sec: 1.11x faster                                             |
| sqlglot_parse            | 1.53 ms                                                      | 1.39 ms: 1.10x faster                                              |
| json                     | 5.65 ms                                                      | 5.13 ms: 1.10x faster                                              |
| logging_silent           | 101 ns                                                       | 92.1 ns: 1.09x faster                                              |
| regex_compile            | 158 ms                                                       | 145 ms: 1.09x faster                                               |
| logging_format           | 8.11 us                                                      | 7.52 us: 1.08x faster                                              |
| mdp                      | 2.75 sec                                                     | 2.56 sec: 1.07x faster                                             |
| sqlglot_normalize        | 126 ms                                                       | 118 ms: 1.07x faster                                               |
| richards                 | 48.3 ms                                                      | 45.1 ms: 1.07x faster                                              |
| sqlglot_transpile        | 1.92 ms                                                      | 1.80 ms: 1.07x faster                                              |
| async_tree_cpu_io_mixed  | 749 ms                                                       | 703 ms: 1.07x faster                                               |
| xml_etree_parse          | 158 ms                                                       | 149 ms: 1.06x faster                                               |
| raytrace                 | 317 ms                                                       | 300 ms: 1.06x faster                                               |
| logging_simple           | 7.19 us                                                      | 6.82 us: 1.05x faster                                              |
| deepcopy_memo            | 38.8 us                                                      | 36.8 us: 1.05x faster                                              |
| bench_thread_pool        | 1.01 ms                                                      | 966 us: 1.05x faster                                               |
| nbody                    | 90.7 ms                                                      | 86.7 ms: 1.05x faster                                              |
| tomli_loads              | 2.26 sec                                                     | 2.18 sec: 1.04x faster                                             |
| dulwich_log              | 68.4 ms                                                      | 66.1 ms: 1.04x faster                                              |
| regex_effbot             | 3.50 ms                                                      | 3.38 ms: 1.03x faster                                              |
| sqlglot_optimize         | 59.8 ms                                                      | 58.1 ms: 1.03x faster                                              |
| pycparser                | 1.32 sec                                                     | 1.29 sec: 1.03x faster                                             |
| pyflate                  | 449 ms                                                       | 437 ms: 1.03x faster                                               |
| spectral_norm            | 93.3 ms                                                      | 90.9 ms: 1.03x faster                                              |
| meteor_contest           | 131 ms                                                       | 128 ms: 1.02x faster                                               |
| deepcopy                 | 399 us                                                       | 391 us: 1.02x faster                                               |
| scimark_sor              | 111 ms                                                       | 109 ms: 1.02x faster                                               |
| crypto_pyaes             | 83.4 ms                                                      | 81.8 ms: 1.02x faster                                              |
| gc_traversal             | 3.85 ms                                                      | 3.77 ms: 1.02x faster                                              |
| pathlib                  | 19.1 ms                                                      | 19.0 ms: 1.01x faster                                              |
| regex_v8                 | 23.9 ms                                                      | 24.0 ms: 1.00x slower                                              |
| docutils                 | 2.86 sec                                                     | 2.88 sec: 1.01x slower                                             |
| deepcopy_reduce          | 3.51 us                                                      | 3.55 us: 1.01x slower                                              |
| pprint_pformat           | 1.63 sec                                                     | 1.66 sec: 1.02x slower                                             |
| pickle_pure_python       | 319 us                                                       | 325 us: 1.02x slower                                               |
| telco                    | 6.86 ms                                                      | 7.01 ms: 1.02x slower                                              |
| pickle_dict              | 30.8 us                                                      | 31.6 us: 1.03x slower                                              |
| coverage                 | 84.8 ms                                                      | 87.0 ms: 1.03x slower                                              |
| unpickle_list            | 4.53 us                                                      | 4.67 us: 1.03x slower                                              |
| pidigits                 | 251 ms                                                       | 260 ms: 1.03x slower                                               |
| scimark_sparse_mat_mult  | 4.05 ms                                                      | 4.19 ms: 1.03x slower                                              |
| pprint_safe_repr         | 784 ms                                                       | 811 ms: 1.03x slower                                               |
| xml_etree_process        | 56.5 ms                                                      | 58.6 ms: 1.04x slower                                              |
| regex_dna                | 227 ms                                                       | 236 ms: 1.04x slower                                               |
| scimark_fft              | 285 ms                                                       | 297 ms: 1.04x slower                                               |
| pickle                   | 9.64 us                                                      | 10.0 us: 1.04x slower                                              |
| scimark_monte_carlo      | 68.2 ms                                                      | 71.2 ms: 1.04x slower                                              |
| xml_etree_generate       | 80.5 ms                                                      | 84.2 ms: 1.05x slower                                              |
| float                    | 74.2 ms                                                      | 77.8 ms: 1.05x slower                                              |
| bench_mp_pool            | 4.62 ms                                                      | 4.91 ms: 1.06x slower                                              |
| unpickle                 | 13.4 us                                                      | 14.3 us: 1.06x slower                                              |
| python_startup           | 10.8 ms                                                      | 11.5 ms: 1.07x slower                                              |
| sqlite_synth             | 2.50 us                                                      | 2.70 us: 1.08x slower                                              |
| python_startup_no_site   | 7.76 ms                                                      | 8.50 ms: 1.10x slower                                              |
| pickle_list              | 3.83 us                                                      | 4.35 us: 1.14x slower                                              |
| async_generators         | 316 ms                                                       | 380 ms: 1.20x slower                                               |
| unpack_sequence          | 45.6 ns                                                      | 56.2 ns: 1.23x slower                                              |
| dask                     | 410 ms                                                       | 566 ms: 1.38x slower                                               |
| Geometric mean           | (ref)                                                        | 1.07x faster                                                       |

Benchmark hidden because not significant (4): 2to3, xml_etree_iterparse, tornado_http, create_gc_cycles
Ignored benchmarks (16) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 99.90% likely to be faster
- 90% likely to have a speedup of 1.02x
- 95% likely to have a speedup of 1.02x
- 99% likely to have a speedup of 1.01x
