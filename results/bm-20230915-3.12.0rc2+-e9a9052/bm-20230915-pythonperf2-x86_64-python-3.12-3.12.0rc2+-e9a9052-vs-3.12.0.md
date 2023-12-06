
# Results vs. 3.12.0

- fork: python
- ref: 3.12
- machine: linux-x86_64
- commit hash: e9a9052
- commit date: 2023-09-15
- overall geometric mean: 1.00x slower
- HPT reliability: 73.75%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230915-pythonperf2-x86_64-python-3.12-3.12.0rc2+-e9a9052 |
|----------------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| 2to3           | 287 ms                                                       | 285 ms: 1.01x faster                                          |
| Geometric mean | (ref)                                                        | 1.00x faster                                                  |

Benchmark hidden because not significant (2): docutils, tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230915-pythonperf2-x86_64-python-3.12-3.12.0rc2+-e9a9052 |
|----------------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| nbody          | 94.1 ms                                                      | 88.9 ms: 1.06x faster                                         |
| float          | 78.5 ms                                                      | 78.1 ms: 1.01x faster                                         |
| pidigits       | 264 ms                                                       | 264 ms: 1.00x slower                                          |
| Geometric mean | (ref)                                                        | 1.02x faster                                                  |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230915-pythonperf2-x86_64-python-3.12-3.12.0rc2+-e9a9052 |
|----------------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| regex_v8       | 25.0 ms                                                      | 23.2 ms: 1.07x faster                                         |
| regex_dna      | 241 ms                                                       | 237 ms: 1.02x faster                                          |
| regex_compile  | 146 ms                                                       | 145 ms: 1.00x faster                                          |
| regex_effbot   | 3.47 ms                                                      | 3.62 ms: 1.04x slower                                         |
| Geometric mean | (ref)                                                        | 1.01x faster                                                  |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230915-pythonperf2-x86_64-python-3.12-3.12.0rc2+-e9a9052 |
|----------------------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| tomli_loads          | 2.20 sec                                                     | 2.13 sec: 1.03x faster                                        |
| unpickle             | 14.8 us                                                      | 14.5 us: 1.02x faster                                         |
| pickle_pure_python   | 323 us                                                       | 318 us: 1.02x faster                                          |
| unpickle_pure_python | 207 us                                                       | 207 us: 1.00x slower                                          |
| json_dumps           | 10.2 ms                                                      | 10.3 ms: 1.01x slower                                         |
| json_loads           | 24.3 us                                                      | 24.5 us: 1.01x slower                                         |
| xml_etree_process    | 58.3 ms                                                      | 59.0 ms: 1.01x slower                                         |
| unpickle_list        | 4.77 us                                                      | 4.82 us: 1.01x slower                                         |
| xml_etree_parse      | 146 ms                                                       | 148 ms: 1.01x slower                                          |
| pickle               | 10.1 us                                                      | 10.3 us: 1.02x slower                                         |
| pickle_dict          | 31.7 us                                                      | 32.4 us: 1.02x slower                                         |
| xml_etree_iterparse  | 103 ms                                                       | 106 ms: 1.03x slower                                          |
| pickle_list          | 4.39 us                                                      | 4.51 us: 1.03x slower                                         |
| Geometric mean       | (ref)                                                        | 1.01x slower                                                  |

Benchmark hidden because not significant (1): xml_etree_generate

Benchmarks with tag 'startup':
==============================

Benchmark hidden because not significant (2): python_startup_no_site, python_startup

Benchmarks with tag 'template':
===============================

Benchmark hidden because not significant (1): mako

All benchmarks:
===============

