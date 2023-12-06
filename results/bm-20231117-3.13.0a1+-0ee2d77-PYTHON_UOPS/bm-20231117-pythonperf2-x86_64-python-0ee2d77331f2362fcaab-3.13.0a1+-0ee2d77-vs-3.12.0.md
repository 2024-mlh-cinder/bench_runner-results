
# Results vs. 3.12.0

- fork: python
- ref: 0ee2d77331f2362fcaab
- machine: linux-x86_64
- commit hash: 0ee2d77
- commit date: 2023-11-17
- overall geometric mean: 1.09x slower \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.03x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231117-pythonperf2-x86_64-python-0ee2d77331f2362fcaab-3.13.0a1+-0ee2d77 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| 2to3           | 285 ms                                                       | 313 ms: 1.10x slower                                                         |
| chameleon      | 7.27 ms                                                      | 8.23 ms: 1.13x slower                                                        |
| docutils       | 2.89 sec                                                     | 2.95 sec: 1.02x slower                                                       |
| tornado_http   | 122 ms                                                       | 125 ms: 1.02x slower                                                         |
| Geometric mean | (ref)                                                        | 1.07x slower                                                                 |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231117-pythonperf2-x86_64-python-0ee2d77331f2362fcaab-3.13.0a1+-0ee2d77 |
|----------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| async_tree_cpu_io_mixed    | 704 ms                                                       | 724 ms: 1.03x slower                                                         |
| async_tree_memoization     | 554 ms                                                       | 572 ms: 1.03x slower                                                         |
| async_tree_memoization_tg  | 554 ms                                                       | 572 ms: 1.03x slower                                                         |
| async_tree_io              | 1.06 sec                                                     | 1.11 sec: 1.05x slower                                                       |
| async_tree_cpu_io_mixed_tg | 706 ms                                                       | 740 ms: 1.05x slower                                                         |
| async_tree_io_tg           | 1.07 sec                                                     | 1.12 sec: 1.05x slower                                                       |
| async_tree_none_tg         | 440 ms                                                       | 464 ms: 1.05x slower                                                         |
| Geometric mean             | (ref)                                                        | 1.04x slower                                                                 |

Benchmark hidden because not significant (1): async_tree_none

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231117-pythonperf2-x86_64-python-0ee2d77331f2362fcaab-3.13.0a1+-0ee2d77 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| pidigits       | 264 ms                                                       | 266 ms: 1.01x slower                                                         |
| float          | 81.6 ms                                                      | 101 ms: 1.24x slower                                                         |
| nbody          | 88.2 ms                                                      | 109 ms: 1.24x slower                                                         |
| Geometric mean | (ref)                                                        | 1.15x slower                                                                 |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231117-pythonperf2-x86_64-python-0ee2d77331f2362fcaab-3.13.0a1+-0ee2d77 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| regex_effbot   | 3.61 ms                                                      | 3.54 ms: 1.02x faster                                                        |
| regex_dna      | 240 ms                                                       | 244 ms: 1.02x slower                                                         |
| regex_v8       | 24.4 ms                                                      | 25.9 ms: 1.06x slower                                                        |
| regex_compile  | 145 ms                                                       | 173 ms: 1.20x slower                                                         |
| Geometric mean | (ref)                                                        | 1.06x slower                                                                 |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231117-pythonperf2-x86_64-python-0ee2d77331f2362fcaab-3.13.0a1+-0ee2d77 |
|----------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| unpickle             | 15.3 us                                                      | 14.5 us: 1.06x faster                                                        |
| pickle_pure_python   | 319 us                                                       | 314 us: 1.02x faster                                                         |
| pickle               | 10.0 us                                                      | 10.1 us: 1.01x slower                                                        |
| pickle_dict          | 32.0 us                                                      | 32.3 us: 1.01x slower                                                        |
| xml_etree_generate   | 85.3 ms                                                      | 86.9 ms: 1.02x slower                                                        |
| xml_etree_parse      | 147 ms                                                       | 152 ms: 1.03x slower                                                         |
| pickle_list          | 4.22 us                                                      | 4.36 us: 1.03x slower                                                        |
| json_loads           | 24.3 us                                                      | 25.2 us: 1.04x slower                                                        |
| json_dumps           | 10.3 ms                                                      | 10.8 ms: 1.05x slower                                                        |
| xml_etree_iterparse  | 104 ms                                                       | 114 ms: 1.11x slower                                                         |
| unpickle_pure_python | 210 us                                                       | 253 us: 1.21x slower                                                         |
| tomli_loads          | 2.17 sec                                                     | 2.87 sec: 1.32x slower                                                       |
| Geometric mean       | (ref)                                                        | 1.05x slower                                                                 |

