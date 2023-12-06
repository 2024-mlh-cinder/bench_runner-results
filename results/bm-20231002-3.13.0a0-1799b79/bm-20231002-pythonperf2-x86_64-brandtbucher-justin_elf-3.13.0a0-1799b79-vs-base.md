
# Results vs. base

- fork: brandtbucher
- ref: justin_elf
- machine: linux-x86_64
- commit hash: 1799b79
- commit date: 2023-10-02
- overall geometric mean: 1.03x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.01x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-4596c76d1a7650fd4650-3.13.0a0-4596c76 | bm-20231002-pythonperf2-x86_64-brandtbucher-justin_elf-3.13.0a0-1799b79 |
|----------------|:---------------------------------------------------------------------------:|:-----------------------------------------------------------------------:|
| docutils       | 2.88 sec                                                                    | 2.92 sec: 1.02x slower                                                  |
| Geometric mean | (ref)                                                                       | 1.01x slower                                                            |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-4596c76d1a7650fd4650-3.13.0a0-4596c76 | bm-20231002-pythonperf2-x86_64-brandtbucher-justin_elf-3.13.0a0-1799b79 |
|----------------|:---------------------------------------------------------------------------:|:-----------------------------------------------------------------------:|
| pidigits       | 265 ms                                                                      | 265 ms: 1.00x faster                                                    |
| float          | 80.1 ms                                                                     | 82.3 ms: 1.03x slower                                                   |
| nbody          | 89.1 ms                                                                     | 110 ms: 1.24x slower                                                    |
| Geometric mean | (ref)                                                                       | 1.08x slower                                                            |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-4596c76d1a7650fd4650-3.13.0a0-4596c76 | bm-20231002-pythonperf2-x86_64-brandtbucher-justin_elf-3.13.0a0-1799b79 |
|----------------|:---------------------------------------------------------------------------:|:-----------------------------------------------------------------------:|
| regex_v8       | 26.0 ms                                                                     | 25.8 ms: 1.01x faster                                                   |
| regex_effbot   | 3.51 ms                                                                     | 3.56 ms: 1.02x slower                                                   |
| regex_dna      | 237 ms                                                                      | 244 ms: 1.03x slower                                                    |
| regex_compile  | 150 ms                                                                      | 155 ms: 1.03x slower                                                    |
| Geometric mean | (ref)                                                                       | 1.02x slower                                                            |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf2-x86_64-python-4596c76d1a7650fd4650-3.13.0a0-4596c76 | bm-20231002-pythonperf2-x86_64-brandtbucher-justin_elf-3.13.0a0-1799b79 |
|----------------------|:---------------------------------------------------------------------------:|:-----------------------------------------------------------------------:|
| xml_etree_generate   | 87.7 ms                                                                     | 86.1 ms: 1.02x faster                                                   |
| json_dumps           | 10.6 ms                                                                     | 10.5 ms: 1.02x faster                                                   |
| xml_etree_iterparse  | 107 ms                                                                      | 106 ms: 1.02x faster                                                    |
| pickle_pure_python   | 320 us                                                                      | 315 us: 1.02x faster                                                    |
| xml_etree_process    | 59.8 ms                                                                     | 59.1 ms: 1.01x faster                                                   |
| unpickle_list        | 4.60 us                                                                     | 4.62 us: 1.00x slower                                                   |
| unpickle_pure_python | 225 us                                                                      | 226 us: 1.00x slower                                                    |
| json_loads           | 24.6 us                                                                     | 24.7 us: 1.01x slower                                                   |
| pickle               | 9.91 us                                                                     | 10.1 us: 1.02x slower                                                   |
| unpickle             | 14.2 us                                                                     | 14.5 us: 1.02x slower                                                   |
| pickle_dict          | 32.0 us                                                                     | 33.3 us: 1.04x slower                                                   |
| pickle_list          | 4.17 us                                                                     | 4.45 us: 1.07x slower                                                   |
| Geometric mean       | (ref)                                                                       | 1.01x slower                                                            |

