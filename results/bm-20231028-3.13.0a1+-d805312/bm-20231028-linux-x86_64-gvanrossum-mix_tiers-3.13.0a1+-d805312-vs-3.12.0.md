
# Results vs. 3.12.0

- fork: gvanrossum
- ref: mix_tiers
- machine: linux-x86_64
- commit hash: d805312
- commit date: 2023-10-28
- overall geometric mean: 1.02x faster
- HPT reliability: 99.83%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231028-linux-x86_64-gvanrossum-mix_tiers-3.13.0a1+-d805312 |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------:|
| 2to3           | 274 ms                                                 | 267 ms: 1.03x faster                                            |
| chameleon      | 7.41 ms                                                | 7.00 ms: 1.06x faster                                           |
| docutils       | 2.75 sec                                               | 2.66 sec: 1.04x faster                                          |
| tornado_http   | 101 ms                                                 | 95.8 ms: 1.05x faster                                           |
| Geometric mean | (ref)                                                  | 1.04x faster                                                    |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231028-linux-x86_64-gvanrossum-mix_tiers-3.13.0a1+-d805312 |
|----------------------------|:------------------------------------------------------:|:---------------------------------------------------------------:|
| async_tree_none            | 475 ms                                                 | 439 ms: 1.08x faster                                            |
| async_tree_memoization     | 580 ms                                                 | 565 ms: 1.03x faster                                            |
| async_tree_cpu_io_mixed    | 724 ms                                                 | 710 ms: 1.02x faster                                            |
| async_tree_cpu_io_mixed_tg | 725 ms                                                 | 740 ms: 1.02x slower                                            |
| async_tree_io              | 1.16 sec                                               | 1.19 sec: 1.02x slower                                          |
| async_tree_none_tg         | 447 ms                                                 | 459 ms: 1.03x slower                                            |
| async_tree_io_tg           | 1.19 sec                                               | 1.23 sec: 1.03x slower                                          |
| async_tree_memoization_tg  | 574 ms                                                 | 596 ms: 1.04x slower                                            |
| Geometric mean             | (ref)                                                  | 1.00x slower                                                    |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231028-linux-x86_64-gvanrossum-mix_tiers-3.13.0a1+-d805312 |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------:|
| float          | 83.3 ms                                                | 82.0 ms: 1.02x faster                                           |
| nbody          | 92.2 ms                                                | 92.8 ms: 1.01x slower                                           |
| pidigits       | 187 ms                                                 | 195 ms: 1.04x slower                                            |
| Geometric mean | (ref)                                                  | 1.01x slower                                                    |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231028-linux-x86_64-gvanrossum-mix_tiers-3.13.0a1+-d805312 |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------:|
| regex_compile  | 148 ms                                                 | 139 ms: 1.07x faster                                            |
| regex_dna      | 209 ms                                                 | 217 ms: 1.04x slower                                            |
| regex_effbot   | 3.57 ms                                                | 3.76 ms: 1.05x slower                                           |
| regex_v8       | 22.7 ms                                                | 25.4 ms: 1.12x slower                                           |
| Geometric mean | (ref)                                                  | 1.04x slower                                                    |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231028-linux-x86_64-gvanrossum-mix_tiers-3.13.0a1+-d805312 |
|----------------------|:------------------------------------------------------:|:---------------------------------------------------------------:|
| unpickle             | 15.8 us                                                | 14.5 us: 1.09x faster                                           |
| pickle_pure_python   | 326 us                                                 | 305 us: 1.07x faster                                            |
| tomli_loads          | 2.30 sec                                               | 2.15 sec: 1.07x faster                                          |
| unpickle_pure_python | 230 us                                                 | 221 us: 1.04x faster                                            |
| xml_etree_process    | 61.2 ms                                                | 59.6 ms: 1.03x faster                                           |
| xml_etree_generate   | 88.7 ms                                                | 86.7 ms: 1.02x faster                                           |
| json_loads           | 28.4 us                                                | 27.7 us: 1.02x faster                                           |
| xml_etree_parse      | 159 ms                                                 | 158 ms: 1.01x faster                                            |
| json_dumps           | 10.6 ms                                                | 10.5 ms: 1.01x faster                                           |
| pickle_dict          | 33.5 us                                                | 33.4 us: 1.00x faster                                           |
| pickle               | 11.2 us                                                | 11.3 us: 1.00x slower                                           |
| unpickle_list        | 5.04 us                                                | 5.11 us: 1.01x slower                                           |
| pickle_list          | 4.67 us                                                | 4.99 us: 1.07x slower                                           |
| Geometric mean       | (ref)                                                  | 1.02x faster                                                    |

