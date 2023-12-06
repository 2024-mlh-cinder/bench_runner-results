
# Results vs. 3.12.0

- fork: python
- ref: 3faf8e586d36e73faba1
- machine: windows-amd64
- commit hash: 3faf8e5
- commit date: 2023-11-25
- overall geometric mean: 1.09x slower \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.07x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231125-pythonperf1-amd64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| 2to3           | 213 ms                                                      | 231 ms: 1.09x slower                                                        |
| chameleon      | 4.95 ms                                                     | 5.39 ms: 1.09x slower                                                       |
| docutils       | 1.61 sec                                                    | 1.72 sec: 1.07x slower                                                      |
| tornado_http   | 87.2 ms                                                     | 94.2 ms: 1.08x slower                                                       |
| Geometric mean | (ref)                                                       | 1.08x slower                                                                |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231125-pythonperf1-amd64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|----------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| async_tree_cpu_io_mixed    | 477 ms                                                      | 495 ms: 1.04x slower                                                        |
| async_tree_cpu_io_mixed_tg | 483 ms                                                      | 523 ms: 1.08x slower                                                        |
| async_tree_io              | 712 ms                                                      | 778 ms: 1.09x slower                                                        |
| async_tree_io_tg           | 742 ms                                                      | 818 ms: 1.10x slower                                                        |
| async_tree_memoization     | 333 ms                                                      | 370 ms: 1.11x slower                                                        |
| async_tree_none_tg         | 277 ms                                                      | 308 ms: 1.11x slower                                                        |
| async_tree_memoization_tg  | 345 ms                                                      | 386 ms: 1.12x slower                                                        |
| Geometric mean             | (ref)                                                       | 1.08x slower                                                                |

Benchmark hidden because not significant (1): async_tree_none

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231125-pythonperf1-amd64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| pidigits       | 150 ms                                                      | 151 ms: 1.01x slower                                                        |
| float          | 54.7 ms                                                     | 57.7 ms: 1.06x slower                                                       |
| nbody          | 68.8 ms                                                     | 83.2 ms: 1.21x slower                                                       |
| Geometric mean | (ref)                                                       | 1.09x slower                                                                |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231125-pythonperf1-amd64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_dna      | 119 ms                                                      | 123 ms: 1.03x slower                                                        |
| regex_compile  | 87.2 ms                                                     | 95.9 ms: 1.10x slower                                                       |
| regex_effbot   | 1.58 ms                                                     | 1.74 ms: 1.10x slower                                                       |
| regex_v8       | 13.5 ms                                                     | 19.4 ms: 1.44x slower                                                       |
| Geometric mean | (ref)                                                       | 1.16x slower                                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231125-pythonperf1-amd64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|----------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| pickle               | 7.38 us                                                     | 7.12 us: 1.04x faster                                                       |
| pickle_dict          | 18.9 us                                                     | 19.3 us: 1.02x slower                                                       |
| pickle_pure_python   | 195 us                                                      | 199 us: 1.02x slower                                                        |
| unpickle_list        | 2.69 us                                                     | 2.79 us: 1.04x slower                                                       |
| xml_etree_parse      | 90.5 ms                                                     | 94.2 ms: 1.04x slower                                                       |
| json_dumps           | 5.83 ms                                                     | 6.08 ms: 1.04x slower                                                       |
| unpickle             | 8.44 us                                                     | 8.87 us: 1.05x slower                                                       |
| json_loads           | 13.6 us                                                     | 14.5 us: 1.06x slower                                                       |
| xml_etree_generate   | 55.8 ms                                                     | 59.6 ms: 1.07x slower                                                       |
| xml_etree_iterparse  | 63.1 ms                                                     | 68.4 ms: 1.08x slower                                                       |
| tomli_loads          | 1.38 sec                                                    | 1.50 sec: 1.08x slower                                                      |
| xml_etree_process    | 37.6 ms                                                     | 41.3 ms: 1.10x slower                                                       |
| unpickle_pure_python | 134 us                                                      | 148 us: 1.10x slower                                                        |
| pickle_list          | 2.88 us                                                     | 3.21 us: 1.11x slower                                                       |
| Geometric mean       | (ref)                                                       | 1.06x slower                                                                |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231125-pythonperf1-amd64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| python_startup         | 18.8 ms                                                     | 20.5 ms: 1.09x slower                                                       |
| python_startup_no_site | 15.9 ms                                                     | 18.3 ms: 1.15x slower                                                       |
| Geometric mean         | (ref)                                                       | 1.12x slower                                                                |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231125-pythonperf1-amd64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|-----------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| mako      | 7.05 ms                                                     | 7.70 ms: 1.09x slower                                                       |

All benchmarks:
===============

