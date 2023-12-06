
# Results vs. 3.11.0

- fork: python
- ref: v3.12.0rc2
- machine: linux-x86_64
- commit hash: 40913a5
- commit date: 2023-09-05
- overall geometric mean: 1.07x faster
- HPT reliability: 99.89%
- HPT 99th percentile: 1.01x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230905-pythonperf2-x86_64-python-v3.12.0rc2-3.12.0rc2-40913a5 |
|----------------|:------------------------------------------------------------:|:------------------------------------------------------------------:|
| 2to3           | 288 ms                                                       | 287 ms: 1.00x faster                                               |
| docutils       | 2.86 sec                                                     | 2.90 sec: 1.02x slower                                             |
| tornado_http   | 122 ms                                                       | 120 ms: 1.02x faster                                               |
| Geometric mean | (ref)                                                        | 1.00x faster                                                       |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230905-pythonperf2-x86_64-python-v3.12.0rc2-3.12.0rc2-40913a5 |
|----------------|:------------------------------------------------------------:|:------------------------------------------------------------------:|
| nbody          | 90.7 ms                                                      | 87.5 ms: 1.04x faster                                              |
| pidigits       | 251 ms                                                       | 264 ms: 1.05x slower                                               |
| float          | 74.2 ms                                                      | 79.6 ms: 1.07x slower                                              |
| Geometric mean | (ref)                                                        | 1.03x slower                                                       |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230905-pythonperf2-x86_64-python-v3.12.0rc2-3.12.0rc2-40913a5 |
|----------------|:------------------------------------------------------------:|:------------------------------------------------------------------:|
| regex_compile  | 158 ms                                                       | 146 ms: 1.08x faster                                               |
| regex_v8       | 23.9 ms                                                      | 23.8 ms: 1.01x faster                                              |
| regex_effbot   | 3.50 ms                                                      | 3.52 ms: 1.01x slower                                              |
| regex_dna      | 227 ms                                                       | 238 ms: 1.05x slower                                               |
| Geometric mean | (ref)                                                        | 1.01x faster                                                       |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230905-pythonperf2-x86_64-python-v3.12.0rc2-3.12.0rc2-40913a5 |
|----------------------|:------------------------------------------------------------:|:------------------------------------------------------------------:|
| json_dumps           | 13.4 ms                                                      | 10.2 ms: 1.31x faster                                              |
| json_loads           | 28.7 us                                                      | 24.4 us: 1.18x faster                                              |
| unpickle_pure_python | 241 us                                                       | 212 us: 1.14x faster                                               |
| xml_etree_parse      | 158 ms                                                       | 146 ms: 1.08x faster                                               |
| tomli_loads          | 2.26 sec                                                     | 2.17 sec: 1.04x faster                                             |
| xml_etree_iterparse  | 104 ms                                                       | 103 ms: 1.01x faster                                               |
| pickle_pure_python   | 319 us                                                       | 326 us: 1.02x slower                                               |
| xml_etree_process    | 56.5 ms                                                      | 58.9 ms: 1.04x slower                                              |
| unpickle_list        | 4.53 us                                                      | 4.75 us: 1.05x slower                                              |
| pickle_dict          | 30.8 us                                                      | 32.4 us: 1.05x slower                                              |
| xml_etree_generate   | 80.5 ms                                                      | 85.8 ms: 1.07x slower                                              |
| pickle               | 9.64 us                                                      | 10.4 us: 1.08x slower                                              |
| unpickle             | 13.4 us                                                      | 14.7 us: 1.10x slower                                              |
| pickle_list          | 3.83 us                                                      | 4.46 us: 1.17x slower                                              |
| Geometric mean       | (ref)                                                        | 1.01x faster                                                       |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230905-pythonperf2-x86_64-python-v3.12.0rc2-3.12.0rc2-40913a5 |
|------------------------|:------------------------------------------------------------:|:------------------------------------------------------------------:|
| python_startup         | 10.8 ms                                                      | 11.7 ms: 1.09x slower                                              |
| python_startup_no_site | 7.76 ms                                                      | 8.67 ms: 1.12x slower                                              |
| Geometric mean         | (ref)                                                        | 1.10x slower                                                       |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230905-pythonperf2-x86_64-python-v3.12.0rc2-3.12.0rc2-40913a5 |
|-----------|:------------------------------------------------------------:|:------------------------------------------------------------------:|
| mako      | 11.0 ms                                                      | 9.92 ms: 1.11x faster                                              |

