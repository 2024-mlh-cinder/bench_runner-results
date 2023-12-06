
# Results vs. 3.10.4

- fork: python
- ref: main
- machine: linux-x86_64
- commit hash: 6c23635
- commit date: 2023-10-21
- overall geometric mean: 1.28x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.21x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231021-pythonperf2-x86_64-python-main-3.13.0a1+-6c23635 |
|----------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| docutils       | 3.40 sec                                                     | 2.90 sec: 1.17x faster                                       |
| tornado_http   | 152 ms                                                       | 122 ms: 1.25x faster                                         |
| Geometric mean | (ref)                                                        | 1.21x faster                                                 |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231021-pythonperf2-x86_64-python-main-3.13.0a1+-6c23635 |
|----------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| nbody          | 137 ms                                                       | 86.2 ms: 1.59x faster                                        |
| float          | 110 ms                                                       | 78.0 ms: 1.41x faster                                        |
| pidigits       | 271 ms                                                       | 265 ms: 1.02x faster                                         |
| Geometric mean | (ref)                                                        | 1.32x faster                                                 |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231021-pythonperf2-x86_64-python-main-3.13.0a1+-6c23635 |
|----------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| regex_compile  | 194 ms                                                       | 148 ms: 1.31x faster                                         |
| regex_dna      | 259 ms                                                       | 238 ms: 1.09x faster                                         |
| regex_v8       | 26.6 ms                                                      | 24.5 ms: 1.09x faster                                        |
| regex_effbot   | 2.99 ms                                                      | 3.53 ms: 1.18x slower                                        |
| Geometric mean | (ref)                                                        | 1.07x faster                                                 |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231021-pythonperf2-x86_64-python-main-3.13.0a1+-6c23635 |
|----------------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| pickle_pure_python   | 457 us                                                       | 313 us: 1.46x faster                                         |
| unpickle_pure_python | 321 us                                                       | 225 us: 1.43x faster                                         |
| json_dumps           | 14.2 ms                                                      | 10.5 ms: 1.35x faster                                        |
| xml_etree_process    | 76.0 ms                                                      | 59.1 ms: 1.29x faster                                        |
| tomli_loads          | 2.97 sec                                                     | 2.32 sec: 1.28x faster                                       |
| json_loads           | 30.0 us                                                      | 24.3 us: 1.23x faster                                        |
| xml_etree_generate   | 94.6 ms                                                      | 85.9 ms: 1.10x faster                                        |
| xml_etree_parse      | 162 ms                                                       | 150 ms: 1.08x faster                                         |
| xml_etree_iterparse  | 110 ms                                                       | 107 ms: 1.03x faster                                         |
| unpickle_list        | 4.49 us                                                      | 4.47 us: 1.00x faster                                        |
| pickle               | 9.94 us                                                      | 10.1 us: 1.01x slower                                        |
| pickle_list          | 4.11 us                                                      | 4.37 us: 1.06x slower                                        |
| pickle_dict          | 30.0 us                                                      | 32.3 us: 1.08x slower                                        |
| Geometric mean       | (ref)                                                        | 1.14x faster                                                 |

