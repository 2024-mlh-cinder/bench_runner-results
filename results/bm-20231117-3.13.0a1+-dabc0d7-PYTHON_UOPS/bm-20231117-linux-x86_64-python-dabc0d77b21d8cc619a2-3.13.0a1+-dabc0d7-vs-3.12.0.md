
# Results vs. 3.12.0

- fork: python
- ref: dabc0d77b21d8cc619a2
- machine: linux-x86_64
- commit hash: dabc0d7
- commit date: 2023-11-17
- overall geometric mean: 1.08x slower \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.02x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231117-linux-x86_64-python-dabc0d77b21d8cc619a2-3.13.0a1+-dabc0d7 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| 2to3           | 274 ms                                                 | 297 ms: 1.08x slower                                                   |
| chameleon      | 7.41 ms                                                | 7.46 ms: 1.01x slower                                                  |
| docutils       | 2.75 sec                                               | 2.72 sec: 1.01x faster                                                 |
| tornado_http   | 101 ms                                                 | 103 ms: 1.02x slower                                                   |
| Geometric mean | (ref)                                                  | 1.02x slower                                                           |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231117-linux-x86_64-python-dabc0d77b21d8cc619a2-3.13.0a1+-dabc0d7 |
|----------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| async_tree_none            | 475 ms                                                 | 464 ms: 1.02x faster                                                   |
| async_tree_cpu_io_mixed    | 724 ms                                                 | 743 ms: 1.03x slower                                                   |
| async_tree_memoization     | 580 ms                                                 | 595 ms: 1.03x slower                                                   |
| async_tree_memoization_tg  | 574 ms                                                 | 610 ms: 1.06x slower                                                   |
| async_tree_io              | 1.16 sec                                               | 1.24 sec: 1.06x slower                                                 |
| async_tree_io_tg           | 1.19 sec                                               | 1.27 sec: 1.07x slower                                                 |
| async_tree_cpu_io_mixed_tg | 725 ms                                                 | 773 ms: 1.07x slower                                                   |
| async_tree_none_tg         | 447 ms                                                 | 481 ms: 1.07x slower                                                   |
| Geometric mean             | (ref)                                                  | 1.04x slower                                                           |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231117-linux-x86_64-python-dabc0d77b21d8cc619a2-3.13.0a1+-dabc0d7 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| pidigits       | 187 ms                                                 | 198 ms: 1.06x slower                                                   |
| float          | 83.3 ms                                                | 119 ms: 1.43x slower                                                   |
| nbody          | 92.2 ms                                                | 142 ms: 1.54x slower                                                   |
| Geometric mean | (ref)                                                  | 1.32x slower                                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231117-linux-x86_64-python-dabc0d77b21d8cc619a2-3.13.0a1+-dabc0d7 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| regex_effbot   | 3.57 ms                                                | 3.56 ms: 1.00x faster                                                  |
| regex_dna      | 209 ms                                                 | 216 ms: 1.04x slower                                                   |
| regex_v8       | 22.7 ms                                                | 24.8 ms: 1.09x slower                                                  |
| regex_compile  | 148 ms                                                 | 171 ms: 1.16x slower                                                   |
| Geometric mean | (ref)                                                  | 1.07x slower                                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231117-linux-x86_64-python-dabc0d77b21d8cc619a2-3.13.0a1+-dabc0d7 |
|----------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| pickle_pure_python   | 326 us                                                 | 308 us: 1.06x faster                                                   |
| unpickle             | 15.8 us                                                | 14.9 us: 1.06x faster                                                  |
| xml_etree_process    | 61.2 ms                                                | 59.3 ms: 1.03x faster                                                  |
| json_loads           | 28.4 us                                                | 28.0 us: 1.01x faster                                                  |
| pickle               | 11.2 us                                                | 11.1 us: 1.01x faster                                                  |
| xml_etree_parse      | 159 ms                                                 | 158 ms: 1.01x faster                                                   |
| xml_etree_generate   | 88.7 ms                                                | 87.8 ms: 1.01x faster                                                  |
| json_dumps           | 10.6 ms                                                | 10.5 ms: 1.01x faster                                                  |
| unpickle_list        | 5.04 us                                                | 5.29 us: 1.05x slower                                                  |
| pickle_list          | 4.67 us                                                | 5.05 us: 1.08x slower                                                  |
| xml_etree_iterparse  | 106 ms                                                 | 114 ms: 1.08x slower                                                   |
| unpickle_pure_python | 230 us                                                 | 252 us: 1.10x slower                                                   |
| tomli_loads          | 2.30 sec                                               | 3.11 sec: 1.35x slower                                                 |
| Geometric mean       | (ref)                                                  | 1.03x slower                                                           |

