
# Results vs. 3.12.0

- fork: gvanrossum
- ref: faster_uops
- machine: linux-x86_64
- commit hash: a2c4f00
- commit date: 2023-11-19
- overall geometric mean: 1.06x slower \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.02x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231119-linux-x86_64-gvanrossum-faster_uops-3.13.0a1+-a2c4f00 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------:|
| 2to3           | 274 ms                                                 | 290 ms: 1.06x slower                                              |
| chameleon      | 7.41 ms                                                | 7.36 ms: 1.01x faster                                             |
| docutils       | 2.75 sec                                               | 2.73 sec: 1.01x faster                                            |
| tornado_http   | 101 ms                                                 | 103 ms: 1.02x slower                                              |
| Geometric mean | (ref)                                                  | 1.02x slower                                                      |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231119-linux-x86_64-gvanrossum-faster_uops-3.13.0a1+-a2c4f00 |
|----------------------------|:------------------------------------------------------:|:-----------------------------------------------------------------:|
| async_tree_none            | 475 ms                                                 | 460 ms: 1.03x faster                                              |
| async_tree_memoization     | 580 ms                                                 | 587 ms: 1.01x slower                                              |
| async_tree_cpu_io_mixed_tg | 725 ms                                                 | 761 ms: 1.05x slower                                              |
| async_tree_io              | 1.16 sec                                               | 1.22 sec: 1.05x slower                                            |
| async_tree_io_tg           | 1.19 sec                                               | 1.26 sec: 1.06x slower                                            |
| async_tree_none_tg         | 447 ms                                                 | 477 ms: 1.07x slower                                              |
| async_tree_memoization_tg  | 574 ms                                                 | 614 ms: 1.07x slower                                              |
| Geometric mean             | (ref)                                                  | 1.04x slower                                                      |

Benchmark hidden because not significant (1): async_tree_cpu_io_mixed

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231119-linux-x86_64-gvanrossum-faster_uops-3.13.0a1+-a2c4f00 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------:|
| pidigits       | 187 ms                                                 | 190 ms: 1.01x slower                                              |
| float          | 83.3 ms                                                | 103 ms: 1.23x slower                                              |
| nbody          | 92.2 ms                                                | 138 ms: 1.50x slower                                              |
| Geometric mean | (ref)                                                  | 1.23x slower                                                      |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231119-linux-x86_64-gvanrossum-faster_uops-3.13.0a1+-a2c4f00 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------:|
| regex_effbot   | 3.57 ms                                                | 3.52 ms: 1.01x faster                                             |
| regex_dna      | 209 ms                                                 | 222 ms: 1.07x slower                                              |
| regex_compile  | 148 ms                                                 | 161 ms: 1.09x slower                                              |
| regex_v8       | 22.7 ms                                                | 24.9 ms: 1.10x slower                                             |
| Geometric mean | (ref)                                                  | 1.06x slower                                                      |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231119-linux-x86_64-gvanrossum-faster_uops-3.13.0a1+-a2c4f00 |
|----------------------|:------------------------------------------------------:|:-----------------------------------------------------------------:|
| pickle_pure_python   | 326 us                                                 | 308 us: 1.06x faster                                              |
| unpickle             | 15.8 us                                                | 15.0 us: 1.05x faster                                             |
| json_loads           | 28.4 us                                                | 28.2 us: 1.01x faster                                             |
| xml_etree_parse      | 159 ms                                                 | 159 ms: 1.00x faster                                              |
| xml_etree_process    | 61.2 ms                                                | 62.9 ms: 1.03x slower                                             |
| xml_etree_generate   | 88.7 ms                                                | 91.3 ms: 1.03x slower                                             |
| pickle_dict          | 33.5 us                                                | 34.5 us: 1.03x slower                                             |
| pickle               | 11.2 us                                                | 11.6 us: 1.04x slower                                             |
| unpickle_pure_python | 230 us                                                 | 245 us: 1.07x slower                                              |
| xml_etree_iterparse  | 106 ms                                                 | 114 ms: 1.08x slower                                              |
| pickle_list          | 4.67 us                                                | 5.11 us: 1.09x slower                                             |
| tomli_loads          | 2.30 sec                                               | 2.77 sec: 1.20x slower                                            |
| Geometric mean       | (ref)                                                  | 1.03x slower                                                      |

