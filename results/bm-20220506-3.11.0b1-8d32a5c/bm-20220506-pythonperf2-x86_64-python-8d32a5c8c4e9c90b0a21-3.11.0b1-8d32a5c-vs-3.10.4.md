
# Results vs. 3.10.4

- fork: python
- ref: 8d32a5c8c4e9c90b0a21
- machine: linux-x86_64
- commit hash: 8d32a5c
- commit date: 2022-05-06
- overall geometric mean: 1.23x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.17x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20220506-pythonperf2-x86_64-python-8d32a5c8c4e9c90b0a21-3.11.0b1-8d32a5c |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| 2to3           | 349 ms                                                       | 281 ms: 1.24x faster                                                        |
| chameleon      | 9.88 ms                                                      | 7.53 ms: 1.31x faster                                                       |
| docutils       | 3.42 sec                                                     | 2.82 sec: 1.21x faster                                                      |
| html5lib       | 94.7 ms                                                      | 69.0 ms: 1.37x faster                                                       |
| tornado_http   | 157 ms                                                       | 121 ms: 1.29x faster                                                        |
| Geometric mean | (ref)                                                        | 1.28x faster                                                                |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20220506-pythonperf2-x86_64-python-8d32a5c8c4e9c90b0a21-3.11.0b1-8d32a5c |
|-------------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| async_tree_io           | 1.61 sec                                                     | 1.17 sec: 1.38x faster                                                      |
| async_tree_none         | 700 ms                                                       | 516 ms: 1.36x faster                                                        |
| async_tree_memoization  | 827 ms                                                       | 624 ms: 1.32x faster                                                        |
| async_tree_cpu_io_mixed | 946 ms                                                       | 748 ms: 1.26x faster                                                        |
| Geometric mean          | (ref)                                                        | 1.33x faster                                                                |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20220506-pythonperf2-x86_64-python-8d32a5c8c4e9c90b0a21-3.11.0b1-8d32a5c |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| float          | 109 ms                                                       | 74.7 ms: 1.45x faster                                                       |
| nbody          | 134 ms                                                       | 100 ms: 1.34x faster                                                        |
| pidigits       | 270 ms                                                       | 251 ms: 1.07x faster                                                        |
| Geometric mean | (ref)                                                        | 1.28x faster                                                                |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20220506-pythonperf2-x86_64-python-8d32a5c8c4e9c90b0a21-3.11.0b1-8d32a5c |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_compile  | 192 ms                                                       | 153 ms: 1.26x faster                                                        |
| regex_v8       | 27.1 ms                                                      | 22.8 ms: 1.19x faster                                                       |
| regex_dna      | 260 ms                                                       | 232 ms: 1.12x faster                                                        |
| regex_effbot   | 3.10 ms                                                      | 2.97 ms: 1.04x faster                                                       |
| Geometric mean | (ref)                                                        | 1.15x faster                                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20220506-pythonperf2-x86_64-python-8d32a5c8c4e9c90b0a21-3.11.0b1-8d32a5c |
|----------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| pickle_pure_python   | 453 us                                                       | 320 us: 1.41x faster                                                        |
| xml_etree_process    | 76.4 ms                                                      | 56.1 ms: 1.36x faster                                                       |
| unpickle_pure_python | 315 us                                                       | 233 us: 1.35x faster                                                        |
| json_loads           | 30.0 us                                                      | 24.6 us: 1.22x faster                                                       |
| xml_etree_generate   | 93.1 ms                                                      | 80.3 ms: 1.16x faster                                                       |
| pickle_list          | 4.23 us                                                      | 3.81 us: 1.11x faster                                                       |
| json_dumps           | 14.2 ms                                                      | 13.5 ms: 1.05x faster                                                       |
| unpickle             | 13.9 us                                                      | 13.3 us: 1.05x faster                                                       |
| pickle               | 10.1 us                                                      | 9.62 us: 1.05x faster                                                       |
| xml_etree_iterparse  | 110 ms                                                       | 105 ms: 1.05x faster                                                        |
| xml_etree_parse      | 159 ms                                                       | 155 ms: 1.03x faster                                                        |
| pickle_dict          | 30.4 us                                                      | 29.9 us: 1.02x faster                                                       |
| unpickle_list        | 4.45 us                                                      | 4.56 us: 1.03x slower                                                       |
| Geometric mean       | (ref)                                                        | 1.13x faster                                                                |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20220506-pythonperf2-x86_64-python-8d32a5c8c4e9c90b0a21-3.11.0b1-8d32a5c |
|------------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| python_startup         | 11.5 ms                                                      | 10.5 ms: 1.10x faster                                                       |
| python_startup_no_site | 7.35 ms                                                      | 7.68 ms: 1.04x slower                                                       |
| Geometric mean         | (ref)                                                        | 1.02x faster                                                                |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20220506-pythonperf2-x86_64-python-8d32a5c8c4e9c90b0a21-3.11.0b1-8d32a5c |
|-----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| mako            | 14.7 ms                                                      | 10.9 ms: 1.35x faster                                                       |
| genshi_text     | 32.3 ms                                                      | 25.4 ms: 1.27x faster                                                       |
| django_template | 51.8 ms                                                      | 41.3 ms: 1.25x faster                                                       |
| genshi_xml      | 64.1 ms                                                      | 56.7 ms: 1.13x faster                                                       |
| Geometric mean  | (ref)                                                        | 1.25x faster                                                                |

