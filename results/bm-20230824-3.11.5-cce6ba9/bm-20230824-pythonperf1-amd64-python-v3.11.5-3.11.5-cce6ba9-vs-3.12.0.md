
# Results vs. 3.12.0

- fork: python
- ref: v3.11.5
- machine: windows-amd64
- commit hash: cce6ba9
- commit date: 2023-08-24
- overall geometric mean: 1.06x slower
- HPT reliability: 99.99%
- HPT 99th percentile: 1.01x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230824-pythonperf1-amd64-python-v3.11.5-3.11.5-cce6ba9 |
|----------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| 2to3           | 214 ms                                                      | 208 ms: 1.03x faster                                        |
| docutils       | 1.63 sec                                                    | 1.60 sec: 1.02x faster                                      |
| tornado_http   | 87.7 ms                                                     | 90.6 ms: 1.03x slower                                       |
| Geometric mean | (ref)                                                       | 1.00x faster                                                |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230824-pythonperf1-amd64-python-v3.11.5-3.11.5-cce6ba9 |
|----------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| nbody          | 72.6 ms                                                     | 70.1 ms: 1.04x faster                                       |
| float          | 55.1 ms                                                     | 53.9 ms: 1.02x faster                                       |
| pidigits       | 150 ms                                                      | 148 ms: 1.02x faster                                        |
| Geometric mean | (ref)                                                       | 1.03x faster                                                |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230824-pythonperf1-amd64-python-v3.11.5-3.11.5-cce6ba9 |
|----------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| regex_effbot   | 1.62 ms                                                     | 1.49 ms: 1.09x faster                                       |
| regex_dna      | 124 ms                                                      | 117 ms: 1.06x faster                                        |
| regex_v8       | 13.9 ms                                                     | 13.8 ms: 1.01x faster                                       |
| regex_compile  | 88.3 ms                                                     | 91.3 ms: 1.03x slower                                       |
| Geometric mean | (ref)                                                       | 1.03x faster                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230824-pythonperf1-amd64-python-v3.11.5-3.11.5-cce6ba9 |
|----------------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| xml_etree_generate   | 55.6 ms                                                     | 51.8 ms: 1.07x faster                                       |
| unpickle_list        | 2.78 us                                                     | 2.60 us: 1.07x faster                                       |
| pickle_dict          | 19.3 us                                                     | 18.5 us: 1.04x faster                                       |
| pickle               | 7.13 us                                                     | 6.86 us: 1.04x faster                                       |
| xml_etree_process    | 38.4 ms                                                     | 36.9 ms: 1.04x faster                                       |
| pickle_list          | 2.86 us                                                     | 2.75 us: 1.04x faster                                       |
| json_loads           | 13.4 us                                                     | 13.0 us: 1.04x faster                                       |
| unpickle             | 8.16 us                                                     | 7.92 us: 1.03x faster                                       |
| xml_etree_iterparse  | 62.5 ms                                                     | 63.4 ms: 1.01x slower                                       |
| tomli_loads          | 1.37 sec                                                    | 1.41 sec: 1.03x slower                                      |
| pickle_pure_python   | 196 us                                                      | 202 us: 1.03x slower                                        |
| xml_etree_parse      | 89.2 ms                                                     | 97.0 ms: 1.09x slower                                       |
| unpickle_pure_python | 133 us                                                      | 151 us: 1.13x slower                                        |
| json_dumps           | 5.60 ms                                                     | 7.63 ms: 1.36x slower                                       |
| Geometric mean       | (ref)                                                       | 1.02x slower                                                |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230824-pythonperf1-amd64-python-v3.11.5-3.11.5-cce6ba9 |
|------------------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| python_startup_no_site | 16.1 ms                                                     | 16.5 ms: 1.02x slower                                       |
| Geometric mean         | (ref)                                                       | 1.01x slower                                                |

Benchmark hidden because not significant (1): python_startup

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230824-pythonperf1-amd64-python-v3.11.5-3.11.5-cce6ba9 |
|-----------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| mako      | 6.93 ms                                                     | 7.44 ms: 1.07x slower                                       |

All benchmarks:
===============

