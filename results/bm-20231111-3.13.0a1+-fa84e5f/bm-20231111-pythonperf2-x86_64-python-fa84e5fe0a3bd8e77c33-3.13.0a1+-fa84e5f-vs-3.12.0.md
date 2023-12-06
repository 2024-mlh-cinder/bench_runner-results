
# Results vs. 3.12.0

- fork: python
- ref: fa84e5fe0a3bd8e77c33
- machine: linux-x86_64
- commit hash: fa84e5f
- commit date: 2023-11-11
- overall geometric mean: 1.01x slower \*
- HPT reliability: 81.16%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231111-pythonperf2-x86_64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| 2to3           | 285 ms                                                       | 292 ms: 1.03x slower                                                         |
| chameleon      | 7.27 ms                                                      | 7.22 ms: 1.01x faster                                                        |
| docutils       | 2.89 sec                                                     | 2.84 sec: 1.02x faster                                                       |
| tornado_http   | 122 ms                                                       | 119 ms: 1.02x faster                                                         |
| Geometric mean | (ref)                                                        | 1.01x faster                                                                 |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                 | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231111-pythonperf2-x86_64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f |
|---------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| async_tree_none           | 459 ms                                                       | 433 ms: 1.06x faster                                                         |
| async_tree_memoization    | 554 ms                                                       | 546 ms: 1.01x faster                                                         |
| async_tree_cpu_io_mixed   | 704 ms                                                       | 695 ms: 1.01x faster                                                         |
| async_tree_none_tg        | 440 ms                                                       | 439 ms: 1.00x faster                                                         |
| async_tree_memoization_tg | 554 ms                                                       | 561 ms: 1.01x slower                                                         |
| async_tree_io             | 1.06 sec                                                     | 1.08 sec: 1.02x slower                                                       |
| async_tree_io_tg          | 1.07 sec                                                     | 1.10 sec: 1.02x slower                                                       |
| Geometric mean            | (ref)                                                        | 1.00x faster                                                                 |

Benchmark hidden because not significant (1): async_tree_cpu_io_mixed_tg

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231111-pythonperf2-x86_64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| nbody          | 88.2 ms                                                      | 84.7 ms: 1.04x faster                                                        |
| float          | 81.6 ms                                                      | 79.3 ms: 1.03x faster                                                        |
| Geometric mean | (ref)                                                        | 1.02x faster                                                                 |

Benchmark hidden because not significant (1): pidigits

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231111-pythonperf2-x86_64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| regex_effbot   | 3.61 ms                                                      | 3.43 ms: 1.05x faster                                                        |
| regex_compile  | 145 ms                                                       | 143 ms: 1.01x faster                                                         |
| regex_dna      | 240 ms                                                       | 244 ms: 1.02x slower                                                         |
| regex_v8       | 24.4 ms                                                      | 25.7 ms: 1.05x slower                                                        |
| Geometric mean | (ref)                                                        | 1.00x slower                                                                 |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231111-pythonperf2-x86_64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f |
|----------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| unpickle             | 15.3 us                                                      | 14.4 us: 1.07x faster                                                        |
| pickle_pure_python   | 319 us                                                       | 321 us: 1.01x slower                                                         |
| pickle               | 10.0 us                                                      | 10.1 us: 1.01x slower                                                        |
| json_loads           | 24.3 us                                                      | 24.6 us: 1.01x slower                                                        |
| pickle_dict          | 32.0 us                                                      | 32.7 us: 1.02x slower                                                        |
| unpickle_list        | 4.65 us                                                      | 4.76 us: 1.02x slower                                                        |
| xml_etree_iterparse  | 104 ms                                                       | 106 ms: 1.02x slower                                                         |
| tomli_loads          | 2.17 sec                                                     | 2.23 sec: 1.03x slower                                                       |
| pickle_list          | 4.22 us                                                      | 4.36 us: 1.03x slower                                                        |
| json_dumps           | 10.3 ms                                                      | 10.6 ms: 1.04x slower                                                        |
| unpickle_pure_python | 210 us                                                       | 222 us: 1.06x slower                                                         |
| Geometric mean       | (ref)                                                        | 1.01x slower                                                                 |

