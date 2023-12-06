
# Results vs. 3.11.0

- fork: python
- ref: 48dfd74a9db9d4aa9c6f
- machine: darwin-arm64
- commit hash: 48dfd74
- commit date: 2023-11-28
- overall geometric mean: 1.05x slower \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.02x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-darwin-arm64-python-deaf509e8fc6e0363bd6-3.11.0-deaf509 | bm-20231128-darwin-arm64-python-48dfd74a9db9d4aa9c6f-3.13.0a2+-48dfd74 |
|----------------|:-------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| 2to3           | 154 ms                                                              | 175 ms: 1.14x slower                                                   |
| chameleon      | 4.21 ms                                                             | 5.09 ms: 1.21x slower                                                  |
| docutils       | 1.43 sec                                                            | 1.51 sec: 1.05x slower                                                 |
| Geometric mean | (ref)                                                               | 1.10x slower                                                           |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20221024-darwin-arm64-python-deaf509e8fc6e0363bd6-3.11.0-deaf509 | bm-20231128-darwin-arm64-python-48dfd74a9db9d4aa9c6f-3.13.0a2+-48dfd74 |
|----------------------------|:-------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| async_tree_none            | 277 ms                                                              | 255 ms: 1.09x faster                                                   |
| async_tree_memoization     | 353 ms                                                              | 333 ms: 1.06x faster                                                   |
| async_tree_memoization_tg  | 351 ms                                                              | 333 ms: 1.05x faster                                                   |
| async_tree_io_tg           | 723 ms                                                              | 688 ms: 1.05x faster                                                   |
| async_tree_none_tg         | 277 ms                                                              | 267 ms: 1.04x faster                                                   |
| async_tree_cpu_io_mixed_tg | 548 ms                                                              | 543 ms: 1.01x faster                                                   |
| async_tree_cpu_io_mixed    | 516 ms                                                              | 527 ms: 1.02x slower                                                   |
| async_tree_io              | 691 ms                                                              | 707 ms: 1.02x slower                                                   |
| Geometric mean             | (ref)                                                               | 1.03x faster                                                           |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-darwin-arm64-python-deaf509e8fc6e0363bd6-3.11.0-deaf509 | bm-20231128-darwin-arm64-python-48dfd74a9db9d4aa9c6f-3.13.0a2+-48dfd74 |
|----------------|:-------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| pidigits       | 280 ms                                                              | 294 ms: 1.05x slower                                                   |
| float          | 55.1 ms                                                             | 58.5 ms: 1.06x slower                                                  |
| nbody          | 68.5 ms                                                             | 84.5 ms: 1.23x slower                                                  |
| Geometric mean | (ref)                                                               | 1.11x slower                                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-darwin-arm64-python-deaf509e8fc6e0363bd6-3.11.0-deaf509 | bm-20231128-darwin-arm64-python-48dfd74a9db9d4aa9c6f-3.13.0a2+-48dfd74 |
|----------------|:-------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| regex_effbot   | 2.45 ms                                                             | 2.57 ms: 1.05x slower                                                  |
| regex_compile  | 73.5 ms                                                             | 80.0 ms: 1.09x slower                                                  |
| regex_v8       | 15.4 ms                                                             | 16.9 ms: 1.10x slower                                                  |
| Geometric mean | (ref)                                                               | 1.06x slower                                                           |

