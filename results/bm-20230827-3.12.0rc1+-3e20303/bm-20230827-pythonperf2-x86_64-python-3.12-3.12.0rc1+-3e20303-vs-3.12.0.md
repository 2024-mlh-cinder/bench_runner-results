
# Results vs. 3.12.0

- fork: python
- ref: 3.12
- machine: linux-x86_64
- commit hash: 3e20303
- commit date: 2023-08-27
- overall geometric mean: 1.00x faster
- HPT reliability: 98.69%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230827-pythonperf2-x86_64-python-3.12-3.12.0rc1+-3e20303 |
|----------------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| 2to3           | 287 ms                                                       | 284 ms: 1.01x faster                                          |
| docutils       | 2.89 sec                                                     | 2.91 sec: 1.01x slower                                        |
| Geometric mean | (ref)                                                        | 1.00x faster                                                  |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230827-pythonperf2-x86_64-python-3.12-3.12.0rc1+-3e20303 |
|----------------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| nbody          | 94.1 ms                                                      | 88.2 ms: 1.07x faster                                         |
| pidigits       | 264 ms                                                       | 259 ms: 1.02x faster                                          |
| Geometric mean | (ref)                                                        | 1.03x faster                                                  |

Benchmark hidden because not significant (1): float

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230827-pythonperf2-x86_64-python-3.12-3.12.0rc1+-3e20303 |
|----------------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| regex_v8       | 25.0 ms                                                      | 23.6 ms: 1.06x faster                                         |
| regex_dna      | 241 ms                                                       | 239 ms: 1.01x faster                                          |
| regex_compile  | 146 ms                                                       | 145 ms: 1.00x faster                                          |
| regex_effbot   | 3.47 ms                                                      | 3.51 ms: 1.01x slower                                         |
| Geometric mean | (ref)                                                        | 1.01x faster                                                  |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230827-pythonperf2-x86_64-python-3.12-3.12.0rc1+-3e20303 |
|----------------------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| pickle_list          | 4.39 us                                                      | 4.17 us: 1.05x faster                                         |
| unpickle_list        | 4.77 us                                                      | 4.67 us: 1.02x faster                                         |
| pickle               | 10.1 us                                                      | 9.90 us: 1.02x faster                                         |
| pickle_pure_python   | 323 us                                                       | 318 us: 1.01x faster                                          |
| xml_etree_generate   | 86.1 ms                                                      | 85.7 ms: 1.01x faster                                         |
| xml_etree_process    | 58.3 ms                                                      | 58.5 ms: 1.00x slower                                         |
| json_dumps           | 10.2 ms                                                      | 10.3 ms: 1.00x slower                                         |
| xml_etree_parse      | 146 ms                                                       | 148 ms: 1.01x slower                                          |
| unpickle_pure_python | 207 us                                                       | 211 us: 1.02x slower                                          |
| json_loads           | 24.3 us                                                      | 24.9 us: 1.03x slower                                         |
| pickle_dict          | 31.7 us                                                      | 33.4 us: 1.05x slower                                         |
| Geometric mean       | (ref)                                                        | 1.00x slower                                                  |

Benchmark hidden because not significant (3): tomli_loads, unpickle, xml_etree_iterparse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230827-pythonperf2-x86_64-python-3.12-3.12.0rc1+-3e20303 |
|------------------------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| python_startup_no_site | 8.70 ms                                                      | 8.51 ms: 1.02x faster                                         |
| python_startup         | 11.7 ms                                                      | 11.5 ms: 1.02x faster                                         |
| Geometric mean         | (ref)                                                        | 1.02x faster                                                  |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230827-pythonperf2-x86_64-python-3.12-3.12.0rc1+-3e20303 |
|-----------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| mako      | 9.94 ms                                                      | 9.88 ms: 1.01x faster                                         |

All benchmarks:
===============

