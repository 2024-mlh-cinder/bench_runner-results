
# Results vs. 3.10.4

- fork: python
- ref: 3.12
- machine: windows-amd64
- commit hash: 3e20303
- commit date: 2023-08-27
- overall geometric mean: 1.18x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.11x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230827-pythonperf1-amd64-python-3.12-3.12.0rc1+-3e20303 |
|----------------|:-----------------------------------------------------------:|:------------------------------------------------------------:|
| 2to3           | 237 ms                                                      | 214 ms: 1.11x faster                                         |
| docutils       | 1.89 sec                                                    | 1.60 sec: 1.18x faster                                       |
| tornado_http   | 109 ms                                                      | 88.4 ms: 1.23x faster                                        |
| Geometric mean | (ref)                                                       | 1.17x faster                                                 |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230827-pythonperf1-amd64-python-3.12-3.12.0rc1+-3e20303 |
|----------------|:-----------------------------------------------------------:|:------------------------------------------------------------:|
| float          | 60.2 ms                                                     | 53.8 ms: 1.12x faster                                        |
| pidigits       | 145 ms                                                      | 147 ms: 1.01x slower                                         |
| nbody          | 69.3 ms                                                     | 70.3 ms: 1.01x slower                                        |
| Geometric mean | (ref)                                                       | 1.03x faster                                                 |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230827-pythonperf1-amd64-python-3.12-3.12.0rc1+-3e20303 |
|----------------|:-----------------------------------------------------------:|:------------------------------------------------------------:|
| regex_compile  | 103 ms                                                      | 87.5 ms: 1.18x faster                                        |
| regex_v8       | 15.0 ms                                                     | 13.1 ms: 1.15x faster                                        |
| regex_dna      | 132 ms                                                      | 116 ms: 1.13x faster                                         |
| regex_effbot   | 1.66 ms                                                     | 1.58 ms: 1.05x faster                                        |
| Geometric mean | (ref)                                                       | 1.13x faster                                                 |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230827-pythonperf1-amd64-python-3.12-3.12.0rc1+-3e20303 |
|----------------------|:-----------------------------------------------------------:|:------------------------------------------------------------:|
| json_dumps           | 8.50 ms                                                     | 5.72 ms: 1.49x faster                                        |
| pickle_pure_python   | 257 us                                                      | 195 us: 1.32x faster                                         |
| unpickle_pure_python | 171 us                                                      | 135 us: 1.27x faster                                         |
| tomli_loads          | 1.62 sec                                                    | 1.36 sec: 1.20x faster                                       |
| xml_etree_process    | 43.4 ms                                                     | 37.8 ms: 1.15x faster                                        |
| xml_etree_parse      | 102 ms                                                      | 91.0 ms: 1.12x faster                                        |
| unpickle             | 9.17 us                                                     | 8.40 us: 1.09x faster                                        |
| json_loads           | 14.2 us                                                     | 13.7 us: 1.03x faster                                        |
| xml_etree_generate   | 54.5 ms                                                     | 55.8 ms: 1.02x slower                                        |
| unpickle_list        | 2.81 us                                                     | 2.90 us: 1.03x slower                                        |
| pickle               | 6.80 us                                                     | 7.36 us: 1.08x slower                                        |
| pickle_list          | 2.59 us                                                     | 2.81 us: 1.09x slower                                        |
| pickle_dict          | 16.9 us                                                     | 18.4 us: 1.09x slower                                        |
| Geometric mean       | (ref)                                                       | 1.09x faster                                                 |

