
# Results vs. 3.10.4

- fork: brandtbucher
- ref: justin
- machine: linux-x86_64
- commit hash: 07fb485
- commit date: 2023-10-11
- overall geometric mean: 1.23x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.16x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231011-pythonperf2-x86_64-brandtbucher-justin-3.13.0a0-07fb485 |
|----------------|:------------------------------------------------------------:|:-------------------------------------------------------------------:|
| docutils       | 3.40 sec                                                     | 2.93 sec: 1.16x faster                                              |
| tornado_http   | 152 ms                                                       | 124 ms: 1.22x faster                                                |
| Geometric mean | (ref)                                                        | 1.19x faster                                                        |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231011-pythonperf2-x86_64-brandtbucher-justin-3.13.0a0-07fb485 |
|----------------|:------------------------------------------------------------:|:-------------------------------------------------------------------:|
| nbody          | 137 ms                                                       | 100 ms: 1.37x faster                                                |
| float          | 110 ms                                                       | 88.8 ms: 1.24x faster                                               |
| pidigits       | 271 ms                                                       | 265 ms: 1.02x faster                                                |
| Geometric mean | (ref)                                                        | 1.20x faster                                                        |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231011-pythonperf2-x86_64-brandtbucher-justin-3.13.0a0-07fb485 |
|----------------|:------------------------------------------------------------:|:-------------------------------------------------------------------:|
| regex_compile  | 194 ms                                                       | 159 ms: 1.22x faster                                                |
| regex_dna      | 259 ms                                                       | 247 ms: 1.05x faster                                                |
| regex_effbot   | 2.99 ms                                                      | 3.62 ms: 1.21x slower                                               |
| Geometric mean | (ref)                                                        | 1.01x faster                                                        |

