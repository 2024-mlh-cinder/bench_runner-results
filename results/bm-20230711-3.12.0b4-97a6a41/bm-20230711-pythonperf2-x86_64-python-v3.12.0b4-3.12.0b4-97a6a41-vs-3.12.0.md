
# Results vs. 3.12.0

- fork: python
- ref: v3.12.0b4
- machine: linux-x86_64
- commit hash: 97a6a41
- commit date: 2023-07-11
- overall geometric mean: 1.00x slower \*
- HPT reliability: 99.91%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230711-pythonperf2-x86_64-python-v3.12.0b4-3.12.0b4-97a6a41 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| docutils       | 2.89 sec                                                     | 2.88 sec: 1.00x faster                                           |
| tornado_http   | 122 ms                                                       | 120 ms: 1.02x faster                                             |
| Geometric mean | (ref)                                                        | 1.01x faster                                                     |

Benchmark hidden because not significant (1): 2to3

Benchmarks with tag 'asyncio':
==============================

Benchmark hidden because not significant (4): async_tree_cpu_io_mixed, async_tree_memoization, async_tree_none, async_tree_io

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230711-pythonperf2-x86_64-python-v3.12.0b4-3.12.0b4-97a6a41 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| float          | 81.6 ms                                                      | 77.8 ms: 1.05x faster                                            |
| pidigits       | 264 ms                                                       | 260 ms: 1.02x faster                                             |
| Geometric mean | (ref)                                                        | 1.03x faster                                                     |

Benchmark hidden because not significant (1): nbody

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230711-pythonperf2-x86_64-python-v3.12.0b4-3.12.0b4-97a6a41 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| regex_effbot   | 3.61 ms                                                      | 3.50 ms: 1.03x faster                                            |
| regex_v8       | 24.4 ms                                                      | 23.7 ms: 1.03x faster                                            |
| regex_dna      | 240 ms                                                       | 236 ms: 1.02x faster                                             |
| regex_compile  | 145 ms                                                       | 144 ms: 1.01x faster                                             |
| Geometric mean | (ref)                                                        | 1.02x faster                                                     |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230711-pythonperf2-x86_64-python-v3.12.0b4-3.12.0b4-97a6a41 |
|----------------------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| unpickle             | 15.3 us                                                      | 14.6 us: 1.05x faster                                            |
| unpickle_pure_python | 210 us                                                       | 207 us: 1.01x faster                                             |
| json_dumps           | 10.3 ms                                                      | 10.2 ms: 1.00x faster                                            |
| unpickle_list        | 4.65 us                                                      | 4.74 us: 1.02x slower                                            |
| xml_etree_iterparse  | 104 ms                                                       | 107 ms: 1.03x slower                                             |
| xml_etree_parse      | 147 ms                                                       | 151 ms: 1.03x slower                                             |
| json_loads           | 24.3 us                                                      | 25.1 us: 1.03x slower                                            |
| pickle_dict          | 32.0 us                                                      | 33.2 us: 1.04x slower                                            |
| pickle               | 10.0 us                                                      | 10.4 us: 1.04x slower                                            |
| pickle_list          | 4.22 us                                                      | 4.44 us: 1.05x slower                                            |
| Geometric mean       | (ref)                                                        | 1.01x slower                                                     |

Benchmark hidden because not significant (4): xml_etree_process, pickle_pure_python, xml_etree_generate, tomli_loads

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230711-pythonperf2-x86_64-python-v3.12.0b4-3.12.0b4-97a6a41 |
|------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| python_startup_no_site | 8.67 ms                                                      | 8.52 ms: 1.02x faster                                            |
| python_startup         | 11.7 ms                                                      | 11.5 ms: 1.01x faster                                            |
| Geometric mean         | (ref)                                                        | 1.02x faster                                                     |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230711-pythonperf2-x86_64-python-v3.12.0b4-3.12.0b4-97a6a41 |
|-----------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| mako      | 10.1 ms                                                      | 9.88 ms: 1.02x faster                                            |

All benchmarks:
===============

