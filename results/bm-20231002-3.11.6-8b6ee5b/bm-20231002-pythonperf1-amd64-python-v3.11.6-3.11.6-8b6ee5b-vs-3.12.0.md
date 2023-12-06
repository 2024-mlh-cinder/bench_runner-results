
# Results vs. 3.12.0

- fork: python
- ref: v3.11.6
- machine: windows-amd64
- commit hash: 8b6ee5b
- commit date: 2023-10-02
- overall geometric mean: 1.06x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.01x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231002-pythonperf1-amd64-python-v3.11.6-3.11.6-8b6ee5b |
|----------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| 2to3           | 214 ms                                                      | 207 ms: 1.03x faster                                        |
| docutils       | 1.63 sec                                                    | 1.60 sec: 1.02x faster                                      |
| tornado_http   | 87.7 ms                                                     | 90.5 ms: 1.03x slower                                       |
| Geometric mean | (ref)                                                       | 1.01x faster                                                |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231002-pythonperf1-amd64-python-v3.11.6-3.11.6-8b6ee5b |
|----------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| nbody          | 72.6 ms                                                     | 69.7 ms: 1.04x faster                                       |
| float          | 55.1 ms                                                     | 54.3 ms: 1.02x faster                                       |
| pidigits       | 150 ms                                                      | 148 ms: 1.01x faster                                        |
| Geometric mean | (ref)                                                       | 1.02x faster                                                |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231002-pythonperf1-amd64-python-v3.11.6-3.11.6-8b6ee5b |
|----------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| regex_effbot   | 1.62 ms                                                     | 1.53 ms: 1.06x faster                                       |
| regex_dna      | 124 ms                                                      | 122 ms: 1.02x faster                                        |
| regex_v8       | 13.9 ms                                                     | 14.2 ms: 1.02x slower                                       |
| regex_compile  | 88.3 ms                                                     | 91.7 ms: 1.04x slower                                       |
| Geometric mean | (ref)                                                       | 1.00x faster                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231002-pythonperf1-amd64-python-v3.11.6-3.11.6-8b6ee5b |
|----------------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| pickle               | 7.13 us                                                     | 6.67 us: 1.07x faster                                       |
| unpickle             | 8.16 us                                                     | 7.67 us: 1.06x faster                                       |
| pickle_list          | 2.86 us                                                     | 2.70 us: 1.06x faster                                       |
| unpickle_list        | 2.78 us                                                     | 2.64 us: 1.05x faster                                       |
| xml_etree_generate   | 55.6 ms                                                     | 52.9 ms: 1.05x faster                                       |
| pickle_dict          | 19.3 us                                                     | 18.4 us: 1.04x faster                                       |
| json_loads           | 13.4 us                                                     | 13.2 us: 1.02x faster                                       |
| xml_etree_process    | 38.4 ms                                                     | 37.8 ms: 1.02x faster                                       |
| xml_etree_iterparse  | 62.5 ms                                                     | 63.3 ms: 1.01x slower                                       |
| tomli_loads          | 1.37 sec                                                    | 1.42 sec: 1.03x slower                                      |
| pickle_pure_python   | 196 us                                                      | 203 us: 1.04x slower                                        |
| xml_etree_parse      | 89.2 ms                                                     | 97.3 ms: 1.09x slower                                       |
| unpickle_pure_python | 133 us                                                      | 151 us: 1.13x slower                                        |
| json_dumps           | 5.60 ms                                                     | 7.74 ms: 1.38x slower                                       |
| Geometric mean       | (ref)                                                       | 1.02x slower                                                |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231002-pythonperf1-amd64-python-v3.11.6-3.11.6-8b6ee5b |
|------------------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| python_startup         | 19.5 ms                                                     | 18.6 ms: 1.05x faster                                       |
| python_startup_no_site | 16.1 ms                                                     | 15.6 ms: 1.04x faster                                       |
| Geometric mean         | (ref)                                                       | 1.04x faster                                                |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231002-pythonperf1-amd64-python-v3.11.6-3.11.6-8b6ee5b |
|-----------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| mako      | 6.93 ms                                                     | 7.31 ms: 1.05x slower                                       |

All benchmarks:
===============

