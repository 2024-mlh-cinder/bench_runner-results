
# Results vs. 3.12.0

- fork: python
- ref: 9da98c0d9a7cc55c67fb
- machine: linux-x86_64
- commit hash: 9da98c0
- commit date: 2023-10-25
- overall geometric mean: 1.02x faster
- HPT reliability: 99.84%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231025-linux-x86_64-python-9da98c0d9a7cc55c67fb-3.13.0a1+-9da98c0 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| 2to3           | 274 ms                                                 | 268 ms: 1.02x faster                                                   |
| chameleon      | 7.41 ms                                                | 6.91 ms: 1.07x faster                                                  |
| docutils       | 2.75 sec                                               | 2.65 sec: 1.04x faster                                                 |
| tornado_http   | 101 ms                                                 | 95.2 ms: 1.06x faster                                                  |
| Geometric mean | (ref)                                                  | 1.05x faster                                                           |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231025-linux-x86_64-python-9da98c0d9a7cc55c67fb-3.13.0a1+-9da98c0 |
|----------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| async_tree_none            | 475 ms                                                 | 440 ms: 1.08x faster                                                   |
| async_tree_memoization     | 580 ms                                                 | 567 ms: 1.02x faster                                                   |
| async_tree_none_tg         | 447 ms                                                 | 456 ms: 1.02x slower                                                   |
| async_tree_io              | 1.16 sec                                               | 1.19 sec: 1.02x slower                                                 |
| async_tree_cpu_io_mixed_tg | 725 ms                                                 | 746 ms: 1.03x slower                                                   |
| async_tree_io_tg           | 1.19 sec                                               | 1.23 sec: 1.04x slower                                                 |
| async_tree_memoization_tg  | 574 ms                                                 | 598 ms: 1.04x slower                                                   |
| Geometric mean             | (ref)                                                  | 1.00x slower                                                           |

Benchmark hidden because not significant (1): async_tree_cpu_io_mixed

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231025-linux-x86_64-python-9da98c0d9a7cc55c67fb-3.13.0a1+-9da98c0 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| float          | 83.3 ms                                                | 81.8 ms: 1.02x faster                                                  |
| pidigits       | 187 ms                                                 | 187 ms: 1.00x slower                                                   |
| nbody          | 92.2 ms                                                | 98.1 ms: 1.06x slower                                                  |
| Geometric mean | (ref)                                                  | 1.02x slower                                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231025-linux-x86_64-python-9da98c0d9a7cc55c67fb-3.13.0a1+-9da98c0 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| regex_compile  | 148 ms                                                 | 138 ms: 1.08x faster                                                   |
| regex_dna      | 209 ms                                                 | 218 ms: 1.05x slower                                                   |
| regex_effbot   | 3.57 ms                                                | 3.84 ms: 1.07x slower                                                  |
| regex_v8       | 22.7 ms                                                | 25.4 ms: 1.12x slower                                                  |
| Geometric mean | (ref)                                                  | 1.04x slower                                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231025-linux-x86_64-python-9da98c0d9a7cc55c67fb-3.13.0a1+-9da98c0 |
|----------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| tomli_loads          | 2.30 sec                                               | 2.15 sec: 1.07x faster                                                 |
| unpickle             | 15.8 us                                                | 14.8 us: 1.07x faster                                                  |
| pickle_pure_python   | 326 us                                                 | 308 us: 1.06x faster                                                   |
| unpickle_pure_python | 230 us                                                 | 221 us: 1.04x faster                                                   |
| xml_etree_process    | 61.2 ms                                                | 59.4 ms: 1.03x faster                                                  |
| xml_etree_generate   | 88.7 ms                                                | 86.5 ms: 1.03x faster                                                  |
| json_loads           | 28.4 us                                                | 27.8 us: 1.02x faster                                                  |
| json_dumps           | 10.6 ms                                                | 10.4 ms: 1.02x faster                                                  |
| unpickle_list        | 5.04 us                                                | 5.17 us: 1.02x slower                                                  |
| pickle_list          | 4.67 us                                                | 4.99 us: 1.07x slower                                                  |
| Geometric mean       | (ref)                                                  | 1.02x faster                                                           |

