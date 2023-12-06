
# Results vs. base

- fork: brandtbucher
- ref: call_kw
- machine: linux-x86_64
- commit hash: 53917a5
- commit date: 2023-09-07
- overall geometric mean: 1.01x faster
- HPT reliability: 99.82%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20230911-linux-x86_64-python-b88d9e75f68f102aca45-3.13.0a0-b88d9e7 | bm-20230907-linux-x86_64-brandtbucher-call_kw-3.13.0a0-53917a5 |
|----------------|:---------------------------------------------------------------------:|:--------------------------------------------------------------:|
| docutils       | 2.61 sec                                                              | 2.60 sec: 1.00x faster                                         |
| tornado_http   | 95.3 ms                                                               | 94.7 ms: 1.01x faster                                          |
| Geometric mean | (ref)                                                                 | 1.00x faster                                                   |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20230911-linux-x86_64-python-b88d9e75f68f102aca45-3.13.0a0-b88d9e7 | bm-20230907-linux-x86_64-brandtbucher-call_kw-3.13.0a0-53917a5 |
|----------------|:---------------------------------------------------------------------:|:--------------------------------------------------------------:|
| pidigits       | 188 ms                                                                | 187 ms: 1.00x faster                                           |
| Geometric mean | (ref)                                                                 | 1.00x faster                                                   |

Benchmark hidden because not significant (2): float, nbody

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20230911-linux-x86_64-python-b88d9e75f68f102aca45-3.13.0a0-b88d9e7 | bm-20230907-linux-x86_64-brandtbucher-call_kw-3.13.0a0-53917a5 |
|----------------|:---------------------------------------------------------------------:|:--------------------------------------------------------------:|
| regex_v8       | 24.4 ms                                                               | 23.6 ms: 1.03x faster                                          |
| regex_effbot   | 3.57 ms                                                               | 3.47 ms: 1.03x faster                                          |
| regex_dna      | 211 ms                                                                | 208 ms: 1.01x faster                                           |
| regex_compile  | 135 ms                                                                | 134 ms: 1.01x faster                                           |
| Geometric mean | (ref)                                                                 | 1.02x faster                                                   |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20230911-linux-x86_64-python-b88d9e75f68f102aca45-3.13.0a0-b88d9e7 | bm-20230907-linux-x86_64-brandtbucher-call_kw-3.13.0a0-53917a5 |
|----------------------|:---------------------------------------------------------------------:|:--------------------------------------------------------------:|
| json_loads           | 25.6 us                                                               | 25.2 us: 1.01x faster                                          |
| xml_etree_parse      | 153 ms                                                                | 152 ms: 1.01x faster                                           |
| pickle_dict          | 31.3 us                                                               | 31.1 us: 1.01x faster                                          |
| pickle_list          | 4.77 us                                                               | 4.75 us: 1.00x faster                                          |
| pickle_pure_python   | 298 us                                                                | 300 us: 1.01x slower                                           |
| unpickle_pure_python | 213 us                                                                | 216 us: 1.01x slower                                           |
| pickle               | 10.6 us                                                               | 10.8 us: 1.02x slower                                          |
| Geometric mean       | (ref)                                                                 | 1.00x faster                                                   |

Benchmark hidden because not significant (7): unpickle_list, json_dumps, xml_etree_iterparse, tomli_loads, unpickle, xml_etree_generate, xml_etree_process

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20230911-linux-x86_64-python-b88d9e75f68f102aca45-3.13.0a0-b88d9e7 | bm-20230907-linux-x86_64-brandtbucher-call_kw-3.13.0a0-53917a5 |
|------------------------|:---------------------------------------------------------------------:|:--------------------------------------------------------------:|
| python_startup         | 10.1 ms                                                               | 10.0 ms: 1.01x faster                                          |
| python_startup_no_site | 6.84 ms                                                               | 6.81 ms: 1.00x faster                                          |
| Geometric mean         | (ref)                                                                 | 1.01x faster                                                   |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20230911-linux-x86_64-python-b88d9e75f68f102aca45-3.13.0a0-b88d9e7 | bm-20230907-linux-x86_64-brandtbucher-call_kw-3.13.0a0-53917a5 |
|-----------|:---------------------------------------------------------------------:|:--------------------------------------------------------------:|
| mako      | 10.6 ms                                                               | 10.5 ms: 1.01x faster                                          |

All benchmarks:
===============

