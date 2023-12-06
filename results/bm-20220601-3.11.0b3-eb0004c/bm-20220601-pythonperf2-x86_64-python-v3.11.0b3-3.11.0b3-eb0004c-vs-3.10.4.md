
# Results vs. 3.10.4

- fork: python
- ref: v3.11.0b3
- machine: linux-x86_64
- commit hash: eb0004c
- commit date: 2022-06-01
- overall geometric mean: 1.22x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.16x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20220601-pythonperf2-x86_64-python-v3.11.0b3-3.11.0b3-eb0004c |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| 2to3           | 349 ms                                                       | 284 ms: 1.23x faster                                             |
| chameleon      | 9.88 ms                                                      | 7.60 ms: 1.30x faster                                            |
| docutils       | 3.42 sec                                                     | 2.83 sec: 1.21x faster                                           |
| html5lib       | 94.7 ms                                                      | 71.0 ms: 1.33x faster                                            |
| tornado_http   | 157 ms                                                       | 119 ms: 1.32x faster                                             |
| Geometric mean | (ref)                                                        | 1.28x faster                                                     |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20220601-pythonperf2-x86_64-python-v3.11.0b3-3.11.0b3-eb0004c |
|-------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| async_tree_io           | 1.61 sec                                                     | 1.17 sec: 1.38x faster                                           |
| async_tree_none         | 700 ms                                                       | 513 ms: 1.36x faster                                             |
| async_tree_memoization  | 827 ms                                                       | 617 ms: 1.34x faster                                             |
| async_tree_cpu_io_mixed | 946 ms                                                       | 810 ms: 1.17x faster                                             |
| Geometric mean          | (ref)                                                        | 1.31x faster                                                     |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20220601-pythonperf2-x86_64-python-v3.11.0b3-3.11.0b3-eb0004c |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| float          | 109 ms                                                       | 73.9 ms: 1.47x faster                                            |
| nbody          | 134 ms                                                       | 93.0 ms: 1.44x faster                                            |
| pidigits       | 270 ms                                                       | 252 ms: 1.07x faster                                             |
| Geometric mean | (ref)                                                        | 1.32x faster                                                     |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20220601-pythonperf2-x86_64-python-v3.11.0b3-3.11.0b3-eb0004c |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| regex_compile  | 192 ms                                                       | 156 ms: 1.23x faster                                             |
| regex_dna      | 260 ms                                                       | 219 ms: 1.19x faster                                             |
| regex_v8       | 27.1 ms                                                      | 24.3 ms: 1.11x faster                                            |
| regex_effbot   | 3.10 ms                                                      | 3.05 ms: 1.02x faster                                            |
| Geometric mean | (ref)                                                        | 1.13x faster                                                     |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20220601-pythonperf2-x86_64-python-v3.11.0b3-3.11.0b3-eb0004c |
|----------------------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| pickle_pure_python   | 453 us                                                       | 319 us: 1.42x faster                                             |
| xml_etree_process    | 76.4 ms                                                      | 55.9 ms: 1.37x faster                                            |
| unpickle_pure_python | 315 us                                                       | 238 us: 1.32x faster                                             |
| json_loads           | 30.0 us                                                      | 25.2 us: 1.19x faster                                            |
| xml_etree_generate   | 93.1 ms                                                      | 80.2 ms: 1.16x faster                                            |
| pickle_list          | 4.23 us                                                      | 3.92 us: 1.08x faster                                            |
| xml_etree_iterparse  | 110 ms                                                       | 103 ms: 1.06x faster                                             |
| json_dumps           | 14.2 ms                                                      | 13.5 ms: 1.06x faster                                            |
| unpickle             | 13.9 us                                                      | 13.2 us: 1.06x faster                                            |
| xml_etree_parse      | 159 ms                                                       | 153 ms: 1.04x faster                                             |
| pickle               | 10.1 us                                                      | 9.80 us: 1.03x faster                                            |
| pickle_dict          | 30.4 us                                                      | 31.3 us: 1.03x slower                                            |
| unpickle_list        | 4.45 us                                                      | 4.58 us: 1.03x slower                                            |
| Geometric mean       | (ref)                                                        | 1.12x faster                                                     |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20220601-pythonperf2-x86_64-python-v3.11.0b3-3.11.0b3-eb0004c |
|------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| python_startup         | 11.5 ms                                                      | 10.7 ms: 1.08x faster                                            |
| python_startup_no_site | 7.35 ms                                                      | 7.70 ms: 1.05x slower                                            |
| Geometric mean         | (ref)                                                        | 1.02x faster                                                     |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20220601-pythonperf2-x86_64-python-v3.11.0b3-3.11.0b3-eb0004c |
|-----------------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| mako            | 14.7 ms                                                      | 10.9 ms: 1.35x faster                                            |
| django_template | 51.8 ms                                                      | 41.4 ms: 1.25x faster                                            |
| genshi_text     | 32.3 ms                                                      | 26.3 ms: 1.23x faster                                            |
| genshi_xml      | 64.1 ms                                                      | 60.1 ms: 1.07x faster                                            |
| Geometric mean  | (ref)                                                        | 1.22x faster                                                     |

