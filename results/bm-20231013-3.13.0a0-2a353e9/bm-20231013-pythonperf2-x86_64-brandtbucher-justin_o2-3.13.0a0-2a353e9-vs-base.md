
# Results vs. base

- fork: brandtbucher
- ref: justin_o2
- machine: linux-x86_64
- commit hash: 2a353e9
- commit date: 2023-10-13
- overall geometric mean: 1.04x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.01x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231010-pythonperf2-x86_64-python-982f1b7d6dc2f13b9607-3.13.0a0-982f1b7 | bm-20231013-pythonperf2-x86_64-brandtbucher-justin_o2-3.13.0a0-2a353e9 |
|----------------|:---------------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| docutils       | 2.89 sec                                                                    | 2.94 sec: 1.02x slower                                                 |
| tornado_http   | 122 ms                                                                      | 124 ms: 1.02x slower                                                   |
| Geometric mean | (ref)                                                                       | 1.02x slower                                                           |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231010-pythonperf2-x86_64-python-982f1b7d6dc2f13b9607-3.13.0a0-982f1b7 | bm-20231013-pythonperf2-x86_64-brandtbucher-justin_o2-3.13.0a0-2a353e9 |
|----------------|:---------------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| pidigits       | 266 ms                                                                      | 265 ms: 1.00x faster                                                   |
| float          | 81.4 ms                                                                     | 89.3 ms: 1.10x slower                                                  |
| nbody          | 88.9 ms                                                                     | 102 ms: 1.15x slower                                                   |
| Geometric mean | (ref)                                                                       | 1.08x slower                                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231010-pythonperf2-x86_64-python-982f1b7d6dc2f13b9607-3.13.0a0-982f1b7 | bm-20231013-pythonperf2-x86_64-brandtbucher-justin_o2-3.13.0a0-2a353e9 |
|----------------|:---------------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| regex_dna      | 246 ms                                                                      | 245 ms: 1.01x faster                                                   |
| regex_v8       | 25.0 ms                                                                     | 25.2 ms: 1.01x slower                                                  |
| regex_effbot   | 3.44 ms                                                                     | 3.57 ms: 1.04x slower                                                  |
| regex_compile  | 149 ms                                                                      | 160 ms: 1.07x slower                                                   |
| Geometric mean | (ref)                                                                       | 1.03x slower                                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231010-pythonperf2-x86_64-python-982f1b7d6dc2f13b9607-3.13.0a0-982f1b7 | bm-20231013-pythonperf2-x86_64-brandtbucher-justin_o2-3.13.0a0-2a353e9 |
|----------------------|:---------------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| unpickle             | 14.9 us                                                                     | 14.7 us: 1.01x faster                                                  |
| json_loads           | 24.8 us                                                                     | 24.5 us: 1.01x faster                                                  |
| json_dumps           | 10.6 ms                                                                     | 10.6 ms: 1.01x faster                                                  |
| unpickle_list        | 4.69 us                                                                     | 4.75 us: 1.01x slower                                                  |
| xml_etree_generate   | 86.2 ms                                                                     | 87.4 ms: 1.01x slower                                                  |
| xml_etree_iterparse  | 106 ms                                                                      | 108 ms: 1.01x slower                                                   |
| pickle_dict          | 32.5 us                                                                     | 33.0 us: 1.01x slower                                                  |
| xml_etree_parse      | 150 ms                                                                      | 152 ms: 1.02x slower                                                   |
| pickle_pure_python   | 310 us                                                                      | 319 us: 1.03x slower                                                   |
| tomli_loads          | 2.32 sec                                                                    | 2.46 sec: 1.06x slower                                                 |
| unpickle_pure_python | 215 us                                                                      | 229 us: 1.07x slower                                                   |
| Geometric mean       | (ref)                                                                       | 1.01x slower                                                           |

