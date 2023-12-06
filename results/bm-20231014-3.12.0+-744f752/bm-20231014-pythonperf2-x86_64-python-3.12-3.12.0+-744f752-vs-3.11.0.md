
# Results vs. 3.11.0

- fork: python
- ref: 3.12
- machine: linux-x86_64
- commit hash: 744f752
- commit date: 2023-10-14
- overall geometric mean: 1.07x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.02x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231014-pythonperf2-x86_64-python-3.12-3.12.0+-744f752 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------:|
| 2to3           | 288 ms                                                       | 285 ms: 1.01x faster                                       |
| docutils       | 2.86 sec                                                     | 2.87 sec: 1.00x slower                                     |
| tornado_http   | 122 ms                                                       | 120 ms: 1.01x faster                                       |
| Geometric mean | (ref)                                                        | 1.01x faster                                               |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231014-pythonperf2-x86_64-python-3.12-3.12.0+-744f752 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------:|
| nbody          | 90.7 ms                                                      | 84.2 ms: 1.08x faster                                      |
| float          | 74.2 ms                                                      | 77.4 ms: 1.04x slower                                      |
| pidigits       | 251 ms                                                       | 263 ms: 1.05x slower                                       |
| Geometric mean | (ref)                                                        | 1.01x slower                                               |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231014-pythonperf2-x86_64-python-3.12-3.12.0+-744f752 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------:|
| regex_compile  | 158 ms                                                       | 141 ms: 1.11x faster                                       |
| regex_effbot   | 3.50 ms                                                      | 3.49 ms: 1.00x faster                                      |
| regex_v8       | 23.9 ms                                                      | 24.3 ms: 1.02x slower                                      |
| regex_dna      | 227 ms                                                       | 243 ms: 1.07x slower                                       |
| Geometric mean | (ref)                                                        | 1.01x faster                                               |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231014-pythonperf2-x86_64-python-3.12-3.12.0+-744f752 |
|----------------------|:------------------------------------------------------------:|:----------------------------------------------------------:|
| json_dumps           | 13.4 ms                                                      | 10.2 ms: 1.31x faster                                      |
| json_loads           | 28.7 us                                                      | 24.0 us: 1.19x faster                                      |
| unpickle_pure_python | 241 us                                                       | 209 us: 1.15x faster                                       |
| xml_etree_parse      | 158 ms                                                       | 147 ms: 1.07x faster                                       |
| tomli_loads          | 2.26 sec                                                     | 2.18 sec: 1.04x faster                                     |
| xml_etree_iterparse  | 104 ms                                                       | 103 ms: 1.02x faster                                       |
| pickle_pure_python   | 319 us                                                       | 316 us: 1.01x faster                                       |
| xml_etree_process    | 56.5 ms                                                      | 58.2 ms: 1.03x slower                                      |
| unpickle_list        | 4.53 us                                                      | 4.70 us: 1.04x slower                                      |
| pickle_dict          | 30.8 us                                                      | 32.4 us: 1.05x slower                                      |
| xml_etree_generate   | 80.5 ms                                                      | 85.9 ms: 1.07x slower                                      |
| pickle               | 9.64 us                                                      | 10.3 us: 1.07x slower                                      |
| unpickle             | 13.4 us                                                      | 14.6 us: 1.09x slower                                      |
| pickle_list          | 3.83 us                                                      | 4.44 us: 1.16x slower                                      |
| Geometric mean       | (ref)                                                        | 1.02x faster                                               |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231014-pythonperf2-x86_64-python-3.12-3.12.0+-744f752 |
|------------------------|:------------------------------------------------------------:|:----------------------------------------------------------:|
| python_startup         | 10.8 ms                                                      | 11.7 ms: 1.09x slower                                      |
| python_startup_no_site | 7.76 ms                                                      | 8.65 ms: 1.11x slower                                      |
| Geometric mean         | (ref)                                                        | 1.10x slower                                               |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231014-pythonperf2-x86_64-python-3.12-3.12.0+-744f752 |
|-----------|:------------------------------------------------------------:|:----------------------------------------------------------:|
| mako      | 11.0 ms                                                      | 9.99 ms: 1.10x faster                                      |

All benchmarks:
===============

