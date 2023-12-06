
# Results vs. 3.11.0

- fork: faster-cpython
- ref: tidy_up_eval_breaker
- machine: linux-x86_64
- commit hash: 2b8766e
- commit date: 2023-09-13
- overall geometric mean: 1.05x faster
- HPT reliability: 88.49%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230913-linux-x86_64-faster%2dcpython-tidy_up_eval_breaker-3.13.0a0-2b8766e |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------------------------:|
| docutils       | 2.63 sec                                               | 2.60 sec: 1.01x faster                                                          |
| tornado_http   | 96.3 ms                                                | 95.1 ms: 1.01x faster                                                           |
| Geometric mean | (ref)                                                  | 1.01x faster                                                                    |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230913-linux-x86_64-faster%2dcpython-tidy_up_eval_breaker-3.13.0a0-2b8766e |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------------------------:|
| pidigits       | 198 ms                                                 | 187 ms: 1.06x faster                                                            |
| nbody          | 93.1 ms                                                | 88.7 ms: 1.05x faster                                                           |
| float          | 77.2 ms                                                | 80.2 ms: 1.04x slower                                                           |
| Geometric mean | (ref)                                                  | 1.02x faster                                                                    |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230913-linux-x86_64-faster%2dcpython-tidy_up_eval_breaker-3.13.0a0-2b8766e |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------------------------:|
| regex_effbot   | 3.99 ms                                                | 3.43 ms: 1.16x faster                                                           |
| regex_compile  | 138 ms                                                 | 136 ms: 1.02x faster                                                            |
| regex_dna      | 204 ms                                                 | 209 ms: 1.02x slower                                                            |
| regex_v8       | 22.0 ms                                                | 23.6 ms: 1.07x slower                                                           |
| Geometric mean | (ref)                                                  | 1.02x faster                                                                    |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230913-linux-x86_64-faster%2dcpython-tidy_up_eval_breaker-3.13.0a0-2b8766e |
|----------------------|:------------------------------------------------------:|:-------------------------------------------------------------------------------:|
| json_dumps           | 12.6 ms                                                | 9.76 ms: 1.29x faster                                                           |
| tomli_loads          | 2.22 sec                                               | 2.08 sec: 1.07x faster                                                          |
| json_loads           | 26.5 us                                                | 25.2 us: 1.05x faster                                                           |
| xml_etree_parse      | 158 ms                                                 | 151 ms: 1.05x faster                                                            |
| unpickle_pure_python | 228 us                                                 | 218 us: 1.04x faster                                                            |
| unpickle_list        | 4.91 us                                                | 4.74 us: 1.03x faster                                                           |
| xml_etree_iterparse  | 104 ms                                                 | 102 ms: 1.02x faster                                                            |
| pickle_pure_python   | 306 us                                                 | 303 us: 1.01x faster                                                            |
| pickle_dict          | 31.1 us                                                | 31.4 us: 1.01x slower                                                           |
| pickle               | 10.1 us                                                | 10.7 us: 1.06x slower                                                           |
| xml_etree_process    | 53.9 ms                                                | 57.4 ms: 1.07x slower                                                           |
| xml_etree_generate   | 76.2 ms                                                | 83.9 ms: 1.10x slower                                                           |
| pickle_list          | 4.11 us                                                | 4.54 us: 1.10x slower                                                           |
| Geometric mean       | (ref)                                                  | 1.01x faster                                                                    |

Benchmark hidden because not significant (1): unpickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230913-linux-x86_64-faster%2dcpython-tidy_up_eval_breaker-3.13.0a0-2b8766e |
|------------------------|:------------------------------------------------------:|:-------------------------------------------------------------------------------:|
| python_startup_no_site | 6.01 ms                                                | 6.84 ms: 1.14x slower                                                           |
| python_startup         | 8.52 ms                                                | 10.1 ms: 1.18x slower                                                           |
| Geometric mean         | (ref)                                                  | 1.16x slower                                                                    |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230913-linux-x86_64-faster%2dcpython-tidy_up_eval_breaker-3.13.0a0-2b8766e |
|-----------|:------------------------------------------------------:|:-------------------------------------------------------------------------------:|
| mako      | 10.1 ms                                                | 10.8 ms: 1.07x slower                                                           |

