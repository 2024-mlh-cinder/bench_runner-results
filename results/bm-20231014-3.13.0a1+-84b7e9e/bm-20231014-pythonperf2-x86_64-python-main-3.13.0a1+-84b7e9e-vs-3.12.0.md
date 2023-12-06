
# Results vs. 3.12.0

- fork: python
- ref: main
- machine: linux-x86_64
- commit hash: 84b7e9e
- commit date: 2023-10-14
- overall geometric mean: 1.01x slower
- HPT reliability: 97.06%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231014-pythonperf2-x86_64-python-main-3.13.0a1+-84b7e9e |
|----------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| docutils       | 2.89 sec                                                     | 2.87 sec: 1.01x faster                                       |
| Geometric mean | (ref)                                                        | 1.01x faster                                                 |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231014-pythonperf2-x86_64-python-main-3.13.0a1+-84b7e9e |
|----------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| nbody          | 94.1 ms                                                      | 86.0 ms: 1.09x faster                                        |
| pidigits       | 264 ms                                                       | 264 ms: 1.00x slower                                         |
| float          | 78.5 ms                                                      | 81.4 ms: 1.04x slower                                        |
| Geometric mean | (ref)                                                        | 1.02x faster                                                 |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231014-pythonperf2-x86_64-python-main-3.13.0a1+-84b7e9e |
|----------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| regex_dna      | 241 ms                                                       | 240 ms: 1.00x faster                                         |
| regex_v8       | 25.0 ms                                                      | 25.3 ms: 1.01x slower                                        |
| regex_compile  | 146 ms                                                       | 148 ms: 1.02x slower                                         |
| regex_effbot   | 3.47 ms                                                      | 3.56 ms: 1.03x slower                                        |
| Geometric mean | (ref)                                                        | 1.01x slower                                                 |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231014-pythonperf2-x86_64-python-main-3.13.0a1+-84b7e9e |
|----------------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| pickle_list          | 4.39 us                                                      | 4.15 us: 1.06x faster                                        |
| unpickle             | 14.8 us                                                      | 14.6 us: 1.01x faster                                        |
| xml_etree_generate   | 86.1 ms                                                      | 85.3 ms: 1.01x faster                                        |
| pickle_pure_python   | 323 us                                                       | 320 us: 1.01x faster                                         |
| pickle_dict          | 31.7 us                                                      | 31.9 us: 1.01x slower                                        |
| unpickle_list        | 4.77 us                                                      | 4.82 us: 1.01x slower                                        |
| xml_etree_iterparse  | 103 ms                                                       | 105 ms: 1.02x slower                                         |
| json_dumps           | 10.2 ms                                                      | 10.6 ms: 1.04x slower                                        |
| tomli_loads          | 2.20 sec                                                     | 2.32 sec: 1.05x slower                                       |
| unpickle_pure_python | 207 us                                                       | 219 us: 1.06x slower                                         |
| Geometric mean       | (ref)                                                        | 1.01x slower                                                 |

Benchmark hidden because not significant (4): xml_etree_process, json_loads, xml_etree_parse, pickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231014-pythonperf2-x86_64-python-main-3.13.0a1+-84b7e9e |
|------------------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| python_startup_no_site | 8.70 ms                                                      | 8.66 ms: 1.00x faster                                        |
| python_startup         | 11.7 ms                                                      | 12.6 ms: 1.07x slower                                        |
| Geometric mean         | (ref)                                                        | 1.03x slower                                                 |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231014-pythonperf2-x86_64-python-main-3.13.0a1+-84b7e9e |
|-----------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| mako      | 9.94 ms                                                      | 10.5 ms: 1.05x slower                                        |

All benchmarks:
===============

