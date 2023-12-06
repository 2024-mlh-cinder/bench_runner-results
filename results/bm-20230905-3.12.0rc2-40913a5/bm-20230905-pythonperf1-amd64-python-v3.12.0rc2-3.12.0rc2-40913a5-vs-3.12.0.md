
# Results vs. 3.12.0

- fork: python
- ref: v3.12.0rc2
- machine: windows-amd64
- commit hash: 40913a5
- commit date: 2023-09-05
- overall geometric mean: 1.01x slower
- HPT reliability: 59.00%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230905-pythonperf1-amd64-python-v3.12.0rc2-3.12.0rc2-40913a5 |
|----------------|:-----------------------------------------------------------:|:-----------------------------------------------------------------:|
| 2to3           | 214 ms                                                      | 216 ms: 1.01x slower                                              |
| docutils       | 1.63 sec                                                    | 1.65 sec: 1.01x slower                                            |
| tornado_http   | 87.7 ms                                                     | 88.4 ms: 1.01x slower                                             |
| Geometric mean | (ref)                                                       | 1.01x slower                                                      |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230905-pythonperf1-amd64-python-v3.12.0rc2-3.12.0rc2-40913a5 |
|----------------|:-----------------------------------------------------------:|:-----------------------------------------------------------------:|
| nbody          | 72.6 ms                                                     | 69.0 ms: 1.05x faster                                             |
| float          | 55.1 ms                                                     | 54.4 ms: 1.01x faster                                             |
| Geometric mean | (ref)                                                       | 1.02x faster                                                      |

Benchmark hidden because not significant (1): pidigits

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230905-pythonperf1-amd64-python-v3.12.0rc2-3.12.0rc2-40913a5 |
|----------------|:-----------------------------------------------------------:|:-----------------------------------------------------------------:|
| regex_dna      | 124 ms                                                      | 119 ms: 1.05x faster                                              |
| regex_effbot   | 1.62 ms                                                     | 1.58 ms: 1.03x faster                                             |
| regex_v8       | 13.9 ms                                                     | 13.7 ms: 1.01x faster                                             |
| regex_compile  | 88.3 ms                                                     | 87.5 ms: 1.01x faster                                             |
| Geometric mean | (ref)                                                       | 1.02x faster                                                      |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230905-pythonperf1-amd64-python-v3.12.0rc2-3.12.0rc2-40913a5 |
|----------------------|:-----------------------------------------------------------:|:-----------------------------------------------------------------:|
| pickle_dict          | 19.3 us                                                     | 18.3 us: 1.05x faster                                             |
| unpickle_list        | 2.78 us                                                     | 2.65 us: 1.05x faster                                             |
| pickle_list          | 2.86 us                                                     | 2.75 us: 1.04x faster                                             |
| pickle               | 7.13 us                                                     | 6.97 us: 1.02x faster                                             |
| pickle_pure_python   | 196 us                                                      | 191 us: 1.02x faster                                              |
| unpickle_pure_python | 133 us                                                      | 130 us: 1.02x faster                                              |
| unpickle             | 8.16 us                                                     | 8.05 us: 1.01x faster                                             |
| xml_etree_process    | 38.4 ms                                                     | 37.9 ms: 1.01x faster                                             |
| tomli_loads          | 1.37 sec                                                    | 1.37 sec: 1.00x slower                                            |
| json_loads           | 13.4 us                                                     | 13.6 us: 1.01x slower                                             |
| json_dumps           | 5.60 ms                                                     | 5.66 ms: 1.01x slower                                             |
| Geometric mean       | (ref)                                                       | 1.01x faster                                                      |

Benchmark hidden because not significant (3): xml_etree_generate, xml_etree_iterparse, xml_etree_parse

Benchmarks with tag 'startup':
==============================

Benchmark hidden because not significant (2): python_startup, python_startup_no_site

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230905-pythonperf1-amd64-python-v3.12.0rc2-3.12.0rc2-40913a5 |
|-----------|:-----------------------------------------------------------:|:-----------------------------------------------------------------:|
| mako      | 6.93 ms                                                     | 7.00 ms: 1.01x slower                                             |

All benchmarks:
===============

