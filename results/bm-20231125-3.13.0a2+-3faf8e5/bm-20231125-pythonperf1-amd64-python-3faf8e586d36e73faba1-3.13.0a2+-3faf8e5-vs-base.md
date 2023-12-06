
# Results vs. base

- fork: python
- ref: 3faf8e586d36e73faba1
- machine: windows-amd64
- commit hash: 3faf8e5
- commit date: 2023-11-25
- overall geometric mean: 1.03x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.01x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | results/bm-20231125-3.13.0a2+-3faf8e5-PYTHON_UOPS/bm-20231125-pythonperf1-amd64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5.json | results/bm-20231125-3.13.0a2+-3faf8e5/bm-20231125-pythonperf1-amd64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5.json |
|----------------|:----------------------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| 2to3           | 231 ms                                                                                                                             | 227 ms: 1.02x faster                                                                                                   |
| docutils       | 1.72 sec                                                                                                                           | 1.64 sec: 1.04x faster                                                                                                 |
| Geometric mean | (ref)                                                                                                                              | 1.02x faster                                                                                                           |

Benchmark hidden because not significant (2): chameleon, tornado_http

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | results/bm-20231125-3.13.0a2+-3faf8e5-PYTHON_UOPS/bm-20231125-pythonperf1-amd64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5.json | results/bm-20231125-3.13.0a2+-3faf8e5/bm-20231125-pythonperf1-amd64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5.json |
|----------------------------|:----------------------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| async_tree_none_tg         | 308 ms                                                                                                                             | 301 ms: 1.02x faster                                                                                                   |
| async_tree_none            | 287 ms                                                                                                                             | 281 ms: 1.02x faster                                                                                                   |
| async_tree_memoization     | 370 ms                                                                                                                             | 363 ms: 1.02x faster                                                                                                   |
| async_tree_io_tg           | 818 ms                                                                                                                             | 809 ms: 1.01x faster                                                                                                   |
| async_tree_cpu_io_mixed_tg | 523 ms                                                                                                                             | 543 ms: 1.04x slower                                                                                                   |
| async_tree_cpu_io_mixed    | 495 ms                                                                                                                             | 516 ms: 1.04x slower                                                                                                   |
| Geometric mean             | (ref)                                                                                                                              | 1.00x slower                                                                                                           |

Benchmark hidden because not significant (2): async_tree_io, async_tree_memoization_tg

Benchmarks with tag 'math':
===========================

