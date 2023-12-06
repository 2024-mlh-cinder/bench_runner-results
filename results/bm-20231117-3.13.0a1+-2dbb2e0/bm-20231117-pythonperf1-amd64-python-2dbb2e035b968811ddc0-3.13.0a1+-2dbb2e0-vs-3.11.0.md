
# Results vs. 3.11.0

- fork: python
- ref: 2dbb2e035b968811ddc0
- machine: windows-amd64
- commit hash: 2dbb2e0
- commit date: 2023-11-17
- overall geometric mean: 1.07x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.02x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231117-pythonperf1-amd64-python-2dbb2e035b968811ddc0-3.13.0a1+-2dbb2e0 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| 2to3           | 207 ms                                                      | 209 ms: 1.01x slower                                                        |
| chameleon      | 5.35 ms                                                     | 4.78 ms: 1.12x faster                                                       |
| docutils       | 1.59 sec                                                    | 1.54 sec: 1.03x faster                                                      |
| tornado_http   | 89.9 ms                                                     | 86.8 ms: 1.04x faster                                                       |
| Geometric mean | (ref)                                                       | 1.04x faster                                                                |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231117-pythonperf1-amd64-python-2dbb2e035b968811ddc0-3.13.0a1+-2dbb2e0 |
|----------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| async_tree_none            | 314 ms                                                      | 265 ms: 1.18x faster                                                        |
| async_tree_cpu_io_mixed    | 495 ms                                                      | 453 ms: 1.09x faster                                                        |
| async_tree_memoization     | 367 ms                                                      | 338 ms: 1.09x faster                                                        |
| async_tree_none_tg         | 299 ms                                                      | 280 ms: 1.07x faster                                                        |
| async_tree_memoization_tg  | 380 ms                                                      | 358 ms: 1.06x faster                                                        |
| async_tree_cpu_io_mixed_tg | 503 ms                                                      | 478 ms: 1.05x faster                                                        |
| async_tree_io_tg           | 795 ms                                                      | 762 ms: 1.04x faster                                                        |
| async_tree_io              | 753 ms                                                      | 728 ms: 1.04x faster                                                        |
| Geometric mean             | (ref)                                                       | 1.08x faster                                                                |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231117-pythonperf1-amd64-python-2dbb2e035b968811ddc0-3.13.0a1+-2dbb2e0 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| float          | 54.4 ms                                                     | 51.8 ms: 1.05x faster                                                       |
| pidigits       | 149 ms                                                      | 147 ms: 1.01x faster                                                        |
| nbody          | 69.3 ms                                                     | 74.6 ms: 1.08x slower                                                       |
| Geometric mean | (ref)                                                       | 1.00x slower                                                                |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231117-pythonperf1-amd64-python-2dbb2e035b968811ddc0-3.13.0a1+-2dbb2e0 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_compile  | 90.8 ms                                                     | 80.5 ms: 1.13x faster                                                       |
| regex_dna      | 121 ms                                                      | 118 ms: 1.02x faster                                                        |
| regex_effbot   | 1.52 ms                                                     | 1.58 ms: 1.04x slower                                                       |
| regex_v8       | 13.7 ms                                                     | 14.9 ms: 1.09x slower                                                       |
| Geometric mean | (ref)                                                       | 1.01x faster                                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231117-pythonperf1-amd64-python-2dbb2e035b968811ddc0-3.13.0a1+-2dbb2e0 |
|----------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| json_dumps           | 7.90 ms                                                     | 5.64 ms: 1.40x faster                                                       |
| unpickle_pure_python | 152 us                                                      | 133 us: 1.14x faster                                                        |
| pickle_pure_python   | 207 us                                                      | 184 us: 1.13x faster                                                        |
| xml_etree_parse      | 94.5 ms                                                     | 92.2 ms: 1.02x faster                                                       |
| xml_etree_iterparse  | 63.0 ms                                                     | 63.6 ms: 1.01x slower                                                       |
| xml_etree_process    | 37.0 ms                                                     | 37.7 ms: 1.02x slower                                                       |
| unpickle             | 7.82 us                                                     | 7.99 us: 1.02x slower                                                       |
| unpickle_list        | 2.57 us                                                     | 2.64 us: 1.03x slower                                                       |
| json_loads           | 12.9 us                                                     | 13.3 us: 1.03x slower                                                       |
| xml_etree_generate   | 52.2 ms                                                     | 54.8 ms: 1.05x slower                                                       |
| pickle_list          | 2.68 us                                                     | 2.87 us: 1.07x slower                                                       |
| pickle               | 6.53 us                                                     | 7.02 us: 1.07x slower                                                       |
| pickle_dict          | 17.8 us                                                     | 19.2 us: 1.08x slower                                                       |
| Geometric mean       | (ref)                                                       | 1.02x faster                                                                |

