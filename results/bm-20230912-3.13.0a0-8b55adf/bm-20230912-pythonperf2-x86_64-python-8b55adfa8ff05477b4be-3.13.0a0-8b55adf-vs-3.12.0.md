
# Results vs. 3.12.0

- fork: python
- ref: 8b55adfa8ff05477b4be
- machine: linux-x86_64
- commit hash: 8b55adf
- commit date: 2023-09-12
- overall geometric mean: 1.01x slower
- HPT reliability: 83.93%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230912-pythonperf2-x86_64-python-8b55adfa8ff05477b4be-3.13.0a0-8b55adf |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| docutils       | 2.89 sec                                                     | 2.88 sec: 1.00x faster                                                      |
| Geometric mean | (ref)                                                        | 1.01x faster                                                                |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230912-pythonperf2-x86_64-python-8b55adfa8ff05477b4be-3.13.0a0-8b55adf |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| nbody          | 94.1 ms                                                      | 85.9 ms: 1.10x faster                                                       |
| pidigits       | 264 ms                                                       | 263 ms: 1.00x faster                                                        |
| float          | 78.5 ms                                                      | 80.9 ms: 1.03x slower                                                       |
| Geometric mean | (ref)                                                        | 1.02x faster                                                                |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230912-pythonperf2-x86_64-python-8b55adfa8ff05477b4be-3.13.0a0-8b55adf |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_v8       | 25.0 ms                                                      | 24.6 ms: 1.02x faster                                                       |
| regex_dna      | 241 ms                                                       | 240 ms: 1.01x faster                                                        |
| regex_compile  | 146 ms                                                       | 149 ms: 1.02x slower                                                        |
| regex_effbot   | 3.47 ms                                                      | 3.66 ms: 1.05x slower                                                       |
| Geometric mean | (ref)                                                        | 1.01x slower                                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230912-pythonperf2-x86_64-python-8b55adfa8ff05477b4be-3.13.0a0-8b55adf |
|----------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| unpickle_list        | 4.77 us                                                      | 4.54 us: 1.05x faster                                                       |
| pickle_pure_python   | 323 us                                                       | 314 us: 1.03x faster                                                        |
| unpickle             | 14.8 us                                                      | 14.5 us: 1.02x faster                                                       |
| json_dumps           | 10.2 ms                                                      | 10.4 ms: 1.01x slower                                                       |
| xml_etree_parse      | 146 ms                                                       | 148 ms: 1.01x slower                                                        |
| xml_etree_iterparse  | 103 ms                                                       | 106 ms: 1.03x slower                                                        |
| pickle_dict          | 31.7 us                                                      | 32.9 us: 1.04x slower                                                       |
| json_loads           | 24.3 us                                                      | 25.2 us: 1.04x slower                                                       |
| unpickle_pure_python | 207 us                                                       | 228 us: 1.10x slower                                                        |
| Geometric mean       | (ref)                                                        | 1.01x slower                                                                |

Benchmark hidden because not significant (5): pickle_list, xml_etree_generate, tomli_loads, pickle, xml_etree_process

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230912-pythonperf2-x86_64-python-8b55adfa8ff05477b4be-3.13.0a0-8b55adf |
|------------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| python_startup_no_site | 8.70 ms                                                      | 8.67 ms: 1.00x faster                                                       |
| python_startup         | 11.7 ms                                                      | 12.6 ms: 1.08x slower                                                       |
| Geometric mean         | (ref)                                                        | 1.04x slower                                                                |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230912-pythonperf2-x86_64-python-8b55adfa8ff05477b4be-3.13.0a0-8b55adf |
|-----------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| mako      | 9.94 ms                                                      | 10.4 ms: 1.05x slower                                                       |

All benchmarks:
===============

