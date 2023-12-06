
# Results vs. 3.10.4

- fork: python
- ref: 3.12
- machine: windows-amd64
- commit hash: 744f752
- commit date: 2023-10-14
- overall geometric mean: 1.17x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.11x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231014-pythonperf1-amd64-python-3.12-3.12.0+-744f752 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------:|
| 2to3           | 237 ms                                                      | 214 ms: 1.11x faster                                      |
| docutils       | 1.89 sec                                                    | 1.63 sec: 1.16x faster                                    |
| tornado_http   | 109 ms                                                      | 91.5 ms: 1.19x faster                                     |
| Geometric mean | (ref)                                                       | 1.15x faster                                              |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231014-pythonperf1-amd64-python-3.12-3.12.0+-744f752 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------:|
| float          | 60.2 ms                                                     | 53.4 ms: 1.13x faster                                     |
| nbody          | 69.3 ms                                                     | 70.6 ms: 1.02x slower                                     |
| pidigits       | 145 ms                                                      | 150 ms: 1.03x slower                                      |
| Geometric mean | (ref)                                                       | 1.02x faster                                              |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231014-pythonperf1-amd64-python-3.12-3.12.0+-744f752 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------:|
| regex_compile  | 103 ms                                                      | 87.6 ms: 1.18x faster                                     |
| regex_v8       | 15.0 ms                                                     | 13.7 ms: 1.10x faster                                     |
| regex_dna      | 132 ms                                                      | 122 ms: 1.08x faster                                      |
| regex_effbot   | 1.66 ms                                                     | 1.64 ms: 1.02x faster                                     |
| Geometric mean | (ref)                                                       | 1.09x faster                                              |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231014-pythonperf1-amd64-python-3.12-3.12.0+-744f752 |
|----------------------|:-----------------------------------------------------------:|:---------------------------------------------------------:|
| json_dumps           | 8.50 ms                                                     | 5.68 ms: 1.50x faster                                     |
| pickle_pure_python   | 257 us                                                      | 198 us: 1.30x faster                                      |
| unpickle_pure_python | 171 us                                                      | 138 us: 1.24x faster                                      |
| xml_etree_process    | 43.4 ms                                                     | 38.1 ms: 1.14x faster                                     |
| tomli_loads          | 1.62 sec                                                    | 1.43 sec: 1.14x faster                                    |
| unpickle             | 9.17 us                                                     | 8.26 us: 1.11x faster                                     |
| xml_etree_parse      | 102 ms                                                      | 92.3 ms: 1.10x faster                                     |
| json_loads           | 14.2 us                                                     | 13.7 us: 1.04x faster                                     |
| unpickle_list        | 2.81 us                                                     | 2.74 us: 1.03x faster                                     |
| xml_etree_generate   | 54.5 ms                                                     | 55.6 ms: 1.02x slower                                     |
| pickle               | 6.80 us                                                     | 7.10 us: 1.04x slower                                     |
| pickle_dict          | 16.9 us                                                     | 18.3 us: 1.08x slower                                     |
| pickle_list          | 2.59 us                                                     | 2.88 us: 1.11x slower                                     |
| Geometric mean       | (ref)                                                       | 1.09x faster                                              |

