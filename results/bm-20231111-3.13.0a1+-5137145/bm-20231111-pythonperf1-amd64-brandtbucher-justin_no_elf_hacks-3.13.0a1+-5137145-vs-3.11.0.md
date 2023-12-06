
# Results vs. 3.11.0

- fork: brandtbucher
- ref: justin_no_elf_hacks
- machine: windows-amd64
- commit hash: 5137145
- commit date: 2023-11-11
- overall geometric mean: 1.07x faster \*
- HPT reliability: 99.99%
- HPT 99th percentile: 1.01x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231111-pythonperf1-amd64-brandtbucher-justin_no_elf_hacks-3.13.0a1+-5137145 |
|----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| 2to3           | 207 ms                                                      | 216 ms: 1.04x slower                                                             |
| chameleon      | 5.35 ms                                                     | 4.98 ms: 1.08x faster                                                            |
| docutils       | 1.59 sec                                                    | 1.56 sec: 1.02x faster                                                           |
| tornado_http   | 89.9 ms                                                     | 89.0 ms: 1.01x faster                                                            |
| Geometric mean | (ref)                                                       | 1.02x faster                                                                     |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231111-pythonperf1-amd64-brandtbucher-justin_no_elf_hacks-3.13.0a1+-5137145 |
|----------------------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| async_tree_none            | 314 ms                                                      | 271 ms: 1.16x faster                                                             |
| async_tree_cpu_io_mixed    | 495 ms                                                      | 456 ms: 1.09x faster                                                             |
| async_tree_memoization     | 367 ms                                                      | 346 ms: 1.06x faster                                                             |
| async_tree_none_tg         | 299 ms                                                      | 286 ms: 1.05x faster                                                             |
| async_tree_cpu_io_mixed_tg | 503 ms                                                      | 481 ms: 1.04x faster                                                             |
| async_tree_memoization_tg  | 380 ms                                                      | 364 ms: 1.04x faster                                                             |
| async_tree_io              | 753 ms                                                      | 725 ms: 1.04x faster                                                             |
| async_tree_io_tg           | 795 ms                                                      | 769 ms: 1.03x faster                                                             |
| Geometric mean             | (ref)                                                       | 1.06x faster                                                                     |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231111-pythonperf1-amd64-brandtbucher-justin_no_elf_hacks-3.13.0a1+-5137145 |
|----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| float          | 54.4 ms                                                     | 51.5 ms: 1.06x faster                                                            |
| pidigits       | 149 ms                                                      | 150 ms: 1.01x slower                                                             |
| nbody          | 69.3 ms                                                     | 71.9 ms: 1.04x slower                                                            |
| Geometric mean | (ref)                                                       | 1.00x faster                                                                     |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231111-pythonperf1-amd64-brandtbucher-justin_no_elf_hacks-3.13.0a1+-5137145 |
|----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| regex_compile  | 90.8 ms                                                     | 81.7 ms: 1.11x faster                                                            |
| regex_dna      | 121 ms                                                      | 119 ms: 1.02x faster                                                             |
| regex_effbot   | 1.52 ms                                                     | 1.57 ms: 1.03x slower                                                            |
| regex_v8       | 13.7 ms                                                     | 14.7 ms: 1.08x slower                                                            |
| Geometric mean | (ref)                                                       | 1.00x faster                                                                     |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231111-pythonperf1-amd64-brandtbucher-justin_no_elf_hacks-3.13.0a1+-5137145 |
|----------------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| json_dumps           | 7.90 ms                                                     | 5.79 ms: 1.36x faster                                                            |
| pickle_pure_python   | 207 us                                                      | 182 us: 1.14x faster                                                             |
| unpickle_pure_python | 152 us                                                      | 136 us: 1.12x faster                                                             |
| tomli_loads          | 1.42 sec                                                    | 1.32 sec: 1.08x faster                                                           |
| xml_etree_parse      | 94.5 ms                                                     | 92.1 ms: 1.03x faster                                                            |
| pickle_dict          | 17.8 us                                                     | 18.4 us: 1.04x slower                                                            |
| xml_etree_generate   | 52.2 ms                                                     | 54.2 ms: 1.04x slower                                                            |
| json_loads           | 12.9 us                                                     | 13.5 us: 1.05x slower                                                            |
| unpickle             | 7.82 us                                                     | 8.22 us: 1.05x slower                                                            |
| unpickle_list        | 2.57 us                                                     | 2.71 us: 1.06x slower                                                            |
| pickle               | 6.53 us                                                     | 7.07 us: 1.08x slower                                                            |
| pickle_list          | 2.68 us                                                     | 2.91 us: 1.09x slower                                                            |
| Geometric mean       | (ref)                                                       | 1.02x faster                                                                     |

