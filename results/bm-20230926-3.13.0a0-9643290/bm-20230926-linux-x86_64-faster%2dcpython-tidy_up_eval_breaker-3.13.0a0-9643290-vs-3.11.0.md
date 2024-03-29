
# Results vs. 3.11.0

- fork: faster-cpython
- ref: tidy_up_eval_breaker
- machine: linux-x86_64
- commit hash: 9643290
- commit date: 2023-09-26
- overall geometric mean: 1.04x faster
- HPT reliability: 90.10%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230926-linux-x86_64-faster%2dcpython-tidy_up_eval_breaker-3.13.0a0-9643290 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------------------------:|
| docutils       | 2.63 sec                                               | 2.60 sec: 1.01x faster                                                          |
| Geometric mean | (ref)                                                  | 1.01x faster                                                                    |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230926-linux-x86_64-faster%2dcpython-tidy_up_eval_breaker-3.13.0a0-9643290 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------------------------:|
| pidigits       | 198 ms                                                 | 188 ms: 1.06x faster                                                            |
| nbody          | 93.1 ms                                                | 91.7 ms: 1.02x faster                                                           |
| float          | 77.2 ms                                                | 80.0 ms: 1.04x slower                                                           |
| Geometric mean | (ref)                                                  | 1.01x faster                                                                    |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230926-linux-x86_64-faster%2dcpython-tidy_up_eval_breaker-3.13.0a0-9643290 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------------------------:|
| regex_effbot   | 3.99 ms                                                | 3.57 ms: 1.12x faster                                                           |
| regex_compile  | 138 ms                                                 | 135 ms: 1.02x faster                                                            |
| regex_v8       | 22.0 ms                                                | 23.3 ms: 1.05x slower                                                           |
| regex_dna      | 204 ms                                                 | 215 ms: 1.06x slower                                                            |
| Geometric mean | (ref)                                                  | 1.01x faster                                                                    |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230926-linux-x86_64-faster%2dcpython-tidy_up_eval_breaker-3.13.0a0-9643290 |
|----------------------|:------------------------------------------------------:|:-------------------------------------------------------------------------------:|
| json_dumps           | 12.6 ms                                                | 9.94 ms: 1.27x faster                                                           |
| unpickle_pure_python | 228 us                                                 | 214 us: 1.07x faster                                                            |
| xml_etree_parse      | 158 ms                                                 | 151 ms: 1.05x faster                                                            |
| tomli_loads          | 2.22 sec                                               | 2.12 sec: 1.05x faster                                                          |
| json_loads           | 26.5 us                                                | 25.4 us: 1.04x faster                                                           |
| pickle_pure_python   | 306 us                                                 | 294 us: 1.04x faster                                                            |
| xml_etree_iterparse  | 104 ms                                                 | 102 ms: 1.02x faster                                                            |
| unpickle_list        | 4.91 us                                                | 4.83 us: 1.02x faster                                                           |
| pickle_dict          | 31.1 us                                                | 32.4 us: 1.04x slower                                                           |
| xml_etree_process    | 53.9 ms                                                | 57.1 ms: 1.06x slower                                                           |
| pickle               | 10.1 us                                                | 10.8 us: 1.08x slower                                                           |
| xml_etree_generate   | 76.2 ms                                                | 82.1 ms: 1.08x slower                                                           |
| unpickle             | 13.7 us                                                | 15.3 us: 1.12x slower                                                           |
| pickle_list          | 4.11 us                                                | 4.75 us: 1.16x slower                                                           |
| Geometric mean       | (ref)                                                  | 1.00x faster                                                                    |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230926-linux-x86_64-faster%2dcpython-tidy_up_eval_breaker-3.13.0a0-9643290 |
|------------------------|:------------------------------------------------------:|:-------------------------------------------------------------------------------:|
| python_startup_no_site | 6.01 ms                                                | 6.83 ms: 1.14x slower                                                           |
| python_startup         | 8.52 ms                                                | 10.1 ms: 1.18x slower                                                           |
| Geometric mean         | (ref)                                                  | 1.16x slower                                                                    |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230926-linux-x86_64-faster%2dcpython-tidy_up_eval_breaker-3.13.0a0-9643290 |
|-----------|:------------------------------------------------------:|:-------------------------------------------------------------------------------:|
| mako      | 10.1 ms                                                | 10.6 ms: 1.05x slower                                                           |

