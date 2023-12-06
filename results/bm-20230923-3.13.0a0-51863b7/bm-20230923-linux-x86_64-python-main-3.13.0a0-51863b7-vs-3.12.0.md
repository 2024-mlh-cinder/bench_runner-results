
# Results vs. 3.12.0

- fork: python
- ref: main
- machine: linux-x86_64
- commit hash: 51863b7
- commit date: 2023-09-23
- overall geometric mean: 1.01x faster
- HPT reliability: 99.61%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230923-linux-x86_64-python-main-3.13.0a0-51863b7 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| docutils       | 2.70 sec                                               | 2.60 sec: 1.04x faster                                |
| tornado_http   | 99.6 ms                                                | 94.9 ms: 1.05x faster                                 |
| Geometric mean | (ref)                                                  | 1.04x faster                                          |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230923-linux-x86_64-python-main-3.13.0a0-51863b7 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| float          | 80.7 ms                                                | 78.8 ms: 1.02x faster                                 |
| pidigits       | 187 ms                                                 | 187 ms: 1.00x slower                                  |
| nbody          | 88.8 ms                                                | 90.9 ms: 1.02x slower                                 |
| Geometric mean | (ref)                                                  | 1.00x slower                                          |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230923-linux-x86_64-python-main-3.13.0a0-51863b7 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| regex_compile  | 144 ms                                                 | 134 ms: 1.07x faster                                  |
| regex_effbot   | 3.55 ms                                                | 3.36 ms: 1.06x faster                                 |
| regex_dna      | 209 ms                                                 | 202 ms: 1.03x faster                                  |
| regex_v8       | 22.3 ms                                                | 24.0 ms: 1.07x slower                                 |
| Geometric mean | (ref)                                                  | 1.02x faster                                          |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230923-linux-x86_64-python-main-3.13.0a0-51863b7 |
|----------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| tomli_loads          | 2.22 sec                                               | 2.06 sec: 1.08x faster                                |
| pickle_pure_python   | 309 us                                                 | 296 us: 1.04x faster                                  |
| xml_etree_generate   | 84.8 ms                                                | 81.5 ms: 1.04x faster                                 |
| xml_etree_process    | 58.6 ms                                                | 56.5 ms: 1.04x faster                                 |
| pickle               | 10.6 us                                                | 10.2 us: 1.04x faster                                 |
| unpickle             | 15.0 us                                                | 14.6 us: 1.02x faster                                 |
| xml_etree_iterparse  | 104 ms                                                 | 102 ms: 1.02x faster                                  |
| unpickle_pure_python | 218 us                                                 | 215 us: 1.02x faster                                  |
| json_dumps           | 9.85 ms                                                | 9.77 ms: 1.01x faster                                 |
| unpickle_list        | 4.95 us                                                | 5.03 us: 1.02x slower                                 |
| pickle_list          | 4.62 us                                                | 4.75 us: 1.03x slower                                 |
| Geometric mean       | (ref)                                                  | 1.02x faster                                          |

Benchmark hidden because not significant (3): xml_etree_parse, pickle_dict, json_loads

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230923-linux-x86_64-python-main-3.13.0a0-51863b7 |
|------------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| python_startup_no_site | 6.90 ms                                                | 6.86 ms: 1.01x faster                                 |
| python_startup         | 9.47 ms                                                | 10.1 ms: 1.06x slower                                 |
| Geometric mean         | (ref)                                                  | 1.03x slower                                          |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230923-linux-x86_64-python-main-3.13.0a0-51863b7 |
|-----------|:------------------------------------------------------:|:-----------------------------------------------------:|
| mako      | 10.7 ms                                                | 10.9 ms: 1.02x slower                                 |

All benchmarks:
===============

