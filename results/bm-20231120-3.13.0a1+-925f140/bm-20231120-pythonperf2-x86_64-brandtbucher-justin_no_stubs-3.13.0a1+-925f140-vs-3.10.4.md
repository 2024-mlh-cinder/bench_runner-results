
# Results vs. 3.10.4

- fork: brandtbucher
- ref: justin_no_stubs
- machine: linux-x86_64
- commit hash: 925f140
- commit date: 2023-11-20
- overall geometric mean: 1.26x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.18x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-pythonperf2-x86_64-brandtbucher-justin_no_stubs-3.13.0a1+-925f140 |
|----------------|:------------------------------------------------------------:|:-----------------------------------------------------------------------------:|
| 2to3           | 349 ms                                                       | 301 ms: 1.16x faster                                                          |
| chameleon      | 9.88 ms                                                      | 7.50 ms: 1.32x faster                                                         |
| docutils       | 3.42 sec                                                     | 2.87 sec: 1.19x faster                                                        |
| tornado_http   | 157 ms                                                       | 120 ms: 1.31x faster                                                          |
| Geometric mean | (ref)                                                        | 1.24x faster                                                                  |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-pythonperf2-x86_64-brandtbucher-justin_no_stubs-3.13.0a1+-925f140 |
|-------------------------|:------------------------------------------------------------:|:-----------------------------------------------------------------------------:|
| async_tree_none         | 700 ms                                                       | 436 ms: 1.61x faster                                                          |
| async_tree_memoization  | 827 ms                                                       | 547 ms: 1.51x faster                                                          |
| async_tree_io           | 1.61 sec                                                     | 1.08 sec: 1.49x faster                                                        |
| async_tree_cpu_io_mixed | 946 ms                                                       | 702 ms: 1.35x faster                                                          |
| Geometric mean          | (ref)                                                        | 1.49x faster                                                                  |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-pythonperf2-x86_64-brandtbucher-justin_no_stubs-3.13.0a1+-925f140 |
|----------------|:------------------------------------------------------------:|:-----------------------------------------------------------------------------:|
| nbody          | 134 ms                                                       | 95.7 ms: 1.40x faster                                                         |
| float          | 109 ms                                                       | 79.1 ms: 1.37x faster                                                         |
| pidigits       | 270 ms                                                       | 265 ms: 1.02x faster                                                          |
| Geometric mean | (ref)                                                        | 1.25x faster                                                                  |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-pythonperf2-x86_64-brandtbucher-justin_no_stubs-3.13.0a1+-925f140 |
|----------------|:------------------------------------------------------------:|:-----------------------------------------------------------------------------:|
| regex_compile  | 192 ms                                                       | 149 ms: 1.29x faster                                                          |
| regex_dna      | 260 ms                                                       | 244 ms: 1.07x faster                                                          |
| regex_v8       | 27.1 ms                                                      | 25.4 ms: 1.07x faster                                                         |
| regex_effbot   | 3.10 ms                                                      | 3.49 ms: 1.13x slower                                                         |
| Geometric mean | (ref)                                                        | 1.07x faster                                                                  |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-pythonperf2-x86_64-brandtbucher-justin_no_stubs-3.13.0a1+-925f140 |
|----------------------|:------------------------------------------------------------:|:-----------------------------------------------------------------------------:|
| pickle_pure_python   | 453 us                                                       | 311 us: 1.45x faster                                                          |
| unpickle_pure_python | 315 us                                                       | 222 us: 1.42x faster                                                          |
| json_dumps           | 14.2 ms                                                      | 10.8 ms: 1.32x faster                                                         |
| tomli_loads          | 2.96 sec                                                     | 2.27 sec: 1.30x faster                                                        |
| xml_etree_process    | 76.4 ms                                                      | 58.9 ms: 1.30x faster                                                         |
| json_loads           | 30.0 us                                                      | 25.6 us: 1.18x faster                                                         |
| xml_etree_generate   | 93.1 ms                                                      | 85.6 ms: 1.09x faster                                                         |
| xml_etree_parse      | 159 ms                                                       | 147 ms: 1.09x faster                                                          |
| xml_etree_iterparse  | 110 ms                                                       | 105 ms: 1.04x faster                                                          |
| pickle               | 10.1 us                                                      | 10.0 us: 1.00x faster                                                         |
| pickle_list          | 4.23 us                                                      | 4.40 us: 1.04x slower                                                         |
| unpickle_list        | 4.45 us                                                      | 4.65 us: 1.04x slower                                                         |
| pickle_dict          | 30.4 us                                                      | 32.3 us: 1.06x slower                                                         |
| unpickle             | 13.9 us                                                      | 15.1 us: 1.09x slower                                                         |
| Geometric mean       | (ref)                                                        | 1.13x faster                                                                  |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-pythonperf2-x86_64-brandtbucher-justin_no_stubs-3.13.0a1+-925f140 |
|------------------------|:------------------------------------------------------------:|:-----------------------------------------------------------------------------:|
| python_startup         | 11.5 ms                                                      | 12.9 ms: 1.11x slower                                                         |
| python_startup_no_site | 7.35 ms                                                      | 11.3 ms: 1.54x slower                                                         |
| Geometric mean         | (ref)                                                        | 1.31x slower                                                                  |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-pythonperf2-x86_64-brandtbucher-justin_no_stubs-3.13.0a1+-925f140 |
|-----------|:------------------------------------------------------------:|:-----------------------------------------------------------------------------:|
| mako      | 14.7 ms                                                      | 11.0 ms: 1.34x faster                                                         |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-pythonperf2-x86_64-brandtbucher-justin_no_stubs-3.13.0a1+-925f140 |
|--------------------------|:------------------------------------------------------------:|:-----------------------------------------------------------------------------:|
| typing_runtime_protocols | 533 us                                                       | 130 us: 4.11x faster                                                          |
| asyncio_tcp              | 785 ms                                                       | 368 ms: 2.13x faster                                                          |
| asyncio_tcp_ssl          | 3.13 sec                                                     | 1.57 sec: 1.99x faster                                                        |
| deltablue                | 7.43 ms                                                      | 3.74 ms: 1.98x faster                                                         |
| raytrace                 | 497 ms                                                       | 285 ms: 1.75x faster                                                          |
| logging_silent           | 168 ns                                                       | 99.3 ns: 1.69x faster                                                         |
| richards_super           | 93.0 ms                                                      | 57.4 ms: 1.62x faster                                                         |
| async_tree_none          | 700 ms                                                       | 436 ms: 1.61x faster                                                          |
| sqlglot_parse            | 2.27 ms                                                      | 1.42 ms: 1.60x faster                                                         |
| scimark_lu               | 165 ms                                                       | 103 ms: 1.59x faster                                                          |
| generators               | 57.7 ms                                                      | 36.4 ms: 1.58x faster                                                         |
| async_tree_memoization   | 827 ms                                                       | 547 ms: 1.51x faster                                                          |
| chaos                    | 106 ms                                                       | 70.4 ms: 1.51x faster                                                         |
| richards                 | 76.3 ms                                                      | 50.9 ms: 1.50x faster                                                         |
| go                       | 258 ms                                                       | 172 ms: 1.50x faster                                                          |
| async_tree_io            | 1.61 sec                                                     | 1.08 sec: 1.49x faster                                                        |
| sqlglot_transpile        | 2.73 ms                                                      | 1.84 ms: 1.48x faster                                                         |
| bench_mp_pool            | 6.82 ms                                                      | 4.66 ms: 1.46x faster                                                         |
| pickle_pure_python       | 453 us                                                       | 311 us: 1.45x faster                                                          |
| crypto_pyaes             | 118 ms                                                       | 82.4 ms: 1.43x faster                                                         |
| unpickle_pure_python     | 315 us                                                       | 222 us: 1.42x faster                                                          |
| nbody                    | 134 ms                                                       | 95.7 ms: 1.40x faster                                                         |
| logging_simple           | 9.06 us                                                      | 6.57 us: 1.38x faster                                                         |
| float                    | 109 ms                                                       | 79.1 ms: 1.37x faster                                                         |
| deepcopy_memo            | 50.5 us                                                      | 36.8 us: 1.37x faster                                                         |
| coroutines               | 30.9 ms                                                      | 22.7 ms: 1.36x faster                                                         |
| scimark_monte_carlo      | 109 ms                                                       | 80.9 ms: 1.35x faster                                                         |
| async_tree_cpu_io_mixed  | 946 ms                                                       | 702 ms: 1.35x faster                                                          |
| logging_format           | 9.82 us                                                      | 7.30 us: 1.35x faster                                                         |
| mako                     | 14.7 ms                                                      | 11.0 ms: 1.34x faster                                                         |
| pyflate                  | 698 ms                                                       | 522 ms: 1.34x faster                                                          |
| comprehensions           | 27.0 us                                                      | 20.2 us: 1.34x faster                                                         |
| spectral_norm            | 141 ms                                                       | 106 ms: 1.33x faster                                                          |
| json_dumps               | 14.2 ms                                                      | 10.8 ms: 1.32x faster                                                         |
| chameleon                | 9.88 ms                                                      | 7.50 ms: 1.32x faster                                                         |
| tornado_http             | 157 ms                                                       | 120 ms: 1.31x faster                                                          |
| tomli_loads              | 2.96 sec                                                     | 2.27 sec: 1.30x faster                                                        |
| xml_etree_process        | 76.4 ms                                                      | 58.9 ms: 1.30x faster                                                         |
| regex_compile            | 192 ms                                                       | 149 ms: 1.29x faster                                                          |
| unpack_sequence          | 60.3 ns                                                      | 47.9 ns: 1.26x faster                                                         |
| deepcopy                 | 459 us                                                       | 367 us: 1.25x faster                                                          |
| scimark_sor              | 183 ms                                                       | 147 ms: 1.25x faster                                                          |
| pycparser                | 1.65 sec                                                     | 1.33 sec: 1.24x faster                                                        |
| mypy2                    | 467 ms                                                       | 378 ms: 1.23x faster                                                          |
| pprint_pformat           | 2.15 sec                                                     | 1.76 sec: 1.22x faster                                                        |
| deepcopy_reduce          | 4.00 us                                                      | 3.28 us: 1.22x faster                                                         |
| sympy_sum                | 194 ms                                                       | 159 ms: 1.22x faster                                                          |
| hexiom                   | 9.46 ms                                                      | 7.78 ms: 1.22x faster                                                         |
| sqlglot_normalize        | 146 ms                                                       | 120 ms: 1.21x faster                                                          |
| pprint_safe_repr         | 1.04 sec                                                     | 860 ms: 1.21x faster                                                          |
| sympy_str                | 359 ms                                                       | 300 ms: 1.20x faster                                                          |
| sympy_expand             | 599 ms                                                       | 500 ms: 1.20x faster                                                          |
| docutils                 | 3.42 sec                                                     | 2.87 sec: 1.19x faster                                                        |
| fannkuch                 | 488 ms                                                       | 411 ms: 1.19x faster                                                          |
| dulwich_log              | 80.0 ms                                                      | 67.6 ms: 1.18x faster                                                         |
| json_loads               | 30.0 us                                                      | 25.6 us: 1.18x faster                                                         |
| dask                     | 469 ms                                                       | 400 ms: 1.17x faster                                                          |
| sympy_integrate          | 28.3 ms                                                      | 24.2 ms: 1.17x faster                                                         |
| scimark_sparse_mat_mult  | 5.21 ms                                                      | 4.48 ms: 1.16x faster                                                         |
| 2to3                     | 349 ms                                                       | 301 ms: 1.16x faster                                                          |
| bench_thread_pool        | 1.13 ms                                                      | 980 us: 1.16x faster                                                          |
| sqlglot_optimize         | 69.9 ms                                                      | 61.4 ms: 1.14x faster                                                         |
| create_gc_cycles         | 1.79 ms                                                      | 1.58 ms: 1.13x faster                                                         |
| json                     | 5.91 ms                                                      | 5.24 ms: 1.13x faster                                                         |
| mdp                      | 2.94 sec                                                     | 2.67 sec: 1.10x faster                                                        |
| pathlib                  | 21.2 ms                                                      | 19.3 ms: 1.10x faster                                                         |
| async_generators         | 418 ms                                                       | 383 ms: 1.09x faster                                                          |
| sqlite_synth             | 2.97 us                                                      | 2.73 us: 1.09x faster                                                         |
| xml_etree_generate       | 93.1 ms                                                      | 85.6 ms: 1.09x faster                                                         |
| xml_etree_parse          | 159 ms                                                       | 147 ms: 1.09x faster                                                          |
| nqueens                  | 112 ms                                                       | 104 ms: 1.08x faster                                                          |
| regex_dna                | 260 ms                                                       | 244 ms: 1.07x faster                                                          |
| regex_v8                 | 27.1 ms                                                      | 25.4 ms: 1.07x faster                                                         |
| gc_traversal             | 3.63 ms                                                      | 3.45 ms: 1.05x faster                                                         |
| xml_etree_iterparse      | 110 ms                                                       | 105 ms: 1.04x faster                                                          |
| meteor_contest           | 138 ms                                                       | 132 ms: 1.04x faster                                                          |
| pidigits                 | 270 ms                                                       | 265 ms: 1.02x faster                                                          |
| asyncio_websockets       | 394 ms                                                       | 390 ms: 1.01x faster                                                          |
| pickle                   | 10.1 us                                                      | 10.0 us: 1.00x faster                                                         |
| pickle_list              | 4.23 us                                                      | 4.40 us: 1.04x slower                                                         |
| unpickle_list            | 4.45 us                                                      | 4.65 us: 1.04x slower                                                         |
| pickle_dict              | 30.4 us                                                      | 32.3 us: 1.06x slower                                                         |
| unpickle                 | 13.9 us                                                      | 15.1 us: 1.09x slower                                                         |
| python_startup           | 11.5 ms                                                      | 12.9 ms: 1.11x slower                                                         |
| regex_effbot             | 3.10 ms                                                      | 3.49 ms: 1.13x slower                                                         |
| telco                    | 7.21 ms                                                      | 8.22 ms: 1.14x slower                                                         |
| coverage                 | 65.9 ms                                                      | 80.8 ms: 1.23x slower                                                         |
| python_startup_no_site   | 7.35 ms                                                      | 11.3 ms: 1.54x slower                                                         |
| Geometric mean           | (ref)                                                        | 1.26x faster                                                                  |

Benchmark hidden because not significant (1): scimark_fft
Ignored benchmarks (11) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
Ignored benchmarks (4) of results/bm-20231120-3.13.0a1+-925f140/bm-20231120-pythonperf2-x86_64-brandtbucher-justin_no_stubs-3.13.0a1+-925f140.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.20x
- 95% likely to have a speedup of 1.19x
- 99% likely to have a speedup of 1.18x
