
# Results vs. 3.10.4

- fork: python
- ref: e2b4e4bab90b69fbd361
- machine: linux-x86_64
- commit hash: e2b4e4b
- commit date: 2021-11-05
- overall geometric mean: 1.13x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.09x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20211105-pythonperf2-x86_64-python-e2b4e4bab90b69fbd361-3.11.0a2-e2b4e4b |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| 2to3           | 349 ms                                                       | 299 ms: 1.17x faster                                                        |
| chameleon      | 9.88 ms                                                      | 9.27 ms: 1.07x faster                                                       |
| docutils       | 3.42 sec                                                     | 3.05 sec: 1.12x faster                                                      |
| html5lib       | 94.7 ms                                                      | 80.0 ms: 1.18x faster                                                       |
| tornado_http   | 157 ms                                                       | 136 ms: 1.16x faster                                                        |
| Geometric mean | (ref)                                                        | 1.14x faster                                                                |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20211105-pythonperf2-x86_64-python-e2b4e4bab90b69fbd361-3.11.0a2-e2b4e4b |
|-------------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| async_tree_none         | 700 ms                                                       | 532 ms: 1.32x faster                                                        |
| async_tree_io           | 1.61 sec                                                     | 1.27 sec: 1.27x faster                                                      |
| async_tree_memoization  | 827 ms                                                       | 668 ms: 1.24x faster                                                        |
| async_tree_cpu_io_mixed | 946 ms                                                       | 818 ms: 1.16x faster                                                        |
| Geometric mean          | (ref)                                                        | 1.24x faster                                                                |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20211105-pythonperf2-x86_64-python-e2b4e4bab90b69fbd361-3.11.0a2-e2b4e4b |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| float          | 109 ms                                                       | 86.1 ms: 1.26x faster                                                       |
| nbody          | 134 ms                                                       | 113 ms: 1.19x faster                                                        |
| pidigits       | 270 ms                                                       | 264 ms: 1.02x faster                                                        |
| Geometric mean | (ref)                                                        | 1.15x faster                                                                |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20211105-pythonperf2-x86_64-python-e2b4e4bab90b69fbd361-3.11.0a2-e2b4e4b |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_compile  | 192 ms                                                       | 158 ms: 1.22x faster                                                        |
| regex_v8       | 27.1 ms                                                      | 25.8 ms: 1.05x faster                                                       |
| regex_effbot   | 3.10 ms                                                      | 3.06 ms: 1.01x faster                                                       |
| regex_dna      | 260 ms                                                       | 262 ms: 1.01x slower                                                        |
| Geometric mean | (ref)                                                        | 1.06x faster                                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20211105-pythonperf2-x86_64-python-e2b4e4bab90b69fbd361-3.11.0a2-e2b4e4b |
|----------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| xml_etree_process    | 76.4 ms                                                      | 61.7 ms: 1.24x faster                                                       |
| json_loads           | 30.0 us                                                      | 24.7 us: 1.22x faster                                                       |
| pickle_pure_python   | 453 us                                                       | 386 us: 1.17x faster                                                        |
| unpickle_pure_python | 315 us                                                       | 277 us: 1.14x faster                                                        |
| xml_etree_generate   | 93.1 ms                                                      | 85.8 ms: 1.09x faster                                                       |
| json_dumps           | 14.2 ms                                                      | 13.4 ms: 1.06x faster                                                       |
| unpickle             | 13.9 us                                                      | 13.4 us: 1.04x faster                                                       |
| xml_etree_iterparse  | 110 ms                                                       | 107 ms: 1.02x faster                                                        |
| pickle_list          | 4.23 us                                                      | 4.17 us: 1.01x faster                                                       |
| xml_etree_parse      | 159 ms                                                       | 157 ms: 1.01x faster                                                        |
| pickle_dict          | 30.4 us                                                      | 30.2 us: 1.01x faster                                                       |
| pickle               | 10.1 us                                                      | 10.3 us: 1.02x slower                                                       |
| unpickle_list        | 4.45 us                                                      | 4.55 us: 1.02x slower                                                       |
| Geometric mean       | (ref)                                                        | 1.07x faster                                                                |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20211105-pythonperf2-x86_64-python-e2b4e4bab90b69fbd361-3.11.0a2-e2b4e4b |
|------------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| python_startup         | 11.5 ms                                                      | 11.2 ms: 1.03x faster                                                       |
| python_startup_no_site | 7.35 ms                                                      | 7.43 ms: 1.01x slower                                                       |
| Geometric mean         | (ref)                                                        | 1.01x faster                                                                |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20211105-pythonperf2-x86_64-python-e2b4e4bab90b69fbd361-3.11.0a2-e2b4e4b |
|-----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| genshi_text     | 32.3 ms                                                      | 28.2 ms: 1.15x faster                                                       |
| mako            | 14.7 ms                                                      | 12.9 ms: 1.14x faster                                                       |
| genshi_xml      | 64.1 ms                                                      | 57.9 ms: 1.11x faster                                                       |
| django_template | 51.8 ms                                                      | 47.4 ms: 1.09x faster                                                       |
| Geometric mean  | (ref)                                                        | 1.12x faster                                                                |

