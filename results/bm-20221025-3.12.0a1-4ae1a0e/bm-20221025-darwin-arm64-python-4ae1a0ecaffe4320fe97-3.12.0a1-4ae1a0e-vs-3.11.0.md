
# Results vs. 3.11.0

- fork: python
- ref: 4ae1a0ecaffe4320fe97
- machine: darwin-arm64
- commit hash: 4ae1a0e
- commit date: 2022-10-25
- overall geometric mean: 1.01x slower
- HPT reliability: 97.78%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-darwin-arm64-python-deaf509e8fc6e0363bd6-3.11.0-deaf509 | bm-20221025-darwin-arm64-python-4ae1a0ecaffe4320fe97-3.12.0a1-4ae1a0e |
|----------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| 2to3           | 154 ms                                                              | 159 ms: 1.03x slower                                                  |
| chameleon      | 4.21 ms                                                             | 4.35 ms: 1.03x slower                                                 |
| docutils       | 1.43 sec                                                            | 1.45 sec: 1.02x slower                                                |
| html5lib       | 33.3 ms                                                             | 33.9 ms: 1.02x slower                                                 |
| Geometric mean | (ref)                                                               | 1.02x slower                                                          |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20221024-darwin-arm64-python-deaf509e8fc6e0363bd6-3.11.0-deaf509 | bm-20221025-darwin-arm64-python-4ae1a0ecaffe4320fe97-3.12.0a1-4ae1a0e |
|----------------------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| async_tree_memoization     | 353 ms                                                              | 322 ms: 1.10x faster                                                  |
| async_tree_none_tg         | 277 ms                                                              | 262 ms: 1.05x faster                                                  |
| async_tree_memoization_tg  | 351 ms                                                              | 336 ms: 1.04x faster                                                  |
| async_tree_io_tg           | 723 ms                                                              | 697 ms: 1.04x faster                                                  |
| async_tree_cpu_io_mixed_tg | 548 ms                                                              | 537 ms: 1.02x faster                                                  |
| async_tree_cpu_io_mixed    | 516 ms                                                              | 523 ms: 1.01x slower                                                  |
| async_tree_none            | 277 ms                                                              | 281 ms: 1.01x slower                                                  |
| async_tree_io              | 691 ms                                                              | 723 ms: 1.05x slower                                                  |
| Geometric mean             | (ref)                                                               | 1.02x faster                                                          |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-darwin-arm64-python-deaf509e8fc6e0363bd6-3.11.0-deaf509 | bm-20221025-darwin-arm64-python-4ae1a0ecaffe4320fe97-3.12.0a1-4ae1a0e |
|----------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| pidigits       | 280 ms                                                              | 280 ms: 1.00x slower                                                  |
| nbody          | 68.5 ms                                                             | 69.0 ms: 1.01x slower                                                 |
| float          | 55.1 ms                                                             | 55.9 ms: 1.01x slower                                                 |
| Geometric mean | (ref)                                                               | 1.01x slower                                                          |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-darwin-arm64-python-deaf509e8fc6e0363bd6-3.11.0-deaf509 | bm-20221025-darwin-arm64-python-4ae1a0ecaffe4320fe97-3.12.0a1-4ae1a0e |
|----------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| regex_v8       | 15.4 ms                                                             | 15.0 ms: 1.03x faster                                                 |
| regex_dna      | 149 ms                                                              | 148 ms: 1.01x faster                                                  |
| regex_compile  | 73.5 ms                                                             | 73.0 ms: 1.01x faster                                                 |
| regex_effbot   | 2.45 ms                                                             | 2.44 ms: 1.01x faster                                                 |
| Geometric mean | (ref)                                                               | 1.01x faster                                                          |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-darwin-arm64-python-deaf509e8fc6e0363bd6-3.11.0-deaf509 | bm-20221025-darwin-arm64-python-4ae1a0ecaffe4320fe97-3.12.0a1-4ae1a0e |
|----------------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| json_dumps           | 7.58 ms                                                             | 6.04 ms: 1.25x faster                                                 |
| unpickle_list        | 2.76 us                                                             | 2.52 us: 1.09x faster                                                 |
| xml_etree_parse      | 97.6 ms                                                             | 90.9 ms: 1.07x faster                                                 |
| unpickle_pure_python | 162 us                                                              | 154 us: 1.05x faster                                                  |
| pickle_pure_python   | 210 us                                                              | 201 us: 1.04x faster                                                  |
| xml_etree_generate   | 47.1 ms                                                             | 46.0 ms: 1.03x faster                                                 |
| unpickle             | 8.35 us                                                             | 8.27 us: 1.01x faster                                                 |
| xml_etree_process    | 34.1 ms                                                             | 33.8 ms: 1.01x faster                                                 |
| pickle               | 7.17 us                                                             | 7.13 us: 1.01x faster                                                 |
| xml_etree_iterparse  | 67.5 ms                                                             | 67.9 ms: 1.01x slower                                                 |
| json_loads           | 15.5 us                                                             | 15.6 us: 1.01x slower                                                 |
| pickle_list          | 2.68 us                                                             | 2.70 us: 1.01x slower                                                 |
| tomli_loads          | 1.32 sec                                                            | 1.42 sec: 1.07x slower                                                |
| Geometric mean       | (ref)                                                               | 1.03x faster                                                          |

