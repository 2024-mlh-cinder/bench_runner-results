
# Results vs. 3.11.0

- fork: brandtbucher
- ref: justin
- machine: darwin-arm64
- commit hash: dfface9
- commit date: 2023-11-28
- overall geometric mean: 1.07x slower \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.03x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-darwin-arm64-python-deaf509e8fc6e0363bd6-3.11.0-deaf509 | bm-20231128-darwin-arm64-brandtbucher-justin-3.13.0a2+-dfface9 |
|----------------|:-------------------------------------------------------------------:|:--------------------------------------------------------------:|
| 2to3           | 154 ms                                                              | 181 ms: 1.18x slower                                           |
| chameleon      | 4.21 ms                                                             | 5.15 ms: 1.22x slower                                          |
| docutils       | 1.43 sec                                                            | 1.52 sec: 1.07x slower                                         |
| tornado_http   | 70.9 ms                                                             | 73.7 ms: 1.04x slower                                          |
| Geometric mean | (ref)                                                               | 1.13x slower                                                   |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20221024-darwin-arm64-python-deaf509e8fc6e0363bd6-3.11.0-deaf509 | bm-20231128-darwin-arm64-brandtbucher-justin-3.13.0a2+-dfface9 |
|----------------------------|:-------------------------------------------------------------------:|:--------------------------------------------------------------:|
| async_tree_none            | 277 ms                                                              | 257 ms: 1.08x faster                                           |
| async_tree_memoization     | 353 ms                                                              | 332 ms: 1.06x faster                                           |
| async_tree_io_tg           | 723 ms                                                              | 687 ms: 1.05x faster                                           |
| async_tree_memoization_tg  | 351 ms                                                              | 335 ms: 1.05x faster                                           |
| async_tree_none_tg         | 277 ms                                                              | 268 ms: 1.03x faster                                           |
| async_tree_cpu_io_mixed_tg | 548 ms                                                              | 543 ms: 1.01x faster                                           |
| async_tree_io              | 691 ms                                                              | 707 ms: 1.02x slower                                           |
| async_tree_cpu_io_mixed    | 516 ms                                                              | 528 ms: 1.02x slower                                           |
| Geometric mean             | (ref)                                                               | 1.03x faster                                                   |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-darwin-arm64-python-deaf509e8fc6e0363bd6-3.11.0-deaf509 | bm-20231128-darwin-arm64-brandtbucher-justin-3.13.0a2+-dfface9 |
|----------------|:-------------------------------------------------------------------:|:--------------------------------------------------------------:|
| pidigits       | 280 ms                                                              | 283 ms: 1.01x slower                                           |
| float          | 55.1 ms                                                             | 58.7 ms: 1.07x slower                                          |
| nbody          | 68.5 ms                                                             | 80.5 ms: 1.18x slower                                          |
| Geometric mean | (ref)                                                               | 1.08x slower                                                   |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-darwin-arm64-python-deaf509e8fc6e0363bd6-3.11.0-deaf509 | bm-20231128-darwin-arm64-brandtbucher-justin-3.13.0a2+-dfface9 |
|----------------|:-------------------------------------------------------------------:|:--------------------------------------------------------------:|
| regex_dna      | 149 ms                                                              | 149 ms: 1.00x faster                                           |
| regex_effbot   | 2.45 ms                                                             | 2.57 ms: 1.05x slower                                          |
| regex_v8       | 15.4 ms                                                             | 17.0 ms: 1.11x slower                                          |
| regex_compile  | 73.5 ms                                                             | 83.9 ms: 1.14x slower                                          |
| Geometric mean | (ref)                                                               | 1.07x slower                                                   |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-darwin-arm64-python-deaf509e8fc6e0363bd6-3.11.0-deaf509 | bm-20231128-darwin-arm64-brandtbucher-justin-3.13.0a2+-dfface9 |
|----------------------|:-------------------------------------------------------------------:|:--------------------------------------------------------------:|
| json_dumps           | 7.58 ms                                                             | 6.57 ms: 1.15x faster                                          |
| pickle_pure_python   | 210 us                                                              | 209 us: 1.00x faster                                           |
| pickle               | 7.17 us                                                             | 7.39 us: 1.03x slower                                          |
| unpickle_pure_python | 162 us                                                              | 171 us: 1.05x slower                                           |
| pickle_dict          | 17.0 us                                                             | 18.0 us: 1.06x slower                                          |
| pickle_list          | 2.68 us                                                             | 2.89 us: 1.08x slower                                          |
| unpickle             | 8.35 us                                                             | 9.11 us: 1.09x slower                                          |
| xml_etree_parse      | 97.6 ms                                                             | 107 ms: 1.10x slower                                           |
| json_loads           | 15.5 us                                                             | 17.3 us: 1.12x slower                                          |
| unpickle_list        | 2.76 us                                                             | 3.12 us: 1.13x slower                                          |
| xml_etree_iterparse  | 67.5 ms                                                             | 76.8 ms: 1.14x slower                                          |
| tomli_loads          | 1.32 sec                                                            | 1.53 sec: 1.16x slower                                         |
| xml_etree_process    | 34.1 ms                                                             | 41.3 ms: 1.21x slower                                          |
| xml_etree_generate   | 47.1 ms                                                             | 59.2 ms: 1.26x slower                                          |
| Geometric mean       | (ref)                                                               | 1.09x slower                                                   |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-darwin-arm64-python-deaf509e8fc6e0363bd6-3.11.0-deaf509 | bm-20231128-darwin-arm64-brandtbucher-justin-3.13.0a2+-dfface9 |
|------------------------|:-------------------------------------------------------------------:|:--------------------------------------------------------------:|
| python_startup         | 11.5 ms                                                             | 12.3 ms: 1.07x slower                                          |
| python_startup_no_site | 9.37 ms                                                             | 10.8 ms: 1.15x slower                                          |
| Geometric mean         | (ref)                                                               | 1.11x slower                                                   |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-darwin-arm64-python-deaf509e8fc6e0363bd6-3.11.0-deaf509 | bm-20231128-darwin-arm64-brandtbucher-justin-3.13.0a2+-dfface9 |
|-----------|:-------------------------------------------------------------------:|:--------------------------------------------------------------:|
| mako      | 8.25 ms                                                             | 7.96 ms: 1.04x faster                                          |

