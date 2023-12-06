
# Results vs. 3.10.4

- fork: python
- ref: v3.12.0b4
- machine: windows-amd64
- commit hash: 97a6a41
- commit date: 2023-07-11
- overall geometric mean: 1.18x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.12x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230711-pythonperf1-amd64-python-v3.12.0b4-3.12.0b4-97a6a41 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| 2to3           | 239 ms                                                      | 207 ms: 1.15x faster                                            |
| docutils       | 1.88 sec                                                    | 1.61 sec: 1.17x faster                                          |
| tornado_http   | 106 ms                                                      | 86.3 ms: 1.22x faster                                           |
| Geometric mean | (ref)                                                       | 1.18x faster                                                    |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230711-pythonperf1-amd64-python-v3.12.0b4-3.12.0b4-97a6a41 |
|-------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| async_tree_memoization  | 505 ms                                                      | 333 ms: 1.52x faster                                            |
| async_tree_io           | 1.07 sec                                                    | 709 ms: 1.51x faster                                            |
| async_tree_none         | 424 ms                                                      | 287 ms: 1.48x faster                                            |
| async_tree_cpu_io_mixed | 617 ms                                                      | 475 ms: 1.30x faster                                            |
| Geometric mean          | (ref)                                                       | 1.45x faster                                                    |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230711-pythonperf1-amd64-python-v3.12.0b4-3.12.0b4-97a6a41 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| float          | 61.7 ms                                                     | 53.6 ms: 1.15x faster                                           |
| pidigits       | 146 ms                                                      | 150 ms: 1.03x slower                                            |
| nbody          | 71.0 ms                                                     | 74.4 ms: 1.05x slower                                           |
| Geometric mean | (ref)                                                       | 1.02x faster                                                    |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230711-pythonperf1-amd64-python-v3.12.0b4-3.12.0b4-97a6a41 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| regex_compile  | 102 ms                                                      | 87.2 ms: 1.17x faster                                           |
| regex_v8       | 15.0 ms                                                     | 13.0 ms: 1.16x faster                                           |
| regex_dna      | 129 ms                                                      | 115 ms: 1.12x faster                                            |
| regex_effbot   | 1.56 ms                                                     | 1.57 ms: 1.01x slower                                           |
| Geometric mean | (ref)                                                       | 1.11x faster                                                    |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230711-pythonperf1-amd64-python-v3.12.0b4-3.12.0b4-97a6a41 |
|----------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| json_dumps           | 8.77 ms                                                     | 5.50 ms: 1.60x faster                                           |
| pickle_pure_python   | 259 us                                                      | 195 us: 1.33x faster                                            |
| unpickle_pure_python | 177 us                                                      | 135 us: 1.31x faster                                            |
| tomli_loads          | 1.65 sec                                                    | 1.41 sec: 1.17x faster                                          |
| xml_etree_process    | 43.1 ms                                                     | 37.4 ms: 1.15x faster                                           |
| unpickle             | 9.11 us                                                     | 8.23 us: 1.11x faster                                           |
| json_loads           | 14.2 us                                                     | 13.4 us: 1.06x faster                                           |
| xml_etree_parse      | 96.8 ms                                                     | 91.5 ms: 1.06x faster                                           |
| xml_etree_generate   | 54.5 ms                                                     | 55.0 ms: 1.01x slower                                           |
| pickle               | 6.87 us                                                     | 7.05 us: 1.02x slower                                           |
| pickle_list          | 2.69 us                                                     | 2.89 us: 1.07x slower                                           |
| pickle_dict          | 17.1 us                                                     | 18.4 us: 1.08x slower                                           |
| unpickle_list        | 2.68 us                                                     | 2.90 us: 1.08x slower                                           |
| Geometric mean       | (ref)                                                       | 1.10x faster                                                    |

