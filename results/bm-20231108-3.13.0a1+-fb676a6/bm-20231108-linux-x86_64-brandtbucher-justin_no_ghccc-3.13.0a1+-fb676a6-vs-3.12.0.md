
# Results vs. 3.12.0

- fork: brandtbucher
- ref: justin_no_ghccc
- machine: linux-x86_64
- commit hash: fb676a6
- commit date: 2023-11-08
- overall geometric mean: 1.00x faster \*
- HPT reliability: 69.64%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231108-linux-x86_64-brandtbucher-justin_no_ghccc-3.13.0a1+-fb676a6 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| 2to3           | 274 ms                                                 | 273 ms: 1.00x faster                                                    |
| chameleon      | 7.41 ms                                                | 7.32 ms: 1.01x faster                                                   |
| docutils       | 2.75 sec                                               | 2.65 sec: 1.04x faster                                                  |
| tornado_http   | 101 ms                                                 | 96.8 ms: 1.04x faster                                                   |
| Geometric mean | (ref)                                                  | 1.02x faster                                                            |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231108-linux-x86_64-brandtbucher-justin_no_ghccc-3.13.0a1+-fb676a6 |
|----------------------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| async_tree_none            | 475 ms                                                 | 447 ms: 1.06x faster                                                    |
| async_tree_memoization     | 580 ms                                                 | 567 ms: 1.02x faster                                                    |
| async_tree_io              | 1.16 sec                                               | 1.18 sec: 1.02x slower                                                  |
| async_tree_none_tg         | 447 ms                                                 | 456 ms: 1.02x slower                                                    |
| async_tree_io_tg           | 1.19 sec                                               | 1.22 sec: 1.02x slower                                                  |
| async_tree_cpu_io_mixed_tg | 725 ms                                                 | 745 ms: 1.03x slower                                                    |
| async_tree_memoization_tg  | 574 ms                                                 | 598 ms: 1.04x slower                                                    |
| Geometric mean             | (ref)                                                  | 1.01x slower                                                            |

Benchmark hidden because not significant (1): async_tree_cpu_io_mixed

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231108-linux-x86_64-brandtbucher-justin_no_ghccc-3.13.0a1+-fb676a6 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| pidigits       | 187 ms                                                 | 188 ms: 1.00x slower                                                    |
| float          | 83.3 ms                                                | 86.8 ms: 1.04x slower                                                   |
| nbody          | 92.2 ms                                                | 103 ms: 1.11x slower                                                    |
| Geometric mean | (ref)                                                  | 1.05x slower                                                            |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231108-linux-x86_64-brandtbucher-justin_no_ghccc-3.13.0a1+-fb676a6 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| regex_compile  | 148 ms                                                 | 142 ms: 1.05x faster                                                    |
| regex_dna      | 209 ms                                                 | 215 ms: 1.03x slower                                                    |
| regex_effbot   | 3.57 ms                                                | 3.77 ms: 1.05x slower                                                   |
| regex_v8       | 22.7 ms                                                | 25.4 ms: 1.12x slower                                                   |
| Geometric mean | (ref)                                                  | 1.04x slower                                                            |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231108-linux-x86_64-brandtbucher-justin_no_ghccc-3.13.0a1+-fb676a6 |
|----------------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| pickle_pure_python   | 326 us                                                 | 303 us: 1.07x faster                                                    |
| tomli_loads          | 2.30 sec                                               | 2.16 sec: 1.07x faster                                                  |
| unpickle             | 15.8 us                                                | 15.1 us: 1.04x faster                                                   |
| json_loads           | 28.4 us                                                | 27.7 us: 1.02x faster                                                   |
| xml_etree_process    | 61.2 ms                                                | 60.0 ms: 1.02x faster                                                   |
| xml_etree_generate   | 88.7 ms                                                | 87.1 ms: 1.02x faster                                                   |
| pickle_dict          | 33.5 us                                                | 33.3 us: 1.01x faster                                                   |
| unpickle_pure_python | 230 us                                                 | 231 us: 1.01x slower                                                    |
| unpickle_list        | 5.04 us                                                | 5.07 us: 1.01x slower                                                   |
| xml_etree_iterparse  | 106 ms                                                 | 109 ms: 1.03x slower                                                    |
| pickle_list          | 4.67 us                                                | 4.83 us: 1.03x slower                                                   |
| pickle               | 11.2 us                                                | 11.6 us: 1.03x slower                                                   |
| Geometric mean       | (ref)                                                  | 1.01x faster                                                            |

