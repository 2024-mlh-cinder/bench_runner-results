
# Results vs. 3.12.0

- fork: gvanrossum
- ref: gil_counter
- machine: linux-x86_64
- commit hash: c681cde
- commit date: 2023-11-15
- overall geometric mean: 1.02x slower \*
- HPT reliability: 99.95%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231115-linux-x86_64-gvanrossum-gil_counter-3.13.0a1+-c681cde |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------:|
| 2to3           | 274 ms                                                 | 285 ms: 1.04x slower                                              |
| chameleon      | 7.41 ms                                                | 7.77 ms: 1.05x slower                                             |
| docutils       | 2.75 sec                                               | 2.70 sec: 1.02x faster                                            |
| tornado_http   | 101 ms                                                 | 98.0 ms: 1.03x faster                                             |
| Geometric mean | (ref)                                                  | 1.01x slower                                                      |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231115-linux-x86_64-gvanrossum-gil_counter-3.13.0a1+-c681cde |
|----------------------------|:------------------------------------------------------:|:-----------------------------------------------------------------:|
| async_tree_none            | 475 ms                                                 | 444 ms: 1.07x faster                                              |
| async_tree_memoization     | 580 ms                                                 | 570 ms: 1.02x faster                                              |
| async_tree_io              | 1.16 sec                                               | 1.20 sec: 1.03x slower                                            |
| async_tree_none_tg         | 447 ms                                                 | 460 ms: 1.03x slower                                              |
| async_tree_io_tg           | 1.19 sec                                               | 1.23 sec: 1.03x slower                                            |
| async_tree_cpu_io_mixed_tg | 725 ms                                                 | 750 ms: 1.04x slower                                              |
| async_tree_memoization_tg  | 574 ms                                                 | 602 ms: 1.05x slower                                              |
| Geometric mean             | (ref)                                                  | 1.01x slower                                                      |

Benchmark hidden because not significant (1): async_tree_cpu_io_mixed

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231115-linux-x86_64-gvanrossum-gil_counter-3.13.0a1+-c681cde |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------:|
| pidigits       | 187 ms                                                 | 188 ms: 1.01x slower                                              |
| nbody          | 92.2 ms                                                | 102 ms: 1.10x slower                                              |
| Geometric mean | (ref)                                                  | 1.04x slower                                                      |

Benchmark hidden because not significant (1): float

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231115-linux-x86_64-gvanrossum-gil_counter-3.13.0a1+-c681cde |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------:|
| regex_effbot   | 3.57 ms                                                | 3.61 ms: 1.01x slower                                             |
| regex_compile  | 148 ms                                                 | 151 ms: 1.02x slower                                              |
| regex_dna      | 209 ms                                                 | 216 ms: 1.04x slower                                              |
| regex_v8       | 22.7 ms                                                | 26.3 ms: 1.16x slower                                             |
| Geometric mean | (ref)                                                  | 1.06x slower                                                      |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231115-linux-x86_64-gvanrossum-gil_counter-3.13.0a1+-c681cde |
|----------------------|:------------------------------------------------------:|:-----------------------------------------------------------------:|
| unpickle             | 15.8 us                                                | 14.9 us: 1.06x faster                                             |
| unpickle_list        | 5.04 us                                                | 4.93 us: 1.02x faster                                             |
| xml_etree_parse      | 159 ms                                                 | 159 ms: 1.01x faster                                              |
| json_loads           | 28.4 us                                                | 28.3 us: 1.00x faster                                             |
| xml_etree_generate   | 88.7 ms                                                | 89.1 ms: 1.00x slower                                             |
| xml_etree_process    | 61.2 ms                                                | 61.7 ms: 1.01x slower                                             |
| xml_etree_iterparse  | 106 ms                                                 | 107 ms: 1.01x slower                                              |
| pickle_dict          | 33.5 us                                                | 34.3 us: 1.02x slower                                             |
| pickle               | 11.2 us                                                | 11.6 us: 1.03x slower                                             |
| pickle_pure_python   | 326 us                                                 | 344 us: 1.05x slower                                              |
| tomli_loads          | 2.30 sec                                               | 2.46 sec: 1.07x slower                                            |
| unpickle_pure_python | 230 us                                                 | 246 us: 1.07x slower                                              |
| pickle_list          | 4.67 us                                                | 5.17 us: 1.11x slower                                             |
| Geometric mean       | (ref)                                                  | 1.02x slower                                                      |

