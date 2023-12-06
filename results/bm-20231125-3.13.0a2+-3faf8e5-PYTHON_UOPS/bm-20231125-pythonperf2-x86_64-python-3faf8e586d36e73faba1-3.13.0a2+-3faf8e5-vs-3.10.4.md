
# Results vs. 3.10.4

- fork: python
- ref: 3faf8e586d36e73faba1
- machine: linux-x86_64
- commit hash: 3faf8e5
- commit date: 2023-11-25
- overall geometric mean: 1.18x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.09x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231125-pythonperf2-x86_64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| 2to3           | 349 ms                                                       | 317 ms: 1.10x faster                                                         |
| chameleon      | 9.88 ms                                                      | 8.21 ms: 1.20x faster                                                        |
| docutils       | 3.42 sec                                                     | 2.95 sec: 1.16x faster                                                       |
| tornado_http   | 157 ms                                                       | 126 ms: 1.24x faster                                                         |
| Geometric mean | (ref)                                                        | 1.18x faster                                                                 |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231125-pythonperf2-x86_64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|-------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| async_tree_none         | 700 ms                                                       | 449 ms: 1.56x faster                                                         |
| async_tree_memoization  | 827 ms                                                       | 561 ms: 1.47x faster                                                         |
| async_tree_io           | 1.61 sec                                                     | 1.10 sec: 1.46x faster                                                       |
| async_tree_cpu_io_mixed | 946 ms                                                       | 713 ms: 1.33x faster                                                         |
| Geometric mean          | (ref)                                                        | 1.45x faster                                                                 |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231125-pythonperf2-x86_64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| float          | 109 ms                                                       | 102 ms: 1.07x faster                                                         |
| nbody          | 134 ms                                                       | 129 ms: 1.04x faster                                                         |
| pidigits       | 270 ms                                                       | 267 ms: 1.01x faster                                                         |
| Geometric mean | (ref)                                                        | 1.04x faster                                                                 |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231125-pythonperf2-x86_64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| regex_compile  | 192 ms                                                       | 175 ms: 1.10x faster                                                         |
| regex_v8       | 27.1 ms                                                      | 25.9 ms: 1.05x faster                                                        |
| regex_dna      | 260 ms                                                       | 251 ms: 1.04x faster                                                         |
| regex_effbot   | 3.10 ms                                                      | 3.50 ms: 1.13x slower                                                        |
| Geometric mean | (ref)                                                        | 1.01x faster                                                                 |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231125-pythonperf2-x86_64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|----------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| pickle_pure_python   | 453 us                                                       | 316 us: 1.43x faster                                                         |
| json_dumps           | 14.2 ms                                                      | 10.8 ms: 1.32x faster                                                        |
| unpickle_pure_python | 315 us                                                       | 249 us: 1.27x faster                                                         |
| xml_etree_process    | 76.4 ms                                                      | 60.9 ms: 1.25x faster                                                        |
| json_loads           | 30.0 us                                                      | 25.3 us: 1.19x faster                                                        |
| tomli_loads          | 2.96 sec                                                     | 2.78 sec: 1.07x faster                                                       |
| xml_etree_parse      | 159 ms                                                       | 151 ms: 1.05x faster                                                         |
| xml_etree_generate   | 93.1 ms                                                      | 90.9 ms: 1.02x faster                                                        |
| pickle_list          | 4.23 us                                                      | 4.36 us: 1.03x slower                                                        |
| unpickle_list        | 4.45 us                                                      | 4.58 us: 1.03x slower                                                        |
| unpickle             | 13.9 us                                                      | 14.7 us: 1.05x slower                                                        |
| xml_etree_iterparse  | 110 ms                                                       | 118 ms: 1.08x slower                                                         |
| pickle_dict          | 30.4 us                                                      | 33.1 us: 1.09x slower                                                        |
| Geometric mean       | (ref)                                                        | 1.08x faster                                                                 |

Benchmark hidden because not significant (1): pickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231125-pythonperf2-x86_64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| python_startup         | 11.5 ms                                                      | 12.9 ms: 1.12x slower                                                        |
| python_startup_no_site | 7.35 ms                                                      | 11.3 ms: 1.54x slower                                                        |
| Geometric mean         | (ref)                                                        | 1.31x slower                                                                 |

Benchmarks with tag 'template':
===============================

