
# Results vs. 3.11.0

- fork: brandtbucher
- ref: justin
- machine: linux-x86_64
- commit hash: a98d4fe
- commit date: 2023-09-13
- overall geometric mean: 1.00x slower
- HPT reliability: 99.48%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230913-linux-x86_64-brandtbucher-justin-3.13.0a0-a98d4fe |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| docutils       | 2.63 sec                                               | 2.71 sec: 1.03x slower                                        |
| tornado_http   | 96.3 ms                                                | 97.4 ms: 1.01x slower                                         |
| Geometric mean | (ref)                                                  | 1.02x slower                                                  |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230913-linux-x86_64-brandtbucher-justin-3.13.0a0-a98d4fe |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| pidigits       | 198 ms                                                 | 189 ms: 1.05x faster                                          |
| float          | 77.2 ms                                                | 83.2 ms: 1.08x slower                                         |
| nbody          | 93.1 ms                                                | 120 ms: 1.29x slower                                          |
| Geometric mean | (ref)                                                  | 1.10x slower                                                  |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230913-linux-x86_64-brandtbucher-justin-3.13.0a0-a98d4fe |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| regex_effbot   | 3.99 ms                                                | 3.62 ms: 1.10x faster                                         |
| regex_dna      | 204 ms                                                 | 210 ms: 1.03x slower                                          |
| regex_compile  | 138 ms                                                 | 148 ms: 1.07x slower                                          |
| regex_v8       | 22.0 ms                                                | 24.0 ms: 1.09x slower                                         |
| Geometric mean | (ref)                                                  | 1.02x slower                                                  |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230913-linux-x86_64-brandtbucher-justin-3.13.0a0-a98d4fe |
|----------------------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| json_dumps           | 12.6 ms                                                | 9.81 ms: 1.28x faster                                         |
| json_loads           | 26.5 us                                                | 25.1 us: 1.06x faster                                         |
| xml_etree_parse      | 158 ms                                                 | 152 ms: 1.04x faster                                          |
| xml_etree_iterparse  | 104 ms                                                 | 102 ms: 1.02x faster                                          |
| unpickle_list        | 4.91 us                                                | 4.83 us: 1.02x faster                                         |
| pickle_dict          | 31.1 us                                                | 31.6 us: 1.02x slower                                         |
| unpickle_pure_python | 228 us                                                 | 234 us: 1.03x slower                                          |
| unpickle             | 13.7 us                                                | 14.2 us: 1.04x slower                                         |
| pickle               | 10.1 us                                                | 10.5 us: 1.04x slower                                         |
| tomli_loads          | 2.22 sec                                               | 2.35 sec: 1.06x slower                                        |
| xml_etree_process    | 53.9 ms                                                | 58.1 ms: 1.08x slower                                         |
| xml_etree_generate   | 76.2 ms                                                | 83.4 ms: 1.09x slower                                         |
| pickle_list          | 4.11 us                                                | 4.81 us: 1.17x slower                                         |
| Geometric mean       | (ref)                                                  | 1.01x slower                                                  |

Benchmark hidden because not significant (1): pickle_pure_python

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230913-linux-x86_64-brandtbucher-justin-3.13.0a0-a98d4fe |
|------------------------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| python_startup_no_site | 6.01 ms                                                | 6.84 ms: 1.14x slower                                         |
| python_startup         | 8.52 ms                                                | 10.1 ms: 1.18x slower                                         |
| Geometric mean         | (ref)                                                  | 1.16x slower                                                  |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230913-linux-x86_64-brandtbucher-justin-3.13.0a0-a98d4fe |
|-----------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| mako      | 10.1 ms                                                | 11.3 ms: 1.12x slower                                         |

All benchmarks:
===============