| Benchmark               | bm-20230911-linux-x86_64-python-b88d9e75f68f102aca45-3.13.0a0-b88d9e7 | bm-20230907-linux-x86_64-brandtbucher-call_kw-3.13.0a0-53917a5 |
|-------------------------|:---------------------------------------------------------------------:|:--------------------------------------------------------------:|
| unpack_sequence         | 45.9 ns                                                               | 43.1 ns: 1.06x faster                                          |
| json                    | 5.03 ms                                                               | 4.78 ms: 1.05x faster                                          |
| scimark_sparse_mat_mult | 4.86 ms                                                               | 4.63 ms: 1.05x faster                                          |
| regex_v8                | 24.4 ms                                                               | 23.6 ms: 1.03x faster                                          |
| regex_effbot            | 3.57 ms                                                               | 3.47 ms: 1.03x faster                                          |
| spectral_norm           | 107 ms                                                                | 105 ms: 1.02x faster                                           |
| telco                   | 8.18 ms                                                               | 8.00 ms: 1.02x faster                                          |
| scimark_fft             | 361 ms                                                                | 354 ms: 1.02x faster                                           |
| asyncio_tcp             | 490 ms                                                                | 481 ms: 1.02x faster                                           |
| crypto_pyaes            | 69.6 ms                                                               | 68.3 ms: 1.02x faster                                          |
| scimark_sor             | 123 ms                                                                | 121 ms: 1.02x faster                                           |
| go                      | 140 ms                                                                | 138 ms: 1.02x faster                                           |
| deepcopy_reduce         | 3.14 us                                                               | 3.10 us: 1.02x faster                                          |
| async_tree_cpu_io_mixed | 712 ms                                                                | 701 ms: 1.02x faster                                           |
| regex_dna               | 211 ms                                                                | 208 ms: 1.01x faster                                           |
| json_loads              | 25.6 us                                                               | 25.2 us: 1.01x faster                                          |
| meteor_contest          | 107 ms                                                                | 105 ms: 1.01x faster                                           |
| mako                    | 10.6 ms                                                               | 10.5 ms: 1.01x faster                                          |
| deepcopy_memo           | 37.0 us                                                               | 36.5 us: 1.01x faster                                          |
| hexiom                  | 6.08 ms                                                               | 6.02 ms: 1.01x faster                                          |
| logging_simple          | 5.92 us                                                               | 5.86 us: 1.01x faster                                          |
| dask                    | 528 ms                                                                | 523 ms: 1.01x faster                                           |
| deepcopy                | 347 us                                                                | 344 us: 1.01x faster                                           |
| scimark_monte_carlo     | 65.9 ms                                                               | 65.3 ms: 1.01x faster                                          |
| bench_thread_pool       | 812 us                                                                | 806 us: 1.01x faster                                           |
| xml_etree_parse         | 153 ms                                                                | 152 ms: 1.01x faster                                           |
| regex_compile           | 135 ms                                                                | 134 ms: 1.01x faster                                           |
| python_startup          | 10.1 ms                                                               | 10.0 ms: 1.01x faster                                          |
| tornado_http            | 95.3 ms                                                               | 94.7 ms: 1.01x faster                                          |
| dulwich_log             | 66.5 ms                                                               | 66.1 ms: 1.01x faster                                          |
| pickle_dict             | 31.3 us                                                               | 31.1 us: 1.01x faster                                          |
| pickle_list             | 4.77 us                                                               | 4.75 us: 1.00x faster                                          |
| create_gc_cycles        | 1.53 ms                                                               | 1.52 ms: 1.00x faster                                          |
| raytrace                | 269 ms                                                                | 268 ms: 1.00x faster                                           |
| python_startup_no_site  | 6.84 ms                                                               | 6.81 ms: 1.00x faster                                          |
| pidigits                | 188 ms                                                                | 187 ms: 1.00x faster                                           |
| docutils                | 2.61 sec                                                              | 2.60 sec: 1.00x faster                                         |
| mypy2                   | 337 ms                                                                | 337 ms: 1.00x faster                                           |
| gc_traversal            | 4.11 ms                                                               | 4.10 ms: 1.00x faster                                          |
| sqlglot_normalize       | 104 ms                                                                | 105 ms: 1.00x slower                                           |
| mdp                     | 2.52 sec                                                              | 2.53 sec: 1.00x slower                                         |
| comprehensions          | 20.6 us                                                               | 20.7 us: 1.00x slower                                          |
| nqueens                 | 78.5 ms                                                               | 78.8 ms: 1.00x slower                                          |
| fannkuch                | 377 ms                                                                | 378 ms: 1.00x slower                                           |
| pprint_pformat          | 1.48 sec                                                              | 1.48 sec: 1.01x slower                                         |
| sqlite_synth            | 2.75 us                                                               | 2.76 us: 1.01x slower                                          |
| generators              | 29.1 ms                                                               | 29.3 ms: 1.01x slower                                          |
| deltablue               | 3.26 ms                                                               | 3.28 ms: 1.01x slower                                          |
| coverage                | 85.0 ms                                                               | 85.6 ms: 1.01x slower                                          |
| pickle_pure_python      | 298 us                                                                | 300 us: 1.01x slower                                           |
| async_generators        | 440 ms                                                                | 446 ms: 1.01x slower                                           |
| chaos                   | 59.7 ms                                                               | 60.4 ms: 1.01x slower                                          |
| sqlglot_parse           | 1.26 ms                                                               | 1.28 ms: 1.01x slower                                          |
| unpickle_pure_python    | 213 us                                                                | 216 us: 1.01x slower                                           |
| pickle                  | 10.6 us                                                               | 10.8 us: 1.02x slower                                          |
| sqlglot_transpile       | 1.57 ms                                                               | 1.60 ms: 1.02x slower                                          |
| richards                | 47.7 ms                                                               | 48.6 ms: 1.02x slower                                          |
| scimark_lu              | 108 ms                                                                | 111 ms: 1.03x slower                                           |
| Geometric mean          | (ref)                                                                 | 1.01x faster                                                   |

Benchmark hidden because not significant (24): unpickle_list, logging_silent, float, async_tree_memoization, logging_format, richards_super, json_dumps, xml_etree_iterparse, typing_runtime_protocols, nbody, pycparser, tomli_loads, sqlglot_optimize, async_tree_io, coroutines, unpickle, async_tree_none, bench_mp_pool, asyncio_tcp_ssl, xml_etree_generate, pprint_safe_repr, pathlib, pyflate, xml_etree_process


# HPT report

- Reliability score: 99.82% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
