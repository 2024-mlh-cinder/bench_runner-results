
# Results vs. 3.12.0

- fork: mdboom
- ref: count_tier2_miss_opc
- machine: linux-x86_64
- commit hash: 22212fb
- commit date: 2023-10-09
- overall geometric mean: 1.02x slower
- HPT reliability: 99.63%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231009-linux-x86_64-mdboom-count_tier2_miss_opc-3.13.0a0-22212fb |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| docutils       | 2.70 sec                                               | 2.65 sec: 1.02x faster                                                |
| tornado_http   | 99.6 ms                                                | 96.0 ms: 1.04x faster                                                 |
| Geometric mean | (ref)                                                  | 1.03x faster                                                          |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231009-linux-x86_64-mdboom-count_tier2_miss_opc-3.13.0a0-22212fb |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| pidigits       | 187 ms                                                 | 188 ms: 1.01x slower                                                  |
| float          | 80.7 ms                                                | 82.8 ms: 1.03x slower                                                 |
| nbody          | 88.8 ms                                                | 95.8 ms: 1.08x slower                                                 |
| Geometric mean | (ref)                                                  | 1.04x slower                                                          |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231009-linux-x86_64-mdboom-count_tier2_miss_opc-3.13.0a0-22212fb |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| regex_compile  | 144 ms                                                 | 138 ms: 1.04x faster                                                  |
| regex_effbot   | 3.55 ms                                                | 3.58 ms: 1.01x slower                                                 |
| regex_v8       | 22.3 ms                                                | 25.5 ms: 1.14x slower                                                 |
| Geometric mean | (ref)                                                  | 1.02x slower                                                          |

Benchmark hidden because not significant (1): regex_dna

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231009-linux-x86_64-mdboom-count_tier2_miss_opc-3.13.0a0-22212fb |
|----------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| tomli_loads          | 2.22 sec                                               | 2.16 sec: 1.03x faster                                                |
| pickle_pure_python   | 309 us                                                 | 307 us: 1.01x faster                                                  |
| unpickle             | 15.0 us                                                | 15.1 us: 1.01x slower                                                 |
| xml_etree_iterparse  | 104 ms                                                 | 105 ms: 1.01x slower                                                  |
| unpickle_pure_python | 218 us                                                 | 223 us: 1.02x slower                                                  |
| xml_etree_process    | 58.6 ms                                                | 60.1 ms: 1.03x slower                                                 |
| xml_etree_generate   | 84.8 ms                                                | 88.1 ms: 1.04x slower                                                 |
| xml_etree_parse      | 154 ms                                                 | 160 ms: 1.04x slower                                                  |
| json_dumps           | 9.85 ms                                                | 10.4 ms: 1.05x slower                                                 |
| pickle               | 10.6 us                                                | 11.3 us: 1.07x slower                                                 |
| unpickle_list        | 4.95 us                                                | 5.30 us: 1.07x slower                                                 |
| pickle_list          | 4.62 us                                                | 4.96 us: 1.08x slower                                                 |
| pickle_dict          | 31.6 us                                                | 34.8 us: 1.10x slower                                                 |
| json_loads           | 25.2 us                                                | 28.4 us: 1.13x slower                                                 |
| Geometric mean       | (ref)                                                  | 1.04x slower                                                          |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231009-linux-x86_64-mdboom-count_tier2_miss_opc-3.13.0a0-22212fb |
|------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| python_startup_no_site | 6.90 ms                                                | 6.87 ms: 1.00x faster                                                 |
| python_startup         | 9.47 ms                                                | 10.1 ms: 1.06x slower                                                 |
| Geometric mean         | (ref)                                                  | 1.03x slower                                                          |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231009-linux-x86_64-mdboom-count_tier2_miss_opc-3.13.0a0-22212fb |
|-----------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| mako      | 10.7 ms                                                | 11.3 ms: 1.06x slower                                                 |

All benchmarks:
===============

