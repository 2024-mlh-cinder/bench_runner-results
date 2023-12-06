
# Results vs. 3.12.0

- fork: python
- ref: 3.12
- machine: linux-x86_64
- commit hash: 0e5eee0
- commit date: 2023-08-20
- overall geometric mean: 1.00x faster
- HPT reliability: 99.97%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230820-pythonperf2-x86_64-python-3.12-3.12.0rc1+-0e5eee0 |
|----------------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| 2to3           | 287 ms                                                       | 286 ms: 1.00x faster                                          |
| docutils       | 2.89 sec                                                     | 2.90 sec: 1.00x slower                                        |
| Geometric mean | (ref)                                                        | 1.00x faster                                                  |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230820-pythonperf2-x86_64-python-3.12-3.12.0rc1+-0e5eee0 |
|----------------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| nbody          | 94.1 ms                                                      | 87.5 ms: 1.07x faster                                         |
| pidigits       | 264 ms                                                       | 260 ms: 1.01x faster                                          |
| Geometric mean | (ref)                                                        | 1.03x faster                                                  |

Benchmark hidden because not significant (1): float

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230820-pythonperf2-x86_64-python-3.12-3.12.0rc1+-0e5eee0 |
|----------------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| regex_v8       | 25.0 ms                                                      | 23.9 ms: 1.04x faster                                         |
| regex_compile  | 146 ms                                                       | 144 ms: 1.01x faster                                          |
| regex_dna      | 241 ms                                                       | 242 ms: 1.00x slower                                          |
| regex_effbot   | 3.47 ms                                                      | 3.50 ms: 1.01x slower                                         |
| Geometric mean | (ref)                                                        | 1.01x faster                                                  |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230820-pythonperf2-x86_64-python-3.12-3.12.0rc1+-0e5eee0 |
|----------------------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| pickle_list          | 4.39 us                                                      | 4.23 us: 1.04x faster                                         |
| unpickle             | 14.8 us                                                      | 14.3 us: 1.03x faster                                         |
| unpickle_list        | 4.77 us                                                      | 4.69 us: 1.02x faster                                         |
| tomli_loads          | 2.20 sec                                                     | 2.18 sec: 1.01x faster                                        |
| unpickle_pure_python | 207 us                                                       | 205 us: 1.01x faster                                          |
| pickle_dict          | 31.7 us                                                      | 31.5 us: 1.01x faster                                         |
| pickle               | 10.1 us                                                      | 10.0 us: 1.00x faster                                         |
| pickle_pure_python   | 323 us                                                       | 322 us: 1.00x faster                                          |
| json_loads           | 24.3 us                                                      | 24.5 us: 1.01x slower                                         |
| xml_etree_process    | 58.3 ms                                                      | 59.1 ms: 1.01x slower                                         |
| json_dumps           | 10.2 ms                                                      | 10.4 ms: 1.02x slower                                         |
| Geometric mean       | (ref)                                                        | 1.01x faster                                                  |

Benchmark hidden because not significant (3): xml_etree_parse, xml_etree_generate, xml_etree_iterparse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230820-pythonperf2-x86_64-python-3.12-3.12.0rc1+-0e5eee0 |
|------------------------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| python_startup_no_site | 8.70 ms                                                      | 8.49 ms: 1.02x faster                                         |
| python_startup         | 11.7 ms                                                      | 11.5 ms: 1.02x faster                                         |
| Geometric mean         | (ref)                                                        | 1.02x faster                                                  |

Benchmarks with tag 'template':
===============================

Benchmark hidden because not significant (1): mako

All benchmarks:
===============

