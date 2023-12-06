
# Results vs. 3.11.0

- fork: python
- ref: v3.11.0b2
- machine: windows-amd64
- commit hash: 72f00f4
- commit date: 2022-05-30
- overall geometric mean: 1.05x slower \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.04x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20220530-pythonperf1-amd64-python-v3.11.0b2-3.11.0b2-72f00f4 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| 2to3           | 207 ms                                                      | 211 ms: 1.02x slower                                            |
| chameleon      | 5.35 ms                                                     | 5.59 ms: 1.04x slower                                           |
| docutils       | 1.59 sec                                                    | 1.66 sec: 1.04x slower                                          |
| html5lib       | 38.6 ms                                                     | 41.4 ms: 1.07x slower                                           |
| tornado_http   | 89.9 ms                                                     | 95.3 ms: 1.06x slower                                           |
| Geometric mean | (ref)                                                       | 1.05x slower                                                    |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20220530-pythonperf1-amd64-python-v3.11.0b2-3.11.0b2-72f00f4 |
|-------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| async_tree_cpu_io_mixed | 495 ms                                                      | 520 ms: 1.05x slower                                            |
| async_tree_io           | 753 ms                                                      | 794 ms: 1.05x slower                                            |
| async_tree_none         | 314 ms                                                      | 336 ms: 1.07x slower                                            |
| async_tree_memoization  | 367 ms                                                      | 400 ms: 1.09x slower                                            |
| Geometric mean          | (ref)                                                       | 1.07x slower                                                    |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20220530-pythonperf1-amd64-python-v3.11.0b2-3.11.0b2-72f00f4 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| nbody          | 69.3 ms                                                     | 70.1 ms: 1.01x slower                                           |
| pidigits       | 149 ms                                                      | 153 ms: 1.03x slower                                            |
| Geometric mean | (ref)                                                       | 1.01x slower                                                    |

Benchmark hidden because not significant (1): float

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20220530-pythonperf1-amd64-python-v3.11.0b2-3.11.0b2-72f00f4 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| regex_effbot   | 1.52 ms                                                     | 1.39 ms: 1.09x faster                                           |
| regex_dna      | 121 ms                                                      | 120 ms: 1.01x faster                                            |
| regex_v8       | 13.7 ms                                                     | 14.4 ms: 1.05x slower                                           |
| regex_compile  | 90.8 ms                                                     | 97.0 ms: 1.07x slower                                           |
| Geometric mean | (ref)                                                       | 1.00x slower                                                    |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20220530-pythonperf1-amd64-python-v3.11.0b2-3.11.0b2-72f00f4 |
|----------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| pickle_dict          | 17.8 us                                                     | 17.4 us: 1.02x faster                                           |
| xml_etree_iterparse  | 63.0 ms                                                     | 62.0 ms: 1.02x faster                                           |
| pickle_list          | 2.68 us                                                     | 2.64 us: 1.01x faster                                           |
| xml_etree_parse      | 94.5 ms                                                     | 96.7 ms: 1.02x slower                                           |
| unpickle             | 7.82 us                                                     | 8.07 us: 1.03x slower                                           |
| pickle               | 6.53 us                                                     | 6.74 us: 1.03x slower                                           |
| xml_etree_generate   | 52.2 ms                                                     | 54.1 ms: 1.04x slower                                           |
| json_dumps           | 7.90 ms                                                     | 8.21 ms: 1.04x slower                                           |
| pickle_pure_python   | 207 us                                                      | 216 us: 1.04x slower                                            |
| xml_etree_process    | 37.0 ms                                                     | 39.1 ms: 1.06x slower                                           |
| unpickle_list        | 2.57 us                                                     | 2.76 us: 1.08x slower                                           |
| unpickle_pure_python | 152 us                                                      | 164 us: 1.08x slower                                            |
| json_loads           | 12.9 us                                                     | 14.1 us: 1.09x slower                                           |
| Geometric mean       | (ref)                                                       | 1.03x slower                                                    |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20220530-pythonperf1-amd64-python-v3.11.0b2-3.11.0b2-72f00f4 |
|------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| python_startup         | 18.8 ms                                                     | 19.0 ms: 1.01x slower                                           |
| python_startup_no_site | 15.5 ms                                                     | 15.8 ms: 1.02x slower                                           |
| Geometric mean         | (ref)                                                       | 1.02x slower                                                    |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20220530-pythonperf1-amd64-python-v3.11.0b2-3.11.0b2-72f00f4 |
|-----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| genshi_text     | 17.7 ms                                                     | 17.9 ms: 1.01x slower                                           |
| django_template | 24.0 ms                                                     | 25.1 ms: 1.04x slower                                           |
| Geometric mean  | (ref)                                                       | 1.01x slower                                                    |

