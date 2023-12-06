
# Results vs. 3.11.0

- fork: python
- ref: 9da98c0d9a7cc55c67fb
- machine: linux-x86_64
- commit hash: 9da98c0
- commit date: 2023-10-25
- overall geometric mean: 1.05x faster
- HPT reliability: 99.88%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231025-linux-x86_64-python-9da98c0d9a7cc55c67fb-3.13.0a1+-9da98c0 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| 2to3           | 266 ms                                                 | 268 ms: 1.01x slower                                                   |
| chameleon      | 6.86 ms                                                | 6.91 ms: 1.01x slower                                                  |
| docutils       | 2.69 sec                                               | 2.65 sec: 1.01x faster                                                 |
| tornado_http   | 97.7 ms                                                | 95.2 ms: 1.03x faster                                                  |
| Geometric mean | (ref)                                                  | 1.01x faster                                                           |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231025-linux-x86_64-python-9da98c0d9a7cc55c67fb-3.13.0a1+-9da98c0 |
|----------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| async_tree_none            | 532 ms                                                 | 440 ms: 1.21x faster                                                   |
| async_tree_memoization     | 640 ms                                                 | 567 ms: 1.13x faster                                                   |
| async_tree_io              | 1.31 sec                                               | 1.19 sec: 1.10x faster                                                 |
| async_tree_none_tg         | 490 ms                                                 | 456 ms: 1.07x faster                                                   |
| async_tree_io_tg           | 1.30 sec                                               | 1.23 sec: 1.06x faster                                                 |
| async_tree_memoization_tg  | 627 ms                                                 | 598 ms: 1.05x faster                                                   |
| async_tree_cpu_io_mixed    | 750 ms                                                 | 718 ms: 1.04x faster                                                   |
| async_tree_cpu_io_mixed_tg | 764 ms                                                 | 746 ms: 1.02x faster                                                   |
| Geometric mean             | (ref)                                                  | 1.08x faster                                                           |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231025-linux-x86_64-python-9da98c0d9a7cc55c67fb-3.13.0a1+-9da98c0 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| pidigits       | 190 ms                                                 | 187 ms: 1.02x faster                                                   |
| float          | 78.9 ms                                                | 81.8 ms: 1.04x slower                                                  |
| nbody          | 91.6 ms                                                | 98.1 ms: 1.07x slower                                                  |
| Geometric mean | (ref)                                                  | 1.03x slower                                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231025-linux-x86_64-python-9da98c0d9a7cc55c67fb-3.13.0a1+-9da98c0 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| regex_compile  | 141 ms                                                 | 138 ms: 1.03x faster                                                   |
| regex_dna      | 204 ms                                                 | 218 ms: 1.07x slower                                                   |
| regex_v8       | 22.9 ms                                                | 25.4 ms: 1.11x slower                                                  |
| regex_effbot   | 3.45 ms                                                | 3.84 ms: 1.11x slower                                                  |
| Geometric mean | (ref)                                                  | 1.06x slower                                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231025-linux-x86_64-python-9da98c0d9a7cc55c67fb-3.13.0a1+-9da98c0 |
|----------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| json_dumps           | 13.5 ms                                                | 10.4 ms: 1.29x faster                                                  |
| unpickle_pure_python | 241 us                                                 | 221 us: 1.09x faster                                                   |
| tomli_loads          | 2.31 sec                                               | 2.15 sec: 1.08x faster                                                 |
| json_loads           | 29.4 us                                                | 27.8 us: 1.06x faster                                                  |
| pickle_dict          | 34.8 us                                                | 33.5 us: 1.04x faster                                                  |
| pickle_pure_python   | 319 us                                                 | 308 us: 1.04x faster                                                   |
| xml_etree_iterparse  | 109 ms                                                 | 106 ms: 1.02x faster                                                   |
| xml_etree_parse      | 163 ms                                                 | 160 ms: 1.02x faster                                                   |
| unpickle_list        | 5.22 us                                                | 5.17 us: 1.01x faster                                                  |
| pickle               | 11.1 us                                                | 11.2 us: 1.01x slower                                                  |
| xml_etree_process    | 56.5 ms                                                | 59.4 ms: 1.05x slower                                                  |
| unpickle             | 13.9 us                                                | 14.8 us: 1.07x slower                                                  |
| pickle_list          | 4.65 us                                                | 4.99 us: 1.07x slower                                                  |
| xml_etree_generate   | 80.4 ms                                                | 86.5 ms: 1.08x slower                                                  |
| Geometric mean       | (ref)                                                  | 1.02x faster                                                           |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231025-linux-x86_64-python-9da98c0d9a7cc55c67fb-3.13.0a1+-9da98c0 |
|------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| python_startup_no_site | 6.09 ms                                                | 6.88 ms: 1.13x slower                                                  |
| python_startup         | 8.69 ms                                                | 10.1 ms: 1.16x slower                                                  |
| Geometric mean         | (ref)                                                  | 1.15x slower                                                           |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231025-linux-x86_64-python-9da98c0d9a7cc55c67fb-3.13.0a1+-9da98c0 |
|-----------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| mako      | 10.8 ms                                                | 11.2 ms: 1.03x slower                                                  |

