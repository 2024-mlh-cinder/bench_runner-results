
# Results vs. 3.12.0

- fork: python
- ref: 3faf8e586d36e73faba1
- machine: darwin-arm64
- commit hash: 3faf8e5
- commit date: 2023-11-25
- overall geometric mean: 1.02x slower
- HPT reliability: 99.99%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0 | bm-20231125-darwin-arm64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|----------------|:-------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| 2to3           | 170 ms                                                              | 174 ms: 1.03x slower                                                   |
| chameleon      | 4.51 ms                                                             | 5.13 ms: 1.14x slower                                                  |
| docutils       | 1.53 sec                                                            | 1.51 sec: 1.02x faster                                                 |
| Geometric mean | (ref)                                                               | 1.04x slower                                                           |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0 | bm-20231125-darwin-arm64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|----------------------------|:-------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| async_tree_none            | 258 ms                                                              | 254 ms: 1.02x faster                                                   |
| async_tree_cpu_io_mixed    | 520 ms                                                              | 526 ms: 1.01x slower                                                   |
| async_tree_cpu_io_mixed_tg | 530 ms                                                              | 542 ms: 1.02x slower                                                   |
| async_tree_io_tg           | 664 ms                                                              | 686 ms: 1.03x slower                                                   |
| async_tree_memoization_tg  | 316 ms                                                              | 332 ms: 1.05x slower                                                   |
| async_tree_none_tg         | 252 ms                                                              | 267 ms: 1.06x slower                                                   |
| async_tree_io              | 659 ms                                                              | 704 ms: 1.07x slower                                                   |
| async_tree_memoization     | 306 ms                                                              | 331 ms: 1.08x slower                                                   |
| Geometric mean             | (ref)                                                               | 1.04x slower                                                           |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0 | bm-20231125-darwin-arm64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|----------------|:-------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| nbody          | 68.8 ms                                                             | 81.9 ms: 1.19x slower                                                  |
| Geometric mean | (ref)                                                               | 1.06x slower                                                           |

Benchmark hidden because not significant (2): pidigits, float

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0 | bm-20231125-darwin-arm64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|----------------|:-------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| regex_effbot   | 2.58 ms                                                             | 2.64 ms: 1.02x slower                                                  |
| regex_compile  | 75.8 ms                                                             | 79.5 ms: 1.05x slower                                                  |
| regex_v8       | 15.6 ms                                                             | 16.9 ms: 1.08x slower                                                  |
| Geometric mean | (ref)                                                               | 1.04x slower                                                           |

Benchmark hidden because not significant (1): regex_dna

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0 | bm-20231125-darwin-arm64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|----------------------|:-------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| unpickle_list        | 3.20 us                                                             | 3.13 us: 1.02x faster                                                  |
| unpickle             | 9.26 us                                                             | 9.08 us: 1.02x faster                                                  |
| pickle_dict          | 18.1 us                                                             | 18.0 us: 1.00x faster                                                  |
| json_loads           | 17.3 us                                                             | 17.4 us: 1.00x slower                                                  |
| pickle               | 7.35 us                                                             | 7.41 us: 1.01x slower                                                  |
| xml_etree_parse      | 106 ms                                                              | 107 ms: 1.01x slower                                                   |
| json_dumps           | 6.48 ms                                                             | 6.55 ms: 1.01x slower                                                  |
| xml_etree_iterparse  | 74.2 ms                                                             | 76.4 ms: 1.03x slower                                                  |
| xml_etree_generate   | 55.8 ms                                                             | 58.2 ms: 1.04x slower                                                  |
| xml_etree_process    | 38.6 ms                                                             | 40.6 ms: 1.05x slower                                                  |
| pickle_pure_python   | 189 us                                                              | 209 us: 1.11x slower                                                   |
| unpickle_pure_python | 144 us                                                              | 165 us: 1.14x slower                                                   |
| tomli_loads          | 1.40 sec                                                            | 1.60 sec: 1.14x slower                                                 |
| Geometric mean       | (ref)                                                               | 1.03x slower                                                           |

Benchmark hidden because not significant (1): pickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0 | bm-20231125-darwin-arm64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|------------------------|:-------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| python_startup         | 12.1 ms                                                             | 11.6 ms: 1.05x faster                                                  |
| python_startup_no_site | 9.90 ms                                                             | 10.1 ms: 1.02x slower                                                  |
| Geometric mean         | (ref)                                                               | 1.01x faster                                                           |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0 | bm-20231125-darwin-arm64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|-----------|:-------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| mako      | 7.52 ms                                                             | 7.78 ms: 1.04x slower                                                  |

All benchmarks:
===============

