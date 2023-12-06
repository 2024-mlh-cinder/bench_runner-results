
# Results vs. 3.11.0

- fork: faster-cpython
- ref: likelihood_on_trace
- machine: linux-x86_64
- commit hash: 55d5c8d
- commit date: 2023-11-16
- overall geometric mean: 1.02x slower \*
- HPT reliability: 80.94%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231116-pythonperf2-x86_64-faster%2dcpython-likelihood_on_trace-3.13.0a1+-55d5c8d |
|----------------|:------------------------------------------------------------:|:-------------------------------------------------------------------------------------:|
| 2to3           | 286 ms                                                       | 315 ms: 1.10x slower                                                                  |
| chameleon      | 7.42 ms                                                      | 7.98 ms: 1.07x slower                                                                 |
| docutils       | 2.87 sec                                                     | 2.94 sec: 1.02x slower                                                                |
| Geometric mean | (ref)                                                        | 1.05x slower                                                                          |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231116-pythonperf2-x86_64-faster%2dcpython-likelihood_on_trace-3.13.0a1+-55d5c8d |
|----------------------------|:------------------------------------------------------------:|:-------------------------------------------------------------------------------------:|
| async_tree_none            | 529 ms                                                       | 450 ms: 1.17x faster                                                                  |
| async_tree_memoization     | 648 ms                                                       | 563 ms: 1.15x faster                                                                  |
| async_tree_io              | 1.19 sec                                                     | 1.10 sec: 1.08x faster                                                                |
| async_tree_memoization_tg  | 605 ms                                                       | 565 ms: 1.07x faster                                                                  |
| async_tree_cpu_io_mixed    | 762 ms                                                       | 715 ms: 1.07x faster                                                                  |
| async_tree_none_tg         | 482 ms                                                       | 454 ms: 1.06x faster                                                                  |
| async_tree_io_tg           | 1.17 sec                                                     | 1.12 sec: 1.05x faster                                                                |
| async_tree_cpu_io_mixed_tg | 760 ms                                                       | 729 ms: 1.04x faster                                                                  |
| Geometric mean             | (ref)                                                        | 1.09x faster                                                                          |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231116-pythonperf2-x86_64-faster%2dcpython-likelihood_on_trace-3.13.0a1+-55d5c8d |
|----------------|:------------------------------------------------------------:|:-------------------------------------------------------------------------------------:|
| pidigits       | 251 ms                                                       | 267 ms: 1.06x slower                                                                  |
| nbody          | 95.8 ms                                                      | 115 ms: 1.20x slower                                                                  |
| float          | 76.0 ms                                                      | 105 ms: 1.38x slower                                                                  |
| Geometric mean | (ref)                                                        | 1.21x slower                                                                          |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231116-pythonperf2-x86_64-faster%2dcpython-likelihood_on_trace-3.13.0a1+-55d5c8d |
|----------------|:------------------------------------------------------------:|:-------------------------------------------------------------------------------------:|
| regex_effbot   | 3.42 ms                                                      | 3.52 ms: 1.03x slower                                                                 |
| regex_dna      | 226 ms                                                       | 244 ms: 1.08x slower                                                                  |
| regex_v8       | 23.7 ms                                                      | 26.2 ms: 1.11x slower                                                                 |
| regex_compile  | 157 ms                                                       | 176 ms: 1.12x slower                                                                  |
| Geometric mean | (ref)                                                        | 1.08x slower                                                                          |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231116-pythonperf2-x86_64-faster%2dcpython-likelihood_on_trace-3.13.0a1+-55d5c8d |
|----------------------|:------------------------------------------------------------:|:-------------------------------------------------------------------------------------:|
| json_dumps           | 13.5 ms                                                      | 10.6 ms: 1.27x faster                                                                 |
| json_loads           | 29.0 us                                                      | 25.2 us: 1.15x faster                                                                 |
| xml_etree_parse      | 159 ms                                                       | 148 ms: 1.07x faster                                                                  |
| pickle_pure_python   | 318 us                                                       | 314 us: 1.01x faster                                                                  |
| xml_etree_process    | 56.1 ms                                                      | 58.3 ms: 1.04x slower                                                                 |
| pickle               | 9.77 us                                                      | 10.3 us: 1.05x slower                                                                 |
| unpickle_list        | 4.47 us                                                      | 4.74 us: 1.06x slower                                                                 |
| unpickle_pure_python | 236 us                                                       | 254 us: 1.07x slower                                                                  |
| xml_etree_iterparse  | 106 ms                                                       | 114 ms: 1.08x slower                                                                  |
| xml_etree_generate   | 80.5 ms                                                      | 87.0 ms: 1.08x slower                                                                 |
| unpickle             | 13.2 us                                                      | 14.6 us: 1.11x slower                                                                 |
| pickle_list          | 3.89 us                                                      | 4.53 us: 1.16x slower                                                                 |
| tomli_loads          | 2.27 sec                                                     | 3.02 sec: 1.33x slower                                                                |
| Geometric mean       | (ref)                                                        | 1.03x slower                                                                          |

