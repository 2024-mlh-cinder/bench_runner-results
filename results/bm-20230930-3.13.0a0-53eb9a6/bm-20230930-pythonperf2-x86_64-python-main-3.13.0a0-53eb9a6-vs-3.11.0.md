
# Results vs. 3.11.0

- fork: python
- ref: main
- machine: linux-x86_64
- commit hash: 53eb9a6
- commit date: 2023-09-30
- overall geometric mean: 1.05x faster
- HPT reliability: 93.96%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230930-pythonperf2-x86_64-python-main-3.13.0a0-53eb9a6 |
|----------------|:------------------------------------------------------------:|:-----------------------------------------------------------:|
| tornado_http   | 122 ms                                                       | 119 ms: 1.02x faster                                        |
| Geometric mean | (ref)                                                        | 1.01x faster                                                |

Benchmark hidden because not significant (1): docutils

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230930-pythonperf2-x86_64-python-main-3.13.0a0-53eb9a6 |
|----------------|:------------------------------------------------------------:|:-----------------------------------------------------------:|
| nbody          | 90.7 ms                                                      | 88.7 ms: 1.02x faster                                       |
| pidigits       | 251 ms                                                       | 264 ms: 1.05x slower                                        |
| float          | 74.2 ms                                                      | 82.3 ms: 1.11x slower                                       |
| Geometric mean | (ref)                                                        | 1.05x slower                                                |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230930-pythonperf2-x86_64-python-main-3.13.0a0-53eb9a6 |
|----------------|:------------------------------------------------------------:|:-----------------------------------------------------------:|
| regex_compile  | 158 ms                                                       | 149 ms: 1.05x faster                                        |
| regex_effbot   | 3.50 ms                                                      | 3.45 ms: 1.02x faster                                       |
| regex_v8       | 23.9 ms                                                      | 25.0 ms: 1.05x slower                                       |
| regex_dna      | 227 ms                                                       | 247 ms: 1.09x slower                                        |
| Geometric mean | (ref)                                                        | 1.02x slower                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230930-pythonperf2-x86_64-python-main-3.13.0a0-53eb9a6 |
|----------------------|:------------------------------------------------------------:|:-----------------------------------------------------------:|
| json_dumps           | 13.4 ms                                                      | 10.6 ms: 1.27x faster                                       |
| json_loads           | 28.7 us                                                      | 24.9 us: 1.15x faster                                       |
| unpickle_pure_python | 241 us                                                       | 218 us: 1.11x faster                                        |
| xml_etree_parse      | 158 ms                                                       | 149 ms: 1.06x faster                                        |
| pickle_pure_python   | 319 us                                                       | 321 us: 1.00x slower                                        |
| xml_etree_iterparse  | 104 ms                                                       | 105 ms: 1.01x slower                                        |
| tomli_loads          | 2.26 sec                                                     | 2.31 sec: 1.02x slower                                      |
| unpickle_list        | 4.53 us                                                      | 4.70 us: 1.04x slower                                       |
| pickle               | 9.64 us                                                      | 10.0 us: 1.04x slower                                       |
| xml_etree_process    | 56.5 ms                                                      | 58.8 ms: 1.04x slower                                       |
| unpickle             | 13.4 us                                                      | 14.2 us: 1.06x slower                                       |
| pickle_dict          | 30.8 us                                                      | 32.6 us: 1.06x slower                                       |
| xml_etree_generate   | 80.5 ms                                                      | 85.8 ms: 1.07x slower                                       |
| pickle_list          | 3.83 us                                                      | 4.30 us: 1.12x slower                                       |
| Geometric mean       | (ref)                                                        | 1.01x faster                                                |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230930-pythonperf2-x86_64-python-main-3.13.0a0-53eb9a6 |
|------------------------|:------------------------------------------------------------:|:-----------------------------------------------------------:|
| python_startup_no_site | 7.76 ms                                                      | 8.67 ms: 1.12x slower                                       |
| python_startup         | 10.8 ms                                                      | 12.6 ms: 1.17x slower                                       |
| Geometric mean         | (ref)                                                        | 1.15x slower                                                |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230930-pythonperf2-x86_64-python-main-3.13.0a0-53eb9a6 |
|-----------|:------------------------------------------------------------:|:-----------------------------------------------------------:|
| mako      | 11.0 ms                                                      | 10.3 ms: 1.07x faster                                       |

