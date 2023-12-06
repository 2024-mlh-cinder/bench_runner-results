
# Results vs. 3.12.0

- fork: python
- ref: v3.12.0b1
- machine: linux-x86_64
- commit hash: 5612078
- commit date: 2023-05-22
- overall geometric mean: 1.01x slower \*
- HPT reliability: 99.73%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230522-pythonperf2-x86_64-python-v3.12.0b1-3.12.0b1-5612078 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| 2to3           | 285 ms                                                       | 284 ms: 1.00x faster                                             |
| docutils       | 2.89 sec                                                     | 2.87 sec: 1.01x faster                                           |
| tornado_http   | 122 ms                                                       | 115 ms: 1.06x faster                                             |
| Geometric mean | (ref)                                                        | 1.02x faster                                                     |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230522-pythonperf2-x86_64-python-v3.12.0b1-3.12.0b1-5612078 |
|-------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| async_tree_memoization  | 554 ms                                                       | 544 ms: 1.02x faster                                             |
| async_tree_none         | 459 ms                                                       | 453 ms: 1.01x faster                                             |
| async_tree_cpu_io_mixed | 704 ms                                                       | 696 ms: 1.01x faster                                             |
| async_tree_io           | 1.06 sec                                                     | 1.05 sec: 1.01x faster                                           |
| Geometric mean          | (ref)                                                        | 1.01x faster                                                     |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230522-pythonperf2-x86_64-python-v3.12.0b1-3.12.0b1-5612078 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| nbody          | 88.2 ms                                                      | 84.7 ms: 1.04x faster                                            |
| float          | 81.6 ms                                                      | 78.6 ms: 1.04x faster                                            |
| pidigits       | 264 ms                                                       | 261 ms: 1.01x faster                                             |
| Geometric mean | (ref)                                                        | 1.03x faster                                                     |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230522-pythonperf2-x86_64-python-v3.12.0b1-3.12.0b1-5612078 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| regex_v8       | 24.4 ms                                                      | 22.8 ms: 1.07x faster                                            |
| regex_effbot   | 3.61 ms                                                      | 3.49 ms: 1.03x faster                                            |
| regex_dna      | 240 ms                                                       | 237 ms: 1.01x faster                                             |
| regex_compile  | 145 ms                                                       | 143 ms: 1.01x faster                                             |
| Geometric mean | (ref)                                                        | 1.03x faster                                                     |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230522-pythonperf2-x86_64-python-v3.12.0b1-3.12.0b1-5612078 |
|----------------------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| unpickle             | 15.3 us                                                      | 14.4 us: 1.06x faster                                            |
| unpickle_pure_python | 210 us                                                       | 204 us: 1.03x faster                                             |
| tomli_loads          | 2.17 sec                                                     | 2.12 sec: 1.02x faster                                           |
| json_dumps           | 10.3 ms                                                      | 10.2 ms: 1.01x faster                                            |
| xml_etree_process    | 58.3 ms                                                      | 59.0 ms: 1.01x slower                                            |
| unpickle_list        | 4.65 us                                                      | 4.72 us: 1.02x slower                                            |
| xml_etree_generate   | 85.3 ms                                                      | 86.8 ms: 1.02x slower                                            |
| pickle_pure_python   | 319 us                                                       | 325 us: 1.02x slower                                             |
| xml_etree_iterparse  | 104 ms                                                       | 106 ms: 1.02x slower                                             |
| pickle_list          | 4.22 us                                                      | 4.37 us: 1.04x slower                                            |
| pickle_dict          | 32.0 us                                                      | 33.2 us: 1.04x slower                                            |
| Geometric mean       | (ref)                                                        | 1.00x slower                                                     |

