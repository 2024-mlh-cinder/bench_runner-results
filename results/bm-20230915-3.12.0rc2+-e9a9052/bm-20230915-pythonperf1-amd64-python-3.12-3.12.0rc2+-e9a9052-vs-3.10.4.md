
# Results vs. 3.10.4

- fork: python
- ref: 3.12
- machine: windows-amd64
- commit hash: e9a9052
- commit date: 2023-09-15
- overall geometric mean: 1.16x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.09x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230915-pythonperf1-amd64-python-3.12-3.12.0rc2+-e9a9052 |
|----------------|:-----------------------------------------------------------:|:------------------------------------------------------------:|
| 2to3           | 237 ms                                                      | 214 ms: 1.10x faster                                         |
| docutils       | 1.89 sec                                                    | 1.64 sec: 1.16x faster                                       |
| tornado_http   | 109 ms                                                      | 87.9 ms: 1.24x faster                                        |
| Geometric mean | (ref)                                                       | 1.17x faster                                                 |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230915-pythonperf1-amd64-python-3.12-3.12.0rc2+-e9a9052 |
|----------------|:-----------------------------------------------------------:|:------------------------------------------------------------:|
| float          | 60.2 ms                                                     | 56.6 ms: 1.06x faster                                        |
| nbody          | 69.3 ms                                                     | 71.4 ms: 1.03x slower                                        |
| pidigits       | 145 ms                                                      | 150 ms: 1.03x slower                                         |
| Geometric mean | (ref)                                                       | 1.00x slower                                                 |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230915-pythonperf1-amd64-python-3.12-3.12.0rc2+-e9a9052 |
|----------------|:-----------------------------------------------------------:|:------------------------------------------------------------:|
| regex_compile  | 103 ms                                                      | 88.9 ms: 1.16x faster                                        |
| regex_dna      | 132 ms                                                      | 118 ms: 1.12x faster                                         |
| regex_v8       | 15.0 ms                                                     | 14.1 ms: 1.07x faster                                        |
| regex_effbot   | 1.66 ms                                                     | 1.58 ms: 1.05x faster                                        |
| Geometric mean | (ref)                                                       | 1.10x faster                                                 |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230915-pythonperf1-amd64-python-3.12-3.12.0rc2+-e9a9052 |
|----------------------|:-----------------------------------------------------------:|:------------------------------------------------------------:|
| json_dumps           | 8.50 ms                                                     | 5.79 ms: 1.47x faster                                        |
| pickle_pure_python   | 257 us                                                      | 200 us: 1.28x faster                                         |
| unpickle_pure_python | 171 us                                                      | 140 us: 1.22x faster                                         |
| tomli_loads          | 1.62 sec                                                    | 1.42 sec: 1.15x faster                                       |
| xml_etree_process    | 43.4 ms                                                     | 38.8 ms: 1.12x faster                                        |
| xml_etree_parse      | 102 ms                                                      | 91.7 ms: 1.11x faster                                        |
| unpickle             | 9.17 us                                                     | 8.32 us: 1.10x faster                                        |
| unpickle_list        | 2.81 us                                                     | 2.67 us: 1.05x faster                                        |
| json_loads           | 14.2 us                                                     | 13.6 us: 1.04x faster                                        |
| xml_etree_generate   | 54.5 ms                                                     | 57.2 ms: 1.05x slower                                        |
| pickle               | 6.80 us                                                     | 7.17 us: 1.05x slower                                        |
| pickle_dict          | 16.9 us                                                     | 18.7 us: 1.10x slower                                        |
| pickle_list          | 2.59 us                                                     | 2.88 us: 1.11x slower                                        |
| Geometric mean       | (ref)                                                       | 1.08x faster                                                 |

