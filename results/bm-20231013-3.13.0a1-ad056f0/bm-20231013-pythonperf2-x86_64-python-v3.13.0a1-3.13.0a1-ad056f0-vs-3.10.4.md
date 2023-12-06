
# Results vs. 3.10.4

- fork: python
- ref: v3.13.0a1
- machine: linux-x86_64
- commit hash: ad056f0
- commit date: 2023-10-13
- overall geometric mean: 1.27x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.20x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231013-pythonperf2-x86_64-python-v3.13.0a1-3.13.0a1-ad056f0 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| 2to3           | 349 ms                                                       | 297 ms: 1.17x faster                                             |
| chameleon      | 9.88 ms                                                      | 7.78 ms: 1.27x faster                                            |
| docutils       | 3.42 sec                                                     | 2.88 sec: 1.19x faster                                           |
| tornado_http   | 157 ms                                                       | 121 ms: 1.29x faster                                             |
| Geometric mean | (ref)                                                        | 1.23x faster                                                     |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231013-pythonperf2-x86_64-python-v3.13.0a1-3.13.0a1-ad056f0 |
|-------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| async_tree_none         | 700 ms                                                       | 439 ms: 1.59x faster                                             |
| async_tree_memoization  | 827 ms                                                       | 557 ms: 1.48x faster                                             |
| async_tree_io           | 1.61 sec                                                     | 1.09 sec: 1.47x faster                                           |
| async_tree_cpu_io_mixed | 946 ms                                                       | 713 ms: 1.33x faster                                             |
| Geometric mean          | (ref)                                                        | 1.47x faster                                                     |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231013-pythonperf2-x86_64-python-v3.13.0a1-3.13.0a1-ad056f0 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| nbody          | 134 ms                                                       | 87.7 ms: 1.53x faster                                            |
| float          | 109 ms                                                       | 81.5 ms: 1.33x faster                                            |
| pidigits       | 270 ms                                                       | 264 ms: 1.02x faster                                             |
| Geometric mean | (ref)                                                        | 1.28x faster                                                     |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231013-pythonperf2-x86_64-python-v3.13.0a1-3.13.0a1-ad056f0 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| regex_compile  | 192 ms                                                       | 150 ms: 1.28x faster                                             |
| regex_dna      | 260 ms                                                       | 241 ms: 1.08x faster                                             |
| regex_v8       | 27.1 ms                                                      | 26.2 ms: 1.03x faster                                            |
| regex_effbot   | 3.10 ms                                                      | 3.55 ms: 1.15x slower                                            |
| Geometric mean | (ref)                                                        | 1.06x faster                                                     |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231013-pythonperf2-x86_64-python-v3.13.0a1-3.13.0a1-ad056f0 |
|----------------------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| pickle_pure_python   | 453 us                                                       | 314 us: 1.44x faster                                             |
| unpickle_pure_python | 315 us                                                       | 220 us: 1.43x faster                                             |
| json_dumps           | 14.2 ms                                                      | 10.6 ms: 1.34x faster                                            |
| tomli_loads          | 2.96 sec                                                     | 2.24 sec: 1.32x faster                                           |
| xml_etree_process    | 76.4 ms                                                      | 59.9 ms: 1.28x faster                                            |
| json_loads           | 30.0 us                                                      | 24.3 us: 1.24x faster                                            |
| xml_etree_generate   | 93.1 ms                                                      | 87.3 ms: 1.07x faster                                            |
| xml_etree_parse      | 159 ms                                                       | 152 ms: 1.05x faster                                             |
| pickle               | 10.1 us                                                      | 10.1 us: 1.00x slower                                            |
| unpickle             | 13.9 us                                                      | 14.3 us: 1.03x slower                                            |
| unpickle_list        | 4.45 us                                                      | 4.61 us: 1.04x slower                                            |
| pickle_list          | 4.23 us                                                      | 4.45 us: 1.05x slower                                            |
| pickle_dict          | 30.4 us                                                      | 32.9 us: 1.08x slower                                            |
| Geometric mean       | (ref)                                                        | 1.13x faster                                                     |

