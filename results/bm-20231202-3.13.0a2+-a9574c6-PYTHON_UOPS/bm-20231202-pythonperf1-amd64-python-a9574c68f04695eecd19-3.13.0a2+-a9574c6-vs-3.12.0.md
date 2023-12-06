
# Results vs. 3.12.0

- fork: python
- ref: a9574c68f04695eecd19
- machine: windows-amd64
- commit hash: a9574c6
- commit date: 2023-12-02
- overall geometric mean: 1.06x slower \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.03x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231202-pythonperf1-amd64-python-a9574c68f04695eecd19-3.13.0a2+-a9574c6 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| 2to3           | 213 ms                                                      | 227 ms: 1.07x slower                                                        |
| chameleon      | 4.95 ms                                                     | 5.24 ms: 1.06x slower                                                       |
| docutils       | 1.61 sec                                                    | 1.65 sec: 1.02x slower                                                      |
| tornado_http   | 87.2 ms                                                     | 90.6 ms: 1.04x slower                                                       |
| Geometric mean | (ref)                                                       | 1.05x slower                                                                |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231202-pythonperf1-amd64-python-a9574c68f04695eecd19-3.13.0a2+-a9574c6 |
|----------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| async_tree_none            | 286 ms                                                      | 276 ms: 1.03x faster                                                        |
| async_tree_cpu_io_mixed    | 477 ms                                                      | 467 ms: 1.02x faster                                                        |
| async_tree_cpu_io_mixed_tg | 483 ms                                                      | 491 ms: 1.02x slower                                                        |
| async_tree_none_tg         | 277 ms                                                      | 290 ms: 1.05x slower                                                        |
| async_tree_io              | 712 ms                                                      | 752 ms: 1.06x slower                                                        |
| async_tree_io_tg           | 742 ms                                                      | 785 ms: 1.06x slower                                                        |
| async_tree_memoization     | 333 ms                                                      | 356 ms: 1.07x slower                                                        |
| async_tree_memoization_tg  | 345 ms                                                      | 379 ms: 1.10x slower                                                        |
| Geometric mean             | (ref)                                                       | 1.04x slower                                                                |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231202-pythonperf1-amd64-python-a9574c68f04695eecd19-3.13.0a2+-a9574c6 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| pidigits       | 150 ms                                                      | 147 ms: 1.02x faster                                                        |
| float          | 54.7 ms                                                     | 57.6 ms: 1.05x slower                                                       |
| nbody          | 68.8 ms                                                     | 81.7 ms: 1.19x slower                                                       |
| Geometric mean | (ref)                                                       | 1.07x slower                                                                |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231202-pythonperf1-amd64-python-a9574c68f04695eecd19-3.13.0a2+-a9574c6 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_effbot   | 1.58 ms                                                     | 1.59 ms: 1.00x slower                                                       |
| regex_compile  | 87.2 ms                                                     | 92.1 ms: 1.06x slower                                                       |
| regex_v8       | 13.5 ms                                                     | 19.5 ms: 1.45x slower                                                       |
| Geometric mean | (ref)                                                       | 1.11x slower                                                                |

Benchmark hidden because not significant (1): regex_dna

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231202-pythonperf1-amd64-python-a9574c68f04695eecd19-3.13.0a2+-a9574c6 |
|----------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| pickle               | 7.38 us                                                     | 6.89 us: 1.07x faster                                                       |
| unpickle_list        | 2.69 us                                                     | 2.57 us: 1.05x faster                                                       |
| unpickle             | 8.44 us                                                     | 8.13 us: 1.04x faster                                                       |
| pickle_dict          | 18.9 us                                                     | 18.3 us: 1.03x faster                                                       |
| json_loads           | 13.6 us                                                     | 13.4 us: 1.02x faster                                                       |
| pickle_pure_python   | 195 us                                                      | 192 us: 1.01x faster                                                        |
| json_dumps           | 5.83 ms                                                     | 5.86 ms: 1.00x slower                                                       |
| xml_etree_generate   | 55.8 ms                                                     | 57.3 ms: 1.03x slower                                                       |
| xml_etree_parse      | 90.5 ms                                                     | 93.1 ms: 1.03x slower                                                       |
| xml_etree_process    | 37.6 ms                                                     | 39.8 ms: 1.06x slower                                                       |
| xml_etree_iterparse  | 63.1 ms                                                     | 67.6 ms: 1.07x slower                                                       |
| pickle_list          | 2.88 us                                                     | 3.10 us: 1.07x slower                                                       |
| tomli_loads          | 1.38 sec                                                    | 1.49 sec: 1.08x slower                                                      |
| unpickle_pure_python | 134 us                                                      | 146 us: 1.09x slower                                                        |
| Geometric mean       | (ref)                                                       | 1.01x slower                                                                |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231202-pythonperf1-amd64-python-a9574c68f04695eecd19-3.13.0a2+-a9574c6 |
|------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| python_startup         | 18.8 ms                                                     | 20.5 ms: 1.09x slower                                                       |
| python_startup_no_site | 15.9 ms                                                     | 18.5 ms: 1.16x slower                                                       |
| Geometric mean         | (ref)                                                       | 1.12x slower                                                                |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231202-pythonperf1-amd64-python-a9574c68f04695eecd19-3.13.0a2+-a9574c6 |
|-----------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| mako      | 7.05 ms                                                     | 7.37 ms: 1.04x slower                                                       |

