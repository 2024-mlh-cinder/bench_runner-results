
# Results vs. 3.12.0

- fork: mdboom
- ref: test_branch3
- machine: linux-x86_64
- commit hash: dbd826e
- commit date: 2023-11-20
- overall geometric mean: 1.05x slower \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.02x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-linux-x86_64-mdboom-test_branch3-3.13.0a1+-dbd826e |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| 2to3           | 274 ms                                                 | 288 ms: 1.05x slower                                           |
| chameleon      | 7.41 ms                                                | 7.46 ms: 1.01x slower                                          |
| docutils       | 2.75 sec                                               | 2.72 sec: 1.01x faster                                         |
| tornado_http   | 101 ms                                                 | 99.1 ms: 1.02x faster                                          |
| Geometric mean | (ref)                                                  | 1.01x slower                                                   |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-linux-x86_64-mdboom-test_branch3-3.13.0a1+-dbd826e |
|----------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| async_tree_none            | 475 ms                                                 | 452 ms: 1.05x faster                                           |
| async_tree_io              | 1.16 sec                                               | 1.21 sec: 1.04x slower                                         |
| async_tree_cpu_io_mixed_tg | 725 ms                                                 | 752 ms: 1.04x slower                                           |
| async_tree_none_tg         | 447 ms                                                 | 468 ms: 1.05x slower                                           |
| async_tree_io_tg           | 1.19 sec                                               | 1.25 sec: 1.05x slower                                         |
| async_tree_memoization_tg  | 574 ms                                                 | 617 ms: 1.07x slower                                           |
| Geometric mean             | (ref)                                                  | 1.02x slower                                                   |

Benchmark hidden because not significant (2): async_tree_cpu_io_mixed, async_tree_memoization

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-linux-x86_64-mdboom-test_branch3-3.13.0a1+-dbd826e |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| pidigits       | 187 ms                                                 | 196 ms: 1.05x slower                                           |
| float          | 83.3 ms                                                | 94.4 ms: 1.13x slower                                          |
| nbody          | 92.2 ms                                                | 112 ms: 1.21x slower                                           |
| Geometric mean | (ref)                                                  | 1.13x slower                                                   |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-linux-x86_64-mdboom-test_branch3-3.13.0a1+-dbd826e |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| regex_dna      | 209 ms                                                 | 217 ms: 1.04x slower                                           |
| regex_v8       | 22.7 ms                                                | 24.5 ms: 1.08x slower                                          |
| regex_compile  | 148 ms                                                 | 160 ms: 1.08x slower                                           |
| Geometric mean | (ref)                                                  | 1.05x slower                                                   |

Benchmark hidden because not significant (1): regex_effbot

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-linux-x86_64-mdboom-test_branch3-3.13.0a1+-dbd826e |
|----------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| unpickle             | 15.8 us                                                | 14.9 us: 1.06x faster                                          |
| pickle_pure_python   | 326 us                                                 | 313 us: 1.04x faster                                           |
| json_dumps           | 10.6 ms                                                | 10.7 ms: 1.01x slower                                          |
| unpickle_list        | 5.04 us                                                | 5.16 us: 1.02x slower                                          |
| xml_etree_process    | 61.2 ms                                                | 63.1 ms: 1.03x slower                                          |
| pickle               | 11.2 us                                                | 11.7 us: 1.04x slower                                          |
| xml_etree_generate   | 88.7 ms                                                | 92.6 ms: 1.04x slower                                          |
| unpickle_pure_python | 230 us                                                 | 241 us: 1.05x slower                                           |
| pickle_dict          | 33.5 us                                                | 35.5 us: 1.06x slower                                          |
| xml_etree_iterparse  | 106 ms                                                 | 114 ms: 1.08x slower                                           |
| tomli_loads          | 2.30 sec                                               | 2.51 sec: 1.09x slower                                         |
| pickle_list          | 4.67 us                                                | 5.20 us: 1.11x slower                                          |
| Geometric mean       | (ref)                                                  | 1.03x slower                                                   |

Benchmark hidden because not significant (2): xml_etree_parse, json_loads

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-linux-x86_64-mdboom-test_branch3-3.13.0a1+-dbd826e |
|------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| python_startup         | 9.53 ms                                                | 10.4 ms: 1.09x slower                                          |
| python_startup_no_site | 6.92 ms                                                | 9.05 ms: 1.31x slower                                          |
| Geometric mean         | (ref)                                                  | 1.20x slower                                                   |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-linux-x86_64-mdboom-test_branch3-3.13.0a1+-dbd826e |
|-----------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| mako      | 11.5 ms                                                | 14.5 ms: 1.26x slower                                          |

