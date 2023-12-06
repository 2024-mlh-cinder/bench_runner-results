
# Results vs. 3.12.0

- fork: mdboom
- ref: count_tier2_miss_opc
- machine: linux-x86_64
- commit hash: 8ce6535
- commit date: 2023-10-09
- overall geometric mean: 1.02x slower
- HPT reliability: 94.66%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231009-linux-x86_64-mdboom-count_tier2_miss_opc-3.13.0a0-8ce6535 |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| docutils       | 2.70 sec                                               | 2.65 sec: 1.02x faster                                                |
| tornado_http   | 99.6 ms                                                | 96.2 ms: 1.03x faster                                                 |
| Geometric mean | (ref)                                                  | 1.03x faster                                                          |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231009-linux-x86_64-mdboom-count_tier2_miss_opc-3.13.0a0-8ce6535 |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| pidigits       | 187 ms                                                 | 187 ms: 1.00x slower                                                  |
| nbody          | 88.8 ms                                                | 95.9 ms: 1.08x slower                                                 |
| Geometric mean | (ref)                                                  | 1.03x slower                                                          |

Benchmark hidden because not significant (1): float

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231009-linux-x86_64-mdboom-count_tier2_miss_opc-3.13.0a0-8ce6535 |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| regex_compile  | 144 ms                                                 | 139 ms: 1.04x faster                                                  |
| regex_dna      | 209 ms                                                 | 207 ms: 1.01x faster                                                  |
| regex_effbot   | 3.55 ms                                                | 3.57 ms: 1.01x slower                                                 |
| regex_v8       | 22.3 ms                                                | 25.6 ms: 1.14x slower                                                 |
| Geometric mean | (ref)                                                  | 1.02x slower                                                          |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231009-linux-x86_64-mdboom-count_tier2_miss_opc-3.13.0a0-8ce6535 |
|----------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| tomli_loads          | 2.22 sec                                               | 2.15 sec: 1.03x faster                                                |
| pickle_pure_python   | 309 us                                                 | 305 us: 1.01x faster                                                  |
| xml_etree_iterparse  | 104 ms                                                 | 105 ms: 1.01x slower                                                  |
| xml_etree_process    | 58.6 ms                                                | 59.2 ms: 1.01x slower                                                 |
| unpickle_pure_python | 218 us                                                 | 222 us: 1.02x slower                                                  |
| xml_etree_generate   | 84.8 ms                                                | 86.5 ms: 1.02x slower                                                 |
| xml_etree_parse      | 154 ms                                                 | 158 ms: 1.03x slower                                                  |
| pickle_dict          | 31.6 us                                                | 33.1 us: 1.05x slower                                                 |
| pickle               | 10.6 us                                                | 11.1 us: 1.05x slower                                                 |
| json_dumps           | 9.85 ms                                                | 10.4 ms: 1.06x slower                                                 |
| unpickle_list        | 4.95 us                                                | 5.31 us: 1.07x slower                                                 |
| pickle_list          | 4.62 us                                                | 5.18 us: 1.12x slower                                                 |
| json_loads           | 25.2 us                                                | 28.6 us: 1.13x slower                                                 |
| Geometric mean       | (ref)                                                  | 1.04x slower                                                          |

Benchmark hidden because not significant (1): unpickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231009-linux-x86_64-mdboom-count_tier2_miss_opc-3.13.0a0-8ce6535 |
|------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| python_startup_no_site | 6.90 ms                                                | 6.85 ms: 1.01x faster                                                 |
| python_startup         | 9.47 ms                                                | 10.0 ms: 1.06x slower                                                 |
| Geometric mean         | (ref)                                                  | 1.03x slower                                                          |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231009-linux-x86_64-mdboom-count_tier2_miss_opc-3.13.0a0-8ce6535 |
|-----------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| mako      | 10.7 ms                                                | 11.5 ms: 1.07x slower                                                 |

