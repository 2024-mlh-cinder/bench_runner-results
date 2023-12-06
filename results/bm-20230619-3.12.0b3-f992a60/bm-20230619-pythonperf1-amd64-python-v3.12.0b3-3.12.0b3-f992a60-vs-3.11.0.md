
# Results vs. 3.11.0

- fork: python
- ref: v3.12.0b3
- machine: windows-amd64
- commit hash: f992a60
- commit date: 2023-06-19
- overall geometric mean: 1.04x faster \*
- HPT reliability: 97.43%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230619-pythonperf1-amd64-python-v3.12.0b3-3.12.0b3-f992a60 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| 2to3           | 207 ms                                                      | 217 ms: 1.04x slower                                            |
| docutils       | 1.59 sec                                                    | 1.66 sec: 1.04x slower                                          |
| Geometric mean | (ref)                                                       | 1.03x slower                                                    |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'asyncio':
==============================

| Benchmark              | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230619-pythonperf1-amd64-python-v3.12.0b3-3.12.0b3-f992a60 |
|------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| async_tree_none        | 314 ms                                                      | 292 ms: 1.07x faster                                            |
| async_tree_memoization | 367 ms                                                      | 352 ms: 1.04x faster                                            |
| async_tree_io          | 753 ms                                                      | 744 ms: 1.01x faster                                            |
| Geometric mean         | (ref)                                                       | 1.03x faster                                                    |

Benchmark hidden because not significant (1): async_tree_cpu_io_mixed

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230619-pythonperf1-amd64-python-v3.12.0b3-3.12.0b3-f992a60 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| nbody          | 69.3 ms                                                     | 67.6 ms: 1.02x faster                                           |
| pidigits       | 149 ms                                                      | 154 ms: 1.04x slower                                            |
| Geometric mean | (ref)                                                       | 1.00x slower                                                    |

Benchmark hidden because not significant (1): float

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230619-pythonperf1-amd64-python-v3.12.0b3-3.12.0b3-f992a60 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| regex_compile  | 90.8 ms                                                     | 87.5 ms: 1.04x faster                                           |
| regex_v8       | 13.7 ms                                                     | 14.0 ms: 1.02x slower                                           |
| regex_effbot   | 1.52 ms                                                     | 1.61 ms: 1.06x slower                                           |
| Geometric mean | (ref)                                                       | 1.01x slower                                                    |

Benchmark hidden because not significant (1): regex_dna

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230619-pythonperf1-amd64-python-v3.12.0b3-3.12.0b3-f992a60 |
|----------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| json_dumps           | 7.90 ms                                                     | 5.79 ms: 1.37x faster                                           |
| unpickle_pure_python | 152 us                                                      | 132 us: 1.15x faster                                            |
| pickle_pure_python   | 207 us                                                      | 194 us: 1.07x faster                                            |
| tomli_loads          | 1.42 sec                                                    | 1.38 sec: 1.03x faster                                          |
| xml_etree_parse      | 94.5 ms                                                     | 92.7 ms: 1.02x faster                                           |
| pickle_dict          | 17.8 us                                                     | 18.1 us: 1.02x slower                                           |
| xml_etree_iterparse  | 63.0 ms                                                     | 64.6 ms: 1.03x slower                                           |
| xml_etree_process    | 37.0 ms                                                     | 38.1 ms: 1.03x slower                                           |
| json_loads           | 12.9 us                                                     | 13.5 us: 1.05x slower                                           |
| pickle               | 6.53 us                                                     | 6.86 us: 1.05x slower                                           |
| unpickle             | 7.82 us                                                     | 8.28 us: 1.06x slower                                           |
| pickle_list          | 2.68 us                                                     | 2.84 us: 1.06x slower                                           |
| xml_etree_generate   | 52.2 ms                                                     | 56.2 ms: 1.08x slower                                           |
| unpickle_list        | 2.57 us                                                     | 2.83 us: 1.10x slower                                           |
| Geometric mean       | (ref)                                                       | 1.01x faster                                                    |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230619-pythonperf1-amd64-python-v3.12.0b3-3.12.0b3-f992a60 |
|------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| python_startup         | 18.8 ms                                                     | 20.4 ms: 1.08x slower                                           |
| python_startup_no_site | 15.5 ms                                                     | 17.1 ms: 1.10x slower                                           |
| Geometric mean         | (ref)                                                       | 1.09x slower                                                    |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230619-pythonperf1-amd64-python-v3.12.0b3-3.12.0b3-f992a60 |
|-----------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| mako      | 7.55 ms                                                     | 6.88 ms: 1.10x faster                                           |

