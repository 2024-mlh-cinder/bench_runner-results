
# Results vs. 3.12.0

- fork: python
- ref: 48dfd74a9db9d4aa9c6f
- machine: linux-x86_64
- commit hash: 48dfd74
- commit date: 2023-11-28
- overall geometric mean: 1.02x faster \*
- HPT reliability: 99.99%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231128-linux-x86_64-python-48dfd74a9db9d4aa9c6f-3.13.0a2+-48dfd74 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| 2to3           | 274 ms                                                 | 264 ms: 1.04x faster                                                   |
| chameleon      | 7.41 ms                                                | 7.06 ms: 1.05x faster                                                  |
| docutils       | 2.75 sec                                               | 2.60 sec: 1.06x faster                                                 |
| tornado_http   | 101 ms                                                 | 94.9 ms: 1.06x faster                                                  |
| Geometric mean | (ref)                                                  | 1.05x faster                                                           |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231128-linux-x86_64-python-48dfd74a9db9d4aa9c6f-3.13.0a2+-48dfd74 |
|----------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| async_tree_none            | 475 ms                                                 | 436 ms: 1.09x faster                                                   |
| async_tree_memoization     | 580 ms                                                 | 558 ms: 1.04x faster                                                   |
| async_tree_cpu_io_mixed    | 724 ms                                                 | 706 ms: 1.03x faster                                                   |
| async_tree_none_tg         | 447 ms                                                 | 453 ms: 1.01x slower                                                   |
| async_tree_io              | 1.16 sec                                               | 1.19 sec: 1.02x slower                                                 |
| async_tree_io_tg           | 1.19 sec                                               | 1.21 sec: 1.02x slower                                                 |
| async_tree_cpu_io_mixed_tg | 725 ms                                                 | 739 ms: 1.02x slower                                                   |
| async_tree_memoization_tg  | 574 ms                                                 | 590 ms: 1.03x slower                                                   |
| Geometric mean             | (ref)                                                  | 1.01x faster                                                           |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231128-linux-x86_64-python-48dfd74a9db9d4aa9c6f-3.13.0a2+-48dfd74 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| float          | 83.3 ms                                                | 81.5 ms: 1.02x faster                                                  |
| pidigits       | 187 ms                                                 | 187 ms: 1.00x slower                                                   |
| Geometric mean | (ref)                                                  | 1.01x faster                                                           |

Benchmark hidden because not significant (1): nbody

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231128-linux-x86_64-python-48dfd74a9db9d4aa9c6f-3.13.0a2+-48dfd74 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| regex_compile  | 148 ms                                                 | 135 ms: 1.10x faster                                                   |
| regex_effbot   | 3.57 ms                                                | 3.62 ms: 1.01x slower                                                  |
| regex_dna      | 209 ms                                                 | 215 ms: 1.03x slower                                                   |
| regex_v8       | 22.7 ms                                                | 25.7 ms: 1.14x slower                                                  |
| Geometric mean | (ref)                                                  | 1.02x slower                                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231128-linux-x86_64-python-48dfd74a9db9d4aa9c6f-3.13.0a2+-48dfd74 |
|----------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| pickle_pure_python   | 326 us                                                 | 302 us: 1.08x faster                                                   |
| tomli_loads          | 2.30 sec                                               | 2.15 sec: 1.07x faster                                                 |
| unpickle_pure_python | 230 us                                                 | 216 us: 1.06x faster                                                   |
| xml_etree_process    | 61.2 ms                                                | 59.7 ms: 1.03x faster                                                  |
| unpickle             | 15.8 us                                                | 15.4 us: 1.02x faster                                                  |
| xml_etree_generate   | 88.7 ms                                                | 87.6 ms: 1.01x faster                                                  |
| xml_etree_parse      | 159 ms                                                 | 158 ms: 1.01x faster                                                   |
| json_dumps           | 10.6 ms                                                | 10.5 ms: 1.01x faster                                                  |
| pickle               | 11.2 us                                                | 11.1 us: 1.01x faster                                                  |
| pickle_dict          | 33.5 us                                                | 33.4 us: 1.00x faster                                                  |
| unpickle_list        | 5.04 us                                                | 5.25 us: 1.04x slower                                                  |
| pickle_list          | 4.67 us                                                | 5.10 us: 1.09x slower                                                  |
| Geometric mean       | (ref)                                                  | 1.01x faster                                                           |

Benchmark hidden because not significant (2): xml_etree_iterparse, json_loads

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231128-linux-x86_64-python-48dfd74a9db9d4aa9c6f-3.13.0a2+-48dfd74 |
|------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| python_startup         | 9.53 ms                                                | 10.3 ms: 1.08x slower                                                  |
| python_startup_no_site | 6.92 ms                                                | 8.98 ms: 1.30x slower                                                  |
| Geometric mean         | (ref)                                                  | 1.19x slower                                                           |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231128-linux-x86_64-python-48dfd74a9db9d4aa9c6f-3.13.0a2+-48dfd74 |
|-----------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| mako      | 11.5 ms                                                | 11.6 ms: 1.01x slower                                                  |

