
# Results vs. 3.10.4

- fork: faster-cpython
- ref: tier_2_exponential_b
- machine: linux-x86_64
- commit hash: 9c6f64f
- commit date: 2023-11-02
- overall geometric mean: 1.23x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.14x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231102-pythonperf2-x86_64-faster%2dcpython-tier_2_exponential_b-3.13.0a1+-9c6f64f |
|----------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------------------:|
| 2to3           | 349 ms                                                       | 307 ms: 1.14x faster                                                                   |
| chameleon      | 9.88 ms                                                      | 7.50 ms: 1.32x faster                                                                  |
| docutils       | 3.42 sec                                                     | 2.98 sec: 1.15x faster                                                                 |
| tornado_http   | 157 ms                                                       | 124 ms: 1.26x faster                                                                   |
| Geometric mean | (ref)                                                        | 1.21x faster                                                                           |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231102-pythonperf2-x86_64-faster%2dcpython-tier_2_exponential_b-3.13.0a1+-9c6f64f |
|-------------------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------------------:|
| async_tree_none         | 700 ms                                                       | 443 ms: 1.58x faster                                                                   |
| async_tree_memoization  | 827 ms                                                       | 559 ms: 1.48x faster                                                                   |
| async_tree_io           | 1.61 sec                                                     | 1.10 sec: 1.47x faster                                                                 |
| async_tree_cpu_io_mixed | 946 ms                                                       | 709 ms: 1.33x faster                                                                   |
| Geometric mean          | (ref)                                                        | 1.46x faster                                                                           |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231102-pythonperf2-x86_64-faster%2dcpython-tier_2_exponential_b-3.13.0a1+-9c6f64f |
|----------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------------------:|
| nbody          | 134 ms                                                       | 105 ms: 1.28x faster                                                                   |
| float          | 109 ms                                                       | 97.3 ms: 1.12x faster                                                                  |
| pidigits       | 270 ms                                                       | 265 ms: 1.02x faster                                                                   |
| Geometric mean | (ref)                                                        | 1.13x faster                                                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231102-pythonperf2-x86_64-faster%2dcpython-tier_2_exponential_b-3.13.0a1+-9c6f64f |
|----------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------------------:|
| regex_compile  | 192 ms                                                       | 170 ms: 1.13x faster                                                                   |
| regex_dna      | 260 ms                                                       | 241 ms: 1.08x faster                                                                   |
| regex_v8       | 27.1 ms                                                      | 25.7 ms: 1.05x faster                                                                  |
| regex_effbot   | 3.10 ms                                                      | 3.57 ms: 1.15x slower                                                                  |
| Geometric mean | (ref)                                                        | 1.03x faster                                                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231102-pythonperf2-x86_64-faster%2dcpython-tier_2_exponential_b-3.13.0a1+-9c6f64f |
|----------------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------------------:|
| pickle_pure_python   | 453 us                                                       | 315 us: 1.44x faster                                                                   |
| json_dumps           | 14.2 ms                                                      | 10.6 ms: 1.34x faster                                                                  |
| unpickle_pure_python | 315 us                                                       | 240 us: 1.31x faster                                                                   |
| xml_etree_process    | 76.4 ms                                                      | 59.0 ms: 1.29x faster                                                                  |
| json_loads           | 30.0 us                                                      | 24.1 us: 1.24x faster                                                                  |
| tomli_loads          | 2.96 sec                                                     | 2.66 sec: 1.11x faster                                                                 |
| xml_etree_parse      | 159 ms                                                       | 147 ms: 1.08x faster                                                                   |
| xml_etree_generate   | 93.1 ms                                                      | 87.4 ms: 1.07x faster                                                                  |
| pickle               | 10.1 us                                                      | 10.2 us: 1.01x slower                                                                  |
| pickle_list          | 4.23 us                                                      | 4.41 us: 1.04x slower                                                                  |
| unpickle_list        | 4.45 us                                                      | 4.64 us: 1.04x slower                                                                  |
| pickle_dict          | 30.4 us                                                      | 32.1 us: 1.05x slower                                                                  |
| unpickle             | 13.9 us                                                      | 15.0 us: 1.08x slower                                                                  |
| Geometric mean       | (ref)                                                        | 1.11x faster                                                                           |

