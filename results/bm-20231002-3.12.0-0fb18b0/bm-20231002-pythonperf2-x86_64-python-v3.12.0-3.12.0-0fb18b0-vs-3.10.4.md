
# Results vs. 3.10.4

- fork: python
- ref: v3.12.0
- machine: linux-x86_64
- commit hash: 0fb18b0
- commit date: 2023-10-02
- overall geometric mean: 1.30x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.21x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 |
|----------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| 2to3           | 349 ms                                                       | 285 ms: 1.23x faster                                         |
| chameleon      | 9.88 ms                                                      | 7.27 ms: 1.36x faster                                        |
| docutils       | 3.42 sec                                                     | 2.89 sec: 1.18x faster                                       |
| tornado_http   | 157 ms                                                       | 122 ms: 1.28x faster                                         |
| Geometric mean | (ref)                                                        | 1.26x faster                                                 |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 |
|-------------------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| async_tree_none         | 700 ms                                                       | 459 ms: 1.52x faster                                         |
| async_tree_io           | 1.61 sec                                                     | 1.06 sec: 1.52x faster                                       |
| async_tree_memoization  | 827 ms                                                       | 554 ms: 1.49x faster                                         |
| async_tree_cpu_io_mixed | 946 ms                                                       | 704 ms: 1.34x faster                                         |
| Geometric mean          | (ref)                                                        | 1.47x faster                                                 |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 |
|----------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| nbody          | 134 ms                                                       | 88.2 ms: 1.52x faster                                        |
| float          | 109 ms                                                       | 81.6 ms: 1.33x faster                                        |
| pidigits       | 270 ms                                                       | 264 ms: 1.02x faster                                         |
| Geometric mean | (ref)                                                        | 1.27x faster                                                 |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 |
|----------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| regex_compile  | 192 ms                                                       | 145 ms: 1.33x faster                                         |
| regex_v8       | 27.1 ms                                                      | 24.4 ms: 1.11x faster                                        |
| regex_dna      | 260 ms                                                       | 240 ms: 1.08x faster                                         |
| regex_effbot   | 3.10 ms                                                      | 3.61 ms: 1.17x slower                                        |
| Geometric mean | (ref)                                                        | 1.08x faster                                                 |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 |
|----------------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| unpickle_pure_python | 315 us                                                       | 210 us: 1.50x faster                                         |
| pickle_pure_python   | 453 us                                                       | 319 us: 1.42x faster                                         |
| json_dumps           | 14.2 ms                                                      | 10.3 ms: 1.39x faster                                        |
| tomli_loads          | 2.96 sec                                                     | 2.17 sec: 1.36x faster                                       |
| xml_etree_process    | 76.4 ms                                                      | 58.3 ms: 1.31x faster                                        |
| json_loads           | 30.0 us                                                      | 24.3 us: 1.24x faster                                        |
| xml_etree_generate   | 93.1 ms                                                      | 85.3 ms: 1.09x faster                                        |
| xml_etree_parse      | 159 ms                                                       | 147 ms: 1.09x faster                                         |
| xml_etree_iterparse  | 110 ms                                                       | 104 ms: 1.06x faster                                         |
| pickle               | 10.1 us                                                      | 10.0 us: 1.00x faster                                        |
| unpickle_list        | 4.45 us                                                      | 4.65 us: 1.05x slower                                        |
| pickle_dict          | 30.4 us                                                      | 32.0 us: 1.05x slower                                        |
| unpickle             | 13.9 us                                                      | 15.3 us: 1.10x slower                                        |
| Geometric mean       | (ref)                                                        | 1.15x faster                                                 |

