
# Results vs. 3.11.0

- fork: python
- ref: v3.11.0b2
- machine: linux-x86_64
- commit hash: 72f00f4
- commit date: 2022-05-30
- overall geometric mean: 1.01x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20220530-pythonperf2-x86_64-python-v3.11.0b2-3.11.0b2-72f00f4 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| 2to3           | 286 ms                                                       | 282 ms: 1.01x faster                                             |
| chameleon      | 7.42 ms                                                      | 7.52 ms: 1.01x slower                                            |
| docutils       | 2.87 sec                                                     | 2.83 sec: 1.01x faster                                           |
| tornado_http   | 125 ms                                                       | 117 ms: 1.06x faster                                             |
| Geometric mean | (ref)                                                        | 1.02x faster                                                     |

Benchmark hidden because not significant (1): html5lib

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20220530-pythonperf2-x86_64-python-v3.11.0b2-3.11.0b2-72f00f4 |
|-------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| async_tree_memoization  | 648 ms                                                       | 609 ms: 1.06x faster                                             |
| async_tree_none         | 529 ms                                                       | 511 ms: 1.03x faster                                             |
| async_tree_cpu_io_mixed | 762 ms                                                       | 740 ms: 1.03x faster                                             |
| async_tree_io           | 1.19 sec                                                     | 1.16 sec: 1.02x faster                                           |
| Geometric mean          | (ref)                                                        | 1.04x faster                                                     |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20220530-pythonperf2-x86_64-python-v3.11.0b2-3.11.0b2-72f00f4 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| float          | 76.0 ms                                                      | 73.8 ms: 1.03x faster                                            |
| Geometric mean | (ref)                                                        | 1.01x faster                                                     |

Benchmark hidden because not significant (2): pidigits, nbody

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20220530-pythonperf2-x86_64-python-v3.11.0b2-3.11.0b2-72f00f4 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| regex_effbot   | 3.42 ms                                                      | 3.11 ms: 1.10x faster                                            |
| regex_compile  | 157 ms                                                       | 157 ms: 1.00x faster                                             |
| regex_dna      | 226 ms                                                       | 227 ms: 1.00x slower                                             |
| regex_v8       | 23.7 ms                                                      | 24.1 ms: 1.02x slower                                            |
| Geometric mean | (ref)                                                        | 1.02x faster                                                     |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20220530-pythonperf2-x86_64-python-v3.11.0b2-3.11.0b2-72f00f4 |
|----------------------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| json_loads           | 29.0 us                                                      | 25.1 us: 1.15x faster                                            |
| pickle_dict          | 31.8 us                                                      | 30.4 us: 1.04x faster                                            |
| xml_etree_parse      | 159 ms                                                       | 153 ms: 1.04x faster                                             |
| xml_etree_generate   | 80.5 ms                                                      | 79.0 ms: 1.02x faster                                            |
| json_dumps           | 13.5 ms                                                      | 13.3 ms: 1.01x faster                                            |
| pickle_list          | 3.89 us                                                      | 3.86 us: 1.01x faster                                            |
| unpickle_pure_python | 236 us                                                       | 234 us: 1.01x faster                                             |
| xml_etree_process    | 56.1 ms                                                      | 55.8 ms: 1.01x faster                                            |
| pickle_pure_python   | 318 us                                                       | 320 us: 1.01x slower                                             |
| unpickle_list        | 4.47 us                                                      | 4.57 us: 1.02x slower                                            |
| Geometric mean       | (ref)                                                        | 1.02x faster                                                     |

Benchmark hidden because not significant (3): xml_etree_iterparse, pickle, unpickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20220530-pythonperf2-x86_64-python-v3.11.0b2-3.11.0b2-72f00f4 |
|------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| python_startup         | 10.8 ms                                                      | 10.7 ms: 1.02x faster                                            |
| python_startup_no_site | 7.78 ms                                                      | 7.70 ms: 1.01x faster                                            |
| Geometric mean         | (ref)                                                        | 1.01x faster                                                     |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20220530-pythonperf2-x86_64-python-v3.11.0b2-3.11.0b2-72f00f4 |
|-----------------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| genshi_text     | 26.1 ms                                                      | 24.4 ms: 1.07x faster                                            |
| django_template | 40.4 ms                                                      | 39.5 ms: 1.02x faster                                            |
| genshi_xml      | 57.2 ms                                                      | 56.0 ms: 1.02x faster                                            |
| Geometric mean  | (ref)                                                        | 1.03x faster                                                     |