| Benchmark                | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231014-pythonperf2-x86_64-python-3.12-3.12.0+-744f752 |
|--------------------------|:------------------------------------------------------------:|:----------------------------------------------------------:|
| typing_runtime_protocols | 523 us                                                       | 153 us: 3.42x faster                                       |
| asyncio_tcp              | 753 ms                                                       | 379 ms: 1.99x faster                                       |
| asyncio_tcp_ssl          | 3.08 sec                                                     | 1.57 sec: 1.96x faster                                     |
| generators               | 56.0 ms                                                      | 37.0 ms: 1.52x faster                                      |
| json_dumps               | 13.4 ms                                                      | 10.2 ms: 1.31x faster                                      |
| chaos                    | 80.9 ms                                                      | 62.7 ms: 1.29x faster                                      |
| fannkuch                 | 429 ms                                                       | 338 ms: 1.27x faster                                       |
| deltablue                | 4.00 ms                                                      | 3.25 ms: 1.23x faster                                      |
| hexiom                   | 7.13 ms                                                      | 5.89 ms: 1.21x faster                                      |
| json_loads               | 28.7 us                                                      | 24.0 us: 1.19x faster                                      |
| richards_super           | 61.0 ms                                                      | 51.1 ms: 1.19x faster                                      |
| coroutines               | 27.6 ms                                                      | 23.4 ms: 1.18x faster                                      |
| scimark_lu               | 115 ms                                                       | 97.6 ms: 1.17x faster                                      |
| unpickle_pure_python     | 241 us                                                       | 209 us: 1.15x faster                                       |
| nqueens                  | 103 ms                                                       | 89.4 ms: 1.15x faster                                      |
| comprehensions           | 24.6 us                                                      | 21.5 us: 1.15x faster                                      |
| async_tree_memoization   | 630 ms                                                       | 552 ms: 1.14x faster                                       |
| async_tree_none          | 519 ms                                                       | 460 ms: 1.13x faster                                       |
| regex_compile            | 158 ms                                                       | 141 ms: 1.11x faster                                       |
| async_tree_io            | 1.17 sec                                                     | 1.06 sec: 1.11x faster                                     |
| json                     | 5.65 ms                                                      | 5.10 ms: 1.11x faster                                      |
| sqlglot_parse            | 1.53 ms                                                      | 1.39 ms: 1.11x faster                                      |
| mako                     | 11.0 ms                                                      | 9.99 ms: 1.10x faster                                      |
| go                       | 164 ms                                                       | 149 ms: 1.10x faster                                       |
| mdp                      | 2.75 sec                                                     | 2.52 sec: 1.09x faster                                     |
| richards                 | 48.3 ms                                                      | 44.4 ms: 1.09x faster                                      |
| deepcopy                 | 399 us                                                       | 367 us: 1.09x faster                                       |
| logging_silent           | 101 ns                                                       | 93.4 ns: 1.08x faster                                      |
| nbody                    | 90.7 ms                                                      | 84.2 ms: 1.08x faster                                      |
| xml_etree_parse          | 158 ms                                                       | 147 ms: 1.07x faster                                       |
| deepcopy_memo            | 38.8 us                                                      | 36.3 us: 1.07x faster                                      |
| sqlglot_transpile        | 1.92 ms                                                      | 1.79 ms: 1.07x faster                                      |
| logging_format           | 8.11 us                                                      | 7.59 us: 1.07x faster                                      |
| sqlglot_normalize        | 126 ms                                                       | 118 ms: 1.07x faster                                       |
| async_tree_cpu_io_mixed  | 749 ms                                                       | 703 ms: 1.07x faster                                       |
| pycparser                | 1.32 sec                                                     | 1.25 sec: 1.06x faster                                     |
| raytrace                 | 317 ms                                                       | 299 ms: 1.06x faster                                       |
| bench_thread_pool        | 1.01 ms                                                      | 958 us: 1.06x faster                                       |
| dulwich_log              | 68.4 ms                                                      | 65.1 ms: 1.05x faster                                      |
| meteor_contest           | 131 ms                                                       | 125 ms: 1.05x faster                                       |
| dask                     | 410 ms                                                       | 393 ms: 1.04x faster                                       |
| crypto_pyaes             | 83.4 ms                                                      | 80.3 ms: 1.04x faster                                      |
| tomli_loads              | 2.26 sec                                                     | 2.18 sec: 1.04x faster                                     |
| logging_simple           | 7.19 us                                                      | 6.94 us: 1.04x faster                                      |
| sqlglot_optimize         | 59.8 ms                                                      | 58.1 ms: 1.03x faster                                      |
| spectral_norm            | 93.3 ms                                                      | 90.7 ms: 1.03x faster                                      |
| deepcopy_reduce          | 3.51 us                                                      | 3.43 us: 1.02x faster                                      |
| gc_traversal             | 3.85 ms                                                      | 3.76 ms: 1.02x faster                                      |
| xml_etree_iterparse      | 104 ms                                                       | 103 ms: 1.02x faster                                       |
| tornado_http             | 122 ms                                                       | 120 ms: 1.01x faster                                       |
| scimark_sor              | 111 ms                                                       | 110 ms: 1.01x faster                                       |
| 2to3                     | 288 ms                                                       | 285 ms: 1.01x faster                                       |
| pickle_pure_python       | 319 us                                                       | 316 us: 1.01x faster                                       |
| pprint_pformat           | 1.63 sec                                                     | 1.62 sec: 1.00x faster                                     |
| pathlib                  | 19.1 ms                                                      | 19.0 ms: 1.00x faster                                      |
| regex_effbot             | 3.50 ms                                                      | 3.49 ms: 1.00x faster                                      |
| docutils                 | 2.86 sec                                                     | 2.87 sec: 1.00x slower                                     |
| scimark_monte_carlo      | 68.2 ms                                                      | 69.2 ms: 1.01x slower                                      |
| telco                    | 6.86 ms                                                      | 6.96 ms: 1.01x slower                                      |
| regex_v8                 | 23.9 ms                                                      | 24.3 ms: 1.02x slower                                      |
| pprint_safe_repr         | 784 ms                                                       | 797 ms: 1.02x slower                                       |
| xml_etree_process        | 56.5 ms                                                      | 58.2 ms: 1.03x slower                                      |
| unpickle_list            | 4.53 us                                                      | 4.70 us: 1.04x slower                                      |
| float                    | 74.2 ms                                                      | 77.4 ms: 1.04x slower                                      |
| pidigits                 | 251 ms                                                       | 263 ms: 1.05x slower                                       |
| scimark_fft              | 285 ms                                                       | 300 ms: 1.05x slower                                       |
| pickle_dict              | 30.8 us                                                      | 32.4 us: 1.05x slower                                      |
| coverage                 | 84.8 ms                                                      | 89.7 ms: 1.06x slower                                      |
| scimark_sparse_mat_mult  | 4.05 ms                                                      | 4.29 ms: 1.06x slower                                      |
| xml_etree_generate       | 80.5 ms                                                      | 85.9 ms: 1.07x slower                                      |
| pickle                   | 9.64 us                                                      | 10.3 us: 1.07x slower                                      |
| regex_dna                | 227 ms                                                       | 243 ms: 1.07x slower                                       |
| unpickle                 | 13.4 us                                                      | 14.6 us: 1.09x slower                                      |
| python_startup           | 10.8 ms                                                      | 11.7 ms: 1.09x slower                                      |
| sqlite_synth             | 2.50 us                                                      | 2.73 us: 1.09x slower                                      |
| unpack_sequence          | 45.6 ns                                                      | 50.2 ns: 1.10x slower                                      |
| python_startup_no_site   | 7.76 ms                                                      | 8.65 ms: 1.11x slower                                      |
| pickle_list              | 3.83 us                                                      | 4.44 us: 1.16x slower                                      |
| async_generators         | 316 ms                                                       | 381 ms: 1.21x slower                                       |
| bench_mp_pool            | 4.62 ms                                                      | 7.40 ms: 1.60x slower                                      |
| Geometric mean           | (ref)                                                        | 1.07x faster                                               |

Benchmark hidden because not significant (3): pyflate, create_gc_cycles, mypy2
Ignored benchmarks (16) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.03x
- 95% likely to have a speedup of 1.03x
- 99% likely to have a speedup of 1.02x
