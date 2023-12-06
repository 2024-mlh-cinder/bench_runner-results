
# Results vs. 3.12.0

- fork: python
- ref: f9774e57d84162ff0cba
- machine: linux-x86_64
- commit hash: f9774e5
- commit date: 2023-03-07
- overall geometric mean: 1.00x faster \*
- HPT reliability: 76.67%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230307-pythonperf2-x86_64-python-f9774e57d84162ff0cba-3.12.0a6-f9774e5 |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| 2to3           | 287 ms                                                       | 284 ms: 1.01x faster                                                        |
| docutils       | 2.89 sec                                                     | 2.79 sec: 1.03x faster                                                      |
| tornado_http   | 122 ms                                                       | 115 ms: 1.06x faster                                                        |
| Geometric mean | (ref)                                                        | 1.03x faster                                                                |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230307-pythonperf2-x86_64-python-f9774e57d84162ff0cba-3.12.0a6-f9774e5 |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| float          | 78.5 ms                                                      | 73.9 ms: 1.06x faster                                                       |
| pidigits       | 264 ms                                                       | 251 ms: 1.05x faster                                                        |
| nbody          | 94.1 ms                                                      | 91.0 ms: 1.03x faster                                                       |
| Geometric mean | (ref)                                                        | 1.05x faster                                                                |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230307-pythonperf2-x86_64-python-f9774e57d84162ff0cba-3.12.0a6-f9774e5 |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_v8       | 25.0 ms                                                      | 22.8 ms: 1.10x faster                                                       |
| regex_dna      | 241 ms                                                       | 225 ms: 1.07x faster                                                        |
| regex_effbot   | 3.47 ms                                                      | 3.36 ms: 1.03x faster                                                       |
| Geometric mean | (ref)                                                        | 1.05x faster                                                                |

Benchmark hidden because not significant (1): regex_compile

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230307-pythonperf2-x86_64-python-f9774e57d84162ff0cba-3.12.0a6-f9774e5 |
|----------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| pickle_list          | 4.39 us                                                      | 3.80 us: 1.16x faster                                                       |
| unpickle             | 14.8 us                                                      | 13.4 us: 1.10x faster                                                       |
| unpickle_list        | 4.77 us                                                      | 4.44 us: 1.07x faster                                                       |
| pickle_pure_python   | 323 us                                                       | 306 us: 1.05x faster                                                        |
| xml_etree_generate   | 86.1 ms                                                      | 83.5 ms: 1.03x faster                                                       |
| unpickle_pure_python | 207 us                                                       | 202 us: 1.02x faster                                                        |
| xml_etree_process    | 58.3 ms                                                      | 57.3 ms: 1.02x faster                                                       |
| xml_etree_parse      | 146 ms                                                       | 144 ms: 1.02x faster                                                        |
| pickle               | 10.1 us                                                      | 10.0 us: 1.01x faster                                                       |
| pickle_dict          | 31.7 us                                                      | 31.8 us: 1.00x slower                                                       |
| json_loads           | 24.3 us                                                      | 24.4 us: 1.01x slower                                                       |
| Geometric mean       | (ref)                                                        | 1.03x faster                                                                |

Benchmark hidden because not significant (2): json_dumps, xml_etree_iterparse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230307-pythonperf2-x86_64-python-f9774e57d84162ff0cba-3.12.0a6-f9774e5 |
|------------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| python_startup_no_site | 8.70 ms                                                      | 8.34 ms: 1.04x faster                                                       |
| python_startup         | 11.7 ms                                                      | 11.3 ms: 1.04x faster                                                       |
| Geometric mean         | (ref)                                                        | 1.04x faster                                                                |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230307-pythonperf2-x86_64-python-f9774e57d84162ff0cba-3.12.0a6-f9774e5 |
|-----------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| mako      | 9.94 ms                                                      | 10.0 ms: 1.01x slower                                                       |

All benchmarks:
===============

