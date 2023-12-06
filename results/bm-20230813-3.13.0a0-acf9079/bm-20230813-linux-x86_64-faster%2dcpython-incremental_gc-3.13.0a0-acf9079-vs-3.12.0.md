
# Results vs. 3.12.0

- fork: faster-cpython
- ref: incremental_gc
- machine: linux-x86_64
- commit hash: acf9079
- commit date: 2023-08-13
- overall geometric mean: 1.03x faster
- HPT reliability: 99.99%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230813-linux-x86_64-faster%2dcpython-incremental_gc-3.13.0a0-acf9079 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------------------:|
| docutils       | 2.70 sec                                               | 2.43 sec: 1.11x faster                                                    |
| tornado_http   | 99.6 ms                                                | 93.6 ms: 1.06x faster                                                     |
| Geometric mean | (ref)                                                  | 1.09x faster                                                              |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230813-linux-x86_64-faster%2dcpython-incremental_gc-3.13.0a0-acf9079 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------------------:|
| float          | 80.7 ms                                                | 75.4 ms: 1.07x faster                                                     |
| nbody          | 88.8 ms                                                | 89.6 ms: 1.01x slower                                                     |
| pidigits       | 187 ms                                                 | 189 ms: 1.01x slower                                                      |
| Geometric mean | (ref)                                                  | 1.02x faster                                                              |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230813-linux-x86_64-faster%2dcpython-incremental_gc-3.13.0a0-acf9079 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------------------:|
| regex_compile  | 144 ms                                                 | 137 ms: 1.05x faster                                                      |
| regex_v8       | 22.3 ms                                                | 22.2 ms: 1.01x faster                                                     |
| regex_effbot   | 3.55 ms                                                | 3.59 ms: 1.01x slower                                                     |
| Geometric mean | (ref)                                                  | 1.01x faster                                                              |

Benchmark hidden because not significant (1): regex_dna

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230813-linux-x86_64-faster%2dcpython-incremental_gc-3.13.0a0-acf9079 |
|----------------------|:------------------------------------------------------:|:-------------------------------------------------------------------------:|
| xml_etree_iterparse  | 104 ms                                                 | 100 ms: 1.03x faster                                                      |
| pickle_pure_python   | 309 us                                                 | 299 us: 1.03x faster                                                      |
| xml_etree_process    | 58.6 ms                                                | 57.2 ms: 1.02x faster                                                     |
| xml_etree_generate   | 84.8 ms                                                | 83.3 ms: 1.02x faster                                                     |
| unpickle_pure_python | 218 us                                                 | 215 us: 1.02x faster                                                      |
| pickle               | 10.6 us                                                | 10.4 us: 1.02x faster                                                     |
| pickle_list          | 4.62 us                                                | 4.55 us: 1.01x faster                                                     |
| unpickle             | 15.0 us                                                | 15.2 us: 1.02x slower                                                     |
| json_loads           | 25.2 us                                                | 25.7 us: 1.02x slower                                                     |
| unpickle_list        | 4.95 us                                                | 5.11 us: 1.03x slower                                                     |
| tomli_loads          | 2.22 sec                                               | 2.33 sec: 1.05x slower                                                    |
| Geometric mean       | (ref)                                                  | 1.00x faster                                                              |

Benchmark hidden because not significant (3): xml_etree_parse, pickle_dict, json_dumps

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230813-linux-x86_64-faster%2dcpython-incremental_gc-3.13.0a0-acf9079 |
|------------------------|:------------------------------------------------------:|:-------------------------------------------------------------------------:|
| python_startup_no_site | 6.90 ms                                                | 6.73 ms: 1.03x faster                                                     |
| python_startup         | 9.47 ms                                                | 9.25 ms: 1.02x faster                                                     |
| Geometric mean         | (ref)                                                  | 1.02x faster                                                              |

Benchmarks with tag 'template':
===============================

Benchmark hidden because not significant (1): mako

All benchmarks:
===============

