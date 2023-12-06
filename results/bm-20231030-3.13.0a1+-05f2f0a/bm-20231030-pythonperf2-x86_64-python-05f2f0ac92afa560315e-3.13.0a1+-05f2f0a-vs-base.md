
# Results vs. base

- fork: python
- ref: 05f2f0ac92afa560315e
- machine: linux-x86_64
- commit hash: 05f2f0a
- commit date: 2023-10-30
- overall geometric mean: 1.00x faster
- HPT reliability: 94.35%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231031-pythonperf2-x86_64-python-4ebf2fae9664a4042511-3.13.0a1+-4ebf2fa | bm-20231030-pythonperf2-x86_64-python-05f2f0ac92afa560315e-3.13.0a1+-05f2f0a |
|----------------|:----------------------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| 2to3           | 297 ms                                                                       | 298 ms: 1.00x slower                                                         |
| chameleon      | 7.43 ms                                                                      | 7.36 ms: 1.01x faster                                                        |
| docutils       | 2.88 sec                                                                     | 2.88 sec: 1.00x slower                                                       |
| Geometric mean | (ref)                                                                        | 1.00x faster                                                                 |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'asyncio':
==============================

| Benchmark          | bm-20231031-pythonperf2-x86_64-python-4ebf2fae9664a4042511-3.13.0a1+-4ebf2fa | bm-20231030-pythonperf2-x86_64-python-05f2f0ac92afa560315e-3.13.0a1+-05f2f0a |
|--------------------|:----------------------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| async_tree_none_tg | 447 ms                                                                       | 443 ms: 1.01x faster                                                         |
| async_tree_io_tg   | 1.11 sec                                                                     | 1.10 sec: 1.01x faster                                                       |
| async_tree_io      | 1.09 sec                                                                     | 1.08 sec: 1.00x faster                                                       |
| Geometric mean     | (ref)                                                                        | 1.01x faster                                                                 |

Benchmark hidden because not significant (5): async_tree_memoization_tg, async_tree_none, async_tree_cpu_io_mixed_tg, async_tree_cpu_io_mixed, async_tree_memoization

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231031-pythonperf2-x86_64-python-4ebf2fae9664a4042511-3.13.0a1+-4ebf2fa | bm-20231030-pythonperf2-x86_64-python-05f2f0ac92afa560315e-3.13.0a1+-05f2f0a |
|----------------|:----------------------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| float          | 81.4 ms                                                                      | 78.7 ms: 1.03x faster                                                        |
| nbody          | 87.9 ms                                                                      | 91.3 ms: 1.04x slower                                                        |
| Geometric mean | (ref)                                                                        | 1.00x slower                                                                 |

Benchmark hidden because not significant (1): pidigits

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231031-pythonperf2-x86_64-python-4ebf2fae9664a4042511-3.13.0a1+-4ebf2fa | bm-20231030-pythonperf2-x86_64-python-05f2f0ac92afa560315e-3.13.0a1+-05f2f0a |
|----------------|:----------------------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| regex_dna      | 246 ms                                                                       | 241 ms: 1.02x faster                                                         |
| regex_compile  | 148 ms                                                                       | 147 ms: 1.00x faster                                                         |
| regex_effbot   | 3.48 ms                                                                      | 3.53 ms: 1.01x slower                                                        |
| regex_v8       | 25.1 ms                                                                      | 25.5 ms: 1.02x slower                                                        |
| Geometric mean | (ref)                                                                        | 1.00x slower                                                                 |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231031-pythonperf2-x86_64-python-4ebf2fae9664a4042511-3.13.0a1+-4ebf2fa | bm-20231030-pythonperf2-x86_64-python-05f2f0ac92afa560315e-3.13.0a1+-05f2f0a |
|----------------------|:----------------------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| xml_etree_process    | 59.4 ms                                                                      | 58.3 ms: 1.02x faster                                                        |
| unpickle_list        | 4.68 us                                                                      | 4.59 us: 1.02x faster                                                        |
| tomli_loads          | 2.23 sec                                                                     | 2.21 sec: 1.01x faster                                                       |
| json_loads           | 24.7 us                                                                      | 24.5 us: 1.00x faster                                                        |
| xml_etree_generate   | 86.5 ms                                                                      | 86.1 ms: 1.00x faster                                                        |
| pickle               | 10.1 us                                                                      | 10.2 us: 1.01x slower                                                        |
| json_dumps           | 10.5 ms                                                                      | 10.6 ms: 1.01x slower                                                        |
| unpickle_pure_python | 218 us                                                                       | 229 us: 1.05x slower                                                         |
| Geometric mean       | (ref)                                                                        | 1.00x slower                                                                 |

