
# Results vs. 3.12.0

- fork: brandtbucher
- ref: justin_o2
- machine: linux-x86_64
- commit hash: 2a353e9
- commit date: 2023-10-13
- overall geometric mean: 1.06x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.02x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231013-pythonperf2-x86_64-brandtbucher-justin_o2-3.13.0a0-2a353e9 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------------:|
| docutils       | 2.89 sec                                                     | 2.94 sec: 1.02x slower                                                 |
| tornado_http   | 122 ms                                                       | 124 ms: 1.02x slower                                                   |
| Geometric mean | (ref)                                                        | 1.02x slower                                                           |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231013-pythonperf2-x86_64-brandtbucher-justin_o2-3.13.0a0-2a353e9 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------------:|
| pidigits       | 264 ms                                                       | 265 ms: 1.00x slower                                                   |
| nbody          | 94.1 ms                                                      | 102 ms: 1.08x slower                                                   |
| float          | 78.5 ms                                                      | 89.3 ms: 1.14x slower                                                  |
| Geometric mean | (ref)                                                        | 1.07x slower                                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231013-pythonperf2-x86_64-brandtbucher-justin_o2-3.13.0a0-2a353e9 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------------:|
| regex_v8       | 25.0 ms                                                      | 25.2 ms: 1.01x slower                                                  |
| regex_dna      | 241 ms                                                       | 245 ms: 1.02x slower                                                   |
| regex_effbot   | 3.47 ms                                                      | 3.57 ms: 1.03x slower                                                  |
| regex_compile  | 146 ms                                                       | 160 ms: 1.10x slower                                                   |
| Geometric mean | (ref)                                                        | 1.04x slower                                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231013-pythonperf2-x86_64-brandtbucher-justin_o2-3.13.0a0-2a353e9 |
|----------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------:|
| pickle_list          | 4.39 us                                                      | 4.30 us: 1.02x faster                                                  |
| pickle_pure_python   | 323 us                                                       | 319 us: 1.01x faster                                                   |
| unpickle             | 14.8 us                                                      | 14.7 us: 1.01x faster                                                  |
| pickle               | 10.1 us                                                      | 10.2 us: 1.01x slower                                                  |
| json_loads           | 24.3 us                                                      | 24.5 us: 1.01x slower                                                  |
| xml_etree_generate   | 86.1 ms                                                      | 87.4 ms: 1.01x slower                                                  |
| xml_etree_process    | 58.3 ms                                                      | 59.3 ms: 1.02x slower                                                  |
| json_dumps           | 10.2 ms                                                      | 10.6 ms: 1.03x slower                                                  |
| pickle_dict          | 31.7 us                                                      | 33.0 us: 1.04x slower                                                  |
| xml_etree_parse      | 146 ms                                                       | 152 ms: 1.04x slower                                                   |
| xml_etree_iterparse  | 103 ms                                                       | 108 ms: 1.04x slower                                                   |
| unpickle_pure_python | 207 us                                                       | 229 us: 1.11x slower                                                   |
| tomli_loads          | 2.20 sec                                                     | 2.46 sec: 1.12x slower                                                 |
| Geometric mean       | (ref)                                                        | 1.03x slower                                                           |

Benchmark hidden because not significant (1): unpickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231013-pythonperf2-x86_64-brandtbucher-justin_o2-3.13.0a0-2a353e9 |
|------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------:|
| python_startup_no_site | 8.70 ms                                                      | 8.72 ms: 1.00x slower                                                  |
| python_startup         | 11.7 ms                                                      | 12.7 ms: 1.08x slower                                                  |
| Geometric mean         | (ref)                                                        | 1.04x slower                                                           |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231013-pythonperf2-x86_64-brandtbucher-justin_o2-3.13.0a0-2a353e9 |
|-----------|:------------------------------------------------------------:|:----------------------------------------------------------------------:|
| mako      | 9.94 ms                                                      | 12.1 ms: 1.21x slower                                                  |

All benchmarks:
===============