All benchmarks:
===============

| Benchmark                | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230913-linux-x86_64-faster%2dcpython-tidy_up_eval_breaker-3.13.0a0-2b8766e |
|--------------------------|:------------------------------------------------------:|:-------------------------------------------------------------------------------:|
| typing_runtime_protocols | 486 us                                                 | 144 us: 3.38x faster                                                            |
| generators               | 73.5 ms                                                | 29.3 ms: 2.50x faster                                                           |
| asyncio_tcp              | 922 ms                                                 | 488 ms: 1.89x faster                                                            |
| asyncio_tcp_ssl          | 3.14 sec                                               | 1.79 sec: 1.75x faster                                                          |
| json_dumps               | 12.6 ms                                                | 9.76 ms: 1.29x faster                                                           |
| mypy2                    | 420 ms                                                 | 338 ms: 1.24x faster                                                            |
| async_tree_none          | 526 ms                                                 | 435 ms: 1.21x faster                                                            |
| coverage                 | 100 ms                                                 | 85.0 ms: 1.18x faster                                                           |
| coroutines               | 25.5 ms                                                | 21.9 ms: 1.16x faster                                                           |
| regex_effbot             | 3.99 ms                                                | 3.43 ms: 1.16x faster                                                           |
| chaos                    | 69.2 ms                                                | 60.4 ms: 1.14x faster                                                           |
| deltablue                | 3.67 ms                                                | 3.27 ms: 1.12x faster                                                           |
| async_tree_memoization   | 627 ms                                                 | 561 ms: 1.12x faster                                                            |
| sqlglot_parse            | 1.40 ms                                                | 1.27 ms: 1.10x faster                                                           |
| async_tree_io            | 1.30 sec                                               | 1.18 sec: 1.10x faster                                                          |
| comprehensions           | 22.4 us                                                | 20.5 us: 1.09x faster                                                           |
| raytrace                 | 297 ms                                                 | 272 ms: 1.09x faster                                                            |
| crypto_pyaes             | 74.7 ms                                                | 69.4 ms: 1.08x faster                                                           |
| sqlglot_transpile        | 1.70 ms                                                | 1.59 ms: 1.07x faster                                                           |
| tomli_loads              | 2.22 sec                                               | 2.08 sec: 1.07x faster                                                          |
| pidigits                 | 198 ms                                                 | 187 ms: 1.06x faster                                                            |
| hexiom                   | 6.37 ms                                                | 6.05 ms: 1.05x faster                                                           |
| nbody                    | 93.1 ms                                                | 88.7 ms: 1.05x faster                                                           |
| json_loads               | 26.5 us                                                | 25.2 us: 1.05x faster                                                           |
| async_tree_cpu_io_mixed  | 739 ms                                                 | 705 ms: 1.05x faster                                                            |
| xml_etree_parse          | 158 ms                                                 | 151 ms: 1.05x faster                                                            |
| json                     | 4.94 ms                                                | 4.73 ms: 1.04x faster                                                           |
| unpickle_pure_python     | 228 us                                                 | 218 us: 1.04x faster                                                            |
| gc_traversal             | 4.02 ms                                                | 3.86 ms: 1.04x faster                                                           |
| nqueens                  | 83.4 ms                                                | 80.4 ms: 1.04x faster                                                           |
| unpickle_list            | 4.91 us                                                | 4.74 us: 1.03x faster                                                           |
| sqlglot_normalize        | 108 ms                                                 | 104 ms: 1.03x faster                                                            |
| logging_format           | 6.68 us                                                | 6.49 us: 1.03x faster                                                           |
| scimark_monte_carlo      | 68.1 ms                                                | 66.2 ms: 1.03x faster                                                           |
| richards_super           | 56.8 ms                                                | 55.3 ms: 1.03x faster                                                           |
| unpack_sequence          | 43.1 ns                                                | 42.1 ns: 1.02x faster                                                           |
| logging_simple           | 6.03 us                                                | 5.92 us: 1.02x faster                                                           |
| xml_etree_iterparse      | 104 ms                                                 | 102 ms: 1.02x faster                                                            |
| pycparser                | 1.18 sec                                               | 1.16 sec: 1.02x faster                                                          |
| regex_compile            | 138 ms                                                 | 136 ms: 1.02x faster                                                            |
| sqlglot_optimize         | 53.1 ms                                                | 52.4 ms: 1.01x faster                                                           |
| bench_thread_pool        | 819 us                                                 | 808 us: 1.01x faster                                                            |
| tornado_http             | 96.3 ms                                                | 95.1 ms: 1.01x faster                                                           |
| meteor_contest           | 107 ms                                                 | 105 ms: 1.01x faster                                                            |
| pickle_pure_python       | 306 us                                                 | 303 us: 1.01x faster                                                            |
| docutils                 | 2.63 sec                                               | 2.60 sec: 1.01x faster                                                          |
| pathlib                  | 18.2 ms                                                | 18.3 ms: 1.00x slower                                                           |
| fannkuch                 | 388 ms                                                 | 390 ms: 1.01x slower                                                            |
| go                       | 140 ms                                                 | 141 ms: 1.01x slower                                                            |
| pickle_dict              | 31.1 us                                                | 31.4 us: 1.01x slower                                                           |
| logging_silent           | 101 ns                                                 | 102 ns: 1.01x slower                                                            |
| pprint_pformat           | 1.46 sec                                               | 1.47 sec: 1.01x slower                                                          |
| deepcopy                 | 342 us                                                 | 347 us: 1.02x slower                                                            |
| mdp                      | 2.62 sec                                               | 2.67 sec: 1.02x slower                                                          |
| regex_dna                | 204 ms                                                 | 209 ms: 1.02x slower                                                            |
| scimark_sor              | 118 ms                                                 | 121 ms: 1.03x slower                                                            |
| pprint_safe_repr         | 701 ms                                                 | 724 ms: 1.03x slower                                                            |
| create_gc_cycles         | 1.49 ms                                                | 1.54 ms: 1.04x slower                                                           |
| float                    | 77.2 ms                                                | 80.2 ms: 1.04x slower                                                           |
| scimark_sparse_mat_mult  | 4.50 ms                                                | 4.69 ms: 1.04x slower                                                           |
| dulwich_log              | 63.7 ms                                                | 66.6 ms: 1.05x slower                                                           |
| pickle                   | 10.1 us                                                | 10.7 us: 1.06x slower                                                           |
| richards                 | 45.7 ms                                                | 48.6 ms: 1.06x slower                                                           |
| xml_etree_process        | 53.9 ms                                                | 57.4 ms: 1.07x slower                                                           |
| spectral_norm            | 100 ms                                                 | 107 ms: 1.07x slower                                                            |
| deepcopy_reduce          | 2.94 us                                                | 3.14 us: 1.07x slower                                                           |
| regex_v8                 | 22.0 ms                                                | 23.6 ms: 1.07x slower                                                           |
| mako                     | 10.1 ms                                                | 10.8 ms: 1.07x slower                                                           |
| sqlite_synth             | 2.52 us                                                | 2.71 us: 1.08x slower                                                           |
| pyflate                  | 418 ms                                                 | 457 ms: 1.09x slower                                                            |
| scimark_fft              | 328 ms                                                 | 361 ms: 1.10x slower                                                            |
| xml_etree_generate       | 76.2 ms                                                | 83.9 ms: 1.10x slower                                                           |
| pickle_list              | 4.11 us                                                | 4.54 us: 1.10x slower                                                           |
| python_startup_no_site   | 6.01 ms                                                | 6.84 ms: 1.14x slower                                                           |
| python_startup           | 8.52 ms                                                | 10.1 ms: 1.18x slower                                                           |
| async_generators         | 368 ms                                                 | 442 ms: 1.20x slower                                                            |
| telco                    | 6.58 ms                                                | 7.97 ms: 1.21x slower                                                           |
| dask                     | 360 ms                                                 | 525 ms: 1.46x slower                                                            |
| Geometric mean           | (ref)                                                  | 1.05x faster                                                                    |

Benchmark hidden because not significant (4): bench_mp_pool, deepcopy_memo, scimark_lu, unpickle
Ignored benchmarks (18) of results/bm-20221024-3.11.0-deaf509/bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509.json: 2to3, aiohttp, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 88.49% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
