
# Results vs. 3.10.4

- fork: python
- ref: 3.12
- machine: windows-amd64
- commit hash: 028f477
- commit date: 2023-10-21
- overall geometric mean: 1.19x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.11x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231021-pythonperf1-amd64-python-3.12-3.12.0+-028f477 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------:|
| 2to3           | 237 ms                                                      | 213 ms: 1.11x faster                                      |
| docutils       | 1.89 sec                                                    | 1.63 sec: 1.16x faster                                    |
| tornado_http   | 109 ms                                                      | 87.6 ms: 1.25x faster                                     |
| Geometric mean | (ref)                                                       | 1.17x faster                                              |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231021-pythonperf1-amd64-python-3.12-3.12.0+-028f477 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------:|
| float          | 60.2 ms                                                     | 53.5 ms: 1.12x faster                                     |
| pidigits       | 145 ms                                                      | 150 ms: 1.03x slower                                      |
| Geometric mean | (ref)                                                       | 1.03x faster                                              |

Benchmark hidden because not significant (1): nbody

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231021-pythonperf1-amd64-python-3.12-3.12.0+-028f477 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------:|
| regex_compile  | 103 ms                                                      | 86.5 ms: 1.20x faster                                     |
| regex_v8       | 15.0 ms                                                     | 13.9 ms: 1.08x faster                                     |
| regex_dna      | 132 ms                                                      | 126 ms: 1.04x faster                                      |
| regex_effbot   | 1.66 ms                                                     | 1.61 ms: 1.04x faster                                     |
| Geometric mean | (ref)                                                       | 1.09x faster                                              |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231021-pythonperf1-amd64-python-3.12-3.12.0+-028f477 |
|----------------------|:-----------------------------------------------------------:|:---------------------------------------------------------:|
| json_dumps           | 8.50 ms                                                     | 5.68 ms: 1.50x faster                                     |
| pickle_pure_python   | 257 us                                                      | 196 us: 1.31x faster                                      |
| unpickle_pure_python | 171 us                                                      | 133 us: 1.29x faster                                      |
| tomli_loads          | 1.62 sec                                                    | 1.38 sec: 1.18x faster                                    |
| xml_etree_process    | 43.4 ms                                                     | 38.1 ms: 1.14x faster                                     |
| unpickle             | 9.17 us                                                     | 8.14 us: 1.13x faster                                     |
| xml_etree_parse      | 102 ms                                                      | 91.2 ms: 1.12x faster                                     |
| json_loads           | 14.2 us                                                     | 13.6 us: 1.04x faster                                     |
| xml_etree_generate   | 54.5 ms                                                     | 55.5 ms: 1.02x slower                                     |
| pickle               | 6.80 us                                                     | 6.95 us: 1.02x slower                                     |
| pickle_dict          | 16.9 us                                                     | 18.3 us: 1.08x slower                                     |
| pickle_list          | 2.59 us                                                     | 2.83 us: 1.09x slower                                     |
| Geometric mean       | (ref)                                                       | 1.10x faster                                              |