| Benchmark                | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230905-pythonperf1-amd64-python-v3.12.0rc2-3.12.0rc2-40913a5 |
|--------------------------|:-----------------------------------------------------------:|:-----------------------------------------------------------------:|
| nbody                    | 72.6 ms                                                     | 69.0 ms: 1.05x faster                                             |
| pickle_dict              | 19.3 us                                                     | 18.3 us: 1.05x faster                                             |
| unpickle_list            | 2.78 us                                                     | 2.65 us: 1.05x faster                                             |
| regex_dna                | 124 ms                                                      | 119 ms: 1.05x faster                                              |
| mdp                      | 1.44 sec                                                    | 1.39 sec: 1.04x faster                                            |
| pickle_list              | 2.86 us                                                     | 2.75 us: 1.04x faster                                             |
| richards                 | 26.9 ms                                                     | 26.0 ms: 1.03x faster                                             |
| scimark_sor              | 79.6 ms                                                     | 77.1 ms: 1.03x faster                                             |
| regex_effbot             | 1.62 ms                                                     | 1.58 ms: 1.03x faster                                             |
| richards_super           | 30.5 ms                                                     | 29.7 ms: 1.03x faster                                             |
| coverage                 | 51.5 ms                                                     | 50.2 ms: 1.03x faster                                             |
| pickle                   | 7.13 us                                                     | 6.97 us: 1.02x faster                                             |
| pickle_pure_python       | 196 us                                                      | 191 us: 1.02x faster                                              |
| scimark_fft              | 180 ms                                                      | 176 ms: 1.02x faster                                              |
| unpickle_pure_python     | 133 us                                                      | 130 us: 1.02x faster                                              |
| scimark_monte_carlo      | 43.7 ms                                                     | 42.8 ms: 1.02x faster                                             |
| go                       | 88.5 ms                                                     | 87.0 ms: 1.02x faster                                             |
| scimark_lu               | 58.1 ms                                                     | 57.2 ms: 1.02x faster                                             |
| regex_v8                 | 13.9 ms                                                     | 13.7 ms: 1.01x faster                                             |
| sqlglot_parse            | 820 us                                                      | 808 us: 1.01x faster                                              |
| float                    | 55.1 ms                                                     | 54.4 ms: 1.01x faster                                             |
| unpickle                 | 8.16 us                                                     | 8.05 us: 1.01x faster                                             |
| sqlglot_transpile        | 1.04 ms                                                     | 1.02 ms: 1.01x faster                                             |
| xml_etree_process        | 38.4 ms                                                     | 37.9 ms: 1.01x faster                                             |
| pyflate                  | 297 ms                                                      | 293 ms: 1.01x faster                                              |
| create_gc_cycles         | 727 us                                                      | 718 us: 1.01x faster                                              |
| crypto_pyaes             | 47.4 ms                                                     | 46.9 ms: 1.01x faster                                             |
| regex_compile            | 88.3 ms                                                     | 87.5 ms: 1.01x faster                                             |
| deepcopy_memo            | 23.8 us                                                     | 23.6 us: 1.01x faster                                             |
| spectral_norm            | 63.2 ms                                                     | 62.7 ms: 1.01x faster                                             |
| sqlite_synth             | 1.76 us                                                     | 1.74 us: 1.01x faster                                             |
| pprint_safe_repr         | 512 ms                                                      | 509 ms: 1.01x faster                                              |
| raytrace                 | 191 ms                                                      | 190 ms: 1.01x faster                                              |
| chaos                    | 42.8 ms                                                     | 42.6 ms: 1.00x faster                                             |
| sqlglot_optimize         | 34.4 ms                                                     | 34.5 ms: 1.00x slower                                             |
| logging_simple           | 6.21 us                                                     | 6.24 us: 1.00x slower                                             |
| tomli_loads              | 1.37 sec                                                    | 1.37 sec: 1.00x slower                                            |
| dulwich_log              | 42.4 ms                                                     | 42.8 ms: 1.01x slower                                             |
| 2to3                     | 214 ms                                                      | 216 ms: 1.01x slower                                              |
| tornado_http             | 87.7 ms                                                     | 88.4 ms: 1.01x slower                                             |
| deepcopy_reduce          | 2.13 us                                                     | 2.15 us: 1.01x slower                                             |
| mako                     | 6.93 ms                                                     | 7.00 ms: 1.01x slower                                             |
| logging_format           | 6.67 us                                                     | 6.74 us: 1.01x slower                                             |
| docutils                 | 1.63 sec                                                    | 1.65 sec: 1.01x slower                                            |
| sqlglot_normalize        | 185 ms                                                      | 187 ms: 1.01x slower                                              |
| scimark_sparse_mat_mult  | 2.48 ms                                                     | 2.50 ms: 1.01x slower                                             |
| mypy2                    | 207 ms                                                      | 209 ms: 1.01x slower                                              |
| json_loads               | 13.4 us                                                     | 13.6 us: 1.01x slower                                             |
| typing_runtime_protocols | 95.2 us                                                     | 96.2 us: 1.01x slower                                             |
| pycparser                | 673 ms                                                      | 681 ms: 1.01x slower                                              |
| json_dumps               | 5.60 ms                                                     | 5.66 ms: 1.01x slower                                             |
| bench_mp_pool            | 66.4 ms                                                     | 67.3 ms: 1.01x slower                                             |
| async_generators         | 235 ms                                                      | 238 ms: 1.01x slower                                              |
| pathlib                  | 77.1 ms                                                     | 78.3 ms: 1.02x slower                                             |
| gc_traversal             | 1.48 ms                                                     | 1.51 ms: 1.02x slower                                             |
| unpack_sequence          | 37.5 ns                                                     | 38.3 ns: 1.02x slower                                             |
| telco                    | 4.09 ms                                                     | 4.19 ms: 1.02x slower                                             |
| nqueens                  | 61.2 ms                                                     | 63.9 ms: 1.04x slower                                             |
| json                     | 2.86 ms                                                     | 2.99 ms: 1.04x slower                                             |
| fannkuch                 | 237 ms                                                      | 249 ms: 1.05x slower                                              |
| generators               | 22.7 ms                                                     | 24.2 ms: 1.06x slower                                             |
| comprehensions           | 14.1 us                                                     | 15.3 us: 1.08x slower                                             |
| coroutines               | 14.0 ms                                                     | 19.0 ms: 1.36x slower                                             |
| dask                     | 259 ms                                                      | 363 ms: 1.40x slower                                              |
| Geometric mean           | (ref)                                                       | 1.01x slower                                                      |

Benchmark hidden because not significant (20): async_tree_none, python_startup, logging_silent, deltablue, aiohttp, xml_etree_generate, pprint_pformat, pidigits, meteor_contest, asyncio_tcp_ssl, deepcopy, hexiom, async_tree_cpu_io_mixed, async_tree_io, xml_etree_iterparse, xml_etree_parse, async_tree_memoization, python_startup_no_site, bench_thread_pool, asyncio_tcp


# HPT report

- Reliability score: 59.00% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
