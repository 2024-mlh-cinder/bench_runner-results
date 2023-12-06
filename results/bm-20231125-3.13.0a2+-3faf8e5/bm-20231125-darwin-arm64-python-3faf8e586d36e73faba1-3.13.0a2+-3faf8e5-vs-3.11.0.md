
# Results vs. 3.11.0

- fork: python
- ref: 3faf8e586d36e73faba1
- machine: darwin-arm64
- commit hash: 3faf8e5
- commit date: 2023-11-25
- overall geometric mean: 1.04x slower
- HPT reliability: 99.99%
- HPT 99th percentile: 1.02x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-darwin-arm64-python-deaf509e8fc6e0363bd6-3.11.0-deaf509 | bm-20231125-darwin-arm64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|----------------|:-------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| 2to3           | 154 ms                                                              | 174 ms: 1.14x slower                                                   |
| chameleon      | 4.21 ms                                                             | 5.13 ms: 1.22x slower                                                  |
| docutils       | 1.43 sec                                                            | 1.51 sec: 1.05x slower                                                 |
| Geometric mean | (ref)                                                               | 1.10x slower                                                           |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20221024-darwin-arm64-python-deaf509e8fc6e0363bd6-3.11.0-deaf509 | bm-20231125-darwin-arm64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|----------------------------|:-------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| async_tree_none            | 277 ms                                                              | 254 ms: 1.09x faster                                                   |
| async_tree_memoization     | 353 ms                                                              | 331 ms: 1.07x faster                                                   |
| async_tree_memoization_tg  | 351 ms                                                              | 332 ms: 1.06x faster                                                   |
| async_tree_io_tg           | 723 ms                                                              | 686 ms: 1.05x faster                                                   |
| async_tree_none_tg         | 277 ms                                                              | 267 ms: 1.03x faster                                                   |
| async_tree_cpu_io_mixed_tg | 548 ms                                                              | 542 ms: 1.01x faster                                                   |
| async_tree_io              | 691 ms                                                              | 704 ms: 1.02x slower                                                   |
| async_tree_cpu_io_mixed    | 516 ms                                                              | 526 ms: 1.02x slower                                                   |
| Geometric mean             | (ref)                                                               | 1.03x faster                                                           |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-darwin-arm64-python-deaf509e8fc6e0363bd6-3.11.0-deaf509 | bm-20231125-darwin-arm64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|----------------|:-------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| pidigits       | 280 ms                                                              | 282 ms: 1.01x slower                                                   |
| float          | 55.1 ms                                                             | 58.1 ms: 1.05x slower                                                  |
| nbody          | 68.5 ms                                                             | 81.9 ms: 1.20x slower                                                  |
| Geometric mean | (ref)                                                               | 1.08x slower                                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-darwin-arm64-python-deaf509e8fc6e0363bd6-3.11.0-deaf509 | bm-20231125-darwin-arm64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|----------------|:-------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| regex_dna      | 149 ms                                                              | 152 ms: 1.02x slower                                                   |
| regex_effbot   | 2.45 ms                                                             | 2.64 ms: 1.08x slower                                                  |
| regex_compile  | 73.5 ms                                                             | 79.5 ms: 1.08x slower                                                  |
| regex_v8       | 15.4 ms                                                             | 16.9 ms: 1.10x slower                                                  |
| Geometric mean | (ref)                                                               | 1.07x slower                                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-darwin-arm64-python-deaf509e8fc6e0363bd6-3.11.0-deaf509 | bm-20231125-darwin-arm64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|----------------------|:-------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| json_dumps           | 7.58 ms                                                             | 6.55 ms: 1.16x faster                                                  |
| pickle_pure_python   | 210 us                                                              | 209 us: 1.01x faster                                                   |
| unpickle_pure_python | 162 us                                                              | 165 us: 1.02x slower                                                   |
| pickle               | 7.17 us                                                             | 7.41 us: 1.03x slower                                                  |
| pickle_dict          | 17.0 us                                                             | 18.0 us: 1.06x slower                                                  |
| pickle_list          | 2.68 us                                                             | 2.89 us: 1.08x slower                                                  |
| unpickle             | 8.35 us                                                             | 9.08 us: 1.09x slower                                                  |
| xml_etree_parse      | 97.6 ms                                                             | 107 ms: 1.10x slower                                                   |
| json_loads           | 15.5 us                                                             | 17.4 us: 1.12x slower                                                  |
| xml_etree_iterparse  | 67.5 ms                                                             | 76.4 ms: 1.13x slower                                                  |
| unpickle_list        | 2.76 us                                                             | 3.13 us: 1.14x slower                                                  |
| xml_etree_process    | 34.1 ms                                                             | 40.6 ms: 1.19x slower                                                  |
| tomli_loads          | 1.32 sec                                                            | 1.60 sec: 1.21x slower                                                 |
| xml_etree_generate   | 47.1 ms                                                             | 58.2 ms: 1.24x slower                                                  |
| Geometric mean       | (ref)                                                               | 1.09x slower                                                           |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-darwin-arm64-python-deaf509e8fc6e0363bd6-3.11.0-deaf509 | bm-20231125-darwin-arm64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|------------------------|:-------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| python_startup_no_site | 9.37 ms                                                             | 10.1 ms: 1.08x slower                                                  |
| Geometric mean         | (ref)                                                               | 1.04x slower                                                           |

