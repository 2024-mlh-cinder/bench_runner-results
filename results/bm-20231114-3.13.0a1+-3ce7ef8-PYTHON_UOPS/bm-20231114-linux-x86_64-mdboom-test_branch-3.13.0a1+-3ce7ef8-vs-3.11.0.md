
# Results vs. 3.11.0

- fork: mdboom
- ref: test_branch
- machine: linux-x86_64
- commit hash: 3ce7ef8
- commit date: 2023-11-14
- overall geometric mean: 1.02x slower \*
- HPT reliability: 99.27%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231114-linux-x86_64-mdboom-test_branch-3.13.0a1+-3ce7ef8 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| 2to3           | 266 ms                                                 | 294 ms: 1.11x slower                                          |
| chameleon      | 6.86 ms                                                | 7.48 ms: 1.09x slower                                         |
| docutils       | 2.69 sec                                               | 2.74 sec: 1.02x slower                                        |
| tornado_http   | 97.7 ms                                                | 102 ms: 1.05x slower                                          |
| Geometric mean | (ref)                                                  | 1.07x slower                                                  |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                 | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231114-linux-x86_64-mdboom-test_branch-3.13.0a1+-3ce7ef8 |
|---------------------------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| async_tree_none           | 532 ms                                                 | 463 ms: 1.15x faster                                          |
| async_tree_memoization    | 640 ms                                                 | 590 ms: 1.08x faster                                          |
| async_tree_io             | 1.31 sec                                               | 1.23 sec: 1.06x faster                                        |
| async_tree_io_tg          | 1.30 sec                                               | 1.26 sec: 1.03x faster                                        |
| async_tree_memoization_tg | 627 ms                                                 | 610 ms: 1.03x faster                                          |
| async_tree_none_tg        | 490 ms                                                 | 477 ms: 1.03x faster                                          |
| async_tree_cpu_io_mixed   | 750 ms                                                 | 742 ms: 1.01x faster                                          |
| Geometric mean            | (ref)                                                  | 1.05x faster                                                  |

Benchmark hidden because not significant (1): async_tree_cpu_io_mixed_tg

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231114-linux-x86_64-mdboom-test_branch-3.13.0a1+-3ce7ef8 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| pidigits       | 190 ms                                                 | 188 ms: 1.01x faster                                          |
| float          | 78.9 ms                                                | 102 ms: 1.29x slower                                          |
| nbody          | 91.6 ms                                                | 122 ms: 1.34x slower                                          |
| Geometric mean | (ref)                                                  | 1.20x slower                                                  |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231114-linux-x86_64-mdboom-test_branch-3.13.0a1+-3ce7ef8 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| regex_effbot   | 3.45 ms                                                | 3.50 ms: 1.01x slower                                         |
| regex_dna      | 204 ms                                                 | 213 ms: 1.05x slower                                          |
| regex_v8       | 22.9 ms                                                | 24.8 ms: 1.08x slower                                         |
| regex_compile  | 141 ms                                                 | 166 ms: 1.18x slower                                          |
| Geometric mean | (ref)                                                  | 1.08x slower                                                  |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231114-linux-x86_64-mdboom-test_branch-3.13.0a1+-3ce7ef8 |
|----------------------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| json_dumps           | 13.5 ms                                                | 10.5 ms: 1.28x faster                                         |
| pickle_dict          | 34.8 us                                                | 32.4 us: 1.08x faster                                         |
| json_loads           | 29.4 us                                                | 28.1 us: 1.05x faster                                         |
| pickle_pure_python   | 319 us                                                 | 308 us: 1.04x faster                                          |
| xml_etree_parse      | 163 ms                                                 | 159 ms: 1.02x faster                                          |
| pickle               | 11.1 us                                                | 11.0 us: 1.01x faster                                         |
| unpickle_pure_python | 241 us                                                 | 242 us: 1.00x slower                                          |
| unpickle_list        | 5.22 us                                                | 5.33 us: 1.02x slower                                         |
| xml_etree_iterparse  | 109 ms                                                 | 114 ms: 1.05x slower                                          |
| pickle_list          | 4.65 us                                                | 4.92 us: 1.06x slower                                         |
| xml_etree_process    | 56.5 ms                                                | 59.9 ms: 1.06x slower                                         |
| xml_etree_generate   | 80.4 ms                                                | 87.9 ms: 1.09x slower                                         |
| unpickle             | 13.9 us                                                | 15.4 us: 1.11x slower                                         |
| tomli_loads          | 2.31 sec                                               | 3.07 sec: 1.32x slower                                        |
| Geometric mean       | (ref)                                                  | 1.02x slower                                                  |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231114-linux-x86_64-mdboom-test_branch-3.13.0a1+-3ce7ef8 |
|------------------------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| python_startup         | 8.69 ms                                                | 10.3 ms: 1.19x slower                                         |
| python_startup_no_site | 6.09 ms                                                | 9.05 ms: 1.48x slower                                         |
| Geometric mean         | (ref)                                                  | 1.33x slower                                                  |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231114-linux-x86_64-mdboom-test_branch-3.13.0a1+-3ce7ef8 |
|-----------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| mako      | 10.8 ms                                                | 14.5 ms: 1.34x slower                                         |

