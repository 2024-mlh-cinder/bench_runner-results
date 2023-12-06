
# Results vs. 3.10.4

- fork: python
- ref: 3faf8e586d36e73faba1
- machine: linux-x86_64
- commit hash: 3faf8e5
- commit date: 2023-11-25
- overall geometric mean: 1.30x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.23x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231125-pythonperf2-x86_64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| 2to3           | 349 ms                                                       | 290 ms: 1.20x faster                                                         |
| chameleon      | 9.88 ms                                                      | 7.59 ms: 1.30x faster                                                        |
| docutils       | 3.42 sec                                                     | 2.82 sec: 1.21x faster                                                       |
| tornado_http   | 157 ms                                                       | 119 ms: 1.31x faster                                                         |
| Geometric mean | (ref)                                                        | 1.26x faster                                                                 |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231125-pythonperf2-x86_64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|-------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| async_tree_none         | 700 ms                                                       | 434 ms: 1.61x faster                                                         |
| async_tree_memoization  | 827 ms                                                       | 542 ms: 1.53x faster                                                         |
| async_tree_io           | 1.61 sec                                                     | 1.07 sec: 1.50x faster                                                       |
| async_tree_cpu_io_mixed | 946 ms                                                       | 692 ms: 1.37x faster                                                         |
| Geometric mean          | (ref)                                                        | 1.50x faster                                                                 |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231125-pythonperf2-x86_64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| nbody          | 134 ms                                                       | 83.7 ms: 1.60x faster                                                        |
| float          | 109 ms                                                       | 79.7 ms: 1.36x faster                                                        |
| pidigits       | 270 ms                                                       | 266 ms: 1.02x faster                                                         |
| Geometric mean | (ref)                                                        | 1.30x faster                                                                 |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231125-pythonperf2-x86_64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| regex_compile  | 192 ms                                                       | 142 ms: 1.35x faster                                                         |
| regex_dna      | 260 ms                                                       | 235 ms: 1.11x faster                                                         |
| regex_v8       | 27.1 ms                                                      | 25.1 ms: 1.08x faster                                                        |
| regex_effbot   | 3.10 ms                                                      | 3.53 ms: 1.14x slower                                                        |
| Geometric mean | (ref)                                                        | 1.09x faster                                                                 |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231125-pythonperf2-x86_64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|----------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| unpickle_pure_python | 315 us                                                       | 210 us: 1.50x faster                                                         |
| pickle_pure_python   | 453 us                                                       | 308 us: 1.47x faster                                                         |
| json_dumps           | 14.2 ms                                                      | 10.5 ms: 1.35x faster                                                        |
| tomli_loads          | 2.96 sec                                                     | 2.22 sec: 1.33x faster                                                       |
| xml_etree_process    | 76.4 ms                                                      | 58.3 ms: 1.31x faster                                                        |
| json_loads           | 30.0 us                                                      | 25.3 us: 1.19x faster                                                        |
| xml_etree_generate   | 93.1 ms                                                      | 84.1 ms: 1.11x faster                                                        |
| xml_etree_parse      | 159 ms                                                       | 147 ms: 1.09x faster                                                         |
| xml_etree_iterparse  | 110 ms                                                       | 107 ms: 1.03x faster                                                         |
| pickle               | 10.1 us                                                      | 10.2 us: 1.02x slower                                                        |
| pickle_dict          | 30.4 us                                                      | 32.0 us: 1.05x slower                                                        |
| pickle_list          | 4.23 us                                                      | 4.45 us: 1.05x slower                                                        |
| unpickle             | 13.9 us                                                      | 14.8 us: 1.06x slower                                                        |
| unpickle_list        | 4.45 us                                                      | 4.79 us: 1.08x slower                                                        |
| Geometric mean       | (ref)                                                        | 1.14x faster                                                                 |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231125-pythonperf2-x86_64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| python_startup         | 11.5 ms                                                      | 12.8 ms: 1.11x slower                                                        |
| python_startup_no_site | 7.35 ms                                                      | 11.2 ms: 1.53x slower                                                        |
| Geometric mean         | (ref)                                                        | 1.30x slower                                                                 |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231125-pythonperf2-x86_64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|-----------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| mako      | 14.7 ms                                                      | 10.1 ms: 1.46x faster                                                        |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231125-pythonperf2-x86_64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|--------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| typing_runtime_protocols | 533 us                                                       | 123 us: 4.34x faster                                                         |
| asyncio_tcp              | 785 ms                                                       | 367 ms: 2.14x faster                                                         |
| deltablue                | 7.43 ms                                                      | 3.58 ms: 2.07x faster                                                        |
| asyncio_tcp_ssl          | 3.13 sec                                                     | 1.57 sec: 1.99x faster                                                       |
| raytrace                 | 497 ms                                                       | 276 ms: 1.80x faster                                                         |
| logging_silent           | 168 ns                                                       | 98.1 ns: 1.71x faster                                                        |
| chaos                    | 106 ms                                                       | 62.6 ms: 1.69x faster                                                        |
| crypto_pyaes             | 118 ms                                                       | 71.3 ms: 1.65x faster                                                        |
| sqlglot_parse            | 2.27 ms                                                      | 1.38 ms: 1.65x faster                                                        |
| generators               | 57.7 ms                                                      | 35.1 ms: 1.64x faster                                                        |
| scimark_lu               | 165 ms                                                       | 100 ms: 1.64x faster                                                         |
| comprehensions           | 27.0 us                                                      | 16.5 us: 1.63x faster                                                        |
| async_tree_none          | 700 ms                                                       | 434 ms: 1.61x faster                                                         |
| nbody                    | 134 ms                                                       | 83.7 ms: 1.60x faster                                                        |
| scimark_monte_carlo      | 109 ms                                                       | 70.1 ms: 1.56x faster                                                        |
| richards_super           | 93.0 ms                                                      | 59.6 ms: 1.56x faster                                                        |
| bench_mp_pool            | 6.82 ms                                                      | 4.44 ms: 1.54x faster                                                        |
| go                       | 258 ms                                                       | 168 ms: 1.53x faster                                                         |
| sqlglot_transpile        | 2.73 ms                                                      | 1.78 ms: 1.53x faster                                                        |
| spectral_norm            | 141 ms                                                       | 92.4 ms: 1.53x faster                                                        |
| async_tree_memoization   | 827 ms                                                       | 542 ms: 1.53x faster                                                         |
| async_tree_io            | 1.61 sec                                                     | 1.07 sec: 1.50x faster                                                       |
| unpickle_pure_python     | 315 us                                                       | 210 us: 1.50x faster                                                         |
| hexiom                   | 9.46 ms                                                      | 6.42 ms: 1.47x faster                                                        |
| pickle_pure_python       | 453 us                                                       | 308 us: 1.47x faster                                                         |
| mako                     | 14.7 ms                                                      | 10.1 ms: 1.46x faster                                                        |
| logging_simple           | 9.06 us                                                      | 6.42 us: 1.41x faster                                                        |
| richards                 | 76.3 ms                                                      | 54.3 ms: 1.41x faster                                                        |
| logging_format           | 9.82 us                                                      | 7.02 us: 1.40x faster                                                        |
| deepcopy_memo            | 50.5 us                                                      | 36.2 us: 1.39x faster                                                        |
| pyflate                  | 698 ms                                                       | 504 ms: 1.39x faster                                                         |
| async_tree_cpu_io_mixed  | 946 ms                                                       | 692 ms: 1.37x faster                                                         |
| coroutines               | 30.9 ms                                                      | 22.6 ms: 1.37x faster                                                        |
| float                    | 109 ms                                                       | 79.7 ms: 1.36x faster                                                        |
| regex_compile            | 192 ms                                                       | 142 ms: 1.35x faster                                                         |
| json_dumps               | 14.2 ms                                                      | 10.5 ms: 1.35x faster                                                        |
| pprint_pformat           | 2.15 sec                                                     | 1.60 sec: 1.34x faster                                                       |
| tomli_loads              | 2.96 sec                                                     | 2.22 sec: 1.33x faster                                                       |
| pprint_safe_repr         | 1.04 sec                                                     | 783 ms: 1.33x faster                                                         |
| tornado_http             | 157 ms                                                       | 119 ms: 1.31x faster                                                         |
| xml_etree_process        | 76.4 ms                                                      | 58.3 ms: 1.31x faster                                                        |
| chameleon                | 9.88 ms                                                      | 7.59 ms: 1.30x faster                                                        |
| unpack_sequence          | 60.3 ns                                                      | 46.6 ns: 1.29x faster                                                        |
| sympy_sum                | 194 ms                                                       | 151 ms: 1.28x faster                                                         |
| fannkuch                 | 488 ms                                                       | 382 ms: 1.28x faster                                                         |
| deepcopy                 | 459 us                                                       | 359 us: 1.28x faster                                                         |
| mypy2                    | 467 ms                                                       | 366 ms: 1.27x faster                                                         |
| sqlglot_normalize        | 146 ms                                                       | 115 ms: 1.27x faster                                                         |
| nqueens                  | 112 ms                                                       | 88.7 ms: 1.26x faster                                                        |
| scimark_sparse_mat_mult  | 5.21 ms                                                      | 4.14 ms: 1.26x faster                                                        |
| pycparser                | 1.65 sec                                                     | 1.32 sec: 1.25x faster                                                       |
| sympy_str                | 359 ms                                                       | 288 ms: 1.24x faster                                                         |
| scimark_sor              | 183 ms                                                       | 148 ms: 1.24x faster                                                         |
| sympy_integrate          | 28.3 ms                                                      | 23.0 ms: 1.23x faster                                                        |
| sympy_expand             | 599 ms                                                       | 488 ms: 1.23x faster                                                         |
| deepcopy_reduce          | 4.00 us                                                      | 3.26 us: 1.23x faster                                                        |
| docutils                 | 3.42 sec                                                     | 2.82 sec: 1.21x faster                                                       |
| 2to3                     | 349 ms                                                       | 290 ms: 1.20x faster                                                         |
| sqlglot_optimize         | 69.9 ms                                                      | 58.1 ms: 1.20x faster                                                        |
| dask                     | 469 ms                                                       | 392 ms: 1.19x faster                                                         |
| json_loads               | 30.0 us                                                      | 25.3 us: 1.19x faster                                                        |
| dulwich_log              | 80.0 ms                                                      | 68.0 ms: 1.18x faster                                                        |
| bench_thread_pool        | 1.13 ms                                                      | 965 us: 1.18x faster                                                         |
| scimark_fft              | 363 ms                                                       | 310 ms: 1.17x faster                                                         |
| mdp                      | 2.94 sec                                                     | 2.52 sec: 1.17x faster                                                       |
| async_generators         | 418 ms                                                       | 359 ms: 1.16x faster                                                         |
| pathlib                  | 21.2 ms                                                      | 18.6 ms: 1.14x faster                                                        |
| json                     | 5.91 ms                                                      | 5.20 ms: 1.14x faster                                                        |
| create_gc_cycles         | 1.79 ms                                                      | 1.61 ms: 1.11x faster                                                        |
| sqlite_synth             | 2.97 us                                                      | 2.68 us: 1.11x faster                                                        |
| xml_etree_generate       | 93.1 ms                                                      | 84.1 ms: 1.11x faster                                                        |
| regex_dna                | 260 ms                                                       | 235 ms: 1.11x faster                                                         |
| xml_etree_parse          | 159 ms                                                       | 147 ms: 1.09x faster                                                         |
| regex_v8                 | 27.1 ms                                                      | 25.1 ms: 1.08x faster                                                        |
| meteor_contest           | 138 ms                                                       | 129 ms: 1.06x faster                                                         |
| xml_etree_iterparse      | 110 ms                                                       | 107 ms: 1.03x faster                                                         |
| pidigits                 | 270 ms                                                       | 266 ms: 1.02x faster                                                         |
| asyncio_websockets       | 394 ms                                                       | 389 ms: 1.01x faster                                                         |
| pickle                   | 10.1 us                                                      | 10.2 us: 1.02x slower                                                        |
| gc_traversal             | 3.63 ms                                                      | 3.74 ms: 1.03x slower                                                        |
| pickle_dict              | 30.4 us                                                      | 32.0 us: 1.05x slower                                                        |
| pickle_list              | 4.23 us                                                      | 4.45 us: 1.05x slower                                                        |
| unpickle                 | 13.9 us                                                      | 14.8 us: 1.06x slower                                                        |
| unpickle_list            | 4.45 us                                                      | 4.79 us: 1.08x slower                                                        |
| python_startup           | 11.5 ms                                                      | 12.8 ms: 1.11x slower                                                        |
| telco                    | 7.21 ms                                                      | 8.01 ms: 1.11x slower                                                        |
| regex_effbot             | 3.10 ms                                                      | 3.53 ms: 1.14x slower                                                        |
| coverage                 | 65.9 ms                                                      | 84.2 ms: 1.28x slower                                                        |
| python_startup_no_site   | 7.35 ms                                                      | 11.2 ms: 1.53x slower                                                        |
| Geometric mean           | (ref)                                                        | 1.30x faster                                                                 |
Ignored benchmarks (11) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
Ignored benchmarks (4) of results/bm-20231125-3.13.0a2+-3faf8e5/bm-20231125-pythonperf2-x86_64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.25x
- 95% likely to have a speedup of 1.25x
- 99% likely to have a speedup of 1.23x
