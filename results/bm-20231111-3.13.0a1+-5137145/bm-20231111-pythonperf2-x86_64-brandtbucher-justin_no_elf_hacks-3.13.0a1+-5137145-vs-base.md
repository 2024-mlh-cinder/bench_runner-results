
# Results vs. base

- fork: brandtbucher
- ref: justin_no_elf_hacks
- machine: linux-x86_64
- commit hash: 5137145
- commit date: 2023-11-11
- overall geometric mean: 1.02x slower
- HPT reliability: 99.95%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231111-pythonperf2-x86_64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f | bm-20231111-pythonperf2-x86_64-brandtbucher-justin_no_elf_hacks-3.13.0a1+-5137145 |
|----------------|:----------------------------------------------------------------------------:|:---------------------------------------------------------------------------------:|
| 2to3           | 293 ms                                                                       | 299 ms: 1.02x slower                                                              |
| chameleon      | 7.31 ms                                                                      | 7.64 ms: 1.04x slower                                                             |
| docutils       | 2.85 sec                                                                     | 2.88 sec: 1.01x slower                                                            |
| Geometric mean | (ref)                                                                        | 1.02x slower                                                                      |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'asyncio':
==============================

| Benchmark                 | bm-20231111-pythonperf2-x86_64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f | bm-20231111-pythonperf2-x86_64-brandtbucher-justin_no_elf_hacks-3.13.0a1+-5137145 |
|---------------------------|:----------------------------------------------------------------------------:|:---------------------------------------------------------------------------------:|
| async_tree_io_tg          | 1.11 sec                                                                     | 1.10 sec: 1.01x faster                                                            |
| async_tree_io             | 1.09 sec                                                                     | 1.08 sec: 1.01x faster                                                            |
| async_tree_none_tg        | 443 ms                                                                       | 445 ms: 1.00x slower                                                              |
| async_tree_memoization_tg | 561 ms                                                                       | 576 ms: 1.03x slower                                                              |
| Geometric mean            | (ref)                                                                        | 1.00x slower                                                                      |

Benchmark hidden because not significant (4): async_tree_cpu_io_mixed, async_tree_memoization, async_tree_cpu_io_mixed_tg, async_tree_none

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231111-pythonperf2-x86_64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f | bm-20231111-pythonperf2-x86_64-brandtbucher-justin_no_elf_hacks-3.13.0a1+-5137145 |
|----------------|:----------------------------------------------------------------------------:|:---------------------------------------------------------------------------------:|
| float          | 79.9 ms                                                                      | 81.3 ms: 1.02x slower                                                             |
| nbody          | 85.2 ms                                                                      | 96.7 ms: 1.13x slower                                                             |
| Geometric mean | (ref)                                                                        | 1.05x slower                                                                      |

Benchmark hidden because not significant (1): pidigits

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231111-pythonperf2-x86_64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f | bm-20231111-pythonperf2-x86_64-brandtbucher-justin_no_elf_hacks-3.13.0a1+-5137145 |
|----------------|:----------------------------------------------------------------------------:|:---------------------------------------------------------------------------------:|
| regex_v8       | 26.3 ms                                                                      | 25.0 ms: 1.05x faster                                                             |
| regex_dna      | 249 ms                                                                       | 239 ms: 1.04x faster                                                              |
| regex_effbot   | 3.50 ms                                                                      | 3.46 ms: 1.01x faster                                                             |
| regex_compile  | 144 ms                                                                       | 150 ms: 1.04x slower                                                              |
| Geometric mean | (ref)                                                                        | 1.01x faster                                                                      |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231111-pythonperf2-x86_64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f | bm-20231111-pythonperf2-x86_64-brandtbucher-justin_no_elf_hacks-3.13.0a1+-5137145 |
|----------------------|:----------------------------------------------------------------------------:|:---------------------------------------------------------------------------------:|
| xml_etree_parse      | 152 ms                                                                       | 146 ms: 1.04x faster                                                              |
| xml_etree_iterparse  | 107 ms                                                                       | 103 ms: 1.04x faster                                                              |
| unpickle_list        | 4.97 us                                                                      | 4.80 us: 1.04x faster                                                             |
| pickle_pure_python   | 323 us                                                                       | 315 us: 1.03x faster                                                              |
| json_dumps           | 10.5 ms                                                                      | 10.4 ms: 1.02x faster                                                             |
| json_loads           | 24.6 us                                                                      | 24.4 us: 1.01x faster                                                             |
| pickle_list          | 4.48 us                                                                      | 4.44 us: 1.01x faster                                                             |
| unpickle             | 14.4 us                                                                      | 14.2 us: 1.01x faster                                                             |
| xml_etree_process    | 58.3 ms                                                                      | 58.0 ms: 1.00x faster                                                             |
| xml_etree_generate   | 85.2 ms                                                                      | 85.7 ms: 1.01x slower                                                             |
| tomli_loads          | 2.22 sec                                                                     | 2.40 sec: 1.08x slower                                                            |
| unpickle_pure_python | 223 us                                                                       | 248 us: 1.11x slower                                                              |
| Geometric mean       | (ref)                                                                        | 1.00x faster                                                                      |

