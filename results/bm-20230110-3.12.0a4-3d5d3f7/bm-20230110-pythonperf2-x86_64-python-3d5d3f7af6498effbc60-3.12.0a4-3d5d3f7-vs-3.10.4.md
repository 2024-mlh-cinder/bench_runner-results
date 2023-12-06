
# Results vs. 3.10.4

- fork: python
- ref: 3d5d3f7af6498effbc60
- machine: linux-x86_64
- commit hash: 3d5d3f7
- commit date: 2023-01-10
- overall geometric mean: 1.26x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.19x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230110-pythonperf2-x86_64-python-3d5d3f7af6498effbc60-3.12.0a4-3d5d3f7 |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| 2to3           | 349 ms                                                       | 286 ms: 1.22x faster                                                        |
| chameleon      | 9.88 ms                                                      | 7.31 ms: 1.35x faster                                                       |
| docutils       | 3.42 sec                                                     | 2.78 sec: 1.23x faster                                                      |
| html5lib       | 94.7 ms                                                      | 66.8 ms: 1.42x faster                                                       |
| Geometric mean | (ref)                                                        | 1.30x faster                                                                |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230110-pythonperf2-x86_64-python-3d5d3f7af6498effbc60-3.12.0a4-3d5d3f7 |
|-------------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| async_tree_io           | 1.61 sec                                                     | 1.15 sec: 1.39x faster                                                      |
| async_tree_none         | 700 ms                                                       | 505 ms: 1.39x faster                                                        |
| async_tree_memoization  | 827 ms                                                       | 608 ms: 1.36x faster                                                        |
| async_tree_cpu_io_mixed | 946 ms                                                       | 742 ms: 1.28x faster                                                        |
| Geometric mean          | (ref)                                                        | 1.35x faster                                                                |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230110-pythonperf2-x86_64-python-3d5d3f7af6498effbc60-3.12.0a4-3d5d3f7 |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| float          | 109 ms                                                       | 72.4 ms: 1.50x faster                                                       |
| nbody          | 134 ms                                                       | 98.1 ms: 1.37x faster                                                       |
| pidigits       | 270 ms                                                       | 252 ms: 1.07x faster                                                        |
| Geometric mean | (ref)                                                        | 1.30x faster                                                                |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230110-pythonperf2-x86_64-python-3d5d3f7af6498effbc60-3.12.0a4-3d5d3f7 |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_compile  | 192 ms                                                       | 149 ms: 1.29x faster                                                        |
| regex_v8       | 27.1 ms                                                      | 23.0 ms: 1.18x faster                                                       |
| regex_dna      | 260 ms                                                       | 229 ms: 1.14x faster                                                        |
| regex_effbot   | 3.10 ms                                                      | 3.43 ms: 1.11x slower                                                       |
| Geometric mean | (ref)                                                        | 1.12x faster                                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230110-pythonperf2-x86_64-python-3d5d3f7af6498effbc60-3.12.0a4-3d5d3f7 |
|----------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| unpickle_pure_python | 315 us                                                       | 214 us: 1.47x faster                                                        |
| pickle_pure_python   | 453 us                                                       | 313 us: 1.45x faster                                                        |
| json_dumps           | 14.2 ms                                                      | 10.1 ms: 1.41x faster                                                       |
| xml_etree_process    | 76.4 ms                                                      | 55.4 ms: 1.38x faster                                                       |
| json_loads           | 30.0 us                                                      | 24.0 us: 1.25x faster                                                       |
| xml_etree_generate   | 93.1 ms                                                      | 80.3 ms: 1.16x faster                                                       |
| pickle_list          | 4.23 us                                                      | 3.70 us: 1.14x faster                                                       |
| xml_etree_parse      | 159 ms                                                       | 144 ms: 1.11x faster                                                        |
| xml_etree_iterparse  | 110 ms                                                       | 104 ms: 1.05x faster                                                        |
| unpickle             | 13.9 us                                                      | 13.3 us: 1.05x faster                                                       |
| pickle               | 10.1 us                                                      | 9.71 us: 1.04x faster                                                       |
| unpickle_list        | 4.45 us                                                      | 4.48 us: 1.01x slower                                                       |
| pickle_dict          | 30.4 us                                                      | 31.1 us: 1.02x slower                                                       |
| Geometric mean       | (ref)                                                        | 1.18x faster                                                                |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230110-pythonperf2-x86_64-python-3d5d3f7af6498effbc60-3.12.0a4-3d5d3f7 |
|------------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| python_startup         | 11.5 ms                                                      | 10.8 ms: 1.07x faster                                                       |
| python_startup_no_site | 7.35 ms                                                      | 7.87 ms: 1.07x slower                                                       |
| Geometric mean         | (ref)                                                        | 1.00x faster                                                                |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230110-pythonperf2-x86_64-python-3d5d3f7af6498effbc60-3.12.0a4-3d5d3f7 |
|-----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| mako            | 14.7 ms                                                      | 10.2 ms: 1.44x faster                                                       |
| django_template | 51.8 ms                                                      | 39.2 ms: 1.32x faster                                                       |
| genshi_text     | 32.3 ms                                                      | 24.8 ms: 1.30x faster                                                       |
| genshi_xml      | 64.1 ms                                                      | 53.7 ms: 1.19x faster                                                       |
| Geometric mean  | (ref)                                                        | 1.31x faster                                                                |

