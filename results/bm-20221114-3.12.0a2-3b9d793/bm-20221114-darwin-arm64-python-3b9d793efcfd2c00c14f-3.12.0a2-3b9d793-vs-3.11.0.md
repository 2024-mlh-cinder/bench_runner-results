
# Results vs. 3.11.0

- fork: python
- ref: 3b9d793efcfd2c00c14f
- machine: darwin-arm64
- commit hash: 3b9d793
- commit date: 2022-11-14
- overall geometric mean: 1.02x slower
- HPT reliability: 99.15%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-darwin-arm64-python-deaf509e8fc6e0363bd6-3.11.0-deaf509 | bm-20221114-darwin-arm64-python-3b9d793efcfd2c00c14f-3.12.0a2-3b9d793 |
|----------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| 2to3           | 154 ms                                                              | 160 ms: 1.04x slower                                                  |
| chameleon      | 4.21 ms                                                             | 4.29 ms: 1.02x slower                                                 |
| docutils       | 1.43 sec                                                            | 1.43 sec: 1.00x slower                                                |
| Geometric mean | (ref)                                                               | 1.01x slower                                                          |

Benchmark hidden because not significant (2): html5lib, tornado_http

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20221024-darwin-arm64-python-deaf509e8fc6e0363bd6-3.11.0-deaf509 | bm-20221114-darwin-arm64-python-3b9d793efcfd2c00c14f-3.12.0a2-3b9d793 |
|----------------------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| async_tree_memoization     | 353 ms                                                              | 329 ms: 1.07x faster                                                  |
| async_tree_none_tg         | 277 ms                                                              | 262 ms: 1.06x faster                                                  |
| async_tree_memoization_tg  | 351 ms                                                              | 336 ms: 1.04x faster                                                  |
| async_tree_io_tg           | 723 ms                                                              | 703 ms: 1.03x faster                                                  |
| async_tree_cpu_io_mixed_tg | 548 ms                                                              | 539 ms: 1.02x faster                                                  |
| async_tree_cpu_io_mixed    | 516 ms                                                              | 522 ms: 1.01x slower                                                  |
| async_tree_none            | 277 ms                                                              | 281 ms: 1.01x slower                                                  |
| async_tree_io              | 691 ms                                                              | 725 ms: 1.05x slower                                                  |
| Geometric mean             | (ref)                                                               | 1.02x faster                                                          |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-darwin-arm64-python-deaf509e8fc6e0363bd6-3.11.0-deaf509 | bm-20221114-darwin-arm64-python-3b9d793efcfd2c00c14f-3.12.0a2-3b9d793 |
|----------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| pidigits       | 280 ms                                                              | 280 ms: 1.00x slower                                                  |
| nbody          | 68.5 ms                                                             | 68.8 ms: 1.00x slower                                                 |
| float          | 55.1 ms                                                             | 56.0 ms: 1.02x slower                                                 |
| Geometric mean | (ref)                                                               | 1.01x slower                                                          |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-darwin-arm64-python-deaf509e8fc6e0363bd6-3.11.0-deaf509 | bm-20221114-darwin-arm64-python-3b9d793efcfd2c00c14f-3.12.0a2-3b9d793 |
|----------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| regex_v8       | 15.4 ms                                                             | 15.0 ms: 1.03x faster                                                 |
| regex_dna      | 149 ms                                                              | 147 ms: 1.02x faster                                                  |
| regex_compile  | 73.5 ms                                                             | 72.7 ms: 1.01x faster                                                 |
| regex_effbot   | 2.45 ms                                                             | 2.44 ms: 1.00x faster                                                 |
| Geometric mean | (ref)                                                               | 1.02x faster                                                          |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-darwin-arm64-python-deaf509e8fc6e0363bd6-3.11.0-deaf509 | bm-20221114-darwin-arm64-python-3b9d793efcfd2c00c14f-3.12.0a2-3b9d793 |
|----------------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| json_dumps           | 7.58 ms                                                             | 5.97 ms: 1.27x faster                                                 |
| unpickle_pure_python | 162 us                                                              | 149 us: 1.09x faster                                                  |
| pickle_pure_python   | 210 us                                                              | 200 us: 1.05x faster                                                  |
| xml_etree_generate   | 47.1 ms                                                             | 46.0 ms: 1.02x faster                                                 |
| xml_etree_parse      | 97.6 ms                                                             | 95.4 ms: 1.02x faster                                                 |
| pickle_list          | 2.68 us                                                             | 2.64 us: 1.01x faster                                                 |
| unpickle_list        | 2.76 us                                                             | 2.73 us: 1.01x faster                                                 |
| unpickle             | 8.35 us                                                             | 8.39 us: 1.00x slower                                                 |
| json_loads           | 15.5 us                                                             | 15.6 us: 1.01x slower                                                 |
| pickle_dict          | 17.0 us                                                             | 17.1 us: 1.01x slower                                                 |
| xml_etree_iterparse  | 67.5 ms                                                             | 69.2 ms: 1.03x slower                                                 |
| tomli_loads          | 1.32 sec                                                            | 1.40 sec: 1.06x slower                                                |
| Geometric mean       | (ref)                                                               | 1.02x faster                                                          |

