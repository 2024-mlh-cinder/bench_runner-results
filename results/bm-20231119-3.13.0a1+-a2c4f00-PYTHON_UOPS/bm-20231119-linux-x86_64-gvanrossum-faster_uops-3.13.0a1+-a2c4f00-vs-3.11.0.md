
# Results vs. 3.11.0

- fork: gvanrossum
- ref: faster_uops
- machine: linux-x86_64
- commit hash: a2c4f00
- commit date: 2023-11-19
- overall geometric mean: 1.03x slower \*
- HPT reliability: 99.94%
- HPT 99th percentile: 1.01x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231119-linux-x86_64-gvanrossum-faster_uops-3.13.0a1+-a2c4f00 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------:|
| 2to3           | 266 ms                                                 | 290 ms: 1.09x slower                                              |
| chameleon      | 6.86 ms                                                | 7.36 ms: 1.07x slower                                             |
| docutils       | 2.69 sec                                               | 2.73 sec: 1.01x slower                                            |
| tornado_http   | 97.7 ms                                                | 103 ms: 1.05x slower                                              |
| Geometric mean | (ref)                                                  | 1.06x slower                                                      |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                 | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231119-linux-x86_64-gvanrossum-faster_uops-3.13.0a1+-a2c4f00 |
|---------------------------|:------------------------------------------------------:|:-----------------------------------------------------------------:|
| async_tree_none           | 532 ms                                                 | 460 ms: 1.16x faster                                              |
| async_tree_memoization    | 640 ms                                                 | 587 ms: 1.09x faster                                              |
| async_tree_io             | 1.31 sec                                               | 1.22 sec: 1.07x faster                                            |
| async_tree_io_tg          | 1.30 sec                                               | 1.26 sec: 1.04x faster                                            |
| async_tree_none_tg        | 490 ms                                                 | 477 ms: 1.03x faster                                              |
| async_tree_cpu_io_mixed   | 750 ms                                                 | 731 ms: 1.03x faster                                              |
| async_tree_memoization_tg | 627 ms                                                 | 614 ms: 1.02x faster                                              |
| Geometric mean            | (ref)                                                  | 1.05x faster                                                      |

Benchmark hidden because not significant (1): async_tree_cpu_io_mixed_tg

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231119-linux-x86_64-gvanrossum-faster_uops-3.13.0a1+-a2c4f00 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------:|
| pidigits       | 190 ms                                                 | 190 ms: 1.00x faster                                              |
| float          | 78.9 ms                                                | 103 ms: 1.30x slower                                              |
| nbody          | 91.6 ms                                                | 138 ms: 1.51x slower                                              |
| Geometric mean | (ref)                                                  | 1.25x slower                                                      |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231119-linux-x86_64-gvanrossum-faster_uops-3.13.0a1+-a2c4f00 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------:|
| regex_effbot   | 3.45 ms                                                | 3.52 ms: 1.02x slower                                             |
| regex_v8       | 22.9 ms                                                | 24.9 ms: 1.09x slower                                             |
| regex_dna      | 204 ms                                                 | 222 ms: 1.09x slower                                              |
| regex_compile  | 141 ms                                                 | 161 ms: 1.14x slower                                              |
| Geometric mean | (ref)                                                  | 1.08x slower                                                      |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231119-linux-x86_64-gvanrossum-faster_uops-3.13.0a1+-a2c4f00 |
|----------------------|:------------------------------------------------------:|:-----------------------------------------------------------------:|
| json_dumps           | 13.5 ms                                                | 10.5 ms: 1.28x faster                                             |
| json_loads           | 29.4 us                                                | 28.2 us: 1.04x faster                                             |
| unpickle_list        | 5.22 us                                                | 5.03 us: 1.04x faster                                             |
| pickle_pure_python   | 319 us                                                 | 308 us: 1.03x faster                                              |
| xml_etree_parse      | 163 ms                                                 | 159 ms: 1.02x faster                                              |
| pickle_dict          | 34.8 us                                                | 34.5 us: 1.01x faster                                             |
| unpickle_pure_python | 241 us                                                 | 245 us: 1.02x slower                                              |
| xml_etree_iterparse  | 109 ms                                                 | 114 ms: 1.05x slower                                              |
| pickle               | 11.1 us                                                | 11.6 us: 1.05x slower                                             |
| unpickle             | 13.9 us                                                | 15.0 us: 1.08x slower                                             |
| pickle_list          | 4.65 us                                                | 5.11 us: 1.10x slower                                             |
| xml_etree_process    | 56.5 ms                                                | 62.9 ms: 1.11x slower                                             |
| xml_etree_generate   | 80.4 ms                                                | 91.3 ms: 1.13x slower                                             |
| tomli_loads          | 2.31 sec                                               | 2.77 sec: 1.19x slower                                            |
| Geometric mean       | (ref)                                                  | 1.02x slower                                                      |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231119-linux-x86_64-gvanrossum-faster_uops-3.13.0a1+-a2c4f00 |
|------------------------|:------------------------------------------------------:|:-----------------------------------------------------------------:|
| python_startup         | 8.69 ms                                                | 10.5 ms: 1.20x slower                                             |
| python_startup_no_site | 6.09 ms                                                | 9.10 ms: 1.49x slower                                             |
| Geometric mean         | (ref)                                                  | 1.34x slower                                                      |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231119-linux-x86_64-gvanrossum-faster_uops-3.13.0a1+-a2c4f00 |
|-----------|:------------------------------------------------------:|:-----------------------------------------------------------------:|
| mako      | 10.8 ms                                                | 15.1 ms: 1.39x slower                                             |

