
# Results vs. 3.10.4

- fork: mdboom
- ref: pogo2
- machine: linux-x86_64
- commit hash: 69004d6
- commit date: 2023-11-20
- overall geometric mean: 1.15x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.08x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-pythonperf2-x86_64-mdboom-pogo2-3.13.0a1+-69004d6 |
|----------------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| 2to3           | 349 ms                                                       | 318 ms: 1.10x faster                                          |
| chameleon      | 9.88 ms                                                      | 7.81 ms: 1.26x faster                                         |
| docutils       | 3.42 sec                                                     | 2.95 sec: 1.16x faster                                        |
| tornado_http   | 157 ms                                                       | 125 ms: 1.25x faster                                          |
| Geometric mean | (ref)                                                        | 1.19x faster                                                  |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-pythonperf2-x86_64-mdboom-pogo2-3.13.0a1+-69004d6 |
|-------------------------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| async_tree_none         | 700 ms                                                       | 451 ms: 1.55x faster                                          |
| async_tree_memoization  | 827 ms                                                       | 566 ms: 1.46x faster                                          |
| async_tree_io           | 1.61 sec                                                     | 1.11 sec: 1.45x faster                                        |
| async_tree_cpu_io_mixed | 946 ms                                                       | 717 ms: 1.32x faster                                          |
| Geometric mean          | (ref)                                                        | 1.44x faster                                                  |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-pythonperf2-x86_64-mdboom-pogo2-3.13.0a1+-69004d6 |
|----------------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| pidigits       | 270 ms                                                       | 268 ms: 1.01x faster                                          |
| float          | 109 ms                                                       | 114 ms: 1.05x slower                                          |
| nbody          | 134 ms                                                       | 149 ms: 1.11x slower                                          |
| Geometric mean | (ref)                                                        | 1.05x slower                                                  |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-pythonperf2-x86_64-mdboom-pogo2-3.13.0a1+-69004d6 |
|----------------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| regex_v8       | 27.1 ms                                                      | 24.7 ms: 1.10x faster                                         |
| regex_compile  | 192 ms                                                       | 178 ms: 1.08x faster                                          |
| regex_dna      | 260 ms                                                       | 241 ms: 1.08x faster                                          |
| regex_effbot   | 3.10 ms                                                      | 3.48 ms: 1.12x slower                                         |
| Geometric mean | (ref)                                                        | 1.03x faster                                                  |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-pythonperf2-x86_64-mdboom-pogo2-3.13.0a1+-69004d6 |
|----------------------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| pickle_pure_python   | 453 us                                                       | 309 us: 1.47x faster                                          |
| json_dumps           | 14.2 ms                                                      | 10.6 ms: 1.34x faster                                         |
| unpickle_pure_python | 315 us                                                       | 255 us: 1.24x faster                                          |
| xml_etree_process    | 76.4 ms                                                      | 63.3 ms: 1.21x faster                                         |
| json_loads           | 30.0 us                                                      | 25.2 us: 1.19x faster                                         |
| xml_etree_parse      | 159 ms                                                       | 147 ms: 1.09x faster                                          |
| xml_etree_generate   | 93.1 ms                                                      | 92.2 ms: 1.01x faster                                         |
| unpickle             | 13.9 us                                                      | 14.8 us: 1.06x slower                                         |
| pickle_list          | 4.23 us                                                      | 4.50 us: 1.06x slower                                         |
| unpickle_list        | 4.45 us                                                      | 4.75 us: 1.07x slower                                         |
| pickle_dict          | 30.4 us                                                      | 33.0 us: 1.08x slower                                         |
| xml_etree_iterparse  | 110 ms                                                       | 123 ms: 1.12x slower                                          |
| Geometric mean       | (ref)                                                        | 1.07x faster                                                  |

