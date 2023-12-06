
# Results vs. base

- fork: iritkatriel
- ref: gen_close
- machine: linux-x86_64
- commit hash: 03335e6
- commit date: 2023-10-26
- overall geometric mean: 1.00x faster
- HPT reliability: 89.85%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231026-linux-x86_64-python-a0c414c35d0dc0d44a88-3.13.0a1+-a0c414c | bm-20231026-linux-x86_64-iritkatriel-gen_close-3.13.0a1+-03335e6 |
|----------------|:----------------------------------------------------------------------:|:----------------------------------------------------------------:|
| 2to3           | 266 ms                                                                 | 264 ms: 1.01x faster                                             |
| Geometric mean | (ref)                                                                  | 1.00x faster                                                     |

Benchmark hidden because not significant (3): chameleon, docutils, tornado_http

Benchmarks with tag 'asyncio':
==============================

| Benchmark          | bm-20231026-linux-x86_64-python-a0c414c35d0dc0d44a88-3.13.0a1+-a0c414c | bm-20231026-linux-x86_64-iritkatriel-gen_close-3.13.0a1+-03335e6 |
|--------------------|:----------------------------------------------------------------------:|:----------------------------------------------------------------:|
| async_tree_none_tg | 459 ms                                                                 | 455 ms: 1.01x faster                                             |
| async_tree_io      | 1.17 sec                                                               | 1.19 sec: 1.01x slower                                           |
| async_tree_io_tg   | 1.21 sec                                                               | 1.23 sec: 1.01x slower                                           |
| Geometric mean     | (ref)                                                                  | 1.00x slower                                                     |

Benchmark hidden because not significant (5): async_tree_cpu_io_mixed, async_tree_none, async_tree_cpu_io_mixed_tg, async_tree_memoization, async_tree_memoization_tg

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231026-linux-x86_64-python-a0c414c35d0dc0d44a88-3.13.0a1+-a0c414c | bm-20231026-linux-x86_64-iritkatriel-gen_close-3.13.0a1+-03335e6 |
|----------------|:----------------------------------------------------------------------:|:----------------------------------------------------------------:|
| nbody          | 92.4 ms                                                                | 91.3 ms: 1.01x faster                                            |
| float          | 81.8 ms                                                                | 81.4 ms: 1.00x faster                                            |
| pidigits       | 187 ms                                                                 | 187 ms: 1.00x slower                                             |
| Geometric mean | (ref)                                                                  | 1.01x faster                                                     |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231026-linux-x86_64-python-a0c414c35d0dc0d44a88-3.13.0a1+-a0c414c | bm-20231026-linux-x86_64-iritkatriel-gen_close-3.13.0a1+-03335e6 |
|----------------|:----------------------------------------------------------------------:|:----------------------------------------------------------------:|
| regex_dna      | 220 ms                                                                 | 212 ms: 1.04x faster                                             |
| regex_effbot   | 3.71 ms                                                                | 3.65 ms: 1.02x faster                                            |
| regex_v8       | 25.6 ms                                                                | 25.5 ms: 1.01x faster                                            |
| regex_compile  | 137 ms                                                                 | 138 ms: 1.01x slower                                             |
| Geometric mean | (ref)                                                                  | 1.01x faster                                                     |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231026-linux-x86_64-python-a0c414c35d0dc0d44a88-3.13.0a1+-a0c414c | bm-20231026-linux-x86_64-iritkatriel-gen_close-3.13.0a1+-03335e6 |
|----------------------|:----------------------------------------------------------------------:|:----------------------------------------------------------------:|
| pickle_dict          | 36.5 us                                                                | 32.8 us: 1.12x faster                                            |
| pickle_list          | 5.19 us                                                                | 4.95 us: 1.05x faster                                            |
| pickle               | 11.6 us                                                                | 11.1 us: 1.05x faster                                            |
| unpickle_list        | 5.15 us                                                                | 5.08 us: 1.01x faster                                            |
| xml_etree_iterparse  | 106 ms                                                                 | 105 ms: 1.01x faster                                             |
| pickle_pure_python   | 303 us                                                                 | 300 us: 1.01x faster                                             |
| xml_etree_process    | 59.2 ms                                                                | 58.8 ms: 1.01x faster                                            |
| unpickle_pure_python | 221 us                                                                 | 220 us: 1.01x faster                                             |
| json_dumps           | 10.4 ms                                                                | 10.4 ms: 1.01x slower                                            |
| json_loads           | 27.8 us                                                                | 28.0 us: 1.01x slower                                            |
| Geometric mean       | (ref)                                                                  | 1.02x faster                                                     |