Benchmark hidden because not significant (2): genshi_xml, mako

All benchmarks:
===============

| Benchmark               | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20220530-pythonperf1-amd64-python-v3.11.0b2-3.11.0b2-72f00f4 |
|-------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| logging_simple          | 6.60 us                                                     | 5.94 us: 1.11x faster                                           |
| logging_format          | 7.06 us                                                     | 6.39 us: 1.10x faster                                           |
| regex_effbot            | 1.52 ms                                                     | 1.39 ms: 1.09x faster                                           |
| unpack_sequence         | 47.0 ns                                                     | 44.3 ns: 1.06x faster                                           |
| sqlite_synth            | 1.79 us                                                     | 1.71 us: 1.05x faster                                           |
| create_gc_cycles        | 706 us                                                      | 675 us: 1.05x faster                                            |
| pickle_dict             | 17.8 us                                                     | 17.4 us: 1.02x faster                                           |
| xml_etree_iterparse     | 63.0 ms                                                     | 62.0 ms: 1.02x faster                                           |
| regex_dna               | 121 ms                                                      | 120 ms: 1.01x faster                                            |
| pickle_list             | 2.68 us                                                     | 2.64 us: 1.01x faster                                           |
| sqlalchemy_declarative  | 83.9 ms                                                     | 83.2 ms: 1.01x faster                                           |
| python_startup          | 18.8 ms                                                     | 19.0 ms: 1.01x slower                                           |
| nbody                   | 69.3 ms                                                     | 70.1 ms: 1.01x slower                                           |
| genshi_text             | 17.7 ms                                                     | 17.9 ms: 1.01x slower                                           |
| raytrace                | 211 ms                                                      | 213 ms: 1.01x slower                                            |
| go                      | 98.8 ms                                                     | 100 ms: 1.01x slower                                            |
| mdp                     | 1.73 sec                                                    | 1.75 sec: 1.02x slower                                          |
| 2to3                    | 207 ms                                                      | 211 ms: 1.02x slower                                            |
| python_startup_no_site  | 15.5 ms                                                     | 15.8 ms: 1.02x slower                                           |
| logging_silent          | 70.7 ns                                                     | 72.2 ns: 1.02x slower                                           |
| xml_etree_parse         | 94.5 ms                                                     | 96.7 ms: 1.02x slower                                           |
| deepcopy_memo           | 25.5 us                                                     | 26.1 us: 1.03x slower                                           |
| richards                | 30.8 ms                                                     | 31.6 ms: 1.03x slower                                           |
| sympy_sum               | 100.0 ms                                                    | 103 ms: 1.03x slower                                            |
| telco                   | 3.93 ms                                                     | 4.05 ms: 1.03x slower                                           |
| thrift                  | 501 us                                                      | 516 us: 1.03x slower                                            |
| pidigits                | 149 ms                                                      | 153 ms: 1.03x slower                                            |
| pyflate                 | 305 ms                                                      | 314 ms: 1.03x slower                                            |
| unpickle                | 7.82 us                                                     | 8.07 us: 1.03x slower                                           |
| sympy_str               | 184 ms                                                      | 190 ms: 1.03x slower                                            |
| scimark_monte_carlo     | 44.6 ms                                                     | 46.0 ms: 1.03x slower                                           |
| pickle                  | 6.53 us                                                     | 6.74 us: 1.03x slower                                           |
| bench_mp_pool           | 61.1 ms                                                     | 63.3 ms: 1.04x slower                                           |
| async_generators        | 181 ms                                                      | 187 ms: 1.04x slower                                            |
| deltablue               | 2.63 ms                                                     | 2.72 ms: 1.04x slower                                           |
| scimark_lu              | 62.3 ms                                                     | 64.6 ms: 1.04x slower                                           |
| xml_etree_generate      | 52.2 ms                                                     | 54.1 ms: 1.04x slower                                           |
| sympy_integrate         | 13.7 ms                                                     | 14.2 ms: 1.04x slower                                           |
| json_dumps              | 7.90 ms                                                     | 8.21 ms: 1.04x slower                                           |
| pylint                  | 317 ms                                                      | 331 ms: 1.04x slower                                            |
| nqueens                 | 66.1 ms                                                     | 68.9 ms: 1.04x slower                                           |
| docutils                | 1.59 sec                                                    | 1.66 sec: 1.04x slower                                          |
| chameleon               | 5.35 ms                                                     | 5.59 ms: 1.04x slower                                           |
| pickle_pure_python      | 207 us                                                      | 216 us: 1.04x slower                                            |
| django_template         | 24.0 ms                                                     | 25.1 ms: 1.04x slower                                           |
| sympy_expand            | 299 ms                                                      | 312 ms: 1.04x slower                                            |
| dulwich_log             | 44.1 ms                                                     | 46.1 ms: 1.05x slower                                           |
| pprint_pformat          | 1.06 sec                                                    | 1.11 sec: 1.05x slower                                          |
| scimark_sor             | 76.4 ms                                                     | 80.0 ms: 1.05x slower                                           |
| bench_thread_pool       | 847 us                                                      | 889 us: 1.05x slower                                            |
| meteor_contest          | 75.0 ms                                                     | 78.7 ms: 1.05x slower                                           |
| async_tree_cpu_io_mixed | 495 ms                                                      | 520 ms: 1.05x slower                                            |
| generators              | 34.0 ms                                                     | 35.7 ms: 1.05x slower                                           |
| scimark_fft             | 181 ms                                                      | 191 ms: 1.05x slower                                            |
| async_tree_io           | 753 ms                                                      | 794 ms: 1.05x slower                                            |
| regex_v8                | 13.7 ms                                                     | 14.4 ms: 1.05x slower                                           |
| xml_etree_process       | 37.0 ms                                                     | 39.1 ms: 1.06x slower                                           |
| pprint_safe_repr        | 519 ms                                                      | 548 ms: 1.06x slower                                            |
| deepcopy_reduce         | 2.07 us                                                     | 2.19 us: 1.06x slower                                           |
| sqlglot_normalize       | 191 ms                                                      | 203 ms: 1.06x slower                                            |
| tornado_http            | 89.9 ms                                                     | 95.3 ms: 1.06x slower                                           |
| pycparser               | 705 ms                                                      | 750 ms: 1.06x slower                                            |
| coroutines              | 14.7 ms                                                     | 15.6 ms: 1.06x slower                                           |
| regex_compile           | 90.8 ms                                                     | 97.0 ms: 1.07x slower                                           |
| dask                    | 262 ms                                                      | 280 ms: 1.07x slower                                            |
| sqlglot_optimize        | 35.1 ms                                                     | 37.5 ms: 1.07x slower                                           |
| fannkuch                | 248 ms                                                      | 266 ms: 1.07x slower                                            |
| scimark_sparse_mat_mult | 2.59 ms                                                     | 2.77 ms: 1.07x slower                                           |
| async_tree_none         | 314 ms                                                      | 336 ms: 1.07x slower                                            |
| hexiom                  | 4.51 ms                                                     | 4.84 ms: 1.07x slower                                           |
| html5lib                | 38.6 ms                                                     | 41.4 ms: 1.07x slower                                           |
| unpickle_list           | 2.57 us                                                     | 2.76 us: 1.08x slower                                           |
| deepcopy                | 242 us                                                      | 261 us: 1.08x slower                                            |
| crypto_pyaes            | 48.2 ms                                                     | 51.8 ms: 1.08x slower                                           |
| unpickle_pure_python    | 152 us                                                      | 164 us: 1.08x slower                                            |
| pathlib                 | 69.4 ms                                                     | 74.8 ms: 1.08x slower                                           |
| aiohttp                 | 854 us                                                      | 921 us: 1.08x slower                                            |
| json                    | 2.99 ms                                                     | 3.23 ms: 1.08x slower                                           |
| async_tree_memoization  | 367 ms                                                      | 400 ms: 1.09x slower                                            |
| json_loads              | 12.9 us                                                     | 14.1 us: 1.09x slower                                           |
| chaos                   | 46.8 ms                                                     | 51.8 ms: 1.11x slower                                           |
| comprehensions          | 15.6 us                                                     | 18.2 us: 1.17x slower                                           |
| asyncio_tcp             | 614 ms                                                      | 742 ms: 1.21x slower                                            |
| sqlglot_transpile       | 1.15 ms                                                     | 1.42 ms: 1.24x slower                                           |
| sqlglot_parse           | 939 us                                                      | 1.21 ms: 1.28x slower                                           |
| mypy2                   | 226 ms                                                      | 295 ms: 1.30x slower                                            |
| coverage                | 43.0 ms                                                     | 106 ms: 2.46x slower                                            |
| Geometric mean          | (ref)                                                       | 1.05x slower                                                    |

Benchmark hidden because not significant (6): genshi_xml, sqlalchemy_imperative, gc_traversal, float, mako, spectral_norm
Ignored benchmarks (9) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_tcp_ssl, flaskblogging, richards_super, tomli_loads, typing_runtime_protocols


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.04x
- 95% likely to have a slowdown of 1.04x
- 99% likely to have a slowdown of 1.04x
