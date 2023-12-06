
# Results vs. 3.11.0

- fork: python
- ref: 0ee2d77331f2362fcaab
- machine: linux-x86_64
- commit hash: 0ee2d77
- commit date: 2023-11-17
- overall geometric mean: 1.02x slower \*
- HPT reliability: 88.06%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231117-pythonperf2-x86_64-python-0ee2d77331f2362fcaab-3.13.0a1+-0ee2d77 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| 2to3           | 286 ms                                                       | 313 ms: 1.10x slower                                                         |
| chameleon      | 7.42 ms                                                      | 8.23 ms: 1.11x slower                                                        |
| docutils       | 2.87 sec                                                     | 2.95 sec: 1.03x slower                                                       |
| Geometric mean | (ref)                                                        | 1.06x slower                                                                 |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231117-pythonperf2-x86_64-python-0ee2d77331f2362fcaab-3.13.0a1+-0ee2d77 |
|----------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| async_tree_none            | 529 ms                                                       | 455 ms: 1.16x faster                                                         |
| async_tree_memoization     | 648 ms                                                       | 572 ms: 1.13x faster                                                         |
| async_tree_io              | 1.19 sec                                                     | 1.11 sec: 1.08x faster                                                       |
| async_tree_memoization_tg  | 605 ms                                                       | 572 ms: 1.06x faster                                                         |
| async_tree_cpu_io_mixed    | 762 ms                                                       | 724 ms: 1.05x faster                                                         |
| async_tree_io_tg           | 1.17 sec                                                     | 1.12 sec: 1.04x faster                                                       |
| async_tree_none_tg         | 482 ms                                                       | 464 ms: 1.04x faster                                                         |
| async_tree_cpu_io_mixed_tg | 760 ms                                                       | 740 ms: 1.03x faster                                                         |
| Geometric mean             | (ref)                                                        | 1.07x faster                                                                 |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231117-pythonperf2-x86_64-python-0ee2d77331f2362fcaab-3.13.0a1+-0ee2d77 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| pidigits       | 251 ms                                                       | 266 ms: 1.06x slower                                                         |
| nbody          | 95.8 ms                                                      | 109 ms: 1.14x slower                                                         |
| float          | 76.0 ms                                                      | 101 ms: 1.33x slower                                                         |
| Geometric mean | (ref)                                                        | 1.17x slower                                                                 |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231117-pythonperf2-x86_64-python-0ee2d77331f2362fcaab-3.13.0a1+-0ee2d77 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| regex_effbot   | 3.42 ms                                                      | 3.54 ms: 1.04x slower                                                        |
| regex_dna      | 226 ms                                                       | 244 ms: 1.08x slower                                                         |
| regex_v8       | 23.7 ms                                                      | 25.9 ms: 1.09x slower                                                        |
| regex_compile  | 157 ms                                                       | 173 ms: 1.10x slower                                                         |
| Geometric mean | (ref)                                                        | 1.08x slower                                                                 |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231117-pythonperf2-x86_64-python-0ee2d77331f2362fcaab-3.13.0a1+-0ee2d77 |
|----------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| json_dumps           | 13.5 ms                                                      | 10.8 ms: 1.25x faster                                                        |
| json_loads           | 29.0 us                                                      | 25.2 us: 1.15x faster                                                        |
| xml_etree_parse      | 159 ms                                                       | 152 ms: 1.05x faster                                                         |
| pickle_pure_python   | 318 us                                                       | 314 us: 1.01x faster                                                         |
| pickle_dict          | 31.8 us                                                      | 32.3 us: 1.02x slower                                                        |
| pickle               | 9.77 us                                                      | 10.1 us: 1.04x slower                                                        |
| unpickle_list        | 4.47 us                                                      | 4.65 us: 1.04x slower                                                        |
| xml_etree_process    | 56.1 ms                                                      | 58.5 ms: 1.04x slower                                                        |
| unpickle_pure_python | 236 us                                                       | 253 us: 1.07x slower                                                         |
| xml_etree_generate   | 80.5 ms                                                      | 86.9 ms: 1.08x slower                                                        |
| xml_etree_iterparse  | 106 ms                                                       | 114 ms: 1.08x slower                                                         |
| unpickle             | 13.2 us                                                      | 14.5 us: 1.10x slower                                                        |
| pickle_list          | 3.89 us                                                      | 4.36 us: 1.12x slower                                                        |
| tomli_loads          | 2.27 sec                                                     | 2.87 sec: 1.26x slower                                                       |
| Geometric mean       | (ref)                                                        | 1.03x slower                                                                 |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231117-pythonperf2-x86_64-python-0ee2d77331f2362fcaab-3.13.0a1+-0ee2d77 |
|------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| python_startup         | 10.8 ms                                                      | 12.9 ms: 1.19x slower                                                        |
| python_startup_no_site | 7.78 ms                                                      | 11.4 ms: 1.46x slower                                                        |
| Geometric mean         | (ref)                                                        | 1.32x slower                                                                 |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231117-pythonperf2-x86_64-python-0ee2d77331f2362fcaab-3.13.0a1+-0ee2d77 |
|-----------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| mako      | 11.0 ms                                                      | 14.7 ms: 1.34x slower                                                        |

