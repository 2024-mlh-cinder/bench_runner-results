
# Results vs. 3.12.0

- fork: mdboom
- ref: optimize_off
- machine: windows-amd64
- commit hash: eadfe93
- commit date: 2023-11-06
- overall geometric mean: 1.49x slower \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.34x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231106-pythonperf1-amd64-mdboom-optimize_off-3.13.0a1+-eadfe93 |
|----------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| 2to3           | 213 ms                                                      | 305 ms: 1.44x slower                                                |
| chameleon      | 4.95 ms                                                     | 8.28 ms: 1.67x slower                                               |
| docutils       | 1.61 sec                                                    | 2.09 sec: 1.30x slower                                              |
| tornado_http   | 87.2 ms                                                     | 106 ms: 1.22x slower                                                |
| Geometric mean | (ref)                                                       | 1.40x slower                                                        |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231106-pythonperf1-amd64-mdboom-optimize_off-3.13.0a1+-eadfe93 |
|----------------------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| async_tree_cpu_io_mixed    | 477 ms                                                      | 591 ms: 1.24x slower                                                |
| async_tree_cpu_io_mixed_tg | 483 ms                                                      | 611 ms: 1.26x slower                                                |
| async_tree_none            | 286 ms                                                      | 363 ms: 1.27x slower                                                |
| async_tree_io_tg           | 742 ms                                                      | 944 ms: 1.27x slower                                                |
| async_tree_io              | 712 ms                                                      | 919 ms: 1.29x slower                                                |
| async_tree_none_tg         | 277 ms                                                      | 373 ms: 1.35x slower                                                |
| async_tree_memoization_tg  | 345 ms                                                      | 468 ms: 1.36x slower                                                |
| async_tree_memoization     | 333 ms                                                      | 456 ms: 1.37x slower                                                |
| Geometric mean             | (ref)                                                       | 1.30x slower                                                        |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231106-pythonperf1-amd64-mdboom-optimize_off-3.13.0a1+-eadfe93 |
|----------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| pidigits       | 150 ms                                                      | 153 ms: 1.02x slower                                                |
| float          | 54.7 ms                                                     | 92.6 ms: 1.69x slower                                               |
| nbody          | 68.8 ms                                                     | 129 ms: 1.88x slower                                                |
| Geometric mean | (ref)                                                       | 1.48x slower                                                        |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231106-pythonperf1-amd64-mdboom-optimize_off-3.13.0a1+-eadfe93 |
|----------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| regex_dna      | 119 ms                                                      | 119 ms: 1.01x faster                                                |
| regex_effbot   | 1.58 ms                                                     | 2.04 ms: 1.29x slower                                               |
| regex_v8       | 13.5 ms                                                     | 18.7 ms: 1.38x slower                                               |
| regex_compile  | 87.2 ms                                                     | 132 ms: 1.51x slower                                                |
| Geometric mean | (ref)                                                       | 1.28x slower                                                        |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231106-pythonperf1-amd64-mdboom-optimize_off-3.13.0a1+-eadfe93 |
|----------------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| unpickle_list        | 2.69 us                                                     | 2.85 us: 1.06x slower                                               |
| pickle_dict          | 18.9 us                                                     | 20.1 us: 1.06x slower                                               |
| pickle               | 7.38 us                                                     | 8.11 us: 1.10x slower                                               |
| pickle_list          | 2.88 us                                                     | 3.28 us: 1.14x slower                                               |
| xml_etree_parse      | 90.5 ms                                                     | 109 ms: 1.20x slower                                                |
| unpickle             | 8.44 us                                                     | 10.7 us: 1.27x slower                                               |
| xml_etree_iterparse  | 63.1 ms                                                     | 91.0 ms: 1.44x slower                                               |
| json_dumps           | 5.83 ms                                                     | 8.58 ms: 1.47x slower                                               |
| json_loads           | 13.6 us                                                     | 21.3 us: 1.56x slower                                               |
| xml_etree_generate   | 55.8 ms                                                     | 92.6 ms: 1.66x slower                                               |
| tomli_loads          | 1.38 sec                                                    | 2.33 sec: 1.69x slower                                              |
| xml_etree_process    | 37.6 ms                                                     | 68.0 ms: 1.81x slower                                               |
| pickle_pure_python   | 195 us                                                      | 385 us: 1.98x slower                                                |
| unpickle_pure_python | 134 us                                                      | 301 us: 2.24x slower                                                |
| Geometric mean       | (ref)                                                       | 1.44x slower                                                        |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231106-pythonperf1-amd64-mdboom-optimize_off-3.13.0a1+-eadfe93 |
|------------------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| python_startup         | 18.8 ms                                                     | 21.6 ms: 1.15x slower                                               |
| python_startup_no_site | 15.9 ms                                                     | 19.5 ms: 1.22x slower                                               |
| Geometric mean         | (ref)                                                       | 1.18x slower                                                        |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231106-pythonperf1-amd64-mdboom-optimize_off-3.13.0a1+-eadfe93 |
|-----------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| mako      | 7.05 ms                                                     | 12.1 ms: 1.72x slower                                               |

