
# Results vs. 3.10.4

- fork: python
- ref: 2e49bd06c5ffab7d1540
- machine: linux-x86_64
- commit hash: 2e49bd0
- commit date: 2022-04-05
- overall geometric mean: 1.20x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.14x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20220405-pythonperf2-x86_64-python-2e49bd06c5ffab7d1540-3.11.0a7-2e49bd0 |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| 2to3           | 349 ms                                                       | 293 ms: 1.19x faster                                                        |
| chameleon      | 9.88 ms                                                      | 7.97 ms: 1.24x faster                                                       |
| docutils       | 3.42 sec                                                     | 2.92 sec: 1.17x faster                                                      |
| html5lib       | 94.7 ms                                                      | 75.0 ms: 1.26x faster                                                       |
| tornado_http   | 157 ms                                                       | 123 ms: 1.27x faster                                                        |
| Geometric mean | (ref)                                                        | 1.23x faster                                                                |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20220405-pythonperf2-x86_64-python-2e49bd06c5ffab7d1540-3.11.0a7-2e49bd0 |
|-------------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| async_tree_io           | 1.61 sec                                                     | 1.18 sec: 1.37x faster                                                      |
| async_tree_none         | 700 ms                                                       | 523 ms: 1.34x faster                                                        |
| async_tree_memoization  | 827 ms                                                       | 641 ms: 1.29x faster                                                        |
| async_tree_cpu_io_mixed | 946 ms                                                       | 753 ms: 1.26x faster                                                        |
| Geometric mean          | (ref)                                                        | 1.31x faster                                                                |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20220405-pythonperf2-x86_64-python-2e49bd06c5ffab7d1540-3.11.0a7-2e49bd0 |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| nbody          | 134 ms                                                       | 93.6 ms: 1.43x faster                                                       |
| float          | 109 ms                                                       | 78.4 ms: 1.39x faster                                                       |
| pidigits       | 270 ms                                                       | 251 ms: 1.08x faster                                                        |
| Geometric mean | (ref)                                                        | 1.29x faster                                                                |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20220405-pythonperf2-x86_64-python-2e49bd06c5ffab7d1540-3.11.0a7-2e49bd0 |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_compile  | 192 ms                                                       | 159 ms: 1.21x faster                                                        |
| regex_dna      | 260 ms                                                       | 253 ms: 1.03x faster                                                        |
| regex_v8       | 27.1 ms                                                      | 26.6 ms: 1.02x faster                                                       |
| regex_effbot   | 3.10 ms                                                      | 3.13 ms: 1.01x slower                                                       |
| Geometric mean | (ref)                                                        | 1.06x faster                                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20220405-pythonperf2-x86_64-python-2e49bd06c5ffab7d1540-3.11.0a7-2e49bd0 |
|----------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| pickle_pure_python   | 453 us                                                       | 331 us: 1.37x faster                                                        |
| xml_etree_process    | 76.4 ms                                                      | 58.3 ms: 1.31x faster                                                       |
| unpickle_pure_python | 315 us                                                       | 242 us: 1.30x faster                                                        |
| json_loads           | 30.0 us                                                      | 24.5 us: 1.23x faster                                                       |
| xml_etree_generate   | 93.1 ms                                                      | 82.8 ms: 1.13x faster                                                       |
| unpickle             | 13.9 us                                                      | 13.0 us: 1.07x faster                                                       |
| json_dumps           | 14.2 ms                                                      | 13.5 ms: 1.05x faster                                                       |
| xml_etree_iterparse  | 110 ms                                                       | 106 ms: 1.04x faster                                                        |
| pickle_list          | 4.23 us                                                      | 4.12 us: 1.03x faster                                                       |
| pickle               | 10.1 us                                                      | 9.88 us: 1.02x faster                                                       |
| xml_etree_parse      | 159 ms                                                       | 157 ms: 1.02x faster                                                        |
| unpickle_list        | 4.45 us                                                      | 4.52 us: 1.02x slower                                                       |
| pickle_dict          | 30.4 us                                                      | 31.1 us: 1.02x slower                                                       |
| Geometric mean       | (ref)                                                        | 1.11x faster                                                                |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20220405-pythonperf2-x86_64-python-2e49bd06c5ffab7d1540-3.11.0a7-2e49bd0 |
|------------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| python_startup         | 11.5 ms                                                      | 10.4 ms: 1.11x faster                                                       |
| python_startup_no_site | 7.35 ms                                                      | 7.46 ms: 1.02x slower                                                       |
| Geometric mean         | (ref)                                                        | 1.05x faster                                                                |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20220405-pythonperf2-x86_64-python-2e49bd06c5ffab7d1540-3.11.0a7-2e49bd0 |
|-----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| mako            | 14.7 ms                                                      | 11.2 ms: 1.31x faster                                                       |
| django_template | 51.8 ms                                                      | 40.7 ms: 1.27x faster                                                       |
| genshi_text     | 32.3 ms                                                      | 26.8 ms: 1.20x faster                                                       |
| genshi_xml      | 64.1 ms                                                      | 59.7 ms: 1.07x faster                                                       |
| Geometric mean  | (ref)                                                        | 1.21x faster                                                                |