Benchmark hidden because not significant (1): unpickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231021-pythonperf2-x86_64-python-main-3.13.0a1+-6c23635 |
|------------------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| python_startup         | 11.5 ms                                                      | 12.6 ms: 1.10x slower                                        |
| python_startup_no_site | 7.32 ms                                                      | 8.69 ms: 1.19x slower                                        |
| Geometric mean         | (ref)                                                        | 1.14x slower                                                 |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231021-pythonperf2-x86_64-python-main-3.13.0a1+-6c23635 |
|-----------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| mako      | 14.7 ms                                                      | 10.4 ms: 1.42x faster                                        |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231021-pythonperf2-x86_64-python-main-3.13.0a1+-6c23635 |
|--------------------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| typing_runtime_protocols | 523 us                                                       | 156 us: 3.36x faster                                         |
| asyncio_tcp              | 782 ms                                                       | 371 ms: 2.11x faster                                         |
| deltablue                | 7.47 ms                                                      | 3.66 ms: 2.04x faster                                        |
| asyncio_tcp_ssl          | 3.09 sec                                                     | 1.58 sec: 1.96x faster                                       |
| raytrace                 | 488 ms                                                       | 280 ms: 1.74x faster                                         |
| chaos                    | 107 ms                                                       | 63.3 ms: 1.69x faster                                        |
| logging_silent           | 166 ns                                                       | 98.3 ns: 1.69x faster                                        |
| crypto_pyaes             | 118 ms                                                       | 71.7 ms: 1.65x faster                                        |
| scimark_lu               | 164 ms                                                       | 99.7 ms: 1.64x faster                                        |
| generators               | 58.0 ms                                                      | 35.8 ms: 1.62x faster                                        |
| async_tree_none          | 700 ms                                                       | 434 ms: 1.61x faster                                         |
| sqlglot_parse            | 2.26 ms                                                      | 1.42 ms: 1.59x faster                                        |
| nbody                    | 137 ms                                                       | 86.2 ms: 1.59x faster                                        |
| scimark_monte_carlo      | 109 ms                                                       | 70.6 ms: 1.55x faster                                        |
| bench_mp_pool            | 7.18 ms                                                      | 4.64 ms: 1.55x faster                                        |
| async_tree_memoization   | 824 ms                                                       | 548 ms: 1.50x faster                                         |
| go                       | 259 ms                                                       | 173 ms: 1.49x faster                                         |
| async_tree_io            | 1.61 sec                                                     | 1.08 sec: 1.49x faster                                       |
| spectral_norm            | 136 ms                                                       | 91.7 ms: 1.49x faster                                        |
| richards_super           | 90.8 ms                                                      | 61.3 ms: 1.48x faster                                        |
| sqlglot_transpile        | 2.71 ms                                                      | 1.83 ms: 1.48x faster                                        |
| hexiom                   | 9.52 ms                                                      | 6.46 ms: 1.47x faster                                        |
| pickle_pure_python       | 457 us                                                       | 313 us: 1.46x faster                                         |
| unpickle_pure_python     | 321 us                                                       | 225 us: 1.43x faster                                         |
| mako                     | 14.7 ms                                                      | 10.4 ms: 1.42x faster                                        |
| float                    | 110 ms                                                       | 78.0 ms: 1.41x faster                                        |
| async_tree_cpu_io_mixed  | 952 ms                                                       | 700 ms: 1.36x faster                                         |
| json_dumps               | 14.2 ms                                                      | 10.5 ms: 1.35x faster                                        |
| coroutines               | 30.4 ms                                                      | 22.7 ms: 1.34x faster                                        |
| richards                 | 74.1 ms                                                      | 55.7 ms: 1.33x faster                                        |
| pyflate                  | 697 ms                                                       | 528 ms: 1.32x faster                                         |
| regex_compile            | 194 ms                                                       | 148 ms: 1.31x faster                                         |
| logging_simple           | 8.90 us                                                      | 6.81 us: 1.31x faster                                        |
| logging_format           | 9.57 us                                                      | 7.42 us: 1.29x faster                                        |
| xml_etree_process        | 76.0 ms                                                      | 59.1 ms: 1.29x faster                                        |
| tomli_loads              | 2.97 sec                                                     | 2.32 sec: 1.28x faster                                       |
| deepcopy_memo            | 48.9 us                                                      | 38.3 us: 1.28x faster                                        |
| nqueens                  | 112 ms                                                       | 88.3 ms: 1.27x faster                                        |
| fannkuch                 | 496 ms                                                       | 392 ms: 1.27x faster                                         |
| pycparser                | 1.66 sec                                                     | 1.33 sec: 1.25x faster                                       |
| mypy2                    | 466 ms                                                       | 373 ms: 1.25x faster                                         |
| pprint_pformat           | 2.15 sec                                                     | 1.73 sec: 1.25x faster                                       |
| tornado_http             | 152 ms                                                       | 122 ms: 1.25x faster                                         |
| comprehensions           | 26.9 us                                                      | 21.7 us: 1.24x faster                                        |
| pprint_safe_repr         | 1.05 sec                                                     | 845 ms: 1.24x faster                                         |
| json_loads               | 30.0 us                                                      | 24.3 us: 1.23x faster                                        |
| sqlglot_normalize        | 144 ms                                                       | 117 ms: 1.23x faster                                         |
| scimark_sparse_mat_mult  | 5.19 ms                                                      | 4.28 ms: 1.21x faster                                        |
| deepcopy                 | 454 us                                                       | 377 us: 1.20x faster                                         |
| mdp                      | 3.03 sec                                                     | 2.52 sec: 1.20x faster                                       |
| deepcopy_reduce          | 4.03 us                                                      | 3.36 us: 1.20x faster                                        |
| scimark_sor              | 177 ms                                                       | 149 ms: 1.19x faster                                         |
| sqlglot_optimize         | 70.3 ms                                                      | 59.2 ms: 1.19x faster                                        |
| create_gc_cycles         | 1.82 ms                                                      | 1.54 ms: 1.18x faster                                        |
| bench_thread_pool        | 1.14 ms                                                      | 964 us: 1.18x faster                                         |
| json                     | 5.96 ms                                                      | 5.08 ms: 1.17x faster                                        |
| docutils                 | 3.40 sec                                                     | 2.90 sec: 1.17x faster                                       |
| dulwich_log              | 80.1 ms                                                      | 69.4 ms: 1.15x faster                                        |
| scimark_fft              | 359 ms                                                       | 316 ms: 1.14x faster                                         |
| sqlite_synth             | 2.97 us                                                      | 2.67 us: 1.11x faster                                        |
| pathlib                  | 21.7 ms                                                      | 19.7 ms: 1.10x faster                                        |
| xml_etree_generate       | 94.6 ms                                                      | 85.9 ms: 1.10x faster                                        |
| regex_dna                | 259 ms                                                       | 238 ms: 1.09x faster                                         |
| regex_v8                 | 26.6 ms                                                      | 24.5 ms: 1.09x faster                                        |
| unpack_sequence          | 59.5 ns                                                      | 54.9 ns: 1.08x faster                                        |
| xml_etree_parse          | 162 ms                                                       | 150 ms: 1.08x faster                                         |
| async_generators         | 422 ms                                                       | 397 ms: 1.06x faster                                         |
| meteor_contest           | 137 ms                                                       | 130 ms: 1.05x faster                                         |
| xml_etree_iterparse      | 110 ms                                                       | 107 ms: 1.03x faster                                         |
| pidigits                 | 271 ms                                                       | 265 ms: 1.02x faster                                         |
| unpickle_list            | 4.49 us                                                      | 4.47 us: 1.00x faster                                        |
| pickle                   | 9.94 us                                                      | 10.1 us: 1.01x slower                                        |
| pickle_list              | 4.11 us                                                      | 4.37 us: 1.06x slower                                        |
| pickle_dict              | 30.0 us                                                      | 32.3 us: 1.08x slower                                        |
| gc_traversal             | 3.45 ms                                                      | 3.72 ms: 1.08x slower                                        |
| python_startup           | 11.5 ms                                                      | 12.6 ms: 1.10x slower                                        |
| telco                    | 7.14 ms                                                      | 8.20 ms: 1.15x slower                                        |
| regex_effbot             | 2.99 ms                                                      | 3.53 ms: 1.18x slower                                        |
| python_startup_no_site   | 7.32 ms                                                      | 8.69 ms: 1.19x slower                                        |
| coverage                 | 64.0 ms                                                      | 80.2 ms: 1.25x slower                                        |
| Geometric mean           | (ref)                                                        | 1.28x faster                                                 |

Benchmark hidden because not significant (1): unpickle
Ignored benchmarks (18) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120.json: 2to3, aiohttp, chameleon, dask, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.24x
- 95% likely to have a speedup of 1.24x
- 99% likely to have a speedup of 1.21x
