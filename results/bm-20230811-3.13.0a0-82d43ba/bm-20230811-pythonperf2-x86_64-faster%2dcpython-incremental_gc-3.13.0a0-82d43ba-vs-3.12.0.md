
# Results vs. 3.12.0

- fork: faster-cpython
- ref: incremental_gc
- machine: linux-x86_64
- commit hash: 82d43ba
- commit date: 2023-08-11
- overall geometric mean: 1.06x slower
- HPT reliability: 98.24%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230811-pythonperf2-x86_64-faster%2dcpython-incremental_gc-3.13.0a0-82d43ba |
|----------------|:------------------------------------------------------------:|:-------------------------------------------------------------------------------:|
| docutils       | 2.89 sec                                                     | 2.78 sec: 1.04x faster                                                          |
| tornado_http   | 122 ms                                                       | 129 ms: 1.06x slower                                                            |
| Geometric mean | (ref)                                                        | 1.01x slower                                                                    |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230811-pythonperf2-x86_64-faster%2dcpython-incremental_gc-3.13.0a0-82d43ba |
|----------------|:------------------------------------------------------------:|:-------------------------------------------------------------------------------:|
| nbody          | 94.1 ms                                                      | 85.8 ms: 1.10x faster                                                           |
| pidigits       | 264 ms                                                       | 260 ms: 1.01x faster                                                            |
| float          | 78.5 ms                                                      | 116 ms: 1.47x slower                                                            |
| Geometric mean | (ref)                                                        | 1.10x slower                                                                    |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230811-pythonperf2-x86_64-faster%2dcpython-incremental_gc-3.13.0a0-82d43ba |
|----------------|:------------------------------------------------------------:|:-------------------------------------------------------------------------------:|
| regex_v8       | 25.0 ms                                                      | 23.8 ms: 1.05x faster                                                           |
| regex_effbot   | 3.47 ms                                                      | 3.37 ms: 1.03x faster                                                           |
| regex_dna      | 241 ms                                                       | 236 ms: 1.02x faster                                                            |
| regex_compile  | 146 ms                                                       | 151 ms: 1.04x slower                                                            |
| Geometric mean | (ref)                                                        | 1.02x faster                                                                    |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230811-pythonperf2-x86_64-faster%2dcpython-incremental_gc-3.13.0a0-82d43ba |
|----------------------|:------------------------------------------------------------:|:-------------------------------------------------------------------------------:|
| pickle_list          | 4.39 us                                                      | 4.22 us: 1.04x faster                                                           |
| pickle               | 10.1 us                                                      | 9.78 us: 1.03x faster                                                           |
| unpickle_list        | 4.77 us                                                      | 4.64 us: 1.03x faster                                                           |
| pickle_pure_python   | 323 us                                                       | 315 us: 1.02x faster                                                            |
| json_dumps           | 10.2 ms                                                      | 10.2 ms: 1.00x faster                                                           |
| pickle_dict          | 31.7 us                                                      | 31.8 us: 1.00x slower                                                           |
| unpickle             | 14.8 us                                                      | 15.0 us: 1.01x slower                                                           |
| xml_etree_process    | 58.3 ms                                                      | 59.7 ms: 1.02x slower                                                           |
| unpickle_pure_python | 207 us                                                       | 218 us: 1.05x slower                                                            |
| json_loads           | 24.3 us                                                      | 26.0 us: 1.07x slower                                                           |
| tomli_loads          | 2.20 sec                                                     | 2.38 sec: 1.08x slower                                                          |
| xml_etree_generate   | 86.1 ms                                                      | 96.4 ms: 1.12x slower                                                           |
| xml_etree_parse      | 146 ms                                                       | 543 ms: 3.71x slower                                                            |
| xml_etree_iterparse  | 103 ms                                                       | 515 ms: 4.99x slower                                                            |
| Geometric mean       | (ref)                                                        | 1.25x slower                                                                    |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230811-pythonperf2-x86_64-faster%2dcpython-incremental_gc-3.13.0a0-82d43ba |
|------------------------|:------------------------------------------------------------:|:-------------------------------------------------------------------------------:|
| python_startup_no_site | 8.70 ms                                                      | 8.75 ms: 1.01x slower                                                           |
| python_startup         | 11.7 ms                                                      | 11.8 ms: 1.01x slower                                                           |
| Geometric mean         | (ref)                                                        | 1.01x slower                                                                    |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230811-pythonperf2-x86_64-faster%2dcpython-incremental_gc-3.13.0a0-82d43ba |
|-----------|:------------------------------------------------------------:|:-------------------------------------------------------------------------------:|
| mako      | 9.94 ms                                                      | 10.3 ms: 1.04x slower                                                           |

