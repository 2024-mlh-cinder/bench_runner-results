
# Results vs. base

- fork: brandtbucher
- ref: break_up_float_reuse
- machine: linux-x86_64
- commit hash: 2dde229
- commit date: 2023-10-19
- overall geometric mean: 1.01x slower
- HPT reliability: 99.95%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231016-linux-x86_64-python-f07ca27709855d4637b4-3.13.0a1+-f07ca27 | bm-20231019-linux-x86_64-brandtbucher-break_up_float_reuse-3.13.0a1+-2dde229 |
|----------------|:----------------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| docutils       | 2.67 sec                                                               | 2.65 sec: 1.01x faster                                                       |
| tornado_http   | 96.3 ms                                                                | 95.7 ms: 1.01x faster                                                        |
| Geometric mean | (ref)                                                                  | 1.01x faster                                                                 |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231016-linux-x86_64-python-f07ca27709855d4637b4-3.13.0a1+-f07ca27 | bm-20231019-linux-x86_64-brandtbucher-break_up_float_reuse-3.13.0a1+-2dde229 |
|----------------|:----------------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| pidigits       | 196 ms                                                                 | 188 ms: 1.04x faster                                                         |
| nbody          | 94.4 ms                                                                | 95.9 ms: 1.02x slower                                                        |
| float          | 80.6 ms                                                                | 82.0 ms: 1.02x slower                                                        |
| Geometric mean | (ref)                                                                  | 1.00x faster                                                                 |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231016-linux-x86_64-python-f07ca27709855d4637b4-3.13.0a1+-f07ca27 | bm-20231019-linux-x86_64-brandtbucher-break_up_float_reuse-3.13.0a1+-2dde229 |
|----------------|:----------------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| regex_v8       | 25.5 ms                                                                | 24.3 ms: 1.05x faster                                                        |
| regex_dna      | 218 ms                                                                 | 218 ms: 1.00x faster                                                         |
| regex_compile  | 138 ms                                                                 | 138 ms: 1.01x slower                                                         |
| Geometric mean | (ref)                                                                  | 1.01x faster                                                                 |

Benchmark hidden because not significant (1): regex_effbot

Benchmarks with tag 'serialize':
================================

| Benchmark          | bm-20231016-linux-x86_64-python-f07ca27709855d4637b4-3.13.0a1+-f07ca27 | bm-20231019-linux-x86_64-brandtbucher-break_up_float_reuse-3.13.0a1+-2dde229 |
|--------------------|:----------------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| unpickle           | 15.0 us                                                                | 14.5 us: 1.04x faster                                                        |
| json_dumps         | 10.5 ms                                                                | 10.4 ms: 1.01x faster                                                        |
| xml_etree_generate | 87.0 ms                                                                | 86.5 ms: 1.01x faster                                                        |
| tomli_loads        | 2.16 sec                                                               | 2.18 sec: 1.01x slower                                                       |
| pickle_list        | 5.13 us                                                                | 5.22 us: 1.02x slower                                                        |
| pickle_pure_python | 305 us                                                                 | 311 us: 1.02x slower                                                         |
| unpickle_list      | 5.10 us                                                                | 5.25 us: 1.03x slower                                                        |
| pickle_dict        | 33.6 us                                                                | 34.9 us: 1.04x slower                                                        |
| Geometric mean     | (ref)                                                                  | 1.00x slower                                                                 |

Benchmark hidden because not significant (6): xml_etree_process, json_loads, pickle, xml_etree_iterparse, unpickle_pure_python, xml_etree_parse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231016-linux-x86_64-python-f07ca27709855d4637b4-3.13.0a1+-f07ca27 | bm-20231019-linux-x86_64-brandtbucher-break_up_float_reuse-3.13.0a1+-2dde229 |
|------------------------|:----------------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| python_startup_no_site | 6.85 ms                                                                | 6.86 ms: 1.00x slower                                                        |
| python_startup         | 10.1 ms                                                                | 10.1 ms: 1.00x slower                                                        |
| Geometric mean         | (ref)                                                                  | 1.00x slower                                                                 |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231016-linux-x86_64-python-f07ca27709855d4637b4-3.13.0a1+-f07ca27 | bm-20231019-linux-x86_64-brandtbucher-break_up_float_reuse-3.13.0a1+-2dde229 |
|-----------|:----------------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| mako      | 11.7 ms                                                                | 11.8 ms: 1.01x slower                                                        |

All benchmarks:
===============

