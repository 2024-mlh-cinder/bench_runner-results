
# Results vs. 3.10.4

- fork: faster-cpython
- ref: tier_2_exponential_b
- machine: linux-x86_64
- commit hash: eda8b06
- commit date: 2023-11-01
- overall geometric mean: 1.22x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.13x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231101-pythonperf2-x86_64-faster%2dcpython-tier_2_exponential_b-3.13.0a1+-eda8b06 |
|----------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------------------:|
| 2to3           | 349 ms                                                       | 308 ms: 1.13x faster                                                                   |
| chameleon      | 9.88 ms                                                      | 7.43 ms: 1.33x faster                                                                  |
| docutils       | 3.42 sec                                                     | 2.94 sec: 1.16x faster                                                                 |
| tornado_http   | 157 ms                                                       | 123 ms: 1.27x faster                                                                   |
| Geometric mean | (ref)                                                        | 1.22x faster                                                                           |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231101-pythonperf2-x86_64-faster%2dcpython-tier_2_exponential_b-3.13.0a1+-eda8b06 |
|-------------------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------------------:|
| async_tree_none         | 700 ms                                                       | 447 ms: 1.57x faster                                                                   |
| async_tree_memoization  | 827 ms                                                       | 562 ms: 1.47x faster                                                                   |
| async_tree_io           | 1.61 sec                                                     | 1.10 sec: 1.47x faster                                                                 |
| async_tree_cpu_io_mixed | 946 ms                                                       | 712 ms: 1.33x faster                                                                   |
| Geometric mean          | (ref)                                                        | 1.46x faster                                                                           |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231101-pythonperf2-x86_64-faster%2dcpython-tier_2_exponential_b-3.13.0a1+-eda8b06 |
|----------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------------------:|
| nbody          | 134 ms                                                       | 110 ms: 1.22x faster                                                                   |
| float          | 109 ms                                                       | 103 ms: 1.05x faster                                                                   |
| pidigits       | 270 ms                                                       | 265 ms: 1.02x faster                                                                   |
| Geometric mean | (ref)                                                        | 1.09x faster                                                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231101-pythonperf2-x86_64-faster%2dcpython-tier_2_exponential_b-3.13.0a1+-eda8b06 |
|----------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------------------:|
| regex_v8       | 27.1 ms                                                      | 24.5 ms: 1.11x faster                                                                  |
| regex_compile  | 192 ms                                                       | 174 ms: 1.11x faster                                                                   |
| regex_dna      | 260 ms                                                       | 243 ms: 1.07x faster                                                                   |
| regex_effbot   | 3.10 ms                                                      | 3.47 ms: 1.12x slower                                                                  |
| Geometric mean | (ref)                                                        | 1.04x faster                                                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231101-pythonperf2-x86_64-faster%2dcpython-tier_2_exponential_b-3.13.0a1+-eda8b06 |
|----------------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------------------:|
| pickle_pure_python   | 453 us                                                       | 315 us: 1.43x faster                                                                   |
| json_dumps           | 14.2 ms                                                      | 10.6 ms: 1.34x faster                                                                  |
| xml_etree_process    | 76.4 ms                                                      | 58.9 ms: 1.30x faster                                                                  |
| unpickle_pure_python | 315 us                                                       | 248 us: 1.27x faster                                                                   |
| json_loads           | 30.0 us                                                      | 24.5 us: 1.23x faster                                                                  |
| xml_etree_generate   | 93.1 ms                                                      | 86.6 ms: 1.08x faster                                                                  |
| xml_etree_parse      | 159 ms                                                       | 149 ms: 1.07x faster                                                                   |
| tomli_loads          | 2.96 sec                                                     | 2.78 sec: 1.06x faster                                                                 |
| pickle               | 10.1 us                                                      | 9.98 us: 1.01x faster                                                                  |
| unpickle             | 13.9 us                                                      | 14.4 us: 1.03x slower                                                                  |
| unpickle_list        | 4.45 us                                                      | 4.61 us: 1.04x slower                                                                  |
| pickle_dict          | 30.4 us                                                      | 32.0 us: 1.05x slower                                                                  |
| Geometric mean       | (ref)                                                        | 1.11x faster                                                                           |

