
# Results vs. 3.12.0

- fork: python
- ref: 3faf8e586d36e73faba1
- machine: linux-x86_64
- commit hash: 3faf8e5
- commit date: 2023-11-25
- overall geometric mean: 1.10x slower \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.04x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231125-pythonperf2-x86_64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| 2to3           | 285 ms                                                       | 317 ms: 1.11x slower                                                         |
| chameleon      | 7.27 ms                                                      | 8.21 ms: 1.13x slower                                                        |
| docutils       | 2.89 sec                                                     | 2.95 sec: 1.02x slower                                                       |
| tornado_http   | 122 ms                                                       | 126 ms: 1.03x slower                                                         |
| Geometric mean | (ref)                                                        | 1.07x slower                                                                 |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231125-pythonperf2-x86_64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|----------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| async_tree_none            | 459 ms                                                       | 449 ms: 1.02x faster                                                         |
| async_tree_cpu_io_mixed    | 704 ms                                                       | 713 ms: 1.01x slower                                                         |
| async_tree_memoization     | 554 ms                                                       | 561 ms: 1.01x slower                                                         |
| async_tree_cpu_io_mixed_tg | 706 ms                                                       | 730 ms: 1.03x slower                                                         |
| async_tree_none_tg         | 440 ms                                                       | 456 ms: 1.04x slower                                                         |
| async_tree_io_tg           | 1.07 sec                                                     | 1.11 sec: 1.04x slower                                                       |
| async_tree_io              | 1.06 sec                                                     | 1.10 sec: 1.04x slower                                                       |
| async_tree_memoization_tg  | 554 ms                                                       | 580 ms: 1.05x slower                                                         |
| Geometric mean             | (ref)                                                        | 1.02x slower                                                                 |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231125-pythonperf2-x86_64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| pidigits       | 264 ms                                                       | 267 ms: 1.01x slower                                                         |
| float          | 81.6 ms                                                      | 102 ms: 1.24x slower                                                         |
| nbody          | 88.2 ms                                                      | 129 ms: 1.47x slower                                                         |
| Geometric mean | (ref)                                                        | 1.23x slower                                                                 |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231125-pythonperf2-x86_64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| regex_effbot   | 3.61 ms                                                      | 3.50 ms: 1.03x faster                                                        |
| regex_dna      | 240 ms                                                       | 251 ms: 1.04x slower                                                         |
| regex_v8       | 24.4 ms                                                      | 25.9 ms: 1.06x slower                                                        |
| regex_compile  | 145 ms                                                       | 175 ms: 1.21x slower                                                         |
| Geometric mean | (ref)                                                        | 1.07x slower                                                                 |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231125-pythonperf2-x86_64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|----------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| unpickle             | 15.3 us                                                      | 14.7 us: 1.04x faster                                                        |
| unpickle_list        | 4.65 us                                                      | 4.58 us: 1.01x faster                                                        |
| pickle_pure_python   | 319 us                                                       | 316 us: 1.01x faster                                                         |
| pickle               | 10.0 us                                                      | 10.1 us: 1.01x slower                                                        |
| xml_etree_parse      | 147 ms                                                       | 151 ms: 1.03x slower                                                         |
| pickle_list          | 4.22 us                                                      | 4.36 us: 1.03x slower                                                        |
| pickle_dict          | 32.0 us                                                      | 33.1 us: 1.03x slower                                                        |
| json_loads           | 24.3 us                                                      | 25.3 us: 1.04x slower                                                        |
| xml_etree_process    | 58.3 ms                                                      | 60.9 ms: 1.04x slower                                                        |
| json_dumps           | 10.3 ms                                                      | 10.8 ms: 1.05x slower                                                        |
| xml_etree_generate   | 85.3 ms                                                      | 90.9 ms: 1.07x slower                                                        |
| xml_etree_iterparse  | 104 ms                                                       | 118 ms: 1.14x slower                                                         |
| unpickle_pure_python | 210 us                                                       | 249 us: 1.19x slower                                                         |
| tomli_loads          | 2.17 sec                                                     | 2.78 sec: 1.28x slower                                                       |
| Geometric mean       | (ref)                                                        | 1.06x slower                                                                 |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231125-pythonperf2-x86_64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| python_startup         | 11.7 ms                                                      | 12.9 ms: 1.10x slower                                                        |
| python_startup_no_site | 8.67 ms                                                      | 11.3 ms: 1.31x slower                                                        |
| Geometric mean         | (ref)                                                        | 1.20x slower                                                                 |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231125-pythonperf2-x86_64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|-----------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| mako      | 10.1 ms                                                      | 14.7 ms: 1.46x slower                                                        |

All benchmarks:
===============

