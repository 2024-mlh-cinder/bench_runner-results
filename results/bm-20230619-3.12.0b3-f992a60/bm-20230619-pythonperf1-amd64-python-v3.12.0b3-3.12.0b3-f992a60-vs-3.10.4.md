
# Results vs. 3.10.4

- fork: python
- ref: v3.12.0b3
- machine: windows-amd64
- commit hash: f992a60
- commit date: 2023-06-19
- overall geometric mean: 1.17x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.10x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230619-pythonperf1-amd64-python-v3.12.0b3-3.12.0b3-f992a60 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| 2to3           | 239 ms                                                      | 217 ms: 1.10x faster                                            |
| docutils       | 1.88 sec                                                    | 1.66 sec: 1.13x faster                                          |
| tornado_http   | 106 ms                                                      | 90.2 ms: 1.17x faster                                           |
| Geometric mean | (ref)                                                       | 1.14x faster                                                    |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230619-pythonperf1-amd64-python-v3.12.0b3-3.12.0b3-f992a60 |
|-------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| async_tree_none         | 424 ms                                                      | 292 ms: 1.45x faster                                            |
| async_tree_io           | 1.07 sec                                                    | 744 ms: 1.44x faster                                            |
| async_tree_memoization  | 505 ms                                                      | 352 ms: 1.44x faster                                            |
| async_tree_cpu_io_mixed | 617 ms                                                      | 493 ms: 1.25x faster                                            |
| Geometric mean          | (ref)                                                       | 1.39x faster                                                    |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230619-pythonperf1-amd64-python-v3.12.0b3-3.12.0b3-f992a60 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| float          | 61.7 ms                                                     | 54.0 ms: 1.14x faster                                           |
| nbody          | 71.0 ms                                                     | 67.6 ms: 1.05x faster                                           |
| pidigits       | 146 ms                                                      | 154 ms: 1.05x slower                                            |
| Geometric mean | (ref)                                                       | 1.05x faster                                                    |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230619-pythonperf1-amd64-python-v3.12.0b3-3.12.0b3-f992a60 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| regex_compile  | 102 ms                                                      | 87.5 ms: 1.17x faster                                           |
| regex_v8       | 15.0 ms                                                     | 14.0 ms: 1.07x faster                                           |
| regex_dna      | 129 ms                                                      | 122 ms: 1.06x faster                                            |
| regex_effbot   | 1.56 ms                                                     | 1.61 ms: 1.03x slower                                           |
| Geometric mean | (ref)                                                       | 1.07x faster                                                    |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230619-pythonperf1-amd64-python-v3.12.0b3-3.12.0b3-f992a60 |
|----------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| json_dumps           | 8.77 ms                                                     | 5.79 ms: 1.52x faster                                           |
| unpickle_pure_python | 177 us                                                      | 132 us: 1.34x faster                                            |
| pickle_pure_python   | 259 us                                                      | 194 us: 1.34x faster                                            |
| tomli_loads          | 1.65 sec                                                    | 1.38 sec: 1.19x faster                                          |
| xml_etree_process    | 43.1 ms                                                     | 38.1 ms: 1.13x faster                                           |
| unpickle             | 9.11 us                                                     | 8.28 us: 1.10x faster                                           |
| json_loads           | 14.2 us                                                     | 13.5 us: 1.05x faster                                           |
| xml_etree_parse      | 96.8 ms                                                     | 92.7 ms: 1.04x faster                                           |
| xml_etree_generate   | 54.5 ms                                                     | 56.2 ms: 1.03x slower                                           |
| pickle_list          | 2.69 us                                                     | 2.84 us: 1.05x slower                                           |
| pickle_dict          | 17.1 us                                                     | 18.1 us: 1.06x slower                                           |
| unpickle_list        | 2.68 us                                                     | 2.83 us: 1.06x slower                                           |
| Geometric mean       | (ref)                                                       | 1.10x faster                                                    |

