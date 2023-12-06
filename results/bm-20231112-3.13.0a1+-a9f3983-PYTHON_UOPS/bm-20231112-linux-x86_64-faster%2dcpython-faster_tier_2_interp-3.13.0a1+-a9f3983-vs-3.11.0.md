
# Results vs. 3.11.0

- fork: faster-cpython
- ref: faster_tier_2_interp
- machine: linux-x86_64
- commit hash: a9f3983
- commit date: 2023-11-12
- overall geometric mean: 1.02x slower \*
- HPT reliability: 99.12%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231112-linux-x86_64-faster%2dcpython-faster_tier_2_interp-3.13.0a1+-a9f3983 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| 2to3           | 266 ms                                                 | 293 ms: 1.10x slower                                                             |
| chameleon      | 6.86 ms                                                | 7.56 ms: 1.10x slower                                                            |
| docutils       | 2.69 sec                                               | 2.72 sec: 1.01x slower                                                           |
| tornado_http   | 97.7 ms                                                | 102 ms: 1.05x slower                                                             |
| Geometric mean | (ref)                                                  | 1.06x slower                                                                     |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                 | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231112-linux-x86_64-faster%2dcpython-faster_tier_2_interp-3.13.0a1+-a9f3983 |
|---------------------------|:------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| async_tree_none           | 532 ms                                                 | 462 ms: 1.15x faster                                                             |
| async_tree_memoization    | 640 ms                                                 | 592 ms: 1.08x faster                                                             |
| async_tree_io             | 1.31 sec                                               | 1.23 sec: 1.07x faster                                                           |
| async_tree_io_tg          | 1.30 sec                                               | 1.26 sec: 1.03x faster                                                           |
| async_tree_memoization_tg | 627 ms                                                 | 611 ms: 1.03x faster                                                             |
| async_tree_none_tg        | 490 ms                                                 | 479 ms: 1.02x faster                                                             |
| async_tree_cpu_io_mixed   | 750 ms                                                 | 736 ms: 1.02x faster                                                             |
| Geometric mean            | (ref)                                                  | 1.05x faster                                                                     |

Benchmark hidden because not significant (1): async_tree_cpu_io_mixed_tg

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231112-linux-x86_64-faster%2dcpython-faster_tier_2_interp-3.13.0a1+-a9f3983 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| pidigits       | 190 ms                                                 | 196 ms: 1.03x slower                                                             |
| nbody          | 91.6 ms                                                | 124 ms: 1.36x slower                                                             |
| float          | 78.9 ms                                                | 109 ms: 1.38x slower                                                             |
| Geometric mean | (ref)                                                  | 1.25x slower                                                                     |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231112-linux-x86_64-faster%2dcpython-faster_tier_2_interp-3.13.0a1+-a9f3983 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| regex_effbot   | 3.45 ms                                                | 3.49 ms: 1.01x slower                                                            |
| regex_dna      | 204 ms                                                 | 214 ms: 1.05x slower                                                             |
| regex_v8       | 22.9 ms                                                | 24.7 ms: 1.08x slower                                                            |
| regex_compile  | 141 ms                                                 | 161 ms: 1.14x slower                                                             |
| Geometric mean | (ref)                                                  | 1.07x slower                                                                     |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231112-linux-x86_64-faster%2dcpython-faster_tier_2_interp-3.13.0a1+-a9f3983 |
|----------------------|:------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| json_dumps           | 13.5 ms                                                | 10.6 ms: 1.27x faster                                                            |
| json_loads           | 29.4 us                                                | 28.2 us: 1.05x faster                                                            |
| pickle_dict          | 34.8 us                                                | 33.6 us: 1.04x faster                                                            |
| pickle_pure_python   | 319 us                                                 | 309 us: 1.03x faster                                                             |
| xml_etree_parse      | 163 ms                                                 | 159 ms: 1.03x faster                                                             |
| unpickle_list        | 5.22 us                                                | 5.10 us: 1.02x faster                                                            |
| pickle               | 11.1 us                                                | 11.4 us: 1.03x slower                                                            |
| unpickle_pure_python | 241 us                                                 | 249 us: 1.03x slower                                                             |
| xml_etree_iterparse  | 109 ms                                                 | 113 ms: 1.04x slower                                                             |
| xml_etree_process    | 56.5 ms                                                | 59.2 ms: 1.05x slower                                                            |
| unpickle             | 13.9 us                                                | 14.6 us: 1.05x slower                                                            |
| pickle_list          | 4.65 us                                                | 4.95 us: 1.06x slower                                                            |
| xml_etree_generate   | 80.4 ms                                                | 87.0 ms: 1.08x slower                                                            |
| tomli_loads          | 2.31 sec                                               | 2.99 sec: 1.29x slower                                                           |
| Geometric mean       | (ref)                                                  | 1.01x slower                                                                     |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231112-linux-x86_64-faster%2dcpython-faster_tier_2_interp-3.13.0a1+-a9f3983 |
|------------------------|:------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| python_startup         | 8.69 ms                                                | 10.3 ms: 1.19x slower                                                            |
| python_startup_no_site | 6.09 ms                                                | 9.03 ms: 1.48x slower                                                            |
| Geometric mean         | (ref)                                                  | 1.33x slower                                                                     |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231112-linux-x86_64-faster%2dcpython-faster_tier_2_interp-3.13.0a1+-a9f3983 |
|-----------|:------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| mako      | 10.8 ms                                                | 15.2 ms: 1.40x slower                                                            |