All benchmarks:
===============

| Benchmark                  | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231106-pythonperf1-amd64-mdboom-optimize_off-3.13.0a1+-eadfe93 |
|----------------------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| sqlglot_normalize          | 183 ms                                                      | 113 ms: 1.62x faster                                                |
| regex_dna                  | 119 ms                                                      | 119 ms: 1.01x faster                                                |
| pidigits                   | 150 ms                                                      | 153 ms: 1.02x slower                                                |
| pathlib                    | 79.6 ms                                                     | 83.4 ms: 1.05x slower                                               |
| unpickle_list              | 2.69 us                                                     | 2.85 us: 1.06x slower                                               |
| pickle_dict                | 18.9 us                                                     | 20.1 us: 1.06x slower                                               |
| asyncio_tcp                | 471 ms                                                      | 508 ms: 1.08x slower                                                |
| sqlite_synth               | 1.75 us                                                     | 1.89 us: 1.08x slower                                               |
| bench_mp_pool              | 67.2 ms                                                     | 73.7 ms: 1.10x slower                                               |
| dulwich_log                | 42.7 ms                                                     | 46.9 ms: 1.10x slower                                               |
| pickle                     | 7.38 us                                                     | 8.11 us: 1.10x slower                                               |
| create_gc_cycles           | 726 us                                                      | 807 us: 1.11x slower                                                |
| pickle_list                | 2.88 us                                                     | 3.28 us: 1.14x slower                                               |
| python_startup             | 18.8 ms                                                     | 21.6 ms: 1.15x slower                                               |
| typing_runtime_protocols   | 96.7 us                                                     | 116 us: 1.20x slower                                                |
| xml_etree_parse            | 90.5 ms                                                     | 109 ms: 1.20x slower                                                |
| tornado_http               | 87.2 ms                                                     | 106 ms: 1.22x slower                                                |
| python_startup_no_site     | 15.9 ms                                                     | 19.5 ms: 1.22x slower                                               |
| async_tree_cpu_io_mixed    | 477 ms                                                      | 591 ms: 1.24x slower                                                |
| bench_thread_pool          | 830 us                                                      | 1.05 ms: 1.26x slower                                               |
| sympy_sum                  | 90.1 ms                                                     | 114 ms: 1.26x slower                                                |
| sympy_str                  | 171 ms                                                      | 217 ms: 1.26x slower                                                |
| async_tree_cpu_io_mixed_tg | 483 ms                                                      | 611 ms: 1.26x slower                                                |
| unpickle                   | 8.44 us                                                     | 10.7 us: 1.27x slower                                               |
| async_tree_none            | 286 ms                                                      | 363 ms: 1.27x slower                                                |
| async_tree_io_tg           | 742 ms                                                      | 944 ms: 1.27x slower                                                |
| mdp                        | 1.42 sec                                                    | 1.81 sec: 1.28x slower                                              |
| async_tree_io              | 712 ms                                                      | 919 ms: 1.29x slower                                                |
| regex_effbot               | 1.58 ms                                                     | 2.04 ms: 1.29x slower                                               |
| docutils                   | 1.61 sec                                                    | 2.09 sec: 1.30x slower                                              |
| sympy_expand               | 278 ms                                                      | 370 ms: 1.33x slower                                                |
| async_tree_none_tg         | 277 ms                                                      | 373 ms: 1.35x slower                                                |
| async_tree_memoization_tg  | 345 ms                                                      | 468 ms: 1.36x slower                                                |
| meteor_contest             | 72.1 ms                                                     | 97.9 ms: 1.36x slower                                               |
| async_tree_memoization     | 333 ms                                                      | 456 ms: 1.37x slower                                                |
| mypy2                      | 209 ms                                                      | 287 ms: 1.37x slower                                                |
| sympy_integrate            | 13.0 ms                                                     | 17.8 ms: 1.37x slower                                               |
| regex_v8                   | 13.5 ms                                                     | 18.7 ms: 1.38x slower                                               |
| json                       | 2.94 ms                                                     | 4.12 ms: 1.40x slower                                               |
| gc_traversal               | 1.49 ms                                                     | 2.13 ms: 1.43x slower                                               |
| 2to3                       | 213 ms                                                      | 305 ms: 1.44x slower                                                |
| xml_etree_iterparse        | 63.1 ms                                                     | 91.0 ms: 1.44x slower                                               |
| json_dumps                 | 5.83 ms                                                     | 8.58 ms: 1.47x slower                                               |
| regex_compile              | 87.2 ms                                                     | 132 ms: 1.51x slower                                                |
| comprehensions             | 14.0 us                                                     | 21.2 us: 1.51x slower                                               |
| logging_format             | 6.72 us                                                     | 10.3 us: 1.54x slower                                               |
| json_loads                 | 13.6 us                                                     | 21.3 us: 1.56x slower                                               |
| logging_simple             | 6.21 us                                                     | 9.87 us: 1.59x slower                                               |
| sqlglot_optimize           | 34.0 ms                                                     | 54.2 ms: 1.59x slower                                               |
| nqueens                    | 61.7 ms                                                     | 98.7 ms: 1.60x slower                                               |
| telco                      | 4.08 ms                                                     | 6.55 ms: 1.60x slower                                               |
| coverage                   | 39.8 ms                                                     | 64.3 ms: 1.62x slower                                               |
| async_generators           | 230 ms                                                      | 375 ms: 1.63x slower                                                |
| crypto_pyaes               | 46.4 ms                                                     | 76.9 ms: 1.66x slower                                               |
| xml_etree_generate         | 55.8 ms                                                     | 92.6 ms: 1.66x slower                                               |
| deepcopy_reduce            | 2.08 us                                                     | 3.48 us: 1.67x slower                                               |
| scimark_sparse_mat_mult    | 2.51 ms                                                     | 4.20 ms: 1.67x slower                                               |
| chameleon                  | 4.95 ms                                                     | 8.28 ms: 1.67x slower                                               |
| deepcopy                   | 233 us                                                      | 390 us: 1.68x slower                                                |
| tomli_loads                | 1.38 sec                                                    | 2.33 sec: 1.69x slower                                              |
| float                      | 54.7 ms                                                     | 92.6 ms: 1.69x slower                                               |
| scimark_fft                | 181 ms                                                      | 308 ms: 1.70x slower                                                |
| unpack_sequence            | 36.9 ns                                                     | 63.4 ns: 1.72x slower                                               |
| mako                       | 7.05 ms                                                     | 12.1 ms: 1.72x slower                                               |
| pycparser                  | 673 ms                                                      | 1.16 sec: 1.73x slower                                              |
| fannkuch                   | 244 ms                                                      | 426 ms: 1.74x slower                                                |
| pyflate                    | 294 ms                                                      | 515 ms: 1.76x slower                                                |
| sqlglot_transpile          | 1.02 ms                                                     | 1.79 ms: 1.76x slower                                               |
| pprint_pformat             | 1.04 sec                                                    | 1.83 sec: 1.77x slower                                              |
| pprint_safe_repr           | 508 ms                                                      | 898 ms: 1.77x slower                                                |
| xml_etree_process          | 37.6 ms                                                     | 68.0 ms: 1.81x slower                                               |
| sqlglot_parse              | 802 us                                                      | 1.45 ms: 1.81x slower                                               |
| raytrace                   | 192 ms                                                      | 349 ms: 1.81x slower                                                |
| chaos                      | 42.1 ms                                                     | 76.6 ms: 1.82x slower                                               |
| nbody                      | 68.8 ms                                                     | 129 ms: 1.88x slower                                                |
| spectral_norm              | 63.9 ms                                                     | 123 ms: 1.93x slower                                                |
| coroutines                 | 14.1 ms                                                     | 27.5 ms: 1.95x slower                                               |
| pickle_pure_python         | 195 us                                                      | 385 us: 1.98x slower                                                |
| generators                 | 22.6 ms                                                     | 45.2 ms: 2.00x slower                                               |
| scimark_monte_carlo        | 43.0 ms                                                     | 86.9 ms: 2.02x slower                                               |
| deepcopy_memo              | 23.4 us                                                     | 47.6 us: 2.03x slower                                               |
| scimark_sor                | 79.8 ms                                                     | 168 ms: 2.11x slower                                                |
| go                         | 89.0 ms                                                     | 190 ms: 2.13x slower                                                |
| hexiom                     | 4.00 ms                                                     | 8.61 ms: 2.15x slower                                               |
| richards_super             | 31.2 ms                                                     | 68.5 ms: 2.20x slower                                               |
| richards                   | 27.6 ms                                                     | 61.7 ms: 2.24x slower                                               |
| unpickle_pure_python       | 134 us                                                      | 301 us: 2.24x slower                                                |
| scimark_lu                 | 57.5 ms                                                     | 130 ms: 2.27x slower                                                |
| deltablue                  | 2.12 ms                                                     | 5.23 ms: 2.46x slower                                               |
| logging_silent             | 60.5 ns                                                     | 151 ns: 2.50x slower                                                |
| Geometric mean             | (ref)                                                       | 1.49x slower                                                        |

Benchmark hidden because not significant (1): asyncio_tcp_ssl
Ignored benchmarks (5) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, dask, django_template, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.37x
- 95% likely to have a slowdown of 1.36x
- 99% likely to have a slowdown of 1.34x
