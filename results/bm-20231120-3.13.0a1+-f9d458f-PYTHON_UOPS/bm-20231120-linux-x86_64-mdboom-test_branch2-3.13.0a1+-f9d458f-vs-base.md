
# Results vs. base

- fork: mdboom
- ref: test_branch2
- machine: linux-x86_64
- commit hash: f9d458f
- commit date: 2023-11-20
- overall geometric mean: 1.00x faster
- HPT reliability: 97.90%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231120-linux-x86_64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 | bm-20231120-linux-x86_64-mdboom-test_branch2-3.13.0a1+-f9d458f |
|----------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------:|
| 2to3           | 297 ms                                                                 | 295 ms: 1.00x faster                                           |
| docutils       | 2.76 sec                                                               | 2.75 sec: 1.00x faster                                         |
| Geometric mean | (ref)                                                                  | 1.00x faster                                                   |

Benchmark hidden because not significant (2): chameleon, tornado_http

Benchmarks with tag 'asyncio':
==============================

| Benchmark        | bm-20231120-linux-x86_64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 | bm-20231120-linux-x86_64-mdboom-test_branch2-3.13.0a1+-f9d458f |
|------------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------:|
| async_tree_io    | 1.24 sec                                                               | 1.21 sec: 1.02x faster                                         |
| async_tree_io_tg | 1.26 sec                                                               | 1.24 sec: 1.02x faster                                         |
| Geometric mean   | (ref)                                                                  | 1.01x faster                                                   |

Benchmark hidden because not significant (6): async_tree_memoization, async_tree_cpu_io_mixed, async_tree_none, async_tree_none_tg, async_tree_memoization_tg, async_tree_cpu_io_mixed_tg

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231120-linux-x86_64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 | bm-20231120-linux-x86_64-mdboom-test_branch2-3.13.0a1+-f9d458f |
|----------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------:|
| pidigits       | 197 ms                                                                 | 197 ms: 1.00x slower                                           |
| Geometric mean | (ref)                                                                  | 1.00x slower                                                   |

Benchmark hidden because not significant (2): float, nbody

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231120-linux-x86_64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 | bm-20231120-linux-x86_64-mdboom-test_branch2-3.13.0a1+-f9d458f |
|----------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------:|
| regex_v8       | 26.2 ms                                                                | 25.9 ms: 1.01x faster                                          |
| regex_compile  | 168 ms                                                                 | 169 ms: 1.00x slower                                           |
| regex_effbot   | 3.66 ms                                                                | 3.69 ms: 1.01x slower                                          |
| regex_dna      | 216 ms                                                                 | 218 ms: 1.01x slower                                           |
| Geometric mean | (ref)                                                                  | 1.00x slower                                                   |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231120-linux-x86_64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 | bm-20231120-linux-x86_64-mdboom-test_branch2-3.13.0a1+-f9d458f |
|----------------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------:|
| pickle_dict          | 35.1 us                                                                | 33.7 us: 1.04x faster                                          |
| unpickle             | 14.8 us                                                                | 14.5 us: 1.02x faster                                          |
| unpickle_list        | 5.17 us                                                                | 5.09 us: 1.02x faster                                          |
| json_dumps           | 10.7 ms                                                                | 10.6 ms: 1.01x faster                                          |
| pickle_list          | 5.16 us                                                                | 5.11 us: 1.01x faster                                          |
| pickle_pure_python   | 309 us                                                                 | 307 us: 1.01x faster                                           |
| pickle               | 11.7 us                                                                | 11.6 us: 1.01x faster                                          |
| xml_etree_process    | 64.9 ms                                                                | 64.5 ms: 1.01x faster                                          |
| xml_etree_iterparse  | 119 ms                                                                 | 118 ms: 1.00x faster                                           |
| tomli_loads          | 2.95 sec                                                               | 2.97 sec: 1.01x slower                                         |
| unpickle_pure_python | 248 us                                                                 | 252 us: 1.02x slower                                           |
| Geometric mean       | (ref)                                                                  | 1.01x faster                                                   |

