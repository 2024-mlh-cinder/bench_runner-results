
# Results vs. 3.11.0

- fork: mdboom
- ref: test_branch3
- machine: linux-x86_64
- commit hash: dbd826e
- commit date: 2023-11-20
- overall geometric mean: 1.01x slower \*
- HPT reliability: 99.89%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-linux-x86_64-mdboom-test_branch3-3.13.0a1+-dbd826e |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| 2to3           | 266 ms                                                 | 288 ms: 1.08x slower                                           |
| chameleon      | 6.86 ms                                                | 7.46 ms: 1.09x slower                                          |
| docutils       | 2.69 sec                                               | 2.72 sec: 1.01x slower                                         |
| tornado_http   | 97.7 ms                                                | 99.1 ms: 1.01x slower                                          |
| Geometric mean | (ref)                                                  | 1.05x slower                                                   |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-linux-x86_64-mdboom-test_branch3-3.13.0a1+-dbd826e |
|----------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| async_tree_none            | 532 ms                                                 | 452 ms: 1.18x faster                                           |
| async_tree_memoization     | 640 ms                                                 | 581 ms: 1.10x faster                                           |
| async_tree_io              | 1.31 sec                                               | 1.21 sec: 1.08x faster                                         |
| async_tree_none_tg         | 490 ms                                                 | 468 ms: 1.05x faster                                           |
| async_tree_io_tg           | 1.30 sec                                               | 1.25 sec: 1.05x faster                                         |
| async_tree_cpu_io_mixed    | 750 ms                                                 | 725 ms: 1.03x faster                                           |
| async_tree_memoization_tg  | 627 ms                                                 | 617 ms: 1.02x faster                                           |
| async_tree_cpu_io_mixed_tg | 764 ms                                                 | 752 ms: 1.02x faster                                           |
| Geometric mean             | (ref)                                                  | 1.06x faster                                                   |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-linux-x86_64-mdboom-test_branch3-3.13.0a1+-dbd826e |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| pidigits       | 190 ms                                                 | 196 ms: 1.03x slower                                           |
| float          | 78.9 ms                                                | 94.4 ms: 1.20x slower                                          |
| nbody          | 91.6 ms                                                | 112 ms: 1.22x slower                                           |
| Geometric mean | (ref)                                                  | 1.15x slower                                                   |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-linux-x86_64-mdboom-test_branch3-3.13.0a1+-dbd826e |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| regex_effbot   | 3.45 ms                                                | 3.57 ms: 1.04x slower                                          |
| regex_dna      | 204 ms                                                 | 217 ms: 1.06x slower                                           |
| regex_v8       | 22.9 ms                                                | 24.5 ms: 1.07x slower                                          |
| regex_compile  | 141 ms                                                 | 160 ms: 1.13x slower                                           |
| Geometric mean | (ref)                                                  | 1.07x slower                                                   |

Benchmarks with tag 'serialize':
================================

| Benchmark           | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-linux-x86_64-mdboom-test_branch3-3.13.0a1+-dbd826e |
|---------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| json_dumps          | 13.5 ms                                                | 10.7 ms: 1.26x faster                                          |
| json_loads          | 29.4 us                                                | 28.5 us: 1.03x faster                                          |
| xml_etree_parse     | 163 ms                                                 | 159 ms: 1.02x faster                                           |
| pickle_pure_python  | 319 us                                                 | 313 us: 1.02x faster                                           |
| unpickle_list       | 5.22 us                                                | 5.16 us: 1.01x faster                                          |
| pickle_dict         | 34.8 us                                                | 35.5 us: 1.02x slower                                          |
| xml_etree_iterparse | 109 ms                                                 | 114 ms: 1.05x slower                                           |
| pickle              | 11.1 us                                                | 11.7 us: 1.05x slower                                          |
| unpickle            | 13.9 us                                                | 14.9 us: 1.07x slower                                          |
| tomli_loads         | 2.31 sec                                               | 2.51 sec: 1.09x slower                                         |
| xml_etree_process   | 56.5 ms                                                | 63.1 ms: 1.12x slower                                          |
| pickle_list         | 4.65 us                                                | 5.20 us: 1.12x slower                                          |
| xml_etree_generate  | 80.4 ms                                                | 92.6 ms: 1.15x slower                                          |
| Geometric mean      | (ref)                                                  | 1.02x slower                                                   |

Benchmark hidden because not significant (1): unpickle_pure_python

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-linux-x86_64-mdboom-test_branch3-3.13.0a1+-dbd826e |
|------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| python_startup         | 8.69 ms                                                | 10.4 ms: 1.20x slower                                          |
| python_startup_no_site | 6.09 ms                                                | 9.05 ms: 1.49x slower                                          |
| Geometric mean         | (ref)                                                  | 1.33x slower                                                   |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-linux-x86_64-mdboom-test_branch3-3.13.0a1+-dbd826e |
|-----------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| mako      | 10.8 ms                                                | 14.5 ms: 1.34x slower                                          |

