
# Results vs. 3.12.0

- fork: python
- ref: 7e2308aaa29419eadeef
- machine: linux-x86_64
- commit hash: 7e2308a
- commit date: 2023-11-15
- overall geometric mean: 1.03x faster \*
- HPT reliability: 99.99%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231115-linux-x86_64-python-7e2308aaa29419eadeef-3.13.0a1+-7e2308a |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| 2to3           | 274 ms                                                 | 264 ms: 1.04x faster                                                   |
| chameleon      | 7.41 ms                                                | 6.98 ms: 1.06x faster                                                  |
| docutils       | 2.75 sec                                               | 2.61 sec: 1.05x faster                                                 |
| tornado_http   | 101 ms                                                 | 96.1 ms: 1.05x faster                                                  |
| Geometric mean | (ref)                                                  | 1.05x faster                                                           |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231115-linux-x86_64-python-7e2308aaa29419eadeef-3.13.0a1+-7e2308a |
|----------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| async_tree_none            | 475 ms                                                 | 434 ms: 1.10x faster                                                   |
| async_tree_memoization     | 580 ms                                                 | 563 ms: 1.03x faster                                                   |
| async_tree_cpu_io_mixed    | 724 ms                                                 | 713 ms: 1.02x faster                                                   |
| async_tree_none_tg         | 447 ms                                                 | 454 ms: 1.01x slower                                                   |
| async_tree_io              | 1.16 sec                                               | 1.19 sec: 1.03x slower                                                 |
| async_tree_cpu_io_mixed_tg | 725 ms                                                 | 745 ms: 1.03x slower                                                   |
| async_tree_io_tg           | 1.19 sec                                               | 1.23 sec: 1.03x slower                                                 |
| async_tree_memoization_tg  | 574 ms                                                 | 595 ms: 1.04x slower                                                   |
| Geometric mean             | (ref)                                                  | 1.00x faster                                                           |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231115-linux-x86_64-python-7e2308aaa29419eadeef-3.13.0a1+-7e2308a |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| float          | 83.3 ms                                                | 81.8 ms: 1.02x faster                                                  |
| nbody          | 92.2 ms                                                | 94.0 ms: 1.02x slower                                                  |
| pidigits       | 187 ms                                                 | 195 ms: 1.04x slower                                                   |
| Geometric mean | (ref)                                                  | 1.01x slower                                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231115-linux-x86_64-python-7e2308aaa29419eadeef-3.13.0a1+-7e2308a |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| regex_compile  | 148 ms                                                 | 135 ms: 1.09x faster                                                   |
| regex_dna      | 209 ms                                                 | 217 ms: 1.04x slower                                                   |
| regex_v8       | 22.7 ms                                                | 24.5 ms: 1.08x slower                                                  |
| Geometric mean | (ref)                                                  | 1.01x slower                                                           |

Benchmark hidden because not significant (1): regex_effbot

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231115-linux-x86_64-python-7e2308aaa29419eadeef-3.13.0a1+-7e2308a |
|----------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| tomli_loads          | 2.30 sec                                               | 2.13 sec: 1.08x faster                                                 |
| pickle_pure_python   | 326 us                                                 | 303 us: 1.07x faster                                                   |
| unpickle             | 15.8 us                                                | 15.0 us: 1.05x faster                                                  |
| unpickle_pure_python | 230 us                                                 | 219 us: 1.05x faster                                                   |
| xml_etree_process    | 61.2 ms                                                | 59.4 ms: 1.03x faster                                                  |
| xml_etree_generate   | 88.7 ms                                                | 86.4 ms: 1.03x faster                                                  |
| json_loads           | 28.4 us                                                | 27.8 us: 1.02x faster                                                  |
| xml_etree_parse      | 159 ms                                                 | 157 ms: 1.01x faster                                                   |
| json_dumps           | 10.6 ms                                                | 10.5 ms: 1.01x faster                                                  |
| xml_etree_iterparse  | 106 ms                                                 | 105 ms: 1.01x faster                                                   |
| unpickle_list        | 5.04 us                                                | 5.06 us: 1.00x slower                                                  |
| pickle_dict          | 33.5 us                                                | 34.2 us: 1.02x slower                                                  |
| pickle               | 11.2 us                                                | 11.7 us: 1.04x slower                                                  |
| pickle_list          | 4.67 us                                                | 5.09 us: 1.09x slower                                                  |
| Geometric mean       | (ref)                                                  | 1.01x faster                                                           |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231115-linux-x86_64-python-7e2308aaa29419eadeef-3.13.0a1+-7e2308a |
|------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| python_startup         | 9.53 ms                                                | 10.4 ms: 1.09x slower                                                  |
| python_startup_no_site | 6.92 ms                                                | 9.02 ms: 1.30x slower                                                  |
| Geometric mean         | (ref)                                                  | 1.19x slower                                                           |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231115-linux-x86_64-python-7e2308aaa29419eadeef-3.13.0a1+-7e2308a |
|-----------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| mako      | 11.5 ms                                                | 11.5 ms: 1.00x faster                                                  |

