
# Results vs. 3.12.0

- fork: python
- ref: 7c12e4835ebe52287acd
- machine: linux-x86_64
- commit hash: 7c12e48
- commit date: 2021-10-05
- overall geometric mean: 1.14x slower \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.10x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20211005-pythonperf2-x86_64-python-7c12e4835ebe52287acd-3.11.0a1-7c12e48 |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| 2to3           | 287 ms                                                       | 329 ms: 1.14x slower                                                        |
| docutils       | 2.89 sec                                                     | 3.22 sec: 1.11x slower                                                      |
| tornado_http   | 122 ms                                                       | 136 ms: 1.12x slower                                                        |
| Geometric mean | (ref)                                                        | 1.13x slower                                                                |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20211005-pythonperf2-x86_64-python-7c12e4835ebe52287acd-3.11.0a1-7c12e48 |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| pidigits       | 264 ms                                                       | 266 ms: 1.01x slower                                                        |
| float          | 78.5 ms                                                      | 86.6 ms: 1.10x slower                                                       |
| nbody          | 94.1 ms                                                      | 132 ms: 1.40x slower                                                        |
| Geometric mean | (ref)                                                        | 1.16x slower                                                                |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20211005-pythonperf2-x86_64-python-7c12e4835ebe52287acd-3.11.0a1-7c12e48 |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_effbot   | 3.47 ms                                                      | 3.05 ms: 1.14x faster                                                       |
| regex_v8       | 25.0 ms                                                      | 25.6 ms: 1.03x slower                                                       |
| regex_dna      | 241 ms                                                       | 262 ms: 1.09x slower                                                        |
| regex_compile  | 146 ms                                                       | 169 ms: 1.16x slower                                                        |
| Geometric mean | (ref)                                                        | 1.03x slower                                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20211005-pythonperf2-x86_64-python-7c12e4835ebe52287acd-3.11.0a1-7c12e48 |
|----------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| unpickle             | 14.8 us                                                      | 13.7 us: 1.08x faster                                                       |
| pickle_list          | 4.39 us                                                      | 4.14 us: 1.06x faster                                                       |
| unpickle_list        | 4.77 us                                                      | 4.54 us: 1.05x faster                                                       |
| pickle_dict          | 31.7 us                                                      | 31.5 us: 1.01x faster                                                       |
| pickle               | 10.1 us                                                      | 10.4 us: 1.03x slower                                                       |
| xml_etree_iterparse  | 103 ms                                                       | 111 ms: 1.08x slower                                                        |
| xml_etree_parse      | 146 ms                                                       | 158 ms: 1.08x slower                                                        |
| xml_etree_process    | 58.3 ms                                                      | 64.1 ms: 1.10x slower                                                       |
| json_loads           | 24.3 us                                                      | 27.0 us: 1.11x slower                                                       |
| pickle_pure_python   | 323 us                                                       | 394 us: 1.22x slower                                                        |
| json_dumps           | 10.2 ms                                                      | 13.6 ms: 1.33x slower                                                       |
| unpickle_pure_python | 207 us                                                       | 293 us: 1.42x slower                                                        |
| Geometric mean       | (ref)                                                        | 1.08x slower                                                                |

Benchmark hidden because not significant (1): xml_etree_generate

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20211005-pythonperf2-x86_64-python-7c12e4835ebe52287acd-3.11.0a1-7c12e48 |
|------------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| python_startup_no_site | 8.70 ms                                                      | 7.57 ms: 1.15x faster                                                       |
| python_startup         | 11.7 ms                                                      | 11.8 ms: 1.00x slower                                                       |
| Geometric mean         | (ref)                                                        | 1.07x faster                                                                |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20211005-pythonperf2-x86_64-python-7c12e4835ebe52287acd-3.11.0a1-7c12e48 |
|-----------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| mako      | 9.94 ms                                                      | 13.1 ms: 1.31x slower                                                       |

All benchmarks:
===============