Benchmark hidden because not significant (1): regex_v8

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231011-pythonperf2-x86_64-brandtbucher-justin-3.13.0a0-07fb485 |
|----------------------|:------------------------------------------------------------:|:-------------------------------------------------------------------:|
| pickle_pure_python   | 457 us                                                       | 317 us: 1.44x faster                                                |
| unpickle_pure_python | 321 us                                                       | 237 us: 1.36x faster                                                |
| json_dumps           | 14.2 ms                                                      | 10.8 ms: 1.32x faster                                               |
| xml_etree_process    | 76.0 ms                                                      | 58.8 ms: 1.29x faster                                               |
| json_loads           | 30.0 us                                                      | 24.6 us: 1.22x faster                                               |
| tomli_loads          | 2.97 sec                                                     | 2.48 sec: 1.20x faster                                              |
| xml_etree_generate   | 94.6 ms                                                      | 85.9 ms: 1.10x faster                                               |
| xml_etree_parse      | 162 ms                                                       | 149 ms: 1.08x faster                                                |
| xml_etree_iterparse  | 110 ms                                                       | 107 ms: 1.03x faster                                                |
| unpickle             | 14.2 us                                                      | 14.3 us: 1.01x slower                                               |
| pickle               | 9.94 us                                                      | 10.0 us: 1.01x slower                                               |
| unpickle_list        | 4.49 us                                                      | 4.68 us: 1.04x slower                                               |
| pickle_list          | 4.11 us                                                      | 4.33 us: 1.05x slower                                               |
| pickle_dict          | 30.0 us                                                      | 32.8 us: 1.09x slower                                               |
| Geometric mean       | (ref)                                                        | 1.12x faster                                                        |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231011-pythonperf2-x86_64-brandtbucher-justin-3.13.0a0-07fb485 |
|------------------------|:------------------------------------------------------------:|:-------------------------------------------------------------------:|
| python_startup         | 11.5 ms                                                      | 12.6 ms: 1.10x slower                                               |
| python_startup_no_site | 7.32 ms                                                      | 8.69 ms: 1.19x slower                                               |
| Geometric mean         | (ref)                                                        | 1.14x slower                                                        |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231011-pythonperf2-x86_64-brandtbucher-justin-3.13.0a0-07fb485 |
|-----------|:------------------------------------------------------------:|:-------------------------------------------------------------------:|
| mako      | 14.7 ms                                                      | 12.1 ms: 1.21x faster                                               |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231011-pythonperf2-x86_64-brandtbucher-justin-3.13.0a0-07fb485 |
|--------------------------|:------------------------------------------------------------:|:-------------------------------------------------------------------:|
| typing_runtime_protocols | 523 us                                                       | 156 us: 3.35x faster                                                |
| asyncio_tcp              | 782 ms                                                       | 371 ms: 2.11x faster                                                |
| asyncio_tcp_ssl          | 3.09 sec                                                     | 1.59 sec: 1.95x faster                                              |
| raytrace                 | 488 ms                                                       | 291 ms: 1.68x faster                                                |
| logging_silent           | 166 ns                                                       | 98.8 ns: 1.68x faster                                               |
| generators               | 58.0 ms                                                      | 36.2 ms: 1.60x faster                                               |
| richards_super           | 90.8 ms                                                      | 57.6 ms: 1.58x faster                                               |
| async_tree_none          | 700 ms                                                       | 444 ms: 1.57x faster                                                |
| scimark_lu               | 164 ms                                                       | 104 ms: 1.57x faster                                                |
| sqlglot_parse            | 2.26 ms                                                      | 1.44 ms: 1.56x faster                                               |
| deltablue                | 7.47 ms                                                      | 4.80 ms: 1.56x faster                                               |
| chaos                    | 107 ms                                                       | 69.8 ms: 1.54x faster                                               |
| bench_mp_pool            | 7.18 ms                                                      | 4.74 ms: 1.52x faster                                               |
| scimark_monte_carlo      | 109 ms                                                       | 73.3 ms: 1.49x faster                                               |
| async_tree_memoization   | 824 ms                                                       | 557 ms: 1.48x faster                                                |
| go                       | 259 ms                                                       | 175 ms: 1.48x faster                                                |
| async_tree_io            | 1.61 sec                                                     | 1.09 sec: 1.48x faster                                              |
| spectral_norm            | 136 ms                                                       | 93.2 ms: 1.46x faster                                               |
| sqlglot_transpile        | 2.71 ms                                                      | 1.86 ms: 1.46x faster                                               |
| pickle_pure_python       | 457 us                                                       | 317 us: 1.44x faster                                                |
| richards                 | 74.1 ms                                                      | 51.6 ms: 1.44x faster                                               |
| crypto_pyaes             | 118 ms                                                       | 83.9 ms: 1.41x faster                                               |
| nbody                    | 137 ms                                                       | 100 ms: 1.37x faster                                                |
| unpickle_pure_python     | 321 us                                                       | 237 us: 1.36x faster                                                |
| async_tree_cpu_io_mixed  | 952 ms                                                       | 712 ms: 1.34x faster                                                |
| json_dumps               | 14.2 ms                                                      | 10.8 ms: 1.32x faster                                               |
| pyflate                  | 697 ms                                                       | 534 ms: 1.31x faster                                                |
| coroutines               | 30.4 ms                                                      | 23.4 ms: 1.30x faster                                               |
| xml_etree_process        | 76.0 ms                                                      | 58.8 ms: 1.29x faster                                               |
| logging_simple           | 8.90 us                                                      | 6.97 us: 1.28x faster                                               |
| pycparser                | 1.66 sec                                                     | 1.34 sec: 1.24x faster                                              |
| float                    | 110 ms                                                       | 88.8 ms: 1.24x faster                                               |
| logging_format           | 9.57 us                                                      | 7.73 us: 1.24x faster                                               |
| deepcopy_memo            | 48.9 us                                                      | 39.5 us: 1.24x faster                                               |
| sqlglot_normalize        | 144 ms                                                       | 117 ms: 1.23x faster                                                |
| tornado_http             | 152 ms                                                       | 124 ms: 1.22x faster                                                |
| mypy2                    | 466 ms                                                       | 382 ms: 1.22x faster                                                |
| regex_compile            | 194 ms                                                       | 159 ms: 1.22x faster                                                |
| json_loads               | 30.0 us                                                      | 24.6 us: 1.22x faster                                               |
| mako                     | 14.7 ms                                                      | 12.1 ms: 1.21x faster                                               |
| deepcopy                 | 454 us                                                       | 376 us: 1.21x faster                                                |
| scimark_sor              | 177 ms                                                       | 148 ms: 1.20x faster                                                |
| tomli_loads              | 2.97 sec                                                     | 2.48 sec: 1.20x faster                                              |
| unpack_sequence          | 59.5 ns                                                      | 49.9 ns: 1.19x faster                                               |
| deepcopy_reduce          | 4.03 us                                                      | 3.38 us: 1.19x faster                                               |
| pprint_pformat           | 2.15 sec                                                     | 1.81 sec: 1.19x faster                                              |
| pprint_safe_repr         | 1.05 sec                                                     | 885 ms: 1.19x faster                                                |
| sqlglot_optimize         | 70.3 ms                                                      | 59.6 ms: 1.18x faster                                               |
| docutils                 | 3.40 sec                                                     | 2.93 sec: 1.16x faster                                              |
| mdp                      | 3.03 sec                                                     | 2.62 sec: 1.16x faster                                              |
| bench_thread_pool        | 1.14 ms                                                      | 983 us: 1.16x faster                                                |
| fannkuch                 | 496 ms                                                       | 429 ms: 1.15x faster                                                |
| json                     | 5.96 ms                                                      | 5.17 ms: 1.15x faster                                               |
| dulwich_log              | 80.1 ms                                                      | 69.5 ms: 1.15x faster                                               |
| create_gc_cycles         | 1.82 ms                                                      | 1.60 ms: 1.14x faster                                               |
| scimark_sparse_mat_mult  | 5.19 ms                                                      | 4.59 ms: 1.13x faster                                               |
| nqueens                  | 112 ms                                                       | 102 ms: 1.10x faster                                                |
| xml_etree_generate       | 94.6 ms                                                      | 85.9 ms: 1.10x faster                                               |
| sqlite_synth             | 2.97 us                                                      | 2.70 us: 1.10x faster                                               |
| xml_etree_parse          | 162 ms                                                       | 149 ms: 1.08x faster                                                |
| pathlib                  | 21.7 ms                                                      | 20.2 ms: 1.08x faster                                               |
| hexiom                   | 9.52 ms                                                      | 9.00 ms: 1.06x faster                                               |
| regex_dna                | 259 ms                                                       | 247 ms: 1.05x faster                                                |
| xml_etree_iterparse      | 110 ms                                                       | 107 ms: 1.03x faster                                                |
| pidigits                 | 271 ms                                                       | 265 ms: 1.02x faster                                                |
| meteor_contest           | 137 ms                                                       | 137 ms: 1.00x slower                                                |
| scimark_fft              | 359 ms                                                       | 361 ms: 1.00x slower                                                |
| unpickle                 | 14.2 us                                                      | 14.3 us: 1.01x slower                                               |
| pickle                   | 9.94 us                                                      | 10.0 us: 1.01x slower                                               |
| gc_traversal             | 3.45 ms                                                      | 3.52 ms: 1.02x slower                                               |
| unpickle_list            | 4.49 us                                                      | 4.68 us: 1.04x slower                                               |
| pickle_list              | 4.11 us                                                      | 4.33 us: 1.05x slower                                               |
| comprehensions           | 26.9 us                                                      | 28.5 us: 1.06x slower                                               |
| pickle_dict              | 30.0 us                                                      | 32.8 us: 1.09x slower                                               |
| python_startup           | 11.5 ms                                                      | 12.6 ms: 1.10x slower                                               |
| telco                    | 7.14 ms                                                      | 8.32 ms: 1.16x slower                                               |
| python_startup_no_site   | 7.32 ms                                                      | 8.69 ms: 1.19x slower                                               |
| regex_effbot             | 2.99 ms                                                      | 3.62 ms: 1.21x slower                                               |
| coverage                 | 64.0 ms                                                      | 82.6 ms: 1.29x slower                                               |
| Geometric mean           | (ref)                                                        | 1.23x faster                                                        |

Benchmark hidden because not significant (2): regex_v8, async_generators
Ignored benchmarks (18) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120.json: 2to3, aiohttp, chameleon, dask, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.19x
- 95% likely to have a speedup of 1.18x
- 99% likely to have a speedup of 1.16x
