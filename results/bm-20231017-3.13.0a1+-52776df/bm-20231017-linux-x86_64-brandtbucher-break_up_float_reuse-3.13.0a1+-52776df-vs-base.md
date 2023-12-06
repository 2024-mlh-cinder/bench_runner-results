
# Results vs. base

- fork: brandtbucher
- ref: break_up_float_reuse
- machine: linux-x86_64
- commit hash: 52776df
- commit date: 2023-10-17
- overall geometric mean: 1.00x slower
- HPT reliability: 51.22%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231016-linux-x86_64-python-f07ca27709855d4637b4-3.13.0a1+-f07ca27 | bm-20231017-linux-x86_64-brandtbucher-break_up_float_reuse-3.13.0a1+-52776df |
|----------------|:----------------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| docutils       | 2.67 sec                                                               | 2.64 sec: 1.01x faster                                                       |
| Geometric mean | (ref)                                                                  | 1.01x faster                                                                 |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231016-linux-x86_64-python-f07ca27709855d4637b4-3.13.0a1+-f07ca27 | bm-20231017-linux-x86_64-brandtbucher-break_up_float_reuse-3.13.0a1+-52776df |
|----------------|:----------------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| pidigits       | 196 ms                                                                 | 188 ms: 1.04x faster                                                         |
| nbody          | 94.4 ms                                                                | 95.1 ms: 1.01x slower                                                        |
| float          | 80.6 ms                                                                | 81.6 ms: 1.01x slower                                                        |
| Geometric mean | (ref)                                                                  | 1.01x faster                                                                 |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231016-linux-x86_64-python-f07ca27709855d4637b4-3.13.0a1+-f07ca27 | bm-20231017-linux-x86_64-brandtbucher-break_up_float_reuse-3.13.0a1+-52776df |
|----------------|:----------------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| regex_effbot   | 4.14 ms                                                                | 4.06 ms: 1.02x faster                                                        |
| regex_dna      | 218 ms                                                                 | 214 ms: 1.02x faster                                                         |
| regex_v8       | 25.5 ms                                                                | 25.6 ms: 1.01x slower                                                        |
| Geometric mean | (ref)                                                                  | 1.01x faster                                                                 |

Benchmark hidden because not significant (1): regex_compile

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231016-linux-x86_64-python-f07ca27709855d4637b4-3.13.0a1+-f07ca27 | bm-20231017-linux-x86_64-brandtbucher-break_up_float_reuse-3.13.0a1+-52776df |
|----------------------|:----------------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| unpickle             | 15.0 us                                                                | 14.3 us: 1.05x faster                                                        |
| pickle_list          | 5.13 us                                                                | 4.97 us: 1.03x faster                                                        |
| unpickle_list        | 5.10 us                                                                | 5.00 us: 1.02x faster                                                        |
| json_dumps           | 10.5 ms                                                                | 10.4 ms: 1.01x faster                                                        |
| xml_etree_generate   | 87.0 ms                                                                | 85.8 ms: 1.01x faster                                                        |
| xml_etree_process    | 59.9 ms                                                                | 59.5 ms: 1.01x faster                                                        |
| json_loads           | 27.8 us                                                                | 27.9 us: 1.01x slower                                                        |
| pickle_pure_python   | 305 us                                                                 | 309 us: 1.01x slower                                                         |
| unpickle_pure_python | 223 us                                                                 | 225 us: 1.01x slower                                                         |
| pickle               | 11.5 us                                                                | 11.7 us: 1.02x slower                                                        |
| pickle_dict          | 33.6 us                                                                | 35.6 us: 1.06x slower                                                        |
| Geometric mean       | (ref)                                                                  | 1.00x faster                                                                 |

Benchmark hidden because not significant (3): tomli_loads, xml_etree_iterparse, xml_etree_parse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231016-linux-x86_64-python-f07ca27709855d4637b4-3.13.0a1+-f07ca27 | bm-20231017-linux-x86_64-brandtbucher-break_up_float_reuse-3.13.0a1+-52776df |
|------------------------|:----------------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| python_startup         | 10.1 ms                                                                | 10.0 ms: 1.00x faster                                                        |
| python_startup_no_site | 6.85 ms                                                                | 6.82 ms: 1.00x faster                                                        |
| Geometric mean         | (ref)                                                                  | 1.00x faster                                                                 |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231016-linux-x86_64-python-f07ca27709855d4637b4-3.13.0a1+-f07ca27 | bm-20231017-linux-x86_64-brandtbucher-break_up_float_reuse-3.13.0a1+-52776df |
|-----------|:----------------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| mako      | 11.7 ms                                                                | 12.0 ms: 1.02x slower                                                        |

All benchmarks:
===============

