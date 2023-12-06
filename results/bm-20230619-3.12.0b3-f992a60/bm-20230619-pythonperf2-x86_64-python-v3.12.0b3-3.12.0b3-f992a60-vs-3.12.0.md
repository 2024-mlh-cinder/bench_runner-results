
# Results vs. 3.12.0

- fork: python
- ref: v3.12.0b3
- machine: linux-x86_64
- commit hash: f992a60
- commit date: 2023-06-19
- overall geometric mean: 1.00x slower \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230619-pythonperf2-x86_64-python-v3.12.0b3-3.12.0b3-f992a60 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| 2to3           | 285 ms                                                       | 283 ms: 1.01x faster                                             |
| docutils       | 2.89 sec                                                     | 2.87 sec: 1.01x faster                                           |
| tornado_http   | 122 ms                                                       | 118 ms: 1.03x faster                                             |
| Geometric mean | (ref)                                                        | 1.02x faster                                                     |

Benchmarks with tag 'asyncio':
==============================

Benchmark hidden because not significant (4): async_tree_memoization, async_tree_none, async_tree_io, async_tree_cpu_io_mixed

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230619-pythonperf2-x86_64-python-v3.12.0b3-3.12.0b3-f992a60 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| nbody          | 88.2 ms                                                      | 84.2 ms: 1.05x faster                                            |
| float          | 81.6 ms                                                      | 78.8 ms: 1.04x faster                                            |
| pidigits       | 264 ms                                                       | 260 ms: 1.02x faster                                             |
| Geometric mean | (ref)                                                        | 1.03x faster                                                     |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230619-pythonperf2-x86_64-python-v3.12.0b3-3.12.0b3-f992a60 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| regex_effbot   | 3.61 ms                                                      | 3.48 ms: 1.04x faster                                            |
| regex_v8       | 24.4 ms                                                      | 23.9 ms: 1.02x faster                                            |
| regex_dna      | 240 ms                                                       | 238 ms: 1.01x faster                                             |
| Geometric mean | (ref)                                                        | 1.02x faster                                                     |

Benchmark hidden because not significant (1): regex_compile

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230619-pythonperf2-x86_64-python-v3.12.0b3-3.12.0b3-f992a60 |
|----------------------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| unpickle             | 15.3 us                                                      | 14.6 us: 1.05x faster                                            |
| unpickle_pure_python | 210 us                                                       | 209 us: 1.00x faster                                             |
| json_dumps           | 10.3 ms                                                      | 10.4 ms: 1.02x slower                                            |
| json_loads           | 24.3 us                                                      | 24.7 us: 1.02x slower                                            |
| xml_etree_parse      | 147 ms                                                       | 150 ms: 1.02x slower                                             |
| pickle_pure_python   | 319 us                                                       | 326 us: 1.02x slower                                             |
| xml_etree_iterparse  | 104 ms                                                       | 106 ms: 1.02x slower                                             |
| pickle               | 10.0 us                                                      | 10.3 us: 1.02x slower                                            |
| pickle_list          | 4.22 us                                                      | 4.43 us: 1.05x slower                                            |
| pickle_dict          | 32.0 us                                                      | 33.6 us: 1.05x slower                                            |
| Geometric mean       | (ref)                                                        | 1.01x slower                                                     |

Benchmark hidden because not significant (4): xml_etree_process, xml_etree_generate, tomli_loads, unpickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230619-pythonperf2-x86_64-python-v3.12.0b3-3.12.0b3-f992a60 |
|------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| python_startup_no_site | 8.67 ms                                                      | 8.43 ms: 1.03x faster                                            |
| python_startup         | 11.7 ms                                                      | 11.4 ms: 1.02x faster                                            |
| Geometric mean         | (ref)                                                        | 1.03x faster                                                     |

Benchmarks with tag 'template':
===============================

Benchmark hidden because not significant (1): mako

All benchmarks:
===============

