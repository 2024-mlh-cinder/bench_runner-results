
# Results vs. 3.12.0

- fork: brandtbucher
- ref: justin_no_elf_hacks
- machine: linux-x86_64
- commit hash: 5137145
- commit date: 2023-11-11
- overall geometric mean: 1.03x slower \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231111-pythonperf2-x86_64-brandtbucher-justin_no_elf_hacks-3.13.0a1+-5137145 |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------------:|
| 2to3           | 285 ms                                                       | 299 ms: 1.05x slower                                                              |
| chameleon      | 7.27 ms                                                      | 7.64 ms: 1.05x slower                                                             |
| docutils       | 2.89 sec                                                     | 2.88 sec: 1.00x faster                                                            |
| Geometric mean | (ref)                                                        | 1.02x slower                                                                      |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231111-pythonperf2-x86_64-brandtbucher-justin_no_elf_hacks-3.13.0a1+-5137145 |
|----------------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------------:|
| async_tree_none            | 459 ms                                                       | 438 ms: 1.05x faster                                                              |
| async_tree_memoization     | 554 ms                                                       | 549 ms: 1.01x faster                                                              |
| async_tree_none_tg         | 440 ms                                                       | 445 ms: 1.01x slower                                                              |
| async_tree_cpu_io_mixed_tg | 706 ms                                                       | 719 ms: 1.02x slower                                                              |
| async_tree_io              | 1.06 sec                                                     | 1.08 sec: 1.02x slower                                                            |
| async_tree_io_tg           | 1.07 sec                                                     | 1.10 sec: 1.03x slower                                                            |
| async_tree_memoization_tg  | 554 ms                                                       | 576 ms: 1.04x slower                                                              |
| Geometric mean             | (ref)                                                        | 1.01x slower                                                                      |

Benchmark hidden because not significant (1): async_tree_cpu_io_mixed

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231111-pythonperf2-x86_64-brandtbucher-justin_no_elf_hacks-3.13.0a1+-5137145 |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------------:|
| pidigits       | 264 ms                                                       | 265 ms: 1.00x slower                                                              |
| nbody          | 88.2 ms                                                      | 96.7 ms: 1.10x slower                                                             |
| Geometric mean | (ref)                                                        | 1.03x slower                                                                      |

Benchmark hidden because not significant (1): float

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231111-pythonperf2-x86_64-brandtbucher-justin_no_elf_hacks-3.13.0a1+-5137145 |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------------:|
| regex_effbot   | 3.61 ms                                                      | 3.46 ms: 1.04x faster                                                             |
| regex_dna      | 240 ms                                                       | 239 ms: 1.00x faster                                                              |
| regex_v8       | 24.4 ms                                                      | 25.0 ms: 1.03x slower                                                             |
| regex_compile  | 145 ms                                                       | 150 ms: 1.04x slower                                                              |
| Geometric mean | (ref)                                                        | 1.00x slower                                                                      |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231111-pythonperf2-x86_64-brandtbucher-justin_no_elf_hacks-3.13.0a1+-5137145 |
|----------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------------:|
| unpickle             | 15.3 us                                                      | 14.2 us: 1.08x faster                                                             |
| pickle_pure_python   | 319 us                                                       | 315 us: 1.02x faster                                                              |
| xml_etree_parse      | 147 ms                                                       | 146 ms: 1.01x faster                                                              |
| xml_etree_process    | 58.3 ms                                                      | 58.0 ms: 1.00x faster                                                             |
| xml_etree_generate   | 85.3 ms                                                      | 85.7 ms: 1.00x slower                                                             |
| json_dumps           | 10.3 ms                                                      | 10.4 ms: 1.01x slower                                                             |
| pickle               | 10.0 us                                                      | 10.2 us: 1.02x slower                                                             |
| unpickle_list        | 4.65 us                                                      | 4.80 us: 1.03x slower                                                             |
| pickle_list          | 4.22 us                                                      | 4.44 us: 1.05x slower                                                             |
| pickle_dict          | 32.0 us                                                      | 33.8 us: 1.06x slower                                                             |
| tomli_loads          | 2.17 sec                                                     | 2.40 sec: 1.11x slower                                                            |
| unpickle_pure_python | 210 us                                                       | 248 us: 1.18x slower                                                              |
| Geometric mean       | (ref)                                                        | 1.02x slower                                                                      |

Benchmark hidden because not significant (2): xml_etree_iterparse, json_loads

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231111-pythonperf2-x86_64-brandtbucher-justin_no_elf_hacks-3.13.0a1+-5137145 |
|------------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------------:|
| python_startup         | 11.7 ms                                                      | 12.9 ms: 1.10x slower                                                             |
| python_startup_no_site | 8.67 ms                                                      | 11.4 ms: 1.31x slower                                                             |
| Geometric mean         | (ref)                                                        | 1.20x slower                                                                      |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231111-pythonperf2-x86_64-brandtbucher-justin_no_elf_hacks-3.13.0a1+-5137145 |
|-----------|:------------------------------------------------------------:|:---------------------------------------------------------------------------------:|
| mako      | 10.1 ms                                                      | 11.2 ms: 1.11x slower                                                             |

