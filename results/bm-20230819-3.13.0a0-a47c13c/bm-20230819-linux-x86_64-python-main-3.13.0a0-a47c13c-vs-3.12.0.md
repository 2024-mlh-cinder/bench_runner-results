
# Results vs. 3.12.0

- fork: python
- ref: main
- machine: linux-x86_64
- commit hash: a47c13c
- commit date: 2023-08-19
- overall geometric mean: 1.00x faster
- HPT reliability: 99.79%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230819-linux-x86_64-python-main-3.13.0a0-a47c13c |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| docutils       | 2.70 sec                                               | 2.62 sec: 1.03x faster                                |
| tornado_http   | 99.6 ms                                                | 95.9 ms: 1.04x faster                                 |
| Geometric mean | (ref)                                                  | 1.03x faster                                          |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230819-linux-x86_64-python-main-3.13.0a0-a47c13c |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| float          | 80.7 ms                                                | 79.7 ms: 1.01x faster                                 |
| nbody          | 88.8 ms                                                | 90.9 ms: 1.02x slower                                 |
| pidigits       | 187 ms                                                 | 201 ms: 1.08x slower                                  |
| Geometric mean | (ref)                                                  | 1.03x slower                                          |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230819-linux-x86_64-python-main-3.13.0a0-a47c13c |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| regex_compile  | 144 ms                                                 | 136 ms: 1.06x faster                                  |
| regex_dna      | 209 ms                                                 | 215 ms: 1.03x slower                                  |
| regex_v8       | 22.3 ms                                                | 24.7 ms: 1.10x slower                                 |
| Geometric mean | (ref)                                                  | 1.02x slower                                          |

Benchmark hidden because not significant (1): regex_effbot

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230819-linux-x86_64-python-main-3.13.0a0-a47c13c |
|----------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| tomli_loads          | 2.22 sec                                               | 2.10 sec: 1.05x faster                                |
| unpickle             | 15.0 us                                                | 14.2 us: 1.05x faster                                 |
| pickle_pure_python   | 309 us                                                 | 303 us: 1.02x faster                                  |
| xml_etree_generate   | 84.8 ms                                                | 83.2 ms: 1.02x faster                                 |
| unpickle_pure_python | 218 us                                                 | 215 us: 1.01x faster                                  |
| unpickle_list        | 4.95 us                                                | 4.88 us: 1.01x faster                                 |
| xml_etree_iterparse  | 104 ms                                                 | 102 ms: 1.01x faster                                  |
| xml_etree_parse      | 154 ms                                                 | 152 ms: 1.01x faster                                  |
| pickle_dict          | 31.6 us                                                | 31.4 us: 1.01x faster                                 |
| xml_etree_process    | 58.6 ms                                                | 58.2 ms: 1.01x faster                                 |
| json_loads           | 25.2 us                                                | 25.7 us: 1.02x slower                                 |
| Geometric mean       | (ref)                                                  | 1.01x faster                                          |

Benchmark hidden because not significant (3): json_dumps, pickle_list, pickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230819-linux-x86_64-python-main-3.13.0a0-a47c13c |
|------------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| python_startup         | 9.47 ms                                                | 9.34 ms: 1.01x faster                                 |
| python_startup_no_site | 6.90 ms                                                | 6.85 ms: 1.01x faster                                 |
| Geometric mean         | (ref)                                                  | 1.01x faster                                          |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230819-linux-x86_64-python-main-3.13.0a0-a47c13c |
|-----------|:------------------------------------------------------:|:-----------------------------------------------------:|
| mako      | 10.7 ms                                                | 10.8 ms: 1.01x slower                                 |

All benchmarks:
===============

