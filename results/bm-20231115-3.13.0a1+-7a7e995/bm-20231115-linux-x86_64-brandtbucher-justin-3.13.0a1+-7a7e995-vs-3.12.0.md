
# Results vs. 3.12.0

- fork: brandtbucher
- ref: justin
- machine: linux-x86_64
- commit hash: 7a7e995
- commit date: 2023-11-15
- overall geometric mean: 1.00x slower \*
- HPT reliability: 70.75%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231115-linux-x86_64-brandtbucher-justin-3.13.0a1+-7a7e995 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| 2to3           | 274 ms                                                 | 272 ms: 1.01x faster                                           |
| chameleon      | 7.41 ms                                                | 7.34 ms: 1.01x faster                                          |
| docutils       | 2.75 sec                                               | 2.65 sec: 1.04x faster                                         |
| tornado_http   | 101 ms                                                 | 96.5 ms: 1.04x faster                                          |
| Geometric mean | (ref)                                                  | 1.02x faster                                                   |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231115-linux-x86_64-brandtbucher-justin-3.13.0a1+-7a7e995 |
|----------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| async_tree_none            | 475 ms                                                 | 442 ms: 1.08x faster                                           |
| async_tree_memoization     | 580 ms                                                 | 569 ms: 1.02x faster                                           |
| async_tree_cpu_io_mixed    | 724 ms                                                 | 715 ms: 1.01x faster                                           |
| async_tree_cpu_io_mixed_tg | 725 ms                                                 | 744 ms: 1.03x slower                                           |
| async_tree_none_tg         | 447 ms                                                 | 461 ms: 1.03x slower                                           |
| async_tree_io              | 1.16 sec                                               | 1.20 sec: 1.03x slower                                         |
| async_tree_io_tg           | 1.19 sec                                               | 1.23 sec: 1.04x slower                                         |
| async_tree_memoization_tg  | 574 ms                                                 | 603 ms: 1.05x slower                                           |
| Geometric mean             | (ref)                                                  | 1.01x slower                                                   |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231115-linux-x86_64-brandtbucher-justin-3.13.0a1+-7a7e995 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| float          | 83.3 ms                                                | 86.5 ms: 1.04x slower                                          |
| pidigits       | 187 ms                                                 | 195 ms: 1.04x slower                                           |
| nbody          | 92.2 ms                                                | 97.3 ms: 1.06x slower                                          |
| Geometric mean | (ref)                                                  | 1.05x slower                                                   |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231115-linux-x86_64-brandtbucher-justin-3.13.0a1+-7a7e995 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| regex_compile  | 148 ms                                                 | 141 ms: 1.05x faster                                           |
| regex_dna      | 209 ms                                                 | 214 ms: 1.03x slower                                           |
| regex_v8       | 22.7 ms                                                | 25.7 ms: 1.14x slower                                          |
| Geometric mean | (ref)                                                  | 1.03x slower                                                   |

Benchmark hidden because not significant (1): regex_effbot

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231115-linux-x86_64-brandtbucher-justin-3.13.0a1+-7a7e995 |
|----------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| pickle_pure_python   | 326 us                                                 | 305 us: 1.07x faster                                           |
| unpickle             | 15.8 us                                                | 14.9 us: 1.05x faster                                          |
| tomli_loads          | 2.30 sec                                               | 2.23 sec: 1.03x faster                                         |
| xml_etree_process    | 61.2 ms                                                | 60.0 ms: 1.02x faster                                          |
| xml_etree_generate   | 88.7 ms                                                | 87.8 ms: 1.01x faster                                          |
| pickle               | 11.2 us                                                | 11.1 us: 1.01x faster                                          |
| json_loads           | 28.4 us                                                | 28.2 us: 1.01x faster                                          |
| xml_etree_parse      | 159 ms                                                 | 158 ms: 1.01x faster                                           |
| unpickle_pure_python | 230 us                                                 | 231 us: 1.00x slower                                           |
| pickle_dict          | 33.5 us                                                | 34.2 us: 1.02x slower                                          |
| xml_etree_iterparse  | 106 ms                                                 | 108 ms: 1.02x slower                                           |
| pickle_list          | 4.67 us                                                | 4.90 us: 1.05x slower                                          |
| unpickle_list        | 5.04 us                                                | 5.36 us: 1.06x slower                                          |
| Geometric mean       | (ref)                                                  | 1.00x faster                                                   |

