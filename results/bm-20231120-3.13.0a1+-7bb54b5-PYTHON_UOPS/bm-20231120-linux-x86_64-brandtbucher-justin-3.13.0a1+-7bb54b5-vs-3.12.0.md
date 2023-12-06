
# Results vs. 3.12.0

- fork: brandtbucher
- ref: justin
- machine: linux-x86_64
- commit hash: 7bb54b5
- commit date: 2023-11-20
- overall geometric mean: 1.00x slower \*
- HPT reliability: 83.43%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-linux-x86_64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| 2to3           | 274 ms                                                 | 273 ms: 1.00x faster                                           |
| chameleon      | 7.41 ms                                                | 7.11 ms: 1.04x faster                                          |
| docutils       | 2.75 sec                                               | 2.66 sec: 1.03x faster                                         |
| tornado_http   | 101 ms                                                 | 96.5 ms: 1.04x faster                                          |
| Geometric mean | (ref)                                                  | 1.03x faster                                                   |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-linux-x86_64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|----------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| async_tree_none            | 475 ms                                                 | 443 ms: 1.07x faster                                           |
| async_tree_memoization     | 580 ms                                                 | 571 ms: 1.02x faster                                           |
| async_tree_none_tg         | 447 ms                                                 | 458 ms: 1.02x slower                                           |
| async_tree_io              | 1.16 sec                                               | 1.20 sec: 1.03x slower                                         |
| async_tree_cpu_io_mixed_tg | 725 ms                                                 | 747 ms: 1.03x slower                                           |
| async_tree_io_tg           | 1.19 sec                                               | 1.23 sec: 1.04x slower                                         |
| async_tree_memoization_tg  | 574 ms                                                 | 602 ms: 1.05x slower                                           |
| Geometric mean             | (ref)                                                  | 1.01x slower                                                   |

Benchmark hidden because not significant (1): async_tree_cpu_io_mixed

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-linux-x86_64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| pidigits       | 187 ms                                                 | 188 ms: 1.00x slower                                           |
| float          | 83.3 ms                                                | 85.0 ms: 1.02x slower                                          |
| nbody          | 92.2 ms                                                | 100 ms: 1.09x slower                                           |
| Geometric mean | (ref)                                                  | 1.04x slower                                                   |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-linux-x86_64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| regex_compile  | 148 ms                                                 | 141 ms: 1.05x faster                                           |
| regex_effbot   | 3.57 ms                                                | 3.63 ms: 1.02x slower                                          |
| regex_dna      | 209 ms                                                 | 216 ms: 1.03x slower                                           |
| regex_v8       | 22.7 ms                                                | 24.3 ms: 1.07x slower                                          |
| Geometric mean | (ref)                                                  | 1.02x slower                                                   |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-linux-x86_64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|----------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| pickle_pure_python   | 326 us                                                 | 309 us: 1.06x faster                                           |
| tomli_loads          | 2.30 sec                                               | 2.21 sec: 1.04x faster                                         |
| unpickle             | 15.8 us                                                | 15.5 us: 1.02x faster                                          |
| xml_etree_process    | 61.2 ms                                                | 61.0 ms: 1.00x faster                                          |
| xml_etree_generate   | 88.7 ms                                                | 89.1 ms: 1.00x slower                                          |
| xml_etree_parse      | 159 ms                                                 | 160 ms: 1.01x slower                                           |
| unpickle_pure_python | 230 us                                                 | 232 us: 1.01x slower                                           |
| pickle_dict          | 33.5 us                                                | 34.0 us: 1.02x slower                                          |
| xml_etree_iterparse  | 106 ms                                                 | 110 ms: 1.04x slower                                           |
| unpickle_list        | 5.04 us                                                | 5.28 us: 1.05x slower                                          |
| pickle_list          | 4.67 us                                                | 4.89 us: 1.05x slower                                          |
| Geometric mean       | (ref)                                                  | 1.00x slower                                                   |

Benchmark hidden because not significant (3): json_loads, pickle, json_dumps

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-linux-x86_64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| python_startup         | 9.53 ms                                                | 10.4 ms: 1.10x slower                                          |
| python_startup_no_site | 6.92 ms                                                | 9.10 ms: 1.32x slower                                          |
| Geometric mean         | (ref)                                                  | 1.20x slower                                                   |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-linux-x86_64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|-----------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| mako      | 11.5 ms                                                | 12.4 ms: 1.08x slower                                          |

