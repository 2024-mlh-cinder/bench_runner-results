
# Results vs. 3.11.0

- fork: python
- ref: 3.12
- machine: windows-amd64
- commit hash: 028f477
- commit date: 2023-10-21
- overall geometric mean: 1.06x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.01x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231021-pythonperf1-amd64-python-3.12-3.12.0+-028f477 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------:|
| 2to3           | 209 ms                                                      | 213 ms: 1.02x slower                                      |
| docutils       | 1.60 sec                                                    | 1.63 sec: 1.02x slower                                    |
| tornado_http   | 91.8 ms                                                     | 87.6 ms: 1.05x faster                                     |
| Geometric mean | (ref)                                                       | 1.00x faster                                              |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231021-pythonperf1-amd64-python-3.12-3.12.0+-028f477 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------:|
| float          | 54.6 ms                                                     | 53.5 ms: 1.02x faster                                     |
| nbody          | 70.0 ms                                                     | 69.2 ms: 1.01x faster                                     |
| pidigits       | 148 ms                                                      | 150 ms: 1.01x slower                                      |
| Geometric mean | (ref)                                                       | 1.01x faster                                              |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231021-pythonperf1-amd64-python-3.12-3.12.0+-028f477 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------:|
| regex_compile  | 90.6 ms                                                     | 86.5 ms: 1.05x faster                                     |
| regex_effbot   | 1.50 ms                                                     | 1.61 ms: 1.07x slower                                     |
| regex_dna      | 115 ms                                                      | 126 ms: 1.09x slower                                      |
| Geometric mean | (ref)                                                       | 1.03x slower                                              |

Benchmark hidden because not significant (1): regex_v8

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231021-pythonperf1-amd64-python-3.12-3.12.0+-028f477 |
|----------------------|:-----------------------------------------------------------:|:---------------------------------------------------------:|
| json_dumps           | 7.56 ms                                                     | 5.68 ms: 1.33x faster                                     |
| unpickle_pure_python | 152 us                                                      | 133 us: 1.15x faster                                      |
| xml_etree_parse      | 95.9 ms                                                     | 91.2 ms: 1.05x faster                                     |
| tomli_loads          | 1.41 sec                                                    | 1.38 sec: 1.03x faster                                    |
| pickle_pure_python   | 200 us                                                      | 196 us: 1.02x faster                                      |
| unpickle             | 8.09 us                                                     | 8.14 us: 1.01x slower                                     |
| xml_etree_iterparse  | 62.6 ms                                                     | 63.6 ms: 1.02x slower                                     |
| xml_etree_process    | 37.1 ms                                                     | 38.1 ms: 1.03x slower                                     |
| pickle               | 6.61 us                                                     | 6.95 us: 1.05x slower                                     |
| json_loads           | 12.9 us                                                     | 13.6 us: 1.05x slower                                     |
| pickle_list          | 2.68 us                                                     | 2.83 us: 1.06x slower                                     |
| xml_etree_generate   | 52.2 ms                                                     | 55.5 ms: 1.06x slower                                     |
| unpickle_list        | 2.55 us                                                     | 2.80 us: 1.10x slower                                     |
| Geometric mean       | (ref)                                                       | 1.01x faster                                              |

Benchmark hidden because not significant (1): pickle_dict

Benchmarks with tag 'startup':
==============================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231021-pythonperf1-amd64-python-3.12-3.12.0+-028f477 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------:|
| python_startup | 18.7 ms                                                     | 19.1 ms: 1.02x slower                                     |
| Geometric mean | (ref)                                                       | 1.01x slower                                              |

Benchmark hidden because not significant (1): python_startup_no_site

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231021-pythonperf1-amd64-python-3.12-3.12.0+-028f477 |
|-----------|:-----------------------------------------------------------:|:---------------------------------------------------------:|
| mako      | 7.26 ms                                                     | 6.88 ms: 1.06x faster                                     |

All benchmarks:
===============

