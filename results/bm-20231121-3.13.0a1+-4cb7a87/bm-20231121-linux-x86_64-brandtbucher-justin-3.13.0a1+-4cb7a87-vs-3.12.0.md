
# Results vs. 3.12.0

- fork: brandtbucher
- ref: justin
- machine: linux-x86_64
- commit hash: 4cb7a87
- commit date: 2023-11-21
- overall geometric mean: 1.06x slower \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.02x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231121-linux-x86_64-brandtbucher-justin-3.13.0a1+-4cb7a87 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| 2to3           | 274 ms                                                 | 291 ms: 1.06x slower                                           |
| chameleon      | 7.41 ms                                                | 7.48 ms: 1.01x slower                                          |
| docutils       | 2.75 sec                                               | 2.73 sec: 1.01x faster                                         |
| tornado_http   | 101 ms                                                 | 99.8 ms: 1.01x faster                                          |
| Geometric mean | (ref)                                                  | 1.01x slower                                                   |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231121-linux-x86_64-brandtbucher-justin-3.13.0a1+-4cb7a87 |
|----------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| async_tree_none            | 475 ms                                                 | 459 ms: 1.04x faster                                           |
| async_tree_memoization     | 580 ms                                                 | 585 ms: 1.01x slower                                           |
| async_tree_cpu_io_mixed    | 724 ms                                                 | 737 ms: 1.02x slower                                           |
| async_tree_cpu_io_mixed_tg | 725 ms                                                 | 763 ms: 1.05x slower                                           |
| async_tree_io              | 1.16 sec                                               | 1.23 sec: 1.05x slower                                         |
| async_tree_none_tg         | 447 ms                                                 | 472 ms: 1.05x slower                                           |
| async_tree_io_tg           | 1.19 sec                                               | 1.26 sec: 1.06x slower                                         |
| async_tree_memoization_tg  | 574 ms                                                 | 622 ms: 1.08x slower                                           |
| Geometric mean             | (ref)                                                  | 1.04x slower                                                   |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231121-linux-x86_64-brandtbucher-justin-3.13.0a1+-4cb7a87 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| pidigits       | 187 ms                                                 | 189 ms: 1.01x slower                                           |
| float          | 83.3 ms                                                | 98.5 ms: 1.18x slower                                          |
| nbody          | 92.2 ms                                                | 128 ms: 1.39x slower                                           |
| Geometric mean | (ref)                                                  | 1.18x slower                                                   |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231121-linux-x86_64-brandtbucher-justin-3.13.0a1+-4cb7a87 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| regex_dna      | 209 ms                                                 | 217 ms: 1.04x slower                                           |
| regex_effbot   | 3.57 ms                                                | 3.72 ms: 1.04x slower                                          |
| regex_compile  | 148 ms                                                 | 162 ms: 1.09x slower                                           |
| regex_v8       | 22.7 ms                                                | 25.6 ms: 1.13x slower                                          |
| Geometric mean | (ref)                                                  | 1.08x slower                                                   |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231121-linux-x86_64-brandtbucher-justin-3.13.0a1+-4cb7a87 |
|----------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| unpickle             | 15.8 us                                                | 14.9 us: 1.06x faster                                          |
| pickle_pure_python   | 326 us                                                 | 308 us: 1.06x faster                                           |
| json_loads           | 28.4 us                                                | 28.2 us: 1.01x faster                                          |
| xml_etree_parse      | 159 ms                                                 | 159 ms: 1.00x faster                                           |
| json_dumps           | 10.6 ms                                                | 10.8 ms: 1.02x slower                                          |
| xml_etree_process    | 61.2 ms                                                | 63.0 ms: 1.03x slower                                          |
| unpickle_list        | 5.04 us                                                | 5.20 us: 1.03x slower                                          |
| pickle               | 11.2 us                                                | 11.6 us: 1.03x slower                                          |
| xml_etree_generate   | 88.7 ms                                                | 92.3 ms: 1.04x slower                                          |
| pickle_dict          | 33.5 us                                                | 34.9 us: 1.04x slower                                          |
| unpickle_pure_python | 230 us                                                 | 242 us: 1.06x slower                                           |
| xml_etree_iterparse  | 106 ms                                                 | 115 ms: 1.09x slower                                           |
| pickle_list          | 4.67 us                                                | 5.10 us: 1.09x slower                                          |
| tomli_loads          | 2.30 sec                                               | 2.73 sec: 1.19x slower                                         |
| Geometric mean       | (ref)                                                  | 1.03x slower                                                   |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231121-linux-x86_64-brandtbucher-justin-3.13.0a1+-4cb7a87 |
|------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| python_startup         | 9.53 ms                                                | 10.4 ms: 1.09x slower                                          |
| python_startup_no_site | 6.92 ms                                                | 9.03 ms: 1.31x slower                                          |
| Geometric mean         | (ref)                                                  | 1.19x slower                                                   |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231121-linux-x86_64-brandtbucher-justin-3.13.0a1+-4cb7a87 |
|-----------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| mako      | 11.5 ms                                                | 15.2 ms: 1.32x slower                                          |

