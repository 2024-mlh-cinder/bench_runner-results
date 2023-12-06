
# Results vs. 3.12.0

- fork: brandtbucher
- ref: justin
- machine: darwin-arm64
- commit hash: dfface9
- commit date: 2023-11-28
- overall geometric mean: 1.05x slower \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.03x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0 | bm-20231128-darwin-arm64-brandtbucher-justin-3.13.0a2+-dfface9 |
|----------------|:-------------------------------------------------------------------:|:--------------------------------------------------------------:|
| 2to3           | 170 ms                                                              | 181 ms: 1.07x slower                                           |
| chameleon      | 4.51 ms                                                             | 5.15 ms: 1.14x slower                                          |
| docutils       | 1.53 sec                                                            | 1.52 sec: 1.00x faster                                         |
| tornado_http   | 70.5 ms                                                             | 73.7 ms: 1.04x slower                                          |
| Geometric mean | (ref)                                                               | 1.06x slower                                                   |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0 | bm-20231128-darwin-arm64-brandtbucher-justin-3.13.0a2+-dfface9 |
|----------------------------|:-------------------------------------------------------------------:|:--------------------------------------------------------------:|
| async_tree_cpu_io_mixed    | 520 ms                                                              | 528 ms: 1.02x slower                                           |
| async_tree_cpu_io_mixed_tg | 530 ms                                                              | 543 ms: 1.02x slower                                           |
| async_tree_io_tg           | 664 ms                                                              | 687 ms: 1.03x slower                                           |
| async_tree_memoization_tg  | 316 ms                                                              | 335 ms: 1.06x slower                                           |
| async_tree_none_tg         | 252 ms                                                              | 268 ms: 1.07x slower                                           |
| async_tree_io              | 659 ms                                                              | 707 ms: 1.07x slower                                           |
| async_tree_memoization     | 306 ms                                                              | 332 ms: 1.09x slower                                           |
| Geometric mean             | (ref)                                                               | 1.04x slower                                                   |

Benchmark hidden because not significant (1): async_tree_none

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0 | bm-20231128-darwin-arm64-brandtbucher-justin-3.13.0a2+-dfface9 |
|----------------|:-------------------------------------------------------------------:|:--------------------------------------------------------------:|
| pidigits       | 282 ms                                                              | 283 ms: 1.00x slower                                           |
| float          | 58.0 ms                                                             | 58.7 ms: 1.01x slower                                          |
| nbody          | 68.8 ms                                                             | 80.5 ms: 1.17x slower                                          |
| Geometric mean | (ref)                                                               | 1.06x slower                                                   |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0 | bm-20231128-darwin-arm64-brandtbucher-justin-3.13.0a2+-dfface9 |
|----------------|:-------------------------------------------------------------------:|:--------------------------------------------------------------:|
| regex_dna      | 152 ms                                                              | 149 ms: 1.02x faster                                           |
| regex_effbot   | 2.58 ms                                                             | 2.57 ms: 1.00x faster                                          |
| regex_v8       | 15.6 ms                                                             | 17.0 ms: 1.09x slower                                          |
| regex_compile  | 75.8 ms                                                             | 83.9 ms: 1.11x slower                                          |
| Geometric mean | (ref)                                                               | 1.04x slower                                                   |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0 | bm-20231128-darwin-arm64-brandtbucher-justin-3.13.0a2+-dfface9 |
|----------------------|:-------------------------------------------------------------------:|:--------------------------------------------------------------:|
| unpickle_list        | 3.20 us                                                             | 3.12 us: 1.03x faster                                          |
| unpickle             | 9.26 us                                                             | 9.11 us: 1.02x faster                                          |
| pickle_dict          | 18.1 us                                                             | 18.0 us: 1.01x faster                                          |
| pickle               | 7.35 us                                                             | 7.39 us: 1.01x slower                                          |
| xml_etree_parse      | 106 ms                                                              | 107 ms: 1.01x slower                                           |
| json_dumps           | 6.48 ms                                                             | 6.57 ms: 1.01x slower                                          |
| xml_etree_iterparse  | 74.2 ms                                                             | 76.8 ms: 1.03x slower                                          |
| xml_etree_generate   | 55.8 ms                                                             | 59.2 ms: 1.06x slower                                          |
| xml_etree_process    | 38.6 ms                                                             | 41.3 ms: 1.07x slower                                          |
| tomli_loads          | 1.40 sec                                                            | 1.53 sec: 1.09x slower                                         |
| pickle_pure_python   | 189 us                                                              | 209 us: 1.11x slower                                           |
| unpickle_pure_python | 144 us                                                              | 171 us: 1.18x slower                                           |
| Geometric mean       | (ref)                                                               | 1.04x slower                                                   |

