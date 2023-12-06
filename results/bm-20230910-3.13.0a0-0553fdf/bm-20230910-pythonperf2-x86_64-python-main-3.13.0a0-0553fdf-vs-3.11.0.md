
# Results vs. 3.11.0

- fork: python
- ref: main
- machine: linux-x86_64
- commit hash: 0553fdf
- commit date: 2023-09-10
- overall geometric mean: 1.04x faster
- HPT reliability: 87.66%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230910-pythonperf2-x86_64-python-main-3.13.0a0-0553fdf |
|----------------|:------------------------------------------------------------:|:-----------------------------------------------------------:|
| docutils       | 2.86 sec                                                     | 2.90 sec: 1.01x slower                                      |
| tornado_http   | 122 ms                                                       | 120 ms: 1.01x faster                                        |
| Geometric mean | (ref)                                                        | 1.00x slower                                                |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230910-pythonperf2-x86_64-python-main-3.13.0a0-0553fdf |
|----------------|:------------------------------------------------------------:|:-----------------------------------------------------------:|
| nbody          | 90.7 ms                                                      | 87.7 ms: 1.03x faster                                       |
| pidigits       | 251 ms                                                       | 264 ms: 1.05x slower                                        |
| float          | 74.2 ms                                                      | 81.1 ms: 1.09x slower                                       |
| Geometric mean | (ref)                                                        | 1.04x slower                                                |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230910-pythonperf2-x86_64-python-main-3.13.0a0-0553fdf |
|----------------|:------------------------------------------------------------:|:-----------------------------------------------------------:|
| regex_compile  | 158 ms                                                       | 148 ms: 1.07x faster                                        |
| regex_effbot   | 3.50 ms                                                      | 3.61 ms: 1.03x slower                                       |
| regex_dna      | 227 ms                                                       | 242 ms: 1.06x slower                                        |
| regex_v8       | 23.9 ms                                                      | 25.6 ms: 1.07x slower                                       |
| Geometric mean | (ref)                                                        | 1.02x slower                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230910-pythonperf2-x86_64-python-main-3.13.0a0-0553fdf |
|----------------------|:------------------------------------------------------------:|:-----------------------------------------------------------:|
| json_dumps           | 13.4 ms                                                      | 10.4 ms: 1.29x faster                                       |
| json_loads           | 28.7 us                                                      | 24.8 us: 1.15x faster                                       |
| xml_etree_parse      | 158 ms                                                       | 148 ms: 1.07x faster                                        |
| unpickle_pure_python | 241 us                                                       | 227 us: 1.06x faster                                        |
| tomli_loads          | 2.26 sec                                                     | 2.18 sec: 1.04x faster                                      |
| pickle_pure_python   | 319 us                                                       | 312 us: 1.02x faster                                        |
| xml_etree_iterparse  | 104 ms                                                       | 106 ms: 1.02x slower                                        |
| unpickle_list        | 4.53 us                                                      | 4.65 us: 1.02x slower                                       |
| xml_etree_process    | 56.5 ms                                                      | 58.9 ms: 1.04x slower                                       |
| pickle_dict          | 30.8 us                                                      | 32.3 us: 1.05x slower                                       |
| pickle               | 9.64 us                                                      | 10.1 us: 1.05x slower                                       |
| xml_etree_generate   | 80.5 ms                                                      | 86.1 ms: 1.07x slower                                       |
| unpickle             | 13.4 us                                                      | 14.9 us: 1.11x slower                                       |
| pickle_list          | 3.83 us                                                      | 4.58 us: 1.20x slower                                       |
| Geometric mean       | (ref)                                                        | 1.00x faster                                                |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230910-pythonperf2-x86_64-python-main-3.13.0a0-0553fdf |
|------------------------|:------------------------------------------------------------:|:-----------------------------------------------------------:|
| python_startup_no_site | 7.76 ms                                                      | 8.67 ms: 1.12x slower                                       |
| python_startup         | 10.8 ms                                                      | 12.6 ms: 1.17x slower                                       |
| Geometric mean         | (ref)                                                        | 1.15x slower                                                |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230910-pythonperf2-x86_64-python-main-3.13.0a0-0553fdf |
|-----------|:------------------------------------------------------------:|:-----------------------------------------------------------:|
| mako      | 11.0 ms                                                      | 10.3 ms: 1.07x faster                                       |

