
# Results vs. base

- fork: python
- ref: 3faf8e586d36e73faba1
- machine: windows-amd64
- commit hash: 3faf8e5
- commit date: 2023-11-25
- overall geometric mean: 1.03x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.01x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | results/bm-20231125-3.13.0a2+-3faf8e5/bm-20231125-pythonperf1-amd64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5.json | results/bm-20231125-3.13.0a2+-3faf8e5-PYTHON_UOPS/bm-20231125-pythonperf1-amd64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5.json |
|----------------|:----------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------------------:|
| 2to3           | 227 ms                                                                                                                 | 231 ms: 1.02x slower                                                                                                               |
| docutils       | 1.64 sec                                                                                                               | 1.72 sec: 1.04x slower                                                                                                             |
| Geometric mean | (ref)                                                                                                                  | 1.02x slower                                                                                                                       |

Benchmark hidden because not significant (2): chameleon, tornado_http

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | results/bm-20231125-3.13.0a2+-3faf8e5/bm-20231125-pythonperf1-amd64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5.json | results/bm-20231125-3.13.0a2+-3faf8e5-PYTHON_UOPS/bm-20231125-pythonperf1-amd64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5.json |
|----------------------------|:----------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------------------:|
| async_tree_cpu_io_mixed    | 516 ms                                                                                                                 | 495 ms: 1.04x faster                                                                                                               |
| async_tree_cpu_io_mixed_tg | 543 ms                                                                                                                 | 523 ms: 1.04x faster                                                                                                               |
| async_tree_io_tg           | 809 ms                                                                                                                 | 818 ms: 1.01x slower                                                                                                               |
| async_tree_memoization     | 363 ms                                                                                                                 | 370 ms: 1.02x slower                                                                                                               |
| async_tree_none            | 281 ms                                                                                                                 | 287 ms: 1.02x slower                                                                                                               |
| async_tree_none_tg         | 301 ms                                                                                                                 | 308 ms: 1.02x slower                                                                                                               |
| Geometric mean             | (ref)                                                                                                                  | 1.00x faster                                                                                                                       |

Benchmark hidden because not significant (2): async_tree_memoization_tg, async_tree_io

Benchmarks with tag 'math':
===========================

| Benchmark      | results/bm-20231125-3.13.0a2+-3faf8e5/bm-20231125-pythonperf1-amd64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5.json | results/bm-20231125-3.13.0a2+-3faf8e5-PYTHON_UOPS/bm-20231125-pythonperf1-amd64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5.json |
|----------------|:----------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------------------:|
| pidigits       | 155 ms                                                                                                                 | 151 ms: 1.03x faster                                                                                                               |
| float          | 55.0 ms                                                                                                                | 57.7 ms: 1.05x slower                                                                                                              |
| nbody          | 75.8 ms                                                                                                                | 83.2 ms: 1.10x slower                                                                                                              |
| Geometric mean | (ref)                                                                                                                  | 1.04x slower                                                                                                                       |

Benchmarks with tag 'regex':
============================

| Benchmark      | results/bm-20231125-3.13.0a2+-3faf8e5/bm-20231125-pythonperf1-amd64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5.json | results/bm-20231125-3.13.0a2+-3faf8e5-PYTHON_UOPS/bm-20231125-pythonperf1-amd64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5.json |
|----------------|:----------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------------------:|
| regex_effbot   | 1.90 ms                                                                                                                | 1.74 ms: 1.09x faster                                                                                                              |
| regex_dna      | 125 ms                                                                                                                 | 123 ms: 1.02x faster                                                                                                               |
| regex_compile  | 87.7 ms                                                                                                                | 95.9 ms: 1.09x slower                                                                                                              |
| regex_v8       | 15.5 ms                                                                                                                | 19.4 ms: 1.25x slower                                                                                                              |
| Geometric mean | (ref)                                                                                                                  | 1.05x slower                                                                                                                       |

Benchmarks with tag 'serialize':
================================

