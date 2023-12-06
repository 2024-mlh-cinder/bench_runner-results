
# Results vs. 3.12.0

- fork: mdboom
- ref: alternative_workarou
- machine: linux-x86_64
- commit hash: d452c37
- commit date: 2023-11-20
- overall geometric mean: 1.01x slower \*
- HPT reliability: 98.49%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-pythonperf2-x86_64-mdboom-alternative_workarou-3.13.0a1+-d452c37 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| 2to3           | 285 ms                                                       | 292 ms: 1.03x slower                                                         |
| chameleon      | 7.27 ms                                                      | 7.58 ms: 1.04x slower                                                        |
| docutils       | 2.89 sec                                                     | 2.84 sec: 1.02x faster                                                       |
| tornado_http   | 122 ms                                                       | 119 ms: 1.03x faster                                                         |
| Geometric mean | (ref)                                                        | 1.01x slower                                                                 |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-pythonperf2-x86_64-mdboom-alternative_workarou-3.13.0a1+-d452c37 |
|----------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| async_tree_none            | 459 ms                                                       | 432 ms: 1.06x faster                                                         |
| async_tree_memoization     | 554 ms                                                       | 545 ms: 1.02x faster                                                         |
| async_tree_cpu_io_mixed    | 704 ms                                                       | 696 ms: 1.01x faster                                                         |
| async_tree_cpu_io_mixed_tg | 706 ms                                                       | 712 ms: 1.01x slower                                                         |
| async_tree_io              | 1.06 sec                                                     | 1.08 sec: 1.02x slower                                                       |
| async_tree_io_tg           | 1.07 sec                                                     | 1.09 sec: 1.02x slower                                                       |
| async_tree_memoization_tg  | 554 ms                                                       | 570 ms: 1.03x slower                                                         |
| Geometric mean             | (ref)                                                        | 1.00x faster                                                                 |

Benchmark hidden because not significant (1): async_tree_none_tg

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-pythonperf2-x86_64-mdboom-alternative_workarou-3.13.0a1+-d452c37 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| pidigits       | 264 ms                                                       | 267 ms: 1.01x slower                                                         |
| Geometric mean | (ref)                                                        | 1.01x faster                                                                 |

Benchmark hidden because not significant (2): float, nbody

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-pythonperf2-x86_64-mdboom-alternative_workarou-3.13.0a1+-d452c37 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| regex_effbot   | 3.61 ms                                                      | 3.58 ms: 1.01x faster                                                        |
| regex_compile  | 145 ms                                                       | 145 ms: 1.01x slower                                                         |
| regex_v8       | 24.4 ms                                                      | 25.6 ms: 1.05x slower                                                        |
| regex_dna      | 240 ms                                                       | 252 ms: 1.05x slower                                                         |
| Geometric mean | (ref)                                                        | 1.02x slower                                                                 |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-pythonperf2-x86_64-mdboom-alternative_workarou-3.13.0a1+-d452c37 |
|----------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| pickle_pure_python   | 319 us                                                       | 309 us: 1.03x faster                                                         |
| unpickle             | 15.3 us                                                      | 15.0 us: 1.02x faster                                                        |
| xml_etree_generate   | 85.3 ms                                                      | 85.2 ms: 1.00x faster                                                        |
| xml_etree_process    | 58.3 ms                                                      | 58.8 ms: 1.01x slower                                                        |
| pickle               | 10.0 us                                                      | 10.2 us: 1.01x slower                                                        |
| xml_etree_iterparse  | 104 ms                                                       | 106 ms: 1.02x slower                                                         |
| xml_etree_parse      | 147 ms                                                       | 150 ms: 1.02x slower                                                         |
| json_dumps           | 10.3 ms                                                      | 10.6 ms: 1.03x slower                                                        |
| json_loads           | 24.3 us                                                      | 25.3 us: 1.04x slower                                                        |
| tomli_loads          | 2.17 sec                                                     | 2.28 sec: 1.05x slower                                                       |
| pickle_list          | 4.22 us                                                      | 4.46 us: 1.06x slower                                                        |
| unpickle_pure_python | 210 us                                                       | 224 us: 1.07x slower                                                         |
| Geometric mean       | (ref)                                                        | 1.02x slower                                                                 |

Benchmark hidden because not significant (2): unpickle_list, pickle_dict

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-pythonperf2-x86_64-mdboom-alternative_workarou-3.13.0a1+-d452c37 |
|------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| python_startup         | 11.7 ms                                                      | 12.8 ms: 1.10x slower                                                        |
| python_startup_no_site | 8.67 ms                                                      | 11.3 ms: 1.30x slower                                                        |
| Geometric mean         | (ref)                                                        | 1.20x slower                                                                 |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-pythonperf2-x86_64-mdboom-alternative_workarou-3.13.0a1+-d452c37 |
|-----------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| mako      | 10.1 ms                                                      | 10.2 ms: 1.02x slower                                                        |

