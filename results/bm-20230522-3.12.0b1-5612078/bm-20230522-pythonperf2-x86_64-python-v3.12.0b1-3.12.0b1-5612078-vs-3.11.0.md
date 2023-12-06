
# Results vs. 3.11.0

- fork: python
- ref: v3.12.0b1
- machine: linux-x86_64
- commit hash: 5612078
- commit date: 2023-05-22
- overall geometric mean: 1.06x faster \*
- HPT reliability: 99.75%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230522-pythonperf2-x86_64-python-v3.12.0b1-3.12.0b1-5612078 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| 2to3           | 286 ms                                                       | 284 ms: 1.01x faster                                             |
| tornado_http   | 125 ms                                                       | 115 ms: 1.08x faster                                             |
| Geometric mean | (ref)                                                        | 1.03x faster                                                     |

Benchmark hidden because not significant (1): docutils

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230522-pythonperf2-x86_64-python-v3.12.0b1-3.12.0b1-5612078 |
|-------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| async_tree_memoization  | 648 ms                                                       | 544 ms: 1.19x faster                                             |
| async_tree_none         | 529 ms                                                       | 453 ms: 1.17x faster                                             |
| async_tree_io           | 1.19 sec                                                     | 1.05 sec: 1.14x faster                                           |
| async_tree_cpu_io_mixed | 762 ms                                                       | 696 ms: 1.09x faster                                             |
| Geometric mean          | (ref)                                                        | 1.15x faster                                                     |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230522-pythonperf2-x86_64-python-v3.12.0b1-3.12.0b1-5612078 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| nbody          | 95.8 ms                                                      | 84.7 ms: 1.13x faster                                            |
| float          | 76.0 ms                                                      | 78.6 ms: 1.03x slower                                            |
| pidigits       | 251 ms                                                       | 261 ms: 1.04x slower                                             |
| Geometric mean | (ref)                                                        | 1.02x faster                                                     |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230522-pythonperf2-x86_64-python-v3.12.0b1-3.12.0b1-5612078 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| regex_compile  | 157 ms                                                       | 143 ms: 1.10x faster                                             |
| regex_v8       | 23.7 ms                                                      | 22.8 ms: 1.04x faster                                            |
| regex_effbot   | 3.42 ms                                                      | 3.49 ms: 1.02x slower                                            |
| regex_dna      | 226 ms                                                       | 237 ms: 1.05x slower                                             |
| Geometric mean | (ref)                                                        | 1.01x faster                                                     |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230522-pythonperf2-x86_64-python-v3.12.0b1-3.12.0b1-5612078 |
|----------------------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| json_dumps           | 13.5 ms                                                      | 10.2 ms: 1.32x faster                                            |
| json_loads           | 29.0 us                                                      | 24.2 us: 1.20x faster                                            |
| unpickle_pure_python | 236 us                                                       | 204 us: 1.16x faster                                             |
| xml_etree_parse      | 159 ms                                                       | 147 ms: 1.08x faster                                             |
| tomli_loads          | 2.27 sec                                                     | 2.12 sec: 1.07x faster                                           |
| pickle_pure_python   | 318 us                                                       | 325 us: 1.02x slower                                             |
| pickle               | 9.77 us                                                      | 10.1 us: 1.03x slower                                            |
| pickle_dict          | 31.8 us                                                      | 33.2 us: 1.05x slower                                            |
| xml_etree_process    | 56.1 ms                                                      | 59.0 ms: 1.05x slower                                            |
| unpickle_list        | 4.47 us                                                      | 4.72 us: 1.06x slower                                            |
| xml_etree_generate   | 80.5 ms                                                      | 86.8 ms: 1.08x slower                                            |
| unpickle             | 13.2 us                                                      | 14.4 us: 1.09x slower                                            |
| pickle_list          | 3.89 us                                                      | 4.37 us: 1.12x slower                                            |
| Geometric mean       | (ref)                                                        | 1.02x faster                                                     |

Benchmark hidden because not significant (1): xml_etree_iterparse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230522-pythonperf2-x86_64-python-v3.12.0b1-3.12.0b1-5612078 |
|------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| python_startup         | 10.8 ms                                                      | 11.5 ms: 1.06x slower                                            |
| python_startup_no_site | 7.78 ms                                                      | 8.50 ms: 1.09x slower                                            |
| Geometric mean         | (ref)                                                        | 1.08x slower                                                     |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230522-pythonperf2-x86_64-python-v3.12.0b1-3.12.0b1-5612078 |
|-----------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| mako      | 11.0 ms                                                      | 9.94 ms: 1.11x faster                                            |

