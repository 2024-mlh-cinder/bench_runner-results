
# Results vs. 3.11.0

- fork: python
- ref: ce6a533c4bf1afa3775d
- machine: windows-amd64
- commit hash: ce6a533
- commit date: 2023-11-12
- overall geometric mean: 1.01x faster \*
- HPT reliability: 69.52%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231112-pythonperf1-amd64-python-ce6a533c4bf1afa3775d-3.13.0a1+-ce6a533 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| 2to3           | 207 ms                                                      | 223 ms: 1.08x slower                                                        |
| chameleon      | 5.35 ms                                                     | 5.00 ms: 1.07x faster                                                       |
| docutils       | 1.59 sec                                                    | 1.60 sec: 1.01x slower                                                      |
| Geometric mean | (ref)                                                       | 1.00x slower                                                                |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231112-pythonperf1-amd64-python-ce6a533c4bf1afa3775d-3.13.0a1+-ce6a533 |
|----------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| async_tree_none            | 314 ms                                                      | 275 ms: 1.14x faster                                                        |
| async_tree_cpu_io_mixed    | 495 ms                                                      | 458 ms: 1.08x faster                                                        |
| async_tree_memoization     | 367 ms                                                      | 353 ms: 1.04x faster                                                        |
| async_tree_cpu_io_mixed_tg | 503 ms                                                      | 485 ms: 1.04x faster                                                        |
| async_tree_none_tg         | 299 ms                                                      | 291 ms: 1.03x faster                                                        |
| async_tree_io_tg           | 795 ms                                                      | 776 ms: 1.02x faster                                                        |
| async_tree_memoization_tg  | 380 ms                                                      | 372 ms: 1.02x faster                                                        |
| Geometric mean             | (ref)                                                       | 1.05x faster                                                                |

Benchmark hidden because not significant (1): async_tree_io

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231112-pythonperf1-amd64-python-ce6a533c4bf1afa3775d-3.13.0a1+-ce6a533 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| pidigits       | 149 ms                                                      | 147 ms: 1.01x faster                                                        |
| float          | 54.4 ms                                                     | 61.9 ms: 1.14x slower                                                       |
| nbody          | 69.3 ms                                                     | 85.1 ms: 1.23x slower                                                       |
| Geometric mean | (ref)                                                       | 1.11x slower                                                                |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231112-pythonperf1-amd64-python-ce6a533c4bf1afa3775d-3.13.0a1+-ce6a533 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_dna      | 121 ms                                                      | 123 ms: 1.02x slower                                                        |
| regex_compile  | 90.8 ms                                                     | 93.6 ms: 1.03x slower                                                       |
| regex_effbot   | 1.52 ms                                                     | 1.62 ms: 1.07x slower                                                       |
| regex_v8       | 13.7 ms                                                     | 15.7 ms: 1.15x slower                                                       |
| Geometric mean | (ref)                                                       | 1.06x slower                                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231112-pythonperf1-amd64-python-ce6a533c4bf1afa3775d-3.13.0a1+-ce6a533 |
|----------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| json_dumps           | 7.90 ms                                                     | 5.68 ms: 1.39x faster                                                       |
| pickle_pure_python   | 207 us                                                      | 181 us: 1.15x faster                                                        |
| unpickle_pure_python | 152 us                                                      | 144 us: 1.06x faster                                                        |
| xml_etree_parse      | 94.5 ms                                                     | 95.9 ms: 1.01x slower                                                       |
| json_loads           | 12.9 us                                                     | 13.3 us: 1.04x slower                                                       |
| pickle_dict          | 17.8 us                                                     | 18.4 us: 1.04x slower                                                       |
| xml_etree_generate   | 52.2 ms                                                     | 54.4 ms: 1.04x slower                                                       |
| unpickle_list        | 2.57 us                                                     | 2.70 us: 1.05x slower                                                       |
| unpickle             | 7.82 us                                                     | 8.25 us: 1.05x slower                                                       |
| pickle_list          | 2.68 us                                                     | 2.87 us: 1.07x slower                                                       |
| pickle               | 6.53 us                                                     | 7.03 us: 1.08x slower                                                       |
| xml_etree_iterparse  | 63.0 ms                                                     | 69.0 ms: 1.10x slower                                                       |
| tomli_loads          | 1.42 sec                                                    | 1.72 sec: 1.21x slower                                                      |
| Geometric mean       | (ref)                                                       | 1.01x slower                                                                |

Benchmark hidden because not significant (1): xml_etree_process

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231112-pythonperf1-amd64-python-ce6a533c4bf1afa3775d-3.13.0a1+-ce6a533 |
|------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| python_startup         | 18.8 ms                                                     | 19.6 ms: 1.04x slower                                                       |
| python_startup_no_site | 15.5 ms                                                     | 17.9 ms: 1.15x slower                                                       |
| Geometric mean         | (ref)                                                       | 1.10x slower                                                                |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231112-pythonperf1-amd64-python-ce6a533c4bf1afa3775d-3.13.0a1+-ce6a533 |
|-----------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| mako      | 7.55 ms                                                     | 8.46 ms: 1.12x slower                                                       |

