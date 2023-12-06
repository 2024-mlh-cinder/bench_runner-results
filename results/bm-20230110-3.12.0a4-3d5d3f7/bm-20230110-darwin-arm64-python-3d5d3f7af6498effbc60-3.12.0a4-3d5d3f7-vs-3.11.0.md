
# Results vs. 3.11.0

- fork: python
- ref: 3d5d3f7af6498effbc60
- machine: darwin-arm64
- commit hash: 3d5d3f7
- commit date: 2023-01-10
- overall geometric mean: 1.01x faster
- HPT reliability: 91.46%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-darwin-arm64-python-deaf509e8fc6e0363bd6-3.11.0-deaf509 | bm-20230110-darwin-arm64-python-3d5d3f7af6498effbc60-3.12.0a4-3d5d3f7 |
|----------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| 2to3           | 154 ms                                                              | 158 ms: 1.03x slower                                                  |
| docutils       | 1.43 sec                                                            | 1.41 sec: 1.01x faster                                                |
| html5lib       | 33.3 ms                                                             | 32.3 ms: 1.03x faster                                                 |
| Geometric mean | (ref)                                                               | 1.00x faster                                                          |

Benchmark hidden because not significant (1): chameleon

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20221024-darwin-arm64-python-deaf509e8fc6e0363bd6-3.11.0-deaf509 | bm-20230110-darwin-arm64-python-3d5d3f7af6498effbc60-3.12.0a4-3d5d3f7 |
|----------------------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| async_tree_memoization     | 353 ms                                                              | 322 ms: 1.09x faster                                                  |
| async_tree_none_tg         | 277 ms                                                              | 266 ms: 1.04x faster                                                  |
| async_tree_memoization_tg  | 351 ms                                                              | 340 ms: 1.03x faster                                                  |
| async_tree_io_tg           | 723 ms                                                              | 710 ms: 1.02x faster                                                  |
| async_tree_cpu_io_mixed_tg | 548 ms                                                              | 543 ms: 1.01x faster                                                  |
| async_tree_none            | 277 ms                                                              | 280 ms: 1.01x slower                                                  |
| async_tree_cpu_io_mixed    | 516 ms                                                              | 521 ms: 1.01x slower                                                  |
| async_tree_io              | 691 ms                                                              | 728 ms: 1.05x slower                                                  |
| Geometric mean             | (ref)                                                               | 1.02x faster                                                          |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-darwin-arm64-python-deaf509e8fc6e0363bd6-3.11.0-deaf509 | bm-20230110-darwin-arm64-python-3d5d3f7af6498effbc60-3.12.0a4-3d5d3f7 |
|----------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| nbody          | 68.5 ms                                                             | 67.7 ms: 1.01x faster                                                 |
| float          | 55.1 ms                                                             | 55.5 ms: 1.01x slower                                                 |
| Geometric mean | (ref)                                                               | 1.00x faster                                                          |

Benchmark hidden because not significant (1): pidigits

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-darwin-arm64-python-deaf509e8fc6e0363bd6-3.11.0-deaf509 | bm-20230110-darwin-arm64-python-3d5d3f7af6498effbc60-3.12.0a4-3d5d3f7 |
|----------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| regex_v8       | 15.4 ms                                                             | 15.0 ms: 1.03x faster                                                 |
| regex_compile  | 73.5 ms                                                             | 72.1 ms: 1.02x faster                                                 |
| regex_dna      | 149 ms                                                              | 147 ms: 1.02x faster                                                  |
| regex_effbot   | 2.45 ms                                                             | 2.44 ms: 1.00x faster                                                 |
| Geometric mean | (ref)                                                               | 1.02x faster                                                          |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-darwin-arm64-python-deaf509e8fc6e0363bd6-3.11.0-deaf509 | bm-20230110-darwin-arm64-python-3d5d3f7af6498effbc60-3.12.0a4-3d5d3f7 |
|----------------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| json_dumps           | 7.58 ms                                                             | 5.84 ms: 1.30x faster                                                 |
| unpickle_pure_python | 162 us                                                              | 137 us: 1.18x faster                                                  |
| pickle_pure_python   | 210 us                                                              | 190 us: 1.11x faster                                                  |
| tomli_loads          | 1.32 sec                                                            | 1.28 sec: 1.03x faster                                                |
| pickle               | 7.17 us                                                             | 6.98 us: 1.03x faster                                                 |
| xml_etree_parse      | 97.6 ms                                                             | 96.4 ms: 1.01x faster                                                 |
| xml_etree_process    | 34.1 ms                                                             | 33.8 ms: 1.01x faster                                                 |
| xml_etree_generate   | 47.1 ms                                                             | 46.9 ms: 1.01x faster                                                 |
| pickle_dict          | 17.0 us                                                             | 17.0 us: 1.00x slower                                                 |
| unpickle             | 8.35 us                                                             | 8.43 us: 1.01x slower                                                 |
| pickle_list          | 2.68 us                                                             | 2.70 us: 1.01x slower                                                 |
| unpickle_list        | 2.76 us                                                             | 2.81 us: 1.02x slower                                                 |
| xml_etree_iterparse  | 67.5 ms                                                             | 70.0 ms: 1.04x slower                                                 |
| Geometric mean       | (ref)                                                               | 1.04x faster                                                          |