| Benchmark      | results/bm-20231125-3.13.0a2+-3faf8e5-PYTHON_UOPS/bm-20231125-pythonperf1-amd64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5.json | results/bm-20231125-3.13.0a2+-3faf8e5/bm-20231125-pythonperf1-amd64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5.json |
|----------------|:----------------------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| nbody          | 83.2 ms                                                                                                                            | 75.8 ms: 1.10x faster                                                                                                  |
| float          | 57.7 ms                                                                                                                            | 55.0 ms: 1.05x faster                                                                                                  |
| pidigits       | 151 ms                                                                                                                             | 155 ms: 1.03x slower                                                                                                   |
| Geometric mean | (ref)                                                                                                                              | 1.04x faster                                                                                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | results/bm-20231125-3.13.0a2+-3faf8e5-PYTHON_UOPS/bm-20231125-pythonperf1-amd64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5.json | results/bm-20231125-3.13.0a2+-3faf8e5/bm-20231125-pythonperf1-amd64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5.json |
|----------------|:----------------------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| regex_v8       | 19.4 ms                                                                                                                            | 15.5 ms: 1.25x faster                                                                                                  |
| regex_compile  | 95.9 ms                                                                                                                            | 87.7 ms: 1.09x faster                                                                                                  |
| regex_dna      | 123 ms                                                                                                                             | 125 ms: 1.02x slower                                                                                                   |
| regex_effbot   | 1.74 ms                                                                                                                            | 1.90 ms: 1.09x slower                                                                                                  |
| Geometric mean | (ref)                                                                                                                              | 1.05x faster                                                                                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | results/bm-20231125-3.13.0a2+-3faf8e5-PYTHON_UOPS/bm-20231125-pythonperf1-amd64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5.json | results/bm-20231125-3.13.0a2+-3faf8e5/bm-20231125-pythonperf1-amd64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5.json |
|----------------------|:----------------------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| pickle_list          | 3.21 us                                                                                                                            | 2.88 us: 1.12x faster                                                                                                  |
| unpickle_list        | 2.79 us                                                                                                                            | 2.68 us: 1.04x faster                                                                                                  |
| unpickle_pure_python | 148 us                                                                                                                             | 143 us: 1.04x faster                                                                                                   |
| xml_etree_iterparse  | 68.4 ms                                                                                                                            | 66.2 ms: 1.03x faster                                                                                                  |
| xml_etree_process    | 41.3 ms                                                                                                                            | 40.3 ms: 1.03x faster                                                                                                  |
| pickle_pure_python   | 199 us                                                                                                                             | 194 us: 1.02x faster                                                                                                   |
| pickle_dict          | 19.3 us                                                                                                                            | 18.9 us: 1.02x faster                                                                                                  |
| unpickle             | 8.87 us                                                                                                                            | 8.75 us: 1.01x faster                                                                                                  |
| xml_etree_generate   | 59.6 ms                                                                                                                            | 59.0 ms: 1.01x faster                                                                                                  |
| xml_etree_parse      | 94.2 ms                                                                                                                            | 95.5 ms: 1.01x slower                                                                                                  |
| pickle               | 7.12 us                                                                                                                            | 7.27 us: 1.02x slower                                                                                                  |
| json_loads           | 14.5 us                                                                                                                            | 15.1 us: 1.04x slower                                                                                                  |
| tomli_loads          | 1.50 sec                                                                                                                           | 1.55 sec: 1.04x slower                                                                                                 |
| json_dumps           | 6.08 ms                                                                                                                            | 6.43 ms: 1.06x slower                                                                                                  |
| Geometric mean       | (ref)                                                                                                                              | 1.01x faster                                                                                                           |

Benchmarks with tag 'startup':
==============================

Benchmark hidden because not significant (2): python_startup_no_site, python_startup

Benchmarks with tag 'template':
===============================

Benchmark hidden because not significant (1): mako

All benchmarks:
===============

