
# Results vs. 3.11.0

- fork: mdboom
- ref: compact_ints2
- machine: linux-x86_64
- commit hash: e25f138
- commit date: 2023-12-04
- overall geometric mean: 1.05x faster \*
- HPT reliability: 99.96%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231204-linux-x86_64-mdboom-compact_ints2-3.13.0a2+-e25f138 |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------:|
| 2to3           | 266 ms                                                 | 264 ms: 1.01x faster                                            |
| chameleon      | 6.86 ms                                                | 7.01 ms: 1.02x slower                                           |
| docutils       | 2.69 sec                                               | 2.60 sec: 1.03x faster                                          |
| tornado_http   | 97.7 ms                                                | 94.6 ms: 1.03x faster                                           |
| Geometric mean | (ref)                                                  | 1.01x faster                                                    |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231204-linux-x86_64-mdboom-compact_ints2-3.13.0a2+-e25f138 |
|----------------------------|:------------------------------------------------------:|:---------------------------------------------------------------:|
| async_tree_none            | 532 ms                                                 | 438 ms: 1.21x faster                                            |
| async_tree_memoization     | 640 ms                                                 | 566 ms: 1.13x faster                                            |
| async_tree_io              | 1.31 sec                                               | 1.19 sec: 1.10x faster                                          |
| async_tree_none_tg         | 490 ms                                                 | 457 ms: 1.07x faster                                            |
| async_tree_io_tg           | 1.30 sec                                               | 1.23 sec: 1.06x faster                                          |
| async_tree_cpu_io_mixed    | 750 ms                                                 | 709 ms: 1.06x faster                                            |
| async_tree_memoization_tg  | 627 ms                                                 | 599 ms: 1.05x faster                                            |
| async_tree_cpu_io_mixed_tg | 764 ms                                                 | 738 ms: 1.04x faster                                            |
| Geometric mean             | (ref)                                                  | 1.09x faster                                                    |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231204-linux-x86_64-mdboom-compact_ints2-3.13.0a2+-e25f138 |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------:|
| pidigits       | 190 ms                                                 | 187 ms: 1.02x faster                                            |
| nbody          | 91.6 ms                                                | 90.1 ms: 1.02x faster                                           |
| float          | 78.9 ms                                                | 82.2 ms: 1.04x slower                                           |
| Geometric mean | (ref)                                                  | 1.00x slower                                                    |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231204-linux-x86_64-mdboom-compact_ints2-3.13.0a2+-e25f138 |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------:|
| regex_compile  | 141 ms                                                 | 135 ms: 1.05x faster                                            |
| regex_effbot   | 3.45 ms                                                | 3.71 ms: 1.07x slower                                           |
| regex_dna      | 204 ms                                                 | 220 ms: 1.08x slower                                            |
| regex_v8       | 22.9 ms                                                | 26.4 ms: 1.15x slower                                           |
| Geometric mean | (ref)                                                  | 1.06x slower                                                    |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231204-linux-x86_64-mdboom-compact_ints2-3.13.0a2+-e25f138 |
|----------------------|:------------------------------------------------------:|:---------------------------------------------------------------:|
| json_dumps           | 13.5 ms                                                | 10.5 ms: 1.28x faster                                           |
| unpickle_pure_python | 241 us                                                 | 218 us: 1.10x faster                                            |
| pickle_pure_python   | 319 us                                                 | 302 us: 1.06x faster                                            |
| json_loads           | 29.4 us                                                | 28.0 us: 1.05x faster                                           |
| unpickle_list        | 5.22 us                                                | 4.98 us: 1.05x faster                                           |
| tomli_loads          | 2.31 sec                                               | 2.23 sec: 1.04x faster                                          |
| pickle_dict          | 34.8 us                                                | 33.7 us: 1.03x faster                                           |
| xml_etree_parse      | 163 ms                                                 | 158 ms: 1.03x faster                                            |
| xml_etree_iterparse  | 109 ms                                                 | 106 ms: 1.03x faster                                            |
| pickle               | 11.1 us                                                | 11.2 us: 1.01x slower                                           |
| pickle_list          | 4.65 us                                                | 4.88 us: 1.05x slower                                           |
| xml_etree_process    | 56.5 ms                                                | 59.6 ms: 1.05x slower                                           |
| xml_etree_generate   | 80.4 ms                                                | 86.8 ms: 1.08x slower                                           |
| unpickle             | 13.9 us                                                | 15.0 us: 1.08x slower                                           |
| Geometric mean       | (ref)                                                  | 1.02x faster                                                    |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231204-linux-x86_64-mdboom-compact_ints2-3.13.0a2+-e25f138 |
|------------------------|:------------------------------------------------------:|:---------------------------------------------------------------:|
| python_startup         | 8.69 ms                                                | 10.3 ms: 1.19x slower                                           |
| python_startup_no_site | 6.09 ms                                                | 8.99 ms: 1.48x slower                                           |
| Geometric mean         | (ref)                                                  | 1.32x slower                                                    |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231204-linux-x86_64-mdboom-compact_ints2-3.13.0a2+-e25f138 |
|-----------|:------------------------------------------------------:|:---------------------------------------------------------------:|
| mako      | 10.8 ms                                                | 11.3 ms: 1.05x slower                                           |

