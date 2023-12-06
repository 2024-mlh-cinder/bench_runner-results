
# Results vs. 3.12.0

- fork: python
- ref: v3.13.0a1
- machine: windows-amd64
- commit hash: ad056f0
- commit date: 2023-10-13
- overall geometric mean: 1.01x slower \*
- HPT reliability: 99.49%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231013-pythonperf1-amd64-python-v3.13.0a1-3.13.0a1-ad056f0 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| 2to3           | 213 ms                                                      | 216 ms: 1.01x slower                                            |
| chameleon      | 4.95 ms                                                     | 4.98 ms: 1.01x slower                                           |
| tornado_http   | 87.2 ms                                                     | 89.1 ms: 1.02x slower                                           |
| Geometric mean | (ref)                                                       | 1.01x slower                                                    |

Benchmark hidden because not significant (1): docutils

Benchmarks with tag 'asyncio':
==============================

| Benchmark                 | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231013-pythonperf1-amd64-python-v3.13.0a1-3.13.0a1-ad056f0 |
|---------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| async_tree_none           | 286 ms                                                      | 267 ms: 1.07x faster                                            |
| async_tree_cpu_io_mixed   | 477 ms                                                      | 455 ms: 1.05x faster                                            |
| async_tree_io             | 712 ms                                                      | 723 ms: 1.02x slower                                            |
| async_tree_memoization    | 333 ms                                                      | 340 ms: 1.02x slower                                            |
| async_tree_none_tg        | 277 ms                                                      | 285 ms: 1.03x slower                                            |
| async_tree_io_tg          | 742 ms                                                      | 772 ms: 1.04x slower                                            |
| async_tree_memoization_tg | 345 ms                                                      | 359 ms: 1.04x slower                                            |
| Geometric mean            | (ref)                                                       | 1.00x slower                                                    |

Benchmark hidden because not significant (1): async_tree_cpu_io_mixed_tg

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231013-pythonperf1-amd64-python-v3.13.0a1-3.13.0a1-ad056f0 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| float          | 54.7 ms                                                     | 53.6 ms: 1.02x faster                                           |
| nbody          | 68.8 ms                                                     | 72.2 ms: 1.05x slower                                           |
| Geometric mean | (ref)                                                       | 1.01x slower                                                    |

Benchmark hidden because not significant (1): pidigits

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231013-pythonperf1-amd64-python-v3.13.0a1-3.13.0a1-ad056f0 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| regex_dna      | 119 ms                                                      | 119 ms: 1.00x faster                                            |
| regex_effbot   | 1.58 ms                                                     | 1.60 ms: 1.01x slower                                           |
| regex_compile  | 87.2 ms                                                     | 90.8 ms: 1.04x slower                                           |
| regex_v8       | 13.5 ms                                                     | 14.8 ms: 1.10x slower                                           |
| Geometric mean | (ref)                                                       | 1.04x slower                                                    |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231013-pythonperf1-amd64-python-v3.13.0a1-3.13.0a1-ad056f0 |
|----------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| pickle               | 7.38 us                                                     | 6.98 us: 1.06x faster                                           |
| json_dumps           | 5.83 ms                                                     | 5.60 ms: 1.04x faster                                           |
| unpickle             | 8.44 us                                                     | 8.12 us: 1.04x faster                                           |
| pickle_dict          | 18.9 us                                                     | 18.4 us: 1.03x faster                                           |
| pickle_pure_python   | 195 us                                                      | 190 us: 1.03x faster                                            |
| json_loads           | 13.6 us                                                     | 13.5 us: 1.01x faster                                           |
| xml_etree_generate   | 55.8 ms                                                     | 55.4 ms: 1.01x faster                                           |
| xml_etree_parse      | 90.5 ms                                                     | 91.6 ms: 1.01x slower                                           |
| xml_etree_iterparse  | 63.1 ms                                                     | 64.0 ms: 1.01x slower                                           |
| unpickle_list        | 2.69 us                                                     | 2.74 us: 1.01x slower                                           |
| xml_etree_process    | 37.6 ms                                                     | 38.2 ms: 1.02x slower                                           |
| unpickle_pure_python | 134 us                                                      | 137 us: 1.02x slower                                            |
| tomli_loads          | 1.38 sec                                                    | 1.48 sec: 1.07x slower                                          |
| Geometric mean       | (ref)                                                       | 1.00x faster                                                    |

