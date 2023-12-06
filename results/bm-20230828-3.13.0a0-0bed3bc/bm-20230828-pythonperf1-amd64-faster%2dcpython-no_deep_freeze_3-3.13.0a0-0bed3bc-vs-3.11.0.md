
# Results vs. 3.11.0

- fork: faster-cpython
- ref: no_deep_freeze_3
- machine: windows-amd64
- commit hash: 0bed3bc
- commit date: 2023-08-28
- overall geometric mean: 1.03x faster
- HPT reliability: 72.22%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230828-pythonperf1-amd64-faster%2dcpython-no_deep_freeze_3-3.13.0a0-0bed3bc |
|----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| tornado_http   | 91.8 ms                                                     | 87.5 ms: 1.05x faster                                                            |
| Geometric mean | (ref)                                                       | 1.02x faster                                                                     |

Benchmark hidden because not significant (1): docutils

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230828-pythonperf1-amd64-faster%2dcpython-no_deep_freeze_3-3.13.0a0-0bed3bc |
|----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| pidigits       | 148 ms                                                      | 151 ms: 1.02x slower                                                             |
| nbody          | 70.0 ms                                                     | 75.4 ms: 1.08x slower                                                            |
| Geometric mean | (ref)                                                       | 1.03x slower                                                                     |

Benchmark hidden because not significant (1): float

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230828-pythonperf1-amd64-faster%2dcpython-no_deep_freeze_3-3.13.0a0-0bed3bc |
|----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| regex_compile  | 90.6 ms                                                     | 90.1 ms: 1.01x faster                                                            |
| regex_dna      | 115 ms                                                      | 118 ms: 1.03x slower                                                             |
| regex_v8       | 13.8 ms                                                     | 14.6 ms: 1.06x slower                                                            |
| regex_effbot   | 1.50 ms                                                     | 1.59 ms: 1.06x slower                                                            |
| Geometric mean | (ref)                                                       | 1.03x slower                                                                     |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230828-pythonperf1-amd64-faster%2dcpython-no_deep_freeze_3-3.13.0a0-0bed3bc |
|----------------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| json_dumps           | 7.56 ms                                                     | 5.72 ms: 1.32x faster                                                            |
| unpickle_pure_python | 152 us                                                      | 141 us: 1.08x faster                                                             |
| xml_etree_parse      | 95.9 ms                                                     | 91.4 ms: 1.05x faster                                                            |
| pickle_pure_python   | 200 us                                                      | 195 us: 1.03x faster                                                             |
| xml_etree_iterparse  | 62.6 ms                                                     | 64.6 ms: 1.03x slower                                                            |
| xml_etree_process    | 37.1 ms                                                     | 38.7 ms: 1.04x slower                                                            |
| pickle_list          | 2.68 us                                                     | 2.80 us: 1.04x slower                                                            |
| tomli_loads          | 1.41 sec                                                    | 1.49 sec: 1.05x slower                                                           |
| json_loads           | 12.9 us                                                     | 13.6 us: 1.05x slower                                                            |
| xml_etree_generate   | 52.2 ms                                                     | 56.8 ms: 1.09x slower                                                            |
| pickle               | 6.61 us                                                     | 7.34 us: 1.11x slower                                                            |
| unpickle_list        | 2.55 us                                                     | 2.93 us: 1.15x slower                                                            |
| Geometric mean       | (ref)                                                       | 1.01x slower                                                                     |

Benchmark hidden because not significant (2): pickle_dict, unpickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230828-pythonperf1-amd64-faster%2dcpython-no_deep_freeze_3-3.13.0a0-0bed3bc |
|------------------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| python_startup_no_site | 15.9 ms                                                     | 16.2 ms: 1.02x slower                                                            |
| python_startup         | 18.7 ms                                                     | 19.8 ms: 1.06x slower                                                            |
| Geometric mean         | (ref)                                                       | 1.04x slower                                                                     |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230828-pythonperf1-amd64-faster%2dcpython-no_deep_freeze_3-3.13.0a0-0bed3bc |
|-----------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| mako      | 7.26 ms                                                     | 7.57 ms: 1.04x slower                                                            |

