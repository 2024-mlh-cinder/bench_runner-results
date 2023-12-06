
# Results vs. 3.12.0

- fork: mdboom
- ref: test_branch
- machine: linux-x86_64
- commit hash: 3ce7ef8
- commit date: 2023-11-14
- overall geometric mean: 1.05x slower \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.01x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231114-linux-x86_64-mdboom-test_branch-3.13.0a1+-3ce7ef8 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| 2to3           | 274 ms                                                 | 294 ms: 1.07x slower                                          |
| chameleon      | 7.41 ms                                                | 7.48 ms: 1.01x slower                                         |
| docutils       | 2.75 sec                                               | 2.74 sec: 1.00x faster                                        |
| tornado_http   | 101 ms                                                 | 102 ms: 1.02x slower                                          |
| Geometric mean | (ref)                                                  | 1.02x slower                                                  |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231114-linux-x86_64-mdboom-test_branch-3.13.0a1+-3ce7ef8 |
|----------------------------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| async_tree_none            | 475 ms                                                 | 463 ms: 1.03x faster                                          |
| async_tree_memoization     | 580 ms                                                 | 590 ms: 1.02x slower                                          |
| async_tree_cpu_io_mixed    | 724 ms                                                 | 742 ms: 1.02x slower                                          |
| async_tree_io              | 1.16 sec                                               | 1.23 sec: 1.06x slower                                        |
| async_tree_cpu_io_mixed_tg | 725 ms                                                 | 768 ms: 1.06x slower                                          |
| async_tree_io_tg           | 1.19 sec                                               | 1.26 sec: 1.06x slower                                        |
| async_tree_memoization_tg  | 574 ms                                                 | 610 ms: 1.06x slower                                          |
| async_tree_none_tg         | 447 ms                                                 | 477 ms: 1.06x slower                                          |
| Geometric mean             | (ref)                                                  | 1.04x slower                                                  |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231114-linux-x86_64-mdboom-test_branch-3.13.0a1+-3ce7ef8 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| pidigits       | 187 ms                                                 | 188 ms: 1.01x slower                                          |
| float          | 83.3 ms                                                | 102 ms: 1.22x slower                                          |
| nbody          | 92.2 ms                                                | 122 ms: 1.33x slower                                          |
| Geometric mean | (ref)                                                  | 1.18x slower                                                  |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231114-linux-x86_64-mdboom-test_branch-3.13.0a1+-3ce7ef8 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| regex_effbot   | 3.57 ms                                                | 3.50 ms: 1.02x faster                                         |
| regex_dna      | 209 ms                                                 | 213 ms: 1.02x slower                                          |
| regex_v8       | 22.7 ms                                                | 24.8 ms: 1.10x slower                                         |
| regex_compile  | 148 ms                                                 | 166 ms: 1.12x slower                                          |
| Geometric mean | (ref)                                                  | 1.05x slower                                                  |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231114-linux-x86_64-mdboom-test_branch-3.13.0a1+-3ce7ef8 |
|----------------------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| pickle_pure_python   | 326 us                                                 | 308 us: 1.06x faster                                          |
| pickle_dict          | 33.5 us                                                | 32.4 us: 1.03x faster                                         |
| unpickle             | 15.8 us                                                | 15.4 us: 1.02x faster                                         |
| xml_etree_process    | 61.2 ms                                                | 59.9 ms: 1.02x faster                                         |
| pickle               | 11.2 us                                                | 11.0 us: 1.02x faster                                         |
| json_loads           | 28.4 us                                                | 28.1 us: 1.01x faster                                         |
| xml_etree_generate   | 88.7 ms                                                | 87.9 ms: 1.01x faster                                         |
| json_dumps           | 10.6 ms                                                | 10.5 ms: 1.01x faster                                         |
| pickle_list          | 4.67 us                                                | 4.92 us: 1.05x slower                                         |
| unpickle_pure_python | 230 us                                                 | 242 us: 1.05x slower                                          |
| unpickle_list        | 5.04 us                                                | 5.33 us: 1.06x slower                                         |
| xml_etree_iterparse  | 106 ms                                                 | 114 ms: 1.08x slower                                          |
| tomli_loads          | 2.30 sec                                               | 3.07 sec: 1.33x slower                                        |
| Geometric mean       | (ref)                                                  | 1.02x slower                                                  |

