
# Results vs. 3.12.0

- fork: python
- ref: v3.12.0b3
- machine: windows-amd64
- commit hash: f992a60
- commit date: 2023-06-19
- overall geometric mean: 1.02x slower \*
- HPT reliability: 99.99%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230619-pythonperf1-amd64-python-v3.12.0b3-3.12.0b3-f992a60 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| 2to3           | 213 ms                                                      | 217 ms: 1.02x slower                                            |
| docutils       | 1.61 sec                                                    | 1.66 sec: 1.03x slower                                          |
| tornado_http   | 87.2 ms                                                     | 90.2 ms: 1.03x slower                                           |
| Geometric mean | (ref)                                                       | 1.03x slower                                                    |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230619-pythonperf1-amd64-python-v3.12.0b3-3.12.0b3-f992a60 |
|-------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| async_tree_none         | 286 ms                                                      | 292 ms: 1.02x slower                                            |
| async_tree_cpu_io_mixed | 477 ms                                                      | 493 ms: 1.03x slower                                            |
| async_tree_io           | 712 ms                                                      | 744 ms: 1.05x slower                                            |
| async_tree_memoization  | 333 ms                                                      | 352 ms: 1.06x slower                                            |
| Geometric mean          | (ref)                                                       | 1.04x slower                                                    |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230619-pythonperf1-amd64-python-v3.12.0b3-3.12.0b3-f992a60 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| nbody          | 68.8 ms                                                     | 67.6 ms: 1.02x faster                                           |
| float          | 54.7 ms                                                     | 54.0 ms: 1.01x faster                                           |
| pidigits       | 150 ms                                                      | 154 ms: 1.02x slower                                            |
| Geometric mean | (ref)                                                       | 1.00x faster                                                    |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230619-pythonperf1-amd64-python-v3.12.0b3-3.12.0b3-f992a60 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| regex_effbot   | 1.58 ms                                                     | 1.61 ms: 1.02x slower                                           |
| regex_dna      | 119 ms                                                      | 122 ms: 1.02x slower                                            |
| regex_v8       | 13.5 ms                                                     | 14.0 ms: 1.04x slower                                           |
| Geometric mean | (ref)                                                       | 1.02x slower                                                    |

Benchmark hidden because not significant (1): regex_compile

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230619-pythonperf1-amd64-python-v3.12.0b3-3.12.0b3-f992a60 |
|----------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| pickle               | 7.38 us                                                     | 6.86 us: 1.08x faster                                           |
| pickle_dict          | 18.9 us                                                     | 18.1 us: 1.05x faster                                           |
| unpickle             | 8.44 us                                                     | 8.28 us: 1.02x faster                                           |
| pickle_list          | 2.88 us                                                     | 2.84 us: 1.02x faster                                           |
| unpickle_pure_python | 134 us                                                      | 132 us: 1.01x faster                                            |
| json_loads           | 13.6 us                                                     | 13.5 us: 1.01x faster                                           |
| json_dumps           | 5.83 ms                                                     | 5.79 ms: 1.01x faster                                           |
| xml_etree_generate   | 55.8 ms                                                     | 56.2 ms: 1.01x slower                                           |
| xml_etree_process    | 37.6 ms                                                     | 38.1 ms: 1.01x slower                                           |
| xml_etree_iterparse  | 63.1 ms                                                     | 64.6 ms: 1.02x slower                                           |
| xml_etree_parse      | 90.5 ms                                                     | 92.7 ms: 1.02x slower                                           |
| unpickle_list        | 2.69 us                                                     | 2.83 us: 1.05x slower                                           |
| Geometric mean       | (ref)                                                       | 1.00x faster                                                    |

Benchmark hidden because not significant (2): pickle_pure_python, tomli_loads

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230619-pythonperf1-amd64-python-v3.12.0b3-3.12.0b3-f992a60 |
|------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| python_startup_no_site | 15.9 ms                                                     | 17.1 ms: 1.07x slower                                           |
| python_startup         | 18.8 ms                                                     | 20.4 ms: 1.08x slower                                           |
| Geometric mean         | (ref)                                                       | 1.08x slower                                                    |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230619-pythonperf1-amd64-python-v3.12.0b3-3.12.0b3-f992a60 |
|-----------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| mako      | 7.05 ms                                                     | 6.88 ms: 1.03x faster                                           |

