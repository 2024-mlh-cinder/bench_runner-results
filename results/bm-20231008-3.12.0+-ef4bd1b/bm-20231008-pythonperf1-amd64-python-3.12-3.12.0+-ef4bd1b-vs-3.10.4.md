
# Results vs. 3.10.4

- fork: python
- ref: 3.12
- machine: windows-amd64
- commit hash: ef4bd1b
- commit date: 2023-10-08
- overall geometric mean: 1.19x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.12x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231008-pythonperf1-amd64-python-3.12-3.12.0+-ef4bd1b |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------:|
| 2to3           | 237 ms                                                      | 214 ms: 1.11x faster                                      |
| docutils       | 1.89 sec                                                    | 1.62 sec: 1.17x faster                                    |
| tornado_http   | 109 ms                                                      | 88.4 ms: 1.23x faster                                     |
| Geometric mean | (ref)                                                       | 1.17x faster                                              |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231008-pythonperf1-amd64-python-3.12-3.12.0+-ef4bd1b |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------:|
| float          | 60.2 ms                                                     | 55.4 ms: 1.09x faster                                     |
| nbody          | 69.3 ms                                                     | 70.0 ms: 1.01x slower                                     |
| pidigits       | 145 ms                                                      | 150 ms: 1.04x slower                                      |
| Geometric mean | (ref)                                                       | 1.01x faster                                              |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231008-pythonperf1-amd64-python-3.12-3.12.0+-ef4bd1b |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------:|
| regex_compile  | 103 ms                                                      | 88.1 ms: 1.17x faster                                     |
| regex_v8       | 15.0 ms                                                     | 13.2 ms: 1.14x faster                                     |
| regex_dna      | 132 ms                                                      | 117 ms: 1.13x faster                                      |
| regex_effbot   | 1.66 ms                                                     | 1.57 ms: 1.06x faster                                     |
| Geometric mean | (ref)                                                       | 1.12x faster                                              |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231008-pythonperf1-amd64-python-3.12-3.12.0+-ef4bd1b |
|----------------------|:-----------------------------------------------------------:|:---------------------------------------------------------:|
| json_dumps           | 8.50 ms                                                     | 5.71 ms: 1.49x faster                                     |
| pickle_pure_python   | 257 us                                                      | 194 us: 1.33x faster                                      |
| unpickle_pure_python | 171 us                                                      | 134 us: 1.28x faster                                      |
| tomli_loads          | 1.62 sec                                                    | 1.37 sec: 1.19x faster                                    |
| unpickle             | 9.17 us                                                     | 8.04 us: 1.14x faster                                     |
| xml_etree_process    | 43.4 ms                                                     | 38.4 ms: 1.13x faster                                     |
| xml_etree_parse      | 102 ms                                                      | 90.6 ms: 1.12x faster                                     |
| json_loads           | 14.2 us                                                     | 13.6 us: 1.04x faster                                     |
| pickle               | 6.80 us                                                     | 6.90 us: 1.01x slower                                     |
| xml_etree_generate   | 54.5 ms                                                     | 56.3 ms: 1.03x slower                                     |
| pickle_list          | 2.59 us                                                     | 2.80 us: 1.08x slower                                     |
| pickle_dict          | 16.9 us                                                     | 18.5 us: 1.09x slower                                     |
| Geometric mean       | (ref)                                                       | 1.10x faster                                              |

