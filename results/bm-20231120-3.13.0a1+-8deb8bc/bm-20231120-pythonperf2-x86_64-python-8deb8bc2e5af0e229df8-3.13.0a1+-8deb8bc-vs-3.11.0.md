
# Results vs. 3.11.0

- fork: python
- ref: 8deb8bc2e5af0e229df8
- machine: linux-x86_64
- commit hash: 8deb8bc
- commit date: 2023-11-20
- overall geometric mean: 1.07x faster \*
- HPT reliability: 99.98%
- HPT 99th percentile: 1.02x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-pythonperf2-x86_64-python-8deb8bc2e5af0e229df8-3.13.0a1+-8deb8bc |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| 2to3           | 286 ms                                                       | 291 ms: 1.02x slower                                                         |
| chameleon      | 7.42 ms                                                      | 7.39 ms: 1.00x faster                                                        |
| docutils       | 2.87 sec                                                     | 2.81 sec: 1.02x faster                                                       |
| tornado_http   | 125 ms                                                       | 119 ms: 1.05x faster                                                         |
| Geometric mean | (ref)                                                        | 1.01x faster                                                                 |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-pythonperf2-x86_64-python-8deb8bc2e5af0e229df8-3.13.0a1+-8deb8bc |
|----------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| async_tree_none            | 529 ms                                                       | 425 ms: 1.24x faster                                                         |
| async_tree_memoization     | 648 ms                                                       | 536 ms: 1.21x faster                                                         |
| async_tree_io              | 1.19 sec                                                     | 1.07 sec: 1.12x faster                                                       |
| async_tree_cpu_io_mixed    | 762 ms                                                       | 685 ms: 1.11x faster                                                         |
| async_tree_none_tg         | 482 ms                                                       | 436 ms: 1.11x faster                                                         |
| async_tree_memoization_tg  | 605 ms                                                       | 553 ms: 1.09x faster                                                         |
| async_tree_io_tg           | 1.17 sec                                                     | 1.08 sec: 1.08x faster                                                       |
| async_tree_cpu_io_mixed_tg | 760 ms                                                       | 704 ms: 1.08x faster                                                         |
| Geometric mean             | (ref)                                                        | 1.13x faster                                                                 |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-pythonperf2-x86_64-python-8deb8bc2e5af0e229df8-3.13.0a1+-8deb8bc |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| nbody          | 95.8 ms                                                      | 85.1 ms: 1.13x faster                                                        |
| float          | 76.0 ms                                                      | 78.5 ms: 1.03x slower                                                        |
| pidigits       | 251 ms                                                       | 266 ms: 1.06x slower                                                         |
| Geometric mean | (ref)                                                        | 1.01x faster                                                                 |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-pythonperf2-x86_64-python-8deb8bc2e5af0e229df8-3.13.0a1+-8deb8bc |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| regex_compile  | 157 ms                                                       | 141 ms: 1.11x faster                                                         |
| regex_effbot   | 3.42 ms                                                      | 3.51 ms: 1.03x slower                                                        |
| regex_v8       | 23.7 ms                                                      | 24.8 ms: 1.05x slower                                                        |
| regex_dna      | 226 ms                                                       | 242 ms: 1.07x slower                                                         |
| Geometric mean | (ref)                                                        | 1.01x slower                                                                 |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-pythonperf2-x86_64-python-8deb8bc2e5af0e229df8-3.13.0a1+-8deb8bc |
|----------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| json_dumps           | 13.5 ms                                                      | 10.7 ms: 1.26x faster                                                        |
| json_loads           | 29.0 us                                                      | 25.5 us: 1.14x faster                                                        |
| xml_etree_parse      | 159 ms                                                       | 148 ms: 1.08x faster                                                         |
| unpickle_pure_python | 236 us                                                       | 222 us: 1.06x faster                                                         |
| pickle_pure_python   | 318 us                                                       | 302 us: 1.05x faster                                                         |
| tomli_loads          | 2.27 sec                                                     | 2.18 sec: 1.05x faster                                                       |
| pickle_dict          | 31.8 us                                                      | 33.1 us: 1.04x slower                                                        |
| unpickle_list        | 4.47 us                                                      | 4.66 us: 1.04x slower                                                        |
| pickle               | 9.77 us                                                      | 10.2 us: 1.04x slower                                                        |
| xml_etree_process    | 56.1 ms                                                      | 58.5 ms: 1.04x slower                                                        |
| xml_etree_generate   | 80.5 ms                                                      | 85.3 ms: 1.06x slower                                                        |
| unpickle             | 13.2 us                                                      | 15.0 us: 1.13x slower                                                        |
| pickle_list          | 3.89 us                                                      | 4.47 us: 1.15x slower                                                        |
| Geometric mean       | (ref)                                                        | 1.01x faster                                                                 |

