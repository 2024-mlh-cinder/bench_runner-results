
# Results vs. 3.11.0

- fork: gvanrossum
- ref: for_iter_uop
- machine: linux-x86_64
- commit hash: 5c5d8bd
- commit date: 2023-11-15
- overall geometric mean: 1.05x slower \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.01x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231115-linux-x86_64-gvanrossum-for_iter_uop-3.13.0a1+-5c5d8bd |
|----------------|:------------------------------------------------------:|:------------------------------------------------------------------:|
| 2to3           | 266 ms                                                 | 291 ms: 1.09x slower                                               |
| chameleon      | 6.86 ms                                                | 7.65 ms: 1.12x slower                                              |
| docutils       | 2.69 sec                                               | 2.75 sec: 1.02x slower                                             |
| tornado_http   | 97.7 ms                                                | 100 ms: 1.02x slower                                               |
| Geometric mean | (ref)                                                  | 1.06x slower                                                       |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                 | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231115-linux-x86_64-gvanrossum-for_iter_uop-3.13.0a1+-5c5d8bd |
|---------------------------|:------------------------------------------------------:|:------------------------------------------------------------------:|
| async_tree_none           | 532 ms                                                 | 465 ms: 1.15x faster                                               |
| async_tree_memoization    | 640 ms                                                 | 596 ms: 1.07x faster                                               |
| async_tree_io             | 1.31 sec                                               | 1.24 sec: 1.06x faster                                             |
| async_tree_io_tg          | 1.30 sec                                               | 1.26 sec: 1.03x faster                                             |
| async_tree_memoization_tg | 627 ms                                                 | 610 ms: 1.03x faster                                               |
| async_tree_none_tg        | 490 ms                                                 | 481 ms: 1.02x faster                                               |
| async_tree_cpu_io_mixed   | 750 ms                                                 | 742 ms: 1.01x faster                                               |
| Geometric mean            | (ref)                                                  | 1.04x faster                                                       |

Benchmark hidden because not significant (1): async_tree_cpu_io_mixed_tg

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231115-linux-x86_64-gvanrossum-for_iter_uop-3.13.0a1+-5c5d8bd |
|----------------|:------------------------------------------------------:|:------------------------------------------------------------------:|
| pidigits       | 190 ms                                                 | 189 ms: 1.01x faster                                               |
| nbody          | 91.6 ms                                                | 121 ms: 1.32x slower                                               |
| float          | 78.9 ms                                                | 109 ms: 1.38x slower                                               |
| Geometric mean | (ref)                                                  | 1.22x slower                                                       |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231115-linux-x86_64-gvanrossum-for_iter_uop-3.13.0a1+-5c5d8bd |
|----------------|:------------------------------------------------------:|:------------------------------------------------------------------:|
| regex_effbot   | 3.45 ms                                                | 3.65 ms: 1.06x slower                                              |
| regex_dna      | 204 ms                                                 | 219 ms: 1.07x slower                                               |
| regex_v8       | 22.9 ms                                                | 26.2 ms: 1.15x slower                                              |
| regex_compile  | 141 ms                                                 | 167 ms: 1.18x slower                                               |
| Geometric mean | (ref)                                                  | 1.11x slower                                                       |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231115-linux-x86_64-gvanrossum-for_iter_uop-3.13.0a1+-5c5d8bd |
|----------------------|:------------------------------------------------------:|:------------------------------------------------------------------:|
| json_dumps           | 13.5 ms                                                | 10.7 ms: 1.26x faster                                              |
| pickle_dict          | 34.8 us                                                | 33.2 us: 1.05x faster                                              |
| pickle_pure_python   | 319 us                                                 | 307 us: 1.04x faster                                               |
| json_loads           | 29.4 us                                                | 28.8 us: 1.02x faster                                              |
| xml_etree_parse      | 163 ms                                                 | 160 ms: 1.02x faster                                               |
| unpickle_pure_python | 241 us                                                 | 255 us: 1.06x slower                                               |
| pickle               | 11.1 us                                                | 11.8 us: 1.06x slower                                              |
| unpickle             | 13.9 us                                                | 14.7 us: 1.06x slower                                              |
| pickle_list          | 4.65 us                                                | 5.01 us: 1.08x slower                                              |
| xml_etree_iterparse  | 109 ms                                                 | 120 ms: 1.11x slower                                               |
| xml_etree_process    | 56.5 ms                                                | 65.6 ms: 1.16x slower                                              |
| xml_etree_generate   | 80.4 ms                                                | 96.8 ms: 1.20x slower                                              |
| tomli_loads          | 2.31 sec                                               | 2.99 sec: 1.29x slower                                             |
| Geometric mean       | (ref)                                                  | 1.04x slower                                                       |

