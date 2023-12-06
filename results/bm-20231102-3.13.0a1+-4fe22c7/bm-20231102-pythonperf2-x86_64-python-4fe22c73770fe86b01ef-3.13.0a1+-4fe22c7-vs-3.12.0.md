
# Results vs. 3.12.0

- fork: python
- ref: 4fe22c73770fe86b01ef
- machine: linux-x86_64
- commit hash: 4fe22c7
- commit date: 2023-11-02
- overall geometric mean: 1.01x slower
- HPT reliability: 62.67%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231102-pythonperf2-x86_64-python-4fe22c73770fe86b01ef-3.13.0a1+-4fe22c7 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| 2to3           | 285 ms                                                       | 291 ms: 1.02x slower                                                         |
| chameleon      | 7.27 ms                                                      | 7.44 ms: 1.02x slower                                                        |
| docutils       | 2.89 sec                                                     | 2.83 sec: 1.02x faster                                                       |
| tornado_http   | 122 ms                                                       | 118 ms: 1.03x faster                                                         |
| Geometric mean | (ref)                                                        | 1.00x faster                                                                 |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231102-pythonperf2-x86_64-python-4fe22c73770fe86b01ef-3.13.0a1+-4fe22c7 |
|----------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| async_tree_none            | 459 ms                                                       | 433 ms: 1.06x faster                                                         |
| async_tree_memoization     | 554 ms                                                       | 546 ms: 1.01x faster                                                         |
| async_tree_none_tg         | 440 ms                                                       | 438 ms: 1.00x faster                                                         |
| async_tree_cpu_io_mixed_tg | 706 ms                                                       | 716 ms: 1.01x slower                                                         |
| async_tree_io_tg           | 1.07 sec                                                     | 1.09 sec: 1.02x slower                                                       |
| async_tree_io              | 1.06 sec                                                     | 1.08 sec: 1.02x slower                                                       |
| async_tree_memoization_tg  | 554 ms                                                       | 572 ms: 1.03x slower                                                         |
| Geometric mean             | (ref)                                                        | 1.00x slower                                                                 |

Benchmark hidden because not significant (1): async_tree_cpu_io_mixed

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231102-pythonperf2-x86_64-python-4fe22c73770fe86b01ef-3.13.0a1+-4fe22c7 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| float          | 81.6 ms                                                      | 79.3 ms: 1.03x faster                                                        |
| Geometric mean | (ref)                                                        | 1.01x faster                                                                 |

Benchmark hidden because not significant (2): nbody, pidigits

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231102-pythonperf2-x86_64-python-4fe22c73770fe86b01ef-3.13.0a1+-4fe22c7 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| regex_effbot   | 3.61 ms                                                      | 3.50 ms: 1.03x faster                                                        |
| regex_dna      | 240 ms                                                       | 234 ms: 1.02x faster                                                         |
| regex_v8       | 24.4 ms                                                      | 25.3 ms: 1.04x slower                                                        |
| Geometric mean | (ref)                                                        | 1.00x faster                                                                 |

Benchmark hidden because not significant (1): regex_compile

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231102-pythonperf2-x86_64-python-4fe22c73770fe86b01ef-3.13.0a1+-4fe22c7 |
|----------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| unpickle             | 15.3 us                                                      | 14.6 us: 1.05x faster                                                        |
| pickle_dict          | 32.0 us                                                      | 31.5 us: 1.01x faster                                                        |
| pickle_pure_python   | 319 us                                                       | 317 us: 1.01x faster                                                         |
| xml_etree_iterparse  | 104 ms                                                       | 105 ms: 1.02x slower                                                         |
| pickle               | 10.0 us                                                      | 10.2 us: 1.02x slower                                                        |
| json_dumps           | 10.3 ms                                                      | 10.4 ms: 1.02x slower                                                        |
| tomli_loads          | 2.17 sec                                                     | 2.21 sec: 1.02x slower                                                       |
| unpickle_list        | 4.65 us                                                      | 4.77 us: 1.03x slower                                                        |
| pickle_list          | 4.22 us                                                      | 4.38 us: 1.04x slower                                                        |
| unpickle_pure_python | 210 us                                                       | 221 us: 1.05x slower                                                         |
| Geometric mean       | (ref)                                                        | 1.01x slower                                                                 |

