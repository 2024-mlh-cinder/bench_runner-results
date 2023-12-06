
# Results vs. 3.12.0

- fork: python
- ref: v3.11.0b3
- machine: windows-amd64
- commit hash: eb0004c
- commit date: 2022-06-01
- overall geometric mean: 1.10x slower \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.06x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220601-pythonperf1-amd64-python-v3.11.0b3-3.11.0b3-eb0004c |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| chameleon      | 4.95 ms                                                     | 5.63 ms: 1.14x slower                                           |
| docutils       | 1.61 sec                                                    | 1.66 sec: 1.03x slower                                          |
| tornado_http   | 87.2 ms                                                     | 94.8 ms: 1.09x slower                                           |
| Geometric mean | (ref)                                                       | 1.06x slower                                                    |

Benchmark hidden because not significant (1): 2to3

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220601-pythonperf1-amd64-python-v3.11.0b3-3.11.0b3-eb0004c |
|-------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| async_tree_cpu_io_mixed | 477 ms                                                      | 519 ms: 1.09x slower                                            |
| async_tree_io           | 712 ms                                                      | 781 ms: 1.10x slower                                            |
| async_tree_none         | 286 ms                                                      | 339 ms: 1.18x slower                                            |
| async_tree_memoization  | 333 ms                                                      | 402 ms: 1.21x slower                                            |
| Geometric mean          | (ref)                                                       | 1.14x slower                                                    |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220601-pythonperf1-amd64-python-v3.11.0b3-3.11.0b3-eb0004c |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| pidigits       | 150 ms                                                      | 154 ms: 1.02x slower                                            |
| float          | 54.7 ms                                                     | 57.2 ms: 1.05x slower                                           |
| nbody          | 68.8 ms                                                     | 71.9 ms: 1.05x slower                                           |
| Geometric mean | (ref)                                                       | 1.04x slower                                                    |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220601-pythonperf1-amd64-python-v3.11.0b3-3.11.0b3-eb0004c |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| regex_effbot   | 1.58 ms                                                     | 1.62 ms: 1.02x slower                                           |
| regex_dna      | 119 ms                                                      | 127 ms: 1.06x slower                                            |
| regex_compile  | 87.2 ms                                                     | 94.2 ms: 1.08x slower                                           |
| regex_v8       | 13.5 ms                                                     | 15.2 ms: 1.12x slower                                           |
| Geometric mean | (ref)                                                       | 1.07x slower                                                    |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220601-pythonperf1-amd64-python-v3.11.0b3-3.11.0b3-eb0004c |
|----------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| pickle               | 7.38 us                                                     | 6.83 us: 1.08x faster                                           |
| pickle_dict          | 18.9 us                                                     | 17.7 us: 1.07x faster                                           |
| pickle_list          | 2.88 us                                                     | 2.81 us: 1.03x faster                                           |
| unpickle             | 8.44 us                                                     | 8.33 us: 1.01x faster                                           |
| xml_etree_process    | 37.6 ms                                                     | 38.9 ms: 1.03x slower                                           |
| json_loads           | 13.6 us                                                     | 14.2 us: 1.04x slower                                           |
| xml_etree_parse      | 90.5 ms                                                     | 97.4 ms: 1.08x slower                                           |
| pickle_pure_python   | 195 us                                                      | 212 us: 1.09x slower                                            |
| unpickle_pure_python | 134 us                                                      | 158 us: 1.18x slower                                            |
| json_dumps           | 5.83 ms                                                     | 7.98 ms: 1.37x slower                                           |
| Geometric mean       | (ref)                                                       | 1.04x slower                                                    |

Benchmark hidden because not significant (3): xml_etree_generate, xml_etree_iterparse, unpickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220601-pythonperf1-amd64-python-v3.11.0b3-3.11.0b3-eb0004c |
|------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| python_startup         | 18.8 ms                                                     | 19.4 ms: 1.03x slower                                           |
| python_startup_no_site | 15.9 ms                                                     | 16.4 ms: 1.03x slower                                           |
| Geometric mean         | (ref)                                                       | 1.03x slower                                                    |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220601-pythonperf1-amd64-python-v3.11.0b3-3.11.0b3-eb0004c |
|-----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| mako            | 7.05 ms                                                     | 7.38 ms: 1.05x slower                                           |
| django_template | 22.8 ms                                                     | 25.4 ms: 1.11x slower                                           |
| Geometric mean  | (ref)                                                       | 1.08x slower                                                    |

