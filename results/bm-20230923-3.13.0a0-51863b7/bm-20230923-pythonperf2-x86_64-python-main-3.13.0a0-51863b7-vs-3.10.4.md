
# Results vs. 3.10.4

- fork: python
- ref: main
- machine: linux-x86_64
- commit hash: 51863b7
- commit date: 2023-09-23
- overall geometric mean: 1.27x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.20x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230923-pythonperf2-x86_64-python-main-3.13.0a0-51863b7 |
|----------------|:------------------------------------------------------------:|:-----------------------------------------------------------:|
| docutils       | 3.40 sec                                                     | 2.86 sec: 1.19x faster                                      |
| tornado_http   | 152 ms                                                       | 120 ms: 1.27x faster                                        |
| Geometric mean | (ref)                                                        | 1.23x faster                                                |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230923-pythonperf2-x86_64-python-main-3.13.0a0-51863b7 |
|----------------|:------------------------------------------------------------:|:-----------------------------------------------------------:|
| nbody          | 137 ms                                                       | 89.7 ms: 1.53x faster                                       |
| float          | 110 ms                                                       | 80.9 ms: 1.36x faster                                       |
| pidigits       | 271 ms                                                       | 264 ms: 1.02x faster                                        |
| Geometric mean | (ref)                                                        | 1.29x faster                                                |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230923-pythonperf2-x86_64-python-main-3.13.0a0-51863b7 |
|----------------|:------------------------------------------------------------:|:-----------------------------------------------------------:|
| regex_compile  | 194 ms                                                       | 148 ms: 1.31x faster                                        |
| regex_dna      | 259 ms                                                       | 238 ms: 1.09x faster                                        |
| regex_v8       | 26.6 ms                                                      | 24.5 ms: 1.09x faster                                       |
| regex_effbot   | 2.99 ms                                                      | 3.55 ms: 1.18x slower                                       |
| Geometric mean | (ref)                                                        | 1.07x faster                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230923-pythonperf2-x86_64-python-main-3.13.0a0-51863b7 |
|----------------------|:------------------------------------------------------------:|:-----------------------------------------------------------:|
| pickle_pure_python   | 457 us                                                       | 317 us: 1.44x faster                                        |
| unpickle_pure_python | 321 us                                                       | 231 us: 1.39x faster                                        |
| json_dumps           | 14.2 ms                                                      | 10.4 ms: 1.36x faster                                       |
| tomli_loads          | 2.97 sec                                                     | 2.30 sec: 1.29x faster                                      |
| xml_etree_process    | 76.0 ms                                                      | 59.4 ms: 1.28x faster                                       |
| json_loads           | 30.0 us                                                      | 25.0 us: 1.20x faster                                       |
| xml_etree_generate   | 94.6 ms                                                      | 86.4 ms: 1.09x faster                                       |
| xml_etree_parse      | 162 ms                                                       | 148 ms: 1.09x faster                                        |
| xml_etree_iterparse  | 110 ms                                                       | 105 ms: 1.05x faster                                        |
| unpickle             | 14.2 us                                                      | 14.5 us: 1.02x slower                                       |
| unpickle_list        | 4.49 us                                                      | 4.68 us: 1.04x slower                                       |
| pickle_dict          | 30.0 us                                                      | 31.9 us: 1.06x slower                                       |
| pickle_list          | 4.11 us                                                      | 4.43 us: 1.08x slower                                       |
| Geometric mean       | (ref)                                                        | 1.13x faster                                                |

