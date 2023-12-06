
# Results vs. 3.11.0

- fork: python
- ref: v3.12.0b1
- machine: windows-amd64
- commit hash: 5612078
- commit date: 2023-05-22
- overall geometric mean: 1.02x faster \*
- HPT reliability: 57.78%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230522-pythonperf1-amd64-python-v3.12.0b1-3.12.0b1-5612078 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| 2to3           | 207 ms                                                      | 218 ms: 1.05x slower                                            |
| docutils       | 1.59 sec                                                    | 1.67 sec: 1.05x slower                                          |
| tornado_http   | 89.9 ms                                                     | 98.2 ms: 1.09x slower                                           |
| Geometric mean | (ref)                                                       | 1.07x slower                                                    |

Benchmarks with tag 'asyncio':
==============================

| Benchmark              | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230522-pythonperf1-amd64-python-v3.12.0b1-3.12.0b1-5612078 |
|------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| async_tree_memoization | 367 ms                                                      | 351 ms: 1.04x faster                                            |
| async_tree_none        | 314 ms                                                      | 309 ms: 1.01x faster                                            |
| async_tree_io          | 753 ms                                                      | 765 ms: 1.02x slower                                            |
| Geometric mean         | (ref)                                                       | 1.01x faster                                                    |

Benchmark hidden because not significant (1): async_tree_cpu_io_mixed

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230522-pythonperf1-amd64-python-v3.12.0b1-3.12.0b1-5612078 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| pidigits       | 149 ms                                                      | 153 ms: 1.03x slower                                            |
| float          | 54.4 ms                                                     | 56.5 ms: 1.04x slower                                           |
| Geometric mean | (ref)                                                       | 1.02x slower                                                    |

Benchmark hidden because not significant (1): nbody

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230522-pythonperf1-amd64-python-v3.12.0b1-3.12.0b1-5612078 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| regex_compile  | 90.8 ms                                                     | 89.3 ms: 1.02x faster                                           |
| regex_v8       | 13.7 ms                                                     | 13.9 ms: 1.02x slower                                           |
| regex_dna      | 121 ms                                                      | 126 ms: 1.04x slower                                            |
| regex_effbot   | 1.52 ms                                                     | 1.62 ms: 1.07x slower                                           |
| Geometric mean | (ref)                                                       | 1.03x slower                                                    |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230522-pythonperf1-amd64-python-v3.12.0b1-3.12.0b1-5612078 |
|----------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| json_dumps           | 7.90 ms                                                     | 5.68 ms: 1.39x faster                                           |
| unpickle_pure_python | 152 us                                                      | 137 us: 1.11x faster                                            |
| pickle_pure_python   | 207 us                                                      | 196 us: 1.06x faster                                            |
| tomli_loads          | 1.42 sec                                                    | 1.39 sec: 1.02x faster                                          |
| xml_etree_parse      | 94.5 ms                                                     | 93.8 ms: 1.01x faster                                           |
| xml_etree_process    | 37.0 ms                                                     | 38.6 ms: 1.04x slower                                           |
| xml_etree_iterparse  | 63.0 ms                                                     | 66.2 ms: 1.05x slower                                           |
| pickle_list          | 2.68 us                                                     | 2.86 us: 1.07x slower                                           |
| json_loads           | 12.9 us                                                     | 13.8 us: 1.07x slower                                           |
| pickle               | 6.53 us                                                     | 7.00 us: 1.07x slower                                           |
| pickle_dict          | 17.8 us                                                     | 19.2 us: 1.08x slower                                           |
| unpickle             | 7.82 us                                                     | 8.47 us: 1.08x slower                                           |
| xml_etree_generate   | 52.2 ms                                                     | 56.6 ms: 1.08x slower                                           |
| unpickle_list        | 2.57 us                                                     | 2.92 us: 1.14x slower                                           |
| Geometric mean       | (ref)                                                       | 1.01x slower                                                    |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230522-pythonperf1-amd64-python-v3.12.0b1-3.12.0b1-5612078 |
|------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| python_startup         | 18.8 ms                                                     | 20.8 ms: 1.11x slower                                           |
| python_startup_no_site | 15.5 ms                                                     | 17.8 ms: 1.15x slower                                           |
| Geometric mean         | (ref)                                                       | 1.13x slower                                                    |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230522-pythonperf1-amd64-python-v3.12.0b1-3.12.0b1-5612078 |
|-----------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| mako      | 7.55 ms                                                     | 7.24 ms: 1.04x faster                                           |

