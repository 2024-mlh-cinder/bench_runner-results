
# Results vs. base

- fork: iritkatriel
- ref: INSTRUMENTED_LINE
- machine: linux-x86_64
- commit hash: 31b3dd0
- commit date: 2023-09-13
- overall geometric mean: 1.01x slower
- HPT reliability: 86.99%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20230913-linux-x86_64-python-d69805b38a1815e7aaad-3.13.0a0-d69805b | bm-20230913-linux-x86_64-iritkatriel-INSTRUMENTED_LINE-3.13.0a0-31b3dd0 |
|----------------|:---------------------------------------------------------------------:|:-----------------------------------------------------------------------:|
| docutils       | 2.61 sec                                                              | 2.62 sec: 1.00x slower                                                  |
| Geometric mean | (ref)                                                                 | 1.01x slower                                                            |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20230913-linux-x86_64-python-d69805b38a1815e7aaad-3.13.0a0-d69805b | bm-20230913-linux-x86_64-iritkatriel-INSTRUMENTED_LINE-3.13.0a0-31b3dd0 |
|----------------|:---------------------------------------------------------------------:|:-----------------------------------------------------------------------:|
| pidigits       | 204 ms                                                                | 187 ms: 1.09x faster                                                    |
| float          | 80.0 ms                                                               | 79.1 ms: 1.01x faster                                                   |
| nbody          | 90.6 ms                                                               | 91.8 ms: 1.01x slower                                                   |
| Geometric mean | (ref)                                                                 | 1.03x faster                                                            |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20230913-linux-x86_64-python-d69805b38a1815e7aaad-3.13.0a0-d69805b | bm-20230913-linux-x86_64-iritkatriel-INSTRUMENTED_LINE-3.13.0a0-31b3dd0 |
|----------------|:---------------------------------------------------------------------:|:-----------------------------------------------------------------------:|
| regex_effbot   | 3.65 ms                                                               | 3.48 ms: 1.05x faster                                                   |
| regex_v8       | 24.7 ms                                                               | 23.9 ms: 1.04x faster                                                   |
| regex_dna      | 212 ms                                                                | 208 ms: 1.02x faster                                                    |
| regex_compile  | 134 ms                                                                | 135 ms: 1.01x slower                                                    |
| Geometric mean | (ref)                                                                 | 1.02x faster                                                            |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20230913-linux-x86_64-python-d69805b38a1815e7aaad-3.13.0a0-d69805b | bm-20230913-linux-x86_64-iritkatriel-INSTRUMENTED_LINE-3.13.0a0-31b3dd0 |
|----------------------|:---------------------------------------------------------------------:|:-----------------------------------------------------------------------:|
| xml_etree_process    | 58.1 ms                                                               | 57.5 ms: 1.01x faster                                                   |
| unpickle_list        | 4.90 us                                                               | 4.86 us: 1.01x faster                                                   |
| xml_etree_generate   | 84.5 ms                                                               | 83.8 ms: 1.01x faster                                                   |
| pickle               | 10.4 us                                                               | 10.4 us: 1.00x faster                                                   |
| unpickle             | 14.2 us                                                               | 14.2 us: 1.01x slower                                                   |
| json_loads           | 25.2 us                                                               | 25.4 us: 1.01x slower                                                   |
| pickle_dict          | 31.4 us                                                               | 31.7 us: 1.01x slower                                                   |
| tomli_loads          | 2.03 sec                                                              | 2.05 sec: 1.01x slower                                                  |
| pickle_pure_python   | 298 us                                                                | 308 us: 1.04x slower                                                    |
| unpickle_pure_python | 213 us                                                                | 221 us: 1.04x slower                                                    |
| Geometric mean       | (ref)                                                                 | 1.00x slower                                                            |

