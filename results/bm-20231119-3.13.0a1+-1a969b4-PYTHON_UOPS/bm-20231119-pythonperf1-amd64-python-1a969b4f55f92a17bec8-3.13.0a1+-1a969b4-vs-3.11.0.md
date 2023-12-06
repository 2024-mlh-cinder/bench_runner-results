
# Results vs. 3.11.0

- fork: python
- ref: 1a969b4f55f92a17bec8
- machine: windows-amd64
- commit hash: 1a969b4
- commit date: 2023-11-19
- overall geometric mean: 1.01x faster \*
- HPT reliability: 54.50%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231119-pythonperf1-amd64-python-1a969b4f55f92a17bec8-3.13.0a1+-1a969b4 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| 2to3           | 207 ms                                                      | 226 ms: 1.09x slower                                                        |
| chameleon      | 5.35 ms                                                     | 5.10 ms: 1.05x faster                                                       |
| docutils       | 1.59 sec                                                    | 1.60 sec: 1.01x slower                                                      |
| Geometric mean | (ref)                                                       | 1.01x slower                                                                |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231119-pythonperf1-amd64-python-1a969b4f55f92a17bec8-3.13.0a1+-1a969b4 |
|----------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| async_tree_none            | 314 ms                                                      | 280 ms: 1.12x faster                                                        |
| async_tree_cpu_io_mixed    | 495 ms                                                      | 466 ms: 1.06x faster                                                        |
| async_tree_memoization     | 367 ms                                                      | 354 ms: 1.04x faster                                                        |
| async_tree_io_tg           | 795 ms                                                      | 778 ms: 1.02x faster                                                        |
| async_tree_none_tg         | 299 ms                                                      | 293 ms: 1.02x faster                                                        |
| async_tree_cpu_io_mixed_tg | 503 ms                                                      | 494 ms: 1.02x faster                                                        |
| Geometric mean             | (ref)                                                       | 1.04x faster                                                                |

Benchmark hidden because not significant (2): async_tree_io, async_tree_memoization_tg

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231119-pythonperf1-amd64-python-1a969b4f55f92a17bec8-3.13.0a1+-1a969b4 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| pidigits       | 149 ms                                                      | 147 ms: 1.01x faster                                                        |
| float          | 54.4 ms                                                     | 62.2 ms: 1.14x slower                                                       |
| nbody          | 69.3 ms                                                     | 85.7 ms: 1.24x slower                                                       |
| Geometric mean | (ref)                                                       | 1.12x slower                                                                |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231119-pythonperf1-amd64-python-1a969b4f55f92a17bec8-3.13.0a1+-1a969b4 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_dna      | 121 ms                                                      | 120 ms: 1.01x faster                                                        |
| regex_compile  | 90.8 ms                                                     | 94.4 ms: 1.04x slower                                                       |
| regex_effbot   | 1.52 ms                                                     | 1.59 ms: 1.05x slower                                                       |
| regex_v8       | 13.7 ms                                                     | 18.9 ms: 1.38x slower                                                       |
| Geometric mean | (ref)                                                       | 1.10x slower                                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231119-pythonperf1-amd64-python-1a969b4f55f92a17bec8-3.13.0a1+-1a969b4 |
|----------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| json_dumps           | 7.90 ms                                                     | 5.76 ms: 1.37x faster                                                       |
| pickle_pure_python   | 207 us                                                      | 187 us: 1.11x faster                                                        |
| unpickle_pure_python | 152 us                                                      | 147 us: 1.04x faster                                                        |
| xml_etree_parse      | 94.5 ms                                                     | 91.3 ms: 1.04x faster                                                       |
| unpickle_list        | 2.57 us                                                     | 2.62 us: 1.02x slower                                                       |
| pickle_dict          | 17.8 us                                                     | 18.4 us: 1.03x slower                                                       |
| xml_etree_process    | 37.0 ms                                                     | 38.4 ms: 1.04x slower                                                       |
| xml_etree_iterparse  | 63.0 ms                                                     | 65.4 ms: 1.04x slower                                                       |
| json_loads           | 12.9 us                                                     | 13.5 us: 1.05x slower                                                       |
| pickle               | 6.53 us                                                     | 6.87 us: 1.05x slower                                                       |
| xml_etree_generate   | 52.2 ms                                                     | 55.4 ms: 1.06x slower                                                       |
| unpickle             | 7.82 us                                                     | 8.42 us: 1.08x slower                                                       |
| tomli_loads          | 1.42 sec                                                    | 1.53 sec: 1.08x slower                                                      |
| pickle_list          | 2.68 us                                                     | 3.12 us: 1.17x slower                                                       |
| Geometric mean       | (ref)                                                       | 1.01x slower                                                                |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231119-pythonperf1-amd64-python-1a969b4f55f92a17bec8-3.13.0a1+-1a969b4 |
|------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| python_startup         | 18.8 ms                                                     | 20.1 ms: 1.07x slower                                                       |
| python_startup_no_site | 15.5 ms                                                     | 18.5 ms: 1.20x slower                                                       |
| Geometric mean         | (ref)                                                       | 1.13x slower                                                                |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231119-pythonperf1-amd64-python-1a969b4f55f92a17bec8-3.13.0a1+-1a969b4 |
|-----------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| mako      | 7.55 ms                                                     | 8.46 ms: 1.12x slower                                                       |