All benchmarks:
===============

| Benchmark               | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20211105-pythonperf2-x86_64-python-e2b4e4bab90b69fbd361-3.11.0a2-e2b4e4b |
|-------------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| deltablue               | 7.43 ms                                                      | 5.07 ms: 1.46x faster                                                       |
| raytrace                | 497 ms                                                       | 349 ms: 1.42x faster                                                        |
| logging_silent          | 168 ns                                                       | 121 ns: 1.39x faster                                                        |
| scimark_monte_carlo     | 109 ms                                                       | 79.5 ms: 1.38x faster                                                       |
| bench_mp_pool           | 6.82 ms                                                      | 5.01 ms: 1.36x faster                                                       |
| spectral_norm           | 141 ms                                                       | 104 ms: 1.36x faster                                                        |
| chaos                   | 106 ms                                                       | 79.2 ms: 1.34x faster                                                       |
| go                      | 258 ms                                                       | 194 ms: 1.33x faster                                                        |
| async_tree_none         | 700 ms                                                       | 532 ms: 1.32x faster                                                        |
| scimark_sor             | 183 ms                                                       | 140 ms: 1.31x faster                                                        |
| unpack_sequence         | 60.3 ns                                                      | 46.0 ns: 1.31x faster                                                       |
| richards                | 76.3 ms                                                      | 59.0 ms: 1.29x faster                                                       |
| async_generators        | 418 ms                                                       | 325 ms: 1.29x faster                                                        |
| async_tree_io           | 1.61 sec                                                     | 1.27 sec: 1.27x faster                                                      |
| float                   | 109 ms                                                       | 86.1 ms: 1.26x faster                                                       |
| thrift                  | 1.20 ms                                                      | 961 us: 1.25x faster                                                        |
| crypto_pyaes            | 118 ms                                                       | 94.9 ms: 1.24x faster                                                       |
| scimark_lu              | 165 ms                                                       | 132 ms: 1.24x faster                                                        |
| async_tree_memoization  | 827 ms                                                       | 668 ms: 1.24x faster                                                        |
| xml_etree_process       | 76.4 ms                                                      | 61.7 ms: 1.24x faster                                                       |
| logging_simple          | 9.06 us                                                      | 7.35 us: 1.23x faster                                                       |
| gunicorn                | 1.20 ms                                                      | 980 us: 1.23x faster                                                        |
| regex_compile           | 192 ms                                                       | 158 ms: 1.22x faster                                                        |
| json_loads              | 30.0 us                                                      | 24.7 us: 1.22x faster                                                       |
| logging_format          | 9.82 us                                                      | 8.08 us: 1.22x faster                                                       |
| hexiom                  | 9.46 ms                                                      | 7.87 ms: 1.20x faster                                                       |
| pyflate                 | 698 ms                                                       | 582 ms: 1.20x faster                                                        |
| nbody                   | 134 ms                                                       | 113 ms: 1.19x faster                                                        |
| pprint_safe_repr        | 1.04 sec                                                     | 877 ms: 1.19x faster                                                        |
| html5lib                | 94.7 ms                                                      | 80.0 ms: 1.18x faster                                                       |
| pprint_pformat          | 2.15 sec                                                     | 1.82 sec: 1.18x faster                                                      |
| deepcopy_memo           | 50.5 us                                                      | 42.9 us: 1.18x faster                                                       |
| pickle_pure_python      | 453 us                                                       | 386 us: 1.17x faster                                                        |
| 2to3                    | 349 ms                                                       | 299 ms: 1.17x faster                                                        |
| scimark_fft             | 363 ms                                                       | 311 ms: 1.17x faster                                                        |
| async_tree_cpu_io_mixed | 946 ms                                                       | 818 ms: 1.16x faster                                                        |
| tornado_http            | 157 ms                                                       | 136 ms: 1.16x faster                                                        |
| genshi_text             | 32.3 ms                                                      | 28.2 ms: 1.15x faster                                                       |
| scimark_sparse_mat_mult | 5.21 ms                                                      | 4.56 ms: 1.14x faster                                                       |
| mako                    | 14.7 ms                                                      | 12.9 ms: 1.14x faster                                                       |
| json                    | 5.91 ms                                                      | 5.19 ms: 1.14x faster                                                       |
| unpickle_pure_python    | 315 us                                                       | 277 us: 1.14x faster                                                        |
| docutils                | 3.42 sec                                                     | 3.05 sec: 1.12x faster                                                      |
| pycparser               | 1.65 sec                                                     | 1.48 sec: 1.11x faster                                                      |
| genshi_xml              | 64.1 ms                                                      | 57.9 ms: 1.11x faster                                                       |
| dulwich_log             | 80.0 ms                                                      | 72.4 ms: 1.11x faster                                                       |
| sqlglot_normalize       | 146 ms                                                       | 132 ms: 1.11x faster                                                        |
| nqueens                 | 112 ms                                                       | 102 ms: 1.10x faster                                                        |
| generators              | 57.7 ms                                                      | 52.7 ms: 1.09x faster                                                       |
| django_template         | 51.8 ms                                                      | 47.4 ms: 1.09x faster                                                       |
| xml_etree_generate      | 93.1 ms                                                      | 85.8 ms: 1.09x faster                                                       |
| bench_thread_pool       | 1.13 ms                                                      | 1.05 ms: 1.08x faster                                                       |
| sqlite_synth            | 2.97 us                                                      | 2.75 us: 1.08x faster                                                       |
| sqlglot_optimize        | 69.9 ms                                                      | 64.9 ms: 1.08x faster                                                       |
| deepcopy                | 459 us                                                       | 428 us: 1.07x faster                                                        |
| meteor_contest          | 138 ms                                                       | 128 ms: 1.07x faster                                                        |
| create_gc_cycles        | 1.79 ms                                                      | 1.67 ms: 1.07x faster                                                       |
| sympy_integrate         | 28.3 ms                                                      | 26.5 ms: 1.07x faster                                                       |
| fannkuch                | 488 ms                                                       | 458 ms: 1.07x faster                                                        |
| chameleon               | 9.88 ms                                                      | 9.27 ms: 1.07x faster                                                       |
| sympy_expand            | 599 ms                                                       | 563 ms: 1.06x faster                                                        |
| telco                   | 7.21 ms                                                      | 6.81 ms: 1.06x faster                                                       |
| json_dumps              | 14.2 ms                                                      | 13.4 ms: 1.06x faster                                                       |
| pathlib                 | 21.2 ms                                                      | 20.0 ms: 1.06x faster                                                       |
| sympy_sum               | 194 ms                                                       | 183 ms: 1.06x faster                                                        |
| dask                    | 469 ms                                                       | 445 ms: 1.05x faster                                                        |
| sympy_str               | 359 ms                                                       | 340 ms: 1.05x faster                                                        |
| regex_v8                | 27.1 ms                                                      | 25.8 ms: 1.05x faster                                                       |
| deepcopy_reduce         | 4.00 us                                                      | 3.81 us: 1.05x faster                                                       |
| coroutines              | 30.9 ms                                                      | 29.5 ms: 1.05x faster                                                       |
| unpickle                | 13.9 us                                                      | 13.4 us: 1.04x faster                                                       |
| sqlglot_transpile       | 2.73 ms                                                      | 2.63 ms: 1.04x faster                                                       |
| python_startup          | 11.5 ms                                                      | 11.2 ms: 1.03x faster                                                       |
| mdp                     | 2.94 sec                                                     | 2.87 sec: 1.02x faster                                                      |
| pidigits                | 270 ms                                                       | 264 ms: 1.02x faster                                                        |
| xml_etree_iterparse     | 110 ms                                                       | 107 ms: 1.02x faster                                                        |
| pickle_list             | 4.23 us                                                      | 4.17 us: 1.01x faster                                                       |
| xml_etree_parse         | 159 ms                                                       | 157 ms: 1.01x faster                                                        |
| sqlglot_parse           | 2.27 ms                                                      | 2.24 ms: 1.01x faster                                                       |
| regex_effbot            | 3.10 ms                                                      | 3.06 ms: 1.01x faster                                                       |
| pickle_dict             | 30.4 us                                                      | 30.2 us: 1.01x faster                                                       |
| regex_dna               | 260 ms                                                       | 262 ms: 1.01x slower                                                        |
| python_startup_no_site  | 7.35 ms                                                      | 7.43 ms: 1.01x slower                                                       |
| pickle                  | 10.1 us                                                      | 10.3 us: 1.02x slower                                                       |
| unpickle_list           | 4.45 us                                                      | 4.55 us: 1.02x slower                                                       |
| gc_traversal            | 3.63 ms                                                      | 3.77 ms: 1.04x slower                                                       |
| coverage                | 65.9 ms                                                      | 68.7 ms: 1.04x slower                                                       |
| comprehensions          | 27.0 us                                                      | 28.8 us: 1.06x slower                                                       |
| flaskblogging           | 4.44 ms                                                      | 4.84 ms: 1.09x slower                                                       |
| Geometric mean          | (ref)                                                        | 1.13x faster                                                                |
Ignored benchmarks (11) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, asyncio_tcp, asyncio_tcp_ssl, asyncio_websockets, mypy2, pylint, richards_super, sqlalchemy_declarative, sqlalchemy_imperative, tomli_loads, typing_runtime_protocols


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.10x
- 95% likely to have a speedup of 1.10x
- 99% likely to have a speedup of 1.09x