Benchmark hidden because not significant (1): pickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 |
|------------------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| python_startup         | 11.5 ms                                                      | 11.7 ms: 1.01x slower                                        |
| python_startup_no_site | 7.35 ms                                                      | 8.67 ms: 1.18x slower                                        |
| Geometric mean         | (ref)                                                        | 1.09x slower                                                 |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 |
|-----------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| mako            | 14.7 ms                                                      | 10.1 ms: 1.46x faster                                        |
| django_template | 51.8 ms                                                      | 38.7 ms: 1.34x faster                                        |
| Geometric mean  | (ref)                                                        | 1.40x faster                                                 |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 |
|--------------------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| typing_runtime_protocols | 533 us                                                       | 150 us: 3.55x faster                                         |
| deltablue                | 7.43 ms                                                      | 3.24 ms: 2.29x faster                                        |
| asyncio_tcp              | 785 ms                                                       | 380 ms: 2.07x faster                                         |
| asyncio_tcp_ssl          | 3.13 sec                                                     | 1.57 sec: 1.99x faster                                       |
| richards_super           | 93.0 ms                                                      | 50.8 ms: 1.83x faster                                        |
| logging_silent           | 168 ns                                                       | 93.3 ns: 1.80x faster                                        |
| go                       | 258 ms                                                       | 149 ms: 1.73x faster                                         |
| scimark_sor              | 183 ms                                                       | 107 ms: 1.72x faster                                         |
| richards                 | 76.3 ms                                                      | 45.1 ms: 1.69x faster                                        |
| scimark_lu               | 165 ms                                                       | 98.6 ms: 1.67x faster                                        |
| chaos                    | 106 ms                                                       | 64.1 ms: 1.65x faster                                        |
| raytrace                 | 497 ms                                                       | 301 ms: 1.65x faster                                         |
| sqlglot_parse            | 2.27 ms                                                      | 1.41 ms: 1.61x faster                                        |
| hexiom                   | 9.46 ms                                                      | 5.97 ms: 1.58x faster                                        |
| pyflate                  | 698 ms                                                       | 442 ms: 1.58x faster                                         |
| scimark_monte_carlo      | 109 ms                                                       | 69.5 ms: 1.57x faster                                        |
| generators               | 57.7 ms                                                      | 37.3 ms: 1.55x faster                                        |
| async_tree_none          | 700 ms                                                       | 459 ms: 1.52x faster                                         |
| nbody                    | 134 ms                                                       | 88.2 ms: 1.52x faster                                        |
| async_tree_io            | 1.61 sec                                                     | 1.06 sec: 1.52x faster                                       |
| sqlglot_transpile        | 2.73 ms                                                      | 1.80 ms: 1.51x faster                                        |
| spectral_norm            | 141 ms                                                       | 93.9 ms: 1.50x faster                                        |
| unpickle_pure_python     | 315 us                                                       | 210 us: 1.50x faster                                         |
| async_tree_memoization   | 827 ms                                                       | 554 ms: 1.49x faster                                         |
| mako                     | 14.7 ms                                                      | 10.1 ms: 1.46x faster                                        |
| crypto_pyaes             | 118 ms                                                       | 82.4 ms: 1.43x faster                                        |
| pickle_pure_python       | 453 us                                                       | 319 us: 1.42x faster                                         |
| json_dumps               | 14.2 ms                                                      | 10.3 ms: 1.39x faster                                        |
| deepcopy_memo            | 50.5 us                                                      | 36.6 us: 1.38x faster                                        |
| bench_mp_pool            | 6.82 ms                                                      | 4.96 ms: 1.38x faster                                        |
| logging_simple           | 9.06 us                                                      | 6.64 us: 1.36x faster                                        |
| tomli_loads              | 2.96 sec                                                     | 2.17 sec: 1.36x faster                                       |
| chameleon                | 9.88 ms                                                      | 7.27 ms: 1.36x faster                                        |
| fannkuch                 | 488 ms                                                       | 362 ms: 1.35x faster                                         |
| logging_format           | 9.82 us                                                      | 7.29 us: 1.35x faster                                        |
| async_tree_cpu_io_mixed  | 946 ms                                                       | 704 ms: 1.34x faster                                         |
| coroutines               | 30.9 ms                                                      | 23.1 ms: 1.34x faster                                        |
| django_template          | 51.8 ms                                                      | 38.7 ms: 1.34x faster                                        |
| regex_compile            | 192 ms                                                       | 145 ms: 1.33x faster                                         |
| float                    | 109 ms                                                       | 81.6 ms: 1.33x faster                                        |
| xml_etree_process        | 76.4 ms                                                      | 58.3 ms: 1.31x faster                                        |
| pprint_pformat           | 2.15 sec                                                     | 1.64 sec: 1.31x faster                                       |
| pprint_safe_repr         | 1.04 sec                                                     | 808 ms: 1.29x faster                                         |
| tornado_http             | 157 ms                                                       | 122 ms: 1.28x faster                                         |
| mypy2                    | 467 ms                                                       | 365 ms: 1.28x faster                                         |
| pycparser                | 1.65 sec                                                     | 1.29 sec: 1.27x faster                                       |
| nqueens                  | 112 ms                                                       | 90.1 ms: 1.24x faster                                        |
| comprehensions           | 27.0 us                                                      | 21.8 us: 1.24x faster                                        |
| sqlalchemy_imperative    | 23.0 ms                                                      | 18.6 ms: 1.24x faster                                        |
| deepcopy                 | 459 us                                                       | 371 us: 1.24x faster                                         |
| json_loads               | 30.0 us                                                      | 24.3 us: 1.24x faster                                        |
| dulwich_log              | 80.0 ms                                                      | 64.9 ms: 1.23x faster                                        |
| 2to3                     | 349 ms                                                       | 285 ms: 1.23x faster                                         |
| sqlglot_normalize        | 146 ms                                                       | 119 ms: 1.23x faster                                         |
| sympy_expand             | 599 ms                                                       | 492 ms: 1.22x faster                                         |
| sqlglot_optimize         | 69.9 ms                                                      | 58.4 ms: 1.20x faster                                        |
| scimark_fft              | 363 ms                                                       | 303 ms: 1.20x faster                                         |
| gunicorn                 | 1.20 ms                                                      | 1.01 ms: 1.19x faster                                        |
| dask                     | 469 ms                                                       | 394 ms: 1.19x faster                                         |
| aiohttp                  | 1.21 ms                                                      | 1.02 ms: 1.19x faster                                        |
| sympy_sum                | 194 ms                                                       | 163 ms: 1.19x faster                                         |
| bench_thread_pool        | 1.13 ms                                                      | 956 us: 1.19x faster                                         |
| docutils                 | 3.42 sec                                                     | 2.89 sec: 1.18x faster                                       |
| sympy_integrate          | 28.3 ms                                                      | 24.0 ms: 1.18x faster                                        |
| sqlalchemy_declarative   | 189 ms                                                       | 161 ms: 1.18x faster                                         |
| sympy_str                | 359 ms                                                       | 305 ms: 1.18x faster                                         |
| deepcopy_reduce          | 4.00 us                                                      | 3.41 us: 1.17x faster                                        |
| scimark_sparse_mat_mult  | 5.21 ms                                                      | 4.49 ms: 1.16x faster                                        |
| mdp                      | 2.94 sec                                                     | 2.56 sec: 1.15x faster                                       |
| json                     | 5.91 ms                                                      | 5.17 ms: 1.14x faster                                        |
| create_gc_cycles         | 1.79 ms                                                      | 1.58 ms: 1.13x faster                                        |
| pathlib                  | 21.2 ms                                                      | 18.7 ms: 1.13x faster                                        |
| regex_v8                 | 27.1 ms                                                      | 24.4 ms: 1.11x faster                                        |
| unpack_sequence          | 60.3 ns                                                      | 54.5 ns: 1.11x faster                                        |
| sqlite_synth             | 2.97 us                                                      | 2.72 us: 1.09x faster                                        |
| xml_etree_generate       | 93.1 ms                                                      | 85.3 ms: 1.09x faster                                        |
| meteor_contest           | 138 ms                                                       | 126 ms: 1.09x faster                                         |
| async_generators         | 418 ms                                                       | 385 ms: 1.09x faster                                         |
| xml_etree_parse          | 159 ms                                                       | 147 ms: 1.09x faster                                         |
| regex_dna                | 260 ms                                                       | 240 ms: 1.08x faster                                         |
| xml_etree_iterparse      | 110 ms                                                       | 104 ms: 1.06x faster                                         |
| pidigits                 | 270 ms                                                       | 264 ms: 1.02x faster                                         |
| asyncio_websockets       | 394 ms                                                       | 386 ms: 1.02x faster                                         |
| telco                    | 7.21 ms                                                      | 7.16 ms: 1.01x faster                                        |
| pickle                   | 10.1 us                                                      | 10.0 us: 1.00x faster                                        |
| python_startup           | 11.5 ms                                                      | 11.7 ms: 1.01x slower                                        |
| gc_traversal             | 3.63 ms                                                      | 3.70 ms: 1.02x slower                                        |
| unpickle_list            | 4.45 us                                                      | 4.65 us: 1.05x slower                                        |
| pickle_dict              | 30.4 us                                                      | 32.0 us: 1.05x slower                                        |
| unpickle                 | 13.9 us                                                      | 15.3 us: 1.10x slower                                        |
| regex_effbot             | 3.10 ms                                                      | 3.61 ms: 1.17x slower                                        |
| python_startup_no_site   | 7.35 ms                                                      | 8.67 ms: 1.18x slower                                        |
| Geometric mean           | (ref)                                                        | 1.30x faster                                                 |

Benchmark hidden because not significant (2): pickle_list, coverage
Ignored benchmarks (6) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120.json: flaskblogging, genshi_text, genshi_xml, html5lib, pylint, thrift
Ignored benchmarks (4) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.24x
- 95% likely to have a speedup of 1.23x
- 99% likely to have a speedup of 1.21x
