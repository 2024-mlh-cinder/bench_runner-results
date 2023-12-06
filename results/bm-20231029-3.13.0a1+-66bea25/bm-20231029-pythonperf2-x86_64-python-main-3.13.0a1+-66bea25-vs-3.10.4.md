
# Results vs. 3.10.4

- fork: python
- ref: main
- machine: linux-x86_64
- commit hash: 66bea25
- commit date: 2023-10-29
- overall geometric mean: 1.27x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.21x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231029-pythonperf2-x86_64-python-main-3.13.0a1+-66bea25 |
|----------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| 2to3           | 349 ms                                                       | 297 ms: 1.18x faster                                         |
| chameleon      | 9.88 ms                                                      | 7.79 ms: 1.27x faster                                        |
| docutils       | 3.42 sec                                                     | 2.88 sec: 1.19x faster                                       |
| tornado_http   | 157 ms                                                       | 122 ms: 1.28x faster                                         |
| Geometric mean | (ref)                                                        | 1.23x faster                                                 |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231029-pythonperf2-x86_64-python-main-3.13.0a1+-66bea25 |
|-------------------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| async_tree_none         | 700 ms                                                       | 440 ms: 1.59x faster                                         |
| async_tree_memoization  | 827 ms                                                       | 556 ms: 1.49x faster                                         |
| async_tree_io           | 1.61 sec                                                     | 1.10 sec: 1.47x faster                                       |
| async_tree_cpu_io_mixed | 946 ms                                                       | 710 ms: 1.33x faster                                         |
| Geometric mean          | (ref)                                                        | 1.47x faster                                                 |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231029-pythonperf2-x86_64-python-main-3.13.0a1+-66bea25 |
|----------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| nbody          | 134 ms                                                       | 88.1 ms: 1.52x faster                                        |
| float          | 109 ms                                                       | 78.8 ms: 1.38x faster                                        |
| pidigits       | 270 ms                                                       | 264 ms: 1.02x faster                                         |
| Geometric mean | (ref)                                                        | 1.29x faster                                                 |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231029-pythonperf2-x86_64-python-main-3.13.0a1+-66bea25 |
|----------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| regex_compile  | 192 ms                                                       | 149 ms: 1.30x faster                                         |
| regex_v8       | 27.1 ms                                                      | 24.4 ms: 1.11x faster                                        |
| regex_dna      | 260 ms                                                       | 238 ms: 1.09x faster                                         |
| regex_effbot   | 3.10 ms                                                      | 3.53 ms: 1.14x slower                                        |
| Geometric mean | (ref)                                                        | 1.08x faster                                                 |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231029-pythonperf2-x86_64-python-main-3.13.0a1+-66bea25 |
|----------------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| unpickle_pure_python | 315 us                                                       | 221 us: 1.43x faster                                         |
| pickle_pure_python   | 453 us                                                       | 319 us: 1.42x faster                                         |
| json_dumps           | 14.2 ms                                                      | 10.5 ms: 1.35x faster                                        |
| tomli_loads          | 2.96 sec                                                     | 2.26 sec: 1.31x faster                                       |
| xml_etree_process    | 76.4 ms                                                      | 59.3 ms: 1.29x faster                                        |
| json_loads           | 30.0 us                                                      | 24.6 us: 1.22x faster                                        |
| xml_etree_generate   | 93.1 ms                                                      | 84.8 ms: 1.10x faster                                        |
| xml_etree_parse      | 159 ms                                                       | 150 ms: 1.07x faster                                         |
| pickle               | 10.1 us                                                      | 10.3 us: 1.02x slower                                        |
| unpickle_list        | 4.45 us                                                      | 4.54 us: 1.02x slower                                        |
| pickle_dict          | 30.4 us                                                      | 31.4 us: 1.03x slower                                        |
| pickle_list          | 4.23 us                                                      | 4.38 us: 1.03x slower                                        |
| unpickle             | 13.9 us                                                      | 14.8 us: 1.06x slower                                        |
| Geometric mean       | (ref)                                                        | 1.13x faster                                                 |

