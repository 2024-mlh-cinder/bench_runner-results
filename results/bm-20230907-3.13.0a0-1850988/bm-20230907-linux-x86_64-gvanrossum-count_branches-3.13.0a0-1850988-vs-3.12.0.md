
# Results vs. 3.12.0

- fork: gvanrossum
- ref: count_branches
- machine: linux-x86_64
- commit hash: 1850988
- commit date: 2023-09-07
- overall geometric mean: 1.01x faster
- HPT reliability: 99.88%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230907-linux-x86_64-gvanrossum-count_branches-3.13.0a0-1850988 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------------:|
| docutils       | 2.70 sec                                               | 2.63 sec: 1.03x faster                                              |
| tornado_http   | 99.6 ms                                                | 95.2 ms: 1.05x faster                                               |
| Geometric mean | (ref)                                                  | 1.04x faster                                                        |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230907-linux-x86_64-gvanrossum-count_branches-3.13.0a0-1850988 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------------:|
| float          | 80.7 ms                                                | 79.3 ms: 1.02x faster                                               |
| nbody          | 88.8 ms                                                | 88.1 ms: 1.01x faster                                               |
| pidigits       | 187 ms                                                 | 187 ms: 1.00x slower                                                |
| Geometric mean | (ref)                                                  | 1.01x faster                                                        |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230907-linux-x86_64-gvanrossum-count_branches-3.13.0a0-1850988 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------------:|
| regex_compile  | 144 ms                                                 | 134 ms: 1.07x faster                                                |
| regex_dna      | 209 ms                                                 | 224 ms: 1.08x slower                                                |
| regex_effbot   | 3.55 ms                                                | 3.85 ms: 1.08x slower                                               |
| regex_v8       | 22.3 ms                                                | 25.5 ms: 1.14x slower                                               |
| Geometric mean | (ref)                                                  | 1.06x slower                                                        |

Benchmarks with tag 'serialize':
================================

| Benchmark           | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230907-linux-x86_64-gvanrossum-count_branches-3.13.0a0-1850988 |
|---------------------|:------------------------------------------------------:|:-------------------------------------------------------------------:|
| tomli_loads         | 2.22 sec                                               | 2.02 sec: 1.10x faster                                              |
| pickle_pure_python  | 309 us                                                 | 292 us: 1.06x faster                                                |
| unpickle            | 15.0 us                                                | 14.3 us: 1.05x faster                                               |
| xml_etree_process   | 58.6 ms                                                | 56.2 ms: 1.04x faster                                               |
| xml_etree_generate  | 84.8 ms                                                | 81.8 ms: 1.04x faster                                               |
| unpickle_list       | 4.95 us                                                | 4.86 us: 1.02x faster                                               |
| xml_etree_iterparse | 104 ms                                                 | 102 ms: 1.01x faster                                                |
| xml_etree_parse     | 154 ms                                                 | 152 ms: 1.01x faster                                                |
| pickle_dict         | 31.6 us                                                | 32.0 us: 1.01x slower                                               |
| pickle_list         | 4.62 us                                                | 4.68 us: 1.01x slower                                               |
| Geometric mean      | (ref)                                                  | 1.02x faster                                                        |

Benchmark hidden because not significant (4): unpickle_pure_python, json_dumps, pickle, json_loads

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230907-linux-x86_64-gvanrossum-count_branches-3.13.0a0-1850988 |
|------------------------|:------------------------------------------------------:|:-------------------------------------------------------------------:|
| python_startup         | 9.47 ms                                                | 9.57 ms: 1.01x slower                                               |
| python_startup_no_site | 6.90 ms                                                | 7.04 ms: 1.02x slower                                               |
| Geometric mean         | (ref)                                                  | 1.02x slower                                                        |

Benchmarks with tag 'template':
===============================

Benchmark hidden because not significant (1): mako

All benchmarks:
===============

