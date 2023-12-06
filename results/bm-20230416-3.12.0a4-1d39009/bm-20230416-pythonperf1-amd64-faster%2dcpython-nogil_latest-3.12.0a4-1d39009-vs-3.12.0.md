
# Results vs. 3.12.0

- fork: faster-cpython
- ref: nogil_latest
- machine: windows-amd64
- commit hash: 1d39009
- commit date: 2023-04-16
- overall geometric mean: 1.09x slower \*
- HPT reliability: 99.99%
- HPT 99th percentile: 1.04x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230416-pythonperf1-amd64-faster%2dcpython-nogil_latest-3.12.0a4-1d39009 |
|----------------|:-----------------------------------------------------------:|:----------------------------------------------------------------------------:|
| 2to3           | 214 ms                                                      | 224 ms: 1.04x slower                                                         |
| docutils       | 1.63 sec                                                    | 1.89 sec: 1.16x slower                                                       |
| Geometric mean | (ref)                                                       | 1.10x slower                                                                 |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230416-pythonperf1-amd64-faster%2dcpython-nogil_latest-3.12.0a4-1d39009 |
|----------------|:-----------------------------------------------------------:|:----------------------------------------------------------------------------:|
| float          | 55.1 ms                                                     | 49.6 ms: 1.11x faster                                                        |
| pidigits       | 150 ms                                                      | 141 ms: 1.07x faster                                                         |
| nbody          | 72.6 ms                                                     | 89.9 ms: 1.24x slower                                                        |
| Geometric mean | (ref)                                                       | 1.01x slower                                                                 |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230416-pythonperf1-amd64-faster%2dcpython-nogil_latest-3.12.0a4-1d39009 |
|----------------|:-----------------------------------------------------------:|:----------------------------------------------------------------------------:|
| regex_dna      | 124 ms                                                      | 110 ms: 1.13x faster                                                         |
| regex_effbot   | 1.62 ms                                                     | 1.53 ms: 1.06x faster                                                        |
| regex_v8       | 13.9 ms                                                     | 13.2 ms: 1.05x faster                                                        |
| regex_compile  | 88.3 ms                                                     | 96.4 ms: 1.09x slower                                                        |
| Geometric mean | (ref)                                                       | 1.04x faster                                                                 |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230416-pythonperf1-amd64-faster%2dcpython-nogil_latest-3.12.0a4-1d39009 |
|----------------------|:-----------------------------------------------------------:|:----------------------------------------------------------------------------:|
| xml_etree_parse      | 89.2 ms                                                     | 82.9 ms: 1.08x faster                                                        |
| pickle_list          | 2.86 us                                                     | 2.81 us: 1.02x faster                                                        |
| unpickle_list        | 2.78 us                                                     | 2.86 us: 1.03x slower                                                        |
| xml_etree_generate   | 55.6 ms                                                     | 57.5 ms: 1.03x slower                                                        |
| xml_etree_process    | 38.4 ms                                                     | 41.7 ms: 1.08x slower                                                        |
| json_loads           | 13.4 us                                                     | 14.6 us: 1.09x slower                                                        |
| pickle_pure_python   | 196 us                                                      | 218 us: 1.11x slower                                                         |
| unpickle             | 8.16 us                                                     | 9.19 us: 1.13x slower                                                        |
| pickle_dict          | 19.3 us                                                     | 21.8 us: 1.13x slower                                                        |
| json_dumps           | 5.60 ms                                                     | 6.50 ms: 1.16x slower                                                        |
| xml_etree_iterparse  | 62.5 ms                                                     | 74.7 ms: 1.19x slower                                                        |
| unpickle_pure_python | 133 us                                                      | 159 us: 1.20x slower                                                         |
| Geometric mean       | (ref)                                                       | 1.08x slower                                                                 |

Benchmark hidden because not significant (1): pickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230416-pythonperf1-amd64-faster%2dcpython-nogil_latest-3.12.0a4-1d39009 |
|------------------------|:-----------------------------------------------------------:|:----------------------------------------------------------------------------:|
| python_startup         | 19.5 ms                                                     | 18.2 ms: 1.07x faster                                                        |
| python_startup_no_site | 16.1 ms                                                     | 15.4 ms: 1.05x faster                                                        |
| Geometric mean         | (ref)                                                       | 1.06x faster                                                                 |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230416-pythonperf1-amd64-faster%2dcpython-nogil_latest-3.12.0a4-1d39009 |
|-----------|:-----------------------------------------------------------:|:----------------------------------------------------------------------------:|
| mako      | 6.93 ms                                                     | 8.95 ms: 1.29x slower                                                        |

