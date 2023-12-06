
# Results vs. 3.12.0

- fork: python
- ref: v3.13.0a1
- machine: linux-x86_64
- commit hash: ad056f0
- commit date: 2023-10-13
- overall geometric mean: 1.03x slower \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.01x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231013-pythonperf2-x86_64-python-v3.13.0a1-3.13.0a1-ad056f0 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| 2to3           | 285 ms                                                       | 297 ms: 1.05x slower                                             |
| chameleon      | 7.27 ms                                                      | 7.78 ms: 1.07x slower                                            |
| docutils       | 2.89 sec                                                     | 2.88 sec: 1.01x faster                                           |
| Geometric mean | (ref)                                                        | 1.03x slower                                                     |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231013-pythonperf2-x86_64-python-v3.13.0a1-3.13.0a1-ad056f0 |
|----------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| async_tree_none            | 459 ms                                                       | 439 ms: 1.04x faster                                             |
| async_tree_cpu_io_mixed    | 704 ms                                                       | 713 ms: 1.01x slower                                             |
| async_tree_none_tg         | 440 ms                                                       | 447 ms: 1.02x slower                                             |
| async_tree_cpu_io_mixed_tg | 706 ms                                                       | 727 ms: 1.03x slower                                             |
| async_tree_memoization_tg  | 554 ms                                                       | 571 ms: 1.03x slower                                             |
| async_tree_io              | 1.06 sec                                                     | 1.09 sec: 1.03x slower                                           |
| async_tree_io_tg           | 1.07 sec                                                     | 1.11 sec: 1.03x slower                                           |
| Geometric mean             | (ref)                                                        | 1.01x slower                                                     |

Benchmark hidden because not significant (1): async_tree_memoization

Benchmarks with tag 'math':
===========================

Benchmark hidden because not significant (3): nbody, float, pidigits

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231013-pythonperf2-x86_64-python-v3.13.0a1-3.13.0a1-ad056f0 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| regex_effbot   | 3.61 ms                                                      | 3.55 ms: 1.02x faster                                            |
| regex_dna      | 240 ms                                                       | 241 ms: 1.00x slower                                             |
| regex_compile  | 145 ms                                                       | 150 ms: 1.04x slower                                             |
| regex_v8       | 24.4 ms                                                      | 26.2 ms: 1.07x slower                                            |
| Geometric mean | (ref)                                                        | 1.02x slower                                                     |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231013-pythonperf2-x86_64-python-v3.13.0a1-3.13.0a1-ad056f0 |
|----------------------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| unpickle             | 15.3 us                                                      | 14.3 us: 1.07x faster                                            |
| pickle_pure_python   | 319 us                                                       | 314 us: 1.02x faster                                             |
| unpickle_list        | 4.65 us                                                      | 4.61 us: 1.01x faster                                            |
| pickle               | 10.0 us                                                      | 10.1 us: 1.01x slower                                            |
| xml_etree_generate   | 85.3 ms                                                      | 87.3 ms: 1.02x slower                                            |
| xml_etree_process    | 58.3 ms                                                      | 59.9 ms: 1.03x slower                                            |
| pickle_dict          | 32.0 us                                                      | 32.9 us: 1.03x slower                                            |
| json_dumps           | 10.3 ms                                                      | 10.6 ms: 1.03x slower                                            |
| tomli_loads          | 2.17 sec                                                     | 2.24 sec: 1.03x slower                                           |
| xml_etree_parse      | 147 ms                                                       | 152 ms: 1.04x slower                                             |
| unpickle_pure_python | 210 us                                                       | 220 us: 1.05x slower                                             |
| pickle_list          | 4.22 us                                                      | 4.45 us: 1.06x slower                                            |
| xml_etree_iterparse  | 104 ms                                                       | 110 ms: 1.07x slower                                             |
| Geometric mean       | (ref)                                                        | 1.02x slower                                                     |

Benchmark hidden because not significant (1): json_loads

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231013-pythonperf2-x86_64-python-v3.13.0a1-3.13.0a1-ad056f0 |
|------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| python_startup_no_site | 8.67 ms                                                      | 8.70 ms: 1.00x slower                                            |
| python_startup         | 11.7 ms                                                      | 12.6 ms: 1.08x slower                                            |
| Geometric mean         | (ref)                                                        | 1.04x slower                                                     |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231013-pythonperf2-x86_64-python-v3.13.0a1-3.13.0a1-ad056f0 |
|-----------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| mako      | 10.1 ms                                                      | 10.4 ms: 1.03x slower                                            |

