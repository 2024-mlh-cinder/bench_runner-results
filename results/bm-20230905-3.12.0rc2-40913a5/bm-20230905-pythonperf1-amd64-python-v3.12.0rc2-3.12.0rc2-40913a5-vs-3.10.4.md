
# Results vs. 3.10.4

- fork: python
- ref: v3.12.0rc2
- machine: windows-amd64
- commit hash: 40913a5
- commit date: 2023-09-05
- overall geometric mean: 1.17x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.10x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230905-pythonperf1-amd64-python-v3.12.0rc2-3.12.0rc2-40913a5 |
|----------------|:-----------------------------------------------------------:|:-----------------------------------------------------------------:|
| 2to3           | 237 ms                                                      | 216 ms: 1.10x faster                                              |
| docutils       | 1.89 sec                                                    | 1.65 sec: 1.15x faster                                            |
| tornado_http   | 109 ms                                                      | 88.4 ms: 1.23x faster                                             |
| Geometric mean | (ref)                                                       | 1.16x faster                                                      |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230905-pythonperf1-amd64-python-v3.12.0rc2-3.12.0rc2-40913a5 |
|----------------|:-----------------------------------------------------------:|:-----------------------------------------------------------------:|
| float          | 60.2 ms                                                     | 54.4 ms: 1.11x faster                                             |
| pidigits       | 145 ms                                                      | 150 ms: 1.03x slower                                              |
| Geometric mean | (ref)                                                       | 1.03x faster                                                      |

