
# Results vs. 3.11.0

- fork: python
- ref: v3.12.0b3
- machine: linux-x86_64
- commit hash: f992a60
- commit date: 2023-06-19
- overall geometric mean: 1.07x faster \*
- HPT reliability: 99.93%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230619-pythonperf2-x86_64-python-v3.12.0b3-3.12.0b3-f992a60 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| 2to3           | 286 ms                                                       | 283 ms: 1.01x faster                                             |
| tornado_http   | 125 ms                                                       | 118 ms: 1.06x faster                                             |
| Geometric mean | (ref)                                                        | 1.02x faster                                                     |

Benchmark hidden because not significant (1): docutils

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230619-pythonperf2-x86_64-python-v3.12.0b3-3.12.0b3-f992a60 |
|-------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| async_tree_memoization  | 648 ms                                                       | 551 ms: 1.18x faster                                             |
| async_tree_none         | 529 ms                                                       | 457 ms: 1.16x faster                                             |
| async_tree_io           | 1.19 sec                                                     | 1.06 sec: 1.13x faster                                           |
| async_tree_cpu_io_mixed | 762 ms                                                       | 704 ms: 1.08x faster                                             |
| Geometric mean          | (ref)                                                        | 1.13x faster                                                     |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230619-pythonperf2-x86_64-python-v3.12.0b3-3.12.0b3-f992a60 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| nbody          | 95.8 ms                                                      | 84.2 ms: 1.14x faster                                            |
| pidigits       | 251 ms                                                       | 260 ms: 1.03x slower                                             |
| float          | 76.0 ms                                                      | 78.8 ms: 1.04x slower                                            |
| Geometric mean | (ref)                                                        | 1.02x faster                                                     |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230619-pythonperf2-x86_64-python-v3.12.0b3-3.12.0b3-f992a60 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| regex_compile  | 157 ms                                                       | 144 ms: 1.09x faster                                             |
| regex_v8       | 23.7 ms                                                      | 23.9 ms: 1.01x slower                                            |
| regex_effbot   | 3.42 ms                                                      | 3.48 ms: 1.02x slower                                            |
| regex_dna      | 226 ms                                                       | 238 ms: 1.05x slower                                             |
| Geometric mean | (ref)                                                        | 1.00x faster                                                     |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230619-pythonperf2-x86_64-python-v3.12.0b3-3.12.0b3-f992a60 |
|----------------------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| json_dumps           | 13.5 ms                                                      | 10.4 ms: 1.29x faster                                            |
| json_loads           | 29.0 us                                                      | 24.7 us: 1.17x faster                                            |
| unpickle_pure_python | 236 us                                                       | 209 us: 1.13x faster                                             |
| xml_etree_parse      | 159 ms                                                       | 150 ms: 1.06x faster                                             |
| tomli_loads          | 2.27 sec                                                     | 2.17 sec: 1.05x faster                                           |
| pickle_pure_python   | 318 us                                                       | 326 us: 1.02x slower                                             |
| xml_etree_process    | 56.1 ms                                                      | 58.2 ms: 1.04x slower                                            |
| unpickle_list        | 4.47 us                                                      | 4.65 us: 1.04x slower                                            |
| pickle               | 9.77 us                                                      | 10.3 us: 1.05x slower                                            |
| xml_etree_generate   | 80.5 ms                                                      | 85.3 ms: 1.06x slower                                            |
| pickle_dict          | 31.8 us                                                      | 33.6 us: 1.06x slower                                            |
| unpickle             | 13.2 us                                                      | 14.6 us: 1.11x slower                                            |
| pickle_list          | 3.89 us                                                      | 4.43 us: 1.14x slower                                            |
| Geometric mean       | (ref)                                                        | 1.01x faster                                                     |

Benchmark hidden because not significant (1): xml_etree_iterparse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230619-pythonperf2-x86_64-python-v3.12.0b3-3.12.0b3-f992a60 |
|------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| python_startup         | 10.8 ms                                                      | 11.4 ms: 1.05x slower                                            |
| python_startup_no_site | 7.78 ms                                                      | 8.43 ms: 1.08x slower                                            |
| Geometric mean         | (ref)                                                        | 1.07x slower                                                     |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230619-pythonperf2-x86_64-python-v3.12.0b3-3.12.0b3-f992a60 |
|-----------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| mako      | 11.0 ms                                                      | 10.0 ms: 1.10x faster                                            |

