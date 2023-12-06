
# Results vs. 3.12.0

- fork: python
- ref: main
- machine: linux-x86_64
- commit hash: 66bea25
- commit date: 2023-10-29
- overall geometric mean: 1.02x faster
- HPT reliability: 99.96%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231029-linux-x86_64-python-main-3.13.0a1+-66bea25 |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| 2to3           | 274 ms                                                 | 265 ms: 1.04x faster                                   |
| chameleon      | 7.41 ms                                                | 6.93 ms: 1.07x faster                                  |
| docutils       | 2.75 sec                                               | 2.64 sec: 1.04x faster                                 |
| tornado_http   | 101 ms                                                 | 95.6 ms: 1.05x faster                                  |
| Geometric mean | (ref)                                                  | 1.05x faster                                           |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231029-linux-x86_64-python-main-3.13.0a1+-66bea25 |
|----------------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| async_tree_none            | 475 ms                                                 | 439 ms: 1.08x faster                                   |
| async_tree_memoization     | 580 ms                                                 | 563 ms: 1.03x faster                                   |
| async_tree_cpu_io_mixed    | 724 ms                                                 | 709 ms: 1.02x faster                                   |
| async_tree_none_tg         | 447 ms                                                 | 456 ms: 1.02x slower                                   |
| async_tree_io              | 1.16 sec                                               | 1.19 sec: 1.02x slower                                 |
| async_tree_cpu_io_mixed_tg | 725 ms                                                 | 744 ms: 1.03x slower                                   |
| async_tree_io_tg           | 1.19 sec                                               | 1.23 sec: 1.04x slower                                 |
| async_tree_memoization_tg  | 574 ms                                                 | 598 ms: 1.04x slower                                   |
| Geometric mean             | (ref)                                                  | 1.00x slower                                           |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231029-linux-x86_64-python-main-3.13.0a1+-66bea25 |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| float          | 83.3 ms                                                | 81.0 ms: 1.03x faster                                  |
| pidigits       | 187 ms                                                 | 187 ms: 1.00x slower                                   |
| nbody          | 92.2 ms                                                | 94.5 ms: 1.02x slower                                  |
| Geometric mean | (ref)                                                  | 1.00x faster                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231029-linux-x86_64-python-main-3.13.0a1+-66bea25 |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| regex_compile  | 148 ms                                                 | 136 ms: 1.09x faster                                   |
| regex_effbot   | 3.57 ms                                                | 3.63 ms: 1.02x slower                                  |
| regex_dna      | 209 ms                                                 | 219 ms: 1.05x slower                                   |
| regex_v8       | 22.7 ms                                                | 25.0 ms: 1.10x slower                                  |
| Geometric mean | (ref)                                                  | 1.02x slower                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231029-linux-x86_64-python-main-3.13.0a1+-66bea25 |
|----------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| pickle_pure_python   | 326 us                                                 | 302 us: 1.08x faster                                   |
| unpickle             | 15.8 us                                                | 14.6 us: 1.08x faster                                  |
| tomli_loads          | 2.30 sec                                               | 2.15 sec: 1.07x faster                                 |
| unpickle_pure_python | 230 us                                                 | 220 us: 1.04x faster                                   |
| xml_etree_process    | 61.2 ms                                                | 59.2 ms: 1.03x faster                                  |
| xml_etree_generate   | 88.7 ms                                                | 86.2 ms: 1.03x faster                                  |
| json_loads           | 28.4 us                                                | 27.8 us: 1.02x faster                                  |
| json_dumps           | 10.6 ms                                                | 10.5 ms: 1.01x faster                                  |
| pickle_dict          | 33.5 us                                                | 33.2 us: 1.01x faster                                  |
| pickle               | 11.2 us                                                | 11.3 us: 1.00x slower                                  |
| xml_etree_iterparse  | 106 ms                                                 | 106 ms: 1.00x slower                                   |
| unpickle_list        | 5.04 us                                                | 5.15 us: 1.02x slower                                  |
| pickle_list          | 4.67 us                                                | 4.81 us: 1.03x slower                                  |
| Geometric mean       | (ref)                                                  | 1.02x faster                                           |

Benchmark hidden because not significant (1): xml_etree_parse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231029-linux-x86_64-python-main-3.13.0a1+-66bea25 |
|------------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| python_startup         | 9.53 ms                                                | 10.3 ms: 1.08x slower                                  |
| python_startup_no_site | 6.92 ms                                                | 8.97 ms: 1.30x slower                                  |
| Geometric mean         | (ref)                                                  | 1.18x slower                                           |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231029-linux-x86_64-python-main-3.13.0a1+-66bea25 |
|-----------|:------------------------------------------------------:|:------------------------------------------------------:|
| mako      | 11.5 ms                                                | 11.5 ms: 1.00x slower                                  |

