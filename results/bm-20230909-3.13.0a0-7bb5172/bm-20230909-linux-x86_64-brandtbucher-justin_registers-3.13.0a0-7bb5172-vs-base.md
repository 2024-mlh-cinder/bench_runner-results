
# Results vs. base

- fork: brandtbucher
- ref: justin_registers
- machine: linux-x86_64
- commit hash: 7bb5172
- commit date: 2023-09-09
- overall geometric mean: 1.07x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.03x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20230905-linux-x86_64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 | bm-20230909-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-7bb5172 |
|----------------|:---------------------------------------------------------------------:|:-----------------------------------------------------------------------:|
| docutils       | 2.62 sec                                                              | 2.73 sec: 1.04x slower                                                  |
| tornado_http   | 95.2 ms                                                               | 97.7 ms: 1.03x slower                                                   |
| Geometric mean | (ref)                                                                 | 1.03x slower                                                            |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20230905-linux-x86_64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 | bm-20230909-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-7bb5172 |
|----------------|:---------------------------------------------------------------------:|:-----------------------------------------------------------------------:|
| pidigits       | 187 ms                                                                | 188 ms: 1.01x slower                                                    |
| float          | 78.2 ms                                                               | 84.3 ms: 1.08x slower                                                   |
| nbody          | 88.7 ms                                                               | 137 ms: 1.55x slower                                                    |
| Geometric mean | (ref)                                                                 | 1.19x slower                                                            |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20230905-linux-x86_64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 | bm-20230909-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-7bb5172 |
|----------------|:---------------------------------------------------------------------:|:-----------------------------------------------------------------------:|
| regex_dna      | 216 ms                                                                | 218 ms: 1.01x slower                                                    |
| regex_v8       | 24.6 ms                                                               | 25.5 ms: 1.04x slower                                                   |
| regex_effbot   | 3.58 ms                                                               | 3.75 ms: 1.05x slower                                                   |
| regex_compile  | 134 ms                                                                | 150 ms: 1.12x slower                                                    |
| Geometric mean | (ref)                                                                 | 1.05x slower                                                            |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20230905-linux-x86_64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 | bm-20230909-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-7bb5172 |
|----------------------|:---------------------------------------------------------------------:|:-----------------------------------------------------------------------:|
| pickle_dict          | 32.6 us                                                               | 32.1 us: 1.02x faster                                                   |
| json_loads           | 24.9 us                                                               | 25.1 us: 1.01x slower                                                   |
| pickle               | 10.7 us                                                               | 10.8 us: 1.01x slower                                                   |
| xml_etree_parse      | 151 ms                                                                | 152 ms: 1.01x slower                                                    |
| pickle_list          | 4.62 us                                                               | 4.68 us: 1.01x slower                                                   |
| json_dumps           | 9.72 ms                                                               | 9.99 ms: 1.03x slower                                                   |
| unpickle             | 14.2 us                                                               | 14.7 us: 1.03x slower                                                   |
| pickle_pure_python   | 295 us                                                                | 305 us: 1.03x slower                                                    |
| xml_etree_iterparse  | 102 ms                                                                | 105 ms: 1.03x slower                                                    |
| xml_etree_process    | 56.2 ms                                                               | 58.6 ms: 1.04x slower                                                   |
| xml_etree_generate   | 81.5 ms                                                               | 88.2 ms: 1.08x slower                                                   |
| unpickle_pure_python | 212 us                                                                | 238 us: 1.12x slower                                                    |
| tomli_loads          | 2.02 sec                                                              | 2.29 sec: 1.13x slower                                                  |
| Geometric mean       | (ref)                                                                 | 1.04x slower                                                            |

Benchmark hidden because not significant (1): unpickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20230905-linux-x86_64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 | bm-20230909-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-7bb5172 |
|------------------------|:---------------------------------------------------------------------:|:-----------------------------------------------------------------------:|
| python_startup         | 9.51 ms                                                               | 9.58 ms: 1.01x slower                                                   |
| python_startup_no_site | 6.98 ms                                                               | 7.04 ms: 1.01x slower                                                   |
| Geometric mean         | (ref)                                                                 | 1.01x slower                                                            |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20230905-linux-x86_64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 | bm-20230909-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-7bb5172 |
|-----------|:---------------------------------------------------------------------:|:-----------------------------------------------------------------------:|
| mako      | 10.5 ms                                                               | 13.9 ms: 1.32x slower                                                   |

