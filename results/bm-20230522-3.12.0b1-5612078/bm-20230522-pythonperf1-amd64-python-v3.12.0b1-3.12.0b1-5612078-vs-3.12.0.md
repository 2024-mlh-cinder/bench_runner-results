
# Results vs. 3.12.0

- fork: python
- ref: v3.12.0b1
- machine: windows-amd64
- commit hash: 5612078
- commit date: 2023-05-22
- overall geometric mean: 1.04x slower \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.02x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230522-pythonperf1-amd64-python-v3.12.0b1-3.12.0b1-5612078 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| 2to3           | 213 ms                                                      | 218 ms: 1.03x slower                                            |
| docutils       | 1.61 sec                                                    | 1.67 sec: 1.04x slower                                          |
| tornado_http   | 87.2 ms                                                     | 98.2 ms: 1.13x slower                                           |
| Geometric mean | (ref)                                                       | 1.06x slower                                                    |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230522-pythonperf1-amd64-python-v3.12.0b1-3.12.0b1-5612078 |
|-------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| async_tree_cpu_io_mixed | 477 ms                                                      | 494 ms: 1.04x slower                                            |
| async_tree_memoization  | 333 ms                                                      | 351 ms: 1.06x slower                                            |
| async_tree_io           | 712 ms                                                      | 765 ms: 1.07x slower                                            |
| async_tree_none         | 286 ms                                                      | 309 ms: 1.08x slower                                            |
| Geometric mean          | (ref)                                                       | 1.06x slower                                                    |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230522-pythonperf1-amd64-python-v3.12.0b1-3.12.0b1-5612078 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| pidigits       | 150 ms                                                      | 153 ms: 1.02x slower                                            |
| float          | 54.7 ms                                                     | 56.5 ms: 1.03x slower                                           |
| Geometric mean | (ref)                                                       | 1.02x slower                                                    |

Benchmark hidden because not significant (1): nbody

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230522-pythonperf1-amd64-python-v3.12.0b1-3.12.0b1-5612078 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| regex_compile  | 87.2 ms                                                     | 89.3 ms: 1.02x slower                                           |
| regex_effbot   | 1.58 ms                                                     | 1.62 ms: 1.03x slower                                           |
| regex_v8       | 13.5 ms                                                     | 13.9 ms: 1.03x slower                                           |
| regex_dna      | 119 ms                                                      | 126 ms: 1.05x slower                                            |
| Geometric mean | (ref)                                                       | 1.03x slower                                                    |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230522-pythonperf1-amd64-python-v3.12.0b1-3.12.0b1-5612078 |
|----------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| pickle               | 7.38 us                                                     | 7.00 us: 1.05x faster                                           |
| json_dumps           | 5.83 ms                                                     | 5.68 ms: 1.03x faster                                           |
| pickle_list          | 2.88 us                                                     | 2.86 us: 1.01x faster                                           |
| pickle_pure_python   | 195 us                                                      | 196 us: 1.01x slower                                            |
| json_loads           | 13.6 us                                                     | 13.8 us: 1.01x slower                                           |
| pickle_dict          | 18.9 us                                                     | 19.2 us: 1.01x slower                                           |
| xml_etree_generate   | 55.8 ms                                                     | 56.6 ms: 1.01x slower                                           |
| unpickle_pure_python | 134 us                                                      | 137 us: 1.02x slower                                            |
| xml_etree_process    | 37.6 ms                                                     | 38.6 ms: 1.02x slower                                           |
| xml_etree_parse      | 90.5 ms                                                     | 93.8 ms: 1.04x slower                                           |
| xml_etree_iterparse  | 63.1 ms                                                     | 66.2 ms: 1.05x slower                                           |
| unpickle_list        | 2.69 us                                                     | 2.92 us: 1.08x slower                                           |
| Geometric mean       | (ref)                                                       | 1.01x slower                                                    |

Benchmark hidden because not significant (2): unpickle, tomli_loads

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230522-pythonperf1-amd64-python-v3.12.0b1-3.12.0b1-5612078 |
|------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| python_startup         | 18.8 ms                                                     | 20.8 ms: 1.11x slower                                           |
| python_startup_no_site | 15.9 ms                                                     | 17.8 ms: 1.12x slower                                           |
| Geometric mean         | (ref)                                                       | 1.11x slower                                                    |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230522-pythonperf1-amd64-python-v3.12.0b1-3.12.0b1-5612078 |
|-----------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| mako      | 7.05 ms                                                     | 7.24 ms: 1.03x slower                                           |

