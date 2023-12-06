
# Results vs. 3.12.0

- fork: python
- ref: 3.12
- machine: windows-amd64
- commit hash: 028f477
- commit date: 2023-10-21
- overall geometric mean: 1.00x faster
- HPT reliability: 97.04%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

Benchmark hidden because not significant (3): 2to3, docutils, tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231021-pythonperf1-amd64-python-3.12-3.12.0+-028f477 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------:|
| nbody          | 72.6 ms                                                     | 69.2 ms: 1.05x faster                                     |
| float          | 55.1 ms                                                     | 53.5 ms: 1.03x faster                                     |
| Geometric mean | (ref)                                                       | 1.03x faster                                              |

Benchmark hidden because not significant (1): pidigits

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231021-pythonperf1-amd64-python-3.12-3.12.0+-028f477 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------:|
| regex_compile  | 88.3 ms                                                     | 86.5 ms: 1.02x faster                                     |
| regex_effbot   | 1.62 ms                                                     | 1.61 ms: 1.01x faster                                     |
| regex_dna      | 124 ms                                                      | 126 ms: 1.02x slower                                      |
| Geometric mean | (ref)                                                       | 1.00x faster                                              |

Benchmark hidden because not significant (1): regex_v8

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231021-pythonperf1-amd64-python-3.12-3.12.0+-028f477 |
|----------------------|:-----------------------------------------------------------:|:---------------------------------------------------------:|
| pickle_dict          | 19.3 us                                                     | 18.3 us: 1.05x faster                                     |
| pickle               | 7.13 us                                                     | 6.95 us: 1.03x faster                                     |
| pickle_list          | 2.86 us                                                     | 2.83 us: 1.01x faster                                     |
| xml_etree_process    | 38.4 ms                                                     | 38.1 ms: 1.01x faster                                     |
| unpickle_pure_python | 133 us                                                      | 133 us: 1.01x faster                                      |
| unpickle_list        | 2.78 us                                                     | 2.80 us: 1.01x slower                                     |
| tomli_loads          | 1.37 sec                                                    | 1.38 sec: 1.01x slower                                    |
| json_loads           | 13.4 us                                                     | 13.6 us: 1.01x slower                                     |
| json_dumps           | 5.60 ms                                                     | 5.68 ms: 1.01x slower                                     |
| xml_etree_iterparse  | 62.5 ms                                                     | 63.6 ms: 1.02x slower                                     |
| xml_etree_parse      | 89.2 ms                                                     | 91.2 ms: 1.02x slower                                     |
| Geometric mean       | (ref)                                                       | 1.00x faster                                              |

Benchmark hidden because not significant (3): unpickle, xml_etree_generate, pickle_pure_python

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231021-pythonperf1-amd64-python-3.12-3.12.0+-028f477 |
|------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------:|
| python_startup         | 19.5 ms                                                     | 19.1 ms: 1.02x faster                                     |
| python_startup_no_site | 16.1 ms                                                     | 15.9 ms: 1.02x faster                                     |
| Geometric mean         | (ref)                                                       | 1.02x faster                                              |

Benchmarks with tag 'template':
===============================

Benchmark hidden because not significant (1): mako

All benchmarks:
===============