Benchmark hidden because not significant (1): pickle_dict

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231117-linux-x86_64-python-dabc0d77b21d8cc619a2-3.13.0a1+-dabc0d7 |
|------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| python_startup         | 9.53 ms                                                | 10.4 ms: 1.09x slower                                                  |
| python_startup_no_site | 6.92 ms                                                | 9.05 ms: 1.31x slower                                                  |
| Geometric mean         | (ref)                                                  | 1.19x slower                                                           |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231117-linux-x86_64-python-dabc0d77b21d8cc619a2-3.13.0a1+-dabc0d7 |
|-----------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| mako      | 11.5 ms                                                | 17.7 ms: 1.54x slower                                                  |

All benchmarks:
===============

| Benchmark                  | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231117-linux-x86_64-python-dabc0d77b21d8cc619a2-3.13.0a1+-dabc0d7 |
|----------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| typing_runtime_protocols   | 153 us                                                 | 127 us: 1.21x faster                                                   |
| unpack_sequence            | 54.2 ns                                                | 46.7 ns: 1.16x faster                                                  |
| generators                 | 32.5 ms                                                | 29.5 ms: 1.10x faster                                                  |
| gc_traversal               | 4.28 ms                                                | 3.92 ms: 1.09x faster                                                  |
| sympy_sum                  | 167 ms                                                 | 155 ms: 1.08x faster                                                   |
| coroutines                 | 23.5 ms                                                | 22.0 ms: 1.06x faster                                                  |
| pickle_pure_python         | 326 us                                                 | 308 us: 1.06x faster                                                   |
| unpickle                   | 15.8 us                                                | 14.9 us: 1.06x faster                                                  |
| asyncio_tcp                | 506 ms                                                 | 483 ms: 1.05x faster                                                   |
| xml_etree_process          | 61.2 ms                                                | 59.3 ms: 1.03x faster                                                  |
| deepcopy_reduce            | 3.23 us                                                | 3.13 us: 1.03x faster                                                  |
| async_tree_none            | 475 ms                                                 | 464 ms: 1.02x faster                                                   |
| logging_simple             | 6.38 us                                                | 6.23 us: 1.02x faster                                                  |
| sqlglot_normalize          | 112 ms                                                 | 109 ms: 1.02x faster                                                   |
| sympy_str                  | 296 ms                                                 | 290 ms: 1.02x faster                                                   |
| logging_format             | 7.10 us                                                | 6.98 us: 1.02x faster                                                  |
| json_loads                 | 28.4 us                                                | 28.0 us: 1.01x faster                                                  |
| deepcopy                   | 363 us                                                 | 358 us: 1.01x faster                                                   |
| pickle                     | 11.2 us                                                | 11.1 us: 1.01x faster                                                  |
| docutils                   | 2.75 sec                                               | 2.72 sec: 1.01x faster                                                 |
| xml_etree_parse            | 159 ms                                                 | 158 ms: 1.01x faster                                                   |
| xml_etree_generate         | 88.7 ms                                                | 87.8 ms: 1.01x faster                                                  |
| json_dumps                 | 10.6 ms                                                | 10.5 ms: 1.01x faster                                                  |
| async_generators           | 459 ms                                                 | 457 ms: 1.01x faster                                                   |
| regex_effbot               | 3.57 ms                                                | 3.56 ms: 1.00x faster                                                  |
| chameleon                  | 7.41 ms                                                | 7.46 ms: 1.01x slower                                                  |
| sqlglot_optimize           | 54.8 ms                                                | 55.3 ms: 1.01x slower                                                  |
| mypy2                      | 351 ms                                                 | 355 ms: 1.01x slower                                                   |
| asyncio_tcp_ssl            | 1.78 sec                                               | 1.81 sec: 1.01x slower                                                 |
| scimark_lu                 | 120 ms                                                 | 122 ms: 1.01x slower                                                   |
| sqlglot_transpile          | 1.68 ms                                                | 1.70 ms: 1.02x slower                                                  |
| bench_thread_pool          | 845 us                                                 | 860 us: 1.02x slower                                                   |
| sqlglot_parse              | 1.35 ms                                                | 1.38 ms: 1.02x slower                                                  |
| tornado_http               | 101 ms                                                 | 103 ms: 1.02x slower                                                   |
| sympy_expand               | 476 ms                                                 | 488 ms: 1.03x slower                                                   |
| async_tree_cpu_io_mixed    | 724 ms                                                 | 743 ms: 1.03x slower                                                   |
| async_tree_memoization     | 580 ms                                                 | 595 ms: 1.03x slower                                                   |
| create_gc_cycles           | 1.45 ms                                                | 1.49 ms: 1.03x slower                                                  |
| sqlite_synth               | 2.83 us                                                | 2.91 us: 1.03x slower                                                  |
| sympy_integrate            | 21.2 ms                                                | 21.9 ms: 1.03x slower                                                  |
| regex_dna                  | 209 ms                                                 | 216 ms: 1.04x slower                                                   |
| pycparser                  | 1.17 sec                                               | 1.22 sec: 1.04x slower                                                 |
| logging_silent             | 108 ns                                                 | 112 ns: 1.04x slower                                                   |
| unpickle_list              | 5.04 us                                                | 5.29 us: 1.05x slower                                                  |
| scimark_sor                | 129 ms                                                 | 137 ms: 1.06x slower                                                   |
| pidigits                   | 187 ms                                                 | 198 ms: 1.06x slower                                                   |
| async_tree_memoization_tg  | 574 ms                                                 | 610 ms: 1.06x slower                                                   |
| async_tree_io              | 1.16 sec                                               | 1.24 sec: 1.06x slower                                                 |
| async_tree_io_tg           | 1.19 sec                                               | 1.27 sec: 1.07x slower                                                 |
| raytrace                   | 308 ms                                                 | 328 ms: 1.07x slower                                                   |
| async_tree_cpu_io_mixed_tg | 725 ms                                                 | 773 ms: 1.07x slower                                                   |
| mdp                        | 2.57 sec                                               | 2.75 sec: 1.07x slower                                                 |
| async_tree_none_tg         | 447 ms                                                 | 481 ms: 1.07x slower                                                   |
| pickle_list                | 4.67 us                                                | 5.05 us: 1.08x slower                                                  |
| xml_etree_iterparse        | 106 ms                                                 | 114 ms: 1.08x slower                                                   |
| 2to3                       | 274 ms                                                 | 297 ms: 1.08x slower                                                   |
| python_startup             | 9.53 ms                                                | 10.4 ms: 1.09x slower                                                  |
| regex_v8                   | 22.7 ms                                                | 24.8 ms: 1.09x slower                                                  |
| deepcopy_memo              | 39.7 us                                                | 43.6 us: 1.10x slower                                                  |
| unpickle_pure_python       | 230 us                                                 | 252 us: 1.10x slower                                                   |
| meteor_contest             | 110 ms                                                 | 121 ms: 1.10x slower                                                   |
| richards                   | 46.0 ms                                                | 52.2 ms: 1.13x slower                                                  |
| richards_super             | 51.9 ms                                                | 59.1 ms: 1.14x slower                                                  |
| pprint_safe_repr           | 765 ms                                                 | 879 ms: 1.15x slower                                                   |
| regex_compile              | 148 ms                                                 | 171 ms: 1.16x slower                                                   |
| crypto_pyaes               | 83.6 ms                                                | 98.1 ms: 1.17x slower                                                  |
| pprint_pformat             | 1.55 sec                                               | 1.84 sec: 1.18x slower                                                 |
| go                         | 140 ms                                                 | 174 ms: 1.24x slower                                                   |
| telco                      | 7.18 ms                                                | 8.96 ms: 1.25x slower                                                  |
| scimark_monte_carlo        | 74.6 ms                                                | 93.5 ms: 1.25x slower                                                  |
| pyflate                    | 471 ms                                                 | 593 ms: 1.26x slower                                                   |
| chaos                      | 67.5 ms                                                | 85.9 ms: 1.27x slower                                                  |
| coverage                   | 75.1 ms                                                | 95.7 ms: 1.27x slower                                                  |
| fannkuch                   | 410 ms                                                 | 532 ms: 1.30x slower                                                   |
| comprehensions             | 20.9 us                                                | 27.2 us: 1.30x slower                                                  |
| python_startup_no_site     | 6.92 ms                                                | 9.05 ms: 1.31x slower                                                  |
| nqueens                    | 86.2 ms                                                | 115 ms: 1.33x slower                                                   |
| tomli_loads                | 2.30 sec                                               | 3.11 sec: 1.35x slower                                                 |
| scimark_fft                | 381 ms                                                 | 540 ms: 1.42x slower                                                   |
| float                      | 83.3 ms                                                | 119 ms: 1.43x slower                                                   |
| scimark_sparse_mat_mult    | 5.33 ms                                                | 7.82 ms: 1.47x slower                                                  |
| nbody                      | 92.2 ms                                                | 142 ms: 1.54x slower                                                   |
| mako                       | 11.5 ms                                                | 17.7 ms: 1.54x slower                                                  |
| deltablue                  | 3.71 ms                                                | 5.97 ms: 1.61x slower                                                  |
| hexiom                     | 6.54 ms                                                | 10.9 ms: 1.67x slower                                                  |
| Geometric mean             | (ref)                                                  | 1.08x slower                                                           |

Benchmark hidden because not significant (8): json, spectral_norm, pickle_dict, dulwich_log, bench_mp_pool, asyncio_websockets, pathlib, dask
Ignored benchmarks (5) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.04x
- 95% likely to have a slowdown of 1.03x
- 99% likely to have a slowdown of 1.02x
