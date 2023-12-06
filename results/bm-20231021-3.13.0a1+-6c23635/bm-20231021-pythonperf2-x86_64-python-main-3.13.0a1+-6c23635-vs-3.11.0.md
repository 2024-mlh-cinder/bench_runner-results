
# Results vs. 3.11.0

- fork: python
- ref: main
- machine: linux-x86_64
- commit hash: 6c23635
- commit date: 2023-10-21
- overall geometric mean: 1.05x faster
- HPT reliability: 86.42%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231021-pythonperf2-x86_64-python-main-3.13.0a1+-6c23635 |
|----------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| docutils       | 2.86 sec                                                     | 2.90 sec: 1.02x slower                                       |
| Geometric mean | (ref)                                                        | 1.01x slower                                                 |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231021-pythonperf2-x86_64-python-main-3.13.0a1+-6c23635 |
|----------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| nbody          | 90.7 ms                                                      | 86.2 ms: 1.05x faster                                        |
| float          | 74.2 ms                                                      | 78.0 ms: 1.05x slower                                        |
| pidigits       | 251 ms                                                       | 265 ms: 1.05x slower                                         |
| Geometric mean | (ref)                                                        | 1.02x slower                                                 |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231021-pythonperf2-x86_64-python-main-3.13.0a1+-6c23635 |
|----------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| regex_compile  | 158 ms                                                       | 148 ms: 1.07x faster                                         |
| regex_effbot   | 3.50 ms                                                      | 3.53 ms: 1.01x slower                                        |
| regex_v8       | 23.9 ms                                                      | 24.5 ms: 1.02x slower                                        |
| regex_dna      | 227 ms                                                       | 238 ms: 1.05x slower                                         |
| Geometric mean | (ref)                                                        | 1.00x slower                                                 |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231021-pythonperf2-x86_64-python-main-3.13.0a1+-6c23635 |
|----------------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| json_dumps           | 13.4 ms                                                      | 10.5 ms: 1.27x faster                                        |
| json_loads           | 28.7 us                                                      | 24.3 us: 1.18x faster                                        |
| unpickle_pure_python | 241 us                                                       | 225 us: 1.07x faster                                         |
| xml_etree_parse      | 158 ms                                                       | 150 ms: 1.05x faster                                         |
| pickle_pure_python   | 319 us                                                       | 313 us: 1.02x faster                                         |
| unpickle_list        | 4.53 us                                                      | 4.47 us: 1.01x faster                                        |
| tomli_loads          | 2.26 sec                                                     | 2.32 sec: 1.02x slower                                       |
| xml_etree_iterparse  | 104 ms                                                       | 107 ms: 1.03x slower                                         |
| pickle               | 9.64 us                                                      | 10.1 us: 1.04x slower                                        |
| xml_etree_process    | 56.5 ms                                                      | 59.1 ms: 1.05x slower                                        |
| pickle_dict          | 30.8 us                                                      | 32.3 us: 1.05x slower                                        |
| unpickle             | 13.4 us                                                      | 14.2 us: 1.06x slower                                        |
| xml_etree_generate   | 80.5 ms                                                      | 85.9 ms: 1.07x slower                                        |
| pickle_list          | 3.83 us                                                      | 4.37 us: 1.14x slower                                        |
| Geometric mean       | (ref)                                                        | 1.01x faster                                                 |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231021-pythonperf2-x86_64-python-main-3.13.0a1+-6c23635 |
|------------------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| python_startup_no_site | 7.76 ms                                                      | 8.69 ms: 1.12x slower                                        |
| python_startup         | 10.8 ms                                                      | 12.6 ms: 1.17x slower                                        |
| Geometric mean         | (ref)                                                        | 1.15x slower                                                 |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231021-pythonperf2-x86_64-python-main-3.13.0a1+-6c23635 |
|-----------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| mako      | 11.0 ms                                                      | 10.4 ms: 1.06x faster                                        |

All benchmarks:
===============

