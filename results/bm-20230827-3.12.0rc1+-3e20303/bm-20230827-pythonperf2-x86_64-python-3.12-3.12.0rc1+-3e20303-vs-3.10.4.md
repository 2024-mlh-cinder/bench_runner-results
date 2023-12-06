
# Results vs. 3.10.4

- fork: python
- ref: 3.12
- machine: linux-x86_64
- commit hash: 3e20303
- commit date: 2023-08-27
- overall geometric mean: 1.30x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.23x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230827-pythonperf2-x86_64-python-3.12-3.12.0rc1+-3e20303 |
|----------------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| 2to3           | 350 ms                                                       | 284 ms: 1.23x faster                                          |
| docutils       | 3.40 sec                                                     | 2.91 sec: 1.17x faster                                        |
| tornado_http   | 152 ms                                                       | 121 ms: 1.26x faster                                          |
| Geometric mean | (ref)                                                        | 1.22x faster                                                  |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230827-pythonperf2-x86_64-python-3.12-3.12.0rc1+-3e20303 |
|----------------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| nbody          | 137 ms                                                       | 88.2 ms: 1.56x faster                                         |
| float          | 110 ms                                                       | 78.3 ms: 1.41x faster                                         |
| pidigits       | 271 ms                                                       | 259 ms: 1.05x faster                                          |
| Geometric mean | (ref)                                                        | 1.32x faster                                                  |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230827-pythonperf2-x86_64-python-3.12-3.12.0rc1+-3e20303 |
|----------------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| regex_compile  | 194 ms                                                       | 145 ms: 1.34x faster                                          |
| regex_v8       | 26.6 ms                                                      | 23.6 ms: 1.13x faster                                         |
| regex_dna      | 259 ms                                                       | 239 ms: 1.08x faster                                          |
| regex_effbot   | 2.99 ms                                                      | 3.51 ms: 1.17x slower                                         |
| Geometric mean | (ref)                                                        | 1.09x faster                                                  |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230827-pythonperf2-x86_64-python-3.12-3.12.0rc1+-3e20303 |
|----------------------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| unpickle_pure_python | 321 us                                                       | 211 us: 1.52x faster                                          |
| pickle_pure_python   | 457 us                                                       | 318 us: 1.44x faster                                          |
| json_dumps           | 14.2 ms                                                      | 10.3 ms: 1.38x faster                                         |
| tomli_loads          | 2.97 sec                                                     | 2.19 sec: 1.36x faster                                        |
| xml_etree_process    | 76.0 ms                                                      | 58.5 ms: 1.30x faster                                         |
| json_loads           | 30.0 us                                                      | 24.9 us: 1.20x faster                                         |
| xml_etree_generate   | 94.6 ms                                                      | 85.7 ms: 1.10x faster                                         |
| xml_etree_parse      | 162 ms                                                       | 148 ms: 1.09x faster                                          |
| xml_etree_iterparse  | 110 ms                                                       | 104 ms: 1.06x faster                                          |
| pickle               | 9.94 us                                                      | 9.90 us: 1.00x faster                                         |
| pickle_list          | 4.11 us                                                      | 4.17 us: 1.02x slower                                         |
| unpickle_list        | 4.49 us                                                      | 4.67 us: 1.04x slower                                         |
| unpickle             | 14.2 us                                                      | 14.8 us: 1.05x slower                                         |
| pickle_dict          | 30.0 us                                                      | 33.4 us: 1.11x slower                                         |
| Geometric mean       | (ref)                                                        | 1.15x faster                                                  |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230827-pythonperf2-x86_64-python-3.12-3.12.0rc1+-3e20303 |
|------------------------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| python_startup_no_site | 7.32 ms                                                      | 8.51 ms: 1.16x slower                                         |
| Geometric mean         | (ref)                                                        | 1.08x slower                                                  |

