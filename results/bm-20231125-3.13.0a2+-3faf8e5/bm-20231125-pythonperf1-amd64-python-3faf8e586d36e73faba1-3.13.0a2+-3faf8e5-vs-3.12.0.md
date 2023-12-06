
# Results vs. 3.12.0

- fork: python
- ref: 3faf8e586d36e73faba1
- machine: windows-amd64
- commit hash: 3faf8e5
- commit date: 2023-11-25
- overall geometric mean: 1.06x slower \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.04x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231125-pythonperf1-amd64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| 2to3           | 213 ms                                                      | 227 ms: 1.07x slower                                                        |
| chameleon      | 4.95 ms                                                     | 5.36 ms: 1.08x slower                                                       |
| docutils       | 1.61 sec                                                    | 1.64 sec: 1.02x slower                                                      |
| tornado_http   | 87.2 ms                                                     | 93.5 ms: 1.07x slower                                                       |
| Geometric mean | (ref)                                                       | 1.06x slower                                                                |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231125-pythonperf1-amd64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|----------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| async_tree_none            | 286 ms                                                      | 281 ms: 1.02x faster                                                        |
| async_tree_cpu_io_mixed    | 477 ms                                                      | 516 ms: 1.08x slower                                                        |
| async_tree_none_tg         | 277 ms                                                      | 301 ms: 1.09x slower                                                        |
| async_tree_io_tg           | 742 ms                                                      | 809 ms: 1.09x slower                                                        |
| async_tree_memoization     | 333 ms                                                      | 363 ms: 1.09x slower                                                        |
| async_tree_io              | 712 ms                                                      | 779 ms: 1.09x slower                                                        |
| async_tree_memoization_tg  | 345 ms                                                      | 387 ms: 1.12x slower                                                        |
| async_tree_cpu_io_mixed_tg | 483 ms                                                      | 543 ms: 1.12x slower                                                        |
| Geometric mean             | (ref)                                                       | 1.08x slower                                                                |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231125-pythonperf1-amd64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| pidigits       | 150 ms                                                      | 155 ms: 1.03x slower                                                        |
| nbody          | 68.8 ms                                                     | 75.8 ms: 1.10x slower                                                       |
| Geometric mean | (ref)                                                       | 1.05x slower                                                                |

Benchmark hidden because not significant (1): float

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231125-pythonperf1-amd64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_compile  | 87.2 ms                                                     | 87.7 ms: 1.01x slower                                                       |
| regex_dna      | 119 ms                                                      | 125 ms: 1.05x slower                                                        |
| regex_v8       | 13.5 ms                                                     | 15.5 ms: 1.15x slower                                                       |
| regex_effbot   | 1.58 ms                                                     | 1.90 ms: 1.20x slower                                                       |
| Geometric mean | (ref)                                                       | 1.10x slower                                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231125-pythonperf1-amd64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|----------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| pickle               | 7.38 us                                                     | 7.27 us: 1.01x faster                                                       |
| unpickle             | 8.44 us                                                     | 8.75 us: 1.04x slower                                                       |
| xml_etree_iterparse  | 63.1 ms                                                     | 66.2 ms: 1.05x slower                                                       |
| xml_etree_parse      | 90.5 ms                                                     | 95.5 ms: 1.05x slower                                                       |
| xml_etree_generate   | 55.8 ms                                                     | 59.0 ms: 1.06x slower                                                       |
| unpickle_pure_python | 134 us                                                      | 143 us: 1.06x slower                                                        |
| xml_etree_process    | 37.6 ms                                                     | 40.3 ms: 1.07x slower                                                       |
| json_dumps           | 5.83 ms                                                     | 6.43 ms: 1.10x slower                                                       |
| json_loads           | 13.6 us                                                     | 15.1 us: 1.11x slower                                                       |
| tomli_loads          | 1.38 sec                                                    | 1.55 sec: 1.13x slower                                                      |
| Geometric mean       | (ref)                                                       | 1.04x slower                                                                |

Benchmark hidden because not significant (4): unpickle_list, pickle_pure_python, pickle_dict, pickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231125-pythonperf1-amd64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| python_startup         | 18.8 ms                                                     | 20.6 ms: 1.10x slower                                                       |
| python_startup_no_site | 15.9 ms                                                     | 18.3 ms: 1.15x slower                                                       |
| Geometric mean         | (ref)                                                       | 1.12x slower                                                                |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231125-pythonperf1-amd64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|-----------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| mako      | 7.05 ms                                                     | 7.74 ms: 1.10x slower                                                       |

All benchmarks:
===============

