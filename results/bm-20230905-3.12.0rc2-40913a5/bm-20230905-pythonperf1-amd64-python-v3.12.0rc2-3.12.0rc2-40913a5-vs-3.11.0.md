
# Results vs. 3.11.0

- fork: python
- ref: v3.12.0rc2
- machine: windows-amd64
- commit hash: 40913a5
- commit date: 2023-09-05
- overall geometric mean: 1.05x faster
- HPT reliability: 99.94%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230905-pythonperf1-amd64-python-v3.12.0rc2-3.12.0rc2-40913a5 |
|----------------|:-----------------------------------------------------------:|:-----------------------------------------------------------------:|
| 2to3           | 209 ms                                                      | 216 ms: 1.03x slower                                              |
| docutils       | 1.60 sec                                                    | 1.65 sec: 1.03x slower                                            |
| tornado_http   | 91.8 ms                                                     | 88.4 ms: 1.04x faster                                             |
| Geometric mean | (ref)                                                       | 1.01x slower                                                      |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230905-pythonperf1-amd64-python-v3.12.0rc2-3.12.0rc2-40913a5 |
|----------------|:-----------------------------------------------------------:|:-----------------------------------------------------------------:|
| nbody          | 70.0 ms                                                     | 69.0 ms: 1.01x faster                                             |
| pidigits       | 148 ms                                                      | 150 ms: 1.01x slower                                              |
| Geometric mean | (ref)                                                       | 1.00x faster                                                      |

Benchmark hidden because not significant (1): float

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230905-pythonperf1-amd64-python-v3.12.0rc2-3.12.0rc2-40913a5 |
|----------------|:-----------------------------------------------------------:|:-----------------------------------------------------------------:|
| regex_compile  | 90.6 ms                                                     | 87.5 ms: 1.04x faster                                             |
| regex_v8       | 13.8 ms                                                     | 13.7 ms: 1.01x faster                                             |
| regex_dna      | 115 ms                                                      | 119 ms: 1.03x slower                                              |
| regex_effbot   | 1.50 ms                                                     | 1.58 ms: 1.06x slower                                             |
| Geometric mean | (ref)                                                       | 1.01x slower                                                      |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230905-pythonperf1-amd64-python-v3.12.0rc2-3.12.0rc2-40913a5 |
|----------------------|:-----------------------------------------------------------:|:-----------------------------------------------------------------:|
| json_dumps           | 7.56 ms                                                     | 5.66 ms: 1.34x faster                                             |
| unpickle_pure_python | 152 us                                                      | 130 us: 1.16x faster                                              |
| xml_etree_parse      | 95.9 ms                                                     | 89.7 ms: 1.07x faster                                             |
| pickle_pure_python   | 200 us                                                      | 191 us: 1.04x faster                                              |
| tomli_loads          | 1.41 sec                                                    | 1.37 sec: 1.03x faster                                            |
| xml_etree_process    | 37.1 ms                                                     | 37.9 ms: 1.02x slower                                             |
| pickle_list          | 2.68 us                                                     | 2.75 us: 1.03x slower                                             |
| unpickle_list        | 2.55 us                                                     | 2.65 us: 1.04x slower                                             |
| json_loads           | 12.9 us                                                     | 13.6 us: 1.05x slower                                             |
| pickle               | 6.61 us                                                     | 6.97 us: 1.05x slower                                             |
| xml_etree_generate   | 52.2 ms                                                     | 55.4 ms: 1.06x slower                                             |
| Geometric mean       | (ref)                                                       | 1.02x faster                                                      |

Benchmark hidden because not significant (3): pickle_dict, unpickle, xml_etree_iterparse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230905-pythonperf1-amd64-python-v3.12.0rc2-3.12.0rc2-40913a5 |
|------------------------|:-----------------------------------------------------------:|:-----------------------------------------------------------------:|
| python_startup_no_site | 15.9 ms                                                     | 16.3 ms: 1.03x slower                                             |
| python_startup         | 18.7 ms                                                     | 19.3 ms: 1.03x slower                                             |
| Geometric mean         | (ref)                                                       | 1.03x slower                                                      |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230905-pythonperf1-amd64-python-v3.12.0rc2-3.12.0rc2-40913a5 |
|-----------|:-----------------------------------------------------------:|:-----------------------------------------------------------------:|
| mako      | 7.26 ms                                                     | 7.00 ms: 1.04x faster                                             |

