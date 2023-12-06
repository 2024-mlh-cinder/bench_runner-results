
# Results vs. 3.12.0

- fork: python
- ref: e2b4e4bab90b69fbd361
- machine: linux-x86_64
- commit hash: e2b4e4b
- commit date: 2021-11-05
- overall geometric mean: 1.12x slower \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.09x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20211105-pythonperf2-x86_64-python-e2b4e4bab90b69fbd361-3.11.0a2-e2b4e4b |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| 2to3           | 285 ms                                                       | 299 ms: 1.05x slower                                                        |
| chameleon      | 7.27 ms                                                      | 9.27 ms: 1.28x slower                                                       |
| docutils       | 2.89 sec                                                     | 3.05 sec: 1.05x slower                                                      |
| tornado_http   | 122 ms                                                       | 136 ms: 1.11x slower                                                        |
| Geometric mean | (ref)                                                        | 1.12x slower                                                                |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20211105-pythonperf2-x86_64-python-e2b4e4bab90b69fbd361-3.11.0a2-e2b4e4b |
|-------------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| async_tree_none         | 459 ms                                                       | 532 ms: 1.16x slower                                                        |
| async_tree_cpu_io_mixed | 704 ms                                                       | 818 ms: 1.16x slower                                                        |
| async_tree_io           | 1.06 sec                                                     | 1.27 sec: 1.20x slower                                                      |
| async_tree_memoization  | 554 ms                                                       | 668 ms: 1.21x slower                                                        |
| Geometric mean          | (ref)                                                        | 1.18x slower                                                                |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20211105-pythonperf2-x86_64-python-e2b4e4bab90b69fbd361-3.11.0a2-e2b4e4b |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| float          | 81.6 ms                                                      | 86.1 ms: 1.05x slower                                                       |
| nbody          | 88.2 ms                                                      | 113 ms: 1.28x slower                                                        |
| Geometric mean | (ref)                                                        | 1.11x slower                                                                |

Benchmark hidden because not significant (1): pidigits

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20211105-pythonperf2-x86_64-python-e2b4e4bab90b69fbd361-3.11.0a2-e2b4e4b |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_effbot   | 3.61 ms                                                      | 3.06 ms: 1.18x faster                                                       |
| regex_v8       | 24.4 ms                                                      | 25.8 ms: 1.06x slower                                                       |
| regex_dna      | 240 ms                                                       | 262 ms: 1.09x slower                                                        |
| regex_compile  | 145 ms                                                       | 158 ms: 1.09x slower                                                        |
| Geometric mean | (ref)                                                        | 1.02x slower                                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20211105-pythonperf2-x86_64-python-e2b4e4bab90b69fbd361-3.11.0a2-e2b4e4b |
|----------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| unpickle             | 15.3 us                                                      | 13.4 us: 1.15x faster                                                       |
| pickle_dict          | 32.0 us                                                      | 30.2 us: 1.06x faster                                                       |
| unpickle_list        | 4.65 us                                                      | 4.55 us: 1.02x faster                                                       |
| pickle_list          | 4.22 us                                                      | 4.17 us: 1.01x faster                                                       |
| xml_etree_generate   | 85.3 ms                                                      | 85.8 ms: 1.01x slower                                                       |
| json_loads           | 24.3 us                                                      | 24.7 us: 1.01x slower                                                       |
| pickle               | 10.0 us                                                      | 10.3 us: 1.02x slower                                                       |
| xml_etree_iterparse  | 104 ms                                                       | 107 ms: 1.03x slower                                                        |
| xml_etree_process    | 58.3 ms                                                      | 61.7 ms: 1.06x slower                                                       |
| xml_etree_parse      | 147 ms                                                       | 157 ms: 1.07x slower                                                        |
| pickle_pure_python   | 319 us                                                       | 386 us: 1.21x slower                                                        |
| json_dumps           | 10.3 ms                                                      | 13.4 ms: 1.31x slower                                                       |
| unpickle_pure_python | 210 us                                                       | 277 us: 1.32x slower                                                        |
| Geometric mean       | (ref)                                                        | 1.06x slower                                                                |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20211105-pythonperf2-x86_64-python-e2b4e4bab90b69fbd361-3.11.0a2-e2b4e4b |
|------------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| python_startup_no_site | 8.67 ms                                                      | 7.43 ms: 1.17x faster                                                       |
| python_startup         | 11.7 ms                                                      | 11.2 ms: 1.05x faster                                                       |
| Geometric mean         | (ref)                                                        | 1.10x faster                                                                |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20211105-pythonperf2-x86_64-python-e2b4e4bab90b69fbd361-3.11.0a2-e2b4e4b |
|-----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| django_template | 38.7 ms                                                      | 47.4 ms: 1.22x slower                                                       |
| mako            | 10.1 ms                                                      | 12.9 ms: 1.28x slower                                                       |
| Geometric mean  | (ref)                                                        | 1.25x slower                                                                |

