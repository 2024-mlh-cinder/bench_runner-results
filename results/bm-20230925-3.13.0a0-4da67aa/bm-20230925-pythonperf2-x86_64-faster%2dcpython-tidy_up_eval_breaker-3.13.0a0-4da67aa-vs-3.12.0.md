
# Results vs. 3.12.0

- fork: faster-cpython
- ref: tidy_up_eval_breaker
- machine: linux-x86_64
- commit hash: 4da67aa
- commit date: 2023-09-25
- overall geometric mean: 1.02x slower
- HPT reliability: 98.24%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230925-pythonperf2-x86_64-faster%2dcpython-tidy_up_eval_breaker-3.13.0a0-4da67aa |
|----------------|:------------------------------------------------------------:|:-------------------------------------------------------------------------------------:|
| docutils       | 2.89 sec                                                     | 2.87 sec: 1.01x faster                                                                |
| Geometric mean | (ref)                                                        | 1.01x faster                                                                          |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230925-pythonperf2-x86_64-faster%2dcpython-tidy_up_eval_breaker-3.13.0a0-4da67aa |
|----------------|:------------------------------------------------------------:|:-------------------------------------------------------------------------------------:|
| nbody          | 94.1 ms                                                      | 86.7 ms: 1.09x faster                                                                 |
| pidigits       | 264 ms                                                       | 265 ms: 1.00x slower                                                                  |
| float          | 78.5 ms                                                      | 81.2 ms: 1.03x slower                                                                 |
| Geometric mean | (ref)                                                        | 1.01x faster                                                                          |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230925-pythonperf2-x86_64-faster%2dcpython-tidy_up_eval_breaker-3.13.0a0-4da67aa |
|----------------|:------------------------------------------------------------:|:-------------------------------------------------------------------------------------:|
| regex_compile  | 146 ms                                                       | 149 ms: 1.02x slower                                                                  |
| regex_dna      | 241 ms                                                       | 250 ms: 1.04x slower                                                                  |
| regex_v8       | 25.0 ms                                                      | 26.0 ms: 1.04x slower                                                                 |
| regex_effbot   | 3.47 ms                                                      | 3.62 ms: 1.04x slower                                                                 |
| Geometric mean | (ref)                                                        | 1.04x slower                                                                          |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230925-pythonperf2-x86_64-faster%2dcpython-tidy_up_eval_breaker-3.13.0a0-4da67aa |
|----------------------|:------------------------------------------------------------:|:-------------------------------------------------------------------------------------:|
| pickle_pure_python   | 323 us                                                       | 318 us: 1.01x faster                                                                  |
| pickle_list          | 4.39 us                                                      | 4.36 us: 1.01x faster                                                                 |
| pickle               | 10.1 us                                                      | 10.0 us: 1.01x faster                                                                 |
| pickle_dict          | 31.7 us                                                      | 32.0 us: 1.01x slower                                                                 |
| unpickle             | 14.8 us                                                      | 15.0 us: 1.02x slower                                                                 |
| unpickle_list        | 4.77 us                                                      | 4.84 us: 1.02x slower                                                                 |
| json_loads           | 24.3 us                                                      | 24.7 us: 1.02x slower                                                                 |
| json_dumps           | 10.2 ms                                                      | 10.4 ms: 1.02x slower                                                                 |
| xml_etree_iterparse  | 103 ms                                                       | 107 ms: 1.04x slower                                                                  |
| xml_etree_parse      | 146 ms                                                       | 153 ms: 1.05x slower                                                                  |
| unpickle_pure_python | 207 us                                                       | 238 us: 1.15x slower                                                                  |
| Geometric mean       | (ref)                                                        | 1.02x slower                                                                          |

