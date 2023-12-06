
# Results vs. 3.11.0

- fork: python
- ref: 1a969b4f55f92a17bec8
- machine: linux-x86_64
- commit hash: 1a969b4
- commit date: 2023-11-19
- overall geometric mean: 1.07x faster \*
- HPT reliability: 99.96%
- HPT 99th percentile: 1.01x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231119-pythonperf2-x86_64-python-1a969b4f55f92a17bec8-3.13.0a1+-1a969b4 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| 2to3           | 286 ms                                                       | 293 ms: 1.02x slower                                                         |
| chameleon      | 7.42 ms                                                      | 7.58 ms: 1.02x slower                                                        |
| docutils       | 2.87 sec                                                     | 2.82 sec: 1.02x faster                                                       |
| tornado_http   | 125 ms                                                       | 118 ms: 1.06x faster                                                         |
| Geometric mean | (ref)                                                        | 1.01x faster                                                                 |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231119-pythonperf2-x86_64-python-1a969b4f55f92a17bec8-3.13.0a1+-1a969b4 |
|----------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| async_tree_none            | 529 ms                                                       | 433 ms: 1.22x faster                                                         |
| async_tree_memoization     | 648 ms                                                       | 545 ms: 1.19x faster                                                         |
| async_tree_io              | 1.19 sec                                                     | 1.08 sec: 1.11x faster                                                       |
| async_tree_none_tg         | 482 ms                                                       | 438 ms: 1.10x faster                                                         |
| async_tree_cpu_io_mixed    | 762 ms                                                       | 693 ms: 1.10x faster                                                         |
| async_tree_cpu_io_mixed_tg | 760 ms                                                       | 709 ms: 1.07x faster                                                         |
| async_tree_io_tg           | 1.17 sec                                                     | 1.09 sec: 1.07x faster                                                       |
| async_tree_memoization_tg  | 605 ms                                                       | 569 ms: 1.06x faster                                                         |
| Geometric mean             | (ref)                                                        | 1.11x faster                                                                 |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231119-pythonperf2-x86_64-python-1a969b4f55f92a17bec8-3.13.0a1+-1a969b4 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| nbody          | 95.8 ms                                                      | 83.7 ms: 1.14x faster                                                        |
| pidigits       | 251 ms                                                       | 265 ms: 1.06x slower                                                         |
| float          | 76.0 ms                                                      | 80.7 ms: 1.06x slower                                                        |
| Geometric mean | (ref)                                                        | 1.01x faster                                                                 |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231119-pythonperf2-x86_64-python-1a969b4f55f92a17bec8-3.13.0a1+-1a969b4 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| regex_compile  | 157 ms                                                       | 145 ms: 1.08x faster                                                         |
| regex_effbot   | 3.42 ms                                                      | 3.49 ms: 1.02x slower                                                        |
| regex_v8       | 23.7 ms                                                      | 25.2 ms: 1.07x slower                                                        |
| regex_dna      | 226 ms                                                       | 251 ms: 1.11x slower                                                         |
| Geometric mean | (ref)                                                        | 1.03x slower                                                                 |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231119-pythonperf2-x86_64-python-1a969b4f55f92a17bec8-3.13.0a1+-1a969b4 |
|----------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| json_dumps           | 13.5 ms                                                      | 10.5 ms: 1.28x faster                                                        |
| json_loads           | 29.0 us                                                      | 25.2 us: 1.15x faster                                                        |
| xml_etree_parse      | 159 ms                                                       | 151 ms: 1.05x faster                                                         |
| pickle_pure_python   | 318 us                                                       | 309 us: 1.03x faster                                                         |
| unpickle_pure_python | 236 us                                                       | 229 us: 1.03x faster                                                         |
| tomli_loads          | 2.27 sec                                                     | 2.29 sec: 1.01x slower                                                       |
| xml_etree_iterparse  | 106 ms                                                       | 107 ms: 1.01x slower                                                         |
| pickle_dict          | 31.8 us                                                      | 32.2 us: 1.01x slower                                                        |
| pickle               | 9.77 us                                                      | 10.1 us: 1.03x slower                                                        |
| xml_etree_process    | 56.1 ms                                                      | 58.2 ms: 1.04x slower                                                        |
| unpickle_list        | 4.47 us                                                      | 4.64 us: 1.04x slower                                                        |
| xml_etree_generate   | 80.5 ms                                                      | 85.3 ms: 1.06x slower                                                        |
| unpickle             | 13.2 us                                                      | 14.2 us: 1.08x slower                                                        |
| pickle_list          | 3.89 us                                                      | 4.39 us: 1.13x slower                                                        |
| Geometric mean       | (ref)                                                        | 1.01x faster                                                                 |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231119-pythonperf2-x86_64-python-1a969b4f55f92a17bec8-3.13.0a1+-1a969b4 |
|------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| python_startup         | 10.8 ms                                                      | 12.8 ms: 1.18x slower                                                        |
| python_startup_no_site | 7.78 ms                                                      | 11.2 ms: 1.44x slower                                                        |
| Geometric mean         | (ref)                                                        | 1.31x slower                                                                 |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231119-pythonperf2-x86_64-python-1a969b4f55f92a17bec8-3.13.0a1+-1a969b4 |
|-----------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| mako      | 11.0 ms                                                      | 10.1 ms: 1.09x faster                                                        |

