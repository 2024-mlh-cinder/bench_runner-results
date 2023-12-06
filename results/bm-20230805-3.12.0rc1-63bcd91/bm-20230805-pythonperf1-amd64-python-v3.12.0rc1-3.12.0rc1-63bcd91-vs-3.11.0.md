
# Results vs. 3.11.0

- fork: python
- ref: v3.12.0rc1
- machine: windows-amd64
- commit hash: 63bcd91
- commit date: 2023-08-05
- overall geometric mean: 1.07x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.02x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230805-pythonperf1-amd64-python-v3.12.0rc1-3.12.0rc1-63bcd91 |
|----------------|:-----------------------------------------------------------:|:-----------------------------------------------------------------:|
| 2to3           | 209 ms                                                      | 211 ms: 1.01x slower                                              |
| tornado_http   | 91.8 ms                                                     | 87.2 ms: 1.05x faster                                             |
| Geometric mean | (ref)                                                       | 1.01x faster                                                      |

Benchmark hidden because not significant (1): docutils

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230805-pythonperf1-amd64-python-v3.12.0rc1-3.12.0rc1-63bcd91 |
|----------------|:-----------------------------------------------------------:|:-----------------------------------------------------------------:|
| nbody          | 70.0 ms                                                     | 68.7 ms: 1.02x faster                                             |
| float          | 54.6 ms                                                     | 53.8 ms: 1.01x faster                                             |
| pidigits       | 148 ms                                                      | 147 ms: 1.01x faster                                              |
| Geometric mean | (ref)                                                       | 1.01x faster                                                      |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230805-pythonperf1-amd64-python-v3.12.0rc1-3.12.0rc1-63bcd91 |
|----------------|:-----------------------------------------------------------:|:-----------------------------------------------------------------:|
| regex_compile  | 90.6 ms                                                     | 85.8 ms: 1.06x faster                                             |
| regex_v8       | 13.8 ms                                                     | 13.8 ms: 1.01x faster                                             |
| regex_dna      | 115 ms                                                      | 121 ms: 1.05x slower                                              |
| regex_effbot   | 1.50 ms                                                     | 1.61 ms: 1.08x slower                                             |
| Geometric mean | (ref)                                                       | 1.02x slower                                                      |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230805-pythonperf1-amd64-python-v3.12.0rc1-3.12.0rc1-63bcd91 |
|----------------------|:-----------------------------------------------------------:|:-----------------------------------------------------------------:|
| json_dumps           | 7.56 ms                                                     | 5.59 ms: 1.35x faster                                             |
| unpickle_pure_python | 152 us                                                      | 133 us: 1.14x faster                                              |
| tomli_loads          | 1.41 sec                                                    | 1.35 sec: 1.05x faster                                            |
| xml_etree_parse      | 95.9 ms                                                     | 91.3 ms: 1.05x faster                                             |
| pickle_pure_python   | 200 us                                                      | 191 us: 1.05x faster                                              |
| xml_etree_process    | 37.1 ms                                                     | 37.6 ms: 1.01x slower                                             |
| unpickle             | 8.09 us                                                     | 8.38 us: 1.04x slower                                             |
| json_loads           | 12.9 us                                                     | 13.5 us: 1.04x slower                                             |
| pickle               | 6.61 us                                                     | 6.98 us: 1.06x slower                                             |
| xml_etree_generate   | 52.2 ms                                                     | 55.1 ms: 1.06x slower                                             |
| pickle_list          | 2.68 us                                                     | 2.87 us: 1.07x slower                                             |
| unpickle_list        | 2.55 us                                                     | 2.79 us: 1.10x slower                                             |
| Geometric mean       | (ref)                                                       | 1.02x faster                                                      |

Benchmark hidden because not significant (2): pickle_dict, xml_etree_iterparse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230805-pythonperf1-amd64-python-v3.12.0rc1-3.12.0rc1-63bcd91 |
|------------------------|:-----------------------------------------------------------:|:-----------------------------------------------------------------:|
| python_startup_no_site | 15.9 ms                                                     | 16.1 ms: 1.01x slower                                             |
| Geometric mean         | (ref)                                                       | 1.01x slower                                                      |

