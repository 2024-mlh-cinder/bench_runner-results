
# Results vs. 3.11.0

- fork: python
- ref: 4fe22c73770fe86b01ef
- machine: linux-x86_64
- commit hash: 4fe22c7
- commit date: 2023-11-02
- overall geometric mean: 1.07x faster
- HPT reliability: 99.87%
- HPT 99th percentile: 1.01x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231102-pythonperf2-x86_64-python-4fe22c73770fe86b01ef-3.13.0a1+-4fe22c7 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| 2to3           | 286 ms                                                       | 291 ms: 1.02x slower                                                         |
| docutils       | 2.87 sec                                                     | 2.83 sec: 1.01x faster                                                       |
| tornado_http   | 125 ms                                                       | 118 ms: 1.05x faster                                                         |
| Geometric mean | (ref)                                                        | 1.01x faster                                                                 |

Benchmark hidden because not significant (1): chameleon

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231102-pythonperf2-x86_64-python-4fe22c73770fe86b01ef-3.13.0a1+-4fe22c7 |
|----------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| async_tree_none            | 529 ms                                                       | 433 ms: 1.22x faster                                                         |
| async_tree_memoization     | 648 ms                                                       | 546 ms: 1.19x faster                                                         |
| async_tree_io              | 1.19 sec                                                     | 1.08 sec: 1.10x faster                                                       |
| async_tree_none_tg         | 482 ms                                                       | 438 ms: 1.10x faster                                                         |
| async_tree_cpu_io_mixed    | 762 ms                                                       | 699 ms: 1.09x faster                                                         |
| async_tree_io_tg           | 1.17 sec                                                     | 1.09 sec: 1.07x faster                                                       |
| async_tree_cpu_io_mixed_tg | 760 ms                                                       | 716 ms: 1.06x faster                                                         |
| async_tree_memoization_tg  | 605 ms                                                       | 572 ms: 1.06x faster                                                         |
| Geometric mean             | (ref)                                                        | 1.11x faster                                                                 |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231102-pythonperf2-x86_64-python-4fe22c73770fe86b01ef-3.13.0a1+-4fe22c7 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| nbody          | 95.8 ms                                                      | 87.6 ms: 1.09x faster                                                        |
| float          | 76.0 ms                                                      | 79.3 ms: 1.04x slower                                                        |
| pidigits       | 251 ms                                                       | 265 ms: 1.05x slower                                                         |
| Geometric mean | (ref)                                                        | 1.00x slower                                                                 |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231102-pythonperf2-x86_64-python-4fe22c73770fe86b01ef-3.13.0a1+-4fe22c7 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| regex_compile  | 157 ms                                                       | 145 ms: 1.08x faster                                                         |
| regex_effbot   | 3.42 ms                                                      | 3.50 ms: 1.03x slower                                                        |
| regex_dna      | 226 ms                                                       | 234 ms: 1.04x slower                                                         |
| regex_v8       | 23.7 ms                                                      | 25.3 ms: 1.07x slower                                                        |
| Geometric mean | (ref)                                                        | 1.01x slower                                                                 |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231102-pythonperf2-x86_64-python-4fe22c73770fe86b01ef-3.13.0a1+-4fe22c7 |
|----------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| json_dumps           | 13.5 ms                                                      | 10.4 ms: 1.29x faster                                                        |
| json_loads           | 29.0 us                                                      | 24.3 us: 1.19x faster                                                        |
| xml_etree_parse      | 159 ms                                                       | 146 ms: 1.09x faster                                                         |
| unpickle_pure_python | 236 us                                                       | 221 us: 1.07x faster                                                         |
| tomli_loads          | 2.27 sec                                                     | 2.21 sec: 1.03x faster                                                       |
| pickle_dict          | 31.8 us                                                      | 31.5 us: 1.01x faster                                                        |
| pickle_pure_python   | 318 us                                                       | 317 us: 1.00x faster                                                         |
| xml_etree_process    | 56.1 ms                                                      | 58.1 ms: 1.04x slower                                                        |
| pickle               | 9.77 us                                                      | 10.2 us: 1.05x slower                                                        |
| xml_etree_generate   | 80.5 ms                                                      | 85.1 ms: 1.06x slower                                                        |
| unpickle_list        | 4.47 us                                                      | 4.77 us: 1.07x slower                                                        |
| unpickle             | 13.2 us                                                      | 14.6 us: 1.11x slower                                                        |
| pickle_list          | 3.89 us                                                      | 4.38 us: 1.12x slower                                                        |
| Geometric mean       | (ref)                                                        | 1.01x faster                                                                 |