Benchmark hidden because not significant (1): xml_etree_iterparse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230915-pythonperf1-amd64-python-3.12-3.12.0rc2+-e9a9052 |
|------------------------|:-----------------------------------------------------------:|:------------------------------------------------------------:|
| python_startup         | 20.0 ms                                                     | 18.9 ms: 1.06x faster                                        |
| python_startup_no_site | 15.5 ms                                                     | 15.9 ms: 1.02x slower                                        |
| Geometric mean         | (ref)                                                       | 1.02x faster                                                 |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230915-pythonperf1-amd64-python-3.12-3.12.0rc2+-e9a9052 |
|-----------|:-----------------------------------------------------------:|:------------------------------------------------------------:|
| mako      | 8.80 ms                                                     | 7.03 ms: 1.25x faster                                        |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230915-pythonperf1-amd64-python-3.12-3.12.0rc2+-e9a9052 |
|--------------------------|:-----------------------------------------------------------:|:------------------------------------------------------------:|
| typing_runtime_protocols | 325 us                                                      | 98.4 us: 3.30x faster                                        |
| deltablue                | 4.17 ms                                                     | 2.18 ms: 1.92x faster                                        |
| mypy2                    | 352 ms                                                      | 209 ms: 1.69x faster                                         |
| richards_super           | 51.7 ms                                                     | 31.1 ms: 1.66x faster                                        |
| logging_silent           | 96.4 ns                                                     | 60.7 ns: 1.59x faster                                        |
| go                       | 136 ms                                                      | 90.6 ms: 1.50x faster                                        |
| richards                 | 41.2 ms                                                     | 27.6 ms: 1.49x faster                                        |
| asyncio_tcp              | 712 ms                                                      | 478 ms: 1.49x faster                                         |
| async_tree_memoization   | 497 ms                                                      | 338 ms: 1.47x faster                                         |
| async_tree_io            | 1.07 sec                                                    | 725 ms: 1.47x faster                                         |
| json_dumps               | 8.50 ms                                                     | 5.79 ms: 1.47x faster                                        |
| sqlglot_parse            | 1.22 ms                                                     | 836 us: 1.46x faster                                         |
| scimark_lu               | 85.4 ms                                                     | 58.8 ms: 1.45x faster                                        |
| async_tree_none          | 420 ms                                                      | 292 ms: 1.44x faster                                         |
| raytrace                 | 271 ms                                                      | 192 ms: 1.41x faster                                         |
| generators               | 31.6 ms                                                     | 22.5 ms: 1.40x faster                                        |
| sqlglot_transpile        | 1.46 ms                                                     | 1.06 ms: 1.38x faster                                        |
| chaos                    | 58.9 ms                                                     | 43.8 ms: 1.35x faster                                        |
| hexiom                   | 5.52 ms                                                     | 4.21 ms: 1.31x faster                                        |
| pyflate                  | 387 ms                                                      | 301 ms: 1.29x faster                                         |
| crypto_pyaes             | 62.3 ms                                                     | 48.5 ms: 1.29x faster                                        |
| pickle_pure_python       | 257 us                                                      | 200 us: 1.28x faster                                         |
| async_tree_cpu_io_mixed  | 609 ms                                                      | 480 ms: 1.27x faster                                         |
| mako                     | 8.80 ms                                                     | 7.03 ms: 1.25x faster                                        |
| pycparser                | 868 ms                                                      | 693 ms: 1.25x faster                                         |
| scimark_sor              | 105 ms                                                      | 84.3 ms: 1.24x faster                                        |
| tornado_http             | 109 ms                                                      | 87.9 ms: 1.24x faster                                        |
| scimark_monte_carlo      | 55.9 ms                                                     | 45.5 ms: 1.23x faster                                        |
| unpickle_pure_python     | 171 us                                                      | 140 us: 1.22x faster                                         |
| spectral_norm            | 78.0 ms                                                     | 64.8 ms: 1.20x faster                                        |
| aiohttp                  | 1.01 ms                                                     | 865 us: 1.16x faster                                         |
| regex_compile            | 103 ms                                                      | 88.9 ms: 1.16x faster                                        |
| docutils                 | 1.89 sec                                                    | 1.64 sec: 1.16x faster                                       |
| deepcopy_memo            | 28.5 us                                                     | 24.7 us: 1.15x faster                                        |
| mdp                      | 1.71 sec                                                    | 1.48 sec: 1.15x faster                                       |
| tomli_loads              | 1.62 sec                                                    | 1.42 sec: 1.15x faster                                       |
| bench_thread_pool        | 946 us                                                      | 830 us: 1.14x faster                                         |
| coroutines               | 15.9 ms                                                     | 14.0 ms: 1.14x faster                                        |
| sqlglot_optimize         | 39.0 ms                                                     | 34.6 ms: 1.13x faster                                        |
| regex_dna                | 132 ms                                                      | 118 ms: 1.12x faster                                         |
| pprint_pformat           | 1.21 sec                                                    | 1.08 sec: 1.12x faster                                       |
| xml_etree_process        | 43.4 ms                                                     | 38.8 ms: 1.12x faster                                        |
| pprint_safe_repr         | 589 ms                                                      | 529 ms: 1.11x faster                                         |
| dulwich_log              | 47.6 ms                                                     | 42.8 ms: 1.11x faster                                        |
| xml_etree_parse          | 102 ms                                                      | 91.7 ms: 1.11x faster                                        |
| 2to3                     | 237 ms                                                      | 214 ms: 1.10x faster                                         |
| unpickle                 | 9.17 us                                                     | 8.32 us: 1.10x faster                                        |
| comprehensions           | 16.0 us                                                     | 14.8 us: 1.08x faster                                        |
| sqlglot_normalize        | 202 ms                                                      | 187 ms: 1.08x faster                                         |
| create_gc_cycles         | 782 us                                                      | 730 us: 1.07x faster                                         |
| regex_v8                 | 15.0 ms                                                     | 14.1 ms: 1.07x faster                                        |
| float                    | 60.2 ms                                                     | 56.6 ms: 1.06x faster                                        |
| nqueens                  | 67.0 ms                                                     | 63.4 ms: 1.06x faster                                        |
| python_startup           | 20.0 ms                                                     | 18.9 ms: 1.06x faster                                        |
| regex_effbot             | 1.66 ms                                                     | 1.58 ms: 1.05x faster                                        |
| unpickle_list            | 2.81 us                                                     | 2.67 us: 1.05x faster                                        |
| sqlite_synth             | 1.84 us                                                     | 1.76 us: 1.05x faster                                        |
| deepcopy                 | 255 us                                                      | 245 us: 1.04x faster                                         |
| json                     | 3.05 ms                                                     | 2.93 ms: 1.04x faster                                        |
| json_loads               | 14.2 us                                                     | 13.6 us: 1.04x faster                                        |
| scimark_fft              | 193 ms                                                      | 187 ms: 1.03x faster                                         |
| scimark_sparse_mat_mult  | 2.66 ms                                                     | 2.60 ms: 1.02x faster                                        |
| fannkuch                 | 258 ms                                                      | 254 ms: 1.01x faster                                         |
| meteor_contest           | 72.5 ms                                                     | 74.0 ms: 1.02x slower                                        |
| python_startup_no_site   | 15.5 ms                                                     | 15.9 ms: 1.02x slower                                        |
| nbody                    | 69.3 ms                                                     | 71.4 ms: 1.03x slower                                        |
| pidigits                 | 145 ms                                                      | 150 ms: 1.03x slower                                         |
| logging_format           | 6.66 us                                                     | 6.94 us: 1.04x slower                                        |
| logging_simple           | 6.20 us                                                     | 6.49 us: 1.05x slower                                        |
| async_generators         | 224 ms                                                      | 234 ms: 1.05x slower                                         |
| xml_etree_generate       | 54.5 ms                                                     | 57.2 ms: 1.05x slower                                        |
| pickle                   | 6.80 us                                                     | 7.17 us: 1.05x slower                                        |
| pickle_dict              | 16.9 us                                                     | 18.7 us: 1.10x slower                                        |
| bench_mp_pool            | 60.7 ms                                                     | 67.1 ms: 1.10x slower                                        |
| telco                    | 3.78 ms                                                     | 4.18 ms: 1.11x slower                                        |
| pickle_list              | 2.59 us                                                     | 2.88 us: 1.11x slower                                        |
| gc_traversal             | 1.34 ms                                                     | 1.50 ms: 1.12x slower                                        |
| dask                     | 305 ms                                                      | 364 ms: 1.19x slower                                         |
| coverage                 | 40.0 ms                                                     | 52.1 ms: 1.30x slower                                        |
| Geometric mean           | (ref)                                                       | 1.16x faster                                                 |

Benchmark hidden because not significant (5): asyncio_tcp_ssl, deepcopy_reduce, unpack_sequence, pathlib, xml_etree_iterparse
Ignored benchmarks (14) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120.json: chameleon, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.11x
- 95% likely to have a speedup of 1.10x
- 99% likely to have a speedup of 1.09x