Benchmark hidden because not significant (1): xml_etree_iterparse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231013-pythonperf2-x86_64-python-v3.13.0a1-3.13.0a1-ad056f0 |
|------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| python_startup         | 11.5 ms                                                      | 12.6 ms: 1.09x slower                                            |
| python_startup_no_site | 7.35 ms                                                      | 8.70 ms: 1.18x slower                                            |
| Geometric mean         | (ref)                                                        | 1.14x slower                                                     |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231013-pythonperf2-x86_64-python-v3.13.0a1-3.13.0a1-ad056f0 |
|-----------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| mako      | 14.7 ms                                                      | 10.4 ms: 1.42x faster                                            |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231013-pythonperf2-x86_64-python-v3.13.0a1-3.13.0a1-ad056f0 |
|--------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| typing_runtime_protocols | 533 us                                                       | 155 us: 3.45x faster                                             |
| asyncio_tcp              | 785 ms                                                       | 367 ms: 2.14x faster                                             |
| deltablue                | 7.43 ms                                                      | 3.66 ms: 2.03x faster                                            |
| asyncio_tcp_ssl          | 3.13 sec                                                     | 1.58 sec: 1.98x faster                                           |
| raytrace                 | 497 ms                                                       | 276 ms: 1.80x faster                                             |
| logging_silent           | 168 ns                                                       | 98.3 ns: 1.71x faster                                            |
| chaos                    | 106 ms                                                       | 62.7 ms: 1.69x faster                                            |
| generators               | 57.7 ms                                                      | 35.4 ms: 1.63x faster                                            |
| crypto_pyaes             | 118 ms                                                       | 73.4 ms: 1.61x faster                                            |
| scimark_lu               | 165 ms                                                       | 103 ms: 1.60x faster                                             |
| sqlglot_parse            | 2.27 ms                                                      | 1.42 ms: 1.59x faster                                            |
| async_tree_none          | 700 ms                                                       | 439 ms: 1.59x faster                                             |
| scimark_monte_carlo      | 109 ms                                                       | 71.0 ms: 1.54x faster                                            |
| nbody                    | 134 ms                                                       | 87.7 ms: 1.53x faster                                            |
| spectral_norm            | 141 ms                                                       | 92.3 ms: 1.53x faster                                            |
| richards_super           | 93.0 ms                                                      | 61.7 ms: 1.51x faster                                            |
| go                       | 258 ms                                                       | 172 ms: 1.50x faster                                             |
| sqlglot_transpile        | 2.73 ms                                                      | 1.83 ms: 1.49x faster                                            |
| async_tree_memoization   | 827 ms                                                       | 557 ms: 1.48x faster                                             |
| async_tree_io            | 1.61 sec                                                     | 1.09 sec: 1.47x faster                                           |
| hexiom                   | 9.46 ms                                                      | 6.54 ms: 1.45x faster                                            |
| bench_mp_pool            | 6.82 ms                                                      | 4.72 ms: 1.44x faster                                            |
| pickle_pure_python       | 453 us                                                       | 314 us: 1.44x faster                                             |
| unpickle_pure_python     | 315 us                                                       | 220 us: 1.43x faster                                             |
| mako                     | 14.7 ms                                                      | 10.4 ms: 1.42x faster                                            |
| richards                 | 76.3 ms                                                      | 55.4 ms: 1.38x faster                                            |
| coroutines               | 30.9 ms                                                      | 22.6 ms: 1.37x faster                                            |
| pyflate                  | 698 ms                                                       | 513 ms: 1.36x faster                                             |
| json_dumps               | 14.2 ms                                                      | 10.6 ms: 1.34x faster                                            |
| logging_simple           | 9.06 us                                                      | 6.79 us: 1.34x faster                                            |
| float                    | 109 ms                                                       | 81.5 ms: 1.33x faster                                            |
| async_tree_cpu_io_mixed  | 946 ms                                                       | 713 ms: 1.33x faster                                             |
| tomli_loads              | 2.96 sec                                                     | 2.24 sec: 1.32x faster                                           |
| logging_format           | 9.82 us                                                      | 7.44 us: 1.32x faster                                            |
| deepcopy_memo            | 50.5 us                                                      | 38.6 us: 1.31x faster                                            |
| tornado_http             | 157 ms                                                       | 121 ms: 1.29x faster                                             |
| regex_compile            | 192 ms                                                       | 150 ms: 1.28x faster                                             |
| pprint_pformat           | 2.15 sec                                                     | 1.68 sec: 1.28x faster                                           |
| xml_etree_process        | 76.4 ms                                                      | 59.9 ms: 1.28x faster                                            |
| chameleon                | 9.88 ms                                                      | 7.78 ms: 1.27x faster                                            |
| comprehensions           | 27.0 us                                                      | 21.5 us: 1.26x faster                                            |
| sqlglot_normalize        | 146 ms                                                       | 117 ms: 1.26x faster                                             |
| pprint_safe_repr         | 1.04 sec                                                     | 829 ms: 1.25x faster                                             |
| nqueens                  | 112 ms                                                       | 89.2 ms: 1.25x faster                                            |
| mypy2                    | 467 ms                                                       | 373 ms: 1.25x faster                                             |
| pycparser                | 1.65 sec                                                     | 1.33 sec: 1.24x faster                                           |
| json_loads               | 30.0 us                                                      | 24.3 us: 1.24x faster                                            |
| fannkuch                 | 488 ms                                                       | 396 ms: 1.23x faster                                             |
| scimark_sor              | 183 ms                                                       | 149 ms: 1.23x faster                                             |
| deepcopy                 | 459 us                                                       | 379 us: 1.21x faster                                             |
| sympy_expand             | 599 ms                                                       | 494 ms: 1.21x faster                                             |
| sympy_sum                | 194 ms                                                       | 161 ms: 1.20x faster                                             |
| scimark_sparse_mat_mult  | 5.21 ms                                                      | 4.34 ms: 1.20x faster                                            |
| sqlglot_optimize         | 69.9 ms                                                      | 58.8 ms: 1.19x faster                                            |
| docutils                 | 3.42 sec                                                     | 2.88 sec: 1.19x faster                                           |
| unpack_sequence          | 60.3 ns                                                      | 50.9 ns: 1.18x faster                                            |
| bench_thread_pool        | 1.13 ms                                                      | 961 us: 1.18x faster                                             |
| deepcopy_reduce          | 4.00 us                                                      | 3.39 us: 1.18x faster                                            |
| 2to3                     | 349 ms                                                       | 297 ms: 1.17x faster                                             |
| sympy_integrate          | 28.3 ms                                                      | 24.2 ms: 1.17x faster                                            |
| sympy_str                | 359 ms                                                       | 307 ms: 1.17x faster                                             |
| mdp                      | 2.94 sec                                                     | 2.52 sec: 1.17x faster                                           |
| dulwich_log              | 80.0 ms                                                      | 69.2 ms: 1.16x faster                                            |
| json                     | 5.91 ms                                                      | 5.12 ms: 1.16x faster                                            |
| scimark_fft              | 363 ms                                                       | 315 ms: 1.15x faster                                             |
| create_gc_cycles         | 1.79 ms                                                      | 1.58 ms: 1.13x faster                                            |
| sqlite_synth             | 2.97 us                                                      | 2.70 us: 1.10x faster                                            |
| pathlib                  | 21.2 ms                                                      | 19.3 ms: 1.09x faster                                            |
| regex_dna                | 260 ms                                                       | 241 ms: 1.08x faster                                             |
| xml_etree_generate       | 93.1 ms                                                      | 87.3 ms: 1.07x faster                                            |
| meteor_contest           | 138 ms                                                       | 131 ms: 1.05x faster                                             |
| async_generators         | 418 ms                                                       | 399 ms: 1.05x faster                                             |
| xml_etree_parse          | 159 ms                                                       | 152 ms: 1.05x faster                                             |
| regex_v8                 | 27.1 ms                                                      | 26.2 ms: 1.03x faster                                            |
| pidigits                 | 270 ms                                                       | 264 ms: 1.02x faster                                             |
| asyncio_websockets       | 394 ms                                                       | 389 ms: 1.01x faster                                             |
| pickle                   | 10.1 us                                                      | 10.1 us: 1.00x slower                                            |
| unpickle                 | 13.9 us                                                      | 14.3 us: 1.03x slower                                            |
| unpickle_list            | 4.45 us                                                      | 4.61 us: 1.04x slower                                            |
| pickle_list              | 4.23 us                                                      | 4.45 us: 1.05x slower                                            |
| pickle_dict              | 30.4 us                                                      | 32.9 us: 1.08x slower                                            |
| gc_traversal             | 3.63 ms                                                      | 3.95 ms: 1.09x slower                                            |
| python_startup           | 11.5 ms                                                      | 12.6 ms: 1.09x slower                                            |
| telco                    | 7.21 ms                                                      | 8.25 ms: 1.14x slower                                            |
| regex_effbot             | 3.10 ms                                                      | 3.55 ms: 1.15x slower                                            |
| python_startup_no_site   | 7.35 ms                                                      | 8.70 ms: 1.18x slower                                            |
| coverage                 | 65.9 ms                                                      | 83.6 ms: 1.27x slower                                            |
| Geometric mean           | (ref)                                                        | 1.27x faster                                                     |

Benchmark hidden because not significant (1): xml_etree_iterparse
Ignored benchmarks (12) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, dask, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
Ignored benchmarks (4) of results/bm-20231013-3.13.0a1-ad056f0/bm-20231013-pythonperf2-x86_64-python-v3.13.0a1-3.13.0a1-ad056f0.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.22x
- 95% likely to have a speedup of 1.21x
- 99% likely to have a speedup of 1.20x
