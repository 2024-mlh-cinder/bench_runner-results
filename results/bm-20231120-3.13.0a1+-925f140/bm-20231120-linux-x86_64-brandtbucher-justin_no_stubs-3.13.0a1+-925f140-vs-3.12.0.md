
# Results vs. 3.12.0

- fork: brandtbucher
- ref: justin_no_stubs
- machine: linux-x86_64
- commit hash: 925f140
- commit date: 2023-11-20
- overall geometric mean: 1.01x slower \*
- HPT reliability: 98.15%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-linux-x86_64-brandtbucher-justin_no_stubs-3.13.0a1+-925f140 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| 2to3           | 274 ms                                                 | 274 ms: 1.00x faster                                                    |
| chameleon      | 7.41 ms                                                | 7.15 ms: 1.04x faster                                                   |
| docutils       | 2.75 sec                                               | 2.66 sec: 1.04x faster                                                  |
| tornado_http   | 101 ms                                                 | 96.5 ms: 1.04x faster                                                   |
| Geometric mean | (ref)                                                  | 1.03x faster                                                            |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-linux-x86_64-brandtbucher-justin_no_stubs-3.13.0a1+-925f140 |
|----------------------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| async_tree_none            | 475 ms                                                 | 444 ms: 1.07x faster                                                    |
| async_tree_memoization     | 580 ms                                                 | 568 ms: 1.02x faster                                                    |
| async_tree_io              | 1.16 sec                                               | 1.19 sec: 1.02x slower                                                  |
| async_tree_io_tg           | 1.19 sec                                               | 1.22 sec: 1.03x slower                                                  |
| async_tree_none_tg         | 447 ms                                                 | 461 ms: 1.03x slower                                                    |
| async_tree_cpu_io_mixed_tg | 725 ms                                                 | 748 ms: 1.03x slower                                                    |
| async_tree_memoization_tg  | 574 ms                                                 | 608 ms: 1.06x slower                                                    |
| Geometric mean             | (ref)                                                  | 1.01x slower                                                            |

Benchmark hidden because not significant (1): async_tree_cpu_io_mixed

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-linux-x86_64-brandtbucher-justin_no_stubs-3.13.0a1+-925f140 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| float          | 83.3 ms                                                | 84.9 ms: 1.02x slower                                                   |
| pidigits       | 187 ms                                                 | 195 ms: 1.04x slower                                                    |
| nbody          | 92.2 ms                                                | 98.9 ms: 1.07x slower                                                   |
| Geometric mean | (ref)                                                  | 1.04x slower                                                            |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-linux-x86_64-brandtbucher-justin_no_stubs-3.13.0a1+-925f140 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| regex_compile  | 148 ms                                                 | 144 ms: 1.03x faster                                                    |
| regex_effbot   | 3.57 ms                                                | 3.58 ms: 1.00x slower                                                   |
| regex_v8       | 22.7 ms                                                | 24.0 ms: 1.06x slower                                                   |
| regex_dna      | 209 ms                                                 | 221 ms: 1.06x slower                                                    |
| Geometric mean | (ref)                                                  | 1.02x slower                                                            |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-linux-x86_64-brandtbucher-justin_no_stubs-3.13.0a1+-925f140 |
|----------------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| tomli_loads          | 2.30 sec                                               | 2.16 sec: 1.06x faster                                                  |
| pickle_pure_python   | 326 us                                                 | 312 us: 1.04x faster                                                    |
| unpickle             | 15.8 us                                                | 15.4 us: 1.02x faster                                                   |
| json_loads           | 28.4 us                                                | 28.2 us: 1.01x faster                                                   |
| xml_etree_generate   | 88.7 ms                                                | 89.1 ms: 1.00x slower                                                   |
| xml_etree_parse      | 159 ms                                                 | 160 ms: 1.00x slower                                                    |
| unpickle_pure_python | 230 us                                                 | 234 us: 1.02x slower                                                    |
| pickle               | 11.2 us                                                | 11.5 us: 1.02x slower                                                   |
| unpickle_list        | 5.04 us                                                | 5.25 us: 1.04x slower                                                   |
| xml_etree_iterparse  | 106 ms                                                 | 110 ms: 1.04x slower                                                    |
| pickle_dict          | 33.5 us                                                | 35.7 us: 1.06x slower                                                   |
| pickle_list          | 4.67 us                                                | 5.18 us: 1.11x slower                                                   |
| Geometric mean       | (ref)                                                  | 1.01x slower                                                            |