Benchmark hidden because not significant (1): json_dumps

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231115-linux-x86_64-brandtbucher-justin-3.13.0a1+-7a7e995 |
|------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| python_startup         | 9.53 ms                                                | 10.4 ms: 1.10x slower                                          |
| python_startup_no_site | 6.92 ms                                                | 9.10 ms: 1.32x slower                                          |
| Geometric mean         | (ref)                                                  | 1.20x slower                                                   |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231115-linux-x86_64-brandtbucher-justin-3.13.0a1+-7a7e995 |
|-----------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| mako      | 11.5 ms                                                | 12.3 ms: 1.07x slower                                          |

All benchmarks:
===============

| Benchmark                  | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231115-linux-x86_64-brandtbucher-justin-3.13.0a1+-7a7e995 |
|----------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| typing_runtime_protocols   | 153 us                                                 | 122 us: 1.26x faster                                           |
| gc_traversal               | 4.28 ms                                                | 3.82 ms: 1.12x faster                                          |
| generators                 | 32.5 ms                                                | 29.2 ms: 1.11x faster                                          |
| sympy_sum                  | 167 ms                                                 | 150 ms: 1.11x faster                                           |
| logging_format             | 7.10 us                                                | 6.46 us: 1.10x faster                                          |
| logging_simple             | 6.38 us                                                | 5.85 us: 1.09x faster                                          |
| unpack_sequence            | 54.2 ns                                                | 49.9 ns: 1.09x faster                                          |
| comprehensions             | 20.9 us                                                | 19.3 us: 1.08x faster                                          |
| crypto_pyaes               | 83.6 ms                                                | 77.1 ms: 1.08x faster                                          |
| sympy_str                  | 296 ms                                                 | 273 ms: 1.08x faster                                           |
| async_tree_none            | 475 ms                                                 | 442 ms: 1.08x faster                                           |
| coroutines                 | 23.5 ms                                                | 21.9 ms: 1.07x faster                                          |
| raytrace                   | 308 ms                                                 | 287 ms: 1.07x faster                                           |
| pickle_pure_python         | 326 us                                                 | 305 us: 1.07x faster                                           |
| unpickle                   | 15.8 us                                                | 14.9 us: 1.05x faster                                          |
| regex_compile              | 148 ms                                                 | 141 ms: 1.05x faster                                           |
| sqlglot_normalize          | 112 ms                                                 | 107 ms: 1.05x faster                                           |
| scimark_sor                | 129 ms                                                 | 124 ms: 1.04x faster                                           |
| tornado_http               | 101 ms                                                 | 96.5 ms: 1.04x faster                                          |
| spectral_norm              | 115 ms                                                 | 110 ms: 1.04x faster                                           |
| sqlglot_parse              | 1.35 ms                                                | 1.30 ms: 1.04x faster                                          |
| docutils                   | 2.75 sec                                               | 2.65 sec: 1.04x faster                                         |
| sqlglot_transpile          | 1.68 ms                                                | 1.62 ms: 1.03x faster                                          |
| sympy_integrate            | 21.2 ms                                                | 20.5 ms: 1.03x faster                                          |
| dulwich_log                | 68.7 ms                                                | 66.6 ms: 1.03x faster                                          |
| tomli_loads                | 2.30 sec                                               | 2.23 sec: 1.03x faster                                         |
| deepcopy_reduce            | 3.23 us                                                | 3.13 us: 1.03x faster                                          |
| deepcopy                   | 363 us                                                 | 353 us: 1.03x faster                                           |
| sympy_expand               | 476 ms                                                 | 463 ms: 1.03x faster                                           |
| chaos                      | 67.5 ms                                                | 65.8 ms: 1.03x faster                                          |
| scimark_lu                 | 120 ms                                                 | 118 ms: 1.02x faster                                           |
| pathlib                    | 18.9 ms                                                | 18.5 ms: 1.02x faster                                          |
| xml_etree_process          | 61.2 ms                                                | 60.0 ms: 1.02x faster                                          |
| asyncio_tcp                | 506 ms                                                 | 496 ms: 1.02x faster                                           |
| async_tree_memoization     | 580 ms                                                 | 569 ms: 1.02x faster                                           |
| async_tree_cpu_io_mixed    | 724 ms                                                 | 715 ms: 1.01x faster                                           |
| dask                       | 369 ms                                                 | 364 ms: 1.01x faster                                           |
| sqlglot_optimize           | 54.8 ms                                                | 54.1 ms: 1.01x faster                                          |
| sqlite_synth               | 2.83 us                                                | 2.80 us: 1.01x faster                                          |
| xml_etree_generate         | 88.7 ms                                                | 87.8 ms: 1.01x faster                                          |
| pickle                     | 11.2 us                                                | 11.1 us: 1.01x faster                                          |
| chameleon                  | 7.41 ms                                                | 7.34 ms: 1.01x faster                                          |
| 2to3                       | 274 ms                                                 | 272 ms: 1.01x faster                                           |
| scimark_monte_carlo        | 74.6 ms                                                | 74.0 ms: 1.01x faster                                          |
| json                       | 5.22 ms                                                | 5.18 ms: 1.01x faster                                          |
| json_loads                 | 28.4 us                                                | 28.2 us: 1.01x faster                                          |
| xml_etree_parse            | 159 ms                                                 | 158 ms: 1.01x faster                                           |
| logging_silent             | 108 ns                                                 | 107 ns: 1.00x faster                                           |
| meteor_contest             | 110 ms                                                 | 110 ms: 1.00x slower                                           |
| unpickle_pure_python       | 230 us                                                 | 231 us: 1.00x slower                                           |
| scimark_fft                | 381 ms                                                 | 383 ms: 1.01x slower                                           |
| deepcopy_memo              | 39.7 us                                                | 40.1 us: 1.01x slower                                          |
| asyncio_tcp_ssl            | 1.78 sec                                               | 1.80 sec: 1.01x slower                                         |
| richards_super             | 51.9 ms                                                | 52.8 ms: 1.02x slower                                          |
| richards                   | 46.0 ms                                                | 46.9 ms: 1.02x slower                                          |
| pickle_dict                | 33.5 us                                                | 34.2 us: 1.02x slower                                          |
| scimark_sparse_mat_mult    | 5.33 ms                                                | 5.45 ms: 1.02x slower                                          |
| mdp                        | 2.57 sec                                               | 2.63 sec: 1.02x slower                                         |
| create_gc_cycles           | 1.45 ms                                                | 1.48 ms: 1.02x slower                                          |
| xml_etree_iterparse        | 106 ms                                                 | 108 ms: 1.02x slower                                           |
| async_tree_cpu_io_mixed_tg | 725 ms                                                 | 744 ms: 1.03x slower                                           |
| regex_dna                  | 209 ms                                                 | 214 ms: 1.03x slower                                           |
| async_tree_none_tg         | 447 ms                                                 | 461 ms: 1.03x slower                                           |
| async_tree_io              | 1.16 sec                                               | 1.20 sec: 1.03x slower                                         |
| pycparser                  | 1.17 sec                                               | 1.21 sec: 1.03x slower                                         |
| async_tree_io_tg           | 1.19 sec                                               | 1.23 sec: 1.04x slower                                         |
| float                      | 83.3 ms                                                | 86.5 ms: 1.04x slower                                          |
| pidigits                   | 187 ms                                                 | 195 ms: 1.04x slower                                           |
| pprint_safe_repr           | 765 ms                                                 | 798 ms: 1.04x slower                                           |
| pprint_pformat             | 1.55 sec                                               | 1.62 sec: 1.04x slower                                         |
| pickle_list                | 4.67 us                                                | 4.90 us: 1.05x slower                                          |
| async_tree_memoization_tg  | 574 ms                                                 | 603 ms: 1.05x slower                                           |
| fannkuch                   | 410 ms                                                 | 430 ms: 1.05x slower                                           |
| nqueens                    | 86.2 ms                                                | 90.9 ms: 1.05x slower                                          |
| nbody                      | 92.2 ms                                                | 97.3 ms: 1.06x slower                                          |
| unpickle_list              | 5.04 us                                                | 5.36 us: 1.06x slower                                          |
| go                         | 140 ms                                                 | 149 ms: 1.06x slower                                           |
| mako                       | 11.5 ms                                                | 12.3 ms: 1.07x slower                                          |
| deltablue                  | 3.71 ms                                                | 4.00 ms: 1.08x slower                                          |
| pyflate                    | 471 ms                                                 | 513 ms: 1.09x slower                                           |
| python_startup             | 9.53 ms                                                | 10.4 ms: 1.10x slower                                          |
| regex_v8                   | 22.7 ms                                                | 25.7 ms: 1.14x slower                                          |
| hexiom                     | 6.54 ms                                                | 7.59 ms: 1.16x slower                                          |
| telco                      | 7.18 ms                                                | 8.44 ms: 1.18x slower                                          |
| coverage                   | 75.1 ms                                                | 94.7 ms: 1.26x slower                                          |
| python_startup_no_site     | 6.92 ms                                                | 9.10 ms: 1.32x slower                                          |
| Geometric mean             | (ref)                                                  | 1.00x slower                                                   |

Benchmark hidden because not significant (7): mypy2, regex_effbot, asyncio_websockets, bench_mp_pool, bench_thread_pool, json_dumps, async_generators
Ignored benchmarks (5) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 70.75% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
