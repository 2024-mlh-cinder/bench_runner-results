
# Results vs. 3.11.0

- fork: mdboom
- ref: collect_tier2_stats
- machine: linux-x86_64
- commit hash: 3f2d583
- commit date: 2023-10-04
- overall geometric mean: 1.01x slower
- HPT reliability: 98.30%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231004-pythonperf2-x86_64-mdboom-collect_tier2_stats-3.13.0a0-3f2d583 |
|----------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------:|
| docutils       | 2.86 sec                                                     | 3.01 sec: 1.05x slower                                                     |
| tornado_http   | 122 ms                                                       | 125 ms: 1.03x slower                                                       |
| Geometric mean | (ref)                                                        | 1.04x slower                                                               |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231004-pythonperf2-x86_64-mdboom-collect_tier2_stats-3.13.0a0-3f2d583 |
|----------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------:|
| pidigits       | 251 ms                                                       | 265 ms: 1.06x slower                                                       |
| nbody          | 90.7 ms                                                      | 114 ms: 1.26x slower                                                       |
| float          | 74.2 ms                                                      | 104 ms: 1.40x slower                                                       |
| Geometric mean | (ref)                                                        | 1.23x slower                                                               |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231004-pythonperf2-x86_64-mdboom-collect_tier2_stats-3.13.0a0-3f2d583 |
|----------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------:|
| regex_effbot   | 3.50 ms                                                      | 3.35 ms: 1.05x faster                                                      |
| regex_dna      | 227 ms                                                       | 234 ms: 1.03x slower                                                       |
| regex_v8       | 23.9 ms                                                      | 25.1 ms: 1.05x slower                                                      |
| regex_compile  | 158 ms                                                       | 178 ms: 1.13x slower                                                       |
| Geometric mean | (ref)                                                        | 1.04x slower                                                               |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231004-pythonperf2-x86_64-mdboom-collect_tier2_stats-3.13.0a0-3f2d583 |
|----------------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------:|
| json_dumps           | 13.4 ms                                                      | 10.6 ms: 1.26x faster                                                      |
| json_loads           | 28.7 us                                                      | 24.9 us: 1.15x faster                                                      |
| xml_etree_parse      | 158 ms                                                       | 149 ms: 1.06x faster                                                       |
| unpickle_pure_python | 241 us                                                       | 239 us: 1.01x faster                                                       |
| pickle_pure_python   | 319 us                                                       | 321 us: 1.01x slower                                                       |
| pickle_dict          | 30.8 us                                                      | 32.0 us: 1.04x slower                                                      |
| unpickle_list        | 4.53 us                                                      | 4.73 us: 1.04x slower                                                      |
| xml_etree_process    | 56.5 ms                                                      | 59.2 ms: 1.05x slower                                                      |
| pickle               | 9.64 us                                                      | 10.1 us: 1.05x slower                                                      |
| xml_etree_iterparse  | 104 ms                                                       | 112 ms: 1.07x slower                                                       |
| xml_etree_generate   | 80.5 ms                                                      | 87.0 ms: 1.08x slower                                                      |
| unpickle             | 13.4 us                                                      | 14.6 us: 1.09x slower                                                      |
| pickle_list          | 3.83 us                                                      | 4.27 us: 1.11x slower                                                      |
| tomli_loads          | 2.26 sec                                                     | 2.65 sec: 1.17x slower                                                     |
| Geometric mean       | (ref)                                                        | 1.02x slower                                                               |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231004-pythonperf2-x86_64-mdboom-collect_tier2_stats-3.13.0a0-3f2d583 |
|------------------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------:|
| python_startup_no_site | 7.76 ms                                                      | 8.68 ms: 1.12x slower                                                      |
| python_startup         | 10.8 ms                                                      | 12.6 ms: 1.18x slower                                                      |
| Geometric mean         | (ref)                                                        | 1.15x slower                                                               |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231004-pythonperf2-x86_64-mdboom-collect_tier2_stats-3.13.0a0-3f2d583 |
|-----------|:------------------------------------------------------------:|:--------------------------------------------------------------------------:|
| mako      | 11.0 ms                                                      | 13.7 ms: 1.25x slower                                                      |