All benchmarks:
===============

| Benchmark               | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220601-pythonperf1-amd64-python-v3.11.0b3-3.11.0b3-eb0004c |
|-------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| async_generators        | 230 ms                                                      | 192 ms: 1.20x faster                                            |
| pathlib                 | 79.6 ms                                                     | 73.6 ms: 1.08x faster                                           |
| pickle                  | 7.38 us                                                     | 6.83 us: 1.08x faster                                           |
| pickle_dict             | 18.9 us                                                     | 17.7 us: 1.07x faster                                           |
| create_gc_cycles        | 726 us                                                      | 686 us: 1.06x faster                                            |
| logging_format          | 6.72 us                                                     | 6.43 us: 1.04x faster                                           |
| logging_simple          | 6.21 us                                                     | 5.96 us: 1.04x faster                                           |
| scimark_sor             | 79.8 ms                                                     | 77.7 ms: 1.03x faster                                           |
| pickle_list             | 2.88 us                                                     | 2.81 us: 1.03x faster                                           |
| unpickle                | 8.44 us                                                     | 8.33 us: 1.01x faster                                           |
| telco                   | 4.08 ms                                                     | 4.13 ms: 1.01x slower                                           |
| sqlalchemy_declarative  | 84.5 ms                                                     | 86.0 ms: 1.02x slower                                           |
| regex_effbot            | 1.58 ms                                                     | 1.62 ms: 1.02x slower                                           |
| pidigits                | 150 ms                                                      | 154 ms: 1.02x slower                                            |
| python_startup          | 18.8 ms                                                     | 19.4 ms: 1.03x slower                                           |
| python_startup_no_site  | 15.9 ms                                                     | 16.4 ms: 1.03x slower                                           |
| xml_etree_process       | 37.6 ms                                                     | 38.9 ms: 1.03x slower                                           |
| docutils                | 1.61 sec                                                    | 1.66 sec: 1.03x slower                                          |
| json_loads              | 13.6 us                                                     | 14.2 us: 1.04x slower                                           |
| scimark_fft             | 181 ms                                                      | 188 ms: 1.04x slower                                            |
| float                   | 54.7 ms                                                     | 57.2 ms: 1.05x slower                                           |
| nbody                   | 68.8 ms                                                     | 71.9 ms: 1.05x slower                                           |
| mako                    | 7.05 ms                                                     | 7.38 ms: 1.05x slower                                           |
| sqlglot_optimize        | 34.0 ms                                                     | 35.9 ms: 1.05x slower                                           |
| scimark_monte_carlo     | 43.0 ms                                                     | 45.4 ms: 1.06x slower                                           |
| aiohttp                 | 848 us                                                      | 897 us: 1.06x slower                                            |
| regex_dna               | 119 ms                                                      | 127 ms: 1.06x slower                                            |
| deepcopy_reduce         | 2.08 us                                                     | 2.22 us: 1.06x slower                                           |
| dulwich_log             | 42.7 ms                                                     | 45.5 ms: 1.07x slower                                           |
| pprint_safe_repr        | 508 ms                                                      | 541 ms: 1.07x slower                                            |
| scimark_sparse_mat_mult | 2.51 ms                                                     | 2.68 ms: 1.07x slower                                           |
| meteor_contest          | 72.1 ms                                                     | 77.1 ms: 1.07x slower                                           |
| bench_thread_pool       | 830 us                                                      | 890 us: 1.07x slower                                            |
| xml_etree_parse         | 90.5 ms                                                     | 97.4 ms: 1.08x slower                                           |
| regex_compile           | 87.2 ms                                                     | 94.2 ms: 1.08x slower                                           |
| sqlglot_normalize       | 183 ms                                                      | 198 ms: 1.08x slower                                            |
| pyflate                 | 294 ms                                                      | 318 ms: 1.08x slower                                            |
| pprint_pformat          | 1.04 sec                                                    | 1.12 sec: 1.08x slower                                          |
| tornado_http            | 87.2 ms                                                     | 94.8 ms: 1.09x slower                                           |
| async_tree_cpu_io_mixed | 477 ms                                                      | 519 ms: 1.09x slower                                            |
| pickle_pure_python      | 195 us                                                      | 212 us: 1.09x slower                                            |
| pycparser               | 673 ms                                                      | 735 ms: 1.09x slower                                            |
| crypto_pyaes            | 46.4 ms                                                     | 50.9 ms: 1.10x slower                                           |
| async_tree_io           | 712 ms                                                      | 781 ms: 1.10x slower                                            |
| sympy_integrate         | 13.0 ms                                                     | 14.2 ms: 1.10x slower                                           |
| sympy_expand            | 278 ms                                                      | 306 ms: 1.10x slower                                            |
| dask                    | 255 ms                                                      | 281 ms: 1.10x slower                                            |
| scimark_lu              | 57.5 ms                                                     | 63.6 ms: 1.11x slower                                           |
| sympy_str               | 171 ms                                                      | 190 ms: 1.11x slower                                            |
| json                    | 2.94 ms                                                     | 3.26 ms: 1.11x slower                                           |
| coroutines              | 14.1 ms                                                     | 15.7 ms: 1.11x slower                                           |
| richards                | 27.6 ms                                                     | 30.7 ms: 1.11x slower                                           |
| deepcopy_memo           | 23.4 us                                                     | 26.0 us: 1.11x slower                                           |
| sympy_sum               | 90.1 ms                                                     | 100 ms: 1.11x slower                                            |
| django_template         | 22.8 ms                                                     | 25.4 ms: 1.11x slower                                           |
| raytrace                | 192 ms                                                      | 215 ms: 1.12x slower                                            |
| spectral_norm           | 63.9 ms                                                     | 71.4 ms: 1.12x slower                                           |
| sqlalchemy_imperative   | 9.20 ms                                                     | 10.3 ms: 1.12x slower                                           |
| regex_v8                | 13.5 ms                                                     | 15.2 ms: 1.12x slower                                           |
| fannkuch                | 244 ms                                                      | 278 ms: 1.14x slower                                            |
| chameleon               | 4.95 ms                                                     | 5.63 ms: 1.14x slower                                           |
| deepcopy                | 233 us                                                      | 265 us: 1.14x slower                                            |
| nqueens                 | 61.7 ms                                                     | 71.0 ms: 1.15x slower                                           |
| mdp                     | 1.42 sec                                                    | 1.66 sec: 1.17x slower                                          |
| go                      | 89.0 ms                                                     | 104 ms: 1.17x slower                                            |
| unpickle_pure_python    | 134 us                                                      | 158 us: 1.18x slower                                            |
| async_tree_none         | 286 ms                                                      | 339 ms: 1.18x slower                                            |
| logging_silent          | 60.5 ns                                                     | 72.7 ns: 1.20x slower                                           |
| hexiom                  | 4.00 ms                                                     | 4.82 ms: 1.20x slower                                           |
| async_tree_memoization  | 333 ms                                                      | 402 ms: 1.21x slower                                            |
| chaos                   | 42.1 ms                                                     | 51.8 ms: 1.23x slower                                           |
| deltablue               | 2.12 ms                                                     | 2.78 ms: 1.31x slower                                           |
| comprehensions          | 14.0 us                                                     | 18.7 us: 1.34x slower                                           |
| json_dumps              | 5.83 ms                                                     | 7.98 ms: 1.37x slower                                           |
| sqlglot_transpile       | 1.02 ms                                                     | 1.41 ms: 1.39x slower                                           |
| mypy2                   | 209 ms                                                      | 293 ms: 1.40x slower                                            |
| sqlglot_parse           | 802 us                                                      | 1.21 ms: 1.51x slower                                           |
| generators              | 22.6 ms                                                     | 35.4 ms: 1.57x slower                                           |
| asyncio_tcp             | 471 ms                                                      | 762 ms: 1.62x slower                                            |
| coverage                | 39.8 ms                                                     | 108 ms: 2.71x slower                                            |
| Geometric mean          | (ref)                                                       | 1.10x slower                                                    |

Benchmark hidden because not significant (8): bench_mp_pool, 2to3, sqlite_synth, unpack_sequence, gc_traversal, xml_etree_generate, xml_etree_iterparse, unpickle_list
Ignored benchmarks (8) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_tcp_ssl, richards_super, tomli_loads, typing_runtime_protocols
Ignored benchmarks (6) of results/bm-20220601-3.11.0b3-eb0004c/bm-20220601-pythonperf1-amd64-python-v3.11.0b3-3.11.0b3-eb0004c.json: flaskblogging, genshi_text, genshi_xml, html5lib, pylint, thrift


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.07x
- 95% likely to have a slowdown of 1.07x
- 99% likely to have a slowdown of 1.06x