All benchmarks:
===============

| Benchmark                | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230619-pythonperf2-x86_64-python-v3.12.0b3-3.12.0b3-f992a60 |
|--------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| typing_runtime_protocols | 527 us                                                       | 152 us: 3.47x faster                                             |
| asyncio_tcp              | 752 ms                                                       | 377 ms: 1.99x faster                                             |
| asyncio_tcp_ssl          | 3.09 sec                                                     | 1.56 sec: 1.98x faster                                           |
| generators               | 56.4 ms                                                      | 36.7 ms: 1.54x faster                                            |
| fannkuch                 | 457 ms                                                       | 343 ms: 1.33x faster                                             |
| json_dumps               | 13.5 ms                                                      | 10.4 ms: 1.29x faster                                            |
| richards_super           | 65.2 ms                                                      | 50.8 ms: 1.28x faster                                            |
| deltablue                | 4.03 ms                                                      | 3.21 ms: 1.25x faster                                            |
| coroutines               | 27.9 ms                                                      | 22.4 ms: 1.24x faster                                            |
| hexiom                   | 6.97 ms                                                      | 5.79 ms: 1.20x faster                                            |
| scimark_lu               | 115 ms                                                       | 96.7 ms: 1.19x faster                                            |
| async_tree_memoization   | 648 ms                                                       | 551 ms: 1.18x faster                                             |
| json_loads               | 29.0 us                                                      | 24.7 us: 1.17x faster                                            |
| async_tree_none          | 529 ms                                                       | 457 ms: 1.16x faster                                             |
| comprehensions           | 24.8 us                                                      | 21.7 us: 1.15x faster                                            |
| go                       | 166 ms                                                       | 145 ms: 1.14x faster                                             |
| nbody                    | 95.8 ms                                                      | 84.2 ms: 1.14x faster                                            |
| unpickle_pure_python     | 236 us                                                       | 209 us: 1.13x faster                                             |
| chaos                    | 71.6 ms                                                      | 63.4 ms: 1.13x faster                                            |
| async_tree_io            | 1.19 sec                                                     | 1.06 sec: 1.13x faster                                           |
| sqlglot_parse            | 1.55 ms                                                      | 1.39 ms: 1.12x faster                                            |
| richards                 | 49.9 ms                                                      | 44.7 ms: 1.12x faster                                            |
| logging_silent           | 102 ns                                                       | 91.8 ns: 1.11x faster                                            |
| logging_simple           | 7.21 us                                                      | 6.49 us: 1.11x faster                                            |
| nqueens                  | 99.2 ms                                                      | 90.2 ms: 1.10x faster                                            |
| logging_format           | 7.83 us                                                      | 7.13 us: 1.10x faster                                            |
| mako                     | 11.0 ms                                                      | 10.0 ms: 1.10x faster                                            |
| regex_compile            | 157 ms                                                       | 144 ms: 1.09x faster                                             |
| mdp                      | 2.72 sec                                                     | 2.49 sec: 1.09x faster                                           |
| async_tree_cpu_io_mixed  | 762 ms                                                       | 704 ms: 1.08x faster                                             |
| sqlglot_transpile        | 1.94 ms                                                      | 1.80 ms: 1.08x faster                                            |
| json                     | 5.59 ms                                                      | 5.18 ms: 1.08x faster                                            |
| bench_thread_pool        | 1.02 ms                                                      | 953 us: 1.07x faster                                             |
| xml_etree_parse          | 159 ms                                                       | 150 ms: 1.06x faster                                             |
| tornado_http             | 125 ms                                                       | 118 ms: 1.06x faster                                             |
| sqlglot_normalize        | 122 ms                                                       | 116 ms: 1.05x faster                                             |
| tomli_loads              | 2.27 sec                                                     | 2.17 sec: 1.05x faster                                           |
| meteor_contest           | 130 ms                                                       | 125 ms: 1.04x faster                                             |
| scimark_monte_carlo      | 70.6 ms                                                      | 67.8 ms: 1.04x faster                                            |
| deepcopy                 | 389 us                                                       | 376 us: 1.04x faster                                             |
| dulwich_log              | 68.3 ms                                                      | 66.1 ms: 1.03x faster                                            |
| sqlglot_optimize         | 59.2 ms                                                      | 57.4 ms: 1.03x faster                                            |
| pyflate                  | 453 ms                                                       | 439 ms: 1.03x faster                                             |
| raytrace                 | 308 ms                                                       | 300 ms: 1.03x faster                                             |
| scimark_sor              | 109 ms                                                       | 107 ms: 1.02x faster                                             |
| 2to3                     | 286 ms                                                       | 283 ms: 1.01x faster                                             |
| crypto_pyaes             | 81.8 ms                                                      | 80.9 ms: 1.01x faster                                            |
| spectral_norm            | 94.0 ms                                                      | 93.4 ms: 1.01x faster                                            |
| regex_v8                 | 23.7 ms                                                      | 23.9 ms: 1.01x slower                                            |
| deepcopy_reduce          | 3.37 us                                                      | 3.41 us: 1.01x slower                                            |
| regex_effbot             | 3.42 ms                                                      | 3.48 ms: 1.02x slower                                            |
| telco                    | 6.91 ms                                                      | 7.07 ms: 1.02x slower                                            |
| pprint_safe_repr         | 780 ms                                                       | 799 ms: 1.02x slower                                             |
| pickle_pure_python       | 318 us                                                       | 326 us: 1.02x slower                                             |
| create_gc_cycles         | 1.59 ms                                                      | 1.64 ms: 1.03x slower                                            |
| pidigits                 | 251 ms                                                       | 260 ms: 1.03x slower                                             |
| float                    | 76.0 ms                                                      | 78.8 ms: 1.04x slower                                            |
| xml_etree_process        | 56.1 ms                                                      | 58.2 ms: 1.04x slower                                            |
| unpickle_list            | 4.47 us                                                      | 4.65 us: 1.04x slower                                            |
| regex_dna                | 226 ms                                                       | 238 ms: 1.05x slower                                             |
| python_startup           | 10.8 ms                                                      | 11.4 ms: 1.05x slower                                            |
| pickle                   | 9.77 us                                                      | 10.3 us: 1.05x slower                                            |
| xml_etree_generate       | 80.5 ms                                                      | 85.3 ms: 1.06x slower                                            |
| pickle_dict              | 31.8 us                                                      | 33.6 us: 1.06x slower                                            |
| scimark_fft              | 281 ms                                                       | 304 ms: 1.08x slower                                             |
| python_startup_no_site   | 7.78 ms                                                      | 8.43 ms: 1.08x slower                                            |
| bench_mp_pool            | 4.63 ms                                                      | 5.05 ms: 1.09x slower                                            |
| sqlite_synth             | 2.49 us                                                      | 2.72 us: 1.09x slower                                            |
| scimark_sparse_mat_mult  | 4.04 ms                                                      | 4.43 ms: 1.10x slower                                            |
| unpack_sequence          | 44.9 ns                                                      | 49.4 ns: 1.10x slower                                            |
| unpickle                 | 13.2 us                                                      | 14.6 us: 1.11x slower                                            |
| pickle_list              | 3.89 us                                                      | 4.43 us: 1.14x slower                                            |
| async_generators         | 322 ms                                                       | 382 ms: 1.19x slower                                             |
| coverage                 | 66.6 ms                                                      | 89.0 ms: 1.34x slower                                            |
| dask                     | 417 ms                                                       | 562 ms: 1.35x slower                                             |
| Geometric mean           | (ref)                                                        | 1.07x faster                                                     |

Benchmark hidden because not significant (8): pycparser, pprint_pformat, xml_etree_iterparse, gc_traversal, docutils, deepcopy_memo, pathlib, mypy2
Ignored benchmarks (21) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 99.93% likely to be faster
- 90% likely to have a speedup of 1.02x
- 95% likely to have a speedup of 1.01x
- 99% likely to have a speedup of 1.00x