Benchmark hidden because not significant (2): xml_etree_parse, json_dumps

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231108-linux-x86_64-brandtbucher-justin_no_ghccc-3.13.0a1+-fb676a6 |
|------------------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| python_startup         | 9.53 ms                                                | 10.4 ms: 1.09x slower                                                   |
| python_startup_no_site | 6.92 ms                                                | 9.12 ms: 1.32x slower                                                   |
| Geometric mean         | (ref)                                                  | 1.20x slower                                                            |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231108-linux-x86_64-brandtbucher-justin_no_ghccc-3.13.0a1+-fb676a6 |
|-----------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| mako      | 11.5 ms                                                | 12.1 ms: 1.05x slower                                                   |

All benchmarks:
===============

| Benchmark                  | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231108-linux-x86_64-brandtbucher-justin_no_ghccc-3.13.0a1+-fb676a6 |
|----------------------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| unpack_sequence            | 54.2 ns                                                | 41.4 ns: 1.31x faster                                                   |
| typing_runtime_protocols   | 153 us                                                 | 119 us: 1.29x faster                                                    |
| gc_traversal               | 4.28 ms                                                | 3.67 ms: 1.17x faster                                                   |
| logging_format             | 7.10 us                                                | 6.35 us: 1.12x faster                                                   |
| logging_simple             | 6.38 us                                                | 5.75 us: 1.11x faster                                                   |
| sympy_sum                  | 167 ms                                                 | 153 ms: 1.10x faster                                                    |
| generators                 | 32.5 ms                                                | 29.8 ms: 1.09x faster                                                   |
| raytrace                   | 308 ms                                                 | 284 ms: 1.08x faster                                                    |
| sympy_str                  | 296 ms                                                 | 274 ms: 1.08x faster                                                    |
| pickle_pure_python         | 326 us                                                 | 303 us: 1.07x faster                                                    |
| crypto_pyaes               | 83.6 ms                                                | 78.2 ms: 1.07x faster                                                   |
| tomli_loads                | 2.30 sec                                               | 2.16 sec: 1.07x faster                                                  |
| comprehensions             | 20.9 us                                                | 19.7 us: 1.06x faster                                                   |
| async_tree_none            | 475 ms                                                 | 447 ms: 1.06x faster                                                    |
| sqlglot_normalize          | 112 ms                                                 | 106 ms: 1.05x faster                                                    |
| regex_compile              | 148 ms                                                 | 142 ms: 1.05x faster                                                    |
| coroutines                 | 23.5 ms                                                | 22.5 ms: 1.04x faster                                                   |
| unpickle                   | 15.8 us                                                | 15.1 us: 1.04x faster                                                   |
| sqlglot_parse              | 1.35 ms                                                | 1.30 ms: 1.04x faster                                                   |
| docutils                   | 2.75 sec                                               | 2.65 sec: 1.04x faster                                                  |
| tornado_http               | 101 ms                                                 | 96.8 ms: 1.04x faster                                                   |
| asyncio_tcp                | 506 ms                                                 | 487 ms: 1.04x faster                                                    |
| sympy_expand               | 476 ms                                                 | 460 ms: 1.03x faster                                                    |
| dulwich_log                | 68.7 ms                                                | 66.6 ms: 1.03x faster                                                   |
| sqlglot_transpile          | 1.68 ms                                                | 1.63 ms: 1.03x faster                                                   |
| chaos                      | 67.5 ms                                                | 65.5 ms: 1.03x faster                                                   |
| sympy_integrate            | 21.2 ms                                                | 20.6 ms: 1.03x faster                                                   |
| json_loads                 | 28.4 us                                                | 27.7 us: 1.02x faster                                                   |
| scimark_sor                | 129 ms                                                 | 126 ms: 1.02x faster                                                    |
| deepcopy_reduce            | 3.23 us                                                | 3.16 us: 1.02x faster                                                   |
| spectral_norm              | 115 ms                                                 | 112 ms: 1.02x faster                                                    |
| async_tree_memoization     | 580 ms                                                 | 567 ms: 1.02x faster                                                    |
| deepcopy                   | 363 us                                                 | 355 us: 1.02x faster                                                    |
| xml_etree_process          | 61.2 ms                                                | 60.0 ms: 1.02x faster                                                   |
| xml_etree_generate         | 88.7 ms                                                | 87.1 ms: 1.02x faster                                                   |
| sqlite_synth               | 2.83 us                                                | 2.79 us: 1.02x faster                                                   |
| scimark_monte_carlo        | 74.6 ms                                                | 73.5 ms: 1.01x faster                                                   |
| chameleon                  | 7.41 ms                                                | 7.32 ms: 1.01x faster                                                   |
| logging_silent             | 108 ns                                                 | 106 ns: 1.01x faster                                                    |
| json                       | 5.22 ms                                                | 5.16 ms: 1.01x faster                                                   |
| sqlglot_optimize           | 54.8 ms                                                | 54.3 ms: 1.01x faster                                                   |
| pickle_dict                | 33.5 us                                                | 33.3 us: 1.01x faster                                                   |
| 2to3                       | 274 ms                                                 | 273 ms: 1.00x faster                                                    |
| pidigits                   | 187 ms                                                 | 188 ms: 1.00x slower                                                    |
| unpickle_pure_python       | 230 us                                                 | 231 us: 1.01x slower                                                    |
| unpickle_list              | 5.04 us                                                | 5.07 us: 1.01x slower                                                   |
| bench_thread_pool          | 845 us                                                 | 850 us: 1.01x slower                                                    |
| asyncio_tcp_ssl            | 1.78 sec                                               | 1.80 sec: 1.01x slower                                                  |
| scimark_fft                | 381 ms                                                 | 385 ms: 1.01x slower                                                    |
| async_generators           | 459 ms                                                 | 465 ms: 1.01x slower                                                    |
| create_gc_cycles           | 1.45 ms                                                | 1.47 ms: 1.01x slower                                                   |
| async_tree_io              | 1.16 sec                                               | 1.18 sec: 1.02x slower                                                  |
| pprint_safe_repr           | 765 ms                                                 | 778 ms: 1.02x slower                                                    |
| async_tree_none_tg         | 447 ms                                                 | 456 ms: 1.02x slower                                                    |
| pathlib                    | 18.9 ms                                                | 19.3 ms: 1.02x slower                                                   |
| async_tree_io_tg           | 1.19 sec                                               | 1.22 sec: 1.02x slower                                                  |
| deepcopy_memo              | 39.7 us                                                | 40.8 us: 1.03x slower                                                   |
| mdp                        | 2.57 sec                                               | 2.64 sec: 1.03x slower                                                  |
| richards                   | 46.0 ms                                                | 47.3 ms: 1.03x slower                                                   |
| async_tree_cpu_io_mixed_tg | 725 ms                                                 | 745 ms: 1.03x slower                                                    |
| xml_etree_iterparse        | 106 ms                                                 | 109 ms: 1.03x slower                                                    |
| scimark_sparse_mat_mult    | 5.33 ms                                                | 5.50 ms: 1.03x slower                                                   |
| meteor_contest             | 110 ms                                                 | 113 ms: 1.03x slower                                                    |
| pprint_pformat             | 1.55 sec                                               | 1.60 sec: 1.03x slower                                                  |
| regex_dna                  | 209 ms                                                 | 215 ms: 1.03x slower                                                    |
| pickle_list                | 4.67 us                                                | 4.83 us: 1.03x slower                                                   |
| pickle                     | 11.2 us                                                | 11.6 us: 1.03x slower                                                   |
| fannkuch                   | 410 ms                                                 | 424 ms: 1.04x slower                                                    |
| richards_super             | 51.9 ms                                                | 53.7 ms: 1.04x slower                                                   |
| async_tree_memoization_tg  | 574 ms                                                 | 598 ms: 1.04x slower                                                    |
| float                      | 83.3 ms                                                | 86.8 ms: 1.04x slower                                                   |
| mako                       | 11.5 ms                                                | 12.1 ms: 1.05x slower                                                   |
| regex_effbot               | 3.57 ms                                                | 3.77 ms: 1.05x slower                                                   |
| pyflate                    | 471 ms                                                 | 497 ms: 1.05x slower                                                    |
| go                         | 140 ms                                                 | 148 ms: 1.05x slower                                                    |
| nqueens                    | 86.2 ms                                                | 91.4 ms: 1.06x slower                                                   |
| deltablue                  | 3.71 ms                                                | 3.94 ms: 1.06x slower                                                   |
| python_startup             | 9.53 ms                                                | 10.4 ms: 1.09x slower                                                   |
| nbody                      | 92.2 ms                                                | 103 ms: 1.11x slower                                                    |
| regex_v8                   | 22.7 ms                                                | 25.4 ms: 1.12x slower                                                   |
| hexiom                     | 6.54 ms                                                | 7.51 ms: 1.15x slower                                                   |
| telco                      | 7.18 ms                                                | 9.01 ms: 1.26x slower                                                   |
| coverage                   | 75.1 ms                                                | 96.0 ms: 1.28x slower                                                   |
| python_startup_no_site     | 6.92 ms                                                | 9.12 ms: 1.32x slower                                                   |
| Geometric mean             | (ref)                                                  | 1.00x faster                                                            |

Benchmark hidden because not significant (8): pycparser, xml_etree_parse, mypy2, scimark_lu, asyncio_websockets, async_tree_cpu_io_mixed, bench_mp_pool, json_dumps
Ignored benchmarks (6) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, dask, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 69.64% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