| Benchmark                | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230912-pythonperf2-x86_64-python-8b55adfa8ff05477b4be-3.13.0a0-8b55adf |
|--------------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| bench_mp_pool            | 5.34 ms                                                      | 4.60 ms: 1.16x faster                                                       |
| crypto_pyaes             | 80.9 ms                                                      | 72.4 ms: 1.12x faster                                                       |
| unpack_sequence          | 53.3 ns                                                      | 47.9 ns: 1.11x faster                                                       |
| scimark_monte_carlo      | 72.4 ms                                                      | 65.4 ms: 1.11x faster                                                       |
| nbody                    | 94.1 ms                                                      | 85.9 ms: 1.10x faster                                                       |
| raytrace                 | 302 ms                                                       | 279 ms: 1.08x faster                                                        |
| coverage                 | 89.6 ms                                                      | 84.0 ms: 1.07x faster                                                       |
| generators               | 36.7 ms                                                      | 34.5 ms: 1.06x faster                                                       |
| async_tree_none          | 459 ms                                                       | 433 ms: 1.06x faster                                                        |
| scimark_sparse_mat_mult  | 4.42 ms                                                      | 4.19 ms: 1.06x faster                                                       |
| unpickle_list            | 4.77 us                                                      | 4.54 us: 1.05x faster                                                       |
| bench_thread_pool        | 980 us                                                       | 949 us: 1.03x faster                                                        |
| pickle_pure_python       | 323 us                                                       | 314 us: 1.03x faster                                                        |
| asyncio_tcp              | 381 ms                                                       | 372 ms: 1.03x faster                                                        |
| scimark_fft              | 304 ms                                                       | 298 ms: 1.02x faster                                                        |
| create_gc_cycles         | 1.67 ms                                                      | 1.64 ms: 1.02x faster                                                       |
| nqueens                  | 90.1 ms                                                      | 88.4 ms: 1.02x faster                                                       |
| logging_simple           | 6.73 us                                                      | 6.62 us: 1.02x faster                                                       |
| unpickle                 | 14.8 us                                                      | 14.5 us: 1.02x faster                                                       |
| regex_v8                 | 25.0 ms                                                      | 24.6 ms: 1.02x faster                                                       |
| async_tree_cpu_io_mixed  | 706 ms                                                       | 696 ms: 1.02x faster                                                        |
| async_tree_memoization   | 553 ms                                                       | 546 ms: 1.01x faster                                                        |
| spectral_norm            | 91.6 ms                                                      | 90.4 ms: 1.01x faster                                                       |
| mdp                      | 2.53 sec                                                     | 2.51 sec: 1.01x faster                                                      |
| logging_format           | 7.37 us                                                      | 7.30 us: 1.01x faster                                                       |
| pprint_safe_repr         | 823 ms                                                       | 816 ms: 1.01x faster                                                        |
| comprehensions           | 21.9 us                                                      | 21.7 us: 1.01x faster                                                       |
| deepcopy_reduce          | 3.46 us                                                      | 3.43 us: 1.01x faster                                                       |
| pprint_pformat           | 1.67 sec                                                     | 1.66 sec: 1.01x faster                                                      |
| regex_dna                | 241 ms                                                       | 240 ms: 1.01x faster                                                        |
| sqlite_synth             | 2.70 us                                                      | 2.69 us: 1.00x faster                                                       |
| python_startup_no_site   | 8.70 ms                                                      | 8.67 ms: 1.00x faster                                                       |
| docutils                 | 2.89 sec                                                     | 2.88 sec: 1.00x faster                                                      |
| deepcopy_memo            | 37.4 us                                                      | 37.3 us: 1.00x faster                                                       |
| pidigits                 | 264 ms                                                       | 263 ms: 1.00x faster                                                        |
| asyncio_tcp_ssl          | 1.58 sec                                                     | 1.58 sec: 1.00x slower                                                      |
| sqlglot_normalize        | 117 ms                                                       | 118 ms: 1.01x slower                                                        |
| mypy2                    | 368 ms                                                       | 372 ms: 1.01x slower                                                        |
| chaos                    | 62.9 ms                                                      | 63.6 ms: 1.01x slower                                                       |
| typing_runtime_protocols | 151 us                                                       | 153 us: 1.01x slower                                                        |
| pycparser                | 1.27 sec                                                     | 1.29 sec: 1.01x slower                                                      |
| json_dumps               | 10.2 ms                                                      | 10.4 ms: 1.01x slower                                                       |
| meteor_contest           | 128 ms                                                       | 130 ms: 1.01x slower                                                        |
| xml_etree_parse          | 146 ms                                                       | 148 ms: 1.01x slower                                                        |
| gc_traversal             | 3.54 ms                                                      | 3.60 ms: 1.02x slower                                                       |
| deepcopy                 | 376 us                                                       | 382 us: 1.02x slower                                                        |
| sqlglot_optimize         | 57.8 ms                                                      | 58.9 ms: 1.02x slower                                                       |
| async_tree_io            | 1.06 sec                                                     | 1.08 sec: 1.02x slower                                                      |
| logging_silent           | 95.6 ns                                                      | 97.7 ns: 1.02x slower                                                       |
| regex_compile            | 146 ms                                                       | 149 ms: 1.02x slower                                                        |
| scimark_lu               | 101 ms                                                       | 103 ms: 1.03x slower                                                        |
| xml_etree_iterparse      | 103 ms                                                       | 106 ms: 1.03x slower                                                        |
| float                    | 78.5 ms                                                      | 80.9 ms: 1.03x slower                                                       |
| pickle_dict              | 31.7 us                                                      | 32.9 us: 1.04x slower                                                       |
| json_loads               | 24.3 us                                                      | 25.2 us: 1.04x slower                                                       |
| mako                     | 9.94 ms                                                      | 10.4 ms: 1.05x slower                                                       |
| regex_effbot             | 3.47 ms                                                      | 3.66 ms: 1.05x slower                                                       |
| dulwich_log              | 65.3 ms                                                      | 69.3 ms: 1.06x slower                                                       |
| python_startup           | 11.7 ms                                                      | 12.6 ms: 1.08x slower                                                       |
| hexiom                   | 5.96 ms                                                      | 6.48 ms: 1.09x slower                                                       |
| unpickle_pure_python     | 207 us                                                       | 228 us: 1.10x slower                                                        |
| fannkuch                 | 350 ms                                                       | 390 ms: 1.11x slower                                                        |
| deltablue                | 3.29 ms                                                      | 3.67 ms: 1.12x slower                                                       |
| go                       | 150 ms                                                       | 171 ms: 1.13x slower                                                        |
| pyflate                  | 447 ms                                                       | 509 ms: 1.14x slower                                                        |
| richards_super           | 51.7 ms                                                      | 59.0 ms: 1.14x slower                                                       |
| telco                    | 6.96 ms                                                      | 7.97 ms: 1.14x slower                                                       |
| richards                 | 45.0 ms                                                      | 52.2 ms: 1.16x slower                                                       |
| scimark_sor              | 110 ms                                                       | 148 ms: 1.35x slower                                                        |
| dask                     | 397 ms                                                       | 589 ms: 1.48x slower                                                        |
| Geometric mean           | (ref)                                                        | 1.01x slower                                                                |

Benchmark hidden because not significant (12): tornado_http, pickle_list, xml_etree_generate, tomli_loads, pickle, sqlglot_parse, coroutines, pathlib, xml_etree_process, json, async_generators, sqlglot_transpile
Ignored benchmarks (1) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: 2to3


# HPT report

- Reliability score: 83.93% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
