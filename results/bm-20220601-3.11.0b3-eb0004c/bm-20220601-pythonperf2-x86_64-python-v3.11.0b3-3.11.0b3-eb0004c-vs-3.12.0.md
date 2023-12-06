
# Results vs. 3.12.0

- fork: python
- ref: v3.11.0b3
- machine: linux-x86_64
- commit hash: eb0004c
- commit date: 2022-06-01
- overall geometric mean: 1.05x slower \*
- HPT reliability: 99.93%
- HPT 99th percentile: 1.01x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220601-pythonperf2-x86_64-python-v3.11.0b3-3.11.0b3-eb0004c |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| 2to3           | 285 ms                                                       | 284 ms: 1.00x faster                                             |
| chameleon      | 7.27 ms                                                      | 7.60 ms: 1.05x slower                                            |
| docutils       | 2.89 sec                                                     | 2.83 sec: 1.02x faster                                           |
| tornado_http   | 122 ms                                                       | 119 ms: 1.03x faster                                             |
| Geometric mean | (ref)                                                        | 1.00x faster                                                     |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220601-pythonperf2-x86_64-python-v3.11.0b3-3.11.0b3-eb0004c |
|-------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| async_tree_io           | 1.06 sec                                                     | 1.17 sec: 1.10x slower                                           |
| async_tree_memoization  | 554 ms                                                       | 617 ms: 1.12x slower                                             |
| async_tree_none         | 459 ms                                                       | 513 ms: 1.12x slower                                             |
| async_tree_cpu_io_mixed | 704 ms                                                       | 810 ms: 1.15x slower                                             |
| Geometric mean          | (ref)                                                        | 1.12x slower                                                     |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220601-pythonperf2-x86_64-python-v3.11.0b3-3.11.0b3-eb0004c |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| float          | 81.6 ms                                                      | 73.9 ms: 1.11x faster                                            |
| pidigits       | 264 ms                                                       | 252 ms: 1.05x faster                                             |
| nbody          | 88.2 ms                                                      | 93.0 ms: 1.05x slower                                            |
| Geometric mean | (ref)                                                        | 1.03x faster                                                     |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220601-pythonperf2-x86_64-python-v3.11.0b3-3.11.0b3-eb0004c |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| regex_effbot   | 3.61 ms                                                      | 3.05 ms: 1.18x faster                                            |
| regex_dna      | 240 ms                                                       | 219 ms: 1.10x faster                                             |
| regex_v8       | 24.4 ms                                                      | 24.3 ms: 1.00x faster                                            |
| regex_compile  | 145 ms                                                       | 156 ms: 1.08x slower                                             |
| Geometric mean | (ref)                                                        | 1.05x faster                                                     |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220601-pythonperf2-x86_64-python-v3.11.0b3-3.11.0b3-eb0004c |
|----------------------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| unpickle             | 15.3 us                                                      | 13.2 us: 1.16x faster                                            |
| pickle_list          | 4.22 us                                                      | 3.92 us: 1.07x faster                                            |
| xml_etree_generate   | 85.3 ms                                                      | 80.2 ms: 1.06x faster                                            |
| xml_etree_process    | 58.3 ms                                                      | 55.9 ms: 1.04x faster                                            |
| pickle               | 10.0 us                                                      | 9.80 us: 1.02x faster                                            |
| pickle_dict          | 32.0 us                                                      | 31.3 us: 1.02x faster                                            |
| unpickle_list        | 4.65 us                                                      | 4.58 us: 1.01x faster                                            |
| json_loads           | 24.3 us                                                      | 25.2 us: 1.04x slower                                            |
| xml_etree_parse      | 147 ms                                                       | 153 ms: 1.04x slower                                             |
| unpickle_pure_python | 210 us                                                       | 238 us: 1.14x slower                                             |
| json_dumps           | 10.3 ms                                                      | 13.5 ms: 1.31x slower                                            |
| Geometric mean       | (ref)                                                        | 1.01x slower                                                     |

Benchmark hidden because not significant (2): xml_etree_iterparse, pickle_pure_python

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220601-pythonperf2-x86_64-python-v3.11.0b3-3.11.0b3-eb0004c |
|------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| python_startup_no_site | 8.67 ms                                                      | 7.70 ms: 1.13x faster                                            |
| python_startup         | 11.7 ms                                                      | 10.7 ms: 1.10x faster                                            |
| Geometric mean         | (ref)                                                        | 1.11x faster                                                     |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220601-pythonperf2-x86_64-python-v3.11.0b3-3.11.0b3-eb0004c |
|-----------------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| django_template | 38.7 ms                                                      | 41.4 ms: 1.07x slower                                            |
| mako            | 10.1 ms                                                      | 10.9 ms: 1.09x slower                                            |
| Geometric mean  | (ref)                                                        | 1.08x slower                                                     |

