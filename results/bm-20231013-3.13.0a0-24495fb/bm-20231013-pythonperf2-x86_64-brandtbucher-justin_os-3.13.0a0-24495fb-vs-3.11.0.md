
# Results vs. 3.11.0

- fork: brandtbucher
- ref: justin_os
- machine: linux-x86_64
- commit hash: 24495fb
- commit date: 2023-10-13
- overall geometric mean: 1.01x faster
- HPT reliability: 95.61%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231013-pythonperf2-x86_64-brandtbucher-justin_os-3.13.0a0-24495fb |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------------:|
| docutils       | 2.86 sec                                                     | 2.94 sec: 1.03x slower                                                 |
| tornado_http   | 122 ms                                                       | 123 ms: 1.01x slower                                                   |
| Geometric mean | (ref)                                                        | 1.02x slower                                                           |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231013-pythonperf2-x86_64-brandtbucher-justin_os-3.13.0a0-24495fb |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------------:|
| pidigits       | 251 ms                                                       | 265 ms: 1.06x slower                                                   |
| nbody          | 90.7 ms                                                      | 100 ms: 1.11x slower                                                   |
| float          | 74.2 ms                                                      | 88.0 ms: 1.19x slower                                                  |
| Geometric mean | (ref)                                                        | 1.12x slower                                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231013-pythonperf2-x86_64-brandtbucher-justin_os-3.13.0a0-24495fb |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------------:|
| regex_compile  | 158 ms                                                       | 159 ms: 1.01x slower                                                   |
| regex_effbot   | 3.50 ms                                                      | 3.59 ms: 1.03x slower                                                  |
| regex_v8       | 23.9 ms                                                      | 24.9 ms: 1.04x slower                                                  |
| regex_dna      | 227 ms                                                       | 248 ms: 1.09x slower                                                   |
| Geometric mean | (ref)                                                        | 1.04x slower                                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark           | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231013-pythonperf2-x86_64-brandtbucher-justin_os-3.13.0a0-24495fb |
|---------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------:|
| json_dumps          | 13.4 ms                                                      | 10.7 ms: 1.25x faster                                                  |
| json_loads          | 28.7 us                                                      | 25.0 us: 1.15x faster                                                  |
| xml_etree_parse     | 158 ms                                                       | 147 ms: 1.08x faster                                                   |
| pickle_pure_python  | 319 us                                                       | 322 us: 1.01x slower                                                   |
| xml_etree_iterparse | 104 ms                                                       | 106 ms: 1.02x slower                                                   |
| pickle_dict         | 30.8 us                                                      | 32.2 us: 1.05x slower                                                  |
| pickle              | 9.64 us                                                      | 10.1 us: 1.05x slower                                                  |
| xml_etree_process   | 56.5 ms                                                      | 59.6 ms: 1.06x slower                                                  |
| unpickle_list       | 4.53 us                                                      | 4.79 us: 1.06x slower                                                  |
| xml_etree_generate  | 80.5 ms                                                      | 86.2 ms: 1.07x slower                                                  |
| unpickle            | 13.4 us                                                      | 14.7 us: 1.09x slower                                                  |
| tomli_loads         | 2.26 sec                                                     | 2.49 sec: 1.10x slower                                                 |
| pickle_list         | 3.83 us                                                      | 4.40 us: 1.15x slower                                                  |
| Geometric mean      | (ref)                                                        | 1.01x slower                                                           |

Benchmark hidden because not significant (1): unpickle_pure_python

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231013-pythonperf2-x86_64-brandtbucher-justin_os-3.13.0a0-24495fb |
|------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------:|
| python_startup_no_site | 7.76 ms                                                      | 8.71 ms: 1.12x slower                                                  |
| python_startup         | 10.8 ms                                                      | 12.8 ms: 1.19x slower                                                  |
| Geometric mean         | (ref)                                                        | 1.15x slower                                                           |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231013-pythonperf2-x86_64-brandtbucher-justin_os-3.13.0a0-24495fb |
|-----------|:------------------------------------------------------------:|:----------------------------------------------------------------------:|
| mako      | 11.0 ms                                                      | 12.0 ms: 1.09x slower                                                  |

