
# Results vs. 3.12.0

- fork: python
- ref: 3.12
- machine: linux-x86_64
- commit hash: 8882b30
- commit date: 2023-09-29
- overall geometric mean: 1.00x slower
- HPT reliability: 74.48%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230929-pythonperf2-x86_64-python-3.12-3.12.0rc3+-8882b30 |
|----------------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| 2to3           | 287 ms                                                       | 286 ms: 1.00x faster                                          |
| Geometric mean | (ref)                                                        | 1.00x slower                                                  |

Benchmark hidden because not significant (2): docutils, tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230929-pythonperf2-x86_64-python-3.12-3.12.0rc3+-8882b30 |
|----------------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| pidigits       | 264 ms                                                       | 265 ms: 1.00x slower                                          |
| Geometric mean | (ref)                                                        | 1.00x slower                                                  |

Benchmark hidden because not significant (2): float, nbody

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230929-pythonperf2-x86_64-python-3.12-3.12.0rc3+-8882b30 |
|----------------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| regex_v8       | 25.0 ms                                                      | 24.7 ms: 1.01x faster                                         |
| regex_compile  | 146 ms                                                       | 145 ms: 1.01x faster                                          |
| regex_dna      | 241 ms                                                       | 240 ms: 1.00x faster                                          |
| regex_effbot   | 3.47 ms                                                      | 3.57 ms: 1.03x slower                                         |
| Geometric mean | (ref)                                                        | 1.00x slower                                                  |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230929-pythonperf2-x86_64-python-3.12-3.12.0rc3+-8882b30 |
|----------------------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| pickle_list          | 4.39 us                                                      | 4.35 us: 1.01x faster                                         |
| tomli_loads          | 2.20 sec                                                     | 2.21 sec: 1.01x slower                                        |
| xml_etree_process    | 58.3 ms                                                      | 58.9 ms: 1.01x slower                                         |
| xml_etree_iterparse  | 103 ms                                                       | 104 ms: 1.01x slower                                          |
| unpickle_list        | 4.77 us                                                      | 4.82 us: 1.01x slower                                         |
| pickle_pure_python   | 323 us                                                       | 326 us: 1.01x slower                                          |
| pickle_dict          | 31.7 us                                                      | 32.1 us: 1.01x slower                                         |
| pickle               | 10.1 us                                                      | 10.2 us: 1.01x slower                                         |
| unpickle_pure_python | 207 us                                                       | 210 us: 1.01x slower                                          |
| Geometric mean       | (ref)                                                        | 1.01x slower                                                  |

Benchmark hidden because not significant (5): json_loads, unpickle, xml_etree_generate, json_dumps, xml_etree_parse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230929-pythonperf2-x86_64-python-3.12-3.12.0rc3+-8882b30 |
|------------------------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| python_startup_no_site | 8.70 ms                                                      | 8.67 ms: 1.00x faster                                         |
| Geometric mean         | (ref)                                                        | 1.00x faster                                                  |

Benchmark hidden because not significant (1): python_startup

Benchmarks with tag 'template':
===============================

Benchmark hidden because not significant (1): mako

All benchmarks:
===============

