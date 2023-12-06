
# Results vs. 3.12.0

- fork: python
- ref: main
- machine: linux-x86_64
- commit hash: a47c13c
- commit date: 2023-08-19
- overall geometric mean: 1.02x slower
- HPT reliability: 94.69%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230819-pythonperf2-x86_64-python-main-3.13.0a0-a47c13c |
|----------------|:------------------------------------------------------------:|:-----------------------------------------------------------:|
| docutils       | 2.89 sec                                                     | 2.87 sec: 1.01x faster                                      |
| Geometric mean | (ref)                                                        | 1.01x faster                                                |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230819-pythonperf2-x86_64-python-main-3.13.0a0-a47c13c |
|----------------|:------------------------------------------------------------:|:-----------------------------------------------------------:|
| nbody          | 94.1 ms                                                      | 84.9 ms: 1.11x faster                                       |
| pidigits       | 264 ms                                                       | 260 ms: 1.02x faster                                        |
| float          | 78.5 ms                                                      | 77.4 ms: 1.01x faster                                       |
| Geometric mean | (ref)                                                        | 1.04x faster                                                |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230819-pythonperf2-x86_64-python-main-3.13.0a0-a47c13c |
|----------------|:------------------------------------------------------------:|:-----------------------------------------------------------:|
| regex_compile  | 146 ms                                                       | 148 ms: 1.02x slower                                        |
| regex_dna      | 241 ms                                                       | 248 ms: 1.03x slower                                        |
| regex_v8       | 25.0 ms                                                      | 26.3 ms: 1.05x slower                                       |
| regex_effbot   | 3.47 ms                                                      | 3.71 ms: 1.07x slower                                       |
| Geometric mean | (ref)                                                        | 1.04x slower                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230819-pythonperf2-x86_64-python-main-3.13.0a0-a47c13c |
|----------------------|:------------------------------------------------------------:|:-----------------------------------------------------------:|
| unpickle_list        | 4.77 us                                                      | 4.60 us: 1.04x faster                                       |
| unpickle             | 14.8 us                                                      | 14.4 us: 1.03x faster                                       |
| pickle_pure_python   | 323 us                                                       | 317 us: 1.02x faster                                        |
| xml_etree_parse      | 146 ms                                                       | 145 ms: 1.01x faster                                        |
| json_dumps           | 10.2 ms                                                      | 10.3 ms: 1.01x slower                                       |
| xml_etree_generate   | 86.1 ms                                                      | 86.6 ms: 1.01x slower                                       |
| xml_etree_process    | 58.3 ms                                                      | 58.8 ms: 1.01x slower                                       |
| tomli_loads          | 2.20 sec                                                     | 2.23 sec: 1.02x slower                                      |
| xml_etree_iterparse  | 103 ms                                                       | 106 ms: 1.02x slower                                        |
| pickle_dict          | 31.7 us                                                      | 32.5 us: 1.02x slower                                       |
| json_loads           | 24.3 us                                                      | 25.2 us: 1.04x slower                                       |
| unpickle_pure_python | 207 us                                                       | 228 us: 1.10x slower                                        |
| Geometric mean       | (ref)                                                        | 1.01x slower                                                |

Benchmark hidden because not significant (2): pickle_list, pickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230819-pythonperf2-x86_64-python-main-3.13.0a0-a47c13c |
|------------------------|:------------------------------------------------------------:|:-----------------------------------------------------------:|
| python_startup         | 11.7 ms                                                      | 11.6 ms: 1.01x faster                                       |
| python_startup_no_site | 8.70 ms                                                      | 8.64 ms: 1.01x faster                                       |
| Geometric mean         | (ref)                                                        | 1.01x faster                                                |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230819-pythonperf2-x86_64-python-main-3.13.0a0-a47c13c |
|-----------|:------------------------------------------------------------:|:-----------------------------------------------------------:|
| mako      | 9.94 ms                                                      | 10.4 ms: 1.04x slower                                       |

