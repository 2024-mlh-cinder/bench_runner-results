
# Results vs. 3.11.0

- fork: faster-cpython
- ref: tidy_up_eval_breaker
- machine: linux-x86_64
- commit hash: 4da67aa
- commit date: 2023-09-25
- overall geometric mean: 1.05x faster
- HPT reliability: 91.62%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230925-pythonperf2-x86_64-faster%2dcpython-tidy_up_eval_breaker-3.13.0a0-4da67aa |
|----------------|:------------------------------------------------------------:|:-------------------------------------------------------------------------------------:|
| docutils       | 2.86 sec                                                     | 2.87 sec: 1.00x slower                                                                |
| Geometric mean | (ref)                                                        | 1.00x faster                                                                          |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230925-pythonperf2-x86_64-faster%2dcpython-tidy_up_eval_breaker-3.13.0a0-4da67aa |
|----------------|:------------------------------------------------------------:|:-------------------------------------------------------------------------------------:|
| nbody          | 90.7 ms                                                      | 86.7 ms: 1.05x faster                                                                 |
| pidigits       | 251 ms                                                       | 265 ms: 1.05x slower                                                                  |
| float          | 74.2 ms                                                      | 81.2 ms: 1.09x slower                                                                 |
| Geometric mean | (ref)                                                        | 1.03x slower                                                                          |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230925-pythonperf2-x86_64-faster%2dcpython-tidy_up_eval_breaker-3.13.0a0-4da67aa |
|----------------|:------------------------------------------------------------:|:-------------------------------------------------------------------------------------:|
| regex_compile  | 158 ms                                                       | 149 ms: 1.06x faster                                                                  |
| regex_effbot   | 3.50 ms                                                      | 3.62 ms: 1.03x slower                                                                 |
| regex_v8       | 23.9 ms                                                      | 26.0 ms: 1.09x slower                                                                 |
| regex_dna      | 227 ms                                                       | 250 ms: 1.10x slower                                                                  |
| Geometric mean | (ref)                                                        | 1.04x slower                                                                          |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230925-pythonperf2-x86_64-faster%2dcpython-tidy_up_eval_breaker-3.13.0a0-4da67aa |
|----------------------|:------------------------------------------------------------:|:-------------------------------------------------------------------------------------:|
| json_dumps           | 13.4 ms                                                      | 10.4 ms: 1.28x faster                                                                 |
| json_loads           | 28.7 us                                                      | 24.7 us: 1.16x faster                                                                 |
| xml_etree_parse      | 158 ms                                                       | 153 ms: 1.03x faster                                                                  |
| tomli_loads          | 2.26 sec                                                     | 2.21 sec: 1.03x faster                                                                |
| unpickle_pure_python | 241 us                                                       | 238 us: 1.01x faster                                                                  |
| xml_etree_iterparse  | 104 ms                                                       | 107 ms: 1.03x slower                                                                  |
| xml_etree_process    | 56.5 ms                                                      | 58.5 ms: 1.04x slower                                                                 |
| pickle_dict          | 30.8 us                                                      | 32.0 us: 1.04x slower                                                                 |
| pickle               | 9.64 us                                                      | 10.0 us: 1.04x slower                                                                 |
| unpickle_list        | 4.53 us                                                      | 4.84 us: 1.07x slower                                                                 |
| xml_etree_generate   | 80.5 ms                                                      | 86.0 ms: 1.07x slower                                                                 |
| unpickle             | 13.4 us                                                      | 15.0 us: 1.12x slower                                                                 |
| pickle_list          | 3.83 us                                                      | 4.36 us: 1.14x slower                                                                 |
| Geometric mean       | (ref)                                                        | 1.00x slower                                                                          |

Benchmark hidden because not significant (1): pickle_pure_python

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230925-pythonperf2-x86_64-faster%2dcpython-tidy_up_eval_breaker-3.13.0a0-4da67aa |
|------------------------|:------------------------------------------------------------:|:-------------------------------------------------------------------------------------:|
| python_startup_no_site | 7.76 ms                                                      | 8.68 ms: 1.12x slower                                                                 |
| python_startup         | 10.8 ms                                                      | 12.7 ms: 1.18x slower                                                                 |
| Geometric mean         | (ref)                                                        | 1.15x slower                                                                          |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230925-pythonperf2-x86_64-faster%2dcpython-tidy_up_eval_breaker-3.13.0a0-4da67aa |
|-----------|:------------------------------------------------------------:|:-------------------------------------------------------------------------------------:|
| mako      | 11.0 ms                                                      | 10.4 ms: 1.06x faster                                                                 |

