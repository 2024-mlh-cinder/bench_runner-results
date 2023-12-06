
# Results vs. 3.11.0

- fork: python
- ref: v3.12.0b2
- machine: linux-x86_64
- commit hash: e6c0efa
- commit date: 2023-06-06
- overall geometric mean: 1.07x faster \*
- HPT reliability: 99.98%
- HPT 99th percentile: 1.01x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230606-pythonperf2-x86_64-python-v3.12.0b2-3.12.0b2-e6c0efa |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| 2to3           | 286 ms                                                       | 285 ms: 1.00x faster                                             |
| docutils       | 2.87 sec                                                     | 2.88 sec: 1.00x slower                                           |
| tornado_http   | 125 ms                                                       | 121 ms: 1.04x faster                                             |
| Geometric mean | (ref)                                                        | 1.01x faster                                                     |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230606-pythonperf2-x86_64-python-v3.12.0b2-3.12.0b2-e6c0efa |
|-------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| async_tree_memoization  | 648 ms                                                       | 546 ms: 1.19x faster                                             |
| async_tree_none         | 529 ms                                                       | 452 ms: 1.17x faster                                             |
| async_tree_io           | 1.19 sec                                                     | 1.04 sec: 1.14x faster                                           |
| async_tree_cpu_io_mixed | 762 ms                                                       | 697 ms: 1.09x faster                                             |
| Geometric mean          | (ref)                                                        | 1.15x faster                                                     |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230606-pythonperf2-x86_64-python-v3.12.0b2-3.12.0b2-e6c0efa |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| nbody          | 95.8 ms                                                      | 83.7 ms: 1.14x faster                                            |
| float          | 76.0 ms                                                      | 77.3 ms: 1.02x slower                                            |
| pidigits       | 251 ms                                                       | 259 ms: 1.03x slower                                             |
| Geometric mean | (ref)                                                        | 1.03x faster                                                     |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230606-pythonperf2-x86_64-python-v3.12.0b2-3.12.0b2-e6c0efa |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| regex_compile  | 157 ms                                                       | 144 ms: 1.09x faster                                             |
| regex_v8       | 23.7 ms                                                      | 23.6 ms: 1.00x faster                                            |
| regex_effbot   | 3.42 ms                                                      | 3.55 ms: 1.04x slower                                            |
| regex_dna      | 226 ms                                                       | 245 ms: 1.08x slower                                             |
| Geometric mean | (ref)                                                        | 1.01x slower                                                     |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230606-pythonperf2-x86_64-python-v3.12.0b2-3.12.0b2-e6c0efa |
|----------------------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| json_dumps           | 13.5 ms                                                      | 10.2 ms: 1.32x faster                                            |
| json_loads           | 29.0 us                                                      | 24.5 us: 1.18x faster                                            |
| unpickle_pure_python | 236 us                                                       | 205 us: 1.15x faster                                             |
| xml_etree_parse      | 159 ms                                                       | 148 ms: 1.07x faster                                             |
| tomli_loads          | 2.27 sec                                                     | 2.19 sec: 1.04x faster                                           |
| xml_etree_iterparse  | 106 ms                                                       | 104 ms: 1.02x faster                                             |
| pickle_dict          | 31.8 us                                                      | 31.2 us: 1.02x faster                                            |
| pickle_pure_python   | 318 us                                                       | 324 us: 1.02x slower                                             |
| pickle               | 9.77 us                                                      | 10.0 us: 1.03x slower                                            |
| xml_etree_process    | 56.1 ms                                                      | 58.8 ms: 1.05x slower                                            |
| unpickle_list        | 4.47 us                                                      | 4.71 us: 1.05x slower                                            |
| xml_etree_generate   | 80.5 ms                                                      | 85.6 ms: 1.06x slower                                            |
| pickle_list          | 3.89 us                                                      | 4.27 us: 1.10x slower                                            |
| unpickle             | 13.2 us                                                      | 14.6 us: 1.11x slower                                            |
| Geometric mean       | (ref)                                                        | 1.02x faster                                                     |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230606-pythonperf2-x86_64-python-v3.12.0b2-3.12.0b2-e6c0efa |
|------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| python_startup         | 10.8 ms                                                      | 11.4 ms: 1.06x slower                                            |
| python_startup_no_site | 7.78 ms                                                      | 8.45 ms: 1.09x slower                                            |
| Geometric mean         | (ref)                                                        | 1.07x slower                                                     |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230606-pythonperf2-x86_64-python-v3.12.0b2-3.12.0b2-e6c0efa |
|-----------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| mako      | 11.0 ms                                                      | 9.93 ms: 1.11x faster                                            |

