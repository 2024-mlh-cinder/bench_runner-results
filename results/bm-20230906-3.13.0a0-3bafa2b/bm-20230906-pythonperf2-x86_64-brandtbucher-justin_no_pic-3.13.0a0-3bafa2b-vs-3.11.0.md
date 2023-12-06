
# Results vs. 3.11.0

- fork: brandtbucher
- ref: justin_no_pic
- machine: linux-x86_64
- commit hash: 3bafa2b
- commit date: 2023-09-06
- overall geometric mean: 1.03x faster
- HPT reliability: 51.20%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230906-pythonperf2-x86_64-brandtbucher-justin_no_pic-3.13.0a0-3bafa2b |
|----------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------:|
| docutils       | 2.86 sec                                                     | 2.93 sec: 1.03x slower                                                     |
| Geometric mean | (ref)                                                        | 1.01x slower                                                               |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230906-pythonperf2-x86_64-brandtbucher-justin_no_pic-3.13.0a0-3bafa2b |
|----------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------:|
| nbody          | 90.7 ms                                                      | 92.0 ms: 1.01x slower                                                      |
| pidigits       | 251 ms                                                       | 264 ms: 1.05x slower                                                       |
| float          | 74.2 ms                                                      | 82.0 ms: 1.11x slower                                                      |
| Geometric mean | (ref)                                                        | 1.06x slower                                                               |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230906-pythonperf2-x86_64-brandtbucher-justin_no_pic-3.13.0a0-3bafa2b |
|----------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------:|
| regex_compile  | 158 ms                                                       | 154 ms: 1.02x faster                                                       |
| regex_effbot   | 3.50 ms                                                      | 3.58 ms: 1.02x slower                                                      |
| regex_v8       | 23.9 ms                                                      | 25.2 ms: 1.05x slower                                                      |
| regex_dna      | 227 ms                                                       | 244 ms: 1.07x slower                                                       |
| Geometric mean | (ref)                                                        | 1.03x slower                                                               |

Benchmarks with tag 'serialize':
================================

| Benchmark           | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230906-pythonperf2-x86_64-brandtbucher-justin_no_pic-3.13.0a0-3bafa2b |
|---------------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------:|
| json_dumps          | 13.4 ms                                                      | 10.3 ms: 1.30x faster                                                      |
| json_loads          | 28.7 us                                                      | 24.6 us: 1.16x faster                                                      |
| xml_etree_parse     | 158 ms                                                       | 147 ms: 1.07x faster                                                       |
| pickle_pure_python  | 319 us                                                       | 316 us: 1.01x faster                                                       |
| tomli_loads         | 2.26 sec                                                     | 2.29 sec: 1.01x slower                                                     |
| xml_etree_iterparse | 104 ms                                                       | 106 ms: 1.02x slower                                                       |
| unpickle_list       | 4.53 us                                                      | 4.77 us: 1.05x slower                                                      |
| pickle              | 9.64 us                                                      | 10.2 us: 1.05x slower                                                      |
| xml_etree_process   | 56.5 ms                                                      | 59.5 ms: 1.05x slower                                                      |
| pickle_dict         | 30.8 us                                                      | 32.7 us: 1.06x slower                                                      |
| xml_etree_generate  | 80.5 ms                                                      | 86.0 ms: 1.07x slower                                                      |
| unpickle            | 13.4 us                                                      | 14.4 us: 1.07x slower                                                      |
| pickle_list         | 3.83 us                                                      | 4.49 us: 1.17x slower                                                      |
| Geometric mean      | (ref)                                                        | 1.00x slower                                                               |

Benchmark hidden because not significant (1): unpickle_pure_python

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230906-pythonperf2-x86_64-brandtbucher-justin_no_pic-3.13.0a0-3bafa2b |
|------------------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------:|
| python_startup         | 10.8 ms                                                      | 11.9 ms: 1.10x slower                                                      |
| python_startup_no_site | 7.76 ms                                                      | 8.86 ms: 1.14x slower                                                      |
| Geometric mean         | (ref)                                                        | 1.12x slower                                                               |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230906-pythonperf2-x86_64-brandtbucher-justin_no_pic-3.13.0a0-3bafa2b |
|-----------|:------------------------------------------------------------:|:--------------------------------------------------------------------------:|
| mako      | 11.0 ms                                                      | 10.5 ms: 1.04x faster                                                      |

