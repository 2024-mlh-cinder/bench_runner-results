
# Results vs. 3.12.0

- fork: python
- ref: v3.11.6
- machine: linux-x86_64
- commit hash: 8b6ee5b
- commit date: 2023-10-02
- overall geometric mean: 1.06x slower
- HPT reliability: 99.68%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231002-pythonperf2-x86_64-python-v3.11.6-3.11.6-8b6ee5b |
|----------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| 2to3           | 287 ms                                                       | 285 ms: 1.01x faster                                         |
| docutils       | 2.89 sec                                                     | 2.83 sec: 1.02x faster                                       |
| Geometric mean | (ref)                                                        | 1.01x faster                                                 |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231002-pythonperf2-x86_64-python-v3.11.6-3.11.6-8b6ee5b |
|----------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| float          | 78.5 ms                                                      | 76.4 ms: 1.03x faster                                        |
| pidigits       | 264 ms                                                       | 268 ms: 1.02x slower                                         |
| nbody          | 94.1 ms                                                      | 96.9 ms: 1.03x slower                                        |
| Geometric mean | (ref)                                                        | 1.01x slower                                                 |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231002-pythonperf2-x86_64-python-v3.11.6-3.11.6-8b6ee5b |
|----------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| regex_dna      | 241 ms                                                       | 220 ms: 1.10x faster                                         |
| regex_v8       | 25.0 ms                                                      | 23.2 ms: 1.08x faster                                        |
| regex_effbot   | 3.47 ms                                                      | 3.29 ms: 1.06x faster                                        |
| regex_compile  | 146 ms                                                       | 157 ms: 1.08x slower                                         |
| Geometric mean | (ref)                                                        | 1.04x faster                                                 |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231002-pythonperf2-x86_64-python-v3.11.6-3.11.6-8b6ee5b |
|----------------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| pickle_list          | 4.39 us                                                      | 3.77 us: 1.16x faster                                        |
| unpickle             | 14.8 us                                                      | 13.3 us: 1.11x faster                                        |
| xml_etree_generate   | 86.1 ms                                                      | 79.8 ms: 1.08x faster                                        |
| xml_etree_process    | 58.3 ms                                                      | 55.8 ms: 1.04x faster                                        |
| pickle_pure_python   | 323 us                                                       | 315 us: 1.03x faster                                         |
| unpickle_list        | 4.77 us                                                      | 4.69 us: 1.02x faster                                        |
| pickle               | 10.1 us                                                      | 9.99 us: 1.01x faster                                        |
| pickle_dict          | 31.7 us                                                      | 32.1 us: 1.01x slower                                        |
| json_loads           | 24.3 us                                                      | 24.6 us: 1.01x slower                                        |
| xml_etree_iterparse  | 103 ms                                                       | 105 ms: 1.02x slower                                         |
| tomli_loads          | 2.20 sec                                                     | 2.28 sec: 1.04x slower                                       |
| xml_etree_parse      | 146 ms                                                       | 159 ms: 1.09x slower                                         |
| unpickle_pure_python | 207 us                                                       | 239 us: 1.15x slower                                         |
| json_dumps           | 10.2 ms                                                      | 13.3 ms: 1.30x slower                                        |
| Geometric mean       | (ref)                                                        | 1.01x slower                                                 |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231002-pythonperf2-x86_64-python-v3.11.6-3.11.6-8b6ee5b |
|------------------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| python_startup_no_site | 8.70 ms                                                      | 7.81 ms: 1.11x faster                                        |
| python_startup         | 11.7 ms                                                      | 10.8 ms: 1.08x faster                                        |
| Geometric mean         | (ref)                                                        | 1.10x faster                                                 |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231002-pythonperf2-x86_64-python-v3.11.6-3.11.6-8b6ee5b |
|-----------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| mako      | 9.94 ms                                                      | 10.8 ms: 1.09x slower                                        |

All benchmarks:
===============