Benchmark hidden because not significant (4): xml_etree_generate, unpickle, xml_etree_parse, tomli_loads

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231026-linux-x86_64-python-a0c414c35d0dc0d44a88-3.13.0a1+-a0c414c | bm-20231026-linux-x86_64-iritkatriel-gen_close-3.13.0a1+-03335e6 |
|------------------------|:----------------------------------------------------------------------:|:----------------------------------------------------------------:|
| python_startup         | 10.3 ms                                                                | 10.3 ms: 1.00x faster                                            |
| python_startup_no_site | 8.97 ms                                                                | 8.94 ms: 1.00x faster                                            |
| Geometric mean         | (ref)                                                                  | 1.00x faster                                                     |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231026-linux-x86_64-python-a0c414c35d0dc0d44a88-3.13.0a1+-a0c414c | bm-20231026-linux-x86_64-iritkatriel-gen_close-3.13.0a1+-03335e6 |
|-----------|:----------------------------------------------------------------------:|:----------------------------------------------------------------:|
| mako      | 11.7 ms                                                                | 11.5 ms: 1.02x faster                                            |

All benchmarks:
===============

| Benchmark                | bm-20231026-linux-x86_64-python-a0c414c35d0dc0d44a88-3.13.0a1+-a0c414c | bm-20231026-linux-x86_64-iritkatriel-gen_close-3.13.0a1+-03335e6 |
|--------------------------|:----------------------------------------------------------------------:|:----------------------------------------------------------------:|
| pickle_dict              | 36.5 us                                                                | 32.8 us: 1.12x faster                                            |
| mdp                      | 2.72 sec                                                               | 2.54 sec: 1.07x faster                                           |
| pickle_list              | 5.19 us                                                                | 4.95 us: 1.05x faster                                            |
| pickle                   | 11.6 us                                                                | 11.1 us: 1.05x faster                                            |
| pycparser                | 1.21 sec                                                               | 1.16 sec: 1.04x faster                                           |
| regex_dna                | 220 ms                                                                 | 212 ms: 1.04x faster                                             |
| unpack_sequence          | 46.0 ns                                                                | 44.7 ns: 1.03x faster                                            |
| richards                 | 49.8 ms                                                                | 48.8 ms: 1.02x faster                                            |
| mako                     | 11.7 ms                                                                | 11.5 ms: 1.02x faster                                            |
| meteor_contest           | 109 ms                                                                 | 107 ms: 1.02x faster                                             |
| create_gc_cycles         | 1.48 ms                                                                | 1.45 ms: 1.02x faster                                            |
| pyflate                  | 478 ms                                                                 | 470 ms: 1.02x faster                                             |
| regex_effbot             | 3.71 ms                                                                | 3.65 ms: 1.02x faster                                            |
| deepcopy_reduce          | 3.17 us                                                                | 3.13 us: 1.02x faster                                            |
| go                       | 147 ms                                                                 | 145 ms: 1.01x faster                                             |
| logging_silent           | 106 ns                                                                 | 105 ns: 1.01x faster                                             |
| richards_super           | 55.7 ms                                                                | 55.0 ms: 1.01x faster                                            |
| chaos                    | 62.2 ms                                                                | 61.4 ms: 1.01x faster                                            |
| unpickle_list            | 5.15 us                                                                | 5.08 us: 1.01x faster                                            |
| nbody                    | 92.4 ms                                                                | 91.3 ms: 1.01x faster                                            |
| deepcopy_memo            | 38.9 us                                                                | 38.5 us: 1.01x faster                                            |
| xml_etree_iterparse      | 106 ms                                                                 | 105 ms: 1.01x faster                                             |
| deepcopy                 | 354 us                                                                 | 350 us: 1.01x faster                                             |
| crypto_pyaes             | 72.2 ms                                                                | 71.5 ms: 1.01x faster                                            |
| typing_runtime_protocols | 153 us                                                                 | 152 us: 1.01x faster                                             |
| pathlib                  | 19.0 ms                                                                | 18.9 ms: 1.01x faster                                            |
| pickle_pure_python       | 303 us                                                                 | 300 us: 1.01x faster                                             |
| async_tree_none_tg       | 459 ms                                                                 | 455 ms: 1.01x faster                                             |
| raytrace                 | 278 ms                                                                 | 276 ms: 1.01x faster                                             |
| hexiom                   | 6.25 ms                                                                | 6.20 ms: 1.01x faster                                            |
| dulwich_log              | 66.9 ms                                                                | 66.4 ms: 1.01x faster                                            |
| 2to3                     | 266 ms                                                                 | 264 ms: 1.01x faster                                             |
| xml_etree_process        | 59.2 ms                                                                | 58.8 ms: 1.01x faster                                            |
| regex_v8                 | 25.6 ms                                                                | 25.5 ms: 1.01x faster                                            |
| unpickle_pure_python     | 221 us                                                                 | 220 us: 1.01x faster                                             |
| scimark_sor              | 126 ms                                                                 | 125 ms: 1.00x faster                                             |
| float                    | 81.8 ms                                                                | 81.4 ms: 1.00x faster                                            |
| sympy_integrate          | 19.7 ms                                                                | 19.7 ms: 1.00x faster                                            |
| python_startup           | 10.3 ms                                                                | 10.3 ms: 1.00x faster                                            |
| sqlglot_normalize        | 105 ms                                                                 | 105 ms: 1.00x faster                                             |
| python_startup_no_site   | 8.97 ms                                                                | 8.94 ms: 1.00x faster                                            |
| pidigits                 | 187 ms                                                                 | 187 ms: 1.00x slower                                             |
| bench_thread_pool        | 813 us                                                                 | 815 us: 1.00x slower                                             |
| coverage                 | 94.0 ms                                                                | 94.3 ms: 1.00x slower                                            |
| deltablue                | 3.37 ms                                                                | 3.38 ms: 1.00x slower                                            |
| asyncio_tcp_ssl          | 1.77 sec                                                               | 1.78 sec: 1.01x slower                                           |
| logging_format           | 6.40 us                                                                | 6.43 us: 1.01x slower                                            |
| scimark_monte_carlo      | 68.6 ms                                                                | 69.1 ms: 1.01x slower                                            |
| asyncio_tcp              | 476 ms                                                                 | 479 ms: 1.01x slower                                             |
| json_dumps               | 10.4 ms                                                                | 10.4 ms: 1.01x slower                                            |
| json_loads               | 27.8 us                                                                | 28.0 us: 1.01x slower                                            |
| comprehensions           | 16.6 us                                                                | 16.7 us: 1.01x slower                                            |
| async_generators         | 454 ms                                                                 | 458 ms: 1.01x slower                                             |
| sqlglot_transpile        | 1.60 ms                                                                | 1.62 ms: 1.01x slower                                            |
| spectral_norm            | 109 ms                                                                 | 110 ms: 1.01x slower                                             |
| telco                    | 8.25 ms                                                                | 8.32 ms: 1.01x slower                                            |
| regex_compile            | 137 ms                                                                 | 138 ms: 1.01x slower                                             |
| async_tree_io            | 1.17 sec                                                               | 1.19 sec: 1.01x slower                                           |
| async_tree_io_tg         | 1.21 sec                                                               | 1.23 sec: 1.01x slower                                           |
| logging_simple           | 5.82 us                                                                | 5.91 us: 1.02x slower                                            |
| sqlglot_parse            | 1.29 ms                                                                | 1.31 ms: 1.02x slower                                            |
| scimark_lu               | 113 ms                                                                 | 116 ms: 1.02x slower                                             |
| coroutines               | 22.1 ms                                                                | 22.5 ms: 1.02x slower                                            |
| scimark_fft              | 361 ms                                                                 | 377 ms: 1.04x slower                                             |
| scimark_sparse_mat_mult  | 4.54 ms                                                                | 4.90 ms: 1.08x slower                                            |
| gc_traversal             | 3.58 ms                                                                | 4.08 ms: 1.14x slower                                            |
| Geometric mean           | (ref)                                                                  | 1.00x faster                                                     |

Benchmark hidden because not significant (26): async_tree_cpu_io_mixed, pprint_safe_repr, async_tree_none, sympy_expand, sympy_str, nqueens, xml_etree_generate, async_tree_cpu_io_mixed_tg, pprint_pformat, generators, sqlite_synth, asyncio_websockets, sympy_sum, unpickle, sqlglot_optimize, bench_mp_pool, docutils, async_tree_memoization, xml_etree_parse, chameleon, mypy2, tornado_http, tomli_loads, fannkuch, json, async_tree_memoization_tg


# HPT report

- Reliability score: 89.85% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