| Benchmark                | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230813-linux-x86_64-faster%2dcpython-incremental_gc-3.13.0a0-acf9079 |
|--------------------------|:------------------------------------------------------:|:-------------------------------------------------------------------------:|
| async_tree_io            | 1.16 sec                                               | 677 ms: 1.71x faster                                                      |
| async_tree_none          | 469 ms                                                 | 311 ms: 1.51x faster                                                      |
| async_tree_memoization   | 573 ms                                                 | 395 ms: 1.45x faster                                                      |
| async_tree_cpu_io_mixed  | 714 ms                                                 | 562 ms: 1.27x faster                                                      |
| crypto_pyaes             | 77.2 ms                                                | 68.3 ms: 1.13x faster                                                     |
| deltablue                | 3.52 ms                                                | 3.14 ms: 1.12x faster                                                     |
| docutils                 | 2.70 sec                                               | 2.43 sec: 1.11x faster                                                    |
| raytrace                 | 294 ms                                                 | 270 ms: 1.09x faster                                                      |
| generators               | 31.1 ms                                                | 28.5 ms: 1.09x faster                                                     |
| asyncio_tcp              | 526 ms                                                 | 485 ms: 1.08x faster                                                      |
| chaos                    | 63.5 ms                                                | 58.8 ms: 1.08x faster                                                     |
| float                    | 80.7 ms                                                | 75.4 ms: 1.07x faster                                                     |
| tornado_http             | 99.6 ms                                                | 93.6 ms: 1.06x faster                                                     |
| scimark_monte_carlo      | 71.0 ms                                                | 66.8 ms: 1.06x faster                                                     |
| logging_format           | 6.90 us                                                | 6.53 us: 1.06x faster                                                     |
| create_gc_cycles         | 1.52 ms                                                | 1.44 ms: 1.05x faster                                                     |
| gc_traversal             | 3.84 ms                                                | 3.64 ms: 1.05x faster                                                     |
| regex_compile            | 144 ms                                                 | 137 ms: 1.05x faster                                                      |
| logging_simple           | 6.18 us                                                | 5.95 us: 1.04x faster                                                     |
| unpack_sequence          | 44.8 ns                                                | 43.2 ns: 1.04x faster                                                     |
| xml_etree_iterparse      | 104 ms                                                 | 100 ms: 1.03x faster                                                      |
| pickle_pure_python       | 309 us                                                 | 299 us: 1.03x faster                                                      |
| scimark_sor              | 125 ms                                                 | 121 ms: 1.03x faster                                                      |
| coverage                 | 94.2 ms                                                | 91.8 ms: 1.03x faster                                                     |
| hexiom                   | 6.12 ms                                                | 5.97 ms: 1.03x faster                                                     |
| sqlglot_parse            | 1.32 ms                                                | 1.29 ms: 1.03x faster                                                     |
| python_startup_no_site   | 6.90 ms                                                | 6.73 ms: 1.03x faster                                                     |
| python_startup           | 9.47 ms                                                | 9.25 ms: 1.02x faster                                                     |
| dulwich_log              | 67.9 ms                                                | 66.3 ms: 1.02x faster                                                     |
| xml_etree_process        | 58.6 ms                                                | 57.2 ms: 1.02x faster                                                     |
| async_generators         | 440 ms                                                 | 431 ms: 1.02x faster                                                      |
| sqlglot_transpile        | 1.64 ms                                                | 1.61 ms: 1.02x faster                                                     |
| xml_etree_generate       | 84.8 ms                                                | 83.3 ms: 1.02x faster                                                     |
| unpickle_pure_python     | 218 us                                                 | 215 us: 1.02x faster                                                      |
| pickle                   | 10.6 us                                                | 10.4 us: 1.02x faster                                                     |
| scimark_lu               | 114 ms                                                 | 112 ms: 1.02x faster                                                      |
| pyflate                  | 450 ms                                                 | 444 ms: 1.02x faster                                                      |
| pickle_list              | 4.62 us                                                | 4.55 us: 1.01x faster                                                     |
| pprint_safe_repr         | 735 ms                                                 | 725 ms: 1.01x faster                                                      |
| nqueens                  | 81.1 ms                                                | 80.2 ms: 1.01x faster                                                     |
| pprint_pformat           | 1.50 sec                                               | 1.48 sec: 1.01x faster                                                    |
| pycparser                | 1.15 sec                                               | 1.14 sec: 1.01x faster                                                    |
| deepcopy                 | 355 us                                                 | 351 us: 1.01x faster                                                      |
| comprehensions           | 20.4 us                                                | 20.2 us: 1.01x faster                                                     |
| mdp                      | 2.57 sec                                               | 2.54 sec: 1.01x faster                                                    |
| coroutines               | 22.4 ms                                                | 22.2 ms: 1.01x faster                                                     |
| sqlglot_normalize        | 107 ms                                                 | 106 ms: 1.01x faster                                                      |
| sqlglot_optimize         | 53.3 ms                                                | 52.9 ms: 1.01x faster                                                     |
| scimark_fft              | 358 ms                                                 | 356 ms: 1.01x faster                                                      |
| bench_thread_pool        | 827 us                                                 | 822 us: 1.01x faster                                                      |
| regex_v8                 | 22.3 ms                                                | 22.2 ms: 1.01x faster                                                     |
| asyncio_tcp_ssl          | 1.79 sec                                               | 1.79 sec: 1.00x faster                                                    |
| meteor_contest           | 105 ms                                                 | 105 ms: 1.00x slower                                                      |
| mypy2                    | 344 ms                                                 | 347 ms: 1.01x slower                                                      |
| nbody                    | 88.8 ms                                                | 89.6 ms: 1.01x slower                                                     |
| deepcopy_memo            | 37.4 us                                                | 37.8 us: 1.01x slower                                                     |
| regex_effbot             | 3.55 ms                                                | 3.59 ms: 1.01x slower                                                     |
| pidigits                 | 187 ms                                                 | 189 ms: 1.01x slower                                                      |
| unpickle                 | 15.0 us                                                | 15.2 us: 1.02x slower                                                     |
| json_loads               | 25.2 us                                                | 25.7 us: 1.02x slower                                                     |
| deepcopy_reduce          | 3.14 us                                                | 3.19 us: 1.02x slower                                                     |
| fannkuch                 | 387 ms                                                 | 394 ms: 1.02x slower                                                      |
| typing_runtime_protocols | 146 us                                                 | 149 us: 1.02x slower                                                      |
| sqlite_synth             | 2.76 us                                                | 2.82 us: 1.02x slower                                                     |
| json                     | 4.77 ms                                                | 4.88 ms: 1.02x slower                                                     |
| scimark_sparse_mat_mult  | 4.74 ms                                                | 4.86 ms: 1.02x slower                                                     |
| go                       | 136 ms                                                 | 139 ms: 1.03x slower                                                      |
| unpickle_list            | 4.95 us                                                | 5.11 us: 1.03x slower                                                     |
| logging_silent           | 99.1 ns                                                | 104 ns: 1.05x slower                                                      |
| tomli_loads              | 2.22 sec                                               | 2.33 sec: 1.05x slower                                                    |
| richards_super           | 49.0 ms                                                | 52.9 ms: 1.08x slower                                                     |
| richards                 | 43.2 ms                                                | 46.8 ms: 1.08x slower                                                     |
| telco                    | 6.87 ms                                                | 7.96 ms: 1.16x slower                                                     |
| dask                     | 365 ms                                                 | 494 ms: 1.35x slower                                                      |
| Geometric mean           | (ref)                                                  | 1.03x faster                                                              |

Benchmark hidden because not significant (8): xml_etree_parse, pathlib, pickle_dict, json_dumps, bench_mp_pool, mako, regex_dna, spectral_norm
Ignored benchmarks (3) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: 2to3, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 99.99% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