| Benchmark                  | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231125-pythonperf1-amd64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|----------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| typing_runtime_protocols   | 96.7 us                                                     | 85.8 us: 1.13x faster                                                       |
| sqlite_synth               | 1.75 us                                                     | 1.59 us: 1.10x faster                                                       |
| comprehensions             | 14.0 us                                                     | 13.5 us: 1.04x faster                                                       |
| pickle                     | 7.38 us                                                     | 7.12 us: 1.04x faster                                                       |
| raytrace                   | 192 ms                                                      | 188 ms: 1.02x faster                                                        |
| bench_mp_pool              | 67.2 ms                                                     | 66.3 ms: 1.01x faster                                                       |
| pidigits                   | 150 ms                                                      | 151 ms: 1.01x slower                                                        |
| mdp                        | 1.42 sec                                                    | 1.45 sec: 1.02x slower                                                      |
| pickle_dict                | 18.9 us                                                     | 19.3 us: 1.02x slower                                                       |
| pathlib                    | 79.6 ms                                                     | 81.2 ms: 1.02x slower                                                       |
| gc_traversal               | 1.49 ms                                                     | 1.52 ms: 1.02x slower                                                       |
| pickle_pure_python         | 195 us                                                      | 199 us: 1.02x slower                                                        |
| regex_dna                  | 119 ms                                                      | 123 ms: 1.03x slower                                                        |
| unpickle_list              | 2.69 us                                                     | 2.79 us: 1.04x slower                                                       |
| async_tree_cpu_io_mixed    | 477 ms                                                      | 495 ms: 1.04x slower                                                        |
| sympy_sum                  | 90.1 ms                                                     | 93.5 ms: 1.04x slower                                                       |
| crypto_pyaes               | 46.4 ms                                                     | 48.2 ms: 1.04x slower                                                       |
| create_gc_cycles           | 726 us                                                      | 754 us: 1.04x slower                                                        |
| xml_etree_parse            | 90.5 ms                                                     | 94.2 ms: 1.04x slower                                                       |
| json_dumps                 | 5.83 ms                                                     | 6.08 ms: 1.04x slower                                                       |
| json                       | 2.94 ms                                                     | 3.07 ms: 1.04x slower                                                       |
| sympy_str                  | 171 ms                                                      | 179 ms: 1.04x slower                                                        |
| coroutines                 | 14.1 ms                                                     | 14.8 ms: 1.05x slower                                                       |
| unpickle                   | 8.44 us                                                     | 8.87 us: 1.05x slower                                                       |
| deepcopy_reduce            | 2.08 us                                                     | 2.20 us: 1.06x slower                                                       |
| float                      | 54.7 ms                                                     | 57.7 ms: 1.06x slower                                                       |
| generators                 | 22.6 ms                                                     | 23.9 ms: 1.06x slower                                                       |
| deepcopy                   | 233 us                                                      | 246 us: 1.06x slower                                                        |
| asyncio_tcp                | 471 ms                                                      | 498 ms: 1.06x slower                                                        |
| scimark_sor                | 79.8 ms                                                     | 84.5 ms: 1.06x slower                                                       |
| json_loads                 | 13.6 us                                                     | 14.5 us: 1.06x slower                                                       |
| logging_silent             | 60.5 ns                                                     | 64.5 ns: 1.07x slower                                                       |
| docutils                   | 1.61 sec                                                    | 1.72 sec: 1.07x slower                                                      |
| xml_etree_generate         | 55.8 ms                                                     | 59.6 ms: 1.07x slower                                                       |
| bench_thread_pool          | 830 us                                                      | 893 us: 1.08x slower                                                        |
| logging_simple             | 6.21 us                                                     | 6.69 us: 1.08x slower                                                       |
| deepcopy_memo              | 23.4 us                                                     | 25.2 us: 1.08x slower                                                       |
| sympy_integrate            | 13.0 ms                                                     | 14.0 ms: 1.08x slower                                                       |
| sqlglot_parse              | 802 us                                                      | 867 us: 1.08x slower                                                        |
| logging_format             | 6.72 us                                                     | 7.26 us: 1.08x slower                                                       |
| tornado_http               | 87.2 ms                                                     | 94.2 ms: 1.08x slower                                                       |
| async_tree_cpu_io_mixed_tg | 483 ms                                                      | 523 ms: 1.08x slower                                                        |
| xml_etree_iterparse        | 63.1 ms                                                     | 68.4 ms: 1.08x slower                                                       |
| sqlglot_transpile          | 1.02 ms                                                     | 1.10 ms: 1.08x slower                                                       |
| tomli_loads                | 1.38 sec                                                    | 1.50 sec: 1.08x slower                                                      |
| 2to3                       | 213 ms                                                      | 231 ms: 1.09x slower                                                        |
| python_startup             | 18.8 ms                                                     | 20.5 ms: 1.09x slower                                                       |
| chameleon                  | 4.95 ms                                                     | 5.39 ms: 1.09x slower                                                       |
| meteor_contest             | 72.1 ms                                                     | 78.7 ms: 1.09x slower                                                       |
| dask                       | 255 ms                                                      | 278 ms: 1.09x slower                                                        |
| mako                       | 7.05 ms                                                     | 7.70 ms: 1.09x slower                                                       |
| async_generators           | 230 ms                                                      | 251 ms: 1.09x slower                                                        |
| dulwich_log                | 42.7 ms                                                     | 46.7 ms: 1.09x slower                                                       |
| async_tree_io              | 712 ms                                                      | 778 ms: 1.09x slower                                                        |
| sympy_expand               | 278 ms                                                      | 305 ms: 1.10x slower                                                        |
| xml_etree_process          | 37.6 ms                                                     | 41.3 ms: 1.10x slower                                                       |
| regex_compile              | 87.2 ms                                                     | 95.9 ms: 1.10x slower                                                       |
| pprint_safe_repr           | 508 ms                                                      | 559 ms: 1.10x slower                                                        |
| scimark_lu                 | 57.5 ms                                                     | 63.3 ms: 1.10x slower                                                       |
| unpickle_pure_python       | 134 us                                                      | 148 us: 1.10x slower                                                        |
| async_tree_io_tg           | 742 ms                                                      | 818 ms: 1.10x slower                                                        |
| regex_effbot               | 1.58 ms                                                     | 1.74 ms: 1.10x slower                                                       |
| sqlglot_normalize          | 183 ms                                                      | 202 ms: 1.10x slower                                                        |
| chaos                      | 42.1 ms                                                     | 46.5 ms: 1.10x slower                                                       |
| pycparser                  | 673 ms                                                      | 744 ms: 1.11x slower                                                        |
| nqueens                    | 61.7 ms                                                     | 68.5 ms: 1.11x slower                                                       |
| async_tree_memoization     | 333 ms                                                      | 370 ms: 1.11x slower                                                        |
| pickle_list                | 2.88 us                                                     | 3.21 us: 1.11x slower                                                       |
| async_tree_none_tg         | 277 ms                                                      | 308 ms: 1.11x slower                                                        |
| pprint_pformat             | 1.04 sec                                                    | 1.16 sec: 1.12x slower                                                      |
| async_tree_memoization_tg  | 345 ms                                                      | 386 ms: 1.12x slower                                                        |
| go                         | 89.0 ms                                                     | 99.8 ms: 1.12x slower                                                       |
| sqlglot_optimize           | 34.0 ms                                                     | 38.2 ms: 1.12x slower                                                       |
| richards                   | 27.6 ms                                                     | 31.3 ms: 1.13x slower                                                       |
| richards_super             | 31.2 ms                                                     | 35.5 ms: 1.14x slower                                                       |
| pyflate                    | 294 ms                                                      | 334 ms: 1.14x slower                                                        |
| python_startup_no_site     | 15.9 ms                                                     | 18.3 ms: 1.15x slower                                                       |
| coverage                   | 39.8 ms                                                     | 45.9 ms: 1.15x slower                                                       |
| fannkuch                   | 244 ms                                                      | 283 ms: 1.16x slower                                                        |
| scimark_monte_carlo        | 43.0 ms                                                     | 50.3 ms: 1.17x slower                                                       |
| scimark_fft                | 181 ms                                                      | 212 ms: 1.17x slower                                                        |
| telco                      | 4.08 ms                                                     | 4.84 ms: 1.19x slower                                                       |
| unpack_sequence            | 36.9 ns                                                     | 44.4 ns: 1.20x slower                                                       |
| nbody                      | 68.8 ms                                                     | 83.2 ms: 1.21x slower                                                       |
| scimark_sparse_mat_mult    | 2.51 ms                                                     | 3.06 ms: 1.22x slower                                                       |
| hexiom                     | 4.00 ms                                                     | 5.10 ms: 1.27x slower                                                       |
| deltablue                  | 2.12 ms                                                     | 2.80 ms: 1.32x slower                                                       |
| spectral_norm              | 63.9 ms                                                     | 86.2 ms: 1.35x slower                                                       |
| regex_v8                   | 13.5 ms                                                     | 19.4 ms: 1.44x slower                                                       |
| mypy2                      | 209 ms                                                      | 313 ms: 1.50x slower                                                        |
| Geometric mean             | (ref)                                                       | 1.09x slower                                                                |

Benchmark hidden because not significant (2): asyncio_tcp_ssl, async_tree_none
Ignored benchmarks (4) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, django_template, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.08x
- 95% likely to have a slowdown of 1.08x
- 99% likely to have a slowdown of 1.07x