All benchmarks:
===============

| Benchmark                | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230910-pythonperf2-x86_64-python-main-3.13.0a0-0553fdf |
|--------------------------|:------------------------------------------------------------:|:-----------------------------------------------------------:|
| typing_runtime_protocols | 523 us                                                       | 151 us: 3.47x faster                                        |
| asyncio_tcp              | 753 ms                                                       | 370 ms: 2.04x faster                                        |
| asyncio_tcp_ssl          | 3.08 sec                                                     | 1.58 sec: 1.95x faster                                      |
| generators               | 56.0 ms                                                      | 35.4 ms: 1.58x faster                                       |
| chaos                    | 80.9 ms                                                      | 62.0 ms: 1.30x faster                                       |
| json_dumps               | 13.4 ms                                                      | 10.4 ms: 1.29x faster                                       |
| mypy2                    | 451 ms                                                       | 372 ms: 1.21x faster                                        |
| coroutines               | 27.6 ms                                                      | 23.0 ms: 1.20x faster                                       |
| async_tree_none          | 519 ms                                                       | 439 ms: 1.18x faster                                        |
| raytrace                 | 317 ms                                                       | 271 ms: 1.17x faster                                        |
| nqueens                  | 103 ms                                                       | 88.9 ms: 1.16x faster                                       |
| json_loads               | 28.7 us                                                      | 24.8 us: 1.15x faster                                       |
| crypto_pyaes             | 83.4 ms                                                      | 72.8 ms: 1.15x faster                                       |
| async_tree_memoization   | 630 ms                                                       | 552 ms: 1.14x faster                                        |
| scimark_lu               | 115 ms                                                       | 103 ms: 1.12x faster                                        |
| json                     | 5.65 ms                                                      | 5.11 ms: 1.11x faster                                       |
| hexiom                   | 7.13 ms                                                      | 6.46 ms: 1.10x faster                                       |
| comprehensions           | 24.6 us                                                      | 22.3 us: 1.10x faster                                       |
| sqlglot_parse            | 1.53 ms                                                      | 1.40 ms: 1.09x faster                                       |
| async_tree_io            | 1.17 sec                                                     | 1.08 sec: 1.09x faster                                      |
| sqlglot_normalize        | 126 ms                                                       | 116 ms: 1.08x faster                                        |
| logging_format           | 8.11 us                                                      | 7.51 us: 1.08x faster                                       |
| deltablue                | 4.00 ms                                                      | 3.70 ms: 1.08x faster                                       |
| fannkuch                 | 429 ms                                                       | 400 ms: 1.07x faster                                        |
| xml_etree_parse          | 158 ms                                                       | 148 ms: 1.07x faster                                        |
| mdp                      | 2.75 sec                                                     | 2.57 sec: 1.07x faster                                      |
| async_tree_cpu_io_mixed  | 749 ms                                                       | 701 ms: 1.07x faster                                        |
| regex_compile            | 158 ms                                                       | 148 ms: 1.07x faster                                        |
| mako                     | 11.0 ms                                                      | 10.3 ms: 1.07x faster                                       |
| coverage                 | 84.8 ms                                                      | 79.8 ms: 1.06x faster                                       |
| deepcopy                 | 399 us                                                       | 376 us: 1.06x faster                                        |
| unpickle_pure_python     | 241 us                                                       | 227 us: 1.06x faster                                        |
| sqlglot_transpile        | 1.92 ms                                                      | 1.82 ms: 1.06x faster                                       |
| logging_simple           | 7.19 us                                                      | 6.81 us: 1.06x faster                                       |
| deepcopy_reduce          | 3.51 us                                                      | 3.37 us: 1.04x faster                                       |
| tomli_loads              | 2.26 sec                                                     | 2.18 sec: 1.04x faster                                      |
| bench_thread_pool        | 1.01 ms                                                      | 976 us: 1.04x faster                                        |
| nbody                    | 90.7 ms                                                      | 87.7 ms: 1.03x faster                                       |
| sqlglot_optimize         | 59.8 ms                                                      | 58.4 ms: 1.02x faster                                       |
| pickle_pure_python       | 319 us                                                       | 312 us: 1.02x faster                                        |
| deepcopy_memo            | 38.8 us                                                      | 38.1 us: 1.02x faster                                       |
| gc_traversal             | 3.85 ms                                                      | 3.79 ms: 1.02x faster                                       |
| tornado_http             | 122 ms                                                       | 120 ms: 1.01x faster                                        |
| meteor_contest           | 131 ms                                                       | 129 ms: 1.01x faster                                        |
| richards_super           | 61.0 ms                                                      | 60.5 ms: 1.01x faster                                       |
| dulwich_log              | 68.4 ms                                                      | 69.0 ms: 1.01x slower                                       |
| logging_silent           | 101 ns                                                       | 102 ns: 1.01x slower                                        |
| spectral_norm            | 93.3 ms                                                      | 94.6 ms: 1.01x slower                                       |
| docutils                 | 2.86 sec                                                     | 2.90 sec: 1.01x slower                                      |
| scimark_monte_carlo      | 68.2 ms                                                      | 69.3 ms: 1.02x slower                                       |
| xml_etree_iterparse      | 104 ms                                                       | 106 ms: 1.02x slower                                        |
| pprint_pformat           | 1.63 sec                                                     | 1.66 sec: 1.02x slower                                      |
| unpickle_list            | 4.53 us                                                      | 4.65 us: 1.02x slower                                       |
| scimark_sparse_mat_mult  | 4.05 ms                                                      | 4.16 ms: 1.03x slower                                       |
| regex_effbot             | 3.50 ms                                                      | 3.61 ms: 1.03x slower                                       |
| pathlib                  | 19.1 ms                                                      | 19.7 ms: 1.03x slower                                       |
| xml_etree_process        | 56.5 ms                                                      | 58.9 ms: 1.04x slower                                       |
| pprint_safe_repr         | 784 ms                                                       | 819 ms: 1.05x slower                                        |
| create_gc_cycles         | 1.61 ms                                                      | 1.68 ms: 1.05x slower                                       |
| pickle_dict              | 30.8 us                                                      | 32.3 us: 1.05x slower                                       |
| pidigits                 | 251 ms                                                       | 264 ms: 1.05x slower                                        |
| pickle                   | 9.64 us                                                      | 10.1 us: 1.05x slower                                       |
| bench_mp_pool            | 4.62 ms                                                      | 4.89 ms: 1.06x slower                                       |
| go                       | 164 ms                                                       | 174 ms: 1.06x slower                                        |
| regex_dna                | 227 ms                                                       | 242 ms: 1.06x slower                                        |
| xml_etree_generate       | 80.5 ms                                                      | 86.1 ms: 1.07x slower                                       |
| regex_v8                 | 23.9 ms                                                      | 25.6 ms: 1.07x slower                                       |
| scimark_fft              | 285 ms                                                       | 308 ms: 1.08x slower                                        |
| sqlite_synth             | 2.50 us                                                      | 2.72 us: 1.09x slower                                       |
| float                    | 74.2 ms                                                      | 81.1 ms: 1.09x slower                                       |
| unpickle                 | 13.4 us                                                      | 14.9 us: 1.11x slower                                       |
| richards                 | 48.3 ms                                                      | 53.5 ms: 1.11x slower                                       |
| python_startup_no_site   | 7.76 ms                                                      | 8.67 ms: 1.12x slower                                       |
| pyflate                  | 449 ms                                                       | 515 ms: 1.15x slower                                        |
| python_startup           | 10.8 ms                                                      | 12.6 ms: 1.17x slower                                       |
| telco                    | 6.86 ms                                                      | 8.15 ms: 1.19x slower                                       |
| pickle_list              | 3.83 us                                                      | 4.58 us: 1.20x slower                                       |
| unpack_sequence          | 45.6 ns                                                      | 55.4 ns: 1.21x slower                                       |
| async_generators         | 316 ms                                                       | 393 ms: 1.25x slower                                        |
| scimark_sor              | 111 ms                                                       | 146 ms: 1.32x slower                                        |
| dask                     | 410 ms                                                       | 588 ms: 1.43x slower                                        |
| Geometric mean           | (ref)                                                        | 1.04x faster                                                |

Benchmark hidden because not significant (1): pycparser
Ignored benchmarks (17) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509.json: 2to3, aiohttp, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 87.66% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
