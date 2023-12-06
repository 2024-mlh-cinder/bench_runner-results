
# Results vs. 3.12.0

- fork: python
- ref: 4ae1a0ecaffe4320fe97
- machine: darwin-arm64
- commit hash: 4ae1a0e
- commit date: 2022-10-25
- overall geometric mean: 1.01x faster
- HPT reliability: 81.68%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0 | bm-20221025-darwin-arm64-python-4ae1a0ecaffe4320fe97-3.12.0a1-4ae1a0e |
|----------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| 2to3           | 170 ms                                                              | 159 ms: 1.07x faster                                                  |
| chameleon      | 4.51 ms                                                             | 4.35 ms: 1.04x faster                                                 |
| docutils       | 1.53 sec                                                            | 1.45 sec: 1.05x faster                                                |
| Geometric mean | (ref)                                                               | 1.04x faster                                                          |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0 | bm-20221025-darwin-arm64-python-4ae1a0ecaffe4320fe97-3.12.0a1-4ae1a0e |
|----------------------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| async_tree_cpu_io_mixed_tg | 530 ms                                                              | 537 ms: 1.01x slower                                                  |
| async_tree_none_tg         | 252 ms                                                              | 262 ms: 1.04x slower                                                  |
| async_tree_io_tg           | 664 ms                                                              | 697 ms: 1.05x slower                                                  |
| async_tree_memoization     | 306 ms                                                              | 322 ms: 1.05x slower                                                  |
| async_tree_memoization_tg  | 316 ms                                                              | 336 ms: 1.06x slower                                                  |
| async_tree_none            | 258 ms                                                              | 281 ms: 1.09x slower                                                  |
| async_tree_io              | 659 ms                                                              | 723 ms: 1.10x slower                                                  |
| Geometric mean             | (ref)                                                               | 1.05x slower                                                          |

Benchmark hidden because not significant (1): async_tree_cpu_io_mixed

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0 | bm-20221025-darwin-arm64-python-4ae1a0ecaffe4320fe97-3.12.0a1-4ae1a0e |
|----------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| float          | 58.0 ms                                                             | 55.9 ms: 1.04x faster                                                 |
| pidigits       | 282 ms                                                              | 280 ms: 1.01x faster                                                  |
| nbody          | 68.8 ms                                                             | 69.0 ms: 1.00x slower                                                 |
| Geometric mean | (ref)                                                               | 1.01x faster                                                          |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0 | bm-20221025-darwin-arm64-python-4ae1a0ecaffe4320fe97-3.12.0a1-4ae1a0e |
|----------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| regex_effbot   | 2.58 ms                                                             | 2.44 ms: 1.06x faster                                                 |
| regex_v8       | 15.6 ms                                                             | 15.0 ms: 1.04x faster                                                 |
| regex_compile  | 75.8 ms                                                             | 73.0 ms: 1.04x faster                                                 |
| regex_dna      | 152 ms                                                              | 148 ms: 1.02x faster                                                  |
| Geometric mean | (ref)                                                               | 1.04x faster                                                          |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0 | bm-20221025-darwin-arm64-python-4ae1a0ecaffe4320fe97-3.12.0a1-4ae1a0e |
|----------------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| unpickle_list        | 3.20 us                                                             | 2.52 us: 1.27x faster                                                 |
| xml_etree_generate   | 55.8 ms                                                             | 46.0 ms: 1.21x faster                                                 |
| xml_etree_parse      | 106 ms                                                              | 90.9 ms: 1.17x faster                                                 |
| xml_etree_process    | 38.6 ms                                                             | 33.8 ms: 1.14x faster                                                 |
| unpickle             | 9.26 us                                                             | 8.27 us: 1.12x faster                                                 |
| json_loads           | 17.3 us                                                             | 15.6 us: 1.11x faster                                                 |
| xml_etree_iterparse  | 74.2 ms                                                             | 67.9 ms: 1.09x faster                                                 |
| json_dumps           | 6.48 ms                                                             | 6.04 ms: 1.07x faster                                                 |
| pickle_list          | 2.89 us                                                             | 2.70 us: 1.07x faster                                                 |
| pickle_dict          | 18.1 us                                                             | 16.9 us: 1.07x faster                                                 |
| pickle               | 7.35 us                                                             | 7.13 us: 1.03x faster                                                 |
| tomli_loads          | 1.40 sec                                                            | 1.42 sec: 1.01x slower                                                |
| unpickle_pure_python | 144 us                                                              | 154 us: 1.07x slower                                                  |
| pickle_pure_python   | 189 us                                                              | 201 us: 1.07x slower                                                  |
| Geometric mean       | (ref)                                                               | 1.08x faster                                                          |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0 | bm-20221025-darwin-arm64-python-4ae1a0ecaffe4320fe97-3.12.0a1-4ae1a0e |
|------------------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| python_startup         | 12.1 ms                                                             | 11.3 ms: 1.07x faster                                                 |
| python_startup_no_site | 9.90 ms                                                             | 9.36 ms: 1.06x faster                                                 |
| Geometric mean         | (ref)                                                               | 1.07x faster                                                          |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0 | bm-20221025-darwin-arm64-python-4ae1a0ecaffe4320fe97-3.12.0a1-4ae1a0e |
|-----------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| django_template | 21.8 ms                                                             | 20.0 ms: 1.09x faster                                                 |
| mako            | 7.52 ms                                                             | 7.66 ms: 1.02x slower                                                 |
| Geometric mean  | (ref)                                                               | 1.04x faster                                                          |

