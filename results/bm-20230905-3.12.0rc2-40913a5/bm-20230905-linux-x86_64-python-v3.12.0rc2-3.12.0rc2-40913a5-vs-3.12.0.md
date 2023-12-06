
# Results vs. 3.12.0

- fork: python
- ref: v3.12.0rc2
- machine: linux-x86_64
- commit hash: 40913a5
- commit date: 2023-09-05
- overall geometric mean: 1.01x slower
- HPT reliability: 99.32%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230905-linux-x86_64-python-v3.12.0rc2-3.12.0rc2-40913a5 |
|----------------|:------------------------------------------------------:|:------------------------------------------------------------:|
| 2to3           | 268 ms                                                 | 268 ms: 1.00x slower                                         |
| tornado_http   | 99.6 ms                                                | 102 ms: 1.02x slower                                         |
| Geometric mean | (ref)                                                  | 1.01x slower                                                 |

Benchmark hidden because not significant (1): docutils

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230905-linux-x86_64-python-v3.12.0rc2-3.12.0rc2-40913a5 |
|----------------|:------------------------------------------------------:|:------------------------------------------------------------:|
| float          | 80.7 ms                                                | 80.1 ms: 1.01x faster                                        |
| nbody          | 88.8 ms                                                | 93.4 ms: 1.05x slower                                        |
| pidigits       | 187 ms                                                 | 212 ms: 1.13x slower                                         |
| Geometric mean | (ref)                                                  | 1.06x slower                                                 |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230905-linux-x86_64-python-v3.12.0rc2-3.12.0rc2-40913a5 |
|----------------|:------------------------------------------------------:|:------------------------------------------------------------:|
| regex_effbot   | 3.55 ms                                                | 3.59 ms: 1.01x slower                                        |
| regex_dna      | 209 ms                                                 | 213 ms: 1.02x slower                                         |
| Geometric mean | (ref)                                                  | 1.01x slower                                                 |

Benchmark hidden because not significant (2): regex_v8, regex_compile

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230905-linux-x86_64-python-v3.12.0rc2-3.12.0rc2-40913a5 |
|----------------------|:------------------------------------------------------:|:------------------------------------------------------------:|
| tomli_loads          | 2.22 sec                                               | 2.20 sec: 1.01x faster                                       |
| xml_etree_generate   | 84.8 ms                                                | 84.3 ms: 1.01x faster                                        |
| json_loads           | 25.2 us                                                | 25.1 us: 1.01x faster                                        |
| unpickle_pure_python | 218 us                                                 | 219 us: 1.00x slower                                         |
| pickle_dict          | 31.6 us                                                | 31.8 us: 1.00x slower                                        |
| unpickle             | 15.0 us                                                | 15.1 us: 1.01x slower                                        |
| pickle_list          | 4.62 us                                                | 4.67 us: 1.01x slower                                        |
| pickle_pure_python   | 309 us                                                 | 314 us: 1.02x slower                                         |
| unpickle_list        | 4.95 us                                                | 5.38 us: 1.09x slower                                        |
| Geometric mean       | (ref)                                                  | 1.01x slower                                                 |

Benchmark hidden because not significant (5): xml_etree_iterparse, pickle, xml_etree_parse, xml_etree_process, json_dumps

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230905-linux-x86_64-python-v3.12.0rc2-3.12.0rc2-40913a5 |
|------------------------|:------------------------------------------------------:|:------------------------------------------------------------:|
| python_startup_no_site | 6.90 ms                                                | 6.88 ms: 1.00x faster                                        |
| python_startup         | 9.47 ms                                                | 9.46 ms: 1.00x faster                                        |
| Geometric mean         | (ref)                                                  | 1.00x faster                                                 |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230905-linux-x86_64-python-v3.12.0rc2-3.12.0rc2-40913a5 |
|-----------|:------------------------------------------------------:|:------------------------------------------------------------:|
| mako      | 10.7 ms                                                | 10.9 ms: 1.02x slower                                        |

All benchmarks:
===============

