
# Results vs. base

- fork: mdboom
- ref: test_branch
- machine: linux-x86_64
- commit hash: 3ce7ef8
- commit date: 2023-11-14
- overall geometric mean: 1.00x slower
- HPT reliability: 91.54%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231114-linux-x86_64-python-4f04172c9287c507f142-3.13.0a1+-4f04172 | bm-20231114-linux-x86_64-mdboom-test_branch-3.13.0a1+-3ce7ef8 |
|----------------|:----------------------------------------------------------------------:|:-------------------------------------------------------------:|
| 2to3           | 293 ms                                                                 | 294 ms: 1.00x slower                                          |
| chameleon      | 7.41 ms                                                                | 7.48 ms: 1.01x slower                                         |
| docutils       | 2.71 sec                                                               | 2.74 sec: 1.01x slower                                        |
| Geometric mean | (ref)                                                                  | 1.01x slower                                                  |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20231114-linux-x86_64-python-4f04172c9287c507f142-3.13.0a1+-4f04172 | bm-20231114-linux-x86_64-mdboom-test_branch-3.13.0a1+-3ce7ef8 |
|-------------------------|:----------------------------------------------------------------------:|:-------------------------------------------------------------:|
| async_tree_io_tg        | 1.26 sec                                                               | 1.26 sec: 1.00x slower                                        |
| async_tree_cpu_io_mixed | 734 ms                                                                 | 742 ms: 1.01x slower                                          |
| Geometric mean          | (ref)                                                                  | 1.00x slower                                                  |

Benchmark hidden because not significant (6): async_tree_none, async_tree_memoization, async_tree_none_tg, async_tree_io, async_tree_memoization_tg, async_tree_cpu_io_mixed_tg

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231114-linux-x86_64-python-4f04172c9287c507f142-3.13.0a1+-4f04172 | bm-20231114-linux-x86_64-mdboom-test_branch-3.13.0a1+-3ce7ef8 |
|----------------|:----------------------------------------------------------------------:|:-------------------------------------------------------------:|
| pidigits       | 196 ms                                                                 | 188 ms: 1.04x faster                                          |
| float          | 101 ms                                                                 | 102 ms: 1.01x slower                                          |
| Geometric mean | (ref)                                                                  | 1.01x faster                                                  |

Benchmark hidden because not significant (1): nbody

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231114-linux-x86_64-python-4f04172c9287c507f142-3.13.0a1+-4f04172 | bm-20231114-linux-x86_64-mdboom-test_branch-3.13.0a1+-3ce7ef8 |
|----------------|:----------------------------------------------------------------------:|:-------------------------------------------------------------:|
| regex_dna      | 217 ms                                                                 | 213 ms: 1.02x faster                                          |
| regex_effbot   | 3.55 ms                                                                | 3.50 ms: 1.01x faster                                         |
| regex_compile  | 164 ms                                                                 | 166 ms: 1.01x slower                                          |
| regex_v8       | 24.4 ms                                                                | 24.8 ms: 1.02x slower                                         |
| Geometric mean | (ref)                                                                  | 1.00x faster                                                  |

Benchmarks with tag 'serialize':
================================

| Benchmark          | bm-20231114-linux-x86_64-python-4f04172c9287c507f142-3.13.0a1+-4f04172 | bm-20231114-linux-x86_64-mdboom-test_branch-3.13.0a1+-3ce7ef8 |
|--------------------|:----------------------------------------------------------------------:|:-------------------------------------------------------------:|
| pickle             | 11.6 us                                                                | 11.0 us: 1.05x faster                                         |
| pickle_dict        | 34.0 us                                                                | 32.4 us: 1.05x faster                                         |
| pickle_list        | 5.14 us                                                                | 4.92 us: 1.04x faster                                         |
| pickle_pure_python | 306 us                                                                 | 308 us: 1.01x slower                                          |
| xml_etree_process  | 59.5 ms                                                                | 59.9 ms: 1.01x slower                                         |
| xml_etree_generate | 86.9 ms                                                                | 87.9 ms: 1.01x slower                                         |
| unpickle           | 15.0 us                                                                | 15.4 us: 1.02x slower                                         |
| unpickle_list      | 5.18 us                                                                | 5.33 us: 1.03x slower                                         |
| tomli_loads        | 2.97 sec                                                               | 3.07 sec: 1.03x slower                                        |
| Geometric mean     | (ref)                                                                  | 1.00x faster                                                  |

