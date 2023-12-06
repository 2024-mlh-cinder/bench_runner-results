
# Results vs. 3.11.0

- fork: brandtbucher
- ref: justin_elf
- machine: linux-x86_64
- commit hash: 1799b79
- commit date: 2023-10-02
- overall geometric mean: 1.02x faster
- HPT reliability: 62.29%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231002-pythonperf2-x86_64-brandtbucher-justin_elf-3.13.0a0-1799b79 |
|----------------|:------------------------------------------------------------:|:-----------------------------------------------------------------------:|
| docutils       | 2.86 sec                                                     | 2.92 sec: 1.02x slower                                                  |
| Geometric mean | (ref)                                                        | 1.01x slower                                                            |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231002-pythonperf2-x86_64-brandtbucher-justin_elf-3.13.0a0-1799b79 |
|----------------|:------------------------------------------------------------:|:-----------------------------------------------------------------------:|
| pidigits       | 251 ms                                                       | 265 ms: 1.05x slower                                                    |
| float          | 74.2 ms                                                      | 82.3 ms: 1.11x slower                                                   |
| nbody          | 90.7 ms                                                      | 110 ms: 1.22x slower                                                    |
| Geometric mean | (ref)                                                        | 1.12x slower                                                            |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231002-pythonperf2-x86_64-brandtbucher-justin_elf-3.13.0a0-1799b79 |
|----------------|:------------------------------------------------------------:|:-----------------------------------------------------------------------:|
| regex_compile  | 158 ms                                                       | 155 ms: 1.02x faster                                                    |
| regex_effbot   | 3.50 ms                                                      | 3.56 ms: 1.02x slower                                                   |
| regex_dna      | 227 ms                                                       | 244 ms: 1.07x slower                                                    |
| regex_v8       | 23.9 ms                                                      | 25.8 ms: 1.08x slower                                                   |
| Geometric mean | (ref)                                                        | 1.04x slower                                                            |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231002-pythonperf2-x86_64-brandtbucher-justin_elf-3.13.0a0-1799b79 |
|----------------------|:------------------------------------------------------------:|:-----------------------------------------------------------------------:|
| json_dumps           | 13.4 ms                                                      | 10.5 ms: 1.28x faster                                                   |
| json_loads           | 28.7 us                                                      | 24.7 us: 1.16x faster                                                   |
| unpickle_pure_python | 241 us                                                       | 226 us: 1.07x faster                                                    |
| xml_etree_parse      | 158 ms                                                       | 149 ms: 1.06x faster                                                    |
| pickle_pure_python   | 319 us                                                       | 315 us: 1.01x faster                                                    |
| xml_etree_iterparse  | 104 ms                                                       | 106 ms: 1.01x slower                                                    |
| unpickle_list        | 4.53 us                                                      | 4.62 us: 1.02x slower                                                   |
| xml_etree_process    | 56.5 ms                                                      | 59.1 ms: 1.05x slower                                                   |
| pickle               | 9.64 us                                                      | 10.1 us: 1.05x slower                                                   |
| xml_etree_generate   | 80.5 ms                                                      | 86.1 ms: 1.07x slower                                                   |
| unpickle             | 13.4 us                                                      | 14.5 us: 1.08x slower                                                   |
| pickle_dict          | 30.8 us                                                      | 33.3 us: 1.08x slower                                                   |
| pickle_list          | 3.83 us                                                      | 4.45 us: 1.16x slower                                                   |
| Geometric mean       | (ref)                                                        | 1.00x faster                                                            |

Benchmark hidden because not significant (1): tomli_loads

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231002-pythonperf2-x86_64-brandtbucher-justin_elf-3.13.0a0-1799b79 |
|------------------------|:------------------------------------------------------------:|:-----------------------------------------------------------------------:|
| python_startup_no_site | 7.76 ms                                                      | 8.72 ms: 1.12x slower                                                   |
| python_startup         | 10.8 ms                                                      | 12.7 ms: 1.18x slower                                                   |
| Geometric mean         | (ref)                                                        | 1.15x slower                                                            |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231002-pythonperf2-x86_64-brandtbucher-justin_elf-3.13.0a0-1799b79 |
|-----------|:------------------------------------------------------------:|:-----------------------------------------------------------------------:|
| mako      | 11.0 ms                                                      | 10.3 ms: 1.06x faster                                                   |

