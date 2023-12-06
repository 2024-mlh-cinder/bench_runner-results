
# Results vs. 3.11.0

- fork: python
- ref: deea7c82682848b2a0db
- machine: linux-x86_64
- commit hash: deea7c8
- commit date: 2023-09-05
- overall geometric mean: 1.05x faster
- HPT reliability: 96.89%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230905-pythonperf2-x86_64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| docutils       | 2.86 sec                                                     | 2.88 sec: 1.01x slower                                                      |
| Geometric mean | (ref)                                                        | 1.00x slower                                                                |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230905-pythonperf2-x86_64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| nbody          | 90.7 ms                                                      | 87.5 ms: 1.04x faster                                                       |
| pidigits       | 251 ms                                                       | 264 ms: 1.05x slower                                                        |
| float          | 74.2 ms                                                      | 80.2 ms: 1.08x slower                                                       |
| Geometric mean | (ref)                                                        | 1.03x slower                                                                |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230905-pythonperf2-x86_64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_compile  | 158 ms                                                       | 147 ms: 1.07x faster                                                        |
| regex_effbot   | 3.50 ms                                                      | 3.48 ms: 1.01x faster                                                       |
| regex_dna      | 227 ms                                                       | 238 ms: 1.05x slower                                                        |
| regex_v8       | 23.9 ms                                                      | 25.6 ms: 1.07x slower                                                       |
| Geometric mean | (ref)                                                        | 1.01x slower                                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230905-pythonperf2-x86_64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 |
|----------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| json_dumps           | 13.4 ms                                                      | 10.5 ms: 1.27x faster                                                       |
| json_loads           | 28.7 us                                                      | 24.9 us: 1.15x faster                                                       |
| xml_etree_parse      | 158 ms                                                       | 147 ms: 1.07x faster                                                        |
| unpickle_pure_python | 241 us                                                       | 230 us: 1.05x faster                                                        |
| tomli_loads          | 2.26 sec                                                     | 2.20 sec: 1.03x faster                                                      |
| pickle_pure_python   | 319 us                                                       | 313 us: 1.02x faster                                                        |
| xml_etree_process    | 56.5 ms                                                      | 58.7 ms: 1.04x slower                                                       |
| pickle_dict          | 30.8 us                                                      | 32.1 us: 1.04x slower                                                       |
| pickle               | 9.64 us                                                      | 10.1 us: 1.04x slower                                                       |
| xml_etree_generate   | 80.5 ms                                                      | 85.7 ms: 1.06x slower                                                       |
| unpickle             | 13.4 us                                                      | 14.4 us: 1.07x slower                                                       |
| pickle_list          | 3.83 us                                                      | 4.31 us: 1.13x slower                                                       |
| Geometric mean       | (ref)                                                        | 1.01x faster                                                                |

Benchmark hidden because not significant (2): xml_etree_iterparse, unpickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230905-pythonperf2-x86_64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 |
|------------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| python_startup         | 10.8 ms                                                      | 11.9 ms: 1.10x slower                                                       |
| python_startup_no_site | 7.76 ms                                                      | 8.84 ms: 1.14x slower                                                       |
| Geometric mean         | (ref)                                                        | 1.12x slower                                                                |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230905-pythonperf2-x86_64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 |
|-----------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| mako      | 11.0 ms                                                      | 10.2 ms: 1.07x faster                                                       |

All benchmarks:
===============

