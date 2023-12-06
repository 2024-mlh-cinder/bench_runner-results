
# Results vs. 3.10.4

- fork: python
- ref: 1a969b4f55f92a17bec8
- machine: linux-x86_64
- commit hash: 1a969b4
- commit date: 2023-11-19
- overall geometric mean: 1.18x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.10x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231119-pythonperf2-x86_64-python-1a969b4f55f92a17bec8-3.13.0a1+-1a969b4 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| 2to3           | 349 ms                                                       | 316 ms: 1.10x faster                                                         |
| chameleon      | 9.88 ms                                                      | 7.93 ms: 1.25x faster                                                        |
| docutils       | 3.42 sec                                                     | 2.93 sec: 1.17x faster                                                       |
| tornado_http   | 157 ms                                                       | 125 ms: 1.25x faster                                                         |
| Geometric mean | (ref)                                                        | 1.19x faster                                                                 |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231119-pythonperf2-x86_64-python-1a969b4f55f92a17bec8-3.13.0a1+-1a969b4 |
|-------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| async_tree_none         | 700 ms                                                       | 453 ms: 1.54x faster                                                         |
| async_tree_memoization  | 827 ms                                                       | 567 ms: 1.46x faster                                                         |
| async_tree_io           | 1.61 sec                                                     | 1.11 sec: 1.45x faster                                                       |
| async_tree_cpu_io_mixed | 946 ms                                                       | 718 ms: 1.32x faster                                                         |
| Geometric mean          | (ref)                                                        | 1.44x faster                                                                 |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231119-pythonperf2-x86_64-python-1a969b4f55f92a17bec8-3.13.0a1+-1a969b4 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| nbody          | 134 ms                                                       | 120 ms: 1.11x faster                                                         |
| pidigits       | 270 ms                                                       | 267 ms: 1.01x faster                                                         |
| float          | 109 ms                                                       | 108 ms: 1.01x faster                                                         |
| Geometric mean | (ref)                                                        | 1.04x faster                                                                 |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231119-pythonperf2-x86_64-python-1a969b4f55f92a17bec8-3.13.0a1+-1a969b4 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| regex_compile  | 192 ms                                                       | 177 ms: 1.09x faster                                                         |
| regex_v8       | 27.1 ms                                                      | 26.2 ms: 1.03x faster                                                        |
| regex_dna      | 260 ms                                                       | 252 ms: 1.03x faster                                                         |
| regex_effbot   | 3.10 ms                                                      | 3.52 ms: 1.13x slower                                                        |
| Geometric mean | (ref)                                                        | 1.01x faster                                                                 |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231119-pythonperf2-x86_64-python-1a969b4f55f92a17bec8-3.13.0a1+-1a969b4 |
|----------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| pickle_pure_python   | 453 us                                                       | 311 us: 1.46x faster                                                         |
| json_dumps           | 14.2 ms                                                      | 10.7 ms: 1.33x faster                                                        |
| xml_etree_process    | 76.4 ms                                                      | 57.8 ms: 1.32x faster                                                        |
| unpickle_pure_python | 315 us                                                       | 252 us: 1.25x faster                                                         |
| json_loads           | 30.0 us                                                      | 25.5 us: 1.18x faster                                                        |
| xml_etree_generate   | 93.1 ms                                                      | 86.8 ms: 1.07x faster                                                        |
| xml_etree_parse      | 159 ms                                                       | 153 ms: 1.04x faster                                                         |
| tomli_loads          | 2.96 sec                                                     | 2.88 sec: 1.03x faster                                                       |
| xml_etree_iterparse  | 110 ms                                                       | 111 ms: 1.02x slower                                                         |
| unpickle             | 13.9 us                                                      | 14.5 us: 1.04x slower                                                        |
| pickle_dict          | 30.4 us                                                      | 32.0 us: 1.05x slower                                                        |
| unpickle_list        | 4.45 us                                                      | 4.70 us: 1.06x slower                                                        |
| pickle_list          | 4.23 us                                                      | 4.49 us: 1.06x slower                                                        |
| Geometric mean       | (ref)                                                        | 1.09x faster                                                                 |

