
# Results vs. 3.11.0

- fork: faster-cpython
- ref: faster_tier_2_interp
- machine: linux-x86_64
- commit hash: 4830ad2
- commit date: 2023-11-09
- overall geometric mean: 1.01x slower \*
- HPT reliability: 98.26%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231109-linux-x86_64-faster%2dcpython-faster_tier_2_interp-3.13.0a1+-4830ad2 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| 2to3           | 266 ms                                                 | 287 ms: 1.08x slower                                                             |
| chameleon      | 6.86 ms                                                | 7.53 ms: 1.10x slower                                                            |
| docutils       | 2.69 sec                                               | 2.71 sec: 1.01x slower                                                           |
| tornado_http   | 97.7 ms                                                | 99.3 ms: 1.02x slower                                                            |
| Geometric mean | (ref)                                                  | 1.05x slower                                                                     |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                 | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231109-linux-x86_64-faster%2dcpython-faster_tier_2_interp-3.13.0a1+-4830ad2 |
|---------------------------|:------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| async_tree_none           | 532 ms                                                 | 454 ms: 1.17x faster                                                             |
| async_tree_memoization    | 640 ms                                                 | 581 ms: 1.10x faster                                                             |
| async_tree_io             | 1.31 sec                                               | 1.20 sec: 1.09x faster                                                           |
| async_tree_io_tg          | 1.30 sec                                               | 1.24 sec: 1.05x faster                                                           |
| async_tree_none_tg        | 490 ms                                                 | 467 ms: 1.05x faster                                                             |
| async_tree_memoization_tg | 627 ms                                                 | 609 ms: 1.03x faster                                                             |
| async_tree_cpu_io_mixed   | 750 ms                                                 | 733 ms: 1.02x faster                                                             |
| Geometric mean            | (ref)                                                  | 1.06x faster                                                                     |

Benchmark hidden because not significant (1): async_tree_cpu_io_mixed_tg

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231109-linux-x86_64-faster%2dcpython-faster_tier_2_interp-3.13.0a1+-4830ad2 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| pidigits       | 190 ms                                                 | 188 ms: 1.01x faster                                                             |
| float          | 78.9 ms                                                | 101 ms: 1.28x slower                                                             |
| nbody          | 91.6 ms                                                | 127 ms: 1.39x slower                                                             |
| Geometric mean | (ref)                                                  | 1.21x slower                                                                     |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231109-linux-x86_64-faster%2dcpython-faster_tier_2_interp-3.13.0a1+-4830ad2 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| regex_effbot   | 3.45 ms                                                | 3.59 ms: 1.04x slower                                                            |
| regex_v8       | 22.9 ms                                                | 24.2 ms: 1.05x slower                                                            |
| regex_dna      | 204 ms                                                 | 219 ms: 1.07x slower                                                             |
| regex_compile  | 141 ms                                                 | 158 ms: 1.12x slower                                                             |
| Geometric mean | (ref)                                                  | 1.07x slower                                                                     |

Benchmarks with tag 'serialize':
================================

| Benchmark           | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231109-linux-x86_64-faster%2dcpython-faster_tier_2_interp-3.13.0a1+-4830ad2 |
|---------------------|:------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| json_dumps          | 13.5 ms                                                | 10.8 ms: 1.24x faster                                                            |
| json_loads          | 29.4 us                                                | 27.6 us: 1.07x faster                                                            |
| xml_etree_parse     | 163 ms                                                 | 157 ms: 1.03x faster                                                             |
| pickle_pure_python  | 319 us                                                 | 310 us: 1.03x faster                                                             |
| pickle_dict         | 34.8 us                                                | 34.5 us: 1.01x faster                                                            |
| xml_etree_iterparse | 109 ms                                                 | 110 ms: 1.02x slower                                                             |
| unpickle_list       | 5.22 us                                                | 5.34 us: 1.02x slower                                                            |
| pickle              | 11.1 us                                                | 11.7 us: 1.06x slower                                                            |
| xml_etree_process   | 56.5 ms                                                | 60.2 ms: 1.07x slower                                                            |
| unpickle            | 13.9 us                                                | 14.8 us: 1.07x slower                                                            |
| pickle_list         | 4.65 us                                                | 5.03 us: 1.08x slower                                                            |
| xml_etree_generate  | 80.4 ms                                                | 87.9 ms: 1.09x slower                                                            |
| tomli_loads         | 2.31 sec                                               | 2.66 sec: 1.15x slower                                                           |
| Geometric mean      | (ref)                                                  | 1.01x slower                                                                     |

