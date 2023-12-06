
# Results vs. 3.12.0

- fork: mdboom
- ref: pogo2
- machine: windows-amd64
- commit hash: 69004d6
- commit date: 2023-11-20
- overall geometric mean: 1.05x slower \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.02x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-pythonperf1-amd64-mdboom-pogo2-3.13.0a1+-69004d6 |
|----------------|:-----------------------------------------------------------:|:------------------------------------------------------------:|
| 2to3           | 213 ms                                                      | 222 ms: 1.05x slower                                         |
| chameleon      | 4.95 ms                                                     | 4.92 ms: 1.01x faster                                        |
| docutils       | 1.61 sec                                                    | 1.61 sec: 1.00x slower                                       |
| tornado_http   | 87.2 ms                                                     | 101 ms: 1.16x slower                                         |
| Geometric mean | (ref)                                                       | 1.05x slower                                                 |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-pythonperf1-amd64-mdboom-pogo2-3.13.0a1+-69004d6 |
|----------------------------|:-----------------------------------------------------------:|:------------------------------------------------------------:|
| async_tree_none            | 286 ms                                                      | 272 ms: 1.05x faster                                         |
| async_tree_cpu_io_mixed    | 477 ms                                                      | 461 ms: 1.03x faster                                         |
| async_tree_cpu_io_mixed_tg | 483 ms                                                      | 489 ms: 1.01x slower                                         |
| async_tree_io              | 712 ms                                                      | 732 ms: 1.03x slower                                         |
| async_tree_none_tg         | 277 ms                                                      | 287 ms: 1.04x slower                                         |
| async_tree_memoization     | 333 ms                                                      | 350 ms: 1.05x slower                                         |
| async_tree_io_tg           | 742 ms                                                      | 780 ms: 1.05x slower                                         |
| async_tree_memoization_tg  | 345 ms                                                      | 369 ms: 1.07x slower                                         |
| Geometric mean             | (ref)                                                       | 1.02x slower                                                 |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-pythonperf1-amd64-mdboom-pogo2-3.13.0a1+-69004d6 |
|----------------|:-----------------------------------------------------------:|:------------------------------------------------------------:|
| pidigits       | 150 ms                                                      | 148 ms: 1.01x faster                                         |
| float          | 54.7 ms                                                     | 58.2 ms: 1.07x slower                                        |
| nbody          | 68.8 ms                                                     | 85.2 ms: 1.24x slower                                        |
| Geometric mean | (ref)                                                       | 1.09x slower                                                 |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-pythonperf1-amd64-mdboom-pogo2-3.13.0a1+-69004d6 |
|----------------|:-----------------------------------------------------------:|:------------------------------------------------------------:|
| regex_effbot   | 1.58 ms                                                     | 1.61 ms: 1.02x slower                                        |
| regex_dna      | 119 ms                                                      | 122 ms: 1.02x slower                                         |
| regex_compile  | 87.2 ms                                                     | 91.7 ms: 1.05x slower                                        |
| regex_v8       | 13.5 ms                                                     | 23.6 ms: 1.75x slower                                        |
| Geometric mean | (ref)                                                       | 1.18x slower                                                 |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-pythonperf1-amd64-mdboom-pogo2-3.13.0a1+-69004d6 |
|----------------------|:-----------------------------------------------------------:|:------------------------------------------------------------:|
| pickle_pure_python   | 195 us                                                      | 181 us: 1.07x faster                                         |
| pickle               | 7.38 us                                                     | 7.02 us: 1.05x faster                                        |
| unpickle             | 8.44 us                                                     | 8.20 us: 1.03x faster                                        |
| unpickle_list        | 2.69 us                                                     | 2.64 us: 1.02x faster                                        |
| json_dumps           | 5.83 ms                                                     | 5.73 ms: 1.02x faster                                        |
| pickle_dict          | 18.9 us                                                     | 18.6 us: 1.02x faster                                        |
| json_loads           | 13.6 us                                                     | 13.5 us: 1.01x faster                                        |
| xml_etree_generate   | 55.8 ms                                                     | 56.1 ms: 1.01x slower                                        |
| xml_etree_parse      | 90.5 ms                                                     | 92.2 ms: 1.02x slower                                        |
| xml_etree_process    | 37.6 ms                                                     | 38.9 ms: 1.03x slower                                        |
| unpickle_pure_python | 134 us                                                      | 139 us: 1.04x slower                                         |
| xml_etree_iterparse  | 63.1 ms                                                     | 67.3 ms: 1.07x slower                                        |
| tomli_loads          | 1.38 sec                                                    | 1.51 sec: 1.09x slower                                       |
| pickle_list          | 2.88 us                                                     | 3.31 us: 1.15x slower                                        |
| Geometric mean       | (ref)                                                       | 1.01x slower                                                 |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-pythonperf1-amd64-mdboom-pogo2-3.13.0a1+-69004d6 |
|------------------------|:-----------------------------------------------------------:|:------------------------------------------------------------:|
| python_startup         | 18.8 ms                                                     | 20.5 ms: 1.09x slower                                        |
| python_startup_no_site | 15.9 ms                                                     | 18.5 ms: 1.16x slower                                        |
| Geometric mean         | (ref)                                                       | 1.12x slower                                                 |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-pythonperf1-amd64-mdboom-pogo2-3.13.0a1+-69004d6 |
|-----------|:-----------------------------------------------------------:|:------------------------------------------------------------:|
| mako      | 7.05 ms                                                     | 7.65 ms: 1.08x slower                                        |