All benchmarks:
===============

| Benchmark                 | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231114-linux-x86_64-mdboom-test_branch-3.13.0a1+-3ce7ef8 |
|---------------------------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| typing_runtime_protocols  | 521 us                                                 | 127 us: 4.09x faster                                          |
| generators                | 76.5 ms                                                | 29.2 ms: 2.62x faster                                         |
| asyncio_tcp               | 887 ms                                                 | 494 ms: 1.80x faster                                          |
| asyncio_tcp_ssl           | 3.13 sec                                               | 1.81 sec: 1.73x faster                                        |
| json_dumps                | 13.5 ms                                                | 10.5 ms: 1.28x faster                                         |
| mypy2                     | 427 ms                                                 | 358 ms: 1.19x faster                                          |
| coroutines                | 26.1 ms                                                | 22.0 ms: 1.19x faster                                         |
| async_tree_none           | 532 ms                                                 | 463 ms: 1.15x faster                                          |
| sympy_sum                 | 170 ms                                                 | 155 ms: 1.10x faster                                          |
| async_tree_memoization    | 640 ms                                                 | 590 ms: 1.08x faster                                          |
| pickle_dict               | 34.8 us                                                | 32.4 us: 1.08x faster                                         |
| async_tree_io             | 1.31 sec                                               | 1.23 sec: 1.06x faster                                        |
| sqlglot_parse             | 1.43 ms                                                | 1.36 ms: 1.06x faster                                         |
| json_loads                | 29.4 us                                                | 28.1 us: 1.05x faster                                         |
| sqlglot_transpile         | 1.75 ms                                                | 1.68 ms: 1.04x faster                                         |
| sympy_str                 | 299 ms                                                 | 288 ms: 1.04x faster                                          |
| pickle_pure_python        | 319 us                                                 | 308 us: 1.04x faster                                          |
| async_tree_io_tg          | 1.30 sec                                               | 1.26 sec: 1.03x faster                                        |
| sqlglot_normalize         | 112 ms                                                 | 109 ms: 1.03x faster                                          |
| async_tree_memoization_tg | 627 ms                                                 | 610 ms: 1.03x faster                                          |
| async_tree_none_tg        | 490 ms                                                 | 477 ms: 1.03x faster                                          |
| richards_super            | 61.2 ms                                                | 59.7 ms: 1.03x faster                                         |
| xml_etree_parse           | 163 ms                                                 | 159 ms: 1.02x faster                                          |
| mdp                       | 2.79 sec                                               | 2.73 sec: 1.02x faster                                        |
| json                      | 5.24 ms                                                | 5.15 ms: 1.02x faster                                         |
| deepcopy                  | 360 us                                                 | 355 us: 1.01x faster                                          |
| logging_silent            | 108 ns                                                 | 107 ns: 1.01x faster                                          |
| pidigits                  | 190 ms                                                 | 188 ms: 1.01x faster                                          |
| async_tree_cpu_io_mixed   | 750 ms                                                 | 742 ms: 1.01x faster                                          |
| gc_traversal              | 3.90 ms                                                | 3.87 ms: 1.01x faster                                         |
| asyncio_websockets        | 556 ms                                                 | 552 ms: 1.01x faster                                          |
| pickle                    | 11.1 us                                                | 11.0 us: 1.01x faster                                         |
| sqlglot_optimize          | 55.2 ms                                                | 54.9 ms: 1.00x faster                                         |
| raytrace                  | 306 ms                                                 | 308 ms: 1.00x slower                                          |
| unpickle_pure_python      | 241 us                                                 | 242 us: 1.00x slower                                          |
| logging_simple            | 6.24 us                                                | 6.29 us: 1.01x slower                                         |
| sympy_integrate           | 21.4 ms                                                | 21.6 ms: 1.01x slower                                         |
| regex_effbot              | 3.45 ms                                                | 3.50 ms: 1.01x slower                                         |
| docutils                  | 2.69 sec                                               | 2.74 sec: 1.02x slower                                        |
| unpickle_list             | 5.22 us                                                | 5.33 us: 1.02x slower                                         |
| pathlib                   | 18.5 ms                                                | 18.9 ms: 1.02x slower                                         |
| bench_thread_pool         | 833 us                                                 | 858 us: 1.03x slower                                          |
| pycparser                 | 1.20 sec                                               | 1.23 sec: 1.03x slower                                        |
| logging_format            | 6.83 us                                                | 7.11 us: 1.04x slower                                         |
| regex_dna                 | 204 ms                                                 | 213 ms: 1.05x slower                                          |
| xml_etree_iterparse       | 109 ms                                                 | 114 ms: 1.05x slower                                          |
| tornado_http              | 97.7 ms                                                | 102 ms: 1.05x slower                                          |
| scimark_sor               | 121 ms                                                 | 128 ms: 1.06x slower                                          |
| pickle_list               | 4.65 us                                                | 4.92 us: 1.06x slower                                         |
| chaos                     | 71.4 ms                                                | 75.6 ms: 1.06x slower                                         |
| xml_etree_process         | 56.5 ms                                                | 59.9 ms: 1.06x slower                                         |
| dulwich_log               | 64.9 ms                                                | 69.3 ms: 1.07x slower                                         |
| meteor_contest            | 109 ms                                                 | 117 ms: 1.07x slower                                          |
| spectral_norm             | 105 ms                                                 | 113 ms: 1.07x slower                                          |
| scimark_lu                | 112 ms                                                 | 121 ms: 1.07x slower                                          |
| richards                  | 48.9 ms                                                | 52.5 ms: 1.07x slower                                         |
| deepcopy_memo             | 38.9 us                                                | 41.8 us: 1.07x slower                                         |
| regex_v8                  | 22.9 ms                                                | 24.8 ms: 1.08x slower                                         |
| pprint_safe_repr          | 743 ms                                                 | 808 ms: 1.09x slower                                          |
| comprehensions            | 23.6 us                                                | 25.7 us: 1.09x slower                                         |
| chameleon                 | 6.86 ms                                                | 7.48 ms: 1.09x slower                                         |
| xml_etree_generate        | 80.4 ms                                                | 87.9 ms: 1.09x slower                                         |
| pprint_pformat            | 1.53 sec                                               | 1.67 sec: 1.10x slower                                        |
| unpack_sequence           | 43.3 ns                                                | 47.5 ns: 1.10x slower                                         |
| 2to3                      | 266 ms                                                 | 294 ms: 1.11x slower                                          |
| sqlite_synth              | 2.58 us                                                | 2.85 us: 1.11x slower                                         |
| crypto_pyaes              | 77.5 ms                                                | 85.7 ms: 1.11x slower                                         |
| unpickle                  | 13.9 us                                                | 15.4 us: 1.11x slower                                         |
| scimark_monte_carlo       | 71.8 ms                                                | 80.5 ms: 1.12x slower                                         |
| coverage                  | 81.2 ms                                                | 95.6 ms: 1.18x slower                                         |
| regex_compile             | 141 ms                                                 | 166 ms: 1.18x slower                                          |
| python_startup            | 8.69 ms                                                | 10.3 ms: 1.19x slower                                         |
| go                        | 143 ms                                                 | 171 ms: 1.20x slower                                          |
| fannkuch                  | 410 ms                                                 | 492 ms: 1.20x slower                                          |
| nqueens                   | 86.8 ms                                                | 105 ms: 1.20x slower                                          |
| async_generators          | 375 ms                                                 | 462 ms: 1.23x slower                                          |
| scimark_fft               | 342 ms                                                 | 432 ms: 1.26x slower                                          |
| float                     | 78.9 ms                                                | 102 ms: 1.29x slower                                          |
| pyflate                   | 426 ms                                                 | 555 ms: 1.30x slower                                          |
| telco                     | 6.72 ms                                                | 8.76 ms: 1.30x slower                                         |
| tomli_loads               | 2.31 sec                                               | 3.07 sec: 1.32x slower                                        |
| nbody                     | 91.6 ms                                                | 122 ms: 1.34x slower                                          |
| mako                      | 10.8 ms                                                | 14.5 ms: 1.34x slower                                         |
| scimark_sparse_mat_mult   | 4.80 ms                                                | 6.56 ms: 1.37x slower                                         |
| deltablue                 | 3.80 ms                                                | 5.20 ms: 1.37x slower                                         |
| python_startup_no_site    | 6.09 ms                                                | 9.05 ms: 1.48x slower                                         |
| hexiom                    | 6.74 ms                                                | 10.2 ms: 1.52x slower                                         |
| Geometric mean            | (ref)                                                  | 1.02x slower                                                  |

Benchmark hidden because not significant (5): sympy_expand, deepcopy_reduce, bench_mp_pool, create_gc_cycles, async_tree_cpu_io_mixed_tg
Ignored benchmarks (13) of results/bm-20221024-3.11.0-deaf509/bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift


# HPT report

- Reliability score: 99.27% likely to be slow
- 90% likely to have a slowdown of 1.01x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
