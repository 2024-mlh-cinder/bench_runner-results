
# Results vs. 3.11.0

- fork: brandtbucher
- ref: justin_o2
- machine: linux-x86_64
- commit hash: 2a353e9
- commit date: 2023-10-13
- overall geometric mean: 1.01x faster
- HPT reliability: 96.41%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231013-pythonperf2-x86_64-brandtbucher-justin_o2-3.13.0a0-2a353e9 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------------:|
| docutils       | 2.86 sec                                                     | 2.94 sec: 1.03x slower                                                 |
| tornado_http   | 122 ms                                                       | 124 ms: 1.02x slower                                                   |
| Geometric mean | (ref)                                                        | 1.03x slower                                                           |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231013-pythonperf2-x86_64-brandtbucher-justin_o2-3.13.0a0-2a353e9 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------------:|
| pidigits       | 251 ms                                                       | 265 ms: 1.05x slower                                                   |
| nbody          | 90.7 ms                                                      | 102 ms: 1.12x slower                                                   |
| float          | 74.2 ms                                                      | 89.3 ms: 1.20x slower                                                  |
| Geometric mean | (ref)                                                        | 1.12x slower                                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231013-pythonperf2-x86_64-brandtbucher-justin_o2-3.13.0a0-2a353e9 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------------:|
| regex_compile  | 158 ms                                                       | 160 ms: 1.01x slower                                                   |
| regex_effbot   | 3.50 ms                                                      | 3.57 ms: 1.02x slower                                                  |
| regex_v8       | 23.9 ms                                                      | 25.2 ms: 1.05x slower                                                  |
| regex_dna      | 227 ms                                                       | 245 ms: 1.08x slower                                                   |
| Geometric mean | (ref)                                                        | 1.04x slower                                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231013-pythonperf2-x86_64-brandtbucher-justin_o2-3.13.0a0-2a353e9 |
|----------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------:|
| json_dumps           | 13.4 ms                                                      | 10.6 ms: 1.27x faster                                                  |
| json_loads           | 28.7 us                                                      | 24.5 us: 1.17x faster                                                  |
| unpickle_pure_python | 241 us                                                       | 229 us: 1.05x faster                                                   |
| xml_etree_parse      | 158 ms                                                       | 152 ms: 1.04x faster                                                   |
| xml_etree_iterparse  | 104 ms                                                       | 108 ms: 1.03x slower                                                   |
| unpickle_list        | 4.53 us                                                      | 4.75 us: 1.05x slower                                                  |
| xml_etree_process    | 56.5 ms                                                      | 59.3 ms: 1.05x slower                                                  |
| pickle               | 9.64 us                                                      | 10.2 us: 1.05x slower                                                  |
| pickle_dict          | 30.8 us                                                      | 33.0 us: 1.07x slower                                                  |
| xml_etree_generate   | 80.5 ms                                                      | 87.4 ms: 1.08x slower                                                  |
| tomli_loads          | 2.26 sec                                                     | 2.46 sec: 1.09x slower                                                 |
| unpickle             | 13.4 us                                                      | 14.7 us: 1.09x slower                                                  |
| pickle_list          | 3.83 us                                                      | 4.30 us: 1.12x slower                                                  |
| Geometric mean       | (ref)                                                        | 1.01x slower                                                           |

Benchmark hidden because not significant (1): pickle_pure_python

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231013-pythonperf2-x86_64-brandtbucher-justin_o2-3.13.0a0-2a353e9 |
|------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------:|
| python_startup_no_site | 7.76 ms                                                      | 8.72 ms: 1.12x slower                                                  |
| python_startup         | 10.8 ms                                                      | 12.7 ms: 1.18x slower                                                  |
| Geometric mean         | (ref)                                                        | 1.15x slower                                                           |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231013-pythonperf2-x86_64-brandtbucher-justin_o2-3.13.0a0-2a353e9 |
|-----------|:------------------------------------------------------------:|:----------------------------------------------------------------------:|
| mako      | 11.0 ms                                                      | 12.1 ms: 1.10x slower                                                  |

All benchmarks:
===============

