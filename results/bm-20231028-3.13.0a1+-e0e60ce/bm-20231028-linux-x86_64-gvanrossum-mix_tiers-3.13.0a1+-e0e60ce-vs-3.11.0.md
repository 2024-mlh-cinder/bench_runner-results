
# Results vs. 3.11.0

- fork: gvanrossum
- ref: mix_tiers
- machine: linux-x86_64
- commit hash: e0e60ce
- commit date: 2023-10-28
- overall geometric mean: 1.01x slower
- HPT reliability: 98.21%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231028-linux-x86_64-gvanrossum-mix_tiers-3.13.0a1+-e0e60ce |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------:|
| 2to3           | 266 ms                                                 | 290 ms: 1.09x slower                                            |
| chameleon      | 6.86 ms                                                | 7.56 ms: 1.10x slower                                           |
| docutils       | 2.69 sec                                               | 2.76 sec: 1.03x slower                                          |
| tornado_http   | 97.7 ms                                                | 102 ms: 1.05x slower                                            |
| Geometric mean | (ref)                                                  | 1.07x slower                                                    |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231028-linux-x86_64-gvanrossum-mix_tiers-3.13.0a1+-e0e60ce |
|----------------------------|:------------------------------------------------------:|:---------------------------------------------------------------:|
| async_tree_none            | 532 ms                                                 | 448 ms: 1.19x faster                                            |
| async_tree_memoization     | 640 ms                                                 | 577 ms: 1.11x faster                                            |
| async_tree_io              | 1.31 sec                                               | 1.20 sec: 1.09x faster                                          |
| async_tree_none_tg         | 490 ms                                                 | 465 ms: 1.05x faster                                            |
| async_tree_io_tg           | 1.30 sec                                               | 1.25 sec: 1.04x faster                                          |
| async_tree_cpu_io_mixed    | 750 ms                                                 | 718 ms: 1.04x faster                                            |
| async_tree_memoization_tg  | 627 ms                                                 | 613 ms: 1.02x faster                                            |
| async_tree_cpu_io_mixed_tg | 764 ms                                                 | 750 ms: 1.02x faster                                            |
| Geometric mean             | (ref)                                                  | 1.07x faster                                                    |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231028-linux-x86_64-gvanrossum-mix_tiers-3.13.0a1+-e0e60ce |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------:|
| pidigits       | 190 ms                                                 | 188 ms: 1.01x faster                                            |
| float          | 78.9 ms                                                | 95.1 ms: 1.21x slower                                           |
| nbody          | 91.6 ms                                                | 118 ms: 1.28x slower                                            |
| Geometric mean | (ref)                                                  | 1.15x slower                                                    |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231028-linux-x86_64-gvanrossum-mix_tiers-3.13.0a1+-e0e60ce |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------:|
| regex_effbot   | 3.45 ms                                                | 3.58 ms: 1.04x slower                                           |
| regex_v8       | 22.9 ms                                                | 24.6 ms: 1.07x slower                                           |
| regex_dna      | 204 ms                                                 | 222 ms: 1.09x slower                                            |
| regex_compile  | 141 ms                                                 | 165 ms: 1.16x slower                                            |
| Geometric mean | (ref)                                                  | 1.09x slower                                                    |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231028-linux-x86_64-gvanrossum-mix_tiers-3.13.0a1+-e0e60ce |
|----------------------|:------------------------------------------------------:|:---------------------------------------------------------------:|
| json_dumps           | 13.5 ms                                                | 10.5 ms: 1.28x faster                                           |
| pickle_dict          | 34.8 us                                                | 32.6 us: 1.07x faster                                           |
| json_loads           | 29.4 us                                                | 27.7 us: 1.06x faster                                           |
| xml_etree_parse      | 163 ms                                                 | 158 ms: 1.03x faster                                            |
| pickle_pure_python   | 319 us                                                 | 311 us: 1.03x faster                                            |
| unpickle_pure_python | 241 us                                                 | 239 us: 1.01x faster                                            |
| pickle               | 11.1 us                                                | 11.0 us: 1.00x faster                                           |
| xml_etree_iterparse  | 109 ms                                                 | 111 ms: 1.02x slower                                            |
| unpickle_list        | 5.22 us                                                | 5.34 us: 1.02x slower                                           |
| pickle_list          | 4.65 us                                                | 4.87 us: 1.05x slower                                           |
| xml_etree_process    | 56.5 ms                                                | 60.2 ms: 1.06x slower                                           |
| tomli_loads          | 2.31 sec                                               | 2.48 sec: 1.07x slower                                          |
| unpickle             | 13.9 us                                                | 15.0 us: 1.08x slower                                           |
| xml_etree_generate   | 80.4 ms                                                | 88.3 ms: 1.10x slower                                           |
| Geometric mean       | (ref)                                                  | 1.00x faster                                                    |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231028-linux-x86_64-gvanrossum-mix_tiers-3.13.0a1+-e0e60ce |
|------------------------|:------------------------------------------------------:|:---------------------------------------------------------------:|
| python_startup         | 8.69 ms                                                | 10.3 ms: 1.19x slower                                           |
| python_startup_no_site | 6.09 ms                                                | 9.01 ms: 1.48x slower                                           |
| Geometric mean         | (ref)                                                  | 1.33x slower                                                    |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231028-linux-x86_64-gvanrossum-mix_tiers-3.13.0a1+-e0e60ce |
|-----------|:------------------------------------------------------:|:---------------------------------------------------------------:|
| mako      | 10.8 ms                                                | 13.8 ms: 1.27x slower                                           |