| Benchmark                  | results/bm-20231125-3.13.0a2+-3faf8e5-PYTHON_UOPS/bm-20231125-pythonperf1-amd64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5.json | results/bm-20231125-3.13.0a2+-3faf8e5/bm-20231125-pythonperf1-amd64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5.json |
|----------------------------|:----------------------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| regex_v8                   | 19.4 ms                                                                                                                            | 15.5 ms: 1.25x faster                                                                                                  |
| spectral_norm              | 86.2 ms                                                                                                                            | 71.2 ms: 1.21x faster                                                                                                  |
| deltablue                  | 2.80 ms                                                                                                                            | 2.31 ms: 1.21x faster                                                                                                  |
| comprehensions             | 13.5 us                                                                                                                            | 11.3 us: 1.19x faster                                                                                                  |
| scimark_monte_carlo        | 50.3 ms                                                                                                                            | 42.6 ms: 1.18x faster                                                                                                  |
| hexiom                     | 5.10 ms                                                                                                                            | 4.36 ms: 1.17x faster                                                                                                  |
| unpack_sequence            | 44.4 ns                                                                                                                            | 39.6 ns: 1.12x faster                                                                                                  |
| pickle_list                | 3.21 us                                                                                                                            | 2.88 us: 1.12x faster                                                                                                  |
| chaos                      | 46.5 ms                                                                                                                            | 41.7 ms: 1.11x faster                                                                                                  |
| fannkuch                   | 283 ms                                                                                                                             | 256 ms: 1.10x faster                                                                                                   |
| nbody                      | 83.2 ms                                                                                                                            | 75.8 ms: 1.10x faster                                                                                                  |
| regex_compile              | 95.9 ms                                                                                                                            | 87.7 ms: 1.09x faster                                                                                                  |
| go                         | 99.8 ms                                                                                                                            | 91.7 ms: 1.09x faster                                                                                                  |
| sympy_sum                  | 93.5 ms                                                                                                                            | 86.7 ms: 1.08x faster                                                                                                  |
| nqueens                    | 68.5 ms                                                                                                                            | 63.6 ms: 1.08x faster                                                                                                  |
| raytrace                   | 188 ms                                                                                                                             | 175 ms: 1.07x faster                                                                                                   |
| pyflate                    | 334 ms                                                                                                                             | 311 ms: 1.07x faster                                                                                                   |
| sqlglot_optimize           | 38.2 ms                                                                                                                            | 35.7 ms: 1.07x faster                                                                                                  |
| scimark_sparse_mat_mult    | 3.06 ms                                                                                                                            | 2.87 ms: 1.07x faster                                                                                                  |
| sqlglot_normalize          | 202 ms                                                                                                                             | 190 ms: 1.07x faster                                                                                                   |
| pprint_pformat             | 1.16 sec                                                                                                                           | 1.09 sec: 1.07x faster                                                                                                 |
| sympy_integrate            | 14.0 ms                                                                                                                            | 13.2 ms: 1.06x faster                                                                                                  |
| sympy_expand               | 305 ms                                                                                                                             | 289 ms: 1.06x faster                                                                                                   |
| typing_runtime_protocols   | 85.8 us                                                                                                                            | 81.4 us: 1.05x faster                                                                                                  |
| sympy_str                  | 179 ms                                                                                                                             | 170 ms: 1.05x faster                                                                                                   |
| scimark_fft                | 212 ms                                                                                                                             | 202 ms: 1.05x faster                                                                                                   |
| logging_simple             | 6.69 us                                                                                                                            | 6.37 us: 1.05x faster                                                                                                  |
| float                      | 57.7 ms                                                                                                                            | 55.0 ms: 1.05x faster                                                                                                  |
| logging_format             | 7.26 us                                                                                                                            | 6.92 us: 1.05x faster                                                                                                  |
| scimark_lu                 | 63.3 ms                                                                                                                            | 60.5 ms: 1.05x faster                                                                                                  |
| pprint_safe_repr           | 559 ms                                                                                                                             | 534 ms: 1.05x faster                                                                                                   |
| docutils                   | 1.72 sec                                                                                                                           | 1.64 sec: 1.04x faster                                                                                                 |
| crypto_pyaes               | 48.2 ms                                                                                                                            | 46.2 ms: 1.04x faster                                                                                                  |
| sqlglot_parse              | 867 us                                                                                                                             | 831 us: 1.04x faster                                                                                                   |
| unpickle_list              | 2.79 us                                                                                                                            | 2.68 us: 1.04x faster                                                                                                  |
| unpickle_pure_python       | 148 us                                                                                                                             | 143 us: 1.04x faster                                                                                                   |
| xml_etree_iterparse        | 68.4 ms                                                                                                                            | 66.2 ms: 1.03x faster                                                                                                  |
| deepcopy_reduce            | 2.20 us                                                                                                                            | 2.14 us: 1.03x faster                                                                                                  |
| sqlglot_transpile          | 1.10 ms                                                                                                                            | 1.07 ms: 1.03x faster                                                                                                  |
| dask                       | 278 ms                                                                                                                             | 270 ms: 1.03x faster                                                                                                   |
| dulwich_log                | 46.7 ms                                                                                                                            | 45.4 ms: 1.03x faster                                                                                                  |
| xml_etree_process          | 41.3 ms                                                                                                                            | 40.3 ms: 1.03x faster                                                                                                  |
| pickle_pure_python         | 199 us                                                                                                                             | 194 us: 1.02x faster                                                                                                   |
| async_tree_none_tg         | 308 ms                                                                                                                             | 301 ms: 1.02x faster                                                                                                   |
| async_tree_none            | 287 ms                                                                                                                             | 281 ms: 1.02x faster                                                                                                   |
| pickle_dict                | 19.3 us                                                                                                                            | 18.9 us: 1.02x faster                                                                                                  |
| meteor_contest             | 78.7 ms                                                                                                                            | 77.0 ms: 1.02x faster                                                                                                  |
| scimark_sor                | 84.5 ms                                                                                                                            | 82.9 ms: 1.02x faster                                                                                                  |
| logging_silent             | 64.5 ns                                                                                                                            | 63.3 ns: 1.02x faster                                                                                                  |
| richards                   | 31.3 ms                                                                                                                            | 30.7 ms: 1.02x faster                                                                                                  |
| async_tree_memoization     | 370 ms                                                                                                                             | 363 ms: 1.02x faster                                                                                                   |
| 2to3                       | 231 ms                                                                                                                             | 227 ms: 1.02x faster                                                                                                   |
| unpickle                   | 8.87 us                                                                                                                            | 8.75 us: 1.01x faster                                                                                                  |
| richards_super             | 35.5 ms                                                                                                                            | 35.1 ms: 1.01x faster                                                                                                  |
| async_tree_io_tg           | 818 ms                                                                                                                             | 809 ms: 1.01x faster                                                                                                   |
| xml_etree_generate         | 59.6 ms                                                                                                                            | 59.0 ms: 1.01x faster                                                                                                  |
| deepcopy                   | 246 us                                                                                                                             | 244 us: 1.01x faster                                                                                                   |
| coverage                   | 45.9 ms                                                                                                                            | 46.2 ms: 1.01x slower                                                                                                  |
| pathlib                    | 81.2 ms                                                                                                                            | 82.1 ms: 1.01x slower                                                                                                  |
| xml_etree_parse            | 94.2 ms                                                                                                                            | 95.5 ms: 1.01x slower                                                                                                  |
| telco                      | 4.84 ms                                                                                                                            | 4.91 ms: 1.01x slower                                                                                                  |
| gc_traversal               | 1.52 ms                                                                                                                            | 1.55 ms: 1.02x slower                                                                                                  |
| deepcopy_memo              | 25.2 us                                                                                                                            | 25.7 us: 1.02x slower                                                                                                  |
| pickle                     | 7.12 us                                                                                                                            | 7.27 us: 1.02x slower                                                                                                  |
| regex_dna                  | 123 ms                                                                                                                             | 125 ms: 1.02x slower                                                                                                   |
| pidigits                   | 151 ms                                                                                                                             | 155 ms: 1.03x slower                                                                                                   |
| coroutines                 | 14.8 ms                                                                                                                            | 15.3 ms: 1.03x slower                                                                                                  |
| async_tree_cpu_io_mixed_tg | 523 ms                                                                                                                             | 543 ms: 1.04x slower                                                                                                   |
| json_loads                 | 14.5 us                                                                                                                            | 15.1 us: 1.04x slower                                                                                                  |
| tomli_loads                | 1.50 sec                                                                                                                           | 1.55 sec: 1.04x slower                                                                                                 |
| async_tree_cpu_io_mixed    | 495 ms                                                                                                                             | 516 ms: 1.04x slower                                                                                                   |
| mdp                        | 1.45 sec                                                                                                                           | 1.51 sec: 1.04x slower                                                                                                 |
| json_dumps                 | 6.08 ms                                                                                                                            | 6.43 ms: 1.06x slower                                                                                                  |
| regex_effbot               | 1.74 ms                                                                                                                            | 1.90 ms: 1.09x slower                                                                                                  |
| asyncio_tcp_ssl            | 1.81 sec                                                                                                                           | 1.98 sec: 1.09x slower                                                                                                 |
| Geometric mean             | (ref)                                                                                                                              | 1.03x faster                                                                                                           |

Benchmark hidden because not significant (17): mypy2, asyncio_tcp, tornado_http, chameleon, python_startup_no_site, generators, async_tree_io, bench_mp_pool, async_generators, async_tree_memoization_tg, sqlite_synth, mako, bench_thread_pool, python_startup, create_gc_cycles, json, pycparser


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.01x
- 95% likely to have a speedup of 1.01x
- 99% likely to have a speedup of 1.01x
