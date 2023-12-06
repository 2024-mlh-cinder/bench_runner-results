
# Results vs. 3.11.0

- fork: faster-cpython
- ref: optimize_globals_to_
- machine: linux-x86_64
- commit hash: 01e464a
- commit date: 2023-11-04
- overall geometric mean: 1.03x slower \*
- HPT reliability: 99.58%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231104-linux-x86_64-faster%2dcpython-optimize_globals_to_-3.13.0a1+-01e464a |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| 2to3           | 266 ms                                                 | 292 ms: 1.10x slower                                                             |
| chameleon      | 6.86 ms                                                | 7.59 ms: 1.11x slower                                                            |
| docutils       | 2.69 sec                                               | 2.73 sec: 1.02x slower                                                           |
| tornado_http   | 97.7 ms                                                | 99.7 ms: 1.02x slower                                                            |
| Geometric mean | (ref)                                                  | 1.06x slower                                                                     |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                 | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231104-linux-x86_64-faster%2dcpython-optimize_globals_to_-3.13.0a1+-01e464a |
|---------------------------|:------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| async_tree_none           | 532 ms                                                 | 459 ms: 1.16x faster                                                             |
| async_tree_memoization    | 640 ms                                                 | 588 ms: 1.09x faster                                                             |
| async_tree_io             | 1.31 sec                                               | 1.21 sec: 1.08x faster                                                           |
| async_tree_io_tg          | 1.30 sec                                               | 1.25 sec: 1.05x faster                                                           |
| async_tree_none_tg        | 490 ms                                                 | 472 ms: 1.04x faster                                                             |
| async_tree_memoization_tg | 627 ms                                                 | 612 ms: 1.03x faster                                                             |
| async_tree_cpu_io_mixed   | 750 ms                                                 | 732 ms: 1.02x faster                                                             |
| Geometric mean            | (ref)                                                  | 1.06x faster                                                                     |

Benchmark hidden because not significant (1): async_tree_cpu_io_mixed_tg

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231104-linux-x86_64-faster%2dcpython-optimize_globals_to_-3.13.0a1+-01e464a |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| pidigits       | 190 ms                                                 | 197 ms: 1.03x slower                                                             |
| float          | 78.9 ms                                                | 104 ms: 1.32x slower                                                             |
| nbody          | 91.6 ms                                                | 122 ms: 1.33x slower                                                             |
| Geometric mean | (ref)                                                  | 1.22x slower                                                                     |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231104-linux-x86_64-faster%2dcpython-optimize_globals_to_-3.13.0a1+-01e464a |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| regex_dna      | 204 ms                                                 | 218 ms: 1.07x slower                                                             |
| regex_effbot   | 3.45 ms                                                | 3.72 ms: 1.08x slower                                                            |
| regex_v8       | 22.9 ms                                                | 25.8 ms: 1.13x slower                                                            |
| regex_compile  | 141 ms                                                 | 164 ms: 1.16x slower                                                             |
| Geometric mean | (ref)                                                  | 1.11x slower                                                                     |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231104-linux-x86_64-faster%2dcpython-optimize_globals_to_-3.13.0a1+-01e464a |
|----------------------|:------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| json_dumps           | 13.5 ms                                                | 10.7 ms: 1.26x faster                                                            |
| json_loads           | 29.4 us                                                | 27.7 us: 1.06x faster                                                            |
| pickle_pure_python   | 319 us                                                 | 303 us: 1.05x faster                                                             |
| xml_etree_parse      | 163 ms                                                 | 159 ms: 1.02x faster                                                             |
| unpickle_pure_python | 241 us                                                 | 243 us: 1.01x slower                                                             |
| pickle_dict          | 34.8 us                                                | 35.6 us: 1.02x slower                                                            |
| xml_etree_iterparse  | 109 ms                                                 | 112 ms: 1.03x slower                                                             |
| unpickle_list        | 5.22 us                                                | 5.40 us: 1.03x slower                                                            |
| pickle               | 11.1 us                                                | 11.6 us: 1.05x slower                                                            |
| xml_etree_process    | 56.5 ms                                                | 59.5 ms: 1.05x slower                                                            |
| xml_etree_generate   | 80.4 ms                                                | 87.6 ms: 1.09x slower                                                            |
| pickle_list          | 4.65 us                                                | 5.11 us: 1.10x slower                                                            |
| unpickle             | 13.9 us                                                | 15.5 us: 1.12x slower                                                            |
| tomli_loads          | 2.31 sec                                               | 2.99 sec: 1.29x slower                                                           |
| Geometric mean       | (ref)                                                  | 1.03x slower                                                                     |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231104-linux-x86_64-faster%2dcpython-optimize_globals_to_-3.13.0a1+-01e464a |
|------------------------|:------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| python_startup         | 8.69 ms                                                | 10.3 ms: 1.19x slower                                                            |
| python_startup_no_site | 6.09 ms                                                | 9.00 ms: 1.48x slower                                                            |
| Geometric mean         | (ref)                                                  | 1.32x slower                                                                     |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231104-linux-x86_64-faster%2dcpython-optimize_globals_to_-3.13.0a1+-01e464a |
|-----------|:------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| mako      | 10.8 ms                                                | 15.3 ms: 1.41x slower                                                            |