| Benchmark                | bm-20231016-linux-x86_64-python-f07ca27709855d4637b4-3.13.0a1+-f07ca27 | bm-20231019-linux-x86_64-brandtbucher-break_up_float_reuse-3.13.0a1+-2dde229 |
|--------------------------|:----------------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| regex_v8                 | 25.5 ms                                                                | 24.3 ms: 1.05x faster                                                        |
| pidigits                 | 196 ms                                                                 | 188 ms: 1.04x faster                                                         |
| unpickle                 | 15.0 us                                                                | 14.5 us: 1.04x faster                                                        |
| spectral_norm            | 118 ms                                                                 | 114 ms: 1.03x faster                                                         |
| scimark_sparse_mat_mult  | 4.93 ms                                                                | 4.82 ms: 1.02x faster                                                        |
| json_dumps               | 10.5 ms                                                                | 10.4 ms: 1.01x faster                                                        |
| scimark_fft              | 381 ms                                                                 | 376 ms: 1.01x faster                                                         |
| logging_silent           | 108 ns                                                                 | 107 ns: 1.01x faster                                                         |
| deepcopy_reduce          | 3.20 us                                                                | 3.16 us: 1.01x faster                                                        |
| asyncio_tcp              | 484 ms                                                                 | 481 ms: 1.01x faster                                                         |
| tornado_http             | 96.3 ms                                                                | 95.7 ms: 1.01x faster                                                        |
| xml_etree_generate       | 87.0 ms                                                                | 86.5 ms: 1.01x faster                                                        |
| docutils                 | 2.67 sec                                                               | 2.65 sec: 1.01x faster                                                       |
| chaos                    | 62.4 ms                                                                | 62.1 ms: 1.00x faster                                                        |
| regex_dna                | 218 ms                                                                 | 218 ms: 1.00x faster                                                         |
| python_startup_no_site   | 6.85 ms                                                                | 6.86 ms: 1.00x slower                                                        |
| asyncio_tcp_ssl          | 1.78 sec                                                               | 1.79 sec: 1.00x slower                                                       |
| python_startup           | 10.1 ms                                                                | 10.1 ms: 1.00x slower                                                        |
| bench_thread_pool        | 812 us                                                                 | 815 us: 1.00x slower                                                         |
| dulwich_log              | 66.7 ms                                                                | 67.0 ms: 1.00x slower                                                        |
| fannkuch                 | 418 ms                                                                 | 420 ms: 1.00x slower                                                         |
| pprint_pformat           | 1.52 sec                                                               | 1.52 sec: 1.00x slower                                                       |
| regex_compile            | 138 ms                                                                 | 138 ms: 1.01x slower                                                         |
| pprint_safe_repr         | 744 ms                                                                 | 748 ms: 1.01x slower                                                         |
| tomli_loads              | 2.16 sec                                                               | 2.18 sec: 1.01x slower                                                       |
| comprehensions           | 20.7 us                                                                | 20.8 us: 1.01x slower                                                        |
| generators               | 29.6 ms                                                                | 29.8 ms: 1.01x slower                                                        |
| typing_runtime_protocols | 152 us                                                                 | 153 us: 1.01x slower                                                         |
| hexiom                   | 6.21 ms                                                                | 6.26 ms: 1.01x slower                                                        |
| deltablue                | 3.34 ms                                                                | 3.37 ms: 1.01x slower                                                        |
| deepcopy                 | 352 us                                                                 | 355 us: 1.01x slower                                                         |
| create_gc_cycles         | 1.45 ms                                                                | 1.46 ms: 1.01x slower                                                        |
| sqlite_synth             | 2.84 us                                                                | 2.87 us: 1.01x slower                                                        |
| mako                     | 11.7 ms                                                                | 11.8 ms: 1.01x slower                                                        |
| logging_simple           | 5.89 us                                                                | 5.96 us: 1.01x slower                                                        |
| deepcopy_memo            | 38.7 us                                                                | 39.2 us: 1.01x slower                                                        |
| richards                 | 48.2 ms                                                                | 48.8 ms: 1.01x slower                                                        |
| logging_format           | 6.43 us                                                                | 6.53 us: 1.01x slower                                                        |
| raytrace                 | 275 ms                                                                 | 279 ms: 1.02x slower                                                         |
| nbody                    | 94.4 ms                                                                | 95.9 ms: 1.02x slower                                                        |
| pyflate                  | 468 ms                                                                 | 476 ms: 1.02x slower                                                         |
| pickle_list              | 5.13 us                                                                | 5.22 us: 1.02x slower                                                        |
| nqueens                  | 79.5 ms                                                                | 80.9 ms: 1.02x slower                                                        |
| pickle_pure_python       | 305 us                                                                 | 311 us: 1.02x slower                                                         |
| float                    | 80.6 ms                                                                | 82.0 ms: 1.02x slower                                                        |
| crypto_pyaes             | 72.4 ms                                                                | 73.8 ms: 1.02x slower                                                        |
| scimark_monte_carlo      | 69.2 ms                                                                | 70.7 ms: 1.02x slower                                                        |
| richards_super           | 54.1 ms                                                                | 55.5 ms: 1.03x slower                                                        |
| unpickle_list            | 5.10 us                                                                | 5.25 us: 1.03x slower                                                        |
| pycparser                | 1.17 sec                                                               | 1.22 sec: 1.04x slower                                                       |
| scimark_sor              | 127 ms                                                                 | 132 ms: 1.04x slower                                                         |
| pickle_dict              | 33.6 us                                                                | 34.9 us: 1.04x slower                                                        |
| coroutines               | 22.7 ms                                                                | 23.7 ms: 1.04x slower                                                        |
| mdp                      | 2.53 sec                                                               | 2.67 sec: 1.06x slower                                                       |
| gc_traversal             | 3.63 ms                                                                | 4.04 ms: 1.11x slower                                                        |
| unpack_sequence          | 47.1 ns                                                                | 58.1 ns: 1.23x slower                                                        |
| Geometric mean           | (ref)                                                                  | 1.01x slower                                                                 |

Benchmark hidden because not significant (25): async_tree_memoization, json, async_generators, sqlglot_parse, sqlglot_transpile, regex_effbot, scimark_lu, sqlglot_normalize, xml_etree_process, json_loads, meteor_contest, bench_mp_pool, sqlglot_optimize, pathlib, pickle, go, async_tree_io, xml_etree_iterparse, coverage, unpickle_pure_python, telco, mypy2, async_tree_cpu_io_mixed, xml_etree_parse, async_tree_none


# HPT report

- Reliability score: 99.95% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
