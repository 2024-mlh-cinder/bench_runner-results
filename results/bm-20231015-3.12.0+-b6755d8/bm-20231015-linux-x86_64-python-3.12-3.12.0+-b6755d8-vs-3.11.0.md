
# Results vs. 3.11.0

- fork: python
- ref: 3.12
- machine: linux-x86_64
- commit hash: b6755d8
- commit date: 2023-10-15
- overall geometric mean: 1.01x slower
- HPT reliability: 99.98%
- HPT 99th percentile: 1.01x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231015-linux-x86_64-python-3.12-3.12.0+-b6755d8 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------:|
| 2to3           | 259 ms                                                 | 276 ms: 1.07x slower                                 |
| docutils       | 2.63 sec                                               | 2.78 sec: 1.06x slower                               |
| tornado_http   | 96.3 ms                                                | 107 ms: 1.12x slower                                 |
| Geometric mean | (ref)                                                  | 1.08x slower                                         |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231015-linux-x86_64-python-3.12-3.12.0+-b6755d8 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------:|
| pidigits       | 198 ms                                                 | 188 ms: 1.05x faster                                 |
| nbody          | 93.1 ms                                                | 93.9 ms: 1.01x slower                                |
| float          | 77.2 ms                                                | 83.7 ms: 1.08x slower                                |
| Geometric mean | (ref)                                                  | 1.01x slower                                         |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231015-linux-x86_64-python-3.12-3.12.0+-b6755d8 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------:|
| regex_effbot   | 3.99 ms                                                | 3.63 ms: 1.10x faster                                |
| regex_dna      | 204 ms                                                 | 209 ms: 1.03x slower                                 |
| regex_v8       | 22.0 ms                                                | 23.1 ms: 1.05x slower                                |
| regex_compile  | 138 ms                                                 | 148 ms: 1.07x slower                                 |
| Geometric mean | (ref)                                                  | 1.01x slower                                         |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231015-linux-x86_64-python-3.12-3.12.0+-b6755d8 |
|----------------------|:------------------------------------------------------:|:----------------------------------------------------:|
| json_dumps           | 12.6 ms                                                | 10.5 ms: 1.20x faster                                |
| unpickle_pure_python | 228 us                                                 | 230 us: 1.01x slower                                 |
| xml_etree_parse      | 158 ms                                                 | 162 ms: 1.02x slower                                 |
| xml_etree_iterparse  | 104 ms                                                 | 106 ms: 1.02x slower                                 |
| unpickle_list        | 4.91 us                                                | 5.21 us: 1.06x slower                                |
| pickle_pure_python   | 306 us                                                 | 325 us: 1.06x slower                                 |
| json_loads           | 26.5 us                                                | 28.5 us: 1.08x slower                                |
| pickle_dict          | 31.1 us                                                | 35.1 us: 1.13x slower                                |
| pickle               | 10.1 us                                                | 11.4 us: 1.13x slower                                |
| xml_etree_process    | 53.9 ms                                                | 61.0 ms: 1.13x slower                                |
| xml_etree_generate   | 76.2 ms                                                | 88.8 ms: 1.16x slower                                |
| unpickle             | 13.7 us                                                | 15.9 us: 1.17x slower                                |
| pickle_list          | 4.11 us                                                | 5.09 us: 1.24x slower                                |
| Geometric mean       | (ref)                                                  | 1.07x slower                                         |

Benchmark hidden because not significant (1): tomli_loads

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231015-linux-x86_64-python-3.12-3.12.0+-b6755d8 |
|------------------------|:------------------------------------------------------:|:----------------------------------------------------:|
| python_startup         | 8.52 ms                                                | 9.70 ms: 1.14x slower                                |
| python_startup_no_site | 6.01 ms                                                | 7.00 ms: 1.17x slower                                |
| Geometric mean         | (ref)                                                  | 1.15x slower                                         |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231015-linux-x86_64-python-3.12-3.12.0+-b6755d8 |
|-----------|:------------------------------------------------------:|:----------------------------------------------------:|
| mako      | 10.1 ms                                                | 11.3 ms: 1.12x slower                                |

All benchmarks:
===============

