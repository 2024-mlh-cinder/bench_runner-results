
# Results vs. 3.12.0

- fork: faster-cpython
- ref: faster_tier_2_interp
- machine: linux-x86_64
- commit hash: a9f3983
- commit date: 2023-11-12
- overall geometric mean: 1.06x slower \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.01x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231112-linux-x86_64-faster%2dcpython-faster_tier_2_interp-3.13.0a1+-a9f3983 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| 2to3           | 274 ms                                                 | 293 ms: 1.07x slower                                                             |
| chameleon      | 7.41 ms                                                | 7.56 ms: 1.02x slower                                                            |
| docutils       | 2.75 sec                                               | 2.72 sec: 1.01x faster                                                           |
| tornado_http   | 101 ms                                                 | 102 ms: 1.02x slower                                                             |
| Geometric mean | (ref)                                                  | 1.02x slower                                                                     |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231112-linux-x86_64-faster%2dcpython-faster_tier_2_interp-3.13.0a1+-a9f3983 |
|----------------------------|:------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| async_tree_none            | 475 ms                                                 | 462 ms: 1.03x faster                                                             |
| async_tree_cpu_io_mixed    | 724 ms                                                 | 736 ms: 1.02x slower                                                             |
| async_tree_memoization     | 580 ms                                                 | 592 ms: 1.02x slower                                                             |
| async_tree_cpu_io_mixed_tg | 725 ms                                                 | 763 ms: 1.05x slower                                                             |
| async_tree_io              | 1.16 sec                                               | 1.23 sec: 1.06x slower                                                           |
| async_tree_io_tg           | 1.19 sec                                               | 1.26 sec: 1.06x slower                                                           |
| async_tree_memoization_tg  | 574 ms                                                 | 611 ms: 1.06x slower                                                             |
| async_tree_none_tg         | 447 ms                                                 | 479 ms: 1.07x slower                                                             |
| Geometric mean             | (ref)                                                  | 1.04x slower                                                                     |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231112-linux-x86_64-faster%2dcpython-faster_tier_2_interp-3.13.0a1+-a9f3983 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| pidigits       | 187 ms                                                 | 196 ms: 1.05x slower                                                             |
| float          | 83.3 ms                                                | 109 ms: 1.31x slower                                                             |
| nbody          | 92.2 ms                                                | 124 ms: 1.35x slower                                                             |
| Geometric mean | (ref)                                                  | 1.23x slower                                                                     |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231112-linux-x86_64-faster%2dcpython-faster_tier_2_interp-3.13.0a1+-a9f3983 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| regex_effbot   | 3.57 ms                                                | 3.49 ms: 1.02x faster                                                            |
| regex_dna      | 209 ms                                                 | 214 ms: 1.03x slower                                                             |
| regex_compile  | 148 ms                                                 | 161 ms: 1.09x slower                                                             |
| regex_v8       | 22.7 ms                                                | 24.7 ms: 1.09x slower                                                            |
| Geometric mean | (ref)                                                  | 1.04x slower                                                                     |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231112-linux-x86_64-faster%2dcpython-faster_tier_2_interp-3.13.0a1+-a9f3983 |
|----------------------|:------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| unpickle             | 15.8 us                                                | 14.6 us: 1.08x faster                                                            |
| pickle_pure_python   | 326 us                                                 | 309 us: 1.05x faster                                                             |
| xml_etree_process    | 61.2 ms                                                | 59.2 ms: 1.03x faster                                                            |
| xml_etree_generate   | 88.7 ms                                                | 87.0 ms: 1.02x faster                                                            |
| json_loads           | 28.4 us                                                | 28.2 us: 1.01x faster                                                            |
| xml_etree_parse      | 159 ms                                                 | 159 ms: 1.00x faster                                                             |
| pickle_dict          | 33.5 us                                                | 33.6 us: 1.00x slower                                                            |
| unpickle_list        | 5.04 us                                                | 5.10 us: 1.01x slower                                                            |
| pickle               | 11.2 us                                                | 11.4 us: 1.02x slower                                                            |
| pickle_list          | 4.67 us                                                | 4.95 us: 1.06x slower                                                            |
| xml_etree_iterparse  | 106 ms                                                 | 113 ms: 1.07x slower                                                             |
| unpickle_pure_python | 230 us                                                 | 249 us: 1.08x slower                                                             |
| tomli_loads          | 2.30 sec                                               | 2.99 sec: 1.30x slower                                                           |
| Geometric mean       | (ref)                                                  | 1.02x slower                                                                     |

