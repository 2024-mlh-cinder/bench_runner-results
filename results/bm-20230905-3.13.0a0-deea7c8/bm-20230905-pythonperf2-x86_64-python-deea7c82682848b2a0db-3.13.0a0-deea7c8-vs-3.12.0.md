
# Results vs. 3.12.0

- fork: python
- ref: deea7c82682848b2a0db
- machine: linux-x86_64
- commit hash: deea7c8
- commit date: 2023-09-05
- overall geometric mean: 1.02x slower
- HPT reliability: 96.76%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230905-pythonperf2-x86_64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| docutils       | 2.89 sec                                                     | 2.91 sec: 1.01x slower                                                      |
| Geometric mean | (ref)                                                        | 1.00x slower                                                                |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230905-pythonperf2-x86_64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| nbody          | 94.1 ms                                                      | 85.3 ms: 1.10x faster                                                       |
| pidigits       | 264 ms                                                       | 264 ms: 1.00x slower                                                        |
| float          | 78.5 ms                                                      | 80.5 ms: 1.03x slower                                                       |
| Geometric mean | (ref)                                                        | 1.02x faster                                                                |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230905-pythonperf2-x86_64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_compile  | 146 ms                                                       | 148 ms: 1.01x slower                                                        |
| regex_dna      | 241 ms                                                       | 247 ms: 1.02x slower                                                        |
| regex_v8       | 25.0 ms                                                      | 25.8 ms: 1.03x slower                                                       |
| regex_effbot   | 3.47 ms                                                      | 3.75 ms: 1.08x slower                                                       |
| Geometric mean | (ref)                                                        | 1.04x slower                                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230905-pythonperf2-x86_64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 |
|----------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| unpickle             | 14.8 us                                                      | 14.3 us: 1.04x faster                                                       |
| xml_etree_generate   | 86.1 ms                                                      | 83.8 ms: 1.03x faster                                                       |
| pickle_pure_python   | 323 us                                                       | 316 us: 1.02x faster                                                        |
| xml_etree_process    | 58.3 ms                                                      | 57.8 ms: 1.01x faster                                                       |
| unpickle_list        | 4.77 us                                                      | 4.73 us: 1.01x faster                                                       |
| pickle_list          | 4.39 us                                                      | 4.36 us: 1.01x faster                                                       |
| tomli_loads          | 2.20 sec                                                     | 2.21 sec: 1.01x slower                                                      |
| json_dumps           | 10.2 ms                                                      | 10.3 ms: 1.01x slower                                                       |
| xml_etree_parse      | 146 ms                                                       | 149 ms: 1.02x slower                                                        |
| pickle_dict          | 31.7 us                                                      | 32.4 us: 1.02x slower                                                       |
| xml_etree_iterparse  | 103 ms                                                       | 106 ms: 1.03x slower                                                        |
| json_loads           | 24.3 us                                                      | 25.2 us: 1.04x slower                                                       |
| unpickle_pure_python | 207 us                                                       | 228 us: 1.10x slower                                                        |
| Geometric mean       | (ref)                                                        | 1.01x slower                                                                |

Benchmark hidden because not significant (1): pickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230905-pythonperf2-x86_64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 |
|------------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| python_startup         | 11.7 ms                                                      | 11.9 ms: 1.02x slower                                                       |
| python_startup_no_site | 8.70 ms                                                      | 8.86 ms: 1.02x slower                                                       |
| Geometric mean         | (ref)                                                        | 1.02x slower                                                                |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230905-pythonperf2-x86_64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 |
|-----------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| mako      | 9.94 ms                                                      | 10.2 ms: 1.03x slower                                                       |

All benchmarks:
===============

