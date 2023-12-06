
# Results vs. 3.11.0

- fork: python
- ref: main
- machine: linux-x86_64
- commit hash: e57ecf6
- commit date: 2023-09-16
- overall geometric mean: 1.05x faster
- HPT reliability: 89.86%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230916-pythonperf2-x86_64-python-main-3.13.0a0-e57ecf6 |
|----------------|:------------------------------------------------------------:|:-----------------------------------------------------------:|
| docutils       | 2.86 sec                                                     | 2.87 sec: 1.00x slower                                      |
| Geometric mean | (ref)                                                        | 1.00x faster                                                |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230916-pythonperf2-x86_64-python-main-3.13.0a0-e57ecf6 |
|----------------|:------------------------------------------------------------:|:-----------------------------------------------------------:|
| nbody          | 90.7 ms                                                      | 86.2 ms: 1.05x faster                                       |
| pidigits       | 251 ms                                                       | 264 ms: 1.05x slower                                        |
| float          | 74.2 ms                                                      | 80.0 ms: 1.08x slower                                       |
| Geometric mean | (ref)                                                        | 1.03x slower                                                |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230916-pythonperf2-x86_64-python-main-3.13.0a0-e57ecf6 |
|----------------|:------------------------------------------------------------:|:-----------------------------------------------------------:|
| regex_compile  | 158 ms                                                       | 149 ms: 1.06x faster                                        |
| regex_effbot   | 3.50 ms                                                      | 3.61 ms: 1.03x slower                                       |
| regex_v8       | 23.9 ms                                                      | 25.5 ms: 1.06x slower                                       |
| regex_dna      | 227 ms                                                       | 245 ms: 1.08x slower                                        |
| Geometric mean | (ref)                                                        | 1.03x slower                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230916-pythonperf2-x86_64-python-main-3.13.0a0-e57ecf6 |
|----------------------|:------------------------------------------------------------:|:-----------------------------------------------------------:|
| json_dumps           | 13.4 ms                                                      | 10.6 ms: 1.26x faster                                       |
| json_loads           | 28.7 us                                                      | 24.9 us: 1.15x faster                                       |
| unpickle_pure_python | 241 us                                                       | 221 us: 1.09x faster                                        |
| xml_etree_parse      | 158 ms                                                       | 150 ms: 1.05x faster                                        |
| tomli_loads          | 2.26 sec                                                     | 2.22 sec: 1.02x faster                                      |
| pickle_pure_python   | 319 us                                                       | 317 us: 1.01x faster                                        |
| xml_etree_iterparse  | 104 ms                                                       | 106 ms: 1.01x slower                                        |
| unpickle_list        | 4.53 us                                                      | 4.67 us: 1.03x slower                                       |
| xml_etree_process    | 56.5 ms                                                      | 58.7 ms: 1.04x slower                                       |
| pickle               | 9.64 us                                                      | 10.1 us: 1.05x slower                                       |
| pickle_dict          | 30.8 us                                                      | 32.6 us: 1.06x slower                                       |
| xml_etree_generate   | 80.5 ms                                                      | 86.0 ms: 1.07x slower                                       |
| unpickle             | 13.4 us                                                      | 14.6 us: 1.09x slower                                       |
| pickle_list          | 3.83 us                                                      | 4.37 us: 1.14x slower                                       |
| Geometric mean       | (ref)                                                        | 1.00x faster                                                |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230916-pythonperf2-x86_64-python-main-3.13.0a0-e57ecf6 |
|------------------------|:------------------------------------------------------------:|:-----------------------------------------------------------:|
| python_startup_no_site | 7.76 ms                                                      | 8.68 ms: 1.12x slower                                       |
| python_startup         | 10.8 ms                                                      | 12.7 ms: 1.18x slower                                       |
| Geometric mean         | (ref)                                                        | 1.15x slower                                                |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230916-pythonperf2-x86_64-python-main-3.13.0a0-e57ecf6 |
|-----------|:------------------------------------------------------------:|:-----------------------------------------------------------:|
| mako      | 11.0 ms                                                      | 10.3 ms: 1.07x faster                                       |

