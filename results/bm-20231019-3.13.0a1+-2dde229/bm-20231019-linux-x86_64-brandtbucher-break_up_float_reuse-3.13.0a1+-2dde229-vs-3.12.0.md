
# Results vs. 3.12.0

- fork: brandtbucher
- ref: break_up_float_reuse
- machine: linux-x86_64
- commit hash: 2dde229
- commit date: 2023-10-19
- overall geometric mean: 1.03x slower
- HPT reliability: 99.72%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231019-linux-x86_64-brandtbucher-break_up_float_reuse-3.13.0a1+-2dde229 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------------:|
| docutils       | 2.70 sec                                               | 2.65 sec: 1.02x faster                                                       |
| tornado_http   | 99.6 ms                                                | 95.7 ms: 1.04x faster                                                        |
| Geometric mean | (ref)                                                  | 1.03x faster                                                                 |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231019-linux-x86_64-brandtbucher-break_up_float_reuse-3.13.0a1+-2dde229 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------------:|
| pidigits       | 187 ms                                                 | 188 ms: 1.01x slower                                                         |
| float          | 80.7 ms                                                | 82.0 ms: 1.02x slower                                                        |
| nbody          | 88.8 ms                                                | 95.9 ms: 1.08x slower                                                        |
| Geometric mean | (ref)                                                  | 1.03x slower                                                                 |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231019-linux-x86_64-brandtbucher-break_up_float_reuse-3.13.0a1+-2dde229 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------------:|
| regex_compile  | 144 ms                                                 | 138 ms: 1.04x faster                                                         |
| regex_dna      | 209 ms                                                 | 218 ms: 1.04x slower                                                         |
| regex_v8       | 22.3 ms                                                | 24.3 ms: 1.09x slower                                                        |
| regex_effbot   | 3.55 ms                                                | 4.13 ms: 1.17x slower                                                        |
| Geometric mean | (ref)                                                  | 1.06x slower                                                                 |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231019-linux-x86_64-brandtbucher-break_up_float_reuse-3.13.0a1+-2dde229 |
|----------------------|:------------------------------------------------------:|:----------------------------------------------------------------------------:|
| unpickle             | 15.0 us                                                | 14.5 us: 1.03x faster                                                        |
| tomli_loads          | 2.22 sec                                               | 2.18 sec: 1.02x faster                                                       |
| pickle_pure_python   | 309 us                                                 | 311 us: 1.01x slower                                                         |
| xml_etree_generate   | 84.8 ms                                                | 86.5 ms: 1.02x slower                                                        |
| xml_etree_iterparse  | 104 ms                                                 | 106 ms: 1.02x slower                                                         |
| unpickle_pure_python | 218 us                                                 | 223 us: 1.02x slower                                                         |
| xml_etree_process    | 58.6 ms                                                | 59.9 ms: 1.02x slower                                                        |
| xml_etree_parse      | 154 ms                                                 | 159 ms: 1.03x slower                                                         |
| json_dumps           | 9.85 ms                                                | 10.4 ms: 1.06x slower                                                        |
| unpickle_list        | 4.95 us                                                | 5.25 us: 1.06x slower                                                        |
| pickle               | 10.6 us                                                | 11.5 us: 1.08x slower                                                        |
| json_loads           | 25.2 us                                                | 27.8 us: 1.10x slower                                                        |
| pickle_dict          | 31.6 us                                                | 34.9 us: 1.10x slower                                                        |
| pickle_list          | 4.62 us                                                | 5.22 us: 1.13x slower                                                        |
| Geometric mean       | (ref)                                                  | 1.04x slower                                                                 |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231019-linux-x86_64-brandtbucher-break_up_float_reuse-3.13.0a1+-2dde229 |
|------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------------:|
| python_startup_no_site | 6.90 ms                                                | 6.86 ms: 1.01x faster                                                        |
| python_startup         | 9.47 ms                                                | 10.1 ms: 1.06x slower                                                        |
| Geometric mean         | (ref)                                                  | 1.03x slower                                                                 |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231019-linux-x86_64-brandtbucher-break_up_float_reuse-3.13.0a1+-2dde229 |
|-----------|:------------------------------------------------------:|:----------------------------------------------------------------------------:|
| mako      | 10.7 ms                                                | 11.8 ms: 1.10x slower                                                        |

