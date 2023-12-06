
# Results vs. 3.10.4

- fork: python
- ref: main
- machine: linux-x86_64
- commit hash: 853b4b5
- commit date: 2023-11-04
- overall geometric mean: 1.29x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.23x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231104-pythonperf2-x86_64-python-main-3.13.0a1+-853b4b5 |
|----------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| 2to3           | 349 ms                                                       | 292 ms: 1.20x faster                                         |
| chameleon      | 9.88 ms                                                      | 7.49 ms: 1.32x faster                                        |
| docutils       | 3.42 sec                                                     | 2.83 sec: 1.21x faster                                       |
| tornado_http   | 157 ms                                                       | 119 ms: 1.31x faster                                         |
| Geometric mean | (ref)                                                        | 1.26x faster                                                 |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231104-pythonperf2-x86_64-python-main-3.13.0a1+-853b4b5 |
|-------------------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| async_tree_none         | 700 ms                                                       | 439 ms: 1.60x faster                                         |
| async_tree_memoization  | 827 ms                                                       | 556 ms: 1.49x faster                                         |
| async_tree_io           | 1.61 sec                                                     | 1.09 sec: 1.48x faster                                       |
| async_tree_cpu_io_mixed | 946 ms                                                       | 708 ms: 1.34x faster                                         |
| Geometric mean          | (ref)                                                        | 1.47x faster                                                 |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231104-pythonperf2-x86_64-python-main-3.13.0a1+-853b4b5 |
|----------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| nbody          | 134 ms                                                       | 85.7 ms: 1.57x faster                                        |
| float          | 109 ms                                                       | 80.6 ms: 1.35x faster                                        |
| pidigits       | 270 ms                                                       | 265 ms: 1.02x faster                                         |
| Geometric mean | (ref)                                                        | 1.29x faster                                                 |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231104-pythonperf2-x86_64-python-main-3.13.0a1+-853b4b5 |
|----------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| regex_compile  | 192 ms                                                       | 145 ms: 1.33x faster                                         |
| regex_dna      | 260 ms                                                       | 237 ms: 1.10x faster                                         |
| regex_v8       | 27.1 ms                                                      | 25.1 ms: 1.08x faster                                        |
| regex_effbot   | 3.10 ms                                                      | 3.49 ms: 1.13x slower                                        |
| Geometric mean | (ref)                                                        | 1.09x faster                                                 |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231104-pythonperf2-x86_64-python-main-3.13.0a1+-853b4b5 |
|----------------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| pickle_pure_python   | 453 us                                                       | 320 us: 1.42x faster                                         |
| json_dumps           | 14.2 ms                                                      | 10.4 ms: 1.36x faster                                        |
| tomli_loads          | 2.96 sec                                                     | 2.23 sec: 1.33x faster                                       |
| unpickle_pure_python | 315 us                                                       | 241 us: 1.31x faster                                         |
| xml_etree_process    | 76.4 ms                                                      | 58.6 ms: 1.30x faster                                        |
| json_loads           | 30.0 us                                                      | 24.1 us: 1.24x faster                                        |
| xml_etree_generate   | 93.1 ms                                                      | 85.3 ms: 1.09x faster                                        |
| xml_etree_parse      | 159 ms                                                       | 146 ms: 1.09x faster                                         |
| xml_etree_iterparse  | 110 ms                                                       | 106 ms: 1.03x faster                                         |
| unpickle             | 13.9 us                                                      | 14.3 us: 1.02x slower                                        |
| pickle_list          | 4.23 us                                                      | 4.44 us: 1.05x slower                                        |
| unpickle_list        | 4.45 us                                                      | 4.73 us: 1.06x slower                                        |
| pickle_dict          | 30.4 us                                                      | 32.4 us: 1.06x slower                                        |
| Geometric mean       | (ref)                                                        | 1.13x faster                                                 |