Benchmark hidden because not significant (1): tomli_loads

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231117-pythonperf1-amd64-python-2dbb2e035b968811ddc0-3.13.0a1+-2dbb2e0 |
|------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| python_startup         | 18.8 ms                                                     | 19.5 ms: 1.03x slower                                                       |
| python_startup_no_site | 15.5 ms                                                     | 17.7 ms: 1.14x slower                                                       |
| Geometric mean         | (ref)                                                       | 1.09x slower                                                                |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231117-pythonperf1-amd64-python-2dbb2e035b968811ddc0-3.13.0a1+-2dbb2e0 |
|-----------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| mako      | 7.55 ms                                                     | 6.49 ms: 1.16x faster                                                       |

All benchmarks:
===============

| Benchmark                  | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231117-pythonperf1-amd64-python-2dbb2e035b968811ddc0-3.13.0a1+-2dbb2e0 |
|----------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| typing_runtime_protocols   | 320 us                                                      | 74.8 us: 4.28x faster                                                       |
| generators                 | 34.0 ms                                                     | 20.7 ms: 1.64x faster                                                       |
| comprehensions             | 15.6 us                                                     | 10.6 us: 1.47x faster                                                       |
| json_dumps                 | 7.90 ms                                                     | 5.64 ms: 1.40x faster                                                       |
| asyncio_tcp                | 614 ms                                                      | 459 ms: 1.34x faster                                                        |
| logging_silent             | 70.7 ns                                                     | 55.7 ns: 1.27x faster                                                       |
| mdp                        | 1.73 sec                                                    | 1.37 sec: 1.26x faster                                                      |
| raytrace                   | 211 ms                                                      | 167 ms: 1.26x faster                                                        |
| deltablue                  | 2.63 ms                                                     | 2.13 ms: 1.23x faster                                                       |
| sqlglot_parse              | 939 us                                                      | 766 us: 1.23x faster                                                        |
| richards_super             | 37.9 ms                                                     | 31.3 ms: 1.21x faster                                                       |
| sympy_sum                  | 100.0 ms                                                    | 83.1 ms: 1.20x faster                                                       |
| async_tree_none            | 314 ms                                                      | 265 ms: 1.18x faster                                                        |
| chaos                      | 46.8 ms                                                     | 40.1 ms: 1.17x faster                                                       |
| hexiom                     | 4.51 ms                                                     | 3.88 ms: 1.16x faster                                                       |
| mako                       | 7.55 ms                                                     | 6.49 ms: 1.16x faster                                                       |
| sqlglot_transpile          | 1.15 ms                                                     | 986 us: 1.16x faster                                                        |
| sympy_str                  | 184 ms                                                      | 159 ms: 1.16x faster                                                        |
| nqueens                    | 66.1 ms                                                     | 57.3 ms: 1.15x faster                                                       |
| sqlite_synth               | 1.79 us                                                     | 1.56 us: 1.15x faster                                                       |
| unpickle_pure_python       | 152 us                                                      | 133 us: 1.14x faster                                                        |
| regex_compile              | 90.8 ms                                                     | 80.5 ms: 1.13x faster                                                       |
| pickle_pure_python         | 207 us                                                      | 184 us: 1.13x faster                                                        |
| go                         | 98.8 ms                                                     | 88.0 ms: 1.12x faster                                                       |
| asyncio_tcp_ssl            | 2.02 sec                                                    | 1.80 sec: 1.12x faster                                                      |
| chameleon                  | 5.35 ms                                                     | 4.78 ms: 1.12x faster                                                       |
| sympy_integrate            | 13.7 ms                                                     | 12.4 ms: 1.11x faster                                                       |
| spectral_norm              | 69.9 ms                                                     | 63.4 ms: 1.10x faster                                                       |
| deepcopy                   | 242 us                                                      | 221 us: 1.10x faster                                                        |
| scimark_lu                 | 62.3 ms                                                     | 56.9 ms: 1.09x faster                                                       |
| crypto_pyaes               | 48.2 ms                                                     | 44.0 ms: 1.09x faster                                                       |
| scimark_sparse_mat_mult    | 2.59 ms                                                     | 2.37 ms: 1.09x faster                                                       |
| async_tree_cpu_io_mixed    | 495 ms                                                      | 453 ms: 1.09x faster                                                        |
| sympy_expand               | 299 ms                                                      | 274 ms: 1.09x faster                                                        |
| async_tree_memoization     | 367 ms                                                      | 338 ms: 1.09x faster                                                        |
| dulwich_log                | 44.1 ms                                                     | 40.8 ms: 1.08x faster                                                       |
| sqlglot_normalize          | 191 ms                                                      | 177 ms: 1.08x faster                                                        |
| richards                   | 30.8 ms                                                     | 28.7 ms: 1.07x faster                                                       |
| scimark_monte_carlo        | 44.6 ms                                                     | 41.8 ms: 1.07x faster                                                       |
| async_tree_none_tg         | 299 ms                                                      | 280 ms: 1.07x faster                                                        |
| deepcopy_memo              | 25.5 us                                                     | 23.9 us: 1.07x faster                                                       |
| json                       | 2.99 ms                                                     | 2.81 ms: 1.07x faster                                                       |
| coroutines                 | 14.7 ms                                                     | 13.8 ms: 1.06x faster                                                       |
| logging_simple             | 6.60 us                                                     | 6.21 us: 1.06x faster                                                       |
| async_tree_memoization_tg  | 380 ms                                                      | 358 ms: 1.06x faster                                                        |
| logging_format             | 7.06 us                                                     | 6.68 us: 1.06x faster                                                       |
| async_tree_cpu_io_mixed_tg | 503 ms                                                      | 478 ms: 1.05x faster                                                        |
| float                      | 54.4 ms                                                     | 51.8 ms: 1.05x faster                                                       |
| deepcopy_reduce            | 2.07 us                                                     | 1.98 us: 1.05x faster                                                       |
| sqlglot_optimize           | 35.1 ms                                                     | 33.6 ms: 1.04x faster                                                       |
| async_tree_io_tg           | 795 ms                                                      | 762 ms: 1.04x faster                                                        |
| tornado_http               | 89.9 ms                                                     | 86.8 ms: 1.04x faster                                                       |
| async_tree_io              | 753 ms                                                      | 728 ms: 1.04x faster                                                        |
| docutils                   | 1.59 sec                                                    | 1.54 sec: 1.03x faster                                                      |
| dask                       | 262 ms                                                      | 254 ms: 1.03x faster                                                        |
| pprint_pformat             | 1.06 sec                                                    | 1.03 sec: 1.03x faster                                                      |
| xml_etree_parse            | 94.5 ms                                                     | 92.2 ms: 1.02x faster                                                       |
| regex_dna                  | 121 ms                                                      | 118 ms: 1.02x faster                                                        |
| pyflate                    | 305 ms                                                      | 298 ms: 1.02x faster                                                        |
| scimark_fft                | 181 ms                                                      | 178 ms: 1.02x faster                                                        |
| pprint_safe_repr           | 519 ms                                                      | 510 ms: 1.02x faster                                                        |
| pidigits                   | 149 ms                                                      | 147 ms: 1.01x faster                                                        |
| meteor_contest             | 75.0 ms                                                     | 74.2 ms: 1.01x faster                                                       |
| 2to3                       | 207 ms                                                      | 209 ms: 1.01x slower                                                        |
| xml_etree_iterparse        | 63.0 ms                                                     | 63.6 ms: 1.01x slower                                                       |
| fannkuch                   | 248 ms                                                      | 251 ms: 1.01x slower                                                        |
| xml_etree_process          | 37.0 ms                                                     | 37.7 ms: 1.02x slower                                                       |
| unpickle                   | 7.82 us                                                     | 7.99 us: 1.02x slower                                                       |
| bench_mp_pool              | 61.1 ms                                                     | 62.6 ms: 1.02x slower                                                       |
| unpickle_list              | 2.57 us                                                     | 2.64 us: 1.03x slower                                                       |
| gc_traversal               | 1.46 ms                                                     | 1.50 ms: 1.03x slower                                                       |
| python_startup             | 18.8 ms                                                     | 19.5 ms: 1.03x slower                                                       |
| json_loads                 | 12.9 us                                                     | 13.3 us: 1.03x slower                                                       |
| regex_effbot               | 1.52 ms                                                     | 1.58 ms: 1.04x slower                                                       |
| xml_etree_generate         | 52.2 ms                                                     | 54.8 ms: 1.05x slower                                                       |
| create_gc_cycles           | 706 us                                                      | 741 us: 1.05x slower                                                        |
| pycparser                  | 705 ms                                                      | 751 ms: 1.07x slower                                                        |
| scimark_sor                | 76.4 ms                                                     | 81.8 ms: 1.07x slower                                                       |
| pickle_list                | 2.68 us                                                     | 2.87 us: 1.07x slower                                                       |
| pickle                     | 6.53 us                                                     | 7.02 us: 1.07x slower                                                       |
| nbody                      | 69.3 ms                                                     | 74.6 ms: 1.08x slower                                                       |
| unpack_sequence            | 47.0 ns                                                     | 50.7 ns: 1.08x slower                                                       |
| pickle_dict                | 17.8 us                                                     | 19.2 us: 1.08x slower                                                       |
| coverage                   | 43.0 ms                                                     | 46.6 ms: 1.08x slower                                                       |
| regex_v8                   | 13.7 ms                                                     | 14.9 ms: 1.09x slower                                                       |
| pathlib                    | 69.4 ms                                                     | 75.5 ms: 1.09x slower                                                       |
| python_startup_no_site     | 15.5 ms                                                     | 17.7 ms: 1.14x slower                                                       |
| telco                      | 3.93 ms                                                     | 4.57 ms: 1.16x slower                                                       |
| mypy2                      | 226 ms                                                      | 287 ms: 1.27x slower                                                        |
| async_generators           | 181 ms                                                      | 229 ms: 1.27x slower                                                        |
| Geometric mean             | (ref)                                                       | 1.07x faster                                                                |

Benchmark hidden because not significant (2): bench_thread_pool, tomli_loads
Ignored benchmarks (10) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.03x
- 95% likely to have a speedup of 1.03x
- 99% likely to have a speedup of 1.02x