Benchmark hidden because not significant (3): json_loads, xml_etree_parse, pickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230522-pythonperf2-x86_64-python-v3.12.0b1-3.12.0b1-5612078 |
|------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| python_startup_no_site | 8.67 ms                                                      | 8.50 ms: 1.02x faster                                            |
| python_startup         | 11.7 ms                                                      | 11.5 ms: 1.01x faster                                            |
| Geometric mean         | (ref)                                                        | 1.02x faster                                                     |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230522-pythonperf2-x86_64-python-v3.12.0b1-3.12.0b1-5612078 |
|-----------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| mako      | 10.1 ms                                                      | 9.94 ms: 1.01x faster                                            |

All benchmarks:
===============

| Benchmark                | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230522-pythonperf2-x86_64-python-v3.12.0b1-3.12.0b1-5612078 |
|--------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| unpack_sequence          | 54.5 ns                                                      | 48.1 ns: 1.13x faster                                            |
| regex_v8                 | 24.4 ms                                                      | 22.8 ms: 1.07x faster                                            |
| generators               | 37.3 ms                                                      | 35.1 ms: 1.06x faster                                            |
| unpickle                 | 15.3 us                                                      | 14.4 us: 1.06x faster                                            |
| tornado_http             | 122 ms                                                       | 115 ms: 1.06x faster                                             |
| nbody                    | 88.2 ms                                                      | 84.7 ms: 1.04x faster                                            |
| sqlglot_normalize        | 119 ms                                                       | 115 ms: 1.04x faster                                             |
| float                    | 81.6 ms                                                      | 78.6 ms: 1.04x faster                                            |
| regex_effbot             | 3.61 ms                                                      | 3.49 ms: 1.03x faster                                            |
| coroutines               | 23.1 ms                                                      | 22.3 ms: 1.03x faster                                            |
| unpickle_pure_python     | 210 us                                                       | 204 us: 1.03x faster                                             |
| scimark_sparse_mat_mult  | 4.49 ms                                                      | 4.38 ms: 1.02x faster                                            |
| pycparser                | 1.29 sec                                                     | 1.27 sec: 1.02x faster                                           |
| tomli_loads              | 2.17 sec                                                     | 2.12 sec: 1.02x faster                                           |
| sqlglot_optimize         | 58.4 ms                                                      | 57.2 ms: 1.02x faster                                            |
| logging_format           | 7.29 us                                                      | 7.14 us: 1.02x faster                                            |
| python_startup_no_site   | 8.67 ms                                                      | 8.50 ms: 1.02x faster                                            |
| fannkuch                 | 362 ms                                                       | 355 ms: 1.02x faster                                             |
| scimark_monte_carlo      | 69.5 ms                                                      | 68.2 ms: 1.02x faster                                            |
| sqlglot_parse            | 1.41 ms                                                      | 1.38 ms: 1.02x faster                                            |
| async_tree_memoization   | 554 ms                                                       | 544 ms: 1.02x faster                                             |
| hexiom                   | 5.97 ms                                                      | 5.88 ms: 1.02x faster                                            |
| async_generators         | 385 ms                                                       | 379 ms: 1.02x faster                                             |
| sqlite_synth             | 2.72 us                                                      | 2.68 us: 1.01x faster                                            |
| python_startup           | 11.7 ms                                                      | 11.5 ms: 1.01x faster                                            |
| async_tree_none          | 459 ms                                                       | 453 ms: 1.01x faster                                             |
| raytrace                 | 301 ms                                                       | 297 ms: 1.01x faster                                             |
| mako                     | 10.1 ms                                                      | 9.94 ms: 1.01x faster                                            |
| pidigits                 | 264 ms                                                       | 261 ms: 1.01x faster                                             |
| async_tree_cpu_io_mixed  | 704 ms                                                       | 696 ms: 1.01x faster                                             |
| deepcopy_reduce          | 3.41 us                                                      | 3.37 us: 1.01x faster                                            |
| regex_dna                | 240 ms                                                       | 237 ms: 1.01x faster                                             |
| mdp                      | 2.56 sec                                                     | 2.53 sec: 1.01x faster                                           |
| comprehensions           | 21.8 us                                                      | 21.6 us: 1.01x faster                                            |
| async_tree_io            | 1.06 sec                                                     | 1.05 sec: 1.01x faster                                           |
| sqlglot_transpile        | 1.80 ms                                                      | 1.79 ms: 1.01x faster                                            |
| typing_runtime_protocols | 150 us                                                       | 149 us: 1.01x faster                                             |
| json_dumps               | 10.3 ms                                                      | 10.2 ms: 1.01x faster                                            |
| go                       | 149 ms                                                       | 148 ms: 1.01x faster                                             |
| regex_compile            | 145 ms                                                       | 143 ms: 1.01x faster                                             |
| telco                    | 7.16 ms                                                      | 7.11 ms: 1.01x faster                                            |
| deltablue                | 3.24 ms                                                      | 3.22 ms: 1.01x faster                                            |
| docutils                 | 2.89 sec                                                     | 2.87 sec: 1.01x faster                                           |
| scimark_lu               | 98.6 ms                                                      | 98.0 ms: 1.01x faster                                            |
| logging_simple           | 6.64 us                                                      | 6.60 us: 1.01x faster                                            |
| 2to3                     | 285 ms                                                       | 284 ms: 1.00x faster                                             |
| asyncio_tcp_ssl          | 1.57 sec                                                     | 1.57 sec: 1.00x faster                                           |
| pprint_pformat           | 1.64 sec                                                     | 1.65 sec: 1.00x slower                                           |
| scimark_fft              | 303 ms                                                       | 305 ms: 1.01x slower                                             |
| meteor_contest           | 126 ms                                                       | 127 ms: 1.01x slower                                             |
| spectral_norm            | 93.9 ms                                                      | 94.5 ms: 1.01x slower                                            |
| xml_etree_process        | 58.3 ms                                                      | 59.0 ms: 1.01x slower                                            |
| unpickle_list            | 4.65 us                                                      | 4.72 us: 1.02x slower                                            |
| xml_etree_generate       | 85.3 ms                                                      | 86.8 ms: 1.02x slower                                            |
| pickle_pure_python       | 319 us                                                       | 325 us: 1.02x slower                                             |
| dulwich_log              | 64.9 ms                                                      | 66.1 ms: 1.02x slower                                            |
| scimark_sor              | 107 ms                                                       | 109 ms: 1.02x slower                                             |
| gc_traversal             | 3.70 ms                                                      | 3.79 ms: 1.02x slower                                            |
| xml_etree_iterparse      | 104 ms                                                       | 106 ms: 1.02x slower                                             |
| pathlib                  | 18.7 ms                                                      | 19.3 ms: 1.03x slower                                            |
| pickle_list              | 4.22 us                                                      | 4.37 us: 1.04x slower                                            |
| pickle_dict              | 32.0 us                                                      | 33.2 us: 1.04x slower                                            |
| create_gc_cycles         | 1.58 ms                                                      | 1.68 ms: 1.06x slower                                            |
| mypy2                    | 365 ms                                                       | 457 ms: 1.25x slower                                             |
| coverage                 | 66.3 ms                                                      | 88.0 ms: 1.33x slower                                            |
| dask                     | 394 ms                                                       | 551 ms: 1.40x slower                                             |
| bench_mp_pool            | 4.96 ms                                                      | 8.65 ms: 1.74x slower                                            |
| Geometric mean           | (ref)                                                        | 1.01x slower                                                     |

Benchmark hidden because not significant (16): bench_thread_pool, logging_silent, deepcopy, json_loads, json, xml_etree_parse, deepcopy_memo, chaos, richards, asyncio_tcp, crypto_pyaes, pickle, pprint_safe_repr, nqueens, pyflate, richards_super
Ignored benchmarks (15) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum


# HPT report

- Reliability score: 99.73% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
