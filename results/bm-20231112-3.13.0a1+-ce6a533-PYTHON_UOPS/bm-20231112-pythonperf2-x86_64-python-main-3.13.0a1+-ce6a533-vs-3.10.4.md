
# Results vs. 3.10.4

- fork: python
- ref: main
- machine: linux-x86_64
- commit hash: ce6a533
- commit date: 2023-11-12
- overall geometric mean: 1.15x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.08x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231112-pythonperf2-x86_64-python-main-3.13.0a1+-ce6a533 |
|----------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| 2to3           | 349 ms                                                       | 323 ms: 1.08x faster                                         |
| chameleon      | 9.88 ms                                                      | 7.93 ms: 1.25x faster                                        |
| docutils       | 3.42 sec                                                     | 2.99 sec: 1.14x faster                                       |
| tornado_http   | 157 ms                                                       | 127 ms: 1.24x faster                                         |
| Geometric mean | (ref)                                                        | 1.17x faster                                                 |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231112-pythonperf2-x86_64-python-main-3.13.0a1+-ce6a533 |
|-------------------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| async_tree_none         | 700 ms                                                       | 468 ms: 1.50x faster                                         |
| async_tree_io           | 1.61 sec                                                     | 1.13 sec: 1.42x faster                                       |
| async_tree_memoization  | 827 ms                                                       | 581 ms: 1.42x faster                                         |
| async_tree_cpu_io_mixed | 946 ms                                                       | 731 ms: 1.29x faster                                         |
| Geometric mean          | (ref)                                                        | 1.41x faster                                                 |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231112-pythonperf2-x86_64-python-main-3.13.0a1+-ce6a533 |
|----------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| nbody          | 134 ms                                                       | 129 ms: 1.04x faster                                         |
| pidigits       | 270 ms                                                       | 266 ms: 1.01x faster                                         |
| float          | 109 ms                                                       | 116 ms: 1.07x slower                                         |
| Geometric mean | (ref)                                                        | 1.00x slower                                                 |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231112-pythonperf2-x86_64-python-main-3.13.0a1+-ce6a533 |
|----------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| regex_v8       | 27.1 ms                                                      | 25.5 ms: 1.06x faster                                        |
| regex_compile  | 192 ms                                                       | 183 ms: 1.05x faster                                         |
| regex_dna      | 260 ms                                                       | 248 ms: 1.05x faster                                         |
| regex_effbot   | 3.10 ms                                                      | 3.53 ms: 1.14x slower                                        |
| Geometric mean | (ref)                                                        | 1.01x faster                                                 |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231112-pythonperf2-x86_64-python-main-3.13.0a1+-ce6a533 |
|----------------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| pickle_pure_python   | 453 us                                                       | 326 us: 1.39x faster                                         |
| json_dumps           | 14.2 ms                                                      | 10.7 ms: 1.33x faster                                        |
| xml_etree_process    | 76.4 ms                                                      | 60.6 ms: 1.26x faster                                        |
| unpickle_pure_python | 315 us                                                       | 252 us: 1.25x faster                                         |
| json_loads           | 30.0 us                                                      | 24.7 us: 1.22x faster                                        |
| xml_etree_parse      | 159 ms                                                       | 154 ms: 1.04x faster                                         |
| xml_etree_generate   | 93.1 ms                                                      | 89.8 ms: 1.04x faster                                        |
| pickle               | 10.1 us                                                      | 10.4 us: 1.03x slower                                        |
| pickle_list          | 4.23 us                                                      | 4.43 us: 1.05x slower                                        |
| unpickle             | 13.9 us                                                      | 14.8 us: 1.06x slower                                        |
| unpickle_list        | 4.45 us                                                      | 4.74 us: 1.07x slower                                        |
| xml_etree_iterparse  | 110 ms                                                       | 118 ms: 1.07x slower                                         |
| pickle_dict          | 30.4 us                                                      | 33.1 us: 1.09x slower                                        |
| tomli_loads          | 2.96 sec                                                     | 3.40 sec: 1.15x slower                                       |
| Geometric mean       | (ref)                                                        | 1.06x faster                                                 |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231112-pythonperf2-x86_64-python-main-3.13.0a1+-ce6a533 |
|------------------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| python_startup         | 11.5 ms                                                      | 12.9 ms: 1.12x slower                                        |
| python_startup_no_site | 7.35 ms                                                      | 11.4 ms: 1.55x slower                                        |
| Geometric mean         | (ref)                                                        | 1.32x slower                                                 |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231112-pythonperf2-x86_64-python-main-3.13.0a1+-ce6a533 |
|-----------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| mako      | 14.7 ms                                                      | 16.2 ms: 1.10x slower                                        |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231112-pythonperf2-x86_64-python-main-3.13.0a1+-ce6a533 |
|--------------------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| typing_runtime_protocols | 533 us                                                       | 135 us: 3.96x faster                                         |
| asyncio_tcp              | 785 ms                                                       | 376 ms: 2.08x faster                                         |
| asyncio_tcp_ssl          | 3.13 sec                                                     | 1.60 sec: 1.96x faster                                       |
| logging_silent           | 168 ns                                                       | 98.8 ns: 1.70x faster                                        |
| generators               | 57.7 ms                                                      | 35.3 ms: 1.63x faster                                        |
| raytrace                 | 497 ms                                                       | 307 ms: 1.62x faster                                         |
| spectral_norm            | 141 ms                                                       | 90.9 ms: 1.55x faster                                        |
| sqlglot_parse            | 2.27 ms                                                      | 1.49 ms: 1.52x faster                                        |
| scimark_lu               | 165 ms                                                       | 109 ms: 1.52x faster                                         |
| async_tree_none          | 700 ms                                                       | 468 ms: 1.50x faster                                         |
| sqlglot_transpile        | 2.73 ms                                                      | 1.91 ms: 1.43x faster                                        |
| async_tree_io            | 1.61 sec                                                     | 1.13 sec: 1.42x faster                                       |
| async_tree_memoization   | 827 ms                                                       | 581 ms: 1.42x faster                                         |
| richards_super           | 93.0 ms                                                      | 65.6 ms: 1.42x faster                                        |
| chaos                    | 106 ms                                                       | 75.7 ms: 1.40x faster                                        |
| coroutines               | 30.9 ms                                                      | 22.1 ms: 1.40x faster                                        |
| pickle_pure_python       | 453 us                                                       | 326 us: 1.39x faster                                         |
| bench_mp_pool            | 6.82 ms                                                      | 4.98 ms: 1.37x faster                                        |
| json_dumps               | 14.2 ms                                                      | 10.7 ms: 1.33x faster                                        |
| async_tree_cpu_io_mixed  | 946 ms                                                       | 731 ms: 1.29x faster                                         |
| crypto_pyaes             | 118 ms                                                       | 91.2 ms: 1.29x faster                                        |
| richards                 | 76.3 ms                                                      | 59.2 ms: 1.29x faster                                        |
| scimark_monte_carlo      | 109 ms                                                       | 85.1 ms: 1.29x faster                                        |
| go                       | 258 ms                                                       | 201 ms: 1.28x faster                                         |
| logging_simple           | 9.06 us                                                      | 7.08 us: 1.28x faster                                        |
| logging_format           | 9.82 us                                                      | 7.72 us: 1.27x faster                                        |
| xml_etree_process        | 76.4 ms                                                      | 60.6 ms: 1.26x faster                                        |
| unpickle_pure_python     | 315 us                                                       | 252 us: 1.25x faster                                         |
| sqlglot_normalize        | 146 ms                                                       | 117 ms: 1.25x faster                                         |
| chameleon                | 9.88 ms                                                      | 7.93 ms: 1.25x faster                                        |
| deltablue                | 7.43 ms                                                      | 5.99 ms: 1.24x faster                                        |
| tornado_http             | 157 ms                                                       | 127 ms: 1.24x faster                                         |
| scimark_sor              | 183 ms                                                       | 150 ms: 1.22x faster                                         |
| json_loads               | 30.0 us                                                      | 24.7 us: 1.22x faster                                        |
| pycparser                | 1.65 sec                                                     | 1.36 sec: 1.21x faster                                       |
| mypy2                    | 467 ms                                                       | 386 ms: 1.21x faster                                         |
| deepcopy                 | 459 us                                                       | 384 us: 1.20x faster                                         |
| deepcopy_reduce          | 4.00 us                                                      | 3.35 us: 1.19x faster                                        |
| sympy_sum                | 194 ms                                                       | 163 ms: 1.19x faster                                         |
| deepcopy_memo            | 50.5 us                                                      | 43.4 us: 1.16x faster                                        |
| sqlglot_optimize         | 69.9 ms                                                      | 60.2 ms: 1.16x faster                                        |
| json                     | 5.91 ms                                                      | 5.15 ms: 1.15x faster                                        |
| pyflate                  | 698 ms                                                       | 612 ms: 1.14x faster                                         |
| docutils                 | 3.42 sec                                                     | 2.99 sec: 1.14x faster                                       |
| unpack_sequence          | 60.3 ns                                                      | 53.1 ns: 1.13x faster                                        |
| create_gc_cycles         | 1.79 ms                                                      | 1.58 ms: 1.13x faster                                        |
| sympy_str                | 359 ms                                                       | 319 ms: 1.12x faster                                         |
| pprint_pformat           | 2.15 sec                                                     | 1.92 sec: 1.12x faster                                       |
| bench_thread_pool        | 1.13 ms                                                      | 1.02 ms: 1.12x faster                                        |
| sympy_expand             | 599 ms                                                       | 539 ms: 1.11x faster                                         |
| pprint_safe_repr         | 1.04 sec                                                     | 937 ms: 1.11x faster                                         |
| dulwich_log              | 80.0 ms                                                      | 72.2 ms: 1.11x faster                                        |
| sympy_integrate          | 28.3 ms                                                      | 25.9 ms: 1.10x faster                                        |
| async_generators         | 418 ms                                                       | 385 ms: 1.09x faster                                         |
| 2to3                     | 349 ms                                                       | 323 ms: 1.08x faster                                         |
| sqlite_synth             | 2.97 us                                                      | 2.76 us: 1.07x faster                                        |
| regex_v8                 | 27.1 ms                                                      | 25.5 ms: 1.06x faster                                        |
| regex_compile            | 192 ms                                                       | 183 ms: 1.05x faster                                         |
| regex_dna                | 260 ms                                                       | 248 ms: 1.05x faster                                         |
| mdp                      | 2.94 sec                                                     | 2.80 sec: 1.05x faster                                       |
| nbody                    | 134 ms                                                       | 129 ms: 1.04x faster                                         |
| xml_etree_parse          | 159 ms                                                       | 154 ms: 1.04x faster                                         |
| xml_etree_generate       | 93.1 ms                                                      | 89.8 ms: 1.04x faster                                        |
| pathlib                  | 21.2 ms                                                      | 20.7 ms: 1.02x faster                                        |
| asyncio_websockets       | 394 ms                                                       | 388 ms: 1.02x faster                                         |
| pidigits                 | 270 ms                                                       | 266 ms: 1.01x faster                                         |
| pickle                   | 10.1 us                                                      | 10.4 us: 1.03x slower                                        |
| pickle_list              | 4.23 us                                                      | 4.43 us: 1.05x slower                                        |
| meteor_contest           | 138 ms                                                       | 145 ms: 1.06x slower                                         |
| unpickle                 | 13.9 us                                                      | 14.8 us: 1.06x slower                                        |
| unpickle_list            | 4.45 us                                                      | 4.74 us: 1.07x slower                                        |
| float                    | 109 ms                                                       | 116 ms: 1.07x slower                                         |
| xml_etree_iterparse      | 110 ms                                                       | 118 ms: 1.07x slower                                         |
| pickle_dict              | 30.4 us                                                      | 33.1 us: 1.09x slower                                        |
| mako                     | 14.7 ms                                                      | 16.2 ms: 1.10x slower                                        |
| gc_traversal             | 3.63 ms                                                      | 4.01 ms: 1.11x slower                                        |
| python_startup           | 11.5 ms                                                      | 12.9 ms: 1.12x slower                                        |
| regex_effbot             | 3.10 ms                                                      | 3.53 ms: 1.14x slower                                        |
| tomli_loads              | 2.96 sec                                                     | 3.40 sec: 1.15x slower                                       |
| nqueens                  | 112 ms                                                       | 129 ms: 1.15x slower                                         |
| scimark_fft              | 363 ms                                                       | 418 ms: 1.15x slower                                         |
| fannkuch                 | 488 ms                                                       | 577 ms: 1.18x slower                                         |
| telco                    | 7.21 ms                                                      | 8.61 ms: 1.19x slower                                        |
| comprehensions           | 27.0 us                                                      | 32.5 us: 1.20x slower                                        |
| coverage                 | 65.9 ms                                                      | 83.2 ms: 1.26x slower                                        |
| hexiom                   | 9.46 ms                                                      | 12.6 ms: 1.33x slower                                        |
| scimark_sparse_mat_mult  | 5.21 ms                                                      | 7.36 ms: 1.41x slower                                        |
| python_startup_no_site   | 7.35 ms                                                      | 11.4 ms: 1.55x slower                                        |
| Geometric mean           | (ref)                                                        | 1.15x faster                                                 |
Ignored benchmarks (12) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, dask, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
Ignored benchmarks (4) of results/bm-20231112-3.13.0a1+-ce6a533-PYTHON_UOPS/bm-20231112-pythonperf2-x86_64-python-main-3.13.0a1+-ce6a533.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.11x
- 95% likely to have a speedup of 1.10x
- 99% likely to have a speedup of 1.08x
