
# Results vs. 3.12.0

- fork: python
- ref: v3.13.0a1
- machine: linux-x86_64
- commit hash: ad056f0
- commit date: 2023-10-13
- overall geometric mean: 1.02x faster \*
- HPT reliability: 99.85%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231013-linux-x86_64-python-v3.13.0a1-3.13.0a1-ad056f0 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------:|
| 2to3           | 274 ms                                                 | 269 ms: 1.02x faster                                       |
| chameleon      | 7.41 ms                                                | 7.07 ms: 1.05x faster                                      |
| docutils       | 2.75 sec                                               | 2.64 sec: 1.04x faster                                     |
| tornado_http   | 101 ms                                                 | 96.0 ms: 1.05x faster                                      |
| Geometric mean | (ref)                                                  | 1.04x faster                                               |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231013-linux-x86_64-python-v3.13.0a1-3.13.0a1-ad056f0 |
|----------------------------|:------------------------------------------------------:|:----------------------------------------------------------:|
| async_tree_none            | 475 ms                                                 | 437 ms: 1.09x faster                                       |
| async_tree_memoization     | 580 ms                                                 | 564 ms: 1.03x faster                                       |
| async_tree_cpu_io_mixed    | 724 ms                                                 | 712 ms: 1.02x faster                                       |
| async_tree_none_tg         | 447 ms                                                 | 453 ms: 1.01x slower                                       |
| async_tree_io              | 1.16 sec                                               | 1.19 sec: 1.02x slower                                     |
| async_tree_cpu_io_mixed_tg | 725 ms                                                 | 741 ms: 1.02x slower                                       |
| async_tree_io_tg           | 1.19 sec                                               | 1.23 sec: 1.03x slower                                     |
| async_tree_memoization_tg  | 574 ms                                                 | 595 ms: 1.04x slower                                       |
| Geometric mean             | (ref)                                                  | 1.00x faster                                               |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231013-linux-x86_64-python-v3.13.0a1-3.13.0a1-ad056f0 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------:|
| nbody          | 92.2 ms                                                | 88.6 ms: 1.04x faster                                      |
| float          | 83.3 ms                                                | 81.6 ms: 1.02x faster                                      |
| pidigits       | 187 ms                                                 | 195 ms: 1.04x slower                                       |
| Geometric mean | (ref)                                                  | 1.01x faster                                               |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231013-linux-x86_64-python-v3.13.0a1-3.13.0a1-ad056f0 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------:|
| regex_compile  | 148 ms                                                 | 138 ms: 1.07x faster                                       |
| regex_dna      | 209 ms                                                 | 212 ms: 1.02x slower                                       |
| regex_effbot   | 3.57 ms                                                | 3.67 ms: 1.03x slower                                      |
| regex_v8       | 22.7 ms                                                | 24.7 ms: 1.09x slower                                      |
| Geometric mean | (ref)                                                  | 1.02x slower                                               |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231013-linux-x86_64-python-v3.13.0a1-3.13.0a1-ad056f0 |
|----------------------|:------------------------------------------------------:|:----------------------------------------------------------:|
| pickle_pure_python   | 326 us                                                 | 300 us: 1.09x faster                                       |
| tomli_loads          | 2.30 sec                                               | 2.15 sec: 1.07x faster                                     |
| unpickle             | 15.8 us                                                | 14.9 us: 1.06x faster                                      |
| unpickle_pure_python | 230 us                                                 | 222 us: 1.03x faster                                       |
| xml_etree_process    | 61.2 ms                                                | 59.9 ms: 1.02x faster                                      |
| xml_etree_generate   | 88.7 ms                                                | 86.9 ms: 1.02x faster                                      |
| json_loads           | 28.4 us                                                | 27.8 us: 1.02x faster                                      |
| xml_etree_parse      | 159 ms                                                 | 157 ms: 1.01x faster                                       |
| json_dumps           | 10.6 ms                                                | 10.5 ms: 1.01x faster                                      |
| pickle_dict          | 33.5 us                                                | 34.6 us: 1.03x slower                                      |
| pickle               | 11.2 us                                                | 11.6 us: 1.04x slower                                      |
| pickle_list          | 4.67 us                                                | 5.10 us: 1.09x slower                                      |
| Geometric mean       | (ref)                                                  | 1.01x faster                                               |

