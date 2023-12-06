
# Results vs. 3.11.0

- fork: python
- ref: 48dfd74a9db9d4aa9c6f
- machine: linux-x86_64
- commit hash: 48dfd74
- commit date: 2023-11-28
- overall geometric mean: 1.06x faster \*
- HPT reliability: 99.95%
- HPT 99th percentile: 1.02x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231128-pythonperf2-x86_64-python-48dfd74a9db9d4aa9c6f-3.13.0a2+-48dfd74 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| 2to3           | 286 ms                                                       | 290 ms: 1.01x slower                                                         |
| docutils       | 2.87 sec                                                     | 2.80 sec: 1.02x faster                                                       |
| tornado_http   | 125 ms                                                       | 117 ms: 1.06x faster                                                         |
| Geometric mean | (ref)                                                        | 1.02x faster                                                                 |

Benchmark hidden because not significant (1): chameleon

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231128-pythonperf2-x86_64-python-48dfd74a9db9d4aa9c6f-3.13.0a2+-48dfd74 |
|----------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| async_tree_none            | 529 ms                                                       | 428 ms: 1.23x faster                                                         |
| async_tree_memoization     | 648 ms                                                       | 540 ms: 1.20x faster                                                         |
| async_tree_io              | 1.19 sec                                                     | 1.07 sec: 1.12x faster                                                       |
| async_tree_none_tg         | 482 ms                                                       | 436 ms: 1.11x faster                                                         |
| async_tree_cpu_io_mixed    | 762 ms                                                       | 695 ms: 1.10x faster                                                         |
| async_tree_memoization_tg  | 605 ms                                                       | 553 ms: 1.09x faster                                                         |
| async_tree_io_tg           | 1.17 sec                                                     | 1.08 sec: 1.08x faster                                                       |
| async_tree_cpu_io_mixed_tg | 760 ms                                                       | 709 ms: 1.07x faster                                                         |
| Geometric mean             | (ref)                                                        | 1.12x faster                                                                 |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231128-pythonperf2-x86_64-python-48dfd74a9db9d4aa9c6f-3.13.0a2+-48dfd74 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| nbody          | 95.8 ms                                                      | 85.2 ms: 1.12x faster                                                        |
| float          | 76.0 ms                                                      | 77.9 ms: 1.02x slower                                                        |
| pidigits       | 251 ms                                                       | 265 ms: 1.06x slower                                                         |
| Geometric mean | (ref)                                                        | 1.01x faster                                                                 |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231128-pythonperf2-x86_64-python-48dfd74a9db9d4aa9c6f-3.13.0a2+-48dfd74 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| regex_compile  | 157 ms                                                       | 143 ms: 1.10x faster                                                         |
| regex_effbot   | 3.42 ms                                                      | 3.52 ms: 1.03x slower                                                        |
| regex_v8       | 23.7 ms                                                      | 25.3 ms: 1.07x slower                                                        |
| regex_dna      | 226 ms                                                       | 244 ms: 1.08x slower                                                         |
| Geometric mean | (ref)                                                        | 1.02x slower                                                                 |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231128-pythonperf2-x86_64-python-48dfd74a9db9d4aa9c6f-3.13.0a2+-48dfd74 |
|----------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| json_dumps           | 13.5 ms                                                      | 10.6 ms: 1.27x faster                                                        |
| json_loads           | 29.0 us                                                      | 25.3 us: 1.14x faster                                                        |
| unpickle_pure_python | 236 us                                                       | 210 us: 1.12x faster                                                         |
| xml_etree_parse      | 159 ms                                                       | 149 ms: 1.07x faster                                                         |
| pickle_pure_python   | 318 us                                                       | 303 us: 1.05x faster                                                         |
| tomli_loads          | 2.27 sec                                                     | 2.21 sec: 1.03x faster                                                       |
| unpickle_list        | 4.47 us                                                      | 4.58 us: 1.02x slower                                                        |
| pickle_dict          | 31.8 us                                                      | 32.7 us: 1.03x slower                                                        |
| xml_etree_process    | 56.1 ms                                                      | 57.9 ms: 1.03x slower                                                        |
| pickle               | 9.77 us                                                      | 10.1 us: 1.04x slower                                                        |
| xml_etree_generate   | 80.5 ms                                                      | 83.8 ms: 1.04x slower                                                        |
| unpickle             | 13.2 us                                                      | 14.5 us: 1.10x slower                                                        |
| pickle_list          | 3.89 us                                                      | 4.47 us: 1.15x slower                                                        |
| Geometric mean       | (ref)                                                        | 1.02x faster                                                                 |

