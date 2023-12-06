
# Results vs. 3.12.0

- fork: python
- ref: v3.12.0b2
- machine: linux-x86_64
- commit hash: e6c0efa
- commit date: 2023-06-06
- overall geometric mean: 1.00x slower \*
- HPT reliability: 99.87%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230606-pythonperf2-x86_64-python-v3.12.0b2-3.12.0b2-e6c0efa |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| docutils       | 2.89 sec                                                     | 2.88 sec: 1.01x faster                                           |
| Geometric mean | (ref)                                                        | 1.01x faster                                                     |

Benchmark hidden because not significant (2): 2to3, tornado_http

Benchmarks with tag 'asyncio':
==============================

| Benchmark              | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230606-pythonperf2-x86_64-python-v3.12.0b2-3.12.0b2-e6c0efa |
|------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| async_tree_none        | 459 ms                                                       | 452 ms: 1.02x faster                                             |
| async_tree_memoization | 554 ms                                                       | 546 ms: 1.01x faster                                             |
| async_tree_io          | 1.06 sec                                                     | 1.04 sec: 1.01x faster                                           |
| Geometric mean         | (ref)                                                        | 1.01x faster                                                     |

Benchmark hidden because not significant (1): async_tree_cpu_io_mixed

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230606-pythonperf2-x86_64-python-v3.12.0b2-3.12.0b2-e6c0efa |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| float          | 81.6 ms                                                      | 77.3 ms: 1.06x faster                                            |
| nbody          | 88.2 ms                                                      | 83.7 ms: 1.05x faster                                            |
| pidigits       | 264 ms                                                       | 259 ms: 1.02x faster                                             |
| Geometric mean | (ref)                                                        | 1.04x faster                                                     |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230606-pythonperf2-x86_64-python-v3.12.0b2-3.12.0b2-e6c0efa |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| regex_v8       | 24.4 ms                                                      | 23.6 ms: 1.03x faster                                            |
| regex_effbot   | 3.61 ms                                                      | 3.55 ms: 1.02x faster                                            |
| regex_dna      | 240 ms                                                       | 245 ms: 1.02x slower                                             |
| Geometric mean | (ref)                                                        | 1.01x faster                                                     |

Benchmark hidden because not significant (1): regex_compile

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230606-pythonperf2-x86_64-python-v3.12.0b2-3.12.0b2-e6c0efa |
|----------------------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| unpickle             | 15.3 us                                                      | 14.6 us: 1.05x faster                                            |
| pickle_dict          | 32.0 us                                                      | 31.2 us: 1.03x faster                                            |
| unpickle_pure_python | 210 us                                                       | 205 us: 1.02x faster                                             |
| xml_etree_generate   | 85.3 ms                                                      | 85.6 ms: 1.00x slower                                            |
| json_loads           | 24.3 us                                                      | 24.5 us: 1.01x slower                                            |
| xml_etree_process    | 58.3 ms                                                      | 58.8 ms: 1.01x slower                                            |
| tomli_loads          | 2.17 sec                                                     | 2.19 sec: 1.01x slower                                           |
| xml_etree_parse      | 147 ms                                                       | 148 ms: 1.01x slower                                             |
| unpickle_list        | 4.65 us                                                      | 4.71 us: 1.01x slower                                            |
| pickle_list          | 4.22 us                                                      | 4.27 us: 1.01x slower                                            |
| pickle_pure_python   | 319 us                                                       | 324 us: 1.01x slower                                             |
| Geometric mean       | (ref)                                                        | 1.00x faster                                                     |

Benchmark hidden because not significant (3): json_dumps, pickle, xml_etree_iterparse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230606-pythonperf2-x86_64-python-v3.12.0b2-3.12.0b2-e6c0efa |
|------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| python_startup_no_site | 8.67 ms                                                      | 8.45 ms: 1.03x faster                                            |
| python_startup         | 11.7 ms                                                      | 11.4 ms: 1.02x faster                                            |
| Geometric mean         | (ref)                                                        | 1.02x faster                                                     |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230606-pythonperf2-x86_64-python-v3.12.0b2-3.12.0b2-e6c0efa |
|-----------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| mako      | 10.1 ms                                                      | 9.93 ms: 1.01x faster                                            |

All benchmarks:
===============

