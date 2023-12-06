
# Results vs. 3.11.0

- fork: python
- ref: v3.11.0b3
- machine: windows-amd64
- commit hash: eb0004c
- commit date: 2022-06-01
- overall geometric mean: 1.06x slower \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.03x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20220601-pythonperf1-amd64-python-v3.11.0b3-3.11.0b3-eb0004c |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| 2to3           | 207 ms                                                      | 212 ms: 1.02x slower                                            |
| chameleon      | 5.35 ms                                                     | 5.63 ms: 1.05x slower                                           |
| docutils       | 1.59 sec                                                    | 1.66 sec: 1.05x slower                                          |
| html5lib       | 38.6 ms                                                     | 41.2 ms: 1.07x slower                                           |
| tornado_http   | 89.9 ms                                                     | 94.8 ms: 1.05x slower                                           |
| Geometric mean | (ref)                                                       | 1.05x slower                                                    |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20220601-pythonperf1-amd64-python-v3.11.0b3-3.11.0b3-eb0004c |
|-------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| async_tree_io           | 753 ms                                                      | 781 ms: 1.04x slower                                            |
| async_tree_cpu_io_mixed | 495 ms                                                      | 519 ms: 1.05x slower                                            |
| async_tree_none         | 314 ms                                                      | 339 ms: 1.08x slower                                            |
| async_tree_memoization  | 367 ms                                                      | 402 ms: 1.10x slower                                            |
| Geometric mean          | (ref)                                                       | 1.07x slower                                                    |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20220601-pythonperf1-amd64-python-v3.11.0b3-3.11.0b3-eb0004c |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| pidigits       | 149 ms                                                      | 154 ms: 1.03x slower                                            |
| nbody          | 69.3 ms                                                     | 71.9 ms: 1.04x slower                                           |
| float          | 54.4 ms                                                     | 57.2 ms: 1.05x slower                                           |
| Geometric mean | (ref)                                                       | 1.04x slower                                                    |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20220601-pythonperf1-amd64-python-v3.11.0b3-3.11.0b3-eb0004c |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| regex_compile  | 90.8 ms                                                     | 94.2 ms: 1.04x slower                                           |
| regex_dna      | 121 ms                                                      | 127 ms: 1.05x slower                                            |
| regex_effbot   | 1.52 ms                                                     | 1.62 ms: 1.06x slower                                           |
| regex_v8       | 13.7 ms                                                     | 15.2 ms: 1.11x slower                                           |
| Geometric mean | (ref)                                                       | 1.06x slower                                                    |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20220601-pythonperf1-amd64-python-v3.11.0b3-3.11.0b3-eb0004c |
|----------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| json_dumps           | 7.90 ms                                                     | 7.98 ms: 1.01x slower                                           |
| pickle_pure_python   | 207 us                                                      | 212 us: 1.02x slower                                            |
| xml_etree_parse      | 94.5 ms                                                     | 97.4 ms: 1.03x slower                                           |
| unpickle_pure_python | 152 us                                                      | 158 us: 1.04x slower                                            |
| pickle               | 6.53 us                                                     | 6.83 us: 1.05x slower                                           |
| pickle_list          | 2.68 us                                                     | 2.81 us: 1.05x slower                                           |
| xml_etree_process    | 37.0 ms                                                     | 38.9 ms: 1.05x slower                                           |
| unpickle_list        | 2.57 us                                                     | 2.71 us: 1.06x slower                                           |
| unpickle             | 7.82 us                                                     | 8.33 us: 1.06x slower                                           |
| xml_etree_generate   | 52.2 ms                                                     | 55.8 ms: 1.07x slower                                           |
| json_loads           | 12.9 us                                                     | 14.2 us: 1.10x slower                                           |
| Geometric mean       | (ref)                                                       | 1.04x slower                                                    |

Benchmark hidden because not significant (2): pickle_dict, xml_etree_iterparse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20220601-pythonperf1-amd64-python-v3.11.0b3-3.11.0b3-eb0004c |
|------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| python_startup         | 18.8 ms                                                     | 19.4 ms: 1.03x slower                                           |
| python_startup_no_site | 15.5 ms                                                     | 16.4 ms: 1.06x slower                                           |
| Geometric mean         | (ref)                                                       | 1.04x slower                                                    |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20220601-pythonperf1-amd64-python-v3.11.0b3-3.11.0b3-eb0004c |
|-----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| mako            | 7.55 ms                                                     | 7.38 ms: 1.02x faster                                           |
| genshi_text     | 17.7 ms                                                     | 18.6 ms: 1.05x slower                                           |
| django_template | 24.0 ms                                                     | 25.4 ms: 1.06x slower                                           |
| Geometric mean  | (ref)                                                       | 1.02x slower                                                    |