All benchmarks:
===============

| Benchmark                | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230522-pythonperf2-x86_64-python-v3.12.0b1-3.12.0b1-5612078 |
|--------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| typing_runtime_protocols | 527 us                                                       | 149 us: 3.54x faster                                             |
| asyncio_tcp              | 752 ms                                                       | 380 ms: 1.98x faster                                             |
| asyncio_tcp_ssl          | 3.09 sec                                                     | 1.57 sec: 1.97x faster                                           |
| generators               | 56.4 ms                                                      | 35.1 ms: 1.61x faster                                            |
| json_dumps               | 13.5 ms                                                      | 10.2 ms: 1.32x faster                                            |
| fannkuch                 | 457 ms                                                       | 355 ms: 1.29x faster                                             |
| richards_super           | 65.2 ms                                                      | 51.1 ms: 1.28x faster                                            |
| deltablue                | 4.03 ms                                                      | 3.22 ms: 1.25x faster                                            |
| coroutines               | 27.9 ms                                                      | 22.3 ms: 1.25x faster                                            |
| json_loads               | 29.0 us                                                      | 24.2 us: 1.20x faster                                            |
| async_tree_memoization   | 648 ms                                                       | 544 ms: 1.19x faster                                             |
| hexiom                   | 6.97 ms                                                      | 5.88 ms: 1.19x faster                                            |
| scimark_lu               | 115 ms                                                       | 98.0 ms: 1.18x faster                                            |
| async_tree_none          | 529 ms                                                       | 453 ms: 1.17x faster                                             |
| unpickle_pure_python     | 236 us                                                       | 204 us: 1.16x faster                                             |
| comprehensions           | 24.8 us                                                      | 21.6 us: 1.15x faster                                            |
| async_tree_io            | 1.19 sec                                                     | 1.05 sec: 1.14x faster                                           |
| nbody                    | 95.8 ms                                                      | 84.7 ms: 1.13x faster                                            |
| sqlglot_parse            | 1.55 ms                                                      | 1.38 ms: 1.12x faster                                            |
| go                       | 166 ms                                                       | 148 ms: 1.12x faster                                             |
| chaos                    | 71.6 ms                                                      | 64.0 ms: 1.12x faster                                            |
| richards                 | 49.9 ms                                                      | 45.0 ms: 1.11x faster                                            |
| mako                     | 11.0 ms                                                      | 9.94 ms: 1.11x faster                                            |
| nqueens                  | 99.2 ms                                                      | 90.2 ms: 1.10x faster                                            |
| logging_silent           | 102 ns                                                       | 93.0 ns: 1.10x faster                                            |
| logging_format           | 7.83 us                                                      | 7.14 us: 1.10x faster                                            |
| regex_compile            | 157 ms                                                       | 143 ms: 1.10x faster                                             |
| async_tree_cpu_io_mixed  | 762 ms                                                       | 696 ms: 1.09x faster                                             |
| logging_simple           | 7.21 us                                                      | 6.60 us: 1.09x faster                                            |
| sqlglot_transpile        | 1.94 ms                                                      | 1.79 ms: 1.08x faster                                            |
| tornado_http             | 125 ms                                                       | 115 ms: 1.08x faster                                             |
| json                     | 5.59 ms                                                      | 5.16 ms: 1.08x faster                                            |
| xml_etree_parse          | 159 ms                                                       | 147 ms: 1.08x faster                                             |
| bench_thread_pool        | 1.02 ms                                                      | 943 us: 1.08x faster                                             |
| mdp                      | 2.72 sec                                                     | 2.53 sec: 1.08x faster                                           |
| gc_traversal             | 4.06 ms                                                      | 3.79 ms: 1.07x faster                                            |
| tomli_loads              | 2.27 sec                                                     | 2.12 sec: 1.07x faster                                           |
| sqlglot_normalize        | 122 ms                                                       | 115 ms: 1.06x faster                                             |
| deepcopy                 | 389 us                                                       | 370 us: 1.05x faster                                             |
| raytrace                 | 308 ms                                                       | 297 ms: 1.04x faster                                             |
| sqlglot_optimize         | 59.2 ms                                                      | 57.2 ms: 1.04x faster                                            |
| regex_v8                 | 23.7 ms                                                      | 22.8 ms: 1.04x faster                                            |
| scimark_monte_carlo      | 70.6 ms                                                      | 68.2 ms: 1.03x faster                                            |
| dulwich_log              | 68.3 ms                                                      | 66.1 ms: 1.03x faster                                            |
| meteor_contest           | 130 ms                                                       | 127 ms: 1.03x faster                                             |
| pyflate                  | 453 ms                                                       | 443 ms: 1.02x faster                                             |
| deepcopy_memo            | 37.3 us                                                      | 36.5 us: 1.02x faster                                            |
| pycparser                | 1.28 sec                                                     | 1.27 sec: 1.01x faster                                           |
| 2to3                     | 286 ms                                                       | 284 ms: 1.01x faster                                             |
| spectral_norm            | 94.0 ms                                                      | 94.5 ms: 1.01x slower                                            |
| pathlib                  | 19.1 ms                                                      | 19.3 ms: 1.01x slower                                            |
| crypto_pyaes             | 81.8 ms                                                      | 82.5 ms: 1.01x slower                                            |
| pprint_pformat           | 1.63 sec                                                     | 1.65 sec: 1.01x slower                                           |
| pickle_pure_python       | 318 us                                                       | 325 us: 1.02x slower                                             |
| regex_effbot             | 3.42 ms                                                      | 3.49 ms: 1.02x slower                                            |
| telco                    | 6.91 ms                                                      | 7.11 ms: 1.03x slower                                            |
| pickle                   | 9.77 us                                                      | 10.1 us: 1.03x slower                                            |
| float                    | 76.0 ms                                                      | 78.6 ms: 1.03x slower                                            |
| pprint_safe_repr         | 780 ms                                                       | 809 ms: 1.04x slower                                             |
| pidigits                 | 251 ms                                                       | 261 ms: 1.04x slower                                             |
| pickle_dict              | 31.8 us                                                      | 33.2 us: 1.05x slower                                            |
| regex_dna                | 226 ms                                                       | 237 ms: 1.05x slower                                             |
| xml_etree_process        | 56.1 ms                                                      | 59.0 ms: 1.05x slower                                            |
| create_gc_cycles         | 1.59 ms                                                      | 1.68 ms: 1.05x slower                                            |
| unpickle_list            | 4.47 us                                                      | 4.72 us: 1.06x slower                                            |
| python_startup           | 10.8 ms                                                      | 11.5 ms: 1.06x slower                                            |
| unpack_sequence          | 44.9 ns                                                      | 48.1 ns: 1.07x slower                                            |
| sqlite_synth             | 2.49 us                                                      | 2.68 us: 1.08x slower                                            |
| xml_etree_generate       | 80.5 ms                                                      | 86.8 ms: 1.08x slower                                            |
| scimark_fft              | 281 ms                                                       | 305 ms: 1.08x slower                                             |
| scimark_sparse_mat_mult  | 4.04 ms                                                      | 4.38 ms: 1.09x slower                                            |
| python_startup_no_site   | 7.78 ms                                                      | 8.50 ms: 1.09x slower                                            |
| unpickle                 | 13.2 us                                                      | 14.4 us: 1.09x slower                                            |
| pickle_list              | 3.89 us                                                      | 4.37 us: 1.12x slower                                            |
| async_generators         | 322 ms                                                       | 379 ms: 1.18x slower                                             |
| coverage                 | 66.6 ms                                                      | 88.0 ms: 1.32x slower                                            |
| dask                     | 417 ms                                                       | 551 ms: 1.32x slower                                             |
| bench_mp_pool            | 4.63 ms                                                      | 8.65 ms: 1.87x slower                                            |
| Geometric mean           | (ref)                                                        | 1.06x faster                                                     |

Benchmark hidden because not significant (5): scimark_sor, xml_etree_iterparse, deepcopy_reduce, docutils, mypy2
Ignored benchmarks (21) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 99.75% likely to be faster
- 90% likely to have a speedup of 1.02x
- 95% likely to have a speedup of 1.01x
- 99% likely to have a speedup of 1.00x
