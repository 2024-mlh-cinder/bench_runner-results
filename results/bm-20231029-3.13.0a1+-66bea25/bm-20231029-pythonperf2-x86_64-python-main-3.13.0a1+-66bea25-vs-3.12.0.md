
# Results vs. 3.12.0

- fork: python
- ref: main
- machine: linux-x86_64
- commit hash: 66bea25
- commit date: 2023-10-29
- overall geometric mean: 1.02x slower
- HPT reliability: 99.98%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231029-pythonperf2-x86_64-python-main-3.13.0a1+-66bea25 |
|----------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| 2to3           | 285 ms                                                       | 297 ms: 1.04x slower                                         |
| chameleon      | 7.27 ms                                                      | 7.79 ms: 1.07x slower                                        |
| docutils       | 2.89 sec                                                     | 2.88 sec: 1.01x faster                                       |
| Geometric mean | (ref)                                                        | 1.03x slower                                                 |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231029-pythonperf2-x86_64-python-main-3.13.0a1+-66bea25 |
|----------------------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| async_tree_none            | 459 ms                                                       | 440 ms: 1.04x faster                                         |
| async_tree_none_tg         | 440 ms                                                       | 449 ms: 1.02x slower                                         |
| async_tree_cpu_io_mixed_tg | 706 ms                                                       | 727 ms: 1.03x slower                                         |
| async_tree_memoization_tg  | 554 ms                                                       | 573 ms: 1.03x slower                                         |
| async_tree_io              | 1.06 sec                                                     | 1.10 sec: 1.04x slower                                       |
| async_tree_io_tg           | 1.07 sec                                                     | 1.11 sec: 1.04x slower                                       |
| Geometric mean             | (ref)                                                        | 1.02x slower                                                 |

Benchmark hidden because not significant (2): async_tree_memoization, async_tree_cpu_io_mixed

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231029-pythonperf2-x86_64-python-main-3.13.0a1+-66bea25 |
|----------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| float          | 81.6 ms                                                      | 78.8 ms: 1.04x faster                                        |
| Geometric mean | (ref)                                                        | 1.01x faster                                                 |

Benchmark hidden because not significant (2): nbody, pidigits

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231029-pythonperf2-x86_64-python-main-3.13.0a1+-66bea25 |
|----------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| regex_effbot   | 3.61 ms                                                      | 3.53 ms: 1.02x faster                                        |
| regex_dna      | 240 ms                                                       | 238 ms: 1.01x faster                                         |
| regex_v8       | 24.4 ms                                                      | 24.4 ms: 1.00x faster                                        |
| regex_compile  | 145 ms                                                       | 149 ms: 1.03x slower                                         |
| Geometric mean | (ref)                                                        | 1.00x faster                                                 |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231029-pythonperf2-x86_64-python-main-3.13.0a1+-66bea25 |
|----------------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| unpickle             | 15.3 us                                                      | 14.8 us: 1.03x faster                                        |
| unpickle_list        | 4.65 us                                                      | 4.54 us: 1.02x faster                                        |
| pickle_dict          | 32.0 us                                                      | 31.4 us: 1.02x faster                                        |
| xml_etree_generate   | 85.3 ms                                                      | 84.8 ms: 1.01x faster                                        |
| json_loads           | 24.3 us                                                      | 24.6 us: 1.01x slower                                        |
| xml_etree_process    | 58.3 ms                                                      | 59.3 ms: 1.02x slower                                        |
| xml_etree_parse      | 147 ms                                                       | 150 ms: 1.02x slower                                         |
| pickle               | 10.0 us                                                      | 10.3 us: 1.02x slower                                        |
| json_dumps           | 10.3 ms                                                      | 10.5 ms: 1.03x slower                                        |
| pickle_list          | 4.22 us                                                      | 4.38 us: 1.04x slower                                        |
| tomli_loads          | 2.17 sec                                                     | 2.26 sec: 1.04x slower                                       |
| xml_etree_iterparse  | 104 ms                                                       | 109 ms: 1.05x slower                                         |
| unpickle_pure_python | 210 us                                                       | 221 us: 1.05x slower                                         |
| Geometric mean       | (ref)                                                        | 1.01x slower                                                 |

