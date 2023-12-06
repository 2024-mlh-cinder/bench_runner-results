
# Results vs. 3.12.0

- fork: python
- ref: v3.11.5
- machine: linux-x86_64
- commit hash: cce6ba9
- commit date: 2023-08-24
- overall geometric mean: 1.07x slower
- HPT reliability: 99.52%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230824-pythonperf2-x86_64-python-v3.11.5-3.11.5-cce6ba9 |
|----------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| 2to3           | 287 ms                                                       | 285 ms: 1.01x faster                                         |
| docutils       | 2.89 sec                                                     | 2.84 sec: 1.02x faster                                       |
| tornado_http   | 122 ms                                                       | 124 ms: 1.02x slower                                         |
| Geometric mean | (ref)                                                        | 1.00x faster                                                 |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230824-pythonperf2-x86_64-python-v3.11.5-3.11.5-cce6ba9 |
|----------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| float          | 78.5 ms                                                      | 74.3 ms: 1.06x faster                                        |
| pidigits       | 264 ms                                                       | 251 ms: 1.05x faster                                         |
| nbody          | 94.1 ms                                                      | 90.5 ms: 1.04x faster                                        |
| Geometric mean | (ref)                                                        | 1.05x faster                                                 |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230824-pythonperf2-x86_64-python-v3.11.5-3.11.5-cce6ba9 |
|----------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| regex_dna      | 241 ms                                                       | 227 ms: 1.06x faster                                         |
| regex_effbot   | 3.47 ms                                                      | 3.31 ms: 1.05x faster                                        |
| regex_v8       | 25.0 ms                                                      | 24.2 ms: 1.03x faster                                        |
| regex_compile  | 146 ms                                                       | 155 ms: 1.06x slower                                         |
| Geometric mean | (ref)                                                        | 1.02x faster                                                 |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230824-pythonperf2-x86_64-python-v3.11.5-3.11.5-cce6ba9 |
|----------------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| unpickle             | 14.8 us                                                      | 13.3 us: 1.11x faster                                        |
| pickle_list          | 4.39 us                                                      | 3.94 us: 1.11x faster                                        |
| xml_etree_generate   | 86.1 ms                                                      | 80.8 ms: 1.07x faster                                        |
| xml_etree_process    | 58.3 ms                                                      | 56.1 ms: 1.04x faster                                        |
| unpickle_list        | 4.77 us                                                      | 4.63 us: 1.03x faster                                        |
| pickle               | 10.1 us                                                      | 9.98 us: 1.01x faster                                        |
| pickle_pure_python   | 323 us                                                       | 320 us: 1.01x faster                                         |
| pickle_dict          | 31.7 us                                                      | 33.1 us: 1.04x slower                                        |
| tomli_loads          | 2.20 sec                                                     | 2.30 sec: 1.05x slower                                       |
| xml_etree_parse      | 146 ms                                                       | 157 ms: 1.07x slower                                         |
| json_loads           | 24.3 us                                                      | 27.9 us: 1.15x slower                                        |
| unpickle_pure_python | 207 us                                                       | 241 us: 1.16x slower                                         |
| json_dumps           | 10.2 ms                                                      | 13.5 ms: 1.32x slower                                        |
| Geometric mean       | (ref)                                                        | 1.03x slower                                                 |

Benchmark hidden because not significant (1): xml_etree_iterparse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230824-pythonperf2-x86_64-python-v3.11.5-3.11.5-cce6ba9 |
|------------------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| python_startup_no_site | 8.70 ms                                                      | 7.79 ms: 1.12x faster                                        |
| python_startup         | 11.7 ms                                                      | 10.8 ms: 1.09x faster                                        |
| Geometric mean         | (ref)                                                        | 1.10x faster                                                 |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230824-pythonperf2-x86_64-python-v3.11.5-3.11.5-cce6ba9 |
|-----------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| mako      | 9.94 ms                                                      | 10.6 ms: 1.07x slower                                        |

All benchmarks:
===============

