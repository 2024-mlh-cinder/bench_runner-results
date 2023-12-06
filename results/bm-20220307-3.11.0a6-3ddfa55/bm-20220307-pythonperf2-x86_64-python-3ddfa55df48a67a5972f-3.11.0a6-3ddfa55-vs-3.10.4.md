
# Results vs. 3.10.4

- fork: python
- ref: 3ddfa55df48a67a5972f
- machine: linux-x86_64
- commit hash: 3ddfa55
- commit date: 2022-03-07
- overall geometric mean: 1.14x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.10x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20220307-pythonperf2-x86_64-python-3ddfa55df48a67a5972f-3.11.0a6-3ddfa55 |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| 2to3           | 349 ms                                                       | 300 ms: 1.17x faster                                                        |
| chameleon      | 9.88 ms                                                      | 8.43 ms: 1.17x faster                                                       |
| docutils       | 3.42 sec                                                     | 2.98 sec: 1.15x faster                                                      |
| html5lib       | 94.7 ms                                                      | 75.6 ms: 1.25x faster                                                       |
| tornado_http   | 157 ms                                                       | 130 ms: 1.20x faster                                                        |
| Geometric mean | (ref)                                                        | 1.19x faster                                                                |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20220307-pythonperf2-x86_64-python-3ddfa55df48a67a5972f-3.11.0a6-3ddfa55 |
|-------------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| async_tree_io           | 1.61 sec                                                     | 1.19 sec: 1.35x faster                                                      |
| async_tree_none         | 700 ms                                                       | 532 ms: 1.32x faster                                                        |
| async_tree_memoization  | 827 ms                                                       | 651 ms: 1.27x faster                                                        |
| async_tree_cpu_io_mixed | 946 ms                                                       | 763 ms: 1.24x faster                                                        |
| Geometric mean          | (ref)                                                        | 1.29x faster                                                                |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20220307-pythonperf2-x86_64-python-3ddfa55df48a67a5972f-3.11.0a6-3ddfa55 |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| float          | 109 ms                                                       | 79.1 ms: 1.37x faster                                                       |
| nbody          | 134 ms                                                       | 98.0 ms: 1.37x faster                                                       |
| pidigits       | 270 ms                                                       | 253 ms: 1.07x faster                                                        |
| Geometric mean | (ref)                                                        | 1.26x faster                                                                |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20220307-pythonperf2-x86_64-python-3ddfa55df48a67a5972f-3.11.0a6-3ddfa55 |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_compile  | 192 ms                                                       | 161 ms: 1.20x faster                                                        |
| regex_v8       | 27.1 ms                                                      | 26.4 ms: 1.03x faster                                                       |
| regex_dna      | 260 ms                                                       | 257 ms: 1.01x faster                                                        |
| regex_effbot   | 3.10 ms                                                      | 3.49 ms: 1.13x slower                                                       |
| Geometric mean | (ref)                                                        | 1.03x faster                                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20220307-pythonperf2-x86_64-python-3ddfa55df48a67a5972f-3.11.0a6-3ddfa55 |
|----------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| xml_etree_process    | 76.4 ms                                                      | 59.4 ms: 1.29x faster                                                       |
| pickle_pure_python   | 453 us                                                       | 352 us: 1.29x faster                                                        |
| json_loads           | 30.0 us                                                      | 23.9 us: 1.25x faster                                                       |
| unpickle_pure_python | 315 us                                                       | 273 us: 1.16x faster                                                        |
| xml_etree_generate   | 93.1 ms                                                      | 83.5 ms: 1.12x faster                                                       |
| xml_etree_iterparse  | 110 ms                                                       | 104 ms: 1.05x faster                                                        |
| json_dumps           | 14.2 ms                                                      | 13.6 ms: 1.05x faster                                                       |
| xml_etree_parse      | 159 ms                                                       | 154 ms: 1.04x faster                                                        |
| unpickle             | 13.9 us                                                      | 13.5 us: 1.03x faster                                                       |
| pickle               | 10.1 us                                                      | 9.96 us: 1.01x faster                                                       |
| pickle_list          | 4.23 us                                                      | 4.28 us: 1.01x slower                                                       |
| unpickle_list        | 4.45 us                                                      | 4.68 us: 1.05x slower                                                       |
| pickle_dict          | 30.4 us                                                      | 32.2 us: 1.06x slower                                                       |
| Geometric mean       | (ref)                                                        | 1.08x faster                                                                |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20220307-pythonperf2-x86_64-python-3ddfa55df48a67a5972f-3.11.0a6-3ddfa55 |
|------------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| python_startup         | 11.5 ms                                                      | 10.4 ms: 1.11x faster                                                       |
| python_startup_no_site | 7.35 ms                                                      | 7.55 ms: 1.03x slower                                                       |
| Geometric mean         | (ref)                                                        | 1.04x faster                                                                |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20220307-pythonperf2-x86_64-python-3ddfa55df48a67a5972f-3.11.0a6-3ddfa55 |
|-----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| mako            | 14.7 ms                                                      | 11.4 ms: 1.29x faster                                                       |
| genshi_text     | 32.3 ms                                                      | 26.5 ms: 1.22x faster                                                       |
| django_template | 51.8 ms                                                      | 43.8 ms: 1.18x faster                                                       |
| genshi_xml      | 64.1 ms                                                      | 60.7 ms: 1.06x faster                                                       |
| Geometric mean  | (ref)                                                        | 1.18x faster                                                                |

