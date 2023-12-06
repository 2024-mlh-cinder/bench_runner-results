
# Results vs. 3.10.4

- fork: faster-cpython
- ref: likelihood_on_trace
- machine: linux-x86_64
- commit hash: 55d5c8d
- commit date: 2023-11-16
- overall geometric mean: 1.19x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.12x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231116-pythonperf2-x86_64-faster%2dcpython-likelihood_on_trace-3.13.0a1+-55d5c8d |
|----------------|:------------------------------------------------------------:|:-------------------------------------------------------------------------------------:|
| 2to3           | 349 ms                                                       | 315 ms: 1.11x faster                                                                  |
| chameleon      | 9.88 ms                                                      | 7.98 ms: 1.24x faster                                                                 |
| docutils       | 3.42 sec                                                     | 2.94 sec: 1.16x faster                                                                |
| tornado_http   | 157 ms                                                       | 124 ms: 1.26x faster                                                                  |
| Geometric mean | (ref)                                                        | 1.19x faster                                                                          |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231116-pythonperf2-x86_64-faster%2dcpython-likelihood_on_trace-3.13.0a1+-55d5c8d |
|-------------------------|:------------------------------------------------------------:|:-------------------------------------------------------------------------------------:|
| async_tree_none         | 700 ms                                                       | 450 ms: 1.55x faster                                                                  |
| async_tree_memoization  | 827 ms                                                       | 563 ms: 1.47x faster                                                                  |
| async_tree_io           | 1.61 sec                                                     | 1.10 sec: 1.46x faster                                                                |
| async_tree_cpu_io_mixed | 946 ms                                                       | 715 ms: 1.32x faster                                                                  |
| Geometric mean          | (ref)                                                        | 1.45x faster                                                                          |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231116-pythonperf2-x86_64-faster%2dcpython-likelihood_on_trace-3.13.0a1+-55d5c8d |
|----------------|:------------------------------------------------------------:|:-------------------------------------------------------------------------------------:|
| nbody          | 134 ms                                                       | 115 ms: 1.16x faster                                                                  |
| float          | 109 ms                                                       | 105 ms: 1.03x faster                                                                  |
| pidigits       | 270 ms                                                       | 267 ms: 1.01x faster                                                                  |
| Geometric mean | (ref)                                                        | 1.07x faster                                                                          |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231116-pythonperf2-x86_64-faster%2dcpython-likelihood_on_trace-3.13.0a1+-55d5c8d |
|----------------|:------------------------------------------------------------:|:-------------------------------------------------------------------------------------:|
| regex_compile  | 192 ms                                                       | 176 ms: 1.10x faster                                                                  |
| regex_dna      | 260 ms                                                       | 244 ms: 1.07x faster                                                                  |
| regex_v8       | 27.1 ms                                                      | 26.2 ms: 1.03x faster                                                                 |
| regex_effbot   | 3.10 ms                                                      | 3.52 ms: 1.14x slower                                                                 |
| Geometric mean | (ref)                                                        | 1.02x faster                                                                          |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231116-pythonperf2-x86_64-faster%2dcpython-likelihood_on_trace-3.13.0a1+-55d5c8d |
|----------------------|:------------------------------------------------------------:|:-------------------------------------------------------------------------------------:|
| pickle_pure_python   | 453 us                                                       | 314 us: 1.44x faster                                                                  |
| json_dumps           | 14.2 ms                                                      | 10.6 ms: 1.34x faster                                                                 |
| xml_etree_process    | 76.4 ms                                                      | 58.3 ms: 1.31x faster                                                                 |
| unpickle_pure_python | 315 us                                                       | 254 us: 1.24x faster                                                                  |
| json_loads           | 30.0 us                                                      | 25.2 us: 1.19x faster                                                                 |
| xml_etree_parse      | 159 ms                                                       | 148 ms: 1.08x faster                                                                  |
| xml_etree_generate   | 93.1 ms                                                      | 87.0 ms: 1.07x faster                                                                 |
| pickle               | 10.1 us                                                      | 10.3 us: 1.02x slower                                                                 |
| tomli_loads          | 2.96 sec                                                     | 3.02 sec: 1.02x slower                                                                |
| xml_etree_iterparse  | 110 ms                                                       | 114 ms: 1.04x slower                                                                  |
| pickle_dict          | 30.4 us                                                      | 31.7 us: 1.04x slower                                                                 |
| unpickle             | 13.9 us                                                      | 14.6 us: 1.05x slower                                                                 |
| unpickle_list        | 4.45 us                                                      | 4.74 us: 1.07x slower                                                                 |
| pickle_list          | 4.23 us                                                      | 4.53 us: 1.07x slower                                                                 |
| Geometric mean       | (ref)                                                        | 1.09x faster                                                                          |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231116-pythonperf2-x86_64-faster%2dcpython-likelihood_on_trace-3.13.0a1+-55d5c8d |
|------------------------|:------------------------------------------------------------:|:-------------------------------------------------------------------------------------:|
| python_startup         | 11.5 ms                                                      | 12.9 ms: 1.12x slower                                                                 |
| python_startup_no_site | 7.35 ms                                                      | 11.4 ms: 1.55x slower                                                                 |
| Geometric mean         | (ref)                                                        | 1.32x slower                                                                          |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231116-pythonperf2-x86_64-faster%2dcpython-likelihood_on_trace-3.13.0a1+-55d5c8d |
|-----------|:------------------------------------------------------------:|:-------------------------------------------------------------------------------------:|
| mako      | 14.7 ms                                                      | 15.9 ms: 1.08x slower                                                                 |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231116-pythonperf2-x86_64-faster%2dcpython-likelihood_on_trace-3.13.0a1+-55d5c8d |
|--------------------------|:------------------------------------------------------------:|:-------------------------------------------------------------------------------------:|
| typing_runtime_protocols | 533 us                                                       | 138 us: 3.88x faster                                                                  |
| asyncio_tcp              | 785 ms                                                       | 373 ms: 2.10x faster                                                                  |
| asyncio_tcp_ssl          | 3.13 sec                                                     | 1.60 sec: 1.96x faster                                                                |
| raytrace                 | 497 ms                                                       | 287 ms: 1.73x faster                                                                  |
| logging_silent           | 168 ns                                                       | 100 ns: 1.68x faster                                                                  |
| generators               | 57.7 ms                                                      | 34.6 ms: 1.67x faster                                                                 |
| async_tree_none          | 700 ms                                                       | 450 ms: 1.55x faster                                                                  |
| spectral_norm            | 141 ms                                                       | 91.0 ms: 1.55x faster                                                                 |
| deltablue                | 7.43 ms                                                      | 4.78 ms: 1.55x faster                                                                 |
| sqlglot_parse            | 2.27 ms                                                      | 1.47 ms: 1.55x faster                                                                 |
| scimark_lu               | 165 ms                                                       | 107 ms: 1.53x faster                                                                  |
| richards_super           | 93.0 ms                                                      | 60.8 ms: 1.53x faster                                                                 |
| async_tree_memoization   | 827 ms                                                       | 563 ms: 1.47x faster                                                                  |
| chaos                    | 106 ms                                                       | 72.2 ms: 1.47x faster                                                                 |
| async_tree_io            | 1.61 sec                                                     | 1.10 sec: 1.46x faster                                                                |
| bench_mp_pool            | 6.82 ms                                                      | 4.70 ms: 1.45x faster                                                                 |
| sqlglot_transpile        | 2.73 ms                                                      | 1.88 ms: 1.45x faster                                                                 |
| pickle_pure_python       | 453 us                                                       | 314 us: 1.44x faster                                                                  |
| richards                 | 76.3 ms                                                      | 54.2 ms: 1.41x faster                                                                 |
| coroutines               | 30.9 ms                                                      | 22.1 ms: 1.39x faster                                                                 |
| go                       | 258 ms                                                       | 185 ms: 1.39x faster                                                                  |
| logging_simple           | 9.06 us                                                      | 6.69 us: 1.36x faster                                                                 |
| crypto_pyaes             | 118 ms                                                       | 87.3 ms: 1.35x faster                                                                 |
| json_dumps               | 14.2 ms                                                      | 10.6 ms: 1.34x faster                                                                 |
| logging_format           | 9.82 us                                                      | 7.39 us: 1.33x faster                                                                 |
| scimark_monte_carlo      | 109 ms                                                       | 82.4 ms: 1.33x faster                                                                 |
| async_tree_cpu_io_mixed  | 946 ms                                                       | 715 ms: 1.32x faster                                                                  |
| xml_etree_process        | 76.4 ms                                                      | 58.3 ms: 1.31x faster                                                                 |
| tornado_http             | 157 ms                                                       | 124 ms: 1.26x faster                                                                  |
| sqlglot_normalize        | 146 ms                                                       | 117 ms: 1.25x faster                                                                  |
| unpickle_pure_python     | 315 us                                                       | 254 us: 1.24x faster                                                                  |
| chameleon                | 9.88 ms                                                      | 7.98 ms: 1.24x faster                                                                 |
| mypy2                    | 467 ms                                                       | 380 ms: 1.23x faster                                                                  |
| sympy_sum                | 194 ms                                                       | 157 ms: 1.23x faster                                                                  |
| deepcopy                 | 459 us                                                       | 376 us: 1.22x faster                                                                  |
| scimark_sor              | 183 ms                                                       | 150 ms: 1.22x faster                                                                  |
| pyflate                  | 698 ms                                                       | 575 ms: 1.21x faster                                                                  |
| pycparser                | 1.65 sec                                                     | 1.36 sec: 1.21x faster                                                                |
| deepcopy_reduce          | 4.00 us                                                      | 3.30 us: 1.21x faster                                                                 |
| deepcopy_memo            | 50.5 us                                                      | 42.3 us: 1.19x faster                                                                 |
| json_loads               | 30.0 us                                                      | 25.2 us: 1.19x faster                                                                 |
| pprint_pformat           | 2.15 sec                                                     | 1.82 sec: 1.18x faster                                                                |
| sqlglot_optimize         | 69.9 ms                                                      | 59.7 ms: 1.17x faster                                                                 |
| pprint_safe_repr         | 1.04 sec                                                     | 891 ms: 1.17x faster                                                                  |
| nbody                    | 134 ms                                                       | 115 ms: 1.16x faster                                                                  |
| docutils                 | 3.42 sec                                                     | 2.94 sec: 1.16x faster                                                                |
| unpack_sequence          | 60.3 ns                                                      | 52.0 ns: 1.16x faster                                                                 |
| sympy_str                | 359 ms                                                       | 310 ms: 1.16x faster                                                                  |
| bench_thread_pool        | 1.13 ms                                                      | 984 us: 1.15x faster                                                                  |
| dask                     | 469 ms                                                       | 407 ms: 1.15x faster                                                                  |
| create_gc_cycles         | 1.79 ms                                                      | 1.56 ms: 1.14x faster                                                                 |
| json                     | 5.91 ms                                                      | 5.20 ms: 1.14x faster                                                                 |
| sympy_expand             | 599 ms                                                       | 527 ms: 1.14x faster                                                                  |
| sympy_integrate          | 28.3 ms                                                      | 25.1 ms: 1.13x faster                                                                 |
| dulwich_log              | 80.0 ms                                                      | 71.4 ms: 1.12x faster                                                                 |
| 2to3                     | 349 ms                                                       | 315 ms: 1.11x faster                                                                  |
| async_generators         | 418 ms                                                       | 380 ms: 1.10x faster                                                                  |
| regex_compile            | 192 ms                                                       | 176 ms: 1.10x faster                                                                  |
| mdp                      | 2.94 sec                                                     | 2.71 sec: 1.08x faster                                                                |
| pathlib                  | 21.2 ms                                                      | 19.6 ms: 1.08x faster                                                                 |
| xml_etree_parse          | 159 ms                                                       | 148 ms: 1.08x faster                                                                  |
| xml_etree_generate       | 93.1 ms                                                      | 87.0 ms: 1.07x faster                                                                 |
| sqlite_synth             | 2.97 us                                                      | 2.78 us: 1.07x faster                                                                 |
| regex_dna                | 260 ms                                                       | 244 ms: 1.07x faster                                                                  |
| gc_traversal             | 3.63 ms                                                      | 3.47 ms: 1.05x faster                                                                 |
| regex_v8                 | 27.1 ms                                                      | 26.2 ms: 1.03x faster                                                                 |
| float                    | 109 ms                                                       | 105 ms: 1.03x faster                                                                  |
| asyncio_websockets       | 394 ms                                                       | 386 ms: 1.02x faster                                                                  |
| pidigits                 | 270 ms                                                       | 267 ms: 1.01x faster                                                                  |
| meteor_contest           | 138 ms                                                       | 138 ms: 1.00x slower                                                                  |
| pickle                   | 10.1 us                                                      | 10.3 us: 1.02x slower                                                                 |
| tomli_loads              | 2.96 sec                                                     | 3.02 sec: 1.02x slower                                                                |
| xml_etree_iterparse      | 110 ms                                                       | 114 ms: 1.04x slower                                                                  |
| pickle_dict              | 30.4 us                                                      | 31.7 us: 1.04x slower                                                                 |
| unpickle                 | 13.9 us                                                      | 14.6 us: 1.05x slower                                                                 |
| nqueens                  | 112 ms                                                       | 118 ms: 1.05x slower                                                                  |
| unpickle_list            | 4.45 us                                                      | 4.74 us: 1.07x slower                                                                 |
| pickle_list              | 4.23 us                                                      | 4.53 us: 1.07x slower                                                                 |
| fannkuch                 | 488 ms                                                       | 526 ms: 1.08x slower                                                                  |
| mako                     | 14.7 ms                                                      | 15.9 ms: 1.08x slower                                                                 |
| comprehensions           | 27.0 us                                                      | 29.6 us: 1.09x slower                                                                 |
| scimark_fft              | 363 ms                                                       | 401 ms: 1.11x slower                                                                  |
| python_startup           | 11.5 ms                                                      | 12.9 ms: 1.12x slower                                                                 |
| regex_effbot             | 3.10 ms                                                      | 3.52 ms: 1.14x slower                                                                 |
| hexiom                   | 9.46 ms                                                      | 11.0 ms: 1.17x slower                                                                 |
| telco                    | 7.21 ms                                                      | 8.53 ms: 1.18x slower                                                                 |
| coverage                 | 65.9 ms                                                      | 79.8 ms: 1.21x slower                                                                 |
| scimark_sparse_mat_mult  | 5.21 ms                                                      | 7.23 ms: 1.39x slower                                                                 |
| python_startup_no_site   | 7.35 ms                                                      | 11.4 ms: 1.55x slower                                                                 |
| Geometric mean           | (ref)                                                        | 1.19x faster                                                                          |
Ignored benchmarks (11) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
Ignored benchmarks (4) of results/bm-20231116-3.13.0a1+-55d5c8d-PYTHON_UOPS/bm-20231116-pythonperf2-x86_64-faster%2dcpython-likelihood_on_trace-3.13.0a1+-55d5c8d.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.15x
- 95% likely to have a speedup of 1.14x
- 99% likely to have a speedup of 1.12x
