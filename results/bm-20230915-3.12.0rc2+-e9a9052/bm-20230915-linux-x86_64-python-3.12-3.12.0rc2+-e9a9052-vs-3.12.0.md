
# Results vs. 3.12.0

- fork: python
- ref: 3.12
- machine: linux-x86_64
- commit hash: e9a9052
- commit date: 2023-09-15
- overall geometric mean: 1.01x slower
- HPT reliability: 99.66%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230915-linux-x86_64-python-3.12-3.12.0rc2+-e9a9052 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| 2to3           | 268 ms                                                 | 269 ms: 1.01x slower                                    |
| docutils       | 2.70 sec                                               | 2.71 sec: 1.00x slower                                  |
| Geometric mean | (ref)                                                  | 1.00x slower                                            |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230915-linux-x86_64-python-3.12-3.12.0rc2+-e9a9052 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| float          | 80.7 ms                                                | 80.0 ms: 1.01x faster                                   |
| pidigits       | 187 ms                                                 | 187 ms: 1.00x slower                                    |
| nbody          | 88.8 ms                                                | 89.8 ms: 1.01x slower                                   |
| Geometric mean | (ref)                                                  | 1.00x slower                                            |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230915-linux-x86_64-python-3.12-3.12.0rc2+-e9a9052 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| regex_dna      | 209 ms                                                 | 214 ms: 1.03x slower                                    |
| regex_v8       | 22.3 ms                                                | 22.9 ms: 1.03x slower                                   |
| regex_effbot   | 3.55 ms                                                | 3.72 ms: 1.05x slower                                   |
| Geometric mean | (ref)                                                  | 1.02x slower                                            |

Benchmark hidden because not significant (1): regex_compile

Benchmarks with tag 'serialize':
================================

| Benchmark          | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230915-linux-x86_64-python-3.12-3.12.0rc2+-e9a9052 |
|--------------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| pickle_list        | 4.62 us                                                | 4.52 us: 1.02x faster                                   |
| tomli_loads        | 2.22 sec                                               | 2.19 sec: 1.01x faster                                  |
| json_loads         | 25.2 us                                                | 25.0 us: 1.01x faster                                   |
| pickle_dict        | 31.6 us                                                | 31.4 us: 1.01x faster                                   |
| xml_etree_generate | 84.8 ms                                                | 84.4 ms: 1.01x faster                                   |
| pickle_pure_python | 309 us                                                 | 314 us: 1.02x slower                                    |
| unpickle_list      | 4.95 us                                                | 5.40 us: 1.09x slower                                   |
| Geometric mean     | (ref)                                                  | 1.00x slower                                            |

Benchmark hidden because not significant (7): pickle, unpickle_pure_python, xml_etree_iterparse, json_dumps, xml_etree_parse, xml_etree_process, unpickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230915-linux-x86_64-python-3.12-3.12.0rc2+-e9a9052 |
|------------------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| python_startup_no_site | 6.90 ms                                                | 6.88 ms: 1.00x faster                                   |
| python_startup         | 9.47 ms                                                | 9.46 ms: 1.00x faster                                   |
| Geometric mean         | (ref)                                                  | 1.00x faster                                            |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230915-linux-x86_64-python-3.12-3.12.0rc2+-e9a9052 |
|-----------|:------------------------------------------------------:|:-------------------------------------------------------:|
| mako      | 10.7 ms                                                | 10.9 ms: 1.02x slower                                   |

All benchmarks:
===============