| Benchmark                | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231021-pythonperf2-x86_64-python-main-3.13.0a1+-6c23635 |
|--------------------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| typing_runtime_protocols | 523 us                                                       | 156 us: 3.36x faster                                         |
| asyncio_tcp              | 753 ms                                                       | 371 ms: 2.03x faster                                         |
| asyncio_tcp_ssl          | 3.08 sec                                                     | 1.58 sec: 1.95x faster                                       |
| generators               | 56.0 ms                                                      | 35.8 ms: 1.56x faster                                        |
| chaos                    | 80.9 ms                                                      | 63.3 ms: 1.28x faster                                        |
| json_dumps               | 13.4 ms                                                      | 10.5 ms: 1.27x faster                                        |
| coroutines               | 27.6 ms                                                      | 22.7 ms: 1.21x faster                                        |
| mypy2                    | 451 ms                                                       | 373 ms: 1.21x faster                                         |
| async_tree_none          | 519 ms                                                       | 434 ms: 1.20x faster                                         |
| json_loads               | 28.7 us                                                      | 24.3 us: 1.18x faster                                        |
| nqueens                  | 103 ms                                                       | 88.3 ms: 1.16x faster                                        |
| crypto_pyaes             | 83.4 ms                                                      | 71.7 ms: 1.16x faster                                        |
| async_tree_memoization   | 630 ms                                                       | 548 ms: 1.15x faster                                         |
| scimark_lu               | 115 ms                                                       | 99.7 ms: 1.15x faster                                        |
| comprehensions           | 24.6 us                                                      | 21.7 us: 1.14x faster                                        |
| raytrace                 | 317 ms                                                       | 280 ms: 1.13x faster                                         |
| json                     | 5.65 ms                                                      | 5.08 ms: 1.11x faster                                        |
| hexiom                   | 7.13 ms                                                      | 6.46 ms: 1.11x faster                                        |
| fannkuch                 | 429 ms                                                       | 392 ms: 1.09x faster                                         |
| logging_format           | 8.11 us                                                      | 7.42 us: 1.09x faster                                        |
| deltablue                | 4.00 ms                                                      | 3.66 ms: 1.09x faster                                        |
| mdp                      | 2.75 sec                                                     | 2.52 sec: 1.09x faster                                       |
| async_tree_io            | 1.17 sec                                                     | 1.08 sec: 1.09x faster                                       |
| sqlglot_parse            | 1.53 ms                                                      | 1.42 ms: 1.08x faster                                        |
| sqlglot_normalize        | 126 ms                                                       | 117 ms: 1.08x faster                                         |
| async_tree_cpu_io_mixed  | 749 ms                                                       | 700 ms: 1.07x faster                                         |
| unpickle_pure_python     | 241 us                                                       | 225 us: 1.07x faster                                         |
| regex_compile            | 158 ms                                                       | 148 ms: 1.07x faster                                         |
| deepcopy                 | 399 us                                                       | 377 us: 1.06x faster                                         |
| mako                     | 11.0 ms                                                      | 10.4 ms: 1.06x faster                                        |
| coverage                 | 84.8 ms                                                      | 80.2 ms: 1.06x faster                                        |
| logging_simple           | 7.19 us                                                      | 6.81 us: 1.06x faster                                        |
| nbody                    | 90.7 ms                                                      | 86.2 ms: 1.05x faster                                        |
| xml_etree_parse          | 158 ms                                                       | 150 ms: 1.05x faster                                         |
| bench_thread_pool        | 1.01 ms                                                      | 964 us: 1.05x faster                                         |
| sqlglot_transpile        | 1.92 ms                                                      | 1.83 ms: 1.05x faster                                        |
| deepcopy_reduce          | 3.51 us                                                      | 3.36 us: 1.05x faster                                        |
| create_gc_cycles         | 1.61 ms                                                      | 1.54 ms: 1.04x faster                                        |
| gc_traversal             | 3.85 ms                                                      | 3.72 ms: 1.03x faster                                        |
| logging_silent           | 101 ns                                                       | 98.3 ns: 1.03x faster                                        |
| pickle_pure_python       | 319 us                                                       | 313 us: 1.02x faster                                         |
| spectral_norm            | 93.3 ms                                                      | 91.7 ms: 1.02x faster                                        |
| deepcopy_memo            | 38.8 us                                                      | 38.3 us: 1.01x faster                                        |
| unpickle_list            | 4.53 us                                                      | 4.47 us: 1.01x faster                                        |
| sqlglot_optimize         | 59.8 ms                                                      | 59.2 ms: 1.01x faster                                        |
| meteor_contest           | 131 ms                                                       | 130 ms: 1.01x faster                                         |
| regex_effbot             | 3.50 ms                                                      | 3.53 ms: 1.01x slower                                        |
| dulwich_log              | 68.4 ms                                                      | 69.4 ms: 1.01x slower                                        |
| docutils                 | 2.86 sec                                                     | 2.90 sec: 1.02x slower                                       |
| regex_v8                 | 23.9 ms                                                      | 24.5 ms: 1.02x slower                                        |
| tomli_loads              | 2.26 sec                                                     | 2.32 sec: 1.02x slower                                       |
| xml_etree_iterparse      | 104 ms                                                       | 107 ms: 1.03x slower                                         |
| pathlib                  | 19.1 ms                                                      | 19.7 ms: 1.03x slower                                        |
| scimark_monte_carlo      | 68.2 ms                                                      | 70.6 ms: 1.04x slower                                        |
| pickle                   | 9.64 us                                                      | 10.1 us: 1.04x slower                                        |
| xml_etree_process        | 56.5 ms                                                      | 59.1 ms: 1.05x slower                                        |
| regex_dna                | 227 ms                                                       | 238 ms: 1.05x slower                                         |
| pickle_dict              | 30.8 us                                                      | 32.3 us: 1.05x slower                                        |
| float                    | 74.2 ms                                                      | 78.0 ms: 1.05x slower                                        |
| pidigits                 | 251 ms                                                       | 265 ms: 1.05x slower                                         |
| scimark_sparse_mat_mult  | 4.05 ms                                                      | 4.28 ms: 1.06x slower                                        |
| go                       | 164 ms                                                       | 173 ms: 1.06x slower                                         |
| unpickle                 | 13.4 us                                                      | 14.2 us: 1.06x slower                                        |
| pprint_pformat           | 1.63 sec                                                     | 1.73 sec: 1.06x slower                                       |
| xml_etree_generate       | 80.5 ms                                                      | 85.9 ms: 1.07x slower                                        |
| sqlite_synth             | 2.50 us                                                      | 2.67 us: 1.07x slower                                        |
| pprint_safe_repr         | 784 ms                                                       | 845 ms: 1.08x slower                                         |
| scimark_fft              | 285 ms                                                       | 316 ms: 1.11x slower                                         |
| python_startup_no_site   | 7.76 ms                                                      | 8.69 ms: 1.12x slower                                        |
| pickle_list              | 3.83 us                                                      | 4.37 us: 1.14x slower                                        |
| richards                 | 48.3 ms                                                      | 55.7 ms: 1.15x slower                                        |
| python_startup           | 10.8 ms                                                      | 12.6 ms: 1.17x slower                                        |
| pyflate                  | 449 ms                                                       | 528 ms: 1.18x slower                                         |
| telco                    | 6.86 ms                                                      | 8.20 ms: 1.19x slower                                        |
| unpack_sequence          | 45.6 ns                                                      | 54.9 ns: 1.20x slower                                        |
| async_generators         | 316 ms                                                       | 397 ms: 1.26x slower                                         |
| scimark_sor              | 111 ms                                                       | 149 ms: 1.34x slower                                         |
| Geometric mean           | (ref)                                                        | 1.05x faster                                                 |

Benchmark hidden because not significant (4): pycparser, tornado_http, bench_mp_pool, richards_super
Ignored benchmarks (18) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509.json: 2to3, aiohttp, chameleon, dask, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 86.42% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
