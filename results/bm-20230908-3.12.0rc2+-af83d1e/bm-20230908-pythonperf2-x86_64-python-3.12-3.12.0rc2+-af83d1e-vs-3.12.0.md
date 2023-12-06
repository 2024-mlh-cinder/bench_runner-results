
# Results vs. 3.12.0

- fork: python
- ref: 3.12
- machine: linux-x86_64
- commit hash: af83d1e
- commit date: 2023-09-08
- overall geometric mean: 1.00x faster
- HPT reliability: 93.81%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230908-pythonperf2-x86_64-python-3.12-3.12.0rc2+-af83d1e |
|----------------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| docutils       | 2.89 sec                                                     | 2.89 sec: 1.00x slower                                        |
| Geometric mean | (ref)                                                        | 1.00x faster                                                  |

Benchmark hidden because not significant (2): 2to3, tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230908-pythonperf2-x86_64-python-3.12-3.12.0rc2+-af83d1e |
|----------------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| nbody          | 94.1 ms                                                      | 85.4 ms: 1.10x faster                                         |
| pidigits       | 264 ms                                                       | 264 ms: 1.00x slower                                          |
| float          | 78.5 ms                                                      | 79.3 ms: 1.01x slower                                         |
| Geometric mean | (ref)                                                        | 1.03x faster                                                  |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230908-pythonperf2-x86_64-python-3.12-3.12.0rc2+-af83d1e |
|----------------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| regex_v8       | 25.0 ms                                                      | 23.3 ms: 1.07x faster                                         |
| regex_dna      | 241 ms                                                       | 238 ms: 1.01x faster                                          |
| regex_compile  | 146 ms                                                       | 146 ms: 1.00x slower                                          |
| regex_effbot   | 3.47 ms                                                      | 3.57 ms: 1.03x slower                                         |
| Geometric mean | (ref)                                                        | 1.01x faster                                                  |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230908-pythonperf2-x86_64-python-3.12-3.12.0rc2+-af83d1e |
|----------------------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| tomli_loads          | 2.20 sec                                                     | 2.14 sec: 1.03x faster                                        |
| xml_etree_iterparse  | 103 ms                                                       | 102 ms: 1.01x faster                                          |
| json_dumps           | 10.2 ms                                                      | 10.2 ms: 1.01x faster                                         |
| pickle_list          | 4.39 us                                                      | 4.41 us: 1.00x slower                                         |
| pickle_dict          | 31.7 us                                                      | 31.9 us: 1.01x slower                                         |
| xml_etree_generate   | 86.1 ms                                                      | 86.8 ms: 1.01x slower                                         |
| pickle_pure_python   | 323 us                                                       | 326 us: 1.01x slower                                          |
| unpickle             | 14.8 us                                                      | 15.0 us: 1.01x slower                                         |
| xml_etree_process    | 58.3 ms                                                      | 59.0 ms: 1.01x slower                                         |
| unpickle_pure_python | 207 us                                                       | 211 us: 1.02x slower                                          |
| Geometric mean       | (ref)                                                        | 1.00x slower                                                  |

Benchmark hidden because not significant (4): xml_etree_parse, unpickle_list, json_loads, pickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230908-pythonperf2-x86_64-python-3.12-3.12.0rc2+-af83d1e |
|------------------------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| python_startup_no_site | 8.70 ms                                                      | 8.68 ms: 1.00x faster                                         |
| python_startup         | 11.7 ms                                                      | 11.7 ms: 1.00x faster                                         |
| Geometric mean         | (ref)                                                        | 1.00x faster                                                  |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230908-pythonperf2-x86_64-python-3.12-3.12.0rc2+-af83d1e |
|-----------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| mako      | 9.94 ms                                                      | 9.87 ms: 1.01x faster                                         |

All benchmarks:
===============

