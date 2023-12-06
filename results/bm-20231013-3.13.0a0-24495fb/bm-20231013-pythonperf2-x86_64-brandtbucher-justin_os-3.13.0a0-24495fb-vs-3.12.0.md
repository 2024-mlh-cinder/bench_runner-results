
# Results vs. 3.12.0

- fork: brandtbucher
- ref: justin_os
- machine: linux-x86_64
- commit hash: 24495fb
- commit date: 2023-10-13
- overall geometric mean: 1.06x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.02x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231013-pythonperf2-x86_64-brandtbucher-justin_os-3.13.0a0-24495fb |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------------:|
| docutils       | 2.89 sec                                                     | 2.94 sec: 1.02x slower                                                 |
| Geometric mean | (ref)                                                        | 1.02x slower                                                           |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231013-pythonperf2-x86_64-brandtbucher-justin_os-3.13.0a0-24495fb |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------------:|
| pidigits       | 264 ms                                                       | 265 ms: 1.01x slower                                                   |
| nbody          | 94.1 ms                                                      | 100 ms: 1.07x slower                                                   |
| float          | 78.5 ms                                                      | 88.0 ms: 1.12x slower                                                  |
| Geometric mean | (ref)                                                        | 1.06x slower                                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231013-pythonperf2-x86_64-brandtbucher-justin_os-3.13.0a0-24495fb |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------------:|
| regex_dna      | 241 ms                                                       | 248 ms: 1.03x slower                                                   |
| regex_effbot   | 3.47 ms                                                      | 3.59 ms: 1.03x slower                                                  |
| regex_compile  | 146 ms                                                       | 159 ms: 1.09x slower                                                   |
| Geometric mean | (ref)                                                        | 1.04x slower                                                           |

Benchmark hidden because not significant (1): regex_v8

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231013-pythonperf2-x86_64-brandtbucher-justin_os-3.13.0a0-24495fb |
|----------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------:|
| unpickle             | 14.8 us                                                      | 14.7 us: 1.01x faster                                                  |
| pickle_pure_python   | 323 us                                                       | 322 us: 1.00x faster                                                   |
| pickle_dict          | 31.7 us                                                      | 32.2 us: 1.01x slower                                                  |
| xml_etree_process    | 58.3 ms                                                      | 59.6 ms: 1.02x slower                                                  |
| xml_etree_iterparse  | 103 ms                                                       | 106 ms: 1.03x slower                                                   |
| json_loads           | 24.3 us                                                      | 25.0 us: 1.03x slower                                                  |
| json_dumps           | 10.2 ms                                                      | 10.7 ms: 1.05x slower                                                  |
| tomli_loads          | 2.20 sec                                                     | 2.49 sec: 1.13x slower                                                 |
| unpickle_pure_python | 207 us                                                       | 241 us: 1.17x slower                                                   |
| Geometric mean       | (ref)                                                        | 1.03x slower                                                           |

Benchmark hidden because not significant (5): xml_etree_generate, pickle, xml_etree_parse, pickle_list, unpickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231013-pythonperf2-x86_64-brandtbucher-justin_os-3.13.0a0-24495fb |
|------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------:|
| python_startup_no_site | 8.70 ms                                                      | 8.71 ms: 1.00x slower                                                  |
| python_startup         | 11.7 ms                                                      | 12.8 ms: 1.09x slower                                                  |
| Geometric mean         | (ref)                                                        | 1.04x slower                                                           |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231013-pythonperf2-x86_64-brandtbucher-justin_os-3.13.0a0-24495fb |
|-----------|:------------------------------------------------------------:|:----------------------------------------------------------------------:|
| mako      | 9.94 ms                                                      | 12.0 ms: 1.20x slower                                                  |

All benchmarks:
===============

