
# Results vs. 3.11.0

- fork: brandtbucher
- ref: justin
- machine: linux-x86_64
- commit hash: 07fb485
- commit date: 2023-10-11
- overall geometric mean: 1.01x faster
- HPT reliability: 84.15%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231011-pythonperf2-x86_64-brandtbucher-justin-3.13.0a0-07fb485 |
|----------------|:------------------------------------------------------------:|:-------------------------------------------------------------------:|
| docutils       | 2.86 sec                                                     | 2.93 sec: 1.02x slower                                              |
| tornado_http   | 122 ms                                                       | 124 ms: 1.02x slower                                                |
| Geometric mean | (ref)                                                        | 1.02x slower                                                        |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231011-pythonperf2-x86_64-brandtbucher-justin-3.13.0a0-07fb485 |
|----------------|:------------------------------------------------------------:|:-------------------------------------------------------------------:|
| pidigits       | 251 ms                                                       | 265 ms: 1.06x slower                                                |
| nbody          | 90.7 ms                                                      | 100 ms: 1.10x slower                                                |
| float          | 74.2 ms                                                      | 88.8 ms: 1.20x slower                                               |
| Geometric mean | (ref)                                                        | 1.12x slower                                                        |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231011-pythonperf2-x86_64-brandtbucher-justin-3.13.0a0-07fb485 |
|----------------|:------------------------------------------------------------:|:-------------------------------------------------------------------:|
| regex_compile  | 158 ms                                                       | 159 ms: 1.01x slower                                                |
| regex_effbot   | 3.50 ms                                                      | 3.62 ms: 1.03x slower                                               |
| regex_dna      | 227 ms                                                       | 247 ms: 1.09x slower                                                |
| regex_v8       | 23.9 ms                                                      | 26.6 ms: 1.11x slower                                               |
| Geometric mean | (ref)                                                        | 1.06x slower                                                        |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231011-pythonperf2-x86_64-brandtbucher-justin-3.13.0a0-07fb485 |
|----------------------|:------------------------------------------------------------:|:-------------------------------------------------------------------:|
| json_dumps           | 13.4 ms                                                      | 10.8 ms: 1.24x faster                                               |
| json_loads           | 28.7 us                                                      | 24.6 us: 1.16x faster                                               |
| xml_etree_parse      | 158 ms                                                       | 149 ms: 1.06x faster                                                |
| unpickle_pure_python | 241 us                                                       | 237 us: 1.02x faster                                                |
| pickle_pure_python   | 319 us                                                       | 317 us: 1.01x faster                                                |
| xml_etree_iterparse  | 104 ms                                                       | 107 ms: 1.03x slower                                                |
| unpickle_list        | 4.53 us                                                      | 4.68 us: 1.03x slower                                               |
| pickle               | 9.64 us                                                      | 10.0 us: 1.04x slower                                               |
| xml_etree_process    | 56.5 ms                                                      | 58.8 ms: 1.04x slower                                               |
| unpickle             | 13.4 us                                                      | 14.3 us: 1.06x slower                                               |
| pickle_dict          | 30.8 us                                                      | 32.8 us: 1.07x slower                                               |
| xml_etree_generate   | 80.5 ms                                                      | 85.9 ms: 1.07x slower                                               |
| tomli_loads          | 2.26 sec                                                     | 2.48 sec: 1.10x slower                                              |
| pickle_list          | 3.83 us                                                      | 4.33 us: 1.13x slower                                               |
| Geometric mean       | (ref)                                                        | 1.01x slower                                                        |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231011-pythonperf2-x86_64-brandtbucher-justin-3.13.0a0-07fb485 |
|------------------------|:------------------------------------------------------------:|:-------------------------------------------------------------------:|
| python_startup_no_site | 7.76 ms                                                      | 8.69 ms: 1.12x slower                                               |
| python_startup         | 10.8 ms                                                      | 12.6 ms: 1.17x slower                                               |
| Geometric mean         | (ref)                                                        | 1.15x slower                                                        |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231011-pythonperf2-x86_64-brandtbucher-justin-3.13.0a0-07fb485 |
|-----------|:------------------------------------------------------------:|:-------------------------------------------------------------------:|
| mako      | 11.0 ms                                                      | 12.1 ms: 1.10x slower                                               |

