
# Results vs. 3.11.0

- fork: python
- ref: v3.13.0a1
- machine: windows-amd64
- commit hash: ad056f0
- commit date: 2023-10-13
- overall geometric mean: 1.05x faster \*
- HPT reliability: 99.83%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231013-pythonperf1-amd64-python-v3.13.0a1-3.13.0a1-ad056f0 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| 2to3           | 207 ms                                                      | 216 ms: 1.04x slower                                            |
| chameleon      | 5.35 ms                                                     | 4.98 ms: 1.07x faster                                           |
| docutils       | 1.59 sec                                                    | 1.61 sec: 1.01x slower                                          |
| Geometric mean | (ref)                                                       | 1.01x faster                                                    |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231013-pythonperf1-amd64-python-v3.13.0a1-3.13.0a1-ad056f0 |
|----------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| async_tree_none            | 314 ms                                                      | 267 ms: 1.18x faster                                            |
| async_tree_cpu_io_mixed    | 495 ms                                                      | 455 ms: 1.09x faster                                            |
| async_tree_memoization     | 367 ms                                                      | 340 ms: 1.08x faster                                            |
| async_tree_memoization_tg  | 380 ms                                                      | 359 ms: 1.06x faster                                            |
| async_tree_none_tg         | 299 ms                                                      | 285 ms: 1.05x faster                                            |
| async_tree_io              | 753 ms                                                      | 723 ms: 1.04x faster                                            |
| async_tree_cpu_io_mixed_tg | 503 ms                                                      | 486 ms: 1.03x faster                                            |
| async_tree_io_tg           | 795 ms                                                      | 772 ms: 1.03x faster                                            |
| Geometric mean             | (ref)                                                       | 1.07x faster                                                    |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231013-pythonperf1-amd64-python-v3.13.0a1-3.13.0a1-ad056f0 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| float          | 54.4 ms                                                     | 53.6 ms: 1.01x faster                                           |
| pidigits       | 149 ms                                                      | 150 ms: 1.01x slower                                            |
| nbody          | 69.3 ms                                                     | 72.2 ms: 1.04x slower                                           |
| Geometric mean | (ref)                                                       | 1.01x slower                                                    |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231013-pythonperf1-amd64-python-v3.13.0a1-3.13.0a1-ad056f0 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| regex_dna      | 121 ms                                                      | 119 ms: 1.02x faster                                            |
| regex_effbot   | 1.52 ms                                                     | 1.60 ms: 1.05x slower                                           |
| regex_v8       | 13.7 ms                                                     | 14.8 ms: 1.08x slower                                           |
| Geometric mean | (ref)                                                       | 1.03x slower                                                    |

Benchmark hidden because not significant (1): regex_compile

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231013-pythonperf1-amd64-python-v3.13.0a1-3.13.0a1-ad056f0 |
|----------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| json_dumps           | 7.90 ms                                                     | 5.60 ms: 1.41x faster                                           |
| unpickle_pure_python | 152 us                                                      | 137 us: 1.11x faster                                            |
| pickle_pure_python   | 207 us                                                      | 190 us: 1.09x faster                                            |
| xml_etree_parse      | 94.5 ms                                                     | 91.6 ms: 1.03x faster                                           |
| xml_etree_iterparse  | 63.0 ms                                                     | 64.0 ms: 1.02x slower                                           |
| xml_etree_process    | 37.0 ms                                                     | 38.2 ms: 1.03x slower                                           |
| pickle_dict          | 17.8 us                                                     | 18.4 us: 1.03x slower                                           |
| unpickle             | 7.82 us                                                     | 8.12 us: 1.04x slower                                           |
| tomli_loads          | 1.42 sec                                                    | 1.48 sec: 1.04x slower                                          |
| json_loads           | 12.9 us                                                     | 13.5 us: 1.05x slower                                           |
| xml_etree_generate   | 52.2 ms                                                     | 55.4 ms: 1.06x slower                                           |
| unpickle_list        | 2.57 us                                                     | 2.74 us: 1.07x slower                                           |
| pickle               | 6.53 us                                                     | 6.98 us: 1.07x slower                                           |
| pickle_list          | 2.68 us                                                     | 2.94 us: 1.10x slower                                           |
| Geometric mean       | (ref)                                                       | 1.01x faster                                                    |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231013-pythonperf1-amd64-python-v3.13.0a1-3.13.0a1-ad056f0 |
|------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| python_startup         | 18.8 ms                                                     | 19.7 ms: 1.04x slower                                           |
| python_startup_no_site | 15.5 ms                                                     | 16.2 ms: 1.05x slower                                           |
| Geometric mean         | (ref)                                                       | 1.04x slower                                                    |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231013-pythonperf1-amd64-python-v3.13.0a1-3.13.0a1-ad056f0 |
|-----------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| mako      | 7.55 ms                                                     | 7.20 ms: 1.05x faster                                           |

