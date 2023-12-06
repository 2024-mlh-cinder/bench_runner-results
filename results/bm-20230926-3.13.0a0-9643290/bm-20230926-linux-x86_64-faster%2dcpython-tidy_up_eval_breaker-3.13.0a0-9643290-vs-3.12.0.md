
# Results vs. 3.12.0

- fork: faster-cpython
- ref: tidy_up_eval_breaker
- machine: linux-x86_64
- commit hash: 9643290
- commit date: 2023-09-26
- overall geometric mean: 1.00x faster
- HPT reliability: 94.12%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230926-linux-x86_64-faster%2dcpython-tidy_up_eval_breaker-3.13.0a0-9643290 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------------------------:|
| docutils       | 2.70 sec                                               | 2.60 sec: 1.04x faster                                                          |
| tornado_http   | 99.6 ms                                                | 95.9 ms: 1.04x faster                                                           |
| Geometric mean | (ref)                                                  | 1.04x faster                                                                    |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230926-linux-x86_64-faster%2dcpython-tidy_up_eval_breaker-3.13.0a0-9643290 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------------------------:|
| float          | 80.7 ms                                                | 80.0 ms: 1.01x faster                                                           |
| pidigits       | 187 ms                                                 | 188 ms: 1.01x slower                                                            |
| nbody          | 88.8 ms                                                | 91.7 ms: 1.03x slower                                                           |
| Geometric mean | (ref)                                                  | 1.01x slower                                                                    |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230926-linux-x86_64-faster%2dcpython-tidy_up_eval_breaker-3.13.0a0-9643290 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------------------------:|
| regex_compile  | 144 ms                                                 | 135 ms: 1.07x faster                                                            |
| regex_effbot   | 3.55 ms                                                | 3.57 ms: 1.01x slower                                                           |
| regex_dna      | 209 ms                                                 | 215 ms: 1.03x slower                                                            |
| regex_v8       | 22.3 ms                                                | 23.3 ms: 1.04x slower                                                           |
| Geometric mean | (ref)                                                  | 1.00x slower                                                                    |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230926-linux-x86_64-faster%2dcpython-tidy_up_eval_breaker-3.13.0a0-9643290 |
|----------------------|:------------------------------------------------------:|:-------------------------------------------------------------------------------:|
| pickle_pure_python   | 309 us                                                 | 294 us: 1.05x faster                                                            |
| tomli_loads          | 2.22 sec                                               | 2.12 sec: 1.05x faster                                                          |
| xml_etree_generate   | 84.8 ms                                                | 82.1 ms: 1.03x faster                                                           |
| xml_etree_process    | 58.6 ms                                                | 57.1 ms: 1.03x faster                                                           |
| unpickle_list        | 4.95 us                                                | 4.83 us: 1.02x faster                                                           |
| unpickle_pure_python | 218 us                                                 | 214 us: 1.02x faster                                                            |
| xml_etree_parse      | 154 ms                                                 | 151 ms: 1.02x faster                                                            |
| xml_etree_iterparse  | 104 ms                                                 | 102 ms: 1.02x faster                                                            |
| json_dumps           | 9.85 ms                                                | 9.94 ms: 1.01x slower                                                           |
| pickle               | 10.6 us                                                | 10.8 us: 1.02x slower                                                           |
| pickle_dict          | 31.6 us                                                | 32.4 us: 1.02x slower                                                           |
| pickle_list          | 4.62 us                                                | 4.75 us: 1.03x slower                                                           |
| Geometric mean       | (ref)                                                  | 1.01x faster                                                                    |

Benchmark hidden because not significant (2): json_loads, unpickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230926-linux-x86_64-faster%2dcpython-tidy_up_eval_breaker-3.13.0a0-9643290 |
|------------------------|:------------------------------------------------------:|:-------------------------------------------------------------------------------:|
| python_startup_no_site | 6.90 ms                                                | 6.83 ms: 1.01x faster                                                           |
| python_startup         | 9.47 ms                                                | 10.1 ms: 1.06x slower                                                           |
| Geometric mean         | (ref)                                                  | 1.03x slower                                                                    |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230926-linux-x86_64-faster%2dcpython-tidy_up_eval_breaker-3.13.0a0-9643290 |
|-----------|:------------------------------------------------------:|:-------------------------------------------------------------------------------:|
| mako      | 10.7 ms                                                | 10.6 ms: 1.01x faster                                                           |

