
# Results vs. base

- fork: faster-cpython
- ref: no_deep_freeze_3
- machine: windows-amd64
- commit hash: 0bed3bc
- commit date: 2023-08-28
- overall geometric mean: 1.00x slower
- HPT reliability: 98.20%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20230830-pythonperf1-amd64-python-2928e5dc6512e4206c61-3.13.0a0-2928e5d | bm-20230828-pythonperf1-amd64-faster%2dcpython-no_deep_freeze_3-3.13.0a0-0bed3bc |
|----------------|:--------------------------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| docutils       | 1.63 sec                                                                   | 1.60 sec: 1.02x faster                                                           |
| Geometric mean | (ref)                                                                      | 1.01x faster                                                                     |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20230830-pythonperf1-amd64-python-2928e5dc6512e4206c61-3.13.0a0-2928e5d | bm-20230828-pythonperf1-amd64-faster%2dcpython-no_deep_freeze_3-3.13.0a0-0bed3bc |
|----------------|:--------------------------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| nbody          | 76.2 ms                                                                    | 75.4 ms: 1.01x faster                                                            |
| float          | 55.3 ms                                                                    | 54.9 ms: 1.01x faster                                                            |
| Geometric mean | (ref)                                                                      | 1.01x faster                                                                     |

Benchmark hidden because not significant (1): pidigits

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20230830-pythonperf1-amd64-python-2928e5dc6512e4206c61-3.13.0a0-2928e5d | bm-20230828-pythonperf1-amd64-faster%2dcpython-no_deep_freeze_3-3.13.0a0-0bed3bc |
|----------------|:--------------------------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| regex_dna      | 119 ms                                                                     | 118 ms: 1.00x faster                                                             |
| regex_v8       | 14.5 ms                                                                    | 14.6 ms: 1.01x slower                                                            |
| Geometric mean | (ref)                                                                      | 1.00x slower                                                                     |

Benchmark hidden because not significant (2): regex_compile, regex_effbot

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20230830-pythonperf1-amd64-python-2928e5dc6512e4206c61-3.13.0a0-2928e5d | bm-20230828-pythonperf1-amd64-faster%2dcpython-no_deep_freeze_3-3.13.0a0-0bed3bc |
|----------------------|:--------------------------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| pickle_list          | 2.85 us                                                                    | 2.80 us: 1.02x faster                                                            |
| pickle_pure_python   | 198 us                                                                     | 195 us: 1.02x faster                                                             |
| json_dumps           | 5.79 ms                                                                    | 5.72 ms: 1.01x faster                                                            |
| xml_etree_parse      | 92.1 ms                                                                    | 91.4 ms: 1.01x faster                                                            |
| unpickle             | 8.17 us                                                                    | 8.12 us: 1.01x faster                                                            |
| json_loads           | 13.6 us                                                                    | 13.6 us: 1.01x faster                                                            |
| xml_etree_iterparse  | 63.9 ms                                                                    | 64.6 ms: 1.01x slower                                                            |
| unpickle_pure_python | 139 us                                                                     | 141 us: 1.01x slower                                                             |
| pickle               | 7.24 us                                                                    | 7.34 us: 1.01x slower                                                            |
| xml_etree_generate   | 56.0 ms                                                                    | 56.8 ms: 1.01x slower                                                            |
| unpickle_list        | 2.73 us                                                                    | 2.93 us: 1.07x slower                                                            |
| Geometric mean       | (ref)                                                                      | 1.00x slower                                                                     |

Benchmark hidden because not significant (3): xml_etree_process, pickle_dict, tomli_loads

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20230830-pythonperf1-amd64-python-2928e5dc6512e4206c61-3.13.0a0-2928e5d | bm-20230828-pythonperf1-amd64-faster%2dcpython-no_deep_freeze_3-3.13.0a0-0bed3bc |
|------------------------|:--------------------------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| python_startup_no_site | 16.4 ms                                                                    | 16.2 ms: 1.01x faster                                                            |
| python_startup         | 19.3 ms                                                                    | 19.8 ms: 1.02x slower                                                            |
| Geometric mean         | (ref)                                                                      | 1.00x slower                                                                     |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20230830-pythonperf1-amd64-python-2928e5dc6512e4206c61-3.13.0a0-2928e5d | bm-20230828-pythonperf1-amd64-faster%2dcpython-no_deep_freeze_3-3.13.0a0-0bed3bc |
|-----------|:--------------------------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| mako      | 7.41 ms                                                                    | 7.57 ms: 1.02x slower                                                            |

All benchmarks:
===============