Benchmark hidden because not significant (1): xml_etree_iterparse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230711-pythonperf1-amd64-python-v3.12.0b4-3.12.0b4-97a6a41 |
|------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| python_startup         | 19.7 ms                                                     | 19.1 ms: 1.03x faster                                           |
| python_startup_no_site | 15.3 ms                                                     | 16.4 ms: 1.07x slower                                           |
| Geometric mean         | (ref)                                                       | 1.02x slower                                                    |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230711-pythonperf1-amd64-python-v3.12.0b4-3.12.0b4-97a6a41 |
|-----------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| mako      | 8.98 ms                                                     | 6.86 ms: 1.31x faster                                           |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230711-pythonperf1-amd64-python-v3.12.0b4-3.12.0b4-97a6a41 |
|--------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| typing_runtime_protocols | 337 us                                                      | 93.3 us: 3.61x faster                                           |
| deltablue                | 4.12 ms                                                     | 2.10 ms: 1.96x faster                                           |
| mypy2                    | 347 ms                                                      | 206 ms: 1.68x faster                                            |
| richards_super           | 50.3 ms                                                     | 30.2 ms: 1.67x faster                                           |
| json_dumps               | 8.77 ms                                                     | 5.50 ms: 1.60x faster                                           |
| logging_silent           | 93.4 ns                                                     | 59.4 ns: 1.57x faster                                           |
| go                       | 135 ms                                                      | 88.2 ms: 1.53x faster                                           |
| async_tree_memoization   | 505 ms                                                      | 333 ms: 1.52x faster                                            |
| richards                 | 40.6 ms                                                     | 26.8 ms: 1.51x faster                                           |
| asyncio_tcp              | 717 ms                                                      | 474 ms: 1.51x faster                                            |
| async_tree_io            | 1.07 sec                                                    | 709 ms: 1.51x faster                                            |
| sqlglot_parse            | 1.20 ms                                                     | 802 us: 1.50x faster                                            |
| async_tree_none          | 424 ms                                                      | 287 ms: 1.48x faster                                            |
| scimark_lu               | 84.0 ms                                                     | 57.6 ms: 1.46x faster                                           |
| raytrace                 | 266 ms                                                      | 186 ms: 1.43x faster                                            |
| generators               | 31.8 ms                                                     | 22.2 ms: 1.43x faster                                           |
| sqlglot_transpile        | 1.45 ms                                                     | 1.01 ms: 1.42x faster                                           |
| chaos                    | 59.5 ms                                                     | 43.3 ms: 1.37x faster                                           |
| pycparser                | 905 ms                                                      | 667 ms: 1.36x faster                                            |
| hexiom                   | 5.59 ms                                                     | 4.14 ms: 1.35x faster                                           |
| scimark_monte_carlo      | 58.0 ms                                                     | 43.0 ms: 1.35x faster                                           |
| pyflate                  | 402 ms                                                      | 298 ms: 1.35x faster                                            |
| crypto_pyaes             | 63.1 ms                                                     | 46.8 ms: 1.35x faster                                           |
| pickle_pure_python       | 259 us                                                      | 195 us: 1.33x faster                                            |
| unpickle_pure_python     | 177 us                                                      | 135 us: 1.31x faster                                            |
| mako                     | 8.98 ms                                                     | 6.86 ms: 1.31x faster                                           |
| async_tree_cpu_io_mixed  | 617 ms                                                      | 475 ms: 1.30x faster                                            |
| scimark_sor              | 105 ms                                                      | 82.6 ms: 1.27x faster                                           |
| tornado_http             | 106 ms                                                      | 86.3 ms: 1.22x faster                                           |
| spectral_norm            | 78.9 ms                                                     | 65.1 ms: 1.21x faster                                           |
| comprehensions           | 16.6 us                                                     | 14.0 us: 1.18x faster                                           |
| regex_compile            | 102 ms                                                      | 87.2 ms: 1.17x faster                                           |
| sqlglot_optimize         | 39.4 ms                                                     | 33.7 ms: 1.17x faster                                           |
| tomli_loads              | 1.65 sec                                                    | 1.41 sec: 1.17x faster                                          |
| pprint_pformat           | 1.22 sec                                                    | 1.05 sec: 1.17x faster                                          |
| docutils                 | 1.88 sec                                                    | 1.61 sec: 1.17x faster                                          |
| deepcopy_memo            | 29.0 us                                                     | 24.9 us: 1.16x faster                                           |
| regex_v8                 | 15.0 ms                                                     | 13.0 ms: 1.16x faster                                           |
| pprint_safe_repr         | 594 ms                                                      | 514 ms: 1.16x faster                                            |
| dulwich_log              | 48.6 ms                                                     | 42.1 ms: 1.15x faster                                           |
| float                    | 61.7 ms                                                     | 53.6 ms: 1.15x faster                                           |
| xml_etree_process        | 43.1 ms                                                     | 37.4 ms: 1.15x faster                                           |
| 2to3                     | 239 ms                                                      | 207 ms: 1.15x faster                                            |
| mdp                      | 1.71 sec                                                    | 1.49 sec: 1.15x faster                                          |
| sqlglot_normalize        | 207 ms                                                      | 181 ms: 1.14x faster                                            |
| aiohttp                  | 961 us                                                      | 849 us: 1.13x faster                                            |
| regex_dna                | 129 ms                                                      | 115 ms: 1.12x faster                                            |
| deepcopy                 | 259 us                                                      | 231 us: 1.12x faster                                            |
| nqueens                  | 68.3 ms                                                     | 61.6 ms: 1.11x faster                                           |
| unpickle                 | 9.11 us                                                     | 8.23 us: 1.11x faster                                           |
| create_gc_cycles         | 800 us                                                      | 724 us: 1.10x faster                                            |
| coroutines               | 15.5 ms                                                     | 14.0 ms: 1.10x faster                                           |
| deepcopy_reduce          | 2.22 us                                                     | 2.03 us: 1.09x faster                                           |
| bench_thread_pool        | 913 us                                                      | 836 us: 1.09x faster                                            |
| sqlite_synth             | 1.90 us                                                     | 1.75 us: 1.08x faster                                           |
| json                     | 3.10 ms                                                     | 2.91 ms: 1.07x faster                                           |
| json_loads               | 14.2 us                                                     | 13.4 us: 1.06x faster                                           |
| xml_etree_parse          | 96.8 ms                                                     | 91.5 ms: 1.06x faster                                           |
| scimark_fft              | 187 ms                                                      | 177 ms: 1.06x faster                                            |
| scimark_sparse_mat_mult  | 2.67 ms                                                     | 2.53 ms: 1.05x faster                                           |
| fannkuch                 | 258 ms                                                      | 248 ms: 1.04x faster                                            |
| python_startup           | 19.7 ms                                                     | 19.1 ms: 1.03x faster                                           |
| regex_effbot             | 1.56 ms                                                     | 1.57 ms: 1.01x slower                                           |
| xml_etree_generate       | 54.5 ms                                                     | 55.0 ms: 1.01x slower                                           |
| logging_format           | 6.73 us                                                     | 6.88 us: 1.02x slower                                           |
| pickle                   | 6.87 us                                                     | 7.05 us: 1.02x slower                                           |
| pidigits                 | 146 ms                                                      | 150 ms: 1.03x slower                                            |
| logging_simple           | 6.28 us                                                     | 6.46 us: 1.03x slower                                           |
| nbody                    | 71.0 ms                                                     | 74.4 ms: 1.05x slower                                           |
| async_generators         | 219 ms                                                      | 230 ms: 1.05x slower                                            |
| gc_traversal             | 1.40 ms                                                     | 1.49 ms: 1.06x slower                                           |
| python_startup_no_site   | 15.3 ms                                                     | 16.4 ms: 1.07x slower                                           |
| pathlib                  | 72.8 ms                                                     | 78.0 ms: 1.07x slower                                           |
| pickle_list              | 2.69 us                                                     | 2.89 us: 1.07x slower                                           |
| pickle_dict              | 17.1 us                                                     | 18.4 us: 1.08x slower                                           |
| telco                    | 3.82 ms                                                     | 4.11 ms: 1.08x slower                                           |
| unpickle_list            | 2.68 us                                                     | 2.90 us: 1.08x slower                                           |
| bench_mp_pool            | 59.9 ms                                                     | 65.4 ms: 1.09x slower                                           |
| unpack_sequence          | 40.0 ns                                                     | 44.7 ns: 1.12x slower                                           |
| dask                     | 305 ms                                                      | 359 ms: 1.18x slower                                            |
| coverage                 | 38.4 ms                                                     | 52.7 ms: 1.37x slower                                           |
| Geometric mean           | (ref)                                                       | 1.18x faster                                                    |

Benchmark hidden because not significant (3): asyncio_tcp_ssl, meteor_contest, xml_etree_iterparse
Ignored benchmarks (14) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120.json: chameleon, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.14x
- 95% likely to have a speedup of 1.14x
- 99% likely to have a speedup of 1.12x
