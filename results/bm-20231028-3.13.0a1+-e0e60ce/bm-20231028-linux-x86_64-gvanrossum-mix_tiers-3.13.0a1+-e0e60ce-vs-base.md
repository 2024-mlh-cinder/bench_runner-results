
# Results vs. base

- fork: gvanrossum
- ref: mix_tiers
- machine: linux-x86_64
- commit hash: e0e60ce
- commit date: 2023-10-28
- overall geometric mean: 1.07x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.02x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231027-linux-x86_64-python-8a158a753c48d166ebce-3.13.0a1+-8a158a7 | bm-20231028-linux-x86_64-gvanrossum-mix_tiers-3.13.0a1+-e0e60ce |
|----------------|:----------------------------------------------------------------------:|:---------------------------------------------------------------:|
| 2to3           | 265 ms                                                                 | 290 ms: 1.10x slower                                            |
| chameleon      | 7.02 ms                                                                | 7.56 ms: 1.08x slower                                           |
| docutils       | 2.65 sec                                                               | 2.76 sec: 1.04x slower                                          |
| tornado_http   | 96.0 ms                                                                | 102 ms: 1.07x slower                                            |
| Geometric mean | (ref)                                                                  | 1.07x slower                                                    |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                 | bm-20231027-linux-x86_64-python-8a158a753c48d166ebce-3.13.0a1+-8a158a7 | bm-20231028-linux-x86_64-gvanrossum-mix_tiers-3.13.0a1+-e0e60ce |
|---------------------------|:----------------------------------------------------------------------:|:---------------------------------------------------------------:|
| async_tree_io             | 1.19 sec                                                               | 1.20 sec: 1.01x slower                                          |
| async_tree_io_tg          | 1.23 sec                                                               | 1.25 sec: 1.01x slower                                          |
| async_tree_none_tg        | 459 ms                                                                 | 465 ms: 1.01x slower                                            |
| async_tree_memoization    | 566 ms                                                                 | 577 ms: 1.02x slower                                            |
| async_tree_memoization_tg | 596 ms                                                                 | 613 ms: 1.03x slower                                            |
| Geometric mean            | (ref)                                                                  | 1.02x slower                                                    |

Benchmark hidden because not significant (3): async_tree_cpu_io_mixed, async_tree_cpu_io_mixed_tg, async_tree_none

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231027-linux-x86_64-python-8a158a753c48d166ebce-3.13.0a1+-8a158a7 | bm-20231028-linux-x86_64-gvanrossum-mix_tiers-3.13.0a1+-e0e60ce |
|----------------|:----------------------------------------------------------------------:|:---------------------------------------------------------------:|
| pidigits       | 187 ms                                                                 | 188 ms: 1.00x slower                                            |
| float          | 80.4 ms                                                                | 95.1 ms: 1.18x slower                                           |
| nbody          | 89.8 ms                                                                | 118 ms: 1.31x slower                                            |
| Geometric mean | (ref)                                                                  | 1.16x slower                                                    |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231027-linux-x86_64-python-8a158a753c48d166ebce-3.13.0a1+-8a158a7 | bm-20231028-linux-x86_64-gvanrossum-mix_tiers-3.13.0a1+-e0e60ce |
|----------------|:----------------------------------------------------------------------:|:---------------------------------------------------------------:|
| regex_v8       | 25.8 ms                                                                | 24.6 ms: 1.05x faster                                           |
| regex_effbot   | 3.71 ms                                                                | 3.58 ms: 1.04x faster                                           |
| regex_dna      | 218 ms                                                                 | 222 ms: 1.01x slower                                            |
| regex_compile  | 138 ms                                                                 | 165 ms: 1.19x slower                                            |
| Geometric mean | (ref)                                                                  | 1.03x slower                                                    |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231027-linux-x86_64-python-8a158a753c48d166ebce-3.13.0a1+-8a158a7 | bm-20231028-linux-x86_64-gvanrossum-mix_tiers-3.13.0a1+-e0e60ce |
|----------------------|:----------------------------------------------------------------------:|:---------------------------------------------------------------:|
| pickle_dict          | 34.3 us                                                                | 32.6 us: 1.05x faster                                           |
| pickle_list          | 4.95 us                                                                | 4.87 us: 1.02x faster                                           |
| pickle               | 11.2 us                                                                | 11.0 us: 1.01x faster                                           |
| json_dumps           | 10.4 ms                                                                | 10.5 ms: 1.01x slower                                           |
| pickle_pure_python   | 308 us                                                                 | 311 us: 1.01x slower                                            |
| xml_etree_process    | 59.4 ms                                                                | 60.2 ms: 1.01x slower                                           |
| xml_etree_generate   | 86.1 ms                                                                | 88.3 ms: 1.02x slower                                           |
| unpickle             | 14.7 us                                                                | 15.0 us: 1.03x slower                                           |
| unpickle_list        | 5.12 us                                                                | 5.34 us: 1.04x slower                                           |
| xml_etree_iterparse  | 105 ms                                                                 | 111 ms: 1.05x slower                                            |
| unpickle_pure_python | 222 us                                                                 | 239 us: 1.08x slower                                            |
| tomli_loads          | 2.13 sec                                                               | 2.48 sec: 1.17x slower                                          |
| Geometric mean       | (ref)                                                                  | 1.02x slower                                                    |

