
# Results vs. base

- fork: python
- ref: 3faf8e586d36e73faba1
- machine: darwin-arm64
- commit hash: 3faf8e5
- commit date: 2023-11-25
- overall geometric mean: 1.06x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.02x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | results/bm-20231125-3.13.0a2+-3faf8e5/bm-20231125-darwin-arm64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5.json | results/bm-20231125-3.13.0a2+-3faf8e5-PYTHON_UOPS/bm-20231125-darwin-arm64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5.json |
|----------------|:-----------------------------------------------------------------------------------------------------------------:|:-----------------------------------------------------------------------------------------------------------------------------:|
| 2to3           | 174 ms                                                                                                            | 182 ms: 1.04x slower                                                                                                          |
| chameleon      | 5.13 ms                                                                                                           | 5.28 ms: 1.03x slower                                                                                                         |
| docutils       | 1.51 sec                                                                                                          | 1.55 sec: 1.03x slower                                                                                                        |
| Geometric mean | (ref)                                                                                                             | 1.03x slower                                                                                                                  |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | results/bm-20231125-3.13.0a2+-3faf8e5/bm-20231125-darwin-arm64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5.json | results/bm-20231125-3.13.0a2+-3faf8e5-PYTHON_UOPS/bm-20231125-darwin-arm64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5.json |
|----------------------------|:-----------------------------------------------------------------------------------------------------------------:|:-----------------------------------------------------------------------------------------------------------------------------:|
| async_tree_cpu_io_mixed    | 526 ms                                                                                                            | 535 ms: 1.02x slower                                                                                                          |
| async_tree_cpu_io_mixed_tg | 542 ms                                                                                                            | 553 ms: 1.02x slower                                                                                                          |
| async_tree_io              | 704 ms                                                                                                            | 718 ms: 1.02x slower                                                                                                          |
| async_tree_io_tg           | 686 ms                                                                                                            | 700 ms: 1.02x slower                                                                                                          |
| async_tree_memoization     | 331 ms                                                                                                            | 340 ms: 1.03x slower                                                                                                          |
| async_tree_none_tg         | 267 ms                                                                                                            | 277 ms: 1.04x slower                                                                                                          |
| async_tree_none            | 254 ms                                                                                                            | 264 ms: 1.04x slower                                                                                                          |
| async_tree_memoization_tg  | 332 ms                                                                                                            | 346 ms: 1.04x slower                                                                                                          |
| Geometric mean             | (ref)                                                                                                             | 1.03x slower                                                                                                                  |

Benchmarks with tag 'math':
===========================

| Benchmark      | results/bm-20231125-3.13.0a2+-3faf8e5/bm-20231125-darwin-arm64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5.json | results/bm-20231125-3.13.0a2+-3faf8e5-PYTHON_UOPS/bm-20231125-darwin-arm64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5.json |
|----------------|:-----------------------------------------------------------------------------------------------------------------:|:-----------------------------------------------------------------------------------------------------------------------------:|
| pidigits       | 282 ms                                                                                                            | 283 ms: 1.00x slower                                                                                                          |
| nbody          | 81.9 ms                                                                                                           | 91.1 ms: 1.11x slower                                                                                                         |
| float          | 58.1 ms                                                                                                           | 70.6 ms: 1.22x slower                                                                                                         |
| Geometric mean | (ref)                                                                                                             | 1.11x slower                                                                                                                  |

Benchmarks with tag 'regex':
============================

| Benchmark      | results/bm-20231125-3.13.0a2+-3faf8e5/bm-20231125-darwin-arm64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5.json | results/bm-20231125-3.13.0a2+-3faf8e5-PYTHON_UOPS/bm-20231125-darwin-arm64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5.json |
|----------------|:-----------------------------------------------------------------------------------------------------------------:|:-----------------------------------------------------------------------------------------------------------------------------:|
| regex_effbot   | 2.64 ms                                                                                                           | 2.60 ms: 1.02x faster                                                                                                         |
| regex_dna      | 152 ms                                                                                                            | 152 ms: 1.00x slower                                                                                                          |
| regex_v8       | 16.9 ms                                                                                                           | 17.1 ms: 1.01x slower                                                                                                         |
| regex_compile  | 79.5 ms                                                                                                           | 89.9 ms: 1.13x slower                                                                                                         |
| Geometric mean | (ref)                                                                                                             | 1.03x slower                                                                                                                  |

Benchmarks with tag 'serialize':
================================

