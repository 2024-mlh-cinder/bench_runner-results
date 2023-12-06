
# Results vs. 3.11.0

- fork: python
- ref: fa84e5fe0a3bd8e77c33
- machine: linux-x86_64
- commit hash: fa84e5f
- commit date: 2023-11-11
- overall geometric mean: 1.07x faster \*
- HPT reliability: 99.91%
- HPT 99th percentile: 1.01x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231111-pythonperf2-x86_64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| 2to3           | 286 ms                                                       | 292 ms: 1.02x slower                                                         |
| chameleon      | 7.42 ms                                                      | 7.22 ms: 1.03x faster                                                        |
| docutils       | 2.87 sec                                                     | 2.84 sec: 1.01x faster                                                       |
| tornado_http   | 125 ms                                                       | 119 ms: 1.05x faster                                                         |
| Geometric mean | (ref)                                                        | 1.02x faster                                                                 |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231111-pythonperf2-x86_64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f |
|----------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| async_tree_none            | 529 ms                                                       | 433 ms: 1.22x faster                                                         |
| async_tree_memoization     | 648 ms                                                       | 546 ms: 1.19x faster                                                         |
| async_tree_io              | 1.19 sec                                                     | 1.08 sec: 1.10x faster                                                       |
| async_tree_none_tg         | 482 ms                                                       | 439 ms: 1.10x faster                                                         |
| async_tree_cpu_io_mixed    | 762 ms                                                       | 695 ms: 1.10x faster                                                         |
| async_tree_memoization_tg  | 605 ms                                                       | 561 ms: 1.08x faster                                                         |
| async_tree_cpu_io_mixed_tg | 760 ms                                                       | 711 ms: 1.07x faster                                                         |
| async_tree_io_tg           | 1.17 sec                                                     | 1.10 sec: 1.07x faster                                                       |
| Geometric mean             | (ref)                                                        | 1.11x faster                                                                 |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231111-pythonperf2-x86_64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| nbody          | 95.8 ms                                                      | 84.7 ms: 1.13x faster                                                        |
| float          | 76.0 ms                                                      | 79.3 ms: 1.04x slower                                                        |
| pidigits       | 251 ms                                                       | 265 ms: 1.05x slower                                                         |
| Geometric mean | (ref)                                                        | 1.01x faster                                                                 |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231111-pythonperf2-x86_64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| regex_compile  | 157 ms                                                       | 143 ms: 1.10x faster                                                         |
| regex_effbot   | 3.42 ms                                                      | 3.43 ms: 1.00x slower                                                        |
| regex_dna      | 226 ms                                                       | 244 ms: 1.08x slower                                                         |
| regex_v8       | 23.7 ms                                                      | 25.7 ms: 1.08x slower                                                        |
| Geometric mean | (ref)                                                        | 1.02x slower                                                                 |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231111-pythonperf2-x86_64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f |
|----------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| json_dumps           | 13.5 ms                                                      | 10.6 ms: 1.27x faster                                                        |
| json_loads           | 29.0 us                                                      | 24.6 us: 1.18x faster                                                        |
| xml_etree_parse      | 159 ms                                                       | 146 ms: 1.09x faster                                                         |
| unpickle_pure_python | 236 us                                                       | 222 us: 1.06x faster                                                         |
| tomli_loads          | 2.27 sec                                                     | 2.23 sec: 1.02x faster                                                       |
| pickle_pure_python   | 318 us                                                       | 321 us: 1.01x slower                                                         |
| pickle_dict          | 31.8 us                                                      | 32.7 us: 1.03x slower                                                        |
| pickle               | 9.77 us                                                      | 10.1 us: 1.04x slower                                                        |
| xml_etree_process    | 56.1 ms                                                      | 58.4 ms: 1.04x slower                                                        |
| xml_etree_generate   | 80.5 ms                                                      | 85.5 ms: 1.06x slower                                                        |
| unpickle_list        | 4.47 us                                                      | 4.76 us: 1.06x slower                                                        |
| unpickle             | 13.2 us                                                      | 14.4 us: 1.09x slower                                                        |
| pickle_list          | 3.89 us                                                      | 4.36 us: 1.12x slower                                                        |
| Geometric mean       | (ref)                                                        | 1.01x faster                                                                 |

Benchmark hidden because not significant (1): xml_etree_iterparse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231111-pythonperf2-x86_64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f |
|------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| python_startup         | 10.8 ms                                                      | 12.8 ms: 1.19x slower                                                        |
| python_startup_no_site | 7.78 ms                                                      | 11.3 ms: 1.45x slower                                                        |
| Geometric mean         | (ref)                                                        | 1.31x slower                                                                 |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231111-pythonperf2-x86_64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f |
|-----------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| mako      | 11.0 ms                                                      | 10.1 ms: 1.09x faster                                                        |

