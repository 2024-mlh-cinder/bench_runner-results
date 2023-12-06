
# Results vs. 3.10.4

- fork: python
- ref: 3.12
- machine: linux-x86_64
- commit hash: 744f752
- commit date: 2023-10-14
- overall geometric mean: 1.30x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.23x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231014-pythonperf2-x86_64-python-3.12-3.12.0+-744f752 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------:|
| 2to3           | 350 ms                                                       | 285 ms: 1.23x faster                                       |
| docutils       | 3.40 sec                                                     | 2.87 sec: 1.19x faster                                     |
| tornado_http   | 152 ms                                                       | 120 ms: 1.27x faster                                       |
| Geometric mean | (ref)                                                        | 1.23x faster                                               |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231014-pythonperf2-x86_64-python-3.12-3.12.0+-744f752 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------:|
| nbody          | 137 ms                                                       | 84.2 ms: 1.63x faster                                      |
| float          | 110 ms                                                       | 77.4 ms: 1.43x faster                                      |
| pidigits       | 271 ms                                                       | 263 ms: 1.03x faster                                       |
| Geometric mean | (ref)                                                        | 1.34x faster                                               |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231014-pythonperf2-x86_64-python-3.12-3.12.0+-744f752 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------:|
| regex_compile  | 194 ms                                                       | 141 ms: 1.37x faster                                       |
| regex_v8       | 26.6 ms                                                      | 24.3 ms: 1.10x faster                                      |
| regex_dna      | 259 ms                                                       | 243 ms: 1.07x faster                                       |
| regex_effbot   | 2.99 ms                                                      | 3.49 ms: 1.17x slower                                      |
| Geometric mean | (ref)                                                        | 1.08x faster                                               |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231014-pythonperf2-x86_64-python-3.12-3.12.0+-744f752 |
|----------------------|:------------------------------------------------------------:|:----------------------------------------------------------:|
| unpickle_pure_python | 321 us                                                       | 209 us: 1.53x faster                                       |
| pickle_pure_python   | 457 us                                                       | 316 us: 1.44x faster                                       |
| json_dumps           | 14.2 ms                                                      | 10.2 ms: 1.39x faster                                      |
| tomli_loads          | 2.97 sec                                                     | 2.18 sec: 1.36x faster                                     |
| xml_etree_process    | 76.0 ms                                                      | 58.2 ms: 1.31x faster                                      |
| json_loads           | 30.0 us                                                      | 24.0 us: 1.25x faster                                      |
| xml_etree_generate   | 94.6 ms                                                      | 85.9 ms: 1.10x faster                                      |
| xml_etree_parse      | 162 ms                                                       | 147 ms: 1.10x faster                                       |
| xml_etree_iterparse  | 110 ms                                                       | 103 ms: 1.08x faster                                       |
| unpickle             | 14.2 us                                                      | 14.6 us: 1.03x slower                                      |
| pickle               | 9.94 us                                                      | 10.3 us: 1.03x slower                                      |
| unpickle_list        | 4.49 us                                                      | 4.70 us: 1.05x slower                                      |
| pickle_list          | 4.11 us                                                      | 4.44 us: 1.08x slower                                      |
| pickle_dict          | 30.0 us                                                      | 32.4 us: 1.08x slower                                      |
| Geometric mean       | (ref)                                                        | 1.15x faster                                               |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231014-pythonperf2-x86_64-python-3.12-3.12.0+-744f752 |
|------------------------|:------------------------------------------------------------:|:----------------------------------------------------------:|
| python_startup         | 11.5 ms                                                      | 11.7 ms: 1.02x slower                                      |
| python_startup_no_site | 7.32 ms                                                      | 8.65 ms: 1.18x slower                                      |
| Geometric mean         | (ref)                                                        | 1.10x slower                                               |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231014-pythonperf2-x86_64-python-3.12-3.12.0+-744f752 |
|-----------|:------------------------------------------------------------:|:----------------------------------------------------------:|
| mako      | 14.7 ms                                                      | 9.99 ms: 1.47x faster                                      |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231014-pythonperf2-x86_64-python-3.12-3.12.0+-744f752 |
|--------------------------|:------------------------------------------------------------:|:----------------------------------------------------------:|
| typing_runtime_protocols | 523 us                                                       | 153 us: 3.42x faster                                       |
| deltablue                | 7.47 ms                                                      | 3.25 ms: 2.30x faster                                      |
| asyncio_tcp              | 782 ms                                                       | 379 ms: 2.06x faster                                       |
| asyncio_tcp_ssl          | 3.09 sec                                                     | 1.57 sec: 1.97x faster                                     |
| richards_super           | 90.8 ms                                                      | 51.1 ms: 1.78x faster                                      |
| logging_silent           | 166 ns                                                       | 93.4 ns: 1.77x faster                                      |
| go                       | 259 ms                                                       | 149 ms: 1.74x faster                                       |
| chaos                    | 107 ms                                                       | 62.7 ms: 1.71x faster                                      |
| scimark_lu               | 164 ms                                                       | 97.6 ms: 1.68x faster                                      |
| richards                 | 74.1 ms                                                      | 44.4 ms: 1.67x faster                                      |
| raytrace                 | 488 ms                                                       | 299 ms: 1.63x faster                                       |
| nbody                    | 137 ms                                                       | 84.2 ms: 1.63x faster                                      |
| sqlglot_parse            | 2.26 ms                                                      | 1.39 ms: 1.63x faster                                      |
| hexiom                   | 9.52 ms                                                      | 5.89 ms: 1.62x faster                                      |
| scimark_sor              | 177 ms                                                       | 110 ms: 1.61x faster                                       |
| scimark_monte_carlo      | 109 ms                                                       | 69.2 ms: 1.58x faster                                      |
| generators               | 58.0 ms                                                      | 37.0 ms: 1.57x faster                                      |
| pyflate                  | 697 ms                                                       | 447 ms: 1.56x faster                                       |
| unpickle_pure_python     | 321 us                                                       | 209 us: 1.53x faster                                       |
| async_tree_none          | 700 ms                                                       | 460 ms: 1.52x faster                                       |
| async_tree_io            | 1.61 sec                                                     | 1.06 sec: 1.52x faster                                     |
| sqlglot_transpile        | 2.71 ms                                                      | 1.79 ms: 1.51x faster                                      |
| spectral_norm            | 136 ms                                                       | 90.7 ms: 1.50x faster                                      |
| async_tree_memoization   | 824 ms                                                       | 552 ms: 1.49x faster                                       |
| crypto_pyaes             | 118 ms                                                       | 80.3 ms: 1.47x faster                                      |
| mako                     | 14.7 ms                                                      | 9.99 ms: 1.47x faster                                      |
| fannkuch                 | 496 ms                                                       | 338 ms: 1.47x faster                                       |
| pickle_pure_python       | 457 us                                                       | 316 us: 1.44x faster                                       |
| float                    | 110 ms                                                       | 77.4 ms: 1.43x faster                                      |
| json_dumps               | 14.2 ms                                                      | 10.2 ms: 1.39x faster                                      |
| regex_compile            | 194 ms                                                       | 141 ms: 1.37x faster                                       |
| tomli_loads              | 2.97 sec                                                     | 2.18 sec: 1.36x faster                                     |
| async_tree_cpu_io_mixed  | 952 ms                                                       | 703 ms: 1.35x faster                                       |
| deepcopy_memo            | 48.9 us                                                      | 36.3 us: 1.35x faster                                      |
| pycparser                | 1.66 sec                                                     | 1.25 sec: 1.34x faster                                     |
| pprint_pformat           | 2.15 sec                                                     | 1.62 sec: 1.33x faster                                     |
| pprint_safe_repr         | 1.05 sec                                                     | 797 ms: 1.32x faster                                       |
| xml_etree_process        | 76.0 ms                                                      | 58.2 ms: 1.31x faster                                      |
| coroutines               | 30.4 ms                                                      | 23.4 ms: 1.30x faster                                      |
| logging_simple           | 8.90 us                                                      | 6.94 us: 1.28x faster                                      |
| tornado_http             | 152 ms                                                       | 120 ms: 1.27x faster                                       |
| logging_format           | 9.57 us                                                      | 7.59 us: 1.26x faster                                      |
| nqueens                  | 112 ms                                                       | 89.4 ms: 1.26x faster                                      |
| comprehensions           | 26.9 us                                                      | 21.5 us: 1.25x faster                                      |
| json_loads               | 30.0 us                                                      | 24.0 us: 1.25x faster                                      |
| deepcopy                 | 454 us                                                       | 367 us: 1.24x faster                                       |
| dulwich_log              | 80.1 ms                                                      | 65.1 ms: 1.23x faster                                      |
| 2to3                     | 350 ms                                                       | 285 ms: 1.23x faster                                       |
| sqlglot_normalize        | 144 ms                                                       | 118 ms: 1.22x faster                                       |
| scimark_sparse_mat_mult  | 5.19 ms                                                      | 4.29 ms: 1.21x faster                                      |
| sqlglot_optimize         | 70.3 ms                                                      | 58.1 ms: 1.21x faster                                      |
| mdp                      | 3.03 sec                                                     | 2.52 sec: 1.20x faster                                     |
| scimark_fft              | 359 ms                                                       | 300 ms: 1.20x faster                                       |
| unpack_sequence          | 59.5 ns                                                      | 50.2 ns: 1.19x faster                                      |
| docutils                 | 3.40 sec                                                     | 2.87 sec: 1.19x faster                                     |
| bench_thread_pool        | 1.14 ms                                                      | 958 us: 1.19x faster                                       |
| dask                     | 463 ms                                                       | 393 ms: 1.18x faster                                       |
| deepcopy_reduce          | 4.03 us                                                      | 3.43 us: 1.17x faster                                      |
| json                     | 5.96 ms                                                      | 5.10 ms: 1.17x faster                                      |
| pathlib                  | 21.7 ms                                                      | 19.0 ms: 1.14x faster                                      |
| create_gc_cycles         | 1.82 ms                                                      | 1.60 ms: 1.14x faster                                      |
| async_generators         | 422 ms                                                       | 381 ms: 1.11x faster                                       |
| xml_etree_generate       | 94.6 ms                                                      | 85.9 ms: 1.10x faster                                      |
| xml_etree_parse          | 162 ms                                                       | 147 ms: 1.10x faster                                       |
| regex_v8                 | 26.6 ms                                                      | 24.3 ms: 1.10x faster                                      |
| meteor_contest           | 137 ms                                                       | 125 ms: 1.09x faster                                       |
| sqlite_synth             | 2.97 us                                                      | 2.73 us: 1.09x faster                                      |
| xml_etree_iterparse      | 110 ms                                                       | 103 ms: 1.08x faster                                       |
| regex_dna                | 259 ms                                                       | 243 ms: 1.07x faster                                       |
| pidigits                 | 271 ms                                                       | 263 ms: 1.03x faster                                       |
| telco                    | 7.14 ms                                                      | 6.96 ms: 1.03x faster                                      |
| python_startup           | 11.5 ms                                                      | 11.7 ms: 1.02x slower                                      |
| unpickle                 | 14.2 us                                                      | 14.6 us: 1.03x slower                                      |
| pickle                   | 9.94 us                                                      | 10.3 us: 1.03x slower                                      |
| unpickle_list            | 4.49 us                                                      | 4.70 us: 1.05x slower                                      |
| pickle_list              | 4.11 us                                                      | 4.44 us: 1.08x slower                                      |
| pickle_dict              | 30.0 us                                                      | 32.4 us: 1.08x slower                                      |
| gc_traversal             | 3.45 ms                                                      | 3.76 ms: 1.09x slower                                      |
| regex_effbot             | 2.99 ms                                                      | 3.49 ms: 1.17x slower                                      |
| python_startup_no_site   | 7.32 ms                                                      | 8.65 ms: 1.18x slower                                      |
| coverage                 | 64.0 ms                                                      | 89.7 ms: 1.40x slower                                      |
| Geometric mean           | (ref)                                                        | 1.30x faster                                               |

Benchmark hidden because not significant (2): mypy2, bench_mp_pool
Ignored benchmarks (16) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.27x
- 95% likely to have a speedup of 1.26x
- 99% likely to have a speedup of 1.23x
