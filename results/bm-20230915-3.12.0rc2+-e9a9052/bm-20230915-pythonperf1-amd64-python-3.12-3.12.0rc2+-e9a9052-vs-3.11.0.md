
# Results vs. 3.11.0

- fork: python
- ref: 3.12
- machine: windows-amd64
- commit hash: e9a9052
- commit date: 2023-09-15
- overall geometric mean: 1.04x faster
- HPT reliability: 77.31%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230915-pythonperf1-amd64-python-3.12-3.12.0rc2+-e9a9052 |
|----------------|:-----------------------------------------------------------:|:------------------------------------------------------------:|
| 2to3           | 209 ms                                                      | 214 ms: 1.03x slower                                         |
| docutils       | 1.60 sec                                                    | 1.64 sec: 1.02x slower                                       |
| tornado_http   | 91.8 ms                                                     | 87.9 ms: 1.05x faster                                        |
| Geometric mean | (ref)                                                       | 1.00x slower                                                 |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230915-pythonperf1-amd64-python-3.12-3.12.0rc2+-e9a9052 |
|----------------|:-----------------------------------------------------------:|:------------------------------------------------------------:|
| pidigits       | 148 ms                                                      | 150 ms: 1.01x slower                                         |
| nbody          | 70.0 ms                                                     | 71.4 ms: 1.02x slower                                        |
| float          | 54.6 ms                                                     | 56.6 ms: 1.04x slower                                        |
| Geometric mean | (ref)                                                       | 1.02x slower                                                 |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230915-pythonperf1-amd64-python-3.12-3.12.0rc2+-e9a9052 |
|----------------|:-----------------------------------------------------------:|:------------------------------------------------------------:|
| regex_compile  | 90.6 ms                                                     | 88.9 ms: 1.02x faster                                        |
| regex_dna      | 115 ms                                                      | 118 ms: 1.02x slower                                         |
| regex_v8       | 13.8 ms                                                     | 14.1 ms: 1.02x slower                                        |
| regex_effbot   | 1.50 ms                                                     | 1.58 ms: 1.06x slower                                        |
| Geometric mean | (ref)                                                       | 1.02x slower                                                 |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230915-pythonperf1-amd64-python-3.12-3.12.0rc2+-e9a9052 |
|----------------------|:-----------------------------------------------------------:|:------------------------------------------------------------:|
| json_dumps           | 7.56 ms                                                     | 5.79 ms: 1.31x faster                                        |
| unpickle_pure_python | 152 us                                                      | 140 us: 1.08x faster                                         |
| xml_etree_parse      | 95.9 ms                                                     | 91.7 ms: 1.05x faster                                        |
| xml_etree_iterparse  | 62.6 ms                                                     | 63.9 ms: 1.02x slower                                        |
| unpickle             | 8.09 us                                                     | 8.32 us: 1.03x slower                                        |
| xml_etree_process    | 37.1 ms                                                     | 38.8 ms: 1.05x slower                                        |
| unpickle_list        | 2.55 us                                                     | 2.67 us: 1.05x slower                                        |
| json_loads           | 12.9 us                                                     | 13.6 us: 1.06x slower                                        |
| pickle_list          | 2.68 us                                                     | 2.88 us: 1.08x slower                                        |
| pickle               | 6.61 us                                                     | 7.17 us: 1.08x slower                                        |
| xml_etree_generate   | 52.2 ms                                                     | 57.2 ms: 1.10x slower                                        |
| Geometric mean       | (ref)                                                       | 1.00x slower                                                 |

Benchmark hidden because not significant (3): tomli_loads, pickle_pure_python, pickle_dict

Benchmarks with tag 'startup':
==============================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230915-pythonperf1-amd64-python-3.12-3.12.0rc2+-e9a9052 |
|----------------|:-----------------------------------------------------------:|:------------------------------------------------------------:|
| python_startup | 18.7 ms                                                     | 18.9 ms: 1.01x slower                                        |
| Geometric mean | (ref)                                                       | 1.01x slower                                                 |

Benchmark hidden because not significant (1): python_startup_no_site

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230915-pythonperf1-amd64-python-3.12-3.12.0rc2+-e9a9052 |
|-----------|:-----------------------------------------------------------:|:------------------------------------------------------------:|
| mako      | 7.26 ms                                                     | 7.03 ms: 1.03x faster                                        |

