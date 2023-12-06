
# Results vs. 3.12.0

- fork: faster-cpython
- ref: optimize_globals_to_
- machine: linux-x86_64
- commit hash: 58d77db
- commit date: 2023-11-16
- overall geometric mean: 1.05x slower \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.01x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231116-linux-x86_64-faster%2dcpython-optimize_globals_to_-3.13.0a1+-58d77db |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| 2to3           | 274 ms                                                 | 285 ms: 1.04x slower                                                             |
| docutils       | 2.75 sec                                               | 2.70 sec: 1.02x faster                                                           |
| tornado_http   | 101 ms                                                 | 99.9 ms: 1.01x faster                                                            |
| Geometric mean | (ref)                                                  | 1.00x slower                                                                     |

Benchmark hidden because not significant (1): chameleon

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231116-linux-x86_64-faster%2dcpython-optimize_globals_to_-3.13.0a1+-58d77db |
|----------------------------|:------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| async_tree_none            | 475 ms                                                 | 460 ms: 1.03x faster                                                             |
| async_tree_cpu_io_mixed    | 724 ms                                                 | 734 ms: 1.01x slower                                                             |
| async_tree_memoization     | 580 ms                                                 | 588 ms: 1.01x slower                                                             |
| async_tree_none_tg         | 447 ms                                                 | 470 ms: 1.05x slower                                                             |
| async_tree_cpu_io_mixed_tg | 725 ms                                                 | 762 ms: 1.05x slower                                                             |
| async_tree_io              | 1.16 sec                                               | 1.23 sec: 1.05x slower                                                           |
| async_tree_io_tg           | 1.19 sec                                               | 1.26 sec: 1.06x slower                                                           |
| async_tree_memoization_tg  | 574 ms                                                 | 610 ms: 1.06x slower                                                             |
| Geometric mean             | (ref)                                                  | 1.03x slower                                                                     |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231116-linux-x86_64-faster%2dcpython-optimize_globals_to_-3.13.0a1+-58d77db |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| pidigits       | 187 ms                                                 | 188 ms: 1.01x slower                                                             |
| float          | 83.3 ms                                                | 101 ms: 1.22x slower                                                             |
| nbody          | 92.2 ms                                                | 114 ms: 1.24x slower                                                             |
| Geometric mean | (ref)                                                  | 1.15x slower                                                                     |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231116-linux-x86_64-faster%2dcpython-optimize_globals_to_-3.13.0a1+-58d77db |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| regex_effbot   | 3.57 ms                                                | 3.62 ms: 1.01x slower                                                            |
| regex_dna      | 209 ms                                                 | 217 ms: 1.04x slower                                                             |
| regex_compile  | 148 ms                                                 | 162 ms: 1.09x slower                                                             |
| regex_v8       | 22.7 ms                                                | 24.8 ms: 1.09x slower                                                            |
| Geometric mean | (ref)                                                  | 1.06x slower                                                                     |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231116-linux-x86_64-faster%2dcpython-optimize_globals_to_-3.13.0a1+-58d77db |
|----------------------|:------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| unpickle             | 15.8 us                                                | 14.8 us: 1.06x faster                                                            |
| pickle_pure_python   | 326 us                                                 | 308 us: 1.06x faster                                                             |
| xml_etree_process    | 61.2 ms                                                | 59.4 ms: 1.03x faster                                                            |
| xml_etree_generate   | 88.7 ms                                                | 87.7 ms: 1.01x faster                                                            |
| json_loads           | 28.4 us                                                | 28.2 us: 1.01x faster                                                            |
| json_dumps           | 10.6 ms                                                | 10.5 ms: 1.01x faster                                                            |
| xml_etree_parse      | 159 ms                                                 | 159 ms: 1.01x faster                                                             |
| unpickle_list        | 5.04 us                                                | 5.06 us: 1.00x slower                                                            |
| pickle               | 11.2 us                                                | 11.7 us: 1.04x slower                                                            |
| xml_etree_iterparse  | 106 ms                                                 | 112 ms: 1.06x slower                                                             |
| unpickle_pure_python | 230 us                                                 | 248 us: 1.08x slower                                                             |
| pickle_dict          | 33.5 us                                                | 36.3 us: 1.08x slower                                                            |
| pickle_list          | 4.67 us                                                | 5.08 us: 1.09x slower                                                            |
| tomli_loads          | 2.30 sec                                               | 2.86 sec: 1.24x slower                                                           |
| Geometric mean       | (ref)                                                  | 1.03x slower                                                                     |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231116-linux-x86_64-faster%2dcpython-optimize_globals_to_-3.13.0a1+-58d77db |
|------------------------|:------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| python_startup         | 9.53 ms                                                | 10.4 ms: 1.09x slower                                                            |
| python_startup_no_site | 6.92 ms                                                | 9.08 ms: 1.31x slower                                                            |
| Geometric mean         | (ref)                                                  | 1.20x slower                                                                     |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231116-linux-x86_64-faster%2dcpython-optimize_globals_to_-3.13.0a1+-58d77db |
|-----------|:------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| mako      | 11.5 ms                                                | 14.7 ms: 1.28x slower                                                            |

