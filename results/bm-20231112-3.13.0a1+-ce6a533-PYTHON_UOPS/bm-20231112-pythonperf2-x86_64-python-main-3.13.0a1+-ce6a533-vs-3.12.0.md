
# Results vs. 3.12.0

- fork: python
- ref: main
- machine: linux-x86_64
- commit hash: ce6a533
- commit date: 2023-11-12
- overall geometric mean: 1.13x slower \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.05x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231112-pythonperf2-x86_64-python-main-3.13.0a1+-ce6a533 |
|----------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| 2to3           | 285 ms                                                       | 323 ms: 1.14x slower                                         |
| chameleon      | 7.27 ms                                                      | 7.93 ms: 1.09x slower                                        |
| docutils       | 2.89 sec                                                     | 2.99 sec: 1.04x slower                                       |
| tornado_http   | 122 ms                                                       | 127 ms: 1.04x slower                                         |
| Geometric mean | (ref)                                                        | 1.07x slower                                                 |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231112-pythonperf2-x86_64-python-main-3.13.0a1+-ce6a533 |
|----------------------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| async_tree_none            | 459 ms                                                       | 468 ms: 1.02x slower                                         |
| async_tree_cpu_io_mixed    | 704 ms                                                       | 731 ms: 1.04x slower                                         |
| async_tree_memoization     | 554 ms                                                       | 581 ms: 1.05x slower                                         |
| async_tree_memoization_tg  | 554 ms                                                       | 583 ms: 1.05x slower                                         |
| async_tree_cpu_io_mixed_tg | 706 ms                                                       | 747 ms: 1.06x slower                                         |
| async_tree_io              | 1.06 sec                                                     | 1.13 sec: 1.07x slower                                       |
| async_tree_io_tg           | 1.07 sec                                                     | 1.15 sec: 1.07x slower                                       |
| async_tree_none_tg         | 440 ms                                                       | 474 ms: 1.08x slower                                         |
| Geometric mean             | (ref)                                                        | 1.05x slower                                                 |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231112-pythonperf2-x86_64-python-main-3.13.0a1+-ce6a533 |
|----------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| pidigits       | 264 ms                                                       | 266 ms: 1.01x slower                                         |
| float          | 81.6 ms                                                      | 116 ms: 1.42x slower                                         |
| nbody          | 88.2 ms                                                      | 129 ms: 1.46x slower                                         |
| Geometric mean | (ref)                                                        | 1.28x slower                                                 |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231112-pythonperf2-x86_64-python-main-3.13.0a1+-ce6a533 |
|----------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| regex_effbot   | 3.61 ms                                                      | 3.53 ms: 1.02x faster                                        |
| regex_dna      | 240 ms                                                       | 248 ms: 1.03x slower                                         |
| regex_v8       | 24.4 ms                                                      | 25.5 ms: 1.05x slower                                        |
| regex_compile  | 145 ms                                                       | 183 ms: 1.27x slower                                         |
| Geometric mean | (ref)                                                        | 1.08x slower                                                 |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231112-pythonperf2-x86_64-python-main-3.13.0a1+-ce6a533 |
|----------------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| unpickle             | 15.3 us                                                      | 14.8 us: 1.04x faster                                        |
| json_loads           | 24.3 us                                                      | 24.7 us: 1.02x slower                                        |
| unpickle_list        | 4.65 us                                                      | 4.74 us: 1.02x slower                                        |
| pickle_pure_python   | 319 us                                                       | 326 us: 1.02x slower                                         |
| pickle               | 10.0 us                                                      | 10.4 us: 1.03x slower                                        |
| pickle_dict          | 32.0 us                                                      | 33.1 us: 1.03x slower                                        |
| xml_etree_process    | 58.3 ms                                                      | 60.6 ms: 1.04x slower                                        |
| json_dumps           | 10.3 ms                                                      | 10.7 ms: 1.04x slower                                        |
| xml_etree_parse      | 147 ms                                                       | 154 ms: 1.05x slower                                         |
| pickle_list          | 4.22 us                                                      | 4.43 us: 1.05x slower                                        |
| xml_etree_generate   | 85.3 ms                                                      | 89.8 ms: 1.05x slower                                        |
| xml_etree_iterparse  | 104 ms                                                       | 118 ms: 1.14x slower                                         |
| unpickle_pure_python | 210 us                                                       | 252 us: 1.20x slower                                         |
| tomli_loads          | 2.17 sec                                                     | 3.40 sec: 1.57x slower                                       |
| Geometric mean       | (ref)                                                        | 1.08x slower                                                 |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231112-pythonperf2-x86_64-python-main-3.13.0a1+-ce6a533 |
|------------------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| python_startup         | 11.7 ms                                                      | 12.9 ms: 1.11x slower                                        |
| python_startup_no_site | 8.67 ms                                                      | 11.4 ms: 1.32x slower                                        |
| Geometric mean         | (ref)                                                        | 1.21x slower                                                 |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231112-pythonperf2-x86_64-python-main-3.13.0a1+-ce6a533 |
|-----------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| mako      | 10.1 ms                                                      | 16.2 ms: 1.61x slower                                        |

