
# Results vs. 3.11.0

- fork: python
- ref: 8d32a5c8c4e9c90b0a21
- machine: darwin-arm64
- commit hash: 8d32a5c
- commit date: 2022-05-06
- overall geometric mean: 1.01x slower
- HPT reliability: 83.47%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-darwin-arm64-python-deaf509e8fc6e0363bd6-3.11.0-deaf509 | bm-20220506-darwin-arm64-python-8d32a5c8c4e9c90b0a21-3.11.0b1-8d32a5c |
|----------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| 2to3           | 154 ms                                                              | 152 ms: 1.01x faster                                                  |
| chameleon      | 4.21 ms                                                             | 4.32 ms: 1.03x slower                                                 |
| docutils       | 1.43 sec                                                            | 1.39 sec: 1.03x faster                                                |
| html5lib       | 33.3 ms                                                             | 31.0 ms: 1.07x faster                                                 |
| Geometric mean | (ref)                                                               | 1.02x faster                                                          |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20221024-darwin-arm64-python-deaf509e8fc6e0363bd6-3.11.0-deaf509 | bm-20220506-darwin-arm64-python-8d32a5c8c4e9c90b0a21-3.11.0b1-8d32a5c |
|----------------------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| async_tree_io_tg           | 723 ms                                                              | 737 ms: 1.02x slower                                                  |
| async_tree_cpu_io_mixed_tg | 548 ms                                                              | 607 ms: 1.11x slower                                                  |
| async_tree_none_tg         | 277 ms                                                              | 332 ms: 1.20x slower                                                  |
| async_tree_memoization_tg  | 351 ms                                                              | 434 ms: 1.23x slower                                                  |
| Geometric mean             | (ref)                                                               | 1.07x slower                                                          |

Benchmark hidden because not significant (4): async_tree_cpu_io_mixed, async_tree_io, async_tree_memoization, async_tree_none

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-darwin-arm64-python-deaf509e8fc6e0363bd6-3.11.0-deaf509 | bm-20220506-darwin-arm64-python-8d32a5c8c4e9c90b0a21-3.11.0b1-8d32a5c |
|----------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| nbody          | 68.5 ms                                                             | 65.6 ms: 1.04x faster                                                 |
| float          | 55.1 ms                                                             | 53.3 ms: 1.03x faster                                                 |
| pidigits       | 280 ms                                                              | 281 ms: 1.00x slower                                                  |
| Geometric mean | (ref)                                                               | 1.03x faster                                                          |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-darwin-arm64-python-deaf509e8fc6e0363bd6-3.11.0-deaf509 | bm-20220506-darwin-arm64-python-8d32a5c8c4e9c90b0a21-3.11.0b1-8d32a5c |
|----------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| regex_effbot   | 2.45 ms                                                             | 2.26 ms: 1.08x faster                                                 |
| regex_dna      | 149 ms                                                              | 144 ms: 1.04x faster                                                  |
| regex_compile  | 73.5 ms                                                             | 73.1 ms: 1.00x faster                                                 |
| regex_v8       | 15.4 ms                                                             | 15.8 ms: 1.02x slower                                                 |
| Geometric mean | (ref)                                                               | 1.02x faster                                                          |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-darwin-arm64-python-deaf509e8fc6e0363bd6-3.11.0-deaf509 | bm-20220506-darwin-arm64-python-8d32a5c8c4e9c90b0a21-3.11.0b1-8d32a5c |
|----------------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| pickle_pure_python   | 210 us                                                              | 196 us: 1.07x faster                                                  |
| unpickle_pure_python | 162 us                                                              | 152 us: 1.07x faster                                                  |
| pickle_list          | 2.68 us                                                             | 2.55 us: 1.05x faster                                                 |
| pickle_dict          | 17.0 us                                                             | 16.2 us: 1.05x faster                                                 |
| pickle               | 7.17 us                                                             | 6.98 us: 1.03x faster                                                 |
| tomli_loads          | 1.32 sec                                                            | 1.31 sec: 1.01x faster                                                |
| xml_etree_generate   | 47.1 ms                                                             | 46.9 ms: 1.00x faster                                                 |
| unpickle             | 8.35 us                                                             | 8.32 us: 1.00x faster                                                 |
| xml_etree_process    | 34.1 ms                                                             | 34.2 ms: 1.00x slower                                                 |
| unpickle_list        | 2.76 us                                                             | 2.77 us: 1.00x slower                                                 |
| Geometric mean       | (ref)                                                               | 1.02x faster                                                          |

Benchmark hidden because not significant (4): xml_etree_iterparse, xml_etree_parse, json_loads, json_dumps

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-darwin-arm64-python-deaf509e8fc6e0363bd6-3.11.0-deaf509 | bm-20220506-darwin-arm64-python-8d32a5c8c4e9c90b0a21-3.11.0b1-8d32a5c |
|------------------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| python_startup_no_site | 9.37 ms                                                             | 9.27 ms: 1.01x faster                                                 |
| python_startup         | 11.5 ms                                                             | 11.4 ms: 1.01x faster                                                 |
| Geometric mean         | (ref)                                                               | 1.01x faster                                                          |