All benchmarks:
===============

| Benchmark                | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230915-pythonperf1-amd64-python-3.12-3.12.0rc2+-e9a9052 |
|--------------------------|:-----------------------------------------------------------:|:------------------------------------------------------------:|
| typing_runtime_protocols | 322 us                                                      | 98.4 us: 3.27x faster                                        |
| generators               | 33.8 ms                                                     | 22.5 ms: 1.50x faster                                        |
| asyncio_tcp              | 699 ms                                                      | 478 ms: 1.46x faster                                         |
| json_dumps               | 7.56 ms                                                     | 5.79 ms: 1.31x faster                                        |
| unpack_sequence          | 46.1 ns                                                     | 37.9 ns: 1.21x faster                                        |
| richards_super           | 37.5 ms                                                     | 31.1 ms: 1.21x faster                                        |
| deltablue                | 2.61 ms                                                     | 2.18 ms: 1.20x faster                                        |
| logging_silent           | 69.8 ns                                                     | 60.7 ns: 1.15x faster                                        |
| sqlglot_parse            | 952 us                                                      | 836 us: 1.14x faster                                         |
| mdp                      | 1.67 sec                                                    | 1.48 sec: 1.13x faster                                       |
| json                     | 3.25 ms                                                     | 2.93 ms: 1.11x faster                                        |
| richards                 | 30.6 ms                                                     | 27.6 ms: 1.11x faster                                        |
| sqlglot_transpile        | 1.16 ms                                                     | 1.06 ms: 1.10x faster                                        |
| async_tree_none          | 320 ms                                                      | 292 ms: 1.10x faster                                         |
| raytrace                 | 211 ms                                                      | 192 ms: 1.10x faster                                         |
| mypy2                    | 229 ms                                                      | 209 ms: 1.10x faster                                         |
| async_tree_memoization   | 371 ms                                                      | 338 ms: 1.10x faster                                         |
| hexiom                   | 4.55 ms                                                     | 4.21 ms: 1.08x faster                                        |
| unpickle_pure_python     | 152 us                                                      | 140 us: 1.08x faster                                         |
| scimark_lu               | 63.5 ms                                                     | 58.8 ms: 1.08x faster                                        |
| comprehensions           | 15.9 us                                                     | 14.8 us: 1.08x faster                                        |
| chaos                    | 47.1 ms                                                     | 43.8 ms: 1.08x faster                                        |
| go                       | 97.3 ms                                                     | 90.6 ms: 1.07x faster                                        |
| async_tree_io            | 779 ms                                                      | 725 ms: 1.07x faster                                         |
| coverage                 | 55.9 ms                                                     | 52.1 ms: 1.07x faster                                        |
| asyncio_tcp_ssl          | 2.11 sec                                                    | 1.99 sec: 1.06x faster                                       |
| spectral_norm            | 67.9 ms                                                     | 64.8 ms: 1.05x faster                                        |
| xml_etree_parse          | 95.9 ms                                                     | 91.7 ms: 1.05x faster                                        |
| tornado_http             | 91.8 ms                                                     | 87.9 ms: 1.05x faster                                        |
| async_tree_cpu_io_mixed  | 501 ms                                                      | 480 ms: 1.04x faster                                         |
| coroutines               | 14.6 ms                                                     | 14.0 ms: 1.04x faster                                        |
| dulwich_log              | 44.5 ms                                                     | 42.8 ms: 1.04x faster                                        |
| aiohttp                  | 899 us                                                      | 865 us: 1.04x faster                                         |
| mako                     | 7.26 ms                                                     | 7.03 ms: 1.03x faster                                        |
| bench_thread_pool        | 852 us                                                      | 830 us: 1.03x faster                                         |
| nqueens                  | 64.9 ms                                                     | 63.4 ms: 1.02x faster                                        |
| regex_compile            | 90.6 ms                                                     | 88.9 ms: 1.02x faster                                        |
| deepcopy_memo            | 25.2 us                                                     | 24.7 us: 1.02x faster                                        |
| logging_simple           | 6.61 us                                                     | 6.49 us: 1.02x faster                                        |
| sqlglot_normalize        | 190 ms                                                      | 187 ms: 1.02x faster                                         |
| pyflate                  | 304 ms                                                      | 301 ms: 1.01x faster                                         |
| logging_format           | 7.01 us                                                     | 6.94 us: 1.01x faster                                        |
| meteor_contest           | 74.7 ms                                                     | 74.0 ms: 1.01x faster                                        |
| sqlglot_optimize         | 34.9 ms                                                     | 34.6 ms: 1.01x faster                                        |
| scimark_sparse_mat_mult  | 2.57 ms                                                     | 2.60 ms: 1.01x slower                                        |
| python_startup           | 18.7 ms                                                     | 18.9 ms: 1.01x slower                                        |
| pidigits                 | 148 ms                                                      | 150 ms: 1.01x slower                                         |
| crypto_pyaes             | 47.6 ms                                                     | 48.5 ms: 1.02x slower                                        |
| regex_dna                | 115 ms                                                      | 118 ms: 1.02x slower                                         |
| scimark_monte_carlo      | 44.6 ms                                                     | 45.5 ms: 1.02x slower                                        |
| regex_v8                 | 13.8 ms                                                     | 14.1 ms: 1.02x slower                                        |
| nbody                    | 70.0 ms                                                     | 71.4 ms: 1.02x slower                                        |
| xml_etree_iterparse      | 62.6 ms                                                     | 63.9 ms: 1.02x slower                                        |
| docutils                 | 1.60 sec                                                    | 1.64 sec: 1.02x slower                                       |
| 2to3                     | 209 ms                                                      | 214 ms: 1.03x slower                                         |
| unpickle                 | 8.09 us                                                     | 8.32 us: 1.03x slower                                        |
| gc_traversal             | 1.46 ms                                                     | 1.50 ms: 1.03x slower                                        |
| pprint_safe_repr         | 512 ms                                                      | 529 ms: 1.03x slower                                         |
| deepcopy_reduce          | 2.07 us                                                     | 2.15 us: 1.04x slower                                        |
| float                    | 54.6 ms                                                     | 56.6 ms: 1.04x slower                                        |
| pprint_pformat           | 1.04 sec                                                    | 1.08 sec: 1.04x slower                                       |
| sqlite_synth             | 1.68 us                                                     | 1.76 us: 1.04x slower                                        |
| xml_etree_process        | 37.1 ms                                                     | 38.8 ms: 1.05x slower                                        |
| unpickle_list            | 2.55 us                                                     | 2.67 us: 1.05x slower                                        |
| scimark_fft              | 178 ms                                                      | 187 ms: 1.05x slower                                         |
| create_gc_cycles         | 693 us                                                      | 730 us: 1.05x slower                                         |
| regex_effbot             | 1.50 ms                                                     | 1.58 ms: 1.06x slower                                        |
| json_loads               | 12.9 us                                                     | 13.6 us: 1.06x slower                                        |
| telco                    | 3.90 ms                                                     | 4.18 ms: 1.07x slower                                        |
| bench_mp_pool            | 62.5 ms                                                     | 67.1 ms: 1.07x slower                                        |
| pickle_list              | 2.68 us                                                     | 2.88 us: 1.08x slower                                        |
| pickle                   | 6.61 us                                                     | 7.17 us: 1.08x slower                                        |
| pathlib                  | 71.4 ms                                                     | 77.8 ms: 1.09x slower                                        |
| xml_etree_generate       | 52.2 ms                                                     | 57.2 ms: 1.10x slower                                        |
| scimark_sor              | 75.6 ms                                                     | 84.3 ms: 1.12x slower                                        |
| async_generators         | 178 ms                                                      | 234 ms: 1.32x slower                                         |
| dask                     | 264 ms                                                      | 364 ms: 1.38x slower                                         |
| Geometric mean           | (ref)                                                       | 1.04x faster                                                 |

Benchmark hidden because not significant (7): deepcopy, python_startup_no_site, tomli_loads, pickle_pure_python, pycparser, fannkuch, pickle_dict
Ignored benchmarks (14) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509.json: chameleon, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 77.31% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
