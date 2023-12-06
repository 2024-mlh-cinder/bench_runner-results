
# Results vs. 3.11.0

- fork: mdboom
- ref: pogo2
- machine: linux-x86_64
- commit hash: 69004d6
- commit date: 2023-11-20
- overall geometric mean: 1.05x slower \*
- HPT reliability: 98.86%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-pythonperf2-x86_64-mdboom-pogo2-3.13.0a1+-69004d6 |
|----------------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| 2to3           | 286 ms                                                       | 318 ms: 1.11x slower                                          |
| chameleon      | 7.42 ms                                                      | 7.81 ms: 1.05x slower                                         |
| docutils       | 2.87 sec                                                     | 2.95 sec: 1.03x slower                                        |
| Geometric mean | (ref)                                                        | 1.05x slower                                                  |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-pythonperf2-x86_64-mdboom-pogo2-3.13.0a1+-69004d6 |
|----------------------------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| async_tree_none            | 529 ms                                                       | 451 ms: 1.17x faster                                          |
| async_tree_memoization     | 648 ms                                                       | 566 ms: 1.14x faster                                          |
| async_tree_io              | 1.19 sec                                                     | 1.11 sec: 1.08x faster                                        |
| async_tree_memoization_tg  | 605 ms                                                       | 569 ms: 1.06x faster                                          |
| async_tree_cpu_io_mixed    | 762 ms                                                       | 717 ms: 1.06x faster                                          |
| async_tree_none_tg         | 482 ms                                                       | 458 ms: 1.05x faster                                          |
| async_tree_io_tg           | 1.17 sec                                                     | 1.13 sec: 1.04x faster                                        |
| async_tree_cpu_io_mixed_tg | 760 ms                                                       | 732 ms: 1.04x faster                                          |
| Geometric mean             | (ref)                                                        | 1.08x faster                                                  |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-pythonperf2-x86_64-mdboom-pogo2-3.13.0a1+-69004d6 |
|----------------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| pidigits       | 251 ms                                                       | 268 ms: 1.07x slower                                          |
| float          | 76.0 ms                                                      | 114 ms: 1.50x slower                                          |
| nbody          | 95.8 ms                                                      | 149 ms: 1.56x slower                                          |
| Geometric mean | (ref)                                                        | 1.36x slower                                                  |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-pythonperf2-x86_64-mdboom-pogo2-3.13.0a1+-69004d6 |
|----------------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| regex_effbot   | 3.42 ms                                                      | 3.48 ms: 1.02x slower                                         |
| regex_v8       | 23.7 ms                                                      | 24.7 ms: 1.05x slower                                         |
| regex_dna      | 226 ms                                                       | 241 ms: 1.07x slower                                          |
| regex_compile  | 157 ms                                                       | 178 ms: 1.14x slower                                          |
| Geometric mean | (ref)                                                        | 1.07x slower                                                  |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-pythonperf2-x86_64-mdboom-pogo2-3.13.0a1+-69004d6 |
|----------------------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| json_dumps           | 13.5 ms                                                      | 10.6 ms: 1.27x faster                                         |
| json_loads           | 29.0 us                                                      | 25.2 us: 1.15x faster                                         |
| xml_etree_parse      | 159 ms                                                       | 147 ms: 1.08x faster                                          |
| pickle_pure_python   | 318 us                                                       | 309 us: 1.03x faster                                          |
| pickle               | 9.77 us                                                      | 10.1 us: 1.03x slower                                         |
| pickle_dict          | 31.8 us                                                      | 33.0 us: 1.04x slower                                         |
| unpickle_list        | 4.47 us                                                      | 4.75 us: 1.06x slower                                         |
| unpickle_pure_python | 236 us                                                       | 255 us: 1.08x slower                                          |
| unpickle             | 13.2 us                                                      | 14.8 us: 1.12x slower                                         |
| xml_etree_process    | 56.1 ms                                                      | 63.3 ms: 1.13x slower                                         |
| xml_etree_generate   | 80.5 ms                                                      | 92.2 ms: 1.15x slower                                         |
| pickle_list          | 3.89 us                                                      | 4.50 us: 1.15x slower                                         |
| xml_etree_iterparse  | 106 ms                                                       | 123 ms: 1.16x slower                                          |
| tomli_loads          | 2.27 sec                                                     | 2.96 sec: 1.30x slower                                        |
| Geometric mean       | (ref)                                                        | 1.05x slower                                                  |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-pythonperf2-x86_64-mdboom-pogo2-3.13.0a1+-69004d6 |
|------------------------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| python_startup         | 10.8 ms                                                      | 12.8 ms: 1.19x slower                                         |
| python_startup_no_site | 7.78 ms                                                      | 11.3 ms: 1.45x slower                                         |
| Geometric mean         | (ref)                                                        | 1.31x slower                                                  |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-pythonperf2-x86_64-mdboom-pogo2-3.13.0a1+-69004d6 |
|-----------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| mako      | 11.0 ms                                                      | 17.9 ms: 1.62x slower                                         |