All benchmarks:
===============

| Benchmark                  | bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0 | bm-20221025-darwin-arm64-python-4ae1a0ecaffe4320fe97-3.12.0a1-4ae1a0e |
|----------------------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| async_generators           | 306 ms                                                              | 195 ms: 1.57x faster                                                  |
| unpickle_list              | 3.20 us                                                             | 2.52 us: 1.27x faster                                                 |
| xml_etree_generate         | 55.8 ms                                                             | 46.0 ms: 1.21x faster                                                 |
| scimark_sparse_mat_mult    | 3.14 ms                                                             | 2.61 ms: 1.20x faster                                                 |
| raytrace                   | 245 ms                                                              | 207 ms: 1.18x faster                                                  |
| telco                      | 3.79 ms                                                             | 3.20 ms: 1.18x faster                                                 |
| xml_etree_parse            | 106 ms                                                              | 90.9 ms: 1.17x faster                                                 |
| xml_etree_process          | 38.6 ms                                                             | 33.8 ms: 1.14x faster                                                 |
| sqlite_synth               | 1.60 us                                                             | 1.42 us: 1.13x faster                                                 |
| sqlglot_optimize           | 34.3 ms                                                             | 30.5 ms: 1.12x faster                                                 |
| bench_mp_pool              | 46.8 ms                                                             | 41.7 ms: 1.12x faster                                                 |
| unpickle                   | 9.26 us                                                             | 8.27 us: 1.12x faster                                                 |
| sqlglot_normalize          | 186 ms                                                              | 167 ms: 1.12x faster                                                  |
| json_loads                 | 17.3 us                                                             | 15.6 us: 1.11x faster                                                 |
| json                       | 3.11 ms                                                             | 2.82 ms: 1.11x faster                                                 |
| bench_thread_pool          | 503 us                                                              | 457 us: 1.10x faster                                                  |
| django_template            | 21.8 ms                                                             | 20.0 ms: 1.09x faster                                                 |
| xml_etree_iterparse        | 74.2 ms                                                             | 67.9 ms: 1.09x faster                                                 |
| logging_silent             | 67.8 ns                                                             | 63.1 ns: 1.07x faster                                                 |
| nqueens                    | 59.6 ms                                                             | 55.6 ms: 1.07x faster                                                 |
| python_startup             | 12.1 ms                                                             | 11.3 ms: 1.07x faster                                                 |
| spectral_norm              | 74.6 ms                                                             | 69.5 ms: 1.07x faster                                                 |
| json_dumps                 | 6.48 ms                                                             | 6.04 ms: 1.07x faster                                                 |
| scimark_fft                | 198 ms                                                              | 185 ms: 1.07x faster                                                  |
| 2to3                       | 170 ms                                                              | 159 ms: 1.07x faster                                                  |
| crypto_pyaes               | 51.8 ms                                                             | 48.4 ms: 1.07x faster                                                 |
| pickle_list                | 2.89 us                                                             | 2.70 us: 1.07x faster                                                 |
| pickle_dict                | 18.1 us                                                             | 16.9 us: 1.07x faster                                                 |
| sympy_expand               | 250 ms                                                              | 235 ms: 1.06x faster                                                  |
| deepcopy_reduce            | 2.03 us                                                             | 1.92 us: 1.06x faster                                                 |
| scimark_lu                 | 71.4 ms                                                             | 67.4 ms: 1.06x faster                                                 |
| comprehensions             | 15.7 us                                                             | 14.8 us: 1.06x faster                                                 |
| regex_effbot               | 2.58 ms                                                             | 2.44 ms: 1.06x faster                                                 |
| python_startup_no_site     | 9.90 ms                                                             | 9.36 ms: 1.06x faster                                                 |
| docutils                   | 1.53 sec                                                            | 1.45 sec: 1.05x faster                                                |
| pathlib                    | 24.4 ms                                                             | 23.1 ms: 1.05x faster                                                 |
| sympy_str                  | 151 ms                                                              | 144 ms: 1.05x faster                                                  |
| regex_v8                   | 15.6 ms                                                             | 15.0 ms: 1.04x faster                                                 |
| float                      | 58.0 ms                                                             | 55.9 ms: 1.04x faster                                                 |
| regex_compile              | 75.8 ms                                                             | 73.0 ms: 1.04x faster                                                 |
| chameleon                  | 4.51 ms                                                             | 4.35 ms: 1.04x faster                                                 |
| dulwich_log                | 29.8 ms                                                             | 28.8 ms: 1.04x faster                                                 |
| logging_simple             | 3.70 us                                                             | 3.58 us: 1.03x faster                                                 |
| logging_format             | 3.98 us                                                             | 3.85 us: 1.03x faster                                                 |
| pickle                     | 7.35 us                                                             | 7.13 us: 1.03x faster                                                 |
| regex_dna                  | 152 ms                                                              | 148 ms: 1.02x faster                                                  |
| sympy_integrate            | 11.3 ms                                                             | 11.1 ms: 1.02x faster                                                 |
| create_gc_cycles           | 702 us                                                              | 687 us: 1.02x faster                                                  |
| pprint_safe_repr           | 492 ms                                                              | 484 ms: 1.02x faster                                                  |
| pprint_pformat             | 1.00 sec                                                            | 990 ms: 1.01x faster                                                  |
| coroutines                 | 18.2 ms                                                             | 18.0 ms: 1.01x faster                                                 |
| fannkuch                   | 262 ms                                                              | 260 ms: 1.01x faster                                                  |
| pidigits                   | 282 ms                                                              | 280 ms: 1.01x faster                                                  |
| gc_traversal               | 2.40 ms                                                             | 2.40 ms: 1.00x slower                                                 |
| nbody                      | 68.8 ms                                                             | 69.0 ms: 1.00x slower                                                 |
| pyflate                    | 328 ms                                                              | 331 ms: 1.01x slower                                                  |
| tomli_loads                | 1.40 sec                                                            | 1.42 sec: 1.01x slower                                                |
| async_tree_cpu_io_mixed_tg | 530 ms                                                              | 537 ms: 1.01x slower                                                  |
| deepcopy                   | 224 us                                                              | 227 us: 1.01x slower                                                  |
| mako                       | 7.52 ms                                                             | 7.66 ms: 1.02x slower                                                 |
| mdp                        | 1.67 sec                                                            | 1.71 sec: 1.02x slower                                                |
| sqlglot_transpile          | 1.07 ms                                                             | 1.10 ms: 1.03x slower                                                 |
| sympy_sum                  | 79.1 ms                                                             | 81.5 ms: 1.03x slower                                                 |
| async_tree_none_tg         | 252 ms                                                              | 262 ms: 1.04x slower                                                  |
| meteor_contest             | 72.9 ms                                                             | 76.4 ms: 1.05x slower                                                 |
| richards                   | 31.0 ms                                                             | 32.5 ms: 1.05x slower                                                 |
| sqlglot_parse              | 895 us                                                              | 940 us: 1.05x slower                                                  |
| async_tree_io_tg           | 664 ms                                                              | 697 ms: 1.05x slower                                                  |
| async_tree_memoization     | 306 ms                                                              | 322 ms: 1.05x slower                                                  |
| generators                 | 28.6 ms                                                             | 30.2 ms: 1.06x slower                                                 |
| scimark_monte_carlo        | 50.0 ms                                                             | 52.9 ms: 1.06x slower                                                 |
| deltablue                  | 2.59 ms                                                             | 2.75 ms: 1.06x slower                                                 |
| async_tree_memoization_tg  | 316 ms                                                              | 336 ms: 1.06x slower                                                  |
| unpickle_pure_python       | 144 us                                                              | 154 us: 1.07x slower                                                  |
| pickle_pure_python         | 189 us                                                              | 201 us: 1.07x slower                                                  |
| scimark_sor                | 93.8 ms                                                             | 100 ms: 1.07x slower                                                  |
| go                         | 106 ms                                                              | 114 ms: 1.08x slower                                                  |
| async_tree_none            | 258 ms                                                              | 281 ms: 1.09x slower                                                  |
| chaos                      | 44.6 ms                                                             | 48.6 ms: 1.09x slower                                                 |
| async_tree_io              | 659 ms                                                              | 723 ms: 1.10x slower                                                  |
| hexiom                     | 4.24 ms                                                             | 4.68 ms: 1.10x slower                                                 |
| richards_super             | 34.9 ms                                                             | 38.6 ms: 1.11x slower                                                 |
| deepcopy_memo              | 24.6 us                                                             | 27.3 us: 1.11x slower                                                 |
| asyncio_tcp_ssl            | 1.26 sec                                                            | 1.43 sec: 1.13x slower                                                |
| unpack_sequence            | 28.7 ns                                                             | 34.1 ns: 1.19x slower                                                 |
| dask                       | 224 ms                                                              | 322 ms: 1.44x slower                                                  |
| asyncio_tcp                | 419 ms                                                              | 659 ms: 1.57x slower                                                  |
| typing_runtime_protocols   | 90.6 us                                                             | 321 us: 3.55x slower                                                  |
| Geometric mean             | (ref)                                                               | 1.01x faster                                                          |

Benchmark hidden because not significant (4): tornado_http, asyncio_websockets, pycparser, async_tree_cpu_io_mixed
Ignored benchmarks (6) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0.json: aiohttp, coverage, gunicorn, mypy2, sqlalchemy_declarative, sqlalchemy_imperative
Ignored benchmarks (5) of results/bm-20221025-3.12.0a1-4ae1a0e/bm-20221025-darwin-arm64-python-4ae1a0ecaffe4320fe97-3.12.0a1-4ae1a0e.json: genshi_text, genshi_xml, html5lib, pylint, thrift


# HPT report

- Reliability score: 81.68% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
