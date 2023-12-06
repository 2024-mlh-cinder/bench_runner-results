
# Results vs. 3.11.0

- fork: brandtbucher
- ref: justin
- machine: linux-x86_64
- commit hash: 7fb79b8
- commit date: 2023-09-05
- overall geometric mean: 1.01x faster
- HPT reliability: 92.51%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230905-pythonperf2-x86_64-brandtbucher-justin-3.13.0a0-7fb79b8 |
|----------------|:------------------------------------------------------------:|:-------------------------------------------------------------------:|
| docutils       | 2.86 sec                                                     | 2.97 sec: 1.04x slower                                              |
| Geometric mean | (ref)                                                        | 1.02x slower                                                        |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230905-pythonperf2-x86_64-brandtbucher-justin-3.13.0a0-7fb79b8 |
|----------------|:------------------------------------------------------------:|:-------------------------------------------------------------------:|
| pidigits       | 251 ms                                                       | 265 ms: 1.05x slower                                                |
| nbody          | 90.7 ms                                                      | 96.0 ms: 1.06x slower                                               |
| float          | 74.2 ms                                                      | 83.2 ms: 1.12x slower                                               |
| Geometric mean | (ref)                                                        | 1.08x slower                                                        |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230905-pythonperf2-x86_64-brandtbucher-justin-3.13.0a0-7fb79b8 |
|----------------|:------------------------------------------------------------:|:-------------------------------------------------------------------:|
| regex_effbot   | 3.50 ms                                                      | 3.64 ms: 1.04x slower                                               |
| regex_dna      | 227 ms                                                       | 241 ms: 1.06x slower                                                |
| regex_v8       | 23.9 ms                                                      | 25.9 ms: 1.08x slower                                               |
| Geometric mean | (ref)                                                        | 1.05x slower                                                        |

Benchmark hidden because not significant (1): regex_compile

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230905-pythonperf2-x86_64-brandtbucher-justin-3.13.0a0-7fb79b8 |
|----------------------|:------------------------------------------------------------:|:-------------------------------------------------------------------:|
| json_dumps           | 13.4 ms                                                      | 10.4 ms: 1.28x faster                                               |
| json_loads           | 28.7 us                                                      | 25.4 us: 1.13x faster                                               |
| xml_etree_parse      | 158 ms                                                       | 147 ms: 1.07x faster                                                |
| unpickle_list        | 4.53 us                                                      | 4.57 us: 1.01x slower                                               |
| unpickle_pure_python | 241 us                                                       | 246 us: 1.02x slower                                                |
| xml_etree_iterparse  | 104 ms                                                       | 108 ms: 1.04x slower                                                |
| xml_etree_process    | 56.5 ms                                                      | 59.4 ms: 1.05x slower                                               |
| pickle               | 9.64 us                                                      | 10.2 us: 1.06x slower                                               |
| tomli_loads          | 2.26 sec                                                     | 2.42 sec: 1.07x slower                                              |
| xml_etree_generate   | 80.5 ms                                                      | 87.0 ms: 1.08x slower                                               |
| pickle_dict          | 30.8 us                                                      | 33.7 us: 1.10x slower                                               |
| unpickle             | 13.4 us                                                      | 15.0 us: 1.12x slower                                               |
| pickle_list          | 3.83 us                                                      | 4.52 us: 1.18x slower                                               |
| Geometric mean       | (ref)                                                        | 1.02x slower                                                        |

Benchmark hidden because not significant (1): pickle_pure_python

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230905-pythonperf2-x86_64-brandtbucher-justin-3.13.0a0-7fb79b8 |
|------------------------|:------------------------------------------------------------:|:-------------------------------------------------------------------:|
| python_startup         | 10.8 ms                                                      | 11.9 ms: 1.11x slower                                               |
| python_startup_no_site | 7.76 ms                                                      | 8.86 ms: 1.14x slower                                               |
| Geometric mean         | (ref)                                                        | 1.12x slower                                                        |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230905-pythonperf2-x86_64-brandtbucher-justin-3.13.0a0-7fb79b8 |
|-----------|:------------------------------------------------------------:|:-------------------------------------------------------------------:|
| mako      | 11.0 ms                                                      | 10.9 ms: 1.01x faster                                               |