All benchmarks:
===============

| Benchmark                  | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-linux-x86_64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|----------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| typing_runtime_protocols   | 153 us                                                 | 120 us: 1.28x faster                                           |
| unpack_sequence            | 54.2 ns                                                | 46.9 ns: 1.16x faster                                          |
| logging_format             | 7.10 us                                                | 6.39 us: 1.11x faster                                          |
| logging_simple             | 6.38 us                                                | 5.80 us: 1.10x faster                                          |
| generators                 | 32.5 ms                                                | 29.8 ms: 1.09x faster                                          |
| comprehensions             | 20.9 us                                                | 19.3 us: 1.08x faster                                          |
| raytrace                   | 308 ms                                                 | 286 ms: 1.08x faster                                           |
| async_tree_none            | 475 ms                                                 | 443 ms: 1.07x faster                                           |
| coroutines                 | 23.5 ms                                                | 21.8 ms: 1.07x faster                                          |
| sympy_sum                  | 167 ms                                                 | 156 ms: 1.07x faster                                           |
| gc_traversal               | 4.28 ms                                                | 4.04 ms: 1.06x faster                                          |
| pickle_pure_python         | 326 us                                                 | 309 us: 1.06x faster                                           |
| crypto_pyaes               | 83.6 ms                                                | 79.4 ms: 1.05x faster                                          |
| deepcopy_reduce            | 3.23 us                                                | 3.07 us: 1.05x faster                                          |
| sympy_str                  | 296 ms                                                 | 282 ms: 1.05x faster                                           |
| regex_compile              | 148 ms                                                 | 141 ms: 1.05x faster                                           |
| tornado_http               | 101 ms                                                 | 96.5 ms: 1.04x faster                                          |
| tomli_loads                | 2.30 sec                                               | 2.21 sec: 1.04x faster                                         |
| chameleon                  | 7.41 ms                                                | 7.11 ms: 1.04x faster                                          |
| dulwich_log                | 68.7 ms                                                | 66.4 ms: 1.04x faster                                          |
| docutils                   | 2.75 sec                                               | 2.66 sec: 1.03x faster                                         |
| asyncio_tcp                | 506 ms                                                 | 489 ms: 1.03x faster                                           |
| deepcopy                   | 363 us                                                 | 353 us: 1.03x faster                                           |
| sqlglot_normalize          | 112 ms                                                 | 109 ms: 1.02x faster                                           |
| sympy_integrate            | 21.2 ms                                                | 20.8 ms: 1.02x faster                                          |
| scimark_sor                | 129 ms                                                 | 127 ms: 1.02x faster                                           |
| sqlglot_parse              | 1.35 ms                                                | 1.32 ms: 1.02x faster                                          |
| chaos                      | 67.5 ms                                                | 66.3 ms: 1.02x faster                                          |
| sqlglot_transpile          | 1.68 ms                                                | 1.65 ms: 1.02x faster                                          |
| sympy_expand               | 476 ms                                                 | 468 ms: 1.02x faster                                           |
| scimark_lu                 | 120 ms                                                 | 119 ms: 1.02x faster                                           |
| async_tree_memoization     | 580 ms                                                 | 571 ms: 1.02x faster                                           |
| unpickle                   | 15.8 us                                                | 15.5 us: 1.02x faster                                          |
| pathlib                    | 18.9 ms                                                | 18.6 ms: 1.02x faster                                          |
| pycparser                  | 1.17 sec                                               | 1.16 sec: 1.01x faster                                         |
| sqlite_synth               | 2.83 us                                                | 2.81 us: 1.01x faster                                          |
| json                       | 5.22 ms                                                | 5.19 ms: 1.01x faster                                          |
| scimark_sparse_mat_mult    | 5.33 ms                                                | 5.31 ms: 1.00x faster                                          |
| xml_etree_process          | 61.2 ms                                                | 61.0 ms: 1.00x faster                                          |
| 2to3                       | 274 ms                                                 | 273 ms: 1.00x faster                                           |
| pidigits                   | 187 ms                                                 | 188 ms: 1.00x slower                                           |
| scimark_fft                | 381 ms                                                 | 382 ms: 1.00x slower                                           |
| xml_etree_generate         | 88.7 ms                                                | 89.1 ms: 1.00x slower                                          |
| xml_etree_parse            | 159 ms                                                 | 160 ms: 1.01x slower                                           |
| scimark_monte_carlo        | 74.6 ms                                                | 75.3 ms: 1.01x slower                                          |
| create_gc_cycles           | 1.45 ms                                                | 1.46 ms: 1.01x slower                                          |
| async_generators           | 459 ms                                                 | 464 ms: 1.01x slower                                           |
| bench_thread_pool          | 845 us                                                 | 854 us: 1.01x slower                                           |
| meteor_contest             | 110 ms                                                 | 111 ms: 1.01x slower                                           |
| unpickle_pure_python       | 230 us                                                 | 232 us: 1.01x slower                                           |
| asyncio_tcp_ssl            | 1.78 sec                                               | 1.80 sec: 1.01x slower                                         |
| sqlglot_optimize           | 54.8 ms                                                | 55.6 ms: 1.01x slower                                          |
| pprint_pformat             | 1.55 sec                                               | 1.57 sec: 1.01x slower                                         |
| pickle_dict                | 33.5 us                                                | 34.0 us: 1.02x slower                                          |
| deepcopy_memo              | 39.7 us                                                | 40.4 us: 1.02x slower                                          |
| richards                   | 46.0 ms                                                | 46.8 ms: 1.02x slower                                          |
| regex_effbot               | 3.57 ms                                                | 3.63 ms: 1.02x slower                                          |
| float                      | 83.3 ms                                                | 85.0 ms: 1.02x slower                                          |
| async_tree_none_tg         | 447 ms                                                 | 458 ms: 1.02x slower                                           |
| logging_silent             | 108 ns                                                 | 110 ns: 1.03x slower                                           |
| async_tree_io              | 1.16 sec                                               | 1.20 sec: 1.03x slower                                         |
| async_tree_cpu_io_mixed_tg | 725 ms                                                 | 747 ms: 1.03x slower                                           |
| regex_dna                  | 209 ms                                                 | 216 ms: 1.03x slower                                           |
| async_tree_io_tg           | 1.19 sec                                               | 1.23 sec: 1.04x slower                                         |
| xml_etree_iterparse        | 106 ms                                                 | 110 ms: 1.04x slower                                           |
| mdp                        | 2.57 sec                                               | 2.68 sec: 1.04x slower                                         |
| unpickle_list              | 5.04 us                                                | 5.28 us: 1.05x slower                                          |
| pickle_list                | 4.67 us                                                | 4.89 us: 1.05x slower                                          |
| async_tree_memoization_tg  | 574 ms                                                 | 602 ms: 1.05x slower                                           |
| fannkuch                   | 410 ms                                                 | 434 ms: 1.06x slower                                           |
| pyflate                    | 471 ms                                                 | 502 ms: 1.07x slower                                           |
| regex_v8                   | 22.7 ms                                                | 24.3 ms: 1.07x slower                                          |
| go                         | 140 ms                                                 | 152 ms: 1.08x slower                                           |
| mako                       | 11.5 ms                                                | 12.4 ms: 1.08x slower                                          |
| nbody                      | 92.2 ms                                                | 100 ms: 1.09x slower                                           |
| nqueens                    | 86.2 ms                                                | 94.4 ms: 1.10x slower                                          |
| deltablue                  | 3.71 ms                                                | 4.06 ms: 1.10x slower                                          |
| python_startup             | 9.53 ms                                                | 10.4 ms: 1.10x slower                                          |
| telco                      | 7.18 ms                                                | 8.31 ms: 1.16x slower                                          |
| hexiom                     | 6.54 ms                                                | 7.60 ms: 1.16x slower                                          |
| spectral_norm              | 115 ms                                                 | 137 ms: 1.19x slower                                           |
| coverage                   | 75.1 ms                                                | 95.4 ms: 1.27x slower                                          |
| python_startup_no_site     | 6.92 ms                                                | 9.10 ms: 1.32x slower                                          |
| Geometric mean             | (ref)                                                  | 1.00x slower                                                   |

Benchmark hidden because not significant (10): async_tree_cpu_io_mixed, dask, json_loads, bench_mp_pool, richards_super, mypy2, pickle, asyncio_websockets, pprint_safe_repr, json_dumps
Ignored benchmarks (5) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 83.43% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
