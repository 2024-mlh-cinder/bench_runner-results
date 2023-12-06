
# Results vs. 3.11.0

- fork: python
- ref: 2e49bd06c5ffab7d1540
- machine: darwin-arm64
- commit hash: 2e49bd0
- commit date: 2022-04-05
- overall geometric mean: 1.03x slower
- HPT reliability: 99.81%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-darwin-arm64-python-deaf509e8fc6e0363bd6-3.11.0-deaf509 | bm-20220405-darwin-arm64-python-2e49bd06c5ffab7d1540-3.11.0a7-2e49bd0 |
|----------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| 2to3           | 154 ms                                                              | 156 ms: 1.01x slower                                                  |
| chameleon      | 4.21 ms                                                             | 4.32 ms: 1.03x slower                                                 |
| docutils       | 1.43 sec                                                            | 1.40 sec: 1.02x faster                                                |
| html5lib       | 33.3 ms                                                             | 32.3 ms: 1.03x faster                                                 |
| Geometric mean | (ref)                                                               | 1.00x faster                                                          |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20221024-darwin-arm64-python-deaf509e8fc6e0363bd6-3.11.0-deaf509 | bm-20220405-darwin-arm64-python-2e49bd06c5ffab7d1540-3.11.0a7-2e49bd0 |
|----------------------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| async_tree_io_tg           | 723 ms                                                              | 748 ms: 1.04x slower                                                  |
| async_tree_cpu_io_mixed_tg | 548 ms                                                              | 611 ms: 1.12x slower                                                  |
| async_tree_none_tg         | 277 ms                                                              | 338 ms: 1.22x slower                                                  |
| async_tree_memoization_tg  | 351 ms                                                              | 436 ms: 1.24x slower                                                  |
| Geometric mean             | (ref)                                                               | 1.08x slower                                                          |

Benchmark hidden because not significant (4): async_tree_none, async_tree_cpu_io_mixed, async_tree_io, async_tree_memoization

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-darwin-arm64-python-deaf509e8fc6e0363bd6-3.11.0-deaf509 | bm-20220405-darwin-arm64-python-2e49bd06c5ffab7d1540-3.11.0a7-2e49bd0 |
|----------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| float          | 55.1 ms                                                             | 49.9 ms: 1.10x faster                                                 |
| nbody          | 68.5 ms                                                             | 67.4 ms: 1.02x faster                                                 |
| pidigits       | 280 ms                                                              | 280 ms: 1.00x slower                                                  |
| Geometric mean | (ref)                                                               | 1.04x faster                                                          |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-darwin-arm64-python-deaf509e8fc6e0363bd6-3.11.0-deaf509 | bm-20220405-darwin-arm64-python-2e49bd06c5ffab7d1540-3.11.0a7-2e49bd0 |
|----------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| regex_effbot   | 2.45 ms                                                             | 2.07 ms: 1.18x faster                                                 |
| regex_compile  | 73.5 ms                                                             | 73.7 ms: 1.00x slower                                                 |
| regex_dna      | 149 ms                                                              | 175 ms: 1.17x slower                                                  |
| regex_v8       | 15.4 ms                                                             | 19.3 ms: 1.25x slower                                                 |
| Geometric mean | (ref)                                                               | 1.06x slower                                                          |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-darwin-arm64-python-deaf509e8fc6e0363bd6-3.11.0-deaf509 | bm-20220405-darwin-arm64-python-2e49bd06c5ffab7d1540-3.11.0a7-2e49bd0 |
|----------------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| pickle_pure_python   | 210 us                                                              | 190 us: 1.10x faster                                                  |
| unpickle_pure_python | 162 us                                                              | 149 us: 1.09x faster                                                  |
| json_loads           | 15.5 us                                                             | 14.9 us: 1.04x faster                                                 |
| xml_etree_parse      | 97.6 ms                                                             | 97.0 ms: 1.01x faster                                                 |
| pickle_list          | 2.68 us                                                             | 2.66 us: 1.00x faster                                                 |
| unpickle             | 8.35 us                                                             | 8.31 us: 1.00x faster                                                 |
| xml_etree_generate   | 47.1 ms                                                             | 47.0 ms: 1.00x faster                                                 |
| xml_etree_process    | 34.1 ms                                                             | 34.6 ms: 1.01x slower                                                 |
| unpickle_list        | 2.76 us                                                             | 2.80 us: 1.02x slower                                                 |
| pickle_dict          | 17.0 us                                                             | 17.4 us: 1.03x slower                                                 |
| tomli_loads          | 1.32 sec                                                            | 1.36 sec: 1.03x slower                                                |
| Geometric mean       | (ref)                                                               | 1.01x faster                                                          |

