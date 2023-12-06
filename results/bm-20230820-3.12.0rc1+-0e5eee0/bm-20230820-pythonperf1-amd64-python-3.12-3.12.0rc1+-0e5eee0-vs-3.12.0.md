
# Results vs. 3.12.0

- fork: python
- ref: 3.12
- machine: windows-amd64
- commit hash: 0e5eee0
- commit date: 2023-08-20
- overall geometric mean: 1.00x faster
- HPT reliability: 99.99%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230820-pythonperf1-amd64-python-3.12-3.12.0rc1+-0e5eee0 |
|----------------|:-----------------------------------------------------------:|:------------------------------------------------------------:|
| 2to3           | 214 ms                                                      | 212 ms: 1.01x faster                                         |
| docutils       | 1.63 sec                                                    | 1.60 sec: 1.02x faster                                       |
| Geometric mean | (ref)                                                       | 1.01x faster                                                 |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230820-pythonperf1-amd64-python-3.12-3.12.0rc1+-0e5eee0 |
|----------------|:-----------------------------------------------------------:|:------------------------------------------------------------:|
| float          | 55.1 ms                                                     | 53.3 ms: 1.03x faster                                        |
| nbody          | 72.6 ms                                                     | 70.2 ms: 1.03x faster                                        |
| pidigits       | 150 ms                                                      | 147 ms: 1.02x faster                                         |
| Geometric mean | (ref)                                                       | 1.03x faster                                                 |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230820-pythonperf1-amd64-python-3.12-3.12.0rc1+-0e5eee0 |
|----------------|:-----------------------------------------------------------:|:------------------------------------------------------------:|
| regex_dna      | 124 ms                                                      | 119 ms: 1.04x faster                                         |
| regex_v8       | 13.9 ms                                                     | 13.3 ms: 1.04x faster                                        |
| regex_effbot   | 1.62 ms                                                     | 1.58 ms: 1.03x faster                                        |
| regex_compile  | 88.3 ms                                                     | 86.7 ms: 1.02x faster                                        |
| Geometric mean | (ref)                                                       | 1.03x faster                                                 |

Benchmarks with tag 'serialize':
================================

| Benchmark          | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230820-pythonperf1-amd64-python-3.12-3.12.0rc1+-0e5eee0 |
|--------------------|:-----------------------------------------------------------:|:------------------------------------------------------------:|
| pickle_dict        | 19.3 us                                                     | 18.2 us: 1.06x faster                                        |
| xml_etree_process  | 38.4 ms                                                     | 37.8 ms: 1.01x faster                                        |
| pickle_pure_python | 196 us                                                      | 193 us: 1.01x faster                                         |
| tomli_loads        | 1.37 sec                                                    | 1.36 sec: 1.01x faster                                       |
| xml_etree_generate | 55.6 ms                                                     | 55.1 ms: 1.01x faster                                        |
| json_loads         | 13.4 us                                                     | 13.5 us: 1.01x slower                                        |
| xml_etree_parse    | 89.2 ms                                                     | 89.8 ms: 1.01x slower                                        |
| json_dumps         | 5.60 ms                                                     | 5.65 ms: 1.01x slower                                        |
| pickle             | 7.13 us                                                     | 7.27 us: 1.02x slower                                        |
| unpickle           | 8.16 us                                                     | 8.37 us: 1.03x slower                                        |
| Geometric mean     | (ref)                                                       | 1.00x faster                                                 |

Benchmark hidden because not significant (4): unpickle_list, xml_etree_iterparse, pickle_list, unpickle_pure_python

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230820-pythonperf1-amd64-python-3.12-3.12.0rc1+-0e5eee0 |
|------------------------|:-----------------------------------------------------------:|:------------------------------------------------------------:|
| python_startup_no_site | 16.1 ms                                                     | 16.7 ms: 1.03x slower                                        |
| Geometric mean         | (ref)                                                       | 1.02x slower                                                 |

Benchmark hidden because not significant (1): python_startup

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230820-pythonperf1-amd64-python-3.12-3.12.0rc1+-0e5eee0 |
|-----------|:-----------------------------------------------------------:|:------------------------------------------------------------:|
| mako      | 6.93 ms                                                     | 6.80 ms: 1.02x faster                                        |

All benchmarks:
===============