All benchmarks:
===============

| Benchmark                  | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231117-pythonperf2-x86_64-python-0ee2d77331f2362fcaab-3.13.0a1+-0ee2d77 |
|----------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| typing_runtime_protocols   | 527 us                                                       | 135 us: 3.92x faster                                                         |
| asyncio_tcp                | 752 ms                                                       | 375 ms: 2.00x faster                                                         |
| asyncio_tcp_ssl            | 3.09 sec                                                     | 1.60 sec: 1.94x faster                                                       |
| generators                 | 56.4 ms                                                      | 35.1 ms: 1.61x faster                                                        |
| coroutines                 | 27.9 ms                                                      | 22.2 ms: 1.25x faster                                                        |
| json_dumps                 | 13.5 ms                                                      | 10.8 ms: 1.25x faster                                                        |
| mypy2                      | 449 ms                                                       | 382 ms: 1.18x faster                                                         |
| sympy_sum                  | 184 ms                                                       | 159 ms: 1.16x faster                                                         |
| async_tree_none            | 529 ms                                                       | 455 ms: 1.16x faster                                                         |
| json_loads                 | 29.0 us                                                      | 25.2 us: 1.15x faster                                                        |
| async_tree_memoization     | 648 ms                                                       | 572 ms: 1.13x faster                                                         |
| gc_traversal               | 4.06 ms                                                      | 3.68 ms: 1.10x faster                                                        |
| scimark_lu                 | 115 ms                                                       | 107 ms: 1.08x faster                                                         |
| sympy_str                  | 336 ms                                                       | 311 ms: 1.08x faster                                                         |
| richards_super             | 65.2 ms                                                      | 60.5 ms: 1.08x faster                                                        |
| async_tree_io              | 1.19 sec                                                     | 1.11 sec: 1.08x faster                                                       |
| logging_simple             | 7.21 us                                                      | 6.74 us: 1.07x faster                                                        |
| json                       | 5.59 ms                                                      | 5.29 ms: 1.06x faster                                                        |
| async_tree_memoization_tg  | 605 ms                                                       | 572 ms: 1.06x faster                                                         |
| async_tree_cpu_io_mixed    | 762 ms                                                       | 724 ms: 1.05x faster                                                         |
| sqlglot_parse              | 1.55 ms                                                      | 1.48 ms: 1.05x faster                                                        |
| logging_format             | 7.83 us                                                      | 7.47 us: 1.05x faster                                                        |
| xml_etree_parse            | 159 ms                                                       | 152 ms: 1.05x faster                                                         |
| sqlglot_normalize          | 122 ms                                                       | 117 ms: 1.05x faster                                                         |
| sympy_expand               | 550 ms                                                       | 528 ms: 1.04x faster                                                         |
| async_tree_io_tg           | 1.17 sec                                                     | 1.12 sec: 1.04x faster                                                       |
| bench_thread_pool          | 1.02 ms                                                      | 979 us: 1.04x faster                                                         |
| async_tree_none_tg         | 482 ms                                                       | 464 ms: 1.04x faster                                                         |
| raytrace                   | 308 ms                                                       | 298 ms: 1.03x faster                                                         |
| deepcopy                   | 389 us                                                       | 378 us: 1.03x faster                                                         |
| spectral_norm              | 94.0 ms                                                      | 91.4 ms: 1.03x faster                                                        |
| async_tree_cpu_io_mixed_tg | 760 ms                                                       | 740 ms: 1.03x faster                                                         |
| sqlglot_transpile          | 1.94 ms                                                      | 1.89 ms: 1.02x faster                                                        |
| dask                       | 417 ms                                                       | 407 ms: 1.02x faster                                                         |
| sympy_integrate            | 25.6 ms                                                      | 25.1 ms: 1.02x faster                                                        |
| chaos                      | 71.6 ms                                                      | 70.5 ms: 1.02x faster                                                        |
| pickle_pure_python         | 318 us                                                       | 314 us: 1.01x faster                                                         |
| logging_silent             | 102 ns                                                       | 101 ns: 1.01x faster                                                         |
| deepcopy_reduce            | 3.37 us                                                      | 3.35 us: 1.01x faster                                                        |
| mdp                        | 2.72 sec                                                     | 2.75 sec: 1.01x slower                                                       |
| create_gc_cycles           | 1.59 ms                                                      | 1.62 ms: 1.01x slower                                                        |
| pickle_dict                | 31.8 us                                                      | 32.3 us: 1.02x slower                                                        |
| pycparser                  | 1.28 sec                                                     | 1.32 sec: 1.03x slower                                                       |
| docutils                   | 2.87 sec                                                     | 2.95 sec: 1.03x slower                                                       |
| regex_effbot               | 3.42 ms                                                      | 3.54 ms: 1.04x slower                                                        |
| pickle                     | 9.77 us                                                      | 10.1 us: 1.04x slower                                                        |
| crypto_pyaes               | 81.8 ms                                                      | 85.0 ms: 1.04x slower                                                        |
| unpickle_list              | 4.47 us                                                      | 4.65 us: 1.04x slower                                                        |
| xml_etree_process          | 56.1 ms                                                      | 58.5 ms: 1.04x slower                                                        |
| dulwich_log                | 68.3 ms                                                      | 71.3 ms: 1.04x slower                                                        |
| unpack_sequence            | 44.9 ns                                                      | 47.2 ns: 1.05x slower                                                        |
| meteor_contest             | 130 ms                                                       | 137 ms: 1.05x slower                                                         |
| pidigits                   | 251 ms                                                       | 266 ms: 1.06x slower                                                         |
| unpickle_pure_python       | 236 us                                                       | 253 us: 1.07x slower                                                         |
| xml_etree_generate         | 80.5 ms                                                      | 86.9 ms: 1.08x slower                                                        |
| regex_dna                  | 226 ms                                                       | 244 ms: 1.08x slower                                                         |
| xml_etree_iterparse        | 106 ms                                                       | 114 ms: 1.08x slower                                                         |
| richards                   | 49.9 ms                                                      | 54.3 ms: 1.09x slower                                                        |
| regex_v8                   | 23.7 ms                                                      | 25.9 ms: 1.09x slower                                                        |
| 2to3                       | 286 ms                                                       | 313 ms: 1.10x slower                                                         |
| unpickle                   | 13.2 us                                                      | 14.5 us: 1.10x slower                                                        |
| regex_compile              | 157 ms                                                       | 173 ms: 1.10x slower                                                         |
| fannkuch                   | 457 ms                                                       | 506 ms: 1.11x slower                                                         |
| chameleon                  | 7.42 ms                                                      | 8.23 ms: 1.11x slower                                                        |
| sqlite_synth               | 2.49 us                                                      | 2.77 us: 1.11x slower                                                        |
| pickle_list                | 3.89 us                                                      | 4.36 us: 1.12x slower                                                        |
| comprehensions             | 24.8 us                                                      | 27.8 us: 1.12x slower                                                        |
| deepcopy_memo              | 37.3 us                                                      | 42.2 us: 1.13x slower                                                        |
| go                         | 166 ms                                                       | 188 ms: 1.13x slower                                                         |
| nbody                      | 95.8 ms                                                      | 109 ms: 1.14x slower                                                         |
| pprint_pformat             | 1.63 sec                                                     | 1.87 sec: 1.14x slower                                                       |
| pprint_safe_repr           | 780 ms                                                       | 913 ms: 1.17x slower                                                         |
| scimark_monte_carlo        | 70.6 ms                                                      | 83.3 ms: 1.18x slower                                                        |
| nqueens                    | 99.2 ms                                                      | 117 ms: 1.18x slower                                                         |
| python_startup             | 10.8 ms                                                      | 12.9 ms: 1.19x slower                                                        |
| async_generators           | 322 ms                                                       | 386 ms: 1.20x slower                                                         |
| telco                      | 6.91 ms                                                      | 8.50 ms: 1.23x slower                                                        |
| coverage                   | 66.6 ms                                                      | 82.4 ms: 1.24x slower                                                        |
| tomli_loads                | 2.27 sec                                                     | 2.87 sec: 1.26x slower                                                       |
| pyflate                    | 453 ms                                                       | 589 ms: 1.30x slower                                                         |
| deltablue                  | 4.03 ms                                                      | 5.25 ms: 1.30x slower                                                        |
| float                      | 76.0 ms                                                      | 101 ms: 1.33x slower                                                         |
| mako                       | 11.0 ms                                                      | 14.7 ms: 1.34x slower                                                        |
| scimark_sor                | 109 ms                                                       | 153 ms: 1.40x slower                                                         |
| scimark_fft                | 281 ms                                                       | 396 ms: 1.41x slower                                                         |
| python_startup_no_site     | 7.78 ms                                                      | 11.4 ms: 1.46x slower                                                        |
| hexiom                     | 6.97 ms                                                      | 10.7 ms: 1.53x slower                                                        |
| scimark_sparse_mat_mult    | 4.04 ms                                                      | 6.58 ms: 1.63x slower                                                        |
| Geometric mean             | (ref)                                                        | 1.02x slower                                                                 |

Benchmark hidden because not significant (5): asyncio_websockets, sqlglot_optimize, tornado_http, pathlib, bench_mp_pool
Ignored benchmarks (11) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift


# HPT report

- Reliability score: 88.06% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
