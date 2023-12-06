
# Results vs. 3.10.4

- fork: python
- ref: 3.12
- machine: windows-amd64
- commit hash: dcaacd9
- commit date: 2023-09-03
- overall geometric mean: 1.17x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.09x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230903-pythonperf1-amd64-python-3.12-3.12.0rc1+-dcaacd9 |
|----------------|:-----------------------------------------------------------:|:------------------------------------------------------------:|
| 2to3           | 237 ms                                                      | 214 ms: 1.11x faster                                         |
| docutils       | 1.89 sec                                                    | 1.64 sec: 1.16x faster                                       |
| tornado_http   | 109 ms                                                      | 88.3 ms: 1.24x faster                                        |
| Geometric mean | (ref)                                                       | 1.17x faster                                                 |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230903-pythonperf1-amd64-python-3.12-3.12.0rc1+-dcaacd9 |
|----------------|:-----------------------------------------------------------:|:------------------------------------------------------------:|
| float          | 60.2 ms                                                     | 55.9 ms: 1.08x faster                                        |
| nbody          | 69.3 ms                                                     | 70.9 ms: 1.02x slower                                        |
| pidigits       | 145 ms                                                      | 150 ms: 1.03x slower                                         |
| Geometric mean | (ref)                                                       | 1.01x faster                                                 |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230903-pythonperf1-amd64-python-3.12-3.12.0rc1+-dcaacd9 |
|----------------|:-----------------------------------------------------------:|:------------------------------------------------------------:|
| regex_compile  | 103 ms                                                      | 87.3 ms: 1.19x faster                                        |
| regex_v8       | 15.0 ms                                                     | 14.1 ms: 1.06x faster                                        |
| regex_dna      | 132 ms                                                      | 124 ms: 1.06x faster                                         |
| regex_effbot   | 1.66 ms                                                     | 1.61 ms: 1.03x faster                                        |
| Geometric mean | (ref)                                                       | 1.08x faster                                                 |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230903-pythonperf1-amd64-python-3.12-3.12.0rc1+-dcaacd9 |
|----------------------|:-----------------------------------------------------------:|:------------------------------------------------------------:|
| json_dumps           | 8.50 ms                                                     | 5.65 ms: 1.50x faster                                        |
| pickle_pure_python   | 257 us                                                      | 196 us: 1.31x faster                                         |
| unpickle_pure_python | 171 us                                                      | 135 us: 1.27x faster                                         |
| tomli_loads          | 1.62 sec                                                    | 1.36 sec: 1.19x faster                                       |
| xml_etree_process    | 43.4 ms                                                     | 37.9 ms: 1.15x faster                                        |
| xml_etree_parse      | 102 ms                                                      | 90.0 ms: 1.13x faster                                        |
| unpickle             | 9.17 us                                                     | 8.19 us: 1.12x faster                                        |
| json_loads           | 14.2 us                                                     | 13.5 us: 1.05x faster                                        |
| xml_etree_iterparse  | 63.5 ms                                                     | 62.8 ms: 1.01x faster                                        |
| xml_etree_generate   | 54.5 ms                                                     | 55.5 ms: 1.02x slower                                        |
| pickle               | 6.80 us                                                     | 7.20 us: 1.06x slower                                        |
| pickle_dict          | 16.9 us                                                     | 18.2 us: 1.08x slower                                        |
| pickle_list          | 2.59 us                                                     | 2.80 us: 1.08x slower                                        |
| Geometric mean       | (ref)                                                       | 1.10x faster                                                 |

