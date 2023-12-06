
# Results vs. 3.12.0

- fork: faster-cpython
- ref: tidy_up_eval_breaker
- machine: linux-x86_64
- commit hash: 2b8766e
- commit date: 2023-09-13
- overall geometric mean: 1.01x faster
- HPT reliability: 99.53%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230913-linux-x86_64-faster%2dcpython-tidy_up_eval_breaker-3.13.0a0-2b8766e |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------------------------:|
| docutils       | 2.70 sec                                               | 2.60 sec: 1.04x faster                                                          |
| tornado_http   | 99.6 ms                                                | 95.1 ms: 1.05x faster                                                           |
| Geometric mean | (ref)                                                  | 1.04x faster                                                                    |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230913-linux-x86_64-faster%2dcpython-tidy_up_eval_breaker-3.13.0a0-2b8766e |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------------------------:|
| float          | 80.7 ms                                                | 80.2 ms: 1.01x faster                                                           |
| pidigits       | 187 ms                                                 | 187 ms: 1.00x slower                                                            |
| Geometric mean | (ref)                                                  | 1.00x faster                                                                    |

Benchmark hidden because not significant (1): nbody

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230913-linux-x86_64-faster%2dcpython-tidy_up_eval_breaker-3.13.0a0-2b8766e |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------------------------:|
| regex_compile  | 144 ms                                                 | 136 ms: 1.06x faster                                                            |
| regex_effbot   | 3.55 ms                                                | 3.43 ms: 1.03x faster                                                           |
| regex_v8       | 22.3 ms                                                | 23.6 ms: 1.05x slower                                                           |
| Geometric mean | (ref)                                                  | 1.01x faster                                                                    |

Benchmark hidden because not significant (1): regex_dna

Benchmarks with tag 'serialize':
================================

| Benchmark           | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230913-linux-x86_64-faster%2dcpython-tidy_up_eval_breaker-3.13.0a0-2b8766e |
|---------------------|:------------------------------------------------------:|:-------------------------------------------------------------------------------:|
| unpickle            | 15.0 us                                                | 14.0 us: 1.07x faster                                                           |
| tomli_loads         | 2.22 sec                                               | 2.08 sec: 1.07x faster                                                          |
| unpickle_list       | 4.95 us                                                | 4.74 us: 1.04x faster                                                           |
| xml_etree_process   | 58.6 ms                                                | 57.4 ms: 1.02x faster                                                           |
| pickle_pure_python  | 309 us                                                 | 303 us: 1.02x faster                                                            |
| pickle_list         | 4.62 us                                                | 4.54 us: 1.02x faster                                                           |
| xml_etree_iterparse | 104 ms                                                 | 102 ms: 1.02x faster                                                            |
| xml_etree_parse     | 154 ms                                                 | 151 ms: 1.01x faster                                                            |
| xml_etree_generate  | 84.8 ms                                                | 83.9 ms: 1.01x faster                                                           |
| json_dumps          | 9.85 ms                                                | 9.76 ms: 1.01x faster                                                           |
| pickle_dict         | 31.6 us                                                | 31.4 us: 1.01x faster                                                           |
| pickle              | 10.6 us                                                | 10.7 us: 1.01x slower                                                           |
| Geometric mean      | (ref)                                                  | 1.02x faster                                                                    |

Benchmark hidden because not significant (2): json_loads, unpickle_pure_python

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230913-linux-x86_64-faster%2dcpython-tidy_up_eval_breaker-3.13.0a0-2b8766e |
|------------------------|:------------------------------------------------------:|:-------------------------------------------------------------------------------:|
| python_startup_no_site | 6.90 ms                                                | 6.84 ms: 1.01x faster                                                           |
| python_startup         | 9.47 ms                                                | 10.1 ms: 1.06x slower                                                           |
| Geometric mean         | (ref)                                                  | 1.03x slower                                                                    |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230913-linux-x86_64-faster%2dcpython-tidy_up_eval_breaker-3.13.0a0-2b8766e |
|-----------|:------------------------------------------------------:|:-------------------------------------------------------------------------------:|
| mako      | 10.7 ms                                                | 10.8 ms: 1.01x slower                                                           |

