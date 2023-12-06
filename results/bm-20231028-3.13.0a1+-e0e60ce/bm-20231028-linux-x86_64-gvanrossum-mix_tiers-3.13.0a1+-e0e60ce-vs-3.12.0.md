
# Results vs. 3.12.0

- fork: gvanrossum
- ref: mix_tiers
- machine: linux-x86_64
- commit hash: e0e60ce
- commit date: 2023-10-28
- overall geometric mean: 1.04x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.01x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231028-linux-x86_64-gvanrossum-mix_tiers-3.13.0a1+-e0e60ce |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------:|
| 2to3           | 274 ms                                                 | 290 ms: 1.06x slower                                            |
| chameleon      | 7.41 ms                                                | 7.56 ms: 1.02x slower                                           |
| tornado_http   | 101 ms                                                 | 102 ms: 1.02x slower                                            |
| Geometric mean | (ref)                                                  | 1.02x slower                                                    |

Benchmark hidden because not significant (1): docutils

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231028-linux-x86_64-gvanrossum-mix_tiers-3.13.0a1+-e0e60ce |
|----------------------------|:------------------------------------------------------:|:---------------------------------------------------------------:|
| async_tree_none            | 475 ms                                                 | 448 ms: 1.06x faster                                            |
| async_tree_cpu_io_mixed_tg | 725 ms                                                 | 750 ms: 1.03x slower                                            |
| async_tree_io              | 1.16 sec                                               | 1.20 sec: 1.04x slower                                          |
| async_tree_none_tg         | 447 ms                                                 | 465 ms: 1.04x slower                                            |
| async_tree_io_tg           | 1.19 sec                                               | 1.25 sec: 1.05x slower                                          |
| async_tree_memoization_tg  | 574 ms                                                 | 613 ms: 1.07x slower                                            |
| Geometric mean             | (ref)                                                  | 1.02x slower                                                    |

Benchmark hidden because not significant (2): async_tree_cpu_io_mixed, async_tree_memoization

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231028-linux-x86_64-gvanrossum-mix_tiers-3.13.0a1+-e0e60ce |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------:|
| pidigits       | 187 ms                                                 | 188 ms: 1.00x slower                                            |
| float          | 83.3 ms                                                | 95.1 ms: 1.14x slower                                           |
| nbody          | 92.2 ms                                                | 118 ms: 1.28x slower                                            |
| Geometric mean | (ref)                                                  | 1.14x slower                                                    |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231028-linux-x86_64-gvanrossum-mix_tiers-3.13.0a1+-e0e60ce |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------:|
| regex_effbot   | 3.57 ms                                                | 3.58 ms: 1.00x slower                                           |
| regex_dna      | 209 ms                                                 | 222 ms: 1.06x slower                                            |
| regex_v8       | 22.7 ms                                                | 24.6 ms: 1.08x slower                                           |
| regex_compile  | 148 ms                                                 | 165 ms: 1.11x slower                                            |
| Geometric mean | (ref)                                                  | 1.06x slower                                                    |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231028-linux-x86_64-gvanrossum-mix_tiers-3.13.0a1+-e0e60ce |
|----------------------|:------------------------------------------------------:|:---------------------------------------------------------------:|
| pickle_pure_python   | 326 us                                                 | 311 us: 1.05x faster                                            |
| unpickle             | 15.8 us                                                | 15.0 us: 1.05x faster                                           |
| pickle_dict          | 33.5 us                                                | 32.6 us: 1.03x faster                                           |
| json_loads           | 28.4 us                                                | 27.7 us: 1.03x faster                                           |
| xml_etree_process    | 61.2 ms                                                | 60.2 ms: 1.02x faster                                           |
| pickle               | 11.2 us                                                | 11.0 us: 1.02x faster                                           |
| xml_etree_parse      | 159 ms                                                 | 158 ms: 1.01x faster                                            |
| json_dumps           | 10.6 ms                                                | 10.5 ms: 1.01x faster                                           |
| xml_etree_generate   | 88.7 ms                                                | 88.3 ms: 1.01x faster                                           |
| unpickle_pure_python | 230 us                                                 | 239 us: 1.04x slower                                            |
| pickle_list          | 4.67 us                                                | 4.87 us: 1.04x slower                                           |
| xml_etree_iterparse  | 106 ms                                                 | 111 ms: 1.05x slower                                            |
| unpickle_list        | 5.04 us                                                | 5.34 us: 1.06x slower                                           |
| tomli_loads          | 2.30 sec                                               | 2.48 sec: 1.08x slower                                          |
| Geometric mean       | (ref)                                                  | 1.00x slower                                                    |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231028-linux-x86_64-gvanrossum-mix_tiers-3.13.0a1+-e0e60ce |
|------------------------|:------------------------------------------------------:|:---------------------------------------------------------------:|
| python_startup         | 9.53 ms                                                | 10.3 ms: 1.08x slower                                           |
| python_startup_no_site | 6.92 ms                                                | 9.01 ms: 1.30x slower                                           |
| Geometric mean         | (ref)                                                  | 1.19x slower                                                    |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231028-linux-x86_64-gvanrossum-mix_tiers-3.13.0a1+-e0e60ce |
|-----------|:------------------------------------------------------:|:---------------------------------------------------------------:|
| mako      | 11.5 ms                                                | 13.8 ms: 1.20x slower                                           |