Benchmark hidden because not significant (1): python_startup

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-darwin-arm64-python-deaf509e8fc6e0363bd6-3.11.0-deaf509 | bm-20231125-darwin-arm64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|-----------|:-------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| mako      | 8.25 ms                                                             | 7.78 ms: 1.06x faster                                                  |

All benchmarks:
===============

| Benchmark                  | bm-20221024-darwin-arm64-python-deaf509e8fc6e0363bd6-3.11.0-deaf509 | bm-20231125-darwin-arm64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|----------------------------|:-------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| typing_runtime_protocols   | 322 us                                                              | 77.6 us: 4.14x faster                                                  |
| asyncio_tcp                | 664 ms                                                              | 430 ms: 1.54x faster                                                   |
| comprehensions             | 14.6 us                                                             | 12.6 us: 1.16x faster                                                  |
| json_dumps                 | 7.58 ms                                                             | 6.55 ms: 1.16x faster                                                  |
| raytrace                   | 205 ms                                                              | 183 ms: 1.12x faster                                                   |
| chaos                      | 48.2 ms                                                             | 43.0 ms: 1.12x faster                                                  |
| mdp                        | 1.84 sec                                                            | 1.64 sec: 1.12x faster                                                 |
| unpack_sequence            | 32.3 ns                                                             | 29.0 ns: 1.11x faster                                                  |
| generators                 | 29.0 ms                                                             | 26.1 ms: 1.11x faster                                                  |
| deepcopy_memo              | 28.7 us                                                             | 26.0 us: 1.10x faster                                                  |
| deltablue                  | 2.69 ms                                                             | 2.45 ms: 1.10x faster                                                  |
| async_tree_none            | 277 ms                                                              | 254 ms: 1.09x faster                                                   |
| asyncio_tcp_ssl            | 1.43 sec                                                            | 1.31 sec: 1.09x faster                                                 |
| async_tree_memoization     | 353 ms                                                              | 331 ms: 1.07x faster                                                   |
| mako                       | 8.25 ms                                                             | 7.78 ms: 1.06x faster                                                  |
| async_tree_memoization_tg  | 351 ms                                                              | 332 ms: 1.06x faster                                                   |
| sympy_sum                  | 80.8 ms                                                             | 76.6 ms: 1.05x faster                                                  |
| async_tree_io_tg           | 723 ms                                                              | 686 ms: 1.05x faster                                                   |
| gc_traversal               | 2.53 ms                                                             | 2.40 ms: 1.05x faster                                                  |
| sqlglot_parse              | 874 us                                                              | 834 us: 1.05x faster                                                   |
| async_tree_none_tg         | 277 ms                                                              | 267 ms: 1.03x faster                                                   |
| sqlglot_transpile          | 1.04 ms                                                             | 1.01 ms: 1.02x faster                                                  |
| create_gc_cycles           | 714 us                                                              | 704 us: 1.02x faster                                                   |
| async_tree_cpu_io_mixed_tg | 548 ms                                                              | 542 ms: 1.01x faster                                                   |
| pickle_pure_python         | 210 us                                                              | 209 us: 1.01x faster                                                   |
| asyncio_websockets         | 408 ms                                                              | 409 ms: 1.00x slower                                                   |
| meteor_contest             | 75.3 ms                                                             | 75.8 ms: 1.01x slower                                                  |
| pidigits                   | 280 ms                                                              | 282 ms: 1.01x slower                                                   |
| deepcopy                   | 232 us                                                              | 234 us: 1.01x slower                                                   |
| regex_dna                  | 149 ms                                                              | 152 ms: 1.02x slower                                                   |
| unpickle_pure_python       | 162 us                                                              | 165 us: 1.02x slower                                                   |
| async_tree_io              | 691 ms                                                              | 704 ms: 1.02x slower                                                   |
| async_tree_cpu_io_mixed    | 516 ms                                                              | 526 ms: 1.02x slower                                                   |
| sympy_str                  | 144 ms                                                              | 148 ms: 1.03x slower                                                   |
| crypto_pyaes               | 47.9 ms                                                             | 49.2 ms: 1.03x slower                                                  |
| dulwich_log                | 29.2 ms                                                             | 30.1 ms: 1.03x slower                                                  |
| pickle                     | 7.17 us                                                             | 7.41 us: 1.03x slower                                                  |
| go                         | 102 ms                                                              | 106 ms: 1.04x slower                                                   |
| bench_mp_pool              | 42.1 ms                                                             | 43.8 ms: 1.04x slower                                                  |
| dask                       | 219 ms                                                              | 229 ms: 1.04x slower                                                   |
| logging_simple             | 3.45 us                                                             | 3.63 us: 1.05x slower                                                  |
| docutils                   | 1.43 sec                                                            | 1.51 sec: 1.05x slower                                                 |
| float                      | 55.1 ms                                                             | 58.1 ms: 1.05x slower                                                  |
| scimark_sparse_mat_mult    | 3.00 ms                                                             | 3.17 ms: 1.06x slower                                                  |
| richards_super             | 36.7 ms                                                             | 38.9 ms: 1.06x slower                                                  |
| logging_format             | 3.73 us                                                             | 3.95 us: 1.06x slower                                                  |
| pickle_dict                | 17.0 us                                                             | 18.0 us: 1.06x slower                                                  |
| scimark_monte_carlo        | 45.7 ms                                                             | 48.6 ms: 1.06x slower                                                  |
| deepcopy_reduce            | 1.96 us                                                             | 2.08 us: 1.06x slower                                                  |
| regex_effbot               | 2.45 ms                                                             | 2.64 ms: 1.08x slower                                                  |
| pathlib                    | 23.0 ms                                                             | 24.8 ms: 1.08x slower                                                  |
| pickle_list                | 2.68 us                                                             | 2.89 us: 1.08x slower                                                  |
| pycparser                  | 658 ms                                                              | 712 ms: 1.08x slower                                                   |
| spectral_norm              | 69.4 ms                                                             | 75.1 ms: 1.08x slower                                                  |
| regex_compile              | 73.5 ms                                                             | 79.5 ms: 1.08x slower                                                  |
| python_startup_no_site     | 9.37 ms                                                             | 10.1 ms: 1.08x slower                                                  |
| sympy_expand               | 236 ms                                                              | 256 ms: 1.09x slower                                                   |
| json                       | 2.77 ms                                                             | 3.01 ms: 1.09x slower                                                  |
| unpickle                   | 8.35 us                                                             | 9.08 us: 1.09x slower                                                  |
| regex_v8                   | 15.4 ms                                                             | 16.9 ms: 1.10x slower                                                  |
| xml_etree_parse            | 97.6 ms                                                             | 107 ms: 1.10x slower                                                   |
| scimark_lu                 | 67.9 ms                                                             | 74.8 ms: 1.10x slower                                                  |
| pprint_pformat             | 986 ms                                                              | 1.09 sec: 1.10x slower                                                 |
| hexiom                     | 4.55 ms                                                             | 5.03 ms: 1.11x slower                                                  |
| bench_thread_pool          | 467 us                                                              | 516 us: 1.11x slower                                                   |
| logging_silent             | 64.3 ns                                                             | 71.4 ns: 1.11x slower                                                  |
| pprint_safe_repr           | 480 ms                                                              | 535 ms: 1.12x slower                                                   |
| json_loads                 | 15.5 us                                                             | 17.4 us: 1.12x slower                                                  |
| xml_etree_iterparse        | 67.5 ms                                                             | 76.4 ms: 1.13x slower                                                  |
| richards                   | 30.7 ms                                                             | 34.8 ms: 1.13x slower                                                  |
| unpickle_list              | 2.76 us                                                             | 3.13 us: 1.14x slower                                                  |
| 2to3                       | 154 ms                                                              | 174 ms: 1.14x slower                                                   |
| scimark_fft                | 186 ms                                                              | 213 ms: 1.14x slower                                                   |
| nqueens                    | 54.3 ms                                                             | 62.6 ms: 1.15x slower                                                  |
| coverage                   | 41.4 ms                                                             | 47.9 ms: 1.16x slower                                                  |
| pyflate                    | 295 ms                                                              | 344 ms: 1.16x slower                                                   |
| fannkuch                   | 247 ms                                                              | 288 ms: 1.17x slower                                                   |
| coroutines                 | 16.4 ms                                                             | 19.2 ms: 1.17x slower                                                  |
| xml_etree_process          | 34.1 ms                                                             | 40.6 ms: 1.19x slower                                                  |
| nbody                      | 68.5 ms                                                             | 81.9 ms: 1.20x slower                                                  |
| sqlglot_normalize          | 160 ms                                                              | 192 ms: 1.20x slower                                                   |
| sqlglot_optimize           | 29.6 ms                                                             | 35.8 ms: 1.21x slower                                                  |
| sqlite_synth               | 1.36 us                                                             | 1.64 us: 1.21x slower                                                  |
| tomli_loads                | 1.32 sec                                                            | 1.60 sec: 1.21x slower                                                 |
| chameleon                  | 4.21 ms                                                             | 5.13 ms: 1.22x slower                                                  |
| xml_etree_generate         | 47.1 ms                                                             | 58.2 ms: 1.24x slower                                                  |
| mypy2                      | 187 ms                                                              | 260 ms: 1.39x slower                                                   |
| scimark_sor                | 74.4 ms                                                             | 107 ms: 1.44x slower                                                   |
| telco                      | 3.17 ms                                                             | 4.65 ms: 1.47x slower                                                  |
| async_generators           | 191 ms                                                              | 304 ms: 1.59x slower                                                   |
| Geometric mean             | (ref)                                                               | 1.04x slower                                                           |

Benchmark hidden because not significant (3): sympy_integrate, python_startup, tornado_http
Ignored benchmarks (11) of results/bm-20221024-3.11.0-deaf509/bm-20221024-darwin-arm64-python-deaf509e8fc6e0363bd6-3.11.0-deaf509.json: aiohttp, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift


# HPT report

- Reliability score: 99.99% likely to be slow
- 90% likely to have a slowdown of 1.03x
- 95% likely to have a slowdown of 1.02x
- 99% likely to have a slowdown of 1.02x
