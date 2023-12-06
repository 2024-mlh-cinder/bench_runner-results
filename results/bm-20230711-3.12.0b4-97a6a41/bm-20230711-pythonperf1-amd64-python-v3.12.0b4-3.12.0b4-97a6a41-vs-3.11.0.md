
# Results vs. 3.11.0

- fork: python
- ref: v3.12.0b4
- machine: windows-amd64
- commit hash: 97a6a41
- commit date: 2023-07-11
- overall geometric mean: 1.05x faster \*
- HPT reliability: 99.86%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230711-pythonperf1-amd64-python-v3.12.0b4-3.12.0b4-97a6a41 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| docutils       | 1.59 sec                                                    | 1.61 sec: 1.01x slower                                          |
| tornado_http   | 89.9 ms                                                     | 86.3 ms: 1.04x faster                                           |
| Geometric mean | (ref)                                                       | 1.01x faster                                                    |

Benchmark hidden because not significant (1): 2to3

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230711-pythonperf1-amd64-python-v3.12.0b4-3.12.0b4-97a6a41 |
|-------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| async_tree_memoization  | 367 ms                                                      | 333 ms: 1.10x faster                                            |
| async_tree_none         | 314 ms                                                      | 287 ms: 1.09x faster                                            |
| async_tree_io           | 753 ms                                                      | 709 ms: 1.06x faster                                            |
| async_tree_cpu_io_mixed | 495 ms                                                      | 475 ms: 1.04x faster                                            |
| Geometric mean          | (ref)                                                       | 1.07x faster                                                    |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230711-pythonperf1-amd64-python-v3.12.0b4-3.12.0b4-97a6a41 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| float          | 54.4 ms                                                     | 53.6 ms: 1.01x faster                                           |
| pidigits       | 149 ms                                                      | 150 ms: 1.01x slower                                            |
| nbody          | 69.3 ms                                                     | 74.4 ms: 1.07x slower                                           |
| Geometric mean | (ref)                                                       | 1.02x slower                                                    |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230711-pythonperf1-amd64-python-v3.12.0b4-3.12.0b4-97a6a41 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| regex_dna      | 121 ms                                                      | 115 ms: 1.05x faster                                            |
| regex_v8       | 13.7 ms                                                     | 13.0 ms: 1.05x faster                                           |
| regex_compile  | 90.8 ms                                                     | 87.2 ms: 1.04x faster                                           |
| regex_effbot   | 1.52 ms                                                     | 1.57 ms: 1.04x slower                                           |
| Geometric mean | (ref)                                                       | 1.03x faster                                                    |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230711-pythonperf1-amd64-python-v3.12.0b4-3.12.0b4-97a6a41 |
|----------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| json_dumps           | 7.90 ms                                                     | 5.50 ms: 1.44x faster                                           |
| unpickle_pure_python | 152 us                                                      | 135 us: 1.13x faster                                            |
| pickle_pure_python   | 207 us                                                      | 195 us: 1.06x faster                                            |
| xml_etree_parse      | 94.5 ms                                                     | 91.5 ms: 1.03x faster                                           |
| tomli_loads          | 1.42 sec                                                    | 1.41 sec: 1.01x faster                                          |
| xml_etree_process    | 37.0 ms                                                     | 37.4 ms: 1.01x slower                                           |
| xml_etree_iterparse  | 63.0 ms                                                     | 64.6 ms: 1.02x slower                                           |
| pickle_dict          | 17.8 us                                                     | 18.4 us: 1.04x slower                                           |
| json_loads           | 12.9 us                                                     | 13.4 us: 1.04x slower                                           |
| unpickle             | 7.82 us                                                     | 8.23 us: 1.05x slower                                           |
| xml_etree_generate   | 52.2 ms                                                     | 55.0 ms: 1.05x slower                                           |
| pickle               | 6.53 us                                                     | 7.05 us: 1.08x slower                                           |
| pickle_list          | 2.68 us                                                     | 2.89 us: 1.08x slower                                           |
| unpickle_list        | 2.57 us                                                     | 2.90 us: 1.13x slower                                           |
| Geometric mean       | (ref)                                                       | 1.01x faster                                                    |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230711-pythonperf1-amd64-python-v3.12.0b4-3.12.0b4-97a6a41 |
|------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| python_startup         | 18.8 ms                                                     | 19.1 ms: 1.02x slower                                           |
| python_startup_no_site | 15.5 ms                                                     | 16.4 ms: 1.06x slower                                           |
| Geometric mean         | (ref)                                                       | 1.04x slower                                                    |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230711-pythonperf1-amd64-python-v3.12.0b4-3.12.0b4-97a6a41 |
|-----------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| mako      | 7.55 ms                                                     | 6.86 ms: 1.10x faster                                           |

