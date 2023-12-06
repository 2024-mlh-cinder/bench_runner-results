
# Results vs. 3.12.0

- fork: brandtbucher
- ref: justin
- machine: linux-x86_64
- commit hash: 241ce0f
- commit date: 2023-11-11
- overall geometric mean: 1.01x slower \*
- HPT reliability: 91.72%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231111-linux-x86_64-brandtbucher-justin-3.13.0a1+-241ce0f |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| 2to3           | 274 ms                                                 | 275 ms: 1.00x slower                                           |
| chameleon      | 7.41 ms                                                | 7.37 ms: 1.00x faster                                          |
| docutils       | 2.75 sec                                               | 2.64 sec: 1.04x faster                                         |
| tornado_http   | 101 ms                                                 | 96.8 ms: 1.04x faster                                          |
| Geometric mean | (ref)                                                  | 1.02x faster                                                   |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231111-linux-x86_64-brandtbucher-justin-3.13.0a1+-241ce0f |
|----------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| async_tree_none            | 475 ms                                                 | 446 ms: 1.07x faster                                           |
| async_tree_none_tg         | 447 ms                                                 | 460 ms: 1.03x slower                                           |
| async_tree_io              | 1.16 sec                                               | 1.20 sec: 1.03x slower                                         |
| async_tree_cpu_io_mixed_tg | 725 ms                                                 | 757 ms: 1.04x slower                                           |
| async_tree_io_tg           | 1.19 sec                                               | 1.24 sec: 1.05x slower                                         |
| async_tree_memoization_tg  | 574 ms                                                 | 606 ms: 1.06x slower                                           |
| Geometric mean             | (ref)                                                  | 1.02x slower                                                   |

Benchmark hidden because not significant (2): async_tree_memoization, async_tree_cpu_io_mixed

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231111-linux-x86_64-brandtbucher-justin-3.13.0a1+-241ce0f |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| pidigits       | 187 ms                                                 | 188 ms: 1.01x slower                                           |
| float          | 83.3 ms                                                | 88.9 ms: 1.07x slower                                          |
| nbody          | 92.2 ms                                                | 101 ms: 1.10x slower                                           |
| Geometric mean | (ref)                                                  | 1.06x slower                                                   |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231111-linux-x86_64-brandtbucher-justin-3.13.0a1+-241ce0f |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| regex_compile  | 148 ms                                                 | 143 ms: 1.03x faster                                           |
| regex_effbot   | 3.57 ms                                                | 3.62 ms: 1.01x slower                                          |
| regex_dna      | 209 ms                                                 | 212 ms: 1.02x slower                                           |
| regex_v8       | 22.7 ms                                                | 25.6 ms: 1.13x slower                                          |
| Geometric mean | (ref)                                                  | 1.03x slower                                                   |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231111-linux-x86_64-brandtbucher-justin-3.13.0a1+-241ce0f |
|----------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| pickle_pure_python   | 326 us                                                 | 309 us: 1.06x faster                                           |
| unpickle             | 15.8 us                                                | 15.1 us: 1.04x faster                                          |
| xml_etree_process    | 61.2 ms                                                | 59.9 ms: 1.02x faster                                          |
| json_loads           | 28.4 us                                                | 27.8 us: 1.02x faster                                          |
| pickle_dict          | 33.5 us                                                | 32.9 us: 1.02x faster                                          |
| xml_etree_generate   | 88.7 ms                                                | 87.4 ms: 1.02x faster                                          |
| json_dumps           | 10.6 ms                                                | 10.5 ms: 1.01x faster                                          |
| unpickle_pure_python | 230 us                                                 | 231 us: 1.01x slower                                           |
| pickle               | 11.2 us                                                | 11.4 us: 1.02x slower                                          |
| pickle_list          | 4.67 us                                                | 4.80 us: 1.03x slower                                          |
| xml_etree_iterparse  | 106 ms                                                 | 110 ms: 1.04x slower                                           |
| unpickle_list        | 5.04 us                                                | 5.68 us: 1.13x slower                                          |
| Geometric mean       | (ref)                                                  | 1.00x slower                                                   |

Benchmark hidden because not significant (2): tomli_loads, xml_etree_parse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231111-linux-x86_64-brandtbucher-justin-3.13.0a1+-241ce0f |
|------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| python_startup         | 9.53 ms                                                | 10.4 ms: 1.09x slower                                          |
| python_startup_no_site | 6.92 ms                                                | 9.11 ms: 1.32x slower                                          |
| Geometric mean         | (ref)                                                  | 1.20x slower                                                   |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231111-linux-x86_64-brandtbucher-justin-3.13.0a1+-241ce0f |
|-----------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| mako      | 11.5 ms                                                | 12.5 ms: 1.08x slower                                          |

