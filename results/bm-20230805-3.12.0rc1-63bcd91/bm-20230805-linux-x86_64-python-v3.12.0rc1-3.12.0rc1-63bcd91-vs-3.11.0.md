
# Results vs. 3.11.0

- fork: python
- ref: v3.12.0rc1
- machine: linux-x86_64
- commit hash: 63bcd91
- commit date: 2023-08-05
- overall geometric mean: 1.03x faster
- HPT reliability: 88.38%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230805-linux-x86_64-python-v3.12.0rc1-3.12.0rc1-63bcd91 |
|----------------|:------------------------------------------------------:|:------------------------------------------------------------:|
| 2to3           | 259 ms                                                 | 267 ms: 1.03x slower                                         |
| docutils       | 2.63 sec                                               | 2.70 sec: 1.03x slower                                       |
| tornado_http   | 96.3 ms                                                | 99.1 ms: 1.03x slower                                        |
| Geometric mean | (ref)                                                  | 1.03x slower                                                 |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230805-linux-x86_64-python-v3.12.0rc1-3.12.0rc1-63bcd91 |
|----------------|:------------------------------------------------------:|:------------------------------------------------------------:|
| nbody          | 93.1 ms                                                | 89.6 ms: 1.04x faster                                        |
| pidigits       | 198 ms                                                 | 201 ms: 1.01x slower                                         |
| float          | 77.2 ms                                                | 79.3 ms: 1.03x slower                                        |
| Geometric mean | (ref)                                                  | 1.00x faster                                                 |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230805-linux-x86_64-python-v3.12.0rc1-3.12.0rc1-63bcd91 |
|----------------|:------------------------------------------------------:|:------------------------------------------------------------:|
| regex_effbot   | 3.99 ms                                                | 3.52 ms: 1.13x faster                                        |
| regex_v8       | 22.0 ms                                                | 22.5 ms: 1.02x slower                                        |
| regex_dna      | 204 ms                                                 | 210 ms: 1.03x slower                                         |
| regex_compile  | 138 ms                                                 | 145 ms: 1.05x slower                                         |
| Geometric mean | (ref)                                                  | 1.01x faster                                                 |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230805-linux-x86_64-python-v3.12.0rc1-3.12.0rc1-63bcd91 |
|----------------------|:------------------------------------------------------:|:------------------------------------------------------------:|
| json_dumps           | 12.6 ms                                                | 9.75 ms: 1.29x faster                                        |
| json_loads           | 26.5 us                                                | 25.4 us: 1.04x faster                                        |
| unpickle_pure_python | 228 us                                                 | 219 us: 1.04x faster                                         |
| xml_etree_parse      | 158 ms                                                 | 155 ms: 1.02x faster                                         |
| pickle_dict          | 31.1 us                                                | 31.4 us: 1.01x slower                                        |
| unpickle_list        | 4.91 us                                                | 4.98 us: 1.01x slower                                        |
| pickle_pure_python   | 306 us                                                 | 311 us: 1.02x slower                                         |
| pickle               | 10.1 us                                                | 10.8 us: 1.07x slower                                        |
| unpickle             | 13.7 us                                                | 14.9 us: 1.09x slower                                        |
| xml_etree_process    | 53.9 ms                                                | 59.2 ms: 1.10x slower                                        |
| pickle_list          | 4.11 us                                                | 4.55 us: 1.11x slower                                        |
| xml_etree_generate   | 76.2 ms                                                | 85.4 ms: 1.12x slower                                        |
| Geometric mean       | (ref)                                                  | 1.01x slower                                                 |

Benchmark hidden because not significant (2): tomli_loads, xml_etree_iterparse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230805-linux-x86_64-python-v3.12.0rc1-3.12.0rc1-63bcd91 |
|------------------------|:------------------------------------------------------:|:------------------------------------------------------------:|
| python_startup         | 8.52 ms                                                | 9.30 ms: 1.09x slower                                        |
| python_startup_no_site | 6.01 ms                                                | 6.76 ms: 1.13x slower                                        |
| Geometric mean         | (ref)                                                  | 1.11x slower                                                 |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230805-linux-x86_64-python-v3.12.0rc1-3.12.0rc1-63bcd91 |
|-----------|:------------------------------------------------------:|:------------------------------------------------------------:|
| mako      | 10.1 ms                                                | 10.7 ms: 1.06x slower                                        |