Benchmark hidden because not significant (1): unpickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230903-pythonperf1-amd64-python-3.12-3.12.0rc1+-dcaacd9 |
|------------------------|:-----------------------------------------------------------:|:------------------------------------------------------------:|
| python_startup         | 20.0 ms                                                     | 19.3 ms: 1.03x faster                                        |
| python_startup_no_site | 15.5 ms                                                     | 16.3 ms: 1.05x slower                                        |
| Geometric mean         | (ref)                                                       | 1.01x slower                                                 |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230903-pythonperf1-amd64-python-3.12-3.12.0rc1+-dcaacd9 |
|-----------|:-----------------------------------------------------------:|:------------------------------------------------------------:|
| mako      | 8.80 ms                                                     | 6.92 ms: 1.27x faster                                        |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230903-pythonperf1-amd64-python-3.12-3.12.0rc1+-dcaacd9 |
|--------------------------|:-----------------------------------------------------------:|:------------------------------------------------------------:|
| typing_runtime_protocols | 325 us                                                      | 97.6 us: 3.33x faster                                        |
| deltablue                | 4.17 ms                                                     | 2.13 ms: 1.96x faster                                        |
| richards_super           | 51.7 ms                                                     | 29.8 ms: 1.74x faster                                        |
| mypy2                    | 352 ms                                                      | 209 ms: 1.68x faster                                         |
| logging_silent           | 96.4 ns                                                     | 60.3 ns: 1.60x faster                                        |
| richards                 | 41.2 ms                                                     | 26.1 ms: 1.57x faster                                        |
| go                       | 136 ms                                                      | 87.8 ms: 1.55x faster                                        |
| asyncio_tcp              | 712 ms                                                      | 472 ms: 1.51x faster                                         |
| json_dumps               | 8.50 ms                                                     | 5.65 ms: 1.50x faster                                        |
| sqlglot_parse            | 1.22 ms                                                     | 813 us: 1.50x faster                                         |
| async_tree_io            | 1.07 sec                                                    | 720 ms: 1.48x faster                                         |
| async_tree_memoization   | 497 ms                                                      | 339 ms: 1.47x faster                                         |
| async_tree_none          | 420 ms                                                      | 289 ms: 1.45x faster                                         |
| scimark_lu               | 85.4 ms                                                     | 59.3 ms: 1.44x faster                                        |
| sqlglot_transpile        | 1.46 ms                                                     | 1.03 ms: 1.41x faster                                        |
| raytrace                 | 271 ms                                                      | 192 ms: 1.41x faster                                         |
| generators               | 31.6 ms                                                     | 22.4 ms: 1.41x faster                                        |
| chaos                    | 58.9 ms                                                     | 43.0 ms: 1.37x faster                                        |
| hexiom                   | 5.52 ms                                                     | 4.04 ms: 1.37x faster                                        |
| scimark_sor              | 105 ms                                                      | 78.1 ms: 1.34x faster                                        |
| crypto_pyaes             | 62.3 ms                                                     | 47.4 ms: 1.31x faster                                        |
| pyflate                  | 387 ms                                                      | 294 ms: 1.31x faster                                         |
| pickle_pure_python       | 257 us                                                      | 196 us: 1.31x faster                                         |
| mako                     | 8.80 ms                                                     | 6.92 ms: 1.27x faster                                        |
| unpickle_pure_python     | 171 us                                                      | 135 us: 1.27x faster                                         |
| async_tree_cpu_io_mixed  | 609 ms                                                      | 480 ms: 1.27x faster                                         |
| pycparser                | 868 ms                                                      | 693 ms: 1.25x faster                                         |
| scimark_monte_carlo      | 55.9 ms                                                     | 44.7 ms: 1.25x faster                                        |
| spectral_norm            | 78.0 ms                                                     | 63.1 ms: 1.24x faster                                        |
| tornado_http             | 109 ms                                                      | 88.3 ms: 1.24x faster                                        |
| deepcopy_memo            | 28.5 us                                                     | 23.8 us: 1.20x faster                                        |
| tomli_loads              | 1.62 sec                                                    | 1.36 sec: 1.19x faster                                       |
| regex_compile            | 103 ms                                                      | 87.3 ms: 1.19x faster                                        |
| aiohttp                  | 1.01 ms                                                     | 853 us: 1.18x faster                                         |
| docutils                 | 1.89 sec                                                    | 1.64 sec: 1.16x faster                                       |
| pprint_pformat           | 1.21 sec                                                    | 1.05 sec: 1.15x faster                                       |
| xml_etree_process        | 43.4 ms                                                     | 37.9 ms: 1.15x faster                                        |
| pprint_safe_repr         | 589 ms                                                      | 515 ms: 1.14x faster                                         |
| mdp                      | 1.71 sec                                                    | 1.50 sec: 1.14x faster                                       |
| xml_etree_parse          | 102 ms                                                      | 90.0 ms: 1.13x faster                                        |
| bench_thread_pool        | 946 us                                                      | 842 us: 1.12x faster                                         |
| dulwich_log              | 47.6 ms                                                     | 42.4 ms: 1.12x faster                                        |
| sqlglot_optimize         | 39.0 ms                                                     | 34.7 ms: 1.12x faster                                        |
| unpickle                 | 9.17 us                                                     | 8.19 us: 1.12x faster                                        |
| comprehensions           | 16.0 us                                                     | 14.4 us: 1.11x faster                                        |
| 2to3                     | 237 ms                                                      | 214 ms: 1.11x faster                                         |
| coroutines               | 15.9 ms                                                     | 14.4 ms: 1.10x faster                                        |
| scimark_fft              | 193 ms                                                      | 177 ms: 1.09x faster                                         |
| nqueens                  | 67.0 ms                                                     | 62.1 ms: 1.08x faster                                        |
| float                    | 60.2 ms                                                     | 55.9 ms: 1.08x faster                                        |
| create_gc_cycles         | 782 us                                                      | 727 us: 1.08x faster                                         |
| sqlglot_normalize        | 202 ms                                                      | 188 ms: 1.07x faster                                         |
| scimark_sparse_mat_mult  | 2.66 ms                                                     | 2.50 ms: 1.07x faster                                        |
| regex_v8                 | 15.0 ms                                                     | 14.1 ms: 1.06x faster                                        |
| regex_dna                | 132 ms                                                      | 124 ms: 1.06x faster                                         |
| fannkuch                 | 258 ms                                                      | 243 ms: 1.06x faster                                         |
| deepcopy                 | 255 us                                                      | 243 us: 1.05x faster                                         |
| sqlite_synth             | 1.84 us                                                     | 1.75 us: 1.05x faster                                        |
| json_loads               | 14.2 us                                                     | 13.5 us: 1.05x faster                                        |
| json                     | 3.05 ms                                                     | 2.93 ms: 1.04x faster                                        |
| unpack_sequence          | 37.8 ns                                                     | 36.5 ns: 1.04x faster                                        |
| python_startup           | 20.0 ms                                                     | 19.3 ms: 1.03x faster                                        |
| regex_effbot             | 1.66 ms                                                     | 1.61 ms: 1.03x faster                                        |
| xml_etree_iterparse      | 63.5 ms                                                     | 62.8 ms: 1.01x faster                                        |
| deepcopy_reduce          | 2.16 us                                                     | 2.14 us: 1.01x faster                                        |
| logging_format           | 6.66 us                                                     | 6.73 us: 1.01x slower                                        |
| logging_simple           | 6.20 us                                                     | 6.29 us: 1.01x slower                                        |
| xml_etree_generate       | 54.5 ms                                                     | 55.5 ms: 1.02x slower                                        |
| pathlib                  | 77.4 ms                                                     | 78.7 ms: 1.02x slower                                        |
| nbody                    | 69.3 ms                                                     | 70.9 ms: 1.02x slower                                        |
| pidigits                 | 145 ms                                                      | 150 ms: 1.03x slower                                         |
| python_startup_no_site   | 15.5 ms                                                     | 16.3 ms: 1.05x slower                                        |
| pickle                   | 6.80 us                                                     | 7.20 us: 1.06x slower                                        |
| async_generators         | 224 ms                                                      | 238 ms: 1.06x slower                                         |
| telco                    | 3.78 ms                                                     | 4.05 ms: 1.07x slower                                        |
| pickle_dict              | 16.9 us                                                     | 18.2 us: 1.08x slower                                        |
| pickle_list              | 2.59 us                                                     | 2.80 us: 1.08x slower                                        |
| gc_traversal             | 1.34 ms                                                     | 1.48 ms: 1.10x slower                                        |
| bench_mp_pool            | 60.7 ms                                                     | 67.0 ms: 1.10x slower                                        |
| dask                     | 305 ms                                                      | 361 ms: 1.19x slower                                         |
| coverage                 | 40.0 ms                                                     | 50.3 ms: 1.26x slower                                        |
| Geometric mean           | (ref)                                                       | 1.17x faster                                                 |

Benchmark hidden because not significant (3): asyncio_tcp_ssl, unpickle_list, meteor_contest
Ignored benchmarks (14) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120.json: chameleon, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.12x
- 95% likely to have a speedup of 1.11x
- 99% likely to have a speedup of 1.09x