| Benchmark                | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230819-linux-x86_64-python-main-3.13.0a0-a47c13c |
|--------------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| coverage                 | 94.2 ms                                                | 84.7 ms: 1.11x faster                                 |
| crypto_pyaes             | 77.2 ms                                                | 70.1 ms: 1.10x faster                                 |
| asyncio_tcp              | 526 ms                                                 | 487 ms: 1.08x faster                                  |
| async_tree_none          | 469 ms                                                 | 439 ms: 1.07x faster                                  |
| raytrace                 | 294 ms                                                 | 275 ms: 1.07x faster                                  |
| generators               | 31.1 ms                                                | 29.2 ms: 1.06x faster                                 |
| chaos                    | 63.5 ms                                                | 59.8 ms: 1.06x faster                                 |
| deltablue                | 3.52 ms                                                | 3.32 ms: 1.06x faster                                 |
| regex_compile            | 144 ms                                                 | 136 ms: 1.06x faster                                  |
| logging_format           | 6.90 us                                                | 6.53 us: 1.06x faster                                 |
| scimark_monte_carlo      | 71.0 ms                                                | 67.2 ms: 1.06x faster                                 |
| tomli_loads              | 2.22 sec                                               | 2.10 sec: 1.05x faster                                |
| unpickle                 | 15.0 us                                                | 14.2 us: 1.05x faster                                 |
| scimark_sparse_mat_mult  | 4.74 ms                                                | 4.53 ms: 1.05x faster                                 |
| logging_simple           | 6.18 us                                                | 5.90 us: 1.05x faster                                 |
| tornado_http             | 99.6 ms                                                | 95.9 ms: 1.04x faster                                 |
| scimark_lu               | 114 ms                                                 | 110 ms: 1.03x faster                                  |
| docutils                 | 2.70 sec                                               | 2.62 sec: 1.03x faster                                |
| sqlglot_parse            | 1.32 ms                                                | 1.28 ms: 1.03x faster                                 |
| sqlglot_transpile        | 1.64 ms                                                | 1.60 ms: 1.03x faster                                 |
| async_tree_memoization   | 573 ms                                                 | 560 ms: 1.02x faster                                  |
| unpack_sequence          | 44.8 ns                                                | 43.8 ns: 1.02x faster                                 |
| dulwich_log              | 67.9 ms                                                | 66.4 ms: 1.02x faster                                 |
| scimark_sor              | 125 ms                                                 | 122 ms: 1.02x faster                                  |
| nqueens                  | 81.1 ms                                                | 79.5 ms: 1.02x faster                                 |
| pickle_pure_python       | 309 us                                                 | 303 us: 1.02x faster                                  |
| async_tree_cpu_io_mixed  | 714 ms                                                 | 701 ms: 1.02x faster                                  |
| xml_etree_generate       | 84.8 ms                                                | 83.2 ms: 1.02x faster                                 |
| unpickle_pure_python     | 218 us                                                 | 215 us: 1.01x faster                                  |
| python_startup           | 9.47 ms                                                | 9.34 ms: 1.01x faster                                 |
| unpickle_list            | 4.95 us                                                | 4.88 us: 1.01x faster                                 |
| sqlglot_normalize        | 107 ms                                                 | 106 ms: 1.01x faster                                  |
| xml_etree_iterparse      | 104 ms                                                 | 102 ms: 1.01x faster                                  |
| float                    | 80.7 ms                                                | 79.7 ms: 1.01x faster                                 |
| deepcopy                 | 355 us                                                 | 351 us: 1.01x faster                                  |
| deepcopy_reduce          | 3.14 us                                                | 3.10 us: 1.01x faster                                 |
| scimark_fft              | 358 ms                                                 | 354 ms: 1.01x faster                                  |
| sqlglot_optimize         | 53.3 ms                                                | 52.7 ms: 1.01x faster                                 |
| bench_thread_pool        | 827 us                                                 | 818 us: 1.01x faster                                  |
| xml_etree_parse          | 154 ms                                                 | 152 ms: 1.01x faster                                  |
| create_gc_cycles         | 1.52 ms                                                | 1.51 ms: 1.01x faster                                 |
| mdp                      | 2.57 sec                                               | 2.54 sec: 1.01x faster                                |
| pickle_dict              | 31.6 us                                                | 31.4 us: 1.01x faster                                 |
| python_startup_no_site   | 6.90 ms                                                | 6.85 ms: 1.01x faster                                 |
| asyncio_tcp_ssl          | 1.79 sec                                               | 1.78 sec: 1.01x faster                                |
| xml_etree_process        | 58.6 ms                                                | 58.2 ms: 1.01x faster                                 |
| typing_runtime_protocols | 146 us                                                 | 145 us: 1.01x faster                                  |
| fannkuch                 | 387 ms                                                 | 385 ms: 1.01x faster                                  |
| hexiom                   | 6.12 ms                                                | 6.11 ms: 1.00x faster                                 |
| pyflate                  | 450 ms                                                 | 452 ms: 1.00x slower                                  |
| mako                     | 10.7 ms                                                | 10.8 ms: 1.01x slower                                 |
| meteor_contest           | 105 ms                                                 | 106 ms: 1.01x slower                                  |
| async_generators         | 440 ms                                                 | 447 ms: 1.01x slower                                  |
| json_loads               | 25.2 us                                                | 25.7 us: 1.02x slower                                 |
| json                     | 4.77 ms                                                | 4.86 ms: 1.02x slower                                 |
| comprehensions           | 20.4 us                                                | 20.9 us: 1.02x slower                                 |
| gc_traversal             | 3.84 ms                                                | 3.93 ms: 1.02x slower                                 |
| nbody                    | 88.8 ms                                                | 90.9 ms: 1.02x slower                                 |
| async_tree_io            | 1.16 sec                                               | 1.19 sec: 1.03x slower                                |
| regex_dna                | 209 ms                                                 | 215 ms: 1.03x slower                                  |
| pycparser                | 1.15 sec                                               | 1.20 sec: 1.04x slower                                |
| logging_silent           | 99.1 ns                                                | 104 ns: 1.04x slower                                  |
| go                       | 136 ms                                                 | 142 ms: 1.05x slower                                  |
| pidigits                 | 187 ms                                                 | 201 ms: 1.08x slower                                  |
| regex_v8                 | 22.3 ms                                                | 24.7 ms: 1.10x slower                                 |
| richards                 | 43.2 ms                                                | 47.7 ms: 1.11x slower                                 |
| richards_super           | 49.0 ms                                                | 54.2 ms: 1.11x slower                                 |
| telco                    | 6.87 ms                                                | 7.98 ms: 1.16x slower                                 |
| mypy2                    | 344 ms                                                 | 456 ms: 1.33x slower                                  |
| dask                     | 365 ms                                                 | 524 ms: 1.44x slower                                  |
| Geometric mean           | (ref)                                                  | 1.00x faster                                          |

Benchmark hidden because not significant (12): coroutines, sqlite_synth, pprint_safe_repr, pprint_pformat, bench_mp_pool, json_dumps, spectral_norm, deepcopy_memo, pickle_list, pathlib, regex_effbot, pickle
Ignored benchmarks (3) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: 2to3, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 99.79% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
