
# Results vs. 3.11.0

- fork: python
- ref: main
- machine: linux-x86_64
- commit hash: ce6a533
- commit date: 2023-11-12
- overall geometric mean: 1.05x slower \*
- HPT reliability: 99.58%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231112-pythonperf2-x86_64-python-main-3.13.0a1+-ce6a533 |
|----------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| 2to3           | 286 ms                                                       | 323 ms: 1.13x slower                                         |
| chameleon      | 7.42 ms                                                      | 7.93 ms: 1.07x slower                                        |
| docutils       | 2.87 sec                                                     | 2.99 sec: 1.04x slower                                       |
| tornado_http   | 125 ms                                                       | 127 ms: 1.01x slower                                         |
| Geometric mean | (ref)                                                        | 1.06x slower                                                 |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231112-pythonperf2-x86_64-python-main-3.13.0a1+-ce6a533 |
|----------------------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| async_tree_none            | 529 ms                                                       | 468 ms: 1.13x faster                                         |
| async_tree_memoization     | 648 ms                                                       | 581 ms: 1.11x faster                                         |
| async_tree_io              | 1.19 sec                                                     | 1.13 sec: 1.05x faster                                       |
| async_tree_cpu_io_mixed    | 762 ms                                                       | 731 ms: 1.04x faster                                         |
| async_tree_memoization_tg  | 605 ms                                                       | 583 ms: 1.04x faster                                         |
| async_tree_io_tg           | 1.17 sec                                                     | 1.15 sec: 1.02x faster                                       |
| async_tree_none_tg         | 482 ms                                                       | 474 ms: 1.02x faster                                         |
| async_tree_cpu_io_mixed_tg | 760 ms                                                       | 747 ms: 1.02x faster                                         |
| Geometric mean             | (ref)                                                        | 1.05x faster                                                 |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231112-pythonperf2-x86_64-python-main-3.13.0a1+-ce6a533 |
|----------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| pidigits       | 251 ms                                                       | 266 ms: 1.06x slower                                         |
| nbody          | 95.8 ms                                                      | 129 ms: 1.34x slower                                         |
| float          | 76.0 ms                                                      | 116 ms: 1.52x slower                                         |
| Geometric mean | (ref)                                                        | 1.29x slower                                                 |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231112-pythonperf2-x86_64-python-main-3.13.0a1+-ce6a533 |
|----------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| regex_effbot   | 3.42 ms                                                      | 3.53 ms: 1.03x slower                                        |
| regex_v8       | 23.7 ms                                                      | 25.5 ms: 1.08x slower                                        |
| regex_dna      | 226 ms                                                       | 248 ms: 1.10x slower                                         |
| regex_compile  | 157 ms                                                       | 183 ms: 1.17x slower                                         |
| Geometric mean | (ref)                                                        | 1.09x slower                                                 |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231112-pythonperf2-x86_64-python-main-3.13.0a1+-ce6a533 |
|----------------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| json_dumps           | 13.5 ms                                                      | 10.7 ms: 1.26x faster                                        |
| json_loads           | 29.0 us                                                      | 24.7 us: 1.17x faster                                        |
| xml_etree_parse      | 159 ms                                                       | 154 ms: 1.03x faster                                         |
| pickle_pure_python   | 318 us                                                       | 326 us: 1.02x slower                                         |
| pickle_dict          | 31.8 us                                                      | 33.1 us: 1.04x slower                                        |
| unpickle_list        | 4.47 us                                                      | 4.74 us: 1.06x slower                                        |
| pickle               | 9.77 us                                                      | 10.4 us: 1.06x slower                                        |
| unpickle_pure_python | 236 us                                                       | 252 us: 1.07x slower                                         |
| xml_etree_process    | 56.1 ms                                                      | 60.6 ms: 1.08x slower                                        |
| xml_etree_iterparse  | 106 ms                                                       | 118 ms: 1.11x slower                                         |
| xml_etree_generate   | 80.5 ms                                                      | 89.8 ms: 1.12x slower                                        |
| unpickle             | 13.2 us                                                      | 14.8 us: 1.12x slower                                        |
| pickle_list          | 3.89 us                                                      | 4.43 us: 1.14x slower                                        |
| tomli_loads          | 2.27 sec                                                     | 3.40 sec: 1.50x slower                                       |
| Geometric mean       | (ref)                                                        | 1.06x slower                                                 |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231112-pythonperf2-x86_64-python-main-3.13.0a1+-ce6a533 |
|------------------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| python_startup         | 10.8 ms                                                      | 12.9 ms: 1.19x slower                                        |
| python_startup_no_site | 7.78 ms                                                      | 11.4 ms: 1.47x slower                                        |
| Geometric mean         | (ref)                                                        | 1.32x slower                                                 |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231112-pythonperf2-x86_64-python-main-3.13.0a1+-ce6a533 |
|-----------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| mako      | 11.0 ms                                                      | 16.2 ms: 1.47x slower                                        |

