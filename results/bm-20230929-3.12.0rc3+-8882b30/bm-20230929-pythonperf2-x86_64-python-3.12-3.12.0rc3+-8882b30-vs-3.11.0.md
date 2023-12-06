
# Results vs. 3.11.0

- fork: python
- ref: 3.12
- machine: linux-x86_64
- commit hash: 8882b30
- commit date: 2023-09-29
- overall geometric mean: 1.07x faster
- HPT reliability: 99.43%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230929-pythonperf2-x86_64-python-3.12-3.12.0rc3+-8882b30 |
|----------------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| 2to3           | 288 ms                                                       | 286 ms: 1.01x faster                                          |
| docutils       | 2.86 sec                                                     | 2.88 sec: 1.01x slower                                        |
| Geometric mean | (ref)                                                        | 1.00x slower                                                  |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230929-pythonperf2-x86_64-python-3.12-3.12.0rc3+-8882b30 |
|----------------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| nbody          | 90.7 ms                                                      | 94.2 ms: 1.04x slower                                         |
| pidigits       | 251 ms                                                       | 265 ms: 1.05x slower                                          |
| float          | 74.2 ms                                                      | 78.4 ms: 1.06x slower                                         |
| Geometric mean | (ref)                                                        | 1.05x slower                                                  |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230929-pythonperf2-x86_64-python-3.12-3.12.0rc3+-8882b30 |
|----------------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| regex_compile  | 158 ms                                                       | 145 ms: 1.09x faster                                          |
| regex_effbot   | 3.50 ms                                                      | 3.57 ms: 1.02x slower                                         |
| regex_v8       | 23.9 ms                                                      | 24.7 ms: 1.03x slower                                         |
| regex_dna      | 227 ms                                                       | 240 ms: 1.06x slower                                          |
| Geometric mean | (ref)                                                        | 1.01x slower                                                  |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230929-pythonperf2-x86_64-python-3.12-3.12.0rc3+-8882b30 |
|----------------------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| json_dumps           | 13.4 ms                                                      | 10.3 ms: 1.30x faster                                         |
| json_loads           | 28.7 us                                                      | 24.2 us: 1.19x faster                                         |
| unpickle_pure_python | 241 us                                                       | 210 us: 1.15x faster                                          |
| xml_etree_parse      | 158 ms                                                       | 147 ms: 1.07x faster                                          |
| tomli_loads          | 2.26 sec                                                     | 2.21 sec: 1.02x faster                                        |
| pickle_pure_python   | 319 us                                                       | 326 us: 1.02x slower                                          |
| pickle_dict          | 30.8 us                                                      | 32.1 us: 1.04x slower                                         |
| xml_etree_process    | 56.5 ms                                                      | 58.9 ms: 1.04x slower                                         |
| pickle               | 9.64 us                                                      | 10.2 us: 1.06x slower                                         |
| unpickle_list        | 4.53 us                                                      | 4.82 us: 1.06x slower                                         |
| xml_etree_generate   | 80.5 ms                                                      | 86.4 ms: 1.07x slower                                         |
| unpickle             | 13.4 us                                                      | 14.8 us: 1.10x slower                                         |
| pickle_list          | 3.83 us                                                      | 4.35 us: 1.14x slower                                         |
| Geometric mean       | (ref)                                                        | 1.01x faster                                                  |

Benchmark hidden because not significant (1): xml_etree_iterparse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230929-pythonperf2-x86_64-python-3.12-3.12.0rc3+-8882b30 |
|------------------------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| python_startup         | 10.8 ms                                                      | 11.7 ms: 1.09x slower                                         |
| python_startup_no_site | 7.76 ms                                                      | 8.67 ms: 1.12x slower                                         |
| Geometric mean         | (ref)                                                        | 1.10x slower                                                  |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230929-pythonperf2-x86_64-python-3.12-3.12.0rc3+-8882b30 |
|-----------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| mako      | 11.0 ms                                                      | 9.96 ms: 1.10x faster                                         |

All benchmarks:
===============

