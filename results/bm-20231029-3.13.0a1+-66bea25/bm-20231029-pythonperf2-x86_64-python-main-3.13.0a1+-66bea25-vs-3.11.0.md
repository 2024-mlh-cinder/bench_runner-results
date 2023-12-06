
# Results vs. 3.11.0

- fork: python
- ref: main
- machine: linux-x86_64
- commit hash: 66bea25
- commit date: 2023-10-29
- overall geometric mean: 1.05x faster
- HPT reliability: 96.55%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231029-pythonperf2-x86_64-python-main-3.13.0a1+-66bea25 |
|----------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| 2to3           | 286 ms                                                       | 297 ms: 1.04x slower                                         |
| chameleon      | 7.42 ms                                                      | 7.79 ms: 1.05x slower                                        |
| docutils       | 2.87 sec                                                     | 2.88 sec: 1.00x slower                                       |
| tornado_http   | 125 ms                                                       | 122 ms: 1.02x faster                                         |
| Geometric mean | (ref)                                                        | 1.02x slower                                                 |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231029-pythonperf2-x86_64-python-main-3.13.0a1+-66bea25 |
|----------------------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| async_tree_none            | 529 ms                                                       | 440 ms: 1.20x faster                                         |
| async_tree_memoization     | 648 ms                                                       | 556 ms: 1.16x faster                                         |
| async_tree_io              | 1.19 sec                                                     | 1.10 sec: 1.09x faster                                       |
| async_tree_cpu_io_mixed    | 762 ms                                                       | 710 ms: 1.07x faster                                         |
| async_tree_none_tg         | 482 ms                                                       | 449 ms: 1.07x faster                                         |
| async_tree_memoization_tg  | 605 ms                                                       | 573 ms: 1.06x faster                                         |
| async_tree_io_tg           | 1.17 sec                                                     | 1.11 sec: 1.05x faster                                       |
| async_tree_cpu_io_mixed_tg | 760 ms                                                       | 727 ms: 1.05x faster                                         |
| Geometric mean             | (ref)                                                        | 1.09x faster                                                 |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231029-pythonperf2-x86_64-python-main-3.13.0a1+-66bea25 |
|----------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| nbody          | 95.8 ms                                                      | 88.1 ms: 1.09x faster                                        |
| float          | 76.0 ms                                                      | 78.8 ms: 1.04x slower                                        |
| pidigits       | 251 ms                                                       | 264 ms: 1.05x slower                                         |
| Geometric mean | (ref)                                                        | 1.00x slower                                                 |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231029-pythonperf2-x86_64-python-main-3.13.0a1+-66bea25 |
|----------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| regex_compile  | 157 ms                                                       | 149 ms: 1.06x faster                                         |
| regex_v8       | 23.7 ms                                                      | 24.4 ms: 1.03x slower                                        |
| regex_effbot   | 3.42 ms                                                      | 3.53 ms: 1.03x slower                                        |
| regex_dna      | 226 ms                                                       | 238 ms: 1.05x slower                                         |
| Geometric mean | (ref)                                                        | 1.01x slower                                                 |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231029-pythonperf2-x86_64-python-main-3.13.0a1+-66bea25 |
|----------------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| json_dumps           | 13.5 ms                                                      | 10.5 ms: 1.28x faster                                        |
| json_loads           | 29.0 us                                                      | 24.6 us: 1.18x faster                                        |
| unpickle_pure_python | 236 us                                                       | 221 us: 1.07x faster                                         |
| xml_etree_parse      | 159 ms                                                       | 150 ms: 1.06x faster                                         |
| pickle_dict          | 31.8 us                                                      | 31.4 us: 1.01x faster                                        |
| tomli_loads          | 2.27 sec                                                     | 2.26 sec: 1.01x faster                                       |
| pickle_pure_python   | 318 us                                                       | 319 us: 1.00x slower                                         |
| unpickle_list        | 4.47 us                                                      | 4.54 us: 1.02x slower                                        |
| xml_etree_iterparse  | 106 ms                                                       | 109 ms: 1.03x slower                                         |
| pickle               | 9.77 us                                                      | 10.3 us: 1.05x slower                                        |
| xml_etree_generate   | 80.5 ms                                                      | 84.8 ms: 1.05x slower                                        |
| xml_etree_process    | 56.1 ms                                                      | 59.3 ms: 1.06x slower                                        |
| unpickle             | 13.2 us                                                      | 14.8 us: 1.12x slower                                        |
| pickle_list          | 3.89 us                                                      | 4.38 us: 1.12x slower                                        |
| Geometric mean       | (ref)                                                        | 1.01x faster                                                 |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231029-pythonperf2-x86_64-python-main-3.13.0a1+-66bea25 |
|------------------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| python_startup         | 10.8 ms                                                      | 12.9 ms: 1.19x slower                                        |
| python_startup_no_site | 7.78 ms                                                      | 11.3 ms: 1.46x slower                                        |
| Geometric mean         | (ref)                                                        | 1.32x slower                                                 |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231029-pythonperf2-x86_64-python-main-3.13.0a1+-66bea25 |
|-----------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| mako      | 11.0 ms                                                      | 10.3 ms: 1.07x faster                                        |

