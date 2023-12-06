
# Results vs. 3.11.0

- fork: python
- ref: v3.12.0b2
- machine: windows-amd64
- commit hash: e6c0efa
- commit date: 2023-06-06
- overall geometric mean: 1.04x faster \*
- HPT reliability: 97.74%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230606-pythonperf1-amd64-python-v3.12.0b2-3.12.0b2-e6c0efa |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| 2to3           | 207 ms                                                      | 216 ms: 1.04x slower                                            |
| docutils       | 1.59 sec                                                    | 1.67 sec: 1.05x slower                                          |
| tornado_http   | 89.9 ms                                                     | 88.5 ms: 1.02x faster                                           |
| Geometric mean | (ref)                                                       | 1.02x slower                                                    |

Benchmarks with tag 'asyncio':
==============================

| Benchmark              | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230606-pythonperf1-amd64-python-v3.12.0b2-3.12.0b2-e6c0efa |
|------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| async_tree_memoization | 367 ms                                                      | 347 ms: 1.06x faster                                            |
| async_tree_none        | 314 ms                                                      | 298 ms: 1.05x faster                                            |
| async_tree_io          | 753 ms                                                      | 744 ms: 1.01x faster                                            |
| Geometric mean         | (ref)                                                       | 1.03x faster                                                    |

Benchmark hidden because not significant (1): async_tree_cpu_io_mixed

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230606-pythonperf1-amd64-python-v3.12.0b2-3.12.0b2-e6c0efa |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| nbody          | 69.3 ms                                                     | 68.3 ms: 1.01x faster                                           |
| float          | 54.4 ms                                                     | 55.2 ms: 1.01x slower                                           |
| pidigits       | 149 ms                                                      | 153 ms: 1.03x slower                                            |
| Geometric mean | (ref)                                                       | 1.01x slower                                                    |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230606-pythonperf1-amd64-python-v3.12.0b2-3.12.0b2-e6c0efa |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| regex_compile  | 90.8 ms                                                     | 87.9 ms: 1.03x faster                                           |
| regex_v8       | 13.7 ms                                                     | 13.9 ms: 1.02x slower                                           |
| regex_dna      | 121 ms                                                      | 125 ms: 1.03x slower                                            |
| regex_effbot   | 1.52 ms                                                     | 1.63 ms: 1.07x slower                                           |
| Geometric mean | (ref)                                                       | 1.02x slower                                                    |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230606-pythonperf1-amd64-python-v3.12.0b2-3.12.0b2-e6c0efa |
|----------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| json_dumps           | 7.90 ms                                                     | 5.59 ms: 1.41x faster                                           |
| unpickle_pure_python | 152 us                                                      | 135 us: 1.13x faster                                            |
| pickle_pure_python   | 207 us                                                      | 197 us: 1.05x faster                                            |
| tomli_loads          | 1.42 sec                                                    | 1.37 sec: 1.04x faster                                          |
| xml_etree_parse      | 94.5 ms                                                     | 91.6 ms: 1.03x faster                                           |
| pickle_dict          | 17.8 us                                                     | 18.2 us: 1.02x slower                                           |
| xml_etree_iterparse  | 63.0 ms                                                     | 65.0 ms: 1.03x slower                                           |
| xml_etree_process    | 37.0 ms                                                     | 38.3 ms: 1.04x slower                                           |
| pickle_list          | 2.68 us                                                     | 2.85 us: 1.06x slower                                           |
| json_loads           | 12.9 us                                                     | 13.7 us: 1.06x slower                                           |
| unpickle             | 7.82 us                                                     | 8.48 us: 1.08x slower                                           |
| pickle               | 6.53 us                                                     | 7.11 us: 1.09x slower                                           |
| xml_etree_generate   | 52.2 ms                                                     | 57.0 ms: 1.09x slower                                           |
| unpickle_list        | 2.57 us                                                     | 2.90 us: 1.13x slower                                           |
| Geometric mean       | (ref)                                                       | 1.00x faster                                                    |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230606-pythonperf1-amd64-python-v3.12.0b2-3.12.0b2-e6c0efa |
|------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| python_startup         | 18.8 ms                                                     | 20.2 ms: 1.07x slower                                           |
| python_startup_no_site | 15.5 ms                                                     | 17.4 ms: 1.12x slower                                           |
| Geometric mean         | (ref)                                                       | 1.10x slower                                                    |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230606-pythonperf1-amd64-python-v3.12.0b2-3.12.0b2-e6c0efa |
|-----------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| mako      | 7.55 ms                                                     | 7.05 ms: 1.07x faster                                           |