| Benchmark               | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230307-pythonperf2-x86_64-python-f9774e57d84162ff0cba-3.12.0a6-f9774e5 |
|-------------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| unpack_sequence         | 53.3 ns                                                      | 44.4 ns: 1.20x faster                                                       |
| pickle_list             | 4.39 us                                                      | 3.80 us: 1.16x faster                                                       |
| bench_mp_pool           | 5.34 ms                                                      | 4.84 ms: 1.10x faster                                                       |
| unpickle                | 14.8 us                                                      | 13.4 us: 1.10x faster                                                       |
| regex_v8                | 25.0 ms                                                      | 22.8 ms: 1.10x faster                                                       |
| scimark_fft             | 304 ms                                                       | 278 ms: 1.09x faster                                                        |
| coverage                | 89.6 ms                                                      | 82.2 ms: 1.09x faster                                                       |
| pprint_safe_repr        | 823 ms                                                       | 762 ms: 1.08x faster                                                        |
| pprint_pformat          | 1.67 sec                                                     | 1.55 sec: 1.08x faster                                                      |
| unpickle_list           | 4.77 us                                                      | 4.44 us: 1.07x faster                                                       |
| regex_dna               | 241 ms                                                       | 225 ms: 1.07x faster                                                        |
| scimark_sparse_mat_mult | 4.42 ms                                                      | 4.14 ms: 1.07x faster                                                       |
| pathlib                 | 19.8 ms                                                      | 18.5 ms: 1.07x faster                                                       |
| float                   | 78.5 ms                                                      | 73.9 ms: 1.06x faster                                                       |
| deepcopy_memo           | 37.4 us                                                      | 35.4 us: 1.06x faster                                                       |
| tornado_http            | 122 ms                                                       | 115 ms: 1.06x faster                                                        |
| pickle_pure_python      | 323 us                                                       | 306 us: 1.05x faster                                                        |
| pidigits                | 264 ms                                                       | 251 ms: 1.05x faster                                                        |
| scimark_sor             | 110 ms                                                       | 105 ms: 1.05x faster                                                        |
| python_startup_no_site  | 8.70 ms                                                      | 8.34 ms: 1.04x faster                                                       |
| raytrace                | 302 ms                                                       | 290 ms: 1.04x faster                                                        |
| scimark_monte_carlo     | 72.4 ms                                                      | 69.5 ms: 1.04x faster                                                       |
| python_startup          | 11.7 ms                                                      | 11.3 ms: 1.04x faster                                                       |
| deepcopy_reduce         | 3.46 us                                                      | 3.33 us: 1.04x faster                                                       |
| pyflate                 | 447 ms                                                       | 432 ms: 1.04x faster                                                        |
| docutils                | 2.89 sec                                                     | 2.79 sec: 1.03x faster                                                      |
| nbody                   | 94.1 ms                                                      | 91.0 ms: 1.03x faster                                                       |
| regex_effbot            | 3.47 ms                                                      | 3.36 ms: 1.03x faster                                                       |
| pycparser               | 1.27 sec                                                     | 1.23 sec: 1.03x faster                                                      |
| xml_etree_generate      | 86.1 ms                                                      | 83.5 ms: 1.03x faster                                                       |
| json                    | 5.14 ms                                                      | 5.00 ms: 1.03x faster                                                       |
| create_gc_cycles        | 1.67 ms                                                      | 1.63 ms: 1.03x faster                                                       |
| sqlite_synth            | 2.70 us                                                      | 2.63 us: 1.03x faster                                                       |
| dulwich_log             | 65.3 ms                                                      | 63.7 ms: 1.03x faster                                                       |
| unpickle_pure_python    | 207 us                                                       | 202 us: 1.02x faster                                                        |
| xml_etree_process       | 58.3 ms                                                      | 57.3 ms: 1.02x faster                                                       |
| xml_etree_parse         | 146 ms                                                       | 144 ms: 1.02x faster                                                        |
| logging_silent          | 95.6 ns                                                      | 94.5 ns: 1.01x faster                                                       |
| 2to3                    | 287 ms                                                       | 284 ms: 1.01x faster                                                        |
| telco                   | 6.96 ms                                                      | 6.90 ms: 1.01x faster                                                       |
| pickle                  | 10.1 us                                                      | 10.0 us: 1.01x faster                                                       |
| pickle_dict             | 31.7 us                                                      | 31.8 us: 1.00x slower                                                       |
| meteor_contest          | 128 ms                                                       | 128 ms: 1.00x slower                                                        |
| mdp                     | 2.53 sec                                                     | 2.54 sec: 1.00x slower                                                      |
| json_loads              | 24.3 us                                                      | 24.4 us: 1.01x slower                                                       |
| sqlglot_optimize        | 57.8 ms                                                      | 58.2 ms: 1.01x slower                                                       |
| crypto_pyaes            | 80.9 ms                                                      | 81.5 ms: 1.01x slower                                                       |
| logging_simple          | 6.73 us                                                      | 6.79 us: 1.01x slower                                                       |
| mako                    | 9.94 ms                                                      | 10.0 ms: 1.01x slower                                                       |
| deltablue               | 3.29 ms                                                      | 3.33 ms: 1.01x slower                                                       |
| mypy2                   | 368 ms                                                       | 377 ms: 1.02x slower                                                        |
| sqlglot_normalize       | 117 ms                                                       | 120 ms: 1.03x slower                                                        |
| logging_format          | 7.37 us                                                      | 7.59 us: 1.03x slower                                                       |
| richards                | 45.0 ms                                                      | 46.4 ms: 1.03x slower                                                       |
| scimark_lu              | 101 ms                                                       | 105 ms: 1.04x slower                                                        |
| spectral_norm           | 91.6 ms                                                      | 95.6 ms: 1.04x slower                                                       |
| generators              | 36.7 ms                                                      | 38.4 ms: 1.05x slower                                                       |
| async_tree_cpu_io_mixed | 706 ms                                                       | 745 ms: 1.05x slower                                                        |
| coroutines              | 23.0 ms                                                      | 24.7 ms: 1.07x slower                                                       |
| sqlglot_transpile       | 1.80 ms                                                      | 1.94 ms: 1.07x slower                                                       |
| nqueens                 | 90.1 ms                                                      | 96.9 ms: 1.08x slower                                                       |
| hexiom                  | 5.96 ms                                                      | 6.46 ms: 1.08x slower                                                       |
| async_tree_memoization  | 553 ms                                                       | 611 ms: 1.10x slower                                                        |
| async_tree_io           | 1.06 sec                                                     | 1.17 sec: 1.10x slower                                                      |
| async_tree_none         | 459 ms                                                       | 510 ms: 1.11x slower                                                        |
| sqlglot_parse           | 1.40 ms                                                      | 1.58 ms: 1.12x slower                                                       |
| gc_traversal            | 3.54 ms                                                      | 3.99 ms: 1.13x slower                                                       |
| chaos                   | 62.9 ms                                                      | 70.9 ms: 1.13x slower                                                       |
| fannkuch                | 350 ms                                                       | 408 ms: 1.16x slower                                                        |
| comprehensions          | 21.9 us                                                      | 26.7 us: 1.22x slower                                                       |
| dask                    | 397 ms                                                       | 560 ms: 1.41x slower                                                        |
| Geometric mean          | (ref)                                                        | 1.00x faster                                                                |

Benchmark hidden because not significant (8): bench_thread_pool, async_generators, json_dumps, asyncio_tcp, regex_compile, xml_etree_iterparse, go, deepcopy
Ignored benchmarks (4) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: asyncio_tcp_ssl, richards_super, tomli_loads, typing_runtime_protocols
Ignored benchmarks (10) of results/bm-20230307-3.12.0a6-f9774e5/bm-20230307-pythonperf2-x86_64-python-f9774e57d84162ff0cba-3.12.0a6-f9774e5.json: chameleon, django_template, genshi_text, genshi_xml, html5lib, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 76.67% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