All benchmarks:
===============

| Benchmark                | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231019-linux-x86_64-brandtbucher-break_up_float_reuse-3.13.0a1+-2dde229 |
|--------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------------:|
| asyncio_tcp              | 526 ms                                                 | 481 ms: 1.09x faster                                                         |
| async_tree_none          | 469 ms                                                 | 440 ms: 1.07x faster                                                         |
| logging_format           | 6.90 us                                                | 6.53 us: 1.06x faster                                                        |
| raytrace                 | 294 ms                                                 | 279 ms: 1.05x faster                                                         |
| crypto_pyaes             | 77.2 ms                                                | 73.8 ms: 1.05x faster                                                        |
| deltablue                | 3.52 ms                                                | 3.37 ms: 1.05x faster                                                        |
| generators               | 31.1 ms                                                | 29.8 ms: 1.04x faster                                                        |
| create_gc_cycles         | 1.52 ms                                                | 1.46 ms: 1.04x faster                                                        |
| tornado_http             | 99.6 ms                                                | 95.7 ms: 1.04x faster                                                        |
| coverage                 | 94.2 ms                                                | 90.6 ms: 1.04x faster                                                        |
| regex_compile            | 144 ms                                                 | 138 ms: 1.04x faster                                                         |
| logging_simple           | 6.18 us                                                | 5.96 us: 1.04x faster                                                        |
| unpickle                 | 15.0 us                                                | 14.5 us: 1.03x faster                                                        |
| sqlglot_parse            | 1.32 ms                                                | 1.29 ms: 1.02x faster                                                        |
| chaos                    | 63.5 ms                                                | 62.1 ms: 1.02x faster                                                        |
| sqlglot_transpile        | 1.64 ms                                                | 1.60 ms: 1.02x faster                                                        |
| docutils                 | 2.70 sec                                               | 2.65 sec: 1.02x faster                                                       |
| tomli_loads              | 2.22 sec                                               | 2.18 sec: 1.02x faster                                                       |
| async_tree_memoization   | 573 ms                                                 | 564 ms: 1.02x faster                                                         |
| bench_thread_pool        | 827 us                                                 | 815 us: 1.02x faster                                                         |
| dulwich_log              | 67.9 ms                                                | 67.0 ms: 1.01x faster                                                        |
| python_startup_no_site   | 6.90 ms                                                | 6.86 ms: 1.01x faster                                                        |
| asyncio_tcp_ssl          | 1.79 sec                                               | 1.79 sec: 1.00x faster                                                       |
| nqueens                  | 81.1 ms                                                | 80.9 ms: 1.00x faster                                                        |
| sqlglot_normalize        | 107 ms                                                 | 107 ms: 1.00x slower                                                         |
| pickle_pure_python       | 309 us                                                 | 311 us: 1.01x slower                                                         |
| sqlglot_optimize         | 53.3 ms                                                | 53.7 ms: 1.01x slower                                                        |
| deepcopy_reduce          | 3.14 us                                                | 3.16 us: 1.01x slower                                                        |
| pidigits                 | 187 ms                                                 | 188 ms: 1.01x slower                                                         |
| pprint_pformat           | 1.50 sec                                               | 1.52 sec: 1.01x slower                                                       |
| float                    | 80.7 ms                                                | 82.0 ms: 1.02x slower                                                        |
| scimark_sparse_mat_mult  | 4.74 ms                                                | 4.82 ms: 1.02x slower                                                        |
| scimark_lu               | 114 ms                                                 | 116 ms: 1.02x slower                                                         |
| comprehensions           | 20.4 us                                                | 20.8 us: 1.02x slower                                                        |
| pprint_safe_repr         | 735 ms                                                 | 748 ms: 1.02x slower                                                         |
| xml_etree_generate       | 84.8 ms                                                | 86.5 ms: 1.02x slower                                                        |
| xml_etree_iterparse      | 104 ms                                                 | 106 ms: 1.02x slower                                                         |
| unpickle_pure_python     | 218 us                                                 | 223 us: 1.02x slower                                                         |
| xml_etree_process        | 58.6 ms                                                | 59.9 ms: 1.02x slower                                                        |
| hexiom                   | 6.12 ms                                                | 6.26 ms: 1.02x slower                                                        |
| async_tree_io            | 1.16 sec                                               | 1.19 sec: 1.03x slower                                                       |
| pathlib                  | 18.5 ms                                                | 19.0 ms: 1.03x slower                                                        |
| xml_etree_parse          | 154 ms                                                 | 159 ms: 1.03x slower                                                         |
| meteor_contest           | 105 ms                                                 | 109 ms: 1.04x slower                                                         |
| mdp                      | 2.57 sec                                               | 2.67 sec: 1.04x slower                                                       |
| sqlite_synth             | 2.76 us                                                | 2.87 us: 1.04x slower                                                        |
| async_generators         | 440 ms                                                 | 459 ms: 1.04x slower                                                         |
| regex_dna                | 209 ms                                                 | 218 ms: 1.04x slower                                                         |
| deepcopy_memo            | 37.4 us                                                | 39.2 us: 1.05x slower                                                        |
| typing_runtime_protocols | 146 us                                                 | 153 us: 1.05x slower                                                         |
| scimark_fft              | 358 ms                                                 | 376 ms: 1.05x slower                                                         |
| gc_traversal             | 3.84 ms                                                | 4.04 ms: 1.05x slower                                                        |
| json_dumps               | 9.85 ms                                                | 10.4 ms: 1.06x slower                                                        |
| go                       | 136 ms                                                 | 143 ms: 1.06x slower                                                         |
| coroutines               | 22.4 ms                                                | 23.7 ms: 1.06x slower                                                        |
| pyflate                  | 450 ms                                                 | 476 ms: 1.06x slower                                                         |
| pycparser                | 1.15 sec                                               | 1.22 sec: 1.06x slower                                                       |
| scimark_sor              | 125 ms                                                 | 132 ms: 1.06x slower                                                         |
| unpickle_list            | 4.95 us                                                | 5.25 us: 1.06x slower                                                        |
| python_startup           | 9.47 ms                                                | 10.1 ms: 1.06x slower                                                        |
| json                     | 4.77 ms                                                | 5.12 ms: 1.07x slower                                                        |
| spectral_norm            | 106 ms                                                 | 114 ms: 1.07x slower                                                         |
| logging_silent           | 99.1 ns                                                | 107 ns: 1.08x slower                                                         |
| nbody                    | 88.8 ms                                                | 95.9 ms: 1.08x slower                                                        |
| pickle                   | 10.6 us                                                | 11.5 us: 1.08x slower                                                        |
| fannkuch                 | 387 ms                                                 | 420 ms: 1.08x slower                                                         |
| regex_v8                 | 22.3 ms                                                | 24.3 ms: 1.09x slower                                                        |
| json_loads               | 25.2 us                                                | 27.8 us: 1.10x slower                                                        |
| pickle_dict              | 31.6 us                                                | 34.9 us: 1.10x slower                                                        |
| mako                     | 10.7 ms                                                | 11.8 ms: 1.10x slower                                                        |
| richards                 | 43.2 ms                                                | 48.8 ms: 1.13x slower                                                        |
| pickle_list              | 4.62 us                                                | 5.22 us: 1.13x slower                                                        |
| richards_super           | 49.0 ms                                                | 55.5 ms: 1.13x slower                                                        |
| regex_effbot             | 3.55 ms                                                | 4.13 ms: 1.17x slower                                                        |
| telco                    | 6.87 ms                                                | 8.37 ms: 1.22x slower                                                        |
| unpack_sequence          | 44.8 ns                                                | 58.1 ns: 1.30x slower                                                        |
| Geometric mean           | (ref)                                                  | 1.03x slower                                                                 |

Benchmark hidden because not significant (5): scimark_monte_carlo, deepcopy, async_tree_cpu_io_mixed, bench_mp_pool, mypy2
Ignored benchmarks (4) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: 2to3, dask, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 99.72% likely to be slow
- 90% likely to have a slowdown of 1.01x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
