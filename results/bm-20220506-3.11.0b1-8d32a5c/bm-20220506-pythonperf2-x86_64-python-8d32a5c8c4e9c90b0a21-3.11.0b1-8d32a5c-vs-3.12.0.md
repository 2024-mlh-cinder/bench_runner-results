
# Results vs. 3.12.0

- fork: python
- ref: 8d32a5c8c4e9c90b0a21
- machine: linux-x86_64
- commit hash: 8d32a5c
- commit date: 2022-05-06
- overall geometric mean: 1.04x slower \*
- HPT reliability: 97.93%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220506-pythonperf2-x86_64-python-8d32a5c8c4e9c90b0a21-3.11.0b1-8d32a5c |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| 2to3           | 285 ms                                                       | 281 ms: 1.01x faster                                                        |
| chameleon      | 7.27 ms                                                      | 7.53 ms: 1.04x slower                                                       |
| docutils       | 2.89 sec                                                     | 2.82 sec: 1.02x faster                                                      |
| Geometric mean | (ref)                                                        | 1.00x faster                                                                |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220506-pythonperf2-x86_64-python-8d32a5c8c4e9c90b0a21-3.11.0b1-8d32a5c |
|-------------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| async_tree_cpu_io_mixed | 704 ms                                                       | 748 ms: 1.06x slower                                                        |
| async_tree_io           | 1.06 sec                                                     | 1.17 sec: 1.11x slower                                                      |
| async_tree_none         | 459 ms                                                       | 516 ms: 1.12x slower                                                        |
| async_tree_memoization  | 554 ms                                                       | 624 ms: 1.13x slower                                                        |
| Geometric mean          | (ref)                                                        | 1.10x slower                                                                |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220506-pythonperf2-x86_64-python-8d32a5c8c4e9c90b0a21-3.11.0b1-8d32a5c |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| float          | 81.6 ms                                                      | 74.7 ms: 1.09x faster                                                       |
| pidigits       | 264 ms                                                       | 251 ms: 1.05x faster                                                        |
| nbody          | 88.2 ms                                                      | 100 ms: 1.13x slower                                                        |
| Geometric mean | (ref)                                                        | 1.00x faster                                                                |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220506-pythonperf2-x86_64-python-8d32a5c8c4e9c90b0a21-3.11.0b1-8d32a5c |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_effbot   | 3.61 ms                                                      | 2.97 ms: 1.22x faster                                                       |
| regex_v8       | 24.4 ms                                                      | 22.8 ms: 1.07x faster                                                       |
| regex_dna      | 240 ms                                                       | 232 ms: 1.04x faster                                                        |
| regex_compile  | 145 ms                                                       | 153 ms: 1.06x slower                                                        |
| Geometric mean | (ref)                                                        | 1.06x faster                                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220506-pythonperf2-x86_64-python-8d32a5c8c4e9c90b0a21-3.11.0b1-8d32a5c |
|----------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| unpickle             | 15.3 us                                                      | 13.3 us: 1.15x faster                                                       |
| pickle_list          | 4.22 us                                                      | 3.81 us: 1.11x faster                                                       |
| pickle_dict          | 32.0 us                                                      | 29.9 us: 1.07x faster                                                       |
| xml_etree_generate   | 85.3 ms                                                      | 80.3 ms: 1.06x faster                                                       |
| pickle               | 10.0 us                                                      | 9.62 us: 1.04x faster                                                       |
| xml_etree_process    | 58.3 ms                                                      | 56.1 ms: 1.04x faster                                                       |
| unpickle_list        | 4.65 us                                                      | 4.56 us: 1.02x faster                                                       |
| xml_etree_iterparse  | 104 ms                                                       | 105 ms: 1.01x slower                                                        |
| json_loads           | 24.3 us                                                      | 24.6 us: 1.01x slower                                                       |
| xml_etree_parse      | 147 ms                                                       | 155 ms: 1.06x slower                                                        |
| unpickle_pure_python | 210 us                                                       | 233 us: 1.11x slower                                                        |
| json_dumps           | 10.3 ms                                                      | 13.5 ms: 1.32x slower                                                       |
| Geometric mean       | (ref)                                                        | 1.00x faster                                                                |

Benchmark hidden because not significant (1): pickle_pure_python

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220506-pythonperf2-x86_64-python-8d32a5c8c4e9c90b0a21-3.11.0b1-8d32a5c |
|------------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| python_startup_no_site | 8.67 ms                                                      | 7.68 ms: 1.13x faster                                                       |
| python_startup         | 11.7 ms                                                      | 10.5 ms: 1.11x faster                                                       |
| Geometric mean         | (ref)                                                        | 1.12x faster                                                                |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220506-pythonperf2-x86_64-python-8d32a5c8c4e9c90b0a21-3.11.0b1-8d32a5c |
|-----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| django_template | 38.7 ms                                                      | 41.3 ms: 1.07x slower                                                       |
| mako            | 10.1 ms                                                      | 10.9 ms: 1.08x slower                                                       |
| Geometric mean  | (ref)                                                        | 1.07x slower                                                                |

