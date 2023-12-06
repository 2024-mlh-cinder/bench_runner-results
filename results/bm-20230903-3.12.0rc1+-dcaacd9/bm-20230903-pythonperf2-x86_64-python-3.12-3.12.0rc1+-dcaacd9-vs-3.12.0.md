
# Results vs. 3.12.0

- fork: python
- ref: 3.12
- machine: linux-x86_64
- commit hash: dcaacd9
- commit date: 2023-09-03
- overall geometric mean: 1.00x faster
- HPT reliability: 99.75%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230903-pythonperf2-x86_64-python-3.12-3.12.0rc1+-dcaacd9 |
|----------------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| 2to3           | 287 ms                                                       | 285 ms: 1.01x faster                                          |
| docutils       | 2.89 sec                                                     | 2.90 sec: 1.00x slower                                        |
| tornado_http   | 122 ms                                                       | 120 ms: 1.01x faster                                          |
| Geometric mean | (ref)                                                        | 1.01x faster                                                  |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230903-pythonperf2-x86_64-python-3.12-3.12.0rc1+-dcaacd9 |
|----------------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| float          | 78.5 ms                                                      | 79.1 ms: 1.01x slower                                         |
| Geometric mean | (ref)                                                        | 1.01x slower                                                  |

Benchmark hidden because not significant (2): pidigits, nbody

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230903-pythonperf2-x86_64-python-3.12-3.12.0rc1+-dcaacd9 |
|----------------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| regex_v8       | 25.0 ms                                                      | 24.6 ms: 1.02x faster                                         |
| regex_effbot   | 3.47 ms                                                      | 3.45 ms: 1.01x faster                                         |
| regex_dna      | 241 ms                                                       | 245 ms: 1.02x slower                                          |
| Geometric mean | (ref)                                                        | 1.00x faster                                                  |

Benchmark hidden because not significant (1): regex_compile

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230903-pythonperf2-x86_64-python-3.12-3.12.0rc1+-dcaacd9 |
|----------------------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| pickle_list          | 4.39 us                                                      | 4.21 us: 1.04x faster                                         |
| pickle               | 10.1 us                                                      | 9.83 us: 1.03x faster                                         |
| tomli_loads          | 2.20 sec                                                     | 2.16 sec: 1.02x faster                                        |
| unpickle             | 14.8 us                                                      | 14.6 us: 1.01x faster                                         |
| json_dumps           | 10.2 ms                                                      | 10.2 ms: 1.01x faster                                         |
| pickle_dict          | 31.7 us                                                      | 31.5 us: 1.00x faster                                         |
| unpickle_pure_python | 207 us                                                       | 206 us: 1.00x faster                                          |
| unpickle_list        | 4.77 us                                                      | 4.79 us: 1.01x slower                                         |
| json_loads           | 24.3 us                                                      | 24.4 us: 1.01x slower                                         |
| xml_etree_generate   | 86.1 ms                                                      | 87.4 ms: 1.01x slower                                         |
| xml_etree_iterparse  | 103 ms                                                       | 105 ms: 1.02x slower                                          |
| xml_etree_process    | 58.3 ms                                                      | 59.5 ms: 1.02x slower                                         |
| xml_etree_parse      | 146 ms                                                       | 151 ms: 1.03x slower                                          |
| Geometric mean       | (ref)                                                        | 1.00x faster                                                  |

Benchmark hidden because not significant (1): pickle_pure_python

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230903-pythonperf2-x86_64-python-3.12-3.12.0rc1+-dcaacd9 |
|------------------------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| python_startup_no_site | 8.70 ms                                                      | 8.66 ms: 1.00x faster                                         |
| python_startup         | 11.7 ms                                                      | 11.7 ms: 1.00x faster                                         |
| Geometric mean         | (ref)                                                        | 1.00x faster                                                  |

Benchmarks with tag 'template':
===============================

Benchmark hidden because not significant (1): mako

All benchmarks:
===============

