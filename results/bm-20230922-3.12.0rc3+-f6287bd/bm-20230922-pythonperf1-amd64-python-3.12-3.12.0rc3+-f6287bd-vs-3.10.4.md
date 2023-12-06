
# Results vs. 3.10.4

- fork: python
- ref: 3.12
- machine: windows-amd64
- commit hash: f6287bd
- commit date: 2023-09-22
- overall geometric mean: 1.18x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.11x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230922-pythonperf1-amd64-python-3.12-3.12.0rc3+-f6287bd |
|----------------|:-----------------------------------------------------------:|:------------------------------------------------------------:|
| 2to3           | 237 ms                                                      | 211 ms: 1.12x faster                                         |
| docutils       | 1.89 sec                                                    | 1.62 sec: 1.17x faster                                       |
| tornado_http   | 109 ms                                                      | 87.6 ms: 1.25x faster                                        |
| Geometric mean | (ref)                                                       | 1.18x faster                                                 |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230922-pythonperf1-amd64-python-3.12-3.12.0rc3+-f6287bd |
|----------------|:-----------------------------------------------------------:|:------------------------------------------------------------:|
| float          | 60.2 ms                                                     | 54.5 ms: 1.10x faster                                        |
| pidigits       | 145 ms                                                      | 150 ms: 1.03x slower                                         |
| nbody          | 69.3 ms                                                     | 71.8 ms: 1.04x slower                                        |
| Geometric mean | (ref)                                                       | 1.01x faster                                                 |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230922-pythonperf1-amd64-python-3.12-3.12.0rc3+-f6287bd |
|----------------|:-----------------------------------------------------------:|:------------------------------------------------------------:|
| regex_compile  | 103 ms                                                      | 86.9 ms: 1.19x faster                                        |
| regex_dna      | 132 ms                                                      | 118 ms: 1.12x faster                                         |
| regex_v8       | 15.0 ms                                                     | 13.5 ms: 1.11x faster                                        |
| regex_effbot   | 1.66 ms                                                     | 1.58 ms: 1.05x faster                                        |
| Geometric mean | (ref)                                                       | 1.12x faster                                                 |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230922-pythonperf1-amd64-python-3.12-3.12.0rc3+-f6287bd |
|----------------------|:-----------------------------------------------------------:|:------------------------------------------------------------:|
| json_dumps           | 8.50 ms                                                     | 5.68 ms: 1.50x faster                                        |
| pickle_pure_python   | 257 us                                                      | 192 us: 1.34x faster                                         |
| unpickle_pure_python | 171 us                                                      | 135 us: 1.27x faster                                         |
| tomli_loads          | 1.62 sec                                                    | 1.36 sec: 1.19x faster                                       |
| xml_etree_process    | 43.4 ms                                                     | 38.2 ms: 1.14x faster                                        |
| xml_etree_parse      | 102 ms                                                      | 90.9 ms: 1.12x faster                                        |
| unpickle             | 9.17 us                                                     | 8.40 us: 1.09x faster                                        |
| unpickle_list        | 2.81 us                                                     | 2.68 us: 1.05x faster                                        |
| json_loads           | 14.2 us                                                     | 13.6 us: 1.04x faster                                        |
| xml_etree_generate   | 54.5 ms                                                     | 55.6 ms: 1.02x slower                                        |
| pickle               | 6.80 us                                                     | 7.09 us: 1.04x slower                                        |
| pickle_dict          | 16.9 us                                                     | 18.4 us: 1.09x slower                                        |
| pickle_list          | 2.59 us                                                     | 2.88 us: 1.11x slower                                        |
| Geometric mean       | (ref)                                                       | 1.10x faster                                                 |

