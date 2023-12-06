
# Results vs. 3.12.0

- fork: python
- ref: v3.12.0rc1
- machine: linux-x86_64
- commit hash: 63bcd91
- commit date: 2023-08-05
- overall geometric mean: 1.00x faster
- HPT reliability: 96.53%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

Benchmark hidden because not significant (3): 2to3, docutils, tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230805-pythonperf2-x86_64-python-v3.12.0rc1-3.12.0rc1-63bcd91 |
|----------------|:------------------------------------------------------------:|:------------------------------------------------------------------:|
| nbody          | 94.1 ms                                                      | 86.7 ms: 1.09x faster                                              |
| pidigits       | 264 ms                                                       | 260 ms: 1.02x faster                                               |
| float          | 78.5 ms                                                      | 77.8 ms: 1.01x faster                                              |
| Geometric mean | (ref)                                                        | 1.04x faster                                                       |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230805-pythonperf2-x86_64-python-v3.12.0rc1-3.12.0rc1-63bcd91 |
|----------------|:------------------------------------------------------------:|:------------------------------------------------------------------:|
| regex_v8       | 25.0 ms                                                      | 24.0 ms: 1.04x faster                                              |
| regex_effbot   | 3.47 ms                                                      | 3.38 ms: 1.03x faster                                              |
| regex_dna      | 241 ms                                                       | 236 ms: 1.02x faster                                               |
| regex_compile  | 146 ms                                                       | 145 ms: 1.01x faster                                               |
| Geometric mean | (ref)                                                        | 1.02x faster                                                       |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230805-pythonperf2-x86_64-python-v3.12.0rc1-3.12.0rc1-63bcd91 |
|----------------------|:------------------------------------------------------------:|:------------------------------------------------------------------:|
| unpickle             | 14.8 us                                                      | 14.3 us: 1.03x faster                                              |
| xml_etree_generate   | 86.1 ms                                                      | 84.2 ms: 1.02x faster                                              |
| unpickle_list        | 4.77 us                                                      | 4.67 us: 1.02x faster                                              |
| tomli_loads          | 2.20 sec                                                     | 2.18 sec: 1.01x faster                                             |
| pickle_list          | 4.39 us                                                      | 4.35 us: 1.01x faster                                              |
| pickle               | 10.1 us                                                      | 10.0 us: 1.01x faster                                              |
| pickle_dict          | 31.7 us                                                      | 31.6 us: 1.00x faster                                              |
| xml_etree_process    | 58.3 ms                                                      | 58.6 ms: 1.01x slower                                              |
| pickle_pure_python   | 323 us                                                       | 325 us: 1.01x slower                                               |
| json_loads           | 24.3 us                                                      | 24.5 us: 1.01x slower                                              |
| xml_etree_iterparse  | 103 ms                                                       | 104 ms: 1.01x slower                                               |
| unpickle_pure_python | 207 us                                                       | 209 us: 1.01x slower                                               |
| xml_etree_parse      | 146 ms                                                       | 149 ms: 1.02x slower                                               |
| json_dumps           | 10.2 ms                                                      | 10.4 ms: 1.02x slower                                              |
| Geometric mean       | (ref)                                                        | 1.00x faster                                                       |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230805-pythonperf2-x86_64-python-v3.12.0rc1-3.12.0rc1-63bcd91 |
|------------------------|:------------------------------------------------------------:|:------------------------------------------------------------------:|
| python_startup_no_site | 8.70 ms                                                      | 8.50 ms: 1.02x faster                                              |
| python_startup         | 11.7 ms                                                      | 11.5 ms: 1.02x faster                                              |
| Geometric mean         | (ref)                                                        | 1.02x faster                                                       |

Benchmarks with tag 'template':
===============================

Benchmark hidden because not significant (1): mako

All benchmarks:
===============