Benchmark hidden because not significant (4): xml_etree_iterparse, xml_etree_parse, pickle_list, json_dumps

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20230913-linux-x86_64-python-d69805b38a1815e7aaad-3.13.0a0-d69805b | bm-20230913-linux-x86_64-iritkatriel-INSTRUMENTED_LINE-3.13.0a0-31b3dd0 |
|------------------------|:---------------------------------------------------------------------:|:-----------------------------------------------------------------------:|
| python_startup         | 10.0 ms                                                               | 10.1 ms: 1.00x slower                                                   |
| python_startup_no_site | 6.82 ms                                                               | 6.85 ms: 1.00x slower                                                   |
| Geometric mean         | (ref)                                                                 | 1.00x slower                                                            |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20230913-linux-x86_64-python-d69805b38a1815e7aaad-3.13.0a0-d69805b | bm-20230913-linux-x86_64-iritkatriel-INSTRUMENTED_LINE-3.13.0a0-31b3dd0 |
|-----------|:---------------------------------------------------------------------:|:-----------------------------------------------------------------------:|
| mako      | 10.6 ms                                                               | 10.8 ms: 1.01x slower                                                   |

All benchmarks:
===============

| Benchmark                | bm-20230913-linux-x86_64-python-d69805b38a1815e7aaad-3.13.0a0-d69805b | bm-20230913-linux-x86_64-iritkatriel-INSTRUMENTED_LINE-3.13.0a0-31b3dd0 |
|--------------------------|:---------------------------------------------------------------------:|:-----------------------------------------------------------------------:|
| pidigits                 | 204 ms                                                                | 187 ms: 1.09x faster                                                    |
| regex_effbot             | 3.65 ms                                                               | 3.48 ms: 1.05x faster                                                   |
| pycparser                | 1.19 sec                                                              | 1.14 sec: 1.04x faster                                                  |
| regex_v8                 | 24.7 ms                                                               | 23.9 ms: 1.04x faster                                                   |
| scimark_sparse_mat_mult  | 4.69 ms                                                               | 4.59 ms: 1.02x faster                                                   |
| async_generators         | 441 ms                                                                | 432 ms: 1.02x faster                                                    |
| regex_dna                | 212 ms                                                                | 208 ms: 1.02x faster                                                    |
| pyflate                  | 456 ms                                                                | 449 ms: 1.01x faster                                                    |
| nqueens                  | 79.2 ms                                                               | 78.2 ms: 1.01x faster                                                   |
| meteor_contest           | 107 ms                                                                | 106 ms: 1.01x faster                                                    |
| crypto_pyaes             | 69.8 ms                                                               | 69.0 ms: 1.01x faster                                                   |
| float                    | 80.0 ms                                                               | 79.1 ms: 1.01x faster                                                   |
| xml_etree_process        | 58.1 ms                                                               | 57.5 ms: 1.01x faster                                                   |
| unpickle_list            | 4.90 us                                                               | 4.86 us: 1.01x faster                                                   |
| sqlglot_transpile        | 1.59 ms                                                               | 1.58 ms: 1.01x faster                                                   |
| xml_etree_generate       | 84.5 ms                                                               | 83.8 ms: 1.01x faster                                                   |
| raytrace                 | 271 ms                                                                | 269 ms: 1.01x faster                                                    |
| comprehensions           | 20.5 us                                                               | 20.4 us: 1.01x faster                                                   |
| go                       | 139 ms                                                                | 139 ms: 1.01x faster                                                    |
| mdp                      | 2.53 sec                                                              | 2.52 sec: 1.01x faster                                                  |
| sqlglot_parse            | 1.28 ms                                                               | 1.27 ms: 1.01x faster                                                   |
| sqlglot_normalize        | 105 ms                                                                | 105 ms: 1.00x faster                                                    |
| pickle                   | 10.4 us                                                               | 10.4 us: 1.00x faster                                                   |
| gc_traversal             | 4.12 ms                                                               | 4.10 ms: 1.00x faster                                                   |
| deepcopy_memo            | 37.5 us                                                               | 37.3 us: 1.00x faster                                                   |
| asyncio_tcp_ssl          | 1.79 sec                                                              | 1.79 sec: 1.00x faster                                                  |
| python_startup           | 10.0 ms                                                               | 10.1 ms: 1.00x slower                                                   |
| mypy2                    | 337 ms                                                                | 338 ms: 1.00x slower                                                    |
| python_startup_no_site   | 6.82 ms                                                               | 6.85 ms: 1.00x slower                                                   |
| docutils                 | 2.61 sec                                                              | 2.62 sec: 1.00x slower                                                  |
| fannkuch                 | 378 ms                                                                | 379 ms: 1.01x slower                                                    |
| create_gc_cycles         | 1.52 ms                                                               | 1.52 ms: 1.01x slower                                                   |
| scimark_monte_carlo      | 65.9 ms                                                               | 66.2 ms: 1.01x slower                                                   |
| unpickle                 | 14.2 us                                                               | 14.2 us: 1.01x slower                                                   |
| bench_thread_pool        | 808 us                                                                | 813 us: 1.01x slower                                                    |
| hexiom                   | 5.98 ms                                                               | 6.02 ms: 1.01x slower                                                   |
| sqlite_synth             | 2.71 us                                                               | 2.73 us: 1.01x slower                                                   |
| chaos                    | 60.1 ms                                                               | 60.5 ms: 1.01x slower                                                   |
| regex_compile            | 134 ms                                                                | 135 ms: 1.01x slower                                                    |
| deepcopy                 | 348 us                                                                | 351 us: 1.01x slower                                                    |
| json_loads               | 25.2 us                                                               | 25.4 us: 1.01x slower                                                   |
| dask                     | 521 ms                                                                | 526 ms: 1.01x slower                                                    |
| pickle_dict              | 31.4 us                                                               | 31.7 us: 1.01x slower                                                   |
| dulwich_log              | 66.2 ms                                                               | 66.8 ms: 1.01x slower                                                   |
| tomli_loads              | 2.03 sec                                                              | 2.05 sec: 1.01x slower                                                  |
| coroutines               | 21.8 ms                                                               | 22.0 ms: 1.01x slower                                                   |
| telco                    | 8.03 ms                                                               | 8.11 ms: 1.01x slower                                                   |
| richards                 | 48.2 ms                                                               | 48.8 ms: 1.01x slower                                                   |
| pprint_safe_repr         | 717 ms                                                                | 726 ms: 1.01x slower                                                    |
| mako                     | 10.6 ms                                                               | 10.8 ms: 1.01x slower                                                   |
| richards_super           | 54.7 ms                                                               | 55.5 ms: 1.01x slower                                                   |
| nbody                    | 90.6 ms                                                               | 91.8 ms: 1.01x slower                                                   |
| typing_runtime_protocols | 140 us                                                                | 142 us: 1.01x slower                                                    |
| pprint_pformat           | 1.47 sec                                                              | 1.49 sec: 1.01x slower                                                  |
| logging_simple           | 5.90 us                                                               | 5.99 us: 1.01x slower                                                   |
| logging_format           | 6.50 us                                                               | 6.62 us: 1.02x slower                                                   |
| async_tree_cpu_io_mixed  | 704 ms                                                                | 721 ms: 1.02x slower                                                    |
| pathlib                  | 18.3 ms                                                               | 18.8 ms: 1.03x slower                                                   |
| spectral_norm            | 105 ms                                                                | 108 ms: 1.03x slower                                                    |
| scimark_sor              | 119 ms                                                                | 122 ms: 1.03x slower                                                    |
| async_tree_memoization   | 565 ms                                                                | 581 ms: 1.03x slower                                                    |
| logging_silent           | 101 ns                                                                | 104 ns: 1.03x slower                                                    |
| async_tree_io            | 1.19 sec                                                              | 1.23 sec: 1.03x slower                                                  |
| pickle_pure_python       | 298 us                                                                | 308 us: 1.04x slower                                                    |
| unpickle_pure_python     | 213 us                                                                | 221 us: 1.04x slower                                                    |
| async_tree_none          | 435 ms                                                                | 451 ms: 1.04x slower                                                    |
| deepcopy_reduce          | 3.09 us                                                               | 3.22 us: 1.04x slower                                                   |
| generators               | 28.8 ms                                                               | 30.0 ms: 1.04x slower                                                   |
| unpack_sequence          | 40.2 ns                                                               | 51.9 ns: 1.29x slower                                                   |
| Geometric mean           | (ref)                                                                 | 1.01x slower                                                            |

Benchmark hidden because not significant (13): xml_etree_iterparse, xml_etree_parse, sqlglot_optimize, scimark_fft, json, pickle_list, deltablue, json_dumps, asyncio_tcp, coverage, bench_mp_pool, scimark_lu, tornado_http


# HPT report

- Reliability score: 86.99% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