| Benchmark                | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231021-pythonperf1-amd64-python-3.12-3.12.0+-028f477 |
|--------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------:|
| typing_runtime_protocols | 322 us                                                      | 94.3 us: 3.41x faster                                     |
| generators               | 33.8 ms                                                     | 22.5 ms: 1.50x faster                                     |
| asyncio_tcp              | 699 ms                                                      | 471 ms: 1.48x faster                                      |
| json_dumps               | 7.56 ms                                                     | 5.68 ms: 1.33x faster                                     |
| unpack_sequence          | 46.1 ns                                                     | 36.8 ns: 1.25x faster                                     |
| richards_super           | 37.5 ms                                                     | 30.5 ms: 1.23x faster                                     |
| deltablue                | 2.61 ms                                                     | 2.13 ms: 1.23x faster                                     |
| sqlglot_parse            | 952 us                                                      | 813 us: 1.17x faster                                      |
| mdp                      | 1.67 sec                                                    | 1.43 sec: 1.17x faster                                    |
| unpickle_pure_python     | 152 us                                                      | 133 us: 1.15x faster                                      |
| logging_silent           | 69.8 ns                                                     | 61.2 ns: 1.14x faster                                     |
| richards                 | 30.6 ms                                                     | 26.8 ms: 1.14x faster                                     |
| hexiom                   | 4.55 ms                                                     | 4.02 ms: 1.13x faster                                     |
| sqlglot_transpile        | 1.16 ms                                                     | 1.03 ms: 1.13x faster                                     |
| comprehensions           | 15.9 us                                                     | 14.2 us: 1.12x faster                                     |
| go                       | 97.3 ms                                                     | 87.5 ms: 1.11x faster                                     |
| async_tree_none          | 320 ms                                                      | 289 ms: 1.11x faster                                      |
| chaos                    | 47.1 ms                                                     | 42.8 ms: 1.10x faster                                     |
| json                     | 3.25 ms                                                     | 2.96 ms: 1.10x faster                                     |
| asyncio_tcp_ssl          | 2.11 sec                                                    | 1.92 sec: 1.10x faster                                    |
| coverage                 | 55.9 ms                                                     | 51.0 ms: 1.10x faster                                     |
| async_tree_memoization   | 371 ms                                                      | 339 ms: 1.09x faster                                      |
| mypy2                    | 229 ms                                                      | 209 ms: 1.09x faster                                      |
| async_tree_io            | 779 ms                                                      | 715 ms: 1.09x faster                                      |
| scimark_lu               | 63.5 ms                                                     | 58.5 ms: 1.09x faster                                     |
| spectral_norm            | 67.9 ms                                                     | 62.8 ms: 1.08x faster                                     |
| raytrace                 | 211 ms                                                      | 196 ms: 1.08x faster                                      |
| deepcopy_memo            | 25.2 us                                                     | 23.6 us: 1.07x faster                                     |
| fannkuch                 | 252 ms                                                      | 236 ms: 1.07x faster                                      |
| logging_simple           | 6.61 us                                                     | 6.24 us: 1.06x faster                                     |
| mako                     | 7.26 ms                                                     | 6.88 ms: 1.06x faster                                     |
| nqueens                  | 64.9 ms                                                     | 61.5 ms: 1.05x faster                                     |
| scimark_monte_carlo      | 44.6 ms                                                     | 42.4 ms: 1.05x faster                                     |
| xml_etree_parse          | 95.9 ms                                                     | 91.2 ms: 1.05x faster                                     |
| scimark_sparse_mat_mult  | 2.57 ms                                                     | 2.45 ms: 1.05x faster                                     |
| tornado_http             | 91.8 ms                                                     | 87.6 ms: 1.05x faster                                     |
| async_tree_cpu_io_mixed  | 501 ms                                                      | 478 ms: 1.05x faster                                      |
| regex_compile            | 90.6 ms                                                     | 86.5 ms: 1.05x faster                                     |
| dulwich_log              | 44.5 ms                                                     | 42.6 ms: 1.04x faster                                     |
| logging_format           | 7.01 us                                                     | 6.73 us: 1.04x faster                                     |
| pyflate                  | 304 ms                                                      | 292 ms: 1.04x faster                                      |
| aiohttp                  | 899 us                                                      | 865 us: 1.04x faster                                      |
| dask                     | 264 ms                                                      | 255 ms: 1.03x faster                                      |
| coroutines               | 14.6 ms                                                     | 14.2 ms: 1.03x faster                                     |
| bench_thread_pool        | 852 us                                                      | 830 us: 1.03x faster                                      |
| tomli_loads              | 1.41 sec                                                    | 1.38 sec: 1.03x faster                                    |
| crypto_pyaes             | 47.6 ms                                                     | 46.4 ms: 1.02x faster                                     |
| scimark_fft              | 178 ms                                                      | 174 ms: 1.02x faster                                      |
| pickle_pure_python       | 200 us                                                      | 196 us: 1.02x faster                                      |
| float                    | 54.6 ms                                                     | 53.5 ms: 1.02x faster                                     |
| sqlglot_normalize        | 190 ms                                                      | 188 ms: 1.02x faster                                      |
| nbody                    | 70.0 ms                                                     | 69.2 ms: 1.01x faster                                     |
| meteor_contest           | 74.7 ms                                                     | 73.9 ms: 1.01x faster                                     |
| deepcopy                 | 246 us                                                      | 244 us: 1.01x faster                                      |
| sqlglot_optimize         | 34.9 ms                                                     | 34.7 ms: 1.00x faster                                     |
| unpickle                 | 8.09 us                                                     | 8.14 us: 1.01x slower                                     |
| bench_mp_pool            | 62.5 ms                                                     | 63.1 ms: 1.01x slower                                     |
| pidigits                 | 148 ms                                                      | 150 ms: 1.01x slower                                      |
| gc_traversal             | 1.46 ms                                                     | 1.48 ms: 1.01x slower                                     |
| xml_etree_iterparse      | 62.6 ms                                                     | 63.6 ms: 1.02x slower                                     |
| docutils                 | 1.60 sec                                                    | 1.63 sec: 1.02x slower                                    |
| 2to3                     | 209 ms                                                      | 213 ms: 1.02x slower                                      |
| python_startup           | 18.7 ms                                                     | 19.1 ms: 1.02x slower                                     |
| xml_etree_process        | 37.1 ms                                                     | 38.1 ms: 1.03x slower                                     |
| deepcopy_reduce          | 2.07 us                                                     | 2.14 us: 1.03x slower                                     |
| create_gc_cycles         | 693 us                                                      | 716 us: 1.03x slower                                      |
| telco                    | 3.90 ms                                                     | 4.04 ms: 1.03x slower                                     |
| scimark_sor              | 75.6 ms                                                     | 78.3 ms: 1.04x slower                                     |
| sqlite_synth             | 1.68 us                                                     | 1.75 us: 1.04x slower                                     |
| pickle                   | 6.61 us                                                     | 6.95 us: 1.05x slower                                     |
| json_loads               | 12.9 us                                                     | 13.6 us: 1.05x slower                                     |
| pickle_list              | 2.68 us                                                     | 2.83 us: 1.06x slower                                     |
| xml_etree_generate       | 52.2 ms                                                     | 55.5 ms: 1.06x slower                                     |
| regex_effbot             | 1.50 ms                                                     | 1.61 ms: 1.07x slower                                     |
| regex_dna                | 115 ms                                                      | 126 ms: 1.09x slower                                      |
| pathlib                  | 71.4 ms                                                     | 78.2 ms: 1.10x slower                                     |
| unpickle_list            | 2.55 us                                                     | 2.80 us: 1.10x slower                                     |
| async_generators         | 178 ms                                                      | 236 ms: 1.33x slower                                      |
| Geometric mean           | (ref)                                                       | 1.06x faster                                              |

Benchmark hidden because not significant (6): pickle_dict, pycparser, pprint_safe_repr, pprint_pformat, python_startup_no_site, regex_v8
Ignored benchmarks (14) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509.json: chameleon, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.02x
- 95% likely to have a speedup of 1.02x
- 99% likely to have a speedup of 1.01x