| Benchmark            | results/bm-20231125-3.13.0a2+-3faf8e5/bm-20231125-darwin-arm64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5.json | results/bm-20231125-3.13.0a2+-3faf8e5-PYTHON_UOPS/bm-20231125-darwin-arm64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5.json |
|----------------------|:-----------------------------------------------------------------------------------------------------------------:|:-----------------------------------------------------------------------------------------------------------------------------:|
| pickle_dict          | 18.0 us                                                                                                           | 17.9 us: 1.01x faster                                                                                                         |
| unpickle_list        | 3.13 us                                                                                                           | 3.14 us: 1.00x slower                                                                                                         |
| pickle_pure_python   | 209 us                                                                                                            | 210 us: 1.00x slower                                                                                                          |
| json_dumps           | 6.55 ms                                                                                                           | 6.64 ms: 1.01x slower                                                                                                         |
| pickle_list          | 2.89 us                                                                                                           | 2.95 us: 1.02x slower                                                                                                         |
| xml_etree_process    | 40.6 ms                                                                                                           | 42.5 ms: 1.05x slower                                                                                                         |
| xml_etree_iterparse  | 76.4 ms                                                                                                           | 81.5 ms: 1.07x slower                                                                                                         |
| tomli_loads          | 1.60 sec                                                                                                          | 1.71 sec: 1.07x slower                                                                                                        |
| xml_etree_generate   | 58.2 ms                                                                                                           | 62.7 ms: 1.08x slower                                                                                                         |
| unpickle_pure_python | 165 us                                                                                                            | 178 us: 1.08x slower                                                                                                          |
| Geometric mean       | (ref)                                                                                                             | 1.03x slower                                                                                                                  |

Benchmark hidden because not significant (4): json_loads, pickle, unpickle, xml_etree_parse

Benchmarks with tag 'startup':
==============================

| Benchmark              | results/bm-20231125-3.13.0a2+-3faf8e5/bm-20231125-darwin-arm64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5.json | results/bm-20231125-3.13.0a2+-3faf8e5-PYTHON_UOPS/bm-20231125-darwin-arm64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5.json |
|------------------------|:-----------------------------------------------------------------------------------------------------------------:|:-----------------------------------------------------------------------------------------------------------------------------:|
| python_startup         | 11.6 ms                                                                                                           | 11.8 ms: 1.02x slower                                                                                                         |
| python_startup_no_site | 10.1 ms                                                                                                           | 10.4 ms: 1.02x slower                                                                                                         |
| Geometric mean         | (ref)                                                                                                             | 1.02x slower                                                                                                                  |

Benchmarks with tag 'template':
===============================

| Benchmark | results/bm-20231125-3.13.0a2+-3faf8e5/bm-20231125-darwin-arm64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5.json | results/bm-20231125-3.13.0a2+-3faf8e5-PYTHON_UOPS/bm-20231125-darwin-arm64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5.json |
|-----------|:-----------------------------------------------------------------------------------------------------------------:|:-----------------------------------------------------------------------------------------------------------------------------:|
| mako      | 7.78 ms                                                                                                           | 9.81 ms: 1.26x slower                                                                                                         |

All benchmarks:
===============