Benchmark hidden because not significant (1): xml_etree_iterparse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230922-pythonperf1-amd64-python-3.12-3.12.0rc3+-f6287bd |
|------------------------|:-----------------------------------------------------------:|:------------------------------------------------------------:|
| python_startup         | 20.0 ms                                                     | 18.8 ms: 1.06x faster                                        |
| python_startup_no_site | 15.5 ms                                                     | 16.0 ms: 1.03x slower                                        |
| Geometric mean         | (ref)                                                       | 1.02x faster                                                 |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230922-pythonperf1-amd64-python-3.12-3.12.0rc3+-f6287bd |
|-----------|:-----------------------------------------------------------:|:------------------------------------------------------------:|
| mako      | 8.80 ms                                                     | 6.93 ms: 1.27x faster                                        |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230922-pythonperf1-amd64-python-3.12-3.12.0rc3+-f6287bd |
|--------------------------|:-----------------------------------------------------------:|:------------------------------------------------------------:|
| typing_runtime_protocols | 325 us                                                      | 96.0 us: 3.38x faster                                        |
| deltablue                | 4.17 ms                                                     | 2.13 ms: 1.96x faster                                        |
| richards_super           | 51.7 ms                                                     | 30.4 ms: 1.70x faster                                        |
| mypy2                    | 352 ms                                                      | 209 ms: 1.69x faster                                         |
| logging_silent           | 96.4 ns                                                     | 60.6 ns: 1.59x faster                                        |
| go                       | 136 ms                                                      | 87.5 ms: 1.56x faster                                        |
| richards                 | 41.2 ms                                                     | 26.6 ms: 1.55x faster                                        |
| asyncio_tcp              | 712 ms                                                      | 464 ms: 1.54x faster                                         |
| sqlglot_parse            | 1.22 ms                                                     | 809 us: 1.51x faster                                         |
| json_dumps               | 8.50 ms                                                     | 5.68 ms: 1.50x faster                                        |
| async_tree_io            | 1.07 sec                                                    | 718 ms: 1.48x faster                                         |
| async_tree_memoization   | 497 ms                                                      | 337 ms: 1.48x faster                                         |
| scimark_lu               | 85.4 ms                                                     | 58.5 ms: 1.46x faster                                        |
| async_tree_none          | 420 ms                                                      | 288 ms: 1.46x faster                                         |
| sqlglot_transpile        | 1.46 ms                                                     | 1.02 ms: 1.43x faster                                        |
| raytrace                 | 271 ms                                                      | 190 ms: 1.43x faster                                         |
| chaos                    | 58.9 ms                                                     | 42.4 ms: 1.39x faster                                        |
| generators               | 31.6 ms                                                     | 22.9 ms: 1.38x faster                                        |
| hexiom                   | 5.52 ms                                                     | 4.00 ms: 1.38x faster                                        |
| crypto_pyaes             | 62.3 ms                                                     | 46.0 ms: 1.36x faster                                        |
| pickle_pure_python       | 257 us                                                      | 192 us: 1.34x faster                                         |
| pyflate                  | 387 ms                                                      | 296 ms: 1.31x faster                                         |
| scimark_sor              | 105 ms                                                      | 80.9 ms: 1.30x faster                                        |
| pycparser                | 868 ms                                                      | 670 ms: 1.30x faster                                         |
| async_tree_cpu_io_mixed  | 609 ms                                                      | 477 ms: 1.28x faster                                         |
| mako                     | 8.80 ms                                                     | 6.93 ms: 1.27x faster                                        |
| unpickle_pure_python     | 171 us                                                      | 135 us: 1.27x faster                                         |
| scimark_monte_carlo      | 55.9 ms                                                     | 44.1 ms: 1.27x faster                                        |
| tornado_http             | 109 ms                                                      | 87.6 ms: 1.25x faster                                        |
| spectral_norm            | 78.0 ms                                                     | 63.2 ms: 1.23x faster                                        |
| deepcopy_memo            | 28.5 us                                                     | 23.7 us: 1.20x faster                                        |
| tomli_loads              | 1.62 sec                                                    | 1.36 sec: 1.19x faster                                       |
| regex_compile            | 103 ms                                                      | 86.9 ms: 1.19x faster                                        |
| aiohttp                  | 1.01 ms                                                     | 854 us: 1.18x faster                                         |
| pprint_pformat           | 1.21 sec                                                    | 1.03 sec: 1.17x faster                                       |
| docutils                 | 1.89 sec                                                    | 1.62 sec: 1.17x faster                                       |
| pprint_safe_repr         | 589 ms                                                      | 508 ms: 1.16x faster                                         |
| bench_thread_pool        | 946 us                                                      | 825 us: 1.15x faster                                         |
| comprehensions           | 16.0 us                                                     | 14.0 us: 1.14x faster                                        |
| sqlglot_optimize         | 39.0 ms                                                     | 34.2 ms: 1.14x faster                                        |
| xml_etree_process        | 43.4 ms                                                     | 38.2 ms: 1.14x faster                                        |
| mdp                      | 1.71 sec                                                    | 1.52 sec: 1.13x faster                                       |
| 2to3                     | 237 ms                                                      | 211 ms: 1.12x faster                                         |
| dulwich_log              | 47.6 ms                                                     | 42.5 ms: 1.12x faster                                        |
| xml_etree_parse          | 102 ms                                                      | 90.9 ms: 1.12x faster                                        |
| regex_dna                | 132 ms                                                      | 118 ms: 1.12x faster                                         |
| coroutines               | 15.9 ms                                                     | 14.3 ms: 1.11x faster                                        |
| regex_v8                 | 15.0 ms                                                     | 13.5 ms: 1.11x faster                                        |
| float                    | 60.2 ms                                                     | 54.5 ms: 1.10x faster                                        |
| sqlglot_normalize        | 202 ms                                                      | 184 ms: 1.10x faster                                         |
| unpickle                 | 9.17 us                                                     | 8.40 us: 1.09x faster                                        |
| nqueens                  | 67.0 ms                                                     | 61.5 ms: 1.09x faster                                        |
| asyncio_tcp_ssl          | 2.03 sec                                                    | 1.87 sec: 1.09x faster                                       |
| scimark_fft              | 193 ms                                                      | 178 ms: 1.09x faster                                         |
| fannkuch                 | 258 ms                                                      | 238 ms: 1.08x faster                                         |
| deepcopy                 | 255 us                                                      | 237 us: 1.08x faster                                         |
| create_gc_cycles         | 782 us                                                      | 726 us: 1.08x faster                                         |
| scimark_sparse_mat_mult  | 2.66 ms                                                     | 2.49 ms: 1.07x faster                                        |
| python_startup           | 20.0 ms                                                     | 18.8 ms: 1.06x faster                                        |
| json                     | 3.05 ms                                                     | 2.89 ms: 1.05x faster                                        |
| regex_effbot             | 1.66 ms                                                     | 1.58 ms: 1.05x faster                                        |
| unpickle_list            | 2.81 us                                                     | 2.68 us: 1.05x faster                                        |
| sqlite_synth             | 1.84 us                                                     | 1.75 us: 1.05x faster                                        |
| json_loads               | 14.2 us                                                     | 13.6 us: 1.04x faster                                        |
| deepcopy_reduce          | 2.16 us                                                     | 2.11 us: 1.02x faster                                        |
| logging_format           | 6.66 us                                                     | 6.61 us: 1.01x faster                                        |
| meteor_contest           | 72.5 ms                                                     | 72.4 ms: 1.00x faster                                        |
| pathlib                  | 77.4 ms                                                     | 78.2 ms: 1.01x slower                                        |
| unpack_sequence          | 37.8 ns                                                     | 38.5 ns: 1.02x slower                                        |
| xml_etree_generate       | 54.5 ms                                                     | 55.6 ms: 1.02x slower                                        |
| python_startup_no_site   | 15.5 ms                                                     | 16.0 ms: 1.03x slower                                        |
| pidigits                 | 145 ms                                                      | 150 ms: 1.03x slower                                         |
| nbody                    | 69.3 ms                                                     | 71.8 ms: 1.04x slower                                        |
| async_generators         | 224 ms                                                      | 233 ms: 1.04x slower                                         |
| pickle                   | 6.80 us                                                     | 7.09 us: 1.04x slower                                        |
| telco                    | 3.78 ms                                                     | 4.07 ms: 1.08x slower                                        |
| pickle_dict              | 16.9 us                                                     | 18.4 us: 1.09x slower                                        |
| bench_mp_pool            | 60.7 ms                                                     | 66.8 ms: 1.10x slower                                        |
| gc_traversal             | 1.34 ms                                                     | 1.49 ms: 1.11x slower                                        |
| pickle_list              | 2.59 us                                                     | 2.88 us: 1.11x slower                                        |
| dask                     | 305 ms                                                      | 362 ms: 1.19x slower                                         |
| coverage                 | 40.0 ms                                                     | 52.7 ms: 1.32x slower                                        |
| Geometric mean           | (ref)                                                       | 1.18x faster                                                 |

Benchmark hidden because not significant (2): logging_simple, xml_etree_iterparse
Ignored benchmarks (14) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120.json: chameleon, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.12x
- 95% likely to have a speedup of 1.12x
- 99% likely to have a speedup of 1.11x