Benchmark hidden because not significant (3): xml_etree_iterparse, json_dumps, pickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-darwin-arm64-python-deaf509e8fc6e0363bd6-3.11.0-deaf509 | bm-20220405-darwin-arm64-python-2e49bd06c5ffab7d1540-3.11.0a7-2e49bd0 |
|------------------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| python_startup_no_site | 9.37 ms                                                             | 9.19 ms: 1.02x faster                                                 |
| python_startup         | 11.5 ms                                                             | 11.4 ms: 1.01x faster                                                 |
| Geometric mean         | (ref)                                                               | 1.02x faster                                                          |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20221024-darwin-arm64-python-deaf509e8fc6e0363bd6-3.11.0-deaf509 | bm-20220405-darwin-arm64-python-2e49bd06c5ffab7d1540-3.11.0a7-2e49bd0 |
|-----------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| mako            | 8.25 ms                                                             | 7.05 ms: 1.17x faster                                                 |
| genshi_text     | 14.5 ms                                                             | 14.0 ms: 1.03x faster                                                 |
| django_template | 19.6 ms                                                             | 20.0 ms: 1.02x slower                                                 |
| genshi_xml      | 28.3 ms                                                             | 29.7 ms: 1.05x slower                                                 |
| Geometric mean  | (ref)                                                               | 1.03x faster                                                          |

All benchmarks:
===============

