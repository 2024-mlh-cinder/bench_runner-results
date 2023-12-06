
# Results vs. 3.11.0

- fork: python
- ref: 3.12
- machine: linux-x86_64
- commit hash: 8882b30
- commit date: 2023-09-29
- overall geometric mean: 1.03x faster
- HPT reliability: 71.92%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230929-linux-x86_64-python-3.12-3.12.0rc3+-8882b30 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| 2to3           | 259 ms                                                 | 269 ms: 1.04x slower                                    |
| docutils       | 2.63 sec                                               | 2.72 sec: 1.04x slower                                  |
| tornado_http   | 96.3 ms                                                | 100 ms: 1.04x slower                                    |
| Geometric mean | (ref)                                                  | 1.04x slower                                            |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230929-linux-x86_64-python-3.12-3.12.0rc3+-8882b30 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| pidigits       | 198 ms                                                 | 188 ms: 1.06x faster                                    |
| float          | 77.2 ms                                                | 80.1 ms: 1.04x slower                                   |
| Geometric mean | (ref)                                                  | 1.01x faster                                            |

Benchmark hidden because not significant (1): nbody

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230929-linux-x86_64-python-3.12-3.12.0rc3+-8882b30 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| regex_effbot   | 3.99 ms                                                | 3.58 ms: 1.11x faster                                   |
| regex_dna      | 204 ms                                                 | 210 ms: 1.03x slower                                    |
| regex_compile  | 138 ms                                                 | 144 ms: 1.04x slower                                    |
| Geometric mean | (ref)                                                  | 1.01x faster                                            |

Benchmark hidden because not significant (1): regex_v8

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230929-linux-x86_64-python-3.12-3.12.0rc3+-8882b30 |
|----------------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| json_dumps           | 12.6 ms                                                | 9.78 ms: 1.29x faster                                   |
| json_loads           | 26.5 us                                                | 25.2 us: 1.05x faster                                   |
| unpickle_pure_python | 228 us                                                 | 218 us: 1.05x faster                                    |
| xml_etree_parse      | 158 ms                                                 | 154 ms: 1.03x faster                                    |
| unpickle_list        | 4.91 us                                                | 5.05 us: 1.03x slower                                   |
| pickle_pure_python   | 306 us                                                 | 316 us: 1.03x slower                                    |
| pickle               | 10.1 us                                                | 10.6 us: 1.05x slower                                   |
| pickle_dict          | 31.1 us                                                | 32.7 us: 1.05x slower                                   |
| unpickle             | 13.7 us                                                | 14.9 us: 1.09x slower                                   |
| xml_etree_process    | 53.9 ms                                                | 59.0 ms: 1.10x slower                                   |
| xml_etree_generate   | 76.2 ms                                                | 84.6 ms: 1.11x slower                                   |
| pickle_list          | 4.11 us                                                | 4.70 us: 1.14x slower                                   |
| Geometric mean       | (ref)                                                  | 1.01x slower                                            |

Benchmark hidden because not significant (2): tomli_loads, xml_etree_iterparse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230929-linux-x86_64-python-3.12-3.12.0rc3+-8882b30 |
|------------------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| python_startup         | 8.52 ms                                                | 9.48 ms: 1.11x slower                                   |
| python_startup_no_site | 6.01 ms                                                | 6.90 ms: 1.15x slower                                   |
| Geometric mean         | (ref)                                                  | 1.13x slower                                            |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230929-linux-x86_64-python-3.12-3.12.0rc3+-8882b30 |
|-----------|:------------------------------------------------------:|:-------------------------------------------------------:|
| mako      | 10.1 ms                                                | 10.7 ms: 1.06x slower                                   |

All benchmarks:
===============