Benchmark hidden because not significant (1): json_dumps

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231115-linux-x86_64-gvanrossum-gil_counter-3.13.0a1+-c681cde |
|------------------------|:------------------------------------------------------:|:-----------------------------------------------------------------:|
| python_startup         | 9.53 ms                                                | 10.4 ms: 1.09x slower                                             |
| python_startup_no_site | 6.92 ms                                                | 9.04 ms: 1.31x slower                                             |
| Geometric mean         | (ref)                                                  | 1.19x slower                                                      |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231115-linux-x86_64-gvanrossum-gil_counter-3.13.0a1+-c681cde |
|-----------|:------------------------------------------------------:|:-----------------------------------------------------------------:|
| mako      | 11.5 ms                                                | 12.0 ms: 1.05x slower                                             |

All benchmarks:
===============

| Benchmark                  | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231115-linux-x86_64-gvanrossum-gil_counter-3.13.0a1+-c681cde |
|----------------------------|:------------------------------------------------------:|:-----------------------------------------------------------------:|
| typing_runtime_protocols   | 153 us                                                 | 117 us: 1.31x faster                                              |
| gc_traversal               | 4.28 ms                                                | 3.64 ms: 1.17x faster                                             |
| comprehensions             | 20.9 us                                                | 18.2 us: 1.15x faster                                             |
| unpack_sequence            | 54.2 ns                                                | 48.3 ns: 1.12x faster                                             |
| logging_format             | 7.10 us                                                | 6.34 us: 1.12x faster                                             |
| logging_simple             | 6.38 us                                                | 5.74 us: 1.11x faster                                             |
| sympy_sum                  | 167 ms                                                 | 153 ms: 1.10x faster                                              |
| async_tree_none            | 475 ms                                                 | 444 ms: 1.07x faster                                              |
| unpickle                   | 15.8 us                                                | 14.9 us: 1.06x faster                                             |
| sympy_str                  | 296 ms                                                 | 281 ms: 1.05x faster                                              |
| crypto_pyaes               | 83.6 ms                                                | 80.3 ms: 1.04x faster                                             |
| scimark_sparse_mat_mult    | 5.33 ms                                                | 5.17 ms: 1.03x faster                                             |
| sympy_integrate            | 21.2 ms                                                | 20.6 ms: 1.03x faster                                             |
| tornado_http               | 101 ms                                                 | 98.0 ms: 1.03x faster                                             |
| unpickle_list              | 5.04 us                                                | 4.93 us: 1.02x faster                                             |
| asyncio_tcp                | 506 ms                                                 | 494 ms: 1.02x faster                                              |
| docutils                   | 2.75 sec                                               | 2.70 sec: 1.02x faster                                            |
| nqueens                    | 86.2 ms                                                | 84.6 ms: 1.02x faster                                             |
| sympy_expand               | 476 ms                                                 | 467 ms: 1.02x faster                                              |
| scimark_monte_carlo        | 74.6 ms                                                | 73.4 ms: 1.02x faster                                             |
| async_tree_memoization     | 580 ms                                                 | 570 ms: 1.02x faster                                              |
| async_generators           | 459 ms                                                 | 452 ms: 1.02x faster                                              |
| chaos                      | 67.5 ms                                                | 66.6 ms: 1.01x faster                                             |
| pathlib                    | 18.9 ms                                                | 18.7 ms: 1.01x faster                                             |
| generators                 | 32.5 ms                                                | 32.1 ms: 1.01x faster                                             |
| json                       | 5.22 ms                                                | 5.17 ms: 1.01x faster                                             |
| dulwich_log                | 68.7 ms                                                | 68.3 ms: 1.01x faster                                             |
| xml_etree_parse            | 159 ms                                                 | 159 ms: 1.01x faster                                              |
| raytrace                   | 308 ms                                                 | 306 ms: 1.00x faster                                              |
| json_loads                 | 28.4 us                                                | 28.3 us: 1.00x faster                                             |
| sqlglot_normalize          | 112 ms                                                 | 111 ms: 1.00x faster                                              |
| xml_etree_generate         | 88.7 ms                                                | 89.1 ms: 1.00x slower                                             |
| mdp                        | 2.57 sec                                               | 2.58 sec: 1.01x slower                                            |
| pidigits                   | 187 ms                                                 | 188 ms: 1.01x slower                                              |
| coroutines                 | 23.5 ms                                                | 23.6 ms: 1.01x slower                                             |
| xml_etree_process          | 61.2 ms                                                | 61.7 ms: 1.01x slower                                             |
| create_gc_cycles           | 1.45 ms                                                | 1.46 ms: 1.01x slower                                             |
| xml_etree_iterparse        | 106 ms                                                 | 107 ms: 1.01x slower                                              |
| asyncio_tcp_ssl            | 1.78 sec                                               | 1.80 sec: 1.01x slower                                            |
| regex_effbot               | 3.57 ms                                                | 3.61 ms: 1.01x slower                                             |
| scimark_lu                 | 120 ms                                                 | 122 ms: 1.01x slower                                              |
| deepcopy_reduce            | 3.23 us                                                | 3.28 us: 1.02x slower                                             |
| scimark_fft                | 381 ms                                                 | 387 ms: 1.02x slower                                              |
| mypy2                      | 351 ms                                                 | 357 ms: 1.02x slower                                              |
| regex_compile              | 148 ms                                                 | 151 ms: 1.02x slower                                              |
| bench_thread_pool          | 845 us                                                 | 862 us: 1.02x slower                                              |
| deltablue                  | 3.71 ms                                                | 3.78 ms: 1.02x slower                                             |
| meteor_contest             | 110 ms                                                 | 112 ms: 1.02x slower                                              |
| pickle_dict                | 33.5 us                                                | 34.3 us: 1.02x slower                                             |
| async_tree_io              | 1.16 sec                                               | 1.20 sec: 1.03x slower                                            |
| async_tree_none_tg         | 447 ms                                                 | 460 ms: 1.03x slower                                              |
| pickle                     | 11.2 us                                                | 11.6 us: 1.03x slower                                             |
| async_tree_io_tg           | 1.19 sec                                               | 1.23 sec: 1.03x slower                                            |
| async_tree_cpu_io_mixed_tg | 725 ms                                                 | 750 ms: 1.04x slower                                              |
| regex_dna                  | 209 ms                                                 | 216 ms: 1.04x slower                                              |
| sqlglot_optimize           | 54.8 ms                                                | 56.9 ms: 1.04x slower                                             |
| 2to3                       | 274 ms                                                 | 285 ms: 1.04x slower                                              |
| scimark_sor                | 129 ms                                                 | 135 ms: 1.04x slower                                              |
| mako                       | 11.5 ms                                                | 12.0 ms: 1.05x slower                                             |
| async_tree_memoization_tg  | 574 ms                                                 | 602 ms: 1.05x slower                                              |
| chameleon                  | 7.41 ms                                                | 7.77 ms: 1.05x slower                                             |
| pickle_pure_python         | 326 us                                                 | 344 us: 1.05x slower                                              |
| pprint_safe_repr           | 765 ms                                                 | 810 ms: 1.06x slower                                              |
| fannkuch                   | 410 ms                                                 | 435 ms: 1.06x slower                                              |
| deepcopy                   | 363 us                                                 | 385 us: 1.06x slower                                              |
| deepcopy_memo              | 39.7 us                                                | 42.3 us: 1.06x slower                                             |
| pprint_pformat             | 1.55 sec                                               | 1.65 sec: 1.07x slower                                            |
| sqlglot_transpile          | 1.68 ms                                                | 1.79 ms: 1.07x slower                                             |
| pyflate                    | 471 ms                                                 | 502 ms: 1.07x slower                                              |
| spectral_norm              | 115 ms                                                 | 123 ms: 1.07x slower                                              |
| tomli_loads                | 2.30 sec                                               | 2.46 sec: 1.07x slower                                            |
| logging_silent             | 108 ns                                                 | 115 ns: 1.07x slower                                              |
| unpickle_pure_python       | 230 us                                                 | 246 us: 1.07x slower                                              |
| sqlglot_parse              | 1.35 ms                                                | 1.46 ms: 1.08x slower                                             |
| python_startup             | 9.53 ms                                                | 10.4 ms: 1.09x slower                                             |
| nbody                      | 92.2 ms                                                | 102 ms: 1.10x slower                                              |
| pickle_list                | 4.67 us                                                | 5.17 us: 1.11x slower                                             |
| hexiom                     | 6.54 ms                                                | 7.27 ms: 1.11x slower                                             |
| pycparser                  | 1.17 sec                                               | 1.31 sec: 1.12x slower                                            |
| regex_v8                   | 22.7 ms                                                | 26.3 ms: 1.16x slower                                             |
| go                         | 140 ms                                                 | 163 ms: 1.16x slower                                              |
| telco                      | 7.18 ms                                                | 8.44 ms: 1.18x slower                                             |
| richards                   | 46.0 ms                                                | 57.3 ms: 1.25x slower                                             |
| richards_super             | 51.9 ms                                                | 65.2 ms: 1.26x slower                                             |
| coverage                   | 75.1 ms                                                | 95.8 ms: 1.28x slower                                             |
| python_startup_no_site     | 6.92 ms                                                | 9.04 ms: 1.31x slower                                             |
| Geometric mean             | (ref)                                                  | 1.02x slower                                                      |

Benchmark hidden because not significant (6): async_tree_cpu_io_mixed, sqlite_synth, json_dumps, asyncio_websockets, bench_mp_pool, float
Ignored benchmarks (6) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, dask, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 99.95% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