Benchmark hidden because not significant (1): xml_etree_iterparse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230827-pythonperf1-amd64-python-3.12-3.12.0rc1+-3e20303 |
|------------------------|:-----------------------------------------------------------:|:------------------------------------------------------------:|
| python_startup         | 20.0 ms                                                     | 19.4 ms: 1.03x faster                                        |
| python_startup_no_site | 15.5 ms                                                     | 16.7 ms: 1.08x slower                                        |
| Geometric mean         | (ref)                                                       | 1.02x slower                                                 |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230827-pythonperf1-amd64-python-3.12-3.12.0rc1+-3e20303 |
|-----------|:-----------------------------------------------------------:|:------------------------------------------------------------:|
| mako      | 8.80 ms                                                     | 6.90 ms: 1.28x faster                                        |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230827-pythonperf1-amd64-python-3.12-3.12.0rc1+-3e20303 |
|--------------------------|:-----------------------------------------------------------:|:------------------------------------------------------------:|
| typing_runtime_protocols | 325 us                                                      | 97.9 us: 3.31x faster                                        |
| deltablue                | 4.17 ms                                                     | 2.15 ms: 1.94x faster                                        |
| richards_super           | 51.7 ms                                                     | 29.0 ms: 1.78x faster                                        |
| mypy2                    | 352 ms                                                      | 209 ms: 1.68x faster                                         |
| richards                 | 41.2 ms                                                     | 25.8 ms: 1.60x faster                                        |
| logging_silent           | 96.4 ns                                                     | 60.7 ns: 1.59x faster                                        |
| go                       | 136 ms                                                      | 87.7 ms: 1.55x faster                                        |
| sqlglot_parse            | 1.22 ms                                                     | 797 us: 1.53x faster                                         |
| json_dumps               | 8.50 ms                                                     | 5.72 ms: 1.49x faster                                        |
| async_tree_memoization   | 497 ms                                                      | 335 ms: 1.49x faster                                         |
| asyncio_tcp              | 712 ms                                                      | 481 ms: 1.48x faster                                         |
| async_tree_io            | 1.07 sec                                                    | 720 ms: 1.48x faster                                         |
| async_tree_none          | 420 ms                                                      | 287 ms: 1.47x faster                                         |
| scimark_lu               | 85.4 ms                                                     | 58.7 ms: 1.46x faster                                        |
| sqlglot_transpile        | 1.46 ms                                                     | 1.01 ms: 1.44x faster                                        |
| raytrace                 | 271 ms                                                      | 189 ms: 1.44x faster                                         |
| generators               | 31.6 ms                                                     | 22.4 ms: 1.41x faster                                        |
| chaos                    | 58.9 ms                                                     | 41.9 ms: 1.40x faster                                        |
| hexiom                   | 5.52 ms                                                     | 4.06 ms: 1.36x faster                                        |
| crypto_pyaes             | 62.3 ms                                                     | 46.4 ms: 1.34x faster                                        |
| scimark_sor              | 105 ms                                                      | 78.2 ms: 1.34x faster                                        |
| pickle_pure_python       | 257 us                                                      | 195 us: 1.32x faster                                         |
| pyflate                  | 387 ms                                                      | 294 ms: 1.32x faster                                         |
| scimark_monte_carlo      | 55.9 ms                                                     | 42.5 ms: 1.32x faster                                        |
| async_tree_cpu_io_mixed  | 609 ms                                                      | 477 ms: 1.28x faster                                         |
| mako                     | 8.80 ms                                                     | 6.90 ms: 1.28x faster                                        |
| unpickle_pure_python     | 171 us                                                      | 135 us: 1.27x faster                                         |
| pycparser                | 868 ms                                                      | 691 ms: 1.26x faster                                         |
| tornado_http             | 109 ms                                                      | 88.4 ms: 1.23x faster                                        |
| spectral_norm            | 78.0 ms                                                     | 63.5 ms: 1.23x faster                                        |
| deepcopy_memo            | 28.5 us                                                     | 23.3 us: 1.23x faster                                        |
| mdp                      | 1.71 sec                                                    | 1.43 sec: 1.20x faster                                       |
| tomli_loads              | 1.62 sec                                                    | 1.36 sec: 1.20x faster                                       |
| regex_compile            | 103 ms                                                      | 87.5 ms: 1.18x faster                                        |
| docutils                 | 1.89 sec                                                    | 1.60 sec: 1.18x faster                                       |
| aiohttp                  | 1.01 ms                                                     | 859 us: 1.17x faster                                         |
| dulwich_log              | 47.6 ms                                                     | 40.8 ms: 1.17x faster                                        |
| xml_etree_process        | 43.4 ms                                                     | 37.8 ms: 1.15x faster                                        |
| regex_v8                 | 15.0 ms                                                     | 13.1 ms: 1.15x faster                                        |
| pprint_pformat           | 1.21 sec                                                    | 1.05 sec: 1.15x faster                                       |
| pprint_safe_repr         | 589 ms                                                      | 514 ms: 1.15x faster                                         |
| coroutines               | 15.9 ms                                                     | 14.0 ms: 1.14x faster                                        |
| regex_dna                | 132 ms                                                      | 116 ms: 1.13x faster                                         |
| bench_thread_pool        | 946 us                                                      | 835 us: 1.13x faster                                         |
| sqlglot_optimize         | 39.0 ms                                                     | 34.4 ms: 1.13x faster                                        |
| xml_etree_parse          | 102 ms                                                      | 91.0 ms: 1.12x faster                                        |
| float                    | 60.2 ms                                                     | 53.8 ms: 1.12x faster                                        |
| 2to3                     | 237 ms                                                      | 214 ms: 1.11x faster                                         |
| comprehensions           | 16.0 us                                                     | 14.5 us: 1.10x faster                                        |
| nqueens                  | 67.0 ms                                                     | 60.8 ms: 1.10x faster                                        |
| sqlglot_normalize        | 202 ms                                                      | 184 ms: 1.10x faster                                         |
| unpickle                 | 9.17 us                                                     | 8.40 us: 1.09x faster                                        |
| create_gc_cycles         | 782 us                                                      | 717 us: 1.09x faster                                         |
| fannkuch                 | 258 ms                                                      | 238 ms: 1.08x faster                                         |
| deepcopy                 | 255 us                                                      | 237 us: 1.08x faster                                         |
| scimark_sparse_mat_mult  | 2.66 ms                                                     | 2.49 ms: 1.07x faster                                        |
| scimark_fft              | 193 ms                                                      | 181 ms: 1.06x faster                                         |
| sqlite_synth             | 1.84 us                                                     | 1.74 us: 1.05x faster                                        |
| asyncio_tcp_ssl          | 2.03 sec                                                    | 1.93 sec: 1.05x faster                                       |
| regex_effbot             | 1.66 ms                                                     | 1.58 ms: 1.05x faster                                        |
| json                     | 3.05 ms                                                     | 2.95 ms: 1.03x faster                                        |
| python_startup           | 20.0 ms                                                     | 19.4 ms: 1.03x faster                                        |
| json_loads               | 14.2 us                                                     | 13.7 us: 1.03x faster                                        |
| deepcopy_reduce          | 2.16 us                                                     | 2.13 us: 1.01x faster                                        |
| meteor_contest           | 72.5 ms                                                     | 72.2 ms: 1.01x faster                                        |
| logging_simple           | 6.20 us                                                     | 6.25 us: 1.01x slower                                        |
| pathlib                  | 77.4 ms                                                     | 78.2 ms: 1.01x slower                                        |
| pidigits                 | 145 ms                                                      | 147 ms: 1.01x slower                                         |
| nbody                    | 69.3 ms                                                     | 70.3 ms: 1.01x slower                                        |
| unpack_sequence          | 37.8 ns                                                     | 38.5 ns: 1.02x slower                                        |
| xml_etree_generate       | 54.5 ms                                                     | 55.8 ms: 1.02x slower                                        |
| unpickle_list            | 2.81 us                                                     | 2.90 us: 1.03x slower                                        |
| async_generators         | 224 ms                                                      | 233 ms: 1.04x slower                                         |
| telco                    | 3.78 ms                                                     | 4.07 ms: 1.08x slower                                        |
| python_startup_no_site   | 15.5 ms                                                     | 16.7 ms: 1.08x slower                                        |
| pickle                   | 6.80 us                                                     | 7.36 us: 1.08x slower                                        |
| pickle_list              | 2.59 us                                                     | 2.81 us: 1.09x slower                                        |
| pickle_dict              | 16.9 us                                                     | 18.4 us: 1.09x slower                                        |
| gc_traversal             | 1.34 ms                                                     | 1.47 ms: 1.10x slower                                        |
| bench_mp_pool            | 60.7 ms                                                     | 66.8 ms: 1.10x slower                                        |
| dask                     | 305 ms                                                      | 361 ms: 1.18x slower                                         |
| coverage                 | 40.0 ms                                                     | 50.3 ms: 1.26x slower                                        |
| Geometric mean           | (ref)                                                       | 1.18x faster                                                 |

Benchmark hidden because not significant (2): xml_etree_iterparse, logging_format
Ignored benchmarks (14) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120.json: chameleon, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.14x
- 95% likely to have a speedup of 1.13x
- 99% likely to have a speedup of 1.11x