All benchmarks:
===============

| Benchmark                 | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231119-linux-x86_64-gvanrossum-faster_uops-3.13.0a1+-a2c4f00 |
|---------------------------|:------------------------------------------------------:|:-----------------------------------------------------------------:|
| typing_runtime_protocols  | 521 us                                                 | 126 us: 4.15x faster                                              |
| generators                | 76.5 ms                                                | 29.8 ms: 2.57x faster                                             |
| asyncio_tcp               | 887 ms                                                 | 499 ms: 1.78x faster                                              |
| asyncio_tcp_ssl           | 3.13 sec                                               | 1.81 sec: 1.73x faster                                            |
| json_dumps                | 13.5 ms                                                | 10.5 ms: 1.28x faster                                             |
| mypy2                     | 427 ms                                                 | 358 ms: 1.19x faster                                              |
| coroutines                | 26.1 ms                                                | 22.3 ms: 1.17x faster                                             |
| async_tree_none           | 532 ms                                                 | 460 ms: 1.16x faster                                              |
| async_tree_memoization    | 640 ms                                                 | 587 ms: 1.09x faster                                              |
| gc_traversal              | 3.90 ms                                                | 3.65 ms: 1.07x faster                                             |
| async_tree_io             | 1.31 sec                                               | 1.22 sec: 1.07x faster                                            |
| richards_super            | 61.2 ms                                                | 58.3 ms: 1.05x faster                                             |
| json_loads                | 29.4 us                                                | 28.2 us: 1.04x faster                                             |
| sympy_sum                 | 170 ms                                                 | 163 ms: 1.04x faster                                              |
| unpickle_list             | 5.22 us                                                | 5.03 us: 1.04x faster                                             |
| async_tree_io_tg          | 1.30 sec                                               | 1.26 sec: 1.04x faster                                            |
| pickle_pure_python        | 319 us                                                 | 308 us: 1.03x faster                                              |
| sqlglot_parse             | 1.43 ms                                                | 1.39 ms: 1.03x faster                                             |
| async_tree_none_tg        | 490 ms                                                 | 477 ms: 1.03x faster                                              |
| async_tree_cpu_io_mixed   | 750 ms                                                 | 731 ms: 1.03x faster                                              |
| xml_etree_parse           | 163 ms                                                 | 159 ms: 1.02x faster                                              |
| async_tree_memoization_tg | 627 ms                                                 | 614 ms: 1.02x faster                                              |
| sqlglot_transpile         | 1.75 ms                                                | 1.72 ms: 1.02x faster                                             |
| comprehensions            | 23.6 us                                                | 23.3 us: 1.01x faster                                             |
| pickle_dict               | 34.8 us                                                | 34.5 us: 1.01x faster                                             |
| create_gc_cycles          | 1.48 ms                                                | 1.46 ms: 1.01x faster                                             |
| asyncio_websockets        | 556 ms                                                 | 553 ms: 1.01x faster                                              |
| logging_simple            | 6.24 us                                                | 6.21 us: 1.01x faster                                             |
| pidigits                  | 190 ms                                                 | 190 ms: 1.00x faster                                              |
| deepcopy                  | 360 us                                                 | 363 us: 1.01x slower                                              |
| mdp                       | 2.79 sec                                               | 2.82 sec: 1.01x slower                                            |
| pathlib                   | 18.5 ms                                                | 18.7 ms: 1.01x slower                                             |
| sympy_expand              | 490 ms                                                 | 496 ms: 1.01x slower                                              |
| docutils                  | 2.69 sec                                               | 2.73 sec: 1.01x slower                                            |
| dask                      | 365 ms                                                 | 371 ms: 1.02x slower                                              |
| unpickle_pure_python      | 241 us                                                 | 245 us: 1.02x slower                                              |
| sympy_integrate           | 21.4 ms                                                | 21.7 ms: 1.02x slower                                             |
| pycparser                 | 1.20 sec                                               | 1.22 sec: 1.02x slower                                            |
| regex_effbot              | 3.45 ms                                                | 3.52 ms: 1.02x slower                                             |
| logging_format            | 6.83 us                                                | 6.98 us: 1.02x slower                                             |
| logging_silent            | 108 ns                                                 | 111 ns: 1.02x slower                                              |
| bench_thread_pool         | 833 us                                                 | 861 us: 1.03x slower                                              |
| raytrace                  | 306 ms                                                 | 317 ms: 1.03x slower                                              |
| scimark_sor               | 121 ms                                                 | 126 ms: 1.04x slower                                              |
| sqlglot_normalize         | 112 ms                                                 | 117 ms: 1.04x slower                                              |
| richards                  | 48.9 ms                                                | 51.0 ms: 1.04x slower                                             |
| xml_etree_iterparse       | 109 ms                                                 | 114 ms: 1.05x slower                                              |
| pickle                    | 11.1 us                                                | 11.6 us: 1.05x slower                                             |
| tornado_http              | 97.7 ms                                                | 103 ms: 1.05x slower                                              |
| deepcopy_memo             | 38.9 us                                                | 41.6 us: 1.07x slower                                             |
| meteor_contest            | 109 ms                                                 | 117 ms: 1.07x slower                                              |
| chameleon                 | 6.86 ms                                                | 7.36 ms: 1.07x slower                                             |
| dulwich_log               | 64.9 ms                                                | 69.9 ms: 1.08x slower                                             |
| scimark_lu                | 112 ms                                                 | 121 ms: 1.08x slower                                              |
| sqlglot_optimize          | 55.2 ms                                                | 59.5 ms: 1.08x slower                                             |
| unpickle                  | 13.9 us                                                | 15.0 us: 1.08x slower                                             |
| regex_v8                  | 22.9 ms                                                | 24.9 ms: 1.09x slower                                             |
| 2to3                      | 266 ms                                                 | 290 ms: 1.09x slower                                              |
| regex_dna                 | 204 ms                                                 | 222 ms: 1.09x slower                                              |
| chaos                     | 71.4 ms                                                | 78.0 ms: 1.09x slower                                             |
| pickle_list               | 4.65 us                                                | 5.11 us: 1.10x slower                                             |
| xml_etree_process         | 56.5 ms                                                | 62.9 ms: 1.11x slower                                             |
| fannkuch                  | 410 ms                                                 | 463 ms: 1.13x slower                                              |
| nqueens                   | 86.8 ms                                                | 98.3 ms: 1.13x slower                                             |
| sqlite_synth              | 2.58 us                                                | 2.92 us: 1.13x slower                                             |
| crypto_pyaes              | 77.5 ms                                                | 87.8 ms: 1.13x slower                                             |
| xml_etree_generate        | 80.4 ms                                                | 91.3 ms: 1.13x slower                                             |
| regex_compile             | 141 ms                                                 | 161 ms: 1.14x slower                                              |
| pprint_safe_repr          | 743 ms                                                 | 853 ms: 1.15x slower                                              |
| go                        | 143 ms                                                 | 164 ms: 1.15x slower                                              |
| pprint_pformat            | 1.53 sec                                               | 1.78 sec: 1.17x slower                                            |
| coverage                  | 81.2 ms                                                | 95.2 ms: 1.17x slower                                             |
| tomli_loads               | 2.31 sec                                               | 2.77 sec: 1.19x slower                                            |
| python_startup            | 8.69 ms                                                | 10.5 ms: 1.20x slower                                             |
| unpack_sequence           | 43.3 ns                                                | 52.6 ns: 1.21x slower                                             |
| async_generators          | 375 ms                                                 | 458 ms: 1.22x slower                                              |
| scimark_monte_carlo       | 71.8 ms                                                | 88.6 ms: 1.24x slower                                             |
| pyflate                   | 426 ms                                                 | 546 ms: 1.28x slower                                              |
| telco                     | 6.72 ms                                                | 8.70 ms: 1.29x slower                                             |
| float                     | 78.9 ms                                                | 103 ms: 1.30x slower                                              |
| scimark_sparse_mat_mult   | 4.80 ms                                                | 6.37 ms: 1.33x slower                                             |
| deltablue                 | 3.80 ms                                                | 5.11 ms: 1.34x slower                                             |
| hexiom                    | 6.74 ms                                                | 9.16 ms: 1.36x slower                                             |
| mako                      | 10.8 ms                                                | 15.1 ms: 1.39x slower                                             |
| spectral_norm             | 105 ms                                                 | 149 ms: 1.42x slower                                              |
| scimark_fft               | 342 ms                                                 | 488 ms: 1.43x slower                                              |
| python_startup_no_site    | 6.09 ms                                                | 9.10 ms: 1.49x slower                                             |
| nbody                     | 91.6 ms                                                | 138 ms: 1.51x slower                                              |
| Geometric mean            | (ref)                                                  | 1.03x slower                                                      |

Benchmark hidden because not significant (5): async_tree_cpu_io_mixed_tg, json, bench_mp_pool, deepcopy_reduce, sympy_str
Ignored benchmarks (12) of results/bm-20221024-3.11.0-deaf509/bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift


# HPT report

- Reliability score: 99.94% likely to be slow
- 90% likely to have a slowdown of 1.01x
- 95% likely to have a slowdown of 1.01x
- 99% likely to have a slowdown of 1.01x