All benchmarks:
===============

| Benchmark                | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230913-linux-x86_64-faster%2dcpython-tidy_up_eval_breaker-3.13.0a0-2b8766e |
|--------------------------|:------------------------------------------------------:|:-------------------------------------------------------------------------------:|
| crypto_pyaes             | 77.2 ms                                                | 69.4 ms: 1.11x faster                                                           |
| coverage                 | 94.2 ms                                                | 85.0 ms: 1.11x faster                                                           |
| raytrace                 | 294 ms                                                 | 272 ms: 1.08x faster                                                            |
| asyncio_tcp              | 526 ms                                                 | 488 ms: 1.08x faster                                                            |
| async_tree_none          | 469 ms                                                 | 435 ms: 1.08x faster                                                            |
| deltablue                | 3.52 ms                                                | 3.27 ms: 1.08x faster                                                           |
| unpickle                 | 15.0 us                                                | 14.0 us: 1.07x faster                                                           |
| scimark_monte_carlo      | 71.0 ms                                                | 66.2 ms: 1.07x faster                                                           |
| tomli_loads              | 2.22 sec                                               | 2.08 sec: 1.07x faster                                                          |
| unpack_sequence          | 44.8 ns                                                | 42.1 ns: 1.06x faster                                                           |
| logging_format           | 6.90 us                                                | 6.49 us: 1.06x faster                                                           |
| generators               | 31.1 ms                                                | 29.3 ms: 1.06x faster                                                           |
| regex_compile            | 144 ms                                                 | 136 ms: 1.06x faster                                                            |
| chaos                    | 63.5 ms                                                | 60.4 ms: 1.05x faster                                                           |
| tornado_http             | 99.6 ms                                                | 95.1 ms: 1.05x faster                                                           |
| unpickle_list            | 4.95 us                                                | 4.74 us: 1.04x faster                                                           |
| logging_simple           | 6.18 us                                                | 5.92 us: 1.04x faster                                                           |
| sqlglot_parse            | 1.32 ms                                                | 1.27 ms: 1.04x faster                                                           |
| docutils                 | 2.70 sec                                               | 2.60 sec: 1.04x faster                                                          |
| regex_effbot             | 3.55 ms                                                | 3.43 ms: 1.03x faster                                                           |
| sqlglot_transpile        | 1.64 ms                                                | 1.59 ms: 1.03x faster                                                           |
| scimark_sor              | 125 ms                                                 | 121 ms: 1.03x faster                                                            |
| sqlglot_normalize        | 107 ms                                                 | 104 ms: 1.03x faster                                                            |
| coroutines               | 22.4 ms                                                | 21.9 ms: 1.03x faster                                                           |
| scimark_lu               | 114 ms                                                 | 111 ms: 1.03x faster                                                            |
| bench_thread_pool        | 827 us                                                 | 808 us: 1.02x faster                                                            |
| deepcopy                 | 355 us                                                 | 347 us: 1.02x faster                                                            |
| async_tree_memoization   | 573 ms                                                 | 561 ms: 1.02x faster                                                            |
| xml_etree_process        | 58.6 ms                                                | 57.4 ms: 1.02x faster                                                           |
| dulwich_log              | 67.9 ms                                                | 66.6 ms: 1.02x faster                                                           |
| pickle_pure_python       | 309 us                                                 | 303 us: 1.02x faster                                                            |
| sqlite_synth             | 2.76 us                                                | 2.71 us: 1.02x faster                                                           |
| pprint_pformat           | 1.50 sec                                               | 1.47 sec: 1.02x faster                                                          |
| pickle_list              | 4.62 us                                                | 4.54 us: 1.02x faster                                                           |
| sqlglot_optimize         | 53.3 ms                                                | 52.4 ms: 1.02x faster                                                           |
| mypy2                    | 344 ms                                                 | 338 ms: 1.02x faster                                                            |
| xml_etree_iterparse      | 104 ms                                                 | 102 ms: 1.02x faster                                                            |
| pprint_safe_repr         | 735 ms                                                 | 724 ms: 1.02x faster                                                            |
| xml_etree_parse          | 154 ms                                                 | 151 ms: 1.01x faster                                                            |
| typing_runtime_protocols | 146 us                                                 | 144 us: 1.01x faster                                                            |
| async_tree_cpu_io_mixed  | 714 ms                                                 | 705 ms: 1.01x faster                                                            |
| hexiom                   | 6.12 ms                                                | 6.05 ms: 1.01x faster                                                           |
| scimark_sparse_mat_mult  | 4.74 ms                                                | 4.69 ms: 1.01x faster                                                           |
| xml_etree_generate       | 84.8 ms                                                | 83.9 ms: 1.01x faster                                                           |
| pathlib                  | 18.5 ms                                                | 18.3 ms: 1.01x faster                                                           |
| nqueens                  | 81.1 ms                                                | 80.4 ms: 1.01x faster                                                           |
| json_dumps               | 9.85 ms                                                | 9.76 ms: 1.01x faster                                                           |
| python_startup_no_site   | 6.90 ms                                                | 6.84 ms: 1.01x faster                                                           |
| deepcopy_memo            | 37.4 us                                                | 37.2 us: 1.01x faster                                                           |
| pickle_dict              | 31.6 us                                                | 31.4 us: 1.01x faster                                                           |
| float                    | 80.7 ms                                                | 80.2 ms: 1.01x faster                                                           |
| asyncio_tcp_ssl          | 1.79 sec                                               | 1.79 sec: 1.00x faster                                                          |
| pidigits                 | 187 ms                                                 | 187 ms: 1.00x slower                                                            |
| comprehensions           | 20.4 us                                                | 20.5 us: 1.00x slower                                                           |
| spectral_norm            | 106 ms                                                 | 107 ms: 1.00x slower                                                            |
| gc_traversal             | 3.84 ms                                                | 3.86 ms: 1.00x slower                                                           |
| async_generators         | 440 ms                                                 | 442 ms: 1.00x slower                                                            |
| meteor_contest           | 105 ms                                                 | 105 ms: 1.00x slower                                                            |
| fannkuch                 | 387 ms                                                 | 390 ms: 1.01x slower                                                            |
| pickle                   | 10.6 us                                                | 10.7 us: 1.01x slower                                                           |
| mako                     | 10.7 ms                                                | 10.8 ms: 1.01x slower                                                           |
| pycparser                | 1.15 sec                                               | 1.16 sec: 1.01x slower                                                          |
| create_gc_cycles         | 1.52 ms                                                | 1.54 ms: 1.01x slower                                                           |
| pyflate                  | 450 ms                                                 | 457 ms: 1.01x slower                                                            |
| async_tree_io            | 1.16 sec                                               | 1.18 sec: 1.02x slower                                                          |
| logging_silent           | 99.1 ns                                                | 102 ns: 1.03x slower                                                            |
| mdp                      | 2.57 sec                                               | 2.67 sec: 1.04x slower                                                          |
| go                       | 136 ms                                                 | 141 ms: 1.04x slower                                                            |
| regex_v8                 | 22.3 ms                                                | 23.6 ms: 1.05x slower                                                           |
| python_startup           | 9.47 ms                                                | 10.1 ms: 1.06x slower                                                           |
| richards                 | 43.2 ms                                                | 48.6 ms: 1.13x slower                                                           |
| richards_super           | 49.0 ms                                                | 55.3 ms: 1.13x slower                                                           |
| telco                    | 6.87 ms                                                | 7.97 ms: 1.16x slower                                                           |
| dask                     | 365 ms                                                 | 525 ms: 1.44x slower                                                            |
| Geometric mean           | (ref)                                                  | 1.01x faster                                                                    |

Benchmark hidden because not significant (8): json, nbody, json_loads, unpickle_pure_python, deepcopy_reduce, regex_dna, bench_mp_pool, scimark_fft
Ignored benchmarks (3) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: 2to3, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 99.53% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
