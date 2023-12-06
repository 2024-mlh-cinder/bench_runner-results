
# Results vs. 3.12.0

- fork: brandtbucher
- ref: justin_no_stubs
- machine: linux-x86_64
- commit hash: 925f140
- commit date: 2023-11-20
- overall geometric mean: 1.04x slower \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.01x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-pythonperf2-x86_64-brandtbucher-justin_no_stubs-3.13.0a1+-925f140 |
|----------------|:------------------------------------------------------------:|:-----------------------------------------------------------------------------:|
| 2to3           | 285 ms                                                       | 301 ms: 1.06x slower                                                          |
| chameleon      | 7.27 ms                                                      | 7.50 ms: 1.03x slower                                                         |
| docutils       | 2.89 sec                                                     | 2.87 sec: 1.01x faster                                                        |
| tornado_http   | 122 ms                                                       | 120 ms: 1.02x faster                                                          |
| Geometric mean | (ref)                                                        | 1.02x slower                                                                  |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-pythonperf2-x86_64-brandtbucher-justin_no_stubs-3.13.0a1+-925f140 |
|----------------------------|:------------------------------------------------------------:|:-----------------------------------------------------------------------------:|
| async_tree_none            | 459 ms                                                       | 436 ms: 1.05x faster                                                          |
| async_tree_memoization     | 554 ms                                                       | 547 ms: 1.01x faster                                                          |
| async_tree_none_tg         | 440 ms                                                       | 444 ms: 1.01x slower                                                          |
| async_tree_cpu_io_mixed_tg | 706 ms                                                       | 720 ms: 1.02x slower                                                          |
| async_tree_io              | 1.06 sec                                                     | 1.08 sec: 1.02x slower                                                        |
| async_tree_io_tg           | 1.07 sec                                                     | 1.10 sec: 1.02x slower                                                        |
| async_tree_memoization_tg  | 554 ms                                                       | 571 ms: 1.03x slower                                                          |
| Geometric mean             | (ref)                                                        | 1.00x slower                                                                  |

Benchmark hidden because not significant (1): async_tree_cpu_io_mixed

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-pythonperf2-x86_64-brandtbucher-justin_no_stubs-3.13.0a1+-925f140 |
|----------------|:------------------------------------------------------------:|:-----------------------------------------------------------------------------:|
| float          | 81.6 ms                                                      | 79.1 ms: 1.03x faster                                                         |
| pidigits       | 264 ms                                                       | 265 ms: 1.00x slower                                                          |
| nbody          | 88.2 ms                                                      | 95.7 ms: 1.08x slower                                                         |
| Geometric mean | (ref)                                                        | 1.02x slower                                                                  |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-pythonperf2-x86_64-brandtbucher-justin_no_stubs-3.13.0a1+-925f140 |
|----------------|:------------------------------------------------------------:|:-----------------------------------------------------------------------------:|
| regex_effbot   | 3.61 ms                                                      | 3.49 ms: 1.04x faster                                                         |
| regex_dna      | 240 ms                                                       | 244 ms: 1.02x slower                                                          |
| regex_compile  | 145 ms                                                       | 149 ms: 1.03x slower                                                          |
| regex_v8       | 24.4 ms                                                      | 25.4 ms: 1.04x slower                                                         |
| Geometric mean | (ref)                                                        | 1.01x slower                                                                  |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-pythonperf2-x86_64-brandtbucher-justin_no_stubs-3.13.0a1+-925f140 |
|----------------------|:------------------------------------------------------------:|:-----------------------------------------------------------------------------:|
| pickle_pure_python   | 319 us                                                       | 311 us: 1.03x faster                                                          |
| unpickle             | 15.3 us                                                      | 15.1 us: 1.01x faster                                                         |
| xml_etree_generate   | 85.3 ms                                                      | 85.6 ms: 1.00x slower                                                         |
| xml_etree_process    | 58.3 ms                                                      | 58.9 ms: 1.01x slower                                                         |
| pickle_dict          | 32.0 us                                                      | 32.3 us: 1.01x slower                                                         |
| xml_etree_iterparse  | 104 ms                                                       | 105 ms: 1.01x slower                                                          |
| pickle_list          | 4.22 us                                                      | 4.40 us: 1.04x slower                                                         |
| tomli_loads          | 2.17 sec                                                     | 2.27 sec: 1.05x slower                                                        |
| json_dumps           | 10.3 ms                                                      | 10.8 ms: 1.05x slower                                                         |
| json_loads           | 24.3 us                                                      | 25.6 us: 1.05x slower                                                         |
| unpickle_pure_python | 210 us                                                       | 222 us: 1.06x slower                                                          |
| Geometric mean       | (ref)                                                        | 1.02x slower                                                                  |