All benchmarks:
===============

| Benchmark                | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230906-pythonperf2-x86_64-brandtbucher-justin_no_pic-3.13.0a0-3bafa2b |
|--------------------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------:|
| typing_runtime_protocols | 523 us                                                       | 153 us: 3.41x faster                                                       |
| asyncio_tcp              | 753 ms                                                       | 374 ms: 2.01x faster                                                       |
| asyncio_tcp_ssl          | 3.08 sec                                                     | 1.58 sec: 1.95x faster                                                     |
| generators               | 56.0 ms                                                      | 36.6 ms: 1.53x faster                                                      |
| json_dumps               | 13.4 ms                                                      | 10.3 ms: 1.30x faster                                                      |
| chaos                    | 80.9 ms                                                      | 65.3 ms: 1.24x faster                                                      |
| coroutines               | 27.6 ms                                                      | 22.6 ms: 1.22x faster                                                      |
| mypy2                    | 451 ms                                                       | 380 ms: 1.19x faster                                                       |
| async_tree_none          | 519 ms                                                       | 438 ms: 1.18x faster                                                       |
| json_loads               | 28.7 us                                                      | 24.6 us: 1.16x faster                                                      |
| raytrace                 | 317 ms                                                       | 276 ms: 1.15x faster                                                       |
| async_tree_memoization   | 630 ms                                                       | 552 ms: 1.14x faster                                                       |
| crypto_pyaes             | 83.4 ms                                                      | 74.0 ms: 1.13x faster                                                      |
| json                     | 5.65 ms                                                      | 5.07 ms: 1.11x faster                                                      |
| logging_format           | 8.11 us                                                      | 7.34 us: 1.11x faster                                                      |
| scimark_lu               | 115 ms                                                       | 104 ms: 1.10x faster                                                       |
| async_tree_io            | 1.17 sec                                                     | 1.09 sec: 1.08x faster                                                     |
| xml_etree_parse          | 158 ms                                                       | 147 ms: 1.07x faster                                                       |
| logging_simple           | 7.19 us                                                      | 6.73 us: 1.07x faster                                                      |
| async_tree_cpu_io_mixed  | 749 ms                                                       | 702 ms: 1.07x faster                                                       |
| deltablue                | 4.00 ms                                                      | 3.75 ms: 1.07x faster                                                      |
| sqlglot_parse            | 1.53 ms                                                      | 1.46 ms: 1.05x faster                                                      |
| sqlglot_normalize        | 126 ms                                                       | 120 ms: 1.05x faster                                                       |
| mdp                      | 2.75 sec                                                     | 2.62 sec: 1.05x faster                                                     |
| gc_traversal             | 3.85 ms                                                      | 3.68 ms: 1.05x faster                                                      |
| deepcopy_reduce          | 3.51 us                                                      | 3.36 us: 1.05x faster                                                      |
| fannkuch                 | 429 ms                                                       | 410 ms: 1.04x faster                                                       |
| mako                     | 11.0 ms                                                      | 10.5 ms: 1.04x faster                                                      |
| nqueens                  | 103 ms                                                       | 98.5 ms: 1.04x faster                                                      |
| deepcopy                 | 399 us                                                       | 384 us: 1.04x faster                                                       |
| logging_silent           | 101 ns                                                       | 98.1 ns: 1.03x faster                                                      |
| create_gc_cycles         | 1.61 ms                                                      | 1.57 ms: 1.03x faster                                                      |
| sqlglot_transpile        | 1.92 ms                                                      | 1.87 ms: 1.02x faster                                                      |
| coverage                 | 84.8 ms                                                      | 82.8 ms: 1.02x faster                                                      |
| regex_compile            | 158 ms                                                       | 154 ms: 1.02x faster                                                       |
| hexiom                   | 7.13 ms                                                      | 7.03 ms: 1.02x faster                                                      |
| pickle_pure_python       | 319 us                                                       | 316 us: 1.01x faster                                                       |
| comprehensions           | 24.6 us                                                      | 24.7 us: 1.00x slower                                                      |
| pprint_pformat           | 1.63 sec                                                     | 1.64 sec: 1.01x slower                                                     |
| pycparser                | 1.32 sec                                                     | 1.34 sec: 1.01x slower                                                     |
| tomli_loads              | 2.26 sec                                                     | 2.29 sec: 1.01x slower                                                     |
| sqlglot_optimize         | 59.8 ms                                                      | 60.6 ms: 1.01x slower                                                      |
| nbody                    | 90.7 ms                                                      | 92.0 ms: 1.01x slower                                                      |
| spectral_norm            | 93.3 ms                                                      | 94.8 ms: 1.02x slower                                                      |
| xml_etree_iterparse      | 104 ms                                                       | 106 ms: 1.02x slower                                                       |
| dulwich_log              | 68.4 ms                                                      | 69.9 ms: 1.02x slower                                                      |
| regex_effbot             | 3.50 ms                                                      | 3.58 ms: 1.02x slower                                                      |
| docutils                 | 2.86 sec                                                     | 2.93 sec: 1.03x slower                                                     |
| pprint_safe_repr         | 784 ms                                                       | 804 ms: 1.03x slower                                                       |
| pathlib                  | 19.1 ms                                                      | 20.0 ms: 1.05x slower                                                      |
| meteor_contest           | 131 ms                                                       | 137 ms: 1.05x slower                                                       |
| pidigits                 | 251 ms                                                       | 264 ms: 1.05x slower                                                       |
| regex_v8                 | 23.9 ms                                                      | 25.2 ms: 1.05x slower                                                      |
| unpickle_list            | 4.53 us                                                      | 4.77 us: 1.05x slower                                                      |
| pickle                   | 9.64 us                                                      | 10.2 us: 1.05x slower                                                      |
| xml_etree_process        | 56.5 ms                                                      | 59.5 ms: 1.05x slower                                                      |
| pickle_dict              | 30.8 us                                                      | 32.7 us: 1.06x slower                                                      |
| go                       | 164 ms                                                       | 175 ms: 1.06x slower                                                       |
| xml_etree_generate       | 80.5 ms                                                      | 86.0 ms: 1.07x slower                                                      |
| regex_dna                | 227 ms                                                       | 244 ms: 1.07x slower                                                       |
| unpickle                 | 13.4 us                                                      | 14.4 us: 1.07x slower                                                      |
| bench_mp_pool            | 4.62 ms                                                      | 5.02 ms: 1.09x slower                                                      |
| sqlite_synth             | 2.50 us                                                      | 2.74 us: 1.10x slower                                                      |
| pyflate                  | 449 ms                                                       | 495 ms: 1.10x slower                                                       |
| python_startup           | 10.8 ms                                                      | 11.9 ms: 1.10x slower                                                      |
| float                    | 74.2 ms                                                      | 82.0 ms: 1.11x slower                                                      |
| richards                 | 48.3 ms                                                      | 53.4 ms: 1.11x slower                                                      |
| unpack_sequence          | 45.6 ns                                                      | 50.6 ns: 1.11x slower                                                      |
| python_startup_no_site   | 7.76 ms                                                      | 8.86 ms: 1.14x slower                                                      |
| scimark_fft              | 285 ms                                                       | 329 ms: 1.16x slower                                                       |
| pickle_list              | 3.83 us                                                      | 4.49 us: 1.17x slower                                                      |
| telco                    | 6.86 ms                                                      | 8.19 ms: 1.19x slower                                                      |
| scimark_sparse_mat_mult  | 4.05 ms                                                      | 5.15 ms: 1.27x slower                                                      |
| async_generators         | 316 ms                                                       | 416 ms: 1.32x slower                                                       |
| scimark_sor              | 111 ms                                                       | 148 ms: 1.33x slower                                                       |
| dask                     | 410 ms                                                       | 593 ms: 1.45x slower                                                       |
| Geometric mean           | (ref)                                                        | 1.03x faster                                                               |

Benchmark hidden because not significant (6): bench_thread_pool, deepcopy_memo, richards_super, tornado_http, scimark_monte_carlo, unpickle_pure_python
Ignored benchmarks (17) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509.json: 2to3, aiohttp, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 51.20% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
