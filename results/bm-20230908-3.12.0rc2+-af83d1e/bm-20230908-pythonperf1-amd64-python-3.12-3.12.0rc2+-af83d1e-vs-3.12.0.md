
# Results vs. 3.12.0

- fork: python
- ref: 3.12
- machine: windows-amd64
- commit hash: af83d1e
- commit date: 2023-09-08
- overall geometric mean: 1.00x faster
- HPT reliability: 99.81%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230908-pythonperf1-amd64-python-3.12-3.12.0rc2+-af83d1e |
|----------------|:-----------------------------------------------------------:|:------------------------------------------------------------:|
| 2to3           | 214 ms                                                      | 213 ms: 1.01x faster                                         |
| docutils       | 1.63 sec                                                    | 1.64 sec: 1.01x slower                                       |
| Geometric mean | (ref)                                                       | 1.00x faster                                                 |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230908-pythonperf1-amd64-python-3.12-3.12.0rc2+-af83d1e |
|----------------|:-----------------------------------------------------------:|:------------------------------------------------------------:|
| nbody          | 72.6 ms                                                     | 69.0 ms: 1.05x faster                                        |
| float          | 55.1 ms                                                     | 54.2 ms: 1.02x faster                                        |
| Geometric mean | (ref)                                                       | 1.02x faster                                                 |

Benchmark hidden because not significant (1): pidigits

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230908-pythonperf1-amd64-python-3.12-3.12.0rc2+-af83d1e |
|----------------|:-----------------------------------------------------------:|:------------------------------------------------------------:|
| regex_dna      | 124 ms                                                      | 121 ms: 1.02x faster                                         |
| regex_compile  | 88.3 ms                                                     | 86.3 ms: 1.02x faster                                        |
| regex_effbot   | 1.62 ms                                                     | 1.59 ms: 1.02x faster                                        |
| regex_v8       | 13.9 ms                                                     | 13.7 ms: 1.01x faster                                        |
| Geometric mean | (ref)                                                       | 1.02x faster                                                 |

Benchmarks with tag 'serialize':
================================

| Benchmark          | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230908-pythonperf1-amd64-python-3.12-3.12.0rc2+-af83d1e |
|--------------------|:-----------------------------------------------------------:|:------------------------------------------------------------:|
| unpickle_list      | 2.78 us                                                     | 2.69 us: 1.03x faster                                        |
| pickle_dict        | 19.3 us                                                     | 18.6 us: 1.03x faster                                        |
| xml_etree_process  | 38.4 ms                                                     | 37.6 ms: 1.02x faster                                        |
| pickle_list        | 2.86 us                                                     | 2.81 us: 1.02x faster                                        |
| xml_etree_generate | 55.6 ms                                                     | 55.0 ms: 1.01x faster                                        |
| pickle_pure_python | 196 us                                                      | 195 us: 1.00x faster                                         |
| pickle             | 7.13 us                                                     | 7.17 us: 1.01x slower                                        |
| unpickle           | 8.16 us                                                     | 8.21 us: 1.01x slower                                        |
| xml_etree_parse    | 89.2 ms                                                     | 89.8 ms: 1.01x slower                                        |
| json_dumps         | 5.60 ms                                                     | 5.70 ms: 1.02x slower                                        |
| Geometric mean     | (ref)                                                       | 1.01x faster                                                 |

Benchmark hidden because not significant (4): unpickle_pure_python, tomli_loads, json_loads, xml_etree_iterparse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230908-pythonperf1-amd64-python-3.12-3.12.0rc2+-af83d1e |
|------------------------|:-----------------------------------------------------------:|:------------------------------------------------------------:|
| python_startup_no_site | 16.1 ms                                                     | 16.4 ms: 1.02x slower                                        |
| Geometric mean         | (ref)                                                       | 1.00x slower                                                 |

Benchmark hidden because not significant (1): python_startup

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230908-pythonperf1-amd64-python-3.12-3.12.0rc2+-af83d1e |
|-----------|:-----------------------------------------------------------:|:------------------------------------------------------------:|
| mako      | 6.93 ms                                                     | 6.87 ms: 1.01x faster                                        |

All benchmarks:
===============