| Benchmark                | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230824-pythonperf1-amd64-python-v3.11.5-3.11.5-cce6ba9 |
|--------------------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| async_generators         | 235 ms                                                      | 180 ms: 1.31x faster                                        |
| pathlib                  | 77.1 ms                                                     | 69.7 ms: 1.11x faster                                       |
| regex_effbot             | 1.62 ms                                                     | 1.49 ms: 1.09x faster                                       |
| bench_mp_pool            | 66.4 ms                                                     | 61.5 ms: 1.08x faster                                       |
| xml_etree_generate       | 55.6 ms                                                     | 51.8 ms: 1.07x faster                                       |
| unpickle_list            | 2.78 us                                                     | 2.60 us: 1.07x faster                                       |
| regex_dna                | 124 ms                                                      | 117 ms: 1.06x faster                                        |
| pickle_dict              | 19.3 us                                                     | 18.5 us: 1.04x faster                                       |
| pickle                   | 7.13 us                                                     | 6.86 us: 1.04x faster                                       |
| scimark_sor              | 79.6 ms                                                     | 76.5 ms: 1.04x faster                                       |
| xml_etree_process        | 38.4 ms                                                     | 36.9 ms: 1.04x faster                                       |
| pickle_list              | 2.86 us                                                     | 2.75 us: 1.04x faster                                       |
| nbody                    | 72.6 ms                                                     | 70.1 ms: 1.04x faster                                       |
| json_loads               | 13.4 us                                                     | 13.0 us: 1.04x faster                                       |
| deepcopy_reduce          | 2.13 us                                                     | 2.06 us: 1.04x faster                                       |
| telco                    | 4.09 ms                                                     | 3.96 ms: 1.03x faster                                       |
| unpickle                 | 8.16 us                                                     | 7.92 us: 1.03x faster                                       |
| 2to3                     | 214 ms                                                      | 208 ms: 1.03x faster                                        |
| create_gc_cycles         | 727 us                                                      | 709 us: 1.02x faster                                        |
| float                    | 55.1 ms                                                     | 53.9 ms: 1.02x faster                                       |
| sqlite_synth             | 1.76 us                                                     | 1.72 us: 1.02x faster                                       |
| docutils                 | 1.63 sec                                                    | 1.60 sec: 1.02x faster                                      |
| pidigits                 | 150 ms                                                      | 148 ms: 1.02x faster                                        |
| aiohttp                  | 865 us                                                      | 853 us: 1.01x faster                                        |
| regex_v8                 | 13.9 ms                                                     | 13.8 ms: 1.01x faster                                       |
| sqlglot_optimize         | 34.4 ms                                                     | 34.5 ms: 1.00x slower                                       |
| pprint_pformat           | 1.04 sec                                                    | 1.05 sec: 1.01x slower                                      |
| scimark_fft              | 180 ms                                                      | 181 ms: 1.01x slower                                        |
| xml_etree_iterparse      | 62.5 ms                                                     | 63.4 ms: 1.01x slower                                       |
| crypto_pyaes             | 47.4 ms                                                     | 48.1 ms: 1.01x slower                                       |
| nqueens                  | 61.2 ms                                                     | 62.3 ms: 1.02x slower                                       |
| pyflate                  | 297 ms                                                      | 302 ms: 1.02x slower                                        |
| dask                     | 259 ms                                                      | 265 ms: 1.02x slower                                        |
| python_startup_no_site   | 16.1 ms                                                     | 16.5 ms: 1.02x slower                                       |
| bench_thread_pool        | 844 us                                                      | 863 us: 1.02x slower                                        |
| sqlglot_normalize        | 185 ms                                                      | 190 ms: 1.03x slower                                        |
| tomli_loads              | 1.37 sec                                                    | 1.41 sec: 1.03x slower                                      |
| dulwich_log              | 42.4 ms                                                     | 43.6 ms: 1.03x slower                                       |
| pickle_pure_python       | 196 us                                                      | 202 us: 1.03x slower                                        |
| tornado_http             | 87.7 ms                                                     | 90.6 ms: 1.03x slower                                       |
| regex_compile            | 88.3 ms                                                     | 91.3 ms: 1.03x slower                                       |
| coroutines               | 14.0 ms                                                     | 14.5 ms: 1.04x slower                                       |
| pycparser                | 673 ms                                                      | 699 ms: 1.04x slower                                        |
| scimark_sparse_mat_mult  | 2.48 ms                                                     | 2.57 ms: 1.04x slower                                       |
| deepcopy_memo            | 23.8 us                                                     | 24.7 us: 1.04x slower                                       |
| asyncio_tcp_ssl          | 1.96 sec                                                    | 2.05 sec: 1.05x slower                                      |
| meteor_contest           | 73.1 ms                                                     | 76.8 ms: 1.05x slower                                       |
| coverage                 | 51.5 ms                                                     | 54.3 ms: 1.06x slower                                       |
| logging_simple           | 6.21 us                                                     | 6.56 us: 1.06x slower                                       |
| async_tree_none          | 294 ms                                                      | 311 ms: 1.06x slower                                        |
| logging_format           | 6.67 us                                                     | 7.06 us: 1.06x slower                                       |
| raytrace                 | 191 ms                                                      | 203 ms: 1.06x slower                                        |
| scimark_monte_carlo      | 43.7 ms                                                     | 46.5 ms: 1.07x slower                                       |
| spectral_norm            | 63.2 ms                                                     | 67.5 ms: 1.07x slower                                       |
| json                     | 2.86 ms                                                     | 3.07 ms: 1.07x slower                                       |
| mako                     | 6.93 ms                                                     | 7.44 ms: 1.07x slower                                       |
| scimark_lu               | 58.1 ms                                                     | 62.7 ms: 1.08x slower                                       |
| async_tree_cpu_io_mixed  | 479 ms                                                      | 516 ms: 1.08x slower                                        |
| async_tree_io            | 720 ms                                                      | 779 ms: 1.08x slower                                        |
| xml_etree_parse          | 89.2 ms                                                     | 97.0 ms: 1.09x slower                                       |
| sqlglot_transpile        | 1.04 ms                                                     | 1.13 ms: 1.09x slower                                       |
| go                       | 88.5 ms                                                     | 98.8 ms: 1.12x slower                                       |
| async_tree_memoization   | 336 ms                                                      | 375 ms: 1.12x slower                                        |
| richards                 | 26.9 ms                                                     | 30.1 ms: 1.12x slower                                       |
| comprehensions           | 14.1 us                                                     | 15.9 us: 1.13x slower                                       |
| mdp                      | 1.44 sec                                                    | 1.63 sec: 1.13x slower                                      |
| hexiom                   | 4.03 ms                                                     | 4.55 ms: 1.13x slower                                       |
| sqlglot_parse            | 820 us                                                      | 928 us: 1.13x slower                                        |
| fannkuch                 | 237 ms                                                      | 268 ms: 1.13x slower                                        |
| unpickle_pure_python     | 133 us                                                      | 151 us: 1.13x slower                                        |
| logging_silent           | 60.6 ns                                                     | 70.0 ns: 1.16x slower                                       |
| chaos                    | 42.8 ms                                                     | 49.5 ms: 1.16x slower                                       |
| unpack_sequence          | 37.5 ns                                                     | 45.5 ns: 1.21x slower                                       |
| deltablue                | 2.14 ms                                                     | 2.61 ms: 1.22x slower                                       |
| richards_super           | 30.5 ms                                                     | 38.0 ms: 1.25x slower                                       |
| mypy2                    | 207 ms                                                      | 275 ms: 1.33x slower                                        |
| json_dumps               | 5.60 ms                                                     | 7.63 ms: 1.36x slower                                       |
| asyncio_tcp              | 472 ms                                                      | 694 ms: 1.47x slower                                        |
| generators               | 22.7 ms                                                     | 33.8 ms: 1.49x slower                                       |
| typing_runtime_protocols | 95.2 us                                                     | 327 us: 3.44x slower                                        |
| Geometric mean           | (ref)                                                       | 1.06x slower                                                |

Benchmark hidden because not significant (4): gc_traversal, python_startup, pprint_safe_repr, deepcopy
Ignored benchmarks (14) of results/bm-20230824-3.11.5-cce6ba9/bm-20230824-pythonperf1-amd64-python-v3.11.5-3.11.5-cce6ba9.json: chameleon, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 99.99% likely to be slow
- 90% likely to have a slowdown of 1.02x
- 95% likely to have a slowdown of 1.01x
- 99% likely to have a slowdown of 1.01x
