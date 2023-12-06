
# Results vs. 3.11.0

- fork: python
- ref: 1a969b4f55f92a17bec8
- machine: linux-x86_64
- commit hash: 1a969b4
- commit date: 2023-11-19
- overall geometric mean: 1.02x slower \*
- HPT reliability: 94.34%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231119-pythonperf2-x86_64-python-1a969b4f55f92a17bec8-3.13.0a1+-1a969b4 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| 2to3           | 286 ms                                                       | 316 ms: 1.11x slower                                                         |
| chameleon      | 7.42 ms                                                      | 7.93 ms: 1.07x slower                                                        |
| docutils       | 2.87 sec                                                     | 2.93 sec: 1.02x slower                                                       |
| Geometric mean | (ref)                                                        | 1.05x slower                                                                 |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231119-pythonperf2-x86_64-python-1a969b4f55f92a17bec8-3.13.0a1+-1a969b4 |
|----------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| async_tree_none            | 529 ms                                                       | 453 ms: 1.17x faster                                                         |
| async_tree_memoization     | 648 ms                                                       | 567 ms: 1.14x faster                                                         |
| async_tree_io              | 1.19 sec                                                     | 1.11 sec: 1.07x faster                                                       |
| async_tree_memoization_tg  | 605 ms                                                       | 568 ms: 1.06x faster                                                         |
| async_tree_cpu_io_mixed    | 762 ms                                                       | 718 ms: 1.06x faster                                                         |
| async_tree_none_tg         | 482 ms                                                       | 459 ms: 1.05x faster                                                         |
| async_tree_io_tg           | 1.17 sec                                                     | 1.12 sec: 1.05x faster                                                       |
| async_tree_cpu_io_mixed_tg | 760 ms                                                       | 732 ms: 1.04x faster                                                         |
| Geometric mean             | (ref)                                                        | 1.08x faster                                                                 |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231119-pythonperf2-x86_64-python-1a969b4f55f92a17bec8-3.13.0a1+-1a969b4 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| pidigits       | 251 ms                                                       | 267 ms: 1.07x slower                                                         |
| nbody          | 95.8 ms                                                      | 120 ms: 1.26x slower                                                         |
| float          | 76.0 ms                                                      | 108 ms: 1.42x slower                                                         |
| Geometric mean | (ref)                                                        | 1.24x slower                                                                 |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231119-pythonperf2-x86_64-python-1a969b4f55f92a17bec8-3.13.0a1+-1a969b4 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| regex_effbot   | 3.42 ms                                                      | 3.52 ms: 1.03x slower                                                        |
| regex_v8       | 23.7 ms                                                      | 26.2 ms: 1.11x slower                                                        |
| regex_dna      | 226 ms                                                       | 252 ms: 1.12x slower                                                         |
| regex_compile  | 157 ms                                                       | 177 ms: 1.13x slower                                                         |
| Geometric mean | (ref)                                                        | 1.09x slower                                                                 |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231119-pythonperf2-x86_64-python-1a969b4f55f92a17bec8-3.13.0a1+-1a969b4 |
|----------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| json_dumps           | 13.5 ms                                                      | 10.7 ms: 1.26x faster                                                        |
| json_loads           | 29.0 us                                                      | 25.5 us: 1.14x faster                                                        |
| xml_etree_parse      | 159 ms                                                       | 153 ms: 1.04x faster                                                         |
| pickle_pure_python   | 318 us                                                       | 311 us: 1.02x faster                                                         |
| pickle_dict          | 31.8 us                                                      | 32.0 us: 1.01x slower                                                        |
| xml_etree_process    | 56.1 ms                                                      | 57.8 ms: 1.03x slower                                                        |
| pickle               | 9.77 us                                                      | 10.1 us: 1.03x slower                                                        |
| xml_etree_iterparse  | 106 ms                                                       | 111 ms: 1.05x slower                                                         |
| unpickle_list        | 4.47 us                                                      | 4.70 us: 1.05x slower                                                        |
| unpickle_pure_python | 236 us                                                       | 252 us: 1.07x slower                                                         |
| xml_etree_generate   | 80.5 ms                                                      | 86.8 ms: 1.08x slower                                                        |
| unpickle             | 13.2 us                                                      | 14.5 us: 1.10x slower                                                        |
| pickle_list          | 3.89 us                                                      | 4.49 us: 1.15x slower                                                        |
| tomli_loads          | 2.27 sec                                                     | 2.88 sec: 1.26x slower                                                       |
| Geometric mean       | (ref)                                                        | 1.03x slower                                                                 |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231119-pythonperf2-x86_64-python-1a969b4f55f92a17bec8-3.13.0a1+-1a969b4 |
|------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| python_startup         | 10.8 ms                                                      | 12.8 ms: 1.18x slower                                                        |
| python_startup_no_site | 7.78 ms                                                      | 11.3 ms: 1.45x slower                                                        |
| Geometric mean         | (ref)                                                        | 1.31x slower                                                                 |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231119-pythonperf2-x86_64-python-1a969b4f55f92a17bec8-3.13.0a1+-1a969b4 |
|-----------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| mako      | 11.0 ms                                                      | 16.9 ms: 1.54x slower                                                        |