| Benchmark                | bm-20231016-linux-x86_64-python-f07ca27709855d4637b4-3.13.0a1+-f07ca27 | bm-20231017-linux-x86_64-brandtbucher-break_up_float_reuse-3.13.0a1+-52776df |
|--------------------------|:----------------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| unpack_sequence          | 47.1 ns                                                                | 42.9 ns: 1.10x faster                                                        |
| unpickle                 | 15.0 us                                                                | 14.3 us: 1.05x faster                                                        |
| spectral_norm            | 118 ms                                                                 | 113 ms: 1.04x faster                                                         |
| pidigits                 | 196 ms                                                                 | 188 ms: 1.04x faster                                                         |
| scimark_fft              | 381 ms                                                                 | 369 ms: 1.03x faster                                                         |
| pickle_list              | 5.13 us                                                                | 4.97 us: 1.03x faster                                                        |
| scimark_sparse_mat_mult  | 4.93 ms                                                                | 4.82 ms: 1.02x faster                                                        |
| regex_effbot             | 4.14 ms                                                                | 4.06 ms: 1.02x faster                                                        |
| pyflate                  | 468 ms                                                                 | 459 ms: 1.02x faster                                                         |
| unpickle_list            | 5.10 us                                                                | 5.00 us: 1.02x faster                                                        |
| regex_dna                | 218 ms                                                                 | 214 ms: 1.02x faster                                                         |
| json_dumps               | 10.5 ms                                                                | 10.4 ms: 1.01x faster                                                        |
| asyncio_tcp              | 484 ms                                                                 | 478 ms: 1.01x faster                                                         |
| xml_etree_generate       | 87.0 ms                                                                | 85.8 ms: 1.01x faster                                                        |
| sqlglot_normalize        | 107 ms                                                                 | 106 ms: 1.01x faster                                                         |
| telco                    | 8.34 ms                                                                | 8.26 ms: 1.01x faster                                                        |
| scimark_lu               | 116 ms                                                                 | 115 ms: 1.01x faster                                                         |
| scimark_monte_carlo      | 69.2 ms                                                                | 68.6 ms: 1.01x faster                                                        |
| docutils                 | 2.67 sec                                                               | 2.64 sec: 1.01x faster                                                       |
| xml_etree_process        | 59.9 ms                                                                | 59.5 ms: 1.01x faster                                                        |
| chaos                    | 62.4 ms                                                                | 62.0 ms: 1.01x faster                                                        |
| python_startup           | 10.1 ms                                                                | 10.0 ms: 1.00x faster                                                        |
| python_startup_no_site   | 6.85 ms                                                                | 6.82 ms: 1.00x faster                                                        |
| asyncio_tcp_ssl          | 1.78 sec                                                               | 1.78 sec: 1.00x faster                                                       |
| sqlglot_optimize         | 53.7 ms                                                                | 53.6 ms: 1.00x faster                                                        |
| go                       | 143 ms                                                                 | 143 ms: 1.00x slower                                                         |
| json_loads               | 27.8 us                                                                | 27.9 us: 1.01x slower                                                        |
| create_gc_cycles         | 1.45 ms                                                                | 1.46 ms: 1.01x slower                                                        |
| regex_v8                 | 25.5 ms                                                                | 25.6 ms: 1.01x slower                                                        |
| richards                 | 48.2 ms                                                                | 48.5 ms: 1.01x slower                                                        |
| pathlib                  | 19.0 ms                                                                | 19.2 ms: 1.01x slower                                                        |
| nbody                    | 94.4 ms                                                                | 95.1 ms: 1.01x slower                                                        |
| generators               | 29.6 ms                                                                | 29.8 ms: 1.01x slower                                                        |
| coverage                 | 90.3 ms                                                                | 91.1 ms: 1.01x slower                                                        |
| comprehensions           | 20.7 us                                                                | 20.8 us: 1.01x slower                                                        |
| pickle_pure_python       | 305 us                                                                 | 309 us: 1.01x slower                                                         |
| deepcopy_memo            | 38.7 us                                                                | 39.2 us: 1.01x slower                                                        |
| pprint_safe_repr         | 744 ms                                                                 | 753 ms: 1.01x slower                                                         |
| typing_runtime_protocols | 152 us                                                                 | 154 us: 1.01x slower                                                         |
| unpickle_pure_python     | 223 us                                                                 | 225 us: 1.01x slower                                                         |
| float                    | 80.6 ms                                                                | 81.6 ms: 1.01x slower                                                        |
| richards_super           | 54.1 ms                                                                | 54.8 ms: 1.01x slower                                                        |
| fannkuch                 | 418 ms                                                                 | 424 ms: 1.01x slower                                                         |
| deepcopy                 | 352 us                                                                 | 357 us: 1.01x slower                                                         |
| hexiom                   | 6.21 ms                                                                | 6.31 ms: 1.02x slower                                                        |
| raytrace                 | 275 ms                                                                 | 280 ms: 1.02x slower                                                         |
| pickle                   | 11.5 us                                                                | 11.7 us: 1.02x slower                                                        |
| mako                     | 11.7 ms                                                                | 12.0 ms: 1.02x slower                                                        |
| mdp                      | 2.53 sec                                                               | 2.58 sec: 1.02x slower                                                       |
| nqueens                  | 79.5 ms                                                                | 81.3 ms: 1.02x slower                                                        |
| pycparser                | 1.17 sec                                                               | 1.21 sec: 1.03x slower                                                       |
| scimark_sor              | 127 ms                                                                 | 132 ms: 1.04x slower                                                         |
| pickle_dict              | 33.6 us                                                                | 35.6 us: 1.06x slower                                                        |
| gc_traversal             | 3.63 ms                                                                | 4.04 ms: 1.11x slower                                                        |
| Geometric mean           | (ref)                                                                  | 1.00x slower                                                                 |

Benchmark hidden because not significant (27): async_tree_memoization, deltablue, tornado_http, async_tree_io, sqlglot_parse, json, logging_format, mypy2, bench_thread_pool, dulwich_log, tomli_loads, coroutines, regex_compile, bench_mp_pool, async_tree_cpu_io_mixed, async_tree_none, pprint_pformat, logging_silent, meteor_contest, sqlglot_transpile, deepcopy_reduce, crypto_pyaes, xml_etree_iterparse, async_generators, logging_simple, sqlite_synth, xml_etree_parse


# HPT report

- Reliability score: 51.22% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