Benchmark hidden because not significant (1): xml_etree_iterparse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-pythonperf2-x86_64-python-8deb8bc2e5af0e229df8-3.13.0a1+-8deb8bc |
|------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| python_startup         | 10.8 ms                                                      | 12.8 ms: 1.18x slower                                                        |
| python_startup_no_site | 7.78 ms                                                      | 11.3 ms: 1.45x slower                                                        |
| Geometric mean         | (ref)                                                        | 1.31x slower                                                                 |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-pythonperf2-x86_64-python-8deb8bc2e5af0e229df8-3.13.0a1+-8deb8bc |
|-----------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| mako      | 11.0 ms                                                      | 10.2 ms: 1.08x faster                                                        |

All benchmarks:
===============

| Benchmark                  | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-pythonperf2-x86_64-python-8deb8bc2e5af0e229df8-3.13.0a1+-8deb8bc |
|----------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| typing_runtime_protocols   | 527 us                                                       | 123 us: 4.28x faster                                                         |
| asyncio_tcp                | 752 ms                                                       | 368 ms: 2.05x faster                                                         |
| asyncio_tcp_ssl            | 3.09 sec                                                     | 1.57 sec: 1.97x faster                                                       |
| generators                 | 56.4 ms                                                      | 34.4 ms: 1.64x faster                                                        |
| comprehensions             | 24.8 us                                                      | 16.3 us: 1.52x faster                                                        |
| json_dumps                 | 13.5 ms                                                      | 10.7 ms: 1.26x faster                                                        |
| coroutines                 | 27.9 ms                                                      | 22.2 ms: 1.25x faster                                                        |
| async_tree_none            | 529 ms                                                       | 425 ms: 1.24x faster                                                         |
| mypy2                      | 449 ms                                                       | 363 ms: 1.24x faster                                                         |
| sympy_sum                  | 184 ms                                                       | 151 ms: 1.22x faster                                                         |
| fannkuch                   | 457 ms                                                       | 378 ms: 1.21x faster                                                         |
| async_tree_memoization     | 648 ms                                                       | 536 ms: 1.21x faster                                                         |
| chaos                      | 71.6 ms                                                      | 60.1 ms: 1.19x faster                                                        |
| crypto_pyaes               | 81.8 ms                                                      | 69.7 ms: 1.17x faster                                                        |
| raytrace                   | 308 ms                                                       | 264 ms: 1.16x faster                                                         |
| sympy_str                  | 336 ms                                                       | 289 ms: 1.16x faster                                                         |
| json_loads                 | 29.0 us                                                      | 25.5 us: 1.14x faster                                                        |
| richards_super             | 65.2 ms                                                      | 57.5 ms: 1.13x faster                                                        |
| sqlglot_parse              | 1.55 ms                                                      | 1.37 ms: 1.13x faster                                                        |
| scimark_lu                 | 115 ms                                                       | 102 ms: 1.13x faster                                                         |
| nbody                      | 95.8 ms                                                      | 85.1 ms: 1.13x faster                                                        |
| nqueens                    | 99.2 ms                                                      | 88.1 ms: 1.13x faster                                                        |
| sympy_expand               | 550 ms                                                       | 490 ms: 1.12x faster                                                         |
| sympy_integrate            | 25.6 ms                                                      | 22.8 ms: 1.12x faster                                                        |
| deltablue                  | 4.03 ms                                                      | 3.59 ms: 1.12x faster                                                        |
| async_tree_io              | 1.19 sec                                                     | 1.07 sec: 1.12x faster                                                       |
| async_tree_cpu_io_mixed    | 762 ms                                                       | 685 ms: 1.11x faster                                                         |
| regex_compile              | 157 ms                                                       | 141 ms: 1.11x faster                                                         |
| async_tree_none_tg         | 482 ms                                                       | 436 ms: 1.11x faster                                                         |
| logging_format             | 7.83 us                                                      | 7.11 us: 1.10x faster                                                        |
| logging_simple             | 7.21 us                                                      | 6.55 us: 1.10x faster                                                        |
| async_tree_memoization_tg  | 605 ms                                                       | 553 ms: 1.09x faster                                                         |
| sqlglot_transpile          | 1.94 ms                                                      | 1.78 ms: 1.09x faster                                                        |
| mdp                        | 2.72 sec                                                     | 2.49 sec: 1.09x faster                                                       |
| hexiom                     | 6.97 ms                                                      | 6.39 ms: 1.09x faster                                                        |
| deepcopy                   | 389 us                                                       | 357 us: 1.09x faster                                                         |
| async_tree_io_tg           | 1.17 sec                                                     | 1.08 sec: 1.08x faster                                                       |
| gc_traversal               | 4.06 ms                                                      | 3.75 ms: 1.08x faster                                                        |
| mako                       | 11.0 ms                                                      | 10.2 ms: 1.08x faster                                                        |
| async_tree_cpu_io_mixed_tg | 760 ms                                                       | 704 ms: 1.08x faster                                                         |
| xml_etree_parse            | 159 ms                                                       | 148 ms: 1.08x faster                                                         |
| json                       | 5.59 ms                                                      | 5.21 ms: 1.07x faster                                                        |
| sqlglot_normalize          | 122 ms                                                       | 114 ms: 1.07x faster                                                         |
| logging_silent             | 102 ns                                                       | 95.6 ns: 1.07x faster                                                        |
| unpickle_pure_python       | 236 us                                                       | 222 us: 1.06x faster                                                         |
| bench_thread_pool          | 1.02 ms                                                      | 963 us: 1.06x faster                                                         |
| dask                       | 417 ms                                                       | 396 ms: 1.05x faster                                                         |
| pickle_pure_python         | 318 us                                                       | 302 us: 1.05x faster                                                         |
| tornado_http               | 125 ms                                                       | 119 ms: 1.05x faster                                                         |
| scimark_monte_carlo        | 70.6 ms                                                      | 67.2 ms: 1.05x faster                                                        |
| tomli_loads                | 2.27 sec                                                     | 2.18 sec: 1.05x faster                                                       |
| deepcopy_reduce            | 3.37 us                                                      | 3.24 us: 1.04x faster                                                        |
| spectral_norm              | 94.0 ms                                                      | 90.8 ms: 1.04x faster                                                        |
| sqlglot_optimize           | 59.2 ms                                                      | 57.8 ms: 1.03x faster                                                        |
| meteor_contest             | 130 ms                                                       | 128 ms: 1.02x faster                                                         |
| pathlib                    | 19.1 ms                                                      | 18.8 ms: 1.02x faster                                                        |
| docutils                   | 2.87 sec                                                     | 2.81 sec: 1.02x faster                                                       |
| deepcopy_memo              | 37.3 us                                                      | 36.6 us: 1.02x faster                                                        |
| pprint_pformat             | 1.63 sec                                                     | 1.61 sec: 1.01x faster                                                       |
| dulwich_log                | 68.3 ms                                                      | 67.6 ms: 1.01x faster                                                        |
| chameleon                  | 7.42 ms                                                      | 7.39 ms: 1.00x faster                                                        |
| go                         | 166 ms                                                       | 168 ms: 1.01x slower                                                         |
| pprint_safe_repr           | 780 ms                                                       | 791 ms: 1.01x slower                                                         |
| create_gc_cycles           | 1.59 ms                                                      | 1.62 ms: 1.02x slower                                                        |
| 2to3                       | 286 ms                                                       | 291 ms: 1.02x slower                                                         |
| regex_effbot               | 3.42 ms                                                      | 3.51 ms: 1.03x slower                                                        |
| scimark_sparse_mat_mult    | 4.04 ms                                                      | 4.15 ms: 1.03x slower                                                        |
| pycparser                  | 1.28 sec                                                     | 1.32 sec: 1.03x slower                                                       |
| float                      | 76.0 ms                                                      | 78.5 ms: 1.03x slower                                                        |
| unpack_sequence            | 44.9 ns                                                      | 46.4 ns: 1.03x slower                                                        |
| pickle_dict                | 31.8 us                                                      | 33.1 us: 1.04x slower                                                        |
| unpickle_list              | 4.47 us                                                      | 4.66 us: 1.04x slower                                                        |
| pickle                     | 9.77 us                                                      | 10.2 us: 1.04x slower                                                        |
| xml_etree_process          | 56.1 ms                                                      | 58.5 ms: 1.04x slower                                                        |
| richards                   | 49.9 ms                                                      | 52.2 ms: 1.05x slower                                                        |
| regex_v8                   | 23.7 ms                                                      | 24.8 ms: 1.05x slower                                                        |
| pidigits                   | 251 ms                                                       | 266 ms: 1.06x slower                                                         |
| xml_etree_generate         | 80.5 ms                                                      | 85.3 ms: 1.06x slower                                                        |
| regex_dna                  | 226 ms                                                       | 242 ms: 1.07x slower                                                         |
| scimark_fft                | 281 ms                                                       | 303 ms: 1.08x slower                                                         |
| sqlite_synth               | 2.49 us                                                      | 2.71 us: 1.09x slower                                                        |
| async_generators           | 322 ms                                                       | 363 ms: 1.13x slower                                                         |
| unpickle                   | 13.2 us                                                      | 15.0 us: 1.13x slower                                                        |
| pickle_list                | 3.89 us                                                      | 4.47 us: 1.15x slower                                                        |
| telco                      | 6.91 ms                                                      | 8.08 ms: 1.17x slower                                                        |
| pyflate                    | 453 ms                                                       | 532 ms: 1.18x slower                                                         |
| python_startup             | 10.8 ms                                                      | 12.8 ms: 1.18x slower                                                        |
| coverage                   | 66.6 ms                                                      | 79.7 ms: 1.20x slower                                                        |
| scimark_sor                | 109 ms                                                       | 147 ms: 1.34x slower                                                         |
| python_startup_no_site     | 7.78 ms                                                      | 11.3 ms: 1.45x slower                                                        |
| Geometric mean             | (ref)                                                        | 1.07x faster                                                                 |

Benchmark hidden because not significant (3): asyncio_websockets, bench_mp_pool, xml_etree_iterparse
Ignored benchmarks (11) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift


# HPT report

- Reliability score: 99.98% likely to be faster
- 90% likely to have a speedup of 1.04x
- 95% likely to have a speedup of 1.03x
- 99% likely to have a speedup of 1.02x