| Benchmark                | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230908-pythonperf2-x86_64-python-3.12-3.12.0rc2+-af83d1e |
|--------------------------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| bench_mp_pool            | 5.34 ms                                                      | 4.61 ms: 1.16x faster                                         |
| unpack_sequence          | 53.3 ns                                                      | 47.3 ns: 1.13x faster                                         |
| nbody                    | 94.1 ms                                                      | 85.4 ms: 1.10x faster                                         |
| regex_v8                 | 25.0 ms                                                      | 23.3 ms: 1.07x faster                                         |
| create_gc_cycles         | 1.67 ms                                                      | 1.61 ms: 1.04x faster                                         |
| scimark_monte_carlo      | 72.4 ms                                                      | 70.0 ms: 1.03x faster                                         |
| pycparser                | 1.27 sec                                                     | 1.24 sec: 1.03x faster                                        |
| tomli_loads              | 2.20 sec                                                     | 2.14 sec: 1.03x faster                                        |
| richards_super           | 51.7 ms                                                      | 50.8 ms: 1.02x faster                                         |
| richards                 | 45.0 ms                                                      | 44.2 ms: 1.02x faster                                         |
| fannkuch                 | 350 ms                                                       | 344 ms: 1.02x faster                                          |
| scimark_lu               | 101 ms                                                       | 99.0 ms: 1.02x faster                                         |
| meteor_contest           | 128 ms                                                       | 126 ms: 1.01x faster                                          |
| async_generators         | 385 ms                                                       | 381 ms: 1.01x faster                                          |
| async_tree_io            | 1.06 sec                                                     | 1.05 sec: 1.01x faster                                        |
| regex_dna                | 241 ms                                                       | 238 ms: 1.01x faster                                          |
| coverage                 | 89.6 ms                                                      | 88.7 ms: 1.01x faster                                         |
| deltablue                | 3.29 ms                                                      | 3.26 ms: 1.01x faster                                         |
| async_tree_memoization   | 553 ms                                                       | 548 ms: 1.01x faster                                          |
| coroutines               | 23.0 ms                                                      | 22.8 ms: 1.01x faster                                         |
| xml_etree_iterparse      | 103 ms                                                       | 102 ms: 1.01x faster                                          |
| async_tree_none          | 459 ms                                                       | 455 ms: 1.01x faster                                          |
| json_dumps               | 10.2 ms                                                      | 10.2 ms: 1.01x faster                                         |
| json                     | 5.14 ms                                                      | 5.11 ms: 1.01x faster                                         |
| mako                     | 9.94 ms                                                      | 9.87 ms: 1.01x faster                                         |
| go                       | 150 ms                                                       | 150 ms: 1.01x faster                                          |
| scimark_sor              | 110 ms                                                       | 109 ms: 1.01x faster                                          |
| crypto_pyaes             | 80.9 ms                                                      | 80.5 ms: 1.00x faster                                         |
| python_startup_no_site   | 8.70 ms                                                      | 8.68 ms: 1.00x faster                                         |
| python_startup           | 11.7 ms                                                      | 11.7 ms: 1.00x faster                                         |
| scimark_sparse_mat_mult  | 4.42 ms                                                      | 4.44 ms: 1.00x slower                                         |
| docutils                 | 2.89 sec                                                     | 2.89 sec: 1.00x slower                                        |
| spectral_norm            | 91.6 ms                                                      | 91.9 ms: 1.00x slower                                         |
| pidigits                 | 264 ms                                                       | 264 ms: 1.00x slower                                          |
| regex_compile            | 146 ms                                                       | 146 ms: 1.00x slower                                          |
| nqueens                  | 90.1 ms                                                      | 90.4 ms: 1.00x slower                                         |
| pathlib                  | 19.8 ms                                                      | 19.9 ms: 1.00x slower                                         |
| pickle_list              | 4.39 us                                                      | 4.41 us: 1.00x slower                                         |
| asyncio_tcp              | 381 ms                                                       | 383 ms: 1.00x slower                                          |
| deepcopy_reduce          | 3.46 us                                                      | 3.47 us: 1.00x slower                                         |
| sqlglot_optimize         | 57.8 ms                                                      | 58.1 ms: 1.01x slower                                         |
| pickle_dict              | 31.7 us                                                      | 31.9 us: 1.01x slower                                         |
| xml_etree_generate       | 86.1 ms                                                      | 86.8 ms: 1.01x slower                                         |
| deepcopy_memo            | 37.4 us                                                      | 37.8 us: 1.01x slower                                         |
| dulwich_log              | 65.3 ms                                                      | 65.9 ms: 1.01x slower                                         |
| chaos                    | 62.9 ms                                                      | 63.5 ms: 1.01x slower                                         |
| float                    | 78.5 ms                                                      | 79.3 ms: 1.01x slower                                         |
| pickle_pure_python       | 323 us                                                       | 326 us: 1.01x slower                                          |
| mdp                      | 2.53 sec                                                     | 2.56 sec: 1.01x slower                                        |
| unpickle                 | 14.8 us                                                      | 15.0 us: 1.01x slower                                         |
| xml_etree_process        | 58.3 ms                                                      | 59.0 ms: 1.01x slower                                         |
| raytrace                 | 302 ms                                                       | 305 ms: 1.01x slower                                          |
| sqlglot_normalize        | 117 ms                                                       | 119 ms: 1.02x slower                                          |
| logging_format           | 7.37 us                                                      | 7.51 us: 1.02x slower                                         |
| typing_runtime_protocols | 151 us                                                       | 155 us: 1.02x slower                                          |
| unpickle_pure_python     | 207 us                                                       | 211 us: 1.02x slower                                          |
| logging_simple           | 6.73 us                                                      | 6.89 us: 1.02x slower                                         |
| deepcopy                 | 376 us                                                       | 385 us: 1.03x slower                                          |
| regex_effbot             | 3.47 ms                                                      | 3.57 ms: 1.03x slower                                         |
| pyflate                  | 447 ms                                                       | 466 ms: 1.04x slower                                          |
| gc_traversal             | 3.54 ms                                                      | 3.76 ms: 1.06x slower                                         |
| dask                     | 397 ms                                                       | 567 ms: 1.43x slower                                          |
| Geometric mean           | (ref)                                                        | 1.00x faster                                                  |

Benchmark hidden because not significant (21): bench_thread_pool, async_tree_cpu_io_mixed, xml_etree_parse, sqlglot_transpile, tornado_http, unpickle_list, sqlglot_parse, 2to3, comprehensions, asyncio_tcp_ssl, hexiom, mypy2, generators, json_loads, pprint_pformat, pickle, scimark_fft, logging_silent, pprint_safe_repr, telco, sqlite_synth


# HPT report

- Reliability score: 93.81% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
