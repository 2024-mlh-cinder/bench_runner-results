
# Results vs. 3.11.0

- fork: python
- ref: v3.13.0a1
- machine: linux-x86_64
- commit hash: ad056f0
- commit date: 2023-10-13
- overall geometric mean: 1.05x faster \*
- HPT reliability: 96.55%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231013-pythonperf2-x86_64-python-v3.13.0a1-3.13.0a1-ad056f0 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| 2to3           | 286 ms                                                       | 297 ms: 1.04x slower                                             |
| chameleon      | 7.42 ms                                                      | 7.78 ms: 1.05x slower                                            |
| docutils       | 2.87 sec                                                     | 2.88 sec: 1.00x slower                                           |
| tornado_http   | 125 ms                                                       | 121 ms: 1.03x faster                                             |
| Geometric mean | (ref)                                                        | 1.02x slower                                                     |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231013-pythonperf2-x86_64-python-v3.13.0a1-3.13.0a1-ad056f0 |
|----------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| async_tree_none            | 529 ms                                                       | 439 ms: 1.20x faster                                             |
| async_tree_memoization     | 648 ms                                                       | 557 ms: 1.16x faster                                             |
| async_tree_io              | 1.19 sec                                                     | 1.09 sec: 1.09x faster                                           |
| async_tree_none_tg         | 482 ms                                                       | 447 ms: 1.08x faster                                             |
| async_tree_cpu_io_mixed    | 762 ms                                                       | 713 ms: 1.07x faster                                             |
| async_tree_memoization_tg  | 605 ms                                                       | 571 ms: 1.06x faster                                             |
| async_tree_io_tg           | 1.17 sec                                                     | 1.11 sec: 1.06x faster                                           |
| async_tree_cpu_io_mixed_tg | 760 ms                                                       | 727 ms: 1.05x faster                                             |
| Geometric mean             | (ref)                                                        | 1.09x faster                                                     |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231013-pythonperf2-x86_64-python-v3.13.0a1-3.13.0a1-ad056f0 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| nbody          | 95.8 ms                                                      | 87.7 ms: 1.09x faster                                            |
| pidigits       | 251 ms                                                       | 264 ms: 1.05x slower                                             |
| float          | 76.0 ms                                                      | 81.5 ms: 1.07x slower                                            |
| Geometric mean | (ref)                                                        | 1.01x slower                                                     |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231013-pythonperf2-x86_64-python-v3.13.0a1-3.13.0a1-ad056f0 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| regex_compile  | 157 ms                                                       | 150 ms: 1.05x faster                                             |
| regex_effbot   | 3.42 ms                                                      | 3.55 ms: 1.04x slower                                            |
| regex_dna      | 226 ms                                                       | 241 ms: 1.06x slower                                             |
| regex_v8       | 23.7 ms                                                      | 26.2 ms: 1.11x slower                                            |
| Geometric mean | (ref)                                                        | 1.04x slower                                                     |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231013-pythonperf2-x86_64-python-v3.13.0a1-3.13.0a1-ad056f0 |
|----------------------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| json_dumps           | 13.5 ms                                                      | 10.6 ms: 1.27x faster                                            |
| json_loads           | 29.0 us                                                      | 24.3 us: 1.19x faster                                            |
| unpickle_pure_python | 236 us                                                       | 220 us: 1.07x faster                                             |
| xml_etree_parse      | 159 ms                                                       | 152 ms: 1.04x faster                                             |
| tomli_loads          | 2.27 sec                                                     | 2.24 sec: 1.01x faster                                           |
| pickle_pure_python   | 318 us                                                       | 314 us: 1.01x faster                                             |
| unpickle_list        | 4.47 us                                                      | 4.61 us: 1.03x slower                                            |
| pickle_dict          | 31.8 us                                                      | 32.9 us: 1.04x slower                                            |
| pickle               | 9.77 us                                                      | 10.1 us: 1.04x slower                                            |
| xml_etree_iterparse  | 106 ms                                                       | 110 ms: 1.04x slower                                             |
| xml_etree_process    | 56.1 ms                                                      | 59.9 ms: 1.07x slower                                            |
| unpickle             | 13.2 us                                                      | 14.3 us: 1.08x slower                                            |
| xml_etree_generate   | 80.5 ms                                                      | 87.3 ms: 1.08x slower                                            |
| pickle_list          | 3.89 us                                                      | 4.45 us: 1.14x slower                                            |
| Geometric mean       | (ref)                                                        | 1.00x faster                                                     |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231013-pythonperf2-x86_64-python-v3.13.0a1-3.13.0a1-ad056f0 |
|------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| python_startup_no_site | 7.78 ms                                                      | 8.70 ms: 1.12x slower                                            |
| python_startup         | 10.8 ms                                                      | 12.6 ms: 1.17x slower                                            |
| Geometric mean         | (ref)                                                        | 1.14x slower                                                     |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231013-pythonperf2-x86_64-python-v3.13.0a1-3.13.0a1-ad056f0 |
|-----------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| mako      | 11.0 ms                                                      | 10.4 ms: 1.06x faster                                            |