Benchmark hidden because not significant (1): pickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231119-pythonperf2-x86_64-python-1a969b4f55f92a17bec8-3.13.0a1+-1a969b4 |
|------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| python_startup         | 11.5 ms                                                      | 12.8 ms: 1.11x slower                                                        |
| python_startup_no_site | 7.35 ms                                                      | 11.3 ms: 1.54x slower                                                        |
| Geometric mean         | (ref)                                                        | 1.30x slower                                                                 |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231119-pythonperf2-x86_64-python-1a969b4f55f92a17bec8-3.13.0a1+-1a969b4 |
|-----------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| mako      | 14.7 ms                                                      | 16.9 ms: 1.15x slower                                                        |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231119-pythonperf2-x86_64-python-1a969b4f55f92a17bec8-3.13.0a1+-1a969b4 |
|--------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| typing_runtime_protocols | 533 us                                                       | 131 us: 4.06x faster                                                         |
| asyncio_tcp              | 785 ms                                                       | 375 ms: 2.09x faster                                                         |
| asyncio_tcp_ssl          | 3.13 sec                                                     | 1.59 sec: 1.97x faster                                                       |
| logging_silent           | 168 ns                                                       | 98.9 ns: 1.70x faster                                                        |
| generators               | 57.7 ms                                                      | 34.0 ms: 1.70x faster                                                        |
| raytrace                 | 497 ms                                                       | 312 ms: 1.60x faster                                                         |
| async_tree_none          | 700 ms                                                       | 453 ms: 1.54x faster                                                         |
| sqlglot_parse            | 2.27 ms                                                      | 1.47 ms: 1.54x faster                                                        |
| spectral_norm            | 141 ms                                                       | 91.7 ms: 1.54x faster                                                        |
| richards_super           | 93.0 ms                                                      | 61.4 ms: 1.51x faster                                                        |
| scimark_lu               | 165 ms                                                       | 109 ms: 1.51x faster                                                         |
| async_tree_memoization   | 827 ms                                                       | 567 ms: 1.46x faster                                                         |
| pickle_pure_python       | 453 us                                                       | 311 us: 1.46x faster                                                         |
| sqlglot_transpile        | 2.73 ms                                                      | 1.88 ms: 1.45x faster                                                        |
| async_tree_io            | 1.61 sec                                                     | 1.11 sec: 1.45x faster                                                       |
| coroutines               | 30.9 ms                                                      | 22.1 ms: 1.40x faster                                                        |
| richards                 | 76.3 ms                                                      | 55.7 ms: 1.37x faster                                                        |
| bench_mp_pool            | 6.82 ms                                                      | 5.02 ms: 1.36x faster                                                        |
| go                       | 258 ms                                                       | 191 ms: 1.35x faster                                                         |
| chaos                    | 106 ms                                                       | 78.9 ms: 1.34x faster                                                        |
| logging_simple           | 9.06 us                                                      | 6.80 us: 1.33x faster                                                        |
| json_dumps               | 14.2 ms                                                      | 10.7 ms: 1.33x faster                                                        |
| deltablue                | 7.43 ms                                                      | 5.61 ms: 1.32x faster                                                        |
| xml_etree_process        | 76.4 ms                                                      | 57.8 ms: 1.32x faster                                                        |
| async_tree_cpu_io_mixed  | 946 ms                                                       | 718 ms: 1.32x faster                                                         |
| logging_format           | 9.82 us                                                      | 7.51 us: 1.31x faster                                                        |
| crypto_pyaes             | 118 ms                                                       | 90.8 ms: 1.30x faster                                                        |
| deepcopy_memo            | 50.5 us                                                      | 40.0 us: 1.26x faster                                                        |
| tornado_http             | 157 ms                                                       | 125 ms: 1.25x faster                                                         |
| deepcopy                 | 459 us                                                       | 367 us: 1.25x faster                                                         |
| unpickle_pure_python     | 315 us                                                       | 252 us: 1.25x faster                                                         |
| pycparser                | 1.65 sec                                                     | 1.32 sec: 1.25x faster                                                       |
| chameleon                | 9.88 ms                                                      | 7.93 ms: 1.25x faster                                                        |
| sqlglot_normalize        | 146 ms                                                       | 117 ms: 1.25x faster                                                         |
| mypy2                    | 467 ms                                                       | 379 ms: 1.23x faster                                                         |
| deepcopy_reduce          | 4.00 us                                                      | 3.26 us: 1.23x faster                                                        |
| scimark_sor              | 183 ms                                                       | 151 ms: 1.21x faster                                                         |
| scimark_monte_carlo      | 109 ms                                                       | 90.2 ms: 1.21x faster                                                        |
| sympy_sum                | 194 ms                                                       | 160 ms: 1.21x faster                                                         |
| pyflate                  | 698 ms                                                       | 582 ms: 1.20x faster                                                         |
| json_loads               | 30.0 us                                                      | 25.5 us: 1.18x faster                                                        |
| sqlglot_optimize         | 69.9 ms                                                      | 59.5 ms: 1.17x faster                                                        |
| bench_thread_pool        | 1.13 ms                                                      | 969 us: 1.17x faster                                                         |
| docutils                 | 3.42 sec                                                     | 2.93 sec: 1.17x faster                                                       |
| dask                     | 469 ms                                                       | 407 ms: 1.15x faster                                                         |
| sympy_str                | 359 ms                                                       | 312 ms: 1.15x faster                                                         |
| pprint_pformat           | 2.15 sec                                                     | 1.89 sec: 1.14x faster                                                       |
| sympy_expand             | 599 ms                                                       | 527 ms: 1.14x faster                                                         |
| pprint_safe_repr         | 1.04 sec                                                     | 916 ms: 1.14x faster                                                         |
| create_gc_cycles         | 1.79 ms                                                      | 1.58 ms: 1.13x faster                                                        |
| sympy_integrate          | 28.3 ms                                                      | 25.0 ms: 1.13x faster                                                        |
| dulwich_log              | 80.0 ms                                                      | 71.3 ms: 1.12x faster                                                        |
| json                     | 5.91 ms                                                      | 5.29 ms: 1.12x faster                                                        |
| nbody                    | 134 ms                                                       | 120 ms: 1.11x faster                                                         |
| unpack_sequence          | 60.3 ns                                                      | 54.3 ns: 1.11x faster                                                        |
| async_generators         | 418 ms                                                       | 379 ms: 1.10x faster                                                         |
| 2to3                     | 349 ms                                                       | 316 ms: 1.10x faster                                                         |
| pathlib                  | 21.2 ms                                                      | 19.4 ms: 1.09x faster                                                        |
| sqlite_synth             | 2.97 us                                                      | 2.72 us: 1.09x faster                                                        |
| regex_compile            | 192 ms                                                       | 177 ms: 1.09x faster                                                         |
| xml_etree_generate       | 93.1 ms                                                      | 86.8 ms: 1.07x faster                                                        |
| mdp                      | 2.94 sec                                                     | 2.77 sec: 1.06x faster                                                       |
| xml_etree_parse          | 159 ms                                                       | 153 ms: 1.04x faster                                                         |
| regex_v8                 | 27.1 ms                                                      | 26.2 ms: 1.03x faster                                                        |
| regex_dna                | 260 ms                                                       | 252 ms: 1.03x faster                                                         |
| tomli_loads              | 2.96 sec                                                     | 2.88 sec: 1.03x faster                                                       |
| pidigits                 | 270 ms                                                       | 267 ms: 1.01x faster                                                         |
| float                    | 109 ms                                                       | 108 ms: 1.01x faster                                                         |
| meteor_contest           | 138 ms                                                       | 139 ms: 1.01x slower                                                         |
| xml_etree_iterparse      | 110 ms                                                       | 111 ms: 1.02x slower                                                         |
| gc_traversal             | 3.63 ms                                                      | 3.71 ms: 1.02x slower                                                        |
| comprehensions           | 27.0 us                                                      | 27.7 us: 1.03x slower                                                        |
| fannkuch                 | 488 ms                                                       | 505 ms: 1.03x slower                                                         |
| unpickle                 | 13.9 us                                                      | 14.5 us: 1.04x slower                                                        |
| nqueens                  | 112 ms                                                       | 117 ms: 1.05x slower                                                         |
| pickle_dict              | 30.4 us                                                      | 32.0 us: 1.05x slower                                                        |
| unpickle_list            | 4.45 us                                                      | 4.70 us: 1.06x slower                                                        |
| pickle_list              | 4.23 us                                                      | 4.49 us: 1.06x slower                                                        |
| python_startup           | 11.5 ms                                                      | 12.8 ms: 1.11x slower                                                        |
| hexiom                   | 9.46 ms                                                      | 10.6 ms: 1.12x slower                                                        |
| regex_effbot             | 3.10 ms                                                      | 3.52 ms: 1.13x slower                                                        |
| mako                     | 14.7 ms                                                      | 16.9 ms: 1.15x slower                                                        |
| telco                    | 7.21 ms                                                      | 8.56 ms: 1.19x slower                                                        |
| scimark_fft              | 363 ms                                                       | 447 ms: 1.23x slower                                                         |
| coverage                 | 65.9 ms                                                      | 82.9 ms: 1.26x slower                                                        |
| scimark_sparse_mat_mult  | 5.21 ms                                                      | 6.60 ms: 1.27x slower                                                        |
| python_startup_no_site   | 7.35 ms                                                      | 11.3 ms: 1.54x slower                                                        |
| Geometric mean           | (ref)                                                        | 1.18x faster                                                                 |

Benchmark hidden because not significant (2): asyncio_websockets, pickle
Ignored benchmarks (11) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
Ignored benchmarks (4) of results/bm-20231119-3.13.0a1+-1a969b4-PYTHON_UOPS/bm-20231119-pythonperf2-x86_64-python-1a969b4f55f92a17bec8-3.13.0a1+-1a969b4.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.13x
- 95% likely to have a speedup of 1.13x
- 99% likely to have a speedup of 1.10x
