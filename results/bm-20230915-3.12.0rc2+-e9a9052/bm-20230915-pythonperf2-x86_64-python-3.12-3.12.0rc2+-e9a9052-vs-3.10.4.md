
# Results vs. 3.10.4

- fork: python
- ref: 3.12
- machine: linux-x86_64
- commit hash: e9a9052
- commit date: 2023-09-15
- overall geometric mean: 1.29x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.22x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230915-pythonperf2-x86_64-python-3.12-3.12.0rc2+-e9a9052 |
|----------------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| 2to3           | 350 ms                                                       | 285 ms: 1.23x faster                                          |
| docutils       | 3.40 sec                                                     | 2.88 sec: 1.18x faster                                        |
| tornado_http   | 152 ms                                                       | 122 ms: 1.25x faster                                          |
| Geometric mean | (ref)                                                        | 1.22x faster                                                  |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230915-pythonperf2-x86_64-python-3.12-3.12.0rc2+-e9a9052 |
|----------------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| nbody          | 137 ms                                                       | 88.9 ms: 1.54x faster                                         |
| float          | 110 ms                                                       | 78.1 ms: 1.41x faster                                         |
| pidigits       | 271 ms                                                       | 264 ms: 1.02x faster                                          |
| Geometric mean | (ref)                                                        | 1.31x faster                                                  |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230915-pythonperf2-x86_64-python-3.12-3.12.0rc2+-e9a9052 |
|----------------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| regex_compile  | 194 ms                                                       | 145 ms: 1.33x faster                                          |
| regex_v8       | 26.6 ms                                                      | 23.2 ms: 1.15x faster                                         |
| regex_dna      | 259 ms                                                       | 237 ms: 1.09x faster                                          |
| regex_effbot   | 2.99 ms                                                      | 3.62 ms: 1.21x slower                                         |
| Geometric mean | (ref)                                                        | 1.08x faster                                                  |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230915-pythonperf2-x86_64-python-3.12-3.12.0rc2+-e9a9052 |
|----------------------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| unpickle_pure_python | 321 us                                                       | 207 us: 1.55x faster                                          |
| pickle_pure_python   | 457 us                                                       | 318 us: 1.44x faster                                          |
| tomli_loads          | 2.97 sec                                                     | 2.13 sec: 1.39x faster                                        |
| json_dumps           | 14.2 ms                                                      | 10.3 ms: 1.37x faster                                         |
| xml_etree_process    | 76.0 ms                                                      | 59.0 ms: 1.29x faster                                         |
| json_loads           | 30.0 us                                                      | 24.5 us: 1.22x faster                                         |
| xml_etree_generate   | 94.6 ms                                                      | 86.1 ms: 1.10x faster                                         |
| xml_etree_parse      | 162 ms                                                       | 148 ms: 1.09x faster                                          |
| xml_etree_iterparse  | 110 ms                                                       | 106 ms: 1.04x faster                                          |
| unpickle             | 14.2 us                                                      | 14.5 us: 1.02x slower                                         |
| pickle               | 9.94 us                                                      | 10.3 us: 1.04x slower                                         |
| unpickle_list        | 4.49 us                                                      | 4.82 us: 1.07x slower                                         |
| pickle_dict          | 30.0 us                                                      | 32.4 us: 1.08x slower                                         |
| pickle_list          | 4.11 us                                                      | 4.51 us: 1.10x slower                                         |
| Geometric mean       | (ref)                                                        | 1.14x faster                                                  |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230915-pythonperf2-x86_64-python-3.12-3.12.0rc2+-e9a9052 |
|------------------------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| python_startup         | 11.5 ms                                                      | 11.7 ms: 1.02x slower                                         |
| python_startup_no_site | 7.32 ms                                                      | 8.69 ms: 1.19x slower                                         |
| Geometric mean         | (ref)                                                        | 1.10x slower                                                  |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230915-pythonperf2-x86_64-python-3.12-3.12.0rc2+-e9a9052 |
|-----------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| mako      | 14.7 ms                                                      | 9.97 ms: 1.47x faster                                         |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230915-pythonperf2-x86_64-python-3.12-3.12.0rc2+-e9a9052 |
|--------------------------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| typing_runtime_protocols | 523 us                                                       | 156 us: 3.34x faster                                          |
| deltablue                | 7.47 ms                                                      | 3.34 ms: 2.24x faster                                         |
| asyncio_tcp              | 782 ms                                                       | 382 ms: 2.05x faster                                          |
| asyncio_tcp_ssl          | 3.09 sec                                                     | 1.58 sec: 1.96x faster                                        |
| richards_super           | 90.8 ms                                                      | 51.6 ms: 1.76x faster                                         |
| logging_silent           | 166 ns                                                       | 95.1 ns: 1.74x faster                                         |
| go                       | 259 ms                                                       | 149 ms: 1.74x faster                                          |
| chaos                    | 107 ms                                                       | 63.2 ms: 1.70x faster                                         |
| scimark_lu               | 164 ms                                                       | 98.2 ms: 1.67x faster                                         |
| richards                 | 74.1 ms                                                      | 45.0 ms: 1.65x faster                                         |
| scimark_sor              | 177 ms                                                       | 109 ms: 1.63x faster                                          |
| sqlglot_parse            | 2.26 ms                                                      | 1.39 ms: 1.62x faster                                         |
| hexiom                   | 9.52 ms                                                      | 5.89 ms: 1.61x faster                                         |
| generators               | 58.0 ms                                                      | 36.6 ms: 1.59x faster                                         |
| bench_mp_pool            | 7.18 ms                                                      | 4.55 ms: 1.58x faster                                         |
| pyflate                  | 697 ms                                                       | 446 ms: 1.56x faster                                          |
| scimark_monte_carlo      | 109 ms                                                       | 70.5 ms: 1.55x faster                                         |
| unpickle_pure_python     | 321 us                                                       | 207 us: 1.55x faster                                          |
| raytrace                 | 488 ms                                                       | 316 ms: 1.55x faster                                          |
| nbody                    | 137 ms                                                       | 88.9 ms: 1.54x faster                                         |
| sqlglot_transpile        | 2.71 ms                                                      | 1.79 ms: 1.51x faster                                         |
| async_tree_none          | 700 ms                                                       | 466 ms: 1.50x faster                                          |
| async_tree_io            | 1.61 sec                                                     | 1.07 sec: 1.50x faster                                        |
| spectral_norm            | 136 ms                                                       | 91.1 ms: 1.50x faster                                         |
| mako                     | 14.7 ms                                                      | 9.97 ms: 1.47x faster                                         |
| async_tree_memoization   | 824 ms                                                       | 561 ms: 1.47x faster                                          |
| crypto_pyaes             | 118 ms                                                       | 81.4 ms: 1.45x faster                                         |
| pickle_pure_python       | 457 us                                                       | 318 us: 1.44x faster                                          |
| fannkuch                 | 496 ms                                                       | 348 ms: 1.42x faster                                          |
| float                    | 110 ms                                                       | 78.1 ms: 1.41x faster                                         |
| tomli_loads              | 2.97 sec                                                     | 2.13 sec: 1.39x faster                                        |
| json_dumps               | 14.2 ms                                                      | 10.3 ms: 1.37x faster                                         |
| regex_compile            | 194 ms                                                       | 145 ms: 1.33x faster                                          |
| deepcopy_memo            | 48.9 us                                                      | 36.7 us: 1.33x faster                                         |
| async_tree_cpu_io_mixed  | 952 ms                                                       | 715 ms: 1.33x faster                                          |
| coroutines               | 30.4 ms                                                      | 23.0 ms: 1.32x faster                                         |
| pycparser                | 1.66 sec                                                     | 1.26 sec: 1.32x faster                                        |
| pprint_pformat           | 2.15 sec                                                     | 1.66 sec: 1.30x faster                                        |
| pprint_safe_repr         | 1.05 sec                                                     | 813 ms: 1.29x faster                                          |
| xml_etree_process        | 76.0 ms                                                      | 59.0 ms: 1.29x faster                                         |
| mypy2                    | 466 ms                                                       | 367 ms: 1.27x faster                                          |
| logging_simple           | 8.90 us                                                      | 7.04 us: 1.26x faster                                         |
| nqueens                  | 112 ms                                                       | 89.4 ms: 1.26x faster                                         |
| tornado_http             | 152 ms                                                       | 122 ms: 1.25x faster                                          |
| logging_format           | 9.57 us                                                      | 7.70 us: 1.24x faster                                         |
| deepcopy                 | 454 us                                                       | 367 us: 1.24x faster                                          |
| comprehensions           | 26.9 us                                                      | 21.9 us: 1.23x faster                                         |
| sqlglot_normalize        | 144 ms                                                       | 118 ms: 1.23x faster                                          |
| 2to3                     | 350 ms                                                       | 285 ms: 1.23x faster                                          |
| json_loads               | 30.0 us                                                      | 24.5 us: 1.22x faster                                         |
| sqlglot_optimize         | 70.3 ms                                                      | 57.8 ms: 1.22x faster                                         |
| dulwich_log              | 80.1 ms                                                      | 65.9 ms: 1.21x faster                                         |
| mdp                      | 3.03 sec                                                     | 2.50 sec: 1.21x faster                                        |
| scimark_fft              | 359 ms                                                       | 300 ms: 1.20x faster                                          |
| deepcopy_reduce          | 4.03 us                                                      | 3.38 us: 1.19x faster                                         |
| scimark_sparse_mat_mult  | 5.19 ms                                                      | 4.37 ms: 1.19x faster                                         |
| docutils                 | 3.40 sec                                                     | 2.88 sec: 1.18x faster                                        |
| bench_thread_pool        | 1.14 ms                                                      | 966 us: 1.18x faster                                          |
| json                     | 5.96 ms                                                      | 5.15 ms: 1.16x faster                                         |
| regex_v8                 | 26.6 ms                                                      | 23.2 ms: 1.15x faster                                         |
| pathlib                  | 21.7 ms                                                      | 19.7 ms: 1.10x faster                                         |
| xml_etree_generate       | 94.6 ms                                                      | 86.1 ms: 1.10x faster                                         |
| regex_dna                | 259 ms                                                       | 237 ms: 1.09x faster                                          |
| async_generators         | 422 ms                                                       | 387 ms: 1.09x faster                                          |
| sqlite_synth             | 2.97 us                                                      | 2.73 us: 1.09x faster                                         |
| xml_etree_parse          | 162 ms                                                       | 148 ms: 1.09x faster                                          |
| meteor_contest           | 137 ms                                                       | 126 ms: 1.08x faster                                          |
| create_gc_cycles         | 1.82 ms                                                      | 1.69 ms: 1.08x faster                                         |
| unpack_sequence          | 59.5 ns                                                      | 55.2 ns: 1.08x faster                                         |
| xml_etree_iterparse      | 110 ms                                                       | 106 ms: 1.04x faster                                          |
| pidigits                 | 271 ms                                                       | 264 ms: 1.02x faster                                          |
| telco                    | 7.14 ms                                                      | 7.07 ms: 1.01x faster                                         |
| python_startup           | 11.5 ms                                                      | 11.7 ms: 1.02x slower                                         |
| unpickle                 | 14.2 us                                                      | 14.5 us: 1.02x slower                                         |
| pickle                   | 9.94 us                                                      | 10.3 us: 1.04x slower                                         |
| unpickle_list            | 4.49 us                                                      | 4.82 us: 1.07x slower                                         |
| pickle_dict              | 30.0 us                                                      | 32.4 us: 1.08x slower                                         |
| pickle_list              | 4.11 us                                                      | 4.51 us: 1.10x slower                                         |
| gc_traversal             | 3.45 ms                                                      | 3.98 ms: 1.15x slower                                         |
| python_startup_no_site   | 7.32 ms                                                      | 8.69 ms: 1.19x slower                                         |
| regex_effbot             | 2.99 ms                                                      | 3.62 ms: 1.21x slower                                         |
| dask                     | 463 ms                                                       | 565 ms: 1.22x slower                                          |
| coverage                 | 64.0 ms                                                      | 91.8 ms: 1.44x slower                                         |
| Geometric mean           | (ref)                                                        | 1.29x faster                                                  |
Ignored benchmarks (16) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.26x
- 95% likely to have a speedup of 1.25x
- 99% likely to have a speedup of 1.22x