| Benchmark                | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230929-pythonperf2-x86_64-python-3.12-3.12.0rc3+-8882b30 |
|--------------------------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| bench_mp_pool            | 5.34 ms                                                      | 4.76 ms: 1.12x faster                                         |
| scimark_lu               | 101 ms                                                       | 97.8 ms: 1.03x faster                                         |
| scimark_fft              | 304 ms                                                       | 297 ms: 1.02x faster                                          |
| scimark_sor              | 110 ms                                                       | 108 ms: 1.02x faster                                          |
| scimark_sparse_mat_mult  | 4.42 ms                                                      | 4.33 ms: 1.02x faster                                         |
| pathlib                  | 19.8 ms                                                      | 19.4 ms: 1.02x faster                                         |
| logging_simple           | 6.73 us                                                      | 6.62 us: 1.02x faster                                         |
| coverage                 | 89.6 ms                                                      | 88.5 ms: 1.01x faster                                         |
| regex_v8                 | 25.0 ms                                                      | 24.7 ms: 1.01x faster                                         |
| scimark_monte_carlo      | 72.4 ms                                                      | 71.6 ms: 1.01x faster                                         |
| pyflate                  | 447 ms                                                       | 443 ms: 1.01x faster                                          |
| comprehensions           | 21.9 us                                                      | 21.7 us: 1.01x faster                                         |
| pickle_list              | 4.39 us                                                      | 4.35 us: 1.01x faster                                         |
| pprint_pformat           | 1.67 sec                                                     | 1.66 sec: 1.01x faster                                        |
| sqlglot_parse            | 1.40 ms                                                      | 1.40 ms: 1.01x faster                                         |
| regex_compile            | 146 ms                                                       | 145 ms: 1.01x faster                                          |
| generators               | 36.7 ms                                                      | 36.5 ms: 1.01x faster                                         |
| pprint_safe_repr         | 823 ms                                                       | 820 ms: 1.00x faster                                          |
| deepcopy                 | 376 us                                                       | 374 us: 1.00x faster                                          |
| deepcopy_reduce          | 3.46 us                                                      | 3.44 us: 1.00x faster                                         |
| 2to3                     | 287 ms                                                       | 286 ms: 1.00x faster                                          |
| logging_silent           | 95.6 ns                                                      | 95.3 ns: 1.00x faster                                         |
| meteor_contest           | 128 ms                                                       | 128 ms: 1.00x faster                                          |
| regex_dna                | 241 ms                                                       | 240 ms: 1.00x faster                                          |
| python_startup_no_site   | 8.70 ms                                                      | 8.67 ms: 1.00x faster                                         |
| deepcopy_memo            | 37.4 us                                                      | 37.3 us: 1.00x faster                                         |
| asyncio_tcp_ssl          | 1.58 sec                                                     | 1.57 sec: 1.00x faster                                        |
| async_tree_io            | 1.06 sec                                                     | 1.06 sec: 1.00x slower                                        |
| pidigits                 | 264 ms                                                       | 265 ms: 1.00x slower                                          |
| mdp                      | 2.53 sec                                                     | 2.54 sec: 1.00x slower                                        |
| tomli_loads              | 2.20 sec                                                     | 2.21 sec: 1.01x slower                                        |
| async_tree_none          | 459 ms                                                       | 462 ms: 1.01x slower                                          |
| coroutines               | 23.0 ms                                                      | 23.2 ms: 1.01x slower                                         |
| hexiom                   | 5.96 ms                                                      | 6.01 ms: 1.01x slower                                         |
| chaos                    | 62.9 ms                                                      | 63.4 ms: 1.01x slower                                         |
| xml_etree_process        | 58.3 ms                                                      | 58.9 ms: 1.01x slower                                         |
| xml_etree_iterparse      | 103 ms                                                       | 104 ms: 1.01x slower                                          |
| unpickle_list            | 4.77 us                                                      | 4.82 us: 1.01x slower                                         |
| pickle_pure_python       | 323 us                                                       | 326 us: 1.01x slower                                          |
| crypto_pyaes             | 80.9 ms                                                      | 81.8 ms: 1.01x slower                                         |
| pickle_dict              | 31.7 us                                                      | 32.1 us: 1.01x slower                                         |
| richards_super           | 51.7 ms                                                      | 52.3 ms: 1.01x slower                                         |
| pickle                   | 10.1 us                                                      | 10.2 us: 1.01x slower                                         |
| pycparser                | 1.27 sec                                                     | 1.29 sec: 1.01x slower                                        |
| telco                    | 6.96 ms                                                      | 7.06 ms: 1.01x slower                                         |
| unpickle_pure_python     | 207 us                                                       | 210 us: 1.01x slower                                          |
| typing_runtime_protocols | 151 us                                                       | 154 us: 1.01x slower                                          |
| spectral_norm            | 91.6 ms                                                      | 93.2 ms: 1.02x slower                                         |
| logging_format           | 7.37 us                                                      | 7.52 us: 1.02x slower                                         |
| fannkuch                 | 350 ms                                                       | 358 ms: 1.02x slower                                          |
| regex_effbot             | 3.47 ms                                                      | 3.57 ms: 1.03x slower                                         |
| gc_traversal             | 3.54 ms                                                      | 4.04 ms: 1.14x slower                                         |
| Geometric mean           | (ref)                                                        | 1.00x slower                                                  |

Benchmark hidden because not significant (31): bench_thread_pool, unpack_sequence, sqlglot_transpile, json, json_loads, asyncio_tcp, dulwich_log, float, mypy2, docutils, dask, python_startup, async_tree_memoization, sqlglot_optimize, sqlglot_normalize, async_generators, unpickle, async_tree_cpu_io_mixed, go, nbody, sqlite_synth, mako, nqueens, xml_etree_generate, deltablue, json_dumps, raytrace, tornado_http, xml_etree_parse, create_gc_cycles, richards


# HPT report

- Reliability score: 74.48% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
