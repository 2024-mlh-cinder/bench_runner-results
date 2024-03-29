
# Results vs. 3.11.0

- fork: python
- ref: main
- machine: linux-x86_64
- commit hash: 8e56d55
- commit date: 2023-10-07
- overall geometric mean: 1.06x faster
- HPT reliability: 97.48%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

Benchmark hidden because not significant (2): docutils, tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231007-pythonperf2-x86_64-python-main-3.13.0a0-8e56d55 |
|----------------|:------------------------------------------------------------:|:-----------------------------------------------------------:|
| nbody          | 90.7 ms                                                      | 85.1 ms: 1.07x faster                                       |
| pidigits       | 251 ms                                                       | 265 ms: 1.05x slower                                        |
| float          | 74.2 ms                                                      | 80.7 ms: 1.09x slower                                       |
| Geometric mean | (ref)                                                        | 1.02x slower                                                |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231007-pythonperf2-x86_64-python-main-3.13.0a0-8e56d55 |
|----------------|:------------------------------------------------------------:|:-----------------------------------------------------------:|
| regex_compile  | 158 ms                                                       | 148 ms: 1.06x faster                                        |
| regex_effbot   | 3.50 ms                                                      | 3.44 ms: 1.02x faster                                       |
| regex_dna      | 227 ms                                                       | 235 ms: 1.04x slower                                        |
| regex_v8       | 23.9 ms                                                      | 25.1 ms: 1.05x slower                                       |
| Geometric mean | (ref)                                                        | 1.00x slower                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231007-pythonperf2-x86_64-python-main-3.13.0a0-8e56d55 |
|----------------------|:------------------------------------------------------------:|:-----------------------------------------------------------:|
| json_dumps           | 13.4 ms                                                      | 10.5 ms: 1.28x faster                                       |
| json_loads           | 28.7 us                                                      | 25.0 us: 1.15x faster                                       |
| unpickle_pure_python | 241 us                                                       | 226 us: 1.07x faster                                        |
| xml_etree_parse      | 158 ms                                                       | 149 ms: 1.06x faster                                        |
| pickle_pure_python   | 319 us                                                       | 311 us: 1.03x faster                                        |
| xml_etree_iterparse  | 104 ms                                                       | 107 ms: 1.03x slower                                        |
| pickle_dict          | 30.8 us                                                      | 31.6 us: 1.03x slower                                       |
| tomli_loads          | 2.26 sec                                                     | 2.32 sec: 1.03x slower                                      |
| unpickle_list        | 4.53 us                                                      | 4.68 us: 1.03x slower                                       |
| xml_etree_process    | 56.5 ms                                                      | 59.1 ms: 1.05x slower                                       |
| unpickle             | 13.4 us                                                      | 14.3 us: 1.06x slower                                       |
| pickle               | 9.64 us                                                      | 10.3 us: 1.07x slower                                       |
| xml_etree_generate   | 80.5 ms                                                      | 86.3 ms: 1.07x slower                                       |
| pickle_list          | 3.83 us                                                      | 4.39 us: 1.15x slower                                       |
| Geometric mean       | (ref)                                                        | 1.00x faster                                                |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231007-pythonperf2-x86_64-python-main-3.13.0a0-8e56d55 |
|------------------------|:------------------------------------------------------------:|:-----------------------------------------------------------:|
| python_startup_no_site | 7.76 ms                                                      | 8.67 ms: 1.12x slower                                       |
| python_startup         | 10.8 ms                                                      | 12.6 ms: 1.17x slower                                       |
| Geometric mean         | (ref)                                                        | 1.14x slower                                                |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231007-pythonperf2-x86_64-python-main-3.13.0a0-8e56d55 |
|-----------|:------------------------------------------------------------:|:-----------------------------------------------------------:|
| mako      | 11.0 ms                                                      | 10.4 ms: 1.05x faster                                       |

All benchmarks:
===============

