
# Results vs. 3.10.4

- fork: python
- ref: 1a969b4f55f92a17bec8
- machine: linux-x86_64
- commit hash: 1a969b4
- commit date: 2023-11-19
- overall geometric mean: 1.29x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.23x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231119-pythonperf2-x86_64-python-1a969b4f55f92a17bec8-3.13.0a1+-1a969b4 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| 2to3           | 349 ms                                                       | 293 ms: 1.19x faster                                                         |
| chameleon      | 9.88 ms                                                      | 7.58 ms: 1.30x faster                                                        |
| docutils       | 3.42 sec                                                     | 2.82 sec: 1.21x faster                                                       |
| tornado_http   | 157 ms                                                       | 118 ms: 1.33x faster                                                         |
| Geometric mean | (ref)                                                        | 1.26x faster                                                                 |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231119-pythonperf2-x86_64-python-1a969b4f55f92a17bec8-3.13.0a1+-1a969b4 |
|-------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| async_tree_none         | 700 ms                                                       | 433 ms: 1.62x faster                                                         |
| async_tree_memoization  | 827 ms                                                       | 545 ms: 1.52x faster                                                         |
| async_tree_io           | 1.61 sec                                                     | 1.08 sec: 1.49x faster                                                       |
| async_tree_cpu_io_mixed | 946 ms                                                       | 693 ms: 1.37x faster                                                         |
| Geometric mean          | (ref)                                                        | 1.50x faster                                                                 |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231119-pythonperf2-x86_64-python-1a969b4f55f92a17bec8-3.13.0a1+-1a969b4 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| nbody          | 134 ms                                                       | 83.7 ms: 1.60x faster                                                        |
| float          | 109 ms                                                       | 80.7 ms: 1.35x faster                                                        |
| pidigits       | 270 ms                                                       | 265 ms: 1.02x faster                                                         |
| Geometric mean | (ref)                                                        | 1.30x faster                                                                 |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231119-pythonperf2-x86_64-python-1a969b4f55f92a17bec8-3.13.0a1+-1a969b4 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| regex_compile  | 192 ms                                                       | 145 ms: 1.33x faster                                                         |
| regex_v8       | 27.1 ms                                                      | 25.2 ms: 1.07x faster                                                        |
| regex_dna      | 260 ms                                                       | 251 ms: 1.04x faster                                                         |
| regex_effbot   | 3.10 ms                                                      | 3.49 ms: 1.13x slower                                                        |
| Geometric mean | (ref)                                                        | 1.07x faster                                                                 |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231119-pythonperf2-x86_64-python-1a969b4f55f92a17bec8-3.13.0a1+-1a969b4 |
|----------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| pickle_pure_python   | 453 us                                                       | 309 us: 1.47x faster                                                         |
| unpickle_pure_python | 315 us                                                       | 229 us: 1.37x faster                                                         |
| json_dumps           | 14.2 ms                                                      | 10.5 ms: 1.36x faster                                                        |
| xml_etree_process    | 76.4 ms                                                      | 58.2 ms: 1.31x faster                                                        |
| tomli_loads          | 2.96 sec                                                     | 2.29 sec: 1.29x faster                                                       |
| json_loads           | 30.0 us                                                      | 25.2 us: 1.19x faster                                                        |
| xml_etree_generate   | 93.1 ms                                                      | 85.3 ms: 1.09x faster                                                        |
| xml_etree_parse      | 159 ms                                                       | 151 ms: 1.06x faster                                                         |
| xml_etree_iterparse  | 110 ms                                                       | 107 ms: 1.02x faster                                                         |
| unpickle             | 13.9 us                                                      | 14.2 us: 1.02x slower                                                        |
| pickle_list          | 4.23 us                                                      | 4.39 us: 1.04x slower                                                        |
| unpickle_list        | 4.45 us                                                      | 4.64 us: 1.04x slower                                                        |
| pickle_dict          | 30.4 us                                                      | 32.2 us: 1.06x slower                                                        |
| Geometric mean       | (ref)                                                        | 1.13x faster                                                                 |

