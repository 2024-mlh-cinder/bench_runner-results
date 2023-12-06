
# Results vs. 3.10.4

- fork: python
- ref: 3.12
- machine: linux-x86_64
- commit hash: af83d1e
- commit date: 2023-09-08
- overall geometric mean: 1.30x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.22x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230908-pythonperf2-x86_64-python-3.12-3.12.0rc2+-af83d1e |
|----------------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| 2to3           | 350 ms                                                       | 287 ms: 1.22x faster                                          |
| docutils       | 3.40 sec                                                     | 2.89 sec: 1.18x faster                                        |
| tornado_http   | 152 ms                                                       | 121 ms: 1.26x faster                                          |
| Geometric mean | (ref)                                                        | 1.22x faster                                                  |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230908-pythonperf2-x86_64-python-3.12-3.12.0rc2+-af83d1e |
|----------------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| nbody          | 137 ms                                                       | 85.4 ms: 1.61x faster                                         |
| float          | 110 ms                                                       | 79.3 ms: 1.39x faster                                         |
| pidigits       | 271 ms                                                       | 264 ms: 1.02x faster                                          |
| Geometric mean | (ref)                                                        | 1.32x faster                                                  |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230908-pythonperf2-x86_64-python-3.12-3.12.0rc2+-af83d1e |
|----------------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| regex_compile  | 194 ms                                                       | 146 ms: 1.33x faster                                          |
| regex_v8       | 26.6 ms                                                      | 23.3 ms: 1.14x faster                                         |
| regex_dna      | 259 ms                                                       | 238 ms: 1.09x faster                                          |
| regex_effbot   | 2.99 ms                                                      | 3.57 ms: 1.19x slower                                         |
| Geometric mean | (ref)                                                        | 1.08x faster                                                  |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230908-pythonperf2-x86_64-python-3.12-3.12.0rc2+-af83d1e |
|----------------------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| unpickle_pure_python | 321 us                                                       | 211 us: 1.52x faster                                          |
| pickle_pure_python   | 457 us                                                       | 326 us: 1.40x faster                                          |
| json_dumps           | 14.2 ms                                                      | 10.2 ms: 1.40x faster                                         |
| tomli_loads          | 2.97 sec                                                     | 2.14 sec: 1.39x faster                                        |
| xml_etree_process    | 76.0 ms                                                      | 59.0 ms: 1.29x faster                                         |
| json_loads           | 30.0 us                                                      | 24.3 us: 1.24x faster                                         |
| xml_etree_parse      | 162 ms                                                       | 145 ms: 1.11x faster                                          |
| xml_etree_generate   | 94.6 ms                                                      | 86.8 ms: 1.09x faster                                         |
| xml_etree_iterparse  | 110 ms                                                       | 102 ms: 1.08x faster                                          |
| pickle               | 9.94 us                                                      | 10.1 us: 1.02x slower                                         |
| unpickle             | 14.2 us                                                      | 15.0 us: 1.06x slower                                         |
| unpickle_list        | 4.49 us                                                      | 4.76 us: 1.06x slower                                         |
| pickle_dict          | 30.0 us                                                      | 31.9 us: 1.06x slower                                         |
| pickle_list          | 4.11 us                                                      | 4.41 us: 1.07x slower                                         |
| Geometric mean       | (ref)                                                        | 1.14x faster                                                  |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230908-pythonperf2-x86_64-python-3.12-3.12.0rc2+-af83d1e |
|------------------------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| python_startup         | 11.5 ms                                                      | 11.7 ms: 1.02x slower                                         |
| python_startup_no_site | 7.32 ms                                                      | 8.68 ms: 1.18x slower                                         |
| Geometric mean         | (ref)                                                        | 1.10x slower                                                  |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230908-pythonperf2-x86_64-python-3.12-3.12.0rc2+-af83d1e |
|-----------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| mako      | 14.7 ms                                                      | 9.87 ms: 1.49x faster                                         |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230908-pythonperf2-x86_64-python-3.12-3.12.0rc2+-af83d1e |
|--------------------------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| typing_runtime_protocols | 523 us                                                       | 155 us: 3.38x faster                                          |
| deltablue                | 7.47 ms                                                      | 3.26 ms: 2.29x faster                                         |
| asyncio_tcp              | 782 ms                                                       | 383 ms: 2.04x faster                                          |
| asyncio_tcp_ssl          | 3.09 sec                                                     | 1.57 sec: 1.96x faster                                        |
| richards_super           | 90.8 ms                                                      | 50.8 ms: 1.79x faster                                         |
| go                       | 259 ms                                                       | 150 ms: 1.73x faster                                          |
| logging_silent           | 166 ns                                                       | 95.8 ns: 1.73x faster                                         |
| chaos                    | 107 ms                                                       | 63.5 ms: 1.69x faster                                         |
| richards                 | 74.1 ms                                                      | 44.2 ms: 1.68x faster                                         |
| scimark_lu               | 164 ms                                                       | 99.0 ms: 1.65x faster                                         |
| scimark_sor              | 177 ms                                                       | 109 ms: 1.62x faster                                          |
| sqlglot_parse            | 2.26 ms                                                      | 1.40 ms: 1.61x faster                                         |
| nbody                    | 137 ms                                                       | 85.4 ms: 1.61x faster                                         |
| hexiom                   | 9.52 ms                                                      | 5.95 ms: 1.60x faster                                         |
| raytrace                 | 488 ms                                                       | 305 ms: 1.60x faster                                          |
| generators               | 58.0 ms                                                      | 36.7 ms: 1.58x faster                                         |
| scimark_monte_carlo      | 109 ms                                                       | 70.0 ms: 1.56x faster                                         |
| bench_mp_pool            | 7.18 ms                                                      | 4.61 ms: 1.56x faster                                         |
| async_tree_none          | 700 ms                                                       | 455 ms: 1.54x faster                                          |
| async_tree_io            | 1.61 sec                                                     | 1.05 sec: 1.54x faster                                        |
| unpickle_pure_python     | 321 us                                                       | 211 us: 1.52x faster                                          |
| sqlglot_transpile        | 2.71 ms                                                      | 1.80 ms: 1.51x faster                                         |
| async_tree_memoization   | 824 ms                                                       | 548 ms: 1.50x faster                                          |
| pyflate                  | 697 ms                                                       | 466 ms: 1.50x faster                                          |
| mako                     | 14.7 ms                                                      | 9.87 ms: 1.49x faster                                         |
| spectral_norm            | 136 ms                                                       | 91.9 ms: 1.48x faster                                         |
| crypto_pyaes             | 118 ms                                                       | 80.5 ms: 1.47x faster                                         |
| fannkuch                 | 496 ms                                                       | 344 ms: 1.44x faster                                          |
| pickle_pure_python       | 457 us                                                       | 326 us: 1.40x faster                                          |
| json_dumps               | 14.2 ms                                                      | 10.2 ms: 1.40x faster                                         |
| float                    | 110 ms                                                       | 79.3 ms: 1.39x faster                                         |
| tomli_loads              | 2.97 sec                                                     | 2.14 sec: 1.39x faster                                        |
| async_tree_cpu_io_mixed  | 952 ms                                                       | 701 ms: 1.36x faster                                          |
| pycparser                | 1.66 sec                                                     | 1.24 sec: 1.34x faster                                        |
| coroutines               | 30.4 ms                                                      | 22.8 ms: 1.33x faster                                         |
| regex_compile            | 194 ms                                                       | 146 ms: 1.33x faster                                          |
| deepcopy_memo            | 48.9 us                                                      | 37.8 us: 1.29x faster                                         |
| logging_simple           | 8.90 us                                                      | 6.89 us: 1.29x faster                                         |
| xml_etree_process        | 76.0 ms                                                      | 59.0 ms: 1.29x faster                                         |
| pprint_pformat           | 2.15 sec                                                     | 1.67 sec: 1.29x faster                                        |
| logging_format           | 9.57 us                                                      | 7.51 us: 1.27x faster                                         |
| pprint_safe_repr         | 1.05 sec                                                     | 825 ms: 1.27x faster                                          |
| mypy2                    | 466 ms                                                       | 368 ms: 1.27x faster                                          |
| unpack_sequence          | 59.5 ns                                                      | 47.3 ns: 1.26x faster                                         |
| tornado_http             | 152 ms                                                       | 121 ms: 1.26x faster                                          |
| nqueens                  | 112 ms                                                       | 90.4 ms: 1.24x faster                                         |
| json_loads               | 30.0 us                                                      | 24.3 us: 1.24x faster                                         |
| comprehensions           | 26.9 us                                                      | 21.9 us: 1.23x faster                                         |
| 2to3                     | 350 ms                                                       | 287 ms: 1.22x faster                                          |
| dulwich_log              | 80.1 ms                                                      | 65.9 ms: 1.21x faster                                         |
| sqlglot_normalize        | 144 ms                                                       | 119 ms: 1.21x faster                                          |
| sqlglot_optimize         | 70.3 ms                                                      | 58.1 ms: 1.21x faster                                         |
| mdp                      | 3.03 sec                                                     | 2.56 sec: 1.18x faster                                        |
| scimark_fft              | 359 ms                                                       | 304 ms: 1.18x faster                                          |
| deepcopy                 | 454 us                                                       | 385 us: 1.18x faster                                          |
| docutils                 | 3.40 sec                                                     | 2.89 sec: 1.18x faster                                        |
| scimark_sparse_mat_mult  | 5.19 ms                                                      | 4.44 ms: 1.17x faster                                         |
| bench_thread_pool        | 1.14 ms                                                      | 973 us: 1.17x faster                                          |
| json                     | 5.96 ms                                                      | 5.11 ms: 1.17x faster                                         |
| deepcopy_reduce          | 4.03 us                                                      | 3.47 us: 1.16x faster                                         |
| regex_v8                 | 26.6 ms                                                      | 23.3 ms: 1.14x faster                                         |
| create_gc_cycles         | 1.82 ms                                                      | 1.61 ms: 1.13x faster                                         |
| xml_etree_parse          | 162 ms                                                       | 145 ms: 1.11x faster                                          |
| async_generators         | 422 ms                                                       | 381 ms: 1.11x faster                                          |
| sqlite_synth             | 2.97 us                                                      | 2.71 us: 1.09x faster                                         |
| pathlib                  | 21.7 ms                                                      | 19.9 ms: 1.09x faster                                         |
| regex_dna                | 259 ms                                                       | 238 ms: 1.09x faster                                          |
| xml_etree_generate       | 94.6 ms                                                      | 86.8 ms: 1.09x faster                                         |
| meteor_contest           | 137 ms                                                       | 126 ms: 1.08x faster                                          |
| xml_etree_iterparse      | 110 ms                                                       | 102 ms: 1.08x faster                                          |
| pidigits                 | 271 ms                                                       | 264 ms: 1.02x faster                                          |
| telco                    | 7.14 ms                                                      | 6.99 ms: 1.02x faster                                         |
| pickle                   | 9.94 us                                                      | 10.1 us: 1.02x slower                                         |
| python_startup           | 11.5 ms                                                      | 11.7 ms: 1.02x slower                                         |
| unpickle                 | 14.2 us                                                      | 15.0 us: 1.06x slower                                         |
| unpickle_list            | 4.49 us                                                      | 4.76 us: 1.06x slower                                         |
| pickle_dict              | 30.0 us                                                      | 31.9 us: 1.06x slower                                         |
| pickle_list              | 4.11 us                                                      | 4.41 us: 1.07x slower                                         |
| gc_traversal             | 3.45 ms                                                      | 3.76 ms: 1.09x slower                                         |
| python_startup_no_site   | 7.32 ms                                                      | 8.68 ms: 1.18x slower                                         |
| regex_effbot             | 2.99 ms                                                      | 3.57 ms: 1.19x slower                                         |
| dask                     | 463 ms                                                       | 567 ms: 1.22x slower                                          |
| coverage                 | 64.0 ms                                                      | 88.7 ms: 1.39x slower                                         |
| Geometric mean           | (ref)                                                        | 1.30x faster                                                  |
Ignored benchmarks (16) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.26x
- 95% likely to have a speedup of 1.25x
- 99% likely to have a speedup of 1.22x
