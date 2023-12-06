
# Results vs. 3.12.0

- fork: mdboom
- ref: optimize_off
- machine: windows-amd64
- commit hash: 54d99b8
- commit date: 2023-11-06
- overall geometric mean: 1.02x faster \*
- HPT reliability: 99.40%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231106-pythonperf1-amd64-mdboom-optimize_off-3.13.0a1+-54d99b8 |
|----------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| 2to3           | 213 ms                                                      | 208 ms: 1.02x faster                                                |
| chameleon      | 4.95 ms                                                     | 4.90 ms: 1.01x faster                                               |
| docutils       | 1.61 sec                                                    | 1.55 sec: 1.03x faster                                              |
| Geometric mean | (ref)                                                       | 1.02x faster                                                        |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'asyncio':
==============================

| Benchmark                 | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231106-pythonperf1-amd64-mdboom-optimize_off-3.13.0a1+-54d99b8 |
|---------------------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| async_tree_none           | 286 ms                                                      | 265 ms: 1.08x faster                                                |
| async_tree_cpu_io_mixed   | 477 ms                                                      | 451 ms: 1.06x faster                                                |
| async_tree_io             | 712 ms                                                      | 723 ms: 1.02x slower                                                |
| async_tree_memoization    | 333 ms                                                      | 339 ms: 1.02x slower                                                |
| async_tree_none_tg        | 277 ms                                                      | 282 ms: 1.02x slower                                                |
| async_tree_io_tg          | 742 ms                                                      | 762 ms: 1.03x slower                                                |
| async_tree_memoization_tg | 345 ms                                                      | 363 ms: 1.05x slower                                                |
| Geometric mean            | (ref)                                                       | 1.00x faster                                                        |

Benchmark hidden because not significant (1): async_tree_cpu_io_mixed_tg

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231106-pythonperf1-amd64-mdboom-optimize_off-3.13.0a1+-54d99b8 |
|----------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| float          | 54.7 ms                                                     | 52.2 ms: 1.05x faster                                               |
| pidigits       | 150 ms                                                      | 147 ms: 1.02x faster                                                |
| nbody          | 68.8 ms                                                     | 72.6 ms: 1.06x slower                                               |
| Geometric mean | (ref)                                                       | 1.00x faster                                                        |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231106-pythonperf1-amd64-mdboom-optimize_off-3.13.0a1+-54d99b8 |
|----------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| regex_compile  | 87.2 ms                                                     | 79.2 ms: 1.10x faster                                               |
| regex_effbot   | 1.58 ms                                                     | 1.57 ms: 1.01x faster                                               |
| regex_dna      | 119 ms                                                      | 119 ms: 1.00x faster                                                |
| regex_v8       | 13.5 ms                                                     | 14.9 ms: 1.10x slower                                               |
| Geometric mean | (ref)                                                       | 1.00x faster                                                        |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231106-pythonperf1-amd64-mdboom-optimize_off-3.13.0a1+-54d99b8 |
|----------------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| pickle_pure_python   | 195 us                                                      | 181 us: 1.07x faster                                                |
| unpickle             | 8.44 us                                                     | 8.02 us: 1.05x faster                                               |
| json_dumps           | 5.83 ms                                                     | 5.63 ms: 1.04x faster                                               |
| unpickle_pure_python | 134 us                                                      | 130 us: 1.03x faster                                                |
| pickle               | 7.38 us                                                     | 7.18 us: 1.03x faster                                               |
| xml_etree_generate   | 55.8 ms                                                     | 55.3 ms: 1.01x faster                                               |
| xml_etree_parse      | 90.5 ms                                                     | 92.0 ms: 1.02x slower                                               |
| tomli_loads          | 1.38 sec                                                    | 1.41 sec: 1.02x slower                                              |
| pickle_dict          | 18.9 us                                                     | 19.8 us: 1.04x slower                                               |
| Geometric mean       | (ref)                                                       | 1.01x faster                                                        |

Benchmark hidden because not significant (5): json_loads, pickle_list, xml_etree_process, unpickle_list, xml_etree_iterparse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231106-pythonperf1-amd64-mdboom-optimize_off-3.13.0a1+-54d99b8 |
|------------------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| python_startup         | 18.8 ms                                                     | 19.6 ms: 1.04x slower                                               |
| python_startup_no_site | 15.9 ms                                                     | 17.6 ms: 1.10x slower                                               |
| Geometric mean         | (ref)                                                       | 1.07x slower                                                        |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231106-pythonperf1-amd64-mdboom-optimize_off-3.13.0a1+-54d99b8 |
|-----------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| mako      | 7.05 ms                                                     | 6.56 ms: 1.07x faster                                               |