All benchmarks:
===============

| Benchmark                | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230619-pythonperf1-amd64-python-v3.12.0b3-3.12.0b3-f992a60 |
|--------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| pickle                   | 7.38 us                                                     | 6.86 us: 1.08x faster                                           |
| richards                 | 27.6 ms                                                     | 26.1 ms: 1.06x faster                                           |
| richards_super           | 31.2 ms                                                     | 29.7 ms: 1.05x faster                                           |
| pickle_dict              | 18.9 us                                                     | 18.1 us: 1.05x faster                                           |
| raytrace                 | 192 ms                                                      | 184 ms: 1.04x faster                                            |
| scimark_fft              | 181 ms                                                      | 175 ms: 1.04x faster                                            |
| mako                     | 7.05 ms                                                     | 6.88 ms: 1.03x faster                                           |
| generators               | 22.6 ms                                                     | 22.0 ms: 1.02x faster                                           |
| deltablue                | 2.12 ms                                                     | 2.07 ms: 1.02x faster                                           |
| typing_runtime_protocols | 96.7 us                                                     | 94.6 us: 1.02x faster                                           |
| scimark_sor              | 79.8 ms                                                     | 78.1 ms: 1.02x faster                                           |
| logging_silent           | 60.5 ns                                                     | 59.3 ns: 1.02x faster                                           |
| unpickle                 | 8.44 us                                                     | 8.28 us: 1.02x faster                                           |
| scimark_sparse_mat_mult  | 2.51 ms                                                     | 2.47 ms: 1.02x faster                                           |
| nbody                    | 68.8 ms                                                     | 67.6 ms: 1.02x faster                                           |
| pickle_list              | 2.88 us                                                     | 2.84 us: 1.02x faster                                           |
| scimark_lu               | 57.5 ms                                                     | 56.6 ms: 1.02x faster                                           |
| unpickle_pure_python     | 134 us                                                      | 132 us: 1.01x faster                                            |
| float                    | 54.7 ms                                                     | 54.0 ms: 1.01x faster                                           |
| nqueens                  | 61.7 ms                                                     | 61.1 ms: 1.01x faster                                           |
| json_loads               | 13.6 us                                                     | 13.5 us: 1.01x faster                                           |
| scimark_monte_carlo      | 43.0 ms                                                     | 42.6 ms: 1.01x faster                                           |
| json_dumps               | 5.83 ms                                                     | 5.79 ms: 1.01x faster                                           |
| go                       | 89.0 ms                                                     | 88.3 ms: 1.01x faster                                           |
| coroutines               | 14.1 ms                                                     | 14.0 ms: 1.01x faster                                           |
| fannkuch                 | 244 ms                                                      | 243 ms: 1.00x faster                                            |
| sqlglot_optimize         | 34.0 ms                                                     | 33.9 ms: 1.00x faster                                           |
| sqlglot_normalize        | 183 ms                                                      | 184 ms: 1.01x slower                                            |
| telco                    | 4.08 ms                                                     | 4.11 ms: 1.01x slower                                           |
| pprint_safe_repr         | 508 ms                                                      | 511 ms: 1.01x slower                                            |
| xml_etree_generate       | 55.8 ms                                                     | 56.2 ms: 1.01x slower                                           |
| mdp                      | 1.42 sec                                                    | 1.43 sec: 1.01x slower                                          |
| bench_mp_pool            | 67.2 ms                                                     | 67.9 ms: 1.01x slower                                           |
| spectral_norm            | 63.9 ms                                                     | 64.6 ms: 1.01x slower                                           |
| pyflate                  | 294 ms                                                      | 297 ms: 1.01x slower                                            |
| xml_etree_process        | 37.6 ms                                                     | 38.1 ms: 1.01x slower                                           |
| chaos                    | 42.1 ms                                                     | 42.8 ms: 1.02x slower                                           |
| async_generators         | 230 ms                                                      | 234 ms: 1.02x slower                                            |
| regex_effbot             | 1.58 ms                                                     | 1.61 ms: 1.02x slower                                           |
| regex_dna                | 119 ms                                                      | 122 ms: 1.02x slower                                            |
| 2to3                     | 213 ms                                                      | 217 ms: 1.02x slower                                            |
| async_tree_none          | 286 ms                                                      | 292 ms: 1.02x slower                                            |
| xml_etree_iterparse      | 63.1 ms                                                     | 64.6 ms: 1.02x slower                                           |
| json                     | 2.94 ms                                                     | 3.01 ms: 1.02x slower                                           |
| create_gc_cycles         | 726 us                                                      | 744 us: 1.02x slower                                            |
| meteor_contest           | 72.1 ms                                                     | 73.9 ms: 1.02x slower                                           |
| xml_etree_parse          | 90.5 ms                                                     | 92.7 ms: 1.02x slower                                           |
| pidigits                 | 150 ms                                                      | 154 ms: 1.02x slower                                            |
| crypto_pyaes             | 46.4 ms                                                     | 47.6 ms: 1.03x slower                                           |
| logging_format           | 6.72 us                                                     | 6.91 us: 1.03x slower                                           |
| gc_traversal             | 1.49 ms                                                     | 1.53 ms: 1.03x slower                                           |
| docutils                 | 1.61 sec                                                    | 1.66 sec: 1.03x slower                                          |
| mypy2                    | 209 ms                                                      | 215 ms: 1.03x slower                                            |
| dulwich_log              | 42.7 ms                                                     | 44.1 ms: 1.03x slower                                           |
| async_tree_cpu_io_mixed  | 477 ms                                                      | 493 ms: 1.03x slower                                            |
| tornado_http             | 87.2 ms                                                     | 90.2 ms: 1.03x slower                                           |
| logging_simple           | 6.21 us                                                     | 6.44 us: 1.04x slower                                           |
| pycparser                | 673 ms                                                      | 699 ms: 1.04x slower                                            |
| regex_v8                 | 13.5 ms                                                     | 14.0 ms: 1.04x slower                                           |
| pathlib                  | 79.6 ms                                                     | 82.8 ms: 1.04x slower                                           |
| bench_thread_pool        | 830 us                                                      | 866 us: 1.04x slower                                            |
| async_tree_io            | 712 ms                                                      | 744 ms: 1.05x slower                                            |
| aiohttp                  | 848 us                                                      | 887 us: 1.05x slower                                            |
| unpack_sequence          | 36.9 ns                                                     | 38.8 ns: 1.05x slower                                           |
| unpickle_list            | 2.69 us                                                     | 2.83 us: 1.05x slower                                           |
| async_tree_memoization   | 333 ms                                                      | 352 ms: 1.06x slower                                            |
| asyncio_tcp              | 471 ms                                                      | 498 ms: 1.06x slower                                            |
| sqlite_synth             | 1.75 us                                                     | 1.86 us: 1.06x slower                                           |
| python_startup_no_site   | 15.9 ms                                                     | 17.1 ms: 1.07x slower                                           |
| python_startup           | 18.8 ms                                                     | 20.4 ms: 1.08x slower                                           |
| asyncio_tcp_ssl          | 1.89 sec                                                    | 2.07 sec: 1.10x slower                                          |
| coverage                 | 39.8 ms                                                     | 52.8 ms: 1.33x slower                                           |
| dask                     | 255 ms                                                      | 370 ms: 1.45x slower                                            |
| Geometric mean           | (ref)                                                       | 1.02x slower                                                    |

Benchmark hidden because not significant (11): deepcopy_memo, deepcopy_reduce, pickle_pure_python, sqlglot_transpile, hexiom, comprehensions, pprint_pformat, sqlglot_parse, regex_compile, tomli_loads, deepcopy
Ignored benchmarks (12) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, chameleon, django_template, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum


# HPT report

- Reliability score: 99.99% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
