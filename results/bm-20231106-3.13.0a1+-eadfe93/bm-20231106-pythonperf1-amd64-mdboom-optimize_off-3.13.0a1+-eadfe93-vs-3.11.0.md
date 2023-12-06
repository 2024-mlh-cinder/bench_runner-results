
# Results vs. 3.11.0

- fork: mdboom
- ref: optimize_off
- machine: windows-amd64
- commit hash: eadfe93
- commit date: 2023-11-06
- overall geometric mean: 1.41x slower \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.26x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231106-pythonperf1-amd64-mdboom-optimize_off-3.13.0a1+-eadfe93 |
|----------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| 2to3           | 207 ms                                                      | 305 ms: 1.47x slower                                                |
| chameleon      | 5.35 ms                                                     | 8.28 ms: 1.55x slower                                               |
| docutils       | 1.59 sec                                                    | 2.09 sec: 1.32x slower                                              |
| tornado_http   | 89.9 ms                                                     | 106 ms: 1.18x slower                                                |
| Geometric mean | (ref)                                                       | 1.37x slower                                                        |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231106-pythonperf1-amd64-mdboom-optimize_off-3.13.0a1+-eadfe93 |
|----------------------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| async_tree_none            | 314 ms                                                      | 363 ms: 1.16x slower                                                |
| async_tree_io_tg           | 795 ms                                                      | 944 ms: 1.19x slower                                                |
| async_tree_cpu_io_mixed    | 495 ms                                                      | 591 ms: 1.19x slower                                                |
| async_tree_cpu_io_mixed_tg | 503 ms                                                      | 611 ms: 1.21x slower                                                |
| async_tree_io              | 753 ms                                                      | 919 ms: 1.22x slower                                                |
| async_tree_memoization_tg  | 380 ms                                                      | 468 ms: 1.23x slower                                                |
| async_tree_memoization     | 367 ms                                                      | 456 ms: 1.24x slower                                                |
| async_tree_none_tg         | 299 ms                                                      | 373 ms: 1.25x slower                                                |
| Geometric mean             | (ref)                                                       | 1.21x slower                                                        |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231106-pythonperf1-amd64-mdboom-optimize_off-3.13.0a1+-eadfe93 |
|----------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| pidigits       | 149 ms                                                      | 153 ms: 1.03x slower                                                |
| float          | 54.4 ms                                                     | 92.6 ms: 1.70x slower                                               |
| nbody          | 69.3 ms                                                     | 129 ms: 1.87x slower                                                |
| Geometric mean | (ref)                                                       | 1.48x slower                                                        |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231106-pythonperf1-amd64-mdboom-optimize_off-3.13.0a1+-eadfe93 |
|----------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| regex_dna      | 121 ms                                                      | 119 ms: 1.02x faster                                                |
| regex_effbot   | 1.52 ms                                                     | 2.04 ms: 1.35x slower                                               |
| regex_v8       | 13.7 ms                                                     | 18.7 ms: 1.36x slower                                               |
| regex_compile  | 90.8 ms                                                     | 132 ms: 1.45x slower                                                |
| Geometric mean | (ref)                                                       | 1.27x slower                                                        |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231106-pythonperf1-amd64-mdboom-optimize_off-3.13.0a1+-eadfe93 |
|----------------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| json_dumps           | 7.90 ms                                                     | 8.58 ms: 1.09x slower                                               |
| unpickle_list        | 2.57 us                                                     | 2.85 us: 1.11x slower                                               |
| pickle_dict          | 17.8 us                                                     | 20.1 us: 1.13x slower                                               |
| xml_etree_parse      | 94.5 ms                                                     | 109 ms: 1.15x slower                                                |
| pickle_list          | 2.68 us                                                     | 3.28 us: 1.22x slower                                               |
| pickle               | 6.53 us                                                     | 8.11 us: 1.24x slower                                               |
| unpickle             | 7.82 us                                                     | 10.7 us: 1.37x slower                                               |
| xml_etree_iterparse  | 63.0 ms                                                     | 91.0 ms: 1.45x slower                                               |
| tomli_loads          | 1.42 sec                                                    | 2.33 sec: 1.64x slower                                              |
| json_loads           | 12.9 us                                                     | 21.3 us: 1.65x slower                                               |
| xml_etree_generate   | 52.2 ms                                                     | 92.6 ms: 1.77x slower                                               |
| xml_etree_process    | 37.0 ms                                                     | 68.0 ms: 1.84x slower                                               |
| pickle_pure_python   | 207 us                                                      | 385 us: 1.86x slower                                                |
| unpickle_pure_python | 152 us                                                      | 301 us: 1.98x slower                                                |
| Geometric mean       | (ref)                                                       | 1.43x slower                                                        |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231106-pythonperf1-amd64-mdboom-optimize_off-3.13.0a1+-eadfe93 |
|------------------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| python_startup         | 18.8 ms                                                     | 21.6 ms: 1.15x slower                                               |
| python_startup_no_site | 15.5 ms                                                     | 19.5 ms: 1.25x slower                                               |
| Geometric mean         | (ref)                                                       | 1.20x slower                                                        |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231106-pythonperf1-amd64-mdboom-optimize_off-3.13.0a1+-eadfe93 |
|-----------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| mako      | 7.55 ms                                                     | 12.1 ms: 1.60x slower                                               |

