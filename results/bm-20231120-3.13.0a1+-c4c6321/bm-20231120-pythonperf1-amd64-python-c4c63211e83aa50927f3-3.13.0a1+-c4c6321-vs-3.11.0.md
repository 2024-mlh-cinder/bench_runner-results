
# Results vs. 3.11.0

- fork: python
- ref: c4c63211e83aa50927f3
- machine: windows-amd64
- commit hash: c4c6321
- commit date: 2023-11-20
- overall geometric mean: 1.07x faster \*
- HPT reliability: 99.99%
- HPT 99th percentile: 1.02x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-pythonperf1-amd64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| 2to3           | 207 ms                                                      | 212 ms: 1.02x slower                                                        |
| chameleon      | 5.35 ms                                                     | 4.88 ms: 1.10x faster                                                       |
| docutils       | 1.59 sec                                                    | 1.56 sec: 1.02x faster                                                      |
| tornado_http   | 89.9 ms                                                     | 95.6 ms: 1.06x slower                                                       |
| Geometric mean | (ref)                                                       | 1.01x faster                                                                |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-pythonperf1-amd64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 |
|----------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| async_tree_none            | 314 ms                                                      | 269 ms: 1.17x faster                                                        |
| async_tree_cpu_io_mixed    | 495 ms                                                      | 452 ms: 1.09x faster                                                        |
| async_tree_memoization     | 367 ms                                                      | 342 ms: 1.07x faster                                                        |
| async_tree_none_tg         | 299 ms                                                      | 284 ms: 1.05x faster                                                        |
| async_tree_io              | 753 ms                                                      | 715 ms: 1.05x faster                                                        |
| async_tree_cpu_io_mixed_tg | 503 ms                                                      | 480 ms: 1.05x faster                                                        |
| async_tree_memoization_tg  | 380 ms                                                      | 363 ms: 1.04x faster                                                        |
| async_tree_io_tg           | 795 ms                                                      | 764 ms: 1.04x faster                                                        |
| Geometric mean             | (ref)                                                       | 1.07x faster                                                                |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-pythonperf1-amd64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| float          | 54.4 ms                                                     | 52.1 ms: 1.04x faster                                                       |
| pidigits       | 149 ms                                                      | 147 ms: 1.01x faster                                                        |
| nbody          | 69.3 ms                                                     | 75.5 ms: 1.09x slower                                                       |
| Geometric mean | (ref)                                                       | 1.01x slower                                                                |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-pythonperf1-amd64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_compile  | 90.8 ms                                                     | 80.4 ms: 1.13x faster                                                       |
| regex_dna      | 121 ms                                                      | 117 ms: 1.04x faster                                                        |
| regex_effbot   | 1.52 ms                                                     | 1.58 ms: 1.04x slower                                                       |
| regex_v8       | 13.7 ms                                                     | 14.6 ms: 1.07x slower                                                       |
| Geometric mean | (ref)                                                       | 1.01x faster                                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-pythonperf1-amd64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 |
|----------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| json_dumps           | 7.90 ms                                                     | 5.65 ms: 1.40x faster                                                       |
| unpickle_pure_python | 152 us                                                      | 130 us: 1.17x faster                                                        |
| pickle_pure_python   | 207 us                                                      | 181 us: 1.14x faster                                                        |
| xml_etree_parse      | 94.5 ms                                                     | 90.1 ms: 1.05x faster                                                       |
| xml_etree_process    | 37.0 ms                                                     | 37.8 ms: 1.02x slower                                                       |
| unpickle_list        | 2.57 us                                                     | 2.62 us: 1.02x slower                                                       |
| tomli_loads          | 1.42 sec                                                    | 1.45 sec: 1.02x slower                                                      |
| pickle_dict          | 17.8 us                                                     | 18.4 us: 1.04x slower                                                       |
| unpickle             | 7.82 us                                                     | 8.12 us: 1.04x slower                                                       |
| xml_etree_generate   | 52.2 ms                                                     | 54.3 ms: 1.04x slower                                                       |
| json_loads           | 12.9 us                                                     | 13.5 us: 1.04x slower                                                       |
| pickle_list          | 2.68 us                                                     | 2.86 us: 1.07x slower                                                       |
| pickle               | 6.53 us                                                     | 7.03 us: 1.08x slower                                                       |
| Geometric mean       | (ref)                                                       | 1.02x faster                                                                |

Benchmark hidden because not significant (1): xml_etree_iterparse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-pythonperf1-amd64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 |
|------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| python_startup         | 18.8 ms                                                     | 20.3 ms: 1.08x slower                                                       |
| python_startup_no_site | 15.5 ms                                                     | 18.1 ms: 1.17x slower                                                       |
| Geometric mean         | (ref)                                                       | 1.12x slower                                                                |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-pythonperf1-amd64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 |
|-----------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| mako      | 7.55 ms                                                     | 6.53 ms: 1.16x faster                                                       |

