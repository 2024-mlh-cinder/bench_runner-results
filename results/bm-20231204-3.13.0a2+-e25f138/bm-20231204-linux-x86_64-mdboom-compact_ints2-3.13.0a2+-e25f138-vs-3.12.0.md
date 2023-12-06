
# Results vs. 3.12.0

- fork: mdboom
- ref: compact_ints2
- machine: linux-x86_64
- commit hash: e25f138
- commit date: 2023-12-04
- overall geometric mean: 1.02x faster \*
- HPT reliability: 99.96%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231204-linux-x86_64-mdboom-compact_ints2-3.13.0a2+-e25f138 |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------:|
| 2to3           | 274 ms                                                 | 264 ms: 1.04x faster                                            |
| chameleon      | 7.41 ms                                                | 7.01 ms: 1.06x faster                                           |
| docutils       | 2.75 sec                                               | 2.60 sec: 1.06x faster                                          |
| tornado_http   | 101 ms                                                 | 94.6 ms: 1.06x faster                                           |
| Geometric mean | (ref)                                                  | 1.05x faster                                                    |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231204-linux-x86_64-mdboom-compact_ints2-3.13.0a2+-e25f138 |
|----------------------------|:------------------------------------------------------:|:---------------------------------------------------------------:|
| async_tree_none            | 475 ms                                                 | 438 ms: 1.08x faster                                            |
| async_tree_memoization     | 580 ms                                                 | 566 ms: 1.02x faster                                            |
| async_tree_cpu_io_mixed    | 724 ms                                                 | 709 ms: 1.02x faster                                            |
| async_tree_cpu_io_mixed_tg | 725 ms                                                 | 738 ms: 1.02x slower                                            |
| async_tree_none_tg         | 447 ms                                                 | 457 ms: 1.02x slower                                            |
| async_tree_io              | 1.16 sec                                               | 1.19 sec: 1.02x slower                                          |
| async_tree_io_tg           | 1.19 sec                                               | 1.23 sec: 1.03x slower                                          |
| async_tree_memoization_tg  | 574 ms                                                 | 599 ms: 1.04x slower                                            |
| Geometric mean             | (ref)                                                  | 1.00x slower                                                    |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231204-linux-x86_64-mdboom-compact_ints2-3.13.0a2+-e25f138 |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------:|
| nbody          | 92.2 ms                                                | 90.1 ms: 1.02x faster                                           |
| float          | 83.3 ms                                                | 82.2 ms: 1.01x faster                                           |
| pidigits       | 187 ms                                                 | 187 ms: 1.00x faster                                            |
| Geometric mean | (ref)                                                  | 1.01x faster                                                    |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231204-linux-x86_64-mdboom-compact_ints2-3.13.0a2+-e25f138 |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------:|
| regex_compile  | 148 ms                                                 | 135 ms: 1.10x faster                                            |
| regex_effbot   | 3.57 ms                                                | 3.71 ms: 1.04x slower                                           |
| regex_dna      | 209 ms                                                 | 220 ms: 1.06x slower                                            |
| regex_v8       | 22.7 ms                                                | 26.4 ms: 1.17x slower                                           |
| Geometric mean | (ref)                                                  | 1.04x slower                                                    |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231204-linux-x86_64-mdboom-compact_ints2-3.13.0a2+-e25f138 |
|----------------------|:------------------------------------------------------:|:---------------------------------------------------------------:|
| pickle_pure_python   | 326 us                                                 | 302 us: 1.08x faster                                            |
| unpickle_pure_python | 230 us                                                 | 218 us: 1.05x faster                                            |
| unpickle             | 15.8 us                                                | 15.0 us: 1.05x faster                                           |
| tomli_loads          | 2.30 sec                                               | 2.23 sec: 1.03x faster                                          |
| xml_etree_process    | 61.2 ms                                                | 59.6 ms: 1.03x faster                                           |
| xml_etree_generate   | 88.7 ms                                                | 86.8 ms: 1.02x faster                                           |
| unpickle_list        | 5.04 us                                                | 4.98 us: 1.01x faster                                           |
| json_loads           | 28.4 us                                                | 28.0 us: 1.01x faster                                           |
| json_dumps           | 10.6 ms                                                | 10.5 ms: 1.01x faster                                           |
| pickle_dict          | 33.5 us                                                | 33.7 us: 1.01x slower                                           |
| pickle_list          | 4.67 us                                                | 4.88 us: 1.05x slower                                           |
| Geometric mean       | (ref)                                                  | 1.02x faster                                                    |

