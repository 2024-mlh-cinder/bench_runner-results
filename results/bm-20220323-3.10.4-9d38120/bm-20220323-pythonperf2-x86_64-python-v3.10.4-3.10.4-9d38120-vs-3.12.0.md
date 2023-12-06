
# Results vs. 3.12.0

- fork: python
- ref: v3.10.4
- machine: linux-x86_64
- commit hash: 9d38120
- commit date: 2022-03-23
- overall geometric mean: 1.30x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.21x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 |
|----------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| 2to3           | 285 ms                                                       | 349 ms: 1.23x slower                                         |
| chameleon      | 7.27 ms                                                      | 9.88 ms: 1.36x slower                                        |
| docutils       | 2.89 sec                                                     | 3.42 sec: 1.18x slower                                       |
| tornado_http   | 122 ms                                                       | 157 ms: 1.28x slower                                         |
| Geometric mean | (ref)                                                        | 1.26x slower                                                 |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 |
|-------------------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| async_tree_cpu_io_mixed | 704 ms                                                       | 946 ms: 1.34x slower                                         |
| async_tree_memoization  | 554 ms                                                       | 827 ms: 1.49x slower                                         |
| async_tree_io           | 1.06 sec                                                     | 1.61 sec: 1.52x slower                                       |
| async_tree_none         | 459 ms                                                       | 700 ms: 1.52x slower                                         |
| Geometric mean          | (ref)                                                        | 1.47x slower                                                 |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 |
|----------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| pidigits       | 264 ms                                                       | 270 ms: 1.02x slower                                         |
| float          | 81.6 ms                                                      | 109 ms: 1.33x slower                                         |
| nbody          | 88.2 ms                                                      | 134 ms: 1.52x slower                                         |
| Geometric mean | (ref)                                                        | 1.27x slower                                                 |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 |
|----------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| regex_effbot   | 3.61 ms                                                      | 3.10 ms: 1.17x faster                                        |
| regex_dna      | 240 ms                                                       | 260 ms: 1.08x slower                                         |
| regex_v8       | 24.4 ms                                                      | 27.1 ms: 1.11x slower                                        |
| regex_compile  | 145 ms                                                       | 192 ms: 1.33x slower                                         |
| Geometric mean | (ref)                                                        | 1.08x slower                                                 |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 |
|----------------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| unpickle             | 15.3 us                                                      | 13.9 us: 1.10x faster                                        |
| pickle_dict          | 32.0 us                                                      | 30.4 us: 1.05x faster                                        |
| unpickle_list        | 4.65 us                                                      | 4.45 us: 1.05x faster                                        |
| pickle               | 10.0 us                                                      | 10.1 us: 1.00x slower                                        |
| xml_etree_iterparse  | 104 ms                                                       | 110 ms: 1.06x slower                                         |
| xml_etree_parse      | 147 ms                                                       | 159 ms: 1.09x slower                                         |
| xml_etree_generate   | 85.3 ms                                                      | 93.1 ms: 1.09x slower                                        |
| json_loads           | 24.3 us                                                      | 30.0 us: 1.24x slower                                        |
| xml_etree_process    | 58.3 ms                                                      | 76.4 ms: 1.31x slower                                        |
| tomli_loads          | 2.17 sec                                                     | 2.96 sec: 1.36x slower                                       |
| json_dumps           | 10.3 ms                                                      | 14.2 ms: 1.39x slower                                        |
| pickle_pure_python   | 319 us                                                       | 453 us: 1.42x slower                                         |
| unpickle_pure_python | 210 us                                                       | 315 us: 1.50x slower                                         |
| Geometric mean       | (ref)                                                        | 1.15x slower                                                 |

Benchmark hidden because not significant (1): pickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 |
|------------------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| python_startup_no_site | 8.67 ms                                                      | 7.35 ms: 1.18x faster                                        |
| python_startup         | 11.7 ms                                                      | 11.5 ms: 1.01x faster                                        |
| Geometric mean         | (ref)                                                        | 1.09x faster                                                 |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 |
|-----------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| django_template | 38.7 ms                                                      | 51.8 ms: 1.34x slower                                        |
| mako            | 10.1 ms                                                      | 14.7 ms: 1.46x slower                                        |
| Geometric mean  | (ref)                                                        | 1.40x slower                                                 |

All benchmarks:
===============