| Benchmark                | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231002-pythonperf1-amd64-python-v3.11.6-3.11.6-8b6ee5b |
|--------------------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| async_generators         | 235 ms                                                      | 179 ms: 1.32x faster                                        |
| bench_mp_pool            | 66.4 ms                                                     | 58.7 ms: 1.13x faster                                       |
| pathlib                  | 77.1 ms                                                     | 68.5 ms: 1.13x faster                                       |
| pickle                   | 7.13 us                                                     | 6.67 us: 1.07x faster                                       |
| unpickle                 | 8.16 us                                                     | 7.67 us: 1.06x faster                                       |
| regex_effbot             | 1.62 ms                                                     | 1.53 ms: 1.06x faster                                       |
| pickle_list              | 2.86 us                                                     | 2.70 us: 1.06x faster                                       |
| unpickle_list            | 2.78 us                                                     | 2.64 us: 1.05x faster                                       |
| xml_etree_generate       | 55.6 ms                                                     | 52.9 ms: 1.05x faster                                       |
| python_startup           | 19.5 ms                                                     | 18.6 ms: 1.05x faster                                       |
| pickle_dict              | 19.3 us                                                     | 18.4 us: 1.04x faster                                       |
| nbody                    | 72.6 ms                                                     | 69.7 ms: 1.04x faster                                       |
| telco                    | 4.09 ms                                                     | 3.93 ms: 1.04x faster                                       |
| scimark_sor              | 79.6 ms                                                     | 76.8 ms: 1.04x faster                                       |
| python_startup_no_site   | 16.1 ms                                                     | 15.6 ms: 1.04x faster                                       |
| 2to3                     | 214 ms                                                      | 207 ms: 1.03x faster                                        |
| create_gc_cycles         | 727 us                                                      | 708 us: 1.03x faster                                        |
| sqlite_synth             | 1.76 us                                                     | 1.72 us: 1.02x faster                                       |
| json_loads               | 13.4 us                                                     | 13.2 us: 1.02x faster                                       |
| regex_dna                | 124 ms                                                      | 122 ms: 1.02x faster                                        |
| docutils                 | 1.63 sec                                                    | 1.60 sec: 1.02x faster                                      |
| deepcopy_reduce          | 2.13 us                                                     | 2.10 us: 1.02x faster                                       |
| xml_etree_process        | 38.4 ms                                                     | 37.8 ms: 1.02x faster                                       |
| float                    | 55.1 ms                                                     | 54.3 ms: 1.02x faster                                       |
| aiohttp                  | 865 us                                                      | 853 us: 1.01x faster                                        |
| pidigits                 | 150 ms                                                      | 148 ms: 1.01x faster                                        |
| scimark_fft              | 180 ms                                                      | 181 ms: 1.00x slower                                        |
| pprint_safe_repr         | 512 ms                                                      | 517 ms: 1.01x slower                                        |
| xml_etree_iterparse      | 62.5 ms                                                     | 63.3 ms: 1.01x slower                                       |
| dask                     | 259 ms                                                      | 263 ms: 1.01x slower                                        |
| pprint_pformat           | 1.04 sec                                                    | 1.06 sec: 1.02x slower                                      |
| fannkuch                 | 237 ms                                                      | 241 ms: 1.02x slower                                        |
| sqlglot_optimize         | 34.4 ms                                                     | 35.1 ms: 1.02x slower                                       |
| regex_v8                 | 13.9 ms                                                     | 14.2 ms: 1.02x slower                                       |
| deepcopy                 | 240 us                                                      | 246 us: 1.02x slower                                        |
| pyflate                  | 297 ms                                                      | 305 ms: 1.03x slower                                        |
| scimark_sparse_mat_mult  | 2.48 ms                                                     | 2.55 ms: 1.03x slower                                       |
| pycparser                | 673 ms                                                      | 694 ms: 1.03x slower                                        |
| tornado_http             | 87.7 ms                                                     | 90.5 ms: 1.03x slower                                       |
| tomli_loads              | 1.37 sec                                                    | 1.42 sec: 1.03x slower                                      |
| sqlglot_normalize        | 185 ms                                                      | 192 ms: 1.04x slower                                        |
| pickle_pure_python       | 196 us                                                      | 203 us: 1.04x slower                                        |
| regex_compile            | 88.3 ms                                                     | 91.7 ms: 1.04x slower                                       |
| crypto_pyaes             | 47.4 ms                                                     | 49.3 ms: 1.04x slower                                       |
| nqueens                  | 61.2 ms                                                     | 63.7 ms: 1.04x slower                                       |
| meteor_contest           | 73.1 ms                                                     | 76.1 ms: 1.04x slower                                       |
| coverage                 | 51.5 ms                                                     | 53.6 ms: 1.04x slower                                       |
| coroutines               | 14.0 ms                                                     | 14.7 ms: 1.05x slower                                       |
| asyncio_tcp_ssl          | 1.96 sec                                                    | 2.07 sec: 1.05x slower                                      |
| mako                     | 6.93 ms                                                     | 7.31 ms: 1.05x slower                                       |
| raytrace                 | 191 ms                                                      | 203 ms: 1.06x slower                                        |
| json                     | 2.86 ms                                                     | 3.03 ms: 1.06x slower                                       |
| async_tree_none          | 294 ms                                                      | 311 ms: 1.06x slower                                        |
| scimark_monte_carlo      | 43.7 ms                                                     | 46.3 ms: 1.06x slower                                       |
| dulwich_log              | 42.4 ms                                                     | 45.0 ms: 1.06x slower                                       |
| deepcopy_memo            | 23.8 us                                                     | 25.3 us: 1.06x slower                                       |
| scimark_lu               | 58.1 ms                                                     | 61.9 ms: 1.07x slower                                       |
| spectral_norm            | 63.2 ms                                                     | 67.5 ms: 1.07x slower                                       |
| async_tree_cpu_io_mixed  | 479 ms                                                      | 515 ms: 1.08x slower                                        |
| logging_format           | 6.67 us                                                     | 7.18 us: 1.08x slower                                       |
| logging_simple           | 6.21 us                                                     | 6.72 us: 1.08x slower                                       |
| async_tree_io            | 720 ms                                                      | 778 ms: 1.08x slower                                        |
| xml_etree_parse          | 89.2 ms                                                     | 97.3 ms: 1.09x slower                                       |
| sqlglot_transpile        | 1.04 ms                                                     | 1.14 ms: 1.10x slower                                       |
| comprehensions           | 14.1 us                                                     | 15.7 us: 1.11x slower                                       |
| async_tree_memoization   | 336 ms                                                      | 375 ms: 1.12x slower                                        |
| hexiom                   | 4.03 ms                                                     | 4.55 ms: 1.13x slower                                       |
| unpickle_pure_python     | 133 us                                                      | 151 us: 1.13x slower                                        |
| richards                 | 26.9 ms                                                     | 30.6 ms: 1.14x slower                                       |
| sqlglot_parse            | 820 us                                                      | 938 us: 1.14x slower                                        |
| go                       | 88.5 ms                                                     | 102 ms: 1.15x slower                                        |
| chaos                    | 42.8 ms                                                     | 49.7 ms: 1.16x slower                                       |
| logging_silent           | 60.6 ns                                                     | 70.7 ns: 1.17x slower                                       |
| mdp                      | 1.44 sec                                                    | 1.71 sec: 1.19x slower                                      |
| deltablue                | 2.14 ms                                                     | 2.63 ms: 1.23x slower                                       |
| unpack_sequence          | 37.5 ns                                                     | 46.3 ns: 1.24x slower                                       |
| richards_super           | 30.5 ms                                                     | 38.4 ms: 1.26x slower                                       |
| mypy2                    | 207 ms                                                      | 277 ms: 1.33x slower                                        |
| json_dumps               | 5.60 ms                                                     | 7.74 ms: 1.38x slower                                       |
| generators               | 22.7 ms                                                     | 33.7 ms: 1.48x slower                                       |
| asyncio_tcp              | 472 ms                                                      | 728 ms: 1.54x slower                                        |
| typing_runtime_protocols | 95.2 us                                                     | 324 us: 3.41x slower                                        |
| Geometric mean           | (ref)                                                       | 1.06x slower                                                |

Benchmark hidden because not significant (2): gc_traversal, bench_thread_pool
Ignored benchmarks (14) of results/bm-20231002-3.11.6-8b6ee5b/bm-20231002-pythonperf1-amd64-python-v3.11.6-3.11.6-8b6ee5b.json: chameleon, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.02x
- 95% likely to have a slowdown of 1.01x
- 99% likely to have a slowdown of 1.01x
