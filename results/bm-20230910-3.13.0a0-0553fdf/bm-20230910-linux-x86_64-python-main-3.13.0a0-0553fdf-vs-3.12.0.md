
# Results vs. 3.12.0

- fork: python
- ref: main
- machine: linux-x86_64
- commit hash: 0553fdf
- commit date: 2023-09-10
- overall geometric mean: 1.01x faster
- HPT reliability: 99.99%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230910-linux-x86_64-python-main-3.13.0a0-0553fdf |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| docutils       | 2.70 sec                                               | 2.60 sec: 1.04x faster                                |
| tornado_http   | 99.6 ms                                                | 94.9 ms: 1.05x faster                                 |
| Geometric mean | (ref)                                                  | 1.04x faster                                          |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230910-linux-x86_64-python-main-3.13.0a0-0553fdf |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| float          | 80.7 ms                                                | 79.8 ms: 1.01x faster                                 |
| pidigits       | 187 ms                                                 | 187 ms: 1.00x slower                                  |
| nbody          | 88.8 ms                                                | 90.6 ms: 1.02x slower                                 |
| Geometric mean | (ref)                                                  | 1.00x slower                                          |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230910-linux-x86_64-python-main-3.13.0a0-0553fdf |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| regex_compile  | 144 ms                                                 | 134 ms: 1.07x faster                                  |
| regex_dna      | 209 ms                                                 | 205 ms: 1.02x faster                                  |
| regex_effbot   | 3.55 ms                                                | 3.50 ms: 1.01x faster                                 |
| regex_v8       | 22.3 ms                                                | 23.4 ms: 1.05x slower                                 |
| Geometric mean | (ref)                                                  | 1.01x faster                                          |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230910-linux-x86_64-python-main-3.13.0a0-0553fdf |
|----------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| tomli_loads          | 2.22 sec                                               | 2.02 sec: 1.10x faster                                |
| unpickle             | 15.0 us                                                | 14.1 us: 1.06x faster                                 |
| pickle_dict          | 31.6 us                                                | 30.0 us: 1.05x faster                                 |
| pickle_pure_python   | 309 us                                                 | 295 us: 1.05x faster                                  |
| xml_etree_generate   | 84.8 ms                                                | 81.8 ms: 1.04x faster                                 |
| xml_etree_process    | 58.6 ms                                                | 56.6 ms: 1.03x faster                                 |
| pickle               | 10.6 us                                                | 10.3 us: 1.03x faster                                 |
| unpickle_pure_python | 218 us                                                 | 212 us: 1.03x faster                                  |
| xml_etree_iterparse  | 104 ms                                                 | 102 ms: 1.02x faster                                  |
| xml_etree_parse      | 154 ms                                                 | 151 ms: 1.02x faster                                  |
| unpickle_list        | 4.95 us                                                | 4.86 us: 1.02x faster                                 |
| pickle_list          | 4.62 us                                                | 4.67 us: 1.01x slower                                 |
| json_dumps           | 9.85 ms                                                | 9.99 ms: 1.01x slower                                 |
| Geometric mean       | (ref)                                                  | 1.03x faster                                          |

Benchmark hidden because not significant (1): json_loads

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230910-linux-x86_64-python-main-3.13.0a0-0553fdf |
|------------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| python_startup_no_site | 6.90 ms                                                | 6.81 ms: 1.01x faster                                 |
| python_startup         | 9.47 ms                                                | 10.0 ms: 1.06x slower                                 |
| Geometric mean         | (ref)                                                  | 1.02x slower                                          |

Benchmarks with tag 'template':
===============================

Benchmark hidden because not significant (1): mako

All benchmarks:
===============