All benchmarks:
===============

| Benchmark               | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20211105-pythonperf2-x86_64-python-e2b4e4bab90b69fbd361-3.11.0a2-e2b4e4b |
|-------------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| unpack_sequence         | 54.5 ns                                                      | 46.0 ns: 1.18x faster                                                       |
| async_generators        | 385 ms                                                       | 325 ms: 1.18x faster                                                        |
| regex_effbot            | 3.61 ms                                                      | 3.06 ms: 1.18x faster                                                       |
| python_startup_no_site  | 8.67 ms                                                      | 7.43 ms: 1.17x faster                                                       |
| unpickle                | 15.3 us                                                      | 13.4 us: 1.15x faster                                                       |
| pickle_dict             | 32.0 us                                                      | 30.2 us: 1.06x faster                                                       |
| telco                   | 7.16 ms                                                      | 6.81 ms: 1.05x faster                                                       |
| python_startup          | 11.7 ms                                                      | 11.2 ms: 1.05x faster                                                       |
| gunicorn                | 1.01 ms                                                      | 980 us: 1.03x faster                                                        |
| unpickle_list           | 4.65 us                                                      | 4.55 us: 1.02x faster                                                       |
| pickle_list             | 4.22 us                                                      | 4.17 us: 1.01x faster                                                       |
| xml_etree_generate      | 85.3 ms                                                      | 85.8 ms: 1.01x slower                                                       |
| sqlite_synth            | 2.72 us                                                      | 2.75 us: 1.01x slower                                                       |
| meteor_contest          | 126 ms                                                       | 128 ms: 1.01x slower                                                        |
| json_loads              | 24.3 us                                                      | 24.7 us: 1.01x slower                                                       |
| scimark_sparse_mat_mult | 4.49 ms                                                      | 4.56 ms: 1.02x slower                                                       |
| gc_traversal            | 3.70 ms                                                      | 3.77 ms: 1.02x slower                                                       |
| pickle                  | 10.0 us                                                      | 10.3 us: 1.02x slower                                                       |
| scimark_fft             | 303 ms                                                       | 311 ms: 1.02x slower                                                        |
| xml_etree_iterparse     | 104 ms                                                       | 107 ms: 1.03x slower                                                        |
| coverage                | 66.3 ms                                                      | 68.7 ms: 1.04x slower                                                       |
| 2to3                    | 285 ms                                                       | 299 ms: 1.05x slower                                                        |
| docutils                | 2.89 sec                                                     | 3.05 sec: 1.05x slower                                                      |
| float                   | 81.6 ms                                                      | 86.1 ms: 1.05x slower                                                       |
| regex_v8                | 24.4 ms                                                      | 25.8 ms: 1.06x slower                                                       |
| xml_etree_process       | 58.3 ms                                                      | 61.7 ms: 1.06x slower                                                       |
| create_gc_cycles        | 1.58 ms                                                      | 1.67 ms: 1.06x slower                                                       |
| pathlib                 | 18.7 ms                                                      | 20.0 ms: 1.07x slower                                                       |
| xml_etree_parse         | 147 ms                                                       | 157 ms: 1.07x slower                                                        |
| pprint_safe_repr        | 808 ms                                                       | 877 ms: 1.09x slower                                                        |
| regex_dna               | 240 ms                                                       | 262 ms: 1.09x slower                                                        |
| regex_compile           | 145 ms                                                       | 158 ms: 1.09x slower                                                        |
| bench_thread_pool       | 956 us                                                       | 1.05 ms: 1.10x slower                                                       |
| sympy_integrate         | 24.0 ms                                                      | 26.5 ms: 1.10x slower                                                       |
| logging_simple          | 6.64 us                                                      | 7.35 us: 1.11x slower                                                       |
| pprint_pformat          | 1.64 sec                                                     | 1.82 sec: 1.11x slower                                                      |
| logging_format          | 7.29 us                                                      | 8.08 us: 1.11x slower                                                       |
| spectral_norm           | 93.9 ms                                                      | 104 ms: 1.11x slower                                                        |
| sqlglot_normalize       | 119 ms                                                       | 132 ms: 1.11x slower                                                        |
| tornado_http            | 122 ms                                                       | 136 ms: 1.11x slower                                                        |
| sqlglot_optimize        | 58.4 ms                                                      | 64.9 ms: 1.11x slower                                                       |
| dulwich_log             | 64.9 ms                                                      | 72.4 ms: 1.11x slower                                                       |
| sympy_str               | 305 ms                                                       | 340 ms: 1.12x slower                                                        |
| deepcopy_reduce         | 3.41 us                                                      | 3.81 us: 1.12x slower                                                       |
| mdp                     | 2.56 sec                                                     | 2.87 sec: 1.12x slower                                                      |
| sympy_sum               | 163 ms                                                       | 183 ms: 1.13x slower                                                        |
| nqueens                 | 90.1 ms                                                      | 102 ms: 1.13x slower                                                        |
| dask                    | 394 ms                                                       | 445 ms: 1.13x slower                                                        |
| scimark_monte_carlo     | 69.5 ms                                                      | 79.5 ms: 1.14x slower                                                       |
| pycparser               | 1.29 sec                                                     | 1.48 sec: 1.14x slower                                                      |
| sympy_expand            | 492 ms                                                       | 563 ms: 1.15x slower                                                        |
| crypto_pyaes            | 82.4 ms                                                      | 94.9 ms: 1.15x slower                                                       |
| deepcopy                | 371 us                                                       | 428 us: 1.15x slower                                                        |
| async_tree_none         | 459 ms                                                       | 532 ms: 1.16x slower                                                        |
| async_tree_cpu_io_mixed | 704 ms                                                       | 818 ms: 1.16x slower                                                        |
| raytrace                | 301 ms                                                       | 349 ms: 1.16x slower                                                        |
| deepcopy_memo           | 36.6 us                                                      | 42.9 us: 1.17x slower                                                       |
| async_tree_io           | 1.06 sec                                                     | 1.27 sec: 1.20x slower                                                      |
| async_tree_memoization  | 554 ms                                                       | 668 ms: 1.21x slower                                                        |
| pickle_pure_python      | 319 us                                                       | 386 us: 1.21x slower                                                        |
| django_template         | 38.7 ms                                                      | 47.4 ms: 1.22x slower                                                       |
| chaos                   | 64.1 ms                                                      | 79.2 ms: 1.24x slower                                                       |
| fannkuch                | 362 ms                                                       | 458 ms: 1.27x slower                                                        |
| chameleon               | 7.27 ms                                                      | 9.27 ms: 1.28x slower                                                       |
| coroutines              | 23.1 ms                                                      | 29.5 ms: 1.28x slower                                                       |
| nbody                   | 88.2 ms                                                      | 113 ms: 1.28x slower                                                        |
| mako                    | 10.1 ms                                                      | 12.9 ms: 1.28x slower                                                       |
| logging_silent          | 93.3 ns                                                      | 121 ns: 1.29x slower                                                        |
| go                      | 149 ms                                                       | 194 ms: 1.30x slower                                                        |
| scimark_sor             | 107 ms                                                       | 140 ms: 1.31x slower                                                        |
| richards                | 45.1 ms                                                      | 59.0 ms: 1.31x slower                                                       |
| json_dumps              | 10.3 ms                                                      | 13.4 ms: 1.31x slower                                                       |
| pyflate                 | 442 ms                                                       | 582 ms: 1.32x slower                                                        |
| hexiom                  | 5.97 ms                                                      | 7.87 ms: 1.32x slower                                                       |
| comprehensions          | 21.8 us                                                      | 28.8 us: 1.32x slower                                                       |
| unpickle_pure_python    | 210 us                                                       | 277 us: 1.32x slower                                                        |
| scimark_lu              | 98.6 ms                                                      | 132 ms: 1.34x slower                                                        |
| generators              | 37.3 ms                                                      | 52.7 ms: 1.41x slower                                                       |
| sqlglot_transpile       | 1.80 ms                                                      | 2.63 ms: 1.46x slower                                                       |
| deltablue               | 3.24 ms                                                      | 5.07 ms: 1.56x slower                                                       |
| sqlglot_parse           | 1.41 ms                                                      | 2.24 ms: 1.59x slower                                                       |
| Geometric mean          | (ref)                                                        | 1.12x slower                                                                |

Benchmark hidden because not significant (3): pidigits, json, bench_mp_pool
Ignored benchmarks (14) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_tcp, asyncio_tcp_ssl, asyncio_websockets, mypy2, richards_super, sqlalchemy_declarative, sqlalchemy_imperative, tomli_loads, typing_runtime_protocols
Ignored benchmarks (5) of results/bm-20211105-3.11.0a2-e2b4e4b/bm-20211105-pythonperf2-x86_64-python-e2b4e4bab90b69fbd361-3.11.0a2-e2b4e4b.json: flaskblogging, genshi_text, genshi_xml, html5lib, thrift


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.10x
- 95% likely to have a slowdown of 1.10x
- 99% likely to have a slowdown of 1.09x
