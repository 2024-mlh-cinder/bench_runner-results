
# Results vs. 3.11.0

- fork: python
- ref: main
- machine: linux-x86_64
- commit hash: 84b7e9e
- commit date: 2023-10-14
- overall geometric mean: 1.05x faster
- HPT reliability: 90.98%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231014-pythonperf2-x86_64-python-main-3.13.0a1+-84b7e9e |
|----------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| docutils       | 2.86 sec                                                     | 2.87 sec: 1.00x slower                                       |
| Geometric mean | (ref)                                                        | 1.00x slower                                                 |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231014-pythonperf2-x86_64-python-main-3.13.0a1+-84b7e9e |
|----------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| nbody          | 90.7 ms                                                      | 86.0 ms: 1.05x faster                                        |
| pidigits       | 251 ms                                                       | 264 ms: 1.05x slower                                         |
| float          | 74.2 ms                                                      | 81.4 ms: 1.10x slower                                        |
| Geometric mean | (ref)                                                        | 1.03x slower                                                 |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231014-pythonperf2-x86_64-python-main-3.13.0a1+-84b7e9e |
|----------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| regex_compile  | 158 ms                                                       | 148 ms: 1.06x faster                                         |
| regex_v8       | 23.9 ms                                                      | 25.3 ms: 1.06x slower                                        |
| regex_dna      | 227 ms                                                       | 240 ms: 1.06x slower                                         |
| Geometric mean | (ref)                                                        | 1.02x slower                                                 |

Benchmark hidden because not significant (1): regex_effbot

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231014-pythonperf2-x86_64-python-main-3.13.0a1+-84b7e9e |
|----------------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| json_dumps           | 13.4 ms                                                      | 10.6 ms: 1.26x faster                                        |
| json_loads           | 28.7 us                                                      | 24.3 us: 1.18x faster                                        |
| unpickle_pure_python | 241 us                                                       | 219 us: 1.10x faster                                         |
| xml_etree_parse      | 158 ms                                                       | 147 ms: 1.07x faster                                         |
| xml_etree_iterparse  | 104 ms                                                       | 105 ms: 1.01x slower                                         |
| tomli_loads          | 2.26 sec                                                     | 2.32 sec: 1.02x slower                                       |
| xml_etree_process    | 56.5 ms                                                      | 58.4 ms: 1.03x slower                                        |
| pickle_dict          | 30.8 us                                                      | 31.9 us: 1.04x slower                                        |
| pickle               | 9.64 us                                                      | 10.2 us: 1.06x slower                                        |
| xml_etree_generate   | 80.5 ms                                                      | 85.3 ms: 1.06x slower                                        |
| unpickle_list        | 4.53 us                                                      | 4.82 us: 1.06x slower                                        |
| pickle_list          | 3.83 us                                                      | 4.15 us: 1.08x slower                                        |
| unpickle             | 13.4 us                                                      | 14.6 us: 1.09x slower                                        |
| Geometric mean       | (ref)                                                        | 1.01x faster                                                 |

Benchmark hidden because not significant (1): pickle_pure_python

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231014-pythonperf2-x86_64-python-main-3.13.0a1+-84b7e9e |
|------------------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| python_startup_no_site | 7.76 ms                                                      | 8.66 ms: 1.12x slower                                        |
| python_startup         | 10.8 ms                                                      | 12.6 ms: 1.17x slower                                        |
| Geometric mean         | (ref)                                                        | 1.14x slower                                                 |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231014-pythonperf2-x86_64-python-main-3.13.0a1+-84b7e9e |
|-----------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| mako      | 11.0 ms                                                      | 10.5 ms: 1.05x faster                                        |

All benchmarks:
===============

