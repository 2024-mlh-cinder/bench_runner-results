
# Results vs. 3.12.0

- fork: python
- ref: 3.12
- machine: linux-x86_64
- commit hash: f6287bd
- commit date: 2023-09-22
- overall geometric mean: 1.00x slower
- HPT reliability: 99.70%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230922-pythonperf2-x86_64-python-3.12-3.12.0rc3+-f6287bd |
|----------------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| 2to3           | 287 ms                                                       | 286 ms: 1.00x faster                                          |
| tornado_http   | 122 ms                                                       | 120 ms: 1.02x faster                                          |
| Geometric mean | (ref)                                                        | 1.01x faster                                                  |

Benchmark hidden because not significant (1): docutils

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230922-pythonperf2-x86_64-python-3.12-3.12.0rc3+-f6287bd |
|----------------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| pidigits       | 264 ms                                                       | 264 ms: 1.00x slower                                          |
| float          | 78.5 ms                                                      | 79.0 ms: 1.01x slower                                         |
| Geometric mean | (ref)                                                        | 1.01x faster                                                  |

Benchmark hidden because not significant (1): nbody

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230922-pythonperf2-x86_64-python-3.12-3.12.0rc3+-f6287bd |
|----------------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| regex_compile  | 146 ms                                                       | 145 ms: 1.01x faster                                          |
| regex_v8       | 25.0 ms                                                      | 25.2 ms: 1.01x slower                                         |
| regex_dna      | 241 ms                                                       | 246 ms: 1.02x slower                                          |
| Geometric mean | (ref)                                                        | 1.01x slower                                                  |

Benchmark hidden because not significant (1): regex_effbot

Benchmarks with tag 'serialize':
================================

| Benchmark          | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230922-pythonperf2-x86_64-python-3.12-3.12.0rc3+-f6287bd |
|--------------------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| tomli_loads        | 2.20 sec                                                     | 2.17 sec: 1.01x faster                                        |
| json_dumps         | 10.2 ms                                                      | 10.2 ms: 1.01x faster                                         |
| unpickle_list      | 4.77 us                                                      | 4.74 us: 1.01x faster                                         |
| pickle_pure_python | 323 us                                                       | 324 us: 1.00x slower                                          |
| pickle             | 10.1 us                                                      | 10.2 us: 1.01x slower                                         |
| xml_etree_parse    | 146 ms                                                       | 148 ms: 1.01x slower                                          |
| xml_etree_process  | 58.3 ms                                                      | 59.1 ms: 1.01x slower                                         |
| json_loads         | 24.3 us                                                      | 24.6 us: 1.02x slower                                         |
| pickle_dict        | 31.7 us                                                      | 32.3 us: 1.02x slower                                         |
| Geometric mean     | (ref)                                                        | 1.00x slower                                                  |

Benchmark hidden because not significant (5): xml_etree_generate, unpickle, pickle_list, unpickle_pure_python, xml_etree_iterparse

Benchmarks with tag 'startup':
==============================

Benchmark hidden because not significant (2): python_startup_no_site, python_startup

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230922-pythonperf2-x86_64-python-3.12-3.12.0rc3+-f6287bd |
|-----------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| mako      | 9.94 ms                                                      | 10.1 ms: 1.01x slower                                         |

All benchmarks:
===============

