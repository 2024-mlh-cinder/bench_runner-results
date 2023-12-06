
# Results vs. 3.10.4

- fork: python
- ref: 6c13e13b13bebfdde8ad
- machine: linux-x86_64
- commit hash: 6c13e13
- commit date: 2023-09-13
- overall geometric mean: 1.28x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.20x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230913-pythonperf2-x86_64-python-6c13e13b13bebfdde8ad-3.13.0a0-6c13e13 |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| docutils       | 3.40 sec                                                     | 2.87 sec: 1.19x faster                                                      |
| tornado_http   | 152 ms                                                       | 121 ms: 1.26x faster                                                        |
| Geometric mean | (ref)                                                        | 1.22x faster                                                                |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230913-pythonperf2-x86_64-python-6c13e13b13bebfdde8ad-3.13.0a0-6c13e13 |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| nbody          | 137 ms                                                       | 87.0 ms: 1.58x faster                                                       |
| float          | 110 ms                                                       | 81.1 ms: 1.36x faster                                                       |
| pidigits       | 271 ms                                                       | 264 ms: 1.02x faster                                                        |
| Geometric mean | (ref)                                                        | 1.30x faster                                                                |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230913-pythonperf2-x86_64-python-6c13e13b13bebfdde8ad-3.13.0a0-6c13e13 |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_compile  | 194 ms                                                       | 149 ms: 1.30x faster                                                        |
| regex_dna      | 259 ms                                                       | 239 ms: 1.09x faster                                                        |
| regex_v8       | 26.6 ms                                                      | 24.8 ms: 1.07x faster                                                       |
| regex_effbot   | 2.99 ms                                                      | 3.42 ms: 1.14x slower                                                       |
| Geometric mean | (ref)                                                        | 1.07x faster                                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230913-pythonperf2-x86_64-python-6c13e13b13bebfdde8ad-3.13.0a0-6c13e13 |
|----------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| pickle_pure_python   | 457 us                                                       | 313 us: 1.46x faster                                                        |
| unpickle_pure_python | 321 us                                                       | 222 us: 1.44x faster                                                        |
| tomli_loads          | 2.97 sec                                                     | 2.22 sec: 1.34x faster                                                      |
| json_dumps           | 14.2 ms                                                      | 10.7 ms: 1.33x faster                                                       |
| xml_etree_process    | 76.0 ms                                                      | 58.6 ms: 1.30x faster                                                       |
| json_loads           | 30.0 us                                                      | 25.1 us: 1.20x faster                                                       |
| xml_etree_generate   | 94.6 ms                                                      | 85.9 ms: 1.10x faster                                                       |
| xml_etree_parse      | 162 ms                                                       | 149 ms: 1.09x faster                                                        |
| xml_etree_iterparse  | 110 ms                                                       | 107 ms: 1.04x faster                                                        |
| unpickle             | 14.2 us                                                      | 14.3 us: 1.01x slower                                                       |
| pickle_list          | 4.11 us                                                      | 4.15 us: 1.01x slower                                                       |
| unpickle_list        | 4.49 us                                                      | 4.72 us: 1.05x slower                                                       |
| pickle_dict          | 30.0 us                                                      | 32.3 us: 1.08x slower                                                       |
| Geometric mean       | (ref)                                                        | 1.14x faster                                                                |

