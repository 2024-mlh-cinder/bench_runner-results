
# Results vs. 3.10.4

- fork: python
- ref: v3.11.0b2
- machine: linux-x86_64
- commit hash: 72f00f4
- commit date: 2022-05-30
- overall geometric mean: 1.23x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.17x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20220530-pythonperf2-x86_64-python-v3.11.0b2-3.11.0b2-72f00f4 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| 2to3           | 349 ms                                                       | 282 ms: 1.24x faster                                             |
| chameleon      | 9.88 ms                                                      | 7.52 ms: 1.31x faster                                            |
| docutils       | 3.42 sec                                                     | 2.83 sec: 1.21x faster                                           |
| html5lib       | 94.7 ms                                                      | 70.5 ms: 1.34x faster                                            |
| tornado_http   | 157 ms                                                       | 117 ms: 1.33x faster                                             |
| Geometric mean | (ref)                                                        | 1.29x faster                                                     |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20220530-pythonperf2-x86_64-python-v3.11.0b2-3.11.0b2-72f00f4 |
|-------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| async_tree_io           | 1.61 sec                                                     | 1.16 sec: 1.38x faster                                           |
| async_tree_none         | 700 ms                                                       | 511 ms: 1.37x faster                                             |
| async_tree_memoization  | 827 ms                                                       | 609 ms: 1.36x faster                                             |
| async_tree_cpu_io_mixed | 946 ms                                                       | 740 ms: 1.28x faster                                             |
| Geometric mean          | (ref)                                                        | 1.35x faster                                                     |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20220530-pythonperf2-x86_64-python-v3.11.0b2-3.11.0b2-72f00f4 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| float          | 109 ms                                                       | 73.8 ms: 1.47x faster                                            |
| nbody          | 134 ms                                                       | 96.9 ms: 1.38x faster                                            |
| pidigits       | 270 ms                                                       | 251 ms: 1.08x faster                                             |
| Geometric mean | (ref)                                                        | 1.30x faster                                                     |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20220530-pythonperf2-x86_64-python-v3.11.0b2-3.11.0b2-72f00f4 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| regex_compile  | 192 ms                                                       | 157 ms: 1.23x faster                                             |
| regex_dna      | 260 ms                                                       | 227 ms: 1.15x faster                                             |
| regex_v8       | 27.1 ms                                                      | 24.1 ms: 1.12x faster                                            |
| regex_effbot   | 3.10 ms                                                      | 3.11 ms: 1.01x slower                                            |
| Geometric mean | (ref)                                                        | 1.12x faster                                                     |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20220530-pythonperf2-x86_64-python-v3.11.0b2-3.11.0b2-72f00f4 |
|----------------------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| pickle_pure_python   | 453 us                                                       | 320 us: 1.41x faster                                             |
| xml_etree_process    | 76.4 ms                                                      | 55.8 ms: 1.37x faster                                            |
| unpickle_pure_python | 315 us                                                       | 234 us: 1.35x faster                                             |
| json_loads           | 30.0 us                                                      | 25.1 us: 1.20x faster                                            |
| xml_etree_generate   | 93.1 ms                                                      | 79.0 ms: 1.18x faster                                            |
| pickle_list          | 4.23 us                                                      | 3.86 us: 1.10x faster                                            |
| json_dumps           | 14.2 ms                                                      | 13.3 ms: 1.07x faster                                            |
| unpickle             | 13.9 us                                                      | 13.3 us: 1.05x faster                                            |
| xml_etree_parse      | 159 ms                                                       | 153 ms: 1.04x faster                                             |
| xml_etree_iterparse  | 110 ms                                                       | 106 ms: 1.03x faster                                             |
| pickle               | 10.1 us                                                      | 9.77 us: 1.03x faster                                            |
| unpickle_list        | 4.45 us                                                      | 4.57 us: 1.03x slower                                            |
| Geometric mean       | (ref)                                                        | 1.13x faster                                                     |

Benchmark hidden because not significant (1): pickle_dict

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20220530-pythonperf2-x86_64-python-v3.11.0b2-3.11.0b2-72f00f4 |
|------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| python_startup         | 11.5 ms                                                      | 10.7 ms: 1.08x faster                                            |
| python_startup_no_site | 7.35 ms                                                      | 7.70 ms: 1.05x slower                                            |
| Geometric mean         | (ref)                                                        | 1.02x faster                                                     |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20220530-pythonperf2-x86_64-python-v3.11.0b2-3.11.0b2-72f00f4 |
|-----------------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| mako            | 14.7 ms                                                      | 10.9 ms: 1.35x faster                                            |
| genshi_text     | 32.3 ms                                                      | 24.4 ms: 1.32x faster                                            |
| django_template | 51.8 ms                                                      | 39.5 ms: 1.31x faster                                            |
| genshi_xml      | 64.1 ms                                                      | 56.0 ms: 1.14x faster                                            |
| Geometric mean  | (ref)                                                        | 1.28x faster                                                     |