Benchmark hidden because not significant (2): xml_etree_parse, json_loads

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231027-linux-x86_64-python-8a158a753c48d166ebce-3.13.0a1+-8a158a7 | bm-20231028-linux-x86_64-gvanrossum-mix_tiers-3.13.0a1+-e0e60ce |
|------------------------|:----------------------------------------------------------------------:|:---------------------------------------------------------------:|
| python_startup         | 10.3 ms                                                                | 10.3 ms: 1.00x slower                                           |
| python_startup_no_site | 8.96 ms                                                                | 9.01 ms: 1.01x slower                                           |
| Geometric mean         | (ref)                                                                  | 1.00x slower                                                    |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231027-linux-x86_64-python-8a158a753c48d166ebce-3.13.0a1+-8a158a7 | bm-20231028-linux-x86_64-gvanrossum-mix_tiers-3.13.0a1+-e0e60ce |
|-----------|:----------------------------------------------------------------------:|:---------------------------------------------------------------:|
| mako      | 11.4 ms                                                                | 13.8 ms: 1.21x slower                                           |

All benchmarks:
===============

| Benchmark                 | bm-20231027-linux-x86_64-python-8a158a753c48d166ebce-3.13.0a1+-8a158a7 | bm-20231028-linux-x86_64-gvanrossum-mix_tiers-3.13.0a1+-e0e60ce |
|---------------------------|:----------------------------------------------------------------------:|:---------------------------------------------------------------:|
| pickle_dict               | 34.3 us                                                                | 32.6 us: 1.05x faster                                           |
| regex_v8                  | 25.8 ms                                                                | 24.6 ms: 1.05x faster                                           |
| regex_effbot              | 3.71 ms                                                                | 3.58 ms: 1.04x faster                                           |
| pickle_list               | 4.95 us                                                                | 4.87 us: 1.02x faster                                           |
| pickle                    | 11.2 us                                                                | 11.0 us: 1.01x faster                                           |
| create_gc_cycles          | 1.47 ms                                                                | 1.46 ms: 1.01x faster                                           |
| coverage                  | 95.0 ms                                                                | 94.3 ms: 1.01x faster                                           |
| pidigits                  | 187 ms                                                                 | 188 ms: 1.00x slower                                            |
| asyncio_tcp_ssl           | 1.78 sec                                                               | 1.79 sec: 1.00x slower                                          |
| python_startup            | 10.3 ms                                                                | 10.3 ms: 1.00x slower                                           |
| python_startup_no_site    | 8.96 ms                                                                | 9.01 ms: 1.01x slower                                           |
| json_dumps                | 10.4 ms                                                                | 10.5 ms: 1.01x slower                                           |
| pickle_pure_python        | 308 us                                                                 | 311 us: 1.01x slower                                            |
| async_tree_io             | 1.19 sec                                                               | 1.20 sec: 1.01x slower                                          |
| scimark_sor               | 128 ms                                                                 | 129 ms: 1.01x slower                                            |
| sqlite_synth              | 2.80 us                                                                | 2.83 us: 1.01x slower                                           |
| xml_etree_process         | 59.4 ms                                                                | 60.2 ms: 1.01x slower                                           |
| async_tree_io_tg          | 1.23 sec                                                               | 1.25 sec: 1.01x slower                                          |
| async_tree_none_tg        | 459 ms                                                                 | 465 ms: 1.01x slower                                            |
| regex_dna                 | 218 ms                                                                 | 222 ms: 1.01x slower                                            |
| async_tree_memoization    | 566 ms                                                                 | 577 ms: 1.02x slower                                            |
| json                      | 5.11 ms                                                                | 5.21 ms: 1.02x slower                                           |
| asyncio_tcp               | 473 ms                                                                 | 482 ms: 1.02x slower                                            |
| sqlglot_normalize         | 106 ms                                                                 | 108 ms: 1.02x slower                                            |
| xml_etree_generate        | 86.1 ms                                                                | 88.3 ms: 1.02x slower                                           |
| unpickle                  | 14.7 us                                                                | 15.0 us: 1.03x slower                                           |
| async_tree_memoization_tg | 596 ms                                                                 | 613 ms: 1.03x slower                                            |
| logging_silent            | 107 ns                                                                 | 110 ns: 1.03x slower                                            |
| deepcopy                  | 353 us                                                                 | 363 us: 1.03x slower                                            |
| async_generators          | 456 ms                                                                 | 472 ms: 1.03x slower                                            |
| sqlglot_optimize          | 53.3 ms                                                                | 55.3 ms: 1.04x slower                                           |
| spectral_norm             | 112 ms                                                                 | 117 ms: 1.04x slower                                            |
| pathlib                   | 19.2 ms                                                                | 20.0 ms: 1.04x slower                                           |
| unpickle_list             | 5.12 us                                                                | 5.34 us: 1.04x slower                                           |
| docutils                  | 2.65 sec                                                               | 2.76 sec: 1.04x slower                                          |
| dulwich_log               | 66.9 ms                                                                | 69.8 ms: 1.04x slower                                           |
| sqlglot_transpile         | 1.60 ms                                                                | 1.67 ms: 1.04x slower                                           |
| bench_thread_pool         | 814 us                                                                 | 850 us: 1.04x slower                                            |
| telco                     | 8.28 ms                                                                | 8.65 ms: 1.04x slower                                           |
| mypy2                     | 342 ms                                                                 | 358 ms: 1.05x slower                                            |
| sqlglot_parse             | 1.28 ms                                                                | 1.34 ms: 1.05x slower                                           |
| typing_runtime_protocols  | 153 us                                                                 | 161 us: 1.05x slower                                            |
| xml_etree_iterparse       | 105 ms                                                                 | 111 ms: 1.05x slower                                            |
| sympy_sum                 | 149 ms                                                                 | 157 ms: 1.05x slower                                            |
| scimark_lu                | 114 ms                                                                 | 120 ms: 1.05x slower                                            |
| mdp                       | 2.54 sec                                                               | 2.68 sec: 1.06x slower                                          |
| richards                  | 47.8 ms                                                                | 50.6 ms: 1.06x slower                                           |
| richards_super            | 54.0 ms                                                                | 57.5 ms: 1.06x slower                                           |
| tornado_http              | 96.0 ms                                                                | 102 ms: 1.07x slower                                            |
| logging_simple            | 6.01 us                                                                | 6.44 us: 1.07x slower                                           |
| sympy_str                 | 270 ms                                                                 | 289 ms: 1.07x slower                                            |
| sympy_expand              | 453 ms                                                                 | 486 ms: 1.07x slower                                            |
| unpickle_pure_python      | 222 us                                                                 | 239 us: 1.08x slower                                            |
| chameleon                 | 7.02 ms                                                                | 7.56 ms: 1.08x slower                                           |
| meteor_contest            | 107 ms                                                                 | 116 ms: 1.08x slower                                            |
| deepcopy_memo             | 39.5 us                                                                | 42.6 us: 1.08x slower                                           |
| sympy_integrate           | 19.8 ms                                                                | 21.6 ms: 1.09x slower                                           |
| 2to3                      | 265 ms                                                                 | 290 ms: 1.10x slower                                            |
| pprint_safe_repr          | 748 ms                                                                 | 820 ms: 1.10x slower                                            |
| generators                | 29.9 ms                                                                | 32.8 ms: 1.10x slower                                           |
| logging_format            | 6.57 us                                                                | 7.25 us: 1.10x slower                                           |
| pprint_pformat            | 1.52 sec                                                               | 1.69 sec: 1.11x slower                                          |
| scimark_monte_carlo       | 68.4 ms                                                                | 76.2 ms: 1.11x slower                                           |
| unpack_sequence           | 44.3 ns                                                                | 49.6 ns: 1.12x slower                                           |
| fannkuch                  | 403 ms                                                                 | 453 ms: 1.13x slower                                            |
| pyflate                   | 459 ms                                                                 | 520 ms: 1.13x slower                                            |
| go                        | 145 ms                                                                 | 165 ms: 1.14x slower                                            |
| raytrace                  | 276 ms                                                                 | 313 ms: 1.14x slower                                            |
| gc_traversal              | 3.58 ms                                                                | 4.07 ms: 1.14x slower                                           |
| scimark_fft               | 366 ms                                                                 | 424 ms: 1.16x slower                                            |
| tomli_loads               | 2.13 sec                                                               | 2.48 sec: 1.17x slower                                          |
| crypto_pyaes              | 72.4 ms                                                                | 84.9 ms: 1.17x slower                                           |
| float                     | 80.4 ms                                                                | 95.1 ms: 1.18x slower                                           |
| regex_compile             | 138 ms                                                                 | 165 ms: 1.19x slower                                            |
| mako                      | 11.4 ms                                                                | 13.8 ms: 1.21x slower                                           |
| chaos                     | 62.1 ms                                                                | 75.7 ms: 1.22x slower                                           |
| scimark_sparse_mat_mult   | 4.83 ms                                                                | 5.92 ms: 1.23x slower                                           |
| nqueens                   | 80.1 ms                                                                | 99.1 ms: 1.24x slower                                           |
| nbody                     | 89.8 ms                                                                | 118 ms: 1.31x slower                                            |
| comprehensions            | 16.5 us                                                                | 22.1 us: 1.34x slower                                           |
| deltablue                 | 3.37 ms                                                                | 4.73 ms: 1.40x slower                                           |
| hexiom                    | 6.12 ms                                                                | 8.96 ms: 1.46x slower                                           |
| Geometric mean            | (ref)                                                                  | 1.07x slower                                                    |

Benchmark hidden because not significant (10): xml_etree_parse, pycparser, deepcopy_reduce, json_loads, asyncio_websockets, bench_mp_pool, coroutines, async_tree_cpu_io_mixed, async_tree_cpu_io_mixed_tg, async_tree_none


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.03x
- 95% likely to have a slowdown of 1.03x
- 99% likely to have a slowdown of 1.02x
