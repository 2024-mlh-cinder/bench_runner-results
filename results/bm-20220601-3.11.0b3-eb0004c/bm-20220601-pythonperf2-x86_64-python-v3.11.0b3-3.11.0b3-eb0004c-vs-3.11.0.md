
# Results vs. 3.11.0

- fork: python
- ref: v3.11.0b3
- machine: linux-x86_64
- commit hash: eb0004c
- commit date: 2022-06-01
- overall geometric mean: 1.00x faster \*
- HPT reliability: 97.47%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20220601-pythonperf2-x86_64-python-v3.11.0b3-3.11.0b3-eb0004c |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| 2to3           | 286 ms                                                       | 284 ms: 1.01x faster                                             |
| chameleon      | 7.42 ms                                                      | 7.60 ms: 1.02x slower                                            |
| docutils       | 2.87 sec                                                     | 2.83 sec: 1.01x faster                                           |
| tornado_http   | 125 ms                                                       | 119 ms: 1.05x faster                                             |
| Geometric mean | (ref)                                                        | 1.01x faster                                                     |

Benchmark hidden because not significant (1): html5lib

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20220601-pythonperf2-x86_64-python-v3.11.0b3-3.11.0b3-eb0004c |
|-------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| async_tree_memoization  | 648 ms                                                       | 617 ms: 1.05x faster                                             |
| async_tree_none         | 529 ms                                                       | 513 ms: 1.03x faster                                             |
| async_tree_io           | 1.19 sec                                                     | 1.17 sec: 1.02x faster                                           |
| async_tree_cpu_io_mixed | 762 ms                                                       | 810 ms: 1.06x slower                                             |
| Geometric mean          | (ref)                                                        | 1.01x faster                                                     |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20220601-pythonperf2-x86_64-python-v3.11.0b3-3.11.0b3-eb0004c |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| nbody          | 95.8 ms                                                      | 93.0 ms: 1.03x faster                                            |
| float          | 76.0 ms                                                      | 73.9 ms: 1.03x faster                                            |
| pidigits       | 251 ms                                                       | 252 ms: 1.00x slower                                             |
| Geometric mean | (ref)                                                        | 1.02x faster                                                     |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20220601-pythonperf2-x86_64-python-v3.11.0b3-3.11.0b3-eb0004c |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| regex_effbot   | 3.42 ms                                                      | 3.05 ms: 1.12x faster                                            |
| regex_dna      | 226 ms                                                       | 219 ms: 1.03x faster                                             |
| regex_compile  | 157 ms                                                       | 156 ms: 1.01x faster                                             |
| regex_v8       | 23.7 ms                                                      | 24.3 ms: 1.03x slower                                            |
| Geometric mean | (ref)                                                        | 1.03x faster                                                     |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20220601-pythonperf2-x86_64-python-v3.11.0b3-3.11.0b3-eb0004c |
|----------------------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| json_loads           | 29.0 us                                                      | 25.2 us: 1.15x faster                                            |
| xml_etree_parse      | 159 ms                                                       | 153 ms: 1.03x faster                                             |
| xml_etree_iterparse  | 106 ms                                                       | 103 ms: 1.03x faster                                             |
| pickle_dict          | 31.8 us                                                      | 31.3 us: 1.01x faster                                            |
| xml_etree_process    | 56.1 ms                                                      | 55.9 ms: 1.00x faster                                            |
| xml_etree_generate   | 80.5 ms                                                      | 80.2 ms: 1.00x faster                                            |
| pickle_list          | 3.89 us                                                      | 3.92 us: 1.01x slower                                            |
| unpickle_pure_python | 236 us                                                       | 238 us: 1.01x slower                                             |
| unpickle_list        | 4.47 us                                                      | 4.58 us: 1.03x slower                                            |
| Geometric mean       | (ref)                                                        | 1.01x faster                                                     |

Benchmark hidden because not significant (4): json_dumps, unpickle, pickle_pure_python, pickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20220601-pythonperf2-x86_64-python-v3.11.0b3-3.11.0b3-eb0004c |
|------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| python_startup         | 10.8 ms                                                      | 10.7 ms: 1.01x faster                                            |
| python_startup_no_site | 7.78 ms                                                      | 7.70 ms: 1.01x faster                                            |
| Geometric mean         | (ref)                                                        | 1.01x faster                                                     |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20220601-pythonperf2-x86_64-python-v3.11.0b3-3.11.0b3-eb0004c |
|-----------------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| genshi_text     | 26.1 ms                                                      | 26.3 ms: 1.01x slower                                            |
| django_template | 40.4 ms                                                      | 41.4 ms: 1.02x slower                                            |
| genshi_xml      | 57.2 ms                                                      | 60.1 ms: 1.05x slower                                            |
| Geometric mean  | (ref)                                                        | 1.02x slower                                                     |

