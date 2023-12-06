
# Results vs. 3.11.0

- fork: gvanrossum
- ref: uops_forever
- machine: linux-x86_64
- commit hash: fa8a0d5
- commit date: 2023-09-26
- overall geometric mean: 1.02x slower
- HPT reliability: 99.95%
- HPT 99th percentile: 1.01x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230926-linux-x86_64-gvanrossum-uops_forever-3.13.0a0-fa8a0d5 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------:|
| docutils       | 2.63 sec                                               | 2.74 sec: 1.04x slower                                            |
| tornado_http   | 96.3 ms                                                | 99.4 ms: 1.03x slower                                             |
| Geometric mean | (ref)                                                  | 1.04x slower                                                      |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230926-linux-x86_64-gvanrossum-uops_forever-3.13.0a0-fa8a0d5 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------:|
| pidigits       | 198 ms                                                 | 188 ms: 1.05x faster                                              |
| float          | 77.2 ms                                                | 99.0 ms: 1.28x slower                                             |
| nbody          | 93.1 ms                                                | 120 ms: 1.28x slower                                              |
| Geometric mean | (ref)                                                  | 1.16x slower                                                      |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230926-linux-x86_64-gvanrossum-uops_forever-3.13.0a0-fa8a0d5 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------:|
| regex_effbot   | 3.99 ms                                                | 3.44 ms: 1.16x faster                                             |
| regex_dna      | 204 ms                                                 | 205 ms: 1.01x slower                                              |
| regex_v8       | 22.0 ms                                                | 23.5 ms: 1.06x slower                                             |
| regex_compile  | 138 ms                                                 | 157 ms: 1.14x slower                                              |
| Geometric mean | (ref)                                                  | 1.01x slower                                                      |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230926-linux-x86_64-gvanrossum-uops_forever-3.13.0a0-fa8a0d5 |
|----------------------|:------------------------------------------------------:|:-----------------------------------------------------------------:|
| json_dumps           | 12.6 ms                                                | 9.87 ms: 1.28x faster                                             |
| xml_etree_parse      | 158 ms                                                 | 152 ms: 1.05x faster                                              |
| json_loads           | 26.5 us                                                | 25.4 us: 1.04x faster                                             |
| pickle_pure_python   | 306 us                                                 | 299 us: 1.02x faster                                              |
| unpickle_pure_python | 228 us                                                 | 233 us: 1.02x slower                                              |
| xml_etree_iterparse  | 104 ms                                                 | 107 ms: 1.03x slower                                              |
| unpickle_list        | 4.91 us                                                | 5.17 us: 1.05x slower                                             |
| pickle_dict          | 31.1 us                                                | 32.9 us: 1.06x slower                                             |
| xml_etree_process    | 53.9 ms                                                | 57.8 ms: 1.07x slower                                             |
| tomli_loads          | 2.22 sec                                               | 2.39 sec: 1.08x slower                                            |
| pickle               | 10.1 us                                                | 11.0 us: 1.09x slower                                             |
| xml_etree_generate   | 76.2 ms                                                | 84.5 ms: 1.11x slower                                             |
| pickle_list          | 4.11 us                                                | 4.64 us: 1.13x slower                                             |
| unpickle             | 13.7 us                                                | 15.9 us: 1.16x slower                                             |
| Geometric mean       | (ref)                                                  | 1.03x slower                                                      |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230926-linux-x86_64-gvanrossum-uops_forever-3.13.0a0-fa8a0d5 |
|------------------------|:------------------------------------------------------:|:-----------------------------------------------------------------:|
| python_startup_no_site | 6.01 ms                                                | 6.84 ms: 1.14x slower                                             |
| python_startup         | 8.52 ms                                                | 10.1 ms: 1.18x slower                                             |
| Geometric mean         | (ref)                                                  | 1.16x slower                                                      |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230926-linux-x86_64-gvanrossum-uops_forever-3.13.0a0-fa8a0d5 |
|-----------|:------------------------------------------------------:|:-----------------------------------------------------------------:|
| mako      | 10.1 ms                                                | 12.0 ms: 1.19x slower                                             |

All benchmarks:
===============