| Benchmark                | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230820-pythonperf1-amd64-python-3.12-3.12.0rc1+-0e5eee0 |
|--------------------------|:-----------------------------------------------------------:|:------------------------------------------------------------:|
| pickle_dict              | 19.3 us                                                     | 18.2 us: 1.06x faster                                        |
| scimark_fft              | 180 ms                                                      | 172 ms: 1.05x faster                                         |
| regex_dna                | 124 ms                                                      | 119 ms: 1.04x faster                                         |
| regex_v8                 | 13.9 ms                                                     | 13.3 ms: 1.04x faster                                        |
| scimark_monte_carlo      | 43.7 ms                                                     | 42.1 ms: 1.04x faster                                        |
| generators               | 22.7 ms                                                     | 21.9 ms: 1.04x faster                                        |
| mdp                      | 1.44 sec                                                    | 1.39 sec: 1.04x faster                                       |
| float                    | 55.1 ms                                                     | 53.3 ms: 1.03x faster                                        |
| nbody                    | 72.6 ms                                                     | 70.2 ms: 1.03x faster                                        |
| dulwich_log              | 42.4 ms                                                     | 41.1 ms: 1.03x faster                                        |
| sqlglot_normalize        | 185 ms                                                      | 180 ms: 1.03x faster                                         |
| regex_effbot             | 1.62 ms                                                     | 1.58 ms: 1.03x faster                                        |
| deepcopy                 | 240 us                                                      | 234 us: 1.03x faster                                         |
| pprint_pformat           | 1.04 sec                                                    | 1.02 sec: 1.03x faster                                       |
| async_tree_none          | 294 ms                                                      | 287 ms: 1.03x faster                                         |
| richards                 | 26.9 ms                                                     | 26.2 ms: 1.03x faster                                        |
| pyflate                  | 297 ms                                                      | 290 ms: 1.02x faster                                         |
| pprint_safe_repr         | 512 ms                                                      | 500 ms: 1.02x faster                                         |
| richards_super           | 30.5 ms                                                     | 29.8 ms: 1.02x faster                                        |
| scimark_lu               | 58.1 ms                                                     | 56.9 ms: 1.02x faster                                        |
| pidigits                 | 150 ms                                                      | 147 ms: 1.02x faster                                         |
| telco                    | 4.09 ms                                                     | 4.01 ms: 1.02x faster                                        |
| mako                     | 6.93 ms                                                     | 6.80 ms: 1.02x faster                                        |
| meteor_contest           | 73.1 ms                                                     | 71.7 ms: 1.02x faster                                        |
| sqlglot_parse            | 820 us                                                      | 804 us: 1.02x faster                                         |
| sqlglot_transpile        | 1.04 ms                                                     | 1.02 ms: 1.02x faster                                        |
| nqueens                  | 61.2 ms                                                     | 60.1 ms: 1.02x faster                                        |
| sqlglot_optimize         | 34.4 ms                                                     | 33.8 ms: 1.02x faster                                        |
| regex_compile            | 88.3 ms                                                     | 86.7 ms: 1.02x faster                                        |
| deepcopy_memo            | 23.8 us                                                     | 23.4 us: 1.02x faster                                        |
| docutils                 | 1.63 sec                                                    | 1.60 sec: 1.02x faster                                       |
| raytrace                 | 191 ms                                                      | 188 ms: 1.02x faster                                         |
| xml_etree_process        | 38.4 ms                                                     | 37.8 ms: 1.01x faster                                        |
| crypto_pyaes             | 47.4 ms                                                     | 46.7 ms: 1.01x faster                                        |
| pickle_pure_python       | 196 us                                                      | 193 us: 1.01x faster                                         |
| 2to3                     | 214 ms                                                      | 212 ms: 1.01x faster                                         |
| deltablue                | 2.14 ms                                                     | 2.11 ms: 1.01x faster                                        |
| go                       | 88.5 ms                                                     | 87.5 ms: 1.01x faster                                        |
| logging_silent           | 60.6 ns                                                     | 59.9 ns: 1.01x faster                                        |
| tomli_loads              | 1.37 sec                                                    | 1.36 sec: 1.01x faster                                       |
| scimark_sparse_mat_mult  | 2.48 ms                                                     | 2.46 ms: 1.01x faster                                        |
| xml_etree_generate       | 55.6 ms                                                     | 55.1 ms: 1.01x faster                                        |
| coverage                 | 51.5 ms                                                     | 51.1 ms: 1.01x faster                                        |
| sqlite_synth             | 1.76 us                                                     | 1.74 us: 1.01x faster                                        |
| hexiom                   | 4.03 ms                                                     | 4.01 ms: 1.01x faster                                        |
| async_generators         | 235 ms                                                      | 234 ms: 1.01x faster                                         |
| bench_mp_pool            | 66.4 ms                                                     | 66.1 ms: 1.00x faster                                        |
| chaos                    | 42.8 ms                                                     | 43.0 ms: 1.01x slower                                        |
| scimark_sor              | 79.6 ms                                                     | 80.1 ms: 1.01x slower                                        |
| mypy2                    | 207 ms                                                      | 208 ms: 1.01x slower                                         |
| json_loads               | 13.4 us                                                     | 13.5 us: 1.01x slower                                        |
| xml_etree_parse          | 89.2 ms                                                     | 89.8 ms: 1.01x slower                                        |
| comprehensions           | 14.1 us                                                     | 14.2 us: 1.01x slower                                        |
| json_dumps               | 5.60 ms                                                     | 5.65 ms: 1.01x slower                                        |
| pathlib                  | 77.1 ms                                                     | 77.9 ms: 1.01x slower                                        |
| fannkuch                 | 237 ms                                                      | 240 ms: 1.01x slower                                         |
| pickle                   | 7.13 us                                                     | 7.27 us: 1.02x slower                                        |
| coroutines               | 14.0 ms                                                     | 14.3 ms: 1.02x slower                                        |
| unpickle                 | 8.16 us                                                     | 8.37 us: 1.03x slower                                        |
| unpack_sequence          | 37.5 ns                                                     | 38.5 ns: 1.03x slower                                        |
| typing_runtime_protocols | 95.2 us                                                     | 98.4 us: 1.03x slower                                        |
| python_startup_no_site   | 16.1 ms                                                     | 16.7 ms: 1.03x slower                                        |
| json                     | 2.86 ms                                                     | 2.97 ms: 1.04x slower                                        |
| spectral_norm            | 63.2 ms                                                     | 66.3 ms: 1.05x slower                                        |
| dask                     | 259 ms                                                      | 362 ms: 1.39x slower                                         |
| Geometric mean           | (ref)                                                       | 1.00x faster                                                 |

Benchmark hidden because not significant (19): bench_thread_pool, create_gc_cycles, async_tree_memoization, async_tree_cpu_io_mixed, async_tree_io, gc_traversal, aiohttp, tornado_http, deepcopy_reduce, logging_simple, unpickle_list, xml_etree_iterparse, pycparser, logging_format, python_startup, pickle_list, asyncio_tcp, unpickle_pure_python, asyncio_tcp_ssl


# HPT report

- Reliability score: 99.99% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
