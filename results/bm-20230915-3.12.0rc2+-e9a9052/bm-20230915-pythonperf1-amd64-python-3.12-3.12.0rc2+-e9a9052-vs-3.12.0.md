
# Results vs. 3.12.0

- fork: python
- ref: 3.12
- machine: windows-amd64
- commit hash: e9a9052
- commit date: 2023-09-15
- overall geometric mean: 1.02x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

Benchmark hidden because not significant (3): 2to3, docutils, tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230915-pythonperf1-amd64-python-3.12-3.12.0rc2+-e9a9052 |
|----------------|:-----------------------------------------------------------:|:------------------------------------------------------------:|
| float          | 55.1 ms                                                     | 56.6 ms: 1.03x slower                                        |
| Geometric mean | (ref)                                                       | 1.00x slower                                                 |

Benchmark hidden because not significant (2): nbody, pidigits

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230915-pythonperf1-amd64-python-3.12-3.12.0rc2+-e9a9052 |
|----------------|:-----------------------------------------------------------:|:------------------------------------------------------------:|
| regex_dna      | 124 ms                                                      | 118 ms: 1.05x faster                                         |
| regex_effbot   | 1.62 ms                                                     | 1.58 ms: 1.03x faster                                        |
| regex_compile  | 88.3 ms                                                     | 88.9 ms: 1.01x slower                                        |
| regex_v8       | 13.9 ms                                                     | 14.1 ms: 1.02x slower                                        |
| Geometric mean | (ref)                                                       | 1.01x faster                                                 |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230915-pythonperf1-amd64-python-3.12-3.12.0rc2+-e9a9052 |
|----------------------|:-----------------------------------------------------------:|:------------------------------------------------------------:|
| unpickle_list        | 2.78 us                                                     | 2.67 us: 1.04x faster                                        |
| pickle_dict          | 19.3 us                                                     | 18.7 us: 1.03x faster                                        |
| pickle               | 7.13 us                                                     | 7.17 us: 1.00x slower                                        |
| pickle_list          | 2.86 us                                                     | 2.88 us: 1.01x slower                                        |
| xml_etree_process    | 38.4 ms                                                     | 38.8 ms: 1.01x slower                                        |
| json_loads           | 13.4 us                                                     | 13.6 us: 1.01x slower                                        |
| unpickle             | 8.16 us                                                     | 8.32 us: 1.02x slower                                        |
| xml_etree_iterparse  | 62.5 ms                                                     | 63.9 ms: 1.02x slower                                        |
| pickle_pure_python   | 196 us                                                      | 200 us: 1.02x slower                                         |
| xml_etree_parse      | 89.2 ms                                                     | 91.7 ms: 1.03x slower                                        |
| xml_etree_generate   | 55.6 ms                                                     | 57.2 ms: 1.03x slower                                        |
| json_dumps           | 5.60 ms                                                     | 5.79 ms: 1.03x slower                                        |
| tomli_loads          | 1.37 sec                                                    | 1.42 sec: 1.03x slower                                       |
| unpickle_pure_python | 133 us                                                      | 140 us: 1.05x slower                                         |
| Geometric mean       | (ref)                                                       | 1.01x slower                                                 |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230915-pythonperf1-amd64-python-3.12-3.12.0rc2+-e9a9052 |
|------------------------|:-----------------------------------------------------------:|:------------------------------------------------------------:|
| python_startup         | 19.5 ms                                                     | 18.9 ms: 1.03x faster                                        |
| python_startup_no_site | 16.1 ms                                                     | 15.9 ms: 1.02x faster                                        |
| Geometric mean         | (ref)                                                       | 1.02x faster                                                 |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230915-pythonperf1-amd64-python-3.12-3.12.0rc2+-e9a9052 |
|-----------|:-----------------------------------------------------------:|:------------------------------------------------------------:|
| mako      | 6.93 ms                                                     | 7.03 ms: 1.01x slower                                        |

All benchmarks:
===============

