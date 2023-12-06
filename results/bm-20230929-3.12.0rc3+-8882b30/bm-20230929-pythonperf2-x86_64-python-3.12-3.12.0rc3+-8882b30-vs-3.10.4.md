
# Results vs. 3.10.4

- fork: python
- ref: 3.12
- machine: linux-x86_64
- commit hash: 8882b30
- commit date: 2023-09-29
- overall geometric mean: 1.30x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.23x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230929-pythonperf2-x86_64-python-3.12-3.12.0rc3+-8882b30 |
|----------------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| 2to3           | 350 ms                                                       | 286 ms: 1.22x faster                                          |
| docutils       | 3.40 sec                                                     | 2.88 sec: 1.18x faster                                        |
| tornado_http   | 152 ms                                                       | 122 ms: 1.24x faster                                          |
| Geometric mean | (ref)                                                        | 1.21x faster                                                  |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230929-pythonperf2-x86_64-python-3.12-3.12.0rc3+-8882b30 |
|----------------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| nbody          | 137 ms                                                       | 94.2 ms: 1.46x faster                                         |
| float          | 110 ms                                                       | 78.4 ms: 1.41x faster                                         |
| pidigits       | 271 ms                                                       | 265 ms: 1.02x faster                                          |
| Geometric mean | (ref)                                                        | 1.28x faster                                                  |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230929-pythonperf2-x86_64-python-3.12-3.12.0rc3+-8882b30 |
|----------------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| regex_compile  | 194 ms                                                       | 145 ms: 1.34x faster                                          |
| regex_dna      | 259 ms                                                       | 240 ms: 1.08x faster                                          |
| regex_v8       | 26.6 ms                                                      | 24.7 ms: 1.08x faster                                         |
| regex_effbot   | 2.99 ms                                                      | 3.57 ms: 1.19x slower                                         |
| Geometric mean | (ref)                                                        | 1.07x faster                                                  |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230929-pythonperf2-x86_64-python-3.12-3.12.0rc3+-8882b30 |
|----------------------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| unpickle_pure_python | 321 us                                                       | 210 us: 1.53x faster                                          |
| pickle_pure_python   | 457 us                                                       | 326 us: 1.40x faster                                          |
| json_dumps           | 14.2 ms                                                      | 10.3 ms: 1.38x faster                                         |
| tomli_loads          | 2.97 sec                                                     | 2.21 sec: 1.34x faster                                        |
| xml_etree_process    | 76.0 ms                                                      | 58.9 ms: 1.29x faster                                         |
| json_loads           | 30.0 us                                                      | 24.2 us: 1.24x faster                                         |
| xml_etree_parse      | 162 ms                                                       | 147 ms: 1.10x faster                                          |
| xml_etree_generate   | 94.6 ms                                                      | 86.4 ms: 1.10x faster                                         |
| xml_etree_iterparse  | 110 ms                                                       | 104 ms: 1.06x faster                                          |
| pickle               | 9.94 us                                                      | 10.2 us: 1.03x slower                                         |
| unpickle             | 14.2 us                                                      | 14.8 us: 1.04x slower                                         |
| pickle_list          | 4.11 us                                                      | 4.35 us: 1.06x slower                                         |
| pickle_dict          | 30.0 us                                                      | 32.1 us: 1.07x slower                                         |
| unpickle_list        | 4.49 us                                                      | 4.82 us: 1.07x slower                                         |
| Geometric mean       | (ref)                                                        | 1.14x faster                                                  |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230929-pythonperf2-x86_64-python-3.12-3.12.0rc3+-8882b30 |
|------------------------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| python_startup         | 11.5 ms                                                      | 11.7 ms: 1.02x slower                                         |
| python_startup_no_site | 7.32 ms                                                      | 8.67 ms: 1.18x slower                                         |
| Geometric mean         | (ref)                                                        | 1.10x slower                                                  |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230929-pythonperf2-x86_64-python-3.12-3.12.0rc3+-8882b30 |
|-----------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| mako      | 14.7 ms                                                      | 9.96 ms: 1.47x faster                                         |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230929-pythonperf2-x86_64-python-3.12-3.12.0rc3+-8882b30 |
|--------------------------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| typing_runtime_protocols | 523 us                                                       | 154 us: 3.40x faster                                          |
| deltablue                | 7.47 ms                                                      | 3.30 ms: 2.27x faster                                         |
| asyncio_tcp              | 782 ms                                                       | 381 ms: 2.06x faster                                          |
| asyncio_tcp_ssl          | 3.09 sec                                                     | 1.57 sec: 1.97x faster                                        |
| logging_silent           | 166 ns                                                       | 95.3 ns: 1.74x faster                                         |
| richards_super           | 90.8 ms                                                      | 52.3 ms: 1.74x faster                                         |
| go                       | 259 ms                                                       | 151 ms: 1.72x faster                                          |
| chaos                    | 107 ms                                                       | 63.4 ms: 1.69x faster                                         |
| scimark_lu               | 164 ms                                                       | 97.8 ms: 1.67x faster                                         |
| scimark_sor              | 177 ms                                                       | 108 ms: 1.64x faster                                          |
| richards                 | 74.1 ms                                                      | 45.4 ms: 1.63x faster                                         |
| sqlglot_parse            | 2.26 ms                                                      | 1.40 ms: 1.62x faster                                         |
| raytrace                 | 488 ms                                                       | 303 ms: 1.61x faster                                          |
| generators               | 58.0 ms                                                      | 36.5 ms: 1.59x faster                                         |
| hexiom                   | 9.52 ms                                                      | 6.01 ms: 1.58x faster                                         |
| pyflate                  | 697 ms                                                       | 443 ms: 1.57x faster                                          |
| unpickle_pure_python     | 321 us                                                       | 210 us: 1.53x faster                                          |
| scimark_monte_carlo      | 109 ms                                                       | 71.6 ms: 1.53x faster                                         |
| async_tree_io            | 1.61 sec                                                     | 1.06 sec: 1.52x faster                                        |
| async_tree_none          | 700 ms                                                       | 462 ms: 1.51x faster                                          |
| sqlglot_transpile        | 2.71 ms                                                      | 1.79 ms: 1.51x faster                                         |
| bench_mp_pool            | 7.18 ms                                                      | 4.76 ms: 1.51x faster                                         |
| async_tree_memoization   | 824 ms                                                       | 554 ms: 1.49x faster                                          |
| mako                     | 14.7 ms                                                      | 9.96 ms: 1.47x faster                                         |
| spectral_norm            | 136 ms                                                       | 93.2 ms: 1.46x faster                                         |
| nbody                    | 137 ms                                                       | 94.2 ms: 1.46x faster                                         |
| crypto_pyaes             | 118 ms                                                       | 81.8 ms: 1.45x faster                                         |
| float                    | 110 ms                                                       | 78.4 ms: 1.41x faster                                         |
| pickle_pure_python       | 457 us                                                       | 326 us: 1.40x faster                                          |
| fannkuch                 | 496 ms                                                       | 358 ms: 1.38x faster                                          |
| json_dumps               | 14.2 ms                                                      | 10.3 ms: 1.38x faster                                         |
| async_tree_cpu_io_mixed  | 952 ms                                                       | 707 ms: 1.35x faster                                          |
| logging_simple           | 8.90 us                                                      | 6.62 us: 1.34x faster                                         |
| tomli_loads              | 2.97 sec                                                     | 2.21 sec: 1.34x faster                                        |
| regex_compile            | 194 ms                                                       | 145 ms: 1.34x faster                                          |
| coroutines               | 30.4 ms                                                      | 23.2 ms: 1.31x faster                                         |
| deepcopy_memo            | 48.9 us                                                      | 37.3 us: 1.31x faster                                         |
| pprint_pformat           | 2.15 sec                                                     | 1.66 sec: 1.30x faster                                        |
| xml_etree_process        | 76.0 ms                                                      | 58.9 ms: 1.29x faster                                         |
| pycparser                | 1.66 sec                                                     | 1.29 sec: 1.29x faster                                        |
| pprint_safe_repr         | 1.05 sec                                                     | 820 ms: 1.28x faster                                          |
| logging_format           | 9.57 us                                                      | 7.52 us: 1.27x faster                                         |
| mypy2                    | 466 ms                                                       | 368 ms: 1.27x faster                                          |
| nqueens                  | 112 ms                                                       | 90.3 ms: 1.25x faster                                         |
| tornado_http             | 152 ms                                                       | 122 ms: 1.24x faster                                          |
| comprehensions           | 26.9 us                                                      | 21.7 us: 1.24x faster                                         |
| json_loads               | 30.0 us                                                      | 24.2 us: 1.24x faster                                         |
| sqlglot_normalize        | 144 ms                                                       | 117 ms: 1.23x faster                                          |
| dulwich_log              | 80.1 ms                                                      | 65.2 ms: 1.23x faster                                         |
| 2to3                     | 350 ms                                                       | 286 ms: 1.22x faster                                          |
| sqlglot_optimize         | 70.3 ms                                                      | 57.9 ms: 1.21x faster                                         |
| deepcopy                 | 454 us                                                       | 374 us: 1.21x faster                                          |
| scimark_fft              | 359 ms                                                       | 297 ms: 1.21x faster                                          |
| scimark_sparse_mat_mult  | 5.19 ms                                                      | 4.33 ms: 1.20x faster                                         |
| mdp                      | 3.03 sec                                                     | 2.54 sec: 1.19x faster                                        |
| docutils                 | 3.40 sec                                                     | 2.88 sec: 1.18x faster                                        |
| bench_thread_pool        | 1.14 ms                                                      | 965 us: 1.18x faster                                          |
| deepcopy_reduce          | 4.03 us                                                      | 3.44 us: 1.17x faster                                         |
| dask                     | 463 ms                                                       | 396 ms: 1.17x faster                                          |
| json                     | 5.96 ms                                                      | 5.12 ms: 1.16x faster                                         |
| unpack_sequence          | 59.5 ns                                                      | 52.9 ns: 1.13x faster                                         |
| pathlib                  | 21.7 ms                                                      | 19.4 ms: 1.12x faster                                         |
| sqlite_synth             | 2.97 us                                                      | 2.70 us: 1.10x faster                                         |
| xml_etree_parse          | 162 ms                                                       | 147 ms: 1.10x faster                                          |
| xml_etree_generate       | 94.6 ms                                                      | 86.4 ms: 1.10x faster                                         |
| async_generators         | 422 ms                                                       | 386 ms: 1.09x faster                                          |
| regex_dna                | 259 ms                                                       | 240 ms: 1.08x faster                                          |
| regex_v8                 | 26.6 ms                                                      | 24.7 ms: 1.08x faster                                         |
| create_gc_cycles         | 1.82 ms                                                      | 1.69 ms: 1.08x faster                                         |
| meteor_contest           | 137 ms                                                       | 128 ms: 1.07x faster                                          |
| xml_etree_iterparse      | 110 ms                                                       | 104 ms: 1.06x faster                                          |
| pidigits                 | 271 ms                                                       | 265 ms: 1.02x faster                                          |
| python_startup           | 11.5 ms                                                      | 11.7 ms: 1.02x slower                                         |
| pickle                   | 9.94 us                                                      | 10.2 us: 1.03x slower                                         |
| unpickle                 | 14.2 us                                                      | 14.8 us: 1.04x slower                                         |
| pickle_list              | 4.11 us                                                      | 4.35 us: 1.06x slower                                         |
| pickle_dict              | 30.0 us                                                      | 32.1 us: 1.07x slower                                         |
| unpickle_list            | 4.49 us                                                      | 4.82 us: 1.07x slower                                         |
| gc_traversal             | 3.45 ms                                                      | 4.04 ms: 1.17x slower                                         |
| python_startup_no_site   | 7.32 ms                                                      | 8.67 ms: 1.18x slower                                         |
| regex_effbot             | 2.99 ms                                                      | 3.57 ms: 1.19x slower                                         |
| coverage                 | 64.0 ms                                                      | 88.5 ms: 1.38x slower                                         |
| Geometric mean           | (ref)                                                        | 1.30x faster                                                  |

Benchmark hidden because not significant (1): telco
Ignored benchmarks (16) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.26x
- 95% likely to have a speedup of 1.24x
- 99% likely to have a speedup of 1.23x