| Benchmark                | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230910-linux-x86_64-python-main-3.13.0a0-0553fdf |
|--------------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| crypto_pyaes             | 77.2 ms                                                | 68.2 ms: 1.13x faster                                 |
| tomli_loads              | 2.22 sec                                               | 2.02 sec: 1.10x faster                                |
| coverage                 | 94.2 ms                                                | 86.8 ms: 1.08x faster                                 |
| deltablue                | 3.52 ms                                                | 3.24 ms: 1.08x faster                                 |
| scimark_monte_carlo      | 71.0 ms                                                | 65.8 ms: 1.08x faster                                 |
| raytrace                 | 294 ms                                                 | 273 ms: 1.08x faster                                  |
| asyncio_tcp              | 526 ms                                                 | 488 ms: 1.08x faster                                  |
| async_tree_none          | 469 ms                                                 | 436 ms: 1.08x faster                                  |
| regex_compile            | 144 ms                                                 | 134 ms: 1.07x faster                                  |
| chaos                    | 63.5 ms                                                | 59.6 ms: 1.07x faster                                 |
| unpickle                 | 15.0 us                                                | 14.1 us: 1.06x faster                                 |
| generators               | 31.1 ms                                                | 29.3 ms: 1.06x faster                                 |
| logging_format           | 6.90 us                                                | 6.53 us: 1.06x faster                                 |
| sqlglot_parse            | 1.32 ms                                                | 1.25 ms: 1.05x faster                                 |
| sqlglot_transpile        | 1.64 ms                                                | 1.56 ms: 1.05x faster                                 |
| pickle_dict              | 31.6 us                                                | 30.0 us: 1.05x faster                                 |
| tornado_http             | 99.6 ms                                                | 94.9 ms: 1.05x faster                                 |
| pickle_pure_python       | 309 us                                                 | 295 us: 1.05x faster                                  |
| coroutines               | 22.4 ms                                                | 21.5 ms: 1.05x faster                                 |
| scimark_sor              | 125 ms                                                 | 120 ms: 1.04x faster                                  |
| typing_runtime_protocols | 146 us                                                 | 140 us: 1.04x faster                                  |
| nqueens                  | 81.1 ms                                                | 78.0 ms: 1.04x faster                                 |
| docutils                 | 2.70 sec                                               | 2.60 sec: 1.04x faster                                |
| xml_etree_generate       | 84.8 ms                                                | 81.8 ms: 1.04x faster                                 |
| fannkuch                 | 387 ms                                                 | 374 ms: 1.04x faster                                  |
| xml_etree_process        | 58.6 ms                                                | 56.6 ms: 1.03x faster                                 |
| hexiom                   | 6.12 ms                                                | 5.92 ms: 1.03x faster                                 |
| pickle                   | 10.6 us                                                | 10.3 us: 1.03x faster                                 |
| unpickle_pure_python     | 218 us                                                 | 212 us: 1.03x faster                                  |
| logging_simple           | 6.18 us                                                | 5.98 us: 1.03x faster                                 |
| sqlglot_normalize        | 107 ms                                                 | 104 ms: 1.03x faster                                  |
| deepcopy                 | 355 us                                                 | 345 us: 1.03x faster                                  |
| bench_thread_pool        | 827 us                                                 | 807 us: 1.02x faster                                  |
| async_tree_memoization   | 573 ms                                                 | 560 ms: 1.02x faster                                  |
| dulwich_log              | 67.9 ms                                                | 66.4 ms: 1.02x faster                                 |
| xml_etree_iterparse      | 104 ms                                                 | 102 ms: 1.02x faster                                  |
| sqlglot_optimize         | 53.3 ms                                                | 52.2 ms: 1.02x faster                                 |
| mypy2                    | 344 ms                                                 | 337 ms: 1.02x faster                                  |
| xml_etree_parse          | 154 ms                                                 | 151 ms: 1.02x faster                                  |
| spectral_norm            | 106 ms                                                 | 104 ms: 1.02x faster                                  |
| async_tree_cpu_io_mixed  | 714 ms                                                 | 702 ms: 1.02x faster                                  |
| regex_dna                | 209 ms                                                 | 205 ms: 1.02x faster                                  |
| pprint_safe_repr         | 735 ms                                                 | 722 ms: 1.02x faster                                  |
| unpickle_list            | 4.95 us                                                | 4.86 us: 1.02x faster                                 |
| pprint_pformat           | 1.50 sec                                               | 1.48 sec: 1.01x faster                                |
| python_startup_no_site   | 6.90 ms                                                | 6.81 ms: 1.01x faster                                 |
| regex_effbot             | 3.55 ms                                                | 3.50 ms: 1.01x faster                                 |
| float                    | 80.7 ms                                                | 79.8 ms: 1.01x faster                                 |
| scimark_lu               | 114 ms                                                 | 113 ms: 1.01x faster                                  |
| pyflate                  | 450 ms                                                 | 446 ms: 1.01x faster                                  |
| deepcopy_reduce          | 3.14 us                                                | 3.11 us: 1.01x faster                                 |
| deepcopy_memo            | 37.4 us                                                | 37.1 us: 1.01x faster                                 |
| asyncio_tcp_ssl          | 1.79 sec                                               | 1.79 sec: 1.00x faster                                |
| pidigits                 | 187 ms                                                 | 187 ms: 1.00x slower                                  |
| mdp                      | 2.57 sec                                               | 2.58 sec: 1.00x slower                                |
| create_gc_cycles         | 1.52 ms                                                | 1.54 ms: 1.01x slower                                 |
| comprehensions           | 20.4 us                                                | 20.7 us: 1.01x slower                                 |
| pickle_list              | 4.62 us                                                | 4.67 us: 1.01x slower                                 |
| json_dumps               | 9.85 ms                                                | 9.99 ms: 1.01x slower                                 |
| pathlib                  | 18.5 ms                                                | 18.8 ms: 1.01x slower                                 |
| gc_traversal             | 3.84 ms                                                | 3.90 ms: 1.01x slower                                 |
| go                       | 136 ms                                                 | 138 ms: 1.02x slower                                  |
| nbody                    | 88.8 ms                                                | 90.6 ms: 1.02x slower                                 |
| async_tree_io            | 1.16 sec                                               | 1.18 sec: 1.02x slower                                |
| pycparser                | 1.15 sec                                               | 1.18 sec: 1.02x slower                                |
| scimark_sparse_mat_mult  | 4.74 ms                                                | 4.86 ms: 1.02x slower                                 |
| logging_silent           | 99.1 ns                                                | 103 ns: 1.04x slower                                  |
| regex_v8                 | 22.3 ms                                                | 23.4 ms: 1.05x slower                                 |
| python_startup           | 9.47 ms                                                | 10.0 ms: 1.06x slower                                 |
| richards                 | 43.2 ms                                                | 46.6 ms: 1.08x slower                                 |
| richards_super           | 49.0 ms                                                | 53.6 ms: 1.10x slower                                 |
| telco                    | 6.87 ms                                                | 7.92 ms: 1.15x slower                                 |
| dask                     | 365 ms                                                 | 522 ms: 1.43x slower                                  |
| Geometric mean           | (ref)                                                  | 1.01x faster                                          |

Benchmark hidden because not significant (9): async_generators, sqlite_synth, meteor_contest, scimark_fft, bench_mp_pool, json_loads, unpack_sequence, mako, json
Ignored benchmarks (3) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: 2to3, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 99.99% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
