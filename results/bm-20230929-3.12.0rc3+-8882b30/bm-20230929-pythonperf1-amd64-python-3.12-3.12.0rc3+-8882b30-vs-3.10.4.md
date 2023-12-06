
# Results vs. 3.10.4

- fork: python
- ref: 3.12
- machine: windows-amd64
- commit hash: 8882b30
- commit date: 2023-09-29
- overall geometric mean: 1.19x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.11x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230929-pythonperf1-amd64-python-3.12-3.12.0rc3+-8882b30 |
|----------------|:-----------------------------------------------------------:|:------------------------------------------------------------:|
| 2to3           | 237 ms                                                      | 211 ms: 1.12x faster                                         |
| docutils       | 1.89 sec                                                    | 1.62 sec: 1.17x faster                                       |
| tornado_http   | 109 ms                                                      | 87.0 ms: 1.25x faster                                        |
| Geometric mean | (ref)                                                       | 1.18x faster                                                 |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230929-pythonperf1-amd64-python-3.12-3.12.0rc3+-8882b30 |
|----------------|:-----------------------------------------------------------:|:------------------------------------------------------------:|
| float          | 60.2 ms                                                     | 55.1 ms: 1.09x faster                                        |
| nbody          | 69.3 ms                                                     | 71.4 ms: 1.03x slower                                        |
| pidigits       | 145 ms                                                      | 150 ms: 1.03x slower                                         |
| Geometric mean | (ref)                                                       | 1.01x faster                                                 |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230929-pythonperf1-amd64-python-3.12-3.12.0rc3+-8882b30 |
|----------------|:-----------------------------------------------------------:|:------------------------------------------------------------:|
| regex_compile  | 103 ms                                                      | 86.9 ms: 1.19x faster                                        |
| regex_v8       | 15.0 ms                                                     | 13.9 ms: 1.08x faster                                        |
| regex_dna      | 132 ms                                                      | 123 ms: 1.07x faster                                         |
| regex_effbot   | 1.66 ms                                                     | 1.62 ms: 1.03x faster                                        |
| Geometric mean | (ref)                                                       | 1.09x faster                                                 |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230929-pythonperf1-amd64-python-3.12-3.12.0rc3+-8882b30 |
|----------------------|:-----------------------------------------------------------:|:------------------------------------------------------------:|
| json_dumps           | 8.50 ms                                                     | 5.62 ms: 1.51x faster                                        |
| pickle_pure_python   | 257 us                                                      | 193 us: 1.33x faster                                         |
| unpickle_pure_python | 171 us                                                      | 135 us: 1.27x faster                                         |
| tomli_loads          | 1.62 sec                                                    | 1.36 sec: 1.19x faster                                       |
| xml_etree_process    | 43.4 ms                                                     | 37.7 ms: 1.15x faster                                        |
| unpickle             | 9.17 us                                                     | 8.28 us: 1.11x faster                                        |
| xml_etree_parse      | 102 ms                                                      | 92.7 ms: 1.10x faster                                        |
| unpickle_list        | 2.81 us                                                     | 2.68 us: 1.05x faster                                        |
| json_loads           | 14.2 us                                                     | 13.6 us: 1.04x faster                                        |
| xml_etree_generate   | 54.5 ms                                                     | 55.3 ms: 1.01x slower                                        |
| pickle               | 6.80 us                                                     | 7.00 us: 1.03x slower                                        |
| pickle_dict          | 16.9 us                                                     | 18.2 us: 1.08x slower                                        |
| pickle_list          | 2.59 us                                                     | 2.84 us: 1.10x slower                                        |
| Geometric mean       | (ref)                                                       | 1.10x faster                                                 |

