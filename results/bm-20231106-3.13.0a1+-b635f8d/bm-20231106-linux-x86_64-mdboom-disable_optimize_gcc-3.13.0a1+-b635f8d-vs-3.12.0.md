
# Results vs. 3.12.0

- fork: mdboom
- ref: disable_optimize_gcc
- machine: linux-x86_64
- commit hash: b635f8d
- commit date: 2023-11-06
- overall geometric mean: 1.07x slower \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.04x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231106-linux-x86_64-mdboom-disable_optimize_gcc-3.13.0a1+-b635f8d |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| 2to3           | 274 ms                                                 | 289 ms: 1.05x slower                                                   |
| chameleon      | 7.41 ms                                                | 8.49 ms: 1.15x slower                                                  |
| docutils       | 2.75 sec                                               | 2.72 sec: 1.01x faster                                                 |
| tornado_http   | 101 ms                                                 | 98.9 ms: 1.02x faster                                                  |
| Geometric mean | (ref)                                                  | 1.04x slower                                                           |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231106-linux-x86_64-mdboom-disable_optimize_gcc-3.13.0a1+-b635f8d |
|----------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| async_tree_none            | 475 ms                                                 | 464 ms: 1.02x faster                                                   |
| async_tree_cpu_io_mixed    | 724 ms                                                 | 742 ms: 1.02x slower                                                   |
| async_tree_memoization     | 580 ms                                                 | 597 ms: 1.03x slower                                                   |
| async_tree_cpu_io_mixed_tg | 725 ms                                                 | 770 ms: 1.06x slower                                                   |
| async_tree_io              | 1.16 sec                                               | 1.24 sec: 1.07x slower                                                 |
| async_tree_none_tg         | 447 ms                                                 | 480 ms: 1.07x slower                                                   |
| async_tree_io_tg           | 1.19 sec                                               | 1.28 sec: 1.08x slower                                                 |
| async_tree_memoization_tg  | 574 ms                                                 | 622 ms: 1.08x slower                                                   |
| Geometric mean             | (ref)                                                  | 1.05x slower                                                           |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231106-linux-x86_64-mdboom-disable_optimize_gcc-3.13.0a1+-b635f8d |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| pidigits       | 187 ms                                                 | 188 ms: 1.01x slower                                                   |
| float          | 83.3 ms                                                | 89.5 ms: 1.07x slower                                                  |
| nbody          | 92.2 ms                                                | 125 ms: 1.36x slower                                                   |
| Geometric mean | (ref)                                                  | 1.14x slower                                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231106-linux-x86_64-mdboom-disable_optimize_gcc-3.13.0a1+-b635f8d |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| regex_effbot   | 3.57 ms                                                | 3.50 ms: 1.02x faster                                                  |
| regex_compile  | 148 ms                                                 | 150 ms: 1.01x slower                                                   |
| regex_dna      | 209 ms                                                 | 217 ms: 1.04x slower                                                   |
| regex_v8       | 22.7 ms                                                | 24.5 ms: 1.08x slower                                                  |
| Geometric mean | (ref)                                                  | 1.03x slower                                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231106-linux-x86_64-mdboom-disable_optimize_gcc-3.13.0a1+-b635f8d |
|----------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| unpickle             | 15.8 us                                                | 14.6 us: 1.08x faster                                                  |
| json_loads           | 28.4 us                                                | 28.0 us: 1.01x faster                                                  |
| xml_etree_parse      | 159 ms                                                 | 163 ms: 1.02x slower                                                   |
| json_dumps           | 10.6 ms                                                | 10.9 ms: 1.03x slower                                                  |
| pickle_list          | 4.67 us                                                | 4.92 us: 1.05x slower                                                  |
| unpickle_list        | 5.04 us                                                | 5.31 us: 1.05x slower                                                  |
| xml_etree_iterparse  | 106 ms                                                 | 113 ms: 1.07x slower                                                   |
| tomli_loads          | 2.30 sec                                               | 2.46 sec: 1.07x slower                                                 |
| xml_etree_generate   | 88.7 ms                                                | 96.0 ms: 1.08x slower                                                  |
| pickle_pure_python   | 326 us                                                 | 357 us: 1.09x slower                                                   |
| unpickle_pure_python | 230 us                                                 | 258 us: 1.12x slower                                                   |
| xml_etree_process    | 61.2 ms                                                | 68.9 ms: 1.13x slower                                                  |
| Geometric mean       | (ref)                                                  | 1.04x slower                                                           |

Benchmark hidden because not significant (2): pickle, pickle_dict

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231106-linux-x86_64-mdboom-disable_optimize_gcc-3.13.0a1+-b635f8d |
|------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| python_startup         | 9.53 ms                                                | 10.4 ms: 1.09x slower                                                  |
| python_startup_no_site | 6.92 ms                                                | 9.06 ms: 1.31x slower                                                  |
| Geometric mean         | (ref)                                                  | 1.20x slower                                                           |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231106-linux-x86_64-mdboom-disable_optimize_gcc-3.13.0a1+-b635f8d |
|-----------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| mako      | 11.5 ms                                                | 13.4 ms: 1.17x slower                                                  |

