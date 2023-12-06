
# Results vs. 3.10.4

- fork: mdboom
- ref: alternative_workarou
- machine: linux-x86_64
- commit hash: d452c37
- commit date: 2023-11-20
- overall geometric mean: 1.29x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.22x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-pythonperf2-x86_64-mdboom-alternative_workarou-3.13.0a1+-d452c37 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| 2to3           | 349 ms                                                       | 292 ms: 1.20x faster                                                         |
| chameleon      | 9.88 ms                                                      | 7.58 ms: 1.30x faster                                                        |
| docutils       | 3.42 sec                                                     | 2.84 sec: 1.20x faster                                                       |
| tornado_http   | 157 ms                                                       | 119 ms: 1.32x faster                                                         |
| Geometric mean | (ref)                                                        | 1.25x faster                                                                 |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-pythonperf2-x86_64-mdboom-alternative_workarou-3.13.0a1+-d452c37 |
|-------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| async_tree_none         | 700 ms                                                       | 432 ms: 1.62x faster                                                         |
| async_tree_memoization  | 827 ms                                                       | 545 ms: 1.52x faster                                                         |
| async_tree_io           | 1.61 sec                                                     | 1.08 sec: 1.49x faster                                                       |
| async_tree_cpu_io_mixed | 946 ms                                                       | 696 ms: 1.36x faster                                                         |
| Geometric mean          | (ref)                                                        | 1.49x faster                                                                 |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-pythonperf2-x86_64-mdboom-alternative_workarou-3.13.0a1+-d452c37 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| nbody          | 134 ms                                                       | 87.6 ms: 1.53x faster                                                        |
| float          | 109 ms                                                       | 79.7 ms: 1.36x faster                                                        |
| pidigits       | 270 ms                                                       | 267 ms: 1.01x faster                                                         |
| Geometric mean | (ref)                                                        | 1.28x faster                                                                 |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-pythonperf2-x86_64-mdboom-alternative_workarou-3.13.0a1+-d452c37 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| regex_compile  | 192 ms                                                       | 145 ms: 1.32x faster                                                         |
| regex_v8       | 27.1 ms                                                      | 25.6 ms: 1.06x faster                                                        |
| regex_dna      | 260 ms                                                       | 252 ms: 1.03x faster                                                         |
| regex_effbot   | 3.10 ms                                                      | 3.58 ms: 1.16x slower                                                        |
| Geometric mean | (ref)                                                        | 1.06x faster                                                                 |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-pythonperf2-x86_64-mdboom-alternative_workarou-3.13.0a1+-d452c37 |
|----------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| pickle_pure_python   | 453 us                                                       | 309 us: 1.46x faster                                                         |
| unpickle_pure_python | 315 us                                                       | 224 us: 1.41x faster                                                         |
| json_dumps           | 14.2 ms                                                      | 10.6 ms: 1.34x faster                                                        |
| xml_etree_process    | 76.4 ms                                                      | 58.8 ms: 1.30x faster                                                        |
| tomli_loads          | 2.96 sec                                                     | 2.28 sec: 1.30x faster                                                       |
| json_loads           | 30.0 us                                                      | 25.3 us: 1.19x faster                                                        |
| xml_etree_generate   | 93.1 ms                                                      | 85.2 ms: 1.09x faster                                                        |
| xml_etree_parse      | 159 ms                                                       | 150 ms: 1.06x faster                                                         |
| xml_etree_iterparse  | 110 ms                                                       | 106 ms: 1.04x faster                                                         |
| pickle               | 10.1 us                                                      | 10.2 us: 1.01x slower                                                        |
| unpickle_list        | 4.45 us                                                      | 4.64 us: 1.04x slower                                                        |
| pickle_dict          | 30.4 us                                                      | 32.0 us: 1.05x slower                                                        |
| pickle_list          | 4.23 us                                                      | 4.46 us: 1.05x slower                                                        |
| unpickle             | 13.9 us                                                      | 15.0 us: 1.08x slower                                                        |
| Geometric mean       | (ref)                                                        | 1.13x faster                                                                 |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-pythonperf2-x86_64-mdboom-alternative_workarou-3.13.0a1+-d452c37 |
|------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| python_startup         | 11.5 ms                                                      | 12.8 ms: 1.11x slower                                                        |
| python_startup_no_site | 7.35 ms                                                      | 11.3 ms: 1.54x slower                                                        |
| Geometric mean         | (ref)                                                        | 1.31x slower                                                                 |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-pythonperf2-x86_64-mdboom-alternative_workarou-3.13.0a1+-d452c37 |
|-----------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| mako      | 14.7 ms                                                      | 10.2 ms: 1.44x faster                                                        |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-pythonperf2-x86_64-mdboom-alternative_workarou-3.13.0a1+-d452c37 |
|--------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| typing_runtime_protocols | 533 us                                                       | 126 us: 4.24x faster                                                         |
| asyncio_tcp              | 785 ms                                                       | 368 ms: 2.14x faster                                                         |
| deltablue                | 7.43 ms                                                      | 3.56 ms: 2.08x faster                                                        |
| asyncio_tcp_ssl          | 3.13 sec                                                     | 1.57 sec: 1.99x faster                                                       |
| raytrace                 | 497 ms                                                       | 271 ms: 1.84x faster                                                         |
| chaos                    | 106 ms                                                       | 60.0 ms: 1.77x faster                                                        |
| logging_silent           | 168 ns                                                       | 97.2 ns: 1.73x faster                                                        |
| generators               | 57.7 ms                                                      | 34.2 ms: 1.69x faster                                                        |
| crypto_pyaes             | 118 ms                                                       | 71.2 ms: 1.66x faster                                                        |
| scimark_lu               | 165 ms                                                       | 99.6 ms: 1.65x faster                                                        |
| scimark_monte_carlo      | 109 ms                                                       | 66.5 ms: 1.65x faster                                                        |
| sqlglot_parse            | 2.27 ms                                                      | 1.39 ms: 1.63x faster                                                        |
| async_tree_none          | 700 ms                                                       | 432 ms: 1.62x faster                                                         |
| comprehensions           | 27.0 us                                                      | 16.7 us: 1.62x faster                                                        |
| richards_super           | 93.0 ms                                                      | 58.6 ms: 1.59x faster                                                        |
| spectral_norm            | 141 ms                                                       | 92.0 ms: 1.54x faster                                                        |
| nbody                    | 134 ms                                                       | 87.6 ms: 1.53x faster                                                        |
| go                       | 258 ms                                                       | 169 ms: 1.52x faster                                                         |
| sqlglot_transpile        | 2.73 ms                                                      | 1.80 ms: 1.52x faster                                                        |
| bench_mp_pool            | 6.82 ms                                                      | 4.49 ms: 1.52x faster                                                        |
| async_tree_memoization   | 827 ms                                                       | 545 ms: 1.52x faster                                                         |
| async_tree_io            | 1.61 sec                                                     | 1.08 sec: 1.49x faster                                                       |
| hexiom                   | 9.46 ms                                                      | 6.44 ms: 1.47x faster                                                        |
| pickle_pure_python       | 453 us                                                       | 309 us: 1.46x faster                                                         |
| richards                 | 76.3 ms                                                      | 52.7 ms: 1.45x faster                                                        |
| mako                     | 14.7 ms                                                      | 10.2 ms: 1.44x faster                                                        |
| unpickle_pure_python     | 315 us                                                       | 224 us: 1.41x faster                                                         |
| coroutines               | 30.9 ms                                                      | 22.2 ms: 1.39x faster                                                        |
| pyflate                  | 698 ms                                                       | 508 ms: 1.37x faster                                                         |
| logging_simple           | 9.06 us                                                      | 6.62 us: 1.37x faster                                                        |
| float                    | 109 ms                                                       | 79.7 ms: 1.36x faster                                                        |
| async_tree_cpu_io_mixed  | 946 ms                                                       | 696 ms: 1.36x faster                                                         |
| deepcopy_memo            | 50.5 us                                                      | 37.6 us: 1.34x faster                                                        |
| json_dumps               | 14.2 ms                                                      | 10.6 ms: 1.34x faster                                                        |
| logging_format           | 9.82 us                                                      | 7.38 us: 1.33x faster                                                        |
| regex_compile            | 192 ms                                                       | 145 ms: 1.32x faster                                                         |
| tornado_http             | 157 ms                                                       | 119 ms: 1.32x faster                                                         |
| chameleon                | 9.88 ms                                                      | 7.58 ms: 1.30x faster                                                        |
| xml_etree_process        | 76.4 ms                                                      | 58.8 ms: 1.30x faster                                                        |
| tomli_loads              | 2.96 sec                                                     | 2.28 sec: 1.30x faster                                                       |
| pprint_pformat           | 2.15 sec                                                     | 1.66 sec: 1.30x faster                                                       |
| mypy2                    | 467 ms                                                       | 366 ms: 1.28x faster                                                         |
| pprint_safe_repr         | 1.04 sec                                                     | 814 ms: 1.28x faster                                                         |
| sympy_sum                | 194 ms                                                       | 152 ms: 1.28x faster                                                         |
| sqlglot_normalize        | 146 ms                                                       | 115 ms: 1.27x faster                                                         |
| fannkuch                 | 488 ms                                                       | 386 ms: 1.26x faster                                                         |
| nqueens                  | 112 ms                                                       | 88.5 ms: 1.26x faster                                                        |
| unpack_sequence          | 60.3 ns                                                      | 48.0 ns: 1.26x faster                                                        |
| scimark_sor              | 183 ms                                                       | 146 ms: 1.25x faster                                                         |
| pycparser                | 1.65 sec                                                     | 1.32 sec: 1.25x faster                                                       |
| scimark_sparse_mat_mult  | 5.21 ms                                                      | 4.20 ms: 1.24x faster                                                        |
| deepcopy                 | 459 us                                                       | 371 us: 1.24x faster                                                         |
| sympy_str                | 359 ms                                                       | 290 ms: 1.24x faster                                                         |
| sympy_integrate          | 28.3 ms                                                      | 23.0 ms: 1.23x faster                                                        |
| sympy_expand             | 599 ms                                                       | 495 ms: 1.21x faster                                                         |
| deepcopy_reduce          | 4.00 us                                                      | 3.33 us: 1.20x faster                                                        |
| docutils                 | 3.42 sec                                                     | 2.84 sec: 1.20x faster                                                       |
| sqlglot_optimize         | 69.9 ms                                                      | 58.3 ms: 1.20x faster                                                        |
| 2to3                     | 349 ms                                                       | 292 ms: 1.20x faster                                                         |
| dulwich_log              | 80.0 ms                                                      | 67.2 ms: 1.19x faster                                                        |
| bench_thread_pool        | 1.13 ms                                                      | 956 us: 1.19x faster                                                         |
| json_loads               | 30.0 us                                                      | 25.3 us: 1.19x faster                                                        |
| dask                     | 469 ms                                                       | 398 ms: 1.18x faster                                                         |
| scimark_fft              | 363 ms                                                       | 308 ms: 1.18x faster                                                         |
| mdp                      | 2.94 sec                                                     | 2.53 sec: 1.16x faster                                                       |
| async_generators         | 418 ms                                                       | 362 ms: 1.15x faster                                                         |
| json                     | 5.91 ms                                                      | 5.21 ms: 1.13x faster                                                        |
| pathlib                  | 21.2 ms                                                      | 18.8 ms: 1.12x faster                                                        |
| create_gc_cycles         | 1.79 ms                                                      | 1.63 ms: 1.10x faster                                                        |
| xml_etree_generate       | 93.1 ms                                                      | 85.2 ms: 1.09x faster                                                        |
| sqlite_synth             | 2.97 us                                                      | 2.72 us: 1.09x faster                                                        |
| meteor_contest           | 138 ms                                                       | 128 ms: 1.07x faster                                                         |
| xml_etree_parse          | 159 ms                                                       | 150 ms: 1.06x faster                                                         |
| regex_v8                 | 27.1 ms                                                      | 25.6 ms: 1.06x faster                                                        |
| xml_etree_iterparse      | 110 ms                                                       | 106 ms: 1.04x faster                                                         |
| regex_dna                | 260 ms                                                       | 252 ms: 1.03x faster                                                         |
| pidigits                 | 270 ms                                                       | 267 ms: 1.01x faster                                                         |
| asyncio_websockets       | 394 ms                                                       | 391 ms: 1.01x faster                                                         |
| pickle                   | 10.1 us                                                      | 10.2 us: 1.01x slower                                                        |
| gc_traversal             | 3.63 ms                                                      | 3.78 ms: 1.04x slower                                                        |
| unpickle_list            | 4.45 us                                                      | 4.64 us: 1.04x slower                                                        |
| pickle_dict              | 30.4 us                                                      | 32.0 us: 1.05x slower                                                        |
| pickle_list              | 4.23 us                                                      | 4.46 us: 1.05x slower                                                        |
| unpickle                 | 13.9 us                                                      | 15.0 us: 1.08x slower                                                        |
| python_startup           | 11.5 ms                                                      | 12.8 ms: 1.11x slower                                                        |
| telco                    | 7.21 ms                                                      | 8.03 ms: 1.11x slower                                                        |
| regex_effbot             | 3.10 ms                                                      | 3.58 ms: 1.16x slower                                                        |
| coverage                 | 65.9 ms                                                      | 85.4 ms: 1.30x slower                                                        |
| python_startup_no_site   | 7.35 ms                                                      | 11.3 ms: 1.54x slower                                                        |
| Geometric mean           | (ref)                                                        | 1.29x faster                                                                 |
Ignored benchmarks (11) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
Ignored benchmarks (4) of results/bm-20231120-3.13.0a1+-d452c37/bm-20231120-pythonperf2-x86_64-mdboom-alternative_workarou-3.13.0a1+-d452c37.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.25x
- 95% likely to have a speedup of 1.24x
- 99% likely to have a speedup of 1.22x