All benchmarks:
===============

| Benchmark                  | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231121-linux-x86_64-brandtbucher-justin-3.13.0a1+-4cb7a87 |
|----------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| unpack_sequence            | 54.2 ns                                                | 42.0 ns: 1.29x faster                                          |
| typing_runtime_protocols   | 153 us                                                 | 123 us: 1.24x faster                                           |
| gc_traversal               | 4.28 ms                                                | 3.87 ms: 1.10x faster                                          |
| generators                 | 32.5 ms                                                | 29.7 ms: 1.09x faster                                          |
| unpickle                   | 15.8 us                                                | 14.9 us: 1.06x faster                                          |
| pickle_pure_python         | 326 us                                                 | 308 us: 1.06x faster                                           |
| logging_simple             | 6.38 us                                                | 6.09 us: 1.05x faster                                          |
| coroutines                 | 23.5 ms                                                | 22.4 ms: 1.05x faster                                          |
| logging_format             | 7.10 us                                                | 6.83 us: 1.04x faster                                          |
| async_tree_none            | 475 ms                                                 | 459 ms: 1.04x faster                                           |
| sympy_sum                  | 167 ms                                                 | 162 ms: 1.03x faster                                           |
| asyncio_tcp                | 506 ms                                                 | 494 ms: 1.02x faster                                           |
| scimark_sor                | 129 ms                                                 | 127 ms: 1.02x faster                                           |
| deepcopy_reduce            | 3.23 us                                                | 3.18 us: 1.02x faster                                          |
| tornado_http               | 101 ms                                                 | 99.8 ms: 1.01x faster                                          |
| docutils                   | 2.75 sec                                               | 2.73 sec: 1.01x faster                                         |
| deepcopy                   | 363 us                                                 | 361 us: 1.01x faster                                           |
| scimark_lu                 | 120 ms                                                 | 120 ms: 1.01x faster                                           |
| json_loads                 | 28.4 us                                                | 28.2 us: 1.01x faster                                          |
| async_generators           | 459 ms                                                 | 457 ms: 1.01x faster                                           |
| xml_etree_parse            | 159 ms                                                 | 159 ms: 1.00x faster                                           |
| dulwich_log                | 68.7 ms                                                | 69.1 ms: 1.01x slower                                          |
| pidigits                   | 187 ms                                                 | 189 ms: 1.01x slower                                           |
| chameleon                  | 7.41 ms                                                | 7.48 ms: 1.01x slower                                          |
| async_tree_memoization     | 580 ms                                                 | 585 ms: 1.01x slower                                           |
| logging_silent             | 108 ns                                                 | 109 ns: 1.01x slower                                           |
| asyncio_tcp_ssl            | 1.78 sec                                               | 1.81 sec: 1.01x slower                                         |
| mypy2                      | 351 ms                                                 | 356 ms: 1.02x slower                                           |
| async_tree_cpu_io_mixed    | 724 ms                                                 | 737 ms: 1.02x slower                                           |
| json_dumps                 | 10.6 ms                                                | 10.8 ms: 1.02x slower                                          |
| bench_thread_pool          | 845 us                                                 | 860 us: 1.02x slower                                           |
| sympy_integrate            | 21.2 ms                                                | 21.6 ms: 1.02x slower                                          |
| create_gc_cycles           | 1.45 ms                                                | 1.48 ms: 1.02x slower                                          |
| sqlite_synth               | 2.83 us                                                | 2.89 us: 1.02x slower                                          |
| sqlglot_transpile          | 1.68 ms                                                | 1.71 ms: 1.02x slower                                          |
| sqlglot_normalize          | 112 ms                                                 | 115 ms: 1.03x slower                                           |
| sqlglot_parse              | 1.35 ms                                                | 1.39 ms: 1.03x slower                                          |
| xml_etree_process          | 61.2 ms                                                | 63.0 ms: 1.03x slower                                          |
| unpickle_list              | 5.04 us                                                | 5.20 us: 1.03x slower                                          |
| raytrace                   | 308 ms                                                 | 318 ms: 1.03x slower                                           |
| pickle                     | 11.2 us                                                | 11.6 us: 1.03x slower                                          |
| sympy_expand               | 476 ms                                                 | 492 ms: 1.03x slower                                           |
| deepcopy_memo              | 39.7 us                                                | 41.1 us: 1.03x slower                                          |
| xml_etree_generate         | 88.7 ms                                                | 92.3 ms: 1.04x slower                                          |
| pickle_dict                | 33.5 us                                                | 34.9 us: 1.04x slower                                          |
| regex_dna                  | 209 ms                                                 | 217 ms: 1.04x slower                                           |
| regex_effbot               | 3.57 ms                                                | 3.72 ms: 1.04x slower                                          |
| pycparser                  | 1.17 sec                                               | 1.22 sec: 1.05x slower                                         |
| async_tree_cpu_io_mixed_tg | 725 ms                                                 | 763 ms: 1.05x slower                                           |
| async_tree_io              | 1.16 sec                                               | 1.23 sec: 1.05x slower                                         |
| async_tree_none_tg         | 447 ms                                                 | 472 ms: 1.05x slower                                           |
| unpickle_pure_python       | 230 us                                                 | 242 us: 1.06x slower                                           |
| async_tree_io_tg           | 1.19 sec                                               | 1.26 sec: 1.06x slower                                         |
| crypto_pyaes               | 83.6 ms                                                | 88.4 ms: 1.06x slower                                          |
| 2to3                       | 274 ms                                                 | 291 ms: 1.06x slower                                           |
| richards_super             | 51.9 ms                                                | 55.3 ms: 1.07x slower                                          |
| sqlglot_optimize           | 54.8 ms                                                | 58.5 ms: 1.07x slower                                          |
| meteor_contest             | 110 ms                                                 | 118 ms: 1.08x slower                                           |
| pprint_safe_repr           | 765 ms                                                 | 824 ms: 1.08x slower                                           |
| async_tree_memoization_tg  | 574 ms                                                 | 622 ms: 1.08x slower                                           |
| xml_etree_iterparse        | 106 ms                                                 | 115 ms: 1.09x slower                                           |
| richards                   | 46.0 ms                                                | 50.1 ms: 1.09x slower                                          |
| python_startup             | 9.53 ms                                                | 10.4 ms: 1.09x slower                                          |
| pickle_list                | 4.67 us                                                | 5.10 us: 1.09x slower                                          |
| regex_compile              | 148 ms                                                 | 162 ms: 1.09x slower                                           |
| comprehensions             | 20.9 us                                                | 23.1 us: 1.10x slower                                          |
| pprint_pformat             | 1.55 sec                                               | 1.72 sec: 1.11x slower                                         |
| mdp                        | 2.57 sec                                               | 2.88 sec: 1.12x slower                                         |
| regex_v8                   | 22.7 ms                                                | 25.6 ms: 1.13x slower                                          |
| fannkuch                   | 410 ms                                                 | 471 ms: 1.15x slower                                           |
| scimark_monte_carlo        | 74.6 ms                                                | 86.1 ms: 1.15x slower                                          |
| chaos                      | 67.5 ms                                                | 78.0 ms: 1.16x slower                                          |
| pyflate                    | 471 ms                                                 | 547 ms: 1.16x slower                                           |
| nqueens                    | 86.2 ms                                                | 100 ms: 1.16x slower                                           |
| go                         | 140 ms                                                 | 165 ms: 1.17x slower                                           |
| float                      | 83.3 ms                                                | 98.5 ms: 1.18x slower                                          |
| tomli_loads                | 2.30 sec                                               | 2.73 sec: 1.19x slower                                         |
| telco                      | 7.18 ms                                                | 8.66 ms: 1.21x slower                                          |
| scimark_sparse_mat_mult    | 5.33 ms                                                | 6.55 ms: 1.23x slower                                          |
| scimark_fft                | 381 ms                                                 | 475 ms: 1.25x slower                                           |
| coverage                   | 75.1 ms                                                | 95.2 ms: 1.27x slower                                          |
| python_startup_no_site     | 6.92 ms                                                | 9.03 ms: 1.31x slower                                          |
| mako                       | 11.5 ms                                                | 15.2 ms: 1.32x slower                                          |
| deltablue                  | 3.71 ms                                                | 5.12 ms: 1.38x slower                                          |
| nbody                      | 92.2 ms                                                | 128 ms: 1.39x slower                                           |
| hexiom                     | 6.54 ms                                                | 9.17 ms: 1.40x slower                                          |
| spectral_norm              | 115 ms                                                 | 162 ms: 1.41x slower                                           |
| Geometric mean             | (ref)                                                  | 1.06x slower                                                   |

Benchmark hidden because not significant (6): asyncio_websockets, bench_mp_pool, pathlib, sympy_str, json, dask
Ignored benchmarks (5) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.03x
- 95% likely to have a slowdown of 1.03x
- 99% likely to have a slowdown of 1.02x