| Benchmark                | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230711-pythonperf2-x86_64-python-v3.12.0b4-3.12.0b4-97a6a41 |
|--------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| unpack_sequence          | 54.5 ns                                                      | 50.2 ns: 1.09x faster                                            |
| fannkuch                 | 362 ms                                                       | 342 ms: 1.06x faster                                             |
| gc_traversal             | 3.70 ms                                                      | 3.52 ms: 1.05x faster                                            |
| float                    | 81.6 ms                                                      | 77.8 ms: 1.05x faster                                            |
| pycparser                | 1.29 sec                                                     | 1.23 sec: 1.05x faster                                           |
| unpickle                 | 15.3 us                                                      | 14.6 us: 1.05x faster                                            |
| sqlglot_normalize        | 119 ms                                                       | 115 ms: 1.03x faster                                             |
| generators               | 37.3 ms                                                      | 36.2 ms: 1.03x faster                                            |
| regex_effbot             | 3.61 ms                                                      | 3.50 ms: 1.03x faster                                            |
| scimark_sparse_mat_mult  | 4.49 ms                                                      | 4.36 ms: 1.03x faster                                            |
| regex_v8                 | 24.4 ms                                                      | 23.7 ms: 1.03x faster                                            |
| spectral_norm            | 93.9 ms                                                      | 91.5 ms: 1.03x faster                                            |
| chaos                    | 64.1 ms                                                      | 62.5 ms: 1.03x faster                                            |
| go                       | 149 ms                                                       | 145 ms: 1.02x faster                                             |
| pprint_safe_repr         | 808 ms                                                       | 789 ms: 1.02x faster                                             |
| scimark_lu               | 98.6 ms                                                      | 96.5 ms: 1.02x faster                                            |
| hexiom                   | 5.97 ms                                                      | 5.84 ms: 1.02x faster                                            |
| mako                     | 10.1 ms                                                      | 9.88 ms: 1.02x faster                                            |
| regex_dna                | 240 ms                                                       | 236 ms: 1.02x faster                                             |
| tornado_http             | 122 ms                                                       | 120 ms: 1.02x faster                                             |
| pidigits                 | 264 ms                                                       | 260 ms: 1.02x faster                                             |
| pprint_pformat           | 1.64 sec                                                     | 1.62 sec: 1.02x faster                                           |
| python_startup_no_site   | 8.67 ms                                                      | 8.52 ms: 1.02x faster                                            |
| deltablue                | 3.24 ms                                                      | 3.19 ms: 1.02x faster                                            |
| mdp                      | 2.56 sec                                                     | 2.51 sec: 1.02x faster                                           |
| sqlglot_optimize         | 58.4 ms                                                      | 57.4 ms: 1.02x faster                                            |
| crypto_pyaes             | 82.4 ms                                                      | 81.1 ms: 1.02x faster                                            |
| richards                 | 45.1 ms                                                      | 44.4 ms: 1.02x faster                                            |
| python_startup           | 11.7 ms                                                      | 11.5 ms: 1.01x faster                                            |
| unpickle_pure_python     | 210 us                                                       | 207 us: 1.01x faster                                             |
| deepcopy_memo            | 36.6 us                                                      | 36.2 us: 1.01x faster                                            |
| sqlglot_parse            | 1.41 ms                                                      | 1.40 ms: 1.01x faster                                            |
| deepcopy_reduce          | 3.41 us                                                      | 3.38 us: 1.01x faster                                            |
| sqlglot_transpile        | 1.80 ms                                                      | 1.79 ms: 1.01x faster                                            |
| regex_compile            | 145 ms                                                       | 144 ms: 1.01x faster                                             |
| docutils                 | 2.89 sec                                                     | 2.88 sec: 1.00x faster                                           |
| nqueens                  | 90.1 ms                                                      | 89.7 ms: 1.00x faster                                            |
| json_dumps               | 10.3 ms                                                      | 10.2 ms: 1.00x faster                                            |
| scimark_monte_carlo      | 69.5 ms                                                      | 69.3 ms: 1.00x faster                                            |
| mypy2                    | 365 ms                                                       | 366 ms: 1.00x slower                                             |
| comprehensions           | 21.8 us                                                      | 21.9 us: 1.01x slower                                            |
| meteor_contest           | 126 ms                                                       | 127 ms: 1.01x slower                                             |
| typing_runtime_protocols | 150 us                                                       | 151 us: 1.01x slower                                             |
| asyncio_tcp              | 380 ms                                                       | 383 ms: 1.01x slower                                             |
| sqlite_synth             | 2.72 us                                                      | 2.75 us: 1.01x slower                                            |
| pathlib                  | 18.7 ms                                                      | 19.0 ms: 1.01x slower                                            |
| async_generators         | 385 ms                                                       | 390 ms: 1.01x slower                                             |
| unpickle_list            | 4.65 us                                                      | 4.74 us: 1.02x slower                                            |
| dulwich_log              | 64.9 ms                                                      | 66.3 ms: 1.02x slower                                            |
| coroutines               | 23.1 ms                                                      | 23.7 ms: 1.03x slower                                            |
| xml_etree_iterparse      | 104 ms                                                       | 107 ms: 1.03x slower                                             |
| xml_etree_parse          | 147 ms                                                       | 151 ms: 1.03x slower                                             |
| pyflate                  | 442 ms                                                       | 457 ms: 1.03x slower                                             |
| json_loads               | 24.3 us                                                      | 25.1 us: 1.03x slower                                            |
| pickle_dict              | 32.0 us                                                      | 33.2 us: 1.04x slower                                            |
| pickle                   | 10.0 us                                                      | 10.4 us: 1.04x slower                                            |
| create_gc_cycles         | 1.58 ms                                                      | 1.65 ms: 1.05x slower                                            |
| pickle_list              | 4.22 us                                                      | 4.44 us: 1.05x slower                                            |
| bench_mp_pool            | 4.96 ms                                                      | 5.44 ms: 1.10x slower                                            |
| coverage                 | 66.3 ms                                                      | 91.3 ms: 1.38x slower                                            |
| dask                     | 394 ms                                                       | 558 ms: 1.42x slower                                             |
| Geometric mean           | (ref)                                                        | 1.00x slower                                                     |

Benchmark hidden because not significant (22): nbody, bench_thread_pool, async_tree_cpu_io_mixed, scimark_fft, async_tree_memoization, telco, xml_etree_process, async_tree_none, raytrace, pickle_pure_python, async_tree_io, xml_etree_generate, 2to3, asyncio_tcp_ssl, logging_simple, logging_format, logging_silent, deepcopy, scimark_sor, json, richards_super, tomli_loads
Ignored benchmarks (15) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum


# HPT report

- Reliability score: 99.91% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