| Benchmark              | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230827-pythonperf2-x86_64-python-3.12-3.12.0rc1+-3e20303 |
|------------------------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| unpack_sequence        | 53.3 ns                                                      | 47.6 ns: 1.12x faster                                         |
| nbody                  | 94.1 ms                                                      | 88.2 ms: 1.07x faster                                         |
| regex_v8               | 25.0 ms                                                      | 23.6 ms: 1.06x faster                                         |
| pickle_list            | 4.39 us                                                      | 4.17 us: 1.05x faster                                         |
| pathlib                | 19.8 ms                                                      | 19.0 ms: 1.04x faster                                         |
| create_gc_cycles       | 1.67 ms                                                      | 1.62 ms: 1.04x faster                                         |
| logging_silent         | 95.6 ns                                                      | 92.3 ns: 1.04x faster                                         |
| pprint_pformat         | 1.67 sec                                                     | 1.62 sec: 1.03x faster                                        |
| pprint_safe_repr       | 823 ms                                                       | 800 ms: 1.03x faster                                          |
| bench_thread_pool      | 980 us                                                       | 954 us: 1.03x faster                                          |
| deepcopy_memo          | 37.4 us                                                      | 36.5 us: 1.03x faster                                         |
| pycparser              | 1.27 sec                                                     | 1.25 sec: 1.02x faster                                        |
| unpickle_list          | 4.77 us                                                      | 4.67 us: 1.02x faster                                         |
| python_startup_no_site | 8.70 ms                                                      | 8.51 ms: 1.02x faster                                         |
| python_startup         | 11.7 ms                                                      | 11.5 ms: 1.02x faster                                         |
| pickle                 | 10.1 us                                                      | 9.90 us: 1.02x faster                                         |
| pidigits               | 264 ms                                                       | 259 ms: 1.02x faster                                          |
| go                     | 150 ms                                                       | 148 ms: 1.02x faster                                          |
| coroutines             | 23.0 ms                                                      | 22.6 ms: 1.02x faster                                         |
| coverage               | 89.6 ms                                                      | 88.2 ms: 1.02x faster                                         |
| scimark_monte_carlo    | 72.4 ms                                                      | 71.4 ms: 1.01x faster                                         |
| pickle_pure_python     | 323 us                                                       | 318 us: 1.01x faster                                          |
| hexiom                 | 5.96 ms                                                      | 5.89 ms: 1.01x faster                                         |
| richards_super         | 51.7 ms                                                      | 51.1 ms: 1.01x faster                                         |
| scimark_lu             | 101 ms                                                       | 99.6 ms: 1.01x faster                                         |
| generators             | 36.7 ms                                                      | 36.3 ms: 1.01x faster                                         |
| raytrace               | 302 ms                                                       | 299 ms: 1.01x faster                                          |
| meteor_contest         | 128 ms                                                       | 127 ms: 1.01x faster                                          |
| 2to3                   | 287 ms                                                       | 284 ms: 1.01x faster                                          |
| sqlglot_normalize      | 117 ms                                                       | 116 ms: 1.01x faster                                          |
| async_generators       | 385 ms                                                       | 382 ms: 1.01x faster                                          |
| regex_dna              | 241 ms                                                       | 239 ms: 1.01x faster                                          |
| sqlglot_parse          | 1.40 ms                                                      | 1.39 ms: 1.01x faster                                         |
| mako                   | 9.94 ms                                                      | 9.88 ms: 1.01x faster                                         |
| scimark_fft            | 304 ms                                                       | 302 ms: 1.01x faster                                          |
| xml_etree_generate     | 86.1 ms                                                      | 85.7 ms: 1.01x faster                                         |
| regex_compile          | 146 ms                                                       | 145 ms: 1.00x faster                                          |
| sqlglot_optimize       | 57.8 ms                                                      | 57.5 ms: 1.00x faster                                         |
| mypy2                  | 368 ms                                                       | 367 ms: 1.00x faster                                          |
| asyncio_tcp_ssl        | 1.58 sec                                                     | 1.57 sec: 1.00x faster                                        |
| spectral_norm          | 91.6 ms                                                      | 91.8 ms: 1.00x slower                                         |
| xml_etree_process      | 58.3 ms                                                      | 58.5 ms: 1.00x slower                                         |
| json_dumps             | 10.2 ms                                                      | 10.3 ms: 1.00x slower                                         |
| mdp                    | 2.53 sec                                                     | 2.55 sec: 1.00x slower                                        |
| deepcopy               | 376 us                                                       | 377 us: 1.01x slower                                          |
| sqlite_synth           | 2.70 us                                                      | 2.71 us: 1.01x slower                                         |
| docutils               | 2.89 sec                                                     | 2.91 sec: 1.01x slower                                        |
| dulwich_log            | 65.3 ms                                                      | 65.9 ms: 1.01x slower                                         |
| logging_simple         | 6.73 us                                                      | 6.80 us: 1.01x slower                                         |
| regex_effbot           | 3.47 ms                                                      | 3.51 ms: 1.01x slower                                         |
| richards               | 45.0 ms                                                      | 45.6 ms: 1.01x slower                                         |
| scimark_sor            | 110 ms                                                       | 112 ms: 1.01x slower                                          |
| xml_etree_parse        | 146 ms                                                       | 148 ms: 1.01x slower                                          |
| telco                  | 6.96 ms                                                      | 7.10 ms: 1.02x slower                                         |
| unpickle_pure_python   | 207 us                                                       | 211 us: 1.02x slower                                          |
| crypto_pyaes           | 80.9 ms                                                      | 82.9 ms: 1.02x slower                                         |
| json_loads             | 24.3 us                                                      | 24.9 us: 1.03x slower                                         |
| fannkuch               | 350 ms                                                       | 363 ms: 1.04x slower                                          |
| gc_traversal           | 3.54 ms                                                      | 3.71 ms: 1.05x slower                                         |
| pyflate                | 447 ms                                                       | 469 ms: 1.05x slower                                          |
| pickle_dict            | 31.7 us                                                      | 33.4 us: 1.05x slower                                         |
| dask                   | 397 ms                                                       | 567 ms: 1.43x slower                                          |
| Geometric mean         | (ref)                                                        | 1.00x faster                                                  |

Benchmark hidden because not significant (21): bench_mp_pool, tornado_http, tomli_loads, sqlglot_transpile, async_tree_cpu_io_mixed, deepcopy_reduce, float, chaos, async_tree_memoization, nqueens, async_tree_io, deltablue, scimark_sparse_mat_mult, comprehensions, json, async_tree_none, unpickle, asyncio_tcp, xml_etree_iterparse, typing_runtime_protocols, logging_format


# HPT report

- Reliability score: 98.69% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