All benchmarks:
===============

| Benchmark                | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231002-pythonperf2-x86_64-brandtbucher-justin_elf-3.13.0a0-1799b79 |
|--------------------------|:------------------------------------------------------------:|:-----------------------------------------------------------------------:|
| typing_runtime_protocols | 523 us                                                       | 158 us: 3.30x faster                                                    |
| asyncio_tcp              | 753 ms                                                       | 370 ms: 2.03x faster                                                    |
| asyncio_tcp_ssl          | 3.08 sec                                                     | 1.59 sec: 1.94x faster                                                  |
| generators               | 56.0 ms                                                      | 36.1 ms: 1.55x faster                                                   |
| json_dumps               | 13.4 ms                                                      | 10.5 ms: 1.28x faster                                                   |
| mypy2                    | 451 ms                                                       | 383 ms: 1.18x faster                                                    |
| async_tree_none          | 519 ms                                                       | 445 ms: 1.17x faster                                                    |
| coroutines               | 27.6 ms                                                      | 23.6 ms: 1.17x faster                                                   |
| json_loads               | 28.7 us                                                      | 24.7 us: 1.16x faster                                                   |
| async_tree_memoization   | 630 ms                                                       | 558 ms: 1.13x faster                                                    |
| raytrace                 | 317 ms                                                       | 286 ms: 1.11x faster                                                    |
| chaos                    | 80.9 ms                                                      | 73.5 ms: 1.10x faster                                                   |
| json                     | 5.65 ms                                                      | 5.14 ms: 1.10x faster                                                   |
| crypto_pyaes             | 83.4 ms                                                      | 76.4 ms: 1.09x faster                                                   |
| logging_format           | 8.11 us                                                      | 7.53 us: 1.08x faster                                                   |
| async_tree_io            | 1.17 sec                                                     | 1.09 sec: 1.07x faster                                                  |
| coverage                 | 84.8 ms                                                      | 79.2 ms: 1.07x faster                                                   |
| sqlglot_parse            | 1.53 ms                                                      | 1.43 ms: 1.07x faster                                                   |
| scimark_lu               | 115 ms                                                       | 107 ms: 1.07x faster                                                    |
| unpickle_pure_python     | 241 us                                                       | 226 us: 1.07x faster                                                    |
| mako                     | 11.0 ms                                                      | 10.3 ms: 1.06x faster                                                   |
| xml_etree_parse          | 158 ms                                                       | 149 ms: 1.06x faster                                                    |
| logging_simple           | 7.19 us                                                      | 6.80 us: 1.06x faster                                                   |
| mdp                      | 2.75 sec                                                     | 2.61 sec: 1.05x faster                                                  |
| deepcopy_reduce          | 3.51 us                                                      | 3.33 us: 1.05x faster                                                   |
| async_tree_cpu_io_mixed  | 749 ms                                                       | 711 ms: 1.05x faster                                                    |
| deepcopy                 | 399 us                                                       | 380 us: 1.05x faster                                                    |
| deltablue                | 4.00 ms                                                      | 3.82 ms: 1.05x faster                                                   |
| fannkuch                 | 429 ms                                                       | 410 ms: 1.05x faster                                                    |
| richards_super           | 61.0 ms                                                      | 58.4 ms: 1.04x faster                                                   |
| sqlglot_normalize        | 126 ms                                                       | 121 ms: 1.04x faster                                                    |
| sqlglot_transpile        | 1.92 ms                                                      | 1.84 ms: 1.04x faster                                                   |
| logging_silent           | 101 ns                                                       | 97.8 ns: 1.03x faster                                                   |
| regex_compile            | 158 ms                                                       | 155 ms: 1.02x faster                                                    |
| pickle_pure_python       | 319 us                                                       | 315 us: 1.01x faster                                                    |
| spectral_norm            | 93.3 ms                                                      | 92.7 ms: 1.01x faster                                                   |
| xml_etree_iterparse      | 104 ms                                                       | 106 ms: 1.01x slower                                                    |
| dulwich_log              | 68.4 ms                                                      | 69.4 ms: 1.01x slower                                                   |
| pycparser                | 1.32 sec                                                     | 1.35 sec: 1.02x slower                                                  |
| create_gc_cycles         | 1.61 ms                                                      | 1.63 ms: 1.02x slower                                                   |
| regex_effbot             | 3.50 ms                                                      | 3.56 ms: 1.02x slower                                                   |
| sqlglot_optimize         | 59.8 ms                                                      | 60.9 ms: 1.02x slower                                                   |
| unpickle_list            | 4.53 us                                                      | 4.62 us: 1.02x slower                                                   |
| docutils                 | 2.86 sec                                                     | 2.92 sec: 1.02x slower                                                  |
| gc_traversal             | 3.85 ms                                                      | 3.94 ms: 1.02x slower                                                   |
| meteor_contest           | 131 ms                                                       | 134 ms: 1.03x slower                                                    |
| pathlib                  | 19.1 ms                                                      | 19.7 ms: 1.03x slower                                                   |
| xml_etree_process        | 56.5 ms                                                      | 59.1 ms: 1.05x slower                                                   |
| pickle                   | 9.64 us                                                      | 10.1 us: 1.05x slower                                                   |
| pidigits                 | 251 ms                                                       | 265 ms: 1.05x slower                                                    |
| bench_mp_pool            | 4.62 ms                                                      | 4.88 ms: 1.06x slower                                                   |
| comprehensions           | 24.6 us                                                      | 26.2 us: 1.06x slower                                                   |
| scimark_sparse_mat_mult  | 4.05 ms                                                      | 4.31 ms: 1.06x slower                                                   |
| xml_etree_generate       | 80.5 ms                                                      | 86.1 ms: 1.07x slower                                                   |
| regex_dna                | 227 ms                                                       | 244 ms: 1.07x slower                                                    |
| regex_v8                 | 23.9 ms                                                      | 25.8 ms: 1.08x slower                                                   |
| richards                 | 48.3 ms                                                      | 52.1 ms: 1.08x slower                                                   |
| unpickle                 | 13.4 us                                                      | 14.5 us: 1.08x slower                                                   |
| go                       | 164 ms                                                       | 177 ms: 1.08x slower                                                    |
| pickle_dict              | 30.8 us                                                      | 33.3 us: 1.08x slower                                                   |
| sqlite_synth             | 2.50 us                                                      | 2.71 us: 1.08x slower                                                   |
| pprint_pformat           | 1.63 sec                                                     | 1.79 sec: 1.10x slower                                                  |
| scimark_monte_carlo      | 68.2 ms                                                      | 75.5 ms: 1.11x slower                                                   |
| float                    | 74.2 ms                                                      | 82.3 ms: 1.11x slower                                                   |
| hexiom                   | 7.13 ms                                                      | 7.93 ms: 1.11x slower                                                   |
| pprint_safe_repr         | 784 ms                                                       | 875 ms: 1.12x slower                                                    |
| python_startup_no_site   | 7.76 ms                                                      | 8.72 ms: 1.12x slower                                                   |
| unpack_sequence          | 45.6 ns                                                      | 52.0 ns: 1.14x slower                                                   |
| pickle_list              | 3.83 us                                                      | 4.45 us: 1.16x slower                                                   |
| python_startup           | 10.8 ms                                                      | 12.7 ms: 1.18x slower                                                   |
| pyflate                  | 449 ms                                                       | 532 ms: 1.19x slower                                                    |
| telco                    | 6.86 ms                                                      | 8.26 ms: 1.20x slower                                                   |
| nbody                    | 90.7 ms                                                      | 110 ms: 1.22x slower                                                    |
| scimark_fft              | 285 ms                                                       | 358 ms: 1.26x slower                                                    |
| async_generators         | 316 ms                                                       | 410 ms: 1.30x slower                                                    |
| scimark_sor              | 111 ms                                                       | 146 ms: 1.31x slower                                                    |
| Geometric mean           | (ref)                                                        | 1.02x faster                                                            |

Benchmark hidden because not significant (5): tornado_http, nqueens, bench_thread_pool, deepcopy_memo, tomli_loads
Ignored benchmarks (18) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509.json: 2to3, aiohttp, chameleon, dask, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 62.29% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
