
# Results vs. 3.12.0

- fork: python
- ref: 2e49bd06c5ffab7d1540
- machine: linux-x86_64
- commit hash: 2e49bd0
- commit date: 2022-04-05
- overall geometric mean: 1.07x slower \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.04x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220405-pythonperf2-x86_64-python-2e49bd06c5ffab7d1540-3.11.0a7-2e49bd0 |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| 2to3           | 285 ms                                                       | 293 ms: 1.03x slower                                                        |
| chameleon      | 7.27 ms                                                      | 7.97 ms: 1.10x slower                                                       |
| docutils       | 2.89 sec                                                     | 2.92 sec: 1.01x slower                                                      |
| Geometric mean | (ref)                                                        | 1.04x slower                                                                |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220405-pythonperf2-x86_64-python-2e49bd06c5ffab7d1540-3.11.0a7-2e49bd0 |
|-------------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| async_tree_cpu_io_mixed | 704 ms                                                       | 753 ms: 1.07x slower                                                        |
| async_tree_io           | 1.06 sec                                                     | 1.18 sec: 1.11x slower                                                      |
| async_tree_none         | 459 ms                                                       | 523 ms: 1.14x slower                                                        |
| async_tree_memoization  | 554 ms                                                       | 641 ms: 1.16x slower                                                        |
| Geometric mean          | (ref)                                                        | 1.12x slower                                                                |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220405-pythonperf2-x86_64-python-2e49bd06c5ffab7d1540-3.11.0a7-2e49bd0 |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| pidigits       | 264 ms                                                       | 251 ms: 1.05x faster                                                        |
| float          | 81.6 ms                                                      | 78.4 ms: 1.04x faster                                                       |
| nbody          | 88.2 ms                                                      | 93.6 ms: 1.06x slower                                                       |
| Geometric mean | (ref)                                                        | 1.01x faster                                                                |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220405-pythonperf2-x86_64-python-2e49bd06c5ffab7d1540-3.11.0a7-2e49bd0 |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_effbot   | 3.61 ms                                                      | 3.13 ms: 1.15x faster                                                       |
| regex_dna      | 240 ms                                                       | 253 ms: 1.05x slower                                                        |
| regex_v8       | 24.4 ms                                                      | 26.6 ms: 1.09x slower                                                       |
| regex_compile  | 145 ms                                                       | 159 ms: 1.10x slower                                                        |
| Geometric mean | (ref)                                                        | 1.02x slower                                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220405-pythonperf2-x86_64-python-2e49bd06c5ffab7d1540-3.11.0a7-2e49bd0 |
|----------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| unpickle             | 15.3 us                                                      | 13.0 us: 1.18x faster                                                       |
| xml_etree_generate   | 85.3 ms                                                      | 82.8 ms: 1.03x faster                                                       |
| unpickle_list        | 4.65 us                                                      | 4.52 us: 1.03x faster                                                       |
| pickle_dict          | 32.0 us                                                      | 31.1 us: 1.03x faster                                                       |
| pickle_list          | 4.22 us                                                      | 4.12 us: 1.02x faster                                                       |
| pickle               | 10.0 us                                                      | 9.88 us: 1.02x faster                                                       |
| json_loads           | 24.3 us                                                      | 24.5 us: 1.01x slower                                                       |
| xml_etree_iterparse  | 104 ms                                                       | 106 ms: 1.02x slower                                                        |
| pickle_pure_python   | 319 us                                                       | 331 us: 1.04x slower                                                        |
| xml_etree_parse      | 147 ms                                                       | 157 ms: 1.07x slower                                                        |
| unpickle_pure_python | 210 us                                                       | 242 us: 1.16x slower                                                        |
| json_dumps           | 10.3 ms                                                      | 13.5 ms: 1.32x slower                                                       |
| Geometric mean       | (ref)                                                        | 1.02x slower                                                                |

Benchmark hidden because not significant (1): xml_etree_process

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220405-pythonperf2-x86_64-python-2e49bd06c5ffab7d1540-3.11.0a7-2e49bd0 |
|------------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| python_startup_no_site | 8.67 ms                                                      | 7.46 ms: 1.16x faster                                                       |
| python_startup         | 11.7 ms                                                      | 10.4 ms: 1.13x faster                                                       |
| Geometric mean         | (ref)                                                        | 1.14x faster                                                                |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220405-pythonperf2-x86_64-python-2e49bd06c5ffab7d1540-3.11.0a7-2e49bd0 |
|-----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| django_template | 38.7 ms                                                      | 40.7 ms: 1.05x slower                                                       |
| mako            | 10.1 ms                                                      | 11.2 ms: 1.11x slower                                                       |
| Geometric mean  | (ref)                                                        | 1.08x slower                                                                |

