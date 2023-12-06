
# Results vs. 3.11.0

- fork: python
- ref: v3.12.0b4
- machine: linux-x86_64
- commit hash: 97a6a41
- commit date: 2023-07-11
- overall geometric mean: 1.07x faster \*
- HPT reliability: 99.94%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230711-pythonperf2-x86_64-python-v3.12.0b4-3.12.0b4-97a6a41 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| 2to3           | 286 ms                                                       | 285 ms: 1.00x faster                                             |
| docutils       | 2.87 sec                                                     | 2.88 sec: 1.00x slower                                           |
| tornado_http   | 125 ms                                                       | 120 ms: 1.04x faster                                             |
| Geometric mean | (ref)                                                        | 1.01x faster                                                     |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230711-pythonperf2-x86_64-python-v3.12.0b4-3.12.0b4-97a6a41 |
|-------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| async_tree_memoization  | 648 ms                                                       | 551 ms: 1.18x faster                                             |
| async_tree_none         | 529 ms                                                       | 458 ms: 1.15x faster                                             |
| async_tree_io           | 1.19 sec                                                     | 1.06 sec: 1.13x faster                                           |
| async_tree_cpu_io_mixed | 762 ms                                                       | 700 ms: 1.09x faster                                             |
| Geometric mean          | (ref)                                                        | 1.14x faster                                                     |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230711-pythonperf2-x86_64-python-v3.12.0b4-3.12.0b4-97a6a41 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| nbody          | 95.8 ms                                                      | 85.5 ms: 1.12x faster                                            |
| float          | 76.0 ms                                                      | 77.8 ms: 1.02x slower                                            |
| pidigits       | 251 ms                                                       | 260 ms: 1.03x slower                                             |
| Geometric mean | (ref)                                                        | 1.02x faster                                                     |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230711-pythonperf2-x86_64-python-v3.12.0b4-3.12.0b4-97a6a41 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| regex_compile  | 157 ms                                                       | 144 ms: 1.09x faster                                             |
| regex_v8       | 23.7 ms                                                      | 23.7 ms: 1.00x slower                                            |
| regex_effbot   | 3.42 ms                                                      | 3.50 ms: 1.03x slower                                            |
| regex_dna      | 226 ms                                                       | 236 ms: 1.04x slower                                             |
| Geometric mean | (ref)                                                        | 1.01x faster                                                     |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230711-pythonperf2-x86_64-python-v3.12.0b4-3.12.0b4-97a6a41 |
|----------------------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| json_dumps           | 13.5 ms                                                      | 10.2 ms: 1.32x faster                                            |
| json_loads           | 29.0 us                                                      | 25.1 us: 1.15x faster                                            |
| unpickle_pure_python | 236 us                                                       | 207 us: 1.14x faster                                             |
| xml_etree_parse      | 159 ms                                                       | 151 ms: 1.05x faster                                             |
| tomli_loads          | 2.27 sec                                                     | 2.18 sec: 1.04x faster                                           |
| xml_etree_process    | 56.1 ms                                                      | 58.2 ms: 1.04x slower                                            |
| pickle_dict          | 31.8 us                                                      | 33.2 us: 1.04x slower                                            |
| xml_etree_generate   | 80.5 ms                                                      | 85.2 ms: 1.06x slower                                            |
| unpickle_list        | 4.47 us                                                      | 4.74 us: 1.06x slower                                            |
| pickle               | 9.77 us                                                      | 10.4 us: 1.07x slower                                            |
| unpickle             | 13.2 us                                                      | 14.6 us: 1.11x slower                                            |
| pickle_list          | 3.89 us                                                      | 4.44 us: 1.14x slower                                            |
| Geometric mean       | (ref)                                                        | 1.01x faster                                                     |

Benchmark hidden because not significant (2): pickle_pure_python, xml_etree_iterparse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230711-pythonperf2-x86_64-python-v3.12.0b4-3.12.0b4-97a6a41 |
|------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| python_startup         | 10.8 ms                                                      | 11.5 ms: 1.06x slower                                            |
| python_startup_no_site | 7.78 ms                                                      | 8.52 ms: 1.09x slower                                            |
| Geometric mean         | (ref)                                                        | 1.08x slower                                                     |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230711-pythonperf2-x86_64-python-v3.12.0b4-3.12.0b4-97a6a41 |
|-----------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| mako      | 11.0 ms                                                      | 9.88 ms: 1.11x faster                                            |