| Benchmark                | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230929-linux-x86_64-python-3.12-3.12.0rc3+-8882b30 |
|--------------------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| typing_runtime_protocols | 486 us                                                 | 145 us: 3.34x faster                                    |
| generators               | 73.5 ms                                                | 32.6 ms: 2.26x faster                                   |
| asyncio_tcp_ssl          | 3.14 sec                                               | 1.80 sec: 1.74x faster                                  |
| asyncio_tcp              | 922 ms                                                 | 529 ms: 1.74x faster                                    |
| json_dumps               | 12.6 ms                                                | 9.78 ms: 1.29x faster                                   |
| mypy2                    | 420 ms                                                 | 345 ms: 1.22x faster                                    |
| coroutines               | 25.5 ms                                                | 22.1 ms: 1.16x faster                                   |
| async_tree_none          | 526 ms                                                 | 468 ms: 1.12x faster                                    |
| richards_super           | 56.8 ms                                                | 50.6 ms: 1.12x faster                                   |
| async_tree_io            | 1.30 sec                                               | 1.16 sec: 1.12x faster                                  |
| regex_effbot             | 3.99 ms                                                | 3.58 ms: 1.11x faster                                   |
| async_tree_memoization   | 627 ms                                                 | 573 ms: 1.09x faster                                    |
| chaos                    | 69.2 ms                                                | 63.5 ms: 1.09x faster                                   |
| comprehensions           | 22.4 us                                                | 20.6 us: 1.09x faster                                   |
| coverage                 | 100 ms                                                 | 94.7 ms: 1.06x faster                                   |
| pidigits                 | 198 ms                                                 | 188 ms: 1.06x faster                                    |
| json_loads               | 26.5 us                                                | 25.2 us: 1.05x faster                                   |
| sqlglot_parse            | 1.40 ms                                                | 1.34 ms: 1.05x faster                                   |
| richards                 | 45.7 ms                                                | 43.7 ms: 1.05x faster                                   |
| unpickle_pure_python     | 228 us                                                 | 218 us: 1.05x faster                                    |
| json                     | 4.94 ms                                                | 4.78 ms: 1.03x faster                                   |
| pycparser                | 1.18 sec                                               | 1.14 sec: 1.03x faster                                  |
| sqlglot_transpile        | 1.70 ms                                                | 1.65 ms: 1.03x faster                                   |
| xml_etree_parse          | 158 ms                                                 | 154 ms: 1.03x faster                                    |
| async_tree_cpu_io_mixed  | 739 ms                                                 | 720 ms: 1.03x faster                                    |
| nqueens                  | 83.4 ms                                                | 81.5 ms: 1.02x faster                                   |
| deltablue                | 3.67 ms                                                | 3.60 ms: 1.02x faster                                   |
| mdp                      | 2.62 sec                                               | 2.56 sec: 1.02x faster                                  |
| meteor_contest           | 107 ms                                                 | 105 ms: 1.02x faster                                    |
| hexiom                   | 6.37 ms                                                | 6.26 ms: 1.02x faster                                   |
| go                       | 140 ms                                                 | 138 ms: 1.02x faster                                    |
| gc_traversal             | 4.02 ms                                                | 3.95 ms: 1.02x faster                                   |
| raytrace                 | 297 ms                                                 | 294 ms: 1.01x faster                                    |
| sqlglot_normalize        | 108 ms                                                 | 107 ms: 1.00x faster                                    |
| sqlglot_optimize         | 53.1 ms                                                | 53.4 ms: 1.01x slower                                   |
| fannkuch                 | 388 ms                                                 | 391 ms: 1.01x slower                                    |
| deepcopy_memo            | 37.0 us                                                | 37.5 us: 1.01x slower                                   |
| bench_thread_pool        | 819 us                                                 | 831 us: 1.01x slower                                    |
| create_gc_cycles         | 1.49 ms                                                | 1.52 ms: 1.02x slower                                   |
| dask                     | 360 ms                                                 | 368 ms: 1.02x slower                                    |
| sqlalchemy_imperative    | 17.9 ms                                                | 18.4 ms: 1.03x slower                                   |
| deepcopy                 | 342 us                                                 | 352 us: 1.03x slower                                    |
| unpickle_list            | 4.91 us                                                | 5.05 us: 1.03x slower                                   |
| regex_dna                | 204 ms                                                 | 210 ms: 1.03x slower                                    |
| pathlib                  | 18.2 ms                                                | 18.8 ms: 1.03x slower                                   |
| pickle_pure_python       | 306 us                                                 | 316 us: 1.03x slower                                    |
| docutils                 | 2.63 sec                                               | 2.72 sec: 1.04x slower                                  |
| float                    | 77.2 ms                                                | 80.1 ms: 1.04x slower                                   |
| 2to3                     | 259 ms                                                 | 269 ms: 1.04x slower                                    |
| pprint_pformat           | 1.46 sec                                               | 1.52 sec: 1.04x slower                                  |
| tornado_http             | 96.3 ms                                                | 100 ms: 1.04x slower                                    |
| regex_compile            | 138 ms                                                 | 144 ms: 1.04x slower                                    |
| scimark_monte_carlo      | 68.1 ms                                                | 71.1 ms: 1.05x slower                                   |
| telco                    | 6.58 ms                                                | 6.88 ms: 1.05x slower                                   |
| scimark_lu               | 110 ms                                                 | 115 ms: 1.05x slower                                    |
| sqlalchemy_declarative   | 138 ms                                                 | 145 ms: 1.05x slower                                    |
| pickle                   | 10.1 us                                                | 10.6 us: 1.05x slower                                   |
| pickle_dict              | 31.1 us                                                | 32.7 us: 1.05x slower                                   |
| deepcopy_reduce          | 2.94 us                                                | 3.11 us: 1.06x slower                                   |
| pprint_safe_repr         | 701 ms                                                 | 742 ms: 1.06x slower                                    |
| spectral_norm            | 100 ms                                                 | 106 ms: 1.06x slower                                    |
| scimark_sor              | 118 ms                                                 | 125 ms: 1.06x slower                                    |
| crypto_pyaes             | 74.7 ms                                                | 79.1 ms: 1.06x slower                                   |
| logging_simple           | 6.03 us                                                | 6.40 us: 1.06x slower                                   |
| mako                     | 10.1 ms                                                | 10.7 ms: 1.06x slower                                   |
| pyflate                  | 418 ms                                                 | 446 ms: 1.07x slower                                    |
| dulwich_log              | 63.7 ms                                                | 68.1 ms: 1.07x slower                                   |
| logging_format           | 6.68 us                                                | 7.16 us: 1.07x slower                                   |
| unpickle                 | 13.7 us                                                | 14.9 us: 1.09x slower                                   |
| sqlite_synth             | 2.52 us                                                | 2.76 us: 1.09x slower                                   |
| scimark_fft              | 328 ms                                                 | 359 ms: 1.09x slower                                    |
| xml_etree_process        | 53.9 ms                                                | 59.0 ms: 1.10x slower                                   |
| xml_etree_generate       | 76.2 ms                                                | 84.6 ms: 1.11x slower                                   |
| python_startup           | 8.52 ms                                                | 9.48 ms: 1.11x slower                                   |
| scimark_sparse_mat_mult  | 4.50 ms                                                | 5.12 ms: 1.14x slower                                   |
| pickle_list              | 4.11 us                                                | 4.70 us: 1.14x slower                                   |
| python_startup_no_site   | 6.01 ms                                                | 6.90 ms: 1.15x slower                                   |
| async_generators         | 368 ms                                                 | 449 ms: 1.22x slower                                    |
| unpack_sequence          | 43.1 ns                                                | 53.7 ns: 1.25x slower                                   |
| Geometric mean           | (ref)                                                  | 1.03x faster                                            |

Benchmark hidden because not significant (6): nbody, tomli_loads, bench_mp_pool, xml_etree_iterparse, regex_v8, logging_silent
Ignored benchmarks (15) of results/bm-20221024-3.11.0-deaf509/bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 71.92% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
