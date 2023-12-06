
# Results vs. 3.10.4

- fork: python
- ref: v3.12.0b2
- machine: windows-amd64
- commit hash: e6c0efa
- commit date: 2023-06-06
- overall geometric mean: 1.17x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.09x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230606-pythonperf1-amd64-python-v3.12.0b2-3.12.0b2-e6c0efa |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| 2to3           | 239 ms                                                      | 216 ms: 1.11x faster                                            |
| docutils       | 1.88 sec                                                    | 1.67 sec: 1.13x faster                                          |
| tornado_http   | 106 ms                                                      | 88.5 ms: 1.19x faster                                           |
| Geometric mean | (ref)                                                       | 1.14x faster                                                    |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230606-pythonperf1-amd64-python-v3.12.0b2-3.12.0b2-e6c0efa |
|-------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| async_tree_memoization  | 505 ms                                                      | 347 ms: 1.45x faster                                            |
| async_tree_io           | 1.07 sec                                                    | 744 ms: 1.44x faster                                            |
| async_tree_none         | 424 ms                                                      | 298 ms: 1.42x faster                                            |
| async_tree_cpu_io_mixed | 617 ms                                                      | 493 ms: 1.25x faster                                            |
| Geometric mean          | (ref)                                                       | 1.39x faster                                                    |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230606-pythonperf1-amd64-python-v3.12.0b2-3.12.0b2-e6c0efa |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| float          | 61.7 ms                                                     | 55.2 ms: 1.12x faster                                           |
| nbody          | 71.0 ms                                                     | 68.3 ms: 1.04x faster                                           |
| pidigits       | 146 ms                                                      | 153 ms: 1.05x slower                                            |
| Geometric mean | (ref)                                                       | 1.04x faster                                                    |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230606-pythonperf1-amd64-python-v3.12.0b2-3.12.0b2-e6c0efa |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| regex_compile  | 102 ms                                                      | 87.9 ms: 1.16x faster                                           |
| regex_v8       | 15.0 ms                                                     | 13.9 ms: 1.08x faster                                           |
| regex_dna      | 129 ms                                                      | 125 ms: 1.04x faster                                            |
| regex_effbot   | 1.56 ms                                                     | 1.63 ms: 1.04x slower                                           |
| Geometric mean | (ref)                                                       | 1.06x faster                                                    |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230606-pythonperf1-amd64-python-v3.12.0b2-3.12.0b2-e6c0efa |
|----------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| json_dumps           | 8.77 ms                                                     | 5.59 ms: 1.57x faster                                           |
| pickle_pure_python   | 259 us                                                      | 197 us: 1.32x faster                                            |
| unpickle_pure_python | 177 us                                                      | 135 us: 1.32x faster                                            |
| tomli_loads          | 1.65 sec                                                    | 1.37 sec: 1.20x faster                                          |
| xml_etree_process    | 43.1 ms                                                     | 38.3 ms: 1.12x faster                                           |
| unpickle             | 9.11 us                                                     | 8.48 us: 1.07x faster                                           |
| xml_etree_parse      | 96.8 ms                                                     | 91.6 ms: 1.06x faster                                           |
| json_loads           | 14.2 us                                                     | 13.7 us: 1.04x faster                                           |
| xml_etree_iterparse  | 64.5 ms                                                     | 65.0 ms: 1.01x slower                                           |
| pickle               | 6.87 us                                                     | 7.11 us: 1.03x slower                                           |
| xml_etree_generate   | 54.5 ms                                                     | 57.0 ms: 1.04x slower                                           |
| pickle_list          | 2.69 us                                                     | 2.85 us: 1.06x slower                                           |
| pickle_dict          | 17.1 us                                                     | 18.2 us: 1.06x slower                                           |
| unpickle_list        | 2.68 us                                                     | 2.90 us: 1.08x slower                                           |
| Geometric mean       | (ref)                                                       | 1.09x faster                                                    |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230606-pythonperf1-amd64-python-v3.12.0b2-3.12.0b2-e6c0efa |
|------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| python_startup         | 19.7 ms                                                     | 20.2 ms: 1.03x slower                                           |
| python_startup_no_site | 15.3 ms                                                     | 17.4 ms: 1.13x slower                                           |
| Geometric mean         | (ref)                                                       | 1.08x slower                                                    |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230606-pythonperf1-amd64-python-v3.12.0b2-3.12.0b2-e6c0efa |
|-----------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| mako      | 8.98 ms                                                     | 7.05 ms: 1.27x faster                                           |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230606-pythonperf1-amd64-python-v3.12.0b2-3.12.0b2-e6c0efa |
|--------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| typing_runtime_protocols | 337 us                                                      | 95.0 us: 3.55x faster                                           |
| deltablue                | 4.12 ms                                                     | 2.08 ms: 1.98x faster                                           |
| richards_super           | 50.3 ms                                                     | 29.2 ms: 1.72x faster                                           |
| mypy2                    | 347 ms                                                      | 217 ms: 1.60x faster                                            |
| richards                 | 40.6 ms                                                     | 25.7 ms: 1.58x faster                                           |
| logging_silent           | 93.4 ns                                                     | 59.4 ns: 1.57x faster                                           |
| json_dumps               | 8.77 ms                                                     | 5.59 ms: 1.57x faster                                           |
| go                       | 135 ms                                                      | 87.8 ms: 1.54x faster                                           |
| sqlglot_parse            | 1.20 ms                                                     | 799 us: 1.51x faster                                            |
| asyncio_tcp              | 717 ms                                                      | 478 ms: 1.50x faster                                            |
| scimark_lu               | 84.0 ms                                                     | 56.8 ms: 1.48x faster                                           |
| async_tree_memoization   | 505 ms                                                      | 347 ms: 1.45x faster                                            |
| async_tree_io            | 1.07 sec                                                    | 744 ms: 1.44x faster                                            |
| sqlglot_transpile        | 1.45 ms                                                     | 1.01 ms: 1.43x faster                                           |
| async_tree_none          | 424 ms                                                      | 298 ms: 1.42x faster                                            |
| raytrace                 | 266 ms                                                      | 187 ms: 1.42x faster                                            |
| generators               | 31.8 ms                                                     | 22.4 ms: 1.42x faster                                           |
| hexiom                   | 5.59 ms                                                     | 4.00 ms: 1.40x faster                                           |
| chaos                    | 59.5 ms                                                     | 42.8 ms: 1.39x faster                                           |
| scimark_monte_carlo      | 58.0 ms                                                     | 42.6 ms: 1.36x faster                                           |
| scimark_sor              | 105 ms                                                      | 77.3 ms: 1.36x faster                                           |
| pyflate                  | 402 ms                                                      | 296 ms: 1.36x faster                                            |
| crypto_pyaes             | 63.1 ms                                                     | 47.2 ms: 1.34x faster                                           |
| pycparser                | 905 ms                                                      | 680 ms: 1.33x faster                                            |
| pickle_pure_python       | 259 us                                                      | 197 us: 1.32x faster                                            |
| unpickle_pure_python     | 177 us                                                      | 135 us: 1.32x faster                                            |
| mako                     | 8.98 ms                                                     | 7.05 ms: 1.27x faster                                           |
| async_tree_cpu_io_mixed  | 617 ms                                                      | 493 ms: 1.25x faster                                            |
| mdp                      | 1.71 sec                                                    | 1.38 sec: 1.24x faster                                          |
| deepcopy_memo            | 29.0 us                                                     | 23.8 us: 1.22x faster                                           |
| tomli_loads              | 1.65 sec                                                    | 1.37 sec: 1.20x faster                                          |
| spectral_norm            | 78.9 ms                                                     | 66.0 ms: 1.20x faster                                           |
| tornado_http             | 106 ms                                                      | 88.5 ms: 1.19x faster                                           |
| pprint_pformat           | 1.22 sec                                                    | 1.03 sec: 1.18x faster                                          |
| sqlglot_optimize         | 39.4 ms                                                     | 33.8 ms: 1.17x faster                                           |
| pprint_safe_repr         | 594 ms                                                      | 510 ms: 1.17x faster                                            |
| regex_compile            | 102 ms                                                      | 87.9 ms: 1.16x faster                                           |
| comprehensions           | 16.6 us                                                     | 14.4 us: 1.15x faster                                           |
| sqlglot_normalize        | 207 ms                                                      | 183 ms: 1.13x faster                                            |
| docutils                 | 1.88 sec                                                    | 1.67 sec: 1.13x faster                                          |
| xml_etree_process        | 43.1 ms                                                     | 38.3 ms: 1.12x faster                                           |
| float                    | 61.7 ms                                                     | 55.2 ms: 1.12x faster                                           |
| nqueens                  | 68.3 ms                                                     | 61.1 ms: 1.12x faster                                           |
| coroutines               | 15.5 ms                                                     | 13.9 ms: 1.11x faster                                           |
| 2to3                     | 239 ms                                                      | 216 ms: 1.11x faster                                            |
| dulwich_log              | 48.6 ms                                                     | 44.2 ms: 1.10x faster                                           |
| aiohttp                  | 961 us                                                      | 879 us: 1.09x faster                                            |
| regex_v8                 | 15.0 ms                                                     | 13.9 ms: 1.08x faster                                           |
| scimark_fft              | 187 ms                                                      | 174 ms: 1.08x faster                                            |
| create_gc_cycles         | 800 us                                                      | 744 us: 1.08x faster                                            |
| deepcopy                 | 259 us                                                      | 241 us: 1.08x faster                                            |
| fannkuch                 | 258 ms                                                      | 240 ms: 1.07x faster                                            |
| unpickle                 | 9.11 us                                                     | 8.48 us: 1.07x faster                                           |
| sqlite_synth             | 1.90 us                                                     | 1.79 us: 1.06x faster                                           |
| deepcopy_reduce          | 2.22 us                                                     | 2.10 us: 1.06x faster                                           |
| xml_etree_parse          | 96.8 ms                                                     | 91.6 ms: 1.06x faster                                           |
| scimark_sparse_mat_mult  | 2.67 ms                                                     | 2.52 ms: 1.06x faster                                           |
| bench_thread_pool        | 913 us                                                      | 867 us: 1.05x faster                                            |
| nbody                    | 71.0 ms                                                     | 68.3 ms: 1.04x faster                                           |
| regex_dna                | 129 ms                                                      | 125 ms: 1.04x faster                                            |
| json_loads               | 14.2 us                                                     | 13.7 us: 1.04x faster                                           |
| json                     | 3.10 ms                                                     | 2.99 ms: 1.04x faster                                           |
| unpack_sequence          | 40.0 ns                                                     | 39.1 ns: 1.02x faster                                           |
| xml_etree_iterparse      | 64.5 ms                                                     | 65.0 ms: 1.01x slower                                           |
| python_startup           | 19.7 ms                                                     | 20.2 ms: 1.03x slower                                           |
| pickle                   | 6.87 us                                                     | 7.11 us: 1.03x slower                                           |
| regex_effbot             | 1.56 ms                                                     | 1.63 ms: 1.04x slower                                           |
| logging_format           | 6.73 us                                                     | 7.01 us: 1.04x slower                                           |
| logging_simple           | 6.28 us                                                     | 6.54 us: 1.04x slower                                           |
| xml_etree_generate       | 54.5 ms                                                     | 57.0 ms: 1.04x slower                                           |
| pidigits                 | 146 ms                                                      | 153 ms: 1.05x slower                                            |
| pickle_list              | 2.69 us                                                     | 2.85 us: 1.06x slower                                           |
| pickle_dict              | 17.1 us                                                     | 18.2 us: 1.06x slower                                           |
| async_generators         | 219 ms                                                      | 233 ms: 1.07x slower                                            |
| unpickle_list            | 2.68 us                                                     | 2.90 us: 1.08x slower                                           |
| telco                    | 3.82 ms                                                     | 4.15 ms: 1.09x slower                                           |
| gc_traversal             | 1.40 ms                                                     | 1.53 ms: 1.09x slower                                           |
| python_startup_no_site   | 15.3 ms                                                     | 17.4 ms: 1.13x slower                                           |
| bench_mp_pool            | 59.9 ms                                                     | 68.0 ms: 1.13x slower                                           |
| pathlib                  | 72.8 ms                                                     | 83.2 ms: 1.14x slower                                           |
| dask                     | 305 ms                                                      | 373 ms: 1.22x slower                                            |
| coverage                 | 38.4 ms                                                     | 52.5 ms: 1.37x slower                                           |
| Geometric mean           | (ref)                                                       | 1.17x faster                                                    |

Benchmark hidden because not significant (2): asyncio_tcp_ssl, meteor_contest
Ignored benchmarks (14) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120.json: chameleon, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.12x
- 95% likely to have a speedup of 1.11x
- 99% likely to have a speedup of 1.09x
