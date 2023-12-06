
# Results vs. 3.11.0

- fork: python
- ref: 3.12
- machine: windows-amd64
- commit hash: 3e20303
- commit date: 2023-08-27
- overall geometric mean: 1.06x faster
- HPT reliability: 99.95%
- HPT 99th percentile: 1.01x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230827-pythonperf1-amd64-python-3.12-3.12.0rc1+-3e20303 |
|----------------|:-----------------------------------------------------------:|:------------------------------------------------------------:|
| 2to3           | 209 ms                                                      | 214 ms: 1.03x slower                                         |
| tornado_http   | 91.8 ms                                                     | 88.4 ms: 1.04x faster                                        |
| Geometric mean | (ref)                                                       | 1.00x faster                                                 |

Benchmark hidden because not significant (1): docutils

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230827-pythonperf1-amd64-python-3.12-3.12.0rc1+-3e20303 |
|----------------|:-----------------------------------------------------------:|:------------------------------------------------------------:|
| float          | 54.6 ms                                                     | 53.8 ms: 1.01x faster                                        |
| pidigits       | 148 ms                                                      | 147 ms: 1.01x faster                                         |
| Geometric mean | (ref)                                                       | 1.01x faster                                                 |

Benchmark hidden because not significant (1): nbody

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230827-pythonperf1-amd64-python-3.12-3.12.0rc1+-3e20303 |
|----------------|:-----------------------------------------------------------:|:------------------------------------------------------------:|
| regex_v8       | 13.8 ms                                                     | 13.1 ms: 1.06x faster                                        |
| regex_compile  | 90.6 ms                                                     | 87.5 ms: 1.04x faster                                        |
| regex_dna      | 115 ms                                                      | 116 ms: 1.01x slower                                         |
| regex_effbot   | 1.50 ms                                                     | 1.58 ms: 1.06x slower                                        |
| Geometric mean | (ref)                                                       | 1.01x faster                                                 |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230827-pythonperf1-amd64-python-3.12-3.12.0rc1+-3e20303 |
|----------------------|:-----------------------------------------------------------:|:------------------------------------------------------------:|
| json_dumps           | 7.56 ms                                                     | 5.72 ms: 1.32x faster                                        |
| unpickle_pure_python | 152 us                                                      | 135 us: 1.12x faster                                         |
| xml_etree_parse      | 95.9 ms                                                     | 91.0 ms: 1.05x faster                                        |
| tomli_loads          | 1.41 sec                                                    | 1.36 sec: 1.04x faster                                       |
| pickle_pure_python   | 200 us                                                      | 195 us: 1.03x faster                                         |
| xml_etree_iterparse  | 62.6 ms                                                     | 63.5 ms: 1.01x slower                                        |
| xml_etree_process    | 37.1 ms                                                     | 37.8 ms: 1.02x slower                                        |
| unpickle             | 8.09 us                                                     | 8.40 us: 1.04x slower                                        |
| pickle_list          | 2.68 us                                                     | 2.81 us: 1.05x slower                                        |
| json_loads           | 12.9 us                                                     | 13.7 us: 1.07x slower                                        |
| xml_etree_generate   | 52.2 ms                                                     | 55.8 ms: 1.07x slower                                        |
| pickle               | 6.61 us                                                     | 7.36 us: 1.11x slower                                        |
| unpickle_list        | 2.55 us                                                     | 2.90 us: 1.14x slower                                        |
| Geometric mean       | (ref)                                                       | 1.00x faster                                                 |

Benchmark hidden because not significant (1): pickle_dict

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230827-pythonperf1-amd64-python-3.12-3.12.0rc1+-3e20303 |
|------------------------|:-----------------------------------------------------------:|:------------------------------------------------------------:|
| python_startup         | 18.7 ms                                                     | 19.4 ms: 1.04x slower                                        |
| python_startup_no_site | 15.9 ms                                                     | 16.7 ms: 1.05x slower                                        |
| Geometric mean         | (ref)                                                       | 1.04x slower                                                 |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230827-pythonperf1-amd64-python-3.12-3.12.0rc1+-3e20303 |
|-----------|:-----------------------------------------------------------:|:------------------------------------------------------------:|
| mako      | 7.26 ms                                                     | 6.90 ms: 1.05x faster                                        |

