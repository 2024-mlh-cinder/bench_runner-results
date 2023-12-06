
# Results vs. 3.12.0

- fork: brandtbucher
- ref: justin
- machine: linux-x86_64
- commit hash: dfface9
- commit date: 2023-11-28
- overall geometric mean: 1.02x slower \*
- HPT reliability: 92.32%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231128-linux-x86_64-brandtbucher-justin-3.13.0a2+-dfface9 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| 2to3           | 274 ms                                                 | 273 ms: 1.00x faster                                           |
| chameleon      | 7.41 ms                                                | 7.19 ms: 1.03x faster                                          |
| docutils       | 2.75 sec                                               | 2.67 sec: 1.03x faster                                         |
| tornado_http   | 101 ms                                                 | 97.0 ms: 1.04x faster                                          |
| Geometric mean | (ref)                                                  | 1.03x faster                                                   |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231128-linux-x86_64-brandtbucher-justin-3.13.0a2+-dfface9 |
|----------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| async_tree_none            | 475 ms                                                 | 443 ms: 1.07x faster                                           |
| async_tree_memoization     | 580 ms                                                 | 568 ms: 1.02x faster                                           |
| async_tree_cpu_io_mixed    | 724 ms                                                 | 714 ms: 1.01x faster                                           |
| async_tree_none_tg         | 447 ms                                                 | 460 ms: 1.03x slower                                           |
| async_tree_io              | 1.16 sec                                               | 1.20 sec: 1.03x slower                                         |
| async_tree_cpu_io_mixed_tg | 725 ms                                                 | 746 ms: 1.03x slower                                           |
| async_tree_io_tg           | 1.19 sec                                               | 1.23 sec: 1.03x slower                                         |
| async_tree_memoization_tg  | 574 ms                                                 | 616 ms: 1.07x slower                                           |
| Geometric mean             | (ref)                                                  | 1.01x slower                                                   |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231128-linux-x86_64-brandtbucher-justin-3.13.0a2+-dfface9 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| float          | 83.3 ms                                                | 84.9 ms: 1.02x slower                                          |
| pidigits       | 187 ms                                                 | 196 ms: 1.05x slower                                           |
| nbody          | 92.2 ms                                                | 98.4 ms: 1.07x slower                                          |
| Geometric mean | (ref)                                                  | 1.04x slower                                                   |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231128-linux-x86_64-brandtbucher-justin-3.13.0a2+-dfface9 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| regex_compile  | 148 ms                                                 | 143 ms: 1.04x faster                                           |
| regex_effbot   | 3.57 ms                                                | 3.71 ms: 1.04x slower                                          |
| regex_dna      | 209 ms                                                 | 222 ms: 1.06x slower                                           |
| regex_v8       | 22.7 ms                                                | 26.0 ms: 1.15x slower                                          |
| Geometric mean | (ref)                                                  | 1.05x slower                                                   |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231128-linux-x86_64-brandtbucher-justin-3.13.0a2+-dfface9 |
|----------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| pickle_pure_python   | 326 us                                                 | 305 us: 1.07x faster                                           |
| tomli_loads          | 2.30 sec                                               | 2.15 sec: 1.07x faster                                         |
| unpickle_list        | 5.04 us                                                | 4.96 us: 1.02x faster                                          |
| json_loads           | 28.4 us                                                | 28.1 us: 1.01x faster                                          |
| unpickle             | 15.8 us                                                | 15.7 us: 1.01x faster                                          |
| unpickle_pure_python | 230 us                                                 | 231 us: 1.00x slower                                           |
| xml_etree_parse      | 159 ms                                                 | 161 ms: 1.01x slower                                           |
| pickle               | 11.2 us                                                | 11.6 us: 1.03x slower                                          |
| xml_etree_iterparse  | 106 ms                                                 | 110 ms: 1.05x slower                                           |
| pickle_list          | 4.67 us                                                | 5.05 us: 1.08x slower                                          |
| pickle_dict          | 33.5 us                                                | 36.4 us: 1.09x slower                                          |
| Geometric mean       | (ref)                                                  | 1.01x slower                                                   |

Benchmark hidden because not significant (3): xml_etree_process, xml_etree_generate, json_dumps

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231128-linux-x86_64-brandtbucher-justin-3.13.0a2+-dfface9 |
|------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| python_startup         | 9.53 ms                                                | 10.4 ms: 1.10x slower                                          |
| python_startup_no_site | 6.92 ms                                                | 9.11 ms: 1.32x slower                                          |
| Geometric mean         | (ref)                                                  | 1.20x slower                                                   |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231128-linux-x86_64-brandtbucher-justin-3.13.0a2+-dfface9 |
|-----------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| mako      | 11.5 ms                                                | 12.2 ms: 1.06x slower                                          |