Benchmark hidden because not significant (1): pickle_dict

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231116-pythonperf2-x86_64-faster%2dcpython-likelihood_on_trace-3.13.0a1+-55d5c8d |
|------------------------|:------------------------------------------------------------:|:-------------------------------------------------------------------------------------:|
| python_startup         | 10.8 ms                                                      | 12.9 ms: 1.19x slower                                                                 |
| python_startup_no_site | 7.78 ms                                                      | 11.4 ms: 1.46x slower                                                                 |
| Geometric mean         | (ref)                                                        | 1.32x slower                                                                          |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231116-pythonperf2-x86_64-faster%2dcpython-likelihood_on_trace-3.13.0a1+-55d5c8d |
|-----------|:------------------------------------------------------------:|:-------------------------------------------------------------------------------------:|
| mako      | 11.0 ms                                                      | 15.9 ms: 1.45x slower                                                                 |

All benchmarks:
===============

| Benchmark                  | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231116-pythonperf2-x86_64-faster%2dcpython-likelihood_on_trace-3.13.0a1+-55d5c8d |
|----------------------------|:------------------------------------------------------------:|:-------------------------------------------------------------------------------------:|
| typing_runtime_protocols   | 527 us                                                       | 138 us: 3.83x faster                                                                  |
| asyncio_tcp                | 752 ms                                                       | 373 ms: 2.01x faster                                                                  |
| asyncio_tcp_ssl            | 3.09 sec                                                     | 1.60 sec: 1.94x faster                                                                |
| generators                 | 56.4 ms                                                      | 34.6 ms: 1.63x faster                                                                 |
| json_dumps                 | 13.5 ms                                                      | 10.6 ms: 1.27x faster                                                                 |
| coroutines                 | 27.9 ms                                                      | 22.1 ms: 1.26x faster                                                                 |
| mypy2                      | 449 ms                                                       | 380 ms: 1.18x faster                                                                  |
| async_tree_none            | 529 ms                                                       | 450 ms: 1.17x faster                                                                  |
| sympy_sum                  | 184 ms                                                       | 157 ms: 1.17x faster                                                                  |
| gc_traversal               | 4.06 ms                                                      | 3.47 ms: 1.17x faster                                                                 |
| async_tree_memoization     | 648 ms                                                       | 563 ms: 1.15x faster                                                                  |
| json_loads                 | 29.0 us                                                      | 25.2 us: 1.15x faster                                                                 |
| async_tree_io              | 1.19 sec                                                     | 1.10 sec: 1.08x faster                                                                |
| sympy_str                  | 336 ms                                                       | 310 ms: 1.08x faster                                                                  |
| logging_simple             | 7.21 us                                                      | 6.69 us: 1.08x faster                                                                 |
| json                       | 5.59 ms                                                      | 5.20 ms: 1.07x faster                                                                 |
| scimark_lu                 | 115 ms                                                       | 107 ms: 1.07x faster                                                                  |
| richards_super             | 65.2 ms                                                      | 60.8 ms: 1.07x faster                                                                 |
| xml_etree_parse            | 159 ms                                                       | 148 ms: 1.07x faster                                                                  |
| raytrace                   | 308 ms                                                       | 287 ms: 1.07x faster                                                                  |
| async_tree_memoization_tg  | 605 ms                                                       | 565 ms: 1.07x faster                                                                  |
| async_tree_cpu_io_mixed    | 762 ms                                                       | 715 ms: 1.07x faster                                                                  |
| async_tree_none_tg         | 482 ms                                                       | 454 ms: 1.06x faster                                                                  |
| sqlglot_parse              | 1.55 ms                                                      | 1.47 ms: 1.06x faster                                                                 |
| logging_format             | 7.83 us                                                      | 7.39 us: 1.06x faster                                                                 |
| async_tree_io_tg           | 1.17 sec                                                     | 1.12 sec: 1.05x faster                                                                |
| sympy_expand               | 550 ms                                                       | 527 ms: 1.04x faster                                                                  |
| async_tree_cpu_io_mixed_tg | 760 ms                                                       | 729 ms: 1.04x faster                                                                  |
| sqlglot_normalize          | 122 ms                                                       | 117 ms: 1.04x faster                                                                  |
| bench_thread_pool          | 1.02 ms                                                      | 984 us: 1.04x faster                                                                  |
| deepcopy                   | 389 us                                                       | 376 us: 1.03x faster                                                                  |
| spectral_norm              | 94.0 ms                                                      | 91.0 ms: 1.03x faster                                                                 |
| sqlglot_transpile          | 1.94 ms                                                      | 1.88 ms: 1.03x faster                                                                 |
| dask                       | 417 ms                                                       | 407 ms: 1.02x faster                                                                  |
| sympy_integrate            | 25.6 ms                                                      | 25.1 ms: 1.02x faster                                                                 |
| deepcopy_reduce            | 3.37 us                                                      | 3.30 us: 1.02x faster                                                                 |
| logging_silent             | 102 ns                                                       | 100 ns: 1.02x faster                                                                  |
| create_gc_cycles           | 1.59 ms                                                      | 1.56 ms: 1.02x faster                                                                 |
| pickle_pure_python         | 318 us                                                       | 314 us: 1.01x faster                                                                  |
| chaos                      | 71.6 ms                                                      | 72.2 ms: 1.01x slower                                                                 |
| sqlglot_optimize           | 59.2 ms                                                      | 59.7 ms: 1.01x slower                                                                 |
| pathlib                    | 19.1 ms                                                      | 19.6 ms: 1.02x slower                                                                 |
| docutils                   | 2.87 sec                                                     | 2.94 sec: 1.02x slower                                                                |
| regex_effbot               | 3.42 ms                                                      | 3.52 ms: 1.03x slower                                                                 |
| xml_etree_process          | 56.1 ms                                                      | 58.3 ms: 1.04x slower                                                                 |
| dulwich_log                | 68.3 ms                                                      | 71.4 ms: 1.04x slower                                                                 |
| pickle                     | 9.77 us                                                      | 10.3 us: 1.05x slower                                                                 |
| meteor_contest             | 130 ms                                                       | 138 ms: 1.06x slower                                                                  |
| pycparser                  | 1.28 sec                                                     | 1.36 sec: 1.06x slower                                                                |
| unpickle_list              | 4.47 us                                                      | 4.74 us: 1.06x slower                                                                 |
| pidigits                   | 251 ms                                                       | 267 ms: 1.06x slower                                                                  |
| crypto_pyaes               | 81.8 ms                                                      | 87.3 ms: 1.07x slower                                                                 |
| unpickle_pure_python       | 236 us                                                       | 254 us: 1.07x slower                                                                  |
| chameleon                  | 7.42 ms                                                      | 7.98 ms: 1.07x slower                                                                 |
| xml_etree_iterparse        | 106 ms                                                       | 114 ms: 1.08x slower                                                                  |
| regex_dna                  | 226 ms                                                       | 244 ms: 1.08x slower                                                                  |
| xml_etree_generate         | 80.5 ms                                                      | 87.0 ms: 1.08x slower                                                                 |
| richards                   | 49.9 ms                                                      | 54.2 ms: 1.09x slower                                                                 |
| 2to3                       | 286 ms                                                       | 315 ms: 1.10x slower                                                                  |
| regex_v8                   | 23.7 ms                                                      | 26.2 ms: 1.11x slower                                                                 |
| unpickle                   | 13.2 us                                                      | 14.6 us: 1.11x slower                                                                 |
| pprint_pformat             | 1.63 sec                                                     | 1.82 sec: 1.12x slower                                                                |
| regex_compile              | 157 ms                                                       | 176 ms: 1.12x slower                                                                  |
| sqlite_synth               | 2.49 us                                                      | 2.78 us: 1.12x slower                                                                 |
| go                         | 166 ms                                                       | 185 ms: 1.12x slower                                                                  |
| deepcopy_memo              | 37.3 us                                                      | 42.3 us: 1.13x slower                                                                 |
| pprint_safe_repr           | 780 ms                                                       | 891 ms: 1.14x slower                                                                  |
| fannkuch                   | 457 ms                                                       | 526 ms: 1.15x slower                                                                  |
| unpack_sequence            | 44.9 ns                                                      | 52.0 ns: 1.16x slower                                                                 |
| pickle_list                | 3.89 us                                                      | 4.53 us: 1.16x slower                                                                 |
| scimark_monte_carlo        | 70.6 ms                                                      | 82.4 ms: 1.17x slower                                                                 |
| async_generators           | 322 ms                                                       | 380 ms: 1.18x slower                                                                  |
| nqueens                    | 99.2 ms                                                      | 118 ms: 1.19x slower                                                                  |
| deltablue                  | 4.03 ms                                                      | 4.78 ms: 1.19x slower                                                                 |
| comprehensions             | 24.8 us                                                      | 29.6 us: 1.19x slower                                                                 |
| python_startup             | 10.8 ms                                                      | 12.9 ms: 1.19x slower                                                                 |
| coverage                   | 66.6 ms                                                      | 79.8 ms: 1.20x slower                                                                 |
| nbody                      | 95.8 ms                                                      | 115 ms: 1.20x slower                                                                  |
| telco                      | 6.91 ms                                                      | 8.53 ms: 1.23x slower                                                                 |
| pyflate                    | 453 ms                                                       | 575 ms: 1.27x slower                                                                  |
| tomli_loads                | 2.27 sec                                                     | 3.02 sec: 1.33x slower                                                                |
| scimark_sor                | 109 ms                                                       | 150 ms: 1.37x slower                                                                  |
| float                      | 76.0 ms                                                      | 105 ms: 1.38x slower                                                                  |
| scimark_fft                | 281 ms                                                       | 401 ms: 1.43x slower                                                                  |
| mako                       | 11.0 ms                                                      | 15.9 ms: 1.45x slower                                                                 |
| python_startup_no_site     | 7.78 ms                                                      | 11.4 ms: 1.46x slower                                                                 |
| hexiom                     | 6.97 ms                                                      | 11.0 ms: 1.58x slower                                                                 |
| scimark_sparse_mat_mult    | 4.04 ms                                                      | 7.23 ms: 1.79x slower                                                                 |
| Geometric mean             | (ref)                                                        | 1.02x slower                                                                          |

Benchmark hidden because not significant (5): tornado_http, asyncio_websockets, pickle_dict, mdp, bench_mp_pool
Ignored benchmarks (11) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift


# HPT report

- Reliability score: 80.94% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
