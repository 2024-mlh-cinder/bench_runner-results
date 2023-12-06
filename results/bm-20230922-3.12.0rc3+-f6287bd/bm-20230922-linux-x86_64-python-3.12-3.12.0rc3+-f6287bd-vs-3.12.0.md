
# Results vs. 3.12.0

- fork: python
- ref: 3.12
- machine: linux-x86_64
- commit hash: f6287bd
- commit date: 2023-09-22
- overall geometric mean: 1.00x slower
- HPT reliability: 95.40%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230922-linux-x86_64-python-3.12-3.12.0rc3+-f6287bd |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| 2to3           | 268 ms                                                 | 268 ms: 1.00x slower                                    |
| docutils       | 2.70 sec                                               | 2.72 sec: 1.01x slower                                  |
| Geometric mean | (ref)                                                  | 1.00x slower                                            |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'math':
===========================

Benchmark hidden because not significant (3): float, nbody, pidigits

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230922-linux-x86_64-python-3.12-3.12.0rc3+-f6287bd |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| regex_v8       | 22.3 ms                                                | 22.5 ms: 1.01x slower                                   |
| regex_dna      | 209 ms                                                 | 214 ms: 1.02x slower                                    |
| regex_effbot   | 3.55 ms                                                | 3.66 ms: 1.03x slower                                   |
| Geometric mean | (ref)                                                  | 1.02x slower                                            |

Benchmark hidden because not significant (1): regex_compile

Benchmarks with tag 'serialize':
================================

| Benchmark           | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230922-linux-x86_64-python-3.12-3.12.0rc3+-f6287bd |
|---------------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| xml_etree_iterparse | 104 ms                                                 | 102 ms: 1.01x faster                                    |
| pickle              | 10.6 us                                                | 10.5 us: 1.01x faster                                   |
| json_loads          | 25.2 us                                                | 25.0 us: 1.01x faster                                   |
| tomli_loads         | 2.22 sec                                               | 2.19 sec: 1.01x faster                                  |
| unpickle            | 15.0 us                                                | 14.9 us: 1.01x faster                                   |
| json_dumps          | 9.85 ms                                                | 9.79 ms: 1.01x faster                                   |
| pickle_list         | 4.62 us                                                | 4.65 us: 1.01x slower                                   |
| xml_etree_process   | 58.6 ms                                                | 59.0 ms: 1.01x slower                                   |
| pickle_dict         | 31.6 us                                                | 31.9 us: 1.01x slower                                   |
| pickle_pure_python  | 309 us                                                 | 315 us: 1.02x slower                                    |
| unpickle_list       | 4.95 us                                                | 5.07 us: 1.02x slower                                   |
| Geometric mean      | (ref)                                                  | 1.00x slower                                            |

Benchmark hidden because not significant (3): xml_etree_parse, xml_etree_generate, unpickle_pure_python

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230922-linux-x86_64-python-3.12-3.12.0rc3+-f6287bd |
|------------------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| python_startup_no_site | 6.90 ms                                                | 6.90 ms: 1.00x faster                                   |
| python_startup         | 9.47 ms                                                | 9.47 ms: 1.00x slower                                   |
| Geometric mean         | (ref)                                                  | 1.00x slower                                            |

Benchmarks with tag 'template':
===============================

Benchmark hidden because not significant (1): mako

All benchmarks:
===============

