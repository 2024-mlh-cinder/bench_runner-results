
# Results vs. 3.11.0

- fork: python
- ref: main
- machine: linux-x86_64
- commit hash: 853b4b5
- commit date: 2023-11-04
- overall geometric mean: 1.06x faster \*
- HPT reliability: 99.53%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231104-pythonperf2-x86_64-python-main-3.13.0a1+-853b4b5 |
|----------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| 2to3           | 286 ms                                                       | 292 ms: 1.02x slower                                         |
| chameleon      | 7.42 ms                                                      | 7.49 ms: 1.01x slower                                        |
| docutils       | 2.87 sec                                                     | 2.83 sec: 1.01x faster                                       |
| tornado_http   | 125 ms                                                       | 119 ms: 1.05x faster                                         |
| Geometric mean | (ref)                                                        | 1.01x faster                                                 |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231104-pythonperf2-x86_64-python-main-3.13.0a1+-853b4b5 |
|----------------------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| async_tree_none            | 529 ms                                                       | 439 ms: 1.21x faster                                         |
| async_tree_memoization     | 648 ms                                                       | 556 ms: 1.17x faster                                         |
| async_tree_io              | 1.19 sec                                                     | 1.09 sec: 1.10x faster                                       |
| async_tree_cpu_io_mixed    | 762 ms                                                       | 708 ms: 1.08x faster                                         |
| async_tree_none_tg         | 482 ms                                                       | 448 ms: 1.07x faster                                         |
| async_tree_io_tg           | 1.17 sec                                                     | 1.11 sec: 1.06x faster                                       |
| async_tree_cpu_io_mixed_tg | 760 ms                                                       | 723 ms: 1.05x faster                                         |
| async_tree_memoization_tg  | 605 ms                                                       | 576 ms: 1.05x faster                                         |
| Geometric mean             | (ref)                                                        | 1.10x faster                                                 |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231104-pythonperf2-x86_64-python-main-3.13.0a1+-853b4b5 |
|----------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| nbody          | 95.8 ms                                                      | 85.7 ms: 1.12x faster                                        |
| pidigits       | 251 ms                                                       | 265 ms: 1.06x slower                                         |
| float          | 76.0 ms                                                      | 80.6 ms: 1.06x slower                                        |
| Geometric mean | (ref)                                                        | 1.00x slower                                                 |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231104-pythonperf2-x86_64-python-main-3.13.0a1+-853b4b5 |
|----------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| regex_compile  | 157 ms                                                       | 145 ms: 1.08x faster                                         |
| regex_effbot   | 3.42 ms                                                      | 3.49 ms: 1.02x slower                                        |
| regex_dna      | 226 ms                                                       | 237 ms: 1.05x slower                                         |
| regex_v8       | 23.7 ms                                                      | 25.1 ms: 1.06x slower                                        |
| Geometric mean | (ref)                                                        | 1.01x slower                                                 |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231104-pythonperf2-x86_64-python-main-3.13.0a1+-853b4b5 |
|----------------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| json_dumps           | 13.5 ms                                                      | 10.4 ms: 1.29x faster                                        |
| json_loads           | 29.0 us                                                      | 24.1 us: 1.20x faster                                        |
| xml_etree_parse      | 159 ms                                                       | 146 ms: 1.08x faster                                         |
| tomli_loads          | 2.27 sec                                                     | 2.23 sec: 1.02x faster                                       |
| pickle_pure_python   | 318 us                                                       | 320 us: 1.00x slower                                         |
| pickle_dict          | 31.8 us                                                      | 32.4 us: 1.02x slower                                        |
| unpickle_pure_python | 236 us                                                       | 241 us: 1.02x slower                                         |
| pickle               | 9.77 us                                                      | 10.1 us: 1.03x slower                                        |
| xml_etree_process    | 56.1 ms                                                      | 58.6 ms: 1.04x slower                                        |
| unpickle_list        | 4.47 us                                                      | 4.73 us: 1.06x slower                                        |
| xml_etree_generate   | 80.5 ms                                                      | 85.3 ms: 1.06x slower                                        |
| unpickle             | 13.2 us                                                      | 14.3 us: 1.08x slower                                        |
| pickle_list          | 3.89 us                                                      | 4.44 us: 1.14x slower                                        |
| Geometric mean       | (ref)                                                        | 1.01x faster                                                 |

Benchmark hidden because not significant (1): xml_etree_iterparse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231104-pythonperf2-x86_64-python-main-3.13.0a1+-853b4b5 |
|------------------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| python_startup         | 10.8 ms                                                      | 12.8 ms: 1.18x slower                                        |
| python_startup_no_site | 7.78 ms                                                      | 11.3 ms: 1.45x slower                                        |
| Geometric mean         | (ref)                                                        | 1.31x slower                                                 |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231104-pythonperf2-x86_64-python-main-3.13.0a1+-853b4b5 |
|-----------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| mako      | 11.0 ms                                                      | 10.2 ms: 1.08x faster                                        |