| Benchmark               | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230606-pythonperf2-x86_64-python-v3.12.0b2-3.12.0b2-e6c0efa |
|-------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| unpack_sequence         | 54.5 ns                                                      | 49.8 ns: 1.09x faster                                            |
| fannkuch                | 362 ms                                                       | 343 ms: 1.06x faster                                             |
| float                   | 81.6 ms                                                      | 77.3 ms: 1.06x faster                                            |
| nbody                   | 88.2 ms                                                      | 83.7 ms: 1.05x faster                                            |
| generators              | 37.3 ms                                                      | 35.5 ms: 1.05x faster                                            |
| unpickle                | 15.3 us                                                      | 14.6 us: 1.05x faster                                            |
| scimark_sparse_mat_mult | 4.49 ms                                                      | 4.29 ms: 1.04x faster                                            |
| pycparser               | 1.29 sec                                                     | 1.24 sec: 1.04x faster                                           |
| regex_v8                | 24.4 ms                                                      | 23.6 ms: 1.03x faster                                            |
| coroutines              | 23.1 ms                                                      | 22.3 ms: 1.03x faster                                            |
| sqlglot_normalize       | 119 ms                                                       | 116 ms: 1.03x faster                                             |
| pickle_dict             | 32.0 us                                                      | 31.2 us: 1.03x faster                                            |
| python_startup_no_site  | 8.67 ms                                                      | 8.45 ms: 1.03x faster                                            |
| spectral_norm           | 93.9 ms                                                      | 91.6 ms: 1.03x faster                                            |
| scimark_fft             | 303 ms                                                       | 296 ms: 1.02x faster                                             |
| scimark_lu              | 98.6 ms                                                      | 96.3 ms: 1.02x faster                                            |
| unpickle_pure_python    | 210 us                                                       | 205 us: 1.02x faster                                             |
| python_startup          | 11.7 ms                                                      | 11.4 ms: 1.02x faster                                            |
| pprint_safe_repr        | 808 ms                                                       | 792 ms: 1.02x faster                                             |
| pidigits                | 264 ms                                                       | 259 ms: 1.02x faster                                             |
| mdp                     | 2.56 sec                                                     | 2.51 sec: 1.02x faster                                           |
| regex_effbot            | 3.61 ms                                                      | 3.55 ms: 1.02x faster                                            |
| deepcopy_memo           | 36.6 us                                                      | 36.0 us: 1.02x faster                                            |
| go                      | 149 ms                                                       | 147 ms: 1.02x faster                                             |
| async_tree_none         | 459 ms                                                       | 452 ms: 1.02x faster                                             |
| sqlglot_optimize        | 58.4 ms                                                      | 57.5 ms: 1.02x faster                                            |
| crypto_pyaes            | 82.4 ms                                                      | 81.2 ms: 1.01x faster                                            |
| pprint_pformat          | 1.64 sec                                                     | 1.62 sec: 1.01x faster                                           |
| mako                    | 10.1 ms                                                      | 9.93 ms: 1.01x faster                                            |
| async_tree_memoization  | 554 ms                                                       | 546 ms: 1.01x faster                                             |
| async_tree_io           | 1.06 sec                                                     | 1.04 sec: 1.01x faster                                           |
| comprehensions          | 21.8 us                                                      | 21.6 us: 1.01x faster                                            |
| telco                   | 7.16 ms                                                      | 7.08 ms: 1.01x faster                                            |
| sqlglot_parse           | 1.41 ms                                                      | 1.40 ms: 1.01x faster                                            |
| chaos                   | 64.1 ms                                                      | 63.6 ms: 1.01x faster                                            |
| nqueens                 | 90.1 ms                                                      | 89.5 ms: 1.01x faster                                            |
| deepcopy                | 371 us                                                       | 369 us: 1.01x faster                                             |
| docutils                | 2.89 sec                                                     | 2.88 sec: 1.01x faster                                           |
| scimark_monte_carlo     | 69.5 ms                                                      | 69.2 ms: 1.00x faster                                            |
| asyncio_tcp_ssl         | 1.57 sec                                                     | 1.57 sec: 1.00x faster                                           |
| hexiom                  | 5.97 ms                                                      | 5.95 ms: 1.00x faster                                            |
| xml_etree_generate      | 85.3 ms                                                      | 85.6 ms: 1.00x slower                                            |
| logging_silent          | 93.3 ns                                                      | 93.8 ns: 1.01x slower                                            |
| json_loads              | 24.3 us                                                      | 24.5 us: 1.01x slower                                            |
| xml_etree_process       | 58.3 ms                                                      | 58.8 ms: 1.01x slower                                            |
| tomli_loads             | 2.17 sec                                                     | 2.19 sec: 1.01x slower                                           |
| meteor_contest          | 126 ms                                                       | 127 ms: 1.01x slower                                             |
| logging_format          | 7.29 us                                                      | 7.35 us: 1.01x slower                                            |
| xml_etree_parse         | 147 ms                                                       | 148 ms: 1.01x slower                                             |
| richards                | 45.1 ms                                                      | 45.5 ms: 1.01x slower                                            |
| async_generators        | 385 ms                                                       | 389 ms: 1.01x slower                                             |
| unpickle_list           | 4.65 us                                                      | 4.71 us: 1.01x slower                                            |
| pickle_list             | 4.22 us                                                      | 4.27 us: 1.01x slower                                            |
| logging_simple          | 6.64 us                                                      | 6.73 us: 1.01x slower                                            |
| pickle_pure_python      | 319 us                                                       | 324 us: 1.01x slower                                             |
| dulwich_log             | 64.9 ms                                                      | 65.9 ms: 1.02x slower                                            |
| raytrace                | 301 ms                                                       | 307 ms: 1.02x slower                                             |
| regex_dna               | 240 ms                                                       | 245 ms: 1.02x slower                                             |
| gc_traversal            | 3.70 ms                                                      | 3.79 ms: 1.02x slower                                            |
| pathlib                 | 18.7 ms                                                      | 19.3 ms: 1.03x slower                                            |
| create_gc_cycles        | 1.58 ms                                                      | 1.62 ms: 1.03x slower                                            |
| bench_mp_pool           | 4.96 ms                                                      | 5.41 ms: 1.09x slower                                            |
| mypy2                   | 365 ms                                                       | 454 ms: 1.24x slower                                             |
| coverage                | 66.3 ms                                                      | 88.5 ms: 1.33x slower                                            |
| dask                    | 394 ms                                                       | 563 ms: 1.43x slower                                             |
| Geometric mean          | (ref)                                                        | 1.00x slower                                                     |

Benchmark hidden because not significant (18): tornado_http, async_tree_cpu_io_mixed, sqlglot_transpile, json_dumps, sqlite_synth, deepcopy_reduce, pyflate, asyncio_tcp, typing_runtime_protocols, pickle, regex_compile, 2to3, scimark_sor, xml_etree_iterparse, deltablue, json, bench_thread_pool, richards_super
Ignored benchmarks (15) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum


# HPT report

- Reliability score: 99.87% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
