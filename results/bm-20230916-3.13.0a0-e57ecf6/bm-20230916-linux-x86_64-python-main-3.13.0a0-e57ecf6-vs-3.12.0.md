
# Results vs. 3.12.0

- fork: python
- ref: main
- machine: linux-x86_64
- commit hash: e57ecf6
- commit date: 2023-09-16
- overall geometric mean: 1.01x faster
- HPT reliability: 99.89%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230916-linux-x86_64-python-main-3.13.0a0-e57ecf6 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| docutils       | 2.70 sec                                               | 2.62 sec: 1.03x faster                                |
| tornado_http   | 99.6 ms                                                | 95.0 ms: 1.05x faster                                 |
| Geometric mean | (ref)                                                  | 1.04x faster                                          |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230916-linux-x86_64-python-main-3.13.0a0-e57ecf6 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| float          | 80.7 ms                                                | 78.7 ms: 1.03x faster                                 |
| nbody          | 88.8 ms                                                | 88.0 ms: 1.01x faster                                 |
| pidigits       | 187 ms                                                 | 203 ms: 1.09x slower                                  |
| Geometric mean | (ref)                                                  | 1.02x slower                                          |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230916-linux-x86_64-python-main-3.13.0a0-e57ecf6 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| regex_compile  | 144 ms                                                 | 134 ms: 1.07x faster                                  |
| regex_effbot   | 3.55 ms                                                | 3.45 ms: 1.03x faster                                 |
| regex_dna      | 209 ms                                                 | 205 ms: 1.02x faster                                  |
| regex_v8       | 22.3 ms                                                | 23.3 ms: 1.04x slower                                 |
| Geometric mean | (ref)                                                  | 1.02x faster                                          |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230916-linux-x86_64-python-main-3.13.0a0-e57ecf6 |
|----------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| unpickle             | 15.0 us                                                | 14.2 us: 1.05x faster                                 |
| tomli_loads          | 2.22 sec                                               | 2.12 sec: 1.05x faster                                |
| pickle_pure_python   | 309 us                                                 | 296 us: 1.05x faster                                  |
| unpickle_pure_python | 218 us                                                 | 211 us: 1.03x faster                                  |
| xml_etree_process    | 58.6 ms                                                | 56.8 ms: 1.03x faster                                 |
| xml_etree_generate   | 84.8 ms                                                | 82.3 ms: 1.03x faster                                 |
| unpickle_list        | 4.95 us                                                | 4.83 us: 1.02x faster                                 |
| xml_etree_iterparse  | 104 ms                                                 | 102 ms: 1.02x faster                                  |
| xml_etree_parse      | 154 ms                                                 | 152 ms: 1.01x faster                                  |
| pickle               | 10.6 us                                                | 10.7 us: 1.01x slower                                 |
| pickle_dict          | 31.6 us                                                | 32.4 us: 1.02x slower                                 |
| pickle_list          | 4.62 us                                                | 4.85 us: 1.05x slower                                 |
| Geometric mean       | (ref)                                                  | 1.01x faster                                          |

Benchmark hidden because not significant (2): json_dumps, json_loads

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230916-linux-x86_64-python-main-3.13.0a0-e57ecf6 |
|------------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| python_startup_no_site | 6.90 ms                                                | 6.83 ms: 1.01x faster                                 |
| python_startup         | 9.47 ms                                                | 10.0 ms: 1.06x slower                                 |
| Geometric mean         | (ref)                                                  | 1.02x slower                                          |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230916-linux-x86_64-python-main-3.13.0a0-e57ecf6 |
|-----------|:------------------------------------------------------:|:-----------------------------------------------------:|
| mako      | 10.7 ms                                                | 10.5 ms: 1.02x faster                                 |

All benchmarks:
===============