All benchmarks:
===============

| Benchmark                  | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231116-linux-x86_64-faster%2dcpython-optimize_globals_to_-3.13.0a1+-58d77db |
|----------------------------|:------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| typing_runtime_protocols   | 153 us                                                 | 123 us: 1.25x faster                                                             |
| unpack_sequence            | 54.2 ns                                                | 47.3 ns: 1.15x faster                                                            |
| gc_traversal               | 4.28 ms                                                | 3.82 ms: 1.12x faster                                                            |
| sympy_sum                  | 167 ms                                                 | 154 ms: 1.08x faster                                                             |
| generators                 | 32.5 ms                                                | 30.2 ms: 1.08x faster                                                            |
| unpickle                   | 15.8 us                                                | 14.8 us: 1.06x faster                                                            |
| pickle_pure_python         | 326 us                                                 | 308 us: 1.06x faster                                                             |
| coroutines                 | 23.5 ms                                                | 22.3 ms: 1.05x faster                                                            |
| sympy_str                  | 296 ms                                                 | 284 ms: 1.04x faster                                                             |
| async_tree_none            | 475 ms                                                 | 460 ms: 1.03x faster                                                             |
| xml_etree_process          | 61.2 ms                                                | 59.4 ms: 1.03x faster                                                            |
| sqlglot_normalize          | 112 ms                                                 | 109 ms: 1.03x faster                                                             |
| logging_simple             | 6.38 us                                                | 6.22 us: 1.03x faster                                                            |
| deepcopy                   | 363 us                                                 | 355 us: 1.02x faster                                                             |
| deepcopy_reduce            | 3.23 us                                                | 3.16 us: 1.02x faster                                                            |
| pathlib                    | 18.9 ms                                                | 18.5 ms: 1.02x faster                                                            |
| asyncio_tcp                | 506 ms                                                 | 496 ms: 1.02x faster                                                             |
| logging_format             | 7.10 us                                                | 6.96 us: 1.02x faster                                                            |
| docutils                   | 2.75 sec                                               | 2.70 sec: 1.02x faster                                                           |
| spectral_norm              | 115 ms                                                 | 113 ms: 1.02x faster                                                             |
| json                       | 5.22 ms                                                | 5.15 ms: 1.01x faster                                                            |
| xml_etree_generate         | 88.7 ms                                                | 87.7 ms: 1.01x faster                                                            |
| raytrace                   | 308 ms                                                 | 305 ms: 1.01x faster                                                             |
| json_loads                 | 28.4 us                                                | 28.2 us: 1.01x faster                                                            |
| json_dumps                 | 10.6 ms                                                | 10.5 ms: 1.01x faster                                                            |
| tornado_http               | 101 ms                                                 | 99.9 ms: 1.01x faster                                                            |
| xml_etree_parse            | 159 ms                                                 | 159 ms: 1.01x faster                                                             |
| sqlglot_parse              | 1.35 ms                                                | 1.34 ms: 1.00x faster                                                            |
| logging_silent             | 108 ns                                                 | 107 ns: 1.00x faster                                                             |
| unpickle_list              | 5.04 us                                                | 5.06 us: 1.00x slower                                                            |
| pidigits                   | 187 ms                                                 | 188 ms: 1.01x slower                                                             |
| dulwich_log                | 68.7 ms                                                | 69.2 ms: 1.01x slower                                                            |
| sympy_expand               | 476 ms                                                 | 480 ms: 1.01x slower                                                             |
| asyncio_tcp_ssl            | 1.78 sec                                               | 1.80 sec: 1.01x slower                                                           |
| async_generators           | 459 ms                                                 | 464 ms: 1.01x slower                                                             |
| mypy2                      | 351 ms                                                 | 355 ms: 1.01x slower                                                             |
| sympy_integrate            | 21.2 ms                                                | 21.5 ms: 1.01x slower                                                            |
| bench_thread_pool          | 845 us                                                 | 856 us: 1.01x slower                                                             |
| regex_effbot               | 3.57 ms                                                | 3.62 ms: 1.01x slower                                                            |
| async_tree_cpu_io_mixed    | 724 ms                                                 | 734 ms: 1.01x slower                                                             |
| async_tree_memoization     | 580 ms                                                 | 588 ms: 1.01x slower                                                             |
| crypto_pyaes               | 83.6 ms                                                | 84.9 ms: 1.02x slower                                                            |
| create_gc_cycles           | 1.45 ms                                                | 1.48 ms: 1.02x slower                                                            |
| scimark_lu                 | 120 ms                                                 | 123 ms: 1.02x slower                                                             |
| sqlite_synth               | 2.83 us                                                | 2.91 us: 1.03x slower                                                            |
| pycparser                  | 1.17 sec                                               | 1.21 sec: 1.04x slower                                                           |
| 2to3                       | 274 ms                                                 | 285 ms: 1.04x slower                                                             |
| regex_dna                  | 209 ms                                                 | 217 ms: 1.04x slower                                                             |
| pickle                     | 11.2 us                                                | 11.7 us: 1.04x slower                                                            |
| async_tree_none_tg         | 447 ms                                                 | 470 ms: 1.05x slower                                                             |
| async_tree_cpu_io_mixed_tg | 725 ms                                                 | 762 ms: 1.05x slower                                                             |
| async_tree_io              | 1.16 sec                                               | 1.23 sec: 1.05x slower                                                           |
| xml_etree_iterparse        | 106 ms                                                 | 112 ms: 1.06x slower                                                             |
| async_tree_io_tg           | 1.19 sec                                               | 1.26 sec: 1.06x slower                                                           |
| async_tree_memoization_tg  | 574 ms                                                 | 610 ms: 1.06x slower                                                             |
| pprint_safe_repr           | 765 ms                                                 | 822 ms: 1.07x slower                                                             |
| mdp                        | 2.57 sec                                               | 2.76 sec: 1.08x slower                                                           |
| meteor_contest             | 110 ms                                                 | 118 ms: 1.08x slower                                                             |
| unpickle_pure_python       | 230 us                                                 | 248 us: 1.08x slower                                                             |
| pickle_dict                | 33.5 us                                                | 36.3 us: 1.08x slower                                                            |
| chaos                      | 67.5 ms                                                | 73.2 ms: 1.08x slower                                                            |
| pprint_pformat             | 1.55 sec                                               | 1.68 sec: 1.08x slower                                                           |
| deepcopy_memo              | 39.7 us                                                | 43.1 us: 1.09x slower                                                            |
| pickle_list                | 4.67 us                                                | 5.08 us: 1.09x slower                                                            |
| regex_compile              | 148 ms                                                 | 162 ms: 1.09x slower                                                             |
| python_startup             | 9.53 ms                                                | 10.4 ms: 1.09x slower                                                            |
| regex_v8                   | 22.7 ms                                                | 24.8 ms: 1.09x slower                                                            |
| richards                   | 46.0 ms                                                | 50.5 ms: 1.10x slower                                                            |
| scimark_monte_carlo        | 74.6 ms                                                | 82.2 ms: 1.10x slower                                                            |
| richards_super             | 51.9 ms                                                | 57.4 ms: 1.10x slower                                                            |
| scimark_fft                | 381 ms                                                 | 427 ms: 1.12x slower                                                             |
| pyflate                    | 471 ms                                                 | 535 ms: 1.14x slower                                                             |
| comprehensions             | 20.9 us                                                | 24.3 us: 1.16x slower                                                            |
| nqueens                    | 86.2 ms                                                | 103 ms: 1.20x slower                                                             |
| fannkuch                   | 410 ms                                                 | 492 ms: 1.20x slower                                                             |
| float                      | 83.3 ms                                                | 101 ms: 1.22x slower                                                             |
| telco                      | 7.18 ms                                                | 8.79 ms: 1.23x slower                                                            |
| nbody                      | 92.2 ms                                                | 114 ms: 1.24x slower                                                             |
| tomli_loads                | 2.30 sec                                               | 2.86 sec: 1.24x slower                                                           |
| mako                       | 11.5 ms                                                | 14.7 ms: 1.28x slower                                                            |
| coverage                   | 75.1 ms                                                | 96.8 ms: 1.29x slower                                                            |
| scimark_sparse_mat_mult    | 5.33 ms                                                | 6.94 ms: 1.30x slower                                                            |
| python_startup_no_site     | 6.92 ms                                                | 9.08 ms: 1.31x slower                                                            |
| go                         | 140 ms                                                 | 186 ms: 1.32x slower                                                             |
| deltablue                  | 3.71 ms                                                | 4.98 ms: 1.34x slower                                                            |
| hexiom                     | 6.54 ms                                                | 9.84 ms: 1.50x slower                                                            |
| Geometric mean             | (ref)                                                  | 1.05x slower                                                                     |

Benchmark hidden because not significant (7): dask, scimark_sor, sqlglot_transpile, asyncio_websockets, sqlglot_optimize, chameleon, bench_mp_pool
Ignored benchmarks (5) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.02x
- 95% likely to have a slowdown of 1.01x
- 99% likely to have a slowdown of 1.01x