All benchmarks:
===============

| Benchmark                  | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231119-pythonperf2-x86_64-python-1a969b4f55f92a17bec8-3.13.0a1+-1a969b4 |
|----------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| typing_runtime_protocols   | 527 us                                                       | 127 us: 4.16x faster                                                         |
| asyncio_tcp                | 752 ms                                                       | 375 ms: 2.00x faster                                                         |
| asyncio_tcp_ssl            | 3.09 sec                                                     | 1.57 sec: 1.97x faster                                                       |
| generators                 | 56.4 ms                                                      | 34.3 ms: 1.64x faster                                                        |
| comprehensions             | 24.8 us                                                      | 16.7 us: 1.49x faster                                                        |
| json_dumps                 | 13.5 ms                                                      | 10.5 ms: 1.28x faster                                                        |
| coroutines                 | 27.9 ms                                                      | 22.2 ms: 1.25x faster                                                        |
| sympy_sum                  | 184 ms                                                       | 150 ms: 1.23x faster                                                         |
| mypy2                      | 449 ms                                                       | 366 ms: 1.23x faster                                                         |
| async_tree_none            | 529 ms                                                       | 433 ms: 1.22x faster                                                         |
| fannkuch                   | 457 ms                                                       | 380 ms: 1.20x faster                                                         |
| async_tree_memoization     | 648 ms                                                       | 545 ms: 1.19x faster                                                         |
| chaos                      | 71.6 ms                                                      | 60.4 ms: 1.19x faster                                                        |
| sympy_str                  | 336 ms                                                       | 288 ms: 1.16x faster                                                         |
| crypto_pyaes               | 81.8 ms                                                      | 70.4 ms: 1.16x faster                                                        |
| raytrace                   | 308 ms                                                       | 268 ms: 1.15x faster                                                         |
| json_loads                 | 29.0 us                                                      | 25.2 us: 1.15x faster                                                        |
| nbody                      | 95.8 ms                                                      | 83.7 ms: 1.14x faster                                                        |
| deltablue                  | 4.03 ms                                                      | 3.55 ms: 1.13x faster                                                        |
| richards_super             | 65.2 ms                                                      | 58.0 ms: 1.12x faster                                                        |
| sympy_expand               | 550 ms                                                       | 491 ms: 1.12x faster                                                         |
| scimark_lu                 | 115 ms                                                       | 103 ms: 1.12x faster                                                         |
| sympy_integrate            | 25.6 ms                                                      | 22.9 ms: 1.12x faster                                                        |
| nqueens                    | 99.2 ms                                                      | 89.3 ms: 1.11x faster                                                        |
| logging_simple             | 7.21 us                                                      | 6.50 us: 1.11x faster                                                        |
| async_tree_io              | 1.19 sec                                                     | 1.08 sec: 1.11x faster                                                       |
| sqlglot_parse              | 1.55 ms                                                      | 1.41 ms: 1.10x faster                                                        |
| async_tree_none_tg         | 482 ms                                                       | 438 ms: 1.10x faster                                                         |
| async_tree_cpu_io_mixed    | 762 ms                                                       | 693 ms: 1.10x faster                                                         |
| logging_format             | 7.83 us                                                      | 7.16 us: 1.09x faster                                                        |
| hexiom                     | 6.97 ms                                                      | 6.39 ms: 1.09x faster                                                        |
| mako                       | 11.0 ms                                                      | 10.1 ms: 1.09x faster                                                        |
| mdp                        | 2.72 sec                                                     | 2.50 sec: 1.09x faster                                                       |
| gc_traversal               | 4.06 ms                                                      | 3.74 ms: 1.09x faster                                                        |
| regex_compile              | 157 ms                                                       | 145 ms: 1.08x faster                                                         |
| json                       | 5.59 ms                                                      | 5.20 ms: 1.07x faster                                                        |
| async_tree_cpu_io_mixed_tg | 760 ms                                                       | 709 ms: 1.07x faster                                                         |
| async_tree_io_tg           | 1.17 sec                                                     | 1.09 sec: 1.07x faster                                                       |
| sqlglot_transpile          | 1.94 ms                                                      | 1.82 ms: 1.07x faster                                                        |
| bench_thread_pool          | 1.02 ms                                                      | 956 us: 1.07x faster                                                         |
| async_tree_memoization_tg  | 605 ms                                                       | 569 ms: 1.06x faster                                                         |
| tornado_http               | 125 ms                                                       | 118 ms: 1.06x faster                                                         |
| dask                       | 417 ms                                                       | 395 ms: 1.06x faster                                                         |
| logging_silent             | 102 ns                                                       | 96.6 ns: 1.06x faster                                                        |
| sqlglot_normalize          | 122 ms                                                       | 116 ms: 1.05x faster                                                         |
| xml_etree_parse            | 159 ms                                                       | 151 ms: 1.05x faster                                                         |
| scimark_monte_carlo        | 70.6 ms                                                      | 67.4 ms: 1.05x faster                                                        |
| deepcopy                   | 389 us                                                       | 374 us: 1.04x faster                                                         |
| spectral_norm              | 94.0 ms                                                      | 90.4 ms: 1.04x faster                                                        |
| pathlib                    | 19.1 ms                                                      | 18.5 ms: 1.04x faster                                                        |
| pickle_pure_python         | 318 us                                                       | 309 us: 1.03x faster                                                         |
| unpickle_pure_python       | 236 us                                                       | 229 us: 1.03x faster                                                         |
| deepcopy_reduce            | 3.37 us                                                      | 3.29 us: 1.02x faster                                                        |
| meteor_contest             | 130 ms                                                       | 128 ms: 1.02x faster                                                         |
| pprint_pformat             | 1.63 sec                                                     | 1.60 sec: 1.02x faster                                                       |
| sqlglot_optimize           | 59.2 ms                                                      | 58.1 ms: 1.02x faster                                                        |
| unpack_sequence            | 44.9 ns                                                      | 44.1 ns: 1.02x faster                                                        |
| docutils                   | 2.87 sec                                                     | 2.82 sec: 1.02x faster                                                       |
| dulwich_log                | 68.3 ms                                                      | 67.3 ms: 1.01x faster                                                        |
| pprint_safe_repr           | 780 ms                                                       | 786 ms: 1.01x slower                                                         |
| tomli_loads                | 2.27 sec                                                     | 2.29 sec: 1.01x slower                                                       |
| xml_etree_iterparse        | 106 ms                                                       | 107 ms: 1.01x slower                                                         |
| asyncio_websockets         | 388 ms                                                       | 393 ms: 1.01x slower                                                         |
| pickle_dict                | 31.8 us                                                      | 32.2 us: 1.01x slower                                                        |
| deepcopy_memo              | 37.3 us                                                      | 37.8 us: 1.01x slower                                                        |
| go                         | 166 ms                                                       | 168 ms: 1.01x slower                                                         |
| chameleon                  | 7.42 ms                                                      | 7.58 ms: 1.02x slower                                                        |
| regex_effbot               | 3.42 ms                                                      | 3.49 ms: 1.02x slower                                                        |
| 2to3                       | 286 ms                                                       | 293 ms: 1.02x slower                                                         |
| pickle                     | 9.77 us                                                      | 10.1 us: 1.03x slower                                                        |
| xml_etree_process          | 56.1 ms                                                      | 58.2 ms: 1.04x slower                                                        |
| unpickle_list              | 4.47 us                                                      | 4.64 us: 1.04x slower                                                        |
| richards                   | 49.9 ms                                                      | 52.3 ms: 1.05x slower                                                        |
| scimark_sparse_mat_mult    | 4.04 ms                                                      | 4.24 ms: 1.05x slower                                                        |
| pidigits                   | 251 ms                                                       | 265 ms: 1.06x slower                                                         |
| xml_etree_generate         | 80.5 ms                                                      | 85.3 ms: 1.06x slower                                                        |
| float                      | 76.0 ms                                                      | 80.7 ms: 1.06x slower                                                        |
| regex_v8                   | 23.7 ms                                                      | 25.2 ms: 1.07x slower                                                        |
| sqlite_synth               | 2.49 us                                                      | 2.66 us: 1.07x slower                                                        |
| unpickle                   | 13.2 us                                                      | 14.2 us: 1.08x slower                                                        |
| scimark_fft                | 281 ms                                                       | 307 ms: 1.09x slower                                                         |
| regex_dna                  | 226 ms                                                       | 251 ms: 1.11x slower                                                         |
| async_generators           | 322 ms                                                       | 362 ms: 1.13x slower                                                         |
| pickle_list                | 3.89 us                                                      | 4.39 us: 1.13x slower                                                        |
| pyflate                    | 453 ms                                                       | 513 ms: 1.13x slower                                                         |
| bench_mp_pool              | 4.63 ms                                                      | 5.36 ms: 1.16x slower                                                        |
| telco                      | 6.91 ms                                                      | 8.07 ms: 1.17x slower                                                        |
| python_startup             | 10.8 ms                                                      | 12.8 ms: 1.18x slower                                                        |
| coverage                   | 66.6 ms                                                      | 82.7 ms: 1.24x slower                                                        |
| scimark_sor                | 109 ms                                                       | 145 ms: 1.32x slower                                                         |
| python_startup_no_site     | 7.78 ms                                                      | 11.2 ms: 1.44x slower                                                        |
| Geometric mean             | (ref)                                                        | 1.07x faster                                                                 |

Benchmark hidden because not significant (2): pycparser, create_gc_cycles
Ignored benchmarks (11) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift


# HPT report

- Reliability score: 99.96% likely to be faster
- 90% likely to have a speedup of 1.03x
- 95% likely to have a speedup of 1.02x
- 99% likely to have a speedup of 1.01x