| Benchmark                | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230905-pythonperf2-x86_64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 |
|--------------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| nbody                    | 94.1 ms                                                      | 85.3 ms: 1.10x faster                                                       |
| crypto_pyaes             | 80.9 ms                                                      | 73.6 ms: 1.10x faster                                                       |
| unpack_sequence          | 53.3 ns                                                      | 49.1 ns: 1.09x faster                                                       |
| raytrace                 | 302 ms                                                       | 279 ms: 1.08x faster                                                        |
| coverage                 | 89.6 ms                                                      | 83.0 ms: 1.08x faster                                                       |
| scimark_sparse_mat_mult  | 4.42 ms                                                      | 4.13 ms: 1.07x faster                                                       |
| scimark_monte_carlo      | 72.4 ms                                                      | 68.6 ms: 1.05x faster                                                       |
| async_tree_none          | 459 ms                                                       | 436 ms: 1.05x faster                                                        |
| generators               | 36.7 ms                                                      | 35.0 ms: 1.05x faster                                                       |
| unpickle                 | 14.8 us                                                      | 14.3 us: 1.04x faster                                                       |
| xml_etree_generate       | 86.1 ms                                                      | 83.8 ms: 1.03x faster                                                       |
| asyncio_tcp              | 381 ms                                                       | 372 ms: 1.02x faster                                                        |
| pickle_pure_python       | 323 us                                                       | 316 us: 1.02x faster                                                        |
| spectral_norm            | 91.6 ms                                                      | 90.1 ms: 1.02x faster                                                       |
| scimark_fft              | 304 ms                                                       | 299 ms: 1.02x faster                                                        |
| nqueens                  | 90.1 ms                                                      | 88.8 ms: 1.02x faster                                                       |
| chaos                    | 62.9 ms                                                      | 62.1 ms: 1.01x faster                                                       |
| mdp                      | 2.53 sec                                                     | 2.50 sec: 1.01x faster                                                      |
| typing_runtime_protocols | 151 us                                                       | 150 us: 1.01x faster                                                        |
| xml_etree_process        | 58.3 ms                                                      | 57.8 ms: 1.01x faster                                                       |
| unpickle_list            | 4.77 us                                                      | 4.73 us: 1.01x faster                                                       |
| pprint_safe_repr         | 823 ms                                                       | 818 ms: 1.01x faster                                                        |
| pickle_list              | 4.39 us                                                      | 4.36 us: 1.01x faster                                                       |
| sqlglot_normalize        | 117 ms                                                       | 116 ms: 1.01x faster                                                        |
| pprint_pformat           | 1.67 sec                                                     | 1.67 sec: 1.01x faster                                                      |
| pathlib                  | 19.8 ms                                                      | 19.7 ms: 1.00x faster                                                       |
| pidigits                 | 264 ms                                                       | 264 ms: 1.00x slower                                                        |
| asyncio_tcp_ssl          | 1.58 sec                                                     | 1.58 sec: 1.00x slower                                                      |
| meteor_contest           | 128 ms                                                       | 128 ms: 1.00x slower                                                        |
| tomli_loads              | 2.20 sec                                                     | 2.21 sec: 1.01x slower                                                      |
| docutils                 | 2.89 sec                                                     | 2.91 sec: 1.01x slower                                                      |
| json_dumps               | 10.2 ms                                                      | 10.3 ms: 1.01x slower                                                       |
| mypy2                    | 368 ms                                                       | 372 ms: 1.01x slower                                                        |
| sqlglot_parse            | 1.40 ms                                                      | 1.42 ms: 1.01x slower                                                       |
| deepcopy_reduce          | 3.46 us                                                      | 3.50 us: 1.01x slower                                                       |
| regex_compile            | 146 ms                                                       | 148 ms: 1.01x slower                                                        |
| python_startup           | 11.7 ms                                                      | 11.9 ms: 1.02x slower                                                       |
| json                     | 5.14 ms                                                      | 5.23 ms: 1.02x slower                                                       |
| xml_etree_parse          | 146 ms                                                       | 149 ms: 1.02x slower                                                        |
| python_startup_no_site   | 8.70 ms                                                      | 8.86 ms: 1.02x slower                                                       |
| deepcopy_memo            | 37.4 us                                                      | 38.2 us: 1.02x slower                                                       |
| comprehensions           | 21.9 us                                                      | 22.4 us: 1.02x slower                                                       |
| pickle_dict              | 31.7 us                                                      | 32.4 us: 1.02x slower                                                       |
| logging_format           | 7.37 us                                                      | 7.54 us: 1.02x slower                                                       |
| sqlglot_optimize         | 57.8 ms                                                      | 59.1 ms: 1.02x slower                                                       |
| sqlite_synth             | 2.70 us                                                      | 2.76 us: 1.02x slower                                                       |
| regex_dna                | 241 ms                                                       | 247 ms: 1.02x slower                                                        |
| async_tree_io            | 1.06 sec                                                     | 1.08 sec: 1.02x slower                                                      |
| float                    | 78.5 ms                                                      | 80.5 ms: 1.03x slower                                                       |
| logging_simple           | 6.73 us                                                      | 6.91 us: 1.03x slower                                                       |
| xml_etree_iterparse      | 103 ms                                                       | 106 ms: 1.03x slower                                                        |
| mako                     | 9.94 ms                                                      | 10.2 ms: 1.03x slower                                                       |
| regex_v8                 | 25.0 ms                                                      | 25.8 ms: 1.03x slower                                                       |
| async_generators         | 385 ms                                                       | 399 ms: 1.04x slower                                                        |
| logging_silent           | 95.6 ns                                                      | 99.1 ns: 1.04x slower                                                       |
| json_loads               | 24.3 us                                                      | 25.2 us: 1.04x slower                                                       |
| deepcopy                 | 376 us                                                       | 390 us: 1.04x slower                                                        |
| dulwich_log              | 65.3 ms                                                      | 69.3 ms: 1.06x slower                                                       |
| pycparser                | 1.27 sec                                                     | 1.36 sec: 1.06x slower                                                      |
| hexiom                   | 5.96 ms                                                      | 6.43 ms: 1.08x slower                                                       |
| regex_effbot             | 3.47 ms                                                      | 3.75 ms: 1.08x slower                                                       |
| unpickle_pure_python     | 207 us                                                       | 228 us: 1.10x slower                                                        |
| fannkuch                 | 350 ms                                                       | 390 ms: 1.11x slower                                                        |
| gc_traversal             | 3.54 ms                                                      | 3.98 ms: 1.13x slower                                                       |
| deltablue                | 3.29 ms                                                      | 3.71 ms: 1.13x slower                                                       |
| pyflate                  | 447 ms                                                       | 515 ms: 1.15x slower                                                        |
| telco                    | 6.96 ms                                                      | 8.05 ms: 1.16x slower                                                       |
| go                       | 150 ms                                                       | 177 ms: 1.18x slower                                                        |
| richards_super           | 51.7 ms                                                      | 61.7 ms: 1.19x slower                                                       |
| richards                 | 45.0 ms                                                      | 55.4 ms: 1.23x slower                                                       |
| scimark_sor              | 110 ms                                                       | 149 ms: 1.36x slower                                                        |
| dask                     | 397 ms                                                       | 592 ms: 1.49x slower                                                        |
| Geometric mean           | (ref)                                                        | 1.02x slower                                                                |

Benchmark hidden because not significant (10): bench_thread_pool, bench_mp_pool, async_tree_cpu_io_mixed, tornado_http, async_tree_memoization, pickle, scimark_lu, create_gc_cycles, sqlglot_transpile, coroutines
Ignored benchmarks (1) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: 2to3


# HPT report

- Reliability score: 96.76% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
