
# Results vs. 3.12.0

- fork: python
- ref: v3.12.0rc1
- machine: linux-x86_64
- commit hash: 63bcd91
- commit date: 2023-08-05
- overall geometric mean: 1.01x slower
- HPT reliability: 91.04%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230805-linux-x86_64-python-v3.12.0rc1-3.12.0rc1-63bcd91 |
|----------------|:------------------------------------------------------:|:------------------------------------------------------------:|
| 2to3           | 268 ms                                                 | 267 ms: 1.00x faster                                         |
| Geometric mean | (ref)                                                  | 1.00x faster                                                 |

Benchmark hidden because not significant (2): docutils, tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230805-linux-x86_64-python-v3.12.0rc1-3.12.0rc1-63bcd91 |
|----------------|:------------------------------------------------------:|:------------------------------------------------------------:|
| float          | 80.7 ms                                                | 79.3 ms: 1.02x faster                                        |
| nbody          | 88.8 ms                                                | 89.6 ms: 1.01x slower                                        |
| pidigits       | 187 ms                                                 | 201 ms: 1.07x slower                                         |
| Geometric mean | (ref)                                                  | 1.02x slower                                                 |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230805-linux-x86_64-python-v3.12.0rc1-3.12.0rc1-63bcd91 |
|----------------|:------------------------------------------------------:|:------------------------------------------------------------:|
| regex_effbot   | 3.55 ms                                                | 3.52 ms: 1.01x faster                                        |
| regex_v8       | 22.3 ms                                                | 22.5 ms: 1.01x slower                                        |
| regex_compile  | 144 ms                                                 | 145 ms: 1.01x slower                                         |
| Geometric mean | (ref)                                                  | 1.00x slower                                                 |

Benchmark hidden because not significant (1): regex_dna

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230805-linux-x86_64-python-v3.12.0rc1-3.12.0rc1-63bcd91 |
|----------------------|:------------------------------------------------------:|:------------------------------------------------------------:|
| pickle_list          | 4.62 us                                                | 4.55 us: 1.02x faster                                        |
| json_dumps           | 9.85 ms                                                | 9.75 ms: 1.01x faster                                        |
| pickle_dict          | 31.6 us                                                | 31.4 us: 1.01x faster                                        |
| unpickle_pure_python | 218 us                                                 | 219 us: 1.01x slower                                         |
| pickle_pure_python   | 309 us                                                 | 311 us: 1.01x slower                                         |
| unpickle_list        | 4.95 us                                                | 4.98 us: 1.01x slower                                        |
| xml_etree_generate   | 84.8 ms                                                | 85.4 ms: 1.01x slower                                        |
| xml_etree_parse      | 154 ms                                                 | 155 ms: 1.01x slower                                         |
| xml_etree_process    | 58.6 ms                                                | 59.2 ms: 1.01x slower                                        |
| pickle               | 10.6 us                                                | 10.8 us: 1.02x slower                                        |
| Geometric mean       | (ref)                                                  | 1.00x slower                                                 |

Benchmark hidden because not significant (4): unpickle, tomli_loads, xml_etree_iterparse, json_loads

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230805-linux-x86_64-python-v3.12.0rc1-3.12.0rc1-63bcd91 |
|------------------------|:------------------------------------------------------:|:------------------------------------------------------------:|
| python_startup_no_site | 6.90 ms                                                | 6.76 ms: 1.02x faster                                        |
| python_startup         | 9.47 ms                                                | 9.30 ms: 1.02x faster                                        |
| Geometric mean         | (ref)                                                  | 1.02x faster                                                 |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230805-linux-x86_64-python-v3.12.0rc1-3.12.0rc1-63bcd91 |
|-----------|:------------------------------------------------------:|:------------------------------------------------------------:|
| mako      | 10.7 ms                                                | 10.7 ms: 1.00x faster                                        |

All benchmarks:
===============

