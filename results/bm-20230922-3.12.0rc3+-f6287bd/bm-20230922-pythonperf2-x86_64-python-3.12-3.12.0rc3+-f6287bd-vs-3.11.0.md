
# Results vs. 3.11.0

- fork: python
- ref: 3.12
- machine: linux-x86_64
- commit hash: f6287bd
- commit date: 2023-09-22
- overall geometric mean: 1.07x faster
- HPT reliability: 99.77%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230922-pythonperf2-x86_64-python-3.12-3.12.0rc3+-f6287bd |
|----------------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| 2to3           | 288 ms                                                       | 286 ms: 1.01x faster                                          |
| docutils       | 2.86 sec                                                     | 2.89 sec: 1.01x slower                                        |
| tornado_http   | 122 ms                                                       | 120 ms: 1.01x faster                                          |
| Geometric mean | (ref)                                                        | 1.00x faster                                                  |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230922-pythonperf2-x86_64-python-3.12-3.12.0rc3+-f6287bd |
|----------------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| pidigits       | 251 ms                                                       | 264 ms: 1.05x slower                                          |
| float          | 74.2 ms                                                      | 79.0 ms: 1.07x slower                                         |
| Geometric mean | (ref)                                                        | 1.04x slower                                                  |

Benchmark hidden because not significant (1): nbody

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230922-pythonperf2-x86_64-python-3.12-3.12.0rc3+-f6287bd |
|----------------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| regex_compile  | 158 ms                                                       | 145 ms: 1.09x faster                                          |
| regex_effbot   | 3.50 ms                                                      | 3.47 ms: 1.01x faster                                         |
| regex_v8       | 23.9 ms                                                      | 25.2 ms: 1.05x slower                                         |
| regex_dna      | 227 ms                                                       | 246 ms: 1.08x slower                                          |
| Geometric mean | (ref)                                                        | 1.01x slower                                                  |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230922-pythonperf2-x86_64-python-3.12-3.12.0rc3+-f6287bd |
|----------------------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| json_dumps           | 13.4 ms                                                      | 10.2 ms: 1.32x faster                                         |
| json_loads           | 28.7 us                                                      | 24.6 us: 1.16x faster                                         |
| unpickle_pure_python | 241 us                                                       | 207 us: 1.16x faster                                          |
| xml_etree_parse      | 158 ms                                                       | 148 ms: 1.07x faster                                          |
| tomli_loads          | 2.26 sec                                                     | 2.17 sec: 1.04x faster                                        |
| pickle_pure_python   | 319 us                                                       | 324 us: 1.02x slower                                          |
| unpickle_list        | 4.53 us                                                      | 4.74 us: 1.04x slower                                         |
| xml_etree_process    | 56.5 ms                                                      | 59.1 ms: 1.05x slower                                         |
| pickle_dict          | 30.8 us                                                      | 32.3 us: 1.05x slower                                         |
| pickle               | 9.64 us                                                      | 10.2 us: 1.06x slower                                         |
| xml_etree_generate   | 80.5 ms                                                      | 85.9 ms: 1.07x slower                                         |
| unpickle             | 13.4 us                                                      | 14.8 us: 1.10x slower                                         |
| pickle_list          | 3.83 us                                                      | 4.39 us: 1.15x slower                                         |
| Geometric mean       | (ref)                                                        | 1.01x faster                                                  |

Benchmark hidden because not significant (1): xml_etree_iterparse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230922-pythonperf2-x86_64-python-3.12-3.12.0rc3+-f6287bd |
|------------------------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| python_startup         | 10.8 ms                                                      | 11.7 ms: 1.09x slower                                         |
| python_startup_no_site | 7.76 ms                                                      | 8.69 ms: 1.12x slower                                         |
| Geometric mean         | (ref)                                                        | 1.10x slower                                                  |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230922-pythonperf2-x86_64-python-3.12-3.12.0rc3+-f6287bd |
|-----------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| mako      | 11.0 ms                                                      | 10.1 ms: 1.09x faster                                         |

All benchmarks:
===============