All benchmarks:
===============

| Benchmark                  | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231028-linux-x86_64-gvanrossum-mix_tiers-3.13.0a1+-e0e60ce |
|----------------------------|:------------------------------------------------------:|:---------------------------------------------------------------:|
| unpack_sequence            | 54.2 ns                                                | 49.6 ns: 1.09x faster                                           |
| sympy_sum                  | 167 ms                                                 | 157 ms: 1.07x faster                                            |
| async_tree_none            | 475 ms                                                 | 448 ms: 1.06x faster                                            |
| gc_traversal               | 4.28 ms                                                | 4.07 ms: 1.05x faster                                           |
| pickle_pure_python         | 326 us                                                 | 311 us: 1.05x faster                                            |
| unpickle                   | 15.8 us                                                | 15.0 us: 1.05x faster                                           |
| asyncio_tcp                | 506 ms                                                 | 482 ms: 1.05x faster                                            |
| sqlglot_normalize          | 112 ms                                                 | 108 ms: 1.03x faster                                            |
| pickle_dict                | 33.5 us                                                | 32.6 us: 1.03x faster                                           |
| json_loads                 | 28.4 us                                                | 27.7 us: 1.03x faster                                           |
| sympy_str                  | 296 ms                                                 | 289 ms: 1.02x faster                                            |
| deepcopy_reduce            | 3.23 us                                                | 3.17 us: 1.02x faster                                           |
| coroutines                 | 23.5 ms                                                | 23.0 ms: 1.02x faster                                           |
| xml_etree_process          | 61.2 ms                                                | 60.2 ms: 1.02x faster                                           |
| pickle                     | 11.2 us                                                | 11.0 us: 1.02x faster                                           |
| xml_etree_parse            | 159 ms                                                 | 158 ms: 1.01x faster                                            |
| json_dumps                 | 10.6 ms                                                | 10.5 ms: 1.01x faster                                           |
| sqlglot_parse              | 1.35 ms                                                | 1.34 ms: 1.01x faster                                           |
| xml_etree_generate         | 88.7 ms                                                | 88.3 ms: 1.01x faster                                           |
| scimark_lu                 | 120 ms                                                 | 120 ms: 1.01x faster                                            |
| regex_effbot               | 3.57 ms                                                | 3.58 ms: 1.00x slower                                           |
| pidigits                   | 187 ms                                                 | 188 ms: 1.00x slower                                            |
| asyncio_tcp_ssl            | 1.78 sec                                               | 1.79 sec: 1.00x slower                                          |
| bench_thread_pool          | 845 us                                                 | 850 us: 1.01x slower                                            |
| create_gc_cycles           | 1.45 ms                                                | 1.46 ms: 1.01x slower                                           |
| sqlglot_optimize           | 54.8 ms                                                | 55.3 ms: 1.01x slower                                           |
| logging_simple             | 6.38 us                                                | 6.44 us: 1.01x slower                                           |
| generators                 | 32.5 ms                                                | 32.8 ms: 1.01x slower                                           |
| dulwich_log                | 68.7 ms                                                | 69.8 ms: 1.02x slower                                           |
| crypto_pyaes               | 83.6 ms                                                | 84.9 ms: 1.02x slower                                           |
| spectral_norm              | 115 ms                                                 | 117 ms: 1.02x slower                                            |
| tornado_http               | 101 ms                                                 | 102 ms: 1.02x slower                                            |
| raytrace                   | 308 ms                                                 | 313 ms: 1.02x slower                                            |
| mypy2                      | 351 ms                                                 | 358 ms: 1.02x slower                                            |
| sympy_integrate            | 21.2 ms                                                | 21.6 ms: 1.02x slower                                           |
| logging_silent             | 108 ns                                                 | 110 ns: 1.02x slower                                            |
| chameleon                  | 7.41 ms                                                | 7.56 ms: 1.02x slower                                           |
| logging_format             | 7.10 us                                                | 7.25 us: 1.02x slower                                           |
| scimark_monte_carlo        | 74.6 ms                                                | 76.2 ms: 1.02x slower                                           |
| sympy_expand               | 476 ms                                                 | 486 ms: 1.02x slower                                            |
| async_generators           | 459 ms                                                 | 472 ms: 1.03x slower                                            |
| pycparser                  | 1.17 sec                                               | 1.21 sec: 1.03x slower                                          |
| async_tree_cpu_io_mixed_tg | 725 ms                                                 | 750 ms: 1.03x slower                                            |
| async_tree_io              | 1.16 sec                                               | 1.20 sec: 1.04x slower                                          |
| async_tree_none_tg         | 447 ms                                                 | 465 ms: 1.04x slower                                            |
| unpickle_pure_python       | 230 us                                                 | 239 us: 1.04x slower                                            |
| pickle_list                | 4.67 us                                                | 4.87 us: 1.04x slower                                           |
| mdp                        | 2.57 sec                                               | 2.68 sec: 1.04x slower                                          |
| xml_etree_iterparse        | 106 ms                                                 | 111 ms: 1.05x slower                                            |
| typing_runtime_protocols   | 153 us                                                 | 161 us: 1.05x slower                                            |
| async_tree_io_tg           | 1.19 sec                                               | 1.25 sec: 1.05x slower                                          |
| meteor_contest             | 110 ms                                                 | 116 ms: 1.05x slower                                            |
| comprehensions             | 20.9 us                                                | 22.1 us: 1.06x slower                                           |
| unpickle_list              | 5.04 us                                                | 5.34 us: 1.06x slower                                           |
| 2to3                       | 274 ms                                                 | 290 ms: 1.06x slower                                            |
| pathlib                    | 18.9 ms                                                | 20.0 ms: 1.06x slower                                           |
| regex_dna                  | 209 ms                                                 | 222 ms: 1.06x slower                                            |
| async_tree_memoization_tg  | 574 ms                                                 | 613 ms: 1.07x slower                                            |
| deepcopy_memo              | 39.7 us                                                | 42.6 us: 1.07x slower                                           |
| pprint_safe_repr           | 765 ms                                                 | 820 ms: 1.07x slower                                            |
| tomli_loads                | 2.30 sec                                               | 2.48 sec: 1.08x slower                                          |
| python_startup             | 9.53 ms                                                | 10.3 ms: 1.08x slower                                           |
| regex_v8                   | 22.7 ms                                                | 24.6 ms: 1.08x slower                                           |
| pprint_pformat             | 1.55 sec                                               | 1.69 sec: 1.09x slower                                          |
| richards                   | 46.0 ms                                                | 50.6 ms: 1.10x slower                                           |
| pyflate                    | 471 ms                                                 | 520 ms: 1.10x slower                                            |
| fannkuch                   | 410 ms                                                 | 453 ms: 1.11x slower                                            |
| richards_super             | 51.9 ms                                                | 57.5 ms: 1.11x slower                                           |
| scimark_sparse_mat_mult    | 5.33 ms                                                | 5.92 ms: 1.11x slower                                           |
| regex_compile              | 148 ms                                                 | 165 ms: 1.11x slower                                            |
| scimark_fft                | 381 ms                                                 | 424 ms: 1.11x slower                                            |
| chaos                      | 67.5 ms                                                | 75.7 ms: 1.12x slower                                           |
| float                      | 83.3 ms                                                | 95.1 ms: 1.14x slower                                           |
| nqueens                    | 86.2 ms                                                | 99.1 ms: 1.15x slower                                           |
| go                         | 140 ms                                                 | 165 ms: 1.18x slower                                            |
| mako                       | 11.5 ms                                                | 13.8 ms: 1.20x slower                                           |
| telco                      | 7.18 ms                                                | 8.65 ms: 1.21x slower                                           |
| coverage                   | 75.1 ms                                                | 94.3 ms: 1.26x slower                                           |
| deltablue                  | 3.71 ms                                                | 4.73 ms: 1.28x slower                                           |
| nbody                      | 92.2 ms                                                | 118 ms: 1.28x slower                                            |
| python_startup_no_site     | 6.92 ms                                                | 9.01 ms: 1.30x slower                                           |
| hexiom                     | 6.54 ms                                                | 8.96 ms: 1.37x slower                                           |
| Geometric mean             | (ref)                                                  | 1.04x slower                                                    |

Benchmark hidden because not significant (10): async_tree_cpu_io_mixed, async_tree_memoization, sqlglot_transpile, json, asyncio_websockets, sqlite_synth, bench_mp_pool, scimark_sor, deepcopy, docutils
Ignored benchmarks (6) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, dask, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.02x
- 95% likely to have a slowdown of 1.01x
- 99% likely to have a slowdown of 1.01x
