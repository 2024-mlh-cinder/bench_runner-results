
# Results vs. 3.11.0

- fork: gvanrossum
- ref: mix_tiers
- machine: linux-x86_64
- commit hash: d805312
- commit date: 2023-10-28
- overall geometric mean: 1.05x faster
- HPT reliability: 98.74%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231028-linux-x86_64-gvanrossum-mix_tiers-3.13.0a1+-d805312 |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------:|
| 2to3           | 266 ms                                                 | 267 ms: 1.00x slower                                            |
| chameleon      | 6.86 ms                                                | 7.00 ms: 1.02x slower                                           |
| docutils       | 2.69 sec                                               | 2.66 sec: 1.01x faster                                          |
| tornado_http   | 97.7 ms                                                | 95.8 ms: 1.02x faster                                           |
| Geometric mean | (ref)                                                  | 1.00x faster                                                    |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231028-linux-x86_64-gvanrossum-mix_tiers-3.13.0a1+-d805312 |
|----------------------------|:------------------------------------------------------:|:---------------------------------------------------------------:|
| async_tree_none            | 532 ms                                                 | 439 ms: 1.21x faster                                            |
| async_tree_memoization     | 640 ms                                                 | 565 ms: 1.13x faster                                            |
| async_tree_io              | 1.31 sec                                               | 1.19 sec: 1.10x faster                                          |
| async_tree_none_tg         | 490 ms                                                 | 459 ms: 1.07x faster                                            |
| async_tree_io_tg           | 1.30 sec                                               | 1.23 sec: 1.06x faster                                          |
| async_tree_cpu_io_mixed    | 750 ms                                                 | 710 ms: 1.06x faster                                            |
| async_tree_memoization_tg  | 627 ms                                                 | 596 ms: 1.05x faster                                            |
| async_tree_cpu_io_mixed_tg | 764 ms                                                 | 740 ms: 1.03x faster                                            |
| Geometric mean             | (ref)                                                  | 1.09x faster                                                    |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231028-linux-x86_64-gvanrossum-mix_tiers-3.13.0a1+-d805312 |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------:|
| nbody          | 91.6 ms                                                | 92.8 ms: 1.01x slower                                           |
| pidigits       | 190 ms                                                 | 195 ms: 1.02x slower                                            |
| float          | 78.9 ms                                                | 82.0 ms: 1.04x slower                                           |
| Geometric mean | (ref)                                                  | 1.03x slower                                                    |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231028-linux-x86_64-gvanrossum-mix_tiers-3.13.0a1+-d805312 |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------:|
| regex_compile  | 141 ms                                                 | 139 ms: 1.02x faster                                            |
| regex_dna      | 204 ms                                                 | 217 ms: 1.06x slower                                            |
| regex_effbot   | 3.45 ms                                                | 3.76 ms: 1.09x slower                                           |
| regex_v8       | 22.9 ms                                                | 25.4 ms: 1.11x slower                                           |
| Geometric mean | (ref)                                                  | 1.06x slower                                                    |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231028-linux-x86_64-gvanrossum-mix_tiers-3.13.0a1+-d805312 |
|----------------------|:------------------------------------------------------:|:---------------------------------------------------------------:|
| json_dumps           | 13.5 ms                                                | 10.5 ms: 1.28x faster                                           |
| unpickle_pure_python | 241 us                                                 | 221 us: 1.09x faster                                            |
| tomli_loads          | 2.31 sec                                               | 2.15 sec: 1.08x faster                                          |
| json_loads           | 29.4 us                                                | 27.7 us: 1.06x faster                                           |
| pickle_pure_python   | 319 us                                                 | 305 us: 1.05x faster                                            |
| pickle_dict          | 34.8 us                                                | 33.4 us: 1.04x faster                                           |
| xml_etree_parse      | 163 ms                                                 | 158 ms: 1.03x faster                                            |
| xml_etree_iterparse  | 109 ms                                                 | 106 ms: 1.02x faster                                            |
| unpickle_list        | 5.22 us                                                | 5.11 us: 1.02x faster                                           |
| pickle               | 11.1 us                                                | 11.3 us: 1.02x slower                                           |
| unpickle             | 13.9 us                                                | 14.5 us: 1.05x slower                                           |
| xml_etree_process    | 56.5 ms                                                | 59.6 ms: 1.05x slower                                           |
| pickle_list          | 4.65 us                                                | 4.99 us: 1.07x slower                                           |
| xml_etree_generate   | 80.4 ms                                                | 86.7 ms: 1.08x slower                                           |
| Geometric mean       | (ref)                                                  | 1.03x faster                                                    |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231028-linux-x86_64-gvanrossum-mix_tiers-3.13.0a1+-d805312 |
|------------------------|:------------------------------------------------------:|:---------------------------------------------------------------:|
| python_startup         | 8.69 ms                                                | 10.3 ms: 1.18x slower                                           |
| python_startup_no_site | 6.09 ms                                                | 8.96 ms: 1.47x slower                                           |
| Geometric mean         | (ref)                                                  | 1.32x slower                                                    |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231028-linux-x86_64-gvanrossum-mix_tiers-3.13.0a1+-d805312 |
|-----------|:------------------------------------------------------:|:---------------------------------------------------------------:|
| mako      | 10.8 ms                                                | 11.4 ms: 1.05x slower                                           |