All benchmarks:
===============

| Benchmark                 | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231106-pythonperf1-amd64-mdboom-optimize_off-3.13.0a1+-54d99b8 |
|---------------------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| comprehensions            | 14.0 us                                                     | 10.7 us: 1.30x faster                                               |
| typing_runtime_protocols  | 96.7 us                                                     | 76.3 us: 1.27x faster                                               |
| raytrace                  | 192 ms                                                      | 162 ms: 1.19x faster                                                |
| sqlite_synth              | 1.75 us                                                     | 1.56 us: 1.12x faster                                               |
| regex_compile             | 87.2 ms                                                     | 79.2 ms: 1.10x faster                                               |
| sympy_sum                 | 90.1 ms                                                     | 82.5 ms: 1.09x faster                                               |
| logging_silent            | 60.5 ns                                                     | 55.5 ns: 1.09x faster                                               |
| sympy_str                 | 171 ms                                                      | 158 ms: 1.09x faster                                                |
| async_tree_none           | 286 ms                                                      | 265 ms: 1.08x faster                                                |
| bench_mp_pool             | 67.2 ms                                                     | 62.6 ms: 1.07x faster                                               |
| mako                      | 7.05 ms                                                     | 6.56 ms: 1.07x faster                                               |
| nqueens                   | 61.7 ms                                                     | 57.5 ms: 1.07x faster                                               |
| pickle_pure_python        | 195 us                                                      | 181 us: 1.07x faster                                                |
| deepcopy_reduce           | 2.08 us                                                     | 1.96 us: 1.07x faster                                               |
| chaos                     | 42.1 ms                                                     | 39.5 ms: 1.06x faster                                               |
| crypto_pyaes              | 46.4 ms                                                     | 43.7 ms: 1.06x faster                                               |
| scimark_sparse_mat_mult   | 2.51 ms                                                     | 2.37 ms: 1.06x faster                                               |
| async_tree_cpu_io_mixed   | 477 ms                                                      | 451 ms: 1.06x faster                                                |
| sqlglot_parse             | 802 us                                                      | 758 us: 1.06x faster                                                |
| deepcopy                  | 233 us                                                      | 220 us: 1.06x faster                                                |
| dulwich_log               | 42.7 ms                                                     | 40.4 ms: 1.06x faster                                               |
| hexiom                    | 4.00 ms                                                     | 3.79 ms: 1.06x faster                                               |
| sqlglot_normalize         | 183 ms                                                      | 174 ms: 1.05x faster                                                |
| unpickle                  | 8.44 us                                                     | 8.02 us: 1.05x faster                                               |
| sympy_integrate           | 13.0 ms                                                     | 12.3 ms: 1.05x faster                                               |
| float                     | 54.7 ms                                                     | 52.2 ms: 1.05x faster                                               |
| deltablue                 | 2.12 ms                                                     | 2.03 ms: 1.04x faster                                               |
| generators                | 22.6 ms                                                     | 21.7 ms: 1.04x faster                                               |
| sqlglot_transpile         | 1.02 ms                                                     | 977 us: 1.04x faster                                                |
| json_dumps                | 5.83 ms                                                     | 5.63 ms: 1.04x faster                                               |
| pprint_safe_repr          | 508 ms                                                      | 490 ms: 1.04x faster                                                |
| docutils                  | 1.61 sec                                                    | 1.55 sec: 1.03x faster                                              |
| coroutines                | 14.1 ms                                                     | 13.7 ms: 1.03x faster                                               |
| unpickle_pure_python      | 134 us                                                      | 130 us: 1.03x faster                                                |
| sympy_expand              | 278 ms                                                      | 270 ms: 1.03x faster                                                |
| sqlglot_optimize          | 34.0 ms                                                     | 33.1 ms: 1.03x faster                                               |
| pprint_pformat            | 1.04 sec                                                    | 1.01 sec: 1.03x faster                                              |
| go                        | 89.0 ms                                                     | 86.5 ms: 1.03x faster                                               |
| pickle                    | 7.38 us                                                     | 7.18 us: 1.03x faster                                               |
| mypy2                     | 209 ms                                                      | 203 ms: 1.03x faster                                                |
| scimark_fft               | 181 ms                                                      | 177 ms: 1.02x faster                                                |
| pidigits                  | 150 ms                                                      | 147 ms: 1.02x faster                                                |
| richards_super            | 31.2 ms                                                     | 30.5 ms: 1.02x faster                                               |
| 2to3                      | 213 ms                                                      | 208 ms: 1.02x faster                                                |
| scimark_monte_carlo       | 43.0 ms                                                     | 42.2 ms: 1.02x faster                                               |
| spectral_norm             | 63.9 ms                                                     | 62.7 ms: 1.02x faster                                               |
| logging_format            | 6.72 us                                                     | 6.61 us: 1.02x faster                                               |
| async_generators          | 230 ms                                                      | 226 ms: 1.02x faster                                                |
| logging_simple            | 6.21 us                                                     | 6.13 us: 1.01x faster                                               |
| chameleon                 | 4.95 ms                                                     | 4.90 ms: 1.01x faster                                               |
| pyflate                   | 294 ms                                                      | 290 ms: 1.01x faster                                                |
| xml_etree_generate        | 55.8 ms                                                     | 55.3 ms: 1.01x faster                                               |
| pathlib                   | 79.6 ms                                                     | 78.9 ms: 1.01x faster                                               |
| regex_effbot              | 1.58 ms                                                     | 1.57 ms: 1.01x faster                                               |
| regex_dna                 | 119 ms                                                      | 119 ms: 1.00x faster                                                |
| scimark_sor               | 79.8 ms                                                     | 80.3 ms: 1.01x slower                                               |
| unpack_sequence           | 36.9 ns                                                     | 37.3 ns: 1.01x slower                                               |
| meteor_contest            | 72.1 ms                                                     | 72.9 ms: 1.01x slower                                               |
| deepcopy_memo             | 23.4 us                                                     | 23.7 us: 1.01x slower                                               |
| mdp                       | 1.42 sec                                                    | 1.44 sec: 1.01x slower                                              |
| xml_etree_parse           | 90.5 ms                                                     | 92.0 ms: 1.02x slower                                               |
| async_tree_io             | 712 ms                                                      | 723 ms: 1.02x slower                                                |
| async_tree_memoization    | 333 ms                                                      | 339 ms: 1.02x slower                                                |
| async_tree_none_tg        | 277 ms                                                      | 282 ms: 1.02x slower                                                |
| tomli_loads               | 1.38 sec                                                    | 1.41 sec: 1.02x slower                                              |
| scimark_lu                | 57.5 ms                                                     | 58.8 ms: 1.02x slower                                               |
| asyncio_tcp               | 471 ms                                                      | 482 ms: 1.02x slower                                                |
| async_tree_io_tg          | 742 ms                                                      | 762 ms: 1.03x slower                                                |
| fannkuch                  | 244 ms                                                      | 252 ms: 1.03x slower                                                |
| python_startup            | 18.8 ms                                                     | 19.6 ms: 1.04x slower                                               |
| pickle_dict               | 18.9 us                                                     | 19.8 us: 1.04x slower                                               |
| async_tree_memoization_tg | 345 ms                                                      | 363 ms: 1.05x slower                                                |
| nbody                     | 68.8 ms                                                     | 72.6 ms: 1.06x slower                                               |
| python_startup_no_site    | 15.9 ms                                                     | 17.6 ms: 1.10x slower                                               |
| regex_v8                  | 13.5 ms                                                     | 14.9 ms: 1.10x slower                                               |
| coverage                  | 39.8 ms                                                     | 45.4 ms: 1.14x slower                                               |
| pycparser                 | 673 ms                                                      | 769 ms: 1.14x slower                                                |
| telco                     | 4.08 ms                                                     | 4.76 ms: 1.16x slower                                               |
| Geometric mean            | (ref)                                                       | 1.02x faster                                                        |

Benchmark hidden because not significant (13): async_tree_cpu_io_mixed_tg, create_gc_cycles, asyncio_tcp_ssl, tornado_http, gc_traversal, richards, json_loads, pickle_list, xml_etree_process, unpickle_list, xml_etree_iterparse, bench_thread_pool, json
Ignored benchmarks (5) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, dask, django_template, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 99.40% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