Benchmark hidden because not significant (2): pickle, xml_etree_process

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-darwin-arm64-python-deaf509e8fc6e0363bd6-3.11.0-deaf509 | bm-20221114-darwin-arm64-python-3b9d793efcfd2c00c14f-3.12.0a2-3b9d793 |
|------------------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| python_startup         | 11.5 ms                                                             | 11.4 ms: 1.01x faster                                                 |
| python_startup_no_site | 9.37 ms                                                             | 9.43 ms: 1.01x slower                                                 |
| Geometric mean         | (ref)                                                               | 1.00x faster                                                          |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20221024-darwin-arm64-python-deaf509e8fc6e0363bd6-3.11.0-deaf509 | bm-20221114-darwin-arm64-python-3b9d793efcfd2c00c14f-3.12.0a2-3b9d793 |
|-----------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| mako            | 8.25 ms                                                             | 7.55 ms: 1.09x faster                                                 |
| django_template | 19.6 ms                                                             | 19.7 ms: 1.01x slower                                                 |
| genshi_text     | 14.5 ms                                                             | 14.9 ms: 1.03x slower                                                 |
| Geometric mean  | (ref)                                                               | 1.01x faster                                                          |

Benchmark hidden because not significant (1): genshi_xml

All benchmarks:
===============

