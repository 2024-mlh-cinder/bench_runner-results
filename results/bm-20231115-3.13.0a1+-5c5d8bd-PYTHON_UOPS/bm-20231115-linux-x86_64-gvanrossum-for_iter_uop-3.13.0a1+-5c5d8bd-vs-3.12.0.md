
# Results vs. 3.12.0

- fork: gvanrossum
- ref: for_iter_uop
- machine: linux-x86_64
- commit hash: 5c5d8bd
- commit date: 2023-11-15
- overall geometric mean: 1.08x slower \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.04x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231115-linux-x86_64-gvanrossum-for_iter_uop-3.13.0a1+-5c5d8bd |
|----------------|:------------------------------------------------------:|:------------------------------------------------------------------:|
| 2to3           | 274 ms                                                 | 291 ms: 1.06x slower                                               |
| chameleon      | 7.41 ms                                                | 7.65 ms: 1.03x slower                                              |
| Geometric mean | (ref)                                                  | 1.02x slower                                                       |

Benchmark hidden because not significant (2): docutils, tornado_http

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231115-linux-x86_64-gvanrossum-for_iter_uop-3.13.0a1+-5c5d8bd |
|----------------------------|:------------------------------------------------------:|:------------------------------------------------------------------:|
| async_tree_none            | 475 ms                                                 | 465 ms: 1.02x faster                                               |
| async_tree_cpu_io_mixed    | 724 ms                                                 | 742 ms: 1.03x slower                                               |
| async_tree_memoization     | 580 ms                                                 | 596 ms: 1.03x slower                                               |
| async_tree_cpu_io_mixed_tg | 725 ms                                                 | 770 ms: 1.06x slower                                               |
| async_tree_memoization_tg  | 574 ms                                                 | 610 ms: 1.06x slower                                               |
| async_tree_io              | 1.16 sec                                               | 1.24 sec: 1.06x slower                                             |
| async_tree_io_tg           | 1.19 sec                                               | 1.26 sec: 1.06x slower                                             |
| async_tree_none_tg         | 447 ms                                                 | 481 ms: 1.07x slower                                               |
| Geometric mean             | (ref)                                                  | 1.04x slower                                                       |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231115-linux-x86_64-gvanrossum-for_iter_uop-3.13.0a1+-5c5d8bd |
|----------------|:------------------------------------------------------:|:------------------------------------------------------------------:|
| pidigits       | 187 ms                                                 | 189 ms: 1.01x slower                                               |
| float          | 83.3 ms                                                | 109 ms: 1.30x slower                                               |
| nbody          | 92.2 ms                                                | 121 ms: 1.31x slower                                               |
| Geometric mean | (ref)                                                  | 1.20x slower                                                       |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231115-linux-x86_64-gvanrossum-for_iter_uop-3.13.0a1+-5c5d8bd |
|----------------|:------------------------------------------------------:|:------------------------------------------------------------------:|
| regex_effbot   | 3.57 ms                                                | 3.65 ms: 1.02x slower                                              |
| regex_dna      | 209 ms                                                 | 219 ms: 1.05x slower                                               |
| regex_compile  | 148 ms                                                 | 167 ms: 1.13x slower                                               |
| regex_v8       | 22.7 ms                                                | 26.2 ms: 1.16x slower                                              |
| Geometric mean | (ref)                                                  | 1.09x slower                                                       |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231115-linux-x86_64-gvanrossum-for_iter_uop-3.13.0a1+-5c5d8bd |
|----------------------|:------------------------------------------------------:|:------------------------------------------------------------------:|
| unpickle             | 15.8 us                                                | 14.7 us: 1.07x faster                                              |
| pickle_pure_python   | 326 us                                                 | 307 us: 1.06x faster                                               |
| pickle_dict          | 33.5 us                                                | 33.2 us: 1.01x faster                                              |
| json_dumps           | 10.6 ms                                                | 10.7 ms: 1.01x slower                                              |
| json_loads           | 28.4 us                                                | 28.8 us: 1.02x slower                                              |
| unpickle_list        | 5.04 us                                                | 5.22 us: 1.04x slower                                              |
| pickle               | 11.2 us                                                | 11.8 us: 1.05x slower                                              |
| xml_etree_process    | 61.2 ms                                                | 65.6 ms: 1.07x slower                                              |
| pickle_list          | 4.67 us                                                | 5.01 us: 1.07x slower                                              |
| xml_etree_generate   | 88.7 ms                                                | 96.8 ms: 1.09x slower                                              |
| unpickle_pure_python | 230 us                                                 | 255 us: 1.11x slower                                               |
| xml_etree_iterparse  | 106 ms                                                 | 120 ms: 1.14x slower                                               |
| tomli_loads          | 2.30 sec                                               | 2.99 sec: 1.30x slower                                             |
| Geometric mean       | (ref)                                                  | 1.05x slower                                                       |

