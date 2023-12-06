
# Results vs. base

- fork: python
- ref: 3faf8e586d36e73faba1
- machine: darwin-arm64
- commit hash: 3faf8e5
- commit date: 2023-11-25
- overall geometric mean: 1.06x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.02x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | results/bm-20231125-3.13.0a2+-3faf8e5-PYTHON_UOPS/bm-20231125-darwin-arm64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5.json | results/bm-20231125-3.13.0a2+-3faf8e5/bm-20231125-darwin-arm64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5.json |
|----------------|:-----------------------------------------------------------------------------------------------------------------------------:|:-----------------------------------------------------------------------------------------------------------------:|
| 2to3           | 182 ms                                                                                                                        | 174 ms: 1.04x faster                                                                                              |
| chameleon      | 5.28 ms                                                                                                                       | 5.13 ms: 1.03x faster                                                                                             |
| docutils       | 1.55 sec                                                                                                                      | 1.51 sec: 1.03x faster                                                                                            |
| Geometric mean | (ref)                                                                                                                         | 1.03x faster                                                                                                      |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | results/bm-20231125-3.13.0a2+-3faf8e5-PYTHON_UOPS/bm-20231125-darwin-arm64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5.json | results/bm-20231125-3.13.0a2+-3faf8e5/bm-20231125-darwin-arm64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5.json |
|----------------------------|:-----------------------------------------------------------------------------------------------------------------------------:|:-----------------------------------------------------------------------------------------------------------------:|
| async_tree_memoization_tg  | 346 ms                                                                                                                        | 332 ms: 1.04x faster                                                                                              |
| async_tree_none            | 264 ms                                                                                                                        | 254 ms: 1.04x faster                                                                                              |
| async_tree_none_tg         | 277 ms                                                                                                                        | 267 ms: 1.04x faster                                                                                              |
| async_tree_memoization     | 340 ms                                                                                                                        | 331 ms: 1.03x faster                                                                                              |
| async_tree_io_tg           | 700 ms                                                                                                                        | 686 ms: 1.02x faster                                                                                              |
| async_tree_io              | 718 ms                                                                                                                        | 704 ms: 1.02x faster                                                                                              |
| async_tree_cpu_io_mixed_tg | 553 ms                                                                                                                        | 542 ms: 1.02x faster                                                                                              |
| async_tree_cpu_io_mixed    | 535 ms                                                                                                                        | 526 ms: 1.02x faster                                                                                              |
| Geometric mean             | (ref)                                                                                                                         | 1.03x faster                                                                                                      |

Benchmarks with tag 'math':
===========================

| Benchmark      | results/bm-20231125-3.13.0a2+-3faf8e5-PYTHON_UOPS/bm-20231125-darwin-arm64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5.json | results/bm-20231125-3.13.0a2+-3faf8e5/bm-20231125-darwin-arm64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5.json |
|----------------|:-----------------------------------------------------------------------------------------------------------------------------:|:-----------------------------------------------------------------------------------------------------------------:|
| float          | 70.6 ms                                                                                                                       | 58.1 ms: 1.22x faster                                                                                             |
| nbody          | 91.1 ms                                                                                                                       | 81.9 ms: 1.11x faster                                                                                             |
| pidigits       | 283 ms                                                                                                                        | 282 ms: 1.00x faster                                                                                              |
| Geometric mean | (ref)                                                                                                                         | 1.11x faster                                                                                                      |

Benchmarks with tag 'regex':
============================

| Benchmark      | results/bm-20231125-3.13.0a2+-3faf8e5-PYTHON_UOPS/bm-20231125-darwin-arm64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5.json | results/bm-20231125-3.13.0a2+-3faf8e5/bm-20231125-darwin-arm64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5.json |
|----------------|:-----------------------------------------------------------------------------------------------------------------------------:|:-----------------------------------------------------------------------------------------------------------------:|
| regex_compile  | 89.9 ms                                                                                                                       | 79.5 ms: 1.13x faster                                                                                             |
| regex_v8       | 17.1 ms                                                                                                                       | 16.9 ms: 1.01x faster                                                                                             |
| regex_dna      | 152 ms                                                                                                                        | 152 ms: 1.00x faster                                                                                              |
| regex_effbot   | 2.60 ms                                                                                                                       | 2.64 ms: 1.02x slower                                                                                             |
| Geometric mean | (ref)                                                                                                                         | 1.03x faster                                                                                                      |

Benchmarks with tag 'serialize':
================================

