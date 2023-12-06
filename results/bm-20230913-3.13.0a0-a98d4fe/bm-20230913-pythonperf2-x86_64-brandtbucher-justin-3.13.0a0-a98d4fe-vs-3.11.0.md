
# Results vs. 3.11.0

- fork: brandtbucher
- ref: justin
- machine: linux-x86_64
- commit hash: a98d4fe
- commit date: 2023-09-13
- overall geometric mean: 1.01x faster
- HPT reliability: 84.93%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230913-pythonperf2-x86_64-brandtbucher-justin-3.13.0a0-a98d4fe |
|----------------|:------------------------------------------------------------:|:-------------------------------------------------------------------:|
| docutils       | 2.86 sec                                                     | 2.95 sec: 1.03x slower                                              |
| Geometric mean | (ref)                                                        | 1.02x slower                                                        |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230913-pythonperf2-x86_64-brandtbucher-justin-3.13.0a0-a98d4fe |
|----------------|:------------------------------------------------------------:|:-------------------------------------------------------------------:|
| pidigits       | 251 ms                                                       | 266 ms: 1.06x slower                                                |
| float          | 74.2 ms                                                      | 84.9 ms: 1.14x slower                                               |
| nbody          | 90.7 ms                                                      | 127 ms: 1.40x slower                                                |
| Geometric mean | (ref)                                                        | 1.19x slower                                                        |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230913-pythonperf2-x86_64-brandtbucher-justin-3.13.0a0-a98d4fe |
|----------------|:------------------------------------------------------------:|:-------------------------------------------------------------------:|
| regex_compile  | 158 ms                                                       | 159 ms: 1.01x slower                                                |
| regex_dna      | 227 ms                                                       | 245 ms: 1.08x slower                                                |
| regex_v8       | 23.9 ms                                                      | 26.3 ms: 1.10x slower                                               |
| Geometric mean | (ref)                                                        | 1.05x slower                                                        |

Benchmark hidden because not significant (1): regex_effbot

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230913-pythonperf2-x86_64-brandtbucher-justin-3.13.0a0-a98d4fe |
|----------------------|:------------------------------------------------------------:|:-------------------------------------------------------------------:|
| json_dumps           | 13.4 ms                                                      | 10.7 ms: 1.26x faster                                               |
| json_loads           | 28.7 us                                                      | 25.4 us: 1.13x faster                                               |
| xml_etree_parse      | 158 ms                                                       | 147 ms: 1.07x faster                                                |
| unpickle_pure_python | 241 us                                                       | 232 us: 1.04x faster                                                |
| pickle_pure_python   | 319 us                                                       | 317 us: 1.01x faster                                                |
| unpickle_list        | 4.53 us                                                      | 4.57 us: 1.01x slower                                               |
| xml_etree_iterparse  | 104 ms                                                       | 106 ms: 1.02x slower                                                |
| pickle_dict          | 30.8 us                                                      | 32.2 us: 1.05x slower                                               |
| pickle               | 9.64 us                                                      | 10.1 us: 1.05x slower                                               |
| xml_etree_process    | 56.5 ms                                                      | 59.5 ms: 1.05x slower                                               |
| xml_etree_generate   | 80.5 ms                                                      | 85.7 ms: 1.06x slower                                               |
| tomli_loads          | 2.26 sec                                                     | 2.44 sec: 1.08x slower                                              |
| unpickle             | 13.4 us                                                      | 14.9 us: 1.11x slower                                               |
| pickle_list          | 3.83 us                                                      | 4.30 us: 1.12x slower                                               |
| Geometric mean       | (ref)                                                        | 1.00x slower                                                        |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230913-pythonperf2-x86_64-brandtbucher-justin-3.13.0a0-a98d4fe |
|------------------------|:------------------------------------------------------------:|:-------------------------------------------------------------------:|
| python_startup_no_site | 7.76 ms                                                      | 8.70 ms: 1.12x slower                                               |
| python_startup         | 10.8 ms                                                      | 12.7 ms: 1.18x slower                                               |
| Geometric mean         | (ref)                                                        | 1.15x slower                                                        |