Benchmark hidden because not significant (1): xml_etree_parse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231114-linux-x86_64-mdboom-test_branch-3.13.0a1+-3ce7ef8 |
|------------------------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| python_startup         | 9.53 ms                                                | 10.3 ms: 1.08x slower                                         |
| python_startup_no_site | 6.92 ms                                                | 9.05 ms: 1.31x slower                                         |
| Geometric mean         | (ref)                                                  | 1.19x slower                                                  |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231114-linux-x86_64-mdboom-test_branch-3.13.0a1+-3ce7ef8 |
|-----------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| mako      | 11.5 ms                                                | 14.5 ms: 1.26x slower                                         |

All benchmarks:
===============

| Benchmark                  | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231114-linux-x86_64-mdboom-test_branch-3.13.0a1+-3ce7ef8 |
|----------------------------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| typing_runtime_protocols   | 153 us                                                 | 127 us: 1.20x faster                                          |
| unpack_sequence            | 54.2 ns                                                | 47.5 ns: 1.14x faster                                         |
| generators                 | 32.5 ms                                                | 29.2 ms: 1.11x faster                                         |
| gc_traversal               | 4.28 ms                                                | 3.87 ms: 1.10x faster                                         |
| sympy_sum                  | 167 ms                                                 | 155 ms: 1.08x faster                                          |
| coroutines                 | 23.5 ms                                                | 22.0 ms: 1.07x faster                                         |
| pickle_pure_python         | 326 us                                                 | 308 us: 1.06x faster                                          |
| pickle_dict                | 33.5 us                                                | 32.4 us: 1.03x faster                                         |
| deepcopy_reduce            | 3.23 us                                                | 3.13 us: 1.03x faster                                         |
| sympy_str                  | 296 ms                                                 | 288 ms: 1.03x faster                                          |
| async_tree_none            | 475 ms                                                 | 463 ms: 1.03x faster                                          |
| sqlglot_normalize          | 112 ms                                                 | 109 ms: 1.03x faster                                          |
| unpickle                   | 15.8 us                                                | 15.4 us: 1.02x faster                                         |
| asyncio_tcp                | 506 ms                                                 | 494 ms: 1.02x faster                                          |
| xml_etree_process          | 61.2 ms                                                | 59.9 ms: 1.02x faster                                         |
| regex_effbot               | 3.57 ms                                                | 3.50 ms: 1.02x faster                                         |
| deepcopy                   | 363 us                                                 | 355 us: 1.02x faster                                          |
| spectral_norm              | 115 ms                                                 | 113 ms: 1.02x faster                                          |
| pickle                     | 11.2 us                                                | 11.0 us: 1.02x faster                                         |
| logging_simple             | 6.38 us                                                | 6.29 us: 1.02x faster                                         |
| json                       | 5.22 ms                                                | 5.15 ms: 1.01x faster                                         |
| json_loads                 | 28.4 us                                                | 28.1 us: 1.01x faster                                         |
| xml_etree_generate         | 88.7 ms                                                | 87.9 ms: 1.01x faster                                         |
| scimark_sor                | 129 ms                                                 | 128 ms: 1.01x faster                                          |
| json_dumps                 | 10.6 ms                                                | 10.5 ms: 1.01x faster                                         |
| docutils                   | 2.75 sec                                               | 2.74 sec: 1.00x faster                                        |
| logging_silent             | 108 ns                                                 | 107 ns: 1.00x faster                                          |
| sqlglot_optimize           | 54.8 ms                                                | 54.9 ms: 1.00x slower                                         |
| async_generators           | 459 ms                                                 | 462 ms: 1.00x slower                                          |
| pidigits                   | 187 ms                                                 | 188 ms: 1.01x slower                                          |
| sqlglot_parse              | 1.35 ms                                                | 1.36 ms: 1.01x slower                                         |
| sqlite_synth               | 2.83 us                                                | 2.85 us: 1.01x slower                                         |
| dulwich_log                | 68.7 ms                                                | 69.3 ms: 1.01x slower                                         |
| chameleon                  | 7.41 ms                                                | 7.48 ms: 1.01x slower                                         |
| bench_thread_pool          | 845 us                                                 | 858 us: 1.02x slower                                          |
| asyncio_tcp_ssl            | 1.78 sec                                               | 1.81 sec: 1.02x slower                                        |
| tornado_http               | 101 ms                                                 | 102 ms: 1.02x slower                                          |
| sympy_integrate            | 21.2 ms                                                | 21.6 ms: 1.02x slower                                         |
| async_tree_memoization     | 580 ms                                                 | 590 ms: 1.02x slower                                          |
| create_gc_cycles           | 1.45 ms                                                | 1.48 ms: 1.02x slower                                         |
| mypy2                      | 351 ms                                                 | 358 ms: 1.02x slower                                          |
| regex_dna                  | 209 ms                                                 | 213 ms: 1.02x slower                                          |
| async_tree_cpu_io_mixed    | 724 ms                                                 | 742 ms: 1.02x slower                                          |
| crypto_pyaes               | 83.6 ms                                                | 85.7 ms: 1.03x slower                                         |
| sympy_expand               | 476 ms                                                 | 489 ms: 1.03x slower                                          |
| pycparser                  | 1.17 sec                                               | 1.23 sec: 1.05x slower                                        |
| deepcopy_memo              | 39.7 us                                                | 41.8 us: 1.05x slower                                         |
| pickle_list                | 4.67 us                                                | 4.92 us: 1.05x slower                                         |
| unpickle_pure_python       | 230 us                                                 | 242 us: 1.05x slower                                          |
| pprint_safe_repr           | 765 ms                                                 | 808 ms: 1.06x slower                                          |
| unpickle_list              | 5.04 us                                                | 5.33 us: 1.06x slower                                         |
| async_tree_io              | 1.16 sec                                               | 1.23 sec: 1.06x slower                                        |
| async_tree_cpu_io_mixed_tg | 725 ms                                                 | 768 ms: 1.06x slower                                          |
| async_tree_io_tg           | 1.19 sec                                               | 1.26 sec: 1.06x slower                                        |
| async_tree_memoization_tg  | 574 ms                                                 | 610 ms: 1.06x slower                                          |
| meteor_contest             | 110 ms                                                 | 117 ms: 1.06x slower                                          |
| mdp                        | 2.57 sec                                               | 2.73 sec: 1.06x slower                                        |
| async_tree_none_tg         | 447 ms                                                 | 477 ms: 1.06x slower                                          |
| 2to3                       | 274 ms                                                 | 294 ms: 1.07x slower                                          |
| xml_etree_iterparse        | 106 ms                                                 | 114 ms: 1.08x slower                                          |
| scimark_monte_carlo        | 74.6 ms                                                | 80.5 ms: 1.08x slower                                         |
| pprint_pformat             | 1.55 sec                                               | 1.67 sec: 1.08x slower                                        |
| python_startup             | 9.53 ms                                                | 10.3 ms: 1.08x slower                                         |
| regex_v8                   | 22.7 ms                                                | 24.8 ms: 1.10x slower                                         |
| chaos                      | 67.5 ms                                                | 75.6 ms: 1.12x slower                                         |
| regex_compile              | 148 ms                                                 | 166 ms: 1.12x slower                                          |
| scimark_fft                | 381 ms                                                 | 432 ms: 1.13x slower                                          |
| richards                   | 46.0 ms                                                | 52.5 ms: 1.14x slower                                         |
| richards_super             | 51.9 ms                                                | 59.7 ms: 1.15x slower                                         |
| pyflate                    | 471 ms                                                 | 555 ms: 1.18x slower                                          |
| fannkuch                   | 410 ms                                                 | 492 ms: 1.20x slower                                          |
| nqueens                    | 86.2 ms                                                | 105 ms: 1.21x slower                                          |
| go                         | 140 ms                                                 | 171 ms: 1.22x slower                                          |
| telco                      | 7.18 ms                                                | 8.76 ms: 1.22x slower                                         |
| float                      | 83.3 ms                                                | 102 ms: 1.22x slower                                          |
| comprehensions             | 20.9 us                                                | 25.7 us: 1.23x slower                                         |
| scimark_sparse_mat_mult    | 5.33 ms                                                | 6.56 ms: 1.23x slower                                         |
| mako                       | 11.5 ms                                                | 14.5 ms: 1.26x slower                                         |
| coverage                   | 75.1 ms                                                | 95.6 ms: 1.27x slower                                         |
| python_startup_no_site     | 6.92 ms                                                | 9.05 ms: 1.31x slower                                         |
| nbody                      | 92.2 ms                                                | 122 ms: 1.33x slower                                          |
| tomli_loads                | 2.30 sec                                               | 3.07 sec: 1.33x slower                                        |
| deltablue                  | 3.71 ms                                                | 5.20 ms: 1.40x slower                                         |
| hexiom                     | 6.54 ms                                                | 10.2 ms: 1.57x slower                                         |
| Geometric mean             | (ref)                                                  | 1.05x slower                                                  |

Benchmark hidden because not significant (8): xml_etree_parse, pathlib, raytrace, bench_mp_pool, asyncio_websockets, scimark_lu, logging_format, sqlglot_transpile
Ignored benchmarks (6) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, dask, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.02x
- 95% likely to have a slowdown of 1.02x
- 99% likely to have a slowdown of 1.01x