All benchmarks:
===============

| Benchmark                 | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231104-linux-x86_64-faster%2dcpython-optimize_globals_to_-3.13.0a1+-01e464a |
|---------------------------|:------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| typing_runtime_protocols  | 521 us                                                 | 124 us: 4.21x faster                                                             |
| generators                | 76.5 ms                                                | 30.0 ms: 2.55x faster                                                            |
| asyncio_tcp               | 887 ms                                                 | 495 ms: 1.79x faster                                                             |
| asyncio_tcp_ssl           | 3.13 sec                                               | 1.81 sec: 1.73x faster                                                           |
| json_dumps                | 13.5 ms                                                | 10.7 ms: 1.26x faster                                                            |
| mypy2                     | 427 ms                                                 | 358 ms: 1.19x faster                                                             |
| coroutines                | 26.1 ms                                                | 22.1 ms: 1.18x faster                                                            |
| async_tree_none           | 532 ms                                                 | 459 ms: 1.16x faster                                                             |
| async_tree_memoization    | 640 ms                                                 | 588 ms: 1.09x faster                                                             |
| sympy_sum                 | 170 ms                                                 | 157 ms: 1.09x faster                                                             |
| async_tree_io             | 1.31 sec                                               | 1.21 sec: 1.08x faster                                                           |
| json_loads                | 29.4 us                                                | 27.7 us: 1.06x faster                                                            |
| richards_super            | 61.2 ms                                                | 57.8 ms: 1.06x faster                                                            |
| sqlglot_parse             | 1.43 ms                                                | 1.36 ms: 1.05x faster                                                            |
| pickle_pure_python        | 319 us                                                 | 303 us: 1.05x faster                                                             |
| async_tree_io_tg          | 1.30 sec                                               | 1.25 sec: 1.05x faster                                                           |
| sqlglot_normalize         | 112 ms                                                 | 107 ms: 1.05x faster                                                             |
| sqlglot_transpile         | 1.75 ms                                                | 1.69 ms: 1.04x faster                                                            |
| sympy_str                 | 299 ms                                                 | 288 ms: 1.04x faster                                                             |
| async_tree_none_tg        | 490 ms                                                 | 472 ms: 1.04x faster                                                             |
| logging_silent            | 108 ns                                                 | 105 ns: 1.03x faster                                                             |
| gc_traversal              | 3.90 ms                                                | 3.80 ms: 1.03x faster                                                            |
| async_tree_memoization_tg | 627 ms                                                 | 612 ms: 1.03x faster                                                             |
| async_tree_cpu_io_mixed   | 750 ms                                                 | 732 ms: 1.02x faster                                                             |
| xml_etree_parse           | 163 ms                                                 | 159 ms: 1.02x faster                                                             |
| json                      | 5.24 ms                                                | 5.14 ms: 1.02x faster                                                            |
| create_gc_cycles          | 1.48 ms                                                | 1.45 ms: 1.02x faster                                                            |
| deepcopy                  | 360 us                                                 | 358 us: 1.01x faster                                                             |
| asyncio_websockets        | 556 ms                                                 | 552 ms: 1.01x faster                                                             |
| sympy_expand              | 490 ms                                                 | 488 ms: 1.01x faster                                                             |
| unpickle_pure_python      | 241 us                                                 | 243 us: 1.01x slower                                                             |
| raytrace                  | 306 ms                                                 | 309 ms: 1.01x slower                                                             |
| sympy_integrate           | 21.4 ms                                                | 21.6 ms: 1.01x slower                                                            |
| logging_simple            | 6.24 us                                                | 6.32 us: 1.01x slower                                                            |
| pycparser                 | 1.20 sec                                               | 1.21 sec: 1.01x slower                                                           |
| docutils                  | 2.69 sec                                               | 2.73 sec: 1.02x slower                                                           |
| tornado_http              | 97.7 ms                                                | 99.7 ms: 1.02x slower                                                            |
| pickle_dict               | 34.8 us                                                | 35.6 us: 1.02x slower                                                            |
| scimark_sor               | 121 ms                                                 | 125 ms: 1.03x slower                                                             |
| bench_thread_pool         | 833 us                                                 | 860 us: 1.03x slower                                                             |
| xml_etree_iterparse       | 109 ms                                                 | 112 ms: 1.03x slower                                                             |
| pidigits                  | 190 ms                                                 | 197 ms: 1.03x slower                                                             |
| unpickle_list             | 5.22 us                                                | 5.40 us: 1.03x slower                                                            |
| spectral_norm             | 105 ms                                                 | 109 ms: 1.04x slower                                                             |
| richards                  | 48.9 ms                                                | 50.7 ms: 1.04x slower                                                            |
| logging_format            | 6.83 us                                                | 7.12 us: 1.04x slower                                                            |
| pickle                    | 11.1 us                                                | 11.6 us: 1.05x slower                                                            |
| xml_etree_process         | 56.5 ms                                                | 59.5 ms: 1.05x slower                                                            |
| mdp                       | 2.79 sec                                               | 2.94 sec: 1.05x slower                                                           |
| chaos                     | 71.4 ms                                                | 75.4 ms: 1.06x slower                                                            |
| regex_dna                 | 204 ms                                                 | 218 ms: 1.07x slower                                                             |
| dulwich_log               | 64.9 ms                                                | 69.4 ms: 1.07x slower                                                            |
| pathlib                   | 18.5 ms                                                | 19.7 ms: 1.07x slower                                                            |
| regex_effbot              | 3.45 ms                                                | 3.72 ms: 1.08x slower                                                            |
| scimark_lu                | 112 ms                                                 | 122 ms: 1.09x slower                                                             |
| pprint_safe_repr          | 743 ms                                                 | 807 ms: 1.09x slower                                                             |
| xml_etree_generate        | 80.4 ms                                                | 87.6 ms: 1.09x slower                                                            |
| pprint_pformat            | 1.53 sec                                               | 1.67 sec: 1.09x slower                                                           |
| deepcopy_memo             | 38.9 us                                                | 42.6 us: 1.10x slower                                                            |
| 2to3                      | 266 ms                                                 | 292 ms: 1.10x slower                                                             |
| pickle_list               | 4.65 us                                                | 5.11 us: 1.10x slower                                                            |
| chameleon                 | 6.86 ms                                                | 7.59 ms: 1.11x slower                                                            |
| meteor_contest            | 109 ms                                                 | 121 ms: 1.11x slower                                                             |
| comprehensions            | 23.6 us                                                | 26.2 us: 1.11x slower                                                            |
| sqlite_synth              | 2.58 us                                                | 2.87 us: 1.11x slower                                                            |
| scimark_monte_carlo       | 71.8 ms                                                | 79.9 ms: 1.11x slower                                                            |
| unpickle                  | 13.9 us                                                | 15.5 us: 1.12x slower                                                            |
| regex_v8                  | 22.9 ms                                                | 25.8 ms: 1.13x slower                                                            |
| crypto_pyaes              | 77.5 ms                                                | 88.4 ms: 1.14x slower                                                            |
| regex_compile             | 141 ms                                                 | 164 ms: 1.16x slower                                                             |
| coverage                  | 81.2 ms                                                | 96.0 ms: 1.18x slower                                                            |
| python_startup            | 8.69 ms                                                | 10.3 ms: 1.19x slower                                                            |
| go                        | 143 ms                                                 | 170 ms: 1.19x slower                                                             |
| async_generators          | 375 ms                                                 | 467 ms: 1.24x slower                                                             |
| fannkuch                  | 410 ms                                                 | 510 ms: 1.25x slower                                                             |
| nqueens                   | 86.8 ms                                                | 108 ms: 1.25x slower                                                             |
| scimark_fft               | 342 ms                                                 | 437 ms: 1.28x slower                                                             |
| tomli_loads               | 2.31 sec                                               | 2.99 sec: 1.29x slower                                                           |
| telco                     | 6.72 ms                                                | 8.71 ms: 1.30x slower                                                            |
| float                     | 78.9 ms                                                | 104 ms: 1.32x slower                                                             |
| nbody                     | 91.6 ms                                                | 122 ms: 1.33x slower                                                             |
| pyflate                   | 426 ms                                                 | 579 ms: 1.36x slower                                                             |
| unpack_sequence           | 43.3 ns                                                | 59.4 ns: 1.37x slower                                                            |
| deltablue                 | 3.80 ms                                                | 5.25 ms: 1.38x slower                                                            |
| mako                      | 10.8 ms                                                | 15.3 ms: 1.41x slower                                                            |
| scimark_sparse_mat_mult   | 4.80 ms                                                | 6.87 ms: 1.43x slower                                                            |
| python_startup_no_site    | 6.09 ms                                                | 9.00 ms: 1.48x slower                                                            |
| hexiom                    | 6.74 ms                                                | 10.3 ms: 1.52x slower                                                            |
| Geometric mean            | (ref)                                                  | 1.03x slower                                                                     |

Benchmark hidden because not significant (4): async_tree_cpu_io_mixed_tg, sqlglot_optimize, bench_mp_pool, deepcopy_reduce
Ignored benchmarks (13) of results/bm-20221024-3.11.0-deaf509/bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift


# HPT report

- Reliability score: 99.58% likely to be slow
- 90% likely to have a slowdown of 1.01x
- 95% likely to have a slowdown of 1.01x
- 99% likely to have a slowdown of 1.00x
