
# Results vs. 3.12.0

- fork: gvanrossum
- ref: call_uops
- machine: linux-x86_64
- commit hash: 05af848
- commit date: 2023-08-16
- overall geometric mean: 1.00x faster
- HPT reliability: 99.68%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230816-linux-x86_64-gvanrossum-call_uops-3.13.0a0-05af848 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| docutils       | 2.70 sec                                               | 2.63 sec: 1.03x faster                                         |
| tornado_http   | 99.6 ms                                                | 95.1 ms: 1.05x faster                                          |
| Geometric mean | (ref)                                                  | 1.04x faster                                                   |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230816-linux-x86_64-gvanrossum-call_uops-3.13.0a0-05af848 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| float          | 80.7 ms                                                | 79.8 ms: 1.01x faster                                          |
| nbody          | 88.8 ms                                                | 88.3 ms: 1.01x faster                                          |
| pidigits       | 187 ms                                                 | 189 ms: 1.01x slower                                           |
| Geometric mean | (ref)                                                  | 1.00x faster                                                   |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230816-linux-x86_64-gvanrossum-call_uops-3.13.0a0-05af848 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| regex_compile  | 144 ms                                                 | 136 ms: 1.06x faster                                           |
| regex_dna      | 209 ms                                                 | 217 ms: 1.04x slower                                           |
| regex_v8       | 22.3 ms                                                | 23.5 ms: 1.05x slower                                          |
| regex_effbot   | 3.55 ms                                                | 3.74 ms: 1.06x slower                                          |
| Geometric mean | (ref)                                                  | 1.02x slower                                                   |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230816-linux-x86_64-gvanrossum-call_uops-3.13.0a0-05af848 |
|----------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| tomli_loads          | 2.22 sec                                               | 2.10 sec: 1.06x faster                                         |
| unpickle             | 15.0 us                                                | 14.3 us: 1.05x faster                                          |
| pickle_pure_python   | 309 us                                                 | 295 us: 1.05x faster                                           |
| unpickle_pure_python | 218 us                                                 | 211 us: 1.03x faster                                           |
| xml_etree_generate   | 84.8 ms                                                | 82.9 ms: 1.02x faster                                          |
| xml_etree_process    | 58.6 ms                                                | 57.6 ms: 1.02x faster                                          |
| xml_etree_iterparse  | 104 ms                                                 | 102 ms: 1.02x faster                                           |
| xml_etree_parse      | 154 ms                                                 | 152 ms: 1.01x faster                                           |
| json_dumps           | 9.85 ms                                                | 9.78 ms: 1.01x faster                                          |
| pickle               | 10.6 us                                                | 10.6 us: 1.00x faster                                          |
| pickle_dict          | 31.6 us                                                | 32.0 us: 1.01x slower                                          |
| pickle_list          | 4.62 us                                                | 4.72 us: 1.02x slower                                          |
| unpickle_list        | 4.95 us                                                | 5.12 us: 1.04x slower                                          |
| Geometric mean       | (ref)                                                  | 1.01x faster                                                   |

Benchmark hidden because not significant (1): json_loads

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230816-linux-x86_64-gvanrossum-call_uops-3.13.0a0-05af848 |
|------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| python_startup         | 9.47 ms                                                | 9.36 ms: 1.01x faster                                          |
| python_startup_no_site | 6.90 ms                                                | 6.86 ms: 1.01x faster                                          |
| Geometric mean         | (ref)                                                  | 1.01x faster                                                   |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230816-linux-x86_64-gvanrossum-call_uops-3.13.0a0-05af848 |
|-----------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| mako      | 10.7 ms                                                | 10.9 ms: 1.02x slower                                          |

All benchmarks:
===============

