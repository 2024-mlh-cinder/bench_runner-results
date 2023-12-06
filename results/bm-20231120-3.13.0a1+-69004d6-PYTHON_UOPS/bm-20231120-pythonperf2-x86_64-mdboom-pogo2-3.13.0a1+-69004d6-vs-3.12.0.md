
# Results vs. 3.12.0

- fork: mdboom
- ref: pogo2
- machine: linux-x86_64
- commit hash: 69004d6
- commit date: 2023-11-20
- overall geometric mean: 1.13x slower \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.05x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-pythonperf2-x86_64-mdboom-pogo2-3.13.0a1+-69004d6 |
|----------------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| 2to3           | 285 ms                                                       | 318 ms: 1.12x slower                                          |
| chameleon      | 7.27 ms                                                      | 7.81 ms: 1.07x slower                                         |
| docutils       | 2.89 sec                                                     | 2.95 sec: 1.02x slower                                        |
| tornado_http   | 122 ms                                                       | 125 ms: 1.02x slower                                          |
| Geometric mean | (ref)                                                        | 1.06x slower                                                  |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-pythonperf2-x86_64-mdboom-pogo2-3.13.0a1+-69004d6 |
|----------------------------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| async_tree_none            | 459 ms                                                       | 451 ms: 1.02x faster                                          |
| async_tree_cpu_io_mixed    | 704 ms                                                       | 717 ms: 1.02x slower                                          |
| async_tree_memoization     | 554 ms                                                       | 566 ms: 1.02x slower                                          |
| async_tree_memoization_tg  | 554 ms                                                       | 569 ms: 1.03x slower                                          |
| async_tree_cpu_io_mixed_tg | 706 ms                                                       | 732 ms: 1.04x slower                                          |
| async_tree_none_tg         | 440 ms                                                       | 458 ms: 1.04x slower                                          |
| async_tree_io              | 1.06 sec                                                     | 1.11 sec: 1.05x slower                                        |
| async_tree_io_tg           | 1.07 sec                                                     | 1.13 sec: 1.05x slower                                        |
| Geometric mean             | (ref)                                                        | 1.03x slower                                                  |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-pythonperf2-x86_64-mdboom-pogo2-3.13.0a1+-69004d6 |
|----------------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| pidigits       | 264 ms                                                       | 268 ms: 1.01x slower                                          |
| float          | 81.6 ms                                                      | 114 ms: 1.39x slower                                          |
| nbody          | 88.2 ms                                                      | 149 ms: 1.69x slower                                          |
| Geometric mean | (ref)                                                        | 1.34x slower                                                  |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-pythonperf2-x86_64-mdboom-pogo2-3.13.0a1+-69004d6 |
|----------------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| regex_effbot   | 3.61 ms                                                      | 3.48 ms: 1.04x faster                                         |
| regex_dna      | 240 ms                                                       | 241 ms: 1.00x slower                                          |
| regex_v8       | 24.4 ms                                                      | 24.7 ms: 1.01x slower                                         |
| regex_compile  | 145 ms                                                       | 178 ms: 1.23x slower                                          |
| Geometric mean | (ref)                                                        | 1.05x slower                                                  |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-pythonperf2-x86_64-mdboom-pogo2-3.13.0a1+-69004d6 |
|----------------------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| unpickle             | 15.3 us                                                      | 14.8 us: 1.04x faster                                         |
| pickle_pure_python   | 319 us                                                       | 309 us: 1.03x faster                                          |
| unpickle_list        | 4.65 us                                                      | 4.75 us: 1.02x slower                                         |
| pickle_dict          | 32.0 us                                                      | 33.0 us: 1.03x slower                                         |
| json_dumps           | 10.3 ms                                                      | 10.6 ms: 1.03x slower                                         |
| json_loads           | 24.3 us                                                      | 25.2 us: 1.04x slower                                         |
| pickle_list          | 4.22 us                                                      | 4.50 us: 1.07x slower                                         |
| xml_etree_generate   | 85.3 ms                                                      | 92.2 ms: 1.08x slower                                         |
| xml_etree_process    | 58.3 ms                                                      | 63.3 ms: 1.09x slower                                         |
| xml_etree_iterparse  | 104 ms                                                       | 123 ms: 1.18x slower                                          |
| unpickle_pure_python | 210 us                                                       | 255 us: 1.21x slower                                          |
| tomli_loads          | 2.17 sec                                                     | 2.96 sec: 1.36x slower                                        |
| Geometric mean       | (ref)                                                        | 1.07x slower                                                  |

