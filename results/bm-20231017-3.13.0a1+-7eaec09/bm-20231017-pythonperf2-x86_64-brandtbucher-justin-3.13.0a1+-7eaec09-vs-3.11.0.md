
# Results vs. 3.11.0

- fork: brandtbucher
- ref: justin
- machine: linux-x86_64
- commit hash: 7eaec09
- commit date: 2023-10-17
- overall geometric mean: 1.04x faster
- HPT reliability: 78.76%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231017-pythonperf2-x86_64-brandtbucher-justin-3.13.0a1+-7eaec09 |
|----------------|:------------------------------------------------------------:|:--------------------------------------------------------------------:|
| docutils       | 2.86 sec                                                     | 2.92 sec: 1.02x slower                                               |
| Geometric mean | (ref)                                                        | 1.01x slower                                                         |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231017-pythonperf2-x86_64-brandtbucher-justin-3.13.0a1+-7eaec09 |
|----------------|:------------------------------------------------------------:|:--------------------------------------------------------------------:|
| nbody          | 90.7 ms                                                      | 88.9 ms: 1.02x faster                                                |
| pidigits       | 251 ms                                                       | 264 ms: 1.05x slower                                                 |
| float          | 74.2 ms                                                      | 78.4 ms: 1.06x slower                                                |
| Geometric mean | (ref)                                                        | 1.03x slower                                                         |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231017-pythonperf2-x86_64-brandtbucher-justin-3.13.0a1+-7eaec09 |
|----------------|:------------------------------------------------------------:|:--------------------------------------------------------------------:|
| regex_compile  | 158 ms                                                       | 150 ms: 1.05x faster                                                 |
| regex_v8       | 23.9 ms                                                      | 25.5 ms: 1.07x slower                                                |
| regex_dna      | 227 ms                                                       | 247 ms: 1.09x slower                                                 |
| Geometric mean | (ref)                                                        | 1.03x slower                                                         |

Benchmark hidden because not significant (1): regex_effbot

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231017-pythonperf2-x86_64-brandtbucher-justin-3.13.0a1+-7eaec09 |
|----------------------|:------------------------------------------------------------:|:--------------------------------------------------------------------:|
| json_dumps           | 13.4 ms                                                      | 10.6 ms: 1.26x faster                                                |
| json_loads           | 28.7 us                                                      | 24.4 us: 1.18x faster                                                |
| xml_etree_parse      | 158 ms                                                       | 150 ms: 1.05x faster                                                 |
| unpickle_pure_python | 241 us                                                       | 237 us: 1.02x faster                                                 |
| pickle_pure_python   | 319 us                                                       | 315 us: 1.01x faster                                                 |
| xml_etree_iterparse  | 104 ms                                                       | 105 ms: 1.01x slower                                                 |
| pickle_dict          | 30.8 us                                                      | 31.8 us: 1.03x slower                                                |
| unpickle_list        | 4.53 us                                                      | 4.75 us: 1.05x slower                                                |
| xml_etree_process    | 56.5 ms                                                      | 59.8 ms: 1.06x slower                                                |
| pickle               | 9.64 us                                                      | 10.3 us: 1.07x slower                                                |
| xml_etree_generate   | 80.5 ms                                                      | 87.1 ms: 1.08x slower                                                |
| unpickle             | 13.4 us                                                      | 14.7 us: 1.09x slower                                                |
| pickle_list          | 3.83 us                                                      | 4.48 us: 1.17x slower                                                |
| Geometric mean       | (ref)                                                        | 1.00x slower                                                         |

Benchmark hidden because not significant (1): tomli_loads

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231017-pythonperf2-x86_64-brandtbucher-justin-3.13.0a1+-7eaec09 |
|------------------------|:------------------------------------------------------------:|:--------------------------------------------------------------------:|
| python_startup_no_site | 7.76 ms                                                      | 8.75 ms: 1.13x slower                                                |
| python_startup         | 10.8 ms                                                      | 12.7 ms: 1.18x slower                                                |
| Geometric mean         | (ref)                                                        | 1.15x slower                                                         |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231017-pythonperf2-x86_64-brandtbucher-justin-3.13.0a1+-7eaec09 |
|-----------|:------------------------------------------------------------:|:--------------------------------------------------------------------:|
| mako      | 11.0 ms                                                      | 10.6 ms: 1.04x faster                                                |