| Benchmark                  | bm-20221024-darwin-arm64-python-deaf509e8fc6e0363bd6-3.11.0-deaf509 | bm-20221114-darwin-arm64-python-3b9d793efcfd2c00c14f-3.12.0a2-3b9d793 |
|----------------------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| json_dumps                 | 7.58 ms                                                             | 5.97 ms: 1.27x faster                                                 |
| scimark_sparse_mat_mult    | 3.00 ms                                                             | 2.64 ms: 1.14x faster                                                 |
| mako                       | 8.25 ms                                                             | 7.55 ms: 1.09x faster                                                 |
| unpickle_pure_python       | 162 us                                                              | 149 us: 1.09x faster                                                  |
| async_tree_memoization     | 353 ms                                                              | 329 ms: 1.07x faster                                                  |
| gc_traversal               | 2.53 ms                                                             | 2.39 ms: 1.06x faster                                                 |
| deepcopy_memo              | 28.7 us                                                             | 27.1 us: 1.06x faster                                                 |
| async_tree_none_tg         | 277 ms                                                              | 262 ms: 1.06x faster                                                  |
| mdp                        | 1.84 sec                                                            | 1.74 sec: 1.06x faster                                                |
| pickle_pure_python         | 210 us                                                              | 200 us: 1.05x faster                                                  |
| create_gc_cycles           | 714 us                                                              | 683 us: 1.05x faster                                                  |
| async_tree_memoization_tg  | 351 ms                                                              | 336 ms: 1.04x faster                                                  |
| regex_v8                   | 15.4 ms                                                             | 15.0 ms: 1.03x faster                                                 |
| async_tree_io_tg           | 723 ms                                                              | 703 ms: 1.03x faster                                                  |
| deepcopy                   | 232 us                                                              | 225 us: 1.03x faster                                                  |
| xml_etree_generate         | 47.1 ms                                                             | 46.0 ms: 1.02x faster                                                 |
| xml_etree_parse            | 97.6 ms                                                             | 95.4 ms: 1.02x faster                                                 |
| deepcopy_reduce            | 1.96 us                                                             | 1.92 us: 1.02x faster                                                 |
| regex_dna                  | 149 ms                                                              | 147 ms: 1.02x faster                                                  |
| dulwich_log                | 29.2 ms                                                             | 28.7 ms: 1.02x faster                                                 |
| async_tree_cpu_io_mixed_tg | 548 ms                                                              | 539 ms: 1.02x faster                                                  |
| richards                   | 30.7 ms                                                             | 30.2 ms: 1.02x faster                                                 |
| scimark_lu                 | 67.9 ms                                                             | 67.0 ms: 1.01x faster                                                 |
| python_startup             | 11.5 ms                                                             | 11.4 ms: 1.01x faster                                                 |
| pickle_list                | 2.68 us                                                             | 2.64 us: 1.01x faster                                                 |
| unpickle_list              | 2.76 us                                                             | 2.73 us: 1.01x faster                                                 |
| regex_compile              | 73.5 ms                                                             | 72.7 ms: 1.01x faster                                                 |
| asyncio_tcp                | 664 ms                                                              | 658 ms: 1.01x faster                                                  |
| bench_thread_pool          | 467 us                                                              | 463 us: 1.01x faster                                                  |
| deltablue                  | 2.69 ms                                                             | 2.67 ms: 1.01x faster                                                 |
| telco                      | 3.17 ms                                                             | 3.15 ms: 1.01x faster                                                 |
| regex_effbot               | 2.45 ms                                                             | 2.44 ms: 1.00x faster                                                 |
| pidigits                   | 280 ms                                                              | 280 ms: 1.00x slower                                                  |
| docutils                   | 1.43 sec                                                            | 1.43 sec: 1.00x slower                                                |
| meteor_contest             | 75.3 ms                                                             | 75.6 ms: 1.00x slower                                                 |
| unpickle                   | 8.35 us                                                             | 8.39 us: 1.00x slower                                                 |
| nbody                      | 68.5 ms                                                             | 68.8 ms: 1.00x slower                                                 |
| django_template            | 19.6 ms                                                             | 19.7 ms: 1.01x slower                                                 |
| python_startup_no_site     | 9.37 ms                                                             | 9.43 ms: 1.01x slower                                                 |
| pprint_safe_repr           | 480 ms                                                              | 483 ms: 1.01x slower                                                  |
| json_loads                 | 15.5 us                                                             | 15.6 us: 1.01x slower                                                 |
| json                       | 2.77 ms                                                             | 2.79 ms: 1.01x slower                                                 |
| thrift                     | 420 us                                                              | 424 us: 1.01x slower                                                  |
| sympy_expand               | 236 ms                                                              | 238 ms: 1.01x slower                                                  |
| pickle_dict                | 17.0 us                                                             | 17.1 us: 1.01x slower                                                 |
| typing_runtime_protocols   | 322 us                                                              | 325 us: 1.01x slower                                                  |
| pprint_pformat             | 986 ms                                                              | 998 ms: 1.01x slower                                                  |
| async_tree_cpu_io_mixed    | 516 ms                                                              | 522 ms: 1.01x slower                                                  |
| sympy_str                  | 144 ms                                                              | 146 ms: 1.01x slower                                                  |
| async_tree_none            | 277 ms                                                              | 281 ms: 1.01x slower                                                  |
| logging_silent             | 64.3 ns                                                             | 65.2 ns: 1.01x slower                                                 |
| float                      | 55.1 ms                                                             | 56.0 ms: 1.02x slower                                                 |
| chameleon                  | 4.21 ms                                                             | 4.29 ms: 1.02x slower                                                 |
| logging_simple             | 3.45 us                                                             | 3.53 us: 1.02x slower                                                 |
| spectral_norm              | 69.4 ms                                                             | 70.9 ms: 1.02x slower                                                 |
| crypto_pyaes               | 47.9 ms                                                             | 49.0 ms: 1.02x slower                                                 |
| sympy_sum                  | 80.8 ms                                                             | 82.6 ms: 1.02x slower                                                 |
| xml_etree_iterparse        | 67.5 ms                                                             | 69.2 ms: 1.03x slower                                                 |
| logging_format             | 3.73 us                                                             | 3.82 us: 1.03x slower                                                 |
| genshi_text                | 14.5 ms                                                             | 14.9 ms: 1.03x slower                                                 |
| chaos                      | 48.2 ms                                                             | 49.7 ms: 1.03x slower                                                 |
| sqlglot_optimize           | 29.6 ms                                                             | 30.7 ms: 1.04x slower                                                 |
| 2to3                       | 154 ms                                                              | 160 ms: 1.04x slower                                                  |
| sqlite_synth               | 1.36 us                                                             | 1.42 us: 1.04x slower                                                 |
| sqlglot_normalize          | 160 ms                                                              | 167 ms: 1.04x slower                                                  |
| unpack_sequence            | 32.3 ns                                                             | 33.8 ns: 1.05x slower                                                 |
| async_tree_io              | 691 ms                                                              | 725 ms: 1.05x slower                                                  |
| fannkuch                   | 247 ms                                                              | 260 ms: 1.05x slower                                                  |
| async_generators           | 191 ms                                                              | 203 ms: 1.06x slower                                                  |
| tomli_loads                | 1.32 sec                                                            | 1.40 sec: 1.06x slower                                                |
| hexiom                     | 4.55 ms                                                             | 4.83 ms: 1.06x slower                                                 |
| raytrace                   | 205 ms                                                              | 220 ms: 1.07x slower                                                  |
| sqlglot_transpile          | 1.04 ms                                                             | 1.12 ms: 1.08x slower                                                 |
| nqueens                    | 54.3 ms                                                             | 58.8 ms: 1.08x slower                                                 |
| comprehensions             | 14.6 us                                                             | 15.9 us: 1.09x slower                                                 |
| sqlglot_parse              | 874 us                                                              | 954 us: 1.09x slower                                                  |
| pyflate                    | 295 ms                                                              | 329 ms: 1.11x slower                                                  |
| go                         | 102 ms                                                              | 115 ms: 1.13x slower                                                  |
| scimark_monte_carlo        | 45.7 ms                                                             | 52.5 ms: 1.15x slower                                                 |
| coroutines                 | 16.4 ms                                                             | 19.3 ms: 1.18x slower                                                 |
| generators                 | 29.0 ms                                                             | 36.6 ms: 1.26x slower                                                 |
| scimark_sor                | 74.4 ms                                                             | 103 ms: 1.39x slower                                                  |
| dask                       | 219 ms                                                              | 320 ms: 1.46x slower                                                  |
| Geometric mean             | (ref)                                                               | 1.02x slower                                                          |

Benchmark hidden because not significant (13): pickle, tornado_http, richards_super, scimark_fft, asyncio_tcp_ssl, pathlib, asyncio_websockets, xml_etree_process, genshi_xml, pycparser, bench_mp_pool, sympy_integrate, html5lib
Ignored benchmarks (8) of results/bm-20221024-3.11.0-deaf509/bm-20221024-darwin-arm64-python-deaf509e8fc6e0363bd6-3.11.0-deaf509.json: aiohttp, coverage, flaskblogging, gunicorn, mypy2, pylint, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 99.15% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