All benchmarks:
===============

| Benchmark                | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230606-pythonperf1-amd64-python-v3.12.0b2-3.12.0b2-e6c0efa |
|--------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| typing_runtime_protocols | 320 us                                                      | 95.0 us: 3.37x faster                                           |
| generators               | 34.0 ms                                                     | 22.4 ms: 1.51x faster                                           |
| json_dumps               | 7.90 ms                                                     | 5.59 ms: 1.41x faster                                           |
| richards_super           | 37.9 ms                                                     | 29.2 ms: 1.30x faster                                           |
| asyncio_tcp              | 614 ms                                                      | 478 ms: 1.28x faster                                            |
| deltablue                | 2.63 ms                                                     | 2.08 ms: 1.26x faster                                           |
| mdp                      | 1.73 sec                                                    | 1.38 sec: 1.25x faster                                          |
| unpack_sequence          | 47.0 ns                                                     | 39.1 ns: 1.20x faster                                           |
| richards                 | 30.8 ms                                                     | 25.7 ms: 1.20x faster                                           |
| logging_silent           | 70.7 ns                                                     | 59.4 ns: 1.19x faster                                           |
| sqlglot_parse            | 939 us                                                      | 799 us: 1.18x faster                                            |
| sqlglot_transpile        | 1.15 ms                                                     | 1.01 ms: 1.14x faster                                           |
| unpickle_pure_python     | 152 us                                                      | 135 us: 1.13x faster                                            |
| hexiom                   | 4.51 ms                                                     | 4.00 ms: 1.13x faster                                           |
| raytrace                 | 211 ms                                                      | 187 ms: 1.13x faster                                            |
| go                       | 98.8 ms                                                     | 87.8 ms: 1.13x faster                                           |
| scimark_lu               | 62.3 ms                                                     | 56.8 ms: 1.10x faster                                           |
| chaos                    | 46.8 ms                                                     | 42.8 ms: 1.09x faster                                           |
| comprehensions           | 15.6 us                                                     | 14.4 us: 1.08x faster                                           |
| nqueens                  | 66.1 ms                                                     | 61.1 ms: 1.08x faster                                           |
| mako                     | 7.55 ms                                                     | 7.05 ms: 1.07x faster                                           |
| deepcopy_memo            | 25.5 us                                                     | 23.8 us: 1.07x faster                                           |
| spectral_norm            | 69.9 ms                                                     | 66.0 ms: 1.06x faster                                           |
| async_tree_memoization   | 367 ms                                                      | 347 ms: 1.06x faster                                            |
| coroutines               | 14.7 ms                                                     | 13.9 ms: 1.05x faster                                           |
| pickle_pure_python       | 207 us                                                      | 197 us: 1.05x faster                                            |
| async_tree_none          | 314 ms                                                      | 298 ms: 1.05x faster                                            |
| sqlglot_normalize        | 191 ms                                                      | 183 ms: 1.05x faster                                            |
| scimark_monte_carlo      | 44.6 ms                                                     | 42.6 ms: 1.05x faster                                           |
| mypy2                    | 226 ms                                                      | 217 ms: 1.05x faster                                            |
| scimark_fft              | 181 ms                                                      | 174 ms: 1.04x faster                                            |
| tomli_loads              | 1.42 sec                                                    | 1.37 sec: 1.04x faster                                          |
| sqlglot_optimize         | 35.1 ms                                                     | 33.8 ms: 1.04x faster                                           |
| pycparser                | 705 ms                                                      | 680 ms: 1.04x faster                                            |
| fannkuch                 | 248 ms                                                      | 240 ms: 1.03x faster                                            |
| regex_compile            | 90.8 ms                                                     | 87.9 ms: 1.03x faster                                           |
| xml_etree_parse          | 94.5 ms                                                     | 91.6 ms: 1.03x faster                                           |
| pyflate                  | 305 ms                                                      | 296 ms: 1.03x faster                                            |
| pprint_pformat           | 1.06 sec                                                    | 1.03 sec: 1.03x faster                                          |
| scimark_sparse_mat_mult  | 2.59 ms                                                     | 2.52 ms: 1.03x faster                                           |
| crypto_pyaes             | 48.2 ms                                                     | 47.2 ms: 1.02x faster                                           |
| pprint_safe_repr         | 519 ms                                                      | 510 ms: 1.02x faster                                            |
| tornado_http             | 89.9 ms                                                     | 88.5 ms: 1.02x faster                                           |
| meteor_contest           | 75.0 ms                                                     | 73.9 ms: 1.02x faster                                           |
| nbody                    | 69.3 ms                                                     | 68.3 ms: 1.01x faster                                           |
| async_tree_io            | 753 ms                                                      | 744 ms: 1.01x faster                                            |
| logging_simple           | 6.60 us                                                     | 6.54 us: 1.01x faster                                           |
| logging_format           | 7.06 us                                                     | 7.01 us: 1.01x faster                                           |
| deepcopy                 | 242 us                                                      | 241 us: 1.00x faster                                            |
| sqlite_synth             | 1.79 us                                                     | 1.79 us: 1.00x faster                                           |
| dulwich_log              | 44.1 ms                                                     | 44.2 ms: 1.00x slower                                           |
| deepcopy_reduce          | 2.07 us                                                     | 2.10 us: 1.01x slower                                           |
| scimark_sor              | 76.4 ms                                                     | 77.3 ms: 1.01x slower                                           |
| float                    | 54.4 ms                                                     | 55.2 ms: 1.01x slower                                           |
| regex_v8                 | 13.7 ms                                                     | 13.9 ms: 1.02x slower                                           |
| pickle_dict              | 17.8 us                                                     | 18.2 us: 1.02x slower                                           |
| bench_thread_pool        | 847 us                                                      | 867 us: 1.02x slower                                            |
| regex_dna                | 121 ms                                                      | 125 ms: 1.03x slower                                            |
| aiohttp                  | 854 us                                                      | 879 us: 1.03x slower                                            |
| xml_etree_iterparse      | 63.0 ms                                                     | 65.0 ms: 1.03x slower                                           |
| pidigits                 | 149 ms                                                      | 153 ms: 1.03x slower                                            |
| xml_etree_process        | 37.0 ms                                                     | 38.3 ms: 1.04x slower                                           |
| 2to3                     | 207 ms                                                      | 216 ms: 1.04x slower                                            |
| gc_traversal             | 1.46 ms                                                     | 1.53 ms: 1.05x slower                                           |
| docutils                 | 1.59 sec                                                    | 1.67 sec: 1.05x slower                                          |
| telco                    | 3.93 ms                                                     | 4.15 ms: 1.05x slower                                           |
| create_gc_cycles         | 706 us                                                      | 744 us: 1.05x slower                                            |
| pickle_list              | 2.68 us                                                     | 2.85 us: 1.06x slower                                           |
| json_loads               | 12.9 us                                                     | 13.7 us: 1.06x slower                                           |
| regex_effbot             | 1.52 ms                                                     | 1.63 ms: 1.07x slower                                           |
| python_startup           | 18.8 ms                                                     | 20.2 ms: 1.07x slower                                           |
| unpickle                 | 7.82 us                                                     | 8.48 us: 1.08x slower                                           |
| pickle                   | 6.53 us                                                     | 7.11 us: 1.09x slower                                           |
| xml_etree_generate       | 52.2 ms                                                     | 57.0 ms: 1.09x slower                                           |
| bench_mp_pool            | 61.1 ms                                                     | 68.0 ms: 1.11x slower                                           |
| python_startup_no_site   | 15.5 ms                                                     | 17.4 ms: 1.12x slower                                           |
| unpickle_list            | 2.57 us                                                     | 2.90 us: 1.13x slower                                           |
| pathlib                  | 69.4 ms                                                     | 83.2 ms: 1.20x slower                                           |
| coverage                 | 43.0 ms                                                     | 52.5 ms: 1.22x slower                                           |
| async_generators         | 181 ms                                                      | 233 ms: 1.29x slower                                            |
| dask                     | 262 ms                                                      | 373 ms: 1.42x slower                                            |
| Geometric mean           | (ref)                                                       | 1.04x faster                                                    |

Benchmark hidden because not significant (3): async_tree_cpu_io_mixed, json, asyncio_tcp_ssl
Ignored benchmarks (18) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 97.74% likely to be faster
- 90% likely to have a speedup of 1.01x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