All benchmarks:
===============

| Benchmark                  | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-pythonperf1-amd64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 |
|----------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| typing_runtime_protocols   | 320 us                                                      | 77.0 us: 4.15x faster                                                       |
| generators                 | 34.0 ms                                                     | 21.4 ms: 1.59x faster                                                       |
| comprehensions             | 15.6 us                                                     | 10.3 us: 1.51x faster                                                       |
| json_dumps                 | 7.90 ms                                                     | 5.65 ms: 1.40x faster                                                       |
| mdp                        | 1.73 sec                                                    | 1.34 sec: 1.29x faster                                                      |
| raytrace                   | 211 ms                                                      | 165 ms: 1.27x faster                                                        |
| logging_silent             | 70.7 ns                                                     | 56.1 ns: 1.26x faster                                                       |
| deltablue                  | 2.63 ms                                                     | 2.13 ms: 1.23x faster                                                       |
| sqlglot_parse              | 939 us                                                      | 768 us: 1.22x faster                                                        |
| sympy_sum                  | 100.0 ms                                                    | 81.8 ms: 1.22x faster                                                       |
| richards_super             | 37.9 ms                                                     | 31.3 ms: 1.21x faster                                                       |
| sympy_str                  | 184 ms                                                      | 157 ms: 1.17x faster                                                        |
| unpickle_pure_python       | 152 us                                                      | 130 us: 1.17x faster                                                        |
| async_tree_none            | 314 ms                                                      | 269 ms: 1.17x faster                                                        |
| hexiom                     | 4.51 ms                                                     | 3.87 ms: 1.17x faster                                                       |
| chaos                      | 46.8 ms                                                     | 40.2 ms: 1.16x faster                                                       |
| sqlglot_transpile          | 1.15 ms                                                     | 988 us: 1.16x faster                                                        |
| mako                       | 7.55 ms                                                     | 6.53 ms: 1.16x faster                                                       |
| sqlite_synth               | 1.79 us                                                     | 1.56 us: 1.15x faster                                                       |
| pickle_pure_python         | 207 us                                                      | 181 us: 1.14x faster                                                        |
| regex_compile              | 90.8 ms                                                     | 80.4 ms: 1.13x faster                                                       |
| asyncio_tcp                | 614 ms                                                      | 545 ms: 1.13x faster                                                        |
| spectral_norm              | 69.9 ms                                                     | 62.3 ms: 1.12x faster                                                       |
| unpack_sequence            | 47.0 ns                                                     | 41.9 ns: 1.12x faster                                                       |
| go                         | 98.8 ms                                                     | 88.4 ms: 1.12x faster                                                       |
| sympy_expand               | 299 ms                                                      | 268 ms: 1.12x faster                                                        |
| nqueens                    | 66.1 ms                                                     | 59.4 ms: 1.11x faster                                                       |
| coroutines                 | 14.7 ms                                                     | 13.2 ms: 1.11x faster                                                       |
| sympy_integrate            | 13.7 ms                                                     | 12.4 ms: 1.11x faster                                                       |
| crypto_pyaes               | 48.2 ms                                                     | 43.7 ms: 1.10x faster                                                       |
| chameleon                  | 5.35 ms                                                     | 4.88 ms: 1.10x faster                                                       |
| async_tree_cpu_io_mixed    | 495 ms                                                      | 452 ms: 1.09x faster                                                        |
| sqlglot_normalize          | 191 ms                                                      | 177 ms: 1.08x faster                                                        |
| scimark_lu                 | 62.3 ms                                                     | 57.6 ms: 1.08x faster                                                       |
| scimark_sparse_mat_mult    | 2.59 ms                                                     | 2.40 ms: 1.08x faster                                                       |
| logging_simple             | 6.60 us                                                     | 6.13 us: 1.08x faster                                                       |
| deepcopy                   | 242 us                                                      | 226 us: 1.07x faster                                                        |
| logging_format             | 7.06 us                                                     | 6.59 us: 1.07x faster                                                       |
| richards                   | 30.8 ms                                                     | 28.8 ms: 1.07x faster                                                       |
| async_tree_memoization     | 367 ms                                                      | 342 ms: 1.07x faster                                                        |
| dulwich_log                | 44.1 ms                                                     | 41.4 ms: 1.06x faster                                                       |
| async_tree_none_tg         | 299 ms                                                      | 284 ms: 1.05x faster                                                        |
| async_tree_io              | 753 ms                                                      | 715 ms: 1.05x faster                                                        |
| sqlglot_optimize           | 35.1 ms                                                     | 33.3 ms: 1.05x faster                                                       |
| xml_etree_parse            | 94.5 ms                                                     | 90.1 ms: 1.05x faster                                                       |
| async_tree_cpu_io_mixed_tg | 503 ms                                                      | 480 ms: 1.05x faster                                                        |
| deepcopy_reduce            | 2.07 us                                                     | 1.98 us: 1.05x faster                                                       |
| async_tree_memoization_tg  | 380 ms                                                      | 363 ms: 1.04x faster                                                        |
| pprint_safe_repr           | 519 ms                                                      | 496 ms: 1.04x faster                                                        |
| float                      | 54.4 ms                                                     | 52.1 ms: 1.04x faster                                                       |
| pyflate                    | 305 ms                                                      | 292 ms: 1.04x faster                                                        |
| deepcopy_memo              | 25.5 us                                                     | 24.5 us: 1.04x faster                                                       |
| regex_dna                  | 121 ms                                                      | 117 ms: 1.04x faster                                                        |
| pprint_pformat             | 1.06 sec                                                    | 1.02 sec: 1.04x faster                                                      |
| async_tree_io_tg           | 795 ms                                                      | 764 ms: 1.04x faster                                                        |
| meteor_contest             | 75.0 ms                                                     | 73.3 ms: 1.02x faster                                                       |
| docutils                   | 1.59 sec                                                    | 1.56 sec: 1.02x faster                                                      |
| scimark_fft                | 181 ms                                                      | 178 ms: 1.02x faster                                                        |
| pidigits                   | 149 ms                                                      | 147 ms: 1.01x faster                                                        |
| scimark_monte_carlo        | 44.6 ms                                                     | 44.8 ms: 1.00x slower                                                       |
| xml_etree_process          | 37.0 ms                                                     | 37.8 ms: 1.02x slower                                                       |
| unpickle_list              | 2.57 us                                                     | 2.62 us: 1.02x slower                                                       |
| tomli_loads                | 1.42 sec                                                    | 1.45 sec: 1.02x slower                                                      |
| 2to3                       | 207 ms                                                      | 212 ms: 1.02x slower                                                        |
| fannkuch                   | 248 ms                                                      | 256 ms: 1.03x slower                                                        |
| pickle_dict                | 17.8 us                                                     | 18.4 us: 1.04x slower                                                       |
| gc_traversal               | 1.46 ms                                                     | 1.51 ms: 1.04x slower                                                       |
| unpickle                   | 7.82 us                                                     | 8.12 us: 1.04x slower                                                       |
| xml_etree_generate         | 52.2 ms                                                     | 54.3 ms: 1.04x slower                                                       |
| regex_effbot               | 1.52 ms                                                     | 1.58 ms: 1.04x slower                                                       |
| json_loads                 | 12.9 us                                                     | 13.5 us: 1.04x slower                                                       |
| bench_mp_pool              | 61.1 ms                                                     | 63.9 ms: 1.05x slower                                                       |
| create_gc_cycles           | 706 us                                                      | 739 us: 1.05x slower                                                        |
| scimark_sor                | 76.4 ms                                                     | 80.9 ms: 1.06x slower                                                       |
| tornado_http               | 89.9 ms                                                     | 95.6 ms: 1.06x slower                                                       |
| pycparser                  | 705 ms                                                      | 751 ms: 1.06x slower                                                        |
| regex_v8                   | 13.7 ms                                                     | 14.6 ms: 1.07x slower                                                       |
| pickle_list                | 2.68 us                                                     | 2.86 us: 1.07x slower                                                       |
| coverage                   | 43.0 ms                                                     | 46.0 ms: 1.07x slower                                                       |
| pickle                     | 6.53 us                                                     | 7.03 us: 1.08x slower                                                       |
| python_startup             | 18.8 ms                                                     | 20.3 ms: 1.08x slower                                                       |
| nbody                      | 69.3 ms                                                     | 75.5 ms: 1.09x slower                                                       |
| pathlib                    | 69.4 ms                                                     | 79.8 ms: 1.15x slower                                                       |
| python_startup_no_site     | 15.5 ms                                                     | 18.1 ms: 1.17x slower                                                       |
| telco                      | 3.93 ms                                                     | 4.66 ms: 1.19x slower                                                       |
| mypy2                      | 226 ms                                                      | 286 ms: 1.26x slower                                                        |
| async_generators           | 181 ms                                                      | 229 ms: 1.27x slower                                                        |
| Geometric mean             | (ref)                                                       | 1.07x faster                                                                |

Benchmark hidden because not significant (5): json, asyncio_tcp_ssl, bench_thread_pool, xml_etree_iterparse, dask
Ignored benchmarks (10) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift


# HPT report

- Reliability score: 99.99% likely to be faster
- 90% likely to have a speedup of 1.03x
- 95% likely to have a speedup of 1.03x
- 99% likely to have a speedup of 1.02x