| Benchmark                | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231014-pythonperf2-x86_64-python-main-3.13.0a1+-84b7e9e |
|--------------------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| typing_runtime_protocols | 523 us                                                       | 151 us: 3.46x faster                                         |
| asyncio_tcp              | 753 ms                                                       | 368 ms: 2.04x faster                                         |
| asyncio_tcp_ssl          | 3.08 sec                                                     | 1.61 sec: 1.91x faster                                       |
| generators               | 56.0 ms                                                      | 35.5 ms: 1.58x faster                                        |
| chaos                    | 80.9 ms                                                      | 62.7 ms: 1.29x faster                                        |
| json_dumps               | 13.4 ms                                                      | 10.6 ms: 1.26x faster                                        |
| mypy2                    | 451 ms                                                       | 370 ms: 1.22x faster                                         |
| async_tree_none          | 519 ms                                                       | 434 ms: 1.20x faster                                         |
| coroutines               | 27.6 ms                                                      | 23.3 ms: 1.18x faster                                        |
| json_loads               | 28.7 us                                                      | 24.3 us: 1.18x faster                                        |
| nqueens                  | 103 ms                                                       | 88.6 ms: 1.16x faster                                        |
| raytrace                 | 317 ms                                                       | 275 ms: 1.15x faster                                         |
| async_tree_memoization   | 630 ms                                                       | 548 ms: 1.15x faster                                         |
| crypto_pyaes             | 83.4 ms                                                      | 73.1 ms: 1.14x faster                                        |
| comprehensions           | 24.6 us                                                      | 21.8 us: 1.13x faster                                        |
| scimark_lu               | 115 ms                                                       | 102 ms: 1.13x faster                                         |
| hexiom                   | 7.13 ms                                                      | 6.39 ms: 1.12x faster                                        |
| json                     | 5.65 ms                                                      | 5.11 ms: 1.10x faster                                        |
| deltablue                | 4.00 ms                                                      | 3.62 ms: 1.10x faster                                        |
| unpickle_pure_python     | 241 us                                                       | 219 us: 1.10x faster                                         |
| sqlglot_parse            | 1.53 ms                                                      | 1.40 ms: 1.09x faster                                        |
| async_tree_io            | 1.17 sec                                                     | 1.08 sec: 1.09x faster                                       |
| gc_traversal             | 3.85 ms                                                      | 3.54 ms: 1.09x faster                                        |
| mdp                      | 2.75 sec                                                     | 2.54 sec: 1.08x faster                                       |
| sqlglot_normalize        | 126 ms                                                       | 117 ms: 1.08x faster                                         |
| fannkuch                 | 429 ms                                                       | 399 ms: 1.08x faster                                         |
| xml_etree_parse          | 158 ms                                                       | 147 ms: 1.07x faster                                         |
| async_tree_cpu_io_mixed  | 749 ms                                                       | 701 ms: 1.07x faster                                         |
| logging_format           | 8.11 us                                                      | 7.59 us: 1.07x faster                                        |
| deepcopy                 | 399 us                                                       | 375 us: 1.06x faster                                         |
| regex_compile            | 158 ms                                                       | 148 ms: 1.06x faster                                         |
| sqlglot_transpile        | 1.92 ms                                                      | 1.81 ms: 1.06x faster                                        |
| deepcopy_reduce          | 3.51 us                                                      | 3.32 us: 1.06x faster                                        |
| nbody                    | 90.7 ms                                                      | 86.0 ms: 1.05x faster                                        |
| mako                     | 11.0 ms                                                      | 10.5 ms: 1.05x faster                                        |
| logging_silent           | 101 ns                                                       | 96.9 ns: 1.04x faster                                        |
| logging_simple           | 7.19 us                                                      | 6.93 us: 1.04x faster                                        |
| pycparser                | 1.32 sec                                                     | 1.28 sec: 1.03x faster                                       |
| deepcopy_memo            | 38.8 us                                                      | 37.7 us: 1.03x faster                                        |
| scimark_monte_carlo      | 68.2 ms                                                      | 66.5 ms: 1.03x faster                                        |
| bench_thread_pool        | 1.01 ms                                                      | 986 us: 1.03x faster                                         |
| sqlglot_optimize         | 59.8 ms                                                      | 59.2 ms: 1.01x faster                                        |
| spectral_norm            | 93.3 ms                                                      | 93.6 ms: 1.00x slower                                        |
| meteor_contest           | 131 ms                                                       | 131 ms: 1.00x slower                                         |
| docutils                 | 2.86 sec                                                     | 2.87 sec: 1.00x slower                                       |
| dulwich_log              | 68.4 ms                                                      | 69.1 ms: 1.01x slower                                        |
| coverage                 | 84.8 ms                                                      | 85.7 ms: 1.01x slower                                        |
| xml_etree_iterparse      | 104 ms                                                       | 105 ms: 1.01x slower                                         |
| pprint_pformat           | 1.63 sec                                                     | 1.67 sec: 1.02x slower                                       |
| tomli_loads              | 2.26 sec                                                     | 2.32 sec: 1.02x slower                                       |
| pathlib                  | 19.1 ms                                                      | 19.6 ms: 1.03x slower                                        |
| xml_etree_process        | 56.5 ms                                                      | 58.4 ms: 1.03x slower                                        |
| pickle_dict              | 30.8 us                                                      | 31.9 us: 1.04x slower                                        |
| create_gc_cycles         | 1.61 ms                                                      | 1.67 ms: 1.04x slower                                        |
| pprint_safe_repr         | 784 ms                                                       | 815 ms: 1.04x slower                                         |
| go                       | 164 ms                                                       | 171 ms: 1.04x slower                                         |
| pidigits                 | 251 ms                                                       | 264 ms: 1.05x slower                                         |
| regex_v8                 | 23.9 ms                                                      | 25.3 ms: 1.06x slower                                        |
| pickle                   | 9.64 us                                                      | 10.2 us: 1.06x slower                                        |
| regex_dna                | 227 ms                                                       | 240 ms: 1.06x slower                                         |
| xml_etree_generate       | 80.5 ms                                                      | 85.3 ms: 1.06x slower                                        |
| unpickle_list            | 4.53 us                                                      | 4.82 us: 1.06x slower                                        |
| scimark_fft              | 285 ms                                                       | 307 ms: 1.08x slower                                         |
| sqlite_synth             | 2.50 us                                                      | 2.70 us: 1.08x slower                                        |
| pickle_list              | 3.83 us                                                      | 4.15 us: 1.08x slower                                        |
| unpickle                 | 13.4 us                                                      | 14.6 us: 1.09x slower                                        |
| float                    | 74.2 ms                                                      | 81.4 ms: 1.10x slower                                        |
| python_startup_no_site   | 7.76 ms                                                      | 8.66 ms: 1.12x slower                                        |
| pyflate                  | 449 ms                                                       | 510 ms: 1.14x slower                                         |
| richards                 | 48.3 ms                                                      | 55.4 ms: 1.15x slower                                        |
| python_startup           | 10.8 ms                                                      | 12.6 ms: 1.17x slower                                        |
| telco                    | 6.86 ms                                                      | 8.11 ms: 1.18x slower                                        |
| unpack_sequence          | 45.6 ns                                                      | 55.1 ns: 1.21x slower                                        |
| async_generators         | 316 ms                                                       | 392 ms: 1.24x slower                                         |
| scimark_sor              | 111 ms                                                       | 145 ms: 1.31x slower                                         |
| Geometric mean           | (ref)                                                        | 1.05x faster                                                 |

Benchmark hidden because not significant (6): tornado_http, richards_super, scimark_sparse_mat_mult, pickle_pure_python, bench_mp_pool, regex_effbot
Ignored benchmarks (18) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509.json: 2to3, aiohttp, chameleon, dask, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 90.98% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
