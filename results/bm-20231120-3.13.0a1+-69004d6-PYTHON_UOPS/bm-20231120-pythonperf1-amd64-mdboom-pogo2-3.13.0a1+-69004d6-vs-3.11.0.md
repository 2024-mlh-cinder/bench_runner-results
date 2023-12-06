
# Results vs. 3.11.0

- fork: mdboom
- ref: pogo2
- machine: windows-amd64
- commit hash: 69004d6
- commit date: 2023-11-20
- overall geometric mean: 1.01x faster \*
- HPT reliability: 69.23%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-pythonperf1-amd64-mdboom-pogo2-3.13.0a1+-69004d6 |
|----------------|:-----------------------------------------------------------:|:------------------------------------------------------------:|
| 2to3           | 207 ms                                                      | 222 ms: 1.07x slower                                         |
| chameleon      | 5.35 ms                                                     | 4.92 ms: 1.09x faster                                        |
| docutils       | 1.59 sec                                                    | 1.61 sec: 1.02x slower                                       |
| tornado_http   | 89.9 ms                                                     | 101 ms: 1.12x slower                                         |
| Geometric mean | (ref)                                                       | 1.03x slower                                                 |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-pythonperf1-amd64-mdboom-pogo2-3.13.0a1+-69004d6 |
|----------------------------|:-----------------------------------------------------------:|:------------------------------------------------------------:|
| async_tree_none            | 314 ms                                                      | 272 ms: 1.15x faster                                         |
| async_tree_cpu_io_mixed    | 495 ms                                                      | 461 ms: 1.07x faster                                         |
| async_tree_memoization     | 367 ms                                                      | 350 ms: 1.05x faster                                         |
| async_tree_none_tg         | 299 ms                                                      | 287 ms: 1.04x faster                                         |
| async_tree_memoization_tg  | 380 ms                                                      | 369 ms: 1.03x faster                                         |
| async_tree_io              | 753 ms                                                      | 732 ms: 1.03x faster                                         |
| async_tree_cpu_io_mixed_tg | 503 ms                                                      | 489 ms: 1.03x faster                                         |
| async_tree_io_tg           | 795 ms                                                      | 780 ms: 1.02x faster                                         |
| Geometric mean             | (ref)                                                       | 1.05x faster                                                 |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-pythonperf1-amd64-mdboom-pogo2-3.13.0a1+-69004d6 |
|----------------|:-----------------------------------------------------------:|:------------------------------------------------------------:|
| float          | 54.4 ms                                                     | 58.2 ms: 1.07x slower                                        |
| nbody          | 69.3 ms                                                     | 85.2 ms: 1.23x slower                                        |
| Geometric mean | (ref)                                                       | 1.10x slower                                                 |

Benchmark hidden because not significant (1): pidigits

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-pythonperf1-amd64-mdboom-pogo2-3.13.0a1+-69004d6 |
|----------------|:-----------------------------------------------------------:|:------------------------------------------------------------:|
| regex_dna      | 121 ms                                                      | 122 ms: 1.00x slower                                         |
| regex_compile  | 90.8 ms                                                     | 91.7 ms: 1.01x slower                                        |
| regex_effbot   | 1.52 ms                                                     | 1.61 ms: 1.06x slower                                        |
| regex_v8       | 13.7 ms                                                     | 23.6 ms: 1.73x slower                                        |
| Geometric mean | (ref)                                                       | 1.17x slower                                                 |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-pythonperf1-amd64-mdboom-pogo2-3.13.0a1+-69004d6 |
|----------------------|:-----------------------------------------------------------:|:------------------------------------------------------------:|
| json_dumps           | 7.90 ms                                                     | 5.73 ms: 1.38x faster                                        |
| pickle_pure_python   | 207 us                                                      | 181 us: 1.14x faster                                         |
| unpickle_pure_python | 152 us                                                      | 139 us: 1.09x faster                                         |
| xml_etree_parse      | 94.5 ms                                                     | 92.2 ms: 1.03x faster                                        |
| unpickle_list        | 2.57 us                                                     | 2.64 us: 1.03x slower                                        |
| json_loads           | 12.9 us                                                     | 13.5 us: 1.04x slower                                        |
| unpickle             | 7.82 us                                                     | 8.20 us: 1.05x slower                                        |
| pickle_dict          | 17.8 us                                                     | 18.6 us: 1.05x slower                                        |
| xml_etree_process    | 37.0 ms                                                     | 38.9 ms: 1.05x slower                                        |
| tomli_loads          | 1.42 sec                                                    | 1.51 sec: 1.06x slower                                       |
| xml_etree_iterparse  | 63.0 ms                                                     | 67.3 ms: 1.07x slower                                        |
| xml_etree_generate   | 52.2 ms                                                     | 56.1 ms: 1.07x slower                                        |
| pickle               | 6.53 us                                                     | 7.02 us: 1.08x slower                                        |
| pickle_list          | 2.68 us                                                     | 3.31 us: 1.23x slower                                        |
| Geometric mean       | (ref)                                                       | 1.01x slower                                                 |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-pythonperf1-amd64-mdboom-pogo2-3.13.0a1+-69004d6 |
|------------------------|:-----------------------------------------------------------:|:------------------------------------------------------------:|
| python_startup         | 18.8 ms                                                     | 20.5 ms: 1.09x slower                                        |
| python_startup_no_site | 15.5 ms                                                     | 18.5 ms: 1.19x slower                                        |
| Geometric mean         | (ref)                                                       | 1.14x slower                                                 |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-pythonperf1-amd64-mdboom-pogo2-3.13.0a1+-69004d6 |
|-----------|:-----------------------------------------------------------:|:------------------------------------------------------------:|
| mako      | 7.55 ms                                                     | 7.65 ms: 1.01x slower                                        |