All benchmarks:
===============

| Benchmark                  | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-pythonperf2-x86_64-mdboom-alternative_workarou-3.13.0a1+-d452c37 |
|----------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| comprehensions             | 21.8 us                                                      | 16.7 us: 1.31x faster                                                        |
| typing_runtime_protocols   | 150 us                                                       | 126 us: 1.20x faster                                                         |
| crypto_pyaes               | 82.4 ms                                                      | 71.2 ms: 1.16x faster                                                        |
| unpack_sequence            | 54.5 ns                                                      | 48.0 ns: 1.14x faster                                                        |
| raytrace                   | 301 ms                                                       | 271 ms: 1.11x faster                                                         |
| bench_mp_pool              | 4.96 ms                                                      | 4.49 ms: 1.10x faster                                                        |
| generators                 | 37.3 ms                                                      | 34.2 ms: 1.09x faster                                                        |
| sympy_sum                  | 163 ms                                                       | 152 ms: 1.07x faster                                                         |
| scimark_sparse_mat_mult    | 4.49 ms                                                      | 4.20 ms: 1.07x faster                                                        |
| chaos                      | 64.1 ms                                                      | 60.0 ms: 1.07x faster                                                        |
| async_generators           | 385 ms                                                       | 362 ms: 1.06x faster                                                         |
| async_tree_none            | 459 ms                                                       | 432 ms: 1.06x faster                                                         |
| sympy_str                  | 305 ms                                                       | 290 ms: 1.05x faster                                                         |
| scimark_monte_carlo        | 69.5 ms                                                      | 66.5 ms: 1.05x faster                                                        |
| sympy_integrate            | 24.0 ms                                                      | 23.0 ms: 1.04x faster                                                        |
| coroutines                 | 23.1 ms                                                      | 22.2 ms: 1.04x faster                                                        |
| pickle_pure_python         | 319 us                                                       | 309 us: 1.03x faster                                                         |
| sqlglot_normalize          | 119 ms                                                       | 115 ms: 1.03x faster                                                         |
| asyncio_tcp                | 380 ms                                                       | 368 ms: 1.03x faster                                                         |
| tornado_http               | 122 ms                                                       | 119 ms: 1.03x faster                                                         |
| deepcopy_reduce            | 3.41 us                                                      | 3.33 us: 1.03x faster                                                        |
| unpickle                   | 15.3 us                                                      | 15.0 us: 1.02x faster                                                        |
| spectral_norm              | 93.9 ms                                                      | 92.0 ms: 1.02x faster                                                        |
| nqueens                    | 90.1 ms                                                      | 88.5 ms: 1.02x faster                                                        |
| docutils                   | 2.89 sec                                                     | 2.84 sec: 1.02x faster                                                       |
| async_tree_memoization     | 554 ms                                                       | 545 ms: 1.02x faster                                                         |
| async_tree_cpu_io_mixed    | 704 ms                                                       | 696 ms: 1.01x faster                                                         |
| mdp                        | 2.56 sec                                                     | 2.53 sec: 1.01x faster                                                       |
| sqlglot_parse              | 1.41 ms                                                      | 1.39 ms: 1.01x faster                                                        |
| regex_effbot               | 3.61 ms                                                      | 3.58 ms: 1.01x faster                                                        |
| asyncio_tcp_ssl            | 1.57 sec                                                     | 1.57 sec: 1.00x faster                                                       |
| xml_etree_generate         | 85.3 ms                                                      | 85.2 ms: 1.00x faster                                                        |
| pathlib                    | 18.7 ms                                                      | 18.8 ms: 1.00x slower                                                        |
| regex_compile              | 145 ms                                                       | 145 ms: 1.01x slower                                                         |
| sympy_expand               | 492 ms                                                       | 495 ms: 1.01x slower                                                         |
| json                       | 5.17 ms                                                      | 5.21 ms: 1.01x slower                                                        |
| xml_etree_process          | 58.3 ms                                                      | 58.8 ms: 1.01x slower                                                        |
| pprint_safe_repr           | 808 ms                                                       | 814 ms: 1.01x slower                                                         |
| pidigits                   | 264 ms                                                       | 267 ms: 1.01x slower                                                         |
| pprint_pformat             | 1.64 sec                                                     | 1.66 sec: 1.01x slower                                                       |
| async_tree_cpu_io_mixed_tg | 706 ms                                                       | 712 ms: 1.01x slower                                                         |
| scimark_lu                 | 98.6 ms                                                      | 99.6 ms: 1.01x slower                                                        |
| dask                       | 394 ms                                                       | 398 ms: 1.01x slower                                                         |
| logging_format             | 7.29 us                                                      | 7.38 us: 1.01x slower                                                        |
| pickle                     | 10.0 us                                                      | 10.2 us: 1.01x slower                                                        |
| meteor_contest             | 126 ms                                                       | 128 ms: 1.01x slower                                                         |
| asyncio_websockets         | 386 ms                                                       | 391 ms: 1.01x slower                                                         |
| scimark_fft                | 303 ms                                                       | 308 ms: 1.02x slower                                                         |
| mako                       | 10.1 ms                                                      | 10.2 ms: 1.02x slower                                                        |
| async_tree_io              | 1.06 sec                                                     | 1.08 sec: 1.02x slower                                                       |
| gc_traversal               | 3.70 ms                                                      | 3.78 ms: 1.02x slower                                                        |
| async_tree_io_tg           | 1.07 sec                                                     | 1.09 sec: 1.02x slower                                                       |
| pycparser                  | 1.29 sec                                                     | 1.32 sec: 1.02x slower                                                       |
| xml_etree_iterparse        | 104 ms                                                       | 106 ms: 1.02x slower                                                         |
| xml_etree_parse            | 147 ms                                                       | 150 ms: 1.02x slower                                                         |
| 2to3                       | 285 ms                                                       | 292 ms: 1.03x slower                                                         |
| deepcopy_memo              | 36.6 us                                                      | 37.6 us: 1.03x slower                                                        |
| async_tree_memoization_tg  | 554 ms                                                       | 570 ms: 1.03x slower                                                         |
| create_gc_cycles           | 1.58 ms                                                      | 1.63 ms: 1.03x slower                                                        |
| json_dumps                 | 10.3 ms                                                      | 10.6 ms: 1.03x slower                                                        |
| dulwich_log                | 64.9 ms                                                      | 67.2 ms: 1.04x slower                                                        |
| json_loads                 | 24.3 us                                                      | 25.3 us: 1.04x slower                                                        |
| logging_silent             | 93.3 ns                                                      | 97.2 ns: 1.04x slower                                                        |
| chameleon                  | 7.27 ms                                                      | 7.58 ms: 1.04x slower                                                        |
| regex_v8                   | 24.4 ms                                                      | 25.6 ms: 1.05x slower                                                        |
| regex_dna                  | 240 ms                                                       | 252 ms: 1.05x slower                                                         |
| tomli_loads                | 2.17 sec                                                     | 2.28 sec: 1.05x slower                                                       |
| pickle_list                | 4.22 us                                                      | 4.46 us: 1.06x slower                                                        |
| unpickle_pure_python       | 210 us                                                       | 224 us: 1.07x slower                                                         |
| fannkuch                   | 362 ms                                                       | 386 ms: 1.07x slower                                                         |
| hexiom                     | 5.97 ms                                                      | 6.44 ms: 1.08x slower                                                        |
| python_startup             | 11.7 ms                                                      | 12.8 ms: 1.10x slower                                                        |
| deltablue                  | 3.24 ms                                                      | 3.56 ms: 1.10x slower                                                        |
| telco                      | 7.16 ms                                                      | 8.03 ms: 1.12x slower                                                        |
| go                         | 149 ms                                                       | 169 ms: 1.14x slower                                                         |
| pyflate                    | 442 ms                                                       | 508 ms: 1.15x slower                                                         |
| richards_super             | 50.8 ms                                                      | 58.6 ms: 1.15x slower                                                        |
| richards                   | 45.1 ms                                                      | 52.7 ms: 1.17x slower                                                        |
| coverage                   | 66.3 ms                                                      | 85.4 ms: 1.29x slower                                                        |
| python_startup_no_site     | 8.67 ms                                                      | 11.3 ms: 1.30x slower                                                        |
| scimark_sor                | 107 ms                                                       | 146 ms: 1.37x slower                                                         |
| Geometric mean             | (ref)                                                        | 1.01x slower                                                                 |

Benchmark hidden because not significant (12): float, nbody, sqlglot_transpile, logging_simple, sqlglot_optimize, unpickle_list, pickle_dict, bench_thread_pool, deepcopy, sqlite_synth, mypy2, async_tree_none_tg
Ignored benchmarks (5) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 98.49% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