| Benchmark            | results/bm-20231125-3.13.0a2+-3faf8e5/bm-20231125-pythonperf1-amd64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5.json | results/bm-20231125-3.13.0a2+-3faf8e5-PYTHON_UOPS/bm-20231125-pythonperf1-amd64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5.json |
|----------------------|:----------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------------------:|
| json_dumps           | 6.43 ms                                                                                                                | 6.08 ms: 1.06x faster                                                                                                              |
| tomli_loads          | 1.55 sec                                                                                                               | 1.50 sec: 1.04x faster                                                                                                             |
| json_loads           | 15.1 us                                                                                                                | 14.5 us: 1.04x faster                                                                                                              |
| pickle               | 7.27 us                                                                                                                | 7.12 us: 1.02x faster                                                                                                              |
| xml_etree_parse      | 95.5 ms                                                                                                                | 94.2 ms: 1.01x faster                                                                                                              |
| xml_etree_generate   | 59.0 ms                                                                                                                | 59.6 ms: 1.01x slower                                                                                                              |
| unpickle             | 8.75 us                                                                                                                | 8.87 us: 1.01x slower                                                                                                              |
| pickle_dict          | 18.9 us                                                                                                                | 19.3 us: 1.02x slower                                                                                                              |
| pickle_pure_python   | 194 us                                                                                                                 | 199 us: 1.02x slower                                                                                                               |
| xml_etree_process    | 40.3 ms                                                                                                                | 41.3 ms: 1.03x slower                                                                                                              |
| xml_etree_iterparse  | 66.2 ms                                                                                                                | 68.4 ms: 1.03x slower                                                                                                              |
| unpickle_pure_python | 143 us                                                                                                                 | 148 us: 1.04x slower                                                                                                               |
| unpickle_list        | 2.68 us                                                                                                                | 2.79 us: 1.04x slower                                                                                                              |
| pickle_list          | 2.88 us                                                                                                                | 3.21 us: 1.12x slower                                                                                                              |
| Geometric mean       | (ref)                                                                                                                  | 1.01x slower                                                                                                                       |

Benchmarks with tag 'startup':
==============================

Benchmark hidden because not significant (2): python_startup, python_startup_no_site

Benchmarks with tag 'template':
===============================

Benchmark hidden because not significant (1): mako

All benchmarks:
===============