Benchmark hidden because not significant (2): unpickle_list, json_dumps

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231119-linux-x86_64-gvanrossum-faster_uops-3.13.0a1+-a2c4f00 |
|------------------------|:------------------------------------------------------:|:-----------------------------------------------------------------:|
| python_startup         | 9.53 ms                                                | 10.5 ms: 1.10x slower                                             |
| python_startup_no_site | 6.92 ms                                                | 9.10 ms: 1.32x slower                                             |
| Geometric mean         | (ref)                                                  | 1.20x slower                                                      |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231119-linux-x86_64-gvanrossum-faster_uops-3.13.0a1+-a2c4f00 |
|-----------|:------------------------------------------------------:|:-----------------------------------------------------------------:|
| mako      | 11.5 ms                                                | 15.1 ms: 1.31x slower                                             |

All benchmarks:
===============

| Benchmark                  | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231119-linux-x86_64-gvanrossum-faster_uops-3.13.0a1+-a2c4f00 |
|----------------------------|:------------------------------------------------------:|:-----------------------------------------------------------------:|
| typing_runtime_protocols   | 153 us                                                 | 126 us: 1.22x faster                                              |
| gc_traversal               | 4.28 ms                                                | 3.65 ms: 1.17x faster                                             |
| generators                 | 32.5 ms                                                | 29.8 ms: 1.09x faster                                             |
| pickle_pure_python         | 326 us                                                 | 308 us: 1.06x faster                                              |
| coroutines                 | 23.5 ms                                                | 22.3 ms: 1.05x faster                                             |
| unpickle                   | 15.8 us                                                | 15.0 us: 1.05x faster                                             |
| async_tree_none            | 475 ms                                                 | 460 ms: 1.03x faster                                              |
| unpack_sequence            | 54.2 ns                                                | 52.6 ns: 1.03x faster                                             |
| deepcopy_reduce            | 3.23 us                                                | 3.14 us: 1.03x faster                                             |
| logging_simple             | 6.38 us                                                | 6.21 us: 1.03x faster                                             |
| sympy_sum                  | 167 ms                                                 | 163 ms: 1.02x faster                                              |
| scimark_sor                | 129 ms                                                 | 126 ms: 1.02x faster                                              |
| logging_format             | 7.10 us                                                | 6.98 us: 1.02x faster                                             |
| asyncio_tcp                | 506 ms                                                 | 499 ms: 1.01x faster                                              |
| regex_effbot               | 3.57 ms                                                | 3.52 ms: 1.01x faster                                             |
| pathlib                    | 18.9 ms                                                | 18.7 ms: 1.01x faster                                             |
| docutils                   | 2.75 sec                                               | 2.73 sec: 1.01x faster                                            |
| json_loads                 | 28.4 us                                                | 28.2 us: 1.01x faster                                             |
| chameleon                  | 7.41 ms                                                | 7.36 ms: 1.01x faster                                             |
| xml_etree_parse            | 159 ms                                                 | 159 ms: 1.00x faster                                              |
| create_gc_cycles           | 1.45 ms                                                | 1.46 ms: 1.01x slower                                             |
| sympy_str                  | 296 ms                                                 | 300 ms: 1.01x slower                                              |
| async_tree_memoization     | 580 ms                                                 | 587 ms: 1.01x slower                                              |
| pidigits                   | 187 ms                                                 | 190 ms: 1.01x slower                                              |
| asyncio_tcp_ssl            | 1.78 sec                                               | 1.81 sec: 1.02x slower                                            |
| dulwich_log                | 68.7 ms                                                | 69.9 ms: 1.02x slower                                             |
| bench_thread_pool          | 845 us                                                 | 861 us: 1.02x slower                                              |
| mypy2                      | 351 ms                                                 | 358 ms: 1.02x slower                                              |
| tornado_http               | 101 ms                                                 | 103 ms: 1.02x slower                                              |
| sympy_integrate            | 21.2 ms                                                | 21.7 ms: 1.02x slower                                             |
| xml_etree_process          | 61.2 ms                                                | 62.9 ms: 1.03x slower                                             |
| sqlglot_transpile          | 1.68 ms                                                | 1.72 ms: 1.03x slower                                             |
| xml_etree_generate         | 88.7 ms                                                | 91.3 ms: 1.03x slower                                             |
| raytrace                   | 308 ms                                                 | 317 ms: 1.03x slower                                              |
| sqlglot_parse              | 1.35 ms                                                | 1.39 ms: 1.03x slower                                             |
| pickle_dict                | 33.5 us                                                | 34.5 us: 1.03x slower                                             |
| logging_silent             | 108 ns                                                 | 111 ns: 1.03x slower                                              |
| sqlite_synth               | 2.83 us                                                | 2.92 us: 1.03x slower                                             |
| pickle                     | 11.2 us                                                | 11.6 us: 1.04x slower                                             |
| pycparser                  | 1.17 sec                                               | 1.22 sec: 1.04x slower                                            |
| sympy_expand               | 476 ms                                                 | 496 ms: 1.04x slower                                              |
| deepcopy_memo              | 39.7 us                                                | 41.6 us: 1.05x slower                                             |
| sqlglot_normalize          | 112 ms                                                 | 117 ms: 1.05x slower                                              |
| async_tree_cpu_io_mixed_tg | 725 ms                                                 | 761 ms: 1.05x slower                                              |
| crypto_pyaes               | 83.6 ms                                                | 87.8 ms: 1.05x slower                                             |
| async_tree_io              | 1.16 sec                                               | 1.22 sec: 1.05x slower                                            |
| 2to3                       | 274 ms                                                 | 290 ms: 1.06x slower                                              |
| async_tree_io_tg           | 1.19 sec                                               | 1.26 sec: 1.06x slower                                            |
| meteor_contest             | 110 ms                                                 | 117 ms: 1.06x slower                                              |
| async_tree_none_tg         | 447 ms                                                 | 477 ms: 1.07x slower                                              |
| regex_dna                  | 209 ms                                                 | 222 ms: 1.07x slower                                              |
| unpickle_pure_python       | 230 us                                                 | 245 us: 1.07x slower                                              |
| async_tree_memoization_tg  | 574 ms                                                 | 614 ms: 1.07x slower                                              |
| xml_etree_iterparse        | 106 ms                                                 | 114 ms: 1.08x slower                                              |
| sqlglot_optimize           | 54.8 ms                                                | 59.5 ms: 1.08x slower                                             |
| regex_compile              | 148 ms                                                 | 161 ms: 1.09x slower                                              |
| pickle_list                | 4.67 us                                                | 5.11 us: 1.09x slower                                             |
| mdp                        | 2.57 sec                                               | 2.82 sec: 1.10x slower                                            |
| python_startup             | 9.53 ms                                                | 10.5 ms: 1.10x slower                                             |
| regex_v8                   | 22.7 ms                                                | 24.9 ms: 1.10x slower                                             |
| richards                   | 46.0 ms                                                | 51.0 ms: 1.11x slower                                             |
| comprehensions             | 20.9 us                                                | 23.3 us: 1.11x slower                                             |
| pprint_safe_repr           | 765 ms                                                 | 853 ms: 1.11x slower                                              |
| richards_super             | 51.9 ms                                                | 58.3 ms: 1.12x slower                                             |
| fannkuch                   | 410 ms                                                 | 463 ms: 1.13x slower                                              |
| nqueens                    | 86.2 ms                                                | 98.3 ms: 1.14x slower                                             |
| pprint_pformat             | 1.55 sec                                               | 1.78 sec: 1.15x slower                                            |
| chaos                      | 67.5 ms                                                | 78.0 ms: 1.16x slower                                             |
| pyflate                    | 471 ms                                                 | 546 ms: 1.16x slower                                              |
| go                         | 140 ms                                                 | 164 ms: 1.17x slower                                              |
| scimark_monte_carlo        | 74.6 ms                                                | 88.6 ms: 1.19x slower                                             |
| scimark_sparse_mat_mult    | 5.33 ms                                                | 6.37 ms: 1.19x slower                                             |
| tomli_loads                | 2.30 sec                                               | 2.77 sec: 1.20x slower                                            |
| telco                      | 7.18 ms                                                | 8.70 ms: 1.21x slower                                             |
| float                      | 83.3 ms                                                | 103 ms: 1.23x slower                                              |
| coverage                   | 75.1 ms                                                | 95.2 ms: 1.27x slower                                             |
| scimark_fft                | 381 ms                                                 | 488 ms: 1.28x slower                                              |
| spectral_norm              | 115 ms                                                 | 149 ms: 1.30x slower                                              |
| mako                       | 11.5 ms                                                | 15.1 ms: 1.31x slower                                             |
| python_startup_no_site     | 6.92 ms                                                | 9.10 ms: 1.32x slower                                             |
| deltablue                  | 3.71 ms                                                | 5.11 ms: 1.38x slower                                             |
| hexiom                     | 6.54 ms                                                | 9.16 ms: 1.40x slower                                             |
| nbody                      | 92.2 ms                                                | 138 ms: 1.50x slower                                              |
| Geometric mean             | (ref)                                                  | 1.06x slower                                                      |

Benchmark hidden because not significant (10): unpickle_list, async_generators, json_dumps, json, deepcopy, bench_mp_pool, asyncio_websockets, dask, scimark_lu, async_tree_cpu_io_mixed
Ignored benchmarks (5) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.03x
- 95% likely to have a slowdown of 1.03x
- 99% likely to have a slowdown of 1.02x