Benchmark hidden because not significant (4): xml_etree_parse, xml_etree_process, xml_etree_generate, json_loads

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231102-pythonperf2-x86_64-python-4fe22c73770fe86b01ef-3.13.0a1+-4fe22c7 |
|------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| python_startup         | 11.7 ms                                                      | 12.8 ms: 1.10x slower                                                        |
| python_startup_no_site | 8.67 ms                                                      | 11.3 ms: 1.30x slower                                                        |
| Geometric mean         | (ref)                                                        | 1.19x slower                                                                 |

Benchmarks with tag 'template':
===============================

Benchmark hidden because not significant (1): mako

All benchmarks:
===============

| Benchmark                  | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231102-pythonperf2-x86_64-python-4fe22c73770fe86b01ef-3.13.0a1+-4fe22c7 |
|----------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| comprehensions             | 21.8 us                                                      | 16.4 us: 1.33x faster                                                        |
| typing_runtime_protocols   | 150 us                                                       | 124 us: 1.21x faster                                                         |
| crypto_pyaes               | 82.4 ms                                                      | 70.6 ms: 1.17x faster                                                        |
| raytrace                   | 301 ms                                                       | 272 ms: 1.11x faster                                                         |
| scimark_sparse_mat_mult    | 4.49 ms                                                      | 4.06 ms: 1.10x faster                                                        |
| scimark_monte_carlo        | 69.5 ms                                                      | 63.2 ms: 1.10x faster                                                        |
| sympy_sum                  | 163 ms                                                       | 149 ms: 1.09x faster                                                         |
| sympy_str                  | 305 ms                                                       | 287 ms: 1.06x faster                                                         |
| async_tree_none            | 459 ms                                                       | 433 ms: 1.06x faster                                                         |
| gc_traversal               | 3.70 ms                                                      | 3.50 ms: 1.06x faster                                                        |
| sympy_integrate            | 24.0 ms                                                      | 22.7 ms: 1.06x faster                                                        |
| sqlglot_normalize          | 119 ms                                                       | 113 ms: 1.05x faster                                                         |
| chaos                      | 64.1 ms                                                      | 61.1 ms: 1.05x faster                                                        |
| generators                 | 37.3 ms                                                      | 35.6 ms: 1.05x faster                                                        |
| unpickle                   | 15.3 us                                                      | 14.6 us: 1.05x faster                                                        |
| deepcopy_reduce            | 3.41 us                                                      | 3.26 us: 1.05x faster                                                        |
| async_generators           | 385 ms                                                       | 369 ms: 1.05x faster                                                         |
| asyncio_tcp                | 380 ms                                                       | 366 ms: 1.04x faster                                                         |
| scimark_fft                | 303 ms                                                       | 293 ms: 1.03x faster                                                         |
| unpack_sequence            | 54.5 ns                                                      | 52.8 ns: 1.03x faster                                                        |
| regex_effbot               | 3.61 ms                                                      | 3.50 ms: 1.03x faster                                                        |
| spectral_norm              | 93.9 ms                                                      | 91.1 ms: 1.03x faster                                                        |
| nqueens                    | 90.1 ms                                                      | 87.5 ms: 1.03x faster                                                        |
| tornado_http               | 122 ms                                                       | 118 ms: 1.03x faster                                                         |
| float                      | 81.6 ms                                                      | 79.3 ms: 1.03x faster                                                        |
| coroutines                 | 23.1 ms                                                      | 22.5 ms: 1.03x faster                                                        |
| regex_dna                  | 240 ms                                                       | 234 ms: 1.02x faster                                                         |
| docutils                   | 2.89 sec                                                     | 2.83 sec: 1.02x faster                                                       |
| mdp                        | 2.56 sec                                                     | 2.51 sec: 1.02x faster                                                       |
| pprint_safe_repr           | 808 ms                                                       | 795 ms: 1.02x faster                                                         |
| sqlglot_optimize           | 58.4 ms                                                      | 57.5 ms: 1.02x faster                                                        |
| pickle_dict                | 32.0 us                                                      | 31.5 us: 1.01x faster                                                        |
| async_tree_memoization     | 554 ms                                                       | 546 ms: 1.01x faster                                                         |
| pprint_pformat             | 1.64 sec                                                     | 1.62 sec: 1.01x faster                                                       |
| pickle_pure_python         | 319 us                                                       | 317 us: 1.01x faster                                                         |
| sympy_expand               | 492 ms                                                       | 489 ms: 1.01x faster                                                         |
| async_tree_none_tg         | 440 ms                                                       | 438 ms: 1.00x faster                                                         |
| mypy2                      | 365 ms                                                       | 366 ms: 1.00x slower                                                         |
| asyncio_tcp_ssl            | 1.57 sec                                                     | 1.58 sec: 1.00x slower                                                       |
| sqlglot_transpile          | 1.80 ms                                                      | 1.82 ms: 1.01x slower                                                        |
| logging_silent             | 93.3 ns                                                      | 94.1 ns: 1.01x slower                                                        |
| async_tree_cpu_io_mixed_tg | 706 ms                                                       | 716 ms: 1.01x slower                                                         |
| scimark_lu                 | 98.6 ms                                                      | 100 ms: 1.01x slower                                                         |
| xml_etree_iterparse        | 104 ms                                                       | 105 ms: 1.02x slower                                                         |
| pickle                     | 10.0 us                                                      | 10.2 us: 1.02x slower                                                        |
| json_dumps                 | 10.3 ms                                                      | 10.4 ms: 1.02x slower                                                        |
| tomli_loads                | 2.17 sec                                                     | 2.21 sec: 1.02x slower                                                       |
| async_tree_io_tg           | 1.07 sec                                                     | 1.09 sec: 1.02x slower                                                       |
| meteor_contest             | 126 ms                                                       | 129 ms: 1.02x slower                                                         |
| async_tree_io              | 1.06 sec                                                     | 1.08 sec: 1.02x slower                                                       |
| 2to3                       | 285 ms                                                       | 291 ms: 1.02x slower                                                         |
| deepcopy_memo              | 36.6 us                                                      | 37.3 us: 1.02x slower                                                        |
| chameleon                  | 7.27 ms                                                      | 7.44 ms: 1.02x slower                                                        |
| logging_format             | 7.29 us                                                      | 7.46 us: 1.02x slower                                                        |
| unpickle_list              | 4.65 us                                                      | 4.77 us: 1.03x slower                                                        |
| pycparser                  | 1.29 sec                                                     | 1.34 sec: 1.03x slower                                                       |
| logging_simple             | 6.64 us                                                      | 6.86 us: 1.03x slower                                                        |
| async_tree_memoization_tg  | 554 ms                                                       | 572 ms: 1.03x slower                                                         |
| create_gc_cycles           | 1.58 ms                                                      | 1.63 ms: 1.03x slower                                                        |
| regex_v8                   | 24.4 ms                                                      | 25.3 ms: 1.04x slower                                                        |
| pickle_list                | 4.22 us                                                      | 4.38 us: 1.04x slower                                                        |
| pathlib                    | 18.7 ms                                                      | 19.5 ms: 1.04x slower                                                        |
| dulwich_log                | 64.9 ms                                                      | 68.2 ms: 1.05x slower                                                        |
| unpickle_pure_python       | 210 us                                                       | 221 us: 1.05x slower                                                         |
| fannkuch                   | 362 ms                                                       | 390 ms: 1.08x slower                                                         |
| hexiom                     | 5.97 ms                                                      | 6.46 ms: 1.08x slower                                                        |
| python_startup             | 11.7 ms                                                      | 12.8 ms: 1.10x slower                                                        |
| deltablue                  | 3.24 ms                                                      | 3.63 ms: 1.12x slower                                                        |
| pyflate                    | 442 ms                                                       | 502 ms: 1.14x slower                                                         |
| telco                      | 7.16 ms                                                      | 8.20 ms: 1.15x slower                                                        |
| go                         | 149 ms                                                       | 171 ms: 1.15x slower                                                         |
| richards_super             | 50.8 ms                                                      | 59.9 ms: 1.18x slower                                                        |
| richards                   | 45.1 ms                                                      | 54.0 ms: 1.20x slower                                                        |
| coverage                   | 66.3 ms                                                      | 82.4 ms: 1.24x slower                                                        |
| python_startup_no_site     | 8.67 ms                                                      | 11.3 ms: 1.30x slower                                                        |
| scimark_sor                | 107 ms                                                       | 144 ms: 1.35x slower                                                         |
| Geometric mean             | (ref)                                                        | 1.01x slower                                                                 |

Benchmark hidden because not significant (16): bench_mp_pool, bench_thread_pool, async_tree_cpu_io_mixed, nbody, xml_etree_parse, xml_etree_process, sqlite_synth, json, xml_etree_generate, sqlglot_parse, pidigits, deepcopy, json_loads, regex_compile, asyncio_websockets, mako
Ignored benchmarks (6) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, dask, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 62.67% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