Benchmark hidden because not significant (1): pickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231104-pythonperf2-x86_64-python-main-3.13.0a1+-853b4b5 |
|------------------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| python_startup         | 11.5 ms                                                      | 12.8 ms: 1.11x slower                                        |
| python_startup_no_site | 7.35 ms                                                      | 11.3 ms: 1.54x slower                                        |
| Geometric mean         | (ref)                                                        | 1.31x slower                                                 |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231104-pythonperf2-x86_64-python-main-3.13.0a1+-853b4b5 |
|-----------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| mako      | 14.7 ms                                                      | 10.2 ms: 1.45x faster                                        |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231104-pythonperf2-x86_64-python-main-3.13.0a1+-853b4b5 |
|--------------------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| typing_runtime_protocols | 533 us                                                       | 121 us: 4.41x faster                                         |
| asyncio_tcp              | 785 ms                                                       | 373 ms: 2.10x faster                                         |
| deltablue                | 7.43 ms                                                      | 3.69 ms: 2.01x faster                                        |
| asyncio_tcp_ssl          | 3.13 sec                                                     | 1.58 sec: 1.98x faster                                       |
| raytrace                 | 497 ms                                                       | 278 ms: 1.79x faster                                         |
| logging_silent           | 168 ns                                                       | 96.5 ns: 1.74x faster                                        |
| chaos                    | 106 ms                                                       | 61.4 ms: 1.73x faster                                        |
| comprehensions           | 27.0 us                                                      | 16.5 us: 1.64x faster                                        |
| crypto_pyaes             | 118 ms                                                       | 72.0 ms: 1.64x faster                                        |
| sqlglot_parse            | 2.27 ms                                                      | 1.41 ms: 1.61x faster                                        |
| generators               | 57.7 ms                                                      | 36.0 ms: 1.60x faster                                        |
| scimark_monte_carlo      | 109 ms                                                       | 68.4 ms: 1.60x faster                                        |
| scimark_lu               | 165 ms                                                       | 103 ms: 1.60x faster                                         |
| async_tree_none          | 700 ms                                                       | 439 ms: 1.60x faster                                         |
| nbody                    | 134 ms                                                       | 85.7 ms: 1.57x faster                                        |
| spectral_norm            | 141 ms                                                       | 90.5 ms: 1.56x faster                                        |
| richards_super           | 93.0 ms                                                      | 59.7 ms: 1.56x faster                                        |
| sqlglot_transpile        | 2.73 ms                                                      | 1.81 ms: 1.51x faster                                        |
| go                       | 258 ms                                                       | 173 ms: 1.49x faster                                         |
| async_tree_memoization   | 827 ms                                                       | 556 ms: 1.49x faster                                         |
| hexiom                   | 9.46 ms                                                      | 6.38 ms: 1.48x faster                                        |
| async_tree_io            | 1.61 sec                                                     | 1.09 sec: 1.48x faster                                       |
| richards                 | 76.3 ms                                                      | 52.7 ms: 1.45x faster                                        |
| mako                     | 14.7 ms                                                      | 10.2 ms: 1.45x faster                                        |
| pickle_pure_python       | 453 us                                                       | 320 us: 1.42x faster                                         |
| coroutines               | 30.9 ms                                                      | 22.1 ms: 1.40x faster                                        |
| json_dumps               | 14.2 ms                                                      | 10.4 ms: 1.36x faster                                        |
| float                    | 109 ms                                                       | 80.6 ms: 1.35x faster                                        |
| async_tree_cpu_io_mixed  | 946 ms                                                       | 708 ms: 1.34x faster                                         |
| logging_simple           | 9.06 us                                                      | 6.80 us: 1.33x faster                                        |
| deepcopy_memo            | 50.5 us                                                      | 38.0 us: 1.33x faster                                        |
| regex_compile            | 192 ms                                                       | 145 ms: 1.33x faster                                         |
| tomli_loads              | 2.96 sec                                                     | 2.23 sec: 1.33x faster                                       |
| pyflate                  | 698 ms                                                       | 529 ms: 1.32x faster                                         |
| chameleon                | 9.88 ms                                                      | 7.49 ms: 1.32x faster                                        |
| logging_format           | 9.82 us                                                      | 7.47 us: 1.31x faster                                        |
| tornado_http             | 157 ms                                                       | 119 ms: 1.31x faster                                         |
| unpickle_pure_python     | 315 us                                                       | 241 us: 1.31x faster                                         |
| xml_etree_process        | 76.4 ms                                                      | 58.6 ms: 1.30x faster                                        |
| pprint_pformat           | 2.15 sec                                                     | 1.66 sec: 1.29x faster                                       |
| sqlglot_normalize        | 146 ms                                                       | 114 ms: 1.29x faster                                         |
| sympy_sum                | 194 ms                                                       | 151 ms: 1.28x faster                                         |
| pprint_safe_repr         | 1.04 sec                                                     | 810 ms: 1.28x faster                                         |
| mypy2                    | 467 ms                                                       | 367 ms: 1.27x faster                                         |
| scimark_sparse_mat_mult  | 5.21 ms                                                      | 4.12 ms: 1.26x faster                                        |
| scimark_sor              | 183 ms                                                       | 146 ms: 1.25x faster                                         |
| pycparser                | 1.65 sec                                                     | 1.32 sec: 1.25x faster                                       |
| fannkuch                 | 488 ms                                                       | 392 ms: 1.25x faster                                         |
| deepcopy                 | 459 us                                                       | 369 us: 1.25x faster                                         |
| nqueens                  | 112 ms                                                       | 89.8 ms: 1.25x faster                                        |
| sympy_str                | 359 ms                                                       | 288 ms: 1.24x faster                                         |
| json_loads               | 30.0 us                                                      | 24.1 us: 1.24x faster                                        |
| sympy_integrate          | 28.3 ms                                                      | 22.9 ms: 1.24x faster                                        |
| sympy_expand             | 599 ms                                                       | 490 ms: 1.22x faster                                         |
| deepcopy_reduce          | 4.00 us                                                      | 3.28 us: 1.22x faster                                        |
| bench_mp_pool            | 6.82 ms                                                      | 5.61 ms: 1.22x faster                                        |
| unpack_sequence          | 60.3 ns                                                      | 49.9 ns: 1.21x faster                                        |
| docutils                 | 3.42 sec                                                     | 2.83 sec: 1.21x faster                                       |
| sqlglot_optimize         | 69.9 ms                                                      | 58.0 ms: 1.20x faster                                        |
| scimark_fft              | 363 ms                                                       | 302 ms: 1.20x faster                                         |
| 2to3                     | 349 ms                                                       | 292 ms: 1.20x faster                                         |
| bench_thread_pool        | 1.13 ms                                                      | 957 us: 1.19x faster                                         |
| dulwich_log              | 80.0 ms                                                      | 68.6 ms: 1.17x faster                                        |
| async_generators         | 418 ms                                                       | 361 ms: 1.16x faster                                         |
| mdp                      | 2.94 sec                                                     | 2.55 sec: 1.15x faster                                       |
| json                     | 5.91 ms                                                      | 5.12 ms: 1.15x faster                                        |
| create_gc_cycles         | 1.79 ms                                                      | 1.57 ms: 1.14x faster                                        |
| sqlite_synth             | 2.97 us                                                      | 2.66 us: 1.12x faster                                        |
| regex_dna                | 260 ms                                                       | 237 ms: 1.10x faster                                         |
| xml_etree_generate       | 93.1 ms                                                      | 85.3 ms: 1.09x faster                                        |
| xml_etree_parse          | 159 ms                                                       | 146 ms: 1.09x faster                                         |
| regex_v8                 | 27.1 ms                                                      | 25.1 ms: 1.08x faster                                        |
| pathlib                  | 21.2 ms                                                      | 19.7 ms: 1.08x faster                                        |
| meteor_contest           | 138 ms                                                       | 129 ms: 1.07x faster                                         |
| xml_etree_iterparse      | 110 ms                                                       | 106 ms: 1.03x faster                                         |
| pidigits                 | 270 ms                                                       | 265 ms: 1.02x faster                                         |
| asyncio_websockets       | 394 ms                                                       | 388 ms: 1.02x faster                                         |
| unpickle                 | 13.9 us                                                      | 14.3 us: 1.02x slower                                        |
| gc_traversal             | 3.63 ms                                                      | 3.73 ms: 1.03x slower                                        |
| pickle_list              | 4.23 us                                                      | 4.44 us: 1.05x slower                                        |
| unpickle_list            | 4.45 us                                                      | 4.73 us: 1.06x slower                                        |
| pickle_dict              | 30.4 us                                                      | 32.4 us: 1.06x slower                                        |
| telco                    | 7.21 ms                                                      | 7.97 ms: 1.10x slower                                        |
| python_startup           | 11.5 ms                                                      | 12.8 ms: 1.11x slower                                        |
| regex_effbot             | 3.10 ms                                                      | 3.49 ms: 1.13x slower                                        |
| coverage                 | 65.9 ms                                                      | 78.3 ms: 1.19x slower                                        |
| python_startup_no_site   | 7.35 ms                                                      | 11.3 ms: 1.54x slower                                        |
| Geometric mean           | (ref)                                                        | 1.29x faster                                                 |

Benchmark hidden because not significant (1): pickle
Ignored benchmarks (12) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, dask, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
Ignored benchmarks (4) of results/bm-20231104-3.13.0a1+-853b4b5/bm-20231104-pythonperf2-x86_64-python-main-3.13.0a1+-853b4b5.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.25x
- 95% likely to have a speedup of 1.24x
- 99% likely to have a speedup of 1.23x
