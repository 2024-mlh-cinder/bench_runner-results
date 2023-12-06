
# Results vs. 3.12.0

- fork: faster-cpython
- ref: no_deep_freeze_3
- machine: windows-amd64
- commit hash: 0bed3bc
- commit date: 2023-08-28
- overall geometric mean: 1.02x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.01x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230828-pythonperf1-amd64-faster%2dcpython-no_deep_freeze_3-3.13.0a0-0bed3bc |
|----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| docutils       | 1.63 sec                                                    | 1.60 sec: 1.02x faster                                                           |
| Geometric mean | (ref)                                                       | 1.01x faster                                                                     |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230828-pythonperf1-amd64-faster%2dcpython-no_deep_freeze_3-3.13.0a0-0bed3bc |
|----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| pidigits       | 150 ms                                                      | 151 ms: 1.00x slower                                                             |
| nbody          | 72.6 ms                                                     | 75.4 ms: 1.04x slower                                                            |
| Geometric mean | (ref)                                                       | 1.01x slower                                                                     |

Benchmark hidden because not significant (1): float

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230828-pythonperf1-amd64-faster%2dcpython-no_deep_freeze_3-3.13.0a0-0bed3bc |
|----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| regex_dna      | 124 ms                                                      | 118 ms: 1.05x faster                                                             |
| regex_effbot   | 1.62 ms                                                     | 1.59 ms: 1.02x faster                                                            |
| regex_compile  | 88.3 ms                                                     | 90.1 ms: 1.02x slower                                                            |
| regex_v8       | 13.9 ms                                                     | 14.6 ms: 1.05x slower                                                            |
| Geometric mean | (ref)                                                       | 1.00x slower                                                                     |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230828-pythonperf1-amd64-faster%2dcpython-no_deep_freeze_3-3.13.0a0-0bed3bc |
|----------------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| pickle_dict          | 19.3 us                                                     | 18.3 us: 1.05x faster                                                            |
| pickle_list          | 2.86 us                                                     | 2.80 us: 1.02x faster                                                            |
| pickle_pure_python   | 196 us                                                      | 195 us: 1.01x faster                                                             |
| xml_etree_process    | 38.4 ms                                                     | 38.7 ms: 1.01x slower                                                            |
| json_loads           | 13.4 us                                                     | 13.6 us: 1.01x slower                                                            |
| json_dumps           | 5.60 ms                                                     | 5.72 ms: 1.02x slower                                                            |
| xml_etree_generate   | 55.6 ms                                                     | 56.8 ms: 1.02x slower                                                            |
| xml_etree_parse      | 89.2 ms                                                     | 91.4 ms: 1.02x slower                                                            |
| pickle               | 7.13 us                                                     | 7.34 us: 1.03x slower                                                            |
| xml_etree_iterparse  | 62.5 ms                                                     | 64.6 ms: 1.03x slower                                                            |
| unpickle_list        | 2.78 us                                                     | 2.93 us: 1.05x slower                                                            |
| unpickle_pure_python | 133 us                                                      | 141 us: 1.06x slower                                                             |
| tomli_loads          | 1.37 sec                                                    | 1.49 sec: 1.09x slower                                                           |
| Geometric mean       | (ref)                                                       | 1.02x slower                                                                     |

Benchmark hidden because not significant (1): unpickle

Benchmarks with tag 'startup':
==============================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230828-pythonperf1-amd64-faster%2dcpython-no_deep_freeze_3-3.13.0a0-0bed3bc |
|----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| python_startup | 19.5 ms                                                     | 19.8 ms: 1.02x slower                                                            |
| Geometric mean | (ref)                                                       | 1.01x slower                                                                     |

Benchmark hidden because not significant (1): python_startup_no_site

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230828-pythonperf1-amd64-faster%2dcpython-no_deep_freeze_3-3.13.0a0-0bed3bc |
|-----------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| mako      | 6.93 ms                                                     | 7.57 ms: 1.09x slower                                                            |

All benchmarks:
===============