All benchmarks:
===============

| Benchmark                | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230926-linux-x86_64-faster%2dcpython-tidy_up_eval_breaker-3.13.0a0-9643290 |
|--------------------------|:------------------------------------------------------:|:-------------------------------------------------------------------------------:|
| coverage                 | 94.2 ms                                                | 84.7 ms: 1.11x faster                                                           |
| crypto_pyaes             | 77.2 ms                                                | 70.1 ms: 1.10x faster                                                           |
| generators               | 31.1 ms                                                | 28.6 ms: 1.09x faster                                                           |
| raytrace                 | 294 ms                                                 | 271 ms: 1.08x faster                                                            |
| deltablue                | 3.52 ms                                                | 3.27 ms: 1.08x faster                                                           |
| async_tree_none          | 469 ms                                                 | 436 ms: 1.08x faster                                                            |
| regex_compile            | 144 ms                                                 | 135 ms: 1.07x faster                                                            |
| scimark_monte_carlo      | 71.0 ms                                                | 66.7 ms: 1.06x faster                                                           |
| logging_format           | 6.90 us                                                | 6.52 us: 1.06x faster                                                           |
| logging_simple           | 6.18 us                                                | 5.86 us: 1.05x faster                                                           |
| chaos                    | 63.5 ms                                                | 60.4 ms: 1.05x faster                                                           |
| pickle_pure_python       | 309 us                                                 | 294 us: 1.05x faster                                                            |
| sqlglot_parse            | 1.32 ms                                                | 1.26 ms: 1.05x faster                                                           |
| asyncio_tcp              | 526 ms                                                 | 502 ms: 1.05x faster                                                            |
| tomli_loads              | 2.22 sec                                               | 2.12 sec: 1.05x faster                                                          |
| sqlglot_transpile        | 1.64 ms                                                | 1.57 ms: 1.04x faster                                                           |
| tornado_http             | 99.6 ms                                                | 95.9 ms: 1.04x faster                                                           |
| docutils                 | 2.70 sec                                               | 2.60 sec: 1.04x faster                                                          |
| xml_etree_generate       | 84.8 ms                                                | 82.1 ms: 1.03x faster                                                           |
| sqlglot_normalize        | 107 ms                                                 | 104 ms: 1.03x faster                                                            |
| scimark_sor              | 125 ms                                                 | 121 ms: 1.03x faster                                                            |
| deepcopy                 | 355 us                                                 | 346 us: 1.03x faster                                                            |
| pprint_safe_repr         | 735 ms                                                 | 715 ms: 1.03x faster                                                            |
| scimark_lu               | 114 ms                                                 | 111 ms: 1.03x faster                                                            |
| pprint_pformat           | 1.50 sec                                               | 1.46 sec: 1.03x faster                                                          |
| xml_etree_process        | 58.6 ms                                                | 57.1 ms: 1.03x faster                                                           |
| dulwich_log              | 67.9 ms                                                | 66.3 ms: 1.02x faster                                                           |
| unpickle_list            | 4.95 us                                                | 4.83 us: 1.02x faster                                                           |
| deepcopy_reduce          | 3.14 us                                                | 3.07 us: 1.02x faster                                                           |
| bench_thread_pool        | 827 us                                                 | 809 us: 1.02x faster                                                            |
| unpickle_pure_python     | 218 us                                                 | 214 us: 1.02x faster                                                            |
| async_tree_memoization   | 573 ms                                                 | 562 ms: 1.02x faster                                                            |
| sqlglot_optimize         | 53.3 ms                                                | 52.3 ms: 1.02x faster                                                           |
| xml_etree_parse          | 154 ms                                                 | 151 ms: 1.02x faster                                                            |
| typing_runtime_protocols | 146 us                                                 | 143 us: 1.02x faster                                                            |
| deepcopy_memo            | 37.4 us                                                | 36.7 us: 1.02x faster                                                           |
| hexiom                   | 6.12 ms                                                | 6.02 ms: 1.02x faster                                                           |
| async_tree_cpu_io_mixed  | 714 ms                                                 | 702 ms: 1.02x faster                                                            |
| xml_etree_iterparse      | 104 ms                                                 | 102 ms: 1.02x faster                                                            |
| mypy2                    | 344 ms                                                 | 339 ms: 1.01x faster                                                            |
| nqueens                  | 81.1 ms                                                | 80.1 ms: 1.01x faster                                                           |
| coroutines               | 22.4 ms                                                | 22.2 ms: 1.01x faster                                                           |
| mako                     | 10.7 ms                                                | 10.6 ms: 1.01x faster                                                           |
| float                    | 80.7 ms                                                | 80.0 ms: 1.01x faster                                                           |
| python_startup_no_site   | 6.90 ms                                                | 6.83 ms: 1.01x faster                                                           |
| sqlite_synth             | 2.76 us                                                | 2.73 us: 1.01x faster                                                           |
| asyncio_tcp_ssl          | 1.79 sec                                               | 1.80 sec: 1.00x slower                                                          |
| pathlib                  | 18.5 ms                                                | 18.6 ms: 1.01x slower                                                           |
| pidigits                 | 187 ms                                                 | 188 ms: 1.01x slower                                                            |
| regex_effbot             | 3.55 ms                                                | 3.57 ms: 1.01x slower                                                           |
| create_gc_cycles         | 1.52 ms                                                | 1.54 ms: 1.01x slower                                                           |
| async_generators         | 440 ms                                                 | 444 ms: 1.01x slower                                                            |
| json_dumps               | 9.85 ms                                                | 9.94 ms: 1.01x slower                                                           |
| spectral_norm            | 106 ms                                                 | 107 ms: 1.01x slower                                                            |
| scimark_fft              | 358 ms                                                 | 366 ms: 1.02x slower                                                            |
| logging_silent           | 99.1 ns                                                | 101 ns: 1.02x slower                                                            |
| pickle                   | 10.6 us                                                | 10.8 us: 1.02x slower                                                           |
| mdp                      | 2.57 sec                                               | 2.63 sec: 1.02x slower                                                          |
| pyflate                  | 450 ms                                                 | 461 ms: 1.02x slower                                                            |
| pickle_dict              | 31.6 us                                                | 32.4 us: 1.02x slower                                                           |
| pycparser                | 1.15 sec                                               | 1.18 sec: 1.03x slower                                                          |
| async_tree_io            | 1.16 sec                                               | 1.19 sec: 1.03x slower                                                          |
| go                       | 136 ms                                                 | 139 ms: 1.03x slower                                                            |
| pickle_list              | 4.62 us                                                | 4.75 us: 1.03x slower                                                           |
| regex_dna                | 209 ms                                                 | 215 ms: 1.03x slower                                                            |
| nbody                    | 88.8 ms                                                | 91.7 ms: 1.03x slower                                                           |
| gc_traversal             | 3.84 ms                                                | 3.97 ms: 1.03x slower                                                           |
| regex_v8                 | 22.3 ms                                                | 23.3 ms: 1.04x slower                                                           |
| python_startup           | 9.47 ms                                                | 10.1 ms: 1.06x slower                                                           |
| richards_super           | 49.0 ms                                                | 53.6 ms: 1.09x slower                                                           |
| richards                 | 43.2 ms                                                | 47.5 ms: 1.10x slower                                                           |
| unpack_sequence          | 44.8 ns                                                | 50.5 ns: 1.13x slower                                                           |
| telco                    | 6.87 ms                                                | 8.10 ms: 1.18x slower                                                           |
| dask                     | 365 ms                                                 | 528 ms: 1.45x slower                                                            |
| Geometric mean           | (ref)                                                  | 1.00x faster                                                                    |

Benchmark hidden because not significant (8): fannkuch, comprehensions, scimark_sparse_mat_mult, bench_mp_pool, meteor_contest, json, json_loads, unpickle
Ignored benchmarks (3) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: 2to3, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 94.12% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