Benchmark hidden because not significant (1): pickle_dict

Benchmarks with tag 'startup':
==============================

| Benchmark      | bm-20221024-darwin-arm64-python-deaf509e8fc6e0363bd6-3.11.0-deaf509 | bm-20221025-darwin-arm64-python-4ae1a0ecaffe4320fe97-3.12.0a1-4ae1a0e |
|----------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| python_startup | 11.5 ms                                                             | 11.3 ms: 1.02x faster                                                 |
| Geometric mean | (ref)                                                               | 1.01x faster                                                          |

Benchmark hidden because not significant (1): python_startup_no_site

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20221024-darwin-arm64-python-deaf509e8fc6e0363bd6-3.11.0-deaf509 | bm-20221025-darwin-arm64-python-4ae1a0ecaffe4320fe97-3.12.0a1-4ae1a0e |
|-----------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| mako            | 8.25 ms                                                             | 7.66 ms: 1.08x faster                                                 |
| genshi_xml      | 28.3 ms                                                             | 28.4 ms: 1.00x slower                                                 |
| genshi_text     | 14.5 ms                                                             | 14.6 ms: 1.01x slower                                                 |
| django_template | 19.6 ms                                                             | 20.0 ms: 1.02x slower                                                 |
| Geometric mean  | (ref)                                                               | 1.01x faster                                                          |

All benchmarks:
===============

