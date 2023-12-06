
# Results vs. 3.12.0

- fork: python
- ref: 3.12
- machine: windows-amd64
- commit hash: f6287bd
- commit date: 2023-09-22
- overall geometric mean: 1.00x faster
- HPT reliability: 99.26%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230922-pythonperf1-amd64-python-3.12-3.12.0rc3+-f6287bd |
|----------------|:-----------------------------------------------------------:|:------------------------------------------------------------:|
| 2to3           | 214 ms                                                      | 211 ms: 1.01x faster                                         |
| docutils       | 1.63 sec                                                    | 1.62 sec: 1.01x faster                                       |
| Geometric mean | (ref)                                                       | 1.01x faster                                                 |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230922-pythonperf1-amd64-python-3.12-3.12.0rc3+-f6287bd |
|----------------|:-----------------------------------------------------------:|:------------------------------------------------------------:|
| float          | 55.1 ms                                                     | 54.5 ms: 1.01x faster                                        |
| Geometric mean | (ref)                                                       | 1.01x faster                                                 |

Benchmark hidden because not significant (2): nbody, pidigits

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230922-pythonperf1-amd64-python-3.12-3.12.0rc3+-f6287bd |
|----------------|:-----------------------------------------------------------:|:------------------------------------------------------------:|
| regex_dna      | 124 ms                                                      | 118 ms: 1.05x faster                                         |
| regex_effbot   | 1.62 ms                                                     | 1.58 ms: 1.03x faster                                        |
| regex_v8       | 13.9 ms                                                     | 13.5 ms: 1.03x faster                                        |
| regex_compile  | 88.3 ms                                                     | 86.9 ms: 1.02x faster                                        |
| Geometric mean | (ref)                                                       | 1.03x faster                                                 |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230922-pythonperf1-amd64-python-3.12-3.12.0rc3+-f6287bd |
|----------------------|:-----------------------------------------------------------:|:------------------------------------------------------------:|
| pickle_dict          | 19.3 us                                                     | 18.4 us: 1.05x faster                                        |
| unpickle_list        | 2.78 us                                                     | 2.68 us: 1.04x faster                                        |
| pickle_pure_python   | 196 us                                                      | 192 us: 1.02x faster                                         |
| pickle               | 7.13 us                                                     | 7.09 us: 1.01x faster                                        |
| xml_etree_process    | 38.4 ms                                                     | 38.2 ms: 1.01x faster                                        |
| tomli_loads          | 1.37 sec                                                    | 1.36 sec: 1.01x faster                                       |
| pickle_list          | 2.86 us                                                     | 2.88 us: 1.01x slower                                        |
| json_loads           | 13.4 us                                                     | 13.6 us: 1.01x slower                                        |
| unpickle_pure_python | 133 us                                                      | 135 us: 1.01x slower                                         |
| xml_etree_iterparse  | 62.5 ms                                                     | 63.4 ms: 1.01x slower                                        |
| json_dumps           | 5.60 ms                                                     | 5.68 ms: 1.02x slower                                        |
| xml_etree_parse      | 89.2 ms                                                     | 90.9 ms: 1.02x slower                                        |
| unpickle             | 8.16 us                                                     | 8.40 us: 1.03x slower                                        |
| Geometric mean       | (ref)                                                       | 1.00x faster                                                 |

Benchmark hidden because not significant (1): xml_etree_generate

Benchmarks with tag 'startup':
==============================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230922-pythonperf1-amd64-python-3.12-3.12.0rc3+-f6287bd |
|----------------|:-----------------------------------------------------------:|:------------------------------------------------------------:|
| python_startup | 19.5 ms                                                     | 18.8 ms: 1.03x faster                                        |
| Geometric mean | (ref)                                                       | 1.02x faster                                                 |

Benchmark hidden because not significant (1): python_startup_no_site

Benchmarks with tag 'template':
===============================

Benchmark hidden because not significant (1): mako

All benchmarks:
===============