Benchmark hidden because not significant (3): xml_etree_parse, xml_etree_process, xml_etree_generate

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231111-pythonperf2-x86_64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f |
|------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| python_startup         | 11.7 ms                                                      | 12.8 ms: 1.10x slower                                                        |
| python_startup_no_site | 8.67 ms                                                      | 11.3 ms: 1.30x slower                                                        |
| Geometric mean         | (ref)                                                        | 1.20x slower                                                                 |

Benchmarks with tag 'template':
===============================

Benchmark hidden because not significant (1): mako

All benchmarks:
===============

| Benchmark                 | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231111-pythonperf2-x86_64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f |
|---------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| comprehensions            | 21.8 us                                                      | 16.3 us: 1.34x faster                                                        |
| typing_runtime_protocols  | 150 us                                                       | 124 us: 1.21x faster                                                         |
| crypto_pyaes              | 82.4 ms                                                      | 70.6 ms: 1.17x faster                                                        |
| raytrace                  | 301 ms                                                       | 271 ms: 1.11x faster                                                         |
| sympy_sum                 | 163 ms                                                       | 151 ms: 1.08x faster                                                         |
| async_generators          | 385 ms                                                       | 359 ms: 1.07x faster                                                         |
| unpack_sequence           | 54.5 ns                                                      | 50.8 ns: 1.07x faster                                                        |
| scimark_sparse_mat_mult   | 4.49 ms                                                      | 4.19 ms: 1.07x faster                                                        |
| unpickle                  | 15.3 us                                                      | 14.4 us: 1.07x faster                                                        |
| gc_traversal              | 3.70 ms                                                      | 3.49 ms: 1.06x faster                                                        |
| async_tree_none           | 459 ms                                                       | 433 ms: 1.06x faster                                                         |
| sympy_str                 | 305 ms                                                       | 289 ms: 1.05x faster                                                         |
| regex_effbot              | 3.61 ms                                                      | 3.43 ms: 1.05x faster                                                        |
| sympy_integrate           | 24.0 ms                                                      | 23.0 ms: 1.05x faster                                                        |
| chaos                     | 64.1 ms                                                      | 61.4 ms: 1.04x faster                                                        |
| nbody                     | 88.2 ms                                                      | 84.7 ms: 1.04x faster                                                        |
| coroutines                | 23.1 ms                                                      | 22.2 ms: 1.04x faster                                                        |
| generators                | 37.3 ms                                                      | 35.9 ms: 1.04x faster                                                        |
| spectral_norm             | 93.9 ms                                                      | 90.6 ms: 1.04x faster                                                        |
| deepcopy_reduce           | 3.41 us                                                      | 3.29 us: 1.04x faster                                                        |
| float                     | 81.6 ms                                                      | 79.3 ms: 1.03x faster                                                        |
| asyncio_tcp               | 380 ms                                                       | 369 ms: 1.03x faster                                                         |
| scimark_monte_carlo       | 69.5 ms                                                      | 67.7 ms: 1.03x faster                                                        |
| tornado_http              | 122 ms                                                       | 119 ms: 1.02x faster                                                         |
| sqlglot_normalize         | 119 ms                                                       | 117 ms: 1.02x faster                                                         |
| docutils                  | 2.89 sec                                                     | 2.84 sec: 1.02x faster                                                       |
| pycparser                 | 1.29 sec                                                     | 1.27 sec: 1.02x faster                                                       |
| async_tree_memoization    | 554 ms                                                       | 546 ms: 1.01x faster                                                         |
| async_tree_cpu_io_mixed   | 704 ms                                                       | 695 ms: 1.01x faster                                                         |
| regex_compile             | 145 ms                                                       | 143 ms: 1.01x faster                                                         |
| mdp                       | 2.56 sec                                                     | 2.53 sec: 1.01x faster                                                       |
| sqlite_synth              | 2.72 us                                                      | 2.69 us: 1.01x faster                                                        |
| pprint_safe_repr          | 808 ms                                                       | 801 ms: 1.01x faster                                                         |
| chameleon                 | 7.27 ms                                                      | 7.22 ms: 1.01x faster                                                        |
| json                      | 5.17 ms                                                      | 5.14 ms: 1.01x faster                                                        |
| nqueens                   | 90.1 ms                                                      | 89.6 ms: 1.01x faster                                                        |
| async_tree_none_tg        | 440 ms                                                       | 439 ms: 1.00x faster                                                         |
| mypy2                     | 365 ms                                                       | 366 ms: 1.00x slower                                                         |
| deepcopy_memo             | 36.6 us                                                      | 36.7 us: 1.00x slower                                                        |
| asyncio_tcp_ssl           | 1.57 sec                                                     | 1.58 sec: 1.01x slower                                                       |
| pickle_pure_python        | 319 us                                                       | 321 us: 1.01x slower                                                         |
| sqlglot_transpile         | 1.80 ms                                                      | 1.82 ms: 1.01x slower                                                        |
| pickle                    | 10.0 us                                                      | 10.1 us: 1.01x slower                                                        |
| asyncio_websockets        | 386 ms                                                       | 390 ms: 1.01x slower                                                         |
| sqlglot_optimize          | 58.4 ms                                                      | 59.1 ms: 1.01x slower                                                        |
| async_tree_memoization_tg | 554 ms                                                       | 561 ms: 1.01x slower                                                         |
| json_loads                | 24.3 us                                                      | 24.6 us: 1.01x slower                                                        |
| scimark_fft               | 303 ms                                                       | 308 ms: 1.01x slower                                                         |
| regex_dna                 | 240 ms                                                       | 244 ms: 1.02x slower                                                         |
| async_tree_io             | 1.06 sec                                                     | 1.08 sec: 1.02x slower                                                       |
| pickle_dict               | 32.0 us                                                      | 32.7 us: 1.02x slower                                                        |
| logging_silent            | 93.3 ns                                                      | 95.3 ns: 1.02x slower                                                        |
| async_tree_io_tg          | 1.07 sec                                                     | 1.10 sec: 1.02x slower                                                       |
| unpickle_list             | 4.65 us                                                      | 4.76 us: 1.02x slower                                                        |
| xml_etree_iterparse       | 104 ms                                                       | 106 ms: 1.02x slower                                                         |
| meteor_contest            | 126 ms                                                       | 130 ms: 1.03x slower                                                         |
| 2to3                      | 285 ms                                                       | 292 ms: 1.03x slower                                                         |
| tomli_loads               | 2.17 sec                                                     | 2.23 sec: 1.03x slower                                                       |
| create_gc_cycles          | 1.58 ms                                                      | 1.63 ms: 1.03x slower                                                        |
| pickle_list               | 4.22 us                                                      | 4.36 us: 1.03x slower                                                        |
| dulwich_log               | 64.9 ms                                                      | 67.2 ms: 1.04x slower                                                        |
| json_dumps                | 10.3 ms                                                      | 10.6 ms: 1.04x slower                                                        |
| pathlib                   | 18.7 ms                                                      | 19.6 ms: 1.04x slower                                                        |
| regex_v8                  | 24.4 ms                                                      | 25.7 ms: 1.05x slower                                                        |
| unpickle_pure_python      | 210 us                                                       | 222 us: 1.06x slower                                                         |
| hexiom                    | 5.97 ms                                                      | 6.45 ms: 1.08x slower                                                        |
| python_startup            | 11.7 ms                                                      | 12.8 ms: 1.10x slower                                                        |
| fannkuch                  | 362 ms                                                       | 400 ms: 1.10x slower                                                         |
| telco                     | 7.16 ms                                                      | 7.94 ms: 1.11x slower                                                        |
| deltablue                 | 3.24 ms                                                      | 3.60 ms: 1.11x slower                                                        |
| go                        | 149 ms                                                       | 169 ms: 1.13x slower                                                         |
| pyflate                   | 442 ms                                                       | 510 ms: 1.15x slower                                                         |
| richards_super            | 50.8 ms                                                      | 61.5 ms: 1.21x slower                                                        |
| richards                  | 45.1 ms                                                      | 55.8 ms: 1.24x slower                                                        |
| coverage                  | 66.3 ms                                                      | 82.8 ms: 1.25x slower                                                        |
| python_startup_no_site    | 8.67 ms                                                      | 11.3 ms: 1.30x slower                                                        |
| scimark_sor               | 107 ms                                                       | 149 ms: 1.39x slower                                                         |
| Geometric mean            | (ref)                                                        | 1.01x slower                                                                 |

Benchmark hidden because not significant (15): bench_mp_pool, xml_etree_parse, logging_simple, pprint_pformat, sympy_expand, scimark_lu, deepcopy, xml_etree_process, sqlglot_parse, pidigits, xml_etree_generate, mako, logging_format, async_tree_cpu_io_mixed_tg, bench_thread_pool
Ignored benchmarks (6) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, dask, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 81.16% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