All benchmarks:
===============

| Benchmark                  | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-pythonperf1-amd64-mdboom-pogo2-3.13.0a1+-69004d6 |
|----------------------------|:-----------------------------------------------------------:|:------------------------------------------------------------:|
| typing_runtime_protocols   | 320 us                                                      | 80.3 us: 3.98x faster                                        |
| generators                 | 34.0 ms                                                     | 20.9 ms: 1.63x faster                                        |
| json_dumps                 | 7.90 ms                                                     | 5.73 ms: 1.38x faster                                        |
| logging_silent             | 70.7 ns                                                     | 56.9 ns: 1.24x faster                                        |
| richards_super             | 37.9 ms                                                     | 30.9 ms: 1.23x faster                                        |
| sqlglot_parse              | 939 us                                                      | 793 us: 1.18x faster                                         |
| unpack_sequence            | 47.0 ns                                                     | 39.7 ns: 1.18x faster                                        |
| raytrace                   | 211 ms                                                      | 179 ms: 1.18x faster                                         |
| comprehensions             | 15.6 us                                                     | 13.4 us: 1.16x faster                                        |
| async_tree_none            | 314 ms                                                      | 272 ms: 1.15x faster                                         |
| pickle_pure_python         | 207 us                                                      | 181 us: 1.14x faster                                         |
| asyncio_tcp                | 614 ms                                                      | 540 ms: 1.14x faster                                         |
| sqlite_synth               | 1.79 us                                                     | 1.58 us: 1.13x faster                                        |
| sqlglot_transpile          | 1.15 ms                                                     | 1.01 ms: 1.13x faster                                        |
| sympy_sum                  | 100.0 ms                                                    | 88.7 ms: 1.13x faster                                        |
| mdp                        | 1.73 sec                                                    | 1.54 sec: 1.12x faster                                       |
| richards                   | 30.8 ms                                                     | 27.9 ms: 1.10x faster                                        |
| asyncio_tcp_ssl            | 2.02 sec                                                    | 1.84 sec: 1.10x faster                                       |
| coroutines                 | 14.7 ms                                                     | 13.3 ms: 1.10x faster                                        |
| scimark_lu                 | 62.3 ms                                                     | 56.9 ms: 1.10x faster                                        |
| unpickle_pure_python       | 152 us                                                      | 139 us: 1.09x faster                                         |
| chameleon                  | 5.35 ms                                                     | 4.92 ms: 1.09x faster                                        |
| deepcopy_memo              | 25.5 us                                                     | 23.4 us: 1.09x faster                                        |
| async_tree_cpu_io_mixed    | 495 ms                                                      | 461 ms: 1.07x faster                                         |
| sympy_str                  | 184 ms                                                      | 172 ms: 1.07x faster                                         |
| deepcopy                   | 242 us                                                      | 229 us: 1.06x faster                                         |
| async_tree_memoization     | 367 ms                                                      | 350 ms: 1.05x faster                                         |
| async_tree_none_tg         | 299 ms                                                      | 287 ms: 1.04x faster                                         |
| deepcopy_reduce            | 2.07 us                                                     | 2.00 us: 1.04x faster                                        |
| go                         | 98.8 ms                                                     | 95.3 ms: 1.04x faster                                        |
| sympy_expand               | 299 ms                                                      | 289 ms: 1.04x faster                                         |
| sqlglot_normalize          | 191 ms                                                      | 185 ms: 1.03x faster                                         |
| async_tree_memoization_tg  | 380 ms                                                      | 369 ms: 1.03x faster                                         |
| async_tree_io              | 753 ms                                                      | 732 ms: 1.03x faster                                         |
| chaos                      | 46.8 ms                                                     | 45.5 ms: 1.03x faster                                        |
| async_tree_cpu_io_mixed_tg | 503 ms                                                      | 489 ms: 1.03x faster                                         |
| xml_etree_parse            | 94.5 ms                                                     | 92.2 ms: 1.03x faster                                        |
| sympy_integrate            | 13.7 ms                                                     | 13.4 ms: 1.02x faster                                        |
| logging_simple             | 6.60 us                                                     | 6.46 us: 1.02x faster                                        |
| logging_format             | 7.06 us                                                     | 6.91 us: 1.02x faster                                        |
| async_tree_io_tg           | 795 ms                                                      | 780 ms: 1.02x faster                                         |
| regex_dna                  | 121 ms                                                      | 122 ms: 1.00x slower                                         |
| sqlglot_optimize           | 35.1 ms                                                     | 35.3 ms: 1.01x slower                                        |
| regex_compile              | 90.8 ms                                                     | 91.7 ms: 1.01x slower                                        |
| mako                       | 7.55 ms                                                     | 7.65 ms: 1.01x slower                                        |
| docutils                   | 1.59 sec                                                    | 1.61 sec: 1.02x slower                                       |
| deltablue                  | 2.63 ms                                                     | 2.67 ms: 1.02x slower                                        |
| crypto_pyaes               | 48.2 ms                                                     | 49.4 ms: 1.03x slower                                        |
| pprint_safe_repr           | 519 ms                                                      | 534 ms: 1.03x slower                                         |
| pprint_pformat             | 1.06 sec                                                    | 1.10 sec: 1.03x slower                                       |
| unpickle_list              | 2.57 us                                                     | 2.64 us: 1.03x slower                                        |
| dask                       | 262 ms                                                      | 271 ms: 1.03x slower                                         |
| scimark_sor                | 76.4 ms                                                     | 78.9 ms: 1.03x slower                                        |
| gc_traversal               | 1.46 ms                                                     | 1.50 ms: 1.03x slower                                        |
| create_gc_cycles           | 706 us                                                      | 732 us: 1.04x slower                                         |
| json_loads                 | 12.9 us                                                     | 13.5 us: 1.04x slower                                        |
| unpickle                   | 7.82 us                                                     | 8.20 us: 1.05x slower                                        |
| pickle_dict                | 17.8 us                                                     | 18.6 us: 1.05x slower                                        |
| xml_etree_process          | 37.0 ms                                                     | 38.9 ms: 1.05x slower                                        |
| meteor_contest             | 75.0 ms                                                     | 79.0 ms: 1.05x slower                                        |
| tomli_loads                | 1.42 sec                                                    | 1.51 sec: 1.06x slower                                       |
| regex_effbot               | 1.52 ms                                                     | 1.61 ms: 1.06x slower                                        |
| xml_etree_iterparse        | 63.0 ms                                                     | 67.3 ms: 1.07x slower                                        |
| pyflate                    | 305 ms                                                      | 326 ms: 1.07x slower                                         |
| float                      | 54.4 ms                                                     | 58.2 ms: 1.07x slower                                        |
| 2to3                       | 207 ms                                                      | 222 ms: 1.07x slower                                         |
| xml_etree_generate         | 52.2 ms                                                     | 56.1 ms: 1.07x slower                                        |
| pickle                     | 6.53 us                                                     | 7.02 us: 1.08x slower                                        |
| coverage                   | 43.0 ms                                                     | 46.3 ms: 1.08x slower                                        |
| bench_mp_pool              | 61.1 ms                                                     | 66.0 ms: 1.08x slower                                        |
| python_startup             | 18.8 ms                                                     | 20.5 ms: 1.09x slower                                        |
| tornado_http               | 89.9 ms                                                     | 101 ms: 1.12x slower                                         |
| hexiom                     | 4.51 ms                                                     | 5.10 ms: 1.13x slower                                        |
| fannkuch                   | 248 ms                                                      | 282 ms: 1.13x slower                                         |
| scimark_monte_carlo        | 44.6 ms                                                     | 50.7 ms: 1.14x slower                                        |
| pathlib                    | 69.4 ms                                                     | 81.0 ms: 1.17x slower                                        |
| telco                      | 3.93 ms                                                     | 4.62 ms: 1.17x slower                                        |
| python_startup_no_site     | 15.5 ms                                                     | 18.5 ms: 1.19x slower                                        |
| scimark_fft                | 181 ms                                                      | 219 ms: 1.21x slower                                         |
| nbody                      | 69.3 ms                                                     | 85.2 ms: 1.23x slower                                        |
| pickle_list                | 2.68 us                                                     | 3.31 us: 1.23x slower                                        |
| spectral_norm              | 69.9 ms                                                     | 87.4 ms: 1.25x slower                                        |
| scimark_sparse_mat_mult    | 2.59 ms                                                     | 3.29 ms: 1.27x slower                                        |
| async_generators           | 181 ms                                                      | 235 ms: 1.30x slower                                         |
| mypy2                      | 226 ms                                                      | 295 ms: 1.30x slower                                         |
| regex_v8                   | 13.7 ms                                                     | 23.6 ms: 1.73x slower                                        |
| Geometric mean             | (ref)                                                       | 1.01x faster                                                 |

Benchmark hidden because not significant (6): json, nqueens, pidigits, dulwich_log, bench_thread_pool, pycparser
Ignored benchmarks (10) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift


# HPT report

- Reliability score: 69.23% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