| Benchmark               | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231014-pythonperf2-x86_64-python-main-3.13.0a1+-84b7e9e |
|-------------------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| bench_mp_pool           | 5.34 ms                                                      | 4.69 ms: 1.14x faster                                        |
| crypto_pyaes            | 80.9 ms                                                      | 73.1 ms: 1.11x faster                                        |
| raytrace                | 302 ms                                                       | 275 ms: 1.10x faster                                         |
| nbody                   | 94.1 ms                                                      | 86.0 ms: 1.09x faster                                        |
| scimark_sparse_mat_mult | 4.42 ms                                                      | 4.06 ms: 1.09x faster                                        |
| scimark_monte_carlo     | 72.4 ms                                                      | 66.5 ms: 1.09x faster                                        |
| async_tree_none         | 459 ms                                                       | 434 ms: 1.06x faster                                         |
| pickle_list             | 4.39 us                                                      | 4.15 us: 1.06x faster                                        |
| coverage                | 89.6 ms                                                      | 85.7 ms: 1.05x faster                                        |
| deepcopy_reduce         | 3.46 us                                                      | 3.32 us: 1.04x faster                                        |
| asyncio_tcp             | 381 ms                                                       | 368 ms: 1.04x faster                                         |
| generators              | 36.7 ms                                                      | 35.5 ms: 1.03x faster                                        |
| nqueens                 | 90.1 ms                                                      | 88.6 ms: 1.02x faster                                        |
| unpickle                | 14.8 us                                                      | 14.6 us: 1.01x faster                                        |
| pathlib                 | 19.8 ms                                                      | 19.6 ms: 1.01x faster                                        |
| pprint_safe_repr        | 823 ms                                                       | 815 ms: 1.01x faster                                         |
| xml_etree_generate      | 86.1 ms                                                      | 85.3 ms: 1.01x faster                                        |
| async_tree_memoization  | 553 ms                                                       | 548 ms: 1.01x faster                                         |
| pickle_pure_python      | 323 us                                                       | 320 us: 1.01x faster                                         |
| docutils                | 2.89 sec                                                     | 2.87 sec: 1.01x faster                                       |
| pprint_pformat          | 1.67 sec                                                     | 1.67 sec: 1.01x faster                                       |
| comprehensions          | 21.9 us                                                      | 21.8 us: 1.00x faster                                        |
| python_startup_no_site  | 8.70 ms                                                      | 8.66 ms: 1.00x faster                                        |
| regex_dna               | 241 ms                                                       | 240 ms: 1.00x faster                                         |
| pidigits                | 264 ms                                                       | 264 ms: 1.00x slower                                         |
| mdp                     | 2.53 sec                                                     | 2.54 sec: 1.00x slower                                       |
| mypy2                   | 368 ms                                                       | 370 ms: 1.00x slower                                         |
| pickle_dict             | 31.7 us                                                      | 31.9 us: 1.01x slower                                        |
| deepcopy_memo           | 37.4 us                                                      | 37.7 us: 1.01x slower                                        |
| scimark_lu              | 101 ms                                                       | 102 ms: 1.01x slower                                         |
| unpickle_list           | 4.77 us                                                      | 4.82 us: 1.01x slower                                        |
| regex_v8                | 25.0 ms                                                      | 25.3 ms: 1.01x slower                                        |
| logging_silent          | 95.6 ns                                                      | 96.9 ns: 1.01x slower                                        |
| coroutines              | 23.0 ms                                                      | 23.3 ms: 1.01x slower                                        |
| async_tree_io           | 1.06 sec                                                     | 1.08 sec: 1.02x slower                                       |
| async_generators        | 385 ms                                                       | 392 ms: 1.02x slower                                         |
| regex_compile           | 146 ms                                                       | 148 ms: 1.02x slower                                         |
| xml_etree_iterparse     | 103 ms                                                       | 105 ms: 1.02x slower                                         |
| spectral_norm           | 91.6 ms                                                      | 93.6 ms: 1.02x slower                                        |
| asyncio_tcp_ssl         | 1.58 sec                                                     | 1.61 sec: 1.02x slower                                       |
| sqlglot_optimize        | 57.8 ms                                                      | 59.2 ms: 1.02x slower                                        |
| regex_effbot            | 3.47 ms                                                      | 3.56 ms: 1.03x slower                                        |
| meteor_contest          | 128 ms                                                       | 131 ms: 1.03x slower                                         |
| logging_simple          | 6.73 us                                                      | 6.93 us: 1.03x slower                                        |
| logging_format          | 7.37 us                                                      | 7.59 us: 1.03x slower                                        |
| unpack_sequence         | 53.3 ns                                                      | 55.1 ns: 1.03x slower                                        |
| float                   | 78.5 ms                                                      | 81.4 ms: 1.04x slower                                        |
| json_dumps              | 10.2 ms                                                      | 10.6 ms: 1.04x slower                                        |
| mako                    | 9.94 ms                                                      | 10.5 ms: 1.05x slower                                        |
| tomli_loads             | 2.20 sec                                                     | 2.32 sec: 1.05x slower                                       |
| dulwich_log             | 65.3 ms                                                      | 69.1 ms: 1.06x slower                                        |
| unpickle_pure_python    | 207 us                                                       | 219 us: 1.06x slower                                         |
| python_startup          | 11.7 ms                                                      | 12.6 ms: 1.07x slower                                        |
| hexiom                  | 5.96 ms                                                      | 6.39 ms: 1.07x slower                                        |
| deltablue               | 3.29 ms                                                      | 3.62 ms: 1.10x slower                                        |
| go                      | 150 ms                                                       | 171 ms: 1.14x slower                                         |
| fannkuch                | 350 ms                                                       | 399 ms: 1.14x slower                                         |
| pyflate                 | 447 ms                                                       | 510 ms: 1.14x slower                                         |
| telco                   | 6.96 ms                                                      | 8.11 ms: 1.16x slower                                        |
| richards_super          | 51.7 ms                                                      | 60.8 ms: 1.18x slower                                        |
| richards                | 45.0 ms                                                      | 55.4 ms: 1.23x slower                                        |
| scimark_sor             | 110 ms                                                       | 145 ms: 1.32x slower                                         |
| Geometric mean          | (ref)                                                        | 1.01x slower                                                 |

Benchmark hidden because not significant (19): async_tree_cpu_io_mixed, json, tornado_http, chaos, typing_runtime_protocols, create_gc_cycles, sqlglot_normalize, sqlglot_parse, gc_traversal, deepcopy, sqlite_synth, sqlglot_transpile, xml_etree_process, json_loads, xml_etree_parse, bench_thread_pool, pycparser, pickle, scimark_fft
Ignored benchmarks (2) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: 2to3, dask


# HPT report

- Reliability score: 97.06% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
