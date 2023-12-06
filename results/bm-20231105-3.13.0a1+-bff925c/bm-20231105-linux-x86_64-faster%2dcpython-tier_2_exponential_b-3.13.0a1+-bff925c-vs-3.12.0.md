
# Results vs. 3.12.0

- fork: faster-cpython
- ref: tier_2_exponential_b
- machine: linux-x86_64
- commit hash: bff925c
- commit date: 2023-11-05
- overall geometric mean: 1.04x slower \*
- HPT reliability: 99.98%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231105-linux-x86_64-faster%2dcpython-tier_2_exponential_b-3.13.0a1+-bff925c |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| 2to3           | 274 ms                                                 | 283 ms: 1.03x slower                                                             |
| chameleon      | 7.41 ms                                                | 7.52 ms: 1.01x slower                                                            |
| docutils       | 2.75 sec                                               | 2.70 sec: 1.02x faster                                                           |
| tornado_http   | 101 ms                                                 | 99.2 ms: 1.01x faster                                                            |
| Geometric mean | (ref)                                                  | 1.00x slower                                                                     |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231105-linux-x86_64-faster%2dcpython-tier_2_exponential_b-3.13.0a1+-bff925c |
|----------------------------|:------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| async_tree_none            | 475 ms                                                 | 452 ms: 1.05x faster                                                             |
| async_tree_io              | 1.16 sec                                               | 1.20 sec: 1.03x slower                                                           |
| async_tree_none_tg         | 447 ms                                                 | 464 ms: 1.04x slower                                                             |
| async_tree_io_tg           | 1.19 sec                                               | 1.23 sec: 1.04x slower                                                           |
| async_tree_cpu_io_mixed_tg | 725 ms                                                 | 756 ms: 1.04x slower                                                             |
| async_tree_memoization_tg  | 574 ms                                                 | 604 ms: 1.05x slower                                                             |
| Geometric mean             | (ref)                                                  | 1.02x slower                                                                     |

Benchmark hidden because not significant (2): async_tree_memoization, async_tree_cpu_io_mixed

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231105-linux-x86_64-faster%2dcpython-tier_2_exponential_b-3.13.0a1+-bff925c |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| pidigits       | 187 ms                                                 | 188 ms: 1.00x slower                                                             |
| float          | 83.3 ms                                                | 105 ms: 1.25x slower                                                             |
| nbody          | 92.2 ms                                                | 126 ms: 1.36x slower                                                             |
| Geometric mean | (ref)                                                  | 1.20x slower                                                                     |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231105-linux-x86_64-faster%2dcpython-tier_2_exponential_b-3.13.0a1+-bff925c |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| regex_effbot   | 3.57 ms                                                | 3.61 ms: 1.01x slower                                                            |
| regex_dna      | 209 ms                                                 | 215 ms: 1.03x slower                                                             |
| regex_compile  | 148 ms                                                 | 158 ms: 1.07x slower                                                             |
| regex_v8       | 22.7 ms                                                | 25.9 ms: 1.14x slower                                                            |
| Geometric mean | (ref)                                                  | 1.06x slower                                                                     |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231105-linux-x86_64-faster%2dcpython-tier_2_exponential_b-3.13.0a1+-bff925c |
|----------------------|:------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| unpickle             | 15.8 us                                                | 14.7 us: 1.07x faster                                                            |
| pickle_pure_python   | 326 us                                                 | 314 us: 1.04x faster                                                             |
| xml_etree_process    | 61.2 ms                                                | 59.2 ms: 1.03x faster                                                            |
| xml_etree_generate   | 88.7 ms                                                | 86.4 ms: 1.03x faster                                                            |
| json_loads           | 28.4 us                                                | 27.8 us: 1.02x faster                                                            |
| xml_etree_parse      | 159 ms                                                 | 158 ms: 1.01x faster                                                             |
| pickle_dict          | 33.5 us                                                | 33.1 us: 1.01x faster                                                            |
| json_dumps           | 10.6 ms                                                | 10.5 ms: 1.01x faster                                                            |
| pickle               | 11.2 us                                                | 11.2 us: 1.01x faster                                                            |
| pickle_list          | 4.67 us                                                | 4.87 us: 1.04x slower                                                            |
| xml_etree_iterparse  | 106 ms                                                 | 111 ms: 1.05x slower                                                             |
| unpickle_pure_python | 230 us                                                 | 241 us: 1.05x slower                                                             |
| unpickle_list        | 5.04 us                                                | 5.53 us: 1.10x slower                                                            |
| tomli_loads          | 2.30 sec                                               | 2.57 sec: 1.12x slower                                                           |
| Geometric mean       | (ref)                                                  | 1.01x slower                                                                     |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231105-linux-x86_64-faster%2dcpython-tier_2_exponential_b-3.13.0a1+-bff925c |
|------------------------|:------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| python_startup         | 9.53 ms                                                | 10.3 ms: 1.08x slower                                                            |
| python_startup_no_site | 6.92 ms                                                | 8.96 ms: 1.30x slower                                                            |
| Geometric mean         | (ref)                                                  | 1.18x slower                                                                     |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231105-linux-x86_64-faster%2dcpython-tier_2_exponential_b-3.13.0a1+-bff925c |
|-----------|:------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| mako      | 11.5 ms                                                | 14.4 ms: 1.25x slower                                                            |