All benchmarks:
===============

| Benchmark                  | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231112-pythonperf2-x86_64-python-main-3.13.0a1+-ce6a533 |
|----------------------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| typing_runtime_protocols   | 527 us                                                       | 135 us: 3.91x faster                                         |
| asyncio_tcp                | 752 ms                                                       | 376 ms: 2.00x faster                                         |
| asyncio_tcp_ssl            | 3.09 sec                                                     | 1.60 sec: 1.93x faster                                       |
| generators                 | 56.4 ms                                                      | 35.3 ms: 1.60x faster                                        |
| coroutines                 | 27.9 ms                                                      | 22.1 ms: 1.26x faster                                        |
| json_dumps                 | 13.5 ms                                                      | 10.7 ms: 1.26x faster                                        |
| json_loads                 | 29.0 us                                                      | 24.7 us: 1.17x faster                                        |
| mypy2                      | 449 ms                                                       | 386 ms: 1.16x faster                                         |
| sympy_sum                  | 184 ms                                                       | 163 ms: 1.13x faster                                         |
| async_tree_none            | 529 ms                                                       | 468 ms: 1.13x faster                                         |
| async_tree_memoization     | 648 ms                                                       | 581 ms: 1.11x faster                                         |
| json                       | 5.59 ms                                                      | 5.15 ms: 1.09x faster                                        |
| scimark_lu                 | 115 ms                                                       | 109 ms: 1.06x faster                                         |
| async_tree_io              | 1.19 sec                                                     | 1.13 sec: 1.05x faster                                       |
| sympy_str                  | 336 ms                                                       | 319 ms: 1.05x faster                                         |
| sqlglot_parse              | 1.55 ms                                                      | 1.49 ms: 1.04x faster                                        |
| async_tree_cpu_io_mixed    | 762 ms                                                       | 731 ms: 1.04x faster                                         |
| sqlglot_normalize          | 122 ms                                                       | 117 ms: 1.04x faster                                         |
| async_tree_memoization_tg  | 605 ms                                                       | 583 ms: 1.04x faster                                         |
| spectral_norm              | 94.0 ms                                                      | 90.9 ms: 1.03x faster                                        |
| xml_etree_parse            | 159 ms                                                       | 154 ms: 1.03x faster                                         |
| logging_silent             | 102 ns                                                       | 98.8 ns: 1.03x faster                                        |
| sympy_expand               | 550 ms                                                       | 539 ms: 1.02x faster                                         |
| logging_simple             | 7.21 us                                                      | 7.08 us: 1.02x faster                                        |
| async_tree_io_tg           | 1.17 sec                                                     | 1.15 sec: 1.02x faster                                       |
| async_tree_none_tg         | 482 ms                                                       | 474 ms: 1.02x faster                                         |
| async_tree_cpu_io_mixed_tg | 760 ms                                                       | 747 ms: 1.02x faster                                         |
| sqlglot_transpile          | 1.94 ms                                                      | 1.91 ms: 1.02x faster                                        |
| deepcopy                   | 389 us                                                       | 384 us: 1.02x faster                                         |
| logging_format             | 7.83 us                                                      | 7.72 us: 1.01x faster                                        |
| gc_traversal               | 4.06 ms                                                      | 4.01 ms: 1.01x faster                                        |
| sympy_integrate            | 25.6 ms                                                      | 25.9 ms: 1.01x slower                                        |
| tornado_http               | 125 ms                                                       | 127 ms: 1.01x slower                                         |
| sqlglot_optimize           | 59.2 ms                                                      | 60.2 ms: 1.02x slower                                        |
| pickle_pure_python         | 318 us                                                       | 326 us: 1.02x slower                                         |
| mdp                        | 2.72 sec                                                     | 2.80 sec: 1.03x slower                                       |
| regex_effbot               | 3.42 ms                                                      | 3.53 ms: 1.03x slower                                        |
| pickle_dict                | 31.8 us                                                      | 33.1 us: 1.04x slower                                        |
| docutils                   | 2.87 sec                                                     | 2.99 sec: 1.04x slower                                       |
| chaos                      | 71.6 ms                                                      | 75.7 ms: 1.06x slower                                        |
| dulwich_log                | 68.3 ms                                                      | 72.2 ms: 1.06x slower                                        |
| pycparser                  | 1.28 sec                                                     | 1.36 sec: 1.06x slower                                       |
| unpickle_list              | 4.47 us                                                      | 4.74 us: 1.06x slower                                        |
| pickle                     | 9.77 us                                                      | 10.4 us: 1.06x slower                                        |
| pidigits                   | 251 ms                                                       | 266 ms: 1.06x slower                                         |
| chameleon                  | 7.42 ms                                                      | 7.93 ms: 1.07x slower                                        |
| unpickle_pure_python       | 236 us                                                       | 252 us: 1.07x slower                                         |
| bench_mp_pool              | 4.63 ms                                                      | 4.98 ms: 1.08x slower                                        |
| regex_v8                   | 23.7 ms                                                      | 25.5 ms: 1.08x slower                                        |
| xml_etree_process          | 56.1 ms                                                      | 60.6 ms: 1.08x slower                                        |
| pathlib                    | 19.1 ms                                                      | 20.7 ms: 1.08x slower                                        |
| regex_dna                  | 226 ms                                                       | 248 ms: 1.10x slower                                         |
| xml_etree_iterparse        | 106 ms                                                       | 118 ms: 1.11x slower                                         |
| sqlite_synth               | 2.49 us                                                      | 2.76 us: 1.11x slower                                        |
| meteor_contest             | 130 ms                                                       | 145 ms: 1.11x slower                                         |
| crypto_pyaes               | 81.8 ms                                                      | 91.2 ms: 1.12x slower                                        |
| xml_etree_generate         | 80.5 ms                                                      | 89.8 ms: 1.12x slower                                        |
| unpickle                   | 13.2 us                                                      | 14.8 us: 1.12x slower                                        |
| 2to3                       | 286 ms                                                       | 323 ms: 1.13x slower                                         |
| pickle_list                | 3.89 us                                                      | 4.43 us: 1.14x slower                                        |
| deepcopy_memo              | 37.3 us                                                      | 43.4 us: 1.16x slower                                        |
| regex_compile              | 157 ms                                                       | 183 ms: 1.17x slower                                         |
| pprint_pformat             | 1.63 sec                                                     | 1.92 sec: 1.18x slower                                       |
| unpack_sequence            | 44.9 ns                                                      | 53.1 ns: 1.18x slower                                        |
| richards                   | 49.9 ms                                                      | 59.2 ms: 1.19x slower                                        |
| python_startup             | 10.8 ms                                                      | 12.9 ms: 1.19x slower                                        |
| async_generators           | 322 ms                                                       | 385 ms: 1.20x slower                                         |
| pprint_safe_repr           | 780 ms                                                       | 937 ms: 1.20x slower                                         |
| scimark_monte_carlo        | 70.6 ms                                                      | 85.1 ms: 1.21x slower                                        |
| go                         | 166 ms                                                       | 201 ms: 1.21x slower                                         |
| telco                      | 6.91 ms                                                      | 8.61 ms: 1.25x slower                                        |
| coverage                   | 66.6 ms                                                      | 83.2 ms: 1.25x slower                                        |
| fannkuch                   | 457 ms                                                       | 577 ms: 1.26x slower                                         |
| nqueens                    | 99.2 ms                                                      | 129 ms: 1.30x slower                                         |
| comprehensions             | 24.8 us                                                      | 32.5 us: 1.31x slower                                        |
| nbody                      | 95.8 ms                                                      | 129 ms: 1.34x slower                                         |
| pyflate                    | 453 ms                                                       | 612 ms: 1.35x slower                                         |
| scimark_sor                | 109 ms                                                       | 150 ms: 1.37x slower                                         |
| python_startup_no_site     | 7.78 ms                                                      | 11.4 ms: 1.47x slower                                        |
| mako                       | 11.0 ms                                                      | 16.2 ms: 1.47x slower                                        |
| scimark_fft                | 281 ms                                                       | 418 ms: 1.49x slower                                         |
| deltablue                  | 4.03 ms                                                      | 5.99 ms: 1.49x slower                                        |
| tomli_loads                | 2.27 sec                                                     | 3.40 sec: 1.50x slower                                       |
| float                      | 76.0 ms                                                      | 116 ms: 1.52x slower                                         |
| hexiom                     | 6.97 ms                                                      | 12.6 ms: 1.81x slower                                        |
| scimark_sparse_mat_mult    | 4.04 ms                                                      | 7.36 ms: 1.82x slower                                        |
| Geometric mean             | (ref)                                                        | 1.05x slower                                                 |

Benchmark hidden because not significant (6): create_gc_cycles, deepcopy_reduce, bench_thread_pool, raytrace, asyncio_websockets, richards_super
Ignored benchmarks (12) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, dask, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift


# HPT report

- Reliability score: 99.58% likely to be slow
- 90% likely to have a slowdown of 1.02x
- 95% likely to have a slowdown of 1.01x
- 99% likely to have a slowdown of 1.00x
