
# Results vs. 3.12.0

- fork: python
- ref: main
- machine: linux-x86_64
- commit hash: 853b4b5
- commit date: 2023-11-04
- overall geometric mean: 1.04x faster \*
- HPT reliability: 99.99%
- HPT 99th percentile: 1.01x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231104-linux-x86_64-python-main-3.13.0a1+-853b4b5 |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| 2to3           | 274 ms                                                 | 262 ms: 1.05x faster                                   |
| chameleon      | 7.41 ms                                                | 6.84 ms: 1.08x faster                                  |
| docutils       | 2.75 sec                                               | 2.59 sec: 1.06x faster                                 |
| tornado_http   | 101 ms                                                 | 95.2 ms: 1.06x faster                                  |
| Geometric mean | (ref)                                                  | 1.06x faster                                           |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231104-linux-x86_64-python-main-3.13.0a1+-853b4b5 |
|----------------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| async_tree_none            | 475 ms                                                 | 439 ms: 1.08x faster                                   |
| async_tree_memoization     | 580 ms                                                 | 565 ms: 1.03x faster                                   |
| async_tree_cpu_io_mixed    | 724 ms                                                 | 711 ms: 1.02x faster                                   |
| async_tree_none_tg         | 447 ms                                                 | 458 ms: 1.02x slower                                   |
| async_tree_cpu_io_mixed_tg | 725 ms                                                 | 743 ms: 1.03x slower                                   |
| async_tree_io              | 1.16 sec                                               | 1.19 sec: 1.03x slower                                 |
| async_tree_io_tg           | 1.19 sec                                               | 1.24 sec: 1.04x slower                                 |
| async_tree_memoization_tg  | 574 ms                                                 | 600 ms: 1.04x slower                                   |
| Geometric mean             | (ref)                                                  | 1.00x slower                                           |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231104-linux-x86_64-python-main-3.13.0a1+-853b4b5 |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| float          | 83.3 ms                                                | 81.5 ms: 1.02x faster                                  |
| nbody          | 92.2 ms                                                | 90.5 ms: 1.02x faster                                  |
| pidigits       | 187 ms                                                 | 195 ms: 1.04x slower                                   |
| Geometric mean | (ref)                                                  | 1.00x slower                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231104-linux-x86_64-python-main-3.13.0a1+-853b4b5 |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| regex_compile  | 148 ms                                                 | 134 ms: 1.10x faster                                   |
| regex_effbot   | 3.57 ms                                                | 3.53 ms: 1.01x faster                                  |
| regex_dna      | 209 ms                                                 | 222 ms: 1.06x slower                                   |
| regex_v8       | 22.7 ms                                                | 24.3 ms: 1.07x slower                                  |
| Geometric mean | (ref)                                                  | 1.01x slower                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231104-linux-x86_64-python-main-3.13.0a1+-853b4b5 |
|----------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| pickle_pure_python   | 326 us                                                 | 295 us: 1.10x faster                                   |
| tomli_loads          | 2.30 sec                                               | 2.12 sec: 1.08x faster                                 |
| unpickle_pure_python | 230 us                                                 | 218 us: 1.05x faster                                   |
| xml_etree_process    | 61.2 ms                                                | 59.1 ms: 1.04x faster                                  |
| json_loads           | 28.4 us                                                | 27.5 us: 1.03x faster                                  |
| unpickle             | 15.8 us                                                | 15.3 us: 1.03x faster                                  |
| xml_etree_generate   | 88.7 ms                                                | 86.6 ms: 1.02x faster                                  |
| json_dumps           | 10.6 ms                                                | 10.4 ms: 1.02x faster                                  |
| xml_etree_iterparse  | 106 ms                                                 | 105 ms: 1.01x faster                                   |
| xml_etree_parse      | 159 ms                                                 | 159 ms: 1.01x faster                                   |
| pickle               | 11.2 us                                                | 11.5 us: 1.03x slower                                  |
| unpickle_list        | 5.04 us                                                | 5.19 us: 1.03x slower                                  |
| pickle_dict          | 33.5 us                                                | 36.1 us: 1.08x slower                                  |
| pickle_list          | 4.67 us                                                | 5.24 us: 1.12x slower                                  |
| Geometric mean       | (ref)                                                  | 1.01x faster                                           |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231104-linux-x86_64-python-main-3.13.0a1+-853b4b5 |
|------------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| python_startup         | 9.53 ms                                                | 10.3 ms: 1.08x slower                                  |
| python_startup_no_site | 6.92 ms                                                | 8.97 ms: 1.30x slower                                  |
| Geometric mean         | (ref)                                                  | 1.18x slower                                           |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231104-linux-x86_64-python-main-3.13.0a1+-853b4b5 |
|-----------|:------------------------------------------------------:|:------------------------------------------------------:|
| mako      | 11.5 ms                                                | 11.1 ms: 1.04x faster                                  |