All benchmarks:
===============

| Benchmark                  | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231106-linux-x86_64-mdboom-disable_optimize_gcc-3.13.0a1+-b635f8d |
|----------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| typing_runtime_protocols   | 153 us                                                 | 130 us: 1.18x faster                                                   |
| sympy_sum                  | 167 ms                                                 | 154 ms: 1.09x faster                                                   |
| unpickle                   | 15.8 us                                                | 14.6 us: 1.08x faster                                                  |
| crypto_pyaes               | 83.6 ms                                                | 78.2 ms: 1.07x faster                                                  |
| comprehensions             | 20.9 us                                                | 19.9 us: 1.05x faster                                                  |
| asyncio_tcp                | 506 ms                                                 | 490 ms: 1.03x faster                                                   |
| sympy_integrate            | 21.2 ms                                                | 20.6 ms: 1.03x faster                                                  |
| async_tree_none            | 475 ms                                                 | 464 ms: 1.02x faster                                                   |
| sympy_str                  | 296 ms                                                 | 290 ms: 1.02x faster                                                   |
| regex_effbot               | 3.57 ms                                                | 3.50 ms: 1.02x faster                                                  |
| tornado_http               | 101 ms                                                 | 98.9 ms: 1.02x faster                                                  |
| json_loads                 | 28.4 us                                                | 28.0 us: 1.01x faster                                                  |
| docutils                   | 2.75 sec                                               | 2.72 sec: 1.01x faster                                                 |
| dulwich_log                | 68.7 ms                                                | 68.0 ms: 1.01x faster                                                  |
| gc_traversal               | 4.28 ms                                                | 4.30 ms: 1.01x slower                                                  |
| pidigits                   | 187 ms                                                 | 188 ms: 1.01x slower                                                   |
| asyncio_tcp_ssl            | 1.78 sec                                               | 1.80 sec: 1.01x slower                                                 |
| mypy2                      | 351 ms                                                 | 354 ms: 1.01x slower                                                   |
| sqlite_synth               | 2.83 us                                                | 2.86 us: 1.01x slower                                                  |
| json                       | 5.22 ms                                                | 5.27 ms: 1.01x slower                                                  |
| regex_compile              | 148 ms                                                 | 150 ms: 1.01x slower                                                   |
| create_gc_cycles           | 1.45 ms                                                | 1.47 ms: 1.01x slower                                                  |
| async_tree_cpu_io_mixed    | 724 ms                                                 | 742 ms: 1.02x slower                                                   |
| xml_etree_parse            | 159 ms                                                 | 163 ms: 1.02x slower                                                   |
| sympy_expand               | 476 ms                                                 | 489 ms: 1.03x slower                                                   |
| async_generators           | 459 ms                                                 | 473 ms: 1.03x slower                                                   |
| async_tree_memoization     | 580 ms                                                 | 597 ms: 1.03x slower                                                   |
| json_dumps                 | 10.6 ms                                                | 10.9 ms: 1.03x slower                                                  |
| meteor_contest             | 110 ms                                                 | 114 ms: 1.04x slower                                                   |
| pycparser                  | 1.17 sec                                               | 1.22 sec: 1.04x slower                                                 |
| regex_dna                  | 209 ms                                                 | 217 ms: 1.04x slower                                                   |
| bench_thread_pool          | 845 us                                                 | 878 us: 1.04x slower                                                   |
| scimark_monte_carlo        | 74.6 ms                                                | 77.8 ms: 1.04x slower                                                  |
| scimark_sparse_mat_mult    | 5.33 ms                                                | 5.60 ms: 1.05x slower                                                  |
| raytrace                   | 308 ms                                                 | 324 ms: 1.05x slower                                                   |
| pickle_list                | 4.67 us                                                | 4.92 us: 1.05x slower                                                  |
| unpickle_list              | 5.04 us                                                | 5.31 us: 1.05x slower                                                  |
| scimark_lu                 | 120 ms                                                 | 127 ms: 1.05x slower                                                   |
| 2to3                       | 274 ms                                                 | 289 ms: 1.05x slower                                                   |
| mdp                        | 2.57 sec                                               | 2.72 sec: 1.06x slower                                                 |
| async_tree_cpu_io_mixed_tg | 725 ms                                                 | 770 ms: 1.06x slower                                                   |
| async_tree_io              | 1.16 sec                                               | 1.24 sec: 1.07x slower                                                 |
| xml_etree_iterparse        | 106 ms                                                 | 113 ms: 1.07x slower                                                   |
| tomli_loads                | 2.30 sec                                               | 2.46 sec: 1.07x slower                                                 |
| chaos                      | 67.5 ms                                                | 72.2 ms: 1.07x slower                                                  |
| sqlglot_transpile          | 1.68 ms                                                | 1.79 ms: 1.07x slower                                                  |
| pathlib                    | 18.9 ms                                                | 20.2 ms: 1.07x slower                                                  |
| async_tree_none_tg         | 447 ms                                                 | 480 ms: 1.07x slower                                                   |
| spectral_norm              | 115 ms                                                 | 123 ms: 1.07x slower                                                   |
| float                      | 83.3 ms                                                | 89.5 ms: 1.07x slower                                                  |
| async_tree_io_tg           | 1.19 sec                                               | 1.28 sec: 1.08x slower                                                 |
| regex_v8                   | 22.7 ms                                                | 24.5 ms: 1.08x slower                                                  |
| sqlglot_parse              | 1.35 ms                                                | 1.46 ms: 1.08x slower                                                  |
| sqlglot_normalize          | 112 ms                                                 | 121 ms: 1.08x slower                                                   |
| xml_etree_generate         | 88.7 ms                                                | 96.0 ms: 1.08x slower                                                  |
| sqlglot_optimize           | 54.8 ms                                                | 59.4 ms: 1.08x slower                                                  |
| async_tree_memoization_tg  | 574 ms                                                 | 622 ms: 1.08x slower                                                   |
| scimark_fft                | 381 ms                                                 | 414 ms: 1.09x slower                                                   |
| python_startup             | 9.53 ms                                                | 10.4 ms: 1.09x slower                                                  |
| pickle_pure_python         | 326 us                                                 | 357 us: 1.09x slower                                                   |
| nqueens                    | 86.2 ms                                                | 95.1 ms: 1.10x slower                                                  |
| logging_format             | 7.10 us                                                | 7.92 us: 1.12x slower                                                  |
| pyflate                    | 471 ms                                                 | 528 ms: 1.12x slower                                                   |
| unpickle_pure_python       | 230 us                                                 | 258 us: 1.12x slower                                                   |
| xml_etree_process          | 61.2 ms                                                | 68.9 ms: 1.13x slower                                                  |
| deepcopy_reduce            | 3.23 us                                                | 3.66 us: 1.13x slower                                                  |
| logging_simple             | 6.38 us                                                | 7.30 us: 1.14x slower                                                  |
| chameleon                  | 7.41 ms                                                | 8.49 ms: 1.15x slower                                                  |
| pprint_safe_repr           | 765 ms                                                 | 878 ms: 1.15x slower                                                   |
| pprint_pformat             | 1.55 sec                                               | 1.78 sec: 1.15x slower                                                 |
| fannkuch                   | 410 ms                                                 | 474 ms: 1.16x slower                                                   |
| deepcopy                   | 363 us                                                 | 420 us: 1.16x slower                                                   |
| deltablue                  | 3.71 ms                                                | 4.32 ms: 1.17x slower                                                  |
| generators                 | 32.5 ms                                                | 37.8 ms: 1.17x slower                                                  |
| mako                       | 11.5 ms                                                | 13.4 ms: 1.17x slower                                                  |
| logging_silent             | 108 ns                                                 | 126 ns: 1.17x slower                                                   |
| hexiom                     | 6.54 ms                                                | 7.66 ms: 1.17x slower                                                  |
| go                         | 140 ms                                                 | 165 ms: 1.17x slower                                                   |
| deepcopy_memo              | 39.7 us                                                | 47.0 us: 1.18x slower                                                  |
| telco                      | 7.18 ms                                                | 8.64 ms: 1.20x slower                                                  |
| coroutines                 | 23.5 ms                                                | 28.5 ms: 1.22x slower                                                  |
| richards_super             | 51.9 ms                                                | 66.0 ms: 1.27x slower                                                  |
| richards                   | 46.0 ms                                                | 58.8 ms: 1.28x slower                                                  |
| python_startup_no_site     | 6.92 ms                                                | 9.06 ms: 1.31x slower                                                  |
| scimark_sor                | 129 ms                                                 | 169 ms: 1.31x slower                                                   |
| coverage                   | 75.1 ms                                                | 101 ms: 1.34x slower                                                   |
| nbody                      | 92.2 ms                                                | 125 ms: 1.36x slower                                                   |
| unpack_sequence            | 54.2 ns                                                | 75.8 ns: 1.40x slower                                                  |
| Geometric mean             | (ref)                                                  | 1.07x slower                                                           |

Benchmark hidden because not significant (4): pickle, asyncio_websockets, pickle_dict, bench_mp_pool
Ignored benchmarks (6) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, dask, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.05x
- 95% likely to have a slowdown of 1.04x
- 99% likely to have a slowdown of 1.04x
