
# Results vs. base

- fork: faster-cpython
- ref: faster_tier_2_interp
- machine: linux-x86_64
- commit hash: a9f3983
- commit date: 2023-11-12
- overall geometric mean: 1.00x faster
- HPT reliability: 99.49%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231114-linux-x86_64-python-16055c160412544e2a49-3.13.0a1+-16055c1 | bm-20231112-linux-x86_64-faster%2dcpython-faster_tier_2_interp-3.13.0a1+-a9f3983 |
|----------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| 2to3           | 297 ms                                                                 | 293 ms: 1.01x faster                                                             |
| chameleon      | 7.46 ms                                                                | 7.56 ms: 1.01x slower                                                            |
| docutils       | 2.73 sec                                                               | 2.72 sec: 1.00x faster                                                           |
| Geometric mean | (ref)                                                                  | 1.00x faster                                                                     |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20231114-linux-x86_64-python-16055c160412544e2a49-3.13.0a1+-16055c1 | bm-20231112-linux-x86_64-faster%2dcpython-faster_tier_2_interp-3.13.0a1+-a9f3983 |
|-------------------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| async_tree_io           | 1.24 sec                                                               | 1.23 sec: 1.01x faster                                                           |
| async_tree_cpu_io_mixed | 744 ms                                                                 | 736 ms: 1.01x faster                                                             |
| async_tree_memoization  | 598 ms                                                                 | 592 ms: 1.01x faster                                                             |
| async_tree_none_tg      | 483 ms                                                                 | 479 ms: 1.01x faster                                                             |
| async_tree_io_tg        | 1.27 sec                                                               | 1.26 sec: 1.01x faster                                                           |
| Geometric mean          | (ref)                                                                  | 1.01x faster                                                                     |

Benchmark hidden because not significant (3): async_tree_none, async_tree_cpu_io_mixed_tg, async_tree_memoization_tg

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231114-linux-x86_64-python-16055c160412544e2a49-3.13.0a1+-16055c1 | bm-20231112-linux-x86_64-faster%2dcpython-faster_tier_2_interp-3.13.0a1+-a9f3983 |
|----------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| nbody          | 126 ms                                                                 | 124 ms: 1.01x faster                                                             |
| float          | 106 ms                                                                 | 109 ms: 1.03x slower                                                             |
| pidigits       | 189 ms                                                                 | 196 ms: 1.04x slower                                                             |
| Geometric mean | (ref)                                                                  | 1.02x slower                                                                     |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231114-linux-x86_64-python-16055c160412544e2a49-3.13.0a1+-16055c1 | bm-20231112-linux-x86_64-faster%2dcpython-faster_tier_2_interp-3.13.0a1+-a9f3983 |
|----------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| regex_compile  | 168 ms                                                                 | 161 ms: 1.04x faster                                                             |
| regex_effbot   | 3.53 ms                                                                | 3.49 ms: 1.01x faster                                                            |
| regex_v8       | 25.0 ms                                                                | 24.7 ms: 1.01x faster                                                            |
| regex_dna      | 212 ms                                                                 | 214 ms: 1.01x slower                                                             |
| Geometric mean | (ref)                                                                  | 1.01x faster                                                                     |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231114-linux-x86_64-python-16055c160412544e2a49-3.13.0a1+-16055c1 | bm-20231112-linux-x86_64-faster%2dcpython-faster_tier_2_interp-3.13.0a1+-a9f3983 |
|----------------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| tomli_loads          | 3.12 sec                                                               | 2.99 sec: 1.04x faster                                                           |
| unpickle_list        | 5.28 us                                                                | 5.10 us: 1.04x faster                                                            |
| unpickle             | 14.9 us                                                                | 14.6 us: 1.03x faster                                                            |
| pickle_list          | 5.02 us                                                                | 4.95 us: 1.01x faster                                                            |
| pickle               | 11.5 us                                                                | 11.4 us: 1.01x faster                                                            |
| xml_etree_generate   | 87.5 ms                                                                | 87.0 ms: 1.01x faster                                                            |
| json_dumps           | 10.6 ms                                                                | 10.6 ms: 1.01x faster                                                            |
| pickle_dict          | 33.7 us                                                                | 33.6 us: 1.00x faster                                                            |
| xml_etree_parse      | 157 ms                                                                 | 159 ms: 1.01x slower                                                             |
| unpickle_pure_python | 247 us                                                                 | 249 us: 1.01x slower                                                             |
| pickle_pure_python   | 306 us                                                                 | 309 us: 1.01x slower                                                             |
| Geometric mean       | (ref)                                                                  | 1.01x faster                                                                     |