Benchmark hidden because not significant (1): json_loads

Benchmarks with tag 'startup':
==============================

| Benchmark      | bm-20221024-darwin-arm64-python-deaf509e8fc6e0363bd6-3.11.0-deaf509 | bm-20230110-darwin-arm64-python-3d5d3f7af6498effbc60-3.12.0a4-3d5d3f7 |
|----------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| python_startup | 11.5 ms                                                             | 11.4 ms: 1.01x faster                                                 |
| Geometric mean | (ref)                                                               | 1.00x slower                                                          |

Benchmark hidden because not significant (1): python_startup_no_site

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20221024-darwin-arm64-python-deaf509e8fc6e0363bd6-3.11.0-deaf509 | bm-20230110-darwin-arm64-python-3d5d3f7af6498effbc60-3.12.0a4-3d5d3f7 |
|-----------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| mako            | 8.25 ms                                                             | 7.76 ms: 1.06x faster                                                 |
| genshi_xml      | 28.3 ms                                                             | 27.3 ms: 1.04x faster                                                 |
| genshi_text     | 14.5 ms                                                             | 14.2 ms: 1.02x faster                                                 |
| django_template | 19.6 ms                                                             | 20.8 ms: 1.06x slower                                                 |
| Geometric mean  | (ref)                                                               | 1.01x faster                                                          |

All benchmarks:
===============