| Benchmark                | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231009-linux-x86_64-mdboom-count_tier2_miss_opc-3.13.0a0-22212fb |
|--------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| asyncio_tcp              | 526 ms                                                 | 468 ms: 1.12x faster                                                  |
| crypto_pyaes             | 77.2 ms                                                | 71.8 ms: 1.08x faster                                                 |
| raytrace                 | 294 ms                                                 | 277 ms: 1.06x faster                                                  |
| generators               | 31.1 ms                                                | 29.3 ms: 1.06x faster                                                 |
| async_tree_none          | 469 ms                                                 | 442 ms: 1.06x faster                                                  |
| unpack_sequence          | 44.8 ns                                                | 42.5 ns: 1.05x faster                                                 |
| logging_format           | 6.90 us                                                | 6.55 us: 1.05x faster                                                 |
| deltablue                | 3.52 ms                                                | 3.36 ms: 1.05x faster                                                 |
| coverage                 | 94.2 ms                                                | 90.3 ms: 1.04x faster                                                 |
| regex_compile            | 144 ms                                                 | 138 ms: 1.04x faster                                                  |
| tornado_http             | 99.6 ms                                                | 96.0 ms: 1.04x faster                                                 |
| chaos                    | 63.5 ms                                                | 61.7 ms: 1.03x faster                                                 |
| tomli_loads              | 2.22 sec                                               | 2.16 sec: 1.03x faster                                                |
| sqlglot_parse            | 1.32 ms                                                | 1.29 ms: 1.02x faster                                                 |
| sqlglot_transpile        | 1.64 ms                                                | 1.61 ms: 1.02x faster                                                 |
| logging_simple           | 6.18 us                                                | 6.05 us: 1.02x faster                                                 |
| docutils                 | 2.70 sec                                               | 2.65 sec: 1.02x faster                                                |
| scimark_monte_carlo      | 71.0 ms                                                | 69.8 ms: 1.02x faster                                                 |
| sqlglot_normalize        | 107 ms                                                 | 105 ms: 1.02x faster                                                  |
| bench_thread_pool        | 827 us                                                 | 818 us: 1.01x faster                                                  |
| asyncio_tcp_ssl          | 1.79 sec                                               | 1.78 sec: 1.01x faster                                                |
| pickle_pure_python       | 309 us                                                 | 307 us: 1.01x faster                                                  |
| dulwich_log              | 67.9 ms                                                | 67.5 ms: 1.01x faster                                                 |
| python_startup_no_site   | 6.90 ms                                                | 6.87 ms: 1.00x faster                                                 |
| sqlglot_optimize         | 53.3 ms                                                | 53.5 ms: 1.00x slower                                                 |
| unpickle                 | 15.0 us                                                | 15.1 us: 1.01x slower                                                 |
| deepcopy                 | 355 us                                                 | 358 us: 1.01x slower                                                  |
| regex_effbot             | 3.55 ms                                                | 3.58 ms: 1.01x slower                                                 |
| pidigits                 | 187 ms                                                 | 188 ms: 1.01x slower                                                  |
| scimark_lu               | 114 ms                                                 | 115 ms: 1.01x slower                                                  |
| pycparser                | 1.15 sec                                               | 1.16 sec: 1.01x slower                                                |
| deepcopy_reduce          | 3.14 us                                                | 3.17 us: 1.01x slower                                                 |
| pprint_pformat           | 1.50 sec                                               | 1.52 sec: 1.01x slower                                                |
| xml_etree_iterparse      | 104 ms                                                 | 105 ms: 1.01x slower                                                  |
| nqueens                  | 81.1 ms                                                | 82.4 ms: 1.02x slower                                                 |
| pprint_safe_repr         | 735 ms                                                 | 748 ms: 1.02x slower                                                  |
| create_gc_cycles         | 1.52 ms                                                | 1.55 ms: 1.02x slower                                                 |
| mdp                      | 2.57 sec                                               | 2.62 sec: 1.02x slower                                                |
| unpickle_pure_python     | 218 us                                                 | 223 us: 1.02x slower                                                  |
| hexiom                   | 6.12 ms                                                | 6.27 ms: 1.02x slower                                                 |
| pathlib                  | 18.5 ms                                                | 19.0 ms: 1.02x slower                                                 |
| float                    | 80.7 ms                                                | 82.8 ms: 1.03x slower                                                 |
| xml_etree_process        | 58.6 ms                                                | 60.1 ms: 1.03x slower                                                 |
| sqlite_synth             | 2.76 us                                                | 2.84 us: 1.03x slower                                                 |
| async_tree_io            | 1.16 sec                                               | 1.19 sec: 1.03x slower                                                |
| xml_etree_generate       | 84.8 ms                                                | 88.1 ms: 1.04x slower                                                 |
| xml_etree_parse          | 154 ms                                                 | 160 ms: 1.04x slower                                                  |
| scimark_fft              | 358 ms                                                 | 373 ms: 1.04x slower                                                  |
| async_generators         | 440 ms                                                 | 459 ms: 1.04x slower                                                  |
| typing_runtime_protocols | 146 us                                                 | 152 us: 1.04x slower                                                  |
| comprehensions           | 20.4 us                                                | 21.4 us: 1.05x slower                                                 |
| meteor_contest           | 105 ms                                                 | 110 ms: 1.05x slower                                                  |
| scimark_sparse_mat_mult  | 4.74 ms                                                | 4.96 ms: 1.05x slower                                                 |
| pyflate                  | 450 ms                                                 | 472 ms: 1.05x slower                                                  |
| fannkuch                 | 387 ms                                                 | 406 ms: 1.05x slower                                                  |
| json_dumps               | 9.85 ms                                                | 10.4 ms: 1.05x slower                                                 |
| deepcopy_memo            | 37.4 us                                                | 39.5 us: 1.06x slower                                                 |
| mako                     | 10.7 ms                                                | 11.3 ms: 1.06x slower                                                 |
| python_startup           | 9.47 ms                                                | 10.1 ms: 1.06x slower                                                 |
| pickle                   | 10.6 us                                                | 11.3 us: 1.07x slower                                                 |
| unpickle_list            | 4.95 us                                                | 5.30 us: 1.07x slower                                                 |
| go                       | 136 ms                                                 | 145 ms: 1.07x slower                                                  |
| pickle_list              | 4.62 us                                                | 4.96 us: 1.08x slower                                                 |
| json                     | 4.77 ms                                                | 5.14 ms: 1.08x slower                                                 |
| spectral_norm            | 106 ms                                                 | 114 ms: 1.08x slower                                                  |
| logging_silent           | 99.1 ns                                                | 107 ns: 1.08x slower                                                  |
| nbody                    | 88.8 ms                                                | 95.8 ms: 1.08x slower                                                 |
| pickle_dict              | 31.6 us                                                | 34.8 us: 1.10x slower                                                 |
| richards                 | 43.2 ms                                                | 47.7 ms: 1.10x slower                                                 |
| richards_super           | 49.0 ms                                                | 54.9 ms: 1.12x slower                                                 |
| json_loads               | 25.2 us                                                | 28.4 us: 1.13x slower                                                 |
| gc_traversal             | 3.84 ms                                                | 4.36 ms: 1.13x slower                                                 |
| regex_v8                 | 22.3 ms                                                | 25.5 ms: 1.14x slower                                                 |
| telco                    | 6.87 ms                                                | 8.33 ms: 1.21x slower                                                 |
| Geometric mean           | (ref)                                                  | 1.02x slower                                                          |

Benchmark hidden because not significant (7): async_tree_memoization, regex_dna, coroutines, bench_mp_pool, mypy2, scimark_sor, async_tree_cpu_io_mixed
Ignored benchmarks (4) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: 2to3, dask, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 99.63% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