| Benchmark                | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230915-linux-x86_64-python-3.12-3.12.0rc2+-e9a9052 |
|--------------------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| pickle_list              | 4.62 us                                                | 4.52 us: 1.02x faster                                   |
| spectral_norm            | 106 ms                                                 | 104 ms: 1.02x faster                                    |
| coroutines               | 22.4 ms                                                | 22.0 ms: 1.02x faster                                   |
| scimark_sor              | 125 ms                                                 | 122 ms: 1.02x faster                                    |
| tomli_loads              | 2.22 sec                                               | 2.19 sec: 1.01x faster                                  |
| scimark_lu               | 114 ms                                                 | 112 ms: 1.01x faster                                    |
| nqueens                  | 81.1 ms                                                | 80.2 ms: 1.01x faster                                   |
| float                    | 80.7 ms                                                | 80.0 ms: 1.01x faster                                   |
| json_loads               | 25.2 us                                                | 25.0 us: 1.01x faster                                   |
| telco                    | 6.87 ms                                                | 6.82 ms: 1.01x faster                                   |
| pickle_dict              | 31.6 us                                                | 31.4 us: 1.01x faster                                   |
| create_gc_cycles         | 1.52 ms                                                | 1.51 ms: 1.01x faster                                   |
| xml_etree_generate       | 84.8 ms                                                | 84.4 ms: 1.01x faster                                   |
| async_tree_io            | 1.16 sec                                               | 1.15 sec: 1.00x faster                                  |
| asyncio_tcp              | 526 ms                                                 | 524 ms: 1.00x faster                                    |
| hexiom                   | 6.12 ms                                                | 6.11 ms: 1.00x faster                                   |
| python_startup_no_site   | 6.90 ms                                                | 6.88 ms: 1.00x faster                                   |
| python_startup           | 9.47 ms                                                | 9.46 ms: 1.00x faster                                   |
| pidigits                 | 187 ms                                                 | 187 ms: 1.00x slower                                    |
| mypy2                    | 344 ms                                                 | 345 ms: 1.00x slower                                    |
| crypto_pyaes             | 77.2 ms                                                | 77.4 ms: 1.00x slower                                   |
| pprint_safe_repr         | 735 ms                                                 | 737 ms: 1.00x slower                                    |
| docutils                 | 2.70 sec                                               | 2.71 sec: 1.00x slower                                  |
| pprint_pformat           | 1.50 sec                                               | 1.51 sec: 1.00x slower                                  |
| scimark_fft              | 358 ms                                                 | 360 ms: 1.01x slower                                    |
| asyncio_tcp_ssl          | 1.79 sec                                               | 1.80 sec: 1.01x slower                                  |
| bench_thread_pool        | 827 us                                                 | 833 us: 1.01x slower                                    |
| 2to3                     | 268 ms                                                 | 269 ms: 1.01x slower                                    |
| sqlglot_normalize        | 107 ms                                                 | 108 ms: 1.01x slower                                    |
| sqlite_synth             | 2.76 us                                                | 2.79 us: 1.01x slower                                   |
| pycparser                | 1.15 sec                                               | 1.16 sec: 1.01x slower                                  |
| async_generators         | 440 ms                                                 | 445 ms: 1.01x slower                                    |
| deepcopy_reduce          | 3.14 us                                                | 3.17 us: 1.01x slower                                   |
| nbody                    | 88.8 ms                                                | 89.8 ms: 1.01x slower                                   |
| typing_runtime_protocols | 146 us                                                 | 148 us: 1.01x slower                                    |
| deepcopy_memo            | 37.4 us                                                | 37.9 us: 1.01x slower                                   |
| raytrace                 | 294 ms                                                 | 299 ms: 1.01x slower                                    |
| pathlib                  | 18.5 ms                                                | 18.8 ms: 1.01x slower                                   |
| deltablue                | 3.52 ms                                                | 3.57 ms: 1.02x slower                                   |
| pickle_pure_python       | 309 us                                                 | 314 us: 1.02x slower                                    |
| mako                     | 10.7 ms                                                | 10.9 ms: 1.02x slower                                   |
| comprehensions           | 20.4 us                                                | 20.9 us: 1.02x slower                                   |
| fannkuch                 | 387 ms                                                 | 395 ms: 1.02x slower                                    |
| scimark_sparse_mat_mult  | 4.74 ms                                                | 4.84 ms: 1.02x slower                                   |
| richards                 | 43.2 ms                                                | 44.1 ms: 1.02x slower                                   |
| meteor_contest           | 105 ms                                                 | 107 ms: 1.02x slower                                    |
| regex_dna                | 209 ms                                                 | 214 ms: 1.03x slower                                    |
| regex_v8                 | 22.3 ms                                                | 22.9 ms: 1.03x slower                                   |
| richards_super           | 49.0 ms                                                | 50.3 ms: 1.03x slower                                   |
| logging_format           | 6.90 us                                                | 7.11 us: 1.03x slower                                   |
| gc_traversal             | 3.84 ms                                                | 3.96 ms: 1.03x slower                                   |
| logging_simple           | 6.18 us                                                | 6.38 us: 1.03x slower                                   |
| pyflate                  | 450 ms                                                 | 466 ms: 1.03x slower                                    |
| logging_silent           | 99.1 ns                                                | 103 ns: 1.04x slower                                    |
| generators               | 31.1 ms                                                | 32.3 ms: 1.04x slower                                   |
| mdp                      | 2.57 sec                                               | 2.68 sec: 1.04x slower                                  |
| regex_effbot             | 3.55 ms                                                | 3.72 ms: 1.05x slower                                   |
| unpickle_list            | 4.95 us                                                | 5.40 us: 1.09x slower                                   |
| unpack_sequence          | 44.8 ns                                                | 50.3 ns: 1.12x slower                                   |
| dask                     | 365 ms                                                 | 535 ms: 1.47x slower                                    |
| Geometric mean           | (ref)                                                  | 1.01x slower                                            |

Benchmark hidden because not significant (25): pickle, unpickle_pure_python, regex_compile, xml_etree_iterparse, json_dumps, async_tree_memoization, scimark_monte_carlo, sqlglot_optimize, deepcopy, dulwich_log, chaos, async_tree_none, bench_mp_pool, async_tree_cpu_io_mixed, tornado_http, go, sqlglot_transpile, xml_etree_parse, xml_etree_process, sqlglot_parse, coverage, sqlalchemy_imperative, sqlalchemy_declarative, json, unpickle


# HPT report

- Reliability score: 99.66% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