Benchmark hidden because not significant (1): unpickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231115-linux-x86_64-gvanrossum-for_iter_uop-3.13.0a1+-5c5d8bd |
|------------------------|:------------------------------------------------------:|:------------------------------------------------------------------:|
| python_startup         | 8.69 ms                                                | 10.4 ms: 1.20x slower                                              |
| python_startup_no_site | 6.09 ms                                                | 9.07 ms: 1.49x slower                                              |
| Geometric mean         | (ref)                                                  | 1.34x slower                                                       |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231115-linux-x86_64-gvanrossum-for_iter_uop-3.13.0a1+-5c5d8bd |
|-----------|:------------------------------------------------------:|:------------------------------------------------------------------:|
| mako      | 10.8 ms                                                | 16.2 ms: 1.49x slower                                              |

All benchmarks:
===============

| Benchmark                 | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231115-linux-x86_64-gvanrossum-for_iter_uop-3.13.0a1+-5c5d8bd |
|---------------------------|:------------------------------------------------------:|:------------------------------------------------------------------:|
| typing_runtime_protocols  | 521 us                                                 | 127 us: 4.11x faster                                               |
| generators                | 76.5 ms                                                | 29.2 ms: 2.62x faster                                              |
| asyncio_tcp               | 887 ms                                                 | 501 ms: 1.77x faster                                               |
| asyncio_tcp_ssl           | 3.13 sec                                               | 1.80 sec: 1.74x faster                                             |
| json_dumps                | 13.5 ms                                                | 10.7 ms: 1.26x faster                                              |
| mypy2                     | 427 ms                                                 | 358 ms: 1.19x faster                                               |
| coroutines                | 26.1 ms                                                | 22.4 ms: 1.17x faster                                              |
| async_tree_none           | 532 ms                                                 | 465 ms: 1.15x faster                                               |
| async_tree_memoization    | 640 ms                                                 | 596 ms: 1.07x faster                                               |
| async_tree_io             | 1.31 sec                                               | 1.24 sec: 1.06x faster                                             |
| pickle_dict               | 34.8 us                                                | 33.2 us: 1.05x faster                                              |
| pickle_pure_python        | 319 us                                                 | 307 us: 1.04x faster                                               |
| async_tree_io_tg          | 1.30 sec                                               | 1.26 sec: 1.03x faster                                             |
| async_tree_memoization_tg | 627 ms                                                 | 610 ms: 1.03x faster                                               |
| gc_traversal              | 3.90 ms                                                | 3.80 ms: 1.03x faster                                              |
| sympy_sum                 | 170 ms                                                 | 166 ms: 1.02x faster                                               |
| richards_super            | 61.2 ms                                                | 59.9 ms: 1.02x faster                                              |
| json_loads                | 29.4 us                                                | 28.8 us: 1.02x faster                                              |
| async_tree_none_tg        | 490 ms                                                 | 481 ms: 1.02x faster                                               |
| xml_etree_parse           | 163 ms                                                 | 160 ms: 1.02x faster                                               |
| sqlglot_parse             | 1.43 ms                                                | 1.42 ms: 1.01x faster                                              |
| async_tree_cpu_io_mixed   | 750 ms                                                 | 742 ms: 1.01x faster                                               |
| sqlglot_transpile         | 1.75 ms                                                | 1.74 ms: 1.01x faster                                              |
| asyncio_websockets        | 556 ms                                                 | 552 ms: 1.01x faster                                               |
| pidigits                  | 190 ms                                                 | 189 ms: 1.01x faster                                               |
| create_gc_cycles          | 1.48 ms                                                | 1.49 ms: 1.01x slower                                              |
| json                      | 5.24 ms                                                | 5.30 ms: 1.01x slower                                              |
| sympy_expand              | 490 ms                                                 | 497 ms: 1.01x slower                                               |
| deepcopy                  | 360 us                                                 | 365 us: 1.01x slower                                               |
| pathlib                   | 18.5 ms                                                | 18.8 ms: 1.02x slower                                              |
| raytrace                  | 306 ms                                                 | 312 ms: 1.02x slower                                               |
| dask                      | 365 ms                                                 | 372 ms: 1.02x slower                                               |
| sympy_str                 | 299 ms                                                 | 306 ms: 1.02x slower                                               |
| docutils                  | 2.69 sec                                               | 2.75 sec: 1.02x slower                                             |
| tornado_http              | 97.7 ms                                                | 100 ms: 1.02x slower                                               |
| logging_format            | 6.83 us                                                | 7.02 us: 1.03x slower                                              |
| logging_silent            | 108 ns                                                 | 112 ns: 1.04x slower                                               |
| sympy_integrate           | 21.4 ms                                                | 22.3 ms: 1.05x slower                                              |
| bench_thread_pool         | 833 us                                                 | 873 us: 1.05x slower                                               |
| unpickle_pure_python      | 241 us                                                 | 255 us: 1.06x slower                                               |
| regex_effbot              | 3.45 ms                                                | 3.65 ms: 1.06x slower                                              |
| sqlglot_normalize         | 112 ms                                                 | 119 ms: 1.06x slower                                               |
| pickle                    | 11.1 us                                                | 11.8 us: 1.06x slower                                              |
| scimark_sor               | 121 ms                                                 | 129 ms: 1.06x slower                                               |
| unpickle                  | 13.9 us                                                | 14.7 us: 1.06x slower                                              |
| unpack_sequence           | 43.3 ns                                                | 46.0 ns: 1.06x slower                                              |
| pycparser                 | 1.20 sec                                               | 1.27 sec: 1.06x slower                                             |
| regex_dna                 | 204 ms                                                 | 219 ms: 1.07x slower                                               |
| richards                  | 48.9 ms                                                | 52.6 ms: 1.08x slower                                              |
| dulwich_log               | 64.9 ms                                                | 69.9 ms: 1.08x slower                                              |
| pickle_list               | 4.65 us                                                | 5.01 us: 1.08x slower                                              |
| chaos                     | 71.4 ms                                                | 77.2 ms: 1.08x slower                                              |
| 2to3                      | 266 ms                                                 | 291 ms: 1.09x slower                                               |
| sqlglot_optimize          | 55.2 ms                                                | 60.9 ms: 1.10x slower                                              |
| xml_etree_iterparse       | 109 ms                                                 | 120 ms: 1.11x slower                                               |
| deepcopy_memo             | 38.9 us                                                | 43.4 us: 1.11x slower                                              |
| chameleon                 | 6.86 ms                                                | 7.65 ms: 1.12x slower                                              |
| scimark_lu                | 112 ms                                                 | 126 ms: 1.12x slower                                               |
| pprint_safe_repr          | 743 ms                                                 | 841 ms: 1.13x slower                                               |
| meteor_contest            | 109 ms                                                 | 124 ms: 1.14x slower                                               |
| pprint_pformat            | 1.53 sec                                               | 1.74 sec: 1.14x slower                                             |
| sqlite_synth              | 2.58 us                                                | 2.96 us: 1.15x slower                                              |
| regex_v8                  | 22.9 ms                                                | 26.2 ms: 1.15x slower                                              |
| comprehensions            | 23.6 us                                                | 27.2 us: 1.16x slower                                              |
| xml_etree_process         | 56.5 ms                                                | 65.6 ms: 1.16x slower                                              |
| coverage                  | 81.2 ms                                                | 94.4 ms: 1.16x slower                                              |
| crypto_pyaes              | 77.5 ms                                                | 90.8 ms: 1.17x slower                                              |
| regex_compile             | 141 ms                                                 | 167 ms: 1.18x slower                                               |
| python_startup            | 8.69 ms                                                | 10.4 ms: 1.20x slower                                              |
| xml_etree_generate        | 80.4 ms                                                | 96.8 ms: 1.20x slower                                              |
| go                        | 143 ms                                                 | 172 ms: 1.20x slower                                               |
| scimark_monte_carlo       | 71.8 ms                                                | 86.4 ms: 1.20x slower                                              |
| async_generators          | 375 ms                                                 | 460 ms: 1.23x slower                                               |
| fannkuch                  | 410 ms                                                 | 522 ms: 1.27x slower                                               |
| tomli_loads               | 2.31 sec                                               | 2.99 sec: 1.29x slower                                             |
| nqueens                   | 86.8 ms                                                | 113 ms: 1.30x slower                                               |
| telco                     | 6.72 ms                                                | 8.86 ms: 1.32x slower                                              |
| nbody                     | 91.6 ms                                                | 121 ms: 1.32x slower                                               |
| scimark_fft               | 342 ms                                                 | 453 ms: 1.32x slower                                               |
| float                     | 78.9 ms                                                | 109 ms: 1.38x slower                                               |
| pyflate                   | 426 ms                                                 | 599 ms: 1.41x slower                                               |
| deltablue                 | 3.80 ms                                                | 5.64 ms: 1.48x slower                                              |
| python_startup_no_site    | 6.09 ms                                                | 9.07 ms: 1.49x slower                                              |
| mako                      | 10.8 ms                                                | 16.2 ms: 1.49x slower                                              |
| scimark_sparse_mat_mult   | 4.80 ms                                                | 7.36 ms: 1.53x slower                                              |
| hexiom                    | 6.74 ms                                                | 10.9 ms: 1.62x slower                                              |
| spectral_norm             | 105 ms                                                 | 186 ms: 1.77x slower                                               |
| Geometric mean            | (ref)                                                  | 1.05x slower                                                       |

Benchmark hidden because not significant (6): deepcopy_reduce, bench_mp_pool, unpickle_list, mdp, logging_simple, async_tree_cpu_io_mixed_tg
Ignored benchmarks (12) of results/bm-20221024-3.11.0-deaf509/bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.02x
- 95% likely to have a slowdown of 1.02x
- 99% likely to have a slowdown of 1.01x
