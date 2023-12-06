
# Results vs. 3.12.0

- fork: python
- ref: c1e2f3b2f70b8a72ea7e
- machine: linux-x86_64
- commit hash: c1e2f3b
- commit date: 2023-08-31
- overall geometric mean: 1.00x faster
- HPT reliability: 85.35%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230831-linux-x86_64-python-c1e2f3b2f70b8a72ea7e-3.13.0a0-c1e2f3b |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| docutils       | 2.70 sec                                               | 2.62 sec: 1.03x faster                                                |
| tornado_http   | 99.6 ms                                                | 95.7 ms: 1.04x faster                                                 |
| Geometric mean | (ref)                                                  | 1.04x faster                                                          |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230831-linux-x86_64-python-c1e2f3b2f70b8a72ea7e-3.13.0a0-c1e2f3b |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| float          | 80.7 ms                                                | 78.7 ms: 1.03x faster                                                 |
| pidigits       | 187 ms                                                 | 189 ms: 1.01x slower                                                  |
| nbody          | 88.8 ms                                                | 91.1 ms: 1.03x slower                                                 |
| Geometric mean | (ref)                                                  | 1.00x slower                                                          |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230831-linux-x86_64-python-c1e2f3b2f70b8a72ea7e-3.13.0a0-c1e2f3b |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| regex_compile  | 144 ms                                                 | 136 ms: 1.06x faster                                                  |
| regex_effbot   | 3.55 ms                                                | 3.60 ms: 1.01x slower                                                 |
| regex_dna      | 209 ms                                                 | 214 ms: 1.03x slower                                                  |
| regex_v8       | 22.3 ms                                                | 24.9 ms: 1.11x slower                                                 |
| Geometric mean | (ref)                                                  | 1.02x slower                                                          |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230831-linux-x86_64-python-c1e2f3b2f70b8a72ea7e-3.13.0a0-c1e2f3b |
|----------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| tomli_loads          | 2.22 sec                                               | 2.12 sec: 1.05x faster                                                |
| pickle_pure_python   | 309 us                                                 | 299 us: 1.03x faster                                                  |
| xml_etree_generate   | 84.8 ms                                                | 82.4 ms: 1.03x faster                                                 |
| xml_etree_process    | 58.6 ms                                                | 57.5 ms: 1.02x faster                                                 |
| unpickle_pure_python | 218 us                                                 | 214 us: 1.02x faster                                                  |
| xml_etree_iterparse  | 104 ms                                                 | 102 ms: 1.01x faster                                                  |
| pickle_dict          | 31.6 us                                                | 31.9 us: 1.01x slower                                                 |
| json_dumps           | 9.85 ms                                                | 9.96 ms: 1.01x slower                                                 |
| unpickle_list        | 4.95 us                                                | 5.01 us: 1.01x slower                                                 |
| Geometric mean       | (ref)                                                  | 1.01x faster                                                          |

Benchmark hidden because not significant (5): unpickle, pickle, xml_etree_parse, json_loads, pickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230831-linux-x86_64-python-c1e2f3b2f70b8a72ea7e-3.13.0a0-c1e2f3b |
|------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| python_startup         | 9.47 ms                                                | 9.52 ms: 1.01x slower                                                 |
| python_startup_no_site | 6.90 ms                                                | 6.97 ms: 1.01x slower                                                 |
| Geometric mean         | (ref)                                                  | 1.01x slower                                                          |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230831-linux-x86_64-python-c1e2f3b2f70b8a72ea7e-3.13.0a0-c1e2f3b |
|-----------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| mako      | 10.7 ms                                                | 10.8 ms: 1.01x slower                                                 |

All benchmarks:
===============

