
# Results vs. 3.11.0

- fork: python
- ref: 2dbb2e035b968811ddc0
- machine: windows-amd64
- commit hash: 2dbb2e0
- commit date: 2023-11-17
- overall geometric mean: 1.02x faster \*
- HPT reliability: 79.66%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231117-pythonperf1-amd64-python-2dbb2e035b968811ddc0-3.13.0a1+-2dbb2e0 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| 2to3           | 207 ms                                                      | 218 ms: 1.05x slower                                                        |
| chameleon      | 5.35 ms                                                     | 4.95 ms: 1.08x faster                                                       |
| Geometric mean | (ref)                                                       | 1.01x faster                                                                |

Benchmark hidden because not significant (2): docutils, tornado_http

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231117-pythonperf1-amd64-python-2dbb2e035b968811ddc0-3.13.0a1+-2dbb2e0 |
|----------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| async_tree_none            | 314 ms                                                      | 276 ms: 1.14x faster                                                        |
| async_tree_cpu_io_mixed    | 495 ms                                                      | 461 ms: 1.07x faster                                                        |
| async_tree_memoization     | 367 ms                                                      | 348 ms: 1.05x faster                                                        |
| async_tree_none_tg         | 299 ms                                                      | 288 ms: 1.04x faster                                                        |
| async_tree_cpu_io_mixed_tg | 503 ms                                                      | 488 ms: 1.03x faster                                                        |
| async_tree_memoization_tg  | 380 ms                                                      | 369 ms: 1.03x faster                                                        |
| async_tree_io_tg           | 795 ms                                                      | 775 ms: 1.03x faster                                                        |
| async_tree_io              | 753 ms                                                      | 739 ms: 1.02x faster                                                        |
| Geometric mean             | (ref)                                                       | 1.05x faster                                                                |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231117-pythonperf1-amd64-python-2dbb2e035b968811ddc0-3.13.0a1+-2dbb2e0 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| float          | 54.4 ms                                                     | 59.8 ms: 1.10x slower                                                       |
| nbody          | 69.3 ms                                                     | 78.6 ms: 1.13x slower                                                       |
| Geometric mean | (ref)                                                       | 1.07x slower                                                                |

Benchmark hidden because not significant (1): pidigits

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231117-pythonperf1-amd64-python-2dbb2e035b968811ddc0-3.13.0a1+-2dbb2e0 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_dna      | 121 ms                                                      | 120 ms: 1.01x faster                                                        |
| regex_compile  | 90.8 ms                                                     | 91.4 ms: 1.01x slower                                                       |
| regex_effbot   | 1.52 ms                                                     | 1.58 ms: 1.04x slower                                                       |
| regex_v8       | 13.7 ms                                                     | 15.4 ms: 1.12x slower                                                       |
| Geometric mean | (ref)                                                       | 1.04x slower                                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231117-pythonperf1-amd64-python-2dbb2e035b968811ddc0-3.13.0a1+-2dbb2e0 |
|----------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| json_dumps           | 7.90 ms                                                     | 5.75 ms: 1.38x faster                                                       |
| pickle_pure_python   | 207 us                                                      | 180 us: 1.15x faster                                                        |
| unpickle_pure_python | 152 us                                                      | 142 us: 1.07x faster                                                        |
| xml_etree_parse      | 94.5 ms                                                     | 92.5 ms: 1.02x faster                                                       |
| xml_etree_process    | 37.0 ms                                                     | 37.3 ms: 1.01x slower                                                       |
| unpickle_list        | 2.57 us                                                     | 2.64 us: 1.03x slower                                                       |
| xml_etree_iterparse  | 63.0 ms                                                     | 65.7 ms: 1.04x slower                                                       |
| unpickle             | 7.82 us                                                     | 8.17 us: 1.04x slower                                                       |
| xml_etree_generate   | 52.2 ms                                                     | 54.6 ms: 1.05x slower                                                       |
| json_loads           | 12.9 us                                                     | 13.6 us: 1.05x slower                                                       |
| pickle_dict          | 17.8 us                                                     | 18.7 us: 1.05x slower                                                       |
| pickle               | 6.53 us                                                     | 7.13 us: 1.09x slower                                                       |
| tomli_loads          | 1.42 sec                                                    | 1.59 sec: 1.12x slower                                                      |
| pickle_list          | 2.68 us                                                     | 3.04 us: 1.13x slower                                                       |
| Geometric mean       | (ref)                                                       | 1.00x slower                                                                |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231117-pythonperf1-amd64-python-2dbb2e035b968811ddc0-3.13.0a1+-2dbb2e0 |
|------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| python_startup         | 18.8 ms                                                     | 19.6 ms: 1.04x slower                                                       |
| python_startup_no_site | 15.5 ms                                                     | 17.7 ms: 1.14x slower                                                       |
| Geometric mean         | (ref)                                                       | 1.09x slower                                                                |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231117-pythonperf1-amd64-python-2dbb2e035b968811ddc0-3.13.0a1+-2dbb2e0 |
|-----------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| mako      | 7.55 ms                                                     | 8.30 ms: 1.10x slower                                                       |