All benchmarks:
===============

| Benchmark                  | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231119-pythonperf1-amd64-python-1a969b4f55f92a17bec8-3.13.0a1+-1a969b4 |
|----------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| typing_runtime_protocols   | 320 us                                                      | 82.7 us: 3.87x faster                                                       |
| generators                 | 34.0 ms                                                     | 21.7 ms: 1.56x faster                                                       |
| json_dumps                 | 7.90 ms                                                     | 5.76 ms: 1.37x faster                                                       |
| asyncio_tcp                | 614 ms                                                      | 473 ms: 1.30x faster                                                        |
| logging_silent             | 70.7 ns                                                     | 58.4 ns: 1.21x faster                                                       |
| richards_super             | 37.9 ms                                                     | 31.4 ms: 1.21x faster                                                       |
| unpack_sequence            | 47.0 ns                                                     | 39.1 ns: 1.20x faster                                                       |
| sqlglot_parse              | 939 us                                                      | 805 us: 1.17x faster                                                        |
| asyncio_tcp_ssl            | 2.02 sec                                                    | 1.76 sec: 1.15x faster                                                      |
| sympy_sum                  | 100.0 ms                                                    | 86.7 ms: 1.15x faster                                                       |
| mdp                        | 1.73 sec                                                    | 1.52 sec: 1.14x faster                                                      |
| raytrace                   | 211 ms                                                      | 187 ms: 1.13x faster                                                        |
| sqlite_synth               | 1.79 us                                                     | 1.60 us: 1.12x faster                                                       |
| async_tree_none            | 314 ms                                                      | 280 ms: 1.12x faster                                                        |
| sqlglot_transpile          | 1.15 ms                                                     | 1.03 ms: 1.11x faster                                                       |
| pickle_pure_python         | 207 us                                                      | 187 us: 1.11x faster                                                        |
| spectral_norm              | 69.9 ms                                                     | 63.3 ms: 1.10x faster                                                       |
| richards                   | 30.8 ms                                                     | 28.2 ms: 1.09x faster                                                       |
| sympy_str                  | 184 ms                                                      | 169 ms: 1.09x faster                                                        |
| deepcopy                   | 242 us                                                      | 226 us: 1.07x faster                                                        |
| async_tree_cpu_io_mixed    | 495 ms                                                      | 466 ms: 1.06x faster                                                        |
| sqlglot_normalize          | 191 ms                                                      | 181 ms: 1.06x faster                                                        |
| coroutines                 | 14.7 ms                                                     | 13.9 ms: 1.05x faster                                                       |
| chameleon                  | 5.35 ms                                                     | 5.10 ms: 1.05x faster                                                       |
| deepcopy_reduce            | 2.07 us                                                     | 1.99 us: 1.04x faster                                                       |
| sympy_expand               | 299 ms                                                      | 288 ms: 1.04x faster                                                        |
| comprehensions             | 15.6 us                                                     | 15.0 us: 1.04x faster                                                       |
| unpickle_pure_python       | 152 us                                                      | 147 us: 1.04x faster                                                        |
| xml_etree_parse            | 94.5 ms                                                     | 91.3 ms: 1.04x faster                                                       |
| async_tree_memoization     | 367 ms                                                      | 354 ms: 1.04x faster                                                        |
| deepcopy_memo              | 25.5 us                                                     | 24.6 us: 1.03x faster                                                       |
| logging_format             | 7.06 us                                                     | 6.83 us: 1.03x faster                                                       |
| dulwich_log                | 44.1 ms                                                     | 42.8 ms: 1.03x faster                                                       |
| sqlglot_optimize           | 35.1 ms                                                     | 34.3 ms: 1.02x faster                                                       |
| scimark_lu                 | 62.3 ms                                                     | 60.9 ms: 1.02x faster                                                       |
| async_tree_io_tg           | 795 ms                                                      | 778 ms: 1.02x faster                                                        |
| async_tree_none_tg         | 299 ms                                                      | 293 ms: 1.02x faster                                                        |
| async_tree_cpu_io_mixed_tg | 503 ms                                                      | 494 ms: 1.02x faster                                                        |
| dask                       | 262 ms                                                      | 258 ms: 1.02x faster                                                        |
| sympy_integrate            | 13.7 ms                                                     | 13.5 ms: 1.02x faster                                                       |
| pycparser                  | 705 ms                                                      | 696 ms: 1.01x faster                                                        |
| pidigits                   | 149 ms                                                      | 147 ms: 1.01x faster                                                        |
| regex_dna                  | 121 ms                                                      | 120 ms: 1.01x faster                                                        |
| docutils                   | 1.59 sec                                                    | 1.60 sec: 1.01x slower                                                      |
| go                         | 98.8 ms                                                     | 99.8 ms: 1.01x slower                                                       |
| chaos                      | 46.8 ms                                                     | 47.7 ms: 1.02x slower                                                       |
| unpickle_list              | 2.57 us                                                     | 2.62 us: 1.02x slower                                                       |
| pickle_dict                | 17.8 us                                                     | 18.4 us: 1.03x slower                                                       |
| gc_traversal               | 1.46 ms                                                     | 1.51 ms: 1.04x slower                                                       |
| xml_etree_process          | 37.0 ms                                                     | 38.4 ms: 1.04x slower                                                       |
| coverage                   | 43.0 ms                                                     | 44.6 ms: 1.04x slower                                                       |
| xml_etree_iterparse        | 63.0 ms                                                     | 65.4 ms: 1.04x slower                                                       |
| create_gc_cycles           | 706 us                                                      | 733 us: 1.04x slower                                                        |
| regex_compile              | 90.8 ms                                                     | 94.4 ms: 1.04x slower                                                       |
| json_loads                 | 12.9 us                                                     | 13.5 us: 1.05x slower                                                       |
| regex_effbot               | 1.52 ms                                                     | 1.59 ms: 1.05x slower                                                       |
| pprint_safe_repr           | 519 ms                                                      | 545 ms: 1.05x slower                                                        |
| pickle                     | 6.53 us                                                     | 6.87 us: 1.05x slower                                                       |
| meteor_contest             | 75.0 ms                                                     | 79.0 ms: 1.05x slower                                                       |
| nqueens                    | 66.1 ms                                                     | 69.7 ms: 1.05x slower                                                       |
| pprint_pformat             | 1.06 sec                                                    | 1.13 sec: 1.06x slower                                                      |
| xml_etree_generate         | 52.2 ms                                                     | 55.4 ms: 1.06x slower                                                       |
| python_startup             | 18.8 ms                                                     | 20.1 ms: 1.07x slower                                                       |
| crypto_pyaes               | 48.2 ms                                                     | 51.6 ms: 1.07x slower                                                       |
| unpickle                   | 7.82 us                                                     | 8.42 us: 1.08x slower                                                       |
| tomli_loads                | 1.42 sec                                                    | 1.53 sec: 1.08x slower                                                      |
| pathlib                    | 69.4 ms                                                     | 75.4 ms: 1.09x slower                                                       |
| 2to3                       | 207 ms                                                      | 226 ms: 1.09x slower                                                        |
| bench_mp_pool              | 61.1 ms                                                     | 66.7 ms: 1.09x slower                                                       |
| pyflate                    | 305 ms                                                      | 336 ms: 1.10x slower                                                        |
| scimark_sor                | 76.4 ms                                                     | 85.0 ms: 1.11x slower                                                       |
| mako                       | 7.55 ms                                                     | 8.46 ms: 1.12x slower                                                       |
| deltablue                  | 2.63 ms                                                     | 2.96 ms: 1.13x slower                                                       |
| scimark_monte_carlo        | 44.6 ms                                                     | 50.3 ms: 1.13x slower                                                       |
| float                      | 54.4 ms                                                     | 62.2 ms: 1.14x slower                                                       |
| fannkuch                   | 248 ms                                                      | 284 ms: 1.15x slower                                                        |
| pickle_list                | 2.68 us                                                     | 3.12 us: 1.17x slower                                                       |
| python_startup_no_site     | 15.5 ms                                                     | 18.5 ms: 1.20x slower                                                       |
| nbody                      | 69.3 ms                                                     | 85.7 ms: 1.24x slower                                                       |
| hexiom                     | 4.51 ms                                                     | 5.63 ms: 1.25x slower                                                       |
| telco                      | 3.93 ms                                                     | 4.94 ms: 1.26x slower                                                       |
| scimark_fft                | 181 ms                                                      | 228 ms: 1.26x slower                                                        |
| mypy2                      | 226 ms                                                      | 294 ms: 1.30x slower                                                        |
| async_generators           | 181 ms                                                      | 236 ms: 1.30x slower                                                        |
| scimark_sparse_mat_mult    | 2.59 ms                                                     | 3.47 ms: 1.34x slower                                                       |
| regex_v8                   | 13.7 ms                                                     | 18.9 ms: 1.38x slower                                                       |
| Geometric mean             | (ref)                                                       | 1.01x faster                                                                |

Benchmark hidden because not significant (6): logging_simple, async_tree_io, async_tree_memoization_tg, tornado_http, json, bench_thread_pool
Ignored benchmarks (10) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift


# HPT report

- Reliability score: 54.50% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