| Benchmark                | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231015-linux-x86_64-python-3.12-3.12.0+-b6755d8 |
|--------------------------|:------------------------------------------------------:|:----------------------------------------------------:|
| typing_runtime_protocols | 486 us                                                 | 157 us: 3.11x faster                                 |
| generators               | 73.5 ms                                                | 31.5 ms: 2.33x faster                                |
| asyncio_tcp              | 922 ms                                                 | 509 ms: 1.81x faster                                 |
| asyncio_tcp_ssl          | 3.14 sec                                               | 1.78 sec: 1.76x faster                               |
| json_dumps               | 12.6 ms                                                | 10.5 ms: 1.20x faster                                |
| coroutines               | 25.5 ms                                                | 22.5 ms: 1.13x faster                                |
| async_tree_io            | 1.30 sec                                               | 1.16 sec: 1.12x faster                               |
| async_tree_none          | 526 ms                                                 | 471 ms: 1.12x faster                                 |
| richards_super           | 56.8 ms                                                | 51.0 ms: 1.11x faster                                |
| regex_effbot             | 3.99 ms                                                | 3.63 ms: 1.10x faster                                |
| async_tree_memoization   | 627 ms                                                 | 576 ms: 1.09x faster                                 |
| pidigits                 | 198 ms                                                 | 188 ms: 1.05x faster                                 |
| comprehensions           | 22.4 us                                                | 21.5 us: 1.05x faster                                |
| chaos                    | 69.2 ms                                                | 66.6 ms: 1.04x faster                                |
| async_tree_cpu_io_mixed  | 739 ms                                                 | 725 ms: 1.02x faster                                 |
| mdp                      | 2.62 sec                                               | 2.57 sec: 1.02x faster                               |
| richards                 | 45.7 ms                                                | 45.0 ms: 1.02x faster                                |
| coverage                 | 100 ms                                                 | 98.5 ms: 1.02x faster                                |
| sqlglot_parse            | 1.40 ms                                                | 1.39 ms: 1.01x faster                                |
| create_gc_cycles         | 1.49 ms                                                | 1.49 ms: 1.00x slower                                |
| nqueens                  | 83.4 ms                                                | 83.8 ms: 1.01x slower                                |
| unpickle_pure_python     | 228 us                                                 | 230 us: 1.01x slower                                 |
| nbody                    | 93.1 ms                                                | 93.9 ms: 1.01x slower                                |
| sqlglot_transpile        | 1.70 ms                                                | 1.72 ms: 1.01x slower                                |
| meteor_contest           | 107 ms                                                 | 108 ms: 1.01x slower                                 |
| hexiom                   | 6.37 ms                                                | 6.49 ms: 1.02x slower                                |
| xml_etree_parse          | 158 ms                                                 | 162 ms: 1.02x slower                                 |
| go                       | 140 ms                                                 | 143 ms: 1.02x slower                                 |
| gc_traversal             | 4.02 ms                                                | 4.11 ms: 1.02x slower                                |
| fannkuch                 | 388 ms                                                 | 397 ms: 1.02x slower                                 |
| xml_etree_iterparse      | 104 ms                                                 | 106 ms: 1.02x slower                                 |
| regex_dna                | 204 ms                                                 | 209 ms: 1.03x slower                                 |
| pathlib                  | 18.2 ms                                                | 18.8 ms: 1.03x slower                                |
| sqlglot_normalize        | 108 ms                                                 | 112 ms: 1.04x slower                                 |
| sqlglot_optimize         | 53.1 ms                                                | 55.1 ms: 1.04x slower                                |
| bench_thread_pool        | 819 us                                                 | 852 us: 1.04x slower                                 |
| dask                     | 360 ms                                                 | 375 ms: 1.04x slower                                 |
| raytrace                 | 297 ms                                                 | 310 ms: 1.05x slower                                 |
| regex_v8                 | 22.0 ms                                                | 23.1 ms: 1.05x slower                                |
| docutils                 | 2.63 sec                                               | 2.78 sec: 1.06x slower                               |
| unpickle_list            | 4.91 us                                                | 5.21 us: 1.06x slower                                |
| pickle_pure_python       | 306 us                                                 | 325 us: 1.06x slower                                 |
| pprint_pformat           | 1.46 sec                                               | 1.55 sec: 1.07x slower                               |
| 2to3                     | 259 ms                                                 | 276 ms: 1.07x slower                                 |
| telco                    | 6.58 ms                                                | 7.03 ms: 1.07x slower                                |
| json                     | 4.94 ms                                                | 5.28 ms: 1.07x slower                                |
| regex_compile            | 138 ms                                                 | 148 ms: 1.07x slower                                 |
| sqlalchemy_declarative   | 138 ms                                                 | 148 ms: 1.07x slower                                 |
| scimark_lu               | 110 ms                                                 | 118 ms: 1.07x slower                                 |
| json_loads               | 26.5 us                                                | 28.5 us: 1.08x slower                                |
| scimark_monte_carlo      | 68.1 ms                                                | 73.4 ms: 1.08x slower                                |
| logging_silent           | 101 ns                                                 | 109 ns: 1.08x slower                                 |
| float                    | 77.2 ms                                                | 83.7 ms: 1.08x slower                                |
| logging_simple           | 6.03 us                                                | 6.54 us: 1.08x slower                                |
| deepcopy                 | 342 us                                                 | 372 us: 1.09x slower                                 |
| pprint_safe_repr         | 701 ms                                                 | 765 ms: 1.09x slower                                 |
| logging_format           | 6.68 us                                                | 7.30 us: 1.09x slower                                |
| pyflate                  | 418 ms                                                 | 458 ms: 1.10x slower                                 |
| deepcopy_memo            | 37.0 us                                                | 40.8 us: 1.10x slower                                |
| scimark_sor              | 118 ms                                                 | 130 ms: 1.10x slower                                 |
| crypto_pyaes             | 74.7 ms                                                | 82.8 ms: 1.11x slower                                |
| spectral_norm            | 100 ms                                                 | 112 ms: 1.12x slower                                 |
| tornado_http             | 96.3 ms                                                | 107 ms: 1.12x slower                                 |
| mako                     | 10.1 ms                                                | 11.3 ms: 1.12x slower                                |
| scimark_fft              | 328 ms                                                 | 370 ms: 1.13x slower                                 |
| pickle_dict              | 31.1 us                                                | 35.1 us: 1.13x slower                                |
| deepcopy_reduce          | 2.94 us                                                | 3.32 us: 1.13x slower                                |
| pickle                   | 10.1 us                                                | 11.4 us: 1.13x slower                                |
| xml_etree_process        | 53.9 ms                                                | 61.0 ms: 1.13x slower                                |
| python_startup           | 8.52 ms                                                | 9.70 ms: 1.14x slower                                |
| sqlite_synth             | 2.52 us                                                | 2.89 us: 1.15x slower                                |
| scimark_sparse_mat_mult  | 4.50 ms                                                | 5.17 ms: 1.15x slower                                |
| xml_etree_generate       | 76.2 ms                                                | 88.8 ms: 1.16x slower                                |
| unpickle                 | 13.7 us                                                | 15.9 us: 1.17x slower                                |
| python_startup_no_site   | 6.01 ms                                                | 7.00 ms: 1.17x slower                                |
| sqlalchemy_imperative    | 17.9 ms                                                | 20.9 ms: 1.17x slower                                |
| dulwich_log              | 63.7 ms                                                | 74.4 ms: 1.17x slower                                |
| pickle_list              | 4.11 us                                                | 5.09 us: 1.24x slower                                |
| unpack_sequence          | 43.1 ns                                                | 53.3 ns: 1.24x slower                                |
| async_generators         | 368 ms                                                 | 462 ms: 1.25x slower                                 |
| Geometric mean           | (ref)                                                  | 1.01x slower                                         |

Benchmark hidden because not significant (5): bench_mp_pool, pycparser, deltablue, tomli_loads, mypy2
Ignored benchmarks (15) of results/bm-20221024-3.11.0-deaf509/bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 99.98% likely to be slow
- 90% likely to have a slowdown of 1.02x
- 95% likely to have a slowdown of 1.01x
- 99% likely to have a slowdown of 1.01x