Benchmark hidden because not significant (3): xml_etree_parse, xml_etree_generate, json_loads

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231120-linux-x86_64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 | bm-20231120-linux-x86_64-mdboom-test_branch2-3.13.0a1+-f9d458f |
|------------------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------:|
| python_startup_no_site | 9.05 ms                                                                | 9.00 ms: 1.00x faster                                          |
| python_startup         | 10.4 ms                                                                | 10.4 ms: 1.00x faster                                          |
| Geometric mean         | (ref)                                                                  | 1.00x faster                                                   |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231120-linux-x86_64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 | bm-20231120-linux-x86_64-mdboom-test_branch2-3.13.0a1+-f9d458f |
|-----------|:----------------------------------------------------------------------:|:--------------------------------------------------------------:|
| mako      | 17.4 ms                                                                | 17.2 ms: 1.01x faster                                          |

All benchmarks:
===============

| Benchmark                | bm-20231120-linux-x86_64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 | bm-20231120-linux-x86_64-mdboom-test_branch2-3.13.0a1+-f9d458f |
|--------------------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------:|
| typing_runtime_protocols | 129 us                                                                 | 123 us: 1.05x faster                                           |
| pickle_dict              | 35.1 us                                                                | 33.7 us: 1.04x faster                                          |
| logging_silent           | 112 ns                                                                 | 109 ns: 1.03x faster                                           |
| fannkuch                 | 502 ms                                                                 | 490 ms: 1.03x faster                                           |
| async_tree_io            | 1.24 sec                                                               | 1.21 sec: 1.02x faster                                         |
| deepcopy_reduce          | 3.22 us                                                                | 3.16 us: 1.02x faster                                          |
| unpickle                 | 14.8 us                                                                | 14.5 us: 1.02x faster                                          |
| scimark_lu               | 124 ms                                                                 | 122 ms: 1.02x faster                                           |
| pyflate                  | 601 ms                                                                 | 592 ms: 1.02x faster                                           |
| unpickle_list            | 5.17 us                                                                | 5.09 us: 1.02x faster                                          |
| async_tree_io_tg         | 1.26 sec                                                               | 1.24 sec: 1.02x faster                                         |
| deepcopy_memo            | 43.0 us                                                                | 42.5 us: 1.01x faster                                          |
| deltablue                | 5.80 ms                                                                | 5.73 ms: 1.01x faster                                          |
| telco                    | 9.02 ms                                                                | 8.92 ms: 1.01x faster                                          |
| regex_v8                 | 26.2 ms                                                                | 25.9 ms: 1.01x faster                                          |
| scimark_sor              | 127 ms                                                                 | 126 ms: 1.01x faster                                           |
| json_dumps               | 10.7 ms                                                                | 10.6 ms: 1.01x faster                                          |
| pickle_list              | 5.16 us                                                                | 5.11 us: 1.01x faster                                          |
| mako                     | 17.4 ms                                                                | 17.2 ms: 1.01x faster                                          |
| deepcopy                 | 366 us                                                                 | 363 us: 1.01x faster                                           |
| richards                 | 51.7 ms                                                                | 51.2 ms: 1.01x faster                                          |
| richards_super           | 58.8 ms                                                                | 58.3 ms: 1.01x faster                                          |
| pickle_pure_python       | 309 us                                                                 | 307 us: 1.01x faster                                           |
| scimark_monte_carlo      | 90.0 ms                                                                | 89.2 ms: 1.01x faster                                          |
| pickle                   | 11.7 us                                                                | 11.6 us: 1.01x faster                                          |
| generators               | 29.6 ms                                                                | 29.4 ms: 1.01x faster                                          |
| logging_simple           | 6.24 us                                                                | 6.20 us: 1.01x faster                                          |
| xml_etree_process        | 64.9 ms                                                                | 64.5 ms: 1.01x faster                                          |
| mypy2                    | 361 ms                                                                 | 359 ms: 1.01x faster                                           |
| asyncio_tcp_ssl          | 1.82 sec                                                               | 1.81 sec: 1.01x faster                                         |
| raytrace                 | 326 ms                                                                 | 324 ms: 1.01x faster                                           |
| 2to3                     | 297 ms                                                                 | 295 ms: 1.00x faster                                           |
| docutils                 | 2.76 sec                                                               | 2.75 sec: 1.00x faster                                         |
| python_startup_no_site   | 9.05 ms                                                                | 9.00 ms: 1.00x faster                                          |
| xml_etree_iterparse      | 119 ms                                                                 | 118 ms: 1.00x faster                                           |
| asyncio_tcp              | 491 ms                                                                 | 490 ms: 1.00x faster                                           |
| dulwich_log              | 70.1 ms                                                                | 69.9 ms: 1.00x faster                                          |
| sympy_integrate          | 22.2 ms                                                                | 22.1 ms: 1.00x faster                                          |
| python_startup           | 10.4 ms                                                                | 10.4 ms: 1.00x faster                                          |
| pidigits                 | 197 ms                                                                 | 197 ms: 1.00x slower                                           |
| sqlglot_optimize         | 60.6 ms                                                                | 60.7 ms: 1.00x slower                                          |
| bench_thread_pool        | 866 us                                                                 | 868 us: 1.00x slower                                           |
| regex_compile            | 168 ms                                                                 | 169 ms: 1.00x slower                                           |
| pprint_pformat           | 1.78 sec                                                               | 1.79 sec: 1.00x slower                                         |
| meteor_contest           | 122 ms                                                                 | 123 ms: 1.00x slower                                           |
| tomli_loads              | 2.95 sec                                                               | 2.97 sec: 1.01x slower                                         |
| go                       | 170 ms                                                                 | 171 ms: 1.01x slower                                           |
| pprint_safe_repr         | 854 ms                                                                 | 861 ms: 1.01x slower                                           |
| regex_effbot             | 3.66 ms                                                                | 3.69 ms: 1.01x slower                                          |
| chaos                    | 82.0 ms                                                                | 82.8 ms: 1.01x slower                                          |
| sqlite_synth             | 2.95 us                                                                | 2.98 us: 1.01x slower                                          |
| sqlglot_normalize        | 118 ms                                                                 | 119 ms: 1.01x slower                                           |
| regex_dna                | 216 ms                                                                 | 218 ms: 1.01x slower                                           |
| comprehensions           | 26.0 us                                                                | 26.3 us: 1.01x slower                                          |
| unpack_sequence          | 49.9 ns                                                                | 50.8 ns: 1.02x slower                                          |
| unpickle_pure_python     | 248 us                                                                 | 252 us: 1.02x slower                                           |
| json                     | 5.16 ms                                                                | 5.27 ms: 1.02x slower                                          |
| nqueens                  | 107 ms                                                                 | 110 ms: 1.03x slower                                           |
| coroutines               | 21.5 ms                                                                | 22.2 ms: 1.03x slower                                          |
| gc_traversal             | 3.67 ms                                                                | 3.81 ms: 1.04x slower                                          |
| mdp                      | 2.75 sec                                                               | 2.91 sec: 1.06x slower                                         |
| scimark_sparse_mat_mult  | 6.88 ms                                                                | 7.47 ms: 1.09x slower                                          |
| Geometric mean           | (ref)                                                                  | 1.00x faster                                                   |

Benchmark hidden because not significant (31): async_tree_memoization, sympy_str, coverage, logging_format, async_tree_cpu_io_mixed, chameleon, pycparser, tornado_http, dask, async_tree_none, create_gc_cycles, async_tree_none_tg, xml_etree_parse, async_tree_memoization_tg, float, sympy_sum, asyncio_websockets, spectral_norm, pathlib, async_tree_cpu_io_mixed_tg, xml_etree_generate, bench_mp_pool, json_loads, hexiom, async_generators, crypto_pyaes, sqlglot_transpile, scimark_fft, sqlglot_parse, nbody, sympy_expand


# HPT report

- Reliability score: 97.90% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