All benchmarks:
===============

| Benchmark                | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231004-pythonperf2-x86_64-mdboom-collect_tier2_stats-3.13.0a0-3f2d583 |
|--------------------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------:|
| typing_runtime_protocols | 523 us                                                       | 162 us: 3.22x faster                                                       |
| asyncio_tcp              | 753 ms                                                       | 374 ms: 2.01x faster                                                       |
| asyncio_tcp_ssl          | 3.08 sec                                                     | 1.60 sec: 1.93x faster                                                     |
| generators               | 56.0 ms                                                      | 36.6 ms: 1.53x faster                                                      |
| json_dumps               | 13.4 ms                                                      | 10.6 ms: 1.26x faster                                                      |
| coroutines               | 27.6 ms                                                      | 23.1 ms: 1.20x faster                                                      |
| mypy2                    | 451 ms                                                       | 388 ms: 1.16x faster                                                       |
| json_loads               | 28.7 us                                                      | 24.9 us: 1.15x faster                                                      |
| async_tree_none          | 519 ms                                                       | 456 ms: 1.14x faster                                                       |
| unpack_sequence          | 45.6 ns                                                      | 41.0 ns: 1.11x faster                                                      |
| async_tree_memoization   | 630 ms                                                       | 570 ms: 1.11x faster                                                       |
| chaos                    | 80.9 ms                                                      | 73.2 ms: 1.11x faster                                                      |
| json                     | 5.65 ms                                                      | 5.17 ms: 1.09x faster                                                      |
| raytrace                 | 317 ms                                                       | 297 ms: 1.07x faster                                                       |
| sqlglot_normalize        | 126 ms                                                       | 119 ms: 1.06x faster                                                       |
| scimark_lu               | 115 ms                                                       | 108 ms: 1.06x faster                                                       |
| logging_format           | 8.11 us                                                      | 7.67 us: 1.06x faster                                                      |
| xml_etree_parse          | 158 ms                                                       | 149 ms: 1.06x faster                                                       |
| coverage                 | 84.8 ms                                                      | 80.6 ms: 1.05x faster                                                      |
| async_tree_io            | 1.17 sec                                                     | 1.12 sec: 1.05x faster                                                     |
| sqlglot_parse            | 1.53 ms                                                      | 1.46 ms: 1.05x faster                                                      |
| regex_effbot             | 3.50 ms                                                      | 3.35 ms: 1.05x faster                                                      |
| deepcopy_reduce          | 3.51 us                                                      | 3.37 us: 1.04x faster                                                      |
| deepcopy                 | 399 us                                                       | 385 us: 1.04x faster                                                       |
| async_tree_cpu_io_mixed  | 749 ms                                                       | 726 ms: 1.03x faster                                                       |
| bench_thread_pool        | 1.01 ms                                                      | 983 us: 1.03x faster                                                       |
| sqlglot_transpile        | 1.92 ms                                                      | 1.88 ms: 1.02x faster                                                      |
| logging_simple           | 7.19 us                                                      | 7.07 us: 1.02x faster                                                      |
| mdp                      | 2.75 sec                                                     | 2.71 sec: 1.01x faster                                                     |
| spectral_norm            | 93.3 ms                                                      | 92.2 ms: 1.01x faster                                                      |
| unpickle_pure_python     | 241 us                                                       | 239 us: 1.01x faster                                                       |
| crypto_pyaes             | 83.4 ms                                                      | 84.0 ms: 1.01x slower                                                      |
| pickle_pure_python       | 319 us                                                       | 321 us: 1.01x slower                                                       |
| sqlglot_optimize         | 59.8 ms                                                      | 60.3 ms: 1.01x slower                                                      |
| richards_super           | 61.0 ms                                                      | 62.1 ms: 1.02x slower                                                      |
| regex_dna                | 227 ms                                                       | 234 ms: 1.03x slower                                                       |
| tornado_http             | 122 ms                                                       | 125 ms: 1.03x slower                                                       |
| pickle_dict              | 30.8 us                                                      | 32.0 us: 1.04x slower                                                      |
| unpickle_list            | 4.53 us                                                      | 4.73 us: 1.04x slower                                                      |
| regex_v8                 | 23.9 ms                                                      | 25.1 ms: 1.05x slower                                                      |
| xml_etree_process        | 56.5 ms                                                      | 59.2 ms: 1.05x slower                                                      |
| pickle                   | 9.64 us                                                      | 10.1 us: 1.05x slower                                                      |
| gc_traversal             | 3.85 ms                                                      | 4.04 ms: 1.05x slower                                                      |
| docutils                 | 2.86 sec                                                     | 3.01 sec: 1.05x slower                                                     |
| create_gc_cycles         | 1.61 ms                                                      | 1.70 ms: 1.06x slower                                                      |
| pidigits                 | 251 ms                                                       | 265 ms: 1.06x slower                                                       |
| meteor_contest           | 131 ms                                                       | 138 ms: 1.06x slower                                                       |
| nqueens                  | 103 ms                                                       | 110 ms: 1.07x slower                                                       |
| dulwich_log              | 68.4 ms                                                      | 73.4 ms: 1.07x slower                                                      |
| xml_etree_iterparse      | 104 ms                                                       | 112 ms: 1.07x slower                                                       |
| xml_etree_generate       | 80.5 ms                                                      | 87.0 ms: 1.08x slower                                                      |
| pathlib                  | 19.1 ms                                                      | 20.6 ms: 1.08x slower                                                      |
| sqlite_synth             | 2.50 us                                                      | 2.72 us: 1.09x slower                                                      |
| unpickle                 | 13.4 us                                                      | 14.6 us: 1.09x slower                                                      |
| fannkuch                 | 429 ms                                                       | 473 ms: 1.10x slower                                                       |
| pprint_pformat           | 1.63 sec                                                     | 1.80 sec: 1.11x slower                                                     |
| pickle_list              | 3.83 us                                                      | 4.27 us: 1.11x slower                                                      |
| python_startup_no_site   | 7.76 ms                                                      | 8.68 ms: 1.12x slower                                                      |
| deepcopy_memo            | 38.8 us                                                      | 43.6 us: 1.12x slower                                                      |
| pprint_safe_repr         | 784 ms                                                       | 883 ms: 1.13x slower                                                       |
| regex_compile            | 158 ms                                                       | 178 ms: 1.13x slower                                                       |
| scimark_monte_carlo      | 68.2 ms                                                      | 76.9 ms: 1.13x slower                                                      |
| go                       | 164 ms                                                       | 186 ms: 1.14x slower                                                       |
| richards                 | 48.3 ms                                                      | 55.3 ms: 1.15x slower                                                      |
| tomli_loads              | 2.26 sec                                                     | 2.65 sec: 1.17x slower                                                     |
| python_startup           | 10.8 ms                                                      | 12.6 ms: 1.18x slower                                                      |
| telco                    | 6.86 ms                                                      | 8.36 ms: 1.22x slower                                                      |
| comprehensions           | 24.6 us                                                      | 30.4 us: 1.23x slower                                                      |
| mako                     | 11.0 ms                                                      | 13.7 ms: 1.25x slower                                                      |
| async_generators         | 316 ms                                                       | 395 ms: 1.25x slower                                                       |
| nbody                    | 90.7 ms                                                      | 114 ms: 1.26x slower                                                       |
| pyflate                  | 449 ms                                                       | 567 ms: 1.26x slower                                                       |
| deltablue                | 4.00 ms                                                      | 5.15 ms: 1.29x slower                                                      |
| scimark_sor              | 111 ms                                                       | 148 ms: 1.33x slower                                                       |
| scimark_fft              | 285 ms                                                       | 382 ms: 1.34x slower                                                       |
| hexiom                   | 7.13 ms                                                      | 9.72 ms: 1.36x slower                                                      |
| float                    | 74.2 ms                                                      | 104 ms: 1.40x slower                                                       |
| scimark_sparse_mat_mult  | 4.05 ms                                                      | 5.95 ms: 1.47x slower                                                      |
| Geometric mean           | (ref)                                                        | 1.01x slower                                                               |

Benchmark hidden because not significant (3): logging_silent, pycparser, bench_mp_pool
Ignored benchmarks (18) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509.json: 2to3, aiohttp, chameleon, dask, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 98.30% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