| Benchmark               | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230903-pythonperf2-x86_64-python-3.12-3.12.0rc1+-dcaacd9 |
|-------------------------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| bench_mp_pool           | 5.34 ms                                                      | 4.69 ms: 1.14x faster                                         |
| unpack_sequence         | 53.3 ns                                                      | 49.1 ns: 1.09x faster                                         |
| pickle_list             | 4.39 us                                                      | 4.21 us: 1.04x faster                                         |
| logging_silent          | 95.6 ns                                                      | 92.1 ns: 1.04x faster                                         |
| scimark_lu              | 101 ms                                                       | 97.0 ms: 1.04x faster                                         |
| create_gc_cycles        | 1.67 ms                                                      | 1.62 ms: 1.04x faster                                         |
| pathlib                 | 19.8 ms                                                      | 19.2 ms: 1.03x faster                                         |
| scimark_sparse_mat_mult | 4.42 ms                                                      | 4.29 ms: 1.03x faster                                         |
| pickle                  | 10.1 us                                                      | 9.83 us: 1.03x faster                                         |
| go                      | 150 ms                                                       | 146 ms: 1.03x faster                                          |
| scimark_monte_carlo     | 72.4 ms                                                      | 70.5 ms: 1.03x faster                                         |
| richards                | 45.0 ms                                                      | 43.9 ms: 1.03x faster                                         |
| scimark_sor             | 110 ms                                                       | 107 ms: 1.03x faster                                          |
| pprint_safe_repr        | 823 ms                                                       | 805 ms: 1.02x faster                                          |
| hexiom                  | 5.96 ms                                                      | 5.83 ms: 1.02x faster                                         |
| scimark_fft             | 304 ms                                                       | 298 ms: 1.02x faster                                          |
| pprint_pformat          | 1.67 sec                                                     | 1.64 sec: 1.02x faster                                        |
| raytrace                | 302 ms                                                       | 297 ms: 1.02x faster                                          |
| tomli_loads             | 2.20 sec                                                     | 2.16 sec: 1.02x faster                                        |
| deltablue               | 3.29 ms                                                      | 3.23 ms: 1.02x faster                                         |
| richards_super          | 51.7 ms                                                      | 50.8 ms: 1.02x faster                                         |
| regex_v8                | 25.0 ms                                                      | 24.6 ms: 1.02x faster                                         |
| meteor_contest          | 128 ms                                                       | 126 ms: 1.01x faster                                          |
| coverage                | 89.6 ms                                                      | 88.3 ms: 1.01x faster                                         |
| spectral_norm           | 91.6 ms                                                      | 90.4 ms: 1.01x faster                                         |
| tornado_http            | 122 ms                                                       | 120 ms: 1.01x faster                                          |
| json                    | 5.14 ms                                                      | 5.08 ms: 1.01x faster                                         |
| chaos                   | 62.9 ms                                                      | 62.2 ms: 1.01x faster                                         |
| unpickle                | 14.8 us                                                      | 14.6 us: 1.01x faster                                         |
| async_generators        | 385 ms                                                       | 382 ms: 1.01x faster                                          |
| pyflate                 | 447 ms                                                       | 443 ms: 1.01x faster                                          |
| fannkuch                | 350 ms                                                       | 347 ms: 1.01x faster                                          |
| nqueens                 | 90.1 ms                                                      | 89.3 ms: 1.01x faster                                         |
| async_tree_memoization  | 553 ms                                                       | 549 ms: 1.01x faster                                          |
| json_dumps              | 10.2 ms                                                      | 10.2 ms: 1.01x faster                                         |
| deepcopy_memo           | 37.4 us                                                      | 37.1 us: 1.01x faster                                         |
| async_tree_io           | 1.06 sec                                                     | 1.05 sec: 1.01x faster                                        |
| mypy2                   | 368 ms                                                       | 366 ms: 1.01x faster                                          |
| 2to3                    | 287 ms                                                       | 285 ms: 1.01x faster                                          |
| async_tree_none         | 459 ms                                                       | 456 ms: 1.01x faster                                          |
| regex_effbot            | 3.47 ms                                                      | 3.45 ms: 1.01x faster                                         |
| pickle_dict             | 31.7 us                                                      | 31.5 us: 1.00x faster                                         |
| python_startup_no_site  | 8.70 ms                                                      | 8.66 ms: 1.00x faster                                         |
| unpickle_pure_python    | 207 us                                                       | 206 us: 1.00x faster                                          |
| python_startup          | 11.7 ms                                                      | 11.7 ms: 1.00x faster                                         |
| crypto_pyaes            | 80.9 ms                                                      | 81.1 ms: 1.00x slower                                         |
| docutils                | 2.89 sec                                                     | 2.90 sec: 1.00x slower                                        |
| unpickle_list           | 4.77 us                                                      | 4.79 us: 1.01x slower                                         |
| json_loads              | 24.3 us                                                      | 24.4 us: 1.01x slower                                         |
| float                   | 78.5 ms                                                      | 79.1 ms: 1.01x slower                                         |
| generators              | 36.7 ms                                                      | 37.0 ms: 1.01x slower                                         |
| telco                   | 6.96 ms                                                      | 7.05 ms: 1.01x slower                                         |
| asyncio_tcp             | 381 ms                                                       | 387 ms: 1.01x slower                                          |
| xml_etree_generate      | 86.1 ms                                                      | 87.4 ms: 1.01x slower                                         |
| regex_dna               | 241 ms                                                       | 245 ms: 1.02x slower                                          |
| xml_etree_iterparse     | 103 ms                                                       | 105 ms: 1.02x slower                                          |
| xml_etree_process       | 58.3 ms                                                      | 59.5 ms: 1.02x slower                                         |
| deepcopy                | 376 us                                                       | 385 us: 1.03x slower                                          |
| xml_etree_parse         | 146 ms                                                       | 151 ms: 1.03x slower                                          |
| gc_traversal            | 3.54 ms                                                      | 3.78 ms: 1.07x slower                                         |
| dask                    | 397 ms                                                       | 565 ms: 1.42x slower                                          |
| Geometric mean          | (ref)                                                        | 1.00x faster                                                  |

Benchmark hidden because not significant (22): bench_thread_pool, async_tree_cpu_io_mixed, typing_runtime_protocols, sqlglot_parse, sqlglot_transpile, logging_simple, comprehensions, mdp, mako, regex_compile, dulwich_log, coroutines, pidigits, asyncio_tcp_ssl, sqlglot_normalize, sqlite_synth, logging_format, deepcopy_reduce, sqlglot_optimize, pycparser, pickle_pure_python, nbody


# HPT report

- Reliability score: 99.75% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