All benchmarks:
===============

| Benchmark                  | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231105-linux-x86_64-faster%2dcpython-tier_2_exponential_b-3.13.0a1+-bff925c |
|----------------------------|:------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| typing_runtime_protocols   | 153 us                                                 | 124 us: 1.23x faster                                                             |
| gc_traversal               | 4.28 ms                                                | 3.64 ms: 1.18x faster                                                            |
| unpack_sequence            | 54.2 ns                                                | 49.0 ns: 1.11x faster                                                            |
| generators                 | 32.5 ms                                                | 29.6 ms: 1.10x faster                                                            |
| sympy_sum                  | 167 ms                                                 | 153 ms: 1.09x faster                                                             |
| unpickle                   | 15.8 us                                                | 14.7 us: 1.07x faster                                                            |
| coroutines                 | 23.5 ms                                                | 22.2 ms: 1.06x faster                                                            |
| async_tree_none            | 475 ms                                                 | 452 ms: 1.05x faster                                                             |
| sympy_str                  | 296 ms                                                 | 282 ms: 1.05x faster                                                             |
| sqlglot_normalize          | 112 ms                                                 | 106 ms: 1.05x faster                                                             |
| pickle_pure_python         | 326 us                                                 | 314 us: 1.04x faster                                                             |
| xml_etree_process          | 61.2 ms                                                | 59.2 ms: 1.03x faster                                                            |
| asyncio_tcp                | 506 ms                                                 | 490 ms: 1.03x faster                                                             |
| deepcopy_reduce            | 3.23 us                                                | 3.13 us: 1.03x faster                                                            |
| logging_simple             | 6.38 us                                                | 6.20 us: 1.03x faster                                                            |
| sqlglot_parse              | 1.35 ms                                                | 1.31 ms: 1.03x faster                                                            |
| xml_etree_generate         | 88.7 ms                                                | 86.4 ms: 1.03x faster                                                            |
| spectral_norm              | 115 ms                                                 | 112 ms: 1.03x faster                                                             |
| deepcopy                   | 363 us                                                 | 355 us: 1.02x faster                                                             |
| sqlglot_transpile          | 1.68 ms                                                | 1.64 ms: 1.02x faster                                                            |
| json_loads                 | 28.4 us                                                | 27.8 us: 1.02x faster                                                            |
| docutils                   | 2.75 sec                                               | 2.70 sec: 1.02x faster                                                           |
| logging_format             | 7.10 us                                                | 6.97 us: 1.02x faster                                                            |
| tornado_http               | 101 ms                                                 | 99.2 ms: 1.01x faster                                                            |
| async_generators           | 459 ms                                                 | 454 ms: 1.01x faster                                                             |
| xml_etree_parse            | 159 ms                                                 | 158 ms: 1.01x faster                                                             |
| raytrace                   | 308 ms                                                 | 304 ms: 1.01x faster                                                             |
| pickle_dict                | 33.5 us                                                | 33.1 us: 1.01x faster                                                            |
| sqlglot_optimize           | 54.8 ms                                                | 54.3 ms: 1.01x faster                                                            |
| json_dumps                 | 10.6 ms                                                | 10.5 ms: 1.01x faster                                                            |
| pickle                     | 11.2 us                                                | 11.2 us: 1.01x faster                                                            |
| sympy_integrate            | 21.2 ms                                                | 21.1 ms: 1.00x faster                                                            |
| dulwich_log                | 68.7 ms                                                | 69.0 ms: 1.00x slower                                                            |
| pidigits                   | 187 ms                                                 | 188 ms: 1.00x slower                                                             |
| create_gc_cycles           | 1.45 ms                                                | 1.46 ms: 1.01x slower                                                            |
| sympy_expand               | 476 ms                                                 | 479 ms: 1.01x slower                                                             |
| mypy2                      | 351 ms                                                 | 354 ms: 1.01x slower                                                             |
| logging_silent             | 108 ns                                                 | 109 ns: 1.01x slower                                                             |
| bench_thread_pool          | 845 us                                                 | 854 us: 1.01x slower                                                             |
| regex_effbot               | 3.57 ms                                                | 3.61 ms: 1.01x slower                                                            |
| asyncio_tcp_ssl            | 1.78 sec                                               | 1.81 sec: 1.01x slower                                                           |
| chameleon                  | 7.41 ms                                                | 7.52 ms: 1.01x slower                                                            |
| scimark_sor                | 129 ms                                                 | 132 ms: 1.02x slower                                                             |
| regex_dna                  | 209 ms                                                 | 215 ms: 1.03x slower                                                             |
| async_tree_io              | 1.16 sec                                               | 1.20 sec: 1.03x slower                                                           |
| crypto_pyaes               | 83.6 ms                                                | 86.3 ms: 1.03x slower                                                            |
| 2to3                       | 274 ms                                                 | 283 ms: 1.03x slower                                                             |
| async_tree_none_tg         | 447 ms                                                 | 464 ms: 1.04x slower                                                             |
| async_tree_io_tg           | 1.19 sec                                               | 1.23 sec: 1.04x slower                                                           |
| pickle_list                | 4.67 us                                                | 4.87 us: 1.04x slower                                                            |
| pathlib                    | 18.9 ms                                                | 19.7 ms: 1.04x slower                                                            |
| async_tree_cpu_io_mixed_tg | 725 ms                                                 | 756 ms: 1.04x slower                                                             |
| pprint_safe_repr           | 765 ms                                                 | 801 ms: 1.05x slower                                                             |
| xml_etree_iterparse        | 106 ms                                                 | 111 ms: 1.05x slower                                                             |
| unpickle_pure_python       | 230 us                                                 | 241 us: 1.05x slower                                                             |
| async_tree_memoization_tg  | 574 ms                                                 | 604 ms: 1.05x slower                                                             |
| deepcopy_memo              | 39.7 us                                                | 42.0 us: 1.06x slower                                                            |
| meteor_contest             | 110 ms                                                 | 116 ms: 1.06x slower                                                             |
| pycparser                  | 1.17 sec                                               | 1.24 sec: 1.06x slower                                                           |
| pprint_pformat             | 1.55 sec                                               | 1.65 sec: 1.06x slower                                                           |
| regex_compile              | 148 ms                                                 | 158 ms: 1.07x slower                                                             |
| scimark_monte_carlo        | 74.6 ms                                                | 80.3 ms: 1.08x slower                                                            |
| python_startup             | 9.53 ms                                                | 10.3 ms: 1.08x slower                                                            |
| richards                   | 46.0 ms                                                | 49.6 ms: 1.08x slower                                                            |
| richards_super             | 51.9 ms                                                | 56.3 ms: 1.09x slower                                                            |
| mdp                        | 2.57 sec                                               | 2.79 sec: 1.09x slower                                                           |
| unpickle_list              | 5.04 us                                                | 5.53 us: 1.10x slower                                                            |
| chaos                      | 67.5 ms                                                | 74.8 ms: 1.11x slower                                                            |
| comprehensions             | 20.9 us                                                | 23.3 us: 1.11x slower                                                            |
| tomli_loads                | 2.30 sec                                               | 2.57 sec: 1.12x slower                                                           |
| nqueens                    | 86.2 ms                                                | 97.9 ms: 1.14x slower                                                            |
| fannkuch                   | 410 ms                                                 | 468 ms: 1.14x slower                                                             |
| regex_v8                   | 22.7 ms                                                | 25.9 ms: 1.14x slower                                                            |
| pyflate                    | 471 ms                                                 | 543 ms: 1.15x slower                                                             |
| scimark_fft                | 381 ms                                                 | 442 ms: 1.16x slower                                                             |
| go                         | 140 ms                                                 | 164 ms: 1.17x slower                                                             |
| scimark_sparse_mat_mult    | 5.33 ms                                                | 6.31 ms: 1.18x slower                                                            |
| telco                      | 7.18 ms                                                | 8.73 ms: 1.22x slower                                                            |
| mako                       | 11.5 ms                                                | 14.4 ms: 1.25x slower                                                            |
| float                      | 83.3 ms                                                | 105 ms: 1.25x slower                                                             |
| coverage                   | 75.1 ms                                                | 94.7 ms: 1.26x slower                                                            |
| python_startup_no_site     | 6.92 ms                                                | 8.96 ms: 1.30x slower                                                            |
| deltablue                  | 3.71 ms                                                | 4.90 ms: 1.32x slower                                                            |
| nbody                      | 92.2 ms                                                | 126 ms: 1.36x slower                                                             |
| hexiom                     | 6.54 ms                                                | 9.19 ms: 1.40x slower                                                            |
| Geometric mean             | (ref)                                                  | 1.04x slower                                                                     |

Benchmark hidden because not significant (7): json, async_tree_memoization, asyncio_websockets, sqlite_synth, bench_mp_pool, scimark_lu, async_tree_cpu_io_mixed
Ignored benchmarks (6) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, dask, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 99.98% likely to be slow
- 90% likely to have a slowdown of 1.01x
- 95% likely to have a slowdown of 1.01x
- 99% likely to have a slowdown of 1.00x