Benchmark hidden because not significant (1): pickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230913-pythonperf2-x86_64-python-6c13e13b13bebfdde8ad-3.13.0a0-6c13e13 |
|------------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| python_startup         | 11.5 ms                                                      | 12.6 ms: 1.10x slower                                                       |
| python_startup_no_site | 7.32 ms                                                      | 8.65 ms: 1.18x slower                                                       |
| Geometric mean         | (ref)                                                        | 1.14x slower                                                                |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230913-pythonperf2-x86_64-python-6c13e13b13bebfdde8ad-3.13.0a0-6c13e13 |
|-----------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| mako      | 14.7 ms                                                      | 10.5 ms: 1.40x faster                                                       |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230913-pythonperf2-x86_64-python-6c13e13b13bebfdde8ad-3.13.0a0-6c13e13 |
|--------------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| typing_runtime_protocols | 523 us                                                       | 148 us: 3.52x faster                                                        |
| asyncio_tcp              | 782 ms                                                       | 372 ms: 2.11x faster                                                        |
| deltablue                | 7.47 ms                                                      | 3.69 ms: 2.02x faster                                                       |
| asyncio_tcp_ssl          | 3.09 sec                                                     | 1.58 sec: 1.96x faster                                                      |
| raytrace                 | 488 ms                                                       | 267 ms: 1.83x faster                                                        |
| logging_silent           | 166 ns                                                       | 97.7 ns: 1.70x faster                                                       |
| chaos                    | 107 ms                                                       | 63.6 ms: 1.68x faster                                                       |
| generators               | 58.0 ms                                                      | 34.7 ms: 1.67x faster                                                       |
| scimark_monte_carlo      | 109 ms                                                       | 66.3 ms: 1.65x faster                                                       |
| crypto_pyaes             | 118 ms                                                       | 71.7 ms: 1.65x faster                                                       |
| scimark_lu               | 164 ms                                                       | 101 ms: 1.62x faster                                                        |
| async_tree_none          | 700 ms                                                       | 437 ms: 1.60x faster                                                        |
| sqlglot_parse            | 2.26 ms                                                      | 1.42 ms: 1.59x faster                                                       |
| nbody                    | 137 ms                                                       | 87.0 ms: 1.58x faster                                                       |
| bench_mp_pool            | 7.18 ms                                                      | 4.66 ms: 1.54x faster                                                       |
| go                       | 259 ms                                                       | 170 ms: 1.53x faster                                                        |
| richards_super           | 90.8 ms                                                      | 60.7 ms: 1.50x faster                                                       |
| async_tree_memoization   | 824 ms                                                       | 552 ms: 1.49x faster                                                        |
| sqlglot_transpile        | 2.71 ms                                                      | 1.82 ms: 1.49x faster                                                       |
| async_tree_io            | 1.61 sec                                                     | 1.09 sec: 1.48x faster                                                      |
| hexiom                   | 9.52 ms                                                      | 6.47 ms: 1.47x faster                                                       |
| spectral_norm            | 136 ms                                                       | 92.6 ms: 1.47x faster                                                       |
| pickle_pure_python       | 457 us                                                       | 313 us: 1.46x faster                                                        |
| unpickle_pure_python     | 321 us                                                       | 222 us: 1.44x faster                                                        |
| mako                     | 14.7 ms                                                      | 10.5 ms: 1.40x faster                                                       |
| richards                 | 74.1 ms                                                      | 54.0 ms: 1.37x faster                                                       |
| float                    | 110 ms                                                       | 81.1 ms: 1.36x faster                                                       |
| pyflate                  | 697 ms                                                       | 516 ms: 1.35x faster                                                        |
| async_tree_cpu_io_mixed  | 952 ms                                                       | 706 ms: 1.35x faster                                                        |
| tomli_loads              | 2.97 sec                                                     | 2.22 sec: 1.34x faster                                                      |
| json_dumps               | 14.2 ms                                                      | 10.7 ms: 1.33x faster                                                       |
| coroutines               | 30.4 ms                                                      | 23.1 ms: 1.32x faster                                                       |
| pprint_pformat           | 2.15 sec                                                     | 1.65 sec: 1.31x faster                                                      |
| logging_simple           | 8.90 us                                                      | 6.83 us: 1.30x faster                                                       |
| pprint_safe_repr         | 1.05 sec                                                     | 806 ms: 1.30x faster                                                        |
| regex_compile            | 194 ms                                                       | 149 ms: 1.30x faster                                                        |
| xml_etree_process        | 76.0 ms                                                      | 58.6 ms: 1.30x faster                                                       |
| deepcopy_memo            | 48.9 us                                                      | 37.8 us: 1.29x faster                                                       |
| logging_format           | 9.57 us                                                      | 7.49 us: 1.28x faster                                                       |
| tornado_http             | 152 ms                                                       | 121 ms: 1.26x faster                                                        |
| mypy2                    | 466 ms                                                       | 370 ms: 1.26x faster                                                        |
| sqlglot_normalize        | 144 ms                                                       | 115 ms: 1.25x faster                                                        |
| nqueens                  | 112 ms                                                       | 90.0 ms: 1.25x faster                                                       |
| pycparser                | 1.66 sec                                                     | 1.33 sec: 1.25x faster                                                      |
| fannkuch                 | 496 ms                                                       | 397 ms: 1.25x faster                                                        |
| scimark_sparse_mat_mult  | 5.19 ms                                                      | 4.24 ms: 1.22x faster                                                       |
| unpack_sequence          | 59.5 ns                                                      | 48.7 ns: 1.22x faster                                                       |
| sqlglot_optimize         | 70.3 ms                                                      | 58.4 ms: 1.20x faster                                                       |
| scimark_sor              | 177 ms                                                       | 148 ms: 1.20x faster                                                        |
| json_loads               | 30.0 us                                                      | 25.1 us: 1.20x faster                                                       |
| comprehensions           | 26.9 us                                                      | 22.6 us: 1.19x faster                                                       |
| scimark_fft              | 359 ms                                                       | 301 ms: 1.19x faster                                                        |
| deepcopy_reduce          | 4.03 us                                                      | 3.39 us: 1.19x faster                                                       |
| deepcopy                 | 454 us                                                       | 382 us: 1.19x faster                                                        |
| mdp                      | 3.03 sec                                                     | 2.55 sec: 1.19x faster                                                      |
| docutils                 | 3.40 sec                                                     | 2.87 sec: 1.19x faster                                                      |
| bench_thread_pool        | 1.14 ms                                                      | 963 us: 1.18x faster                                                        |
| dulwich_log              | 80.1 ms                                                      | 69.3 ms: 1.16x faster                                                       |
| json                     | 5.96 ms                                                      | 5.16 ms: 1.15x faster                                                       |
| create_gc_cycles         | 1.82 ms                                                      | 1.64 ms: 1.11x faster                                                       |
| pathlib                  | 21.7 ms                                                      | 19.7 ms: 1.10x faster                                                       |
| xml_etree_generate       | 94.6 ms                                                      | 85.9 ms: 1.10x faster                                                       |
| xml_etree_parse          | 162 ms                                                       | 149 ms: 1.09x faster                                                        |
| regex_dna                | 259 ms                                                       | 239 ms: 1.09x faster                                                        |
| sqlite_synth             | 2.97 us                                                      | 2.75 us: 1.08x faster                                                       |
| async_generators         | 422 ms                                                       | 392 ms: 1.08x faster                                                        |
| regex_v8                 | 26.6 ms                                                      | 24.8 ms: 1.07x faster                                                       |
| meteor_contest           | 137 ms                                                       | 129 ms: 1.06x faster                                                        |
| xml_etree_iterparse      | 110 ms                                                       | 107 ms: 1.04x faster                                                        |
| pidigits                 | 271 ms                                                       | 264 ms: 1.02x faster                                                        |
| unpickle                 | 14.2 us                                                      | 14.3 us: 1.01x slower                                                       |
| pickle_list              | 4.11 us                                                      | 4.15 us: 1.01x slower                                                       |
| gc_traversal             | 3.45 ms                                                      | 3.56 ms: 1.03x slower                                                       |
| unpickle_list            | 4.49 us                                                      | 4.72 us: 1.05x slower                                                       |
| pickle_dict              | 30.0 us                                                      | 32.3 us: 1.08x slower                                                       |
| python_startup           | 11.5 ms                                                      | 12.6 ms: 1.10x slower                                                       |
| regex_effbot             | 2.99 ms                                                      | 3.42 ms: 1.14x slower                                                       |
| telco                    | 7.14 ms                                                      | 8.20 ms: 1.15x slower                                                       |
| python_startup_no_site   | 7.32 ms                                                      | 8.65 ms: 1.18x slower                                                       |
| dask                     | 463 ms                                                       | 588 ms: 1.27x slower                                                        |
| coverage                 | 64.0 ms                                                      | 81.3 ms: 1.27x slower                                                       |
| Geometric mean           | (ref)                                                        | 1.28x faster                                                                |

Benchmark hidden because not significant (1): pickle
Ignored benchmarks (17) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120.json: 2to3, aiohttp, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.25x
- 95% likely to have a speedup of 1.24x
- 99% likely to have a speedup of 1.20x
