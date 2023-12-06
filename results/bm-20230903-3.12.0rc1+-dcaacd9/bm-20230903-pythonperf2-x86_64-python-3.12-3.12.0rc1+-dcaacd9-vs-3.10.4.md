
# Results vs. 3.10.4

- fork: python
- ref: 3.12
- machine: linux-x86_64
- commit hash: dcaacd9
- commit date: 2023-09-03
- overall geometric mean: 1.30x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.22x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230903-pythonperf2-x86_64-python-3.12-3.12.0rc1+-dcaacd9 |
|----------------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| 2to3           | 350 ms                                                       | 285 ms: 1.23x faster                                          |
| docutils       | 3.40 sec                                                     | 2.90 sec: 1.18x faster                                        |
| tornado_http   | 152 ms                                                       | 120 ms: 1.27x faster                                          |
| Geometric mean | (ref)                                                        | 1.22x faster                                                  |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230903-pythonperf2-x86_64-python-3.12-3.12.0rc1+-dcaacd9 |
|----------------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| nbody          | 137 ms                                                       | 95.9 ms: 1.43x faster                                         |
| float          | 110 ms                                                       | 79.1 ms: 1.40x faster                                         |
| pidigits       | 271 ms                                                       | 264 ms: 1.02x faster                                          |
| Geometric mean | (ref)                                                        | 1.27x faster                                                  |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230903-pythonperf2-x86_64-python-3.12-3.12.0rc1+-dcaacd9 |
|----------------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| regex_compile  | 194 ms                                                       | 145 ms: 1.33x faster                                          |
| regex_v8       | 26.6 ms                                                      | 24.6 ms: 1.08x faster                                         |
| regex_dna      | 259 ms                                                       | 245 ms: 1.06x faster                                          |
| regex_effbot   | 2.99 ms                                                      | 3.45 ms: 1.15x slower                                         |
| Geometric mean | (ref)                                                        | 1.07x faster                                                  |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230903-pythonperf2-x86_64-python-3.12-3.12.0rc1+-dcaacd9 |
|----------------------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| unpickle_pure_python | 321 us                                                       | 206 us: 1.56x faster                                          |
| pickle_pure_python   | 457 us                                                       | 325 us: 1.41x faster                                          |
| json_dumps           | 14.2 ms                                                      | 10.2 ms: 1.40x faster                                         |
| tomli_loads          | 2.97 sec                                                     | 2.16 sec: 1.37x faster                                        |
| xml_etree_process    | 76.0 ms                                                      | 59.5 ms: 1.28x faster                                         |
| json_loads           | 30.0 us                                                      | 24.4 us: 1.23x faster                                         |
| xml_etree_generate   | 94.6 ms                                                      | 87.4 ms: 1.08x faster                                         |
| xml_etree_parse      | 162 ms                                                       | 151 ms: 1.07x faster                                          |
| xml_etree_iterparse  | 110 ms                                                       | 105 ms: 1.05x faster                                          |
| pickle               | 9.94 us                                                      | 9.83 us: 1.01x faster                                         |
| pickle_list          | 4.11 us                                                      | 4.21 us: 1.03x slower                                         |
| unpickle             | 14.2 us                                                      | 14.6 us: 1.03x slower                                         |
| pickle_dict          | 30.0 us                                                      | 31.5 us: 1.05x slower                                         |
| unpickle_list        | 4.49 us                                                      | 4.79 us: 1.07x slower                                         |
| Geometric mean       | (ref)                                                        | 1.15x faster                                                  |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230903-pythonperf2-x86_64-python-3.12-3.12.0rc1+-dcaacd9 |
|------------------------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| python_startup         | 11.5 ms                                                      | 11.7 ms: 1.02x slower                                         |
| python_startup_no_site | 7.32 ms                                                      | 8.66 ms: 1.18x slower                                         |
| Geometric mean         | (ref)                                                        | 1.10x slower                                                  |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230903-pythonperf2-x86_64-python-3.12-3.12.0rc1+-dcaacd9 |
|-----------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| mako      | 14.7 ms                                                      | 9.93 ms: 1.48x faster                                         |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230903-pythonperf2-x86_64-python-3.12-3.12.0rc1+-dcaacd9 |
|--------------------------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| typing_runtime_protocols | 523 us                                                       | 151 us: 3.47x faster                                          |
| deltablue                | 7.47 ms                                                      | 3.23 ms: 2.31x faster                                         |
| asyncio_tcp              | 782 ms                                                       | 387 ms: 2.02x faster                                          |
| asyncio_tcp_ssl          | 3.09 sec                                                     | 1.58 sec: 1.96x faster                                        |
| logging_silent           | 166 ns                                                       | 92.1 ns: 1.80x faster                                         |
| richards_super           | 90.8 ms                                                      | 50.8 ms: 1.79x faster                                         |
| go                       | 259 ms                                                       | 146 ms: 1.77x faster                                          |
| chaos                    | 107 ms                                                       | 62.2 ms: 1.72x faster                                         |
| richards                 | 74.1 ms                                                      | 43.9 ms: 1.69x faster                                         |
| scimark_lu               | 164 ms                                                       | 97.0 ms: 1.69x faster                                         |
| scimark_sor              | 177 ms                                                       | 107 ms: 1.65x faster                                          |
| raytrace                 | 488 ms                                                       | 297 ms: 1.65x faster                                          |
| hexiom                   | 9.52 ms                                                      | 5.83 ms: 1.63x faster                                         |
| sqlglot_parse            | 2.26 ms                                                      | 1.40 ms: 1.61x faster                                         |
| pyflate                  | 697 ms                                                       | 443 ms: 1.57x faster                                          |
| generators               | 58.0 ms                                                      | 37.0 ms: 1.57x faster                                         |
| unpickle_pure_python     | 321 us                                                       | 206 us: 1.56x faster                                          |
| scimark_monte_carlo      | 109 ms                                                       | 70.5 ms: 1.55x faster                                         |
| async_tree_none          | 700 ms                                                       | 456 ms: 1.53x faster                                          |
| bench_mp_pool            | 7.18 ms                                                      | 4.69 ms: 1.53x faster                                         |
| async_tree_io            | 1.61 sec                                                     | 1.05 sec: 1.53x faster                                        |
| sqlglot_transpile        | 2.71 ms                                                      | 1.80 ms: 1.51x faster                                         |
| spectral_norm            | 136 ms                                                       | 90.4 ms: 1.51x faster                                         |
| async_tree_memoization   | 824 ms                                                       | 549 ms: 1.50x faster                                          |
| mako                     | 14.7 ms                                                      | 9.93 ms: 1.48x faster                                         |
| crypto_pyaes             | 118 ms                                                       | 81.1 ms: 1.46x faster                                         |
| nbody                    | 137 ms                                                       | 95.9 ms: 1.43x faster                                         |
| fannkuch                 | 496 ms                                                       | 347 ms: 1.43x faster                                          |
| pickle_pure_python       | 457 us                                                       | 325 us: 1.41x faster                                          |
| json_dumps               | 14.2 ms                                                      | 10.2 ms: 1.40x faster                                         |
| float                    | 110 ms                                                       | 79.1 ms: 1.40x faster                                         |
| tomli_loads              | 2.97 sec                                                     | 2.16 sec: 1.37x faster                                        |
| async_tree_cpu_io_mixed  | 952 ms                                                       | 702 ms: 1.36x faster                                          |
| regex_compile            | 194 ms                                                       | 145 ms: 1.33x faster                                          |
| logging_simple           | 8.90 us                                                      | 6.71 us: 1.32x faster                                         |
| coroutines               | 30.4 ms                                                      | 23.0 ms: 1.32x faster                                         |
| deepcopy_memo            | 48.9 us                                                      | 37.1 us: 1.32x faster                                         |
| pprint_pformat           | 2.15 sec                                                     | 1.64 sec: 1.31x faster                                        |
| pprint_safe_repr         | 1.05 sec                                                     | 805 ms: 1.30x faster                                          |
| pycparser                | 1.66 sec                                                     | 1.28 sec: 1.30x faster                                        |
| logging_format           | 9.57 us                                                      | 7.39 us: 1.29x faster                                         |
| xml_etree_process        | 76.0 ms                                                      | 59.5 ms: 1.28x faster                                         |
| mypy2                    | 466 ms                                                       | 366 ms: 1.27x faster                                          |
| tornado_http             | 152 ms                                                       | 120 ms: 1.27x faster                                          |
| nqueens                  | 112 ms                                                       | 89.3 ms: 1.26x faster                                         |
| comprehensions           | 26.9 us                                                      | 21.8 us: 1.23x faster                                         |
| sqlglot_normalize        | 144 ms                                                       | 117 ms: 1.23x faster                                          |
| json_loads               | 30.0 us                                                      | 24.4 us: 1.23x faster                                         |
| dulwich_log              | 80.1 ms                                                      | 65.2 ms: 1.23x faster                                         |
| 2to3                     | 350 ms                                                       | 285 ms: 1.23x faster                                          |
| unpack_sequence          | 59.5 ns                                                      | 49.1 ns: 1.21x faster                                         |
| sqlglot_optimize         | 70.3 ms                                                      | 58.0 ms: 1.21x faster                                         |
| scimark_sparse_mat_mult  | 5.19 ms                                                      | 4.29 ms: 1.21x faster                                         |
| scimark_fft              | 359 ms                                                       | 298 ms: 1.21x faster                                          |
| mdp                      | 3.03 sec                                                     | 2.53 sec: 1.20x faster                                        |
| deepcopy                 | 454 us                                                       | 385 us: 1.18x faster                                          |
| bench_thread_pool        | 1.14 ms                                                      | 967 us: 1.18x faster                                          |
| docutils                 | 3.40 sec                                                     | 2.90 sec: 1.18x faster                                        |
| json                     | 5.96 ms                                                      | 5.08 ms: 1.17x faster                                         |
| deepcopy_reduce          | 4.03 us                                                      | 3.47 us: 1.16x faster                                         |
| pathlib                  | 21.7 ms                                                      | 19.2 ms: 1.13x faster                                         |
| create_gc_cycles         | 1.82 ms                                                      | 1.62 ms: 1.13x faster                                         |
| async_generators         | 422 ms                                                       | 382 ms: 1.11x faster                                          |
| sqlite_synth             | 2.97 us                                                      | 2.70 us: 1.10x faster                                         |
| meteor_contest           | 137 ms                                                       | 126 ms: 1.08x faster                                          |
| regex_v8                 | 26.6 ms                                                      | 24.6 ms: 1.08x faster                                         |
| xml_etree_generate       | 94.6 ms                                                      | 87.4 ms: 1.08x faster                                         |
| xml_etree_parse          | 162 ms                                                       | 151 ms: 1.07x faster                                          |
| regex_dna                | 259 ms                                                       | 245 ms: 1.06x faster                                          |
| xml_etree_iterparse      | 110 ms                                                       | 105 ms: 1.05x faster                                          |
| pidigits                 | 271 ms                                                       | 264 ms: 1.02x faster                                          |
| telco                    | 7.14 ms                                                      | 7.05 ms: 1.01x faster                                         |
| pickle                   | 9.94 us                                                      | 9.83 us: 1.01x faster                                         |
| python_startup           | 11.5 ms                                                      | 11.7 ms: 1.02x slower                                         |
| pickle_list              | 4.11 us                                                      | 4.21 us: 1.03x slower                                         |
| unpickle                 | 14.2 us                                                      | 14.6 us: 1.03x slower                                         |
| pickle_dict              | 30.0 us                                                      | 31.5 us: 1.05x slower                                         |
| unpickle_list            | 4.49 us                                                      | 4.79 us: 1.07x slower                                         |
| gc_traversal             | 3.45 ms                                                      | 3.78 ms: 1.09x slower                                         |
| regex_effbot             | 2.99 ms                                                      | 3.45 ms: 1.15x slower                                         |
| python_startup_no_site   | 7.32 ms                                                      | 8.66 ms: 1.18x slower                                         |
| dask                     | 463 ms                                                       | 565 ms: 1.22x slower                                          |
| coverage                 | 64.0 ms                                                      | 88.3 ms: 1.38x slower                                         |
| Geometric mean           | (ref)                                                        | 1.30x faster                                                  |
Ignored benchmarks (16) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.27x
- 95% likely to have a speedup of 1.26x
- 99% likely to have a speedup of 1.22x