Benchmarks with tag 'template':
===============================

Benchmark hidden because not significant (1): mako

All benchmarks:
===============

| Benchmark                | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230913-pythonperf2-x86_64-brandtbucher-justin-3.13.0a0-a98d4fe |
|--------------------------|:------------------------------------------------------------:|:-------------------------------------------------------------------:|
| typing_runtime_protocols | 523 us                                                       | 160 us: 3.26x faster                                                |
| asyncio_tcp              | 753 ms                                                       | 371 ms: 2.03x faster                                                |
| asyncio_tcp_ssl          | 3.08 sec                                                     | 1.58 sec: 1.95x faster                                              |
| generators               | 56.0 ms                                                      | 37.2 ms: 1.51x faster                                               |
| json_dumps               | 13.4 ms                                                      | 10.7 ms: 1.26x faster                                               |
| async_tree_none          | 519 ms                                                       | 440 ms: 1.18x faster                                                |
| coroutines               | 27.6 ms                                                      | 23.5 ms: 1.17x faster                                               |
| raytrace                 | 317 ms                                                       | 271 ms: 1.17x faster                                                |
| mypy2                    | 451 ms                                                       | 387 ms: 1.17x faster                                                |
| async_tree_memoization   | 630 ms                                                       | 555 ms: 1.14x faster                                                |
| json_loads               | 28.7 us                                                      | 25.4 us: 1.13x faster                                               |
| chaos                    | 80.9 ms                                                      | 72.2 ms: 1.12x faster                                               |
| json                     | 5.65 ms                                                      | 5.15 ms: 1.10x faster                                               |
| crypto_pyaes             | 83.4 ms                                                      | 76.6 ms: 1.09x faster                                               |
| async_tree_io            | 1.17 sec                                                     | 1.09 sec: 1.08x faster                                              |
| logging_format           | 8.11 us                                                      | 7.54 us: 1.08x faster                                               |
| xml_etree_parse          | 158 ms                                                       | 147 ms: 1.07x faster                                                |
| deltablue                | 4.00 ms                                                      | 3.77 ms: 1.06x faster                                               |
| sqlglot_parse            | 1.53 ms                                                      | 1.44 ms: 1.06x faster                                               |
| async_tree_cpu_io_mixed  | 749 ms                                                       | 706 ms: 1.06x faster                                                |
| scimark_lu               | 115 ms                                                       | 108 ms: 1.06x faster                                                |
| coverage                 | 84.8 ms                                                      | 80.6 ms: 1.05x faster                                               |
| logging_simple           | 7.19 us                                                      | 6.87 us: 1.05x faster                                               |
| sqlglot_normalize        | 126 ms                                                       | 120 ms: 1.05x faster                                                |
| deepcopy_reduce          | 3.51 us                                                      | 3.37 us: 1.04x faster                                               |
| unpickle_pure_python     | 241 us                                                       | 232 us: 1.04x faster                                                |
| deepcopy                 | 399 us                                                       | 386 us: 1.04x faster                                                |
| bench_thread_pool        | 1.01 ms                                                      | 977 us: 1.03x faster                                                |
| sqlglot_transpile        | 1.92 ms                                                      | 1.86 ms: 1.03x faster                                               |
| pycparser                | 1.32 sec                                                     | 1.30 sec: 1.02x faster                                              |
| mdp                      | 2.75 sec                                                     | 2.71 sec: 1.01x faster                                              |
| logging_silent           | 101 ns                                                       | 99.4 ns: 1.01x faster                                               |
| spectral_norm            | 93.3 ms                                                      | 92.5 ms: 1.01x faster                                               |
| pickle_pure_python       | 319 us                                                       | 317 us: 1.01x faster                                                |
| unpickle_list            | 4.53 us                                                      | 4.57 us: 1.01x slower                                               |
| regex_compile            | 158 ms                                                       | 159 ms: 1.01x slower                                                |
| sqlglot_optimize         | 59.8 ms                                                      | 60.6 ms: 1.01x slower                                               |
| fannkuch                 | 429 ms                                                       | 437 ms: 1.02x slower                                                |
| xml_etree_iterparse      | 104 ms                                                       | 106 ms: 1.02x slower                                                |
| dulwich_log              | 68.4 ms                                                      | 69.9 ms: 1.02x slower                                               |
| pprint_pformat           | 1.63 sec                                                     | 1.67 sec: 1.02x slower                                              |
| gc_traversal             | 3.85 ms                                                      | 3.95 ms: 1.03x slower                                               |
| deepcopy_memo            | 38.8 us                                                      | 40.0 us: 1.03x slower                                               |
| docutils                 | 2.86 sec                                                     | 2.95 sec: 1.03x slower                                              |
| pprint_safe_repr         | 784 ms                                                       | 819 ms: 1.05x slower                                                |
| pickle_dict              | 30.8 us                                                      | 32.2 us: 1.05x slower                                               |
| pickle                   | 9.64 us                                                      | 10.1 us: 1.05x slower                                               |
| pathlib                  | 19.1 ms                                                      | 20.0 ms: 1.05x slower                                               |
| xml_etree_process        | 56.5 ms                                                      | 59.5 ms: 1.05x slower                                               |
| pidigits                 | 251 ms                                                       | 266 ms: 1.06x slower                                                |
| meteor_contest           | 131 ms                                                       | 139 ms: 1.06x slower                                                |
| xml_etree_generate       | 80.5 ms                                                      | 85.7 ms: 1.06x slower                                               |
| comprehensions           | 24.6 us                                                      | 26.3 us: 1.07x slower                                               |
| hexiom                   | 7.13 ms                                                      | 7.64 ms: 1.07x slower                                               |
| scimark_monte_carlo      | 68.2 ms                                                      | 73.4 ms: 1.08x slower                                               |
| nqueens                  | 103 ms                                                       | 111 ms: 1.08x slower                                                |
| tomli_loads              | 2.26 sec                                                     | 2.44 sec: 1.08x slower                                              |
| regex_dna                | 227 ms                                                       | 245 ms: 1.08x slower                                                |
| sqlite_synth             | 2.50 us                                                      | 2.71 us: 1.08x slower                                               |
| go                       | 164 ms                                                       | 179 ms: 1.09x slower                                                |
| regex_v8                 | 23.9 ms                                                      | 26.3 ms: 1.10x slower                                               |
| unpickle                 | 13.4 us                                                      | 14.9 us: 1.11x slower                                               |
| python_startup_no_site   | 7.76 ms                                                      | 8.70 ms: 1.12x slower                                               |
| pickle_list              | 3.83 us                                                      | 4.30 us: 1.12x slower                                               |
| pyflate                  | 449 ms                                                       | 509 ms: 1.13x slower                                                |
| richards                 | 48.3 ms                                                      | 55.1 ms: 1.14x slower                                               |
| float                    | 74.2 ms                                                      | 84.9 ms: 1.14x slower                                               |
| python_startup           | 10.8 ms                                                      | 12.7 ms: 1.18x slower                                               |
| telco                    | 6.86 ms                                                      | 8.26 ms: 1.20x slower                                               |
| unpack_sequence          | 45.6 ns                                                      | 57.6 ns: 1.26x slower                                               |
| async_generators         | 316 ms                                                       | 415 ms: 1.32x slower                                                |
| scimark_sor              | 111 ms                                                       | 148 ms: 1.33x slower                                                |
| scimark_sparse_mat_mult  | 4.05 ms                                                      | 5.63 ms: 1.39x slower                                               |
| scimark_fft              | 285 ms                                                       | 398 ms: 1.40x slower                                                |
| nbody                    | 90.7 ms                                                      | 127 ms: 1.40x slower                                                |
| dask                     | 410 ms                                                       | 595 ms: 1.45x slower                                                |
| Geometric mean           | (ref)                                                        | 1.01x faster                                                        |

Benchmark hidden because not significant (6): mako, regex_effbot, richards_super, create_gc_cycles, tornado_http, bench_mp_pool
Ignored benchmarks (17) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509.json: 2to3, aiohttp, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 84.93% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
