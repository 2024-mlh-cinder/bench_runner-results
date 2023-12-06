
# Results vs. 3.10.4

- fork: python
- ref: 2e91dba437fe5c56c6f8
- machine: linux-x86_64
- commit hash: 2e91dba
- commit date: 2021-12-08
- overall geometric mean: 1.15x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.11x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20211208-pythonperf2-x86_64-python-2e91dba437fe5c56c6f8-3.11.0a3-2e91dba |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| 2to3           | 349 ms                                                       | 293 ms: 1.19x faster                                                        |
| chameleon      | 9.88 ms                                                      | 8.85 ms: 1.12x faster                                                       |
| docutils       | 3.42 sec                                                     | 3.02 sec: 1.13x faster                                                      |
| html5lib       | 94.7 ms                                                      | 75.1 ms: 1.26x faster                                                       |
| tornado_http   | 157 ms                                                       | 135 ms: 1.16x faster                                                        |
| Geometric mean | (ref)                                                        | 1.17x faster                                                                |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20211208-pythonperf2-x86_64-python-2e91dba437fe5c56c6f8-3.11.0a3-2e91dba |
|-------------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| async_tree_none         | 700 ms                                                       | 545 ms: 1.28x faster                                                        |
| async_tree_io           | 1.61 sec                                                     | 1.32 sec: 1.22x faster                                                      |
| async_tree_memoization  | 827 ms                                                       | 686 ms: 1.21x faster                                                        |
| async_tree_cpu_io_mixed | 946 ms                                                       | 811 ms: 1.17x faster                                                        |
| Geometric mean          | (ref)                                                        | 1.22x faster                                                                |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20211208-pythonperf2-x86_64-python-2e91dba437fe5c56c6f8-3.11.0a3-2e91dba |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| float          | 109 ms                                                       | 80.9 ms: 1.34x faster                                                       |
| nbody          | 134 ms                                                       | 109 ms: 1.24x faster                                                        |
| pidigits       | 270 ms                                                       | 253 ms: 1.07x faster                                                        |
| Geometric mean | (ref)                                                        | 1.21x faster                                                                |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20211208-pythonperf2-x86_64-python-2e91dba437fe5c56c6f8-3.11.0a3-2e91dba |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_compile  | 192 ms                                                       | 153 ms: 1.26x faster                                                        |
| regex_v8       | 27.1 ms                                                      | 25.7 ms: 1.05x faster                                                       |
| regex_dna      | 260 ms                                                       | 261 ms: 1.00x slower                                                        |
| Geometric mean | (ref)                                                        | 1.07x faster                                                                |

Benchmark hidden because not significant (1): regex_effbot

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20211208-pythonperf2-x86_64-python-2e91dba437fe5c56c6f8-3.11.0a3-2e91dba |
|----------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| xml_etree_process    | 76.4 ms                                                      | 60.9 ms: 1.26x faster                                                       |
| pickle_pure_python   | 453 us                                                       | 366 us: 1.24x faster                                                        |
| unpickle_pure_python | 315 us                                                       | 265 us: 1.19x faster                                                        |
| json_loads           | 30.0 us                                                      | 25.3 us: 1.19x faster                                                       |
| xml_etree_generate   | 93.1 ms                                                      | 82.8 ms: 1.12x faster                                                       |
| unpickle             | 13.9 us                                                      | 13.2 us: 1.06x faster                                                       |
| xml_etree_parse      | 159 ms                                                       | 155 ms: 1.03x faster                                                        |
| json_dumps           | 14.2 ms                                                      | 14.1 ms: 1.01x faster                                                       |
| pickle               | 10.1 us                                                      | 10.2 us: 1.02x slower                                                       |
| unpickle_list        | 4.45 us                                                      | 4.53 us: 1.02x slower                                                       |
| pickle_list          | 4.23 us                                                      | 4.32 us: 1.02x slower                                                       |
| pickle_dict          | 30.4 us                                                      | 33.0 us: 1.09x slower                                                       |
| Geometric mean       | (ref)                                                        | 1.07x faster                                                                |

Benchmark hidden because not significant (1): xml_etree_iterparse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20211208-pythonperf2-x86_64-python-2e91dba437fe5c56c6f8-3.11.0a3-2e91dba |
|------------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| python_startup         | 11.5 ms                                                      | 10.1 ms: 1.14x faster                                                       |
| python_startup_no_site | 7.35 ms                                                      | 7.14 ms: 1.03x faster                                                       |
| Geometric mean         | (ref)                                                        | 1.08x faster                                                                |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20211208-pythonperf2-x86_64-python-2e91dba437fe5c56c6f8-3.11.0a3-2e91dba |
|-----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| django_template | 51.8 ms                                                      | 44.9 ms: 1.15x faster                                                       |
| mako            | 14.7 ms                                                      | 12.9 ms: 1.15x faster                                                       |
| genshi_text     | 32.3 ms                                                      | 28.2 ms: 1.14x faster                                                       |
| genshi_xml      | 64.1 ms                                                      | 59.7 ms: 1.07x faster                                                       |
| Geometric mean  | (ref)                                                        | 1.13x faster                                                                |