All benchmarks:
===============

| Benchmark                  | bm-20221024-darwin-arm64-python-deaf509e8fc6e0363bd6-3.11.0-deaf509 | bm-20231128-darwin-arm64-brandtbucher-justin-3.13.0a2+-dfface9 |
|----------------------------|:-------------------------------------------------------------------:|:--------------------------------------------------------------:|
| typing_runtime_protocols   | 322 us                                                              | 79.1 us: 4.07x faster                                          |
| asyncio_tcp                | 664 ms                                                              | 427 ms: 1.56x faster                                           |
| json_dumps                 | 7.58 ms                                                             | 6.57 ms: 1.15x faster                                          |
| generators                 | 29.0 ms                                                             | 26.0 ms: 1.11x faster                                          |
| unpack_sequence            | 32.3 ns                                                             | 29.0 ns: 1.11x faster                                          |
| asyncio_tcp_ssl            | 1.43 sec                                                            | 1.31 sec: 1.09x faster                                         |
| raytrace                   | 205 ms                                                              | 189 ms: 1.09x faster                                           |
| async_tree_none            | 277 ms                                                              | 257 ms: 1.08x faster                                           |
| chaos                      | 48.2 ms                                                             | 44.9 ms: 1.07x faster                                          |
| mdp                        | 1.84 sec                                                            | 1.72 sec: 1.07x faster                                         |
| deepcopy_memo              | 28.7 us                                                             | 26.9 us: 1.07x faster                                          |
| async_tree_memoization     | 353 ms                                                              | 332 ms: 1.06x faster                                           |
| comprehensions             | 14.6 us                                                             | 13.8 us: 1.06x faster                                          |
| gc_traversal               | 2.53 ms                                                             | 2.40 ms: 1.05x faster                                          |
| async_tree_io_tg           | 723 ms                                                              | 687 ms: 1.05x faster                                           |
| async_tree_memoization_tg  | 351 ms                                                              | 335 ms: 1.05x faster                                           |
| deltablue                  | 2.69 ms                                                             | 2.57 ms: 1.05x faster                                          |
| mako                       | 8.25 ms                                                             | 7.96 ms: 1.04x faster                                          |
| sqlglot_parse              | 874 us                                                              | 849 us: 1.03x faster                                           |
| async_tree_none_tg         | 277 ms                                                              | 268 ms: 1.03x faster                                           |
| create_gc_cycles           | 714 us                                                              | 701 us: 1.02x faster                                           |
| async_tree_cpu_io_mixed_tg | 548 ms                                                              | 543 ms: 1.01x faster                                           |
| regex_dna                  | 149 ms                                                              | 149 ms: 1.00x faster                                           |
| pickle_pure_python         | 210 us                                                              | 209 us: 1.00x faster                                           |
| sympy_sum                  | 80.8 ms                                                             | 81.0 ms: 1.00x slower                                          |
| asyncio_websockets         | 408 ms                                                              | 409 ms: 1.00x slower                                           |
| pidigits                   | 280 ms                                                              | 283 ms: 1.01x slower                                           |
| richards_super             | 36.7 ms                                                             | 37.3 ms: 1.02x slower                                          |
| async_tree_io              | 691 ms                                                              | 707 ms: 1.02x slower                                           |
| async_tree_cpu_io_mixed    | 516 ms                                                              | 528 ms: 1.02x slower                                           |
| deepcopy                   | 232 us                                                              | 238 us: 1.03x slower                                           |
| pickle                     | 7.17 us                                                             | 7.39 us: 1.03x slower                                          |
| tornado_http               | 70.9 ms                                                             | 73.7 ms: 1.04x slower                                          |
| meteor_contest             | 75.3 ms                                                             | 78.5 ms: 1.04x slower                                          |
| dulwich_log                | 29.2 ms                                                             | 30.5 ms: 1.04x slower                                          |
| regex_effbot               | 2.45 ms                                                             | 2.57 ms: 1.05x slower                                          |
| crypto_pyaes               | 47.9 ms                                                             | 50.3 ms: 1.05x slower                                          |
| logging_format             | 3.73 us                                                             | 3.92 us: 1.05x slower                                          |
| unpickle_pure_python       | 162 us                                                              | 171 us: 1.05x slower                                           |
| logging_simple             | 3.45 us                                                             | 3.64 us: 1.05x slower                                          |
| dask                       | 219 ms                                                              | 231 ms: 1.06x slower                                           |
| pickle_dict                | 17.0 us                                                             | 18.0 us: 1.06x slower                                          |
| docutils                   | 1.43 sec                                                            | 1.52 sec: 1.07x slower                                         |
| float                      | 55.1 ms                                                             | 58.7 ms: 1.07x slower                                          |
| sympy_str                  | 144 ms                                                              | 154 ms: 1.07x slower                                           |
| python_startup             | 11.5 ms                                                             | 12.3 ms: 1.07x slower                                          |
| sympy_integrate            | 11.2 ms                                                             | 12.0 ms: 1.07x slower                                          |
| pathlib                    | 23.0 ms                                                             | 24.9 ms: 1.08x slower                                          |
| pickle_list                | 2.68 us                                                             | 2.89 us: 1.08x slower                                          |
| deepcopy_reduce            | 1.96 us                                                             | 2.12 us: 1.08x slower                                          |
| richards                   | 30.7 ms                                                             | 33.4 ms: 1.09x slower                                          |
| unpickle                   | 8.35 us                                                             | 9.11 us: 1.09x slower                                          |
| pycparser                  | 658 ms                                                              | 719 ms: 1.09x slower                                           |
| json                       | 2.77 ms                                                             | 3.03 ms: 1.09x slower                                          |
| xml_etree_parse            | 97.6 ms                                                             | 107 ms: 1.10x slower                                           |
| sympy_expand               | 236 ms                                                              | 260 ms: 1.10x slower                                           |
| bench_mp_pool              | 42.1 ms                                                             | 46.3 ms: 1.10x slower                                          |
| regex_v8                   | 15.4 ms                                                             | 17.0 ms: 1.11x slower                                          |
| scimark_sparse_mat_mult    | 3.00 ms                                                             | 3.31 ms: 1.11x slower                                          |
| scimark_monte_carlo        | 45.7 ms                                                             | 50.8 ms: 1.11x slower                                          |
| go                         | 102 ms                                                              | 114 ms: 1.11x slower                                           |
| json_loads                 | 15.5 us                                                             | 17.3 us: 1.12x slower                                          |
| logging_silent             | 64.3 ns                                                             | 71.9 ns: 1.12x slower                                          |
| pprint_pformat             | 986 ms                                                              | 1.11 sec: 1.13x slower                                         |
| pprint_safe_repr           | 480 ms                                                              | 542 ms: 1.13x slower                                           |
| unpickle_list              | 2.76 us                                                             | 3.12 us: 1.13x slower                                          |
| bench_thread_pool          | 467 us                                                              | 531 us: 1.14x slower                                           |
| xml_etree_iterparse        | 67.5 ms                                                             | 76.8 ms: 1.14x slower                                          |
| regex_compile              | 73.5 ms                                                             | 83.9 ms: 1.14x slower                                          |
| python_startup_no_site     | 9.37 ms                                                             | 10.8 ms: 1.15x slower                                          |
| scimark_lu                 | 67.9 ms                                                             | 78.6 ms: 1.16x slower                                          |
| tomli_loads                | 1.32 sec                                                            | 1.53 sec: 1.16x slower                                         |
| coverage                   | 41.4 ms                                                             | 48.5 ms: 1.17x slower                                          |
| coroutines                 | 16.4 ms                                                             | 19.3 ms: 1.17x slower                                          |
| nbody                      | 68.5 ms                                                             | 80.5 ms: 1.18x slower                                          |
| pyflate                    | 295 ms                                                              | 349 ms: 1.18x slower                                           |
| 2to3                       | 154 ms                                                              | 181 ms: 1.18x slower                                           |
| spectral_norm              | 69.4 ms                                                             | 82.1 ms: 1.18x slower                                          |
| scimark_fft                | 186 ms                                                              | 222 ms: 1.19x slower                                           |
| nqueens                    | 54.3 ms                                                             | 65.7 ms: 1.21x slower                                          |
| xml_etree_process          | 34.1 ms                                                             | 41.3 ms: 1.21x slower                                          |
| fannkuch                   | 247 ms                                                              | 301 ms: 1.22x slower                                           |
| chameleon                  | 4.21 ms                                                             | 5.15 ms: 1.22x slower                                          |
| sqlite_synth               | 1.36 us                                                             | 1.66 us: 1.23x slower                                          |
| sqlglot_normalize          | 160 ms                                                              | 197 ms: 1.23x slower                                           |
| sqlglot_optimize           | 29.6 ms                                                             | 37.1 ms: 1.25x slower                                          |
| xml_etree_generate         | 47.1 ms                                                             | 59.2 ms: 1.26x slower                                          |
| hexiom                     | 4.55 ms                                                             | 5.82 ms: 1.28x slower                                          |
| scimark_sor                | 74.4 ms                                                             | 108 ms: 1.45x slower                                           |
| telco                      | 3.17 ms                                                             | 4.64 ms: 1.47x slower                                          |
| async_generators           | 191 ms                                                              | 321 ms: 1.68x slower                                           |
| mypy2                      | 187 ms                                                              | 541 ms: 2.89x slower                                           |
| Geometric mean             | (ref)                                                               | 1.07x slower                                                   |

Benchmark hidden because not significant (1): sqlglot_transpile
Ignored benchmarks (11) of results/bm-20221024-3.11.0-deaf509/bm-20221024-darwin-arm64-python-deaf509e8fc6e0363bd6-3.11.0-deaf509.json: aiohttp, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.05x
- 95% likely to have a slowdown of 1.04x
- 99% likely to have a slowdown of 1.03x