| Benchmark                | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230915-pythonperf1-amd64-python-3.12-3.12.0rc2+-e9a9052 |
|--------------------------|:-----------------------------------------------------------:|:------------------------------------------------------------:|
| regex_dna                | 124 ms                                                      | 118 ms: 1.05x faster                                         |
| unpickle_list            | 2.78 us                                                     | 2.67 us: 1.04x faster                                        |
| pickle_dict              | 19.3 us                                                     | 18.7 us: 1.03x faster                                        |
| regex_effbot             | 1.62 ms                                                     | 1.58 ms: 1.03x faster                                        |
| python_startup           | 19.5 ms                                                     | 18.9 ms: 1.03x faster                                        |
| python_startup_no_site   | 16.1 ms                                                     | 15.9 ms: 1.02x faster                                        |
| generators               | 22.7 ms                                                     | 22.5 ms: 1.01x faster                                        |
| async_generators         | 235 ms                                                      | 234 ms: 1.00x faster                                         |
| coroutines               | 14.0 ms                                                     | 14.0 ms: 1.00x slower                                        |
| pickle                   | 7.13 us                                                     | 7.17 us: 1.00x slower                                        |
| sqlglot_optimize         | 34.4 ms                                                     | 34.6 ms: 1.01x slower                                        |
| deepcopy_reduce          | 2.13 us                                                     | 2.15 us: 1.01x slower                                        |
| mypy2                    | 207 ms                                                      | 209 ms: 1.01x slower                                         |
| regex_compile            | 88.3 ms                                                     | 88.9 ms: 1.01x slower                                        |
| pickle_list              | 2.86 us                                                     | 2.88 us: 1.01x slower                                        |
| pathlib                  | 77.1 ms                                                     | 77.8 ms: 1.01x slower                                        |
| sqlglot_normalize        | 185 ms                                                      | 187 ms: 1.01x slower                                         |
| dulwich_log              | 42.4 ms                                                     | 42.8 ms: 1.01x slower                                        |
| bench_mp_pool            | 66.4 ms                                                     | 67.1 ms: 1.01x slower                                        |
| scimark_lu               | 58.1 ms                                                     | 58.8 ms: 1.01x slower                                        |
| xml_etree_process        | 38.4 ms                                                     | 38.8 ms: 1.01x slower                                        |
| meteor_contest           | 73.1 ms                                                     | 74.0 ms: 1.01x slower                                        |
| coverage                 | 51.5 ms                                                     | 52.1 ms: 1.01x slower                                        |
| pyflate                  | 297 ms                                                      | 301 ms: 1.01x slower                                         |
| unpack_sequence          | 37.5 ns                                                     | 37.9 ns: 1.01x slower                                        |
| json_loads               | 13.4 us                                                     | 13.6 us: 1.01x slower                                        |
| mako                     | 6.93 ms                                                     | 7.03 ms: 1.01x slower                                        |
| gc_traversal             | 1.48 ms                                                     | 1.50 ms: 1.01x slower                                        |
| regex_v8                 | 13.9 ms                                                     | 14.1 ms: 1.02x slower                                        |
| deltablue                | 2.14 ms                                                     | 2.18 ms: 1.02x slower                                        |
| unpickle                 | 8.16 us                                                     | 8.32 us: 1.02x slower                                        |
| deepcopy                 | 240 us                                                      | 245 us: 1.02x slower                                         |
| sqlglot_parse            | 820 us                                                      | 836 us: 1.02x slower                                         |
| sqlglot_transpile        | 1.04 ms                                                     | 1.06 ms: 1.02x slower                                        |
| richards_super           | 30.5 ms                                                     | 31.1 ms: 1.02x slower                                        |
| telco                    | 4.09 ms                                                     | 4.18 ms: 1.02x slower                                        |
| xml_etree_iterparse      | 62.5 ms                                                     | 63.9 ms: 1.02x slower                                        |
| pickle_pure_python       | 196 us                                                      | 200 us: 1.02x slower                                         |
| crypto_pyaes             | 47.4 ms                                                     | 48.5 ms: 1.02x slower                                        |
| json                     | 2.86 ms                                                     | 2.93 ms: 1.02x slower                                        |
| go                       | 88.5 ms                                                     | 90.6 ms: 1.02x slower                                        |
| chaos                    | 42.8 ms                                                     | 43.8 ms: 1.02x slower                                        |
| richards                 | 26.9 ms                                                     | 27.6 ms: 1.03x slower                                        |
| spectral_norm            | 63.2 ms                                                     | 64.8 ms: 1.03x slower                                        |
| float                    | 55.1 ms                                                     | 56.6 ms: 1.03x slower                                        |
| mdp                      | 1.44 sec                                                    | 1.48 sec: 1.03x slower                                       |
| xml_etree_parse          | 89.2 ms                                                     | 91.7 ms: 1.03x slower                                        |
| pycparser                | 673 ms                                                      | 693 ms: 1.03x slower                                         |
| xml_etree_generate       | 55.6 ms                                                     | 57.2 ms: 1.03x slower                                        |
| pprint_pformat           | 1.04 sec                                                    | 1.08 sec: 1.03x slower                                       |
| json_dumps               | 5.60 ms                                                     | 5.79 ms: 1.03x slower                                        |
| pprint_safe_repr         | 512 ms                                                      | 529 ms: 1.03x slower                                         |
| typing_runtime_protocols | 95.2 us                                                     | 98.4 us: 1.03x slower                                        |
| tomli_loads              | 1.37 sec                                                    | 1.42 sec: 1.03x slower                                       |
| nqueens                  | 61.2 ms                                                     | 63.4 ms: 1.04x slower                                        |
| deepcopy_memo            | 23.8 us                                                     | 24.7 us: 1.04x slower                                        |
| scimark_fft              | 180 ms                                                      | 187 ms: 1.04x slower                                         |
| logging_format           | 6.67 us                                                     | 6.94 us: 1.04x slower                                        |
| scimark_monte_carlo      | 43.7 ms                                                     | 45.5 ms: 1.04x slower                                        |
| hexiom                   | 4.03 ms                                                     | 4.21 ms: 1.04x slower                                        |
| comprehensions           | 14.1 us                                                     | 14.8 us: 1.04x slower                                        |
| logging_simple           | 6.21 us                                                     | 6.49 us: 1.04x slower                                        |
| scimark_sparse_mat_mult  | 2.48 ms                                                     | 2.60 ms: 1.05x slower                                        |
| unpickle_pure_python     | 133 us                                                      | 140 us: 1.05x slower                                         |
| scimark_sor              | 79.6 ms                                                     | 84.3 ms: 1.06x slower                                        |
| fannkuch                 | 237 ms                                                      | 254 ms: 1.07x slower                                         |
| dask                     | 259 ms                                                      | 364 ms: 1.40x slower                                         |
| Geometric mean           | (ref)                                                       | 1.02x slower                                                 |

Benchmark hidden because not significant (17): nbody, bench_thread_pool, async_tree_none, pidigits, aiohttp, 2to3, sqlite_synth, logging_silent, async_tree_cpu_io_mixed, tornado_http, raytrace, docutils, create_gc_cycles, async_tree_memoization, async_tree_io, asyncio_tcp_ssl, asyncio_tcp


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.01x
- 95% likely to have a slowdown of 1.01x
- 99% likely to have a slowdown of 1.00x