Benchmark hidden because not significant (1): unpickle_pure_python

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231109-linux-x86_64-faster%2dcpython-faster_tier_2_interp-3.13.0a1+-4830ad2 |
|------------------------|:------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| python_startup         | 8.69 ms                                                | 10.3 ms: 1.19x slower                                                            |
| python_startup_no_site | 6.09 ms                                                | 9.03 ms: 1.48x slower                                                            |
| Geometric mean         | (ref)                                                  | 1.33x slower                                                                     |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231109-linux-x86_64-faster%2dcpython-faster_tier_2_interp-3.13.0a1+-4830ad2 |
|-----------|:------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| mako      | 10.8 ms                                                | 14.2 ms: 1.31x slower                                                            |

All benchmarks:
===============

| Benchmark                 | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231109-linux-x86_64-faster%2dcpython-faster_tier_2_interp-3.13.0a1+-4830ad2 |
|---------------------------|:------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| typing_runtime_protocols  | 521 us                                                 | 126 us: 4.14x faster                                                             |
| generators                | 76.5 ms                                                | 30.9 ms: 2.47x faster                                                            |
| asyncio_tcp               | 887 ms                                                 | 494 ms: 1.79x faster                                                             |
| asyncio_tcp_ssl           | 3.13 sec                                               | 1.81 sec: 1.73x faster                                                           |
| json_dumps                | 13.5 ms                                                | 10.8 ms: 1.24x faster                                                            |
| mypy2                     | 427 ms                                                 | 356 ms: 1.20x faster                                                             |
| coroutines                | 26.1 ms                                                | 22.1 ms: 1.19x faster                                                            |
| async_tree_none           | 532 ms                                                 | 454 ms: 1.17x faster                                                             |
| async_tree_memoization    | 640 ms                                                 | 581 ms: 1.10x faster                                                             |
| sympy_sum                 | 170 ms                                                 | 155 ms: 1.10x faster                                                             |
| async_tree_io             | 1.31 sec                                               | 1.20 sec: 1.09x faster                                                           |
| json_loads                | 29.4 us                                                | 27.6 us: 1.07x faster                                                            |
| sqlglot_parse             | 1.43 ms                                                | 1.35 ms: 1.07x faster                                                            |
| sympy_str                 | 299 ms                                                 | 283 ms: 1.06x faster                                                             |
| async_tree_io_tg          | 1.30 sec                                               | 1.24 sec: 1.05x faster                                                           |
| richards_super            | 61.2 ms                                                | 58.2 ms: 1.05x faster                                                            |
| sqlglot_transpile         | 1.75 ms                                                | 1.67 ms: 1.05x faster                                                            |
| async_tree_none_tg        | 490 ms                                                 | 467 ms: 1.05x faster                                                             |
| comprehensions            | 23.6 us                                                | 22.6 us: 1.04x faster                                                            |
| gc_traversal              | 3.90 ms                                                | 3.77 ms: 1.04x faster                                                            |
| xml_etree_parse           | 163 ms                                                 | 157 ms: 1.03x faster                                                             |
| async_tree_memoization_tg | 627 ms                                                 | 609 ms: 1.03x faster                                                             |
| pickle_pure_python        | 319 us                                                 | 310 us: 1.03x faster                                                             |
| sqlglot_normalize         | 112 ms                                                 | 109 ms: 1.03x faster                                                             |
| async_tree_cpu_io_mixed   | 750 ms                                                 | 733 ms: 1.02x faster                                                             |
| sympy_expand              | 490 ms                                                 | 480 ms: 1.02x faster                                                             |
| pidigits                  | 190 ms                                                 | 188 ms: 1.01x faster                                                             |
| create_gc_cycles          | 1.48 ms                                                | 1.46 ms: 1.01x faster                                                            |
| pickle_dict               | 34.8 us                                                | 34.5 us: 1.01x faster                                                            |
| sympy_integrate           | 21.4 ms                                                | 21.2 ms: 1.01x faster                                                            |
| raytrace                  | 306 ms                                                 | 304 ms: 1.01x faster                                                             |
| asyncio_websockets        | 556 ms                                                 | 552 ms: 1.01x faster                                                             |
| docutils                  | 2.69 sec                                               | 2.71 sec: 1.01x slower                                                           |
| logging_format            | 6.83 us                                                | 6.94 us: 1.02x slower                                                            |
| tornado_http              | 97.7 ms                                                | 99.3 ms: 1.02x slower                                                            |
| xml_etree_iterparse       | 109 ms                                                 | 110 ms: 1.02x slower                                                             |
| deepcopy_reduce           | 3.14 us                                                | 3.20 us: 1.02x slower                                                            |
| unpickle_list             | 5.22 us                                                | 5.34 us: 1.02x slower                                                            |
| mdp                       | 2.79 sec                                               | 2.87 sec: 1.03x slower                                                           |
| bench_thread_pool         | 833 us                                                 | 859 us: 1.03x slower                                                             |
| chaos                     | 71.4 ms                                                | 74.0 ms: 1.04x slower                                                            |
| unpack_sequence           | 43.3 ns                                                | 45.0 ns: 1.04x slower                                                            |
| regex_effbot              | 3.45 ms                                                | 3.59 ms: 1.04x slower                                                            |
| pycparser                 | 1.20 sec                                               | 1.25 sec: 1.04x slower                                                           |
| richards                  | 48.9 ms                                                | 51.5 ms: 1.05x slower                                                            |
| scimark_sor               | 121 ms                                                 | 128 ms: 1.05x slower                                                             |
| regex_v8                  | 22.9 ms                                                | 24.2 ms: 1.05x slower                                                            |
| dulwich_log               | 64.9 ms                                                | 68.8 ms: 1.06x slower                                                            |
| pickle                    | 11.1 us                                                | 11.7 us: 1.06x slower                                                            |
| scimark_lu                | 112 ms                                                 | 120 ms: 1.06x slower                                                             |
| xml_etree_process         | 56.5 ms                                                | 60.2 ms: 1.07x slower                                                            |
| pathlib                   | 18.5 ms                                                | 19.7 ms: 1.07x slower                                                            |
| unpickle                  | 13.9 us                                                | 14.8 us: 1.07x slower                                                            |
| regex_dna                 | 204 ms                                                 | 219 ms: 1.07x slower                                                             |
| meteor_contest            | 109 ms                                                 | 117 ms: 1.08x slower                                                             |
| 2to3                      | 266 ms                                                 | 287 ms: 1.08x slower                                                             |
| pickle_list               | 4.65 us                                                | 5.03 us: 1.08x slower                                                            |
| deepcopy_memo             | 38.9 us                                                | 42.3 us: 1.09x slower                                                            |
| spectral_norm             | 105 ms                                                 | 114 ms: 1.09x slower                                                             |
| xml_etree_generate        | 80.4 ms                                                | 87.9 ms: 1.09x slower                                                            |
| chameleon                 | 6.86 ms                                                | 7.53 ms: 1.10x slower                                                            |
| pprint_safe_repr          | 743 ms                                                 | 826 ms: 1.11x slower                                                             |
| pprint_pformat            | 1.53 sec                                               | 1.70 sec: 1.12x slower                                                           |
| regex_compile             | 141 ms                                                 | 158 ms: 1.12x slower                                                             |
| scimark_monte_carlo       | 71.8 ms                                                | 80.6 ms: 1.12x slower                                                            |
| crypto_pyaes              | 77.5 ms                                                | 87.1 ms: 1.12x slower                                                            |
| sqlite_synth              | 2.58 us                                                | 2.93 us: 1.14x slower                                                            |
| go                        | 143 ms                                                 | 163 ms: 1.14x slower                                                             |
| tomli_loads               | 2.31 sec                                               | 2.66 sec: 1.15x slower                                                           |
| coverage                  | 81.2 ms                                                | 93.7 ms: 1.15x slower                                                            |
| fannkuch                  | 410 ms                                                 | 477 ms: 1.16x slower                                                             |
| nqueens                   | 86.8 ms                                                | 102 ms: 1.17x slower                                                             |
| python_startup            | 8.69 ms                                                | 10.3 ms: 1.19x slower                                                            |
| async_generators          | 375 ms                                                 | 456 ms: 1.21x slower                                                             |
| scimark_sparse_mat_mult   | 4.80 ms                                                | 6.03 ms: 1.25x slower                                                            |
| deltablue                 | 3.80 ms                                                | 4.83 ms: 1.27x slower                                                            |
| float                     | 78.9 ms                                                | 101 ms: 1.28x slower                                                             |
| pyflate                   | 426 ms                                                 | 549 ms: 1.29x slower                                                             |
| telco                     | 6.72 ms                                                | 8.73 ms: 1.30x slower                                                            |
| scimark_fft               | 342 ms                                                 | 447 ms: 1.31x slower                                                             |
| mako                      | 10.8 ms                                                | 14.2 ms: 1.31x slower                                                            |
| hexiom                    | 6.74 ms                                                | 9.19 ms: 1.36x slower                                                            |
| nbody                     | 91.6 ms                                                | 127 ms: 1.39x slower                                                             |
| python_startup_no_site    | 6.09 ms                                                | 9.03 ms: 1.48x slower                                                            |
| Geometric mean            | (ref)                                                  | 1.01x slower                                                                     |

Benchmark hidden because not significant (8): async_tree_cpu_io_mixed_tg, json, bench_mp_pool, deepcopy, sqlglot_optimize, logging_silent, unpickle_pure_python, logging_simple
Ignored benchmarks (13) of results/bm-20221024-3.11.0-deaf509/bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift


# HPT report

- Reliability score: 98.26% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