All benchmarks:
===============

| Benchmark                  | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231111-pythonperf2-x86_64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f |
|----------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| typing_runtime_protocols   | 527 us                                                       | 124 us: 4.23x faster                                                         |
| asyncio_tcp                | 752 ms                                                       | 369 ms: 2.04x faster                                                         |
| asyncio_tcp_ssl            | 3.09 sec                                                     | 1.58 sec: 1.95x faster                                                       |
| generators                 | 56.4 ms                                                      | 35.9 ms: 1.57x faster                                                        |
| comprehensions             | 24.8 us                                                      | 16.3 us: 1.52x faster                                                        |
| json_dumps                 | 13.5 ms                                                      | 10.6 ms: 1.27x faster                                                        |
| coroutines                 | 27.9 ms                                                      | 22.2 ms: 1.26x faster                                                        |
| mypy2                      | 449 ms                                                       | 366 ms: 1.23x faster                                                         |
| sympy_sum                  | 184 ms                                                       | 151 ms: 1.22x faster                                                         |
| async_tree_none            | 529 ms                                                       | 433 ms: 1.22x faster                                                         |
| async_tree_memoization     | 648 ms                                                       | 546 ms: 1.19x faster                                                         |
| json_loads                 | 29.0 us                                                      | 24.6 us: 1.18x faster                                                        |
| scimark_lu                 | 115 ms                                                       | 98.6 ms: 1.17x faster                                                        |
| chaos                      | 71.6 ms                                                      | 61.4 ms: 1.17x faster                                                        |
| gc_traversal               | 4.06 ms                                                      | 3.49 ms: 1.16x faster                                                        |
| sympy_str                  | 336 ms                                                       | 289 ms: 1.16x faster                                                         |
| crypto_pyaes               | 81.8 ms                                                      | 70.6 ms: 1.16x faster                                                        |
| fannkuch                   | 457 ms                                                       | 400 ms: 1.14x faster                                                         |
| raytrace                   | 308 ms                                                       | 271 ms: 1.13x faster                                                         |
| nbody                      | 95.8 ms                                                      | 84.7 ms: 1.13x faster                                                        |
| sympy_expand               | 550 ms                                                       | 492 ms: 1.12x faster                                                         |
| deltablue                  | 4.03 ms                                                      | 3.60 ms: 1.12x faster                                                        |
| sympy_integrate            | 25.6 ms                                                      | 23.0 ms: 1.12x faster                                                        |
| nqueens                    | 99.2 ms                                                      | 89.6 ms: 1.11x faster                                                        |
| async_tree_io              | 1.19 sec                                                     | 1.08 sec: 1.10x faster                                                       |
| sqlglot_parse              | 1.55 ms                                                      | 1.41 ms: 1.10x faster                                                        |
| async_tree_none_tg         | 482 ms                                                       | 439 ms: 1.10x faster                                                         |
| regex_compile              | 157 ms                                                       | 143 ms: 1.10x faster                                                         |
| async_tree_cpu_io_mixed    | 762 ms                                                       | 695 ms: 1.10x faster                                                         |
| logging_simple             | 7.21 us                                                      | 6.61 us: 1.09x faster                                                        |
| mako                       | 11.0 ms                                                      | 10.1 ms: 1.09x faster                                                        |
| json                       | 5.59 ms                                                      | 5.14 ms: 1.09x faster                                                        |
| xml_etree_parse            | 159 ms                                                       | 146 ms: 1.09x faster                                                         |
| hexiom                     | 6.97 ms                                                      | 6.45 ms: 1.08x faster                                                        |
| async_tree_memoization_tg  | 605 ms                                                       | 561 ms: 1.08x faster                                                         |
| mdp                        | 2.72 sec                                                     | 2.53 sec: 1.07x faster                                                       |
| logging_silent             | 102 ns                                                       | 95.3 ns: 1.07x faster                                                        |
| async_tree_cpu_io_mixed_tg | 760 ms                                                       | 711 ms: 1.07x faster                                                         |
| async_tree_io_tg           | 1.17 sec                                                     | 1.10 sec: 1.07x faster                                                       |
| logging_format             | 7.83 us                                                      | 7.33 us: 1.07x faster                                                        |
| sqlglot_transpile          | 1.94 ms                                                      | 1.82 ms: 1.07x faster                                                        |
| unpickle_pure_python       | 236 us                                                       | 222 us: 1.06x faster                                                         |
| richards_super             | 65.2 ms                                                      | 61.5 ms: 1.06x faster                                                        |
| bench_thread_pool          | 1.02 ms                                                      | 968 us: 1.05x faster                                                         |
| tornado_http               | 125 ms                                                       | 119 ms: 1.05x faster                                                         |
| deepcopy                   | 389 us                                                       | 372 us: 1.05x faster                                                         |
| sqlglot_normalize          | 122 ms                                                       | 117 ms: 1.04x faster                                                         |
| scimark_monte_carlo        | 70.6 ms                                                      | 67.7 ms: 1.04x faster                                                        |
| spectral_norm              | 94.0 ms                                                      | 90.6 ms: 1.04x faster                                                        |
| chameleon                  | 7.42 ms                                                      | 7.22 ms: 1.03x faster                                                        |
| deepcopy_reduce            | 3.37 us                                                      | 3.29 us: 1.02x faster                                                        |
| tomli_loads                | 2.27 sec                                                     | 2.23 sec: 1.02x faster                                                       |
| dulwich_log                | 68.3 ms                                                      | 67.2 ms: 1.02x faster                                                        |
| deepcopy_memo              | 37.3 us                                                      | 36.7 us: 1.02x faster                                                        |
| docutils                   | 2.87 sec                                                     | 2.84 sec: 1.01x faster                                                       |
| pycparser                  | 1.28 sec                                                     | 1.27 sec: 1.01x faster                                                       |
| meteor_contest             | 130 ms                                                       | 130 ms: 1.00x faster                                                         |
| sqlglot_optimize           | 59.2 ms                                                      | 59.1 ms: 1.00x faster                                                        |
| regex_effbot               | 3.42 ms                                                      | 3.43 ms: 1.00x slower                                                        |
| pickle_pure_python         | 318 us                                                       | 321 us: 1.01x slower                                                         |
| go                         | 166 ms                                                       | 169 ms: 1.02x slower                                                         |
| pathlib                    | 19.1 ms                                                      | 19.6 ms: 1.02x slower                                                        |
| create_gc_cycles           | 1.59 ms                                                      | 1.63 ms: 1.02x slower                                                        |
| 2to3                       | 286 ms                                                       | 292 ms: 1.02x slower                                                         |
| pprint_safe_repr           | 780 ms                                                       | 801 ms: 1.03x slower                                                         |
| pickle_dict                | 31.8 us                                                      | 32.7 us: 1.03x slower                                                        |
| pickle                     | 9.77 us                                                      | 10.1 us: 1.04x slower                                                        |
| scimark_sparse_mat_mult    | 4.04 ms                                                      | 4.19 ms: 1.04x slower                                                        |
| xml_etree_process          | 56.1 ms                                                      | 58.4 ms: 1.04x slower                                                        |
| bench_mp_pool              | 4.63 ms                                                      | 4.82 ms: 1.04x slower                                                        |
| float                      | 76.0 ms                                                      | 79.3 ms: 1.04x slower                                                        |
| pidigits                   | 251 ms                                                       | 265 ms: 1.05x slower                                                         |
| xml_etree_generate         | 80.5 ms                                                      | 85.5 ms: 1.06x slower                                                        |
| unpickle_list              | 4.47 us                                                      | 4.76 us: 1.06x slower                                                        |
| regex_dna                  | 226 ms                                                       | 244 ms: 1.08x slower                                                         |
| sqlite_synth               | 2.49 us                                                      | 2.69 us: 1.08x slower                                                        |
| regex_v8                   | 23.7 ms                                                      | 25.7 ms: 1.08x slower                                                        |
| unpickle                   | 13.2 us                                                      | 14.4 us: 1.09x slower                                                        |
| scimark_fft                | 281 ms                                                       | 308 ms: 1.09x slower                                                         |
| async_generators           | 322 ms                                                       | 359 ms: 1.12x slower                                                         |
| richards                   | 49.9 ms                                                      | 55.8 ms: 1.12x slower                                                        |
| pickle_list                | 3.89 us                                                      | 4.36 us: 1.12x slower                                                        |
| pyflate                    | 453 ms                                                       | 510 ms: 1.13x slower                                                         |
| unpack_sequence            | 44.9 ns                                                      | 50.8 ns: 1.13x slower                                                        |
| telco                      | 6.91 ms                                                      | 7.94 ms: 1.15x slower                                                        |
| python_startup             | 10.8 ms                                                      | 12.8 ms: 1.19x slower                                                        |
| coverage                   | 66.6 ms                                                      | 82.8 ms: 1.24x slower                                                        |
| scimark_sor                | 109 ms                                                       | 149 ms: 1.36x slower                                                         |
| python_startup_no_site     | 7.78 ms                                                      | 11.3 ms: 1.45x slower                                                        |
| Geometric mean             | (ref)                                                        | 1.07x faster                                                                 |

Benchmark hidden because not significant (3): xml_etree_iterparse, asyncio_websockets, pprint_pformat
Ignored benchmarks (12) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, dask, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift


# HPT report

- Reliability score: 99.91% likely to be faster
- 90% likely to have a speedup of 1.02x
- 95% likely to have a speedup of 1.01x
- 99% likely to have a speedup of 1.01x
