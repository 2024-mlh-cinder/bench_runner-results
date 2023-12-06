
# Results vs. base

- fork: faster-cpython
- ref: no_deep_freeze_3
- machine: linux-x86_64
- commit hash: 1ad9bed
- commit date: 2023-08-27
- overall geometric mean: 1.01x faster
- HPT reliability: 95.66%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20230830-linux-x86_64-python-2928e5dc6512e4206c61-3.13.0a0-2928e5d | bm-20230827-linux-x86_64-faster%2dcpython-no_deep_freeze_3-3.13.0a0-1ad9bed |
|----------------|:---------------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| docutils       | 2.62 sec                                                              | 2.61 sec: 1.00x faster                                                      |
| Geometric mean | (ref)                                                                 | 1.00x faster                                                                |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20230830-linux-x86_64-python-2928e5dc6512e4206c61-3.13.0a0-2928e5d | bm-20230827-linux-x86_64-faster%2dcpython-no_deep_freeze_3-3.13.0a0-1ad9bed |
|----------------|:---------------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| pidigits       | 189 ms                                                                | 189 ms: 1.00x slower                                                        |
| float          | 79.0 ms                                                               | 80.4 ms: 1.02x slower                                                       |
| Geometric mean | (ref)                                                                 | 1.00x slower                                                                |

Benchmark hidden because not significant (1): nbody

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20230830-linux-x86_64-python-2928e5dc6512e4206c61-3.13.0a0-2928e5d | bm-20230827-linux-x86_64-faster%2dcpython-no_deep_freeze_3-3.13.0a0-1ad9bed |
|----------------|:---------------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_v8       | 25.2 ms                                                               | 23.1 ms: 1.09x faster                                                       |
| regex_effbot   | 3.72 ms                                                               | 3.45 ms: 1.08x faster                                                       |
| regex_dna      | 214 ms                                                                | 204 ms: 1.05x faster                                                        |
| regex_compile  | 134 ms                                                                | 135 ms: 1.01x slower                                                        |
| Geometric mean | (ref)                                                                 | 1.05x faster                                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20230830-linux-x86_64-python-2928e5dc6512e4206c61-3.13.0a0-2928e5d | bm-20230827-linux-x86_64-faster%2dcpython-no_deep_freeze_3-3.13.0a0-1ad9bed |
|----------------------|:---------------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| pickle_dict          | 32.1 us                                                               | 30.4 us: 1.06x faster                                                       |
| unpickle_list        | 5.18 us                                                               | 5.04 us: 1.03x faster                                                       |
| json_dumps           | 10.0 ms                                                               | 9.75 ms: 1.03x faster                                                       |
| json_loads           | 25.6 us                                                               | 25.2 us: 1.02x faster                                                       |
| pickle               | 10.3 us                                                               | 10.1 us: 1.01x faster                                                       |
| xml_etree_parse      | 153 ms                                                                | 151 ms: 1.01x faster                                                        |
| tomli_loads          | 2.13 sec                                                              | 2.11 sec: 1.01x faster                                                      |
| pickle_pure_python   | 303 us                                                                | 301 us: 1.01x faster                                                        |
| unpickle_pure_python | 213 us                                                                | 212 us: 1.00x faster                                                        |
| Geometric mean       | (ref)                                                                 | 1.01x faster                                                                |

Benchmark hidden because not significant (5): xml_etree_iterparse, unpickle, pickle_list, xml_etree_process, xml_etree_generate

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20230830-linux-x86_64-python-2928e5dc6512e4206c61-3.13.0a0-2928e5d | bm-20230827-linux-x86_64-faster%2dcpython-no_deep_freeze_3-3.13.0a0-1ad9bed |
|------------------------|:---------------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| python_startup_no_site | 7.00 ms                                                               | 6.84 ms: 1.02x faster                                                       |
| python_startup         | 9.56 ms                                                               | 10.1 ms: 1.05x slower                                                       |
| Geometric mean         | (ref)                                                                 | 1.01x slower                                                                |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20230830-linux-x86_64-python-2928e5dc6512e4206c61-3.13.0a0-2928e5d | bm-20230827-linux-x86_64-faster%2dcpython-no_deep_freeze_3-3.13.0a0-1ad9bed |
|-----------|:---------------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| mako      | 10.8 ms                                                               | 10.8 ms: 1.01x slower                                                       |

All benchmarks:
===============