All benchmarks:
===============

| Benchmark                | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231011-pythonperf2-x86_64-brandtbucher-justin-3.13.0a0-07fb485 |
|--------------------------|:------------------------------------------------------------:|:-------------------------------------------------------------------:|
| typing_runtime_protocols | 523 us                                                       | 156 us: 3.35x faster                                                |
| asyncio_tcp              | 753 ms                                                       | 371 ms: 2.03x faster                                                |
| asyncio_tcp_ssl          | 3.08 sec                                                     | 1.59 sec: 1.94x faster                                              |
| generators               | 56.0 ms                                                      | 36.2 ms: 1.55x faster                                               |
| json_dumps               | 13.4 ms                                                      | 10.8 ms: 1.24x faster                                               |
| mypy2                    | 451 ms                                                       | 382 ms: 1.18x faster                                                |
| coroutines               | 27.6 ms                                                      | 23.4 ms: 1.18x faster                                               |
| async_tree_none          | 519 ms                                                       | 444 ms: 1.17x faster                                                |
| json_loads               | 28.7 us                                                      | 24.6 us: 1.16x faster                                               |
| chaos                    | 80.9 ms                                                      | 69.8 ms: 1.16x faster                                               |
| async_tree_memoization   | 630 ms                                                       | 557 ms: 1.13x faster                                                |
| scimark_lu               | 115 ms                                                       | 104 ms: 1.10x faster                                                |
| gc_traversal             | 3.85 ms                                                      | 3.52 ms: 1.09x faster                                               |
| json                     | 5.65 ms                                                      | 5.17 ms: 1.09x faster                                               |
| raytrace                 | 317 ms                                                       | 291 ms: 1.09x faster                                                |
| async_tree_io            | 1.17 sec                                                     | 1.09 sec: 1.08x faster                                              |
| sqlglot_normalize        | 126 ms                                                       | 117 ms: 1.08x faster                                                |
| deepcopy                 | 399 us                                                       | 376 us: 1.06x faster                                                |
| sqlglot_parse            | 1.53 ms                                                      | 1.44 ms: 1.06x faster                                               |
| richards_super           | 61.0 ms                                                      | 57.6 ms: 1.06x faster                                               |
| xml_etree_parse          | 158 ms                                                       | 149 ms: 1.06x faster                                                |
| async_tree_cpu_io_mixed  | 749 ms                                                       | 712 ms: 1.05x faster                                                |
| logging_format           | 8.11 us                                                      | 7.73 us: 1.05x faster                                               |
| mdp                      | 2.75 sec                                                     | 2.62 sec: 1.05x faster                                              |
| deepcopy_reduce          | 3.51 us                                                      | 3.38 us: 1.04x faster                                               |
| sqlglot_transpile        | 1.92 ms                                                      | 1.86 ms: 1.03x faster                                               |
| logging_simple           | 7.19 us                                                      | 6.97 us: 1.03x faster                                               |
| bench_thread_pool        | 1.01 ms                                                      | 983 us: 1.03x faster                                                |
| coverage                 | 84.8 ms                                                      | 82.6 ms: 1.03x faster                                               |
| logging_silent           | 101 ns                                                       | 98.8 ns: 1.02x faster                                               |
| unpickle_pure_python     | 241 us                                                       | 237 us: 1.02x faster                                                |
| nqueens                  | 103 ms                                                       | 102 ms: 1.01x faster                                                |
| pickle_pure_python       | 319 us                                                       | 317 us: 1.01x faster                                                |
| sqlglot_optimize         | 59.8 ms                                                      | 59.6 ms: 1.00x faster                                               |
| crypto_pyaes             | 83.4 ms                                                      | 83.9 ms: 1.01x slower                                               |
| regex_compile            | 158 ms                                                       | 159 ms: 1.01x slower                                                |
| pycparser                | 1.32 sec                                                     | 1.34 sec: 1.01x slower                                              |
| dulwich_log              | 68.4 ms                                                      | 69.5 ms: 1.01x slower                                               |
| deepcopy_memo            | 38.8 us                                                      | 39.5 us: 1.02x slower                                               |
| tornado_http             | 122 ms                                                       | 124 ms: 1.02x slower                                                |
| docutils                 | 2.86 sec                                                     | 2.93 sec: 1.02x slower                                              |
| xml_etree_iterparse      | 104 ms                                                       | 107 ms: 1.03x slower                                                |
| unpickle_list            | 4.53 us                                                      | 4.68 us: 1.03x slower                                               |
| regex_effbot             | 3.50 ms                                                      | 3.62 ms: 1.03x slower                                               |
| pickle                   | 9.64 us                                                      | 10.0 us: 1.04x slower                                               |
| xml_etree_process        | 56.5 ms                                                      | 58.8 ms: 1.04x slower                                               |
| meteor_contest           | 131 ms                                                       | 137 ms: 1.05x slower                                                |
| pidigits                 | 251 ms                                                       | 265 ms: 1.06x slower                                                |
| pathlib                  | 19.1 ms                                                      | 20.2 ms: 1.06x slower                                               |
| unpickle                 | 13.4 us                                                      | 14.3 us: 1.06x slower                                               |
| pickle_dict              | 30.8 us                                                      | 32.8 us: 1.07x slower                                               |
| xml_etree_generate       | 80.5 ms                                                      | 85.9 ms: 1.07x slower                                               |
| richards                 | 48.3 ms                                                      | 51.6 ms: 1.07x slower                                               |
| go                       | 164 ms                                                       | 175 ms: 1.07x slower                                                |
| scimark_monte_carlo      | 68.2 ms                                                      | 73.3 ms: 1.07x slower                                               |
| sqlite_synth             | 2.50 us                                                      | 2.70 us: 1.08x slower                                               |
| regex_dna                | 227 ms                                                       | 247 ms: 1.09x slower                                                |
| unpack_sequence          | 45.6 ns                                                      | 49.9 ns: 1.09x slower                                               |
| tomli_loads              | 2.26 sec                                                     | 2.48 sec: 1.10x slower                                              |
| mako                     | 11.0 ms                                                      | 12.1 ms: 1.10x slower                                               |
| nbody                    | 90.7 ms                                                      | 100 ms: 1.10x slower                                                |
| regex_v8                 | 23.9 ms                                                      | 26.6 ms: 1.11x slower                                               |
| pprint_pformat           | 1.63 sec                                                     | 1.81 sec: 1.11x slower                                              |
| python_startup_no_site   | 7.76 ms                                                      | 8.69 ms: 1.12x slower                                               |
| pprint_safe_repr         | 784 ms                                                       | 885 ms: 1.13x slower                                                |
| pickle_list              | 3.83 us                                                      | 4.33 us: 1.13x slower                                               |
| scimark_sparse_mat_mult  | 4.05 ms                                                      | 4.59 ms: 1.13x slower                                               |
| comprehensions           | 24.6 us                                                      | 28.5 us: 1.16x slower                                               |
| python_startup           | 10.8 ms                                                      | 12.6 ms: 1.17x slower                                               |
| pyflate                  | 449 ms                                                       | 534 ms: 1.19x slower                                                |
| float                    | 74.2 ms                                                      | 88.8 ms: 1.20x slower                                               |
| deltablue                | 4.00 ms                                                      | 4.80 ms: 1.20x slower                                               |
| telco                    | 6.86 ms                                                      | 8.32 ms: 1.21x slower                                               |
| hexiom                   | 7.13 ms                                                      | 9.00 ms: 1.26x slower                                               |
| scimark_fft              | 285 ms                                                       | 361 ms: 1.27x slower                                                |
| scimark_sor              | 111 ms                                                       | 148 ms: 1.33x slower                                                |
| async_generators         | 316 ms                                                       | 422 ms: 1.34x slower                                                |
| Geometric mean           | (ref)                                                        | 1.01x faster                                                        |

Benchmark hidden because not significant (4): create_gc_cycles, spectral_norm, fannkuch, bench_mp_pool
Ignored benchmarks (18) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509.json: 2to3, aiohttp, chameleon, dask, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 84.15% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
