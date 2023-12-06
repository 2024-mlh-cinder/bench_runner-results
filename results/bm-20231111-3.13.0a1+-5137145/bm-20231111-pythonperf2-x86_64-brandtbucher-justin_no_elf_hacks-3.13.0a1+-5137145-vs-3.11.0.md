
# Results vs. 3.11.0

- fork: brandtbucher
- ref: justin_no_elf_hacks
- machine: linux-x86_64
- commit hash: 5137145
- commit date: 2023-11-11
- overall geometric mean: 1.04x faster \*
- HPT reliability: 84.62%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231111-pythonperf2-x86_64-brandtbucher-justin_no_elf_hacks-3.13.0a1+-5137145 |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------------:|
| 2to3           | 286 ms                                                       | 299 ms: 1.05x slower                                                              |
| chameleon      | 7.42 ms                                                      | 7.64 ms: 1.03x slower                                                             |
| docutils       | 2.87 sec                                                     | 2.88 sec: 1.01x slower                                                            |
| tornado_http   | 125 ms                                                       | 121 ms: 1.04x faster                                                              |
| Geometric mean | (ref)                                                        | 1.01x slower                                                                      |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231111-pythonperf2-x86_64-brandtbucher-justin_no_elf_hacks-3.13.0a1+-5137145 |
|----------------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------------:|
| async_tree_none            | 529 ms                                                       | 438 ms: 1.21x faster                                                              |
| async_tree_memoization     | 648 ms                                                       | 549 ms: 1.18x faster                                                              |
| async_tree_io              | 1.19 sec                                                     | 1.08 sec: 1.10x faster                                                            |
| async_tree_cpu_io_mixed    | 762 ms                                                       | 701 ms: 1.09x faster                                                              |
| async_tree_none_tg         | 482 ms                                                       | 445 ms: 1.08x faster                                                              |
| async_tree_io_tg           | 1.17 sec                                                     | 1.10 sec: 1.07x faster                                                            |
| async_tree_cpu_io_mixed_tg | 760 ms                                                       | 719 ms: 1.06x faster                                                              |
| async_tree_memoization_tg  | 605 ms                                                       | 576 ms: 1.05x faster                                                              |
| Geometric mean             | (ref)                                                        | 1.10x faster                                                                      |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231111-pythonperf2-x86_64-brandtbucher-justin_no_elf_hacks-3.13.0a1+-5137145 |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------------:|
| nbody          | 95.8 ms                                                      | 96.7 ms: 1.01x slower                                                             |
| pidigits       | 251 ms                                                       | 265 ms: 1.06x slower                                                              |
| float          | 76.0 ms                                                      | 81.3 ms: 1.07x slower                                                             |
| Geometric mean | (ref)                                                        | 1.05x slower                                                                      |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231111-pythonperf2-x86_64-brandtbucher-justin_no_elf_hacks-3.13.0a1+-5137145 |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------------:|
| regex_compile  | 157 ms                                                       | 150 ms: 1.05x faster                                                              |
| regex_effbot   | 3.42 ms                                                      | 3.46 ms: 1.01x slower                                                             |
| regex_dna      | 226 ms                                                       | 239 ms: 1.06x slower                                                              |
| regex_v8       | 23.7 ms                                                      | 25.0 ms: 1.06x slower                                                             |
| Geometric mean | (ref)                                                        | 1.02x slower                                                                      |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231111-pythonperf2-x86_64-brandtbucher-justin_no_elf_hacks-3.13.0a1+-5137145 |
|----------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------------:|
| json_dumps           | 13.5 ms                                                      | 10.4 ms: 1.30x faster                                                             |
| json_loads           | 29.0 us                                                      | 24.4 us: 1.19x faster                                                             |
| xml_etree_parse      | 159 ms                                                       | 146 ms: 1.09x faster                                                              |
| xml_etree_iterparse  | 106 ms                                                       | 103 ms: 1.02x faster                                                              |
| pickle_pure_python   | 318 us                                                       | 315 us: 1.01x faster                                                              |
| xml_etree_process    | 56.1 ms                                                      | 58.0 ms: 1.03x slower                                                             |
| pickle               | 9.77 us                                                      | 10.2 us: 1.05x slower                                                             |
| unpickle_pure_python | 236 us                                                       | 248 us: 1.05x slower                                                              |
| tomli_loads          | 2.27 sec                                                     | 2.40 sec: 1.06x slower                                                            |
| xml_etree_generate   | 80.5 ms                                                      | 85.7 ms: 1.06x slower                                                             |
| pickle_dict          | 31.8 us                                                      | 33.8 us: 1.07x slower                                                             |
| unpickle_list        | 4.47 us                                                      | 4.80 us: 1.07x slower                                                             |
| unpickle             | 13.2 us                                                      | 14.2 us: 1.08x slower                                                             |
| pickle_list          | 3.89 us                                                      | 4.44 us: 1.14x slower                                                             |
| Geometric mean       | (ref)                                                        | 1.00x slower                                                                      |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231111-pythonperf2-x86_64-brandtbucher-justin_no_elf_hacks-3.13.0a1+-5137145 |
|------------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------------:|
| python_startup         | 10.8 ms                                                      | 12.9 ms: 1.19x slower                                                             |
| python_startup_no_site | 7.78 ms                                                      | 11.4 ms: 1.46x slower                                                             |
| Geometric mean         | (ref)                                                        | 1.32x slower                                                                      |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231111-pythonperf2-x86_64-brandtbucher-justin_no_elf_hacks-3.13.0a1+-5137145 |
|-----------|:------------------------------------------------------------:|:---------------------------------------------------------------------------------:|
| mako      | 11.0 ms                                                      | 11.2 ms: 1.01x slower                                                             |

