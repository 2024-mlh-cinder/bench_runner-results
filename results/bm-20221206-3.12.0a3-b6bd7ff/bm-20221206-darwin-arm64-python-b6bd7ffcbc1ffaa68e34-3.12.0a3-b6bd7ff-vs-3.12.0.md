
# Results vs. 3.12.0

- fork: python
- ref: b6bd7ffcbc1ffaa68e34
- machine: darwin-arm64
- commit hash: b6bd7ff
- commit date: 2022-12-06
- overall geometric mean: 1.04x slower
- HPT reliability: 98.17%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0 | bm-20221206-darwin-arm64-python-b6bd7ffcbc1ffaa68e34-3.12.0a3-b6bd7ff |
|----------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| 2to3           | 170 ms                                                              | 166 ms: 1.02x faster                                                  |
| chameleon      | 4.51 ms                                                             | 4.68 ms: 1.04x slower                                                 |
| docutils       | 1.53 sec                                                            | 1.48 sec: 1.03x faster                                                |
| Geometric mean | (ref)                                                               | 1.01x faster                                                          |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0 | bm-20221206-darwin-arm64-python-b6bd7ffcbc1ffaa68e34-3.12.0a3-b6bd7ff |
|----------------------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| async_tree_cpu_io_mixed    | 520 ms                                                              | 539 ms: 1.04x slower                                                  |
| async_tree_cpu_io_mixed_tg | 530 ms                                                              | 553 ms: 1.04x slower                                                  |
| async_tree_memoization     | 306 ms                                                              | 333 ms: 1.09x slower                                                  |
| async_tree_none_tg         | 252 ms                                                              | 276 ms: 1.10x slower                                                  |
| async_tree_io_tg           | 664 ms                                                              | 733 ms: 1.10x slower                                                  |
| async_tree_memoization_tg  | 316 ms                                                              | 350 ms: 1.11x slower                                                  |
| async_tree_none            | 258 ms                                                              | 295 ms: 1.14x slower                                                  |
| async_tree_io              | 659 ms                                                              | 758 ms: 1.15x slower                                                  |
| Geometric mean             | (ref)                                                               | 1.10x slower                                                          |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0 | bm-20221206-darwin-arm64-python-b6bd7ffcbc1ffaa68e34-3.12.0a3-b6bd7ff |
|----------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| pidigits       | 282 ms                                                              | 280 ms: 1.01x faster                                                  |
| float          | 58.0 ms                                                             | 57.6 ms: 1.01x faster                                                 |
| nbody          | 68.8 ms                                                             | 68.4 ms: 1.01x faster                                                 |
| Geometric mean | (ref)                                                               | 1.01x faster                                                          |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0 | bm-20221206-darwin-arm64-python-b6bd7ffcbc1ffaa68e34-3.12.0a3-b6bd7ff |
|----------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| regex_effbot   | 2.58 ms                                                             | 2.45 ms: 1.05x faster                                                 |
| regex_v8       | 15.6 ms                                                             | 15.1 ms: 1.03x faster                                                 |
| regex_dna      | 152 ms                                                              | 147 ms: 1.03x faster                                                  |
| regex_compile  | 75.8 ms                                                             | 78.1 ms: 1.03x slower                                                 |
| Geometric mean | (ref)                                                               | 1.02x faster                                                          |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0 | bm-20221206-darwin-arm64-python-b6bd7ffcbc1ffaa68e34-3.12.0a3-b6bd7ff |
|----------------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| xml_etree_generate   | 55.8 ms                                                             | 47.5 ms: 1.17x faster                                                 |
| unpickle_list        | 3.20 us                                                             | 2.75 us: 1.16x faster                                                 |
| xml_etree_parse      | 106 ms                                                              | 96.5 ms: 1.10x faster                                                 |
| json_loads           | 17.3 us                                                             | 15.8 us: 1.10x faster                                                 |
| unpickle             | 9.26 us                                                             | 8.45 us: 1.10x faster                                                 |
| pickle_list          | 2.89 us                                                             | 2.67 us: 1.08x faster                                                 |
| pickle_dict          | 18.1 us                                                             | 17.0 us: 1.06x faster                                                 |
| xml_etree_process    | 38.6 ms                                                             | 36.4 ms: 1.06x faster                                                 |
| xml_etree_iterparse  | 74.2 ms                                                             | 70.3 ms: 1.06x faster                                                 |
| json_dumps           | 6.48 ms                                                             | 6.15 ms: 1.05x faster                                                 |
| pickle               | 7.35 us                                                             | 7.13 us: 1.03x faster                                                 |
| tomli_loads          | 1.40 sec                                                            | 1.51 sec: 1.08x slower                                                |
| unpickle_pure_python | 144 us                                                              | 160 us: 1.11x slower                                                  |
| pickle_pure_python   | 189 us                                                              | 213 us: 1.13x slower                                                  |
| Geometric mean       | (ref)                                                               | 1.05x faster                                                          |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0 | bm-20221206-darwin-arm64-python-b6bd7ffcbc1ffaa68e34-3.12.0a3-b6bd7ff |
|------------------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| python_startup         | 12.1 ms                                                             | 11.4 ms: 1.06x faster                                                 |
| python_startup_no_site | 9.90 ms                                                             | 9.48 ms: 1.04x faster                                                 |
| Geometric mean         | (ref)                                                               | 1.05x faster                                                          |