| Benchmark                | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230916-linux-x86_64-python-main-3.13.0a0-e57ecf6 |
|--------------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| generators               | 31.1 ms                                                | 27.9 ms: 1.11x faster                                 |
| crypto_pyaes             | 77.2 ms                                                | 69.8 ms: 1.11x faster                                 |
| raytrace                 | 294 ms                                                 | 266 ms: 1.11x faster                                  |
| coverage                 | 94.2 ms                                                | 86.7 ms: 1.09x faster                                 |
| async_tree_none          | 469 ms                                                 | 437 ms: 1.07x faster                                  |
| asyncio_tcp              | 526 ms                                                 | 490 ms: 1.07x faster                                  |
| regex_compile            | 144 ms                                                 | 134 ms: 1.07x faster                                  |
| unpack_sequence          | 44.8 ns                                                | 41.9 ns: 1.07x faster                                 |
| chaos                    | 63.5 ms                                                | 59.4 ms: 1.07x faster                                 |
| scimark_monte_carlo      | 71.0 ms                                                | 66.6 ms: 1.07x faster                                 |
| deltablue                | 3.52 ms                                                | 3.32 ms: 1.06x faster                                 |
| unpickle                 | 15.0 us                                                | 14.2 us: 1.05x faster                                 |
| tornado_http             | 99.6 ms                                                | 95.0 ms: 1.05x faster                                 |
| tomli_loads              | 2.22 sec                                               | 2.12 sec: 1.05x faster                                |
| pickle_pure_python       | 309 us                                                 | 296 us: 1.05x faster                                  |
| scimark_sparse_mat_mult  | 4.74 ms                                                | 4.54 ms: 1.04x faster                                 |
| sqlglot_parse            | 1.32 ms                                                | 1.27 ms: 1.04x faster                                 |
| sqlglot_transpile        | 1.64 ms                                                | 1.58 ms: 1.04x faster                                 |
| typing_runtime_protocols | 146 us                                                 | 141 us: 1.04x faster                                  |
| nqueens                  | 81.1 ms                                                | 78.2 ms: 1.04x faster                                 |
| scimark_lu               | 114 ms                                                 | 110 ms: 1.03x faster                                  |
| unpickle_pure_python     | 218 us                                                 | 211 us: 1.03x faster                                  |
| hexiom                   | 6.12 ms                                                | 5.93 ms: 1.03x faster                                 |
| xml_etree_process        | 58.6 ms                                                | 56.8 ms: 1.03x faster                                 |
| logging_format           | 6.90 us                                                | 6.69 us: 1.03x faster                                 |
| xml_etree_generate       | 84.8 ms                                                | 82.3 ms: 1.03x faster                                 |
| docutils                 | 2.70 sec                                               | 2.62 sec: 1.03x faster                                |
| deepcopy                 | 355 us                                                 | 345 us: 1.03x faster                                  |
| pprint_pformat           | 1.50 sec                                               | 1.46 sec: 1.03x faster                                |
| regex_effbot             | 3.55 ms                                                | 3.45 ms: 1.03x faster                                 |
| deepcopy_memo            | 37.4 us                                                | 36.4 us: 1.03x faster                                 |
| float                    | 80.7 ms                                                | 78.7 ms: 1.03x faster                                 |
| bench_thread_pool        | 827 us                                                 | 806 us: 1.03x faster                                  |
| unpickle_list            | 4.95 us                                                | 4.83 us: 1.02x faster                                 |
| pprint_safe_repr         | 735 ms                                                 | 718 ms: 1.02x faster                                  |
| mako                     | 10.7 ms                                                | 10.5 ms: 1.02x faster                                 |
| dulwich_log              | 67.9 ms                                                | 66.6 ms: 1.02x faster                                 |
| async_tree_cpu_io_mixed  | 714 ms                                                 | 700 ms: 1.02x faster                                  |
| mypy2                    | 344 ms                                                 | 337 ms: 1.02x faster                                  |
| xml_etree_iterparse      | 104 ms                                                 | 102 ms: 1.02x faster                                  |
| async_tree_memoization   | 573 ms                                                 | 562 ms: 1.02x faster                                  |
| sqlglot_normalize        | 107 ms                                                 | 105 ms: 1.02x faster                                  |
| regex_dna                | 209 ms                                                 | 205 ms: 1.02x faster                                  |
| xml_etree_parse          | 154 ms                                                 | 152 ms: 1.01x faster                                  |
| fannkuch                 | 387 ms                                                 | 382 ms: 1.01x faster                                  |
| sqlite_synth             | 2.76 us                                                | 2.73 us: 1.01x faster                                 |
| logging_simple           | 6.18 us                                                | 6.10 us: 1.01x faster                                 |
| python_startup_no_site   | 6.90 ms                                                | 6.83 ms: 1.01x faster                                 |
| sqlglot_optimize         | 53.3 ms                                                | 52.8 ms: 1.01x faster                                 |
| nbody                    | 88.8 ms                                                | 88.0 ms: 1.01x faster                                 |
| logging_silent           | 99.1 ns                                                | 98.5 ns: 1.01x faster                                 |
| deepcopy_reduce          | 3.14 us                                                | 3.12 us: 1.01x faster                                 |
| pyflate                  | 450 ms                                                 | 453 ms: 1.00x slower                                  |
| meteor_contest           | 105 ms                                                 | 106 ms: 1.01x slower                                  |
| spectral_norm            | 106 ms                                                 | 107 ms: 1.01x slower                                  |
| async_generators         | 440 ms                                                 | 445 ms: 1.01x slower                                  |
| json                     | 4.77 ms                                                | 4.83 ms: 1.01x slower                                 |
| pickle                   | 10.6 us                                                | 10.7 us: 1.01x slower                                 |
| pickle_dict              | 31.6 us                                                | 32.4 us: 1.02x slower                                 |
| mdp                      | 2.57 sec                                               | 2.63 sec: 1.02x slower                                |
| async_tree_io            | 1.16 sec                                               | 1.19 sec: 1.03x slower                                |
| go                       | 136 ms                                                 | 140 ms: 1.03x slower                                  |
| scimark_sor              | 125 ms                                                 | 129 ms: 1.03x slower                                  |
| regex_v8                 | 22.3 ms                                                | 23.3 ms: 1.04x slower                                 |
| pickle_list              | 4.62 us                                                | 4.85 us: 1.05x slower                                 |
| python_startup           | 9.47 ms                                                | 10.0 ms: 1.06x slower                                 |
| gc_traversal             | 3.84 ms                                                | 4.12 ms: 1.07x slower                                 |
| pidigits                 | 187 ms                                                 | 203 ms: 1.09x slower                                  |
| richards_super           | 49.0 ms                                                | 54.4 ms: 1.11x slower                                 |
| richards                 | 43.2 ms                                                | 48.4 ms: 1.12x slower                                 |
| telco                    | 6.87 ms                                                | 7.98 ms: 1.16x slower                                 |
| dask                     | 365 ms                                                 | 529 ms: 1.45x slower                                  |
| Geometric mean           | (ref)                                                  | 1.01x faster                                          |

Benchmark hidden because not significant (10): pycparser, coroutines, json_dumps, pathlib, comprehensions, create_gc_cycles, asyncio_tcp_ssl, bench_mp_pool, scimark_fft, json_loads
Ignored benchmarks (3) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: 2to3, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 99.89% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
