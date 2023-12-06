
# Results vs. 3.11.0

- fork: gvanrossum
- ref: uops_forever
- machine: linux-x86_64
- commit hash: ab9b54e
- commit date: 2023-10-30
- overall geometric mean: 1.01x slower
- HPT reliability: 99.47%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231030-linux-x86_64-gvanrossum-uops_forever-3.13.0a1+-ab9b54e |
|----------------|:------------------------------------------------------:|:------------------------------------------------------------------:|
| 2to3           | 266 ms                                                 | 290 ms: 1.09x slower                                               |
| chameleon      | 6.86 ms                                                | 7.46 ms: 1.09x slower                                              |
| docutils       | 2.69 sec                                               | 2.76 sec: 1.03x slower                                             |
| tornado_http   | 97.7 ms                                                | 102 ms: 1.05x slower                                               |
| Geometric mean | (ref)                                                  | 1.06x slower                                                       |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231030-linux-x86_64-gvanrossum-uops_forever-3.13.0a1+-ab9b54e |
|----------------------------|:------------------------------------------------------:|:------------------------------------------------------------------:|
| async_tree_none            | 532 ms                                                 | 457 ms: 1.16x faster                                               |
| async_tree_memoization     | 640 ms                                                 | 585 ms: 1.09x faster                                               |
| async_tree_io              | 1.31 sec                                               | 1.21 sec: 1.08x faster                                             |
| async_tree_io_tg           | 1.30 sec                                               | 1.25 sec: 1.04x faster                                             |
| async_tree_none_tg         | 490 ms                                                 | 471 ms: 1.04x faster                                               |
| async_tree_cpu_io_mixed    | 750 ms                                                 | 725 ms: 1.03x faster                                               |
| async_tree_cpu_io_mixed_tg | 764 ms                                                 | 751 ms: 1.02x faster                                               |
| Geometric mean             | (ref)                                                  | 1.06x faster                                                       |

Benchmark hidden because not significant (1): async_tree_memoization_tg

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231030-linux-x86_64-gvanrossum-uops_forever-3.13.0a1+-ab9b54e |
|----------------|:------------------------------------------------------:|:------------------------------------------------------------------:|
| pidigits       | 190 ms                                                 | 196 ms: 1.03x slower                                               |
| nbody          | 91.6 ms                                                | 110 ms: 1.20x slower                                               |
| float          | 78.9 ms                                                | 95.9 ms: 1.21x slower                                              |
| Geometric mean | (ref)                                                  | 1.15x slower                                                       |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231030-linux-x86_64-gvanrossum-uops_forever-3.13.0a1+-ab9b54e |
|----------------|:------------------------------------------------------:|:------------------------------------------------------------------:|
| regex_effbot   | 3.45 ms                                                | 3.58 ms: 1.04x slower                                              |
| regex_dna      | 204 ms                                                 | 215 ms: 1.06x slower                                               |
| regex_v8       | 22.9 ms                                                | 25.9 ms: 1.13x slower                                              |
| regex_compile  | 141 ms                                                 | 162 ms: 1.14x slower                                               |
| Geometric mean | (ref)                                                  | 1.09x slower                                                       |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231030-linux-x86_64-gvanrossum-uops_forever-3.13.0a1+-ab9b54e |
|----------------------|:------------------------------------------------------:|:------------------------------------------------------------------:|
| json_dumps           | 13.5 ms                                                | 10.6 ms: 1.27x faster                                              |
| json_loads           | 29.4 us                                                | 27.6 us: 1.07x faster                                              |
| pickle_pure_python   | 319 us                                                 | 312 us: 1.02x faster                                               |
| xml_etree_parse      | 163 ms                                                 | 159 ms: 1.02x faster                                               |
| unpickle_list        | 5.22 us                                                | 5.14 us: 1.01x faster                                              |
| unpickle_pure_python | 241 us                                                 | 240 us: 1.00x faster                                               |
| pickle_dict          | 34.8 us                                                | 35.1 us: 1.01x slower                                              |
| pickle               | 11.1 us                                                | 11.2 us: 1.01x slower                                              |
| xml_etree_iterparse  | 109 ms                                                 | 111 ms: 1.03x slower                                               |
| tomli_loads          | 2.31 sec                                               | 2.46 sec: 1.06x slower                                             |
| xml_etree_process    | 56.5 ms                                                | 60.0 ms: 1.06x slower                                              |
| unpickle             | 13.9 us                                                | 14.8 us: 1.07x slower                                              |
| pickle_list          | 4.65 us                                                | 5.02 us: 1.08x slower                                              |
| xml_etree_generate   | 80.4 ms                                                | 87.7 ms: 1.09x slower                                              |
| Geometric mean       | (ref)                                                  | 1.00x slower                                                       |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231030-linux-x86_64-gvanrossum-uops_forever-3.13.0a1+-ab9b54e |
|------------------------|:------------------------------------------------------:|:------------------------------------------------------------------:|
| python_startup         | 8.69 ms                                                | 10.3 ms: 1.19x slower                                              |
| python_startup_no_site | 6.09 ms                                                | 9.00 ms: 1.48x slower                                              |
| Geometric mean         | (ref)                                                  | 1.33x slower                                                       |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231030-linux-x86_64-gvanrossum-uops_forever-3.13.0a1+-ab9b54e |
|-----------|:------------------------------------------------------:|:------------------------------------------------------------------:|
| mako      | 10.8 ms                                                | 13.2 ms: 1.22x slower                                              |

