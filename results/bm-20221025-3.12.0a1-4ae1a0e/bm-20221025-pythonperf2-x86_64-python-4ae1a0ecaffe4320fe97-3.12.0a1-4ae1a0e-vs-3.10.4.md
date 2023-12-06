
# Results vs. 3.10.4

- fork: python
- ref: 4ae1a0ecaffe4320fe97
- machine: linux-x86_64
- commit hash: 4ae1a0e
- commit date: 2022-10-25
- overall geometric mean: 1.26x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.20x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20221025-pythonperf2-x86_64-python-4ae1a0ecaffe4320fe97-3.12.0a1-4ae1a0e |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| 2to3           | 349 ms                                                       | 278 ms: 1.26x faster                                                        |
| chameleon      | 9.88 ms                                                      | 7.62 ms: 1.30x faster                                                       |
| docutils       | 3.42 sec                                                     | 2.79 sec: 1.22x faster                                                      |
| html5lib       | 94.7 ms                                                      | 66.2 ms: 1.43x faster                                                       |
| tornado_http   | 157 ms                                                       | 114 ms: 1.37x faster                                                        |
| Geometric mean | (ref)                                                        | 1.31x faster                                                                |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20221025-pythonperf2-x86_64-python-4ae1a0ecaffe4320fe97-3.12.0a1-4ae1a0e |
|-------------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| async_tree_io           | 1.61 sec                                                     | 1.16 sec: 1.39x faster                                                      |
| async_tree_none         | 700 ms                                                       | 516 ms: 1.36x faster                                                        |
| async_tree_memoization  | 827 ms                                                       | 618 ms: 1.34x faster                                                        |
| async_tree_cpu_io_mixed | 946 ms                                                       | 756 ms: 1.25x faster                                                        |
| Geometric mean          | (ref)                                                        | 1.33x faster                                                                |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20221025-pythonperf2-x86_64-python-4ae1a0ecaffe4320fe97-3.12.0a1-4ae1a0e |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| float          | 109 ms                                                       | 73.2 ms: 1.48x faster                                                       |
| nbody          | 134 ms                                                       | 98.1 ms: 1.37x faster                                                       |
| pidigits       | 270 ms                                                       | 251 ms: 1.08x faster                                                        |
| Geometric mean | (ref)                                                        | 1.30x faster                                                                |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20221025-pythonperf2-x86_64-python-4ae1a0ecaffe4320fe97-3.12.0a1-4ae1a0e |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_compile  | 192 ms                                                       | 146 ms: 1.32x faster                                                        |
| regex_v8       | 27.1 ms                                                      | 22.9 ms: 1.18x faster                                                       |
| regex_dna      | 260 ms                                                       | 232 ms: 1.12x faster                                                        |
| regex_effbot   | 3.10 ms                                                      | 3.34 ms: 1.08x slower                                                       |
| Geometric mean | (ref)                                                        | 1.13x faster                                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20221025-pythonperf2-x86_64-python-4ae1a0ecaffe4320fe97-3.12.0a1-4ae1a0e |
|----------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| unpickle_pure_python | 315 us                                                       | 208 us: 1.51x faster                                                        |
| pickle_pure_python   | 453 us                                                       | 313 us: 1.45x faster                                                        |
| xml_etree_process    | 76.4 ms                                                      | 54.1 ms: 1.41x faster                                                       |
| json_dumps           | 14.2 ms                                                      | 10.4 ms: 1.37x faster                                                       |
| json_loads           | 30.0 us                                                      | 24.3 us: 1.24x faster                                                       |
| xml_etree_generate   | 93.1 ms                                                      | 77.6 ms: 1.20x faster                                                       |
| xml_etree_parse      | 159 ms                                                       | 138 ms: 1.15x faster                                                        |
| pickle_list          | 4.23 us                                                      | 3.84 us: 1.10x faster                                                       |
| xml_etree_iterparse  | 110 ms                                                       | 103 ms: 1.07x faster                                                        |
| unpickle             | 13.9 us                                                      | 13.3 us: 1.05x faster                                                       |
| pickle               | 10.1 us                                                      | 10.1 us: 1.00x slower                                                       |
| pickle_dict          | 30.4 us                                                      | 31.9 us: 1.05x slower                                                       |
| Geometric mean       | (ref)                                                        | 1.18x faster                                                                |

Benchmark hidden because not significant (1): unpickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20221025-pythonperf2-x86_64-python-4ae1a0ecaffe4320fe97-3.12.0a1-4ae1a0e |
|------------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| python_startup         | 11.5 ms                                                      | 10.6 ms: 1.09x faster                                                       |
| python_startup_no_site | 7.35 ms                                                      | 7.62 ms: 1.04x slower                                                       |
| Geometric mean         | (ref)                                                        | 1.03x faster                                                                |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20221025-pythonperf2-x86_64-python-4ae1a0ecaffe4320fe97-3.12.0a1-4ae1a0e |
|-----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| mako            | 14.7 ms                                                      | 10.4 ms: 1.41x faster                                                       |
| genshi_text     | 32.3 ms                                                      | 24.7 ms: 1.31x faster                                                       |
| django_template | 51.8 ms                                                      | 40.6 ms: 1.27x faster                                                       |
| genshi_xml      | 64.1 ms                                                      | 55.5 ms: 1.16x faster                                                       |
| Geometric mean  | (ref)                                                        | 1.28x faster                                                                |