Benchmark hidden because not significant (1): python_startup

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230805-pythonperf1-amd64-python-v3.12.0rc1-3.12.0rc1-63bcd91 |
|-----------|:-----------------------------------------------------------:|:-----------------------------------------------------------------:|
| mako      | 7.26 ms                                                     | 6.82 ms: 1.06x faster                                             |

All benchmarks:
===============

| Benchmark                | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230805-pythonperf1-amd64-python-v3.12.0rc1-3.12.0rc1-63bcd91 |
|--------------------------|:-----------------------------------------------------------:|:-----------------------------------------------------------------:|
| typing_runtime_protocols | 322 us                                                      | 93.3 us: 3.45x faster                                             |
| generators               | 33.8 ms                                                     | 22.5 ms: 1.50x faster                                             |
| asyncio_tcp              | 699 ms                                                      | 470 ms: 1.49x faster                                              |
| json_dumps               | 7.56 ms                                                     | 5.59 ms: 1.35x faster                                             |
| unpack_sequence          | 46.1 ns                                                     | 35.1 ns: 1.31x faster                                             |
| richards_super           | 37.5 ms                                                     | 29.5 ms: 1.27x faster                                             |
| deltablue                | 2.61 ms                                                     | 2.13 ms: 1.22x faster                                             |
| sqlglot_parse            | 952 us                                                      | 800 us: 1.19x faster                                              |
| richards                 | 30.6 ms                                                     | 26.1 ms: 1.17x faster                                             |
| mdp                      | 1.67 sec                                                    | 1.43 sec: 1.17x faster                                            |
| logging_silent           | 69.8 ns                                                     | 60.0 ns: 1.16x faster                                             |
| sqlglot_transpile        | 1.16 ms                                                     | 1.01 ms: 1.15x faster                                             |
| hexiom                   | 4.55 ms                                                     | 3.98 ms: 1.14x faster                                             |
| unpickle_pure_python     | 152 us                                                      | 133 us: 1.14x faster                                              |
| raytrace                 | 211 ms                                                      | 184 ms: 1.14x faster                                              |
| go                       | 97.3 ms                                                     | 86.3 ms: 1.13x faster                                             |
| comprehensions           | 15.9 us                                                     | 14.1 us: 1.13x faster                                             |
| async_tree_memoization   | 371 ms                                                      | 331 ms: 1.12x faster                                              |
| async_tree_none          | 320 ms                                                      | 286 ms: 1.12x faster                                              |
| json                     | 3.25 ms                                                     | 2.91 ms: 1.12x faster                                             |
| scimark_lu               | 63.5 ms                                                     | 57.1 ms: 1.11x faster                                             |
| async_tree_io            | 779 ms                                                      | 701 ms: 1.11x faster                                              |
| asyncio_tcp_ssl          | 2.11 sec                                                    | 1.90 sec: 1.11x faster                                            |
| mypy2                    | 229 ms                                                      | 208 ms: 1.10x faster                                              |
| chaos                    | 47.1 ms                                                     | 42.8 ms: 1.10x faster                                             |
| deepcopy_memo            | 25.2 us                                                     | 22.9 us: 1.10x faster                                             |
| scimark_monte_carlo      | 44.6 ms                                                     | 41.5 ms: 1.08x faster                                             |
| deepcopy                 | 246 us                                                      | 229 us: 1.07x faster                                              |
| coverage                 | 55.9 ms                                                     | 52.1 ms: 1.07x faster                                             |
| fannkuch                 | 252 ms                                                      | 236 ms: 1.07x faster                                              |
| mako                     | 7.26 ms                                                     | 6.82 ms: 1.06x faster                                             |
| async_tree_cpu_io_mixed  | 501 ms                                                      | 471 ms: 1.06x faster                                              |
| sqlglot_normalize        | 190 ms                                                      | 180 ms: 1.06x faster                                              |
| regex_compile            | 90.6 ms                                                     | 85.8 ms: 1.06x faster                                             |
| spectral_norm            | 67.9 ms                                                     | 64.4 ms: 1.05x faster                                             |
| nqueens                  | 64.9 ms                                                     | 61.6 ms: 1.05x faster                                             |
| aiohttp                  | 899 us                                                      | 854 us: 1.05x faster                                              |
| tornado_http             | 91.8 ms                                                     | 87.2 ms: 1.05x faster                                             |
| tomli_loads              | 1.41 sec                                                    | 1.35 sec: 1.05x faster                                            |
| xml_etree_parse          | 95.9 ms                                                     | 91.3 ms: 1.05x faster                                             |
| pickle_pure_python       | 200 us                                                      | 191 us: 1.05x faster                                              |
| dulwich_log              | 44.5 ms                                                     | 42.5 ms: 1.05x faster                                             |
| coroutines               | 14.6 ms                                                     | 14.0 ms: 1.05x faster                                             |
| pyflate                  | 304 ms                                                      | 292 ms: 1.04x faster                                              |
| scimark_sparse_mat_mult  | 2.57 ms                                                     | 2.47 ms: 1.04x faster                                             |
| sqlglot_optimize         | 34.9 ms                                                     | 33.5 ms: 1.04x faster                                             |
| logging_simple           | 6.61 us                                                     | 6.37 us: 1.04x faster                                             |
| logging_format           | 7.01 us                                                     | 6.77 us: 1.04x faster                                             |
| pycparser                | 691 ms                                                      | 670 ms: 1.03x faster                                              |
| scimark_fft              | 178 ms                                                      | 174 ms: 1.03x faster                                              |
| meteor_contest           | 74.7 ms                                                     | 73.1 ms: 1.02x faster                                             |
| nbody                    | 70.0 ms                                                     | 68.7 ms: 1.02x faster                                             |
| pprint_pformat           | 1.04 sec                                                    | 1.02 sec: 1.02x faster                                            |
| float                    | 54.6 ms                                                     | 53.8 ms: 1.01x faster                                             |
| pprint_safe_repr         | 512 ms                                                      | 504 ms: 1.01x faster                                              |
| crypto_pyaes             | 47.6 ms                                                     | 46.9 ms: 1.01x faster                                             |
| pidigits                 | 148 ms                                                      | 147 ms: 1.01x faster                                              |
| regex_v8                 | 13.8 ms                                                     | 13.8 ms: 1.01x faster                                             |
| 2to3                     | 209 ms                                                      | 211 ms: 1.01x slower                                              |
| gc_traversal             | 1.46 ms                                                     | 1.47 ms: 1.01x slower                                             |
| python_startup_no_site   | 15.9 ms                                                     | 16.1 ms: 1.01x slower                                             |
| xml_etree_process        | 37.1 ms                                                     | 37.6 ms: 1.01x slower                                             |
| telco                    | 3.90 ms                                                     | 3.98 ms: 1.02x slower                                             |
| sqlite_synth             | 1.68 us                                                     | 1.73 us: 1.03x slower                                             |
| create_gc_cycles         | 693 us                                                      | 717 us: 1.04x slower                                              |
| unpickle                 | 8.09 us                                                     | 8.38 us: 1.04x slower                                             |
| scimark_sor              | 75.6 ms                                                     | 78.7 ms: 1.04x slower                                             |
| json_loads               | 12.9 us                                                     | 13.5 us: 1.04x slower                                             |
| regex_dna                | 115 ms                                                      | 121 ms: 1.05x slower                                              |
| pickle                   | 6.61 us                                                     | 6.98 us: 1.06x slower                                             |
| xml_etree_generate       | 52.2 ms                                                     | 55.1 ms: 1.06x slower                                             |
| bench_mp_pool            | 62.5 ms                                                     | 66.3 ms: 1.06x slower                                             |
| pickle_list              | 2.68 us                                                     | 2.87 us: 1.07x slower                                             |
| regex_effbot             | 1.50 ms                                                     | 1.61 ms: 1.08x slower                                             |
| pathlib                  | 71.4 ms                                                     | 78.1 ms: 1.09x slower                                             |
| unpickle_list            | 2.55 us                                                     | 2.79 us: 1.10x slower                                             |
| async_generators         | 178 ms                                                      | 229 ms: 1.29x slower                                              |
| dask                     | 264 ms                                                      | 361 ms: 1.37x slower                                              |
| Geometric mean           | (ref)                                                       | 1.07x faster                                                      |

Benchmark hidden because not significant (6): pickle_dict, bench_thread_pool, docutils, python_startup, deepcopy_reduce, xml_etree_iterparse
Ignored benchmarks (14) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509.json: chameleon, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.03x
- 95% likely to have a speedup of 1.02x
- 99% likely to have a speedup of 1.02x