Benchmark hidden because not significant (1): xml_etree_iterparse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231102-pythonperf2-x86_64-python-4fe22c73770fe86b01ef-3.13.0a1+-4fe22c7 |
|------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| python_startup         | 10.8 ms                                                      | 12.8 ms: 1.18x slower                                                        |
| python_startup_no_site | 7.78 ms                                                      | 11.3 ms: 1.45x slower                                                        |
| Geometric mean         | (ref)                                                        | 1.31x slower                                                                 |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231102-pythonperf2-x86_64-python-4fe22c73770fe86b01ef-3.13.0a1+-4fe22c7 |
|-----------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| mako      | 11.0 ms                                                      | 10.2 ms: 1.08x faster                                                        |

All benchmarks:
===============

| Benchmark                  | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231102-pythonperf2-x86_64-python-4fe22c73770fe86b01ef-3.13.0a1+-4fe22c7 |
|----------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| typing_runtime_protocols   | 527 us                                                       | 124 us: 4.25x faster                                                         |
| asyncio_tcp                | 752 ms                                                       | 366 ms: 2.06x faster                                                         |
| asyncio_tcp_ssl            | 3.09 sec                                                     | 1.58 sec: 1.96x faster                                                       |
| generators                 | 56.4 ms                                                      | 35.6 ms: 1.58x faster                                                        |
| comprehensions             | 24.8 us                                                      | 16.4 us: 1.51x faster                                                        |
| json_dumps                 | 13.5 ms                                                      | 10.4 ms: 1.29x faster                                                        |
| coroutines                 | 27.9 ms                                                      | 22.5 ms: 1.24x faster                                                        |
| sympy_sum                  | 184 ms                                                       | 149 ms: 1.24x faster                                                         |
| mypy2                      | 449 ms                                                       | 366 ms: 1.23x faster                                                         |
| async_tree_none            | 529 ms                                                       | 433 ms: 1.22x faster                                                         |
| json_loads                 | 29.0 us                                                      | 24.3 us: 1.19x faster                                                        |
| async_tree_memoization     | 648 ms                                                       | 546 ms: 1.19x faster                                                         |
| fannkuch                   | 457 ms                                                       | 390 ms: 1.17x faster                                                         |
| chaos                      | 71.6 ms                                                      | 61.1 ms: 1.17x faster                                                        |
| sympy_str                  | 336 ms                                                       | 287 ms: 1.17x faster                                                         |
| gc_traversal               | 4.06 ms                                                      | 3.50 ms: 1.16x faster                                                        |
| crypto_pyaes               | 81.8 ms                                                      | 70.6 ms: 1.16x faster                                                        |
| scimark_lu                 | 115 ms                                                       | 100 ms: 1.15x faster                                                         |
| nqueens                    | 99.2 ms                                                      | 87.5 ms: 1.13x faster                                                        |
| raytrace                   | 308 ms                                                       | 272 ms: 1.13x faster                                                         |
| sympy_integrate            | 25.6 ms                                                      | 22.7 ms: 1.13x faster                                                        |
| sympy_expand               | 550 ms                                                       | 489 ms: 1.13x faster                                                         |
| scimark_monte_carlo        | 70.6 ms                                                      | 63.2 ms: 1.12x faster                                                        |
| deltablue                  | 4.03 ms                                                      | 3.63 ms: 1.11x faster                                                        |
| async_tree_io              | 1.19 sec                                                     | 1.08 sec: 1.10x faster                                                       |
| sqlglot_parse              | 1.55 ms                                                      | 1.41 ms: 1.10x faster                                                        |
| async_tree_none_tg         | 482 ms                                                       | 438 ms: 1.10x faster                                                         |
| nbody                      | 95.8 ms                                                      | 87.6 ms: 1.09x faster                                                        |
| async_tree_cpu_io_mixed    | 762 ms                                                       | 699 ms: 1.09x faster                                                         |
| richards_super             | 65.2 ms                                                      | 59.9 ms: 1.09x faster                                                        |
| xml_etree_parse            | 159 ms                                                       | 146 ms: 1.09x faster                                                         |
| mdp                        | 2.72 sec                                                     | 2.51 sec: 1.08x faster                                                       |
| regex_compile              | 157 ms                                                       | 145 ms: 1.08x faster                                                         |
| json                       | 5.59 ms                                                      | 5.16 ms: 1.08x faster                                                        |
| logging_silent             | 102 ns                                                       | 94.1 ns: 1.08x faster                                                        |
| mako                       | 11.0 ms                                                      | 10.2 ms: 1.08x faster                                                        |
| hexiom                     | 6.97 ms                                                      | 6.46 ms: 1.08x faster                                                        |
| sqlglot_normalize          | 122 ms                                                       | 113 ms: 1.08x faster                                                         |
| bench_thread_pool          | 1.02 ms                                                      | 948 us: 1.08x faster                                                         |
| async_tree_io_tg           | 1.17 sec                                                     | 1.09 sec: 1.07x faster                                                       |
| unpickle_pure_python       | 236 us                                                       | 221 us: 1.07x faster                                                         |
| sqlglot_transpile          | 1.94 ms                                                      | 1.82 ms: 1.07x faster                                                        |
| async_tree_cpu_io_mixed_tg | 760 ms                                                       | 716 ms: 1.06x faster                                                         |
| async_tree_memoization_tg  | 605 ms                                                       | 572 ms: 1.06x faster                                                         |
| tornado_http               | 125 ms                                                       | 118 ms: 1.05x faster                                                         |
| logging_simple             | 7.21 us                                                      | 6.86 us: 1.05x faster                                                        |
| logging_format             | 7.83 us                                                      | 7.46 us: 1.05x faster                                                        |
| deepcopy                   | 389 us                                                       | 372 us: 1.05x faster                                                         |
| deepcopy_reduce            | 3.37 us                                                      | 3.26 us: 1.03x faster                                                        |
| spectral_norm              | 94.0 ms                                                      | 91.1 ms: 1.03x faster                                                        |
| tomli_loads                | 2.27 sec                                                     | 2.21 sec: 1.03x faster                                                       |
| sqlglot_optimize           | 59.2 ms                                                      | 57.5 ms: 1.03x faster                                                        |
| docutils                   | 2.87 sec                                                     | 2.83 sec: 1.01x faster                                                       |
| meteor_contest             | 130 ms                                                       | 129 ms: 1.01x faster                                                         |
| pickle_dict                | 31.8 us                                                      | 31.5 us: 1.01x faster                                                        |
| pickle_pure_python         | 318 us                                                       | 317 us: 1.00x faster                                                         |
| scimark_sparse_mat_mult    | 4.04 ms                                                      | 4.06 ms: 1.01x slower                                                        |
| 2to3                       | 286 ms                                                       | 291 ms: 1.02x slower                                                         |
| pprint_safe_repr           | 780 ms                                                       | 795 ms: 1.02x slower                                                         |
| pathlib                    | 19.1 ms                                                      | 19.5 ms: 1.02x slower                                                        |
| create_gc_cycles           | 1.59 ms                                                      | 1.63 ms: 1.02x slower                                                        |
| regex_effbot               | 3.42 ms                                                      | 3.50 ms: 1.03x slower                                                        |
| go                         | 166 ms                                                       | 171 ms: 1.03x slower                                                         |
| xml_etree_process          | 56.1 ms                                                      | 58.1 ms: 1.04x slower                                                        |
| regex_dna                  | 226 ms                                                       | 234 ms: 1.04x slower                                                         |
| pycparser                  | 1.28 sec                                                     | 1.34 sec: 1.04x slower                                                       |
| scimark_fft                | 281 ms                                                       | 293 ms: 1.04x slower                                                         |
| float                      | 76.0 ms                                                      | 79.3 ms: 1.04x slower                                                        |
| pickle                     | 9.77 us                                                      | 10.2 us: 1.05x slower                                                        |
| pidigits                   | 251 ms                                                       | 265 ms: 1.05x slower                                                         |
| xml_etree_generate         | 80.5 ms                                                      | 85.1 ms: 1.06x slower                                                        |
| bench_mp_pool              | 4.63 ms                                                      | 4.91 ms: 1.06x slower                                                        |
| unpickle_list              | 4.47 us                                                      | 4.77 us: 1.07x slower                                                        |
| regex_v8                   | 23.7 ms                                                      | 25.3 ms: 1.07x slower                                                        |
| richards                   | 49.9 ms                                                      | 54.0 ms: 1.08x slower                                                        |
| sqlite_synth               | 2.49 us                                                      | 2.71 us: 1.09x slower                                                        |
| unpickle                   | 13.2 us                                                      | 14.6 us: 1.11x slower                                                        |
| pyflate                    | 453 ms                                                       | 502 ms: 1.11x slower                                                         |
| pickle_list                | 3.89 us                                                      | 4.38 us: 1.12x slower                                                        |
| async_generators           | 322 ms                                                       | 369 ms: 1.15x slower                                                         |
| unpack_sequence            | 44.9 ns                                                      | 52.8 ns: 1.18x slower                                                        |
| python_startup             | 10.8 ms                                                      | 12.8 ms: 1.18x slower                                                        |
| telco                      | 6.91 ms                                                      | 8.20 ms: 1.19x slower                                                        |
| coverage                   | 66.6 ms                                                      | 82.4 ms: 1.24x slower                                                        |
| scimark_sor                | 109 ms                                                       | 144 ms: 1.32x slower                                                         |
| python_startup_no_site     | 7.78 ms                                                      | 11.3 ms: 1.45x slower                                                        |
| Geometric mean             | (ref)                                                        | 1.07x faster                                                                 |

Benchmark hidden because not significant (6): xml_etree_iterparse, pprint_pformat, asyncio_websockets, dulwich_log, deepcopy_memo, chameleon
Ignored benchmarks (12) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, dask, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift


# HPT report

- Reliability score: 99.87% likely to be faster
- 90% likely to have a speedup of 1.02x
- 95% likely to have a speedup of 1.02x
- 99% likely to have a speedup of 1.01x