Benchmark hidden because not significant (1): xml_etree_iterparse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231029-pythonperf2-x86_64-python-main-3.13.0a1+-66bea25 |
|------------------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| python_startup         | 11.5 ms                                                      | 12.9 ms: 1.11x slower                                        |
| python_startup_no_site | 7.35 ms                                                      | 11.3 ms: 1.54x slower                                        |
| Geometric mean         | (ref)                                                        | 1.31x slower                                                 |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231029-pythonperf2-x86_64-python-main-3.13.0a1+-66bea25 |
|-----------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| mako      | 14.7 ms                                                      | 10.3 ms: 1.43x faster                                        |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231029-pythonperf2-x86_64-python-main-3.13.0a1+-66bea25 |
|--------------------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| typing_runtime_protocols | 533 us                                                       | 153 us: 3.48x faster                                         |
| asyncio_tcp              | 785 ms                                                       | 369 ms: 2.13x faster                                         |
| deltablue                | 7.43 ms                                                      | 3.71 ms: 2.00x faster                                        |
| asyncio_tcp_ssl          | 3.13 sec                                                     | 1.58 sec: 1.98x faster                                       |
| raytrace                 | 497 ms                                                       | 274 ms: 1.81x faster                                         |
| chaos                    | 106 ms                                                       | 62.3 ms: 1.70x faster                                        |
| logging_silent           | 168 ns                                                       | 99.4 ns: 1.69x faster                                        |
| crypto_pyaes             | 118 ms                                                       | 71.8 ms: 1.64x faster                                        |
| scimark_lu               | 165 ms                                                       | 101 ms: 1.63x faster                                         |
| comprehensions           | 27.0 us                                                      | 16.8 us: 1.61x faster                                        |
| generators               | 57.7 ms                                                      | 36.2 ms: 1.59x faster                                        |
| async_tree_none          | 700 ms                                                       | 440 ms: 1.59x faster                                         |
| sqlglot_parse            | 2.27 ms                                                      | 1.43 ms: 1.58x faster                                        |
| scimark_monte_carlo      | 109 ms                                                       | 69.4 ms: 1.58x faster                                        |
| nbody                    | 134 ms                                                       | 88.1 ms: 1.52x faster                                        |
| richards_super           | 93.0 ms                                                      | 61.1 ms: 1.52x faster                                        |
| spectral_norm            | 141 ms                                                       | 93.8 ms: 1.51x faster                                        |
| go                       | 258 ms                                                       | 171 ms: 1.51x faster                                         |
| bench_mp_pool            | 6.82 ms                                                      | 4.56 ms: 1.50x faster                                        |
| async_tree_memoization   | 827 ms                                                       | 556 ms: 1.49x faster                                         |
| sqlglot_transpile        | 2.73 ms                                                      | 1.85 ms: 1.48x faster                                        |
| async_tree_io            | 1.61 sec                                                     | 1.10 sec: 1.47x faster                                       |
| hexiom                   | 9.46 ms                                                      | 6.54 ms: 1.45x faster                                        |
| mako                     | 14.7 ms                                                      | 10.3 ms: 1.43x faster                                        |
| unpickle_pure_python     | 315 us                                                       | 221 us: 1.43x faster                                         |
| pickle_pure_python       | 453 us                                                       | 319 us: 1.42x faster                                         |
| float                    | 109 ms                                                       | 78.8 ms: 1.38x faster                                        |
| richards                 | 76.3 ms                                                      | 55.9 ms: 1.37x faster                                        |
| pyflate                  | 698 ms                                                       | 516 ms: 1.35x faster                                         |
| json_dumps               | 14.2 ms                                                      | 10.5 ms: 1.35x faster                                        |
| coroutines               | 30.9 ms                                                      | 23.1 ms: 1.34x faster                                        |
| async_tree_cpu_io_mixed  | 946 ms                                                       | 710 ms: 1.33x faster                                         |
| deepcopy_memo            | 50.5 us                                                      | 38.1 us: 1.33x faster                                        |
| tomli_loads              | 2.96 sec                                                     | 2.26 sec: 1.31x faster                                       |
| logging_format           | 9.82 us                                                      | 7.53 us: 1.30x faster                                        |
| unpack_sequence          | 60.3 ns                                                      | 46.3 ns: 1.30x faster                                        |
| logging_simple           | 9.06 us                                                      | 6.96 us: 1.30x faster                                        |
| regex_compile            | 192 ms                                                       | 149 ms: 1.30x faster                                         |
| xml_etree_process        | 76.4 ms                                                      | 59.3 ms: 1.29x faster                                        |
| tornado_http             | 157 ms                                                       | 122 ms: 1.28x faster                                         |
| pycparser                | 1.65 sec                                                     | 1.30 sec: 1.27x faster                                       |
| sympy_sum                | 194 ms                                                       | 152 ms: 1.27x faster                                         |
| chameleon                | 9.88 ms                                                      | 7.79 ms: 1.27x faster                                        |
| fannkuch                 | 488 ms                                                       | 385 ms: 1.27x faster                                         |
| pprint_pformat           | 2.15 sec                                                     | 1.70 sec: 1.27x faster                                       |
| mypy2                    | 467 ms                                                       | 371 ms: 1.26x faster                                         |
| nqueens                  | 112 ms                                                       | 89.1 ms: 1.26x faster                                        |
| sqlglot_normalize        | 146 ms                                                       | 117 ms: 1.25x faster                                         |
| pprint_safe_repr         | 1.04 sec                                                     | 836 ms: 1.24x faster                                         |
| scimark_sparse_mat_mult  | 5.21 ms                                                      | 4.21 ms: 1.24x faster                                        |
| scimark_sor              | 183 ms                                                       | 150 ms: 1.22x faster                                         |
| sympy_str                | 359 ms                                                       | 293 ms: 1.22x faster                                         |
| json_loads               | 30.0 us                                                      | 24.6 us: 1.22x faster                                        |
| sympy_expand             | 599 ms                                                       | 496 ms: 1.21x faster                                         |
| sympy_integrate          | 28.3 ms                                                      | 23.6 ms: 1.20x faster                                        |
| deepcopy                 | 459 us                                                       | 382 us: 1.20x faster                                         |
| docutils                 | 3.42 sec                                                     | 2.88 sec: 1.19x faster                                       |
| deepcopy_reduce          | 4.00 us                                                      | 3.37 us: 1.19x faster                                        |
| sqlglot_optimize         | 69.9 ms                                                      | 59.3 ms: 1.18x faster                                        |
| 2to3                     | 349 ms                                                       | 297 ms: 1.18x faster                                         |
| scimark_fft              | 363 ms                                                       | 310 ms: 1.17x faster                                         |
| bench_thread_pool        | 1.13 ms                                                      | 973 us: 1.17x faster                                         |
| dulwich_log              | 80.0 ms                                                      | 69.0 ms: 1.16x faster                                        |
| mdp                      | 2.94 sec                                                     | 2.54 sec: 1.16x faster                                       |
| json                     | 5.91 ms                                                      | 5.16 ms: 1.15x faster                                        |
| regex_v8                 | 27.1 ms                                                      | 24.4 ms: 1.11x faster                                        |
| xml_etree_generate       | 93.1 ms                                                      | 84.8 ms: 1.10x faster                                        |
| sqlite_synth             | 2.97 us                                                      | 2.71 us: 1.10x faster                                        |
| regex_dna                | 260 ms                                                       | 238 ms: 1.09x faster                                         |
| create_gc_cycles         | 1.79 ms                                                      | 1.64 ms: 1.09x faster                                        |
| pathlib                  | 21.2 ms                                                      | 19.7 ms: 1.08x faster                                        |
| xml_etree_parse          | 159 ms                                                       | 150 ms: 1.07x faster                                         |
| async_generators         | 418 ms                                                       | 394 ms: 1.06x faster                                         |
| meteor_contest           | 138 ms                                                       | 131 ms: 1.05x faster                                         |
| pidigits                 | 270 ms                                                       | 264 ms: 1.02x faster                                         |
| asyncio_websockets       | 394 ms                                                       | 388 ms: 1.02x faster                                         |
| pickle                   | 10.1 us                                                      | 10.3 us: 1.02x slower                                        |
| unpickle_list            | 4.45 us                                                      | 4.54 us: 1.02x slower                                        |
| pickle_dict              | 30.4 us                                                      | 31.4 us: 1.03x slower                                        |
| pickle_list              | 4.23 us                                                      | 4.38 us: 1.03x slower                                        |
| unpickle                 | 13.9 us                                                      | 14.8 us: 1.06x slower                                        |
| gc_traversal             | 3.63 ms                                                      | 3.92 ms: 1.08x slower                                        |
| python_startup           | 11.5 ms                                                      | 12.9 ms: 1.11x slower                                        |
| telco                    | 7.21 ms                                                      | 8.18 ms: 1.13x slower                                        |
| regex_effbot             | 3.10 ms                                                      | 3.53 ms: 1.14x slower                                        |
| coverage                 | 65.9 ms                                                      | 79.9 ms: 1.21x slower                                        |
| python_startup_no_site   | 7.35 ms                                                      | 11.3 ms: 1.54x slower                                        |
| Geometric mean           | (ref)                                                        | 1.27x faster                                                 |

Benchmark hidden because not significant (1): xml_etree_iterparse
Ignored benchmarks (12) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, dask, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
Ignored benchmarks (4) of results/bm-20231029-3.13.0a1+-66bea25/bm-20231029-pythonperf2-x86_64-python-main-3.13.0a1+-66bea25.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.24x
- 95% likely to have a speedup of 1.23x
- 99% likely to have a speedup of 1.21x