All benchmarks:
===============

| Benchmark                  | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231104-pythonperf2-x86_64-python-main-3.13.0a1+-853b4b5 |
|----------------------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| typing_runtime_protocols   | 527 us                                                       | 121 us: 4.35x faster                                         |
| asyncio_tcp                | 752 ms                                                       | 373 ms: 2.01x faster                                         |
| asyncio_tcp_ssl            | 3.09 sec                                                     | 1.58 sec: 1.95x faster                                       |
| generators                 | 56.4 ms                                                      | 36.0 ms: 1.57x faster                                        |
| comprehensions             | 24.8 us                                                      | 16.5 us: 1.51x faster                                        |
| json_dumps                 | 13.5 ms                                                      | 10.4 ms: 1.29x faster                                        |
| coroutines                 | 27.9 ms                                                      | 22.1 ms: 1.26x faster                                        |
| mypy2                      | 449 ms                                                       | 367 ms: 1.22x faster                                         |
| sympy_sum                  | 184 ms                                                       | 151 ms: 1.22x faster                                         |
| async_tree_none            | 529 ms                                                       | 439 ms: 1.21x faster                                         |
| json_loads                 | 29.0 us                                                      | 24.1 us: 1.20x faster                                        |
| fannkuch                   | 457 ms                                                       | 392 ms: 1.17x faster                                         |
| chaos                      | 71.6 ms                                                      | 61.4 ms: 1.17x faster                                        |
| async_tree_memoization     | 648 ms                                                       | 556 ms: 1.17x faster                                         |
| sympy_str                  | 336 ms                                                       | 288 ms: 1.16x faster                                         |
| crypto_pyaes               | 81.8 ms                                                      | 72.0 ms: 1.14x faster                                        |
| sympy_expand               | 550 ms                                                       | 490 ms: 1.12x faster                                         |
| sympy_integrate            | 25.6 ms                                                      | 22.9 ms: 1.12x faster                                        |
| nbody                      | 95.8 ms                                                      | 85.7 ms: 1.12x faster                                        |
| scimark_lu                 | 115 ms                                                       | 103 ms: 1.12x faster                                         |
| raytrace                   | 308 ms                                                       | 278 ms: 1.11x faster                                         |
| nqueens                    | 99.2 ms                                                      | 89.8 ms: 1.10x faster                                        |
| sqlglot_parse              | 1.55 ms                                                      | 1.41 ms: 1.10x faster                                        |
| async_tree_io              | 1.19 sec                                                     | 1.09 sec: 1.10x faster                                       |
| hexiom                     | 6.97 ms                                                      | 6.38 ms: 1.09x faster                                        |
| richards_super             | 65.2 ms                                                      | 59.7 ms: 1.09x faster                                        |
| json                       | 5.59 ms                                                      | 5.12 ms: 1.09x faster                                        |
| deltablue                  | 4.03 ms                                                      | 3.69 ms: 1.09x faster                                        |
| gc_traversal               | 4.06 ms                                                      | 3.73 ms: 1.09x faster                                        |
| regex_compile              | 157 ms                                                       | 145 ms: 1.08x faster                                         |
| xml_etree_parse            | 159 ms                                                       | 146 ms: 1.08x faster                                         |
| mako                       | 11.0 ms                                                      | 10.2 ms: 1.08x faster                                        |
| async_tree_cpu_io_mixed    | 762 ms                                                       | 708 ms: 1.08x faster                                         |
| async_tree_none_tg         | 482 ms                                                       | 448 ms: 1.07x faster                                         |
| sqlglot_normalize          | 122 ms                                                       | 114 ms: 1.07x faster                                         |
| sqlglot_transpile          | 1.94 ms                                                      | 1.81 ms: 1.07x faster                                        |
| mdp                        | 2.72 sec                                                     | 2.55 sec: 1.07x faster                                       |
| bench_thread_pool          | 1.02 ms                                                      | 957 us: 1.07x faster                                         |
| logging_simple             | 7.21 us                                                      | 6.80 us: 1.06x faster                                        |
| async_tree_io_tg           | 1.17 sec                                                     | 1.11 sec: 1.06x faster                                       |
| logging_silent             | 102 ns                                                       | 96.5 ns: 1.06x faster                                        |
| deepcopy                   | 389 us                                                       | 369 us: 1.06x faster                                         |
| async_tree_cpu_io_mixed_tg | 760 ms                                                       | 723 ms: 1.05x faster                                         |
| async_tree_memoization_tg  | 605 ms                                                       | 576 ms: 1.05x faster                                         |
| logging_format             | 7.83 us                                                      | 7.47 us: 1.05x faster                                        |
| tornado_http               | 125 ms                                                       | 119 ms: 1.05x faster                                         |
| spectral_norm              | 94.0 ms                                                      | 90.5 ms: 1.04x faster                                        |
| scimark_monte_carlo        | 70.6 ms                                                      | 68.4 ms: 1.03x faster                                        |
| deepcopy_reduce            | 3.37 us                                                      | 3.28 us: 1.03x faster                                        |
| sqlglot_optimize           | 59.2 ms                                                      | 58.0 ms: 1.02x faster                                        |
| tomli_loads                | 2.27 sec                                                     | 2.23 sec: 1.02x faster                                       |
| docutils                   | 2.87 sec                                                     | 2.83 sec: 1.01x faster                                       |
| meteor_contest             | 130 ms                                                       | 129 ms: 1.01x faster                                         |
| pickle_pure_python         | 318 us                                                       | 320 us: 1.00x slower                                         |
| chameleon                  | 7.42 ms                                                      | 7.49 ms: 1.01x slower                                        |
| deepcopy_memo              | 37.3 us                                                      | 38.0 us: 1.02x slower                                        |
| pprint_pformat             | 1.63 sec                                                     | 1.66 sec: 1.02x slower                                       |
| pickle_dict                | 31.8 us                                                      | 32.4 us: 1.02x slower                                        |
| scimark_sparse_mat_mult    | 4.04 ms                                                      | 4.12 ms: 1.02x slower                                        |
| regex_effbot               | 3.42 ms                                                      | 3.49 ms: 1.02x slower                                        |
| 2to3                       | 286 ms                                                       | 292 ms: 1.02x slower                                         |
| unpickle_pure_python       | 236 us                                                       | 241 us: 1.02x slower                                         |
| pycparser                  | 1.28 sec                                                     | 1.32 sec: 1.03x slower                                       |
| pathlib                    | 19.1 ms                                                      | 19.7 ms: 1.03x slower                                        |
| pickle                     | 9.77 us                                                      | 10.1 us: 1.03x slower                                        |
| pprint_safe_repr           | 780 ms                                                       | 810 ms: 1.04x slower                                         |
| go                         | 166 ms                                                       | 173 ms: 1.04x slower                                         |
| xml_etree_process          | 56.1 ms                                                      | 58.6 ms: 1.04x slower                                        |
| regex_dna                  | 226 ms                                                       | 237 ms: 1.05x slower                                         |
| richards                   | 49.9 ms                                                      | 52.7 ms: 1.06x slower                                        |
| pidigits                   | 251 ms                                                       | 265 ms: 1.06x slower                                         |
| unpickle_list              | 4.47 us                                                      | 4.73 us: 1.06x slower                                        |
| float                      | 76.0 ms                                                      | 80.6 ms: 1.06x slower                                        |
| xml_etree_generate         | 80.5 ms                                                      | 85.3 ms: 1.06x slower                                        |
| regex_v8                   | 23.7 ms                                                      | 25.1 ms: 1.06x slower                                        |
| sqlite_synth               | 2.49 us                                                      | 2.66 us: 1.07x slower                                        |
| scimark_fft                | 281 ms                                                       | 302 ms: 1.07x slower                                         |
| unpickle                   | 13.2 us                                                      | 14.3 us: 1.08x slower                                        |
| unpack_sequence            | 44.9 ns                                                      | 49.9 ns: 1.11x slower                                        |
| async_generators           | 322 ms                                                       | 361 ms: 1.12x slower                                         |
| pickle_list                | 3.89 us                                                      | 4.44 us: 1.14x slower                                        |
| telco                      | 6.91 ms                                                      | 7.97 ms: 1.15x slower                                        |
| pyflate                    | 453 ms                                                       | 529 ms: 1.17x slower                                         |
| coverage                   | 66.6 ms                                                      | 78.3 ms: 1.17x slower                                        |
| python_startup             | 10.8 ms                                                      | 12.8 ms: 1.18x slower                                        |
| bench_mp_pool              | 4.63 ms                                                      | 5.61 ms: 1.21x slower                                        |
| scimark_sor                | 109 ms                                                       | 146 ms: 1.34x slower                                         |
| python_startup_no_site     | 7.78 ms                                                      | 11.3 ms: 1.45x slower                                        |
| Geometric mean             | (ref)                                                        | 1.06x faster                                                 |

Benchmark hidden because not significant (4): create_gc_cycles, asyncio_websockets, xml_etree_iterparse, dulwich_log
Ignored benchmarks (12) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, dask, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift


# HPT report

- Reliability score: 99.53% likely to be faster
- 90% likely to have a speedup of 1.02x
- 95% likely to have a speedup of 1.01x
- 99% likely to have a speedup of 1.00x
