
# Results vs. 3.10.4

- fork: python
- ref: 3.12
- machine: windows-amd64
- commit hash: af83d1e
- commit date: 2023-09-08
- overall geometric mean: 1.18x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.11x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230908-pythonperf1-amd64-python-3.12-3.12.0rc2+-af83d1e |
|----------------|:-----------------------------------------------------------:|:------------------------------------------------------------:|
| 2to3           | 237 ms                                                      | 213 ms: 1.11x faster                                         |
| docutils       | 1.89 sec                                                    | 1.64 sec: 1.15x faster                                       |
| tornado_http   | 109 ms                                                      | 87.4 ms: 1.25x faster                                        |
| Geometric mean | (ref)                                                       | 1.17x faster                                                 |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230908-pythonperf1-amd64-python-3.12-3.12.0rc2+-af83d1e |
|----------------|:-----------------------------------------------------------:|:------------------------------------------------------------:|
| float          | 60.2 ms                                                     | 54.2 ms: 1.11x faster                                        |
| pidigits       | 145 ms                                                      | 150 ms: 1.03x slower                                         |
| Geometric mean | (ref)                                                       | 1.03x faster                                                 |

Benchmark hidden because not significant (1): nbody

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230908-pythonperf1-amd64-python-3.12-3.12.0rc2+-af83d1e |
|----------------|:-----------------------------------------------------------:|:------------------------------------------------------------:|
| regex_compile  | 103 ms                                                      | 86.3 ms: 1.20x faster                                        |
| regex_v8       | 15.0 ms                                                     | 13.7 ms: 1.09x faster                                        |
| regex_dna      | 132 ms                                                      | 121 ms: 1.09x faster                                         |
| regex_effbot   | 1.66 ms                                                     | 1.59 ms: 1.05x faster                                        |
| Geometric mean | (ref)                                                       | 1.11x faster                                                 |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230908-pythonperf1-amd64-python-3.12-3.12.0rc2+-af83d1e |
|----------------------|:-----------------------------------------------------------:|:------------------------------------------------------------:|
| json_dumps           | 8.50 ms                                                     | 5.70 ms: 1.49x faster                                        |
| pickle_pure_python   | 257 us                                                      | 195 us: 1.32x faster                                         |
| unpickle_pure_python | 171 us                                                      | 133 us: 1.29x faster                                         |
| tomli_loads          | 1.62 sec                                                    | 1.37 sec: 1.19x faster                                       |
| xml_etree_process    | 43.4 ms                                                     | 37.6 ms: 1.16x faster                                        |
| xml_etree_parse      | 102 ms                                                      | 89.8 ms: 1.13x faster                                        |
| unpickle             | 9.17 us                                                     | 8.21 us: 1.12x faster                                        |
| json_loads           | 14.2 us                                                     | 13.5 us: 1.05x faster                                        |
| unpickle_list        | 2.81 us                                                     | 2.69 us: 1.05x faster                                        |
| xml_etree_iterparse  | 63.5 ms                                                     | 62.7 ms: 1.01x faster                                        |
| xml_etree_generate   | 54.5 ms                                                     | 55.0 ms: 1.01x slower                                        |
| pickle               | 6.80 us                                                     | 7.17 us: 1.05x slower                                        |
| pickle_list          | 2.59 us                                                     | 2.81 us: 1.08x slower                                        |
| pickle_dict          | 16.9 us                                                     | 18.6 us: 1.10x slower                                        |
| Geometric mean       | (ref)                                                       | 1.10x faster                                                 |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230908-pythonperf1-amd64-python-3.12-3.12.0rc2+-af83d1e |
|------------------------|:-----------------------------------------------------------:|:------------------------------------------------------------:|
| python_startup         | 20.0 ms                                                     | 19.3 ms: 1.04x faster                                        |
| python_startup_no_site | 15.5 ms                                                     | 16.4 ms: 1.06x slower                                        |
| Geometric mean         | (ref)                                                       | 1.01x slower                                                 |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230908-pythonperf1-amd64-python-3.12-3.12.0rc2+-af83d1e |
|-----------|:-----------------------------------------------------------:|:------------------------------------------------------------:|
| mako      | 8.80 ms                                                     | 6.87 ms: 1.28x faster                                        |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230908-pythonperf1-amd64-python-3.12-3.12.0rc2+-af83d1e |
|--------------------------|:-----------------------------------------------------------:|:------------------------------------------------------------:|
| typing_runtime_protocols | 325 us                                                      | 96.2 us: 3.37x faster                                        |
| deltablue                | 4.17 ms                                                     | 2.16 ms: 1.93x faster                                        |
| richards_super           | 51.7 ms                                                     | 30.1 ms: 1.72x faster                                        |
| mypy2                    | 352 ms                                                      | 208 ms: 1.69x faster                                         |
| logging_silent           | 96.4 ns                                                     | 60.2 ns: 1.60x faster                                        |
| go                       | 136 ms                                                      | 86.7 ms: 1.57x faster                                        |
| richards                 | 41.2 ms                                                     | 26.7 ms: 1.54x faster                                        |
| sqlglot_parse            | 1.22 ms                                                     | 806 us: 1.51x faster                                         |
| asyncio_tcp              | 712 ms                                                      | 472 ms: 1.51x faster                                         |
| json_dumps               | 8.50 ms                                                     | 5.70 ms: 1.49x faster                                        |
| scimark_lu               | 85.4 ms                                                     | 57.3 ms: 1.49x faster                                        |
| async_tree_memoization   | 497 ms                                                      | 336 ms: 1.48x faster                                         |
| async_tree_io            | 1.07 sec                                                    | 723 ms: 1.47x faster                                         |
| async_tree_none          | 420 ms                                                      | 289 ms: 1.45x faster                                         |
| raytrace                 | 271 ms                                                      | 188 ms: 1.44x faster                                         |
| sqlglot_transpile        | 1.46 ms                                                     | 1.02 ms: 1.43x faster                                        |
| generators               | 31.6 ms                                                     | 22.5 ms: 1.41x faster                                        |
| chaos                    | 58.9 ms                                                     | 42.5 ms: 1.39x faster                                        |
| hexiom                   | 5.52 ms                                                     | 4.03 ms: 1.37x faster                                        |
| scimark_sor              | 105 ms                                                      | 77.9 ms: 1.35x faster                                        |
| crypto_pyaes             | 62.3 ms                                                     | 47.0 ms: 1.33x faster                                        |
| pyflate                  | 387 ms                                                      | 293 ms: 1.32x faster                                         |
| scimark_monte_carlo      | 55.9 ms                                                     | 42.4 ms: 1.32x faster                                        |
| pickle_pure_python       | 257 us                                                      | 195 us: 1.32x faster                                         |
| unpickle_pure_python     | 171 us                                                      | 133 us: 1.29x faster                                         |
| mako                     | 8.80 ms                                                     | 6.87 ms: 1.28x faster                                        |
| async_tree_cpu_io_mixed  | 609 ms                                                      | 478 ms: 1.27x faster                                         |
| pycparser                | 868 ms                                                      | 682 ms: 1.27x faster                                         |
| tornado_http             | 109 ms                                                      | 87.4 ms: 1.25x faster                                        |
| mdp                      | 1.71 sec                                                    | 1.40 sec: 1.23x faster                                       |
| spectral_norm            | 78.0 ms                                                     | 64.0 ms: 1.22x faster                                        |
| regex_compile            | 103 ms                                                      | 86.3 ms: 1.20x faster                                        |
| tomli_loads              | 1.62 sec                                                    | 1.37 sec: 1.19x faster                                       |
| pprint_pformat           | 1.21 sec                                                    | 1.02 sec: 1.18x faster                                       |
| deepcopy_memo            | 28.5 us                                                     | 24.1 us: 1.18x faster                                        |
| aiohttp                  | 1.01 ms                                                     | 854 us: 1.18x faster                                         |
| pprint_safe_repr         | 589 ms                                                      | 500 ms: 1.18x faster                                         |
| xml_etree_process        | 43.4 ms                                                     | 37.6 ms: 1.16x faster                                        |
| docutils                 | 1.89 sec                                                    | 1.64 sec: 1.15x faster                                       |
| coroutines               | 15.9 ms                                                     | 14.0 ms: 1.14x faster                                        |
| xml_etree_parse          | 102 ms                                                      | 89.8 ms: 1.13x faster                                        |
| sqlglot_optimize         | 39.0 ms                                                     | 34.6 ms: 1.13x faster                                        |
| bench_thread_pool        | 946 us                                                      | 841 us: 1.12x faster                                         |
| comprehensions           | 16.0 us                                                     | 14.2 us: 1.12x faster                                        |
| dulwich_log              | 47.6 ms                                                     | 42.5 ms: 1.12x faster                                        |
| unpickle                 | 9.17 us                                                     | 8.21 us: 1.12x faster                                        |
| 2to3                     | 237 ms                                                      | 213 ms: 1.11x faster                                         |
| float                    | 60.2 ms                                                     | 54.2 ms: 1.11x faster                                        |
| scimark_fft              | 193 ms                                                      | 175 ms: 1.10x faster                                         |
| fannkuch                 | 258 ms                                                      | 234 ms: 1.10x faster                                         |
| regex_v8                 | 15.0 ms                                                     | 13.7 ms: 1.09x faster                                        |
| sqlglot_normalize        | 202 ms                                                      | 185 ms: 1.09x faster                                         |
| regex_dna                | 132 ms                                                      | 121 ms: 1.09x faster                                         |
| nqueens                  | 67.0 ms                                                     | 61.5 ms: 1.09x faster                                        |
| create_gc_cycles         | 782 us                                                      | 723 us: 1.08x faster                                         |
| deepcopy                 | 255 us                                                      | 237 us: 1.08x faster                                         |
| scimark_sparse_mat_mult  | 2.66 ms                                                     | 2.48 ms: 1.07x faster                                        |
| asyncio_tcp_ssl          | 2.03 sec                                                    | 1.90 sec: 1.07x faster                                       |
| sqlite_synth             | 1.84 us                                                     | 1.75 us: 1.05x faster                                        |
| json_loads               | 14.2 us                                                     | 13.5 us: 1.05x faster                                        |
| json                     | 3.05 ms                                                     | 2.91 ms: 1.05x faster                                        |
| regex_effbot             | 1.66 ms                                                     | 1.59 ms: 1.05x faster                                        |
| unpickle_list            | 2.81 us                                                     | 2.69 us: 1.05x faster                                        |
| deepcopy_reduce          | 2.16 us                                                     | 2.06 us: 1.05x faster                                        |
| python_startup           | 20.0 ms                                                     | 19.3 ms: 1.04x faster                                        |
| xml_etree_iterparse      | 63.5 ms                                                     | 62.7 ms: 1.01x faster                                        |
| meteor_contest           | 72.5 ms                                                     | 72.1 ms: 1.01x faster                                        |
| xml_etree_generate       | 54.5 ms                                                     | 55.0 ms: 1.01x slower                                        |
| logging_format           | 6.66 us                                                     | 6.74 us: 1.01x slower                                        |
| pathlib                  | 77.4 ms                                                     | 78.9 ms: 1.02x slower                                        |
| logging_simple           | 6.20 us                                                     | 6.32 us: 1.02x slower                                        |
| pidigits                 | 145 ms                                                      | 150 ms: 1.03x slower                                         |
| async_generators         | 224 ms                                                      | 234 ms: 1.05x slower                                         |
| pickle                   | 6.80 us                                                     | 7.17 us: 1.05x slower                                        |
| python_startup_no_site   | 15.5 ms                                                     | 16.4 ms: 1.06x slower                                        |
| telco                    | 3.78 ms                                                     | 4.07 ms: 1.08x slower                                        |
| pickle_list              | 2.59 us                                                     | 2.81 us: 1.08x slower                                        |
| pickle_dict              | 16.9 us                                                     | 18.6 us: 1.10x slower                                        |
| gc_traversal             | 1.34 ms                                                     | 1.49 ms: 1.11x slower                                        |
| bench_mp_pool            | 60.7 ms                                                     | 67.2 ms: 1.11x slower                                        |
| dask                     | 305 ms                                                      | 361 ms: 1.18x slower                                         |
| coverage                 | 40.0 ms                                                     | 50.1 ms: 1.25x slower                                        |
| Geometric mean           | (ref)                                                       | 1.18x faster                                                 |

Benchmark hidden because not significant (2): unpack_sequence, nbody
Ignored benchmarks (14) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120.json: chameleon, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.13x
- 95% likely to have a speedup of 1.12x
- 99% likely to have a speedup of 1.11x
