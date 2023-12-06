
# Results vs. base

- fork: faster-cpython
- ref: tidy_up_eval_breaker
- machine: linux-x86_64
- commit hash: 2b8766e
- commit date: 2023-09-13
- overall geometric mean: 1.01x faster
- HPT reliability: 99.47%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

Benchmark hidden because not significant (2): docutils, tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20230912-linux-x86_64-python-8b55adfa8ff05477b4be-3.13.0a0-8b55adf | bm-20230913-linux-x86_64-faster%2dcpython-tidy_up_eval_breaker-3.13.0a0-2b8766e |
|----------------|:---------------------------------------------------------------------:|:-------------------------------------------------------------------------------:|
| nbody          | 89.8 ms                                                               | 88.7 ms: 1.01x faster                                                           |
| pidigits       | 187 ms                                                                | 187 ms: 1.00x faster                                                            |
| Geometric mean | (ref)                                                                 | 1.01x faster                                                                    |

Benchmark hidden because not significant (1): float

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20230912-linux-x86_64-python-8b55adfa8ff05477b4be-3.13.0a0-8b55adf | bm-20230913-linux-x86_64-faster%2dcpython-tidy_up_eval_breaker-3.13.0a0-2b8766e |
|----------------|:---------------------------------------------------------------------:|:-------------------------------------------------------------------------------:|
| regex_v8       | 24.6 ms                                                               | 23.6 ms: 1.05x faster                                                           |
| regex_effbot   | 3.58 ms                                                               | 3.43 ms: 1.04x faster                                                           |
| regex_dna      | 214 ms                                                                | 209 ms: 1.03x faster                                                            |
| Geometric mean | (ref)                                                                 | 1.03x faster                                                                    |

Benchmark hidden because not significant (1): regex_compile

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20230912-linux-x86_64-python-8b55adfa8ff05477b4be-3.13.0a0-8b55adf | bm-20230913-linux-x86_64-faster%2dcpython-tidy_up_eval_breaker-3.13.0a0-2b8766e |
|----------------------|:---------------------------------------------------------------------:|:-------------------------------------------------------------------------------:|
| unpickle             | 14.5 us                                                               | 14.0 us: 1.04x faster                                                           |
| pickle_dict          | 32.5 us                                                               | 31.4 us: 1.04x faster                                                           |
| unpickle_list        | 4.82 us                                                               | 4.74 us: 1.02x faster                                                           |
| pickle               | 10.8 us                                                               | 10.7 us: 1.02x faster                                                           |
| unpickle_pure_python | 221 us                                                                | 218 us: 1.01x faster                                                            |
| xml_etree_process    | 58.0 ms                                                               | 57.4 ms: 1.01x faster                                                           |
| json_dumps           | 9.86 ms                                                               | 9.76 ms: 1.01x faster                                                           |
| xml_etree_generate   | 84.6 ms                                                               | 83.9 ms: 1.01x faster                                                           |
| xml_etree_parse      | 152 ms                                                                | 151 ms: 1.01x faster                                                            |
| Geometric mean       | (ref)                                                                 | 1.01x faster                                                                    |

Benchmark hidden because not significant (5): xml_etree_iterparse, json_loads, pickle_list, pickle_pure_python, tomli_loads

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20230912-linux-x86_64-python-8b55adfa8ff05477b4be-3.13.0a0-8b55adf | bm-20230913-linux-x86_64-faster%2dcpython-tidy_up_eval_breaker-3.13.0a0-2b8766e |
|------------------------|:---------------------------------------------------------------------:|:-------------------------------------------------------------------------------:|
| python_startup         | 10.1 ms                                                               | 10.1 ms: 1.00x faster                                                           |
| python_startup_no_site | 6.85 ms                                                               | 6.84 ms: 1.00x faster                                                           |
| Geometric mean         | (ref)                                                                 | 1.00x faster                                                                    |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20230912-linux-x86_64-python-8b55adfa8ff05477b4be-3.13.0a0-8b55adf | bm-20230913-linux-x86_64-faster%2dcpython-tidy_up_eval_breaker-3.13.0a0-2b8766e |
|-----------|:---------------------------------------------------------------------:|:-------------------------------------------------------------------------------:|
| mako      | 10.9 ms                                                               | 10.8 ms: 1.01x faster                                                           |

All benchmarks:
===============

