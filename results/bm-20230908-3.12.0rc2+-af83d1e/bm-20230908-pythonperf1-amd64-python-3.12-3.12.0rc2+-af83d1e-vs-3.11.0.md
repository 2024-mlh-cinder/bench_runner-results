
# Results vs. 3.11.0

- fork: python
- ref: 3.12
- machine: windows-amd64
- commit hash: af83d1e
- commit date: 2023-09-08
- overall geometric mean: 1.06x faster
- HPT reliability: 99.99%
- HPT 99th percentile: 1.01x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230908-pythonperf1-amd64-python-3.12-3.12.0rc2+-af83d1e |
|----------------|:-----------------------------------------------------------:|:------------------------------------------------------------:|
| 2to3           | 209 ms                                                      | 213 ms: 1.02x slower                                         |
| docutils       | 1.60 sec                                                    | 1.64 sec: 1.02x slower                                       |
| tornado_http   | 91.8 ms                                                     | 87.4 ms: 1.05x faster                                        |
| Geometric mean | (ref)                                                       | 1.00x faster                                                 |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230908-pythonperf1-amd64-python-3.12-3.12.0rc2+-af83d1e |
|----------------|:-----------------------------------------------------------:|:------------------------------------------------------------:|
| nbody          | 70.0 ms                                                     | 69.0 ms: 1.01x faster                                        |
| float          | 54.6 ms                                                     | 54.2 ms: 1.01x faster                                        |
| pidigits       | 148 ms                                                      | 150 ms: 1.01x slower                                         |
| Geometric mean | (ref)                                                       | 1.00x faster                                                 |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230908-pythonperf1-amd64-python-3.12-3.12.0rc2+-af83d1e |
|----------------|:-----------------------------------------------------------:|:------------------------------------------------------------:|
| regex_compile  | 90.6 ms                                                     | 86.3 ms: 1.05x faster                                        |
| regex_v8       | 13.8 ms                                                     | 13.7 ms: 1.01x faster                                        |
| regex_dna      | 115 ms                                                      | 121 ms: 1.05x slower                                         |
| regex_effbot   | 1.50 ms                                                     | 1.59 ms: 1.06x slower                                        |
| Geometric mean | (ref)                                                       | 1.01x slower                                                 |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230908-pythonperf1-amd64-python-3.12-3.12.0rc2+-af83d1e |
|----------------------|:-----------------------------------------------------------:|:------------------------------------------------------------:|
| json_dumps           | 7.56 ms                                                     | 5.70 ms: 1.33x faster                                        |
| unpickle_pure_python | 152 us                                                      | 133 us: 1.14x faster                                         |
| xml_etree_parse      | 95.9 ms                                                     | 89.8 ms: 1.07x faster                                        |
| tomli_loads          | 1.41 sec                                                    | 1.37 sec: 1.03x faster                                       |
| pickle_pure_python   | 200 us                                                      | 195 us: 1.03x faster                                         |
| unpickle             | 8.09 us                                                     | 8.21 us: 1.01x slower                                        |
| xml_etree_process    | 37.1 ms                                                     | 37.6 ms: 1.01x slower                                        |
| json_loads           | 12.9 us                                                     | 13.5 us: 1.05x slower                                        |
| pickle_list          | 2.68 us                                                     | 2.81 us: 1.05x slower                                        |
| xml_etree_generate   | 52.2 ms                                                     | 55.0 ms: 1.05x slower                                        |
| unpickle_list        | 2.55 us                                                     | 2.69 us: 1.06x slower                                        |
| pickle               | 6.61 us                                                     | 7.17 us: 1.08x slower                                        |
| Geometric mean       | (ref)                                                       | 1.02x faster                                                 |

Benchmark hidden because not significant (2): xml_etree_iterparse, pickle_dict

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230908-pythonperf1-amd64-python-3.12-3.12.0rc2+-af83d1e |
|------------------------|:-----------------------------------------------------------:|:------------------------------------------------------------:|
| python_startup         | 18.7 ms                                                     | 19.3 ms: 1.03x slower                                        |
| python_startup_no_site | 15.9 ms                                                     | 16.4 ms: 1.03x slower                                        |
| Geometric mean         | (ref)                                                       | 1.03x slower                                                 |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230908-pythonperf1-amd64-python-3.12-3.12.0rc2+-af83d1e |
|-----------|:-----------------------------------------------------------:|:------------------------------------------------------------:|
| mako      | 7.26 ms                                                     | 6.87 ms: 1.06x faster                                        |

