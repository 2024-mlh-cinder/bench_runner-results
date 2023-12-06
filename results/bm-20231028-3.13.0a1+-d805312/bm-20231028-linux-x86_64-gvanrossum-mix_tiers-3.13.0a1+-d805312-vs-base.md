
# Results vs. base

- fork: gvanrossum
- ref: mix_tiers
- machine: linux-x86_64
- commit hash: d805312
- commit date: 2023-10-28
- overall geometric mean: 1.00x slower
- HPT reliability: 85.08%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231027-linux-x86_64-python-8a158a753c48d166ebce-3.13.0a1+-8a158a7 | bm-20231028-linux-x86_64-gvanrossum-mix_tiers-3.13.0a1+-d805312 |
|----------------|:----------------------------------------------------------------------:|:---------------------------------------------------------------:|
| 2to3           | 265 ms                                                                 | 267 ms: 1.01x slower                                            |
| docutils       | 2.65 sec                                                               | 2.66 sec: 1.00x slower                                          |
| Geometric mean | (ref)                                                                  | 1.00x slower                                                    |

Benchmark hidden because not significant (2): chameleon, tornado_http

Benchmarks with tag 'asyncio':
==============================

| Benchmark        | bm-20231027-linux-x86_64-python-8a158a753c48d166ebce-3.13.0a1+-8a158a7 | bm-20231028-linux-x86_64-gvanrossum-mix_tiers-3.13.0a1+-d805312 |
|------------------|:----------------------------------------------------------------------:|:---------------------------------------------------------------:|
| async_tree_io_tg | 1.23 sec                                                               | 1.23 sec: 1.00x faster                                          |
| async_tree_io    | 1.19 sec                                                               | 1.19 sec: 1.00x faster                                          |
| Geometric mean   | (ref)                                                                  | 1.00x faster                                                    |

Benchmark hidden because not significant (6): async_tree_cpu_io_mixed, async_tree_cpu_io_mixed_tg, async_tree_none, async_tree_memoization, async_tree_memoization_tg, async_tree_none_tg

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231027-linux-x86_64-python-8a158a753c48d166ebce-3.13.0a1+-8a158a7 | bm-20231028-linux-x86_64-gvanrossum-mix_tiers-3.13.0a1+-d805312 |
|----------------|:----------------------------------------------------------------------:|:---------------------------------------------------------------:|
| float          | 80.4 ms                                                                | 82.0 ms: 1.02x slower                                           |
| nbody          | 89.8 ms                                                                | 92.8 ms: 1.03x slower                                           |
| pidigits       | 187 ms                                                                 | 195 ms: 1.04x slower                                            |
| Geometric mean | (ref)                                                                  | 1.03x slower                                                    |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231027-linux-x86_64-python-8a158a753c48d166ebce-3.13.0a1+-8a158a7 | bm-20231028-linux-x86_64-gvanrossum-mix_tiers-3.13.0a1+-d805312 |
|----------------|:----------------------------------------------------------------------:|:---------------------------------------------------------------:|
| regex_v8       | 25.8 ms                                                                | 25.4 ms: 1.02x faster                                           |
| regex_dna      | 218 ms                                                                 | 217 ms: 1.01x faster                                            |
| regex_effbot   | 3.71 ms                                                                | 3.76 ms: 1.01x slower                                           |
| Geometric mean | (ref)                                                                  | 1.00x faster                                                    |

Benchmark hidden because not significant (1): regex_compile

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231027-linux-x86_64-python-8a158a753c48d166ebce-3.13.0a1+-8a158a7 | bm-20231028-linux-x86_64-gvanrossum-mix_tiers-3.13.0a1+-d805312 |
|----------------------|:----------------------------------------------------------------------:|:---------------------------------------------------------------:|
| pickle_dict          | 34.3 us                                                                | 33.4 us: 1.03x faster                                           |
| unpickle             | 14.7 us                                                                | 14.5 us: 1.01x faster                                           |
| pickle_pure_python   | 308 us                                                                 | 305 us: 1.01x faster                                            |
| unpickle_pure_python | 222 us                                                                 | 221 us: 1.00x faster                                            |
| xml_etree_process    | 59.4 ms                                                                | 59.6 ms: 1.00x slower                                           |
| xml_etree_generate   | 86.1 ms                                                                | 86.7 ms: 1.01x slower                                           |
| xml_etree_iterparse  | 105 ms                                                                 | 106 ms: 1.01x slower                                            |
| pickle               | 11.2 us                                                                | 11.3 us: 1.01x slower                                           |
| pickle_list          | 4.95 us                                                                | 4.99 us: 1.01x slower                                           |
| json_dumps           | 10.4 ms                                                                | 10.5 ms: 1.01x slower                                           |
| tomli_loads          | 2.13 sec                                                               | 2.15 sec: 1.01x slower                                          |
| Geometric mean       | (ref)                                                                  | 1.00x slower                                                    |