Benchmark hidden because not significant (1): json_dumps

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231112-linux-x86_64-faster%2dcpython-faster_tier_2_interp-3.13.0a1+-a9f3983 |
|------------------------|:------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| python_startup         | 9.53 ms                                                | 10.3 ms: 1.08x slower                                                            |
| python_startup_no_site | 6.92 ms                                                | 9.03 ms: 1.31x slower                                                            |
| Geometric mean         | (ref)                                                  | 1.19x slower                                                                     |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231112-linux-x86_64-faster%2dcpython-faster_tier_2_interp-3.13.0a1+-a9f3983 |
|-----------|:------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| mako      | 11.5 ms                                                | 15.2 ms: 1.32x slower                                                            |

All benchmarks:
===============

| Benchmark                  | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231112-linux-x86_64-faster%2dcpython-faster_tier_2_interp-3.13.0a1+-a9f3983 |
|----------------------------|:------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| typing_runtime_protocols   | 153 us                                                 | 124 us: 1.24x faster                                                             |
| unpack_sequence            | 54.2 ns                                                | 46.6 ns: 1.16x faster                                                            |
| gc_traversal               | 4.28 ms                                                | 3.82 ms: 1.12x faster                                                            |
| sympy_sum                  | 167 ms                                                 | 154 ms: 1.09x faster                                                             |
| generators                 | 32.5 ms                                                | 29.9 ms: 1.09x faster                                                            |
| unpickle                   | 15.8 us                                                | 14.6 us: 1.08x faster                                                            |
| pickle_pure_python         | 326 us                                                 | 309 us: 1.05x faster                                                             |
| coroutines                 | 23.5 ms                                                | 22.3 ms: 1.05x faster                                                            |
| spectral_norm              | 115 ms                                                 | 111 ms: 1.04x faster                                                             |
| xml_etree_process          | 61.2 ms                                                | 59.2 ms: 1.03x faster                                                            |
| sqlglot_normalize          | 112 ms                                                 | 108 ms: 1.03x faster                                                             |
| sympy_str                  | 296 ms                                                 | 287 ms: 1.03x faster                                                             |
| async_tree_none            | 475 ms                                                 | 462 ms: 1.03x faster                                                             |
| scimark_sor                | 129 ms                                                 | 126 ms: 1.03x faster                                                             |
| regex_effbot               | 3.57 ms                                                | 3.49 ms: 1.02x faster                                                            |
| xml_etree_generate         | 88.7 ms                                                | 87.0 ms: 1.02x faster                                                            |
| json                       | 5.22 ms                                                | 5.12 ms: 1.02x faster                                                            |
| logging_simple             | 6.38 us                                                | 6.28 us: 1.02x faster                                                            |
| docutils                   | 2.75 sec                                               | 2.72 sec: 1.01x faster                                                           |
| deepcopy                   | 363 us                                                 | 359 us: 1.01x faster                                                             |
| json_loads                 | 28.4 us                                                | 28.2 us: 1.01x faster                                                            |
| asyncio_tcp                | 506 ms                                                 | 502 ms: 1.01x faster                                                             |
| scimark_lu                 | 120 ms                                                 | 120 ms: 1.01x faster                                                             |
| deepcopy_reduce            | 3.23 us                                                | 3.21 us: 1.01x faster                                                            |
| xml_etree_parse            | 159 ms                                                 | 159 ms: 1.00x faster                                                             |
| sqlglot_parse              | 1.35 ms                                                | 1.34 ms: 1.00x faster                                                            |
| logging_silent             | 108 ns                                                 | 107 ns: 1.00x faster                                                             |
| pickle_dict                | 33.5 us                                                | 33.6 us: 1.00x slower                                                            |
| dulwich_log                | 68.7 ms                                                | 69.2 ms: 1.01x slower                                                            |
| unpickle_list              | 5.04 us                                                | 5.10 us: 1.01x slower                                                            |
| logging_format             | 7.10 us                                                | 7.18 us: 1.01x slower                                                            |
| mypy2                      | 351 ms                                                 | 355 ms: 1.01x slower                                                             |
| sympy_integrate            | 21.2 ms                                                | 21.5 ms: 1.01x slower                                                            |
| asyncio_tcp_ssl            | 1.78 sec                                               | 1.81 sec: 1.02x slower                                                           |
| async_tree_cpu_io_mixed    | 724 ms                                                 | 736 ms: 1.02x slower                                                             |
| pickle                     | 11.2 us                                                | 11.4 us: 1.02x slower                                                            |
| sympy_expand               | 476 ms                                                 | 483 ms: 1.02x slower                                                             |
| tornado_http               | 101 ms                                                 | 102 ms: 1.02x slower                                                             |
| async_generators           | 459 ms                                                 | 468 ms: 1.02x slower                                                             |
| bench_thread_pool          | 845 us                                                 | 860 us: 1.02x slower                                                             |
| chameleon                  | 7.41 ms                                                | 7.56 ms: 1.02x slower                                                            |
| async_tree_memoization     | 580 ms                                                 | 592 ms: 1.02x slower                                                             |
| create_gc_cycles           | 1.45 ms                                                | 1.49 ms: 1.02x slower                                                            |
| regex_dna                  | 209 ms                                                 | 214 ms: 1.03x slower                                                             |
| sqlite_synth               | 2.83 us                                                | 2.91 us: 1.03x slower                                                            |
| raytrace                   | 308 ms                                                 | 316 ms: 1.03x slower                                                             |
| pidigits                   | 187 ms                                                 | 196 ms: 1.05x slower                                                             |
| async_tree_cpu_io_mixed_tg | 725 ms                                                 | 763 ms: 1.05x slower                                                             |
| async_tree_io              | 1.16 sec                                               | 1.23 sec: 1.06x slower                                                           |
| crypto_pyaes               | 83.6 ms                                                | 88.5 ms: 1.06x slower                                                            |
| pickle_list                | 4.67 us                                                | 4.95 us: 1.06x slower                                                            |
| async_tree_io_tg           | 1.19 sec                                               | 1.26 sec: 1.06x slower                                                           |
| async_tree_memoization_tg  | 574 ms                                                 | 611 ms: 1.06x slower                                                             |
| 2to3                       | 274 ms                                                 | 293 ms: 1.07x slower                                                             |
| async_tree_none_tg         | 447 ms                                                 | 479 ms: 1.07x slower                                                             |
| xml_etree_iterparse        | 106 ms                                                 | 113 ms: 1.07x slower                                                             |
| pycparser                  | 1.17 sec                                               | 1.26 sec: 1.08x slower                                                           |
| mdp                        | 2.57 sec                                               | 2.78 sec: 1.08x slower                                                           |
| python_startup             | 9.53 ms                                                | 10.3 ms: 1.08x slower                                                            |
| unpickle_pure_python       | 230 us                                                 | 249 us: 1.08x slower                                                             |
| regex_compile              | 148 ms                                                 | 161 ms: 1.09x slower                                                             |
| pprint_safe_repr           | 765 ms                                                 | 833 ms: 1.09x slower                                                             |
| regex_v8                   | 22.7 ms                                                | 24.7 ms: 1.09x slower                                                            |
| deepcopy_memo              | 39.7 us                                                | 43.3 us: 1.09x slower                                                            |
| meteor_contest             | 110 ms                                                 | 120 ms: 1.09x slower                                                             |
| scimark_monte_carlo        | 74.6 ms                                                | 81.6 ms: 1.09x slower                                                            |
| pprint_pformat             | 1.55 sec                                               | 1.71 sec: 1.10x slower                                                           |
| chaos                      | 67.5 ms                                                | 75.7 ms: 1.12x slower                                                            |
| richards_super             | 51.9 ms                                                | 59.2 ms: 1.14x slower                                                            |
| richards                   | 46.0 ms                                                | 52.7 ms: 1.14x slower                                                            |
| scimark_fft                | 381 ms                                                 | 440 ms: 1.15x slower                                                             |
| go                         | 140 ms                                                 | 170 ms: 1.21x slower                                                             |
| pyflate                    | 471 ms                                                 | 573 ms: 1.22x slower                                                             |
| fannkuch                   | 410 ms                                                 | 512 ms: 1.25x slower                                                             |
| scimark_sparse_mat_mult    | 5.33 ms                                                | 6.66 ms: 1.25x slower                                                            |
| telco                      | 7.18 ms                                                | 8.98 ms: 1.25x slower                                                            |
| comprehensions             | 20.9 us                                                | 26.5 us: 1.27x slower                                                            |
| coverage                   | 75.1 ms                                                | 95.3 ms: 1.27x slower                                                            |
| tomli_loads                | 2.30 sec                                               | 2.99 sec: 1.30x slower                                                           |
| python_startup_no_site     | 6.92 ms                                                | 9.03 ms: 1.31x slower                                                            |
| nqueens                    | 86.2 ms                                                | 113 ms: 1.31x slower                                                             |
| float                      | 83.3 ms                                                | 109 ms: 1.31x slower                                                             |
| mako                       | 11.5 ms                                                | 15.2 ms: 1.32x slower                                                            |
| nbody                      | 92.2 ms                                                | 124 ms: 1.35x slower                                                             |
| deltablue                  | 3.71 ms                                                | 5.32 ms: 1.44x slower                                                            |
| hexiom                     | 6.54 ms                                                | 10.6 ms: 1.62x slower                                                            |
| Geometric mean             | (ref)                                                  | 1.06x slower                                                                     |

Benchmark hidden because not significant (6): pathlib, sqlglot_transpile, json_dumps, asyncio_websockets, bench_mp_pool, sqlglot_optimize
Ignored benchmarks (6) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, dask, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.02x
- 95% likely to have a slowdown of 1.02x
- 99% likely to have a slowdown of 1.01x