Benchmark hidden because not significant (2): xml_etree_process, json_dumps

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-linux-x86_64-brandtbucher-justin_no_stubs-3.13.0a1+-925f140 |
|------------------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| python_startup         | 9.53 ms                                                | 10.4 ms: 1.09x slower                                                   |
| python_startup_no_site | 6.92 ms                                                | 9.07 ms: 1.31x slower                                                   |
| Geometric mean         | (ref)                                                  | 1.20x slower                                                            |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-linux-x86_64-brandtbucher-justin_no_stubs-3.13.0a1+-925f140 |
|-----------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| mako      | 11.5 ms                                                | 12.3 ms: 1.07x slower                                                   |

All benchmarks:
===============

| Benchmark                  | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-linux-x86_64-brandtbucher-justin_no_stubs-3.13.0a1+-925f140 |
|----------------------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| typing_runtime_protocols   | 153 us                                                 | 119 us: 1.29x faster                                                    |
| logging_format             | 7.10 us                                                | 6.38 us: 1.11x faster                                                   |
| unpack_sequence            | 54.2 ns                                                | 49.2 ns: 1.10x faster                                                   |
| logging_simple             | 6.38 us                                                | 5.82 us: 1.10x faster                                                   |
| comprehensions             | 20.9 us                                                | 19.4 us: 1.08x faster                                                   |
| generators                 | 32.5 ms                                                | 30.1 ms: 1.08x faster                                                   |
| raytrace                   | 308 ms                                                 | 286 ms: 1.08x faster                                                    |
| sympy_sum                  | 167 ms                                                 | 156 ms: 1.07x faster                                                    |
| async_tree_none            | 475 ms                                                 | 444 ms: 1.07x faster                                                    |
| crypto_pyaes               | 83.6 ms                                                | 78.3 ms: 1.07x faster                                                   |
| tomli_loads                | 2.30 sec                                               | 2.16 sec: 1.06x faster                                                  |
| sympy_str                  | 296 ms                                                 | 282 ms: 1.05x faster                                                    |
| pickle_pure_python         | 326 us                                                 | 312 us: 1.04x faster                                                    |
| tornado_http               | 101 ms                                                 | 96.5 ms: 1.04x faster                                                   |
| deepcopy_reduce            | 3.23 us                                                | 3.11 us: 1.04x faster                                                   |
| chameleon                  | 7.41 ms                                                | 7.15 ms: 1.04x faster                                                   |
| docutils                   | 2.75 sec                                               | 2.66 sec: 1.04x faster                                                  |
| regex_compile              | 148 ms                                                 | 144 ms: 1.03x faster                                                    |
| coroutines                 | 23.5 ms                                                | 22.7 ms: 1.03x faster                                                   |
| dulwich_log                | 68.7 ms                                                | 66.7 ms: 1.03x faster                                                   |
| asyncio_tcp                | 506 ms                                                 | 491 ms: 1.03x faster                                                    |
| sqlglot_normalize          | 112 ms                                                 | 108 ms: 1.03x faster                                                    |
| pathlib                    | 18.9 ms                                                | 18.4 ms: 1.02x faster                                                   |
| sqlglot_parse              | 1.35 ms                                                | 1.32 ms: 1.02x faster                                                   |
| unpickle                   | 15.8 us                                                | 15.4 us: 1.02x faster                                                   |
| deepcopy                   | 363 us                                                 | 355 us: 1.02x faster                                                    |
| async_tree_memoization     | 580 ms                                                 | 568 ms: 1.02x faster                                                    |
| scimark_sor                | 129 ms                                                 | 127 ms: 1.02x faster                                                    |
| sqlglot_transpile          | 1.68 ms                                                | 1.65 ms: 1.02x faster                                                   |
| sympy_expand               | 476 ms                                                 | 469 ms: 1.01x faster                                                    |
| sympy_integrate            | 21.2 ms                                                | 20.9 ms: 1.01x faster                                                   |
| json                       | 5.22 ms                                                | 5.15 ms: 1.01x faster                                                   |
| dask                       | 369 ms                                                 | 365 ms: 1.01x faster                                                    |
| json_loads                 | 28.4 us                                                | 28.2 us: 1.01x faster                                                   |
| scimark_lu                 | 120 ms                                                 | 120 ms: 1.01x faster                                                    |
| chaos                      | 67.5 ms                                                | 67.2 ms: 1.01x faster                                                   |
| 2to3                       | 274 ms                                                 | 274 ms: 1.00x faster                                                    |
| gc_traversal               | 4.28 ms                                                | 4.29 ms: 1.00x slower                                                   |
| regex_effbot               | 3.57 ms                                                | 3.58 ms: 1.00x slower                                                   |
| xml_etree_generate         | 88.7 ms                                                | 89.1 ms: 1.00x slower                                                   |
| xml_etree_parse            | 159 ms                                                 | 160 ms: 1.00x slower                                                    |
| create_gc_cycles           | 1.45 ms                                                | 1.46 ms: 1.01x slower                                                   |
| scimark_fft                | 381 ms                                                 | 384 ms: 1.01x slower                                                    |
| bench_thread_pool          | 845 us                                                 | 854 us: 1.01x slower                                                    |
| sqlglot_optimize           | 54.8 ms                                                | 55.5 ms: 1.01x slower                                                   |
| async_generators           | 459 ms                                                 | 465 ms: 1.01x slower                                                    |
| asyncio_tcp_ssl            | 1.78 sec                                               | 1.81 sec: 1.01x slower                                                  |
| meteor_contest             | 110 ms                                                 | 111 ms: 1.02x slower                                                    |
| logging_silent             | 108 ns                                                 | 110 ns: 1.02x slower                                                    |
| float                      | 83.3 ms                                                | 84.9 ms: 1.02x slower                                                   |
| richards                   | 46.0 ms                                                | 46.9 ms: 1.02x slower                                                   |
| unpickle_pure_python       | 230 us                                                 | 234 us: 1.02x slower                                                    |
| deepcopy_memo              | 39.7 us                                                | 40.5 us: 1.02x slower                                                   |
| mdp                        | 2.57 sec                                               | 2.62 sec: 1.02x slower                                                  |
| pycparser                  | 1.17 sec                                               | 1.20 sec: 1.02x slower                                                  |
| pprint_safe_repr           | 765 ms                                                 | 783 ms: 1.02x slower                                                    |
| pickle                     | 11.2 us                                                | 11.5 us: 1.02x slower                                                   |
| async_tree_io              | 1.16 sec                                               | 1.19 sec: 1.02x slower                                                  |
| richards_super             | 51.9 ms                                                | 53.2 ms: 1.03x slower                                                   |
| async_tree_io_tg           | 1.19 sec                                               | 1.22 sec: 1.03x slower                                                  |
| pprint_pformat             | 1.55 sec                                               | 1.60 sec: 1.03x slower                                                  |
| async_tree_none_tg         | 447 ms                                                 | 461 ms: 1.03x slower                                                    |
| async_tree_cpu_io_mixed_tg | 725 ms                                                 | 748 ms: 1.03x slower                                                    |
| unpickle_list              | 5.04 us                                                | 5.25 us: 1.04x slower                                                   |
| xml_etree_iterparse        | 106 ms                                                 | 110 ms: 1.04x slower                                                    |
| pidigits                   | 187 ms                                                 | 195 ms: 1.04x slower                                                    |
| fannkuch                   | 410 ms                                                 | 431 ms: 1.05x slower                                                    |
| async_tree_memoization_tg  | 574 ms                                                 | 608 ms: 1.06x slower                                                    |
| regex_v8                   | 22.7 ms                                                | 24.0 ms: 1.06x slower                                                   |
| regex_dna                  | 209 ms                                                 | 221 ms: 1.06x slower                                                    |
| pickle_dict                | 33.5 us                                                | 35.7 us: 1.06x slower                                                   |
| mako                       | 11.5 ms                                                | 12.3 ms: 1.07x slower                                                   |
| nqueens                    | 86.2 ms                                                | 92.0 ms: 1.07x slower                                                   |
| pyflate                    | 471 ms                                                 | 503 ms: 1.07x slower                                                    |
| nbody                      | 92.2 ms                                                | 98.9 ms: 1.07x slower                                                   |
| go                         | 140 ms                                                 | 151 ms: 1.08x slower                                                    |
| python_startup             | 9.53 ms                                                | 10.4 ms: 1.09x slower                                                   |
| deltablue                  | 3.71 ms                                                | 4.08 ms: 1.10x slower                                                   |
| pickle_list                | 4.67 us                                                | 5.18 us: 1.11x slower                                                   |
| telco                      | 7.18 ms                                                | 8.38 ms: 1.17x slower                                                   |
| hexiom                     | 6.54 ms                                                | 7.65 ms: 1.17x slower                                                   |
| spectral_norm              | 115 ms                                                 | 136 ms: 1.19x slower                                                    |
| coverage                   | 75.1 ms                                                | 96.1 ms: 1.28x slower                                                   |
| python_startup_no_site     | 6.92 ms                                                | 9.07 ms: 1.31x slower                                                   |
| Geometric mean             | (ref)                                                  | 1.01x slower                                                            |

Benchmark hidden because not significant (9): async_tree_cpu_io_mixed, sqlite_synth, xml_etree_process, asyncio_websockets, bench_mp_pool, json_dumps, scimark_sparse_mat_mult, mypy2, scimark_monte_carlo
Ignored benchmarks (5) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 98.15% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