All benchmarks:
===============

| Benchmark                  | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-pythonperf2-x86_64-mdboom-pogo2-3.13.0a1+-69004d6 |
|----------------------------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| typing_runtime_protocols   | 527 us                                                       | 132 us: 4.00x faster                                          |
| asyncio_tcp                | 752 ms                                                       | 374 ms: 2.01x faster                                          |
| asyncio_tcp_ssl            | 3.09 sec                                                     | 1.59 sec: 1.94x faster                                        |
| generators                 | 56.4 ms                                                      | 35.2 ms: 1.60x faster                                         |
| json_dumps                 | 13.5 ms                                                      | 10.6 ms: 1.27x faster                                         |
| coroutines                 | 27.9 ms                                                      | 22.3 ms: 1.25x faster                                         |
| mypy2                      | 449 ms                                                       | 382 ms: 1.17x faster                                          |
| async_tree_none            | 529 ms                                                       | 451 ms: 1.17x faster                                          |
| json_loads                 | 29.0 us                                                      | 25.2 us: 1.15x faster                                         |
| async_tree_memoization     | 648 ms                                                       | 566 ms: 1.14x faster                                          |
| gc_traversal               | 4.06 ms                                                      | 3.71 ms: 1.09x faster                                         |
| richards_super             | 65.2 ms                                                      | 60.3 ms: 1.08x faster                                         |
| xml_etree_parse            | 159 ms                                                       | 147 ms: 1.08x faster                                          |
| sympy_sum                  | 184 ms                                                       | 171 ms: 1.08x faster                                          |
| scimark_lu                 | 115 ms                                                       | 107 ms: 1.08x faster                                          |
| async_tree_io              | 1.19 sec                                                     | 1.11 sec: 1.08x faster                                        |
| json                       | 5.59 ms                                                      | 5.20 ms: 1.07x faster                                         |
| logging_simple             | 7.21 us                                                      | 6.77 us: 1.07x faster                                         |
| async_tree_memoization_tg  | 605 ms                                                       | 569 ms: 1.06x faster                                          |
| async_tree_cpu_io_mixed    | 762 ms                                                       | 717 ms: 1.06x faster                                          |
| logging_format             | 7.83 us                                                      | 7.41 us: 1.06x faster                                         |
| async_tree_none_tg         | 482 ms                                                       | 458 ms: 1.05x faster                                          |
| deepcopy                   | 389 us                                                       | 371 us: 1.05x faster                                          |
| sqlglot_parse              | 1.55 ms                                                      | 1.49 ms: 1.04x faster                                         |
| async_tree_io_tg           | 1.17 sec                                                     | 1.13 sec: 1.04x faster                                        |
| async_tree_cpu_io_mixed_tg | 760 ms                                                       | 732 ms: 1.04x faster                                          |
| deepcopy_reduce            | 3.37 us                                                      | 3.27 us: 1.03x faster                                         |
| pickle_pure_python         | 318 us                                                       | 309 us: 1.03x faster                                          |
| bench_thread_pool          | 1.02 ms                                                      | 991 us: 1.03x faster                                          |
| logging_silent             | 102 ns                                                       | 100 ns: 1.02x faster                                          |
| dask                       | 417 ms                                                       | 410 ms: 1.02x faster                                          |
| sympy_str                  | 336 ms                                                       | 331 ms: 1.01x faster                                          |
| sqlglot_transpile          | 1.94 ms                                                      | 1.92 ms: 1.01x faster                                         |
| sympy_expand               | 550 ms                                                       | 546 ms: 1.01x faster                                          |
| mdp                        | 2.72 sec                                                     | 2.73 sec: 1.01x slower                                        |
| create_gc_cycles           | 1.59 ms                                                      | 1.62 ms: 1.01x slower                                         |
| regex_effbot               | 3.42 ms                                                      | 3.48 ms: 1.02x slower                                         |
| sqlglot_normalize          | 122 ms                                                       | 124 ms: 1.02x slower                                          |
| docutils                   | 2.87 sec                                                     | 2.95 sec: 1.03x slower                                        |
| bench_mp_pool              | 4.63 ms                                                      | 4.77 ms: 1.03x slower                                         |
| pickle                     | 9.77 us                                                      | 10.1 us: 1.03x slower                                         |
| pathlib                    | 19.1 ms                                                      | 19.8 ms: 1.03x slower                                         |
| pickle_dict                | 31.8 us                                                      | 33.0 us: 1.04x slower                                         |
| regex_v8                   | 23.7 ms                                                      | 24.7 ms: 1.05x slower                                         |
| raytrace                   | 308 ms                                                       | 322 ms: 1.05x slower                                          |
| chameleon                  | 7.42 ms                                                      | 7.81 ms: 1.05x slower                                         |
| pycparser                  | 1.28 sec                                                     | 1.36 sec: 1.06x slower                                        |
| dulwich_log                | 68.3 ms                                                      | 72.5 ms: 1.06x slower                                         |
| unpickle_list              | 4.47 us                                                      | 4.75 us: 1.06x slower                                         |
| regex_dna                  | 226 ms                                                       | 241 ms: 1.07x slower                                          |
| pidigits                   | 251 ms                                                       | 268 ms: 1.07x slower                                          |
| unpickle_pure_python       | 236 us                                                       | 255 us: 1.08x slower                                          |
| sqlglot_optimize           | 59.2 ms                                                      | 64.5 ms: 1.09x slower                                         |
| richards                   | 49.9 ms                                                      | 54.7 ms: 1.10x slower                                         |
| meteor_contest             | 130 ms                                                       | 145 ms: 1.11x slower                                          |
| 2to3                       | 286 ms                                                       | 318 ms: 1.11x slower                                          |
| unpickle                   | 13.2 us                                                      | 14.8 us: 1.12x slower                                         |
| go                         | 166 ms                                                       | 186 ms: 1.13x slower                                          |
| xml_etree_process          | 56.1 ms                                                      | 63.3 ms: 1.13x slower                                         |
| deepcopy_memo              | 37.3 us                                                      | 42.3 us: 1.13x slower                                         |
| regex_compile              | 157 ms                                                       | 178 ms: 1.14x slower                                          |
| comprehensions             | 24.8 us                                                      | 28.2 us: 1.14x slower                                         |
| sqlite_synth               | 2.49 us                                                      | 2.83 us: 1.14x slower                                         |
| fannkuch                   | 457 ms                                                       | 521 ms: 1.14x slower                                          |
| xml_etree_generate         | 80.5 ms                                                      | 92.2 ms: 1.15x slower                                         |
| crypto_pyaes               | 81.8 ms                                                      | 93.9 ms: 1.15x slower                                         |
| pickle_list                | 3.89 us                                                      | 4.50 us: 1.15x slower                                         |
| xml_etree_iterparse        | 106 ms                                                       | 123 ms: 1.16x slower                                          |
| chaos                      | 71.6 ms                                                      | 83.4 ms: 1.16x slower                                         |
| nqueens                    | 99.2 ms                                                      | 116 ms: 1.17x slower                                          |
| unpack_sequence            | 44.9 ns                                                      | 52.8 ns: 1.18x slower                                         |
| python_startup             | 10.8 ms                                                      | 12.8 ms: 1.19x slower                                         |
| async_generators           | 322 ms                                                       | 385 ms: 1.20x slower                                          |
| pprint_pformat             | 1.63 sec                                                     | 1.96 sec: 1.20x slower                                        |
| pprint_safe_repr           | 780 ms                                                       | 951 ms: 1.22x slower                                          |
| telco                      | 6.91 ms                                                      | 8.51 ms: 1.23x slower                                         |
| coverage                   | 66.6 ms                                                      | 82.7 ms: 1.24x slower                                         |
| tomli_loads                | 2.27 sec                                                     | 2.96 sec: 1.30x slower                                        |
| pyflate                    | 453 ms                                                       | 611 ms: 1.35x slower                                          |
| scimark_monte_carlo        | 70.6 ms                                                      | 97.8 ms: 1.39x slower                                         |
| scimark_sor                | 109 ms                                                       | 152 ms: 1.39x slower                                          |
| python_startup_no_site     | 7.78 ms                                                      | 11.3 ms: 1.45x slower                                         |
| float                      | 76.0 ms                                                      | 114 ms: 1.50x slower                                          |
| deltablue                  | 4.03 ms                                                      | 6.03 ms: 1.50x slower                                         |
| nbody                      | 95.8 ms                                                      | 149 ms: 1.56x slower                                          |
| hexiom                     | 6.97 ms                                                      | 10.9 ms: 1.57x slower                                         |
| mako                       | 11.0 ms                                                      | 17.9 ms: 1.62x slower                                         |
| scimark_fft                | 281 ms                                                       | 478 ms: 1.70x slower                                          |
| scimark_sparse_mat_mult    | 4.04 ms                                                      | 7.06 ms: 1.75x slower                                         |
| spectral_norm              | 94.0 ms                                                      | 185 ms: 1.97x slower                                          |
| Geometric mean             | (ref)                                                        | 1.05x slower                                                  |

Benchmark hidden because not significant (3): tornado_http, asyncio_websockets, sympy_integrate
Ignored benchmarks (11) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift


# HPT report

- Reliability score: 98.86% likely to be slow
- 90% likely to have a slowdown of 1.01x
- 95% likely to have a slowdown of 1.01x
- 99% likely to have a slowdown of 1.00x
