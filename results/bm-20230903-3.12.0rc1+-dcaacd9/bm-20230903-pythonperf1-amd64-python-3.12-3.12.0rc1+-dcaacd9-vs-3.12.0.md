
# Results vs. 3.12.0

- fork: python
- ref: 3.12
- machine: windows-amd64
- commit hash: dcaacd9
- commit date: 2023-09-03
- overall geometric mean: 1.01x slower
- HPT reliability: 90.36%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

Benchmark hidden because not significant (3): 2to3, docutils, tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230903-pythonperf1-amd64-python-3.12-3.12.0rc1+-dcaacd9 |
|----------------|:-----------------------------------------------------------:|:------------------------------------------------------------:|
| nbody          | 72.6 ms                                                     | 70.9 ms: 1.03x faster                                        |
| pidigits       | 150 ms                                                      | 150 ms: 1.00x faster                                         |
| float          | 55.1 ms                                                     | 55.9 ms: 1.01x slower                                        |
| Geometric mean | (ref)                                                       | 1.00x faster                                                 |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230903-pythonperf1-amd64-python-3.12-3.12.0rc1+-dcaacd9 |
|----------------|:-----------------------------------------------------------:|:------------------------------------------------------------:|
| regex_compile  | 88.3 ms                                                     | 87.3 ms: 1.01x faster                                        |
| regex_effbot   | 1.62 ms                                                     | 1.61 ms: 1.01x faster                                        |
| regex_v8       | 13.9 ms                                                     | 14.1 ms: 1.02x slower                                        |
| Geometric mean | (ref)                                                       | 1.00x slower                                                 |

Benchmark hidden because not significant (1): regex_dna

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230903-pythonperf1-amd64-python-3.12-3.12.0rc1+-dcaacd9 |
|----------------------|:-----------------------------------------------------------:|:------------------------------------------------------------:|
| pickle_dict          | 19.3 us                                                     | 18.2 us: 1.06x faster                                        |
| pickle_list          | 2.86 us                                                     | 2.80 us: 1.02x faster                                        |
| xml_etree_process    | 38.4 ms                                                     | 37.9 ms: 1.01x faster                                        |
| tomli_loads          | 1.37 sec                                                    | 1.36 sec: 1.01x faster                                       |
| pickle_pure_python   | 196 us                                                      | 196 us: 1.00x slower                                         |
| json_loads           | 13.4 us                                                     | 13.5 us: 1.01x slower                                        |
| xml_etree_parse      | 89.2 ms                                                     | 90.0 ms: 1.01x slower                                        |
| pickle               | 7.13 us                                                     | 7.20 us: 1.01x slower                                        |
| json_dumps           | 5.60 ms                                                     | 5.65 ms: 1.01x slower                                        |
| unpickle_pure_python | 133 us                                                      | 135 us: 1.01x slower                                         |
| Geometric mean       | (ref)                                                       | 1.00x faster                                                 |

Benchmark hidden because not significant (4): xml_etree_generate, xml_etree_iterparse, unpickle_list, unpickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230903-pythonperf1-amd64-python-3.12-3.12.0rc1+-dcaacd9 |
|------------------------|:-----------------------------------------------------------:|:------------------------------------------------------------:|
| python_startup_no_site | 16.1 ms                                                     | 16.3 ms: 1.01x slower                                        |
| Geometric mean         | (ref)                                                       | 1.00x slower                                                 |

Benchmark hidden because not significant (1): python_startup

Benchmarks with tag 'template':
===============================

Benchmark hidden because not significant (1): mako

All benchmarks:
===============

