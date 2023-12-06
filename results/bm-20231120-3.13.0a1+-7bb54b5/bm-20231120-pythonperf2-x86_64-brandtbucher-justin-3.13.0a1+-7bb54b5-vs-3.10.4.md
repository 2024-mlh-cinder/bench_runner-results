
# Results vs. 3.10.4

- fork: brandtbucher
- ref: justin
- machine: linux-x86_64
- commit hash: 7bb54b5
- commit date: 2023-11-20
- overall geometric mean: 1.25x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.18x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-pythonperf2-x86_64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|----------------|:------------------------------------------------------------:|:--------------------------------------------------------------------:|
| 2to3           | 349 ms                                                       | 302 ms: 1.16x faster                                                 |
| chameleon      | 9.88 ms                                                      | 7.53 ms: 1.31x faster                                                |
| docutils       | 3.42 sec                                                     | 2.87 sec: 1.19x faster                                               |
| tornado_http   | 157 ms                                                       | 122 ms: 1.29x faster                                                 |
| Geometric mean | (ref)                                                        | 1.23x faster                                                         |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-pythonperf2-x86_64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|-------------------------|:------------------------------------------------------------:|:--------------------------------------------------------------------:|
| async_tree_none         | 700 ms                                                       | 441 ms: 1.59x faster                                                 |
| async_tree_memoization  | 827 ms                                                       | 554 ms: 1.49x faster                                                 |
| async_tree_io           | 1.61 sec                                                     | 1.09 sec: 1.48x faster                                               |
| async_tree_cpu_io_mixed | 946 ms                                                       | 708 ms: 1.34x faster                                                 |
| Geometric mean          | (ref)                                                        | 1.47x faster                                                         |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-pythonperf2-x86_64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|----------------|:------------------------------------------------------------:|:--------------------------------------------------------------------:|
| nbody          | 134 ms                                                       | 94.4 ms: 1.42x faster                                                |
| float          | 109 ms                                                       | 81.0 ms: 1.34x faster                                                |
| pidigits       | 270 ms                                                       | 265 ms: 1.02x faster                                                 |
| Geometric mean | (ref)                                                        | 1.25x faster                                                         |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-pythonperf2-x86_64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|----------------|:------------------------------------------------------------:|:--------------------------------------------------------------------:|
| regex_compile  | 192 ms                                                       | 150 ms: 1.29x faster                                                 |
| regex_dna      | 260 ms                                                       | 240 ms: 1.09x faster                                                 |
| regex_v8       | 27.1 ms                                                      | 25.5 ms: 1.06x faster                                                |
| regex_effbot   | 3.10 ms                                                      | 3.57 ms: 1.15x slower                                                |
| Geometric mean | (ref)                                                        | 1.07x faster                                                         |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-pythonperf2-x86_64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|----------------------|:------------------------------------------------------------:|:--------------------------------------------------------------------:|
| pickle_pure_python   | 453 us                                                       | 316 us: 1.43x faster                                                 |
| unpickle_pure_python | 315 us                                                       | 227 us: 1.39x faster                                                 |
| json_dumps           | 14.2 ms                                                      | 10.8 ms: 1.32x faster                                                |
| tomli_loads          | 2.96 sec                                                     | 2.29 sec: 1.29x faster                                               |
| xml_etree_process    | 76.4 ms                                                      | 59.7 ms: 1.28x faster                                                |
| json_loads           | 30.0 us                                                      | 25.7 us: 1.17x faster                                                |
| xml_etree_parse      | 159 ms                                                       | 148 ms: 1.08x faster                                                 |
| xml_etree_generate   | 93.1 ms                                                      | 86.8 ms: 1.07x faster                                                |
| xml_etree_iterparse  | 110 ms                                                       | 106 ms: 1.03x faster                                                 |
| pickle               | 10.1 us                                                      | 9.99 us: 1.01x faster                                                |
| unpickle_list        | 4.45 us                                                      | 4.69 us: 1.06x slower                                                |
| unpickle             | 13.9 us                                                      | 14.9 us: 1.07x slower                                                |
| pickle_dict          | 30.4 us                                                      | 33.3 us: 1.09x slower                                                |
| Geometric mean       | (ref)                                                        | 1.12x faster                                                         |