Benchmark hidden because not significant (3): json_loads, xml_etree_process, xml_etree_iterparse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231114-linux-x86_64-python-16055c160412544e2a49-3.13.0a1+-16055c1 | bm-20231112-linux-x86_64-faster%2dcpython-faster_tier_2_interp-3.13.0a1+-a9f3983 |
|------------------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| python_startup         | 10.4 ms                                                                | 10.3 ms: 1.01x faster                                                            |
| python_startup_no_site | 9.06 ms                                                                | 9.03 ms: 1.00x faster                                                            |
| Geometric mean         | (ref)                                                                  | 1.00x faster                                                                     |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231114-linux-x86_64-python-16055c160412544e2a49-3.13.0a1+-16055c1 | bm-20231112-linux-x86_64-faster%2dcpython-faster_tier_2_interp-3.13.0a1+-a9f3983 |
|-----------|:----------------------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| mako      | 15.2 ms                                                                | 15.2 ms: 1.00x slower                                                            |

All benchmarks:
===============

| Benchmark                | bm-20231114-linux-x86_64-python-16055c160412544e2a49-3.13.0a1+-16055c1 | bm-20231112-linux-x86_64-faster%2dcpython-faster_tier_2_interp-3.13.0a1+-a9f3983 |
|--------------------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| mdp                      | 2.94 sec                                                               | 2.78 sec: 1.06x faster                                                           |
| tomli_loads              | 3.12 sec                                                               | 2.99 sec: 1.04x faster                                                           |
| regex_compile            | 168 ms                                                                 | 161 ms: 1.04x faster                                                             |
| unpickle_list            | 5.28 us                                                                | 5.10 us: 1.04x faster                                                            |
| unpack_sequence          | 48.2 ns                                                                | 46.6 ns: 1.04x faster                                                            |
| unpickle                 | 14.9 us                                                                | 14.6 us: 1.03x faster                                                            |
| scimark_lu               | 122 ms                                                                 | 120 ms: 1.02x faster                                                             |
| typing_runtime_protocols | 127 us                                                                 | 124 us: 1.02x faster                                                             |
| scimark_sor              | 129 ms                                                                 | 126 ms: 1.02x faster                                                             |
| json                     | 5.22 ms                                                                | 5.12 ms: 1.02x faster                                                            |
| sympy_sum                | 157 ms                                                                 | 154 ms: 1.02x faster                                                             |
| scimark_sparse_mat_mult  | 6.77 ms                                                                | 6.66 ms: 1.02x faster                                                            |
| chaos                    | 76.9 ms                                                                | 75.7 ms: 1.02x faster                                                            |
| pickle_list              | 5.02 us                                                                | 4.95 us: 1.01x faster                                                            |
| nbody                    | 126 ms                                                                 | 124 ms: 1.01x faster                                                             |
| deltablue                | 5.40 ms                                                                | 5.32 ms: 1.01x faster                                                            |
| async_tree_io            | 1.24 sec                                                               | 1.23 sec: 1.01x faster                                                           |
| 2to3                     | 297 ms                                                                 | 293 ms: 1.01x faster                                                             |
| async_tree_cpu_io_mixed  | 744 ms                                                                 | 736 ms: 1.01x faster                                                             |
| regex_effbot             | 3.53 ms                                                                | 3.49 ms: 1.01x faster                                                            |
| regex_v8                 | 25.0 ms                                                                | 24.7 ms: 1.01x faster                                                            |
| spectral_norm            | 112 ms                                                                 | 111 ms: 1.01x faster                                                             |
| pickle                   | 11.5 us                                                                | 11.4 us: 1.01x faster                                                            |
| sympy_expand             | 488 ms                                                                 | 483 ms: 1.01x faster                                                             |
| async_tree_memoization   | 598 ms                                                                 | 592 ms: 1.01x faster                                                             |
| sympy_integrate          | 21.7 ms                                                                | 21.5 ms: 1.01x faster                                                            |
| mypy2                    | 358 ms                                                                 | 355 ms: 1.01x faster                                                             |
| go                       | 171 ms                                                                 | 170 ms: 1.01x faster                                                             |
| async_tree_none_tg       | 483 ms                                                                 | 479 ms: 1.01x faster                                                             |
| xml_etree_generate       | 87.5 ms                                                                | 87.0 ms: 1.01x faster                                                            |
| json_dumps               | 10.6 ms                                                                | 10.6 ms: 1.01x faster                                                            |
| async_tree_io_tg         | 1.27 sec                                                               | 1.26 sec: 1.01x faster                                                           |
| python_startup           | 10.4 ms                                                                | 10.3 ms: 1.01x faster                                                            |
| bench_thread_pool        | 864 us                                                                 | 860 us: 1.00x faster                                                             |
| docutils                 | 2.73 sec                                                               | 2.72 sec: 1.00x faster                                                           |
| async_generators         | 470 ms                                                                 | 468 ms: 1.00x faster                                                             |
| scimark_monte_carlo      | 81.9 ms                                                                | 81.6 ms: 1.00x faster                                                            |
| pickle_dict              | 33.7 us                                                                | 33.6 us: 1.00x faster                                                            |
| python_startup_no_site   | 9.06 ms                                                                | 9.03 ms: 1.00x faster                                                            |
| sqlglot_optimize         | 55.0 ms                                                                | 54.9 ms: 1.00x faster                                                            |
| asyncio_tcp_ssl          | 1.81 sec                                                               | 1.81 sec: 1.00x faster                                                           |
| pprint_pformat           | 1.70 sec                                                               | 1.71 sec: 1.00x slower                                                           |
| mako                     | 15.2 ms                                                                | 15.2 ms: 1.00x slower                                                            |
| asyncio_tcp              | 499 ms                                                                 | 502 ms: 1.01x slower                                                             |
| meteor_contest           | 119 ms                                                                 | 120 ms: 1.01x slower                                                             |
| raytrace                 | 314 ms                                                                 | 316 ms: 1.01x slower                                                             |
| deepcopy_memo            | 43.0 us                                                                | 43.3 us: 1.01x slower                                                            |
| regex_dna                | 212 ms                                                                 | 214 ms: 1.01x slower                                                             |
| xml_etree_parse          | 157 ms                                                                 | 159 ms: 1.01x slower                                                             |
| sqlite_synth             | 2.88 us                                                                | 2.91 us: 1.01x slower                                                            |
| coroutines               | 22.1 ms                                                                | 22.3 ms: 1.01x slower                                                            |
| unpickle_pure_python     | 247 us                                                                 | 249 us: 1.01x slower                                                             |
| pprint_safe_repr         | 824 ms                                                                 | 833 ms: 1.01x slower                                                             |
| pickle_pure_python       | 306 us                                                                 | 309 us: 1.01x slower                                                             |
| chameleon                | 7.46 ms                                                                | 7.56 ms: 1.01x slower                                                            |
| fannkuch                 | 505 ms                                                                 | 512 ms: 1.01x slower                                                             |
| deepcopy_reduce          | 3.16 us                                                                | 3.21 us: 1.01x slower                                                            |
| logging_format           | 7.08 us                                                                | 7.18 us: 1.01x slower                                                            |
| telco                    | 8.85 ms                                                                | 8.98 ms: 1.01x slower                                                            |
| logging_silent           | 106 ns                                                                 | 107 ns: 1.02x slower                                                             |
| deepcopy                 | 351 us                                                                 | 359 us: 1.02x slower                                                             |
| pyflate                  | 559 ms                                                                 | 573 ms: 1.02x slower                                                             |
| pycparser                | 1.23 sec                                                               | 1.26 sec: 1.03x slower                                                           |
| nqueens                  | 110 ms                                                                 | 113 ms: 1.03x slower                                                             |
| crypto_pyaes             | 86.1 ms                                                                | 88.5 ms: 1.03x slower                                                            |
| float                    | 106 ms                                                                 | 109 ms: 1.03x slower                                                             |
| generators               | 29.0 ms                                                                | 29.9 ms: 1.03x slower                                                            |
| pidigits                 | 189 ms                                                                 | 196 ms: 1.04x slower                                                             |
| gc_traversal             | 3.58 ms                                                                | 3.82 ms: 1.07x slower                                                            |
| Geometric mean           | (ref)                                                                  | 1.00x faster                                                                     |

Benchmark hidden because not significant (23): async_tree_none, sympy_str, async_tree_cpu_io_mixed_tg, tornado_http, sqlglot_transpile, json_loads, async_tree_memoization_tg, xml_etree_process, logging_simple, sqlglot_parse, asyncio_websockets, hexiom, xml_etree_iterparse, bench_mp_pool, pathlib, comprehensions, richards_super, dulwich_log, scimark_fft, sqlglot_normalize, coverage, create_gc_cycles, richards


# HPT report

- Reliability score: 99.49% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