| Benchmark                | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231002-pythonperf2-x86_64-python-v3.11.6-3.11.6-8b6ee5b |
|--------------------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| async_generators         | 385 ms                                                       | 316 ms: 1.22x faster                                         |
| unpack_sequence          | 53.3 ns                                                      | 45.6 ns: 1.17x faster                                        |
| pickle_list              | 4.39 us                                                      | 3.77 us: 1.16x faster                                        |
| python_startup_no_site   | 8.70 ms                                                      | 7.81 ms: 1.11x faster                                        |
| unpickle                 | 14.8 us                                                      | 13.3 us: 1.11x faster                                        |
| bench_mp_pool            | 5.34 ms                                                      | 4.82 ms: 1.11x faster                                        |
| regex_dna                | 241 ms                                                       | 220 ms: 1.10x faster                                         |
| python_startup           | 11.7 ms                                                      | 10.8 ms: 1.08x faster                                        |
| xml_etree_generate       | 86.1 ms                                                      | 79.8 ms: 1.08x faster                                        |
| sqlite_synth             | 2.70 us                                                      | 2.50 us: 1.08x faster                                        |
| regex_v8                 | 25.0 ms                                                      | 23.2 ms: 1.08x faster                                        |
| scimark_sparse_mat_mult  | 4.42 ms                                                      | 4.11 ms: 1.08x faster                                        |
| pprint_safe_repr         | 823 ms                                                       | 775 ms: 1.06x faster                                         |
| scimark_fft              | 304 ms                                                       | 286 ms: 1.06x faster                                         |
| scimark_monte_carlo      | 72.4 ms                                                      | 68.3 ms: 1.06x faster                                        |
| regex_effbot             | 3.47 ms                                                      | 3.29 ms: 1.06x faster                                        |
| xml_etree_process        | 58.3 ms                                                      | 55.8 ms: 1.04x faster                                        |
| create_gc_cycles         | 1.67 ms                                                      | 1.61 ms: 1.04x faster                                        |
| pprint_pformat           | 1.67 sec                                                     | 1.61 sec: 1.04x faster                                       |
| pathlib                  | 19.8 ms                                                      | 19.2 ms: 1.03x faster                                        |
| float                    | 78.5 ms                                                      | 76.4 ms: 1.03x faster                                        |
| pickle_pure_python       | 323 us                                                       | 315 us: 1.03x faster                                         |
| telco                    | 6.96 ms                                                      | 6.80 ms: 1.02x faster                                        |
| deepcopy_reduce          | 3.46 us                                                      | 3.39 us: 1.02x faster                                        |
| docutils                 | 2.89 sec                                                     | 2.83 sec: 1.02x faster                                       |
| unpickle_list            | 4.77 us                                                      | 4.69 us: 1.02x faster                                        |
| pyflate                  | 447 ms                                                       | 442 ms: 1.01x faster                                         |
| pickle                   | 10.1 us                                                      | 9.99 us: 1.01x faster                                        |
| 2to3                     | 287 ms                                                       | 285 ms: 1.01x faster                                         |
| pickle_dict              | 31.7 us                                                      | 32.1 us: 1.01x slower                                        |
| sqlglot_optimize         | 57.8 ms                                                      | 58.6 ms: 1.01x slower                                        |
| json_loads               | 24.3 us                                                      | 24.6 us: 1.01x slower                                        |
| json                     | 5.14 ms                                                      | 5.23 ms: 1.02x slower                                        |
| pidigits                 | 264 ms                                                       | 268 ms: 1.02x slower                                         |
| crypto_pyaes             | 80.9 ms                                                      | 82.4 ms: 1.02x slower                                        |
| deepcopy                 | 376 us                                                       | 383 us: 1.02x slower                                         |
| xml_etree_iterparse      | 103 ms                                                       | 105 ms: 1.02x slower                                         |
| scimark_sor              | 110 ms                                                       | 112 ms: 1.02x slower                                         |
| dask                     | 397 ms                                                       | 407 ms: 1.03x slower                                         |
| nbody                    | 94.1 ms                                                      | 96.9 ms: 1.03x slower                                        |
| sqlglot_normalize        | 117 ms                                                       | 121 ms: 1.03x slower                                         |
| logging_simple           | 6.73 us                                                      | 6.96 us: 1.03x slower                                        |
| tomli_loads              | 2.20 sec                                                     | 2.28 sec: 1.04x slower                                       |
| logging_format           | 7.37 us                                                      | 7.66 us: 1.04x slower                                        |
| logging_silent           | 95.6 ns                                                      | 101 ns: 1.06x slower                                         |
| sqlglot_transpile        | 1.80 ms                                                      | 1.91 ms: 1.06x slower                                        |
| spectral_norm            | 91.6 ms                                                      | 97.3 ms: 1.06x slower                                        |
| async_tree_cpu_io_mixed  | 706 ms                                                       | 751 ms: 1.06x slower                                         |
| go                       | 150 ms                                                       | 162 ms: 1.08x slower                                         |
| regex_compile            | 146 ms                                                       | 157 ms: 1.08x slower                                         |
| mako                     | 9.94 ms                                                      | 10.8 ms: 1.09x slower                                        |
| xml_etree_parse          | 146 ms                                                       | 159 ms: 1.09x slower                                         |
| sqlglot_parse            | 1.40 ms                                                      | 1.53 ms: 1.09x slower                                        |
| richards                 | 45.0 ms                                                      | 49.6 ms: 1.10x slower                                        |
| async_tree_io            | 1.06 sec                                                     | 1.17 sec: 1.11x slower                                       |
| gc_traversal             | 3.54 ms                                                      | 3.97 ms: 1.12x slower                                        |
| async_tree_memoization   | 553 ms                                                       | 622 ms: 1.12x slower                                         |
| nqueens                  | 90.1 ms                                                      | 101 ms: 1.12x slower                                         |
| scimark_lu               | 101 ms                                                       | 114 ms: 1.13x slower                                         |
| mdp                      | 2.53 sec                                                     | 2.86 sec: 1.13x slower                                       |
| async_tree_none          | 459 ms                                                       | 519 ms: 1.13x slower                                         |
| comprehensions           | 21.9 us                                                      | 24.8 us: 1.13x slower                                        |
| unpickle_pure_python     | 207 us                                                       | 239 us: 1.15x slower                                         |
| chaos                    | 62.9 ms                                                      | 73.4 ms: 1.17x slower                                        |
| hexiom                   | 5.96 ms                                                      | 6.97 ms: 1.17x slower                                        |
| deltablue                | 3.29 ms                                                      | 3.97 ms: 1.21x slower                                        |
| coroutines               | 23.0 ms                                                      | 27.9 ms: 1.21x slower                                        |
| richards_super           | 51.7 ms                                                      | 63.6 ms: 1.23x slower                                        |
| fannkuch                 | 350 ms                                                       | 437 ms: 1.25x slower                                         |
| json_dumps               | 10.2 ms                                                      | 13.3 ms: 1.30x slower                                        |
| mypy2                    | 368 ms                                                       | 534 ms: 1.45x slower                                         |
| generators               | 36.7 ms                                                      | 54.3 ms: 1.48x slower                                        |
| asyncio_tcp_ssl          | 1.58 sec                                                     | 3.09 sec: 1.96x slower                                       |
| asyncio_tcp              | 381 ms                                                       | 747 ms: 1.96x slower                                         |
| typing_runtime_protocols | 151 us                                                       | 519 us: 3.43x slower                                         |
| Geometric mean           | (ref)                                                        | 1.06x slower                                                 |

Benchmark hidden because not significant (7): raytrace, dulwich_log, meteor_contest, pycparser, deepcopy_memo, tornado_http, bench_thread_pool
Ignored benchmarks (1) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: coverage
Ignored benchmarks (16) of results/bm-20231002-3.11.6-8b6ee5b/bm-20231002-pythonperf2-x86_64-python-v3.11.6-3.11.6-8b6ee5b.json: aiohttp, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 99.68% likely to be slow
- 90% likely to have a slowdown of 1.01x
- 95% likely to have a slowdown of 1.01x
- 99% likely to have a slowdown of 1.00x