| Benchmark                | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230922-pythonperf2-x86_64-python-3.12-3.12.0rc3+-f6287bd |
|--------------------------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| typing_runtime_protocols | 523 us                                                       | 151 us: 3.47x faster                                          |
| asyncio_tcp              | 753 ms                                                       | 379 ms: 1.99x faster                                          |
| asyncio_tcp_ssl          | 3.08 sec                                                     | 1.57 sec: 1.96x faster                                        |
| generators               | 56.0 ms                                                      | 36.8 ms: 1.52x faster                                         |
| json_dumps               | 13.4 ms                                                      | 10.2 ms: 1.32x faster                                         |
| chaos                    | 80.9 ms                                                      | 63.3 ms: 1.28x faster                                         |
| mypy2                    | 451 ms                                                       | 368 ms: 1.23x faster                                          |
| fannkuch                 | 429 ms                                                       | 351 ms: 1.22x faster                                          |
| deltablue                | 4.00 ms                                                      | 3.32 ms: 1.20x faster                                         |
| hexiom                   | 7.13 ms                                                      | 5.98 ms: 1.19x faster                                         |
| coroutines               | 27.6 ms                                                      | 23.1 ms: 1.19x faster                                         |
| json_loads               | 28.7 us                                                      | 24.6 us: 1.16x faster                                         |
| richards_super           | 61.0 ms                                                      | 52.5 ms: 1.16x faster                                         |
| unpickle_pure_python     | 241 us                                                       | 207 us: 1.16x faster                                          |
| comprehensions           | 24.6 us                                                      | 21.6 us: 1.14x faster                                         |
| async_tree_memoization   | 630 ms                                                       | 556 ms: 1.13x faster                                          |
| async_tree_none          | 519 ms                                                       | 460 ms: 1.13x faster                                          |
| scimark_lu               | 115 ms                                                       | 102 ms: 1.13x faster                                          |
| nqueens                  | 103 ms                                                       | 92.1 ms: 1.12x faster                                         |
| async_tree_io            | 1.17 sec                                                     | 1.06 sec: 1.11x faster                                        |
| mako                     | 11.0 ms                                                      | 10.1 ms: 1.09x faster                                         |
| json                     | 5.65 ms                                                      | 5.19 ms: 1.09x faster                                         |
| regex_compile            | 158 ms                                                       | 145 ms: 1.09x faster                                          |
| sqlglot_parse            | 1.53 ms                                                      | 1.41 ms: 1.09x faster                                         |
| gc_traversal             | 3.85 ms                                                      | 3.55 ms: 1.08x faster                                         |
| mdp                      | 2.75 sec                                                     | 2.54 sec: 1.08x faster                                        |
| logging_format           | 8.11 us                                                      | 7.58 us: 1.07x faster                                         |
| sqlglot_normalize        | 126 ms                                                       | 118 ms: 1.07x faster                                          |
| logging_simple           | 7.19 us                                                      | 6.74 us: 1.07x faster                                         |
| xml_etree_parse          | 158 ms                                                       | 148 ms: 1.07x faster                                          |
| go                       | 164 ms                                                       | 154 ms: 1.07x faster                                          |
| logging_silent           | 101 ns                                                       | 94.6 ns: 1.07x faster                                         |
| async_tree_cpu_io_mixed  | 749 ms                                                       | 706 ms: 1.06x faster                                          |
| sqlglot_transpile        | 1.92 ms                                                      | 1.82 ms: 1.06x faster                                         |
| bench_thread_pool        | 1.01 ms                                                      | 960 us: 1.05x faster                                          |
| richards                 | 48.3 ms                                                      | 46.3 ms: 1.04x faster                                         |
| meteor_contest           | 131 ms                                                       | 125 ms: 1.04x faster                                          |
| tomli_loads              | 2.26 sec                                                     | 2.17 sec: 1.04x faster                                        |
| dulwich_log              | 68.4 ms                                                      | 65.7 ms: 1.04x faster                                         |
| deepcopy                 | 399 us                                                       | 384 us: 1.04x faster                                          |
| dask                     | 410 ms                                                       | 397 ms: 1.03x faster                                          |
| sqlglot_optimize         | 59.8 ms                                                      | 58.0 ms: 1.03x faster                                         |
| pycparser                | 1.32 sec                                                     | 1.29 sec: 1.03x faster                                        |
| raytrace                 | 317 ms                                                       | 308 ms: 1.03x faster                                          |
| crypto_pyaes             | 83.4 ms                                                      | 81.1 ms: 1.03x faster                                         |
| deepcopy_memo            | 38.8 us                                                      | 37.7 us: 1.03x faster                                         |
| spectral_norm            | 93.3 ms                                                      | 91.0 ms: 1.03x faster                                         |
| tornado_http             | 122 ms                                                       | 120 ms: 1.01x faster                                          |
| deepcopy_reduce          | 3.51 us                                                      | 3.47 us: 1.01x faster                                         |
| regex_effbot             | 3.50 ms                                                      | 3.47 ms: 1.01x faster                                         |
| 2to3                     | 288 ms                                                       | 286 ms: 1.01x faster                                          |
| scimark_sor              | 111 ms                                                       | 112 ms: 1.01x slower                                          |
| docutils                 | 2.86 sec                                                     | 2.89 sec: 1.01x slower                                        |
| pickle_pure_python       | 319 us                                                       | 324 us: 1.02x slower                                          |
| telco                    | 6.86 ms                                                      | 6.98 ms: 1.02x slower                                         |
| pathlib                  | 19.1 ms                                                      | 19.5 ms: 1.02x slower                                         |
| pprint_pformat           | 1.63 sec                                                     | 1.67 sec: 1.02x slower                                        |
| create_gc_cycles         | 1.61 ms                                                      | 1.66 ms: 1.03x slower                                         |
| scimark_monte_carlo      | 68.2 ms                                                      | 70.8 ms: 1.04x slower                                         |
| pyflate                  | 449 ms                                                       | 466 ms: 1.04x slower                                          |
| pprint_safe_repr         | 784 ms                                                       | 817 ms: 1.04x slower                                          |
| unpickle_list            | 4.53 us                                                      | 4.74 us: 1.04x slower                                         |
| xml_etree_process        | 56.5 ms                                                      | 59.1 ms: 1.05x slower                                         |
| pickle_dict              | 30.8 us                                                      | 32.3 us: 1.05x slower                                         |
| pidigits                 | 251 ms                                                       | 264 ms: 1.05x slower                                          |
| regex_v8                 | 23.9 ms                                                      | 25.2 ms: 1.05x slower                                         |
| pickle                   | 9.64 us                                                      | 10.2 us: 1.06x slower                                         |
| unpack_sequence          | 45.6 ns                                                      | 48.6 ns: 1.07x slower                                         |
| float                    | 74.2 ms                                                      | 79.0 ms: 1.07x slower                                         |
| coverage                 | 84.8 ms                                                      | 90.5 ms: 1.07x slower                                         |
| xml_etree_generate       | 80.5 ms                                                      | 85.9 ms: 1.07x slower                                         |
| scimark_fft              | 285 ms                                                       | 306 ms: 1.07x slower                                          |
| scimark_sparse_mat_mult  | 4.05 ms                                                      | 4.36 ms: 1.08x slower                                         |
| regex_dna                | 227 ms                                                       | 246 ms: 1.08x slower                                          |
| python_startup           | 10.8 ms                                                      | 11.7 ms: 1.09x slower                                         |
| bench_mp_pool            | 4.62 ms                                                      | 5.08 ms: 1.10x slower                                         |
| unpickle                 | 13.4 us                                                      | 14.8 us: 1.10x slower                                         |
| sqlite_synth             | 2.50 us                                                      | 2.75 us: 1.10x slower                                         |
| python_startup_no_site   | 7.76 ms                                                      | 8.69 ms: 1.12x slower                                         |
| pickle_list              | 3.83 us                                                      | 4.39 us: 1.15x slower                                         |
| async_generators         | 316 ms                                                       | 391 ms: 1.24x slower                                          |
| Geometric mean           | (ref)                                                        | 1.07x faster                                                  |

Benchmark hidden because not significant (2): xml_etree_iterparse, nbody
Ignored benchmarks (16) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 99.77% likely to be faster
- 90% likely to have a speedup of 1.02x
- 95% likely to have a speedup of 1.02x
- 99% likely to have a speedup of 1.00x