Benchmark hidden because not significant (2): json_loads, pickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0 | bm-20231128-darwin-arm64-brandtbucher-justin-3.13.0a2+-dfface9 |
|------------------------|:-------------------------------------------------------------------:|:--------------------------------------------------------------:|
| python_startup_no_site | 9.90 ms                                                             | 10.8 ms: 1.09x slower                                          |
| Geometric mean         | (ref)                                                               | 1.05x slower                                                   |

Benchmark hidden because not significant (1): python_startup

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0 | bm-20231128-darwin-arm64-brandtbucher-justin-3.13.0a2+-dfface9 |
|-----------|:-------------------------------------------------------------------:|:--------------------------------------------------------------:|
| mako      | 7.52 ms                                                             | 7.96 ms: 1.06x slower                                          |

All benchmarks:
===============

| Benchmark                  | bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0 | bm-20231128-darwin-arm64-brandtbucher-justin-3.13.0a2+-dfface9 |
|----------------------------|:-------------------------------------------------------------------:|:--------------------------------------------------------------:|
| raytrace                   | 245 ms                                                              | 189 ms: 1.30x faster                                           |
| typing_runtime_protocols   | 90.6 us                                                             | 79.1 us: 1.15x faster                                          |
| comprehensions             | 15.7 us                                                             | 13.8 us: 1.14x faster                                          |
| generators                 | 28.6 ms                                                             | 26.0 ms: 1.10x faster                                          |
| sqlglot_parse              | 895 us                                                              | 849 us: 1.05x faster                                           |
| sqlglot_transpile          | 1.07 ms                                                             | 1.04 ms: 1.03x faster                                          |
| crypto_pyaes               | 51.8 ms                                                             | 50.3 ms: 1.03x faster                                          |
| json                       | 3.11 ms                                                             | 3.03 ms: 1.03x faster                                          |
| unpickle_list              | 3.20 us                                                             | 3.12 us: 1.03x faster                                          |
| regex_dna                  | 152 ms                                                              | 149 ms: 1.02x faster                                           |
| logging_simple             | 3.70 us                                                             | 3.64 us: 1.02x faster                                          |
| unpickle                   | 9.26 us                                                             | 9.11 us: 1.02x faster                                          |
| logging_format             | 3.98 us                                                             | 3.92 us: 1.02x faster                                          |
| deltablue                  | 2.59 ms                                                             | 2.57 ms: 1.01x faster                                          |
| pickle_dict                | 18.1 us                                                             | 18.0 us: 1.01x faster                                          |
| docutils                   | 1.53 sec                                                            | 1.52 sec: 1.00x faster                                         |
| regex_effbot               | 2.58 ms                                                             | 2.57 ms: 1.00x faster                                          |
| create_gc_cycles           | 702 us                                                              | 701 us: 1.00x faster                                           |
| pidigits                   | 282 ms                                                              | 283 ms: 1.00x slower                                           |
| chaos                      | 44.6 ms                                                             | 44.9 ms: 1.01x slower                                          |
| pickle                     | 7.35 us                                                             | 7.39 us: 1.01x slower                                          |
| unpack_sequence            | 28.7 ns                                                             | 29.0 ns: 1.01x slower                                          |
| xml_etree_parse            | 106 ms                                                              | 107 ms: 1.01x slower                                           |
| float                      | 58.0 ms                                                             | 58.7 ms: 1.01x slower                                          |
| json_dumps                 | 6.48 ms                                                             | 6.57 ms: 1.01x slower                                          |
| async_tree_cpu_io_mixed    | 520 ms                                                              | 528 ms: 1.02x slower                                           |
| scimark_monte_carlo        | 50.0 ms                                                             | 50.8 ms: 1.02x slower                                          |
| sympy_str                  | 151 ms                                                              | 154 ms: 1.02x slower                                           |
| pathlib                    | 24.4 ms                                                             | 24.9 ms: 1.02x slower                                          |
| dulwich_log                | 29.8 ms                                                             | 30.5 ms: 1.02x slower                                          |
| sympy_sum                  | 79.1 ms                                                             | 81.0 ms: 1.02x slower                                          |
| async_tree_cpu_io_mixed_tg | 530 ms                                                              | 543 ms: 1.02x slower                                           |
| mdp                        | 1.67 sec                                                            | 1.72 sec: 1.03x slower                                         |
| dask                       | 224 ms                                                              | 231 ms: 1.03x slower                                           |
| async_tree_io_tg           | 664 ms                                                              | 687 ms: 1.03x slower                                           |
| xml_etree_iterparse        | 74.2 ms                                                             | 76.8 ms: 1.03x slower                                          |
| sqlite_synth               | 1.60 us                                                             | 1.66 us: 1.04x slower                                          |
| asyncio_tcp_ssl            | 1.26 sec                                                            | 1.31 sec: 1.04x slower                                         |
| sympy_expand               | 250 ms                                                              | 260 ms: 1.04x slower                                           |
| deepcopy_reduce            | 2.03 us                                                             | 2.12 us: 1.04x slower                                          |
| tornado_http               | 70.5 ms                                                             | 73.7 ms: 1.04x slower                                          |
| async_generators           | 306 ms                                                              | 321 ms: 1.05x slower                                           |
| scimark_sparse_mat_mult    | 3.14 ms                                                             | 3.31 ms: 1.05x slower                                          |
| bench_thread_pool          | 503 us                                                              | 531 us: 1.06x slower                                           |
| mako                       | 7.52 ms                                                             | 7.96 ms: 1.06x slower                                          |
| sympy_integrate            | 11.3 ms                                                             | 12.0 ms: 1.06x slower                                          |
| sqlglot_normalize          | 186 ms                                                              | 197 ms: 1.06x slower                                           |
| coroutines                 | 18.2 ms                                                             | 19.3 ms: 1.06x slower                                          |
| xml_etree_generate         | 55.8 ms                                                             | 59.2 ms: 1.06x slower                                          |
| async_tree_memoization_tg  | 316 ms                                                              | 335 ms: 1.06x slower                                           |
| logging_silent             | 67.8 ns                                                             | 71.9 ns: 1.06x slower                                          |
| deepcopy                   | 224 us                                                              | 238 us: 1.06x slower                                           |
| pyflate                    | 328 ms                                                              | 349 ms: 1.06x slower                                           |
| async_tree_none_tg         | 252 ms                                                              | 268 ms: 1.07x slower                                           |
| 2to3                       | 170 ms                                                              | 181 ms: 1.07x slower                                           |
| go                         | 106 ms                                                              | 114 ms: 1.07x slower                                           |
| richards_super             | 34.9 ms                                                             | 37.3 ms: 1.07x slower                                          |
| xml_etree_process          | 38.6 ms                                                             | 41.3 ms: 1.07x slower                                          |
| async_tree_io              | 659 ms                                                              | 707 ms: 1.07x slower                                           |
| meteor_contest             | 72.9 ms                                                             | 78.5 ms: 1.08x slower                                          |
| richards                   | 31.0 ms                                                             | 33.4 ms: 1.08x slower                                          |
| pycparser                  | 667 ms                                                              | 719 ms: 1.08x slower                                           |
| sqlglot_optimize           | 34.3 ms                                                             | 37.1 ms: 1.08x slower                                          |
| python_startup_no_site     | 9.90 ms                                                             | 10.8 ms: 1.09x slower                                          |
| async_tree_memoization     | 306 ms                                                              | 332 ms: 1.09x slower                                           |
| regex_v8                   | 15.6 ms                                                             | 17.0 ms: 1.09x slower                                          |
| deepcopy_memo              | 24.6 us                                                             | 26.9 us: 1.09x slower                                          |
| tomli_loads                | 1.40 sec                                                            | 1.53 sec: 1.09x slower                                         |
| spectral_norm              | 74.6 ms                                                             | 82.1 ms: 1.10x slower                                          |
| scimark_lu                 | 71.4 ms                                                             | 78.6 ms: 1.10x slower                                          |
| nqueens                    | 59.6 ms                                                             | 65.7 ms: 1.10x slower                                          |
| pprint_safe_repr           | 492 ms                                                              | 542 ms: 1.10x slower                                           |
| pprint_pformat             | 1.00 sec                                                            | 1.11 sec: 1.11x slower                                         |
| regex_compile              | 75.8 ms                                                             | 83.9 ms: 1.11x slower                                          |
| pickle_pure_python         | 189 us                                                              | 209 us: 1.11x slower                                           |
| scimark_fft                | 198 ms                                                              | 222 ms: 1.12x slower                                           |
| chameleon                  | 4.51 ms                                                             | 5.15 ms: 1.14x slower                                          |
| fannkuch                   | 262 ms                                                              | 301 ms: 1.15x slower                                           |
| scimark_sor                | 93.8 ms                                                             | 108 ms: 1.15x slower                                           |
| nbody                      | 68.8 ms                                                             | 80.5 ms: 1.17x slower                                          |
| unpickle_pure_python       | 144 us                                                              | 171 us: 1.18x slower                                           |
| telco                      | 3.79 ms                                                             | 4.64 ms: 1.23x slower                                          |
| coverage                   | 37.8 ms                                                             | 48.5 ms: 1.28x slower                                          |
| hexiom                     | 4.24 ms                                                             | 5.82 ms: 1.37x slower                                          |
| mypy2                      | 256 ms                                                              | 541 ms: 2.12x slower                                           |
| Geometric mean             | (ref)                                                               | 1.05x slower                                                   |

Benchmark hidden because not significant (8): bench_mp_pool, async_tree_none, json_loads, gc_traversal, asyncio_websockets, pickle_list, python_startup, asyncio_tcp
Ignored benchmarks (5) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0.json: aiohttp, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.03x
- 95% likely to have a slowdown of 1.03x
- 99% likely to have a slowdown of 1.03x
