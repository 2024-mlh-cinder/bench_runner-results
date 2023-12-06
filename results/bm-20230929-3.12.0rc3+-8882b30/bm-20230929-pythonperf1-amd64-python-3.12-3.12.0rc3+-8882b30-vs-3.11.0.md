
# Results vs. 3.11.0

- fork: python
- ref: 3.12
- machine: windows-amd64
- commit hash: 8882b30
- commit date: 2023-09-29
- overall geometric mean: 1.06x faster
- HPT reliability: 99.99%
- HPT 99th percentile: 1.01x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230929-pythonperf1-amd64-python-3.12-3.12.0rc3+-8882b30 |
|----------------|:-----------------------------------------------------------:|:------------------------------------------------------------:|
| 2to3           | 209 ms                                                      | 211 ms: 1.01x slower                                         |
| docutils       | 1.60 sec                                                    | 1.62 sec: 1.01x slower                                       |
| tornado_http   | 91.8 ms                                                     | 87.0 ms: 1.06x faster                                        |
| Geometric mean | (ref)                                                       | 1.01x faster                                                 |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230929-pythonperf1-amd64-python-3.12-3.12.0rc3+-8882b30 |
|----------------|:-----------------------------------------------------------:|:------------------------------------------------------------:|
| float          | 54.6 ms                                                     | 55.1 ms: 1.01x slower                                        |
| pidigits       | 148 ms                                                      | 150 ms: 1.01x slower                                         |
| nbody          | 70.0 ms                                                     | 71.4 ms: 1.02x slower                                        |
| Geometric mean | (ref)                                                       | 1.01x slower                                                 |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230929-pythonperf1-amd64-python-3.12-3.12.0rc3+-8882b30 |
|----------------|:-----------------------------------------------------------:|:------------------------------------------------------------:|
| regex_compile  | 90.6 ms                                                     | 86.9 ms: 1.04x faster                                        |
| regex_v8       | 13.8 ms                                                     | 13.9 ms: 1.01x slower                                        |
| regex_dna      | 115 ms                                                      | 123 ms: 1.07x slower                                         |
| regex_effbot   | 1.50 ms                                                     | 1.62 ms: 1.08x slower                                        |
| Geometric mean | (ref)                                                       | 1.03x slower                                                 |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230929-pythonperf1-amd64-python-3.12-3.12.0rc3+-8882b30 |
|----------------------|:-----------------------------------------------------------:|:------------------------------------------------------------:|
| json_dumps           | 7.56 ms                                                     | 5.62 ms: 1.34x faster                                        |
| unpickle_pure_python | 152 us                                                      | 135 us: 1.13x faster                                         |
| tomli_loads          | 1.41 sec                                                    | 1.36 sec: 1.04x faster                                       |
| xml_etree_parse      | 95.9 ms                                                     | 92.7 ms: 1.03x faster                                        |
| pickle_pure_python   | 200 us                                                      | 193 us: 1.03x faster                                         |
| xml_etree_iterparse  | 62.6 ms                                                     | 63.4 ms: 1.01x slower                                        |
| xml_etree_process    | 37.1 ms                                                     | 37.7 ms: 1.02x slower                                        |
| unpickle             | 8.09 us                                                     | 8.28 us: 1.02x slower                                        |
| unpickle_list        | 2.55 us                                                     | 2.68 us: 1.05x slower                                        |
| json_loads           | 12.9 us                                                     | 13.6 us: 1.05x slower                                        |
| pickle_list          | 2.68 us                                                     | 2.84 us: 1.06x slower                                        |
| pickle               | 6.61 us                                                     | 7.00 us: 1.06x slower                                        |
| xml_etree_generate   | 52.2 ms                                                     | 55.3 ms: 1.06x slower                                        |
| Geometric mean       | (ref)                                                       | 1.02x faster                                                 |

Benchmark hidden because not significant (1): pickle_dict

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230929-pythonperf1-amd64-python-3.12-3.12.0rc3+-8882b30 |
|------------------------|:-----------------------------------------------------------:|:------------------------------------------------------------:|
| python_startup_no_site | 15.9 ms                                                     | 16.2 ms: 1.02x slower                                        |
| python_startup         | 18.7 ms                                                     | 19.1 ms: 1.02x slower                                        |
| Geometric mean         | (ref)                                                       | 1.02x slower                                                 |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230929-pythonperf1-amd64-python-3.12-3.12.0rc3+-8882b30 |
|-----------|:-----------------------------------------------------------:|:------------------------------------------------------------:|
| mako      | 7.26 ms                                                     | 6.93 ms: 1.05x faster                                        |

