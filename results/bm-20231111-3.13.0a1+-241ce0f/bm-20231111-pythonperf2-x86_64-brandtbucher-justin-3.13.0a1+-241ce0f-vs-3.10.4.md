
# Results vs. 3.10.4

- fork: brandtbucher
- ref: justin
- machine: linux-x86_64
- commit hash: 241ce0f
- commit date: 2023-11-11
- overall geometric mean: 1.26x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.18x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231111-pythonperf2-x86_64-brandtbucher-justin-3.13.0a1+-241ce0f |
|----------------|:------------------------------------------------------------:|:--------------------------------------------------------------------:|
| 2to3           | 349 ms                                                       | 300 ms: 1.16x faster                                                 |
| chameleon      | 9.88 ms                                                      | 7.65 ms: 1.29x faster                                                |
| docutils       | 3.42 sec                                                     | 2.87 sec: 1.19x faster                                               |
| tornado_http   | 157 ms                                                       | 120 ms: 1.30x faster                                                 |
| Geometric mean | (ref)                                                        | 1.23x faster                                                         |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231111-pythonperf2-x86_64-brandtbucher-justin-3.13.0a1+-241ce0f |
|-------------------------|:------------------------------------------------------------:|:--------------------------------------------------------------------:|
| async_tree_none         | 700 ms                                                       | 445 ms: 1.57x faster                                                 |
| async_tree_memoization  | 827 ms                                                       | 556 ms: 1.49x faster                                                 |
| async_tree_io           | 1.61 sec                                                     | 1.09 sec: 1.47x faster                                               |
| async_tree_cpu_io_mixed | 946 ms                                                       | 708 ms: 1.34x faster                                                 |
| Geometric mean          | (ref)                                                        | 1.46x faster                                                         |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231111-pythonperf2-x86_64-brandtbucher-justin-3.13.0a1+-241ce0f |
|----------------|:------------------------------------------------------------:|:--------------------------------------------------------------------:|
| nbody          | 134 ms                                                       | 98.3 ms: 1.37x faster                                                |
| float          | 109 ms                                                       | 82.7 ms: 1.31x faster                                                |
| pidigits       | 270 ms                                                       | 265 ms: 1.02x faster                                                 |
| Geometric mean | (ref)                                                        | 1.22x faster                                                         |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231111-pythonperf2-x86_64-brandtbucher-justin-3.13.0a1+-241ce0f |
|----------------|:------------------------------------------------------------:|:--------------------------------------------------------------------:|
| regex_compile  | 192 ms                                                       | 150 ms: 1.28x faster                                                 |
| regex_dna      | 260 ms                                                       | 237 ms: 1.10x faster                                                 |
| regex_v8       | 27.1 ms                                                      | 25.4 ms: 1.06x faster                                                |
| regex_effbot   | 3.10 ms                                                      | 3.51 ms: 1.13x slower                                                |
| Geometric mean | (ref)                                                        | 1.07x faster                                                         |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231111-pythonperf2-x86_64-brandtbucher-justin-3.13.0a1+-241ce0f |
|----------------------|:------------------------------------------------------------:|:--------------------------------------------------------------------:|
| pickle_pure_python   | 453 us                                                       | 309 us: 1.46x faster                                                 |
| unpickle_pure_python | 315 us                                                       | 222 us: 1.42x faster                                                 |
| json_dumps           | 14.2 ms                                                      | 10.4 ms: 1.37x faster                                                |
| xml_etree_process    | 76.4 ms                                                      | 59.2 ms: 1.29x faster                                                |
| json_loads           | 30.0 us                                                      | 24.4 us: 1.23x faster                                                |
| tomli_loads          | 2.96 sec                                                     | 2.43 sec: 1.22x faster                                               |
| xml_etree_parse      | 159 ms                                                       | 145 ms: 1.10x faster                                                 |
| xml_etree_generate   | 93.1 ms                                                      | 85.9 ms: 1.08x faster                                                |
| xml_etree_iterparse  | 110 ms                                                       | 104 ms: 1.05x faster                                                 |
| pickle               | 10.1 us                                                      | 10.3 us: 1.02x slower                                                |
| pickle_list          | 4.23 us                                                      | 4.42 us: 1.05x slower                                                |
| unpickle             | 13.9 us                                                      | 14.7 us: 1.06x slower                                                |
| pickle_dict          | 30.4 us                                                      | 32.7 us: 1.08x slower                                                |
| unpickle_list        | 4.45 us                                                      | 4.79 us: 1.08x slower                                                |
| Geometric mean       | (ref)                                                        | 1.13x faster                                                         |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231111-pythonperf2-x86_64-brandtbucher-justin-3.13.0a1+-241ce0f |
|------------------------|:------------------------------------------------------------:|:--------------------------------------------------------------------:|
| python_startup         | 11.5 ms                                                      | 12.9 ms: 1.12x slower                                                |
| python_startup_no_site | 7.35 ms                                                      | 11.4 ms: 1.55x slower                                                |
| Geometric mean         | (ref)                                                        | 1.31x slower                                                         |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231111-pythonperf2-x86_64-brandtbucher-justin-3.13.0a1+-241ce0f |
|-----------|:------------------------------------------------------------:|:--------------------------------------------------------------------:|
| mako      | 14.7 ms                                                      | 11.0 ms: 1.34x faster                                                |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231111-pythonperf2-x86_64-brandtbucher-justin-3.13.0a1+-241ce0f |
|--------------------------|:------------------------------------------------------------:|:--------------------------------------------------------------------:|
| typing_runtime_protocols | 533 us                                                       | 128 us: 4.17x faster                                                 |
| asyncio_tcp              | 785 ms                                                       | 368 ms: 2.13x faster                                                 |
| asyncio_tcp_ssl          | 3.13 sec                                                     | 1.58 sec: 1.98x faster                                               |
| deltablue                | 7.43 ms                                                      | 3.83 ms: 1.94x faster                                                |
| logging_silent           | 168 ns                                                       | 95.6 ns: 1.76x faster                                                |
| raytrace                 | 497 ms                                                       | 285 ms: 1.74x faster                                                 |
| generators               | 57.7 ms                                                      | 35.5 ms: 1.63x faster                                                |
| sqlglot_parse            | 2.27 ms                                                      | 1.41 ms: 1.61x faster                                                |
| richards_super           | 93.0 ms                                                      | 58.8 ms: 1.58x faster                                                |
| async_tree_none          | 700 ms                                                       | 445 ms: 1.57x faster                                                 |
| scimark_lu               | 165 ms                                                       | 105 ms: 1.57x faster                                                 |
| chaos                    | 106 ms                                                       | 68.0 ms: 1.56x faster                                                |
| spectral_norm            | 141 ms                                                       | 91.1 ms: 1.55x faster                                                |
| crypto_pyaes             | 118 ms                                                       | 78.5 ms: 1.50x faster                                                |
| richards                 | 76.3 ms                                                      | 50.9 ms: 1.50x faster                                                |
| sqlglot_transpile        | 2.73 ms                                                      | 1.83 ms: 1.49x faster                                                |
| async_tree_memoization   | 827 ms                                                       | 556 ms: 1.49x faster                                                 |
| go                       | 258 ms                                                       | 174 ms: 1.48x faster                                                 |
| async_tree_io            | 1.61 sec                                                     | 1.09 sec: 1.47x faster                                               |
| pickle_pure_python       | 453 us                                                       | 309 us: 1.46x faster                                                 |
| scimark_monte_carlo      | 109 ms                                                       | 75.2 ms: 1.45x faster                                                |
| unpickle_pure_python     | 315 us                                                       | 222 us: 1.42x faster                                                 |
| unpack_sequence          | 60.3 ns                                                      | 43.1 ns: 1.40x faster                                                |
| logging_simple           | 9.06 us                                                      | 6.56 us: 1.38x faster                                                |
| pyflate                  | 698 ms                                                       | 507 ms: 1.38x faster                                                 |
| json_dumps               | 14.2 ms                                                      | 10.4 ms: 1.37x faster                                                |
| nbody                    | 134 ms                                                       | 98.3 ms: 1.37x faster                                                |
| logging_format           | 9.82 us                                                      | 7.19 us: 1.36x faster                                                |
| coroutines               | 30.9 ms                                                      | 22.7 ms: 1.36x faster                                                |
| mako                     | 14.7 ms                                                      | 11.0 ms: 1.34x faster                                                |
| async_tree_cpu_io_mixed  | 946 ms                                                       | 708 ms: 1.34x faster                                                 |
| deepcopy_memo            | 50.5 us                                                      | 37.9 us: 1.33x faster                                                |
| float                    | 109 ms                                                       | 82.7 ms: 1.31x faster                                                |
| tornado_http             | 157 ms                                                       | 120 ms: 1.30x faster                                                 |
| chameleon                | 9.88 ms                                                      | 7.65 ms: 1.29x faster                                                |
| xml_etree_process        | 76.4 ms                                                      | 59.2 ms: 1.29x faster                                                |
| regex_compile            | 192 ms                                                       | 150 ms: 1.28x faster                                                 |
| pprint_pformat           | 2.15 sec                                                     | 1.70 sec: 1.27x faster                                               |
| sympy_sum                | 194 ms                                                       | 153 ms: 1.27x faster                                                 |
| deepcopy                 | 459 us                                                       | 367 us: 1.25x faster                                                 |
| pprint_safe_repr         | 1.04 sec                                                     | 832 ms: 1.25x faster                                                 |
| mypy2                    | 467 ms                                                       | 374 ms: 1.25x faster                                                 |
| pycparser                | 1.65 sec                                                     | 1.32 sec: 1.24x faster                                               |
| sqlglot_normalize        | 146 ms                                                       | 118 ms: 1.24x faster                                                 |
| comprehensions           | 27.0 us                                                      | 21.9 us: 1.24x faster                                                |
| json_loads               | 30.0 us                                                      | 24.4 us: 1.23x faster                                                |
| tomli_loads              | 2.96 sec                                                     | 2.43 sec: 1.22x faster                                               |
| sympy_str                | 359 ms                                                       | 294 ms: 1.22x faster                                                 |
| scimark_sor              | 183 ms                                                       | 150 ms: 1.22x faster                                                 |
| deepcopy_reduce          | 4.00 us                                                      | 3.30 us: 1.21x faster                                                |
| sympy_expand             | 599 ms                                                       | 498 ms: 1.20x faster                                                 |
| docutils                 | 3.42 sec                                                     | 2.87 sec: 1.19x faster                                               |
| sympy_integrate          | 28.3 ms                                                      | 23.9 ms: 1.19x faster                                                |
| sqlglot_optimize         | 69.9 ms                                                      | 59.1 ms: 1.18x faster                                                |
| dulwich_log              | 80.0 ms                                                      | 68.0 ms: 1.18x faster                                                |
| create_gc_cycles         | 1.79 ms                                                      | 1.53 ms: 1.17x faster                                                |
| 2to3                     | 349 ms                                                       | 300 ms: 1.16x faster                                                 |
| json                     | 5.91 ms                                                      | 5.08 ms: 1.16x faster                                                |
| bench_thread_pool        | 1.13 ms                                                      | 980 us: 1.16x faster                                                 |
| hexiom                   | 9.46 ms                                                      | 8.19 ms: 1.16x faster                                                |
| scimark_sparse_mat_mult  | 5.21 ms                                                      | 4.55 ms: 1.15x faster                                                |
| fannkuch                 | 488 ms                                                       | 428 ms: 1.14x faster                                                 |
| mdp                      | 2.94 sec                                                     | 2.61 sec: 1.12x faster                                               |
| sqlite_synth             | 2.97 us                                                      | 2.69 us: 1.10x faster                                                |
| bench_mp_pool            | 6.82 ms                                                      | 6.19 ms: 1.10x faster                                                |
| xml_etree_parse          | 159 ms                                                       | 145 ms: 1.10x faster                                                 |
| regex_dna                | 260 ms                                                       | 237 ms: 1.10x faster                                                 |
| xml_etree_generate       | 93.1 ms                                                      | 85.9 ms: 1.08x faster                                                |
| async_generators         | 418 ms                                                       | 389 ms: 1.07x faster                                                 |
| pathlib                  | 21.2 ms                                                      | 19.7 ms: 1.07x faster                                                |
| nqueens                  | 112 ms                                                       | 104 ms: 1.07x faster                                                 |
| regex_v8                 | 27.1 ms                                                      | 25.4 ms: 1.06x faster                                                |
| xml_etree_iterparse      | 110 ms                                                       | 104 ms: 1.05x faster                                                 |
| scimark_fft              | 363 ms                                                       | 348 ms: 1.04x faster                                                 |
| meteor_contest           | 138 ms                                                       | 133 ms: 1.03x faster                                                 |
| pidigits                 | 270 ms                                                       | 265 ms: 1.02x faster                                                 |
| asyncio_websockets       | 394 ms                                                       | 387 ms: 1.02x faster                                                 |
| pickle                   | 10.1 us                                                      | 10.3 us: 1.02x slower                                                |
| pickle_list              | 4.23 us                                                      | 4.42 us: 1.05x slower                                                |
| unpickle                 | 13.9 us                                                      | 14.7 us: 1.06x slower                                                |
| pickle_dict              | 30.4 us                                                      | 32.7 us: 1.08x slower                                                |
| unpickle_list            | 4.45 us                                                      | 4.79 us: 1.08x slower                                                |
| gc_traversal             | 3.63 ms                                                      | 3.91 ms: 1.08x slower                                                |
| python_startup           | 11.5 ms                                                      | 12.9 ms: 1.12x slower                                                |
| telco                    | 7.21 ms                                                      | 8.16 ms: 1.13x slower                                                |
| regex_effbot             | 3.10 ms                                                      | 3.51 ms: 1.13x slower                                                |
| coverage                 | 65.9 ms                                                      | 82.4 ms: 1.25x slower                                                |
| python_startup_no_site   | 7.35 ms                                                      | 11.4 ms: 1.55x slower                                                |
| Geometric mean           | (ref)                                                        | 1.26x faster                                                         |
Ignored benchmarks (12) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, dask, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
Ignored benchmarks (4) of results/bm-20231111-3.13.0a1+-241ce0f/bm-20231111-pythonperf2-x86_64-brandtbucher-justin-3.13.0a1+-241ce0f.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.22x
- 95% likely to have a speedup of 1.20x
- 99% likely to have a speedup of 1.18x
