
# Results vs. base

- fork: colesbury
- ref: biased_reference_cou
- machine: linux-x86_64
- commit hash: 2144e0e
- commit date: 2023-10-12
- overall geometric mean: 1.00x faster
- HPT reliability: 58.48%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

Benchmark hidden because not significant (2): docutils, tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231012-pythonperf2-x86_64-python-19b7ead5eb2fd1a0d194-3.13.0a0-19b7ead | bm-20231012-pythonperf2-x86_64-colesbury-biased_reference_cou-3.13.0a0-2144e0e |
|----------------|:---------------------------------------------------------------------------:|:------------------------------------------------------------------------------:|
| float          | 80.3 ms                                                                     | 81.8 ms: 1.02x slower                                                          |
| nbody          | 88.5 ms                                                                     | 90.5 ms: 1.02x slower                                                          |
| Geometric mean | (ref)                                                                       | 1.01x slower                                                                   |

Benchmark hidden because not significant (1): pidigits

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231012-pythonperf2-x86_64-python-19b7ead5eb2fd1a0d194-3.13.0a0-19b7ead | bm-20231012-pythonperf2-x86_64-colesbury-biased_reference_cou-3.13.0a0-2144e0e |
|----------------|:---------------------------------------------------------------------------:|:------------------------------------------------------------------------------:|
| regex_effbot   | 3.46 ms                                                                     | 3.36 ms: 1.03x faster                                                          |
| regex_v8       | 24.9 ms                                                                     | 24.6 ms: 1.01x faster                                                          |
| regex_compile  | 149 ms                                                                      | 147 ms: 1.01x faster                                                           |
| regex_dna      | 238 ms                                                                      | 245 ms: 1.03x slower                                                           |
| Geometric mean | (ref)                                                                       | 1.01x faster                                                                   |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231012-pythonperf2-x86_64-python-19b7ead5eb2fd1a0d194-3.13.0a0-19b7ead | bm-20231012-pythonperf2-x86_64-colesbury-biased_reference_cou-3.13.0a0-2144e0e |
|----------------------|:---------------------------------------------------------------------------:|:------------------------------------------------------------------------------:|
| tomli_loads          | 2.36 sec                                                                    | 2.22 sec: 1.06x faster                                                         |
| unpickle_list        | 4.73 us                                                                     | 4.63 us: 1.02x faster                                                          |
| pickle_dict          | 32.5 us                                                                     | 31.9 us: 1.02x faster                                                          |
| xml_etree_iterparse  | 107 ms                                                                      | 106 ms: 1.01x faster                                                           |
| pickle               | 10.2 us                                                                     | 10.1 us: 1.01x faster                                                          |
| json_dumps           | 10.5 ms                                                                     | 10.4 ms: 1.01x faster                                                          |
| pickle_pure_python   | 312 us                                                                      | 316 us: 1.01x slower                                                           |
| unpickle_pure_python | 227 us                                                                      | 230 us: 1.01x slower                                                           |
| xml_etree_generate   | 84.8 ms                                                                     | 86.5 ms: 1.02x slower                                                          |
| unpickle             | 14.1 us                                                                     | 14.4 us: 1.02x slower                                                          |
| xml_etree_process    | 58.0 ms                                                                     | 60.0 ms: 1.03x slower                                                          |
| Geometric mean       | (ref)                                                                       | 1.00x faster                                                                   |

Benchmark hidden because not significant (3): xml_etree_parse, pickle_list, json_loads

Benchmarks with tag 'startup':
==============================

| Benchmark      | bm-20231012-pythonperf2-x86_64-python-19b7ead5eb2fd1a0d194-3.13.0a0-19b7ead | bm-20231012-pythonperf2-x86_64-colesbury-biased_reference_cou-3.13.0a0-2144e0e |
|----------------|:---------------------------------------------------------------------------:|:------------------------------------------------------------------------------:|
| python_startup | 12.6 ms                                                                     | 12.6 ms: 1.00x slower                                                          |
| Geometric mean | (ref)                                                                       | 1.00x slower                                                                   |

Benchmark hidden because not significant (1): python_startup_no_site

Benchmarks with tag 'template':
===============================

Benchmark hidden because not significant (1): mako

All benchmarks:
===============

