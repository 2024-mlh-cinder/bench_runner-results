
# Results vs. 3.12.0

- fork: python
- ref: v3.12.0b2
- machine: windows-amd64
- commit hash: e6c0efa
- commit date: 2023-06-06
- overall geometric mean: 1.02x slower \*
- HPT reliability: 99.94%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230606-pythonperf1-amd64-python-v3.12.0b2-3.12.0b2-e6c0efa |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| 2to3           | 213 ms                                                      | 216 ms: 1.01x slower                                            |
| docutils       | 1.61 sec                                                    | 1.67 sec: 1.04x slower                                          |
| tornado_http   | 87.2 ms                                                     | 88.5 ms: 1.02x slower                                           |
| Geometric mean | (ref)                                                       | 1.02x slower                                                    |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230606-pythonperf1-amd64-python-v3.12.0b2-3.12.0b2-e6c0efa |
|-------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| async_tree_cpu_io_mixed | 477 ms                                                      | 493 ms: 1.03x slower                                            |
| async_tree_none         | 286 ms                                                      | 298 ms: 1.04x slower                                            |
| async_tree_memoization  | 333 ms                                                      | 347 ms: 1.04x slower                                            |
| async_tree_io           | 712 ms                                                      | 744 ms: 1.05x slower                                            |
| Geometric mean          | (ref)                                                       | 1.04x slower                                                    |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230606-pythonperf1-amd64-python-v3.12.0b2-3.12.0b2-e6c0efa |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| float          | 54.7 ms                                                     | 55.2 ms: 1.01x slower                                           |
| pidigits       | 150 ms                                                      | 153 ms: 1.02x slower                                            |
| Geometric mean | (ref)                                                       | 1.01x slower                                                    |

Benchmark hidden because not significant (1): nbody

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230606-pythonperf1-amd64-python-v3.12.0b2-3.12.0b2-e6c0efa |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| regex_compile  | 87.2 ms                                                     | 87.9 ms: 1.01x slower                                           |
| regex_effbot   | 1.58 ms                                                     | 1.63 ms: 1.03x slower                                           |
| regex_v8       | 13.5 ms                                                     | 13.9 ms: 1.03x slower                                           |
| regex_dna      | 119 ms                                                      | 125 ms: 1.04x slower                                            |
| Geometric mean | (ref)                                                       | 1.03x slower                                                    |

Benchmarks with tag 'serialize':
================================

| Benchmark           | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230606-pythonperf1-amd64-python-v3.12.0b2-3.12.0b2-e6c0efa |
|---------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| pickle_dict         | 18.9 us                                                     | 18.2 us: 1.04x faster                                           |
| json_dumps          | 5.83 ms                                                     | 5.59 ms: 1.04x faster                                           |
| pickle              | 7.38 us                                                     | 7.11 us: 1.04x faster                                           |
| pickle_list         | 2.88 us                                                     | 2.85 us: 1.01x faster                                           |
| json_loads          | 13.6 us                                                     | 13.7 us: 1.01x slower                                           |
| pickle_pure_python  | 195 us                                                      | 197 us: 1.01x slower                                            |
| xml_etree_parse     | 90.5 ms                                                     | 91.6 ms: 1.01x slower                                           |
| xml_etree_process   | 37.6 ms                                                     | 38.3 ms: 1.02x slower                                           |
| xml_etree_generate  | 55.8 ms                                                     | 57.0 ms: 1.02x slower                                           |
| xml_etree_iterparse | 63.1 ms                                                     | 65.0 ms: 1.03x slower                                           |
| unpickle_list       | 2.69 us                                                     | 2.90 us: 1.07x slower                                           |
| Geometric mean      | (ref)                                                       | 1.00x slower                                                    |

Benchmark hidden because not significant (3): tomli_loads, unpickle_pure_python, unpickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230606-pythonperf1-amd64-python-v3.12.0b2-3.12.0b2-e6c0efa |
|------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| python_startup         | 18.8 ms                                                     | 20.2 ms: 1.07x slower                                           |
| python_startup_no_site | 15.9 ms                                                     | 17.4 ms: 1.09x slower                                           |
| Geometric mean         | (ref)                                                       | 1.08x slower                                                    |

