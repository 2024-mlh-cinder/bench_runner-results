
# Results vs. 3.10.4

- fork: python
- ref: v3.12.0b1
- machine: windows-amd64
- commit hash: 5612078
- commit date: 2023-05-22
- overall geometric mean: 1.15x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.06x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230522-pythonperf1-amd64-python-v3.12.0b1-3.12.0b1-5612078 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| 2to3           | 239 ms                                                      | 218 ms: 1.09x faster                                            |
| docutils       | 1.88 sec                                                    | 1.67 sec: 1.12x faster                                          |
| tornado_http   | 106 ms                                                      | 98.2 ms: 1.08x faster                                           |
| Geometric mean | (ref)                                                       | 1.10x faster                                                    |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230522-pythonperf1-amd64-python-v3.12.0b1-3.12.0b1-5612078 |
|-------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| async_tree_memoization  | 505 ms                                                      | 351 ms: 1.44x faster                                            |
| async_tree_io           | 1.07 sec                                                    | 765 ms: 1.40x faster                                            |
| async_tree_none         | 424 ms                                                      | 309 ms: 1.37x faster                                            |
| async_tree_cpu_io_mixed | 617 ms                                                      | 494 ms: 1.25x faster                                            |
| Geometric mean          | (ref)                                                       | 1.36x faster                                                    |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230522-pythonperf1-amd64-python-v3.12.0b1-3.12.0b1-5612078 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| float          | 61.7 ms                                                     | 56.5 ms: 1.09x faster                                           |
| nbody          | 71.0 ms                                                     | 69.0 ms: 1.03x faster                                           |
| pidigits       | 146 ms                                                      | 153 ms: 1.05x slower                                            |
| Geometric mean | (ref)                                                       | 1.02x faster                                                    |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230522-pythonperf1-amd64-python-v3.12.0b1-3.12.0b1-5612078 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| regex_compile  | 102 ms                                                      | 89.3 ms: 1.15x faster                                           |
| regex_v8       | 15.0 ms                                                     | 13.9 ms: 1.08x faster                                           |
| regex_dna      | 129 ms                                                      | 126 ms: 1.03x faster                                            |
| regex_effbot   | 1.56 ms                                                     | 1.62 ms: 1.04x slower                                           |
| Geometric mean | (ref)                                                       | 1.05x faster                                                    |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230522-pythonperf1-amd64-python-v3.12.0b1-3.12.0b1-5612078 |
|----------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| json_dumps           | 8.77 ms                                                     | 5.68 ms: 1.54x faster                                           |
| pickle_pure_python   | 259 us                                                      | 196 us: 1.32x faster                                            |
| unpickle_pure_python | 177 us                                                      | 137 us: 1.29x faster                                            |
| tomli_loads          | 1.65 sec                                                    | 1.39 sec: 1.19x faster                                          |
| xml_etree_process    | 43.1 ms                                                     | 38.6 ms: 1.12x faster                                           |
| unpickle             | 9.11 us                                                     | 8.47 us: 1.08x faster                                           |
| xml_etree_parse      | 96.8 ms                                                     | 93.8 ms: 1.03x faster                                           |
| json_loads           | 14.2 us                                                     | 13.8 us: 1.03x faster                                           |
| pickle               | 6.87 us                                                     | 7.00 us: 1.02x slower                                           |
| xml_etree_iterparse  | 64.5 ms                                                     | 66.2 ms: 1.03x slower                                           |
| xml_etree_generate   | 54.5 ms                                                     | 56.6 ms: 1.04x slower                                           |
| pickle_list          | 2.69 us                                                     | 2.86 us: 1.06x slower                                           |
| unpickle_list        | 2.68 us                                                     | 2.92 us: 1.09x slower                                           |
| pickle_dict          | 17.1 us                                                     | 19.2 us: 1.12x slower                                           |
| Geometric mean       | (ref)                                                       | 1.08x faster                                                    |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230522-pythonperf1-amd64-python-v3.12.0b1-3.12.0b1-5612078 |
|------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| python_startup         | 19.7 ms                                                     | 20.8 ms: 1.06x slower                                           |
| python_startup_no_site | 15.3 ms                                                     | 17.8 ms: 1.16x slower                                           |
| Geometric mean         | (ref)                                                       | 1.11x slower                                                    |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230522-pythonperf1-amd64-python-v3.12.0b1-3.12.0b1-5612078 |
|-----------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| mako      | 8.98 ms                                                     | 7.24 ms: 1.24x faster                                           |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230522-pythonperf1-amd64-python-v3.12.0b1-3.12.0b1-5612078 |
|--------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| typing_runtime_protocols | 337 us                                                      | 94.7 us: 3.56x faster                                           |
| deltablue                | 4.12 ms                                                     | 2.20 ms: 1.87x faster                                           |
| richards_super           | 50.3 ms                                                     | 29.1 ms: 1.73x faster                                           |
| richards                 | 40.6 ms                                                     | 25.5 ms: 1.59x faster                                           |
| mypy2                    | 347 ms                                                      | 221 ms: 1.57x faster                                            |
| logging_silent           | 93.4 ns                                                     | 60.1 ns: 1.55x faster                                           |
| json_dumps               | 8.77 ms                                                     | 5.68 ms: 1.54x faster                                           |
| go                       | 135 ms                                                      | 88.2 ms: 1.53x faster                                           |
| sqlglot_parse            | 1.20 ms                                                     | 800 us: 1.50x faster                                            |
| async_tree_memoization   | 505 ms                                                      | 351 ms: 1.44x faster                                            |
| sqlglot_transpile        | 1.45 ms                                                     | 1.02 ms: 1.42x faster                                           |
| scimark_lu               | 84.0 ms                                                     | 60.0 ms: 1.40x faster                                           |
| async_tree_io            | 1.07 sec                                                    | 765 ms: 1.40x faster                                            |
| raytrace                 | 266 ms                                                      | 192 ms: 1.38x faster                                            |
| generators               | 31.8 ms                                                     | 23.0 ms: 1.38x faster                                           |
| async_tree_none          | 424 ms                                                      | 309 ms: 1.37x faster                                            |
| hexiom                   | 5.59 ms                                                     | 4.09 ms: 1.37x faster                                           |
| scimark_monte_carlo      | 58.0 ms                                                     | 42.9 ms: 1.35x faster                                           |
| pyflate                  | 402 ms                                                      | 298 ms: 1.35x faster                                            |
| chaos                    | 59.5 ms                                                     | 44.3 ms: 1.34x faster                                           |
| crypto_pyaes             | 63.1 ms                                                     | 47.4 ms: 1.33x faster                                           |
| pickle_pure_python       | 259 us                                                      | 196 us: 1.32x faster                                            |
| scimark_sor              | 105 ms                                                      | 80.6 ms: 1.31x faster                                           |
| pycparser                | 905 ms                                                      | 700 ms: 1.29x faster                                            |
| unpickle_pure_python     | 177 us                                                      | 137 us: 1.29x faster                                            |
| async_tree_cpu_io_mixed  | 617 ms                                                      | 494 ms: 1.25x faster                                            |
| mako                     | 8.98 ms                                                     | 7.24 ms: 1.24x faster                                           |
| mdp                      | 1.71 sec                                                    | 1.40 sec: 1.23x faster                                          |
| deepcopy_memo            | 29.0 us                                                     | 23.7 us: 1.22x faster                                           |
| spectral_norm            | 78.9 ms                                                     | 66.3 ms: 1.19x faster                                           |
| tomli_loads              | 1.65 sec                                                    | 1.39 sec: 1.19x faster                                          |
| pprint_pformat           | 1.22 sec                                                    | 1.06 sec: 1.16x faster                                          |
| comprehensions           | 16.6 us                                                     | 14.4 us: 1.15x faster                                           |
| pprint_safe_repr         | 594 ms                                                      | 517 ms: 1.15x faster                                            |
| regex_compile            | 102 ms                                                      | 89.3 ms: 1.15x faster                                           |
| sqlglot_optimize         | 39.4 ms                                                     | 35.0 ms: 1.13x faster                                           |
| docutils                 | 1.88 sec                                                    | 1.67 sec: 1.12x faster                                          |
| xml_etree_process        | 43.1 ms                                                     | 38.6 ms: 1.12x faster                                           |
| nqueens                  | 68.3 ms                                                     | 61.6 ms: 1.11x faster                                           |
| sqlglot_normalize        | 207 ms                                                      | 187 ms: 1.10x faster                                            |
| deepcopy                 | 259 us                                                      | 236 us: 1.10x faster                                            |
| float                    | 61.7 ms                                                     | 56.5 ms: 1.09x faster                                           |
| 2to3                     | 239 ms                                                      | 218 ms: 1.09x faster                                            |
| regex_v8                 | 15.0 ms                                                     | 13.9 ms: 1.08x faster                                           |
| tornado_http             | 106 ms                                                      | 98.2 ms: 1.08x faster                                           |
| unpickle                 | 9.11 us                                                     | 8.47 us: 1.08x faster                                           |
| dulwich_log              | 48.6 ms                                                     | 45.3 ms: 1.07x faster                                           |
| coroutines               | 15.5 ms                                                     | 14.4 ms: 1.07x faster                                           |
| sqlite_synth             | 1.90 us                                                     | 1.78 us: 1.06x faster                                           |
| scimark_sparse_mat_mult  | 2.67 ms                                                     | 2.52 ms: 1.06x faster                                           |
| deepcopy_reduce          | 2.22 us                                                     | 2.10 us: 1.06x faster                                           |
| scimark_fft              | 187 ms                                                      | 178 ms: 1.05x faster                                            |
| fannkuch                 | 258 ms                                                      | 246 ms: 1.05x faster                                            |
| asyncio_tcp              | 717 ms                                                      | 686 ms: 1.05x faster                                            |
| create_gc_cycles         | 800 us                                                      | 766 us: 1.04x faster                                            |
| json                     | 3.10 ms                                                     | 2.98 ms: 1.04x faster                                           |
| aiohttp                  | 961 us                                                      | 928 us: 1.04x faster                                            |
| unpack_sequence          | 40.0 ns                                                     | 38.7 ns: 1.03x faster                                           |
| xml_etree_parse          | 96.8 ms                                                     | 93.8 ms: 1.03x faster                                           |
| json_loads               | 14.2 us                                                     | 13.8 us: 1.03x faster                                           |
| nbody                    | 71.0 ms                                                     | 69.0 ms: 1.03x faster                                           |
| regex_dna                | 129 ms                                                      | 126 ms: 1.03x faster                                            |
| pickle                   | 6.87 us                                                     | 7.00 us: 1.02x slower                                           |
| meteor_contest           | 73.8 ms                                                     | 75.2 ms: 1.02x slower                                           |
| xml_etree_iterparse      | 64.5 ms                                                     | 66.2 ms: 1.03x slower                                           |
| xml_etree_generate       | 54.5 ms                                                     | 56.6 ms: 1.04x slower                                           |
| regex_effbot             | 1.56 ms                                                     | 1.62 ms: 1.04x slower                                           |
| pidigits                 | 146 ms                                                      | 153 ms: 1.05x slower                                            |
| python_startup           | 19.7 ms                                                     | 20.8 ms: 1.06x slower                                           |
| pickle_list              | 2.69 us                                                     | 2.86 us: 1.06x slower                                           |
| logging_simple           | 6.28 us                                                     | 6.77 us: 1.08x slower                                           |
| logging_format           | 6.73 us                                                     | 7.28 us: 1.08x slower                                           |
| async_generators         | 219 ms                                                      | 237 ms: 1.08x slower                                            |
| unpickle_list            | 2.68 us                                                     | 2.92 us: 1.09x slower                                           |
| gc_traversal             | 1.40 ms                                                     | 1.53 ms: 1.10x slower                                           |
| telco                    | 3.82 ms                                                     | 4.23 ms: 1.11x slower                                           |
| pickle_dict              | 17.1 us                                                     | 19.2 us: 1.12x slower                                           |
| asyncio_tcp_ssl          | 2.09 sec                                                    | 2.39 sec: 1.14x slower                                          |
| python_startup_no_site   | 15.3 ms                                                     | 17.8 ms: 1.16x slower                                           |
| bench_mp_pool            | 59.9 ms                                                     | 70.0 ms: 1.17x slower                                           |
| pathlib                  | 72.8 ms                                                     | 85.4 ms: 1.17x slower                                           |
| dask                     | 305 ms                                                      | 382 ms: 1.26x slower                                            |
| coverage                 | 38.4 ms                                                     | 50.9 ms: 1.33x slower                                           |
| Geometric mean           | (ref)                                                       | 1.15x faster                                                    |

Benchmark hidden because not significant (1): bench_thread_pool
Ignored benchmarks (14) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120.json: chameleon, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.09x
- 95% likely to have a speedup of 1.08x
- 99% likely to have a speedup of 1.06x
