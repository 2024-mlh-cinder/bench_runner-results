
# Results vs. 3.10.4

- fork: faster-cpython
- ref: tier_2_exponential_b
- machine: linux-x86_64
- commit hash: bf453f8
- commit date: 2023-11-02
- overall geometric mean: 1.22x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.13x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231102-pythonperf2-x86_64-faster%2dcpython-tier_2_exponential_b-3.13.0a1+-bf453f8 |
|----------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------------------:|
| 2to3           | 349 ms                                                       | 308 ms: 1.13x faster                                                                   |
| chameleon      | 9.88 ms                                                      | 7.72 ms: 1.28x faster                                                                  |
| docutils       | 3.42 sec                                                     | 2.95 sec: 1.16x faster                                                                 |
| tornado_http   | 157 ms                                                       | 123 ms: 1.28x faster                                                                   |
| Geometric mean | (ref)                                                        | 1.21x faster                                                                           |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231102-pythonperf2-x86_64-faster%2dcpython-tier_2_exponential_b-3.13.0a1+-bf453f8 |
|-------------------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------------------:|
| async_tree_none         | 700 ms                                                       | 450 ms: 1.56x faster                                                                   |
| async_tree_memoization  | 827 ms                                                       | 565 ms: 1.46x faster                                                                   |
| async_tree_io           | 1.61 sec                                                     | 1.10 sec: 1.46x faster                                                                 |
| async_tree_cpu_io_mixed | 946 ms                                                       | 720 ms: 1.31x faster                                                                   |
| Geometric mean          | (ref)                                                        | 1.45x faster                                                                           |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231102-pythonperf2-x86_64-faster%2dcpython-tier_2_exponential_b-3.13.0a1+-bf453f8 |
|----------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------------------:|
| nbody          | 134 ms                                                       | 115 ms: 1.17x faster                                                                   |
| float          | 109 ms                                                       | 103 ms: 1.05x faster                                                                   |
| pidigits       | 270 ms                                                       | 266 ms: 1.02x faster                                                                   |
| Geometric mean | (ref)                                                        | 1.08x faster                                                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231102-pythonperf2-x86_64-faster%2dcpython-tier_2_exponential_b-3.13.0a1+-bf453f8 |
|----------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------------------:|
| regex_compile  | 192 ms                                                       | 174 ms: 1.10x faster                                                                   |
| regex_dna      | 260 ms                                                       | 247 ms: 1.05x faster                                                                   |
| regex_v8       | 27.1 ms                                                      | 25.8 ms: 1.05x faster                                                                  |
| regex_effbot   | 3.10 ms                                                      | 3.48 ms: 1.12x slower                                                                  |
| Geometric mean | (ref)                                                        | 1.02x faster                                                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231102-pythonperf2-x86_64-faster%2dcpython-tier_2_exponential_b-3.13.0a1+-bf453f8 |
|----------------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------------------:|
| pickle_pure_python   | 453 us                                                       | 324 us: 1.40x faster                                                                   |
| json_dumps           | 14.2 ms                                                      | 10.5 ms: 1.35x faster                                                                  |
| unpickle_pure_python | 315 us                                                       | 243 us: 1.30x faster                                                                   |
| xml_etree_process    | 76.4 ms                                                      | 59.1 ms: 1.29x faster                                                                  |
| json_loads           | 30.0 us                                                      | 24.3 us: 1.23x faster                                                                  |
| xml_etree_generate   | 93.1 ms                                                      | 86.9 ms: 1.07x faster                                                                  |
| xml_etree_parse      | 159 ms                                                       | 152 ms: 1.05x faster                                                                   |
| tomli_loads          | 2.96 sec                                                     | 2.83 sec: 1.05x faster                                                                 |
| pickle               | 10.1 us                                                      | 10.0 us: 1.01x faster                                                                  |
| xml_etree_iterparse  | 110 ms                                                       | 113 ms: 1.03x slower                                                                   |
| pickle_dict          | 30.4 us                                                      | 31.8 us: 1.05x slower                                                                  |
| unpickle             | 13.9 us                                                      | 14.6 us: 1.05x slower                                                                  |
| unpickle_list        | 4.45 us                                                      | 4.75 us: 1.07x slower                                                                  |
| Geometric mean       | (ref)                                                        | 1.10x faster                                                                           |