| Benchmark                | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230820-pythonperf2-x86_64-python-3.12-3.12.0rc1+-0e5eee0 |
|--------------------------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| nbody                    | 94.1 ms                                                      | 87.5 ms: 1.07x faster                                         |
| scimark_monte_carlo      | 72.4 ms                                                      | 68.9 ms: 1.05x faster                                         |
| regex_v8                 | 25.0 ms                                                      | 23.9 ms: 1.04x faster                                         |
| go                       | 150 ms                                                       | 145 ms: 1.04x faster                                          |
| pickle_list              | 4.39 us                                                      | 4.23 us: 1.04x faster                                         |
| deltablue                | 3.29 ms                                                      | 3.18 ms: 1.04x faster                                         |
| create_gc_cycles         | 1.67 ms                                                      | 1.62 ms: 1.03x faster                                         |
| unpickle                 | 14.8 us                                                      | 14.3 us: 1.03x faster                                         |
| hexiom                   | 5.96 ms                                                      | 5.79 ms: 1.03x faster                                         |
| pathlib                  | 19.8 ms                                                      | 19.2 ms: 1.03x faster                                         |
| scimark_lu               | 101 ms                                                       | 97.9 ms: 1.03x faster                                         |
| coroutines               | 23.0 ms                                                      | 22.4 ms: 1.03x faster                                         |
| scimark_sparse_mat_mult  | 4.42 ms                                                      | 4.32 ms: 1.03x faster                                         |
| bench_thread_pool        | 980 us                                                       | 957 us: 1.02x faster                                          |
| python_startup_no_site   | 8.70 ms                                                      | 8.49 ms: 1.02x faster                                         |
| fannkuch                 | 350 ms                                                       | 342 ms: 1.02x faster                                          |
| python_startup           | 11.7 ms                                                      | 11.5 ms: 1.02x faster                                         |
| pprint_safe_repr         | 823 ms                                                       | 807 ms: 1.02x faster                                          |
| scimark_fft              | 304 ms                                                       | 299 ms: 1.02x faster                                          |
| pprint_pformat           | 1.67 sec                                                     | 1.64 sec: 1.02x faster                                        |
| unpickle_list            | 4.77 us                                                      | 4.69 us: 1.02x faster                                         |
| meteor_contest           | 128 ms                                                       | 126 ms: 1.02x faster                                          |
| comprehensions           | 21.9 us                                                      | 21.6 us: 1.02x faster                                         |
| richards                 | 45.0 ms                                                      | 44.4 ms: 1.01x faster                                         |
| sqlglot_parse            | 1.40 ms                                                      | 1.38 ms: 1.01x faster                                         |
| pidigits                 | 264 ms                                                       | 260 ms: 1.01x faster                                          |
| json                     | 5.14 ms                                                      | 5.08 ms: 1.01x faster                                         |
| pyflate                  | 447 ms                                                       | 442 ms: 1.01x faster                                          |
| sqlglot_transpile        | 1.80 ms                                                      | 1.78 ms: 1.01x faster                                         |
| regex_compile            | 146 ms                                                       | 144 ms: 1.01x faster                                          |
| typing_runtime_protocols | 151 us                                                       | 150 us: 1.01x faster                                          |
| scimark_sor              | 110 ms                                                       | 109 ms: 1.01x faster                                          |
| tomli_loads              | 2.20 sec                                                     | 2.18 sec: 1.01x faster                                        |
| logging_simple           | 6.73 us                                                      | 6.67 us: 1.01x faster                                         |
| raytrace                 | 302 ms                                                       | 299 ms: 1.01x faster                                          |
| mypy2                    | 368 ms                                                       | 366 ms: 1.01x faster                                          |
| unpickle_pure_python     | 207 us                                                       | 205 us: 1.01x faster                                          |
| generators               | 36.7 ms                                                      | 36.5 ms: 1.01x faster                                         |
| pickle_dict              | 31.7 us                                                      | 31.5 us: 1.01x faster                                         |
| pickle                   | 10.1 us                                                      | 10.0 us: 1.00x faster                                         |
| coverage                 | 89.6 ms                                                      | 89.2 ms: 1.00x faster                                         |
| mdp                      | 2.53 sec                                                     | 2.52 sec: 1.00x faster                                        |
| 2to3                     | 287 ms                                                       | 286 ms: 1.00x faster                                          |
| asyncio_tcp_ssl          | 1.58 sec                                                     | 1.57 sec: 1.00x faster                                        |
| pickle_pure_python       | 323 us                                                       | 322 us: 1.00x faster                                          |
| async_tree_io            | 1.06 sec                                                     | 1.06 sec: 1.00x slower                                        |
| regex_dna                | 241 ms                                                       | 242 ms: 1.00x slower                                          |
| docutils                 | 2.89 sec                                                     | 2.90 sec: 1.00x slower                                        |
| regex_effbot             | 3.47 ms                                                      | 3.50 ms: 1.01x slower                                         |
| deepcopy_reduce          | 3.46 us                                                      | 3.49 us: 1.01x slower                                         |
| json_loads               | 24.3 us                                                      | 24.5 us: 1.01x slower                                         |
| deepcopy                 | 376 us                                                       | 379 us: 1.01x slower                                          |
| sqlite_synth             | 2.70 us                                                      | 2.72 us: 1.01x slower                                         |
| crypto_pyaes             | 80.9 ms                                                      | 81.7 ms: 1.01x slower                                         |
| spectral_norm            | 91.6 ms                                                      | 92.6 ms: 1.01x slower                                         |
| gc_traversal             | 3.54 ms                                                      | 3.59 ms: 1.01x slower                                         |
| xml_etree_process        | 58.3 ms                                                      | 59.1 ms: 1.01x slower                                         |
| deepcopy_memo            | 37.4 us                                                      | 38.0 us: 1.01x slower                                         |
| async_generators         | 385 ms                                                       | 391 ms: 1.02x slower                                          |
| json_dumps               | 10.2 ms                                                      | 10.4 ms: 1.02x slower                                         |
| telco                    | 6.96 ms                                                      | 7.09 ms: 1.02x slower                                         |
| dulwich_log              | 65.3 ms                                                      | 66.6 ms: 1.02x slower                                         |
| unpack_sequence          | 53.3 ns                                                      | 54.5 ns: 1.02x slower                                         |
| dask                     | 397 ms                                                       | 569 ms: 1.43x slower                                          |
| Geometric mean           | (ref)                                                        | 1.00x faster                                                  |

Benchmark hidden because not significant (19): bench_mp_pool, pycparser, tornado_http, xml_etree_parse, async_tree_cpu_io_mixed, richards_super, chaos, async_tree_memoization, sqlglot_optimize, float, nqueens, async_tree_none, logging_silent, sqlglot_normalize, xml_etree_generate, asyncio_tcp, xml_etree_iterparse, mako, logging_format


# HPT report

- Reliability score: 99.97% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