All benchmarks:
===============

| Benchmark                  | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231112-pythonperf2-x86_64-python-main-3.13.0a1+-ce6a533 |
|----------------------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| typing_runtime_protocols   | 150 us                                                       | 135 us: 1.12x faster                                         |
| generators                 | 37.3 ms                                                      | 35.3 ms: 1.06x faster                                        |
| coroutines                 | 23.1 ms                                                      | 22.1 ms: 1.05x faster                                        |
| unpickle                   | 15.3 us                                                      | 14.8 us: 1.04x faster                                        |
| spectral_norm              | 93.9 ms                                                      | 90.9 ms: 1.03x faster                                        |
| unpack_sequence            | 54.5 ns                                                      | 53.1 ns: 1.03x faster                                        |
| regex_effbot               | 3.61 ms                                                      | 3.53 ms: 1.02x faster                                        |
| deepcopy_reduce            | 3.41 us                                                      | 3.35 us: 1.02x faster                                        |
| sqlglot_normalize          | 119 ms                                                       | 117 ms: 1.02x faster                                         |
| asyncio_tcp                | 380 ms                                                       | 376 ms: 1.01x faster                                         |
| pidigits                   | 264 ms                                                       | 266 ms: 1.01x slower                                         |
| json_loads                 | 24.3 us                                                      | 24.7 us: 1.02x slower                                        |
| sqlite_synth               | 2.72 us                                                      | 2.76 us: 1.02x slower                                        |
| asyncio_tcp_ssl            | 1.57 sec                                                     | 1.60 sec: 1.02x slower                                       |
| async_tree_none            | 459 ms                                                       | 468 ms: 1.02x slower                                         |
| unpickle_list              | 4.65 us                                                      | 4.74 us: 1.02x slower                                        |
| pickle_pure_python         | 319 us                                                       | 326 us: 1.02x slower                                         |
| raytrace                   | 301 ms                                                       | 307 ms: 1.02x slower                                         |
| sqlglot_optimize           | 58.4 ms                                                      | 60.2 ms: 1.03x slower                                        |
| pickle                     | 10.0 us                                                      | 10.4 us: 1.03x slower                                        |
| regex_dna                  | 240 ms                                                       | 248 ms: 1.03x slower                                         |
| deepcopy                   | 371 us                                                       | 384 us: 1.03x slower                                         |
| pickle_dict                | 32.0 us                                                      | 33.1 us: 1.03x slower                                        |
| docutils                   | 2.89 sec                                                     | 2.99 sec: 1.04x slower                                       |
| tornado_http               | 122 ms                                                       | 127 ms: 1.04x slower                                         |
| async_tree_cpu_io_mixed    | 704 ms                                                       | 731 ms: 1.04x slower                                         |
| xml_etree_process          | 58.3 ms                                                      | 60.6 ms: 1.04x slower                                        |
| json_dumps                 | 10.3 ms                                                      | 10.7 ms: 1.04x slower                                        |
| regex_v8                   | 24.4 ms                                                      | 25.5 ms: 1.05x slower                                        |
| xml_etree_parse            | 147 ms                                                       | 154 ms: 1.05x slower                                         |
| sympy_str                  | 305 ms                                                       | 319 ms: 1.05x slower                                         |
| pycparser                  | 1.29 sec                                                     | 1.36 sec: 1.05x slower                                       |
| async_tree_memoization     | 554 ms                                                       | 581 ms: 1.05x slower                                         |
| pickle_list                | 4.22 us                                                      | 4.43 us: 1.05x slower                                        |
| xml_etree_generate         | 85.3 ms                                                      | 89.8 ms: 1.05x slower                                        |
| async_tree_memoization_tg  | 554 ms                                                       | 583 ms: 1.05x slower                                         |
| mypy2                      | 365 ms                                                       | 386 ms: 1.06x slower                                         |
| sqlglot_transpile          | 1.80 ms                                                      | 1.91 ms: 1.06x slower                                        |
| async_tree_cpu_io_mixed_tg | 706 ms                                                       | 747 ms: 1.06x slower                                         |
| logging_format             | 7.29 us                                                      | 7.72 us: 1.06x slower                                        |
| sqlglot_parse              | 1.41 ms                                                      | 1.49 ms: 1.06x slower                                        |
| logging_silent             | 93.3 ns                                                      | 98.8 ns: 1.06x slower                                        |
| bench_thread_pool          | 956 us                                                       | 1.02 ms: 1.06x slower                                        |
| logging_simple             | 6.64 us                                                      | 7.08 us: 1.07x slower                                        |
| async_tree_io              | 1.06 sec                                                     | 1.13 sec: 1.07x slower                                       |
| async_tree_io_tg           | 1.07 sec                                                     | 1.15 sec: 1.07x slower                                       |
| async_tree_none_tg         | 440 ms                                                       | 474 ms: 1.08x slower                                         |
| sympy_integrate            | 24.0 ms                                                      | 25.9 ms: 1.08x slower                                        |
| gc_traversal               | 3.70 ms                                                      | 4.01 ms: 1.08x slower                                        |
| chameleon                  | 7.27 ms                                                      | 7.93 ms: 1.09x slower                                        |
| sympy_expand               | 492 ms                                                       | 539 ms: 1.10x slower                                         |
| mdp                        | 2.56 sec                                                     | 2.80 sec: 1.10x slower                                       |
| scimark_lu                 | 98.6 ms                                                      | 109 ms: 1.10x slower                                         |
| python_startup             | 11.7 ms                                                      | 12.9 ms: 1.11x slower                                        |
| crypto_pyaes               | 82.4 ms                                                      | 91.2 ms: 1.11x slower                                        |
| pathlib                    | 18.7 ms                                                      | 20.7 ms: 1.11x slower                                        |
| dulwich_log                | 64.9 ms                                                      | 72.2 ms: 1.11x slower                                        |
| 2to3                       | 285 ms                                                       | 323 ms: 1.14x slower                                         |
| xml_etree_iterparse        | 104 ms                                                       | 118 ms: 1.14x slower                                         |
| meteor_contest             | 126 ms                                                       | 145 ms: 1.15x slower                                         |
| pprint_safe_repr           | 808 ms                                                       | 937 ms: 1.16x slower                                         |
| pprint_pformat             | 1.64 sec                                                     | 1.92 sec: 1.17x slower                                       |
| chaos                      | 64.1 ms                                                      | 75.7 ms: 1.18x slower                                        |
| deepcopy_memo              | 36.6 us                                                      | 43.4 us: 1.19x slower                                        |
| telco                      | 7.16 ms                                                      | 8.61 ms: 1.20x slower                                        |
| unpickle_pure_python       | 210 us                                                       | 252 us: 1.20x slower                                         |
| scimark_monte_carlo        | 69.5 ms                                                      | 85.1 ms: 1.22x slower                                        |
| coverage                   | 66.3 ms                                                      | 83.2 ms: 1.25x slower                                        |
| regex_compile              | 145 ms                                                       | 183 ms: 1.27x slower                                         |
| richards_super             | 50.8 ms                                                      | 65.6 ms: 1.29x slower                                        |
| richards                   | 45.1 ms                                                      | 59.2 ms: 1.31x slower                                        |
| python_startup_no_site     | 8.67 ms                                                      | 11.4 ms: 1.32x slower                                        |
| go                         | 149 ms                                                       | 201 ms: 1.35x slower                                         |
| scimark_fft                | 303 ms                                                       | 418 ms: 1.38x slower                                         |
| pyflate                    | 442 ms                                                       | 612 ms: 1.38x slower                                         |
| scimark_sor                | 107 ms                                                       | 150 ms: 1.40x slower                                         |
| float                      | 81.6 ms                                                      | 116 ms: 1.42x slower                                         |
| nqueens                    | 90.1 ms                                                      | 129 ms: 1.43x slower                                         |
| nbody                      | 88.2 ms                                                      | 129 ms: 1.46x slower                                         |
| comprehensions             | 21.8 us                                                      | 32.5 us: 1.49x slower                                        |
| tomli_loads                | 2.17 sec                                                     | 3.40 sec: 1.57x slower                                       |
| fannkuch                   | 362 ms                                                       | 577 ms: 1.59x slower                                         |
| mako                       | 10.1 ms                                                      | 16.2 ms: 1.61x slower                                        |
| scimark_sparse_mat_mult    | 4.49 ms                                                      | 7.36 ms: 1.64x slower                                        |
| deltablue                  | 3.24 ms                                                      | 5.99 ms: 1.85x slower                                        |
| hexiom                     | 5.97 ms                                                      | 12.6 ms: 2.11x slower                                        |
| Geometric mean             | (ref)                                                        | 1.13x slower                                                 |

Benchmark hidden because not significant (6): json, sympy_sum, async_generators, create_gc_cycles, bench_mp_pool, asyncio_websockets
Ignored benchmarks (6) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, dask, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.06x
- 95% likely to have a slowdown of 1.05x
- 99% likely to have a slowdown of 1.05x