Benchmark hidden because not significant (1): pickle_pure_python

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231029-pythonperf2-x86_64-python-main-3.13.0a1+-66bea25 |
|------------------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| python_startup         | 11.7 ms                                                      | 12.9 ms: 1.10x slower                                        |
| python_startup_no_site | 8.67 ms                                                      | 11.3 ms: 1.31x slower                                        |
| Geometric mean         | (ref)                                                        | 1.20x slower                                                 |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231029-pythonperf2-x86_64-python-main-3.13.0a1+-66bea25 |
|-----------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| mako      | 10.1 ms                                                      | 10.3 ms: 1.02x slower                                        |

All benchmarks:
===============

| Benchmark                  | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231029-pythonperf2-x86_64-python-main-3.13.0a1+-66bea25 |
|----------------------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| comprehensions             | 21.8 us                                                      | 16.8 us: 1.30x faster                                        |
| unpack_sequence            | 54.5 ns                                                      | 46.3 ns: 1.18x faster                                        |
| crypto_pyaes               | 82.4 ms                                                      | 71.8 ms: 1.15x faster                                        |
| raytrace                   | 301 ms                                                       | 274 ms: 1.10x faster                                         |
| bench_mp_pool              | 4.96 ms                                                      | 4.56 ms: 1.09x faster                                        |
| sympy_sum                  | 163 ms                                                       | 152 ms: 1.07x faster                                         |
| scimark_sparse_mat_mult    | 4.49 ms                                                      | 4.21 ms: 1.07x faster                                        |
| async_tree_none            | 459 ms                                                       | 440 ms: 1.04x faster                                         |
| sympy_str                  | 305 ms                                                       | 293 ms: 1.04x faster                                         |
| float                      | 81.6 ms                                                      | 78.8 ms: 1.04x faster                                        |
| unpickle                   | 15.3 us                                                      | 14.8 us: 1.03x faster                                        |
| generators                 | 37.3 ms                                                      | 36.2 ms: 1.03x faster                                        |
| asyncio_tcp                | 380 ms                                                       | 369 ms: 1.03x faster                                         |
| chaos                      | 64.1 ms                                                      | 62.3 ms: 1.03x faster                                        |
| unpickle_list              | 4.65 us                                                      | 4.54 us: 1.02x faster                                        |
| regex_effbot               | 3.61 ms                                                      | 3.53 ms: 1.02x faster                                        |
| pickle_dict                | 32.0 us                                                      | 31.4 us: 1.02x faster                                        |
| sympy_integrate            | 24.0 ms                                                      | 23.6 ms: 1.02x faster                                        |
| sqlglot_normalize          | 119 ms                                                       | 117 ms: 1.02x faster                                         |
| deepcopy_reduce            | 3.41 us                                                      | 3.37 us: 1.01x faster                                        |
| nqueens                    | 90.1 ms                                                      | 89.1 ms: 1.01x faster                                        |
| regex_dna                  | 240 ms                                                       | 238 ms: 1.01x faster                                         |
| mdp                        | 2.56 sec                                                     | 2.54 sec: 1.01x faster                                       |
| xml_etree_generate         | 85.3 ms                                                      | 84.8 ms: 1.01x faster                                        |
| docutils                   | 2.89 sec                                                     | 2.88 sec: 1.01x faster                                       |
| sqlite_synth               | 2.72 us                                                      | 2.71 us: 1.00x faster                                        |
| regex_v8                   | 24.4 ms                                                      | 24.4 ms: 1.00x faster                                        |
| asyncio_tcp_ssl            | 1.57 sec                                                     | 1.58 sec: 1.01x slower                                       |
| sympy_expand               | 492 ms                                                       | 496 ms: 1.01x slower                                         |
| json_loads                 | 24.3 us                                                      | 24.6 us: 1.01x slower                                        |
| sqlglot_optimize           | 58.4 ms                                                      | 59.3 ms: 1.02x slower                                        |
| mypy2                      | 365 ms                                                       | 371 ms: 1.02x slower                                         |
| xml_etree_process          | 58.3 ms                                                      | 59.3 ms: 1.02x slower                                        |
| sqlglot_parse              | 1.41 ms                                                      | 1.43 ms: 1.02x slower                                        |
| xml_etree_parse            | 147 ms                                                       | 150 ms: 1.02x slower                                         |
| typing_runtime_protocols   | 150 us                                                       | 153 us: 1.02x slower                                         |
| mako                       | 10.1 ms                                                      | 10.3 ms: 1.02x slower                                        |
| async_tree_none_tg         | 440 ms                                                       | 449 ms: 1.02x slower                                         |
| scimark_fft                | 303 ms                                                       | 310 ms: 1.02x slower                                         |
| async_generators           | 385 ms                                                       | 394 ms: 1.02x slower                                         |
| pickle                     | 10.0 us                                                      | 10.3 us: 1.02x slower                                        |
| scimark_lu                 | 98.6 ms                                                      | 101 ms: 1.02x slower                                         |
| sqlglot_transpile          | 1.80 ms                                                      | 1.85 ms: 1.02x slower                                        |
| json_dumps                 | 10.3 ms                                                      | 10.5 ms: 1.03x slower                                        |
| regex_compile              | 145 ms                                                       | 149 ms: 1.03x slower                                         |
| async_tree_cpu_io_mixed_tg | 706 ms                                                       | 727 ms: 1.03x slower                                         |
| deepcopy                   | 371 us                                                       | 382 us: 1.03x slower                                         |
| pprint_pformat             | 1.64 sec                                                     | 1.70 sec: 1.03x slower                                       |
| logging_format             | 7.29 us                                                      | 7.53 us: 1.03x slower                                        |
| meteor_contest             | 126 ms                                                       | 131 ms: 1.03x slower                                         |
| pprint_safe_repr           | 808 ms                                                       | 836 ms: 1.03x slower                                         |
| async_tree_memoization_tg  | 554 ms                                                       | 573 ms: 1.03x slower                                         |
| async_tree_io              | 1.06 sec                                                     | 1.10 sec: 1.04x slower                                       |
| pickle_list                | 4.22 us                                                      | 4.38 us: 1.04x slower                                        |
| create_gc_cycles           | 1.58 ms                                                      | 1.64 ms: 1.04x slower                                        |
| async_tree_io_tg           | 1.07 sec                                                     | 1.11 sec: 1.04x slower                                       |
| deepcopy_memo              | 36.6 us                                                      | 38.1 us: 1.04x slower                                        |
| tomli_loads                | 2.17 sec                                                     | 2.26 sec: 1.04x slower                                       |
| 2to3                       | 285 ms                                                       | 297 ms: 1.04x slower                                         |
| logging_simple             | 6.64 us                                                      | 6.96 us: 1.05x slower                                        |
| pathlib                    | 18.7 ms                                                      | 19.7 ms: 1.05x slower                                        |
| xml_etree_iterparse        | 104 ms                                                       | 109 ms: 1.05x slower                                         |
| unpickle_pure_python       | 210 us                                                       | 221 us: 1.05x slower                                         |
| gc_traversal               | 3.70 ms                                                      | 3.92 ms: 1.06x slower                                        |
| dulwich_log                | 64.9 ms                                                      | 69.0 ms: 1.06x slower                                        |
| fannkuch                   | 362 ms                                                       | 385 ms: 1.06x slower                                         |
| logging_silent             | 93.3 ns                                                      | 99.4 ns: 1.07x slower                                        |
| chameleon                  | 7.27 ms                                                      | 7.79 ms: 1.07x slower                                        |
| hexiom                     | 5.97 ms                                                      | 6.54 ms: 1.09x slower                                        |
| python_startup             | 11.7 ms                                                      | 12.9 ms: 1.10x slower                                        |
| telco                      | 7.16 ms                                                      | 8.18 ms: 1.14x slower                                        |
| deltablue                  | 3.24 ms                                                      | 3.71 ms: 1.14x slower                                        |
| go                         | 149 ms                                                       | 171 ms: 1.15x slower                                         |
| pyflate                    | 442 ms                                                       | 516 ms: 1.17x slower                                         |
| richards_super             | 50.8 ms                                                      | 61.1 ms: 1.20x slower                                        |
| coverage                   | 66.3 ms                                                      | 79.9 ms: 1.21x slower                                        |
| richards                   | 45.1 ms                                                      | 55.9 ms: 1.24x slower                                        |
| python_startup_no_site     | 8.67 ms                                                      | 11.3 ms: 1.31x slower                                        |
| scimark_sor                | 107 ms                                                       | 150 ms: 1.40x slower                                         |
| Geometric mean             | (ref)                                                        | 1.02x slower                                                 |

Benchmark hidden because not significant (13): json, scimark_monte_carlo, spectral_norm, nbody, pidigits, pickle_pure_python, pycparser, tornado_http, coroutines, async_tree_memoization, asyncio_websockets, async_tree_cpu_io_mixed, bench_thread_pool
Ignored benchmarks (6) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, dask, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 99.98% likely to be slow
- 90% likely to have a slowdown of 1.01x
- 95% likely to have a slowdown of 1.01x
- 99% likely to have a slowdown of 1.00x
