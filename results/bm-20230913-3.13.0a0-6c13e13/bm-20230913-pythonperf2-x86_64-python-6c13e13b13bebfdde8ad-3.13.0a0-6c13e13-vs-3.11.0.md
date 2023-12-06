
# Results vs. 3.11.0

- fork: python
- ref: 6c13e13b13bebfdde8ad
- machine: linux-x86_64
- commit hash: 6c13e13
- commit date: 2023-09-13
- overall geometric mean: 1.05x faster
- HPT reliability: 97.02%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230913-pythonperf2-x86_64-python-6c13e13b13bebfdde8ad-3.13.0a0-6c13e13 |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| docutils       | 2.86 sec                                                     | 2.87 sec: 1.00x slower                                                      |
| Geometric mean | (ref)                                                        | 1.00x faster                                                                |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230913-pythonperf2-x86_64-python-6c13e13b13bebfdde8ad-3.13.0a0-6c13e13 |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| nbody          | 90.7 ms                                                      | 87.0 ms: 1.04x faster                                                       |
| pidigits       | 251 ms                                                       | 264 ms: 1.05x slower                                                        |
| float          | 74.2 ms                                                      | 81.1 ms: 1.09x slower                                                       |
| Geometric mean | (ref)                                                        | 1.03x slower                                                                |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230913-pythonperf2-x86_64-python-6c13e13b13bebfdde8ad-3.13.0a0-6c13e13 |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_compile  | 158 ms                                                       | 149 ms: 1.06x faster                                                        |
| regex_effbot   | 3.50 ms                                                      | 3.42 ms: 1.02x faster                                                       |
| regex_v8       | 23.9 ms                                                      | 24.8 ms: 1.04x slower                                                       |
| regex_dna      | 227 ms                                                       | 239 ms: 1.05x slower                                                        |
| Geometric mean | (ref)                                                        | 1.00x slower                                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230913-pythonperf2-x86_64-python-6c13e13b13bebfdde8ad-3.13.0a0-6c13e13 |
|----------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| json_dumps           | 13.4 ms                                                      | 10.7 ms: 1.25x faster                                                       |
| json_loads           | 28.7 us                                                      | 25.1 us: 1.14x faster                                                       |
| unpickle_pure_python | 241 us                                                       | 222 us: 1.08x faster                                                        |
| xml_etree_parse      | 158 ms                                                       | 149 ms: 1.06x faster                                                        |
| pickle_pure_python   | 319 us                                                       | 313 us: 1.02x faster                                                        |
| tomli_loads          | 2.26 sec                                                     | 2.22 sec: 1.02x faster                                                      |
| xml_etree_iterparse  | 104 ms                                                       | 107 ms: 1.02x slower                                                        |
| pickle               | 9.64 us                                                      | 9.94 us: 1.03x slower                                                       |
| xml_etree_process    | 56.5 ms                                                      | 58.6 ms: 1.04x slower                                                       |
| unpickle_list        | 4.53 us                                                      | 4.72 us: 1.04x slower                                                       |
| pickle_dict          | 30.8 us                                                      | 32.3 us: 1.05x slower                                                       |
| unpickle             | 13.4 us                                                      | 14.3 us: 1.06x slower                                                       |
| xml_etree_generate   | 80.5 ms                                                      | 85.9 ms: 1.07x slower                                                       |
| pickle_list          | 3.83 us                                                      | 4.15 us: 1.08x slower                                                       |
| Geometric mean       | (ref)                                                        | 1.01x faster                                                                |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230913-pythonperf2-x86_64-python-6c13e13b13bebfdde8ad-3.13.0a0-6c13e13 |
|------------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| python_startup_no_site | 7.76 ms                                                      | 8.65 ms: 1.11x slower                                                       |
| python_startup         | 10.8 ms                                                      | 12.6 ms: 1.17x slower                                                       |
| Geometric mean         | (ref)                                                        | 1.14x slower                                                                |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230913-pythonperf2-x86_64-python-6c13e13b13bebfdde8ad-3.13.0a0-6c13e13 |
|-----------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| mako      | 11.0 ms                                                      | 10.5 ms: 1.05x faster                                                       |

All benchmarks:
===============