All benchmarks:
===============

| Benchmark               | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20220530-pythonperf2-x86_64-python-v3.11.0b2-3.11.0b2-72f00f4 |
|-------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| deltablue               | 7.43 ms                                                      | 3.98 ms: 1.87x faster                                            |
| scimark_sor             | 183 ms                                                       | 108 ms: 1.70x faster                                             |
| logging_silent          | 168 ns                                                       | 98.9 ns: 1.70x faster                                            |
| go                      | 258 ms                                                       | 154 ms: 1.67x faster                                             |
| raytrace                | 497 ms                                                       | 305 ms: 1.63x faster                                             |
| scimark_monte_carlo     | 109 ms                                                       | 67.5 ms: 1.62x faster                                            |
| pyflate                 | 698 ms                                                       | 431 ms: 1.62x faster                                             |
| richards                | 76.3 ms                                                      | 48.5 ms: 1.57x faster                                            |
| spectral_norm           | 141 ms                                                       | 93.4 ms: 1.51x faster                                            |
| bench_mp_pool           | 6.82 ms                                                      | 4.55 ms: 1.50x faster                                            |
| scimark_lu              | 165 ms                                                       | 111 ms: 1.48x faster                                             |
| float                   | 109 ms                                                       | 73.8 ms: 1.47x faster                                            |
| chaos                   | 106 ms                                                       | 72.1 ms: 1.47x faster                                            |
| crypto_pyaes            | 118 ms                                                       | 83.5 ms: 1.41x faster                                            |
| pickle_pure_python      | 453 us                                                       | 320 us: 1.41x faster                                             |
| nbody                   | 134 ms                                                       | 96.9 ms: 1.38x faster                                            |
| async_tree_io           | 1.61 sec                                                     | 1.16 sec: 1.38x faster                                           |
| async_tree_none         | 700 ms                                                       | 511 ms: 1.37x faster                                             |
| pprint_safe_repr        | 1.04 sec                                                     | 759 ms: 1.37x faster                                             |
| xml_etree_process       | 76.4 ms                                                      | 55.8 ms: 1.37x faster                                            |
| pprint_pformat          | 2.15 sec                                                     | 1.57 sec: 1.37x faster                                           |
| deepcopy_memo           | 50.5 us                                                      | 36.9 us: 1.37x faster                                            |
| async_tree_memoization  | 827 ms                                                       | 609 ms: 1.36x faster                                             |
| hexiom                  | 9.46 ms                                                      | 6.99 ms: 1.35x faster                                            |
| mako                    | 14.7 ms                                                      | 10.9 ms: 1.35x faster                                            |
| unpickle_pure_python    | 315 us                                                       | 234 us: 1.35x faster                                             |
| html5lib                | 94.7 ms                                                      | 70.5 ms: 1.34x faster                                            |
| unpack_sequence         | 60.3 ns                                                      | 45.1 ns: 1.34x faster                                            |
| async_generators        | 418 ms                                                       | 313 ms: 1.33x faster                                             |
| tornado_http            | 157 ms                                                       | 117 ms: 1.33x faster                                             |
| genshi_text             | 32.3 ms                                                      | 24.4 ms: 1.32x faster                                            |
| chameleon               | 9.88 ms                                                      | 7.52 ms: 1.31x faster                                            |
| django_template         | 51.8 ms                                                      | 39.5 ms: 1.31x faster                                            |
| gunicorn                | 1.20 ms                                                      | 929 us: 1.29x faster                                             |
| scimark_sparse_mat_mult | 5.21 ms                                                      | 4.05 ms: 1.29x faster                                            |
| thrift                  | 1.20 ms                                                      | 935 us: 1.28x faster                                             |
| aiohttp                 | 1.21 ms                                                      | 944 us: 1.28x faster                                             |
| scimark_fft             | 363 ms                                                       | 284 ms: 1.28x faster                                             |
| async_tree_cpu_io_mixed | 946 ms                                                       | 740 ms: 1.28x faster                                             |
| pycparser               | 1.65 sec                                                     | 1.30 sec: 1.27x faster                                           |
| logging_simple          | 9.06 us                                                      | 7.21 us: 1.26x faster                                            |
| logging_format          | 9.82 us                                                      | 7.81 us: 1.26x faster                                            |
| 2to3                    | 349 ms                                                       | 282 ms: 1.24x faster                                             |
| sqlalchemy_declarative  | 189 ms                                                       | 153 ms: 1.24x faster                                             |
| regex_compile           | 192 ms                                                       | 157 ms: 1.23x faster                                             |
| docutils                | 3.42 sec                                                     | 2.83 sec: 1.21x faster                                           |
| json_loads              | 30.0 us                                                      | 25.1 us: 1.20x faster                                            |
| sqlglot_transpile       | 2.73 ms                                                      | 2.29 ms: 1.19x faster                                            |
| deepcopy                | 459 us                                                       | 385 us: 1.19x faster                                             |
| dulwich_log             | 80.0 ms                                                      | 67.2 ms: 1.19x faster                                            |
| sqlalchemy_imperative   | 23.0 ms                                                      | 19.4 ms: 1.19x faster                                            |
| sqlglot_normalize       | 146 ms                                                       | 124 ms: 1.18x faster                                             |
| xml_etree_generate      | 93.1 ms                                                      | 79.0 ms: 1.18x faster                                            |
| sqlglot_optimize        | 69.9 ms                                                      | 59.7 ms: 1.17x faster                                            |
| sqlite_synth            | 2.97 us                                                      | 2.54 us: 1.17x faster                                            |
| sqlglot_parse           | 2.27 ms                                                      | 1.95 ms: 1.17x faster                                            |
| deepcopy_reduce         | 4.00 us                                                      | 3.47 us: 1.15x faster                                            |
| regex_dna               | 260 ms                                                       | 227 ms: 1.15x faster                                             |
| dask                    | 469 ms                                                       | 410 ms: 1.14x faster                                             |
| json                    | 5.91 ms                                                      | 5.16 ms: 1.14x faster                                            |
| nqueens                 | 112 ms                                                       | 97.7 ms: 1.14x faster                                            |
| genshi_xml              | 64.1 ms                                                      | 56.0 ms: 1.14x faster                                            |
| sympy_integrate         | 28.3 ms                                                      | 25.0 ms: 1.13x faster                                            |
| bench_thread_pool       | 1.13 ms                                                      | 1.00 ms: 1.13x faster                                            |
| sympy_expand            | 599 ms                                                       | 533 ms: 1.12x faster                                             |
| regex_v8                | 27.1 ms                                                      | 24.1 ms: 1.12x faster                                            |
| pathlib                 | 21.2 ms                                                      | 19.1 ms: 1.11x faster                                            |
| coroutines              | 30.9 ms                                                      | 27.9 ms: 1.11x faster                                            |
| pylint                  | 564 ms                                                       | 510 ms: 1.11x faster                                             |
| sympy_str               | 359 ms                                                       | 327 ms: 1.10x faster                                             |
| pickle_list             | 4.23 us                                                      | 3.86 us: 1.10x faster                                            |
| sympy_sum               | 194 ms                                                       | 177 ms: 1.09x faster                                             |
| fannkuch                | 488 ms                                                       | 447 ms: 1.09x faster                                             |
| create_gc_cycles        | 1.79 ms                                                      | 1.64 ms: 1.09x faster                                            |
| python_startup          | 11.5 ms                                                      | 10.7 ms: 1.08x faster                                            |
| pidigits                | 270 ms                                                       | 251 ms: 1.08x faster                                             |
| json_dumps              | 14.2 ms                                                      | 13.3 ms: 1.07x faster                                            |
| meteor_contest          | 138 ms                                                       | 129 ms: 1.06x faster                                             |
| mypy2                   | 467 ms                                                       | 439 ms: 1.06x faster                                             |
| asyncio_tcp             | 785 ms                                                       | 746 ms: 1.05x faster                                             |
| unpickle                | 13.9 us                                                      | 13.3 us: 1.05x faster                                            |
| generators              | 57.7 ms                                                      | 55.2 ms: 1.04x faster                                            |
| xml_etree_parse         | 159 ms                                                       | 153 ms: 1.04x faster                                             |
| xml_etree_iterparse     | 110 ms                                                       | 106 ms: 1.03x faster                                             |
| mdp                     | 2.94 sec                                                     | 2.85 sec: 1.03x faster                                           |
| telco                   | 7.21 ms                                                      | 6.99 ms: 1.03x faster                                            |
| pickle                  | 10.1 us                                                      | 9.77 us: 1.03x faster                                            |
| regex_effbot            | 3.10 ms                                                      | 3.11 ms: 1.01x slower                                            |
| unpickle_list           | 4.45 us                                                      | 4.57 us: 1.03x slower                                            |
| comprehensions          | 27.0 us                                                      | 27.9 us: 1.03x slower                                            |
| python_startup_no_site  | 7.35 ms                                                      | 7.70 ms: 1.05x slower                                            |
| gc_traversal            | 3.63 ms                                                      | 3.94 ms: 1.09x slower                                            |
| Geometric mean          | (ref)                                                        | 1.23x faster                                                     |

Benchmark hidden because not significant (1): pickle_dict
Ignored benchmarks (7) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120.json: asyncio_tcp_ssl, asyncio_websockets, coverage, flaskblogging, richards_super, tomli_loads, typing_runtime_protocols


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.20x
- 95% likely to have a speedup of 1.18x
- 99% likely to have a speedup of 1.17x