All benchmarks:
===============

| Benchmark               | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230110-pythonperf2-x86_64-python-3d5d3f7af6498effbc60-3.12.0a4-3d5d3f7 |
|-------------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| asyncio_tcp             | 785 ms                                                       | 386 ms: 2.04x faster                                                        |
| deltablue               | 7.43 ms                                                      | 3.69 ms: 2.01x faster                                                       |
| scimark_sor             | 183 ms                                                       | 108 ms: 1.70x faster                                                        |
| go                      | 258 ms                                                       | 153 ms: 1.68x faster                                                        |
| raytrace                | 497 ms                                                       | 299 ms: 1.66x faster                                                        |
| logging_silent          | 168 ns                                                       | 102 ns: 1.65x faster                                                        |
| scimark_monte_carlo     | 109 ms                                                       | 66.6 ms: 1.64x faster                                                       |
| scimark_lu              | 165 ms                                                       | 101 ms: 1.63x faster                                                        |
| richards                | 76.3 ms                                                      | 46.9 ms: 1.63x faster                                                       |
| pyflate                 | 698 ms                                                       | 433 ms: 1.61x faster                                                        |
| float                   | 109 ms                                                       | 72.4 ms: 1.50x faster                                                       |
| chaos                   | 106 ms                                                       | 70.9 ms: 1.49x faster                                                       |
| unpickle_pure_python    | 315 us                                                       | 214 us: 1.47x faster                                                        |
| crypto_pyaes            | 118 ms                                                       | 81.1 ms: 1.46x faster                                                       |
| pickle_pure_python      | 453 us                                                       | 313 us: 1.45x faster                                                        |
| mako                    | 14.7 ms                                                      | 10.2 ms: 1.44x faster                                                       |
| sqlglot_parse           | 2.27 ms                                                      | 1.59 ms: 1.43x faster                                                       |
| html5lib                | 94.7 ms                                                      | 66.8 ms: 1.42x faster                                                       |
| scimark_sparse_mat_mult | 5.21 ms                                                      | 3.70 ms: 1.41x faster                                                       |
| json_dumps              | 14.2 ms                                                      | 10.1 ms: 1.41x faster                                                       |
| sqlglot_transpile       | 2.73 ms                                                      | 1.95 ms: 1.40x faster                                                       |
| hexiom                  | 9.46 ms                                                      | 6.77 ms: 1.40x faster                                                       |
| spectral_norm           | 141 ms                                                       | 101 ms: 1.40x faster                                                        |
| async_tree_io           | 1.61 sec                                                     | 1.15 sec: 1.39x faster                                                      |
| async_tree_none         | 700 ms                                                       | 505 ms: 1.39x faster                                                        |
| bench_mp_pool           | 6.82 ms                                                      | 4.94 ms: 1.38x faster                                                       |
| xml_etree_process       | 76.4 ms                                                      | 55.4 ms: 1.38x faster                                                       |
| deepcopy_memo           | 50.5 us                                                      | 36.7 us: 1.38x faster                                                       |
| unpack_sequence         | 60.3 ns                                                      | 44.0 ns: 1.37x faster                                                       |
| nbody                   | 134 ms                                                       | 98.1 ms: 1.37x faster                                                       |
| async_tree_memoization  | 827 ms                                                       | 608 ms: 1.36x faster                                                        |
| chameleon               | 9.88 ms                                                      | 7.31 ms: 1.35x faster                                                       |
| pprint_pformat          | 2.15 sec                                                     | 1.63 sec: 1.32x faster                                                      |
| django_template         | 51.8 ms                                                      | 39.2 ms: 1.32x faster                                                       |
| thrift                  | 1.20 ms                                                      | 908 us: 1.32x faster                                                        |
| pprint_safe_repr        | 1.04 sec                                                     | 794 ms: 1.31x faster                                                        |
| pycparser               | 1.65 sec                                                     | 1.26 sec: 1.31x faster                                                      |
| logging_simple          | 9.06 us                                                      | 6.95 us: 1.30x faster                                                       |
| genshi_text             | 32.3 ms                                                      | 24.8 ms: 1.30x faster                                                       |
| async_generators        | 418 ms                                                       | 322 ms: 1.30x faster                                                        |
| regex_compile           | 192 ms                                                       | 149 ms: 1.29x faster                                                        |
| fannkuch                | 488 ms                                                       | 380 ms: 1.28x faster                                                        |
| scimark_fft             | 363 ms                                                       | 283 ms: 1.28x faster                                                        |
| logging_format          | 9.82 us                                                      | 7.66 us: 1.28x faster                                                       |
| async_tree_cpu_io_mixed | 946 ms                                                       | 742 ms: 1.28x faster                                                        |
| json_loads              | 30.0 us                                                      | 24.0 us: 1.25x faster                                                       |
| docutils                | 3.42 sec                                                     | 2.78 sec: 1.23x faster                                                      |
| mypy2                   | 467 ms                                                       | 380 ms: 1.23x faster                                                        |
| 2to3                    | 349 ms                                                       | 286 ms: 1.22x faster                                                        |
| deepcopy                | 459 us                                                       | 379 us: 1.21x faster                                                        |
| deepcopy_reduce         | 4.00 us                                                      | 3.33 us: 1.20x faster                                                       |
| genshi_xml              | 64.1 ms                                                      | 53.7 ms: 1.19x faster                                                       |
| sqlglot_normalize       | 146 ms                                                       | 123 ms: 1.19x faster                                                        |
| nqueens                 | 112 ms                                                       | 94.0 ms: 1.19x faster                                                       |
| dulwich_log             | 80.0 ms                                                      | 67.5 ms: 1.19x faster                                                       |
| sqlglot_optimize        | 69.9 ms                                                      | 59.3 ms: 1.18x faster                                                       |
| regex_v8                | 27.1 ms                                                      | 23.0 ms: 1.18x faster                                                       |
| xml_etree_generate      | 93.1 ms                                                      | 80.3 ms: 1.16x faster                                                       |
| sqlite_synth            | 2.97 us                                                      | 2.56 us: 1.16x faster                                                       |
| bench_thread_pool       | 1.13 ms                                                      | 987 us: 1.15x faster                                                        |
| dask                    | 469 ms                                                       | 408 ms: 1.15x faster                                                        |
| pickle_list             | 4.23 us                                                      | 3.70 us: 1.14x faster                                                       |
| regex_dna               | 260 ms                                                       | 229 ms: 1.14x faster                                                        |
| create_gc_cycles        | 1.79 ms                                                      | 1.58 ms: 1.13x faster                                                       |
| json                    | 5.91 ms                                                      | 5.24 ms: 1.13x faster                                                       |
| sympy_expand            | 599 ms                                                       | 537 ms: 1.12x faster                                                        |
| xml_etree_parse         | 159 ms                                                       | 144 ms: 1.11x faster                                                        |
| sympy_integrate         | 28.3 ms                                                      | 25.6 ms: 1.11x faster                                                       |
| coroutines              | 30.9 ms                                                      | 27.9 ms: 1.11x faster                                                       |
| pathlib                 | 21.2 ms                                                      | 19.4 ms: 1.09x faster                                                       |
| telco                   | 7.21 ms                                                      | 6.70 ms: 1.08x faster                                                       |
| pidigits                | 270 ms                                                       | 252 ms: 1.07x faster                                                        |
| python_startup          | 11.5 ms                                                      | 10.8 ms: 1.07x faster                                                       |
| sympy_str               | 359 ms                                                       | 335 ms: 1.07x faster                                                        |
| mdp                     | 2.94 sec                                                     | 2.75 sec: 1.07x faster                                                      |
| xml_etree_iterparse     | 110 ms                                                       | 104 ms: 1.05x faster                                                        |
| meteor_contest          | 138 ms                                                       | 131 ms: 1.05x faster                                                        |
| unpickle                | 13.9 us                                                      | 13.3 us: 1.05x faster                                                       |
| sympy_sum               | 194 ms                                                       | 186 ms: 1.04x faster                                                        |
| pickle                  | 10.1 us                                                      | 9.71 us: 1.04x faster                                                       |
| gc_traversal            | 3.63 ms                                                      | 3.54 ms: 1.02x faster                                                       |
| unpickle_list           | 4.45 us                                                      | 4.48 us: 1.01x slower                                                       |
| pickle_dict             | 30.4 us                                                      | 31.1 us: 1.02x slower                                                       |
| generators              | 57.7 ms                                                      | 60.5 ms: 1.05x slower                                                       |
| python_startup_no_site  | 7.35 ms                                                      | 7.87 ms: 1.07x slower                                                       |
| regex_effbot            | 3.10 ms                                                      | 3.43 ms: 1.11x slower                                                       |
| coverage                | 65.9 ms                                                      | 89.3 ms: 1.36x slower                                                       |
| Geometric mean          | (ref)                                                        | 1.26x faster                                                                |

Benchmark hidden because not significant (1): comprehensions
Ignored benchmarks (12) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, asyncio_tcp_ssl, asyncio_websockets, flaskblogging, gunicorn, pylint, richards_super, sqlalchemy_declarative, sqlalchemy_imperative, tomli_loads, tornado_http, typing_runtime_protocols


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.23x
- 95% likely to have a speedup of 1.22x
- 99% likely to have a speedup of 1.19x
