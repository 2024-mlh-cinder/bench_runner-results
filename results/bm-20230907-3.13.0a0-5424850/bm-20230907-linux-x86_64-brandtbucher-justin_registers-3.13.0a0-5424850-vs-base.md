
# Results vs. base

- fork: brandtbucher
- ref: justin_registers
- machine: linux-x86_64
- commit hash: 5424850
- commit date: 2023-09-07
- overall geometric mean: 1.05x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.03x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20230905-linux-x86_64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 | bm-20230907-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-5424850 |
|----------------|:---------------------------------------------------------------------:|:-----------------------------------------------------------------------:|
| docutils       | 2.62 sec                                                              | 2.72 sec: 1.04x slower                                                  |
| tornado_http   | 95.2 ms                                                               | 98.0 ms: 1.03x slower                                                   |
| Geometric mean | (ref)                                                                 | 1.03x slower                                                            |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20230905-linux-x86_64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 | bm-20230907-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-5424850 |
|----------------|:---------------------------------------------------------------------:|:-----------------------------------------------------------------------:|
| pidigits       | 187 ms                                                                | 187 ms: 1.00x slower                                                    |
| float          | 78.2 ms                                                               | 82.9 ms: 1.06x slower                                                   |
| nbody          | 88.7 ms                                                               | 103 ms: 1.16x slower                                                    |
| Geometric mean | (ref)                                                                 | 1.07x slower                                                            |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20230905-linux-x86_64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 | bm-20230907-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-5424850 |
|----------------|:---------------------------------------------------------------------:|:-----------------------------------------------------------------------:|
| regex_effbot   | 3.58 ms                                                               | 3.63 ms: 1.01x slower                                                   |
| regex_v8       | 24.6 ms                                                               | 25.2 ms: 1.03x slower                                                   |
| regex_dna      | 216 ms                                                                | 226 ms: 1.05x slower                                                    |
| regex_compile  | 134 ms                                                                | 147 ms: 1.10x slower                                                    |
| Geometric mean | (ref)                                                                 | 1.05x slower                                                            |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20230905-linux-x86_64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 | bm-20230907-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-5424850 |
|----------------------|:---------------------------------------------------------------------:|:-----------------------------------------------------------------------:|
| pickle_dict          | 32.6 us                                                               | 32.2 us: 1.01x faster                                                   |
| xml_etree_parse      | 151 ms                                                                | 152 ms: 1.01x slower                                                    |
| unpickle_list        | 4.89 us                                                               | 4.93 us: 1.01x slower                                                   |
| pickle               | 10.7 us                                                               | 10.8 us: 1.02x slower                                                   |
| json_loads           | 24.9 us                                                               | 25.3 us: 1.02x slower                                                   |
| json_dumps           | 9.72 ms                                                               | 9.91 ms: 1.02x slower                                                   |
| pickle_pure_python   | 295 us                                                                | 303 us: 1.03x slower                                                    |
| xml_etree_iterparse  | 102 ms                                                                | 105 ms: 1.03x slower                                                    |
| xml_etree_generate   | 81.5 ms                                                               | 84.5 ms: 1.04x slower                                                   |
| xml_etree_process    | 56.2 ms                                                               | 58.3 ms: 1.04x slower                                                   |
| unpickle             | 14.2 us                                                               | 14.8 us: 1.04x slower                                                   |
| pickle_list          | 4.62 us                                                               | 4.83 us: 1.04x slower                                                   |
| tomli_loads          | 2.02 sec                                                              | 2.26 sec: 1.12x slower                                                  |
| unpickle_pure_python | 212 us                                                                | 237 us: 1.12x slower                                                    |
| Geometric mean       | (ref)                                                                 | 1.04x slower                                                            |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20230905-linux-x86_64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 | bm-20230907-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-5424850 |
|------------------------|:---------------------------------------------------------------------:|:-----------------------------------------------------------------------:|
| python_startup         | 9.51 ms                                                               | 9.59 ms: 1.01x slower                                                   |
| python_startup_no_site | 6.98 ms                                                               | 7.06 ms: 1.01x slower                                                   |
| Geometric mean         | (ref)                                                                 | 1.01x slower                                                            |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20230905-linux-x86_64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 | bm-20230907-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-5424850 |
|-----------|:---------------------------------------------------------------------:|:-----------------------------------------------------------------------:|
| mako      | 10.5 ms                                                               | 11.6 ms: 1.10x slower                                                   |