All benchmarks:
===============

| Benchmark                  | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231111-pythonperf2-x86_64-brandtbucher-justin_no_elf_hacks-3.13.0a1+-5137145 |
|----------------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------------:|
| unpack_sequence            | 54.5 ns                                                      | 45.5 ns: 1.20x faster                                                             |
| typing_runtime_protocols   | 150 us                                                       | 129 us: 1.17x faster                                                              |
| unpickle                   | 15.3 us                                                      | 14.2 us: 1.08x faster                                                             |
| crypto_pyaes               | 82.4 ms                                                      | 78.0 ms: 1.06x faster                                                             |
| deepcopy_reduce            | 3.41 us                                                      | 3.23 us: 1.06x faster                                                             |
| raytrace                   | 301 ms                                                       | 285 ms: 1.05x faster                                                              |
| sympy_sum                  | 163 ms                                                       | 155 ms: 1.05x faster                                                              |
| async_tree_none            | 459 ms                                                       | 438 ms: 1.05x faster                                                              |
| generators                 | 37.3 ms                                                      | 35.7 ms: 1.05x faster                                                             |
| regex_effbot               | 3.61 ms                                                      | 3.46 ms: 1.04x faster                                                             |
| create_gc_cycles           | 1.58 ms                                                      | 1.51 ms: 1.04x faster                                                             |
| sympy_str                  | 305 ms                                                       | 294 ms: 1.04x faster                                                              |
| asyncio_tcp                | 380 ms                                                       | 366 ms: 1.04x faster                                                              |
| deepcopy                   | 371 us                                                       | 359 us: 1.04x faster                                                              |
| spectral_norm              | 93.9 ms                                                      | 91.1 ms: 1.03x faster                                                             |
| sqlglot_normalize          | 119 ms                                                       | 116 ms: 1.02x faster                                                              |
| json                       | 5.17 ms                                                      | 5.05 ms: 1.02x faster                                                             |
| gc_traversal               | 3.70 ms                                                      | 3.64 ms: 1.02x faster                                                             |
| coroutines                 | 23.1 ms                                                      | 22.7 ms: 1.02x faster                                                             |
| sqlite_synth               | 2.72 us                                                      | 2.68 us: 1.02x faster                                                             |
| pickle_pure_python         | 319 us                                                       | 315 us: 1.02x faster                                                              |
| comprehensions             | 21.8 us                                                      | 21.5 us: 1.01x faster                                                             |
| async_tree_memoization     | 554 ms                                                       | 549 ms: 1.01x faster                                                              |
| async_generators           | 385 ms                                                       | 382 ms: 1.01x faster                                                              |
| xml_etree_parse            | 147 ms                                                       | 146 ms: 1.01x faster                                                              |
| xml_etree_process          | 58.3 ms                                                      | 58.0 ms: 1.00x faster                                                             |
| regex_dna                  | 240 ms                                                       | 239 ms: 1.00x faster                                                              |
| docutils                   | 2.89 sec                                                     | 2.88 sec: 1.00x faster                                                            |
| pidigits                   | 264 ms                                                       | 265 ms: 1.00x slower                                                              |
| xml_etree_generate         | 85.3 ms                                                      | 85.7 ms: 1.00x slower                                                             |
| sympy_expand               | 492 ms                                                       | 494 ms: 1.00x slower                                                              |
| logging_simple             | 6.64 us                                                      | 6.68 us: 1.01x slower                                                             |
| asyncio_tcp_ssl            | 1.57 sec                                                     | 1.58 sec: 1.01x slower                                                            |
| asyncio_websockets         | 386 ms                                                       | 390 ms: 1.01x slower                                                              |
| sqlglot_transpile          | 1.80 ms                                                      | 1.82 ms: 1.01x slower                                                             |
| sqlglot_optimize           | 58.4 ms                                                      | 59.0 ms: 1.01x slower                                                             |
| json_dumps                 | 10.3 ms                                                      | 10.4 ms: 1.01x slower                                                             |
| async_tree_none_tg         | 440 ms                                                       | 445 ms: 1.01x slower                                                              |
| deepcopy_memo              | 36.6 us                                                      | 37.0 us: 1.01x slower                                                             |
| async_tree_cpu_io_mixed_tg | 706 ms                                                       | 719 ms: 1.02x slower                                                              |
| pickle                     | 10.0 us                                                      | 10.2 us: 1.02x slower                                                             |
| bench_thread_pool          | 956 us                                                       | 976 us: 1.02x slower                                                              |
| logging_format             | 7.29 us                                                      | 7.44 us: 1.02x slower                                                             |
| mypy2                      | 365 ms                                                       | 374 ms: 1.02x slower                                                              |
| async_tree_io              | 1.06 sec                                                     | 1.08 sec: 1.02x slower                                                            |
| mdp                        | 2.56 sec                                                     | 2.62 sec: 1.02x slower                                                            |
| async_tree_io_tg           | 1.07 sec                                                     | 1.10 sec: 1.03x slower                                                            |
| regex_v8                   | 24.4 ms                                                      | 25.0 ms: 1.03x slower                                                             |
| pycparser                  | 1.29 sec                                                     | 1.34 sec: 1.03x slower                                                            |
| unpickle_list              | 4.65 us                                                      | 4.80 us: 1.03x slower                                                             |
| pprint_safe_repr           | 808 ms                                                       | 836 ms: 1.03x slower                                                              |
| logging_silent             | 93.3 ns                                                      | 96.8 ns: 1.04x slower                                                             |
| regex_compile              | 145 ms                                                       | 150 ms: 1.04x slower                                                              |
| pprint_pformat             | 1.64 sec                                                     | 1.71 sec: 1.04x slower                                                            |
| async_tree_memoization_tg  | 554 ms                                                       | 576 ms: 1.04x slower                                                              |
| dulwich_log                | 64.9 ms                                                      | 67.8 ms: 1.04x slower                                                             |
| chaos                      | 64.1 ms                                                      | 67.0 ms: 1.05x slower                                                             |
| 2to3                       | 285 ms                                                       | 299 ms: 1.05x slower                                                              |
| pathlib                    | 18.7 ms                                                      | 19.7 ms: 1.05x slower                                                             |
| chameleon                  | 7.27 ms                                                      | 7.64 ms: 1.05x slower                                                             |
| pickle_list                | 4.22 us                                                      | 4.44 us: 1.05x slower                                                             |
| meteor_contest             | 126 ms                                                       | 133 ms: 1.05x slower                                                              |
| pickle_dict                | 32.0 us                                                      | 33.8 us: 1.06x slower                                                             |
| scimark_monte_carlo        | 69.5 ms                                                      | 73.9 ms: 1.06x slower                                                             |
| scimark_lu                 | 98.6 ms                                                      | 105 ms: 1.06x slower                                                              |
| nbody                      | 88.2 ms                                                      | 96.7 ms: 1.10x slower                                                             |
| python_startup             | 11.7 ms                                                      | 12.9 ms: 1.10x slower                                                             |
| mako                       | 10.1 ms                                                      | 11.2 ms: 1.11x slower                                                             |
| tomli_loads                | 2.17 sec                                                     | 2.40 sec: 1.11x slower                                                            |
| bench_mp_pool              | 4.96 ms                                                      | 5.60 ms: 1.13x slower                                                             |
| scimark_fft                | 303 ms                                                       | 345 ms: 1.14x slower                                                              |
| nqueens                    | 90.1 ms                                                      | 103 ms: 1.15x slower                                                              |
| richards_super             | 50.8 ms                                                      | 58.3 ms: 1.15x slower                                                             |
| pyflate                    | 442 ms                                                       | 509 ms: 1.15x slower                                                              |
| richards                   | 45.1 ms                                                      | 52.1 ms: 1.16x slower                                                             |
| fannkuch                   | 362 ms                                                       | 423 ms: 1.17x slower                                                              |
| deltablue                  | 3.24 ms                                                      | 3.80 ms: 1.17x slower                                                             |
| telco                      | 7.16 ms                                                      | 8.42 ms: 1.18x slower                                                             |
| unpickle_pure_python       | 210 us                                                       | 248 us: 1.18x slower                                                              |
| go                         | 149 ms                                                       | 176 ms: 1.18x slower                                                              |
| coverage                   | 66.3 ms                                                      | 83.1 ms: 1.25x slower                                                             |
| python_startup_no_site     | 8.67 ms                                                      | 11.4 ms: 1.31x slower                                                             |
| hexiom                     | 5.97 ms                                                      | 8.19 ms: 1.37x slower                                                             |
| scimark_sor                | 107 ms                                                       | 149 ms: 1.40x slower                                                              |
| Geometric mean             | (ref)                                                        | 1.03x slower                                                                      |

Benchmark hidden because not significant (8): tornado_http, async_tree_cpu_io_mixed, float, xml_etree_iterparse, sqlglot_parse, sympy_integrate, json_loads, scimark_sparse_mat_mult
Ignored benchmarks (6) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, dask, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.01x
- 95% likely to have a slowdown of 1.01x
- 99% likely to have a slowdown of 1.00x