Benchmark hidden because not significant (1): xml_etree_parse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231115-linux-x86_64-gvanrossum-for_iter_uop-3.13.0a1+-5c5d8bd |
|------------------------|:------------------------------------------------------:|:------------------------------------------------------------------:|
| python_startup         | 9.53 ms                                                | 10.4 ms: 1.09x slower                                              |
| python_startup_no_site | 6.92 ms                                                | 9.07 ms: 1.31x slower                                              |
| Geometric mean         | (ref)                                                  | 1.20x slower                                                       |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231115-linux-x86_64-gvanrossum-for_iter_uop-3.13.0a1+-5c5d8bd |
|-----------|:------------------------------------------------------:|:------------------------------------------------------------------:|
| mako      | 11.5 ms                                                | 16.2 ms: 1.41x slower                                              |

All benchmarks:
===============

| Benchmark                  | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231115-linux-x86_64-gvanrossum-for_iter_uop-3.13.0a1+-5c5d8bd |
|----------------------------|:------------------------------------------------------:|:------------------------------------------------------------------:|
| typing_runtime_protocols   | 153 us                                                 | 127 us: 1.21x faster                                               |
| unpack_sequence            | 54.2 ns                                                | 46.0 ns: 1.18x faster                                              |
| gc_traversal               | 4.28 ms                                                | 3.80 ms: 1.12x faster                                              |
| generators                 | 32.5 ms                                                | 29.2 ms: 1.11x faster                                              |
| unpickle                   | 15.8 us                                                | 14.7 us: 1.07x faster                                              |
| pickle_pure_python         | 326 us                                                 | 307 us: 1.06x faster                                               |
| coroutines                 | 23.5 ms                                                | 22.4 ms: 1.05x faster                                              |
| deepcopy_reduce            | 3.23 us                                                | 3.12 us: 1.03x faster                                              |
| async_tree_none            | 475 ms                                                 | 465 ms: 1.02x faster                                               |
| logging_simple             | 6.38 us                                                | 6.28 us: 1.02x faster                                              |
| logging_format             | 7.10 us                                                | 7.02 us: 1.01x faster                                              |
| asyncio_tcp                | 506 ms                                                 | 501 ms: 1.01x faster                                               |
| pickle_dict                | 33.5 us                                                | 33.2 us: 1.01x faster                                              |
| sympy_sum                  | 167 ms                                                 | 166 ms: 1.00x faster                                               |
| deepcopy                   | 363 us                                                 | 365 us: 1.01x slower                                               |
| asyncio_tcp_ssl            | 1.78 sec                                               | 1.80 sec: 1.01x slower                                             |
| pidigits                   | 187 ms                                                 | 189 ms: 1.01x slower                                               |
| json_dumps                 | 10.6 ms                                                | 10.7 ms: 1.01x slower                                              |
| json                       | 5.22 ms                                                | 5.30 ms: 1.01x slower                                              |
| raytrace                   | 308 ms                                                 | 312 ms: 1.01x slower                                               |
| json_loads                 | 28.4 us                                                | 28.8 us: 1.02x slower                                              |
| dulwich_log                | 68.7 ms                                                | 69.9 ms: 1.02x slower                                              |
| mypy2                      | 351 ms                                                 | 358 ms: 1.02x slower                                               |
| regex_effbot               | 3.57 ms                                                | 3.65 ms: 1.02x slower                                              |
| create_gc_cycles           | 1.45 ms                                                | 1.49 ms: 1.03x slower                                              |
| async_tree_cpu_io_mixed    | 724 ms                                                 | 742 ms: 1.03x slower                                               |
| async_tree_memoization     | 580 ms                                                 | 596 ms: 1.03x slower                                               |
| sympy_str                  | 296 ms                                                 | 306 ms: 1.03x slower                                               |
| bench_thread_pool          | 845 us                                                 | 873 us: 1.03x slower                                               |
| chameleon                  | 7.41 ms                                                | 7.65 ms: 1.03x slower                                              |
| unpickle_list              | 5.04 us                                                | 5.22 us: 1.04x slower                                              |
| sqlglot_transpile          | 1.68 ms                                                | 1.74 ms: 1.04x slower                                              |
| sqlite_synth               | 2.83 us                                                | 2.96 us: 1.04x slower                                              |
| sympy_expand               | 476 ms                                                 | 497 ms: 1.04x slower                                               |
| logging_silent             | 108 ns                                                 | 112 ns: 1.05x slower                                               |
| scimark_lu                 | 120 ms                                                 | 126 ms: 1.05x slower                                               |
| regex_dna                  | 209 ms                                                 | 219 ms: 1.05x slower                                               |
| pickle                     | 11.2 us                                                | 11.8 us: 1.05x slower                                              |
| sqlglot_parse              | 1.35 ms                                                | 1.42 ms: 1.05x slower                                              |
| sympy_integrate            | 21.2 ms                                                | 22.3 ms: 1.05x slower                                              |
| 2to3                       | 274 ms                                                 | 291 ms: 1.06x slower                                               |
| async_tree_cpu_io_mixed_tg | 725 ms                                                 | 770 ms: 1.06x slower                                               |
| async_tree_memoization_tg  | 574 ms                                                 | 610 ms: 1.06x slower                                               |
| async_tree_io              | 1.16 sec                                               | 1.24 sec: 1.06x slower                                             |
| async_tree_io_tg           | 1.19 sec                                               | 1.26 sec: 1.06x slower                                             |
| sqlglot_normalize          | 112 ms                                                 | 119 ms: 1.07x slower                                               |
| xml_etree_process          | 61.2 ms                                                | 65.6 ms: 1.07x slower                                              |
| pickle_list                | 4.67 us                                                | 5.01 us: 1.07x slower                                              |
| async_tree_none_tg         | 447 ms                                                 | 481 ms: 1.07x slower                                               |
| pycparser                  | 1.17 sec                                               | 1.27 sec: 1.09x slower                                             |
| crypto_pyaes               | 83.6 ms                                                | 90.8 ms: 1.09x slower                                              |
| mdp                        | 2.57 sec                                               | 2.79 sec: 1.09x slower                                             |
| xml_etree_generate         | 88.7 ms                                                | 96.8 ms: 1.09x slower                                              |
| python_startup             | 9.53 ms                                                | 10.4 ms: 1.09x slower                                              |
| deepcopy_memo              | 39.7 us                                                | 43.4 us: 1.09x slower                                              |
| pprint_safe_repr           | 765 ms                                                 | 841 ms: 1.10x slower                                               |
| unpickle_pure_python       | 230 us                                                 | 255 us: 1.11x slower                                               |
| sqlglot_optimize           | 54.8 ms                                                | 60.9 ms: 1.11x slower                                              |
| pprint_pformat             | 1.55 sec                                               | 1.74 sec: 1.12x slower                                             |
| regex_compile              | 148 ms                                                 | 167 ms: 1.13x slower                                               |
| meteor_contest             | 110 ms                                                 | 124 ms: 1.13x slower                                               |
| xml_etree_iterparse        | 106 ms                                                 | 120 ms: 1.14x slower                                               |
| richards                   | 46.0 ms                                                | 52.6 ms: 1.14x slower                                              |
| chaos                      | 67.5 ms                                                | 77.2 ms: 1.14x slower                                              |
| richards_super             | 51.9 ms                                                | 59.9 ms: 1.15x slower                                              |
| regex_v8                   | 22.7 ms                                                | 26.2 ms: 1.16x slower                                              |
| scimark_monte_carlo        | 74.6 ms                                                | 86.4 ms: 1.16x slower                                              |
| scimark_fft                | 381 ms                                                 | 453 ms: 1.19x slower                                               |
| go                         | 140 ms                                                 | 172 ms: 1.23x slower                                               |
| telco                      | 7.18 ms                                                | 8.86 ms: 1.23x slower                                              |
| coverage                   | 75.1 ms                                                | 94.4 ms: 1.26x slower                                              |
| pyflate                    | 471 ms                                                 | 599 ms: 1.27x slower                                               |
| fannkuch                   | 410 ms                                                 | 522 ms: 1.27x slower                                               |
| comprehensions             | 20.9 us                                                | 27.2 us: 1.30x slower                                              |
| tomli_loads                | 2.30 sec                                               | 2.99 sec: 1.30x slower                                             |
| float                      | 83.3 ms                                                | 109 ms: 1.30x slower                                               |
| nqueens                    | 86.2 ms                                                | 113 ms: 1.31x slower                                               |
| python_startup_no_site     | 6.92 ms                                                | 9.07 ms: 1.31x slower                                              |
| nbody                      | 92.2 ms                                                | 121 ms: 1.31x slower                                               |
| scimark_sparse_mat_mult    | 5.33 ms                                                | 7.36 ms: 1.38x slower                                              |
| mako                       | 11.5 ms                                                | 16.2 ms: 1.41x slower                                              |
| deltablue                  | 3.71 ms                                                | 5.64 ms: 1.52x slower                                              |
| spectral_norm              | 115 ms                                                 | 186 ms: 1.62x slower                                               |
| hexiom                     | 6.54 ms                                                | 10.9 ms: 1.67x slower                                              |
| Geometric mean             | (ref)                                                  | 1.08x slower                                                       |

Benchmark hidden because not significant (9): tornado_http, pathlib, scimark_sor, docutils, asyncio_websockets, bench_mp_pool, async_generators, xml_etree_parse, dask
Ignored benchmarks (5) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.05x
- 95% likely to have a slowdown of 1.04x
- 99% likely to have a slowdown of 1.04x