Benchmark hidden because not significant (6): unpickle, xml_etree_parse, pickle_dict, pickle_pure_python, pickle_list, xml_etree_iterparse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231031-pythonperf2-x86_64-python-4ebf2fae9664a4042511-3.13.0a1+-4ebf2fa | bm-20231030-pythonperf2-x86_64-python-05f2f0ac92afa560315e-3.13.0a1+-05f2f0a |
|------------------------|:----------------------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| python_startup         | 12.8 ms                                                                      | 12.9 ms: 1.00x slower                                                        |
| python_startup_no_site | 11.3 ms                                                                      | 11.4 ms: 1.01x slower                                                        |
| Geometric mean         | (ref)                                                                        | 1.01x slower                                                                 |

Benchmarks with tag 'template':
===============================

Benchmark hidden because not significant (1): mako

All benchmarks:
===============

| Benchmark                | bm-20231031-pythonperf2-x86_64-python-4ebf2fae9664a4042511-3.13.0a1+-4ebf2fa | bm-20231030-pythonperf2-x86_64-python-05f2f0ac92afa560315e-3.13.0a1+-05f2f0a |
|--------------------------|:----------------------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| unpack_sequence          | 56.7 ns                                                                      | 51.7 ns: 1.10x faster                                                        |
| scimark_sparse_mat_mult  | 4.27 ms                                                                      | 4.12 ms: 1.04x faster                                                        |
| float                    | 81.4 ms                                                                      | 78.7 ms: 1.03x faster                                                        |
| pycparser                | 1.34 sec                                                                     | 1.30 sec: 1.03x faster                                                       |
| scimark_fft              | 311 ms                                                                       | 303 ms: 1.02x faster                                                         |
| regex_dna                | 246 ms                                                                       | 241 ms: 1.02x faster                                                         |
| xml_etree_process        | 59.4 ms                                                                      | 58.3 ms: 1.02x faster                                                        |
| unpickle_list            | 4.68 us                                                                      | 4.59 us: 1.02x faster                                                        |
| go                       | 175 ms                                                                       | 172 ms: 1.02x faster                                                         |
| sympy_expand             | 502 ms                                                                       | 494 ms: 1.02x faster                                                         |
| scimark_sor              | 147 ms                                                                       | 145 ms: 1.01x faster                                                         |
| richards                 | 55.2 ms                                                                      | 54.6 ms: 1.01x faster                                                        |
| meteor_contest           | 131 ms                                                                       | 130 ms: 1.01x faster                                                         |
| async_tree_none_tg       | 447 ms                                                                       | 443 ms: 1.01x faster                                                         |
| deepcopy                 | 373 us                                                                       | 369 us: 1.01x faster                                                         |
| chameleon                | 7.43 ms                                                                      | 7.36 ms: 1.01x faster                                                        |
| telco                    | 8.15 ms                                                                      | 8.08 ms: 1.01x faster                                                        |
| logging_silent           | 98.0 ns                                                                      | 97.2 ns: 1.01x faster                                                        |
| tomli_loads              | 2.23 sec                                                                     | 2.21 sec: 1.01x faster                                                       |
| async_tree_io_tg         | 1.11 sec                                                                     | 1.10 sec: 1.01x faster                                                       |
| richards_super           | 60.7 ms                                                                      | 60.2 ms: 1.01x faster                                                        |
| coroutines               | 23.0 ms                                                                      | 22.8 ms: 1.01x faster                                                        |
| sympy_str                | 296 ms                                                                       | 294 ms: 1.01x faster                                                         |
| json_loads               | 24.7 us                                                                      | 24.5 us: 1.00x faster                                                        |
| comprehensions           | 16.8 us                                                                      | 16.7 us: 1.00x faster                                                        |
| chaos                    | 62.6 ms                                                                      | 62.2 ms: 1.00x faster                                                        |
| async_tree_io            | 1.09 sec                                                                     | 1.08 sec: 1.00x faster                                                       |
| xml_etree_generate       | 86.5 ms                                                                      | 86.1 ms: 1.00x faster                                                        |
| sqlglot_optimize         | 59.3 ms                                                                      | 59.0 ms: 1.00x faster                                                        |
| mypy2                    | 370 ms                                                                       | 369 ms: 1.00x faster                                                         |
| spectral_norm            | 92.6 ms                                                                      | 92.3 ms: 1.00x faster                                                        |
| deepcopy_memo            | 36.8 us                                                                      | 36.7 us: 1.00x faster                                                        |
| regex_compile            | 148 ms                                                                       | 147 ms: 1.00x faster                                                         |
| sympy_integrate          | 23.7 ms                                                                      | 23.6 ms: 1.00x faster                                                        |
| asyncio_tcp_ssl          | 1.58 sec                                                                     | 1.58 sec: 1.00x faster                                                       |
| 2to3                     | 297 ms                                                                       | 298 ms: 1.00x slower                                                         |
| scimark_monte_carlo      | 68.7 ms                                                                      | 68.9 ms: 1.00x slower                                                        |
| docutils                 | 2.88 sec                                                                     | 2.88 sec: 1.00x slower                                                       |
| crypto_pyaes             | 72.2 ms                                                                      | 72.4 ms: 1.00x slower                                                        |
| sqlglot_normalize        | 117 ms                                                                       | 117 ms: 1.00x slower                                                         |
| fannkuch                 | 394 ms                                                                       | 396 ms: 1.00x slower                                                         |
| python_startup           | 12.8 ms                                                                      | 12.9 ms: 1.00x slower                                                        |
| python_startup_no_site   | 11.3 ms                                                                      | 11.4 ms: 1.01x slower                                                        |
| hexiom                   | 6.49 ms                                                                      | 6.53 ms: 1.01x slower                                                        |
| deepcopy_reduce          | 3.30 us                                                                      | 3.32 us: 1.01x slower                                                        |
| pickle                   | 10.1 us                                                                      | 10.2 us: 1.01x slower                                                        |
| raytrace                 | 273 ms                                                                       | 275 ms: 1.01x slower                                                         |
| sqlite_synth             | 2.64 us                                                                      | 2.66 us: 1.01x slower                                                        |
| sqlglot_parse            | 1.41 ms                                                                      | 1.43 ms: 1.01x slower                                                        |
| typing_runtime_protocols | 152 us                                                                       | 154 us: 1.01x slower                                                         |
| gc_traversal             | 3.47 ms                                                                      | 3.52 ms: 1.01x slower                                                        |
| regex_effbot             | 3.48 ms                                                                      | 3.53 ms: 1.01x slower                                                        |
| json_dumps               | 10.5 ms                                                                      | 10.6 ms: 1.01x slower                                                        |
| dulwich_log              | 69.2 ms                                                                      | 70.1 ms: 1.01x slower                                                        |
| regex_v8                 | 25.1 ms                                                                      | 25.5 ms: 1.02x slower                                                        |
| logging_simple           | 6.77 us                                                                      | 6.88 us: 1.02x slower                                                        |
| logging_format           | 7.41 us                                                                      | 7.53 us: 1.02x slower                                                        |
| scimark_lu               | 101 ms                                                                       | 103 ms: 1.02x slower                                                         |
| async_generators         | 393 ms                                                                       | 400 ms: 1.02x slower                                                         |
| pprint_safe_repr         | 807 ms                                                                       | 829 ms: 1.03x slower                                                         |
| pprint_pformat           | 1.65 sec                                                                     | 1.70 sec: 1.03x slower                                                       |
| nbody                    | 87.9 ms                                                                      | 91.3 ms: 1.04x slower                                                        |
| unpickle_pure_python     | 218 us                                                                       | 229 us: 1.05x slower                                                         |
| coverage                 | 80.3 ms                                                                      | 87.3 ms: 1.09x slower                                                        |
| Geometric mean           | (ref)                                                                        | 1.00x faster                                                                 |

Benchmark hidden because not significant (28): async_tree_memoization_tg, async_tree_none, async_tree_cpu_io_mixed_tg, async_tree_cpu_io_mixed, async_tree_memoization, mako, create_gc_cycles, asyncio_tcp, bench_mp_pool, unpickle, asyncio_websockets, xml_etree_parse, pathlib, mdp, json, sympy_sum, pickle_dict, generators, pidigits, nqueens, pyflate, sqlglot_transpile, pickle_pure_python, deltablue, tornado_http, pickle_list, xml_etree_iterparse, bench_thread_pool


# HPT report

- Reliability score: 94.35% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