All benchmarks:
===============

| Benchmark                | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230926-linux-x86_64-faster%2dcpython-tidy_up_eval_breaker-3.13.0a0-9643290 |
|--------------------------|:------------------------------------------------------:|:-------------------------------------------------------------------------------:|
| typing_runtime_protocols | 486 us                                                 | 143 us: 3.39x faster                                                            |
| generators               | 73.5 ms                                                | 28.6 ms: 2.57x faster                                                           |
| asyncio_tcp              | 922 ms                                                 | 502 ms: 1.84x faster                                                            |
| asyncio_tcp_ssl          | 3.14 sec                                               | 1.80 sec: 1.74x faster                                                          |
| json_dumps               | 12.6 ms                                                | 9.94 ms: 1.27x faster                                                           |
| mypy2                    | 420 ms                                                 | 339 ms: 1.24x faster                                                            |
| async_tree_none          | 526 ms                                                 | 436 ms: 1.21x faster                                                            |
| coverage                 | 100 ms                                                 | 84.7 ms: 1.18x faster                                                           |
| coroutines               | 25.5 ms                                                | 22.2 ms: 1.15x faster                                                           |
| chaos                    | 69.2 ms                                                | 60.4 ms: 1.15x faster                                                           |
| deltablue                | 3.67 ms                                                | 3.27 ms: 1.12x faster                                                           |
| regex_effbot             | 3.99 ms                                                | 3.57 ms: 1.12x faster                                                           |
| async_tree_memoization   | 627 ms                                                 | 562 ms: 1.12x faster                                                            |
| sqlglot_parse            | 1.40 ms                                                | 1.26 ms: 1.11x faster                                                           |
| comprehensions           | 22.4 us                                                | 20.4 us: 1.10x faster                                                           |
| raytrace                 | 297 ms                                                 | 271 ms: 1.09x faster                                                            |
| async_tree_io            | 1.30 sec                                               | 1.19 sec: 1.09x faster                                                          |
| sqlglot_transpile        | 1.70 ms                                                | 1.57 ms: 1.08x faster                                                           |
| crypto_pyaes             | 74.7 ms                                                | 70.1 ms: 1.07x faster                                                           |
| unpickle_pure_python     | 228 us                                                 | 214 us: 1.07x faster                                                            |
| richards_super           | 56.8 ms                                                | 53.6 ms: 1.06x faster                                                           |
| hexiom                   | 6.37 ms                                                | 6.02 ms: 1.06x faster                                                           |
| pidigits                 | 198 ms                                                 | 188 ms: 1.06x faster                                                            |
| async_tree_cpu_io_mixed  | 739 ms                                                 | 702 ms: 1.05x faster                                                            |
| xml_etree_parse          | 158 ms                                                 | 151 ms: 1.05x faster                                                            |
| tomli_loads              | 2.22 sec                                               | 2.12 sec: 1.05x faster                                                          |
| json_loads               | 26.5 us                                                | 25.4 us: 1.04x faster                                                           |
| nqueens                  | 83.4 ms                                                | 80.1 ms: 1.04x faster                                                           |
| pickle_pure_python       | 306 us                                                 | 294 us: 1.04x faster                                                            |
| sqlglot_normalize        | 108 ms                                                 | 104 ms: 1.04x faster                                                            |
| json                     | 4.94 ms                                                | 4.78 ms: 1.03x faster                                                           |
| logging_simple           | 6.03 us                                                | 5.86 us: 1.03x faster                                                           |
| logging_format           | 6.68 us                                                | 6.52 us: 1.03x faster                                                           |
| regex_compile            | 138 ms                                                 | 135 ms: 1.02x faster                                                            |
| scimark_monte_carlo      | 68.1 ms                                                | 66.7 ms: 1.02x faster                                                           |
| xml_etree_iterparse      | 104 ms                                                 | 102 ms: 1.02x faster                                                            |
| meteor_contest           | 107 ms                                                 | 105 ms: 1.02x faster                                                            |
| unpickle_list            | 4.91 us                                                | 4.83 us: 1.02x faster                                                           |
| sqlglot_optimize         | 53.1 ms                                                | 52.3 ms: 1.02x faster                                                           |
| nbody                    | 93.1 ms                                                | 91.7 ms: 1.02x faster                                                           |
| bench_thread_pool        | 819 us                                                 | 809 us: 1.01x faster                                                            |
| gc_traversal             | 4.02 ms                                                | 3.97 ms: 1.01x faster                                                           |
| docutils                 | 2.63 sec                                               | 2.60 sec: 1.01x faster                                                          |
| deepcopy_memo            | 37.0 us                                                | 36.7 us: 1.01x faster                                                           |
| go                       | 140 ms                                                 | 139 ms: 1.00x faster                                                            |
| fannkuch                 | 388 ms                                                 | 386 ms: 1.00x faster                                                            |
| mdp                      | 2.62 sec                                               | 2.63 sec: 1.00x slower                                                          |
| scimark_lu               | 110 ms                                                 | 111 ms: 1.01x slower                                                            |
| deepcopy                 | 342 us                                                 | 346 us: 1.01x slower                                                            |
| pprint_safe_repr         | 701 ms                                                 | 715 ms: 1.02x slower                                                            |
| pathlib                  | 18.2 ms                                                | 18.6 ms: 1.02x slower                                                           |
| scimark_sor              | 118 ms                                                 | 121 ms: 1.02x slower                                                            |
| create_gc_cycles         | 1.49 ms                                                | 1.54 ms: 1.03x slower                                                           |
| float                    | 77.2 ms                                                | 80.0 ms: 1.04x slower                                                           |
| richards                 | 45.7 ms                                                | 47.5 ms: 1.04x slower                                                           |
| dulwich_log              | 63.7 ms                                                | 66.3 ms: 1.04x slower                                                           |
| pickle_dict              | 31.1 us                                                | 32.4 us: 1.04x slower                                                           |
| deepcopy_reduce          | 2.94 us                                                | 3.07 us: 1.04x slower                                                           |
| mako                     | 10.1 ms                                                | 10.6 ms: 1.05x slower                                                           |
| scimark_sparse_mat_mult  | 4.50 ms                                                | 4.74 ms: 1.05x slower                                                           |
| regex_v8                 | 22.0 ms                                                | 23.3 ms: 1.05x slower                                                           |
| regex_dna                | 204 ms                                                 | 215 ms: 1.06x slower                                                            |
| xml_etree_process        | 53.9 ms                                                | 57.1 ms: 1.06x slower                                                           |
| spectral_norm            | 100 ms                                                 | 107 ms: 1.07x slower                                                            |
| pickle                   | 10.1 us                                                | 10.8 us: 1.08x slower                                                           |
| xml_etree_generate       | 76.2 ms                                                | 82.1 ms: 1.08x slower                                                           |
| sqlite_synth             | 2.52 us                                                | 2.73 us: 1.09x slower                                                           |
| pyflate                  | 418 ms                                                 | 461 ms: 1.10x slower                                                            |
| scimark_fft              | 328 ms                                                 | 366 ms: 1.11x slower                                                            |
| unpickle                 | 13.7 us                                                | 15.3 us: 1.12x slower                                                           |
| python_startup_no_site   | 6.01 ms                                                | 6.83 ms: 1.14x slower                                                           |
| pickle_list              | 4.11 us                                                | 4.75 us: 1.16x slower                                                           |
| unpack_sequence          | 43.1 ns                                                | 50.5 ns: 1.17x slower                                                           |
| python_startup           | 8.52 ms                                                | 10.1 ms: 1.18x slower                                                           |
| async_generators         | 368 ms                                                 | 444 ms: 1.21x slower                                                            |
| telco                    | 6.58 ms                                                | 8.10 ms: 1.23x slower                                                           |
| dask                     | 360 ms                                                 | 528 ms: 1.47x slower                                                            |
| Geometric mean           | (ref)                                                  | 1.04x faster                                                                    |

Benchmark hidden because not significant (5): tornado_http, pycparser, bench_mp_pool, logging_silent, pprint_pformat
Ignored benchmarks (18) of results/bm-20221024-3.11.0-deaf509/bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509.json: 2to3, aiohttp, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 90.10% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
