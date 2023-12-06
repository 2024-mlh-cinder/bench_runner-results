
# Results vs. 3.10.4

- fork: python
- ref: 4fe22c73770fe86b01ef
- machine: linux-x86_64
- commit hash: 4fe22c7
- commit date: 2023-11-02
- overall geometric mean: 1.30x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.24x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231102-pythonperf2-x86_64-python-4fe22c73770fe86b01ef-3.13.0a1+-4fe22c7 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| 2to3           | 349 ms                                                       | 291 ms: 1.20x faster                                                         |
| chameleon      | 9.88 ms                                                      | 7.44 ms: 1.33x faster                                                        |
| docutils       | 3.42 sec                                                     | 2.83 sec: 1.21x faster                                                       |
| tornado_http   | 157 ms                                                       | 118 ms: 1.32x faster                                                         |
| Geometric mean | (ref)                                                        | 1.26x faster                                                                 |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231102-pythonperf2-x86_64-python-4fe22c73770fe86b01ef-3.13.0a1+-4fe22c7 |
|-------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| async_tree_none         | 700 ms                                                       | 433 ms: 1.62x faster                                                         |
| async_tree_memoization  | 827 ms                                                       | 546 ms: 1.51x faster                                                         |
| async_tree_io           | 1.61 sec                                                     | 1.08 sec: 1.49x faster                                                       |
| async_tree_cpu_io_mixed | 946 ms                                                       | 699 ms: 1.35x faster                                                         |
| Geometric mean          | (ref)                                                        | 1.49x faster                                                                 |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231102-pythonperf2-x86_64-python-4fe22c73770fe86b01ef-3.13.0a1+-4fe22c7 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| nbody          | 134 ms                                                       | 87.6 ms: 1.53x faster                                                        |
| float          | 109 ms                                                       | 79.3 ms: 1.37x faster                                                        |
| pidigits       | 270 ms                                                       | 265 ms: 1.02x faster                                                         |
| Geometric mean | (ref)                                                        | 1.29x faster                                                                 |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231102-pythonperf2-x86_64-python-4fe22c73770fe86b01ef-3.13.0a1+-4fe22c7 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| regex_compile  | 192 ms                                                       | 145 ms: 1.33x faster                                                         |
| regex_dna      | 260 ms                                                       | 234 ms: 1.11x faster                                                         |
| regex_v8       | 27.1 ms                                                      | 25.3 ms: 1.07x faster                                                        |
| regex_effbot   | 3.10 ms                                                      | 3.50 ms: 1.13x slower                                                        |
| Geometric mean | (ref)                                                        | 1.09x faster                                                                 |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231102-pythonperf2-x86_64-python-4fe22c73770fe86b01ef-3.13.0a1+-4fe22c7 |
|----------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| unpickle_pure_python | 315 us                                                       | 221 us: 1.43x faster                                                         |
| pickle_pure_python   | 453 us                                                       | 317 us: 1.43x faster                                                         |
| json_dumps           | 14.2 ms                                                      | 10.4 ms: 1.36x faster                                                        |
| tomli_loads          | 2.96 sec                                                     | 2.21 sec: 1.34x faster                                                       |
| xml_etree_process    | 76.4 ms                                                      | 58.1 ms: 1.32x faster                                                        |
| json_loads           | 30.0 us                                                      | 24.3 us: 1.23x faster                                                        |
| xml_etree_generate   | 93.1 ms                                                      | 85.1 ms: 1.09x faster                                                        |
| xml_etree_parse      | 159 ms                                                       | 146 ms: 1.09x faster                                                         |
| xml_etree_iterparse  | 110 ms                                                       | 105 ms: 1.04x faster                                                         |
| pickle               | 10.1 us                                                      | 10.2 us: 1.01x slower                                                        |
| pickle_list          | 4.23 us                                                      | 4.38 us: 1.04x slower                                                        |
| pickle_dict          | 30.4 us                                                      | 31.5 us: 1.04x slower                                                        |
| unpickle             | 13.9 us                                                      | 14.6 us: 1.05x slower                                                        |
| unpickle_list        | 4.45 us                                                      | 4.77 us: 1.07x slower                                                        |
| Geometric mean       | (ref)                                                        | 1.14x faster                                                                 |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231102-pythonperf2-x86_64-python-4fe22c73770fe86b01ef-3.13.0a1+-4fe22c7 |
|------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| python_startup         | 11.5 ms                                                      | 12.8 ms: 1.11x slower                                                        |
| python_startup_no_site | 7.35 ms                                                      | 11.3 ms: 1.53x slower                                                        |
| Geometric mean         | (ref)                                                        | 1.30x slower                                                                 |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231102-pythonperf2-x86_64-python-4fe22c73770fe86b01ef-3.13.0a1+-4fe22c7 |
|-----------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| mako      | 14.7 ms                                                      | 10.2 ms: 1.45x faster                                                        |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231102-pythonperf2-x86_64-python-4fe22c73770fe86b01ef-3.13.0a1+-4fe22c7 |
|--------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| typing_runtime_protocols | 533 us                                                       | 124 us: 4.31x faster                                                         |
| asyncio_tcp              | 785 ms                                                       | 366 ms: 2.15x faster                                                         |
| deltablue                | 7.43 ms                                                      | 3.63 ms: 2.04x faster                                                        |
| asyncio_tcp_ssl          | 3.13 sec                                                     | 1.58 sec: 1.98x faster                                                       |
| raytrace                 | 497 ms                                                       | 272 ms: 1.83x faster                                                         |
| logging_silent           | 168 ns                                                       | 94.1 ns: 1.78x faster                                                        |
| chaos                    | 106 ms                                                       | 61.1 ms: 1.73x faster                                                        |
| scimark_monte_carlo      | 109 ms                                                       | 63.2 ms: 1.73x faster                                                        |
| crypto_pyaes             | 118 ms                                                       | 70.6 ms: 1.67x faster                                                        |
| comprehensions           | 27.0 us                                                      | 16.4 us: 1.65x faster                                                        |
| scimark_lu               | 165 ms                                                       | 100 ms: 1.64x faster                                                         |
| generators               | 57.7 ms                                                      | 35.6 ms: 1.62x faster                                                        |
| async_tree_none          | 700 ms                                                       | 433 ms: 1.62x faster                                                         |
| sqlglot_parse            | 2.27 ms                                                      | 1.41 ms: 1.61x faster                                                        |
| richards_super           | 93.0 ms                                                      | 59.9 ms: 1.55x faster                                                        |
| spectral_norm            | 141 ms                                                       | 91.1 ms: 1.55x faster                                                        |
| nbody                    | 134 ms                                                       | 87.6 ms: 1.53x faster                                                        |
| async_tree_memoization   | 827 ms                                                       | 546 ms: 1.51x faster                                                         |
| go                       | 258 ms                                                       | 171 ms: 1.51x faster                                                         |
| sqlglot_transpile        | 2.73 ms                                                      | 1.82 ms: 1.50x faster                                                        |
| async_tree_io            | 1.61 sec                                                     | 1.08 sec: 1.49x faster                                                       |
| hexiom                   | 9.46 ms                                                      | 6.46 ms: 1.46x faster                                                        |
| mako                     | 14.7 ms                                                      | 10.2 ms: 1.45x faster                                                        |
| unpickle_pure_python     | 315 us                                                       | 221 us: 1.43x faster                                                         |
| pickle_pure_python       | 453 us                                                       | 317 us: 1.43x faster                                                         |
| richards                 | 76.3 ms                                                      | 54.0 ms: 1.41x faster                                                        |
| pyflate                  | 698 ms                                                       | 502 ms: 1.39x faster                                                         |
| bench_mp_pool            | 6.82 ms                                                      | 4.91 ms: 1.39x faster                                                        |
| coroutines               | 30.9 ms                                                      | 22.5 ms: 1.37x faster                                                        |
| float                    | 109 ms                                                       | 79.3 ms: 1.37x faster                                                        |
| json_dumps               | 14.2 ms                                                      | 10.4 ms: 1.36x faster                                                        |
| async_tree_cpu_io_mixed  | 946 ms                                                       | 699 ms: 1.35x faster                                                         |
| deepcopy_memo            | 50.5 us                                                      | 37.3 us: 1.35x faster                                                        |
| tomli_loads              | 2.96 sec                                                     | 2.21 sec: 1.34x faster                                                       |
| regex_compile            | 192 ms                                                       | 145 ms: 1.33x faster                                                         |
| chameleon                | 9.88 ms                                                      | 7.44 ms: 1.33x faster                                                        |
| pprint_pformat           | 2.15 sec                                                     | 1.62 sec: 1.32x faster                                                       |
| logging_simple           | 9.06 us                                                      | 6.86 us: 1.32x faster                                                        |
| tornado_http             | 157 ms                                                       | 118 ms: 1.32x faster                                                         |
| logging_format           | 9.82 us                                                      | 7.46 us: 1.32x faster                                                        |
| xml_etree_process        | 76.4 ms                                                      | 58.1 ms: 1.32x faster                                                        |
| pprint_safe_repr         | 1.04 sec                                                     | 795 ms: 1.31x faster                                                         |
| sympy_sum                | 194 ms                                                       | 149 ms: 1.30x faster                                                         |
| sqlglot_normalize        | 146 ms                                                       | 113 ms: 1.29x faster                                                         |
| scimark_sparse_mat_mult  | 5.21 ms                                                      | 4.06 ms: 1.28x faster                                                        |
| nqueens                  | 112 ms                                                       | 87.5 ms: 1.28x faster                                                        |
| mypy2                    | 467 ms                                                       | 366 ms: 1.28x faster                                                         |
| scimark_sor              | 183 ms                                                       | 144 ms: 1.27x faster                                                         |
| fannkuch                 | 488 ms                                                       | 390 ms: 1.25x faster                                                         |
| sympy_str                | 359 ms                                                       | 287 ms: 1.25x faster                                                         |
| sympy_integrate          | 28.3 ms                                                      | 22.7 ms: 1.25x faster                                                        |
| scimark_fft              | 363 ms                                                       | 293 ms: 1.24x faster                                                         |
| deepcopy                 | 459 us                                                       | 372 us: 1.23x faster                                                         |
| pycparser                | 1.65 sec                                                     | 1.34 sec: 1.23x faster                                                       |
| json_loads               | 30.0 us                                                      | 24.3 us: 1.23x faster                                                        |
| deepcopy_reduce          | 4.00 us                                                      | 3.26 us: 1.23x faster                                                        |
| sympy_expand             | 599 ms                                                       | 489 ms: 1.22x faster                                                         |
| sqlglot_optimize         | 69.9 ms                                                      | 57.5 ms: 1.21x faster                                                        |
| docutils                 | 3.42 sec                                                     | 2.83 sec: 1.21x faster                                                       |
| 2to3                     | 349 ms                                                       | 291 ms: 1.20x faster                                                         |
| bench_thread_pool        | 1.13 ms                                                      | 948 us: 1.20x faster                                                         |
| dulwich_log              | 80.0 ms                                                      | 68.2 ms: 1.17x faster                                                        |
| mdp                      | 2.94 sec                                                     | 2.51 sec: 1.17x faster                                                       |
| json                     | 5.91 ms                                                      | 5.16 ms: 1.15x faster                                                        |
| unpack_sequence          | 60.3 ns                                                      | 52.8 ns: 1.14x faster                                                        |
| async_generators         | 418 ms                                                       | 369 ms: 1.13x faster                                                         |
| regex_dna                | 260 ms                                                       | 234 ms: 1.11x faster                                                         |
| create_gc_cycles         | 1.79 ms                                                      | 1.63 ms: 1.10x faster                                                        |
| sqlite_synth             | 2.97 us                                                      | 2.71 us: 1.10x faster                                                        |
| xml_etree_generate       | 93.1 ms                                                      | 85.1 ms: 1.09x faster                                                        |
| xml_etree_parse          | 159 ms                                                       | 146 ms: 1.09x faster                                                         |
| pathlib                  | 21.2 ms                                                      | 19.5 ms: 1.08x faster                                                        |
| regex_v8                 | 27.1 ms                                                      | 25.3 ms: 1.07x faster                                                        |
| meteor_contest           | 138 ms                                                       | 129 ms: 1.07x faster                                                         |
| xml_etree_iterparse      | 110 ms                                                       | 105 ms: 1.04x faster                                                         |
| gc_traversal             | 3.63 ms                                                      | 3.50 ms: 1.04x faster                                                        |
| pidigits                 | 270 ms                                                       | 265 ms: 1.02x faster                                                         |
| asyncio_websockets       | 394 ms                                                       | 387 ms: 1.02x faster                                                         |
| pickle                   | 10.1 us                                                      | 10.2 us: 1.01x slower                                                        |
| pickle_list              | 4.23 us                                                      | 4.38 us: 1.04x slower                                                        |
| pickle_dict              | 30.4 us                                                      | 31.5 us: 1.04x slower                                                        |
| unpickle                 | 13.9 us                                                      | 14.6 us: 1.05x slower                                                        |
| unpickle_list            | 4.45 us                                                      | 4.77 us: 1.07x slower                                                        |
| python_startup           | 11.5 ms                                                      | 12.8 ms: 1.11x slower                                                        |
| regex_effbot             | 3.10 ms                                                      | 3.50 ms: 1.13x slower                                                        |
| telco                    | 7.21 ms                                                      | 8.20 ms: 1.14x slower                                                        |
| coverage                 | 65.9 ms                                                      | 82.4 ms: 1.25x slower                                                        |
| python_startup_no_site   | 7.35 ms                                                      | 11.3 ms: 1.53x slower                                                        |
| Geometric mean           | (ref)                                                        | 1.30x faster                                                                 |
Ignored benchmarks (12) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, dask, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
Ignored benchmarks (4) of results/bm-20231102-3.13.0a1+-4fe22c7/bm-20231102-pythonperf2-x86_64-python-4fe22c73770fe86b01ef-3.13.0a1+-4fe22c7.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.26x
- 95% likely to have a speedup of 1.25x
- 99% likely to have a speedup of 1.24x