All benchmarks:
===============

| Benchmark                  | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231204-linux-x86_64-mdboom-compact_ints2-3.13.0a2+-e25f138 |
|----------------------------|:------------------------------------------------------:|:---------------------------------------------------------------:|
| typing_runtime_protocols   | 521 us                                                 | 115 us: 4.54x faster                                            |
| generators                 | 76.5 ms                                                | 29.2 ms: 2.62x faster                                           |
| asyncio_tcp                | 887 ms                                                 | 484 ms: 1.83x faster                                            |
| asyncio_tcp_ssl            | 3.13 sec                                               | 1.78 sec: 1.75x faster                                          |
| comprehensions             | 23.6 us                                                | 16.4 us: 1.43x faster                                           |
| json_dumps                 | 13.5 ms                                                | 10.5 ms: 1.28x faster                                           |
| async_tree_none            | 532 ms                                                 | 438 ms: 1.21x faster                                            |
| coroutines                 | 26.1 ms                                                | 22.0 ms: 1.19x faster                                           |
| chaos                      | 71.4 ms                                                | 61.4 ms: 1.16x faster                                           |
| sympy_sum                  | 170 ms                                                 | 147 ms: 1.16x faster                                            |
| deltablue                  | 3.80 ms                                                | 3.33 ms: 1.14x faster                                           |
| richards_super             | 61.2 ms                                                | 54.0 ms: 1.13x faster                                           |
| sqlglot_parse              | 1.43 ms                                                | 1.26 ms: 1.13x faster                                           |
| async_tree_memoization     | 640 ms                                                 | 566 ms: 1.13x faster                                            |
| sympy_str                  | 299 ms                                                 | 266 ms: 1.12x faster                                            |
| sqlglot_transpile          | 1.75 ms                                                | 1.58 ms: 1.11x faster                                           |
| raytrace                   | 306 ms                                                 | 277 ms: 1.11x faster                                            |
| unpickle_pure_python       | 241 us                                                 | 218 us: 1.10x faster                                            |
| sympy_integrate            | 21.4 ms                                                | 19.4 ms: 1.10x faster                                           |
| async_tree_io              | 1.31 sec                                               | 1.19 sec: 1.10x faster                                          |
| logging_simple             | 6.24 us                                                | 5.71 us: 1.09x faster                                           |
| crypto_pyaes               | 77.5 ms                                                | 71.0 ms: 1.09x faster                                           |
| hexiom                     | 6.74 ms                                                | 6.18 ms: 1.09x faster                                           |
| nqueens                    | 86.8 ms                                                | 79.6 ms: 1.09x faster                                           |
| logging_format             | 6.83 us                                                | 6.27 us: 1.09x faster                                           |
| sympy_expand               | 490 ms                                                 | 451 ms: 1.09x faster                                            |
| async_tree_none_tg         | 490 ms                                                 | 457 ms: 1.07x faster                                            |
| sqlglot_normalize          | 112 ms                                                 | 105 ms: 1.07x faster                                            |
| async_tree_io_tg           | 1.30 sec                                               | 1.23 sec: 1.06x faster                                          |
| async_tree_cpu_io_mixed    | 750 ms                                                 | 709 ms: 1.06x faster                                            |
| pickle_pure_python         | 319 us                                                 | 302 us: 1.06x faster                                            |
| json_loads                 | 29.4 us                                                | 28.0 us: 1.05x faster                                           |
| unpickle_list              | 5.22 us                                                | 4.98 us: 1.05x faster                                           |
| regex_compile              | 141 ms                                                 | 135 ms: 1.05x faster                                            |
| async_tree_memoization_tg  | 627 ms                                                 | 599 ms: 1.05x faster                                            |
| scimark_monte_carlo        | 71.8 ms                                                | 68.8 ms: 1.04x faster                                           |
| deepcopy                   | 360 us                                                 | 347 us: 1.04x faster                                            |
| tomli_loads                | 2.31 sec                                               | 2.23 sec: 1.04x faster                                          |
| fannkuch                   | 410 ms                                                 | 395 ms: 1.04x faster                                            |
| async_tree_cpu_io_mixed_tg | 764 ms                                                 | 738 ms: 1.04x faster                                            |
| docutils                   | 2.69 sec                                               | 2.60 sec: 1.03x faster                                          |
| pickle_dict                | 34.8 us                                                | 33.7 us: 1.03x faster                                           |
| tornado_http               | 97.7 ms                                                | 94.6 ms: 1.03x faster                                           |
| sqlglot_optimize           | 55.2 ms                                                | 53.5 ms: 1.03x faster                                           |
| pathlib                    | 18.5 ms                                                | 17.9 ms: 1.03x faster                                           |
| xml_etree_parse            | 163 ms                                                 | 158 ms: 1.03x faster                                            |
| xml_etree_iterparse        | 109 ms                                                 | 106 ms: 1.03x faster                                            |
| richards                   | 48.9 ms                                                | 47.8 ms: 1.02x faster                                           |
| pidigits                   | 190 ms                                                 | 187 ms: 1.02x faster                                            |
| pprint_pformat             | 1.53 sec                                               | 1.50 sec: 1.02x faster                                          |
| nbody                      | 91.6 ms                                                | 90.1 ms: 1.02x faster                                           |
| meteor_contest             | 109 ms                                                 | 107 ms: 1.02x faster                                            |
| pprint_safe_repr           | 743 ms                                                 | 732 ms: 1.01x faster                                            |
| json                       | 5.24 ms                                                | 5.17 ms: 1.01x faster                                           |
| logging_silent             | 108 ns                                                 | 107 ns: 1.01x faster                                            |
| go                         | 143 ms                                                 | 142 ms: 1.01x faster                                            |
| deepcopy_reduce            | 3.14 us                                                | 3.11 us: 1.01x faster                                           |
| asyncio_websockets         | 556 ms                                                 | 551 ms: 1.01x faster                                            |
| 2to3                       | 266 ms                                                 | 264 ms: 1.01x faster                                            |
| bench_thread_pool          | 833 us                                                 | 828 us: 1.01x faster                                            |
| mdp                        | 2.79 sec                                               | 2.81 sec: 1.01x slower                                          |
| pickle                     | 11.1 us                                                | 11.2 us: 1.01x slower                                           |
| pycparser                  | 1.20 sec                                               | 1.22 sec: 1.02x slower                                          |
| scimark_lu                 | 112 ms                                                 | 115 ms: 1.02x slower                                            |
| chameleon                  | 6.86 ms                                                | 7.01 ms: 1.02x slower                                           |
| scimark_sparse_mat_mult    | 4.80 ms                                                | 4.92 ms: 1.02x slower                                           |
| scimark_sor                | 121 ms                                                 | 125 ms: 1.03x slower                                            |
| float                      | 78.9 ms                                                | 82.2 ms: 1.04x slower                                           |
| mako                       | 10.8 ms                                                | 11.3 ms: 1.05x slower                                           |
| pickle_list                | 4.65 us                                                | 4.88 us: 1.05x slower                                           |
| xml_etree_process          | 56.5 ms                                                | 59.6 ms: 1.05x slower                                           |
| unpack_sequence            | 43.3 ns                                                | 45.8 ns: 1.06x slower                                           |
| gc_traversal               | 3.90 ms                                                | 4.17 ms: 1.07x slower                                           |
| scimark_fft                | 342 ms                                                 | 366 ms: 1.07x slower                                            |
| spectral_norm              | 105 ms                                                 | 113 ms: 1.07x slower                                            |
| regex_effbot               | 3.45 ms                                                | 3.71 ms: 1.07x slower                                           |
| regex_dna                  | 204 ms                                                 | 220 ms: 1.08x slower                                            |
| xml_etree_generate         | 80.4 ms                                                | 86.8 ms: 1.08x slower                                           |
| unpickle                   | 13.9 us                                                | 15.0 us: 1.08x slower                                           |
| sqlite_synth               | 2.58 us                                                | 2.80 us: 1.09x slower                                           |
| pyflate                    | 426 ms                                                 | 465 ms: 1.09x slower                                            |
| regex_v8                   | 22.9 ms                                                | 26.4 ms: 1.15x slower                                           |
| coverage                   | 81.2 ms                                                | 94.7 ms: 1.17x slower                                           |
| async_generators           | 375 ms                                                 | 443 ms: 1.18x slower                                            |
| python_startup             | 8.69 ms                                                | 10.3 ms: 1.19x slower                                           |
| telco                      | 6.72 ms                                                | 8.28 ms: 1.23x slower                                           |
| python_startup_no_site     | 6.09 ms                                                | 8.99 ms: 1.48x slower                                           |
| mypy2                      | 427 ms                                                 | 838 ms: 1.96x slower                                            |
| Geometric mean             | (ref)                                                  | 1.05x faster                                                    |

Benchmark hidden because not significant (4): create_gc_cycles, dulwich_log, bench_mp_pool, deepcopy_memo
Ignored benchmarks (13) of results/bm-20221024-3.11.0-deaf509/bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift


# HPT report

- Reliability score: 99.96% likely to be faster
- 90% likely to have a speedup of 1.01x
- 95% likely to have a speedup of 1.01x
- 99% likely to have a speedup of 1.00x