| Benchmark               | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230922-pythonperf2-x86_64-python-3.12-3.12.0rc3+-f6287bd |
|-------------------------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| unpack_sequence         | 53.3 ns                                                      | 48.6 ns: 1.10x faster                                         |
| scimark_monte_carlo     | 72.4 ms                                                      | 70.8 ms: 1.02x faster                                         |
| meteor_contest          | 128 ms                                                       | 125 ms: 1.02x faster                                          |
| tornado_http            | 122 ms                                                       | 120 ms: 1.02x faster                                          |
| pathlib                 | 19.8 ms                                                      | 19.5 ms: 1.02x faster                                         |
| comprehensions          | 21.9 us                                                      | 21.6 us: 1.01x faster                                         |
| scimark_sparse_mat_mult | 4.42 ms                                                      | 4.36 ms: 1.01x faster                                         |
| tomli_loads             | 2.20 sec                                                     | 2.17 sec: 1.01x faster                                        |
| logging_silent          | 95.6 ns                                                      | 94.6 ns: 1.01x faster                                         |
| pprint_safe_repr        | 823 ms                                                       | 817 ms: 1.01x faster                                          |
| json_dumps              | 10.2 ms                                                      | 10.2 ms: 1.01x faster                                         |
| asyncio_tcp             | 381 ms                                                       | 379 ms: 1.01x faster                                          |
| unpickle_list           | 4.77 us                                                      | 4.74 us: 1.01x faster                                         |
| spectral_norm           | 91.6 ms                                                      | 91.0 ms: 1.01x faster                                         |
| regex_compile           | 146 ms                                                       | 145 ms: 1.01x faster                                          |
| 2to3                    | 287 ms                                                       | 286 ms: 1.00x faster                                          |
| pidigits                | 264 ms                                                       | 264 ms: 1.00x slower                                          |
| async_tree_io           | 1.06 sec                                                     | 1.06 sec: 1.00x slower                                        |
| telco                   | 6.96 ms                                                      | 6.98 ms: 1.00x slower                                         |
| generators              | 36.7 ms                                                      | 36.8 ms: 1.00x slower                                         |
| sqlglot_optimize        | 57.8 ms                                                      | 58.0 ms: 1.00x slower                                         |
| hexiom                  | 5.96 ms                                                      | 5.98 ms: 1.00x slower                                         |
| pickle_pure_python      | 323 us                                                       | 324 us: 1.00x slower                                          |
| sqlglot_normalize       | 117 ms                                                       | 118 ms: 1.01x slower                                          |
| dulwich_log             | 65.3 ms                                                      | 65.7 ms: 1.01x slower                                         |
| chaos                   | 62.9 ms                                                      | 63.3 ms: 1.01x slower                                         |
| float                   | 78.5 ms                                                      | 79.0 ms: 1.01x slower                                         |
| scimark_fft             | 304 ms                                                       | 306 ms: 1.01x slower                                          |
| sqlglot_transpile       | 1.80 ms                                                      | 1.82 ms: 1.01x slower                                         |
| deepcopy_memo           | 37.4 us                                                      | 37.7 us: 1.01x slower                                         |
| json                    | 5.14 ms                                                      | 5.19 ms: 1.01x slower                                         |
| pickle                  | 10.1 us                                                      | 10.2 us: 1.01x slower                                         |
| regex_v8                | 25.0 ms                                                      | 25.2 ms: 1.01x slower                                         |
| coverage                | 89.6 ms                                                      | 90.5 ms: 1.01x slower                                         |
| xml_etree_parse         | 146 ms                                                       | 148 ms: 1.01x slower                                          |
| deltablue               | 3.29 ms                                                      | 3.32 ms: 1.01x slower                                         |
| mako                    | 9.94 ms                                                      | 10.1 ms: 1.01x slower                                         |
| xml_etree_process       | 58.3 ms                                                      | 59.1 ms: 1.01x slower                                         |
| async_generators        | 385 ms                                                       | 391 ms: 1.01x slower                                          |
| richards_super          | 51.7 ms                                                      | 52.5 ms: 1.02x slower                                         |
| json_loads              | 24.3 us                                                      | 24.6 us: 1.02x slower                                         |
| scimark_sor             | 110 ms                                                       | 112 ms: 1.02x slower                                          |
| sqlite_synth            | 2.70 us                                                      | 2.75 us: 1.02x slower                                         |
| pickle_dict             | 31.7 us                                                      | 32.3 us: 1.02x slower                                         |
| raytrace                | 302 ms                                                       | 308 ms: 1.02x slower                                          |
| deepcopy                | 376 us                                                       | 384 us: 1.02x slower                                          |
| go                      | 150 ms                                                       | 154 ms: 1.02x slower                                          |
| nqueens                 | 90.1 ms                                                      | 92.1 ms: 1.02x slower                                         |
| regex_dna               | 241 ms                                                       | 246 ms: 1.02x slower                                          |
| richards                | 45.0 ms                                                      | 46.3 ms: 1.03x slower                                         |
| logging_format          | 7.37 us                                                      | 7.58 us: 1.03x slower                                         |
| pyflate                 | 447 ms                                                       | 466 ms: 1.04x slower                                          |
| Geometric mean          | (ref)                                                        | 1.00x slower                                                  |

Benchmark hidden because not significant (31): bench_mp_pool, nbody, bench_thread_pool, create_gc_cycles, typing_runtime_protocols, xml_etree_generate, pprint_pformat, mypy2, unpickle, asyncio_tcp_ssl, regex_effbot, python_startup_no_site, python_startup, dask, async_tree_cpu_io_mixed, mdp, logging_simple, pickle_list, gc_traversal, docutils, unpickle_pure_python, async_tree_none, sqlglot_parse, xml_etree_iterparse, fannkuch, crypto_pyaes, deepcopy_reduce, async_tree_memoization, coroutines, pycparser, scimark_lu


# HPT report

- Reliability score: 99.70% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