All benchmarks:
===============

| Benchmark                | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230606-pythonperf2-x86_64-python-v3.12.0b2-3.12.0b2-e6c0efa |
|--------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| typing_runtime_protocols | 527 us                                                       | 150 us: 3.51x faster                                             |
| asyncio_tcp              | 752 ms                                                       | 379 ms: 1.98x faster                                             |
| asyncio_tcp_ssl          | 3.09 sec                                                     | 1.57 sec: 1.97x faster                                           |
| generators               | 56.4 ms                                                      | 35.5 ms: 1.59x faster                                            |
| fannkuch                 | 457 ms                                                       | 343 ms: 1.33x faster                                             |
| json_dumps               | 13.5 ms                                                      | 10.2 ms: 1.32x faster                                            |
| richards_super           | 65.2 ms                                                      | 51.0 ms: 1.28x faster                                            |
| coroutines               | 27.9 ms                                                      | 22.3 ms: 1.25x faster                                            |
| deltablue                | 4.03 ms                                                      | 3.25 ms: 1.24x faster                                            |
| scimark_lu               | 115 ms                                                       | 96.3 ms: 1.20x faster                                            |
| async_tree_memoization   | 648 ms                                                       | 546 ms: 1.19x faster                                             |
| json_loads               | 29.0 us                                                      | 24.5 us: 1.18x faster                                            |
| hexiom                   | 6.97 ms                                                      | 5.95 ms: 1.17x faster                                            |
| async_tree_none          | 529 ms                                                       | 452 ms: 1.17x faster                                             |
| unpickle_pure_python     | 236 us                                                       | 205 us: 1.15x faster                                             |
| comprehensions           | 24.8 us                                                      | 21.6 us: 1.15x faster                                            |
| nbody                    | 95.8 ms                                                      | 83.7 ms: 1.14x faster                                            |
| async_tree_io            | 1.19 sec                                                     | 1.04 sec: 1.14x faster                                           |
| go                       | 166 ms                                                       | 147 ms: 1.13x faster                                             |
| chaos                    | 71.6 ms                                                      | 63.6 ms: 1.13x faster                                            |
| sqlglot_parse            | 1.55 ms                                                      | 1.40 ms: 1.11x faster                                            |
| nqueens                  | 99.2 ms                                                      | 89.5 ms: 1.11x faster                                            |
| mako                     | 11.0 ms                                                      | 9.93 ms: 1.11x faster                                            |
| richards                 | 49.9 ms                                                      | 45.5 ms: 1.10x faster                                            |
| async_tree_cpu_io_mixed  | 762 ms                                                       | 697 ms: 1.09x faster                                             |
| logging_silent           | 102 ns                                                       | 93.8 ns: 1.09x faster                                            |
| regex_compile            | 157 ms                                                       | 144 ms: 1.09x faster                                             |
| mdp                      | 2.72 sec                                                     | 2.51 sec: 1.08x faster                                           |
| sqlglot_transpile        | 1.94 ms                                                      | 1.80 ms: 1.08x faster                                            |
| json                     | 5.59 ms                                                      | 5.19 ms: 1.08x faster                                            |
| logging_simple           | 7.21 us                                                      | 6.73 us: 1.07x faster                                            |
| gc_traversal             | 4.06 ms                                                      | 3.79 ms: 1.07x faster                                            |
| xml_etree_parse          | 159 ms                                                       | 148 ms: 1.07x faster                                             |
| logging_format           | 7.83 us                                                      | 7.35 us: 1.06x faster                                            |
| bench_thread_pool        | 1.02 ms                                                      | 960 us: 1.06x faster                                             |
| deepcopy                 | 389 us                                                       | 369 us: 1.06x faster                                             |
| sqlglot_normalize        | 122 ms                                                       | 116 ms: 1.05x faster                                             |
| tomli_loads              | 2.27 sec                                                     | 2.19 sec: 1.04x faster                                           |
| deepcopy_memo            | 37.3 us                                                      | 36.0 us: 1.04x faster                                            |
| tornado_http             | 125 ms                                                       | 121 ms: 1.04x faster                                             |
| dulwich_log              | 68.3 ms                                                      | 65.9 ms: 1.04x faster                                            |
| pycparser                | 1.28 sec                                                     | 1.24 sec: 1.03x faster                                           |
| sqlglot_optimize         | 59.2 ms                                                      | 57.5 ms: 1.03x faster                                            |
| spectral_norm            | 94.0 ms                                                      | 91.6 ms: 1.03x faster                                            |
| pyflate                  | 453 ms                                                       | 441 ms: 1.03x faster                                             |
| scimark_sor              | 109 ms                                                       | 107 ms: 1.02x faster                                             |
| xml_etree_iterparse      | 106 ms                                                       | 104 ms: 1.02x faster                                             |
| meteor_contest           | 130 ms                                                       | 127 ms: 1.02x faster                                             |
| scimark_monte_carlo      | 70.6 ms                                                      | 69.2 ms: 1.02x faster                                            |
| pickle_dict              | 31.8 us                                                      | 31.2 us: 1.02x faster                                            |
| pprint_pformat           | 1.63 sec                                                     | 1.62 sec: 1.01x faster                                           |
| crypto_pyaes             | 81.8 ms                                                      | 81.2 ms: 1.01x faster                                            |
| 2to3                     | 286 ms                                                       | 285 ms: 1.00x faster                                             |
| regex_v8                 | 23.7 ms                                                      | 23.6 ms: 1.00x faster                                            |
| docutils                 | 2.87 sec                                                     | 2.88 sec: 1.00x slower                                           |
| pathlib                  | 19.1 ms                                                      | 19.3 ms: 1.01x slower                                            |
| deepcopy_reduce          | 3.37 us                                                      | 3.40 us: 1.01x slower                                            |
| pprint_safe_repr         | 780 ms                                                       | 792 ms: 1.02x slower                                             |
| pickle_pure_python       | 318 us                                                       | 324 us: 1.02x slower                                             |
| float                    | 76.0 ms                                                      | 77.3 ms: 1.02x slower                                            |
| create_gc_cycles         | 1.59 ms                                                      | 1.62 ms: 1.02x slower                                            |
| telco                    | 6.91 ms                                                      | 7.08 ms: 1.03x slower                                            |
| pickle                   | 9.77 us                                                      | 10.0 us: 1.03x slower                                            |
| pidigits                 | 251 ms                                                       | 259 ms: 1.03x slower                                             |
| regex_effbot             | 3.42 ms                                                      | 3.55 ms: 1.04x slower                                            |
| xml_etree_process        | 56.1 ms                                                      | 58.8 ms: 1.05x slower                                            |
| unpickle_list            | 4.47 us                                                      | 4.71 us: 1.05x slower                                            |
| scimark_fft              | 281 ms                                                       | 296 ms: 1.05x slower                                             |
| python_startup           | 10.8 ms                                                      | 11.4 ms: 1.06x slower                                            |
| xml_etree_generate       | 80.5 ms                                                      | 85.6 ms: 1.06x slower                                            |
| scimark_sparse_mat_mult  | 4.04 ms                                                      | 4.29 ms: 1.06x slower                                            |
| regex_dna                | 226 ms                                                       | 245 ms: 1.08x slower                                             |
| python_startup_no_site   | 7.78 ms                                                      | 8.45 ms: 1.09x slower                                            |
| sqlite_synth             | 2.49 us                                                      | 2.71 us: 1.09x slower                                            |
| pickle_list              | 3.89 us                                                      | 4.27 us: 1.10x slower                                            |
| unpickle                 | 13.2 us                                                      | 14.6 us: 1.11x slower                                            |
| unpack_sequence          | 44.9 ns                                                      | 49.8 ns: 1.11x slower                                            |
| bench_mp_pool            | 4.63 ms                                                      | 5.41 ms: 1.17x slower                                            |
| async_generators         | 322 ms                                                       | 389 ms: 1.21x slower                                             |
| coverage                 | 66.6 ms                                                      | 88.5 ms: 1.33x slower                                            |
| dask                     | 417 ms                                                       | 563 ms: 1.35x slower                                             |
| Geometric mean           | (ref)                                                        | 1.07x faster                                                     |

Benchmark hidden because not significant (2): raytrace, mypy2
Ignored benchmarks (21) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 99.98% likely to be faster
- 90% likely to have a speedup of 1.02x
- 95% likely to have a speedup of 1.02x
- 99% likely to have a speedup of 1.01x