Benchmark hidden because not significant (1): pickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231119-pythonperf2-x86_64-python-1a969b4f55f92a17bec8-3.13.0a1+-1a969b4 |
|------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| python_startup         | 11.5 ms                                                      | 12.8 ms: 1.11x slower                                                        |
| python_startup_no_site | 7.35 ms                                                      | 11.2 ms: 1.53x slower                                                        |
| Geometric mean         | (ref)                                                        | 1.30x slower                                                                 |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231119-pythonperf2-x86_64-python-1a969b4f55f92a17bec8-3.13.0a1+-1a969b4 |
|-----------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| mako      | 14.7 ms                                                      | 10.1 ms: 1.46x faster                                                        |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231119-pythonperf2-x86_64-python-1a969b4f55f92a17bec8-3.13.0a1+-1a969b4 |
|--------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| typing_runtime_protocols | 533 us                                                       | 127 us: 4.21x faster                                                         |
| asyncio_tcp              | 785 ms                                                       | 375 ms: 2.09x faster                                                         |
| deltablue                | 7.43 ms                                                      | 3.55 ms: 2.09x faster                                                        |
| asyncio_tcp_ssl          | 3.13 sec                                                     | 1.57 sec: 1.99x faster                                                       |
| raytrace                 | 497 ms                                                       | 268 ms: 1.86x faster                                                         |
| chaos                    | 106 ms                                                       | 60.4 ms: 1.75x faster                                                        |
| logging_silent           | 168 ns                                                       | 96.6 ns: 1.74x faster                                                        |
| generators               | 57.7 ms                                                      | 34.3 ms: 1.68x faster                                                        |
| crypto_pyaes             | 118 ms                                                       | 70.4 ms: 1.67x faster                                                        |
| scimark_monte_carlo      | 109 ms                                                       | 67.4 ms: 1.62x faster                                                        |
| comprehensions           | 27.0 us                                                      | 16.7 us: 1.62x faster                                                        |
| async_tree_none          | 700 ms                                                       | 433 ms: 1.62x faster                                                         |
| sqlglot_parse            | 2.27 ms                                                      | 1.41 ms: 1.61x faster                                                        |
| richards_super           | 93.0 ms                                                      | 58.0 ms: 1.60x faster                                                        |
| nbody                    | 134 ms                                                       | 83.7 ms: 1.60x faster                                                        |
| scimark_lu               | 165 ms                                                       | 103 ms: 1.60x faster                                                         |
| spectral_norm            | 141 ms                                                       | 90.4 ms: 1.56x faster                                                        |
| go                       | 258 ms                                                       | 168 ms: 1.53x faster                                                         |
| async_tree_memoization   | 827 ms                                                       | 545 ms: 1.52x faster                                                         |
| sqlglot_transpile        | 2.73 ms                                                      | 1.82 ms: 1.50x faster                                                        |
| async_tree_io            | 1.61 sec                                                     | 1.08 sec: 1.49x faster                                                       |
| hexiom                   | 9.46 ms                                                      | 6.39 ms: 1.48x faster                                                        |
| pickle_pure_python       | 453 us                                                       | 309 us: 1.47x faster                                                         |
| richards                 | 76.3 ms                                                      | 52.3 ms: 1.46x faster                                                        |
| mako                     | 14.7 ms                                                      | 10.1 ms: 1.46x faster                                                        |
| logging_simple           | 9.06 us                                                      | 6.50 us: 1.39x faster                                                        |
| coroutines               | 30.9 ms                                                      | 22.2 ms: 1.39x faster                                                        |
| unpickle_pure_python     | 315 us                                                       | 229 us: 1.37x faster                                                         |
| logging_format           | 9.82 us                                                      | 7.16 us: 1.37x faster                                                        |
| unpack_sequence          | 60.3 ns                                                      | 44.1 ns: 1.37x faster                                                        |
| async_tree_cpu_io_mixed  | 946 ms                                                       | 693 ms: 1.37x faster                                                         |
| pyflate                  | 698 ms                                                       | 513 ms: 1.36x faster                                                         |
| json_dumps               | 14.2 ms                                                      | 10.5 ms: 1.36x faster                                                        |
| pprint_pformat           | 2.15 sec                                                     | 1.60 sec: 1.35x faster                                                       |
| float                    | 109 ms                                                       | 80.7 ms: 1.35x faster                                                        |
| deepcopy_memo            | 50.5 us                                                      | 37.8 us: 1.33x faster                                                        |
| tornado_http             | 157 ms                                                       | 118 ms: 1.33x faster                                                         |
| regex_compile            | 192 ms                                                       | 145 ms: 1.33x faster                                                         |
| pprint_safe_repr         | 1.04 sec                                                     | 786 ms: 1.32x faster                                                         |
| xml_etree_process        | 76.4 ms                                                      | 58.2 ms: 1.31x faster                                                        |
| chameleon                | 9.88 ms                                                      | 7.58 ms: 1.30x faster                                                        |
| sympy_sum                | 194 ms                                                       | 150 ms: 1.29x faster                                                         |
| tomli_loads              | 2.96 sec                                                     | 2.29 sec: 1.29x faster                                                       |
| pycparser                | 1.65 sec                                                     | 1.28 sec: 1.29x faster                                                       |
| fannkuch                 | 488 ms                                                       | 380 ms: 1.28x faster                                                         |
| mypy2                    | 467 ms                                                       | 366 ms: 1.28x faster                                                         |
| bench_mp_pool            | 6.82 ms                                                      | 5.36 ms: 1.27x faster                                                        |
| scimark_sor              | 183 ms                                                       | 145 ms: 1.27x faster                                                         |
| sqlglot_normalize        | 146 ms                                                       | 116 ms: 1.27x faster                                                         |
| nqueens                  | 112 ms                                                       | 89.3 ms: 1.25x faster                                                        |
| sympy_str                | 359 ms                                                       | 288 ms: 1.24x faster                                                         |
| sympy_integrate          | 28.3 ms                                                      | 22.9 ms: 1.23x faster                                                        |
| scimark_sparse_mat_mult  | 5.21 ms                                                      | 4.24 ms: 1.23x faster                                                        |
| deepcopy                 | 459 us                                                       | 374 us: 1.23x faster                                                         |
| sympy_expand             | 599 ms                                                       | 491 ms: 1.22x faster                                                         |
| deepcopy_reduce          | 4.00 us                                                      | 3.29 us: 1.22x faster                                                        |
| docutils                 | 3.42 sec                                                     | 2.82 sec: 1.21x faster                                                       |
| sqlglot_optimize         | 69.9 ms                                                      | 58.1 ms: 1.20x faster                                                        |
| 2to3                     | 349 ms                                                       | 293 ms: 1.19x faster                                                         |
| json_loads               | 30.0 us                                                      | 25.2 us: 1.19x faster                                                        |
| dask                     | 469 ms                                                       | 395 ms: 1.19x faster                                                         |
| dulwich_log              | 80.0 ms                                                      | 67.3 ms: 1.19x faster                                                        |
| bench_thread_pool        | 1.13 ms                                                      | 956 us: 1.19x faster                                                         |
| scimark_fft              | 363 ms                                                       | 307 ms: 1.18x faster                                                         |
| mdp                      | 2.94 sec                                                     | 2.50 sec: 1.18x faster                                                       |
| async_generators         | 418 ms                                                       | 362 ms: 1.16x faster                                                         |
| pathlib                  | 21.2 ms                                                      | 18.5 ms: 1.15x faster                                                        |
| json                     | 5.91 ms                                                      | 5.20 ms: 1.14x faster                                                        |
| sqlite_synth             | 2.97 us                                                      | 2.66 us: 1.11x faster                                                        |
| create_gc_cycles         | 1.79 ms                                                      | 1.61 ms: 1.11x faster                                                        |
| xml_etree_generate       | 93.1 ms                                                      | 85.3 ms: 1.09x faster                                                        |
| meteor_contest           | 138 ms                                                       | 128 ms: 1.08x faster                                                         |
| regex_v8                 | 27.1 ms                                                      | 25.2 ms: 1.07x faster                                                        |
| xml_etree_parse          | 159 ms                                                       | 151 ms: 1.06x faster                                                         |
| regex_dna                | 260 ms                                                       | 251 ms: 1.04x faster                                                         |
| xml_etree_iterparse      | 110 ms                                                       | 107 ms: 1.02x faster                                                         |
| pidigits                 | 270 ms                                                       | 265 ms: 1.02x faster                                                         |
| unpickle                 | 13.9 us                                                      | 14.2 us: 1.02x slower                                                        |
| gc_traversal             | 3.63 ms                                                      | 3.74 ms: 1.03x slower                                                        |
| pickle_list              | 4.23 us                                                      | 4.39 us: 1.04x slower                                                        |
| unpickle_list            | 4.45 us                                                      | 4.64 us: 1.04x slower                                                        |
| pickle_dict              | 30.4 us                                                      | 32.2 us: 1.06x slower                                                        |
| python_startup           | 11.5 ms                                                      | 12.8 ms: 1.11x slower                                                        |
| telco                    | 7.21 ms                                                      | 8.07 ms: 1.12x slower                                                        |
| regex_effbot             | 3.10 ms                                                      | 3.49 ms: 1.13x slower                                                        |
| coverage                 | 65.9 ms                                                      | 82.7 ms: 1.26x slower                                                        |
| python_startup_no_site   | 7.35 ms                                                      | 11.2 ms: 1.53x slower                                                        |
| Geometric mean           | (ref)                                                        | 1.29x faster                                                                 |

Benchmark hidden because not significant (2): asyncio_websockets, pickle
Ignored benchmarks (11) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
Ignored benchmarks (4) of results/bm-20231119-3.13.0a1+-1a969b4/bm-20231119-pythonperf2-x86_64-python-1a969b4f55f92a17bec8-3.13.0a1+-1a969b4.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.26x
- 95% likely to have a speedup of 1.25x
- 99% likely to have a speedup of 1.23x
