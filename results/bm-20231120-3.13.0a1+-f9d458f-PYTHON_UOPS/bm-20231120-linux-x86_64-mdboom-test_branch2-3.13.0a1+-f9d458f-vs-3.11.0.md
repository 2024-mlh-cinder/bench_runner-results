
# Results vs. 3.11.0

- fork: mdboom
- ref: test_branch2
- machine: linux-x86_64
- commit hash: f9d458f
- commit date: 2023-11-20
- overall geometric mean: 1.05x slower \*
- HPT reliability: 99.99%
- HPT 99th percentile: 1.02x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-linux-x86_64-mdboom-test_branch2-3.13.0a1+-f9d458f |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| 2to3           | 266 ms                                                 | 295 ms: 1.11x slower                                           |
| chameleon      | 6.86 ms                                                | 7.47 ms: 1.09x slower                                          |
| docutils       | 2.69 sec                                               | 2.75 sec: 1.02x slower                                         |
| tornado_http   | 97.7 ms                                                | 103 ms: 1.05x slower                                           |
| Geometric mean | (ref)                                                  | 1.07x slower                                                   |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                 | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-linux-x86_64-mdboom-test_branch2-3.13.0a1+-f9d458f |
|---------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| async_tree_none           | 532 ms                                                 | 464 ms: 1.15x faster                                           |
| async_tree_memoization    | 640 ms                                                 | 587 ms: 1.09x faster                                           |
| async_tree_io             | 1.31 sec                                               | 1.21 sec: 1.08x faster                                         |
| async_tree_io_tg          | 1.30 sec                                               | 1.24 sec: 1.05x faster                                         |
| async_tree_memoization_tg | 627 ms                                                 | 607 ms: 1.03x faster                                           |
| async_tree_none_tg        | 490 ms                                                 | 478 ms: 1.03x faster                                           |
| async_tree_cpu_io_mixed   | 750 ms                                                 | 733 ms: 1.02x faster                                           |
| Geometric mean            | (ref)                                                  | 1.06x faster                                                   |

Benchmark hidden because not significant (1): async_tree_cpu_io_mixed_tg

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-linux-x86_64-mdboom-test_branch2-3.13.0a1+-f9d458f |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| pidigits       | 190 ms                                                 | 197 ms: 1.04x slower                                           |
| float          | 78.9 ms                                                | 115 ms: 1.46x slower                                           |
| nbody          | 91.6 ms                                                | 141 ms: 1.54x slower                                           |
| Geometric mean | (ref)                                                  | 1.33x slower                                                   |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-linux-x86_64-mdboom-test_branch2-3.13.0a1+-f9d458f |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| regex_effbot   | 3.45 ms                                                | 3.69 ms: 1.07x slower                                          |
| regex_dna      | 204 ms                                                 | 218 ms: 1.07x slower                                           |
| regex_v8       | 22.9 ms                                                | 25.9 ms: 1.13x slower                                          |
| regex_compile  | 141 ms                                                 | 169 ms: 1.19x slower                                           |
| Geometric mean | (ref)                                                  | 1.11x slower                                                   |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-linux-x86_64-mdboom-test_branch2-3.13.0a1+-f9d458f |
|----------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| json_dumps           | 13.5 ms                                                | 10.6 ms: 1.27x faster                                          |
| json_loads           | 29.4 us                                                | 28.2 us: 1.04x faster                                          |
| pickle_pure_python   | 319 us                                                 | 307 us: 1.04x faster                                           |
| pickle_dict          | 34.8 us                                                | 33.7 us: 1.03x faster                                          |
| unpickle_list        | 5.22 us                                                | 5.09 us: 1.03x faster                                          |
| xml_etree_parse      | 163 ms                                                 | 159 ms: 1.02x faster                                           |
| unpickle_pure_python | 241 us                                                 | 252 us: 1.05x slower                                           |
| pickle               | 11.1 us                                                | 11.6 us: 1.05x slower                                          |
| unpickle             | 13.9 us                                                | 14.5 us: 1.05x slower                                          |
| xml_etree_iterparse  | 109 ms                                                 | 118 ms: 1.09x slower                                           |
| pickle_list          | 4.65 us                                                | 5.11 us: 1.10x slower                                          |
| xml_etree_process    | 56.5 ms                                                | 64.5 ms: 1.14x slower                                          |
| xml_etree_generate   | 80.4 ms                                                | 94.5 ms: 1.18x slower                                          |
| tomli_loads          | 2.31 sec                                               | 2.97 sec: 1.28x slower                                         |
| Geometric mean       | (ref)                                                  | 1.03x slower                                                   |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-linux-x86_64-mdboom-test_branch2-3.13.0a1+-f9d458f |
|------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| python_startup         | 8.69 ms                                                | 10.4 ms: 1.19x slower                                          |
| python_startup_no_site | 6.09 ms                                                | 9.00 ms: 1.48x slower                                          |
| Geometric mean         | (ref)                                                  | 1.33x slower                                                   |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-linux-x86_64-mdboom-test_branch2-3.13.0a1+-f9d458f |
|-----------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| mako      | 10.8 ms                                                | 17.2 ms: 1.59x slower                                          |

