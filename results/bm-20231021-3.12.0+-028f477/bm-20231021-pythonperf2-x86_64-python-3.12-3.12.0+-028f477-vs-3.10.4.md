
# Results vs. 3.10.4

- fork: python
- ref: 3.12
- machine: linux-x86_64
- commit hash: 028f477
- commit date: 2023-10-21
- overall geometric mean: 1.29x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.22x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231021-pythonperf2-x86_64-python-3.12-3.12.0+-028f477 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------:|
| 2to3           | 350 ms                                                       | 287 ms: 1.22x faster                                       |
| docutils       | 3.40 sec                                                     | 2.87 sec: 1.18x faster                                     |
| tornado_http   | 152 ms                                                       | 120 ms: 1.27x faster                                       |
| Geometric mean | (ref)                                                        | 1.22x faster                                               |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231021-pythonperf2-x86_64-python-3.12-3.12.0+-028f477 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------:|
| nbody          | 137 ms                                                       | 83.4 ms: 1.65x faster                                      |
| float          | 110 ms                                                       | 79.1 ms: 1.39x faster                                      |
| pidigits       | 271 ms                                                       | 264 ms: 1.03x faster                                       |
| Geometric mean | (ref)                                                        | 1.33x faster                                               |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231021-pythonperf2-x86_64-python-3.12-3.12.0+-028f477 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------:|
| regex_compile  | 194 ms                                                       | 143 ms: 1.36x faster                                       |
| regex_v8       | 26.6 ms                                                      | 24.1 ms: 1.11x faster                                      |
| regex_dna      | 259 ms                                                       | 244 ms: 1.06x faster                                       |
| regex_effbot   | 2.99 ms                                                      | 3.53 ms: 1.18x slower                                      |
| Geometric mean | (ref)                                                        | 1.08x faster                                               |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231021-pythonperf2-x86_64-python-3.12-3.12.0+-028f477 |
|----------------------|:------------------------------------------------------------:|:----------------------------------------------------------:|
| unpickle_pure_python | 321 us                                                       | 206 us: 1.56x faster                                       |
| pickle_pure_python   | 457 us                                                       | 325 us: 1.41x faster                                       |
| json_dumps           | 14.2 ms                                                      | 10.4 ms: 1.37x faster                                      |
| tomli_loads          | 2.97 sec                                                     | 2.20 sec: 1.35x faster                                     |
| xml_etree_process    | 76.0 ms                                                      | 58.2 ms: 1.31x faster                                      |
| json_loads           | 30.0 us                                                      | 24.3 us: 1.24x faster                                      |
| xml_etree_generate   | 94.6 ms                                                      | 85.5 ms: 1.11x faster                                      |
| xml_etree_parse      | 162 ms                                                       | 147 ms: 1.10x faster                                       |
| xml_etree_iterparse  | 110 ms                                                       | 103 ms: 1.07x faster                                       |
| unpickle             | 14.2 us                                                      | 14.5 us: 1.03x slower                                      |
| pickle               | 9.94 us                                                      | 10.2 us: 1.03x slower                                      |
| unpickle_list        | 4.49 us                                                      | 4.82 us: 1.07x slower                                      |
| pickle_list          | 4.11 us                                                      | 4.43 us: 1.08x slower                                      |
| pickle_dict          | 30.0 us                                                      | 32.6 us: 1.09x slower                                      |
| Geometric mean       | (ref)                                                        | 1.14x faster                                               |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231021-pythonperf2-x86_64-python-3.12-3.12.0+-028f477 |
|------------------------|:------------------------------------------------------------:|:----------------------------------------------------------:|
| python_startup         | 11.5 ms                                                      | 11.7 ms: 1.02x slower                                      |
| python_startup_no_site | 7.32 ms                                                      | 8.68 ms: 1.18x slower                                      |
| Geometric mean         | (ref)                                                        | 1.10x slower                                               |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231021-pythonperf2-x86_64-python-3.12-3.12.0+-028f477 |
|-----------|:------------------------------------------------------------:|:----------------------------------------------------------:|
| mako      | 14.7 ms                                                      | 10.1 ms: 1.45x faster                                      |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231021-pythonperf2-x86_64-python-3.12-3.12.0+-028f477 |
|--------------------------|:------------------------------------------------------------:|:----------------------------------------------------------:|
| typing_runtime_protocols | 523 us                                                       | 153 us: 3.42x faster                                       |
| deltablue                | 7.47 ms                                                      | 3.26 ms: 2.29x faster                                      |
| asyncio_tcp              | 782 ms                                                       | 379 ms: 2.07x faster                                       |
| asyncio_tcp_ssl          | 3.09 sec                                                     | 1.57 sec: 1.97x faster                                     |
| richards_super           | 90.8 ms                                                      | 51.2 ms: 1.77x faster                                      |
| logging_silent           | 166 ns                                                       | 93.6 ns: 1.77x faster                                      |
| go                       | 259 ms                                                       | 147 ms: 1.76x faster                                       |
| chaos                    | 107 ms                                                       | 64.2 ms: 1.67x faster                                      |
| nbody                    | 137 ms                                                       | 83.4 ms: 1.65x faster                                      |
| richards                 | 74.1 ms                                                      | 45.1 ms: 1.64x faster                                      |
| scimark_lu               | 164 ms                                                       | 101 ms: 1.62x faster                                       |
| sqlglot_parse            | 2.26 ms                                                      | 1.39 ms: 1.62x faster                                      |
| raytrace                 | 488 ms                                                       | 301 ms: 1.62x faster                                       |
| scimark_sor              | 177 ms                                                       | 110 ms: 1.61x faster                                       |
| hexiom                   | 9.52 ms                                                      | 5.96 ms: 1.60x faster                                      |
| pyflate                  | 697 ms                                                       | 436 ms: 1.60x faster                                       |
| generators               | 58.0 ms                                                      | 36.8 ms: 1.57x faster                                      |
| scimark_monte_carlo      | 109 ms                                                       | 69.6 ms: 1.57x faster                                      |
| unpickle_pure_python     | 321 us                                                       | 206 us: 1.56x faster                                       |
| async_tree_none          | 700 ms                                                       | 463 ms: 1.51x faster                                       |
| async_tree_io            | 1.61 sec                                                     | 1.06 sec: 1.51x faster                                     |
| sqlglot_transpile        | 2.71 ms                                                      | 1.80 ms: 1.51x faster                                      |
| spectral_norm            | 136 ms                                                       | 91.9 ms: 1.48x faster                                      |
| crypto_pyaes             | 118 ms                                                       | 79.8 ms: 1.48x faster                                      |
| async_tree_memoization   | 824 ms                                                       | 557 ms: 1.48x faster                                       |
| mako                     | 14.7 ms                                                      | 10.1 ms: 1.45x faster                                      |
| fannkuch                 | 496 ms                                                       | 344 ms: 1.44x faster                                       |
| pickle_pure_python       | 457 us                                                       | 325 us: 1.41x faster                                       |
| float                    | 110 ms                                                       | 79.1 ms: 1.39x faster                                      |
| json_dumps               | 14.2 ms                                                      | 10.4 ms: 1.37x faster                                      |
| regex_compile            | 194 ms                                                       | 143 ms: 1.36x faster                                       |
| tomli_loads              | 2.97 sec                                                     | 2.20 sec: 1.35x faster                                     |
| async_tree_cpu_io_mixed  | 952 ms                                                       | 705 ms: 1.35x faster                                       |
| coroutines               | 30.4 ms                                                      | 22.7 ms: 1.34x faster                                      |
| pycparser                | 1.66 sec                                                     | 1.25 sec: 1.34x faster                                     |
| deepcopy_memo            | 48.9 us                                                      | 37.2 us: 1.31x faster                                      |
| xml_etree_process        | 76.0 ms                                                      | 58.2 ms: 1.31x faster                                      |
| pprint_pformat           | 2.15 sec                                                     | 1.66 sec: 1.30x faster                                     |
| pprint_safe_repr         | 1.05 sec                                                     | 817 ms: 1.28x faster                                       |
| tornado_http             | 152 ms                                                       | 120 ms: 1.27x faster                                       |
| logging_simple           | 8.90 us                                                      | 7.00 us: 1.27x faster                                      |
| nqueens                  | 112 ms                                                       | 89.1 ms: 1.26x faster                                      |
| logging_format           | 9.57 us                                                      | 7.65 us: 1.25x faster                                      |
| json_loads               | 30.0 us                                                      | 24.3 us: 1.24x faster                                      |
| comprehensions           | 26.9 us                                                      | 21.9 us: 1.23x faster                                      |
| bench_mp_pool            | 7.18 ms                                                      | 5.87 ms: 1.22x faster                                      |
| dulwich_log              | 80.1 ms                                                      | 65.7 ms: 1.22x faster                                      |
| 2to3                     | 350 ms                                                       | 287 ms: 1.22x faster                                       |
| sqlglot_normalize        | 144 ms                                                       | 119 ms: 1.21x faster                                       |
| mdp                      | 3.03 sec                                                     | 2.54 sec: 1.19x faster                                     |
| deepcopy                 | 454 us                                                       | 381 us: 1.19x faster                                       |
| scimark_sparse_mat_mult  | 5.19 ms                                                      | 4.36 ms: 1.19x faster                                      |
| sqlglot_optimize         | 70.3 ms                                                      | 59.2 ms: 1.19x faster                                      |
| docutils                 | 3.40 sec                                                     | 2.87 sec: 1.18x faster                                     |
| bench_thread_pool        | 1.14 ms                                                      | 962 us: 1.18x faster                                       |
| scimark_fft              | 359 ms                                                       | 306 ms: 1.17x faster                                       |
| deepcopy_reduce          | 4.03 us                                                      | 3.44 us: 1.17x faster                                      |
| dask                     | 463 ms                                                       | 396 ms: 1.17x faster                                       |
| json                     | 5.96 ms                                                      | 5.16 ms: 1.16x faster                                      |
| create_gc_cycles         | 1.82 ms                                                      | 1.58 ms: 1.15x faster                                      |
| pathlib                  | 21.7 ms                                                      | 19.2 ms: 1.13x faster                                      |
| unpack_sequence          | 59.5 ns                                                      | 53.7 ns: 1.11x faster                                      |
| regex_v8                 | 26.6 ms                                                      | 24.1 ms: 1.11x faster                                      |
| xml_etree_generate       | 94.6 ms                                                      | 85.5 ms: 1.11x faster                                      |
| async_generators         | 422 ms                                                       | 385 ms: 1.10x faster                                       |
| xml_etree_parse          | 162 ms                                                       | 147 ms: 1.10x faster                                       |
| sqlite_synth             | 2.97 us                                                      | 2.72 us: 1.09x faster                                      |
| xml_etree_iterparse      | 110 ms                                                       | 103 ms: 1.07x faster                                       |
| regex_dna                | 259 ms                                                       | 244 ms: 1.06x faster                                       |
| meteor_contest           | 137 ms                                                       | 130 ms: 1.05x faster                                       |
| pidigits                 | 271 ms                                                       | 264 ms: 1.03x faster                                       |
| python_startup           | 11.5 ms                                                      | 11.7 ms: 1.02x slower                                      |
| unpickle                 | 14.2 us                                                      | 14.5 us: 1.03x slower                                      |
| pickle                   | 9.94 us                                                      | 10.2 us: 1.03x slower                                      |
| telco                    | 7.14 ms                                                      | 7.45 ms: 1.04x slower                                      |
| unpickle_list            | 4.49 us                                                      | 4.82 us: 1.07x slower                                      |
| pickle_list              | 4.11 us                                                      | 4.43 us: 1.08x slower                                      |
| pickle_dict              | 30.0 us                                                      | 32.6 us: 1.09x slower                                      |
| gc_traversal             | 3.45 ms                                                      | 3.94 ms: 1.14x slower                                      |
| regex_effbot             | 2.99 ms                                                      | 3.53 ms: 1.18x slower                                      |
| python_startup_no_site   | 7.32 ms                                                      | 8.68 ms: 1.18x slower                                      |
| coverage                 | 64.0 ms                                                      | 92.1 ms: 1.44x slower                                      |
| Geometric mean           | (ref)                                                        | 1.29x faster                                               |

Benchmark hidden because not significant (1): mypy2
Ignored benchmarks (16) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.27x
- 95% likely to have a speedup of 1.26x
- 99% likely to have a speedup of 1.22x