| Benchmark                | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230913-linux-x86_64-brandtbucher-justin-3.13.0a0-a98d4fe |
|--------------------------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| typing_runtime_protocols | 486 us                                                 | 155 us: 3.14x faster                                          |
| generators               | 73.5 ms                                                | 28.1 ms: 2.61x faster                                         |
| asyncio_tcp              | 922 ms                                                 | 496 ms: 1.86x faster                                          |
| asyncio_tcp_ssl          | 3.14 sec                                               | 1.81 sec: 1.73x faster                                        |
| json_dumps               | 12.6 ms                                                | 9.81 ms: 1.28x faster                                         |
| mypy2                    | 420 ms                                                 | 354 ms: 1.19x faster                                          |
| async_tree_none          | 526 ms                                                 | 447 ms: 1.18x faster                                          |
| coverage                 | 100 ms                                                 | 85.3 ms: 1.17x faster                                         |
| coroutines               | 25.5 ms                                                | 21.8 ms: 1.17x faster                                         |
| regex_effbot             | 3.99 ms                                                | 3.62 ms: 1.10x faster                                         |
| async_tree_memoization   | 627 ms                                                 | 572 ms: 1.10x faster                                          |
| gc_traversal             | 4.02 ms                                                | 3.69 ms: 1.09x faster                                         |
| sqlglot_parse            | 1.40 ms                                                | 1.29 ms: 1.09x faster                                         |
| async_tree_io            | 1.30 sec                                               | 1.20 sec: 1.08x faster                                        |
| raytrace                 | 297 ms                                                 | 279 ms: 1.07x faster                                          |
| sqlglot_transpile        | 1.70 ms                                                | 1.60 ms: 1.06x faster                                         |
| json_loads               | 26.5 us                                                | 25.1 us: 1.06x faster                                         |
| pidigits                 | 198 ms                                                 | 189 ms: 1.05x faster                                          |
| deltablue                | 3.67 ms                                                | 3.52 ms: 1.04x faster                                         |
| xml_etree_parse          | 158 ms                                                 | 152 ms: 1.04x faster                                          |
| richards_super           | 56.8 ms                                                | 54.7 ms: 1.04x faster                                         |
| async_tree_cpu_io_mixed  | 739 ms                                                 | 713 ms: 1.04x faster                                          |
| json                     | 4.94 ms                                                | 4.82 ms: 1.02x faster                                         |
| xml_etree_iterparse      | 104 ms                                                 | 102 ms: 1.02x faster                                          |
| unpickle_list            | 4.91 us                                                | 4.83 us: 1.02x faster                                         |
| sqlglot_normalize        | 108 ms                                                 | 106 ms: 1.02x faster                                          |
| scimark_monte_carlo      | 68.1 ms                                                | 68.3 ms: 1.00x slower                                         |
| sqlglot_optimize         | 53.1 ms                                                | 53.6 ms: 1.01x slower                                         |
| crypto_pyaes             | 74.7 ms                                                | 75.5 ms: 1.01x slower                                         |
| create_gc_cycles         | 1.49 ms                                                | 1.50 ms: 1.01x slower                                         |
| tornado_http             | 96.3 ms                                                | 97.4 ms: 1.01x slower                                         |
| pickle_dict              | 31.1 us                                                | 31.6 us: 1.02x slower                                         |
| pycparser                | 1.18 sec                                               | 1.21 sec: 1.03x slower                                        |
| unpickle_pure_python     | 228 us                                                 | 234 us: 1.03x slower                                          |
| regex_dna                | 204 ms                                                 | 210 ms: 1.03x slower                                          |
| docutils                 | 2.63 sec                                               | 2.71 sec: 1.03x slower                                        |
| scimark_sor              | 118 ms                                                 | 122 ms: 1.03x slower                                          |
| scimark_lu               | 110 ms                                                 | 114 ms: 1.04x slower                                          |
| logging_format           | 6.68 us                                                | 6.92 us: 1.04x slower                                         |
| logging_simple           | 6.03 us                                                | 6.28 us: 1.04x slower                                         |
| unpickle                 | 13.7 us                                                | 14.2 us: 1.04x slower                                         |
| pickle                   | 10.1 us                                                | 10.5 us: 1.04x slower                                         |
| richards                 | 45.7 ms                                                | 47.9 ms: 1.05x slower                                         |
| pathlib                  | 18.2 ms                                                | 19.2 ms: 1.05x slower                                         |
| logging_silent           | 101 ns                                                 | 107 ns: 1.06x slower                                          |
| tomli_loads              | 2.22 sec                                               | 2.35 sec: 1.06x slower                                        |
| meteor_contest           | 107 ms                                                 | 113 ms: 1.06x slower                                          |
| bench_thread_pool        | 819 us                                                 | 871 us: 1.06x slower                                          |
| regex_compile            | 138 ms                                                 | 148 ms: 1.07x slower                                          |
| float                    | 77.2 ms                                                | 83.2 ms: 1.08x slower                                         |
| mdp                      | 2.62 sec                                               | 2.82 sec: 1.08x slower                                        |
| go                       | 140 ms                                                 | 151 ms: 1.08x slower                                          |
| xml_etree_process        | 53.9 ms                                                | 58.1 ms: 1.08x slower                                         |
| spectral_norm            | 100 ms                                                 | 109 ms: 1.09x slower                                          |
| sqlite_synth             | 2.52 us                                                | 2.74 us: 1.09x slower                                         |
| regex_v8                 | 22.0 ms                                                | 24.0 ms: 1.09x slower                                         |
| deepcopy_reduce          | 2.94 us                                                | 3.21 us: 1.09x slower                                         |
| dulwich_log              | 63.7 ms                                                | 69.5 ms: 1.09x slower                                         |
| deepcopy                 | 342 us                                                 | 374 us: 1.09x slower                                          |
| xml_etree_generate       | 76.2 ms                                                | 83.4 ms: 1.09x slower                                         |
| scimark_sparse_mat_mult  | 4.50 ms                                                | 4.93 ms: 1.10x slower                                         |
| comprehensions           | 22.4 us                                                | 24.7 us: 1.10x slower                                         |
| pprint_safe_repr         | 701 ms                                                 | 773 ms: 1.10x slower                                          |
| pprint_pformat           | 1.46 sec                                               | 1.61 sec: 1.11x slower                                        |
| mako                     | 10.1 ms                                                | 11.3 ms: 1.12x slower                                         |
| chaos                    | 69.2 ms                                                | 78.1 ms: 1.13x slower                                         |
| python_startup_no_site   | 6.01 ms                                                | 6.84 ms: 1.14x slower                                         |
| scimark_fft              | 328 ms                                                 | 378 ms: 1.15x slower                                          |
| pyflate                  | 418 ms                                                 | 486 ms: 1.16x slower                                          |
| pickle_list              | 4.11 us                                                | 4.81 us: 1.17x slower                                         |
| hexiom                   | 6.37 ms                                                | 7.48 ms: 1.17x slower                                         |
| python_startup           | 8.52 ms                                                | 10.1 ms: 1.18x slower                                         |
| fannkuch                 | 388 ms                                                 | 460 ms: 1.19x slower                                          |
| nqueens                  | 83.4 ms                                                | 103 ms: 1.24x slower                                          |
| telco                    | 6.58 ms                                                | 8.19 ms: 1.24x slower                                         |
| async_generators         | 368 ms                                                 | 463 ms: 1.26x slower                                          |
| deepcopy_memo            | 37.0 us                                                | 46.7 us: 1.26x slower                                         |
| nbody                    | 93.1 ms                                                | 120 ms: 1.29x slower                                          |
| unpack_sequence          | 43.1 ns                                                | 58.4 ns: 1.36x slower                                         |
| dask                     | 360 ms                                                 | 533 ms: 1.48x slower                                          |
| Geometric mean           | (ref)                                                  | 1.00x slower                                                  |

Benchmark hidden because not significant (2): bench_mp_pool, pickle_pure_python
Ignored benchmarks (18) of results/bm-20221024-3.11.0-deaf509/bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509.json: 2to3, aiohttp, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 99.48% likely to be slow
- 90% likely to have a slowdown of 1.02x
- 95% likely to have a slowdown of 1.01x
- 99% likely to have a slowdown of 1.00x