Benchmark hidden because not significant (1): xml_etree_iterparse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231028-linux-x86_64-gvanrossum-mix_tiers-3.13.0a1+-d805312 |
|------------------------|:------------------------------------------------------:|:---------------------------------------------------------------:|
| python_startup         | 9.53 ms                                                | 10.3 ms: 1.08x slower                                           |
| python_startup_no_site | 6.92 ms                                                | 8.96 ms: 1.30x slower                                           |
| Geometric mean         | (ref)                                                  | 1.18x slower                                                    |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231028-linux-x86_64-gvanrossum-mix_tiers-3.13.0a1+-d805312 |
|-----------|:------------------------------------------------------:|:---------------------------------------------------------------:|
| mako      | 11.5 ms                                                | 11.4 ms: 1.01x faster                                           |

All benchmarks:
===============

| Benchmark                  | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231028-linux-x86_64-gvanrossum-mix_tiers-3.13.0a1+-d805312 |
|----------------------------|:------------------------------------------------------:|:---------------------------------------------------------------:|
| unpack_sequence            | 54.2 ns                                                | 42.6 ns: 1.27x faster                                           |
| comprehensions             | 20.9 us                                                | 16.8 us: 1.25x faster                                           |
| crypto_pyaes               | 83.6 ms                                                | 73.3 ms: 1.14x faster                                           |
| sympy_sum                  | 167 ms                                                 | 148 ms: 1.13x faster                                            |
| raytrace                   | 308 ms                                                 | 275 ms: 1.12x faster                                            |
| sympy_str                  | 296 ms                                                 | 267 ms: 1.11x faster                                            |
| deltablue                  | 3.71 ms                                                | 3.36 ms: 1.10x faster                                           |
| generators                 | 32.5 ms                                                | 29.7 ms: 1.09x faster                                           |
| chaos                      | 67.5 ms                                                | 61.9 ms: 1.09x faster                                           |
| logging_format             | 7.10 us                                                | 6.52 us: 1.09x faster                                           |
| unpickle                   | 15.8 us                                                | 14.5 us: 1.09x faster                                           |
| gc_traversal               | 4.28 ms                                                | 3.94 ms: 1.08x faster                                           |
| async_tree_none            | 475 ms                                                 | 439 ms: 1.08x faster                                            |
| scimark_monte_carlo        | 74.6 ms                                                | 68.9 ms: 1.08x faster                                           |
| logging_simple             | 6.38 us                                                | 5.95 us: 1.07x faster                                           |
| pickle_pure_python         | 326 us                                                 | 305 us: 1.07x faster                                            |
| regex_compile              | 148 ms                                                 | 139 ms: 1.07x faster                                            |
| tomli_loads                | 2.30 sec                                               | 2.15 sec: 1.07x faster                                          |
| sympy_integrate            | 21.2 ms                                                | 19.9 ms: 1.07x faster                                           |
| nqueens                    | 86.2 ms                                                | 81.3 ms: 1.06x faster                                           |
| asyncio_tcp                | 506 ms                                                 | 477 ms: 1.06x faster                                            |
| scimark_sparse_mat_mult    | 5.33 ms                                                | 5.03 ms: 1.06x faster                                           |
| chameleon                  | 7.41 ms                                                | 7.00 ms: 1.06x faster                                           |
| sqlglot_parse              | 1.35 ms                                                | 1.28 ms: 1.06x faster                                           |
| sqlglot_normalize          | 112 ms                                                 | 106 ms: 1.05x faster                                            |
| tornado_http               | 101 ms                                                 | 95.8 ms: 1.05x faster                                           |
| sympy_expand               | 476 ms                                                 | 453 ms: 1.05x faster                                            |
| sqlglot_transpile          | 1.68 ms                                                | 1.60 ms: 1.05x faster                                           |
| hexiom                     | 6.54 ms                                                | 6.28 ms: 1.04x faster                                           |
| coroutines                 | 23.5 ms                                                | 22.5 ms: 1.04x faster                                           |
| scimark_lu                 | 120 ms                                                 | 116 ms: 1.04x faster                                            |
| bench_thread_pool          | 845 us                                                 | 815 us: 1.04x faster                                            |
| docutils                   | 2.75 sec                                               | 2.66 sec: 1.04x faster                                          |
| unpickle_pure_python       | 230 us                                                 | 221 us: 1.04x faster                                            |
| dulwich_log                | 68.7 ms                                                | 66.7 ms: 1.03x faster                                           |
| mypy2                      | 351 ms                                                 | 341 ms: 1.03x faster                                            |
| xml_etree_process          | 61.2 ms                                                | 59.6 ms: 1.03x faster                                           |
| 2to3                       | 274 ms                                                 | 267 ms: 1.03x faster                                            |
| async_tree_memoization     | 580 ms                                                 | 565 ms: 1.03x faster                                            |
| sqlglot_optimize           | 54.8 ms                                                | 53.5 ms: 1.03x faster                                           |
| xml_etree_generate         | 88.7 ms                                                | 86.7 ms: 1.02x faster                                           |
| json_loads                 | 28.4 us                                                | 27.7 us: 1.02x faster                                           |
| async_tree_cpu_io_mixed    | 724 ms                                                 | 710 ms: 1.02x faster                                            |
| json                       | 5.22 ms                                                | 5.12 ms: 1.02x faster                                           |
| spectral_norm              | 115 ms                                                 | 113 ms: 1.02x faster                                            |
| float                      | 83.3 ms                                                | 82.0 ms: 1.02x faster                                           |
| deepcopy                   | 363 us                                                 | 357 us: 1.01x faster                                            |
| deepcopy_reduce            | 3.23 us                                                | 3.18 us: 1.01x faster                                           |
| mdp                        | 2.57 sec                                               | 2.53 sec: 1.01x faster                                          |
| pprint_safe_repr           | 765 ms                                                 | 757 ms: 1.01x faster                                            |
| mako                       | 11.5 ms                                                | 11.4 ms: 1.01x faster                                           |
| scimark_fft                | 381 ms                                                 | 377 ms: 1.01x faster                                            |
| xml_etree_parse            | 159 ms                                                 | 158 ms: 1.01x faster                                            |
| fannkuch                   | 410 ms                                                 | 407 ms: 1.01x faster                                            |
| meteor_contest             | 110 ms                                                 | 109 ms: 1.01x faster                                            |
| pprint_pformat             | 1.55 sec                                               | 1.54 sec: 1.01x faster                                          |
| logging_silent             | 108 ns                                                 | 107 ns: 1.01x faster                                            |
| json_dumps                 | 10.6 ms                                                | 10.5 ms: 1.01x faster                                           |
| pickle_dict                | 33.5 us                                                | 33.4 us: 1.00x faster                                           |
| asyncio_tcp_ssl            | 1.78 sec                                               | 1.78 sec: 1.00x slower                                          |
| pickle                     | 11.2 us                                                | 11.3 us: 1.00x slower                                           |
| nbody                      | 92.2 ms                                                | 92.8 ms: 1.01x slower                                           |
| unpickle_list              | 5.04 us                                                | 5.11 us: 1.01x slower                                           |
| typing_runtime_protocols   | 153 us                                                 | 156 us: 1.02x slower                                            |
| create_gc_cycles           | 1.45 ms                                                | 1.48 ms: 1.02x slower                                           |
| pyflate                    | 471 ms                                                 | 480 ms: 1.02x slower                                            |
| async_tree_cpu_io_mixed_tg | 725 ms                                                 | 740 ms: 1.02x slower                                            |
| async_tree_io              | 1.16 sec                                               | 1.19 sec: 1.02x slower                                          |
| async_tree_none_tg         | 447 ms                                                 | 459 ms: 1.03x slower                                            |
| go                         | 140 ms                                                 | 145 ms: 1.03x slower                                            |
| async_tree_io_tg           | 1.19 sec                                               | 1.23 sec: 1.03x slower                                          |
| scimark_sor                | 129 ms                                                 | 134 ms: 1.03x slower                                            |
| async_tree_memoization_tg  | 574 ms                                                 | 596 ms: 1.04x slower                                            |
| regex_dna                  | 209 ms                                                 | 217 ms: 1.04x slower                                            |
| pidigits                   | 187 ms                                                 | 195 ms: 1.04x slower                                            |
| regex_effbot               | 3.57 ms                                                | 3.76 ms: 1.05x slower                                           |
| richards_super             | 51.9 ms                                                | 55.2 ms: 1.06x slower                                           |
| pickle_list                | 4.67 us                                                | 4.99 us: 1.07x slower                                           |
| richards                   | 46.0 ms                                                | 49.4 ms: 1.07x slower                                           |
| python_startup             | 9.53 ms                                                | 10.3 ms: 1.08x slower                                           |
| regex_v8                   | 22.7 ms                                                | 25.4 ms: 1.12x slower                                           |
| telco                      | 7.18 ms                                                | 8.40 ms: 1.17x slower                                           |
| coverage                   | 75.1 ms                                                | 94.9 ms: 1.26x slower                                           |
| python_startup_no_site     | 6.92 ms                                                | 8.96 ms: 1.30x slower                                           |
| Geometric mean             | (ref)                                                  | 1.02x faster                                                    |

Benchmark hidden because not significant (8): bench_mp_pool, asyncio_websockets, async_generators, pycparser, deepcopy_memo, sqlite_synth, pathlib, xml_etree_iterparse
Ignored benchmarks (6) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, dask, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 99.83% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