| Benchmark                | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231021-pythonperf1-amd64-python-3.12-3.12.0+-028f477 |
|--------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------:|
| pickle_dict              | 19.3 us                                                     | 18.3 us: 1.05x faster                                     |
| bench_mp_pool            | 66.4 ms                                                     | 63.1 ms: 1.05x faster                                     |
| nbody                    | 72.6 ms                                                     | 69.2 ms: 1.05x faster                                     |
| scimark_fft              | 180 ms                                                      | 174 ms: 1.03x faster                                      |
| float                    | 55.1 ms                                                     | 53.5 ms: 1.03x faster                                     |
| scimark_monte_carlo      | 43.7 ms                                                     | 42.4 ms: 1.03x faster                                     |
| pickle                   | 7.13 us                                                     | 6.95 us: 1.03x faster                                     |
| crypto_pyaes             | 47.4 ms                                                     | 46.4 ms: 1.02x faster                                     |
| regex_compile            | 88.3 ms                                                     | 86.5 ms: 1.02x faster                                     |
| unpack_sequence          | 37.5 ns                                                     | 36.8 ns: 1.02x faster                                     |
| scimark_sor              | 79.6 ms                                                     | 78.3 ms: 1.02x faster                                     |
| python_startup           | 19.5 ms                                                     | 19.1 ms: 1.02x faster                                     |
| pyflate                  | 297 ms                                                      | 292 ms: 1.02x faster                                      |
| python_startup_no_site   | 16.1 ms                                                     | 15.9 ms: 1.02x faster                                     |
| create_gc_cycles         | 727 us                                                      | 716 us: 1.02x faster                                      |
| dask                     | 259 ms                                                      | 255 ms: 1.01x faster                                      |
| telco                    | 4.09 ms                                                     | 4.04 ms: 1.01x faster                                     |
| regex_effbot             | 1.62 ms                                                     | 1.61 ms: 1.01x faster                                     |
| scimark_sparse_mat_mult  | 2.48 ms                                                     | 2.45 ms: 1.01x faster                                     |
| go                       | 88.5 ms                                                     | 87.5 ms: 1.01x faster                                     |
| pickle_list              | 2.86 us                                                     | 2.83 us: 1.01x faster                                     |
| coverage                 | 51.5 ms                                                     | 51.0 ms: 1.01x faster                                     |
| typing_runtime_protocols | 95.2 us                                                     | 94.3 us: 1.01x faster                                     |
| deepcopy_memo            | 23.8 us                                                     | 23.6 us: 1.01x faster                                     |
| xml_etree_process        | 38.4 ms                                                     | 38.1 ms: 1.01x faster                                     |
| sqlglot_parse            | 820 us                                                      | 813 us: 1.01x faster                                      |
| sqlglot_transpile        | 1.04 ms                                                     | 1.03 ms: 1.01x faster                                     |
| mdp                      | 1.44 sec                                                    | 1.43 sec: 1.01x faster                                    |
| pprint_pformat           | 1.04 sec                                                    | 1.04 sec: 1.01x faster                                    |
| spectral_norm            | 63.2 ms                                                     | 62.8 ms: 1.01x faster                                     |
| sqlite_synth             | 1.76 us                                                     | 1.75 us: 1.01x faster                                     |
| unpickle_pure_python     | 133 us                                                      | 133 us: 1.01x faster                                      |
| pprint_safe_repr         | 512 ms                                                      | 510 ms: 1.00x faster                                      |
| richards                 | 26.9 ms                                                     | 26.8 ms: 1.00x faster                                     |
| hexiom                   | 4.03 ms                                                     | 4.02 ms: 1.00x faster                                     |
| nqueens                  | 61.2 ms                                                     | 61.5 ms: 1.00x slower                                     |
| logging_simple           | 6.21 us                                                     | 6.24 us: 1.00x slower                                     |
| scimark_lu               | 58.1 ms                                                     | 58.5 ms: 1.01x slower                                     |
| unpickle_list            | 2.78 us                                                     | 2.80 us: 1.01x slower                                     |
| tomli_loads              | 1.37 sec                                                    | 1.38 sec: 1.01x slower                                    |
| logging_format           | 6.67 us                                                     | 6.73 us: 1.01x slower                                     |
| json_loads               | 13.4 us                                                     | 13.6 us: 1.01x slower                                     |
| sqlglot_optimize         | 34.4 ms                                                     | 34.7 ms: 1.01x slower                                     |
| logging_silent           | 60.6 ns                                                     | 61.2 ns: 1.01x slower                                     |
| mypy2                    | 207 ms                                                      | 209 ms: 1.01x slower                                      |
| sqlglot_normalize        | 185 ms                                                      | 188 ms: 1.01x slower                                      |
| meteor_contest           | 73.1 ms                                                     | 73.9 ms: 1.01x slower                                     |
| coroutines               | 14.0 ms                                                     | 14.2 ms: 1.01x slower                                     |
| deepcopy                 | 240 us                                                      | 244 us: 1.01x slower                                      |
| json_dumps               | 5.60 ms                                                     | 5.68 ms: 1.01x slower                                     |
| pathlib                  | 77.1 ms                                                     | 78.2 ms: 1.01x slower                                     |
| xml_etree_iterparse      | 62.5 ms                                                     | 63.6 ms: 1.02x slower                                     |
| pycparser                | 673 ms                                                      | 685 ms: 1.02x slower                                      |
| regex_dna                | 124 ms                                                      | 126 ms: 1.02x slower                                      |
| raytrace                 | 191 ms                                                      | 196 ms: 1.02x slower                                      |
| xml_etree_parse          | 89.2 ms                                                     | 91.2 ms: 1.02x slower                                     |
| json                     | 2.86 ms                                                     | 2.96 ms: 1.03x slower                                     |
| Geometric mean           | (ref)                                                       | 1.00x faster                                              |

Benchmark hidden because not significant (27): asyncio_tcp_ssl, bench_thread_pool, async_tree_none, generators, mako, async_tree_io, gc_traversal, 2to3, deltablue, fannkuch, unpickle, regex_v8, async_tree_cpu_io_mixed, asyncio_tcp, tornado_http, xml_etree_generate, pidigits, aiohttp, pickle_pure_python, richards_super, chaos, deepcopy_reduce, async_generators, comprehensions, docutils, dulwich_log, async_tree_memoization


# HPT report

- Reliability score: 97.04% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