| Benchmark            | bm-20231012-pythonperf2-x86_64-python-19b7ead5eb2fd1a0d194-3.13.0a0-19b7ead | bm-20231012-pythonperf2-x86_64-colesbury-biased_reference_cou-3.13.0a0-2144e0e |
|----------------------|:---------------------------------------------------------------------------:|:------------------------------------------------------------------------------:|
| unpack_sequence      | 54.1 ns                                                                     | 49.6 ns: 1.09x faster                                                          |
| tomli_loads          | 2.36 sec                                                                    | 2.22 sec: 1.06x faster                                                         |
| regex_effbot         | 3.46 ms                                                                     | 3.36 ms: 1.03x faster                                                          |
| meteor_contest       | 133 ms                                                                      | 129 ms: 1.03x faster                                                           |
| logging_format       | 7.50 us                                                                     | 7.33 us: 1.02x faster                                                          |
| unpickle_list        | 4.73 us                                                                     | 4.63 us: 1.02x faster                                                          |
| pickle_dict          | 32.5 us                                                                     | 31.9 us: 1.02x faster                                                          |
| richards             | 54.9 ms                                                                     | 54.0 ms: 1.02x faster                                                          |
| telco                | 8.20 ms                                                                     | 8.07 ms: 1.02x faster                                                          |
| logging_simple       | 6.88 us                                                                     | 6.78 us: 1.02x faster                                                          |
| regex_v8             | 24.9 ms                                                                     | 24.6 ms: 1.01x faster                                                          |
| sqlite_synth         | 2.71 us                                                                     | 2.67 us: 1.01x faster                                                          |
| regex_compile        | 149 ms                                                                      | 147 ms: 1.01x faster                                                           |
| nqueens              | 88.1 ms                                                                     | 87.2 ms: 1.01x faster                                                          |
| scimark_fft          | 298 ms                                                                      | 294 ms: 1.01x faster                                                           |
| deepcopy_reduce      | 3.37 us                                                                     | 3.34 us: 1.01x faster                                                          |
| xml_etree_iterparse  | 107 ms                                                                      | 106 ms: 1.01x faster                                                           |
| richards_super       | 60.2 ms                                                                     | 59.6 ms: 1.01x faster                                                          |
| pickle               | 10.2 us                                                                     | 10.1 us: 1.01x faster                                                          |
| scimark_sor          | 149 ms                                                                      | 148 ms: 1.01x faster                                                           |
| json_dumps           | 10.5 ms                                                                     | 10.4 ms: 1.01x faster                                                          |
| spectral_norm        | 91.7 ms                                                                     | 91.1 ms: 1.01x faster                                                          |
| scimark_lu           | 102 ms                                                                      | 101 ms: 1.01x faster                                                           |
| sqlglot_normalize    | 116 ms                                                                      | 116 ms: 1.00x faster                                                           |
| pyflate              | 514 ms                                                                      | 511 ms: 1.00x faster                                                           |
| dulwich_log          | 70.0 ms                                                                     | 69.7 ms: 1.00x faster                                                          |
| pathlib              | 19.5 ms                                                                     | 19.4 ms: 1.00x faster                                                          |
| python_startup       | 12.6 ms                                                                     | 12.6 ms: 1.00x slower                                                          |
| sqlglot_optimize     | 58.4 ms                                                                     | 58.7 ms: 1.00x slower                                                          |
| mypy2                | 371 ms                                                                      | 374 ms: 1.01x slower                                                           |
| asyncio_tcp          | 366 ms                                                                      | 369 ms: 1.01x slower                                                           |
| logging_silent       | 97.3 ns                                                                     | 98.1 ns: 1.01x slower                                                          |
| sqlglot_parse        | 1.41 ms                                                                     | 1.43 ms: 1.01x slower                                                          |
| generators           | 35.2 ms                                                                     | 35.6 ms: 1.01x slower                                                          |
| pycparser            | 1.29 sec                                                                    | 1.31 sec: 1.01x slower                                                         |
| fannkuch             | 392 ms                                                                      | 396 ms: 1.01x slower                                                           |
| deltablue            | 3.66 ms                                                                     | 3.71 ms: 1.01x slower                                                          |
| deepcopy_memo        | 37.0 us                                                                     | 37.5 us: 1.01x slower                                                          |
| pickle_pure_python   | 312 us                                                                      | 316 us: 1.01x slower                                                           |
| gc_traversal         | 3.71 ms                                                                     | 3.76 ms: 1.01x slower                                                          |
| unpickle_pure_python | 227 us                                                                      | 230 us: 1.01x slower                                                           |
| async_generators     | 386 ms                                                                      | 392 ms: 1.01x slower                                                           |
| mdp                  | 2.52 sec                                                                    | 2.57 sec: 1.02x slower                                                         |
| float                | 80.3 ms                                                                     | 81.8 ms: 1.02x slower                                                          |
| xml_etree_generate   | 84.8 ms                                                                     | 86.5 ms: 1.02x slower                                                          |
| go                   | 170 ms                                                                      | 173 ms: 1.02x slower                                                           |
| create_gc_cycles     | 1.64 ms                                                                     | 1.68 ms: 1.02x slower                                                          |
| nbody                | 88.5 ms                                                                     | 90.5 ms: 1.02x slower                                                          |
| pprint_pformat       | 1.65 sec                                                                    | 1.69 sec: 1.02x slower                                                         |
| unpickle             | 14.1 us                                                                     | 14.4 us: 1.02x slower                                                          |
| regex_dna            | 238 ms                                                                      | 245 ms: 1.03x slower                                                           |
| pprint_safe_repr     | 809 ms                                                                      | 834 ms: 1.03x slower                                                           |
| scimark_monte_carlo  | 69.8 ms                                                                     | 72.1 ms: 1.03x slower                                                          |
| xml_etree_process    | 58.0 ms                                                                     | 60.0 ms: 1.03x slower                                                          |
| Geometric mean       | (ref)                                                                       | 1.00x faster                                                                   |

Benchmark hidden because not significant (27): bench_mp_pool, scimark_sparse_mat_mult, coroutines, xml_etree_parse, tornado_http, pickle_list, chaos, coverage, crypto_pyaes, docutils, deepcopy, async_tree_io, mako, asyncio_tcp_ssl, async_tree_none, json, python_startup_no_site, pidigits, json_loads, async_tree_memoization, bench_thread_pool, comprehensions, hexiom, typing_runtime_protocols, sqlglot_transpile, async_tree_cpu_io_mixed, raytrace


# HPT report

- Reliability score: 58.48% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