All benchmarks:
===============

| Benchmark                | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230905-pythonperf2-x86_64-brandtbucher-justin-3.13.0a0-7fb79b8 |
|--------------------------|:------------------------------------------------------------:|:-------------------------------------------------------------------:|
| typing_runtime_protocols | 523 us                                                       | 160 us: 3.26x faster                                                |
| asyncio_tcp              | 753 ms                                                       | 372 ms: 2.02x faster                                                |
| asyncio_tcp_ssl          | 3.08 sec                                                     | 1.58 sec: 1.95x faster                                              |
| generators               | 56.0 ms                                                      | 36.6 ms: 1.53x faster                                               |
| json_dumps               | 13.4 ms                                                      | 10.4 ms: 1.28x faster                                               |
| coroutines               | 27.6 ms                                                      | 22.7 ms: 1.21x faster                                               |
| chaos                    | 80.9 ms                                                      | 68.4 ms: 1.18x faster                                               |
| mypy2                    | 451 ms                                                       | 386 ms: 1.17x faster                                                |
| async_tree_none          | 519 ms                                                       | 449 ms: 1.16x faster                                                |
| raytrace                 | 317 ms                                                       | 279 ms: 1.13x faster                                                |
| json_loads               | 28.7 us                                                      | 25.4 us: 1.13x faster                                               |
| async_tree_memoization   | 630 ms                                                       | 562 ms: 1.12x faster                                                |
| logging_format           | 8.11 us                                                      | 7.43 us: 1.09x faster                                               |
| json                     | 5.65 ms                                                      | 5.19 ms: 1.09x faster                                               |
| crypto_pyaes             | 83.4 ms                                                      | 76.9 ms: 1.09x faster                                               |
| scimark_lu               | 115 ms                                                       | 107 ms: 1.07x faster                                                |
| xml_etree_parse          | 158 ms                                                       | 147 ms: 1.07x faster                                                |
| async_tree_io            | 1.17 sec                                                     | 1.10 sec: 1.07x faster                                              |
| sqlglot_parse            | 1.53 ms                                                      | 1.45 ms: 1.06x faster                                               |
| deltablue                | 4.00 ms                                                      | 3.79 ms: 1.05x faster                                               |
| logging_simple           | 7.19 us                                                      | 6.86 us: 1.05x faster                                               |
| async_tree_cpu_io_mixed  | 749 ms                                                       | 716 ms: 1.05x faster                                                |
| sqlglot_normalize        | 126 ms                                                       | 121 ms: 1.04x faster                                                |
| mdp                      | 2.75 sec                                                     | 2.67 sec: 1.03x faster                                              |
| sqlglot_transpile        | 1.92 ms                                                      | 1.87 ms: 1.02x faster                                               |
| coverage                 | 84.8 ms                                                      | 83.0 ms: 1.02x faster                                               |
| pycparser                | 1.32 sec                                                     | 1.30 sec: 1.02x faster                                              |
| logging_silent           | 101 ns                                                       | 99.7 ns: 1.01x faster                                               |
| mako                     | 11.0 ms                                                      | 10.9 ms: 1.01x faster                                               |
| deepcopy_reduce          | 3.51 us                                                      | 3.48 us: 1.01x faster                                               |
| deepcopy                 | 399 us                                                       | 396 us: 1.01x faster                                                |
| unpickle_list            | 4.53 us                                                      | 4.57 us: 1.01x slower                                               |
| richards_super           | 61.0 ms                                                      | 61.7 ms: 1.01x slower                                               |
| nqueens                  | 103 ms                                                       | 104 ms: 1.01x slower                                                |
| dulwich_log              | 68.4 ms                                                      | 69.5 ms: 1.02x slower                                               |
| fannkuch                 | 429 ms                                                       | 438 ms: 1.02x slower                                                |
| spectral_norm            | 93.3 ms                                                      | 95.3 ms: 1.02x slower                                               |
| unpickle_pure_python     | 241 us                                                       | 246 us: 1.02x slower                                                |
| sqlglot_optimize         | 59.8 ms                                                      | 61.5 ms: 1.03x slower                                               |
| deepcopy_memo            | 38.8 us                                                      | 40.0 us: 1.03x slower                                               |
| pprint_pformat           | 1.63 sec                                                     | 1.68 sec: 1.03x slower                                              |
| xml_etree_iterparse      | 104 ms                                                       | 108 ms: 1.04x slower                                                |
| docutils                 | 2.86 sec                                                     | 2.97 sec: 1.04x slower                                              |
| regex_effbot             | 3.50 ms                                                      | 3.64 ms: 1.04x slower                                               |
| pathlib                  | 19.1 ms                                                      | 20.0 ms: 1.05x slower                                               |
| scimark_monte_carlo      | 68.2 ms                                                      | 71.7 ms: 1.05x slower                                               |
| pprint_safe_repr         | 784 ms                                                       | 824 ms: 1.05x slower                                                |
| xml_etree_process        | 56.5 ms                                                      | 59.4 ms: 1.05x slower                                               |
| hexiom                   | 7.13 ms                                                      | 7.51 ms: 1.05x slower                                               |
| pidigits                 | 251 ms                                                       | 265 ms: 1.05x slower                                                |
| nbody                    | 90.7 ms                                                      | 96.0 ms: 1.06x slower                                               |
| regex_dna                | 227 ms                                                       | 241 ms: 1.06x slower                                                |
| pickle                   | 9.64 us                                                      | 10.2 us: 1.06x slower                                               |
| comprehensions           | 24.6 us                                                      | 26.2 us: 1.07x slower                                               |
| meteor_contest           | 131 ms                                                       | 140 ms: 1.07x slower                                                |
| tomli_loads              | 2.26 sec                                                     | 2.42 sec: 1.07x slower                                              |
| xml_etree_generate       | 80.5 ms                                                      | 87.0 ms: 1.08x slower                                               |
| gc_traversal             | 3.85 ms                                                      | 4.16 ms: 1.08x slower                                               |
| regex_v8                 | 23.9 ms                                                      | 25.9 ms: 1.08x slower                                               |
| pickle_dict              | 30.8 us                                                      | 33.7 us: 1.10x slower                                               |
| python_startup           | 10.8 ms                                                      | 11.9 ms: 1.11x slower                                               |
| sqlite_synth             | 2.50 us                                                      | 2.77 us: 1.11x slower                                               |
| go                       | 164 ms                                                       | 182 ms: 1.11x slower                                                |
| unpack_sequence          | 45.6 ns                                                      | 51.1 ns: 1.12x slower                                               |
| unpickle                 | 13.4 us                                                      | 15.0 us: 1.12x slower                                               |
| float                    | 74.2 ms                                                      | 83.2 ms: 1.12x slower                                               |
| pyflate                  | 449 ms                                                       | 511 ms: 1.14x slower                                                |
| python_startup_no_site   | 7.76 ms                                                      | 8.86 ms: 1.14x slower                                               |
| richards                 | 48.3 ms                                                      | 56.0 ms: 1.16x slower                                               |
| scimark_fft              | 285 ms                                                       | 333 ms: 1.17x slower                                                |
| pickle_list              | 3.83 us                                                      | 4.52 us: 1.18x slower                                               |
| telco                    | 6.86 ms                                                      | 8.29 ms: 1.21x slower                                               |
| scimark_sparse_mat_mult  | 4.05 ms                                                      | 5.23 ms: 1.29x slower                                               |
| async_generators         | 316 ms                                                       | 416 ms: 1.32x slower                                                |
| scimark_sor              | 111 ms                                                       | 147 ms: 1.32x slower                                                |
| dask                     | 410 ms                                                       | 596 ms: 1.45x slower                                                |
| Geometric mean           | (ref)                                                        | 1.01x faster                                                        |

Benchmark hidden because not significant (6): create_gc_cycles, regex_compile, pickle_pure_python, bench_thread_pool, tornado_http, bench_mp_pool
Ignored benchmarks (17) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509.json: 2to3, aiohttp, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 92.51% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