Benchmark hidden because not significant (1): mako

All benchmarks:
===============

| Benchmark               | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20220601-pythonperf2-x86_64-python-v3.11.0b3-3.11.0b3-eb0004c |
|-------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| json_loads              | 29.0 us                                                      | 25.2 us: 1.15x faster                                            |
| regex_effbot            | 3.42 ms                                                      | 3.05 ms: 1.12x faster                                            |
| json                    | 5.59 ms                                                      | 5.20 ms: 1.08x faster                                            |
| gunicorn                | 986 us                                                       | 931 us: 1.06x faster                                             |
| tornado_http            | 125 ms                                                       | 119 ms: 1.05x faster                                             |
| async_tree_memoization  | 648 ms                                                       | 617 ms: 1.05x faster                                             |
| scimark_lu              | 115 ms                                                       | 110 ms: 1.05x faster                                             |
| sympy_sum               | 184 ms                                                       | 177 ms: 1.04x faster                                             |
| sympy_expand            | 550 ms                                                       | 531 ms: 1.04x faster                                             |
| thrift                  | 941 us                                                       | 909 us: 1.04x faster                                             |
| xml_etree_parse         | 159 ms                                                       | 153 ms: 1.03x faster                                             |
| regex_dna               | 226 ms                                                       | 219 ms: 1.03x faster                                             |
| nbody                   | 95.8 ms                                                      | 93.0 ms: 1.03x faster                                            |
| async_tree_none         | 529 ms                                                       | 513 ms: 1.03x faster                                             |
| float                   | 76.0 ms                                                      | 73.9 ms: 1.03x faster                                            |
| xml_etree_iterparse     | 106 ms                                                       | 103 ms: 1.03x faster                                             |
| aiohttp                 | 984 us                                                       | 958 us: 1.03x faster                                             |
| logging_silent          | 102 ns                                                       | 99.3 ns: 1.03x faster                                            |
| sympy_str               | 336 ms                                                       | 327 ms: 1.03x faster                                             |
| pyflate                 | 453 ms                                                       | 441 ms: 1.03x faster                                             |
| flaskblogging           | 3.92 ms                                                      | 3.82 ms: 1.03x faster                                            |
| telco                   | 6.91 ms                                                      | 6.75 ms: 1.02x faster                                            |
| bench_mp_pool           | 4.63 ms                                                      | 4.52 ms: 1.02x faster                                            |
| async_tree_io           | 1.19 sec                                                     | 1.17 sec: 1.02x faster                                           |
| sqlalchemy_imperative   | 19.9 ms                                                      | 19.6 ms: 1.02x faster                                            |
| sympy_integrate         | 25.6 ms                                                      | 25.2 ms: 1.02x faster                                            |
| nqueens                 | 99.2 ms                                                      | 97.6 ms: 1.02x faster                                            |
| scimark_monte_carlo     | 70.6 ms                                                      | 69.5 ms: 1.01x faster                                            |
| python_startup          | 10.8 ms                                                      | 10.7 ms: 1.01x faster                                            |
| richards                | 49.9 ms                                                      | 49.2 ms: 1.01x faster                                            |
| pickle_dict             | 31.8 us                                                      | 31.3 us: 1.01x faster                                            |
| async_generators        | 322 ms                                                       | 318 ms: 1.01x faster                                             |
| docutils                | 2.87 sec                                                     | 2.83 sec: 1.01x faster                                           |
| raytrace                | 308 ms                                                       | 304 ms: 1.01x faster                                             |
| pprint_pformat          | 1.63 sec                                                     | 1.61 sec: 1.01x faster                                           |
| python_startup_no_site  | 7.78 ms                                                      | 7.70 ms: 1.01x faster                                            |
| gc_traversal            | 4.06 ms                                                      | 4.03 ms: 1.01x faster                                            |
| regex_compile           | 157 ms                                                       | 156 ms: 1.01x faster                                             |
| 2to3                    | 286 ms                                                       | 284 ms: 1.01x faster                                             |
| generators              | 56.4 ms                                                      | 56.0 ms: 1.01x faster                                            |
| logging_simple          | 7.21 us                                                      | 7.16 us: 1.01x faster                                            |
| pprint_safe_repr        | 780 ms                                                       | 774 ms: 1.01x faster                                             |
| xml_etree_process       | 56.1 ms                                                      | 55.9 ms: 1.00x faster                                            |
| xml_etree_generate      | 80.5 ms                                                      | 80.2 ms: 1.00x faster                                            |
| pidigits                | 251 ms                                                       | 252 ms: 1.00x slower                                             |
| hexiom                  | 6.97 ms                                                      | 7.00 ms: 1.00x slower                                            |
| meteor_contest          | 130 ms                                                       | 131 ms: 1.00x slower                                             |
| pickle_list             | 3.89 us                                                      | 3.92 us: 1.01x slower                                            |
| unpickle_pure_python    | 236 us                                                       | 238 us: 1.01x slower                                             |
| sqlite_synth            | 2.49 us                                                      | 2.51 us: 1.01x slower                                            |
| genshi_text             | 26.1 ms                                                      | 26.3 ms: 1.01x slower                                            |
| deepcopy_memo           | 37.3 us                                                      | 37.7 us: 1.01x slower                                            |
| sqlglot_normalize       | 122 ms                                                       | 123 ms: 1.01x slower                                             |
| unpack_sequence         | 44.9 ns                                                      | 45.4 ns: 1.01x slower                                            |
| logging_format          | 7.83 us                                                      | 7.95 us: 1.02x slower                                            |
| scimark_fft             | 281 ms                                                       | 286 ms: 1.02x slower                                             |
| pycparser               | 1.28 sec                                                     | 1.31 sec: 1.02x slower                                           |
| django_template         | 40.4 ms                                                      | 41.4 ms: 1.02x slower                                            |
| scimark_sor             | 109 ms                                                       | 112 ms: 1.02x slower                                             |
| chameleon               | 7.42 ms                                                      | 7.60 ms: 1.02x slower                                            |
| unpickle_list           | 4.47 us                                                      | 4.58 us: 1.03x slower                                            |
| chaos                   | 71.6 ms                                                      | 73.6 ms: 1.03x slower                                            |
| regex_v8                | 23.7 ms                                                      | 24.3 ms: 1.03x slower                                            |
| spectral_norm           | 94.0 ms                                                      | 96.8 ms: 1.03x slower                                            |
| deepcopy_reduce         | 3.37 us                                                      | 3.48 us: 1.03x slower                                            |
| crypto_pyaes            | 81.8 ms                                                      | 84.5 ms: 1.03x slower                                            |
| mdp                     | 2.72 sec                                                     | 2.81 sec: 1.04x slower                                           |
| deltablue               | 4.03 ms                                                      | 4.20 ms: 1.04x slower                                            |
| genshi_xml              | 57.2 ms                                                      | 60.1 ms: 1.05x slower                                            |
| create_gc_cycles        | 1.59 ms                                                      | 1.68 ms: 1.05x slower                                            |
| async_tree_cpu_io_mixed | 762 ms                                                       | 810 ms: 1.06x slower                                             |
| fannkuch                | 457 ms                                                       | 496 ms: 1.08x slower                                             |
| comprehensions          | 24.8 us                                                      | 28.3 us: 1.14x slower                                            |
| sqlglot_transpile       | 1.94 ms                                                      | 2.32 ms: 1.20x slower                                            |
| sqlglot_parse           | 1.55 ms                                                      | 1.97 ms: 1.27x slower                                            |
| Geometric mean          | (ref)                                                        | 1.00x faster                                                     |

Benchmark hidden because not significant (19): mypy2, pylint, dask, bench_thread_pool, mako, sqlalchemy_declarative, scimark_sparse_mat_mult, asyncio_tcp, go, coroutines, pathlib, json_dumps, unpickle, pickle_pure_python, sqlglot_optimize, dulwich_log, deepcopy, pickle, html5lib
Ignored benchmarks (10) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_tcp_ssl, asyncio_websockets, coverage, richards_super, tomli_loads, typing_runtime_protocols


# HPT report

- Reliability score: 97.47% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