All benchmarks:
===============

| Benchmark               | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20220506-pythonperf2-x86_64-python-8d32a5c8c4e9c90b0a21-3.11.0b1-8d32a5c |
|-------------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| deltablue               | 7.43 ms                                                      | 3.93 ms: 1.89x faster                                                       |
| logging_silent          | 168 ns                                                       | 99.8 ns: 1.68x faster                                                       |
| scimark_sor             | 183 ms                                                       | 110 ms: 1.67x faster                                                        |
| go                      | 258 ms                                                       | 156 ms: 1.65x faster                                                        |
| pyflate                 | 698 ms                                                       | 433 ms: 1.61x faster                                                        |
| raytrace                | 497 ms                                                       | 309 ms: 1.61x faster                                                        |
| scimark_monte_carlo     | 109 ms                                                       | 69.2 ms: 1.58x faster                                                       |
| richards                | 76.3 ms                                                      | 50.1 ms: 1.52x faster                                                       |
| spectral_norm           | 141 ms                                                       | 93.1 ms: 1.52x faster                                                       |
| bench_mp_pool           | 6.82 ms                                                      | 4.56 ms: 1.50x faster                                                       |
| chaos                   | 106 ms                                                       | 72.4 ms: 1.46x faster                                                       |
| float                   | 109 ms                                                       | 74.7 ms: 1.45x faster                                                       |
| scimark_lu              | 165 ms                                                       | 114 ms: 1.44x faster                                                        |
| crypto_pyaes            | 118 ms                                                       | 82.3 ms: 1.43x faster                                                       |
| pickle_pure_python      | 453 us                                                       | 320 us: 1.41x faster                                                        |
| pprint_safe_repr        | 1.04 sec                                                     | 755 ms: 1.38x faster                                                        |
| async_tree_io           | 1.61 sec                                                     | 1.17 sec: 1.38x faster                                                      |
| html5lib                | 94.7 ms                                                      | 69.0 ms: 1.37x faster                                                       |
| pprint_pformat          | 2.15 sec                                                     | 1.57 sec: 1.37x faster                                                      |
| hexiom                  | 9.46 ms                                                      | 6.91 ms: 1.37x faster                                                       |
| xml_etree_process       | 76.4 ms                                                      | 56.1 ms: 1.36x faster                                                       |
| async_tree_none         | 700 ms                                                       | 516 ms: 1.36x faster                                                        |
| unpickle_pure_python    | 315 us                                                       | 233 us: 1.35x faster                                                        |
| mako                    | 14.7 ms                                                      | 10.9 ms: 1.35x faster                                                       |
| deepcopy_memo           | 50.5 us                                                      | 37.6 us: 1.34x faster                                                       |
| nbody                   | 134 ms                                                       | 100 ms: 1.34x faster                                                        |
| async_tree_memoization  | 827 ms                                                       | 624 ms: 1.32x faster                                                        |
| async_generators        | 418 ms                                                       | 318 ms: 1.31x faster                                                        |
| logging_simple          | 9.06 us                                                      | 6.90 us: 1.31x faster                                                       |
| thrift                  | 1.20 ms                                                      | 913 us: 1.31x faster                                                        |
| chameleon               | 9.88 ms                                                      | 7.53 ms: 1.31x faster                                                       |
| pycparser               | 1.65 sec                                                     | 1.26 sec: 1.31x faster                                                      |
| unpack_sequence         | 60.3 ns                                                      | 46.2 ns: 1.30x faster                                                       |
| gunicorn                | 1.20 ms                                                      | 928 us: 1.29x faster                                                        |
| tornado_http            | 157 ms                                                       | 121 ms: 1.29x faster                                                        |
| scimark_sparse_mat_mult | 5.21 ms                                                      | 4.06 ms: 1.28x faster                                                       |
| aiohttp                 | 1.21 ms                                                      | 945 us: 1.28x faster                                                        |
| logging_format          | 9.82 us                                                      | 7.67 us: 1.28x faster                                                       |
| genshi_text             | 32.3 ms                                                      | 25.4 ms: 1.27x faster                                                       |
| async_tree_cpu_io_mixed | 946 ms                                                       | 748 ms: 1.26x faster                                                        |
| regex_compile           | 192 ms                                                       | 153 ms: 1.26x faster                                                        |
| django_template         | 51.8 ms                                                      | 41.3 ms: 1.25x faster                                                       |
| 2to3                    | 349 ms                                                       | 281 ms: 1.24x faster                                                        |
| scimark_fft             | 363 ms                                                       | 294 ms: 1.23x faster                                                        |
| sqlalchemy_declarative  | 189 ms                                                       | 153 ms: 1.23x faster                                                        |
| sqlglot_normalize       | 146 ms                                                       | 119 ms: 1.23x faster                                                        |
| json_loads              | 30.0 us                                                      | 24.6 us: 1.22x faster                                                       |
| docutils                | 3.42 sec                                                     | 2.82 sec: 1.21x faster                                                      |
| regex_v8                | 27.1 ms                                                      | 22.8 ms: 1.19x faster                                                       |
| sqlglot_optimize        | 69.9 ms                                                      | 58.9 ms: 1.19x faster                                                       |
| sqlglot_transpile       | 2.73 ms                                                      | 2.30 ms: 1.19x faster                                                       |
| sqlite_synth            | 2.97 us                                                      | 2.51 us: 1.18x faster                                                       |
| sqlalchemy_imperative   | 23.0 ms                                                      | 19.5 ms: 1.18x faster                                                       |
| dulwich_log             | 80.0 ms                                                      | 68.0 ms: 1.18x faster                                                       |
| deepcopy_reduce         | 4.00 us                                                      | 3.42 us: 1.17x faster                                                       |
| fannkuch                | 488 ms                                                       | 418 ms: 1.17x faster                                                        |
| nqueens                 | 112 ms                                                       | 95.8 ms: 1.17x faster                                                       |
| sqlglot_parse           | 2.27 ms                                                      | 1.95 ms: 1.17x faster                                                       |
| deepcopy                | 459 us                                                       | 394 us: 1.17x faster                                                        |
| flaskblogging           | 4.44 ms                                                      | 3.82 ms: 1.16x faster                                                       |
| xml_etree_generate      | 93.1 ms                                                      | 80.3 ms: 1.16x faster                                                       |
| json                    | 5.91 ms                                                      | 5.14 ms: 1.15x faster                                                       |
| genshi_xml              | 64.1 ms                                                      | 56.7 ms: 1.13x faster                                                       |
| sympy_integrate         | 28.3 ms                                                      | 25.2 ms: 1.13x faster                                                       |
| pathlib                 | 21.2 ms                                                      | 18.8 ms: 1.13x faster                                                       |
| regex_dna               | 260 ms                                                       | 232 ms: 1.12x faster                                                        |
| dask                    | 469 ms                                                       | 418 ms: 1.12x faster                                                        |
| pylint                  | 564 ms                                                       | 505 ms: 1.12x faster                                                        |
| bench_thread_pool       | 1.13 ms                                                      | 1.02 ms: 1.11x faster                                                       |
| pickle_list             | 4.23 us                                                      | 3.81 us: 1.11x faster                                                       |
| sympy_expand            | 599 ms                                                       | 540 ms: 1.11x faster                                                        |
| coroutines              | 30.9 ms                                                      | 28.0 ms: 1.10x faster                                                       |
| python_startup          | 11.5 ms                                                      | 10.5 ms: 1.10x faster                                                       |
| sympy_str               | 359 ms                                                       | 329 ms: 1.09x faster                                                        |
| create_gc_cycles        | 1.79 ms                                                      | 1.64 ms: 1.09x faster                                                       |
| sympy_sum               | 194 ms                                                       | 178 ms: 1.09x faster                                                        |
| pidigits                | 270 ms                                                       | 251 ms: 1.07x faster                                                        |
| mypy2                   | 467 ms                                                       | 438 ms: 1.07x faster                                                        |
| mdp                     | 2.94 sec                                                     | 2.78 sec: 1.06x faster                                                      |
| json_dumps              | 14.2 ms                                                      | 13.5 ms: 1.05x faster                                                       |
| unpickle                | 13.9 us                                                      | 13.3 us: 1.05x faster                                                       |
| asyncio_tcp             | 785 ms                                                       | 749 ms: 1.05x faster                                                        |
| pickle                  | 10.1 us                                                      | 9.62 us: 1.05x faster                                                       |
| meteor_contest          | 138 ms                                                       | 131 ms: 1.05x faster                                                        |
| xml_etree_iterparse     | 110 ms                                                       | 105 ms: 1.05x faster                                                        |
| regex_effbot            | 3.10 ms                                                      | 2.97 ms: 1.04x faster                                                       |
| generators              | 57.7 ms                                                      | 55.5 ms: 1.04x faster                                                       |
| telco                   | 7.21 ms                                                      | 6.99 ms: 1.03x faster                                                       |
| xml_etree_parse         | 159 ms                                                       | 155 ms: 1.03x faster                                                        |
| pickle_dict             | 30.4 us                                                      | 29.9 us: 1.02x faster                                                       |
| unpickle_list           | 4.45 us                                                      | 4.56 us: 1.03x slower                                                       |
| comprehensions          | 27.0 us                                                      | 28.2 us: 1.04x slower                                                       |
| python_startup_no_site  | 7.35 ms                                                      | 7.68 ms: 1.04x slower                                                       |
| gc_traversal            | 3.63 ms                                                      | 3.85 ms: 1.06x slower                                                       |
| Geometric mean          | (ref)                                                        | 1.23x faster                                                                |
Ignored benchmarks (6) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120.json: asyncio_tcp_ssl, asyncio_websockets, coverage, richards_super, tomli_loads, typing_runtime_protocols


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.20x
- 95% likely to have a speedup of 1.19x
- 99% likely to have a speedup of 1.17x