All benchmarks:
===============

| Benchmark                | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230811-pythonperf2-x86_64-faster%2dcpython-incremental_gc-3.13.0a0-82d43ba |
|--------------------------|:------------------------------------------------------------:|:-------------------------------------------------------------------------------:|
| async_tree_io            | 1.06 sec                                                     | 726 ms: 1.46x faster                                                            |
| async_tree_none          | 459 ms                                                       | 352 ms: 1.30x faster                                                            |
| async_tree_memoization   | 553 ms                                                       | 434 ms: 1.27x faster                                                            |
| async_tree_cpu_io_mixed  | 706 ms                                                       | 611 ms: 1.16x faster                                                            |
| unpack_sequence          | 53.3 ns                                                      | 47.8 ns: 1.12x faster                                                           |
| crypto_pyaes             | 80.9 ms                                                      | 73.5 ms: 1.10x faster                                                           |
| nbody                    | 94.1 ms                                                      | 85.8 ms: 1.10x faster                                                           |
| raytrace                 | 302 ms                                                       | 280 ms: 1.08x faster                                                            |
| scimark_monte_carlo      | 72.4 ms                                                      | 68.0 ms: 1.06x faster                                                           |
| regex_v8                 | 25.0 ms                                                      | 23.8 ms: 1.05x faster                                                           |
| pickle_list              | 4.39 us                                                      | 4.22 us: 1.04x faster                                                           |
| docutils                 | 2.89 sec                                                     | 2.78 sec: 1.04x faster                                                          |
| asyncio_tcp              | 381 ms                                                       | 369 ms: 1.03x faster                                                            |
| pickle                   | 10.1 us                                                      | 9.78 us: 1.03x faster                                                           |
| regex_effbot             | 3.47 ms                                                      | 3.37 ms: 1.03x faster                                                           |
| unpickle_list            | 4.77 us                                                      | 4.64 us: 1.03x faster                                                           |
| pprint_safe_repr         | 823 ms                                                       | 803 ms: 1.03x faster                                                            |
| pickle_pure_python       | 323 us                                                       | 315 us: 1.02x faster                                                            |
| regex_dna                | 241 ms                                                       | 236 ms: 1.02x faster                                                            |
| pprint_pformat           | 1.67 sec                                                     | 1.64 sec: 1.02x faster                                                          |
| chaos                    | 62.9 ms                                                      | 61.7 ms: 1.02x faster                                                           |
| pidigits                 | 264 ms                                                       | 260 ms: 1.01x faster                                                            |
| deepcopy_memo            | 37.4 us                                                      | 37.0 us: 1.01x faster                                                           |
| pathlib                  | 19.8 ms                                                      | 19.6 ms: 1.01x faster                                                           |
| scimark_sparse_mat_mult  | 4.42 ms                                                      | 4.38 ms: 1.01x faster                                                           |
| meteor_contest           | 128 ms                                                       | 127 ms: 1.01x faster                                                            |
| json_dumps               | 10.2 ms                                                      | 10.2 ms: 1.00x faster                                                           |
| comprehensions           | 21.9 us                                                      | 22.0 us: 1.00x slower                                                           |
| pickle_dict              | 31.7 us                                                      | 31.8 us: 1.00x slower                                                           |
| python_startup_no_site   | 8.70 ms                                                      | 8.75 ms: 1.01x slower                                                           |
| python_startup           | 11.7 ms                                                      | 11.8 ms: 1.01x slower                                                           |
| scimark_lu               | 101 ms                                                       | 101 ms: 1.01x slower                                                            |
| json                     | 5.14 ms                                                      | 5.19 ms: 1.01x slower                                                           |
| scimark_fft              | 304 ms                                                       | 308 ms: 1.01x slower                                                            |
| deepcopy                 | 376 us                                                       | 380 us: 1.01x slower                                                            |
| unpickle                 | 14.8 us                                                      | 15.0 us: 1.01x slower                                                           |
| logging_format           | 7.37 us                                                      | 7.48 us: 1.01x slower                                                           |
| nqueens                  | 90.1 ms                                                      | 91.4 ms: 1.01x slower                                                           |
| spectral_norm            | 91.6 ms                                                      | 93.2 ms: 1.02x slower                                                           |
| logging_silent           | 95.6 ns                                                      | 97.4 ns: 1.02x slower                                                           |
| sqlglot_normalize        | 117 ms                                                       | 119 ms: 1.02x slower                                                            |
| logging_simple           | 6.73 us                                                      | 6.87 us: 1.02x slower                                                           |
| coroutines               | 23.0 ms                                                      | 23.5 ms: 1.02x slower                                                           |
| xml_etree_process        | 58.3 ms                                                      | 59.7 ms: 1.02x slower                                                           |
| mdp                      | 2.53 sec                                                     | 2.60 sec: 1.03x slower                                                          |
| typing_runtime_protocols | 151 us                                                       | 156 us: 1.03x slower                                                            |
| mako                     | 9.94 ms                                                      | 10.3 ms: 1.04x slower                                                           |
| sqlglot_optimize         | 57.8 ms                                                      | 59.9 ms: 1.04x slower                                                           |
| regex_compile            | 146 ms                                                       | 151 ms: 1.04x slower                                                            |
| async_generators         | 385 ms                                                       | 405 ms: 1.05x slower                                                            |
| dulwich_log              | 65.3 ms                                                      | 68.6 ms: 1.05x slower                                                           |
| unpickle_pure_python     | 207 us                                                       | 218 us: 1.05x slower                                                            |
| tornado_http             | 122 ms                                                       | 129 ms: 1.06x slower                                                            |
| sqlglot_parse            | 1.40 ms                                                      | 1.48 ms: 1.06x slower                                                           |
| coverage                 | 89.6 ms                                                      | 95.1 ms: 1.06x slower                                                           |
| json_loads               | 24.3 us                                                      | 26.0 us: 1.07x slower                                                           |
| tomli_loads              | 2.20 sec                                                     | 2.38 sec: 1.08x slower                                                          |
| sqlglot_transpile        | 1.80 ms                                                      | 1.95 ms: 1.08x slower                                                           |
| hexiom                   | 5.96 ms                                                      | 6.58 ms: 1.10x slower                                                           |
| fannkuch                 | 350 ms                                                       | 387 ms: 1.11x slower                                                            |
| xml_etree_generate       | 86.1 ms                                                      | 96.4 ms: 1.12x slower                                                           |
| pyflate                  | 447 ms                                                       | 511 ms: 1.14x slower                                                            |
| richards_super           | 51.7 ms                                                      | 59.5 ms: 1.15x slower                                                           |
| deltablue                | 3.29 ms                                                      | 3.80 ms: 1.15x slower                                                           |
| go                       | 150 ms                                                       | 175 ms: 1.16x slower                                                            |
| telco                    | 6.96 ms                                                      | 8.16 ms: 1.17x slower                                                           |
| richards                 | 45.0 ms                                                      | 53.0 ms: 1.18x slower                                                           |
| gc_traversal             | 3.54 ms                                                      | 4.37 ms: 1.24x slower                                                           |
| mypy2                    | 368 ms                                                       | 457 ms: 1.24x slower                                                            |
| scimark_sor              | 110 ms                                                       | 142 ms: 1.29x slower                                                            |
| float                    | 78.5 ms                                                      | 116 ms: 1.47x slower                                                            |
| dask                     | 397 ms                                                       | 593 ms: 1.49x slower                                                            |
| xml_etree_parse          | 146 ms                                                       | 543 ms: 3.71x slower                                                            |
| xml_etree_iterparse      | 103 ms                                                       | 515 ms: 4.99x slower                                                            |
| Geometric mean           | (ref)                                                        | 1.06x slower                                                                    |

Benchmark hidden because not significant (8): bench_mp_pool, bench_thread_pool, create_gc_cycles, sqlite_synth, pycparser, deepcopy_reduce, asyncio_tcp_ssl, generators
Ignored benchmarks (1) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: 2to3


# HPT report

- Reliability score: 98.24% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
