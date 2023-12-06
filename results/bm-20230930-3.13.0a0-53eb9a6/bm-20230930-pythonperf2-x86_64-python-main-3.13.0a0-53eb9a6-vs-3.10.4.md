
# Results vs. 3.10.4

- fork: python
- ref: main
- machine: linux-x86_64
- commit hash: 53eb9a6
- commit date: 2023-09-30
- overall geometric mean: 1.27x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.22x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230930-pythonperf2-x86_64-python-main-3.13.0a0-53eb9a6 |
|----------------|:------------------------------------------------------------:|:-----------------------------------------------------------:|
| docutils       | 3.40 sec                                                     | 2.85 sec: 1.19x faster                                      |
| tornado_http   | 152 ms                                                       | 119 ms: 1.28x faster                                        |
| Geometric mean | (ref)                                                        | 1.23x faster                                                |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230930-pythonperf2-x86_64-python-main-3.13.0a0-53eb9a6 |
|----------------|:------------------------------------------------------------:|:-----------------------------------------------------------:|
| nbody          | 137 ms                                                       | 88.7 ms: 1.55x faster                                       |
| float          | 110 ms                                                       | 82.3 ms: 1.34x faster                                       |
| pidigits       | 271 ms                                                       | 264 ms: 1.02x faster                                        |
| Geometric mean | (ref)                                                        | 1.28x faster                                                |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230930-pythonperf2-x86_64-python-main-3.13.0a0-53eb9a6 |
|----------------|:------------------------------------------------------------:|:-----------------------------------------------------------:|
| regex_compile  | 194 ms                                                       | 149 ms: 1.30x faster                                        |
| regex_v8       | 26.6 ms                                                      | 25.0 ms: 1.07x faster                                       |
| regex_dna      | 259 ms                                                       | 247 ms: 1.05x faster                                        |
| regex_effbot   | 2.99 ms                                                      | 3.45 ms: 1.15x slower                                       |
| Geometric mean | (ref)                                                        | 1.06x faster                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230930-pythonperf2-x86_64-python-main-3.13.0a0-53eb9a6 |
|----------------------|:------------------------------------------------------------:|:-----------------------------------------------------------:|
| unpickle_pure_python | 321 us                                                       | 218 us: 1.47x faster                                        |
| pickle_pure_python   | 457 us                                                       | 321 us: 1.43x faster                                        |
| json_dumps           | 14.2 ms                                                      | 10.6 ms: 1.35x faster                                       |
| xml_etree_process    | 76.0 ms                                                      | 58.8 ms: 1.29x faster                                       |
| tomli_loads          | 2.97 sec                                                     | 2.31 sec: 1.29x faster                                      |
| json_loads           | 30.0 us                                                      | 24.9 us: 1.20x faster                                       |
| xml_etree_generate   | 94.6 ms                                                      | 85.8 ms: 1.10x faster                                       |
| xml_etree_parse      | 162 ms                                                       | 149 ms: 1.08x faster                                        |
| xml_etree_iterparse  | 110 ms                                                       | 105 ms: 1.05x faster                                        |
| unpickle             | 14.2 us                                                      | 14.2 us: 1.00x slower                                       |
| pickle               | 9.94 us                                                      | 10.0 us: 1.01x slower                                       |
| unpickle_list        | 4.49 us                                                      | 4.70 us: 1.05x slower                                       |
| pickle_list          | 4.11 us                                                      | 4.30 us: 1.05x slower                                       |
| pickle_dict          | 30.0 us                                                      | 32.6 us: 1.09x slower                                       |
| Geometric mean       | (ref)                                                        | 1.13x faster                                                |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230930-pythonperf2-x86_64-python-main-3.13.0a0-53eb9a6 |
|------------------------|:------------------------------------------------------------:|:-----------------------------------------------------------:|
| python_startup         | 11.5 ms                                                      | 12.6 ms: 1.10x slower                                       |
| python_startup_no_site | 7.32 ms                                                      | 8.67 ms: 1.18x slower                                       |
| Geometric mean         | (ref)                                                        | 1.14x slower                                                |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230930-pythonperf2-x86_64-python-main-3.13.0a0-53eb9a6 |
|-----------|:------------------------------------------------------------:|:-----------------------------------------------------------:|
| mako      | 14.7 ms                                                      | 10.3 ms: 1.43x faster                                       |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230930-pythonperf2-x86_64-python-main-3.13.0a0-53eb9a6 |
|--------------------------|:------------------------------------------------------------:|:-----------------------------------------------------------:|
| typing_runtime_protocols | 523 us                                                       | 152 us: 3.44x faster                                        |
| asyncio_tcp              | 782 ms                                                       | 369 ms: 2.12x faster                                        |
| deltablue                | 7.47 ms                                                      | 3.65 ms: 2.04x faster                                       |
| asyncio_tcp_ssl          | 3.09 sec                                                     | 1.58 sec: 1.96x faster                                      |
| raytrace                 | 488 ms                                                       | 279 ms: 1.75x faster                                        |
| logging_silent           | 166 ns                                                       | 95.9 ns: 1.73x faster                                       |
| chaos                    | 107 ms                                                       | 63.8 ms: 1.68x faster                                       |
| crypto_pyaes             | 118 ms                                                       | 71.4 ms: 1.65x faster                                       |
| scimark_lu               | 164 ms                                                       | 99.3 ms: 1.65x faster                                       |
| scimark_monte_carlo      | 109 ms                                                       | 66.6 ms: 1.64x faster                                       |
| generators               | 58.0 ms                                                      | 35.3 ms: 1.64x faster                                       |
| sqlglot_parse            | 2.26 ms                                                      | 1.41 ms: 1.60x faster                                       |
| async_tree_none          | 700 ms                                                       | 438 ms: 1.60x faster                                        |
| nbody                    | 137 ms                                                       | 88.7 ms: 1.55x faster                                       |
| go                       | 259 ms                                                       | 167 ms: 1.55x faster                                        |
| bench_mp_pool            | 7.18 ms                                                      | 4.75 ms: 1.51x faster                                       |
| sqlglot_transpile        | 2.71 ms                                                      | 1.82 ms: 1.49x faster                                       |
| richards_super           | 90.8 ms                                                      | 60.9 ms: 1.49x faster                                       |
| async_tree_memoization   | 824 ms                                                       | 555 ms: 1.49x faster                                        |
| spectral_norm            | 136 ms                                                       | 92.4 ms: 1.48x faster                                       |
| unpickle_pure_python     | 321 us                                                       | 218 us: 1.47x faster                                        |
| async_tree_io            | 1.61 sec                                                     | 1.09 sec: 1.47x faster                                      |
| hexiom                   | 9.52 ms                                                      | 6.49 ms: 1.47x faster                                       |
| mako                     | 14.7 ms                                                      | 10.3 ms: 1.43x faster                                       |
| pickle_pure_python       | 457 us                                                       | 321 us: 1.43x faster                                        |
| richards                 | 74.1 ms                                                      | 54.3 ms: 1.36x faster                                       |
| pyflate                  | 697 ms                                                       | 511 ms: 1.36x faster                                        |
| async_tree_cpu_io_mixed  | 952 ms                                                       | 705 ms: 1.35x faster                                        |
| json_dumps               | 14.2 ms                                                      | 10.6 ms: 1.35x faster                                       |
| float                    | 110 ms                                                       | 82.3 ms: 1.34x faster                                       |
| coroutines               | 30.4 ms                                                      | 23.3 ms: 1.31x faster                                       |
| pprint_safe_repr         | 1.05 sec                                                     | 810 ms: 1.30x faster                                        |
| regex_compile            | 194 ms                                                       | 149 ms: 1.30x faster                                        |
| pprint_pformat           | 2.15 sec                                                     | 1.66 sec: 1.30x faster                                      |
| xml_etree_process        | 76.0 ms                                                      | 58.8 ms: 1.29x faster                                       |
| tomli_loads              | 2.97 sec                                                     | 2.31 sec: 1.29x faster                                      |
| deepcopy_memo            | 48.9 us                                                      | 38.0 us: 1.29x faster                                       |
| tornado_http             | 152 ms                                                       | 119 ms: 1.28x faster                                        |
| logging_simple           | 8.90 us                                                      | 6.97 us: 1.28x faster                                       |
| nqueens                  | 112 ms                                                       | 89.4 ms: 1.26x faster                                       |
| fannkuch                 | 496 ms                                                       | 396 ms: 1.25x faster                                        |
| sqlglot_normalize        | 144 ms                                                       | 115 ms: 1.25x faster                                        |
| pycparser                | 1.66 sec                                                     | 1.33 sec: 1.25x faster                                      |
| logging_format           | 9.57 us                                                      | 7.75 us: 1.23x faster                                       |
| scimark_sparse_mat_mult  | 5.19 ms                                                      | 4.23 ms: 1.23x faster                                       |
| comprehensions           | 26.9 us                                                      | 22.0 us: 1.22x faster                                       |
| mdp                      | 3.03 sec                                                     | 2.51 sec: 1.21x faster                                      |
| sqlglot_optimize         | 70.3 ms                                                      | 58.2 ms: 1.21x faster                                       |
| json_loads               | 30.0 us                                                      | 24.9 us: 1.20x faster                                       |
| scimark_fft              | 359 ms                                                       | 299 ms: 1.20x faster                                        |
| bench_thread_pool        | 1.14 ms                                                      | 951 us: 1.20x faster                                        |
| docutils                 | 3.40 sec                                                     | 2.85 sec: 1.19x faster                                      |
| scimark_sor              | 177 ms                                                       | 150 ms: 1.18x faster                                        |
| deepcopy_reduce          | 4.03 us                                                      | 3.42 us: 1.18x faster                                       |
| dulwich_log              | 80.1 ms                                                      | 68.9 ms: 1.16x faster                                       |
| json                     | 5.96 ms                                                      | 5.14 ms: 1.16x faster                                       |
| deepcopy                 | 454 us                                                       | 392 us: 1.16x faster                                        |
| unpack_sequence          | 59.5 ns                                                      | 53.1 ns: 1.12x faster                                       |
| sqlite_synth             | 2.97 us                                                      | 2.66 us: 1.11x faster                                       |
| xml_etree_generate       | 94.6 ms                                                      | 85.8 ms: 1.10x faster                                       |
| async_generators         | 422 ms                                                       | 388 ms: 1.09x faster                                        |
| pathlib                  | 21.7 ms                                                      | 20.0 ms: 1.09x faster                                       |
| xml_etree_parse          | 162 ms                                                       | 149 ms: 1.08x faster                                        |
| regex_v8                 | 26.6 ms                                                      | 25.0 ms: 1.07x faster                                       |
| create_gc_cycles         | 1.82 ms                                                      | 1.71 ms: 1.06x faster                                       |
| meteor_contest           | 137 ms                                                       | 130 ms: 1.05x faster                                        |
| regex_dna                | 259 ms                                                       | 247 ms: 1.05x faster                                        |
| xml_etree_iterparse      | 110 ms                                                       | 105 ms: 1.05x faster                                        |
| pidigits                 | 271 ms                                                       | 264 ms: 1.02x faster                                        |
| unpickle                 | 14.2 us                                                      | 14.2 us: 1.00x slower                                       |
| pickle                   | 9.94 us                                                      | 10.0 us: 1.01x slower                                       |
| unpickle_list            | 4.49 us                                                      | 4.70 us: 1.05x slower                                       |
| pickle_list              | 4.11 us                                                      | 4.30 us: 1.05x slower                                       |
| pickle_dict              | 30.0 us                                                      | 32.6 us: 1.09x slower                                       |
| python_startup           | 11.5 ms                                                      | 12.6 ms: 1.10x slower                                       |
| telco                    | 7.14 ms                                                      | 8.03 ms: 1.12x slower                                       |
| regex_effbot             | 2.99 ms                                                      | 3.45 ms: 1.15x slower                                       |
| python_startup_no_site   | 7.32 ms                                                      | 8.67 ms: 1.18x slower                                       |
| gc_traversal             | 3.45 ms                                                      | 4.19 ms: 1.21x slower                                       |
| coverage                 | 64.0 ms                                                      | 82.8 ms: 1.29x slower                                       |
| Geometric mean           | (ref)                                                        | 1.27x faster                                                |

Benchmark hidden because not significant (1): mypy2
Ignored benchmarks (18) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120.json: 2to3, aiohttp, chameleon, dask, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.25x
- 95% likely to have a speedup of 1.24x
- 99% likely to have a speedup of 1.22x