Benchmark hidden because not significant (1): pickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231102-pythonperf2-x86_64-faster%2dcpython-tier_2_exponential_b-3.13.0a1+-bf453f8 |
|------------------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------------------:|
| python_startup         | 11.5 ms                                                      | 12.9 ms: 1.11x slower                                                                  |
| python_startup_no_site | 7.35 ms                                                      | 11.4 ms: 1.55x slower                                                                  |
| Geometric mean         | (ref)                                                        | 1.31x slower                                                                           |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231102-pythonperf2-x86_64-faster%2dcpython-tier_2_exponential_b-3.13.0a1+-bf453f8 |
|-----------|:------------------------------------------------------------:|:--------------------------------------------------------------------------------------:|
| mako      | 14.7 ms                                                      | 14.2 ms: 1.04x faster                                                                  |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231102-pythonperf2-x86_64-faster%2dcpython-tier_2_exponential_b-3.13.0a1+-bf453f8 |
|--------------------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------------------:|
| typing_runtime_protocols | 533 us                                                       | 132 us: 4.03x faster                                                                   |
| asyncio_tcp              | 785 ms                                                       | 373 ms: 2.10x faster                                                                   |
| asyncio_tcp_ssl          | 3.13 sec                                                     | 1.59 sec: 1.96x faster                                                                 |
| raytrace                 | 497 ms                                                       | 283 ms: 1.76x faster                                                                   |
| logging_silent           | 168 ns                                                       | 99.2 ns: 1.69x faster                                                                  |
| scimark_lu               | 165 ms                                                       | 104 ms: 1.58x faster                                                                   |
| sqlglot_parse            | 2.27 ms                                                      | 1.45 ms: 1.57x faster                                                                  |
| chaos                    | 106 ms                                                       | 67.8 ms: 1.56x faster                                                                  |
| generators               | 57.7 ms                                                      | 37.0 ms: 1.56x faster                                                                  |
| async_tree_none          | 700 ms                                                       | 450 ms: 1.56x faster                                                                   |
| crypto_pyaes             | 118 ms                                                       | 75.9 ms: 1.55x faster                                                                  |
| spectral_norm            | 141 ms                                                       | 91.1 ms: 1.55x faster                                                                  |
| richards_super           | 93.0 ms                                                      | 60.1 ms: 1.55x faster                                                                  |
| scimark_monte_carlo      | 109 ms                                                       | 71.8 ms: 1.52x faster                                                                  |
| bench_mp_pool            | 6.82 ms                                                      | 4.58 ms: 1.49x faster                                                                  |
| unpack_sequence          | 60.3 ns                                                      | 40.5 ns: 1.49x faster                                                                  |
| async_tree_memoization   | 827 ms                                                       | 565 ms: 1.46x faster                                                                   |
| sqlglot_transpile        | 2.73 ms                                                      | 1.87 ms: 1.46x faster                                                                  |
| async_tree_io            | 1.61 sec                                                     | 1.10 sec: 1.46x faster                                                                 |
| go                       | 258 ms                                                       | 179 ms: 1.44x faster                                                                   |
| richards                 | 76.3 ms                                                      | 53.6 ms: 1.42x faster                                                                  |
| pickle_pure_python       | 453 us                                                       | 324 us: 1.40x faster                                                                   |
| deltablue                | 7.43 ms                                                      | 5.32 ms: 1.40x faster                                                                  |
| coroutines               | 30.9 ms                                                      | 22.6 ms: 1.36x faster                                                                  |
| json_dumps               | 14.2 ms                                                      | 10.5 ms: 1.35x faster                                                                  |
| async_tree_cpu_io_mixed  | 946 ms                                                       | 720 ms: 1.31x faster                                                                   |
| logging_simple           | 9.06 us                                                      | 6.94 us: 1.31x faster                                                                  |
| pyflate                  | 698 ms                                                       | 538 ms: 1.30x faster                                                                   |
| unpickle_pure_python     | 315 us                                                       | 243 us: 1.30x faster                                                                   |
| xml_etree_process        | 76.4 ms                                                      | 59.1 ms: 1.29x faster                                                                  |
| logging_format           | 9.82 us                                                      | 7.62 us: 1.29x faster                                                                  |
| chameleon                | 9.88 ms                                                      | 7.72 ms: 1.28x faster                                                                  |
| tornado_http             | 157 ms                                                       | 123 ms: 1.28x faster                                                                   |
| pycparser                | 1.65 sec                                                     | 1.32 sec: 1.25x faster                                                                 |
| sqlglot_normalize        | 146 ms                                                       | 118 ms: 1.24x faster                                                                   |
| sympy_sum                | 194 ms                                                       | 157 ms: 1.24x faster                                                                   |
| json_loads               | 30.0 us                                                      | 24.3 us: 1.23x faster                                                                  |
| mypy2                    | 467 ms                                                       | 381 ms: 1.23x faster                                                                   |
| scimark_sor              | 183 ms                                                       | 150 ms: 1.23x faster                                                                   |
| deepcopy                 | 459 us                                                       | 380 us: 1.21x faster                                                                   |
| deepcopy_reduce          | 4.00 us                                                      | 3.32 us: 1.21x faster                                                                  |
| deepcopy_memo            | 50.5 us                                                      | 42.6 us: 1.19x faster                                                                  |
| pprint_pformat           | 2.15 sec                                                     | 1.82 sec: 1.18x faster                                                                 |
| sympy_str                | 359 ms                                                       | 306 ms: 1.17x faster                                                                   |
| fannkuch                 | 488 ms                                                       | 417 ms: 1.17x faster                                                                   |
| nbody                    | 134 ms                                                       | 115 ms: 1.17x faster                                                                   |
| sqlglot_optimize         | 69.9 ms                                                      | 60.0 ms: 1.16x faster                                                                  |
| pprint_safe_repr         | 1.04 sec                                                     | 895 ms: 1.16x faster                                                                   |
| docutils                 | 3.42 sec                                                     | 2.95 sec: 1.16x faster                                                                 |
| bench_thread_pool        | 1.13 ms                                                      | 985 us: 1.15x faster                                                                   |
| sympy_integrate          | 28.3 ms                                                      | 24.6 ms: 1.15x faster                                                                  |
| sympy_expand             | 599 ms                                                       | 521 ms: 1.15x faster                                                                   |
| dulwich_log              | 80.0 ms                                                      | 69.8 ms: 1.15x faster                                                                  |
| 2to3                     | 349 ms                                                       | 308 ms: 1.13x faster                                                                   |
| json                     | 5.91 ms                                                      | 5.24 ms: 1.13x faster                                                                  |
| regex_compile            | 192 ms                                                       | 174 ms: 1.10x faster                                                                   |
| async_generators         | 418 ms                                                       | 380 ms: 1.10x faster                                                                   |
| create_gc_cycles         | 1.79 ms                                                      | 1.63 ms: 1.10x faster                                                                  |
| mdp                      | 2.94 sec                                                     | 2.69 sec: 1.09x faster                                                                 |
| sqlite_synth             | 2.97 us                                                      | 2.74 us: 1.08x faster                                                                  |
| xml_etree_generate       | 93.1 ms                                                      | 86.9 ms: 1.07x faster                                                                  |
| comprehensions           | 27.0 us                                                      | 25.3 us: 1.07x faster                                                                  |
| scimark_fft              | 363 ms                                                       | 342 ms: 1.06x faster                                                                   |
| float                    | 109 ms                                                       | 103 ms: 1.05x faster                                                                   |
| regex_dna                | 260 ms                                                       | 247 ms: 1.05x faster                                                                   |
| xml_etree_parse          | 159 ms                                                       | 152 ms: 1.05x faster                                                                   |
| regex_v8                 | 27.1 ms                                                      | 25.8 ms: 1.05x faster                                                                  |
| pathlib                  | 21.2 ms                                                      | 20.2 ms: 1.05x faster                                                                  |
| tomli_loads              | 2.96 sec                                                     | 2.83 sec: 1.05x faster                                                                 |
| mako                     | 14.7 ms                                                      | 14.2 ms: 1.04x faster                                                                  |
| asyncio_websockets       | 394 ms                                                       | 386 ms: 1.02x faster                                                                   |
| pidigits                 | 270 ms                                                       | 266 ms: 1.02x faster                                                                   |
| nqueens                  | 112 ms                                                       | 111 ms: 1.01x faster                                                                   |
| pickle                   | 10.1 us                                                      | 10.0 us: 1.01x faster                                                                  |
| meteor_contest           | 138 ms                                                       | 137 ms: 1.00x faster                                                                   |
| scimark_sparse_mat_mult  | 5.21 ms                                                      | 5.27 ms: 1.01x slower                                                                  |
| xml_etree_iterparse      | 110 ms                                                       | 113 ms: 1.03x slower                                                                   |
| hexiom                   | 9.46 ms                                                      | 9.82 ms: 1.04x slower                                                                  |
| pickle_dict              | 30.4 us                                                      | 31.8 us: 1.05x slower                                                                  |
| unpickle                 | 13.9 us                                                      | 14.6 us: 1.05x slower                                                                  |
| unpickle_list            | 4.45 us                                                      | 4.75 us: 1.07x slower                                                                  |
| gc_traversal             | 3.63 ms                                                      | 3.95 ms: 1.09x slower                                                                  |
| python_startup           | 11.5 ms                                                      | 12.9 ms: 1.11x slower                                                                  |
| regex_effbot             | 3.10 ms                                                      | 3.48 ms: 1.12x slower                                                                  |
| telco                    | 7.21 ms                                                      | 8.23 ms: 1.14x slower                                                                  |
| coverage                 | 65.9 ms                                                      | 79.2 ms: 1.20x slower                                                                  |
| python_startup_no_site   | 7.35 ms                                                      | 11.4 ms: 1.55x slower                                                                  |
| Geometric mean           | (ref)                                                        | 1.22x faster                                                                           |

Benchmark hidden because not significant (1): pickle_list
Ignored benchmarks (12) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, dask, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
Ignored benchmarks (4) of results/bm-20231102-3.13.0a1+-bf453f8/bm-20231102-pythonperf2-x86_64-faster%2dcpython-tier_2_exponential_b-3.13.0a1+-bf453f8.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.15x
- 95% likely to have a speedup of 1.15x
- 99% likely to have a speedup of 1.13x