Benchmark hidden because not significant (1): xml_etree_iterparse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230929-pythonperf1-amd64-python-3.12-3.12.0rc3+-8882b30 |
|------------------------|:-----------------------------------------------------------:|:------------------------------------------------------------:|
| python_startup         | 20.0 ms                                                     | 19.1 ms: 1.05x faster                                        |
| python_startup_no_site | 15.5 ms                                                     | 16.2 ms: 1.04x slower                                        |
| Geometric mean         | (ref)                                                       | 1.00x faster                                                 |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230929-pythonperf1-amd64-python-3.12-3.12.0rc3+-8882b30 |
|-----------|:-----------------------------------------------------------:|:------------------------------------------------------------:|
| mako      | 8.80 ms                                                     | 6.93 ms: 1.27x faster                                        |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230929-pythonperf1-amd64-python-3.12-3.12.0rc3+-8882b30 |
|--------------------------|:-----------------------------------------------------------:|:------------------------------------------------------------:|
| typing_runtime_protocols | 325 us                                                      | 94.2 us: 3.45x faster                                        |
| deltablue                | 4.17 ms                                                     | 2.12 ms: 1.97x faster                                        |
| richards_super           | 51.7 ms                                                     | 30.1 ms: 1.72x faster                                        |
| mypy2                    | 352 ms                                                      | 208 ms: 1.69x faster                                         |
| logging_silent           | 96.4 ns                                                     | 60.4 ns: 1.60x faster                                        |
| richards                 | 41.2 ms                                                     | 26.5 ms: 1.55x faster                                        |
| go                       | 136 ms                                                      | 87.9 ms: 1.55x faster                                        |
| asyncio_tcp              | 712 ms                                                      | 469 ms: 1.52x faster                                         |
| sqlglot_parse            | 1.22 ms                                                     | 805 us: 1.51x faster                                         |
| json_dumps               | 8.50 ms                                                     | 5.62 ms: 1.51x faster                                        |
| async_tree_memoization   | 497 ms                                                      | 334 ms: 1.49x faster                                         |
| scimark_lu               | 85.4 ms                                                     | 57.4 ms: 1.49x faster                                        |
| async_tree_io            | 1.07 sec                                                    | 717 ms: 1.49x faster                                         |
| async_tree_none          | 420 ms                                                      | 287 ms: 1.46x faster                                         |
| sqlglot_transpile        | 1.46 ms                                                     | 1.02 ms: 1.43x faster                                        |
| raytrace                 | 271 ms                                                      | 193 ms: 1.41x faster                                         |
| chaos                    | 58.9 ms                                                     | 41.8 ms: 1.41x faster                                        |
| generators               | 31.6 ms                                                     | 22.5 ms: 1.41x faster                                        |
| hexiom                   | 5.52 ms                                                     | 4.00 ms: 1.38x faster                                        |
| scimark_sor              | 105 ms                                                      | 77.2 ms: 1.36x faster                                        |
| pickle_pure_python       | 257 us                                                      | 193 us: 1.33x faster                                         |
| pyflate                  | 387 ms                                                      | 292 ms: 1.33x faster                                         |
| scimark_monte_carlo      | 55.9 ms                                                     | 42.1 ms: 1.33x faster                                        |
| crypto_pyaes             | 62.3 ms                                                     | 47.0 ms: 1.33x faster                                        |
| async_tree_cpu_io_mixed  | 609 ms                                                      | 477 ms: 1.28x faster                                         |
| unpickle_pure_python     | 171 us                                                      | 135 us: 1.27x faster                                         |
| mako                     | 8.80 ms                                                     | 6.93 ms: 1.27x faster                                        |
| pycparser                | 868 ms                                                      | 686 ms: 1.26x faster                                         |
| tornado_http             | 109 ms                                                      | 87.0 ms: 1.25x faster                                        |
| spectral_norm            | 78.0 ms                                                     | 63.2 ms: 1.23x faster                                        |
| deepcopy_memo            | 28.5 us                                                     | 23.9 us: 1.19x faster                                        |
| tomli_loads              | 1.62 sec                                                    | 1.36 sec: 1.19x faster                                       |
| regex_compile            | 103 ms                                                      | 86.9 ms: 1.19x faster                                        |
| dask                     | 305 ms                                                      | 257 ms: 1.19x faster                                         |
| pprint_pformat           | 1.21 sec                                                    | 1.02 sec: 1.19x faster                                       |
| mdp                      | 1.71 sec                                                    | 1.45 sec: 1.18x faster                                       |
| pprint_safe_repr         | 589 ms                                                      | 499 ms: 1.18x faster                                         |
| aiohttp                  | 1.01 ms                                                     | 855 us: 1.18x faster                                         |
| docutils                 | 1.89 sec                                                    | 1.62 sec: 1.17x faster                                       |
| xml_etree_process        | 43.4 ms                                                     | 37.7 ms: 1.15x faster                                        |
| sqlglot_optimize         | 39.0 ms                                                     | 34.0 ms: 1.14x faster                                        |
| bench_thread_pool        | 946 us                                                      | 831 us: 1.14x faster                                         |
| coroutines               | 15.9 ms                                                     | 14.0 ms: 1.13x faster                                        |
| 2to3                     | 237 ms                                                      | 211 ms: 1.12x faster                                         |
| comprehensions           | 16.0 us                                                     | 14.3 us: 1.12x faster                                        |
| dulwich_log              | 47.6 ms                                                     | 42.9 ms: 1.11x faster                                        |
| unpickle                 | 9.17 us                                                     | 8.28 us: 1.11x faster                                        |
| xml_etree_parse          | 102 ms                                                      | 92.7 ms: 1.10x faster                                        |
| sqlglot_normalize        | 202 ms                                                      | 184 ms: 1.10x faster                                         |
| deepcopy                 | 255 us                                                      | 233 us: 1.09x faster                                         |
| float                    | 60.2 ms                                                     | 55.1 ms: 1.09x faster                                        |
| nqueens                  | 67.0 ms                                                     | 61.8 ms: 1.09x faster                                        |
| scimark_fft              | 193 ms                                                      | 179 ms: 1.08x faster                                         |
| regex_v8                 | 15.0 ms                                                     | 13.9 ms: 1.08x faster                                        |
| create_gc_cycles         | 782 us                                                      | 729 us: 1.07x faster                                         |
| regex_dna                | 132 ms                                                      | 123 ms: 1.07x faster                                         |
| scimark_sparse_mat_mult  | 2.66 ms                                                     | 2.50 ms: 1.06x faster                                        |
| sqlite_synth             | 1.84 us                                                     | 1.74 us: 1.06x faster                                        |
| unpickle_list            | 2.81 us                                                     | 2.68 us: 1.05x faster                                        |
| deepcopy_reduce          | 2.16 us                                                     | 2.06 us: 1.05x faster                                        |
| python_startup           | 20.0 ms                                                     | 19.1 ms: 1.05x faster                                        |
| asyncio_tcp_ssl          | 2.03 sec                                                    | 1.94 sec: 1.05x faster                                       |
| json_loads               | 14.2 us                                                     | 13.6 us: 1.04x faster                                        |
| fannkuch                 | 258 ms                                                      | 247 ms: 1.04x faster                                         |
| unpack_sequence          | 37.8 ns                                                     | 36.5 ns: 1.04x faster                                        |
| json                     | 3.05 ms                                                     | 2.94 ms: 1.04x faster                                        |
| regex_effbot             | 1.66 ms                                                     | 1.62 ms: 1.03x faster                                        |
| logging_format           | 6.66 us                                                     | 6.56 us: 1.02x faster                                        |
| logging_simple           | 6.20 us                                                     | 6.15 us: 1.01x faster                                        |
| pathlib                  | 77.4 ms                                                     | 78.2 ms: 1.01x slower                                        |
| xml_etree_generate       | 54.5 ms                                                     | 55.3 ms: 1.01x slower                                        |
| pickle                   | 6.80 us                                                     | 7.00 us: 1.03x slower                                        |
| nbody                    | 69.3 ms                                                     | 71.4 ms: 1.03x slower                                        |
| pidigits                 | 145 ms                                                      | 150 ms: 1.03x slower                                         |
| python_startup_no_site   | 15.5 ms                                                     | 16.2 ms: 1.04x slower                                        |
| async_generators         | 224 ms                                                      | 235 ms: 1.05x slower                                         |
| pickle_dict              | 16.9 us                                                     | 18.2 us: 1.08x slower                                        |
| pickle_list              | 2.59 us                                                     | 2.84 us: 1.10x slower                                        |
| telco                    | 3.78 ms                                                     | 4.18 ms: 1.11x slower                                        |
| bench_mp_pool            | 60.7 ms                                                     | 67.2 ms: 1.11x slower                                        |
| gc_traversal             | 1.34 ms                                                     | 1.49 ms: 1.11x slower                                        |
| coverage                 | 40.0 ms                                                     | 50.7 ms: 1.27x slower                                        |
| Geometric mean           | (ref)                                                       | 1.19x faster                                                 |

Benchmark hidden because not significant (2): xml_etree_iterparse, meteor_contest
Ignored benchmarks (14) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120.json: chameleon, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.14x
- 95% likely to have a speedup of 1.13x
- 99% likely to have a speedup of 1.11x