Benchmark hidden because not significant (2): unpickle_list, xml_etree_iterparse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231008-pythonperf1-amd64-python-3.12-3.12.0+-ef4bd1b |
|------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------:|
| python_startup         | 20.0 ms                                                     | 18.7 ms: 1.07x faster                                     |
| python_startup_no_site | 15.5 ms                                                     | 15.9 ms: 1.02x slower                                     |
| Geometric mean         | (ref)                                                       | 1.02x faster                                              |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231008-pythonperf1-amd64-python-3.12-3.12.0+-ef4bd1b |
|-----------|:-----------------------------------------------------------:|:---------------------------------------------------------:|
| mako      | 8.80 ms                                                     | 6.97 ms: 1.26x faster                                     |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231008-pythonperf1-amd64-python-3.12-3.12.0+-ef4bd1b |
|--------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------:|
| typing_runtime_protocols | 325 us                                                      | 99.7 us: 3.26x faster                                     |
| deltablue                | 4.17 ms                                                     | 2.13 ms: 1.95x faster                                     |
| richards_super           | 51.7 ms                                                     | 30.2 ms: 1.71x faster                                     |
| mypy2                    | 352 ms                                                      | 208 ms: 1.69x faster                                      |
| logging_silent           | 96.4 ns                                                     | 60.5 ns: 1.59x faster                                     |
| richards                 | 41.2 ms                                                     | 26.5 ms: 1.55x faster                                     |
| sqlglot_parse            | 1.22 ms                                                     | 806 us: 1.51x faster                                      |
| asyncio_tcp              | 712 ms                                                      | 473 ms: 1.51x faster                                      |
| go                       | 136 ms                                                      | 90.5 ms: 1.50x faster                                     |
| async_tree_io            | 1.07 sec                                                    | 713 ms: 1.49x faster                                      |
| json_dumps               | 8.50 ms                                                     | 5.71 ms: 1.49x faster                                     |
| async_tree_memoization   | 497 ms                                                      | 337 ms: 1.48x faster                                      |
| async_tree_none          | 420 ms                                                      | 288 ms: 1.46x faster                                      |
| scimark_lu               | 85.4 ms                                                     | 58.8 ms: 1.45x faster                                     |
| sqlglot_transpile        | 1.46 ms                                                     | 1.02 ms: 1.43x faster                                     |
| generators               | 31.6 ms                                                     | 22.5 ms: 1.40x faster                                     |
| raytrace                 | 271 ms                                                      | 196 ms: 1.38x faster                                      |
| chaos                    | 58.9 ms                                                     | 42.7 ms: 1.38x faster                                     |
| hexiom                   | 5.52 ms                                                     | 4.05 ms: 1.36x faster                                     |
| crypto_pyaes             | 62.3 ms                                                     | 45.8 ms: 1.36x faster                                     |
| pickle_pure_python       | 257 us                                                      | 194 us: 1.33x faster                                      |
| pyflate                  | 387 ms                                                      | 293 ms: 1.32x faster                                      |
| scimark_sor              | 105 ms                                                      | 79.6 ms: 1.32x faster                                     |
| unpickle_pure_python     | 171 us                                                      | 134 us: 1.28x faster                                      |
| scimark_monte_carlo      | 55.9 ms                                                     | 43.7 ms: 1.28x faster                                     |
| async_tree_cpu_io_mixed  | 609 ms                                                      | 480 ms: 1.27x faster                                      |
| pycparser                | 868 ms                                                      | 685 ms: 1.27x faster                                      |
| mako                     | 8.80 ms                                                     | 6.97 ms: 1.26x faster                                     |
| mdp                      | 1.71 sec                                                    | 1.37 sec: 1.25x faster                                    |
| spectral_norm            | 78.0 ms                                                     | 63.1 ms: 1.24x faster                                     |
| tornado_http             | 109 ms                                                      | 88.4 ms: 1.23x faster                                     |
| deepcopy_memo            | 28.5 us                                                     | 23.7 us: 1.20x faster                                     |
| dask                     | 305 ms                                                      | 256 ms: 1.19x faster                                      |
| tomli_loads              | 1.62 sec                                                    | 1.37 sec: 1.19x faster                                    |
| regex_compile            | 103 ms                                                      | 88.1 ms: 1.17x faster                                     |
| aiohttp                  | 1.01 ms                                                     | 861 us: 1.17x faster                                      |
| docutils                 | 1.89 sec                                                    | 1.62 sec: 1.17x faster                                    |
| pprint_pformat           | 1.21 sec                                                    | 1.04 sec: 1.17x faster                                    |
| pprint_safe_repr         | 589 ms                                                      | 506 ms: 1.16x faster                                      |
| unpickle                 | 9.17 us                                                     | 8.04 us: 1.14x faster                                     |
| bench_thread_pool        | 946 us                                                      | 830 us: 1.14x faster                                      |
| coroutines               | 15.9 ms                                                     | 14.0 ms: 1.14x faster                                     |
| regex_v8                 | 15.0 ms                                                     | 13.2 ms: 1.14x faster                                     |
| sqlglot_optimize         | 39.0 ms                                                     | 34.3 ms: 1.14x faster                                     |
| xml_etree_process        | 43.4 ms                                                     | 38.4 ms: 1.13x faster                                     |
| regex_dna                | 132 ms                                                      | 117 ms: 1.13x faster                                      |
| xml_etree_parse          | 102 ms                                                      | 90.6 ms: 1.12x faster                                     |
| dulwich_log              | 47.6 ms                                                     | 42.5 ms: 1.12x faster                                     |
| comprehensions           | 16.0 us                                                     | 14.3 us: 1.12x faster                                     |
| 2to3                     | 237 ms                                                      | 214 ms: 1.11x faster                                      |
| sqlglot_normalize        | 202 ms                                                      | 185 ms: 1.09x faster                                      |
| float                    | 60.2 ms                                                     | 55.4 ms: 1.09x faster                                     |
| scimark_fft              | 193 ms                                                      | 178 ms: 1.08x faster                                      |
| create_gc_cycles         | 782 us                                                      | 724 us: 1.08x faster                                      |
| python_startup           | 20.0 ms                                                     | 18.7 ms: 1.07x faster                                     |
| deepcopy                 | 255 us                                                      | 240 us: 1.07x faster                                      |
| scimark_sparse_mat_mult  | 2.66 ms                                                     | 2.51 ms: 1.06x faster                                     |
| regex_effbot             | 1.66 ms                                                     | 1.57 ms: 1.06x faster                                     |
| sqlite_synth             | 1.84 us                                                     | 1.75 us: 1.05x faster                                     |
| json                     | 3.05 ms                                                     | 2.90 ms: 1.05x faster                                     |
| nqueens                  | 67.0 ms                                                     | 64.0 ms: 1.05x faster                                     |
| fannkuch                 | 258 ms                                                      | 246 ms: 1.05x faster                                      |
| asyncio_tcp_ssl          | 2.03 sec                                                    | 1.94 sec: 1.05x faster                                    |
| json_loads               | 14.2 us                                                     | 13.6 us: 1.04x faster                                     |
| nbody                    | 69.3 ms                                                     | 70.0 ms: 1.01x slower                                     |
| unpack_sequence          | 37.8 ns                                                     | 38.3 ns: 1.01x slower                                     |
| logging_simple           | 6.20 us                                                     | 6.28 us: 1.01x slower                                     |
| pickle                   | 6.80 us                                                     | 6.90 us: 1.01x slower                                     |
| logging_format           | 6.66 us                                                     | 6.80 us: 1.02x slower                                     |
| meteor_contest           | 72.5 ms                                                     | 74.1 ms: 1.02x slower                                     |
| python_startup_no_site   | 15.5 ms                                                     | 15.9 ms: 1.02x slower                                     |
| xml_etree_generate       | 54.5 ms                                                     | 56.3 ms: 1.03x slower                                     |
| bench_mp_pool            | 60.7 ms                                                     | 62.9 ms: 1.04x slower                                     |
| pidigits                 | 145 ms                                                      | 150 ms: 1.04x slower                                      |
| async_generators         | 224 ms                                                      | 235 ms: 1.05x slower                                      |
| telco                    | 3.78 ms                                                     | 4.08 ms: 1.08x slower                                     |
| pickle_list              | 2.59 us                                                     | 2.80 us: 1.08x slower                                     |
| pickle_dict              | 16.9 us                                                     | 18.5 us: 1.09x slower                                     |
| gc_traversal             | 1.34 ms                                                     | 1.49 ms: 1.11x slower                                     |
| coverage                 | 40.0 ms                                                     | 51.3 ms: 1.28x slower                                     |
| Geometric mean           | (ref)                                                       | 1.19x faster                                              |

Benchmark hidden because not significant (4): unpickle_list, deepcopy_reduce, xml_etree_iterparse, pathlib
Ignored benchmarks (14) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120.json: chameleon, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.14x
- 95% likely to have a speedup of 1.13x
- 99% likely to have a speedup of 1.12x