All benchmarks:
===============

| Benchmark                | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230905-pythonperf2-x86_64-python-v3.12.0rc2-3.12.0rc2-40913a5 |
|--------------------------|:------------------------------------------------------------:|:------------------------------------------------------------------:|
| typing_runtime_protocols | 523 us                                                       | 149 us: 3.50x faster                                               |
| asyncio_tcp_ssl          | 3.08 sec                                                     | 1.57 sec: 1.96x faster                                             |
| asyncio_tcp              | 753 ms                                                       | 386 ms: 1.95x faster                                               |
| generators               | 56.0 ms                                                      | 36.7 ms: 1.53x faster                                              |
| json_dumps               | 13.4 ms                                                      | 10.2 ms: 1.31x faster                                              |
| chaos                    | 80.9 ms                                                      | 62.3 ms: 1.30x faster                                              |
| fannkuch                 | 429 ms                                                       | 335 ms: 1.28x faster                                               |
| mypy2                    | 451 ms                                                       | 368 ms: 1.23x faster                                               |
| deltablue                | 4.00 ms                                                      | 3.29 ms: 1.22x faster                                              |
| richards_super           | 61.0 ms                                                      | 50.5 ms: 1.21x faster                                              |
| hexiom                   | 7.13 ms                                                      | 5.97 ms: 1.20x faster                                              |
| coroutines               | 27.6 ms                                                      | 23.3 ms: 1.18x faster                                              |
| json_loads               | 28.7 us                                                      | 24.4 us: 1.18x faster                                              |
| scimark_lu               | 115 ms                                                       | 97.6 ms: 1.17x faster                                              |
| async_tree_memoization   | 630 ms                                                       | 552 ms: 1.14x faster                                               |
| unpickle_pure_python     | 241 us                                                       | 212 us: 1.14x faster                                               |
| async_tree_none          | 519 ms                                                       | 458 ms: 1.13x faster                                               |
| comprehensions           | 24.6 us                                                      | 21.8 us: 1.13x faster                                              |
| nqueens                  | 103 ms                                                       | 91.3 ms: 1.13x faster                                              |
| async_tree_io            | 1.17 sec                                                     | 1.06 sec: 1.11x faster                                             |
| mako                     | 11.0 ms                                                      | 9.92 ms: 1.11x faster                                              |
| go                       | 164 ms                                                       | 148 ms: 1.11x faster                                               |
| json                     | 5.65 ms                                                      | 5.12 ms: 1.10x faster                                              |
| logging_format           | 8.11 us                                                      | 7.40 us: 1.10x faster                                              |
| mdp                      | 2.75 sec                                                     | 2.52 sec: 1.09x faster                                             |
| gc_traversal             | 3.85 ms                                                      | 3.54 ms: 1.09x faster                                              |
| sqlglot_parse            | 1.53 ms                                                      | 1.41 ms: 1.08x faster                                              |
| richards                 | 48.3 ms                                                      | 44.6 ms: 1.08x faster                                              |
| xml_etree_parse          | 158 ms                                                       | 146 ms: 1.08x faster                                               |
| pycparser                | 1.32 sec                                                     | 1.23 sec: 1.08x faster                                             |
| regex_compile            | 158 ms                                                       | 146 ms: 1.08x faster                                               |
| async_tree_cpu_io_mixed  | 749 ms                                                       | 702 ms: 1.07x faster                                               |
| sqlglot_transpile        | 1.92 ms                                                      | 1.81 ms: 1.06x faster                                              |
| dulwich_log              | 68.4 ms                                                      | 64.9 ms: 1.05x faster                                              |
| logging_simple           | 7.19 us                                                      | 6.84 us: 1.05x faster                                              |
| logging_silent           | 101 ns                                                       | 95.9 ns: 1.05x faster                                              |
| sqlglot_normalize        | 126 ms                                                       | 120 ms: 1.05x faster                                               |
| deepcopy                 | 399 us                                                       | 382 us: 1.05x faster                                               |
| tomli_loads              | 2.26 sec                                                     | 2.17 sec: 1.04x faster                                             |
| meteor_contest           | 131 ms                                                       | 126 ms: 1.04x faster                                               |
| bench_thread_pool        | 1.01 ms                                                      | 975 us: 1.04x faster                                               |
| nbody                    | 90.7 ms                                                      | 87.5 ms: 1.04x faster                                              |
| deepcopy_memo            | 38.8 us                                                      | 37.7 us: 1.03x faster                                              |
| raytrace                 | 317 ms                                                       | 308 ms: 1.03x faster                                               |
| crypto_pyaes             | 83.4 ms                                                      | 81.5 ms: 1.02x faster                                              |
| spectral_norm            | 93.3 ms                                                      | 91.3 ms: 1.02x faster                                              |
| sqlglot_optimize         | 59.8 ms                                                      | 58.6 ms: 1.02x faster                                              |
| deepcopy_reduce          | 3.51 us                                                      | 3.45 us: 1.02x faster                                              |
| tornado_http             | 122 ms                                                       | 120 ms: 1.02x faster                                               |
| pyflate                  | 449 ms                                                       | 443 ms: 1.01x faster                                               |
| xml_etree_iterparse      | 104 ms                                                       | 103 ms: 1.01x faster                                               |
| regex_v8                 | 23.9 ms                                                      | 23.8 ms: 1.01x faster                                              |
| scimark_sor              | 111 ms                                                       | 111 ms: 1.00x faster                                               |
| 2to3                     | 288 ms                                                       | 287 ms: 1.00x faster                                               |
| pathlib                  | 19.1 ms                                                      | 19.1 ms: 1.00x slower                                              |
| regex_effbot             | 3.50 ms                                                      | 3.52 ms: 1.01x slower                                              |
| scimark_fft              | 285 ms                                                       | 288 ms: 1.01x slower                                               |
| docutils                 | 2.86 sec                                                     | 2.90 sec: 1.02x slower                                             |
| scimark_monte_carlo      | 68.2 ms                                                      | 69.4 ms: 1.02x slower                                              |
| telco                    | 6.86 ms                                                      | 6.99 ms: 1.02x slower                                              |
| pickle_pure_python       | 319 us                                                       | 326 us: 1.02x slower                                               |
| pprint_pformat           | 1.63 sec                                                     | 1.67 sec: 1.02x slower                                             |
| create_gc_cycles         | 1.61 ms                                                      | 1.66 ms: 1.03x slower                                              |
| coverage                 | 84.8 ms                                                      | 88.0 ms: 1.04x slower                                              |
| scimark_sparse_mat_mult  | 4.05 ms                                                      | 4.21 ms: 1.04x slower                                              |
| xml_etree_process        | 56.5 ms                                                      | 58.9 ms: 1.04x slower                                              |
| pprint_safe_repr         | 784 ms                                                       | 820 ms: 1.05x slower                                               |
| unpickle_list            | 4.53 us                                                      | 4.75 us: 1.05x slower                                              |
| regex_dna                | 227 ms                                                       | 238 ms: 1.05x slower                                               |
| pidigits                 | 251 ms                                                       | 264 ms: 1.05x slower                                               |
| pickle_dict              | 30.8 us                                                      | 32.4 us: 1.05x slower                                              |
| xml_etree_generate       | 80.5 ms                                                      | 85.8 ms: 1.07x slower                                              |
| float                    | 74.2 ms                                                      | 79.6 ms: 1.07x slower                                              |
| pickle                   | 9.64 us                                                      | 10.4 us: 1.08x slower                                              |
| sqlite_synth             | 2.50 us                                                      | 2.72 us: 1.09x slower                                              |
| python_startup           | 10.8 ms                                                      | 11.7 ms: 1.09x slower                                              |
| unpickle                 | 13.4 us                                                      | 14.7 us: 1.10x slower                                              |
| python_startup_no_site   | 7.76 ms                                                      | 8.67 ms: 1.12x slower                                              |
| pickle_list              | 3.83 us                                                      | 4.46 us: 1.17x slower                                              |
| unpack_sequence          | 45.6 ns                                                      | 53.7 ns: 1.18x slower                                              |
| async_generators         | 316 ms                                                       | 381 ms: 1.21x slower                                               |
| dask                     | 410 ms                                                       | 566 ms: 1.38x slower                                               |
| Geometric mean           | (ref)                                                        | 1.07x faster                                                       |

Benchmark hidden because not significant (1): bench_mp_pool
Ignored benchmarks (16) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 99.89% likely to be faster
- 90% likely to have a speedup of 1.02x
- 95% likely to have a speedup of 1.02x
- 99% likely to have a speedup of 1.01x
