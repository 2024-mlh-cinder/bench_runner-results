
# Results vs. 3.11.0

- fork: python
- ref: main
- machine: linux-x86_64
- commit hash: 51863b7
- commit date: 2023-09-23
- overall geometric mean: 1.05x faster
- HPT reliability: 88.84%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230923-pythonperf2-x86_64-python-main-3.13.0a0-51863b7 |
|----------------|:------------------------------------------------------------:|:-----------------------------------------------------------:|
| tornado_http   | 122 ms                                                       | 120 ms: 1.01x faster                                        |
| Geometric mean | (ref)                                                        | 1.01x faster                                                |

Benchmark hidden because not significant (1): docutils

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230923-pythonperf2-x86_64-python-main-3.13.0a0-51863b7 |
|----------------|:------------------------------------------------------------:|:-----------------------------------------------------------:|
| nbody          | 90.7 ms                                                      | 89.7 ms: 1.01x faster                                       |
| pidigits       | 251 ms                                                       | 264 ms: 1.05x slower                                        |
| float          | 74.2 ms                                                      | 80.9 ms: 1.09x slower                                       |
| Geometric mean | (ref)                                                        | 1.04x slower                                                |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230923-pythonperf2-x86_64-python-main-3.13.0a0-51863b7 |
|----------------|:------------------------------------------------------------:|:-----------------------------------------------------------:|
| regex_compile  | 158 ms                                                       | 148 ms: 1.07x faster                                        |
| regex_effbot   | 3.50 ms                                                      | 3.55 ms: 1.01x slower                                       |
| regex_v8       | 23.9 ms                                                      | 24.5 ms: 1.03x slower                                       |
| regex_dna      | 227 ms                                                       | 238 ms: 1.05x slower                                        |
| Geometric mean | (ref)                                                        | 1.01x slower                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230923-pythonperf2-x86_64-python-main-3.13.0a0-51863b7 |
|----------------------|:------------------------------------------------------------:|:-----------------------------------------------------------:|
| json_dumps           | 13.4 ms                                                      | 10.4 ms: 1.29x faster                                       |
| json_loads           | 28.7 us                                                      | 25.0 us: 1.15x faster                                       |
| xml_etree_parse      | 158 ms                                                       | 148 ms: 1.07x faster                                        |
| unpickle_pure_python | 241 us                                                       | 231 us: 1.04x faster                                        |
| pickle_pure_python   | 319 us                                                       | 317 us: 1.01x faster                                        |
| xml_etree_iterparse  | 104 ms                                                       | 105 ms: 1.01x slower                                        |
| tomli_loads          | 2.26 sec                                                     | 2.30 sec: 1.02x slower                                      |
| unpickle_list        | 4.53 us                                                      | 4.68 us: 1.03x slower                                       |
| pickle               | 9.64 us                                                      | 9.95 us: 1.03x slower                                       |
| pickle_dict          | 30.8 us                                                      | 31.9 us: 1.04x slower                                       |
| xml_etree_process    | 56.5 ms                                                      | 59.4 ms: 1.05x slower                                       |
| xml_etree_generate   | 80.5 ms                                                      | 86.4 ms: 1.07x slower                                       |
| unpickle             | 13.4 us                                                      | 14.5 us: 1.08x slower                                       |
| pickle_list          | 3.83 us                                                      | 4.43 us: 1.16x slower                                       |
| Geometric mean       | (ref)                                                        | 1.00x faster                                                |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230923-pythonperf2-x86_64-python-main-3.13.0a0-51863b7 |
|------------------------|:------------------------------------------------------------:|:-----------------------------------------------------------:|
| python_startup_no_site | 7.76 ms                                                      | 8.67 ms: 1.12x slower                                       |
| python_startup         | 10.8 ms                                                      | 12.6 ms: 1.17x slower                                       |
| Geometric mean         | (ref)                                                        | 1.15x slower                                                |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230923-pythonperf2-x86_64-python-main-3.13.0a0-51863b7 |
|-----------|:------------------------------------------------------------:|:-----------------------------------------------------------:|
| mako      | 11.0 ms                                                      | 10.4 ms: 1.06x faster                                       |

