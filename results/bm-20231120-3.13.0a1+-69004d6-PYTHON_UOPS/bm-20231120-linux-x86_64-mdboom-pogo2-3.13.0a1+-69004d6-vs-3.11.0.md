
# Results vs. 3.11.0

- fork: mdboom
- ref: pogo2
- machine: linux-x86_64
- commit hash: 69004d6
- commit date: 2023-11-20
- overall geometric mean: 1.08x slower \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.02x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-linux-x86_64-mdboom-pogo2-3.13.0a1+-69004d6 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| 2to3           | 266 ms                                                 | 300 ms: 1.13x slower                                    |
| chameleon      | 6.86 ms                                                | 7.79 ms: 1.14x slower                                   |
| docutils       | 2.69 sec                                               | 2.77 sec: 1.03x slower                                  |
| tornado_http   | 97.7 ms                                                | 103 ms: 1.06x slower                                    |
| Geometric mean | (ref)                                                  | 1.09x slower                                            |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                 | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-linux-x86_64-mdboom-pogo2-3.13.0a1+-69004d6 |
|---------------------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| async_tree_none           | 532 ms                                                 | 467 ms: 1.14x faster                                    |
| async_tree_memoization    | 640 ms                                                 | 594 ms: 1.08x faster                                    |
| async_tree_io             | 1.31 sec                                               | 1.24 sec: 1.06x faster                                  |
| async_tree_memoization_tg | 627 ms                                                 | 606 ms: 1.04x faster                                    |
| async_tree_io_tg          | 1.30 sec                                               | 1.27 sec: 1.03x faster                                  |
| async_tree_none_tg        | 490 ms                                                 | 477 ms: 1.03x faster                                    |
| async_tree_cpu_io_mixed   | 750 ms                                                 | 737 ms: 1.02x faster                                    |
| Geometric mean            | (ref)                                                  | 1.05x faster                                            |

Benchmark hidden because not significant (1): async_tree_cpu_io_mixed_tg

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-linux-x86_64-mdboom-pogo2-3.13.0a1+-69004d6 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| pidigits       | 190 ms                                                 | 191 ms: 1.00x slower                                    |
| float          | 78.9 ms                                                | 120 ms: 1.52x slower                                    |
| nbody          | 91.6 ms                                                | 170 ms: 1.86x slower                                    |
| Geometric mean | (ref)                                                  | 1.42x slower                                            |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-linux-x86_64-mdboom-pogo2-3.13.0a1+-69004d6 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| regex_effbot   | 3.45 ms                                                | 3.61 ms: 1.05x slower                                   |
| regex_v8       | 22.9 ms                                                | 24.7 ms: 1.08x slower                                   |
| regex_dna      | 204 ms                                                 | 224 ms: 1.10x slower                                    |
| regex_compile  | 141 ms                                                 | 174 ms: 1.23x slower                                    |
| Geometric mean | (ref)                                                  | 1.11x slower                                            |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-linux-x86_64-mdboom-pogo2-3.13.0a1+-69004d6 |
|----------------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| json_dumps           | 13.5 ms                                                | 10.7 ms: 1.26x faster                                   |
| json_loads           | 29.4 us                                                | 28.2 us: 1.04x faster                                   |
| pickle_dict          | 34.8 us                                                | 33.4 us: 1.04x faster                                   |
| pickle_pure_python   | 319 us                                                 | 310 us: 1.03x faster                                    |
| xml_etree_parse      | 163 ms                                                 | 160 ms: 1.02x faster                                    |
| unpickle_list        | 5.22 us                                                | 5.18 us: 1.01x faster                                   |
| pickle               | 11.1 us                                                | 11.3 us: 1.02x slower                                   |
| pickle_list          | 4.65 us                                                | 4.93 us: 1.06x slower                                   |
| unpickle_pure_python | 241 us                                                 | 258 us: 1.07x slower                                    |
| xml_etree_iterparse  | 109 ms                                                 | 124 ms: 1.14x slower                                    |
| xml_etree_process    | 56.5 ms                                                | 65.8 ms: 1.17x slower                                   |
| unpickle             | 13.9 us                                                | 16.3 us: 1.17x slower                                   |
| xml_etree_generate   | 80.4 ms                                                | 96.7 ms: 1.20x slower                                   |
| tomli_loads          | 2.31 sec                                               | 3.17 sec: 1.37x slower                                  |
| Geometric mean       | (ref)                                                  | 1.05x slower                                            |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-linux-x86_64-mdboom-pogo2-3.13.0a1+-69004d6 |
|------------------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| python_startup         | 8.69 ms                                                | 10.4 ms: 1.20x slower                                   |
| python_startup_no_site | 6.09 ms                                                | 9.08 ms: 1.49x slower                                   |
| Geometric mean         | (ref)                                                  | 1.34x slower                                            |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-linux-x86_64-mdboom-pogo2-3.13.0a1+-69004d6 |
|-----------|:------------------------------------------------------:|:-------------------------------------------------------:|
| mako      | 10.8 ms                                                | 18.4 ms: 1.70x slower                                   |