All benchmarks:
===============

| Benchmark                  | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231202-pythonperf1-amd64-python-a9574c68f04695eecd19-3.13.0a2+-a9574c6 |
|----------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| typing_runtime_protocols   | 96.7 us                                                     | 83.4 us: 1.16x faster                                                       |
| sqlite_synth               | 1.75 us                                                     | 1.59 us: 1.10x faster                                                       |
| pickle                     | 7.38 us                                                     | 6.89 us: 1.07x faster                                                       |
| comprehensions             | 14.0 us                                                     | 13.2 us: 1.06x faster                                                       |
| unpickle_list              | 2.69 us                                                     | 2.57 us: 1.05x faster                                                       |
| raytrace                   | 192 ms                                                      | 184 ms: 1.05x faster                                                        |
| unpickle                   | 8.44 us                                                     | 8.13 us: 1.04x faster                                                       |
| pickle_dict                | 18.9 us                                                     | 18.3 us: 1.03x faster                                                       |
| async_tree_none            | 286 ms                                                      | 276 ms: 1.03x faster                                                        |
| async_tree_cpu_io_mixed    | 477 ms                                                      | 467 ms: 1.02x faster                                                        |
| json_loads                 | 13.6 us                                                     | 13.4 us: 1.02x faster                                                       |
| pidigits                   | 150 ms                                                      | 147 ms: 1.02x faster                                                        |
| pickle_pure_python         | 195 us                                                      | 192 us: 1.01x faster                                                        |
| generators                 | 22.6 ms                                                     | 22.4 ms: 1.01x faster                                                       |
| scimark_sor                | 79.8 ms                                                     | 79.5 ms: 1.00x faster                                                       |
| regex_effbot               | 1.58 ms                                                     | 1.59 ms: 1.00x slower                                                       |
| json_dumps                 | 5.83 ms                                                     | 5.86 ms: 1.00x slower                                                       |
| mdp                        | 1.42 sec                                                    | 1.43 sec: 1.00x slower                                                      |
| dulwich_log                | 42.7 ms                                                     | 43.0 ms: 1.01x slower                                                       |
| sympy_str                  | 171 ms                                                      | 173 ms: 1.01x slower                                                        |
| deepcopy_reduce            | 2.08 us                                                     | 2.12 us: 1.02x slower                                                       |
| async_tree_cpu_io_mixed_tg | 483 ms                                                      | 491 ms: 1.02x slower                                                        |
| coroutines                 | 14.1 ms                                                     | 14.4 ms: 1.02x slower                                                       |
| deepcopy_memo              | 23.4 us                                                     | 23.8 us: 1.02x slower                                                       |
| bench_mp_pool              | 67.2 ms                                                     | 68.5 ms: 1.02x slower                                                       |
| docutils                   | 1.61 sec                                                    | 1.65 sec: 1.02x slower                                                      |
| deepcopy                   | 233 us                                                      | 239 us: 1.03x slower                                                        |
| gc_traversal               | 1.49 ms                                                     | 1.53 ms: 1.03x slower                                                       |
| xml_etree_generate         | 55.8 ms                                                     | 57.3 ms: 1.03x slower                                                       |
| asyncio_tcp                | 471 ms                                                      | 484 ms: 1.03x slower                                                        |
| logging_silent             | 60.5 ns                                                     | 62.2 ns: 1.03x slower                                                       |
| xml_etree_parse            | 90.5 ms                                                     | 93.1 ms: 1.03x slower                                                       |
| scimark_lu                 | 57.5 ms                                                     | 59.5 ms: 1.04x slower                                                       |
| create_gc_cycles           | 726 us                                                      | 753 us: 1.04x slower                                                        |
| tornado_http               | 87.2 ms                                                     | 90.6 ms: 1.04x slower                                                       |
| pycparser                  | 673 ms                                                      | 701 ms: 1.04x slower                                                        |
| mako                       | 7.05 ms                                                     | 7.37 ms: 1.04x slower                                                       |
| sympy_expand               | 278 ms                                                      | 290 ms: 1.04x slower                                                        |
| async_tree_none_tg         | 277 ms                                                      | 290 ms: 1.05x slower                                                        |
| logging_format             | 6.72 us                                                     | 7.05 us: 1.05x slower                                                       |
| dask                       | 255 ms                                                      | 268 ms: 1.05x slower                                                        |
| sympy_integrate            | 13.0 ms                                                     | 13.6 ms: 1.05x slower                                                       |
| float                      | 54.7 ms                                                     | 57.6 ms: 1.05x slower                                                       |
| crypto_pyaes               | 46.4 ms                                                     | 49.0 ms: 1.05x slower                                                       |
| unpack_sequence            | 36.9 ns                                                     | 38.9 ns: 1.06x slower                                                       |
| regex_compile              | 87.2 ms                                                     | 92.1 ms: 1.06x slower                                                       |
| async_tree_io              | 712 ms                                                      | 752 ms: 1.06x slower                                                        |
| async_tree_io_tg           | 742 ms                                                      | 785 ms: 1.06x slower                                                        |
| chameleon                  | 4.95 ms                                                     | 5.24 ms: 1.06x slower                                                       |
| logging_simple             | 6.21 us                                                     | 6.57 us: 1.06x slower                                                       |
| xml_etree_process          | 37.6 ms                                                     | 39.8 ms: 1.06x slower                                                       |
| sqlglot_parse              | 802 us                                                      | 849 us: 1.06x slower                                                        |
| sqlglot_normalize          | 183 ms                                                      | 195 ms: 1.06x slower                                                        |
| bench_thread_pool          | 830 us                                                      | 882 us: 1.06x slower                                                        |
| sqlglot_transpile          | 1.02 ms                                                     | 1.08 ms: 1.06x slower                                                       |
| async_generators           | 230 ms                                                      | 245 ms: 1.06x slower                                                        |
| 2to3                       | 213 ms                                                      | 227 ms: 1.07x slower                                                        |
| async_tree_memoization     | 333 ms                                                      | 356 ms: 1.07x slower                                                        |
| chaos                      | 42.1 ms                                                     | 45.0 ms: 1.07x slower                                                       |
| xml_etree_iterparse        | 63.1 ms                                                     | 67.6 ms: 1.07x slower                                                       |
| nqueens                    | 61.7 ms                                                     | 66.3 ms: 1.07x slower                                                       |
| pickle_list                | 2.88 us                                                     | 3.10 us: 1.07x slower                                                       |
| meteor_contest             | 72.1 ms                                                     | 77.6 ms: 1.08x slower                                                       |
| richards_super             | 31.2 ms                                                     | 33.6 ms: 1.08x slower                                                       |
| go                         | 89.0 ms                                                     | 96.3 ms: 1.08x slower                                                       |
| pprint_safe_repr           | 508 ms                                                      | 549 ms: 1.08x slower                                                        |
| tomli_loads                | 1.38 sec                                                    | 1.49 sec: 1.08x slower                                                      |
| pprint_pformat             | 1.04 sec                                                    | 1.12 sec: 1.08x slower                                                      |
| python_startup             | 18.8 ms                                                     | 20.5 ms: 1.09x slower                                                       |
| richards                   | 27.6 ms                                                     | 30.0 ms: 1.09x slower                                                       |
| sqlglot_optimize           | 34.0 ms                                                     | 37.1 ms: 1.09x slower                                                       |
| unpickle_pure_python       | 134 us                                                      | 146 us: 1.09x slower                                                        |
| async_tree_memoization_tg  | 345 ms                                                      | 379 ms: 1.10x slower                                                        |
| pyflate                    | 294 ms                                                      | 325 ms: 1.11x slower                                                        |
| fannkuch                   | 244 ms                                                      | 273 ms: 1.12x slower                                                        |
| scimark_fft                | 181 ms                                                      | 207 ms: 1.14x slower                                                        |
| scimark_monte_carlo        | 43.0 ms                                                     | 49.8 ms: 1.16x slower                                                       |
| python_startup_no_site     | 15.9 ms                                                     | 18.5 ms: 1.16x slower                                                       |
| telco                      | 4.08 ms                                                     | 4.73 ms: 1.16x slower                                                       |
| nbody                      | 68.8 ms                                                     | 81.7 ms: 1.19x slower                                                       |
| coverage                   | 39.8 ms                                                     | 47.3 ms: 1.19x slower                                                       |
| scimark_sparse_mat_mult    | 2.51 ms                                                     | 3.08 ms: 1.23x slower                                                       |
| hexiom                     | 4.00 ms                                                     | 5.08 ms: 1.27x slower                                                       |
| spectral_norm              | 63.9 ms                                                     | 81.5 ms: 1.27x slower                                                       |
| deltablue                  | 2.12 ms                                                     | 2.76 ms: 1.30x slower                                                       |
| regex_v8                   | 13.5 ms                                                     | 19.5 ms: 1.45x slower                                                       |
| mypy2                      | 209 ms                                                      | 439 ms: 2.10x slower                                                        |
| Geometric mean             | (ref)                                                       | 1.06x slower                                                                |

Benchmark hidden because not significant (5): asyncio_tcp_ssl, sympy_sum, regex_dna, pathlib, json
Ignored benchmarks (4) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, django_template, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.04x
- 95% likely to have a slowdown of 1.04x
- 99% likely to have a slowdown of 1.03x