All benchmarks:
===============

| Benchmark               | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220506-pythonperf2-x86_64-python-8d32a5c8c4e9c90b0a21-3.11.0b1-8d32a5c |
|-------------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_effbot            | 3.61 ms                                                      | 2.97 ms: 1.22x faster                                                       |
| async_generators        | 385 ms                                                       | 318 ms: 1.21x faster                                                        |
| unpack_sequence         | 54.5 ns                                                      | 46.2 ns: 1.18x faster                                                       |
| unpickle                | 15.3 us                                                      | 13.3 us: 1.15x faster                                                       |
| python_startup_no_site  | 8.67 ms                                                      | 7.68 ms: 1.13x faster                                                       |
| python_startup          | 11.7 ms                                                      | 10.5 ms: 1.11x faster                                                       |
| pickle_list             | 4.22 us                                                      | 3.81 us: 1.11x faster                                                       |
| scimark_sparse_mat_mult | 4.49 ms                                                      | 4.06 ms: 1.11x faster                                                       |
| float                   | 81.6 ms                                                      | 74.7 ms: 1.09x faster                                                       |
| bench_mp_pool           | 4.96 ms                                                      | 4.56 ms: 1.09x faster                                                       |
| gunicorn                | 1.01 ms                                                      | 928 us: 1.08x faster                                                        |
| sqlite_synth            | 2.72 us                                                      | 2.51 us: 1.08x faster                                                       |
| aiohttp                 | 1.02 ms                                                      | 945 us: 1.08x faster                                                        |
| regex_v8                | 24.4 ms                                                      | 22.8 ms: 1.07x faster                                                       |
| pickle_dict             | 32.0 us                                                      | 29.9 us: 1.07x faster                                                       |
| pprint_safe_repr        | 808 ms                                                       | 755 ms: 1.07x faster                                                        |
| xml_etree_generate      | 85.3 ms                                                      | 80.3 ms: 1.06x faster                                                       |
| pidigits                | 264 ms                                                       | 251 ms: 1.05x faster                                                        |
| pprint_pformat          | 1.64 sec                                                     | 1.57 sec: 1.05x faster                                                      |
| sqlalchemy_declarative  | 161 ms                                                       | 153 ms: 1.05x faster                                                        |
| pickle                  | 10.0 us                                                      | 9.62 us: 1.04x faster                                                       |
| xml_etree_process       | 58.3 ms                                                      | 56.1 ms: 1.04x faster                                                       |
| regex_dna               | 240 ms                                                       | 232 ms: 1.04x faster                                                        |
| scimark_fft             | 303 ms                                                       | 294 ms: 1.03x faster                                                        |
| pycparser               | 1.29 sec                                                     | 1.26 sec: 1.03x faster                                                      |
| telco                   | 7.16 ms                                                      | 6.99 ms: 1.02x faster                                                       |
| docutils                | 2.89 sec                                                     | 2.82 sec: 1.02x faster                                                      |
| pyflate                 | 442 ms                                                       | 433 ms: 1.02x faster                                                        |
| unpickle_list           | 4.65 us                                                      | 4.56 us: 1.02x faster                                                       |
| 2to3                    | 285 ms                                                       | 281 ms: 1.01x faster                                                        |
| spectral_norm           | 93.9 ms                                                      | 93.1 ms: 1.01x faster                                                       |
| json                    | 5.17 ms                                                      | 5.14 ms: 1.01x faster                                                       |
| scimark_monte_carlo     | 69.5 ms                                                      | 69.2 ms: 1.01x faster                                                       |
| sqlglot_normalize       | 119 ms                                                       | 119 ms: 1.00x faster                                                        |
| pathlib                 | 18.7 ms                                                      | 18.8 ms: 1.00x slower                                                       |
| sqlglot_optimize        | 58.4 ms                                                      | 58.9 ms: 1.01x slower                                                       |
| xml_etree_iterparse     | 104 ms                                                       | 105 ms: 1.01x slower                                                        |
| json_loads              | 24.3 us                                                      | 24.6 us: 1.01x slower                                                       |
| raytrace                | 301 ms                                                       | 309 ms: 1.03x slower                                                        |
| deepcopy_memo           | 36.6 us                                                      | 37.6 us: 1.03x slower                                                       |
| scimark_sor             | 107 ms                                                       | 110 ms: 1.03x slower                                                        |
| chameleon               | 7.27 ms                                                      | 7.53 ms: 1.04x slower                                                       |
| gc_traversal            | 3.70 ms                                                      | 3.85 ms: 1.04x slower                                                       |
| meteor_contest          | 126 ms                                                       | 131 ms: 1.04x slower                                                        |
| logging_simple          | 6.64 us                                                      | 6.90 us: 1.04x slower                                                       |
| create_gc_cycles        | 1.58 ms                                                      | 1.64 ms: 1.04x slower                                                       |
| dulwich_log             | 64.9 ms                                                      | 68.0 ms: 1.05x slower                                                       |
| sympy_integrate         | 24.0 ms                                                      | 25.2 ms: 1.05x slower                                                       |
| sqlalchemy_imperative   | 18.6 ms                                                      | 19.5 ms: 1.05x slower                                                       |
| go                      | 149 ms                                                       | 156 ms: 1.05x slower                                                        |
| logging_format          | 7.29 us                                                      | 7.67 us: 1.05x slower                                                       |
| regex_compile           | 145 ms                                                       | 153 ms: 1.06x slower                                                        |
| xml_etree_parse         | 147 ms                                                       | 155 ms: 1.06x slower                                                        |
| deepcopy                | 371 us                                                       | 394 us: 1.06x slower                                                        |
| async_tree_cpu_io_mixed | 704 ms                                                       | 748 ms: 1.06x slower                                                        |
| dask                    | 394 ms                                                       | 418 ms: 1.06x slower                                                        |
| nqueens                 | 90.1 ms                                                      | 95.8 ms: 1.06x slower                                                       |
| django_template         | 38.7 ms                                                      | 41.3 ms: 1.07x slower                                                       |
| bench_thread_pool       | 956 us                                                       | 1.02 ms: 1.07x slower                                                       |
| logging_silent          | 93.3 ns                                                      | 99.8 ns: 1.07x slower                                                       |
| sympy_str               | 305 ms                                                       | 329 ms: 1.08x slower                                                        |
| mako                    | 10.1 ms                                                      | 10.9 ms: 1.08x slower                                                       |
| mdp                     | 2.56 sec                                                     | 2.78 sec: 1.09x slower                                                      |
| sympy_sum               | 163 ms                                                       | 178 ms: 1.10x slower                                                        |
| sympy_expand            | 492 ms                                                       | 540 ms: 1.10x slower                                                        |
| async_tree_io           | 1.06 sec                                                     | 1.17 sec: 1.11x slower                                                      |
| unpickle_pure_python    | 210 us                                                       | 233 us: 1.11x slower                                                        |
| richards                | 45.1 ms                                                      | 50.1 ms: 1.11x slower                                                       |
| async_tree_none         | 459 ms                                                       | 516 ms: 1.12x slower                                                        |
| async_tree_memoization  | 554 ms                                                       | 624 ms: 1.13x slower                                                        |
| chaos                   | 64.1 ms                                                      | 72.4 ms: 1.13x slower                                                       |
| nbody                   | 88.2 ms                                                      | 100 ms: 1.13x slower                                                        |
| fannkuch                | 362 ms                                                       | 418 ms: 1.16x slower                                                        |
| scimark_lu              | 98.6 ms                                                      | 114 ms: 1.16x slower                                                        |
| hexiom                  | 5.97 ms                                                      | 6.91 ms: 1.16x slower                                                       |
| mypy2                   | 365 ms                                                       | 438 ms: 1.20x slower                                                        |
| deltablue               | 3.24 ms                                                      | 3.93 ms: 1.21x slower                                                       |
| coroutines              | 23.1 ms                                                      | 28.0 ms: 1.22x slower                                                       |
| sqlglot_transpile       | 1.80 ms                                                      | 2.30 ms: 1.28x slower                                                       |
| comprehensions          | 21.8 us                                                      | 28.2 us: 1.29x slower                                                       |
| json_dumps              | 10.3 ms                                                      | 13.5 ms: 1.32x slower                                                       |
| sqlglot_parse           | 1.41 ms                                                      | 1.95 ms: 1.38x slower                                                       |
| generators              | 37.3 ms                                                      | 55.5 ms: 1.49x slower                                                       |
| asyncio_tcp             | 380 ms                                                       | 749 ms: 1.97x slower                                                        |
| Geometric mean          | (ref)                                                        | 1.04x slower                                                                |

Benchmark hidden because not significant (4): tornado_http, crypto_pyaes, pickle_pure_python, deepcopy_reduce
Ignored benchmarks (10) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_tcp_ssl, asyncio_websockets, coverage, richards_super, tomli_loads, typing_runtime_protocols
Ignored benchmarks (6) of results/bm-20220506-3.11.0b1-8d32a5c/bm-20220506-pythonperf2-x86_64-python-8d32a5c8c4e9c90b0a21-3.11.0b1-8d32a5c.json: flaskblogging, genshi_text, genshi_xml, html5lib, pylint, thrift


# HPT report

- Reliability score: 97.93% likely to be slow
- 90% likely to have a slowdown of 1.01x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
