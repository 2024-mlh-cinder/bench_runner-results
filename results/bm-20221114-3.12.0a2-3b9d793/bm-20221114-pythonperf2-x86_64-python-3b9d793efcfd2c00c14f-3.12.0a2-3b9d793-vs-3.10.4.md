
# Results vs. 3.10.4

- fork: python
- ref: 3b9d793efcfd2c00c14f
- machine: linux-x86_64
- commit hash: 3b9d793
- commit date: 2022-11-14
- overall geometric mean: 1.25x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.19x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20221114-pythonperf2-x86_64-python-3b9d793efcfd2c00c14f-3.12.0a2-3b9d793 |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| 2to3           | 349 ms                                                       | 282 ms: 1.24x faster                                                        |
| chameleon      | 9.88 ms                                                      | 7.19 ms: 1.37x faster                                                       |
| docutils       | 3.42 sec                                                     | 2.77 sec: 1.24x faster                                                      |
| html5lib       | 94.7 ms                                                      | 66.7 ms: 1.42x faster                                                       |
| tornado_http   | 157 ms                                                       | 115 ms: 1.36x faster                                                        |
| Geometric mean | (ref)                                                        | 1.32x faster                                                                |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20221114-pythonperf2-x86_64-python-3b9d793efcfd2c00c14f-3.12.0a2-3b9d793 |
|-------------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| async_tree_io           | 1.61 sec                                                     | 1.17 sec: 1.37x faster                                                      |
| async_tree_none         | 700 ms                                                       | 520 ms: 1.35x faster                                                        |
| async_tree_memoization  | 827 ms                                                       | 621 ms: 1.33x faster                                                        |
| async_tree_cpu_io_mixed | 946 ms                                                       | 762 ms: 1.24x faster                                                        |
| Geometric mean          | (ref)                                                        | 1.32x faster                                                                |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20221114-pythonperf2-x86_64-python-3b9d793efcfd2c00c14f-3.12.0a2-3b9d793 |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| float          | 109 ms                                                       | 73.2 ms: 1.48x faster                                                       |
| nbody          | 134 ms                                                       | 90.9 ms: 1.48x faster                                                       |
| pidigits       | 270 ms                                                       | 252 ms: 1.07x faster                                                        |
| Geometric mean | (ref)                                                        | 1.33x faster                                                                |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20221114-pythonperf2-x86_64-python-3b9d793efcfd2c00c14f-3.12.0a2-3b9d793 |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_compile  | 192 ms                                                       | 147 ms: 1.31x faster                                                        |
| regex_v8       | 27.1 ms                                                      | 23.2 ms: 1.17x faster                                                       |
| regex_dna      | 260 ms                                                       | 227 ms: 1.15x faster                                                        |
| regex_effbot   | 3.10 ms                                                      | 3.45 ms: 1.11x slower                                                       |
| Geometric mean | (ref)                                                        | 1.12x faster                                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20221114-pythonperf2-x86_64-python-3b9d793efcfd2c00c14f-3.12.0a2-3b9d793 |
|----------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| unpickle_pure_python | 315 us                                                       | 209 us: 1.50x faster                                                        |
| pickle_pure_python   | 453 us                                                       | 314 us: 1.44x faster                                                        |
| xml_etree_process    | 76.4 ms                                                      | 54.8 ms: 1.40x faster                                                       |
| json_dumps           | 14.2 ms                                                      | 10.2 ms: 1.39x faster                                                       |
| json_loads           | 30.0 us                                                      | 23.7 us: 1.26x faster                                                       |
| xml_etree_generate   | 93.1 ms                                                      | 79.3 ms: 1.17x faster                                                       |
| pickle_list          | 4.23 us                                                      | 3.65 us: 1.16x faster                                                       |
| xml_etree_parse      | 159 ms                                                       | 143 ms: 1.12x faster                                                        |
| unpickle             | 13.9 us                                                      | 12.6 us: 1.10x faster                                                       |
| xml_etree_iterparse  | 110 ms                                                       | 108 ms: 1.02x faster                                                        |
| unpickle_list        | 4.45 us                                                      | 4.51 us: 1.02x slower                                                       |
| pickle_dict          | 30.4 us                                                      | 33.4 us: 1.10x slower                                                       |
| Geometric mean       | (ref)                                                        | 1.18x faster                                                                |

Benchmark hidden because not significant (1): pickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20221114-pythonperf2-x86_64-python-3b9d793efcfd2c00c14f-3.12.0a2-3b9d793 |
|------------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| python_startup         | 11.5 ms                                                      | 10.8 ms: 1.07x faster                                                       |
| python_startup_no_site | 7.35 ms                                                      | 7.87 ms: 1.07x slower                                                       |
| Geometric mean         | (ref)                                                        | 1.00x slower                                                                |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20221114-pythonperf2-x86_64-python-3b9d793efcfd2c00c14f-3.12.0a2-3b9d793 |
|-----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| mako            | 14.7 ms                                                      | 10.2 ms: 1.44x faster                                                       |
| django_template | 51.8 ms                                                      | 39.7 ms: 1.30x faster                                                       |
| genshi_text     | 32.3 ms                                                      | 25.2 ms: 1.28x faster                                                       |
| genshi_xml      | 64.1 ms                                                      | 54.0 ms: 1.19x faster                                                       |
| Geometric mean  | (ref)                                                        | 1.30x faster                                                                |