| Benchmark                | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230831-linux-x86_64-python-c1e2f3b2f70b8a72ea7e-3.13.0a0-c1e2f3b |
|--------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| crypto_pyaes             | 77.2 ms                                                | 68.6 ms: 1.12x faster                                                 |
| coverage                 | 94.2 ms                                                | 86.9 ms: 1.08x faster                                                 |
| generators               | 31.1 ms                                                | 28.8 ms: 1.08x faster                                                 |
| deltablue                | 3.52 ms                                                | 3.26 ms: 1.08x faster                                                 |
| asyncio_tcp              | 526 ms                                                 | 490 ms: 1.07x faster                                                  |
| scimark_monte_carlo      | 71.0 ms                                                | 66.2 ms: 1.07x faster                                                 |
| raytrace                 | 294 ms                                                 | 275 ms: 1.07x faster                                                  |
| logging_format           | 6.90 us                                                | 6.46 us: 1.07x faster                                                 |
| async_tree_none          | 469 ms                                                 | 440 ms: 1.07x faster                                                  |
| regex_compile            | 144 ms                                                 | 136 ms: 1.06x faster                                                  |
| chaos                    | 63.5 ms                                                | 60.3 ms: 1.05x faster                                                 |
| gc_traversal             | 3.84 ms                                                | 3.66 ms: 1.05x faster                                                 |
| tomli_loads              | 2.22 sec                                               | 2.12 sec: 1.05x faster                                                |
| logging_simple           | 6.18 us                                                | 5.93 us: 1.04x faster                                                 |
| typing_runtime_protocols | 146 us                                                 | 140 us: 1.04x faster                                                  |
| tornado_http             | 99.6 ms                                                | 95.7 ms: 1.04x faster                                                 |
| sqlglot_transpile        | 1.64 ms                                                | 1.58 ms: 1.04x faster                                                 |
| create_gc_cycles         | 1.52 ms                                                | 1.47 ms: 1.03x faster                                                 |
| sqlglot_parse            | 1.32 ms                                                | 1.28 ms: 1.03x faster                                                 |
| pickle_pure_python       | 309 us                                                 | 299 us: 1.03x faster                                                  |
| spectral_norm            | 106 ms                                                 | 103 ms: 1.03x faster                                                  |
| docutils                 | 2.70 sec                                               | 2.62 sec: 1.03x faster                                                |
| dulwich_log              | 67.9 ms                                                | 66.0 ms: 1.03x faster                                                 |
| xml_etree_generate       | 84.8 ms                                                | 82.4 ms: 1.03x faster                                                 |
| float                    | 80.7 ms                                                | 78.7 ms: 1.03x faster                                                 |
| scimark_sor              | 125 ms                                                 | 121 ms: 1.03x faster                                                  |
| scimark_lu               | 114 ms                                                 | 112 ms: 1.02x faster                                                  |
| xml_etree_process        | 58.6 ms                                                | 57.5 ms: 1.02x faster                                                 |
| scimark_fft              | 358 ms                                                 | 352 ms: 1.02x faster                                                  |
| unpickle_pure_python     | 218 us                                                 | 214 us: 1.02x faster                                                  |
| bench_thread_pool        | 827 us                                                 | 813 us: 1.02x faster                                                  |
| hexiom                   | 6.12 ms                                                | 6.01 ms: 1.02x faster                                                 |
| coroutines               | 22.4 ms                                                | 22.1 ms: 1.02x faster                                                 |
| async_tree_cpu_io_mixed  | 714 ms                                                 | 702 ms: 1.02x faster                                                  |
| deepcopy                 | 355 us                                                 | 350 us: 1.02x faster                                                  |
| sqlite_synth             | 2.76 us                                                | 2.72 us: 1.01x faster                                                 |
| xml_etree_iterparse      | 104 ms                                                 | 102 ms: 1.01x faster                                                  |
| sqlglot_normalize        | 107 ms                                                 | 106 ms: 1.01x faster                                                  |
| pyflate                  | 450 ms                                                 | 444 ms: 1.01x faster                                                  |
| mypy2                    | 344 ms                                                 | 340 ms: 1.01x faster                                                  |
| nqueens                  | 81.1 ms                                                | 80.4 ms: 1.01x faster                                                 |
| asyncio_tcp_ssl          | 1.79 sec                                               | 1.80 sec: 1.00x slower                                                |
| pathlib                  | 18.5 ms                                                | 18.6 ms: 1.00x slower                                                 |
| pprint_pformat           | 1.50 sec                                               | 1.51 sec: 1.00x slower                                                |
| python_startup           | 9.47 ms                                                | 9.52 ms: 1.01x slower                                                 |
| deepcopy_memo            | 37.4 us                                                | 37.7 us: 1.01x slower                                                 |
| pprint_safe_repr         | 735 ms                                                 | 741 ms: 1.01x slower                                                  |
| deepcopy_reduce          | 3.14 us                                                | 3.17 us: 1.01x slower                                                 |
| pickle_dict              | 31.6 us                                                | 31.9 us: 1.01x slower                                                 |
| mako                     | 10.7 ms                                                | 10.8 ms: 1.01x slower                                                 |
| python_startup_no_site   | 6.90 ms                                                | 6.97 ms: 1.01x slower                                                 |
| json_dumps               | 9.85 ms                                                | 9.96 ms: 1.01x slower                                                 |
| pidigits                 | 187 ms                                                 | 189 ms: 1.01x slower                                                  |
| unpickle_list            | 4.95 us                                                | 5.01 us: 1.01x slower                                                 |
| regex_effbot             | 3.55 ms                                                | 3.60 ms: 1.01x slower                                                 |
| pycparser                | 1.15 sec                                               | 1.17 sec: 1.02x slower                                                |
| meteor_contest           | 105 ms                                                 | 107 ms: 1.02x slower                                                  |
| comprehensions           | 20.4 us                                                | 20.8 us: 1.02x slower                                                 |
| async_generators         | 440 ms                                                 | 448 ms: 1.02x slower                                                  |
| fannkuch                 | 387 ms                                                 | 396 ms: 1.02x slower                                                  |
| go                       | 136 ms                                                 | 139 ms: 1.03x slower                                                  |
| nbody                    | 88.8 ms                                                | 91.1 ms: 1.03x slower                                                 |
| regex_dna                | 209 ms                                                 | 214 ms: 1.03x slower                                                  |
| json                     | 4.77 ms                                                | 4.91 ms: 1.03x slower                                                 |
| async_tree_io            | 1.16 sec                                               | 1.19 sec: 1.03x slower                                                |
| logging_silent           | 99.1 ns                                                | 103 ns: 1.04x slower                                                  |
| mdp                      | 2.57 sec                                               | 2.73 sec: 1.06x slower                                                |
| richards                 | 43.2 ms                                                | 47.2 ms: 1.09x slower                                                 |
| richards_super           | 49.0 ms                                                | 53.9 ms: 1.10x slower                                                 |
| regex_v8                 | 22.3 ms                                                | 24.9 ms: 1.11x slower                                                 |
| unpack_sequence          | 44.8 ns                                                | 51.5 ns: 1.15x slower                                                 |
| telco                    | 6.87 ms                                                | 8.01 ms: 1.16x slower                                                 |
| dask                     | 365 ms                                                 | 524 ms: 1.44x slower                                                  |
| Geometric mean           | (ref)                                                  | 1.00x faster                                                          |

Benchmark hidden because not significant (9): unpickle, async_tree_memoization, scimark_sparse_mat_mult, pickle, bench_mp_pool, xml_etree_parse, sqlglot_optimize, json_loads, pickle_list
Ignored benchmarks (3) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: 2to3, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 85.35% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
