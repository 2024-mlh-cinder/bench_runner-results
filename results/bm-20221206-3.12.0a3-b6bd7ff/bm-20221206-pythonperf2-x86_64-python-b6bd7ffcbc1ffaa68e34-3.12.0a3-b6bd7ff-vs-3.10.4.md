
# Results vs. 3.10.4

- fork: python
- ref: b6bd7ffcbc1ffaa68e34
- machine: linux-x86_64
- commit hash: b6bd7ff
- commit date: 2022-12-06
- overall geometric mean: 1.24x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.19x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20221206-pythonperf2-x86_64-python-b6bd7ffcbc1ffaa68e34-3.12.0a3-b6bd7ff |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| 2to3           | 349 ms                                                       | 281 ms: 1.24x faster                                                        |
| chameleon      | 9.88 ms                                                      | 7.51 ms: 1.32x faster                                                       |
| docutils       | 3.42 sec                                                     | 2.76 sec: 1.24x faster                                                      |
| html5lib       | 94.7 ms                                                      | 66.2 ms: 1.43x faster                                                       |
| Geometric mean | (ref)                                                        | 1.31x faster                                                                |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20221206-pythonperf2-x86_64-python-b6bd7ffcbc1ffaa68e34-3.12.0a3-b6bd7ff |
|-------------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| async_tree_io           | 1.61 sec                                                     | 1.18 sec: 1.37x faster                                                      |
| async_tree_memoization  | 827 ms                                                       | 623 ms: 1.33x faster                                                        |
| async_tree_none         | 700 ms                                                       | 531 ms: 1.32x faster                                                        |
| async_tree_cpu_io_mixed | 946 ms                                                       | 767 ms: 1.23x faster                                                        |
| Geometric mean          | (ref)                                                        | 1.31x faster                                                                |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20221206-pythonperf2-x86_64-python-b6bd7ffcbc1ffaa68e34-3.12.0a3-b6bd7ff |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| float          | 109 ms                                                       | 73.2 ms: 1.48x faster                                                       |
| nbody          | 134 ms                                                       | 94.3 ms: 1.42x faster                                                       |
| pidigits       | 270 ms                                                       | 250 ms: 1.08x faster                                                        |
| Geometric mean | (ref)                                                        | 1.32x faster                                                                |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20221206-pythonperf2-x86_64-python-b6bd7ffcbc1ffaa68e34-3.12.0a3-b6bd7ff |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_compile  | 192 ms                                                       | 150 ms: 1.28x faster                                                        |
| regex_v8       | 27.1 ms                                                      | 22.3 ms: 1.21x faster                                                       |
| regex_dna      | 260 ms                                                       | 233 ms: 1.12x faster                                                        |
| regex_effbot   | 3.10 ms                                                      | 3.44 ms: 1.11x slower                                                       |
| Geometric mean | (ref)                                                        | 1.12x faster                                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20221206-pythonperf2-x86_64-python-b6bd7ffcbc1ffaa68e34-3.12.0a3-b6bd7ff |
|----------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| unpickle_pure_python | 315 us                                                       | 212 us: 1.49x faster                                                        |
| pickle_pure_python   | 453 us                                                       | 316 us: 1.43x faster                                                        |
| json_dumps           | 14.2 ms                                                      | 10.3 ms: 1.38x faster                                                       |
| xml_etree_process    | 76.4 ms                                                      | 55.6 ms: 1.37x faster                                                       |
| json_loads           | 30.0 us                                                      | 24.2 us: 1.24x faster                                                       |
| xml_etree_generate   | 93.1 ms                                                      | 78.9 ms: 1.18x faster                                                       |
| xml_etree_parse      | 159 ms                                                       | 141 ms: 1.13x faster                                                        |
| pickle_list          | 4.23 us                                                      | 3.90 us: 1.09x faster                                                       |
| unpickle             | 13.9 us                                                      | 13.1 us: 1.06x faster                                                       |
| pickle               | 10.1 us                                                      | 9.84 us: 1.02x faster                                                       |
| xml_etree_iterparse  | 110 ms                                                       | 108 ms: 1.02x faster                                                        |
| pickle_dict          | 30.4 us                                                      | 31.9 us: 1.05x slower                                                       |
| Geometric mean       | (ref)                                                        | 1.17x faster                                                                |

Benchmark hidden because not significant (1): unpickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20221206-pythonperf2-x86_64-python-b6bd7ffcbc1ffaa68e34-3.12.0a3-b6bd7ff |
|------------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| python_startup         | 11.5 ms                                                      | 10.8 ms: 1.07x faster                                                       |
| python_startup_no_site | 7.35 ms                                                      | 7.86 ms: 1.07x slower                                                       |
| Geometric mean         | (ref)                                                        | 1.00x faster                                                                |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20221206-pythonperf2-x86_64-python-b6bd7ffcbc1ffaa68e34-3.12.0a3-b6bd7ff |
|-----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| mako            | 14.7 ms                                                      | 10.4 ms: 1.42x faster                                                       |
| django_template | 51.8 ms                                                      | 39.6 ms: 1.31x faster                                                       |
| genshi_text     | 32.3 ms                                                      | 25.8 ms: 1.25x faster                                                       |
| genshi_xml      | 64.1 ms                                                      | 53.5 ms: 1.20x faster                                                       |
| Geometric mean  | (ref)                                                        | 1.29x faster                                                                |

