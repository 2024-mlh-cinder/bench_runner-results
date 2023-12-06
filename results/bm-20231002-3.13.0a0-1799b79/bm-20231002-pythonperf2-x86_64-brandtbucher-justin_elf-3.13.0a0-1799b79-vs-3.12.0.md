
# Results vs. 3.12.0

- fork: brandtbucher
- ref: justin_elf
- machine: linux-x86_64
- commit hash: 1799b79
- commit date: 2023-10-02
- overall geometric mean: 1.04x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.02x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231002-pythonperf2-x86_64-brandtbucher-justin_elf-3.13.0a0-1799b79 |
|----------------|:------------------------------------------------------------:|:-----------------------------------------------------------------------:|
| docutils       | 2.89 sec                                                     | 2.92 sec: 1.01x slower                                                  |
| Geometric mean | (ref)                                                        | 1.00x slower                                                            |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231002-pythonperf2-x86_64-brandtbucher-justin_elf-3.13.0a0-1799b79 |
|----------------|:------------------------------------------------------------:|:-----------------------------------------------------------------------:|
| pidigits       | 264 ms                                                       | 265 ms: 1.00x slower                                                    |
| float          | 78.5 ms                                                      | 82.3 ms: 1.05x slower                                                   |
| nbody          | 94.1 ms                                                      | 110 ms: 1.17x slower                                                    |
| Geometric mean | (ref)                                                        | 1.07x slower                                                            |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231002-pythonperf2-x86_64-brandtbucher-justin_elf-3.13.0a0-1799b79 |
|----------------|:------------------------------------------------------------:|:-----------------------------------------------------------------------:|
| regex_dna      | 241 ms                                                       | 244 ms: 1.01x slower                                                    |
| regex_effbot   | 3.47 ms                                                      | 3.56 ms: 1.03x slower                                                   |
| regex_v8       | 25.0 ms                                                      | 25.8 ms: 1.03x slower                                                   |
| regex_compile  | 146 ms                                                       | 155 ms: 1.06x slower                                                    |
| Geometric mean | (ref)                                                        | 1.03x slower                                                            |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231002-pythonperf2-x86_64-brandtbucher-justin_elf-3.13.0a0-1799b79 |
|----------------------|:------------------------------------------------------------:|:-----------------------------------------------------------------------:|
| unpickle_list        | 4.77 us                                                      | 4.62 us: 1.03x faster                                                   |
| pickle_pure_python   | 323 us                                                       | 315 us: 1.02x faster                                                    |
| unpickle             | 14.8 us                                                      | 14.5 us: 1.02x faster                                                   |
| xml_etree_process    | 58.3 ms                                                      | 59.1 ms: 1.01x slower                                                   |
| pickle_list          | 4.39 us                                                      | 4.45 us: 1.01x slower                                                   |
| json_loads           | 24.3 us                                                      | 24.7 us: 1.02x slower                                                   |
| xml_etree_parse      | 146 ms                                                       | 149 ms: 1.02x slower                                                    |
| json_dumps           | 10.2 ms                                                      | 10.5 ms: 1.02x slower                                                   |
| xml_etree_iterparse  | 103 ms                                                       | 106 ms: 1.02x slower                                                    |
| tomli_loads          | 2.20 sec                                                     | 2.27 sec: 1.03x slower                                                  |
| pickle_dict          | 31.7 us                                                      | 33.3 us: 1.05x slower                                                   |
| unpickle_pure_python | 207 us                                                       | 226 us: 1.09x slower                                                    |
| Geometric mean       | (ref)                                                        | 1.01x slower                                                            |

Benchmark hidden because not significant (2): xml_etree_generate, pickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231002-pythonperf2-x86_64-brandtbucher-justin_elf-3.13.0a0-1799b79 |
|------------------------|:------------------------------------------------------------:|:-----------------------------------------------------------------------:|
| python_startup_no_site | 8.70 ms                                                      | 8.72 ms: 1.00x slower                                                   |
| python_startup         | 11.7 ms                                                      | 12.7 ms: 1.08x slower                                                   |
| Geometric mean         | (ref)                                                        | 1.04x slower                                                            |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231002-pythonperf2-x86_64-brandtbucher-justin_elf-3.13.0a0-1799b79 |
|-----------|:------------------------------------------------------------:|:-----------------------------------------------------------------------:|
| mako      | 9.94 ms                                                      | 10.3 ms: 1.04x slower                                                   |