| Benchmark                  | results/bm-20231125-3.13.0a2+-3faf8e5/bm-20231125-darwin-arm64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5.json | results/bm-20231125-3.13.0a2+-3faf8e5-PYTHON_UOPS/bm-20231125-darwin-arm64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5.json |
|----------------------------|:-----------------------------------------------------------------------------------------------------------------:|:-----------------------------------------------------------------------------------------------------------------------------:|
| richards                   | 34.8 ms                                                                                                           | 34.1 ms: 1.02x faster                                                                                                         |
| richards_super             | 38.9 ms                                                                                                           | 38.0 ms: 1.02x faster                                                                                                         |
| regex_effbot               | 2.64 ms                                                                                                           | 2.60 ms: 1.02x faster                                                                                                         |
| unpack_sequence            | 29.0 ns                                                                                                           | 28.6 ns: 1.01x faster                                                                                                         |
| pickle_dict                | 18.0 us                                                                                                           | 17.9 us: 1.01x faster                                                                                                         |
| generators                 | 26.1 ms                                                                                                           | 26.0 ms: 1.00x faster                                                                                                         |
| regex_dna                  | 152 ms                                                                                                            | 152 ms: 1.00x slower                                                                                                          |
| pidigits                   | 282 ms                                                                                                            | 283 ms: 1.00x slower                                                                                                          |
| unpickle_list              | 3.13 us                                                                                                           | 3.14 us: 1.00x slower                                                                                                         |
| pickle_pure_python         | 209 us                                                                                                            | 210 us: 1.00x slower                                                                                                          |
| pycparser                  | 712 ms                                                                                                            | 719 ms: 1.01x slower                                                                                                          |
| regex_v8                   | 16.9 ms                                                                                                           | 17.1 ms: 1.01x slower                                                                                                         |
| json                       | 3.01 ms                                                                                                           | 3.04 ms: 1.01x slower                                                                                                         |
| json_dumps                 | 6.55 ms                                                                                                           | 6.64 ms: 1.01x slower                                                                                                         |
| deepcopy_reduce            | 2.08 us                                                                                                           | 2.11 us: 1.01x slower                                                                                                         |
| python_startup             | 11.6 ms                                                                                                           | 11.8 ms: 1.02x slower                                                                                                         |
| dask                       | 229 ms                                                                                                            | 233 ms: 1.02x slower                                                                                                          |
| dulwich_log                | 30.1 ms                                                                                                           | 30.6 ms: 1.02x slower                                                                                                         |
| async_tree_cpu_io_mixed    | 526 ms                                                                                                            | 535 ms: 1.02x slower                                                                                                          |
| bench_mp_pool              | 43.8 ms                                                                                                           | 44.6 ms: 1.02x slower                                                                                                         |
| logging_format             | 3.95 us                                                                                                           | 4.02 us: 1.02x slower                                                                                                         |
| async_tree_cpu_io_mixed_tg | 542 ms                                                                                                            | 553 ms: 1.02x slower                                                                                                          |
| pickle_list                | 2.89 us                                                                                                           | 2.95 us: 1.02x slower                                                                                                         |
| async_tree_io              | 704 ms                                                                                                            | 718 ms: 1.02x slower                                                                                                          |
| scimark_sor                | 107 ms                                                                                                            | 109 ms: 1.02x slower                                                                                                          |
| deepcopy                   | 234 us                                                                                                            | 239 us: 1.02x slower                                                                                                          |
| async_tree_io_tg           | 686 ms                                                                                                            | 700 ms: 1.02x slower                                                                                                          |
| logging_simple             | 3.63 us                                                                                                           | 3.71 us: 1.02x slower                                                                                                         |
| python_startup_no_site     | 10.1 ms                                                                                                           | 10.4 ms: 1.02x slower                                                                                                         |
| docutils                   | 1.51 sec                                                                                                          | 1.55 sec: 1.03x slower                                                                                                        |
| logging_silent             | 71.4 ns                                                                                                           | 73.2 ns: 1.03x slower                                                                                                         |
| async_tree_memoization     | 331 ms                                                                                                            | 340 ms: 1.03x slower                                                                                                          |
| async_generators           | 304 ms                                                                                                            | 313 ms: 1.03x slower                                                                                                          |
| chameleon                  | 5.13 ms                                                                                                           | 5.28 ms: 1.03x slower                                                                                                         |
| sympy_expand               | 256 ms                                                                                                            | 264 ms: 1.03x slower                                                                                                          |
| coroutines                 | 19.2 ms                                                                                                           | 19.9 ms: 1.03x slower                                                                                                         |
| bench_thread_pool          | 516 us                                                                                                            | 534 us: 1.03x slower                                                                                                          |
| async_tree_none_tg         | 267 ms                                                                                                            | 277 ms: 1.04x slower                                                                                                          |
| sqlglot_transpile          | 1.01 ms                                                                                                           | 1.05 ms: 1.04x slower                                                                                                         |
| async_tree_none            | 254 ms                                                                                                            | 264 ms: 1.04x slower                                                                                                          |
| sqlglot_parse              | 834 us                                                                                                            | 867 us: 1.04x slower                                                                                                          |
| async_tree_memoization_tg  | 332 ms                                                                                                            | 346 ms: 1.04x slower                                                                                                          |
| sqlite_synth               | 1.64 us                                                                                                           | 1.71 us: 1.04x slower                                                                                                         |
| 2to3                       | 174 ms                                                                                                            | 182 ms: 1.04x slower                                                                                                          |
| telco                      | 4.65 ms                                                                                                           | 4.86 ms: 1.04x slower                                                                                                         |
| xml_etree_process          | 40.6 ms                                                                                                           | 42.5 ms: 1.05x slower                                                                                                         |
| scimark_lu                 | 74.8 ms                                                                                                           | 78.4 ms: 1.05x slower                                                                                                         |
| typing_runtime_protocols   | 77.6 us                                                                                                           | 81.6 us: 1.05x slower                                                                                                         |
| mdp                        | 1.64 sec                                                                                                          | 1.73 sec: 1.05x slower                                                                                                        |
| sqlglot_normalize          | 192 ms                                                                                                            | 204 ms: 1.06x slower                                                                                                          |
| xml_etree_iterparse        | 76.4 ms                                                                                                           | 81.5 ms: 1.07x slower                                                                                                         |
| sqlglot_optimize           | 35.8 ms                                                                                                           | 38.2 ms: 1.07x slower                                                                                                         |
| deepcopy_memo              | 26.0 us                                                                                                           | 27.8 us: 1.07x slower                                                                                                         |
| go                         | 106 ms                                                                                                            | 113 ms: 1.07x slower                                                                                                          |
| tomli_loads                | 1.60 sec                                                                                                          | 1.71 sec: 1.07x slower                                                                                                        |
| xml_etree_generate         | 58.2 ms                                                                                                           | 62.7 ms: 1.08x slower                                                                                                         |
| unpickle_pure_python       | 165 us                                                                                                            | 178 us: 1.08x slower                                                                                                          |
| sympy_str                  | 148 ms                                                                                                            | 160 ms: 1.08x slower                                                                                                          |
| meteor_contest             | 75.8 ms                                                                                                           | 82.0 ms: 1.08x slower                                                                                                         |
| raytrace                   | 183 ms                                                                                                            | 199 ms: 1.09x slower                                                                                                          |
| sympy_integrate            | 11.2 ms                                                                                                           | 12.3 ms: 1.10x slower                                                                                                         |
| pyflate                    | 344 ms                                                                                                            | 378 ms: 1.10x slower                                                                                                          |
| sympy_sum                  | 76.6 ms                                                                                                           | 84.8 ms: 1.11x slower                                                                                                         |
| nbody                      | 81.9 ms                                                                                                           | 91.1 ms: 1.11x slower                                                                                                         |
| pprint_safe_repr           | 535 ms                                                                                                            | 596 ms: 1.11x slower                                                                                                          |
| pprint_pformat             | 1.09 sec                                                                                                          | 1.23 sec: 1.13x slower                                                                                                        |
| regex_compile              | 79.5 ms                                                                                                           | 89.9 ms: 1.13x slower                                                                                                         |
| crypto_pyaes               | 49.2 ms                                                                                                           | 55.7 ms: 1.13x slower                                                                                                         |
| nqueens                    | 62.6 ms                                                                                                           | 71.9 ms: 1.15x slower                                                                                                         |
| chaos                      | 43.0 ms                                                                                                           | 49.7 ms: 1.16x slower                                                                                                         |
| fannkuch                   | 288 ms                                                                                                            | 345 ms: 1.20x slower                                                                                                          |
| scimark_fft                | 213 ms                                                                                                            | 256 ms: 1.20x slower                                                                                                          |
| float                      | 58.1 ms                                                                                                           | 70.6 ms: 1.22x slower                                                                                                         |
| scimark_monte_carlo        | 48.6 ms                                                                                                           | 60.3 ms: 1.24x slower                                                                                                         |
| hexiom                     | 5.03 ms                                                                                                           | 6.31 ms: 1.26x slower                                                                                                         |
| mako                       | 7.78 ms                                                                                                           | 9.81 ms: 1.26x slower                                                                                                         |
| comprehensions             | 12.6 us                                                                                                           | 16.5 us: 1.31x slower                                                                                                         |
| scimark_sparse_mat_mult    | 3.17 ms                                                                                                           | 4.30 ms: 1.36x slower                                                                                                         |
| spectral_norm              | 75.1 ms                                                                                                           | 104 ms: 1.38x slower                                                                                                          |
| deltablue                  | 2.45 ms                                                                                                           | 3.63 ms: 1.48x slower                                                                                                         |
| Geometric mean             | (ref)                                                                                                             | 1.06x slower                                                                                                                  |

Benchmark hidden because not significant (13): asyncio_tcp, json_loads, create_gc_cycles, asyncio_websockets, asyncio_tcp_ssl, coverage, pickle, gc_traversal, unpickle, pathlib, xml_etree_parse, tornado_http, mypy2


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.03x
- 95% likely to have a slowdown of 1.02x
- 99% likely to have a slowdown of 1.02x