All benchmarks:
===============

| Benchmark                | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230522-pythonperf1-amd64-python-v3.12.0b1-3.12.0b1-5612078 |
|--------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| typing_runtime_protocols | 320 us                                                      | 94.7 us: 3.38x faster                                           |
| generators               | 34.0 ms                                                     | 23.0 ms: 1.48x faster                                           |
| json_dumps               | 7.90 ms                                                     | 5.68 ms: 1.39x faster                                           |
| richards_super           | 37.9 ms                                                     | 29.1 ms: 1.30x faster                                           |
| mdp                      | 1.73 sec                                                    | 1.40 sec: 1.24x faster                                          |
| unpack_sequence          | 47.0 ns                                                     | 38.7 ns: 1.21x faster                                           |
| richards                 | 30.8 ms                                                     | 25.5 ms: 1.21x faster                                           |
| deltablue                | 2.63 ms                                                     | 2.20 ms: 1.19x faster                                           |
| logging_silent           | 70.7 ns                                                     | 60.1 ns: 1.18x faster                                           |
| sqlglot_parse            | 939 us                                                      | 800 us: 1.17x faster                                            |
| sqlglot_transpile        | 1.15 ms                                                     | 1.02 ms: 1.13x faster                                           |
| go                       | 98.8 ms                                                     | 88.2 ms: 1.12x faster                                           |
| unpickle_pure_python     | 152 us                                                      | 137 us: 1.11x faster                                            |
| hexiom                   | 4.51 ms                                                     | 4.09 ms: 1.10x faster                                           |
| raytrace                 | 211 ms                                                      | 192 ms: 1.10x faster                                            |
| comprehensions           | 15.6 us                                                     | 14.4 us: 1.08x faster                                           |
| deepcopy_memo            | 25.5 us                                                     | 23.7 us: 1.07x faster                                           |
| nqueens                  | 66.1 ms                                                     | 61.6 ms: 1.07x faster                                           |
| pickle_pure_python       | 207 us                                                      | 196 us: 1.06x faster                                            |
| chaos                    | 46.8 ms                                                     | 44.3 ms: 1.06x faster                                           |
| spectral_norm            | 69.9 ms                                                     | 66.3 ms: 1.05x faster                                           |
| async_tree_memoization   | 367 ms                                                      | 351 ms: 1.04x faster                                            |
| mako                     | 7.55 ms                                                     | 7.24 ms: 1.04x faster                                           |
| scimark_monte_carlo      | 44.6 ms                                                     | 42.9 ms: 1.04x faster                                           |
| scimark_lu               | 62.3 ms                                                     | 60.0 ms: 1.04x faster                                           |
| deepcopy                 | 242 us                                                      | 236 us: 1.03x faster                                            |
| scimark_sparse_mat_mult  | 2.59 ms                                                     | 2.52 ms: 1.03x faster                                           |
| mypy2                    | 226 ms                                                      | 221 ms: 1.03x faster                                            |
| tomli_loads              | 1.42 sec                                                    | 1.39 sec: 1.02x faster                                          |
| sqlglot_normalize        | 191 ms                                                      | 187 ms: 1.02x faster                                            |
| pyflate                  | 305 ms                                                      | 298 ms: 1.02x faster                                            |
| regex_compile            | 90.8 ms                                                     | 89.3 ms: 1.02x faster                                           |
| scimark_fft              | 181 ms                                                      | 178 ms: 1.02x faster                                            |
| crypto_pyaes             | 48.2 ms                                                     | 47.4 ms: 1.02x faster                                           |
| coroutines               | 14.7 ms                                                     | 14.4 ms: 1.02x faster                                           |
| async_tree_none          | 314 ms                                                      | 309 ms: 1.01x faster                                            |
| fannkuch                 | 248 ms                                                      | 246 ms: 1.01x faster                                            |
| xml_etree_parse          | 94.5 ms                                                     | 93.8 ms: 1.01x faster                                           |
| pprint_pformat           | 1.06 sec                                                    | 1.06 sec: 1.01x faster                                          |
| sqlite_synth             | 1.79 us                                                     | 1.78 us: 1.01x faster                                           |
| meteor_contest           | 75.0 ms                                                     | 75.2 ms: 1.00x slower                                           |
| deepcopy_reduce          | 2.07 us                                                     | 2.10 us: 1.01x slower                                           |
| async_tree_io            | 753 ms                                                      | 765 ms: 1.02x slower                                            |
| regex_v8                 | 13.7 ms                                                     | 13.9 ms: 1.02x slower                                           |
| logging_simple           | 6.60 us                                                     | 6.77 us: 1.03x slower                                           |
| dulwich_log              | 44.1 ms                                                     | 45.3 ms: 1.03x slower                                           |
| logging_format           | 7.06 us                                                     | 7.28 us: 1.03x slower                                           |
| pidigits                 | 149 ms                                                      | 153 ms: 1.03x slower                                            |
| regex_dna                | 121 ms                                                      | 126 ms: 1.04x slower                                            |
| float                    | 54.4 ms                                                     | 56.5 ms: 1.04x slower                                           |
| xml_etree_process        | 37.0 ms                                                     | 38.6 ms: 1.04x slower                                           |
| xml_etree_iterparse      | 63.0 ms                                                     | 66.2 ms: 1.05x slower                                           |
| gc_traversal             | 1.46 ms                                                     | 1.53 ms: 1.05x slower                                           |
| docutils                 | 1.59 sec                                                    | 1.67 sec: 1.05x slower                                          |
| 2to3                     | 207 ms                                                      | 218 ms: 1.05x slower                                            |
| scimark_sor              | 76.4 ms                                                     | 80.6 ms: 1.05x slower                                           |
| bench_thread_pool        | 847 us                                                      | 895 us: 1.06x slower                                            |
| pickle_list              | 2.68 us                                                     | 2.86 us: 1.07x slower                                           |
| regex_effbot             | 1.52 ms                                                     | 1.62 ms: 1.07x slower                                           |
| json_loads               | 12.9 us                                                     | 13.8 us: 1.07x slower                                           |
| pickle                   | 6.53 us                                                     | 7.00 us: 1.07x slower                                           |
| telco                    | 3.93 ms                                                     | 4.23 ms: 1.08x slower                                           |
| pickle_dict              | 17.8 us                                                     | 19.2 us: 1.08x slower                                           |
| unpickle                 | 7.82 us                                                     | 8.47 us: 1.08x slower                                           |
| xml_etree_generate       | 52.2 ms                                                     | 56.6 ms: 1.08x slower                                           |
| create_gc_cycles         | 706 us                                                      | 766 us: 1.09x slower                                            |
| aiohttp                  | 854 us                                                      | 928 us: 1.09x slower                                            |
| tornado_http             | 89.9 ms                                                     | 98.2 ms: 1.09x slower                                           |
| python_startup           | 18.8 ms                                                     | 20.8 ms: 1.11x slower                                           |
| asyncio_tcp              | 614 ms                                                      | 686 ms: 1.12x slower                                            |
| unpickle_list            | 2.57 us                                                     | 2.92 us: 1.14x slower                                           |
| bench_mp_pool            | 61.1 ms                                                     | 70.0 ms: 1.14x slower                                           |
| python_startup_no_site   | 15.5 ms                                                     | 17.8 ms: 1.15x slower                                           |
| asyncio_tcp_ssl          | 2.02 sec                                                    | 2.39 sec: 1.18x slower                                          |
| coverage                 | 43.0 ms                                                     | 50.9 ms: 1.19x slower                                           |
| pathlib                  | 69.4 ms                                                     | 85.4 ms: 1.23x slower                                           |
| async_generators         | 181 ms                                                      | 237 ms: 1.31x slower                                            |
| dask                     | 262 ms                                                      | 382 ms: 1.46x slower                                            |
| Geometric mean           | (ref)                                                       | 1.02x faster                                                    |

Benchmark hidden because not significant (6): pycparser, nbody, pprint_safe_repr, json, async_tree_cpu_io_mixed, sqlglot_optimize
Ignored benchmarks (18) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 57.78% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