All benchmarks:
===============

| Benchmark                  | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231025-linux-x86_64-python-9da98c0d9a7cc55c67fb-3.13.0a1+-9da98c0 |
|----------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| typing_runtime_protocols   | 521 us                                                 | 151 us: 3.45x faster                                                   |
| generators                 | 76.5 ms                                                | 29.6 ms: 2.58x faster                                                  |
| asyncio_tcp                | 887 ms                                                 | 484 ms: 1.83x faster                                                   |
| asyncio_tcp_ssl            | 3.13 sec                                               | 1.77 sec: 1.76x faster                                                 |
| json_dumps                 | 13.5 ms                                                | 10.4 ms: 1.29x faster                                                  |
| mypy2                      | 427 ms                                                 | 343 ms: 1.25x faster                                                   |
| async_tree_none            | 532 ms                                                 | 440 ms: 1.21x faster                                                   |
| deltablue                  | 3.80 ms                                                | 3.29 ms: 1.16x faster                                                  |
| coroutines                 | 26.1 ms                                                | 22.7 ms: 1.15x faster                                                  |
| chaos                      | 71.4 ms                                                | 62.2 ms: 1.15x faster                                                  |
| comprehensions             | 23.6 us                                                | 20.8 us: 1.13x faster                                                  |
| async_tree_memoization     | 640 ms                                                 | 567 ms: 1.13x faster                                                   |
| raytrace                   | 306 ms                                                 | 273 ms: 1.12x faster                                                   |
| richards_super             | 61.2 ms                                                | 54.6 ms: 1.12x faster                                                  |
| sqlglot_parse              | 1.43 ms                                                | 1.29 ms: 1.11x faster                                                  |
| async_tree_io              | 1.31 sec                                               | 1.19 sec: 1.10x faster                                                 |
| hexiom                     | 6.74 ms                                                | 6.15 ms: 1.10x faster                                                  |
| sympy_sum                  | 170 ms                                                 | 156 ms: 1.09x faster                                                   |
| unpickle_pure_python       | 241 us                                                 | 221 us: 1.09x faster                                                   |
| sqlglot_transpile          | 1.75 ms                                                | 1.61 ms: 1.09x faster                                                  |
| sympy_expand               | 490 ms                                                 | 453 ms: 1.08x faster                                                   |
| tomli_loads                | 2.31 sec                                               | 2.15 sec: 1.08x faster                                                 |
| async_tree_none_tg         | 490 ms                                                 | 456 ms: 1.07x faster                                                   |
| sympy_str                  | 299 ms                                                 | 279 ms: 1.07x faster                                                   |
| mdp                        | 2.79 sec                                               | 2.61 sec: 1.07x faster                                                 |
| crypto_pyaes               | 77.5 ms                                                | 72.5 ms: 1.07x faster                                                  |
| nqueens                    | 86.8 ms                                                | 81.3 ms: 1.07x faster                                                  |
| sqlglot_normalize          | 112 ms                                                 | 106 ms: 1.06x faster                                                   |
| logging_simple             | 6.24 us                                                | 5.89 us: 1.06x faster                                                  |
| json_loads                 | 29.4 us                                                | 27.8 us: 1.06x faster                                                  |
| async_tree_io_tg           | 1.30 sec                                               | 1.23 sec: 1.06x faster                                                 |
| logging_format             | 6.83 us                                                | 6.47 us: 1.06x faster                                                  |
| sympy_integrate            | 21.4 ms                                                | 20.3 ms: 1.05x faster                                                  |
| async_tree_memoization_tg  | 627 ms                                                 | 598 ms: 1.05x faster                                                   |
| async_tree_cpu_io_mixed    | 750 ms                                                 | 718 ms: 1.04x faster                                                   |
| pickle_dict                | 34.8 us                                                | 33.5 us: 1.04x faster                                                  |
| pickle_pure_python         | 319 us                                                 | 308 us: 1.04x faster                                                   |
| scimark_monte_carlo        | 71.8 ms                                                | 69.2 ms: 1.04x faster                                                  |
| sqlglot_optimize           | 55.2 ms                                                | 53.5 ms: 1.03x faster                                                  |
| gc_traversal               | 3.90 ms                                                | 3.79 ms: 1.03x faster                                                  |
| json                       | 5.24 ms                                                | 5.09 ms: 1.03x faster                                                  |
| regex_compile              | 141 ms                                                 | 138 ms: 1.03x faster                                                   |
| tornado_http               | 97.7 ms                                                | 95.2 ms: 1.03x faster                                                  |
| bench_thread_pool          | 833 us                                                 | 812 us: 1.03x faster                                                   |
| async_tree_cpu_io_mixed_tg | 764 ms                                                 | 746 ms: 1.02x faster                                                   |
| pycparser                  | 1.20 sec                                               | 1.17 sec: 1.02x faster                                                 |
| xml_etree_iterparse        | 109 ms                                                 | 106 ms: 1.02x faster                                                   |
| xml_etree_parse            | 163 ms                                                 | 160 ms: 1.02x faster                                                   |
| go                         | 143 ms                                                 | 140 ms: 1.02x faster                                                   |
| logging_silent             | 108 ns                                                 | 107 ns: 1.02x faster                                                   |
| deepcopy                   | 360 us                                                 | 354 us: 1.02x faster                                                   |
| deepcopy_memo              | 38.9 us                                                | 38.3 us: 1.02x faster                                                  |
| pidigits                   | 190 ms                                                 | 187 ms: 1.02x faster                                                   |
| docutils                   | 2.69 sec                                               | 2.65 sec: 1.01x faster                                                 |
| unpickle_list              | 5.22 us                                                | 5.17 us: 1.01x faster                                                  |
| asyncio_websockets         | 556 ms                                                 | 551 ms: 1.01x faster                                                   |
| meteor_contest             | 109 ms                                                 | 108 ms: 1.01x faster                                                   |
| deepcopy_reduce            | 3.14 us                                                | 3.12 us: 1.01x faster                                                  |
| create_gc_cycles           | 1.48 ms                                                | 1.47 ms: 1.01x faster                                                  |
| pprint_pformat             | 1.53 sec                                               | 1.52 sec: 1.00x faster                                                 |
| fannkuch                   | 410 ms                                                 | 412 ms: 1.00x slower                                                   |
| chameleon                  | 6.86 ms                                                | 6.91 ms: 1.01x slower                                                  |
| 2to3                       | 266 ms                                                 | 268 ms: 1.01x slower                                                   |
| pprint_safe_repr           | 743 ms                                                 | 751 ms: 1.01x slower                                                   |
| pickle                     | 11.1 us                                                | 11.2 us: 1.01x slower                                                  |
| scimark_lu                 | 112 ms                                                 | 115 ms: 1.02x slower                                                   |
| pathlib                    | 18.5 ms                                                | 19.0 ms: 1.03x slower                                                  |
| dulwich_log                | 64.9 ms                                                | 66.9 ms: 1.03x slower                                                  |
| unpack_sequence            | 43.3 ns                                                | 44.8 ns: 1.03x slower                                                  |
| mako                       | 10.8 ms                                                | 11.2 ms: 1.03x slower                                                  |
| scimark_sor                | 121 ms                                                 | 126 ms: 1.04x slower                                                   |
| float                      | 78.9 ms                                                | 81.8 ms: 1.04x slower                                                  |
| xml_etree_process          | 56.5 ms                                                | 59.4 ms: 1.05x slower                                                  |
| spectral_norm              | 105 ms                                                 | 112 ms: 1.06x slower                                                   |
| unpickle                   | 13.9 us                                                | 14.8 us: 1.07x slower                                                  |
| scimark_sparse_mat_mult    | 4.80 ms                                                | 5.13 ms: 1.07x slower                                                  |
| regex_dna                  | 204 ms                                                 | 218 ms: 1.07x slower                                                   |
| nbody                      | 91.6 ms                                                | 98.1 ms: 1.07x slower                                                  |
| pickle_list                | 4.65 us                                                | 4.99 us: 1.07x slower                                                  |
| xml_etree_generate         | 80.4 ms                                                | 86.5 ms: 1.08x slower                                                  |
| sqlite_synth               | 2.58 us                                                | 2.81 us: 1.09x slower                                                  |
| pyflate                    | 426 ms                                                 | 471 ms: 1.11x slower                                                   |
| regex_v8                   | 22.9 ms                                                | 25.4 ms: 1.11x slower                                                  |
| regex_effbot               | 3.45 ms                                                | 3.84 ms: 1.11x slower                                                  |
| scimark_fft                | 342 ms                                                 | 384 ms: 1.12x slower                                                   |
| python_startup_no_site     | 6.09 ms                                                | 6.88 ms: 1.13x slower                                                  |
| python_startup             | 8.69 ms                                                | 10.1 ms: 1.16x slower                                                  |
| coverage                   | 81.2 ms                                                | 94.9 ms: 1.17x slower                                                  |
| async_generators           | 375 ms                                                 | 456 ms: 1.22x slower                                                   |
| telco                      | 6.72 ms                                                | 8.28 ms: 1.23x slower                                                  |
| Geometric mean             | (ref)                                                  | 1.05x faster                                                           |

Benchmark hidden because not significant (2): bench_mp_pool, richards
Ignored benchmarks (13) of results/bm-20221024-3.11.0-deaf509/bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift


# HPT report

- Reliability score: 99.88% likely to be faster
- 90% likely to have a speedup of 1.01x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