All benchmarks:
===============

| Benchmark                | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230805-linux-x86_64-python-v3.12.0rc1-3.12.0rc1-63bcd91 |
|--------------------------|:------------------------------------------------------:|:------------------------------------------------------------:|
| typing_runtime_protocols | 486 us                                                 | 149 us: 3.25x faster                                         |
| generators               | 73.5 ms                                                | 30.2 ms: 2.43x faster                                        |
| asyncio_tcp              | 922 ms                                                 | 515 ms: 1.79x faster                                         |
| asyncio_tcp_ssl          | 3.14 sec                                               | 1.80 sec: 1.74x faster                                       |
| json_dumps               | 12.6 ms                                                | 9.75 ms: 1.29x faster                                        |
| mypy2                    | 420 ms                                                 | 343 ms: 1.22x faster                                         |
| regex_effbot             | 3.99 ms                                                | 3.52 ms: 1.13x faster                                        |
| richards_super           | 56.8 ms                                                | 50.3 ms: 1.13x faster                                        |
| coroutines               | 25.5 ms                                                | 22.7 ms: 1.12x faster                                        |
| async_tree_none          | 526 ms                                                 | 471 ms: 1.12x faster                                         |
| async_tree_io            | 1.30 sec                                               | 1.16 sec: 1.11x faster                                       |
| async_tree_memoization   | 627 ms                                                 | 573 ms: 1.09x faster                                         |
| comprehensions           | 22.4 us                                                | 20.7 us: 1.09x faster                                        |
| chaos                    | 69.2 ms                                                | 64.0 ms: 1.08x faster                                        |
| coverage                 | 100 ms                                                 | 94.3 ms: 1.06x faster                                        |
| async_tree_cpu_io_mixed  | 739 ms                                                 | 708 ms: 1.04x faster                                         |
| json_loads               | 26.5 us                                                | 25.4 us: 1.04x faster                                        |
| nbody                    | 93.1 ms                                                | 89.6 ms: 1.04x faster                                        |
| unpickle_pure_python     | 228 us                                                 | 219 us: 1.04x faster                                         |
| json                     | 4.94 ms                                                | 4.77 ms: 1.04x faster                                        |
| sqlglot_parse            | 1.40 ms                                                | 1.35 ms: 1.04x faster                                        |
| go                       | 140 ms                                                 | 135 ms: 1.03x faster                                         |
| deltablue                | 3.67 ms                                                | 3.55 ms: 1.03x faster                                        |
| pycparser                | 1.18 sec                                               | 1.14 sec: 1.03x faster                                       |
| richards                 | 45.7 ms                                                | 44.3 ms: 1.03x faster                                        |
| mdp                      | 2.62 sec                                               | 2.54 sec: 1.03x faster                                       |
| gc_traversal             | 4.02 ms                                                | 3.91 ms: 1.03x faster                                        |
| hexiom                   | 6.37 ms                                                | 6.21 ms: 1.03x faster                                        |
| xml_etree_parse          | 158 ms                                                 | 155 ms: 1.02x faster                                         |
| nqueens                  | 83.4 ms                                                | 81.5 ms: 1.02x faster                                        |
| sqlglot_transpile        | 1.70 ms                                                | 1.67 ms: 1.02x faster                                        |
| meteor_contest           | 107 ms                                                 | 105 ms: 1.02x faster                                         |
| pickle_dict              | 31.1 us                                                | 31.4 us: 1.01x slower                                        |
| pidigits                 | 198 ms                                                 | 201 ms: 1.01x slower                                         |
| logging_silent           | 101 ns                                                 | 102 ns: 1.01x slower                                         |
| unpickle_list            | 4.91 us                                                | 4.98 us: 1.01x slower                                        |
| bench_thread_pool        | 819 us                                                 | 832 us: 1.02x slower                                         |
| fannkuch                 | 388 ms                                                 | 394 ms: 1.02x slower                                         |
| pickle_pure_python       | 306 us                                                 | 311 us: 1.02x slower                                         |
| create_gc_cycles         | 1.49 ms                                                | 1.51 ms: 1.02x slower                                        |
| regex_v8                 | 22.0 ms                                                | 22.5 ms: 1.02x slower                                        |
| sqlglot_optimize         | 53.1 ms                                                | 54.3 ms: 1.02x slower                                        |
| float                    | 77.2 ms                                                | 79.3 ms: 1.03x slower                                        |
| sqlglot_normalize        | 108 ms                                                 | 111 ms: 1.03x slower                                         |
| pprint_pformat           | 1.46 sec                                               | 1.50 sec: 1.03x slower                                       |
| logging_simple           | 6.03 us                                                | 6.20 us: 1.03x slower                                        |
| sqlalchemy_imperative    | 17.9 ms                                                | 18.4 ms: 1.03x slower                                        |
| docutils                 | 2.63 sec                                               | 2.70 sec: 1.03x slower                                       |
| regex_dna                | 204 ms                                                 | 210 ms: 1.03x slower                                         |
| tornado_http             | 96.3 ms                                                | 99.1 ms: 1.03x slower                                        |
| 2to3                     | 259 ms                                                 | 267 ms: 1.03x slower                                         |
| deepcopy                 | 342 us                                                 | 355 us: 1.04x slower                                         |
| scimark_lu               | 110 ms                                                 | 114 ms: 1.04x slower                                         |
| telco                    | 6.58 ms                                                | 6.86 ms: 1.04x slower                                        |
| sqlalchemy_declarative   | 138 ms                                                 | 145 ms: 1.05x slower                                         |
| logging_format           | 6.68 us                                                | 6.99 us: 1.05x slower                                        |
| regex_compile            | 138 ms                                                 | 145 ms: 1.05x slower                                         |
| crypto_pyaes             | 74.7 ms                                                | 78.4 ms: 1.05x slower                                        |
| pprint_safe_repr         | 701 ms                                                 | 737 ms: 1.05x slower                                         |
| scimark_monte_carlo      | 68.1 ms                                                | 71.7 ms: 1.05x slower                                        |
| scimark_sor              | 118 ms                                                 | 125 ms: 1.06x slower                                         |
| mako                     | 10.1 ms                                                | 10.7 ms: 1.06x slower                                        |
| pyflate                  | 418 ms                                                 | 444 ms: 1.06x slower                                         |
| spectral_norm            | 100 ms                                                 | 107 ms: 1.07x slower                                         |
| deepcopy_reduce          | 2.94 us                                                | 3.14 us: 1.07x slower                                        |
| pickle                   | 10.1 us                                                | 10.8 us: 1.07x slower                                        |
| dulwich_log              | 63.7 ms                                                | 68.5 ms: 1.08x slower                                        |
| scimark_fft              | 328 ms                                                 | 356 ms: 1.08x slower                                         |
| scimark_sparse_mat_mult  | 4.50 ms                                                | 4.89 ms: 1.09x slower                                        |
| python_startup           | 8.52 ms                                                | 9.30 ms: 1.09x slower                                        |
| sqlite_synth             | 2.52 us                                                | 2.75 us: 1.09x slower                                        |
| unpickle                 | 13.7 us                                                | 14.9 us: 1.09x slower                                        |
| xml_etree_process        | 53.9 ms                                                | 59.2 ms: 1.10x slower                                        |
| pickle_list              | 4.11 us                                                | 4.55 us: 1.11x slower                                        |
| xml_etree_generate       | 76.2 ms                                                | 85.4 ms: 1.12x slower                                        |
| python_startup_no_site   | 6.01 ms                                                | 6.76 ms: 1.13x slower                                        |
| unpack_sequence          | 43.1 ns                                                | 52.6 ns: 1.22x slower                                        |
| async_generators         | 368 ms                                                 | 450 ms: 1.22x slower                                         |
| dask                     | 360 ms                                                 | 537 ms: 1.49x slower                                         |
| Geometric mean           | (ref)                                                  | 1.03x faster                                                 |

Benchmark hidden because not significant (6): tomli_loads, bench_mp_pool, pathlib, xml_etree_iterparse, raytrace, deepcopy_memo
Ignored benchmarks (15) of results/bm-20221024-3.11.0-deaf509/bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 88.38% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