Benchmark hidden because not significant (2): pickle_dict, pickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231111-pythonperf2-x86_64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f | bm-20231111-pythonperf2-x86_64-brandtbucher-justin_no_elf_hacks-3.13.0a1+-5137145 |
|------------------------|:----------------------------------------------------------------------------:|:---------------------------------------------------------------------------------:|
| python_startup         | 12.8 ms                                                                      | 12.9 ms: 1.00x slower                                                             |
| python_startup_no_site | 11.3 ms                                                                      | 11.4 ms: 1.01x slower                                                             |
| Geometric mean         | (ref)                                                                        | 1.01x slower                                                                      |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231111-pythonperf2-x86_64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f | bm-20231111-pythonperf2-x86_64-brandtbucher-justin_no_elf_hacks-3.13.0a1+-5137145 |
|-----------|:----------------------------------------------------------------------------:|:---------------------------------------------------------------------------------:|
| mako      | 10.2 ms                                                                      | 11.2 ms: 1.10x slower                                                             |

All benchmarks:
===============

| Benchmark                 | bm-20231111-pythonperf2-x86_64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f | bm-20231111-pythonperf2-x86_64-brandtbucher-justin_no_elf_hacks-3.13.0a1+-5137145 |
|---------------------------|:----------------------------------------------------------------------------:|:---------------------------------------------------------------------------------:|
| gc_traversal              | 3.99 ms                                                                      | 3.64 ms: 1.10x faster                                                             |
| richards                  | 56.2 ms                                                                      | 52.1 ms: 1.08x faster                                                             |
| richards_super            | 62.4 ms                                                                      | 58.3 ms: 1.07x faster                                                             |
| create_gc_cycles          | 1.60 ms                                                                      | 1.51 ms: 1.06x faster                                                             |
| deepcopy                  | 377 us                                                                       | 359 us: 1.05x faster                                                              |
| regex_v8                  | 26.3 ms                                                                      | 25.0 ms: 1.05x faster                                                             |
| unpack_sequence           | 47.4 ns                                                                      | 45.5 ns: 1.04x faster                                                             |
| regex_dna                 | 249 ms                                                                       | 239 ms: 1.04x faster                                                              |
| xml_etree_parse           | 152 ms                                                                       | 146 ms: 1.04x faster                                                              |
| json                      | 5.24 ms                                                                      | 5.05 ms: 1.04x faster                                                             |
| xml_etree_iterparse       | 107 ms                                                                       | 103 ms: 1.04x faster                                                              |
| unpickle_list             | 4.97 us                                                                      | 4.80 us: 1.04x faster                                                             |
| deepcopy_reduce           | 3.33 us                                                                      | 3.23 us: 1.03x faster                                                             |
| scimark_sor               | 153 ms                                                                       | 149 ms: 1.03x faster                                                              |
| pickle_pure_python        | 323 us                                                                       | 315 us: 1.03x faster                                                              |
| deepcopy_memo             | 37.9 us                                                                      | 37.0 us: 1.02x faster                                                             |
| pyflate                   | 520 ms                                                                       | 509 ms: 1.02x faster                                                              |
| json_dumps                | 10.5 ms                                                                      | 10.4 ms: 1.02x faster                                                             |
| json_loads                | 24.6 us                                                                      | 24.4 us: 1.01x faster                                                             |
| regex_effbot              | 3.50 ms                                                                      | 3.46 ms: 1.01x faster                                                             |
| async_tree_io_tg          | 1.11 sec                                                                     | 1.10 sec: 1.01x faster                                                            |
| async_tree_io             | 1.09 sec                                                                     | 1.08 sec: 1.01x faster                                                            |
| pickle_list               | 4.48 us                                                                      | 4.44 us: 1.01x faster                                                             |
| unpickle                  | 14.4 us                                                                      | 14.2 us: 1.01x faster                                                             |
| xml_etree_process         | 58.3 ms                                                                      | 58.0 ms: 1.00x faster                                                             |
| coverage                  | 83.4 ms                                                                      | 83.1 ms: 1.00x faster                                                             |
| spectral_norm             | 90.9 ms                                                                      | 91.1 ms: 1.00x slower                                                             |
| python_startup            | 12.8 ms                                                                      | 12.9 ms: 1.00x slower                                                             |
| async_tree_none_tg        | 443 ms                                                                       | 445 ms: 1.00x slower                                                              |
| xml_etree_generate        | 85.2 ms                                                                      | 85.7 ms: 1.01x slower                                                             |
| generators                | 35.4 ms                                                                      | 35.7 ms: 1.01x slower                                                             |
| python_startup_no_site    | 11.3 ms                                                                      | 11.4 ms: 1.01x slower                                                             |
| sqlglot_optimize          | 58.5 ms                                                                      | 59.0 ms: 1.01x slower                                                             |
| docutils                  | 2.85 sec                                                                     | 2.88 sec: 1.01x slower                                                            |
| asyncio_websockets        | 385 ms                                                                       | 390 ms: 1.01x slower                                                              |
| sympy_str                 | 290 ms                                                                       | 294 ms: 1.01x slower                                                              |
| float                     | 79.9 ms                                                                      | 81.3 ms: 1.02x slower                                                             |
| mypy2                     | 367 ms                                                                       | 374 ms: 1.02x slower                                                              |
| 2to3                      | 293 ms                                                                       | 299 ms: 1.02x slower                                                              |
| bench_thread_pool         | 953 us                                                                       | 976 us: 1.02x slower                                                              |
| scimark_sparse_mat_mult   | 4.40 ms                                                                      | 4.51 ms: 1.02x slower                                                             |
| coroutines                | 22.2 ms                                                                      | 22.7 ms: 1.02x slower                                                             |
| logging_format            | 7.26 us                                                                      | 7.44 us: 1.03x slower                                                             |
| pprint_safe_repr          | 813 ms                                                                       | 836 ms: 1.03x slower                                                              |
| sympy_sum                 | 150 ms                                                                       | 155 ms: 1.03x slower                                                              |
| pprint_pformat            | 1.66 sec                                                                     | 1.71 sec: 1.03x slower                                                            |
| async_tree_memoization_tg | 561 ms                                                                       | 576 ms: 1.03x slower                                                              |
| mdp                       | 2.54 sec                                                                     | 2.62 sec: 1.03x slower                                                            |
| meteor_contest            | 129 ms                                                                       | 133 ms: 1.04x slower                                                              |
| pycparser                 | 1.29 sec                                                                     | 1.34 sec: 1.04x slower                                                            |
| go                        | 169 ms                                                                       | 176 ms: 1.04x slower                                                              |
| regex_compile             | 144 ms                                                                       | 150 ms: 1.04x slower                                                              |
| telco                     | 8.07 ms                                                                      | 8.42 ms: 1.04x slower                                                             |
| chameleon                 | 7.31 ms                                                                      | 7.64 ms: 1.04x slower                                                             |
| sympy_integrate           | 22.9 ms                                                                      | 24.0 ms: 1.05x slower                                                             |
| fannkuch                  | 401 ms                                                                       | 423 ms: 1.05x slower                                                              |
| raytrace                  | 271 ms                                                                       | 285 ms: 1.05x slower                                                              |
| deltablue                 | 3.59 ms                                                                      | 3.80 ms: 1.06x slower                                                             |
| scimark_lu                | 99.1 ms                                                                      | 105 ms: 1.06x slower                                                              |
| typing_runtime_protocols  | 121 us                                                                       | 129 us: 1.06x slower                                                              |
| async_generators          | 359 ms                                                                       | 382 ms: 1.07x slower                                                              |
| crypto_pyaes              | 72.5 ms                                                                      | 78.0 ms: 1.08x slower                                                             |
| tomli_loads               | 2.22 sec                                                                     | 2.40 sec: 1.08x slower                                                            |
| scimark_monte_carlo       | 68.2 ms                                                                      | 73.9 ms: 1.08x slower                                                             |
| chaos                     | 61.1 ms                                                                      | 67.0 ms: 1.10x slower                                                             |
| mako                      | 10.2 ms                                                                      | 11.2 ms: 1.10x slower                                                             |
| scimark_fft               | 314 ms                                                                       | 345 ms: 1.10x slower                                                              |
| unpickle_pure_python      | 223 us                                                                       | 248 us: 1.11x slower                                                              |
| nbody                     | 85.2 ms                                                                      | 96.7 ms: 1.13x slower                                                             |
| nqueens                   | 87.7 ms                                                                      | 103 ms: 1.18x slower                                                              |
| hexiom                    | 6.50 ms                                                                      | 8.19 ms: 1.26x slower                                                             |
| comprehensions            | 16.4 us                                                                      | 21.5 us: 1.31x slower                                                             |
| Geometric mean            | (ref)                                                                        | 1.02x slower                                                                      |

Benchmark hidden because not significant (20): pickle_dict, async_tree_cpu_io_mixed, async_tree_memoization, async_tree_cpu_io_mixed_tg, sqlglot_transpile, sqlglot_parse, dulwich_log, asyncio_tcp, sqlite_synth, logging_simple, asyncio_tcp_ssl, pathlib, pidigits, sympy_expand, pickle, sqlglot_normalize, async_tree_none, logging_silent, tornado_http, bench_mp_pool


# HPT report

- Reliability score: 99.95% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