Benchmarks with tag 'template':
===============================

| Benchmark      | bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0 | bm-20221206-darwin-arm64-python-b6bd7ffcbc1ffaa68e34-3.12.0a3-b6bd7ff |
|----------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| mako           | 7.52 ms                                                             | 7.45 ms: 1.01x faster                                                 |
| Geometric mean | (ref)                                                               | 1.00x faster                                                          |

Benchmark hidden because not significant (1): django_template

All benchmarks:
===============

| Benchmark                  | bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0 | bm-20221206-darwin-arm64-python-b6bd7ffcbc1ffaa68e34-3.12.0a3-b6bd7ff |
|----------------------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| async_generators           | 306 ms                                                              | 208 ms: 1.47x faster                                                  |
| telco                      | 3.79 ms                                                             | 3.09 ms: 1.22x faster                                                 |
| scimark_sparse_mat_mult    | 3.14 ms                                                             | 2.65 ms: 1.19x faster                                                 |
| xml_etree_generate         | 55.8 ms                                                             | 47.5 ms: 1.17x faster                                                 |
| unpickle_list              | 3.20 us                                                             | 2.75 us: 1.16x faster                                                 |
| sqlite_synth               | 1.60 us                                                             | 1.43 us: 1.12x faster                                                 |
| raytrace                   | 245 ms                                                              | 218 ms: 1.12x faster                                                  |
| xml_etree_parse            | 106 ms                                                              | 96.5 ms: 1.10x faster                                                 |
| json_loads                 | 17.3 us                                                             | 15.8 us: 1.10x faster                                                 |
| bench_mp_pool              | 46.8 ms                                                             | 42.6 ms: 1.10x faster                                                 |
| unpickle                   | 9.26 us                                                             | 8.45 us: 1.10x faster                                                 |
| json                       | 3.11 ms                                                             | 2.85 ms: 1.09x faster                                                 |
| pickle_list                | 2.89 us                                                             | 2.67 us: 1.08x faster                                                 |
| pickle_dict                | 18.1 us                                                             | 17.0 us: 1.06x faster                                                 |
| scimark_fft                | 198 ms                                                              | 186 ms: 1.06x faster                                                  |
| python_startup             | 12.1 ms                                                             | 11.4 ms: 1.06x faster                                                 |
| xml_etree_process          | 38.6 ms                                                             | 36.4 ms: 1.06x faster                                                 |
| xml_etree_iterparse        | 74.2 ms                                                             | 70.3 ms: 1.06x faster                                                 |
| regex_effbot               | 2.58 ms                                                             | 2.45 ms: 1.05x faster                                                 |
| json_dumps                 | 6.48 ms                                                             | 6.15 ms: 1.05x faster                                                 |
| pathlib                    | 24.4 ms                                                             | 23.3 ms: 1.05x faster                                                 |
| python_startup_no_site     | 9.90 ms                                                             | 9.48 ms: 1.04x faster                                                 |
| sqlglot_optimize           | 34.3 ms                                                             | 33.1 ms: 1.04x faster                                                 |
| bench_thread_pool          | 503 us                                                              | 485 us: 1.04x faster                                                  |
| sqlglot_normalize          | 186 ms                                                              | 180 ms: 1.03x faster                                                  |
| docutils                   | 1.53 sec                                                            | 1.48 sec: 1.03x faster                                                |
| regex_v8                   | 15.6 ms                                                             | 15.1 ms: 1.03x faster                                                 |
| regex_dna                  | 152 ms                                                              | 147 ms: 1.03x faster                                                  |
| pickle                     | 7.35 us                                                             | 7.13 us: 1.03x faster                                                 |
| create_gc_cycles           | 702 us                                                              | 682 us: 1.03x faster                                                  |
| 2to3                       | 170 ms                                                              | 166 ms: 1.02x faster                                                  |
| dulwich_log                | 29.8 ms                                                             | 29.4 ms: 1.02x faster                                                 |
| sympy_expand               | 250 ms                                                              | 246 ms: 1.01x faster                                                  |
| mako                       | 7.52 ms                                                             | 7.45 ms: 1.01x faster                                                 |
| gc_traversal               | 2.40 ms                                                             | 2.38 ms: 1.01x faster                                                 |
| pidigits                   | 282 ms                                                              | 280 ms: 1.01x faster                                                  |
| float                      | 58.0 ms                                                             | 57.6 ms: 1.01x faster                                                 |
| crypto_pyaes               | 51.8 ms                                                             | 51.5 ms: 1.01x faster                                                 |
| nbody                      | 68.8 ms                                                             | 68.4 ms: 1.01x faster                                                 |
| nqueens                    | 59.6 ms                                                             | 60.0 ms: 1.01x slower                                                 |
| sympy_str                  | 151 ms                                                              | 153 ms: 1.01x slower                                                  |
| fannkuch                   | 262 ms                                                              | 267 ms: 1.02x slower                                                  |
| pycparser                  | 667 ms                                                              | 686 ms: 1.03x slower                                                  |
| deepcopy_reduce            | 2.03 us                                                             | 2.09 us: 1.03x slower                                                 |
| logging_simple             | 3.70 us                                                             | 3.81 us: 1.03x slower                                                 |
| regex_compile              | 75.8 ms                                                             | 78.1 ms: 1.03x slower                                                 |
| logging_format             | 3.98 us                                                             | 4.10 us: 1.03x slower                                                 |
| pprint_safe_repr           | 492 ms                                                              | 507 ms: 1.03x slower                                                  |
| pprint_pformat             | 1.00 sec                                                            | 1.03 sec: 1.03x slower                                                |
| pyflate                    | 328 ms                                                              | 340 ms: 1.03x slower                                                  |
| async_tree_cpu_io_mixed    | 520 ms                                                              | 539 ms: 1.04x slower                                                  |
| chameleon                  | 4.51 ms                                                             | 4.68 ms: 1.04x slower                                                 |
| meteor_contest             | 72.9 ms                                                             | 75.9 ms: 1.04x slower                                                 |
| async_tree_cpu_io_mixed_tg | 530 ms                                                              | 553 ms: 1.04x slower                                                  |
| sympy_integrate            | 11.3 ms                                                             | 11.9 ms: 1.05x slower                                                 |
| mdp                        | 1.67 sec                                                            | 1.77 sec: 1.06x slower                                                |
| spectral_norm              | 74.6 ms                                                             | 79.6 ms: 1.07x slower                                                 |
| deepcopy                   | 224 us                                                              | 240 us: 1.07x slower                                                  |
| scimark_monte_carlo        | 50.0 ms                                                             | 53.6 ms: 1.07x slower                                                 |
| sympy_sum                  | 79.1 ms                                                             | 85.0 ms: 1.07x slower                                                 |
| tomli_loads                | 1.40 sec                                                            | 1.51 sec: 1.08x slower                                                |
| async_tree_memoization     | 306 ms                                                              | 333 ms: 1.09x slower                                                  |
| deltablue                  | 2.59 ms                                                             | 2.83 ms: 1.09x slower                                                 |
| async_tree_none_tg         | 252 ms                                                              | 276 ms: 1.10x slower                                                  |
| comprehensions             | 15.7 us                                                             | 17.3 us: 1.10x slower                                                 |
| async_tree_io_tg           | 664 ms                                                              | 733 ms: 1.10x slower                                                  |
| async_tree_memoization_tg  | 316 ms                                                              | 350 ms: 1.11x slower                                                  |
| go                         | 106 ms                                                              | 118 ms: 1.11x slower                                                  |
| unpickle_pure_python       | 144 us                                                              | 160 us: 1.11x slower                                                  |
| sqlglot_transpile          | 1.07 ms                                                             | 1.19 ms: 1.11x slower                                                 |
| scimark_sor                | 93.8 ms                                                             | 105 ms: 1.11x slower                                                  |
| richards                   | 31.0 ms                                                             | 34.7 ms: 1.12x slower                                                 |
| coroutines                 | 18.2 ms                                                             | 20.5 ms: 1.13x slower                                                 |
| unpack_sequence            | 28.7 ns                                                             | 32.3 ns: 1.13x slower                                                 |
| pickle_pure_python         | 189 us                                                              | 213 us: 1.13x slower                                                  |
| sqlglot_parse              | 895 us                                                              | 1.02 ms: 1.14x slower                                                 |
| async_tree_none            | 258 ms                                                              | 295 ms: 1.14x slower                                                  |
| scimark_lu                 | 71.4 ms                                                             | 81.7 ms: 1.14x slower                                                 |
| async_tree_io              | 659 ms                                                              | 758 ms: 1.15x slower                                                  |
| chaos                      | 44.6 ms                                                             | 51.4 ms: 1.15x slower                                                 |
| asyncio_tcp_ssl            | 1.26 sec                                                            | 1.46 sec: 1.15x slower                                                |
| deepcopy_memo              | 24.6 us                                                             | 28.7 us: 1.17x slower                                                 |
| logging_silent             | 67.8 ns                                                             | 79.3 ns: 1.17x slower                                                 |
| hexiom                     | 4.24 ms                                                             | 4.97 ms: 1.17x slower                                                 |
| richards_super             | 34.9 ms                                                             | 41.5 ms: 1.19x slower                                                 |
| generators                 | 28.6 ms                                                             | 37.2 ms: 1.30x slower                                                 |
| dask                       | 224 ms                                                              | 331 ms: 1.48x slower                                                  |
| asyncio_tcp                | 419 ms                                                              | 661 ms: 1.58x slower                                                  |
| typing_runtime_protocols   | 90.6 us                                                             | 329 us: 3.63x slower                                                  |
| Geometric mean             | (ref)                                                               | 1.04x slower                                                          |

Benchmark hidden because not significant (2): asyncio_websockets, django_template
Ignored benchmarks (7) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0.json: aiohttp, coverage, gunicorn, mypy2, sqlalchemy_declarative, sqlalchemy_imperative, tornado_http
Ignored benchmarks (4) of results/bm-20221206-3.12.0a3-b6bd7ff/bm-20221206-darwin-arm64-python-b6bd7ffcbc1ffaa68e34-3.12.0a3-b6bd7ff.json: genshi_text, genshi_xml, html5lib, thrift


# HPT report

- Reliability score: 98.17% likely to be slow
- 90% likely to have a slowdown of 1.01x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