Benchmark hidden because not significant (5): unpickle_pure_python, json_loads, json_dumps, xml_etree_parse, xml_etree_iterparse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231114-linux-x86_64-python-4f04172c9287c507f142-3.13.0a1+-4f04172 | bm-20231114-linux-x86_64-mdboom-test_branch-3.13.0a1+-3ce7ef8 |
|------------------------|:----------------------------------------------------------------------:|:-------------------------------------------------------------:|
| python_startup         | 10.4 ms                                                                | 10.3 ms: 1.00x faster                                         |
| python_startup_no_site | 9.08 ms                                                                | 9.05 ms: 1.00x faster                                         |
| Geometric mean         | (ref)                                                                  | 1.00x faster                                                  |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231114-linux-x86_64-python-4f04172c9287c507f142-3.13.0a1+-4f04172 | bm-20231114-linux-x86_64-mdboom-test_branch-3.13.0a1+-3ce7ef8 |
|-----------|:----------------------------------------------------------------------:|:-------------------------------------------------------------:|
| mako      | 14.3 ms                                                                | 14.5 ms: 1.02x slower                                         |

All benchmarks:
===============

| Benchmark                | bm-20231114-linux-x86_64-python-4f04172c9287c507f142-3.13.0a1+-4f04172 | bm-20231114-linux-x86_64-mdboom-test_branch-3.13.0a1+-3ce7ef8 |
|--------------------------|:----------------------------------------------------------------------:|:-------------------------------------------------------------:|
| mdp                      | 2.93 sec                                                               | 2.73 sec: 1.07x faster                                        |
| pickle                   | 11.6 us                                                                | 11.0 us: 1.05x faster                                         |
| pickle_dict              | 34.0 us                                                                | 32.4 us: 1.05x faster                                         |
| pickle_list              | 5.14 us                                                                | 4.92 us: 1.04x faster                                         |
| logging_silent           | 112 ns                                                                 | 107 ns: 1.04x faster                                          |
| pidigits                 | 196 ms                                                                 | 188 ms: 1.04x faster                                          |
| telco                    | 9.00 ms                                                                | 8.76 ms: 1.03x faster                                         |
| logging_format           | 7.27 us                                                                | 7.11 us: 1.02x faster                                         |
| regex_dna                | 217 ms                                                                 | 213 ms: 1.02x faster                                          |
| regex_effbot             | 3.55 ms                                                                | 3.50 ms: 1.01x faster                                         |
| coroutines               | 22.3 ms                                                                | 22.0 ms: 1.01x faster                                         |
| meteor_contest           | 118 ms                                                                 | 117 ms: 1.01x faster                                          |
| logging_simple           | 6.35 us                                                                | 6.29 us: 1.01x faster                                         |
| pathlib                  | 19.0 ms                                                                | 18.9 ms: 1.01x faster                                         |
| deepcopy_memo            | 42.1 us                                                                | 41.8 us: 1.01x faster                                         |
| raytrace                 | 310 ms                                                                 | 308 ms: 1.01x faster                                          |
| json                     | 5.19 ms                                                                | 5.15 ms: 1.01x faster                                         |
| generators               | 29.3 ms                                                                | 29.2 ms: 1.01x faster                                         |
| asyncio_tcp              | 496 ms                                                                 | 494 ms: 1.00x faster                                          |
| python_startup           | 10.4 ms                                                                | 10.3 ms: 1.00x faster                                         |
| sqlglot_optimize         | 55.2 ms                                                                | 54.9 ms: 1.00x faster                                         |
| python_startup_no_site   | 9.08 ms                                                                | 9.05 ms: 1.00x faster                                         |
| bench_thread_pool        | 861 us                                                                 | 858 us: 1.00x faster                                          |
| dulwich_log              | 69.1 ms                                                                | 69.3 ms: 1.00x slower                                         |
| 2to3                     | 293 ms                                                                 | 294 ms: 1.00x slower                                          |
| async_tree_io_tg         | 1.26 sec                                                               | 1.26 sec: 1.00x slower                                        |
| pprint_safe_repr         | 805 ms                                                                 | 808 ms: 1.00x slower                                          |
| pprint_pformat           | 1.67 sec                                                               | 1.67 sec: 1.00x slower                                        |
| float                    | 101 ms                                                                 | 102 ms: 1.01x slower                                          |
| deltablue                | 5.17 ms                                                                | 5.20 ms: 1.01x slower                                         |
| pickle_pure_python       | 306 us                                                                 | 308 us: 1.01x slower                                          |
| go                       | 170 ms                                                                 | 171 ms: 1.01x slower                                          |
| xml_etree_process        | 59.5 ms                                                                | 59.9 ms: 1.01x slower                                         |
| chaos                    | 75.1 ms                                                                | 75.6 ms: 1.01x slower                                         |
| chameleon                | 7.41 ms                                                                | 7.48 ms: 1.01x slower                                         |
| docutils                 | 2.71 sec                                                               | 2.74 sec: 1.01x slower                                        |
| deepcopy                 | 352 us                                                                 | 355 us: 1.01x slower                                          |
| async_tree_cpu_io_mixed  | 734 ms                                                                 | 742 ms: 1.01x slower                                          |
| xml_etree_generate       | 86.9 ms                                                                | 87.9 ms: 1.01x slower                                         |
| create_gc_cycles         | 1.46 ms                                                                | 1.48 ms: 1.01x slower                                         |
| regex_compile            | 164 ms                                                                 | 166 ms: 1.01x slower                                          |
| coverage                 | 94.1 ms                                                                | 95.6 ms: 1.02x slower                                         |
| typing_runtime_protocols | 125 us                                                                 | 127 us: 1.02x slower                                          |
| comprehensions           | 25.2 us                                                                | 25.7 us: 1.02x slower                                         |
| regex_v8                 | 24.4 ms                                                                | 24.8 ms: 1.02x slower                                         |
| scimark_sparse_mat_mult  | 6.44 ms                                                                | 6.56 ms: 1.02x slower                                         |
| crypto_pyaes             | 84.1 ms                                                                | 85.7 ms: 1.02x slower                                         |
| scimark_fft              | 424 ms                                                                 | 432 ms: 1.02x slower                                          |
| mako                     | 14.3 ms                                                                | 14.5 ms: 1.02x slower                                         |
| nqueens                  | 102 ms                                                                 | 105 ms: 1.02x slower                                          |
| hexiom                   | 10.0 ms                                                                | 10.2 ms: 1.02x slower                                         |
| unpickle                 | 15.0 us                                                                | 15.4 us: 1.02x slower                                         |
| fannkuch                 | 478 ms                                                                 | 492 ms: 1.03x slower                                          |
| unpickle_list            | 5.18 us                                                                | 5.33 us: 1.03x slower                                         |
| tomli_loads              | 2.97 sec                                                               | 3.07 sec: 1.03x slower                                        |
| unpack_sequence          | 45.3 ns                                                                | 47.5 ns: 1.05x slower                                         |
| gc_traversal             | 3.63 ms                                                                | 3.87 ms: 1.07x slower                                         |
| Geometric mean           | (ref)                                                                  | 1.00x slower                                                  |

Benchmark hidden because not significant (35): sympy_str, sqlite_synth, async_tree_none, sympy_sum, spectral_norm, scimark_monte_carlo, sympy_expand, unpickle_pure_python, tornado_http, mypy2, richards, sqlglot_normalize, deepcopy_reduce, sympy_integrate, asyncio_tcp_ssl, async_tree_memoization, async_generators, bench_mp_pool, async_tree_none_tg, asyncio_websockets, json_loads, sqlglot_transpile, sqlglot_parse, async_tree_io, pyflate, json_dumps, xml_etree_parse, scimark_sor, xml_etree_iterparse, richards_super, pycparser, nbody, scimark_lu, async_tree_memoization_tg, async_tree_cpu_io_mixed_tg


# HPT report

- Reliability score: 91.54% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