| Benchmark                | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230908-pythonperf1-amd64-python-3.12-3.12.0rc2+-af83d1e |
|--------------------------|:-----------------------------------------------------------:|:------------------------------------------------------------:|
| nbody                    | 72.6 ms                                                     | 69.0 ms: 1.05x faster                                        |
| unpickle_list            | 2.78 us                                                     | 2.69 us: 1.03x faster                                        |
| deepcopy_reduce          | 2.13 us                                                     | 2.06 us: 1.03x faster                                        |
| mdp                      | 1.44 sec                                                    | 1.40 sec: 1.03x faster                                       |
| pickle_dict              | 19.3 us                                                     | 18.6 us: 1.03x faster                                        |
| scimark_monte_carlo      | 43.7 ms                                                     | 42.4 ms: 1.03x faster                                        |
| scimark_fft              | 180 ms                                                      | 175 ms: 1.03x faster                                         |
| coverage                 | 51.5 ms                                                     | 50.1 ms: 1.03x faster                                        |
| pprint_safe_repr         | 512 ms                                                      | 500 ms: 1.02x faster                                         |
| pprint_pformat           | 1.04 sec                                                    | 1.02 sec: 1.02x faster                                       |
| regex_dna                | 124 ms                                                      | 121 ms: 1.02x faster                                         |
| regex_compile            | 88.3 ms                                                     | 86.3 ms: 1.02x faster                                        |
| scimark_sor              | 79.6 ms                                                     | 77.9 ms: 1.02x faster                                        |
| xml_etree_process        | 38.4 ms                                                     | 37.6 ms: 1.02x faster                                        |
| regex_effbot             | 1.62 ms                                                     | 1.59 ms: 1.02x faster                                        |
| go                       | 88.5 ms                                                     | 86.7 ms: 1.02x faster                                        |
| pickle_list              | 2.86 us                                                     | 2.81 us: 1.02x faster                                        |
| float                    | 55.1 ms                                                     | 54.2 ms: 1.02x faster                                        |
| sqlglot_parse            | 820 us                                                      | 806 us: 1.02x faster                                         |
| raytrace                 | 191 ms                                                      | 188 ms: 1.02x faster                                         |
| sqlglot_transpile        | 1.04 ms                                                     | 1.02 ms: 1.02x faster                                        |
| scimark_lu               | 58.1 ms                                                     | 57.3 ms: 1.02x faster                                        |
| pyflate                  | 297 ms                                                      | 293 ms: 1.01x faster                                         |
| meteor_contest           | 73.1 ms                                                     | 72.1 ms: 1.01x faster                                        |
| deepcopy                 | 240 us                                                      | 237 us: 1.01x faster                                         |
| generators               | 22.7 ms                                                     | 22.5 ms: 1.01x faster                                        |
| aiohttp                  | 865 us                                                      | 854 us: 1.01x faster                                         |
| richards_super           | 30.5 ms                                                     | 30.1 ms: 1.01x faster                                        |
| fannkuch                 | 237 ms                                                      | 234 ms: 1.01x faster                                         |
| mako                     | 6.93 ms                                                     | 6.87 ms: 1.01x faster                                        |
| regex_v8                 | 13.9 ms                                                     | 13.7 ms: 1.01x faster                                        |
| xml_etree_generate       | 55.6 ms                                                     | 55.0 ms: 1.01x faster                                        |
| crypto_pyaes             | 47.4 ms                                                     | 47.0 ms: 1.01x faster                                        |
| richards                 | 26.9 ms                                                     | 26.7 ms: 1.01x faster                                        |
| 2to3                     | 214 ms                                                      | 213 ms: 1.01x faster                                         |
| logging_silent           | 60.6 ns                                                     | 60.2 ns: 1.01x faster                                        |
| chaos                    | 42.8 ms                                                     | 42.5 ms: 1.01x faster                                        |
| pickle_pure_python       | 196 us                                                      | 195 us: 1.00x faster                                         |
| async_generators         | 235 ms                                                      | 234 ms: 1.00x faster                                         |
| telco                    | 4.09 ms                                                     | 4.07 ms: 1.00x faster                                        |
| sqlite_synth             | 1.76 us                                                     | 1.75 us: 1.00x faster                                        |
| nqueens                  | 61.2 ms                                                     | 61.5 ms: 1.01x slower                                        |
| comprehensions           | 14.1 us                                                     | 14.2 us: 1.01x slower                                        |
| pickle                   | 7.13 us                                                     | 7.17 us: 1.01x slower                                        |
| sqlglot_optimize         | 34.4 ms                                                     | 34.6 ms: 1.01x slower                                        |
| mypy2                    | 207 ms                                                      | 208 ms: 1.01x slower                                         |
| docutils                 | 1.63 sec                                                    | 1.64 sec: 1.01x slower                                       |
| unpickle                 | 8.16 us                                                     | 8.21 us: 1.01x slower                                        |
| xml_etree_parse          | 89.2 ms                                                     | 89.8 ms: 1.01x slower                                        |
| logging_format           | 6.67 us                                                     | 6.74 us: 1.01x slower                                        |
| typing_runtime_protocols | 95.2 us                                                     | 96.2 us: 1.01x slower                                        |
| bench_mp_pool            | 66.4 ms                                                     | 67.2 ms: 1.01x slower                                        |
| pycparser                | 673 ms                                                      | 682 ms: 1.01x slower                                         |
| deltablue                | 2.14 ms                                                     | 2.16 ms: 1.01x slower                                        |
| spectral_norm            | 63.2 ms                                                     | 64.0 ms: 1.01x slower                                        |
| python_startup_no_site   | 16.1 ms                                                     | 16.4 ms: 1.02x slower                                        |
| logging_simple           | 6.21 us                                                     | 6.32 us: 1.02x slower                                        |
| json                     | 2.86 ms                                                     | 2.91 ms: 1.02x slower                                        |
| json_dumps               | 5.60 ms                                                     | 5.70 ms: 1.02x slower                                        |
| pathlib                  | 77.1 ms                                                     | 78.9 ms: 1.02x slower                                        |
| dask                     | 259 ms                                                      | 361 ms: 1.39x slower                                         |
| Geometric mean           | (ref)                                                       | 1.00x faster                                                 |

Benchmark hidden because not significant (23): asyncio_tcp_ssl, async_tree_none, python_startup, create_gc_cycles, tornado_http, unpickle_pure_python, bench_thread_pool, sqlglot_normalize, pidigits, async_tree_cpu_io_mixed, hexiom, tomli_loads, coroutines, dulwich_log, async_tree_memoization, asyncio_tcp, gc_traversal, scimark_sparse_mat_mult, json_loads, xml_etree_iterparse, async_tree_io, unpack_sequence, deepcopy_memo


# HPT report

- Reliability score: 99.81% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