All benchmarks:
===============

| Benchmark               | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230416-pythonperf1-amd64-faster%2dcpython-nogil_latest-3.12.0a4-1d39009 |
|-------------------------|:-----------------------------------------------------------:|:----------------------------------------------------------------------------:|
| async_tree_io           | 720 ms                                                      | 405 ms: 1.78x faster                                                         |
| async_tree_none         | 294 ms                                                      | 189 ms: 1.55x faster                                                         |
| async_tree_memoization  | 336 ms                                                      | 240 ms: 1.40x faster                                                         |
| sqlite_synth            | 1.76 us                                                     | 1.35 us: 1.30x faster                                                        |
| async_tree_cpu_io_mixed | 479 ms                                                      | 371 ms: 1.29x faster                                                         |
| async_generators        | 235 ms                                                      | 205 ms: 1.15x faster                                                         |
| regex_dna               | 124 ms                                                      | 110 ms: 1.13x faster                                                         |
| float                   | 55.1 ms                                                     | 49.6 ms: 1.11x faster                                                        |
| xml_etree_parse         | 89.2 ms                                                     | 82.9 ms: 1.08x faster                                                        |
| pidigits                | 150 ms                                                      | 141 ms: 1.07x faster                                                         |
| python_startup          | 19.5 ms                                                     | 18.2 ms: 1.07x faster                                                        |
| regex_effbot            | 1.62 ms                                                     | 1.53 ms: 1.06x faster                                                        |
| regex_v8                | 13.9 ms                                                     | 13.2 ms: 1.05x faster                                                        |
| python_startup_no_site  | 16.1 ms                                                     | 15.4 ms: 1.05x faster                                                        |
| pathlib                 | 77.1 ms                                                     | 73.6 ms: 1.05x faster                                                        |
| bench_mp_pool           | 66.4 ms                                                     | 63.9 ms: 1.04x faster                                                        |
| pickle_list             | 2.86 us                                                     | 2.81 us: 1.02x faster                                                        |
| pyflate                 | 297 ms                                                      | 302 ms: 1.02x slower                                                         |
| dulwich_log             | 42.4 ms                                                     | 43.6 ms: 1.03x slower                                                        |
| json                    | 2.86 ms                                                     | 2.94 ms: 1.03x slower                                                        |
| unpickle_list           | 2.78 us                                                     | 2.86 us: 1.03x slower                                                        |
| create_gc_cycles        | 727 us                                                      | 748 us: 1.03x slower                                                         |
| xml_etree_generate      | 55.6 ms                                                     | 57.5 ms: 1.03x slower                                                        |
| asyncio_tcp             | 472 ms                                                      | 489 ms: 1.04x slower                                                         |
| 2to3                    | 214 ms                                                      | 224 ms: 1.04x slower                                                         |
| gc_traversal            | 1.48 ms                                                     | 1.56 ms: 1.05x slower                                                        |
| pycparser               | 673 ms                                                      | 713 ms: 1.06x slower                                                         |
| sqlglot_optimize        | 34.4 ms                                                     | 36.8 ms: 1.07x slower                                                        |
| sqlglot_normalize       | 185 ms                                                      | 199 ms: 1.07x slower                                                         |
| nqueens                 | 61.2 ms                                                     | 65.6 ms: 1.07x slower                                                        |
| telco                   | 4.09 ms                                                     | 4.41 ms: 1.08x slower                                                        |
| xml_etree_process       | 38.4 ms                                                     | 41.7 ms: 1.08x slower                                                        |
| json_loads              | 13.4 us                                                     | 14.6 us: 1.09x slower                                                        |
| regex_compile           | 88.3 ms                                                     | 96.4 ms: 1.09x slower                                                        |
| logging_format          | 6.67 us                                                     | 7.40 us: 1.11x slower                                                        |
| crypto_pyaes            | 47.4 ms                                                     | 52.7 ms: 1.11x slower                                                        |
| pickle_pure_python      | 196 us                                                      | 218 us: 1.11x slower                                                         |
| logging_simple          | 6.21 us                                                     | 6.92 us: 1.11x slower                                                        |
| scimark_sor             | 79.6 ms                                                     | 89.1 ms: 1.12x slower                                                        |
| deepcopy_reduce         | 2.13 us                                                     | 2.40 us: 1.13x slower                                                        |
| unpickle                | 8.16 us                                                     | 9.19 us: 1.13x slower                                                        |
| mdp                     | 1.44 sec                                                    | 1.63 sec: 1.13x slower                                                       |
| deepcopy                | 240 us                                                      | 272 us: 1.13x slower                                                         |
| pickle_dict             | 19.3 us                                                     | 21.8 us: 1.13x slower                                                        |
| pprint_safe_repr        | 512 ms                                                      | 586 ms: 1.14x slower                                                         |
| docutils                | 1.63 sec                                                    | 1.89 sec: 1.16x slower                                                       |
| pprint_pformat          | 1.04 sec                                                    | 1.21 sec: 1.16x slower                                                       |
| json_dumps              | 5.60 ms                                                     | 6.50 ms: 1.16x slower                                                        |
| go                      | 88.5 ms                                                     | 103 ms: 1.16x slower                                                         |
| coverage                | 51.5 ms                                                     | 59.9 ms: 1.16x slower                                                        |
| scimark_monte_carlo     | 43.7 ms                                                     | 51.2 ms: 1.17x slower                                                        |
| meteor_contest          | 73.1 ms                                                     | 86.5 ms: 1.18x slower                                                        |
| xml_etree_iterparse     | 62.5 ms                                                     | 74.7 ms: 1.19x slower                                                        |
| unpickle_pure_python    | 133 us                                                      | 159 us: 1.20x slower                                                         |
| richards                | 26.9 ms                                                     | 32.3 ms: 1.20x slower                                                        |
| coroutines              | 14.0 ms                                                     | 16.8 ms: 1.20x slower                                                        |
| fannkuch                | 237 ms                                                      | 285 ms: 1.20x slower                                                         |
| scimark_sparse_mat_mult | 2.48 ms                                                     | 2.98 ms: 1.20x slower                                                        |
| scimark_fft             | 180 ms                                                      | 220 ms: 1.22x slower                                                         |
| bench_thread_pool       | 844 us                                                      | 1.03 ms: 1.22x slower                                                        |
| hexiom                  | 4.03 ms                                                     | 4.97 ms: 1.23x slower                                                        |
| nbody                   | 72.6 ms                                                     | 89.9 ms: 1.24x slower                                                        |
| logging_silent          | 60.6 ns                                                     | 75.0 ns: 1.24x slower                                                        |
| deepcopy_memo           | 23.8 us                                                     | 29.5 us: 1.24x slower                                                        |
| spectral_norm           | 63.2 ms                                                     | 78.8 ms: 1.25x slower                                                        |
| chaos                   | 42.8 ms                                                     | 53.7 ms: 1.26x slower                                                        |
| scimark_lu              | 58.1 ms                                                     | 73.1 ms: 1.26x slower                                                        |
| raytrace                | 191 ms                                                      | 241 ms: 1.26x slower                                                         |
| deltablue               | 2.14 ms                                                     | 2.71 ms: 1.27x slower                                                        |
| sqlglot_transpile       | 1.04 ms                                                     | 1.33 ms: 1.28x slower                                                        |
| mako                    | 6.93 ms                                                     | 8.95 ms: 1.29x slower                                                        |
| comprehensions          | 14.1 us                                                     | 19.1 us: 1.35x slower                                                        |
| sqlglot_parse           | 820 us                                                      | 1.12 ms: 1.37x slower                                                        |
| mypy2                   | 207 ms                                                      | 291 ms: 1.40x slower                                                         |
| unpack_sequence         | 37.5 ns                                                     | 55.2 ns: 1.47x slower                                                        |
| generators              | 22.7 ms                                                     | 37.5 ms: 1.65x slower                                                        |
| Geometric mean          | (ref)                                                       | 1.09x slower                                                                 |

Benchmark hidden because not significant (1): pickle
Ignored benchmarks (7) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, asyncio_tcp_ssl, dask, richards_super, tomli_loads, tornado_http, typing_runtime_protocols
Ignored benchmarks (10) of results/bm-20230416-3.12.0a4-1d39009/bm-20230416-pythonperf1-amd64-faster%2dcpython-nogil_latest-3.12.0a4-1d39009.json: chameleon, django_template, genshi_text, genshi_xml, html5lib, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 99.99% likely to be slow
- 90% likely to have a slowdown of 1.06x
- 95% likely to have a slowdown of 1.05x
- 99% likely to have a slowdown of 1.04x