All benchmarks:
===============

| Benchmark                | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230916-pythonperf2-x86_64-python-main-3.13.0a0-e57ecf6 |
|--------------------------|:------------------------------------------------------------:|:-----------------------------------------------------------:|
| typing_runtime_protocols | 523 us                                                       | 150 us: 3.47x faster                                        |
| asyncio_tcp              | 753 ms                                                       | 371 ms: 2.03x faster                                        |
| asyncio_tcp_ssl          | 3.08 sec                                                     | 1.58 sec: 1.95x faster                                      |
| generators               | 56.0 ms                                                      | 34.7 ms: 1.61x faster                                       |
| chaos                    | 80.9 ms                                                      | 62.1 ms: 1.30x faster                                       |
| json_dumps               | 13.4 ms                                                      | 10.6 ms: 1.26x faster                                       |
| mypy2                    | 451 ms                                                       | 370 ms: 1.22x faster                                        |
| coroutines               | 27.6 ms                                                      | 23.1 ms: 1.19x faster                                       |
| async_tree_none          | 519 ms                                                       | 436 ms: 1.19x faster                                        |
| raytrace                 | 317 ms                                                       | 270 ms: 1.17x faster                                        |
| json_loads               | 28.7 us                                                      | 24.9 us: 1.15x faster                                       |
| nqueens                  | 103 ms                                                       | 89.5 ms: 1.15x faster                                       |
| async_tree_memoization   | 630 ms                                                       | 552 ms: 1.14x faster                                        |
| crypto_pyaes             | 83.4 ms                                                      | 73.5 ms: 1.13x faster                                       |
| comprehensions           | 24.6 us                                                      | 21.9 us: 1.12x faster                                       |
| scimark_lu               | 115 ms                                                       | 102 ms: 1.12x faster                                        |
| hexiom                   | 7.13 ms                                                      | 6.50 ms: 1.10x faster                                       |
| json                     | 5.65 ms                                                      | 5.16 ms: 1.10x faster                                       |
| deltablue                | 4.00 ms                                                      | 3.66 ms: 1.09x faster                                       |
| unpickle_pure_python     | 241 us                                                       | 221 us: 1.09x faster                                        |
| sqlglot_parse            | 1.53 ms                                                      | 1.41 ms: 1.09x faster                                       |
| sqlglot_normalize        | 126 ms                                                       | 116 ms: 1.09x faster                                        |
| async_tree_io            | 1.17 sec                                                     | 1.09 sec: 1.08x faster                                      |
| mdp                      | 2.75 sec                                                     | 2.55 sec: 1.08x faster                                      |
| async_tree_cpu_io_mixed  | 749 ms                                                       | 702 ms: 1.07x faster                                        |
| mako                     | 11.0 ms                                                      | 10.3 ms: 1.07x faster                                       |
| logging_format           | 8.11 us                                                      | 7.61 us: 1.07x faster                                       |
| regex_compile            | 158 ms                                                       | 149 ms: 1.06x faster                                        |
| fannkuch                 | 429 ms                                                       | 405 ms: 1.06x faster                                        |
| sqlglot_transpile        | 1.92 ms                                                      | 1.82 ms: 1.06x faster                                       |
| xml_etree_parse          | 158 ms                                                       | 150 ms: 1.05x faster                                        |
| nbody                    | 90.7 ms                                                      | 86.2 ms: 1.05x faster                                       |
| bench_thread_pool        | 1.01 ms                                                      | 970 us: 1.04x faster                                        |
| coverage                 | 84.8 ms                                                      | 81.5 ms: 1.04x faster                                       |
| deepcopy                 | 399 us                                                       | 384 us: 1.04x faster                                        |
| logging_simple           | 7.19 us                                                      | 6.95 us: 1.03x faster                                       |
| logging_silent           | 101 ns                                                       | 97.7 ns: 1.03x faster                                       |
| pycparser                | 1.32 sec                                                     | 1.29 sec: 1.03x faster                                      |
| spectral_norm            | 93.3 ms                                                      | 91.2 ms: 1.02x faster                                       |
| sqlglot_optimize         | 59.8 ms                                                      | 58.7 ms: 1.02x faster                                       |
| tomli_loads              | 2.26 sec                                                     | 2.22 sec: 1.02x faster                                      |
| deepcopy_memo            | 38.8 us                                                      | 38.3 us: 1.01x faster                                       |
| deepcopy_reduce          | 3.51 us                                                      | 3.47 us: 1.01x faster                                       |
| pickle_pure_python       | 319 us                                                       | 317 us: 1.01x faster                                        |
| meteor_contest           | 131 ms                                                       | 131 ms: 1.00x slower                                        |
| docutils                 | 2.86 sec                                                     | 2.87 sec: 1.00x slower                                      |
| unpack_sequence          | 45.6 ns                                                      | 46.2 ns: 1.01x slower                                       |
| xml_etree_iterparse      | 104 ms                                                       | 106 ms: 1.01x slower                                        |
| scimark_monte_carlo      | 68.2 ms                                                      | 70.1 ms: 1.03x slower                                       |
| pprint_pformat           | 1.63 sec                                                     | 1.68 sec: 1.03x slower                                      |
| unpickle_list            | 4.53 us                                                      | 4.67 us: 1.03x slower                                       |
| regex_effbot             | 3.50 ms                                                      | 3.61 ms: 1.03x slower                                       |
| pathlib                  | 19.1 ms                                                      | 19.7 ms: 1.03x slower                                       |
| richards_super           | 61.0 ms                                                      | 63.3 ms: 1.04x slower                                       |
| go                       | 164 ms                                                       | 170 ms: 1.04x slower                                        |
| xml_etree_process        | 56.5 ms                                                      | 58.7 ms: 1.04x slower                                       |
| scimark_fft              | 285 ms                                                       | 298 ms: 1.05x slower                                        |
| scimark_sparse_mat_mult  | 4.05 ms                                                      | 4.24 ms: 1.05x slower                                       |
| pidigits                 | 251 ms                                                       | 264 ms: 1.05x slower                                        |
| create_gc_cycles         | 1.61 ms                                                      | 1.69 ms: 1.05x slower                                       |
| pickle                   | 9.64 us                                                      | 10.1 us: 1.05x slower                                       |
| pprint_safe_repr         | 784 ms                                                       | 827 ms: 1.06x slower                                        |
| pickle_dict              | 30.8 us                                                      | 32.6 us: 1.06x slower                                       |
| regex_v8                 | 23.9 ms                                                      | 25.5 ms: 1.06x slower                                       |
| xml_etree_generate       | 80.5 ms                                                      | 86.0 ms: 1.07x slower                                       |
| regex_dna                | 227 ms                                                       | 245 ms: 1.08x slower                                        |
| float                    | 74.2 ms                                                      | 80.0 ms: 1.08x slower                                       |
| sqlite_synth             | 2.50 us                                                      | 2.70 us: 1.08x slower                                       |
| unpickle                 | 13.4 us                                                      | 14.6 us: 1.09x slower                                       |
| python_startup_no_site   | 7.76 ms                                                      | 8.68 ms: 1.12x slower                                       |
| pickle_list              | 3.83 us                                                      | 4.37 us: 1.14x slower                                       |
| pyflate                  | 449 ms                                                       | 516 ms: 1.15x slower                                        |
| python_startup           | 10.8 ms                                                      | 12.7 ms: 1.18x slower                                       |
| telco                    | 6.86 ms                                                      | 8.11 ms: 1.18x slower                                       |
| richards                 | 48.3 ms                                                      | 57.6 ms: 1.19x slower                                       |
| async_generators         | 316 ms                                                       | 393 ms: 1.25x slower                                        |
| scimark_sor              | 111 ms                                                       | 150 ms: 1.35x slower                                        |
| dask                     | 410 ms                                                       | 589 ms: 1.44x slower                                        |
| Geometric mean           | (ref)                                                        | 1.05x faster                                                |

Benchmark hidden because not significant (4): bench_mp_pool, tornado_http, gc_traversal, dulwich_log
Ignored benchmarks (17) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509.json: 2to3, aiohttp, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 89.86% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