All benchmarks:
===============

| Benchmark                | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230923-pythonperf2-x86_64-python-main-3.13.0a0-51863b7 |
|--------------------------|:------------------------------------------------------------:|:-----------------------------------------------------------:|
| typing_runtime_protocols | 523 us                                                       | 150 us: 3.48x faster                                        |
| asyncio_tcp              | 753 ms                                                       | 370 ms: 2.04x faster                                        |
| asyncio_tcp_ssl          | 3.08 sec                                                     | 1.58 sec: 1.95x faster                                      |
| generators               | 56.0 ms                                                      | 35.3 ms: 1.59x faster                                       |
| json_dumps               | 13.4 ms                                                      | 10.4 ms: 1.29x faster                                       |
| chaos                    | 80.9 ms                                                      | 63.8 ms: 1.27x faster                                       |
| mypy2                    | 451 ms                                                       | 370 ms: 1.22x faster                                        |
| async_tree_none          | 519 ms                                                       | 433 ms: 1.20x faster                                        |
| coroutines               | 27.6 ms                                                      | 23.4 ms: 1.18x faster                                       |
| raytrace                 | 317 ms                                                       | 269 ms: 1.18x faster                                        |
| crypto_pyaes             | 83.4 ms                                                      | 72.0 ms: 1.16x faster                                       |
| nqueens                  | 103 ms                                                       | 88.8 ms: 1.16x faster                                       |
| async_tree_memoization   | 630 ms                                                       | 547 ms: 1.15x faster                                        |
| json_loads               | 28.7 us                                                      | 25.0 us: 1.15x faster                                       |
| comprehensions           | 24.6 us                                                      | 21.9 us: 1.13x faster                                       |
| scimark_lu               | 115 ms                                                       | 102 ms: 1.12x faster                                        |
| hexiom                   | 7.13 ms                                                      | 6.40 ms: 1.12x faster                                       |
| json                     | 5.65 ms                                                      | 5.13 ms: 1.10x faster                                       |
| sqlglot_normalize        | 126 ms                                                       | 115 ms: 1.10x faster                                        |
| sqlglot_parse            | 1.53 ms                                                      | 1.40 ms: 1.09x faster                                       |
| async_tree_io            | 1.17 sec                                                     | 1.08 sec: 1.09x faster                                      |
| fannkuch                 | 429 ms                                                       | 395 ms: 1.08x faster                                        |
| deltablue                | 4.00 ms                                                      | 3.69 ms: 1.08x faster                                       |
| mdp                      | 2.75 sec                                                     | 2.55 sec: 1.08x faster                                      |
| async_tree_cpu_io_mixed  | 749 ms                                                       | 696 ms: 1.08x faster                                        |
| logging_format           | 8.11 us                                                      | 7.55 us: 1.07x faster                                       |
| bench_thread_pool        | 1.01 ms                                                      | 944 us: 1.07x faster                                        |
| gc_traversal             | 3.85 ms                                                      | 3.60 ms: 1.07x faster                                       |
| xml_etree_parse          | 158 ms                                                       | 148 ms: 1.07x faster                                        |
| regex_compile            | 158 ms                                                       | 148 ms: 1.07x faster                                        |
| sqlglot_transpile        | 1.92 ms                                                      | 1.81 ms: 1.06x faster                                       |
| mako                     | 11.0 ms                                                      | 10.4 ms: 1.06x faster                                       |
| deepcopy                 | 399 us                                                       | 377 us: 1.06x faster                                        |
| coverage                 | 84.8 ms                                                      | 80.6 ms: 1.05x faster                                       |
| deepcopy_memo            | 38.8 us                                                      | 37.1 us: 1.05x faster                                       |
| unpickle_pure_python     | 241 us                                                       | 231 us: 1.04x faster                                        |
| logging_silent           | 101 ns                                                       | 96.8 ns: 1.04x faster                                       |
| logging_simple           | 7.19 us                                                      | 6.95 us: 1.03x faster                                       |
| richards_super           | 61.0 ms                                                      | 59.2 ms: 1.03x faster                                       |
| sqlglot_optimize         | 59.8 ms                                                      | 58.3 ms: 1.03x faster                                       |
| deepcopy_reduce          | 3.51 us                                                      | 3.43 us: 1.02x faster                                       |
| pycparser                | 1.32 sec                                                     | 1.30 sec: 1.02x faster                                      |
| tornado_http             | 122 ms                                                       | 120 ms: 1.01x faster                                        |
| nbody                    | 90.7 ms                                                      | 89.7 ms: 1.01x faster                                       |
| pickle_pure_python       | 319 us                                                       | 317 us: 1.01x faster                                        |
| meteor_contest           | 131 ms                                                       | 131 ms: 1.00x slower                                        |
| spectral_norm            | 93.3 ms                                                      | 94.2 ms: 1.01x slower                                       |
| xml_etree_iterparse      | 104 ms                                                       | 105 ms: 1.01x slower                                        |
| regex_effbot             | 3.50 ms                                                      | 3.55 ms: 1.01x slower                                       |
| tomli_loads              | 2.26 sec                                                     | 2.30 sec: 1.02x slower                                      |
| scimark_monte_carlo      | 68.2 ms                                                      | 69.6 ms: 1.02x slower                                       |
| go                       | 164 ms                                                       | 167 ms: 1.02x slower                                        |
| regex_v8                 | 23.9 ms                                                      | 24.5 ms: 1.03x slower                                       |
| unpickle_list            | 4.53 us                                                      | 4.68 us: 1.03x slower                                       |
| pickle                   | 9.64 us                                                      | 9.95 us: 1.03x slower                                       |
| scimark_sparse_mat_mult  | 4.05 ms                                                      | 4.18 ms: 1.03x slower                                       |
| pprint_pformat           | 1.63 sec                                                     | 1.69 sec: 1.03x slower                                      |
| pickle_dict              | 30.8 us                                                      | 31.9 us: 1.04x slower                                       |
| regex_dna                | 227 ms                                                       | 238 ms: 1.05x slower                                        |
| pathlib                  | 19.1 ms                                                      | 20.0 ms: 1.05x slower                                       |
| xml_etree_process        | 56.5 ms                                                      | 59.4 ms: 1.05x slower                                       |
| pidigits                 | 251 ms                                                       | 264 ms: 1.05x slower                                        |
| create_gc_cycles         | 1.61 ms                                                      | 1.70 ms: 1.05x slower                                       |
| pprint_safe_repr         | 784 ms                                                       | 830 ms: 1.06x slower                                        |
| scimark_fft              | 285 ms                                                       | 305 ms: 1.07x slower                                        |
| xml_etree_generate       | 80.5 ms                                                      | 86.4 ms: 1.07x slower                                       |
| unpickle                 | 13.4 us                                                      | 14.5 us: 1.08x slower                                       |
| sqlite_synth             | 2.50 us                                                      | 2.72 us: 1.09x slower                                       |
| float                    | 74.2 ms                                                      | 80.9 ms: 1.09x slower                                       |
| richards                 | 48.3 ms                                                      | 53.5 ms: 1.11x slower                                       |
| python_startup_no_site   | 7.76 ms                                                      | 8.67 ms: 1.12x slower                                       |
| pyflate                  | 449 ms                                                       | 510 ms: 1.14x slower                                        |
| unpack_sequence          | 45.6 ns                                                      | 52.1 ns: 1.14x slower                                       |
| pickle_list              | 3.83 us                                                      | 4.43 us: 1.16x slower                                       |
| telco                    | 6.86 ms                                                      | 8.01 ms: 1.17x slower                                       |
| python_startup           | 10.8 ms                                                      | 12.6 ms: 1.17x slower                                       |
| async_generators         | 316 ms                                                       | 402 ms: 1.27x slower                                        |
| scimark_sor              | 111 ms                                                       | 150 ms: 1.35x slower                                        |
| dask                     | 410 ms                                                       | 587 ms: 1.43x slower                                        |
| Geometric mean           | (ref)                                                        | 1.05x faster                                                |

Benchmark hidden because not significant (3): dulwich_log, docutils, bench_mp_pool
Ignored benchmarks (17) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509.json: 2to3, aiohttp, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 88.84% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