| Benchmark                | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230905-pythonperf2-x86_64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 |
|--------------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| typing_runtime_protocols | 523 us                                                       | 148 us: 3.54x faster                                                        |
| asyncio_tcp              | 753 ms                                                       | 369 ms: 2.04x faster                                                        |
| asyncio_tcp_ssl          | 3.08 sec                                                     | 1.58 sec: 1.95x faster                                                      |
| generators               | 56.0 ms                                                      | 35.0 ms: 1.60x faster                                                       |
| chaos                    | 80.9 ms                                                      | 61.5 ms: 1.31x faster                                                       |
| json_dumps               | 13.4 ms                                                      | 10.5 ms: 1.27x faster                                                       |
| mypy2                    | 451 ms                                                       | 373 ms: 1.21x faster                                                        |
| coroutines               | 27.6 ms                                                      | 23.2 ms: 1.19x faster                                                       |
| async_tree_none          | 519 ms                                                       | 438 ms: 1.19x faster                                                        |
| crypto_pyaes             | 83.4 ms                                                      | 71.3 ms: 1.17x faster                                                       |
| json_loads               | 28.7 us                                                      | 24.9 us: 1.15x faster                                                       |
| nqueens                  | 103 ms                                                       | 89.5 ms: 1.15x faster                                                       |
| scimark_lu               | 115 ms                                                       | 100 ms: 1.14x faster                                                        |
| async_tree_memoization   | 630 ms                                                       | 552 ms: 1.14x faster                                                        |
| comprehensions           | 24.6 us                                                      | 21.9 us: 1.12x faster                                                       |
| raytrace                 | 317 ms                                                       | 282 ms: 1.12x faster                                                        |
| hexiom                   | 7.13 ms                                                      | 6.45 ms: 1.11x faster                                                       |
| json                     | 5.65 ms                                                      | 5.13 ms: 1.10x faster                                                       |
| fannkuch                 | 429 ms                                                       | 389 ms: 1.10x faster                                                        |
| gc_traversal             | 3.85 ms                                                      | 3.53 ms: 1.09x faster                                                       |
| sqlglot_parse            | 1.53 ms                                                      | 1.41 ms: 1.08x faster                                                       |
| async_tree_io            | 1.17 sec                                                     | 1.08 sec: 1.08x faster                                                      |
| sqlglot_normalize        | 126 ms                                                       | 116 ms: 1.08x faster                                                        |
| xml_etree_parse          | 158 ms                                                       | 147 ms: 1.07x faster                                                        |
| deltablue                | 4.00 ms                                                      | 3.72 ms: 1.07x faster                                                       |
| mako                     | 11.0 ms                                                      | 10.2 ms: 1.07x faster                                                       |
| regex_compile            | 158 ms                                                       | 147 ms: 1.07x faster                                                        |
| mdp                      | 2.75 sec                                                     | 2.57 sec: 1.07x faster                                                      |
| deepcopy                 | 399 us                                                       | 374 us: 1.07x faster                                                        |
| async_tree_cpu_io_mixed  | 749 ms                                                       | 704 ms: 1.06x faster                                                        |
| logging_format           | 8.11 us                                                      | 7.64 us: 1.06x faster                                                       |
| sqlglot_transpile        | 1.92 ms                                                      | 1.81 ms: 1.06x faster                                                       |
| deepcopy_memo            | 38.8 us                                                      | 36.9 us: 1.05x faster                                                       |
| unpickle_pure_python     | 241 us                                                       | 230 us: 1.05x faster                                                        |
| logging_simple           | 7.19 us                                                      | 6.90 us: 1.04x faster                                                       |
| bench_thread_pool        | 1.01 ms                                                      | 974 us: 1.04x faster                                                        |
| deepcopy_reduce          | 3.51 us                                                      | 3.39 us: 1.04x faster                                                       |
| nbody                    | 90.7 ms                                                      | 87.5 ms: 1.04x faster                                                       |
| tomli_loads              | 2.26 sec                                                     | 2.20 sec: 1.03x faster                                                      |
| spectral_norm            | 93.3 ms                                                      | 91.1 ms: 1.02x faster                                                       |
| meteor_contest           | 131 ms                                                       | 128 ms: 1.02x faster                                                        |
| pickle_pure_python       | 319 us                                                       | 313 us: 1.02x faster                                                        |
| sqlglot_optimize         | 59.8 ms                                                      | 59.1 ms: 1.01x faster                                                       |
| pycparser                | 1.32 sec                                                     | 1.31 sec: 1.01x faster                                                      |
| coverage                 | 84.8 ms                                                      | 83.9 ms: 1.01x faster                                                       |
| scimark_monte_carlo      | 68.2 ms                                                      | 67.6 ms: 1.01x faster                                                       |
| logging_silent           | 101 ns                                                       | 100 ns: 1.01x faster                                                        |
| scimark_sparse_mat_mult  | 4.05 ms                                                      | 4.02 ms: 1.01x faster                                                       |
| regex_effbot             | 3.50 ms                                                      | 3.48 ms: 1.01x faster                                                       |
| docutils                 | 2.86 sec                                                     | 2.88 sec: 1.01x slower                                                      |
| richards_super           | 61.0 ms                                                      | 61.7 ms: 1.01x slower                                                       |
| dulwich_log              | 68.4 ms                                                      | 69.4 ms: 1.01x slower                                                       |
| unpack_sequence          | 45.6 ns                                                      | 46.6 ns: 1.02x slower                                                       |
| pprint_pformat           | 1.63 sec                                                     | 1.68 sec: 1.03x slower                                                      |
| xml_etree_process        | 56.5 ms                                                      | 58.7 ms: 1.04x slower                                                       |
| bench_mp_pool            | 4.62 ms                                                      | 4.81 ms: 1.04x slower                                                       |
| pickle_dict              | 30.8 us                                                      | 32.1 us: 1.04x slower                                                       |
| pickle                   | 9.64 us                                                      | 10.1 us: 1.04x slower                                                       |
| scimark_fft              | 285 ms                                                       | 298 ms: 1.05x slower                                                        |
| go                       | 164 ms                                                       | 172 ms: 1.05x slower                                                        |
| regex_dna                | 227 ms                                                       | 238 ms: 1.05x slower                                                        |
| pidigits                 | 251 ms                                                       | 264 ms: 1.05x slower                                                        |
| pprint_safe_repr         | 784 ms                                                       | 826 ms: 1.05x slower                                                        |
| pathlib                  | 19.1 ms                                                      | 20.2 ms: 1.06x slower                                                       |
| xml_etree_generate       | 80.5 ms                                                      | 85.7 ms: 1.06x slower                                                       |
| regex_v8                 | 23.9 ms                                                      | 25.6 ms: 1.07x slower                                                       |
| unpickle                 | 13.4 us                                                      | 14.4 us: 1.07x slower                                                       |
| float                    | 74.2 ms                                                      | 80.2 ms: 1.08x slower                                                       |
| sqlite_synth             | 2.50 us                                                      | 2.72 us: 1.09x slower                                                       |
| python_startup           | 10.8 ms                                                      | 11.9 ms: 1.10x slower                                                       |
| pickle_list              | 3.83 us                                                      | 4.31 us: 1.13x slower                                                       |
| python_startup_no_site   | 7.76 ms                                                      | 8.84 ms: 1.14x slower                                                       |
| richards                 | 48.3 ms                                                      | 55.4 ms: 1.15x slower                                                       |
| pyflate                  | 449 ms                                                       | 515 ms: 1.15x slower                                                        |
| telco                    | 6.86 ms                                                      | 8.05 ms: 1.17x slower                                                       |
| async_generators         | 316 ms                                                       | 399 ms: 1.26x slower                                                        |
| scimark_sor              | 111 ms                                                       | 148 ms: 1.33x slower                                                        |
| dask                     | 410 ms                                                       | 591 ms: 1.44x slower                                                        |
| Geometric mean           | (ref)                                                        | 1.05x faster                                                                |

Benchmark hidden because not significant (4): tornado_http, create_gc_cycles, xml_etree_iterparse, unpickle_list
Ignored benchmarks (17) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509.json: 2to3, aiohttp, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 96.89% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