Benchmark hidden because not significant (1): mako

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231125-pythonperf2-x86_64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|--------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| typing_runtime_protocols | 533 us                                                       | 131 us: 4.07x faster                                                         |
| asyncio_tcp              | 785 ms                                                       | 371 ms: 2.11x faster                                                         |
| asyncio_tcp_ssl          | 3.13 sec                                                     | 1.59 sec: 1.97x faster                                                       |
| logging_silent           | 168 ns                                                       | 98.7 ns: 1.70x faster                                                        |
| generators               | 57.7 ms                                                      | 34.7 ms: 1.66x faster                                                        |
| raytrace                 | 497 ms                                                       | 312 ms: 1.60x faster                                                         |
| async_tree_none          | 700 ms                                                       | 449 ms: 1.56x faster                                                         |
| scimark_lu               | 165 ms                                                       | 106 ms: 1.55x faster                                                         |
| richards_super           | 93.0 ms                                                      | 60.1 ms: 1.55x faster                                                        |
| sqlglot_parse            | 2.27 ms                                                      | 1.48 ms: 1.53x faster                                                        |
| async_tree_memoization   | 827 ms                                                       | 561 ms: 1.47x faster                                                         |
| async_tree_io            | 1.61 sec                                                     | 1.10 sec: 1.46x faster                                                       |
| bench_mp_pool            | 6.82 ms                                                      | 4.74 ms: 1.44x faster                                                        |
| sqlglot_transpile        | 2.73 ms                                                      | 1.90 ms: 1.44x faster                                                        |
| pickle_pure_python       | 453 us                                                       | 316 us: 1.43x faster                                                         |
| go                       | 258 ms                                                       | 182 ms: 1.42x faster                                                         |
| richards                 | 76.3 ms                                                      | 54.1 ms: 1.41x faster                                                        |
| unpack_sequence          | 60.3 ns                                                      | 42.8 ns: 1.41x faster                                                        |
| coroutines               | 30.9 ms                                                      | 22.2 ms: 1.39x faster                                                        |
| crypto_pyaes             | 118 ms                                                       | 86.0 ms: 1.37x faster                                                        |
| chaos                    | 106 ms                                                       | 77.8 ms: 1.36x faster                                                        |
| deltablue                | 7.43 ms                                                      | 5.52 ms: 1.34x faster                                                        |
| async_tree_cpu_io_mixed  | 946 ms                                                       | 713 ms: 1.33x faster                                                         |
| logging_simple           | 9.06 us                                                      | 6.84 us: 1.33x faster                                                        |
| json_dumps               | 14.2 ms                                                      | 10.8 ms: 1.32x faster                                                        |
| logging_format           | 9.82 us                                                      | 7.56 us: 1.30x faster                                                        |
| deepcopy_memo            | 50.5 us                                                      | 39.2 us: 1.29x faster                                                        |
| unpickle_pure_python     | 315 us                                                       | 249 us: 1.27x faster                                                         |
| xml_etree_process        | 76.4 ms                                                      | 60.9 ms: 1.25x faster                                                        |
| deepcopy                 | 459 us                                                       | 367 us: 1.25x faster                                                         |
| pycparser                | 1.65 sec                                                     | 1.33 sec: 1.24x faster                                                       |
| tornado_http             | 157 ms                                                       | 126 ms: 1.24x faster                                                         |
| scimark_sor              | 183 ms                                                       | 149 ms: 1.23x faster                                                         |
| deepcopy_reduce          | 4.00 us                                                      | 3.27 us: 1.22x faster                                                        |
| mypy2                    | 467 ms                                                       | 382 ms: 1.22x faster                                                         |
| pyflate                  | 698 ms                                                       | 578 ms: 1.21x faster                                                         |
| chameleon                | 9.88 ms                                                      | 8.21 ms: 1.20x faster                                                        |
| json_loads               | 30.0 us                                                      | 25.3 us: 1.19x faster                                                        |
| scimark_monte_carlo      | 109 ms                                                       | 92.1 ms: 1.19x faster                                                        |
| sqlglot_normalize        | 146 ms                                                       | 125 ms: 1.17x faster                                                         |
| bench_thread_pool        | 1.13 ms                                                      | 976 us: 1.16x faster                                                         |
| docutils                 | 3.42 sec                                                     | 2.95 sec: 1.16x faster                                                       |
| sympy_sum                | 194 ms                                                       | 169 ms: 1.15x faster                                                         |
| pprint_pformat           | 2.15 sec                                                     | 1.88 sec: 1.14x faster                                                       |
| dask                     | 469 ms                                                       | 411 ms: 1.14x faster                                                         |
| pprint_safe_repr         | 1.04 sec                                                     | 916 ms: 1.14x faster                                                         |
| sympy_integrate          | 28.3 ms                                                      | 25.1 ms: 1.13x faster                                                        |
| json                     | 5.91 ms                                                      | 5.27 ms: 1.12x faster                                                        |
| dulwich_log              | 80.0 ms                                                      | 71.5 ms: 1.12x faster                                                        |
| 2to3                     | 349 ms                                                       | 317 ms: 1.10x faster                                                         |
| create_gc_cycles         | 1.79 ms                                                      | 1.62 ms: 1.10x faster                                                        |
| sqlglot_optimize         | 69.9 ms                                                      | 63.6 ms: 1.10x faster                                                        |
| regex_compile            | 192 ms                                                       | 175 ms: 1.10x faster                                                         |
| sympy_expand             | 599 ms                                                       | 545 ms: 1.10x faster                                                         |
| mdp                      | 2.94 sec                                                     | 2.68 sec: 1.10x faster                                                       |
| pathlib                  | 21.2 ms                                                      | 19.3 ms: 1.10x faster                                                        |
| sympy_str                | 359 ms                                                       | 327 ms: 1.10x faster                                                         |
| async_generators         | 418 ms                                                       | 388 ms: 1.08x faster                                                         |
| float                    | 109 ms                                                       | 102 ms: 1.07x faster                                                         |
| comprehensions           | 27.0 us                                                      | 25.4 us: 1.07x faster                                                        |
| tomli_loads              | 2.96 sec                                                     | 2.78 sec: 1.07x faster                                                       |
| sqlite_synth             | 2.97 us                                                      | 2.81 us: 1.06x faster                                                        |
| xml_etree_parse          | 159 ms                                                       | 151 ms: 1.05x faster                                                         |
| regex_v8                 | 27.1 ms                                                      | 25.9 ms: 1.05x faster                                                        |
| nbody                    | 134 ms                                                       | 129 ms: 1.04x faster                                                         |
| regex_dna                | 260 ms                                                       | 251 ms: 1.04x faster                                                         |
| nqueens                  | 112 ms                                                       | 109 ms: 1.03x faster                                                         |
| fannkuch                 | 488 ms                                                       | 475 ms: 1.03x faster                                                         |
| xml_etree_generate       | 93.1 ms                                                      | 90.9 ms: 1.02x faster                                                        |
| pidigits                 | 270 ms                                                       | 267 ms: 1.01x faster                                                         |
| asyncio_websockets       | 394 ms                                                       | 390 ms: 1.01x faster                                                         |
| meteor_contest           | 138 ms                                                       | 140 ms: 1.02x slower                                                         |
| pickle_list              | 4.23 us                                                      | 4.36 us: 1.03x slower                                                        |
| unpickle_list            | 4.45 us                                                      | 4.58 us: 1.03x slower                                                        |
| hexiom                   | 9.46 ms                                                      | 9.89 ms: 1.05x slower                                                        |
| unpickle                 | 13.9 us                                                      | 14.7 us: 1.05x slower                                                        |
| xml_etree_iterparse      | 110 ms                                                       | 118 ms: 1.08x slower                                                         |
| pickle_dict              | 30.4 us                                                      | 33.1 us: 1.09x slower                                                        |
| python_startup           | 11.5 ms                                                      | 12.9 ms: 1.12x slower                                                        |
| regex_effbot             | 3.10 ms                                                      | 3.50 ms: 1.13x slower                                                        |
| gc_traversal             | 3.63 ms                                                      | 4.18 ms: 1.15x slower                                                        |
| spectral_norm            | 141 ms                                                       | 165 ms: 1.17x slower                                                         |
| telco                    | 7.21 ms                                                      | 8.48 ms: 1.18x slower                                                        |
| coverage                 | 65.9 ms                                                      | 80.1 ms: 1.22x slower                                                        |
| scimark_fft              | 363 ms                                                       | 451 ms: 1.24x slower                                                         |
| scimark_sparse_mat_mult  | 5.21 ms                                                      | 6.75 ms: 1.29x slower                                                        |
| python_startup_no_site   | 7.35 ms                                                      | 11.3 ms: 1.54x slower                                                        |
| Geometric mean           | (ref)                                                        | 1.18x faster                                                                 |

Benchmark hidden because not significant (2): mako, pickle
Ignored benchmarks (11) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
Ignored benchmarks (4) of results/bm-20231125-3.13.0a2+-3faf8e5-PYTHON_UOPS/bm-20231125-pythonperf2-x86_64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.11x
- 95% likely to have a speedup of 1.10x
- 99% likely to have a speedup of 1.09x