| Benchmark                | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230913-pythonperf2-x86_64-python-6c13e13b13bebfdde8ad-3.13.0a0-6c13e13 |
|--------------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| typing_runtime_protocols | 523 us                                                       | 148 us: 3.52x faster                                                        |
| asyncio_tcp              | 753 ms                                                       | 372 ms: 2.03x faster                                                        |
| asyncio_tcp_ssl          | 3.08 sec                                                     | 1.58 sec: 1.95x faster                                                      |
| generators               | 56.0 ms                                                      | 34.7 ms: 1.62x faster                                                       |
| chaos                    | 80.9 ms                                                      | 63.6 ms: 1.27x faster                                                       |
| json_dumps               | 13.4 ms                                                      | 10.7 ms: 1.25x faster                                                       |
| mypy2                    | 451 ms                                                       | 370 ms: 1.22x faster                                                        |
| coroutines               | 27.6 ms                                                      | 23.1 ms: 1.19x faster                                                       |
| async_tree_none          | 519 ms                                                       | 437 ms: 1.19x faster                                                        |
| raytrace                 | 317 ms                                                       | 267 ms: 1.19x faster                                                        |
| crypto_pyaes             | 83.4 ms                                                      | 71.7 ms: 1.16x faster                                                       |
| json_loads               | 28.7 us                                                      | 25.1 us: 1.14x faster                                                       |
| nqueens                  | 103 ms                                                       | 90.0 ms: 1.14x faster                                                       |
| async_tree_memoization   | 630 ms                                                       | 552 ms: 1.14x faster                                                        |
| scimark_lu               | 115 ms                                                       | 101 ms: 1.13x faster                                                        |
| hexiom                   | 7.13 ms                                                      | 6.47 ms: 1.10x faster                                                       |
| json                     | 5.65 ms                                                      | 5.16 ms: 1.09x faster                                                       |
| sqlglot_normalize        | 126 ms                                                       | 115 ms: 1.09x faster                                                        |
| comprehensions           | 24.6 us                                                      | 22.6 us: 1.09x faster                                                       |
| logging_format           | 8.11 us                                                      | 7.49 us: 1.08x faster                                                       |
| deltablue                | 4.00 ms                                                      | 3.69 ms: 1.08x faster                                                       |
| unpickle_pure_python     | 241 us                                                       | 222 us: 1.08x faster                                                        |
| sqlglot_parse            | 1.53 ms                                                      | 1.42 ms: 1.08x faster                                                       |
| gc_traversal             | 3.85 ms                                                      | 3.56 ms: 1.08x faster                                                       |
| async_tree_io            | 1.17 sec                                                     | 1.09 sec: 1.08x faster                                                      |
| fannkuch                 | 429 ms                                                       | 397 ms: 1.08x faster                                                        |
| mdp                      | 2.75 sec                                                     | 2.55 sec: 1.08x faster                                                      |
| xml_etree_parse          | 158 ms                                                       | 149 ms: 1.06x faster                                                        |
| async_tree_cpu_io_mixed  | 749 ms                                                       | 706 ms: 1.06x faster                                                        |
| regex_compile            | 158 ms                                                       | 149 ms: 1.06x faster                                                        |
| sqlglot_transpile        | 1.92 ms                                                      | 1.82 ms: 1.06x faster                                                       |
| logging_simple           | 7.19 us                                                      | 6.83 us: 1.05x faster                                                       |
| mako                     | 11.0 ms                                                      | 10.5 ms: 1.05x faster                                                       |
| bench_thread_pool        | 1.01 ms                                                      | 963 us: 1.05x faster                                                        |
| deepcopy                 | 399 us                                                       | 382 us: 1.05x faster                                                        |
| coverage                 | 84.8 ms                                                      | 81.3 ms: 1.04x faster                                                       |
| nbody                    | 90.7 ms                                                      | 87.0 ms: 1.04x faster                                                       |
| deepcopy_reduce          | 3.51 us                                                      | 3.39 us: 1.04x faster                                                       |
| logging_silent           | 101 ns                                                       | 97.7 ns: 1.03x faster                                                       |
| scimark_monte_carlo      | 68.2 ms                                                      | 66.3 ms: 1.03x faster                                                       |
| deepcopy_memo            | 38.8 us                                                      | 37.8 us: 1.03x faster                                                       |
| sqlglot_optimize         | 59.8 ms                                                      | 58.4 ms: 1.02x faster                                                       |
| regex_effbot             | 3.50 ms                                                      | 3.42 ms: 1.02x faster                                                       |
| pickle_pure_python       | 319 us                                                       | 313 us: 1.02x faster                                                        |
| tomli_loads              | 2.26 sec                                                     | 2.22 sec: 1.02x faster                                                      |
| meteor_contest           | 131 ms                                                       | 129 ms: 1.01x faster                                                        |
| spectral_norm            | 93.3 ms                                                      | 92.6 ms: 1.01x faster                                                       |
| richards_super           | 61.0 ms                                                      | 60.7 ms: 1.01x faster                                                       |
| docutils                 | 2.86 sec                                                     | 2.87 sec: 1.00x slower                                                      |
| pprint_pformat           | 1.63 sec                                                     | 1.65 sec: 1.01x slower                                                      |
| dulwich_log              | 68.4 ms                                                      | 69.3 ms: 1.01x slower                                                       |
| create_gc_cycles         | 1.61 ms                                                      | 1.64 ms: 1.02x slower                                                       |
| xml_etree_iterparse      | 104 ms                                                       | 107 ms: 1.02x slower                                                        |
| pprint_safe_repr         | 784 ms                                                       | 806 ms: 1.03x slower                                                        |
| pickle                   | 9.64 us                                                      | 9.94 us: 1.03x slower                                                       |
| pathlib                  | 19.1 ms                                                      | 19.7 ms: 1.03x slower                                                       |
| go                       | 164 ms                                                       | 170 ms: 1.03x slower                                                        |
| regex_v8                 | 23.9 ms                                                      | 24.8 ms: 1.04x slower                                                       |
| xml_etree_process        | 56.5 ms                                                      | 58.6 ms: 1.04x slower                                                       |
| unpickle_list            | 4.53 us                                                      | 4.72 us: 1.04x slower                                                       |
| scimark_sparse_mat_mult  | 4.05 ms                                                      | 4.24 ms: 1.05x slower                                                       |
| pickle_dict              | 30.8 us                                                      | 32.3 us: 1.05x slower                                                       |
| regex_dna                | 227 ms                                                       | 239 ms: 1.05x slower                                                        |
| pidigits                 | 251 ms                                                       | 264 ms: 1.05x slower                                                        |
| scimark_fft              | 285 ms                                                       | 301 ms: 1.06x slower                                                        |
| unpickle                 | 13.4 us                                                      | 14.3 us: 1.06x slower                                                       |
| xml_etree_generate       | 80.5 ms                                                      | 85.9 ms: 1.07x slower                                                       |
| unpack_sequence          | 45.6 ns                                                      | 48.7 ns: 1.07x slower                                                       |
| pickle_list              | 3.83 us                                                      | 4.15 us: 1.08x slower                                                       |
| float                    | 74.2 ms                                                      | 81.1 ms: 1.09x slower                                                       |
| sqlite_synth             | 2.50 us                                                      | 2.75 us: 1.10x slower                                                       |
| python_startup_no_site   | 7.76 ms                                                      | 8.65 ms: 1.11x slower                                                       |
| richards                 | 48.3 ms                                                      | 54.0 ms: 1.12x slower                                                       |
| pyflate                  | 449 ms                                                       | 516 ms: 1.15x slower                                                        |
| python_startup           | 10.8 ms                                                      | 12.6 ms: 1.17x slower                                                       |
| telco                    | 6.86 ms                                                      | 8.20 ms: 1.19x slower                                                       |
| async_generators         | 316 ms                                                       | 392 ms: 1.24x slower                                                        |
| scimark_sor              | 111 ms                                                       | 148 ms: 1.33x slower                                                        |
| dask                     | 410 ms                                                       | 588 ms: 1.43x slower                                                        |
| Geometric mean           | (ref)                                                        | 1.05x faster                                                                |

Benchmark hidden because not significant (3): tornado_http, pycparser, bench_mp_pool
Ignored benchmarks (17) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509.json: 2to3, aiohttp, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 97.02% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