| Benchmark                | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230922-pythonperf1-amd64-python-3.12-3.12.0rc3+-f6287bd |
|--------------------------|:-----------------------------------------------------------:|:------------------------------------------------------------:|
| asyncio_tcp_ssl          | 1.96 sec                                                    | 1.87 sec: 1.05x faster                                       |
| regex_dna                | 124 ms                                                      | 118 ms: 1.05x faster                                         |
| pickle_dict              | 19.3 us                                                     | 18.4 us: 1.05x faster                                        |
| unpickle_list            | 2.78 us                                                     | 2.68 us: 1.04x faster                                        |
| python_startup           | 19.5 ms                                                     | 18.8 ms: 1.03x faster                                        |
| crypto_pyaes             | 47.4 ms                                                     | 46.0 ms: 1.03x faster                                        |
| regex_effbot             | 1.62 ms                                                     | 1.58 ms: 1.03x faster                                        |
| regex_v8                 | 13.9 ms                                                     | 13.5 ms: 1.03x faster                                        |
| bench_thread_pool        | 844 us                                                      | 825 us: 1.02x faster                                         |
| async_tree_none          | 294 ms                                                      | 288 ms: 1.02x faster                                         |
| pickle_pure_python       | 196 us                                                      | 192 us: 1.02x faster                                         |
| regex_compile            | 88.3 ms                                                     | 86.9 ms: 1.02x faster                                        |
| 2to3                     | 214 ms                                                      | 211 ms: 1.01x faster                                         |
| deepcopy                 | 240 us                                                      | 237 us: 1.01x faster                                         |
| sqlglot_transpile        | 1.04 ms                                                     | 1.02 ms: 1.01x faster                                        |
| aiohttp                  | 865 us                                                      | 854 us: 1.01x faster                                         |
| sqlglot_parse            | 820 us                                                      | 809 us: 1.01x faster                                         |
| richards                 | 26.9 ms                                                     | 26.6 ms: 1.01x faster                                        |
| pprint_pformat           | 1.04 sec                                                    | 1.03 sec: 1.01x faster                                       |
| scimark_fft              | 180 ms                                                      | 178 ms: 1.01x faster                                         |
| deepcopy_reduce          | 2.13 us                                                     | 2.11 us: 1.01x faster                                        |
| float                    | 55.1 ms                                                     | 54.5 ms: 1.01x faster                                        |
| async_generators         | 235 ms                                                      | 233 ms: 1.01x faster                                         |
| go                       | 88.5 ms                                                     | 87.5 ms: 1.01x faster                                        |
| comprehensions           | 14.1 us                                                     | 14.0 us: 1.01x faster                                        |
| sqlglot_normalize        | 185 ms                                                      | 184 ms: 1.01x faster                                         |
| meteor_contest           | 73.1 ms                                                     | 72.4 ms: 1.01x faster                                        |
| logging_format           | 6.67 us                                                     | 6.61 us: 1.01x faster                                        |
| raytrace                 | 191 ms                                                      | 190 ms: 1.01x faster                                         |
| pprint_safe_repr         | 512 ms                                                      | 508 ms: 1.01x faster                                         |
| chaos                    | 42.8 ms                                                     | 42.4 ms: 1.01x faster                                        |
| hexiom                   | 4.03 ms                                                     | 4.00 ms: 1.01x faster                                        |
| logging_simple           | 6.21 us                                                     | 6.17 us: 1.01x faster                                        |
| docutils                 | 1.63 sec                                                    | 1.62 sec: 1.01x faster                                       |
| pickle                   | 7.13 us                                                     | 7.09 us: 1.01x faster                                        |
| sqlglot_optimize         | 34.4 ms                                                     | 34.2 ms: 1.01x faster                                        |
| deltablue                | 2.14 ms                                                     | 2.13 ms: 1.01x faster                                        |
| xml_etree_process        | 38.4 ms                                                     | 38.2 ms: 1.01x faster                                        |
| tomli_loads              | 1.37 sec                                                    | 1.36 sec: 1.01x faster                                       |
| pycparser                | 673 ms                                                      | 670 ms: 1.00x faster                                         |
| telco                    | 4.09 ms                                                     | 4.07 ms: 1.00x faster                                        |
| pyflate                  | 297 ms                                                      | 296 ms: 1.00x faster                                         |
| richards_super           | 30.5 ms                                                     | 30.4 ms: 1.00x faster                                        |
| nqueens                  | 61.2 ms                                                     | 61.5 ms: 1.00x slower                                        |
| scimark_sparse_mat_mult  | 2.48 ms                                                     | 2.49 ms: 1.00x slower                                        |
| fannkuch                 | 237 ms                                                      | 238 ms: 1.01x slower                                         |
| bench_mp_pool            | 66.4 ms                                                     | 66.8 ms: 1.01x slower                                        |
| scimark_lu               | 58.1 ms                                                     | 58.5 ms: 1.01x slower                                        |
| pickle_list              | 2.86 us                                                     | 2.88 us: 1.01x slower                                        |
| mypy2                    | 207 ms                                                      | 209 ms: 1.01x slower                                         |
| json_loads               | 13.4 us                                                     | 13.6 us: 1.01x slower                                        |
| typing_runtime_protocols | 95.2 us                                                     | 96.0 us: 1.01x slower                                        |
| json                     | 2.86 ms                                                     | 2.89 ms: 1.01x slower                                        |
| scimark_monte_carlo      | 43.7 ms                                                     | 44.1 ms: 1.01x slower                                        |
| unpickle_pure_python     | 133 us                                                      | 135 us: 1.01x slower                                         |
| pathlib                  | 77.1 ms                                                     | 78.2 ms: 1.01x slower                                        |
| xml_etree_iterparse      | 62.5 ms                                                     | 63.4 ms: 1.01x slower                                        |
| json_dumps               | 5.60 ms                                                     | 5.68 ms: 1.02x slower                                        |
| scimark_sor              | 79.6 ms                                                     | 80.9 ms: 1.02x slower                                        |
| xml_etree_parse          | 89.2 ms                                                     | 90.9 ms: 1.02x slower                                        |
| coroutines               | 14.0 ms                                                     | 14.3 ms: 1.02x slower                                        |
| coverage                 | 51.5 ms                                                     | 52.7 ms: 1.02x slower                                        |
| unpack_sequence          | 37.5 ns                                                     | 38.5 ns: 1.03x slower                                        |
| unpickle                 | 8.16 us                                                     | 8.40 us: 1.03x slower                                        |
| mdp                      | 1.44 sec                                                    | 1.52 sec: 1.05x slower                                       |
| dask                     | 259 ms                                                      | 362 ms: 1.40x slower                                         |
| Geometric mean           | (ref)                                                       | 1.00x faster                                                 |

Benchmark hidden because not significant (18): asyncio_tcp, nbody, python_startup_no_site, async_tree_io, async_tree_cpu_io_mixed, deepcopy_memo, sqlite_synth, create_gc_cycles, tornado_http, mako, pidigits, xml_etree_generate, spectral_norm, dulwich_log, logging_silent, async_tree_memoization, generators, gc_traversal


# HPT report

- Reliability score: 99.26% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