All benchmarks:
===============

| Benchmark                  | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231028-linux-x86_64-gvanrossum-mix_tiers-3.13.0a1+-d805312 |
|----------------------------|:------------------------------------------------------:|:---------------------------------------------------------------:|
| typing_runtime_protocols   | 521 us                                                 | 156 us: 3.35x faster                                            |
| generators                 | 76.5 ms                                                | 29.7 ms: 2.57x faster                                           |
| asyncio_tcp                | 887 ms                                                 | 477 ms: 1.86x faster                                            |
| asyncio_tcp_ssl            | 3.13 sec                                               | 1.78 sec: 1.75x faster                                          |
| comprehensions             | 23.6 us                                                | 16.8 us: 1.40x faster                                           |
| json_dumps                 | 13.5 ms                                                | 10.5 ms: 1.28x faster                                           |
| mypy2                      | 427 ms                                                 | 341 ms: 1.25x faster                                            |
| async_tree_none            | 532 ms                                                 | 439 ms: 1.21x faster                                            |
| coroutines                 | 26.1 ms                                                | 22.5 ms: 1.16x faster                                           |
| chaos                      | 71.4 ms                                                | 61.9 ms: 1.15x faster                                           |
| sympy_sum                  | 170 ms                                                 | 148 ms: 1.15x faster                                            |
| async_tree_memoization     | 640 ms                                                 | 565 ms: 1.13x faster                                            |
| deltablue                  | 3.80 ms                                                | 3.36 ms: 1.13x faster                                           |
| sqlglot_parse              | 1.43 ms                                                | 1.28 ms: 1.12x faster                                           |
| sympy_str                  | 299 ms                                                 | 267 ms: 1.12x faster                                            |
| raytrace                   | 306 ms                                                 | 275 ms: 1.12x faster                                            |
| richards_super             | 61.2 ms                                                | 55.2 ms: 1.11x faster                                           |
| async_tree_io              | 1.31 sec                                               | 1.19 sec: 1.10x faster                                          |
| mdp                        | 2.79 sec                                               | 2.53 sec: 1.10x faster                                          |
| sqlglot_transpile          | 1.75 ms                                                | 1.60 ms: 1.10x faster                                           |
| unpickle_pure_python       | 241 us                                                 | 221 us: 1.09x faster                                            |
| sympy_expand               | 490 ms                                                 | 453 ms: 1.08x faster                                            |
| tomli_loads                | 2.31 sec                                               | 2.15 sec: 1.08x faster                                          |
| sympy_integrate            | 21.4 ms                                                | 19.9 ms: 1.07x faster                                           |
| hexiom                     | 6.74 ms                                                | 6.28 ms: 1.07x faster                                           |
| nqueens                    | 86.8 ms                                                | 81.3 ms: 1.07x faster                                           |
| async_tree_none_tg         | 490 ms                                                 | 459 ms: 1.07x faster                                            |
| async_tree_io_tg           | 1.30 sec                                               | 1.23 sec: 1.06x faster                                          |
| sqlglot_normalize          | 112 ms                                                 | 106 ms: 1.06x faster                                            |
| json_loads                 | 29.4 us                                                | 27.7 us: 1.06x faster                                           |
| async_tree_cpu_io_mixed    | 750 ms                                                 | 710 ms: 1.06x faster                                            |
| crypto_pyaes               | 77.5 ms                                                | 73.3 ms: 1.06x faster                                           |
| async_tree_memoization_tg  | 627 ms                                                 | 596 ms: 1.05x faster                                            |
| logging_simple             | 6.24 us                                                | 5.95 us: 1.05x faster                                           |
| logging_format             | 6.83 us                                                | 6.52 us: 1.05x faster                                           |
| pickle_pure_python         | 319 us                                                 | 305 us: 1.05x faster                                            |
| scimark_monte_carlo        | 71.8 ms                                                | 68.9 ms: 1.04x faster                                           |
| pickle_dict                | 34.8 us                                                | 33.4 us: 1.04x faster                                           |
| async_tree_cpu_io_mixed_tg | 764 ms                                                 | 740 ms: 1.03x faster                                            |
| sqlglot_optimize           | 55.2 ms                                                | 53.5 ms: 1.03x faster                                           |
| xml_etree_parse            | 163 ms                                                 | 158 ms: 1.03x faster                                            |
| bench_thread_pool          | 833 us                                                 | 815 us: 1.02x faster                                            |
| json                       | 5.24 ms                                                | 5.12 ms: 1.02x faster                                           |
| xml_etree_iterparse        | 109 ms                                                 | 106 ms: 1.02x faster                                            |
| unpickle_list              | 5.22 us                                                | 5.11 us: 1.02x faster                                           |
| regex_compile              | 141 ms                                                 | 139 ms: 1.02x faster                                            |
| pycparser                  | 1.20 sec                                               | 1.17 sec: 1.02x faster                                          |
| tornado_http               | 97.7 ms                                                | 95.8 ms: 1.02x faster                                           |
| unpack_sequence            | 43.3 ns                                                | 42.6 ns: 1.02x faster                                           |
| logging_silent             | 108 ns                                                 | 107 ns: 1.01x faster                                            |
| docutils                   | 2.69 sec                                               | 2.66 sec: 1.01x faster                                          |
| deepcopy                   | 360 us                                                 | 357 us: 1.01x faster                                            |
| fannkuch                   | 410 ms                                                 | 407 ms: 1.01x faster                                            |
| asyncio_websockets         | 556 ms                                                 | 552 ms: 1.01x faster                                            |
| 2to3                       | 266 ms                                                 | 267 ms: 1.00x slower                                            |
| pprint_pformat             | 1.53 sec                                               | 1.54 sec: 1.01x slower                                          |
| gc_traversal               | 3.90 ms                                                | 3.94 ms: 1.01x slower                                           |
| richards                   | 48.9 ms                                                | 49.4 ms: 1.01x slower                                           |
| nbody                      | 91.6 ms                                                | 92.8 ms: 1.01x slower                                           |
| go                         | 143 ms                                                 | 145 ms: 1.01x slower                                            |
| deepcopy_reduce            | 3.14 us                                                | 3.18 us: 1.01x slower                                           |
| pickle                     | 11.1 us                                                | 11.3 us: 1.02x slower                                           |
| pprint_safe_repr           | 743 ms                                                 | 757 ms: 1.02x slower                                            |
| chameleon                  | 6.86 ms                                                | 7.00 ms: 1.02x slower                                           |
| deepcopy_memo              | 38.9 us                                                | 39.8 us: 1.02x slower                                           |
| pidigits                   | 190 ms                                                 | 195 ms: 1.02x slower                                            |
| dulwich_log                | 64.9 ms                                                | 66.7 ms: 1.03x slower                                           |
| pathlib                    | 18.5 ms                                                | 19.0 ms: 1.03x slower                                           |
| scimark_lu                 | 112 ms                                                 | 116 ms: 1.03x slower                                            |
| float                      | 78.9 ms                                                | 82.0 ms: 1.04x slower                                           |
| scimark_sparse_mat_mult    | 4.80 ms                                                | 5.03 ms: 1.05x slower                                           |
| unpickle                   | 13.9 us                                                | 14.5 us: 1.05x slower                                           |
| mako                       | 10.8 ms                                                | 11.4 ms: 1.05x slower                                           |
| xml_etree_process          | 56.5 ms                                                | 59.6 ms: 1.05x slower                                           |
| regex_dna                  | 204 ms                                                 | 217 ms: 1.06x slower                                            |
| spectral_norm              | 105 ms                                                 | 113 ms: 1.07x slower                                            |
| pickle_list                | 4.65 us                                                | 4.99 us: 1.07x slower                                           |
| xml_etree_generate         | 80.4 ms                                                | 86.7 ms: 1.08x slower                                           |
| regex_effbot               | 3.45 ms                                                | 3.76 ms: 1.09x slower                                           |
| scimark_sor                | 121 ms                                                 | 134 ms: 1.10x slower                                            |
| sqlite_synth               | 2.58 us                                                | 2.84 us: 1.10x slower                                           |
| scimark_fft                | 342 ms                                                 | 377 ms: 1.10x slower                                            |
| regex_v8                   | 22.9 ms                                                | 25.4 ms: 1.11x slower                                           |
| pyflate                    | 426 ms                                                 | 480 ms: 1.13x slower                                            |
| coverage                   | 81.2 ms                                                | 94.9 ms: 1.17x slower                                           |
| python_startup             | 8.69 ms                                                | 10.3 ms: 1.18x slower                                           |
| async_generators           | 375 ms                                                 | 460 ms: 1.22x slower                                            |
| telco                      | 6.72 ms                                                | 8.40 ms: 1.25x slower                                           |
| python_startup_no_site     | 6.09 ms                                                | 8.96 ms: 1.47x slower                                           |
| Geometric mean             | (ref)                                                  | 1.05x faster                                                    |

Benchmark hidden because not significant (3): bench_mp_pool, create_gc_cycles, meteor_contest
Ignored benchmarks (13) of results/bm-20221024-3.11.0-deaf509/bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift


# HPT report

- Reliability score: 98.74% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
