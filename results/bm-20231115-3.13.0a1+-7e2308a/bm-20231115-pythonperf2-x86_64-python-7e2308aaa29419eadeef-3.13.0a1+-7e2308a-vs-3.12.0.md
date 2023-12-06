
# Results vs. 3.12.0

- fork: python
- ref: 7e2308aaa29419eadeef
- machine: linux-x86_64
- commit hash: 7e2308a
- commit date: 2023-11-15
- overall geometric mean: 1.01x slower \*
- HPT reliability: 96.02%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231115-pythonperf2-x86_64-python-7e2308aaa29419eadeef-3.13.0a1+-7e2308a |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| 2to3           | 285 ms                                                       | 293 ms: 1.03x slower                                                         |
| chameleon      | 7.27 ms                                                      | 7.42 ms: 1.02x slower                                                        |
| docutils       | 2.89 sec                                                     | 2.83 sec: 1.02x faster                                                       |
| tornado_http   | 122 ms                                                       | 120 ms: 1.01x faster                                                         |
| Geometric mean | (ref)                                                        | 1.00x slower                                                                 |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                 | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231115-pythonperf2-x86_64-python-7e2308aaa29419eadeef-3.13.0a1+-7e2308a |
|---------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| async_tree_none           | 459 ms                                                       | 429 ms: 1.07x faster                                                         |
| async_tree_memoization    | 554 ms                                                       | 544 ms: 1.02x faster                                                         |
| async_tree_cpu_io_mixed   | 704 ms                                                       | 693 ms: 1.02x faster                                                         |
| async_tree_memoization_tg | 554 ms                                                       | 559 ms: 1.01x slower                                                         |
| async_tree_io             | 1.06 sec                                                     | 1.08 sec: 1.02x slower                                                       |
| async_tree_io_tg          | 1.07 sec                                                     | 1.10 sec: 1.02x slower                                                       |
| Geometric mean            | (ref)                                                        | 1.01x faster                                                                 |

Benchmark hidden because not significant (2): async_tree_none_tg, async_tree_cpu_io_mixed_tg

Benchmarks with tag 'math':
===========================

Benchmark hidden because not significant (3): float, nbody, pidigits

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231115-pythonperf2-x86_64-python-7e2308aaa29419eadeef-3.13.0a1+-7e2308a |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| regex_compile  | 145 ms                                                       | 143 ms: 1.01x faster                                                         |
| regex_effbot   | 3.61 ms                                                      | 3.59 ms: 1.01x faster                                                        |
| regex_v8       | 24.4 ms                                                      | 25.6 ms: 1.05x slower                                                        |
| regex_dna      | 240 ms                                                       | 255 ms: 1.06x slower                                                         |
| Geometric mean | (ref)                                                        | 1.02x slower                                                                 |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231115-pythonperf2-x86_64-python-7e2308aaa29419eadeef-3.13.0a1+-7e2308a |
|----------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| unpickle             | 15.3 us                                                      | 14.3 us: 1.07x faster                                                        |
| pickle_pure_python   | 319 us                                                       | 312 us: 1.02x faster                                                         |
| unpickle_list        | 4.65 us                                                      | 4.61 us: 1.01x faster                                                        |
| xml_etree_generate   | 85.3 ms                                                      | 86.2 ms: 1.01x slower                                                        |
| pickle               | 10.0 us                                                      | 10.2 us: 1.01x slower                                                        |
| unpickle_pure_python | 210 us                                                       | 212 us: 1.01x slower                                                         |
| pickle_dict          | 32.0 us                                                      | 32.5 us: 1.02x slower                                                        |
| tomli_loads          | 2.17 sec                                                     | 2.21 sec: 1.02x slower                                                       |
| xml_etree_iterparse  | 104 ms                                                       | 107 ms: 1.03x slower                                                         |
| xml_etree_parse      | 147 ms                                                       | 153 ms: 1.04x slower                                                         |
| json_loads           | 24.3 us                                                      | 25.5 us: 1.05x slower                                                        |
| json_dumps           | 10.3 ms                                                      | 11.0 ms: 1.07x slower                                                        |
| pickle_list          | 4.22 us                                                      | 4.68 us: 1.11x slower                                                        |
| Geometric mean       | (ref)                                                        | 1.02x slower                                                                 |