Benchmark hidden because not significant (1): regex_dna

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-darwin-arm64-python-deaf509e8fc6e0363bd6-3.11.0-deaf509 | bm-20231128-darwin-arm64-python-48dfd74a9db9d4aa9c6f-3.13.0a2+-48dfd74 |
|----------------------|:-------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| json_dumps           | 7.58 ms                                                             | 6.62 ms: 1.15x faster                                                  |
| pickle_pure_python   | 210 us                                                              | 209 us: 1.00x faster                                                   |
| unpickle_pure_python | 162 us                                                              | 165 us: 1.02x slower                                                   |
| pickle               | 7.17 us                                                             | 7.53 us: 1.05x slower                                                  |
| unpickle             | 8.35 us                                                             | 9.04 us: 1.08x slower                                                  |
| pickle_dict          | 17.0 us                                                             | 18.6 us: 1.10x slower                                                  |
| pickle_list          | 2.68 us                                                             | 2.94 us: 1.10x slower                                                  |
| xml_etree_parse      | 97.6 ms                                                             | 107 ms: 1.10x slower                                                   |
| json_loads           | 15.5 us                                                             | 17.3 us: 1.12x slower                                                  |
| unpickle_list        | 2.76 us                                                             | 3.12 us: 1.13x slower                                                  |
| xml_etree_iterparse  | 67.5 ms                                                             | 76.8 ms: 1.14x slower                                                  |
| xml_etree_process    | 34.1 ms                                                             | 41.2 ms: 1.21x slower                                                  |
| tomli_loads          | 1.32 sec                                                            | 1.61 sec: 1.22x slower                                                 |
| xml_etree_generate   | 47.1 ms                                                             | 58.4 ms: 1.24x slower                                                  |
| Geometric mean       | (ref)                                                               | 1.09x slower                                                           |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-darwin-arm64-python-deaf509e8fc6e0363bd6-3.11.0-deaf509 | bm-20231128-darwin-arm64-python-48dfd74a9db9d4aa9c6f-3.13.0a2+-48dfd74 |
|------------------------|:-------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| python_startup         | 11.5 ms                                                             | 12.2 ms: 1.06x slower                                                  |
| python_startup_no_site | 9.37 ms                                                             | 10.9 ms: 1.17x slower                                                  |
| Geometric mean         | (ref)                                                               | 1.11x slower                                                           |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-darwin-arm64-python-deaf509e8fc6e0363bd6-3.11.0-deaf509 | bm-20231128-darwin-arm64-python-48dfd74a9db9d4aa9c6f-3.13.0a2+-48dfd74 |
|-----------|:-------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| mako      | 8.25 ms                                                             | 7.75 ms: 1.06x faster                                                  |

All benchmarks:
===============