All benchmarks:
===============

| Benchmark                 | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-linux-x86_64-mdboom-test_branch2-3.13.0a1+-f9d458f |
|---------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| typing_runtime_protocols  | 521 us                                                 | 123 us: 4.24x faster                                           |
| generators                | 76.5 ms                                                | 29.4 ms: 2.60x faster                                          |
| asyncio_tcp               | 887 ms                                                 | 490 ms: 1.81x faster                                           |
| asyncio_tcp_ssl           | 3.13 sec                                               | 1.81 sec: 1.73x faster                                         |
| json_dumps                | 13.5 ms                                                | 10.6 ms: 1.27x faster                                          |
| mypy2                     | 427 ms                                                 | 359 ms: 1.19x faster                                           |
| coroutines                | 26.1 ms                                                | 22.2 ms: 1.18x faster                                          |
| async_tree_none           | 532 ms                                                 | 464 ms: 1.15x faster                                           |
| async_tree_memoization    | 640 ms                                                 | 587 ms: 1.09x faster                                           |
| async_tree_io             | 1.31 sec                                               | 1.21 sec: 1.08x faster                                         |
| richards_super            | 61.2 ms                                                | 58.3 ms: 1.05x faster                                          |
| async_tree_io_tg          | 1.30 sec                                               | 1.24 sec: 1.05x faster                                         |
| json_loads                | 29.4 us                                                | 28.2 us: 1.04x faster                                          |
| pickle_pure_python        | 319 us                                                 | 307 us: 1.04x faster                                           |
| async_tree_memoization_tg | 627 ms                                                 | 607 ms: 1.03x faster                                           |
| pickle_dict               | 34.8 us                                                | 33.7 us: 1.03x faster                                          |
| sympy_sum                 | 170 ms                                                 | 165 ms: 1.03x faster                                           |
| unpickle_list             | 5.22 us                                                | 5.09 us: 1.03x faster                                          |
| gc_traversal              | 3.90 ms                                                | 3.81 ms: 1.03x faster                                          |
| async_tree_none_tg        | 490 ms                                                 | 478 ms: 1.03x faster                                           |
| async_tree_cpu_io_mixed   | 750 ms                                                 | 733 ms: 1.02x faster                                           |
| xml_etree_parse           | 163 ms                                                 | 159 ms: 1.02x faster                                           |
| sqlglot_parse             | 1.43 ms                                                | 1.42 ms: 1.01x faster                                          |
| create_gc_cycles          | 1.48 ms                                                | 1.46 ms: 1.01x faster                                          |
| sqlglot_transpile         | 1.75 ms                                                | 1.74 ms: 1.01x faster                                          |
| logging_simple            | 6.24 us                                                | 6.20 us: 1.01x faster                                          |
| asyncio_websockets        | 556 ms                                                 | 552 ms: 1.01x faster                                           |
| logging_silent            | 108 ns                                                 | 109 ns: 1.01x slower                                           |
| deepcopy_reduce           | 3.14 us                                                | 3.16 us: 1.01x slower                                          |
| deepcopy                  | 360 us                                                 | 363 us: 1.01x slower                                           |
| dask                      | 365 ms                                                 | 370 ms: 1.01x slower                                           |
| sympy_str                 | 299 ms                                                 | 304 ms: 1.02x slower                                           |
| docutils                  | 2.69 sec                                               | 2.75 sec: 1.02x slower                                         |
| pathlib                   | 18.5 ms                                                | 18.9 ms: 1.02x slower                                          |
| logging_format            | 6.83 us                                                | 7.00 us: 1.03x slower                                          |
| sympy_expand              | 490 ms                                                 | 504 ms: 1.03x slower                                           |
| scimark_sor               | 121 ms                                                 | 126 ms: 1.04x slower                                           |
| pidigits                  | 190 ms                                                 | 197 ms: 1.04x slower                                           |
| sympy_integrate           | 21.4 ms                                                | 22.1 ms: 1.04x slower                                          |
| bench_thread_pool         | 833 us                                                 | 868 us: 1.04x slower                                           |
| mdp                       | 2.79 sec                                               | 2.91 sec: 1.05x slower                                         |
| unpickle_pure_python      | 241 us                                                 | 252 us: 1.05x slower                                           |
| pickle                    | 11.1 us                                                | 11.6 us: 1.05x slower                                          |
| richards                  | 48.9 ms                                                | 51.2 ms: 1.05x slower                                          |
| unpickle                  | 13.9 us                                                | 14.5 us: 1.05x slower                                          |
| tornado_http              | 97.7 ms                                                | 103 ms: 1.05x slower                                           |
| raytrace                  | 306 ms                                                 | 324 ms: 1.06x slower                                           |
| sqlglot_normalize         | 112 ms                                                 | 119 ms: 1.06x slower                                           |
| pycparser                 | 1.20 sec                                               | 1.27 sec: 1.06x slower                                         |
| regex_effbot              | 3.45 ms                                                | 3.69 ms: 1.07x slower                                          |
| regex_dna                 | 204 ms                                                 | 218 ms: 1.07x slower                                           |
| dulwich_log               | 64.9 ms                                                | 69.9 ms: 1.08x slower                                          |
| scimark_lu                | 112 ms                                                 | 122 ms: 1.08x slower                                           |
| chameleon                 | 6.86 ms                                                | 7.47 ms: 1.09x slower                                          |
| xml_etree_iterparse       | 109 ms                                                 | 118 ms: 1.09x slower                                           |
| deepcopy_memo             | 38.9 us                                                | 42.5 us: 1.09x slower                                          |
| pickle_list               | 4.65 us                                                | 5.11 us: 1.10x slower                                          |
| sqlglot_optimize          | 55.2 ms                                                | 60.7 ms: 1.10x slower                                          |
| 2to3                      | 266 ms                                                 | 295 ms: 1.11x slower                                           |
| comprehensions            | 23.6 us                                                | 26.3 us: 1.12x slower                                          |
| meteor_contest            | 109 ms                                                 | 123 ms: 1.13x slower                                           |
| regex_v8                  | 22.9 ms                                                | 25.9 ms: 1.13x slower                                          |
| xml_etree_process         | 56.5 ms                                                | 64.5 ms: 1.14x slower                                          |
| sqlite_synth              | 2.58 us                                                | 2.98 us: 1.15x slower                                          |
| pprint_safe_repr          | 743 ms                                                 | 861 ms: 1.16x slower                                           |
| chaos                     | 71.4 ms                                                | 82.8 ms: 1.16x slower                                          |
| coverage                  | 81.2 ms                                                | 94.7 ms: 1.17x slower                                          |
| pprint_pformat            | 1.53 sec                                               | 1.79 sec: 1.17x slower                                         |
| unpack_sequence           | 43.3 ns                                                | 50.8 ns: 1.17x slower                                          |
| xml_etree_generate        | 80.4 ms                                                | 94.5 ms: 1.18x slower                                          |
| regex_compile             | 141 ms                                                 | 169 ms: 1.19x slower                                           |
| python_startup            | 8.69 ms                                                | 10.4 ms: 1.19x slower                                          |
| go                        | 143 ms                                                 | 171 ms: 1.19x slower                                           |
| fannkuch                  | 410 ms                                                 | 490 ms: 1.19x slower                                           |
| crypto_pyaes              | 77.5 ms                                                | 93.9 ms: 1.21x slower                                          |
| async_generators          | 375 ms                                                 | 461 ms: 1.23x slower                                           |
| scimark_monte_carlo       | 71.8 ms                                                | 89.2 ms: 1.24x slower                                          |
| nqueens                   | 86.8 ms                                                | 110 ms: 1.26x slower                                           |
| tomli_loads               | 2.31 sec                                               | 2.97 sec: 1.28x slower                                         |
| telco                     | 6.72 ms                                                | 8.92 ms: 1.33x slower                                          |
| pyflate                   | 426 ms                                                 | 592 ms: 1.39x slower                                           |
| float                     | 78.9 ms                                                | 115 ms: 1.46x slower                                           |
| python_startup_no_site    | 6.09 ms                                                | 9.00 ms: 1.48x slower                                          |
| deltablue                 | 3.80 ms                                                | 5.73 ms: 1.51x slower                                          |
| hexiom                    | 6.74 ms                                                | 10.3 ms: 1.53x slower                                          |
| scimark_fft               | 342 ms                                                 | 525 ms: 1.53x slower                                           |
| nbody                     | 91.6 ms                                                | 141 ms: 1.54x slower                                           |
| scimark_sparse_mat_mult   | 4.80 ms                                                | 7.47 ms: 1.55x slower                                          |
| mako                      | 10.8 ms                                                | 17.2 ms: 1.59x slower                                          |
| spectral_norm             | 105 ms                                                 | 169 ms: 1.61x slower                                           |
| Geometric mean            | (ref)                                                  | 1.05x slower                                                   |

Benchmark hidden because not significant (3): async_tree_cpu_io_mixed_tg, bench_mp_pool, json
Ignored benchmarks (12) of results/bm-20221024-3.11.0-deaf509/bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift


# HPT report

- Reliability score: 99.99% likely to be slow
- 90% likely to have a slowdown of 1.03x
- 95% likely to have a slowdown of 1.03x
- 99% likely to have a slowdown of 1.02x
