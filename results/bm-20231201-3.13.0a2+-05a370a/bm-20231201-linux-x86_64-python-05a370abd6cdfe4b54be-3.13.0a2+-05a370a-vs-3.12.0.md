
# Results vs. 3.12.0

- fork: python
- ref: 05a370abd6cdfe4b54be
- machine: linux-x86_64
- commit hash: 05a370a
- commit date: 2023-12-01
- overall geometric mean: 1.02x faster \*
- HPT reliability: 99.98%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231201-linux-x86_64-python-05a370abd6cdfe4b54be-3.13.0a2+-05a370a |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| 2to3           | 274 ms                                                 | 264 ms: 1.04x faster                                                   |
| chameleon      | 7.41 ms                                                | 6.88 ms: 1.08x faster                                                  |
| docutils       | 2.75 sec                                               | 2.61 sec: 1.06x faster                                                 |
| tornado_http   | 101 ms                                                 | 96.0 ms: 1.05x faster                                                  |
| Geometric mean | (ref)                                                  | 1.05x faster                                                           |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231201-linux-x86_64-python-05a370abd6cdfe4b54be-3.13.0a2+-05a370a |
|----------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| async_tree_none            | 475 ms                                                 | 437 ms: 1.09x faster                                                   |
| async_tree_memoization     | 580 ms                                                 | 566 ms: 1.02x faster                                                   |
| async_tree_cpu_io_mixed    | 724 ms                                                 | 714 ms: 1.01x faster                                                   |
| async_tree_io              | 1.16 sec                                               | 1.18 sec: 1.02x slower                                                 |
| async_tree_none_tg         | 447 ms                                                 | 457 ms: 1.02x slower                                                   |
| async_tree_cpu_io_mixed_tg | 725 ms                                                 | 744 ms: 1.03x slower                                                   |
| async_tree_io_tg           | 1.19 sec                                               | 1.23 sec: 1.03x slower                                                 |
| async_tree_memoization_tg  | 574 ms                                                 | 595 ms: 1.04x slower                                                   |
| Geometric mean             | (ref)                                                  | 1.00x slower                                                           |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231201-linux-x86_64-python-05a370abd6cdfe4b54be-3.13.0a2+-05a370a |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| float          | 83.3 ms                                                | 82.3 ms: 1.01x faster                                                  |
| pidigits       | 187 ms                                                 | 187 ms: 1.00x slower                                                   |
| Geometric mean | (ref)                                                  | 1.00x faster                                                           |

Benchmark hidden because not significant (1): nbody

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231201-linux-x86_64-python-05a370abd6cdfe4b54be-3.13.0a2+-05a370a |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| regex_compile  | 148 ms                                                 | 133 ms: 1.12x faster                                                   |
| regex_effbot   | 3.57 ms                                                | 3.59 ms: 1.00x slower                                                  |
| regex_dna      | 209 ms                                                 | 214 ms: 1.03x slower                                                   |
| regex_v8       | 22.7 ms                                                | 26.1 ms: 1.15x slower                                                  |
| Geometric mean | (ref)                                                  | 1.02x slower                                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231201-linux-x86_64-python-05a370abd6cdfe4b54be-3.13.0a2+-05a370a |
|----------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| pickle_pure_python   | 326 us                                                 | 305 us: 1.07x faster                                                   |
| unpickle_pure_python | 230 us                                                 | 217 us: 1.06x faster                                                   |
| tomli_loads          | 2.30 sec                                               | 2.19 sec: 1.05x faster                                                 |
| unpickle             | 15.8 us                                                | 15.3 us: 1.03x faster                                                  |
| xml_etree_process    | 61.2 ms                                                | 59.5 ms: 1.03x faster                                                  |
| xml_etree_generate   | 88.7 ms                                                | 87.0 ms: 1.02x faster                                                  |
| pickle_dict          | 33.5 us                                                | 33.0 us: 1.02x faster                                                  |
| xml_etree_parse      | 159 ms                                                 | 158 ms: 1.01x faster                                                   |
| xml_etree_iterparse  | 106 ms                                                 | 105 ms: 1.01x faster                                                   |
| json_dumps           | 10.6 ms                                                | 10.5 ms: 1.01x faster                                                  |
| unpickle_list        | 5.04 us                                                | 5.23 us: 1.04x slower                                                  |
| pickle_list          | 4.67 us                                                | 4.91 us: 1.05x slower                                                  |
| Geometric mean       | (ref)                                                  | 1.02x faster                                                           |