| Benchmark                | bm-20230830-pythonperf1-amd64-python-2928e5dc6512e4206c61-3.13.0a0-2928e5d | bm-20230828-pythonperf1-amd64-faster%2dcpython-no_deep_freeze_3-3.13.0a0-0bed3bc |
|--------------------------|:--------------------------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| unpack_sequence          | 41.9 ns                                                                    | 38.5 ns: 1.09x faster                                                            |
| coverage                 | 47.0 ms                                                                    | 45.7 ms: 1.03x faster                                                            |
| logging_format           | 6.85 us                                                                    | 6.71 us: 1.02x faster                                                            |
| coroutines               | 15.3 ms                                                                    | 15.0 ms: 1.02x faster                                                            |
| pickle_list              | 2.85 us                                                                    | 2.80 us: 1.02x faster                                                            |
| docutils                 | 1.63 sec                                                                   | 1.60 sec: 1.02x faster                                                           |
| pickle_pure_python       | 198 us                                                                     | 195 us: 1.02x faster                                                             |
| python_startup_no_site   | 16.4 ms                                                                    | 16.2 ms: 1.01x faster                                                            |
| typing_runtime_protocols | 95.6 us                                                                    | 94.4 us: 1.01x faster                                                            |
| chaos                    | 42.2 ms                                                                    | 41.7 ms: 1.01x faster                                                            |
| json_dumps               | 5.79 ms                                                                    | 5.72 ms: 1.01x faster                                                            |
| comprehensions           | 14.8 us                                                                    | 14.6 us: 1.01x faster                                                            |
| logging_simple           | 6.37 us                                                                    | 6.30 us: 1.01x faster                                                            |
| nbody                    | 76.2 ms                                                                    | 75.4 ms: 1.01x faster                                                            |
| sqlglot_optimize         | 35.2 ms                                                                    | 34.9 ms: 1.01x faster                                                            |
| float                    | 55.3 ms                                                                    | 54.9 ms: 1.01x faster                                                            |
| richards_super           | 32.8 ms                                                                    | 32.6 ms: 1.01x faster                                                            |
| xml_etree_parse          | 92.1 ms                                                                    | 91.4 ms: 1.01x faster                                                            |
| sqlglot_normalize        | 189 ms                                                                     | 188 ms: 1.01x faster                                                             |
| unpickle                 | 8.17 us                                                                    | 8.12 us: 1.01x faster                                                            |
| json_loads               | 13.6 us                                                                    | 13.6 us: 1.01x faster                                                            |
| richards                 | 29.2 ms                                                                    | 29.1 ms: 1.01x faster                                                            |
| regex_dna                | 119 ms                                                                     | 118 ms: 1.00x faster                                                             |
| fannkuch                 | 262 ms                                                                     | 261 ms: 1.00x faster                                                             |
| meteor_contest           | 73.3 ms                                                                    | 73.2 ms: 1.00x faster                                                            |
| pyflate                  | 306 ms                                                                     | 307 ms: 1.00x slower                                                             |
| go                       | 92.4 ms                                                                    | 92.9 ms: 1.01x slower                                                            |
| logging_silent           | 63.7 ns                                                                    | 64.0 ns: 1.01x slower                                                            |
| sqlglot_transpile        | 1.04 ms                                                                    | 1.04 ms: 1.01x slower                                                            |
| regex_v8                 | 14.5 ms                                                                    | 14.6 ms: 1.01x slower                                                            |
| mypy2                    | 213 ms                                                                     | 214 ms: 1.01x slower                                                             |
| bench_mp_pool            | 66.9 ms                                                                    | 67.4 ms: 1.01x slower                                                            |
| scimark_fft              | 183 ms                                                                     | 185 ms: 1.01x slower                                                             |
| telco                    | 4.61 ms                                                                    | 4.65 ms: 1.01x slower                                                            |
| hexiom                   | 4.26 ms                                                                    | 4.30 ms: 1.01x slower                                                            |
| xml_etree_iterparse      | 63.9 ms                                                                    | 64.6 ms: 1.01x slower                                                            |
| deltablue                | 2.22 ms                                                                    | 2.24 ms: 1.01x slower                                                            |
| sqlite_synth             | 1.75 us                                                                    | 1.76 us: 1.01x slower                                                            |
| gc_traversal             | 1.48 ms                                                                    | 1.49 ms: 1.01x slower                                                            |
| unpickle_pure_python     | 139 us                                                                     | 141 us: 1.01x slower                                                             |
| deepcopy                 | 238 us                                                                     | 241 us: 1.01x slower                                                             |
| pickle                   | 7.24 us                                                                    | 7.34 us: 1.01x slower                                                            |
| async_generators         | 238 ms                                                                     | 241 ms: 1.01x slower                                                             |
| xml_etree_generate       | 56.0 ms                                                                    | 56.8 ms: 1.01x slower                                                            |
| dulwich_log              | 44.4 ms                                                                    | 45.1 ms: 1.02x slower                                                            |
| mako                     | 7.41 ms                                                                    | 7.57 ms: 1.02x slower                                                            |
| deepcopy_memo            | 24.5 us                                                                    | 25.0 us: 1.02x slower                                                            |
| pprint_pformat           | 1.07 sec                                                                   | 1.10 sec: 1.02x slower                                                           |
| spectral_norm            | 65.2 ms                                                                    | 66.7 ms: 1.02x slower                                                            |
| python_startup           | 19.3 ms                                                                    | 19.8 ms: 1.02x slower                                                            |
| pprint_safe_repr         | 524 ms                                                                     | 537 ms: 1.03x slower                                                             |
| scimark_sor              | 82.9 ms                                                                    | 85.2 ms: 1.03x slower                                                            |
| crypto_pyaes             | 44.5 ms                                                                    | 46.0 ms: 1.03x slower                                                            |
| scimark_monte_carlo      | 43.3 ms                                                                    | 45.1 ms: 1.04x slower                                                            |
| unpickle_list            | 2.73 us                                                                    | 2.93 us: 1.07x slower                                                            |
| json                     | 2.87 ms                                                                    | 3.10 ms: 1.08x slower                                                            |
| mdp                      | 1.39 sec                                                                   | 1.51 sec: 1.09x slower                                                           |
| Geometric mean           | (ref)                                                                      | 1.00x slower                                                                     |

Benchmark hidden because not significant (25): asyncio_tcp_ssl, nqueens, regex_compile, xml_etree_process, pickle_dict, generators, bench_thread_pool, pidigits, sqlglot_parse, scimark_sparse_mat_mult, create_gc_cycles, regex_effbot, tomli_loads, tornado_http, async_tree_io, async_tree_none, scimark_lu, raytrace, pathlib, deepcopy_reduce, dask, async_tree_memoization, async_tree_cpu_io_mixed, pycparser, asyncio_tcp


# HPT report

- Reliability score: 98.20% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