All benchmarks:
===============

| Benchmark                  | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231013-pythonperf2-x86_64-python-v3.13.0a1-3.13.0a1-ad056f0 |
|----------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| typing_runtime_protocols   | 527 us                                                       | 155 us: 3.41x faster                                             |
| asyncio_tcp                | 752 ms                                                       | 367 ms: 2.05x faster                                             |
| asyncio_tcp_ssl            | 3.09 sec                                                     | 1.58 sec: 1.96x faster                                           |
| generators                 | 56.4 ms                                                      | 35.4 ms: 1.59x faster                                            |
| json_dumps                 | 13.5 ms                                                      | 10.6 ms: 1.27x faster                                            |
| coroutines                 | 27.9 ms                                                      | 22.6 ms: 1.23x faster                                            |
| mypy2                      | 449 ms                                                       | 373 ms: 1.20x faster                                             |
| async_tree_none            | 529 ms                                                       | 439 ms: 1.20x faster                                             |
| json_loads                 | 29.0 us                                                      | 24.3 us: 1.19x faster                                            |
| async_tree_memoization     | 648 ms                                                       | 557 ms: 1.16x faster                                             |
| fannkuch                   | 457 ms                                                       | 396 ms: 1.16x faster                                             |
| comprehensions             | 24.8 us                                                      | 21.5 us: 1.15x faster                                            |
| sympy_sum                  | 184 ms                                                       | 161 ms: 1.14x faster                                             |
| chaos                      | 71.6 ms                                                      | 62.7 ms: 1.14x faster                                            |
| scimark_lu                 | 115 ms                                                       | 103 ms: 1.12x faster                                             |
| raytrace                   | 308 ms                                                       | 276 ms: 1.12x faster                                             |
| crypto_pyaes               | 81.8 ms                                                      | 73.4 ms: 1.11x faster                                            |
| sympy_expand               | 550 ms                                                       | 494 ms: 1.11x faster                                             |
| nqueens                    | 99.2 ms                                                      | 89.2 ms: 1.11x faster                                            |
| deltablue                  | 4.03 ms                                                      | 3.66 ms: 1.10x faster                                            |
| sympy_str                  | 336 ms                                                       | 307 ms: 1.09x faster                                             |
| json                       | 5.59 ms                                                      | 5.12 ms: 1.09x faster                                            |
| nbody                      | 95.8 ms                                                      | 87.7 ms: 1.09x faster                                            |
| sqlglot_parse              | 1.55 ms                                                      | 1.42 ms: 1.09x faster                                            |
| async_tree_io              | 1.19 sec                                                     | 1.09 sec: 1.09x faster                                           |
| mdp                        | 2.72 sec                                                     | 2.52 sec: 1.08x faster                                           |
| async_tree_none_tg         | 482 ms                                                       | 447 ms: 1.08x faster                                             |
| unpickle_pure_python       | 236 us                                                       | 220 us: 1.07x faster                                             |
| async_tree_cpu_io_mixed    | 762 ms                                                       | 713 ms: 1.07x faster                                             |
| hexiom                     | 6.97 ms                                                      | 6.54 ms: 1.07x faster                                            |
| logging_simple             | 7.21 us                                                      | 6.79 us: 1.06x faster                                            |
| mako                       | 11.0 ms                                                      | 10.4 ms: 1.06x faster                                            |
| bench_thread_pool          | 1.02 ms                                                      | 961 us: 1.06x faster                                             |
| async_tree_memoization_tg  | 605 ms                                                       | 571 ms: 1.06x faster                                             |
| sqlglot_transpile          | 1.94 ms                                                      | 1.83 ms: 1.06x faster                                            |
| async_tree_io_tg           | 1.17 sec                                                     | 1.11 sec: 1.06x faster                                           |
| sympy_integrate            | 25.6 ms                                                      | 24.2 ms: 1.06x faster                                            |
| richards_super             | 65.2 ms                                                      | 61.7 ms: 1.06x faster                                            |
| logging_format             | 7.83 us                                                      | 7.44 us: 1.05x faster                                            |
| async_tree_cpu_io_mixed_tg | 760 ms                                                       | 727 ms: 1.05x faster                                             |
| sqlglot_normalize          | 122 ms                                                       | 117 ms: 1.05x faster                                             |
| regex_compile              | 157 ms                                                       | 150 ms: 1.05x faster                                             |
| xml_etree_parse            | 159 ms                                                       | 152 ms: 1.04x faster                                             |
| logging_silent             | 102 ns                                                       | 98.3 ns: 1.04x faster                                            |
| tornado_http               | 125 ms                                                       | 121 ms: 1.03x faster                                             |
| gc_traversal               | 4.06 ms                                                      | 3.95 ms: 1.03x faster                                            |
| deepcopy                   | 389 us                                                       | 379 us: 1.03x faster                                             |
| spectral_norm              | 94.0 ms                                                      | 92.3 ms: 1.02x faster                                            |
| tomli_loads                | 2.27 sec                                                     | 2.24 sec: 1.01x faster                                           |
| pickle_pure_python         | 318 us                                                       | 314 us: 1.01x faster                                             |
| sqlglot_optimize           | 59.2 ms                                                      | 58.8 ms: 1.01x faster                                            |
| docutils                   | 2.87 sec                                                     | 2.88 sec: 1.00x slower                                           |
| meteor_contest             | 130 ms                                                       | 131 ms: 1.00x slower                                             |
| scimark_monte_carlo        | 70.6 ms                                                      | 71.0 ms: 1.01x slower                                            |
| deepcopy_reduce            | 3.37 us                                                      | 3.39 us: 1.01x slower                                            |
| pathlib                    | 19.1 ms                                                      | 19.3 ms: 1.01x slower                                            |
| dulwich_log                | 68.3 ms                                                      | 69.2 ms: 1.01x slower                                            |
| unpickle_list              | 4.47 us                                                      | 4.61 us: 1.03x slower                                            |
| pprint_pformat             | 1.63 sec                                                     | 1.68 sec: 1.03x slower                                           |
| deepcopy_memo              | 37.3 us                                                      | 38.6 us: 1.03x slower                                            |
| pickle_dict                | 31.8 us                                                      | 32.9 us: 1.04x slower                                            |
| pickle                     | 9.77 us                                                      | 10.1 us: 1.04x slower                                            |
| pycparser                  | 1.28 sec                                                     | 1.33 sec: 1.04x slower                                           |
| go                         | 166 ms                                                       | 172 ms: 1.04x slower                                             |
| regex_effbot               | 3.42 ms                                                      | 3.55 ms: 1.04x slower                                            |
| 2to3                       | 286 ms                                                       | 297 ms: 1.04x slower                                             |
| xml_etree_iterparse        | 106 ms                                                       | 110 ms: 1.04x slower                                             |
| chameleon                  | 7.42 ms                                                      | 7.78 ms: 1.05x slower                                            |
| pidigits                   | 251 ms                                                       | 264 ms: 1.05x slower                                             |
| pprint_safe_repr           | 780 ms                                                       | 829 ms: 1.06x slower                                             |
| regex_dna                  | 226 ms                                                       | 241 ms: 1.06x slower                                             |
| xml_etree_process          | 56.1 ms                                                      | 59.9 ms: 1.07x slower                                            |
| float                      | 76.0 ms                                                      | 81.5 ms: 1.07x slower                                            |
| scimark_sparse_mat_mult    | 4.04 ms                                                      | 4.34 ms: 1.08x slower                                            |
| unpickle                   | 13.2 us                                                      | 14.3 us: 1.08x slower                                            |
| xml_etree_generate         | 80.5 ms                                                      | 87.3 ms: 1.08x slower                                            |
| sqlite_synth               | 2.49 us                                                      | 2.70 us: 1.09x slower                                            |
| regex_v8                   | 23.7 ms                                                      | 26.2 ms: 1.11x slower                                            |
| richards                   | 49.9 ms                                                      | 55.4 ms: 1.11x slower                                            |
| python_startup_no_site     | 7.78 ms                                                      | 8.70 ms: 1.12x slower                                            |
| scimark_fft                | 281 ms                                                       | 315 ms: 1.12x slower                                             |
| pyflate                    | 453 ms                                                       | 513 ms: 1.13x slower                                             |
| unpack_sequence            | 44.9 ns                                                      | 50.9 ns: 1.13x slower                                            |
| pickle_list                | 3.89 us                                                      | 4.45 us: 1.14x slower                                            |
| python_startup             | 10.8 ms                                                      | 12.6 ms: 1.17x slower                                            |
| telco                      | 6.91 ms                                                      | 8.25 ms: 1.19x slower                                            |
| async_generators           | 322 ms                                                       | 399 ms: 1.24x slower                                             |
| coverage                   | 66.6 ms                                                      | 83.6 ms: 1.25x slower                                            |
| scimark_sor                | 109 ms                                                       | 149 ms: 1.36x slower                                             |
| Geometric mean             | (ref)                                                        | 1.05x faster                                                     |

Benchmark hidden because not significant (3): create_gc_cycles, asyncio_websockets, bench_mp_pool
Ignored benchmarks (12) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, dask, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift


# HPT report

- Reliability score: 96.55% likely to be faster
- 90% likely to have a speedup of 1.01x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