All benchmarks:
===============

| Benchmark                  | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231013-pythonperf1-amd64-python-v3.13.0a1-3.13.0a1-ad056f0 |
|----------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| typing_runtime_protocols   | 320 us                                                      | 96.3 us: 3.32x faster                                           |
| generators                 | 34.0 ms                                                     | 22.3 ms: 1.52x faster                                           |
| json_dumps                 | 7.90 ms                                                     | 5.60 ms: 1.41x faster                                           |
| asyncio_tcp                | 614 ms                                                      | 470 ms: 1.31x faster                                            |
| unpack_sequence            | 47.0 ns                                                     | 38.5 ns: 1.22x faster                                           |
| raytrace                   | 211 ms                                                      | 174 ms: 1.21x faster                                            |
| deltablue                  | 2.63 ms                                                     | 2.19 ms: 1.20x faster                                           |
| richards_super             | 37.9 ms                                                     | 32.0 ms: 1.18x faster                                           |
| async_tree_none            | 314 ms                                                      | 267 ms: 1.18x faster                                            |
| chaos                      | 46.8 ms                                                     | 40.4 ms: 1.16x faster                                           |
| sqlglot_parse              | 939 us                                                      | 811 us: 1.16x faster                                            |
| mdp                        | 1.73 sec                                                    | 1.49 sec: 1.16x faster                                          |
| nqueens                    | 66.1 ms                                                     | 59.1 ms: 1.12x faster                                           |
| logging_silent             | 70.7 ns                                                     | 63.2 ns: 1.12x faster                                           |
| sqlglot_transpile          | 1.15 ms                                                     | 1.03 ms: 1.12x faster                                           |
| crypto_pyaes               | 48.2 ms                                                     | 43.3 ms: 1.11x faster                                           |
| spectral_norm              | 69.9 ms                                                     | 63.0 ms: 1.11x faster                                           |
| unpickle_pure_python       | 152 us                                                      | 137 us: 1.11x faster                                            |
| hexiom                     | 4.51 ms                                                     | 4.09 ms: 1.10x faster                                           |
| comprehensions             | 15.6 us                                                     | 14.2 us: 1.10x faster                                           |
| go                         | 98.8 ms                                                     | 90.0 ms: 1.10x faster                                           |
| sympy_sum                  | 100.0 ms                                                    | 91.1 ms: 1.10x faster                                           |
| pickle_pure_python         | 207 us                                                      | 190 us: 1.09x faster                                            |
| scimark_monte_carlo        | 44.6 ms                                                     | 41.0 ms: 1.09x faster                                           |
| sqlite_synth               | 1.79 us                                                     | 1.65 us: 1.09x faster                                           |
| async_tree_cpu_io_mixed    | 495 ms                                                      | 455 ms: 1.09x faster                                            |
| mypy2                      | 226 ms                                                      | 209 ms: 1.08x faster                                            |
| async_tree_memoization     | 367 ms                                                      | 340 ms: 1.08x faster                                            |
| chameleon                  | 5.35 ms                                                     | 4.98 ms: 1.07x faster                                           |
| asyncio_tcp_ssl            | 2.02 sec                                                    | 1.89 sec: 1.07x faster                                          |
| richards                   | 30.8 ms                                                     | 28.8 ms: 1.07x faster                                           |
| scimark_lu                 | 62.3 ms                                                     | 58.6 ms: 1.06x faster                                           |
| scimark_sparse_mat_mult    | 2.59 ms                                                     | 2.45 ms: 1.06x faster                                           |
| async_tree_memoization_tg  | 380 ms                                                      | 359 ms: 1.06x faster                                            |
| deepcopy                   | 242 us                                                      | 230 us: 1.05x faster                                            |
| sympy_str                  | 184 ms                                                      | 175 ms: 1.05x faster                                            |
| async_tree_none_tg         | 299 ms                                                      | 285 ms: 1.05x faster                                            |
| mako                       | 7.55 ms                                                     | 7.20 ms: 1.05x faster                                           |
| sympy_expand               | 299 ms                                                      | 287 ms: 1.04x faster                                            |
| sympy_integrate            | 13.7 ms                                                     | 13.1 ms: 1.04x faster                                           |
| async_tree_io              | 753 ms                                                      | 723 ms: 1.04x faster                                            |
| sqlglot_normalize          | 191 ms                                                      | 184 ms: 1.04x faster                                            |
| logging_format             | 7.06 us                                                     | 6.81 us: 1.04x faster                                           |
| async_tree_cpu_io_mixed_tg | 503 ms                                                      | 486 ms: 1.03x faster                                            |
| xml_etree_parse            | 94.5 ms                                                     | 91.6 ms: 1.03x faster                                           |
| scimark_fft                | 181 ms                                                      | 176 ms: 1.03x faster                                            |
| logging_simple             | 6.60 us                                                     | 6.40 us: 1.03x faster                                           |
| pprint_pformat             | 1.06 sec                                                    | 1.03 sec: 1.03x faster                                          |
| async_tree_io_tg           | 795 ms                                                      | 772 ms: 1.03x faster                                            |
| deepcopy_memo              | 25.5 us                                                     | 24.8 us: 1.03x faster                                           |
| pprint_safe_repr           | 519 ms                                                      | 507 ms: 1.02x faster                                            |
| pyflate                    | 305 ms                                                      | 298 ms: 1.02x faster                                            |
| regex_dna                  | 121 ms                                                      | 119 ms: 1.02x faster                                            |
| float                      | 54.4 ms                                                     | 53.6 ms: 1.01x faster                                           |
| sqlglot_optimize           | 35.1 ms                                                     | 34.8 ms: 1.01x faster                                           |
| meteor_contest             | 75.0 ms                                                     | 74.5 ms: 1.01x faster                                           |
| fannkuch                   | 248 ms                                                      | 249 ms: 1.01x slower                                            |
| scimark_sor                | 76.4 ms                                                     | 77.0 ms: 1.01x slower                                           |
| pidigits                   | 149 ms                                                      | 150 ms: 1.01x slower                                            |
| docutils                   | 1.59 sec                                                    | 1.61 sec: 1.01x slower                                          |
| xml_etree_iterparse        | 63.0 ms                                                     | 64.0 ms: 1.02x slower                                           |
| gc_traversal               | 1.46 ms                                                     | 1.49 ms: 1.02x slower                                           |
| dulwich_log                | 44.1 ms                                                     | 45.2 ms: 1.03x slower                                           |
| create_gc_cycles           | 706 us                                                      | 728 us: 1.03x slower                                            |
| xml_etree_process          | 37.0 ms                                                     | 38.2 ms: 1.03x slower                                           |
| pickle_dict                | 17.8 us                                                     | 18.4 us: 1.03x slower                                           |
| unpickle                   | 7.82 us                                                     | 8.12 us: 1.04x slower                                           |
| tomli_loads                | 1.42 sec                                                    | 1.48 sec: 1.04x slower                                          |
| 2to3                       | 207 ms                                                      | 216 ms: 1.04x slower                                            |
| nbody                      | 69.3 ms                                                     | 72.2 ms: 1.04x slower                                           |
| python_startup             | 18.8 ms                                                     | 19.7 ms: 1.04x slower                                           |
| python_startup_no_site     | 15.5 ms                                                     | 16.2 ms: 1.05x slower                                           |
| bench_mp_pool              | 61.1 ms                                                     | 64.0 ms: 1.05x slower                                           |
| json_loads                 | 12.9 us                                                     | 13.5 us: 1.05x slower                                           |
| regex_effbot               | 1.52 ms                                                     | 1.60 ms: 1.05x slower                                           |
| coverage                   | 43.0 ms                                                     | 45.4 ms: 1.06x slower                                           |
| xml_etree_generate         | 52.2 ms                                                     | 55.4 ms: 1.06x slower                                           |
| unpickle_list              | 2.57 us                                                     | 2.74 us: 1.07x slower                                           |
| pickle                     | 6.53 us                                                     | 6.98 us: 1.07x slower                                           |
| regex_v8                   | 13.7 ms                                                     | 14.8 ms: 1.08x slower                                           |
| pickle_list                | 2.68 us                                                     | 2.94 us: 1.10x slower                                           |
| pathlib                    | 69.4 ms                                                     | 78.5 ms: 1.13x slower                                           |
| telco                      | 3.93 ms                                                     | 4.73 ms: 1.20x slower                                           |
| pycparser                  | 705 ms                                                      | 861 ms: 1.22x slower                                            |
| async_generators           | 181 ms                                                      | 236 ms: 1.30x slower                                            |
| Geometric mean             | (ref)                                                       | 1.05x faster                                                    |

Benchmark hidden because not significant (6): bench_thread_pool, tornado_http, regex_compile, deepcopy_reduce, coroutines, json
Ignored benchmarks (11) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, dask, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift


# HPT report

- Reliability score: 99.83% likely to be faster
- 90% likely to have a speedup of 1.02x
- 95% likely to have a speedup of 1.01x
- 99% likely to have a speedup of 1.00x