Benchmark hidden because not significant (3): xml_etree_generate, tomli_loads, xml_etree_process

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230925-pythonperf2-x86_64-faster%2dcpython-tidy_up_eval_breaker-3.13.0a0-4da67aa |
|------------------------|:------------------------------------------------------------:|:-------------------------------------------------------------------------------------:|
| python_startup_no_site | 8.70 ms                                                      | 8.68 ms: 1.00x faster                                                                 |
| python_startup         | 11.7 ms                                                      | 12.7 ms: 1.08x slower                                                                 |
| Geometric mean         | (ref)                                                        | 1.04x slower                                                                          |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230925-pythonperf2-x86_64-faster%2dcpython-tidy_up_eval_breaker-3.13.0a0-4da67aa |
|-----------|:------------------------------------------------------------:|:-------------------------------------------------------------------------------------:|
| mako      | 9.94 ms                                                      | 10.4 ms: 1.04x slower                                                                 |

All benchmarks:
===============

| Benchmark                | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230925-pythonperf2-x86_64-faster%2dcpython-tidy_up_eval_breaker-3.13.0a0-4da67aa |
|--------------------------|:------------------------------------------------------------:|:-------------------------------------------------------------------------------------:|
| unpack_sequence          | 53.3 ns                                                      | 44.5 ns: 1.20x faster                                                                 |
| coverage                 | 89.6 ms                                                      | 78.4 ms: 1.14x faster                                                                 |
| bench_mp_pool            | 5.34 ms                                                      | 4.83 ms: 1.10x faster                                                                 |
| crypto_pyaes             | 80.9 ms                                                      | 73.4 ms: 1.10x faster                                                                 |
| scimark_sparse_mat_mult  | 4.42 ms                                                      | 4.06 ms: 1.09x faster                                                                 |
| nbody                    | 94.1 ms                                                      | 86.7 ms: 1.09x faster                                                                 |
| scimark_monte_carlo      | 72.4 ms                                                      | 66.9 ms: 1.08x faster                                                                 |
| raytrace                 | 302 ms                                                       | 281 ms: 1.08x faster                                                                  |
| async_tree_none          | 459 ms                                                       | 436 ms: 1.05x faster                                                                  |
| generators               | 36.7 ms                                                      | 35.3 ms: 1.04x faster                                                                 |
| asyncio_tcp              | 381 ms                                                       | 368 ms: 1.04x faster                                                                  |
| nqueens                  | 90.1 ms                                                      | 88.0 ms: 1.02x faster                                                                 |
| pathlib                  | 19.8 ms                                                      | 19.3 ms: 1.02x faster                                                                 |
| sqlite_synth             | 2.70 us                                                      | 2.66 us: 1.01x faster                                                                 |
| pickle_pure_python       | 323 us                                                       | 318 us: 1.01x faster                                                                  |
| deepcopy_memo            | 37.4 us                                                      | 37.0 us: 1.01x faster                                                                 |
| deepcopy_reduce          | 3.46 us                                                      | 3.42 us: 1.01x faster                                                                 |
| sqlglot_parse            | 1.40 ms                                                      | 1.39 ms: 1.01x faster                                                                 |
| async_tree_memoization   | 553 ms                                                       | 549 ms: 1.01x faster                                                                  |
| json                     | 5.14 ms                                                      | 5.10 ms: 1.01x faster                                                                 |
| typing_runtime_protocols | 151 us                                                       | 150 us: 1.01x faster                                                                  |
| spectral_norm            | 91.6 ms                                                      | 90.9 ms: 1.01x faster                                                                 |
| docutils                 | 2.89 sec                                                     | 2.87 sec: 1.01x faster                                                                |
| mdp                      | 2.53 sec                                                     | 2.52 sec: 1.01x faster                                                                |
| sqlglot_normalize        | 117 ms                                                       | 116 ms: 1.01x faster                                                                  |
| pickle_list              | 4.39 us                                                      | 4.36 us: 1.01x faster                                                                 |
| pickle                   | 10.1 us                                                      | 10.0 us: 1.01x faster                                                                 |
| python_startup_no_site   | 8.70 ms                                                      | 8.68 ms: 1.00x faster                                                                 |
| asyncio_tcp_ssl          | 1.58 sec                                                     | 1.58 sec: 1.00x slower                                                                |
| pprint_pformat           | 1.67 sec                                                     | 1.68 sec: 1.00x slower                                                                |
| pidigits                 | 264 ms                                                       | 265 ms: 1.00x slower                                                                  |
| deepcopy                 | 376 us                                                       | 379 us: 1.01x slower                                                                  |
| mypy2                    | 368 ms                                                       | 372 ms: 1.01x slower                                                                  |
| pickle_dict              | 31.7 us                                                      | 32.0 us: 1.01x slower                                                                 |
| comprehensions           | 21.9 us                                                      | 22.1 us: 1.01x slower                                                                 |
| gc_traversal             | 3.54 ms                                                      | 3.58 ms: 1.01x slower                                                                 |
| unpickle                 | 14.8 us                                                      | 15.0 us: 1.02x slower                                                                 |
| unpickle_list            | 4.77 us                                                      | 4.84 us: 1.02x slower                                                                 |
| sqlglot_optimize         | 57.8 ms                                                      | 58.7 ms: 1.02x slower                                                                 |
| scimark_fft              | 304 ms                                                       | 310 ms: 1.02x slower                                                                  |
| json_loads               | 24.3 us                                                      | 24.7 us: 1.02x slower                                                                 |
| json_dumps               | 10.2 ms                                                      | 10.4 ms: 1.02x slower                                                                 |
| logging_silent           | 95.6 ns                                                      | 97.6 ns: 1.02x slower                                                                 |
| regex_compile            | 146 ms                                                       | 149 ms: 1.02x slower                                                                  |
| async_generators         | 385 ms                                                       | 395 ms: 1.02x slower                                                                  |
| meteor_contest           | 128 ms                                                       | 131 ms: 1.02x slower                                                                  |
| async_tree_io            | 1.06 sec                                                     | 1.09 sec: 1.03x slower                                                                |
| float                    | 78.5 ms                                                      | 81.2 ms: 1.03x slower                                                                 |
| regex_dna                | 241 ms                                                       | 250 ms: 1.04x slower                                                                  |
| xml_etree_iterparse      | 103 ms                                                       | 107 ms: 1.04x slower                                                                  |
| regex_v8                 | 25.0 ms                                                      | 26.0 ms: 1.04x slower                                                                 |
| regex_effbot             | 3.47 ms                                                      | 3.62 ms: 1.04x slower                                                                 |
| mako                     | 9.94 ms                                                      | 10.4 ms: 1.04x slower                                                                 |
| xml_etree_parse          | 146 ms                                                       | 153 ms: 1.05x slower                                                                  |
| pycparser                | 1.27 sec                                                     | 1.34 sec: 1.05x slower                                                                |
| dulwich_log              | 65.3 ms                                                      | 69.6 ms: 1.06x slower                                                                 |
| hexiom                   | 5.96 ms                                                      | 6.39 ms: 1.07x slower                                                                 |
| python_startup           | 11.7 ms                                                      | 12.7 ms: 1.08x slower                                                                 |
| deltablue                | 3.29 ms                                                      | 3.64 ms: 1.11x slower                                                                 |
| fannkuch                 | 350 ms                                                       | 393 ms: 1.12x slower                                                                  |
| pyflate                  | 447 ms                                                       | 508 ms: 1.14x slower                                                                  |
| go                       | 150 ms                                                       | 171 ms: 1.14x slower                                                                  |
| telco                    | 6.96 ms                                                      | 7.99 ms: 1.15x slower                                                                 |
| unpickle_pure_python     | 207 us                                                       | 238 us: 1.15x slower                                                                  |
| richards_super           | 51.7 ms                                                      | 60.9 ms: 1.18x slower                                                                 |
| richards                 | 45.0 ms                                                      | 54.8 ms: 1.22x slower                                                                 |
| scimark_sor              | 110 ms                                                       | 148 ms: 1.34x slower                                                                  |
| dask                     | 397 ms                                                       | 587 ms: 1.48x slower                                                                  |
| Geometric mean           | (ref)                                                        | 1.02x slower                                                                          |

Benchmark hidden because not significant (14): bench_thread_pool, tornado_http, async_tree_cpu_io_mixed, sqlglot_transpile, coroutines, pprint_safe_repr, logging_simple, logging_format, xml_etree_generate, chaos, scimark_lu, create_gc_cycles, tomli_loads, xml_etree_process
Ignored benchmarks (1) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: 2to3


# HPT report

- Reliability score: 98.24% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
