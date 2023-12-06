
# Results vs. 3.10.4

- fork: python
- ref: v3.12.0rc1
- machine: windows-amd64
- commit hash: 63bcd91
- commit date: 2023-08-05
- overall geometric mean: 1.19x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.11x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230805-pythonperf1-amd64-python-v3.12.0rc1-3.12.0rc1-63bcd91 |
|----------------|:-----------------------------------------------------------:|:-----------------------------------------------------------------:|
| 2to3           | 237 ms                                                      | 211 ms: 1.12x faster                                              |
| docutils       | 1.89 sec                                                    | 1.60 sec: 1.18x faster                                            |
| tornado_http   | 109 ms                                                      | 87.2 ms: 1.25x faster                                             |
| Geometric mean | (ref)                                                       | 1.18x faster                                                      |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230805-pythonperf1-amd64-python-v3.12.0rc1-3.12.0rc1-63bcd91 |
|----------------|:-----------------------------------------------------------:|:-----------------------------------------------------------------:|
| float          | 60.2 ms                                                     | 53.8 ms: 1.12x faster                                             |
| nbody          | 69.3 ms                                                     | 68.7 ms: 1.01x faster                                             |
| pidigits       | 145 ms                                                      | 147 ms: 1.01x slower                                              |
| Geometric mean | (ref)                                                       | 1.04x faster                                                      |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230805-pythonperf1-amd64-python-v3.12.0rc1-3.12.0rc1-63bcd91 |
|----------------|:-----------------------------------------------------------:|:-----------------------------------------------------------------:|
| regex_compile  | 103 ms                                                      | 85.8 ms: 1.21x faster                                             |
| regex_v8       | 15.0 ms                                                     | 13.8 ms: 1.09x faster                                             |
| regex_dna      | 132 ms                                                      | 121 ms: 1.09x faster                                              |
| regex_effbot   | 1.66 ms                                                     | 1.61 ms: 1.03x faster                                             |
| Geometric mean | (ref)                                                       | 1.10x faster                                                      |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230805-pythonperf1-amd64-python-v3.12.0rc1-3.12.0rc1-63bcd91 |
|----------------------|:-----------------------------------------------------------:|:-----------------------------------------------------------------:|
| json_dumps           | 8.50 ms                                                     | 5.59 ms: 1.52x faster                                             |
| pickle_pure_python   | 257 us                                                      | 191 us: 1.35x faster                                              |
| unpickle_pure_python | 171 us                                                      | 133 us: 1.29x faster                                              |
| tomli_loads          | 1.62 sec                                                    | 1.35 sec: 1.20x faster                                            |
| xml_etree_process    | 43.4 ms                                                     | 37.6 ms: 1.16x faster                                             |
| xml_etree_parse      | 102 ms                                                      | 91.3 ms: 1.11x faster                                             |
| unpickle             | 9.17 us                                                     | 8.38 us: 1.09x faster                                             |
| json_loads           | 14.2 us                                                     | 13.5 us: 1.05x faster                                             |
| xml_etree_generate   | 54.5 ms                                                     | 55.1 ms: 1.01x slower                                             |
| pickle               | 6.80 us                                                     | 6.98 us: 1.03x slower                                             |
| pickle_dict          | 16.9 us                                                     | 18.3 us: 1.08x slower                                             |
| pickle_list          | 2.59 us                                                     | 2.87 us: 1.11x slower                                             |
| Geometric mean       | (ref)                                                       | 1.10x faster                                                      |