| Benchmark                  | results/bm-20231125-3.13.0a2+-3faf8e5/bm-20231125-pythonperf1-amd64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5.json | results/bm-20231125-3.13.0a2+-3faf8e5-PYTHON_UOPS/bm-20231125-pythonperf1-amd64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5.json |
|----------------------------|:----------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------------------:|
| asyncio_tcp_ssl            | 1.98 sec                                                                                                               | 1.81 sec: 1.09x faster                                                                                                             |
| regex_effbot               | 1.90 ms                                                                                                                | 1.74 ms: 1.09x faster                                                                                                              |
| json_dumps                 | 6.43 ms                                                                                                                | 6.08 ms: 1.06x faster                                                                                                              |
| mdp                        | 1.51 sec                                                                                                               | 1.45 sec: 1.04x faster                                                                                                             |
| async_tree_cpu_io_mixed    | 516 ms                                                                                                                 | 495 ms: 1.04x faster                                                                                                               |
| tomli_loads                | 1.55 sec                                                                                                               | 1.50 sec: 1.04x faster                                                                                                             |
| json_loads                 | 15.1 us                                                                                                                | 14.5 us: 1.04x faster                                                                                                              |
| async_tree_cpu_io_mixed_tg | 543 ms                                                                                                                 | 523 ms: 1.04x faster                                                                                                               |
| coroutines                 | 15.3 ms                                                                                                                | 14.8 ms: 1.03x faster                                                                                                              |
| pidigits                   | 155 ms                                                                                                                 | 151 ms: 1.03x faster                                                                                                               |
| regex_dna                  | 125 ms                                                                                                                 | 123 ms: 1.02x faster                                                                                                               |
| pickle                     | 7.27 us                                                                                                                | 7.12 us: 1.02x faster                                                                                                              |
| deepcopy_memo              | 25.7 us                                                                                                                | 25.2 us: 1.02x faster                                                                                                              |
| gc_traversal               | 1.55 ms                                                                                                                | 1.52 ms: 1.02x faster                                                                                                              |
| telco                      | 4.91 ms                                                                                                                | 4.84 ms: 1.01x faster                                                                                                              |
| xml_etree_parse            | 95.5 ms                                                                                                                | 94.2 ms: 1.01x faster                                                                                                              |
| pathlib                    | 82.1 ms                                                                                                                | 81.2 ms: 1.01x faster                                                                                                              |
| coverage                   | 46.2 ms                                                                                                                | 45.9 ms: 1.01x faster                                                                                                              |
| deepcopy                   | 244 us                                                                                                                 | 246 us: 1.01x slower                                                                                                               |
| xml_etree_generate         | 59.0 ms                                                                                                                | 59.6 ms: 1.01x slower                                                                                                              |
| async_tree_io_tg           | 809 ms                                                                                                                 | 818 ms: 1.01x slower                                                                                                               |
| richards_super             | 35.1 ms                                                                                                                | 35.5 ms: 1.01x slower                                                                                                              |
| unpickle                   | 8.75 us                                                                                                                | 8.87 us: 1.01x slower                                                                                                              |
| 2to3                       | 227 ms                                                                                                                 | 231 ms: 1.02x slower                                                                                                               |
| async_tree_memoization     | 363 ms                                                                                                                 | 370 ms: 1.02x slower                                                                                                               |
| richards                   | 30.7 ms                                                                                                                | 31.3 ms: 1.02x slower                                                                                                              |
| logging_silent             | 63.3 ns                                                                                                                | 64.5 ns: 1.02x slower                                                                                                              |
| scimark_sor                | 82.9 ms                                                                                                                | 84.5 ms: 1.02x slower                                                                                                              |
| meteor_contest             | 77.0 ms                                                                                                                | 78.7 ms: 1.02x slower                                                                                                              |
| pickle_dict                | 18.9 us                                                                                                                | 19.3 us: 1.02x slower                                                                                                              |
| async_tree_none            | 281 ms                                                                                                                 | 287 ms: 1.02x slower                                                                                                               |
| async_tree_none_tg         | 301 ms                                                                                                                 | 308 ms: 1.02x slower                                                                                                               |
| pickle_pure_python         | 194 us                                                                                                                 | 199 us: 1.02x slower                                                                                                               |
| xml_etree_process          | 40.3 ms                                                                                                                | 41.3 ms: 1.03x slower                                                                                                              |
| dulwich_log                | 45.4 ms                                                                                                                | 46.7 ms: 1.03x slower                                                                                                              |
| dask                       | 270 ms                                                                                                                 | 278 ms: 1.03x slower                                                                                                               |
| sqlglot_transpile          | 1.07 ms                                                                                                                | 1.10 ms: 1.03x slower                                                                                                              |
| deepcopy_reduce            | 2.14 us                                                                                                                | 2.20 us: 1.03x slower                                                                                                              |
| xml_etree_iterparse        | 66.2 ms                                                                                                                | 68.4 ms: 1.03x slower                                                                                                              |
| unpickle_pure_python       | 143 us                                                                                                                 | 148 us: 1.04x slower                                                                                                               |
| unpickle_list              | 2.68 us                                                                                                                | 2.79 us: 1.04x slower                                                                                                              |
| sqlglot_parse              | 831 us                                                                                                                 | 867 us: 1.04x slower                                                                                                               |
| crypto_pyaes               | 46.2 ms                                                                                                                | 48.2 ms: 1.04x slower                                                                                                              |
| docutils                   | 1.64 sec                                                                                                               | 1.72 sec: 1.04x slower                                                                                                             |
| pprint_safe_repr           | 534 ms                                                                                                                 | 559 ms: 1.05x slower                                                                                                               |
| scimark_lu                 | 60.5 ms                                                                                                                | 63.3 ms: 1.05x slower                                                                                                              |
| logging_format             | 6.92 us                                                                                                                | 7.26 us: 1.05x slower                                                                                                              |
| float                      | 55.0 ms                                                                                                                | 57.7 ms: 1.05x slower                                                                                                              |
| logging_simple             | 6.37 us                                                                                                                | 6.69 us: 1.05x slower                                                                                                              |
| scimark_fft                | 202 ms                                                                                                                 | 212 ms: 1.05x slower                                                                                                               |
| sympy_str                  | 170 ms                                                                                                                 | 179 ms: 1.05x slower                                                                                                               |
| typing_runtime_protocols   | 81.4 us                                                                                                                | 85.8 us: 1.05x slower                                                                                                              |
| sympy_expand               | 289 ms                                                                                                                 | 305 ms: 1.06x slower                                                                                                               |
| sympy_integrate            | 13.2 ms                                                                                                                | 14.0 ms: 1.06x slower                                                                                                              |
| pprint_pformat             | 1.09 sec                                                                                                               | 1.16 sec: 1.07x slower                                                                                                             |
| sqlglot_normalize          | 190 ms                                                                                                                 | 202 ms: 1.07x slower                                                                                                               |
| scimark_sparse_mat_mult    | 2.87 ms                                                                                                                | 3.06 ms: 1.07x slower                                                                                                              |
| sqlglot_optimize           | 35.7 ms                                                                                                                | 38.2 ms: 1.07x slower                                                                                                              |
| pyflate                    | 311 ms                                                                                                                 | 334 ms: 1.07x slower                                                                                                               |
| raytrace                   | 175 ms                                                                                                                 | 188 ms: 1.07x slower                                                                                                               |
| nqueens                    | 63.6 ms                                                                                                                | 68.5 ms: 1.08x slower                                                                                                              |
| sympy_sum                  | 86.7 ms                                                                                                                | 93.5 ms: 1.08x slower                                                                                                              |
| go                         | 91.7 ms                                                                                                                | 99.8 ms: 1.09x slower                                                                                                              |
| regex_compile              | 87.7 ms                                                                                                                | 95.9 ms: 1.09x slower                                                                                                              |
| nbody                      | 75.8 ms                                                                                                                | 83.2 ms: 1.10x slower                                                                                                              |
| fannkuch                   | 256 ms                                                                                                                 | 283 ms: 1.10x slower                                                                                                               |
| chaos                      | 41.7 ms                                                                                                                | 46.5 ms: 1.11x slower                                                                                                              |
| pickle_list                | 2.88 us                                                                                                                | 3.21 us: 1.12x slower                                                                                                              |
| unpack_sequence            | 39.6 ns                                                                                                                | 44.4 ns: 1.12x slower                                                                                                              |
| hexiom                     | 4.36 ms                                                                                                                | 5.10 ms: 1.17x slower                                                                                                              |
| scimark_monte_carlo        | 42.6 ms                                                                                                                | 50.3 ms: 1.18x slower                                                                                                              |
| comprehensions             | 11.3 us                                                                                                                | 13.5 us: 1.19x slower                                                                                                              |
| deltablue                  | 2.31 ms                                                                                                                | 2.80 ms: 1.21x slower                                                                                                              |
| spectral_norm              | 71.2 ms                                                                                                                | 86.2 ms: 1.21x slower                                                                                                              |
| regex_v8                   | 15.5 ms                                                                                                                | 19.4 ms: 1.25x slower                                                                                                              |
| Geometric mean             | (ref)                                                                                                                  | 1.03x slower                                                                                                                       |

Benchmark hidden because not significant (17): pycparser, json, create_gc_cycles, python_startup, bench_thread_pool, mako, sqlite_synth, async_tree_memoization_tg, async_generators, bench_mp_pool, async_tree_io, generators, python_startup_no_site, chameleon, tornado_http, asyncio_tcp, mypy2


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.01x
- 95% likely to have a slowdown of 1.01x
- 99% likely to have a slowdown of 1.01x
