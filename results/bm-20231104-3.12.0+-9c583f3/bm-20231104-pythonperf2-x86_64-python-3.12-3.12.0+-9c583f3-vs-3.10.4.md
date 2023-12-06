
# Results vs. 3.10.4

- fork: python
- ref: 3.12
- machine: linux-x86_64
- commit hash: 9c583f3
- commit date: 2023-11-04
- overall geometric mean: 1.30x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.22x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231104-pythonperf2-x86_64-python-3.12-3.12.0+-9c583f3 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------:|
| 2to3           | 349 ms                                                       | 286 ms: 1.22x faster                                       |
| chameleon      | 9.88 ms                                                      | 7.25 ms: 1.36x faster                                      |
| docutils       | 3.42 sec                                                     | 2.85 sec: 1.20x faster                                     |
| tornado_http   | 157 ms                                                       | 120 ms: 1.30x faster                                       |
| Geometric mean | (ref)                                                        | 1.27x faster                                               |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231104-pythonperf2-x86_64-python-3.12-3.12.0+-9c583f3 |
|-------------------------|:------------------------------------------------------------:|:----------------------------------------------------------:|
| async_tree_none         | 700 ms                                                       | 458 ms: 1.53x faster                                       |
| async_tree_io           | 1.61 sec                                                     | 1.06 sec: 1.52x faster                                     |
| async_tree_memoization  | 827 ms                                                       | 553 ms: 1.50x faster                                       |
| async_tree_cpu_io_mixed | 946 ms                                                       | 704 ms: 1.34x faster                                       |
| Geometric mean          | (ref)                                                        | 1.47x faster                                               |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231104-pythonperf2-x86_64-python-3.12-3.12.0+-9c583f3 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------:|
| nbody          | 134 ms                                                       | 83.2 ms: 1.61x faster                                      |
| float          | 109 ms                                                       | 77.7 ms: 1.40x faster                                      |
| pidigits       | 270 ms                                                       | 264 ms: 1.02x faster                                       |
| Geometric mean | (ref)                                                        | 1.32x faster                                               |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231104-pythonperf2-x86_64-python-3.12-3.12.0+-9c583f3 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------:|
| regex_compile  | 192 ms                                                       | 139 ms: 1.39x faster                                       |
| regex_v8       | 27.1 ms                                                      | 24.2 ms: 1.12x faster                                      |
| regex_dna      | 260 ms                                                       | 244 ms: 1.07x faster                                       |
| regex_effbot   | 3.10 ms                                                      | 3.50 ms: 1.13x slower                                      |
| Geometric mean | (ref)                                                        | 1.10x faster                                               |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231104-pythonperf2-x86_64-python-3.12-3.12.0+-9c583f3 |
|----------------------|:------------------------------------------------------------:|:----------------------------------------------------------:|
| unpickle_pure_python | 315 us                                                       | 210 us: 1.50x faster                                       |
| pickle_pure_python   | 453 us                                                       | 324 us: 1.40x faster                                       |
| json_dumps           | 14.2 ms                                                      | 10.2 ms: 1.40x faster                                      |
| tomli_loads          | 2.96 sec                                                     | 2.23 sec: 1.33x faster                                     |
| xml_etree_process    | 76.4 ms                                                      | 58.2 ms: 1.31x faster                                      |
| json_loads           | 30.0 us                                                      | 24.4 us: 1.23x faster                                      |
| xml_etree_generate   | 93.1 ms                                                      | 86.0 ms: 1.08x faster                                      |
| xml_etree_parse      | 159 ms                                                       | 148 ms: 1.08x faster                                       |
| xml_etree_iterparse  | 110 ms                                                       | 104 ms: 1.06x faster                                       |
| pickle               | 10.1 us                                                      | 10.2 us: 1.01x slower                                      |
| unpickle             | 13.9 us                                                      | 14.9 us: 1.07x slower                                      |
| unpickle_list        | 4.45 us                                                      | 4.75 us: 1.07x slower                                      |
| pickle_dict          | 30.4 us                                                      | 32.6 us: 1.07x slower                                      |
| pickle_list          | 4.23 us                                                      | 4.57 us: 1.08x slower                                      |
| Geometric mean       | (ref)                                                        | 1.13x faster                                               |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231104-pythonperf2-x86_64-python-3.12-3.12.0+-9c583f3 |
|------------------------|:------------------------------------------------------------:|:----------------------------------------------------------:|
| python_startup         | 11.5 ms                                                      | 11.7 ms: 1.01x slower                                      |
| python_startup_no_site | 7.35 ms                                                      | 8.63 ms: 1.17x slower                                      |
| Geometric mean         | (ref)                                                        | 1.09x slower                                               |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231104-pythonperf2-x86_64-python-3.12-3.12.0+-9c583f3 |
|-----------------|:------------------------------------------------------------:|:----------------------------------------------------------:|
| mako            | 14.7 ms                                                      | 9.98 ms: 1.48x faster                                      |
| django_template | 51.8 ms                                                      | 38.7 ms: 1.34x faster                                      |
| Geometric mean  | (ref)                                                        | 1.40x faster                                               |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231104-pythonperf2-x86_64-python-3.12-3.12.0+-9c583f3 |
|--------------------------|:------------------------------------------------------------:|:----------------------------------------------------------:|
| typing_runtime_protocols | 533 us                                                       | 122 us: 4.37x faster                                       |
| deltablue                | 7.43 ms                                                      | 3.29 ms: 2.26x faster                                      |
| asyncio_tcp              | 785 ms                                                       | 378 ms: 2.08x faster                                       |
| asyncio_tcp_ssl          | 3.13 sec                                                     | 1.58 sec: 1.99x faster                                     |
| logging_silent           | 168 ns                                                       | 91.8 ns: 1.83x faster                                      |
| richards_super           | 93.0 ms                                                      | 51.3 ms: 1.81x faster                                      |
| go                       | 258 ms                                                       | 149 ms: 1.73x faster                                       |
| richards                 | 76.3 ms                                                      | 44.7 ms: 1.71x faster                                      |
| chaos                    | 106 ms                                                       | 62.1 ms: 1.71x faster                                      |
| scimark_sor              | 183 ms                                                       | 109 ms: 1.68x faster                                       |
| raytrace                 | 497 ms                                                       | 297 ms: 1.68x faster                                       |
| scimark_lu               | 165 ms                                                       | 98.9 ms: 1.66x faster                                      |
| sqlglot_parse            | 2.27 ms                                                      | 1.38 ms: 1.64x faster                                      |
| nbody                    | 134 ms                                                       | 83.2 ms: 1.61x faster                                      |
| scimark_monte_carlo      | 109 ms                                                       | 68.9 ms: 1.59x faster                                      |
| hexiom                   | 9.46 ms                                                      | 5.97 ms: 1.58x faster                                      |
| pyflate                  | 698 ms                                                       | 442 ms: 1.58x faster                                       |
| generators               | 57.7 ms                                                      | 36.5 ms: 1.58x faster                                      |
| spectral_norm            | 141 ms                                                       | 91.3 ms: 1.55x faster                                      |
| sqlglot_transpile        | 2.73 ms                                                      | 1.79 ms: 1.53x faster                                      |
| async_tree_none          | 700 ms                                                       | 458 ms: 1.53x faster                                       |
| async_tree_io            | 1.61 sec                                                     | 1.06 sec: 1.52x faster                                     |
| unpickle_pure_python     | 315 us                                                       | 210 us: 1.50x faster                                       |
| async_tree_memoization   | 827 ms                                                       | 553 ms: 1.50x faster                                       |
| mako                     | 14.7 ms                                                      | 9.98 ms: 1.48x faster                                      |
| crypto_pyaes             | 118 ms                                                       | 82.0 ms: 1.44x faster                                      |
| fannkuch                 | 488 ms                                                       | 348 ms: 1.40x faster                                       |
| pickle_pure_python       | 453 us                                                       | 324 us: 1.40x faster                                       |
| json_dumps               | 14.2 ms                                                      | 10.2 ms: 1.40x faster                                      |
| float                    | 109 ms                                                       | 77.7 ms: 1.40x faster                                      |
| regex_compile            | 192 ms                                                       | 139 ms: 1.39x faster                                       |
| deepcopy_memo            | 50.5 us                                                      | 36.5 us: 1.38x faster                                      |
| chameleon                | 9.88 ms                                                      | 7.25 ms: 1.36x faster                                      |
| async_tree_cpu_io_mixed  | 946 ms                                                       | 704 ms: 1.34x faster                                       |
| django_template          | 51.8 ms                                                      | 38.7 ms: 1.34x faster                                      |
| pycparser                | 1.65 sec                                                     | 1.23 sec: 1.34x faster                                     |
| tomli_loads              | 2.96 sec                                                     | 2.23 sec: 1.33x faster                                     |
| coroutines               | 30.9 ms                                                      | 23.2 ms: 1.33x faster                                      |
| pprint_pformat           | 2.15 sec                                                     | 1.63 sec: 1.32x faster                                     |
| xml_etree_process        | 76.4 ms                                                      | 58.2 ms: 1.31x faster                                      |
| logging_simple           | 9.06 us                                                      | 6.91 us: 1.31x faster                                      |
| pprint_safe_repr         | 1.04 sec                                                     | 798 ms: 1.30x faster                                       |
| tornado_http             | 157 ms                                                       | 120 ms: 1.30x faster                                       |
| logging_format           | 9.82 us                                                      | 7.61 us: 1.29x faster                                      |
| comprehensions           | 27.0 us                                                      | 21.0 us: 1.29x faster                                      |
| sqlglot_normalize        | 146 ms                                                       | 116 ms: 1.26x faster                                       |
| deepcopy                 | 459 us                                                       | 368 us: 1.25x faster                                       |
| nqueens                  | 112 ms                                                       | 89.6 ms: 1.25x faster                                      |
| scimark_fft              | 363 ms                                                       | 294 ms: 1.24x faster                                       |
| dulwich_log              | 80.0 ms                                                      | 64.9 ms: 1.23x faster                                      |
| json_loads               | 30.0 us                                                      | 24.4 us: 1.23x faster                                      |
| sqlalchemy_imperative    | 23.0 ms                                                      | 18.7 ms: 1.23x faster                                      |
| sympy_expand             | 599 ms                                                       | 489 ms: 1.22x faster                                       |
| 2to3                     | 349 ms                                                       | 286 ms: 1.22x faster                                       |
| sqlglot_optimize         | 69.9 ms                                                      | 58.0 ms: 1.20x faster                                      |
| sympy_sum                | 194 ms                                                       | 161 ms: 1.20x faster                                       |
| sympy_integrate          | 28.3 ms                                                      | 23.6 ms: 1.20x faster                                      |
| docutils                 | 3.42 sec                                                     | 2.85 sec: 1.20x faster                                     |
| gunicorn                 | 1.20 ms                                                      | 1.00 ms: 1.20x faster                                      |
| scimark_sparse_mat_mult  | 5.21 ms                                                      | 4.35 ms: 1.20x faster                                      |
| sympy_str                | 359 ms                                                       | 301 ms: 1.19x faster                                       |
| dask                     | 469 ms                                                       | 394 ms: 1.19x faster                                       |
| sqlalchemy_declarative   | 189 ms                                                       | 159 ms: 1.19x faster                                       |
| bench_thread_pool        | 1.13 ms                                                      | 959 us: 1.18x faster                                       |
| aiohttp                  | 1.21 ms                                                      | 1.02 ms: 1.18x faster                                      |
| deepcopy_reduce          | 4.00 us                                                      | 3.42 us: 1.17x faster                                      |
| bench_mp_pool            | 6.82 ms                                                      | 5.86 ms: 1.16x faster                                      |
| mdp                      | 2.94 sec                                                     | 2.54 sec: 1.16x faster                                     |
| json                     | 5.91 ms                                                      | 5.11 ms: 1.16x faster                                      |
| create_gc_cycles         | 1.79 ms                                                      | 1.60 ms: 1.12x faster                                      |
| regex_v8                 | 27.1 ms                                                      | 24.2 ms: 1.12x faster                                      |
| unpack_sequence          | 60.3 ns                                                      | 53.9 ns: 1.12x faster                                      |
| pathlib                  | 21.2 ms                                                      | 19.4 ms: 1.09x faster                                      |
| xml_etree_generate       | 93.1 ms                                                      | 86.0 ms: 1.08x faster                                      |
| sqlite_synth             | 2.97 us                                                      | 2.74 us: 1.08x faster                                      |
| xml_etree_parse          | 159 ms                                                       | 148 ms: 1.08x faster                                       |
| async_generators         | 418 ms                                                       | 390 ms: 1.07x faster                                       |
| regex_dna                | 260 ms                                                       | 244 ms: 1.07x faster                                       |
| meteor_contest           | 138 ms                                                       | 130 ms: 1.06x faster                                       |
| xml_etree_iterparse      | 110 ms                                                       | 104 ms: 1.06x faster                                       |
| pidigits                 | 270 ms                                                       | 264 ms: 1.02x faster                                       |
| gc_traversal             | 3.63 ms                                                      | 3.55 ms: 1.02x faster                                      |
| asyncio_websockets       | 394 ms                                                       | 387 ms: 1.02x faster                                       |
| coverage                 | 65.9 ms                                                      | 64.9 ms: 1.02x faster                                      |
| python_startup           | 11.5 ms                                                      | 11.7 ms: 1.01x slower                                      |
| pickle                   | 10.1 us                                                      | 10.2 us: 1.01x slower                                      |
| telco                    | 7.21 ms                                                      | 7.59 ms: 1.05x slower                                      |
| unpickle                 | 13.9 us                                                      | 14.9 us: 1.07x slower                                      |
| unpickle_list            | 4.45 us                                                      | 4.75 us: 1.07x slower                                      |
| pickle_dict              | 30.4 us                                                      | 32.6 us: 1.07x slower                                      |
| pickle_list              | 4.23 us                                                      | 4.57 us: 1.08x slower                                      |
| regex_effbot             | 3.10 ms                                                      | 3.50 ms: 1.13x slower                                      |
| python_startup_no_site   | 7.35 ms                                                      | 8.63 ms: 1.17x slower                                      |
| Geometric mean           | (ref)                                                        | 1.30x faster                                               |

Benchmark hidden because not significant (1): mypy2
Ignored benchmarks (6) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120.json: flaskblogging, genshi_text, genshi_xml, html5lib, pylint, thrift
Ignored benchmarks (4) of results/bm-20231104-3.12.0+-9c583f3/bm-20231104-pythonperf2-x86_64-python-3.12-3.12.0+-9c583f3.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.25x
- 95% likely to have a speedup of 1.24x
- 99% likely to have a speedup of 1.22x