| Benchmark                | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230922-linux-x86_64-python-3.12-3.12.0rc3+-f6287bd |
|--------------------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| generators               | 31.1 ms                                                | 30.1 ms: 1.03x faster                                   |
| fannkuch                 | 387 ms                                                 | 379 ms: 1.02x faster                                    |
| async_tree_io            | 1.16 sec                                               | 1.14 sec: 1.02x faster                                  |
| coroutines               | 22.4 ms                                                | 22.1 ms: 1.02x faster                                   |
| create_gc_cycles         | 1.52 ms                                                | 1.50 ms: 1.01x faster                                   |
| xml_etree_iterparse      | 104 ms                                                 | 102 ms: 1.01x faster                                    |
| async_tree_none          | 469 ms                                                 | 464 ms: 1.01x faster                                    |
| scimark_lu               | 114 ms                                                 | 113 ms: 1.01x faster                                    |
| async_tree_memoization   | 573 ms                                                 | 566 ms: 1.01x faster                                    |
| pickle                   | 10.6 us                                                | 10.5 us: 1.01x faster                                   |
| json_loads               | 25.2 us                                                | 25.0 us: 1.01x faster                                   |
| tomli_loads              | 2.22 sec                                               | 2.19 sec: 1.01x faster                                  |
| scimark_sor              | 125 ms                                                 | 123 ms: 1.01x faster                                    |
| scimark_monte_carlo      | 71.0 ms                                                | 70.4 ms: 1.01x faster                                   |
| unpickle                 | 15.0 us                                                | 14.9 us: 1.01x faster                                   |
| json_dumps               | 9.85 ms                                                | 9.79 ms: 1.01x faster                                   |
| mdp                      | 2.57 sec                                               | 2.56 sec: 1.00x faster                                  |
| asyncio_tcp_ssl          | 1.79 sec                                               | 1.79 sec: 1.00x faster                                  |
| python_startup_no_site   | 6.90 ms                                                | 6.90 ms: 1.00x faster                                   |
| python_startup           | 9.47 ms                                                | 9.47 ms: 1.00x slower                                   |
| 2to3                     | 268 ms                                                 | 268 ms: 1.00x slower                                    |
| mypy2                    | 344 ms                                                 | 344 ms: 1.00x slower                                    |
| dulwich_log              | 67.9 ms                                                | 68.1 ms: 1.00x slower                                   |
| pprint_pformat           | 1.50 sec                                               | 1.51 sec: 1.00x slower                                  |
| sqlglot_optimize         | 53.3 ms                                                | 53.5 ms: 1.00x slower                                   |
| chaos                    | 63.5 ms                                                | 63.8 ms: 1.00x slower                                   |
| go                       | 136 ms                                                 | 136 ms: 1.00x slower                                    |
| bench_thread_pool        | 827 us                                                 | 831 us: 1.00x slower                                    |
| regex_v8                 | 22.3 ms                                                | 22.5 ms: 1.01x slower                                   |
| hexiom                   | 6.12 ms                                                | 6.17 ms: 1.01x slower                                   |
| pickle_list              | 4.62 us                                                | 4.65 us: 1.01x slower                                   |
| docutils                 | 2.70 sec                                               | 2.72 sec: 1.01x slower                                  |
| xml_etree_process        | 58.6 ms                                                | 59.0 ms: 1.01x slower                                   |
| pickle_dict              | 31.6 us                                                | 31.9 us: 1.01x slower                                   |
| pycparser                | 1.15 sec                                               | 1.16 sec: 1.01x slower                                  |
| pprint_safe_repr         | 735 ms                                                 | 741 ms: 1.01x slower                                    |
| deepcopy_reduce          | 3.14 us                                                | 3.17 us: 1.01x slower                                   |
| deltablue                | 3.52 ms                                                | 3.55 ms: 1.01x slower                                   |
| deepcopy_memo            | 37.4 us                                                | 37.8 us: 1.01x slower                                   |
| sqlglot_normalize        | 107 ms                                                 | 108 ms: 1.01x slower                                    |
| raytrace                 | 294 ms                                                 | 298 ms: 1.01x slower                                    |
| meteor_contest           | 105 ms                                                 | 106 ms: 1.01x slower                                    |
| asyncio_tcp              | 526 ms                                                 | 533 ms: 1.01x slower                                    |
| scimark_sparse_mat_mult  | 4.74 ms                                                | 4.82 ms: 1.01x slower                                   |
| logging_format           | 6.90 us                                                | 7.01 us: 1.02x slower                                   |
| typing_runtime_protocols | 146 us                                                 | 148 us: 1.02x slower                                    |
| spectral_norm            | 106 ms                                                 | 108 ms: 1.02x slower                                    |
| coverage                 | 94.2 ms                                                | 95.8 ms: 1.02x slower                                   |
| logging_simple           | 6.18 us                                                | 6.29 us: 1.02x slower                                   |
| pickle_pure_python       | 309 us                                                 | 315 us: 1.02x slower                                    |
| richards                 | 43.2 ms                                                | 44.0 ms: 1.02x slower                                   |
| scimark_fft              | 358 ms                                                 | 366 ms: 1.02x slower                                    |
| richards_super           | 49.0 ms                                                | 50.0 ms: 1.02x slower                                   |
| regex_dna                | 209 ms                                                 | 214 ms: 1.02x slower                                    |
| unpickle_list            | 4.95 us                                                | 5.07 us: 1.02x slower                                   |
| regex_effbot             | 3.55 ms                                                | 3.66 ms: 1.03x slower                                   |
| logging_silent           | 99.1 ns                                                | 103 ns: 1.04x slower                                    |
| crypto_pyaes             | 77.2 ms                                                | 80.4 ms: 1.04x slower                                   |
| gc_traversal             | 3.84 ms                                                | 4.09 ms: 1.06x slower                                   |
| unpack_sequence          | 44.8 ns                                                | 47.9 ns: 1.07x slower                                   |
| Geometric mean           | (ref)                                                  | 1.00x slower                                            |

Benchmark hidden because not significant (25): async_tree_cpu_io_mixed, float, nqueens, pyflate, xml_etree_parse, sqlalchemy_imperative, comprehensions, pathlib, nbody, xml_etree_generate, bench_mp_pool, pidigits, regex_compile, dask, telco, sqlite_synth, sqlglot_transpile, deepcopy, unpickle_pure_python, async_generators, sqlglot_parse, tornado_http, mako, sqlalchemy_declarative, json


# HPT report

- Reliability score: 95.40% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