All benchmarks:
===============

| Benchmark                  | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231104-linux-x86_64-python-main-3.13.0a1+-853b4b5 |
|----------------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| typing_runtime_protocols   | 153 us                                                 | 115 us: 1.34x faster                                   |
| comprehensions             | 20.9 us                                                | 15.9 us: 1.32x faster                                  |
| unpack_sequence            | 54.2 ns                                                | 41.9 ns: 1.29x faster                                  |
| crypto_pyaes               | 83.6 ms                                                | 70.3 ms: 1.19x faster                                  |
| gc_traversal               | 4.28 ms                                                | 3.67 ms: 1.16x faster                                  |
| raytrace                   | 308 ms                                                 | 268 ms: 1.15x faster                                   |
| sympy_sum                  | 167 ms                                                 | 146 ms: 1.14x faster                                   |
| deltablue                  | 3.71 ms                                                | 3.25 ms: 1.14x faster                                  |
| chaos                      | 67.5 ms                                                | 59.8 ms: 1.13x faster                                  |
| logging_format             | 7.10 us                                                | 6.30 us: 1.13x faster                                  |
| sympy_str                  | 296 ms                                                 | 265 ms: 1.12x faster                                   |
| logging_simple             | 6.38 us                                                | 5.72 us: 1.12x faster                                  |
| nqueens                    | 86.2 ms                                                | 77.7 ms: 1.11x faster                                  |
| scimark_monte_carlo        | 74.6 ms                                                | 67.5 ms: 1.11x faster                                  |
| pickle_pure_python         | 326 us                                                 | 295 us: 1.10x faster                                   |
| regex_compile              | 148 ms                                                 | 134 ms: 1.10x faster                                   |
| sympy_integrate            | 21.2 ms                                                | 19.3 ms: 1.10x faster                                  |
| generators                 | 32.5 ms                                                | 29.5 ms: 1.10x faster                                  |
| spectral_norm              | 115 ms                                                 | 105 ms: 1.09x faster                                   |
| hexiom                     | 6.54 ms                                                | 6.03 ms: 1.09x faster                                  |
| scimark_sparse_mat_mult    | 5.33 ms                                                | 4.92 ms: 1.08x faster                                  |
| chameleon                  | 7.41 ms                                                | 6.84 ms: 1.08x faster                                  |
| async_tree_none            | 475 ms                                                 | 439 ms: 1.08x faster                                   |
| tomli_loads                | 2.30 sec                                               | 2.12 sec: 1.08x faster                                 |
| sqlglot_parse              | 1.35 ms                                                | 1.26 ms: 1.07x faster                                  |
| sqlglot_normalize          | 112 ms                                                 | 104 ms: 1.07x faster                                   |
| coroutines                 | 23.5 ms                                                | 22.0 ms: 1.06x faster                                  |
| scimark_sor                | 129 ms                                                 | 121 ms: 1.06x faster                                   |
| sqlglot_transpile          | 1.68 ms                                                | 1.58 ms: 1.06x faster                                  |
| sympy_expand               | 476 ms                                                 | 447 ms: 1.06x faster                                   |
| docutils                   | 2.75 sec                                               | 2.59 sec: 1.06x faster                                 |
| scimark_lu                 | 120 ms                                                 | 114 ms: 1.06x faster                                   |
| tornado_http               | 101 ms                                                 | 95.2 ms: 1.06x faster                                  |
| pprint_safe_repr           | 765 ms                                                 | 724 ms: 1.06x faster                                   |
| deepcopy_memo              | 39.7 us                                                | 37.6 us: 1.06x faster                                  |
| scimark_fft                | 381 ms                                                 | 361 ms: 1.05x faster                                   |
| deepcopy                   | 363 us                                                 | 344 us: 1.05x faster                                   |
| unpickle_pure_python       | 230 us                                                 | 218 us: 1.05x faster                                   |
| pprint_pformat             | 1.55 sec                                               | 1.48 sec: 1.05x faster                                 |
| dulwich_log                | 68.7 ms                                                | 65.6 ms: 1.05x faster                                  |
| deepcopy_reduce            | 3.23 us                                                | 3.08 us: 1.05x faster                                  |
| 2to3                       | 274 ms                                                 | 262 ms: 1.05x faster                                   |
| asyncio_tcp                | 506 ms                                                 | 484 ms: 1.04x faster                                   |
| pyflate                    | 471 ms                                                 | 451 ms: 1.04x faster                                   |
| fannkuch                   | 410 ms                                                 | 396 ms: 1.04x faster                                   |
| mako                       | 11.5 ms                                                | 11.1 ms: 1.04x faster                                  |
| xml_etree_process          | 61.2 ms                                                | 59.1 ms: 1.04x faster                                  |
| json_loads                 | 28.4 us                                                | 27.5 us: 1.03x faster                                  |
| mypy2                      | 351 ms                                                 | 340 ms: 1.03x faster                                   |
| unpickle                   | 15.8 us                                                | 15.3 us: 1.03x faster                                  |
| sqlglot_optimize           | 54.8 ms                                                | 53.1 ms: 1.03x faster                                  |
| async_generators           | 459 ms                                                 | 447 ms: 1.03x faster                                   |
| logging_silent             | 108 ns                                                 | 105 ns: 1.03x faster                                   |
| async_tree_memoization     | 580 ms                                                 | 565 ms: 1.03x faster                                   |
| xml_etree_generate         | 88.7 ms                                                | 86.6 ms: 1.02x faster                                  |
| meteor_contest             | 110 ms                                                 | 107 ms: 1.02x faster                                   |
| bench_thread_pool          | 845 us                                                 | 826 us: 1.02x faster                                   |
| float                      | 83.3 ms                                                | 81.5 ms: 1.02x faster                                  |
| json_dumps                 | 10.6 ms                                                | 10.4 ms: 1.02x faster                                  |
| json                       | 5.22 ms                                                | 5.12 ms: 1.02x faster                                  |
| nbody                      | 92.2 ms                                                | 90.5 ms: 1.02x faster                                  |
| async_tree_cpu_io_mixed    | 724 ms                                                 | 711 ms: 1.02x faster                                   |
| regex_effbot               | 3.57 ms                                                | 3.53 ms: 1.01x faster                                  |
| xml_etree_iterparse        | 106 ms                                                 | 105 ms: 1.01x faster                                   |
| go                         | 140 ms                                                 | 139 ms: 1.01x faster                                   |
| xml_etree_parse            | 159 ms                                                 | 159 ms: 1.01x faster                                   |
| asyncio_tcp_ssl            | 1.78 sec                                               | 1.79 sec: 1.00x slower                                 |
| mdp                        | 2.57 sec                                               | 2.59 sec: 1.01x slower                                 |
| async_tree_none_tg         | 447 ms                                                 | 458 ms: 1.02x slower                                   |
| async_tree_cpu_io_mixed_tg | 725 ms                                                 | 743 ms: 1.03x slower                                   |
| pickle                     | 11.2 us                                                | 11.5 us: 1.03x slower                                  |
| async_tree_io              | 1.16 sec                                               | 1.19 sec: 1.03x slower                                 |
| pycparser                  | 1.17 sec                                               | 1.20 sec: 1.03x slower                                 |
| unpickle_list              | 5.04 us                                                | 5.19 us: 1.03x slower                                  |
| async_tree_io_tg           | 1.19 sec                                               | 1.24 sec: 1.04x slower                                 |
| pidigits                   | 187 ms                                                 | 195 ms: 1.04x slower                                   |
| async_tree_memoization_tg  | 574 ms                                                 | 600 ms: 1.04x slower                                   |
| richards                   | 46.0 ms                                                | 48.4 ms: 1.05x slower                                  |
| richards_super             | 51.9 ms                                                | 55.0 ms: 1.06x slower                                  |
| regex_dna                  | 209 ms                                                 | 222 ms: 1.06x slower                                   |
| regex_v8                   | 22.7 ms                                                | 24.3 ms: 1.07x slower                                  |
| pickle_dict                | 33.5 us                                                | 36.1 us: 1.08x slower                                  |
| python_startup             | 9.53 ms                                                | 10.3 ms: 1.08x slower                                  |
| pickle_list                | 4.67 us                                                | 5.24 us: 1.12x slower                                  |
| telco                      | 7.18 ms                                                | 8.31 ms: 1.16x slower                                  |
| coverage                   | 75.1 ms                                                | 95.7 ms: 1.27x slower                                  |
| python_startup_no_site     | 6.92 ms                                                | 8.97 ms: 1.30x slower                                  |
| Geometric mean             | (ref)                                                  | 1.04x faster                                           |

Benchmark hidden because not significant (5): sqlite_synth, asyncio_websockets, pathlib, bench_mp_pool, create_gc_cycles
Ignored benchmarks (6) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, dask, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 99.99% likely to be faster
- 90% likely to have a speedup of 1.02x
- 95% likely to have a speedup of 1.01x
- 99% likely to have a speedup of 1.01x
