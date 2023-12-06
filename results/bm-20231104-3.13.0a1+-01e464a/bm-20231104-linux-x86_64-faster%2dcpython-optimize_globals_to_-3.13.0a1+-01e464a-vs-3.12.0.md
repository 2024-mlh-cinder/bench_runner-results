
# Results vs. 3.12.0

- fork: faster-cpython
- ref: optimize_globals_to_
- machine: linux-x86_64
- commit hash: 01e464a
- commit date: 2023-11-04
- overall geometric mean: 1.06x slower \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.02x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231104-linux-x86_64-faster%2dcpython-optimize_globals_to_-3.13.0a1+-01e464a |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| 2to3           | 274 ms                                                 | 292 ms: 1.06x slower                                                             |
| chameleon      | 7.41 ms                                                | 7.59 ms: 1.02x slower                                                            |
| docutils       | 2.75 sec                                               | 2.73 sec: 1.01x faster                                                           |
| tornado_http   | 101 ms                                                 | 99.7 ms: 1.01x faster                                                            |
| Geometric mean | (ref)                                                  | 1.02x slower                                                                     |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231104-linux-x86_64-faster%2dcpython-optimize_globals_to_-3.13.0a1+-01e464a |
|----------------------------|:------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| async_tree_none            | 475 ms                                                 | 459 ms: 1.04x faster                                                             |
| async_tree_memoization     | 580 ms                                                 | 588 ms: 1.01x slower                                                             |
| async_tree_io              | 1.16 sec                                               | 1.21 sec: 1.04x slower                                                           |
| async_tree_cpu_io_mixed_tg | 725 ms                                                 | 757 ms: 1.04x slower                                                             |
| async_tree_io_tg           | 1.19 sec                                               | 1.25 sec: 1.05x slower                                                           |
| async_tree_none_tg         | 447 ms                                                 | 472 ms: 1.06x slower                                                             |
| async_tree_memoization_tg  | 574 ms                                                 | 612 ms: 1.06x slower                                                             |
| Geometric mean             | (ref)                                                  | 1.03x slower                                                                     |

Benchmark hidden because not significant (1): async_tree_cpu_io_mixed

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231104-linux-x86_64-faster%2dcpython-optimize_globals_to_-3.13.0a1+-01e464a |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| pidigits       | 187 ms                                                 | 197 ms: 1.05x slower                                                             |
| float          | 83.3 ms                                                | 104 ms: 1.25x slower                                                             |
| nbody          | 92.2 ms                                                | 122 ms: 1.32x slower                                                             |
| Geometric mean | (ref)                                                  | 1.20x slower                                                                     |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231104-linux-x86_64-faster%2dcpython-optimize_globals_to_-3.13.0a1+-01e464a |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| regex_effbot   | 3.57 ms                                                | 3.72 ms: 1.04x slower                                                            |
| regex_dna      | 209 ms                                                 | 218 ms: 1.04x slower                                                             |
| regex_compile  | 148 ms                                                 | 164 ms: 1.11x slower                                                             |
| regex_v8       | 22.7 ms                                                | 25.8 ms: 1.14x slower                                                            |
| Geometric mean | (ref)                                                  | 1.08x slower                                                                     |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231104-linux-x86_64-faster%2dcpython-optimize_globals_to_-3.13.0a1+-01e464a |
|----------------------|:------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| pickle_pure_python   | 326 us                                                 | 303 us: 1.08x faster                                                             |
| xml_etree_process    | 61.2 ms                                                | 59.5 ms: 1.03x faster                                                            |
| json_loads           | 28.4 us                                                | 27.7 us: 1.02x faster                                                            |
| unpickle             | 15.8 us                                                | 15.5 us: 1.02x faster                                                            |
| xml_etree_generate   | 88.7 ms                                                | 87.6 ms: 1.01x faster                                                            |
| json_dumps           | 10.6 ms                                                | 10.7 ms: 1.01x slower                                                            |
| pickle               | 11.2 us                                                | 11.6 us: 1.03x slower                                                            |
| unpickle_pure_python | 230 us                                                 | 243 us: 1.06x slower                                                             |
| xml_etree_iterparse  | 106 ms                                                 | 112 ms: 1.06x slower                                                             |
| pickle_dict          | 33.5 us                                                | 35.6 us: 1.06x slower                                                            |
| unpickle_list        | 5.04 us                                                | 5.40 us: 1.07x slower                                                            |
| pickle_list          | 4.67 us                                                | 5.11 us: 1.09x slower                                                            |
| tomli_loads          | 2.30 sec                                               | 2.99 sec: 1.30x slower                                                           |
| Geometric mean       | (ref)                                                  | 1.04x slower                                                                     |