| Benchmark               | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20211005-pythonperf2-x86_64-python-7c12e4835ebe52287acd-3.11.0a1-7c12e48 |
|-------------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| coverage                | 89.6 ms                                                      | 72.0 ms: 1.24x faster                                                       |
| python_startup_no_site  | 8.70 ms                                                      | 7.57 ms: 1.15x faster                                                       |
| unpack_sequence         | 53.3 ns                                                      | 46.5 ns: 1.15x faster                                                       |
| regex_effbot            | 3.47 ms                                                      | 3.05 ms: 1.14x faster                                                       |
| unpickle                | 14.8 us                                                      | 13.7 us: 1.08x faster                                                       |
| async_generators        | 385 ms                                                       | 356 ms: 1.08x faster                                                        |
| pickle_list             | 4.39 us                                                      | 4.14 us: 1.06x faster                                                       |
| unpickle_list           | 4.77 us                                                      | 4.54 us: 1.05x faster                                                       |
| telco                   | 6.96 ms                                                      | 6.66 ms: 1.05x faster                                                       |
| logging_format          | 7.37 us                                                      | 7.28 us: 1.01x faster                                                       |
| pickle_dict             | 31.7 us                                                      | 31.5 us: 1.01x faster                                                       |
| python_startup          | 11.7 ms                                                      | 11.8 ms: 1.00x slower                                                       |
| pidigits                | 264 ms                                                       | 266 ms: 1.01x slower                                                        |
| sqlite_synth            | 2.70 us                                                      | 2.76 us: 1.02x slower                                                       |
| regex_v8                | 25.0 ms                                                      | 25.6 ms: 1.03x slower                                                       |
| pickle                  | 10.1 us                                                      | 10.4 us: 1.03x slower                                                       |
| meteor_contest          | 128 ms                                                       | 133 ms: 1.04x slower                                                        |
| json                    | 5.14 ms                                                      | 5.40 ms: 1.05x slower                                                       |
| pathlib                 | 19.8 ms                                                      | 20.9 ms: 1.06x slower                                                       |
| pprint_safe_repr        | 823 ms                                                       | 879 ms: 1.07x slower                                                        |
| deepcopy_reduce         | 3.46 us                                                      | 3.70 us: 1.07x slower                                                       |
| xml_etree_iterparse     | 103 ms                                                       | 111 ms: 1.08x slower                                                        |
| xml_etree_parse         | 146 ms                                                       | 158 ms: 1.08x slower                                                        |
| regex_dna               | 241 ms                                                       | 262 ms: 1.09x slower                                                        |
| bench_thread_pool       | 980 us                                                       | 1.07 ms: 1.09x slower                                                       |
| dask                    | 397 ms                                                       | 433 ms: 1.09x slower                                                        |
| pprint_pformat          | 1.67 sec                                                     | 1.83 sec: 1.09x slower                                                      |
| scimark_sparse_mat_mult | 4.42 ms                                                      | 4.84 ms: 1.09x slower                                                       |
| scimark_fft             | 304 ms                                                       | 333 ms: 1.10x slower                                                        |
| xml_etree_process       | 58.3 ms                                                      | 64.1 ms: 1.10x slower                                                       |
| float                   | 78.5 ms                                                      | 86.6 ms: 1.10x slower                                                       |
| pycparser               | 1.27 sec                                                     | 1.41 sec: 1.11x slower                                                      |
| json_loads              | 24.3 us                                                      | 27.0 us: 1.11x slower                                                       |
| docutils                | 2.89 sec                                                     | 3.22 sec: 1.11x slower                                                      |
| tornado_http            | 122 ms                                                       | 136 ms: 1.12x slower                                                        |
| async_tree_none         | 459 ms                                                       | 515 ms: 1.12x slower                                                        |
| mdp                     | 2.53 sec                                                     | 2.84 sec: 1.12x slower                                                      |
| async_tree_cpu_io_mixed | 706 ms                                                       | 796 ms: 1.13x slower                                                        |
| dulwich_log             | 65.3 ms                                                      | 74.2 ms: 1.14x slower                                                       |
| deepcopy                | 376 us                                                       | 427 us: 1.14x slower                                                        |
| create_gc_cycles        | 1.67 ms                                                      | 1.90 ms: 1.14x slower                                                       |
| nqueens                 | 90.1 ms                                                      | 103 ms: 1.14x slower                                                        |
| 2to3                    | 287 ms                                                       | 329 ms: 1.14x slower                                                        |
| sqlglot_optimize        | 57.8 ms                                                      | 66.6 ms: 1.15x slower                                                       |
| sqlglot_normalize       | 117 ms                                                       | 135 ms: 1.15x slower                                                        |
| regex_compile           | 146 ms                                                       | 169 ms: 1.16x slower                                                        |
| async_tree_io           | 1.06 sec                                                     | 1.24 sec: 1.18x slower                                                      |
| async_tree_memoization  | 553 ms                                                       | 660 ms: 1.19x slower                                                        |
| deepcopy_memo           | 37.4 us                                                      | 44.7 us: 1.19x slower                                                       |
| scimark_monte_carlo     | 72.4 ms                                                      | 87.3 ms: 1.21x slower                                                       |
| pickle_pure_python      | 323 us                                                       | 394 us: 1.22x slower                                                        |
| raytrace                | 302 ms                                                       | 371 ms: 1.23x slower                                                        |
| coroutines              | 23.0 ms                                                      | 28.5 ms: 1.24x slower                                                       |
| crypto_pyaes            | 80.9 ms                                                      | 102 ms: 1.26x slower                                                        |
| spectral_norm           | 91.6 ms                                                      | 120 ms: 1.31x slower                                                        |
| mako                    | 9.94 ms                                                      | 13.1 ms: 1.31x slower                                                       |
| json_dumps              | 10.2 ms                                                      | 13.6 ms: 1.33x slower                                                       |
| scimark_sor             | 110 ms                                                       | 147 ms: 1.33x slower                                                        |
| comprehensions          | 21.9 us                                                      | 29.5 us: 1.35x slower                                                       |
| fannkuch                | 350 ms                                                       | 472 ms: 1.35x slower                                                        |
| hexiom                  | 5.96 ms                                                      | 8.15 ms: 1.37x slower                                                       |
| pyflate                 | 447 ms                                                       | 615 ms: 1.38x slower                                                        |
| chaos                   | 62.9 ms                                                      | 87.5 ms: 1.39x slower                                                       |
| nbody                   | 94.1 ms                                                      | 132 ms: 1.40x slower                                                        |
| go                      | 150 ms                                                       | 211 ms: 1.40x slower                                                        |
| logging_silent          | 95.6 ns                                                      | 134 ns: 1.40x slower                                                        |
| unpickle_pure_python    | 207 us                                                       | 293 us: 1.42x slower                                                        |
| generators              | 36.7 ms                                                      | 52.5 ms: 1.43x slower                                                       |
| scimark_lu              | 101 ms                                                       | 145 ms: 1.44x slower                                                        |
| richards                | 45.0 ms                                                      | 64.9 ms: 1.44x slower                                                       |
| sqlglot_transpile       | 1.80 ms                                                      | 2.76 ms: 1.53x slower                                                       |
| sqlglot_parse           | 1.40 ms                                                      | 2.37 ms: 1.69x slower                                                       |
| deltablue               | 3.29 ms                                                      | 5.73 ms: 1.74x slower                                                       |
| Geometric mean          | (ref)                                                        | 1.14x slower                                                                |

Benchmark hidden because not significant (4): bench_mp_pool, logging_simple, xml_etree_generate, gc_traversal
Ignored benchmarks (6) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: asyncio_tcp, asyncio_tcp_ssl, mypy2, richards_super, tomli_loads, typing_runtime_protocols
Ignored benchmarks (12) of results/bm-20211005-3.11.0a1-7c12e48/bm-20211005-pythonperf2-x86_64-python-7c12e4835ebe52287acd-3.11.0a1-7c12e48.json: chameleon, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.11x
- 95% likely to have a slowdown of 1.11x
- 99% likely to have a slowdown of 1.10x