All benchmarks:
===============

| Benchmark                | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231013-pythonperf2-x86_64-brandtbucher-justin_os-3.13.0a0-24495fb |
|--------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------:|
| typing_runtime_protocols | 523 us                                                       | 158 us: 3.31x faster                                                   |
| asyncio_tcp              | 753 ms                                                       | 374 ms: 2.01x faster                                                   |
| asyncio_tcp_ssl          | 3.08 sec                                                     | 1.59 sec: 1.94x faster                                                 |
| generators               | 56.0 ms                                                      | 36.7 ms: 1.53x faster                                                  |
| json_dumps               | 13.4 ms                                                      | 10.7 ms: 1.25x faster                                                  |
| coroutines               | 27.6 ms                                                      | 23.4 ms: 1.18x faster                                                  |
| mypy2                    | 451 ms                                                       | 385 ms: 1.17x faster                                                   |
| async_tree_none          | 519 ms                                                       | 448 ms: 1.16x faster                                                   |
| chaos                    | 80.9 ms                                                      | 70.2 ms: 1.15x faster                                                  |
| json_loads               | 28.7 us                                                      | 25.0 us: 1.15x faster                                                  |
| async_tree_memoization   | 630 ms                                                       | 563 ms: 1.12x faster                                                   |
| raytrace                 | 317 ms                                                       | 285 ms: 1.11x faster                                                   |
| json                     | 5.65 ms                                                      | 5.13 ms: 1.10x faster                                                  |
| scimark_lu               | 115 ms                                                       | 105 ms: 1.09x faster                                                   |
| xml_etree_parse          | 158 ms                                                       | 147 ms: 1.08x faster                                                   |
| sqlglot_parse            | 1.53 ms                                                      | 1.44 ms: 1.06x faster                                                  |
| async_tree_io            | 1.17 sec                                                     | 1.10 sec: 1.06x faster                                                 |
| logging_format           | 8.11 us                                                      | 7.75 us: 1.05x faster                                                  |
| async_tree_cpu_io_mixed  | 749 ms                                                       | 716 ms: 1.05x faster                                                   |
| sqlglot_normalize        | 126 ms                                                       | 121 ms: 1.04x faster                                                   |
| richards_super           | 61.0 ms                                                      | 58.8 ms: 1.04x faster                                                  |
| sqlglot_transpile        | 1.92 ms                                                      | 1.85 ms: 1.04x faster                                                  |
| bench_thread_pool        | 1.01 ms                                                      | 978 us: 1.03x faster                                                   |
| deepcopy                 | 399 us                                                       | 388 us: 1.03x faster                                                   |
| coverage                 | 84.8 ms                                                      | 82.4 ms: 1.03x faster                                                  |
| mdp                      | 2.75 sec                                                     | 2.68 sec: 1.03x faster                                                 |
| deepcopy_reduce          | 3.51 us                                                      | 3.43 us: 1.02x faster                                                  |
| logging_simple           | 7.19 us                                                      | 7.09 us: 1.01x faster                                                  |
| nqueens                  | 103 ms                                                       | 102 ms: 1.01x faster                                                   |
| regex_compile            | 158 ms                                                       | 159 ms: 1.01x slower                                                   |
| pickle_pure_python       | 319 us                                                       | 322 us: 1.01x slower                                                   |
| spectral_norm            | 93.3 ms                                                      | 94.1 ms: 1.01x slower                                                  |
| tornado_http             | 122 ms                                                       | 123 ms: 1.01x slower                                                   |
| dulwich_log              | 68.4 ms                                                      | 69.5 ms: 1.02x slower                                                  |
| xml_etree_iterparse      | 104 ms                                                       | 106 ms: 1.02x slower                                                   |
| pycparser                | 1.32 sec                                                     | 1.35 sec: 1.02x slower                                                 |
| fannkuch                 | 429 ms                                                       | 437 ms: 1.02x slower                                                   |
| sqlglot_optimize         | 59.8 ms                                                      | 61.2 ms: 1.02x slower                                                  |
| deepcopy_memo            | 38.8 us                                                      | 39.8 us: 1.03x slower                                                  |
| regex_effbot             | 3.50 ms                                                      | 3.59 ms: 1.03x slower                                                  |
| docutils                 | 2.86 sec                                                     | 2.94 sec: 1.03x slower                                                 |
| unpack_sequence          | 45.6 ns                                                      | 47.1 ns: 1.03x slower                                                  |
| gc_traversal             | 3.85 ms                                                      | 3.97 ms: 1.03x slower                                                  |
| regex_v8                 | 23.9 ms                                                      | 24.9 ms: 1.04x slower                                                  |
| meteor_contest           | 131 ms                                                       | 137 ms: 1.04x slower                                                   |
| pickle_dict              | 30.8 us                                                      | 32.2 us: 1.05x slower                                                  |
| pathlib                  | 19.1 ms                                                      | 20.0 ms: 1.05x slower                                                  |
| pickle                   | 9.64 us                                                      | 10.1 us: 1.05x slower                                                  |
| pidigits                 | 251 ms                                                       | 265 ms: 1.06x slower                                                   |
| xml_etree_process        | 56.5 ms                                                      | 59.6 ms: 1.06x slower                                                  |
| unpickle_list            | 4.53 us                                                      | 4.79 us: 1.06x slower                                                  |
| sqlite_synth             | 2.50 us                                                      | 2.67 us: 1.07x slower                                                  |
| xml_etree_generate       | 80.5 ms                                                      | 86.2 ms: 1.07x slower                                                  |
| scimark_monte_carlo      | 68.2 ms                                                      | 73.5 ms: 1.08x slower                                                  |
| richards                 | 48.3 ms                                                      | 52.6 ms: 1.09x slower                                                  |
| mako                     | 11.0 ms                                                      | 12.0 ms: 1.09x slower                                                  |
| regex_dna                | 227 ms                                                       | 248 ms: 1.09x slower                                                   |
| go                       | 164 ms                                                       | 179 ms: 1.09x slower                                                   |
| unpickle                 | 13.4 us                                                      | 14.7 us: 1.09x slower                                                  |
| tomli_loads              | 2.26 sec                                                     | 2.49 sec: 1.10x slower                                                 |
| pprint_pformat           | 1.63 sec                                                     | 1.80 sec: 1.11x slower                                                 |
| nbody                    | 90.7 ms                                                      | 100 ms: 1.11x slower                                                   |
| python_startup_no_site   | 7.76 ms                                                      | 8.71 ms: 1.12x slower                                                  |
| pprint_safe_repr         | 784 ms                                                       | 882 ms: 1.12x slower                                                   |
| pickle_list              | 3.83 us                                                      | 4.40 us: 1.15x slower                                                  |
| comprehensions           | 24.6 us                                                      | 28.4 us: 1.16x slower                                                  |
| scimark_sparse_mat_mult  | 4.05 ms                                                      | 4.71 ms: 1.16x slower                                                  |
| pyflate                  | 449 ms                                                       | 528 ms: 1.18x slower                                                   |
| float                    | 74.2 ms                                                      | 88.0 ms: 1.19x slower                                                  |
| python_startup           | 10.8 ms                                                      | 12.8 ms: 1.19x slower                                                  |
| deltablue                | 4.00 ms                                                      | 4.81 ms: 1.20x slower                                                  |
| telco                    | 6.86 ms                                                      | 8.34 ms: 1.22x slower                                                  |
| hexiom                   | 7.13 ms                                                      | 8.90 ms: 1.25x slower                                                  |
| scimark_fft              | 285 ms                                                       | 362 ms: 1.27x slower                                                   |
| async_generators         | 316 ms                                                       | 410 ms: 1.30x slower                                                   |
| scimark_sor              | 111 ms                                                       | 147 ms: 1.32x slower                                                   |
| Geometric mean           | (ref)                                                        | 1.01x faster                                                           |

Benchmark hidden because not significant (5): logging_silent, create_gc_cycles, unpickle_pure_python, crypto_pyaes, bench_mp_pool
Ignored benchmarks (18) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509.json: 2to3, aiohttp, chameleon, dask, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 95.61% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
