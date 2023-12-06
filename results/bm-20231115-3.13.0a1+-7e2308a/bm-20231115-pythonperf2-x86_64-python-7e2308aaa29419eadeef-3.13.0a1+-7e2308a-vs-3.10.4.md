
# Results vs. 3.10.4

- fork: python
- ref: 7e2308aaa29419eadeef
- machine: linux-x86_64
- commit hash: 7e2308a
- commit date: 2023-11-15
- overall geometric mean: 1.29x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.22x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231115-pythonperf2-x86_64-python-7e2308aaa29419eadeef-3.13.0a1+-7e2308a |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| 2to3           | 349 ms                                                       | 293 ms: 1.19x faster                                                         |
| chameleon      | 9.88 ms                                                      | 7.42 ms: 1.33x faster                                                        |
| docutils       | 3.42 sec                                                     | 2.83 sec: 1.21x faster                                                       |
| tornado_http   | 157 ms                                                       | 120 ms: 1.30x faster                                                         |
| Geometric mean | (ref)                                                        | 1.26x faster                                                                 |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231115-pythonperf2-x86_64-python-7e2308aaa29419eadeef-3.13.0a1+-7e2308a |
|-------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| async_tree_none         | 700 ms                                                       | 429 ms: 1.63x faster                                                         |
| async_tree_memoization  | 827 ms                                                       | 544 ms: 1.52x faster                                                         |
| async_tree_io           | 1.61 sec                                                     | 1.08 sec: 1.49x faster                                                       |
| async_tree_cpu_io_mixed | 946 ms                                                       | 693 ms: 1.36x faster                                                         |
| Geometric mean          | (ref)                                                        | 1.50x faster                                                                 |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231115-pythonperf2-x86_64-python-7e2308aaa29419eadeef-3.13.0a1+-7e2308a |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| nbody          | 134 ms                                                       | 87.2 ms: 1.54x faster                                                        |
| float          | 109 ms                                                       | 79.7 ms: 1.36x faster                                                        |
| pidigits       | 270 ms                                                       | 264 ms: 1.02x faster                                                         |
| Geometric mean | (ref)                                                        | 1.29x faster                                                                 |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231115-pythonperf2-x86_64-python-7e2308aaa29419eadeef-3.13.0a1+-7e2308a |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| regex_compile  | 192 ms                                                       | 143 ms: 1.35x faster                                                         |
| regex_v8       | 27.1 ms                                                      | 25.6 ms: 1.06x faster                                                        |
| regex_dna      | 260 ms                                                       | 255 ms: 1.02x faster                                                         |
| regex_effbot   | 3.10 ms                                                      | 3.59 ms: 1.16x slower                                                        |
| Geometric mean | (ref)                                                        | 1.06x faster                                                                 |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231115-pythonperf2-x86_64-python-7e2308aaa29419eadeef-3.13.0a1+-7e2308a |
|----------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| unpickle_pure_python | 315 us                                                       | 212 us: 1.49x faster                                                         |
| pickle_pure_python   | 453 us                                                       | 312 us: 1.45x faster                                                         |
| tomli_loads          | 2.96 sec                                                     | 2.21 sec: 1.34x faster                                                       |
| xml_etree_process    | 76.4 ms                                                      | 58.5 ms: 1.31x faster                                                        |
| json_dumps           | 14.2 ms                                                      | 11.0 ms: 1.30x faster                                                        |
| json_loads           | 30.0 us                                                      | 25.5 us: 1.18x faster                                                        |
| xml_etree_generate   | 93.1 ms                                                      | 86.2 ms: 1.08x faster                                                        |
| xml_etree_parse      | 159 ms                                                       | 153 ms: 1.04x faster                                                         |
| xml_etree_iterparse  | 110 ms                                                       | 107 ms: 1.03x faster                                                         |
| pickle               | 10.1 us                                                      | 10.2 us: 1.01x slower                                                        |
| unpickle             | 13.9 us                                                      | 14.3 us: 1.03x slower                                                        |
| unpickle_list        | 4.45 us                                                      | 4.61 us: 1.04x slower                                                        |
| pickle_dict          | 30.4 us                                                      | 32.5 us: 1.07x slower                                                        |
| pickle_list          | 4.23 us                                                      | 4.68 us: 1.11x slower                                                        |
| Geometric mean       | (ref)                                                        | 1.13x faster                                                                 |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231115-pythonperf2-x86_64-python-7e2308aaa29419eadeef-3.13.0a1+-7e2308a |
|------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| python_startup         | 11.5 ms                                                      | 12.9 ms: 1.12x slower                                                        |
| python_startup_no_site | 7.35 ms                                                      | 11.3 ms: 1.54x slower                                                        |
| Geometric mean         | (ref)                                                        | 1.31x slower                                                                 |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231115-pythonperf2-x86_64-python-7e2308aaa29419eadeef-3.13.0a1+-7e2308a |
|-----------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| mako      | 14.7 ms                                                      | 10.1 ms: 1.46x faster                                                        |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231115-pythonperf2-x86_64-python-7e2308aaa29419eadeef-3.13.0a1+-7e2308a |
|--------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| typing_runtime_protocols | 533 us                                                       | 124 us: 4.30x faster                                                         |
| asyncio_tcp              | 785 ms                                                       | 369 ms: 2.13x faster                                                         |
| deltablue                | 7.43 ms                                                      | 3.59 ms: 2.07x faster                                                        |
| asyncio_tcp_ssl          | 3.13 sec                                                     | 1.58 sec: 1.98x faster                                                       |
| raytrace                 | 497 ms                                                       | 273 ms: 1.82x faster                                                         |
| logging_silent           | 168 ns                                                       | 96.5 ns: 1.74x faster                                                        |
| chaos                    | 106 ms                                                       | 61.3 ms: 1.73x faster                                                        |
| crypto_pyaes             | 118 ms                                                       | 70.6 ms: 1.67x faster                                                        |
| scimark_lu               | 165 ms                                                       | 100 ms: 1.65x faster                                                         |
| generators               | 57.7 ms                                                      | 35.1 ms: 1.64x faster                                                        |
| scimark_monte_carlo      | 109 ms                                                       | 66.8 ms: 1.64x faster                                                        |
| async_tree_none          | 700 ms                                                       | 429 ms: 1.63x faster                                                         |
| sqlglot_parse            | 2.27 ms                                                      | 1.39 ms: 1.63x faster                                                        |
| comprehensions           | 27.0 us                                                      | 16.7 us: 1.62x faster                                                        |
| spectral_norm            | 141 ms                                                       | 90.6 ms: 1.56x faster                                                        |
| richards_super           | 93.0 ms                                                      | 59.8 ms: 1.55x faster                                                        |
| go                       | 258 ms                                                       | 167 ms: 1.55x faster                                                         |
| nbody                    | 134 ms                                                       | 87.2 ms: 1.54x faster                                                        |
| async_tree_memoization   | 827 ms                                                       | 544 ms: 1.52x faster                                                         |
| sqlglot_transpile        | 2.73 ms                                                      | 1.80 ms: 1.52x faster                                                        |
| async_tree_io            | 1.61 sec                                                     | 1.08 sec: 1.49x faster                                                       |
| unpickle_pure_python     | 315 us                                                       | 212 us: 1.49x faster                                                         |
| hexiom                   | 9.46 ms                                                      | 6.41 ms: 1.48x faster                                                        |
| mako                     | 14.7 ms                                                      | 10.1 ms: 1.46x faster                                                        |
| pickle_pure_python       | 453 us                                                       | 312 us: 1.45x faster                                                         |
| logging_simple           | 9.06 us                                                      | 6.35 us: 1.43x faster                                                        |
| logging_format           | 9.82 us                                                      | 6.99 us: 1.41x faster                                                        |
| richards                 | 76.3 ms                                                      | 54.6 ms: 1.40x faster                                                        |
| coroutines               | 30.9 ms                                                      | 22.2 ms: 1.39x faster                                                        |
| deepcopy_memo            | 50.5 us                                                      | 36.8 us: 1.37x faster                                                        |
| async_tree_cpu_io_mixed  | 946 ms                                                       | 693 ms: 1.36x faster                                                         |
| float                    | 109 ms                                                       | 79.7 ms: 1.36x faster                                                        |
| regex_compile            | 192 ms                                                       | 143 ms: 1.35x faster                                                         |
| tomli_loads              | 2.96 sec                                                     | 2.21 sec: 1.34x faster                                                       |
| chameleon                | 9.88 ms                                                      | 7.42 ms: 1.33x faster                                                        |
| pyflate                  | 698 ms                                                       | 532 ms: 1.31x faster                                                         |
| xml_etree_process        | 76.4 ms                                                      | 58.5 ms: 1.31x faster                                                        |
| tornado_http             | 157 ms                                                       | 120 ms: 1.30x faster                                                         |
| pprint_pformat           | 2.15 sec                                                     | 1.66 sec: 1.30x faster                                                       |
| json_dumps               | 14.2 ms                                                      | 11.0 ms: 1.30x faster                                                        |
| sympy_sum                | 194 ms                                                       | 150 ms: 1.29x faster                                                         |
| pprint_safe_repr         | 1.04 sec                                                     | 810 ms: 1.28x faster                                                         |
| sqlglot_normalize        | 146 ms                                                       | 114 ms: 1.28x faster                                                         |
| deepcopy                 | 459 us                                                       | 359 us: 1.28x faster                                                         |
| nqueens                  | 112 ms                                                       | 87.6 ms: 1.28x faster                                                        |
| pycparser                | 1.65 sec                                                     | 1.29 sec: 1.28x faster                                                       |
| mypy2                    | 467 ms                                                       | 367 ms: 1.27x faster                                                         |
| fannkuch                 | 488 ms                                                       | 385 ms: 1.27x faster                                                         |
| sympy_str                | 359 ms                                                       | 289 ms: 1.24x faster                                                         |
| scimark_sor              | 183 ms                                                       | 148 ms: 1.24x faster                                                         |
| sympy_integrate          | 28.3 ms                                                      | 22.9 ms: 1.24x faster                                                        |
| scimark_sparse_mat_mult  | 5.21 ms                                                      | 4.22 ms: 1.23x faster                                                        |
| unpack_sequence          | 60.3 ns                                                      | 49.0 ns: 1.23x faster                                                        |
| deepcopy_reduce          | 4.00 us                                                      | 3.27 us: 1.22x faster                                                        |
| sympy_expand             | 599 ms                                                       | 491 ms: 1.22x faster                                                         |
| docutils                 | 3.42 sec                                                     | 2.83 sec: 1.21x faster                                                       |
| sqlglot_optimize         | 69.9 ms                                                      | 57.8 ms: 1.21x faster                                                        |
| 2to3                     | 349 ms                                                       | 293 ms: 1.19x faster                                                         |
| scimark_fft              | 363 ms                                                       | 305 ms: 1.19x faster                                                         |
| dask                     | 469 ms                                                       | 397 ms: 1.18x faster                                                         |
| json_loads               | 30.0 us                                                      | 25.5 us: 1.18x faster                                                        |
| dulwich_log              | 80.0 ms                                                      | 68.2 ms: 1.17x faster                                                        |
| bench_thread_pool        | 1.13 ms                                                      | 976 us: 1.16x faster                                                         |
| bench_mp_pool            | 6.82 ms                                                      | 5.89 ms: 1.16x faster                                                        |
| mdp                      | 2.94 sec                                                     | 2.54 sec: 1.16x faster                                                       |
| json                     | 5.91 ms                                                      | 5.18 ms: 1.14x faster                                                        |
| pathlib                  | 21.2 ms                                                      | 18.5 ms: 1.14x faster                                                        |
| async_generators         | 418 ms                                                       | 369 ms: 1.13x faster                                                         |
| create_gc_cycles         | 1.79 ms                                                      | 1.59 ms: 1.12x faster                                                        |
| sqlite_synth             | 2.97 us                                                      | 2.70 us: 1.10x faster                                                        |
| meteor_contest           | 138 ms                                                       | 127 ms: 1.08x faster                                                         |
| xml_etree_generate       | 93.1 ms                                                      | 86.2 ms: 1.08x faster                                                        |
| regex_v8                 | 27.1 ms                                                      | 25.6 ms: 1.06x faster                                                        |
| xml_etree_parse          | 159 ms                                                       | 153 ms: 1.04x faster                                                         |
| xml_etree_iterparse      | 110 ms                                                       | 107 ms: 1.03x faster                                                         |
| pidigits                 | 270 ms                                                       | 264 ms: 1.02x faster                                                         |
| asyncio_websockets       | 394 ms                                                       | 386 ms: 1.02x faster                                                         |
| regex_dna                | 260 ms                                                       | 255 ms: 1.02x faster                                                         |
| pickle                   | 10.1 us                                                      | 10.2 us: 1.01x slower                                                        |
| unpickle                 | 13.9 us                                                      | 14.3 us: 1.03x slower                                                        |
| unpickle_list            | 4.45 us                                                      | 4.61 us: 1.04x slower                                                        |
| pickle_dict              | 30.4 us                                                      | 32.5 us: 1.07x slower                                                        |
| gc_traversal             | 3.63 ms                                                      | 3.99 ms: 1.10x slower                                                        |
| pickle_list              | 4.23 us                                                      | 4.68 us: 1.11x slower                                                        |
| python_startup           | 11.5 ms                                                      | 12.9 ms: 1.12x slower                                                        |
| telco                    | 7.21 ms                                                      | 8.07 ms: 1.12x slower                                                        |
| regex_effbot             | 3.10 ms                                                      | 3.59 ms: 1.16x slower                                                        |
| coverage                 | 65.9 ms                                                      | 79.8 ms: 1.21x slower                                                        |
| python_startup_no_site   | 7.35 ms                                                      | 11.3 ms: 1.54x slower                                                        |
| Geometric mean           | (ref)                                                        | 1.29x faster                                                                 |
Ignored benchmarks (11) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
Ignored benchmarks (4) of results/bm-20231115-3.13.0a1+-7e2308a/bm-20231115-pythonperf2-x86_64-python-7e2308aaa29419eadeef-3.13.0a1+-7e2308a.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.25x
- 95% likely to have a speedup of 1.24x
- 99% likely to have a speedup of 1.22x
