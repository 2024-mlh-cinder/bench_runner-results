
# Results vs. 3.11.0

- fork: python
- ref: main
- machine: linux-x86_64
- commit hash: 66bea25
- commit date: 2023-10-29
- overall geometric mean: 1.06x faster
- HPT reliability: 99.94%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231029-linux-x86_64-python-main-3.13.0a1+-66bea25 |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| 2to3           | 266 ms                                                 | 265 ms: 1.01x faster                                   |
| chameleon      | 6.86 ms                                                | 6.93 ms: 1.01x slower                                  |
| docutils       | 2.69 sec                                               | 2.64 sec: 1.02x faster                                 |
| tornado_http   | 97.7 ms                                                | 95.6 ms: 1.02x faster                                  |
| Geometric mean | (ref)                                                  | 1.01x faster                                           |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231029-linux-x86_64-python-main-3.13.0a1+-66bea25 |
|----------------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| async_tree_none            | 532 ms                                                 | 439 ms: 1.21x faster                                   |
| async_tree_memoization     | 640 ms                                                 | 563 ms: 1.14x faster                                   |
| async_tree_io              | 1.31 sec                                               | 1.19 sec: 1.10x faster                                 |
| async_tree_none_tg         | 490 ms                                                 | 456 ms: 1.07x faster                                   |
| async_tree_io_tg           | 1.30 sec                                               | 1.23 sec: 1.06x faster                                 |
| async_tree_cpu_io_mixed    | 750 ms                                                 | 709 ms: 1.06x faster                                   |
| async_tree_memoization_tg  | 627 ms                                                 | 598 ms: 1.05x faster                                   |
| async_tree_cpu_io_mixed_tg | 764 ms                                                 | 744 ms: 1.03x faster                                   |
| Geometric mean             | (ref)                                                  | 1.09x faster                                           |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231029-linux-x86_64-python-main-3.13.0a1+-66bea25 |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| pidigits       | 190 ms                                                 | 187 ms: 1.02x faster                                   |
| float          | 78.9 ms                                                | 81.0 ms: 1.03x slower                                  |
| nbody          | 91.6 ms                                                | 94.5 ms: 1.03x slower                                  |
| Geometric mean | (ref)                                                  | 1.01x slower                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231029-linux-x86_64-python-main-3.13.0a1+-66bea25 |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| regex_compile  | 141 ms                                                 | 136 ms: 1.04x faster                                   |
| regex_effbot   | 3.45 ms                                                | 3.63 ms: 1.05x slower                                  |
| regex_dna      | 204 ms                                                 | 219 ms: 1.07x slower                                   |
| regex_v8       | 22.9 ms                                                | 25.0 ms: 1.09x slower                                  |
| Geometric mean | (ref)                                                  | 1.04x slower                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231029-linux-x86_64-python-main-3.13.0a1+-66bea25 |
|----------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| json_dumps           | 13.5 ms                                                | 10.5 ms: 1.29x faster                                  |
| unpickle_pure_python | 241 us                                                 | 220 us: 1.10x faster                                   |
| tomli_loads          | 2.31 sec                                               | 2.15 sec: 1.08x faster                                 |
| json_loads           | 29.4 us                                                | 27.8 us: 1.06x faster                                  |
| pickle_pure_python   | 319 us                                                 | 302 us: 1.06x faster                                   |
| pickle_dict          | 34.8 us                                                | 33.2 us: 1.05x faster                                  |
| xml_etree_parse      | 163 ms                                                 | 159 ms: 1.02x faster                                   |
| xml_etree_iterparse  | 109 ms                                                 | 106 ms: 1.02x faster                                   |
| unpickle_list        | 5.22 us                                                | 5.15 us: 1.01x faster                                  |
| pickle               | 11.1 us                                                | 11.3 us: 1.02x slower                                  |
| pickle_list          | 4.65 us                                                | 4.81 us: 1.03x slower                                  |
| xml_etree_process    | 56.5 ms                                                | 59.2 ms: 1.05x slower                                  |
| unpickle             | 13.9 us                                                | 14.6 us: 1.05x slower                                  |
| xml_etree_generate   | 80.4 ms                                                | 86.2 ms: 1.07x slower                                  |
| Geometric mean       | (ref)                                                  | 1.03x faster                                           |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231029-linux-x86_64-python-main-3.13.0a1+-66bea25 |
|------------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| python_startup         | 8.69 ms                                                | 10.3 ms: 1.19x slower                                  |
| python_startup_no_site | 6.09 ms                                                | 8.97 ms: 1.47x slower                                  |
| Geometric mean         | (ref)                                                  | 1.32x slower                                           |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231029-linux-x86_64-python-main-3.13.0a1+-66bea25 |
|-----------|:------------------------------------------------------:|:------------------------------------------------------:|
| mako      | 10.8 ms                                                | 11.5 ms: 1.06x slower                                  |