| Benchmark                | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230915-pythonperf2-x86_64-python-3.12-3.12.0rc2+-e9a9052 |
|--------------------------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| bench_mp_pool            | 5.34 ms                                                      | 4.55 ms: 1.17x faster                                         |
| regex_v8                 | 25.0 ms                                                      | 23.2 ms: 1.07x faster                                         |
| nbody                    | 94.1 ms                                                      | 88.9 ms: 1.06x faster                                         |
| tomli_loads              | 2.20 sec                                                     | 2.13 sec: 1.03x faster                                        |
| scimark_monte_carlo      | 72.4 ms                                                      | 70.5 ms: 1.03x faster                                         |
| scimark_lu               | 101 ms                                                       | 98.2 ms: 1.02x faster                                         |
| deepcopy_reduce          | 3.46 us                                                      | 3.38 us: 1.02x faster                                         |
| deepcopy                 | 376 us                                                       | 367 us: 1.02x faster                                          |
| unpickle                 | 14.8 us                                                      | 14.5 us: 1.02x faster                                         |
| deepcopy_memo            | 37.4 us                                                      | 36.7 us: 1.02x faster                                         |
| pickle_pure_python       | 323 us                                                       | 318 us: 1.02x faster                                          |
| regex_dna                | 241 ms                                                       | 237 ms: 1.02x faster                                          |
| scimark_fft              | 304 ms                                                       | 300 ms: 1.01x faster                                          |
| scimark_sparse_mat_mult  | 4.42 ms                                                      | 4.37 ms: 1.01x faster                                         |
| pprint_safe_repr         | 823 ms                                                       | 813 ms: 1.01x faster                                          |
| meteor_contest           | 128 ms                                                       | 126 ms: 1.01x faster                                          |
| mdp                      | 2.53 sec                                                     | 2.50 sec: 1.01x faster                                        |
| scimark_sor              | 110 ms                                                       | 109 ms: 1.01x faster                                          |
| pprint_pformat           | 1.67 sec                                                     | 1.66 sec: 1.01x faster                                        |
| go                       | 150 ms                                                       | 149 ms: 1.01x faster                                          |
| hexiom                   | 5.96 ms                                                      | 5.89 ms: 1.01x faster                                         |
| pycparser                | 1.27 sec                                                     | 1.26 sec: 1.01x faster                                        |
| nqueens                  | 90.1 ms                                                      | 89.4 ms: 1.01x faster                                         |
| sqlglot_parse            | 1.40 ms                                                      | 1.39 ms: 1.01x faster                                         |
| sqlglot_transpile        | 1.80 ms                                                      | 1.79 ms: 1.01x faster                                         |
| 2to3                     | 287 ms                                                       | 285 ms: 1.01x faster                                          |
| logging_silent           | 95.6 ns                                                      | 95.1 ns: 1.01x faster                                         |
| spectral_norm            | 91.6 ms                                                      | 91.1 ms: 1.01x faster                                         |
| fannkuch                 | 350 ms                                                       | 348 ms: 1.01x faster                                          |
| float                    | 78.5 ms                                                      | 78.1 ms: 1.01x faster                                         |
| pyflate                  | 447 ms                                                       | 446 ms: 1.00x faster                                          |
| mypy2                    | 368 ms                                                       | 367 ms: 1.00x faster                                          |
| generators               | 36.7 ms                                                      | 36.6 ms: 1.00x faster                                         |
| regex_compile            | 146 ms                                                       | 145 ms: 1.00x faster                                          |
| pidigits                 | 264 ms                                                       | 264 ms: 1.00x slower                                          |
| unpickle_pure_python     | 207 us                                                       | 207 us: 1.00x slower                                          |
| async_generators         | 385 ms                                                       | 387 ms: 1.00x slower                                          |
| sqlglot_normalize        | 117 ms                                                       | 118 ms: 1.00x slower                                          |
| crypto_pyaes             | 80.9 ms                                                      | 81.4 ms: 1.01x slower                                         |
| dulwich_log              | 65.3 ms                                                      | 65.9 ms: 1.01x slower                                         |
| json_dumps               | 10.2 ms                                                      | 10.3 ms: 1.01x slower                                         |
| sqlite_synth             | 2.70 us                                                      | 2.73 us: 1.01x slower                                         |
| json_loads               | 24.3 us                                                      | 24.5 us: 1.01x slower                                         |
| xml_etree_process        | 58.3 ms                                                      | 59.0 ms: 1.01x slower                                         |
| unpickle_list            | 4.77 us                                                      | 4.82 us: 1.01x slower                                         |
| async_tree_cpu_io_mixed  | 706 ms                                                       | 715 ms: 1.01x slower                                          |
| async_tree_memoization   | 553 ms                                                       | 561 ms: 1.01x slower                                          |
| xml_etree_parse          | 146 ms                                                       | 148 ms: 1.01x slower                                          |
| async_tree_io            | 1.06 sec                                                     | 1.07 sec: 1.01x slower                                        |
| telco                    | 6.96 ms                                                      | 7.07 ms: 1.02x slower                                         |
| deltablue                | 3.29 ms                                                      | 3.34 ms: 1.02x slower                                         |
| async_tree_none          | 459 ms                                                       | 466 ms: 1.02x slower                                          |
| pickle                   | 10.1 us                                                      | 10.3 us: 1.02x slower                                         |
| pickle_dict              | 31.7 us                                                      | 32.4 us: 1.02x slower                                         |
| coverage                 | 89.6 ms                                                      | 91.8 ms: 1.02x slower                                         |
| xml_etree_iterparse      | 103 ms                                                       | 106 ms: 1.03x slower                                          |
| pickle_list              | 4.39 us                                                      | 4.51 us: 1.03x slower                                         |
| typing_runtime_protocols | 151 us                                                       | 156 us: 1.03x slower                                          |
| unpack_sequence          | 53.3 ns                                                      | 55.2 ns: 1.04x slower                                         |
| regex_effbot             | 3.47 ms                                                      | 3.62 ms: 1.04x slower                                         |
| logging_format           | 7.37 us                                                      | 7.70 us: 1.04x slower                                         |
| logging_simple           | 6.73 us                                                      | 7.04 us: 1.05x slower                                         |
| raytrace                 | 302 ms                                                       | 316 ms: 1.05x slower                                          |
| gc_traversal             | 3.54 ms                                                      | 3.98 ms: 1.12x slower                                         |
| dask                     | 397 ms                                                       | 565 ms: 1.42x slower                                          |
| Geometric mean           | (ref)                                                        | 1.00x slower                                                  |

Benchmark hidden because not significant (18): bench_thread_pool, pathlib, coroutines, richards_super, docutils, tornado_http, comprehensions, python_startup_no_site, richards, xml_etree_generate, sqlglot_optimize, asyncio_tcp, json, asyncio_tcp_ssl, python_startup, mako, chaos, create_gc_cycles


# HPT report

- Reliability score: 73.75% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