All benchmarks:
===============

| Benchmark               | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220405-pythonperf2-x86_64-python-2e49bd06c5ffab7d1540-3.11.0a7-2e49bd0 |
|-------------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| async_generators        | 385 ms                                                       | 319 ms: 1.21x faster                                                        |
| unpickle                | 15.3 us                                                      | 13.0 us: 1.18x faster                                                       |
| python_startup_no_site  | 8.67 ms                                                      | 7.46 ms: 1.16x faster                                                       |
| regex_effbot            | 3.61 ms                                                      | 3.13 ms: 1.15x faster                                                       |
| unpack_sequence         | 54.5 ns                                                      | 47.3 ns: 1.15x faster                                                       |
| python_startup          | 11.7 ms                                                      | 10.4 ms: 1.13x faster                                                       |
| sqlite_synth            | 2.72 us                                                      | 2.52 us: 1.08x faster                                                       |
| bench_mp_pool           | 4.96 ms                                                      | 4.60 ms: 1.08x faster                                                       |
| dask                    | 394 ms                                                       | 367 ms: 1.07x faster                                                        |
| telco                   | 7.16 ms                                                      | 6.79 ms: 1.05x faster                                                       |
| pidigits                | 264 ms                                                       | 251 ms: 1.05x faster                                                        |
| float                   | 81.6 ms                                                      | 78.4 ms: 1.04x faster                                                       |
| gunicorn                | 1.01 ms                                                      | 968 us: 1.04x faster                                                        |
| aiohttp                 | 1.02 ms                                                      | 978 us: 1.04x faster                                                        |
| gc_traversal            | 3.70 ms                                                      | 3.58 ms: 1.03x faster                                                       |
| xml_etree_generate      | 85.3 ms                                                      | 82.8 ms: 1.03x faster                                                       |
| unpickle_list           | 4.65 us                                                      | 4.52 us: 1.03x faster                                                       |
| pickle_dict             | 32.0 us                                                      | 31.1 us: 1.03x faster                                                       |
| pickle_list             | 4.22 us                                                      | 4.12 us: 1.02x faster                                                       |
| scimark_fft             | 303 ms                                                       | 297 ms: 1.02x faster                                                        |
| pickle                  | 10.0 us                                                      | 9.88 us: 1.02x faster                                                       |
| logging_simple          | 6.64 us                                                      | 6.69 us: 1.01x slower                                                       |
| json_loads              | 24.3 us                                                      | 24.5 us: 1.01x slower                                                       |
| docutils                | 2.89 sec                                                     | 2.92 sec: 1.01x slower                                                      |
| pprint_safe_repr        | 808 ms                                                       | 818 ms: 1.01x slower                                                        |
| deepcopy_reduce         | 3.41 us                                                      | 3.48 us: 1.02x slower                                                       |
| xml_etree_iterparse     | 104 ms                                                       | 106 ms: 1.02x slower                                                        |
| pycparser               | 1.29 sec                                                     | 1.33 sec: 1.03x slower                                                      |
| 2to3                    | 285 ms                                                       | 293 ms: 1.03x slower                                                        |
| pprint_pformat          | 1.64 sec                                                     | 1.69 sec: 1.03x slower                                                      |
| pathlib                 | 18.7 ms                                                      | 19.3 ms: 1.03x slower                                                       |
| pickle_pure_python      | 319 us                                                       | 331 us: 1.04x slower                                                        |
| deepcopy                | 371 us                                                       | 385 us: 1.04x slower                                                        |
| logging_format          | 7.29 us                                                      | 7.59 us: 1.04x slower                                                       |
| create_gc_cycles        | 1.58 ms                                                      | 1.65 ms: 1.04x slower                                                       |
| pyflate                 | 442 ms                                                       | 464 ms: 1.05x slower                                                        |
| django_template         | 38.7 ms                                                      | 40.7 ms: 1.05x slower                                                       |
| sympy_integrate         | 24.0 ms                                                      | 25.3 ms: 1.05x slower                                                       |
| meteor_contest          | 126 ms                                                       | 133 ms: 1.05x slower                                                        |
| regex_dna               | 240 ms                                                       | 253 ms: 1.05x slower                                                        |
| scimark_sor             | 107 ms                                                       | 112 ms: 1.05x slower                                                        |
| sqlglot_optimize        | 58.4 ms                                                      | 61.9 ms: 1.06x slower                                                       |
| sqlglot_normalize       | 119 ms                                                       | 127 ms: 1.06x slower                                                        |
| deepcopy_memo           | 36.6 us                                                      | 38.8 us: 1.06x slower                                                       |
| nbody                   | 88.2 ms                                                      | 93.6 ms: 1.06x slower                                                       |
| bench_thread_pool       | 956 us                                                       | 1.02 ms: 1.06x slower                                                       |
| xml_etree_parse         | 147 ms                                                       | 157 ms: 1.07x slower                                                        |
| async_tree_cpu_io_mixed | 704 ms                                                       | 753 ms: 1.07x slower                                                        |
| raytrace                | 301 ms                                                       | 322 ms: 1.07x slower                                                        |
| dulwich_log             | 64.9 ms                                                      | 69.8 ms: 1.08x slower                                                       |
| mdp                     | 2.56 sec                                                     | 2.76 sec: 1.08x slower                                                      |
| sympy_str               | 305 ms                                                       | 330 ms: 1.08x slower                                                        |
| crypto_pyaes            | 82.4 ms                                                      | 89.5 ms: 1.09x slower                                                       |
| sympy_sum               | 163 ms                                                       | 177 ms: 1.09x slower                                                        |
| regex_v8                | 24.4 ms                                                      | 26.6 ms: 1.09x slower                                                       |
| chameleon               | 7.27 ms                                                      | 7.97 ms: 1.10x slower                                                       |
| regex_compile           | 145 ms                                                       | 159 ms: 1.10x slower                                                        |
| sqlalchemy_imperative   | 18.6 ms                                                      | 20.5 ms: 1.10x slower                                                       |
| scimark_monte_carlo     | 69.5 ms                                                      | 77.1 ms: 1.11x slower                                                       |
| mako                    | 10.1 ms                                                      | 11.2 ms: 1.11x slower                                                       |
| async_tree_io           | 1.06 sec                                                     | 1.18 sec: 1.11x slower                                                      |
| sympy_expand            | 492 ms                                                       | 549 ms: 1.12x slower                                                        |
| go                      | 149 ms                                                       | 166 ms: 1.12x slower                                                        |
| logging_silent          | 93.3 ns                                                      | 105 ns: 1.12x slower                                                        |
| nqueens                 | 90.1 ms                                                      | 102 ms: 1.13x slower                                                        |
| async_tree_none         | 459 ms                                                       | 523 ms: 1.14x slower                                                        |
| spectral_norm           | 93.9 ms                                                      | 107 ms: 1.14x slower                                                        |
| chaos                   | 64.1 ms                                                      | 73.4 ms: 1.15x slower                                                       |
| unpickle_pure_python    | 210 us                                                       | 242 us: 1.16x slower                                                        |
| async_tree_memoization  | 554 ms                                                       | 641 ms: 1.16x slower                                                        |
| richards                | 45.1 ms                                                      | 52.8 ms: 1.17x slower                                                       |
| scimark_lu              | 98.6 ms                                                      | 120 ms: 1.22x slower                                                        |
| fannkuch                | 362 ms                                                       | 442 ms: 1.22x slower                                                        |
| mypy2                   | 365 ms                                                       | 453 ms: 1.24x slower                                                        |
| coroutines              | 23.1 ms                                                      | 29.0 ms: 1.26x slower                                                       |
| comprehensions          | 21.8 us                                                      | 27.8 us: 1.28x slower                                                       |
| hexiom                  | 5.97 ms                                                      | 7.66 ms: 1.28x slower                                                       |
| deltablue               | 3.24 ms                                                      | 4.23 ms: 1.31x slower                                                       |
| json_dumps              | 10.3 ms                                                      | 13.5 ms: 1.32x slower                                                       |
| sqlglot_transpile       | 1.80 ms                                                      | 2.38 ms: 1.32x slower                                                       |
| sqlglot_parse           | 1.41 ms                                                      | 2.04 ms: 1.45x slower                                                       |
| generators              | 37.3 ms                                                      | 54.7 ms: 1.47x slower                                                       |
| asyncio_tcp             | 380 ms                                                       | 746 ms: 1.96x slower                                                        |
| Geometric mean          | (ref)                                                        | 1.07x slower                                                                |

Benchmark hidden because not significant (5): sqlalchemy_declarative, xml_etree_process, json, scimark_sparse_mat_mult, tornado_http
Ignored benchmarks (10) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_tcp_ssl, asyncio_websockets, coverage, richards_super, tomli_loads, typing_runtime_protocols
Ignored benchmarks (6) of results/bm-20220405-3.11.0a7-2e49bd0/bm-20220405-pythonperf2-x86_64-python-2e49bd06c5ffab7d1540-3.11.0a7-2e49bd0.json: flaskblogging, genshi_text, genshi_xml, html5lib, pylint, thrift


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.05x
- 95% likely to have a slowdown of 1.05x
- 99% likely to have a slowdown of 1.04x