All benchmarks:
===============

| Benchmark                | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230905-pythonperf1-amd64-python-v3.12.0rc2-3.12.0rc2-40913a5 |
|--------------------------|:-----------------------------------------------------------:|:-----------------------------------------------------------------:|
| typing_runtime_protocols | 322 us                                                      | 96.2 us: 3.35x faster                                             |
| asyncio_tcp              | 699 ms                                                      | 480 ms: 1.45x faster                                              |
| generators               | 33.8 ms                                                     | 24.2 ms: 1.40x faster                                             |
| json_dumps               | 7.56 ms                                                     | 5.66 ms: 1.34x faster                                             |
| richards_super           | 37.5 ms                                                     | 29.7 ms: 1.26x faster                                             |
| deltablue                | 2.61 ms                                                     | 2.13 ms: 1.23x faster                                             |
| mdp                      | 1.67 sec                                                    | 1.39 sec: 1.20x faster                                            |
| unpack_sequence          | 46.1 ns                                                     | 38.3 ns: 1.20x faster                                             |
| sqlglot_parse            | 952 us                                                      | 808 us: 1.18x faster                                              |
| richards                 | 30.6 ms                                                     | 26.0 ms: 1.17x faster                                             |
| unpickle_pure_python     | 152 us                                                      | 130 us: 1.16x faster                                              |
| logging_silent           | 69.8 ns                                                     | 60.3 ns: 1.16x faster                                             |
| sqlglot_transpile        | 1.16 ms                                                     | 1.02 ms: 1.14x faster                                             |
| hexiom                   | 4.55 ms                                                     | 4.04 ms: 1.13x faster                                             |
| go                       | 97.3 ms                                                     | 87.0 ms: 1.12x faster                                             |
| coverage                 | 55.9 ms                                                     | 50.2 ms: 1.11x faster                                             |
| scimark_lu               | 63.5 ms                                                     | 57.2 ms: 1.11x faster                                             |
| raytrace                 | 211 ms                                                      | 190 ms: 1.11x faster                                              |
| chaos                    | 47.1 ms                                                     | 42.6 ms: 1.11x faster                                             |
| async_tree_none          | 320 ms                                                      | 291 ms: 1.10x faster                                              |
| async_tree_memoization   | 371 ms                                                      | 339 ms: 1.10x faster                                              |
| mypy2                    | 229 ms                                                      | 209 ms: 1.09x faster                                              |
| json                     | 3.25 ms                                                     | 2.99 ms: 1.09x faster                                             |
| spectral_norm            | 67.9 ms                                                     | 62.7 ms: 1.08x faster                                             |
| async_tree_io            | 779 ms                                                      | 722 ms: 1.08x faster                                              |
| asyncio_tcp_ssl          | 2.11 sec                                                    | 1.96 sec: 1.08x faster                                            |
| xml_etree_parse          | 95.9 ms                                                     | 89.7 ms: 1.07x faster                                             |
| deepcopy_memo            | 25.2 us                                                     | 23.6 us: 1.07x faster                                             |
| logging_simple           | 6.61 us                                                     | 6.24 us: 1.06x faster                                             |
| pickle_pure_python       | 200 us                                                      | 191 us: 1.04x faster                                              |
| async_tree_cpu_io_mixed  | 501 ms                                                      | 480 ms: 1.04x faster                                              |
| scimark_monte_carlo      | 44.6 ms                                                     | 42.8 ms: 1.04x faster                                             |
| aiohttp                  | 899 us                                                      | 863 us: 1.04x faster                                              |
| comprehensions           | 15.9 us                                                     | 15.3 us: 1.04x faster                                             |
| logging_format           | 7.01 us                                                     | 6.74 us: 1.04x faster                                             |
| dulwich_log              | 44.5 ms                                                     | 42.8 ms: 1.04x faster                                             |
| tornado_http             | 91.8 ms                                                     | 88.4 ms: 1.04x faster                                             |
| mako                     | 7.26 ms                                                     | 7.00 ms: 1.04x faster                                             |
| pyflate                  | 304 ms                                                      | 293 ms: 1.04x faster                                              |
| regex_compile            | 90.6 ms                                                     | 87.5 ms: 1.04x faster                                             |
| tomli_loads              | 1.41 sec                                                    | 1.37 sec: 1.03x faster                                            |
| scimark_sparse_mat_mult  | 2.57 ms                                                     | 2.50 ms: 1.03x faster                                             |
| meteor_contest           | 74.7 ms                                                     | 73.1 ms: 1.02x faster                                             |
| deepcopy                 | 246 us                                                      | 241 us: 1.02x faster                                              |
| nqueens                  | 64.9 ms                                                     | 63.9 ms: 1.02x faster                                             |
| sqlglot_normalize        | 190 ms                                                      | 187 ms: 1.02x faster                                              |
| pycparser                | 691 ms                                                      | 681 ms: 1.02x faster                                              |
| nbody                    | 70.0 ms                                                     | 69.0 ms: 1.01x faster                                             |
| crypto_pyaes             | 47.6 ms                                                     | 46.9 ms: 1.01x faster                                             |
| regex_v8                 | 13.8 ms                                                     | 13.7 ms: 1.01x faster                                             |
| fannkuch                 | 252 ms                                                      | 249 ms: 1.01x faster                                              |
| scimark_fft              | 178 ms                                                      | 176 ms: 1.01x faster                                              |
| sqlglot_optimize         | 34.9 ms                                                     | 34.5 ms: 1.01x faster                                             |
| pidigits                 | 148 ms                                                      | 150 ms: 1.01x slower                                              |
| scimark_sor              | 75.6 ms                                                     | 77.1 ms: 1.02x slower                                             |
| xml_etree_process        | 37.1 ms                                                     | 37.9 ms: 1.02x slower                                             |
| python_startup_no_site   | 15.9 ms                                                     | 16.3 ms: 1.03x slower                                             |
| pickle_list              | 2.68 us                                                     | 2.75 us: 1.03x slower                                             |
| regex_dna                | 115 ms                                                      | 119 ms: 1.03x slower                                              |
| docutils                 | 1.60 sec                                                    | 1.65 sec: 1.03x slower                                            |
| python_startup           | 18.7 ms                                                     | 19.3 ms: 1.03x slower                                             |
| 2to3                     | 209 ms                                                      | 216 ms: 1.03x slower                                              |
| gc_traversal             | 1.46 ms                                                     | 1.51 ms: 1.03x slower                                             |
| create_gc_cycles         | 693 us                                                      | 718 us: 1.04x slower                                              |
| sqlite_synth             | 1.68 us                                                     | 1.74 us: 1.04x slower                                             |
| deepcopy_reduce          | 2.07 us                                                     | 2.15 us: 1.04x slower                                             |
| unpickle_list            | 2.55 us                                                     | 2.65 us: 1.04x slower                                             |
| json_loads               | 12.9 us                                                     | 13.6 us: 1.05x slower                                             |
| pickle                   | 6.61 us                                                     | 6.97 us: 1.05x slower                                             |
| regex_effbot             | 1.50 ms                                                     | 1.58 ms: 1.06x slower                                             |
| xml_etree_generate       | 52.2 ms                                                     | 55.4 ms: 1.06x slower                                             |
| telco                    | 3.90 ms                                                     | 4.19 ms: 1.07x slower                                             |
| bench_mp_pool            | 62.5 ms                                                     | 67.3 ms: 1.08x slower                                             |
| pathlib                  | 71.4 ms                                                     | 78.3 ms: 1.10x slower                                             |
| coroutines               | 14.6 ms                                                     | 19.0 ms: 1.30x slower                                             |
| async_generators         | 178 ms                                                      | 238 ms: 1.34x slower                                              |
| dask                     | 264 ms                                                      | 363 ms: 1.38x slower                                              |
| Geometric mean           | (ref)                                                       | 1.05x faster                                                      |

Benchmark hidden because not significant (7): pickle_dict, unpickle, pprint_safe_repr, float, pprint_pformat, xml_etree_iterparse, bench_thread_pool
Ignored benchmarks (14) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509.json: chameleon, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 99.94% likely to be faster
- 90% likely to have a speedup of 1.01x
- 95% likely to have a speedup of 1.01x
- 99% likely to have a speedup of 1.00x