All benchmarks:
===============

| Benchmark                  | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231013-pythonperf2-x86_64-python-v3.13.0a1-3.13.0a1-ad056f0 |
|----------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| crypto_pyaes               | 82.4 ms                                                      | 73.4 ms: 1.12x faster                                            |
| raytrace                   | 301 ms                                                       | 276 ms: 1.09x faster                                             |
| unpack_sequence            | 54.5 ns                                                      | 50.9 ns: 1.07x faster                                            |
| unpickle                   | 15.3 us                                                      | 14.3 us: 1.07x faster                                            |
| generators                 | 37.3 ms                                                      | 35.4 ms: 1.06x faster                                            |
| bench_mp_pool              | 4.96 ms                                                      | 4.72 ms: 1.05x faster                                            |
| async_tree_none            | 459 ms                                                       | 439 ms: 1.04x faster                                             |
| asyncio_tcp                | 380 ms                                                       | 367 ms: 1.04x faster                                             |
| scimark_sparse_mat_mult    | 4.49 ms                                                      | 4.34 ms: 1.03x faster                                            |
| sqlglot_normalize          | 119 ms                                                       | 117 ms: 1.02x faster                                             |
| chaos                      | 64.1 ms                                                      | 62.7 ms: 1.02x faster                                            |
| coroutines                 | 23.1 ms                                                      | 22.6 ms: 1.02x faster                                            |
| regex_effbot               | 3.61 ms                                                      | 3.55 ms: 1.02x faster                                            |
| spectral_norm              | 93.9 ms                                                      | 92.3 ms: 1.02x faster                                            |
| pickle_pure_python         | 319 us                                                       | 314 us: 1.02x faster                                             |
| mdp                        | 2.56 sec                                                     | 2.52 sec: 1.01x faster                                           |
| comprehensions             | 21.8 us                                                      | 21.5 us: 1.01x faster                                            |
| json                       | 5.17 ms                                                      | 5.12 ms: 1.01x faster                                            |
| nqueens                    | 90.1 ms                                                      | 89.2 ms: 1.01x faster                                            |
| sympy_sum                  | 163 ms                                                       | 161 ms: 1.01x faster                                             |
| unpickle_list              | 4.65 us                                                      | 4.61 us: 1.01x faster                                            |
| deepcopy_reduce            | 3.41 us                                                      | 3.39 us: 1.01x faster                                            |
| docutils                   | 2.89 sec                                                     | 2.88 sec: 1.01x faster                                           |
| regex_dna                  | 240 ms                                                       | 241 ms: 1.00x slower                                             |
| python_startup_no_site     | 8.67 ms                                                      | 8.70 ms: 1.00x slower                                            |
| asyncio_tcp_ssl            | 1.57 sec                                                     | 1.58 sec: 1.00x slower                                           |
| sympy_str                  | 305 ms                                                       | 307 ms: 1.01x slower                                             |
| sympy_expand               | 492 ms                                                       | 494 ms: 1.01x slower                                             |
| sqlglot_optimize           | 58.4 ms                                                      | 58.8 ms: 1.01x slower                                            |
| sympy_integrate            | 24.0 ms                                                      | 24.2 ms: 1.01x slower                                            |
| pickle                     | 10.0 us                                                      | 10.1 us: 1.01x slower                                            |
| sqlglot_parse              | 1.41 ms                                                      | 1.42 ms: 1.01x slower                                            |
| async_tree_cpu_io_mixed    | 704 ms                                                       | 713 ms: 1.01x slower                                             |
| sqlglot_transpile          | 1.80 ms                                                      | 1.83 ms: 1.01x slower                                            |
| async_tree_none_tg         | 440 ms                                                       | 447 ms: 1.02x slower                                             |
| deepcopy                   | 371 us                                                       | 379 us: 1.02x slower                                             |
| scimark_monte_carlo        | 69.5 ms                                                      | 71.0 ms: 1.02x slower                                            |
| logging_format             | 7.29 us                                                      | 7.44 us: 1.02x slower                                            |
| mypy2                      | 365 ms                                                       | 373 ms: 1.02x slower                                             |
| logging_simple             | 6.64 us                                                      | 6.79 us: 1.02x slower                                            |
| xml_etree_generate         | 85.3 ms                                                      | 87.3 ms: 1.02x slower                                            |
| pprint_pformat             | 1.64 sec                                                     | 1.68 sec: 1.02x slower                                           |
| pprint_safe_repr           | 808 ms                                                       | 829 ms: 1.03x slower                                             |
| xml_etree_process          | 58.3 ms                                                      | 59.9 ms: 1.03x slower                                            |
| pickle_dict                | 32.0 us                                                      | 32.9 us: 1.03x slower                                            |
| pycparser                  | 1.29 sec                                                     | 1.33 sec: 1.03x slower                                           |
| async_tree_cpu_io_mixed_tg | 706 ms                                                       | 727 ms: 1.03x slower                                             |
| mako                       | 10.1 ms                                                      | 10.4 ms: 1.03x slower                                            |
| typing_runtime_protocols   | 150 us                                                       | 155 us: 1.03x slower                                             |
| async_tree_memoization_tg  | 554 ms                                                       | 571 ms: 1.03x slower                                             |
| pathlib                    | 18.7 ms                                                      | 19.3 ms: 1.03x slower                                            |
| json_dumps                 | 10.3 ms                                                      | 10.6 ms: 1.03x slower                                            |
| async_tree_io              | 1.06 sec                                                     | 1.09 sec: 1.03x slower                                           |
| tomli_loads                | 2.17 sec                                                     | 2.24 sec: 1.03x slower                                           |
| async_tree_io_tg           | 1.07 sec                                                     | 1.11 sec: 1.03x slower                                           |
| async_generators           | 385 ms                                                       | 399 ms: 1.03x slower                                             |
| meteor_contest             | 126 ms                                                       | 131 ms: 1.04x slower                                             |
| xml_etree_parse            | 147 ms                                                       | 152 ms: 1.04x slower                                             |
| scimark_fft                | 303 ms                                                       | 315 ms: 1.04x slower                                             |
| regex_compile              | 145 ms                                                       | 150 ms: 1.04x slower                                             |
| scimark_lu                 | 98.6 ms                                                      | 103 ms: 1.04x slower                                             |
| 2to3                       | 285 ms                                                       | 297 ms: 1.05x slower                                             |
| unpickle_pure_python       | 210 us                                                       | 220 us: 1.05x slower                                             |
| logging_silent             | 93.3 ns                                                      | 98.3 ns: 1.05x slower                                            |
| deepcopy_memo              | 36.6 us                                                      | 38.6 us: 1.05x slower                                            |
| pickle_list                | 4.22 us                                                      | 4.45 us: 1.06x slower                                            |
| xml_etree_iterparse        | 104 ms                                                       | 110 ms: 1.07x slower                                             |
| dulwich_log                | 64.9 ms                                                      | 69.2 ms: 1.07x slower                                            |
| gc_traversal               | 3.70 ms                                                      | 3.95 ms: 1.07x slower                                            |
| chameleon                  | 7.27 ms                                                      | 7.78 ms: 1.07x slower                                            |
| regex_v8                   | 24.4 ms                                                      | 26.2 ms: 1.07x slower                                            |
| python_startup             | 11.7 ms                                                      | 12.6 ms: 1.08x slower                                            |
| fannkuch                   | 362 ms                                                       | 396 ms: 1.09x slower                                             |
| hexiom                     | 5.97 ms                                                      | 6.54 ms: 1.09x slower                                            |
| deltablue                  | 3.24 ms                                                      | 3.66 ms: 1.13x slower                                            |
| telco                      | 7.16 ms                                                      | 8.25 ms: 1.15x slower                                            |
| go                         | 149 ms                                                       | 172 ms: 1.16x slower                                             |
| pyflate                    | 442 ms                                                       | 513 ms: 1.16x slower                                             |
| richards_super             | 50.8 ms                                                      | 61.7 ms: 1.21x slower                                            |
| richards                   | 45.1 ms                                                      | 55.4 ms: 1.23x slower                                            |
| coverage                   | 66.3 ms                                                      | 83.6 ms: 1.26x slower                                            |
| scimark_sor                | 107 ms                                                       | 149 ms: 1.40x slower                                             |
| Geometric mean             | (ref)                                                        | 1.03x slower                                                     |

Benchmark hidden because not significant (10): sqlite_synth, tornado_http, nbody, float, pidigits, json_loads, create_gc_cycles, bench_thread_pool, async_tree_memoization, asyncio_websockets
Ignored benchmarks (6) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, dask, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.01x
- 95% likely to have a slowdown of 1.01x
- 99% likely to have a slowdown of 1.01x