| Benchmark                | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230816-linux-x86_64-gvanrossum-call_uops-3.13.0a0-05af848 |
|--------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| coverage                 | 94.2 ms                                                | 84.6 ms: 1.11x faster                                          |
| crypto_pyaes             | 77.2 ms                                                | 69.6 ms: 1.11x faster                                          |
| generators               | 31.1 ms                                                | 28.3 ms: 1.10x faster                                          |
| logging_format           | 6.90 us                                                | 6.41 us: 1.08x faster                                          |
| asyncio_tcp              | 526 ms                                                 | 488 ms: 1.08x faster                                           |
| scimark_monte_carlo      | 71.0 ms                                                | 66.0 ms: 1.08x faster                                          |
| async_tree_none          | 469 ms                                                 | 437 ms: 1.07x faster                                           |
| deltablue                | 3.52 ms                                                | 3.29 ms: 1.07x faster                                          |
| raytrace                 | 294 ms                                                 | 276 ms: 1.06x faster                                           |
| logging_simple           | 6.18 us                                                | 5.81 us: 1.06x faster                                          |
| regex_compile            | 144 ms                                                 | 136 ms: 1.06x faster                                           |
| tomli_loads              | 2.22 sec                                               | 2.10 sec: 1.06x faster                                         |
| chaos                    | 63.5 ms                                                | 60.2 ms: 1.06x faster                                          |
| unpack_sequence          | 44.8 ns                                                | 42.7 ns: 1.05x faster                                          |
| tornado_http             | 99.6 ms                                                | 95.1 ms: 1.05x faster                                          |
| unpickle                 | 15.0 us                                                | 14.3 us: 1.05x faster                                          |
| pickle_pure_python       | 309 us                                                 | 295 us: 1.05x faster                                           |
| sqlglot_parse            | 1.32 ms                                                | 1.28 ms: 1.03x faster                                          |
| unpickle_pure_python     | 218 us                                                 | 211 us: 1.03x faster                                           |
| dulwich_log              | 67.9 ms                                                | 65.8 ms: 1.03x faster                                          |
| nqueens                  | 81.1 ms                                                | 78.9 ms: 1.03x faster                                          |
| docutils                 | 2.70 sec                                               | 2.63 sec: 1.03x faster                                         |
| typing_runtime_protocols | 146 us                                                 | 142 us: 1.03x faster                                           |
| create_gc_cycles         | 1.52 ms                                                | 1.48 ms: 1.03x faster                                          |
| sqlglot_normalize        | 107 ms                                                 | 105 ms: 1.02x faster                                           |
| xml_etree_generate       | 84.8 ms                                                | 82.9 ms: 1.02x faster                                          |
| sqlglot_transpile        | 1.64 ms                                                | 1.61 ms: 1.02x faster                                          |
| pprint_safe_repr         | 735 ms                                                 | 721 ms: 1.02x faster                                           |
| scimark_sor              | 125 ms                                                 | 122 ms: 1.02x faster                                           |
| deepcopy                 | 355 us                                                 | 349 us: 1.02x faster                                           |
| async_tree_memoization   | 573 ms                                                 | 563 ms: 1.02x faster                                           |
| async_tree_cpu_io_mixed  | 714 ms                                                 | 702 ms: 1.02x faster                                           |
| xml_etree_process        | 58.6 ms                                                | 57.6 ms: 1.02x faster                                          |
| scimark_lu               | 114 ms                                                 | 112 ms: 1.02x faster                                           |
| xml_etree_iterparse      | 104 ms                                                 | 102 ms: 1.02x faster                                           |
| hexiom                   | 6.12 ms                                                | 6.03 ms: 1.02x faster                                          |
| sqlite_synth             | 2.76 us                                                | 2.72 us: 1.01x faster                                          |
| bench_thread_pool        | 827 us                                                 | 815 us: 1.01x faster                                           |
| xml_etree_parse          | 154 ms                                                 | 152 ms: 1.01x faster                                           |
| sqlglot_optimize         | 53.3 ms                                                | 52.6 ms: 1.01x faster                                          |
| pprint_pformat           | 1.50 sec                                               | 1.48 sec: 1.01x faster                                         |
| coroutines               | 22.4 ms                                                | 22.2 ms: 1.01x faster                                          |
| float                    | 80.7 ms                                                | 79.8 ms: 1.01x faster                                          |
| python_startup           | 9.47 ms                                                | 9.36 ms: 1.01x faster                                          |
| deepcopy_memo            | 37.4 us                                                | 37.0 us: 1.01x faster                                          |
| scimark_fft              | 358 ms                                                 | 355 ms: 1.01x faster                                           |
| pyflate                  | 450 ms                                                 | 446 ms: 1.01x faster                                           |
| mdp                      | 2.57 sec                                               | 2.54 sec: 1.01x faster                                         |
| json_dumps               | 9.85 ms                                                | 9.78 ms: 1.01x faster                                          |
| nbody                    | 88.8 ms                                                | 88.3 ms: 1.01x faster                                          |
| python_startup_no_site   | 6.90 ms                                                | 6.86 ms: 1.01x faster                                          |
| pickle                   | 10.6 us                                                | 10.6 us: 1.00x faster                                          |
| comprehensions           | 20.4 us                                                | 20.4 us: 1.00x faster                                          |
| asyncio_tcp_ssl          | 1.79 sec                                               | 1.79 sec: 1.00x faster                                         |
| meteor_contest           | 105 ms                                                 | 105 ms: 1.00x slower                                           |
| pathlib                  | 18.5 ms                                                | 18.6 ms: 1.00x slower                                          |
| fannkuch                 | 387 ms                                                 | 390 ms: 1.01x slower                                           |
| spectral_norm            | 106 ms                                                 | 107 ms: 1.01x slower                                           |
| pidigits                 | 187 ms                                                 | 189 ms: 1.01x slower                                           |
| pickle_dict              | 31.6 us                                                | 32.0 us: 1.01x slower                                          |
| mako                     | 10.7 ms                                                | 10.9 ms: 1.02x slower                                          |
| pickle_list              | 4.62 us                                                | 4.72 us: 1.02x slower                                          |
| async_generators         | 440 ms                                                 | 452 ms: 1.03x slower                                           |
| go                       | 136 ms                                                 | 140 ms: 1.03x slower                                           |
| async_tree_io            | 1.16 sec                                               | 1.19 sec: 1.03x slower                                         |
| json                     | 4.77 ms                                                | 4.92 ms: 1.03x slower                                          |
| unpickle_list            | 4.95 us                                                | 5.12 us: 1.04x slower                                          |
| regex_dna                | 209 ms                                                 | 217 ms: 1.04x slower                                           |
| scimark_sparse_mat_mult  | 4.74 ms                                                | 4.94 ms: 1.04x slower                                          |
| logging_silent           | 99.1 ns                                                | 104 ns: 1.04x slower                                           |
| pycparser                | 1.15 sec                                               | 1.21 sec: 1.05x slower                                         |
| regex_v8                 | 22.3 ms                                                | 23.5 ms: 1.05x slower                                          |
| regex_effbot             | 3.55 ms                                                | 3.74 ms: 1.06x slower                                          |
| gc_traversal             | 3.84 ms                                                | 4.06 ms: 1.06x slower                                          |
| richards                 | 43.2 ms                                                | 48.0 ms: 1.11x slower                                          |
| richards_super           | 49.0 ms                                                | 54.4 ms: 1.11x slower                                          |
| telco                    | 6.87 ms                                                | 8.08 ms: 1.18x slower                                          |
| mypy2                    | 344 ms                                                 | 455 ms: 1.32x slower                                           |
| dask                     | 365 ms                                                 | 519 ms: 1.42x slower                                           |
| Geometric mean           | (ref)                                                  | 1.00x faster                                                   |

Benchmark hidden because not significant (3): json_loads, bench_mp_pool, deepcopy_reduce
Ignored benchmarks (3) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: 2to3, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 99.68% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