| Benchmark               | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230805-pythonperf2-x86_64-python-v3.12.0rc1-3.12.0rc1-63bcd91 |
|-------------------------|:------------------------------------------------------------:|:------------------------------------------------------------------:|
| bench_mp_pool           | 5.34 ms                                                      | 4.91 ms: 1.09x faster                                              |
| nbody                   | 94.1 ms                                                      | 86.7 ms: 1.09x faster                                              |
| scimark_sparse_mat_mult | 4.42 ms                                                      | 4.19 ms: 1.06x faster                                              |
| pathlib                 | 19.8 ms                                                      | 19.0 ms: 1.04x faster                                              |
| regex_v8                | 25.0 ms                                                      | 24.0 ms: 1.04x faster                                              |
| logging_silent          | 95.6 ns                                                      | 92.1 ns: 1.04x faster                                              |
| unpickle                | 14.8 us                                                      | 14.3 us: 1.03x faster                                              |
| go                      | 150 ms                                                       | 146 ms: 1.03x faster                                               |
| create_gc_cycles        | 1.67 ms                                                      | 1.62 ms: 1.03x faster                                              |
| coverage                | 89.6 ms                                                      | 87.0 ms: 1.03x faster                                              |
| scimark_lu              | 101 ms                                                       | 98.0 ms: 1.03x faster                                              |
| regex_effbot            | 3.47 ms                                                      | 3.38 ms: 1.03x faster                                              |
| scimark_fft             | 304 ms                                                       | 297 ms: 1.03x faster                                               |
| hexiom                  | 5.96 ms                                                      | 5.81 ms: 1.02x faster                                              |
| pyflate                 | 447 ms                                                       | 437 ms: 1.02x faster                                               |
| python_startup_no_site  | 8.70 ms                                                      | 8.50 ms: 1.02x faster                                              |
| xml_etree_generate      | 86.1 ms                                                      | 84.2 ms: 1.02x faster                                              |
| deltablue               | 3.29 ms                                                      | 3.21 ms: 1.02x faster                                              |
| unpickle_list           | 4.77 us                                                      | 4.67 us: 1.02x faster                                              |
| python_startup          | 11.7 ms                                                      | 11.5 ms: 1.02x faster                                              |
| regex_dna               | 241 ms                                                       | 236 ms: 1.02x faster                                               |
| deepcopy_memo           | 37.4 us                                                      | 36.8 us: 1.02x faster                                              |
| scimark_monte_carlo     | 72.4 ms                                                      | 71.2 ms: 1.02x faster                                              |
| coroutines              | 23.0 ms                                                      | 22.6 ms: 1.02x faster                                              |
| pidigits                | 264 ms                                                       | 260 ms: 1.02x faster                                               |
| pprint_safe_repr        | 823 ms                                                       | 811 ms: 1.02x faster                                               |
| async_generators        | 385 ms                                                       | 380 ms: 1.01x faster                                               |
| scimark_sor             | 110 ms                                                       | 109 ms: 1.01x faster                                               |
| tomli_loads             | 2.20 sec                                                     | 2.18 sec: 1.01x faster                                             |
| pprint_pformat          | 1.67 sec                                                     | 1.66 sec: 1.01x faster                                             |
| pickle_list             | 4.39 us                                                      | 4.35 us: 1.01x faster                                              |
| float                   | 78.5 ms                                                      | 77.8 ms: 1.01x faster                                              |
| sqlglot_parse           | 1.40 ms                                                      | 1.39 ms: 1.01x faster                                              |
| comprehensions          | 21.9 us                                                      | 21.7 us: 1.01x faster                                              |
| generators              | 36.7 ms                                                      | 36.4 ms: 1.01x faster                                              |
| spectral_norm           | 91.6 ms                                                      | 90.9 ms: 1.01x faster                                              |
| pickle                  | 10.1 us                                                      | 10.0 us: 1.01x faster                                              |
| raytrace                | 302 ms                                                       | 300 ms: 1.01x faster                                               |
| regex_compile           | 146 ms                                                       | 145 ms: 1.01x faster                                               |
| pickle_dict             | 31.7 us                                                      | 31.6 us: 1.00x faster                                              |
| asyncio_tcp_ssl         | 1.58 sec                                                     | 1.57 sec: 1.00x faster                                             |
| meteor_contest          | 128 ms                                                       | 128 ms: 1.00x faster                                               |
| async_tree_io           | 1.06 sec                                                     | 1.06 sec: 1.00x slower                                             |
| sqlite_synth            | 2.70 us                                                      | 2.70 us: 1.00x slower                                              |
| sqlglot_normalize       | 117 ms                                                       | 118 ms: 1.00x slower                                               |
| xml_etree_process       | 58.3 ms                                                      | 58.6 ms: 1.01x slower                                              |
| telco                   | 6.96 ms                                                      | 7.01 ms: 1.01x slower                                              |
| sqlglot_optimize        | 57.8 ms                                                      | 58.1 ms: 1.01x slower                                              |
| pickle_pure_python      | 323 us                                                       | 325 us: 1.01x slower                                               |
| asyncio_tcp             | 381 ms                                                       | 384 ms: 1.01x slower                                               |
| json_loads              | 24.3 us                                                      | 24.5 us: 1.01x slower                                              |
| mdp                     | 2.53 sec                                                     | 2.56 sec: 1.01x slower                                             |
| chaos                   | 62.9 ms                                                      | 63.5 ms: 1.01x slower                                              |
| pycparser               | 1.27 sec                                                     | 1.29 sec: 1.01x slower                                             |
| xml_etree_iterparse     | 103 ms                                                       | 104 ms: 1.01x slower                                               |
| unpickle_pure_python    | 207 us                                                       | 209 us: 1.01x slower                                               |
| crypto_pyaes            | 80.9 ms                                                      | 81.8 ms: 1.01x slower                                              |
| dulwich_log             | 65.3 ms                                                      | 66.1 ms: 1.01x slower                                              |
| logging_simple          | 6.73 us                                                      | 6.82 us: 1.01x slower                                              |
| xml_etree_parse         | 146 ms                                                       | 149 ms: 1.02x slower                                               |
| json_dumps              | 10.2 ms                                                      | 10.4 ms: 1.02x slower                                              |
| logging_format          | 7.37 us                                                      | 7.52 us: 1.02x slower                                              |
| deepcopy_reduce         | 3.46 us                                                      | 3.55 us: 1.03x slower                                              |
| fannkuch                | 350 ms                                                       | 361 ms: 1.03x slower                                               |
| deepcopy                | 376 us                                                       | 391 us: 1.04x slower                                               |
| unpack_sequence         | 53.3 ns                                                      | 56.2 ns: 1.06x slower                                              |
| gc_traversal            | 3.54 ms                                                      | 3.77 ms: 1.07x slower                                              |
| dask                    | 397 ms                                                       | 566 ms: 1.43x slower                                               |
| Geometric mean          | (ref)                                                        | 1.00x faster                                                       |

Benchmark hidden because not significant (15): bench_thread_pool, async_tree_cpu_io_mixed, typing_runtime_protocols, mako, sqlglot_transpile, docutils, nqueens, json, 2to3, tornado_http, async_tree_none, mypy2, richards, async_tree_memoization, richards_super


# HPT report

- Reliability score: 96.53% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
