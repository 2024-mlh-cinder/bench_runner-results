
# Results vs. 3.11.0

- fork: python
- ref: main
- machine: linux-x86_64
- commit hash: 8e56d55
- commit date: 2023-10-07
- overall geometric mean: 1.02x faster
- HPT reliability: 82.50%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

Benchmark hidden because not significant (2): docutils, tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231007-linux-x86_64-python-main-3.13.0a0-8e56d55 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| pidigits       | 198 ms                                                 | 187 ms: 1.06x faster                                  |
| nbody          | 93.1 ms                                                | 91.4 ms: 1.02x faster                                 |
| float          | 77.2 ms                                                | 82.7 ms: 1.07x slower                                 |
| Geometric mean | (ref)                                                  | 1.00x faster                                          |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231007-linux-x86_64-python-main-3.13.0a0-8e56d55 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| regex_effbot   | 3.99 ms                                                | 3.65 ms: 1.09x faster                                 |
| regex_compile  | 138 ms                                                 | 139 ms: 1.00x slower                                  |
| regex_dna      | 204 ms                                                 | 211 ms: 1.04x slower                                  |
| regex_v8       | 22.0 ms                                                | 25.5 ms: 1.16x slower                                 |
| Geometric mean | (ref)                                                  | 1.02x slower                                          |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231007-linux-x86_64-python-main-3.13.0a0-8e56d55 |
|----------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| json_dumps           | 12.6 ms                                                | 10.5 ms: 1.20x faster                                 |
| tomli_loads          | 2.22 sec                                               | 2.17 sec: 1.02x faster                                |
| unpickle_pure_python | 228 us                                                 | 225 us: 1.01x faster                                  |
| xml_etree_iterparse  | 104 ms                                                 | 105 ms: 1.01x slower                                  |
| unpickle_list        | 4.91 us                                                | 5.08 us: 1.03x slower                                 |
| json_loads           | 26.5 us                                                | 28.4 us: 1.07x slower                                 |
| unpickle             | 13.7 us                                                | 14.9 us: 1.09x slower                                 |
| pickle_dict          | 31.1 us                                                | 34.2 us: 1.10x slower                                 |
| xml_etree_process    | 53.9 ms                                                | 59.6 ms: 1.11x slower                                 |
| xml_etree_generate   | 76.2 ms                                                | 86.7 ms: 1.14x slower                                 |
| pickle               | 10.1 us                                                | 11.6 us: 1.15x slower                                 |
| pickle_list          | 4.11 us                                                | 5.18 us: 1.26x slower                                 |
| Geometric mean       | (ref)                                                  | 1.05x slower                                          |

Benchmark hidden because not significant (2): xml_etree_parse, pickle_pure_python

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231007-linux-x86_64-python-main-3.13.0a0-8e56d55 |
|------------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| python_startup_no_site | 6.01 ms                                                | 6.85 ms: 1.14x slower                                 |
| python_startup         | 8.52 ms                                                | 10.1 ms: 1.18x slower                                 |
| Geometric mean         | (ref)                                                  | 1.16x slower                                          |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231007-linux-x86_64-python-main-3.13.0a0-8e56d55 |
|-----------|:------------------------------------------------------:|:-----------------------------------------------------:|
| mako      | 10.1 ms                                                | 11.8 ms: 1.17x slower                                 |

All benchmarks:
===============