| Benchmark                  | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231125-pythonperf2-x86_64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|----------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| unpack_sequence            | 54.5 ns                                                      | 42.8 ns: 1.27x faster                                                        |
| typing_runtime_protocols   | 150 us                                                       | 131 us: 1.15x faster                                                         |
| generators                 | 37.3 ms                                                      | 34.7 ms: 1.07x faster                                                        |
| bench_mp_pool              | 4.96 ms                                                      | 4.74 ms: 1.05x faster                                                        |
| deepcopy_reduce            | 3.41 us                                                      | 3.27 us: 1.04x faster                                                        |
| unpickle                   | 15.3 us                                                      | 14.7 us: 1.04x faster                                                        |
| coroutines                 | 23.1 ms                                                      | 22.2 ms: 1.04x faster                                                        |
| regex_effbot               | 3.61 ms                                                      | 3.50 ms: 1.03x faster                                                        |
| async_tree_none            | 459 ms                                                       | 449 ms: 1.02x faster                                                         |
| asyncio_tcp                | 380 ms                                                       | 371 ms: 1.02x faster                                                         |
| unpickle_list              | 4.65 us                                                      | 4.58 us: 1.01x faster                                                        |
| pickle_pure_python         | 319 us                                                       | 316 us: 1.01x faster                                                         |
| deepcopy                   | 371 us                                                       | 367 us: 1.01x faster                                                         |
| pickle                     | 10.0 us                                                      | 10.1 us: 1.01x slower                                                        |
| async_generators           | 385 ms                                                       | 388 ms: 1.01x slower                                                         |
| asyncio_tcp_ssl            | 1.57 sec                                                     | 1.59 sec: 1.01x slower                                                       |
| pidigits                   | 264 ms                                                       | 267 ms: 1.01x slower                                                         |
| asyncio_websockets         | 386 ms                                                       | 390 ms: 1.01x slower                                                         |
| async_tree_cpu_io_mixed    | 704 ms                                                       | 713 ms: 1.01x slower                                                         |
| async_tree_memoization     | 554 ms                                                       | 561 ms: 1.01x slower                                                         |
| json                       | 5.17 ms                                                      | 5.27 ms: 1.02x slower                                                        |
| docutils                   | 2.89 sec                                                     | 2.95 sec: 1.02x slower                                                       |
| bench_thread_pool          | 956 us                                                       | 976 us: 1.02x slower                                                         |
| pycparser                  | 1.29 sec                                                     | 1.33 sec: 1.02x slower                                                       |
| pathlib                    | 18.7 ms                                                      | 19.3 ms: 1.03x slower                                                        |
| logging_simple             | 6.64 us                                                      | 6.84 us: 1.03x slower                                                        |
| create_gc_cycles           | 1.58 ms                                                      | 1.62 ms: 1.03x slower                                                        |
| xml_etree_parse            | 147 ms                                                       | 151 ms: 1.03x slower                                                         |
| pickle_list                | 4.22 us                                                      | 4.36 us: 1.03x slower                                                        |
| async_tree_cpu_io_mixed_tg | 706 ms                                                       | 730 ms: 1.03x slower                                                         |
| pickle_dict                | 32.0 us                                                      | 33.1 us: 1.03x slower                                                        |
| tornado_http               | 122 ms                                                       | 126 ms: 1.03x slower                                                         |
| sqlite_synth               | 2.72 us                                                      | 2.81 us: 1.03x slower                                                        |
| async_tree_none_tg         | 440 ms                                                       | 456 ms: 1.04x slower                                                         |
| sympy_sum                  | 163 ms                                                       | 169 ms: 1.04x slower                                                         |
| raytrace                   | 301 ms                                                       | 312 ms: 1.04x slower                                                         |
| logging_format             | 7.29 us                                                      | 7.56 us: 1.04x slower                                                        |
| async_tree_io_tg           | 1.07 sec                                                     | 1.11 sec: 1.04x slower                                                       |
| async_tree_io              | 1.06 sec                                                     | 1.10 sec: 1.04x slower                                                       |
| json_loads                 | 24.3 us                                                      | 25.3 us: 1.04x slower                                                        |
| crypto_pyaes               | 82.4 ms                                                      | 86.0 ms: 1.04x slower                                                        |
| xml_etree_process          | 58.3 ms                                                      | 60.9 ms: 1.04x slower                                                        |
| dask                       | 394 ms                                                       | 411 ms: 1.04x slower                                                         |
| regex_dna                  | 240 ms                                                       | 251 ms: 1.04x slower                                                         |
| sqlglot_normalize          | 119 ms                                                       | 125 ms: 1.05x slower                                                         |
| mypy2                      | 365 ms                                                       | 382 ms: 1.05x slower                                                         |
| sympy_integrate            | 24.0 ms                                                      | 25.1 ms: 1.05x slower                                                        |
| async_tree_memoization_tg  | 554 ms                                                       | 580 ms: 1.05x slower                                                         |
| mdp                        | 2.56 sec                                                     | 2.68 sec: 1.05x slower                                                       |
| sqlglot_parse              | 1.41 ms                                                      | 1.48 ms: 1.05x slower                                                        |
| json_dumps                 | 10.3 ms                                                      | 10.8 ms: 1.05x slower                                                        |
| sqlglot_transpile          | 1.80 ms                                                      | 1.90 ms: 1.05x slower                                                        |
| logging_silent             | 93.3 ns                                                      | 98.7 ns: 1.06x slower                                                        |
| regex_v8                   | 24.4 ms                                                      | 25.9 ms: 1.06x slower                                                        |
| xml_etree_generate         | 85.3 ms                                                      | 90.9 ms: 1.07x slower                                                        |
| sympy_str                  | 305 ms                                                       | 327 ms: 1.07x slower                                                         |
| deepcopy_memo              | 36.6 us                                                      | 39.2 us: 1.07x slower                                                        |
| scimark_lu                 | 98.6 ms                                                      | 106 ms: 1.08x slower                                                         |
| sqlglot_optimize           | 58.4 ms                                                      | 63.6 ms: 1.09x slower                                                        |
| dulwich_log                | 64.9 ms                                                      | 71.5 ms: 1.10x slower                                                        |
| python_startup             | 11.7 ms                                                      | 12.9 ms: 1.10x slower                                                        |
| meteor_contest             | 126 ms                                                       | 140 ms: 1.11x slower                                                         |
| sympy_expand               | 492 ms                                                       | 545 ms: 1.11x slower                                                         |
| 2to3                       | 285 ms                                                       | 317 ms: 1.11x slower                                                         |
| gc_traversal               | 3.70 ms                                                      | 4.18 ms: 1.13x slower                                                        |
| chameleon                  | 7.27 ms                                                      | 8.21 ms: 1.13x slower                                                        |
| pprint_safe_repr           | 808 ms                                                       | 916 ms: 1.13x slower                                                         |
| xml_etree_iterparse        | 104 ms                                                       | 118 ms: 1.14x slower                                                         |
| pprint_pformat             | 1.64 sec                                                     | 1.88 sec: 1.15x slower                                                       |
| comprehensions             | 21.8 us                                                      | 25.4 us: 1.16x slower                                                        |
| richards_super             | 50.8 ms                                                      | 60.1 ms: 1.18x slower                                                        |
| telco                      | 7.16 ms                                                      | 8.48 ms: 1.18x slower                                                        |
| unpickle_pure_python       | 210 us                                                       | 249 us: 1.19x slower                                                         |
| richards                   | 45.1 ms                                                      | 54.1 ms: 1.20x slower                                                        |
| nqueens                    | 90.1 ms                                                      | 109 ms: 1.21x slower                                                         |
| coverage                   | 66.3 ms                                                      | 80.1 ms: 1.21x slower                                                        |
| regex_compile              | 145 ms                                                       | 175 ms: 1.21x slower                                                         |
| chaos                      | 64.1 ms                                                      | 77.8 ms: 1.22x slower                                                        |
| go                         | 149 ms                                                       | 182 ms: 1.22x slower                                                         |
| float                      | 81.6 ms                                                      | 102 ms: 1.24x slower                                                         |
| tomli_loads                | 2.17 sec                                                     | 2.78 sec: 1.28x slower                                                       |
| python_startup_no_site     | 8.67 ms                                                      | 11.3 ms: 1.31x slower                                                        |
| pyflate                    | 442 ms                                                       | 578 ms: 1.31x slower                                                         |
| fannkuch                   | 362 ms                                                       | 475 ms: 1.31x slower                                                         |
| scimark_monte_carlo        | 69.5 ms                                                      | 92.1 ms: 1.32x slower                                                        |
| scimark_sor                | 107 ms                                                       | 149 ms: 1.40x slower                                                         |
| mako                       | 10.1 ms                                                      | 14.7 ms: 1.46x slower                                                        |
| nbody                      | 88.2 ms                                                      | 129 ms: 1.47x slower                                                         |
| scimark_fft                | 303 ms                                                       | 451 ms: 1.49x slower                                                         |
| scimark_sparse_mat_mult    | 4.49 ms                                                      | 6.75 ms: 1.50x slower                                                        |
| hexiom                     | 5.97 ms                                                      | 9.89 ms: 1.66x slower                                                        |
| deltablue                  | 3.24 ms                                                      | 5.52 ms: 1.70x slower                                                        |
| spectral_norm              | 93.9 ms                                                      | 165 ms: 1.76x slower                                                         |
| Geometric mean             | (ref)                                                        | 1.10x slower                                                                 |
Ignored benchmarks (5) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.05x
- 95% likely to have a slowdown of 1.04x
- 99% likely to have a slowdown of 1.04x