All benchmarks:
===============

| Benchmark                  | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231112-pythonperf1-amd64-python-ce6a533c4bf1afa3775d-3.13.0a1+-ce6a533 |
|----------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| typing_runtime_protocols   | 320 us                                                      | 78.2 us: 4.09x faster                                                       |
| generators                 | 34.0 ms                                                     | 20.8 ms: 1.63x faster                                                       |
| json_dumps                 | 7.90 ms                                                     | 5.68 ms: 1.39x faster                                                       |
| asyncio_tcp                | 614 ms                                                      | 496 ms: 1.24x faster                                                        |
| logging_silent             | 70.7 ns                                                     | 57.4 ns: 1.23x faster                                                       |
| raytrace                   | 211 ms                                                      | 176 ms: 1.20x faster                                                        |
| spectral_norm              | 69.9 ms                                                     | 58.5 ms: 1.19x faster                                                       |
| sqlglot_parse              | 939 us                                                      | 788 us: 1.19x faster                                                        |
| richards_super             | 37.9 ms                                                     | 31.9 ms: 1.19x faster                                                       |
| unpack_sequence            | 47.0 ns                                                     | 40.1 ns: 1.17x faster                                                       |
| sympy_sum                  | 100.0 ms                                                    | 85.5 ms: 1.17x faster                                                       |
| mdp                        | 1.73 sec                                                    | 1.50 sec: 1.15x faster                                                      |
| pickle_pure_python         | 207 us                                                      | 181 us: 1.15x faster                                                        |
| async_tree_none            | 314 ms                                                      | 275 ms: 1.14x faster                                                        |
| sqlite_synth               | 1.79 us                                                     | 1.58 us: 1.14x faster                                                       |
| sqlglot_transpile          | 1.15 ms                                                     | 1.01 ms: 1.14x faster                                                       |
| sympy_str                  | 184 ms                                                      | 168 ms: 1.09x faster                                                        |
| coroutines                 | 14.7 ms                                                     | 13.4 ms: 1.09x faster                                                       |
| deepcopy                   | 242 us                                                      | 224 us: 1.08x faster                                                        |
| async_tree_cpu_io_mixed    | 495 ms                                                      | 458 ms: 1.08x faster                                                        |
| richards                   | 30.8 ms                                                     | 28.5 ms: 1.08x faster                                                       |
| scimark_lu                 | 62.3 ms                                                     | 57.9 ms: 1.08x faster                                                       |
| sqlglot_normalize          | 191 ms                                                      | 178 ms: 1.07x faster                                                        |
| chameleon                  | 5.35 ms                                                     | 5.00 ms: 1.07x faster                                                       |
| unpickle_pure_python       | 152 us                                                      | 144 us: 1.06x faster                                                        |
| deepcopy_memo              | 25.5 us                                                     | 24.1 us: 1.06x faster                                                       |
| deepcopy_reduce            | 2.07 us                                                     | 1.98 us: 1.05x faster                                                       |
| sympy_expand               | 299 ms                                                      | 286 ms: 1.05x faster                                                        |
| async_tree_memoization     | 367 ms                                                      | 353 ms: 1.04x faster                                                        |
| sqlglot_optimize           | 35.1 ms                                                     | 33.7 ms: 1.04x faster                                                       |
| async_tree_cpu_io_mixed_tg | 503 ms                                                      | 485 ms: 1.04x faster                                                        |
| chaos                      | 46.8 ms                                                     | 45.3 ms: 1.03x faster                                                       |
| async_tree_none_tg         | 299 ms                                                      | 291 ms: 1.03x faster                                                        |
| dulwich_log                | 44.1 ms                                                     | 42.9 ms: 1.03x faster                                                       |
| async_tree_io_tg           | 795 ms                                                      | 776 ms: 1.02x faster                                                        |
| async_tree_memoization_tg  | 380 ms                                                      | 372 ms: 1.02x faster                                                        |
| sympy_integrate            | 13.7 ms                                                     | 13.5 ms: 1.01x faster                                                       |
| logging_simple             | 6.60 us                                                     | 6.53 us: 1.01x faster                                                       |
| logging_format             | 7.06 us                                                     | 6.98 us: 1.01x faster                                                       |
| pidigits                   | 149 ms                                                      | 147 ms: 1.01x faster                                                        |
| docutils                   | 1.59 sec                                                    | 1.60 sec: 1.01x slower                                                      |
| go                         | 98.8 ms                                                     | 99.8 ms: 1.01x slower                                                       |
| xml_etree_parse            | 94.5 ms                                                     | 95.9 ms: 1.01x slower                                                       |
| regex_dna                  | 121 ms                                                      | 123 ms: 1.02x slower                                                        |
| comprehensions             | 15.6 us                                                     | 16.0 us: 1.03x slower                                                       |
| regex_compile              | 90.8 ms                                                     | 93.6 ms: 1.03x slower                                                       |
| json_loads                 | 12.9 us                                                     | 13.3 us: 1.04x slower                                                       |
| pickle_dict                | 17.8 us                                                     | 18.4 us: 1.04x slower                                                       |
| gc_traversal               | 1.46 ms                                                     | 1.51 ms: 1.04x slower                                                       |
| bench_mp_pool              | 61.1 ms                                                     | 63.3 ms: 1.04x slower                                                       |
| xml_etree_generate         | 52.2 ms                                                     | 54.4 ms: 1.04x slower                                                       |
| python_startup             | 18.8 ms                                                     | 19.6 ms: 1.04x slower                                                       |
| create_gc_cycles           | 706 us                                                      | 737 us: 1.04x slower                                                        |
| pprint_safe_repr           | 519 ms                                                      | 543 ms: 1.05x slower                                                        |
| pprint_pformat             | 1.06 sec                                                    | 1.12 sec: 1.05x slower                                                      |
| scimark_sor                | 76.4 ms                                                     | 80.2 ms: 1.05x slower                                                       |
| crypto_pyaes               | 48.2 ms                                                     | 50.6 ms: 1.05x slower                                                       |
| unpickle_list              | 2.57 us                                                     | 2.70 us: 1.05x slower                                                       |
| unpickle                   | 7.82 us                                                     | 8.25 us: 1.05x slower                                                       |
| meteor_contest             | 75.0 ms                                                     | 79.5 ms: 1.06x slower                                                       |
| regex_effbot               | 1.52 ms                                                     | 1.62 ms: 1.07x slower                                                       |
| pickle_list                | 2.68 us                                                     | 2.87 us: 1.07x slower                                                       |
| pickle                     | 6.53 us                                                     | 7.03 us: 1.08x slower                                                       |
| scimark_monte_carlo        | 44.6 ms                                                     | 48.0 ms: 1.08x slower                                                       |
| 2to3                       | 207 ms                                                      | 223 ms: 1.08x slower                                                        |
| coverage                   | 43.0 ms                                                     | 47.0 ms: 1.09x slower                                                       |
| xml_etree_iterparse        | 63.0 ms                                                     | 69.0 ms: 1.10x slower                                                       |
| nqueens                    | 66.1 ms                                                     | 72.6 ms: 1.10x slower                                                       |
| pycparser                  | 705 ms                                                      | 776 ms: 1.10x slower                                                        |
| mako                       | 7.55 ms                                                     | 8.46 ms: 1.12x slower                                                       |
| pyflate                    | 305 ms                                                      | 344 ms: 1.13x slower                                                        |
| float                      | 54.4 ms                                                     | 61.9 ms: 1.14x slower                                                       |
| pathlib                    | 69.4 ms                                                     | 79.2 ms: 1.14x slower                                                       |
| deltablue                  | 2.63 ms                                                     | 3.00 ms: 1.14x slower                                                       |
| regex_v8                   | 13.7 ms                                                     | 15.7 ms: 1.15x slower                                                       |
| python_startup_no_site     | 15.5 ms                                                     | 17.9 ms: 1.15x slower                                                       |
| scimark_fft                | 181 ms                                                      | 217 ms: 1.20x slower                                                        |
| tomli_loads                | 1.42 sec                                                    | 1.72 sec: 1.21x slower                                                      |
| telco                      | 3.93 ms                                                     | 4.82 ms: 1.23x slower                                                       |
| nbody                      | 69.3 ms                                                     | 85.1 ms: 1.23x slower                                                       |
| fannkuch                   | 248 ms                                                      | 307 ms: 1.24x slower                                                        |
| mypy2                      | 226 ms                                                      | 295 ms: 1.30x slower                                                        |
| async_generators           | 181 ms                                                      | 237 ms: 1.31x slower                                                        |
| hexiom                     | 4.51 ms                                                     | 6.15 ms: 1.36x slower                                                       |
| scimark_sparse_mat_mult    | 2.59 ms                                                     | 3.64 ms: 1.41x slower                                                       |
| Geometric mean             | (ref)                                                       | 1.01x faster                                                                |

Benchmark hidden because not significant (6): asyncio_tcp_ssl, json, async_tree_io, xml_etree_process, tornado_http, bench_thread_pool
Ignored benchmarks (11) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, dask, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift


# HPT report

- Reliability score: 69.52% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