| Benchmark                | bm-20230830-linux-x86_64-python-2928e5dc6512e4206c61-3.13.0a0-2928e5d | bm-20230827-linux-x86_64-faster%2dcpython-no_deep_freeze_3-3.13.0a0-1ad9bed |
|--------------------------|:---------------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_v8                 | 25.2 ms                                                               | 23.1 ms: 1.09x faster                                                       |
| gc_traversal             | 4.33 ms                                                               | 4.01 ms: 1.08x faster                                                       |
| regex_effbot             | 3.72 ms                                                               | 3.45 ms: 1.08x faster                                                       |
| unpack_sequence          | 43.5 ns                                                               | 40.5 ns: 1.07x faster                                                       |
| pickle_dict              | 32.1 us                                                               | 30.4 us: 1.06x faster                                                       |
| regex_dna                | 214 ms                                                                | 204 ms: 1.05x faster                                                        |
| deepcopy_reduce          | 3.19 us                                                               | 3.05 us: 1.04x faster                                                       |
| mdp                      | 2.64 sec                                                              | 2.55 sec: 1.04x faster                                                      |
| unpickle_list            | 5.18 us                                                               | 5.04 us: 1.03x faster                                                       |
| pprint_safe_repr         | 735 ms                                                                | 716 ms: 1.03x faster                                                        |
| json_dumps               | 10.0 ms                                                               | 9.75 ms: 1.03x faster                                                       |
| spectral_norm            | 108 ms                                                                | 106 ms: 1.03x faster                                                        |
| python_startup_no_site   | 7.00 ms                                                               | 6.84 ms: 1.02x faster                                                       |
| pprint_pformat           | 1.50 sec                                                              | 1.46 sec: 1.02x faster                                                      |
| meteor_contest           | 106 ms                                                                | 104 ms: 1.02x faster                                                        |
| deepcopy                 | 349 us                                                                | 343 us: 1.02x faster                                                        |
| sqlglot_normalize        | 106 ms                                                                | 104 ms: 1.02x faster                                                        |
| scimark_monte_carlo      | 67.9 ms                                                               | 66.7 ms: 1.02x faster                                                       |
| json_loads               | 25.6 us                                                               | 25.2 us: 1.02x faster                                                       |
| pickle                   | 10.3 us                                                               | 10.1 us: 1.01x faster                                                       |
| sqlite_synth             | 2.77 us                                                               | 2.74 us: 1.01x faster                                                       |
| logging_format           | 6.50 us                                                               | 6.43 us: 1.01x faster                                                       |
| sqlglot_optimize         | 52.9 ms                                                               | 52.3 ms: 1.01x faster                                                       |
| xml_etree_parse          | 153 ms                                                                | 151 ms: 1.01x faster                                                        |
| logging_simple           | 5.92 us                                                               | 5.86 us: 1.01x faster                                                       |
| dulwich_log              | 66.6 ms                                                               | 66.0 ms: 1.01x faster                                                       |
| tomli_loads              | 2.13 sec                                                              | 2.11 sec: 1.01x faster                                                      |
| raytrace                 | 278 ms                                                                | 275 ms: 1.01x faster                                                        |
| pickle_pure_python       | 303 us                                                                | 301 us: 1.01x faster                                                        |
| scimark_lu               | 110 ms                                                                | 109 ms: 1.01x faster                                                        |
| chaos                    | 60.7 ms                                                               | 60.3 ms: 1.01x faster                                                       |
| async_generators         | 449 ms                                                                | 446 ms: 1.01x faster                                                        |
| docutils                 | 2.62 sec                                                              | 2.61 sec: 1.00x faster                                                      |
| go                       | 142 ms                                                                | 141 ms: 1.00x faster                                                        |
| unpickle_pure_python     | 213 us                                                                | 212 us: 1.00x faster                                                        |
| pidigits                 | 189 ms                                                                | 189 ms: 1.00x slower                                                        |
| pyflate                  | 448 ms                                                                | 449 ms: 1.00x slower                                                        |
| comprehensions           | 20.5 us                                                               | 20.6 us: 1.00x slower                                                       |
| mako                     | 10.8 ms                                                               | 10.8 ms: 1.01x slower                                                       |
| logging_silent           | 102 ns                                                                | 102 ns: 1.01x slower                                                        |
| regex_compile            | 134 ms                                                                | 135 ms: 1.01x slower                                                        |
| scimark_sor              | 122 ms                                                                | 123 ms: 1.01x slower                                                        |
| deltablue                | 3.29 ms                                                               | 3.33 ms: 1.01x slower                                                       |
| json                     | 4.78 ms                                                               | 4.85 ms: 1.01x slower                                                       |
| scimark_sparse_mat_mult  | 4.61 ms                                                               | 4.67 ms: 1.01x slower                                                       |
| fannkuch                 | 385 ms                                                                | 391 ms: 1.01x slower                                                        |
| float                    | 79.0 ms                                                               | 80.4 ms: 1.02x slower                                                       |
| pycparser                | 1.16 sec                                                              | 1.18 sec: 1.02x slower                                                      |
| typing_runtime_protocols | 142 us                                                                | 144 us: 1.02x slower                                                        |
| crypto_pyaes             | 68.4 ms                                                               | 69.8 ms: 1.02x slower                                                       |
| create_gc_cycles         | 1.50 ms                                                               | 1.53 ms: 1.03x slower                                                       |
| python_startup           | 9.56 ms                                                               | 10.1 ms: 1.05x slower                                                       |
| coroutines               | 21.8 ms                                                               | 24.0 ms: 1.10x slower                                                       |
| Geometric mean           | (ref)                                                                 | 1.01x faster                                                                |

Benchmark hidden because not significant (29): async_tree_memoization, async_tree_none, async_tree_cpu_io_mixed, nbody, dask, pathlib, xml_etree_iterparse, unpickle, deepcopy_memo, pickle_list, tornado_http, sqlglot_transpile, nqueens, async_tree_io, xml_etree_process, asyncio_tcp_ssl, bench_thread_pool, mypy2, bench_mp_pool, hexiom, asyncio_tcp, sqlglot_parse, coverage, richards_super, richards, generators, scimark_fft, xml_etree_generate, telco


# HPT report

- Reliability score: 95.66% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