Benchmark hidden because not significant (2): xml_etree_process, xml_etree_iterparse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231111-pythonperf1-amd64-brandtbucher-justin_no_elf_hacks-3.13.0a1+-5137145 |
|------------------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| python_startup         | 18.8 ms                                                     | 20.0 ms: 1.06x slower                                                            |
| python_startup_no_site | 15.5 ms                                                     | 18.1 ms: 1.17x slower                                                            |
| Geometric mean         | (ref)                                                       | 1.12x slower                                                                     |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231111-pythonperf1-amd64-brandtbucher-justin_no_elf_hacks-3.13.0a1+-5137145 |
|-----------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| mako      | 7.55 ms                                                     | 6.48 ms: 1.17x faster                                                            |

All benchmarks:
===============

| Benchmark                  | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231111-pythonperf1-amd64-brandtbucher-justin_no_elf_hacks-3.13.0a1+-5137145 |
|----------------------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| typing_runtime_protocols   | 320 us                                                      | 76.5 us: 4.18x faster                                                            |
| generators                 | 34.0 ms                                                     | 20.9 ms: 1.63x faster                                                            |
| json_dumps                 | 7.90 ms                                                     | 5.79 ms: 1.36x faster                                                            |
| comprehensions             | 15.6 us                                                     | 11.5 us: 1.35x faster                                                            |
| richards_super             | 37.9 ms                                                     | 29.0 ms: 1.31x faster                                                            |
| asyncio_tcp                | 614 ms                                                      | 471 ms: 1.30x faster                                                             |
| raytrace                   | 211 ms                                                      | 169 ms: 1.25x faster                                                             |
| logging_silent             | 70.7 ns                                                     | 56.9 ns: 1.24x faster                                                            |
| deltablue                  | 2.63 ms                                                     | 2.13 ms: 1.23x faster                                                            |
| sqlglot_parse              | 939 us                                                      | 779 us: 1.21x faster                                                             |
| spectral_norm              | 69.9 ms                                                     | 58.3 ms: 1.20x faster                                                            |
| richards                   | 30.8 ms                                                     | 25.9 ms: 1.19x faster                                                            |
| sympy_sum                  | 100.0 ms                                                    | 85.4 ms: 1.17x faster                                                            |
| unpack_sequence            | 47.0 ns                                                     | 40.2 ns: 1.17x faster                                                            |
| mako                       | 7.55 ms                                                     | 6.48 ms: 1.17x faster                                                            |
| sqlite_synth               | 1.79 us                                                     | 1.55 us: 1.16x faster                                                            |
| mdp                        | 1.73 sec                                                    | 1.49 sec: 1.16x faster                                                           |
| async_tree_none            | 314 ms                                                      | 271 ms: 1.16x faster                                                             |
| sympy_str                  | 184 ms                                                      | 160 ms: 1.15x faster                                                             |
| sqlglot_transpile          | 1.15 ms                                                     | 1.01 ms: 1.14x faster                                                            |
| pickle_pure_python         | 207 us                                                      | 182 us: 1.14x faster                                                             |
| chaos                      | 46.8 ms                                                     | 41.4 ms: 1.13x faster                                                            |
| unpickle_pure_python       | 152 us                                                      | 136 us: 1.12x faster                                                             |
| regex_compile              | 90.8 ms                                                     | 81.7 ms: 1.11x faster                                                            |
| deepcopy                   | 242 us                                                      | 218 us: 1.11x faster                                                             |
| coroutines                 | 14.7 ms                                                     | 13.4 ms: 1.10x faster                                                            |
| sympy_expand               | 299 ms                                                      | 274 ms: 1.09x faster                                                             |
| deepcopy_memo              | 25.5 us                                                     | 23.3 us: 1.09x faster                                                            |
| go                         | 98.8 ms                                                     | 90.8 ms: 1.09x faster                                                            |
| async_tree_cpu_io_mixed    | 495 ms                                                      | 456 ms: 1.09x faster                                                             |
| logging_simple             | 6.60 us                                                     | 6.11 us: 1.08x faster                                                            |
| logging_format             | 7.06 us                                                     | 6.54 us: 1.08x faster                                                            |
| tomli_loads                | 1.42 sec                                                    | 1.32 sec: 1.08x faster                                                           |
| chameleon                  | 5.35 ms                                                     | 4.98 ms: 1.08x faster                                                            |
| dulwich_log                | 44.1 ms                                                     | 41.3 ms: 1.07x faster                                                            |
| sympy_integrate            | 13.7 ms                                                     | 12.8 ms: 1.07x faster                                                            |
| scimark_sparse_mat_mult    | 2.59 ms                                                     | 2.43 ms: 1.07x faster                                                            |
| asyncio_tcp_ssl            | 2.02 sec                                                    | 1.90 sec: 1.06x faster                                                           |
| crypto_pyaes               | 48.2 ms                                                     | 45.3 ms: 1.06x faster                                                            |
| async_tree_memoization     | 367 ms                                                      | 346 ms: 1.06x faster                                                             |
| scimark_lu                 | 62.3 ms                                                     | 58.8 ms: 1.06x faster                                                            |
| deepcopy_reduce            | 2.07 us                                                     | 1.96 us: 1.06x faster                                                            |
| sqlglot_normalize          | 191 ms                                                      | 181 ms: 1.06x faster                                                             |
| float                      | 54.4 ms                                                     | 51.5 ms: 1.06x faster                                                            |
| nqueens                    | 66.1 ms                                                     | 62.8 ms: 1.05x faster                                                            |
| async_tree_none_tg         | 299 ms                                                      | 286 ms: 1.05x faster                                                             |
| async_tree_cpu_io_mixed_tg | 503 ms                                                      | 481 ms: 1.04x faster                                                             |
| async_tree_memoization_tg  | 380 ms                                                      | 364 ms: 1.04x faster                                                             |
| async_tree_io              | 753 ms                                                      | 725 ms: 1.04x faster                                                             |
| async_tree_io_tg           | 795 ms                                                      | 769 ms: 1.03x faster                                                             |
| hexiom                     | 4.51 ms                                                     | 4.37 ms: 1.03x faster                                                            |
| sqlglot_optimize           | 35.1 ms                                                     | 34.2 ms: 1.03x faster                                                            |
| xml_etree_parse            | 94.5 ms                                                     | 92.1 ms: 1.03x faster                                                            |
| pyflate                    | 305 ms                                                      | 300 ms: 1.02x faster                                                             |
| regex_dna                  | 121 ms                                                      | 119 ms: 1.02x faster                                                             |
| bench_thread_pool          | 847 us                                                      | 834 us: 1.02x faster                                                             |
| docutils                   | 1.59 sec                                                    | 1.56 sec: 1.02x faster                                                           |
| tornado_http               | 89.9 ms                                                     | 89.0 ms: 1.01x faster                                                            |
| scimark_monte_carlo        | 44.6 ms                                                     | 44.3 ms: 1.01x faster                                                            |
| pprint_pformat             | 1.06 sec                                                    | 1.05 sec: 1.01x faster                                                           |
| pprint_safe_repr           | 519 ms                                                      | 516 ms: 1.00x faster                                                             |
| fannkuch                   | 248 ms                                                      | 250 ms: 1.01x slower                                                             |
| pidigits                   | 149 ms                                                      | 150 ms: 1.01x slower                                                             |
| create_gc_cycles           | 706 us                                                      | 721 us: 1.02x slower                                                             |
| gc_traversal               | 1.46 ms                                                     | 1.49 ms: 1.03x slower                                                            |
| regex_effbot               | 1.52 ms                                                     | 1.57 ms: 1.03x slower                                                            |
| coverage                   | 43.0 ms                                                     | 44.5 ms: 1.04x slower                                                            |
| pickle_dict                | 17.8 us                                                     | 18.4 us: 1.04x slower                                                            |
| nbody                      | 69.3 ms                                                     | 71.9 ms: 1.04x slower                                                            |
| xml_etree_generate         | 52.2 ms                                                     | 54.2 ms: 1.04x slower                                                            |
| 2to3                       | 207 ms                                                      | 216 ms: 1.04x slower                                                             |
| json_loads                 | 12.9 us                                                     | 13.5 us: 1.05x slower                                                            |
| unpickle                   | 7.82 us                                                     | 8.22 us: 1.05x slower                                                            |
| scimark_fft                | 181 ms                                                      | 191 ms: 1.06x slower                                                             |
| unpickle_list              | 2.57 us                                                     | 2.71 us: 1.06x slower                                                            |
| bench_mp_pool              | 61.1 ms                                                     | 64.8 ms: 1.06x slower                                                            |
| pycparser                  | 705 ms                                                      | 748 ms: 1.06x slower                                                             |
| python_startup             | 18.8 ms                                                     | 20.0 ms: 1.06x slower                                                            |
| regex_v8                   | 13.7 ms                                                     | 14.7 ms: 1.08x slower                                                            |
| pickle                     | 6.53 us                                                     | 7.07 us: 1.08x slower                                                            |
| pickle_list                | 2.68 us                                                     | 2.91 us: 1.09x slower                                                            |
| scimark_sor                | 76.4 ms                                                     | 84.0 ms: 1.10x slower                                                            |
| pathlib                    | 69.4 ms                                                     | 79.1 ms: 1.14x slower                                                            |
| python_startup_no_site     | 15.5 ms                                                     | 18.1 ms: 1.17x slower                                                            |
| telco                      | 3.93 ms                                                     | 4.66 ms: 1.19x slower                                                            |
| mypy2                      | 226 ms                                                      | 293 ms: 1.29x slower                                                             |
| async_generators           | 181 ms                                                      | 238 ms: 1.31x slower                                                             |
| Geometric mean             | (ref)                                                       | 1.07x faster                                                                     |

Benchmark hidden because not significant (4): meteor_contest, xml_etree_process, xml_etree_iterparse, json
Ignored benchmarks (11) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, dask, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift


# HPT report

- Reliability score: 99.99% likely to be faster
- 90% likely to have a speedup of 1.02x
- 95% likely to have a speedup of 1.02x
- 99% likely to have a speedup of 1.01x