| Benchmark                  | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231125-pythonperf1-amd64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|----------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| comprehensions             | 14.0 us                                                     | 11.3 us: 1.24x faster                                                       |
| typing_runtime_protocols   | 96.7 us                                                     | 81.4 us: 1.19x faster                                                       |
| raytrace                   | 192 ms                                                      | 175 ms: 1.10x faster                                                        |
| sqlite_synth               | 1.75 us                                                     | 1.59 us: 1.09x faster                                                       |
| sympy_sum                  | 90.1 ms                                                     | 86.7 ms: 1.04x faster                                                       |
| async_tree_none            | 286 ms                                                      | 281 ms: 1.02x faster                                                        |
| pickle                     | 7.38 us                                                     | 7.27 us: 1.01x faster                                                       |
| bench_mp_pool              | 67.2 ms                                                     | 66.4 ms: 1.01x faster                                                       |
| scimark_monte_carlo        | 43.0 ms                                                     | 42.6 ms: 1.01x faster                                                       |
| sympy_str                  | 171 ms                                                      | 170 ms: 1.01x faster                                                        |
| chaos                      | 42.1 ms                                                     | 41.7 ms: 1.01x faster                                                       |
| crypto_pyaes               | 46.4 ms                                                     | 46.2 ms: 1.00x faster                                                       |
| regex_compile              | 87.2 ms                                                     | 87.7 ms: 1.01x slower                                                       |
| sympy_integrate            | 13.0 ms                                                     | 13.2 ms: 1.02x slower                                                       |
| docutils                   | 1.61 sec                                                    | 1.64 sec: 1.02x slower                                                      |
| deepcopy_reduce            | 2.08 us                                                     | 2.14 us: 1.02x slower                                                       |
| logging_simple             | 6.21 us                                                     | 6.37 us: 1.03x slower                                                       |
| logging_format             | 6.72 us                                                     | 6.92 us: 1.03x slower                                                       |
| nqueens                    | 61.7 ms                                                     | 63.6 ms: 1.03x slower                                                       |
| go                         | 89.0 ms                                                     | 91.7 ms: 1.03x slower                                                       |
| pathlib                    | 79.6 ms                                                     | 82.1 ms: 1.03x slower                                                       |
| sqlglot_normalize          | 183 ms                                                      | 190 ms: 1.03x slower                                                        |
| pidigits                   | 150 ms                                                      | 155 ms: 1.03x slower                                                        |
| sqlglot_parse              | 802 us                                                      | 831 us: 1.04x slower                                                        |
| unpickle                   | 8.44 us                                                     | 8.75 us: 1.04x slower                                                       |
| gc_traversal               | 1.49 ms                                                     | 1.55 ms: 1.04x slower                                                       |
| scimark_sor                | 79.8 ms                                                     | 82.9 ms: 1.04x slower                                                       |
| sympy_expand               | 278 ms                                                      | 289 ms: 1.04x slower                                                        |
| logging_silent             | 60.5 ns                                                     | 63.3 ns: 1.05x slower                                                       |
| asyncio_tcp                | 471 ms                                                      | 493 ms: 1.05x slower                                                        |
| xml_etree_iterparse        | 63.1 ms                                                     | 66.2 ms: 1.05x slower                                                       |
| deepcopy                   | 233 us                                                      | 244 us: 1.05x slower                                                        |
| create_gc_cycles           | 726 us                                                      | 762 us: 1.05x slower                                                        |
| sqlglot_optimize           | 34.0 ms                                                     | 35.7 ms: 1.05x slower                                                       |
| pprint_pformat             | 1.04 sec                                                    | 1.09 sec: 1.05x slower                                                      |
| fannkuch                   | 244 ms                                                      | 256 ms: 1.05x slower                                                        |
| regex_dna                  | 119 ms                                                      | 125 ms: 1.05x slower                                                        |
| pprint_safe_repr           | 508 ms                                                      | 534 ms: 1.05x slower                                                        |
| scimark_lu                 | 57.5 ms                                                     | 60.5 ms: 1.05x slower                                                       |
| sqlglot_transpile          | 1.02 ms                                                     | 1.07 ms: 1.05x slower                                                       |
| xml_etree_parse            | 90.5 ms                                                     | 95.5 ms: 1.05x slower                                                       |
| generators                 | 22.6 ms                                                     | 23.8 ms: 1.06x slower                                                       |
| xml_etree_generate         | 55.8 ms                                                     | 59.0 ms: 1.06x slower                                                       |
| pyflate                    | 294 ms                                                      | 311 ms: 1.06x slower                                                        |
| dask                       | 255 ms                                                      | 270 ms: 1.06x slower                                                        |
| json                       | 2.94 ms                                                     | 3.13 ms: 1.06x slower                                                       |
| unpickle_pure_python       | 134 us                                                      | 143 us: 1.06x slower                                                        |
| dulwich_log                | 42.7 ms                                                     | 45.4 ms: 1.06x slower                                                       |
| mdp                        | 1.42 sec                                                    | 1.51 sec: 1.06x slower                                                      |
| 2to3                       | 213 ms                                                      | 227 ms: 1.07x slower                                                        |
| meteor_contest             | 72.1 ms                                                     | 77.0 ms: 1.07x slower                                                       |
| xml_etree_process          | 37.6 ms                                                     | 40.3 ms: 1.07x slower                                                       |
| tornado_http               | 87.2 ms                                                     | 93.5 ms: 1.07x slower                                                       |
| unpack_sequence            | 36.9 ns                                                     | 39.6 ns: 1.07x slower                                                       |
| async_tree_cpu_io_mixed    | 477 ms                                                      | 516 ms: 1.08x slower                                                        |
| bench_thread_pool          | 830 us                                                      | 898 us: 1.08x slower                                                        |
| chameleon                  | 4.95 ms                                                     | 5.36 ms: 1.08x slower                                                       |
| coroutines                 | 14.1 ms                                                     | 15.3 ms: 1.08x slower                                                       |
| async_tree_none_tg         | 277 ms                                                      | 301 ms: 1.09x slower                                                        |
| hexiom                     | 4.00 ms                                                     | 4.36 ms: 1.09x slower                                                       |
| deltablue                  | 2.12 ms                                                     | 2.31 ms: 1.09x slower                                                       |
| async_tree_io_tg           | 742 ms                                                      | 809 ms: 1.09x slower                                                        |
| async_tree_memoization     | 333 ms                                                      | 363 ms: 1.09x slower                                                        |
| async_generators           | 230 ms                                                      | 252 ms: 1.09x slower                                                        |
| async_tree_io              | 712 ms                                                      | 779 ms: 1.09x slower                                                        |
| python_startup             | 18.8 ms                                                     | 20.6 ms: 1.10x slower                                                       |
| mako                       | 7.05 ms                                                     | 7.74 ms: 1.10x slower                                                       |
| deepcopy_memo              | 23.4 us                                                     | 25.7 us: 1.10x slower                                                       |
| nbody                      | 68.8 ms                                                     | 75.8 ms: 1.10x slower                                                       |
| json_dumps                 | 5.83 ms                                                     | 6.43 ms: 1.10x slower                                                       |
| json_loads                 | 13.6 us                                                     | 15.1 us: 1.11x slower                                                       |
| richards                   | 27.6 ms                                                     | 30.7 ms: 1.11x slower                                                       |
| scimark_fft                | 181 ms                                                      | 202 ms: 1.11x slower                                                        |
| spectral_norm              | 63.9 ms                                                     | 71.2 ms: 1.12x slower                                                       |
| async_tree_memoization_tg  | 345 ms                                                      | 387 ms: 1.12x slower                                                        |
| async_tree_cpu_io_mixed_tg | 483 ms                                                      | 543 ms: 1.12x slower                                                        |
| richards_super             | 31.2 ms                                                     | 35.1 ms: 1.12x slower                                                       |
| tomli_loads                | 1.38 sec                                                    | 1.55 sec: 1.13x slower                                                      |
| scimark_sparse_mat_mult    | 2.51 ms                                                     | 2.87 ms: 1.14x slower                                                       |
| python_startup_no_site     | 15.9 ms                                                     | 18.3 ms: 1.15x slower                                                       |
| regex_v8                   | 13.5 ms                                                     | 15.5 ms: 1.15x slower                                                       |
| pycparser                  | 673 ms                                                      | 777 ms: 1.15x slower                                                        |
| coverage                   | 39.8 ms                                                     | 46.2 ms: 1.16x slower                                                       |
| regex_effbot               | 1.58 ms                                                     | 1.90 ms: 1.20x slower                                                       |
| telco                      | 4.08 ms                                                     | 4.91 ms: 1.20x slower                                                       |
| mypy2                      | 209 ms                                                      | 305 ms: 1.46x slower                                                        |
| Geometric mean             | (ref)                                                       | 1.06x slower                                                                |

Benchmark hidden because not significant (6): unpickle_list, pickle_pure_python, pickle_dict, pickle_list, float, asyncio_tcp_ssl
Ignored benchmarks (4) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, django_template, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.05x
- 95% likely to have a slowdown of 1.05x
- 99% likely to have a slowdown of 1.04x