Benchmarks with tag 'template':
===============================

| Benchmark      | bm-20221024-darwin-arm64-python-deaf509e8fc6e0363bd6-3.11.0-deaf509 | bm-20220506-darwin-arm64-python-8d32a5c8c4e9c90b0a21-3.11.0b1-8d32a5c |
|----------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| mako           | 8.25 ms                                                             | 8.18 ms: 1.01x faster                                                 |
| genshi_xml     | 28.3 ms                                                             | 28.7 ms: 1.02x slower                                                 |
| Geometric mean | (ref)                                                               | 1.00x slower                                                          |

Benchmark hidden because not significant (2): django_template, genshi_text

All benchmarks:
===============

| Benchmark                  | bm-20221024-darwin-arm64-python-deaf509e8fc6e0363bd6-3.11.0-deaf509 | bm-20220506-darwin-arm64-python-8d32a5c8c4e9c90b0a21-3.11.0b1-8d32a5c |
|----------------------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| regex_effbot               | 2.45 ms                                                             | 2.26 ms: 1.08x faster                                                 |
| html5lib                   | 33.3 ms                                                             | 31.0 ms: 1.07x faster                                                 |
| pickle_pure_python         | 210 us                                                              | 196 us: 1.07x faster                                                  |
| unpickle_pure_python       | 162 us                                                              | 152 us: 1.07x faster                                                  |
| gc_traversal               | 2.53 ms                                                             | 2.38 ms: 1.06x faster                                                 |
| mdp                        | 1.84 sec                                                            | 1.73 sec: 1.06x faster                                                |
| pickle_list                | 2.68 us                                                             | 2.55 us: 1.05x faster                                                 |
| pickle_dict                | 17.0 us                                                             | 16.2 us: 1.05x faster                                                 |
| nbody                      | 68.5 ms                                                             | 65.6 ms: 1.04x faster                                                 |
| meteor_contest             | 75.3 ms                                                             | 72.5 ms: 1.04x faster                                                 |
| scimark_monte_carlo        | 45.7 ms                                                             | 44.1 ms: 1.04x faster                                                 |
| regex_dna                  | 149 ms                                                              | 144 ms: 1.04x faster                                                  |
| sympy_sum                  | 80.8 ms                                                             | 78.1 ms: 1.03x faster                                                 |
| float                      | 55.1 ms                                                             | 53.3 ms: 1.03x faster                                                 |
| pyflate                    | 295 ms                                                              | 286 ms: 1.03x faster                                                  |
| deepcopy_memo              | 28.7 us                                                             | 27.8 us: 1.03x faster                                                 |
| docutils                   | 1.43 sec                                                            | 1.39 sec: 1.03x faster                                                |
| pickle                     | 7.17 us                                                             | 6.98 us: 1.03x faster                                                 |
| sqlalchemy_imperative      | 7.33 ms                                                             | 7.14 ms: 1.03x faster                                                 |
| thrift                     | 420 us                                                              | 411 us: 1.02x faster                                                  |
| scimark_fft                | 186 ms                                                              | 182 ms: 1.02x faster                                                  |
| sqlite_synth               | 1.36 us                                                             | 1.33 us: 1.02x faster                                                 |
| sympy_expand               | 236 ms                                                              | 232 ms: 1.02x faster                                                  |
| spectral_norm              | 69.4 ms                                                             | 68.2 ms: 1.02x faster                                                 |
| scimark_sparse_mat_mult    | 3.00 ms                                                             | 2.95 ms: 1.02x faster                                                 |
| deepcopy                   | 232 us                                                              | 228 us: 1.02x faster                                                  |
| logging_simple             | 3.45 us                                                             | 3.41 us: 1.01x faster                                                 |
| logging_format             | 3.73 us                                                             | 3.68 us: 1.01x faster                                                 |
| deepcopy_reduce            | 1.96 us                                                             | 1.93 us: 1.01x faster                                                 |
| sqlalchemy_declarative     | 60.4 ms                                                             | 59.7 ms: 1.01x faster                                                 |
| raytrace                   | 205 ms                                                              | 203 ms: 1.01x faster                                                  |
| python_startup_no_site     | 9.37 ms                                                             | 9.27 ms: 1.01x faster                                                 |
| python_startup             | 11.5 ms                                                             | 11.4 ms: 1.01x faster                                                 |
| dulwich_log                | 29.2 ms                                                             | 28.9 ms: 1.01x faster                                                 |
| sympy_str                  | 144 ms                                                              | 143 ms: 1.01x faster                                                  |
| 2to3                       | 154 ms                                                              | 152 ms: 1.01x faster                                                  |
| mako                       | 8.25 ms                                                             | 8.18 ms: 1.01x faster                                                 |
| tomli_loads                | 1.32 sec                                                            | 1.31 sec: 1.01x faster                                                |
| sympy_integrate            | 11.2 ms                                                             | 11.1 ms: 1.01x faster                                                 |
| async_generators           | 191 ms                                                              | 190 ms: 1.01x faster                                                  |
| xml_etree_generate         | 47.1 ms                                                             | 46.9 ms: 1.00x faster                                                 |
| regex_compile              | 73.5 ms                                                             | 73.1 ms: 1.00x faster                                                 |
| unpickle                   | 8.35 us                                                             | 8.32 us: 1.00x faster                                                 |
| crypto_pyaes               | 47.9 ms                                                             | 47.8 ms: 1.00x faster                                                 |
| mypy2                      | 187 ms                                                              | 187 ms: 1.00x faster                                                  |
| chaos                      | 48.2 ms                                                             | 48.2 ms: 1.00x faster                                                 |
| pidigits                   | 280 ms                                                              | 281 ms: 1.00x slower                                                  |
| xml_etree_process          | 34.1 ms                                                             | 34.2 ms: 1.00x slower                                                 |
| telco                      | 3.17 ms                                                             | 3.18 ms: 1.00x slower                                                 |
| unpickle_list              | 2.76 us                                                             | 2.77 us: 1.00x slower                                                 |
| pprint_safe_repr           | 480 ms                                                              | 482 ms: 1.00x slower                                                  |
| asyncio_tcp_ssl            | 1.43 sec                                                            | 1.43 sec: 1.01x slower                                                |
| scimark_lu                 | 67.9 ms                                                             | 68.4 ms: 1.01x slower                                                 |
| deltablue                  | 2.69 ms                                                             | 2.71 ms: 1.01x slower                                                 |
| hexiom                     | 4.55 ms                                                             | 4.59 ms: 1.01x slower                                                 |
| richards                   | 30.7 ms                                                             | 31.1 ms: 1.01x slower                                                 |
| genshi_xml                 | 28.3 ms                                                             | 28.7 ms: 1.02x slower                                                 |
| typing_runtime_protocols   | 322 us                                                              | 327 us: 1.02x slower                                                  |
| go                         | 102 ms                                                              | 104 ms: 1.02x slower                                                  |
| unpack_sequence            | 32.3 ns                                                             | 32.9 ns: 1.02x slower                                                 |
| async_tree_io_tg           | 723 ms                                                              | 737 ms: 1.02x slower                                                  |
| richards_super             | 36.7 ms                                                             | 37.4 ms: 1.02x slower                                                 |
| logging_silent             | 64.3 ns                                                             | 65.8 ns: 1.02x slower                                                 |
| regex_v8                   | 15.4 ms                                                             | 15.8 ms: 1.02x slower                                                 |
| sqlglot_normalize          | 160 ms                                                              | 164 ms: 1.03x slower                                                  |
| chameleon                  | 4.21 ms                                                             | 4.32 ms: 1.03x slower                                                 |
| coroutines                 | 16.4 ms                                                             | 16.9 ms: 1.03x slower                                                 |
| bench_thread_pool          | 467 us                                                              | 480 us: 1.03x slower                                                  |
| generators                 | 29.0 ms                                                             | 29.9 ms: 1.03x slower                                                 |
| sqlglot_optimize           | 29.6 ms                                                             | 30.5 ms: 1.03x slower                                                 |
| scimark_sor                | 74.4 ms                                                             | 78.2 ms: 1.05x slower                                                 |
| async_tree_cpu_io_mixed_tg | 548 ms                                                              | 607 ms: 1.11x slower                                                  |
| comprehensions             | 14.6 us                                                             | 17.1 us: 1.17x slower                                                 |
| async_tree_none_tg         | 277 ms                                                              | 332 ms: 1.20x slower                                                  |
| async_tree_memoization_tg  | 351 ms                                                              | 434 ms: 1.23x slower                                                  |
| sqlglot_transpile          | 1.04 ms                                                             | 1.29 ms: 1.24x slower                                                 |
| sqlglot_parse              | 874 us                                                              | 1.12 ms: 1.29x slower                                                 |
| coverage                   | 41.4 ms                                                             | 73.6 ms: 1.78x slower                                                 |
| Geometric mean             | (ref)                                                               | 1.01x slower                                                          |

Benchmark hidden because not significant (26): tornado_http, bench_mp_pool, asyncio_tcp, xml_etree_iterparse, xml_etree_parse, async_tree_cpu_io_mixed, async_tree_io, json_loads, json_dumps, asyncio_websockets, json, pprint_pformat, django_template, async_tree_memoization, async_tree_none, fannkuch, create_gc_cycles, pycparser, genshi_text, nqueens, pathlib, aiohttp, pylint, flaskblogging, dask, gunicorn


# HPT report

- Reliability score: 83.47% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