| Benchmark                | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230907-linux-x86_64-gvanrossum-count_branches-3.13.0a0-1850988 |
|--------------------------|:------------------------------------------------------:|:-------------------------------------------------------------------:|
| unpack_sequence          | 44.8 ns                                                | 39.8 ns: 1.13x faster                                               |
| coverage                 | 94.2 ms                                                | 85.3 ms: 1.10x faster                                               |
| crypto_pyaes             | 77.2 ms                                                | 70.0 ms: 1.10x faster                                               |
| tomli_loads              | 2.22 sec                                               | 2.02 sec: 1.10x faster                                              |
| logging_format           | 6.90 us                                                | 6.37 us: 1.08x faster                                               |
| chaos                    | 63.5 ms                                                | 58.6 ms: 1.08x faster                                               |
| raytrace                 | 294 ms                                                 | 271 ms: 1.08x faster                                                |
| asyncio_tcp              | 526 ms                                                 | 490 ms: 1.07x faster                                                |
| regex_compile            | 144 ms                                                 | 134 ms: 1.07x faster                                                |
| deltablue                | 3.52 ms                                                | 3.29 ms: 1.07x faster                                               |
| scimark_monte_carlo      | 71.0 ms                                                | 66.5 ms: 1.07x faster                                               |
| generators               | 31.1 ms                                                | 29.1 ms: 1.07x faster                                               |
| async_tree_none          | 469 ms                                                 | 440 ms: 1.07x faster                                                |
| logging_simple           | 6.18 us                                                | 5.80 us: 1.06x faster                                               |
| pickle_pure_python       | 309 us                                                 | 292 us: 1.06x faster                                                |
| unpickle                 | 15.0 us                                                | 14.3 us: 1.05x faster                                               |
| sqlglot_transpile        | 1.64 ms                                                | 1.56 ms: 1.05x faster                                               |
| sqlglot_parse            | 1.32 ms                                                | 1.26 ms: 1.05x faster                                               |
| tornado_http             | 99.6 ms                                                | 95.2 ms: 1.05x faster                                               |
| xml_etree_process        | 58.6 ms                                                | 56.2 ms: 1.04x faster                                               |
| hexiom                   | 6.12 ms                                                | 5.89 ms: 1.04x faster                                               |
| xml_etree_generate       | 84.8 ms                                                | 81.8 ms: 1.04x faster                                               |
| sqlglot_normalize        | 107 ms                                                 | 104 ms: 1.04x faster                                                |
| nqueens                  | 81.1 ms                                                | 78.4 ms: 1.03x faster                                               |
| docutils                 | 2.70 sec                                               | 2.63 sec: 1.03x faster                                              |
| dulwich_log              | 67.9 ms                                                | 66.2 ms: 1.03x faster                                               |
| deepcopy                 | 355 us                                                 | 346 us: 1.03x faster                                                |
| scimark_sor              | 125 ms                                                 | 121 ms: 1.03x faster                                                |
| scimark_sparse_mat_mult  | 4.74 ms                                                | 4.63 ms: 1.03x faster                                               |
| pprint_safe_repr         | 735 ms                                                 | 719 ms: 1.02x faster                                                |
| pprint_pformat           | 1.50 sec                                               | 1.47 sec: 1.02x faster                                              |
| mypy2                    | 344 ms                                                 | 336 ms: 1.02x faster                                                |
| spectral_norm            | 106 ms                                                 | 104 ms: 1.02x faster                                                |
| sqlglot_optimize         | 53.3 ms                                                | 52.2 ms: 1.02x faster                                               |
| coroutines               | 22.4 ms                                                | 22.0 ms: 1.02x faster                                               |
| float                    | 80.7 ms                                                | 79.3 ms: 1.02x faster                                               |
| scimark_lu               | 114 ms                                                 | 112 ms: 1.02x faster                                                |
| bench_thread_pool        | 827 us                                                 | 812 us: 1.02x faster                                                |
| deepcopy_reduce          | 3.14 us                                                | 3.08 us: 1.02x faster                                               |
| unpickle_list            | 4.95 us                                                | 4.86 us: 1.02x faster                                               |
| async_tree_cpu_io_mixed  | 714 ms                                                 | 704 ms: 1.01x faster                                                |
| sqlite_synth             | 2.76 us                                                | 2.72 us: 1.01x faster                                               |
| xml_etree_iterparse      | 104 ms                                                 | 102 ms: 1.01x faster                                                |
| fannkuch                 | 387 ms                                                 | 383 ms: 1.01x faster                                                |
| xml_etree_parse          | 154 ms                                                 | 152 ms: 1.01x faster                                                |
| create_gc_cycles         | 1.52 ms                                                | 1.51 ms: 1.01x faster                                               |
| nbody                    | 88.8 ms                                                | 88.1 ms: 1.01x faster                                               |
| pyflate                  | 450 ms                                                 | 449 ms: 1.00x faster                                                |
| gc_traversal             | 3.84 ms                                                | 3.83 ms: 1.00x faster                                               |
| pidigits                 | 187 ms                                                 | 187 ms: 1.00x slower                                                |
| async_generators         | 440 ms                                                 | 443 ms: 1.01x slower                                                |
| deepcopy_memo            | 37.4 us                                                | 37.7 us: 1.01x slower                                               |
| comprehensions           | 20.4 us                                                | 20.6 us: 1.01x slower                                               |
| python_startup           | 9.47 ms                                                | 9.57 ms: 1.01x slower                                               |
| pickle_dict              | 31.6 us                                                | 32.0 us: 1.01x slower                                               |
| pickle_list              | 4.62 us                                                | 4.68 us: 1.01x slower                                               |
| logging_silent           | 99.1 ns                                                | 101 ns: 1.02x slower                                                |
| meteor_contest           | 105 ms                                                 | 107 ms: 1.02x slower                                                |
| python_startup_no_site   | 6.90 ms                                                | 7.04 ms: 1.02x slower                                               |
| typing_runtime_protocols | 146 us                                                 | 149 us: 1.02x slower                                                |
| go                       | 136 ms                                                 | 139 ms: 1.03x slower                                                |
| async_tree_io            | 1.16 sec                                               | 1.19 sec: 1.03x slower                                              |
| pycparser                | 1.15 sec                                               | 1.20 sec: 1.05x slower                                              |
| json                     | 4.77 ms                                                | 5.01 ms: 1.05x slower                                               |
| mdp                      | 2.57 sec                                               | 2.73 sec: 1.06x slower                                              |
| regex_dna                | 209 ms                                                 | 224 ms: 1.08x slower                                                |
| richards                 | 43.2 ms                                                | 46.7 ms: 1.08x slower                                               |
| regex_effbot             | 3.55 ms                                                | 3.85 ms: 1.08x slower                                               |
| richards_super           | 49.0 ms                                                | 53.9 ms: 1.10x slower                                               |
| regex_v8                 | 22.3 ms                                                | 25.5 ms: 1.14x slower                                               |
| telco                    | 6.87 ms                                                | 7.94 ms: 1.16x slower                                               |
| dask                     | 365 ms                                                 | 521 ms: 1.43x slower                                                |
| Geometric mean           | (ref)                                                  | 1.01x faster                                                        |

Benchmark hidden because not significant (10): async_tree_memoization, pathlib, unpickle_pure_python, json_dumps, scimark_fft, mako, asyncio_tcp_ssl, bench_mp_pool, pickle, json_loads
Ignored benchmarks (3) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: 2to3, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 99.88% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