Benchmark hidden because not significant (1): xml_etree_iterparse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231128-pythonperf2-x86_64-python-48dfd74a9db9d4aa9c6f-3.13.0a2+-48dfd74 |
|------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| python_startup         | 10.8 ms                                                      | 12.8 ms: 1.18x slower                                                        |
| python_startup_no_site | 7.78 ms                                                      | 11.2 ms: 1.44x slower                                                        |
| Geometric mean         | (ref)                                                        | 1.31x slower                                                                 |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231128-pythonperf2-x86_64-python-48dfd74a9db9d4aa9c6f-3.13.0a2+-48dfd74 |
|-----------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| mako      | 11.0 ms                                                      | 10.3 ms: 1.07x faster                                                        |

All benchmarks:
===============

| Benchmark                  | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231128-pythonperf2-x86_64-python-48dfd74a9db9d4aa9c6f-3.13.0a2+-48dfd74 |
|----------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| typing_runtime_protocols   | 527 us                                                       | 121 us: 4.34x faster                                                         |
| asyncio_tcp                | 752 ms                                                       | 367 ms: 2.05x faster                                                         |
| asyncio_tcp_ssl            | 3.09 sec                                                     | 1.57 sec: 1.97x faster                                                       |
| generators                 | 56.4 ms                                                      | 34.7 ms: 1.62x faster                                                        |
| comprehensions             | 24.8 us                                                      | 16.6 us: 1.50x faster                                                        |
| json_dumps                 | 13.5 ms                                                      | 10.6 ms: 1.27x faster                                                        |
| coroutines                 | 27.9 ms                                                      | 22.1 ms: 1.26x faster                                                        |
| sympy_sum                  | 184 ms                                                       | 149 ms: 1.24x faster                                                         |
| async_tree_none            | 529 ms                                                       | 428 ms: 1.23x faster                                                         |
| fannkuch                   | 457 ms                                                       | 380 ms: 1.20x faster                                                         |
| async_tree_memoization     | 648 ms                                                       | 540 ms: 1.20x faster                                                         |
| chaos                      | 71.6 ms                                                      | 60.2 ms: 1.19x faster                                                        |
| raytrace                   | 308 ms                                                       | 262 ms: 1.17x faster                                                         |
| sympy_str                  | 336 ms                                                       | 287 ms: 1.17x faster                                                         |
| scimark_lu                 | 115 ms                                                       | 100 ms: 1.15x faster                                                         |
| gc_traversal               | 4.06 ms                                                      | 3.54 ms: 1.15x faster                                                        |
| crypto_pyaes               | 81.8 ms                                                      | 71.3 ms: 1.15x faster                                                        |
| json_loads                 | 29.0 us                                                      | 25.3 us: 1.14x faster                                                        |
| sympy_expand               | 550 ms                                                       | 486 ms: 1.13x faster                                                         |
| logging_simple             | 7.21 us                                                      | 6.37 us: 1.13x faster                                                        |
| sqlglot_parse              | 1.55 ms                                                      | 1.38 ms: 1.13x faster                                                        |
| nbody                      | 95.8 ms                                                      | 85.2 ms: 1.12x faster                                                        |
| unpickle_pure_python       | 236 us                                                       | 210 us: 1.12x faster                                                         |
| sympy_integrate            | 25.6 ms                                                      | 22.9 ms: 1.12x faster                                                        |
| richards_super             | 65.2 ms                                                      | 58.3 ms: 1.12x faster                                                        |
| async_tree_io              | 1.19 sec                                                     | 1.07 sec: 1.12x faster                                                       |
| nqueens                    | 99.2 ms                                                      | 89.0 ms: 1.11x faster                                                        |
| deltablue                  | 4.03 ms                                                      | 3.62 ms: 1.11x faster                                                        |
| async_tree_none_tg         | 482 ms                                                       | 436 ms: 1.11x faster                                                         |
| regex_compile              | 157 ms                                                       | 143 ms: 1.10x faster                                                         |
| logging_format             | 7.83 us                                                      | 7.14 us: 1.10x faster                                                        |
| async_tree_cpu_io_mixed    | 762 ms                                                       | 695 ms: 1.10x faster                                                         |
| deepcopy                   | 389 us                                                       | 356 us: 1.09x faster                                                         |
| sqlglot_transpile          | 1.94 ms                                                      | 1.77 ms: 1.09x faster                                                        |
| async_tree_memoization_tg  | 605 ms                                                       | 553 ms: 1.09x faster                                                         |
| json                       | 5.59 ms                                                      | 5.12 ms: 1.09x faster                                                        |
| hexiom                     | 6.97 ms                                                      | 6.44 ms: 1.08x faster                                                        |
| async_tree_io_tg           | 1.17 sec                                                     | 1.08 sec: 1.08x faster                                                       |
| mdp                        | 2.72 sec                                                     | 2.52 sec: 1.08x faster                                                       |
| async_tree_cpu_io_mixed_tg | 760 ms                                                       | 709 ms: 1.07x faster                                                         |
| scimark_monte_carlo        | 70.6 ms                                                      | 66.1 ms: 1.07x faster                                                        |
| mako                       | 11.0 ms                                                      | 10.3 ms: 1.07x faster                                                        |
| xml_etree_parse            | 159 ms                                                       | 149 ms: 1.07x faster                                                         |
| tornado_http               | 125 ms                                                       | 117 ms: 1.06x faster                                                         |
| sqlglot_normalize          | 122 ms                                                       | 115 ms: 1.06x faster                                                         |
| bench_thread_pool          | 1.02 ms                                                      | 964 us: 1.06x faster                                                         |
| dask                       | 417 ms                                                       | 396 ms: 1.05x faster                                                         |
| deepcopy_reduce            | 3.37 us                                                      | 3.20 us: 1.05x faster                                                        |
| pickle_pure_python         | 318 us                                                       | 303 us: 1.05x faster                                                         |
| logging_silent             | 102 ns                                                       | 97.2 ns: 1.05x faster                                                        |
| spectral_norm              | 94.0 ms                                                      | 90.5 ms: 1.04x faster                                                        |
| meteor_contest             | 130 ms                                                       | 126 ms: 1.03x faster                                                         |
| tomli_loads                | 2.27 sec                                                     | 2.21 sec: 1.03x faster                                                       |
| docutils                   | 2.87 sec                                                     | 2.80 sec: 1.02x faster                                                       |
| pathlib                    | 19.1 ms                                                      | 18.8 ms: 1.02x faster                                                        |
| deepcopy_memo              | 37.3 us                                                      | 36.6 us: 1.02x faster                                                        |
| sqlglot_optimize           | 59.2 ms                                                      | 58.1 ms: 1.02x faster                                                        |
| pycparser                  | 1.28 sec                                                     | 1.27 sec: 1.01x faster                                                       |
| dulwich_log                | 68.3 ms                                                      | 67.4 ms: 1.01x faster                                                        |
| 2to3                       | 286 ms                                                       | 290 ms: 1.01x slower                                                         |
| pprint_safe_repr           | 780 ms                                                       | 797 ms: 1.02x slower                                                         |
| unpickle_list              | 4.47 us                                                      | 4.58 us: 1.02x slower                                                        |
| float                      | 76.0 ms                                                      | 77.9 ms: 1.02x slower                                                        |
| pickle_dict                | 31.8 us                                                      | 32.7 us: 1.03x slower                                                        |
| xml_etree_process          | 56.1 ms                                                      | 57.9 ms: 1.03x slower                                                        |
| regex_effbot               | 3.42 ms                                                      | 3.52 ms: 1.03x slower                                                        |
| go                         | 166 ms                                                       | 172 ms: 1.04x slower                                                         |
| pickle                     | 9.77 us                                                      | 10.1 us: 1.04x slower                                                        |
| xml_etree_generate         | 80.5 ms                                                      | 83.8 ms: 1.04x slower                                                        |
| richards                   | 49.9 ms                                                      | 52.4 ms: 1.05x slower                                                        |
| pidigits                   | 251 ms                                                       | 265 ms: 1.06x slower                                                         |
| regex_v8                   | 23.7 ms                                                      | 25.3 ms: 1.07x slower                                                        |
| regex_dna                  | 226 ms                                                       | 244 ms: 1.08x slower                                                         |
| sqlite_synth               | 2.49 us                                                      | 2.69 us: 1.08x slower                                                        |
| unpickle                   | 13.2 us                                                      | 14.5 us: 1.10x slower                                                        |
| scimark_fft                | 281 ms                                                       | 313 ms: 1.11x slower                                                         |
| scimark_sparse_mat_mult    | 4.04 ms                                                      | 4.51 ms: 1.12x slower                                                        |
| pyflate                    | 453 ms                                                       | 506 ms: 1.12x slower                                                         |
| async_generators           | 322 ms                                                       | 364 ms: 1.13x slower                                                         |
| pickle_list                | 3.89 us                                                      | 4.47 us: 1.15x slower                                                        |
| python_startup             | 10.8 ms                                                      | 12.8 ms: 1.18x slower                                                        |
| telco                      | 6.91 ms                                                      | 8.17 ms: 1.18x slower                                                        |
| coverage                   | 66.6 ms                                                      | 79.0 ms: 1.19x slower                                                        |
| unpack_sequence            | 44.9 ns                                                      | 57.4 ns: 1.28x slower                                                        |
| scimark_sor                | 109 ms                                                       | 145 ms: 1.33x slower                                                         |
| python_startup_no_site     | 7.78 ms                                                      | 11.2 ms: 1.44x slower                                                        |
| mypy2                      | 449 ms                                                       | 859 ms: 1.91x slower                                                         |
| Geometric mean             | (ref)                                                        | 1.06x faster                                                                 |

Benchmark hidden because not significant (6): bench_mp_pool, asyncio_websockets, pprint_pformat, chameleon, xml_etree_iterparse, create_gc_cycles
Ignored benchmarks (11) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift


# HPT report

- Reliability score: 99.95% likely to be faster
- 90% likely to have a speedup of 1.03x
- 95% likely to have a speedup of 1.02x
- 99% likely to have a speedup of 1.02x