| Benchmark                | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230926-linux-x86_64-gvanrossum-uops_forever-3.13.0a0-fa8a0d5 |
|--------------------------|:------------------------------------------------------:|:-----------------------------------------------------------------:|
| typing_runtime_protocols | 486 us                                                 | 150 us: 3.23x faster                                              |
| generators               | 73.5 ms                                                | 30.0 ms: 2.45x faster                                             |
| asyncio_tcp              | 922 ms                                                 | 511 ms: 1.80x faster                                              |
| asyncio_tcp_ssl          | 3.14 sec                                               | 1.82 sec: 1.73x faster                                            |
| json_dumps               | 12.6 ms                                                | 9.87 ms: 1.28x faster                                             |
| mypy2                    | 420 ms                                                 | 351 ms: 1.20x faster                                              |
| async_tree_none          | 526 ms                                                 | 450 ms: 1.17x faster                                              |
| coverage                 | 100 ms                                                 | 85.5 ms: 1.17x faster                                             |
| coroutines               | 25.5 ms                                                | 21.9 ms: 1.16x faster                                             |
| regex_effbot             | 3.99 ms                                                | 3.44 ms: 1.16x faster                                             |
| async_tree_memoization   | 627 ms                                                 | 576 ms: 1.09x faster                                              |
| async_tree_io            | 1.30 sec                                               | 1.19 sec: 1.09x faster                                            |
| pidigits                 | 198 ms                                                 | 188 ms: 1.05x faster                                              |
| sqlglot_parse            | 1.40 ms                                                | 1.33 ms: 1.05x faster                                             |
| xml_etree_parse          | 158 ms                                                 | 152 ms: 1.05x faster                                              |
| json_loads               | 26.5 us                                                | 25.4 us: 1.04x faster                                             |
| gc_traversal             | 4.02 ms                                                | 3.87 ms: 1.04x faster                                             |
| async_tree_cpu_io_mixed  | 739 ms                                                 | 717 ms: 1.03x faster                                              |
| sqlglot_transpile        | 1.70 ms                                                | 1.65 ms: 1.03x faster                                             |
| pickle_pure_python       | 306 us                                                 | 299 us: 1.02x faster                                              |
| crypto_pyaes             | 74.7 ms                                                | 73.2 ms: 1.02x faster                                             |
| sqlglot_normalize        | 108 ms                                                 | 107 ms: 1.01x faster                                              |
| regex_dna                | 204 ms                                                 | 205 ms: 1.01x slower                                              |
| raytrace                 | 297 ms                                                 | 299 ms: 1.01x slower                                              |
| pycparser                | 1.18 sec                                               | 1.19 sec: 1.01x slower                                            |
| logging_simple           | 6.03 us                                                | 6.11 us: 1.01x slower                                             |
| create_gc_cycles         | 1.49 ms                                                | 1.51 ms: 1.02x slower                                             |
| logging_silent           | 101 ns                                                 | 103 ns: 1.02x slower                                              |
| mdp                      | 2.62 sec                                               | 2.67 sec: 1.02x slower                                            |
| logging_format           | 6.68 us                                                | 6.83 us: 1.02x slower                                             |
| unpickle_pure_python     | 228 us                                                 | 233 us: 1.02x slower                                              |
| bench_thread_pool        | 819 us                                                 | 839 us: 1.02x slower                                              |
| sqlglot_optimize         | 53.1 ms                                                | 54.6 ms: 1.03x slower                                             |
| scimark_sor              | 118 ms                                                 | 122 ms: 1.03x slower                                              |
| tornado_http             | 96.3 ms                                                | 99.4 ms: 1.03x slower                                             |
| xml_etree_iterparse      | 104 ms                                                 | 107 ms: 1.03x slower                                              |
| docutils                 | 2.63 sec                                               | 2.74 sec: 1.04x slower                                            |
| pathlib                  | 18.2 ms                                                | 19.0 ms: 1.04x slower                                             |
| deepcopy                 | 342 us                                                 | 357 us: 1.04x slower                                              |
| unpickle_list            | 4.91 us                                                | 5.17 us: 1.05x slower                                             |
| chaos                    | 69.2 ms                                                | 73.1 ms: 1.06x slower                                             |
| pickle_dict              | 31.1 us                                                | 32.9 us: 1.06x slower                                             |
| scimark_lu               | 110 ms                                                 | 117 ms: 1.06x slower                                              |
| regex_v8                 | 22.0 ms                                                | 23.5 ms: 1.06x slower                                             |
| sqlite_synth             | 2.52 us                                                | 2.70 us: 1.07x slower                                             |
| xml_etree_process        | 53.9 ms                                                | 57.8 ms: 1.07x slower                                             |
| scimark_monte_carlo      | 68.1 ms                                                | 73.2 ms: 1.08x slower                                             |
| meteor_contest           | 107 ms                                                 | 115 ms: 1.08x slower                                              |
| tomli_loads              | 2.22 sec                                               | 2.39 sec: 1.08x slower                                            |
| deepcopy_reduce          | 2.94 us                                                | 3.18 us: 1.08x slower                                             |
| dulwich_log              | 63.7 ms                                                | 69.2 ms: 1.09x slower                                             |
| go                       | 140 ms                                                 | 152 ms: 1.09x slower                                              |
| pickle                   | 10.1 us                                                | 11.0 us: 1.09x slower                                             |
| spectral_norm            | 100 ms                                                 | 110 ms: 1.10x slower                                              |
| richards                 | 45.7 ms                                                | 50.6 ms: 1.11x slower                                             |
| xml_etree_generate       | 76.2 ms                                                | 84.5 ms: 1.11x slower                                             |
| deepcopy_memo            | 37.0 us                                                | 41.1 us: 1.11x slower                                             |
| deltablue                | 3.67 ms                                                | 4.09 ms: 1.11x slower                                             |
| pickle_list              | 4.11 us                                                | 4.64 us: 1.13x slower                                             |
| pprint_pformat           | 1.46 sec                                               | 1.66 sec: 1.14x slower                                            |
| python_startup_no_site   | 6.01 ms                                                | 6.84 ms: 1.14x slower                                             |
| regex_compile            | 138 ms                                                 | 157 ms: 1.14x slower                                              |
| pprint_safe_repr         | 701 ms                                                 | 799 ms: 1.14x slower                                              |
| fannkuch                 | 388 ms                                                 | 449 ms: 1.16x slower                                              |
| unpickle                 | 13.7 us                                                | 15.9 us: 1.16x slower                                             |
| python_startup           | 8.52 ms                                                | 10.1 ms: 1.18x slower                                             |
| unpack_sequence          | 43.1 ns                                                | 50.9 ns: 1.18x slower                                             |
| nqueens                  | 83.4 ms                                                | 98.7 ms: 1.18x slower                                             |
| mako                     | 10.1 ms                                                | 12.0 ms: 1.19x slower                                             |
| comprehensions           | 22.4 us                                                | 27.1 us: 1.21x slower                                             |
| async_generators         | 368 ms                                                 | 459 ms: 1.25x slower                                              |
| telco                    | 6.58 ms                                                | 8.29 ms: 1.26x slower                                             |
| float                    | 77.2 ms                                                | 99.0 ms: 1.28x slower                                             |
| nbody                    | 93.1 ms                                                | 120 ms: 1.28x slower                                              |
| scimark_sparse_mat_mult  | 4.50 ms                                                | 5.83 ms: 1.30x slower                                             |
| pyflate                  | 418 ms                                                 | 547 ms: 1.31x slower                                              |
| scimark_fft              | 328 ms                                                 | 431 ms: 1.31x slower                                              |
| hexiom                   | 6.37 ms                                                | 9.03 ms: 1.42x slower                                             |
| dask                     | 360 ms                                                 | 538 ms: 1.50x slower                                              |
| Geometric mean           | (ref)                                                  | 1.02x slower                                                      |

Benchmark hidden because not significant (3): json, bench_mp_pool, richards_super
Ignored benchmarks (18) of results/bm-20221024-3.11.0-deaf509/bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509.json: 2to3, aiohttp, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 99.95% likely to be slow
- 90% likely to have a slowdown of 1.02x
- 95% likely to have a slowdown of 1.02x
- 99% likely to have a slowdown of 1.01x