All benchmarks:
===============

| Benchmark                  | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231028-linux-x86_64-gvanrossum-mix_tiers-3.13.0a1+-e0e60ce |
|----------------------------|:------------------------------------------------------:|:---------------------------------------------------------------:|
| typing_runtime_protocols   | 521 us                                                 | 161 us: 3.24x faster                                            |
| generators                 | 76.5 ms                                                | 32.8 ms: 2.33x faster                                           |
| asyncio_tcp                | 887 ms                                                 | 482 ms: 1.84x faster                                            |
| asyncio_tcp_ssl            | 3.13 sec                                               | 1.79 sec: 1.75x faster                                          |
| json_dumps                 | 13.5 ms                                                | 10.5 ms: 1.28x faster                                           |
| mypy2                      | 427 ms                                                 | 358 ms: 1.19x faster                                            |
| async_tree_none            | 532 ms                                                 | 448 ms: 1.19x faster                                            |
| coroutines                 | 26.1 ms                                                | 23.0 ms: 1.14x faster                                           |
| async_tree_memoization     | 640 ms                                                 | 577 ms: 1.11x faster                                            |
| async_tree_io              | 1.31 sec                                               | 1.20 sec: 1.09x faster                                          |
| sympy_sum                  | 170 ms                                                 | 157 ms: 1.09x faster                                            |
| sqlglot_parse              | 1.43 ms                                                | 1.34 ms: 1.07x faster                                           |
| pickle_dict                | 34.8 us                                                | 32.6 us: 1.07x faster                                           |
| richards_super             | 61.2 ms                                                | 57.5 ms: 1.06x faster                                           |
| comprehensions             | 23.6 us                                                | 22.1 us: 1.06x faster                                           |
| json_loads                 | 29.4 us                                                | 27.7 us: 1.06x faster                                           |
| async_tree_none_tg         | 490 ms                                                 | 465 ms: 1.05x faster                                            |
| sqlglot_transpile          | 1.75 ms                                                | 1.67 ms: 1.05x faster                                           |
| async_tree_io_tg           | 1.30 sec                                               | 1.25 sec: 1.04x faster                                          |
| async_tree_cpu_io_mixed    | 750 ms                                                 | 718 ms: 1.04x faster                                            |
| mdp                        | 2.79 sec                                               | 2.68 sec: 1.04x faster                                          |
| sqlglot_normalize          | 112 ms                                                 | 108 ms: 1.04x faster                                            |
| sympy_str                  | 299 ms                                                 | 289 ms: 1.03x faster                                            |
| xml_etree_parse            | 163 ms                                                 | 158 ms: 1.03x faster                                            |
| pickle_pure_python         | 319 us                                                 | 311 us: 1.03x faster                                            |
| async_tree_memoization_tg  | 627 ms                                                 | 613 ms: 1.02x faster                                            |
| async_tree_cpu_io_mixed_tg | 764 ms                                                 | 750 ms: 1.02x faster                                            |
| pidigits                   | 190 ms                                                 | 188 ms: 1.01x faster                                            |
| create_gc_cycles           | 1.48 ms                                                | 1.46 ms: 1.01x faster                                           |
| sympy_expand               | 490 ms                                                 | 486 ms: 1.01x faster                                            |
| asyncio_websockets         | 556 ms                                                 | 552 ms: 1.01x faster                                            |
| unpickle_pure_python       | 241 us                                                 | 239 us: 1.01x faster                                            |
| pickle                     | 11.1 us                                                | 11.0 us: 1.00x faster                                           |
| sqlglot_optimize           | 55.2 ms                                                | 55.3 ms: 1.00x slower                                           |
| deepcopy                   | 360 us                                                 | 363 us: 1.01x slower                                            |
| pycparser                  | 1.20 sec                                               | 1.21 sec: 1.01x slower                                          |
| deepcopy_reduce            | 3.14 us                                                | 3.17 us: 1.01x slower                                           |
| logging_silent             | 108 ns                                                 | 110 ns: 1.01x slower                                            |
| sympy_integrate            | 21.4 ms                                                | 21.6 ms: 1.01x slower                                           |
| xml_etree_iterparse        | 109 ms                                                 | 111 ms: 1.02x slower                                            |
| bench_thread_pool          | 833 us                                                 | 850 us: 1.02x slower                                            |
| unpickle_list              | 5.22 us                                                | 5.34 us: 1.02x slower                                           |
| raytrace                   | 306 ms                                                 | 313 ms: 1.02x slower                                            |
| docutils                   | 2.69 sec                                               | 2.76 sec: 1.03x slower                                          |
| logging_simple             | 6.24 us                                                | 6.44 us: 1.03x slower                                           |
| richards                   | 48.9 ms                                                | 50.6 ms: 1.03x slower                                           |
| regex_effbot               | 3.45 ms                                                | 3.58 ms: 1.04x slower                                           |
| gc_traversal               | 3.90 ms                                                | 4.07 ms: 1.04x slower                                           |
| tornado_http               | 97.7 ms                                                | 102 ms: 1.05x slower                                            |
| pickle_list                | 4.65 us                                                | 4.87 us: 1.05x slower                                           |
| chaos                      | 71.4 ms                                                | 75.7 ms: 1.06x slower                                           |
| meteor_contest             | 109 ms                                                 | 116 ms: 1.06x slower                                            |
| logging_format             | 6.83 us                                                | 7.25 us: 1.06x slower                                           |
| scimark_monte_carlo        | 71.8 ms                                                | 76.2 ms: 1.06x slower                                           |
| scimark_sor                | 121 ms                                                 | 129 ms: 1.06x slower                                            |
| xml_etree_process          | 56.5 ms                                                | 60.2 ms: 1.06x slower                                           |
| scimark_lu                 | 112 ms                                                 | 120 ms: 1.07x slower                                            |
| tomli_loads                | 2.31 sec                                               | 2.48 sec: 1.07x slower                                          |
| regex_v8                   | 22.9 ms                                                | 24.6 ms: 1.07x slower                                           |
| dulwich_log                | 64.9 ms                                                | 69.8 ms: 1.07x slower                                           |
| pathlib                    | 18.5 ms                                                | 20.0 ms: 1.08x slower                                           |
| unpickle                   | 13.9 us                                                | 15.0 us: 1.08x slower                                           |
| regex_dna                  | 204 ms                                                 | 222 ms: 1.09x slower                                            |
| 2to3                       | 266 ms                                                 | 290 ms: 1.09x slower                                            |
| deepcopy_memo              | 38.9 us                                                | 42.6 us: 1.10x slower                                           |
| crypto_pyaes               | 77.5 ms                                                | 84.9 ms: 1.10x slower                                           |
| xml_etree_generate         | 80.4 ms                                                | 88.3 ms: 1.10x slower                                           |
| sqlite_synth               | 2.58 us                                                | 2.83 us: 1.10x slower                                           |
| chameleon                  | 6.86 ms                                                | 7.56 ms: 1.10x slower                                           |
| pprint_safe_repr           | 743 ms                                                 | 820 ms: 1.10x slower                                            |
| fannkuch                   | 410 ms                                                 | 453 ms: 1.11x slower                                            |
| pprint_pformat             | 1.53 sec                                               | 1.69 sec: 1.11x slower                                          |
| spectral_norm              | 105 ms                                                 | 117 ms: 1.11x slower                                            |
| nqueens                    | 86.8 ms                                                | 99.1 ms: 1.14x slower                                           |
| unpack_sequence            | 43.3 ns                                                | 49.6 ns: 1.15x slower                                           |
| go                         | 143 ms                                                 | 165 ms: 1.16x slower                                            |
| coverage                   | 81.2 ms                                                | 94.3 ms: 1.16x slower                                           |
| regex_compile              | 141 ms                                                 | 165 ms: 1.16x slower                                            |
| python_startup             | 8.69 ms                                                | 10.3 ms: 1.19x slower                                           |
| float                      | 78.9 ms                                                | 95.1 ms: 1.21x slower                                           |
| pyflate                    | 426 ms                                                 | 520 ms: 1.22x slower                                            |
| scimark_sparse_mat_mult    | 4.80 ms                                                | 5.92 ms: 1.23x slower                                           |
| scimark_fft                | 342 ms                                                 | 424 ms: 1.24x slower                                            |
| deltablue                  | 3.80 ms                                                | 4.73 ms: 1.24x slower                                           |
| async_generators           | 375 ms                                                 | 472 ms: 1.26x slower                                            |
| mako                       | 10.8 ms                                                | 13.8 ms: 1.27x slower                                           |
| nbody                      | 91.6 ms                                                | 118 ms: 1.28x slower                                            |
| telco                      | 6.72 ms                                                | 8.65 ms: 1.29x slower                                           |
| hexiom                     | 6.74 ms                                                | 8.96 ms: 1.33x slower                                           |
| python_startup_no_site     | 6.09 ms                                                | 9.01 ms: 1.48x slower                                           |
| Geometric mean             | (ref)                                                  | 1.01x slower                                                    |

Benchmark hidden because not significant (2): json, bench_mp_pool
Ignored benchmarks (13) of results/bm-20221024-3.11.0-deaf509/bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift


# HPT report

- Reliability score: 98.21% likely to be slow
- 90% likely to have a slowdown of 1.01x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