Benchmark hidden because not significant (1): xml_etree_parse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231104-linux-x86_64-faster%2dcpython-optimize_globals_to_-3.13.0a1+-01e464a |
|------------------------|:------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| python_startup         | 9.53 ms                                                | 10.3 ms: 1.08x slower                                                            |
| python_startup_no_site | 6.92 ms                                                | 9.00 ms: 1.30x slower                                                            |
| Geometric mean         | (ref)                                                  | 1.19x slower                                                                     |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231104-linux-x86_64-faster%2dcpython-optimize_globals_to_-3.13.0a1+-01e464a |
|-----------|:------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| mako      | 11.5 ms                                                | 15.3 ms: 1.33x slower                                                            |

All benchmarks:
===============

| Benchmark                  | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231104-linux-x86_64-faster%2dcpython-optimize_globals_to_-3.13.0a1+-01e464a |
|----------------------------|:------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| typing_runtime_protocols   | 153 us                                                 | 124 us: 1.24x faster                                                             |
| gc_traversal               | 4.28 ms                                                | 3.80 ms: 1.12x faster                                                            |
| generators                 | 32.5 ms                                                | 30.0 ms: 1.08x faster                                                            |
| pickle_pure_python         | 326 us                                                 | 303 us: 1.08x faster                                                             |
| sympy_sum                  | 167 ms                                                 | 157 ms: 1.07x faster                                                             |
| coroutines                 | 23.5 ms                                                | 22.1 ms: 1.06x faster                                                            |
| spectral_norm              | 115 ms                                                 | 109 ms: 1.05x faster                                                             |
| sqlglot_normalize          | 112 ms                                                 | 107 ms: 1.04x faster                                                             |
| async_tree_none            | 475 ms                                                 | 459 ms: 1.04x faster                                                             |
| scimark_sor                | 129 ms                                                 | 125 ms: 1.03x faster                                                             |
| xml_etree_process          | 61.2 ms                                                | 59.5 ms: 1.03x faster                                                            |
| sympy_str                  | 296 ms                                                 | 288 ms: 1.03x faster                                                             |
| deepcopy_reduce            | 3.23 us                                                | 3.15 us: 1.03x faster                                                            |
| json_loads                 | 28.4 us                                                | 27.7 us: 1.02x faster                                                            |
| logging_silent             | 108 ns                                                 | 105 ns: 1.02x faster                                                             |
| asyncio_tcp                | 506 ms                                                 | 495 ms: 1.02x faster                                                             |
| unpickle                   | 15.8 us                                                | 15.5 us: 1.02x faster                                                            |
| json                       | 5.22 ms                                                | 5.14 ms: 1.01x faster                                                            |
| deepcopy                   | 363 us                                                 | 358 us: 1.01x faster                                                             |
| xml_etree_generate         | 88.7 ms                                                | 87.6 ms: 1.01x faster                                                            |
| logging_simple             | 6.38 us                                                | 6.32 us: 1.01x faster                                                            |
| tornado_http               | 101 ms                                                 | 99.7 ms: 1.01x faster                                                            |
| docutils                   | 2.75 sec                                               | 2.73 sec: 1.01x faster                                                           |
| raytrace                   | 308 ms                                                 | 309 ms: 1.00x slower                                                             |
| sqlglot_optimize           | 54.8 ms                                                | 55.1 ms: 1.01x slower                                                            |
| sqlglot_parse              | 1.35 ms                                                | 1.36 ms: 1.01x slower                                                            |
| json_dumps                 | 10.6 ms                                                | 10.7 ms: 1.01x slower                                                            |
| sqlglot_transpile          | 1.68 ms                                                | 1.69 ms: 1.01x slower                                                            |
| dulwich_log                | 68.7 ms                                                | 69.4 ms: 1.01x slower                                                            |
| sqlite_synth               | 2.83 us                                                | 2.87 us: 1.01x slower                                                            |
| scimark_lu                 | 120 ms                                                 | 122 ms: 1.01x slower                                                             |
| async_tree_memoization     | 580 ms                                                 | 588 ms: 1.01x slower                                                             |
| async_generators           | 459 ms                                                 | 467 ms: 1.02x slower                                                             |
| asyncio_tcp_ssl            | 1.78 sec                                               | 1.81 sec: 1.02x slower                                                           |
| sympy_integrate            | 21.2 ms                                                | 21.6 ms: 1.02x slower                                                            |
| bench_thread_pool          | 845 us                                                 | 860 us: 1.02x slower                                                             |
| mypy2                      | 351 ms                                                 | 358 ms: 1.02x slower                                                             |
| chameleon                  | 7.41 ms                                                | 7.59 ms: 1.02x slower                                                            |
| sympy_expand               | 476 ms                                                 | 488 ms: 1.03x slower                                                             |
| pickle                     | 11.2 us                                                | 11.6 us: 1.03x slower                                                            |
| pycparser                  | 1.17 sec                                               | 1.21 sec: 1.04x slower                                                           |
| async_tree_io              | 1.16 sec                                               | 1.21 sec: 1.04x slower                                                           |
| regex_effbot               | 3.57 ms                                                | 3.72 ms: 1.04x slower                                                            |
| async_tree_cpu_io_mixed_tg | 725 ms                                                 | 757 ms: 1.04x slower                                                             |
| regex_dna                  | 209 ms                                                 | 218 ms: 1.04x slower                                                             |
| pathlib                    | 18.9 ms                                                | 19.7 ms: 1.04x slower                                                            |
| async_tree_io_tg           | 1.19 sec                                               | 1.25 sec: 1.05x slower                                                           |
| pidigits                   | 187 ms                                                 | 197 ms: 1.05x slower                                                             |
| async_tree_none_tg         | 447 ms                                                 | 472 ms: 1.06x slower                                                             |
| pprint_safe_repr           | 765 ms                                                 | 807 ms: 1.06x slower                                                             |
| unpickle_pure_python       | 230 us                                                 | 243 us: 1.06x slower                                                             |
| crypto_pyaes               | 83.6 ms                                                | 88.4 ms: 1.06x slower                                                            |
| xml_etree_iterparse        | 106 ms                                                 | 112 ms: 1.06x slower                                                             |
| pickle_dict                | 33.5 us                                                | 35.6 us: 1.06x slower                                                            |
| 2to3                       | 274 ms                                                 | 292 ms: 1.06x slower                                                             |
| async_tree_memoization_tg  | 574 ms                                                 | 612 ms: 1.06x slower                                                             |
| unpickle_list              | 5.04 us                                                | 5.40 us: 1.07x slower                                                            |
| scimark_monte_carlo        | 74.6 ms                                                | 79.9 ms: 1.07x slower                                                            |
| deepcopy_memo              | 39.7 us                                                | 42.6 us: 1.07x slower                                                            |
| pprint_pformat             | 1.55 sec                                               | 1.67 sec: 1.08x slower                                                           |
| python_startup             | 9.53 ms                                                | 10.3 ms: 1.08x slower                                                            |
| pickle_list                | 4.67 us                                                | 5.11 us: 1.09x slower                                                            |
| unpack_sequence            | 54.2 ns                                                | 59.4 ns: 1.10x slower                                                            |
| meteor_contest             | 110 ms                                                 | 121 ms: 1.10x slower                                                             |
| richards                   | 46.0 ms                                                | 50.7 ms: 1.10x slower                                                            |
| regex_compile              | 148 ms                                                 | 164 ms: 1.11x slower                                                             |
| richards_super             | 51.9 ms                                                | 57.8 ms: 1.11x slower                                                            |
| chaos                      | 67.5 ms                                                | 75.4 ms: 1.12x slower                                                            |
| regex_v8                   | 22.7 ms                                                | 25.8 ms: 1.14x slower                                                            |
| mdp                        | 2.57 sec                                               | 2.94 sec: 1.14x slower                                                           |
| scimark_fft                | 381 ms                                                 | 437 ms: 1.15x slower                                                             |
| go                         | 140 ms                                                 | 170 ms: 1.21x slower                                                             |
| telco                      | 7.18 ms                                                | 8.71 ms: 1.21x slower                                                            |
| pyflate                    | 471 ms                                                 | 579 ms: 1.23x slower                                                             |
| fannkuch                   | 410 ms                                                 | 510 ms: 1.24x slower                                                             |
| comprehensions             | 20.9 us                                                | 26.2 us: 1.25x slower                                                            |
| float                      | 83.3 ms                                                | 104 ms: 1.25x slower                                                             |
| nqueens                    | 86.2 ms                                                | 108 ms: 1.25x slower                                                             |
| coverage                   | 75.1 ms                                                | 96.0 ms: 1.28x slower                                                            |
| scimark_sparse_mat_mult    | 5.33 ms                                                | 6.87 ms: 1.29x slower                                                            |
| tomli_loads                | 2.30 sec                                               | 2.99 sec: 1.30x slower                                                           |
| python_startup_no_site     | 6.92 ms                                                | 9.00 ms: 1.30x slower                                                            |
| nbody                      | 92.2 ms                                                | 122 ms: 1.32x slower                                                             |
| mako                       | 11.5 ms                                                | 15.3 ms: 1.33x slower                                                            |
| deltablue                  | 3.71 ms                                                | 5.25 ms: 1.42x slower                                                            |
| hexiom                     | 6.54 ms                                                | 10.3 ms: 1.57x slower                                                            |
| Geometric mean             | (ref)                                                  | 1.06x slower                                                                     |

Benchmark hidden because not significant (6): xml_etree_parse, asyncio_websockets, bench_mp_pool, create_gc_cycles, logging_format, async_tree_cpu_io_mixed
Ignored benchmarks (6) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, dask, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.03x
- 95% likely to have a slowdown of 1.02x
- 99% likely to have a slowdown of 1.02x