| Benchmark                | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230828-pythonperf1-amd64-faster%2dcpython-no_deep_freeze_3-3.13.0a0-0bed3bc |
|--------------------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| coverage                 | 51.5 ms                                                     | 45.7 ms: 1.13x faster                                                            |
| async_tree_none          | 294 ms                                                      | 267 ms: 1.10x faster                                                             |
| raytrace                 | 191 ms                                                      | 177 ms: 1.08x faster                                                             |
| asyncio_tcp_ssl          | 1.96 sec                                                    | 1.86 sec: 1.06x faster                                                           |
| pickle_dict              | 19.3 us                                                     | 18.3 us: 1.05x faster                                                            |
| regex_dna                | 124 ms                                                      | 118 ms: 1.05x faster                                                             |
| crypto_pyaes             | 47.4 ms                                                     | 46.0 ms: 1.03x faster                                                            |
| chaos                    | 42.8 ms                                                     | 41.7 ms: 1.02x faster                                                            |
| regex_effbot             | 1.62 ms                                                     | 1.59 ms: 1.02x faster                                                            |
| pickle_list              | 2.86 us                                                     | 2.80 us: 1.02x faster                                                            |
| docutils                 | 1.63 sec                                                    | 1.60 sec: 1.02x faster                                                           |
| typing_runtime_protocols | 95.2 us                                                     | 94.4 us: 1.01x faster                                                            |
| pickle_pure_python       | 196 us                                                      | 195 us: 1.01x faster                                                             |
| pidigits                 | 150 ms                                                      | 151 ms: 1.00x slower                                                             |
| sqlglot_parse            | 820 us                                                      | 823 us: 1.00x slower                                                             |
| sqlite_synth             | 1.76 us                                                     | 1.76 us: 1.01x slower                                                            |
| logging_format           | 6.67 us                                                     | 6.71 us: 1.01x slower                                                            |
| sqlglot_transpile        | 1.04 ms                                                     | 1.04 ms: 1.01x slower                                                            |
| xml_etree_process        | 38.4 ms                                                     | 38.7 ms: 1.01x slower                                                            |
| gc_traversal             | 1.48 ms                                                     | 1.49 ms: 1.01x slower                                                            |
| json_loads               | 13.4 us                                                     | 13.6 us: 1.01x slower                                                            |
| scimark_sparse_mat_mult  | 2.48 ms                                                     | 2.50 ms: 1.01x slower                                                            |
| nqueens                  | 61.2 ms                                                     | 61.9 ms: 1.01x slower                                                            |
| deepcopy_reduce          | 2.13 us                                                     | 2.16 us: 1.01x slower                                                            |
| sqlglot_normalize        | 185 ms                                                      | 188 ms: 1.01x slower                                                             |
| sqlglot_optimize         | 34.4 ms                                                     | 34.9 ms: 1.01x slower                                                            |
| logging_simple           | 6.21 us                                                     | 6.30 us: 1.01x slower                                                            |
| bench_mp_pool            | 66.4 ms                                                     | 67.4 ms: 1.01x slower                                                            |
| python_startup           | 19.5 ms                                                     | 19.8 ms: 1.02x slower                                                            |
| regex_compile            | 88.3 ms                                                     | 90.1 ms: 1.02x slower                                                            |
| json_dumps               | 5.60 ms                                                     | 5.72 ms: 1.02x slower                                                            |
| xml_etree_generate       | 55.6 ms                                                     | 56.8 ms: 1.02x slower                                                            |
| xml_etree_parse          | 89.2 ms                                                     | 91.4 ms: 1.02x slower                                                            |
| async_generators         | 235 ms                                                      | 241 ms: 1.03x slower                                                             |
| pathlib                  | 77.1 ms                                                     | 79.2 ms: 1.03x slower                                                            |
| scimark_fft              | 180 ms                                                      | 185 ms: 1.03x slower                                                             |
| unpack_sequence          | 37.5 ns                                                     | 38.5 ns: 1.03x slower                                                            |
| pickle                   | 7.13 us                                                     | 7.34 us: 1.03x slower                                                            |
| async_tree_memoization   | 336 ms                                                      | 346 ms: 1.03x slower                                                             |
| scimark_monte_carlo      | 43.7 ms                                                     | 45.1 ms: 1.03x slower                                                            |
| xml_etree_iterparse      | 62.5 ms                                                     | 64.6 ms: 1.03x slower                                                            |
| pyflate                  | 297 ms                                                      | 307 ms: 1.03x slower                                                             |
| mypy2                    | 207 ms                                                      | 214 ms: 1.03x slower                                                             |
| comprehensions           | 14.1 us                                                     | 14.6 us: 1.04x slower                                                            |
| nbody                    | 72.6 ms                                                     | 75.4 ms: 1.04x slower                                                            |
| scimark_lu               | 58.1 ms                                                     | 60.6 ms: 1.04x slower                                                            |
| mdp                      | 1.44 sec                                                    | 1.51 sec: 1.05x slower                                                           |
| pprint_safe_repr         | 512 ms                                                      | 537 ms: 1.05x slower                                                             |
| deltablue                | 2.14 ms                                                     | 2.24 ms: 1.05x slower                                                            |
| go                       | 88.5 ms                                                     | 92.9 ms: 1.05x slower                                                            |
| deepcopy_memo            | 23.8 us                                                     | 25.0 us: 1.05x slower                                                            |
| pprint_pformat           | 1.04 sec                                                    | 1.10 sec: 1.05x slower                                                           |
| unpickle_list            | 2.78 us                                                     | 2.93 us: 1.05x slower                                                            |
| regex_v8                 | 13.9 ms                                                     | 14.6 ms: 1.05x slower                                                            |
| unpickle_pure_python     | 133 us                                                      | 141 us: 1.06x slower                                                             |
| spectral_norm            | 63.2 ms                                                     | 66.7 ms: 1.06x slower                                                            |
| logging_silent           | 60.6 ns                                                     | 64.0 ns: 1.06x slower                                                            |
| generators               | 22.7 ms                                                     | 24.1 ms: 1.06x slower                                                            |
| dulwich_log              | 42.4 ms                                                     | 45.1 ms: 1.06x slower                                                            |
| hexiom                   | 4.03 ms                                                     | 4.30 ms: 1.07x slower                                                            |
| richards_super           | 30.5 ms                                                     | 32.6 ms: 1.07x slower                                                            |
| scimark_sor              | 79.6 ms                                                     | 85.2 ms: 1.07x slower                                                            |
| coroutines               | 14.0 ms                                                     | 15.0 ms: 1.07x slower                                                            |
| pycparser                | 673 ms                                                      | 722 ms: 1.07x slower                                                             |
| richards                 | 26.9 ms                                                     | 29.1 ms: 1.08x slower                                                            |
| json                     | 2.86 ms                                                     | 3.10 ms: 1.08x slower                                                            |
| tomli_loads              | 1.37 sec                                                    | 1.49 sec: 1.09x slower                                                           |
| mako                     | 6.93 ms                                                     | 7.57 ms: 1.09x slower                                                            |
| fannkuch                 | 237 ms                                                      | 261 ms: 1.10x slower                                                             |
| telco                    | 4.09 ms                                                     | 4.65 ms: 1.14x slower                                                            |
| dask                     | 259 ms                                                      | 372 ms: 1.44x slower                                                             |
| Geometric mean           | (ref)                                                       | 1.02x slower                                                                     |

Benchmark hidden because not significant (11): create_gc_cycles, async_tree_cpu_io_mixed, float, unpickle, tornado_http, bench_thread_pool, meteor_contest, deepcopy, python_startup_no_site, async_tree_io, asyncio_tcp
Ignored benchmarks (2) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0.json: 2to3, aiohttp


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.01x
- 95% likely to have a slowdown of 1.01x
- 99% likely to have a slowdown of 1.01x
