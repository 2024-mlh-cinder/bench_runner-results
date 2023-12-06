
# Results vs. 3.11.0

- fork: faster-cpython
- ref: optimize_globals_to_
- machine: linux-x86_64
- commit hash: 58d77db
- commit date: 2023-11-16
- overall geometric mean: 1.01x slower \*
- HPT reliability: 96.94%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231116-linux-x86_64-faster%2dcpython-optimize_globals_to_-3.13.0a1+-58d77db |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| 2to3           | 266 ms                                                 | 285 ms: 1.07x slower                                                             |
| chameleon      | 6.86 ms                                                | 7.40 ms: 1.08x slower                                                            |
| docutils       | 2.69 sec                                               | 2.70 sec: 1.01x slower                                                           |
| tornado_http   | 97.7 ms                                                | 99.9 ms: 1.02x slower                                                            |
| Geometric mean | (ref)                                                  | 1.04x slower                                                                     |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                 | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231116-linux-x86_64-faster%2dcpython-optimize_globals_to_-3.13.0a1+-58d77db |
|---------------------------|:------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| async_tree_none           | 532 ms                                                 | 460 ms: 1.16x faster                                                             |
| async_tree_memoization    | 640 ms                                                 | 588 ms: 1.09x faster                                                             |
| async_tree_io             | 1.31 sec                                               | 1.23 sec: 1.07x faster                                                           |
| async_tree_none_tg        | 490 ms                                                 | 470 ms: 1.04x faster                                                             |
| async_tree_io_tg          | 1.30 sec                                               | 1.26 sec: 1.04x faster                                                           |
| async_tree_memoization_tg | 627 ms                                                 | 610 ms: 1.03x faster                                                             |
| async_tree_cpu_io_mixed   | 750 ms                                                 | 734 ms: 1.02x faster                                                             |
| Geometric mean            | (ref)                                                  | 1.05x faster                                                                     |

Benchmark hidden because not significant (1): async_tree_cpu_io_mixed_tg

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231116-linux-x86_64-faster%2dcpython-optimize_globals_to_-3.13.0a1+-58d77db |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| pidigits       | 190 ms                                                 | 188 ms: 1.01x faster                                                             |
| nbody          | 91.6 ms                                                | 114 ms: 1.25x slower                                                             |
| float          | 78.9 ms                                                | 101 ms: 1.28x slower                                                             |
| Geometric mean | (ref)                                                  | 1.17x slower                                                                     |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231116-linux-x86_64-faster%2dcpython-optimize_globals_to_-3.13.0a1+-58d77db |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| regex_effbot   | 3.45 ms                                                | 3.62 ms: 1.05x slower                                                            |
| regex_dna      | 204 ms                                                 | 217 ms: 1.06x slower                                                             |
| regex_v8       | 22.9 ms                                                | 24.8 ms: 1.08x slower                                                            |
| regex_compile  | 141 ms                                                 | 162 ms: 1.15x slower                                                             |
| Geometric mean | (ref)                                                  | 1.08x slower                                                                     |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231116-linux-x86_64-faster%2dcpython-optimize_globals_to_-3.13.0a1+-58d77db |
|----------------------|:------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| json_dumps           | 13.5 ms                                                | 10.5 ms: 1.28x faster                                                            |
| json_loads           | 29.4 us                                                | 28.2 us: 1.05x faster                                                            |
| pickle_pure_python   | 319 us                                                 | 308 us: 1.04x faster                                                             |
| unpickle_list        | 5.22 us                                                | 5.06 us: 1.03x faster                                                            |
| xml_etree_parse      | 163 ms                                                 | 159 ms: 1.03x faster                                                             |
| unpickle_pure_python | 241 us                                                 | 248 us: 1.03x slower                                                             |
| xml_etree_iterparse  | 109 ms                                                 | 112 ms: 1.03x slower                                                             |
| pickle_dict          | 34.8 us                                                | 36.3 us: 1.04x slower                                                            |
| xml_etree_process    | 56.5 ms                                                | 59.4 ms: 1.05x slower                                                            |
| pickle               | 11.1 us                                                | 11.7 us: 1.06x slower                                                            |
| unpickle             | 13.9 us                                                | 14.8 us: 1.07x slower                                                            |
| xml_etree_generate   | 80.4 ms                                                | 87.7 ms: 1.09x slower                                                            |
| pickle_list          | 4.65 us                                                | 5.08 us: 1.09x slower                                                            |
| tomli_loads          | 2.31 sec                                               | 2.86 sec: 1.24x slower                                                           |
| Geometric mean       | (ref)                                                  | 1.02x slower                                                                     |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231116-linux-x86_64-faster%2dcpython-optimize_globals_to_-3.13.0a1+-58d77db |
|------------------------|:------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| python_startup         | 8.69 ms                                                | 10.4 ms: 1.20x slower                                                            |
| python_startup_no_site | 6.09 ms                                                | 9.08 ms: 1.49x slower                                                            |
| Geometric mean         | (ref)                                                  | 1.34x slower                                                                     |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231116-linux-x86_64-faster%2dcpython-optimize_globals_to_-3.13.0a1+-58d77db |
|-----------|:------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| mako      | 10.8 ms                                                | 14.7 ms: 1.36x slower                                                            |