All benchmarks:
===============

| Benchmark                | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230819-pythonperf2-x86_64-python-main-3.13.0a0-a47c13c |
|--------------------------|:------------------------------------------------------------:|:-----------------------------------------------------------:|
| bench_mp_pool            | 5.34 ms                                                      | 4.48 ms: 1.19x faster                                       |
| scimark_sparse_mat_mult  | 4.42 ms                                                      | 3.99 ms: 1.11x faster                                       |
| nbody                    | 94.1 ms                                                      | 84.9 ms: 1.11x faster                                       |
| crypto_pyaes             | 80.9 ms                                                      | 73.2 ms: 1.10x faster                                       |
| raytrace                 | 302 ms                                                       | 274 ms: 1.10x faster                                        |
| coverage                 | 89.6 ms                                                      | 84.0 ms: 1.07x faster                                       |
| scimark_monte_carlo      | 72.4 ms                                                      | 68.5 ms: 1.06x faster                                       |
| create_gc_cycles         | 1.67 ms                                                      | 1.59 ms: 1.05x faster                                       |
| async_tree_none          | 459 ms                                                       | 441 ms: 1.04x faster                                        |
| unpickle_list            | 4.77 us                                                      | 4.60 us: 1.04x faster                                       |
| scimark_fft              | 304 ms                                                       | 294 ms: 1.03x faster                                        |
| unpickle                 | 14.8 us                                                      | 14.4 us: 1.03x faster                                       |
| asyncio_tcp              | 381 ms                                                       | 372 ms: 1.03x faster                                        |
| pathlib                  | 19.8 ms                                                      | 19.3 ms: 1.03x faster                                       |
| deepcopy_reduce          | 3.46 us                                                      | 3.38 us: 1.02x faster                                       |
| pickle_pure_python       | 323 us                                                       | 317 us: 1.02x faster                                        |
| pidigits                 | 264 ms                                                       | 260 ms: 1.02x faster                                        |
| float                    | 78.5 ms                                                      | 77.4 ms: 1.01x faster                                       |
| generators               | 36.7 ms                                                      | 36.2 ms: 1.01x faster                                       |
| typing_runtime_protocols | 151 us                                                       | 150 us: 1.01x faster                                        |
| python_startup           | 11.7 ms                                                      | 11.6 ms: 1.01x faster                                       |
| xml_etree_parse          | 146 ms                                                       | 145 ms: 1.01x faster                                        |
| chaos                    | 62.9 ms                                                      | 62.4 ms: 1.01x faster                                       |
| python_startup_no_site   | 8.70 ms                                                      | 8.64 ms: 1.01x faster                                       |
| sqlglot_normalize        | 117 ms                                                       | 116 ms: 1.01x faster                                        |
| docutils                 | 2.89 sec                                                     | 2.87 sec: 1.01x faster                                      |
| pprint_safe_repr         | 823 ms                                                       | 819 ms: 1.01x faster                                        |
| pprint_pformat           | 1.67 sec                                                     | 1.67 sec: 1.00x faster                                      |
| mdp                      | 2.53 sec                                                     | 2.54 sec: 1.00x slower                                      |
| json_dumps               | 10.2 ms                                                      | 10.3 ms: 1.01x slower                                       |
| xml_etree_generate       | 86.1 ms                                                      | 86.6 ms: 1.01x slower                                       |
| sqlite_synth             | 2.70 us                                                      | 2.72 us: 1.01x slower                                       |
| sqlglot_optimize         | 57.8 ms                                                      | 58.3 ms: 1.01x slower                                       |
| xml_etree_process        | 58.3 ms                                                      | 58.8 ms: 1.01x slower                                       |
| logging_format           | 7.37 us                                                      | 7.45 us: 1.01x slower                                       |
| json                     | 5.14 ms                                                      | 5.20 ms: 1.01x slower                                       |
| deepcopy                 | 376 us                                                       | 381 us: 1.01x slower                                        |
| comprehensions           | 21.9 us                                                      | 22.2 us: 1.01x slower                                       |
| tomli_loads              | 2.20 sec                                                     | 2.23 sec: 1.02x slower                                      |
| async_generators         | 385 ms                                                       | 392 ms: 1.02x slower                                        |
| deepcopy_memo            | 37.4 us                                                      | 38.1 us: 1.02x slower                                       |
| regex_compile            | 146 ms                                                       | 148 ms: 1.02x slower                                        |
| sqlglot_parse            | 1.40 ms                                                      | 1.43 ms: 1.02x slower                                       |
| meteor_contest           | 128 ms                                                       | 131 ms: 1.02x slower                                        |
| xml_etree_iterparse      | 103 ms                                                       | 106 ms: 1.02x slower                                        |
| sqlglot_transpile        | 1.80 ms                                                      | 1.85 ms: 1.02x slower                                       |
| pickle_dict              | 31.7 us                                                      | 32.5 us: 1.02x slower                                       |
| regex_dna                | 241 ms                                                       | 248 ms: 1.03x slower                                        |
| async_tree_io            | 1.06 sec                                                     | 1.09 sec: 1.03x slower                                      |
| json_loads               | 24.3 us                                                      | 25.2 us: 1.04x slower                                       |
| mako                     | 9.94 ms                                                      | 10.4 ms: 1.04x slower                                       |
| logging_silent           | 95.6 ns                                                      | 100 ns: 1.05x slower                                        |
| pycparser                | 1.27 sec                                                     | 1.34 sec: 1.05x slower                                      |
| dulwich_log              | 65.3 ms                                                      | 68.9 ms: 1.05x slower                                       |
| regex_v8                 | 25.0 ms                                                      | 26.3 ms: 1.05x slower                                       |
| gc_traversal             | 3.54 ms                                                      | 3.75 ms: 1.06x slower                                       |
| regex_effbot             | 3.47 ms                                                      | 3.71 ms: 1.07x slower                                       |
| hexiom                   | 5.96 ms                                                      | 6.52 ms: 1.10x slower                                       |
| unpickle_pure_python     | 207 us                                                       | 228 us: 1.10x slower                                        |
| spectral_norm            | 91.6 ms                                                      | 101 ms: 1.11x slower                                        |
| deltablue                | 3.29 ms                                                      | 3.71 ms: 1.13x slower                                       |
| go                       | 150 ms                                                       | 170 ms: 1.13x slower                                        |
| pyflate                  | 447 ms                                                       | 509 ms: 1.14x slower                                        |
| telco                    | 6.96 ms                                                      | 7.94 ms: 1.14x slower                                       |
| fannkuch                 | 350 ms                                                       | 399 ms: 1.14x slower                                        |
| richards_super           | 51.7 ms                                                      | 60.6 ms: 1.17x slower                                       |
| unpack_sequence          | 53.3 ns                                                      | 62.6 ns: 1.17x slower                                       |
| richards                 | 45.0 ms                                                      | 53.8 ms: 1.19x slower                                       |
| mypy2                    | 368 ms                                                       | 465 ms: 1.26x slower                                        |
| scimark_sor              | 110 ms                                                       | 147 ms: 1.34x slower                                        |
| dask                     | 397 ms                                                       | 589 ms: 1.48x slower                                        |
| Geometric mean           | (ref)                                                        | 1.02x slower                                                |

Benchmark hidden because not significant (11): tornado_http, coroutines, async_tree_cpu_io_mixed, bench_thread_pool, nqueens, scimark_lu, pickle_list, logging_simple, asyncio_tcp_ssl, pickle, async_tree_memoization
Ignored benchmarks (1) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: 2to3


# HPT report

- Reliability score: 94.69% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