| Benchmark                | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230903-pythonperf1-amd64-python-3.12-3.12.0rc1+-dcaacd9 |
|--------------------------|:-----------------------------------------------------------:|:------------------------------------------------------------:|
| pickle_dict              | 19.3 us                                                     | 18.2 us: 1.06x faster                                        |
| richards                 | 26.9 ms                                                     | 26.1 ms: 1.03x faster                                        |
| unpack_sequence          | 37.5 ns                                                     | 36.5 ns: 1.03x faster                                        |
| nbody                    | 72.6 ms                                                     | 70.9 ms: 1.03x faster                                        |
| richards_super           | 30.5 ms                                                     | 29.8 ms: 1.02x faster                                        |
| coverage                 | 51.5 ms                                                     | 50.3 ms: 1.02x faster                                        |
| pickle_list              | 2.86 us                                                     | 2.80 us: 1.02x faster                                        |
| scimark_sor              | 79.6 ms                                                     | 78.1 ms: 1.02x faster                                        |
| scimark_fft              | 180 ms                                                      | 177 ms: 1.02x faster                                         |
| generators               | 22.7 ms                                                     | 22.4 ms: 1.02x faster                                        |
| aiohttp                  | 865 us                                                      | 853 us: 1.01x faster                                         |
| xml_etree_process        | 38.4 ms                                                     | 37.9 ms: 1.01x faster                                        |
| regex_compile            | 88.3 ms                                                     | 87.3 ms: 1.01x faster                                        |
| telco                    | 4.09 ms                                                     | 4.05 ms: 1.01x faster                                        |
| pyflate                  | 297 ms                                                      | 294 ms: 1.01x faster                                         |
| meteor_contest           | 73.1 ms                                                     | 72.5 ms: 1.01x faster                                        |
| sqlglot_parse            | 820 us                                                      | 813 us: 1.01x faster                                         |
| go                       | 88.5 ms                                                     | 87.8 ms: 1.01x faster                                        |
| regex_effbot             | 1.62 ms                                                     | 1.61 ms: 1.01x faster                                        |
| tomli_loads              | 1.37 sec                                                    | 1.36 sec: 1.01x faster                                       |
| pidigits                 | 150 ms                                                      | 150 ms: 1.00x faster                                         |
| pprint_pformat           | 1.04 sec                                                    | 1.05 sec: 1.00x slower                                       |
| raytrace                 | 191 ms                                                      | 192 ms: 1.00x slower                                         |
| pickle_pure_python       | 196 us                                                      | 196 us: 1.00x slower                                         |
| pprint_safe_repr         | 512 ms                                                      | 515 ms: 1.01x slower                                         |
| chaos                    | 42.8 ms                                                     | 43.0 ms: 1.01x slower                                        |
| json_loads               | 13.4 us                                                     | 13.5 us: 1.01x slower                                        |
| scimark_sparse_mat_mult  | 2.48 ms                                                     | 2.50 ms: 1.01x slower                                        |
| logging_format           | 6.67 us                                                     | 6.73 us: 1.01x slower                                        |
| xml_etree_parse          | 89.2 ms                                                     | 90.0 ms: 1.01x slower                                        |
| bench_mp_pool            | 66.4 ms                                                     | 67.0 ms: 1.01x slower                                        |
| sqlglot_optimize         | 34.4 ms                                                     | 34.7 ms: 1.01x slower                                        |
| mypy2                    | 207 ms                                                      | 209 ms: 1.01x slower                                         |
| pickle                   | 7.13 us                                                     | 7.20 us: 1.01x slower                                        |
| json_dumps               | 5.60 ms                                                     | 5.65 ms: 1.01x slower                                        |
| async_generators         | 235 ms                                                      | 238 ms: 1.01x slower                                         |
| logging_simple           | 6.21 us                                                     | 6.29 us: 1.01x slower                                        |
| unpickle_pure_python     | 133 us                                                      | 135 us: 1.01x slower                                         |
| deepcopy                 | 240 us                                                      | 243 us: 1.01x slower                                         |
| float                    | 55.1 ms                                                     | 55.9 ms: 1.01x slower                                        |
| python_startup_no_site   | 16.1 ms                                                     | 16.3 ms: 1.01x slower                                        |
| nqueens                  | 61.2 ms                                                     | 62.1 ms: 1.01x slower                                        |
| sqlglot_normalize        | 185 ms                                                      | 188 ms: 1.02x slower                                         |
| comprehensions           | 14.1 us                                                     | 14.4 us: 1.02x slower                                        |
| regex_v8                 | 13.9 ms                                                     | 14.1 ms: 1.02x slower                                        |
| pathlib                  | 77.1 ms                                                     | 78.7 ms: 1.02x slower                                        |
| scimark_lu               | 58.1 ms                                                     | 59.3 ms: 1.02x slower                                        |
| json                     | 2.86 ms                                                     | 2.93 ms: 1.02x slower                                        |
| scimark_monte_carlo      | 43.7 ms                                                     | 44.7 ms: 1.02x slower                                        |
| typing_runtime_protocols | 95.2 us                                                     | 97.6 us: 1.03x slower                                        |
| fannkuch                 | 237 ms                                                      | 243 ms: 1.03x slower                                         |
| pycparser                | 673 ms                                                      | 693 ms: 1.03x slower                                         |
| coroutines               | 14.0 ms                                                     | 14.4 ms: 1.03x slower                                        |
| mdp                      | 1.44 sec                                                    | 1.50 sec: 1.04x slower                                       |
| dask                     | 259 ms                                                      | 361 ms: 1.39x slower                                         |
| Geometric mean           | (ref)                                                       | 1.01x slower                                                 |

Benchmark hidden because not significant (29): async_tree_none, python_startup, logging_silent, deltablue, xml_etree_generate, bench_thread_pool, deepcopy_memo, mako, dulwich_log, sqlite_synth, sqlglot_transpile, 2to3, spectral_norm, async_tree_io, create_gc_cycles, crypto_pyaes, gc_traversal, asyncio_tcp, hexiom, regex_dna, deepcopy_reduce, async_tree_cpu_io_mixed, docutils, xml_etree_iterparse, unpickle_list, unpickle, tornado_http, async_tree_memoization, asyncio_tcp_ssl


# HPT report

- Reliability score: 90.36% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