All benchmarks:
===============

| Benchmark                  | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-linux-x86_64-mdboom-test_branch3-3.13.0a1+-dbd826e |
|----------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| typing_runtime_protocols   | 153 us                                                 | 124 us: 1.23x faster                                           |
| unpack_sequence            | 54.2 ns                                                | 46.0 ns: 1.18x faster                                          |
| gc_traversal               | 4.28 ms                                                | 3.83 ms: 1.12x faster                                          |
| generators                 | 32.5 ms                                                | 29.7 ms: 1.09x faster                                          |
| unpickle                   | 15.8 us                                                | 14.9 us: 1.06x faster                                          |
| async_tree_none            | 475 ms                                                 | 452 ms: 1.05x faster                                           |
| pickle_pure_python         | 326 us                                                 | 313 us: 1.04x faster                                           |
| sympy_sum                  | 167 ms                                                 | 161 ms: 1.04x faster                                           |
| logging_simple             | 6.38 us                                                | 6.15 us: 1.04x faster                                          |
| coroutines                 | 23.5 ms                                                | 22.7 ms: 1.03x faster                                          |
| asyncio_tcp                | 506 ms                                                 | 491 ms: 1.03x faster                                           |
| deepcopy_reduce            | 3.23 us                                                | 3.15 us: 1.02x faster                                          |
| logging_format             | 7.10 us                                                | 6.98 us: 1.02x faster                                          |
| tornado_http               | 101 ms                                                 | 99.1 ms: 1.02x faster                                          |
| scimark_sor                | 129 ms                                                 | 127 ms: 1.01x faster                                           |
| docutils                   | 2.75 sec                                               | 2.72 sec: 1.01x faster                                         |
| pathlib                    | 18.9 ms                                                | 18.7 ms: 1.01x faster                                          |
| json                       | 5.22 ms                                                | 5.18 ms: 1.01x faster                                          |
| deepcopy                   | 363 us                                                 | 361 us: 1.00x faster                                           |
| logging_silent             | 108 ns                                                 | 108 ns: 1.00x slower                                           |
| chameleon                  | 7.41 ms                                                | 7.46 ms: 1.01x slower                                          |
| json_dumps                 | 10.6 ms                                                | 10.7 ms: 1.01x slower                                          |
| sympy_integrate            | 21.2 ms                                                | 21.4 ms: 1.01x slower                                          |
| dulwich_log                | 68.7 ms                                                | 69.6 ms: 1.01x slower                                          |
| bench_thread_pool          | 845 us                                                 | 858 us: 1.02x slower                                           |
| mypy2                      | 351 ms                                                 | 357 ms: 1.02x slower                                           |
| asyncio_tcp_ssl            | 1.78 sec                                               | 1.81 sec: 1.02x slower                                         |
| sqlglot_transpile          | 1.68 ms                                                | 1.71 ms: 1.02x slower                                          |
| sqlite_synth               | 2.83 us                                                | 2.89 us: 1.02x slower                                          |
| unpickle_list              | 5.04 us                                                | 5.16 us: 1.02x slower                                          |
| create_gc_cycles           | 1.45 ms                                                | 1.48 ms: 1.02x slower                                          |
| sqlglot_parse              | 1.35 ms                                                | 1.38 ms: 1.03x slower                                          |
| pycparser                  | 1.17 sec                                               | 1.20 sec: 1.03x slower                                         |
| xml_etree_process          | 61.2 ms                                                | 63.1 ms: 1.03x slower                                          |
| sympy_expand               | 476 ms                                                 | 491 ms: 1.03x slower                                           |
| deepcopy_memo              | 39.7 us                                                | 41.1 us: 1.03x slower                                          |
| sqlglot_normalize          | 112 ms                                                 | 115 ms: 1.03x slower                                           |
| crypto_pyaes               | 83.6 ms                                                | 86.6 ms: 1.04x slower                                          |
| async_tree_io              | 1.16 sec                                               | 1.21 sec: 1.04x slower                                         |
| async_tree_cpu_io_mixed_tg | 725 ms                                                 | 752 ms: 1.04x slower                                           |
| regex_dna                  | 209 ms                                                 | 217 ms: 1.04x slower                                           |
| pickle                     | 11.2 us                                                | 11.7 us: 1.04x slower                                          |
| xml_etree_generate         | 88.7 ms                                                | 92.6 ms: 1.04x slower                                          |
| async_tree_none_tg         | 447 ms                                                 | 468 ms: 1.05x slower                                           |
| pidigits                   | 187 ms                                                 | 196 ms: 1.05x slower                                           |
| async_tree_io_tg           | 1.19 sec                                               | 1.25 sec: 1.05x slower                                         |
| 2to3                       | 274 ms                                                 | 288 ms: 1.05x slower                                           |
| unpickle_pure_python       | 230 us                                                 | 241 us: 1.05x slower                                           |
| comprehensions             | 20.9 us                                                | 22.2 us: 1.06x slower                                          |
| pickle_dict                | 33.5 us                                                | 35.5 us: 1.06x slower                                          |
| pprint_safe_repr           | 765 ms                                                 | 812 ms: 1.06x slower                                           |
| sqlglot_optimize           | 54.8 ms                                                | 58.6 ms: 1.07x slower                                          |
| meteor_contest             | 110 ms                                                 | 118 ms: 1.07x slower                                           |
| scimark_monte_carlo        | 74.6 ms                                                | 80.1 ms: 1.07x slower                                          |
| async_tree_memoization_tg  | 574 ms                                                 | 617 ms: 1.07x slower                                           |
| regex_v8                   | 22.7 ms                                                | 24.5 ms: 1.08x slower                                          |
| regex_compile              | 148 ms                                                 | 160 ms: 1.08x slower                                           |
| xml_etree_iterparse        | 106 ms                                                 | 114 ms: 1.08x slower                                           |
| pprint_pformat             | 1.55 sec                                               | 1.69 sec: 1.09x slower                                         |
| python_startup             | 9.53 ms                                                | 10.4 ms: 1.09x slower                                          |
| tomli_loads                | 2.30 sec                                               | 2.51 sec: 1.09x slower                                         |
| mdp                        | 2.57 sec                                               | 2.82 sec: 1.10x slower                                         |
| richards_super             | 51.9 ms                                                | 57.2 ms: 1.10x slower                                          |
| richards                   | 46.0 ms                                                | 50.8 ms: 1.10x slower                                          |
| pickle_list                | 4.67 us                                                | 5.20 us: 1.11x slower                                          |
| chaos                      | 67.5 ms                                                | 75.6 ms: 1.12x slower                                          |
| nqueens                    | 86.2 ms                                                | 97.0 ms: 1.13x slower                                          |
| fannkuch                   | 410 ms                                                 | 464 ms: 1.13x slower                                           |
| float                      | 83.3 ms                                                | 94.4 ms: 1.13x slower                                          |
| pyflate                    | 471 ms                                                 | 543 ms: 1.15x slower                                           |
| go                         | 140 ms                                                 | 163 ms: 1.16x slower                                           |
| scimark_sparse_mat_mult    | 5.33 ms                                                | 6.23 ms: 1.17x slower                                          |
| telco                      | 7.18 ms                                                | 8.64 ms: 1.20x slower                                          |
| nbody                      | 92.2 ms                                                | 112 ms: 1.21x slower                                           |
| scimark_fft                | 381 ms                                                 | 463 ms: 1.22x slower                                           |
| mako                       | 11.5 ms                                                | 14.5 ms: 1.26x slower                                          |
| coverage                   | 75.1 ms                                                | 94.8 ms: 1.26x slower                                          |
| python_startup_no_site     | 6.92 ms                                                | 9.05 ms: 1.31x slower                                          |
| deltablue                  | 3.71 ms                                                | 4.87 ms: 1.31x slower                                          |
| hexiom                     | 6.54 ms                                                | 8.90 ms: 1.36x slower                                          |
| spectral_norm              | 115 ms                                                 | 156 ms: 1.36x slower                                           |
| Geometric mean             | (ref)                                                  | 1.05x slower                                                   |

Benchmark hidden because not significant (12): dask, asyncio_websockets, sympy_str, bench_mp_pool, xml_etree_parse, scimark_lu, regex_effbot, async_tree_cpu_io_mixed, async_generators, async_tree_memoization, json_loads, raytrace
Ignored benchmarks (5) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.03x
- 95% likely to have a slowdown of 1.02x
- 99% likely to have a slowdown of 1.02x