All benchmarks:
===============

| Benchmark               | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220601-pythonperf2-x86_64-python-v3.11.0b3-3.11.0b3-eb0004c |
|-------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| async_generators        | 385 ms                                                       | 318 ms: 1.21x faster                                             |
| unpack_sequence         | 54.5 ns                                                      | 45.4 ns: 1.20x faster                                            |
| regex_effbot            | 3.61 ms                                                      | 3.05 ms: 1.18x faster                                            |
| unpickle                | 15.3 us                                                      | 13.2 us: 1.16x faster                                            |
| python_startup_no_site  | 8.67 ms                                                      | 7.70 ms: 1.13x faster                                            |
| scimark_sparse_mat_mult | 4.49 ms                                                      | 4.03 ms: 1.11x faster                                            |
| float                   | 81.6 ms                                                      | 73.9 ms: 1.11x faster                                            |
| regex_dna               | 240 ms                                                       | 219 ms: 1.10x faster                                             |
| bench_mp_pool           | 4.96 ms                                                      | 4.52 ms: 1.10x faster                                            |
| python_startup          | 11.7 ms                                                      | 10.7 ms: 1.10x faster                                            |
| sqlite_synth            | 2.72 us                                                      | 2.51 us: 1.08x faster                                            |
| gunicorn                | 1.01 ms                                                      | 931 us: 1.08x faster                                             |
| pickle_list             | 4.22 us                                                      | 3.92 us: 1.07x faster                                            |
| xml_etree_generate      | 85.3 ms                                                      | 80.2 ms: 1.06x faster                                            |
| aiohttp                 | 1.02 ms                                                      | 958 us: 1.06x faster                                             |
| telco                   | 7.16 ms                                                      | 6.75 ms: 1.06x faster                                            |
| scimark_fft             | 303 ms                                                       | 286 ms: 1.06x faster                                             |
| pidigits                | 264 ms                                                       | 252 ms: 1.05x faster                                             |
| pprint_safe_repr        | 808 ms                                                       | 774 ms: 1.04x faster                                             |
| xml_etree_process       | 58.3 ms                                                      | 55.9 ms: 1.04x faster                                            |
| sqlalchemy_declarative  | 161 ms                                                       | 154 ms: 1.04x faster                                             |
| tornado_http            | 122 ms                                                       | 119 ms: 1.03x faster                                             |
| pickle                  | 10.0 us                                                      | 9.80 us: 1.02x faster                                            |
| pickle_dict             | 32.0 us                                                      | 31.3 us: 1.02x faster                                            |
| docutils                | 2.89 sec                                                     | 2.83 sec: 1.02x faster                                           |
| pprint_pformat          | 1.64 sec                                                     | 1.61 sec: 1.02x faster                                           |
| unpickle_list           | 4.65 us                                                      | 4.58 us: 1.01x faster                                            |
| regex_v8                | 24.4 ms                                                      | 24.3 ms: 1.00x faster                                            |
| 2to3                    | 285 ms                                                       | 284 ms: 1.00x faster                                             |
| pycparser               | 1.29 sec                                                     | 1.31 sec: 1.01x slower                                           |
| raytrace                | 301 ms                                                       | 304 ms: 1.01x slower                                             |
| sqlglot_optimize        | 58.4 ms                                                      | 59.4 ms: 1.02x slower                                            |
| deepcopy_reduce         | 3.41 us                                                      | 3.48 us: 1.02x slower                                            |
| pathlib                 | 18.7 ms                                                      | 19.2 ms: 1.02x slower                                            |
| crypto_pyaes            | 82.4 ms                                                      | 84.5 ms: 1.02x slower                                            |
| deepcopy_memo           | 36.6 us                                                      | 37.7 us: 1.03x slower                                            |
| spectral_norm           | 93.9 ms                                                      | 96.8 ms: 1.03x slower                                            |
| sqlglot_normalize       | 119 ms                                                       | 123 ms: 1.03x slower                                             |
| meteor_contest          | 126 ms                                                       | 131 ms: 1.04x slower                                             |
| json_loads              | 24.3 us                                                      | 25.2 us: 1.04x slower                                            |
| xml_etree_parse         | 147 ms                                                       | 153 ms: 1.04x slower                                             |
| chameleon               | 7.27 ms                                                      | 7.60 ms: 1.05x slower                                            |
| scimark_sor             | 107 ms                                                       | 112 ms: 1.05x slower                                             |
| sympy_integrate         | 24.0 ms                                                      | 25.2 ms: 1.05x slower                                            |
| deepcopy                | 371 us                                                       | 390 us: 1.05x slower                                             |
| dask                    | 394 ms                                                       | 414 ms: 1.05x slower                                             |
| sqlalchemy_imperative   | 18.6 ms                                                      | 19.6 ms: 1.05x slower                                            |
| dulwich_log             | 64.9 ms                                                      | 68.4 ms: 1.05x slower                                            |
| nbody                   | 88.2 ms                                                      | 93.0 ms: 1.05x slower                                            |
| bench_thread_pool       | 956 us                                                       | 1.01 ms: 1.06x slower                                            |
| logging_silent          | 93.3 ns                                                      | 99.3 ns: 1.06x slower                                            |
| create_gc_cycles        | 1.58 ms                                                      | 1.68 ms: 1.06x slower                                            |
| django_template         | 38.7 ms                                                      | 41.4 ms: 1.07x slower                                            |
| sympy_str               | 305 ms                                                       | 327 ms: 1.07x slower                                             |
| regex_compile           | 145 ms                                                       | 156 ms: 1.08x slower                                             |
| logging_simple          | 6.64 us                                                      | 7.16 us: 1.08x slower                                            |
| sympy_expand            | 492 ms                                                       | 531 ms: 1.08x slower                                             |
| nqueens                 | 90.1 ms                                                      | 97.6 ms: 1.08x slower                                            |
| mako                    | 10.1 ms                                                      | 10.9 ms: 1.09x slower                                            |
| gc_traversal            | 3.70 ms                                                      | 4.03 ms: 1.09x slower                                            |
| sympy_sum               | 163 ms                                                       | 177 ms: 1.09x slower                                             |
| logging_format          | 7.29 us                                                      | 7.95 us: 1.09x slower                                            |
| richards                | 45.1 ms                                                      | 49.2 ms: 1.09x slower                                            |
| mdp                     | 2.56 sec                                                     | 2.81 sec: 1.10x slower                                           |
| async_tree_io           | 1.06 sec                                                     | 1.17 sec: 1.10x slower                                           |
| go                      | 149 ms                                                       | 166 ms: 1.11x slower                                             |
| async_tree_memoization  | 554 ms                                                       | 617 ms: 1.12x slower                                             |
| scimark_lu              | 98.6 ms                                                      | 110 ms: 1.12x slower                                             |
| async_tree_none         | 459 ms                                                       | 513 ms: 1.12x slower                                             |
| unpickle_pure_python    | 210 us                                                       | 238 us: 1.14x slower                                             |
| chaos                   | 64.1 ms                                                      | 73.6 ms: 1.15x slower                                            |
| async_tree_cpu_io_mixed | 704 ms                                                       | 810 ms: 1.15x slower                                             |
| hexiom                  | 5.97 ms                                                      | 7.00 ms: 1.17x slower                                            |
| mypy2                   | 365 ms                                                       | 438 ms: 1.20x slower                                             |
| coroutines              | 23.1 ms                                                      | 27.9 ms: 1.21x slower                                            |
| sqlglot_transpile       | 1.80 ms                                                      | 2.32 ms: 1.29x slower                                            |
| deltablue               | 3.24 ms                                                      | 4.20 ms: 1.30x slower                                            |
| comprehensions          | 21.8 us                                                      | 28.3 us: 1.30x slower                                            |
| json_dumps              | 10.3 ms                                                      | 13.5 ms: 1.31x slower                                            |
| fannkuch                | 362 ms                                                       | 496 ms: 1.37x slower                                             |
| sqlglot_parse           | 1.41 ms                                                      | 1.97 ms: 1.40x slower                                            |
| generators              | 37.3 ms                                                      | 56.0 ms: 1.50x slower                                            |
| asyncio_tcp             | 380 ms                                                       | 751 ms: 1.98x slower                                             |
| Geometric mean          | (ref)                                                        | 1.05x slower                                                     |

Benchmark hidden because not significant (5): xml_etree_iterparse, pyflate, pickle_pure_python, scimark_monte_carlo, json
Ignored benchmarks (10) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_tcp_ssl, asyncio_websockets, coverage, richards_super, tomli_loads, typing_runtime_protocols
Ignored benchmarks (6) of results/bm-20220601-3.11.0b3-eb0004c/bm-20220601-pythonperf2-x86_64-python-v3.11.0b3-3.11.0b3-eb0004c.json: flaskblogging, genshi_text, genshi_xml, html5lib, pylint, thrift


# HPT report

- Reliability score: 99.93% likely to be slow
- 90% likely to have a slowdown of 1.02x
- 95% likely to have a slowdown of 1.01x
- 99% likely to have a slowdown of 1.01x