All benchmarks:
===============

| Benchmark                | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231017-pythonperf2-x86_64-brandtbucher-justin-3.13.0a1+-7eaec09 |
|--------------------------|:------------------------------------------------------------:|:--------------------------------------------------------------------:|
| typing_runtime_protocols | 523 us                                                       | 157 us: 3.32x faster                                                 |
| asyncio_tcp              | 753 ms                                                       | 369 ms: 2.04x faster                                                 |
| asyncio_tcp_ssl          | 3.08 sec                                                     | 1.58 sec: 1.95x faster                                               |
| generators               | 56.0 ms                                                      | 36.3 ms: 1.54x faster                                                |
| json_dumps               | 13.4 ms                                                      | 10.6 ms: 1.26x faster                                                |
| chaos                    | 80.9 ms                                                      | 67.1 ms: 1.20x faster                                                |
| coroutines               | 27.6 ms                                                      | 23.1 ms: 1.19x faster                                                |
| async_tree_none          | 519 ms                                                       | 438 ms: 1.19x faster                                                 |
| json_loads               | 28.7 us                                                      | 24.4 us: 1.18x faster                                                |
| mypy2                    | 451 ms                                                       | 384 ms: 1.17x faster                                                 |
| async_tree_memoization   | 630 ms                                                       | 550 ms: 1.15x faster                                                 |
| raytrace                 | 317 ms                                                       | 286 ms: 1.11x faster                                                 |
| json                     | 5.65 ms                                                      | 5.12 ms: 1.10x faster                                                |
| logging_format           | 8.11 us                                                      | 7.42 us: 1.09x faster                                                |
| crypto_pyaes             | 83.4 ms                                                      | 76.3 ms: 1.09x faster                                                |
| async_tree_io            | 1.17 sec                                                     | 1.08 sec: 1.09x faster                                               |
| scimark_lu               | 115 ms                                                       | 106 ms: 1.08x faster                                                 |
| deltablue                | 4.00 ms                                                      | 3.72 ms: 1.08x faster                                                |
| fannkuch                 | 429 ms                                                       | 400 ms: 1.07x faster                                                 |
| sqlglot_parse            | 1.53 ms                                                      | 1.43 ms: 1.07x faster                                                |
| async_tree_cpu_io_mixed  | 749 ms                                                       | 700 ms: 1.07x faster                                                 |
| logging_simple           | 7.19 us                                                      | 6.73 us: 1.07x faster                                                |
| sqlglot_normalize        | 126 ms                                                       | 118 ms: 1.06x faster                                                 |
| mdp                      | 2.75 sec                                                     | 2.59 sec: 1.06x faster                                               |
| create_gc_cycles         | 1.61 ms                                                      | 1.53 ms: 1.05x faster                                                |
| xml_etree_parse          | 158 ms                                                       | 150 ms: 1.05x faster                                                 |
| gc_traversal             | 3.85 ms                                                      | 3.66 ms: 1.05x faster                                                |
| richards_super           | 61.0 ms                                                      | 58.1 ms: 1.05x faster                                                |
| regex_compile            | 158 ms                                                       | 150 ms: 1.05x faster                                                 |
| deepcopy_reduce          | 3.51 us                                                      | 3.35 us: 1.05x faster                                                |
| deepcopy                 | 399 us                                                       | 381 us: 1.05x faster                                                 |
| nqueens                  | 103 ms                                                       | 98.0 ms: 1.05x faster                                                |
| sqlglot_transpile        | 1.92 ms                                                      | 1.84 ms: 1.04x faster                                                |
| mako                     | 11.0 ms                                                      | 10.6 ms: 1.04x faster                                                |
| logging_silent           | 101 ns                                                       | 97.4 ns: 1.03x faster                                                |
| bench_thread_pool        | 1.01 ms                                                      | 983 us: 1.03x faster                                                 |
| coverage                 | 84.8 ms                                                      | 83.1 ms: 1.02x faster                                                |
| nbody                    | 90.7 ms                                                      | 88.9 ms: 1.02x faster                                                |
| unpickle_pure_python     | 241 us                                                       | 237 us: 1.02x faster                                                 |
| deepcopy_memo            | 38.8 us                                                      | 38.2 us: 1.02x faster                                                |
| pycparser                | 1.32 sec                                                     | 1.31 sec: 1.01x faster                                               |
| pickle_pure_python       | 319 us                                                       | 315 us: 1.01x faster                                                 |
| spectral_norm            | 93.3 ms                                                      | 92.8 ms: 1.01x faster                                                |
| sqlglot_optimize         | 59.8 ms                                                      | 60.1 ms: 1.00x slower                                                |
| xml_etree_iterparse      | 104 ms                                                       | 105 ms: 1.01x slower                                                 |
| meteor_contest           | 131 ms                                                       | 132 ms: 1.01x slower                                                 |
| dulwich_log              | 68.4 ms                                                      | 69.7 ms: 1.02x slower                                                |
| docutils                 | 2.86 sec                                                     | 2.92 sec: 1.02x slower                                               |
| comprehensions           | 24.6 us                                                      | 25.2 us: 1.02x slower                                                |
| pathlib                  | 19.1 ms                                                      | 19.6 ms: 1.03x slower                                                |
| pickle_dict              | 30.8 us                                                      | 31.8 us: 1.03x slower                                                |
| go                       | 164 ms                                                       | 170 ms: 1.03x slower                                                 |
| hexiom                   | 7.13 ms                                                      | 7.42 ms: 1.04x slower                                                |
| unpickle_list            | 4.53 us                                                      | 4.75 us: 1.05x slower                                                |
| pprint_pformat           | 1.63 sec                                                     | 1.71 sec: 1.05x slower                                               |
| pidigits                 | 251 ms                                                       | 264 ms: 1.05x slower                                                 |
| scimark_monte_carlo      | 68.2 ms                                                      | 71.8 ms: 1.05x slower                                                |
| float                    | 74.2 ms                                                      | 78.4 ms: 1.06x slower                                                |
| xml_etree_process        | 56.5 ms                                                      | 59.8 ms: 1.06x slower                                                |
| pprint_safe_repr         | 784 ms                                                       | 836 ms: 1.07x slower                                                 |
| regex_v8                 | 23.9 ms                                                      | 25.5 ms: 1.07x slower                                                |
| pickle                   | 9.64 us                                                      | 10.3 us: 1.07x slower                                                |
| bench_mp_pool            | 4.62 ms                                                      | 4.97 ms: 1.07x slower                                                |
| richards                 | 48.3 ms                                                      | 51.9 ms: 1.08x slower                                                |
| xml_etree_generate       | 80.5 ms                                                      | 87.1 ms: 1.08x slower                                                |
| sqlite_synth             | 2.50 us                                                      | 2.70 us: 1.08x slower                                                |
| regex_dna                | 227 ms                                                       | 247 ms: 1.09x slower                                                 |
| unpickle                 | 13.4 us                                                      | 14.7 us: 1.09x slower                                                |
| scimark_sparse_mat_mult  | 4.05 ms                                                      | 4.45 ms: 1.10x slower                                                |
| python_startup_no_site   | 7.76 ms                                                      | 8.75 ms: 1.13x slower                                                |
| unpack_sequence          | 45.6 ns                                                      | 52.5 ns: 1.15x slower                                                |
| pyflate                  | 449 ms                                                       | 523 ms: 1.17x slower                                                 |
| pickle_list              | 3.83 us                                                      | 4.48 us: 1.17x slower                                                |
| python_startup           | 10.8 ms                                                      | 12.7 ms: 1.18x slower                                                |
| telco                    | 6.86 ms                                                      | 8.16 ms: 1.19x slower                                                |
| scimark_fft              | 285 ms                                                       | 341 ms: 1.20x slower                                                 |
| async_generators         | 316 ms                                                       | 403 ms: 1.28x slower                                                 |
| scimark_sor              | 111 ms                                                       | 146 ms: 1.32x slower                                                 |
| Geometric mean           | (ref)                                                        | 1.04x faster                                                         |

Benchmark hidden because not significant (3): regex_effbot, tomli_loads, tornado_http
Ignored benchmarks (18) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509.json: 2to3, aiohttp, chameleon, dask, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 78.76% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