| Benchmark                | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 |
|--------------------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| python_startup_no_site   | 8.67 ms                                                      | 7.35 ms: 1.18x faster                                        |
| regex_effbot             | 3.61 ms                                                      | 3.10 ms: 1.17x faster                                        |
| unpickle                 | 15.3 us                                                      | 13.9 us: 1.10x faster                                        |
| pickle_dict              | 32.0 us                                                      | 30.4 us: 1.05x faster                                        |
| unpickle_list            | 4.65 us                                                      | 4.45 us: 1.05x faster                                        |
| gc_traversal             | 3.70 ms                                                      | 3.63 ms: 1.02x faster                                        |
| python_startup           | 11.7 ms                                                      | 11.5 ms: 1.01x faster                                        |
| pickle                   | 10.0 us                                                      | 10.1 us: 1.00x slower                                        |
| telco                    | 7.16 ms                                                      | 7.21 ms: 1.01x slower                                        |
| asyncio_websockets       | 386 ms                                                       | 394 ms: 1.02x slower                                         |
| pidigits                 | 264 ms                                                       | 270 ms: 1.02x slower                                         |
| xml_etree_iterparse      | 104 ms                                                       | 110 ms: 1.06x slower                                         |
| regex_dna                | 240 ms                                                       | 260 ms: 1.08x slower                                         |
| xml_etree_parse          | 147 ms                                                       | 159 ms: 1.09x slower                                         |
| async_generators         | 385 ms                                                       | 418 ms: 1.09x slower                                         |
| meteor_contest           | 126 ms                                                       | 138 ms: 1.09x slower                                         |
| xml_etree_generate       | 85.3 ms                                                      | 93.1 ms: 1.09x slower                                        |
| sqlite_synth             | 2.72 us                                                      | 2.97 us: 1.09x slower                                        |
| unpack_sequence          | 54.5 ns                                                      | 60.3 ns: 1.11x slower                                        |
| regex_v8                 | 24.4 ms                                                      | 27.1 ms: 1.11x slower                                        |
| pathlib                  | 18.7 ms                                                      | 21.2 ms: 1.13x slower                                        |
| create_gc_cycles         | 1.58 ms                                                      | 1.79 ms: 1.13x slower                                        |
| json                     | 5.17 ms                                                      | 5.91 ms: 1.14x slower                                        |
| mdp                      | 2.56 sec                                                     | 2.94 sec: 1.15x slower                                       |
| scimark_sparse_mat_mult  | 4.49 ms                                                      | 5.21 ms: 1.16x slower                                        |
| deepcopy_reduce          | 3.41 us                                                      | 4.00 us: 1.17x slower                                        |
| sympy_str                | 305 ms                                                       | 359 ms: 1.18x slower                                         |
| sqlalchemy_declarative   | 161 ms                                                       | 189 ms: 1.18x slower                                         |
| sympy_integrate          | 24.0 ms                                                      | 28.3 ms: 1.18x slower                                        |
| docutils                 | 2.89 sec                                                     | 3.42 sec: 1.18x slower                                       |
| bench_thread_pool        | 956 us                                                       | 1.13 ms: 1.19x slower                                        |
| sympy_sum                | 163 ms                                                       | 194 ms: 1.19x slower                                         |
| aiohttp                  | 1.02 ms                                                      | 1.21 ms: 1.19x slower                                        |
| dask                     | 394 ms                                                       | 469 ms: 1.19x slower                                         |
| gunicorn                 | 1.01 ms                                                      | 1.20 ms: 1.19x slower                                        |
| scimark_fft              | 303 ms                                                       | 363 ms: 1.20x slower                                         |
| sqlglot_optimize         | 58.4 ms                                                      | 69.9 ms: 1.20x slower                                        |
| sympy_expand             | 492 ms                                                       | 599 ms: 1.22x slower                                         |
| sqlglot_normalize        | 119 ms                                                       | 146 ms: 1.23x slower                                         |
| 2to3                     | 285 ms                                                       | 349 ms: 1.23x slower                                         |
| dulwich_log              | 64.9 ms                                                      | 80.0 ms: 1.23x slower                                        |
| json_loads               | 24.3 us                                                      | 30.0 us: 1.24x slower                                        |
| deepcopy                 | 371 us                                                       | 459 us: 1.24x slower                                         |
| sqlalchemy_imperative    | 18.6 ms                                                      | 23.0 ms: 1.24x slower                                        |
| comprehensions           | 21.8 us                                                      | 27.0 us: 1.24x slower                                        |
| nqueens                  | 90.1 ms                                                      | 112 ms: 1.24x slower                                         |
| pycparser                | 1.29 sec                                                     | 1.65 sec: 1.27x slower                                       |
| mypy2                    | 365 ms                                                       | 467 ms: 1.28x slower                                         |
| tornado_http             | 122 ms                                                       | 157 ms: 1.28x slower                                         |
| pprint_safe_repr         | 808 ms                                                       | 1.04 sec: 1.29x slower                                       |
| pprint_pformat           | 1.64 sec                                                     | 2.15 sec: 1.31x slower                                       |
| xml_etree_process        | 58.3 ms                                                      | 76.4 ms: 1.31x slower                                        |
| float                    | 81.6 ms                                                      | 109 ms: 1.33x slower                                         |
| regex_compile            | 145 ms                                                       | 192 ms: 1.33x slower                                         |
| django_template          | 38.7 ms                                                      | 51.8 ms: 1.34x slower                                        |
| coroutines               | 23.1 ms                                                      | 30.9 ms: 1.34x slower                                        |
| async_tree_cpu_io_mixed  | 704 ms                                                       | 946 ms: 1.34x slower                                         |
| logging_format           | 7.29 us                                                      | 9.82 us: 1.35x slower                                        |
| fannkuch                 | 362 ms                                                       | 488 ms: 1.35x slower                                         |
| chameleon                | 7.27 ms                                                      | 9.88 ms: 1.36x slower                                        |
| tomli_loads              | 2.17 sec                                                     | 2.96 sec: 1.36x slower                                       |
| logging_simple           | 6.64 us                                                      | 9.06 us: 1.36x slower                                        |
| bench_mp_pool            | 4.96 ms                                                      | 6.82 ms: 1.38x slower                                        |
| deepcopy_memo            | 36.6 us                                                      | 50.5 us: 1.38x slower                                        |
| json_dumps               | 10.3 ms                                                      | 14.2 ms: 1.39x slower                                        |
| pickle_pure_python       | 319 us                                                       | 453 us: 1.42x slower                                         |
| crypto_pyaes             | 82.4 ms                                                      | 118 ms: 1.43x slower                                         |
| mako                     | 10.1 ms                                                      | 14.7 ms: 1.46x slower                                        |
| async_tree_memoization   | 554 ms                                                       | 827 ms: 1.49x slower                                         |
| unpickle_pure_python     | 210 us                                                       | 315 us: 1.50x slower                                         |
| spectral_norm            | 93.9 ms                                                      | 141 ms: 1.50x slower                                         |
| sqlglot_transpile        | 1.80 ms                                                      | 2.73 ms: 1.51x slower                                        |
| async_tree_io            | 1.06 sec                                                     | 1.61 sec: 1.52x slower                                       |
| nbody                    | 88.2 ms                                                      | 134 ms: 1.52x slower                                         |
| async_tree_none          | 459 ms                                                       | 700 ms: 1.52x slower                                         |
| generators               | 37.3 ms                                                      | 57.7 ms: 1.55x slower                                        |
| scimark_monte_carlo      | 69.5 ms                                                      | 109 ms: 1.57x slower                                         |
| pyflate                  | 442 ms                                                       | 698 ms: 1.58x slower                                         |
| hexiom                   | 5.97 ms                                                      | 9.46 ms: 1.58x slower                                        |
| sqlglot_parse            | 1.41 ms                                                      | 2.27 ms: 1.61x slower                                        |
| raytrace                 | 301 ms                                                       | 497 ms: 1.65x slower                                         |
| chaos                    | 64.1 ms                                                      | 106 ms: 1.65x slower                                         |
| scimark_lu               | 98.6 ms                                                      | 165 ms: 1.67x slower                                         |
| richards                 | 45.1 ms                                                      | 76.3 ms: 1.69x slower                                        |
| scimark_sor              | 107 ms                                                       | 183 ms: 1.72x slower                                         |
| go                       | 149 ms                                                       | 258 ms: 1.73x slower                                         |
| logging_silent           | 93.3 ns                                                      | 168 ns: 1.80x slower                                         |
| richards_super           | 50.8 ms                                                      | 93.0 ms: 1.83x slower                                        |
| asyncio_tcp_ssl          | 1.57 sec                                                     | 3.13 sec: 1.99x slower                                       |
| asyncio_tcp              | 380 ms                                                       | 785 ms: 2.07x slower                                         |
| deltablue                | 3.24 ms                                                      | 7.43 ms: 2.29x slower                                        |
| typing_runtime_protocols | 150 us                                                       | 533 us: 3.55x slower                                         |
| Geometric mean           | (ref)                                                        | 1.30x slower                                                 |

Benchmark hidden because not significant (2): coverage, pickle_list
Ignored benchmarks (4) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg
Ignored benchmarks (6) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120.json: flaskblogging, genshi_text, genshi_xml, html5lib, pylint, thrift


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.24x
- 95% likely to have a slowdown of 1.23x
- 99% likely to have a slowdown of 1.21x