All benchmarks:
===============

| Benchmark                  | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231115-linux-x86_64-python-7e2308aaa29419eadeef-3.13.0a1+-7e2308a |
|----------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| typing_runtime_protocols   | 153 us                                                 | 116 us: 1.32x faster                                                   |
| comprehensions             | 20.9 us                                                | 16.8 us: 1.24x faster                                                  |
| crypto_pyaes               | 83.6 ms                                                | 71.6 ms: 1.17x faster                                                  |
| logging_format             | 7.10 us                                                | 6.24 us: 1.14x faster                                                  |
| sympy_sum                  | 167 ms                                                 | 148 ms: 1.13x faster                                                   |
| logging_simple             | 6.38 us                                                | 5.68 us: 1.12x faster                                                  |
| deltablue                  | 3.71 ms                                                | 3.33 ms: 1.11x faster                                                  |
| raytrace                   | 308 ms                                                 | 277 ms: 1.11x faster                                                   |
| sympy_str                  | 296 ms                                                 | 267 ms: 1.11x faster                                                   |
| chaos                      | 67.5 ms                                                | 61.0 ms: 1.11x faster                                                  |
| gc_traversal               | 4.28 ms                                                | 3.87 ms: 1.10x faster                                                  |
| async_tree_none            | 475 ms                                                 | 434 ms: 1.10x faster                                                   |
| unpack_sequence            | 54.2 ns                                                | 49.4 ns: 1.10x faster                                                  |
| generators                 | 32.5 ms                                                | 29.7 ms: 1.09x faster                                                  |
| regex_compile              | 148 ms                                                 | 135 ms: 1.09x faster                                                   |
| scimark_monte_carlo        | 74.6 ms                                                | 68.6 ms: 1.09x faster                                                  |
| sympy_integrate            | 21.2 ms                                                | 19.5 ms: 1.08x faster                                                  |
| tomli_loads                | 2.30 sec                                               | 2.13 sec: 1.08x faster                                                 |
| pickle_pure_python         | 326 us                                                 | 303 us: 1.07x faster                                                   |
| coroutines                 | 23.5 ms                                                | 21.9 ms: 1.07x faster                                                  |
| chameleon                  | 7.41 ms                                                | 6.98 ms: 1.06x faster                                                  |
| nqueens                    | 86.2 ms                                                | 81.4 ms: 1.06x faster                                                  |
| sqlglot_parse              | 1.35 ms                                                | 1.28 ms: 1.06x faster                                                  |
| hexiom                     | 6.54 ms                                                | 6.19 ms: 1.06x faster                                                  |
| docutils                   | 2.75 sec                                               | 2.61 sec: 1.05x faster                                                 |
| sqlglot_transpile          | 1.68 ms                                                | 1.59 ms: 1.05x faster                                                  |
| sqlglot_normalize          | 112 ms                                                 | 106 ms: 1.05x faster                                                   |
| unpickle                   | 15.8 us                                                | 15.0 us: 1.05x faster                                                  |
| tornado_http               | 101 ms                                                 | 96.1 ms: 1.05x faster                                                  |
| sympy_expand               | 476 ms                                                 | 454 ms: 1.05x faster                                                   |
| unpickle_pure_python       | 230 us                                                 | 219 us: 1.05x faster                                                   |
| scimark_sor                | 129 ms                                                 | 124 ms: 1.05x faster                                                   |
| fannkuch                   | 410 ms                                                 | 393 ms: 1.04x faster                                                   |
| dulwich_log                | 68.7 ms                                                | 65.9 ms: 1.04x faster                                                  |
| deepcopy                   | 363 us                                                 | 348 us: 1.04x faster                                                   |
| 2to3                       | 274 ms                                                 | 264 ms: 1.04x faster                                                   |
| deepcopy_reduce            | 3.23 us                                                | 3.11 us: 1.04x faster                                                  |
| pathlib                    | 18.9 ms                                                | 18.2 ms: 1.04x faster                                                  |
| pprint_safe_repr           | 765 ms                                                 | 738 ms: 1.04x faster                                                   |
| scimark_lu                 | 120 ms                                                 | 116 ms: 1.04x faster                                                   |
| deepcopy_memo              | 39.7 us                                                | 38.5 us: 1.03x faster                                                  |
| xml_etree_process          | 61.2 ms                                                | 59.4 ms: 1.03x faster                                                  |
| pprint_pformat             | 1.55 sec                                               | 1.51 sec: 1.03x faster                                                 |
| async_tree_memoization     | 580 ms                                                 | 563 ms: 1.03x faster                                                   |
| async_generators           | 459 ms                                                 | 447 ms: 1.03x faster                                                   |
| xml_etree_generate         | 88.7 ms                                                | 86.4 ms: 1.03x faster                                                  |
| mypy2                      | 351 ms                                                 | 342 ms: 1.03x faster                                                   |
| scimark_sparse_mat_mult    | 5.33 ms                                                | 5.21 ms: 1.02x faster                                                  |
| sqlglot_optimize           | 54.8 ms                                                | 53.5 ms: 1.02x faster                                                  |
| scimark_fft                | 381 ms                                                 | 372 ms: 1.02x faster                                                   |
| json_loads                 | 28.4 us                                                | 27.8 us: 1.02x faster                                                  |
| json                       | 5.22 ms                                                | 5.12 ms: 1.02x faster                                                  |
| float                      | 83.3 ms                                                | 81.8 ms: 1.02x faster                                                  |
| asyncio_tcp                | 506 ms                                                 | 497 ms: 1.02x faster                                                   |
| dask                       | 369 ms                                                 | 363 ms: 1.02x faster                                                   |
| async_tree_cpu_io_mixed    | 724 ms                                                 | 713 ms: 1.02x faster                                                   |
| xml_etree_parse            | 159 ms                                                 | 157 ms: 1.01x faster                                                   |
| meteor_contest             | 110 ms                                                 | 108 ms: 1.01x faster                                                   |
| bench_thread_pool          | 845 us                                                 | 834 us: 1.01x faster                                                   |
| mdp                        | 2.57 sec                                               | 2.54 sec: 1.01x faster                                                 |
| pyflate                    | 471 ms                                                 | 466 ms: 1.01x faster                                                   |
| json_dumps                 | 10.6 ms                                                | 10.5 ms: 1.01x faster                                                  |
| sqlite_synth               | 2.83 us                                                | 2.81 us: 1.01x faster                                                  |
| spectral_norm              | 115 ms                                                 | 114 ms: 1.01x faster                                                   |
| xml_etree_iterparse        | 106 ms                                                 | 105 ms: 1.01x faster                                                   |
| mako                       | 11.5 ms                                                | 11.5 ms: 1.00x faster                                                  |
| unpickle_list              | 5.04 us                                                | 5.06 us: 1.00x slower                                                  |
| asyncio_tcp_ssl            | 1.78 sec                                               | 1.79 sec: 1.01x slower                                                 |
| async_tree_none_tg         | 447 ms                                                 | 454 ms: 1.01x slower                                                   |
| create_gc_cycles           | 1.45 ms                                                | 1.48 ms: 1.02x slower                                                  |
| nbody                      | 92.2 ms                                                | 94.0 ms: 1.02x slower                                                  |
| pickle_dict                | 33.5 us                                                | 34.2 us: 1.02x slower                                                  |
| pycparser                  | 1.17 sec                                               | 1.20 sec: 1.02x slower                                                 |
| async_tree_io              | 1.16 sec                                               | 1.19 sec: 1.03x slower                                                 |
| async_tree_cpu_io_mixed_tg | 725 ms                                                 | 745 ms: 1.03x slower                                                   |
| richards                   | 46.0 ms                                                | 47.4 ms: 1.03x slower                                                  |
| async_tree_io_tg           | 1.19 sec                                               | 1.23 sec: 1.03x slower                                                 |
| async_tree_memoization_tg  | 574 ms                                                 | 595 ms: 1.04x slower                                                   |
| pidigits                   | 187 ms                                                 | 195 ms: 1.04x slower                                                   |
| regex_dna                  | 209 ms                                                 | 217 ms: 1.04x slower                                                   |
| richards_super             | 51.9 ms                                                | 54.1 ms: 1.04x slower                                                  |
| pickle                     | 11.2 us                                                | 11.7 us: 1.04x slower                                                  |
| regex_v8                   | 22.7 ms                                                | 24.5 ms: 1.08x slower                                                  |
| python_startup             | 9.53 ms                                                | 10.4 ms: 1.09x slower                                                  |
| pickle_list                | 4.67 us                                                | 5.09 us: 1.09x slower                                                  |
| telco                      | 7.18 ms                                                | 8.41 ms: 1.17x slower                                                  |
| coverage                   | 75.1 ms                                                | 95.0 ms: 1.26x slower                                                  |
| python_startup_no_site     | 6.92 ms                                                | 9.02 ms: 1.30x slower                                                  |
| Geometric mean             | (ref)                                                  | 1.03x faster                                                           |

Benchmark hidden because not significant (5): asyncio_websockets, bench_mp_pool, logging_silent, regex_effbot, go
Ignored benchmarks (5) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 99.99% likely to be faster
- 90% likely to have a speedup of 1.01x
- 95% likely to have a speedup of 1.01x
- 99% likely to have a speedup of 1.00x