All benchmarks:
===============

| Benchmark               | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20220601-pythonperf2-x86_64-python-v3.11.0b3-3.11.0b3-eb0004c |
|-------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| deltablue               | 7.43 ms                                                      | 4.20 ms: 1.77x faster                                            |
| logging_silent          | 168 ns                                                       | 99.3 ns: 1.69x faster                                            |
| scimark_sor             | 183 ms                                                       | 112 ms: 1.64x faster                                             |
| raytrace                | 497 ms                                                       | 304 ms: 1.64x faster                                             |
| pyflate                 | 698 ms                                                       | 441 ms: 1.58x faster                                             |
| scimark_monte_carlo     | 109 ms                                                       | 69.5 ms: 1.57x faster                                            |
| go                      | 258 ms                                                       | 166 ms: 1.56x faster                                             |
| richards                | 76.3 ms                                                      | 49.2 ms: 1.55x faster                                            |
| bench_mp_pool           | 6.82 ms                                                      | 4.52 ms: 1.51x faster                                            |
| scimark_lu              | 165 ms                                                       | 110 ms: 1.49x faster                                             |
| float                   | 109 ms                                                       | 73.9 ms: 1.47x faster                                            |
| spectral_norm           | 141 ms                                                       | 96.8 ms: 1.46x faster                                            |
| nbody                   | 134 ms                                                       | 93.0 ms: 1.44x faster                                            |
| chaos                   | 106 ms                                                       | 73.6 ms: 1.44x faster                                            |
| pickle_pure_python      | 453 us                                                       | 319 us: 1.42x faster                                             |
| crypto_pyaes            | 118 ms                                                       | 84.5 ms: 1.40x faster                                            |
| async_tree_io           | 1.61 sec                                                     | 1.17 sec: 1.38x faster                                           |
| xml_etree_process       | 76.4 ms                                                      | 55.9 ms: 1.37x faster                                            |
| async_tree_none         | 700 ms                                                       | 513 ms: 1.36x faster                                             |
| hexiom                  | 9.46 ms                                                      | 7.00 ms: 1.35x faster                                            |
| mako                    | 14.7 ms                                                      | 10.9 ms: 1.35x faster                                            |
| pprint_safe_repr        | 1.04 sec                                                     | 774 ms: 1.34x faster                                             |
| deepcopy_memo           | 50.5 us                                                      | 37.7 us: 1.34x faster                                            |
| async_tree_memoization  | 827 ms                                                       | 617 ms: 1.34x faster                                             |
| html5lib                | 94.7 ms                                                      | 71.0 ms: 1.33x faster                                            |
| pprint_pformat          | 2.15 sec                                                     | 1.61 sec: 1.33x faster                                           |
| unpack_sequence         | 60.3 ns                                                      | 45.4 ns: 1.33x faster                                            |
| unpickle_pure_python    | 315 us                                                       | 238 us: 1.32x faster                                             |
| tornado_http            | 157 ms                                                       | 119 ms: 1.32x faster                                             |
| thrift                  | 1.20 ms                                                      | 909 us: 1.32x faster                                             |
| async_generators        | 418 ms                                                       | 318 ms: 1.32x faster                                             |
| chameleon               | 9.88 ms                                                      | 7.60 ms: 1.30x faster                                            |
| scimark_sparse_mat_mult | 5.21 ms                                                      | 4.03 ms: 1.29x faster                                            |
| gunicorn                | 1.20 ms                                                      | 931 us: 1.29x faster                                             |
| scimark_fft             | 363 ms                                                       | 286 ms: 1.27x faster                                             |
| logging_simple          | 9.06 us                                                      | 7.16 us: 1.27x faster                                            |
| aiohttp                 | 1.21 ms                                                      | 958 us: 1.26x faster                                             |
| pycparser               | 1.65 sec                                                     | 1.31 sec: 1.26x faster                                           |
| django_template         | 51.8 ms                                                      | 41.4 ms: 1.25x faster                                            |
| regex_compile           | 192 ms                                                       | 156 ms: 1.23x faster                                             |
| logging_format          | 9.82 us                                                      | 7.95 us: 1.23x faster                                            |
| 2to3                    | 349 ms                                                       | 284 ms: 1.23x faster                                             |
| sqlalchemy_declarative  | 189 ms                                                       | 154 ms: 1.23x faster                                             |
| genshi_text             | 32.3 ms                                                      | 26.3 ms: 1.23x faster                                            |
| docutils                | 3.42 sec                                                     | 2.83 sec: 1.21x faster                                           |
| json_loads              | 30.0 us                                                      | 25.2 us: 1.19x faster                                            |
| regex_dna               | 260 ms                                                       | 219 ms: 1.19x faster                                             |
| sqlglot_normalize       | 146 ms                                                       | 123 ms: 1.19x faster                                             |
| sqlite_synth            | 2.97 us                                                      | 2.51 us: 1.18x faster                                            |
| sqlglot_optimize        | 69.9 ms                                                      | 59.4 ms: 1.18x faster                                            |
| sqlglot_transpile       | 2.73 ms                                                      | 2.32 ms: 1.18x faster                                            |
| deepcopy                | 459 us                                                       | 390 us: 1.18x faster                                             |
| sqlalchemy_imperative   | 23.0 ms                                                      | 19.6 ms: 1.18x faster                                            |
| dulwich_log             | 80.0 ms                                                      | 68.4 ms: 1.17x faster                                            |
| async_tree_cpu_io_mixed | 946 ms                                                       | 810 ms: 1.17x faster                                             |
| flaskblogging           | 4.44 ms                                                      | 3.82 ms: 1.16x faster                                            |
| xml_etree_generate      | 93.1 ms                                                      | 80.2 ms: 1.16x faster                                            |
| sqlglot_parse           | 2.27 ms                                                      | 1.97 ms: 1.15x faster                                            |
| deepcopy_reduce         | 4.00 us                                                      | 3.48 us: 1.15x faster                                            |
| nqueens                 | 112 ms                                                       | 97.6 ms: 1.15x faster                                            |
| json                    | 5.91 ms                                                      | 5.20 ms: 1.14x faster                                            |
| dask                    | 469 ms                                                       | 414 ms: 1.13x faster                                             |
| sympy_expand            | 599 ms                                                       | 531 ms: 1.13x faster                                             |
| sympy_integrate         | 28.3 ms                                                      | 25.2 ms: 1.12x faster                                            |
| bench_thread_pool       | 1.13 ms                                                      | 1.01 ms: 1.12x faster                                            |
| regex_v8                | 27.1 ms                                                      | 24.3 ms: 1.11x faster                                            |
| coroutines              | 30.9 ms                                                      | 27.9 ms: 1.11x faster                                            |
| pathlib                 | 21.2 ms                                                      | 19.2 ms: 1.10x faster                                            |
| sympy_str               | 359 ms                                                       | 327 ms: 1.10x faster                                             |
| pylint                  | 564 ms                                                       | 515 ms: 1.09x faster                                             |
| sympy_sum               | 194 ms                                                       | 177 ms: 1.09x faster                                             |
| python_startup          | 11.5 ms                                                      | 10.7 ms: 1.08x faster                                            |
| pickle_list             | 4.23 us                                                      | 3.92 us: 1.08x faster                                            |
| pidigits                | 270 ms                                                       | 252 ms: 1.07x faster                                             |
| telco                   | 7.21 ms                                                      | 6.75 ms: 1.07x faster                                            |
| genshi_xml              | 64.1 ms                                                      | 60.1 ms: 1.07x faster                                            |
| mypy2                   | 467 ms                                                       | 438 ms: 1.07x faster                                             |
| create_gc_cycles        | 1.79 ms                                                      | 1.68 ms: 1.07x faster                                            |
| xml_etree_iterparse     | 110 ms                                                       | 103 ms: 1.06x faster                                             |
| json_dumps              | 14.2 ms                                                      | 13.5 ms: 1.06x faster                                            |
| unpickle                | 13.9 us                                                      | 13.2 us: 1.06x faster                                            |
| meteor_contest          | 138 ms                                                       | 131 ms: 1.05x faster                                             |
| asyncio_tcp             | 785 ms                                                       | 751 ms: 1.05x faster                                             |
| mdp                     | 2.94 sec                                                     | 2.81 sec: 1.04x faster                                           |
| xml_etree_parse         | 159 ms                                                       | 153 ms: 1.04x faster                                             |
| generators              | 57.7 ms                                                      | 56.0 ms: 1.03x faster                                            |
| pickle                  | 10.1 us                                                      | 9.80 us: 1.03x faster                                            |
| regex_effbot            | 3.10 ms                                                      | 3.05 ms: 1.02x faster                                            |
| fannkuch                | 488 ms                                                       | 496 ms: 1.02x slower                                             |
| pickle_dict             | 30.4 us                                                      | 31.3 us: 1.03x slower                                            |
| unpickle_list           | 4.45 us                                                      | 4.58 us: 1.03x slower                                            |
| comprehensions          | 27.0 us                                                      | 28.3 us: 1.05x slower                                            |
| python_startup_no_site  | 7.35 ms                                                      | 7.70 ms: 1.05x slower                                            |
| gc_traversal            | 3.63 ms                                                      | 4.03 ms: 1.11x slower                                            |
| Geometric mean          | (ref)                                                        | 1.22x faster                                                     |
Ignored benchmarks (6) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120.json: asyncio_tcp_ssl, asyncio_websockets, coverage, richards_super, tomli_loads, typing_runtime_protocols


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.18x
- 95% likely to have a speedup of 1.17x
- 99% likely to have a speedup of 1.16x