All benchmarks:
===============

| Benchmark               | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20220307-pythonperf2-x86_64-python-3ddfa55df48a67a5972f-3.11.0a6-3ddfa55 |
|-------------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| deltablue               | 7.43 ms                                                      | 4.49 ms: 1.65x faster                                                       |
| scimark_sor             | 183 ms                                                       | 121 ms: 1.52x faster                                                        |
| scimark_monte_carlo     | 109 ms                                                       | 74.4 ms: 1.47x faster                                                       |
| logging_silent          | 168 ns                                                       | 115 ns: 1.46x faster                                                        |
| go                      | 258 ms                                                       | 178 ms: 1.45x faster                                                        |
| raytrace                | 497 ms                                                       | 343 ms: 1.45x faster                                                        |
| bench_mp_pool           | 6.82 ms                                                      | 4.80 ms: 1.42x faster                                                       |
| pyflate                 | 698 ms                                                       | 494 ms: 1.41x faster                                                        |
| float                   | 109 ms                                                       | 79.1 ms: 1.37x faster                                                       |
| nbody                   | 134 ms                                                       | 98.0 ms: 1.37x faster                                                       |
| chaos                   | 106 ms                                                       | 77.5 ms: 1.37x faster                                                       |
| richards                | 76.3 ms                                                      | 55.9 ms: 1.37x faster                                                       |
| scimark_lu              | 165 ms                                                       | 122 ms: 1.35x faster                                                        |
| async_tree_io           | 1.61 sec                                                     | 1.19 sec: 1.35x faster                                                      |
| async_tree_none         | 700 ms                                                       | 532 ms: 1.32x faster                                                        |
| async_generators        | 418 ms                                                       | 320 ms: 1.31x faster                                                        |
| xml_etree_process       | 76.4 ms                                                      | 59.4 ms: 1.29x faster                                                       |
| mako                    | 14.7 ms                                                      | 11.4 ms: 1.29x faster                                                       |
| pickle_pure_python      | 453 us                                                       | 352 us: 1.29x faster                                                        |
| logging_simple          | 9.06 us                                                      | 7.08 us: 1.28x faster                                                       |
| spectral_norm           | 141 ms                                                       | 111 ms: 1.28x faster                                                        |
| async_tree_memoization  | 827 ms                                                       | 651 ms: 1.27x faster                                                        |
| logging_format          | 9.82 us                                                      | 7.75 us: 1.27x faster                                                       |
| crypto_pyaes            | 118 ms                                                       | 93.5 ms: 1.26x faster                                                       |
| json_loads              | 30.0 us                                                      | 23.9 us: 1.25x faster                                                       |
| html5lib                | 94.7 ms                                                      | 75.6 ms: 1.25x faster                                                       |
| async_tree_cpu_io_mixed | 946 ms                                                       | 763 ms: 1.24x faster                                                        |
| hexiom                  | 9.46 ms                                                      | 7.74 ms: 1.22x faster                                                       |
| pprint_safe_repr        | 1.04 sec                                                     | 853 ms: 1.22x faster                                                        |
| genshi_text             | 32.3 ms                                                      | 26.5 ms: 1.22x faster                                                       |
| pprint_pformat          | 2.15 sec                                                     | 1.77 sec: 1.21x faster                                                      |
| deepcopy_memo           | 50.5 us                                                      | 41.7 us: 1.21x faster                                                       |
| thrift                  | 1.20 ms                                                      | 991 us: 1.21x faster                                                        |
| gunicorn                | 1.20 ms                                                      | 994 us: 1.21x faster                                                        |
| aiohttp                 | 1.21 ms                                                      | 1.00 ms: 1.21x faster                                                       |
| tornado_http            | 157 ms                                                       | 130 ms: 1.20x faster                                                        |
| regex_compile           | 192 ms                                                       | 161 ms: 1.20x faster                                                        |
| scimark_fft             | 363 ms                                                       | 305 ms: 1.19x faster                                                        |
| django_template         | 51.8 ms                                                      | 43.8 ms: 1.18x faster                                                       |
| json                    | 5.91 ms                                                      | 5.04 ms: 1.17x faster                                                       |
| chameleon               | 9.88 ms                                                      | 8.43 ms: 1.17x faster                                                       |
| sqlite_synth            | 2.97 us                                                      | 2.54 us: 1.17x faster                                                       |
| 2to3                    | 349 ms                                                       | 300 ms: 1.17x faster                                                        |
| unpickle_pure_python    | 315 us                                                       | 273 us: 1.16x faster                                                        |
| sqlalchemy_declarative  | 189 ms                                                       | 164 ms: 1.15x faster                                                        |
| pycparser               | 1.65 sec                                                     | 1.43 sec: 1.15x faster                                                      |
| scimark_sparse_mat_mult | 5.21 ms                                                      | 4.53 ms: 1.15x faster                                                       |
| docutils                | 3.42 sec                                                     | 2.98 sec: 1.15x faster                                                      |
| sqlglot_normalize       | 146 ms                                                       | 131 ms: 1.12x faster                                                        |
| xml_etree_generate      | 93.1 ms                                                      | 83.5 ms: 1.12x faster                                                       |
| nqueens                 | 112 ms                                                       | 100 ms: 1.11x faster                                                        |
| deepcopy                | 459 us                                                       | 413 us: 1.11x faster                                                        |
| flaskblogging           | 4.44 ms                                                      | 3.99 ms: 1.11x faster                                                       |
| python_startup          | 11.5 ms                                                      | 10.4 ms: 1.11x faster                                                       |
| create_gc_cycles        | 1.79 ms                                                      | 1.63 ms: 1.10x faster                                                       |
| sqlalchemy_imperative   | 23.0 ms                                                      | 21.0 ms: 1.10x faster                                                       |
| sqlglot_optimize        | 69.9 ms                                                      | 63.7 ms: 1.10x faster                                                       |
| pathlib                 | 21.2 ms                                                      | 19.3 ms: 1.09x faster                                                       |
| sympy_integrate         | 28.3 ms                                                      | 25.9 ms: 1.09x faster                                                       |
| sqlglot_transpile       | 2.73 ms                                                      | 2.50 ms: 1.09x faster                                                       |
| bench_thread_pool       | 1.13 ms                                                      | 1.04 ms: 1.09x faster                                                       |
| dulwich_log             | 80.0 ms                                                      | 73.8 ms: 1.08x faster                                                       |
| fannkuch                | 488 ms                                                       | 453 ms: 1.08x faster                                                        |
| deepcopy_reduce         | 4.00 us                                                      | 3.73 us: 1.07x faster                                                       |
| pidigits                | 270 ms                                                       | 253 ms: 1.07x faster                                                        |
| sqlglot_parse           | 2.27 ms                                                      | 2.13 ms: 1.07x faster                                                       |
| dask                    | 469 ms                                                       | 442 ms: 1.06x faster                                                        |
| genshi_xml              | 64.1 ms                                                      | 60.7 ms: 1.06x faster                                                       |
| sympy_sum               | 194 ms                                                       | 184 ms: 1.05x faster                                                        |
| generators              | 57.7 ms                                                      | 54.8 ms: 1.05x faster                                                       |
| xml_etree_iterparse     | 110 ms                                                       | 104 ms: 1.05x faster                                                        |
| telco                   | 7.21 ms                                                      | 6.90 ms: 1.05x faster                                                       |
| sympy_str               | 359 ms                                                       | 343 ms: 1.05x faster                                                        |
| json_dumps              | 14.2 ms                                                      | 13.6 ms: 1.05x faster                                                       |
| sympy_expand            | 599 ms                                                       | 573 ms: 1.04x faster                                                        |
| meteor_contest          | 138 ms                                                       | 133 ms: 1.04x faster                                                        |
| asyncio_tcp             | 785 ms                                                       | 757 ms: 1.04x faster                                                        |
| xml_etree_parse         | 159 ms                                                       | 154 ms: 1.04x faster                                                        |
| unpickle                | 13.9 us                                                      | 13.5 us: 1.03x faster                                                       |
| regex_v8                | 27.1 ms                                                      | 26.4 ms: 1.03x faster                                                       |
| coroutines              | 30.9 ms                                                      | 30.1 ms: 1.03x faster                                                       |
| regex_dna               | 260 ms                                                       | 257 ms: 1.01x faster                                                        |
| pickle                  | 10.1 us                                                      | 9.96 us: 1.01x faster                                                       |
| mdp                     | 2.94 sec                                                     | 2.91 sec: 1.01x faster                                                      |
| pickle_list             | 4.23 us                                                      | 4.28 us: 1.01x slower                                                       |
| python_startup_no_site  | 7.35 ms                                                      | 7.55 ms: 1.03x slower                                                       |
| unpickle_list           | 4.45 us                                                      | 4.68 us: 1.05x slower                                                       |
| pickle_dict             | 30.4 us                                                      | 32.2 us: 1.06x slower                                                       |
| comprehensions          | 27.0 us                                                      | 29.6 us: 1.09x slower                                                       |
| gc_traversal            | 3.63 ms                                                      | 4.03 ms: 1.11x slower                                                       |
| regex_effbot            | 3.10 ms                                                      | 3.49 ms: 1.13x slower                                                       |
| coverage                | 65.9 ms                                                      | 84.1 ms: 1.28x slower                                                       |
| unpack_sequence         | 60.3 ns                                                      | 152 ns: 2.52x slower                                                        |
| Geometric mean          | (ref)                                                        | 1.14x faster                                                                |
Ignored benchmarks (7) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120.json: asyncio_tcp_ssl, asyncio_websockets, mypy2, pylint, richards_super, tomli_loads, typing_runtime_protocols


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.12x
- 95% likely to have a speedup of 1.11x
- 99% likely to have a speedup of 1.10x