All benchmarks:
===============

| Benchmark                  | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231111-linux-x86_64-brandtbucher-justin-3.13.0a1+-241ce0f |
|----------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| typing_runtime_protocols   | 153 us                                                 | 121 us: 1.26x faster                                           |
| gc_traversal               | 4.28 ms                                                | 3.82 ms: 1.12x faster                                          |
| generators                 | 32.5 ms                                                | 29.1 ms: 1.11x faster                                          |
| sympy_sum                  | 167 ms                                                 | 151 ms: 1.10x faster                                           |
| logging_format             | 7.10 us                                                | 6.53 us: 1.09x faster                                          |
| sympy_str                  | 296 ms                                                 | 274 ms: 1.08x faster                                           |
| logging_simple             | 6.38 us                                                | 5.95 us: 1.07x faster                                          |
| raytrace                   | 308 ms                                                 | 288 ms: 1.07x faster                                           |
| async_tree_none            | 475 ms                                                 | 446 ms: 1.07x faster                                           |
| crypto_pyaes               | 83.6 ms                                                | 78.5 ms: 1.06x faster                                          |
| pickle_pure_python         | 326 us                                                 | 309 us: 1.06x faster                                           |
| coroutines                 | 23.5 ms                                                | 22.4 ms: 1.05x faster                                          |
| sqlglot_normalize          | 112 ms                                                 | 107 ms: 1.05x faster                                           |
| unpickle                   | 15.8 us                                                | 15.1 us: 1.04x faster                                          |
| docutils                   | 2.75 sec                                               | 2.64 sec: 1.04x faster                                         |
| asyncio_tcp                | 506 ms                                                 | 486 ms: 1.04x faster                                           |
| tornado_http               | 101 ms                                                 | 96.8 ms: 1.04x faster                                          |
| deepcopy                   | 363 us                                                 | 349 us: 1.04x faster                                           |
| deepcopy_reduce            | 3.23 us                                                | 3.11 us: 1.04x faster                                          |
| sqlglot_parse              | 1.35 ms                                                | 1.31 ms: 1.03x faster                                          |
| sympy_expand               | 476 ms                                                 | 460 ms: 1.03x faster                                           |
| regex_compile              | 148 ms                                                 | 143 ms: 1.03x faster                                           |
| sqlglot_transpile          | 1.68 ms                                                | 1.63 ms: 1.03x faster                                          |
| sympy_integrate            | 21.2 ms                                                | 20.6 ms: 1.03x faster                                          |
| dulwich_log                | 68.7 ms                                                | 66.9 ms: 1.03x faster                                          |
| logging_silent             | 108 ns                                                 | 105 ns: 1.03x faster                                           |
| scimark_lu                 | 120 ms                                                 | 118 ms: 1.02x faster                                           |
| xml_etree_process          | 61.2 ms                                                | 59.9 ms: 1.02x faster                                          |
| json_loads                 | 28.4 us                                                | 27.8 us: 1.02x faster                                          |
| pickle_dict                | 33.5 us                                                | 32.9 us: 1.02x faster                                          |
| xml_etree_generate         | 88.7 ms                                                | 87.4 ms: 1.02x faster                                          |
| chaos                      | 67.5 ms                                                | 66.5 ms: 1.02x faster                                          |
| spectral_norm              | 115 ms                                                 | 113 ms: 1.01x faster                                           |
| sqlglot_optimize           | 54.8 ms                                                | 54.0 ms: 1.01x faster                                          |
| sqlite_synth               | 2.83 us                                                | 2.80 us: 1.01x faster                                          |
| deepcopy_memo              | 39.7 us                                                | 39.3 us: 1.01x faster                                          |
| json_dumps                 | 10.6 ms                                                | 10.5 ms: 1.01x faster                                          |
| json                       | 5.22 ms                                                | 5.18 ms: 1.01x faster                                          |
| mypy2                      | 351 ms                                                 | 349 ms: 1.01x faster                                           |
| chameleon                  | 7.41 ms                                                | 7.37 ms: 1.00x faster                                          |
| 2to3                       | 274 ms                                                 | 275 ms: 1.00x slower                                           |
| bench_thread_pool          | 845 us                                                 | 848 us: 1.00x slower                                           |
| async_generators           | 459 ms                                                 | 461 ms: 1.00x slower                                           |
| scimark_fft                | 381 ms                                                 | 383 ms: 1.01x slower                                           |
| pprint_safe_repr           | 765 ms                                                 | 769 ms: 1.01x slower                                           |
| unpickle_pure_python       | 230 us                                                 | 231 us: 1.01x slower                                           |
| pidigits                   | 187 ms                                                 | 188 ms: 1.01x slower                                           |
| pycparser                  | 1.17 sec                                               | 1.18 sec: 1.01x slower                                         |
| asyncio_tcp_ssl            | 1.78 sec                                               | 1.80 sec: 1.01x slower                                         |
| regex_effbot               | 3.57 ms                                                | 3.62 ms: 1.01x slower                                          |
| create_gc_cycles           | 1.45 ms                                                | 1.47 ms: 1.01x slower                                          |
| pprint_pformat             | 1.55 sec                                               | 1.57 sec: 1.01x slower                                         |
| regex_dna                  | 209 ms                                                 | 212 ms: 1.02x slower                                           |
| pickle                     | 11.2 us                                                | 11.4 us: 1.02x slower                                          |
| scimark_sor                | 129 ms                                                 | 131 ms: 1.02x slower                                           |
| pathlib                    | 18.9 ms                                                | 19.3 ms: 1.02x slower                                          |
| pickle_list                | 4.67 us                                                | 4.80 us: 1.03x slower                                          |
| async_tree_none_tg         | 447 ms                                                 | 460 ms: 1.03x slower                                           |
| async_tree_io              | 1.16 sec                                               | 1.20 sec: 1.03x slower                                         |
| richards_super             | 51.9 ms                                                | 53.8 ms: 1.04x slower                                          |
| xml_etree_iterparse        | 106 ms                                                 | 110 ms: 1.04x slower                                           |
| richards                   | 46.0 ms                                                | 47.8 ms: 1.04x slower                                          |
| meteor_contest             | 110 ms                                                 | 114 ms: 1.04x slower                                           |
| async_tree_cpu_io_mixed_tg | 725 ms                                                 | 757 ms: 1.04x slower                                           |
| async_tree_io_tg           | 1.19 sec                                               | 1.24 sec: 1.05x slower                                         |
| scimark_sparse_mat_mult    | 5.33 ms                                                | 5.61 ms: 1.05x slower                                          |
| async_tree_memoization_tg  | 574 ms                                                 | 606 ms: 1.06x slower                                           |
| float                      | 83.3 ms                                                | 88.9 ms: 1.07x slower                                          |
| mdp                        | 2.57 sec                                               | 2.77 sec: 1.08x slower                                         |
| mako                       | 11.5 ms                                                | 12.5 ms: 1.08x slower                                          |
| nqueens                    | 86.2 ms                                                | 93.5 ms: 1.09x slower                                          |
| go                         | 140 ms                                                 | 152 ms: 1.09x slower                                           |
| python_startup             | 9.53 ms                                                | 10.4 ms: 1.09x slower                                          |
| pyflate                    | 471 ms                                                 | 518 ms: 1.10x slower                                           |
| nbody                      | 92.2 ms                                                | 101 ms: 1.10x slower                                           |
| fannkuch                   | 410 ms                                                 | 453 ms: 1.11x slower                                           |
| deltablue                  | 3.71 ms                                                | 4.14 ms: 1.12x slower                                          |
| unpickle_list              | 5.04 us                                                | 5.68 us: 1.13x slower                                          |
| regex_v8                   | 22.7 ms                                                | 25.6 ms: 1.13x slower                                          |
| hexiom                     | 6.54 ms                                                | 7.80 ms: 1.19x slower                                          |
| telco                      | 7.18 ms                                                | 8.58 ms: 1.20x slower                                          |
| coverage                   | 75.1 ms                                                | 95.2 ms: 1.27x slower                                          |
| python_startup_no_site     | 6.92 ms                                                | 9.11 ms: 1.32x slower                                          |
| Geometric mean             | (ref)                                                  | 1.01x slower                                                   |

Benchmark hidden because not significant (9): async_tree_memoization, tomli_loads, scimark_monte_carlo, comprehensions, bench_mp_pool, unpack_sequence, asyncio_websockets, xml_etree_parse, async_tree_cpu_io_mixed
Ignored benchmarks (6) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, dask, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 91.72% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