| Benchmark                | bm-20230912-linux-x86_64-python-8b55adfa8ff05477b4be-3.13.0a0-8b55adf | bm-20230913-linux-x86_64-faster%2dcpython-tidy_up_eval_breaker-3.13.0a0-2b8766e |
|--------------------------|:---------------------------------------------------------------------:|:-------------------------------------------------------------------------------:|
| unpack_sequence          | 45.0 ns                                                               | 42.1 ns: 1.07x faster                                                           |
| regex_v8                 | 24.6 ms                                                               | 23.6 ms: 1.05x faster                                                           |
| regex_effbot             | 3.58 ms                                                               | 3.43 ms: 1.04x faster                                                           |
| unpickle                 | 14.5 us                                                               | 14.0 us: 1.04x faster                                                           |
| gc_traversal             | 4.00 ms                                                               | 3.86 ms: 1.04x faster                                                           |
| pickle_dict              | 32.5 us                                                               | 31.4 us: 1.04x faster                                                           |
| telco                    | 8.23 ms                                                               | 7.97 ms: 1.03x faster                                                           |
| regex_dna                | 214 ms                                                                | 209 ms: 1.03x faster                                                            |
| pycparser                | 1.19 sec                                                              | 1.16 sec: 1.02x faster                                                          |
| sqlite_synth             | 2.77 us                                                               | 2.71 us: 1.02x faster                                                           |
| logging_format           | 6.63 us                                                               | 6.49 us: 1.02x faster                                                           |
| scimark_sparse_mat_mult  | 4.79 ms                                                               | 4.69 ms: 1.02x faster                                                           |
| deltablue                | 3.32 ms                                                               | 3.27 ms: 1.02x faster                                                           |
| unpickle_list            | 4.82 us                                                               | 4.74 us: 1.02x faster                                                           |
| pickle                   | 10.8 us                                                               | 10.7 us: 1.02x faster                                                           |
| scimark_sor              | 123 ms                                                                | 121 ms: 1.02x faster                                                            |
| coroutines               | 22.2 ms                                                               | 21.9 ms: 1.01x faster                                                           |
| typing_runtime_protocols | 146 us                                                                | 144 us: 1.01x faster                                                            |
| unpickle_pure_python     | 221 us                                                                | 218 us: 1.01x faster                                                            |
| nbody                    | 89.8 ms                                                               | 88.7 ms: 1.01x faster                                                           |
| fannkuch                 | 395 ms                                                                | 390 ms: 1.01x faster                                                            |
| json                     | 4.78 ms                                                               | 4.73 ms: 1.01x faster                                                           |
| xml_etree_process        | 58.0 ms                                                               | 57.4 ms: 1.01x faster                                                           |
| json_dumps               | 9.86 ms                                                               | 9.76 ms: 1.01x faster                                                           |
| logging_simple           | 5.98 us                                                               | 5.92 us: 1.01x faster                                                           |
| mako                     | 10.9 ms                                                               | 10.8 ms: 1.01x faster                                                           |
| xml_etree_generate       | 84.6 ms                                                               | 83.9 ms: 1.01x faster                                                           |
| coverage                 | 85.7 ms                                                               | 85.0 ms: 1.01x faster                                                           |
| async_tree_io            | 1.19 sec                                                              | 1.18 sec: 1.01x faster                                                          |
| crypto_pyaes             | 69.9 ms                                                               | 69.4 ms: 1.01x faster                                                           |
| asyncio_tcp              | 491 ms                                                                | 488 ms: 1.01x faster                                                            |
| pyflate                  | 459 ms                                                                | 457 ms: 1.01x faster                                                            |
| xml_etree_parse          | 152 ms                                                                | 151 ms: 1.01x faster                                                            |
| sqlglot_optimize         | 52.6 ms                                                               | 52.4 ms: 1.00x faster                                                           |
| meteor_contest           | 106 ms                                                                | 105 ms: 1.00x faster                                                            |
| python_startup           | 10.1 ms                                                               | 10.1 ms: 1.00x faster                                                           |
| asyncio_tcp_ssl          | 1.79 sec                                                              | 1.79 sec: 1.00x faster                                                          |
| mypy2                    | 339 ms                                                                | 338 ms: 1.00x faster                                                            |
| python_startup_no_site   | 6.85 ms                                                               | 6.84 ms: 1.00x faster                                                           |
| pidigits                 | 187 ms                                                                | 187 ms: 1.00x faster                                                            |
| hexiom                   | 6.03 ms                                                               | 6.05 ms: 1.00x slower                                                           |
| pprint_safe_repr         | 721 ms                                                                | 724 ms: 1.00x slower                                                            |
| raytrace                 | 270 ms                                                                | 272 ms: 1.00x slower                                                            |
| create_gc_cycles         | 1.53 ms                                                               | 1.54 ms: 1.01x slower                                                           |
| logging_silent           | 102 ns                                                                | 102 ns: 1.01x slower                                                            |
| sqlglot_parse            | 1.27 ms                                                               | 1.27 ms: 1.01x slower                                                           |
| pprint_pformat           | 1.46 sec                                                              | 1.47 sec: 1.01x slower                                                          |
| deepcopy                 | 345 us                                                                | 347 us: 1.01x slower                                                            |
| sqlglot_transpile        | 1.58 ms                                                               | 1.59 ms: 1.01x slower                                                           |
| richards_super           | 54.8 ms                                                               | 55.3 ms: 1.01x slower                                                           |
| comprehensions           | 20.3 us                                                               | 20.5 us: 1.01x slower                                                           |
| generators               | 29.1 ms                                                               | 29.3 ms: 1.01x slower                                                           |
| go                       | 140 ms                                                                | 141 ms: 1.01x slower                                                            |
| deepcopy_memo            | 36.8 us                                                               | 37.2 us: 1.01x slower                                                           |
| nqueens                  | 79.5 ms                                                               | 80.4 ms: 1.01x slower                                                           |
| deepcopy_reduce          | 3.10 us                                                               | 3.14 us: 1.01x slower                                                           |
| scimark_fft              | 353 ms                                                                | 361 ms: 1.02x slower                                                            |
| richards                 | 47.6 ms                                                               | 48.6 ms: 1.02x slower                                                           |
| scimark_lu               | 109 ms                                                                | 111 ms: 1.02x slower                                                            |
| mdp                      | 2.53 sec                                                              | 2.67 sec: 1.05x slower                                                          |
| Geometric mean           | (ref)                                                                 | 1.01x faster                                                                    |

Benchmark hidden because not significant (22): async_tree_memoization, async_tree_none, async_tree_cpu_io_mixed, xml_etree_iterparse, float, tornado_http, chaos, async_generators, scimark_monte_carlo, dask, docutils, json_loads, bench_thread_pool, dulwich_log, sqlglot_normalize, pathlib, bench_mp_pool, pickle_list, pickle_pure_python, tomli_loads, regex_compile, spectral_norm


# HPT report

- Reliability score: 99.47% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