All benchmarks:
===============

| Benchmark                  | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231128-linux-x86_64-python-48dfd74a9db9d4aa9c6f-3.13.0a2+-48dfd74 |
|----------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| typing_runtime_protocols   | 153 us                                                 | 119 us: 1.29x faster                                                   |
| comprehensions             | 20.9 us                                                | 16.4 us: 1.28x faster                                                  |
| unpack_sequence            | 54.2 ns                                                | 45.9 ns: 1.18x faster                                                  |
| gc_traversal               | 4.28 ms                                                | 3.64 ms: 1.17x faster                                                  |
| crypto_pyaes               | 83.6 ms                                                | 71.4 ms: 1.17x faster                                                  |
| sympy_sum                  | 167 ms                                                 | 147 ms: 1.14x faster                                                   |
| deltablue                  | 3.71 ms                                                | 3.29 ms: 1.13x faster                                                  |
| logging_format             | 7.10 us                                                | 6.32 us: 1.12x faster                                                  |
| sympy_str                  | 296 ms                                                 | 268 ms: 1.11x faster                                                   |
| raytrace                   | 308 ms                                                 | 279 ms: 1.10x faster                                                   |
| logging_simple             | 6.38 us                                                | 5.80 us: 1.10x faster                                                  |
| regex_compile              | 148 ms                                                 | 135 ms: 1.10x faster                                                   |
| chaos                      | 67.5 ms                                                | 61.8 ms: 1.09x faster                                                  |
| generators                 | 32.5 ms                                                | 29.8 ms: 1.09x faster                                                  |
| async_tree_none            | 475 ms                                                 | 436 ms: 1.09x faster                                                   |
| scimark_monte_carlo        | 74.6 ms                                                | 68.6 ms: 1.09x faster                                                  |
| sympy_integrate            | 21.2 ms                                                | 19.5 ms: 1.09x faster                                                  |
| hexiom                     | 6.54 ms                                                | 6.02 ms: 1.09x faster                                                  |
| pickle_pure_python         | 326 us                                                 | 302 us: 1.08x faster                                                   |
| nqueens                    | 86.2 ms                                                | 80.1 ms: 1.08x faster                                                  |
| tomli_loads                | 2.30 sec                                               | 2.15 sec: 1.07x faster                                                 |
| scimark_sparse_mat_mult    | 5.33 ms                                                | 5.00 ms: 1.07x faster                                                  |
| coroutines                 | 23.5 ms                                                | 22.1 ms: 1.06x faster                                                  |
| tornado_http               | 101 ms                                                 | 94.9 ms: 1.06x faster                                                  |
| unpickle_pure_python       | 230 us                                                 | 216 us: 1.06x faster                                                   |
| docutils                   | 2.75 sec                                               | 2.60 sec: 1.06x faster                                                 |
| sqlglot_parse              | 1.35 ms                                                | 1.28 ms: 1.06x faster                                                  |
| sqlglot_transpile          | 1.68 ms                                                | 1.59 ms: 1.05x faster                                                  |
| chameleon                  | 7.41 ms                                                | 7.06 ms: 1.05x faster                                                  |
| dulwich_log                | 68.7 ms                                                | 65.5 ms: 1.05x faster                                                  |
| pathlib                    | 18.9 ms                                                | 18.0 ms: 1.05x faster                                                  |
| scimark_lu                 | 120 ms                                                 | 115 ms: 1.04x faster                                                   |
| sqlglot_normalize          | 112 ms                                                 | 107 ms: 1.04x faster                                                   |
| scimark_sor                | 129 ms                                                 | 124 ms: 1.04x faster                                                   |
| 2to3                       | 274 ms                                                 | 264 ms: 1.04x faster                                                   |
| sympy_expand               | 476 ms                                                 | 457 ms: 1.04x faster                                                   |
| asyncio_tcp                | 506 ms                                                 | 486 ms: 1.04x faster                                                   |
| deepcopy                   | 363 us                                                 | 349 us: 1.04x faster                                                   |
| async_tree_memoization     | 580 ms                                                 | 558 ms: 1.04x faster                                                   |
| pprint_safe_repr           | 765 ms                                                 | 737 ms: 1.04x faster                                                   |
| deepcopy_reduce            | 3.23 us                                                | 3.12 us: 1.04x faster                                                  |
| pyflate                    | 471 ms                                                 | 456 ms: 1.03x faster                                                   |
| spectral_norm              | 115 ms                                                 | 111 ms: 1.03x faster                                                   |
| async_generators           | 459 ms                                                 | 445 ms: 1.03x faster                                                   |
| pprint_pformat             | 1.55 sec                                               | 1.50 sec: 1.03x faster                                                 |
| scimark_fft                | 381 ms                                                 | 369 ms: 1.03x faster                                                   |
| async_tree_cpu_io_mixed    | 724 ms                                                 | 706 ms: 1.03x faster                                                   |
| dask                       | 369 ms                                                 | 360 ms: 1.03x faster                                                   |
| xml_etree_process          | 61.2 ms                                                | 59.7 ms: 1.03x faster                                                  |
| logging_silent             | 108 ns                                                 | 105 ns: 1.02x faster                                                   |
| float                      | 83.3 ms                                                | 81.5 ms: 1.02x faster                                                  |
| unpickle                   | 15.8 us                                                | 15.4 us: 1.02x faster                                                  |
| sqlglot_optimize           | 54.8 ms                                                | 53.9 ms: 1.02x faster                                                  |
| fannkuch                   | 410 ms                                                 | 404 ms: 1.02x faster                                                   |
| bench_thread_pool          | 845 us                                                 | 832 us: 1.02x faster                                                   |
| xml_etree_generate         | 88.7 ms                                                | 87.6 ms: 1.01x faster                                                  |
| json                       | 5.22 ms                                                | 5.16 ms: 1.01x faster                                                  |
| meteor_contest             | 110 ms                                                 | 108 ms: 1.01x faster                                                   |
| deepcopy_memo              | 39.7 us                                                | 39.3 us: 1.01x faster                                                  |
| mdp                        | 2.57 sec                                               | 2.54 sec: 1.01x faster                                                 |
| xml_etree_parse            | 159 ms                                                 | 158 ms: 1.01x faster                                                   |
| json_dumps                 | 10.6 ms                                                | 10.5 ms: 1.01x faster                                                  |
| pickle                     | 11.2 us                                                | 11.1 us: 1.01x faster                                                  |
| pickle_dict                | 33.5 us                                                | 33.4 us: 1.00x faster                                                  |
| pidigits                   | 187 ms                                                 | 187 ms: 1.00x slower                                                   |
| asyncio_tcp_ssl            | 1.78 sec                                               | 1.78 sec: 1.00x slower                                                 |
| mako                       | 11.5 ms                                                | 11.6 ms: 1.01x slower                                                  |
| go                         | 140 ms                                                 | 142 ms: 1.01x slower                                                   |
| create_gc_cycles           | 1.45 ms                                                | 1.46 ms: 1.01x slower                                                  |
| async_tree_none_tg         | 447 ms                                                 | 453 ms: 1.01x slower                                                   |
| regex_effbot               | 3.57 ms                                                | 3.62 ms: 1.01x slower                                                  |
| async_tree_io              | 1.16 sec                                               | 1.19 sec: 1.02x slower                                                 |
| async_tree_io_tg           | 1.19 sec                                               | 1.21 sec: 1.02x slower                                                 |
| async_tree_cpu_io_mixed_tg | 725 ms                                                 | 739 ms: 1.02x slower                                                   |
| async_tree_memoization_tg  | 574 ms                                                 | 590 ms: 1.03x slower                                                   |
| richards                   | 46.0 ms                                                | 47.4 ms: 1.03x slower                                                  |
| regex_dna                  | 209 ms                                                 | 215 ms: 1.03x slower                                                   |
| pycparser                  | 1.17 sec                                               | 1.21 sec: 1.04x slower                                                 |
| unpickle_list              | 5.04 us                                                | 5.25 us: 1.04x slower                                                  |
| richards_super             | 51.9 ms                                                | 54.1 ms: 1.04x slower                                                  |
| python_startup             | 9.53 ms                                                | 10.3 ms: 1.08x slower                                                  |
| pickle_list                | 4.67 us                                                | 5.10 us: 1.09x slower                                                  |
| regex_v8                   | 22.7 ms                                                | 25.7 ms: 1.14x slower                                                  |
| telco                      | 7.18 ms                                                | 8.42 ms: 1.17x slower                                                  |
| coverage                   | 75.1 ms                                                | 95.5 ms: 1.27x slower                                                  |
| python_startup_no_site     | 6.92 ms                                                | 8.98 ms: 1.30x slower                                                  |
| mypy2                      | 351 ms                                                 | 842 ms: 2.40x slower                                                   |
| Geometric mean             | (ref)                                                  | 1.02x faster                                                           |

Benchmark hidden because not significant (6): nbody, xml_etree_iterparse, sqlite_synth, bench_mp_pool, json_loads, asyncio_websockets
Ignored benchmarks (5) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 99.99% likely to be faster
- 90% likely to have a speedup of 1.01x
- 95% likely to have a speedup of 1.01x
- 99% likely to have a speedup of 1.00x