Benchmark hidden because not significant (1): xml_etree_process

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231115-pythonperf2-x86_64-python-7e2308aaa29419eadeef-3.13.0a1+-7e2308a |
|------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| python_startup         | 11.7 ms                                                      | 12.9 ms: 1.11x slower                                                        |
| python_startup_no_site | 8.67 ms                                                      | 11.3 ms: 1.31x slower                                                        |
| Geometric mean         | (ref)                                                        | 1.20x slower                                                                 |

Benchmarks with tag 'template':
===============================

Benchmark hidden because not significant (1): mako

All benchmarks:
===============

| Benchmark                 | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231115-pythonperf2-x86_64-python-7e2308aaa29419eadeef-3.13.0a1+-7e2308a |
|---------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| comprehensions            | 21.8 us                                                      | 16.7 us: 1.31x faster                                                        |
| typing_runtime_protocols  | 150 us                                                       | 124 us: 1.21x faster                                                         |
| crypto_pyaes              | 82.4 ms                                                      | 70.6 ms: 1.17x faster                                                        |
| unpack_sequence           | 54.5 ns                                                      | 49.0 ns: 1.11x faster                                                        |
| raytrace                  | 301 ms                                                       | 273 ms: 1.10x faster                                                         |
| sympy_sum                 | 163 ms                                                       | 150 ms: 1.09x faster                                                         |
| async_tree_none           | 459 ms                                                       | 429 ms: 1.07x faster                                                         |
| unpickle                  | 15.3 us                                                      | 14.3 us: 1.07x faster                                                        |
| generators                | 37.3 ms                                                      | 35.1 ms: 1.06x faster                                                        |
| scimark_sparse_mat_mult   | 4.49 ms                                                      | 4.22 ms: 1.06x faster                                                        |
| sympy_str                 | 305 ms                                                       | 289 ms: 1.05x faster                                                         |
| sympy_integrate           | 24.0 ms                                                      | 22.9 ms: 1.05x faster                                                        |
| logging_simple            | 6.64 us                                                      | 6.35 us: 1.04x faster                                                        |
| chaos                     | 64.1 ms                                                      | 61.3 ms: 1.04x faster                                                        |
| async_generators          | 385 ms                                                       | 369 ms: 1.04x faster                                                         |
| sqlglot_normalize         | 119 ms                                                       | 114 ms: 1.04x faster                                                         |
| logging_format            | 7.29 us                                                      | 6.99 us: 1.04x faster                                                        |
| deepcopy_reduce           | 3.41 us                                                      | 3.27 us: 1.04x faster                                                        |
| scimark_monte_carlo       | 69.5 ms                                                      | 66.8 ms: 1.04x faster                                                        |
| coroutines                | 23.1 ms                                                      | 22.2 ms: 1.04x faster                                                        |
| spectral_norm             | 93.9 ms                                                      | 90.6 ms: 1.04x faster                                                        |
| deepcopy                  | 371 us                                                       | 359 us: 1.03x faster                                                         |
| asyncio_tcp               | 380 ms                                                       | 369 ms: 1.03x faster                                                         |
| nqueens                   | 90.1 ms                                                      | 87.6 ms: 1.03x faster                                                        |
| pickle_pure_python        | 319 us                                                       | 312 us: 1.02x faster                                                         |
| docutils                  | 2.89 sec                                                     | 2.83 sec: 1.02x faster                                                       |
| async_tree_memoization    | 554 ms                                                       | 544 ms: 1.02x faster                                                         |
| async_tree_cpu_io_mixed   | 704 ms                                                       | 693 ms: 1.02x faster                                                         |
| tornado_http              | 122 ms                                                       | 120 ms: 1.01x faster                                                         |
| regex_compile             | 145 ms                                                       | 143 ms: 1.01x faster                                                         |
| pathlib                   | 18.7 ms                                                      | 18.5 ms: 1.01x faster                                                        |
| sqlglot_parse             | 1.41 ms                                                      | 1.39 ms: 1.01x faster                                                        |
| sqlglot_optimize          | 58.4 ms                                                      | 57.8 ms: 1.01x faster                                                        |
| unpickle_list             | 4.65 us                                                      | 4.61 us: 1.01x faster                                                        |
| sqlite_synth              | 2.72 us                                                      | 2.70 us: 1.01x faster                                                        |
| mdp                       | 2.56 sec                                                     | 2.54 sec: 1.01x faster                                                       |
| regex_effbot              | 3.61 ms                                                      | 3.59 ms: 1.01x faster                                                        |
| meteor_contest            | 126 ms                                                       | 127 ms: 1.00x slower                                                         |
| asyncio_tcp_ssl           | 1.57 sec                                                     | 1.58 sec: 1.00x slower                                                       |
| mypy2                     | 365 ms                                                       | 367 ms: 1.01x slower                                                         |
| pprint_pformat            | 1.64 sec                                                     | 1.66 sec: 1.01x slower                                                       |
| async_tree_memoization_tg | 554 ms                                                       | 559 ms: 1.01x slower                                                         |
| xml_etree_generate        | 85.3 ms                                                      | 86.2 ms: 1.01x slower                                                        |
| pickle                    | 10.0 us                                                      | 10.2 us: 1.01x slower                                                        |
| unpickle_pure_python      | 210 us                                                       | 212 us: 1.01x slower                                                         |
| scimark_lu                | 98.6 ms                                                      | 100 ms: 1.01x slower                                                         |
| pickle_dict               | 32.0 us                                                      | 32.5 us: 1.02x slower                                                        |
| tomli_loads               | 2.17 sec                                                     | 2.21 sec: 1.02x slower                                                       |
| async_tree_io             | 1.06 sec                                                     | 1.08 sec: 1.02x slower                                                       |
| bench_thread_pool         | 956 us                                                       | 976 us: 1.02x slower                                                         |
| chameleon                 | 7.27 ms                                                      | 7.42 ms: 1.02x slower                                                        |
| async_tree_io_tg          | 1.07 sec                                                     | 1.10 sec: 1.02x slower                                                       |
| 2to3                      | 285 ms                                                       | 293 ms: 1.03x slower                                                         |
| xml_etree_iterparse       | 104 ms                                                       | 107 ms: 1.03x slower                                                         |
| logging_silent            | 93.3 ns                                                      | 96.5 ns: 1.03x slower                                                        |
| xml_etree_parse           | 147 ms                                                       | 153 ms: 1.04x slower                                                         |
| regex_v8                  | 24.4 ms                                                      | 25.6 ms: 1.05x slower                                                        |
| json_loads                | 24.3 us                                                      | 25.5 us: 1.05x slower                                                        |
| dulwich_log               | 64.9 ms                                                      | 68.2 ms: 1.05x slower                                                        |
| regex_dna                 | 240 ms                                                       | 255 ms: 1.06x slower                                                         |
| fannkuch                  | 362 ms                                                       | 385 ms: 1.06x slower                                                         |
| json_dumps                | 10.3 ms                                                      | 11.0 ms: 1.07x slower                                                        |
| hexiom                    | 5.97 ms                                                      | 6.41 ms: 1.07x slower                                                        |
| gc_traversal              | 3.70 ms                                                      | 3.99 ms: 1.08x slower                                                        |
| python_startup            | 11.7 ms                                                      | 12.9 ms: 1.11x slower                                                        |
| deltablue                 | 3.24 ms                                                      | 3.59 ms: 1.11x slower                                                        |
| pickle_list               | 4.22 us                                                      | 4.68 us: 1.11x slower                                                        |
| go                        | 149 ms                                                       | 167 ms: 1.12x slower                                                         |
| telco                     | 7.16 ms                                                      | 8.07 ms: 1.13x slower                                                        |
| richards_super            | 50.8 ms                                                      | 59.8 ms: 1.18x slower                                                        |
| bench_mp_pool             | 4.96 ms                                                      | 5.89 ms: 1.19x slower                                                        |
| coverage                  | 66.3 ms                                                      | 79.8 ms: 1.20x slower                                                        |
| pyflate                   | 442 ms                                                       | 532 ms: 1.20x slower                                                         |
| richards                  | 45.1 ms                                                      | 54.6 ms: 1.21x slower                                                        |
| python_startup_no_site    | 8.67 ms                                                      | 11.3 ms: 1.31x slower                                                        |
| scimark_sor               | 107 ms                                                       | 148 ms: 1.39x slower                                                         |
| Geometric mean            | (ref)                                                        | 1.01x slower                                                                 |

Benchmark hidden because not significant (17): float, nbody, sqlglot_transpile, pycparser, sympy_expand, async_tree_none_tg, mako, asyncio_websockets, pidigits, json, pprint_safe_repr, xml_etree_process, scimark_fft, deepcopy_memo, async_tree_cpu_io_mixed_tg, dask, create_gc_cycles
Ignored benchmarks (5) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 96.02% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