All benchmarks:
===============

| Benchmark                | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231002-pythonperf2-x86_64-brandtbucher-justin_elf-3.13.0a0-1799b79 |
|--------------------------|:------------------------------------------------------------:|:-----------------------------------------------------------------------:|
| coverage                 | 89.6 ms                                                      | 79.2 ms: 1.13x faster                                                   |
| bench_mp_pool            | 5.34 ms                                                      | 4.88 ms: 1.09x faster                                                   |
| crypto_pyaes             | 80.9 ms                                                      | 76.4 ms: 1.06x faster                                                   |
| raytrace                 | 302 ms                                                       | 286 ms: 1.05x faster                                                    |
| deepcopy_reduce          | 3.46 us                                                      | 3.33 us: 1.04x faster                                                   |
| unpickle_list            | 4.77 us                                                      | 4.62 us: 1.03x faster                                                   |
| async_tree_none          | 459 ms                                                       | 445 ms: 1.03x faster                                                    |
| asyncio_tcp              | 381 ms                                                       | 370 ms: 1.03x faster                                                    |
| scimark_sparse_mat_mult  | 4.42 ms                                                      | 4.31 ms: 1.03x faster                                                   |
| unpack_sequence          | 53.3 ns                                                      | 52.0 ns: 1.03x faster                                                   |
| create_gc_cycles         | 1.67 ms                                                      | 1.63 ms: 1.02x faster                                                   |
| pickle_pure_python       | 323 us                                                       | 315 us: 1.02x faster                                                    |
| unpickle                 | 14.8 us                                                      | 14.5 us: 1.02x faster                                                   |
| generators               | 36.7 ms                                                      | 36.1 ms: 1.02x faster                                                   |
| pathlib                  | 19.8 ms                                                      | 19.7 ms: 1.00x faster                                                   |
| python_startup_no_site   | 8.70 ms                                                      | 8.72 ms: 1.00x slower                                                   |
| pidigits                 | 264 ms                                                       | 265 ms: 1.00x slower                                                    |
| sqlite_synth             | 2.70 us                                                      | 2.71 us: 1.00x slower                                                   |
| asyncio_tcp_ssl          | 1.58 sec                                                     | 1.59 sec: 1.01x slower                                                  |
| async_tree_memoization   | 553 ms                                                       | 558 ms: 1.01x slower                                                    |
| logging_simple           | 6.73 us                                                      | 6.80 us: 1.01x slower                                                   |
| spectral_norm            | 91.6 ms                                                      | 92.7 ms: 1.01x slower                                                   |
| docutils                 | 2.89 sec                                                     | 2.92 sec: 1.01x slower                                                  |
| regex_dna                | 241 ms                                                       | 244 ms: 1.01x slower                                                    |
| deepcopy                 | 376 us                                                       | 380 us: 1.01x slower                                                    |
| xml_etree_process        | 58.3 ms                                                      | 59.1 ms: 1.01x slower                                                   |
| pickle_list              | 4.39 us                                                      | 4.45 us: 1.01x slower                                                   |
| json_loads               | 24.3 us                                                      | 24.7 us: 1.02x slower                                                   |
| sqlglot_parse            | 1.40 ms                                                      | 1.43 ms: 1.02x slower                                                   |
| xml_etree_parse          | 146 ms                                                       | 149 ms: 1.02x slower                                                    |
| logging_format           | 7.37 us                                                      | 7.53 us: 1.02x slower                                                   |
| logging_silent           | 95.6 ns                                                      | 97.8 ns: 1.02x slower                                                   |
| json_dumps               | 10.2 ms                                                      | 10.5 ms: 1.02x slower                                                   |
| sqlglot_transpile        | 1.80 ms                                                      | 1.84 ms: 1.02x slower                                                   |
| xml_etree_iterparse      | 103 ms                                                       | 106 ms: 1.02x slower                                                    |
| regex_effbot             | 3.47 ms                                                      | 3.56 ms: 1.03x slower                                                   |
| coroutines               | 23.0 ms                                                      | 23.6 ms: 1.03x slower                                                   |
| bench_thread_pool        | 980 us                                                       | 1.01 ms: 1.03x slower                                                   |
| mdp                      | 2.53 sec                                                     | 2.61 sec: 1.03x slower                                                  |
| sqlglot_normalize        | 117 ms                                                       | 121 ms: 1.03x slower                                                    |
| regex_v8                 | 25.0 ms                                                      | 25.8 ms: 1.03x slower                                                   |
| tomli_loads              | 2.20 sec                                                     | 2.27 sec: 1.03x slower                                                  |
| async_tree_io            | 1.06 sec                                                     | 1.09 sec: 1.03x slower                                                  |
| deepcopy_memo            | 37.4 us                                                      | 38.8 us: 1.04x slower                                                   |
| mako                     | 9.94 ms                                                      | 10.3 ms: 1.04x slower                                                   |
| mypy2                    | 368 ms                                                       | 383 ms: 1.04x slower                                                    |
| scimark_monte_carlo      | 72.4 ms                                                      | 75.5 ms: 1.04x slower                                                   |
| typing_runtime_protocols | 151 us                                                       | 158 us: 1.05x slower                                                    |
| float                    | 78.5 ms                                                      | 82.3 ms: 1.05x slower                                                   |
| pickle_dict              | 31.7 us                                                      | 33.3 us: 1.05x slower                                                   |
| meteor_contest           | 128 ms                                                       | 134 ms: 1.05x slower                                                    |
| sqlglot_optimize         | 57.8 ms                                                      | 60.9 ms: 1.05x slower                                                   |
| pycparser                | 1.27 sec                                                     | 1.35 sec: 1.06x slower                                                  |
| regex_compile            | 146 ms                                                       | 155 ms: 1.06x slower                                                    |
| dulwich_log              | 65.3 ms                                                      | 69.4 ms: 1.06x slower                                                   |
| pprint_safe_repr         | 823 ms                                                       | 875 ms: 1.06x slower                                                    |
| async_generators         | 385 ms                                                       | 410 ms: 1.06x slower                                                    |
| scimark_lu               | 101 ms                                                       | 107 ms: 1.07x slower                                                    |
| pprint_pformat           | 1.67 sec                                                     | 1.79 sec: 1.07x slower                                                  |
| python_startup           | 11.7 ms                                                      | 12.7 ms: 1.08x slower                                                   |
| unpickle_pure_python     | 207 us                                                       | 226 us: 1.09x slower                                                    |
| gc_traversal             | 3.54 ms                                                      | 3.94 ms: 1.11x slower                                                   |
| richards_super           | 51.7 ms                                                      | 58.4 ms: 1.13x slower                                                   |
| nqueens                  | 90.1 ms                                                      | 102 ms: 1.14x slower                                                    |
| richards                 | 45.0 ms                                                      | 52.1 ms: 1.16x slower                                                   |
| deltablue                | 3.29 ms                                                      | 3.82 ms: 1.16x slower                                                   |
| chaos                    | 62.9 ms                                                      | 73.5 ms: 1.17x slower                                                   |
| fannkuch                 | 350 ms                                                       | 410 ms: 1.17x slower                                                    |
| nbody                    | 94.1 ms                                                      | 110 ms: 1.17x slower                                                    |
| scimark_fft              | 304 ms                                                       | 358 ms: 1.18x slower                                                    |
| go                       | 150 ms                                                       | 177 ms: 1.18x slower                                                    |
| telco                    | 6.96 ms                                                      | 8.26 ms: 1.19x slower                                                   |
| pyflate                  | 447 ms                                                       | 532 ms: 1.19x slower                                                    |
| comprehensions           | 21.9 us                                                      | 26.2 us: 1.20x slower                                                   |
| scimark_sor              | 110 ms                                                       | 146 ms: 1.32x slower                                                    |
| hexiom                   | 5.96 ms                                                      | 7.93 ms: 1.33x slower                                                   |
| Geometric mean           | (ref)                                                        | 1.04x slower                                                            |

Benchmark hidden because not significant (5): tornado_http, xml_etree_generate, json, pickle, async_tree_cpu_io_mixed
Ignored benchmarks (2) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: 2to3, dask


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.02x
- 95% likely to have a slowdown of 1.02x
- 99% likely to have a slowdown of 1.02x
