
# Results vs. 3.12.0

- fork: python
- ref: 48dfd74a9db9d4aa9c6f
- machine: darwin-arm64
- commit hash: 48dfd74
- commit date: 2023-11-28
- overall geometric mean: 1.04x slower \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.01x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0 | bm-20231128-darwin-arm64-python-48dfd74a9db9d4aa9c6f-3.13.0a2+-48dfd74 |
|----------------|:-------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| 2to3           | 170 ms                                                              | 175 ms: 1.03x slower                                                   |
| chameleon      | 4.51 ms                                                             | 5.09 ms: 1.13x slower                                                  |
| docutils       | 1.53 sec                                                            | 1.51 sec: 1.02x faster                                                 |
| Geometric mean | (ref)                                                               | 1.04x slower                                                           |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0 | bm-20231128-darwin-arm64-python-48dfd74a9db9d4aa9c6f-3.13.0a2+-48dfd74 |
|----------------------------|:-------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| async_tree_cpu_io_mixed    | 520 ms                                                              | 527 ms: 1.01x slower                                                   |
| async_tree_cpu_io_mixed_tg | 530 ms                                                              | 543 ms: 1.02x slower                                                   |
| async_tree_io_tg           | 664 ms                                                              | 688 ms: 1.04x slower                                                   |
| async_tree_memoization_tg  | 316 ms                                                              | 333 ms: 1.05x slower                                                   |
| async_tree_none_tg         | 252 ms                                                              | 267 ms: 1.06x slower                                                   |
| async_tree_io              | 659 ms                                                              | 707 ms: 1.07x slower                                                   |
| async_tree_memoization     | 306 ms                                                              | 333 ms: 1.09x slower                                                   |
| Geometric mean             | (ref)                                                               | 1.04x slower                                                           |

Benchmark hidden because not significant (1): async_tree_none

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0 | bm-20231128-darwin-arm64-python-48dfd74a9db9d4aa9c6f-3.13.0a2+-48dfd74 |
|----------------|:-------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| float          | 58.0 ms                                                             | 58.5 ms: 1.01x slower                                                  |
| pidigits       | 282 ms                                                              | 294 ms: 1.04x slower                                                   |
| nbody          | 68.8 ms                                                             | 84.5 ms: 1.23x slower                                                  |
| Geometric mean | (ref)                                                               | 1.09x slower                                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0 | bm-20231128-darwin-arm64-python-48dfd74a9db9d4aa9c6f-3.13.0a2+-48dfd74 |
|----------------|:-------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| regex_dna      | 152 ms                                                              | 150 ms: 1.01x faster                                                   |
| regex_effbot   | 2.58 ms                                                             | 2.57 ms: 1.00x faster                                                  |
| regex_compile  | 75.8 ms                                                             | 80.0 ms: 1.06x slower                                                  |
| regex_v8       | 15.6 ms                                                             | 16.9 ms: 1.08x slower                                                  |
| Geometric mean | (ref)                                                               | 1.03x slower                                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0 | bm-20231128-darwin-arm64-python-48dfd74a9db9d4aa9c6f-3.13.0a2+-48dfd74 |
|----------------------|:-------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| unpickle_list        | 3.20 us                                                             | 3.12 us: 1.03x faster                                                  |
| unpickle             | 9.26 us                                                             | 9.04 us: 1.03x faster                                                  |
| xml_etree_parse      | 106 ms                                                              | 107 ms: 1.01x slower                                                   |
| pickle_list          | 2.89 us                                                             | 2.94 us: 1.02x slower                                                  |
| json_dumps           | 6.48 ms                                                             | 6.62 ms: 1.02x slower                                                  |
| pickle               | 7.35 us                                                             | 7.53 us: 1.02x slower                                                  |
| pickle_dict          | 18.1 us                                                             | 18.6 us: 1.03x slower                                                  |
| xml_etree_iterparse  | 74.2 ms                                                             | 76.8 ms: 1.03x slower                                                  |
| xml_etree_generate   | 55.8 ms                                                             | 58.4 ms: 1.05x slower                                                  |
| xml_etree_process    | 38.6 ms                                                             | 41.2 ms: 1.07x slower                                                  |
| pickle_pure_python   | 189 us                                                              | 209 us: 1.11x slower                                                   |
| unpickle_pure_python | 144 us                                                              | 165 us: 1.14x slower                                                   |
| tomli_loads          | 1.40 sec                                                            | 1.61 sec: 1.15x slower                                                 |
| Geometric mean       | (ref)                                                               | 1.04x slower                                                           |

Benchmark hidden because not significant (1): json_loads

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0 | bm-20231128-darwin-arm64-python-48dfd74a9db9d4aa9c6f-3.13.0a2+-48dfd74 |
|------------------------|:-------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| python_startup_no_site | 9.90 ms                                                             | 10.9 ms: 1.10x slower                                                  |
| Geometric mean         | (ref)                                                               | 1.05x slower                                                           |