Benchmark hidden because not significant (2): json_loads, pickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231201-linux-x86_64-python-05a370abd6cdfe4b54be-3.13.0a2+-05a370a |
|------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| python_startup         | 9.53 ms                                                | 10.3 ms: 1.08x slower                                                  |
| python_startup_no_site | 6.92 ms                                                | 8.95 ms: 1.29x slower                                                  |
| Geometric mean         | (ref)                                                  | 1.18x slower                                                           |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231201-linux-x86_64-python-05a370abd6cdfe4b54be-3.13.0a2+-05a370a |
|-----------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| mako      | 11.5 ms                                                | 11.1 ms: 1.04x faster                                                  |

All benchmarks:
===============

| Benchmark                  | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231201-linux-x86_64-python-05a370abd6cdfe4b54be-3.13.0a2+-05a370a |
|----------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| typing_runtime_protocols   | 153 us                                                 | 115 us: 1.34x faster                                                   |
| comprehensions             | 20.9 us                                                | 16.0 us: 1.31x faster                                                  |
| crypto_pyaes               | 83.6 ms                                                | 71.8 ms: 1.16x faster                                                  |
| generators                 | 32.5 ms                                                | 28.3 ms: 1.15x faster                                                  |
| logging_format             | 7.10 us                                                | 6.26 us: 1.13x faster                                                  |
| deltablue                  | 3.71 ms                                                | 3.28 ms: 1.13x faster                                                  |
| sympy_sum                  | 167 ms                                                 | 148 ms: 1.13x faster                                                   |
| logging_simple             | 6.38 us                                                | 5.68 us: 1.12x faster                                                  |
| raytrace                   | 308 ms                                                 | 275 ms: 1.12x faster                                                   |
| regex_compile              | 148 ms                                                 | 133 ms: 1.12x faster                                                   |
| sympy_str                  | 296 ms                                                 | 267 ms: 1.11x faster                                                   |
| scimark_sparse_mat_mult    | 5.33 ms                                                | 4.81 ms: 1.11x faster                                                  |
| chaos                      | 67.5 ms                                                | 61.9 ms: 1.09x faster                                                  |
| scimark_monte_carlo        | 74.6 ms                                                | 68.5 ms: 1.09x faster                                                  |
| async_tree_none            | 475 ms                                                 | 437 ms: 1.09x faster                                                   |
| sympy_integrate            | 21.2 ms                                                | 19.6 ms: 1.08x faster                                                  |
| coroutines                 | 23.5 ms                                                | 21.7 ms: 1.08x faster                                                  |
| chameleon                  | 7.41 ms                                                | 6.88 ms: 1.08x faster                                                  |
| pickle_pure_python         | 326 us                                                 | 305 us: 1.07x faster                                                   |
| nqueens                    | 86.2 ms                                                | 80.7 ms: 1.07x faster                                                  |
| unpickle_pure_python       | 230 us                                                 | 217 us: 1.06x faster                                                   |
| hexiom                     | 6.54 ms                                                | 6.19 ms: 1.06x faster                                                  |
| docutils                   | 2.75 sec                                               | 2.61 sec: 1.06x faster                                                 |
| sqlglot_parse              | 1.35 ms                                                | 1.28 ms: 1.05x faster                                                  |
| sqlglot_normalize          | 112 ms                                                 | 106 ms: 1.05x faster                                                   |
| sympy_expand               | 476 ms                                                 | 453 ms: 1.05x faster                                                   |
| unpack_sequence            | 54.2 ns                                                | 51.6 ns: 1.05x faster                                                  |
| tornado_http               | 101 ms                                                 | 96.0 ms: 1.05x faster                                                  |
| sqlglot_transpile          | 1.68 ms                                                | 1.60 ms: 1.05x faster                                                  |
| tomli_loads                | 2.30 sec                                               | 2.19 sec: 1.05x faster                                                 |
| dulwich_log                | 68.7 ms                                                | 65.9 ms: 1.04x faster                                                  |
| scimark_fft                | 381 ms                                                 | 365 ms: 1.04x faster                                                   |
| scimark_lu                 | 120 ms                                                 | 116 ms: 1.04x faster                                                   |
| deepcopy_reduce            | 3.23 us                                                | 3.10 us: 1.04x faster                                                  |
| pathlib                    | 18.9 ms                                                | 18.2 ms: 1.04x faster                                                  |
| scimark_sor                | 129 ms                                                 | 124 ms: 1.04x faster                                                   |
| deepcopy_memo              | 39.7 us                                                | 38.2 us: 1.04x faster                                                  |
| 2to3                       | 274 ms                                                 | 264 ms: 1.04x faster                                                   |
| mako                       | 11.5 ms                                                | 11.1 ms: 1.04x faster                                                  |
| deepcopy                   | 363 us                                                 | 349 us: 1.04x faster                                                   |
| asyncio_tcp                | 506 ms                                                 | 488 ms: 1.04x faster                                                   |
| async_generators           | 459 ms                                                 | 445 ms: 1.03x faster                                                   |
| fannkuch                   | 410 ms                                                 | 398 ms: 1.03x faster                                                   |
| unpickle                   | 15.8 us                                                | 15.3 us: 1.03x faster                                                  |
| xml_etree_process          | 61.2 ms                                                | 59.5 ms: 1.03x faster                                                  |
| sqlglot_optimize           | 54.8 ms                                                | 53.4 ms: 1.03x faster                                                  |
| async_tree_memoization     | 580 ms                                                 | 566 ms: 1.02x faster                                                   |
| dask                       | 369 ms                                                 | 361 ms: 1.02x faster                                                   |
| pprint_safe_repr           | 765 ms                                                 | 748 ms: 1.02x faster                                                   |
| xml_etree_generate         | 88.7 ms                                                | 87.0 ms: 1.02x faster                                                  |
| pprint_pformat             | 1.55 sec                                               | 1.52 sec: 1.02x faster                                                 |
| bench_thread_pool          | 845 us                                                 | 829 us: 1.02x faster                                                   |
| meteor_contest             | 110 ms                                                 | 108 ms: 1.02x faster                                                   |
| pickle_dict                | 33.5 us                                                | 33.0 us: 1.02x faster                                                  |
| async_tree_cpu_io_mixed    | 724 ms                                                 | 714 ms: 1.01x faster                                                   |
| float                      | 83.3 ms                                                | 82.3 ms: 1.01x faster                                                  |
| xml_etree_parse            | 159 ms                                                 | 158 ms: 1.01x faster                                                   |
| xml_etree_iterparse        | 106 ms                                                 | 105 ms: 1.01x faster                                                   |
| spectral_norm              | 115 ms                                                 | 114 ms: 1.01x faster                                                   |
| json                       | 5.22 ms                                                | 5.18 ms: 1.01x faster                                                  |
| pyflate                    | 471 ms                                                 | 467 ms: 1.01x faster                                                   |
| json_dumps                 | 10.6 ms                                                | 10.5 ms: 1.01x faster                                                  |
| go                         | 140 ms                                                 | 140 ms: 1.00x faster                                                   |
| mdp                        | 2.57 sec                                               | 2.56 sec: 1.00x faster                                                 |
| pidigits                   | 187 ms                                                 | 187 ms: 1.00x slower                                                   |
| gc_traversal               | 4.28 ms                                                | 4.29 ms: 1.00x slower                                                  |
| asyncio_tcp_ssl            | 1.78 sec                                               | 1.79 sec: 1.00x slower                                                 |
| regex_effbot               | 3.57 ms                                                | 3.59 ms: 1.00x slower                                                  |
| create_gc_cycles           | 1.45 ms                                                | 1.46 ms: 1.01x slower                                                  |
| async_tree_io              | 1.16 sec                                               | 1.18 sec: 1.02x slower                                                 |
| async_tree_none_tg         | 447 ms                                                 | 457 ms: 1.02x slower                                                   |
| async_tree_cpu_io_mixed_tg | 725 ms                                                 | 744 ms: 1.03x slower                                                   |
| regex_dna                  | 209 ms                                                 | 214 ms: 1.03x slower                                                   |
| async_tree_io_tg           | 1.19 sec                                               | 1.23 sec: 1.03x slower                                                 |
| pycparser                  | 1.17 sec                                               | 1.21 sec: 1.04x slower                                                 |
| unpickle_list              | 5.04 us                                                | 5.23 us: 1.04x slower                                                  |
| async_tree_memoization_tg  | 574 ms                                                 | 595 ms: 1.04x slower                                                   |
| richards_super             | 51.9 ms                                                | 53.8 ms: 1.04x slower                                                  |
| richards                   | 46.0 ms                                                | 48.0 ms: 1.04x slower                                                  |
| pickle_list                | 4.67 us                                                | 4.91 us: 1.05x slower                                                  |
| python_startup             | 9.53 ms                                                | 10.3 ms: 1.08x slower                                                  |
| regex_v8                   | 22.7 ms                                                | 26.1 ms: 1.15x slower                                                  |
| telco                      | 7.18 ms                                                | 8.28 ms: 1.15x slower                                                  |
| coverage                   | 75.1 ms                                                | 94.4 ms: 1.26x slower                                                  |
| python_startup_no_site     | 6.92 ms                                                | 8.95 ms: 1.29x slower                                                  |
| mypy2                      | 351 ms                                                 | 838 ms: 2.39x slower                                                   |
| Geometric mean             | (ref)                                                  | 1.02x faster                                                           |

Benchmark hidden because not significant (7): sqlite_synth, json_loads, pickle, asyncio_websockets, bench_mp_pool, nbody, logging_silent
Ignored benchmarks (5) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 99.98% likely to be faster
- 90% likely to have a speedup of 1.01x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