Benchmark hidden because not significant (1): pickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-pythonperf2-x86_64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|------------------------|:------------------------------------------------------------:|:--------------------------------------------------------------------:|
| python_startup         | 11.5 ms                                                      | 12.9 ms: 1.12x slower                                                |
| python_startup_no_site | 7.35 ms                                                      | 11.4 ms: 1.55x slower                                                |
| Geometric mean         | (ref)                                                        | 1.32x slower                                                         |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-pythonperf2-x86_64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|-----------|:------------------------------------------------------------:|:--------------------------------------------------------------------:|
| mako      | 14.7 ms                                                      | 11.0 ms: 1.33x faster                                                |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-pythonperf2-x86_64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|--------------------------|:------------------------------------------------------------:|:--------------------------------------------------------------------:|
| typing_runtime_protocols | 533 us                                                       | 129 us: 4.12x faster                                                 |
| asyncio_tcp              | 785 ms                                                       | 366 ms: 2.14x faster                                                 |
| deltablue                | 7.43 ms                                                      | 3.71 ms: 2.00x faster                                                |
| asyncio_tcp_ssl          | 3.13 sec                                                     | 1.57 sec: 1.99x faster                                               |
| raytrace                 | 497 ms                                                       | 288 ms: 1.73x faster                                                 |
| logging_silent           | 168 ns                                                       | 99.0 ns: 1.69x faster                                                |
| richards_super           | 93.0 ms                                                      | 56.1 ms: 1.66x faster                                                |
| generators               | 57.7 ms                                                      | 36.0 ms: 1.60x faster                                                |
| scimark_lu               | 165 ms                                                       | 104 ms: 1.59x faster                                                 |
| sqlglot_parse            | 2.27 ms                                                      | 1.43 ms: 1.59x faster                                                |
| async_tree_none          | 700 ms                                                       | 441 ms: 1.59x faster                                                 |
| go                       | 258 ms                                                       | 168 ms: 1.53x faster                                                 |
| richards                 | 76.3 ms                                                      | 49.9 ms: 1.53x faster                                                |
| chaos                    | 106 ms                                                       | 70.3 ms: 1.51x faster                                                |
| async_tree_memoization   | 827 ms                                                       | 554 ms: 1.49x faster                                                 |
| async_tree_io            | 1.61 sec                                                     | 1.09 sec: 1.48x faster                                               |
| sqlglot_transpile        | 2.73 ms                                                      | 1.86 ms: 1.47x faster                                                |
| crypto_pyaes             | 118 ms                                                       | 81.3 ms: 1.45x faster                                                |
| pickle_pure_python       | 453 us                                                       | 316 us: 1.43x faster                                                 |
| bench_mp_pool            | 6.82 ms                                                      | 4.80 ms: 1.42x faster                                                |
| nbody                    | 134 ms                                                       | 94.4 ms: 1.42x faster                                                |
| scimark_monte_carlo      | 109 ms                                                       | 78.4 ms: 1.39x faster                                                |
| spectral_norm            | 141 ms                                                       | 101 ms: 1.39x faster                                                 |
| unpickle_pure_python     | 315 us                                                       | 227 us: 1.39x faster                                                 |
| logging_simple           | 9.06 us                                                      | 6.62 us: 1.37x faster                                                |
| coroutines               | 30.9 ms                                                      | 22.6 ms: 1.36x faster                                                |
| logging_format           | 9.82 us                                                      | 7.20 us: 1.36x faster                                                |
| deepcopy_memo            | 50.5 us                                                      | 37.1 us: 1.36x faster                                                |
| pyflate                  | 698 ms                                                       | 515 ms: 1.36x faster                                                 |
| float                    | 109 ms                                                       | 81.0 ms: 1.34x faster                                                |
| async_tree_cpu_io_mixed  | 946 ms                                                       | 708 ms: 1.34x faster                                                 |
| mako                     | 14.7 ms                                                      | 11.0 ms: 1.33x faster                                                |
| comprehensions           | 27.0 us                                                      | 20.3 us: 1.33x faster                                                |
| json_dumps               | 14.2 ms                                                      | 10.8 ms: 1.32x faster                                                |
| chameleon                | 9.88 ms                                                      | 7.53 ms: 1.31x faster                                                |
| tomli_loads              | 2.96 sec                                                     | 2.29 sec: 1.29x faster                                               |
| regex_compile            | 192 ms                                                       | 150 ms: 1.29x faster                                                 |
| tornado_http             | 157 ms                                                       | 122 ms: 1.29x faster                                                 |
| xml_etree_process        | 76.4 ms                                                      | 59.7 ms: 1.28x faster                                                |
| unpack_sequence          | 60.3 ns                                                      | 48.0 ns: 1.25x faster                                                |
| deepcopy                 | 459 us                                                       | 366 us: 1.25x faster                                                 |
| pycparser                | 1.65 sec                                                     | 1.33 sec: 1.24x faster                                               |
| scimark_sor              | 183 ms                                                       | 148 ms: 1.24x faster                                                 |
| pprint_pformat           | 2.15 sec                                                     | 1.74 sec: 1.24x faster                                               |
| mypy2                    | 467 ms                                                       | 380 ms: 1.23x faster                                                 |
| pprint_safe_repr         | 1.04 sec                                                     | 850 ms: 1.22x faster                                                 |
| sympy_sum                | 194 ms                                                       | 160 ms: 1.21x faster                                                 |
| hexiom                   | 9.46 ms                                                      | 7.82 ms: 1.21x faster                                                |
| deepcopy_reduce          | 4.00 us                                                      | 3.31 us: 1.21x faster                                                |
| sqlglot_normalize        | 146 ms                                                       | 122 ms: 1.20x faster                                                 |
| scimark_sparse_mat_mult  | 5.21 ms                                                      | 4.35 ms: 1.20x faster                                                |
| docutils                 | 3.42 sec                                                     | 2.87 sec: 1.19x faster                                               |
| sympy_str                | 359 ms                                                       | 302 ms: 1.19x faster                                                 |
| sympy_expand             | 599 ms                                                       | 506 ms: 1.18x faster                                                 |
| dulwich_log              | 80.0 ms                                                      | 67.7 ms: 1.18x faster                                                |
| fannkuch                 | 488 ms                                                       | 414 ms: 1.18x faster                                                 |
| json_loads               | 30.0 us                                                      | 25.7 us: 1.17x faster                                                |
| bench_thread_pool        | 1.13 ms                                                      | 972 us: 1.17x faster                                                 |
| sympy_integrate          | 28.3 ms                                                      | 24.4 ms: 1.16x faster                                                |
| dask                     | 469 ms                                                       | 404 ms: 1.16x faster                                                 |
| 2to3                     | 349 ms                                                       | 302 ms: 1.16x faster                                                 |
| sqlglot_optimize         | 69.9 ms                                                      | 61.7 ms: 1.13x faster                                                |
| create_gc_cycles         | 1.79 ms                                                      | 1.59 ms: 1.13x faster                                                |
| mdp                      | 2.94 sec                                                     | 2.61 sec: 1.13x faster                                               |
| json                     | 5.91 ms                                                      | 5.32 ms: 1.11x faster                                                |
| pathlib                  | 21.2 ms                                                      | 19.1 ms: 1.11x faster                                                |
| sqlite_synth             | 2.97 us                                                      | 2.72 us: 1.09x faster                                                |
| nqueens                  | 112 ms                                                       | 103 ms: 1.09x faster                                                 |
| regex_dna                | 260 ms                                                       | 240 ms: 1.09x faster                                                 |
| xml_etree_parse          | 159 ms                                                       | 148 ms: 1.08x faster                                                 |
| xml_etree_generate       | 93.1 ms                                                      | 86.8 ms: 1.07x faster                                                |
| regex_v8                 | 27.1 ms                                                      | 25.5 ms: 1.06x faster                                                |
| async_generators         | 418 ms                                                       | 395 ms: 1.06x faster                                                 |
| meteor_contest           | 138 ms                                                       | 132 ms: 1.05x faster                                                 |
| xml_etree_iterparse      | 110 ms                                                       | 106 ms: 1.03x faster                                                 |
| pidigits                 | 270 ms                                                       | 265 ms: 1.02x faster                                                 |
| asyncio_websockets       | 394 ms                                                       | 388 ms: 1.02x faster                                                 |
| pickle                   | 10.1 us                                                      | 9.99 us: 1.01x faster                                                |
| scimark_fft              | 363 ms                                                       | 375 ms: 1.04x slower                                                 |
| unpickle_list            | 4.45 us                                                      | 4.69 us: 1.06x slower                                                |
| unpickle                 | 13.9 us                                                      | 14.9 us: 1.07x slower                                                |
| gc_traversal             | 3.63 ms                                                      | 3.93 ms: 1.08x slower                                                |
| pickle_dict              | 30.4 us                                                      | 33.3 us: 1.09x slower                                                |
| python_startup           | 11.5 ms                                                      | 12.9 ms: 1.12x slower                                                |
| regex_effbot             | 3.10 ms                                                      | 3.57 ms: 1.15x slower                                                |
| telco                    | 7.21 ms                                                      | 8.36 ms: 1.16x slower                                                |
| coverage                 | 65.9 ms                                                      | 79.9 ms: 1.21x slower                                                |
| python_startup_no_site   | 7.35 ms                                                      | 11.4 ms: 1.55x slower                                                |
| Geometric mean           | (ref)                                                        | 1.25x faster                                                         |

Benchmark hidden because not significant (1): pickle_list
Ignored benchmarks (11) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
Ignored benchmarks (4) of results/bm-20231120-3.13.0a1+-7bb54b5/bm-20231120-pythonperf2-x86_64-brandtbucher-justin-3.13.0a1+-7bb54b5.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.20x
- 95% likely to have a speedup of 1.19x
- 99% likely to have a speedup of 1.18x