Benchmark hidden because not significant (2): pickle_list, xml_etree_iterparse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231101-pythonperf2-x86_64-faster%2dcpython-tier_2_exponential_b-3.13.0a1+-eda8b06 |
|------------------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------------------:|
| python_startup         | 11.5 ms                                                      | 12.9 ms: 1.11x slower                                                                  |
| python_startup_no_site | 7.35 ms                                                      | 11.4 ms: 1.55x slower                                                                  |
| Geometric mean         | (ref)                                                        | 1.31x slower                                                                           |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231101-pythonperf2-x86_64-faster%2dcpython-tier_2_exponential_b-3.13.0a1+-eda8b06 |
|-----------|:------------------------------------------------------------:|:--------------------------------------------------------------------------------------:|
| mako      | 14.7 ms                                                      | 14.3 ms: 1.03x faster                                                                  |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231101-pythonperf2-x86_64-faster%2dcpython-tier_2_exponential_b-3.13.0a1+-eda8b06 |
|--------------------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------------------:|
| typing_runtime_protocols | 533 us                                                       | 131 us: 4.06x faster                                                                   |
| asyncio_tcp              | 785 ms                                                       | 371 ms: 2.12x faster                                                                   |
| asyncio_tcp_ssl          | 3.13 sec                                                     | 1.60 sec: 1.96x faster                                                                 |
| logging_silent           | 168 ns                                                       | 98.5 ns: 1.70x faster                                                                  |
| raytrace                 | 497 ms                                                       | 303 ms: 1.64x faster                                                                   |
| generators               | 57.7 ms                                                      | 35.3 ms: 1.63x faster                                                                  |
| richards_super           | 93.0 ms                                                      | 59.1 ms: 1.57x faster                                                                  |
| async_tree_none          | 700 ms                                                       | 447 ms: 1.57x faster                                                                   |
| scimark_lu               | 165 ms                                                       | 106 ms: 1.55x faster                                                                   |
| sqlglot_parse            | 2.27 ms                                                      | 1.46 ms: 1.55x faster                                                                  |
| chaos                    | 106 ms                                                       | 68.4 ms: 1.55x faster                                                                  |
| spectral_norm            | 141 ms                                                       | 91.5 ms: 1.54x faster                                                                  |
| crypto_pyaes             | 118 ms                                                       | 77.2 ms: 1.53x faster                                                                  |
| bench_mp_pool            | 6.82 ms                                                      | 4.50 ms: 1.52x faster                                                                  |
| async_tree_memoization   | 827 ms                                                       | 562 ms: 1.47x faster                                                                   |
| async_tree_io            | 1.61 sec                                                     | 1.10 sec: 1.47x faster                                                                 |
| scimark_monte_carlo      | 109 ms                                                       | 75.3 ms: 1.45x faster                                                                  |
| sqlglot_transpile        | 2.73 ms                                                      | 1.88 ms: 1.45x faster                                                                  |
| richards                 | 76.3 ms                                                      | 53.2 ms: 1.44x faster                                                                  |
| pickle_pure_python       | 453 us                                                       | 315 us: 1.43x faster                                                                   |
| go                       | 258 ms                                                       | 182 ms: 1.42x faster                                                                   |
| deltablue                | 7.43 ms                                                      | 5.41 ms: 1.37x faster                                                                  |
| coroutines               | 30.9 ms                                                      | 22.7 ms: 1.36x faster                                                                  |
| json_dumps               | 14.2 ms                                                      | 10.6 ms: 1.34x faster                                                                  |
| logging_format           | 9.82 us                                                      | 7.35 us: 1.33x faster                                                                  |
| chameleon                | 9.88 ms                                                      | 7.43 ms: 1.33x faster                                                                  |
| async_tree_cpu_io_mixed  | 946 ms                                                       | 712 ms: 1.33x faster                                                                   |
| logging_simple           | 9.06 us                                                      | 6.86 us: 1.32x faster                                                                  |
| xml_etree_process        | 76.4 ms                                                      | 58.9 ms: 1.30x faster                                                                  |
| pyflate                  | 698 ms                                                       | 545 ms: 1.28x faster                                                                   |
| unpickle_pure_python     | 315 us                                                       | 248 us: 1.27x faster                                                                   |
| tornado_http             | 157 ms                                                       | 123 ms: 1.27x faster                                                                   |
| sqlglot_normalize        | 146 ms                                                       | 117 ms: 1.25x faster                                                                   |
| sympy_sum                | 194 ms                                                       | 157 ms: 1.23x faster                                                                   |
| json_loads               | 30.0 us                                                      | 24.5 us: 1.23x faster                                                                  |
| mypy2                    | 467 ms                                                       | 381 ms: 1.23x faster                                                                   |
| nbody                    | 134 ms                                                       | 110 ms: 1.22x faster                                                                   |
| deepcopy                 | 459 us                                                       | 379 us: 1.21x faster                                                                   |
| pycparser                | 1.65 sec                                                     | 1.37 sec: 1.20x faster                                                                 |
| scimark_sor              | 183 ms                                                       | 152 ms: 1.20x faster                                                                   |
| deepcopy_memo            | 50.5 us                                                      | 42.4 us: 1.19x faster                                                                  |
| unpack_sequence          | 60.3 ns                                                      | 50.7 ns: 1.19x faster                                                                  |
| deepcopy_reduce          | 4.00 us                                                      | 3.37 us: 1.19x faster                                                                  |
| sympy_str                | 359 ms                                                       | 306 ms: 1.17x faster                                                                   |
| sqlglot_optimize         | 69.9 ms                                                      | 59.9 ms: 1.17x faster                                                                  |
| docutils                 | 3.42 sec                                                     | 2.94 sec: 1.16x faster                                                                 |
| pprint_pformat           | 2.15 sec                                                     | 1.86 sec: 1.16x faster                                                                 |
| sympy_expand             | 599 ms                                                       | 519 ms: 1.15x faster                                                                   |
| bench_thread_pool        | 1.13 ms                                                      | 985 us: 1.15x faster                                                                   |
| fannkuch                 | 488 ms                                                       | 425 ms: 1.15x faster                                                                   |
| sympy_integrate          | 28.3 ms                                                      | 24.6 ms: 1.15x faster                                                                  |
| pprint_safe_repr         | 1.04 sec                                                     | 906 ms: 1.15x faster                                                                   |
| json                     | 5.91 ms                                                      | 5.20 ms: 1.14x faster                                                                  |
| 2to3                     | 349 ms                                                       | 308 ms: 1.13x faster                                                                   |
| dulwich_log              | 80.0 ms                                                      | 70.5 ms: 1.13x faster                                                                  |
| create_gc_cycles         | 1.79 ms                                                      | 1.60 ms: 1.12x faster                                                                  |
| mdp                      | 2.94 sec                                                     | 2.64 sec: 1.11x faster                                                                 |
| regex_v8                 | 27.1 ms                                                      | 24.5 ms: 1.11x faster                                                                  |
| regex_compile            | 192 ms                                                       | 174 ms: 1.11x faster                                                                   |
| sqlite_synth             | 2.97 us                                                      | 2.70 us: 1.10x faster                                                                  |
| async_generators         | 418 ms                                                       | 383 ms: 1.09x faster                                                                   |
| xml_etree_generate       | 93.1 ms                                                      | 86.6 ms: 1.08x faster                                                                  |
| regex_dna                | 260 ms                                                       | 243 ms: 1.07x faster                                                                   |
| xml_etree_parse          | 159 ms                                                       | 149 ms: 1.07x faster                                                                   |
| tomli_loads              | 2.96 sec                                                     | 2.78 sec: 1.06x faster                                                                 |
| scimark_fft              | 363 ms                                                       | 343 ms: 1.06x faster                                                                   |
| float                    | 109 ms                                                       | 103 ms: 1.05x faster                                                                   |
| pathlib                  | 21.2 ms                                                      | 20.2 ms: 1.05x faster                                                                  |
| comprehensions           | 27.0 us                                                      | 26.1 us: 1.04x faster                                                                  |
| mako                     | 14.7 ms                                                      | 14.3 ms: 1.03x faster                                                                  |
| pidigits                 | 270 ms                                                       | 265 ms: 1.02x faster                                                                   |
| asyncio_websockets       | 394 ms                                                       | 387 ms: 1.02x faster                                                                   |
| meteor_contest           | 138 ms                                                       | 136 ms: 1.01x faster                                                                   |
| pickle                   | 10.1 us                                                      | 9.98 us: 1.01x faster                                                                  |
| scimark_sparse_mat_mult  | 5.21 ms                                                      | 5.30 ms: 1.02x slower                                                                  |
| gc_traversal             | 3.63 ms                                                      | 3.74 ms: 1.03x slower                                                                  |
| unpickle                 | 13.9 us                                                      | 14.4 us: 1.03x slower                                                                  |
| unpickle_list            | 4.45 us                                                      | 4.61 us: 1.04x slower                                                                  |
| pickle_dict              | 30.4 us                                                      | 32.0 us: 1.05x slower                                                                  |
| hexiom                   | 9.46 ms                                                      | 9.99 ms: 1.06x slower                                                                  |
| python_startup           | 11.5 ms                                                      | 12.9 ms: 1.11x slower                                                                  |
| regex_effbot             | 3.10 ms                                                      | 3.47 ms: 1.12x slower                                                                  |
| telco                    | 7.21 ms                                                      | 8.15 ms: 1.13x slower                                                                  |
| coverage                 | 65.9 ms                                                      | 80.2 ms: 1.22x slower                                                                  |
| python_startup_no_site   | 7.35 ms                                                      | 11.4 ms: 1.55x slower                                                                  |
| Geometric mean           | (ref)                                                        | 1.22x faster                                                                           |

Benchmark hidden because not significant (3): pickle_list, nqueens, xml_etree_iterparse
Ignored benchmarks (12) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, dask, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
Ignored benchmarks (4) of results/bm-20231101-3.13.0a1+-eda8b06/bm-20231101-pythonperf2-x86_64-faster%2dcpython-tier_2_exponential_b-3.13.0a1+-eda8b06.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.15x
- 95% likely to have a speedup of 1.14x
- 99% likely to have a speedup of 1.13x