All benchmarks:
===============

| Benchmark                | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230827-pythonperf1-amd64-python-3.12-3.12.0rc1+-3e20303 |
|--------------------------|:-----------------------------------------------------------:|:------------------------------------------------------------:|
| typing_runtime_protocols | 322 us                                                      | 97.9 us: 3.29x faster                                        |
| generators               | 33.8 ms                                                     | 22.4 ms: 1.51x faster                                        |
| asyncio_tcp              | 699 ms                                                      | 481 ms: 1.45x faster                                         |
| json_dumps               | 7.56 ms                                                     | 5.72 ms: 1.32x faster                                        |
| richards_super           | 37.5 ms                                                     | 29.0 ms: 1.29x faster                                        |
| deltablue                | 2.61 ms                                                     | 2.15 ms: 1.21x faster                                        |
| unpack_sequence          | 46.1 ns                                                     | 38.5 ns: 1.20x faster                                        |
| sqlglot_parse            | 952 us                                                      | 797 us: 1.19x faster                                         |
| richards                 | 30.6 ms                                                     | 25.8 ms: 1.19x faster                                        |
| mdp                      | 1.67 sec                                                    | 1.43 sec: 1.17x faster                                       |
| logging_silent           | 69.8 ns                                                     | 60.7 ns: 1.15x faster                                        |
| sqlglot_transpile        | 1.16 ms                                                     | 1.01 ms: 1.15x faster                                        |
| unpickle_pure_python     | 152 us                                                      | 135 us: 1.12x faster                                         |
| chaos                    | 47.1 ms                                                     | 41.9 ms: 1.12x faster                                        |
| hexiom                   | 4.55 ms                                                     | 4.06 ms: 1.12x faster                                        |
| async_tree_none          | 320 ms                                                      | 287 ms: 1.12x faster                                         |
| raytrace                 | 211 ms                                                      | 189 ms: 1.12x faster                                         |
| coverage                 | 55.9 ms                                                     | 50.3 ms: 1.11x faster                                        |
| go                       | 97.3 ms                                                     | 87.7 ms: 1.11x faster                                        |
| async_tree_memoization   | 371 ms                                                      | 335 ms: 1.11x faster                                         |
| json                     | 3.25 ms                                                     | 2.95 ms: 1.10x faster                                        |
| comprehensions           | 15.9 us                                                     | 14.5 us: 1.10x faster                                        |
| mypy2                    | 229 ms                                                      | 209 ms: 1.10x faster                                         |
| asyncio_tcp_ssl          | 2.11 sec                                                    | 1.93 sec: 1.09x faster                                       |
| dulwich_log              | 44.5 ms                                                     | 40.8 ms: 1.09x faster                                        |
| scimark_lu               | 63.5 ms                                                     | 58.7 ms: 1.08x faster                                        |
| deepcopy_memo            | 25.2 us                                                     | 23.3 us: 1.08x faster                                        |
| async_tree_io            | 779 ms                                                      | 720 ms: 1.08x faster                                         |
| spectral_norm            | 67.9 ms                                                     | 63.5 ms: 1.07x faster                                        |
| nqueens                  | 64.9 ms                                                     | 60.8 ms: 1.07x faster                                        |
| fannkuch                 | 252 ms                                                      | 238 ms: 1.06x faster                                         |
| logging_simple           | 6.61 us                                                     | 6.25 us: 1.06x faster                                        |
| regex_v8                 | 13.8 ms                                                     | 13.1 ms: 1.06x faster                                        |
| xml_etree_parse          | 95.9 ms                                                     | 91.0 ms: 1.05x faster                                        |
| mako                     | 7.26 ms                                                     | 6.90 ms: 1.05x faster                                        |
| scimark_monte_carlo      | 44.6 ms                                                     | 42.5 ms: 1.05x faster                                        |
| async_tree_cpu_io_mixed  | 501 ms                                                      | 477 ms: 1.05x faster                                         |
| logging_format           | 7.01 us                                                     | 6.68 us: 1.05x faster                                        |
| aiohttp                  | 899 us                                                      | 859 us: 1.05x faster                                         |
| coroutines               | 14.6 ms                                                     | 14.0 ms: 1.04x faster                                        |
| tomli_loads              | 1.41 sec                                                    | 1.36 sec: 1.04x faster                                       |
| tornado_http             | 91.8 ms                                                     | 88.4 ms: 1.04x faster                                        |
| deepcopy                 | 246 us                                                      | 237 us: 1.04x faster                                         |
| meteor_contest           | 74.7 ms                                                     | 72.2 ms: 1.04x faster                                        |
| regex_compile            | 90.6 ms                                                     | 87.5 ms: 1.04x faster                                        |
| scimark_sparse_mat_mult  | 2.57 ms                                                     | 2.49 ms: 1.03x faster                                        |
| pyflate                  | 304 ms                                                      | 294 ms: 1.03x faster                                         |
| sqlglot_normalize        | 190 ms                                                      | 184 ms: 1.03x faster                                         |
| crypto_pyaes             | 47.6 ms                                                     | 46.4 ms: 1.03x faster                                        |
| pickle_pure_python       | 200 us                                                      | 195 us: 1.03x faster                                         |
| bench_thread_pool        | 852 us                                                      | 835 us: 1.02x faster                                         |
| float                    | 54.6 ms                                                     | 53.8 ms: 1.01x faster                                        |
| sqlglot_optimize         | 34.9 ms                                                     | 34.4 ms: 1.01x faster                                        |
| pidigits                 | 148 ms                                                      | 147 ms: 1.01x faster                                         |
| regex_dna                | 115 ms                                                      | 116 ms: 1.01x slower                                         |
| gc_traversal             | 1.46 ms                                                     | 1.47 ms: 1.01x slower                                        |
| pprint_pformat           | 1.04 sec                                                    | 1.05 sec: 1.01x slower                                       |
| xml_etree_iterparse      | 62.6 ms                                                     | 63.5 ms: 1.01x slower                                        |
| scimark_fft              | 178 ms                                                      | 181 ms: 1.02x slower                                         |
| xml_etree_process        | 37.1 ms                                                     | 37.8 ms: 1.02x slower                                        |
| 2to3                     | 209 ms                                                      | 214 ms: 1.03x slower                                         |
| deepcopy_reduce          | 2.07 us                                                     | 2.13 us: 1.03x slower                                        |
| create_gc_cycles         | 693 us                                                      | 717 us: 1.04x slower                                         |
| scimark_sor              | 75.6 ms                                                     | 78.2 ms: 1.04x slower                                        |
| python_startup           | 18.7 ms                                                     | 19.4 ms: 1.04x slower                                        |
| sqlite_synth             | 1.68 us                                                     | 1.74 us: 1.04x slower                                        |
| unpickle                 | 8.09 us                                                     | 8.40 us: 1.04x slower                                        |
| telco                    | 3.90 ms                                                     | 4.07 ms: 1.04x slower                                        |
| pickle_list              | 2.68 us                                                     | 2.81 us: 1.05x slower                                        |
| python_startup_no_site   | 15.9 ms                                                     | 16.7 ms: 1.05x slower                                        |
| regex_effbot             | 1.50 ms                                                     | 1.58 ms: 1.06x slower                                        |
| json_loads               | 12.9 us                                                     | 13.7 us: 1.07x slower                                        |
| bench_mp_pool            | 62.5 ms                                                     | 66.8 ms: 1.07x slower                                        |
| xml_etree_generate       | 52.2 ms                                                     | 55.8 ms: 1.07x slower                                        |
| pathlib                  | 71.4 ms                                                     | 78.2 ms: 1.10x slower                                        |
| pickle                   | 6.61 us                                                     | 7.36 us: 1.11x slower                                        |
| unpickle_list            | 2.55 us                                                     | 2.90 us: 1.14x slower                                        |
| async_generators         | 178 ms                                                      | 233 ms: 1.31x slower                                         |
| dask                     | 264 ms                                                      | 361 ms: 1.36x slower                                         |
| Geometric mean           | (ref)                                                       | 1.06x faster                                                 |

Benchmark hidden because not significant (5): pickle_dict, pycparser, docutils, nbody, pprint_safe_repr
Ignored benchmarks (14) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509.json: chameleon, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 99.95% likely to be faster
- 90% likely to have a speedup of 1.02x
- 95% likely to have a speedup of 1.02x
- 99% likely to have a speedup of 1.01x