All benchmarks:
===============

| Benchmark               | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20221025-pythonperf2-x86_64-python-4ae1a0ecaffe4320fe97-3.12.0a1-4ae1a0e |
|-------------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| deltablue               | 7.43 ms                                                      | 3.65 ms: 2.03x faster                                                       |
| logging_silent          | 168 ns                                                       | 95.5 ns: 1.76x faster                                                       |
| scimark_sor             | 183 ms                                                       | 108 ms: 1.69x faster                                                        |
| go                      | 258 ms                                                       | 155 ms: 1.67x faster                                                        |
| raytrace                | 497 ms                                                       | 298 ms: 1.67x faster                                                        |
| pyflate                 | 698 ms                                                       | 431 ms: 1.62x faster                                                        |
| scimark_monte_carlo     | 109 ms                                                       | 67.8 ms: 1.61x faster                                                       |
| richards                | 76.3 ms                                                      | 47.6 ms: 1.60x faster                                                       |
| unpickle_pure_python    | 315 us                                                       | 208 us: 1.51x faster                                                        |
| sqlglot_parse           | 2.27 ms                                                      | 1.51 ms: 1.50x faster                                                       |
| bench_mp_pool           | 6.82 ms                                                      | 4.56 ms: 1.50x faster                                                       |
| scimark_lu              | 165 ms                                                       | 111 ms: 1.48x faster                                                        |
| float                   | 109 ms                                                       | 73.2 ms: 1.48x faster                                                       |
| spectral_norm           | 141 ms                                                       | 96.1 ms: 1.47x faster                                                       |
| scimark_sparse_mat_mult | 5.21 ms                                                      | 3.58 ms: 1.45x faster                                                       |
| pickle_pure_python      | 453 us                                                       | 313 us: 1.45x faster                                                        |
| chaos                   | 106 ms                                                       | 73.4 ms: 1.44x faster                                                       |
| sqlglot_transpile       | 2.73 ms                                                      | 1.90 ms: 1.44x faster                                                       |
| html5lib                | 94.7 ms                                                      | 66.2 ms: 1.43x faster                                                       |
| hexiom                  | 9.46 ms                                                      | 6.61 ms: 1.43x faster                                                       |
| crypto_pyaes            | 118 ms                                                       | 83.2 ms: 1.42x faster                                                       |
| mako                    | 14.7 ms                                                      | 10.4 ms: 1.41x faster                                                       |
| xml_etree_process       | 76.4 ms                                                      | 54.1 ms: 1.41x faster                                                       |
| deepcopy_memo           | 50.5 us                                                      | 36.4 us: 1.39x faster                                                       |
| async_tree_io           | 1.61 sec                                                     | 1.16 sec: 1.39x faster                                                      |
| pprint_pformat          | 2.15 sec                                                     | 1.57 sec: 1.37x faster                                                      |
| json_dumps              | 14.2 ms                                                      | 10.4 ms: 1.37x faster                                                       |
| tornado_http            | 157 ms                                                       | 114 ms: 1.37x faster                                                        |
| nbody                   | 134 ms                                                       | 98.1 ms: 1.37x faster                                                       |
| pprint_safe_repr        | 1.04 sec                                                     | 761 ms: 1.37x faster                                                        |
| async_tree_none         | 700 ms                                                       | 516 ms: 1.36x faster                                                        |
| aiohttp                 | 1.21 ms                                                      | 894 us: 1.35x faster                                                        |
| gunicorn                | 1.20 ms                                                      | 888 us: 1.35x faster                                                        |
| unpack_sequence         | 60.3 ns                                                      | 45.0 ns: 1.34x faster                                                       |
| async_tree_memoization  | 827 ms                                                       | 618 ms: 1.34x faster                                                        |
| regex_compile           | 192 ms                                                       | 146 ms: 1.32x faster                                                        |
| pycparser               | 1.65 sec                                                     | 1.25 sec: 1.32x faster                                                      |
| genshi_text             | 32.3 ms                                                      | 24.7 ms: 1.31x faster                                                       |
| async_generators        | 418 ms                                                       | 321 ms: 1.30x faster                                                        |
| chameleon               | 9.88 ms                                                      | 7.62 ms: 1.30x faster                                                       |
| logging_simple          | 9.06 us                                                      | 7.06 us: 1.28x faster                                                       |
| django_template         | 51.8 ms                                                      | 40.6 ms: 1.27x faster                                                       |
| logging_format          | 9.82 us                                                      | 7.77 us: 1.26x faster                                                       |
| scimark_fft             | 363 ms                                                       | 288 ms: 1.26x faster                                                        |
| 2to3                    | 349 ms                                                       | 278 ms: 1.26x faster                                                        |
| mypy2                   | 467 ms                                                       | 372 ms: 1.26x faster                                                        |
| thrift                  | 1.20 ms                                                      | 953 us: 1.26x faster                                                        |
| async_tree_cpu_io_mixed | 946 ms                                                       | 756 ms: 1.25x faster                                                        |
| json_loads              | 30.0 us                                                      | 24.3 us: 1.24x faster                                                       |
| docutils                | 3.42 sec                                                     | 2.79 sec: 1.22x faster                                                      |
| sqlglot_normalize       | 146 ms                                                       | 120 ms: 1.22x faster                                                        |
| dulwich_log             | 80.0 ms                                                      | 65.9 ms: 1.21x faster                                                       |
| fannkuch                | 488 ms                                                       | 405 ms: 1.21x faster                                                        |
| sqlglot_optimize        | 69.9 ms                                                      | 58.2 ms: 1.20x faster                                                       |
| xml_etree_generate      | 93.1 ms                                                      | 77.6 ms: 1.20x faster                                                       |
| deepcopy_reduce         | 4.00 us                                                      | 3.35 us: 1.19x faster                                                       |
| regex_v8                | 27.1 ms                                                      | 22.9 ms: 1.18x faster                                                       |
| bench_thread_pool       | 1.13 ms                                                      | 966 us: 1.18x faster                                                        |
| json                    | 5.91 ms                                                      | 5.05 ms: 1.17x faster                                                       |
| sqlite_synth            | 2.97 us                                                      | 2.54 us: 1.17x faster                                                       |
| deepcopy                | 459 us                                                       | 394 us: 1.16x faster                                                        |
| genshi_xml              | 64.1 ms                                                      | 55.5 ms: 1.16x faster                                                       |
| nqueens                 | 112 ms                                                       | 97.1 ms: 1.15x faster                                                       |
| xml_etree_parse         | 159 ms                                                       | 138 ms: 1.15x faster                                                        |
| dask                    | 469 ms                                                       | 409 ms: 1.15x faster                                                        |
| pylint                  | 564 ms                                                       | 496 ms: 1.14x faster                                                        |
| sympy_expand            | 599 ms                                                       | 527 ms: 1.13x faster                                                        |
| coroutines              | 30.9 ms                                                      | 27.4 ms: 1.12x faster                                                       |
| regex_dna               | 260 ms                                                       | 232 ms: 1.12x faster                                                        |
| comprehensions          | 27.0 us                                                      | 24.2 us: 1.12x faster                                                       |
| pathlib                 | 21.2 ms                                                      | 19.0 ms: 1.12x faster                                                       |
| sympy_integrate         | 28.3 ms                                                      | 25.4 ms: 1.12x faster                                                       |
| create_gc_cycles        | 1.79 ms                                                      | 1.61 ms: 1.11x faster                                                       |
| sympy_str               | 359 ms                                                       | 326 ms: 1.10x faster                                                        |
| pickle_list             | 4.23 us                                                      | 3.84 us: 1.10x faster                                                       |
| meteor_contest          | 138 ms                                                       | 126 ms: 1.09x faster                                                        |
| python_startup          | 11.5 ms                                                      | 10.6 ms: 1.09x faster                                                       |
| telco                   | 7.21 ms                                                      | 6.64 ms: 1.09x faster                                                       |
| mdp                     | 2.94 sec                                                     | 2.71 sec: 1.09x faster                                                      |
| pidigits                | 270 ms                                                       | 251 ms: 1.08x faster                                                        |
| sympy_sum               | 194 ms                                                       | 181 ms: 1.07x faster                                                        |
| xml_etree_iterparse     | 110 ms                                                       | 103 ms: 1.07x faster                                                        |
| generators              | 57.7 ms                                                      | 54.6 ms: 1.06x faster                                                       |
| asyncio_tcp             | 785 ms                                                       | 747 ms: 1.05x faster                                                        |
| unpickle                | 13.9 us                                                      | 13.3 us: 1.05x faster                                                       |
| gc_traversal            | 3.63 ms                                                      | 3.54 ms: 1.03x faster                                                       |
| pickle                  | 10.1 us                                                      | 10.1 us: 1.00x slower                                                       |
| python_startup_no_site  | 7.35 ms                                                      | 7.62 ms: 1.04x slower                                                       |
| pickle_dict             | 30.4 us                                                      | 31.9 us: 1.05x slower                                                       |
| regex_effbot            | 3.10 ms                                                      | 3.34 ms: 1.08x slower                                                       |
| coverage                | 65.9 ms                                                      | 81.5 ms: 1.24x slower                                                       |
| Geometric mean          | (ref)                                                        | 1.26x faster                                                                |

Benchmark hidden because not significant (1): unpickle_list
Ignored benchmarks (8) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120.json: asyncio_tcp_ssl, asyncio_websockets, flaskblogging, richards_super, sqlalchemy_declarative, sqlalchemy_imperative, tomli_loads, typing_runtime_protocols


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.22x
- 95% likely to have a speedup of 1.21x
- 99% likely to have a speedup of 1.20x