Benchmark hidden because not significant (3): xml_etree_parse, xml_etree_iterparse, pickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231204-linux-x86_64-mdboom-compact_ints2-3.13.0a2+-e25f138 |
|------------------------|:------------------------------------------------------:|:---------------------------------------------------------------:|
| python_startup         | 9.53 ms                                                | 10.3 ms: 1.08x slower                                           |
| python_startup_no_site | 6.92 ms                                                | 8.99 ms: 1.30x slower                                           |
| Geometric mean         | (ref)                                                  | 1.19x slower                                                    |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231204-linux-x86_64-mdboom-compact_ints2-3.13.0a2+-e25f138 |
|-----------|:------------------------------------------------------:|:---------------------------------------------------------------:|
| mako      | 11.5 ms                                                | 11.3 ms: 1.01x faster                                           |

All benchmarks:
===============

| Benchmark                  | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231204-linux-x86_64-mdboom-compact_ints2-3.13.0a2+-e25f138 |
|----------------------------|:------------------------------------------------------:|:---------------------------------------------------------------:|
| typing_runtime_protocols   | 153 us                                                 | 115 us: 1.34x faster                                            |
| comprehensions             | 20.9 us                                                | 16.4 us: 1.27x faster                                           |
| unpack_sequence            | 54.2 ns                                                | 45.8 ns: 1.18x faster                                           |
| crypto_pyaes               | 83.6 ms                                                | 71.0 ms: 1.18x faster                                           |
| sympy_sum                  | 167 ms                                                 | 147 ms: 1.14x faster                                            |
| logging_format             | 7.10 us                                                | 6.27 us: 1.13x faster                                           |
| logging_simple             | 6.38 us                                                | 5.71 us: 1.12x faster                                           |
| deltablue                  | 3.71 ms                                                | 3.33 ms: 1.11x faster                                           |
| sympy_str                  | 296 ms                                                 | 266 ms: 1.11x faster                                            |
| generators                 | 32.5 ms                                                | 29.2 ms: 1.11x faster                                           |
| raytrace                   | 308 ms                                                 | 277 ms: 1.11x faster                                            |
| chaos                      | 67.5 ms                                                | 61.4 ms: 1.10x faster                                           |
| regex_compile              | 148 ms                                                 | 135 ms: 1.10x faster                                            |
| sympy_integrate            | 21.2 ms                                                | 19.4 ms: 1.09x faster                                           |
| async_tree_none            | 475 ms                                                 | 438 ms: 1.08x faster                                            |
| scimark_monte_carlo        | 74.6 ms                                                | 68.8 ms: 1.08x faster                                           |
| scimark_sparse_mat_mult    | 5.33 ms                                                | 4.92 ms: 1.08x faster                                           |
| nqueens                    | 86.2 ms                                                | 79.6 ms: 1.08x faster                                           |
| pickle_pure_python         | 326 us                                                 | 302 us: 1.08x faster                                            |
| sqlglot_parse              | 1.35 ms                                                | 1.26 ms: 1.07x faster                                           |
| coroutines                 | 23.5 ms                                                | 22.0 ms: 1.07x faster                                           |
| tornado_http               | 101 ms                                                 | 94.6 ms: 1.06x faster                                           |
| sqlglot_transpile          | 1.68 ms                                                | 1.58 ms: 1.06x faster                                           |
| hexiom                     | 6.54 ms                                                | 6.18 ms: 1.06x faster                                           |
| dulwich_log                | 68.7 ms                                                | 64.9 ms: 1.06x faster                                           |
| sqlglot_normalize          | 112 ms                                                 | 105 ms: 1.06x faster                                            |
| docutils                   | 2.75 sec                                               | 2.60 sec: 1.06x faster                                          |
| chameleon                  | 7.41 ms                                                | 7.01 ms: 1.06x faster                                           |
| sympy_expand               | 476 ms                                                 | 451 ms: 1.06x faster                                            |
| pathlib                    | 18.9 ms                                                | 17.9 ms: 1.05x faster                                           |
| unpickle_pure_python       | 230 us                                                 | 218 us: 1.05x faster                                            |
| scimark_lu                 | 120 ms                                                 | 115 ms: 1.05x faster                                            |
| unpickle                   | 15.8 us                                                | 15.0 us: 1.05x faster                                           |
| asyncio_tcp                | 506 ms                                                 | 484 ms: 1.04x faster                                            |
| pprint_safe_repr           | 765 ms                                                 | 732 ms: 1.04x faster                                            |
| deepcopy                   | 363 us                                                 | 347 us: 1.04x faster                                            |
| scimark_fft                | 381 ms                                                 | 366 ms: 1.04x faster                                            |
| deepcopy_reduce            | 3.23 us                                                | 3.11 us: 1.04x faster                                           |
| 2to3                       | 274 ms                                                 | 264 ms: 1.04x faster                                            |
| scimark_sor                | 129 ms                                                 | 125 ms: 1.04x faster                                            |
| async_generators           | 459 ms                                                 | 443 ms: 1.04x faster                                            |
| fannkuch                   | 410 ms                                                 | 395 ms: 1.04x faster                                            |
| pprint_pformat             | 1.55 sec                                               | 1.50 sec: 1.03x faster                                          |
| tomli_loads                | 2.30 sec                                               | 2.23 sec: 1.03x faster                                          |
| xml_etree_process          | 61.2 ms                                                | 59.6 ms: 1.03x faster                                           |
| gc_traversal               | 4.28 ms                                                | 4.17 ms: 1.03x faster                                           |
| sqlglot_optimize           | 54.8 ms                                                | 53.5 ms: 1.02x faster                                           |
| async_tree_memoization     | 580 ms                                                 | 566 ms: 1.02x faster                                            |
| meteor_contest             | 110 ms                                                 | 107 ms: 1.02x faster                                            |
| nbody                      | 92.2 ms                                                | 90.1 ms: 1.02x faster                                           |
| xml_etree_generate         | 88.7 ms                                                | 86.8 ms: 1.02x faster                                           |
| async_tree_cpu_io_mixed    | 724 ms                                                 | 709 ms: 1.02x faster                                            |
| bench_thread_pool          | 845 us                                                 | 828 us: 1.02x faster                                            |
| deepcopy_memo              | 39.7 us                                                | 39.0 us: 1.02x faster                                           |
| spectral_norm              | 115 ms                                                 | 113 ms: 1.02x faster                                            |
| float                      | 83.3 ms                                                | 82.2 ms: 1.01x faster                                           |
| unpickle_list              | 5.04 us                                                | 4.98 us: 1.01x faster                                           |
| mako                       | 11.5 ms                                                | 11.3 ms: 1.01x faster                                           |
| json_loads                 | 28.4 us                                                | 28.0 us: 1.01x faster                                           |
| sqlite_synth               | 2.83 us                                                | 2.80 us: 1.01x faster                                           |
| pyflate                    | 471 ms                                                 | 465 ms: 1.01x faster                                            |
| json                       | 5.22 ms                                                | 5.17 ms: 1.01x faster                                           |
| json_dumps                 | 10.6 ms                                                | 10.5 ms: 1.01x faster                                           |
| logging_silent             | 108 ns                                                 | 107 ns: 1.00x faster                                            |
| pidigits                   | 187 ms                                                 | 187 ms: 1.00x faster                                            |
| asyncio_tcp_ssl            | 1.78 sec                                               | 1.78 sec: 1.00x slower                                          |
| pickle_dict                | 33.5 us                                                | 33.7 us: 1.01x slower                                           |
| go                         | 140 ms                                                 | 142 ms: 1.01x slower                                            |
| create_gc_cycles           | 1.45 ms                                                | 1.47 ms: 1.02x slower                                           |
| async_tree_cpu_io_mixed_tg | 725 ms                                                 | 738 ms: 1.02x slower                                            |
| async_tree_none_tg         | 447 ms                                                 | 457 ms: 1.02x slower                                            |
| async_tree_io              | 1.16 sec                                               | 1.19 sec: 1.02x slower                                          |
| async_tree_io_tg           | 1.19 sec                                               | 1.23 sec: 1.03x slower                                          |
| richards                   | 46.0 ms                                                | 47.8 ms: 1.04x slower                                           |
| regex_effbot               | 3.57 ms                                                | 3.71 ms: 1.04x slower                                           |
| pycparser                  | 1.17 sec                                               | 1.22 sec: 1.04x slower                                          |
| richards_super             | 51.9 ms                                                | 54.0 ms: 1.04x slower                                           |
| async_tree_memoization_tg  | 574 ms                                                 | 599 ms: 1.04x slower                                            |
| pickle_list                | 4.67 us                                                | 4.88 us: 1.05x slower                                           |
| regex_dna                  | 209 ms                                                 | 220 ms: 1.06x slower                                            |
| python_startup             | 9.53 ms                                                | 10.3 ms: 1.08x slower                                           |
| mdp                        | 2.57 sec                                               | 2.81 sec: 1.09x slower                                          |
| telco                      | 7.18 ms                                                | 8.28 ms: 1.15x slower                                           |
| regex_v8                   | 22.7 ms                                                | 26.4 ms: 1.17x slower                                           |
| coverage                   | 75.1 ms                                                | 94.7 ms: 1.26x slower                                           |
| python_startup_no_site     | 6.92 ms                                                | 8.99 ms: 1.30x slower                                           |
| mypy2                      | 351 ms                                                 | 838 ms: 2.39x slower                                            |
| Geometric mean             | (ref)                                                  | 1.02x faster                                                    |

Benchmark hidden because not significant (5): xml_etree_parse, asyncio_websockets, bench_mp_pool, xml_etree_iterparse, pickle
Ignored benchmarks (6) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, dask, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 99.96% likely to be faster
- 90% likely to have a speedup of 1.01x
- 95% likely to have a speedup of 1.01x
- 99% likely to have a speedup of 1.00x