All benchmarks:
===============

| Benchmark                | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230929-pythonperf1-amd64-python-3.12-3.12.0rc3+-8882b30 |
|--------------------------|:-----------------------------------------------------------:|:------------------------------------------------------------:|
| typing_runtime_protocols | 322 us                                                      | 94.2 us: 3.42x faster                                        |
| generators               | 33.8 ms                                                     | 22.5 ms: 1.50x faster                                        |
| asyncio_tcp              | 699 ms                                                      | 469 ms: 1.49x faster                                         |
| json_dumps               | 7.56 ms                                                     | 5.62 ms: 1.34x faster                                        |
| unpack_sequence          | 46.1 ns                                                     | 36.5 ns: 1.26x faster                                        |
| richards_super           | 37.5 ms                                                     | 30.1 ms: 1.25x faster                                        |
| deltablue                | 2.61 ms                                                     | 2.12 ms: 1.23x faster                                        |
| sqlglot_parse            | 952 us                                                      | 805 us: 1.18x faster                                         |
| logging_silent           | 69.8 ns                                                     | 60.4 ns: 1.16x faster                                        |
| richards                 | 30.6 ms                                                     | 26.5 ms: 1.15x faster                                        |
| mdp                      | 1.67 sec                                                    | 1.45 sec: 1.15x faster                                       |
| sqlglot_transpile        | 1.16 ms                                                     | 1.02 ms: 1.14x faster                                        |
| hexiom                   | 4.55 ms                                                     | 4.00 ms: 1.14x faster                                        |
| unpickle_pure_python     | 152 us                                                      | 135 us: 1.13x faster                                         |
| chaos                    | 47.1 ms                                                     | 41.8 ms: 1.13x faster                                        |
| comprehensions           | 15.9 us                                                     | 14.3 us: 1.12x faster                                        |
| async_tree_none          | 320 ms                                                      | 287 ms: 1.12x faster                                         |
| async_tree_memoization   | 371 ms                                                      | 334 ms: 1.11x faster                                         |
| go                       | 97.3 ms                                                     | 87.9 ms: 1.11x faster                                        |
| scimark_lu               | 63.5 ms                                                     | 57.4 ms: 1.11x faster                                        |
| json                     | 3.25 ms                                                     | 2.94 ms: 1.11x faster                                        |
| coverage                 | 55.9 ms                                                     | 50.7 ms: 1.10x faster                                        |
| mypy2                    | 229 ms                                                      | 208 ms: 1.10x faster                                         |
| raytrace                 | 211 ms                                                      | 193 ms: 1.09x faster                                         |
| asyncio_tcp_ssl          | 2.11 sec                                                    | 1.94 sec: 1.09x faster                                       |
| async_tree_io            | 779 ms                                                      | 717 ms: 1.09x faster                                         |
| logging_simple           | 6.61 us                                                     | 6.15 us: 1.07x faster                                        |
| spectral_norm            | 67.9 ms                                                     | 63.2 ms: 1.07x faster                                        |
| logging_format           | 7.01 us                                                     | 6.56 us: 1.07x faster                                        |
| scimark_monte_carlo      | 44.6 ms                                                     | 42.1 ms: 1.06x faster                                        |
| tornado_http             | 91.8 ms                                                     | 87.0 ms: 1.06x faster                                        |
| deepcopy                 | 246 us                                                      | 233 us: 1.05x faster                                         |
| deepcopy_memo            | 25.2 us                                                     | 23.9 us: 1.05x faster                                        |
| async_tree_cpu_io_mixed  | 501 ms                                                      | 477 ms: 1.05x faster                                         |
| aiohttp                  | 899 us                                                      | 855 us: 1.05x faster                                         |
| nqueens                  | 64.9 ms                                                     | 61.8 ms: 1.05x faster                                        |
| mako                     | 7.26 ms                                                     | 6.93 ms: 1.05x faster                                        |
| regex_compile            | 90.6 ms                                                     | 86.9 ms: 1.04x faster                                        |
| pyflate                  | 304 ms                                                      | 292 ms: 1.04x faster                                         |
| coroutines               | 14.6 ms                                                     | 14.0 ms: 1.04x faster                                        |
| tomli_loads              | 1.41 sec                                                    | 1.36 sec: 1.04x faster                                       |
| dulwich_log              | 44.5 ms                                                     | 42.9 ms: 1.04x faster                                        |
| xml_etree_parse          | 95.9 ms                                                     | 92.7 ms: 1.03x faster                                        |
| pickle_pure_python       | 200 us                                                      | 193 us: 1.03x faster                                         |
| sqlglot_normalize        | 190 ms                                                      | 184 ms: 1.03x faster                                         |
| dask                     | 264 ms                                                      | 257 ms: 1.03x faster                                         |
| meteor_contest           | 74.7 ms                                                     | 72.7 ms: 1.03x faster                                        |
| scimark_sparse_mat_mult  | 2.57 ms                                                     | 2.50 ms: 1.03x faster                                        |
| pprint_safe_repr         | 512 ms                                                      | 499 ms: 1.03x faster                                         |
| bench_thread_pool        | 852 us                                                      | 831 us: 1.03x faster                                         |
| sqlglot_optimize         | 34.9 ms                                                     | 34.0 ms: 1.02x faster                                        |
| pprint_pformat           | 1.04 sec                                                    | 1.02 sec: 1.02x faster                                       |
| fannkuch                 | 252 ms                                                      | 247 ms: 1.02x faster                                         |
| crypto_pyaes             | 47.6 ms                                                     | 47.0 ms: 1.01x faster                                        |
| deepcopy_reduce          | 2.07 us                                                     | 2.06 us: 1.01x faster                                        |
| regex_v8                 | 13.8 ms                                                     | 13.9 ms: 1.01x slower                                        |
| float                    | 54.6 ms                                                     | 55.1 ms: 1.01x slower                                        |
| docutils                 | 1.60 sec                                                    | 1.62 sec: 1.01x slower                                       |
| 2to3                     | 209 ms                                                      | 211 ms: 1.01x slower                                         |
| pidigits                 | 148 ms                                                      | 150 ms: 1.01x slower                                         |
| xml_etree_iterparse      | 62.6 ms                                                     | 63.4 ms: 1.01x slower                                        |
| xml_etree_process        | 37.1 ms                                                     | 37.7 ms: 1.02x slower                                        |
| python_startup_no_site   | 15.9 ms                                                     | 16.2 ms: 1.02x slower                                        |
| python_startup           | 18.7 ms                                                     | 19.1 ms: 1.02x slower                                        |
| nbody                    | 70.0 ms                                                     | 71.4 ms: 1.02x slower                                        |
| scimark_sor              | 75.6 ms                                                     | 77.2 ms: 1.02x slower                                        |
| gc_traversal             | 1.46 ms                                                     | 1.49 ms: 1.02x slower                                        |
| unpickle                 | 8.09 us                                                     | 8.28 us: 1.02x slower                                        |
| sqlite_synth             | 1.68 us                                                     | 1.74 us: 1.03x slower                                        |
| unpickle_list            | 2.55 us                                                     | 2.68 us: 1.05x slower                                        |
| create_gc_cycles         | 693 us                                                      | 729 us: 1.05x slower                                         |
| json_loads               | 12.9 us                                                     | 13.6 us: 1.05x slower                                        |
| pickle_list              | 2.68 us                                                     | 2.84 us: 1.06x slower                                        |
| pickle                   | 6.61 us                                                     | 7.00 us: 1.06x slower                                        |
| xml_etree_generate       | 52.2 ms                                                     | 55.3 ms: 1.06x slower                                        |
| regex_dna                | 115 ms                                                      | 123 ms: 1.07x slower                                         |
| telco                    | 3.90 ms                                                     | 4.18 ms: 1.07x slower                                        |
| bench_mp_pool            | 62.5 ms                                                     | 67.2 ms: 1.07x slower                                        |
| regex_effbot             | 1.50 ms                                                     | 1.62 ms: 1.08x slower                                        |
| pathlib                  | 71.4 ms                                                     | 78.2 ms: 1.10x slower                                        |
| async_generators         | 178 ms                                                      | 235 ms: 1.33x slower                                         |
| Geometric mean           | (ref)                                                       | 1.06x faster                                                 |

Benchmark hidden because not significant (3): pickle_dict, pycparser, scimark_fft
Ignored benchmarks (14) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509.json: chameleon, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 99.99% likely to be faster
- 90% likely to have a speedup of 1.02x
- 95% likely to have a speedup of 1.02x
- 99% likely to have a speedup of 1.01x
