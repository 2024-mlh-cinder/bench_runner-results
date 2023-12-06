
# Results vs. 3.10.4

- fork: python
- ref: fa84e5fe0a3bd8e77c33
- machine: linux-x86_64
- commit hash: fa84e5f
- commit date: 2023-11-11
- overall geometric mean: 1.29x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.22x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231111-pythonperf2-x86_64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| 2to3           | 349 ms                                                       | 292 ms: 1.19x faster                                                         |
| chameleon      | 9.88 ms                                                      | 7.22 ms: 1.37x faster                                                        |
| docutils       | 3.42 sec                                                     | 2.84 sec: 1.20x faster                                                       |
| tornado_http   | 157 ms                                                       | 119 ms: 1.32x faster                                                         |
| Geometric mean | (ref)                                                        | 1.27x faster                                                                 |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231111-pythonperf2-x86_64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f |
|-------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| async_tree_none         | 700 ms                                                       | 433 ms: 1.62x faster                                                         |
| async_tree_memoization  | 827 ms                                                       | 546 ms: 1.51x faster                                                         |
| async_tree_io           | 1.61 sec                                                     | 1.08 sec: 1.49x faster                                                       |
| async_tree_cpu_io_mixed | 946 ms                                                       | 695 ms: 1.36x faster                                                         |
| Geometric mean          | (ref)                                                        | 1.49x faster                                                                 |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231111-pythonperf2-x86_64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| nbody          | 134 ms                                                       | 84.7 ms: 1.58x faster                                                        |
| float          | 109 ms                                                       | 79.3 ms: 1.37x faster                                                        |
| pidigits       | 270 ms                                                       | 265 ms: 1.02x faster                                                         |
| Geometric mean | (ref)                                                        | 1.30x faster                                                                 |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231111-pythonperf2-x86_64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| regex_compile  | 192 ms                                                       | 143 ms: 1.35x faster                                                         |
| regex_dna      | 260 ms                                                       | 244 ms: 1.06x faster                                                         |
| regex_v8       | 27.1 ms                                                      | 25.7 ms: 1.06x faster                                                        |
| regex_effbot   | 3.10 ms                                                      | 3.43 ms: 1.11x slower                                                        |
| Geometric mean | (ref)                                                        | 1.08x faster                                                                 |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231111-pythonperf2-x86_64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f |
|----------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| unpickle_pure_python | 315 us                                                       | 222 us: 1.42x faster                                                         |
| pickle_pure_python   | 453 us                                                       | 321 us: 1.41x faster                                                         |
| json_dumps           | 14.2 ms                                                      | 10.6 ms: 1.34x faster                                                        |
| tomli_loads          | 2.96 sec                                                     | 2.23 sec: 1.33x faster                                                       |
| xml_etree_process    | 76.4 ms                                                      | 58.4 ms: 1.31x faster                                                        |
| json_loads           | 30.0 us                                                      | 24.6 us: 1.22x faster                                                        |
| xml_etree_parse      | 159 ms                                                       | 146 ms: 1.09x faster                                                         |
| xml_etree_generate   | 93.1 ms                                                      | 85.5 ms: 1.09x faster                                                        |
| xml_etree_iterparse  | 110 ms                                                       | 106 ms: 1.03x faster                                                         |
| pickle               | 10.1 us                                                      | 10.1 us: 1.01x slower                                                        |
| unpickle             | 13.9 us                                                      | 14.4 us: 1.03x slower                                                        |
| pickle_list          | 4.23 us                                                      | 4.36 us: 1.03x slower                                                        |
| unpickle_list        | 4.45 us                                                      | 4.76 us: 1.07x slower                                                        |
| pickle_dict          | 30.4 us                                                      | 32.7 us: 1.07x slower                                                        |
| Geometric mean       | (ref)                                                        | 1.13x faster                                                                 |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231111-pythonperf2-x86_64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f |
|------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| python_startup         | 11.5 ms                                                      | 12.8 ms: 1.11x slower                                                        |
| python_startup_no_site | 7.35 ms                                                      | 11.3 ms: 1.54x slower                                                        |
| Geometric mean         | (ref)                                                        | 1.31x slower                                                                 |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231111-pythonperf2-x86_64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f |
|-----------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| mako      | 14.7 ms                                                      | 10.1 ms: 1.46x faster                                                        |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231111-pythonperf2-x86_64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f |
|--------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| typing_runtime_protocols | 533 us                                                       | 124 us: 4.29x faster                                                         |
| asyncio_tcp              | 785 ms                                                       | 369 ms: 2.13x faster                                                         |
| deltablue                | 7.43 ms                                                      | 3.60 ms: 2.06x faster                                                        |
| asyncio_tcp_ssl          | 3.13 sec                                                     | 1.58 sec: 1.98x faster                                                       |
| raytrace                 | 497 ms                                                       | 271 ms: 1.83x faster                                                         |
| logging_silent           | 168 ns                                                       | 95.3 ns: 1.76x faster                                                        |
| chaos                    | 106 ms                                                       | 61.4 ms: 1.73x faster                                                        |
| crypto_pyaes             | 118 ms                                                       | 70.6 ms: 1.67x faster                                                        |
| scimark_lu               | 165 ms                                                       | 98.6 ms: 1.67x faster                                                        |
| comprehensions           | 27.0 us                                                      | 16.3 us: 1.66x faster                                                        |
| scimark_monte_carlo      | 109 ms                                                       | 67.7 ms: 1.62x faster                                                        |
| async_tree_none          | 700 ms                                                       | 433 ms: 1.62x faster                                                         |
| sqlglot_parse            | 2.27 ms                                                      | 1.41 ms: 1.61x faster                                                        |
| generators               | 57.7 ms                                                      | 35.9 ms: 1.60x faster                                                        |
| nbody                    | 134 ms                                                       | 84.7 ms: 1.58x faster                                                        |
| spectral_norm            | 141 ms                                                       | 90.6 ms: 1.56x faster                                                        |
| go                       | 258 ms                                                       | 169 ms: 1.53x faster                                                         |
| async_tree_memoization   | 827 ms                                                       | 546 ms: 1.51x faster                                                         |
| richards_super           | 93.0 ms                                                      | 61.5 ms: 1.51x faster                                                        |
| sqlglot_transpile        | 2.73 ms                                                      | 1.82 ms: 1.50x faster                                                        |
| async_tree_io            | 1.61 sec                                                     | 1.08 sec: 1.49x faster                                                       |
| hexiom                   | 9.46 ms                                                      | 6.45 ms: 1.47x faster                                                        |
| mako                     | 14.7 ms                                                      | 10.1 ms: 1.46x faster                                                        |
| unpickle_pure_python     | 315 us                                                       | 222 us: 1.42x faster                                                         |
| bench_mp_pool            | 6.82 ms                                                      | 4.82 ms: 1.41x faster                                                        |
| pickle_pure_python       | 453 us                                                       | 321 us: 1.41x faster                                                         |
| coroutines               | 30.9 ms                                                      | 22.2 ms: 1.39x faster                                                        |
| deepcopy_memo            | 50.5 us                                                      | 36.7 us: 1.38x faster                                                        |
| logging_simple           | 9.06 us                                                      | 6.61 us: 1.37x faster                                                        |
| pyflate                  | 698 ms                                                       | 510 ms: 1.37x faster                                                         |
| float                    | 109 ms                                                       | 79.3 ms: 1.37x faster                                                        |
| chameleon                | 9.88 ms                                                      | 7.22 ms: 1.37x faster                                                        |
| richards                 | 76.3 ms                                                      | 55.8 ms: 1.37x faster                                                        |
| async_tree_cpu_io_mixed  | 946 ms                                                       | 695 ms: 1.36x faster                                                         |
| regex_compile            | 192 ms                                                       | 143 ms: 1.35x faster                                                         |
| json_dumps               | 14.2 ms                                                      | 10.6 ms: 1.34x faster                                                        |
| logging_format           | 9.82 us                                                      | 7.33 us: 1.34x faster                                                        |
| tomli_loads              | 2.96 sec                                                     | 2.23 sec: 1.33x faster                                                       |
| tornado_http             | 157 ms                                                       | 119 ms: 1.32x faster                                                         |
| pprint_pformat           | 2.15 sec                                                     | 1.64 sec: 1.31x faster                                                       |
| xml_etree_process        | 76.4 ms                                                      | 58.4 ms: 1.31x faster                                                        |
| pprint_safe_repr         | 1.04 sec                                                     | 801 ms: 1.30x faster                                                         |
| pycparser                | 1.65 sec                                                     | 1.27 sec: 1.30x faster                                                       |
| sympy_sum                | 194 ms                                                       | 151 ms: 1.28x faster                                                         |
| mypy2                    | 467 ms                                                       | 366 ms: 1.27x faster                                                         |
| sqlglot_normalize        | 146 ms                                                       | 117 ms: 1.25x faster                                                         |
| nqueens                  | 112 ms                                                       | 89.6 ms: 1.25x faster                                                        |
| scimark_sparse_mat_mult  | 5.21 ms                                                      | 4.19 ms: 1.24x faster                                                        |
| sympy_str                | 359 ms                                                       | 289 ms: 1.24x faster                                                         |
| deepcopy                 | 459 us                                                       | 372 us: 1.24x faster                                                         |
| sympy_integrate          | 28.3 ms                                                      | 23.0 ms: 1.23x faster                                                        |
| scimark_sor              | 183 ms                                                       | 149 ms: 1.23x faster                                                         |
| fannkuch                 | 488 ms                                                       | 400 ms: 1.22x faster                                                         |
| json_loads               | 30.0 us                                                      | 24.6 us: 1.22x faster                                                        |
| sympy_expand             | 599 ms                                                       | 492 ms: 1.22x faster                                                         |
| deepcopy_reduce          | 4.00 us                                                      | 3.29 us: 1.21x faster                                                        |
| docutils                 | 3.42 sec                                                     | 2.84 sec: 1.20x faster                                                       |
| 2to3                     | 349 ms                                                       | 292 ms: 1.19x faster                                                         |
| dulwich_log              | 80.0 ms                                                      | 67.2 ms: 1.19x faster                                                        |
| unpack_sequence          | 60.3 ns                                                      | 50.8 ns: 1.19x faster                                                        |
| sqlglot_optimize         | 69.9 ms                                                      | 59.1 ms: 1.18x faster                                                        |
| scimark_fft              | 363 ms                                                       | 308 ms: 1.18x faster                                                         |
| bench_thread_pool        | 1.13 ms                                                      | 968 us: 1.17x faster                                                         |
| async_generators         | 418 ms                                                       | 359 ms: 1.16x faster                                                         |
| mdp                      | 2.94 sec                                                     | 2.53 sec: 1.16x faster                                                       |
| json                     | 5.91 ms                                                      | 5.14 ms: 1.15x faster                                                        |
| sqlite_synth             | 2.97 us                                                      | 2.69 us: 1.10x faster                                                        |
| create_gc_cycles         | 1.79 ms                                                      | 1.63 ms: 1.10x faster                                                        |
| xml_etree_parse          | 159 ms                                                       | 146 ms: 1.09x faster                                                         |
| xml_etree_generate       | 93.1 ms                                                      | 85.5 ms: 1.09x faster                                                        |
| pathlib                  | 21.2 ms                                                      | 19.6 ms: 1.08x faster                                                        |
| regex_dna                | 260 ms                                                       | 244 ms: 1.06x faster                                                         |
| meteor_contest           | 138 ms                                                       | 130 ms: 1.06x faster                                                         |
| regex_v8                 | 27.1 ms                                                      | 25.7 ms: 1.06x faster                                                        |
| gc_traversal             | 3.63 ms                                                      | 3.49 ms: 1.04x faster                                                        |
| xml_etree_iterparse      | 110 ms                                                       | 106 ms: 1.03x faster                                                         |
| pidigits                 | 270 ms                                                       | 265 ms: 1.02x faster                                                         |
| asyncio_websockets       | 394 ms                                                       | 390 ms: 1.01x faster                                                         |
| pickle                   | 10.1 us                                                      | 10.1 us: 1.01x slower                                                        |
| unpickle                 | 13.9 us                                                      | 14.4 us: 1.03x slower                                                        |
| pickle_list              | 4.23 us                                                      | 4.36 us: 1.03x slower                                                        |
| unpickle_list            | 4.45 us                                                      | 4.76 us: 1.07x slower                                                        |
| pickle_dict              | 30.4 us                                                      | 32.7 us: 1.07x slower                                                        |
| telco                    | 7.21 ms                                                      | 7.94 ms: 1.10x slower                                                        |
| regex_effbot             | 3.10 ms                                                      | 3.43 ms: 1.11x slower                                                        |
| python_startup           | 11.5 ms                                                      | 12.8 ms: 1.11x slower                                                        |
| coverage                 | 65.9 ms                                                      | 82.8 ms: 1.26x slower                                                        |
| python_startup_no_site   | 7.35 ms                                                      | 11.3 ms: 1.54x slower                                                        |
| Geometric mean           | (ref)                                                        | 1.29x faster                                                                 |
Ignored benchmarks (12) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, dask, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
Ignored benchmarks (4) of results/bm-20231111-3.13.0a1+-fa84e5f/bm-20231111-pythonperf2-x86_64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.25x
- 95% likely to have a speedup of 1.24x
- 99% likely to have a speedup of 1.22x