All benchmarks:
===============

| Benchmark                  | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-pythonperf1-amd64-mdboom-pogo2-3.13.0a1+-69004d6 |
|----------------------------|:-----------------------------------------------------------:|:------------------------------------------------------------:|
| typing_runtime_protocols   | 96.7 us                                                     | 80.3 us: 1.20x faster                                        |
| sqlite_synth               | 1.75 us                                                     | 1.58 us: 1.10x faster                                        |
| generators                 | 22.6 ms                                                     | 20.9 ms: 1.08x faster                                        |
| raytrace                   | 192 ms                                                      | 179 ms: 1.08x faster                                         |
| pickle_pure_python         | 195 us                                                      | 181 us: 1.07x faster                                         |
| logging_silent             | 60.5 ns                                                     | 56.9 ns: 1.06x faster                                        |
| coroutines                 | 14.1 ms                                                     | 13.3 ms: 1.06x faster                                        |
| async_tree_none            | 286 ms                                                      | 272 ms: 1.05x faster                                         |
| pickle                     | 7.38 us                                                     | 7.02 us: 1.05x faster                                        |
| deepcopy_reduce            | 2.08 us                                                     | 2.00 us: 1.04x faster                                        |
| comprehensions             | 14.0 us                                                     | 13.4 us: 1.04x faster                                        |
| async_tree_cpu_io_mixed    | 477 ms                                                      | 461 ms: 1.03x faster                                         |
| unpickle                   | 8.44 us                                                     | 8.20 us: 1.03x faster                                        |
| unpickle_list              | 2.69 us                                                     | 2.64 us: 1.02x faster                                        |
| bench_mp_pool              | 67.2 ms                                                     | 66.0 ms: 1.02x faster                                        |
| deepcopy                   | 233 us                                                      | 229 us: 1.02x faster                                         |
| json_dumps                 | 5.83 ms                                                     | 5.73 ms: 1.02x faster                                        |
| pickle_dict                | 18.9 us                                                     | 18.6 us: 1.02x faster                                        |
| sympy_sum                  | 90.1 ms                                                     | 88.7 ms: 1.02x faster                                        |
| pidigits                   | 150 ms                                                      | 148 ms: 1.01x faster                                         |
| json_loads                 | 13.6 us                                                     | 13.5 us: 1.01x faster                                        |
| sqlglot_parse              | 802 us                                                      | 793 us: 1.01x faster                                         |
| scimark_sor                | 79.8 ms                                                     | 78.9 ms: 1.01x faster                                        |
| scimark_lu                 | 57.5 ms                                                     | 56.9 ms: 1.01x faster                                        |
| richards_super             | 31.2 ms                                                     | 30.9 ms: 1.01x faster                                        |
| chameleon                  | 4.95 ms                                                     | 4.92 ms: 1.01x faster                                        |
| docutils                   | 1.61 sec                                                    | 1.61 sec: 1.00x slower                                       |
| xml_etree_generate         | 55.8 ms                                                     | 56.1 ms: 1.01x slower                                        |
| sqlglot_normalize          | 183 ms                                                      | 185 ms: 1.01x slower                                         |
| richards                   | 27.6 ms                                                     | 27.9 ms: 1.01x slower                                        |
| gc_traversal               | 1.49 ms                                                     | 1.50 ms: 1.01x slower                                        |
| async_tree_cpu_io_mixed_tg | 483 ms                                                      | 489 ms: 1.01x slower                                         |
| pathlib                    | 79.6 ms                                                     | 81.0 ms: 1.02x slower                                        |
| xml_etree_parse            | 90.5 ms                                                     | 92.2 ms: 1.02x slower                                        |
| regex_effbot               | 1.58 ms                                                     | 1.61 ms: 1.02x slower                                        |
| regex_dna                  | 119 ms                                                      | 122 ms: 1.02x slower                                         |
| async_generators           | 230 ms                                                      | 235 ms: 1.02x slower                                         |
| bench_thread_pool          | 830 us                                                      | 850 us: 1.02x slower                                         |
| async_tree_io              | 712 ms                                                      | 732 ms: 1.03x slower                                         |
| logging_format             | 6.72 us                                                     | 6.91 us: 1.03x slower                                        |
| dulwich_log                | 42.7 ms                                                     | 44.1 ms: 1.03x slower                                        |
| sympy_integrate            | 13.0 ms                                                     | 13.4 ms: 1.03x slower                                        |
| xml_etree_process          | 37.6 ms                                                     | 38.9 ms: 1.03x slower                                        |
| unpickle_pure_python       | 134 us                                                      | 139 us: 1.04x slower                                         |
| sqlglot_optimize           | 34.0 ms                                                     | 35.3 ms: 1.04x slower                                        |
| sympy_expand               | 278 ms                                                      | 289 ms: 1.04x slower                                         |
| async_tree_none_tg         | 277 ms                                                      | 287 ms: 1.04x slower                                         |
| logging_simple             | 6.21 us                                                     | 6.46 us: 1.04x slower                                        |
| 2to3                       | 213 ms                                                      | 222 ms: 1.05x slower                                         |
| async_tree_memoization     | 333 ms                                                      | 350 ms: 1.05x slower                                         |
| async_tree_io_tg           | 742 ms                                                      | 780 ms: 1.05x slower                                         |
| pprint_safe_repr           | 508 ms                                                      | 534 ms: 1.05x slower                                         |
| regex_compile              | 87.2 ms                                                     | 91.7 ms: 1.05x slower                                        |
| pprint_pformat             | 1.04 sec                                                    | 1.10 sec: 1.06x slower                                       |
| pycparser                  | 673 ms                                                      | 715 ms: 1.06x slower                                         |
| dask                       | 255 ms                                                      | 271 ms: 1.06x slower                                         |
| crypto_pyaes               | 46.4 ms                                                     | 49.4 ms: 1.06x slower                                        |
| xml_etree_iterparse        | 63.1 ms                                                     | 67.3 ms: 1.07x slower                                        |
| float                      | 54.7 ms                                                     | 58.2 ms: 1.07x slower                                        |
| nqueens                    | 61.7 ms                                                     | 65.9 ms: 1.07x slower                                        |
| async_tree_memoization_tg  | 345 ms                                                      | 369 ms: 1.07x slower                                         |
| go                         | 89.0 ms                                                     | 95.3 ms: 1.07x slower                                        |
| unpack_sequence            | 36.9 ns                                                     | 39.7 ns: 1.08x slower                                        |
| chaos                      | 42.1 ms                                                     | 45.5 ms: 1.08x slower                                        |
| mdp                        | 1.42 sec                                                    | 1.54 sec: 1.08x slower                                       |
| mako                       | 7.05 ms                                                     | 7.65 ms: 1.08x slower                                        |
| python_startup             | 18.8 ms                                                     | 20.5 ms: 1.09x slower                                        |
| tomli_loads                | 1.38 sec                                                    | 1.51 sec: 1.09x slower                                       |
| meteor_contest             | 72.1 ms                                                     | 79.0 ms: 1.10x slower                                        |
| pyflate                    | 294 ms                                                      | 326 ms: 1.11x slower                                         |
| telco                      | 4.08 ms                                                     | 4.62 ms: 1.13x slower                                        |
| asyncio_tcp                | 471 ms                                                      | 540 ms: 1.15x slower                                         |
| pickle_list                | 2.88 us                                                     | 3.31 us: 1.15x slower                                        |
| fannkuch                   | 244 ms                                                      | 282 ms: 1.15x slower                                         |
| tornado_http               | 87.2 ms                                                     | 101 ms: 1.16x slower                                         |
| python_startup_no_site     | 15.9 ms                                                     | 18.5 ms: 1.16x slower                                        |
| coverage                   | 39.8 ms                                                     | 46.3 ms: 1.16x slower                                        |
| scimark_monte_carlo        | 43.0 ms                                                     | 50.7 ms: 1.18x slower                                        |
| scimark_fft                | 181 ms                                                      | 219 ms: 1.21x slower                                         |
| nbody                      | 68.8 ms                                                     | 85.2 ms: 1.24x slower                                        |
| deltablue                  | 2.12 ms                                                     | 2.67 ms: 1.26x slower                                        |
| hexiom                     | 4.00 ms                                                     | 5.10 ms: 1.27x slower                                        |
| scimark_sparse_mat_mult    | 2.51 ms                                                     | 3.29 ms: 1.31x slower                                        |
| spectral_norm              | 63.9 ms                                                     | 87.4 ms: 1.37x slower                                        |
| mypy2                      | 209 ms                                                      | 295 ms: 1.41x slower                                         |
| regex_v8                   | 13.5 ms                                                     | 23.6 ms: 1.75x slower                                        |
| Geometric mean             | (ref)                                                       | 1.05x slower                                                 |

Benchmark hidden because not significant (6): asyncio_tcp_ssl, json, sqlglot_transpile, deepcopy_memo, sympy_str, create_gc_cycles
Ignored benchmarks (4) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, django_template, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.03x
- 95% likely to have a slowdown of 1.02x
- 99% likely to have a slowdown of 1.02x