Benchmark hidden because not significant (1): mako

All benchmarks:
===============

| Benchmark               | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20220530-pythonperf2-x86_64-python-v3.11.0b2-3.11.0b2-72f00f4 |
|-------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| json_loads              | 29.0 us                                                      | 25.1 us: 1.15x faster                                            |
| regex_effbot            | 3.42 ms                                                      | 3.11 ms: 1.10x faster                                            |
| json                    | 5.59 ms                                                      | 5.16 ms: 1.08x faster                                            |
| go                      | 166 ms                                                       | 154 ms: 1.07x faster                                             |
| genshi_text             | 26.1 ms                                                      | 24.4 ms: 1.07x faster                                            |
| tornado_http            | 125 ms                                                       | 117 ms: 1.06x faster                                             |
| async_tree_memoization  | 648 ms                                                       | 609 ms: 1.06x faster                                             |
| gunicorn                | 986 us                                                       | 929 us: 1.06x faster                                             |
| pyflate                 | 453 ms                                                       | 431 ms: 1.05x faster                                             |
| scimark_monte_carlo     | 70.6 ms                                                      | 67.5 ms: 1.05x faster                                            |
| pickle_dict             | 31.8 us                                                      | 30.4 us: 1.04x faster                                            |
| sympy_sum               | 184 ms                                                       | 177 ms: 1.04x faster                                             |
| aiohttp                 | 984 us                                                       | 944 us: 1.04x faster                                             |
| pprint_pformat          | 1.63 sec                                                     | 1.57 sec: 1.04x faster                                           |
| scimark_lu              | 115 ms                                                       | 111 ms: 1.04x faster                                             |
| xml_etree_parse         | 159 ms                                                       | 153 ms: 1.04x faster                                             |
| async_tree_none         | 529 ms                                                       | 511 ms: 1.03x faster                                             |
| sympy_expand            | 550 ms                                                       | 533 ms: 1.03x faster                                             |
| logging_silent          | 102 ns                                                       | 98.9 ns: 1.03x faster                                            |
| gc_traversal            | 4.06 ms                                                      | 3.94 ms: 1.03x faster                                            |
| float                   | 76.0 ms                                                      | 73.8 ms: 1.03x faster                                            |
| async_tree_cpu_io_mixed | 762 ms                                                       | 740 ms: 1.03x faster                                             |
| sympy_str               | 336 ms                                                       | 327 ms: 1.03x faster                                             |
| richards                | 49.9 ms                                                      | 48.5 ms: 1.03x faster                                            |
| sqlalchemy_imperative   | 19.9 ms                                                      | 19.4 ms: 1.03x faster                                            |
| pprint_safe_repr        | 780 ms                                                       | 759 ms: 1.03x faster                                             |
| async_generators        | 322 ms                                                       | 313 ms: 1.03x faster                                             |
| django_template         | 40.4 ms                                                      | 39.5 ms: 1.02x faster                                            |
| sympy_integrate         | 25.6 ms                                                      | 25.0 ms: 1.02x faster                                            |
| fannkuch                | 457 ms                                                       | 447 ms: 1.02x faster                                             |
| async_tree_io           | 1.19 sec                                                     | 1.16 sec: 1.02x faster                                           |
| pylint                  | 521 ms                                                       | 510 ms: 1.02x faster                                             |
| generators              | 56.4 ms                                                      | 55.2 ms: 1.02x faster                                            |
| genshi_xml              | 57.2 ms                                                      | 56.0 ms: 1.02x faster                                            |
| xml_etree_generate      | 80.5 ms                                                      | 79.0 ms: 1.02x faster                                            |
| scimark_sor             | 109 ms                                                       | 108 ms: 1.02x faster                                             |
| dask                    | 417 ms                                                       | 410 ms: 1.02x faster                                             |
| dulwich_log             | 68.3 ms                                                      | 67.2 ms: 1.02x faster                                            |
| python_startup          | 10.8 ms                                                      | 10.7 ms: 1.02x faster                                            |
| docutils                | 2.87 sec                                                     | 2.83 sec: 1.01x faster                                           |
| nqueens                 | 99.2 ms                                                      | 97.7 ms: 1.01x faster                                            |
| 2to3                    | 286 ms                                                       | 282 ms: 1.01x faster                                             |
| sqlalchemy_declarative  | 155 ms                                                       | 153 ms: 1.01x faster                                             |
| deltablue               | 4.03 ms                                                      | 3.98 ms: 1.01x faster                                            |
| python_startup_no_site  | 7.78 ms                                                      | 7.70 ms: 1.01x faster                                            |
| json_dumps              | 13.5 ms                                                      | 13.3 ms: 1.01x faster                                            |
| deepcopy                | 389 us                                                       | 385 us: 1.01x faster                                             |
| deepcopy_memo           | 37.3 us                                                      | 36.9 us: 1.01x faster                                            |
| pickle_list             | 3.89 us                                                      | 3.86 us: 1.01x faster                                            |
| raytrace                | 308 ms                                                       | 305 ms: 1.01x faster                                             |
| unpickle_pure_python    | 236 us                                                       | 234 us: 1.01x faster                                             |
| meteor_contest          | 130 ms                                                       | 129 ms: 1.01x faster                                             |
| asyncio_tcp             | 752 ms                                                       | 746 ms: 1.01x faster                                             |
| spectral_norm           | 94.0 ms                                                      | 93.4 ms: 1.01x faster                                            |
| xml_etree_process       | 56.1 ms                                                      | 55.8 ms: 1.01x faster                                            |
| regex_compile           | 157 ms                                                       | 157 ms: 1.00x faster                                             |
| regex_dna               | 226 ms                                                       | 227 ms: 1.00x slower                                             |
| scimark_sparse_mat_mult | 4.04 ms                                                      | 4.05 ms: 1.00x slower                                            |
| chaos                   | 71.6 ms                                                      | 72.1 ms: 1.01x slower                                            |
| pickle_pure_python      | 318 us                                                       | 320 us: 1.01x slower                                             |
| sqlglot_optimize        | 59.2 ms                                                      | 59.7 ms: 1.01x slower                                            |
| scimark_fft             | 281 ms                                                       | 284 ms: 1.01x slower                                             |
| telco                   | 6.91 ms                                                      | 6.99 ms: 1.01x slower                                            |
| chameleon               | 7.42 ms                                                      | 7.52 ms: 1.01x slower                                            |
| pycparser               | 1.28 sec                                                     | 1.30 sec: 1.01x slower                                           |
| sqlglot_normalize       | 122 ms                                                       | 124 ms: 1.02x slower                                             |
| regex_v8                | 23.7 ms                                                      | 24.1 ms: 1.02x slower                                            |
| crypto_pyaes            | 81.8 ms                                                      | 83.5 ms: 1.02x slower                                            |
| sqlite_synth            | 2.49 us                                                      | 2.54 us: 1.02x slower                                            |
| unpickle_list           | 4.47 us                                                      | 4.57 us: 1.02x slower                                            |
| deepcopy_reduce         | 3.37 us                                                      | 3.47 us: 1.03x slower                                            |
| create_gc_cycles        | 1.59 ms                                                      | 1.64 ms: 1.03x slower                                            |
| mdp                     | 2.72 sec                                                     | 2.85 sec: 1.05x slower                                           |
| comprehensions          | 24.8 us                                                      | 27.9 us: 1.12x slower                                            |
| sqlglot_transpile       | 1.94 ms                                                      | 2.29 ms: 1.18x slower                                            |
| sqlglot_parse           | 1.55 ms                                                      | 1.95 ms: 1.25x slower                                            |
| Geometric mean          | (ref)                                                        | 1.01x faster                                                     |

Benchmark hidden because not significant (17): mypy2, bench_thread_pool, bench_mp_pool, thrift, mako, pathlib, html5lib, logging_format, logging_simple, xml_etree_iterparse, pickle, coroutines, pidigits, hexiom, unpickle, unpack_sequence, nbody
Ignored benchmarks (11) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_tcp_ssl, asyncio_websockets, coverage, flaskblogging, richards_super, tomli_loads, typing_runtime_protocols


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.01x
- 95% likely to have a speedup of 1.01x
- 99% likely to have a speedup of 1.00x