All benchmarks:
===============

| Benchmark               | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20221206-pythonperf2-x86_64-python-b6bd7ffcbc1ffaa68e34-3.12.0a3-b6bd7ff |
|-------------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| deltablue               | 7.43 ms                                                      | 3.67 ms: 2.02x faster                                                       |
| logging_silent          | 168 ns                                                       | 99.7 ns: 1.68x faster                                                       |
| scimark_sor             | 183 ms                                                       | 109 ms: 1.67x faster                                                        |
| richards                | 76.3 ms                                                      | 46.1 ms: 1.65x faster                                                       |
| scimark_lu              | 165 ms                                                       | 100 ms: 1.64x faster                                                        |
| go                      | 258 ms                                                       | 159 ms: 1.62x faster                                                        |
| pyflate                 | 698 ms                                                       | 440 ms: 1.59x faster                                                        |
| bench_mp_pool           | 6.82 ms                                                      | 4.46 ms: 1.53x faster                                                       |
| raytrace                | 497 ms                                                       | 327 ms: 1.52x faster                                                        |
| scimark_monte_carlo     | 109 ms                                                       | 72.7 ms: 1.50x faster                                                       |
| sqlglot_parse           | 2.27 ms                                                      | 1.52 ms: 1.50x faster                                                       |
| unpickle_pure_python    | 315 us                                                       | 212 us: 1.49x faster                                                        |
| float                   | 109 ms                                                       | 73.2 ms: 1.48x faster                                                       |
| spectral_norm           | 141 ms                                                       | 96.2 ms: 1.47x faster                                                       |
| sqlglot_transpile       | 2.73 ms                                                      | 1.87 ms: 1.46x faster                                                       |
| crypto_pyaes            | 118 ms                                                       | 81.8 ms: 1.44x faster                                                       |
| pickle_pure_python      | 453 us                                                       | 316 us: 1.43x faster                                                        |
| html5lib                | 94.7 ms                                                      | 66.2 ms: 1.43x faster                                                       |
| mako                    | 14.7 ms                                                      | 10.4 ms: 1.42x faster                                                       |
| nbody                   | 134 ms                                                       | 94.3 ms: 1.42x faster                                                       |
| hexiom                  | 9.46 ms                                                      | 6.73 ms: 1.40x faster                                                       |
| scimark_sparse_mat_mult | 5.21 ms                                                      | 3.73 ms: 1.40x faster                                                       |
| deepcopy_memo           | 50.5 us                                                      | 36.2 us: 1.39x faster                                                       |
| pprint_pformat          | 2.15 sec                                                     | 1.56 sec: 1.38x faster                                                      |
| json_dumps              | 14.2 ms                                                      | 10.3 ms: 1.38x faster                                                       |
| xml_etree_process       | 76.4 ms                                                      | 55.6 ms: 1.37x faster                                                       |
| pprint_safe_repr        | 1.04 sec                                                     | 758 ms: 1.37x faster                                                        |
| async_tree_io           | 1.61 sec                                                     | 1.18 sec: 1.37x faster                                                      |
| chaos                   | 106 ms                                                       | 78.3 ms: 1.35x faster                                                       |
| thrift                  | 1.20 ms                                                      | 894 us: 1.34x faster                                                        |
| async_tree_memoization  | 827 ms                                                       | 623 ms: 1.33x faster                                                        |
| unpack_sequence         | 60.3 ns                                                      | 45.5 ns: 1.33x faster                                                       |
| async_tree_none         | 700 ms                                                       | 531 ms: 1.32x faster                                                        |
| chameleon               | 9.88 ms                                                      | 7.51 ms: 1.32x faster                                                       |
| pycparser               | 1.65 sec                                                     | 1.26 sec: 1.31x faster                                                      |
| django_template         | 51.8 ms                                                      | 39.6 ms: 1.31x faster                                                       |
| logging_simple          | 9.06 us                                                      | 7.03 us: 1.29x faster                                                       |
| scimark_fft             | 363 ms                                                       | 282 ms: 1.29x faster                                                        |
| regex_compile           | 192 ms                                                       | 150 ms: 1.28x faster                                                        |
| logging_format          | 9.82 us                                                      | 7.72 us: 1.27x faster                                                       |
| genshi_text             | 32.3 ms                                                      | 25.8 ms: 1.25x faster                                                       |
| async_generators        | 418 ms                                                       | 335 ms: 1.25x faster                                                        |
| mypy2                   | 467 ms                                                       | 375 ms: 1.25x faster                                                        |
| 2to3                    | 349 ms                                                       | 281 ms: 1.24x faster                                                        |
| json_loads              | 30.0 us                                                      | 24.2 us: 1.24x faster                                                       |
| docutils                | 3.42 sec                                                     | 2.76 sec: 1.24x faster                                                      |
| async_tree_cpu_io_mixed | 946 ms                                                       | 767 ms: 1.23x faster                                                        |
| fannkuch                | 488 ms                                                       | 398 ms: 1.23x faster                                                        |
| regex_v8                | 27.1 ms                                                      | 22.3 ms: 1.21x faster                                                       |
| deepcopy                | 459 us                                                       | 380 us: 1.21x faster                                                        |
| sqlglot_normalize       | 146 ms                                                       | 121 ms: 1.21x faster                                                        |
| dulwich_log             | 80.0 ms                                                      | 66.7 ms: 1.20x faster                                                       |
| genshi_xml              | 64.1 ms                                                      | 53.5 ms: 1.20x faster                                                       |
| sqlglot_optimize        | 69.9 ms                                                      | 58.5 ms: 1.19x faster                                                       |
| deepcopy_reduce         | 4.00 us                                                      | 3.37 us: 1.19x faster                                                       |
| xml_etree_generate      | 93.1 ms                                                      | 78.9 ms: 1.18x faster                                                       |
| json                    | 5.91 ms                                                      | 5.11 ms: 1.16x faster                                                       |
| dask                    | 469 ms                                                       | 409 ms: 1.15x faster                                                        |
| bench_thread_pool       | 1.13 ms                                                      | 994 us: 1.14x faster                                                        |
| sqlite_synth            | 2.97 us                                                      | 2.60 us: 1.14x faster                                                       |
| xml_etree_parse         | 159 ms                                                       | 141 ms: 1.13x faster                                                        |
| create_gc_cycles        | 1.79 ms                                                      | 1.60 ms: 1.12x faster                                                       |
| regex_dna               | 260 ms                                                       | 233 ms: 1.12x faster                                                        |
| pathlib                 | 21.2 ms                                                      | 19.0 ms: 1.11x faster                                                       |
| sympy_expand            | 599 ms                                                       | 539 ms: 1.11x faster                                                        |
| sympy_integrate         | 28.3 ms                                                      | 25.6 ms: 1.11x faster                                                       |
| coroutines              | 30.9 ms                                                      | 28.0 ms: 1.10x faster                                                       |
| nqueens                 | 112 ms                                                       | 102 ms: 1.10x faster                                                        |
| telco                   | 7.21 ms                                                      | 6.60 ms: 1.09x faster                                                       |
| pickle_list             | 4.23 us                                                      | 3.90 us: 1.09x faster                                                       |
| sympy_str               | 359 ms                                                       | 331 ms: 1.08x faster                                                        |
| pidigits                | 270 ms                                                       | 250 ms: 1.08x faster                                                        |
| mdp                     | 2.94 sec                                                     | 2.73 sec: 1.08x faster                                                      |
| python_startup          | 11.5 ms                                                      | 10.8 ms: 1.07x faster                                                       |
| meteor_contest          | 138 ms                                                       | 129 ms: 1.07x faster                                                        |
| unpickle                | 13.9 us                                                      | 13.1 us: 1.06x faster                                                       |
| asyncio_tcp             | 785 ms                                                       | 743 ms: 1.06x faster                                                        |
| sympy_sum               | 194 ms                                                       | 183 ms: 1.06x faster                                                        |
| pickle                  | 10.1 us                                                      | 9.84 us: 1.02x faster                                                       |
| xml_etree_iterparse     | 110 ms                                                       | 108 ms: 1.02x faster                                                        |
| comprehensions          | 27.0 us                                                      | 27.3 us: 1.01x slower                                                       |
| gc_traversal            | 3.63 ms                                                      | 3.79 ms: 1.04x slower                                                       |
| pickle_dict             | 30.4 us                                                      | 31.9 us: 1.05x slower                                                       |
| generators              | 57.7 ms                                                      | 60.8 ms: 1.06x slower                                                       |
| python_startup_no_site  | 7.35 ms                                                      | 7.86 ms: 1.07x slower                                                       |
| regex_effbot            | 3.10 ms                                                      | 3.44 ms: 1.11x slower                                                       |
| coverage                | 65.9 ms                                                      | 85.0 ms: 1.29x slower                                                       |
| Geometric mean          | (ref)                                                        | 1.24x faster                                                                |

Benchmark hidden because not significant (1): unpickle_list
Ignored benchmarks (12) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, asyncio_tcp_ssl, asyncio_websockets, flaskblogging, gunicorn, pylint, richards_super, sqlalchemy_declarative, sqlalchemy_imperative, tomli_loads, tornado_http, typing_runtime_protocols


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.22x
- 95% likely to have a speedup of 1.21x
- 99% likely to have a speedup of 1.19x