All benchmarks:
===============

| Benchmark                | bm-20230905-linux-x86_64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 | bm-20230907-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-5424850 |
|--------------------------|:---------------------------------------------------------------------:|:-----------------------------------------------------------------------:|
| gc_traversal             | 4.33 ms                                                               | 3.67 ms: 1.18x faster                                                   |
| coroutines               | 22.6 ms                                                               | 22.1 ms: 1.02x faster                                                   |
| pickle_dict              | 32.6 us                                                               | 32.2 us: 1.01x faster                                                   |
| pidigits                 | 187 ms                                                                | 187 ms: 1.00x slower                                                    |
| xml_etree_parse          | 151 ms                                                                | 152 ms: 1.01x slower                                                    |
| async_tree_io            | 1.19 sec                                                              | 1.20 sec: 1.01x slower                                                  |
| asyncio_tcp_ssl          | 1.79 sec                                                              | 1.81 sec: 1.01x slower                                                  |
| asyncio_tcp              | 488 ms                                                                | 492 ms: 1.01x slower                                                    |
| unpickle_list            | 4.89 us                                                               | 4.93 us: 1.01x slower                                                   |
| python_startup           | 9.51 ms                                                               | 9.59 ms: 1.01x slower                                                   |
| python_startup_no_site   | 6.98 ms                                                               | 7.06 ms: 1.01x slower                                                   |
| regex_effbot             | 3.58 ms                                                               | 3.63 ms: 1.01x slower                                                   |
| async_tree_memoization   | 564 ms                                                                | 573 ms: 1.02x slower                                                    |
| pickle                   | 10.7 us                                                               | 10.8 us: 1.02x slower                                                   |
| pathlib                  | 18.6 ms                                                               | 18.9 ms: 1.02x slower                                                   |
| logging_format           | 6.52 us                                                               | 6.62 us: 1.02x slower                                                   |
| json_loads               | 24.9 us                                                               | 25.3 us: 1.02x slower                                                   |
| json_dumps               | 9.72 ms                                                               | 9.91 ms: 1.02x slower                                                   |
| logging_simple           | 5.89 us                                                               | 6.02 us: 1.02x slower                                                   |
| deepcopy_reduce          | 3.10 us                                                               | 3.18 us: 1.02x slower                                                   |
| regex_v8                 | 24.6 ms                                                               | 25.2 ms: 1.03x slower                                                   |
| richards_super           | 53.8 ms                                                               | 55.3 ms: 1.03x slower                                                   |
| pickle_pure_python       | 295 us                                                                | 303 us: 1.03x slower                                                    |
| coverage                 | 86.6 ms                                                               | 88.9 ms: 1.03x slower                                                   |
| xml_etree_iterparse      | 102 ms                                                                | 105 ms: 1.03x slower                                                    |
| tornado_http             | 95.2 ms                                                               | 98.0 ms: 1.03x slower                                                   |
| dask                     | 519 ms                                                                | 535 ms: 1.03x slower                                                    |
| sqlglot_normalize        | 103 ms                                                                | 107 ms: 1.03x slower                                                    |
| sqlglot_parse            | 1.26 ms                                                               | 1.30 ms: 1.03x slower                                                   |
| spectral_norm            | 106 ms                                                                | 110 ms: 1.04x slower                                                    |
| xml_etree_generate       | 81.5 ms                                                               | 84.5 ms: 1.04x slower                                                   |
| xml_etree_process        | 56.2 ms                                                               | 58.3 ms: 1.04x slower                                                   |
| sqlglot_optimize         | 52.3 ms                                                               | 54.2 ms: 1.04x slower                                                   |
| deepcopy                 | 345 us                                                                | 358 us: 1.04x slower                                                    |
| generators               | 28.9 ms                                                               | 30.0 ms: 1.04x slower                                                   |
| unpickle                 | 14.2 us                                                               | 14.8 us: 1.04x slower                                                   |
| bench_thread_pool        | 813 us                                                                | 844 us: 1.04x slower                                                    |
| docutils                 | 2.62 sec                                                              | 2.72 sec: 1.04x slower                                                  |
| raytrace                 | 273 ms                                                                | 283 ms: 1.04x slower                                                    |
| sqlglot_transpile        | 1.56 ms                                                               | 1.62 ms: 1.04x slower                                                   |
| dulwich_log              | 66.4 ms                                                               | 69.0 ms: 1.04x slower                                                   |
| pprint_safe_repr         | 724 ms                                                                | 756 ms: 1.04x slower                                                    |
| richards                 | 47.5 ms                                                               | 49.6 ms: 1.04x slower                                                   |
| pickle_list              | 4.62 us                                                               | 4.83 us: 1.04x slower                                                   |
| scimark_monte_carlo      | 65.6 ms                                                               | 68.7 ms: 1.05x slower                                                   |
| telco                    | 7.98 ms                                                               | 8.35 ms: 1.05x slower                                                   |
| regex_dna                | 216 ms                                                                | 226 ms: 1.05x slower                                                    |
| pprint_pformat           | 1.47 sec                                                              | 1.55 sec: 1.06x slower                                                  |
| scimark_sor              | 118 ms                                                                | 125 ms: 1.06x slower                                                    |
| mypy2                    | 337 ms                                                                | 357 ms: 1.06x slower                                                    |
| crypto_pyaes             | 68.7 ms                                                               | 72.7 ms: 1.06x slower                                                   |
| async_generators         | 445 ms                                                                | 471 ms: 1.06x slower                                                    |
| float                    | 78.2 ms                                                               | 82.9 ms: 1.06x slower                                                   |
| scimark_lu               | 110 ms                                                                | 117 ms: 1.07x slower                                                    |
| deltablue                | 3.28 ms                                                               | 3.49 ms: 1.07x slower                                                   |
| scimark_fft              | 349 ms                                                                | 374 ms: 1.07x slower                                                    |
| pycparser                | 1.16 sec                                                              | 1.24 sec: 1.07x slower                                                  |
| meteor_contest           | 106 ms                                                                | 113 ms: 1.07x slower                                                    |
| mdp                      | 2.57 sec                                                              | 2.76 sec: 1.07x slower                                                  |
| pyflate                  | 448 ms                                                                | 482 ms: 1.08x slower                                                    |
| logging_silent           | 102 ns                                                                | 110 ns: 1.08x slower                                                    |
| mako                     | 10.5 ms                                                               | 11.6 ms: 1.10x slower                                                   |
| go                       | 138 ms                                                                | 152 ms: 1.10x slower                                                    |
| deepcopy_memo            | 36.9 us                                                               | 40.7 us: 1.10x slower                                                   |
| regex_compile            | 134 ms                                                                | 147 ms: 1.10x slower                                                    |
| fannkuch                 | 382 ms                                                                | 426 ms: 1.11x slower                                                    |
| tomli_loads              | 2.02 sec                                                              | 2.26 sec: 1.12x slower                                                  |
| unpickle_pure_python     | 212 us                                                                | 237 us: 1.12x slower                                                    |
| typing_runtime_protocols | 140 us                                                                | 158 us: 1.13x slower                                                    |
| scimark_sparse_mat_mult  | 4.63 ms                                                               | 5.25 ms: 1.14x slower                                                   |
| chaos                    | 59.1 ms                                                               | 67.5 ms: 1.14x slower                                                   |
| nbody                    | 88.7 ms                                                               | 103 ms: 1.16x slower                                                    |
| unpack_sequence          | 43.8 ns                                                               | 51.5 ns: 1.18x slower                                                   |
| nqueens                  | 79.4 ms                                                               | 94.9 ms: 1.19x slower                                                   |
| comprehensions           | 20.7 us                                                               | 25.1 us: 1.21x slower                                                   |
| hexiom                   | 5.96 ms                                                               | 7.29 ms: 1.22x slower                                                   |
| Geometric mean           | (ref)                                                                 | 1.05x slower                                                            |

Benchmark hidden because not significant (6): json, bench_mp_pool, create_gc_cycles, sqlite_synth, async_tree_cpu_io_mixed, async_tree_none


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.03x
- 95% likely to have a slowdown of 1.03x
- 99% likely to have a slowdown of 1.03x