Benchmark hidden because not significant (1): xml_etree_iterparse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231014-pythonperf1-amd64-python-3.12-3.12.0+-744f752 |
|------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------:|
| python_startup         | 20.0 ms                                                     | 18.8 ms: 1.06x faster                                     |
| python_startup_no_site | 15.5 ms                                                     | 15.9 ms: 1.02x slower                                     |
| Geometric mean         | (ref)                                                       | 1.02x faster                                              |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231014-pythonperf1-amd64-python-3.12-3.12.0+-744f752 |
|-----------|:-----------------------------------------------------------:|:---------------------------------------------------------:|
| mako      | 8.80 ms                                                     | 6.96 ms: 1.27x faster                                     |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231014-pythonperf1-amd64-python-3.12-3.12.0+-744f752 |
|--------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------:|
| typing_runtime_protocols | 325 us                                                      | 103 us: 3.15x faster                                      |
| deltablue                | 4.17 ms                                                     | 2.15 ms: 1.94x faster                                     |
| mypy2                    | 352 ms                                                      | 209 ms: 1.68x faster                                      |
| richards_super           | 51.7 ms                                                     | 31.0 ms: 1.67x faster                                     |
| logging_silent           | 96.4 ns                                                     | 60.6 ns: 1.59x faster                                     |
| asyncio_tcp              | 712 ms                                                      | 471 ms: 1.51x faster                                      |
| richards                 | 41.2 ms                                                     | 27.3 ms: 1.51x faster                                     |
| async_tree_io            | 1.07 sec                                                    | 709 ms: 1.50x faster                                      |
| json_dumps               | 8.50 ms                                                     | 5.68 ms: 1.50x faster                                     |
| sqlglot_parse            | 1.22 ms                                                     | 818 us: 1.49x faster                                      |
| async_tree_memoization   | 497 ms                                                      | 336 ms: 1.48x faster                                      |
| async_tree_none          | 420 ms                                                      | 290 ms: 1.45x faster                                      |
| go                       | 136 ms                                                      | 94.1 ms: 1.45x faster                                     |
| scimark_lu               | 85.4 ms                                                     | 59.4 ms: 1.44x faster                                     |
| sqlglot_transpile        | 1.46 ms                                                     | 1.04 ms: 1.41x faster                                     |
| raytrace                 | 271 ms                                                      | 195 ms: 1.39x faster                                      |
| generators               | 31.6 ms                                                     | 23.0 ms: 1.37x faster                                     |
| chaos                    | 58.9 ms                                                     | 43.4 ms: 1.36x faster                                     |
| hexiom                   | 5.52 ms                                                     | 4.14 ms: 1.33x faster                                     |
| crypto_pyaes             | 62.3 ms                                                     | 47.2 ms: 1.32x faster                                     |
| pyflate                  | 387 ms                                                      | 295 ms: 1.31x faster                                      |
| pickle_pure_python       | 257 us                                                      | 198 us: 1.30x faster                                      |
| scimark_sor              | 105 ms                                                      | 82.4 ms: 1.27x faster                                     |
| async_tree_cpu_io_mixed  | 609 ms                                                      | 479 ms: 1.27x faster                                      |
| mako                     | 8.80 ms                                                     | 6.96 ms: 1.27x faster                                     |
| scimark_monte_carlo      | 55.9 ms                                                     | 44.5 ms: 1.26x faster                                     |
| unpickle_pure_python     | 171 us                                                      | 138 us: 1.24x faster                                      |
| pycparser                | 868 ms                                                      | 701 ms: 1.24x faster                                      |
| spectral_norm            | 78.0 ms                                                     | 64.6 ms: 1.21x faster                                     |
| dask                     | 305 ms                                                      | 254 ms: 1.20x faster                                      |
| tornado_http             | 109 ms                                                      | 91.5 ms: 1.19x faster                                     |
| aiohttp                  | 1.01 ms                                                     | 846 us: 1.19x faster                                      |
| regex_compile            | 103 ms                                                      | 87.6 ms: 1.18x faster                                     |
| deepcopy_memo            | 28.5 us                                                     | 24.5 us: 1.16x faster                                     |
| docutils                 | 1.89 sec                                                    | 1.63 sec: 1.16x faster                                    |
| pprint_pformat           | 1.21 sec                                                    | 1.05 sec: 1.15x faster                                    |
| bench_thread_pool        | 946 us                                                      | 828 us: 1.14x faster                                      |
| pprint_safe_repr         | 589 ms                                                      | 516 ms: 1.14x faster                                      |
| xml_etree_process        | 43.4 ms                                                     | 38.1 ms: 1.14x faster                                     |
| sqlglot_optimize         | 39.0 ms                                                     | 34.2 ms: 1.14x faster                                     |
| tomli_loads              | 1.62 sec                                                    | 1.43 sec: 1.14x faster                                    |
| float                    | 60.2 ms                                                     | 53.4 ms: 1.13x faster                                     |
| mdp                      | 1.71 sec                                                    | 1.52 sec: 1.13x faster                                    |
| dulwich_log              | 47.6 ms                                                     | 42.4 ms: 1.12x faster                                     |
| unpickle                 | 9.17 us                                                     | 8.26 us: 1.11x faster                                     |
| 2to3                     | 237 ms                                                      | 214 ms: 1.11x faster                                      |
| create_gc_cycles         | 782 us                                                      | 705 us: 1.11x faster                                      |
| xml_etree_parse          | 102 ms                                                      | 92.3 ms: 1.10x faster                                     |
| regex_v8                 | 15.0 ms                                                     | 13.7 ms: 1.10x faster                                     |
| comprehensions           | 16.0 us                                                     | 14.5 us: 1.10x faster                                     |
| coroutines               | 15.9 ms                                                     | 14.5 ms: 1.10x faster                                     |
| sqlglot_normalize        | 202 ms                                                      | 185 ms: 1.09x faster                                      |
| regex_dna                | 132 ms                                                      | 122 ms: 1.08x faster                                      |
| nqueens                  | 67.0 ms                                                     | 62.5 ms: 1.07x faster                                     |
| asyncio_tcp_ssl          | 2.03 sec                                                    | 1.91 sec: 1.06x faster                                    |
| python_startup           | 20.0 ms                                                     | 18.8 ms: 1.06x faster                                     |
| scimark_sparse_mat_mult  | 2.66 ms                                                     | 2.51 ms: 1.06x faster                                     |
| scimark_fft              | 193 ms                                                      | 183 ms: 1.06x faster                                      |
| sqlite_synth             | 1.84 us                                                     | 1.74 us: 1.05x faster                                     |
| deepcopy                 | 255 us                                                      | 242 us: 1.05x faster                                      |
| json                     | 3.05 ms                                                     | 2.92 ms: 1.04x faster                                     |
| json_loads               | 14.2 us                                                     | 13.7 us: 1.04x faster                                     |
| unpickle_list            | 2.81 us                                                     | 2.74 us: 1.03x faster                                     |
| deepcopy_reduce          | 2.16 us                                                     | 2.12 us: 1.02x faster                                     |
| regex_effbot             | 1.66 ms                                                     | 1.64 ms: 1.02x faster                                     |
| fannkuch                 | 258 ms                                                      | 254 ms: 1.01x faster                                      |
| meteor_contest           | 72.5 ms                                                     | 73.1 ms: 1.01x slower                                     |
| logging_simple           | 6.20 us                                                     | 6.25 us: 1.01x slower                                     |
| logging_format           | 6.66 us                                                     | 6.76 us: 1.01x slower                                     |
| nbody                    | 69.3 ms                                                     | 70.6 ms: 1.02x slower                                     |
| xml_etree_generate       | 54.5 ms                                                     | 55.6 ms: 1.02x slower                                     |
| python_startup_no_site   | 15.5 ms                                                     | 15.9 ms: 1.02x slower                                     |
| pidigits                 | 145 ms                                                      | 150 ms: 1.03x slower                                      |
| bench_mp_pool            | 60.7 ms                                                     | 62.8 ms: 1.03x slower                                     |
| pickle                   | 6.80 us                                                     | 7.10 us: 1.04x slower                                     |
| async_generators         | 224 ms                                                      | 236 ms: 1.06x slower                                      |
| telco                    | 3.78 ms                                                     | 4.05 ms: 1.07x slower                                     |
| pickle_dict              | 16.9 us                                                     | 18.3 us: 1.08x slower                                     |
| gc_traversal             | 1.34 ms                                                     | 1.47 ms: 1.09x slower                                     |
| pickle_list              | 2.59 us                                                     | 2.88 us: 1.11x slower                                     |
| unpack_sequence          | 37.8 ns                                                     | 47.7 ns: 1.26x slower                                     |
| coverage                 | 40.0 ms                                                     | 50.5 ms: 1.26x slower                                     |
| Geometric mean           | (ref)                                                       | 1.17x faster                                              |

Benchmark hidden because not significant (2): xml_etree_iterparse, pathlib
Ignored benchmarks (14) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120.json: chameleon, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.12x
- 95% likely to have a speedup of 1.12x
- 99% likely to have a speedup of 1.11x