All benchmarks:
===============

| Benchmark                  | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231029-linux-x86_64-python-main-3.13.0a1+-66bea25 |
|----------------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| typing_runtime_protocols   | 521 us                                                 | 152 us: 3.43x faster                                   |
| generators                 | 76.5 ms                                                | 29.5 ms: 2.59x faster                                  |
| asyncio_tcp                | 887 ms                                                 | 474 ms: 1.87x faster                                   |
| asyncio_tcp_ssl            | 3.13 sec                                               | 1.79 sec: 1.75x faster                                 |
| comprehensions             | 23.6 us                                                | 16.5 us: 1.42x faster                                  |
| json_dumps                 | 13.5 ms                                                | 10.5 ms: 1.29x faster                                  |
| mypy2                      | 427 ms                                                 | 342 ms: 1.25x faster                                   |
| async_tree_none            | 532 ms                                                 | 439 ms: 1.21x faster                                   |
| coroutines                 | 26.1 ms                                                | 22.5 ms: 1.16x faster                                  |
| sympy_sum                  | 170 ms                                                 | 148 ms: 1.15x faster                                   |
| chaos                      | 71.4 ms                                                | 62.0 ms: 1.15x faster                                  |
| async_tree_memoization     | 640 ms                                                 | 563 ms: 1.14x faster                                   |
| deltablue                  | 3.80 ms                                                | 3.40 ms: 1.12x faster                                  |
| sympy_str                  | 299 ms                                                 | 268 ms: 1.12x faster                                   |
| sqlglot_parse              | 1.43 ms                                                | 1.29 ms: 1.11x faster                                  |
| raytrace                   | 306 ms                                                 | 276 ms: 1.11x faster                                   |
| richards_super             | 61.2 ms                                                | 55.5 ms: 1.10x faster                                  |
| async_tree_io              | 1.31 sec                                               | 1.19 sec: 1.10x faster                                 |
| mdp                        | 2.79 sec                                               | 2.54 sec: 1.10x faster                                 |
| unpickle_pure_python       | 241 us                                                 | 220 us: 1.10x faster                                   |
| sqlglot_transpile          | 1.75 ms                                                | 1.61 ms: 1.09x faster                                  |
| sympy_expand               | 490 ms                                                 | 452 ms: 1.08x faster                                   |
| nqueens                    | 86.8 ms                                                | 80.2 ms: 1.08x faster                                  |
| tomli_loads                | 2.31 sec                                               | 2.15 sec: 1.08x faster                                 |
| sympy_integrate            | 21.4 ms                                                | 19.9 ms: 1.07x faster                                  |
| async_tree_none_tg         | 490 ms                                                 | 456 ms: 1.07x faster                                   |
| crypto_pyaes               | 77.5 ms                                                | 72.2 ms: 1.07x faster                                  |
| hexiom                     | 6.74 ms                                                | 6.29 ms: 1.07x faster                                  |
| sqlglot_normalize          | 112 ms                                                 | 106 ms: 1.06x faster                                   |
| async_tree_io_tg           | 1.30 sec                                               | 1.23 sec: 1.06x faster                                 |
| json_loads                 | 29.4 us                                                | 27.8 us: 1.06x faster                                  |
| async_tree_cpu_io_mixed    | 750 ms                                                 | 709 ms: 1.06x faster                                   |
| pickle_pure_python         | 319 us                                                 | 302 us: 1.06x faster                                   |
| logging_simple             | 6.24 us                                                | 5.95 us: 1.05x faster                                  |
| async_tree_memoization_tg  | 627 ms                                                 | 598 ms: 1.05x faster                                   |
| pickle_dict                | 34.8 us                                                | 33.2 us: 1.05x faster                                  |
| logging_format             | 6.83 us                                                | 6.54 us: 1.04x faster                                  |
| scimark_monte_carlo        | 71.8 ms                                                | 68.8 ms: 1.04x faster                                  |
| regex_compile              | 141 ms                                                 | 136 ms: 1.04x faster                                   |
| sqlglot_optimize           | 55.2 ms                                                | 53.3 ms: 1.03x faster                                  |
| logging_silent             | 108 ns                                                 | 105 ns: 1.03x faster                                   |
| gc_traversal               | 3.90 ms                                                | 3.79 ms: 1.03x faster                                  |
| json                       | 5.24 ms                                                | 5.09 ms: 1.03x faster                                  |
| async_tree_cpu_io_mixed_tg | 764 ms                                                 | 744 ms: 1.03x faster                                   |
| deepcopy                   | 360 us                                                 | 351 us: 1.03x faster                                   |
| xml_etree_parse            | 163 ms                                                 | 159 ms: 1.02x faster                                   |
| xml_etree_iterparse        | 109 ms                                                 | 106 ms: 1.02x faster                                   |
| bench_thread_pool          | 833 us                                                 | 815 us: 1.02x faster                                   |
| tornado_http               | 97.7 ms                                                | 95.6 ms: 1.02x faster                                  |
| deepcopy_reduce            | 3.14 us                                                | 3.07 us: 1.02x faster                                  |
| pprint_pformat             | 1.53 sec                                               | 1.50 sec: 1.02x faster                                 |
| docutils                   | 2.69 sec                                               | 2.64 sec: 1.02x faster                                 |
| pidigits                   | 190 ms                                                 | 187 ms: 1.02x faster                                   |
| unpickle_list              | 5.22 us                                                | 5.15 us: 1.01x faster                                  |
| meteor_contest             | 109 ms                                                 | 108 ms: 1.01x faster                                   |
| asyncio_websockets         | 556 ms                                                 | 551 ms: 1.01x faster                                   |
| pprint_safe_repr           | 743 ms                                                 | 738 ms: 1.01x faster                                   |
| 2to3                       | 266 ms                                                 | 265 ms: 1.01x faster                                   |
| create_gc_cycles           | 1.48 ms                                                | 1.47 ms: 1.00x faster                                  |
| fannkuch                   | 410 ms                                                 | 408 ms: 1.00x faster                                   |
| deepcopy_memo              | 38.9 us                                                | 39.1 us: 1.01x slower                                  |
| chameleon                  | 6.86 ms                                                | 6.93 ms: 1.01x slower                                  |
| go                         | 143 ms                                                 | 145 ms: 1.01x slower                                   |
| pickle                     | 11.1 us                                                | 11.3 us: 1.02x slower                                  |
| richards                   | 48.9 ms                                                | 49.6 ms: 1.02x slower                                  |
| scimark_lu                 | 112 ms                                                 | 115 ms: 1.02x slower                                   |
| float                      | 78.9 ms                                                | 81.0 ms: 1.03x slower                                  |
| scimark_sparse_mat_mult    | 4.80 ms                                                | 4.95 ms: 1.03x slower                                  |
| dulwich_log                | 64.9 ms                                                | 67.0 ms: 1.03x slower                                  |
| nbody                      | 91.6 ms                                                | 94.5 ms: 1.03x slower                                  |
| pickle_list                | 4.65 us                                                | 4.81 us: 1.03x slower                                  |
| pathlib                    | 18.5 ms                                                | 19.2 ms: 1.04x slower                                  |
| xml_etree_process          | 56.5 ms                                                | 59.2 ms: 1.05x slower                                  |
| scimark_sor                | 121 ms                                                 | 127 ms: 1.05x slower                                   |
| regex_effbot               | 3.45 ms                                                | 3.63 ms: 1.05x slower                                  |
| unpickle                   | 13.9 us                                                | 14.6 us: 1.05x slower                                  |
| mako                       | 10.8 ms                                                | 11.5 ms: 1.06x slower                                  |
| xml_etree_generate         | 80.4 ms                                                | 86.2 ms: 1.07x slower                                  |
| regex_dna                  | 204 ms                                                 | 219 ms: 1.07x slower                                   |
| scimark_fft                | 342 ms                                                 | 369 ms: 1.08x slower                                   |
| spectral_norm              | 105 ms                                                 | 114 ms: 1.08x slower                                   |
| pyflate                    | 426 ms                                                 | 462 ms: 1.08x slower                                   |
| sqlite_synth               | 2.58 us                                                | 2.81 us: 1.09x slower                                  |
| regex_v8                   | 22.9 ms                                                | 25.0 ms: 1.09x slower                                  |
| unpack_sequence            | 43.3 ns                                                | 47.3 ns: 1.09x slower                                  |
| coverage                   | 81.2 ms                                                | 93.2 ms: 1.15x slower                                  |
| python_startup             | 8.69 ms                                                | 10.3 ms: 1.19x slower                                  |
| async_generators           | 375 ms                                                 | 454 ms: 1.21x slower                                   |
| telco                      | 6.72 ms                                                | 8.29 ms: 1.23x slower                                  |
| python_startup_no_site     | 6.09 ms                                                | 8.97 ms: 1.47x slower                                  |
| Geometric mean             | (ref)                                                  | 1.06x faster                                           |

Benchmark hidden because not significant (2): pycparser, bench_mp_pool
Ignored benchmarks (13) of results/bm-20221024-3.11.0-deaf509/bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift


# HPT report

- Reliability score: 99.94% likely to be faster
- 90% likely to have a speedup of 1.01x
- 95% likely to have a speedup of 1.01x
- 99% likely to have a speedup of 1.00x