All benchmarks:
===============

| Benchmark                | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230828-pythonperf1-amd64-faster%2dcpython-no_deep_freeze_3-3.13.0a0-0bed3bc |
|--------------------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| typing_runtime_protocols | 322 us                                                      | 94.4 us: 3.41x faster                                                            |
| asyncio_tcp              | 699 ms                                                      | 477 ms: 1.47x faster                                                             |
| generators               | 33.8 ms                                                     | 24.1 ms: 1.40x faster                                                            |
| json_dumps               | 7.56 ms                                                     | 5.72 ms: 1.32x faster                                                            |
| coverage                 | 55.9 ms                                                     | 45.7 ms: 1.22x faster                                                            |
| async_tree_none          | 320 ms                                                      | 267 ms: 1.20x faster                                                             |
| unpack_sequence          | 46.1 ns                                                     | 38.5 ns: 1.20x faster                                                            |
| raytrace                 | 211 ms                                                      | 177 ms: 1.19x faster                                                             |
| deltablue                | 2.61 ms                                                     | 2.24 ms: 1.16x faster                                                            |
| sqlglot_parse            | 952 us                                                      | 823 us: 1.16x faster                                                             |
| richards_super           | 37.5 ms                                                     | 32.6 ms: 1.15x faster                                                            |
| asyncio_tcp_ssl          | 2.11 sec                                                    | 1.86 sec: 1.13x faster                                                           |
| chaos                    | 47.1 ms                                                     | 41.7 ms: 1.13x faster                                                            |
| sqlglot_transpile        | 1.16 ms                                                     | 1.04 ms: 1.12x faster                                                            |
| mdp                      | 1.67 sec                                                    | 1.51 sec: 1.10x faster                                                           |
| logging_silent           | 69.8 ns                                                     | 64.0 ns: 1.09x faster                                                            |
| comprehensions           | 15.9 us                                                     | 14.6 us: 1.09x faster                                                            |
| unpickle_pure_python     | 152 us                                                      | 141 us: 1.08x faster                                                             |
| async_tree_io            | 779 ms                                                      | 725 ms: 1.07x faster                                                             |
| async_tree_memoization   | 371 ms                                                      | 346 ms: 1.07x faster                                                             |
| mypy2                    | 229 ms                                                      | 214 ms: 1.07x faster                                                             |
| hexiom                   | 4.55 ms                                                     | 4.30 ms: 1.06x faster                                                            |
| async_tree_cpu_io_mixed  | 501 ms                                                      | 474 ms: 1.06x faster                                                             |
| richards                 | 30.6 ms                                                     | 29.1 ms: 1.05x faster                                                            |
| logging_simple           | 6.61 us                                                     | 6.30 us: 1.05x faster                                                            |
| xml_etree_parse          | 95.9 ms                                                     | 91.4 ms: 1.05x faster                                                            |
| tornado_http             | 91.8 ms                                                     | 87.5 ms: 1.05x faster                                                            |
| scimark_lu               | 63.5 ms                                                     | 60.6 ms: 1.05x faster                                                            |
| nqueens                  | 64.9 ms                                                     | 61.9 ms: 1.05x faster                                                            |
| go                       | 97.3 ms                                                     | 92.9 ms: 1.05x faster                                                            |
| logging_format           | 7.01 us                                                     | 6.71 us: 1.04x faster                                                            |
| crypto_pyaes             | 47.6 ms                                                     | 46.0 ms: 1.03x faster                                                            |
| pickle_pure_python       | 200 us                                                      | 195 us: 1.03x faster                                                             |
| scimark_sparse_mat_mult  | 2.57 ms                                                     | 2.50 ms: 1.03x faster                                                            |
| meteor_contest           | 74.7 ms                                                     | 73.2 ms: 1.02x faster                                                            |
| deepcopy                 | 246 us                                                      | 241 us: 1.02x faster                                                             |
| spectral_norm            | 67.9 ms                                                     | 66.7 ms: 1.02x faster                                                            |
| sqlglot_normalize        | 190 ms                                                      | 188 ms: 1.01x faster                                                             |
| regex_compile            | 90.6 ms                                                     | 90.1 ms: 1.01x faster                                                            |
| scimark_monte_carlo      | 44.6 ms                                                     | 45.1 ms: 1.01x slower                                                            |
| pyflate                  | 304 ms                                                      | 307 ms: 1.01x slower                                                             |
| dulwich_log              | 44.5 ms                                                     | 45.1 ms: 1.01x slower                                                            |
| pidigits                 | 148 ms                                                      | 151 ms: 1.02x slower                                                             |
| python_startup_no_site   | 15.9 ms                                                     | 16.2 ms: 1.02x slower                                                            |
| coroutines               | 14.6 ms                                                     | 15.0 ms: 1.02x slower                                                            |
| gc_traversal             | 1.46 ms                                                     | 1.49 ms: 1.03x slower                                                            |
| regex_dna                | 115 ms                                                      | 118 ms: 1.03x slower                                                             |
| xml_etree_iterparse      | 62.6 ms                                                     | 64.6 ms: 1.03x slower                                                            |
| fannkuch                 | 252 ms                                                      | 261 ms: 1.03x slower                                                             |
| scimark_fft              | 178 ms                                                      | 185 ms: 1.04x slower                                                             |
| create_gc_cycles         | 693 us                                                      | 720 us: 1.04x slower                                                             |
| deepcopy_reduce          | 2.07 us                                                     | 2.16 us: 1.04x slower                                                            |
| mako                     | 7.26 ms                                                     | 7.57 ms: 1.04x slower                                                            |
| xml_etree_process        | 37.1 ms                                                     | 38.7 ms: 1.04x slower                                                            |
| pycparser                | 691 ms                                                      | 722 ms: 1.04x slower                                                             |
| pickle_list              | 2.68 us                                                     | 2.80 us: 1.04x slower                                                            |
| sqlite_synth             | 1.68 us                                                     | 1.76 us: 1.05x slower                                                            |
| pprint_safe_repr         | 512 ms                                                      | 537 ms: 1.05x slower                                                             |
| tomli_loads              | 1.41 sec                                                    | 1.49 sec: 1.05x slower                                                           |
| json_loads               | 12.9 us                                                     | 13.6 us: 1.05x slower                                                            |
| pprint_pformat           | 1.04 sec                                                    | 1.10 sec: 1.06x slower                                                           |
| regex_v8                 | 13.8 ms                                                     | 14.6 ms: 1.06x slower                                                            |
| python_startup           | 18.7 ms                                                     | 19.8 ms: 1.06x slower                                                            |
| regex_effbot             | 1.50 ms                                                     | 1.59 ms: 1.06x slower                                                            |
| nbody                    | 70.0 ms                                                     | 75.4 ms: 1.08x slower                                                            |
| bench_mp_pool            | 62.5 ms                                                     | 67.4 ms: 1.08x slower                                                            |
| xml_etree_generate       | 52.2 ms                                                     | 56.8 ms: 1.09x slower                                                            |
| pathlib                  | 71.4 ms                                                     | 79.2 ms: 1.11x slower                                                            |
| pickle                   | 6.61 us                                                     | 7.34 us: 1.11x slower                                                            |
| scimark_sor              | 75.6 ms                                                     | 85.2 ms: 1.13x slower                                                            |
| unpickle_list            | 2.55 us                                                     | 2.93 us: 1.15x slower                                                            |
| telco                    | 3.90 ms                                                     | 4.65 ms: 1.19x slower                                                            |
| async_generators         | 178 ms                                                      | 241 ms: 1.36x slower                                                             |
| dask                     | 264 ms                                                      | 372 ms: 1.41x slower                                                             |
| Geometric mean           | (ref)                                                       | 1.03x faster                                                                     |

Benchmark hidden because not significant (8): json, pickle_dict, bench_thread_pool, deepcopy_memo, sqlglot_optimize, docutils, unpickle, float
Ignored benchmarks (16) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509.json: 2to3, aiohttp, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 72.22% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