Benchmark hidden because not significant (1): genshi_xml

All benchmarks:
===============

| Benchmark               | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20220601-pythonperf1-amd64-python-v3.11.0b3-3.11.0b3-eb0004c |
|-------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| unpack_sequence         | 47.0 ns                                                     | 36.8 ns: 1.27x faster                                           |
| logging_simple          | 6.60 us                                                     | 5.96 us: 1.11x faster                                           |
| logging_format          | 7.06 us                                                     | 6.43 us: 1.10x faster                                           |
| mdp                     | 1.73 sec                                                    | 1.66 sec: 1.04x faster                                          |
| sqlite_synth            | 1.79 us                                                     | 1.74 us: 1.03x faster                                           |
| create_gc_cycles        | 706 us                                                      | 686 us: 1.03x faster                                            |
| mako                    | 7.55 ms                                                     | 7.38 ms: 1.02x faster                                           |
| sqlalchemy_imperative   | 10.5 ms                                                     | 10.3 ms: 1.02x faster                                           |
| richards                | 30.8 ms                                                     | 30.7 ms: 1.00x faster                                           |
| json_dumps              | 7.90 ms                                                     | 7.98 ms: 1.01x slower                                           |
| flaskblogging           | 2.03 sec                                                    | 2.05 sec: 1.01x slower                                          |
| scimark_sor             | 76.4 ms                                                     | 77.7 ms: 1.02x slower                                           |
| scimark_monte_carlo     | 44.6 ms                                                     | 45.4 ms: 1.02x slower                                           |
| raytrace                | 211 ms                                                      | 215 ms: 1.02x slower                                            |
| scimark_lu              | 62.3 ms                                                     | 63.6 ms: 1.02x slower                                           |
| gc_traversal            | 1.46 ms                                                     | 1.49 ms: 1.02x slower                                           |
| deepcopy_memo           | 25.5 us                                                     | 26.0 us: 1.02x slower                                           |
| 2to3                    | 207 ms                                                      | 212 ms: 1.02x slower                                            |
| spectral_norm           | 69.9 ms                                                     | 71.4 ms: 1.02x slower                                           |
| sqlglot_optimize        | 35.1 ms                                                     | 35.9 ms: 1.02x slower                                           |
| sympy_expand            | 299 ms                                                      | 306 ms: 1.02x slower                                            |
| pickle_pure_python      | 207 us                                                      | 212 us: 1.02x slower                                            |
| sqlalchemy_declarative  | 83.9 ms                                                     | 86.0 ms: 1.03x slower                                           |
| thrift                  | 501 us                                                      | 514 us: 1.03x slower                                            |
| python_startup          | 18.8 ms                                                     | 19.4 ms: 1.03x slower                                           |
| meteor_contest          | 75.0 ms                                                     | 77.1 ms: 1.03x slower                                           |
| logging_silent          | 70.7 ns                                                     | 72.7 ns: 1.03x slower                                           |
| xml_etree_parse         | 94.5 ms                                                     | 97.4 ms: 1.03x slower                                           |
| sympy_str               | 184 ms                                                      | 190 ms: 1.03x slower                                            |
| dulwich_log             | 44.1 ms                                                     | 45.5 ms: 1.03x slower                                           |
| pidigits                | 149 ms                                                      | 154 ms: 1.03x slower                                            |
| scimark_sparse_mat_mult | 2.59 ms                                                     | 2.68 ms: 1.03x slower                                           |
| unpickle_pure_python    | 152 us                                                      | 158 us: 1.04x slower                                            |
| sqlglot_normalize       | 191 ms                                                      | 198 ms: 1.04x slower                                            |
| regex_compile           | 90.8 ms                                                     | 94.2 ms: 1.04x slower                                           |
| async_tree_io           | 753 ms                                                      | 781 ms: 1.04x slower                                            |
| sympy_integrate         | 13.7 ms                                                     | 14.2 ms: 1.04x slower                                           |
| nbody                   | 69.3 ms                                                     | 71.9 ms: 1.04x slower                                           |
| scimark_fft             | 181 ms                                                      | 188 ms: 1.04x slower                                            |
| pylint                  | 317 ms                                                      | 331 ms: 1.04x slower                                            |
| generators              | 34.0 ms                                                     | 35.4 ms: 1.04x slower                                           |
| pycparser               | 705 ms                                                      | 735 ms: 1.04x slower                                            |
| pyflate                 | 305 ms                                                      | 318 ms: 1.04x slower                                            |
| pprint_safe_repr        | 519 ms                                                      | 541 ms: 1.04x slower                                            |
| regex_dna               | 121 ms                                                      | 127 ms: 1.05x slower                                            |
| pickle                  | 6.53 us                                                     | 6.83 us: 1.05x slower                                           |
| docutils                | 1.59 sec                                                    | 1.66 sec: 1.05x slower                                          |
| async_tree_cpu_io_mixed | 495 ms                                                      | 519 ms: 1.05x slower                                            |
| pickle_list             | 2.68 us                                                     | 2.81 us: 1.05x slower                                           |
| telco                   | 3.93 ms                                                     | 4.13 ms: 1.05x slower                                           |
| bench_thread_pool       | 847 us                                                      | 890 us: 1.05x slower                                            |
| xml_etree_process       | 37.0 ms                                                     | 38.9 ms: 1.05x slower                                           |
| genshi_text             | 17.7 ms                                                     | 18.6 ms: 1.05x slower                                           |
| float                   | 54.4 ms                                                     | 57.2 ms: 1.05x slower                                           |
| chameleon               | 5.35 ms                                                     | 5.63 ms: 1.05x slower                                           |
| aiohttp                 | 854 us                                                      | 897 us: 1.05x slower                                            |
| tornado_http            | 89.9 ms                                                     | 94.8 ms: 1.05x slower                                           |
| go                      | 98.8 ms                                                     | 104 ms: 1.05x slower                                            |
| unpickle_list           | 2.57 us                                                     | 2.71 us: 1.06x slower                                           |
| crypto_pyaes            | 48.2 ms                                                     | 50.9 ms: 1.06x slower                                           |
| python_startup_no_site  | 15.5 ms                                                     | 16.4 ms: 1.06x slower                                           |
| django_template         | 24.0 ms                                                     | 25.4 ms: 1.06x slower                                           |
| pprint_pformat          | 1.06 sec                                                    | 1.12 sec: 1.06x slower                                          |
| deltablue               | 2.63 ms                                                     | 2.78 ms: 1.06x slower                                           |
| async_generators        | 181 ms                                                      | 192 ms: 1.06x slower                                            |
| pathlib                 | 69.4 ms                                                     | 73.6 ms: 1.06x slower                                           |
| unpickle                | 7.82 us                                                     | 8.33 us: 1.06x slower                                           |
| regex_effbot            | 1.52 ms                                                     | 1.62 ms: 1.06x slower                                           |
| coroutines              | 14.7 ms                                                     | 15.7 ms: 1.07x slower                                           |
| hexiom                  | 4.51 ms                                                     | 4.82 ms: 1.07x slower                                           |
| html5lib                | 38.6 ms                                                     | 41.2 ms: 1.07x slower                                           |
| xml_etree_generate      | 52.2 ms                                                     | 55.8 ms: 1.07x slower                                           |
| deepcopy_reduce         | 2.07 us                                                     | 2.22 us: 1.07x slower                                           |
| dask                    | 262 ms                                                      | 281 ms: 1.07x slower                                            |
| nqueens                 | 66.1 ms                                                     | 71.0 ms: 1.07x slower                                           |
| async_tree_none         | 314 ms                                                      | 339 ms: 1.08x slower                                            |
| json                    | 2.99 ms                                                     | 3.26 ms: 1.09x slower                                           |
| deepcopy                | 242 us                                                      | 265 us: 1.09x slower                                            |
| bench_mp_pool           | 61.1 ms                                                     | 67.0 ms: 1.10x slower                                           |
| async_tree_memoization  | 367 ms                                                      | 402 ms: 1.10x slower                                            |
| json_loads              | 12.9 us                                                     | 14.2 us: 1.10x slower                                           |
| chaos                   | 46.8 ms                                                     | 51.8 ms: 1.11x slower                                           |
| regex_v8                | 13.7 ms                                                     | 15.2 ms: 1.11x slower                                           |
| fannkuch                | 248 ms                                                      | 278 ms: 1.12x slower                                            |
| comprehensions          | 15.6 us                                                     | 18.7 us: 1.20x slower                                           |
| sqlglot_transpile       | 1.15 ms                                                     | 1.41 ms: 1.23x slower                                           |
| asyncio_tcp             | 614 ms                                                      | 762 ms: 1.24x slower                                            |
| sqlglot_parse           | 939 us                                                      | 1.21 ms: 1.29x slower                                           |
| mypy2                   | 226 ms                                                      | 293 ms: 1.29x slower                                            |
| coverage                | 43.0 ms                                                     | 108 ms: 2.50x slower                                            |
| Geometric mean          | (ref)                                                       | 1.06x slower                                                    |

Benchmark hidden because not significant (4): pickle_dict, xml_etree_iterparse, sympy_sum, genshi_xml
Ignored benchmarks (8) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_tcp_ssl, richards_super, tomli_loads, typing_runtime_protocols


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.04x
- 95% likely to have a slowdown of 1.04x
- 99% likely to have a slowdown of 1.03x