| Benchmark                | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231007-pythonperf2-x86_64-python-main-3.13.0a0-8e56d55 |
|--------------------------|:------------------------------------------------------------:|:-----------------------------------------------------------:|
| typing_runtime_protocols | 523 us                                                       | 150 us: 3.49x faster                                        |
| asyncio_tcp              | 753 ms                                                       | 366 ms: 2.06x faster                                        |
| asyncio_tcp_ssl          | 3.08 sec                                                     | 1.58 sec: 1.95x faster                                      |
| generators               | 56.0 ms                                                      | 34.8 ms: 1.61x faster                                       |
| chaos                    | 80.9 ms                                                      | 61.1 ms: 1.32x faster                                       |
| json_dumps               | 13.4 ms                                                      | 10.5 ms: 1.28x faster                                       |
| mypy2                    | 451 ms                                                       | 370 ms: 1.22x faster                                        |
| async_tree_none          | 519 ms                                                       | 435 ms: 1.19x faster                                        |
| coroutines               | 27.6 ms                                                      | 23.3 ms: 1.18x faster                                       |
| raytrace                 | 317 ms                                                       | 268 ms: 1.18x faster                                        |
| nqueens                  | 103 ms                                                       | 87.9 ms: 1.17x faster                                       |
| json_loads               | 28.7 us                                                      | 25.0 us: 1.15x faster                                       |
| async_tree_memoization   | 630 ms                                                       | 549 ms: 1.15x faster                                        |
| crypto_pyaes             | 83.4 ms                                                      | 72.9 ms: 1.14x faster                                       |
| scimark_lu               | 115 ms                                                       | 101 ms: 1.14x faster                                        |
| comprehensions           | 24.6 us                                                      | 22.1 us: 1.11x faster                                       |
| fannkuch                 | 429 ms                                                       | 385 ms: 1.11x faster                                        |
| deltablue                | 4.00 ms                                                      | 3.61 ms: 1.11x faster                                       |
| json                     | 5.65 ms                                                      | 5.14 ms: 1.10x faster                                       |
| hexiom                   | 7.13 ms                                                      | 6.50 ms: 1.10x faster                                       |
| sqlglot_normalize        | 126 ms                                                       | 115 ms: 1.10x faster                                        |
| mdp                      | 2.75 sec                                                     | 2.51 sec: 1.09x faster                                      |
| deepcopy                 | 399 us                                                       | 368 us: 1.08x faster                                        |
| async_tree_io            | 1.17 sec                                                     | 1.08 sec: 1.08x faster                                      |
| sqlglot_parse            | 1.53 ms                                                      | 1.42 ms: 1.08x faster                                       |
| logging_format           | 8.11 us                                                      | 7.56 us: 1.07x faster                                       |
| async_tree_cpu_io_mixed  | 749 ms                                                       | 700 ms: 1.07x faster                                        |
| unpickle_pure_python     | 241 us                                                       | 226 us: 1.07x faster                                        |
| nbody                    | 90.7 ms                                                      | 85.1 ms: 1.07x faster                                       |
| regex_compile            | 158 ms                                                       | 148 ms: 1.06x faster                                        |
| xml_etree_parse          | 158 ms                                                       | 149 ms: 1.06x faster                                        |
| mako                     | 11.0 ms                                                      | 10.4 ms: 1.05x faster                                       |
| deepcopy_reduce          | 3.51 us                                                      | 3.34 us: 1.05x faster                                       |
| bench_thread_pool        | 1.01 ms                                                      | 962 us: 1.05x faster                                        |
| deepcopy_memo            | 38.8 us                                                      | 36.9 us: 1.05x faster                                       |
| sqlglot_transpile        | 1.92 ms                                                      | 1.83 ms: 1.05x faster                                       |
| logging_simple           | 7.19 us                                                      | 6.88 us: 1.05x faster                                       |
| logging_silent           | 101 ns                                                       | 96.9 ns: 1.04x faster                                       |
| pycparser                | 1.32 sec                                                     | 1.28 sec: 1.03x faster                                      |
| gc_traversal             | 3.85 ms                                                      | 3.74 ms: 1.03x faster                                       |
| sqlglot_optimize         | 59.8 ms                                                      | 58.2 ms: 1.03x faster                                       |
| pickle_pure_python       | 319 us                                                       | 311 us: 1.03x faster                                        |
| spectral_norm            | 93.3 ms                                                      | 91.0 ms: 1.03x faster                                       |
| coverage                 | 84.8 ms                                                      | 82.8 ms: 1.02x faster                                       |
| scimark_monte_carlo      | 68.2 ms                                                      | 66.8 ms: 1.02x faster                                       |
| unpack_sequence          | 45.6 ns                                                      | 44.8 ns: 1.02x faster                                       |
| regex_effbot             | 3.50 ms                                                      | 3.44 ms: 1.02x faster                                       |
| richards_super           | 61.0 ms                                                      | 60.2 ms: 1.01x faster                                       |
| scimark_sparse_mat_mult  | 4.05 ms                                                      | 4.00 ms: 1.01x faster                                       |
| meteor_contest           | 131 ms                                                       | 132 ms: 1.01x slower                                        |
| pprint_pformat           | 1.63 sec                                                     | 1.65 sec: 1.01x slower                                      |
| dulwich_log              | 68.4 ms                                                      | 69.4 ms: 1.01x slower                                       |
| xml_etree_iterparse      | 104 ms                                                       | 107 ms: 1.03x slower                                        |
| pickle_dict              | 30.8 us                                                      | 31.6 us: 1.03x slower                                       |
| tomli_loads              | 2.26 sec                                                     | 2.32 sec: 1.03x slower                                      |
| pathlib                  | 19.1 ms                                                      | 19.6 ms: 1.03x slower                                       |
| pprint_safe_repr         | 784 ms                                                       | 808 ms: 1.03x slower                                        |
| unpickle_list            | 4.53 us                                                      | 4.68 us: 1.03x slower                                       |
| regex_dna                | 227 ms                                                       | 235 ms: 1.04x slower                                        |
| create_gc_cycles         | 1.61 ms                                                      | 1.67 ms: 1.04x slower                                       |
| scimark_fft              | 285 ms                                                       | 296 ms: 1.04x slower                                        |
| go                       | 164 ms                                                       | 171 ms: 1.04x slower                                        |
| xml_etree_process        | 56.5 ms                                                      | 59.1 ms: 1.05x slower                                       |
| regex_v8                 | 23.9 ms                                                      | 25.1 ms: 1.05x slower                                       |
| pidigits                 | 251 ms                                                       | 265 ms: 1.05x slower                                        |
| unpickle                 | 13.4 us                                                      | 14.3 us: 1.06x slower                                       |
| pickle                   | 9.64 us                                                      | 10.3 us: 1.07x slower                                       |
| xml_etree_generate       | 80.5 ms                                                      | 86.3 ms: 1.07x slower                                       |
| sqlite_synth             | 2.50 us                                                      | 2.70 us: 1.08x slower                                       |
| float                    | 74.2 ms                                                      | 80.7 ms: 1.09x slower                                       |
| python_startup_no_site   | 7.76 ms                                                      | 8.67 ms: 1.12x slower                                       |
| richards                 | 48.3 ms                                                      | 54.0 ms: 1.12x slower                                       |
| pyflate                  | 449 ms                                                       | 514 ms: 1.15x slower                                        |
| pickle_list              | 3.83 us                                                      | 4.39 us: 1.15x slower                                       |
| python_startup           | 10.8 ms                                                      | 12.6 ms: 1.17x slower                                       |
| telco                    | 6.86 ms                                                      | 8.08 ms: 1.18x slower                                       |
| async_generators         | 316 ms                                                       | 404 ms: 1.28x slower                                        |
| scimark_sor              | 111 ms                                                       | 146 ms: 1.31x slower                                        |
| Geometric mean           | (ref)                                                        | 1.06x faster                                                |

Benchmark hidden because not significant (3): bench_mp_pool, docutils, tornado_http
Ignored benchmarks (18) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509.json: 2to3, aiohttp, chameleon, dask, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 97.48% likely to be faster
- 90% likely to have a speedup of 1.01x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