All benchmarks:
===============

| Benchmark                | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231009-linux-x86_64-mdboom-count_tier2_miss_opc-3.13.0a0-8ce6535 |
|--------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| asyncio_tcp              | 526 ms                                                 | 466 ms: 1.13x faster                                                  |
| crypto_pyaes             | 77.2 ms                                                | 71.8 ms: 1.08x faster                                                 |
| async_tree_none          | 469 ms                                                 | 437 ms: 1.07x faster                                                  |
| generators               | 31.1 ms                                                | 29.2 ms: 1.06x faster                                                 |
| logging_format           | 6.90 us                                                | 6.53 us: 1.06x faster                                                 |
| raytrace                 | 294 ms                                                 | 281 ms: 1.05x faster                                                  |
| deltablue                | 3.52 ms                                                | 3.37 ms: 1.05x faster                                                 |
| logging_simple           | 6.18 us                                                | 5.95 us: 1.04x faster                                                 |
| regex_compile            | 144 ms                                                 | 139 ms: 1.04x faster                                                  |
| sqlglot_parse            | 1.32 ms                                                | 1.28 ms: 1.04x faster                                                 |
| tornado_http             | 99.6 ms                                                | 96.2 ms: 1.03x faster                                                 |
| tomli_loads              | 2.22 sec                                               | 2.15 sec: 1.03x faster                                                |
| coverage                 | 94.2 ms                                                | 91.6 ms: 1.03x faster                                                 |
| sqlglot_transpile        | 1.64 ms                                                | 1.60 ms: 1.03x faster                                                 |
| scimark_monte_carlo      | 71.0 ms                                                | 69.4 ms: 1.02x faster                                                 |
| coroutines               | 22.4 ms                                                | 22.0 ms: 1.02x faster                                                 |
| docutils                 | 2.70 sec                                               | 2.65 sec: 1.02x faster                                                |
| chaos                    | 63.5 ms                                                | 62.4 ms: 1.02x faster                                                 |
| sqlglot_normalize        | 107 ms                                                 | 106 ms: 1.01x faster                                                  |
| pickle_pure_python       | 309 us                                                 | 305 us: 1.01x faster                                                  |
| bench_thread_pool        | 827 us                                                 | 816 us: 1.01x faster                                                  |
| async_tree_memoization   | 573 ms                                                 | 566 ms: 1.01x faster                                                  |
| nqueens                  | 81.1 ms                                                | 80.1 ms: 1.01x faster                                                 |
| asyncio_tcp_ssl          | 1.79 sec                                               | 1.77 sec: 1.01x faster                                                |
| python_startup_no_site   | 6.90 ms                                                | 6.85 ms: 1.01x faster                                                 |
| regex_dna                | 209 ms                                                 | 207 ms: 1.01x faster                                                  |
| dulwich_log              | 67.9 ms                                                | 67.5 ms: 1.01x faster                                                 |
| pidigits                 | 187 ms                                                 | 187 ms: 1.00x slower                                                  |
| regex_effbot             | 3.55 ms                                                | 3.57 ms: 1.01x slower                                                 |
| create_gc_cycles         | 1.52 ms                                                | 1.53 ms: 1.01x slower                                                 |
| deepcopy                 | 355 us                                                 | 358 us: 1.01x slower                                                  |
| pprint_pformat           | 1.50 sec                                               | 1.51 sec: 1.01x slower                                                |
| xml_etree_iterparse      | 104 ms                                                 | 105 ms: 1.01x slower                                                  |
| pycparser                | 1.15 sec                                               | 1.16 sec: 1.01x slower                                                |
| pprint_safe_repr         | 735 ms                                                 | 743 ms: 1.01x slower                                                  |
| xml_etree_process        | 58.6 ms                                                | 59.2 ms: 1.01x slower                                                 |
| deepcopy_reduce          | 3.14 us                                                | 3.19 us: 1.02x slower                                                 |
| unpickle_pure_python     | 218 us                                                 | 222 us: 1.02x slower                                                  |
| hexiom                   | 6.12 ms                                                | 6.22 ms: 1.02x slower                                                 |
| xml_etree_generate       | 84.8 ms                                                | 86.5 ms: 1.02x slower                                                 |
| fannkuch                 | 387 ms                                                 | 397 ms: 1.02x slower                                                  |
| async_tree_io            | 1.16 sec                                               | 1.19 sec: 1.03x slower                                                |
| xml_etree_parse          | 154 ms                                                 | 158 ms: 1.03x slower                                                  |
| pathlib                  | 18.5 ms                                                | 19.1 ms: 1.03x slower                                                 |
| gc_traversal             | 3.84 ms                                                | 3.97 ms: 1.03x slower                                                 |
| sqlite_synth             | 2.76 us                                                | 2.85 us: 1.03x slower                                                 |
| comprehensions           | 20.4 us                                                | 21.3 us: 1.04x slower                                                 |
| meteor_contest           | 105 ms                                                 | 109 ms: 1.04x slower                                                  |
| scimark_fft              | 358 ms                                                 | 375 ms: 1.05x slower                                                  |
| pyflate                  | 450 ms                                                 | 471 ms: 1.05x slower                                                  |
| async_generators         | 440 ms                                                 | 461 ms: 1.05x slower                                                  |
| typing_runtime_protocols | 146 us                                                 | 153 us: 1.05x slower                                                  |
| mdp                      | 2.57 sec                                               | 2.69 sec: 1.05x slower                                                |
| pickle_dict              | 31.6 us                                                | 33.1 us: 1.05x slower                                                 |
| pickle                   | 10.6 us                                                | 11.1 us: 1.05x slower                                                 |
| spectral_norm            | 106 ms                                                 | 112 ms: 1.05x slower                                                  |
| json_dumps               | 9.85 ms                                                | 10.4 ms: 1.06x slower                                                 |
| scimark_sparse_mat_mult  | 4.74 ms                                                | 5.02 ms: 1.06x slower                                                 |
| python_startup           | 9.47 ms                                                | 10.0 ms: 1.06x slower                                                 |
| go                       | 136 ms                                                 | 144 ms: 1.06x slower                                                  |
| deepcopy_memo            | 37.4 us                                                | 39.9 us: 1.07x slower                                                 |
| mako                     | 10.7 ms                                                | 11.5 ms: 1.07x slower                                                 |
| unpickle_list            | 4.95 us                                                | 5.31 us: 1.07x slower                                                 |
| nbody                    | 88.8 ms                                                | 95.9 ms: 1.08x slower                                                 |
| logging_silent           | 99.1 ns                                                | 107 ns: 1.08x slower                                                  |
| json                     | 4.77 ms                                                | 5.17 ms: 1.08x slower                                                 |
| pickle_list              | 4.62 us                                                | 5.18 us: 1.12x slower                                                 |
| richards                 | 43.2 ms                                                | 48.7 ms: 1.13x slower                                                 |
| json_loads               | 25.2 us                                                | 28.6 us: 1.13x slower                                                 |
| richards_super           | 49.0 ms                                                | 55.6 ms: 1.13x slower                                                 |
| regex_v8                 | 22.3 ms                                                | 25.6 ms: 1.14x slower                                                 |
| unpack_sequence          | 44.8 ns                                                | 52.0 ns: 1.16x slower                                                 |
| telco                    | 6.87 ms                                                | 8.51 ms: 1.24x slower                                                 |
| Geometric mean           | (ref)                                                  | 1.02x slower                                                          |

Benchmark hidden because not significant (8): unpickle, async_tree_cpu_io_mixed, scimark_lu, float, scimark_sor, sqlglot_optimize, bench_mp_pool, mypy2
Ignored benchmarks (4) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: 2to3, dask, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 94.66% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