All benchmarks:
===============

| Benchmark                | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230908-pythonperf1-amd64-python-3.12-3.12.0rc2+-af83d1e |
|--------------------------|:-----------------------------------------------------------:|:------------------------------------------------------------:|
| typing_runtime_protocols | 322 us                                                      | 96.2 us: 3.34x faster                                        |
| generators               | 33.8 ms                                                     | 22.5 ms: 1.50x faster                                        |
| asyncio_tcp              | 699 ms                                                      | 472 ms: 1.48x faster                                         |
| json_dumps               | 7.56 ms                                                     | 5.70 ms: 1.33x faster                                        |
| richards_super           | 37.5 ms                                                     | 30.1 ms: 1.24x faster                                        |
| unpack_sequence          | 46.1 ns                                                     | 37.6 ns: 1.22x faster                                        |
| deltablue                | 2.61 ms                                                     | 2.16 ms: 1.21x faster                                        |
| mdp                      | 1.67 sec                                                    | 1.40 sec: 1.20x faster                                       |
| sqlglot_parse            | 952 us                                                      | 806 us: 1.18x faster                                         |
| logging_silent           | 69.8 ns                                                     | 60.2 ns: 1.16x faster                                        |
| richards                 | 30.6 ms                                                     | 26.7 ms: 1.14x faster                                        |
| unpickle_pure_python     | 152 us                                                      | 133 us: 1.14x faster                                         |
| sqlglot_transpile        | 1.16 ms                                                     | 1.02 ms: 1.14x faster                                        |
| hexiom                   | 4.55 ms                                                     | 4.03 ms: 1.13x faster                                        |
| go                       | 97.3 ms                                                     | 86.7 ms: 1.12x faster                                        |
| comprehensions           | 15.9 us                                                     | 14.2 us: 1.12x faster                                        |
| raytrace                 | 211 ms                                                      | 188 ms: 1.12x faster                                         |
| json                     | 3.25 ms                                                     | 2.91 ms: 1.12x faster                                        |
| coverage                 | 55.9 ms                                                     | 50.1 ms: 1.11x faster                                        |
| scimark_lu               | 63.5 ms                                                     | 57.3 ms: 1.11x faster                                        |
| asyncio_tcp_ssl          | 2.11 sec                                                    | 1.90 sec: 1.11x faster                                       |
| chaos                    | 47.1 ms                                                     | 42.5 ms: 1.11x faster                                        |
| async_tree_none          | 320 ms                                                      | 289 ms: 1.11x faster                                         |
| async_tree_memoization   | 371 ms                                                      | 336 ms: 1.10x faster                                         |
| mypy2                    | 229 ms                                                      | 208 ms: 1.10x faster                                         |
| async_tree_io            | 779 ms                                                      | 723 ms: 1.08x faster                                         |
| fannkuch                 | 252 ms                                                      | 234 ms: 1.08x faster                                         |
| xml_etree_parse          | 95.9 ms                                                     | 89.8 ms: 1.07x faster                                        |
| spectral_norm            | 67.9 ms                                                     | 64.0 ms: 1.06x faster                                        |
| mako                     | 7.26 ms                                                     | 6.87 ms: 1.06x faster                                        |
| nqueens                  | 64.9 ms                                                     | 61.5 ms: 1.05x faster                                        |
| scimark_monte_carlo      | 44.6 ms                                                     | 42.4 ms: 1.05x faster                                        |
| aiohttp                  | 899 us                                                      | 854 us: 1.05x faster                                         |
| tornado_http             | 91.8 ms                                                     | 87.4 ms: 1.05x faster                                        |
| regex_compile            | 90.6 ms                                                     | 86.3 ms: 1.05x faster                                        |
| dulwich_log              | 44.5 ms                                                     | 42.5 ms: 1.05x faster                                        |
| async_tree_cpu_io_mixed  | 501 ms                                                      | 478 ms: 1.05x faster                                         |
| logging_simple           | 6.61 us                                                     | 6.32 us: 1.05x faster                                        |
| coroutines               | 14.6 ms                                                     | 14.0 ms: 1.05x faster                                        |
| deepcopy_memo            | 25.2 us                                                     | 24.1 us: 1.04x faster                                        |
| logging_format           | 7.01 us                                                     | 6.74 us: 1.04x faster                                        |
| pyflate                  | 304 ms                                                      | 293 ms: 1.04x faster                                         |
| meteor_contest           | 74.7 ms                                                     | 72.1 ms: 1.04x faster                                        |
| deepcopy                 | 246 us                                                      | 237 us: 1.04x faster                                         |
| scimark_sparse_mat_mult  | 2.57 ms                                                     | 2.48 ms: 1.04x faster                                        |
| tomli_loads              | 1.41 sec                                                    | 1.37 sec: 1.03x faster                                       |
| sqlglot_normalize        | 190 ms                                                      | 185 ms: 1.03x faster                                         |
| pickle_pure_python       | 200 us                                                      | 195 us: 1.03x faster                                         |
| pprint_safe_repr         | 512 ms                                                      | 500 ms: 1.02x faster                                         |
| scimark_fft              | 178 ms                                                      | 175 ms: 1.02x faster                                         |
| pprint_pformat           | 1.04 sec                                                    | 1.02 sec: 1.02x faster                                       |
| nbody                    | 70.0 ms                                                     | 69.0 ms: 1.01x faster                                        |
| pycparser                | 691 ms                                                      | 682 ms: 1.01x faster                                         |
| crypto_pyaes             | 47.6 ms                                                     | 47.0 ms: 1.01x faster                                        |
| sqlglot_optimize         | 34.9 ms                                                     | 34.6 ms: 1.01x faster                                        |
| float                    | 54.6 ms                                                     | 54.2 ms: 1.01x faster                                        |
| regex_v8                 | 13.8 ms                                                     | 13.7 ms: 1.01x faster                                        |
| pidigits                 | 148 ms                                                      | 150 ms: 1.01x slower                                         |
| unpickle                 | 8.09 us                                                     | 8.21 us: 1.01x slower                                        |
| xml_etree_process        | 37.1 ms                                                     | 37.6 ms: 1.01x slower                                        |
| 2to3                     | 209 ms                                                      | 213 ms: 1.02x slower                                         |
| gc_traversal             | 1.46 ms                                                     | 1.49 ms: 1.02x slower                                        |
| docutils                 | 1.60 sec                                                    | 1.64 sec: 1.02x slower                                       |
| scimark_sor              | 75.6 ms                                                     | 77.9 ms: 1.03x slower                                        |
| python_startup           | 18.7 ms                                                     | 19.3 ms: 1.03x slower                                        |
| python_startup_no_site   | 15.9 ms                                                     | 16.4 ms: 1.03x slower                                        |
| sqlite_synth             | 1.68 us                                                     | 1.75 us: 1.04x slower                                        |
| telco                    | 3.90 ms                                                     | 4.07 ms: 1.04x slower                                        |
| create_gc_cycles         | 693 us                                                      | 723 us: 1.04x slower                                         |
| json_loads               | 12.9 us                                                     | 13.5 us: 1.05x slower                                        |
| pickle_list              | 2.68 us                                                     | 2.81 us: 1.05x slower                                        |
| regex_dna                | 115 ms                                                      | 121 ms: 1.05x slower                                         |
| xml_etree_generate       | 52.2 ms                                                     | 55.0 ms: 1.05x slower                                        |
| unpickle_list            | 2.55 us                                                     | 2.69 us: 1.06x slower                                        |
| regex_effbot             | 1.50 ms                                                     | 1.59 ms: 1.06x slower                                        |
| bench_mp_pool            | 62.5 ms                                                     | 67.2 ms: 1.08x slower                                        |
| pickle                   | 6.61 us                                                     | 7.17 us: 1.08x slower                                        |
| pathlib                  | 71.4 ms                                                     | 78.9 ms: 1.11x slower                                        |
| async_generators         | 178 ms                                                      | 234 ms: 1.32x slower                                         |
| dask                     | 264 ms                                                      | 361 ms: 1.36x slower                                         |
| Geometric mean           | (ref)                                                       | 1.06x faster                                                 |

Benchmark hidden because not significant (4): bench_thread_pool, deepcopy_reduce, xml_etree_iterparse, pickle_dict
Ignored benchmarks (14) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509.json: chameleon, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 99.99% likely to be faster
- 90% likely to have a speedup of 1.02x
- 95% likely to have a speedup of 1.02x
- 99% likely to have a speedup of 1.01x