| Benchmark                  | bm-20221024-darwin-arm64-python-deaf509e8fc6e0363bd6-3.11.0-deaf509 | bm-20221025-darwin-arm64-python-4ae1a0ecaffe4320fe97-3.12.0a1-4ae1a0e |
|----------------------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| json_dumps                 | 7.58 ms                                                             | 6.04 ms: 1.25x faster                                                 |
| scimark_sparse_mat_mult    | 3.00 ms                                                             | 2.61 ms: 1.15x faster                                                 |
| async_tree_memoization     | 353 ms                                                              | 322 ms: 1.10x faster                                                  |
| unpickle_list              | 2.76 us                                                             | 2.52 us: 1.09x faster                                                 |
| mdp                        | 1.84 sec                                                            | 1.71 sec: 1.08x faster                                                |
| mako                       | 8.25 ms                                                             | 7.66 ms: 1.08x faster                                                 |
| xml_etree_parse            | 97.6 ms                                                             | 90.9 ms: 1.07x faster                                                 |
| async_tree_none_tg         | 277 ms                                                              | 262 ms: 1.05x faster                                                  |
| unpickle_pure_python       | 162 us                                                              | 154 us: 1.05x faster                                                  |
| deepcopy_memo              | 28.7 us                                                             | 27.3 us: 1.05x faster                                                 |
| gc_traversal               | 2.53 ms                                                             | 2.40 ms: 1.05x faster                                                 |
| async_tree_memoization_tg  | 351 ms                                                              | 336 ms: 1.04x faster                                                  |
| pickle_pure_python         | 210 us                                                              | 201 us: 1.04x faster                                                  |
| create_gc_cycles           | 714 us                                                              | 687 us: 1.04x faster                                                  |
| async_tree_io_tg           | 723 ms                                                              | 697 ms: 1.04x faster                                                  |
| xml_etree_generate         | 47.1 ms                                                             | 46.0 ms: 1.03x faster                                                 |
| regex_v8                   | 15.4 ms                                                             | 15.0 ms: 1.03x faster                                                 |
| deepcopy_reduce            | 1.96 us                                                             | 1.92 us: 1.02x faster                                                 |
| bench_thread_pool          | 467 us                                                              | 457 us: 1.02x faster                                                  |
| deepcopy                   | 232 us                                                              | 227 us: 1.02x faster                                                  |
| async_tree_cpu_io_mixed_tg | 548 ms                                                              | 537 ms: 1.02x faster                                                  |
| python_startup             | 11.5 ms                                                             | 11.3 ms: 1.02x faster                                                 |
| logging_silent             | 64.3 ns                                                             | 63.1 ns: 1.02x faster                                                 |
| dulwich_log                | 29.2 ms                                                             | 28.8 ms: 1.01x faster                                                 |
| thrift                     | 420 us                                                              | 415 us: 1.01x faster                                                  |
| sympy_integrate            | 11.2 ms                                                             | 11.1 ms: 1.01x faster                                                 |
| unpickle                   | 8.35 us                                                             | 8.27 us: 1.01x faster                                                 |
| regex_dna                  | 149 ms                                                              | 148 ms: 1.01x faster                                                  |
| scimark_lu                 | 67.9 ms                                                             | 67.4 ms: 1.01x faster                                                 |
| xml_etree_process          | 34.1 ms                                                             | 33.8 ms: 1.01x faster                                                 |
| scimark_fft                | 186 ms                                                              | 185 ms: 1.01x faster                                                  |
| asyncio_tcp                | 664 ms                                                              | 659 ms: 1.01x faster                                                  |
| regex_compile              | 73.5 ms                                                             | 73.0 ms: 1.01x faster                                                 |
| regex_effbot               | 2.45 ms                                                             | 2.44 ms: 1.01x faster                                                 |
| sympy_expand               | 236 ms                                                              | 235 ms: 1.01x faster                                                  |
| pickle                     | 7.17 us                                                             | 7.13 us: 1.01x faster                                                 |
| pidigits                   | 280 ms                                                              | 280 ms: 1.00x slower                                                  |
| spectral_norm              | 69.4 ms                                                             | 69.5 ms: 1.00x slower                                                 |
| genshi_xml                 | 28.3 ms                                                             | 28.4 ms: 1.00x slower                                                 |
| pprint_pformat             | 986 ms                                                              | 990 ms: 1.00x slower                                                  |
| asyncio_tcp_ssl            | 1.43 sec                                                            | 1.43 sec: 1.00x slower                                                |
| raytrace                   | 205 ms                                                              | 207 ms: 1.01x slower                                                  |
| xml_etree_iterparse        | 67.5 ms                                                             | 67.9 ms: 1.01x slower                                                 |
| json_loads                 | 15.5 us                                                             | 15.6 us: 1.01x slower                                                 |
| pprint_safe_repr           | 480 ms                                                              | 484 ms: 1.01x slower                                                  |
| chaos                      | 48.2 ms                                                             | 48.6 ms: 1.01x slower                                                 |
| genshi_text                | 14.5 ms                                                             | 14.6 ms: 1.01x slower                                                 |
| nbody                      | 68.5 ms                                                             | 69.0 ms: 1.01x slower                                                 |
| sympy_sum                  | 80.8 ms                                                             | 81.5 ms: 1.01x slower                                                 |
| crypto_pyaes               | 47.9 ms                                                             | 48.4 ms: 1.01x slower                                                 |
| pickle_list                | 2.68 us                                                             | 2.70 us: 1.01x slower                                                 |
| telco                      | 3.17 ms                                                             | 3.20 ms: 1.01x slower                                                 |
| async_tree_cpu_io_mixed    | 516 ms                                                              | 523 ms: 1.01x slower                                                  |
| pycparser                  | 658 ms                                                              | 668 ms: 1.01x slower                                                  |
| float                      | 55.1 ms                                                             | 55.9 ms: 1.01x slower                                                 |
| meteor_contest             | 75.3 ms                                                             | 76.4 ms: 1.01x slower                                                 |
| async_tree_none            | 277 ms                                                              | 281 ms: 1.01x slower                                                  |
| comprehensions             | 14.6 us                                                             | 14.8 us: 1.01x slower                                                 |
| docutils                   | 1.43 sec                                                            | 1.45 sec: 1.02x slower                                                |
| django_template            | 19.6 ms                                                             | 20.0 ms: 1.02x slower                                                 |
| json                       | 2.77 ms                                                             | 2.82 ms: 1.02x slower                                                 |
| html5lib                   | 33.3 ms                                                             | 33.9 ms: 1.02x slower                                                 |
| async_generators           | 191 ms                                                              | 195 ms: 1.02x slower                                                  |
| nqueens                    | 54.3 ms                                                             | 55.6 ms: 1.02x slower                                                 |
| deltablue                  | 2.69 ms                                                             | 2.75 ms: 1.02x slower                                                 |
| hexiom                     | 4.55 ms                                                             | 4.68 ms: 1.03x slower                                                 |
| sqlglot_optimize           | 29.6 ms                                                             | 30.5 ms: 1.03x slower                                                 |
| 2to3                       | 154 ms                                                              | 159 ms: 1.03x slower                                                  |
| logging_format             | 3.73 us                                                             | 3.85 us: 1.03x slower                                                 |
| chameleon                  | 4.21 ms                                                             | 4.35 ms: 1.03x slower                                                 |
| logging_simple             | 3.45 us                                                             | 3.58 us: 1.04x slower                                                 |
| generators                 | 29.0 ms                                                             | 30.2 ms: 1.04x slower                                                 |
| sqlglot_normalize          | 160 ms                                                              | 167 ms: 1.04x slower                                                  |
| sqlite_synth               | 1.36 us                                                             | 1.42 us: 1.04x slower                                                 |
| async_tree_io              | 691 ms                                                              | 723 ms: 1.05x slower                                                  |
| richards_super             | 36.7 ms                                                             | 38.6 ms: 1.05x slower                                                 |
| fannkuch                   | 247 ms                                                              | 260 ms: 1.05x slower                                                  |
| unpack_sequence            | 32.3 ns                                                             | 34.1 ns: 1.06x slower                                                 |
| richards                   | 30.7 ms                                                             | 32.5 ms: 1.06x slower                                                 |
| sqlglot_transpile          | 1.04 ms                                                             | 1.10 ms: 1.06x slower                                                 |
| tomli_loads                | 1.32 sec                                                            | 1.42 sec: 1.07x slower                                                |
| sqlglot_parse              | 874 us                                                              | 940 us: 1.07x slower                                                  |
| coroutines                 | 16.4 ms                                                             | 18.0 ms: 1.10x slower                                                 |
| pyflate                    | 295 ms                                                              | 331 ms: 1.12x slower                                                  |
| go                         | 102 ms                                                              | 114 ms: 1.12x slower                                                  |
| scimark_monte_carlo        | 45.7 ms                                                             | 52.9 ms: 1.16x slower                                                 |
| scimark_sor                | 74.4 ms                                                             | 100 ms: 1.35x slower                                                  |
| dask                       | 219 ms                                                              | 322 ms: 1.47x slower                                                  |
| Geometric mean             | (ref)                                                               | 1.01x slower                                                          |

Benchmark hidden because not significant (9): tornado_http, bench_mp_pool, pickle_dict, typing_runtime_protocols, python_startup_no_site, sympy_str, asyncio_websockets, pathlib, pylint
Ignored benchmarks (7) of results/bm-20221024-3.11.0-deaf509/bm-20221024-darwin-arm64-python-deaf509e8fc6e0363bd6-3.11.0-deaf509.json: aiohttp, coverage, flaskblogging, gunicorn, mypy2, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 97.78% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