All benchmarks:
===============

| Benchmark                | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230711-pythonperf2-x86_64-python-v3.12.0b4-3.12.0b4-97a6a41 |
|--------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| typing_runtime_protocols | 527 us                                                       | 151 us: 3.48x faster                                             |
| asyncio_tcp_ssl          | 3.09 sec                                                     | 1.57 sec: 1.96x faster                                           |
| asyncio_tcp              | 752 ms                                                       | 383 ms: 1.96x faster                                             |
| generators               | 56.4 ms                                                      | 36.2 ms: 1.56x faster                                            |
| fannkuch                 | 457 ms                                                       | 342 ms: 1.34x faster                                             |
| json_dumps               | 13.5 ms                                                      | 10.2 ms: 1.32x faster                                            |
| richards_super           | 65.2 ms                                                      | 51.0 ms: 1.28x faster                                            |
| deltablue                | 4.03 ms                                                      | 3.19 ms: 1.26x faster                                            |
| mypy2                    | 449 ms                                                       | 366 ms: 1.23x faster                                             |
| scimark_lu               | 115 ms                                                       | 96.5 ms: 1.19x faster                                            |
| hexiom                   | 6.97 ms                                                      | 5.84 ms: 1.19x faster                                            |
| async_tree_memoization   | 648 ms                                                       | 551 ms: 1.18x faster                                             |
| coroutines               | 27.9 ms                                                      | 23.7 ms: 1.17x faster                                            |
| async_tree_none          | 529 ms                                                       | 458 ms: 1.15x faster                                             |
| gc_traversal             | 4.06 ms                                                      | 3.52 ms: 1.15x faster                                            |
| json_loads               | 29.0 us                                                      | 25.1 us: 1.15x faster                                            |
| chaos                    | 71.6 ms                                                      | 62.5 ms: 1.15x faster                                            |
| go                       | 166 ms                                                       | 145 ms: 1.14x faster                                             |
| unpickle_pure_python     | 236 us                                                       | 207 us: 1.14x faster                                             |
| comprehensions           | 24.8 us                                                      | 21.9 us: 1.13x faster                                            |
| async_tree_io            | 1.19 sec                                                     | 1.06 sec: 1.13x faster                                           |
| richards                 | 49.9 ms                                                      | 44.4 ms: 1.12x faster                                            |
| nbody                    | 95.8 ms                                                      | 85.5 ms: 1.12x faster                                            |
| mako                     | 11.0 ms                                                      | 9.88 ms: 1.11x faster                                            |
| sqlglot_parse            | 1.55 ms                                                      | 1.40 ms: 1.11x faster                                            |
| nqueens                  | 99.2 ms                                                      | 89.7 ms: 1.11x faster                                            |
| regex_compile            | 157 ms                                                       | 144 ms: 1.09x faster                                             |
| logging_silent           | 102 ns                                                       | 93.5 ns: 1.09x faster                                            |
| async_tree_cpu_io_mixed  | 762 ms                                                       | 700 ms: 1.09x faster                                             |
| logging_simple           | 7.21 us                                                      | 6.64 us: 1.09x faster                                            |
| sqlglot_transpile        | 1.94 ms                                                      | 1.79 ms: 1.08x faster                                            |
| bench_thread_pool        | 1.02 ms                                                      | 942 us: 1.08x faster                                             |
| mdp                      | 2.72 sec                                                     | 2.51 sec: 1.08x faster                                           |
| json                     | 5.59 ms                                                      | 5.19 ms: 1.08x faster                                            |
| logging_format           | 7.83 us                                                      | 7.31 us: 1.07x faster                                            |
| sqlglot_normalize        | 122 ms                                                       | 115 ms: 1.06x faster                                             |
| xml_etree_parse          | 159 ms                                                       | 151 ms: 1.05x faster                                             |
| deepcopy                 | 389 us                                                       | 372 us: 1.05x faster                                             |
| tornado_http             | 125 ms                                                       | 120 ms: 1.04x faster                                             |
| tomli_loads              | 2.27 sec                                                     | 2.18 sec: 1.04x faster                                           |
| pycparser                | 1.28 sec                                                     | 1.23 sec: 1.04x faster                                           |
| sqlglot_optimize         | 59.2 ms                                                      | 57.4 ms: 1.03x faster                                            |
| deepcopy_memo            | 37.3 us                                                      | 36.2 us: 1.03x faster                                            |
| dulwich_log              | 68.3 ms                                                      | 66.3 ms: 1.03x faster                                            |
| spectral_norm            | 94.0 ms                                                      | 91.5 ms: 1.03x faster                                            |
| raytrace                 | 308 ms                                                       | 300 ms: 1.03x faster                                             |
| meteor_contest           | 130 ms                                                       | 127 ms: 1.02x faster                                             |
| scimark_sor              | 109 ms                                                       | 107 ms: 1.02x faster                                             |
| scimark_monte_carlo      | 70.6 ms                                                      | 69.3 ms: 1.02x faster                                            |
| pprint_pformat           | 1.63 sec                                                     | 1.62 sec: 1.01x faster                                           |
| pathlib                  | 19.1 ms                                                      | 19.0 ms: 1.01x faster                                            |
| crypto_pyaes             | 81.8 ms                                                      | 81.1 ms: 1.01x faster                                            |
| 2to3                     | 286 ms                                                       | 285 ms: 1.00x faster                                             |
| regex_v8                 | 23.7 ms                                                      | 23.7 ms: 1.00x slower                                            |
| docutils                 | 2.87 sec                                                     | 2.88 sec: 1.00x slower                                           |
| pprint_safe_repr         | 780 ms                                                       | 789 ms: 1.01x slower                                             |
| float                    | 76.0 ms                                                      | 77.8 ms: 1.02x slower                                            |
| regex_effbot             | 3.42 ms                                                      | 3.50 ms: 1.03x slower                                            |
| telco                    | 6.91 ms                                                      | 7.13 ms: 1.03x slower                                            |
| pidigits                 | 251 ms                                                       | 260 ms: 1.03x slower                                             |
| create_gc_cycles         | 1.59 ms                                                      | 1.65 ms: 1.04x slower                                            |
| xml_etree_process        | 56.1 ms                                                      | 58.2 ms: 1.04x slower                                            |
| regex_dna                | 226 ms                                                       | 236 ms: 1.04x slower                                             |
| pickle_dict              | 31.8 us                                                      | 33.2 us: 1.04x slower                                            |
| xml_etree_generate       | 80.5 ms                                                      | 85.2 ms: 1.06x slower                                            |
| unpickle_list            | 4.47 us                                                      | 4.74 us: 1.06x slower                                            |
| python_startup           | 10.8 ms                                                      | 11.5 ms: 1.06x slower                                            |
| pickle                   | 9.77 us                                                      | 10.4 us: 1.07x slower                                            |
| scimark_fft              | 281 ms                                                       | 302 ms: 1.07x slower                                             |
| scimark_sparse_mat_mult  | 4.04 ms                                                      | 4.36 ms: 1.08x slower                                            |
| python_startup_no_site   | 7.78 ms                                                      | 8.52 ms: 1.09x slower                                            |
| sqlite_synth             | 2.49 us                                                      | 2.75 us: 1.10x slower                                            |
| unpickle                 | 13.2 us                                                      | 14.6 us: 1.11x slower                                            |
| unpack_sequence          | 44.9 ns                                                      | 50.2 ns: 1.12x slower                                            |
| pickle_list              | 3.89 us                                                      | 4.44 us: 1.14x slower                                            |
| bench_mp_pool            | 4.63 ms                                                      | 5.44 ms: 1.18x slower                                            |
| async_generators         | 322 ms                                                       | 390 ms: 1.21x slower                                             |
| dask                     | 417 ms                                                       | 558 ms: 1.34x slower                                             |
| coverage                 | 66.6 ms                                                      | 91.3 ms: 1.37x slower                                            |
| Geometric mean           | (ref)                                                        | 1.07x faster                                                     |

Benchmark hidden because not significant (4): pickle_pure_python, deepcopy_reduce, xml_etree_iterparse, pyflate
Ignored benchmarks (21) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 99.94% likely to be faster
- 90% likely to have a speedup of 1.02x
- 95% likely to have a speedup of 1.02x
- 99% likely to have a speedup of 1.00x