All benchmarks:
===============

| Benchmark                | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230711-pythonperf1-amd64-python-v3.12.0b4-3.12.0b4-97a6a41 |
|--------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| typing_runtime_protocols | 320 us                                                      | 93.3 us: 3.43x faster                                           |
| generators               | 34.0 ms                                                     | 22.2 ms: 1.53x faster                                           |
| json_dumps               | 7.90 ms                                                     | 5.50 ms: 1.44x faster                                           |
| asyncio_tcp              | 614 ms                                                      | 474 ms: 1.30x faster                                            |
| richards_super           | 37.9 ms                                                     | 30.2 ms: 1.25x faster                                           |
| deltablue                | 2.63 ms                                                     | 2.10 ms: 1.25x faster                                           |
| logging_silent           | 70.7 ns                                                     | 59.4 ns: 1.19x faster                                           |
| sqlglot_parse            | 939 us                                                      | 802 us: 1.17x faster                                            |
| mdp                      | 1.73 sec                                                    | 1.49 sec: 1.16x faster                                          |
| richards                 | 30.8 ms                                                     | 26.8 ms: 1.15x faster                                           |
| raytrace                 | 211 ms                                                      | 186 ms: 1.14x faster                                            |
| sqlglot_transpile        | 1.15 ms                                                     | 1.01 ms: 1.13x faster                                           |
| unpickle_pure_python     | 152 us                                                      | 135 us: 1.13x faster                                            |
| go                       | 98.8 ms                                                     | 88.2 ms: 1.12x faster                                           |
| comprehensions           | 15.6 us                                                     | 14.0 us: 1.11x faster                                           |
| async_tree_memoization   | 367 ms                                                      | 333 ms: 1.10x faster                                            |
| mako                     | 7.55 ms                                                     | 6.86 ms: 1.10x faster                                           |
| mypy2                    | 226 ms                                                      | 206 ms: 1.10x faster                                            |
| async_tree_none          | 314 ms                                                      | 287 ms: 1.09x faster                                            |
| hexiom                   | 4.51 ms                                                     | 4.14 ms: 1.09x faster                                           |
| scimark_lu               | 62.3 ms                                                     | 57.6 ms: 1.08x faster                                           |
| chaos                    | 46.8 ms                                                     | 43.3 ms: 1.08x faster                                           |
| spectral_norm            | 69.9 ms                                                     | 65.1 ms: 1.07x faster                                           |
| nqueens                  | 66.1 ms                                                     | 61.6 ms: 1.07x faster                                           |
| async_tree_io            | 753 ms                                                      | 709 ms: 1.06x faster                                            |
| pickle_pure_python       | 207 us                                                      | 195 us: 1.06x faster                                            |
| pycparser                | 705 ms                                                      | 667 ms: 1.06x faster                                            |
| sqlglot_normalize        | 191 ms                                                      | 181 ms: 1.05x faster                                            |
| regex_dna                | 121 ms                                                      | 115 ms: 1.05x faster                                            |
| regex_v8                 | 13.7 ms                                                     | 13.0 ms: 1.05x faster                                           |
| unpack_sequence          | 47.0 ns                                                     | 44.7 ns: 1.05x faster                                           |
| deepcopy                 | 242 us                                                      | 231 us: 1.05x faster                                            |
| dulwich_log              | 44.1 ms                                                     | 42.1 ms: 1.05x faster                                           |
| coroutines               | 14.7 ms                                                     | 14.0 ms: 1.04x faster                                           |
| async_tree_cpu_io_mixed  | 495 ms                                                      | 475 ms: 1.04x faster                                            |
| regex_compile            | 90.8 ms                                                     | 87.2 ms: 1.04x faster                                           |
| tornado_http             | 89.9 ms                                                     | 86.3 ms: 1.04x faster                                           |
| sqlglot_optimize         | 35.1 ms                                                     | 33.7 ms: 1.04x faster                                           |
| scimark_monte_carlo      | 44.6 ms                                                     | 43.0 ms: 1.04x faster                                           |
| xml_etree_parse          | 94.5 ms                                                     | 91.5 ms: 1.03x faster                                           |
| crypto_pyaes             | 48.2 ms                                                     | 46.8 ms: 1.03x faster                                           |
| sqlite_synth             | 1.79 us                                                     | 1.75 us: 1.03x faster                                           |
| logging_format           | 7.06 us                                                     | 6.88 us: 1.03x faster                                           |
| deepcopy_memo            | 25.5 us                                                     | 24.9 us: 1.02x faster                                           |
| pyflate                  | 305 ms                                                      | 298 ms: 1.02x faster                                            |
| logging_simple           | 6.60 us                                                     | 6.46 us: 1.02x faster                                           |
| scimark_sparse_mat_mult  | 2.59 ms                                                     | 2.53 ms: 1.02x faster                                           |
| scimark_fft              | 181 ms                                                      | 177 ms: 1.02x faster                                            |
| deepcopy_reduce          | 2.07 us                                                     | 2.03 us: 1.02x faster                                           |
| meteor_contest           | 75.0 ms                                                     | 73.8 ms: 1.02x faster                                           |
| pprint_pformat           | 1.06 sec                                                    | 1.05 sec: 1.02x faster                                          |
| float                    | 54.4 ms                                                     | 53.6 ms: 1.01x faster                                           |
| pprint_safe_repr         | 519 ms                                                      | 514 ms: 1.01x faster                                            |
| tomli_loads              | 1.42 sec                                                    | 1.41 sec: 1.01x faster                                          |
| xml_etree_process        | 37.0 ms                                                     | 37.4 ms: 1.01x slower                                           |
| docutils                 | 1.59 sec                                                    | 1.61 sec: 1.01x slower                                          |
| pidigits                 | 149 ms                                                      | 150 ms: 1.01x slower                                            |
| python_startup           | 18.8 ms                                                     | 19.1 ms: 1.02x slower                                           |
| gc_traversal             | 1.46 ms                                                     | 1.49 ms: 1.02x slower                                           |
| xml_etree_iterparse      | 63.0 ms                                                     | 64.6 ms: 1.02x slower                                           |
| create_gc_cycles         | 706 us                                                      | 724 us: 1.03x slower                                            |
| regex_effbot             | 1.52 ms                                                     | 1.57 ms: 1.04x slower                                           |
| pickle_dict              | 17.8 us                                                     | 18.4 us: 1.04x slower                                           |
| json_loads               | 12.9 us                                                     | 13.4 us: 1.04x slower                                           |
| telco                    | 3.93 ms                                                     | 4.11 ms: 1.04x slower                                           |
| unpickle                 | 7.82 us                                                     | 8.23 us: 1.05x slower                                           |
| xml_etree_generate       | 52.2 ms                                                     | 55.0 ms: 1.05x slower                                           |
| python_startup_no_site   | 15.5 ms                                                     | 16.4 ms: 1.06x slower                                           |
| bench_mp_pool            | 61.1 ms                                                     | 65.4 ms: 1.07x slower                                           |
| nbody                    | 69.3 ms                                                     | 74.4 ms: 1.07x slower                                           |
| pickle                   | 6.53 us                                                     | 7.05 us: 1.08x slower                                           |
| pickle_list              | 2.68 us                                                     | 2.89 us: 1.08x slower                                           |
| scimark_sor              | 76.4 ms                                                     | 82.6 ms: 1.08x slower                                           |
| pathlib                  | 69.4 ms                                                     | 78.0 ms: 1.13x slower                                           |
| unpickle_list            | 2.57 us                                                     | 2.90 us: 1.13x slower                                           |
| coverage                 | 43.0 ms                                                     | 52.7 ms: 1.23x slower                                           |
| async_generators         | 181 ms                                                      | 230 ms: 1.27x slower                                            |
| dask                     | 262 ms                                                      | 359 ms: 1.37x slower                                            |
| Geometric mean           | (ref)                                                       | 1.05x faster                                                    |

Benchmark hidden because not significant (6): json, bench_thread_pool, aiohttp, fannkuch, 2to3, asyncio_tcp_ssl
Ignored benchmarks (18) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 99.86% likely to be faster
- 90% likely to have a speedup of 1.01x
- 95% likely to have a speedup of 1.01x
- 99% likely to have a speedup of 1.00x