| Benchmark                | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230805-linux-x86_64-python-v3.12.0rc1-3.12.0rc1-63bcd91 |
|--------------------------|:------------------------------------------------------:|:------------------------------------------------------------:|
| generators               | 31.1 ms                                                | 30.2 ms: 1.03x faster                                        |
| python_startup_no_site   | 6.90 ms                                                | 6.76 ms: 1.02x faster                                        |
| asyncio_tcp              | 526 ms                                                 | 515 ms: 1.02x faster                                         |
| python_startup           | 9.47 ms                                                | 9.30 ms: 1.02x faster                                        |
| float                    | 80.7 ms                                                | 79.3 ms: 1.02x faster                                        |
| pickle_list              | 4.62 us                                                | 4.55 us: 1.02x faster                                        |
| pyflate                  | 450 ms                                                 | 444 ms: 1.01x faster                                         |
| pathlib                  | 18.5 ms                                                | 18.3 ms: 1.01x faster                                        |
| mdp                      | 2.57 sec                                               | 2.54 sec: 1.01x faster                                       |
| json_dumps               | 9.85 ms                                                | 9.75 ms: 1.01x faster                                        |
| deepcopy_memo            | 37.4 us                                                | 37.1 us: 1.01x faster                                        |
| pickle_dict              | 31.6 us                                                | 31.4 us: 1.01x faster                                        |
| regex_effbot             | 3.55 ms                                                | 3.52 ms: 1.01x faster                                        |
| create_gc_cycles         | 1.52 ms                                                | 1.51 ms: 1.01x faster                                        |
| scimark_fft              | 358 ms                                                 | 356 ms: 1.01x faster                                         |
| mako                     | 10.7 ms                                                | 10.7 ms: 1.00x faster                                        |
| pprint_pformat           | 1.50 sec                                               | 1.50 sec: 1.00x faster                                       |
| 2to3                     | 268 ms                                                 | 267 ms: 1.00x faster                                         |
| asyncio_tcp_ssl          | 1.79 sec                                               | 1.80 sec: 1.00x slower                                       |
| nqueens                  | 81.1 ms                                                | 81.5 ms: 1.00x slower                                        |
| unpickle_pure_python     | 218 us                                                 | 219 us: 1.01x slower                                         |
| pickle_pure_python       | 309 us                                                 | 311 us: 1.01x slower                                         |
| bench_thread_pool        | 827 us                                                 | 832 us: 1.01x slower                                         |
| async_tree_io            | 1.16 sec                                               | 1.16 sec: 1.01x slower                                       |
| unpickle_list            | 4.95 us                                                | 4.98 us: 1.01x slower                                        |
| xml_etree_generate       | 84.8 ms                                                | 85.4 ms: 1.01x slower                                        |
| regex_v8                 | 22.3 ms                                                | 22.5 ms: 1.01x slower                                        |
| xml_etree_parse          | 154 ms                                                 | 155 ms: 1.01x slower                                         |
| chaos                    | 63.5 ms                                                | 64.0 ms: 1.01x slower                                        |
| regex_compile            | 144 ms                                                 | 145 ms: 1.01x slower                                         |
| nbody                    | 88.8 ms                                                | 89.6 ms: 1.01x slower                                        |
| dulwich_log              | 67.9 ms                                                | 68.5 ms: 1.01x slower                                        |
| deltablue                | 3.52 ms                                                | 3.55 ms: 1.01x slower                                        |
| scimark_monte_carlo      | 71.0 ms                                                | 71.7 ms: 1.01x slower                                        |
| coroutines               | 22.4 ms                                                | 22.7 ms: 1.01x slower                                        |
| comprehensions           | 20.4 us                                                | 20.7 us: 1.01x slower                                        |
| raytrace                 | 294 ms                                                 | 297 ms: 1.01x slower                                         |
| xml_etree_process        | 58.6 ms                                                | 59.2 ms: 1.01x slower                                        |
| logging_format           | 6.90 us                                                | 6.99 us: 1.01x slower                                        |
| hexiom                   | 6.12 ms                                                | 6.21 ms: 1.01x slower                                        |
| sqlglot_transpile        | 1.64 ms                                                | 1.67 ms: 1.02x slower                                        |
| pickle                   | 10.6 us                                                | 10.8 us: 1.02x slower                                        |
| crypto_pyaes             | 77.2 ms                                                | 78.4 ms: 1.02x slower                                        |
| gc_traversal             | 3.84 ms                                                | 3.91 ms: 1.02x slower                                        |
| fannkuch                 | 387 ms                                                 | 394 ms: 1.02x slower                                         |
| sqlglot_optimize         | 53.3 ms                                                | 54.3 ms: 1.02x slower                                        |
| async_generators         | 440 ms                                                 | 450 ms: 1.02x slower                                         |
| sqlglot_parse            | 1.32 ms                                                | 1.35 ms: 1.02x slower                                        |
| typing_runtime_protocols | 146 us                                                 | 149 us: 1.02x slower                                         |
| richards                 | 43.2 ms                                                | 44.3 ms: 1.03x slower                                        |
| richards_super           | 49.0 ms                                                | 50.3 ms: 1.03x slower                                        |
| scimark_sparse_mat_mult  | 4.74 ms                                                | 4.89 ms: 1.03x slower                                        |
| logging_silent           | 99.1 ns                                                | 102 ns: 1.03x slower                                         |
| sqlglot_normalize        | 107 ms                                                 | 111 ms: 1.03x slower                                         |
| pidigits                 | 187 ms                                                 | 201 ms: 1.07x slower                                         |
| unpack_sequence          | 44.8 ns                                                | 52.6 ns: 1.17x slower                                        |
| dask                     | 365 ms                                                 | 537 ms: 1.47x slower                                         |
| Geometric mean           | (ref)                                                  | 1.01x slower                                                 |

Benchmark hidden because not significant (28): async_tree_cpu_io_mixed, pycparser, tornado_http, sqlite_synth, go, telco, unpickle, sqlalchemy_imperative, mypy2, tomli_loads, deepcopy, meteor_contest, json, docutils, async_tree_memoization, deepcopy_reduce, bench_mp_pool, coverage, scimark_sor, pprint_safe_repr, xml_etree_iterparse, async_tree_none, scimark_lu, logging_simple, sqlalchemy_declarative, regex_dna, spectral_norm, json_loads


# HPT report

- Reliability score: 91.04% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