All benchmarks:
===============

| Benchmark                  | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231029-pythonperf2-x86_64-python-main-3.13.0a1+-66bea25 |
|----------------------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| typing_runtime_protocols   | 527 us                                                       | 153 us: 3.44x faster                                         |
| asyncio_tcp                | 752 ms                                                       | 369 ms: 2.04x faster                                         |
| asyncio_tcp_ssl            | 3.09 sec                                                     | 1.58 sec: 1.95x faster                                       |
| generators                 | 56.4 ms                                                      | 36.2 ms: 1.56x faster                                        |
| comprehensions             | 24.8 us                                                      | 16.8 us: 1.48x faster                                        |
| json_dumps                 | 13.5 ms                                                      | 10.5 ms: 1.28x faster                                        |
| sympy_sum                  | 184 ms                                                       | 152 ms: 1.21x faster                                         |
| mypy2                      | 449 ms                                                       | 371 ms: 1.21x faster                                         |
| coroutines                 | 27.9 ms                                                      | 23.1 ms: 1.21x faster                                        |
| async_tree_none            | 529 ms                                                       | 440 ms: 1.20x faster                                         |
| fannkuch                   | 457 ms                                                       | 385 ms: 1.19x faster                                         |
| json_loads                 | 29.0 us                                                      | 24.6 us: 1.18x faster                                        |
| async_tree_memoization     | 648 ms                                                       | 556 ms: 1.16x faster                                         |
| chaos                      | 71.6 ms                                                      | 62.3 ms: 1.15x faster                                        |
| sympy_str                  | 336 ms                                                       | 293 ms: 1.15x faster                                         |
| scimark_lu                 | 115 ms                                                       | 101 ms: 1.14x faster                                         |
| crypto_pyaes               | 81.8 ms                                                      | 71.8 ms: 1.14x faster                                        |
| raytrace                   | 308 ms                                                       | 274 ms: 1.12x faster                                         |
| nqueens                    | 99.2 ms                                                      | 89.1 ms: 1.11x faster                                        |
| sympy_expand               | 550 ms                                                       | 496 ms: 1.11x faster                                         |
| sympy_integrate            | 25.6 ms                                                      | 23.6 ms: 1.09x faster                                        |
| nbody                      | 95.8 ms                                                      | 88.1 ms: 1.09x faster                                        |
| deltablue                  | 4.03 ms                                                      | 3.71 ms: 1.09x faster                                        |
| async_tree_io              | 1.19 sec                                                     | 1.10 sec: 1.09x faster                                       |
| json                       | 5.59 ms                                                      | 5.16 ms: 1.08x faster                                        |
| sqlglot_parse              | 1.55 ms                                                      | 1.43 ms: 1.08x faster                                        |
| async_tree_cpu_io_mixed    | 762 ms                                                       | 710 ms: 1.07x faster                                         |
| async_tree_none_tg         | 482 ms                                                       | 449 ms: 1.07x faster                                         |
| mdp                        | 2.72 sec                                                     | 2.54 sec: 1.07x faster                                       |
| mako                       | 11.0 ms                                                      | 10.3 ms: 1.07x faster                                        |
| unpickle_pure_python       | 236 us                                                       | 221 us: 1.07x faster                                         |
| richards_super             | 65.2 ms                                                      | 61.1 ms: 1.07x faster                                        |
| hexiom                     | 6.97 ms                                                      | 6.54 ms: 1.07x faster                                        |
| xml_etree_parse            | 159 ms                                                       | 150 ms: 1.06x faster                                         |
| regex_compile              | 157 ms                                                       | 149 ms: 1.06x faster                                         |
| async_tree_memoization_tg  | 605 ms                                                       | 573 ms: 1.06x faster                                         |
| async_tree_io_tg           | 1.17 sec                                                     | 1.11 sec: 1.05x faster                                       |
| sqlglot_transpile          | 1.94 ms                                                      | 1.85 ms: 1.05x faster                                        |
| bench_thread_pool          | 1.02 ms                                                      | 973 us: 1.05x faster                                         |
| async_tree_cpu_io_mixed_tg | 760 ms                                                       | 727 ms: 1.05x faster                                         |
| sqlglot_normalize          | 122 ms                                                       | 117 ms: 1.04x faster                                         |
| logging_format             | 7.83 us                                                      | 7.53 us: 1.04x faster                                        |
| gc_traversal               | 4.06 ms                                                      | 3.92 ms: 1.04x faster                                        |
| logging_simple             | 7.21 us                                                      | 6.96 us: 1.04x faster                                        |
| logging_silent             | 102 ns                                                       | 99.4 ns: 1.03x faster                                        |
| tornado_http               | 125 ms                                                       | 122 ms: 1.02x faster                                         |
| deepcopy                   | 389 us                                                       | 382 us: 1.02x faster                                         |
| scimark_monte_carlo        | 70.6 ms                                                      | 69.4 ms: 1.02x faster                                        |
| pickle_dict                | 31.8 us                                                      | 31.4 us: 1.01x faster                                        |
| tomli_loads                | 2.27 sec                                                     | 2.26 sec: 1.01x faster                                       |
| docutils                   | 2.87 sec                                                     | 2.88 sec: 1.00x slower                                       |
| pickle_pure_python         | 318 us                                                       | 319 us: 1.00x slower                                         |
| meteor_contest             | 130 ms                                                       | 131 ms: 1.00x slower                                         |
| pycparser                  | 1.28 sec                                                     | 1.30 sec: 1.01x slower                                       |
| dulwich_log                | 68.3 ms                                                      | 69.0 ms: 1.01x slower                                        |
| unpickle_list              | 4.47 us                                                      | 4.54 us: 1.02x slower                                        |
| deepcopy_memo              | 37.3 us                                                      | 38.1 us: 1.02x slower                                        |
| xml_etree_iterparse        | 106 ms                                                       | 109 ms: 1.03x slower                                         |
| pathlib                    | 19.1 ms                                                      | 19.7 ms: 1.03x slower                                        |
| create_gc_cycles           | 1.59 ms                                                      | 1.64 ms: 1.03x slower                                        |
| regex_v8                   | 23.7 ms                                                      | 24.4 ms: 1.03x slower                                        |
| unpack_sequence            | 44.9 ns                                                      | 46.3 ns: 1.03x slower                                        |
| go                         | 166 ms                                                       | 171 ms: 1.03x slower                                         |
| regex_effbot               | 3.42 ms                                                      | 3.53 ms: 1.03x slower                                        |
| float                      | 76.0 ms                                                      | 78.8 ms: 1.04x slower                                        |
| 2to3                       | 286 ms                                                       | 297 ms: 1.04x slower                                         |
| pprint_pformat             | 1.63 sec                                                     | 1.70 sec: 1.04x slower                                       |
| scimark_sparse_mat_mult    | 4.04 ms                                                      | 4.21 ms: 1.04x slower                                        |
| chameleon                  | 7.42 ms                                                      | 7.79 ms: 1.05x slower                                        |
| pickle                     | 9.77 us                                                      | 10.3 us: 1.05x slower                                        |
| regex_dna                  | 226 ms                                                       | 238 ms: 1.05x slower                                         |
| pidigits                   | 251 ms                                                       | 264 ms: 1.05x slower                                         |
| xml_etree_generate         | 80.5 ms                                                      | 84.8 ms: 1.05x slower                                        |
| xml_etree_process          | 56.1 ms                                                      | 59.3 ms: 1.06x slower                                        |
| pprint_safe_repr           | 780 ms                                                       | 836 ms: 1.07x slower                                         |
| sqlite_synth               | 2.49 us                                                      | 2.71 us: 1.09x slower                                        |
| scimark_fft                | 281 ms                                                       | 310 ms: 1.10x slower                                         |
| richards                   | 49.9 ms                                                      | 55.9 ms: 1.12x slower                                        |
| unpickle                   | 13.2 us                                                      | 14.8 us: 1.12x slower                                        |
| pickle_list                | 3.89 us                                                      | 4.38 us: 1.12x slower                                        |
| pyflate                    | 453 ms                                                       | 516 ms: 1.14x slower                                         |
| telco                      | 6.91 ms                                                      | 8.18 ms: 1.18x slower                                        |
| python_startup             | 10.8 ms                                                      | 12.9 ms: 1.19x slower                                        |
| coverage                   | 66.6 ms                                                      | 79.9 ms: 1.20x slower                                        |
| async_generators           | 322 ms                                                       | 394 ms: 1.22x slower                                         |
| scimark_sor                | 109 ms                                                       | 150 ms: 1.37x slower                                         |
| python_startup_no_site     | 7.78 ms                                                      | 11.3 ms: 1.46x slower                                        |
| Geometric mean             | (ref)                                                        | 1.05x faster                                                 |

Benchmark hidden because not significant (5): bench_mp_pool, spectral_norm, asyncio_websockets, deepcopy_reduce, sqlglot_optimize
Ignored benchmarks (12) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, dask, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift


# HPT report

- Reliability score: 96.55% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