| Benchmark                  | bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0 | bm-20231125-darwin-arm64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|----------------------------|:-------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| raytrace                   | 245 ms                                                              | 183 ms: 1.34x faster                                                   |
| comprehensions             | 15.7 us                                                             | 12.6 us: 1.25x faster                                                  |
| typing_runtime_protocols   | 90.6 us                                                             | 77.6 us: 1.17x faster                                                  |
| generators                 | 28.6 ms                                                             | 26.1 ms: 1.09x faster                                                  |
| sqlglot_parse              | 895 us                                                              | 834 us: 1.07x faster                                                   |
| bench_mp_pool              | 46.8 ms                                                             | 43.8 ms: 1.07x faster                                                  |
| deltablue                  | 2.59 ms                                                             | 2.45 ms: 1.06x faster                                                  |
| sqlglot_transpile          | 1.07 ms                                                             | 1.01 ms: 1.06x faster                                                  |
| crypto_pyaes               | 51.8 ms                                                             | 49.2 ms: 1.05x faster                                                  |
| python_startup             | 12.1 ms                                                             | 11.6 ms: 1.05x faster                                                  |
| chaos                      | 44.6 ms                                                             | 43.0 ms: 1.04x faster                                                  |
| json                       | 3.11 ms                                                             | 3.01 ms: 1.04x faster                                                  |
| sympy_sum                  | 79.1 ms                                                             | 76.6 ms: 1.03x faster                                                  |
| scimark_monte_carlo        | 50.0 ms                                                             | 48.6 ms: 1.03x faster                                                  |
| unpickle_list              | 3.20 us                                                             | 3.13 us: 1.02x faster                                                  |
| sympy_str                  | 151 ms                                                              | 148 ms: 1.02x faster                                                   |
| unpickle                   | 9.26 us                                                             | 9.08 us: 1.02x faster                                                  |
| logging_simple             | 3.70 us                                                             | 3.63 us: 1.02x faster                                                  |
| mdp                        | 1.67 sec                                                            | 1.64 sec: 1.02x faster                                                 |
| async_tree_none            | 258 ms                                                              | 254 ms: 1.02x faster                                                   |
| docutils                   | 1.53 sec                                                            | 1.51 sec: 1.02x faster                                                 |
| sympy_integrate            | 11.3 ms                                                             | 11.2 ms: 1.01x faster                                                  |
| logging_format             | 3.98 us                                                             | 3.95 us: 1.01x faster                                                  |
| async_generators           | 306 ms                                                              | 304 ms: 1.00x faster                                                   |
| pickle_dict                | 18.1 us                                                             | 18.0 us: 1.00x faster                                                  |
| go                         | 106 ms                                                              | 106 ms: 1.00x faster                                                   |
| gc_traversal               | 2.40 ms                                                             | 2.40 ms: 1.00x slower                                                  |
| create_gc_cycles           | 702 us                                                              | 704 us: 1.00x slower                                                   |
| json_loads                 | 17.3 us                                                             | 17.4 us: 1.00x slower                                                  |
| spectral_norm              | 74.6 ms                                                             | 75.1 ms: 1.01x slower                                                  |
| pickle                     | 7.35 us                                                             | 7.41 us: 1.01x slower                                                  |
| dulwich_log                | 29.8 ms                                                             | 30.1 ms: 1.01x slower                                                  |
| scimark_sparse_mat_mult    | 3.14 ms                                                             | 3.17 ms: 1.01x slower                                                  |
| unpack_sequence            | 28.7 ns                                                             | 29.0 ns: 1.01x slower                                                  |
| xml_etree_parse            | 106 ms                                                              | 107 ms: 1.01x slower                                                   |
| json_dumps                 | 6.48 ms                                                             | 6.55 ms: 1.01x slower                                                  |
| async_tree_cpu_io_mixed    | 520 ms                                                              | 526 ms: 1.01x slower                                                   |
| pathlib                    | 24.4 ms                                                             | 24.8 ms: 1.02x slower                                                  |
| dask                       | 224 ms                                                              | 229 ms: 1.02x slower                                                   |
| async_tree_cpu_io_mixed_tg | 530 ms                                                              | 542 ms: 1.02x slower                                                   |
| regex_effbot               | 2.58 ms                                                             | 2.64 ms: 1.02x slower                                                  |
| python_startup_no_site     | 9.90 ms                                                             | 10.1 ms: 1.02x slower                                                  |
| sqlite_synth               | 1.60 us                                                             | 1.64 us: 1.03x slower                                                  |
| deepcopy_reduce            | 2.03 us                                                             | 2.08 us: 1.03x slower                                                  |
| sympy_expand               | 250 ms                                                              | 256 ms: 1.03x slower                                                   |
| bench_thread_pool          | 503 us                                                              | 516 us: 1.03x slower                                                   |
| 2to3                       | 170 ms                                                              | 174 ms: 1.03x slower                                                   |
| xml_etree_iterparse        | 74.2 ms                                                             | 76.4 ms: 1.03x slower                                                  |
| async_tree_io_tg           | 664 ms                                                              | 686 ms: 1.03x slower                                                   |
| sqlglot_normalize          | 186 ms                                                              | 192 ms: 1.03x slower                                                   |
| mako                       | 7.52 ms                                                             | 7.78 ms: 1.04x slower                                                  |
| asyncio_tcp_ssl            | 1.26 sec                                                            | 1.31 sec: 1.04x slower                                                 |
| meteor_contest             | 72.9 ms                                                             | 75.8 ms: 1.04x slower                                                  |
| xml_etree_generate         | 55.8 ms                                                             | 58.2 ms: 1.04x slower                                                  |
| sqlglot_optimize           | 34.3 ms                                                             | 35.8 ms: 1.04x slower                                                  |
| deepcopy                   | 224 us                                                              | 234 us: 1.04x slower                                                   |
| scimark_lu                 | 71.4 ms                                                             | 74.8 ms: 1.05x slower                                                  |
| pyflate                    | 328 ms                                                              | 344 ms: 1.05x slower                                                   |
| regex_compile              | 75.8 ms                                                             | 79.5 ms: 1.05x slower                                                  |
| nqueens                    | 59.6 ms                                                             | 62.6 ms: 1.05x slower                                                  |
| async_tree_memoization_tg  | 316 ms                                                              | 332 ms: 1.05x slower                                                   |
| xml_etree_process          | 38.6 ms                                                             | 40.6 ms: 1.05x slower                                                  |
| logging_silent             | 67.8 ns                                                             | 71.4 ns: 1.05x slower                                                  |
| coroutines                 | 18.2 ms                                                             | 19.2 ms: 1.06x slower                                                  |
| deepcopy_memo              | 24.6 us                                                             | 26.0 us: 1.06x slower                                                  |
| async_tree_none_tg         | 252 ms                                                              | 267 ms: 1.06x slower                                                   |
| pycparser                  | 667 ms                                                              | 712 ms: 1.07x slower                                                   |
| async_tree_io              | 659 ms                                                              | 704 ms: 1.07x slower                                                   |
| scimark_fft                | 198 ms                                                              | 213 ms: 1.08x slower                                                   |
| regex_v8                   | 15.6 ms                                                             | 16.9 ms: 1.08x slower                                                  |
| async_tree_memoization     | 306 ms                                                              | 331 ms: 1.08x slower                                                   |
| pprint_pformat             | 1.00 sec                                                            | 1.09 sec: 1.09x slower                                                 |
| pprint_safe_repr           | 492 ms                                                              | 535 ms: 1.09x slower                                                   |
| fannkuch                   | 262 ms                                                              | 288 ms: 1.10x slower                                                   |
| pickle_pure_python         | 189 us                                                              | 209 us: 1.11x slower                                                   |
| richards_super             | 34.9 ms                                                             | 38.9 ms: 1.11x slower                                                  |
| richards                   | 31.0 ms                                                             | 34.8 ms: 1.12x slower                                                  |
| chameleon                  | 4.51 ms                                                             | 5.13 ms: 1.14x slower                                                  |
| unpickle_pure_python       | 144 us                                                              | 165 us: 1.14x slower                                                   |
| scimark_sor                | 93.8 ms                                                             | 107 ms: 1.14x slower                                                   |
| tomli_loads                | 1.40 sec                                                            | 1.60 sec: 1.14x slower                                                 |
| hexiom                     | 4.24 ms                                                             | 5.03 ms: 1.19x slower                                                  |
| nbody                      | 68.8 ms                                                             | 81.9 ms: 1.19x slower                                                  |
| telco                      | 3.79 ms                                                             | 4.65 ms: 1.23x slower                                                  |
| coverage                   | 37.8 ms                                                             | 47.9 ms: 1.27x slower                                                  |
| Geometric mean             | (ref)                                                               | 1.02x slower                                                           |

Benchmark hidden because not significant (8): pidigits, regex_dna, asyncio_websockets, float, pickle_list, tornado_http, mypy2, asyncio_tcp
Ignored benchmarks (5) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0.json: aiohttp, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 99.99% likely to be slow
- 90% likely to have a slowdown of 1.01x
- 95% likely to have a slowdown of 1.01x
- 99% likely to have a slowdown of 1.00x