Benchmark hidden because not significant (1): pickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231013-pythonperf1-amd64-python-v3.13.0a1-3.13.0a1-ad056f0 |
|------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| python_startup_no_site | 15.9 ms                                                     | 16.2 ms: 1.02x slower                                           |
| python_startup         | 18.8 ms                                                     | 19.7 ms: 1.04x slower                                           |
| Geometric mean         | (ref)                                                       | 1.03x slower                                                    |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231013-pythonperf1-amd64-python-v3.13.0a1-3.13.0a1-ad056f0 |
|-----------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| mako      | 7.05 ms                                                     | 7.20 ms: 1.02x slower                                           |

All benchmarks:
===============

| Benchmark                 | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231013-pythonperf1-amd64-python-v3.13.0a1-3.13.0a1-ad056f0 |
|---------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| raytrace                  | 192 ms                                                      | 174 ms: 1.10x faster                                            |
| crypto_pyaes              | 46.4 ms                                                     | 43.3 ms: 1.07x faster                                           |
| async_tree_none           | 286 ms                                                      | 267 ms: 1.07x faster                                            |
| sqlite_synth              | 1.75 us                                                     | 1.65 us: 1.06x faster                                           |
| pickle                    | 7.38 us                                                     | 6.98 us: 1.06x faster                                           |
| bench_mp_pool             | 67.2 ms                                                     | 64.0 ms: 1.05x faster                                           |
| scimark_monte_carlo       | 43.0 ms                                                     | 41.0 ms: 1.05x faster                                           |
| async_tree_cpu_io_mixed   | 477 ms                                                      | 455 ms: 1.05x faster                                            |
| nqueens                   | 61.7 ms                                                     | 59.1 ms: 1.04x faster                                           |
| chaos                     | 42.1 ms                                                     | 40.4 ms: 1.04x faster                                           |
| json_dumps                | 5.83 ms                                                     | 5.60 ms: 1.04x faster                                           |
| unpickle                  | 8.44 us                                                     | 8.12 us: 1.04x faster                                           |
| scimark_sor               | 79.8 ms                                                     | 77.0 ms: 1.04x faster                                           |
| pickle_dict               | 18.9 us                                                     | 18.4 us: 1.03x faster                                           |
| scimark_fft               | 181 ms                                                      | 176 ms: 1.03x faster                                            |
| pickle_pure_python        | 195 us                                                      | 190 us: 1.03x faster                                            |
| scimark_sparse_mat_mult   | 2.51 ms                                                     | 2.45 ms: 1.03x faster                                           |
| float                     | 54.7 ms                                                     | 53.6 ms: 1.02x faster                                           |
| spectral_norm             | 63.9 ms                                                     | 63.0 ms: 1.01x faster                                           |
| pathlib                   | 79.6 ms                                                     | 78.5 ms: 1.01x faster                                           |
| generators                | 22.6 ms                                                     | 22.3 ms: 1.01x faster                                           |
| deepcopy                  | 233 us                                                      | 230 us: 1.01x faster                                            |
| json_loads                | 13.6 us                                                     | 13.5 us: 1.01x faster                                           |
| xml_etree_generate        | 55.8 ms                                                     | 55.4 ms: 1.01x faster                                           |
| pprint_pformat            | 1.04 sec                                                    | 1.03 sec: 1.01x faster                                          |
| deepcopy_reduce           | 2.08 us                                                     | 2.07 us: 1.01x faster                                           |
| regex_dna                 | 119 ms                                                      | 119 ms: 1.00x faster                                            |
| chameleon                 | 4.95 ms                                                     | 4.98 ms: 1.01x slower                                           |
| regex_effbot              | 1.58 ms                                                     | 1.60 ms: 1.01x slower                                           |
| comprehensions            | 14.0 us                                                     | 14.2 us: 1.01x slower                                           |
| sympy_sum                 | 90.1 ms                                                     | 91.1 ms: 1.01x slower                                           |
| sqlglot_parse             | 802 us                                                      | 811 us: 1.01x slower                                            |
| go                        | 89.0 ms                                                     | 90.0 ms: 1.01x slower                                           |
| xml_etree_parse           | 90.5 ms                                                     | 91.6 ms: 1.01x slower                                           |
| sqlglot_transpile         | 1.02 ms                                                     | 1.03 ms: 1.01x slower                                           |
| logging_format            | 6.72 us                                                     | 6.81 us: 1.01x slower                                           |
| xml_etree_iterparse       | 63.1 ms                                                     | 64.0 ms: 1.01x slower                                           |
| sympy_integrate           | 13.0 ms                                                     | 13.1 ms: 1.01x slower                                           |
| 2to3                      | 213 ms                                                      | 216 ms: 1.01x slower                                            |
| unpickle_list             | 2.69 us                                                     | 2.74 us: 1.01x slower                                           |
| pyflate                   | 294 ms                                                      | 298 ms: 1.02x slower                                            |
| async_tree_io             | 712 ms                                                      | 723 ms: 1.02x slower                                            |
| xml_etree_process         | 37.6 ms                                                     | 38.2 ms: 1.02x slower                                           |
| python_startup_no_site    | 15.9 ms                                                     | 16.2 ms: 1.02x slower                                           |
| sympy_str                 | 171 ms                                                      | 175 ms: 1.02x slower                                            |
| scimark_lu                | 57.5 ms                                                     | 58.6 ms: 1.02x slower                                           |
| mako                      | 7.05 ms                                                     | 7.20 ms: 1.02x slower                                           |
| async_tree_memoization    | 333 ms                                                      | 340 ms: 1.02x slower                                            |
| fannkuch                  | 244 ms                                                      | 249 ms: 1.02x slower                                            |
| tornado_http              | 87.2 ms                                                     | 89.1 ms: 1.02x slower                                           |
| sqlglot_optimize          | 34.0 ms                                                     | 34.8 ms: 1.02x slower                                           |
| hexiom                    | 4.00 ms                                                     | 4.09 ms: 1.02x slower                                           |
| unpickle_pure_python      | 134 us                                                      | 137 us: 1.02x slower                                            |
| async_generators          | 230 ms                                                      | 236 ms: 1.03x slower                                            |
| richards_super            | 31.2 ms                                                     | 32.0 ms: 1.03x slower                                           |
| async_tree_none_tg        | 277 ms                                                      | 285 ms: 1.03x slower                                            |
| sympy_expand              | 278 ms                                                      | 287 ms: 1.03x slower                                            |
| deltablue                 | 2.12 ms                                                     | 2.19 ms: 1.03x slower                                           |
| logging_simple            | 6.21 us                                                     | 6.40 us: 1.03x slower                                           |
| meteor_contest            | 72.1 ms                                                     | 74.5 ms: 1.03x slower                                           |
| async_tree_io_tg          | 742 ms                                                      | 772 ms: 1.04x slower                                            |
| regex_compile             | 87.2 ms                                                     | 90.8 ms: 1.04x slower                                           |
| async_tree_memoization_tg | 345 ms                                                      | 359 ms: 1.04x slower                                            |
| coroutines                | 14.1 ms                                                     | 14.7 ms: 1.04x slower                                           |
| python_startup            | 18.8 ms                                                     | 19.7 ms: 1.04x slower                                           |
| unpack_sequence           | 36.9 ns                                                     | 38.5 ns: 1.04x slower                                           |
| logging_silent            | 60.5 ns                                                     | 63.2 ns: 1.05x slower                                           |
| richards                  | 27.6 ms                                                     | 28.8 ms: 1.05x slower                                           |
| nbody                     | 68.8 ms                                                     | 72.2 ms: 1.05x slower                                           |
| mdp                       | 1.42 sec                                                    | 1.49 sec: 1.05x slower                                          |
| dulwich_log               | 42.7 ms                                                     | 45.2 ms: 1.06x slower                                           |
| deepcopy_memo             | 23.4 us                                                     | 24.8 us: 1.06x slower                                           |
| tomli_loads               | 1.38 sec                                                    | 1.48 sec: 1.07x slower                                          |
| regex_v8                  | 13.5 ms                                                     | 14.8 ms: 1.10x slower                                           |
| coverage                  | 39.8 ms                                                     | 45.4 ms: 1.14x slower                                           |
| telco                     | 4.08 ms                                                     | 4.73 ms: 1.16x slower                                           |
| pycparser                 | 673 ms                                                      | 861 ms: 1.28x slower                                            |
| Geometric mean            | (ref)                                                       | 1.01x slower                                                    |

Benchmark hidden because not significant (14): typing_runtime_protocols, pprint_safe_repr, gc_traversal, asyncio_tcp, pidigits, mypy2, sqlglot_normalize, docutils, asyncio_tcp_ssl, create_gc_cycles, async_tree_cpu_io_mixed_tg, bench_thread_pool, pickle_list, json
Ignored benchmarks (5) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, dask, django_template, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 99.49% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