| Benchmark                | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230905-linux-x86_64-python-v3.12.0rc2-3.12.0rc2-40913a5 |
|--------------------------|:------------------------------------------------------:|:------------------------------------------------------------:|
| asyncio_tcp              | 526 ms                                                 | 505 ms: 1.04x faster                                         |
| coroutines               | 22.4 ms                                                | 22.1 ms: 1.02x faster                                        |
| async_tree_io            | 1.16 sec                                               | 1.14 sec: 1.02x faster                                       |
| deepcopy                 | 355 us                                                 | 351 us: 1.01x faster                                         |
| typing_runtime_protocols | 146 us                                                 | 144 us: 1.01x faster                                         |
| async_tree_none          | 469 ms                                                 | 465 ms: 1.01x faster                                         |
| deltablue                | 3.52 ms                                                | 3.49 ms: 1.01x faster                                        |
| generators               | 31.1 ms                                                | 30.8 ms: 1.01x faster                                        |
| float                    | 80.7 ms                                                | 80.1 ms: 1.01x faster                                        |
| tomli_loads              | 2.22 sec                                               | 2.20 sec: 1.01x faster                                       |
| pathlib                  | 18.5 ms                                                | 18.4 ms: 1.01x faster                                        |
| create_gc_cycles         | 1.52 ms                                                | 1.51 ms: 1.01x faster                                        |
| xml_etree_generate       | 84.8 ms                                                | 84.3 ms: 1.01x faster                                        |
| logging_silent           | 99.1 ns                                                | 98.5 ns: 1.01x faster                                        |
| sqlite_synth             | 2.76 us                                                | 2.74 us: 1.01x faster                                        |
| telco                    | 6.87 ms                                                | 6.83 ms: 1.01x faster                                        |
| json_loads               | 25.2 us                                                | 25.1 us: 1.01x faster                                        |
| deepcopy_reduce          | 3.14 us                                                | 3.12 us: 1.01x faster                                        |
| gc_traversal             | 3.84 ms                                                | 3.83 ms: 1.00x faster                                        |
| python_startup_no_site   | 6.90 ms                                                | 6.88 ms: 1.00x faster                                        |
| python_startup           | 9.47 ms                                                | 9.46 ms: 1.00x faster                                        |
| 2to3                     | 268 ms                                                 | 268 ms: 1.00x slower                                         |
| asyncio_tcp_ssl          | 1.79 sec                                               | 1.80 sec: 1.00x slower                                       |
| nqueens                  | 81.1 ms                                                | 81.4 ms: 1.00x slower                                        |
| unpickle_pure_python     | 218 us                                                 | 219 us: 1.00x slower                                         |
| sqlglot_optimize         | 53.3 ms                                                | 53.5 ms: 1.00x slower                                        |
| pickle_dict              | 31.6 us                                                | 31.8 us: 1.00x slower                                        |
| dulwich_log              | 67.9 ms                                                | 68.2 ms: 1.00x slower                                        |
| chaos                    | 63.5 ms                                                | 63.8 ms: 1.00x slower                                        |
| scimark_monte_carlo      | 71.0 ms                                                | 71.4 ms: 1.00x slower                                        |
| pprint_pformat           | 1.50 sec                                               | 1.51 sec: 1.01x slower                                       |
| sqlglot_normalize        | 107 ms                                                 | 108 ms: 1.01x slower                                         |
| unpickle                 | 15.0 us                                                | 15.1 us: 1.01x slower                                        |
| hexiom                   | 6.12 ms                                                | 6.17 ms: 1.01x slower                                        |
| sqlglot_parse            | 1.32 ms                                                | 1.33 ms: 1.01x slower                                        |
| pycparser                | 1.15 sec                                               | 1.16 sec: 1.01x slower                                       |
| async_generators         | 440 ms                                                 | 445 ms: 1.01x slower                                         |
| pickle_list              | 4.62 us                                                | 4.67 us: 1.01x slower                                        |
| regex_effbot             | 3.55 ms                                                | 3.59 ms: 1.01x slower                                        |
| meteor_contest           | 105 ms                                                 | 106 ms: 1.01x slower                                         |
| scimark_sparse_mat_mult  | 4.74 ms                                                | 4.81 ms: 1.01x slower                                        |
| comprehensions           | 20.4 us                                                | 20.7 us: 1.01x slower                                        |
| scimark_fft              | 358 ms                                                 | 364 ms: 1.02x slower                                         |
| pickle_pure_python       | 309 us                                                 | 314 us: 1.02x slower                                         |
| logging_simple           | 6.18 us                                                | 6.28 us: 1.02x slower                                        |
| unpack_sequence          | 44.8 ns                                                | 45.6 ns: 1.02x slower                                        |
| mako                     | 10.7 ms                                                | 10.9 ms: 1.02x slower                                        |
| tornado_http             | 99.6 ms                                                | 102 ms: 1.02x slower                                         |
| regex_dna                | 209 ms                                                 | 213 ms: 1.02x slower                                         |
| logging_format           | 6.90 us                                                | 7.08 us: 1.03x slower                                        |
| crypto_pyaes             | 77.2 ms                                                | 79.6 ms: 1.03x slower                                        |
| fannkuch                 | 387 ms                                                 | 400 ms: 1.03x slower                                         |
| pyflate                  | 450 ms                                                 | 467 ms: 1.04x slower                                         |
| nbody                    | 88.8 ms                                                | 93.4 ms: 1.05x slower                                        |
| unpickle_list            | 4.95 us                                                | 5.38 us: 1.09x slower                                        |
| pidigits                 | 187 ms                                                 | 212 ms: 1.13x slower                                         |
| dask                     | 365 ms                                                 | 537 ms: 1.47x slower                                         |
| Geometric mean           | (ref)                                                  | 1.01x slower                                                 |

Benchmark hidden because not significant (28): async_tree_cpu_io_mixed, scimark_lu, async_tree_memoization, xml_etree_iterparse, pickle, raytrace, scimark_sor, richards_super, regex_v8, spectral_norm, go, sqlalchemy_imperative, bench_mp_pool, mypy2, pprint_safe_repr, bench_thread_pool, regex_compile, xml_etree_parse, deepcopy_memo, xml_etree_process, richards, mdp, docutils, json_dumps, sqlglot_transpile, coverage, json, sqlalchemy_declarative


# HPT report

- Reliability score: 99.32% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