Benchmark hidden because not significant (3): unpickle_list, xml_etree_parse, json_loads

Benchmarks with tag 'startup':
==============================

| Benchmark      | bm-20231027-linux-x86_64-python-8a158a753c48d166ebce-3.13.0a1+-8a158a7 | bm-20231028-linux-x86_64-gvanrossum-mix_tiers-3.13.0a1+-d805312 |
|----------------|:----------------------------------------------------------------------:|:---------------------------------------------------------------:|
| python_startup | 10.3 ms                                                                | 10.3 ms: 1.00x slower                                           |
| Geometric mean | (ref)                                                                  | 1.00x slower                                                    |

Benchmark hidden because not significant (1): python_startup_no_site

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231027-linux-x86_64-python-8a158a753c48d166ebce-3.13.0a1+-8a158a7 | bm-20231028-linux-x86_64-gvanrossum-mix_tiers-3.13.0a1+-d805312 |
|-----------|:----------------------------------------------------------------------:|:---------------------------------------------------------------:|
| mako      | 11.4 ms                                                                | 11.4 ms: 1.01x faster                                           |

All benchmarks:
===============

| Benchmark                | bm-20231027-linux-x86_64-python-8a158a753c48d166ebce-3.13.0a1+-8a158a7 | bm-20231028-linux-x86_64-gvanrossum-mix_tiers-3.13.0a1+-d805312 |
|--------------------------|:----------------------------------------------------------------------:|:---------------------------------------------------------------:|
| unpack_sequence          | 44.3 ns                                                                | 42.6 ns: 1.04x faster                                           |
| pycparser                | 1.21 sec                                                               | 1.17 sec: 1.03x faster                                          |
| pickle_dict              | 34.3 us                                                                | 33.4 us: 1.03x faster                                           |
| coroutines               | 22.9 ms                                                                | 22.5 ms: 1.02x faster                                           |
| regex_v8                 | 25.8 ms                                                                | 25.4 ms: 1.02x faster                                           |
| pathlib                  | 19.2 ms                                                                | 19.0 ms: 1.01x faster                                           |
| logging_simple           | 6.01 us                                                                | 5.95 us: 1.01x faster                                           |
| sympy_str                | 270 ms                                                                 | 267 ms: 1.01x faster                                            |
| unpickle                 | 14.7 us                                                                | 14.5 us: 1.01x faster                                           |
| pickle_pure_python       | 308 us                                                                 | 305 us: 1.01x faster                                            |
| regex_dna                | 218 ms                                                                 | 217 ms: 1.01x faster                                            |
| logging_format           | 6.57 us                                                                | 6.52 us: 1.01x faster                                           |
| mako                     | 11.4 ms                                                                | 11.4 ms: 1.01x faster                                           |
| generators               | 29.9 ms                                                                | 29.7 ms: 1.00x faster                                           |
| sqlglot_normalize        | 106 ms                                                                 | 106 ms: 1.00x faster                                            |
| async_tree_io_tg         | 1.23 sec                                                               | 1.23 sec: 1.00x faster                                          |
| go                       | 145 ms                                                                 | 145 ms: 1.00x faster                                            |
| unpickle_pure_python     | 222 us                                                                 | 221 us: 1.00x faster                                            |
| deltablue                | 3.37 ms                                                                | 3.36 ms: 1.00x faster                                           |
| chaos                    | 62.1 ms                                                                | 61.9 ms: 1.00x faster                                           |
| raytrace                 | 276 ms                                                                 | 275 ms: 1.00x faster                                            |
| async_tree_io            | 1.19 sec                                                               | 1.19 sec: 1.00x faster                                          |
| dulwich_log              | 66.9 ms                                                                | 66.7 ms: 1.00x faster                                           |
| python_startup           | 10.3 ms                                                                | 10.3 ms: 1.00x slower                                           |
| sqlglot_optimize         | 53.3 ms                                                                | 53.5 ms: 1.00x slower                                           |
| docutils                 | 2.65 sec                                                               | 2.66 sec: 1.00x slower                                          |
| create_gc_cycles         | 1.47 ms                                                                | 1.48 ms: 1.00x slower                                           |
| xml_etree_process        | 59.4 ms                                                                | 59.6 ms: 1.00x slower                                           |
| xml_etree_generate       | 86.1 ms                                                                | 86.7 ms: 1.01x slower                                           |
| scimark_monte_carlo      | 68.4 ms                                                                | 68.9 ms: 1.01x slower                                           |
| async_generators         | 456 ms                                                                 | 460 ms: 1.01x slower                                            |
| deepcopy_memo            | 39.5 us                                                                | 39.8 us: 1.01x slower                                           |
| xml_etree_iterparse      | 105 ms                                                                 | 106 ms: 1.01x slower                                            |
| 2to3                     | 265 ms                                                                 | 267 ms: 1.01x slower                                            |
| asyncio_tcp              | 473 ms                                                                 | 477 ms: 1.01x slower                                            |
| pickle                   | 11.2 us                                                                | 11.3 us: 1.01x slower                                           |
| pickle_list              | 4.95 us                                                                | 4.99 us: 1.01x slower                                           |
| json_dumps               | 10.4 ms                                                                | 10.5 ms: 1.01x slower                                           |
| fannkuch                 | 403 ms                                                                 | 407 ms: 1.01x slower                                            |
| tomli_loads              | 2.13 sec                                                               | 2.15 sec: 1.01x slower                                          |
| deepcopy                 | 353 us                                                                 | 357 us: 1.01x slower                                            |
| pprint_safe_repr         | 748 ms                                                                 | 757 ms: 1.01x slower                                            |
| crypto_pyaes             | 72.4 ms                                                                | 73.3 ms: 1.01x slower                                           |
| regex_effbot             | 3.71 ms                                                                | 3.76 ms: 1.01x slower                                           |
| nqueens                  | 80.1 ms                                                                | 81.3 ms: 1.01x slower                                           |
| telco                    | 8.28 ms                                                                | 8.40 ms: 1.01x slower                                           |
| sqlite_synth             | 2.80 us                                                                | 2.84 us: 1.02x slower                                           |
| pprint_pformat           | 1.52 sec                                                               | 1.54 sec: 1.02x slower                                          |
| typing_runtime_protocols | 153 us                                                                 | 156 us: 1.02x slower                                            |
| meteor_contest           | 107 ms                                                                 | 109 ms: 1.02x slower                                            |
| comprehensions           | 16.5 us                                                                | 16.8 us: 1.02x slower                                           |
| scimark_lu               | 114 ms                                                                 | 116 ms: 1.02x slower                                            |
| float                    | 80.4 ms                                                                | 82.0 ms: 1.02x slower                                           |
| richards_super           | 54.0 ms                                                                | 55.2 ms: 1.02x slower                                           |
| hexiom                   | 6.12 ms                                                                | 6.28 ms: 1.03x slower                                           |
| scimark_fft              | 366 ms                                                                 | 377 ms: 1.03x slower                                            |
| richards                 | 47.8 ms                                                                | 49.4 ms: 1.03x slower                                           |
| nbody                    | 89.8 ms                                                                | 92.8 ms: 1.03x slower                                           |
| pidigits                 | 187 ms                                                                 | 195 ms: 1.04x slower                                            |
| scimark_sparse_mat_mult  | 4.83 ms                                                                | 5.03 ms: 1.04x slower                                           |
| pyflate                  | 459 ms                                                                 | 480 ms: 1.04x slower                                            |
| scimark_sor              | 128 ms                                                                 | 134 ms: 1.05x slower                                            |
| gc_traversal             | 3.58 ms                                                                | 3.94 ms: 1.10x slower                                           |
| Geometric mean           | (ref)                                                                  | 1.00x slower                                                    |

Benchmark hidden because not significant (29): async_tree_cpu_io_mixed, mypy2, chameleon, async_tree_cpu_io_mixed_tg, sympy_sum, tornado_http, sqlglot_parse, unpickle_list, async_tree_none, async_tree_memoization, xml_etree_parse, mdp, coverage, bench_mp_pool, asyncio_tcp_ssl, asyncio_websockets, async_tree_memoization_tg, sqlglot_transpile, sympy_expand, async_tree_none_tg, python_startup_no_site, bench_thread_pool, json_loads, logging_silent, sympy_integrate, deepcopy_reduce, json, spectral_norm, regex_compile


# HPT report

- Reliability score: 85.08% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
