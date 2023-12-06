
# Results vs. 3.10.4

- fork: python
- ref: 0ee2d77331f2362fcaab
- machine: linux-x86_64
- commit hash: 0ee2d77
- commit date: 2023-11-17
- overall geometric mean: 1.19x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.11x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231117-pythonperf2-x86_64-python-0ee2d77331f2362fcaab-3.13.0a1+-0ee2d77 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| 2to3           | 349 ms                                                       | 313 ms: 1.12x faster                                                         |
| chameleon      | 9.88 ms                                                      | 8.23 ms: 1.20x faster                                                        |
| docutils       | 3.42 sec                                                     | 2.95 sec: 1.16x faster                                                       |
| tornado_http   | 157 ms                                                       | 125 ms: 1.25x faster                                                         |
| Geometric mean | (ref)                                                        | 1.18x faster                                                                 |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231117-pythonperf2-x86_64-python-0ee2d77331f2362fcaab-3.13.0a1+-0ee2d77 |
|-------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| async_tree_none         | 700 ms                                                       | 455 ms: 1.54x faster                                                         |
| async_tree_io           | 1.61 sec                                                     | 1.11 sec: 1.45x faster                                                       |
| async_tree_memoization  | 827 ms                                                       | 572 ms: 1.45x faster                                                         |
| async_tree_cpu_io_mixed | 946 ms                                                       | 724 ms: 1.31x faster                                                         |
| Geometric mean          | (ref)                                                        | 1.43x faster                                                                 |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231117-pythonperf2-x86_64-python-0ee2d77331f2362fcaab-3.13.0a1+-0ee2d77 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| nbody          | 134 ms                                                       | 109 ms: 1.23x faster                                                         |
| float          | 109 ms                                                       | 101 ms: 1.08x faster                                                         |
| pidigits       | 270 ms                                                       | 266 ms: 1.01x faster                                                         |
| Geometric mean | (ref)                                                        | 1.10x faster                                                                 |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231117-pythonperf2-x86_64-python-0ee2d77331f2362fcaab-3.13.0a1+-0ee2d77 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| regex_compile  | 192 ms                                                       | 173 ms: 1.11x faster                                                         |
| regex_dna      | 260 ms                                                       | 244 ms: 1.07x faster                                                         |
| regex_v8       | 27.1 ms                                                      | 25.9 ms: 1.05x faster                                                        |
| regex_effbot   | 3.10 ms                                                      | 3.54 ms: 1.14x slower                                                        |
| Geometric mean | (ref)                                                        | 1.02x faster                                                                 |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231117-pythonperf2-x86_64-python-0ee2d77331f2362fcaab-3.13.0a1+-0ee2d77 |
|----------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| pickle_pure_python   | 453 us                                                       | 314 us: 1.44x faster                                                         |
| json_dumps           | 14.2 ms                                                      | 10.8 ms: 1.32x faster                                                        |
| xml_etree_process    | 76.4 ms                                                      | 58.5 ms: 1.31x faster                                                        |
| unpickle_pure_python | 315 us                                                       | 253 us: 1.25x faster                                                         |
| json_loads           | 30.0 us                                                      | 25.2 us: 1.19x faster                                                        |
| xml_etree_generate   | 93.1 ms                                                      | 86.9 ms: 1.07x faster                                                        |
| xml_etree_parse      | 159 ms                                                       | 152 ms: 1.05x faster                                                         |
| tomli_loads          | 2.96 sec                                                     | 2.87 sec: 1.03x faster                                                       |
| pickle               | 10.1 us                                                      | 10.1 us: 1.00x slower                                                        |
| pickle_list          | 4.23 us                                                      | 4.36 us: 1.03x slower                                                        |
| unpickle             | 13.9 us                                                      | 14.5 us: 1.04x slower                                                        |
| xml_etree_iterparse  | 110 ms                                                       | 114 ms: 1.05x slower                                                         |
| unpickle_list        | 4.45 us                                                      | 4.65 us: 1.05x slower                                                        |
| pickle_dict          | 30.4 us                                                      | 32.3 us: 1.06x slower                                                        |
| Geometric mean       | (ref)                                                        | 1.09x faster                                                                 |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231117-pythonperf2-x86_64-python-0ee2d77331f2362fcaab-3.13.0a1+-0ee2d77 |
|------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| python_startup         | 11.5 ms                                                      | 12.9 ms: 1.12x slower                                                        |
| python_startup_no_site | 7.35 ms                                                      | 11.4 ms: 1.55x slower                                                        |
| Geometric mean         | (ref)                                                        | 1.32x slower                                                                 |

Benchmarks with tag 'template':
===============================