| Benchmark                | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230824-pythonperf2-x86_64-python-v3.11.5-3.11.5-cce6ba9 |
|--------------------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| async_generators         | 385 ms                                                       | 318 ms: 1.21x faster                                         |
| unpack_sequence          | 53.3 ns                                                      | 46.9 ns: 1.14x faster                                        |
| bench_mp_pool            | 5.34 ms                                                      | 4.75 ms: 1.12x faster                                        |
| python_startup_no_site   | 8.70 ms                                                      | 7.79 ms: 1.12x faster                                        |
| unpickle                 | 14.8 us                                                      | 13.3 us: 1.11x faster                                        |
| pickle_list              | 4.39 us                                                      | 3.94 us: 1.11x faster                                        |
| scimark_sparse_mat_mult  | 4.42 ms                                                      | 4.00 ms: 1.11x faster                                        |
| python_startup           | 11.7 ms                                                      | 10.8 ms: 1.09x faster                                        |
| scimark_fft              | 304 ms                                                       | 280 ms: 1.09x faster                                         |
| xml_etree_generate       | 86.1 ms                                                      | 80.8 ms: 1.07x faster                                        |
| pprint_safe_repr         | 823 ms                                                       | 775 ms: 1.06x faster                                         |
| regex_dna                | 241 ms                                                       | 227 ms: 1.06x faster                                         |
| float                    | 78.5 ms                                                      | 74.3 ms: 1.06x faster                                        |
| sqlite_synth             | 2.70 us                                                      | 2.55 us: 1.06x faster                                        |
| pidigits                 | 264 ms                                                       | 251 ms: 1.05x faster                                         |
| scimark_monte_carlo      | 72.4 ms                                                      | 69.0 ms: 1.05x faster                                        |
| regex_effbot             | 3.47 ms                                                      | 3.31 ms: 1.05x faster                                        |
| pathlib                  | 19.8 ms                                                      | 19.0 ms: 1.04x faster                                        |
| pprint_pformat           | 1.67 sec                                                     | 1.61 sec: 1.04x faster                                       |
| nbody                    | 94.1 ms                                                      | 90.5 ms: 1.04x faster                                        |
| xml_etree_process        | 58.3 ms                                                      | 56.1 ms: 1.04x faster                                        |
| create_gc_cycles         | 1.67 ms                                                      | 1.62 ms: 1.04x faster                                        |
| regex_v8                 | 25.0 ms                                                      | 24.2 ms: 1.03x faster                                        |
| telco                    | 6.96 ms                                                      | 6.75 ms: 1.03x faster                                        |
| unpickle_list            | 4.77 us                                                      | 4.63 us: 1.03x faster                                        |
| docutils                 | 2.89 sec                                                     | 2.84 sec: 1.02x faster                                       |
| deepcopy_reduce          | 3.46 us                                                      | 3.40 us: 1.02x faster                                        |
| pyflate                  | 447 ms                                                       | 441 ms: 1.01x faster                                         |
| pickle                   | 10.1 us                                                      | 9.98 us: 1.01x faster                                        |
| pickle_pure_python       | 323 us                                                       | 320 us: 1.01x faster                                         |
| 2to3                     | 287 ms                                                       | 285 ms: 1.01x faster                                         |
| crypto_pyaes             | 80.9 ms                                                      | 81.7 ms: 1.01x slower                                        |
| scimark_sor              | 110 ms                                                       | 111 ms: 1.01x slower                                         |
| tornado_http             | 122 ms                                                       | 124 ms: 1.02x slower                                         |
| sqlglot_optimize         | 57.8 ms                                                      | 58.9 ms: 1.02x slower                                        |
| spectral_norm            | 91.6 ms                                                      | 93.3 ms: 1.02x slower                                        |
| meteor_contest           | 128 ms                                                       | 131 ms: 1.02x slower                                         |
| dask                     | 397 ms                                                       | 409 ms: 1.03x slower                                         |
| pycparser                | 1.27 sec                                                     | 1.32 sec: 1.04x slower                                       |
| pickle_dict              | 31.7 us                                                      | 33.1 us: 1.04x slower                                        |
| tomli_loads              | 2.20 sec                                                     | 2.30 sec: 1.05x slower                                       |
| logging_silent           | 95.6 ns                                                      | 100 ns: 1.05x slower                                         |
| deepcopy                 | 376 us                                                       | 396 us: 1.05x slower                                         |
| raytrace                 | 302 ms                                                       | 318 ms: 1.05x slower                                         |
| sqlglot_transpile        | 1.80 ms                                                      | 1.91 ms: 1.06x slower                                        |
| sqlglot_normalize        | 117 ms                                                       | 124 ms: 1.06x slower                                         |
| logging_format           | 7.37 us                                                      | 7.83 us: 1.06x slower                                        |
| regex_compile            | 146 ms                                                       | 155 ms: 1.06x slower                                         |
| gc_traversal             | 3.54 ms                                                      | 3.77 ms: 1.07x slower                                        |
| mako                     | 9.94 ms                                                      | 10.6 ms: 1.07x slower                                        |
| xml_etree_parse          | 146 ms                                                       | 157 ms: 1.07x slower                                         |
| json                     | 5.14 ms                                                      | 5.55 ms: 1.08x slower                                        |
| go                       | 150 ms                                                       | 163 ms: 1.08x slower                                         |
| async_tree_cpu_io_mixed  | 706 ms                                                       | 765 ms: 1.08x slower                                         |
| logging_simple           | 6.73 us                                                      | 7.33 us: 1.09x slower                                        |
| mdp                      | 2.53 sec                                                     | 2.78 sec: 1.10x slower                                       |
| sqlglot_parse            | 1.40 ms                                                      | 1.54 ms: 1.10x slower                                        |
| async_tree_io            | 1.06 sec                                                     | 1.17 sec: 1.11x slower                                       |
| scimark_lu               | 101 ms                                                       | 113 ms: 1.13x slower                                         |
| async_tree_none          | 459 ms                                                       | 518 ms: 1.13x slower                                         |
| async_tree_memoization   | 553 ms                                                       | 624 ms: 1.13x slower                                         |
| nqueens                  | 90.1 ms                                                      | 102 ms: 1.13x slower                                         |
| comprehensions           | 21.9 us                                                      | 25.0 us: 1.14x slower                                        |
| richards                 | 45.0 ms                                                      | 51.6 ms: 1.15x slower                                        |
| json_loads               | 24.3 us                                                      | 27.9 us: 1.15x slower                                        |
| unpickle_pure_python     | 207 us                                                       | 241 us: 1.16x slower                                         |
| coroutines               | 23.0 ms                                                      | 27.7 ms: 1.20x slower                                        |
| hexiom                   | 5.96 ms                                                      | 7.21 ms: 1.21x slower                                        |
| deltablue                | 3.29 ms                                                      | 4.03 ms: 1.23x slower                                        |
| richards_super           | 51.7 ms                                                      | 64.3 ms: 1.24x slower                                        |
| chaos                    | 62.9 ms                                                      | 79.1 ms: 1.26x slower                                        |
| json_dumps               | 10.2 ms                                                      | 13.5 ms: 1.32x slower                                        |
| fannkuch                 | 350 ms                                                       | 470 ms: 1.34x slower                                         |
| mypy2                    | 368 ms                                                       | 537 ms: 1.46x slower                                         |
| generators               | 36.7 ms                                                      | 55.4 ms: 1.51x slower                                        |
| asyncio_tcp_ssl          | 1.58 sec                                                     | 3.08 sec: 1.96x slower                                       |
| asyncio_tcp              | 381 ms                                                       | 753 ms: 1.98x slower                                         |
| typing_runtime_protocols | 151 us                                                       | 518 us: 3.43x slower                                         |
| Geometric mean           | (ref)                                                        | 1.07x slower                                                 |

Benchmark hidden because not significant (4): xml_etree_iterparse, deepcopy_memo, dulwich_log, bench_thread_pool
Ignored benchmarks (1) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: coverage
Ignored benchmarks (16) of results/bm-20230824-3.11.5-cce6ba9/bm-20230824-pythonperf2-x86_64-python-v3.11.5-3.11.5-cce6ba9.json: aiohttp, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 99.52% likely to be slow
- 90% likely to have a slowdown of 1.01x
- 95% likely to have a slowdown of 1.01x
- 99% likely to have a slowdown of 1.00x