| Benchmark                | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230929-pythonperf2-x86_64-python-3.12-3.12.0rc3+-8882b30 |
|--------------------------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| typing_runtime_protocols | 523 us                                                       | 154 us: 3.40x faster                                          |
| asyncio_tcp              | 753 ms                                                       | 381 ms: 1.98x faster                                          |
| asyncio_tcp_ssl          | 3.08 sec                                                     | 1.57 sec: 1.96x faster                                        |
| generators               | 56.0 ms                                                      | 36.5 ms: 1.54x faster                                         |
| json_dumps               | 13.4 ms                                                      | 10.3 ms: 1.30x faster                                         |
| chaos                    | 80.9 ms                                                      | 63.4 ms: 1.27x faster                                         |
| mypy2                    | 451 ms                                                       | 368 ms: 1.23x faster                                          |
| deltablue                | 4.00 ms                                                      | 3.30 ms: 1.21x faster                                         |
| fannkuch                 | 429 ms                                                       | 358 ms: 1.20x faster                                          |
| coroutines               | 27.6 ms                                                      | 23.2 ms: 1.19x faster                                         |
| hexiom                   | 7.13 ms                                                      | 6.01 ms: 1.19x faster                                         |
| json_loads               | 28.7 us                                                      | 24.2 us: 1.19x faster                                         |
| scimark_lu               | 115 ms                                                       | 97.8 ms: 1.17x faster                                         |
| richards_super           | 61.0 ms                                                      | 52.3 ms: 1.17x faster                                         |
| unpickle_pure_python     | 241 us                                                       | 210 us: 1.15x faster                                          |
| nqueens                  | 103 ms                                                       | 90.3 ms: 1.14x faster                                         |
| async_tree_memoization   | 630 ms                                                       | 554 ms: 1.14x faster                                          |
| comprehensions           | 24.6 us                                                      | 21.7 us: 1.13x faster                                         |
| async_tree_none          | 519 ms                                                       | 462 ms: 1.12x faster                                          |
| async_tree_io            | 1.17 sec                                                     | 1.06 sec: 1.11x faster                                        |
| json                     | 5.65 ms                                                      | 5.12 ms: 1.10x faster                                         |
| mako                     | 11.0 ms                                                      | 9.96 ms: 1.10x faster                                         |
| sqlglot_parse            | 1.53 ms                                                      | 1.40 ms: 1.10x faster                                         |
| regex_compile            | 158 ms                                                       | 145 ms: 1.09x faster                                          |
| go                       | 164 ms                                                       | 151 ms: 1.09x faster                                          |
| logging_simple           | 7.19 us                                                      | 6.62 us: 1.09x faster                                         |
| mdp                      | 2.75 sec                                                     | 2.54 sec: 1.08x faster                                        |
| logging_format           | 8.11 us                                                      | 7.52 us: 1.08x faster                                         |
| sqlglot_normalize        | 126 ms                                                       | 117 ms: 1.07x faster                                          |
| xml_etree_parse          | 158 ms                                                       | 147 ms: 1.07x faster                                          |
| sqlglot_transpile        | 1.92 ms                                                      | 1.79 ms: 1.07x faster                                         |
| deepcopy                 | 399 us                                                       | 374 us: 1.07x faster                                          |
| richards                 | 48.3 ms                                                      | 45.4 ms: 1.06x faster                                         |
| async_tree_cpu_io_mixed  | 749 ms                                                       | 707 ms: 1.06x faster                                          |
| logging_silent           | 101 ns                                                       | 95.3 ns: 1.06x faster                                         |
| dulwich_log              | 68.4 ms                                                      | 65.2 ms: 1.05x faster                                         |
| bench_thread_pool        | 1.01 ms                                                      | 965 us: 1.05x faster                                          |
| raytrace                 | 317 ms                                                       | 303 ms: 1.05x faster                                          |
| deepcopy_memo            | 38.8 us                                                      | 37.3 us: 1.04x faster                                         |
| dask                     | 410 ms                                                       | 396 ms: 1.03x faster                                          |
| sqlglot_optimize         | 59.8 ms                                                      | 57.9 ms: 1.03x faster                                         |
| scimark_sor              | 111 ms                                                       | 108 ms: 1.03x faster                                          |
| meteor_contest           | 131 ms                                                       | 128 ms: 1.03x faster                                          |
| pycparser                | 1.32 sec                                                     | 1.29 sec: 1.03x faster                                        |
| tomli_loads              | 2.26 sec                                                     | 2.21 sec: 1.02x faster                                        |
| crypto_pyaes             | 83.4 ms                                                      | 81.8 ms: 1.02x faster                                         |
| deepcopy_reduce          | 3.51 us                                                      | 3.44 us: 1.02x faster                                         |
| pyflate                  | 449 ms                                                       | 443 ms: 1.01x faster                                          |
| 2to3                     | 288 ms                                                       | 286 ms: 1.01x faster                                          |
| docutils                 | 2.86 sec                                                     | 2.88 sec: 1.01x slower                                        |
| pathlib                  | 19.1 ms                                                      | 19.4 ms: 1.02x slower                                         |
| regex_effbot             | 3.50 ms                                                      | 3.57 ms: 1.02x slower                                         |
| pprint_pformat           | 1.63 sec                                                     | 1.66 sec: 1.02x slower                                        |
| pickle_pure_python       | 319 us                                                       | 326 us: 1.02x slower                                          |
| telco                    | 6.86 ms                                                      | 7.06 ms: 1.03x slower                                         |
| regex_v8                 | 23.9 ms                                                      | 24.7 ms: 1.03x slower                                         |
| nbody                    | 90.7 ms                                                      | 94.2 ms: 1.04x slower                                         |
| scimark_fft              | 285 ms                                                       | 297 ms: 1.04x slower                                          |
| pickle_dict              | 30.8 us                                                      | 32.1 us: 1.04x slower                                         |
| xml_etree_process        | 56.5 ms                                                      | 58.9 ms: 1.04x slower                                         |
| coverage                 | 84.8 ms                                                      | 88.5 ms: 1.04x slower                                         |
| pprint_safe_repr         | 784 ms                                                       | 820 ms: 1.05x slower                                          |
| create_gc_cycles         | 1.61 ms                                                      | 1.69 ms: 1.05x slower                                         |
| gc_traversal             | 3.85 ms                                                      | 4.04 ms: 1.05x slower                                         |
| scimark_monte_carlo      | 68.2 ms                                                      | 71.6 ms: 1.05x slower                                         |
| pidigits                 | 251 ms                                                       | 265 ms: 1.05x slower                                          |
| float                    | 74.2 ms                                                      | 78.4 ms: 1.06x slower                                         |
| regex_dna                | 227 ms                                                       | 240 ms: 1.06x slower                                          |
| pickle                   | 9.64 us                                                      | 10.2 us: 1.06x slower                                         |
| unpickle_list            | 4.53 us                                                      | 4.82 us: 1.06x slower                                         |
| scimark_sparse_mat_mult  | 4.05 ms                                                      | 4.33 ms: 1.07x slower                                         |
| xml_etree_generate       | 80.5 ms                                                      | 86.4 ms: 1.07x slower                                         |
| sqlite_synth             | 2.50 us                                                      | 2.70 us: 1.08x slower                                         |
| python_startup           | 10.8 ms                                                      | 11.7 ms: 1.09x slower                                         |
| unpickle                 | 13.4 us                                                      | 14.8 us: 1.10x slower                                         |
| python_startup_no_site   | 7.76 ms                                                      | 8.67 ms: 1.12x slower                                         |
| pickle_list              | 3.83 us                                                      | 4.35 us: 1.14x slower                                         |
| unpack_sequence          | 45.6 ns                                                      | 52.9 ns: 1.16x slower                                         |
| async_generators         | 316 ms                                                       | 386 ms: 1.22x slower                                          |
| Geometric mean           | (ref)                                                        | 1.07x faster                                                  |

Benchmark hidden because not significant (4): spectral_norm, xml_etree_iterparse, tornado_http, bench_mp_pool
Ignored benchmarks (16) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 99.43% likely to be faster
- 90% likely to have a speedup of 1.02x
- 95% likely to have a speedup of 1.01x
- 99% likely to have a speedup of 1.00x
