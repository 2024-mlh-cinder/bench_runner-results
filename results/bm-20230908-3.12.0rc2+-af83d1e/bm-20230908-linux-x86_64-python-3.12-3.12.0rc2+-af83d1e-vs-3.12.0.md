
# Results vs. 3.12.0

- fork: python
- ref: 3.12
- machine: linux-x86_64
- commit hash: af83d1e
- commit date: 2023-09-08
- overall geometric mean: 1.01x slower
- HPT reliability: 97.13%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230908-linux-x86_64-python-3.12-3.12.0rc2+-af83d1e |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| 2to3           | 268 ms                                                 | 270 ms: 1.01x slower                                    |
| docutils       | 2.70 sec                                               | 2.72 sec: 1.01x slower                                  |
| Geometric mean | (ref)                                                  | 1.01x slower                                            |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230908-linux-x86_64-python-3.12-3.12.0rc2+-af83d1e |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| float          | 80.7 ms                                                | 79.0 ms: 1.02x faster                                   |
| pidigits       | 187 ms                                                 | 212 ms: 1.13x slower                                    |
| Geometric mean | (ref)                                                  | 1.03x slower                                            |

Benchmark hidden because not significant (1): nbody

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230908-linux-x86_64-python-3.12-3.12.0rc2+-af83d1e |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| regex_dna      | 209 ms                                                 | 211 ms: 1.01x slower                                    |
| regex_v8       | 22.3 ms                                                | 22.9 ms: 1.02x slower                                   |
| regex_effbot   | 3.55 ms                                                | 3.73 ms: 1.05x slower                                   |
| Geometric mean | (ref)                                                  | 1.02x slower                                            |

Benchmark hidden because not significant (1): regex_compile

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230908-linux-x86_64-python-3.12-3.12.0rc2+-af83d1e |
|----------------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| json_dumps           | 9.85 ms                                                | 9.72 ms: 1.01x faster                                   |
| json_loads           | 25.2 us                                                | 25.0 us: 1.01x faster                                   |
| tomli_loads          | 2.22 sec                                               | 2.23 sec: 1.00x slower                                  |
| unpickle_pure_python | 218 us                                                 | 220 us: 1.01x slower                                    |
| xml_etree_process    | 58.6 ms                                                | 59.1 ms: 1.01x slower                                   |
| pickle_pure_python   | 309 us                                                 | 313 us: 1.01x slower                                    |
| pickle_list          | 4.62 us                                                | 4.69 us: 1.02x slower                                   |
| pickle_dict          | 31.6 us                                                | 32.2 us: 1.02x slower                                   |
| pickle               | 10.6 us                                                | 10.9 us: 1.02x slower                                   |
| unpickle_list        | 4.95 us                                                | 5.11 us: 1.03x slower                                   |
| unpickle             | 15.0 us                                                | 15.6 us: 1.04x slower                                   |
| Geometric mean       | (ref)                                                  | 1.01x slower                                            |

Benchmark hidden because not significant (3): xml_etree_parse, xml_etree_iterparse, xml_etree_generate

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230908-linux-x86_64-python-3.12-3.12.0rc2+-af83d1e |
|------------------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| python_startup_no_site | 6.90 ms                                                | 6.86 ms: 1.01x faster                                   |
| python_startup         | 9.47 ms                                                | 9.43 ms: 1.00x faster                                   |
| Geometric mean         | (ref)                                                  | 1.01x faster                                            |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230908-linux-x86_64-python-3.12-3.12.0rc2+-af83d1e |
|-----------|:------------------------------------------------------:|:-------------------------------------------------------:|
| mako      | 10.7 ms                                                | 11.0 ms: 1.02x slower                                   |

All benchmarks:
===============