Benchmark hidden because not significant (2): pickle, tomli_loads

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-pythonperf2-x86_64-mdboom-pogo2-3.13.0a1+-69004d6 |
|------------------------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| python_startup         | 11.5 ms                                                      | 12.8 ms: 1.11x slower                                         |
| python_startup_no_site | 7.35 ms                                                      | 11.3 ms: 1.54x slower                                         |
| Geometric mean         | (ref)                                                        | 1.31x slower                                                  |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-pythonperf2-x86_64-mdboom-pogo2-3.13.0a1+-69004d6 |
|-----------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| mako      | 14.7 ms                                                      | 17.9 ms: 1.21x slower                                         |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-pythonperf2-x86_64-mdboom-pogo2-3.13.0a1+-69004d6 |
|--------------------------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| typing_runtime_protocols | 533 us                                                       | 132 us: 4.05x faster                                          |
| asyncio_tcp              | 785 ms                                                       | 374 ms: 2.10x faster                                          |
| asyncio_tcp_ssl          | 3.13 sec                                                     | 1.59 sec: 1.96x faster                                        |
| logging_silent           | 168 ns                                                       | 100 ns: 1.67x faster                                          |
| generators               | 57.7 ms                                                      | 35.2 ms: 1.64x faster                                         |
| async_tree_none          | 700 ms                                                       | 451 ms: 1.55x faster                                          |
| raytrace                 | 497 ms                                                       | 322 ms: 1.54x faster                                          |
| richards_super           | 93.0 ms                                                      | 60.3 ms: 1.54x faster                                         |
| scimark_lu               | 165 ms                                                       | 107 ms: 1.54x faster                                          |
| sqlglot_parse            | 2.27 ms                                                      | 1.49 ms: 1.52x faster                                         |
| pickle_pure_python       | 453 us                                                       | 309 us: 1.47x faster                                          |
| async_tree_memoization   | 827 ms                                                       | 566 ms: 1.46x faster                                          |
| async_tree_io            | 1.61 sec                                                     | 1.11 sec: 1.45x faster                                        |
| bench_mp_pool            | 6.82 ms                                                      | 4.77 ms: 1.43x faster                                         |
| sqlglot_transpile        | 2.73 ms                                                      | 1.92 ms: 1.43x faster                                         |
| richards                 | 76.3 ms                                                      | 54.7 ms: 1.39x faster                                         |
| coroutines               | 30.9 ms                                                      | 22.3 ms: 1.38x faster                                         |
| go                       | 258 ms                                                       | 186 ms: 1.38x faster                                          |
| json_dumps               | 14.2 ms                                                      | 10.6 ms: 1.34x faster                                         |
| logging_simple           | 9.06 us                                                      | 6.77 us: 1.34x faster                                         |
| logging_format           | 9.82 us                                                      | 7.41 us: 1.32x faster                                         |
| async_tree_cpu_io_mixed  | 946 ms                                                       | 717 ms: 1.32x faster                                          |
| chaos                    | 106 ms                                                       | 83.4 ms: 1.27x faster                                         |
| chameleon                | 9.88 ms                                                      | 7.81 ms: 1.26x faster                                         |
| crypto_pyaes             | 118 ms                                                       | 93.9 ms: 1.26x faster                                         |
| tornado_http             | 157 ms                                                       | 125 ms: 1.25x faster                                          |
| deepcopy                 | 459 us                                                       | 371 us: 1.24x faster                                          |
| unpickle_pure_python     | 315 us                                                       | 255 us: 1.24x faster                                          |
| deltablue                | 7.43 ms                                                      | 6.03 ms: 1.23x faster                                         |
| deepcopy_reduce          | 4.00 us                                                      | 3.27 us: 1.22x faster                                         |
| mypy2                    | 467 ms                                                       | 382 ms: 1.22x faster                                          |
| pycparser                | 1.65 sec                                                     | 1.36 sec: 1.21x faster                                        |
| scimark_sor              | 183 ms                                                       | 152 ms: 1.21x faster                                          |
| xml_etree_process        | 76.4 ms                                                      | 63.3 ms: 1.21x faster                                         |
| deepcopy_memo            | 50.5 us                                                      | 42.3 us: 1.19x faster                                         |
| json_loads               | 30.0 us                                                      | 25.2 us: 1.19x faster                                         |
| sqlglot_normalize        | 146 ms                                                       | 124 ms: 1.18x faster                                          |
| docutils                 | 3.42 sec                                                     | 2.95 sec: 1.16x faster                                        |
| bench_thread_pool        | 1.13 ms                                                      | 991 us: 1.15x faster                                          |
| dask                     | 469 ms                                                       | 410 ms: 1.14x faster                                          |
| pyflate                  | 698 ms                                                       | 611 ms: 1.14x faster                                          |
| unpack_sequence          | 60.3 ns                                                      | 52.8 ns: 1.14x faster                                         |
| json                     | 5.91 ms                                                      | 5.20 ms: 1.14x faster                                         |
| sympy_sum                | 194 ms                                                       | 171 ms: 1.13x faster                                          |
| scimark_monte_carlo      | 109 ms                                                       | 97.8 ms: 1.12x faster                                         |
| sympy_integrate          | 28.3 ms                                                      | 25.6 ms: 1.11x faster                                         |
| create_gc_cycles         | 1.79 ms                                                      | 1.62 ms: 1.11x faster                                         |
| dulwich_log              | 80.0 ms                                                      | 72.5 ms: 1.10x faster                                         |
| 2to3                     | 349 ms                                                       | 318 ms: 1.10x faster                                          |
| sympy_expand             | 599 ms                                                       | 546 ms: 1.10x faster                                          |
| pprint_pformat           | 2.15 sec                                                     | 1.96 sec: 1.10x faster                                        |
| regex_v8                 | 27.1 ms                                                      | 24.7 ms: 1.10x faster                                         |
| pprint_safe_repr         | 1.04 sec                                                     | 951 ms: 1.09x faster                                          |
| async_generators         | 418 ms                                                       | 385 ms: 1.09x faster                                          |
| xml_etree_parse          | 159 ms                                                       | 147 ms: 1.09x faster                                          |
| sqlglot_optimize         | 69.9 ms                                                      | 64.5 ms: 1.08x faster                                         |
| sympy_str                | 359 ms                                                       | 331 ms: 1.08x faster                                          |
| regex_compile            | 192 ms                                                       | 178 ms: 1.08x faster                                          |
| regex_dna                | 260 ms                                                       | 241 ms: 1.08x faster                                          |
| mdp                      | 2.94 sec                                                     | 2.73 sec: 1.07x faster                                        |
| pathlib                  | 21.2 ms                                                      | 19.8 ms: 1.07x faster                                         |
| sqlite_synth             | 2.97 us                                                      | 2.83 us: 1.05x faster                                         |
| asyncio_websockets       | 394 ms                                                       | 388 ms: 1.02x faster                                          |
| xml_etree_generate       | 93.1 ms                                                      | 92.2 ms: 1.01x faster                                         |
| pidigits                 | 270 ms                                                       | 268 ms: 1.01x faster                                          |
| gc_traversal             | 3.63 ms                                                      | 3.71 ms: 1.02x slower                                         |
| nqueens                  | 112 ms                                                       | 116 ms: 1.04x slower                                          |
| comprehensions           | 27.0 us                                                      | 28.2 us: 1.04x slower                                         |
| float                    | 109 ms                                                       | 114 ms: 1.05x slower                                          |
| meteor_contest           | 138 ms                                                       | 145 ms: 1.05x slower                                          |
| unpickle                 | 13.9 us                                                      | 14.8 us: 1.06x slower                                         |
| pickle_list              | 4.23 us                                                      | 4.50 us: 1.06x slower                                         |
| fannkuch                 | 488 ms                                                       | 521 ms: 1.07x slower                                          |
| unpickle_list            | 4.45 us                                                      | 4.75 us: 1.07x slower                                         |
| pickle_dict              | 30.4 us                                                      | 33.0 us: 1.08x slower                                         |
| python_startup           | 11.5 ms                                                      | 12.8 ms: 1.11x slower                                         |
| nbody                    | 134 ms                                                       | 149 ms: 1.11x slower                                          |
| xml_etree_iterparse      | 110 ms                                                       | 123 ms: 1.12x slower                                          |
| regex_effbot             | 3.10 ms                                                      | 3.48 ms: 1.12x slower                                         |
| hexiom                   | 9.46 ms                                                      | 10.9 ms: 1.15x slower                                         |
| telco                    | 7.21 ms                                                      | 8.51 ms: 1.18x slower                                         |
| mako                     | 14.7 ms                                                      | 17.9 ms: 1.21x slower                                         |
| coverage                 | 65.9 ms                                                      | 82.7 ms: 1.25x slower                                         |
| spectral_norm            | 141 ms                                                       | 185 ms: 1.31x slower                                          |
| scimark_fft              | 363 ms                                                       | 478 ms: 1.32x slower                                          |
| scimark_sparse_mat_mult  | 5.21 ms                                                      | 7.06 ms: 1.35x slower                                         |
| python_startup_no_site   | 7.35 ms                                                      | 11.3 ms: 1.54x slower                                         |
| Geometric mean           | (ref)                                                        | 1.15x faster                                                  |

Benchmark hidden because not significant (2): pickle, tomli_loads
Ignored benchmarks (11) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
Ignored benchmarks (4) of results/bm-20231120-3.13.0a1+-69004d6-PYTHON_UOPS/bm-20231120-pythonperf2-x86_64-mdboom-pogo2-3.13.0a1+-69004d6.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.09x
- 95% likely to have a speedup of 1.09x
- 99% likely to have a speedup of 1.08x
