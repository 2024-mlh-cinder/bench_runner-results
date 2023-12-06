
# Results vs. 3.12.0

- fork: colesbury
- ref: biased_reference_cou
- machine: linux-x86_64
- commit hash: 2144e0e
- commit date: 2023-10-12
- overall geometric mean: 1.01x slower
- HPT reliability: 99.24%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231012-pythonperf2-x86_64-colesbury-biased_reference_cou-3.13.0a0-2144e0e |
|----------------|:------------------------------------------------------------:|:------------------------------------------------------------------------------:|
| docutils       | 2.89 sec                                                     | 2.87 sec: 1.00x faster                                                         |
| tornado_http   | 122 ms                                                       | 119 ms: 1.02x faster                                                           |
| Geometric mean | (ref)                                                        | 1.01x faster                                                                   |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231012-pythonperf2-x86_64-colesbury-biased_reference_cou-3.13.0a0-2144e0e |
|----------------|:------------------------------------------------------------:|:------------------------------------------------------------------------------:|
| nbody          | 94.1 ms                                                      | 90.5 ms: 1.04x faster                                                          |
| pidigits       | 264 ms                                                       | 264 ms: 1.00x slower                                                           |
| float          | 78.5 ms                                                      | 81.8 ms: 1.04x slower                                                          |
| Geometric mean | (ref)                                                        | 1.00x slower                                                                   |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231012-pythonperf2-x86_64-colesbury-biased_reference_cou-3.13.0a0-2144e0e |
|----------------|:------------------------------------------------------------:|:------------------------------------------------------------------------------:|
| regex_effbot   | 3.47 ms                                                      | 3.36 ms: 1.03x faster                                                          |
| regex_v8       | 25.0 ms                                                      | 24.6 ms: 1.02x faster                                                          |
| regex_compile  | 146 ms                                                       | 147 ms: 1.01x slower                                                           |
| regex_dna      | 241 ms                                                       | 245 ms: 1.02x slower                                                           |
| Geometric mean | (ref)                                                        | 1.01x faster                                                                   |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231012-pythonperf2-x86_64-colesbury-biased_reference_cou-3.13.0a0-2144e0e |
|----------------------|:------------------------------------------------------------:|:------------------------------------------------------------------------------:|
| unpickle_list        | 4.77 us                                                      | 4.63 us: 1.03x faster                                                          |
| unpickle             | 14.8 us                                                      | 14.4 us: 1.02x faster                                                          |
| pickle_pure_python   | 323 us                                                       | 316 us: 1.02x faster                                                           |
| xml_etree_generate   | 86.1 ms                                                      | 86.5 ms: 1.00x slower                                                          |
| pickle_dict          | 31.7 us                                                      | 31.9 us: 1.01x slower                                                          |
| pickle_list          | 4.39 us                                                      | 4.43 us: 1.01x slower                                                          |
| tomli_loads          | 2.20 sec                                                     | 2.22 sec: 1.01x slower                                                         |
| xml_etree_parse      | 146 ms                                                       | 148 ms: 1.01x slower                                                           |
| json_dumps           | 10.2 ms                                                      | 10.4 ms: 1.02x slower                                                          |
| xml_etree_iterparse  | 103 ms                                                       | 106 ms: 1.03x slower                                                           |
| xml_etree_process    | 58.3 ms                                                      | 60.0 ms: 1.03x slower                                                          |
| unpickle_pure_python | 207 us                                                       | 230 us: 1.11x slower                                                           |
| Geometric mean       | (ref)                                                        | 1.01x slower                                                                   |

Benchmark hidden because not significant (2): json_loads, pickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231012-pythonperf2-x86_64-colesbury-biased_reference_cou-3.13.0a0-2144e0e |
|------------------------|:------------------------------------------------------------:|:------------------------------------------------------------------------------:|
| python_startup_no_site | 8.70 ms                                                      | 8.69 ms: 1.00x faster                                                          |
| python_startup         | 11.7 ms                                                      | 12.6 ms: 1.08x slower                                                          |
| Geometric mean         | (ref)                                                        | 1.04x slower                                                                   |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231012-pythonperf2-x86_64-colesbury-biased_reference_cou-3.13.0a0-2144e0e |
|-----------|:------------------------------------------------------------:|:------------------------------------------------------------------------------:|
| mako      | 9.94 ms                                                      | 10.3 ms: 1.03x slower                                                          |