Benchmark hidden because not significant (1): mako

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231117-pythonperf2-x86_64-python-0ee2d77331f2362fcaab-3.13.0a1+-0ee2d77 |
|--------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| typing_runtime_protocols | 533 us                                                       | 135 us: 3.96x faster                                                         |
| asyncio_tcp              | 785 ms                                                       | 375 ms: 2.09x faster                                                         |
| asyncio_tcp_ssl          | 3.13 sec                                                     | 1.60 sec: 1.96x faster                                                       |
| raytrace                 | 497 ms                                                       | 298 ms: 1.67x faster                                                         |
| logging_silent           | 168 ns                                                       | 101 ns: 1.66x faster                                                         |
| generators               | 57.7 ms                                                      | 35.1 ms: 1.64x faster                                                        |
| spectral_norm            | 141 ms                                                       | 91.4 ms: 1.55x faster                                                        |
| scimark_lu               | 165 ms                                                       | 107 ms: 1.54x faster                                                         |
| async_tree_none          | 700 ms                                                       | 455 ms: 1.54x faster                                                         |
| richards_super           | 93.0 ms                                                      | 60.5 ms: 1.54x faster                                                        |
| sqlglot_parse            | 2.27 ms                                                      | 1.48 ms: 1.53x faster                                                        |
| chaos                    | 106 ms                                                       | 70.5 ms: 1.50x faster                                                        |
| async_tree_io            | 1.61 sec                                                     | 1.11 sec: 1.45x faster                                                       |
| async_tree_memoization   | 827 ms                                                       | 572 ms: 1.45x faster                                                         |
| sqlglot_transpile        | 2.73 ms                                                      | 1.89 ms: 1.44x faster                                                        |
| pickle_pure_python       | 453 us                                                       | 314 us: 1.44x faster                                                         |
| deltablue                | 7.43 ms                                                      | 5.25 ms: 1.41x faster                                                        |
| richards                 | 76.3 ms                                                      | 54.3 ms: 1.41x faster                                                        |
| coroutines               | 30.9 ms                                                      | 22.2 ms: 1.39x faster                                                        |
| crypto_pyaes             | 118 ms                                                       | 85.0 ms: 1.39x faster                                                        |
| go                       | 258 ms                                                       | 188 ms: 1.37x faster                                                         |
| logging_simple           | 9.06 us                                                      | 6.74 us: 1.34x faster                                                        |
| json_dumps               | 14.2 ms                                                      | 10.8 ms: 1.32x faster                                                        |
| bench_mp_pool            | 6.82 ms                                                      | 5.18 ms: 1.32x faster                                                        |
| logging_format           | 9.82 us                                                      | 7.47 us: 1.31x faster                                                        |
| scimark_monte_carlo      | 109 ms                                                       | 83.3 ms: 1.31x faster                                                        |
| async_tree_cpu_io_mixed  | 946 ms                                                       | 724 ms: 1.31x faster                                                         |
| xml_etree_process        | 76.4 ms                                                      | 58.5 ms: 1.31x faster                                                        |
| unpack_sequence          | 60.3 ns                                                      | 47.2 ns: 1.28x faster                                                        |
| sqlglot_normalize        | 146 ms                                                       | 117 ms: 1.25x faster                                                         |
| tornado_http             | 157 ms                                                       | 125 ms: 1.25x faster                                                         |
| pycparser                | 1.65 sec                                                     | 1.32 sec: 1.25x faster                                                       |
| unpickle_pure_python     | 315 us                                                       | 253 us: 1.25x faster                                                         |
| nbody                    | 134 ms                                                       | 109 ms: 1.23x faster                                                         |
| mypy2                    | 467 ms                                                       | 382 ms: 1.22x faster                                                         |
| sympy_sum                | 194 ms                                                       | 159 ms: 1.22x faster                                                         |
| deepcopy                 | 459 us                                                       | 378 us: 1.21x faster                                                         |
| chameleon                | 9.88 ms                                                      | 8.23 ms: 1.20x faster                                                        |
| scimark_sor              | 183 ms                                                       | 153 ms: 1.20x faster                                                         |
| deepcopy_memo            | 50.5 us                                                      | 42.2 us: 1.20x faster                                                        |
| deepcopy_reduce          | 4.00 us                                                      | 3.35 us: 1.19x faster                                                        |
| json_loads               | 30.0 us                                                      | 25.2 us: 1.19x faster                                                        |
| pyflate                  | 698 ms                                                       | 589 ms: 1.19x faster                                                         |
| sqlglot_optimize         | 69.9 ms                                                      | 59.2 ms: 1.18x faster                                                        |
| bench_thread_pool        | 1.13 ms                                                      | 979 us: 1.16x faster                                                         |
| docutils                 | 3.42 sec                                                     | 2.95 sec: 1.16x faster                                                       |
| sympy_str                | 359 ms                                                       | 311 ms: 1.15x faster                                                         |
| dask                     | 469 ms                                                       | 407 ms: 1.15x faster                                                         |
| pprint_pformat           | 2.15 sec                                                     | 1.87 sec: 1.15x faster                                                       |
| pprint_safe_repr         | 1.04 sec                                                     | 913 ms: 1.14x faster                                                         |
| sympy_expand             | 599 ms                                                       | 528 ms: 1.13x faster                                                         |
| sympy_integrate          | 28.3 ms                                                      | 25.1 ms: 1.13x faster                                                        |
| dulwich_log              | 80.0 ms                                                      | 71.3 ms: 1.12x faster                                                        |
| json                     | 5.91 ms                                                      | 5.29 ms: 1.12x faster                                                        |
| 2to3                     | 349 ms                                                       | 313 ms: 1.12x faster                                                         |
| regex_compile            | 192 ms                                                       | 173 ms: 1.11x faster                                                         |
| create_gc_cycles         | 1.79 ms                                                      | 1.62 ms: 1.11x faster                                                        |
| pathlib                  | 21.2 ms                                                      | 19.2 ms: 1.10x faster                                                        |
| async_generators         | 418 ms                                                       | 386 ms: 1.08x faster                                                         |
| float                    | 109 ms                                                       | 101 ms: 1.08x faster                                                         |
| sqlite_synth             | 2.97 us                                                      | 2.77 us: 1.07x faster                                                        |
| xml_etree_generate       | 93.1 ms                                                      | 86.9 ms: 1.07x faster                                                        |
| mdp                      | 2.94 sec                                                     | 2.75 sec: 1.07x faster                                                       |
| regex_dna                | 260 ms                                                       | 244 ms: 1.07x faster                                                         |
| xml_etree_parse          | 159 ms                                                       | 152 ms: 1.05x faster                                                         |
| regex_v8                 | 27.1 ms                                                      | 25.9 ms: 1.05x faster                                                        |
| tomli_loads              | 2.96 sec                                                     | 2.87 sec: 1.03x faster                                                       |
| asyncio_websockets       | 394 ms                                                       | 387 ms: 1.02x faster                                                         |
| pidigits                 | 270 ms                                                       | 266 ms: 1.01x faster                                                         |
| meteor_contest           | 138 ms                                                       | 137 ms: 1.00x faster                                                         |
| pickle                   | 10.1 us                                                      | 10.1 us: 1.00x slower                                                        |
| gc_traversal             | 3.63 ms                                                      | 3.68 ms: 1.01x slower                                                        |
| comprehensions           | 27.0 us                                                      | 27.8 us: 1.03x slower                                                        |
| pickle_list              | 4.23 us                                                      | 4.36 us: 1.03x slower                                                        |
| fannkuch                 | 488 ms                                                       | 506 ms: 1.04x slower                                                         |
| unpickle                 | 13.9 us                                                      | 14.5 us: 1.04x slower                                                        |
| xml_etree_iterparse      | 110 ms                                                       | 114 ms: 1.05x slower                                                         |
| unpickle_list            | 4.45 us                                                      | 4.65 us: 1.05x slower                                                        |
| nqueens                  | 112 ms                                                       | 117 ms: 1.05x slower                                                         |
| pickle_dict              | 30.4 us                                                      | 32.3 us: 1.06x slower                                                        |
| scimark_fft              | 363 ms                                                       | 396 ms: 1.09x slower                                                         |
| python_startup           | 11.5 ms                                                      | 12.9 ms: 1.12x slower                                                        |
| hexiom                   | 9.46 ms                                                      | 10.7 ms: 1.13x slower                                                        |
| regex_effbot             | 3.10 ms                                                      | 3.54 ms: 1.14x slower                                                        |
| telco                    | 7.21 ms                                                      | 8.50 ms: 1.18x slower                                                        |
| coverage                 | 65.9 ms                                                      | 82.4 ms: 1.25x slower                                                        |
| scimark_sparse_mat_mult  | 5.21 ms                                                      | 6.58 ms: 1.26x slower                                                        |
| python_startup_no_site   | 7.35 ms                                                      | 11.4 ms: 1.55x slower                                                        |
| Geometric mean           | (ref)                                                        | 1.19x faster                                                                 |

Benchmark hidden because not significant (1): mako
Ignored benchmarks (11) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
Ignored benchmarks (4) of results/bm-20231117-3.13.0a1+-0ee2d77-PYTHON_UOPS/bm-20231117-pythonperf2-x86_64-python-0ee2d77331f2362fcaab-3.13.0a1+-0ee2d77.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.14x
- 95% likely to have a speedup of 1.13x
- 99% likely to have a speedup of 1.11x