All benchmarks:
===============

| Benchmark                | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230619-pythonperf1-amd64-python-v3.12.0b3-3.12.0b3-f992a60 |
|--------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| typing_runtime_protocols | 320 us                                                      | 94.6 us: 3.38x faster                                           |
| generators               | 34.0 ms                                                     | 22.0 ms: 1.54x faster                                           |
| json_dumps               | 7.90 ms                                                     | 5.79 ms: 1.37x faster                                           |
| richards_super           | 37.9 ms                                                     | 29.7 ms: 1.27x faster                                           |
| deltablue                | 2.63 ms                                                     | 2.07 ms: 1.27x faster                                           |
| asyncio_tcp              | 614 ms                                                      | 498 ms: 1.23x faster                                            |
| unpack_sequence          | 47.0 ns                                                     | 38.8 ns: 1.21x faster                                           |
| mdp                      | 1.73 sec                                                    | 1.43 sec: 1.20x faster                                          |
| logging_silent           | 70.7 ns                                                     | 59.3 ns: 1.19x faster                                           |
| richards                 | 30.8 ms                                                     | 26.1 ms: 1.18x faster                                           |
| sqlglot_parse            | 939 us                                                      | 802 us: 1.17x faster                                            |
| unpickle_pure_python     | 152 us                                                      | 132 us: 1.15x faster                                            |
| raytrace                 | 211 ms                                                      | 184 ms: 1.14x faster                                            |
| sqlglot_transpile        | 1.15 ms                                                     | 1.01 ms: 1.13x faster                                           |
| hexiom                   | 4.51 ms                                                     | 3.99 ms: 1.13x faster                                           |
| go                       | 98.8 ms                                                     | 88.3 ms: 1.12x faster                                           |
| comprehensions           | 15.6 us                                                     | 14.0 us: 1.11x faster                                           |
| scimark_lu               | 62.3 ms                                                     | 56.6 ms: 1.10x faster                                           |
| mako                     | 7.55 ms                                                     | 6.88 ms: 1.10x faster                                           |
| chaos                    | 46.8 ms                                                     | 42.8 ms: 1.09x faster                                           |
| deepcopy_memo            | 25.5 us                                                     | 23.3 us: 1.09x faster                                           |
| nqueens                  | 66.1 ms                                                     | 61.1 ms: 1.08x faster                                           |
| spectral_norm            | 69.9 ms                                                     | 64.6 ms: 1.08x faster                                           |
| async_tree_none          | 314 ms                                                      | 292 ms: 1.07x faster                                            |
| pickle_pure_python       | 207 us                                                      | 194 us: 1.07x faster                                            |
| mypy2                    | 226 ms                                                      | 215 ms: 1.05x faster                                            |
| scimark_sparse_mat_mult  | 2.59 ms                                                     | 2.47 ms: 1.05x faster                                           |
| scimark_monte_carlo      | 44.6 ms                                                     | 42.6 ms: 1.05x faster                                           |
| coroutines               | 14.7 ms                                                     | 14.0 ms: 1.05x faster                                           |
| async_tree_memoization   | 367 ms                                                      | 352 ms: 1.04x faster                                            |
| regex_compile            | 90.8 ms                                                     | 87.5 ms: 1.04x faster                                           |
| scimark_fft              | 181 ms                                                      | 175 ms: 1.04x faster                                            |
| deepcopy                 | 242 us                                                      | 234 us: 1.04x faster                                            |
| sqlglot_normalize        | 191 ms                                                      | 184 ms: 1.04x faster                                            |
| sqlglot_optimize         | 35.1 ms                                                     | 33.9 ms: 1.03x faster                                           |
| tomli_loads              | 1.42 sec                                                    | 1.38 sec: 1.03x faster                                          |
| pprint_pformat           | 1.06 sec                                                    | 1.04 sec: 1.03x faster                                          |
| pyflate                  | 305 ms                                                      | 297 ms: 1.03x faster                                            |
| logging_simple           | 6.60 us                                                     | 6.44 us: 1.03x faster                                           |
| nbody                    | 69.3 ms                                                     | 67.6 ms: 1.02x faster                                           |
| logging_format           | 7.06 us                                                     | 6.91 us: 1.02x faster                                           |
| fannkuch                 | 248 ms                                                      | 243 ms: 1.02x faster                                            |
| xml_etree_parse          | 94.5 ms                                                     | 92.7 ms: 1.02x faster                                           |
| meteor_contest           | 75.0 ms                                                     | 73.9 ms: 1.01x faster                                           |
| pprint_safe_repr         | 519 ms                                                      | 511 ms: 1.01x faster                                            |
| async_tree_io            | 753 ms                                                      | 744 ms: 1.01x faster                                            |
| crypto_pyaes             | 48.2 ms                                                     | 47.6 ms: 1.01x faster                                           |
| pickle_dict              | 17.8 us                                                     | 18.1 us: 1.02x slower                                           |
| bench_thread_pool        | 847 us                                                      | 866 us: 1.02x slower                                            |
| scimark_sor              | 76.4 ms                                                     | 78.1 ms: 1.02x slower                                           |
| regex_v8                 | 13.7 ms                                                     | 14.0 ms: 1.02x slower                                           |
| xml_etree_iterparse      | 63.0 ms                                                     | 64.6 ms: 1.03x slower                                           |
| xml_etree_process        | 37.0 ms                                                     | 38.1 ms: 1.03x slower                                           |
| sqlite_synth             | 1.79 us                                                     | 1.86 us: 1.03x slower                                           |
| pidigits                 | 149 ms                                                      | 154 ms: 1.04x slower                                            |
| aiohttp                  | 854 us                                                      | 887 us: 1.04x slower                                            |
| docutils                 | 1.59 sec                                                    | 1.66 sec: 1.04x slower                                          |
| 2to3                     | 207 ms                                                      | 217 ms: 1.04x slower                                            |
| telco                    | 3.93 ms                                                     | 4.11 ms: 1.05x slower                                           |
| json_loads               | 12.9 us                                                     | 13.5 us: 1.05x slower                                           |
| pickle                   | 6.53 us                                                     | 6.86 us: 1.05x slower                                           |
| gc_traversal             | 1.46 ms                                                     | 1.53 ms: 1.05x slower                                           |
| create_gc_cycles         | 706 us                                                      | 744 us: 1.05x slower                                            |
| unpickle                 | 7.82 us                                                     | 8.28 us: 1.06x slower                                           |
| regex_effbot             | 1.52 ms                                                     | 1.61 ms: 1.06x slower                                           |
| pickle_list              | 2.68 us                                                     | 2.84 us: 1.06x slower                                           |
| xml_etree_generate       | 52.2 ms                                                     | 56.2 ms: 1.08x slower                                           |
| python_startup           | 18.8 ms                                                     | 20.4 ms: 1.08x slower                                           |
| python_startup_no_site   | 15.5 ms                                                     | 17.1 ms: 1.10x slower                                           |
| unpickle_list            | 2.57 us                                                     | 2.83 us: 1.10x slower                                           |
| bench_mp_pool            | 61.1 ms                                                     | 67.9 ms: 1.11x slower                                           |
| pathlib                  | 69.4 ms                                                     | 82.8 ms: 1.19x slower                                           |
| coverage                 | 43.0 ms                                                     | 52.8 ms: 1.23x slower                                           |
| async_generators         | 181 ms                                                      | 234 ms: 1.29x slower                                            |
| dask                     | 262 ms                                                      | 370 ms: 1.41x slower                                            |
| Geometric mean           | (ref)                                                       | 1.04x faster                                                    |

Benchmark hidden because not significant (9): pycparser, float, async_tree_cpu_io_mixed, dulwich_log, deepcopy_reduce, regex_dna, tornado_http, json, asyncio_tcp_ssl
Ignored benchmarks (18) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 97.43% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