Benchmark hidden because not significant (2): unpickle_list, xml_etree_process

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231117-pythonperf2-x86_64-python-0ee2d77331f2362fcaab-3.13.0a1+-0ee2d77 |
|------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| python_startup         | 11.7 ms                                                      | 12.9 ms: 1.10x slower                                                        |
| python_startup_no_site | 8.67 ms                                                      | 11.4 ms: 1.31x slower                                                        |
| Geometric mean         | (ref)                                                        | 1.20x slower                                                                 |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231117-pythonperf2-x86_64-python-0ee2d77331f2362fcaab-3.13.0a1+-0ee2d77 |
|-----------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| mako      | 10.1 ms                                                      | 14.7 ms: 1.46x slower                                                        |

All benchmarks:
===============

| Benchmark                  | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231117-pythonperf2-x86_64-python-0ee2d77331f2362fcaab-3.13.0a1+-0ee2d77 |
|----------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| unpack_sequence            | 54.5 ns                                                      | 47.2 ns: 1.15x faster                                                        |
| typing_runtime_protocols   | 150 us                                                       | 135 us: 1.12x faster                                                         |
| generators                 | 37.3 ms                                                      | 35.1 ms: 1.06x faster                                                        |
| unpickle                   | 15.3 us                                                      | 14.5 us: 1.06x faster                                                        |
| coroutines                 | 23.1 ms                                                      | 22.2 ms: 1.04x faster                                                        |
| spectral_norm              | 93.9 ms                                                      | 91.4 ms: 1.03x faster                                                        |
| sympy_sum                  | 163 ms                                                       | 159 ms: 1.03x faster                                                         |
| sqlglot_normalize          | 119 ms                                                       | 117 ms: 1.02x faster                                                         |
| regex_effbot               | 3.61 ms                                                      | 3.54 ms: 1.02x faster                                                        |
| deepcopy_reduce            | 3.41 us                                                      | 3.35 us: 1.02x faster                                                        |
| pickle_pure_python         | 319 us                                                       | 314 us: 1.02x faster                                                         |
| asyncio_tcp                | 380 ms                                                       | 375 ms: 1.01x faster                                                         |
| raytrace                   | 301 ms                                                       | 298 ms: 1.01x faster                                                         |
| pidigits                   | 264 ms                                                       | 266 ms: 1.01x slower                                                         |
| pickle                     | 10.0 us                                                      | 10.1 us: 1.01x slower                                                        |
| pickle_dict                | 32.0 us                                                      | 32.3 us: 1.01x slower                                                        |
| sqlglot_optimize           | 58.4 ms                                                      | 59.2 ms: 1.01x slower                                                        |
| asyncio_tcp_ssl            | 1.57 sec                                                     | 1.60 sec: 1.01x slower                                                       |
| logging_simple             | 6.64 us                                                      | 6.74 us: 1.01x slower                                                        |
| regex_dna                  | 240 ms                                                       | 244 ms: 1.02x slower                                                         |
| pycparser                  | 1.29 sec                                                     | 1.32 sec: 1.02x slower                                                       |
| sqlite_synth               | 2.72 us                                                      | 2.77 us: 1.02x slower                                                        |
| xml_etree_generate         | 85.3 ms                                                      | 86.9 ms: 1.02x slower                                                        |
| deepcopy                   | 371 us                                                       | 378 us: 1.02x slower                                                         |
| sympy_str                  | 305 ms                                                       | 311 ms: 1.02x slower                                                         |
| docutils                   | 2.89 sec                                                     | 2.95 sec: 1.02x slower                                                       |
| json                       | 5.17 ms                                                      | 5.29 ms: 1.02x slower                                                        |
| pathlib                    | 18.7 ms                                                      | 19.2 ms: 1.02x slower                                                        |
| bench_thread_pool          | 956 us                                                       | 979 us: 1.02x slower                                                         |
| tornado_http               | 122 ms                                                       | 125 ms: 1.02x slower                                                         |
| logging_format             | 7.29 us                                                      | 7.47 us: 1.02x slower                                                        |
| create_gc_cycles           | 1.58 ms                                                      | 1.62 ms: 1.02x slower                                                        |
| async_tree_cpu_io_mixed    | 704 ms                                                       | 724 ms: 1.03x slower                                                         |
| crypto_pyaes               | 82.4 ms                                                      | 85.0 ms: 1.03x slower                                                        |
| async_tree_memoization     | 554 ms                                                       | 572 ms: 1.03x slower                                                         |
| xml_etree_parse            | 147 ms                                                       | 152 ms: 1.03x slower                                                         |
| pickle_list                | 4.22 us                                                      | 4.36 us: 1.03x slower                                                        |
| async_tree_memoization_tg  | 554 ms                                                       | 572 ms: 1.03x slower                                                         |
| dask                       | 394 ms                                                       | 407 ms: 1.03x slower                                                         |
| json_loads                 | 24.3 us                                                      | 25.2 us: 1.04x slower                                                        |
| sympy_integrate            | 24.0 ms                                                      | 25.1 ms: 1.04x slower                                                        |
| mypy2                      | 365 ms                                                       | 382 ms: 1.05x slower                                                         |
| async_tree_io              | 1.06 sec                                                     | 1.11 sec: 1.05x slower                                                       |
| async_tree_cpu_io_mixed_tg | 706 ms                                                       | 740 ms: 1.05x slower                                                         |
| sqlglot_transpile          | 1.80 ms                                                      | 1.89 ms: 1.05x slower                                                        |
| async_tree_io_tg           | 1.07 sec                                                     | 1.12 sec: 1.05x slower                                                       |
| json_dumps                 | 10.3 ms                                                      | 10.8 ms: 1.05x slower                                                        |
| sqlglot_parse              | 1.41 ms                                                      | 1.48 ms: 1.05x slower                                                        |
| async_tree_none_tg         | 440 ms                                                       | 464 ms: 1.05x slower                                                         |
| regex_v8                   | 24.4 ms                                                      | 25.9 ms: 1.06x slower                                                        |
| sympy_expand               | 492 ms                                                       | 528 ms: 1.07x slower                                                         |
| mdp                        | 2.56 sec                                                     | 2.75 sec: 1.07x slower                                                       |
| scimark_lu                 | 98.6 ms                                                      | 107 ms: 1.08x slower                                                         |
| logging_silent             | 93.3 ns                                                      | 101 ns: 1.08x slower                                                         |
| meteor_contest             | 126 ms                                                       | 137 ms: 1.09x slower                                                         |
| dulwich_log                | 64.9 ms                                                      | 71.3 ms: 1.10x slower                                                        |
| 2to3                       | 285 ms                                                       | 313 ms: 1.10x slower                                                         |
| chaos                      | 64.1 ms                                                      | 70.5 ms: 1.10x slower                                                        |
| python_startup             | 11.7 ms                                                      | 12.9 ms: 1.10x slower                                                        |
| xml_etree_iterparse        | 104 ms                                                       | 114 ms: 1.11x slower                                                         |
| pprint_safe_repr           | 808 ms                                                       | 913 ms: 1.13x slower                                                         |
| chameleon                  | 7.27 ms                                                      | 8.23 ms: 1.13x slower                                                        |
| pprint_pformat             | 1.64 sec                                                     | 1.87 sec: 1.14x slower                                                       |
| deepcopy_memo              | 36.6 us                                                      | 42.2 us: 1.15x slower                                                        |
| telco                      | 7.16 ms                                                      | 8.50 ms: 1.19x slower                                                        |
| richards_super             | 50.8 ms                                                      | 60.5 ms: 1.19x slower                                                        |
| regex_compile              | 145 ms                                                       | 173 ms: 1.20x slower                                                         |
| scimark_monte_carlo        | 69.5 ms                                                      | 83.3 ms: 1.20x slower                                                        |
| richards                   | 45.1 ms                                                      | 54.3 ms: 1.20x slower                                                        |
| unpickle_pure_python       | 210 us                                                       | 253 us: 1.21x slower                                                         |
| float                      | 81.6 ms                                                      | 101 ms: 1.24x slower                                                         |
| nbody                      | 88.2 ms                                                      | 109 ms: 1.24x slower                                                         |
| coverage                   | 66.3 ms                                                      | 82.4 ms: 1.24x slower                                                        |
| go                         | 149 ms                                                       | 188 ms: 1.26x slower                                                         |
| comprehensions             | 21.8 us                                                      | 27.8 us: 1.28x slower                                                        |
| nqueens                    | 90.1 ms                                                      | 117 ms: 1.30x slower                                                         |
| scimark_fft                | 303 ms                                                       | 396 ms: 1.31x slower                                                         |
| python_startup_no_site     | 8.67 ms                                                      | 11.4 ms: 1.31x slower                                                        |
| tomli_loads                | 2.17 sec                                                     | 2.87 sec: 1.32x slower                                                       |
| pyflate                    | 442 ms                                                       | 589 ms: 1.33x slower                                                         |
| fannkuch                   | 362 ms                                                       | 506 ms: 1.40x slower                                                         |
| scimark_sor                | 107 ms                                                       | 153 ms: 1.43x slower                                                         |
| mako                       | 10.1 ms                                                      | 14.7 ms: 1.46x slower                                                        |
| scimark_sparse_mat_mult    | 4.49 ms                                                      | 6.58 ms: 1.47x slower                                                        |
| deltablue                  | 3.24 ms                                                      | 5.25 ms: 1.62x slower                                                        |
| hexiom                     | 5.97 ms                                                      | 10.7 ms: 1.79x slower                                                        |
| Geometric mean             | (ref)                                                        | 1.09x slower                                                                 |

Benchmark hidden because not significant (7): async_tree_none, gc_traversal, unpickle_list, async_generators, xml_etree_process, asyncio_websockets, bench_mp_pool
Ignored benchmarks (5) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.04x
- 95% likely to have a slowdown of 1.04x
- 99% likely to have a slowdown of 1.03x