All benchmarks:
===============

| Benchmark                | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230925-pythonperf2-x86_64-faster%2dcpython-tidy_up_eval_breaker-3.13.0a0-4da67aa |
|--------------------------|:------------------------------------------------------------:|:-------------------------------------------------------------------------------------:|
| typing_runtime_protocols | 523 us                                                       | 150 us: 3.48x faster                                                                  |
| asyncio_tcp              | 753 ms                                                       | 368 ms: 2.05x faster                                                                  |
| asyncio_tcp_ssl          | 3.08 sec                                                     | 1.58 sec: 1.95x faster                                                                |
| generators               | 56.0 ms                                                      | 35.3 ms: 1.59x faster                                                                 |
| chaos                    | 80.9 ms                                                      | 63.0 ms: 1.28x faster                                                                 |
| json_dumps               | 13.4 ms                                                      | 10.4 ms: 1.28x faster                                                                 |
| mypy2                    | 451 ms                                                       | 372 ms: 1.21x faster                                                                  |
| coroutines               | 27.6 ms                                                      | 22.9 ms: 1.20x faster                                                                 |
| async_tree_none          | 519 ms                                                       | 436 ms: 1.19x faster                                                                  |
| nqueens                  | 103 ms                                                       | 88.0 ms: 1.17x faster                                                                 |
| json_loads               | 28.7 us                                                      | 24.7 us: 1.16x faster                                                                 |
| async_tree_memoization   | 630 ms                                                       | 549 ms: 1.15x faster                                                                  |
| crypto_pyaes             | 83.4 ms                                                      | 73.4 ms: 1.14x faster                                                                 |
| scimark_lu               | 115 ms                                                       | 101 ms: 1.13x faster                                                                  |
| raytrace                 | 317 ms                                                       | 281 ms: 1.13x faster                                                                  |
| hexiom                   | 7.13 ms                                                      | 6.39 ms: 1.12x faster                                                                 |
| comprehensions           | 24.6 us                                                      | 22.1 us: 1.11x faster                                                                 |
| json                     | 5.65 ms                                                      | 5.10 ms: 1.11x faster                                                                 |
| sqlglot_parse            | 1.53 ms                                                      | 1.39 ms: 1.10x faster                                                                 |
| logging_format           | 8.11 us                                                      | 7.36 us: 1.10x faster                                                                 |
| deltablue                | 4.00 ms                                                      | 3.64 ms: 1.10x faster                                                                 |
| mdp                      | 2.75 sec                                                     | 2.52 sec: 1.09x faster                                                                |
| fannkuch                 | 429 ms                                                       | 393 ms: 1.09x faster                                                                  |
| sqlglot_normalize        | 126 ms                                                       | 116 ms: 1.08x faster                                                                  |
| coverage                 | 84.8 ms                                                      | 78.4 ms: 1.08x faster                                                                 |
| async_tree_io            | 1.17 sec                                                     | 1.09 sec: 1.08x faster                                                                |
| gc_traversal             | 3.85 ms                                                      | 3.58 ms: 1.07x faster                                                                 |
| logging_simple           | 7.19 us                                                      | 6.71 us: 1.07x faster                                                                 |
| sqlglot_transpile        | 1.92 ms                                                      | 1.79 ms: 1.07x faster                                                                 |
| async_tree_cpu_io_mixed  | 749 ms                                                       | 701 ms: 1.07x faster                                                                  |
| mako                     | 11.0 ms                                                      | 10.4 ms: 1.06x faster                                                                 |
| regex_compile            | 158 ms                                                       | 149 ms: 1.06x faster                                                                  |
| deepcopy                 | 399 us                                                       | 379 us: 1.05x faster                                                                  |
| deepcopy_memo            | 38.8 us                                                      | 37.0 us: 1.05x faster                                                                 |
| bench_thread_pool        | 1.01 ms                                                      | 963 us: 1.05x faster                                                                  |
| nbody                    | 90.7 ms                                                      | 86.7 ms: 1.05x faster                                                                 |
| logging_silent           | 101 ns                                                       | 97.6 ns: 1.03x faster                                                                 |
| xml_etree_parse          | 158 ms                                                       | 153 ms: 1.03x faster                                                                  |
| deepcopy_reduce          | 3.51 us                                                      | 3.42 us: 1.03x faster                                                                 |
| spectral_norm            | 93.3 ms                                                      | 90.9 ms: 1.03x faster                                                                 |
| unpack_sequence          | 45.6 ns                                                      | 44.5 ns: 1.03x faster                                                                 |
| tomli_loads              | 2.26 sec                                                     | 2.21 sec: 1.03x faster                                                                |
| scimark_monte_carlo      | 68.2 ms                                                      | 66.9 ms: 1.02x faster                                                                 |
| sqlglot_optimize         | 59.8 ms                                                      | 58.7 ms: 1.02x faster                                                                 |
| unpickle_pure_python     | 241 us                                                       | 238 us: 1.01x faster                                                                  |
| meteor_contest           | 131 ms                                                       | 131 ms: 1.00x slower                                                                  |
| docutils                 | 2.86 sec                                                     | 2.87 sec: 1.00x slower                                                                |
| scimark_sparse_mat_mult  | 4.05 ms                                                      | 4.06 ms: 1.00x slower                                                                 |
| pycparser                | 1.32 sec                                                     | 1.34 sec: 1.01x slower                                                                |
| pathlib                  | 19.1 ms                                                      | 19.3 ms: 1.01x slower                                                                 |
| dulwich_log              | 68.4 ms                                                      | 69.6 ms: 1.02x slower                                                                 |
| xml_etree_iterparse      | 104 ms                                                       | 107 ms: 1.03x slower                                                                  |
| pprint_pformat           | 1.63 sec                                                     | 1.68 sec: 1.03x slower                                                                |
| regex_effbot             | 3.50 ms                                                      | 3.62 ms: 1.03x slower                                                                 |
| xml_etree_process        | 56.5 ms                                                      | 58.5 ms: 1.04x slower                                                                 |
| pickle_dict              | 30.8 us                                                      | 32.0 us: 1.04x slower                                                                 |
| pickle                   | 9.64 us                                                      | 10.0 us: 1.04x slower                                                                 |
| create_gc_cycles         | 1.61 ms                                                      | 1.68 ms: 1.04x slower                                                                 |
| bench_mp_pool            | 4.62 ms                                                      | 4.83 ms: 1.05x slower                                                                 |
| go                       | 164 ms                                                       | 171 ms: 1.05x slower                                                                  |
| pprint_safe_repr         | 784 ms                                                       | 821 ms: 1.05x slower                                                                  |
| pidigits                 | 251 ms                                                       | 265 ms: 1.05x slower                                                                  |
| sqlite_synth             | 2.50 us                                                      | 2.66 us: 1.07x slower                                                                 |
| unpickle_list            | 4.53 us                                                      | 4.84 us: 1.07x slower                                                                 |
| xml_etree_generate       | 80.5 ms                                                      | 86.0 ms: 1.07x slower                                                                 |
| regex_v8                 | 23.9 ms                                                      | 26.0 ms: 1.09x slower                                                                 |
| scimark_fft              | 285 ms                                                       | 310 ms: 1.09x slower                                                                  |
| float                    | 74.2 ms                                                      | 81.2 ms: 1.09x slower                                                                 |
| regex_dna                | 227 ms                                                       | 250 ms: 1.10x slower                                                                  |
| unpickle                 | 13.4 us                                                      | 15.0 us: 1.12x slower                                                                 |
| python_startup_no_site   | 7.76 ms                                                      | 8.68 ms: 1.12x slower                                                                 |
| pyflate                  | 449 ms                                                       | 508 ms: 1.13x slower                                                                  |
| richards                 | 48.3 ms                                                      | 54.8 ms: 1.13x slower                                                                 |
| pickle_list              | 3.83 us                                                      | 4.36 us: 1.14x slower                                                                 |
| telco                    | 6.86 ms                                                      | 7.99 ms: 1.17x slower                                                                 |
| python_startup           | 10.8 ms                                                      | 12.7 ms: 1.18x slower                                                                 |
| async_generators         | 316 ms                                                       | 395 ms: 1.25x slower                                                                  |
| scimark_sor              | 111 ms                                                       | 148 ms: 1.33x slower                                                                  |
| dask                     | 410 ms                                                       | 587 ms: 1.43x slower                                                                  |
| Geometric mean           | (ref)                                                        | 1.05x faster                                                                          |

Benchmark hidden because not significant (3): tornado_http, pickle_pure_python, richards_super
Ignored benchmarks (17) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509.json: 2to3, aiohttp, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 91.62% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