| Benchmark                | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231013-pythonperf2-x86_64-brandtbucher-justin_os-3.13.0a0-24495fb |
|--------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------:|
| unpack_sequence          | 53.3 ns                                                      | 47.1 ns: 1.13x faster                                                  |
| bench_mp_pool            | 5.34 ms                                                      | 4.83 ms: 1.11x faster                                                  |
| coverage                 | 89.6 ms                                                      | 82.4 ms: 1.09x faster                                                  |
| raytrace                 | 302 ms                                                       | 285 ms: 1.06x faster                                                   |
| create_gc_cycles         | 1.67 ms                                                      | 1.60 ms: 1.05x faster                                                  |
| async_tree_none          | 459 ms                                                       | 448 ms: 1.02x faster                                                   |
| asyncio_tcp              | 381 ms                                                       | 374 ms: 1.02x faster                                                   |
| sqlite_synth             | 2.70 us                                                      | 2.67 us: 1.01x faster                                                  |
| deepcopy_reduce          | 3.46 us                                                      | 3.43 us: 1.01x faster                                                  |
| unpickle                 | 14.8 us                                                      | 14.7 us: 1.01x faster                                                  |
| pickle_pure_python       | 323 us                                                       | 322 us: 1.00x faster                                                   |
| python_startup_no_site   | 8.70 ms                                                      | 8.71 ms: 1.00x slower                                                  |
| pidigits                 | 264 ms                                                       | 265 ms: 1.01x slower                                                   |
| asyncio_tcp_ssl          | 1.58 sec                                                     | 1.59 sec: 1.01x slower                                                 |
| pathlib                  | 19.8 ms                                                      | 20.0 ms: 1.01x slower                                                  |
| async_tree_cpu_io_mixed  | 706 ms                                                       | 716 ms: 1.01x slower                                                   |
| pickle_dict              | 31.7 us                                                      | 32.2 us: 1.01x slower                                                  |
| scimark_monte_carlo      | 72.4 ms                                                      | 73.5 ms: 1.02x slower                                                  |
| docutils                 | 2.89 sec                                                     | 2.94 sec: 1.02x slower                                                 |
| async_tree_memoization   | 553 ms                                                       | 563 ms: 1.02x slower                                                   |
| coroutines               | 23.0 ms                                                      | 23.4 ms: 1.02x slower                                                  |
| xml_etree_process        | 58.3 ms                                                      | 59.6 ms: 1.02x slower                                                  |
| sqlglot_parse            | 1.40 ms                                                      | 1.44 ms: 1.02x slower                                                  |
| xml_etree_iterparse      | 103 ms                                                       | 106 ms: 1.03x slower                                                   |
| sqlglot_transpile        | 1.80 ms                                                      | 1.85 ms: 1.03x slower                                                  |
| spectral_norm            | 91.6 ms                                                      | 94.1 ms: 1.03x slower                                                  |
| regex_dna                | 241 ms                                                       | 248 ms: 1.03x slower                                                   |
| json_loads               | 24.3 us                                                      | 25.0 us: 1.03x slower                                                  |
| deepcopy                 | 376 us                                                       | 388 us: 1.03x slower                                                   |
| crypto_pyaes             | 80.9 ms                                                      | 83.6 ms: 1.03x slower                                                  |
| sqlglot_normalize        | 117 ms                                                       | 121 ms: 1.03x slower                                                   |
| regex_effbot             | 3.47 ms                                                      | 3.59 ms: 1.03x slower                                                  |
| scimark_lu               | 101 ms                                                       | 105 ms: 1.04x slower                                                   |
| async_tree_io            | 1.06 sec                                                     | 1.10 sec: 1.04x slower                                                 |
| typing_runtime_protocols | 151 us                                                       | 158 us: 1.04x slower                                                   |
| mypy2                    | 368 ms                                                       | 385 ms: 1.05x slower                                                   |
| logging_silent           | 95.6 ns                                                      | 100 ns: 1.05x slower                                                   |
| json_dumps               | 10.2 ms                                                      | 10.7 ms: 1.05x slower                                                  |
| logging_format           | 7.37 us                                                      | 7.75 us: 1.05x slower                                                  |
| logging_simple           | 6.73 us                                                      | 7.09 us: 1.05x slower                                                  |
| pycparser                | 1.27 sec                                                     | 1.35 sec: 1.06x slower                                                 |
| mdp                      | 2.53 sec                                                     | 2.68 sec: 1.06x slower                                                 |
| sqlglot_optimize         | 57.8 ms                                                      | 61.2 ms: 1.06x slower                                                  |
| deepcopy_memo            | 37.4 us                                                      | 39.8 us: 1.06x slower                                                  |
| dulwich_log              | 65.3 ms                                                      | 69.5 ms: 1.06x slower                                                  |
| async_generators         | 385 ms                                                       | 410 ms: 1.06x slower                                                   |
| scimark_sparse_mat_mult  | 4.42 ms                                                      | 4.71 ms: 1.07x slower                                                  |
| meteor_contest           | 128 ms                                                       | 137 ms: 1.07x slower                                                   |
| nbody                    | 94.1 ms                                                      | 100 ms: 1.07x slower                                                   |
| pprint_safe_repr         | 823 ms                                                       | 882 ms: 1.07x slower                                                   |
| pprint_pformat           | 1.67 sec                                                     | 1.80 sec: 1.08x slower                                                 |
| python_startup           | 11.7 ms                                                      | 12.8 ms: 1.09x slower                                                  |
| regex_compile            | 146 ms                                                       | 159 ms: 1.09x slower                                                   |
| chaos                    | 62.9 ms                                                      | 70.2 ms: 1.12x slower                                                  |
| float                    | 78.5 ms                                                      | 88.0 ms: 1.12x slower                                                  |
| gc_traversal             | 3.54 ms                                                      | 3.97 ms: 1.12x slower                                                  |
| tomli_loads              | 2.20 sec                                                     | 2.49 sec: 1.13x slower                                                 |
| nqueens                  | 90.1 ms                                                      | 102 ms: 1.13x slower                                                   |
| richards_super           | 51.7 ms                                                      | 58.8 ms: 1.14x slower                                                  |
| unpickle_pure_python     | 207 us                                                       | 241 us: 1.17x slower                                                   |
| richards                 | 45.0 ms                                                      | 52.6 ms: 1.17x slower                                                  |
| pyflate                  | 447 ms                                                       | 528 ms: 1.18x slower                                                   |
| scimark_fft              | 304 ms                                                       | 362 ms: 1.19x slower                                                   |
| go                       | 150 ms                                                       | 179 ms: 1.19x slower                                                   |
| telco                    | 6.96 ms                                                      | 8.34 ms: 1.20x slower                                                  |
| mako                     | 9.94 ms                                                      | 12.0 ms: 1.20x slower                                                  |
| fannkuch                 | 350 ms                                                       | 437 ms: 1.25x slower                                                   |
| comprehensions           | 21.9 us                                                      | 28.4 us: 1.30x slower                                                  |
| scimark_sor              | 110 ms                                                       | 147 ms: 1.33x slower                                                   |
| deltablue                | 3.29 ms                                                      | 4.81 ms: 1.46x slower                                                  |
| hexiom                   | 5.96 ms                                                      | 8.90 ms: 1.49x slower                                                  |
| Geometric mean           | (ref)                                                        | 1.06x slower                                                           |

Benchmark hidden because not significant (10): json, bench_thread_pool, regex_v8, xml_etree_generate, generators, pickle, xml_etree_parse, pickle_list, unpickle_list, tornado_http
Ignored benchmarks (2) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: 2to3, dask


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.03x
- 95% likely to have a slowdown of 1.03x
- 99% likely to have a slowdown of 1.02x