All benchmarks:
===============

| Benchmark                | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230522-pythonperf1-amd64-python-v3.12.0b1-3.12.0b1-5612078 |
|--------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| richards                 | 27.6 ms                                                     | 25.5 ms: 1.08x faster                                           |
| richards_super           | 31.2 ms                                                     | 29.1 ms: 1.07x faster                                           |
| pickle                   | 7.38 us                                                     | 7.00 us: 1.05x faster                                           |
| json_dumps               | 5.83 ms                                                     | 5.68 ms: 1.03x faster                                           |
| typing_runtime_protocols | 96.7 us                                                     | 94.7 us: 1.02x faster                                           |
| mdp                      | 1.42 sec                                                    | 1.40 sec: 1.02x faster                                          |
| scimark_fft              | 181 ms                                                      | 178 ms: 1.01x faster                                            |
| pickle_list              | 2.88 us                                                     | 2.86 us: 1.01x faster                                           |
| go                       | 89.0 ms                                                     | 88.2 ms: 1.01x faster                                           |
| logging_silent           | 60.5 ns                                                     | 60.1 ns: 1.01x faster                                           |
| scimark_sparse_mat_mult  | 2.51 ms                                                     | 2.52 ms: 1.00x slower                                           |
| pickle_pure_python       | 195 us                                                      | 196 us: 1.01x slower                                            |
| fannkuch                 | 244 ms                                                      | 246 ms: 1.01x slower                                            |
| deepcopy_reduce          | 2.08 us                                                     | 2.10 us: 1.01x slower                                           |
| scimark_sor              | 79.8 ms                                                     | 80.6 ms: 1.01x slower                                           |
| json_loads               | 13.6 us                                                     | 13.8 us: 1.01x slower                                           |
| json                     | 2.94 ms                                                     | 2.98 ms: 1.01x slower                                           |
| deepcopy                 | 233 us                                                      | 236 us: 1.01x slower                                            |
| deepcopy_memo            | 23.4 us                                                     | 23.7 us: 1.01x slower                                           |
| pickle_dict              | 18.9 us                                                     | 19.2 us: 1.01x slower                                           |
| xml_etree_generate       | 55.8 ms                                                     | 56.6 ms: 1.01x slower                                           |
| pyflate                  | 294 ms                                                      | 298 ms: 1.02x slower                                            |
| generators               | 22.6 ms                                                     | 23.0 ms: 1.02x slower                                           |
| pprint_safe_repr         | 508 ms                                                      | 517 ms: 1.02x slower                                            |
| pprint_pformat           | 1.04 sec                                                    | 1.06 sec: 1.02x slower                                          |
| sqlglot_normalize        | 183 ms                                                      | 187 ms: 1.02x slower                                            |
| crypto_pyaes             | 46.4 ms                                                     | 47.4 ms: 1.02x slower                                           |
| sqlite_synth             | 1.75 us                                                     | 1.78 us: 1.02x slower                                           |
| pidigits                 | 150 ms                                                      | 153 ms: 1.02x slower                                            |
| unpickle_pure_python     | 134 us                                                      | 137 us: 1.02x slower                                            |
| coroutines               | 14.1 ms                                                     | 14.4 ms: 1.02x slower                                           |
| hexiom                   | 4.00 ms                                                     | 4.09 ms: 1.02x slower                                           |
| regex_compile            | 87.2 ms                                                     | 89.3 ms: 1.02x slower                                           |
| xml_etree_process        | 37.6 ms                                                     | 38.6 ms: 1.02x slower                                           |
| regex_effbot             | 1.58 ms                                                     | 1.62 ms: 1.03x slower                                           |
| mako                     | 7.05 ms                                                     | 7.24 ms: 1.03x slower                                           |
| 2to3                     | 213 ms                                                      | 218 ms: 1.03x slower                                            |
| sqlglot_optimize         | 34.0 ms                                                     | 35.0 ms: 1.03x slower                                           |
| gc_traversal             | 1.49 ms                                                     | 1.53 ms: 1.03x slower                                           |
| comprehensions           | 14.0 us                                                     | 14.4 us: 1.03x slower                                           |
| async_generators         | 230 ms                                                      | 237 ms: 1.03x slower                                            |
| regex_v8                 | 13.5 ms                                                     | 13.9 ms: 1.03x slower                                           |
| float                    | 54.7 ms                                                     | 56.5 ms: 1.03x slower                                           |
| async_tree_cpu_io_mixed  | 477 ms                                                      | 494 ms: 1.04x slower                                            |
| xml_etree_parse          | 90.5 ms                                                     | 93.8 ms: 1.04x slower                                           |
| telco                    | 4.08 ms                                                     | 4.23 ms: 1.04x slower                                           |
| deltablue                | 2.12 ms                                                     | 2.20 ms: 1.04x slower                                           |
| spectral_norm            | 63.9 ms                                                     | 66.3 ms: 1.04x slower                                           |
| pycparser                | 673 ms                                                      | 700 ms: 1.04x slower                                            |
| bench_mp_pool            | 67.2 ms                                                     | 70.0 ms: 1.04x slower                                           |
| docutils                 | 1.61 sec                                                    | 1.67 sec: 1.04x slower                                          |
| meteor_contest           | 72.1 ms                                                     | 75.2 ms: 1.04x slower                                           |
| scimark_lu               | 57.5 ms                                                     | 60.0 ms: 1.04x slower                                           |
| xml_etree_iterparse      | 63.1 ms                                                     | 66.2 ms: 1.05x slower                                           |
| unpack_sequence          | 36.9 ns                                                     | 38.7 ns: 1.05x slower                                           |
| chaos                    | 42.1 ms                                                     | 44.3 ms: 1.05x slower                                           |
| regex_dna                | 119 ms                                                      | 126 ms: 1.05x slower                                            |
| create_gc_cycles         | 726 us                                                      | 766 us: 1.06x slower                                            |
| async_tree_memoization   | 333 ms                                                      | 351 ms: 1.06x slower                                            |
| mypy2                    | 209 ms                                                      | 221 ms: 1.06x slower                                            |
| dulwich_log              | 42.7 ms                                                     | 45.3 ms: 1.06x slower                                           |
| pathlib                  | 79.6 ms                                                     | 85.4 ms: 1.07x slower                                           |
| async_tree_io            | 712 ms                                                      | 765 ms: 1.07x slower                                            |
| bench_thread_pool        | 830 us                                                      | 895 us: 1.08x slower                                            |
| async_tree_none          | 286 ms                                                      | 309 ms: 1.08x slower                                            |
| unpickle_list            | 2.69 us                                                     | 2.92 us: 1.08x slower                                           |
| logging_format           | 6.72 us                                                     | 7.28 us: 1.08x slower                                           |
| logging_simple           | 6.21 us                                                     | 6.77 us: 1.09x slower                                           |
| aiohttp                  | 848 us                                                      | 928 us: 1.09x slower                                            |
| python_startup           | 18.8 ms                                                     | 20.8 ms: 1.11x slower                                           |
| python_startup_no_site   | 15.9 ms                                                     | 17.8 ms: 1.12x slower                                           |
| tornado_http             | 87.2 ms                                                     | 98.2 ms: 1.13x slower                                           |
| asyncio_tcp_ssl          | 1.89 sec                                                    | 2.39 sec: 1.26x slower                                          |
| coverage                 | 39.8 ms                                                     | 50.9 ms: 1.28x slower                                           |
| asyncio_tcp              | 471 ms                                                      | 686 ms: 1.46x slower                                            |
| dask                     | 255 ms                                                      | 382 ms: 1.50x slower                                            |
| Geometric mean           | (ref)                                                       | 1.04x slower                                                    |

Benchmark hidden because not significant (8): sqlglot_parse, scimark_monte_carlo, nqueens, raytrace, sqlglot_transpile, nbody, unpickle, tomli_loads
Ignored benchmarks (12) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, chameleon, django_template, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.02x
- 95% likely to have a slowdown of 1.02x
- 99% likely to have a slowdown of 1.02x