Benchmark hidden because not significant (3): pickle_list, pickle, xml_etree_process

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231010-pythonperf2-x86_64-python-982f1b7d6dc2f13b9607-3.13.0a0-982f1b7 | bm-20231013-pythonperf2-x86_64-brandtbucher-justin_o2-3.13.0a0-2a353e9 |
|------------------------|:---------------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| python_startup         | 12.6 ms                                                                     | 12.7 ms: 1.00x slower                                                  |
| python_startup_no_site | 8.69 ms                                                                     | 8.72 ms: 1.00x slower                                                  |
| Geometric mean         | (ref)                                                                       | 1.00x slower                                                           |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231010-pythonperf2-x86_64-python-982f1b7d6dc2f13b9607-3.13.0a0-982f1b7 | bm-20231013-pythonperf2-x86_64-brandtbucher-justin_o2-3.13.0a0-2a353e9 |
|-----------|:---------------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| mako      | 10.3 ms                                                                     | 12.1 ms: 1.17x slower                                                  |

All benchmarks:
===============

| Benchmark                | bm-20231010-pythonperf2-x86_64-python-982f1b7d6dc2f13b9607-3.13.0a0-982f1b7 | bm-20231013-pythonperf2-x86_64-brandtbucher-justin_o2-3.13.0a0-2a353e9 |
|--------------------------|:---------------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| unpack_sequence          | 52.3 ns                                                                     | 48.3 ns: 1.08x faster                                                  |
| create_gc_cycles         | 1.70 ms                                                                     | 1.61 ms: 1.06x faster                                                  |
| richards                 | 55.2 ms                                                                     | 52.3 ms: 1.06x faster                                                  |
| richards_super           | 61.8 ms                                                                     | 58.4 ms: 1.06x faster                                                  |
| unpickle                 | 14.9 us                                                                     | 14.7 us: 1.01x faster                                                  |
| gc_traversal             | 4.00 ms                                                                     | 3.95 ms: 1.01x faster                                                  |
| json_loads               | 24.8 us                                                                     | 24.5 us: 1.01x faster                                                  |
| asyncio_tcp              | 372 ms                                                                      | 370 ms: 1.01x faster                                                   |
| json_dumps               | 10.6 ms                                                                     | 10.6 ms: 1.01x faster                                                  |
| regex_dna                | 246 ms                                                                      | 245 ms: 1.01x faster                                                   |
| pyflate                  | 533 ms                                                                      | 530 ms: 1.00x faster                                                   |
| pidigits                 | 266 ms                                                                      | 265 ms: 1.00x faster                                                   |
| asyncio_tcp_ssl          | 1.58 sec                                                                    | 1.58 sec: 1.00x slower                                                 |
| python_startup           | 12.6 ms                                                                     | 12.7 ms: 1.00x slower                                                  |
| python_startup_no_site   | 8.69 ms                                                                     | 8.72 ms: 1.00x slower                                                  |
| regex_v8                 | 25.0 ms                                                                     | 25.2 ms: 1.01x slower                                                  |
| deepcopy_reduce          | 3.30 us                                                                     | 3.33 us: 1.01x slower                                                  |
| sqlite_synth             | 2.68 us                                                                     | 2.71 us: 1.01x slower                                                  |
| unpickle_list            | 4.69 us                                                                     | 4.75 us: 1.01x slower                                                  |
| xml_etree_generate       | 86.2 ms                                                                     | 87.4 ms: 1.01x slower                                                  |
| xml_etree_iterparse      | 106 ms                                                                      | 108 ms: 1.01x slower                                                   |
| logging_format           | 7.53 us                                                                     | 7.64 us: 1.01x slower                                                  |
| pickle_dict              | 32.5 us                                                                     | 33.0 us: 1.01x slower                                                  |
| sqlglot_parse            | 1.41 ms                                                                     | 1.43 ms: 1.01x slower                                                  |
| sqlglot_transpile        | 1.82 ms                                                                     | 1.85 ms: 1.02x slower                                                  |
| xml_etree_parse          | 150 ms                                                                      | 152 ms: 1.02x slower                                                   |
| pathlib                  | 19.9 ms                                                                     | 20.2 ms: 1.02x slower                                                  |
| async_tree_cpu_io_mixed  | 704 ms                                                                      | 716 ms: 1.02x slower                                                   |
| docutils                 | 2.89 sec                                                                    | 2.94 sec: 1.02x slower                                                 |
| async_tree_io            | 1.08 sec                                                                    | 1.10 sec: 1.02x slower                                                 |
| async_tree_memoization   | 552 ms                                                                      | 563 ms: 1.02x slower                                                   |
| go                       | 172 ms                                                                      | 176 ms: 1.02x slower                                                   |
| tornado_http             | 122 ms                                                                      | 124 ms: 1.02x slower                                                   |
| logging_silent           | 97.8 ns                                                                     | 99.9 ns: 1.02x slower                                                  |
| typing_runtime_protocols | 151 us                                                                      | 155 us: 1.02x slower                                                   |
| telco                    | 8.10 ms                                                                     | 8.30 ms: 1.03x slower                                                  |
| async_tree_none          | 438 ms                                                                      | 449 ms: 1.03x slower                                                   |
| mdp                      | 2.54 sec                                                                    | 2.61 sec: 1.03x slower                                                 |
| spectral_norm            | 91.4 ms                                                                     | 94.0 ms: 1.03x slower                                                  |
| sqlglot_optimize         | 58.5 ms                                                                     | 60.2 ms: 1.03x slower                                                  |
| pickle_pure_python       | 310 us                                                                      | 319 us: 1.03x slower                                                   |
| sqlglot_normalize        | 115 ms                                                                      | 119 ms: 1.03x slower                                                   |
| mypy2                    | 372 ms                                                                      | 384 ms: 1.03x slower                                                   |
| scimark_sor              | 146 ms                                                                      | 151 ms: 1.04x slower                                                   |
| generators               | 35.1 ms                                                                     | 36.4 ms: 1.04x slower                                                  |
| regex_effbot             | 3.44 ms                                                                     | 3.57 ms: 1.04x slower                                                  |
| scimark_lu               | 100 ms                                                                      | 105 ms: 1.04x slower                                                   |
| async_generators         | 395 ms                                                                      | 418 ms: 1.06x slower                                                   |
| tomli_loads              | 2.32 sec                                                                    | 2.46 sec: 1.06x slower                                                 |
| unpickle_pure_python     | 215 us                                                                      | 229 us: 1.07x slower                                                   |
| regex_compile            | 149 ms                                                                      | 160 ms: 1.07x slower                                                   |
| raytrace                 | 272 ms                                                                      | 292 ms: 1.07x slower                                                   |
| meteor_contest           | 130 ms                                                                      | 139 ms: 1.08x slower                                                   |
| deepcopy_memo            | 37.3 us                                                                     | 40.2 us: 1.08x slower                                                  |
| coverage                 | 79.8 ms                                                                     | 86.1 ms: 1.08x slower                                                  |
| pprint_pformat           | 1.65 sec                                                                    | 1.79 sec: 1.09x slower                                                 |
| pprint_safe_repr         | 807 ms                                                                      | 878 ms: 1.09x slower                                                   |
| float                    | 81.4 ms                                                                     | 89.3 ms: 1.10x slower                                                  |
| crypto_pyaes             | 75.0 ms                                                                     | 83.6 ms: 1.11x slower                                                  |
| chaos                    | 62.6 ms                                                                     | 70.3 ms: 1.12x slower                                                  |
| scimark_monte_carlo      | 66.4 ms                                                                     | 74.9 ms: 1.13x slower                                                  |
| nbody                    | 88.9 ms                                                                     | 102 ms: 1.15x slower                                                   |
| fannkuch                 | 383 ms                                                                      | 440 ms: 1.15x slower                                                   |
| scimark_sparse_mat_mult  | 4.07 ms                                                                     | 4.75 ms: 1.17x slower                                                  |
| nqueens                  | 88.4 ms                                                                     | 103 ms: 1.17x slower                                                   |
| mako                     | 10.3 ms                                                                     | 12.1 ms: 1.17x slower                                                  |
| scimark_fft              | 296 ms                                                                      | 356 ms: 1.20x slower                                                   |
| comprehensions           | 22.1 us                                                                     | 28.7 us: 1.30x slower                                                  |
| deltablue                | 3.74 ms                                                                     | 4.89 ms: 1.31x slower                                                  |
| hexiom                   | 6.44 ms                                                                     | 8.97 ms: 1.39x slower                                                  |
| Geometric mean           | (ref)                                                                       | 1.04x slower                                                           |

Benchmark hidden because not significant (11): pickle_list, logging_simple, dulwich_log, pycparser, pickle, bench_mp_pool, deepcopy, json, coroutines, xml_etree_process, bench_thread_pool


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.02x
- 95% likely to have a slowdown of 1.02x
- 99% likely to have a slowdown of 1.01x