| Benchmark                | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231007-linux-x86_64-python-main-3.13.0a0-8e56d55 |
|--------------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| typing_runtime_protocols | 486 us                                                 | 154 us: 3.16x faster                                  |
| generators               | 73.5 ms                                                | 29.0 ms: 2.53x faster                                 |
| asyncio_tcp              | 922 ms                                                 | 474 ms: 1.95x faster                                  |
| asyncio_tcp_ssl          | 3.14 sec                                               | 1.77 sec: 1.77x faster                                |
| mypy2                    | 420 ms                                                 | 344 ms: 1.22x faster                                  |
| json_dumps               | 12.6 ms                                                | 10.5 ms: 1.20x faster                                 |
| async_tree_none          | 526 ms                                                 | 440 ms: 1.19x faster                                  |
| chaos                    | 69.2 ms                                                | 61.8 ms: 1.12x faster                                 |
| async_tree_memoization   | 627 ms                                                 | 567 ms: 1.11x faster                                  |
| coverage                 | 100 ms                                                 | 90.4 ms: 1.11x faster                                 |
| deltablue                | 3.67 ms                                                | 3.32 ms: 1.10x faster                                 |
| coroutines               | 25.5 ms                                                | 23.3 ms: 1.09x faster                                 |
| regex_effbot             | 3.99 ms                                                | 3.65 ms: 1.09x faster                                 |
| sqlglot_parse            | 1.40 ms                                                | 1.29 ms: 1.09x faster                                 |
| async_tree_io            | 1.30 sec                                               | 1.19 sec: 1.09x faster                                |
| raytrace                 | 297 ms                                                 | 278 ms: 1.07x faster                                  |
| comprehensions           | 22.4 us                                                | 21.1 us: 1.06x faster                                 |
| sqlglot_transpile        | 1.70 ms                                                | 1.61 ms: 1.06x faster                                 |
| pidigits                 | 198 ms                                                 | 187 ms: 1.06x faster                                  |
| richards_super           | 56.8 ms                                                | 54.2 ms: 1.05x faster                                 |
| nqueens                  | 83.4 ms                                                | 79.8 ms: 1.05x faster                                 |
| gc_traversal             | 4.02 ms                                                | 3.85 ms: 1.04x faster                                 |
| async_tree_cpu_io_mixed  | 739 ms                                                 | 714 ms: 1.03x faster                                  |
| logging_format           | 6.68 us                                                | 6.48 us: 1.03x faster                                 |
| logging_simple           | 6.03 us                                                | 5.86 us: 1.03x faster                                 |
| crypto_pyaes             | 74.7 ms                                                | 72.8 ms: 1.03x faster                                 |
| tomli_loads              | 2.22 sec                                               | 2.17 sec: 1.02x faster                                |
| nbody                    | 93.1 ms                                                | 91.4 ms: 1.02x faster                                 |
| sqlglot_normalize        | 108 ms                                                 | 106 ms: 1.01x faster                                  |
| unpickle_pure_python     | 228 us                                                 | 225 us: 1.01x faster                                  |
| hexiom                   | 6.37 ms                                                | 6.31 ms: 1.01x faster                                 |
| bench_thread_pool        | 819 us                                                 | 813 us: 1.01x faster                                  |
| mdp                      | 2.62 sec                                               | 2.60 sec: 1.01x faster                                |
| regex_compile            | 138 ms                                                 | 139 ms: 1.00x slower                                  |
| xml_etree_iterparse      | 104 ms                                                 | 105 ms: 1.01x slower                                  |
| sqlglot_optimize         | 53.1 ms                                                | 53.6 ms: 1.01x slower                                 |
| scimark_monte_carlo      | 68.1 ms                                                | 69.2 ms: 1.02x slower                                 |
| meteor_contest           | 107 ms                                                 | 109 ms: 1.02x slower                                  |
| pycparser                | 1.18 sec                                               | 1.21 sec: 1.03x slower                                |
| create_gc_cycles         | 1.49 ms                                                | 1.53 ms: 1.03x slower                                 |
| unpickle_list            | 4.91 us                                                | 5.08 us: 1.03x slower                                 |
| regex_dna                | 204 ms                                                 | 211 ms: 1.04x slower                                  |
| deepcopy                 | 342 us                                                 | 355 us: 1.04x slower                                  |
| json                     | 4.94 ms                                                | 5.14 ms: 1.04x slower                                 |
| pprint_pformat           | 1.46 sec                                               | 1.52 sec: 1.04x slower                                |
| pathlib                  | 18.2 ms                                                | 19.0 ms: 1.04x slower                                 |
| go                       | 140 ms                                                 | 146 ms: 1.04x slower                                  |
| richards                 | 45.7 ms                                                | 47.8 ms: 1.04x slower                                 |
| scimark_sparse_mat_mult  | 4.50 ms                                                | 4.70 ms: 1.05x slower                                 |
| scimark_lu               | 110 ms                                                 | 115 ms: 1.05x slower                                  |
| deepcopy_memo            | 37.0 us                                                | 38.9 us: 1.05x slower                                 |
| dulwich_log              | 63.7 ms                                                | 67.4 ms: 1.06x slower                                 |
| pprint_safe_repr         | 701 ms                                                 | 744 ms: 1.06x slower                                  |
| fannkuch                 | 388 ms                                                 | 412 ms: 1.06x slower                                  |
| scimark_sor              | 118 ms                                                 | 126 ms: 1.06x slower                                  |
| logging_silent           | 101 ns                                                 | 107 ns: 1.06x slower                                  |
| float                    | 77.2 ms                                                | 82.7 ms: 1.07x slower                                 |
| json_loads               | 26.5 us                                                | 28.4 us: 1.07x slower                                 |
| deepcopy_reduce          | 2.94 us                                                | 3.19 us: 1.09x slower                                 |
| unpickle                 | 13.7 us                                                | 14.9 us: 1.09x slower                                 |
| pickle_dict              | 31.1 us                                                | 34.2 us: 1.10x slower                                 |
| xml_etree_process        | 53.9 ms                                                | 59.6 ms: 1.11x slower                                 |
| pyflate                  | 418 ms                                                 | 465 ms: 1.11x slower                                  |
| scimark_fft              | 328 ms                                                 | 370 ms: 1.13x slower                                  |
| sqlite_synth             | 2.52 us                                                | 2.85 us: 1.13x slower                                 |
| spectral_norm            | 100 ms                                                 | 114 ms: 1.14x slower                                  |
| xml_etree_generate       | 76.2 ms                                                | 86.7 ms: 1.14x slower                                 |
| python_startup_no_site   | 6.01 ms                                                | 6.85 ms: 1.14x slower                                 |
| pickle                   | 10.1 us                                                | 11.6 us: 1.15x slower                                 |
| regex_v8                 | 22.0 ms                                                | 25.5 ms: 1.16x slower                                 |
| mako                     | 10.1 ms                                                | 11.8 ms: 1.17x slower                                 |
| python_startup           | 8.52 ms                                                | 10.1 ms: 1.18x slower                                 |
| telco                    | 6.58 ms                                                | 8.23 ms: 1.25x slower                                 |
| pickle_list              | 4.11 us                                                | 5.18 us: 1.26x slower                                 |
| async_generators         | 368 ms                                                 | 471 ms: 1.28x slower                                  |
| unpack_sequence          | 43.1 ns                                                | 55.1 ns: 1.28x slower                                 |
| Geometric mean           | (ref)                                                  | 1.02x faster                                          |

Benchmark hidden because not significant (5): xml_etree_parse, bench_mp_pool, tornado_http, pickle_pure_python, docutils
Ignored benchmarks (19) of results/bm-20221024-3.11.0-deaf509/bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509.json: 2to3, aiohttp, chameleon, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 82.50% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
