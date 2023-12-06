
# Results vs. base

- fork: faster-cpython
- ref: tidy_up_eval_breaker
- machine: linux-x86_64
- commit hash: 4da67aa
- commit date: 2023-09-25
- overall geometric mean: 1.00x slower
- HPT reliability: 98.68%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20230912-pythonperf2-x86_64-python-8b55adfa8ff05477b4be-3.13.0a0-8b55adf | bm-20230925-pythonperf2-x86_64-faster%2dcpython-tidy_up_eval_breaker-3.13.0a0-4da67aa |
|----------------|:---------------------------------------------------------------------------:|:-------------------------------------------------------------------------------------:|
| docutils       | 2.88 sec                                                                    | 2.87 sec: 1.00x faster                                                                |
| Geometric mean | (ref)                                                                       | 1.00x faster                                                                          |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20230912-pythonperf2-x86_64-python-8b55adfa8ff05477b4be-3.13.0a0-8b55adf | bm-20230925-pythonperf2-x86_64-faster%2dcpython-tidy_up_eval_breaker-3.13.0a0-4da67aa |
|----------------|:---------------------------------------------------------------------------:|:-------------------------------------------------------------------------------------:|
| pidigits       | 263 ms                                                                      | 265 ms: 1.01x slower                                                                  |
| nbody          | 85.9 ms                                                                     | 86.7 ms: 1.01x slower                                                                 |
| Geometric mean | (ref)                                                                       | 1.01x slower                                                                          |

Benchmark hidden because not significant (1): float

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20230912-pythonperf2-x86_64-python-8b55adfa8ff05477b4be-3.13.0a0-8b55adf | bm-20230925-pythonperf2-x86_64-faster%2dcpython-tidy_up_eval_breaker-3.13.0a0-4da67aa |
|----------------|:---------------------------------------------------------------------------:|:-------------------------------------------------------------------------------------:|
| regex_dna      | 240 ms                                                                      | 250 ms: 1.04x slower                                                                  |
| regex_v8       | 24.6 ms                                                                     | 26.0 ms: 1.06x slower                                                                 |
| Geometric mean | (ref)                                                                       | 1.02x slower                                                                          |

Benchmark hidden because not significant (2): regex_effbot, regex_compile

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20230912-pythonperf2-x86_64-python-8b55adfa8ff05477b4be-3.13.0a0-8b55adf | bm-20230925-pythonperf2-x86_64-faster%2dcpython-tidy_up_eval_breaker-3.13.0a0-4da67aa |
|----------------------|:---------------------------------------------------------------------------:|:-------------------------------------------------------------------------------------:|
| pickle_dict          | 32.9 us                                                                     | 32.0 us: 1.03x faster                                                                 |
| json_loads           | 25.2 us                                                                     | 24.7 us: 1.02x faster                                                                 |
| pickle               | 10.1 us                                                                     | 10.0 us: 1.00x faster                                                                 |
| tomli_loads          | 2.19 sec                                                                    | 2.21 sec: 1.00x slower                                                                |
| json_dumps           | 10.4 ms                                                                     | 10.4 ms: 1.01x slower                                                                 |
| pickle_pure_python   | 314 us                                                                      | 318 us: 1.01x slower                                                                  |
| unpickle             | 14.5 us                                                                     | 15.0 us: 1.03x slower                                                                 |
| xml_etree_parse      | 148 ms                                                                      | 153 ms: 1.03x slower                                                                  |
| unpickle_pure_python | 228 us                                                                      | 238 us: 1.05x slower                                                                  |
| unpickle_list        | 4.54 us                                                                     | 4.84 us: 1.07x slower                                                                 |
| Geometric mean       | (ref)                                                                       | 1.01x slower                                                                          |