All benchmarks:
===============

| Benchmark                  | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231117-pythonperf1-amd64-python-2dbb2e035b968811ddc0-3.13.0a1+-2dbb2e0 |
|----------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| typing_runtime_protocols   | 320 us                                                      | 80.2 us: 3.99x faster                                                       |
| generators                 | 34.0 ms                                                     | 20.6 ms: 1.65x faster                                                       |
| json_dumps                 | 7.90 ms                                                     | 5.75 ms: 1.38x faster                                                       |
| asyncio_tcp                | 614 ms                                                      | 480 ms: 1.28x faster                                                        |
| unpack_sequence            | 47.0 ns                                                     | 38.0 ns: 1.24x faster                                                       |
| richards_super             | 37.9 ms                                                     | 31.4 ms: 1.21x faster                                                       |
| logging_silent             | 70.7 ns                                                     | 58.7 ns: 1.20x faster                                                       |
| raytrace                   | 211 ms                                                      | 177 ms: 1.19x faster                                                        |
| sqlglot_parse              | 939 us                                                      | 787 us: 1.19x faster                                                        |
| sympy_sum                  | 100.0 ms                                                    | 84.6 ms: 1.18x faster                                                       |
| spectral_norm              | 69.9 ms                                                     | 59.7 ms: 1.17x faster                                                       |
| pickle_pure_python         | 207 us                                                      | 180 us: 1.15x faster                                                        |
| sqlglot_transpile          | 1.15 ms                                                     | 1.00 ms: 1.14x faster                                                       |
| mdp                        | 1.73 sec                                                    | 1.52 sec: 1.14x faster                                                      |
| asyncio_tcp_ssl            | 2.02 sec                                                    | 1.78 sec: 1.14x faster                                                      |
| async_tree_none            | 314 ms                                                      | 276 ms: 1.14x faster                                                        |
| sqlite_synth               | 1.79 us                                                     | 1.58 us: 1.13x faster                                                       |
| coroutines                 | 14.7 ms                                                     | 13.1 ms: 1.12x faster                                                       |
| sympy_str                  | 184 ms                                                      | 165 ms: 1.11x faster                                                        |
| richards                   | 30.8 ms                                                     | 27.9 ms: 1.10x faster                                                       |
| deepcopy                   | 242 us                                                      | 222 us: 1.09x faster                                                        |
| chameleon                  | 5.35 ms                                                     | 4.95 ms: 1.08x faster                                                       |
| sqlglot_normalize          | 191 ms                                                      | 177 ms: 1.08x faster                                                        |
| async_tree_cpu_io_mixed    | 495 ms                                                      | 461 ms: 1.07x faster                                                        |
| deepcopy_memo              | 25.5 us                                                     | 23.7 us: 1.07x faster                                                       |
| unpickle_pure_python       | 152 us                                                      | 142 us: 1.07x faster                                                        |
| sympy_expand               | 299 ms                                                      | 280 ms: 1.07x faster                                                        |
| scimark_lu                 | 62.3 ms                                                     | 58.6 ms: 1.06x faster                                                       |
| async_tree_memoization     | 367 ms                                                      | 348 ms: 1.05x faster                                                        |
| sqlglot_optimize           | 35.1 ms                                                     | 33.6 ms: 1.04x faster                                                       |
| deepcopy_reduce            | 2.07 us                                                     | 1.99 us: 1.04x faster                                                       |
| dulwich_log                | 44.1 ms                                                     | 42.3 ms: 1.04x faster                                                       |
| chaos                      | 46.8 ms                                                     | 45.0 ms: 1.04x faster                                                       |
| async_tree_none_tg         | 299 ms                                                      | 288 ms: 1.04x faster                                                        |
| async_tree_cpu_io_mixed_tg | 503 ms                                                      | 488 ms: 1.03x faster                                                        |
| async_tree_memoization_tg  | 380 ms                                                      | 369 ms: 1.03x faster                                                        |
| logging_simple             | 6.60 us                                                     | 6.43 us: 1.03x faster                                                       |
| async_tree_io_tg           | 795 ms                                                      | 775 ms: 1.03x faster                                                        |
| dask                       | 262 ms                                                      | 256 ms: 1.03x faster                                                        |
| sympy_integrate            | 13.7 ms                                                     | 13.4 ms: 1.03x faster                                                       |
| logging_format             | 7.06 us                                                     | 6.89 us: 1.02x faster                                                       |
| xml_etree_parse            | 94.5 ms                                                     | 92.5 ms: 1.02x faster                                                       |
| async_tree_io              | 753 ms                                                      | 739 ms: 1.02x faster                                                        |
| regex_dna                  | 121 ms                                                      | 120 ms: 1.01x faster                                                        |
| regex_compile              | 90.8 ms                                                     | 91.4 ms: 1.01x slower                                                       |
| xml_etree_process          | 37.0 ms                                                     | 37.3 ms: 1.01x slower                                                       |
| scimark_sor                | 76.4 ms                                                     | 77.6 ms: 1.02x slower                                                       |
| unpickle_list              | 2.57 us                                                     | 2.64 us: 1.03x slower                                                       |
| gc_traversal               | 1.46 ms                                                     | 1.51 ms: 1.03x slower                                                       |
| bench_mp_pool              | 61.1 ms                                                     | 63.3 ms: 1.04x slower                                                       |
| pprint_safe_repr           | 519 ms                                                      | 538 ms: 1.04x slower                                                        |
| pprint_pformat             | 1.06 sec                                                    | 1.11 sec: 1.04x slower                                                      |
| regex_effbot               | 1.52 ms                                                     | 1.58 ms: 1.04x slower                                                       |
| xml_etree_iterparse        | 63.0 ms                                                     | 65.7 ms: 1.04x slower                                                       |
| python_startup             | 18.8 ms                                                     | 19.6 ms: 1.04x slower                                                       |
| unpickle                   | 7.82 us                                                     | 8.17 us: 1.04x slower                                                       |
| xml_etree_generate         | 52.2 ms                                                     | 54.6 ms: 1.05x slower                                                       |
| json_loads                 | 12.9 us                                                     | 13.6 us: 1.05x slower                                                       |
| 2to3                       | 207 ms                                                      | 218 ms: 1.05x slower                                                        |
| coverage                   | 43.0 ms                                                     | 45.3 ms: 1.05x slower                                                       |
| pickle_dict                | 17.8 us                                                     | 18.7 us: 1.05x slower                                                       |
| meteor_contest             | 75.0 ms                                                     | 79.0 ms: 1.05x slower                                                       |
| create_gc_cycles           | 706 us                                                      | 744 us: 1.05x slower                                                        |
| crypto_pyaes               | 48.2 ms                                                     | 51.2 ms: 1.06x slower                                                       |
| nqueens                    | 66.1 ms                                                     | 70.4 ms: 1.07x slower                                                       |
| pathlib                    | 69.4 ms                                                     | 75.1 ms: 1.08x slower                                                       |
| pickle                     | 6.53 us                                                     | 7.13 us: 1.09x slower                                                       |
| pyflate                    | 305 ms                                                      | 333 ms: 1.09x slower                                                        |
| mako                       | 7.55 ms                                                     | 8.30 ms: 1.10x slower                                                       |
| scimark_monte_carlo        | 44.6 ms                                                     | 49.0 ms: 1.10x slower                                                       |
| float                      | 54.4 ms                                                     | 59.8 ms: 1.10x slower                                                       |
| tomli_loads                | 1.42 sec                                                    | 1.59 sec: 1.12x slower                                                      |
| regex_v8                   | 13.7 ms                                                     | 15.4 ms: 1.12x slower                                                       |
| deltablue                  | 2.63 ms                                                     | 2.96 ms: 1.13x slower                                                       |
| nbody                      | 69.3 ms                                                     | 78.6 ms: 1.13x slower                                                       |
| pickle_list                | 2.68 us                                                     | 3.04 us: 1.13x slower                                                       |
| python_startup_no_site     | 15.5 ms                                                     | 17.7 ms: 1.14x slower                                                       |
| scimark_fft                | 181 ms                                                      | 213 ms: 1.18x slower                                                        |
| fannkuch                   | 248 ms                                                      | 294 ms: 1.19x slower                                                        |
| telco                      | 3.93 ms                                                     | 4.87 ms: 1.24x slower                                                       |
| async_generators           | 181 ms                                                      | 233 ms: 1.29x slower                                                        |
| mypy2                      | 226 ms                                                      | 293 ms: 1.29x slower                                                        |
| hexiom                     | 4.51 ms                                                     | 5.96 ms: 1.32x slower                                                       |
| scimark_sparse_mat_mult    | 2.59 ms                                                     | 3.88 ms: 1.50x slower                                                       |
| Geometric mean             | (ref)                                                       | 1.02x faster                                                                |

Benchmark hidden because not significant (8): pidigits, pycparser, comprehensions, tornado_http, docutils, go, bench_thread_pool, json
Ignored benchmarks (10) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift


# HPT report

- Reliability score: 79.66% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