All benchmarks:
===============

| Benchmark                 | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-linux-x86_64-mdboom-pogo2-3.13.0a1+-69004d6 |
|---------------------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| typing_runtime_protocols  | 521 us                                                 | 129 us: 4.06x faster                                    |
| generators                | 76.5 ms                                                | 29.6 ms: 2.59x faster                                   |
| asyncio_tcp               | 887 ms                                                 | 491 ms: 1.81x faster                                    |
| asyncio_tcp_ssl           | 3.13 sec                                               | 1.80 sec: 1.73x faster                                  |
| json_dumps                | 13.5 ms                                                | 10.7 ms: 1.26x faster                                   |
| mypy2                     | 427 ms                                                 | 361 ms: 1.18x faster                                    |
| coroutines                | 26.1 ms                                                | 22.4 ms: 1.17x faster                                   |
| async_tree_none           | 532 ms                                                 | 467 ms: 1.14x faster                                    |
| gc_traversal              | 3.90 ms                                                | 3.51 ms: 1.11x faster                                   |
| async_tree_memoization    | 640 ms                                                 | 594 ms: 1.08x faster                                    |
| async_tree_io             | 1.31 sec                                               | 1.24 sec: 1.06x faster                                  |
| json_loads                | 29.4 us                                                | 28.2 us: 1.04x faster                                   |
| pickle_dict               | 34.8 us                                                | 33.4 us: 1.04x faster                                   |
| async_tree_memoization_tg | 627 ms                                                 | 606 ms: 1.04x faster                                    |
| async_tree_io_tg          | 1.30 sec                                               | 1.27 sec: 1.03x faster                                  |
| pickle_pure_python        | 319 us                                                 | 310 us: 1.03x faster                                    |
| async_tree_none_tg        | 490 ms                                                 | 477 ms: 1.03x faster                                    |
| xml_etree_parse           | 163 ms                                                 | 160 ms: 1.02x faster                                    |
| json                      | 5.24 ms                                                | 5.14 ms: 1.02x faster                                   |
| async_tree_cpu_io_mixed   | 750 ms                                                 | 737 ms: 1.02x faster                                    |
| richards_super            | 61.2 ms                                                | 60.2 ms: 1.02x faster                                   |
| sympy_sum                 | 170 ms                                                 | 169 ms: 1.01x faster                                    |
| unpickle_list             | 5.22 us                                                | 5.18 us: 1.01x faster                                   |
| create_gc_cycles          | 1.48 ms                                                | 1.47 ms: 1.01x faster                                   |
| asyncio_websockets        | 556 ms                                                 | 553 ms: 1.01x faster                                    |
| pidigits                  | 190 ms                                                 | 191 ms: 1.00x slower                                    |
| mdp                       | 2.79 sec                                               | 2.80 sec: 1.00x slower                                  |
| sqlglot_transpile         | 1.75 ms                                                | 1.77 ms: 1.01x slower                                   |
| logging_simple            | 6.24 us                                                | 6.31 us: 1.01x slower                                   |
| dask                      | 365 ms                                                 | 371 ms: 1.02x slower                                    |
| pickle                    | 11.1 us                                                | 11.3 us: 1.02x slower                                   |
| deepcopy_reduce           | 3.14 us                                                | 3.20 us: 1.02x slower                                   |
| deepcopy                  | 360 us                                                 | 368 us: 1.02x slower                                    |
| pathlib                   | 18.5 ms                                                | 18.9 ms: 1.02x slower                                   |
| sympy_expand              | 490 ms                                                 | 504 ms: 1.03x slower                                    |
| docutils                  | 2.69 sec                                               | 2.77 sec: 1.03x slower                                  |
| logging_format            | 6.83 us                                                | 7.11 us: 1.04x slower                                   |
| regex_effbot              | 3.45 ms                                                | 3.61 ms: 1.05x slower                                   |
| sympy_str                 | 299 ms                                                 | 313 ms: 1.05x slower                                    |
| logging_silent            | 108 ns                                                 | 114 ns: 1.05x slower                                    |
| bench_thread_pool         | 833 us                                                 | 875 us: 1.05x slower                                    |
| tornado_http              | 97.7 ms                                                | 103 ms: 1.06x slower                                    |
| pycparser                 | 1.20 sec                                               | 1.26 sec: 1.06x slower                                  |
| pickle_list               | 4.65 us                                                | 4.93 us: 1.06x slower                                   |
| sympy_integrate           | 21.4 ms                                                | 22.7 ms: 1.06x slower                                   |
| unpickle_pure_python      | 241 us                                                 | 258 us: 1.07x slower                                    |
| dulwich_log               | 64.9 ms                                                | 69.7 ms: 1.07x slower                                   |
| sqlglot_normalize         | 112 ms                                                 | 121 ms: 1.08x slower                                    |
| regex_v8                  | 22.9 ms                                                | 24.7 ms: 1.08x slower                                   |
| richards                  | 48.9 ms                                                | 53.4 ms: 1.09x slower                                   |
| raytrace                  | 306 ms                                                 | 336 ms: 1.10x slower                                    |
| regex_dna                 | 204 ms                                                 | 224 ms: 1.10x slower                                    |
| scimark_lu                | 112 ms                                                 | 124 ms: 1.11x slower                                    |
| sqlglot_optimize          | 55.2 ms                                                | 62.0 ms: 1.12x slower                                   |
| 2to3                      | 266 ms                                                 | 300 ms: 1.13x slower                                    |
| scimark_sor               | 121 ms                                                 | 137 ms: 1.13x slower                                    |
| chameleon                 | 6.86 ms                                                | 7.79 ms: 1.14x slower                                   |
| xml_etree_iterparse       | 109 ms                                                 | 124 ms: 1.14x slower                                    |
| unpack_sequence           | 43.3 ns                                                | 49.3 ns: 1.14x slower                                   |
| sqlite_synth              | 2.58 us                                                | 2.96 us: 1.15x slower                                   |
| xml_etree_process         | 56.5 ms                                                | 65.8 ms: 1.17x slower                                   |
| deepcopy_memo             | 38.9 us                                                | 45.4 us: 1.17x slower                                   |
| meteor_contest            | 109 ms                                                 | 127 ms: 1.17x slower                                    |
| coverage                  | 81.2 ms                                                | 95.2 ms: 1.17x slower                                   |
| unpickle                  | 13.9 us                                                | 16.3 us: 1.17x slower                                   |
| python_startup            | 8.69 ms                                                | 10.4 ms: 1.20x slower                                   |
| xml_etree_generate        | 80.4 ms                                                | 96.7 ms: 1.20x slower                                   |
| comprehensions            | 23.6 us                                                | 28.6 us: 1.21x slower                                   |
| regex_compile             | 141 ms                                                 | 174 ms: 1.23x slower                                    |
| go                        | 143 ms                                                 | 177 ms: 1.24x slower                                    |
| async_generators          | 375 ms                                                 | 467 ms: 1.24x slower                                    |
| pprint_safe_repr          | 743 ms                                                 | 928 ms: 1.25x slower                                    |
| chaos                     | 71.4 ms                                                | 89.4 ms: 1.25x slower                                   |
| pprint_pformat            | 1.53 sec                                               | 1.93 sec: 1.26x slower                                  |
| crypto_pyaes              | 77.5 ms                                                | 103 ms: 1.33x slower                                    |
| fannkuch                  | 410 ms                                                 | 551 ms: 1.34x slower                                    |
| telco                     | 6.72 ms                                                | 9.06 ms: 1.35x slower                                   |
| tomli_loads               | 2.31 sec                                               | 3.17 sec: 1.37x slower                                  |
| nqueens                   | 86.8 ms                                                | 120 ms: 1.38x slower                                    |
| scimark_monte_carlo       | 71.8 ms                                                | 103 ms: 1.43x slower                                    |
| pyflate                   | 426 ms                                                 | 632 ms: 1.48x slower                                    |
| python_startup_no_site    | 6.09 ms                                                | 9.08 ms: 1.49x slower                                   |
| float                     | 78.9 ms                                                | 120 ms: 1.52x slower                                    |
| scimark_sparse_mat_mult   | 4.80 ms                                                | 7.94 ms: 1.65x slower                                   |
| deltablue                 | 3.80 ms                                                | 6.30 ms: 1.65x slower                                   |
| scimark_fft               | 342 ms                                                 | 567 ms: 1.66x slower                                    |
| mako                      | 10.8 ms                                                | 18.4 ms: 1.70x slower                                   |
| hexiom                    | 6.74 ms                                                | 11.5 ms: 1.71x slower                                   |
| nbody                     | 91.6 ms                                                | 170 ms: 1.86x slower                                    |
| spectral_norm             | 105 ms                                                 | 205 ms: 1.95x slower                                    |
| Geometric mean            | (ref)                                                  | 1.08x slower                                            |

Benchmark hidden because not significant (3): async_tree_cpu_io_mixed_tg, bench_mp_pool, sqlglot_parse
Ignored benchmarks (12) of results/bm-20221024-3.11.0-deaf509/bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.04x
- 95% likely to have a slowdown of 1.03x
- 99% likely to have a slowdown of 1.02x