All benchmarks:
===============

| Benchmark               | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20211208-pythonperf2-x86_64-python-2e91dba437fe5c56c6f8-3.11.0a3-2e91dba |
|-------------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| scimark_sor             | 183 ms                                                       | 115 ms: 1.59x faster                                                        |
| deltablue               | 7.43 ms                                                      | 4.78 ms: 1.55x faster                                                       |
| scimark_lu              | 165 ms                                                       | 110 ms: 1.50x faster                                                        |
| go                      | 258 ms                                                       | 173 ms: 1.49x faster                                                        |
| logging_silent          | 168 ns                                                       | 116 ns: 1.45x faster                                                        |
| raytrace                | 497 ms                                                       | 347 ms: 1.43x faster                                                        |
| scimark_monte_carlo     | 109 ms                                                       | 76.7 ms: 1.43x faster                                                       |
| spectral_norm           | 141 ms                                                       | 99.9 ms: 1.41x faster                                                       |
| bench_mp_pool           | 6.82 ms                                                      | 4.90 ms: 1.39x faster                                                       |
| chaos                   | 106 ms                                                       | 78.3 ms: 1.35x faster                                                       |
| richards                | 76.3 ms                                                      | 56.7 ms: 1.35x faster                                                       |
| float                   | 109 ms                                                       | 80.9 ms: 1.34x faster                                                       |
| pyflate                 | 698 ms                                                       | 525 ms: 1.33x faster                                                        |
| async_generators        | 418 ms                                                       | 319 ms: 1.31x faster                                                        |
| unpack_sequence         | 60.3 ns                                                      | 46.3 ns: 1.30x faster                                                       |
| logging_simple          | 9.06 us                                                      | 7.04 us: 1.29x faster                                                       |
| async_tree_none         | 700 ms                                                       | 545 ms: 1.28x faster                                                        |
| hexiom                  | 9.46 ms                                                      | 7.41 ms: 1.28x faster                                                       |
| logging_format          | 9.82 us                                                      | 7.70 us: 1.27x faster                                                       |
| html5lib                | 94.7 ms                                                      | 75.1 ms: 1.26x faster                                                       |
| regex_compile           | 192 ms                                                       | 153 ms: 1.26x faster                                                        |
| xml_etree_process       | 76.4 ms                                                      | 60.9 ms: 1.26x faster                                                       |
| pprint_safe_repr        | 1.04 sec                                                     | 832 ms: 1.25x faster                                                        |
| crypto_pyaes            | 118 ms                                                       | 94.7 ms: 1.25x faster                                                       |
| pprint_pformat          | 2.15 sec                                                     | 1.74 sec: 1.24x faster                                                      |
| nbody                   | 134 ms                                                       | 109 ms: 1.24x faster                                                        |
| pickle_pure_python      | 453 us                                                       | 366 us: 1.24x faster                                                        |
| pycparser               | 1.65 sec                                                     | 1.35 sec: 1.22x faster                                                      |
| async_tree_io           | 1.61 sec                                                     | 1.32 sec: 1.22x faster                                                      |
| deepcopy_memo           | 50.5 us                                                      | 41.5 us: 1.22x faster                                                       |
| async_tree_memoization  | 827 ms                                                       | 686 ms: 1.21x faster                                                        |
| thrift                  | 1.20 ms                                                      | 995 us: 1.20x faster                                                        |
| gunicorn                | 1.20 ms                                                      | 1.00 ms: 1.20x faster                                                       |
| 2to3                    | 349 ms                                                       | 293 ms: 1.19x faster                                                        |
| unpickle_pure_python    | 315 us                                                       | 265 us: 1.19x faster                                                        |
| json_loads              | 30.0 us                                                      | 25.3 us: 1.19x faster                                                       |
| async_tree_cpu_io_mixed | 946 ms                                                       | 811 ms: 1.17x faster                                                        |
| tornado_http            | 157 ms                                                       | 135 ms: 1.16x faster                                                        |
| scimark_fft             | 363 ms                                                       | 314 ms: 1.16x faster                                                        |
| django_template         | 51.8 ms                                                      | 44.9 ms: 1.15x faster                                                       |
| generators              | 57.7 ms                                                      | 50.1 ms: 1.15x faster                                                       |
| mako                    | 14.7 ms                                                      | 12.9 ms: 1.15x faster                                                       |
| coroutines              | 30.9 ms                                                      | 27.0 ms: 1.14x faster                                                       |
| genshi_text             | 32.3 ms                                                      | 28.2 ms: 1.14x faster                                                       |
| python_startup          | 11.5 ms                                                      | 10.1 ms: 1.14x faster                                                       |
| fannkuch                | 488 ms                                                       | 428 ms: 1.14x faster                                                        |
| scimark_sparse_mat_mult | 5.21 ms                                                      | 4.58 ms: 1.14x faster                                                       |
| docutils                | 3.42 sec                                                     | 3.02 sec: 1.13x faster                                                      |
| json                    | 5.91 ms                                                      | 5.24 ms: 1.13x faster                                                       |
| deepcopy_reduce         | 4.00 us                                                      | 3.55 us: 1.13x faster                                                       |
| xml_etree_generate      | 93.1 ms                                                      | 82.8 ms: 1.12x faster                                                       |
| chameleon               | 9.88 ms                                                      | 8.85 ms: 1.12x faster                                                       |
| sqlglot_normalize       | 146 ms                                                       | 133 ms: 1.10x faster                                                        |
| deepcopy                | 459 us                                                       | 418 us: 1.10x faster                                                        |
| sqlite_synth            | 2.97 us                                                      | 2.70 us: 1.10x faster                                                       |
| dulwich_log             | 80.0 ms                                                      | 73.0 ms: 1.10x faster                                                       |
| nqueens                 | 112 ms                                                       | 103 ms: 1.09x faster                                                        |
| sqlglot_optimize        | 69.9 ms                                                      | 64.7 ms: 1.08x faster                                                       |
| create_gc_cycles        | 1.79 ms                                                      | 1.66 ms: 1.08x faster                                                       |
| dask                    | 469 ms                                                       | 435 ms: 1.08x faster                                                        |
| genshi_xml              | 64.1 ms                                                      | 59.7 ms: 1.07x faster                                                       |
| bench_thread_pool       | 1.13 ms                                                      | 1.06 ms: 1.07x faster                                                       |
| pidigits                | 270 ms                                                       | 253 ms: 1.07x faster                                                        |
| sympy_integrate         | 28.3 ms                                                      | 26.5 ms: 1.07x faster                                                       |
| meteor_contest          | 138 ms                                                       | 129 ms: 1.07x faster                                                        |
| mdp                     | 2.94 sec                                                     | 2.76 sec: 1.06x faster                                                      |
| pathlib                 | 21.2 ms                                                      | 19.9 ms: 1.06x faster                                                       |
| unpickle                | 13.9 us                                                      | 13.2 us: 1.06x faster                                                       |
| regex_v8                | 27.1 ms                                                      | 25.7 ms: 1.05x faster                                                       |
| sqlglot_transpile       | 2.73 ms                                                      | 2.60 ms: 1.05x faster                                                       |
| sympy_expand            | 599 ms                                                       | 579 ms: 1.03x faster                                                        |
| python_startup_no_site  | 7.35 ms                                                      | 7.14 ms: 1.03x faster                                                       |
| sqlglot_parse           | 2.27 ms                                                      | 2.21 ms: 1.03x faster                                                       |
| xml_etree_parse         | 159 ms                                                       | 155 ms: 1.03x faster                                                        |
| sympy_sum               | 194 ms                                                       | 189 ms: 1.02x faster                                                        |
| sympy_str               | 359 ms                                                       | 350 ms: 1.02x faster                                                        |
| telco                   | 7.21 ms                                                      | 7.11 ms: 1.01x faster                                                       |
| json_dumps              | 14.2 ms                                                      | 14.1 ms: 1.01x faster                                                       |
| regex_dna               | 260 ms                                                       | 261 ms: 1.00x slower                                                        |
| pickle                  | 10.1 us                                                      | 10.2 us: 1.02x slower                                                       |
| unpickle_list           | 4.45 us                                                      | 4.53 us: 1.02x slower                                                       |
| pickle_list             | 4.23 us                                                      | 4.32 us: 1.02x slower                                                       |
| gc_traversal            | 3.63 ms                                                      | 3.89 ms: 1.07x slower                                                       |
| pickle_dict             | 30.4 us                                                      | 33.0 us: 1.09x slower                                                       |
| coverage                | 65.9 ms                                                      | 72.1 ms: 1.09x slower                                                       |
| flaskblogging           | 4.44 ms                                                      | 4.95 ms: 1.12x slower                                                       |
| comprehensions          | 27.0 us                                                      | 30.6 us: 1.13x slower                                                       |
| Geometric mean          | (ref)                                                        | 1.15x faster                                                                |

Benchmark hidden because not significant (2): regex_effbot, xml_etree_iterparse
Ignored benchmarks (11) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, asyncio_tcp, asyncio_tcp_ssl, asyncio_websockets, mypy2, pylint, richards_super, sqlalchemy_declarative, sqlalchemy_imperative, tomli_loads, typing_runtime_protocols


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.13x
- 95% likely to have a speedup of 1.12x
- 99% likely to have a speedup of 1.11x