Benchmark hidden because not significant (2): xml_etree_iterparse, unpickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231013-linux-x86_64-python-v3.13.0a1-3.13.0a1-ad056f0 |
|------------------------|:------------------------------------------------------:|:----------------------------------------------------------:|
| python_startup_no_site | 6.92 ms                                                | 6.87 ms: 1.01x faster                                      |
| python_startup         | 9.53 ms                                                | 10.1 ms: 1.06x slower                                      |
| Geometric mean         | (ref)                                                  | 1.02x slower                                               |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231013-linux-x86_64-python-v3.13.0a1-3.13.0a1-ad056f0 |
|-----------|:------------------------------------------------------:|:----------------------------------------------------------:|
| mako      | 11.5 ms                                                | 11.2 ms: 1.02x faster                                      |

All benchmarks:
===============

| Benchmark                  | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231013-linux-x86_64-python-v3.13.0a1-3.13.0a1-ad056f0 |
|----------------------------|:------------------------------------------------------:|:----------------------------------------------------------:|
| crypto_pyaes               | 83.6 ms                                                | 71.8 ms: 1.16x faster                                      |
| raytrace                   | 308 ms                                                 | 274 ms: 1.12x faster                                       |
| scimark_sparse_mat_mult    | 5.33 ms                                                | 4.79 ms: 1.11x faster                                      |
| deltablue                  | 3.71 ms                                                | 3.34 ms: 1.11x faster                                      |
| gc_traversal               | 4.28 ms                                                | 3.87 ms: 1.11x faster                                      |
| logging_format             | 7.10 us                                                | 6.47 us: 1.10x faster                                      |
| chaos                      | 67.5 ms                                                | 61.7 ms: 1.09x faster                                      |
| async_tree_none            | 475 ms                                                 | 437 ms: 1.09x faster                                       |
| pickle_pure_python         | 326 us                                                 | 300 us: 1.09x faster                                       |
| generators                 | 32.5 ms                                                | 29.9 ms: 1.08x faster                                      |
| logging_simple             | 6.38 us                                                | 5.90 us: 1.08x faster                                      |
| scimark_monte_carlo        | 74.6 ms                                                | 69.5 ms: 1.07x faster                                      |
| sympy_sum                  | 167 ms                                                 | 156 ms: 1.07x faster                                       |
| tomli_loads                | 2.30 sec                                               | 2.15 sec: 1.07x faster                                     |
| regex_compile              | 148 ms                                                 | 138 ms: 1.07x faster                                       |
| hexiom                     | 6.54 ms                                                | 6.16 ms: 1.06x faster                                      |
| unpack_sequence            | 54.2 ns                                                | 51.0 ns: 1.06x faster                                      |
| unpickle                   | 15.8 us                                                | 14.9 us: 1.06x faster                                      |
| sympy_str                  | 296 ms                                                 | 281 ms: 1.05x faster                                       |
| sympy_expand               | 476 ms                                                 | 452 ms: 1.05x faster                                       |
| nqueens                    | 86.2 ms                                                | 81.9 ms: 1.05x faster                                      |
| scimark_sor                | 129 ms                                                 | 123 ms: 1.05x faster                                       |
| sqlglot_parse              | 1.35 ms                                                | 1.29 ms: 1.05x faster                                      |
| tornado_http               | 101 ms                                                 | 96.0 ms: 1.05x faster                                      |
| sympy_integrate            | 21.2 ms                                                | 20.2 ms: 1.05x faster                                      |
| chameleon                  | 7.41 ms                                                | 7.07 ms: 1.05x faster                                      |
| sqlglot_normalize          | 112 ms                                                 | 107 ms: 1.05x faster                                       |
| scimark_lu                 | 120 ms                                                 | 115 ms: 1.05x faster                                       |
| sqlglot_transpile          | 1.68 ms                                                | 1.60 ms: 1.05x faster                                      |
| asyncio_tcp                | 506 ms                                                 | 484 ms: 1.05x faster                                       |
| docutils                   | 2.75 sec                                               | 2.64 sec: 1.04x faster                                     |
| spectral_norm              | 115 ms                                                 | 110 ms: 1.04x faster                                       |
| nbody                      | 92.2 ms                                                | 88.6 ms: 1.04x faster                                      |
| bench_thread_pool          | 845 us                                                 | 815 us: 1.04x faster                                       |
| unpickle_pure_python       | 230 us                                                 | 222 us: 1.03x faster                                       |
| scimark_fft                | 381 ms                                                 | 369 ms: 1.03x faster                                       |
| deepcopy                   | 363 us                                                 | 353 us: 1.03x faster                                       |
| async_tree_memoization     | 580 ms                                                 | 564 ms: 1.03x faster                                       |
| deepcopy_reduce            | 3.23 us                                                | 3.14 us: 1.03x faster                                      |
| deepcopy_memo              | 39.7 us                                                | 38.7 us: 1.03x faster                                      |
| dulwich_log                | 68.7 ms                                                | 67.1 ms: 1.02x faster                                      |
| xml_etree_process          | 61.2 ms                                                | 59.9 ms: 1.02x faster                                      |
| mypy2                      | 351 ms                                                 | 343 ms: 1.02x faster                                       |
| mako                       | 11.5 ms                                                | 11.2 ms: 1.02x faster                                      |
| xml_etree_generate         | 88.7 ms                                                | 86.9 ms: 1.02x faster                                      |
| float                      | 83.3 ms                                                | 81.6 ms: 1.02x faster                                      |
| 2to3                       | 274 ms                                                 | 269 ms: 1.02x faster                                       |
| json_loads                 | 28.4 us                                                | 27.8 us: 1.02x faster                                      |
| fannkuch                   | 410 ms                                                 | 402 ms: 1.02x faster                                       |
| pprint_safe_repr           | 765 ms                                                 | 752 ms: 1.02x faster                                       |
| sqlglot_optimize           | 54.8 ms                                                | 53.9 ms: 1.02x faster                                      |
| async_tree_cpu_io_mixed    | 724 ms                                                 | 712 ms: 1.02x faster                                       |
| pprint_pformat             | 1.55 sec                                               | 1.53 sec: 1.02x faster                                     |
| async_generators           | 459 ms                                                 | 453 ms: 1.01x faster                                       |
| sqlite_synth               | 2.83 us                                                | 2.80 us: 1.01x faster                                      |
| xml_etree_parse            | 159 ms                                                 | 157 ms: 1.01x faster                                       |
| json                       | 5.22 ms                                                | 5.16 ms: 1.01x faster                                      |
| json_dumps                 | 10.6 ms                                                | 10.5 ms: 1.01x faster                                      |
| python_startup_no_site     | 6.92 ms                                                | 6.87 ms: 1.01x faster                                      |
| comprehensions             | 20.9 us                                                | 20.8 us: 1.01x faster                                      |
| meteor_contest             | 110 ms                                                 | 109 ms: 1.00x faster                                       |
| asyncio_tcp_ssl            | 1.78 sec                                               | 1.79 sec: 1.00x slower                                     |
| pyflate                    | 471 ms                                                 | 473 ms: 1.01x slower                                       |
| go                         | 140 ms                                                 | 141 ms: 1.01x slower                                       |
| async_tree_none_tg         | 447 ms                                                 | 453 ms: 1.01x slower                                       |
| typing_runtime_protocols   | 153 us                                                 | 156 us: 1.02x slower                                       |
| create_gc_cycles           | 1.45 ms                                                | 1.48 ms: 1.02x slower                                      |
| regex_dna                  | 209 ms                                                 | 212 ms: 1.02x slower                                       |
| async_tree_io              | 1.16 sec                                               | 1.19 sec: 1.02x slower                                     |
| async_tree_cpu_io_mixed_tg | 725 ms                                                 | 741 ms: 1.02x slower                                       |
| pathlib                    | 18.9 ms                                                | 19.4 ms: 1.02x slower                                      |
| regex_effbot               | 3.57 ms                                                | 3.67 ms: 1.03x slower                                      |
| pycparser                  | 1.17 sec                                               | 1.20 sec: 1.03x slower                                     |
| pickle_dict                | 33.5 us                                                | 34.6 us: 1.03x slower                                      |
| async_tree_io_tg           | 1.19 sec                                               | 1.23 sec: 1.03x slower                                     |
| async_tree_memoization_tg  | 574 ms                                                 | 595 ms: 1.04x slower                                       |
| pickle                     | 11.2 us                                                | 11.6 us: 1.04x slower                                      |
| pidigits                   | 187 ms                                                 | 195 ms: 1.04x slower                                       |
| richards                   | 46.0 ms                                                | 48.6 ms: 1.06x slower                                      |
| python_startup             | 9.53 ms                                                | 10.1 ms: 1.06x slower                                      |
| richards_super             | 51.9 ms                                                | 55.0 ms: 1.06x slower                                      |
| mdp                        | 2.57 sec                                               | 2.74 sec: 1.07x slower                                     |
| pickle_list                | 4.67 us                                                | 5.10 us: 1.09x slower                                      |
| regex_v8                   | 22.7 ms                                                | 24.7 ms: 1.09x slower                                      |
| telco                      | 7.18 ms                                                | 8.17 ms: 1.14x slower                                      |
| coverage                   | 75.1 ms                                                | 94.4 ms: 1.26x slower                                      |
| Geometric mean             | (ref)                                                  | 1.02x faster                                               |

Benchmark hidden because not significant (6): logging_silent, coroutines, xml_etree_iterparse, asyncio_websockets, bench_mp_pool, unpickle_list
Ignored benchmarks (6) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, dask, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 99.85% likely to be faster
- 90% likely to have a speedup of 1.01x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