All benchmarks:
===============

| Benchmark                | bm-20230905-linux-x86_64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 | bm-20230909-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-7bb5172 |
|--------------------------|:---------------------------------------------------------------------:|:-----------------------------------------------------------------------:|
| gc_traversal             | 4.33 ms                                                               | 3.84 ms: 1.13x faster                                                   |
| coroutines               | 22.6 ms                                                               | 22.1 ms: 1.02x faster                                                   |
| pickle_dict              | 32.6 us                                                               | 32.1 us: 1.02x faster                                                   |
| json                     | 4.91 ms                                                               | 4.84 ms: 1.01x faster                                                   |
| sqlite_synth             | 2.76 us                                                               | 2.74 us: 1.01x faster                                                   |
| asyncio_tcp_ssl          | 1.79 sec                                                              | 1.80 sec: 1.01x slower                                                  |
| json_loads               | 24.9 us                                                               | 25.1 us: 1.01x slower                                                   |
| python_startup           | 9.51 ms                                                               | 9.58 ms: 1.01x slower                                                   |
| pickle                   | 10.7 us                                                               | 10.8 us: 1.01x slower                                                   |
| xml_etree_parse          | 151 ms                                                                | 152 ms: 1.01x slower                                                    |
| pidigits                 | 187 ms                                                                | 188 ms: 1.01x slower                                                    |
| python_startup_no_site   | 6.98 ms                                                               | 7.04 ms: 1.01x slower                                                   |
| create_gc_cycles         | 1.49 ms                                                               | 1.51 ms: 1.01x slower                                                   |
| regex_dna                | 216 ms                                                                | 218 ms: 1.01x slower                                                    |
| pathlib                  | 18.6 ms                                                               | 18.8 ms: 1.01x slower                                                   |
| pickle_list              | 4.62 us                                                               | 4.68 us: 1.01x slower                                                   |
| asyncio_tcp              | 488 ms                                                                | 494 ms: 1.01x slower                                                    |
| deepcopy_reduce          | 3.10 us                                                               | 3.15 us: 1.01x slower                                                   |
| async_tree_cpu_io_mixed  | 706 ms                                                                | 719 ms: 1.02x slower                                                    |
| async_tree_io            | 1.19 sec                                                              | 1.21 sec: 1.02x slower                                                  |
| pycparser                | 1.16 sec                                                              | 1.18 sec: 1.02x slower                                                  |
| logging_format           | 6.52 us                                                               | 6.67 us: 1.02x slower                                                   |
| logging_simple           | 5.89 us                                                               | 6.03 us: 1.02x slower                                                   |
| tornado_http             | 95.2 ms                                                               | 97.7 ms: 1.03x slower                                                   |
| json_dumps               | 9.72 ms                                                               | 9.99 ms: 1.03x slower                                                   |
| async_tree_memoization   | 564 ms                                                                | 580 ms: 1.03x slower                                                    |
| scimark_monte_carlo      | 65.6 ms                                                               | 67.7 ms: 1.03x slower                                                   |
| sqlglot_parse            | 1.26 ms                                                               | 1.30 ms: 1.03x slower                                                   |
| mdp                      | 2.57 sec                                                              | 2.65 sec: 1.03x slower                                                  |
| unpickle                 | 14.2 us                                                               | 14.7 us: 1.03x slower                                                   |
| pickle_pure_python       | 295 us                                                                | 305 us: 1.03x slower                                                    |
| async_tree_none          | 436 ms                                                                | 451 ms: 1.03x slower                                                    |
| xml_etree_iterparse      | 102 ms                                                                | 105 ms: 1.03x slower                                                    |
| dulwich_log              | 66.4 ms                                                               | 68.9 ms: 1.04x slower                                                   |
| richards                 | 47.5 ms                                                               | 49.3 ms: 1.04x slower                                                   |
| richards_super           | 53.8 ms                                                               | 55.9 ms: 1.04x slower                                                   |
| dask                     | 519 ms                                                                | 539 ms: 1.04x slower                                                    |
| sqlglot_transpile        | 1.56 ms                                                               | 1.62 ms: 1.04x slower                                                   |
| regex_v8                 | 24.6 ms                                                               | 25.5 ms: 1.04x slower                                                   |
| xml_etree_process        | 56.2 ms                                                               | 58.6 ms: 1.04x slower                                                   |
| docutils                 | 2.62 sec                                                              | 2.73 sec: 1.04x slower                                                  |
| telco                    | 7.98 ms                                                               | 8.35 ms: 1.05x slower                                                   |
| regex_effbot             | 3.58 ms                                                               | 3.75 ms: 1.05x slower                                                   |
| generators               | 28.9 ms                                                               | 30.3 ms: 1.05x slower                                                   |
| bench_thread_pool        | 813 us                                                                | 853 us: 1.05x slower                                                    |
| raytrace                 | 273 ms                                                                | 287 ms: 1.05x slower                                                    |
| sqlglot_normalize        | 103 ms                                                                | 109 ms: 1.05x slower                                                    |
| pprint_safe_repr         | 724 ms                                                                | 767 ms: 1.06x slower                                                    |
| logging_silent           | 102 ns                                                                | 108 ns: 1.06x slower                                                    |
| spectral_norm            | 106 ms                                                                | 113 ms: 1.06x slower                                                    |
| meteor_contest           | 106 ms                                                                | 113 ms: 1.07x slower                                                    |
| scimark_lu               | 110 ms                                                                | 117 ms: 1.07x slower                                                    |
| async_generators         | 445 ms                                                                | 476 ms: 1.07x slower                                                    |
| sqlglot_optimize         | 52.3 ms                                                               | 56.0 ms: 1.07x slower                                                   |
| pprint_pformat           | 1.47 sec                                                              | 1.57 sec: 1.07x slower                                                  |
| float                    | 78.2 ms                                                               | 84.3 ms: 1.08x slower                                                   |
| pyflate                  | 448 ms                                                                | 484 ms: 1.08x slower                                                    |
| crypto_pyaes             | 68.7 ms                                                               | 74.2 ms: 1.08x slower                                                   |
| mypy2                    | 337 ms                                                                | 364 ms: 1.08x slower                                                    |
| xml_etree_generate       | 81.5 ms                                                               | 88.2 ms: 1.08x slower                                                   |
| deepcopy                 | 345 us                                                                | 376 us: 1.09x slower                                                    |
| scimark_fft              | 349 ms                                                                | 382 ms: 1.09x slower                                                    |
| go                       | 138 ms                                                                | 152 ms: 1.10x slower                                                    |
| scimark_sor              | 118 ms                                                                | 130 ms: 1.10x slower                                                    |
| deltablue                | 3.28 ms                                                               | 3.62 ms: 1.10x slower                                                   |
| fannkuch                 | 382 ms                                                                | 429 ms: 1.12x slower                                                    |
| regex_compile            | 134 ms                                                                | 150 ms: 1.12x slower                                                    |
| unpickle_pure_python     | 212 us                                                                | 238 us: 1.12x slower                                                    |
| tomli_loads              | 2.02 sec                                                              | 2.29 sec: 1.13x slower                                                  |
| chaos                    | 59.1 ms                                                               | 67.7 ms: 1.14x slower                                                   |
| typing_runtime_protocols | 140 us                                                                | 162 us: 1.15x slower                                                    |
| nqueens                  | 79.4 ms                                                               | 96.9 ms: 1.22x slower                                                   |
| hexiom                   | 5.96 ms                                                               | 7.38 ms: 1.24x slower                                                   |
| unpack_sequence          | 43.8 ns                                                               | 55.9 ns: 1.28x slower                                                   |
| mako                     | 10.5 ms                                                               | 13.9 ms: 1.32x slower                                                   |
| comprehensions           | 20.7 us                                                               | 27.9 us: 1.35x slower                                                   |
| deepcopy_memo            | 36.9 us                                                               | 51.5 us: 1.39x slower                                                   |
| nbody                    | 88.7 ms                                                               | 137 ms: 1.55x slower                                                    |
| scimark_sparse_mat_mult  | 4.63 ms                                                               | 9.20 ms: 1.99x slower                                                   |
| Geometric mean           | (ref)                                                                 | 1.07x slower                                                            |

Benchmark hidden because not significant (3): unpickle_list, coverage, bench_mp_pool


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.03x
- 95% likely to have a slowdown of 1.03x
- 99% likely to have a slowdown of 1.03x