All benchmarks:
===============

| Benchmark               | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20220405-pythonperf2-x86_64-python-2e49bd06c5ffab7d1540-3.11.0a7-2e49bd0 |
|-------------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| deltablue               | 7.43 ms                                                      | 4.23 ms: 1.76x faster                                                       |
| scimark_sor             | 183 ms                                                       | 112 ms: 1.63x faster                                                        |
| logging_silent          | 168 ns                                                       | 105 ns: 1.60x faster                                                        |
| go                      | 258 ms                                                       | 166 ms: 1.55x faster                                                        |
| raytrace                | 497 ms                                                       | 322 ms: 1.54x faster                                                        |
| pyflate                 | 698 ms                                                       | 464 ms: 1.51x faster                                                        |
| bench_mp_pool           | 6.82 ms                                                      | 4.60 ms: 1.48x faster                                                       |
| richards                | 76.3 ms                                                      | 52.8 ms: 1.44x faster                                                       |
| chaos                   | 106 ms                                                       | 73.4 ms: 1.44x faster                                                       |
| nbody                   | 134 ms                                                       | 93.6 ms: 1.43x faster                                                       |
| scimark_monte_carlo     | 109 ms                                                       | 77.1 ms: 1.42x faster                                                       |
| float                   | 109 ms                                                       | 78.4 ms: 1.39x faster                                                       |
| scimark_lu              | 165 ms                                                       | 120 ms: 1.37x faster                                                        |
| pickle_pure_python      | 453 us                                                       | 331 us: 1.37x faster                                                        |
| async_tree_io           | 1.61 sec                                                     | 1.18 sec: 1.37x faster                                                      |
| logging_simple          | 9.06 us                                                      | 6.69 us: 1.35x faster                                                       |
| async_tree_none         | 700 ms                                                       | 523 ms: 1.34x faster                                                        |
| crypto_pyaes            | 118 ms                                                       | 89.5 ms: 1.32x faster                                                       |
| spectral_norm           | 141 ms                                                       | 107 ms: 1.32x faster                                                        |
| mako                    | 14.7 ms                                                      | 11.2 ms: 1.31x faster                                                       |
| async_generators        | 418 ms                                                       | 319 ms: 1.31x faster                                                        |
| xml_etree_process       | 76.4 ms                                                      | 58.3 ms: 1.31x faster                                                       |
| deepcopy_memo           | 50.5 us                                                      | 38.8 us: 1.30x faster                                                       |
| unpickle_pure_python    | 315 us                                                       | 242 us: 1.30x faster                                                        |
| logging_format          | 9.82 us                                                      | 7.59 us: 1.29x faster                                                       |
| async_tree_memoization  | 827 ms                                                       | 641 ms: 1.29x faster                                                        |
| thrift                  | 1.20 ms                                                      | 928 us: 1.29x faster                                                        |
| dask                    | 469 ms                                                       | 367 ms: 1.28x faster                                                        |
| unpack_sequence         | 60.3 ns                                                      | 47.3 ns: 1.27x faster                                                       |
| django_template         | 51.8 ms                                                      | 40.7 ms: 1.27x faster                                                       |
| pprint_pformat          | 2.15 sec                                                     | 1.69 sec: 1.27x faster                                                      |
| pprint_safe_repr        | 1.04 sec                                                     | 818 ms: 1.27x faster                                                        |
| tornado_http            | 157 ms                                                       | 123 ms: 1.27x faster                                                        |
| html5lib                | 94.7 ms                                                      | 75.0 ms: 1.26x faster                                                       |
| async_tree_cpu_io_mixed | 946 ms                                                       | 753 ms: 1.26x faster                                                        |
| gunicorn                | 1.20 ms                                                      | 968 us: 1.24x faster                                                        |
| pycparser               | 1.65 sec                                                     | 1.33 sec: 1.24x faster                                                      |
| chameleon               | 9.88 ms                                                      | 7.97 ms: 1.24x faster                                                       |
| aiohttp                 | 1.21 ms                                                      | 978 us: 1.24x faster                                                        |
| hexiom                  | 9.46 ms                                                      | 7.66 ms: 1.23x faster                                                       |
| json_loads              | 30.0 us                                                      | 24.5 us: 1.23x faster                                                       |
| scimark_fft             | 363 ms                                                       | 297 ms: 1.22x faster                                                        |
| regex_compile           | 192 ms                                                       | 159 ms: 1.21x faster                                                        |
| genshi_text             | 32.3 ms                                                      | 26.8 ms: 1.20x faster                                                       |
| 2to3                    | 349 ms                                                       | 293 ms: 1.19x faster                                                        |
| deepcopy                | 459 us                                                       | 385 us: 1.19x faster                                                        |
| sqlalchemy_declarative  | 189 ms                                                       | 160 ms: 1.18x faster                                                        |
| sqlite_synth            | 2.97 us                                                      | 2.52 us: 1.18x faster                                                       |
| docutils                | 3.42 sec                                                     | 2.92 sec: 1.17x faster                                                      |
| sqlglot_normalize       | 146 ms                                                       | 127 ms: 1.16x faster                                                        |
| scimark_sparse_mat_mult | 5.21 ms                                                      | 4.51 ms: 1.16x faster                                                       |
| deepcopy_reduce         | 4.00 us                                                      | 3.48 us: 1.15x faster                                                       |
| dulwich_log             | 80.0 ms                                                      | 69.8 ms: 1.15x faster                                                       |
| sqlglot_transpile       | 2.73 ms                                                      | 2.38 ms: 1.15x faster                                                       |
| json                    | 5.91 ms                                                      | 5.17 ms: 1.14x faster                                                       |
| flaskblogging           | 4.44 ms                                                      | 3.92 ms: 1.13x faster                                                       |
| sqlglot_optimize        | 69.9 ms                                                      | 61.9 ms: 1.13x faster                                                       |
| xml_etree_generate      | 93.1 ms                                                      | 82.8 ms: 1.13x faster                                                       |
| sympy_integrate         | 28.3 ms                                                      | 25.3 ms: 1.12x faster                                                       |
| sqlalchemy_imperative   | 23.0 ms                                                      | 20.5 ms: 1.12x faster                                                       |
| bench_thread_pool       | 1.13 ms                                                      | 1.02 ms: 1.12x faster                                                       |
| python_startup          | 11.5 ms                                                      | 10.4 ms: 1.11x faster                                                       |
| sqlglot_parse           | 2.27 ms                                                      | 2.04 ms: 1.11x faster                                                       |
| fannkuch                | 488 ms                                                       | 442 ms: 1.11x faster                                                        |
| pathlib                 | 21.2 ms                                                      | 19.3 ms: 1.09x faster                                                       |
| nqueens                 | 112 ms                                                       | 102 ms: 1.09x faster                                                        |
| sympy_sum               | 194 ms                                                       | 177 ms: 1.09x faster                                                        |
| pylint                  | 564 ms                                                       | 517 ms: 1.09x faster                                                        |
| sympy_expand            | 599 ms                                                       | 549 ms: 1.09x faster                                                        |
| create_gc_cycles        | 1.79 ms                                                      | 1.65 ms: 1.09x faster                                                       |
| sympy_str               | 359 ms                                                       | 330 ms: 1.09x faster                                                        |
| pidigits                | 270 ms                                                       | 251 ms: 1.08x faster                                                        |
| genshi_xml              | 64.1 ms                                                      | 59.7 ms: 1.07x faster                                                       |
| unpickle                | 13.9 us                                                      | 13.0 us: 1.07x faster                                                       |
| mdp                     | 2.94 sec                                                     | 2.76 sec: 1.07x faster                                                      |
| coroutines              | 30.9 ms                                                      | 29.0 ms: 1.06x faster                                                       |
| telco                   | 7.21 ms                                                      | 6.79 ms: 1.06x faster                                                       |
| json_dumps              | 14.2 ms                                                      | 13.5 ms: 1.05x faster                                                       |
| generators              | 57.7 ms                                                      | 54.7 ms: 1.05x faster                                                       |
| asyncio_tcp             | 785 ms                                                       | 746 ms: 1.05x faster                                                        |
| xml_etree_iterparse     | 110 ms                                                       | 106 ms: 1.04x faster                                                        |
| meteor_contest          | 138 ms                                                       | 133 ms: 1.03x faster                                                        |
| regex_dna               | 260 ms                                                       | 253 ms: 1.03x faster                                                        |
| pickle_list             | 4.23 us                                                      | 4.12 us: 1.03x faster                                                       |
| pickle                  | 10.1 us                                                      | 9.88 us: 1.02x faster                                                       |
| regex_v8                | 27.1 ms                                                      | 26.6 ms: 1.02x faster                                                       |
| xml_etree_parse         | 159 ms                                                       | 157 ms: 1.02x faster                                                        |
| gc_traversal            | 3.63 ms                                                      | 3.58 ms: 1.01x faster                                                       |
| regex_effbot            | 3.10 ms                                                      | 3.13 ms: 1.01x slower                                                       |
| python_startup_no_site  | 7.35 ms                                                      | 7.46 ms: 1.02x slower                                                       |
| unpickle_list           | 4.45 us                                                      | 4.52 us: 1.02x slower                                                       |
| pickle_dict             | 30.4 us                                                      | 31.1 us: 1.02x slower                                                       |
| comprehensions          | 27.0 us                                                      | 27.8 us: 1.03x slower                                                       |
| Geometric mean          | (ref)                                                        | 1.20x faster                                                                |

Benchmark hidden because not significant (1): mypy2
Ignored benchmarks (6) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120.json: asyncio_tcp_ssl, asyncio_websockets, coverage, richards_super, tomli_loads, typing_runtime_protocols


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.16x
- 95% likely to have a speedup of 1.15x
- 99% likely to have a speedup of 1.14x