Benchmark hidden because not significant (4): pickle_dict, xml_etree_parse, pickle, xml_etree_iterparse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231025-linux-x86_64-python-9da98c0d9a7cc55c67fb-3.13.0a1+-9da98c0 |
|------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| python_startup_no_site | 6.92 ms                                                | 6.88 ms: 1.00x faster                                                  |
| python_startup         | 9.53 ms                                                | 10.1 ms: 1.06x slower                                                  |
| Geometric mean         | (ref)                                                  | 1.03x slower                                                           |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231025-linux-x86_64-python-9da98c0d9a7cc55c67fb-3.13.0a1+-9da98c0 |
|-----------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| mako      | 11.5 ms                                                | 11.2 ms: 1.03x faster                                                  |

All benchmarks:
===============

| Benchmark                  | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231025-linux-x86_64-python-9da98c0d9a7cc55c67fb-3.13.0a1+-9da98c0 |
|----------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| unpack_sequence            | 54.2 ns                                                | 44.8 ns: 1.21x faster                                                  |
| crypto_pyaes               | 83.6 ms                                                | 72.5 ms: 1.15x faster                                                  |
| raytrace                   | 308 ms                                                 | 273 ms: 1.13x faster                                                   |
| gc_traversal               | 4.28 ms                                                | 3.79 ms: 1.13x faster                                                  |
| deltablue                  | 3.71 ms                                                | 3.29 ms: 1.13x faster                                                  |
| logging_format             | 7.10 us                                                | 6.47 us: 1.10x faster                                                  |
| generators                 | 32.5 ms                                                | 29.6 ms: 1.10x faster                                                  |
| chaos                      | 67.5 ms                                                | 62.2 ms: 1.08x faster                                                  |
| logging_simple             | 6.38 us                                                | 5.89 us: 1.08x faster                                                  |
| async_tree_none            | 475 ms                                                 | 440 ms: 1.08x faster                                                   |
| scimark_monte_carlo        | 74.6 ms                                                | 69.2 ms: 1.08x faster                                                  |
| regex_compile              | 148 ms                                                 | 138 ms: 1.08x faster                                                   |
| sympy_sum                  | 167 ms                                                 | 156 ms: 1.07x faster                                                   |
| chameleon                  | 7.41 ms                                                | 6.91 ms: 1.07x faster                                                  |
| tomli_loads                | 2.30 sec                                               | 2.15 sec: 1.07x faster                                                 |
| unpickle                   | 15.8 us                                                | 14.8 us: 1.07x faster                                                  |
| hexiom                     | 6.54 ms                                                | 6.15 ms: 1.06x faster                                                  |
| sympy_str                  | 296 ms                                                 | 279 ms: 1.06x faster                                                   |
| pickle_pure_python         | 326 us                                                 | 308 us: 1.06x faster                                                   |
| nqueens                    | 86.2 ms                                                | 81.3 ms: 1.06x faster                                                  |
| tornado_http               | 101 ms                                                 | 95.2 ms: 1.06x faster                                                  |
| sqlglot_normalize          | 112 ms                                                 | 106 ms: 1.06x faster                                                   |
| sympy_expand               | 476 ms                                                 | 453 ms: 1.05x faster                                                   |
| scimark_lu                 | 120 ms                                                 | 115 ms: 1.05x faster                                                   |
| sympy_integrate            | 21.2 ms                                                | 20.3 ms: 1.05x faster                                                  |
| sqlglot_parse              | 1.35 ms                                                | 1.29 ms: 1.05x faster                                                  |
| asyncio_tcp                | 506 ms                                                 | 484 ms: 1.04x faster                                                   |
| scimark_sparse_mat_mult    | 5.33 ms                                                | 5.13 ms: 1.04x faster                                                  |
| bench_thread_pool          | 845 us                                                 | 812 us: 1.04x faster                                                   |
| sqlglot_transpile          | 1.68 ms                                                | 1.61 ms: 1.04x faster                                                  |
| unpickle_pure_python       | 230 us                                                 | 221 us: 1.04x faster                                                   |
| deepcopy_memo              | 39.7 us                                                | 38.3 us: 1.04x faster                                                  |
| docutils                   | 2.75 sec                                               | 2.65 sec: 1.04x faster                                                 |
| deepcopy_reduce            | 3.23 us                                                | 3.12 us: 1.04x faster                                                  |
| coroutines                 | 23.5 ms                                                | 22.7 ms: 1.03x faster                                                  |
| xml_etree_process          | 61.2 ms                                                | 59.4 ms: 1.03x faster                                                  |
| dulwich_log                | 68.7 ms                                                | 66.9 ms: 1.03x faster                                                  |
| scimark_sor                | 129 ms                                                 | 126 ms: 1.03x faster                                                   |
| spectral_norm              | 115 ms                                                 | 112 ms: 1.03x faster                                                   |
| xml_etree_generate         | 88.7 ms                                                | 86.5 ms: 1.03x faster                                                  |
| mako                       | 11.5 ms                                                | 11.2 ms: 1.03x faster                                                  |
| json                       | 5.22 ms                                                | 5.09 ms: 1.03x faster                                                  |
| sqlglot_optimize           | 54.8 ms                                                | 53.5 ms: 1.02x faster                                                  |
| mypy2                      | 351 ms                                                 | 343 ms: 1.02x faster                                                   |
| deepcopy                   | 363 us                                                 | 354 us: 1.02x faster                                                   |
| 2to3                       | 274 ms                                                 | 268 ms: 1.02x faster                                                   |
| async_tree_memoization     | 580 ms                                                 | 567 ms: 1.02x faster                                                   |
| json_loads                 | 28.4 us                                                | 27.8 us: 1.02x faster                                                  |
| pprint_pformat             | 1.55 sec                                               | 1.52 sec: 1.02x faster                                                 |
| pprint_safe_repr           | 765 ms                                                 | 751 ms: 1.02x faster                                                   |
| float                      | 83.3 ms                                                | 81.8 ms: 1.02x faster                                                  |
| json_dumps                 | 10.6 ms                                                | 10.4 ms: 1.02x faster                                                  |
| meteor_contest             | 110 ms                                                 | 108 ms: 1.01x faster                                                   |
| typing_runtime_protocols   | 153 us                                                 | 151 us: 1.01x faster                                                   |
| sqlite_synth               | 2.83 us                                                | 2.81 us: 1.01x faster                                                  |
| comprehensions             | 20.9 us                                                | 20.8 us: 1.01x faster                                                  |
| logging_silent             | 108 ns                                                 | 107 ns: 1.01x faster                                                   |
| async_generators           | 459 ms                                                 | 456 ms: 1.01x faster                                                   |
| python_startup_no_site     | 6.92 ms                                                | 6.88 ms: 1.00x faster                                                  |
| asyncio_tcp_ssl            | 1.78 sec                                               | 1.77 sec: 1.00x faster                                                 |
| pidigits                   | 187 ms                                                 | 187 ms: 1.00x slower                                                   |
| fannkuch                   | 410 ms                                                 | 412 ms: 1.00x slower                                                   |
| scimark_fft                | 381 ms                                                 | 384 ms: 1.01x slower                                                   |
| create_gc_cycles           | 1.45 ms                                                | 1.47 ms: 1.01x slower                                                  |
| mdp                        | 2.57 sec                                               | 2.61 sec: 1.02x slower                                                 |
| async_tree_none_tg         | 447 ms                                                 | 456 ms: 1.02x slower                                                   |
| async_tree_io              | 1.16 sec                                               | 1.19 sec: 1.02x slower                                                 |
| unpickle_list              | 5.04 us                                                | 5.17 us: 1.02x slower                                                  |
| async_tree_cpu_io_mixed_tg | 725 ms                                                 | 746 ms: 1.03x slower                                                   |
| async_tree_io_tg           | 1.19 sec                                               | 1.23 sec: 1.04x slower                                                 |
| async_tree_memoization_tg  | 574 ms                                                 | 598 ms: 1.04x slower                                                   |
| regex_dna                  | 209 ms                                                 | 218 ms: 1.05x slower                                                   |
| richards_super             | 51.9 ms                                                | 54.6 ms: 1.05x slower                                                  |
| python_startup             | 9.53 ms                                                | 10.1 ms: 1.06x slower                                                  |
| richards                   | 46.0 ms                                                | 48.9 ms: 1.06x slower                                                  |
| nbody                      | 92.2 ms                                                | 98.1 ms: 1.06x slower                                                  |
| pickle_list                | 4.67 us                                                | 4.99 us: 1.07x slower                                                  |
| regex_effbot               | 3.57 ms                                                | 3.84 ms: 1.07x slower                                                  |
| regex_v8                   | 22.7 ms                                                | 25.4 ms: 1.12x slower                                                  |
| telco                      | 7.18 ms                                                | 8.28 ms: 1.15x slower                                                  |
| coverage                   | 75.1 ms                                                | 94.9 ms: 1.26x slower                                                  |
| Geometric mean             | (ref)                                                  | 1.02x faster                                                           |

Benchmark hidden because not significant (11): async_tree_cpu_io_mixed, pycparser, asyncio_websockets, bench_mp_pool, go, pickle_dict, xml_etree_parse, pyflate, pickle, pathlib, xml_etree_iterparse
Ignored benchmarks (6) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, dask, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 99.84% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