Benchmark hidden because not significant (1): xml_etree_iterparse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231102-pythonperf2-x86_64-faster%2dcpython-tier_2_exponential_b-3.13.0a1+-9c6f64f |
|------------------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------------------:|
| python_startup         | 11.5 ms                                                      | 12.9 ms: 1.12x slower                                                                  |
| python_startup_no_site | 7.35 ms                                                      | 11.4 ms: 1.55x slower                                                                  |
| Geometric mean         | (ref)                                                        | 1.31x slower                                                                           |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231102-pythonperf2-x86_64-faster%2dcpython-tier_2_exponential_b-3.13.0a1+-9c6f64f |
|-----------|:------------------------------------------------------------:|:--------------------------------------------------------------------------------------:|
| mako      | 14.7 ms                                                      | 13.3 ms: 1.11x faster                                                                  |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231102-pythonperf2-x86_64-faster%2dcpython-tier_2_exponential_b-3.13.0a1+-9c6f64f |
|--------------------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------------------:|
| typing_runtime_protocols | 533 us                                                       | 131 us: 4.08x faster                                                                   |
| asyncio_tcp              | 785 ms                                                       | 370 ms: 2.12x faster                                                                   |
| asyncio_tcp_ssl          | 3.13 sec                                                     | 1.59 sec: 1.96x faster                                                                 |
| raytrace                 | 497 ms                                                       | 286 ms: 1.74x faster                                                                   |
| logging_silent           | 168 ns                                                       | 98.1 ns: 1.71x faster                                                                  |
| generators               | 57.7 ms                                                      | 35.6 ms: 1.62x faster                                                                  |
| richards_super           | 93.0 ms                                                      | 58.7 ms: 1.58x faster                                                                  |
| async_tree_none          | 700 ms                                                       | 443 ms: 1.58x faster                                                                   |
| crypto_pyaes             | 118 ms                                                       | 74.9 ms: 1.58x faster                                                                  |
| chaos                    | 106 ms                                                       | 67.3 ms: 1.58x faster                                                                  |
| scimark_lu               | 165 ms                                                       | 105 ms: 1.57x faster                                                                   |
| sqlglot_parse            | 2.27 ms                                                      | 1.45 ms: 1.56x faster                                                                  |
| spectral_norm            | 141 ms                                                       | 91.4 ms: 1.55x faster                                                                  |
| scimark_monte_carlo      | 109 ms                                                       | 71.0 ms: 1.54x faster                                                                  |
| deltablue                | 7.43 ms                                                      | 4.83 ms: 1.54x faster                                                                  |
| bench_mp_pool            | 6.82 ms                                                      | 4.58 ms: 1.49x faster                                                                  |
| async_tree_memoization   | 827 ms                                                       | 559 ms: 1.48x faster                                                                   |
| async_tree_io            | 1.61 sec                                                     | 1.10 sec: 1.47x faster                                                                 |
| sqlglot_transpile        | 2.73 ms                                                      | 1.87 ms: 1.46x faster                                                                  |
| richards                 | 76.3 ms                                                      | 52.5 ms: 1.45x faster                                                                  |
| go                       | 258 ms                                                       | 178 ms: 1.45x faster                                                                   |
| pickle_pure_python       | 453 us                                                       | 315 us: 1.44x faster                                                                   |
| logging_simple           | 9.06 us                                                      | 6.63 us: 1.37x faster                                                                  |
| coroutines               | 30.9 ms                                                      | 22.8 ms: 1.35x faster                                                                  |
| logging_format           | 9.82 us                                                      | 7.32 us: 1.34x faster                                                                  |
| json_dumps               | 14.2 ms                                                      | 10.6 ms: 1.34x faster                                                                  |
| async_tree_cpu_io_mixed  | 946 ms                                                       | 709 ms: 1.33x faster                                                                   |
| chameleon                | 9.88 ms                                                      | 7.50 ms: 1.32x faster                                                                  |
| unpickle_pure_python     | 315 us                                                       | 240 us: 1.31x faster                                                                   |
| xml_etree_process        | 76.4 ms                                                      | 59.0 ms: 1.29x faster                                                                  |
| nbody                    | 134 ms                                                       | 105 ms: 1.28x faster                                                                   |
| pyflate                  | 698 ms                                                       | 547 ms: 1.28x faster                                                                   |
| unpack_sequence          | 60.3 ns                                                      | 47.5 ns: 1.27x faster                                                                  |
| tornado_http             | 157 ms                                                       | 124 ms: 1.26x faster                                                                   |
| sqlglot_normalize        | 146 ms                                                       | 117 ms: 1.25x faster                                                                   |
| scimark_sor              | 183 ms                                                       | 147 ms: 1.25x faster                                                                   |
| json_loads               | 30.0 us                                                      | 24.1 us: 1.24x faster                                                                  |
| sympy_sum                | 194 ms                                                       | 158 ms: 1.23x faster                                                                   |
| deepcopy_reduce          | 4.00 us                                                      | 3.27 us: 1.22x faster                                                                  |
| mypy2                    | 467 ms                                                       | 382 ms: 1.22x faster                                                                   |
| deepcopy                 | 459 us                                                       | 377 us: 1.22x faster                                                                   |
| pycparser                | 1.65 sec                                                     | 1.36 sec: 1.21x faster                                                                 |
| deepcopy_memo            | 50.5 us                                                      | 41.7 us: 1.21x faster                                                                  |
| pprint_pformat           | 2.15 sec                                                     | 1.82 sec: 1.18x faster                                                                 |
| pprint_safe_repr         | 1.04 sec                                                     | 887 ms: 1.17x faster                                                                   |
| sympy_str                | 359 ms                                                       | 307 ms: 1.17x faster                                                                   |
| fannkuch                 | 488 ms                                                       | 418 ms: 1.17x faster                                                                   |
| bench_thread_pool        | 1.13 ms                                                      | 975 us: 1.16x faster                                                                   |
| sqlglot_optimize         | 69.9 ms                                                      | 60.3 ms: 1.16x faster                                                                  |
| sympy_integrate          | 28.3 ms                                                      | 24.6 ms: 1.15x faster                                                                  |
| sympy_expand             | 599 ms                                                       | 521 ms: 1.15x faster                                                                   |
| docutils                 | 3.42 sec                                                     | 2.98 sec: 1.15x faster                                                                 |
| comprehensions           | 27.0 us                                                      | 23.7 us: 1.14x faster                                                                  |
| 2to3                     | 349 ms                                                       | 307 ms: 1.14x faster                                                                   |
| dulwich_log              | 80.0 ms                                                      | 70.5 ms: 1.14x faster                                                                  |
| create_gc_cycles         | 1.79 ms                                                      | 1.58 ms: 1.13x faster                                                                  |
| regex_compile            | 192 ms                                                       | 170 ms: 1.13x faster                                                                   |
| json                     | 5.91 ms                                                      | 5.23 ms: 1.13x faster                                                                  |
| float                    | 109 ms                                                       | 97.3 ms: 1.12x faster                                                                  |
| tomli_loads              | 2.96 sec                                                     | 2.66 sec: 1.11x faster                                                                 |
| mako                     | 14.7 ms                                                      | 13.3 ms: 1.11x faster                                                                  |
| async_generators         | 418 ms                                                       | 378 ms: 1.11x faster                                                                   |
| sqlite_synth             | 2.97 us                                                      | 2.70 us: 1.10x faster                                                                  |
| mdp                      | 2.94 sec                                                     | 2.69 sec: 1.09x faster                                                                 |
| scimark_fft              | 363 ms                                                       | 332 ms: 1.09x faster                                                                   |
| xml_etree_parse          | 159 ms                                                       | 147 ms: 1.08x faster                                                                   |
| regex_dna                | 260 ms                                                       | 241 ms: 1.08x faster                                                                   |
| xml_etree_generate       | 93.1 ms                                                      | 87.4 ms: 1.07x faster                                                                  |
| pathlib                  | 21.2 ms                                                      | 20.0 ms: 1.06x faster                                                                  |
| regex_v8                 | 27.1 ms                                                      | 25.7 ms: 1.05x faster                                                                  |
| gc_traversal             | 3.63 ms                                                      | 3.49 ms: 1.04x faster                                                                  |
| nqueens                  | 112 ms                                                       | 108 ms: 1.04x faster                                                                   |
| hexiom                   | 9.46 ms                                                      | 9.13 ms: 1.04x faster                                                                  |
| scimark_sparse_mat_mult  | 5.21 ms                                                      | 5.06 ms: 1.03x faster                                                                  |
| asyncio_websockets       | 394 ms                                                       | 386 ms: 1.02x faster                                                                   |
| pidigits                 | 270 ms                                                       | 265 ms: 1.02x faster                                                                   |
| meteor_contest           | 138 ms                                                       | 135 ms: 1.02x faster                                                                   |
| pickle                   | 10.1 us                                                      | 10.2 us: 1.01x slower                                                                  |
| pickle_list              | 4.23 us                                                      | 4.41 us: 1.04x slower                                                                  |
| unpickle_list            | 4.45 us                                                      | 4.64 us: 1.04x slower                                                                  |
| pickle_dict              | 30.4 us                                                      | 32.1 us: 1.05x slower                                                                  |
| unpickle                 | 13.9 us                                                      | 15.0 us: 1.08x slower                                                                  |
| python_startup           | 11.5 ms                                                      | 12.9 ms: 1.12x slower                                                                  |
| telco                    | 7.21 ms                                                      | 8.25 ms: 1.14x slower                                                                  |
| regex_effbot             | 3.10 ms                                                      | 3.57 ms: 1.15x slower                                                                  |
| coverage                 | 65.9 ms                                                      | 86.2 ms: 1.31x slower                                                                  |
| python_startup_no_site   | 7.35 ms                                                      | 11.4 ms: 1.55x slower                                                                  |
| Geometric mean           | (ref)                                                        | 1.23x faster                                                                           |

Benchmark hidden because not significant (1): xml_etree_iterparse
Ignored benchmarks (12) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, dask, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
Ignored benchmarks (4) of results/bm-20231102-3.13.0a1+-9c6f64f/bm-20231102-pythonperf2-x86_64-faster%2dcpython-tier_2_exponential_b-3.13.0a1+-9c6f64f.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.16x
- 95% likely to have a speedup of 1.15x
- 99% likely to have a speedup of 1.14x