Benchmark hidden because not significant (2): xml_etree_parse, pickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-pythonperf2-x86_64-mdboom-pogo2-3.13.0a1+-69004d6 |
|------------------------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| python_startup         | 11.7 ms                                                      | 12.8 ms: 1.10x slower                                         |
| python_startup_no_site | 8.67 ms                                                      | 11.3 ms: 1.30x slower                                         |
| Geometric mean         | (ref)                                                        | 1.20x slower                                                  |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-pythonperf2-x86_64-mdboom-pogo2-3.13.0a1+-69004d6 |
|-----------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| mako      | 10.1 ms                                                      | 17.9 ms: 1.77x slower                                         |

All benchmarks:
===============

| Benchmark                  | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-pythonperf2-x86_64-mdboom-pogo2-3.13.0a1+-69004d6 |
|----------------------------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| typing_runtime_protocols   | 150 us                                                       | 132 us: 1.14x faster                                          |
| generators                 | 37.3 ms                                                      | 35.2 ms: 1.06x faster                                         |
| deepcopy_reduce            | 3.41 us                                                      | 3.27 us: 1.04x faster                                         |
| bench_mp_pool              | 4.96 ms                                                      | 4.77 ms: 1.04x faster                                         |
| regex_effbot               | 3.61 ms                                                      | 3.48 ms: 1.04x faster                                         |
| unpickle                   | 15.3 us                                                      | 14.8 us: 1.04x faster                                         |
| coroutines                 | 23.1 ms                                                      | 22.3 ms: 1.03x faster                                         |
| pickle_pure_python         | 319 us                                                       | 309 us: 1.03x faster                                          |
| unpack_sequence            | 54.5 ns                                                      | 52.8 ns: 1.03x faster                                         |
| async_tree_none            | 459 ms                                                       | 451 ms: 1.02x faster                                          |
| asyncio_tcp                | 380 ms                                                       | 374 ms: 1.02x faster                                          |
| regex_dna                  | 240 ms                                                       | 241 ms: 1.00x slower                                          |
| json                       | 5.17 ms                                                      | 5.20 ms: 1.01x slower                                         |
| asyncio_tcp_ssl            | 1.57 sec                                                     | 1.59 sec: 1.01x slower                                        |
| regex_v8                   | 24.4 ms                                                      | 24.7 ms: 1.01x slower                                         |
| pidigits                   | 264 ms                                                       | 268 ms: 1.01x slower                                          |
| logging_format             | 7.29 us                                                      | 7.41 us: 1.02x slower                                         |
| async_tree_cpu_io_mixed    | 704 ms                                                       | 717 ms: 1.02x slower                                          |
| docutils                   | 2.89 sec                                                     | 2.95 sec: 1.02x slower                                        |
| logging_simple             | 6.64 us                                                      | 6.77 us: 1.02x slower                                         |
| unpickle_list              | 4.65 us                                                      | 4.75 us: 1.02x slower                                         |
| async_tree_memoization     | 554 ms                                                       | 566 ms: 1.02x slower                                          |
| tornado_http               | 122 ms                                                       | 125 ms: 1.02x slower                                          |
| create_gc_cycles           | 1.58 ms                                                      | 1.62 ms: 1.02x slower                                         |
| async_tree_memoization_tg  | 554 ms                                                       | 569 ms: 1.03x slower                                          |
| pickle_dict                | 32.0 us                                                      | 33.0 us: 1.03x slower                                         |
| json_dumps                 | 10.3 ms                                                      | 10.6 ms: 1.03x slower                                         |
| async_tree_cpu_io_mixed_tg | 706 ms                                                       | 732 ms: 1.04x slower                                          |
| bench_thread_pool          | 956 us                                                       | 991 us: 1.04x slower                                          |
| json_loads                 | 24.3 us                                                      | 25.2 us: 1.04x slower                                         |
| async_tree_none_tg         | 440 ms                                                       | 458 ms: 1.04x slower                                          |
| dask                       | 394 ms                                                       | 410 ms: 1.04x slower                                          |
| sqlite_synth               | 2.72 us                                                      | 2.83 us: 1.04x slower                                         |
| sqlglot_normalize          | 119 ms                                                       | 124 ms: 1.04x slower                                          |
| async_tree_io              | 1.06 sec                                                     | 1.11 sec: 1.05x slower                                        |
| mypy2                      | 365 ms                                                       | 382 ms: 1.05x slower                                          |
| pycparser                  | 1.29 sec                                                     | 1.36 sec: 1.05x slower                                        |
| sympy_sum                  | 163 ms                                                       | 171 ms: 1.05x slower                                          |
| async_tree_io_tg           | 1.07 sec                                                     | 1.13 sec: 1.05x slower                                        |
| pathlib                    | 18.7 ms                                                      | 19.8 ms: 1.06x slower                                         |
| sqlglot_parse              | 1.41 ms                                                      | 1.49 ms: 1.06x slower                                         |
| sqlglot_transpile          | 1.80 ms                                                      | 1.92 ms: 1.06x slower                                         |
| sympy_integrate            | 24.0 ms                                                      | 25.6 ms: 1.06x slower                                         |
| pickle_list                | 4.22 us                                                      | 4.50 us: 1.07x slower                                         |
| mdp                        | 2.56 sec                                                     | 2.73 sec: 1.07x slower                                        |
| raytrace                   | 301 ms                                                       | 322 ms: 1.07x slower                                          |
| chameleon                  | 7.27 ms                                                      | 7.81 ms: 1.07x slower                                         |
| logging_silent             | 93.3 ns                                                      | 100 ns: 1.08x slower                                          |
| xml_etree_generate         | 85.3 ms                                                      | 92.2 ms: 1.08x slower                                         |
| scimark_lu                 | 98.6 ms                                                      | 107 ms: 1.08x slower                                          |
| sympy_str                  | 305 ms                                                       | 331 ms: 1.09x slower                                          |
| xml_etree_process          | 58.3 ms                                                      | 63.3 ms: 1.09x slower                                         |
| python_startup             | 11.7 ms                                                      | 12.8 ms: 1.10x slower                                         |
| sqlglot_optimize           | 58.4 ms                                                      | 64.5 ms: 1.10x slower                                         |
| sympy_expand               | 492 ms                                                       | 546 ms: 1.11x slower                                          |
| 2to3                       | 285 ms                                                       | 318 ms: 1.12x slower                                          |
| dulwich_log                | 64.9 ms                                                      | 72.5 ms: 1.12x slower                                         |
| crypto_pyaes               | 82.4 ms                                                      | 93.9 ms: 1.14x slower                                         |
| meteor_contest             | 126 ms                                                       | 145 ms: 1.14x slower                                          |
| deepcopy_memo              | 36.6 us                                                      | 42.3 us: 1.16x slower                                         |
| pprint_safe_repr           | 808 ms                                                       | 951 ms: 1.18x slower                                          |
| xml_etree_iterparse        | 104 ms                                                       | 123 ms: 1.18x slower                                          |
| richards_super             | 50.8 ms                                                      | 60.3 ms: 1.19x slower                                         |
| telco                      | 7.16 ms                                                      | 8.51 ms: 1.19x slower                                         |
| pprint_pformat             | 1.64 sec                                                     | 1.96 sec: 1.19x slower                                        |
| richards                   | 45.1 ms                                                      | 54.7 ms: 1.21x slower                                         |
| unpickle_pure_python       | 210 us                                                       | 255 us: 1.21x slower                                          |
| regex_compile              | 145 ms                                                       | 178 ms: 1.23x slower                                          |
| coverage                   | 66.3 ms                                                      | 82.7 ms: 1.25x slower                                         |
| go                         | 149 ms                                                       | 186 ms: 1.25x slower                                          |
| nqueens                    | 90.1 ms                                                      | 116 ms: 1.29x slower                                          |
| comprehensions             | 21.8 us                                                      | 28.2 us: 1.29x slower                                         |
| chaos                      | 64.1 ms                                                      | 83.4 ms: 1.30x slower                                         |
| python_startup_no_site     | 8.67 ms                                                      | 11.3 ms: 1.30x slower                                         |
| tomli_loads                | 2.17 sec                                                     | 2.96 sec: 1.36x slower                                        |
| pyflate                    | 442 ms                                                       | 611 ms: 1.38x slower                                          |
| float                      | 81.6 ms                                                      | 114 ms: 1.39x slower                                          |
| scimark_monte_carlo        | 69.5 ms                                                      | 97.8 ms: 1.41x slower                                         |
| scimark_sor                | 107 ms                                                       | 152 ms: 1.42x slower                                          |
| fannkuch                   | 362 ms                                                       | 521 ms: 1.44x slower                                          |
| scimark_sparse_mat_mult    | 4.49 ms                                                      | 7.06 ms: 1.57x slower                                         |
| scimark_fft                | 303 ms                                                       | 478 ms: 1.58x slower                                          |
| nbody                      | 88.2 ms                                                      | 149 ms: 1.69x slower                                          |
| mako                       | 10.1 ms                                                      | 17.9 ms: 1.77x slower                                         |
| hexiom                     | 5.97 ms                                                      | 10.9 ms: 1.83x slower                                         |
| deltablue                  | 3.24 ms                                                      | 6.03 ms: 1.86x slower                                         |
| spectral_norm              | 93.9 ms                                                      | 185 ms: 1.97x slower                                          |
| Geometric mean             | (ref)                                                        | 1.13x slower                                                  |

Benchmark hidden because not significant (6): deepcopy, async_generators, xml_etree_parse, pickle, gc_traversal, asyncio_websockets
Ignored benchmarks (5) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.05x
- 95% likely to have a slowdown of 1.05x
- 99% likely to have a slowdown of 1.05x