Benchmark hidden because not significant (1): python_startup

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230827-pythonperf2-x86_64-python-3.12-3.12.0rc1+-3e20303 |
|-----------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| mako      | 14.7 ms                                                      | 9.88 ms: 1.49x faster                                         |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230827-pythonperf2-x86_64-python-3.12-3.12.0rc1+-3e20303 |
|--------------------------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| typing_runtime_protocols | 523 us                                                       | 152 us: 3.44x faster                                          |
| deltablue                | 7.47 ms                                                      | 3.29 ms: 2.27x faster                                         |
| asyncio_tcp              | 782 ms                                                       | 383 ms: 2.04x faster                                          |
| asyncio_tcp_ssl          | 3.09 sec                                                     | 1.57 sec: 1.97x faster                                        |
| logging_silent           | 166 ns                                                       | 92.3 ns: 1.80x faster                                         |
| richards_super           | 90.8 ms                                                      | 51.1 ms: 1.78x faster                                         |
| go                       | 259 ms                                                       | 148 ms: 1.75x faster                                          |
| chaos                    | 107 ms                                                       | 62.7 ms: 1.71x faster                                         |
| scimark_lu               | 164 ms                                                       | 99.6 ms: 1.64x faster                                         |
| raytrace                 | 488 ms                                                       | 299 ms: 1.63x faster                                          |
| richards                 | 74.1 ms                                                      | 45.6 ms: 1.63x faster                                         |
| sqlglot_parse            | 2.26 ms                                                      | 1.39 ms: 1.62x faster                                         |
| hexiom                   | 9.52 ms                                                      | 5.89 ms: 1.62x faster                                         |
| generators               | 58.0 ms                                                      | 36.3 ms: 1.60x faster                                         |
| scimark_sor              | 177 ms                                                       | 112 ms: 1.59x faster                                          |
| nbody                    | 137 ms                                                       | 88.2 ms: 1.56x faster                                         |
| scimark_monte_carlo      | 109 ms                                                       | 71.4 ms: 1.53x faster                                         |
| async_tree_none          | 700 ms                                                       | 460 ms: 1.52x faster                                          |
| unpickle_pure_python     | 321 us                                                       | 211 us: 1.52x faster                                          |
| async_tree_io            | 1.61 sec                                                     | 1.06 sec: 1.52x faster                                        |
| sqlglot_transpile        | 2.71 ms                                                      | 1.80 ms: 1.51x faster                                         |
| async_tree_memoization   | 824 ms                                                       | 553 ms: 1.49x faster                                          |
| pyflate                  | 697 ms                                                       | 469 ms: 1.49x faster                                          |
| mako                     | 14.7 ms                                                      | 9.88 ms: 1.49x faster                                         |
| spectral_norm            | 136 ms                                                       | 91.8 ms: 1.48x faster                                         |
| pickle_pure_python       | 457 us                                                       | 318 us: 1.44x faster                                          |
| crypto_pyaes             | 118 ms                                                       | 82.9 ms: 1.43x faster                                         |
| bench_mp_pool            | 7.18 ms                                                      | 5.09 ms: 1.41x faster                                         |
| float                    | 110 ms                                                       | 78.3 ms: 1.41x faster                                         |
| json_dumps               | 14.2 ms                                                      | 10.3 ms: 1.38x faster                                         |
| fannkuch                 | 496 ms                                                       | 363 ms: 1.37x faster                                          |
| tomli_loads              | 2.97 sec                                                     | 2.19 sec: 1.36x faster                                        |
| async_tree_cpu_io_mixed  | 952 ms                                                       | 704 ms: 1.35x faster                                          |
| coroutines               | 30.4 ms                                                      | 22.6 ms: 1.35x faster                                         |
| deepcopy_memo            | 48.9 us                                                      | 36.5 us: 1.34x faster                                         |
| regex_compile            | 194 ms                                                       | 145 ms: 1.34x faster                                          |
| pycparser                | 1.66 sec                                                     | 1.25 sec: 1.33x faster                                        |
| pprint_pformat           | 2.15 sec                                                     | 1.62 sec: 1.33x faster                                        |
| pprint_safe_repr         | 1.05 sec                                                     | 800 ms: 1.31x faster                                          |
| logging_simple           | 8.90 us                                                      | 6.80 us: 1.31x faster                                         |
| xml_etree_process        | 76.0 ms                                                      | 58.5 ms: 1.30x faster                                         |
| logging_format           | 9.57 us                                                      | 7.41 us: 1.29x faster                                         |
| mypy2                    | 466 ms                                                       | 367 ms: 1.27x faster                                          |
| tornado_http             | 152 ms                                                       | 121 ms: 1.26x faster                                          |
| unpack_sequence          | 59.5 ns                                                      | 47.6 ns: 1.25x faster                                         |
| nqueens                  | 112 ms                                                       | 90.2 ms: 1.25x faster                                         |
| sqlglot_normalize        | 144 ms                                                       | 116 ms: 1.24x faster                                          |
| 2to3                     | 350 ms                                                       | 284 ms: 1.23x faster                                          |
| comprehensions           | 26.9 us                                                      | 21.9 us: 1.23x faster                                         |
| sqlglot_optimize         | 70.3 ms                                                      | 57.5 ms: 1.22x faster                                         |
| dulwich_log              | 80.1 ms                                                      | 65.9 ms: 1.22x faster                                         |
| json_loads               | 30.0 us                                                      | 24.9 us: 1.20x faster                                         |
| deepcopy                 | 454 us                                                       | 377 us: 1.20x faster                                          |
| mdp                      | 3.03 sec                                                     | 2.55 sec: 1.19x faster                                        |
| bench_thread_pool        | 1.14 ms                                                      | 954 us: 1.19x faster                                          |
| scimark_fft              | 359 ms                                                       | 302 ms: 1.19x faster                                          |
| scimark_sparse_mat_mult  | 5.19 ms                                                      | 4.43 ms: 1.17x faster                                         |
| docutils                 | 3.40 sec                                                     | 2.91 sec: 1.17x faster                                        |
| deepcopy_reduce          | 4.03 us                                                      | 3.45 us: 1.17x faster                                         |
| json                     | 5.96 ms                                                      | 5.16 ms: 1.16x faster                                         |
| pathlib                  | 21.7 ms                                                      | 19.0 ms: 1.14x faster                                         |
| regex_v8                 | 26.6 ms                                                      | 23.6 ms: 1.13x faster                                         |
| create_gc_cycles         | 1.82 ms                                                      | 1.62 ms: 1.13x faster                                         |
| async_generators         | 422 ms                                                       | 382 ms: 1.10x faster                                          |
| xml_etree_generate       | 94.6 ms                                                      | 85.7 ms: 1.10x faster                                         |
| sqlite_synth             | 2.97 us                                                      | 2.71 us: 1.09x faster                                         |
| xml_etree_parse          | 162 ms                                                       | 148 ms: 1.09x faster                                          |
| regex_dna                | 259 ms                                                       | 239 ms: 1.08x faster                                          |
| meteor_contest           | 137 ms                                                       | 127 ms: 1.08x faster                                          |
| xml_etree_iterparse      | 110 ms                                                       | 104 ms: 1.06x faster                                          |
| pidigits                 | 271 ms                                                       | 259 ms: 1.05x faster                                          |
| pickle                   | 9.94 us                                                      | 9.90 us: 1.00x faster                                         |
| pickle_list              | 4.11 us                                                      | 4.17 us: 1.02x slower                                         |
| unpickle_list            | 4.49 us                                                      | 4.67 us: 1.04x slower                                         |
| unpickle                 | 14.2 us                                                      | 14.8 us: 1.05x slower                                         |
| gc_traversal             | 3.45 ms                                                      | 3.71 ms: 1.08x slower                                         |
| pickle_dict              | 30.0 us                                                      | 33.4 us: 1.11x slower                                         |
| python_startup_no_site   | 7.32 ms                                                      | 8.51 ms: 1.16x slower                                         |
| regex_effbot             | 2.99 ms                                                      | 3.51 ms: 1.17x slower                                         |
| dask                     | 463 ms                                                       | 567 ms: 1.22x slower                                          |
| coverage                 | 64.0 ms                                                      | 88.2 ms: 1.38x slower                                         |
| Geometric mean           | (ref)                                                        | 1.30x faster                                                  |

Benchmark hidden because not significant (2): telco, python_startup
Ignored benchmarks (16) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.26x
- 95% likely to have a speedup of 1.25x
- 99% likely to have a speedup of 1.23x