| Benchmark                | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231013-pythonperf2-x86_64-brandtbucher-justin_o2-3.13.0a0-2a353e9 |
|--------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------:|
| typing_runtime_protocols | 523 us                                                       | 155 us: 3.38x faster                                                   |
| asyncio_tcp              | 753 ms                                                       | 370 ms: 2.04x faster                                                   |
| asyncio_tcp_ssl          | 3.08 sec                                                     | 1.58 sec: 1.95x faster                                                 |
| generators               | 56.0 ms                                                      | 36.4 ms: 1.54x faster                                                  |
| json_dumps               | 13.4 ms                                                      | 10.6 ms: 1.27x faster                                                  |
| coroutines               | 27.6 ms                                                      | 23.3 ms: 1.18x faster                                                  |
| mypy2                    | 451 ms                                                       | 384 ms: 1.17x faster                                                   |
| json_loads               | 28.7 us                                                      | 24.5 us: 1.17x faster                                                  |
| async_tree_none          | 519 ms                                                       | 449 ms: 1.16x faster                                                   |
| chaos                    | 80.9 ms                                                      | 70.3 ms: 1.15x faster                                                  |
| async_tree_memoization   | 630 ms                                                       | 563 ms: 1.12x faster                                                   |
| scimark_lu               | 115 ms                                                       | 105 ms: 1.10x faster                                                   |
| json                     | 5.65 ms                                                      | 5.18 ms: 1.09x faster                                                  |
| raytrace                 | 317 ms                                                       | 292 ms: 1.08x faster                                                   |
| sqlglot_parse            | 1.53 ms                                                      | 1.43 ms: 1.07x faster                                                  |
| deepcopy                 | 399 us                                                       | 374 us: 1.07x faster                                                   |
| async_tree_io            | 1.17 sec                                                     | 1.10 sec: 1.06x faster                                                 |
| logging_format           | 8.11 us                                                      | 7.64 us: 1.06x faster                                                  |
| sqlglot_normalize        | 126 ms                                                       | 119 ms: 1.06x faster                                                   |
| deepcopy_reduce          | 3.51 us                                                      | 3.33 us: 1.06x faster                                                  |
| mdp                      | 2.75 sec                                                     | 2.61 sec: 1.05x faster                                                 |
| unpickle_pure_python     | 241 us                                                       | 229 us: 1.05x faster                                                   |
| async_tree_cpu_io_mixed  | 749 ms                                                       | 716 ms: 1.05x faster                                                   |
| richards_super           | 61.0 ms                                                      | 58.4 ms: 1.04x faster                                                  |
| sqlglot_transpile        | 1.92 ms                                                      | 1.85 ms: 1.04x faster                                                  |
| logging_simple           | 7.19 us                                                      | 6.93 us: 1.04x faster                                                  |
| xml_etree_parse          | 158 ms                                                       | 152 ms: 1.04x faster                                                   |
| logging_silent           | 101 ns                                                       | 99.9 ns: 1.01x faster                                                  |
| nqueens                  | 103 ms                                                       | 103 ms: 1.01x slower                                                   |
| spectral_norm            | 93.3 ms                                                      | 94.0 ms: 1.01x slower                                                  |
| sqlglot_optimize         | 59.8 ms                                                      | 60.2 ms: 1.01x slower                                                  |
| pycparser                | 1.32 sec                                                     | 1.34 sec: 1.01x slower                                                 |
| regex_compile            | 158 ms                                                       | 160 ms: 1.01x slower                                                   |
| coverage                 | 84.8 ms                                                      | 86.1 ms: 1.02x slower                                                  |
| dulwich_log              | 68.4 ms                                                      | 69.9 ms: 1.02x slower                                                  |
| regex_effbot             | 3.50 ms                                                      | 3.57 ms: 1.02x slower                                                  |
| tornado_http             | 122 ms                                                       | 124 ms: 1.02x slower                                                   |
| gc_traversal             | 3.85 ms                                                      | 3.95 ms: 1.03x slower                                                  |
| fannkuch                 | 429 ms                                                       | 440 ms: 1.03x slower                                                   |
| docutils                 | 2.86 sec                                                     | 2.94 sec: 1.03x slower                                                 |
| xml_etree_iterparse      | 104 ms                                                       | 108 ms: 1.03x slower                                                   |
| deepcopy_memo            | 38.8 us                                                      | 40.2 us: 1.04x slower                                                  |
| unpickle_list            | 4.53 us                                                      | 4.75 us: 1.05x slower                                                  |
| xml_etree_process        | 56.5 ms                                                      | 59.3 ms: 1.05x slower                                                  |
| regex_v8                 | 23.9 ms                                                      | 25.2 ms: 1.05x slower                                                  |
| pidigits                 | 251 ms                                                       | 265 ms: 1.05x slower                                                   |
| pickle                   | 9.64 us                                                      | 10.2 us: 1.05x slower                                                  |
| unpack_sequence          | 45.6 ns                                                      | 48.3 ns: 1.06x slower                                                  |
| pathlib                  | 19.1 ms                                                      | 20.2 ms: 1.06x slower                                                  |
| meteor_contest           | 131 ms                                                       | 139 ms: 1.07x slower                                                   |
| pickle_dict              | 30.8 us                                                      | 33.0 us: 1.07x slower                                                  |
| go                       | 164 ms                                                       | 176 ms: 1.07x slower                                                   |
| regex_dna                | 227 ms                                                       | 245 ms: 1.08x slower                                                   |
| richards                 | 48.3 ms                                                      | 52.3 ms: 1.08x slower                                                  |
| sqlite_synth             | 2.50 us                                                      | 2.71 us: 1.08x slower                                                  |
| xml_etree_generate       | 80.5 ms                                                      | 87.4 ms: 1.08x slower                                                  |
| tomli_loads              | 2.26 sec                                                     | 2.46 sec: 1.09x slower                                                 |
| unpickle                 | 13.4 us                                                      | 14.7 us: 1.09x slower                                                  |
| mako                     | 11.0 ms                                                      | 12.1 ms: 1.10x slower                                                  |
| scimark_monte_carlo      | 68.2 ms                                                      | 74.9 ms: 1.10x slower                                                  |
| pprint_pformat           | 1.63 sec                                                     | 1.79 sec: 1.10x slower                                                 |
| pprint_safe_repr         | 784 ms                                                       | 878 ms: 1.12x slower                                                   |
| pickle_list              | 3.83 us                                                      | 4.30 us: 1.12x slower                                                  |
| nbody                    | 90.7 ms                                                      | 102 ms: 1.12x slower                                                   |
| python_startup_no_site   | 7.76 ms                                                      | 8.72 ms: 1.12x slower                                                  |
| comprehensions           | 24.6 us                                                      | 28.7 us: 1.17x slower                                                  |
| scimark_sparse_mat_mult  | 4.05 ms                                                      | 4.75 ms: 1.17x slower                                                  |
| python_startup           | 10.8 ms                                                      | 12.7 ms: 1.18x slower                                                  |
| pyflate                  | 449 ms                                                       | 530 ms: 1.18x slower                                                   |
| float                    | 74.2 ms                                                      | 89.3 ms: 1.20x slower                                                  |
| telco                    | 6.86 ms                                                      | 8.30 ms: 1.21x slower                                                  |
| deltablue                | 4.00 ms                                                      | 4.89 ms: 1.22x slower                                                  |
| scimark_fft              | 285 ms                                                       | 356 ms: 1.25x slower                                                   |
| hexiom                   | 7.13 ms                                                      | 8.97 ms: 1.26x slower                                                  |
| async_generators         | 316 ms                                                       | 418 ms: 1.32x slower                                                   |
| scimark_sor              | 111 ms                                                       | 151 ms: 1.36x slower                                                   |
| Geometric mean           | (ref)                                                        | 1.01x faster                                                           |

Benchmark hidden because not significant (5): bench_thread_pool, bench_mp_pool, pickle_pure_python, create_gc_cycles, crypto_pyaes
Ignored benchmarks (18) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509.json: 2to3, aiohttp, chameleon, dask, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 96.41% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