All benchmarks:
===============

| Benchmark                 | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231112-linux-x86_64-faster%2dcpython-faster_tier_2_interp-3.13.0a1+-a9f3983 |
|---------------------------|:------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| typing_runtime_protocols  | 521 us                                                 | 124 us: 4.20x faster                                                             |
| generators                | 76.5 ms                                                | 29.9 ms: 2.56x faster                                                            |
| asyncio_tcp               | 887 ms                                                 | 502 ms: 1.77x faster                                                             |
| asyncio_tcp_ssl           | 3.13 sec                                               | 1.81 sec: 1.73x faster                                                           |
| json_dumps                | 13.5 ms                                                | 10.6 ms: 1.27x faster                                                            |
| mypy2                     | 427 ms                                                 | 355 ms: 1.20x faster                                                             |
| coroutines                | 26.1 ms                                                | 22.3 ms: 1.17x faster                                                            |
| async_tree_none           | 532 ms                                                 | 462 ms: 1.15x faster                                                             |
| sympy_sum                 | 170 ms                                                 | 154 ms: 1.11x faster                                                             |
| async_tree_memoization    | 640 ms                                                 | 592 ms: 1.08x faster                                                             |
| sqlglot_parse             | 1.43 ms                                                | 1.34 ms: 1.07x faster                                                            |
| async_tree_io             | 1.31 sec                                               | 1.23 sec: 1.07x faster                                                           |
| sqlglot_transpile         | 1.75 ms                                                | 1.67 ms: 1.05x faster                                                            |
| json_loads                | 29.4 us                                                | 28.2 us: 1.05x faster                                                            |
| sympy_str                 | 299 ms                                                 | 287 ms: 1.04x faster                                                             |
| sqlglot_normalize         | 112 ms                                                 | 108 ms: 1.04x faster                                                             |
| pickle_dict               | 34.8 us                                                | 33.6 us: 1.04x faster                                                            |
| async_tree_io_tg          | 1.30 sec                                               | 1.26 sec: 1.03x faster                                                           |
| richards_super            | 61.2 ms                                                | 59.2 ms: 1.03x faster                                                            |
| pickle_pure_python        | 319 us                                                 | 309 us: 1.03x faster                                                             |
| async_tree_memoization_tg | 627 ms                                                 | 611 ms: 1.03x faster                                                             |
| xml_etree_parse           | 163 ms                                                 | 159 ms: 1.03x faster                                                             |
| unpickle_list             | 5.22 us                                                | 5.10 us: 1.02x faster                                                            |
| gc_traversal              | 3.90 ms                                                | 3.82 ms: 1.02x faster                                                            |
| json                      | 5.24 ms                                                | 5.12 ms: 1.02x faster                                                            |
| async_tree_none_tg        | 490 ms                                                 | 479 ms: 1.02x faster                                                             |
| async_tree_cpu_io_mixed   | 750 ms                                                 | 736 ms: 1.02x faster                                                             |
| sympy_expand              | 490 ms                                                 | 483 ms: 1.01x faster                                                             |
| logging_silent            | 108 ns                                                 | 107 ns: 1.01x faster                                                             |
| asyncio_websockets        | 556 ms                                                 | 551 ms: 1.01x faster                                                             |
| sqlglot_optimize          | 55.2 ms                                                | 54.9 ms: 1.01x faster                                                            |
| deepcopy                  | 360 us                                                 | 359 us: 1.00x faster                                                             |
| mdp                       | 2.79 sec                                               | 2.78 sec: 1.00x faster                                                           |
| create_gc_cycles          | 1.48 ms                                                | 1.49 ms: 1.01x slower                                                            |
| sympy_integrate           | 21.4 ms                                                | 21.5 ms: 1.01x slower                                                            |
| regex_effbot              | 3.45 ms                                                | 3.49 ms: 1.01x slower                                                            |
| docutils                  | 2.69 sec                                               | 2.72 sec: 1.01x slower                                                           |
| pathlib                   | 18.5 ms                                                | 18.8 ms: 1.02x slower                                                            |
| deepcopy_reduce           | 3.14 us                                                | 3.21 us: 1.02x slower                                                            |
| pickle                    | 11.1 us                                                | 11.4 us: 1.03x slower                                                            |
| pidigits                  | 190 ms                                                 | 196 ms: 1.03x slower                                                             |
| raytrace                  | 306 ms                                                 | 316 ms: 1.03x slower                                                             |
| bench_thread_pool         | 833 us                                                 | 860 us: 1.03x slower                                                             |
| unpickle_pure_python      | 241 us                                                 | 249 us: 1.03x slower                                                             |
| scimark_sor               | 121 ms                                                 | 126 ms: 1.04x slower                                                             |
| xml_etree_iterparse       | 109 ms                                                 | 113 ms: 1.04x slower                                                             |
| tornado_http              | 97.7 ms                                                | 102 ms: 1.05x slower                                                             |
| xml_etree_process         | 56.5 ms                                                | 59.2 ms: 1.05x slower                                                            |
| regex_dna                 | 204 ms                                                 | 214 ms: 1.05x slower                                                             |
| unpickle                  | 13.9 us                                                | 14.6 us: 1.05x slower                                                            |
| logging_format            | 6.83 us                                                | 7.18 us: 1.05x slower                                                            |
| spectral_norm             | 105 ms                                                 | 111 ms: 1.05x slower                                                             |
| pycparser                 | 1.20 sec                                               | 1.26 sec: 1.06x slower                                                           |
| chaos                     | 71.4 ms                                                | 75.7 ms: 1.06x slower                                                            |
| pickle_list               | 4.65 us                                                | 4.95 us: 1.06x slower                                                            |
| scimark_lu                | 112 ms                                                 | 120 ms: 1.06x slower                                                             |
| dulwich_log               | 64.9 ms                                                | 69.2 ms: 1.06x slower                                                            |
| unpack_sequence           | 43.3 ns                                                | 46.6 ns: 1.08x slower                                                            |
| richards                  | 48.9 ms                                                | 52.7 ms: 1.08x slower                                                            |
| regex_v8                  | 22.9 ms                                                | 24.7 ms: 1.08x slower                                                            |
| xml_etree_generate        | 80.4 ms                                                | 87.0 ms: 1.08x slower                                                            |
| 2to3                      | 266 ms                                                 | 293 ms: 1.10x slower                                                             |
| meteor_contest            | 109 ms                                                 | 120 ms: 1.10x slower                                                             |
| chameleon                 | 6.86 ms                                                | 7.56 ms: 1.10x slower                                                            |
| deepcopy_memo             | 38.9 us                                                | 43.3 us: 1.11x slower                                                            |
| pprint_pformat            | 1.53 sec                                               | 1.71 sec: 1.12x slower                                                           |
| pprint_safe_repr          | 743 ms                                                 | 833 ms: 1.12x slower                                                             |
| comprehensions            | 23.6 us                                                | 26.5 us: 1.13x slower                                                            |
| sqlite_synth              | 2.58 us                                                | 2.91 us: 1.13x slower                                                            |
| scimark_monte_carlo       | 71.8 ms                                                | 81.6 ms: 1.14x slower                                                            |
| regex_compile             | 141 ms                                                 | 161 ms: 1.14x slower                                                             |
| crypto_pyaes              | 77.5 ms                                                | 88.5 ms: 1.14x slower                                                            |
| coverage                  | 81.2 ms                                                | 95.3 ms: 1.17x slower                                                            |
| python_startup            | 8.69 ms                                                | 10.3 ms: 1.19x slower                                                            |
| go                        | 143 ms                                                 | 170 ms: 1.19x slower                                                             |
| async_generators          | 375 ms                                                 | 468 ms: 1.25x slower                                                             |
| fannkuch                  | 410 ms                                                 | 512 ms: 1.25x slower                                                             |
| scimark_fft               | 342 ms                                                 | 440 ms: 1.28x slower                                                             |
| tomli_loads               | 2.31 sec                                               | 2.99 sec: 1.29x slower                                                           |
| nqueens                   | 86.8 ms                                                | 113 ms: 1.30x slower                                                             |
| telco                     | 6.72 ms                                                | 8.98 ms: 1.34x slower                                                            |
| pyflate                   | 426 ms                                                 | 573 ms: 1.34x slower                                                             |
| nbody                     | 91.6 ms                                                | 124 ms: 1.36x slower                                                             |
| float                     | 78.9 ms                                                | 109 ms: 1.38x slower                                                             |
| scimark_sparse_mat_mult   | 4.80 ms                                                | 6.66 ms: 1.39x slower                                                            |
| deltablue                 | 3.80 ms                                                | 5.32 ms: 1.40x slower                                                            |
| mako                      | 10.8 ms                                                | 15.2 ms: 1.40x slower                                                            |
| python_startup_no_site    | 6.09 ms                                                | 9.03 ms: 1.48x slower                                                            |
| hexiom                    | 6.74 ms                                                | 10.6 ms: 1.57x slower                                                            |
| Geometric mean            | (ref)                                                  | 1.02x slower                                                                     |

Benchmark hidden because not significant (3): async_tree_cpu_io_mixed_tg, bench_mp_pool, logging_simple
Ignored benchmarks (13) of results/bm-20221024-3.11.0-deaf509/bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift


# HPT report

- Reliability score: 99.12% likely to be slow
- 90% likely to have a slowdown of 1.01x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