Benchmark hidden because not significant (2): pickle, xml_etree_iterparse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230619-pythonperf1-amd64-python-v3.12.0b3-3.12.0b3-f992a60 |
|------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| python_startup         | 19.7 ms                                                     | 20.4 ms: 1.04x slower                                           |
| python_startup_no_site | 15.3 ms                                                     | 17.1 ms: 1.11x slower                                           |
| Geometric mean         | (ref)                                                       | 1.07x slower                                                    |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230619-pythonperf1-amd64-python-v3.12.0b3-3.12.0b3-f992a60 |
|-----------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| mako      | 8.98 ms                                                     | 6.88 ms: 1.31x faster                                           |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230619-pythonperf1-amd64-python-v3.12.0b3-3.12.0b3-f992a60 |
|--------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| typing_runtime_protocols | 337 us                                                      | 94.6 us: 3.56x faster                                           |
| deltablue                | 4.12 ms                                                     | 2.07 ms: 1.99x faster                                           |
| richards_super           | 50.3 ms                                                     | 29.7 ms: 1.69x faster                                           |
| mypy2                    | 347 ms                                                      | 215 ms: 1.61x faster                                            |
| logging_silent           | 93.4 ns                                                     | 59.3 ns: 1.58x faster                                           |
| richards                 | 40.6 ms                                                     | 26.1 ms: 1.56x faster                                           |
| go                       | 135 ms                                                      | 88.3 ms: 1.53x faster                                           |
| json_dumps               | 8.77 ms                                                     | 5.79 ms: 1.52x faster                                           |
| sqlglot_parse            | 1.20 ms                                                     | 802 us: 1.50x faster                                            |
| scimark_lu               | 84.0 ms                                                     | 56.6 ms: 1.48x faster                                           |
| async_tree_none          | 424 ms                                                      | 292 ms: 1.45x faster                                            |
| raytrace                 | 266 ms                                                      | 184 ms: 1.44x faster                                            |
| generators               | 31.8 ms                                                     | 22.0 ms: 1.44x faster                                           |
| asyncio_tcp              | 717 ms                                                      | 498 ms: 1.44x faster                                            |
| async_tree_io            | 1.07 sec                                                    | 744 ms: 1.44x faster                                            |
| async_tree_memoization   | 505 ms                                                      | 352 ms: 1.44x faster                                            |
| sqlglot_transpile        | 1.45 ms                                                     | 1.01 ms: 1.43x faster                                           |
| hexiom                   | 5.59 ms                                                     | 3.99 ms: 1.40x faster                                           |
| chaos                    | 59.5 ms                                                     | 42.8 ms: 1.39x faster                                           |
| scimark_monte_carlo      | 58.0 ms                                                     | 42.6 ms: 1.36x faster                                           |
| pyflate                  | 402 ms                                                      | 297 ms: 1.35x faster                                            |
| scimark_sor              | 105 ms                                                      | 78.1 ms: 1.35x faster                                           |
| unpickle_pure_python     | 177 us                                                      | 132 us: 1.34x faster                                            |
| pickle_pure_python       | 259 us                                                      | 194 us: 1.34x faster                                            |
| crypto_pyaes             | 63.1 ms                                                     | 47.6 ms: 1.32x faster                                           |
| mako                     | 8.98 ms                                                     | 6.88 ms: 1.31x faster                                           |
| pycparser                | 905 ms                                                      | 699 ms: 1.29x faster                                            |
| async_tree_cpu_io_mixed  | 617 ms                                                      | 493 ms: 1.25x faster                                            |
| deepcopy_memo            | 29.0 us                                                     | 23.3 us: 1.24x faster                                           |
| spectral_norm            | 78.9 ms                                                     | 64.6 ms: 1.22x faster                                           |
| mdp                      | 1.71 sec                                                    | 1.43 sec: 1.20x faster                                          |
| tomli_loads              | 1.65 sec                                                    | 1.38 sec: 1.19x faster                                          |
| comprehensions           | 16.6 us                                                     | 14.0 us: 1.19x faster                                           |
| pprint_pformat           | 1.22 sec                                                    | 1.04 sec: 1.18x faster                                          |
| tornado_http             | 106 ms                                                      | 90.2 ms: 1.17x faster                                           |
| regex_compile            | 102 ms                                                      | 87.5 ms: 1.17x faster                                           |
| sqlglot_optimize         | 39.4 ms                                                     | 33.9 ms: 1.16x faster                                           |
| pprint_safe_repr         | 594 ms                                                      | 511 ms: 1.16x faster                                            |
| float                    | 61.7 ms                                                     | 54.0 ms: 1.14x faster                                           |
| docutils                 | 1.88 sec                                                    | 1.66 sec: 1.13x faster                                          |
| xml_etree_process        | 43.1 ms                                                     | 38.1 ms: 1.13x faster                                           |
| sqlglot_normalize        | 207 ms                                                      | 184 ms: 1.12x faster                                            |
| nqueens                  | 68.3 ms                                                     | 61.1 ms: 1.12x faster                                           |
| deepcopy                 | 259 us                                                      | 234 us: 1.11x faster                                            |
| coroutines               | 15.5 ms                                                     | 14.0 ms: 1.10x faster                                           |
| 2to3                     | 239 ms                                                      | 217 ms: 1.10x faster                                            |
| dulwich_log              | 48.6 ms                                                     | 44.1 ms: 1.10x faster                                           |
| unpickle                 | 9.11 us                                                     | 8.28 us: 1.10x faster                                           |
| aiohttp                  | 961 us                                                      | 887 us: 1.08x faster                                            |
| scimark_sparse_mat_mult  | 2.67 ms                                                     | 2.47 ms: 1.08x faster                                           |
| create_gc_cycles         | 800 us                                                      | 744 us: 1.08x faster                                            |
| scimark_fft              | 187 ms                                                      | 175 ms: 1.07x faster                                            |
| regex_v8                 | 15.0 ms                                                     | 14.0 ms: 1.07x faster                                           |
| deepcopy_reduce          | 2.22 us                                                     | 2.08 us: 1.07x faster                                           |
| regex_dna                | 129 ms                                                      | 122 ms: 1.06x faster                                            |
| fannkuch                 | 258 ms                                                      | 243 ms: 1.06x faster                                            |
| json_loads               | 14.2 us                                                     | 13.5 us: 1.05x faster                                           |
| bench_thread_pool        | 913 us                                                      | 866 us: 1.05x faster                                            |
| nbody                    | 71.0 ms                                                     | 67.6 ms: 1.05x faster                                           |
| xml_etree_parse          | 96.8 ms                                                     | 92.7 ms: 1.04x faster                                           |
| unpack_sequence          | 40.0 ns                                                     | 38.8 ns: 1.03x faster                                           |
| json                     | 3.10 ms                                                     | 3.01 ms: 1.03x faster                                           |
| sqlite_synth             | 1.90 us                                                     | 1.86 us: 1.02x faster                                           |
| logging_simple           | 6.28 us                                                     | 6.44 us: 1.03x slower                                           |
| logging_format           | 6.73 us                                                     | 6.91 us: 1.03x slower                                           |
| regex_effbot             | 1.56 ms                                                     | 1.61 ms: 1.03x slower                                           |
| xml_etree_generate       | 54.5 ms                                                     | 56.2 ms: 1.03x slower                                           |
| python_startup           | 19.7 ms                                                     | 20.4 ms: 1.04x slower                                           |
| pidigits                 | 146 ms                                                      | 154 ms: 1.05x slower                                            |
| pickle_list              | 2.69 us                                                     | 2.84 us: 1.05x slower                                           |
| pickle_dict              | 17.1 us                                                     | 18.1 us: 1.06x slower                                           |
| unpickle_list            | 2.68 us                                                     | 2.83 us: 1.06x slower                                           |
| async_generators         | 219 ms                                                      | 234 ms: 1.07x slower                                            |
| telco                    | 3.82 ms                                                     | 4.11 ms: 1.08x slower                                           |
| gc_traversal             | 1.40 ms                                                     | 1.53 ms: 1.10x slower                                           |
| python_startup_no_site   | 15.3 ms                                                     | 17.1 ms: 1.11x slower                                           |
| bench_mp_pool            | 59.9 ms                                                     | 67.9 ms: 1.13x slower                                           |
| pathlib                  | 72.8 ms                                                     | 82.8 ms: 1.14x slower                                           |
| dask                     | 305 ms                                                      | 370 ms: 1.21x slower                                            |
| coverage                 | 38.4 ms                                                     | 52.8 ms: 1.38x slower                                           |
| Geometric mean           | (ref)                                                       | 1.17x faster                                                    |

Benchmark hidden because not significant (4): asyncio_tcp_ssl, pickle, meteor_contest, xml_etree_iterparse
Ignored benchmarks (14) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120.json: chameleon, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.12x
- 95% likely to have a speedup of 1.11x
- 99% likely to have a speedup of 1.10x