| Benchmark            | results/bm-20231125-3.13.0a2+-3faf8e5-PYTHON_UOPS/bm-20231125-darwin-arm64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5.json | results/bm-20231125-3.13.0a2+-3faf8e5/bm-20231125-darwin-arm64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5.json |
|----------------------|:-----------------------------------------------------------------------------------------------------------------------------:|:-----------------------------------------------------------------------------------------------------------------:|
| unpickle_pure_python | 178 us                                                                                                                        | 165 us: 1.08x faster                                                                                              |
| xml_etree_generate   | 62.7 ms                                                                                                                       | 58.2 ms: 1.08x faster                                                                                             |
| tomli_loads          | 1.71 sec                                                                                                                      | 1.60 sec: 1.07x faster                                                                                            |
| xml_etree_iterparse  | 81.5 ms                                                                                                                       | 76.4 ms: 1.07x faster                                                                                             |
| xml_etree_process    | 42.5 ms                                                                                                                       | 40.6 ms: 1.05x faster                                                                                             |
| pickle_list          | 2.95 us                                                                                                                       | 2.89 us: 1.02x faster                                                                                             |
| json_dumps           | 6.64 ms                                                                                                                       | 6.55 ms: 1.01x faster                                                                                             |
| pickle_pure_python   | 210 us                                                                                                                        | 209 us: 1.00x faster                                                                                              |
| unpickle_list        | 3.14 us                                                                                                                       | 3.13 us: 1.00x faster                                                                                             |
| pickle_dict          | 17.9 us                                                                                                                       | 18.0 us: 1.01x slower                                                                                             |
| Geometric mean       | (ref)                                                                                                                         | 1.03x faster                                                                                                      |

Benchmark hidden because not significant (4): xml_etree_parse, unpickle, pickle, json_loads

Benchmarks with tag 'startup':
==============================

| Benchmark              | results/bm-20231125-3.13.0a2+-3faf8e5-PYTHON_UOPS/bm-20231125-darwin-arm64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5.json | results/bm-20231125-3.13.0a2+-3faf8e5/bm-20231125-darwin-arm64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5.json |
|------------------------|:-----------------------------------------------------------------------------------------------------------------------------:|:-----------------------------------------------------------------------------------------------------------------:|
| python_startup_no_site | 10.4 ms                                                                                                                       | 10.1 ms: 1.02x faster                                                                                             |
| python_startup         | 11.8 ms                                                                                                                       | 11.6 ms: 1.02x faster                                                                                             |
| Geometric mean         | (ref)                                                                                                                         | 1.02x faster                                                                                                      |

Benchmarks with tag 'template':
===============================

| Benchmark | results/bm-20231125-3.13.0a2+-3faf8e5-PYTHON_UOPS/bm-20231125-darwin-arm64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5.json | results/bm-20231125-3.13.0a2+-3faf8e5/bm-20231125-darwin-arm64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5.json |
|-----------|:-----------------------------------------------------------------------------------------------------------------------------:|:-----------------------------------------------------------------------------------------------------------------:|
| mako      | 9.81 ms                                                                                                                       | 7.78 ms: 1.26x faster                                                                                             |

All benchmarks:
===============