| Benchmark                  | bm-20221024-darwin-arm64-python-deaf509e8fc6e0363bd6-3.11.0-deaf509 | bm-20220405-darwin-arm64-python-2e49bd06c5ffab7d1540-3.11.0a7-2e49bd0 |
|----------------------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| regex_effbot               | 2.45 ms                                                             | 2.07 ms: 1.18x faster                                                 |
| mako                       | 8.25 ms                                                             | 7.05 ms: 1.17x faster                                                 |
| deepcopy_memo              | 28.7 us                                                             | 24.8 us: 1.16x faster                                                 |
| pickle_pure_python         | 210 us                                                              | 190 us: 1.10x faster                                                  |
| float                      | 55.1 ms                                                             | 49.9 ms: 1.10x faster                                                 |
| deepcopy                   | 232 us                                                              | 212 us: 1.09x faster                                                  |
| unpickle_pure_python       | 162 us                                                              | 149 us: 1.09x faster                                                  |
| sqlite_synth               | 1.36 us                                                             | 1.26 us: 1.07x faster                                                 |
| deepcopy_reduce            | 1.96 us                                                             | 1.83 us: 1.07x faster                                                 |
| gc_traversal               | 2.53 ms                                                             | 2.38 ms: 1.06x faster                                                 |
| mdp                        | 1.84 sec                                                            | 1.76 sec: 1.05x faster                                                |
| logging_format             | 3.73 us                                                             | 3.58 us: 1.04x faster                                                 |
| json_loads                 | 15.5 us                                                             | 14.9 us: 1.04x faster                                                 |
| sympy_sum                  | 80.8 ms                                                             | 78.2 ms: 1.03x faster                                                 |
| genshi_text                | 14.5 ms                                                             | 14.0 ms: 1.03x faster                                                 |
| html5lib                   | 33.3 ms                                                             | 32.3 ms: 1.03x faster                                                 |
| logging_simple             | 3.45 us                                                             | 3.35 us: 1.03x faster                                                 |
| scimark_monte_carlo        | 45.7 ms                                                             | 44.6 ms: 1.03x faster                                                 |
| docutils                   | 1.43 sec                                                            | 1.40 sec: 1.02x faster                                                |
| python_startup_no_site     | 9.37 ms                                                             | 9.19 ms: 1.02x faster                                                 |
| meteor_contest             | 75.3 ms                                                             | 73.9 ms: 1.02x faster                                                 |
| nbody                      | 68.5 ms                                                             | 67.4 ms: 1.02x faster                                                 |
| python_startup             | 11.5 ms                                                             | 11.4 ms: 1.01x faster                                                 |
| create_gc_cycles           | 714 us                                                              | 706 us: 1.01x faster                                                  |
| async_generators           | 191 ms                                                              | 189 ms: 1.01x faster                                                  |
| dulwich_log                | 29.2 ms                                                             | 28.9 ms: 1.01x faster                                                 |
| json                       | 2.77 ms                                                             | 2.75 ms: 1.01x faster                                                 |
| sympy_expand               | 236 ms                                                              | 234 ms: 1.01x faster                                                  |
| xml_etree_parse            | 97.6 ms                                                             | 97.0 ms: 1.01x faster                                                 |
| sympy_str                  | 144 ms                                                              | 144 ms: 1.01x faster                                                  |
| pickle_list                | 2.68 us                                                             | 2.66 us: 1.00x faster                                                 |
| unpickle                   | 8.35 us                                                             | 8.31 us: 1.00x faster                                                 |
| telco                      | 3.17 ms                                                             | 3.15 ms: 1.00x faster                                                 |
| sqlalchemy_imperative      | 7.33 ms                                                             | 7.31 ms: 1.00x faster                                                 |
| xml_etree_generate         | 47.1 ms                                                             | 47.0 ms: 1.00x faster                                                 |
| pidigits                   | 280 ms                                                              | 280 ms: 1.00x slower                                                  |
| regex_compile              | 73.5 ms                                                             | 73.7 ms: 1.00x slower                                                 |
| typing_runtime_protocols   | 322 us                                                              | 323 us: 1.00x slower                                                  |
| scimark_fft                | 186 ms                                                              | 187 ms: 1.00x slower                                                  |
| asyncio_tcp_ssl            | 1.43 sec                                                            | 1.43 sec: 1.00x slower                                                |
| sqlalchemy_declarative     | 60.4 ms                                                             | 60.7 ms: 1.00x slower                                                 |
| raytrace                   | 205 ms                                                              | 207 ms: 1.01x slower                                                  |
| pyflate                    | 295 ms                                                              | 297 ms: 1.01x slower                                                  |
| chaos                      | 48.2 ms                                                             | 48.7 ms: 1.01x slower                                                 |
| flaskblogging              | 2.37 ms                                                             | 2.39 ms: 1.01x slower                                                 |
| mypy2                      | 187 ms                                                              | 190 ms: 1.01x slower                                                  |
| xml_etree_process          | 34.1 ms                                                             | 34.6 ms: 1.01x slower                                                 |
| scimark_sparse_mat_mult    | 3.00 ms                                                             | 3.04 ms: 1.01x slower                                                 |
| 2to3                       | 154 ms                                                              | 156 ms: 1.01x slower                                                  |
| unpickle_list              | 2.76 us                                                             | 2.80 us: 1.02x slower                                                 |
| pprint_pformat             | 986 ms                                                              | 1.00 sec: 1.02x slower                                                |
| django_template            | 19.6 ms                                                             | 20.0 ms: 1.02x slower                                                 |
| richards                   | 30.7 ms                                                             | 31.3 ms: 1.02x slower                                                 |
| spectral_norm              | 69.4 ms                                                             | 70.9 ms: 1.02x slower                                                 |
| go                         | 102 ms                                                              | 105 ms: 1.03x slower                                                  |
| pprint_safe_repr           | 480 ms                                                              | 492 ms: 1.03x slower                                                  |
| pickle_dict                | 17.0 us                                                             | 17.4 us: 1.03x slower                                                 |
| chameleon                  | 4.21 ms                                                             | 4.32 ms: 1.03x slower                                                 |
| nqueens                    | 54.3 ms                                                             | 55.8 ms: 1.03x slower                                                 |
| fannkuch                   | 247 ms                                                              | 254 ms: 1.03x slower                                                  |
| tomli_loads                | 1.32 sec                                                            | 1.36 sec: 1.03x slower                                                |
| richards_super             | 36.7 ms                                                             | 37.9 ms: 1.03x slower                                                 |
| async_tree_io_tg           | 723 ms                                                              | 748 ms: 1.04x slower                                                  |
| sqlglot_normalize          | 160 ms                                                              | 166 ms: 1.04x slower                                                  |
| generators                 | 29.0 ms                                                             | 30.1 ms: 1.04x slower                                                 |
| sqlglot_optimize           | 29.6 ms                                                             | 30.7 ms: 1.04x slower                                                 |
| pycparser                  | 658 ms                                                              | 684 ms: 1.04x slower                                                  |
| bench_thread_pool          | 467 us                                                              | 487 us: 1.04x slower                                                  |
| unpack_sequence            | 32.3 ns                                                             | 33.7 ns: 1.05x slower                                                 |
| scimark_lu                 | 67.9 ms                                                             | 71.2 ms: 1.05x slower                                                 |
| genshi_xml                 | 28.3 ms                                                             | 29.7 ms: 1.05x slower                                                 |
| hexiom                     | 4.55 ms                                                             | 4.85 ms: 1.07x slower                                                 |
| logging_silent             | 64.3 ns                                                             | 70.1 ns: 1.09x slower                                                 |
| coroutines                 | 16.4 ms                                                             | 17.9 ms: 1.09x slower                                                 |
| scimark_sor                | 74.4 ms                                                             | 82.8 ms: 1.11x slower                                                 |
| crypto_pyaes               | 47.9 ms                                                             | 53.4 ms: 1.11x slower                                                 |
| async_tree_cpu_io_mixed_tg | 548 ms                                                              | 611 ms: 1.12x slower                                                  |
| comprehensions             | 14.6 us                                                             | 16.3 us: 1.12x slower                                                 |
| regex_dna                  | 149 ms                                                              | 175 ms: 1.17x slower                                                  |
| async_tree_none_tg         | 277 ms                                                              | 338 ms: 1.22x slower                                                  |
| async_tree_memoization_tg  | 351 ms                                                              | 436 ms: 1.24x slower                                                  |
| sqlglot_transpile          | 1.04 ms                                                             | 1.30 ms: 1.25x slower                                                 |
| regex_v8                   | 15.4 ms                                                             | 19.3 ms: 1.25x slower                                                 |
| sqlglot_parse              | 874 us                                                              | 1.15 ms: 1.31x slower                                                 |
| coverage                   | 41.4 ms                                                             | 392 ms: 9.46x slower                                                  |
| Geometric mean             | (ref)                                                               | 1.03x slower                                                          |

Benchmark hidden because not significant (18): bench_mp_pool, pylint, aiohttp, tornado_http, sympy_integrate, xml_etree_iterparse, asyncio_websockets, asyncio_tcp, json_dumps, thrift, async_tree_none, pathlib, deltablue, async_tree_cpu_io_mixed, async_tree_io, pickle, gunicorn, async_tree_memoization
Ignored benchmarks (1) of results/bm-20221024-3.11.0-deaf509/bm-20221024-darwin-arm64-python-deaf509e8fc6e0363bd6-3.11.0-deaf509.json: dask


# HPT report

- Reliability score: 99.81% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
