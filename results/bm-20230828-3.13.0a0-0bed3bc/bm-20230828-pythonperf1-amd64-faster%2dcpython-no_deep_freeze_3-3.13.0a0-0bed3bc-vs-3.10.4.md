
# Results vs. 3.10.4

- fork: faster-cpython
- ref: no_deep_freeze_3
- machine: windows-amd64
- commit hash: 0bed3bc
- commit date: 2023-08-28
- overall geometric mean: 1.15x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.08x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230828-pythonperf1-amd64-faster%2dcpython-no_deep_freeze_3-3.13.0a0-0bed3bc |
|----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| docutils       | 1.89 sec                                                    | 1.60 sec: 1.18x faster                                                           |
| tornado_http   | 109 ms                                                      | 87.5 ms: 1.25x faster                                                            |
| Geometric mean | (ref)                                                       | 1.21x faster                                                                     |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230828-pythonperf1-amd64-faster%2dcpython-no_deep_freeze_3-3.13.0a0-0bed3bc |
|----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| float          | 60.2 ms                                                     | 54.9 ms: 1.10x faster                                                            |
| pidigits       | 145 ms                                                      | 151 ms: 1.04x slower                                                             |
| nbody          | 69.3 ms                                                     | 75.4 ms: 1.09x slower                                                            |
| Geometric mean | (ref)                                                       | 1.01x slower                                                                     |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230828-pythonperf1-amd64-faster%2dcpython-no_deep_freeze_3-3.13.0a0-0bed3bc |
|----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| regex_compile  | 103 ms                                                      | 90.1 ms: 1.15x faster                                                            |
| regex_dna      | 132 ms                                                      | 118 ms: 1.11x faster                                                             |
| regex_effbot   | 1.66 ms                                                     | 1.59 ms: 1.05x faster                                                            |
| regex_v8       | 15.0 ms                                                     | 14.6 ms: 1.03x faster                                                            |
| Geometric mean | (ref)                                                       | 1.08x faster                                                                     |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230828-pythonperf1-amd64-faster%2dcpython-no_deep_freeze_3-3.13.0a0-0bed3bc |
|----------------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| json_dumps           | 8.50 ms                                                     | 5.72 ms: 1.49x faster                                                            |
| pickle_pure_python   | 257 us                                                      | 195 us: 1.32x faster                                                             |
| unpickle_pure_python | 171 us                                                      | 141 us: 1.22x faster                                                             |
| unpickle             | 9.17 us                                                     | 8.12 us: 1.13x faster                                                            |
| xml_etree_process    | 43.4 ms                                                     | 38.7 ms: 1.12x faster                                                            |
| xml_etree_parse      | 102 ms                                                      | 91.4 ms: 1.11x faster                                                            |
| tomli_loads          | 1.62 sec                                                    | 1.49 sec: 1.09x faster                                                           |
| json_loads           | 14.2 us                                                     | 13.6 us: 1.04x faster                                                            |
| xml_etree_iterparse  | 63.5 ms                                                     | 64.6 ms: 1.02x slower                                                            |
| unpickle_list        | 2.81 us                                                     | 2.93 us: 1.04x slower                                                            |
| xml_etree_generate   | 54.5 ms                                                     | 56.8 ms: 1.04x slower                                                            |
| pickle               | 6.80 us                                                     | 7.34 us: 1.08x slower                                                            |
| pickle_dict          | 16.9 us                                                     | 18.3 us: 1.08x slower                                                            |
| pickle_list          | 2.59 us                                                     | 2.80 us: 1.08x slower                                                            |
| Geometric mean       | (ref)                                                       | 1.08x faster                                                                     |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230828-pythonperf1-amd64-faster%2dcpython-no_deep_freeze_3-3.13.0a0-0bed3bc |
|------------------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| python_startup         | 20.0 ms                                                     | 19.8 ms: 1.01x faster                                                            |
| python_startup_no_site | 15.5 ms                                                     | 16.2 ms: 1.04x slower                                                            |
| Geometric mean         | (ref)                                                       | 1.02x slower                                                                     |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230828-pythonperf1-amd64-faster%2dcpython-no_deep_freeze_3-3.13.0a0-0bed3bc |
|-----------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| mako      | 8.80 ms                                                     | 7.57 ms: 1.16x faster                                                            |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230828-pythonperf1-amd64-faster%2dcpython-no_deep_freeze_3-3.13.0a0-0bed3bc |
|--------------------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| typing_runtime_protocols | 325 us                                                      | 94.4 us: 3.44x faster                                                            |
| deltablue                | 4.17 ms                                                     | 2.24 ms: 1.86x faster                                                            |
| mypy2                    | 352 ms                                                      | 214 ms: 1.64x faster                                                             |
| richards_super           | 51.7 ms                                                     | 32.6 ms: 1.59x faster                                                            |
| async_tree_none          | 420 ms                                                      | 267 ms: 1.57x faster                                                             |
| raytrace                 | 271 ms                                                      | 177 ms: 1.53x faster                                                             |
| logging_silent           | 96.4 ns                                                     | 64.0 ns: 1.51x faster                                                            |
| asyncio_tcp              | 712 ms                                                      | 477 ms: 1.49x faster                                                             |
| json_dumps               | 8.50 ms                                                     | 5.72 ms: 1.49x faster                                                            |
| sqlglot_parse            | 1.22 ms                                                     | 823 us: 1.48x faster                                                             |
| async_tree_io            | 1.07 sec                                                    | 725 ms: 1.47x faster                                                             |
| go                       | 136 ms                                                      | 92.9 ms: 1.47x faster                                                            |
| async_tree_memoization   | 497 ms                                                      | 346 ms: 1.44x faster                                                             |
| richards                 | 41.2 ms                                                     | 29.1 ms: 1.41x faster                                                            |
| chaos                    | 58.9 ms                                                     | 41.7 ms: 1.41x faster                                                            |
| scimark_lu               | 85.4 ms                                                     | 60.6 ms: 1.41x faster                                                            |
| sqlglot_transpile        | 1.46 ms                                                     | 1.04 ms: 1.40x faster                                                            |
| crypto_pyaes             | 62.3 ms                                                     | 46.0 ms: 1.36x faster                                                            |
| pickle_pure_python       | 257 us                                                      | 195 us: 1.32x faster                                                             |
| generators               | 31.6 ms                                                     | 24.1 ms: 1.31x faster                                                            |
| async_tree_cpu_io_mixed  | 609 ms                                                      | 474 ms: 1.28x faster                                                             |
| hexiom                   | 5.52 ms                                                     | 4.30 ms: 1.28x faster                                                            |
| pyflate                  | 387 ms                                                      | 307 ms: 1.26x faster                                                             |
| tornado_http             | 109 ms                                                      | 87.5 ms: 1.25x faster                                                            |
| scimark_monte_carlo      | 55.9 ms                                                     | 45.1 ms: 1.24x faster                                                            |
| scimark_sor              | 105 ms                                                      | 85.2 ms: 1.23x faster                                                            |
| unpickle_pure_python     | 171 us                                                      | 141 us: 1.22x faster                                                             |
| pycparser                | 868 ms                                                      | 722 ms: 1.20x faster                                                             |
| docutils                 | 1.89 sec                                                    | 1.60 sec: 1.18x faster                                                           |
| spectral_norm            | 78.0 ms                                                     | 66.7 ms: 1.17x faster                                                            |
| mako                     | 8.80 ms                                                     | 7.57 ms: 1.16x faster                                                            |
| regex_compile            | 103 ms                                                      | 90.1 ms: 1.15x faster                                                            |
| deepcopy_memo            | 28.5 us                                                     | 25.0 us: 1.14x faster                                                            |
| mdp                      | 1.71 sec                                                    | 1.51 sec: 1.13x faster                                                           |
| unpickle                 | 9.17 us                                                     | 8.12 us: 1.13x faster                                                            |
| xml_etree_process        | 43.4 ms                                                     | 38.7 ms: 1.12x faster                                                            |
| bench_thread_pool        | 946 us                                                      | 844 us: 1.12x faster                                                             |
| sqlglot_optimize         | 39.0 ms                                                     | 34.9 ms: 1.12x faster                                                            |
| regex_dna                | 132 ms                                                      | 118 ms: 1.11x faster                                                             |
| xml_etree_parse          | 102 ms                                                      | 91.4 ms: 1.11x faster                                                            |
| pprint_pformat           | 1.21 sec                                                    | 1.10 sec: 1.10x faster                                                           |
| float                    | 60.2 ms                                                     | 54.9 ms: 1.10x faster                                                            |
| pprint_safe_repr         | 589 ms                                                      | 537 ms: 1.10x faster                                                             |
| asyncio_tcp_ssl          | 2.03 sec                                                    | 1.86 sec: 1.09x faster                                                           |
| comprehensions           | 16.0 us                                                     | 14.6 us: 1.09x faster                                                            |
| tomli_loads              | 1.62 sec                                                    | 1.49 sec: 1.09x faster                                                           |
| create_gc_cycles         | 782 us                                                      | 720 us: 1.09x faster                                                             |
| nqueens                  | 67.0 ms                                                     | 61.9 ms: 1.08x faster                                                            |
| sqlglot_normalize        | 202 ms                                                      | 188 ms: 1.08x faster                                                             |
| coroutines               | 15.9 ms                                                     | 15.0 ms: 1.06x faster                                                            |
| scimark_sparse_mat_mult  | 2.66 ms                                                     | 2.50 ms: 1.06x faster                                                            |
| deepcopy                 | 255 us                                                      | 241 us: 1.06x faster                                                             |
| dulwich_log              | 47.6 ms                                                     | 45.1 ms: 1.06x faster                                                            |
| regex_effbot             | 1.66 ms                                                     | 1.59 ms: 1.05x faster                                                            |
| scimark_fft              | 193 ms                                                      | 185 ms: 1.04x faster                                                             |
| json_loads               | 14.2 us                                                     | 13.6 us: 1.04x faster                                                            |
| sqlite_synth             | 1.84 us                                                     | 1.76 us: 1.04x faster                                                            |
| regex_v8                 | 15.0 ms                                                     | 14.6 ms: 1.03x faster                                                            |
| python_startup           | 20.0 ms                                                     | 19.8 ms: 1.01x faster                                                            |
| logging_format           | 6.66 us                                                     | 6.71 us: 1.01x slower                                                            |
| meteor_contest           | 72.5 ms                                                     | 73.2 ms: 1.01x slower                                                            |
| fannkuch                 | 258 ms                                                      | 261 ms: 1.01x slower                                                             |
| logging_simple           | 6.20 us                                                     | 6.30 us: 1.02x slower                                                            |
| xml_etree_iterparse      | 63.5 ms                                                     | 64.6 ms: 1.02x slower                                                            |
| unpack_sequence          | 37.8 ns                                                     | 38.5 ns: 1.02x slower                                                            |
| pathlib                  | 77.4 ms                                                     | 79.2 ms: 1.02x slower                                                            |
| pidigits                 | 145 ms                                                      | 151 ms: 1.04x slower                                                             |
| unpickle_list            | 2.81 us                                                     | 2.93 us: 1.04x slower                                                            |
| xml_etree_generate       | 54.5 ms                                                     | 56.8 ms: 1.04x slower                                                            |
| python_startup_no_site   | 15.5 ms                                                     | 16.2 ms: 1.04x slower                                                            |
| pickle                   | 6.80 us                                                     | 7.34 us: 1.08x slower                                                            |
| async_generators         | 224 ms                                                      | 241 ms: 1.08x slower                                                             |
| pickle_dict              | 16.9 us                                                     | 18.3 us: 1.08x slower                                                            |
| pickle_list              | 2.59 us                                                     | 2.80 us: 1.08x slower                                                            |
| nbody                    | 69.3 ms                                                     | 75.4 ms: 1.09x slower                                                            |
| bench_mp_pool            | 60.7 ms                                                     | 67.4 ms: 1.11x slower                                                            |
| gc_traversal             | 1.34 ms                                                     | 1.49 ms: 1.11x slower                                                            |
| coverage                 | 40.0 ms                                                     | 45.7 ms: 1.14x slower                                                            |
| dask                     | 305 ms                                                      | 372 ms: 1.22x slower                                                             |
| telco                    | 3.78 ms                                                     | 4.65 ms: 1.23x slower                                                            |
| Geometric mean           | (ref)                                                       | 1.15x faster                                                                     |

Benchmark hidden because not significant (2): deepcopy_reduce, json
Ignored benchmarks (16) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120.json: 2to3, aiohttp, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.09x
- 95% likely to have a speedup of 1.09x
- 99% likely to have a speedup of 1.08x