All benchmarks:
===============

| Benchmark                  | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231128-linux-x86_64-brandtbucher-justin-3.13.0a2+-dfface9 |
|----------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| typing_runtime_protocols   | 153 us                                                 | 119 us: 1.28x faster                                           |
| generators                 | 32.5 ms                                                | 28.7 ms: 1.13x faster                                          |
| gc_traversal               | 4.28 ms                                                | 3.85 ms: 1.11x faster                                          |
| logging_format             | 7.10 us                                                | 6.45 us: 1.10x faster                                          |
| logging_simple             | 6.38 us                                                | 5.84 us: 1.09x faster                                          |
| comprehensions             | 20.9 us                                                | 19.3 us: 1.09x faster                                          |
| raytrace                   | 308 ms                                                 | 285 ms: 1.08x faster                                           |
| async_tree_none            | 475 ms                                                 | 443 ms: 1.07x faster                                           |
| crypto_pyaes               | 83.6 ms                                                | 78.0 ms: 1.07x faster                                          |
| pickle_pure_python         | 326 us                                                 | 305 us: 1.07x faster                                           |
| tomli_loads                | 2.30 sec                                               | 2.15 sec: 1.07x faster                                         |
| sympy_sum                  | 167 ms                                                 | 157 ms: 1.06x faster                                           |
| sympy_str                  | 296 ms                                                 | 280 ms: 1.06x faster                                           |
| scimark_sparse_mat_mult    | 5.33 ms                                                | 5.06 ms: 1.05x faster                                          |
| scimark_sor                | 129 ms                                                 | 123 ms: 1.05x faster                                           |
| regex_compile              | 148 ms                                                 | 143 ms: 1.04x faster                                           |
| deepcopy_reduce            | 3.23 us                                                | 3.11 us: 1.04x faster                                          |
| sqlglot_parse              | 1.35 ms                                                | 1.30 ms: 1.04x faster                                          |
| tornado_http               | 101 ms                                                 | 97.0 ms: 1.04x faster                                          |
| pathlib                    | 18.9 ms                                                | 18.3 ms: 1.04x faster                                          |
| coroutines                 | 23.5 ms                                                | 22.7 ms: 1.03x faster                                          |
| dulwich_log                | 68.7 ms                                                | 66.5 ms: 1.03x faster                                          |
| scimark_lu                 | 120 ms                                                 | 116 ms: 1.03x faster                                           |
| sqlglot_transpile          | 1.68 ms                                                | 1.63 ms: 1.03x faster                                          |
| docutils                   | 2.75 sec                                               | 2.67 sec: 1.03x faster                                         |
| chameleon                  | 7.41 ms                                                | 7.19 ms: 1.03x faster                                          |
| scimark_fft                | 381 ms                                                 | 371 ms: 1.03x faster                                           |
| asyncio_tcp                | 506 ms                                                 | 494 ms: 1.02x faster                                           |
| sympy_integrate            | 21.2 ms                                                | 20.7 ms: 1.02x faster                                          |
| deepcopy                   | 363 us                                                 | 355 us: 1.02x faster                                           |
| async_tree_memoization     | 580 ms                                                 | 568 ms: 1.02x faster                                           |
| json                       | 5.22 ms                                                | 5.12 ms: 1.02x faster                                          |
| unpickle_list              | 5.04 us                                                | 4.96 us: 1.02x faster                                          |
| chaos                      | 67.5 ms                                                | 66.4 ms: 1.02x faster                                          |
| sqlglot_normalize          | 112 ms                                                 | 110 ms: 1.02x faster                                           |
| async_tree_cpu_io_mixed    | 724 ms                                                 | 714 ms: 1.01x faster                                           |
| dask                       | 369 ms                                                 | 365 ms: 1.01x faster                                           |
| json_loads                 | 28.4 us                                                | 28.1 us: 1.01x faster                                          |
| sympy_expand               | 476 ms                                                 | 470 ms: 1.01x faster                                           |
| sqlite_synth               | 2.83 us                                                | 2.80 us: 1.01x faster                                          |
| unpickle                   | 15.8 us                                                | 15.7 us: 1.01x faster                                          |
| deepcopy_memo              | 39.7 us                                                | 39.6 us: 1.00x faster                                          |
| 2to3                       | 274 ms                                                 | 273 ms: 1.00x faster                                           |
| bench_mp_pool              | 24.0 ms                                                | 24.0 ms: 1.00x slower                                          |
| bench_thread_pool          | 845 us                                                 | 848 us: 1.00x slower                                           |
| logging_silent             | 108 ns                                                 | 108 ns: 1.00x slower                                           |
| unpickle_pure_python       | 230 us                                                 | 231 us: 1.00x slower                                           |
| asyncio_tcp_ssl            | 1.78 sec                                               | 1.79 sec: 1.01x slower                                         |
| richards_super             | 51.9 ms                                                | 52.3 ms: 1.01x slower                                          |
| xml_etree_parse            | 159 ms                                                 | 161 ms: 1.01x slower                                           |
| async_generators           | 459 ms                                                 | 465 ms: 1.01x slower                                           |
| create_gc_cycles           | 1.45 ms                                                | 1.47 ms: 1.01x slower                                          |
| pprint_safe_repr           | 765 ms                                                 | 775 ms: 1.01x slower                                           |
| sqlglot_optimize           | 54.8 ms                                                | 55.8 ms: 1.02x slower                                          |
| float                      | 83.3 ms                                                | 84.9 ms: 1.02x slower                                          |
| scimark_monte_carlo        | 74.6 ms                                                | 76.4 ms: 1.02x slower                                          |
| pprint_pformat             | 1.55 sec                                               | 1.59 sec: 1.02x slower                                         |
| meteor_contest             | 110 ms                                                 | 112 ms: 1.02x slower                                           |
| async_tree_none_tg         | 447 ms                                                 | 460 ms: 1.03x slower                                           |
| async_tree_io              | 1.16 sec                                               | 1.20 sec: 1.03x slower                                         |
| richards                   | 46.0 ms                                                | 47.3 ms: 1.03x slower                                          |
| async_tree_cpu_io_mixed_tg | 725 ms                                                 | 746 ms: 1.03x slower                                           |
| unpack_sequence            | 54.2 ns                                                | 55.9 ns: 1.03x slower                                          |
| pycparser                  | 1.17 sec                                               | 1.21 sec: 1.03x slower                                         |
| async_tree_io_tg           | 1.19 sec                                               | 1.23 sec: 1.03x slower                                         |
| pickle                     | 11.2 us                                                | 11.6 us: 1.03x slower                                          |
| regex_effbot               | 3.57 ms                                                | 3.71 ms: 1.04x slower                                          |
| xml_etree_iterparse        | 106 ms                                                 | 110 ms: 1.05x slower                                           |
| fannkuch                   | 410 ms                                                 | 429 ms: 1.05x slower                                           |
| pidigits                   | 187 ms                                                 | 196 ms: 1.05x slower                                           |
| pyflate                    | 471 ms                                                 | 493 ms: 1.05x slower                                           |
| mako                       | 11.5 ms                                                | 12.2 ms: 1.06x slower                                          |
| regex_dna                  | 209 ms                                                 | 222 ms: 1.06x slower                                           |
| nqueens                    | 86.2 ms                                                | 91.8 ms: 1.07x slower                                          |
| nbody                      | 92.2 ms                                                | 98.4 ms: 1.07x slower                                          |
| go                         | 140 ms                                                 | 150 ms: 1.07x slower                                           |
| async_tree_memoization_tg  | 574 ms                                                 | 616 ms: 1.07x slower                                           |
| pickle_list                | 4.67 us                                                | 5.05 us: 1.08x slower                                          |
| pickle_dict                | 33.5 us                                                | 36.4 us: 1.09x slower                                          |
| mdp                        | 2.57 sec                                               | 2.80 sec: 1.09x slower                                         |
| python_startup             | 9.53 ms                                                | 10.4 ms: 1.10x slower                                          |
| deltablue                  | 3.71 ms                                                | 4.07 ms: 1.10x slower                                          |
| regex_v8                   | 22.7 ms                                                | 26.0 ms: 1.15x slower                                          |
| hexiom                     | 6.54 ms                                                | 7.52 ms: 1.15x slower                                          |
| telco                      | 7.18 ms                                                | 8.29 ms: 1.15x slower                                          |
| spectral_norm              | 115 ms                                                 | 138 ms: 1.20x slower                                           |
| coverage                   | 75.1 ms                                                | 93.9 ms: 1.25x slower                                          |
| python_startup_no_site     | 6.92 ms                                                | 9.11 ms: 1.32x slower                                          |
| mypy2                      | 351 ms                                                 | 861 ms: 2.45x slower                                           |
| Geometric mean             | (ref)                                                  | 1.02x slower                                                   |

Benchmark hidden because not significant (4): xml_etree_process, xml_etree_generate, json_dumps, asyncio_websockets
Ignored benchmarks (5) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 92.32% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