| Benchmark                | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231013-pythonperf2-x86_64-brandtbucher-justin_o2-3.13.0a0-2a353e9 |
|--------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------:|
| bench_mp_pool            | 5.34 ms                                                      | 4.55 ms: 1.17x faster                                                  |
| unpack_sequence          | 53.3 ns                                                      | 48.3 ns: 1.10x faster                                                  |
| coverage                 | 89.6 ms                                                      | 86.1 ms: 1.04x faster                                                  |
| create_gc_cycles         | 1.67 ms                                                      | 1.61 ms: 1.04x faster                                                  |
| deepcopy_reduce          | 3.46 us                                                      | 3.33 us: 1.04x faster                                                  |
| raytrace                 | 302 ms                                                       | 292 ms: 1.03x faster                                                   |
| asyncio_tcp              | 381 ms                                                       | 370 ms: 1.03x faster                                                   |
| async_tree_none          | 459 ms                                                       | 449 ms: 1.02x faster                                                   |
| pickle_list              | 4.39 us                                                      | 4.30 us: 1.02x faster                                                  |
| pickle_pure_python       | 323 us                                                       | 319 us: 1.01x faster                                                   |
| unpickle                 | 14.8 us                                                      | 14.7 us: 1.01x faster                                                  |
| generators               | 36.7 ms                                                      | 36.4 ms: 1.01x faster                                                  |
| deepcopy                 | 376 us                                                       | 374 us: 1.00x faster                                                   |
| python_startup_no_site   | 8.70 ms                                                      | 8.72 ms: 1.00x slower                                                  |
| pidigits                 | 264 ms                                                       | 265 ms: 1.00x slower                                                   |
| asyncio_tcp_ssl          | 1.58 sec                                                     | 1.58 sec: 1.00x slower                                                 |
| pickle                   | 10.1 us                                                      | 10.2 us: 1.01x slower                                                  |
| json                     | 5.14 ms                                                      | 5.18 ms: 1.01x slower                                                  |
| regex_v8                 | 25.0 ms                                                      | 25.2 ms: 1.01x slower                                                  |
| json_loads               | 24.3 us                                                      | 24.5 us: 1.01x slower                                                  |
| coroutines               | 23.0 ms                                                      | 23.3 ms: 1.01x slower                                                  |
| xml_etree_generate       | 86.1 ms                                                      | 87.4 ms: 1.01x slower                                                  |
| async_tree_cpu_io_mixed  | 706 ms                                                       | 716 ms: 1.01x slower                                                   |
| sqlglot_normalize        | 117 ms                                                       | 119 ms: 1.02x slower                                                   |
| regex_dna                | 241 ms                                                       | 245 ms: 1.02x slower                                                   |
| async_tree_memoization   | 553 ms                                                       | 563 ms: 1.02x slower                                                   |
| xml_etree_process        | 58.3 ms                                                      | 59.3 ms: 1.02x slower                                                  |
| docutils                 | 2.89 sec                                                     | 2.94 sec: 1.02x slower                                                 |
| sqlglot_parse            | 1.40 ms                                                      | 1.43 ms: 1.02x slower                                                  |
| pathlib                  | 19.8 ms                                                      | 20.2 ms: 1.02x slower                                                  |
| tornado_http             | 122 ms                                                       | 124 ms: 1.02x slower                                                   |
| typing_runtime_protocols | 151 us                                                       | 155 us: 1.02x slower                                                   |
| sqlglot_transpile        | 1.80 ms                                                      | 1.85 ms: 1.02x slower                                                  |
| spectral_norm            | 91.6 ms                                                      | 94.0 ms: 1.03x slower                                                  |
| logging_simple           | 6.73 us                                                      | 6.93 us: 1.03x slower                                                  |
| mdp                      | 2.53 sec                                                     | 2.61 sec: 1.03x slower                                                 |
| regex_effbot             | 3.47 ms                                                      | 3.57 ms: 1.03x slower                                                  |
| json_dumps               | 10.2 ms                                                      | 10.6 ms: 1.03x slower                                                  |
| crypto_pyaes             | 80.9 ms                                                      | 83.6 ms: 1.03x slower                                                  |
| scimark_monte_carlo      | 72.4 ms                                                      | 74.9 ms: 1.04x slower                                                  |
| logging_format           | 7.37 us                                                      | 7.64 us: 1.04x slower                                                  |
| scimark_lu               | 101 ms                                                       | 105 ms: 1.04x slower                                                   |
| pickle_dict              | 31.7 us                                                      | 33.0 us: 1.04x slower                                                  |
| xml_etree_parse          | 146 ms                                                       | 152 ms: 1.04x slower                                                   |
| sqlglot_optimize         | 57.8 ms                                                      | 60.2 ms: 1.04x slower                                                  |
| async_tree_io            | 1.06 sec                                                     | 1.10 sec: 1.04x slower                                                 |
| mypy2                    | 368 ms                                                       | 384 ms: 1.04x slower                                                   |
| logging_silent           | 95.6 ns                                                      | 99.9 ns: 1.04x slower                                                  |
| xml_etree_iterparse      | 103 ms                                                       | 108 ms: 1.04x slower                                                   |
| pycparser                | 1.27 sec                                                     | 1.34 sec: 1.05x slower                                                 |
| pprint_safe_repr         | 823 ms                                                       | 878 ms: 1.07x slower                                                   |
| dulwich_log              | 65.3 ms                                                      | 69.9 ms: 1.07x slower                                                  |
| pprint_pformat           | 1.67 sec                                                     | 1.79 sec: 1.07x slower                                                 |
| scimark_sparse_mat_mult  | 4.42 ms                                                      | 4.75 ms: 1.07x slower                                                  |
| deepcopy_memo            | 37.4 us                                                      | 40.2 us: 1.08x slower                                                  |
| python_startup           | 11.7 ms                                                      | 12.7 ms: 1.08x slower                                                  |
| nbody                    | 94.1 ms                                                      | 102 ms: 1.08x slower                                                   |
| async_generators         | 385 ms                                                       | 418 ms: 1.08x slower                                                   |
| meteor_contest           | 128 ms                                                       | 139 ms: 1.09x slower                                                   |
| regex_compile            | 146 ms                                                       | 160 ms: 1.10x slower                                                   |
| unpickle_pure_python     | 207 us                                                       | 229 us: 1.11x slower                                                   |
| gc_traversal             | 3.54 ms                                                      | 3.95 ms: 1.11x slower                                                  |
| chaos                    | 62.9 ms                                                      | 70.3 ms: 1.12x slower                                                  |
| tomli_loads              | 2.20 sec                                                     | 2.46 sec: 1.12x slower                                                 |
| richards_super           | 51.7 ms                                                      | 58.4 ms: 1.13x slower                                                  |
| float                    | 78.5 ms                                                      | 89.3 ms: 1.14x slower                                                  |
| nqueens                  | 90.1 ms                                                      | 103 ms: 1.15x slower                                                   |
| richards                 | 45.0 ms                                                      | 52.3 ms: 1.16x slower                                                  |
| scimark_fft              | 304 ms                                                       | 356 ms: 1.17x slower                                                   |
| go                       | 150 ms                                                       | 176 ms: 1.17x slower                                                   |
| pyflate                  | 447 ms                                                       | 530 ms: 1.19x slower                                                   |
| telco                    | 6.96 ms                                                      | 8.30 ms: 1.19x slower                                                  |
| mako                     | 9.94 ms                                                      | 12.1 ms: 1.21x slower                                                  |
| fannkuch                 | 350 ms                                                       | 440 ms: 1.26x slower                                                   |
| comprehensions           | 21.9 us                                                      | 28.7 us: 1.31x slower                                                  |
| scimark_sor              | 110 ms                                                       | 151 ms: 1.38x slower                                                   |
| deltablue                | 3.29 ms                                                      | 4.89 ms: 1.49x slower                                                  |
| hexiom                   | 5.96 ms                                                      | 8.97 ms: 1.51x slower                                                  |
| Geometric mean           | (ref)                                                        | 1.06x slower                                                           |

Benchmark hidden because not significant (3): unpickle_list, sqlite_synth, bench_thread_pool
Ignored benchmarks (2) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: 2to3, dask


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.03x
- 95% likely to have a slowdown of 1.03x
- 99% likely to have a slowdown of 1.02x
