
# Results vs. base

- fork: faster-cpython
- ref: no_deep_freeze_3
- machine: darwin-arm64
- commit hash: 0bed3bc
- commit date: 2023-08-28
- overall geometric mean: 1.01x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20230830-darwin-arm64-python-2928e5dc6512e4206c61-3.13.0a0-2928e5d | bm-20230828-darwin-arm64-faster%2dcpython-no_deep_freeze_3-3.13.0a0-0bed3bc |
|----------------|:---------------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| docutils       | 1.51 sec                                                              | 1.52 sec: 1.00x slower                                                      |
| Geometric mean | (ref)                                                                 | 1.01x slower                                                                |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20230830-darwin-arm64-python-2928e5dc6512e4206c61-3.13.0a0-2928e5d | bm-20230828-darwin-arm64-faster%2dcpython-no_deep_freeze_3-3.13.0a0-0bed3bc |
|----------------|:---------------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| nbody          | 72.3 ms                                                               | 72.0 ms: 1.00x faster                                                       |
| pidigits       | 282 ms                                                                | 282 ms: 1.00x slower                                                        |
| Geometric mean | (ref)                                                                 | 1.00x faster                                                                |

Benchmark hidden because not significant (1): float

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20230830-darwin-arm64-python-2928e5dc6512e4206c61-3.13.0a0-2928e5d | bm-20230828-darwin-arm64-faster%2dcpython-no_deep_freeze_3-3.13.0a0-0bed3bc |
|----------------|:---------------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_compile  | 79.4 ms                                                               | 79.1 ms: 1.00x faster                                                       |
| regex_v8       | 16.9 ms                                                               | 17.0 ms: 1.01x slower                                                       |
| Geometric mean | (ref)                                                                 | 1.00x slower                                                                |

Benchmark hidden because not significant (2): regex_effbot, regex_dna

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20230830-darwin-arm64-python-2928e5dc6512e4206c61-3.13.0a0-2928e5d | bm-20230828-darwin-arm64-faster%2dcpython-no_deep_freeze_3-3.13.0a0-0bed3bc |
|----------------------|:---------------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| tomli_loads          | 1.57 sec                                                              | 1.55 sec: 1.01x faster                                                      |
| pickle_dict          | 18.0 us                                                               | 17.9 us: 1.00x faster                                                       |
| json_dumps           | 6.50 ms                                                               | 6.49 ms: 1.00x faster                                                       |
| unpickle_pure_python | 162 us                                                                | 162 us: 1.00x faster                                                        |
| pickle_pure_python   | 200 us                                                                | 200 us: 1.00x slower                                                        |
| pickle               | 7.38 us                                                               | 7.41 us: 1.00x slower                                                       |
| Geometric mean       | (ref)                                                                 | 1.00x faster                                                                |

Benchmark hidden because not significant (8): xml_etree_iterparse, xml_etree_parse, xml_etree_generate, xml_etree_process, unpickle, pickle_list, unpickle_list, json_loads

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20230830-darwin-arm64-python-2928e5dc6512e4206c61-3.13.0a0-2928e5d | bm-20230828-darwin-arm64-faster%2dcpython-no_deep_freeze_3-3.13.0a0-0bed3bc |
|------------------------|:---------------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| python_startup_no_site | 9.40 ms                                                               | 9.15 ms: 1.03x faster                                                       |
| python_startup         | 11.5 ms                                                               | 11.8 ms: 1.02x slower                                                       |
| Geometric mean         | (ref)                                                                 | 1.00x faster                                                                |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20230830-darwin-arm64-python-2928e5dc6512e4206c61-3.13.0a0-2928e5d | bm-20230828-darwin-arm64-faster%2dcpython-no_deep_freeze_3-3.13.0a0-0bed3bc |
|-----------|:---------------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| mako      | 7.51 ms                                                               | 7.43 ms: 1.01x faster                                                       |

All benchmarks:
===============