| Benchmark                  | results/bm-20231125-3.13.0a2+-3faf8e5-PYTHON_UOPS/bm-20231125-darwin-arm64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5.json | results/bm-20231125-3.13.0a2+-3faf8e5/bm-20231125-darwin-arm64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5.json |
|----------------------------|:-----------------------------------------------------------------------------------------------------------------------------:|:-----------------------------------------------------------------------------------------------------------------:|
| deltablue                  | 3.63 ms                                                                                                                       | 2.45 ms: 1.48x faster                                                                                             |
| spectral_norm              | 104 ms                                                                                                                        | 75.1 ms: 1.38x faster                                                                                             |
| scimark_sparse_mat_mult    | 4.30 ms                                                                                                                       | 3.17 ms: 1.36x faster                                                                                             |
| comprehensions             | 16.5 us                                                                                                                       | 12.6 us: 1.31x faster                                                                                             |
| mako                       | 9.81 ms                                                                                                                       | 7.78 ms: 1.26x faster                                                                                             |
| hexiom                     | 6.31 ms                                                                                                                       | 5.03 ms: 1.26x faster                                                                                             |
| scimark_monte_carlo        | 60.3 ms                                                                                                                       | 48.6 ms: 1.24x faster                                                                                             |
| float                      | 70.6 ms                                                                                                                       | 58.1 ms: 1.22x faster                                                                                             |
| scimark_fft                | 256 ms                                                                                                                        | 213 ms: 1.20x faster                                                                                              |
| fannkuch                   | 345 ms                                                                                                                        | 288 ms: 1.20x faster                                                                                              |
| chaos                      | 49.7 ms                                                                                                                       | 43.0 ms: 1.16x faster                                                                                             |
| nqueens                    | 71.9 ms                                                                                                                       | 62.6 ms: 1.15x faster                                                                                             |
| crypto_pyaes               | 55.7 ms                                                                                                                       | 49.2 ms: 1.13x faster                                                                                             |
| regex_compile              | 89.9 ms                                                                                                                       | 79.5 ms: 1.13x faster                                                                                             |
| pprint_pformat             | 1.23 sec                                                                                                                      | 1.09 sec: 1.13x faster                                                                                            |
| pprint_safe_repr           | 596 ms                                                                                                                        | 535 ms: 1.11x faster                                                                                              |
| nbody                      | 91.1 ms                                                                                                                       | 81.9 ms: 1.11x faster                                                                                             |
| sympy_sum                  | 84.8 ms                                                                                                                       | 76.6 ms: 1.11x faster                                                                                             |
| pyflate                    | 378 ms                                                                                                                        | 344 ms: 1.10x faster                                                                                              |
| sympy_integrate            | 12.3 ms                                                                                                                       | 11.2 ms: 1.10x faster                                                                                             |
| raytrace                   | 199 ms                                                                                                                        | 183 ms: 1.09x faster                                                                                              |
| meteor_contest             | 82.0 ms                                                                                                                       | 75.8 ms: 1.08x faster                                                                                             |
| sympy_str                  | 160 ms                                                                                                                        | 148 ms: 1.08x faster                                                                                              |
| unpickle_pure_python       | 178 us                                                                                                                        | 165 us: 1.08x faster                                                                                              |
| xml_etree_generate         | 62.7 ms                                                                                                                       | 58.2 ms: 1.08x faster                                                                                             |
| tomli_loads                | 1.71 sec                                                                                                                      | 1.60 sec: 1.07x faster                                                                                            |
| go                         | 113 ms                                                                                                                        | 106 ms: 1.07x faster                                                                                              |
| deepcopy_memo              | 27.8 us                                                                                                                       | 26.0 us: 1.07x faster                                                                                             |
| sqlglot_optimize           | 38.2 ms                                                                                                                       | 35.8 ms: 1.07x faster                                                                                             |
| xml_etree_iterparse        | 81.5 ms                                                                                                                       | 76.4 ms: 1.07x faster                                                                                             |
| sqlglot_normalize          | 204 ms                                                                                                                        | 192 ms: 1.06x faster                                                                                              |
| mdp                        | 1.73 sec                                                                                                                      | 1.64 sec: 1.05x faster                                                                                            |
| typing_runtime_protocols   | 81.6 us                                                                                                                       | 77.6 us: 1.05x faster                                                                                             |
| scimark_lu                 | 78.4 ms                                                                                                                       | 74.8 ms: 1.05x faster                                                                                             |
| xml_etree_process          | 42.5 ms                                                                                                                       | 40.6 ms: 1.05x faster                                                                                             |
| telco                      | 4.86 ms                                                                                                                       | 4.65 ms: 1.04x faster                                                                                             |
| 2to3                       | 182 ms                                                                                                                        | 174 ms: 1.04x faster                                                                                              |
| sqlite_synth               | 1.71 us                                                                                                                       | 1.64 us: 1.04x faster                                                                                             |
| async_tree_memoization_tg  | 346 ms                                                                                                                        | 332 ms: 1.04x faster                                                                                              |
| sqlglot_parse              | 867 us                                                                                                                        | 834 us: 1.04x faster                                                                                              |
| async_tree_none            | 264 ms                                                                                                                        | 254 ms: 1.04x faster                                                                                              |
| sqlglot_transpile          | 1.05 ms                                                                                                                       | 1.01 ms: 1.04x faster                                                                                             |
| async_tree_none_tg         | 277 ms                                                                                                                        | 267 ms: 1.04x faster                                                                                              |
| bench_thread_pool          | 534 us                                                                                                                        | 516 us: 1.03x faster                                                                                              |
| coroutines                 | 19.9 ms                                                                                                                       | 19.2 ms: 1.03x faster                                                                                             |
| sympy_expand               | 264 ms                                                                                                                        | 256 ms: 1.03x faster                                                                                              |
| chameleon                  | 5.28 ms                                                                                                                       | 5.13 ms: 1.03x faster                                                                                             |
| async_generators           | 313 ms                                                                                                                        | 304 ms: 1.03x faster                                                                                              |
| async_tree_memoization     | 340 ms                                                                                                                        | 331 ms: 1.03x faster                                                                                              |
| logging_silent             | 73.2 ns                                                                                                                       | 71.4 ns: 1.03x faster                                                                                             |
| docutils                   | 1.55 sec                                                                                                                      | 1.51 sec: 1.03x faster                                                                                            |
| python_startup_no_site     | 10.4 ms                                                                                                                       | 10.1 ms: 1.02x faster                                                                                             |
| logging_simple             | 3.71 us                                                                                                                       | 3.63 us: 1.02x faster                                                                                             |
| async_tree_io_tg           | 700 ms                                                                                                                        | 686 ms: 1.02x faster                                                                                              |
| deepcopy                   | 239 us                                                                                                                        | 234 us: 1.02x faster                                                                                              |
| scimark_sor                | 109 ms                                                                                                                        | 107 ms: 1.02x faster                                                                                              |
| async_tree_io              | 718 ms                                                                                                                        | 704 ms: 1.02x faster                                                                                              |
| pickle_list                | 2.95 us                                                                                                                       | 2.89 us: 1.02x faster                                                                                             |
| async_tree_cpu_io_mixed_tg | 553 ms                                                                                                                        | 542 ms: 1.02x faster                                                                                              |
| logging_format             | 4.02 us                                                                                                                       | 3.95 us: 1.02x faster                                                                                             |
| bench_mp_pool              | 44.6 ms                                                                                                                       | 43.8 ms: 1.02x faster                                                                                             |
| async_tree_cpu_io_mixed    | 535 ms                                                                                                                        | 526 ms: 1.02x faster                                                                                              |
| dulwich_log                | 30.6 ms                                                                                                                       | 30.1 ms: 1.02x faster                                                                                             |
| dask                       | 233 ms                                                                                                                        | 229 ms: 1.02x faster                                                                                              |
| python_startup             | 11.8 ms                                                                                                                       | 11.6 ms: 1.02x faster                                                                                             |
| deepcopy_reduce            | 2.11 us                                                                                                                       | 2.08 us: 1.01x faster                                                                                             |
| json_dumps                 | 6.64 ms                                                                                                                       | 6.55 ms: 1.01x faster                                                                                             |
| json                       | 3.04 ms                                                                                                                       | 3.01 ms: 1.01x faster                                                                                             |
| regex_v8                   | 17.1 ms                                                                                                                       | 16.9 ms: 1.01x faster                                                                                             |
| pycparser                  | 719 ms                                                                                                                        | 712 ms: 1.01x faster                                                                                              |
| pickle_pure_python         | 210 us                                                                                                                        | 209 us: 1.00x faster                                                                                              |
| unpickle_list              | 3.14 us                                                                                                                       | 3.13 us: 1.00x faster                                                                                             |
| pidigits                   | 283 ms                                                                                                                        | 282 ms: 1.00x faster                                                                                              |
| regex_dna                  | 152 ms                                                                                                                        | 152 ms: 1.00x faster                                                                                              |
| generators                 | 26.0 ms                                                                                                                       | 26.1 ms: 1.00x slower                                                                                             |
| pickle_dict                | 17.9 us                                                                                                                       | 18.0 us: 1.01x slower                                                                                             |
| unpack_sequence            | 28.6 ns                                                                                                                       | 29.0 ns: 1.01x slower                                                                                             |
| regex_effbot               | 2.60 ms                                                                                                                       | 2.64 ms: 1.02x slower                                                                                             |
| richards_super             | 38.0 ms                                                                                                                       | 38.9 ms: 1.02x slower                                                                                             |
| richards                   | 34.1 ms                                                                                                                       | 34.8 ms: 1.02x slower                                                                                             |
| Geometric mean             | (ref)                                                                                                                         | 1.06x faster                                                                                                      |

Benchmark hidden because not significant (13): mypy2, tornado_http, xml_etree_parse, pathlib, unpickle, gc_traversal, pickle, coverage, asyncio_tcp_ssl, asyncio_websockets, create_gc_cycles, json_loads, asyncio_tcp


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.03x
- 95% likely to have a speedup of 1.02x
- 99% likely to have a speedup of 1.02x