| Benchmark                  | bm-20221024-darwin-arm64-python-deaf509e8fc6e0363bd6-3.11.0-deaf509 | bm-20231128-darwin-arm64-python-48dfd74a9db9d4aa9c6f-3.13.0a2+-48dfd74 |
|----------------------------|:-------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| typing_runtime_protocols   | 322 us                                                              | 78.0 us: 4.12x faster                                                  |
| asyncio_tcp                | 664 ms                                                              | 428 ms: 1.55x faster                                                   |
| comprehensions             | 14.6 us                                                             | 12.7 us: 1.15x faster                                                  |
| json_dumps                 | 7.58 ms                                                             | 6.62 ms: 1.15x faster                                                  |
| chaos                      | 48.2 ms                                                             | 43.0 ms: 1.12x faster                                                  |
| raytrace                   | 205 ms                                                              | 183 ms: 1.12x faster                                                   |
| unpack_sequence            | 32.3 ns                                                             | 28.8 ns: 1.12x faster                                                  |
| generators                 | 29.0 ms                                                             | 26.1 ms: 1.11x faster                                                  |
| mdp                        | 1.84 sec                                                            | 1.67 sec: 1.10x faster                                                 |
| deepcopy_memo              | 28.7 us                                                             | 26.0 us: 1.10x faster                                                  |
| deltablue                  | 2.69 ms                                                             | 2.44 ms: 1.10x faster                                                  |
| asyncio_tcp_ssl            | 1.43 sec                                                            | 1.30 sec: 1.09x faster                                                 |
| async_tree_none            | 277 ms                                                              | 255 ms: 1.09x faster                                                   |
| mako                       | 8.25 ms                                                             | 7.75 ms: 1.06x faster                                                  |
| async_tree_memoization     | 353 ms                                                              | 333 ms: 1.06x faster                                                   |
| sympy_sum                  | 80.8 ms                                                             | 76.2 ms: 1.06x faster                                                  |
| async_tree_memoization_tg  | 351 ms                                                              | 333 ms: 1.05x faster                                                   |
| sqlglot_parse              | 874 us                                                              | 831 us: 1.05x faster                                                   |
| async_tree_io_tg           | 723 ms                                                              | 688 ms: 1.05x faster                                                   |
| gc_traversal               | 2.53 ms                                                             | 2.42 ms: 1.04x faster                                                  |
| async_tree_none_tg         | 277 ms                                                              | 267 ms: 1.04x faster                                                   |
| sqlglot_transpile          | 1.04 ms                                                             | 1.01 ms: 1.03x faster                                                  |
| async_tree_cpu_io_mixed_tg | 548 ms                                                              | 543 ms: 1.01x faster                                                   |
| pickle_pure_python         | 210 us                                                              | 209 us: 1.00x faster                                                   |
| asyncio_websockets         | 408 ms                                                              | 408 ms: 1.00x slower                                                   |
| deepcopy                   | 232 us                                                              | 233 us: 1.01x slower                                                   |
| create_gc_cycles           | 714 us                                                              | 724 us: 1.01x slower                                                   |
| unpickle_pure_python       | 162 us                                                              | 165 us: 1.02x slower                                                   |
| async_tree_cpu_io_mixed    | 516 ms                                                              | 527 ms: 1.02x slower                                                   |
| async_tree_io              | 691 ms                                                              | 707 ms: 1.02x slower                                                   |
| crypto_pyaes               | 47.9 ms                                                             | 49.0 ms: 1.02x slower                                                  |
| sympy_str                  | 144 ms                                                              | 148 ms: 1.03x slower                                                   |
| dulwich_log                | 29.2 ms                                                             | 30.0 ms: 1.03x slower                                                  |
| go                         | 102 ms                                                              | 106 ms: 1.04x slower                                                   |
| dask                       | 219 ms                                                              | 229 ms: 1.04x slower                                                   |
| pidigits                   | 280 ms                                                              | 294 ms: 1.05x slower                                                   |
| logging_simple             | 3.45 us                                                             | 3.62 us: 1.05x slower                                                  |
| regex_effbot               | 2.45 ms                                                             | 2.57 ms: 1.05x slower                                                  |
| pickle                     | 7.17 us                                                             | 7.53 us: 1.05x slower                                                  |
| logging_format             | 3.73 us                                                             | 3.91 us: 1.05x slower                                                  |
| docutils                   | 1.43 sec                                                            | 1.51 sec: 1.05x slower                                                 |
| python_startup             | 11.5 ms                                                             | 12.2 ms: 1.06x slower                                                  |
| bench_mp_pool              | 42.1 ms                                                             | 44.5 ms: 1.06x slower                                                  |
| scimark_sparse_mat_mult    | 3.00 ms                                                             | 3.18 ms: 1.06x slower                                                  |
| richards_super             | 36.7 ms                                                             | 39.0 ms: 1.06x slower                                                  |
| float                      | 55.1 ms                                                             | 58.5 ms: 1.06x slower                                                  |
| scimark_monte_carlo        | 45.7 ms                                                             | 48.6 ms: 1.06x slower                                                  |
| deepcopy_reduce            | 1.96 us                                                             | 2.09 us: 1.07x slower                                                  |
| pycparser                  | 658 ms                                                              | 709 ms: 1.08x slower                                                   |
| spectral_norm              | 69.4 ms                                                             | 74.9 ms: 1.08x slower                                                  |
| sympy_expand               | 236 ms                                                              | 255 ms: 1.08x slower                                                   |
| unpickle                   | 8.35 us                                                             | 9.04 us: 1.08x slower                                                  |
| regex_compile              | 73.5 ms                                                             | 80.0 ms: 1.09x slower                                                  |
| logging_silent             | 64.3 ns                                                             | 70.3 ns: 1.09x slower                                                  |
| json                       | 2.77 ms                                                             | 3.03 ms: 1.09x slower                                                  |
| pathlib                    | 23.0 ms                                                             | 25.2 ms: 1.10x slower                                                  |
| pickle_dict                | 17.0 us                                                             | 18.6 us: 1.10x slower                                                  |
| regex_v8                   | 15.4 ms                                                             | 16.9 ms: 1.10x slower                                                  |
| pickle_list                | 2.68 us                                                             | 2.94 us: 1.10x slower                                                  |
| xml_etree_parse            | 97.6 ms                                                             | 107 ms: 1.10x slower                                                   |
| bench_thread_pool          | 467 us                                                              | 514 us: 1.10x slower                                                   |
| scimark_lu                 | 67.9 ms                                                             | 75.1 ms: 1.10x slower                                                  |
| hexiom                     | 4.55 ms                                                             | 5.04 ms: 1.11x slower                                                  |
| json_loads                 | 15.5 us                                                             | 17.3 us: 1.12x slower                                                  |
| pprint_pformat             | 986 ms                                                              | 1.10 sec: 1.12x slower                                                 |
| unpickle_list              | 2.76 us                                                             | 3.12 us: 1.13x slower                                                  |
| richards                   | 30.7 ms                                                             | 34.8 ms: 1.14x slower                                                  |
| 2to3                       | 154 ms                                                              | 175 ms: 1.14x slower                                                   |
| xml_etree_iterparse        | 67.5 ms                                                             | 76.8 ms: 1.14x slower                                                  |
| scimark_fft                | 186 ms                                                              | 212 ms: 1.14x slower                                                   |
| coverage                   | 41.4 ms                                                             | 47.9 ms: 1.16x slower                                                  |
| pyflate                    | 295 ms                                                              | 344 ms: 1.16x slower                                                   |
| python_startup_no_site     | 9.37 ms                                                             | 10.9 ms: 1.17x slower                                                  |
| pprint_safe_repr           | 480 ms                                                              | 562 ms: 1.17x slower                                                   |
| coroutines                 | 16.4 ms                                                             | 19.3 ms: 1.18x slower                                                  |
| nqueens                    | 54.3 ms                                                             | 64.9 ms: 1.19x slower                                                  |
| fannkuch                   | 247 ms                                                              | 296 ms: 1.20x slower                                                   |
| sqlglot_normalize          | 160 ms                                                              | 192 ms: 1.20x slower                                                   |
| xml_etree_process          | 34.1 ms                                                             | 41.2 ms: 1.21x slower                                                  |
| sqlglot_optimize           | 29.6 ms                                                             | 35.7 ms: 1.21x slower                                                  |
| chameleon                  | 4.21 ms                                                             | 5.09 ms: 1.21x slower                                                  |
| sqlite_synth               | 1.36 us                                                             | 1.66 us: 1.22x slower                                                  |
| tomli_loads                | 1.32 sec                                                            | 1.61 sec: 1.22x slower                                                 |
| nbody                      | 68.5 ms                                                             | 84.5 ms: 1.23x slower                                                  |
| xml_etree_generate         | 47.1 ms                                                             | 58.4 ms: 1.24x slower                                                  |
| scimark_sor                | 74.4 ms                                                             | 108 ms: 1.45x slower                                                   |
| telco                      | 3.17 ms                                                             | 4.71 ms: 1.49x slower                                                  |
| async_generators           | 191 ms                                                              | 305 ms: 1.59x slower                                                   |
| mypy2                      | 187 ms                                                              | 560 ms: 2.99x slower                                                   |
| Geometric mean             | (ref)                                                               | 1.05x slower                                                           |

Benchmark hidden because not significant (4): sympy_integrate, meteor_contest, regex_dna, tornado_http
Ignored benchmarks (11) of results/bm-20221024-3.11.0-deaf509/bm-20221024-darwin-arm64-python-deaf509e8fc6e0363bd6-3.11.0-deaf509.json: aiohttp, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.04x
- 95% likely to have a slowdown of 1.03x
- 99% likely to have a slowdown of 1.02x