Benchmark hidden because not significant (4): pickle_list, xml_etree_generate, xml_etree_process, xml_etree_iterparse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20230912-pythonperf2-x86_64-python-8b55adfa8ff05477b4be-3.13.0a0-8b55adf | bm-20230925-pythonperf2-x86_64-faster%2dcpython-tidy_up_eval_breaker-3.13.0a0-4da67aa |
|------------------------|:---------------------------------------------------------------------------:|:-------------------------------------------------------------------------------------:|
| python_startup_no_site | 8.67 ms                                                                     | 8.68 ms: 1.00x slower                                                                 |
| python_startup         | 12.6 ms                                                                     | 12.7 ms: 1.00x slower                                                                 |
| Geometric mean         | (ref)                                                                       | 1.00x slower                                                                          |

Benchmarks with tag 'template':
===============================

Benchmark hidden because not significant (1): mako

All benchmarks:
===============

| Benchmark                | bm-20230912-pythonperf2-x86_64-python-8b55adfa8ff05477b4be-3.13.0a0-8b55adf | bm-20230925-pythonperf2-x86_64-faster%2dcpython-tidy_up_eval_breaker-3.13.0a0-4da67aa |
|--------------------------|:---------------------------------------------------------------------------:|:-------------------------------------------------------------------------------------:|
| unpack_sequence          | 47.9 ns                                                                     | 44.5 ns: 1.08x faster                                                                 |
| coverage                 | 84.0 ms                                                                     | 78.4 ms: 1.07x faster                                                                 |
| scimark_sparse_mat_mult  | 4.19 ms                                                                     | 4.06 ms: 1.03x faster                                                                 |
| pickle_dict              | 32.9 us                                                                     | 32.0 us: 1.03x faster                                                                 |
| scimark_lu               | 103 ms                                                                      | 101 ms: 1.02x faster                                                                  |
| pathlib                  | 19.8 ms                                                                     | 19.3 ms: 1.02x faster                                                                 |
| json_loads               | 25.2 us                                                                     | 24.7 us: 1.02x faster                                                                 |
| typing_runtime_protocols | 153 us                                                                      | 150 us: 1.02x faster                                                                  |
| hexiom                   | 6.48 ms                                                                     | 6.39 ms: 1.01x faster                                                                 |
| sqlglot_normalize        | 118 ms                                                                      | 116 ms: 1.01x faster                                                                  |
| asyncio_tcp              | 372 ms                                                                      | 368 ms: 1.01x faster                                                                  |
| deepcopy                 | 382 us                                                                      | 379 us: 1.01x faster                                                                  |
| chaos                    | 63.6 ms                                                                     | 63.0 ms: 1.01x faster                                                                 |
| sqlglot_transpile        | 1.81 ms                                                                     | 1.79 ms: 1.01x faster                                                                 |
| deepcopy_memo            | 37.3 us                                                                     | 37.0 us: 1.01x faster                                                                 |
| sqlglot_parse            | 1.40 ms                                                                     | 1.39 ms: 1.01x faster                                                                 |
| sqlite_synth             | 2.69 us                                                                     | 2.66 us: 1.01x faster                                                                 |
| json                     | 5.15 ms                                                                     | 5.10 ms: 1.01x faster                                                                 |
| deltablue                | 3.67 ms                                                                     | 3.64 ms: 1.01x faster                                                                 |
| nqueens                  | 88.4 ms                                                                     | 88.0 ms: 1.01x faster                                                                 |
| docutils                 | 2.88 sec                                                                    | 2.87 sec: 1.00x faster                                                                |
| pickle                   | 10.1 us                                                                     | 10.0 us: 1.00x faster                                                                 |
| sqlglot_optimize         | 58.9 ms                                                                     | 58.7 ms: 1.00x faster                                                                 |
| mypy2                    | 372 ms                                                                      | 372 ms: 1.00x faster                                                                  |
| pyflate                  | 509 ms                                                                      | 508 ms: 1.00x faster                                                                  |
| asyncio_tcp_ssl          | 1.58 sec                                                                    | 1.58 sec: 1.00x faster                                                                |
| python_startup_no_site   | 8.67 ms                                                                     | 8.68 ms: 1.00x slower                                                                 |
| python_startup           | 12.6 ms                                                                     | 12.7 ms: 1.00x slower                                                                 |
| dulwich_log              | 69.3 ms                                                                     | 69.6 ms: 1.00x slower                                                                 |
| mdp                      | 2.51 sec                                                                    | 2.52 sec: 1.00x slower                                                                |
| tomli_loads              | 2.19 sec                                                                    | 2.21 sec: 1.00x slower                                                                |
| go                       | 171 ms                                                                      | 171 ms: 1.00x slower                                                                  |
| pidigits                 | 263 ms                                                                      | 265 ms: 1.01x slower                                                                  |
| spectral_norm            | 90.4 ms                                                                     | 90.9 ms: 1.01x slower                                                                 |
| json_dumps               | 10.4 ms                                                                     | 10.4 ms: 1.01x slower                                                                 |
| pprint_safe_repr         | 816 ms                                                                      | 821 ms: 1.01x slower                                                                  |
| async_tree_io            | 1.08 sec                                                                    | 1.09 sec: 1.01x slower                                                                |
| logging_format           | 7.30 us                                                                     | 7.36 us: 1.01x slower                                                                 |
| fannkuch                 | 390 ms                                                                      | 393 ms: 1.01x slower                                                                  |
| pprint_pformat           | 1.66 sec                                                                    | 1.68 sec: 1.01x slower                                                                |
| nbody                    | 85.9 ms                                                                     | 86.7 ms: 1.01x slower                                                                 |
| meteor_contest           | 130 ms                                                                      | 131 ms: 1.01x slower                                                                  |
| pickle_pure_python       | 314 us                                                                      | 318 us: 1.01x slower                                                                  |
| logging_simple           | 6.62 us                                                                     | 6.71 us: 1.01x slower                                                                 |
| crypto_pyaes             | 72.4 ms                                                                     | 73.4 ms: 1.01x slower                                                                 |
| comprehensions           | 21.7 us                                                                     | 22.1 us: 1.02x slower                                                                 |
| generators               | 34.5 ms                                                                     | 35.3 ms: 1.02x slower                                                                 |
| async_generators         | 386 ms                                                                      | 395 ms: 1.02x slower                                                                  |
| create_gc_cycles         | 1.64 ms                                                                     | 1.68 ms: 1.02x slower                                                                 |
| scimark_monte_carlo      | 65.4 ms                                                                     | 66.9 ms: 1.02x slower                                                                 |
| unpickle                 | 14.5 us                                                                     | 15.0 us: 1.03x slower                                                                 |
| xml_etree_parse          | 148 ms                                                                      | 153 ms: 1.03x slower                                                                  |
| richards_super           | 59.0 ms                                                                     | 60.9 ms: 1.03x slower                                                                 |
| pycparser                | 1.29 sec                                                                    | 1.34 sec: 1.04x slower                                                                |
| scimark_fft              | 298 ms                                                                      | 310 ms: 1.04x slower                                                                  |
| regex_dna                | 240 ms                                                                      | 250 ms: 1.04x slower                                                                  |
| unpickle_pure_python     | 228 us                                                                      | 238 us: 1.05x slower                                                                  |
| richards                 | 52.2 ms                                                                     | 54.8 ms: 1.05x slower                                                                 |
| bench_mp_pool            | 4.60 ms                                                                     | 4.83 ms: 1.05x slower                                                                 |
| regex_v8                 | 24.6 ms                                                                     | 26.0 ms: 1.06x slower                                                                 |
| unpickle_list            | 4.54 us                                                                     | 4.84 us: 1.07x slower                                                                 |
| Geometric mean           | (ref)                                                                       | 1.00x slower                                                                          |

Benchmark hidden because not significant (21): regex_effbot, mako, gc_traversal, dask, coroutines, deepcopy_reduce, pickle_list, regex_compile, scimark_sor, logging_silent, tornado_http, xml_etree_generate, telco, xml_etree_process, raytrace, float, async_tree_memoization, async_tree_none, async_tree_cpu_io_mixed, xml_etree_iterparse, bench_thread_pool


# HPT report

- Reliability score: 98.68% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