All benchmarks:
===============

| Benchmark                | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230930-pythonperf2-x86_64-python-main-3.13.0a0-53eb9a6 |
|--------------------------|:------------------------------------------------------------:|:-----------------------------------------------------------:|
| typing_runtime_protocols | 523 us                                                       | 152 us: 3.44x faster                                        |
| asyncio_tcp              | 753 ms                                                       | 369 ms: 2.04x faster                                        |
| asyncio_tcp_ssl          | 3.08 sec                                                     | 1.58 sec: 1.95x faster                                      |
| generators               | 56.0 ms                                                      | 35.3 ms: 1.59x faster                                       |
| json_dumps               | 13.4 ms                                                      | 10.6 ms: 1.27x faster                                       |
| chaos                    | 80.9 ms                                                      | 63.8 ms: 1.27x faster                                       |
| async_tree_none          | 519 ms                                                       | 438 ms: 1.19x faster                                        |
| coroutines               | 27.6 ms                                                      | 23.3 ms: 1.18x faster                                       |
| crypto_pyaes             | 83.4 ms                                                      | 71.4 ms: 1.17x faster                                       |
| scimark_lu               | 115 ms                                                       | 99.3 ms: 1.15x faster                                       |
| json_loads               | 28.7 us                                                      | 24.9 us: 1.15x faster                                       |
| nqueens                  | 103 ms                                                       | 89.4 ms: 1.15x faster                                       |
| async_tree_memoization   | 630 ms                                                       | 555 ms: 1.14x faster                                        |
| raytrace                 | 317 ms                                                       | 279 ms: 1.13x faster                                        |
| comprehensions           | 24.6 us                                                      | 22.0 us: 1.12x faster                                       |
| unpickle_pure_python     | 241 us                                                       | 218 us: 1.11x faster                                        |
| json                     | 5.65 ms                                                      | 5.14 ms: 1.10x faster                                       |
| hexiom                   | 7.13 ms                                                      | 6.49 ms: 1.10x faster                                       |
| mdp                      | 2.75 sec                                                     | 2.51 sec: 1.10x faster                                      |
| deltablue                | 4.00 ms                                                      | 3.65 ms: 1.09x faster                                       |
| sqlglot_normalize        | 126 ms                                                       | 115 ms: 1.09x faster                                        |
| sqlglot_parse            | 1.53 ms                                                      | 1.41 ms: 1.09x faster                                       |
| fannkuch                 | 429 ms                                                       | 396 ms: 1.08x faster                                        |
| async_tree_io            | 1.17 sec                                                     | 1.09 sec: 1.07x faster                                      |
| mako                     | 11.0 ms                                                      | 10.3 ms: 1.07x faster                                       |
| bench_thread_pool        | 1.01 ms                                                      | 951 us: 1.06x faster                                        |
| async_tree_cpu_io_mixed  | 749 ms                                                       | 705 ms: 1.06x faster                                        |
| xml_etree_parse          | 158 ms                                                       | 149 ms: 1.06x faster                                        |
| sqlglot_transpile        | 1.92 ms                                                      | 1.82 ms: 1.06x faster                                       |
| regex_compile            | 158 ms                                                       | 149 ms: 1.05x faster                                        |
| logging_silent           | 101 ns                                                       | 95.9 ns: 1.05x faster                                       |
| logging_format           | 8.11 us                                                      | 7.75 us: 1.05x faster                                       |
| logging_simple           | 7.19 us                                                      | 6.97 us: 1.03x faster                                       |
| sqlglot_optimize         | 59.8 ms                                                      | 58.2 ms: 1.03x faster                                       |
| deepcopy_reduce          | 3.51 us                                                      | 3.42 us: 1.03x faster                                       |
| scimark_monte_carlo      | 68.2 ms                                                      | 66.6 ms: 1.02x faster                                       |
| coverage                 | 84.8 ms                                                      | 82.8 ms: 1.02x faster                                       |
| tornado_http             | 122 ms                                                       | 119 ms: 1.02x faster                                        |
| nbody                    | 90.7 ms                                                      | 88.7 ms: 1.02x faster                                       |
| deepcopy_memo            | 38.8 us                                                      | 38.0 us: 1.02x faster                                       |
| deepcopy                 | 399 us                                                       | 392 us: 1.02x faster                                        |
| regex_effbot             | 3.50 ms                                                      | 3.45 ms: 1.02x faster                                       |
| spectral_norm            | 93.3 ms                                                      | 92.4 ms: 1.01x faster                                       |
| meteor_contest           | 131 ms                                                       | 130 ms: 1.01x faster                                        |
| pickle_pure_python       | 319 us                                                       | 321 us: 1.00x slower                                        |
| dulwich_log              | 68.4 ms                                                      | 68.9 ms: 1.01x slower                                       |
| xml_etree_iterparse      | 104 ms                                                       | 105 ms: 1.01x slower                                        |
| pprint_pformat           | 1.63 sec                                                     | 1.66 sec: 1.02x slower                                      |
| tomli_loads              | 2.26 sec                                                     | 2.31 sec: 1.02x slower                                      |
| go                       | 164 ms                                                       | 167 ms: 1.02x slower                                        |
| pprint_safe_repr         | 784 ms                                                       | 810 ms: 1.03x slower                                        |
| unpickle_list            | 4.53 us                                                      | 4.70 us: 1.04x slower                                       |
| pickle                   | 9.64 us                                                      | 10.0 us: 1.04x slower                                       |
| xml_etree_process        | 56.5 ms                                                      | 58.8 ms: 1.04x slower                                       |
| scimark_sparse_mat_mult  | 4.05 ms                                                      | 4.23 ms: 1.04x slower                                       |
| regex_v8                 | 23.9 ms                                                      | 25.0 ms: 1.05x slower                                       |
| pathlib                  | 19.1 ms                                                      | 20.0 ms: 1.05x slower                                       |
| scimark_fft              | 285 ms                                                       | 299 ms: 1.05x slower                                        |
| pidigits                 | 251 ms                                                       | 264 ms: 1.05x slower                                        |
| unpickle                 | 13.4 us                                                      | 14.2 us: 1.06x slower                                       |
| pickle_dict              | 30.8 us                                                      | 32.6 us: 1.06x slower                                       |
| create_gc_cycles         | 1.61 ms                                                      | 1.71 ms: 1.06x slower                                       |
| sqlite_synth             | 2.50 us                                                      | 2.66 us: 1.07x slower                                       |
| xml_etree_generate       | 80.5 ms                                                      | 85.8 ms: 1.07x slower                                       |
| gc_traversal             | 3.85 ms                                                      | 4.19 ms: 1.09x slower                                       |
| regex_dna                | 227 ms                                                       | 247 ms: 1.09x slower                                        |
| float                    | 74.2 ms                                                      | 82.3 ms: 1.11x slower                                       |
| python_startup_no_site   | 7.76 ms                                                      | 8.67 ms: 1.12x slower                                       |
| pickle_list              | 3.83 us                                                      | 4.30 us: 1.12x slower                                       |
| richards                 | 48.3 ms                                                      | 54.3 ms: 1.12x slower                                       |
| pyflate                  | 449 ms                                                       | 511 ms: 1.14x slower                                        |
| unpack_sequence          | 45.6 ns                                                      | 53.1 ns: 1.16x slower                                       |
| telco                    | 6.86 ms                                                      | 8.03 ms: 1.17x slower                                       |
| python_startup           | 10.8 ms                                                      | 12.6 ms: 1.17x slower                                       |
| async_generators         | 316 ms                                                       | 388 ms: 1.23x slower                                        |
| scimark_sor              | 111 ms                                                       | 150 ms: 1.35x slower                                        |
| Geometric mean           | (ref)                                                        | 1.05x faster                                                |

Benchmark hidden because not significant (5): richards_super, docutils, pycparser, mypy2, bench_mp_pool
Ignored benchmarks (18) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509.json: 2to3, aiohttp, chameleon, dask, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 93.96% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