All benchmarks:
===============

| Benchmark                  | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231106-pythonperf1-amd64-mdboom-optimize_off-3.13.0a1+-eadfe93 |
|----------------------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| typing_runtime_protocols   | 320 us                                                      | 116 us: 2.77x faster                                                |
| sqlglot_normalize          | 191 ms                                                      | 113 ms: 1.68x faster                                                |
| asyncio_tcp                | 614 ms                                                      | 508 ms: 1.21x faster                                                |
| asyncio_tcp_ssl            | 2.02 sec                                                    | 1.92 sec: 1.06x faster                                              |
| regex_dna                  | 121 ms                                                      | 119 ms: 1.02x faster                                                |
| pidigits                   | 149 ms                                                      | 153 ms: 1.03x slower                                                |
| mdp                        | 1.73 sec                                                    | 1.81 sec: 1.05x slower                                              |
| sqlite_synth               | 1.79 us                                                     | 1.89 us: 1.05x slower                                               |
| dulwich_log                | 44.1 ms                                                     | 46.9 ms: 1.06x slower                                               |
| json_dumps                 | 7.90 ms                                                     | 8.58 ms: 1.09x slower                                               |
| unpickle_list              | 2.57 us                                                     | 2.85 us: 1.11x slower                                               |
| pickle_dict                | 17.8 us                                                     | 20.1 us: 1.13x slower                                               |
| sympy_sum                  | 100.0 ms                                                    | 114 ms: 1.14x slower                                                |
| create_gc_cycles           | 706 us                                                      | 807 us: 1.14x slower                                                |
| python_startup             | 18.8 ms                                                     | 21.6 ms: 1.15x slower                                               |
| xml_etree_parse            | 94.5 ms                                                     | 109 ms: 1.15x slower                                                |
| async_tree_none            | 314 ms                                                      | 363 ms: 1.16x slower                                                |
| sympy_str                  | 184 ms                                                      | 217 ms: 1.18x slower                                                |
| tornado_http               | 89.9 ms                                                     | 106 ms: 1.18x slower                                                |
| async_tree_io_tg           | 795 ms                                                      | 944 ms: 1.19x slower                                                |
| async_tree_cpu_io_mixed    | 495 ms                                                      | 591 ms: 1.19x slower                                                |
| pathlib                    | 69.4 ms                                                     | 83.4 ms: 1.20x slower                                               |
| bench_mp_pool              | 61.1 ms                                                     | 73.7 ms: 1.21x slower                                               |
| async_tree_cpu_io_mixed_tg | 503 ms                                                      | 611 ms: 1.21x slower                                                |
| async_tree_io              | 753 ms                                                      | 919 ms: 1.22x slower                                                |
| pickle_list                | 2.68 us                                                     | 3.28 us: 1.22x slower                                               |
| async_tree_memoization_tg  | 380 ms                                                      | 468 ms: 1.23x slower                                                |
| bench_thread_pool          | 847 us                                                      | 1.05 ms: 1.23x slower                                               |
| sympy_expand               | 299 ms                                                      | 370 ms: 1.24x slower                                                |
| pickle                     | 6.53 us                                                     | 8.11 us: 1.24x slower                                               |
| async_tree_memoization     | 367 ms                                                      | 456 ms: 1.24x slower                                                |
| async_tree_none_tg         | 299 ms                                                      | 373 ms: 1.25x slower                                                |
| python_startup_no_site     | 15.5 ms                                                     | 19.5 ms: 1.25x slower                                               |
| mypy2                      | 226 ms                                                      | 287 ms: 1.27x slower                                                |
| sympy_integrate            | 13.7 ms                                                     | 17.8 ms: 1.30x slower                                               |
| meteor_contest             | 75.0 ms                                                     | 97.9 ms: 1.31x slower                                               |
| docutils                   | 1.59 sec                                                    | 2.09 sec: 1.32x slower                                              |
| generators                 | 34.0 ms                                                     | 45.2 ms: 1.33x slower                                               |
| regex_effbot               | 1.52 ms                                                     | 2.04 ms: 1.35x slower                                               |
| unpack_sequence            | 47.0 ns                                                     | 63.4 ns: 1.35x slower                                               |
| comprehensions             | 15.6 us                                                     | 21.2 us: 1.36x slower                                               |
| regex_v8                   | 13.7 ms                                                     | 18.7 ms: 1.36x slower                                               |
| unpickle                   | 7.82 us                                                     | 10.7 us: 1.37x slower                                               |
| json                       | 2.99 ms                                                     | 4.12 ms: 1.38x slower                                               |
| xml_etree_iterparse        | 63.0 ms                                                     | 91.0 ms: 1.45x slower                                               |
| regex_compile              | 90.8 ms                                                     | 132 ms: 1.45x slower                                                |
| gc_traversal               | 1.46 ms                                                     | 2.13 ms: 1.46x slower                                               |
| logging_format             | 7.06 us                                                     | 10.3 us: 1.46x slower                                               |
| 2to3                       | 207 ms                                                      | 305 ms: 1.47x slower                                                |
| logging_simple             | 6.60 us                                                     | 9.87 us: 1.49x slower                                               |
| nqueens                    | 66.1 ms                                                     | 98.7 ms: 1.49x slower                                               |
| coverage                   | 43.0 ms                                                     | 64.3 ms: 1.50x slower                                               |
| sqlglot_optimize           | 35.1 ms                                                     | 54.2 ms: 1.55x slower                                               |
| sqlglot_parse              | 939 us                                                      | 1.45 ms: 1.55x slower                                               |
| chameleon                  | 5.35 ms                                                     | 8.28 ms: 1.55x slower                                               |
| sqlglot_transpile          | 1.15 ms                                                     | 1.79 ms: 1.56x slower                                               |
| crypto_pyaes               | 48.2 ms                                                     | 76.9 ms: 1.60x slower                                               |
| mako                       | 7.55 ms                                                     | 12.1 ms: 1.60x slower                                               |
| deepcopy                   | 242 us                                                      | 390 us: 1.61x slower                                                |
| scimark_sparse_mat_mult    | 2.59 ms                                                     | 4.20 ms: 1.62x slower                                               |
| chaos                      | 46.8 ms                                                     | 76.6 ms: 1.64x slower                                               |
| tomli_loads                | 1.42 sec                                                    | 2.33 sec: 1.64x slower                                              |
| pycparser                  | 705 ms                                                      | 1.16 sec: 1.65x slower                                              |
| json_loads                 | 12.9 us                                                     | 21.3 us: 1.65x slower                                               |
| raytrace                   | 211 ms                                                      | 349 ms: 1.66x slower                                                |
| telco                      | 3.93 ms                                                     | 6.55 ms: 1.67x slower                                               |
| deepcopy_reduce            | 2.07 us                                                     | 3.48 us: 1.68x slower                                               |
| pyflate                    | 305 ms                                                      | 515 ms: 1.69x slower                                                |
| scimark_fft                | 181 ms                                                      | 308 ms: 1.70x slower                                                |
| float                      | 54.4 ms                                                     | 92.6 ms: 1.70x slower                                               |
| fannkuch                   | 248 ms                                                      | 426 ms: 1.72x slower                                                |
| pprint_pformat             | 1.06 sec                                                    | 1.83 sec: 1.72x slower                                              |
| pprint_safe_repr           | 519 ms                                                      | 898 ms: 1.73x slower                                                |
| spectral_norm              | 69.9 ms                                                     | 123 ms: 1.76x slower                                                |
| xml_etree_generate         | 52.2 ms                                                     | 92.6 ms: 1.77x slower                                               |
| richards_super             | 37.9 ms                                                     | 68.5 ms: 1.81x slower                                               |
| xml_etree_process          | 37.0 ms                                                     | 68.0 ms: 1.84x slower                                               |
| pickle_pure_python         | 207 us                                                      | 385 us: 1.86x slower                                                |
| nbody                      | 69.3 ms                                                     | 129 ms: 1.87x slower                                                |
| deepcopy_memo              | 25.5 us                                                     | 47.6 us: 1.87x slower                                               |
| coroutines                 | 14.7 ms                                                     | 27.5 ms: 1.88x slower                                               |
| hexiom                     | 4.51 ms                                                     | 8.61 ms: 1.91x slower                                               |
| go                         | 98.8 ms                                                     | 190 ms: 1.92x slower                                                |
| scimark_monte_carlo        | 44.6 ms                                                     | 86.9 ms: 1.95x slower                                               |
| unpickle_pure_python       | 152 us                                                      | 301 us: 1.98x slower                                                |
| deltablue                  | 2.63 ms                                                     | 5.23 ms: 1.99x slower                                               |
| richards                   | 30.8 ms                                                     | 61.7 ms: 2.00x slower                                               |
| async_generators           | 181 ms                                                      | 375 ms: 2.07x slower                                                |
| scimark_lu                 | 62.3 ms                                                     | 130 ms: 2.09x slower                                                |
| logging_silent             | 70.7 ns                                                     | 151 ns: 2.14x slower                                                |
| scimark_sor                | 76.4 ms                                                     | 168 ms: 2.20x slower                                                |
| Geometric mean             | (ref)                                                       | 1.41x slower                                                        |
Ignored benchmarks (11) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, dask, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.31x
- 95% likely to have a slowdown of 1.30x
- 99% likely to have a slowdown of 1.26x