All benchmarks:
===============

| Benchmark                  | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231111-pythonperf2-x86_64-brandtbucher-justin_no_elf_hacks-3.13.0a1+-5137145 |
|----------------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------------:|
| typing_runtime_protocols   | 527 us                                                       | 129 us: 4.10x faster                                                              |
| asyncio_tcp                | 752 ms                                                       | 366 ms: 2.05x faster                                                              |
| asyncio_tcp_ssl            | 3.09 sec                                                     | 1.58 sec: 1.95x faster                                                            |
| generators                 | 56.4 ms                                                      | 35.7 ms: 1.58x faster                                                             |
| json_dumps                 | 13.5 ms                                                      | 10.4 ms: 1.30x faster                                                             |
| coroutines                 | 27.9 ms                                                      | 22.7 ms: 1.23x faster                                                             |
| async_tree_none            | 529 ms                                                       | 438 ms: 1.21x faster                                                              |
| mypy2                      | 449 ms                                                       | 374 ms: 1.20x faster                                                              |
| sympy_sum                  | 184 ms                                                       | 155 ms: 1.19x faster                                                              |
| json_loads                 | 29.0 us                                                      | 24.4 us: 1.19x faster                                                             |
| async_tree_memoization     | 648 ms                                                       | 549 ms: 1.18x faster                                                              |
| comprehensions             | 24.8 us                                                      | 21.5 us: 1.15x faster                                                             |
| sympy_str                  | 336 ms                                                       | 294 ms: 1.14x faster                                                              |
| richards_super             | 65.2 ms                                                      | 58.3 ms: 1.12x faster                                                             |
| gc_traversal               | 4.06 ms                                                      | 3.64 ms: 1.12x faster                                                             |
| sympy_expand               | 550 ms                                                       | 494 ms: 1.11x faster                                                              |
| json                       | 5.59 ms                                                      | 5.05 ms: 1.11x faster                                                             |
| sqlglot_parse              | 1.55 ms                                                      | 1.41 ms: 1.10x faster                                                             |
| async_tree_io              | 1.19 sec                                                     | 1.08 sec: 1.10x faster                                                            |
| scimark_lu                 | 115 ms                                                       | 105 ms: 1.10x faster                                                              |
| xml_etree_parse            | 159 ms                                                       | 146 ms: 1.09x faster                                                              |
| async_tree_cpu_io_mixed    | 762 ms                                                       | 701 ms: 1.09x faster                                                              |
| deepcopy                   | 389 us                                                       | 359 us: 1.09x faster                                                              |
| async_tree_none_tg         | 482 ms                                                       | 445 ms: 1.08x faster                                                              |
| fannkuch                   | 457 ms                                                       | 423 ms: 1.08x faster                                                              |
| logging_simple             | 7.21 us                                                      | 6.68 us: 1.08x faster                                                             |
| raytrace                   | 308 ms                                                       | 285 ms: 1.08x faster                                                              |
| chaos                      | 71.6 ms                                                      | 67.0 ms: 1.07x faster                                                             |
| async_tree_io_tg           | 1.17 sec                                                     | 1.10 sec: 1.07x faster                                                            |
| sympy_integrate            | 25.6 ms                                                      | 24.0 ms: 1.07x faster                                                             |
| sqlglot_transpile          | 1.94 ms                                                      | 1.82 ms: 1.06x faster                                                             |
| deltablue                  | 4.03 ms                                                      | 3.80 ms: 1.06x faster                                                             |
| async_tree_cpu_io_mixed_tg | 760 ms                                                       | 719 ms: 1.06x faster                                                              |
| create_gc_cycles           | 1.59 ms                                                      | 1.51 ms: 1.05x faster                                                             |
| logging_silent             | 102 ns                                                       | 96.8 ns: 1.05x faster                                                             |
| logging_format             | 7.83 us                                                      | 7.44 us: 1.05x faster                                                             |
| async_tree_memoization_tg  | 605 ms                                                       | 576 ms: 1.05x faster                                                              |
| crypto_pyaes               | 81.8 ms                                                      | 78.0 ms: 1.05x faster                                                             |
| sqlglot_normalize          | 122 ms                                                       | 116 ms: 1.05x faster                                                              |
| regex_compile              | 157 ms                                                       | 150 ms: 1.05x faster                                                              |
| bench_thread_pool          | 1.02 ms                                                      | 976 us: 1.05x faster                                                              |
| deepcopy_reduce            | 3.37 us                                                      | 3.23 us: 1.04x faster                                                             |
| mdp                        | 2.72 sec                                                     | 2.62 sec: 1.04x faster                                                            |
| tornado_http               | 125 ms                                                       | 121 ms: 1.04x faster                                                              |
| spectral_norm              | 94.0 ms                                                      | 91.1 ms: 1.03x faster                                                             |
| xml_etree_iterparse        | 106 ms                                                       | 103 ms: 1.02x faster                                                              |
| pickle_pure_python         | 318 us                                                       | 315 us: 1.01x faster                                                              |
| dulwich_log                | 68.3 ms                                                      | 67.8 ms: 1.01x faster                                                             |
| deepcopy_memo              | 37.3 us                                                      | 37.0 us: 1.01x faster                                                             |
| sqlglot_optimize           | 59.2 ms                                                      | 59.0 ms: 1.00x faster                                                             |
| docutils                   | 2.87 sec                                                     | 2.88 sec: 1.01x slower                                                            |
| nbody                      | 95.8 ms                                                      | 96.7 ms: 1.01x slower                                                             |
| regex_effbot               | 3.42 ms                                                      | 3.46 ms: 1.01x slower                                                             |
| mako                       | 11.0 ms                                                      | 11.2 ms: 1.01x slower                                                             |
| unpack_sequence            | 44.9 ns                                                      | 45.5 ns: 1.01x slower                                                             |
| meteor_contest             | 130 ms                                                       | 133 ms: 1.02x slower                                                              |
| chameleon                  | 7.42 ms                                                      | 7.64 ms: 1.03x slower                                                             |
| pathlib                    | 19.1 ms                                                      | 19.7 ms: 1.03x slower                                                             |
| xml_etree_process          | 56.1 ms                                                      | 58.0 ms: 1.03x slower                                                             |
| pycparser                  | 1.28 sec                                                     | 1.34 sec: 1.04x slower                                                            |
| nqueens                    | 99.2 ms                                                      | 103 ms: 1.04x slower                                                              |
| richards                   | 49.9 ms                                                      | 52.1 ms: 1.05x slower                                                             |
| 2to3                       | 286 ms                                                       | 299 ms: 1.05x slower                                                              |
| scimark_monte_carlo        | 70.6 ms                                                      | 73.9 ms: 1.05x slower                                                             |
| pickle                     | 9.77 us                                                      | 10.2 us: 1.05x slower                                                             |
| pprint_pformat             | 1.63 sec                                                     | 1.71 sec: 1.05x slower                                                            |
| unpickle_pure_python       | 236 us                                                       | 248 us: 1.05x slower                                                              |
| tomli_loads                | 2.27 sec                                                     | 2.40 sec: 1.06x slower                                                            |
| pidigits                   | 251 ms                                                       | 265 ms: 1.06x slower                                                              |
| regex_dna                  | 226 ms                                                       | 239 ms: 1.06x slower                                                              |
| regex_v8                   | 23.7 ms                                                      | 25.0 ms: 1.06x slower                                                             |
| go                         | 166 ms                                                       | 176 ms: 1.06x slower                                                              |
| xml_etree_generate         | 80.5 ms                                                      | 85.7 ms: 1.06x slower                                                             |
| pickle_dict                | 31.8 us                                                      | 33.8 us: 1.07x slower                                                             |
| float                      | 76.0 ms                                                      | 81.3 ms: 1.07x slower                                                             |
| pprint_safe_repr           | 780 ms                                                       | 836 ms: 1.07x slower                                                              |
| unpickle_list              | 4.47 us                                                      | 4.80 us: 1.07x slower                                                             |
| sqlite_synth               | 2.49 us                                                      | 2.68 us: 1.08x slower                                                             |
| unpickle                   | 13.2 us                                                      | 14.2 us: 1.08x slower                                                             |
| scimark_sparse_mat_mult    | 4.04 ms                                                      | 4.51 ms: 1.12x slower                                                             |
| pyflate                    | 453 ms                                                       | 509 ms: 1.12x slower                                                              |
| pickle_list                | 3.89 us                                                      | 4.44 us: 1.14x slower                                                             |
| hexiom                     | 6.97 ms                                                      | 8.19 ms: 1.17x slower                                                             |
| async_generators           | 322 ms                                                       | 382 ms: 1.19x slower                                                              |
| python_startup             | 10.8 ms                                                      | 12.9 ms: 1.19x slower                                                             |
| bench_mp_pool              | 4.63 ms                                                      | 5.60 ms: 1.21x slower                                                             |
| telco                      | 6.91 ms                                                      | 8.42 ms: 1.22x slower                                                             |
| scimark_fft                | 281 ms                                                       | 345 ms: 1.23x slower                                                              |
| coverage                   | 66.6 ms                                                      | 83.1 ms: 1.25x slower                                                             |
| scimark_sor                | 109 ms                                                       | 149 ms: 1.36x slower                                                              |
| python_startup_no_site     | 7.78 ms                                                      | 11.4 ms: 1.46x slower                                                             |
| Geometric mean             | (ref)                                                        | 1.04x faster                                                                      |

Benchmark hidden because not significant (1): asyncio_websockets
Ignored benchmarks (12) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, dask, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift


# HPT report

- Reliability score: 84.62% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