All benchmarks:
===============

| Benchmark                  | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231119-pythonperf2-x86_64-python-1a969b4f55f92a17bec8-3.13.0a1+-1a969b4 |
|----------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| typing_runtime_protocols   | 527 us                                                       | 131 us: 4.01x faster                                                         |
| asyncio_tcp                | 752 ms                                                       | 375 ms: 2.01x faster                                                         |
| asyncio_tcp_ssl            | 3.09 sec                                                     | 1.59 sec: 1.95x faster                                                       |
| generators                 | 56.4 ms                                                      | 34.0 ms: 1.66x faster                                                        |
| coroutines                 | 27.9 ms                                                      | 22.1 ms: 1.26x faster                                                        |
| json_dumps                 | 13.5 ms                                                      | 10.7 ms: 1.26x faster                                                        |
| mypy2                      | 449 ms                                                       | 379 ms: 1.19x faster                                                         |
| async_tree_none            | 529 ms                                                       | 453 ms: 1.17x faster                                                         |
| sympy_sum                  | 184 ms                                                       | 160 ms: 1.15x faster                                                         |
| async_tree_memoization     | 648 ms                                                       | 567 ms: 1.14x faster                                                         |
| json_loads                 | 29.0 us                                                      | 25.5 us: 1.14x faster                                                        |
| gc_traversal               | 4.06 ms                                                      | 3.71 ms: 1.10x faster                                                        |
| sympy_str                  | 336 ms                                                       | 312 ms: 1.08x faster                                                         |
| async_tree_io              | 1.19 sec                                                     | 1.11 sec: 1.07x faster                                                       |
| async_tree_memoization_tg  | 605 ms                                                       | 568 ms: 1.06x faster                                                         |
| logging_simple             | 7.21 us                                                      | 6.80 us: 1.06x faster                                                        |
| deepcopy                   | 389 us                                                       | 367 us: 1.06x faster                                                         |
| async_tree_cpu_io_mixed    | 762 ms                                                       | 718 ms: 1.06x faster                                                         |
| richards_super             | 65.2 ms                                                      | 61.4 ms: 1.06x faster                                                        |
| json                       | 5.59 ms                                                      | 5.29 ms: 1.06x faster                                                        |
| sqlglot_parse              | 1.55 ms                                                      | 1.47 ms: 1.06x faster                                                        |
| scimark_lu                 | 115 ms                                                       | 109 ms: 1.05x faster                                                         |
| bench_thread_pool          | 1.02 ms                                                      | 969 us: 1.05x faster                                                         |
| async_tree_none_tg         | 482 ms                                                       | 459 ms: 1.05x faster                                                         |
| async_tree_io_tg           | 1.17 sec                                                     | 1.12 sec: 1.05x faster                                                       |
| sympy_expand               | 550 ms                                                       | 527 ms: 1.04x faster                                                         |
| logging_format             | 7.83 us                                                      | 7.51 us: 1.04x faster                                                        |
| xml_etree_parse            | 159 ms                                                       | 153 ms: 1.04x faster                                                         |
| async_tree_cpu_io_mixed_tg | 760 ms                                                       | 732 ms: 1.04x faster                                                         |
| sqlglot_normalize          | 122 ms                                                       | 117 ms: 1.04x faster                                                         |
| deepcopy_reduce            | 3.37 us                                                      | 3.26 us: 1.03x faster                                                        |
| logging_silent             | 102 ns                                                       | 98.9 ns: 1.03x faster                                                        |
| sqlglot_transpile          | 1.94 ms                                                      | 1.88 ms: 1.03x faster                                                        |
| spectral_norm              | 94.0 ms                                                      | 91.7 ms: 1.02x faster                                                        |
| dask                       | 417 ms                                                       | 407 ms: 1.02x faster                                                         |
| pickle_pure_python         | 318 us                                                       | 311 us: 1.02x faster                                                         |
| sympy_integrate            | 25.6 ms                                                      | 25.0 ms: 1.02x faster                                                        |
| sqlglot_optimize           | 59.2 ms                                                      | 59.5 ms: 1.00x slower                                                        |
| pickle_dict                | 31.8 us                                                      | 32.0 us: 1.01x slower                                                        |
| pathlib                    | 19.1 ms                                                      | 19.4 ms: 1.01x slower                                                        |
| raytrace                   | 308 ms                                                       | 312 ms: 1.01x slower                                                         |
| asyncio_websockets         | 388 ms                                                       | 394 ms: 1.01x slower                                                         |
| docutils                   | 2.87 sec                                                     | 2.93 sec: 1.02x slower                                                       |
| mdp                        | 2.72 sec                                                     | 2.77 sec: 1.02x slower                                                       |
| regex_effbot               | 3.42 ms                                                      | 3.52 ms: 1.03x slower                                                        |
| xml_etree_process          | 56.1 ms                                                      | 57.8 ms: 1.03x slower                                                        |
| pycparser                  | 1.28 sec                                                     | 1.32 sec: 1.03x slower                                                       |
| pickle                     | 9.77 us                                                      | 10.1 us: 1.03x slower                                                        |
| dulwich_log                | 68.3 ms                                                      | 71.3 ms: 1.04x slower                                                        |
| xml_etree_iterparse        | 106 ms                                                       | 111 ms: 1.05x slower                                                         |
| unpickle_list              | 4.47 us                                                      | 4.70 us: 1.05x slower                                                        |
| meteor_contest             | 130 ms                                                       | 139 ms: 1.06x slower                                                         |
| pidigits                   | 251 ms                                                       | 267 ms: 1.07x slower                                                         |
| unpickle_pure_python       | 236 us                                                       | 252 us: 1.07x slower                                                         |
| chameleon                  | 7.42 ms                                                      | 7.93 ms: 1.07x slower                                                        |
| deepcopy_memo              | 37.3 us                                                      | 40.0 us: 1.07x slower                                                        |
| xml_etree_generate         | 80.5 ms                                                      | 86.8 ms: 1.08x slower                                                        |
| bench_mp_pool              | 4.63 ms                                                      | 5.02 ms: 1.08x slower                                                        |
| sqlite_synth               | 2.49 us                                                      | 2.72 us: 1.09x slower                                                        |
| unpickle                   | 13.2 us                                                      | 14.5 us: 1.10x slower                                                        |
| chaos                      | 71.6 ms                                                      | 78.9 ms: 1.10x slower                                                        |
| fannkuch                   | 457 ms                                                       | 505 ms: 1.10x slower                                                         |
| regex_v8                   | 23.7 ms                                                      | 26.2 ms: 1.11x slower                                                        |
| 2to3                       | 286 ms                                                       | 316 ms: 1.11x slower                                                         |
| crypto_pyaes               | 81.8 ms                                                      | 90.8 ms: 1.11x slower                                                        |
| regex_dna                  | 226 ms                                                       | 252 ms: 1.12x slower                                                         |
| comprehensions             | 24.8 us                                                      | 27.7 us: 1.12x slower                                                        |
| richards                   | 49.9 ms                                                      | 55.7 ms: 1.12x slower                                                        |
| regex_compile              | 157 ms                                                       | 177 ms: 1.13x slower                                                         |
| pickle_list                | 3.89 us                                                      | 4.49 us: 1.15x slower                                                        |
| go                         | 166 ms                                                       | 191 ms: 1.15x slower                                                         |
| pprint_pformat             | 1.63 sec                                                     | 1.89 sec: 1.16x slower                                                       |
| pprint_safe_repr           | 780 ms                                                       | 916 ms: 1.17x slower                                                         |
| async_generators           | 322 ms                                                       | 379 ms: 1.18x slower                                                         |
| nqueens                    | 99.2 ms                                                      | 117 ms: 1.18x slower                                                         |
| python_startup             | 10.8 ms                                                      | 12.8 ms: 1.18x slower                                                        |
| unpack_sequence            | 44.9 ns                                                      | 54.3 ns: 1.21x slower                                                        |
| telco                      | 6.91 ms                                                      | 8.56 ms: 1.24x slower                                                        |
| coverage                   | 66.6 ms                                                      | 82.9 ms: 1.24x slower                                                        |
| nbody                      | 95.8 ms                                                      | 120 ms: 1.26x slower                                                         |
| tomli_loads                | 2.27 sec                                                     | 2.88 sec: 1.26x slower                                                       |
| scimark_monte_carlo        | 70.6 ms                                                      | 90.2 ms: 1.28x slower                                                        |
| pyflate                    | 453 ms                                                       | 582 ms: 1.29x slower                                                         |
| scimark_sor                | 109 ms                                                       | 151 ms: 1.38x slower                                                         |
| deltablue                  | 4.03 ms                                                      | 5.61 ms: 1.39x slower                                                        |
| float                      | 76.0 ms                                                      | 108 ms: 1.42x slower                                                         |
| python_startup_no_site     | 7.78 ms                                                      | 11.3 ms: 1.45x slower                                                        |
| hexiom                     | 6.97 ms                                                      | 10.6 ms: 1.52x slower                                                        |
| mako                       | 11.0 ms                                                      | 16.9 ms: 1.54x slower                                                        |
| scimark_fft                | 281 ms                                                       | 447 ms: 1.59x slower                                                         |
| scimark_sparse_mat_mult    | 4.04 ms                                                      | 6.60 ms: 1.63x slower                                                        |
| Geometric mean             | (ref)                                                        | 1.02x slower                                                                 |

Benchmark hidden because not significant (2): create_gc_cycles, tornado_http
Ignored benchmarks (11) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift


# HPT report

- Reliability score: 94.34% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