All benchmarks:
===============

| Benchmark                  | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231030-linux-x86_64-gvanrossum-uops_forever-3.13.0a1+-ab9b54e |
|----------------------------|:------------------------------------------------------:|:------------------------------------------------------------------:|
| typing_runtime_protocols   | 521 us                                                 | 159 us: 3.28x faster                                               |
| generators                 | 76.5 ms                                                | 30.4 ms: 2.51x faster                                              |
| asyncio_tcp                | 887 ms                                                 | 477 ms: 1.86x faster                                               |
| asyncio_tcp_ssl            | 3.13 sec                                               | 1.80 sec: 1.74x faster                                             |
| json_dumps                 | 13.5 ms                                                | 10.6 ms: 1.27x faster                                              |
| mypy2                      | 427 ms                                                 | 357 ms: 1.20x faster                                               |
| async_tree_none            | 532 ms                                                 | 457 ms: 1.16x faster                                               |
| coroutines                 | 26.1 ms                                                | 22.8 ms: 1.15x faster                                              |
| gc_traversal               | 3.90 ms                                                | 3.50 ms: 1.11x faster                                              |
| async_tree_memoization     | 640 ms                                                 | 585 ms: 1.09x faster                                               |
| async_tree_io              | 1.31 sec                                               | 1.21 sec: 1.08x faster                                             |
| sympy_sum                  | 170 ms                                                 | 157 ms: 1.08x faster                                               |
| richards_super             | 61.2 ms                                                | 57.0 ms: 1.07x faster                                              |
| sqlglot_parse              | 1.43 ms                                                | 1.34 ms: 1.07x faster                                              |
| json_loads                 | 29.4 us                                                | 27.6 us: 1.07x faster                                              |
| comprehensions             | 23.6 us                                                | 22.2 us: 1.06x faster                                              |
| sqlglot_transpile          | 1.75 ms                                                | 1.67 ms: 1.05x faster                                              |
| sqlglot_normalize          | 112 ms                                                 | 108 ms: 1.04x faster                                               |
| async_tree_io_tg           | 1.30 sec                                               | 1.25 sec: 1.04x faster                                             |
| sympy_str                  | 299 ms                                                 | 287 ms: 1.04x faster                                               |
| async_tree_none_tg         | 490 ms                                                 | 471 ms: 1.04x faster                                               |
| async_tree_cpu_io_mixed    | 750 ms                                                 | 725 ms: 1.03x faster                                               |
| pickle_pure_python         | 319 us                                                 | 312 us: 1.02x faster                                               |
| xml_etree_parse            | 163 ms                                                 | 159 ms: 1.02x faster                                               |
| logging_silent             | 108 ns                                                 | 106 ns: 1.02x faster                                               |
| json                       | 5.24 ms                                                | 5.14 ms: 1.02x faster                                              |
| create_gc_cycles           | 1.48 ms                                                | 1.45 ms: 1.02x faster                                              |
| async_tree_cpu_io_mixed_tg | 764 ms                                                 | 751 ms: 1.02x faster                                               |
| unpickle_list              | 5.22 us                                                | 5.14 us: 1.01x faster                                              |
| sympy_expand               | 490 ms                                                 | 484 ms: 1.01x faster                                               |
| asyncio_websockets         | 556 ms                                                 | 552 ms: 1.01x faster                                               |
| unpickle_pure_python       | 241 us                                                 | 240 us: 1.00x faster                                               |
| deepcopy_reduce            | 3.14 us                                                | 3.15 us: 1.01x slower                                              |
| sympy_integrate            | 21.4 ms                                                | 21.5 ms: 1.01x slower                                              |
| raytrace                   | 306 ms                                                 | 309 ms: 1.01x slower                                               |
| pickle_dict                | 34.8 us                                                | 35.1 us: 1.01x slower                                              |
| pickle                     | 11.1 us                                                | 11.2 us: 1.01x slower                                              |
| logging_simple             | 6.24 us                                                | 6.35 us: 1.02x slower                                              |
| bench_thread_pool          | 833 us                                                 | 849 us: 1.02x slower                                               |
| xml_etree_iterparse        | 109 ms                                                 | 111 ms: 1.03x slower                                               |
| docutils                   | 2.69 sec                                               | 2.76 sec: 1.03x slower                                             |
| pidigits                   | 190 ms                                                 | 196 ms: 1.03x slower                                               |
| richards                   | 48.9 ms                                                | 50.5 ms: 1.03x slower                                              |
| mdp                        | 2.79 sec                                               | 2.88 sec: 1.03x slower                                             |
| regex_effbot               | 3.45 ms                                                | 3.58 ms: 1.04x slower                                              |
| unpack_sequence            | 43.3 ns                                                | 45.0 ns: 1.04x slower                                              |
| tornado_http               | 97.7 ms                                                | 102 ms: 1.05x slower                                               |
| pycparser                  | 1.20 sec                                               | 1.26 sec: 1.05x slower                                             |
| chaos                      | 71.4 ms                                                | 75.0 ms: 1.05x slower                                              |
| scimark_sor                | 121 ms                                                 | 128 ms: 1.05x slower                                               |
| regex_dna                  | 204 ms                                                 | 215 ms: 1.06x slower                                               |
| meteor_contest             | 109 ms                                                 | 115 ms: 1.06x slower                                               |
| tomli_loads                | 2.31 sec                                               | 2.46 sec: 1.06x slower                                             |
| xml_etree_process          | 56.5 ms                                                | 60.0 ms: 1.06x slower                                              |
| logging_format             | 6.83 us                                                | 7.29 us: 1.07x slower                                              |
| pathlib                    | 18.5 ms                                                | 19.8 ms: 1.07x slower                                              |
| unpickle                   | 13.9 us                                                | 14.8 us: 1.07x slower                                              |
| dulwich_log                | 64.9 ms                                                | 69.7 ms: 1.07x slower                                              |
| scimark_monte_carlo        | 71.8 ms                                                | 77.1 ms: 1.07x slower                                              |
| scimark_lu                 | 112 ms                                                 | 121 ms: 1.08x slower                                               |
| pickle_list                | 4.65 us                                                | 5.02 us: 1.08x slower                                              |
| crypto_pyaes               | 77.5 ms                                                | 83.9 ms: 1.08x slower                                              |
| chameleon                  | 6.86 ms                                                | 7.46 ms: 1.09x slower                                              |
| xml_etree_generate         | 80.4 ms                                                | 87.7 ms: 1.09x slower                                              |
| pprint_safe_repr           | 743 ms                                                 | 810 ms: 1.09x slower                                               |
| 2to3                       | 266 ms                                                 | 290 ms: 1.09x slower                                               |
| pprint_pformat             | 1.53 sec                                               | 1.67 sec: 1.09x slower                                             |
| deepcopy_memo              | 38.9 us                                                | 42.8 us: 1.10x slower                                              |
| spectral_norm              | 105 ms                                                 | 116 ms: 1.10x slower                                               |
| sqlite_synth               | 2.58 us                                                | 2.86 us: 1.11x slower                                              |
| fannkuch                   | 410 ms                                                 | 455 ms: 1.11x slower                                               |
| regex_v8                   | 22.9 ms                                                | 25.9 ms: 1.13x slower                                              |
| nqueens                    | 86.8 ms                                                | 98.3 ms: 1.13x slower                                              |
| regex_compile              | 141 ms                                                 | 162 ms: 1.14x slower                                               |
| coverage                   | 81.2 ms                                                | 94.2 ms: 1.16x slower                                              |
| go                         | 143 ms                                                 | 166 ms: 1.16x slower                                               |
| python_startup             | 8.69 ms                                                | 10.3 ms: 1.19x slower                                              |
| nbody                      | 91.6 ms                                                | 110 ms: 1.20x slower                                               |
| deltablue                  | 3.80 ms                                                | 4.61 ms: 1.21x slower                                              |
| float                      | 78.9 ms                                                | 95.9 ms: 1.21x slower                                              |
| mako                       | 10.8 ms                                                | 13.2 ms: 1.22x slower                                              |
| scimark_sparse_mat_mult    | 4.80 ms                                                | 5.88 ms: 1.22x slower                                              |
| pyflate                    | 426 ms                                                 | 528 ms: 1.24x slower                                               |
| telco                      | 6.72 ms                                                | 8.53 ms: 1.27x slower                                              |
| async_generators           | 375 ms                                                 | 479 ms: 1.28x slower                                               |
| scimark_fft                | 342 ms                                                 | 439 ms: 1.28x slower                                               |
| hexiom                     | 6.74 ms                                                | 8.84 ms: 1.31x slower                                              |
| python_startup_no_site     | 6.09 ms                                                | 9.00 ms: 1.48x slower                                              |
| Geometric mean             | (ref)                                                  | 1.01x slower                                                       |

Benchmark hidden because not significant (4): async_tree_memoization_tg, deepcopy, bench_mp_pool, sqlglot_optimize
Ignored benchmarks (13) of results/bm-20221024-3.11.0-deaf509/bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift


# HPT report

- Reliability score: 99.47% likely to be slow
- 90% likely to have a slowdown of 1.01x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