Benchmark hidden because not significant (3): pickle, xml_etree_parse, unpickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-pythonperf2-x86_64-brandtbucher-justin_no_stubs-3.13.0a1+-925f140 |
|------------------------|:------------------------------------------------------------:|:-----------------------------------------------------------------------------:|
| python_startup         | 11.7 ms                                                      | 12.9 ms: 1.10x slower                                                         |
| python_startup_no_site | 8.67 ms                                                      | 11.3 ms: 1.31x slower                                                         |
| Geometric mean         | (ref)                                                        | 1.20x slower                                                                  |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-pythonperf2-x86_64-brandtbucher-justin_no_stubs-3.13.0a1+-925f140 |
|-----------|:------------------------------------------------------------:|:-----------------------------------------------------------------------------:|
| mako      | 10.1 ms                                                      | 11.0 ms: 1.09x slower                                                         |

All benchmarks:
===============

| Benchmark                  | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-pythonperf2-x86_64-brandtbucher-justin_no_stubs-3.13.0a1+-925f140 |
|----------------------------|:------------------------------------------------------------:|:-----------------------------------------------------------------------------:|
| typing_runtime_protocols   | 150 us                                                       | 130 us: 1.16x faster                                                          |
| unpack_sequence            | 54.5 ns                                                      | 47.9 ns: 1.14x faster                                                         |
| comprehensions             | 21.8 us                                                      | 20.2 us: 1.08x faster                                                         |
| gc_traversal               | 3.70 ms                                                      | 3.45 ms: 1.08x faster                                                         |
| bench_mp_pool              | 4.96 ms                                                      | 4.66 ms: 1.06x faster                                                         |
| raytrace                   | 301 ms                                                       | 285 ms: 1.06x faster                                                          |
| async_tree_none            | 459 ms                                                       | 436 ms: 1.05x faster                                                          |
| deepcopy_reduce            | 3.41 us                                                      | 3.28 us: 1.04x faster                                                         |
| regex_effbot               | 3.61 ms                                                      | 3.49 ms: 1.04x faster                                                         |
| float                      | 81.6 ms                                                      | 79.1 ms: 1.03x faster                                                         |
| asyncio_tcp                | 380 ms                                                       | 368 ms: 1.03x faster                                                          |
| pickle_pure_python         | 319 us                                                       | 311 us: 1.03x faster                                                          |
| generators                 | 37.3 ms                                                      | 36.4 ms: 1.03x faster                                                         |
| sympy_sum                  | 163 ms                                                       | 159 ms: 1.03x faster                                                          |
| sympy_str                  | 305 ms                                                       | 300 ms: 1.02x faster                                                          |
| tornado_http               | 122 ms                                                       | 120 ms: 1.02x faster                                                          |
| coroutines                 | 23.1 ms                                                      | 22.7 ms: 1.02x faster                                                         |
| unpickle                   | 15.3 us                                                      | 15.1 us: 1.01x faster                                                         |
| deepcopy                   | 371 us                                                       | 367 us: 1.01x faster                                                          |
| async_tree_memoization     | 554 ms                                                       | 547 ms: 1.01x faster                                                          |
| logging_simple             | 6.64 us                                                      | 6.57 us: 1.01x faster                                                         |
| docutils                   | 2.89 sec                                                     | 2.87 sec: 1.01x faster                                                        |
| async_generators           | 385 ms                                                       | 383 ms: 1.01x faster                                                          |
| asyncio_tcp_ssl            | 1.57 sec                                                     | 1.57 sec: 1.00x slower                                                        |
| pidigits                   | 264 ms                                                       | 265 ms: 1.00x slower                                                          |
| xml_etree_generate         | 85.3 ms                                                      | 85.6 ms: 1.00x slower                                                         |
| sqlite_synth               | 2.72 us                                                      | 2.73 us: 1.00x slower                                                         |
| deepcopy_memo              | 36.6 us                                                      | 36.8 us: 1.01x slower                                                         |
| sqlglot_parse              | 1.41 ms                                                      | 1.42 ms: 1.01x slower                                                         |
| sympy_integrate            | 24.0 ms                                                      | 24.2 ms: 1.01x slower                                                         |
| async_tree_none_tg         | 440 ms                                                       | 444 ms: 1.01x slower                                                          |
| asyncio_websockets         | 386 ms                                                       | 390 ms: 1.01x slower                                                          |
| xml_etree_process          | 58.3 ms                                                      | 58.9 ms: 1.01x slower                                                         |
| pickle_dict                | 32.0 us                                                      | 32.3 us: 1.01x slower                                                         |
| sqlglot_normalize          | 119 ms                                                       | 120 ms: 1.01x slower                                                          |
| xml_etree_iterparse        | 104 ms                                                       | 105 ms: 1.01x slower                                                          |
| json                       | 5.17 ms                                                      | 5.24 ms: 1.01x slower                                                         |
| regex_dna                  | 240 ms                                                       | 244 ms: 1.02x slower                                                          |
| dask                       | 394 ms                                                       | 400 ms: 1.02x slower                                                          |
| sympy_expand               | 492 ms                                                       | 500 ms: 1.02x slower                                                          |
| async_tree_cpu_io_mixed_tg | 706 ms                                                       | 720 ms: 1.02x slower                                                          |
| async_tree_io              | 1.06 sec                                                     | 1.08 sec: 1.02x slower                                                        |
| sqlglot_transpile          | 1.80 ms                                                      | 1.84 ms: 1.02x slower                                                         |
| async_tree_io_tg           | 1.07 sec                                                     | 1.10 sec: 1.02x slower                                                        |
| bench_thread_pool          | 956 us                                                       | 980 us: 1.02x slower                                                          |
| pycparser                  | 1.29 sec                                                     | 1.33 sec: 1.03x slower                                                        |
| pathlib                    | 18.7 ms                                                      | 19.3 ms: 1.03x slower                                                         |
| chameleon                  | 7.27 ms                                                      | 7.50 ms: 1.03x slower                                                         |
| async_tree_memoization_tg  | 554 ms                                                       | 571 ms: 1.03x slower                                                          |
| regex_compile              | 145 ms                                                       | 149 ms: 1.03x slower                                                          |
| mypy2                      | 365 ms                                                       | 378 ms: 1.04x slower                                                          |
| regex_v8                   | 24.4 ms                                                      | 25.4 ms: 1.04x slower                                                         |
| dulwich_log                | 64.9 ms                                                      | 67.6 ms: 1.04x slower                                                         |
| pickle_list                | 4.22 us                                                      | 4.40 us: 1.04x slower                                                         |
| mdp                        | 2.56 sec                                                     | 2.67 sec: 1.05x slower                                                        |
| scimark_lu                 | 98.6 ms                                                      | 103 ms: 1.05x slower                                                          |
| meteor_contest             | 126 ms                                                       | 132 ms: 1.05x slower                                                          |
| tomli_loads                | 2.17 sec                                                     | 2.27 sec: 1.05x slower                                                        |
| json_dumps                 | 10.3 ms                                                      | 10.8 ms: 1.05x slower                                                         |
| sqlglot_optimize           | 58.4 ms                                                      | 61.4 ms: 1.05x slower                                                         |
| json_loads                 | 24.3 us                                                      | 25.6 us: 1.05x slower                                                         |
| unpickle_pure_python       | 210 us                                                       | 222 us: 1.06x slower                                                          |
| 2to3                       | 285 ms                                                       | 301 ms: 1.06x slower                                                          |
| pprint_safe_repr           | 808 ms                                                       | 860 ms: 1.06x slower                                                          |
| logging_silent             | 93.3 ns                                                      | 99.3 ns: 1.06x slower                                                         |
| pprint_pformat             | 1.64 sec                                                     | 1.76 sec: 1.07x slower                                                        |
| nbody                      | 88.2 ms                                                      | 95.7 ms: 1.08x slower                                                         |
| mako                       | 10.1 ms                                                      | 11.0 ms: 1.09x slower                                                         |
| chaos                      | 64.1 ms                                                      | 70.4 ms: 1.10x slower                                                         |
| python_startup             | 11.7 ms                                                      | 12.9 ms: 1.10x slower                                                         |
| spectral_norm              | 93.9 ms                                                      | 106 ms: 1.13x slower                                                          |
| richards                   | 45.1 ms                                                      | 50.9 ms: 1.13x slower                                                         |
| richards_super             | 50.8 ms                                                      | 57.4 ms: 1.13x slower                                                         |
| fannkuch                   | 362 ms                                                       | 411 ms: 1.14x slower                                                          |
| telco                      | 7.16 ms                                                      | 8.22 ms: 1.15x slower                                                         |
| nqueens                    | 90.1 ms                                                      | 104 ms: 1.15x slower                                                          |
| deltablue                  | 3.24 ms                                                      | 3.74 ms: 1.16x slower                                                         |
| go                         | 149 ms                                                       | 172 ms: 1.16x slower                                                          |
| scimark_monte_carlo        | 69.5 ms                                                      | 80.9 ms: 1.16x slower                                                         |
| pyflate                    | 442 ms                                                       | 522 ms: 1.18x slower                                                          |
| scimark_fft                | 303 ms                                                       | 364 ms: 1.20x slower                                                          |
| coverage                   | 66.3 ms                                                      | 80.8 ms: 1.22x slower                                                         |
| hexiom                     | 5.97 ms                                                      | 7.78 ms: 1.30x slower                                                         |
| python_startup_no_site     | 8.67 ms                                                      | 11.3 ms: 1.31x slower                                                         |
| scimark_sor                | 107 ms                                                       | 147 ms: 1.38x slower                                                          |
| Geometric mean             | (ref)                                                        | 1.04x slower                                                                  |

Benchmark hidden because not significant (8): async_tree_cpu_io_mixed, scimark_sparse_mat_mult, pickle, xml_etree_parse, unpickle_list, crypto_pyaes, logging_format, create_gc_cycles
Ignored benchmarks (5) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.01x
- 95% likely to have a slowdown of 1.01x
- 99% likely to have a slowdown of 1.01x