All benchmarks:
===============

| Benchmark                  | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231029-linux-x86_64-python-main-3.13.0a1+-66bea25 |
|----------------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| comprehensions             | 20.9 us                                                | 16.5 us: 1.27x faster                                  |
| crypto_pyaes               | 83.6 ms                                                | 72.2 ms: 1.16x faster                                  |
| unpack_sequence            | 54.2 ns                                                | 47.3 ns: 1.15x faster                                  |
| sympy_sum                  | 167 ms                                                 | 148 ms: 1.13x faster                                   |
| gc_traversal               | 4.28 ms                                                | 3.79 ms: 1.13x faster                                  |
| raytrace                   | 308 ms                                                 | 276 ms: 1.11x faster                                   |
| sympy_str                  | 296 ms                                                 | 268 ms: 1.10x faster                                   |
| generators                 | 32.5 ms                                                | 29.5 ms: 1.10x faster                                  |
| deltablue                  | 3.71 ms                                                | 3.40 ms: 1.09x faster                                  |
| chaos                      | 67.5 ms                                                | 62.0 ms: 1.09x faster                                  |
| regex_compile              | 148 ms                                                 | 136 ms: 1.09x faster                                   |
| logging_format             | 7.10 us                                                | 6.54 us: 1.08x faster                                  |
| scimark_monte_carlo        | 74.6 ms                                                | 68.8 ms: 1.08x faster                                  |
| async_tree_none            | 475 ms                                                 | 439 ms: 1.08x faster                                   |
| pickle_pure_python         | 326 us                                                 | 302 us: 1.08x faster                                   |
| scimark_sparse_mat_mult    | 5.33 ms                                                | 4.95 ms: 1.08x faster                                  |
| unpickle                   | 15.8 us                                                | 14.6 us: 1.08x faster                                  |
| nqueens                    | 86.2 ms                                                | 80.2 ms: 1.07x faster                                  |
| logging_simple             | 6.38 us                                                | 5.95 us: 1.07x faster                                  |
| tomli_loads                | 2.30 sec                                               | 2.15 sec: 1.07x faster                                 |
| chameleon                  | 7.41 ms                                                | 6.93 ms: 1.07x faster                                  |
| asyncio_tcp                | 506 ms                                                 | 474 ms: 1.07x faster                                   |
| sympy_integrate            | 21.2 ms                                                | 19.9 ms: 1.07x faster                                  |
| sqlglot_normalize          | 112 ms                                                 | 106 ms: 1.06x faster                                   |
| tornado_http               | 101 ms                                                 | 95.6 ms: 1.05x faster                                  |
| deepcopy_reduce            | 3.23 us                                                | 3.07 us: 1.05x faster                                  |
| sympy_expand               | 476 ms                                                 | 452 ms: 1.05x faster                                   |
| scimark_lu                 | 120 ms                                                 | 115 ms: 1.05x faster                                   |
| sqlglot_parse              | 1.35 ms                                                | 1.29 ms: 1.05x faster                                  |
| unpickle_pure_python       | 230 us                                                 | 220 us: 1.04x faster                                   |
| coroutines                 | 23.5 ms                                                | 22.5 ms: 1.04x faster                                  |
| docutils                   | 2.75 sec                                               | 2.64 sec: 1.04x faster                                 |
| hexiom                     | 6.54 ms                                                | 6.29 ms: 1.04x faster                                  |
| sqlglot_transpile          | 1.68 ms                                                | 1.61 ms: 1.04x faster                                  |
| bench_thread_pool          | 845 us                                                 | 815 us: 1.04x faster                                   |
| 2to3                       | 274 ms                                                 | 265 ms: 1.04x faster                                   |
| pprint_pformat             | 1.55 sec                                               | 1.50 sec: 1.04x faster                                 |
| pprint_safe_repr           | 765 ms                                                 | 738 ms: 1.04x faster                                   |
| xml_etree_process          | 61.2 ms                                                | 59.2 ms: 1.03x faster                                  |
| deepcopy                   | 363 us                                                 | 351 us: 1.03x faster                                   |
| scimark_fft                | 381 ms                                                 | 369 ms: 1.03x faster                                   |
| xml_etree_generate         | 88.7 ms                                                | 86.2 ms: 1.03x faster                                  |
| async_tree_memoization     | 580 ms                                                 | 563 ms: 1.03x faster                                   |
| float                      | 83.3 ms                                                | 81.0 ms: 1.03x faster                                  |
| sqlglot_optimize           | 54.8 ms                                                | 53.3 ms: 1.03x faster                                  |
| mypy2                      | 351 ms                                                 | 342 ms: 1.03x faster                                   |
| dulwich_log                | 68.7 ms                                                | 67.0 ms: 1.03x faster                                  |
| json                       | 5.22 ms                                                | 5.09 ms: 1.03x faster                                  |
| logging_silent             | 108 ns                                                 | 105 ns: 1.03x faster                                   |
| async_tree_cpu_io_mixed    | 724 ms                                                 | 709 ms: 1.02x faster                                   |
| json_loads                 | 28.4 us                                                | 27.8 us: 1.02x faster                                  |
| meteor_contest             | 110 ms                                                 | 108 ms: 1.02x faster                                   |
| pyflate                    | 471 ms                                                 | 462 ms: 1.02x faster                                   |
| deepcopy_memo              | 39.7 us                                                | 39.1 us: 1.02x faster                                  |
| scimark_sor                | 129 ms                                                 | 127 ms: 1.01x faster                                   |
| async_generators           | 459 ms                                                 | 454 ms: 1.01x faster                                   |
| mdp                        | 2.57 sec                                               | 2.54 sec: 1.01x faster                                 |
| json_dumps                 | 10.6 ms                                                | 10.5 ms: 1.01x faster                                  |
| typing_runtime_protocols   | 153 us                                                 | 152 us: 1.01x faster                                   |
| sqlite_synth               | 2.83 us                                                | 2.81 us: 1.01x faster                                  |
| spectral_norm              | 115 ms                                                 | 114 ms: 1.01x faster                                   |
| pickle_dict                | 33.5 us                                                | 33.2 us: 1.01x faster                                  |
| fannkuch                   | 410 ms                                                 | 408 ms: 1.00x faster                                   |
| mako                       | 11.5 ms                                                | 11.5 ms: 1.00x slower                                  |
| pidigits                   | 187 ms                                                 | 187 ms: 1.00x slower                                   |
| asyncio_tcp_ssl            | 1.78 sec                                               | 1.79 sec: 1.00x slower                                 |
| pickle                     | 11.2 us                                                | 11.3 us: 1.00x slower                                  |
| xml_etree_iterparse        | 106 ms                                                 | 106 ms: 1.00x slower                                   |
| create_gc_cycles           | 1.45 ms                                                | 1.47 ms: 1.01x slower                                  |
| pathlib                    | 18.9 ms                                                | 19.2 ms: 1.01x slower                                  |
| regex_effbot               | 3.57 ms                                                | 3.63 ms: 1.02x slower                                  |
| async_tree_none_tg         | 447 ms                                                 | 456 ms: 1.02x slower                                   |
| pycparser                  | 1.17 sec                                               | 1.19 sec: 1.02x slower                                 |
| unpickle_list              | 5.04 us                                                | 5.15 us: 1.02x slower                                  |
| async_tree_io              | 1.16 sec                                               | 1.19 sec: 1.02x slower                                 |
| nbody                      | 92.2 ms                                                | 94.5 ms: 1.02x slower                                  |
| async_tree_cpu_io_mixed_tg | 725 ms                                                 | 744 ms: 1.03x slower                                   |
| pickle_list                | 4.67 us                                                | 4.81 us: 1.03x slower                                  |
| go                         | 140 ms                                                 | 145 ms: 1.03x slower                                   |
| async_tree_io_tg           | 1.19 sec                                               | 1.23 sec: 1.04x slower                                 |
| async_tree_memoization_tg  | 574 ms                                                 | 598 ms: 1.04x slower                                   |
| regex_dna                  | 209 ms                                                 | 219 ms: 1.05x slower                                   |
| richards_super             | 51.9 ms                                                | 55.5 ms: 1.07x slower                                  |
| richards                   | 46.0 ms                                                | 49.6 ms: 1.08x slower                                  |
| python_startup             | 9.53 ms                                                | 10.3 ms: 1.08x slower                                  |
| regex_v8                   | 22.7 ms                                                | 25.0 ms: 1.10x slower                                  |
| telco                      | 7.18 ms                                                | 8.29 ms: 1.15x slower                                  |
| coverage                   | 75.1 ms                                                | 93.2 ms: 1.24x slower                                  |
| python_startup_no_site     | 6.92 ms                                                | 8.97 ms: 1.30x slower                                  |
| Geometric mean             | (ref)                                                  | 1.02x faster                                           |

Benchmark hidden because not significant (3): xml_etree_parse, asyncio_websockets, bench_mp_pool
Ignored benchmarks (6) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, dask, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 99.96% likely to be faster
- 90% likely to have a speedup of 1.01x
- 95% likely to have a speedup of 1.01x
- 99% likely to have a speedup of 1.00x