Benchmark hidden because not significant (1): pickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230923-pythonperf2-x86_64-python-main-3.13.0a0-51863b7 |
|------------------------|:------------------------------------------------------------:|:-----------------------------------------------------------:|
| python_startup         | 11.5 ms                                                      | 12.6 ms: 1.10x slower                                       |
| python_startup_no_site | 7.32 ms                                                      | 8.67 ms: 1.18x slower                                       |
| Geometric mean         | (ref)                                                        | 1.14x slower                                                |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230923-pythonperf2-x86_64-python-main-3.13.0a0-51863b7 |
|-----------|:------------------------------------------------------------:|:-----------------------------------------------------------:|
| mako      | 14.7 ms                                                      | 10.4 ms: 1.42x faster                                       |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230923-pythonperf2-x86_64-python-main-3.13.0a0-51863b7 |
|--------------------------|:------------------------------------------------------------:|:-----------------------------------------------------------:|
| typing_runtime_protocols | 523 us                                                       | 150 us: 3.48x faster                                        |
| asyncio_tcp              | 782 ms                                                       | 370 ms: 2.12x faster                                        |
| deltablue                | 7.47 ms                                                      | 3.69 ms: 2.02x faster                                       |
| asyncio_tcp_ssl          | 3.09 sec                                                     | 1.58 sec: 1.95x faster                                      |
| raytrace                 | 488 ms                                                       | 269 ms: 1.81x faster                                        |
| logging_silent           | 166 ns                                                       | 96.8 ns: 1.71x faster                                       |
| chaos                    | 107 ms                                                       | 63.8 ms: 1.68x faster                                       |
| crypto_pyaes             | 118 ms                                                       | 72.0 ms: 1.64x faster                                       |
| generators               | 58.0 ms                                                      | 35.3 ms: 1.64x faster                                       |
| async_tree_none          | 700 ms                                                       | 433 ms: 1.62x faster                                        |
| sqlglot_parse            | 2.26 ms                                                      | 1.40 ms: 1.61x faster                                       |
| scimark_lu               | 164 ms                                                       | 102 ms: 1.61x faster                                        |
| scimark_monte_carlo      | 109 ms                                                       | 69.6 ms: 1.57x faster                                       |
| go                       | 259 ms                                                       | 167 ms: 1.55x faster                                        |
| richards_super           | 90.8 ms                                                      | 59.2 ms: 1.54x faster                                       |
| nbody                    | 137 ms                                                       | 89.7 ms: 1.53x faster                                       |
| async_tree_memoization   | 824 ms                                                       | 547 ms: 1.51x faster                                        |
| sqlglot_transpile        | 2.71 ms                                                      | 1.81 ms: 1.50x faster                                       |
| async_tree_io            | 1.61 sec                                                     | 1.08 sec: 1.50x faster                                      |
| hexiom                   | 9.52 ms                                                      | 6.40 ms: 1.49x faster                                       |
| bench_mp_pool            | 7.18 ms                                                      | 4.84 ms: 1.48x faster                                       |
| spectral_norm            | 136 ms                                                       | 94.2 ms: 1.45x faster                                       |
| pickle_pure_python       | 457 us                                                       | 317 us: 1.44x faster                                        |
| mako                     | 14.7 ms                                                      | 10.4 ms: 1.42x faster                                       |
| unpickle_pure_python     | 321 us                                                       | 231 us: 1.39x faster                                        |
| richards                 | 74.1 ms                                                      | 53.5 ms: 1.38x faster                                       |
| async_tree_cpu_io_mixed  | 952 ms                                                       | 696 ms: 1.37x faster                                        |
| pyflate                  | 697 ms                                                       | 510 ms: 1.37x faster                                        |
| json_dumps               | 14.2 ms                                                      | 10.4 ms: 1.36x faster                                       |
| float                    | 110 ms                                                       | 80.9 ms: 1.36x faster                                       |
| deepcopy_memo            | 48.9 us                                                      | 37.1 us: 1.32x faster                                       |
| regex_compile            | 194 ms                                                       | 148 ms: 1.31x faster                                        |
| coroutines               | 30.4 ms                                                      | 23.4 ms: 1.30x faster                                       |
| tomli_loads              | 2.97 sec                                                     | 2.30 sec: 1.29x faster                                      |
| pycparser                | 1.66 sec                                                     | 1.30 sec: 1.28x faster                                      |
| logging_simple           | 8.90 us                                                      | 6.95 us: 1.28x faster                                       |
| xml_etree_process        | 76.0 ms                                                      | 59.4 ms: 1.28x faster                                       |
| pprint_pformat           | 2.15 sec                                                     | 1.69 sec: 1.28x faster                                      |
| tornado_http             | 152 ms                                                       | 120 ms: 1.27x faster                                        |
| nqueens                  | 112 ms                                                       | 88.8 ms: 1.27x faster                                       |
| logging_format           | 9.57 us                                                      | 7.55 us: 1.27x faster                                       |
| pprint_safe_repr         | 1.05 sec                                                     | 830 ms: 1.27x faster                                        |
| mypy2                    | 466 ms                                                       | 370 ms: 1.26x faster                                        |
| sqlglot_normalize        | 144 ms                                                       | 115 ms: 1.26x faster                                        |
| fannkuch                 | 496 ms                                                       | 395 ms: 1.25x faster                                        |
| scimark_sparse_mat_mult  | 5.19 ms                                                      | 4.18 ms: 1.24x faster                                       |
| comprehensions           | 26.9 us                                                      | 21.9 us: 1.23x faster                                       |
| sqlglot_optimize         | 70.3 ms                                                      | 58.3 ms: 1.21x faster                                       |
| bench_thread_pool        | 1.14 ms                                                      | 944 us: 1.20x faster                                        |
| deepcopy                 | 454 us                                                       | 377 us: 1.20x faster                                        |
| json_loads               | 30.0 us                                                      | 25.0 us: 1.20x faster                                       |
| mdp                      | 3.03 sec                                                     | 2.55 sec: 1.19x faster                                      |
| docutils                 | 3.40 sec                                                     | 2.86 sec: 1.19x faster                                      |
| scimark_sor              | 177 ms                                                       | 150 ms: 1.18x faster                                        |
| scimark_fft              | 359 ms                                                       | 305 ms: 1.18x faster                                        |
| deepcopy_reduce          | 4.03 us                                                      | 3.43 us: 1.17x faster                                       |
| dulwich_log              | 80.1 ms                                                      | 68.4 ms: 1.17x faster                                       |
| json                     | 5.96 ms                                                      | 5.13 ms: 1.16x faster                                       |
| unpack_sequence          | 59.5 ns                                                      | 52.1 ns: 1.14x faster                                       |
| xml_etree_generate       | 94.6 ms                                                      | 86.4 ms: 1.09x faster                                       |
| xml_etree_parse          | 162 ms                                                       | 148 ms: 1.09x faster                                        |
| sqlite_synth             | 2.97 us                                                      | 2.72 us: 1.09x faster                                       |
| regex_dna                | 259 ms                                                       | 238 ms: 1.09x faster                                        |
| pathlib                  | 21.7 ms                                                      | 20.0 ms: 1.09x faster                                       |
| regex_v8                 | 26.6 ms                                                      | 24.5 ms: 1.09x faster                                       |
| create_gc_cycles         | 1.82 ms                                                      | 1.70 ms: 1.07x faster                                       |
| async_generators         | 422 ms                                                       | 402 ms: 1.05x faster                                        |
| xml_etree_iterparse      | 110 ms                                                       | 105 ms: 1.05x faster                                        |
| meteor_contest           | 137 ms                                                       | 131 ms: 1.04x faster                                        |
| pidigits                 | 271 ms                                                       | 264 ms: 1.02x faster                                        |
| unpickle                 | 14.2 us                                                      | 14.5 us: 1.02x slower                                       |
| unpickle_list            | 4.49 us                                                      | 4.68 us: 1.04x slower                                       |
| gc_traversal             | 3.45 ms                                                      | 3.60 ms: 1.04x slower                                       |
| pickle_dict              | 30.0 us                                                      | 31.9 us: 1.06x slower                                       |
| pickle_list              | 4.11 us                                                      | 4.43 us: 1.08x slower                                       |
| python_startup           | 11.5 ms                                                      | 12.6 ms: 1.10x slower                                       |
| telco                    | 7.14 ms                                                      | 8.01 ms: 1.12x slower                                       |
| python_startup_no_site   | 7.32 ms                                                      | 8.67 ms: 1.18x slower                                       |
| regex_effbot             | 2.99 ms                                                      | 3.55 ms: 1.18x slower                                       |
| coverage                 | 64.0 ms                                                      | 80.6 ms: 1.26x slower                                       |
| dask                     | 463 ms                                                       | 587 ms: 1.27x slower                                        |
| Geometric mean           | (ref)                                                        | 1.27x faster                                                |

Benchmark hidden because not significant (1): pickle
Ignored benchmarks (17) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120.json: 2to3, aiohttp, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.25x
- 95% likely to have a speedup of 1.24x
- 99% likely to have a speedup of 1.20x