Benchmarks with tag 'template':
===============================

Benchmark hidden because not significant (1): mako

All benchmarks:
===============

| Benchmark                | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230606-pythonperf1-amd64-python-v3.12.0b2-3.12.0b2-e6c0efa |
|--------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| richards                 | 27.6 ms                                                     | 25.7 ms: 1.07x faster                                           |
| richards_super           | 31.2 ms                                                     | 29.2 ms: 1.07x faster                                           |
| pickle_dict              | 18.9 us                                                     | 18.2 us: 1.04x faster                                           |
| json_dumps               | 5.83 ms                                                     | 5.59 ms: 1.04x faster                                           |
| scimark_fft              | 181 ms                                                      | 174 ms: 1.04x faster                                            |
| pickle                   | 7.38 us                                                     | 7.11 us: 1.04x faster                                           |
| scimark_sor              | 79.8 ms                                                     | 77.3 ms: 1.03x faster                                           |
| mdp                      | 1.42 sec                                                    | 1.38 sec: 1.03x faster                                          |
| raytrace                 | 192 ms                                                      | 187 ms: 1.03x faster                                            |
| deltablue                | 2.12 ms                                                     | 2.08 ms: 1.02x faster                                           |
| logging_silent           | 60.5 ns                                                     | 59.4 ns: 1.02x faster                                           |
| typing_runtime_protocols | 96.7 us                                                     | 95.0 us: 1.02x faster                                           |
| fannkuch                 | 244 ms                                                      | 240 ms: 1.02x faster                                            |
| coroutines               | 14.1 ms                                                     | 13.9 ms: 1.02x faster                                           |
| go                       | 89.0 ms                                                     | 87.8 ms: 1.01x faster                                           |
| pickle_list              | 2.88 us                                                     | 2.85 us: 1.01x faster                                           |
| scimark_lu               | 57.5 ms                                                     | 56.8 ms: 1.01x faster                                           |
| nqueens                  | 61.7 ms                                                     | 61.1 ms: 1.01x faster                                           |
| scimark_monte_carlo      | 43.0 ms                                                     | 42.6 ms: 1.01x faster                                           |
| sqlglot_transpile        | 1.02 ms                                                     | 1.01 ms: 1.01x faster                                           |
| sqlglot_optimize         | 34.0 ms                                                     | 33.8 ms: 1.01x faster                                           |
| sqlglot_normalize        | 183 ms                                                      | 183 ms: 1.00x faster                                            |
| pprint_safe_repr         | 508 ms                                                      | 510 ms: 1.00x slower                                            |
| scimark_sparse_mat_mult  | 2.51 ms                                                     | 2.52 ms: 1.01x slower                                           |
| deepcopy_reduce          | 2.08 us                                                     | 2.10 us: 1.01x slower                                           |
| json_loads               | 13.6 us                                                     | 13.7 us: 1.01x slower                                           |
| regex_compile            | 87.2 ms                                                     | 87.9 ms: 1.01x slower                                           |
| pyflate                  | 294 ms                                                      | 296 ms: 1.01x slower                                            |
| float                    | 54.7 ms                                                     | 55.2 ms: 1.01x slower                                           |
| pickle_pure_python       | 195 us                                                      | 197 us: 1.01x slower                                            |
| pycparser                | 673 ms                                                      | 680 ms: 1.01x slower                                            |
| bench_mp_pool            | 67.2 ms                                                     | 68.0 ms: 1.01x slower                                           |
| xml_etree_parse          | 90.5 ms                                                     | 91.6 ms: 1.01x slower                                           |
| 2to3                     | 213 ms                                                      | 216 ms: 1.01x slower                                            |
| async_generators         | 230 ms                                                      | 233 ms: 1.01x slower                                            |
| telco                    | 4.08 ms                                                     | 4.15 ms: 1.02x slower                                           |
| tornado_http             | 87.2 ms                                                     | 88.5 ms: 1.02x slower                                           |
| crypto_pyaes             | 46.4 ms                                                     | 47.2 ms: 1.02x slower                                           |
| json                     | 2.94 ms                                                     | 2.99 ms: 1.02x slower                                           |
| deepcopy_memo            | 23.4 us                                                     | 23.8 us: 1.02x slower                                           |
| chaos                    | 42.1 ms                                                     | 42.8 ms: 1.02x slower                                           |
| xml_etree_process        | 37.6 ms                                                     | 38.3 ms: 1.02x slower                                           |
| xml_etree_generate       | 55.8 ms                                                     | 57.0 ms: 1.02x slower                                           |
| pidigits                 | 150 ms                                                      | 153 ms: 1.02x slower                                            |
| sqlite_synth             | 1.75 us                                                     | 1.79 us: 1.02x slower                                           |
| meteor_contest           | 72.1 ms                                                     | 73.9 ms: 1.02x slower                                           |
| create_gc_cycles         | 726 us                                                      | 744 us: 1.02x slower                                            |
| gc_traversal             | 1.49 ms                                                     | 1.53 ms: 1.03x slower                                           |
| comprehensions           | 14.0 us                                                     | 14.4 us: 1.03x slower                                           |
| regex_effbot             | 1.58 ms                                                     | 1.63 ms: 1.03x slower                                           |
| xml_etree_iterparse      | 63.1 ms                                                     | 65.0 ms: 1.03x slower                                           |
| regex_v8                 | 13.5 ms                                                     | 13.9 ms: 1.03x slower                                           |
| async_tree_cpu_io_mixed  | 477 ms                                                      | 493 ms: 1.03x slower                                            |
| spectral_norm            | 63.9 ms                                                     | 66.0 ms: 1.03x slower                                           |
| dulwich_log              | 42.7 ms                                                     | 44.2 ms: 1.04x slower                                           |
| docutils                 | 1.61 sec                                                    | 1.67 sec: 1.04x slower                                          |
| aiohttp                  | 848 us                                                      | 879 us: 1.04x slower                                            |
| mypy2                    | 209 ms                                                      | 217 ms: 1.04x slower                                            |
| deepcopy                 | 233 us                                                      | 241 us: 1.04x slower                                            |
| async_tree_none          | 286 ms                                                      | 298 ms: 1.04x slower                                            |
| regex_dna                | 119 ms                                                      | 125 ms: 1.04x slower                                            |
| async_tree_memoization   | 333 ms                                                      | 347 ms: 1.04x slower                                            |
| logging_format           | 6.72 us                                                     | 7.01 us: 1.04x slower                                           |
| bench_thread_pool        | 830 us                                                      | 867 us: 1.04x slower                                            |
| async_tree_io            | 712 ms                                                      | 744 ms: 1.05x slower                                            |
| pathlib                  | 79.6 ms                                                     | 83.2 ms: 1.05x slower                                           |
| logging_simple           | 6.21 us                                                     | 6.54 us: 1.05x slower                                           |
| unpack_sequence          | 36.9 ns                                                     | 39.1 ns: 1.06x slower                                           |
| python_startup           | 18.8 ms                                                     | 20.2 ms: 1.07x slower                                           |
| unpickle_list            | 2.69 us                                                     | 2.90 us: 1.07x slower                                           |
| python_startup_no_site   | 15.9 ms                                                     | 17.4 ms: 1.09x slower                                           |
| asyncio_tcp_ssl          | 1.89 sec                                                    | 2.09 sec: 1.11x slower                                          |
| coverage                 | 39.8 ms                                                     | 52.5 ms: 1.32x slower                                           |
| dask                     | 255 ms                                                      | 373 ms: 1.47x slower                                            |
| Geometric mean           | (ref)                                                       | 1.02x slower                                                    |

Benchmark hidden because not significant (10): generators, nbody, tomli_loads, sqlglot_parse, pprint_pformat, mako, hexiom, unpickle_pure_python, unpickle, asyncio_tcp
Ignored benchmarks (12) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, chameleon, django_template, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum


# HPT report

- Reliability score: 99.94% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