| Benchmark                | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230908-linux-x86_64-python-3.12-3.12.0rc2+-af83d1e |
|--------------------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| gc_traversal             | 3.84 ms                                                | 3.67 ms: 1.05x faster                                   |
| asyncio_tcp              | 526 ms                                                 | 505 ms: 1.04x faster                                    |
| scimark_fft              | 358 ms                                                 | 350 ms: 1.02x faster                                    |
| generators               | 31.1 ms                                                | 30.4 ms: 1.02x faster                                   |
| float                    | 80.7 ms                                                | 79.0 ms: 1.02x faster                                   |
| create_gc_cycles         | 1.52 ms                                                | 1.49 ms: 1.02x faster                                   |
| scimark_sor              | 125 ms                                                 | 122 ms: 1.02x faster                                    |
| spectral_norm            | 106 ms                                                 | 104 ms: 1.02x faster                                    |
| scimark_lu               | 114 ms                                                 | 112 ms: 1.01x faster                                    |
| json_dumps               | 9.85 ms                                                | 9.72 ms: 1.01x faster                                   |
| telco                    | 6.87 ms                                                | 6.80 ms: 1.01x faster                                   |
| hexiom                   | 6.12 ms                                                | 6.06 ms: 1.01x faster                                   |
| deltablue                | 3.52 ms                                                | 3.48 ms: 1.01x faster                                   |
| json_loads               | 25.2 us                                                | 25.0 us: 1.01x faster                                   |
| typing_runtime_protocols | 146 us                                                 | 145 us: 1.01x faster                                    |
| python_startup_no_site   | 6.90 ms                                                | 6.86 ms: 1.01x faster                                   |
| go                       | 136 ms                                                 | 135 ms: 1.01x faster                                    |
| python_startup           | 9.47 ms                                                | 9.43 ms: 1.00x faster                                   |
| bench_thread_pool        | 827 us                                                 | 825 us: 1.00x faster                                    |
| asyncio_tcp_ssl          | 1.79 sec                                               | 1.80 sec: 1.00x slower                                  |
| meteor_contest           | 105 ms                                                 | 105 ms: 1.00x slower                                    |
| async_generators         | 440 ms                                                 | 442 ms: 1.00x slower                                    |
| tomli_loads              | 2.22 sec                                               | 2.23 sec: 1.00x slower                                  |
| pprint_pformat           | 1.50 sec                                               | 1.51 sec: 1.00x slower                                  |
| pprint_safe_repr         | 735 ms                                                 | 739 ms: 1.01x slower                                    |
| logging_silent           | 99.1 ns                                                | 99.7 ns: 1.01x slower                                   |
| comprehensions           | 20.4 us                                                | 20.6 us: 1.01x slower                                   |
| crypto_pyaes             | 77.2 ms                                                | 77.7 ms: 1.01x slower                                   |
| docutils                 | 2.70 sec                                               | 2.72 sec: 1.01x slower                                  |
| unpickle_pure_python     | 218 us                                                 | 220 us: 1.01x slower                                    |
| 2to3                     | 268 ms                                                 | 270 ms: 1.01x slower                                    |
| sqlglot_parse            | 1.32 ms                                                | 1.33 ms: 1.01x slower                                   |
| xml_etree_process        | 58.6 ms                                                | 59.1 ms: 1.01x slower                                   |
| mdp                      | 2.57 sec                                               | 2.59 sec: 1.01x slower                                  |
| richards_super           | 49.0 ms                                                | 49.5 ms: 1.01x slower                                   |
| regex_dna                | 209 ms                                                 | 211 ms: 1.01x slower                                    |
| pickle_pure_python       | 309 us                                                 | 313 us: 1.01x slower                                    |
| scimark_monte_carlo      | 71.0 ms                                                | 71.9 ms: 1.01x slower                                   |
| pycparser                | 1.15 sec                                               | 1.16 sec: 1.01x slower                                  |
| sqlglot_optimize         | 53.3 ms                                                | 54.0 ms: 1.01x slower                                   |
| richards                 | 43.2 ms                                                | 43.8 ms: 1.01x slower                                   |
| deepcopy_memo            | 37.4 us                                                | 37.9 us: 1.01x slower                                   |
| dulwich_log              | 67.9 ms                                                | 68.9 ms: 1.01x slower                                   |
| pickle_list              | 4.62 us                                                | 4.69 us: 1.02x slower                                   |
| logging_format           | 6.90 us                                                | 7.02 us: 1.02x slower                                   |
| pickle_dict              | 31.6 us                                                | 32.2 us: 1.02x slower                                   |
| deepcopy_reduce          | 3.14 us                                                | 3.20 us: 1.02x slower                                   |
| fannkuch                 | 387 ms                                                 | 396 ms: 1.02x slower                                    |
| regex_v8                 | 22.3 ms                                                | 22.9 ms: 1.02x slower                                   |
| mako                     | 10.7 ms                                                | 11.0 ms: 1.02x slower                                   |
| pickle                   | 10.6 us                                                | 10.9 us: 1.02x slower                                   |
| logging_simple           | 6.18 us                                                | 6.33 us: 1.03x slower                                   |
| pyflate                  | 450 ms                                                 | 463 ms: 1.03x slower                                    |
| sqlglot_normalize        | 107 ms                                                 | 110 ms: 1.03x slower                                    |
| unpickle_list            | 4.95 us                                                | 5.11 us: 1.03x slower                                   |
| unpickle                 | 15.0 us                                                | 15.6 us: 1.04x slower                                   |
| regex_effbot             | 3.55 ms                                                | 3.73 ms: 1.05x slower                                   |
| unpack_sequence          | 44.8 ns                                                | 50.0 ns: 1.11x slower                                   |
| pidigits                 | 187 ms                                                 | 212 ms: 1.13x slower                                    |
| dask                     | 365 ms                                                 | 537 ms: 1.47x slower                                    |
| Geometric mean           | (ref)                                                  | 1.01x slower                                            |

Benchmark hidden because not significant (25): sqlalchemy_imperative, async_tree_cpu_io_mixed, coroutines, async_tree_memoization, xml_etree_parse, raytrace, nqueens, async_tree_none, deepcopy, sqlite_synth, nbody, async_tree_io, xml_etree_iterparse, xml_etree_generate, pathlib, tornado_http, bench_mp_pool, mypy2, sqlalchemy_declarative, regex_compile, chaos, sqlglot_transpile, scimark_sparse_mat_mult, coverage, json


# HPT report

- Reliability score: 97.13% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