Benchmark hidden because not significant (2): unpickle_list, xml_etree_iterparse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230805-pythonperf1-amd64-python-v3.12.0rc1-3.12.0rc1-63bcd91 |
|------------------------|:-----------------------------------------------------------:|:-----------------------------------------------------------------:|
| python_startup         | 20.0 ms                                                     | 18.7 ms: 1.07x faster                                             |
| python_startup_no_site | 15.5 ms                                                     | 16.1 ms: 1.04x slower                                             |
| Geometric mean         | (ref)                                                       | 1.01x faster                                                      |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230805-pythonperf1-amd64-python-v3.12.0rc1-3.12.0rc1-63bcd91 |
|-----------|:-----------------------------------------------------------:|:-----------------------------------------------------------------:|
| mako      | 8.80 ms                                                     | 6.82 ms: 1.29x faster                                             |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230805-pythonperf1-amd64-python-v3.12.0rc1-3.12.0rc1-63bcd91 |
|--------------------------|:-----------------------------------------------------------:|:-----------------------------------------------------------------:|
| typing_runtime_protocols | 325 us                                                      | 93.3 us: 3.48x faster                                             |
| deltablue                | 4.17 ms                                                     | 2.13 ms: 1.96x faster                                             |
| richards_super           | 51.7 ms                                                     | 29.5 ms: 1.75x faster                                             |
| mypy2                    | 352 ms                                                      | 208 ms: 1.70x faster                                              |
| logging_silent           | 96.4 ns                                                     | 60.0 ns: 1.61x faster                                             |
| go                       | 136 ms                                                      | 86.3 ms: 1.58x faster                                             |
| richards                 | 41.2 ms                                                     | 26.1 ms: 1.58x faster                                             |
| sqlglot_parse            | 1.22 ms                                                     | 800 us: 1.52x faster                                              |
| json_dumps               | 8.50 ms                                                     | 5.59 ms: 1.52x faster                                             |
| async_tree_io            | 1.07 sec                                                    | 701 ms: 1.52x faster                                              |
| asyncio_tcp              | 712 ms                                                      | 470 ms: 1.52x faster                                              |
| async_tree_memoization   | 497 ms                                                      | 331 ms: 1.50x faster                                              |
| scimark_lu               | 85.4 ms                                                     | 57.1 ms: 1.50x faster                                             |
| raytrace                 | 271 ms                                                      | 184 ms: 1.47x faster                                              |
| async_tree_none          | 420 ms                                                      | 286 ms: 1.47x faster                                              |
| sqlglot_transpile        | 1.46 ms                                                     | 1.01 ms: 1.45x faster                                             |
| generators               | 31.6 ms                                                     | 22.5 ms: 1.40x faster                                             |
| hexiom                   | 5.52 ms                                                     | 3.98 ms: 1.39x faster                                             |
| chaos                    | 58.9 ms                                                     | 42.8 ms: 1.38x faster                                             |
| scimark_monte_carlo      | 55.9 ms                                                     | 41.5 ms: 1.35x faster                                             |
| pickle_pure_python       | 257 us                                                      | 191 us: 1.35x faster                                              |
| scimark_sor              | 105 ms                                                      | 78.7 ms: 1.33x faster                                             |
| crypto_pyaes             | 62.3 ms                                                     | 46.9 ms: 1.33x faster                                             |
| pyflate                  | 387 ms                                                      | 292 ms: 1.33x faster                                              |
| pycparser                | 868 ms                                                      | 670 ms: 1.29x faster                                              |
| async_tree_cpu_io_mixed  | 609 ms                                                      | 471 ms: 1.29x faster                                              |
| unpickle_pure_python     | 171 us                                                      | 133 us: 1.29x faster                                              |
| mako                     | 8.80 ms                                                     | 6.82 ms: 1.29x faster                                             |
| tornado_http             | 109 ms                                                      | 87.2 ms: 1.25x faster                                             |
| deepcopy_memo            | 28.5 us                                                     | 22.9 us: 1.25x faster                                             |
| spectral_norm            | 78.0 ms                                                     | 64.4 ms: 1.21x faster                                             |
| regex_compile            | 103 ms                                                      | 85.8 ms: 1.21x faster                                             |
| tomli_loads              | 1.62 sec                                                    | 1.35 sec: 1.20x faster                                            |
| mdp                      | 1.71 sec                                                    | 1.43 sec: 1.20x faster                                            |
| docutils                 | 1.89 sec                                                    | 1.60 sec: 1.18x faster                                            |
| aiohttp                  | 1.01 ms                                                     | 854 us: 1.18x faster                                              |
| pprint_pformat           | 1.21 sec                                                    | 1.02 sec: 1.18x faster                                            |
| pprint_safe_repr         | 589 ms                                                      | 504 ms: 1.17x faster                                              |
| sqlglot_optimize         | 39.0 ms                                                     | 33.5 ms: 1.16x faster                                             |
| xml_etree_process        | 43.4 ms                                                     | 37.6 ms: 1.16x faster                                             |
| coroutines               | 15.9 ms                                                     | 14.0 ms: 1.14x faster                                             |
| comprehensions           | 16.0 us                                                     | 14.1 us: 1.13x faster                                             |
| sqlglot_normalize        | 202 ms                                                      | 180 ms: 1.13x faster                                              |
| 2to3                     | 237 ms                                                      | 211 ms: 1.12x faster                                              |
| dulwich_log              | 47.6 ms                                                     | 42.5 ms: 1.12x faster                                             |
| float                    | 60.2 ms                                                     | 53.8 ms: 1.12x faster                                             |
| xml_etree_parse          | 102 ms                                                      | 91.3 ms: 1.11x faster                                             |
| deepcopy                 | 255 us                                                      | 229 us: 1.11x faster                                              |
| scimark_fft              | 193 ms                                                      | 174 ms: 1.11x faster                                              |
| bench_thread_pool        | 946 us                                                      | 852 us: 1.11x faster                                              |
| unpickle                 | 9.17 us                                                     | 8.38 us: 1.09x faster                                             |
| fannkuch                 | 258 ms                                                      | 236 ms: 1.09x faster                                              |
| regex_v8                 | 15.0 ms                                                     | 13.8 ms: 1.09x faster                                             |
| create_gc_cycles         | 782 us                                                      | 717 us: 1.09x faster                                              |
| nqueens                  | 67.0 ms                                                     | 61.6 ms: 1.09x faster                                             |
| regex_dna                | 132 ms                                                      | 121 ms: 1.09x faster                                              |
| scimark_sparse_mat_mult  | 2.66 ms                                                     | 2.47 ms: 1.08x faster                                             |
| unpack_sequence          | 37.8 ns                                                     | 35.1 ns: 1.08x faster                                             |
| asyncio_tcp_ssl          | 2.03 sec                                                    | 1.90 sec: 1.07x faster                                            |
| python_startup           | 20.0 ms                                                     | 18.7 ms: 1.07x faster                                             |
| sqlite_synth             | 1.84 us                                                     | 1.73 us: 1.06x faster                                             |
| json_loads               | 14.2 us                                                     | 13.5 us: 1.05x faster                                             |
| json                     | 3.05 ms                                                     | 2.91 ms: 1.05x faster                                             |
| deepcopy_reduce          | 2.16 us                                                     | 2.08 us: 1.04x faster                                             |
| regex_effbot             | 1.66 ms                                                     | 1.61 ms: 1.03x faster                                             |
| nbody                    | 69.3 ms                                                     | 68.7 ms: 1.01x faster                                             |
| meteor_contest           | 72.5 ms                                                     | 73.1 ms: 1.01x slower                                             |
| pathlib                  | 77.4 ms                                                     | 78.1 ms: 1.01x slower                                             |
| xml_etree_generate       | 54.5 ms                                                     | 55.1 ms: 1.01x slower                                             |
| pidigits                 | 145 ms                                                      | 147 ms: 1.01x slower                                              |
| logging_format           | 6.66 us                                                     | 6.77 us: 1.02x slower                                             |
| async_generators         | 224 ms                                                      | 229 ms: 1.02x slower                                              |
| pickle                   | 6.80 us                                                     | 6.98 us: 1.03x slower                                             |
| logging_simple           | 6.20 us                                                     | 6.37 us: 1.03x slower                                             |
| python_startup_no_site   | 15.5 ms                                                     | 16.1 ms: 1.04x slower                                             |
| telco                    | 3.78 ms                                                     | 3.98 ms: 1.05x slower                                             |
| pickle_dict              | 16.9 us                                                     | 18.3 us: 1.08x slower                                             |
| bench_mp_pool            | 60.7 ms                                                     | 66.3 ms: 1.09x slower                                             |
| gc_traversal             | 1.34 ms                                                     | 1.47 ms: 1.10x slower                                             |
| pickle_list              | 2.59 us                                                     | 2.87 us: 1.11x slower                                             |
| dask                     | 305 ms                                                      | 361 ms: 1.18x slower                                              |
| coverage                 | 40.0 ms                                                     | 52.1 ms: 1.30x slower                                             |
| Geometric mean           | (ref)                                                       | 1.19x faster                                                      |

Benchmark hidden because not significant (2): unpickle_list, xml_etree_iterparse
Ignored benchmarks (14) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120.json: chameleon, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.14x
- 95% likely to have a speedup of 1.13x
- 99% likely to have a speedup of 1.11x