| Benchmark                  | bm-20221024-darwin-arm64-python-deaf509e8fc6e0363bd6-3.11.0-deaf509 | bm-20230110-darwin-arm64-python-3d5d3f7af6498effbc60-3.12.0a4-3d5d3f7 |
|----------------------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| asyncio_tcp                | 664 ms                                                              | 430 ms: 1.54x faster                                                  |
| json_dumps                 | 7.58 ms                                                             | 5.84 ms: 1.30x faster                                                 |
| unpickle_pure_python       | 162 us                                                              | 137 us: 1.18x faster                                                  |
| asyncio_tcp_ssl            | 1.43 sec                                                            | 1.26 sec: 1.13x faster                                                |
| scimark_sparse_mat_mult    | 3.00 ms                                                             | 2.66 ms: 1.13x faster                                                 |
| pickle_pure_python         | 210 us                                                              | 190 us: 1.11x faster                                                  |
| async_tree_memoization     | 353 ms                                                              | 322 ms: 1.09x faster                                                  |
| mdp                        | 1.84 sec                                                            | 1.70 sec: 1.08x faster                                                |
| deltablue                  | 2.69 ms                                                             | 2.51 ms: 1.07x faster                                                 |
| unpack_sequence            | 32.3 ns                                                             | 30.2 ns: 1.07x faster                                                 |
| mako                       | 8.25 ms                                                             | 7.76 ms: 1.06x faster                                                 |
| gc_traversal               | 2.53 ms                                                             | 2.38 ms: 1.06x faster                                                 |
| meteor_contest             | 75.3 ms                                                             | 71.1 ms: 1.06x faster                                                 |
| create_gc_cycles           | 714 us                                                              | 686 us: 1.04x faster                                                  |
| async_tree_none_tg         | 277 ms                                                              | 266 ms: 1.04x faster                                                  |
| genshi_xml                 | 28.3 ms                                                             | 27.3 ms: 1.04x faster                                                 |
| logging_format             | 3.73 us                                                             | 3.60 us: 1.03x faster                                                 |
| async_tree_memoization_tg  | 351 ms                                                              | 340 ms: 1.03x faster                                                  |
| dulwich_log                | 29.2 ms                                                             | 28.2 ms: 1.03x faster                                                 |
| deepcopy_memo              | 28.7 us                                                             | 27.7 us: 1.03x faster                                                 |
| logging_simple             | 3.45 us                                                             | 3.34 us: 1.03x faster                                                 |
| html5lib                   | 33.3 ms                                                             | 32.3 ms: 1.03x faster                                                 |
| tomli_loads                | 1.32 sec                                                            | 1.28 sec: 1.03x faster                                                |
| regex_v8                   | 15.4 ms                                                             | 15.0 ms: 1.03x faster                                                 |
| richards                   | 30.7 ms                                                             | 29.8 ms: 1.03x faster                                                 |
| pickle                     | 7.17 us                                                             | 6.98 us: 1.03x faster                                                 |
| sympy_expand               | 236 ms                                                              | 230 ms: 1.03x faster                                                  |
| pycparser                  | 658 ms                                                              | 643 ms: 1.02x faster                                                  |
| genshi_text                | 14.5 ms                                                             | 14.2 ms: 1.02x faster                                                 |
| scimark_fft                | 186 ms                                                              | 182 ms: 1.02x faster                                                  |
| deepcopy                   | 232 us                                                              | 227 us: 1.02x faster                                                  |
| richards_super             | 36.7 ms                                                             | 36.0 ms: 1.02x faster                                                 |
| regex_compile              | 73.5 ms                                                             | 72.1 ms: 1.02x faster                                                 |
| regex_dna                  | 149 ms                                                              | 147 ms: 1.02x faster                                                  |
| async_tree_io_tg           | 723 ms                                                              | 710 ms: 1.02x faster                                                  |
| bench_thread_pool          | 467 us                                                              | 460 us: 1.01x faster                                                  |
| fannkuch                   | 247 ms                                                              | 244 ms: 1.01x faster                                                  |
| xml_etree_parse            | 97.6 ms                                                             | 96.4 ms: 1.01x faster                                                 |
| docutils                   | 1.43 sec                                                            | 1.41 sec: 1.01x faster                                                |
| nbody                      | 68.5 ms                                                             | 67.7 ms: 1.01x faster                                                 |
| sympy_integrate            | 11.2 ms                                                             | 11.1 ms: 1.01x faster                                                 |
| python_startup             | 11.5 ms                                                             | 11.4 ms: 1.01x faster                                                 |
| xml_etree_process          | 34.1 ms                                                             | 33.8 ms: 1.01x faster                                                 |
| scimark_lu                 | 67.9 ms                                                             | 67.3 ms: 1.01x faster                                                 |
| async_tree_cpu_io_mixed_tg | 548 ms                                                              | 543 ms: 1.01x faster                                                  |
| pprint_pformat             | 986 ms                                                              | 977 ms: 1.01x faster                                                  |
| deepcopy_reduce            | 1.96 us                                                             | 1.94 us: 1.01x faster                                                 |
| logging_silent             | 64.3 ns                                                             | 63.9 ns: 1.01x faster                                                 |
| sympy_str                  | 144 ms                                                              | 144 ms: 1.01x faster                                                  |
| xml_etree_generate         | 47.1 ms                                                             | 46.9 ms: 1.01x faster                                                 |
| regex_effbot               | 2.45 ms                                                             | 2.44 ms: 1.00x faster                                                 |
| typing_runtime_protocols   | 322 us                                                              | 320 us: 1.00x faster                                                  |
| thrift                     | 420 us                                                              | 419 us: 1.00x faster                                                  |
| pickle_dict                | 17.0 us                                                             | 17.0 us: 1.00x slower                                                 |
| sqlite_synth               | 1.36 us                                                             | 1.36 us: 1.00x slower                                                 |
| json                       | 2.77 ms                                                             | 2.79 ms: 1.01x slower                                                 |
| float                      | 55.1 ms                                                             | 55.5 ms: 1.01x slower                                                 |
| async_tree_none            | 277 ms                                                              | 280 ms: 1.01x slower                                                  |
| unpickle                   | 8.35 us                                                             | 8.43 us: 1.01x slower                                                 |
| pickle_list                | 2.68 us                                                             | 2.70 us: 1.01x slower                                                 |
| async_tree_cpu_io_mixed    | 516 ms                                                              | 521 ms: 1.01x slower                                                  |
| sympy_sum                  | 80.8 ms                                                             | 81.7 ms: 1.01x slower                                                 |
| raytrace                   | 205 ms                                                              | 208 ms: 1.01x slower                                                  |
| sqlglot_optimize           | 29.6 ms                                                             | 30.0 ms: 1.01x slower                                                 |
| spectral_norm              | 69.4 ms                                                             | 70.6 ms: 1.02x slower                                                 |
| pyflate                    | 295 ms                                                              | 301 ms: 1.02x slower                                                  |
| telco                      | 3.17 ms                                                             | 3.22 ms: 1.02x slower                                                 |
| unpickle_list              | 2.76 us                                                             | 2.81 us: 1.02x slower                                                 |
| scimark_monte_carlo        | 45.7 ms                                                             | 46.8 ms: 1.02x slower                                                 |
| hexiom                     | 4.55 ms                                                             | 4.66 ms: 1.03x slower                                                 |
| chaos                      | 48.2 ms                                                             | 49.5 ms: 1.03x slower                                                 |
| 2to3                       | 154 ms                                                              | 158 ms: 1.03x slower                                                  |
| sqlglot_normalize          | 160 ms                                                              | 165 ms: 1.03x slower                                                  |
| go                         | 102 ms                                                              | 106 ms: 1.03x slower                                                  |
| xml_etree_iterparse        | 67.5 ms                                                             | 70.0 ms: 1.04x slower                                                 |
| async_generators           | 191 ms                                                              | 200 ms: 1.04x slower                                                  |
| crypto_pyaes               | 47.9 ms                                                             | 50.4 ms: 1.05x slower                                                 |
| async_tree_io              | 691 ms                                                              | 728 ms: 1.05x slower                                                  |
| nqueens                    | 54.3 ms                                                             | 57.2 ms: 1.05x slower                                                 |
| django_template            | 19.6 ms                                                             | 20.8 ms: 1.06x slower                                                 |
| coroutines                 | 16.4 ms                                                             | 17.5 ms: 1.06x slower                                                 |
| sqlglot_transpile          | 1.04 ms                                                             | 1.15 ms: 1.11x slower                                                 |
| scimark_sor                | 74.4 ms                                                             | 83.4 ms: 1.12x slower                                                 |
| sqlglot_parse              | 874 us                                                              | 985 us: 1.13x slower                                                  |
| comprehensions             | 14.6 us                                                             | 16.6 us: 1.14x slower                                                 |
| generators                 | 29.0 ms                                                             | 35.1 ms: 1.21x slower                                                 |
| dask                       | 219 ms                                                              | 309 ms: 1.41x slower                                                  |
| Geometric mean             | (ref)                                                               | 1.01x faster                                                          |

Benchmark hidden because not significant (8): json_loads, pprint_safe_repr, chameleon, pidigits, asyncio_websockets, pathlib, bench_mp_pool, python_startup_no_site
Ignored benchmarks (9) of results/bm-20221024-3.11.0-deaf509/bm-20221024-darwin-arm64-python-deaf509e8fc6e0363bd6-3.11.0-deaf509.json: aiohttp, coverage, flaskblogging, gunicorn, mypy2, pylint, sqlalchemy_declarative, sqlalchemy_imperative, tornado_http


# HPT report

- Reliability score: 91.46% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