| Benchmark                | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230923-linux-x86_64-python-main-3.13.0a0-51863b7 |
|--------------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| crypto_pyaes             | 77.2 ms                                                | 69.8 ms: 1.11x faster                                 |
| raytrace                 | 294 ms                                                 | 271 ms: 1.09x faster                                  |
| tomli_loads              | 2.22 sec                                               | 2.06 sec: 1.08x faster                                |
| async_tree_none          | 469 ms                                                 | 436 ms: 1.08x faster                                  |
| regex_compile            | 144 ms                                                 | 134 ms: 1.07x faster                                  |
| coverage                 | 94.2 ms                                                | 87.8 ms: 1.07x faster                                 |
| scimark_monte_carlo      | 71.0 ms                                                | 67.2 ms: 1.06x faster                                 |
| regex_effbot             | 3.55 ms                                                | 3.36 ms: 1.06x faster                                 |
| chaos                    | 63.5 ms                                                | 60.2 ms: 1.06x faster                                 |
| deltablue                | 3.52 ms                                                | 3.34 ms: 1.05x faster                                 |
| generators               | 31.1 ms                                                | 29.5 ms: 1.05x faster                                 |
| logging_format           | 6.90 us                                                | 6.57 us: 1.05x faster                                 |
| tornado_http             | 99.6 ms                                                | 94.9 ms: 1.05x faster                                 |
| typing_runtime_protocols | 146 us                                                 | 140 us: 1.05x faster                                  |
| sqlglot_transpile        | 1.64 ms                                                | 1.57 ms: 1.04x faster                                 |
| asyncio_tcp              | 526 ms                                                 | 504 ms: 1.04x faster                                  |
| logging_simple           | 6.18 us                                                | 5.92 us: 1.04x faster                                 |
| pickle_pure_python       | 309 us                                                 | 296 us: 1.04x faster                                  |
| sqlglot_parse            | 1.32 ms                                                | 1.27 ms: 1.04x faster                                 |
| docutils                 | 2.70 sec                                               | 2.60 sec: 1.04x faster                                |
| xml_etree_generate       | 84.8 ms                                                | 81.5 ms: 1.04x faster                                 |
| xml_etree_process        | 58.6 ms                                                | 56.5 ms: 1.04x faster                                 |
| pickle                   | 10.6 us                                                | 10.2 us: 1.04x faster                                 |
| deepcopy                 | 355 us                                                 | 344 us: 1.03x faster                                  |
| regex_dna                | 209 ms                                                 | 202 ms: 1.03x faster                                  |
| dulwich_log              | 67.9 ms                                                | 65.9 ms: 1.03x faster                                 |
| nqueens                  | 81.1 ms                                                | 78.7 ms: 1.03x faster                                 |
| pprint_safe_repr         | 735 ms                                                 | 713 ms: 1.03x faster                                  |
| pprint_pformat           | 1.50 sec                                               | 1.46 sec: 1.03x faster                                |
| bench_thread_pool        | 827 us                                                 | 805 us: 1.03x faster                                  |
| scimark_lu               | 114 ms                                                 | 111 ms: 1.02x faster                                  |
| mdp                      | 2.57 sec                                               | 2.50 sec: 1.02x faster                                |
| float                    | 80.7 ms                                                | 78.8 ms: 1.02x faster                                 |
| deepcopy_memo            | 37.4 us                                                | 36.6 us: 1.02x faster                                 |
| hexiom                   | 6.12 ms                                                | 5.99 ms: 1.02x faster                                 |
| unpickle                 | 15.0 us                                                | 14.6 us: 1.02x faster                                 |
| async_tree_cpu_io_mixed  | 714 ms                                                 | 699 ms: 1.02x faster                                  |
| sqlglot_normalize        | 107 ms                                                 | 105 ms: 1.02x faster                                  |
| async_tree_memoization   | 573 ms                                                 | 561 ms: 1.02x faster                                  |
| xml_etree_iterparse      | 104 ms                                                 | 102 ms: 1.02x faster                                  |
| unpickle_pure_python     | 218 us                                                 | 215 us: 1.02x faster                                  |
| mypy2                    | 344 ms                                                 | 338 ms: 1.02x faster                                  |
| deepcopy_reduce          | 3.14 us                                                | 3.09 us: 1.01x faster                                 |
| scimark_fft              | 358 ms                                                 | 353 ms: 1.01x faster                                  |
| sqlglot_optimize         | 53.3 ms                                                | 52.6 ms: 1.01x faster                                 |
| json_dumps               | 9.85 ms                                                | 9.77 ms: 1.01x faster                                 |
| comprehensions           | 20.4 us                                                | 20.3 us: 1.01x faster                                 |
| coroutines               | 22.4 ms                                                | 22.3 ms: 1.01x faster                                 |
| python_startup_no_site   | 6.90 ms                                                | 6.86 ms: 1.01x faster                                 |
| asyncio_tcp_ssl          | 1.79 sec                                               | 1.79 sec: 1.00x faster                                |
| pidigits                 | 187 ms                                                 | 187 ms: 1.00x slower                                  |
| gc_traversal             | 3.84 ms                                                | 3.85 ms: 1.00x slower                                 |
| pycparser                | 1.15 sec                                               | 1.16 sec: 1.01x slower                                |
| async_generators         | 440 ms                                                 | 443 ms: 1.01x slower                                  |
| create_gc_cycles         | 1.52 ms                                                | 1.54 ms: 1.01x slower                                 |
| meteor_contest           | 105 ms                                                 | 106 ms: 1.01x slower                                  |
| logging_silent           | 99.1 ns                                                | 100 ns: 1.01x slower                                  |
| fannkuch                 | 387 ms                                                 | 393 ms: 1.02x slower                                  |
| mako                     | 10.7 ms                                                | 10.9 ms: 1.02x slower                                 |
| async_tree_io            | 1.16 sec                                               | 1.18 sec: 1.02x slower                                |
| unpickle_list            | 4.95 us                                                | 5.03 us: 1.02x slower                                 |
| nbody                    | 88.8 ms                                                | 90.9 ms: 1.02x slower                                 |
| pyflate                  | 450 ms                                                 | 462 ms: 1.03x slower                                  |
| pathlib                  | 18.5 ms                                                | 19.0 ms: 1.03x slower                                 |
| pickle_list              | 4.62 us                                                | 4.75 us: 1.03x slower                                 |
| scimark_sor              | 125 ms                                                 | 130 ms: 1.04x slower                                  |
| go                       | 136 ms                                                 | 143 ms: 1.06x slower                                  |
| python_startup           | 9.47 ms                                                | 10.1 ms: 1.06x slower                                 |
| unpack_sequence          | 44.8 ns                                                | 48.0 ns: 1.07x slower                                 |
| regex_v8                 | 22.3 ms                                                | 24.0 ms: 1.07x slower                                 |
| richards_super           | 49.0 ms                                                | 54.2 ms: 1.11x slower                                 |
| richards                 | 43.2 ms                                                | 48.0 ms: 1.11x slower                                 |
| telco                    | 6.87 ms                                                | 7.97 ms: 1.16x slower                                 |
| dask                     | 365 ms                                                 | 526 ms: 1.44x slower                                  |
| Geometric mean           | (ref)                                                  | 1.01x faster                                          |

Benchmark hidden because not significant (8): xml_etree_parse, scimark_sparse_mat_mult, pickle_dict, sqlite_synth, spectral_norm, bench_mp_pool, json, json_loads
Ignored benchmarks (3) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: 2to3, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 99.61% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