Benchmark hidden because not significant (2): tomli_loads, xml_etree_parse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf2-x86_64-python-4596c76d1a7650fd4650-3.13.0a0-4596c76 | bm-20231002-pythonperf2-x86_64-brandtbucher-justin_elf-3.13.0a0-1799b79 |
|------------------------|:---------------------------------------------------------------------------:|:-----------------------------------------------------------------------:|
| python_startup_no_site | 8.69 ms                                                                     | 8.72 ms: 1.00x slower                                                   |
| python_startup         | 12.6 ms                                                                     | 12.7 ms: 1.00x slower                                                   |
| Geometric mean         | (ref)                                                                       | 1.00x slower                                                            |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-pythonperf2-x86_64-python-4596c76d1a7650fd4650-3.13.0a0-4596c76 | bm-20231002-pythonperf2-x86_64-brandtbucher-justin_elf-3.13.0a0-1799b79 |
|-----------|:---------------------------------------------------------------------------:|:-----------------------------------------------------------------------:|
| mako      | 10.4 ms                                                                     | 10.3 ms: 1.01x faster                                                   |

All benchmarks:
===============

| Benchmark                | bm-20231002-pythonperf2-x86_64-python-4596c76d1a7650fd4650-3.13.0a0-4596c76 | bm-20231002-pythonperf2-x86_64-brandtbucher-justin_elf-3.13.0a0-1799b79 |
|--------------------------|:---------------------------------------------------------------------------:|:-----------------------------------------------------------------------:|
| gc_traversal             | 4.21 ms                                                                     | 3.94 ms: 1.07x faster                                                   |
| coverage                 | 84.5 ms                                                                     | 79.2 ms: 1.07x faster                                                   |
| richards                 | 54.8 ms                                                                     | 52.1 ms: 1.05x faster                                                   |
| richards_super           | 61.4 ms                                                                     | 58.4 ms: 1.05x faster                                                   |
| create_gc_cycles         | 1.70 ms                                                                     | 1.63 ms: 1.04x faster                                                   |
| xml_etree_generate       | 87.7 ms                                                                     | 86.1 ms: 1.02x faster                                                   |
| json_dumps               | 10.6 ms                                                                     | 10.5 ms: 1.02x faster                                                   |
| xml_etree_iterparse      | 107 ms                                                                      | 106 ms: 1.02x faster                                                    |
| pickle_pure_python       | 320 us                                                                      | 315 us: 1.02x faster                                                    |
| xml_etree_process        | 59.8 ms                                                                     | 59.1 ms: 1.01x faster                                                   |
| mako                     | 10.4 ms                                                                     | 10.3 ms: 1.01x faster                                                   |
| regex_v8                 | 26.0 ms                                                                     | 25.8 ms: 1.01x faster                                                   |
| scimark_sor              | 147 ms                                                                      | 146 ms: 1.01x faster                                                    |
| deepcopy_reduce          | 3.36 us                                                                     | 3.33 us: 1.01x faster                                                   |
| logging_simple           | 6.85 us                                                                     | 6.80 us: 1.01x faster                                                   |
| pidigits                 | 265 ms                                                                      | 265 ms: 1.00x faster                                                    |
| unpickle_list            | 4.60 us                                                                     | 4.62 us: 1.00x slower                                                   |
| python_startup_no_site   | 8.69 ms                                                                     | 8.72 ms: 1.00x slower                                                   |
| spectral_norm            | 92.3 ms                                                                     | 92.7 ms: 1.00x slower                                                   |
| python_startup           | 12.6 ms                                                                     | 12.7 ms: 1.00x slower                                                   |
| unpickle_pure_python     | 225 us                                                                      | 226 us: 1.00x slower                                                    |
| asyncio_tcp_ssl          | 1.58 sec                                                                    | 1.59 sec: 1.00x slower                                                  |
| json_loads               | 24.6 us                                                                     | 24.7 us: 1.01x slower                                                   |
| deepcopy                 | 378 us                                                                      | 380 us: 1.01x slower                                                    |
| asyncio_tcp              | 368 ms                                                                      | 370 ms: 1.01x slower                                                    |
| json                     | 5.11 ms                                                                     | 5.14 ms: 1.01x slower                                                   |
| sqlite_synth             | 2.69 us                                                                     | 2.71 us: 1.01x slower                                                   |
| unpack_sequence          | 51.6 ns                                                                     | 52.0 ns: 1.01x slower                                                   |
| pathlib                  | 19.6 ms                                                                     | 19.7 ms: 1.01x slower                                                   |
| scimark_sparse_mat_mult  | 4.27 ms                                                                     | 4.31 ms: 1.01x slower                                                   |
| async_tree_cpu_io_mixed  | 702 ms                                                                      | 711 ms: 1.01x slower                                                    |
| async_tree_memoization   | 551 ms                                                                      | 558 ms: 1.01x slower                                                    |
| docutils                 | 2.88 sec                                                                    | 2.92 sec: 1.02x slower                                                  |
| regex_effbot             | 3.51 ms                                                                     | 3.56 ms: 1.02x slower                                                   |
| telco                    | 8.12 ms                                                                     | 8.26 ms: 1.02x slower                                                   |
| fannkuch                 | 403 ms                                                                      | 410 ms: 1.02x slower                                                    |
| sqlglot_transpile        | 1.81 ms                                                                     | 1.84 ms: 1.02x slower                                                   |
| pickle                   | 9.91 us                                                                     | 10.1 us: 1.02x slower                                                   |
| sqlglot_parse            | 1.40 ms                                                                     | 1.43 ms: 1.02x slower                                                   |
| coroutines               | 23.2 ms                                                                     | 23.6 ms: 1.02x slower                                                   |
| unpickle                 | 14.2 us                                                                     | 14.5 us: 1.02x slower                                                   |
| logging_silent           | 95.8 ns                                                                     | 97.8 ns: 1.02x slower                                                   |
| deepcopy_memo            | 38.0 us                                                                     | 38.8 us: 1.02x slower                                                   |
| async_tree_none          | 435 ms                                                                      | 445 ms: 1.02x slower                                                    |
| float                    | 80.1 ms                                                                     | 82.3 ms: 1.03x slower                                                   |
| mypy2                    | 373 ms                                                                      | 383 ms: 1.03x slower                                                    |
| regex_dna                | 237 ms                                                                      | 244 ms: 1.03x slower                                                    |
| regex_compile            | 150 ms                                                                      | 155 ms: 1.03x slower                                                    |
| typing_runtime_protocols | 153 us                                                                      | 158 us: 1.03x slower                                                    |
| mdp                      | 2.51 sec                                                                    | 2.61 sec: 1.04x slower                                                  |
| generators               | 34.8 ms                                                                     | 36.1 ms: 1.04x slower                                                   |
| pycparser                | 1.30 sec                                                                    | 1.35 sec: 1.04x slower                                                  |
| pyflate                  | 512 ms                                                                      | 532 ms: 1.04x slower                                                    |
| go                       | 171 ms                                                                      | 177 ms: 1.04x slower                                                    |
| pickle_dict              | 32.0 us                                                                     | 33.3 us: 1.04x slower                                                   |
| deltablue                | 3.66 ms                                                                     | 3.82 ms: 1.04x slower                                                   |
| sqlglot_optimize         | 58.4 ms                                                                     | 60.9 ms: 1.04x slower                                                   |
| meteor_contest           | 128 ms                                                                      | 134 ms: 1.05x slower                                                    |
| bench_thread_pool        | 959 us                                                                      | 1.01 ms: 1.05x slower                                                   |
| sqlglot_normalize        | 114 ms                                                                      | 121 ms: 1.05x slower                                                    |
| async_generators         | 387 ms                                                                      | 410 ms: 1.06x slower                                                    |
| scimark_lu               | 101 ms                                                                      | 107 ms: 1.06x slower                                                    |
| bench_mp_pool            | 4.59 ms                                                                     | 4.88 ms: 1.06x slower                                                   |
| raytrace                 | 269 ms                                                                      | 286 ms: 1.07x slower                                                    |
| pickle_list              | 4.17 us                                                                     | 4.45 us: 1.07x slower                                                   |
| crypto_pyaes             | 71.3 ms                                                                     | 76.4 ms: 1.07x slower                                                   |
| pprint_safe_repr         | 811 ms                                                                      | 875 ms: 1.08x slower                                                    |
| pprint_pformat           | 1.65 sec                                                                    | 1.79 sec: 1.08x slower                                                  |
| scimark_monte_carlo      | 66.1 ms                                                                     | 75.5 ms: 1.14x slower                                                   |
| nqueens                  | 88.6 ms                                                                     | 102 ms: 1.16x slower                                                    |
| chaos                    | 62.7 ms                                                                     | 73.5 ms: 1.17x slower                                                   |
| scimark_fft              | 301 ms                                                                      | 358 ms: 1.19x slower                                                    |
| comprehensions           | 21.7 us                                                                     | 26.2 us: 1.21x slower                                                   |
| hexiom                   | 6.47 ms                                                                     | 7.93 ms: 1.23x slower                                                   |
| nbody                    | 89.1 ms                                                                     | 110 ms: 1.24x slower                                                    |
| Geometric mean           | (ref)                                                                       | 1.03x slower                                                            |

Benchmark hidden because not significant (6): logging_format, tornado_http, dulwich_log, tomli_loads, async_tree_io, xml_etree_parse


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.01x
- 95% likely to have a slowdown of 1.01x
- 99% likely to have a slowdown of 1.01x