All benchmarks:
===============

| Benchmark               | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231012-pythonperf2-x86_64-colesbury-biased_reference_cou-3.13.0a0-2144e0e |
|-------------------------|:------------------------------------------------------------:|:------------------------------------------------------------------------------:|
| bench_mp_pool           | 5.34 ms                                                      | 4.58 ms: 1.17x faster                                                          |
| crypto_pyaes            | 80.9 ms                                                      | 72.0 ms: 1.12x faster                                                          |
| coverage                | 89.6 ms                                                      | 82.2 ms: 1.09x faster                                                          |
| scimark_sparse_mat_mult | 4.42 ms                                                      | 4.09 ms: 1.08x faster                                                          |
| unpack_sequence         | 53.3 ns                                                      | 49.6 ns: 1.07x faster                                                          |
| raytrace                | 302 ms                                                       | 282 ms: 1.07x faster                                                           |
| async_tree_none         | 459 ms                                                       | 437 ms: 1.05x faster                                                           |
| nbody                   | 94.1 ms                                                      | 90.5 ms: 1.04x faster                                                          |
| deepcopy_reduce         | 3.46 us                                                      | 3.34 us: 1.04x faster                                                          |
| asyncio_tcp             | 381 ms                                                       | 369 ms: 1.03x faster                                                           |
| nqueens                 | 90.1 ms                                                      | 87.2 ms: 1.03x faster                                                          |
| scimark_fft             | 304 ms                                                       | 294 ms: 1.03x faster                                                           |
| regex_effbot            | 3.47 ms                                                      | 3.36 ms: 1.03x faster                                                          |
| generators              | 36.7 ms                                                      | 35.6 ms: 1.03x faster                                                          |
| chaos                   | 62.9 ms                                                      | 61.0 ms: 1.03x faster                                                          |
| unpickle_list           | 4.77 us                                                      | 4.63 us: 1.03x faster                                                          |
| unpickle                | 14.8 us                                                      | 14.4 us: 1.02x faster                                                          |
| tornado_http            | 122 ms                                                       | 119 ms: 1.02x faster                                                           |
| pickle_pure_python      | 323 us                                                       | 316 us: 1.02x faster                                                           |
| pathlib                 | 19.8 ms                                                      | 19.4 ms: 1.02x faster                                                          |
| regex_v8                | 25.0 ms                                                      | 24.6 ms: 1.02x faster                                                          |
| sqlglot_normalize       | 117 ms                                                       | 116 ms: 1.01x faster                                                           |
| sqlite_synth            | 2.70 us                                                      | 2.67 us: 1.01x faster                                                          |
| spectral_norm           | 91.6 ms                                                      | 91.1 ms: 1.01x faster                                                          |
| docutils                | 2.89 sec                                                     | 2.87 sec: 1.00x faster                                                         |
| scimark_monte_carlo     | 72.4 ms                                                      | 72.1 ms: 1.00x faster                                                          |
| python_startup_no_site  | 8.70 ms                                                      | 8.69 ms: 1.00x faster                                                          |
| pidigits                | 264 ms                                                       | 264 ms: 1.00x slower                                                           |
| asyncio_tcp_ssl         | 1.58 sec                                                     | 1.58 sec: 1.00x slower                                                         |
| xml_etree_generate      | 86.1 ms                                                      | 86.5 ms: 1.00x slower                                                          |
| pickle_dict             | 31.7 us                                                      | 31.9 us: 1.01x slower                                                          |
| scimark_lu              | 101 ms                                                       | 101 ms: 1.01x slower                                                           |
| comprehensions          | 21.9 us                                                      | 22.1 us: 1.01x slower                                                          |
| meteor_contest          | 128 ms                                                       | 129 ms: 1.01x slower                                                           |
| pprint_pformat          | 1.67 sec                                                     | 1.69 sec: 1.01x slower                                                         |
| pickle_list             | 4.39 us                                                      | 4.43 us: 1.01x slower                                                          |
| tomli_loads             | 2.20 sec                                                     | 2.22 sec: 1.01x slower                                                         |
| regex_compile           | 146 ms                                                       | 147 ms: 1.01x slower                                                           |
| pprint_safe_repr        | 823 ms                                                       | 834 ms: 1.01x slower                                                           |
| mdp                     | 2.53 sec                                                     | 2.57 sec: 1.01x slower                                                         |
| xml_etree_parse         | 146 ms                                                       | 148 ms: 1.01x slower                                                           |
| sqlglot_parse           | 1.40 ms                                                      | 1.43 ms: 1.01x slower                                                          |
| sqlglot_transpile       | 1.80 ms                                                      | 1.83 ms: 1.01x slower                                                          |
| sqlglot_optimize        | 57.8 ms                                                      | 58.7 ms: 1.02x slower                                                          |
| mypy2                   | 368 ms                                                       | 374 ms: 1.02x slower                                                           |
| regex_dna               | 241 ms                                                       | 245 ms: 1.02x slower                                                           |
| async_generators        | 385 ms                                                       | 392 ms: 1.02x slower                                                           |
| json_dumps              | 10.2 ms                                                      | 10.4 ms: 1.02x slower                                                          |
| async_tree_io           | 1.06 sec                                                     | 1.08 sec: 1.02x slower                                                         |
| pycparser               | 1.27 sec                                                     | 1.31 sec: 1.02x slower                                                         |
| logging_silent          | 95.6 ns                                                      | 98.1 ns: 1.03x slower                                                          |
| xml_etree_iterparse     | 103 ms                                                       | 106 ms: 1.03x slower                                                           |
| xml_etree_process       | 58.3 ms                                                      | 60.0 ms: 1.03x slower                                                          |
| mako                    | 9.94 ms                                                      | 10.3 ms: 1.03x slower                                                          |
| float                   | 78.5 ms                                                      | 81.8 ms: 1.04x slower                                                          |
| gc_traversal            | 3.54 ms                                                      | 3.76 ms: 1.06x slower                                                          |
| dulwich_log             | 65.3 ms                                                      | 69.7 ms: 1.07x slower                                                          |
| hexiom                  | 5.96 ms                                                      | 6.42 ms: 1.08x slower                                                          |
| python_startup          | 11.7 ms                                                      | 12.6 ms: 1.08x slower                                                          |
| unpickle_pure_python    | 207 us                                                       | 230 us: 1.11x slower                                                           |
| deltablue               | 3.29 ms                                                      | 3.71 ms: 1.13x slower                                                          |
| fannkuch                | 350 ms                                                       | 396 ms: 1.13x slower                                                           |
| pyflate                 | 447 ms                                                       | 511 ms: 1.14x slower                                                           |
| go                      | 150 ms                                                       | 173 ms: 1.15x slower                                                           |
| richards_super          | 51.7 ms                                                      | 59.6 ms: 1.15x slower                                                          |
| telco                   | 6.96 ms                                                      | 8.07 ms: 1.16x slower                                                          |
| richards                | 45.0 ms                                                      | 54.0 ms: 1.20x slower                                                          |
| scimark_sor             | 110 ms                                                       | 148 ms: 1.35x slower                                                           |
| Geometric mean          | (ref)                                                        | 1.01x slower                                                                   |

Benchmark hidden because not significant (13): bench_thread_pool, logging_format, json, deepcopy, async_tree_cpu_io_mixed, json_loads, typing_runtime_protocols, async_tree_memoization, pickle, deepcopy_memo, create_gc_cycles, logging_simple, coroutines
Ignored benchmarks (2) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: 2to3, dask


# HPT report

- Reliability score: 99.24% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