All benchmarks:
===============

| Benchmark                  | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-linux-x86_64-mdboom-test_branch3-3.13.0a1+-dbd826e |
|----------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| typing_runtime_protocols   | 521 us                                                 | 124 us: 4.19x faster                                           |
| generators                 | 76.5 ms                                                | 29.7 ms: 2.57x faster                                          |
| asyncio_tcp                | 887 ms                                                 | 491 ms: 1.81x faster                                           |
| asyncio_tcp_ssl            | 3.13 sec                                               | 1.81 sec: 1.73x faster                                         |
| json_dumps                 | 13.5 ms                                                | 10.7 ms: 1.26x faster                                          |
| mypy2                      | 427 ms                                                 | 357 ms: 1.20x faster                                           |
| async_tree_none            | 532 ms                                                 | 452 ms: 1.18x faster                                           |
| coroutines                 | 26.1 ms                                                | 22.7 ms: 1.15x faster                                          |
| async_tree_memoization     | 640 ms                                                 | 581 ms: 1.10x faster                                           |
| async_tree_io              | 1.31 sec                                               | 1.21 sec: 1.08x faster                                         |
| richards_super             | 61.2 ms                                                | 57.2 ms: 1.07x faster                                          |
| comprehensions             | 23.6 us                                                | 22.2 us: 1.06x faster                                          |
| sympy_sum                  | 170 ms                                                 | 161 ms: 1.06x faster                                           |
| async_tree_none_tg         | 490 ms                                                 | 468 ms: 1.05x faster                                           |
| async_tree_io_tg           | 1.30 sec                                               | 1.25 sec: 1.05x faster                                         |
| sqlglot_parse              | 1.43 ms                                                | 1.38 ms: 1.04x faster                                          |
| json_loads                 | 29.4 us                                                | 28.5 us: 1.03x faster                                          |
| async_tree_cpu_io_mixed    | 750 ms                                                 | 725 ms: 1.03x faster                                           |
| sqlglot_transpile          | 1.75 ms                                                | 1.71 ms: 1.03x faster                                          |
| xml_etree_parse            | 163 ms                                                 | 159 ms: 1.02x faster                                           |
| pickle_pure_python         | 319 us                                                 | 313 us: 1.02x faster                                           |
| gc_traversal               | 3.90 ms                                                | 3.83 ms: 1.02x faster                                          |
| async_tree_memoization_tg  | 627 ms                                                 | 617 ms: 1.02x faster                                           |
| async_tree_cpu_io_mixed_tg | 764 ms                                                 | 752 ms: 1.02x faster                                           |
| logging_simple             | 6.24 us                                                | 6.15 us: 1.01x faster                                          |
| unpickle_list              | 5.22 us                                                | 5.16 us: 1.01x faster                                          |
| sympy_str                  | 299 ms                                                 | 296 ms: 1.01x faster                                           |
| json                       | 5.24 ms                                                | 5.18 ms: 1.01x faster                                          |
| asyncio_websockets         | 556 ms                                                 | 552 ms: 1.01x faster                                           |
| logging_silent             | 108 ns                                                 | 108 ns: 1.00x faster                                           |
| sympy_integrate            | 21.4 ms                                                | 21.4 ms: 1.00x slower                                          |
| create_gc_cycles           | 1.48 ms                                                | 1.48 ms: 1.00x slower                                          |
| deepcopy_reduce            | 3.14 us                                                | 3.15 us: 1.00x slower                                          |
| raytrace                   | 306 ms                                                 | 309 ms: 1.01x slower                                           |
| dask                       | 365 ms                                                 | 368 ms: 1.01x slower                                           |
| mdp                        | 2.79 sec                                               | 2.82 sec: 1.01x slower                                         |
| docutils                   | 2.69 sec                                               | 2.72 sec: 1.01x slower                                         |
| pathlib                    | 18.5 ms                                                | 18.7 ms: 1.01x slower                                          |
| tornado_http               | 97.7 ms                                                | 99.1 ms: 1.01x slower                                          |
| pickle_dict                | 34.8 us                                                | 35.5 us: 1.02x slower                                          |
| logging_format             | 6.83 us                                                | 6.98 us: 1.02x slower                                          |
| sqlglot_normalize          | 112 ms                                                 | 115 ms: 1.03x slower                                           |
| bench_thread_pool          | 833 us                                                 | 858 us: 1.03x slower                                           |
| pidigits                   | 190 ms                                                 | 196 ms: 1.03x slower                                           |
| regex_effbot               | 3.45 ms                                                | 3.57 ms: 1.04x slower                                          |
| richards                   | 48.9 ms                                                | 50.8 ms: 1.04x slower                                          |
| scimark_sor                | 121 ms                                                 | 127 ms: 1.05x slower                                           |
| xml_etree_iterparse        | 109 ms                                                 | 114 ms: 1.05x slower                                           |
| pickle                     | 11.1 us                                                | 11.7 us: 1.05x slower                                          |
| deepcopy_memo              | 38.9 us                                                | 41.1 us: 1.06x slower                                          |
| chaos                      | 71.4 ms                                                | 75.6 ms: 1.06x slower                                          |
| unpack_sequence            | 43.3 ns                                                | 46.0 ns: 1.06x slower                                          |
| sqlglot_optimize           | 55.2 ms                                                | 58.6 ms: 1.06x slower                                          |
| regex_dna                  | 204 ms                                                 | 217 ms: 1.06x slower                                           |
| regex_v8                   | 22.9 ms                                                | 24.5 ms: 1.07x slower                                          |
| dulwich_log                | 64.9 ms                                                | 69.6 ms: 1.07x slower                                          |
| scimark_lu                 | 112 ms                                                 | 120 ms: 1.07x slower                                           |
| unpickle                   | 13.9 us                                                | 14.9 us: 1.07x slower                                          |
| meteor_contest             | 109 ms                                                 | 118 ms: 1.08x slower                                           |
| 2to3                       | 266 ms                                                 | 288 ms: 1.08x slower                                           |
| tomli_loads                | 2.31 sec                                               | 2.51 sec: 1.09x slower                                         |
| chameleon                  | 6.86 ms                                                | 7.46 ms: 1.09x slower                                          |
| pprint_safe_repr           | 743 ms                                                 | 812 ms: 1.09x slower                                           |
| pprint_pformat             | 1.53 sec                                               | 1.69 sec: 1.10x slower                                         |
| scimark_monte_carlo        | 71.8 ms                                                | 80.1 ms: 1.12x slower                                          |
| xml_etree_process          | 56.5 ms                                                | 63.1 ms: 1.12x slower                                          |
| nqueens                    | 86.8 ms                                                | 97.0 ms: 1.12x slower                                          |
| crypto_pyaes               | 77.5 ms                                                | 86.6 ms: 1.12x slower                                          |
| pickle_list                | 4.65 us                                                | 5.20 us: 1.12x slower                                          |
| sqlite_synth               | 2.58 us                                                | 2.89 us: 1.12x slower                                          |
| regex_compile              | 141 ms                                                 | 160 ms: 1.13x slower                                           |
| fannkuch                   | 410 ms                                                 | 464 ms: 1.13x slower                                           |
| go                         | 143 ms                                                 | 163 ms: 1.14x slower                                           |
| xml_etree_generate         | 80.4 ms                                                | 92.6 ms: 1.15x slower                                          |
| coverage                   | 81.2 ms                                                | 94.8 ms: 1.17x slower                                          |
| float                      | 78.9 ms                                                | 94.4 ms: 1.20x slower                                          |
| python_startup             | 8.69 ms                                                | 10.4 ms: 1.20x slower                                          |
| nbody                      | 91.6 ms                                                | 112 ms: 1.22x slower                                           |
| async_generators           | 375 ms                                                 | 460 ms: 1.23x slower                                           |
| pyflate                    | 426 ms                                                 | 543 ms: 1.28x slower                                           |
| deltablue                  | 3.80 ms                                                | 4.87 ms: 1.28x slower                                          |
| telco                      | 6.72 ms                                                | 8.64 ms: 1.29x slower                                          |
| scimark_sparse_mat_mult    | 4.80 ms                                                | 6.23 ms: 1.30x slower                                          |
| hexiom                     | 6.74 ms                                                | 8.90 ms: 1.32x slower                                          |
| mako                       | 10.8 ms                                                | 14.5 ms: 1.34x slower                                          |
| scimark_fft                | 342 ms                                                 | 463 ms: 1.35x slower                                           |
| spectral_norm              | 105 ms                                                 | 156 ms: 1.49x slower                                           |
| python_startup_no_site     | 6.09 ms                                                | 9.05 ms: 1.49x slower                                          |
| Geometric mean             | (ref)                                                  | 1.01x slower                                                   |

Benchmark hidden because not significant (5): bench_mp_pool, unpickle_pure_python, sympy_expand, deepcopy, pycparser
Ignored benchmarks (12) of results/bm-20221024-3.11.0-deaf509/bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift


# HPT report

- Reliability score: 99.89% likely to be slow
- 90% likely to have a slowdown of 1.01x
- 95% likely to have a slowdown of 1.01x
- 99% likely to have a slowdown of 1.00x