Benchmark hidden because not significant (1): python_startup

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0 | bm-20231128-darwin-arm64-python-48dfd74a9db9d4aa9c6f-3.13.0a2+-48dfd74 |
|-----------|:-------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| mako      | 7.52 ms                                                             | 7.75 ms: 1.03x slower                                                  |

All benchmarks:
===============

| Benchmark                  | bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0 | bm-20231128-darwin-arm64-python-48dfd74a9db9d4aa9c6f-3.13.0a2+-48dfd74 |
|----------------------------|:-------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| raytrace                   | 245 ms                                                              | 183 ms: 1.34x faster                                                   |
| comprehensions             | 15.7 us                                                             | 12.7 us: 1.24x faster                                                  |
| typing_runtime_protocols   | 90.6 us                                                             | 78.0 us: 1.16x faster                                                  |
| generators                 | 28.6 ms                                                             | 26.1 ms: 1.10x faster                                                  |
| sqlglot_parse              | 895 us                                                              | 831 us: 1.08x faster                                                   |
| deltablue                  | 2.59 ms                                                             | 2.44 ms: 1.06x faster                                                  |
| sqlglot_transpile          | 1.07 ms                                                             | 1.01 ms: 1.06x faster                                                  |
| crypto_pyaes               | 51.8 ms                                                             | 49.0 ms: 1.06x faster                                                  |
| bench_mp_pool              | 46.8 ms                                                             | 44.5 ms: 1.05x faster                                                  |
| sympy_sum                  | 79.1 ms                                                             | 76.2 ms: 1.04x faster                                                  |
| chaos                      | 44.6 ms                                                             | 43.0 ms: 1.04x faster                                                  |
| json                       | 3.11 ms                                                             | 3.03 ms: 1.03x faster                                                  |
| scimark_monte_carlo        | 50.0 ms                                                             | 48.6 ms: 1.03x faster                                                  |
| unpickle_list              | 3.20 us                                                             | 3.12 us: 1.03x faster                                                  |
| unpickle                   | 9.26 us                                                             | 9.04 us: 1.03x faster                                                  |
| logging_simple             | 3.70 us                                                             | 3.62 us: 1.02x faster                                                  |
| sympy_str                  | 151 ms                                                              | 148 ms: 1.02x faster                                                   |
| logging_format             | 3.98 us                                                             | 3.91 us: 1.02x faster                                                  |
| docutils                   | 1.53 sec                                                            | 1.51 sec: 1.02x faster                                                 |
| regex_dna                  | 152 ms                                                              | 150 ms: 1.01x faster                                                   |
| sympy_integrate            | 11.3 ms                                                             | 11.2 ms: 1.01x faster                                                  |
| async_generators           | 306 ms                                                              | 305 ms: 1.00x faster                                                   |
| regex_effbot               | 2.58 ms                                                             | 2.57 ms: 1.00x faster                                                  |
| spectral_norm              | 74.6 ms                                                             | 74.9 ms: 1.00x slower                                                  |
| dulwich_log                | 29.8 ms                                                             | 30.0 ms: 1.01x slower                                                  |
| float                      | 58.0 ms                                                             | 58.5 ms: 1.01x slower                                                  |
| gc_traversal               | 2.40 ms                                                             | 2.42 ms: 1.01x slower                                                  |
| scimark_sparse_mat_mult    | 3.14 ms                                                             | 3.18 ms: 1.01x slower                                                  |
| xml_etree_parse            | 106 ms                                                              | 107 ms: 1.01x slower                                                   |
| async_tree_cpu_io_mixed    | 520 ms                                                              | 527 ms: 1.01x slower                                                   |
| pickle_list                | 2.89 us                                                             | 2.94 us: 1.02x slower                                                  |
| json_dumps                 | 6.48 ms                                                             | 6.62 ms: 1.02x slower                                                  |
| dask                       | 224 ms                                                              | 229 ms: 1.02x slower                                                   |
| sympy_expand               | 250 ms                                                              | 255 ms: 1.02x slower                                                   |
| bench_thread_pool          | 503 us                                                              | 514 us: 1.02x slower                                                   |
| pickle                     | 7.35 us                                                             | 7.53 us: 1.02x slower                                                  |
| async_tree_cpu_io_mixed_tg | 530 ms                                                              | 543 ms: 1.02x slower                                                   |
| 2to3                       | 170 ms                                                              | 175 ms: 1.03x slower                                                   |
| pickle_dict                | 18.1 us                                                             | 18.6 us: 1.03x slower                                                  |
| deepcopy_reduce            | 2.03 us                                                             | 2.09 us: 1.03x slower                                                  |
| create_gc_cycles           | 702 us                                                              | 724 us: 1.03x slower                                                   |
| mako                       | 7.52 ms                                                             | 7.75 ms: 1.03x slower                                                  |
| sqlite_synth               | 1.60 us                                                             | 1.66 us: 1.03x slower                                                  |
| asyncio_tcp_ssl            | 1.26 sec                                                            | 1.30 sec: 1.03x slower                                                 |
| meteor_contest             | 72.9 ms                                                             | 75.3 ms: 1.03x slower                                                  |
| sqlglot_normalize          | 186 ms                                                              | 192 ms: 1.03x slower                                                   |
| xml_etree_iterparse        | 74.2 ms                                                             | 76.8 ms: 1.03x slower                                                  |
| pathlib                    | 24.4 ms                                                             | 25.2 ms: 1.04x slower                                                  |
| async_tree_io_tg           | 664 ms                                                              | 688 ms: 1.04x slower                                                   |
| logging_silent             | 67.8 ns                                                             | 70.3 ns: 1.04x slower                                                  |
| pidigits                   | 282 ms                                                              | 294 ms: 1.04x slower                                                   |
| deepcopy                   | 224 us                                                              | 233 us: 1.04x slower                                                   |
| sqlglot_optimize           | 34.3 ms                                                             | 35.7 ms: 1.04x slower                                                  |
| xml_etree_generate         | 55.8 ms                                                             | 58.4 ms: 1.05x slower                                                  |
| pyflate                    | 328 ms                                                              | 344 ms: 1.05x slower                                                   |
| scimark_lu                 | 71.4 ms                                                             | 75.1 ms: 1.05x slower                                                  |
| async_tree_memoization_tg  | 316 ms                                                              | 333 ms: 1.05x slower                                                   |
| regex_compile              | 75.8 ms                                                             | 80.0 ms: 1.06x slower                                                  |
| deepcopy_memo              | 24.6 us                                                             | 26.0 us: 1.06x slower                                                  |
| async_tree_none_tg         | 252 ms                                                              | 267 ms: 1.06x slower                                                   |
| coroutines                 | 18.2 ms                                                             | 19.3 ms: 1.06x slower                                                  |
| pycparser                  | 667 ms                                                              | 709 ms: 1.06x slower                                                   |
| xml_etree_process          | 38.6 ms                                                             | 41.2 ms: 1.07x slower                                                  |
| scimark_fft                | 198 ms                                                              | 212 ms: 1.07x slower                                                   |
| async_tree_io              | 659 ms                                                              | 707 ms: 1.07x slower                                                   |
| regex_v8                   | 15.6 ms                                                             | 16.9 ms: 1.08x slower                                                  |
| nqueens                    | 59.6 ms                                                             | 64.9 ms: 1.09x slower                                                  |
| async_tree_memoization     | 306 ms                                                              | 333 ms: 1.09x slower                                                   |
| pprint_pformat             | 1.00 sec                                                            | 1.10 sec: 1.10x slower                                                 |
| python_startup_no_site     | 9.90 ms                                                             | 10.9 ms: 1.10x slower                                                  |
| pickle_pure_python         | 189 us                                                              | 209 us: 1.11x slower                                                   |
| richards_super             | 34.9 ms                                                             | 39.0 ms: 1.12x slower                                                  |
| richards                   | 31.0 ms                                                             | 34.8 ms: 1.12x slower                                                  |
| chameleon                  | 4.51 ms                                                             | 5.09 ms: 1.13x slower                                                  |
| fannkuch                   | 262 ms                                                              | 296 ms: 1.13x slower                                                   |
| unpickle_pure_python       | 144 us                                                              | 165 us: 1.14x slower                                                   |
| pprint_safe_repr           | 492 ms                                                              | 562 ms: 1.14x slower                                                   |
| scimark_sor                | 93.8 ms                                                             | 108 ms: 1.15x slower                                                   |
| tomli_loads                | 1.40 sec                                                            | 1.61 sec: 1.15x slower                                                 |
| hexiom                     | 4.24 ms                                                             | 5.04 ms: 1.19x slower                                                  |
| nbody                      | 68.8 ms                                                             | 84.5 ms: 1.23x slower                                                  |
| telco                      | 3.79 ms                                                             | 4.71 ms: 1.25x slower                                                  |
| coverage                   | 37.8 ms                                                             | 47.9 ms: 1.27x slower                                                  |
| mypy2                      | 256 ms                                                              | 560 ms: 2.19x slower                                                   |
| Geometric mean             | (ref)                                                               | 1.04x slower                                                           |

Benchmark hidden because not significant (9): async_tree_none, mdp, go, asyncio_websockets, json_loads, python_startup, unpack_sequence, tornado_http, asyncio_tcp
Ignored benchmarks (5) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0.json: aiohttp, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.02x
- 95% likely to have a slowdown of 1.01x
- 99% likely to have a slowdown of 1.01x