Benchmark hidden because not significant (1): nbody

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230905-pythonperf1-amd64-python-v3.12.0rc2-3.12.0rc2-40913a5 |
|----------------|:-----------------------------------------------------------:|:-----------------------------------------------------------------:|
| regex_compile  | 103 ms                                                      | 87.5 ms: 1.18x faster                                             |
| regex_dna      | 132 ms                                                      | 119 ms: 1.11x faster                                              |
| regex_v8       | 15.0 ms                                                     | 13.7 ms: 1.10x faster                                             |
| regex_effbot   | 1.66 ms                                                     | 1.58 ms: 1.05x faster                                             |
| Geometric mean | (ref)                                                       | 1.11x faster                                                      |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230905-pythonperf1-amd64-python-v3.12.0rc2-3.12.0rc2-40913a5 |
|----------------------|:-----------------------------------------------------------:|:-----------------------------------------------------------------:|
| json_dumps           | 8.50 ms                                                     | 5.66 ms: 1.50x faster                                             |
| pickle_pure_python   | 257 us                                                      | 191 us: 1.34x faster                                              |
| unpickle_pure_python | 171 us                                                      | 130 us: 1.31x faster                                              |
| tomli_loads          | 1.62 sec                                                    | 1.37 sec: 1.18x faster                                            |
| xml_etree_process    | 43.4 ms                                                     | 37.9 ms: 1.15x faster                                             |
| unpickle             | 9.17 us                                                     | 8.05 us: 1.14x faster                                             |
| xml_etree_parse      | 102 ms                                                      | 89.7 ms: 1.13x faster                                             |
| unpickle_list        | 2.81 us                                                     | 2.65 us: 1.06x faster                                             |
| json_loads           | 14.2 us                                                     | 13.6 us: 1.04x faster                                             |
| xml_etree_iterparse  | 63.5 ms                                                     | 62.8 ms: 1.01x faster                                             |
| xml_etree_generate   | 54.5 ms                                                     | 55.4 ms: 1.02x slower                                             |
| pickle               | 6.80 us                                                     | 6.97 us: 1.02x slower                                             |
| pickle_list          | 2.59 us                                                     | 2.75 us: 1.06x slower                                             |
| pickle_dict          | 16.9 us                                                     | 18.3 us: 1.08x slower                                             |
| Geometric mean       | (ref)                                                       | 1.11x faster                                                      |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230905-pythonperf1-amd64-python-v3.12.0rc2-3.12.0rc2-40913a5 |
|------------------------|:-----------------------------------------------------------:|:-----------------------------------------------------------------:|
| python_startup         | 20.0 ms                                                     | 19.3 ms: 1.04x faster                                             |
| python_startup_no_site | 15.5 ms                                                     | 16.3 ms: 1.05x slower                                             |
| Geometric mean         | (ref)                                                       | 1.01x slower                                                      |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230905-pythonperf1-amd64-python-v3.12.0rc2-3.12.0rc2-40913a5 |
|-----------|:-----------------------------------------------------------:|:-----------------------------------------------------------------:|
| mako      | 8.80 ms                                                     | 7.00 ms: 1.26x faster                                             |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230905-pythonperf1-amd64-python-v3.12.0rc2-3.12.0rc2-40913a5 |
|--------------------------|:-----------------------------------------------------------:|:-----------------------------------------------------------------:|
| typing_runtime_protocols | 325 us                                                      | 96.2 us: 3.38x faster                                             |
| deltablue                | 4.17 ms                                                     | 2.13 ms: 1.96x faster                                             |
| richards_super           | 51.7 ms                                                     | 29.7 ms: 1.74x faster                                             |
| mypy2                    | 352 ms                                                      | 209 ms: 1.68x faster                                              |
| logging_silent           | 96.4 ns                                                     | 60.3 ns: 1.60x faster                                             |
| richards                 | 41.2 ms                                                     | 26.0 ms: 1.58x faster                                             |
| go                       | 136 ms                                                      | 87.0 ms: 1.57x faster                                             |
| sqlglot_parse            | 1.22 ms                                                     | 808 us: 1.51x faster                                              |
| json_dumps               | 8.50 ms                                                     | 5.66 ms: 1.50x faster                                             |
| scimark_lu               | 85.4 ms                                                     | 57.2 ms: 1.49x faster                                             |
| asyncio_tcp              | 712 ms                                                      | 480 ms: 1.48x faster                                              |
| async_tree_io            | 1.07 sec                                                    | 722 ms: 1.47x faster                                              |
| async_tree_memoization   | 497 ms                                                      | 339 ms: 1.47x faster                                              |
| async_tree_none          | 420 ms                                                      | 291 ms: 1.45x faster                                              |
| sqlglot_transpile        | 1.46 ms                                                     | 1.02 ms: 1.43x faster                                             |
| raytrace                 | 271 ms                                                      | 190 ms: 1.42x faster                                              |
| chaos                    | 58.9 ms                                                     | 42.6 ms: 1.38x faster                                             |
| hexiom                   | 5.52 ms                                                     | 4.04 ms: 1.37x faster                                             |
| scimark_sor              | 105 ms                                                      | 77.1 ms: 1.36x faster                                             |
| pickle_pure_python       | 257 us                                                      | 191 us: 1.34x faster                                              |
| crypto_pyaes             | 62.3 ms                                                     | 46.9 ms: 1.33x faster                                             |
| pyflate                  | 387 ms                                                      | 293 ms: 1.32x faster                                              |
| unpickle_pure_python     | 171 us                                                      | 130 us: 1.31x faster                                              |
| generators               | 31.6 ms                                                     | 24.2 ms: 1.31x faster                                             |
| scimark_monte_carlo      | 55.9 ms                                                     | 42.8 ms: 1.30x faster                                             |
| pycparser                | 868 ms                                                      | 681 ms: 1.28x faster                                              |
| async_tree_cpu_io_mixed  | 609 ms                                                      | 480 ms: 1.27x faster                                              |
| mako                     | 8.80 ms                                                     | 7.00 ms: 1.26x faster                                             |
| spectral_norm            | 78.0 ms                                                     | 62.7 ms: 1.24x faster                                             |
| mdp                      | 1.71 sec                                                    | 1.39 sec: 1.23x faster                                            |
| tornado_http             | 109 ms                                                      | 88.4 ms: 1.23x faster                                             |
| deepcopy_memo            | 28.5 us                                                     | 23.6 us: 1.21x faster                                             |
| regex_compile            | 103 ms                                                      | 87.5 ms: 1.18x faster                                             |
| tomli_loads              | 1.62 sec                                                    | 1.37 sec: 1.18x faster                                            |
| aiohttp                  | 1.01 ms                                                     | 863 us: 1.17x faster                                              |
| pprint_safe_repr         | 589 ms                                                      | 509 ms: 1.16x faster                                              |
| pprint_pformat           | 1.21 sec                                                    | 1.04 sec: 1.16x faster                                            |
| docutils                 | 1.89 sec                                                    | 1.65 sec: 1.15x faster                                            |
| xml_etree_process        | 43.4 ms                                                     | 37.9 ms: 1.15x faster                                             |
| unpickle                 | 9.17 us                                                     | 8.05 us: 1.14x faster                                             |
| xml_etree_parse          | 102 ms                                                      | 89.7 ms: 1.13x faster                                             |
| sqlglot_optimize         | 39.0 ms                                                     | 34.5 ms: 1.13x faster                                             |
| dulwich_log              | 47.6 ms                                                     | 42.8 ms: 1.11x faster                                             |
| regex_dna                | 132 ms                                                      | 119 ms: 1.11x faster                                              |
| float                    | 60.2 ms                                                     | 54.4 ms: 1.11x faster                                             |
| bench_thread_pool        | 946 us                                                      | 857 us: 1.10x faster                                              |
| regex_v8                 | 15.0 ms                                                     | 13.7 ms: 1.10x faster                                             |
| 2to3                     | 237 ms                                                      | 216 ms: 1.10x faster                                              |
| scimark_fft              | 193 ms                                                      | 176 ms: 1.10x faster                                              |
| create_gc_cycles         | 782 us                                                      | 718 us: 1.09x faster                                              |
| sqlglot_normalize        | 202 ms                                                      | 187 ms: 1.08x faster                                              |
| scimark_sparse_mat_mult  | 2.66 ms                                                     | 2.50 ms: 1.06x faster                                             |
| unpickle_list            | 2.81 us                                                     | 2.65 us: 1.06x faster                                             |
| deepcopy                 | 255 us                                                      | 241 us: 1.06x faster                                              |
| sqlite_synth             | 1.84 us                                                     | 1.74 us: 1.05x faster                                             |
| regex_effbot             | 1.66 ms                                                     | 1.58 ms: 1.05x faster                                             |
| nqueens                  | 67.0 ms                                                     | 63.9 ms: 1.05x faster                                             |
| comprehensions           | 16.0 us                                                     | 15.3 us: 1.04x faster                                             |
| json_loads               | 14.2 us                                                     | 13.6 us: 1.04x faster                                             |
| python_startup           | 20.0 ms                                                     | 19.3 ms: 1.04x faster                                             |
| asyncio_tcp_ssl          | 2.03 sec                                                    | 1.96 sec: 1.04x faster                                            |
| fannkuch                 | 258 ms                                                      | 249 ms: 1.03x faster                                              |
| json                     | 3.05 ms                                                     | 2.99 ms: 1.02x faster                                             |
| xml_etree_iterparse      | 63.5 ms                                                     | 62.8 ms: 1.01x faster                                             |
| logging_simple           | 6.20 us                                                     | 6.24 us: 1.01x slower                                             |
| meteor_contest           | 72.5 ms                                                     | 73.1 ms: 1.01x slower                                             |
| logging_format           | 6.66 us                                                     | 6.74 us: 1.01x slower                                             |
| pathlib                  | 77.4 ms                                                     | 78.3 ms: 1.01x slower                                             |
| unpack_sequence          | 37.8 ns                                                     | 38.3 ns: 1.01x slower                                             |
| xml_etree_generate       | 54.5 ms                                                     | 55.4 ms: 1.02x slower                                             |
| pickle                   | 6.80 us                                                     | 6.97 us: 1.02x slower                                             |
| pidigits                 | 145 ms                                                      | 150 ms: 1.03x slower                                              |
| python_startup_no_site   | 15.5 ms                                                     | 16.3 ms: 1.05x slower                                             |
| pickle_list              | 2.59 us                                                     | 2.75 us: 1.06x slower                                             |
| async_generators         | 224 ms                                                      | 238 ms: 1.07x slower                                              |
| pickle_dict              | 16.9 us                                                     | 18.3 us: 1.08x slower                                             |
| telco                    | 3.78 ms                                                     | 4.19 ms: 1.11x slower                                             |
| bench_mp_pool            | 60.7 ms                                                     | 67.3 ms: 1.11x slower                                             |
| gc_traversal             | 1.34 ms                                                     | 1.51 ms: 1.12x slower                                             |
| dask                     | 305 ms                                                      | 363 ms: 1.19x slower                                              |
| coroutines               | 15.9 ms                                                     | 19.0 ms: 1.19x slower                                             |
| coverage                 | 40.0 ms                                                     | 50.2 ms: 1.25x slower                                             |
| Geometric mean           | (ref)                                                       | 1.17x faster                                                      |

Benchmark hidden because not significant (2): nbody, deepcopy_reduce
Ignored benchmarks (14) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120.json: chameleon, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.13x
- 95% likely to have a speedup of 1.11x
- 99% likely to have a speedup of 1.10x