Benchmark hidden because not significant (2): unpickle_list, xml_etree_iterparse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231021-pythonperf1-amd64-python-3.12-3.12.0+-028f477 |
|------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------:|
| python_startup         | 20.0 ms                                                     | 19.1 ms: 1.04x faster                                     |
| python_startup_no_site | 15.5 ms                                                     | 15.9 ms: 1.02x slower                                     |
| Geometric mean         | (ref)                                                       | 1.01x faster                                              |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231021-pythonperf1-amd64-python-3.12-3.12.0+-028f477 |
|-----------|:-----------------------------------------------------------:|:---------------------------------------------------------:|
| mako      | 8.80 ms                                                     | 6.88 ms: 1.28x faster                                     |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231021-pythonperf1-amd64-python-3.12-3.12.0+-028f477 |
|--------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------:|
| typing_runtime_protocols | 325 us                                                      | 94.3 us: 3.44x faster                                     |
| deltablue                | 4.17 ms                                                     | 2.13 ms: 1.96x faster                                     |
| richards_super           | 51.7 ms                                                     | 30.5 ms: 1.70x faster                                     |
| mypy2                    | 352 ms                                                      | 209 ms: 1.68x faster                                      |
| logging_silent           | 96.4 ns                                                     | 61.2 ns: 1.58x faster                                     |
| go                       | 136 ms                                                      | 87.5 ms: 1.56x faster                                     |
| richards                 | 41.2 ms                                                     | 26.8 ms: 1.54x faster                                     |
| asyncio_tcp              | 712 ms                                                      | 471 ms: 1.51x faster                                      |
| sqlglot_parse            | 1.22 ms                                                     | 813 us: 1.50x faster                                      |
| json_dumps               | 8.50 ms                                                     | 5.68 ms: 1.50x faster                                     |
| async_tree_io            | 1.07 sec                                                    | 715 ms: 1.49x faster                                      |
| async_tree_memoization   | 497 ms                                                      | 339 ms: 1.47x faster                                      |
| scimark_lu               | 85.4 ms                                                     | 58.5 ms: 1.46x faster                                     |
| async_tree_none          | 420 ms                                                      | 289 ms: 1.45x faster                                      |
| sqlglot_transpile        | 1.46 ms                                                     | 1.03 ms: 1.42x faster                                     |
| generators               | 31.6 ms                                                     | 22.5 ms: 1.40x faster                                     |
| raytrace                 | 271 ms                                                      | 196 ms: 1.38x faster                                      |
| chaos                    | 58.9 ms                                                     | 42.8 ms: 1.38x faster                                     |
| hexiom                   | 5.52 ms                                                     | 4.02 ms: 1.37x faster                                     |
| crypto_pyaes             | 62.3 ms                                                     | 46.4 ms: 1.34x faster                                     |
| scimark_sor              | 105 ms                                                      | 78.3 ms: 1.34x faster                                     |
| pyflate                  | 387 ms                                                      | 292 ms: 1.32x faster                                      |
| scimark_monte_carlo      | 55.9 ms                                                     | 42.4 ms: 1.32x faster                                     |
| pickle_pure_python       | 257 us                                                      | 196 us: 1.31x faster                                      |
| unpickle_pure_python     | 171 us                                                      | 133 us: 1.29x faster                                      |
| mako                     | 8.80 ms                                                     | 6.88 ms: 1.28x faster                                     |
| async_tree_cpu_io_mixed  | 609 ms                                                      | 478 ms: 1.27x faster                                      |
| pycparser                | 868 ms                                                      | 685 ms: 1.27x faster                                      |
| tornado_http             | 109 ms                                                      | 87.6 ms: 1.25x faster                                     |
| spectral_norm            | 78.0 ms                                                     | 62.8 ms: 1.24x faster                                     |
| deepcopy_memo            | 28.5 us                                                     | 23.6 us: 1.21x faster                                     |
| mdp                      | 1.71 sec                                                    | 1.43 sec: 1.20x faster                                    |
| regex_compile            | 103 ms                                                      | 86.5 ms: 1.20x faster                                     |
| dask                     | 305 ms                                                      | 255 ms: 1.19x faster                                      |
| tomli_loads              | 1.62 sec                                                    | 1.38 sec: 1.18x faster                                    |
| aiohttp                  | 1.01 ms                                                     | 865 us: 1.16x faster                                      |
| pprint_pformat           | 1.21 sec                                                    | 1.04 sec: 1.16x faster                                    |
| docutils                 | 1.89 sec                                                    | 1.63 sec: 1.16x faster                                    |
| pprint_safe_repr         | 589 ms                                                      | 510 ms: 1.15x faster                                      |
| xml_etree_process        | 43.4 ms                                                     | 38.1 ms: 1.14x faster                                     |
| bench_thread_pool        | 946 us                                                      | 830 us: 1.14x faster                                      |
| comprehensions           | 16.0 us                                                     | 14.2 us: 1.13x faster                                     |
| unpickle                 | 9.17 us                                                     | 8.14 us: 1.13x faster                                     |
| float                    | 60.2 ms                                                     | 53.5 ms: 1.12x faster                                     |
| coroutines               | 15.9 ms                                                     | 14.2 ms: 1.12x faster                                     |
| sqlglot_optimize         | 39.0 ms                                                     | 34.7 ms: 1.12x faster                                     |
| dulwich_log              | 47.6 ms                                                     | 42.6 ms: 1.12x faster                                     |
| xml_etree_parse          | 102 ms                                                      | 91.2 ms: 1.12x faster                                     |
| 2to3                     | 237 ms                                                      | 213 ms: 1.11x faster                                      |
| scimark_fft              | 193 ms                                                      | 174 ms: 1.11x faster                                      |
| create_gc_cycles         | 782 us                                                      | 716 us: 1.09x faster                                      |
| fannkuch                 | 258 ms                                                      | 236 ms: 1.09x faster                                      |
| nqueens                  | 67.0 ms                                                     | 61.5 ms: 1.09x faster                                     |
| scimark_sparse_mat_mult  | 2.66 ms                                                     | 2.45 ms: 1.09x faster                                     |
| regex_v8                 | 15.0 ms                                                     | 13.9 ms: 1.08x faster                                     |
| sqlglot_normalize        | 202 ms                                                      | 188 ms: 1.08x faster                                      |
| asyncio_tcp_ssl          | 2.03 sec                                                    | 1.92 sec: 1.06x faster                                    |
| sqlite_synth             | 1.84 us                                                     | 1.75 us: 1.05x faster                                     |
| deepcopy                 | 255 us                                                      | 244 us: 1.05x faster                                      |
| regex_dna                | 132 ms                                                      | 126 ms: 1.04x faster                                      |
| python_startup           | 20.0 ms                                                     | 19.1 ms: 1.04x faster                                     |
| json_loads               | 14.2 us                                                     | 13.6 us: 1.04x faster                                     |
| regex_effbot             | 1.66 ms                                                     | 1.61 ms: 1.04x faster                                     |
| json                     | 3.05 ms                                                     | 2.96 ms: 1.03x faster                                     |
| unpack_sequence          | 37.8 ns                                                     | 36.8 ns: 1.03x faster                                     |
| deepcopy_reduce          | 2.16 us                                                     | 2.14 us: 1.01x faster                                     |
| logging_simple           | 6.20 us                                                     | 6.24 us: 1.01x slower                                     |
| logging_format           | 6.66 us                                                     | 6.73 us: 1.01x slower                                     |
| pathlib                  | 77.4 ms                                                     | 78.2 ms: 1.01x slower                                     |
| xml_etree_generate       | 54.5 ms                                                     | 55.5 ms: 1.02x slower                                     |
| meteor_contest           | 72.5 ms                                                     | 73.9 ms: 1.02x slower                                     |
| pickle                   | 6.80 us                                                     | 6.95 us: 1.02x slower                                     |
| python_startup_no_site   | 15.5 ms                                                     | 15.9 ms: 1.02x slower                                     |
| pidigits                 | 145 ms                                                      | 150 ms: 1.03x slower                                      |
| bench_mp_pool            | 60.7 ms                                                     | 63.1 ms: 1.04x slower                                     |
| async_generators         | 224 ms                                                      | 236 ms: 1.05x slower                                      |
| telco                    | 3.78 ms                                                     | 4.04 ms: 1.07x slower                                     |
| pickle_dict              | 16.9 us                                                     | 18.3 us: 1.08x slower                                     |
| pickle_list              | 2.59 us                                                     | 2.83 us: 1.09x slower                                     |
| gc_traversal             | 1.34 ms                                                     | 1.48 ms: 1.10x slower                                     |
| coverage                 | 40.0 ms                                                     | 51.0 ms: 1.27x slower                                     |
| Geometric mean           | (ref)                                                       | 1.19x faster                                              |

Benchmark hidden because not significant (3): unpickle_list, nbody, xml_etree_iterparse
Ignored benchmarks (14) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120.json: chameleon, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.14x
- 95% likely to have a speedup of 1.12x
- 99% likely to have a speedup of 1.11x