| Benchmark               | bm-20230830-darwin-arm64-python-2928e5dc6512e4206c61-3.13.0a0-2928e5d | bm-20230828-darwin-arm64-faster%2dcpython-no_deep_freeze_3-3.13.0a0-0bed3bc |
|-------------------------|:---------------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| mypy2                   | 260 ms                                                                | 193 ms: 1.35x faster                                                        |
| generators              | 28.9 ms                                                               | 26.2 ms: 1.10x faster                                                       |
| asyncio_tcp_ssl         | 1.35 sec                                                              | 1.27 sec: 1.06x faster                                                      |
| json                    | 3.16 ms                                                               | 3.01 ms: 1.05x faster                                                       |
| coroutines              | 19.7 ms                                                               | 18.8 ms: 1.05x faster                                                       |
| python_startup_no_site  | 9.40 ms                                                               | 9.15 ms: 1.03x faster                                                       |
| telco                   | 4.65 ms                                                               | 4.57 ms: 1.02x faster                                                       |
| bench_thread_pool       | 496 us                                                                | 490 us: 1.01x faster                                                        |
| logging_format          | 4.04 us                                                               | 3.99 us: 1.01x faster                                                       |
| mako                    | 7.51 ms                                                               | 7.43 ms: 1.01x faster                                                       |
| richards_super          | 39.1 ms                                                               | 38.7 ms: 1.01x faster                                                       |
| async_generators        | 312 ms                                                                | 309 ms: 1.01x faster                                                        |
| coverage                | 47.8 ms                                                               | 47.3 ms: 1.01x faster                                                       |
| sqlglot_normalize       | 193 ms                                                                | 191 ms: 1.01x faster                                                        |
| chaos                   | 42.2 ms                                                               | 41.9 ms: 1.01x faster                                                       |
| raytrace                | 191 ms                                                                | 189 ms: 1.01x faster                                                        |
| tomli_loads             | 1.57 sec                                                              | 1.55 sec: 1.01x faster                                                      |
| scimark_sparse_mat_mult | 3.11 ms                                                               | 3.09 ms: 1.01x faster                                                       |
| sqlglot_optimize        | 35.4 ms                                                               | 35.1 ms: 1.01x faster                                                       |
| pprint_safe_repr        | 515 ms                                                                | 512 ms: 1.01x faster                                                        |
| deepcopy_memo           | 25.2 us                                                               | 25.0 us: 1.01x faster                                                       |
| sqlglot_transpile       | 1.02 ms                                                               | 1.01 ms: 1.01x faster                                                       |
| sqlglot_parse           | 838 us                                                                | 832 us: 1.01x faster                                                        |
| nqueens                 | 59.6 ms                                                               | 59.2 ms: 1.01x faster                                                       |
| pyflate                 | 350 ms                                                                | 348 ms: 1.01x faster                                                        |
| pycparser               | 704 ms                                                                | 701 ms: 1.01x faster                                                        |
| scimark_fft             | 202 ms                                                                | 201 ms: 1.00x faster                                                        |
| pprint_pformat          | 1.05 sec                                                              | 1.04 sec: 1.00x faster                                                      |
| pickle_dict             | 18.0 us                                                               | 17.9 us: 1.00x faster                                                       |
| async_tree_io           | 707 ms                                                                | 704 ms: 1.00x faster                                                        |
| hexiom                  | 4.88 ms                                                               | 4.86 ms: 1.00x faster                                                       |
| deepcopy                | 232 us                                                                | 231 us: 1.00x faster                                                        |
| nbody                   | 72.3 ms                                                               | 72.0 ms: 1.00x faster                                                       |
| regex_compile           | 79.4 ms                                                               | 79.1 ms: 1.00x faster                                                       |
| scimark_monte_carlo     | 46.4 ms                                                               | 46.2 ms: 1.00x faster                                                       |
| fannkuch                | 288 ms                                                                | 287 ms: 1.00x faster                                                        |
| dulwich_log             | 31.0 ms                                                               | 30.9 ms: 1.00x faster                                                       |
| json_dumps              | 6.50 ms                                                               | 6.49 ms: 1.00x faster                                                       |
| richards                | 35.6 ms                                                               | 35.5 ms: 1.00x faster                                                       |
| scimark_sor             | 108 ms                                                                | 108 ms: 1.00x faster                                                        |
| crypto_pyaes            | 47.8 ms                                                               | 47.7 ms: 1.00x faster                                                       |
| comprehensions          | 14.9 us                                                               | 14.9 us: 1.00x faster                                                       |
| unpickle_pure_python    | 162 us                                                                | 162 us: 1.00x faster                                                        |
| pidigits                | 282 ms                                                                | 282 ms: 1.00x slower                                                        |
| docutils                | 1.51 sec                                                              | 1.52 sec: 1.00x slower                                                      |
| logging_simple          | 3.73 us                                                               | 3.74 us: 1.00x slower                                                       |
| gc_traversal            | 2.40 ms                                                               | 2.40 ms: 1.00x slower                                                       |
| pickle_pure_python      | 200 us                                                                | 200 us: 1.00x slower                                                        |
| meteor_contest          | 73.9 ms                                                               | 74.1 ms: 1.00x slower                                                       |
| pickle                  | 7.38 us                                                               | 7.41 us: 1.00x slower                                                       |
| regex_v8                | 16.9 ms                                                               | 17.0 ms: 1.01x slower                                                       |
| create_gc_cycles        | 700 us                                                                | 708 us: 1.01x slower                                                        |
| bench_mp_pool           | 45.9 ms                                                               | 46.4 ms: 1.01x slower                                                       |
| scimark_lu              | 75.3 ms                                                               | 76.2 ms: 1.01x slower                                                       |
| python_startup          | 11.5 ms                                                               | 11.8 ms: 1.02x slower                                                       |
| asyncio_tcp             | 410 ms                                                                | 439 ms: 1.07x slower                                                        |
| Geometric mean          | (ref)                                                                 | 1.01x faster                                                                |

Benchmark hidden because not significant (26): unpack_sequence, xml_etree_iterparse, xml_etree_parse, float, deepcopy_reduce, xml_etree_generate, mdp, async_tree_cpu_io_mixed, logging_silent, go, async_tree_memoization, regex_effbot, spectral_norm, xml_etree_process, unpickle, typing_runtime_protocols, dask, regex_dna, deltablue, pickle_list, pathlib, sqlite_synth, unpickle_list, json_loads, async_tree_none, tornado_http


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