All benchmarks:
===============

| Benchmark               | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20221114-pythonperf2-x86_64-python-3b9d793efcfd2c00c14f-3.12.0a2-3b9d793 |
|-------------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| deltablue               | 7.43 ms                                                      | 3.64 ms: 2.04x faster                                                       |
| scimark_sor             | 183 ms                                                       | 106 ms: 1.72x faster                                                        |
| logging_silent          | 168 ns                                                       | 99.2 ns: 1.69x faster                                                       |
| richards                | 76.3 ms                                                      | 45.4 ms: 1.68x faster                                                       |
| scimark_monte_carlo     | 109 ms                                                       | 66.4 ms: 1.65x faster                                                       |
| raytrace                | 497 ms                                                       | 305 ms: 1.63x faster                                                        |
| go                      | 258 ms                                                       | 160 ms: 1.61x faster                                                        |
| pyflate                 | 698 ms                                                       | 436 ms: 1.60x faster                                                        |
| spectral_norm           | 141 ms                                                       | 93.2 ms: 1.52x faster                                                       |
| sqlglot_parse           | 2.27 ms                                                      | 1.50 ms: 1.51x faster                                                       |
| unpickle_pure_python    | 315 us                                                       | 209 us: 1.50x faster                                                        |
| bench_mp_pool           | 6.82 ms                                                      | 4.59 ms: 1.49x faster                                                       |
| float                   | 109 ms                                                       | 73.2 ms: 1.48x faster                                                       |
| scimark_lu              | 165 ms                                                       | 111 ms: 1.48x faster                                                        |
| nbody                   | 134 ms                                                       | 90.9 ms: 1.48x faster                                                       |
| crypto_pyaes            | 118 ms                                                       | 80.7 ms: 1.46x faster                                                       |
| sqlglot_transpile       | 2.73 ms                                                      | 1.87 ms: 1.46x faster                                                       |
| chaos                   | 106 ms                                                       | 72.9 ms: 1.45x faster                                                       |
| pickle_pure_python      | 453 us                                                       | 314 us: 1.44x faster                                                        |
| mako                    | 14.7 ms                                                      | 10.2 ms: 1.44x faster                                                       |
| html5lib                | 94.7 ms                                                      | 66.7 ms: 1.42x faster                                                       |
| hexiom                  | 9.46 ms                                                      | 6.76 ms: 1.40x faster                                                       |
| xml_etree_process       | 76.4 ms                                                      | 54.8 ms: 1.40x faster                                                       |
| scimark_sparse_mat_mult | 5.21 ms                                                      | 3.74 ms: 1.39x faster                                                       |
| json_dumps              | 14.2 ms                                                      | 10.2 ms: 1.39x faster                                                       |
| pprint_pformat          | 2.15 sec                                                     | 1.55 sec: 1.39x faster                                                      |
| pprint_safe_repr        | 1.04 sec                                                     | 752 ms: 1.38x faster                                                        |
| deepcopy_memo           | 50.5 us                                                      | 36.7 us: 1.38x faster                                                       |
| chameleon               | 9.88 ms                                                      | 7.19 ms: 1.37x faster                                                       |
| async_tree_io           | 1.61 sec                                                     | 1.17 sec: 1.37x faster                                                      |
| tornado_http            | 157 ms                                                       | 115 ms: 1.36x faster                                                        |
| gunicorn                | 1.20 ms                                                      | 886 us: 1.36x faster                                                        |
| async_tree_none         | 700 ms                                                       | 520 ms: 1.35x faster                                                        |
| aiohttp                 | 1.21 ms                                                      | 904 us: 1.34x faster                                                        |
| logging_simple          | 9.06 us                                                      | 6.78 us: 1.34x faster                                                       |
| async_tree_memoization  | 827 ms                                                       | 621 ms: 1.33x faster                                                        |
| scimark_fft             | 363 ms                                                       | 273 ms: 1.33x faster                                                        |
| pycparser               | 1.65 sec                                                     | 1.24 sec: 1.33x faster                                                      |
| unpack_sequence         | 60.3 ns                                                      | 45.8 ns: 1.32x faster                                                       |
| regex_compile           | 192 ms                                                       | 147 ms: 1.31x faster                                                        |
| thrift                  | 1.20 ms                                                      | 913 us: 1.31x faster                                                        |
| django_template         | 51.8 ms                                                      | 39.7 ms: 1.30x faster                                                       |
| async_generators        | 418 ms                                                       | 321 ms: 1.30x faster                                                        |
| logging_format          | 9.82 us                                                      | 7.60 us: 1.29x faster                                                       |
| genshi_text             | 32.3 ms                                                      | 25.2 ms: 1.28x faster                                                       |
| json_loads              | 30.0 us                                                      | 23.7 us: 1.26x faster                                                       |
| fannkuch                | 488 ms                                                       | 391 ms: 1.25x faster                                                        |
| mypy2                   | 467 ms                                                       | 374 ms: 1.25x faster                                                        |
| async_tree_cpu_io_mixed | 946 ms                                                       | 762 ms: 1.24x faster                                                        |
| 2to3                    | 349 ms                                                       | 282 ms: 1.24x faster                                                        |
| docutils                | 3.42 sec                                                     | 2.77 sec: 1.24x faster                                                      |
| sqlglot_optimize        | 69.9 ms                                                      | 58.2 ms: 1.20x faster                                                       |
| sqlglot_normalize       | 146 ms                                                       | 122 ms: 1.20x faster                                                        |
| json                    | 5.91 ms                                                      | 4.95 ms: 1.19x faster                                                       |
| dulwich_log             | 80.0 ms                                                      | 67.2 ms: 1.19x faster                                                       |
| deepcopy                | 459 us                                                       | 387 us: 1.19x faster                                                        |
| genshi_xml              | 64.1 ms                                                      | 54.0 ms: 1.19x faster                                                       |
| deepcopy_reduce         | 4.00 us                                                      | 3.39 us: 1.18x faster                                                       |
| xml_etree_generate      | 93.1 ms                                                      | 79.3 ms: 1.17x faster                                                       |
| bench_thread_pool       | 1.13 ms                                                      | 969 us: 1.17x faster                                                        |
| regex_v8                | 27.1 ms                                                      | 23.2 ms: 1.17x faster                                                       |
| pickle_list             | 4.23 us                                                      | 3.65 us: 1.16x faster                                                       |
| sqlite_synth            | 2.97 us                                                      | 2.57 us: 1.16x faster                                                       |
| regex_dna               | 260 ms                                                       | 227 ms: 1.15x faster                                                        |
| dask                    | 469 ms                                                       | 410 ms: 1.14x faster                                                        |
| create_gc_cycles        | 1.79 ms                                                      | 1.60 ms: 1.12x faster                                                       |
| xml_etree_parse         | 159 ms                                                       | 143 ms: 1.12x faster                                                        |
| sympy_integrate         | 28.3 ms                                                      | 25.5 ms: 1.11x faster                                                       |
| coroutines              | 30.9 ms                                                      | 27.9 ms: 1.11x faster                                                       |
| unpickle                | 13.9 us                                                      | 12.6 us: 1.10x faster                                                       |
| telco                   | 7.21 ms                                                      | 6.58 ms: 1.10x faster                                                       |
| pathlib                 | 21.2 ms                                                      | 19.3 ms: 1.10x faster                                                       |
| nqueens                 | 112 ms                                                       | 103 ms: 1.09x faster                                                        |
| sympy_expand            | 599 ms                                                       | 550 ms: 1.09x faster                                                        |
| mdp                     | 2.94 sec                                                     | 2.73 sec: 1.08x faster                                                      |
| pidigits                | 270 ms                                                       | 252 ms: 1.07x faster                                                        |
| meteor_contest          | 138 ms                                                       | 129 ms: 1.07x faster                                                        |
| python_startup          | 11.5 ms                                                      | 10.8 ms: 1.07x faster                                                       |
| sympy_str               | 359 ms                                                       | 337 ms: 1.06x faster                                                        |
| sympy_sum               | 194 ms                                                       | 184 ms: 1.05x faster                                                        |
| asyncio_tcp             | 785 ms                                                       | 749 ms: 1.05x faster                                                        |
| xml_etree_iterparse     | 110 ms                                                       | 108 ms: 1.02x faster                                                        |
| comprehensions          | 27.0 us                                                      | 26.9 us: 1.00x faster                                                       |
| unpickle_list           | 4.45 us                                                      | 4.51 us: 1.02x slower                                                       |
| generators              | 57.7 ms                                                      | 61.2 ms: 1.06x slower                                                       |
| python_startup_no_site  | 7.35 ms                                                      | 7.87 ms: 1.07x slower                                                       |
| gc_traversal            | 3.63 ms                                                      | 3.92 ms: 1.08x slower                                                       |
| pickle_dict             | 30.4 us                                                      | 33.4 us: 1.10x slower                                                       |
| regex_effbot            | 3.10 ms                                                      | 3.45 ms: 1.11x slower                                                       |
| coverage                | 65.9 ms                                                      | 86.9 ms: 1.32x slower                                                       |
| Geometric mean          | (ref)                                                        | 1.25x faster                                                                |

Benchmark hidden because not significant (1): pickle
Ignored benchmarks (9) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120.json: asyncio_tcp_ssl, asyncio_websockets, flaskblogging, pylint, richards_super, sqlalchemy_declarative, sqlalchemy_imperative, tomli_loads, typing_runtime_protocols


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.23x
- 95% likely to have a speedup of 1.22x
- 99% likely to have a speedup of 1.19x