All benchmarks:
===============

| Benchmark                 | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231116-linux-x86_64-faster%2dcpython-optimize_globals_to_-3.13.0a1+-58d77db |
|---------------------------|:------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| typing_runtime_protocols  | 521 us                                                 | 123 us: 4.25x faster                                                             |
| generators                | 76.5 ms                                                | 30.2 ms: 2.53x faster                                                            |
| asyncio_tcp               | 887 ms                                                 | 496 ms: 1.79x faster                                                             |
| asyncio_tcp_ssl           | 3.13 sec                                               | 1.80 sec: 1.74x faster                                                           |
| json_dumps                | 13.5 ms                                                | 10.5 ms: 1.28x faster                                                            |
| mypy2                     | 427 ms                                                 | 355 ms: 1.20x faster                                                             |
| coroutines                | 26.1 ms                                                | 22.3 ms: 1.17x faster                                                            |
| async_tree_none           | 532 ms                                                 | 460 ms: 1.16x faster                                                             |
| sympy_sum                 | 170 ms                                                 | 154 ms: 1.10x faster                                                             |
| async_tree_memoization    | 640 ms                                                 | 588 ms: 1.09x faster                                                             |
| richards_super            | 61.2 ms                                                | 57.4 ms: 1.07x faster                                                            |
| sqlglot_parse             | 1.43 ms                                                | 1.34 ms: 1.07x faster                                                            |
| async_tree_io             | 1.31 sec                                               | 1.23 sec: 1.07x faster                                                           |
| sympy_str                 | 299 ms                                                 | 284 ms: 1.05x faster                                                             |
| sqlglot_transpile         | 1.75 ms                                                | 1.67 ms: 1.05x faster                                                            |
| json_loads                | 29.4 us                                                | 28.2 us: 1.05x faster                                                            |
| async_tree_none_tg        | 490 ms                                                 | 470 ms: 1.04x faster                                                             |
| pickle_pure_python        | 319 us                                                 | 308 us: 1.04x faster                                                             |
| async_tree_io_tg          | 1.30 sec                                               | 1.26 sec: 1.04x faster                                                           |
| sqlglot_normalize         | 112 ms                                                 | 109 ms: 1.03x faster                                                             |
| unpickle_list             | 5.22 us                                                | 5.06 us: 1.03x faster                                                            |
| async_tree_memoization_tg | 627 ms                                                 | 610 ms: 1.03x faster                                                             |
| xml_etree_parse           | 163 ms                                                 | 159 ms: 1.03x faster                                                             |
| gc_traversal              | 3.90 ms                                                | 3.82 ms: 1.02x faster                                                            |
| async_tree_cpu_io_mixed   | 750 ms                                                 | 734 ms: 1.02x faster                                                             |
| sympy_expand              | 490 ms                                                 | 480 ms: 1.02x faster                                                             |
| json                      | 5.24 ms                                                | 5.15 ms: 1.02x faster                                                            |
| deepcopy                  | 360 us                                                 | 355 us: 1.02x faster                                                             |
| logging_silent            | 108 ns                                                 | 107 ns: 1.01x faster                                                             |
| pidigits                  | 190 ms                                                 | 188 ms: 1.01x faster                                                             |
| mdp                       | 2.79 sec                                               | 2.76 sec: 1.01x faster                                                           |
| sqlglot_optimize          | 55.2 ms                                                | 54.7 ms: 1.01x faster                                                            |
| asyncio_websockets        | 556 ms                                                 | 551 ms: 1.01x faster                                                             |
| sympy_integrate           | 21.4 ms                                                | 21.5 ms: 1.01x slower                                                            |
| docutils                  | 2.69 sec                                               | 2.70 sec: 1.01x slower                                                           |
| deepcopy_reduce           | 3.14 us                                                | 3.16 us: 1.01x slower                                                            |
| pycparser                 | 1.20 sec                                               | 1.21 sec: 1.01x slower                                                           |
| logging_format            | 6.83 us                                                | 6.96 us: 1.02x slower                                                            |
| tornado_http              | 97.7 ms                                                | 99.9 ms: 1.02x slower                                                            |
| chaos                     | 71.4 ms                                                | 73.2 ms: 1.02x slower                                                            |
| bench_thread_pool         | 833 us                                                 | 856 us: 1.03x slower                                                             |
| unpickle_pure_python      | 241 us                                                 | 248 us: 1.03x slower                                                             |
| xml_etree_iterparse       | 109 ms                                                 | 112 ms: 1.03x slower                                                             |
| comprehensions            | 23.6 us                                                | 24.3 us: 1.03x slower                                                            |
| richards                  | 48.9 ms                                                | 50.5 ms: 1.03x slower                                                            |
| pickle_dict               | 34.8 us                                                | 36.3 us: 1.04x slower                                                            |
| regex_effbot              | 3.45 ms                                                | 3.62 ms: 1.05x slower                                                            |
| xml_etree_process         | 56.5 ms                                                | 59.4 ms: 1.05x slower                                                            |
| pickle                    | 11.1 us                                                | 11.7 us: 1.06x slower                                                            |
| scimark_sor               | 121 ms                                                 | 129 ms: 1.06x slower                                                             |
| regex_dna                 | 204 ms                                                 | 217 ms: 1.06x slower                                                             |
| dulwich_log               | 64.9 ms                                                | 69.2 ms: 1.07x slower                                                            |
| unpickle                  | 13.9 us                                                | 14.8 us: 1.07x slower                                                            |
| 2to3                      | 266 ms                                                 | 285 ms: 1.07x slower                                                             |
| spectral_norm             | 105 ms                                                 | 113 ms: 1.07x slower                                                             |
| chameleon                 | 6.86 ms                                                | 7.40 ms: 1.08x slower                                                            |
| regex_v8                  | 22.9 ms                                                | 24.8 ms: 1.08x slower                                                            |
| meteor_contest            | 109 ms                                                 | 118 ms: 1.09x slower                                                             |
| xml_etree_generate        | 80.4 ms                                                | 87.7 ms: 1.09x slower                                                            |
| pickle_list               | 4.65 us                                                | 5.08 us: 1.09x slower                                                            |
| unpack_sequence           | 43.3 ns                                                | 47.3 ns: 1.09x slower                                                            |
| scimark_lu                | 112 ms                                                 | 123 ms: 1.10x slower                                                             |
| crypto_pyaes              | 77.5 ms                                                | 84.9 ms: 1.10x slower                                                            |
| pprint_pformat            | 1.53 sec                                               | 1.68 sec: 1.10x slower                                                           |
| pprint_safe_repr          | 743 ms                                                 | 822 ms: 1.11x slower                                                             |
| deepcopy_memo             | 38.9 us                                                | 43.1 us: 1.11x slower                                                            |
| sqlite_synth              | 2.58 us                                                | 2.91 us: 1.13x slower                                                            |
| regex_compile             | 141 ms                                                 | 162 ms: 1.15x slower                                                             |
| scimark_monte_carlo       | 71.8 ms                                                | 82.2 ms: 1.15x slower                                                            |
| nqueens                   | 86.8 ms                                                | 103 ms: 1.19x slower                                                             |
| coverage                  | 81.2 ms                                                | 96.8 ms: 1.19x slower                                                            |
| python_startup            | 8.69 ms                                                | 10.4 ms: 1.20x slower                                                            |
| fannkuch                  | 410 ms                                                 | 492 ms: 1.20x slower                                                             |
| tomli_loads               | 2.31 sec                                               | 2.86 sec: 1.24x slower                                                           |
| async_generators          | 375 ms                                                 | 464 ms: 1.24x slower                                                             |
| nbody                     | 91.6 ms                                                | 114 ms: 1.25x slower                                                             |
| scimark_fft               | 342 ms                                                 | 427 ms: 1.25x slower                                                             |
| pyflate                   | 426 ms                                                 | 535 ms: 1.26x slower                                                             |
| float                     | 78.9 ms                                                | 101 ms: 1.28x slower                                                             |
| go                        | 143 ms                                                 | 186 ms: 1.30x slower                                                             |
| deltablue                 | 3.80 ms                                                | 4.98 ms: 1.31x slower                                                            |
| telco                     | 6.72 ms                                                | 8.79 ms: 1.31x slower                                                            |
| mako                      | 10.8 ms                                                | 14.7 ms: 1.36x slower                                                            |
| scimark_sparse_mat_mult   | 4.80 ms                                                | 6.94 ms: 1.44x slower                                                            |
| hexiom                    | 6.74 ms                                                | 9.84 ms: 1.46x slower                                                            |
| python_startup_no_site    | 6.09 ms                                                | 9.08 ms: 1.49x slower                                                            |
| Geometric mean            | (ref)                                                  | 1.01x slower                                                                     |

Benchmark hidden because not significant (7): raytrace, logging_simple, async_tree_cpu_io_mixed_tg, bench_mp_pool, pathlib, create_gc_cycles, dask
Ignored benchmarks (12) of results/bm-20221024-3.11.0-deaf509/bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift


# HPT report

- Reliability score: 96.94% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