| Benchmark                | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230619-pythonperf2-x86_64-python-v3.12.0b3-3.12.0b3-f992a60 |
|--------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| unpack_sequence          | 54.5 ns                                                      | 49.4 ns: 1.10x faster                                            |
| fannkuch                 | 362 ms                                                       | 343 ms: 1.06x faster                                             |
| unpickle                 | 15.3 us                                                      | 14.6 us: 1.05x faster                                            |
| nbody                    | 88.2 ms                                                      | 84.2 ms: 1.05x faster                                            |
| regex_effbot             | 3.61 ms                                                      | 3.48 ms: 1.04x faster                                            |
| float                    | 81.6 ms                                                      | 78.8 ms: 1.04x faster                                            |
| tornado_http             | 122 ms                                                       | 118 ms: 1.03x faster                                             |
| hexiom                   | 5.97 ms                                                      | 5.79 ms: 1.03x faster                                            |
| coroutines               | 23.1 ms                                                      | 22.4 ms: 1.03x faster                                            |
| python_startup_no_site   | 8.67 ms                                                      | 8.43 ms: 1.03x faster                                            |
| sqlglot_normalize        | 119 ms                                                       | 116 ms: 1.03x faster                                             |
| scimark_monte_carlo      | 69.5 ms                                                      | 67.8 ms: 1.03x faster                                            |
| python_startup           | 11.7 ms                                                      | 11.4 ms: 1.02x faster                                            |
| mdp                      | 2.56 sec                                                     | 2.49 sec: 1.02x faster                                           |
| go                       | 149 ms                                                       | 145 ms: 1.02x faster                                             |
| logging_simple           | 6.64 us                                                      | 6.49 us: 1.02x faster                                            |
| logging_format           | 7.29 us                                                      | 7.13 us: 1.02x faster                                            |
| regex_v8                 | 24.4 ms                                                      | 23.9 ms: 1.02x faster                                            |
| crypto_pyaes             | 82.4 ms                                                      | 80.9 ms: 1.02x faster                                            |
| scimark_lu               | 98.6 ms                                                      | 96.7 ms: 1.02x faster                                            |
| pidigits                 | 264 ms                                                       | 260 ms: 1.02x faster                                             |
| sqlglot_optimize         | 58.4 ms                                                      | 57.4 ms: 1.02x faster                                            |
| generators               | 37.3 ms                                                      | 36.7 ms: 1.02x faster                                            |
| pycparser                | 1.29 sec                                                     | 1.27 sec: 1.02x faster                                           |
| logging_silent           | 93.3 ns                                                      | 91.8 ns: 1.02x faster                                            |
| sqlglot_parse            | 1.41 ms                                                      | 1.39 ms: 1.01x faster                                            |
| meteor_contest           | 126 ms                                                       | 125 ms: 1.01x faster                                             |
| scimark_sparse_mat_mult  | 4.49 ms                                                      | 4.43 ms: 1.01x faster                                            |
| telco                    | 7.16 ms                                                      | 7.07 ms: 1.01x faster                                            |
| pprint_safe_repr         | 808 ms                                                       | 799 ms: 1.01x faster                                             |
| chaos                    | 64.1 ms                                                      | 63.4 ms: 1.01x faster                                            |
| pprint_pformat           | 1.64 sec                                                     | 1.63 sec: 1.01x faster                                           |
| async_generators         | 385 ms                                                       | 382 ms: 1.01x faster                                             |
| regex_dna                | 240 ms                                                       | 238 ms: 1.01x faster                                             |
| deltablue                | 3.24 ms                                                      | 3.21 ms: 1.01x faster                                            |
| docutils                 | 2.89 sec                                                     | 2.87 sec: 1.01x faster                                           |
| pyflate                  | 442 ms                                                       | 439 ms: 1.01x faster                                             |
| 2to3                     | 285 ms                                                       | 283 ms: 1.01x faster                                             |
| asyncio_tcp              | 380 ms                                                       | 377 ms: 1.01x faster                                             |
| comprehensions           | 21.8 us                                                      | 21.7 us: 1.01x faster                                            |
| asyncio_tcp_ssl          | 1.57 sec                                                     | 1.56 sec: 1.01x faster                                           |
| spectral_norm            | 93.9 ms                                                      | 93.4 ms: 1.01x faster                                            |
| raytrace                 | 301 ms                                                       | 300 ms: 1.00x faster                                             |
| unpickle_pure_python     | 210 us                                                       | 209 us: 1.00x faster                                             |
| typing_runtime_protocols | 150 us                                                       | 152 us: 1.01x slower                                             |
| deepcopy                 | 371 us                                                       | 376 us: 1.01x slower                                             |
| json_dumps               | 10.3 ms                                                      | 10.4 ms: 1.02x slower                                            |
| dulwich_log              | 64.9 ms                                                      | 66.1 ms: 1.02x slower                                            |
| json_loads               | 24.3 us                                                      | 24.7 us: 1.02x slower                                            |
| xml_etree_parse          | 147 ms                                                       | 150 ms: 1.02x slower                                             |
| pickle_pure_python       | 319 us                                                       | 326 us: 1.02x slower                                             |
| deepcopy_memo            | 36.6 us                                                      | 37.4 us: 1.02x slower                                            |
| xml_etree_iterparse      | 104 ms                                                       | 106 ms: 1.02x slower                                             |
| pathlib                  | 18.7 ms                                                      | 19.2 ms: 1.02x slower                                            |
| pickle                   | 10.0 us                                                      | 10.3 us: 1.02x slower                                            |
| create_gc_cycles         | 1.58 ms                                                      | 1.64 ms: 1.04x slower                                            |
| pickle_list              | 4.22 us                                                      | 4.43 us: 1.05x slower                                            |
| pickle_dict              | 32.0 us                                                      | 33.6 us: 1.05x slower                                            |
| gc_traversal             | 3.70 ms                                                      | 4.06 ms: 1.10x slower                                            |
| mypy2                    | 365 ms                                                       | 455 ms: 1.25x slower                                             |
| coverage                 | 66.3 ms                                                      | 89.0 ms: 1.34x slower                                            |
| dask                     | 394 ms                                                       | 562 ms: 1.43x slower                                             |
| Geometric mean           | (ref)                                                        | 1.00x slower                                                     |

Benchmark hidden because not significant (21): richards, async_tree_memoization, sqlglot_transpile, regex_compile, async_tree_none, bench_thread_pool, mako, xml_etree_process, richards_super, xml_etree_generate, async_tree_io, tomli_loads, deepcopy_reduce, async_tree_cpu_io_mixed, sqlite_synth, unpickle_list, scimark_sor, json, nqueens, scimark_fft, bench_mp_pool
Ignored benchmarks (15) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
