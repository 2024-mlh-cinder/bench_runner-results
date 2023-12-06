
# Results vs. 3.11.0

- fork: mdboom
- ref: alternative_workarou
- machine: windows-amd64
- commit hash: badfdf2
- commit date: 2023-11-17
- overall geometric mean: 1.01x faster \*
- HPT reliability: 55.27%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231117-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-badfdf2 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| 2to3           | 207 ms                                                      | 223 ms: 1.08x slower                                                        |
| chameleon      | 5.35 ms                                                     | 5.13 ms: 1.04x faster                                                       |
| docutils       | 1.59 sec                                                    | 1.62 sec: 1.02x slower                                                      |
| tornado_http   | 89.9 ms                                                     | 88.9 ms: 1.01x faster                                                       |
| Geometric mean | (ref)                                                       | 1.01x slower                                                                |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231117-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-badfdf2 |
|----------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| async_tree_none            | 314 ms                                                      | 273 ms: 1.15x faster                                                        |
| async_tree_cpu_io_mixed    | 495 ms                                                      | 461 ms: 1.07x faster                                                        |
| async_tree_memoization     | 367 ms                                                      | 349 ms: 1.05x faster                                                        |
| async_tree_none_tg         | 299 ms                                                      | 289 ms: 1.03x faster                                                        |
| async_tree_cpu_io_mixed_tg | 503 ms                                                      | 489 ms: 1.03x faster                                                        |
| async_tree_memoization_tg  | 380 ms                                                      | 370 ms: 1.03x faster                                                        |
| async_tree_io_tg           | 795 ms                                                      | 777 ms: 1.02x faster                                                        |
| async_tree_io              | 753 ms                                                      | 739 ms: 1.02x faster                                                        |
| Geometric mean             | (ref)                                                       | 1.05x faster                                                                |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231117-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-badfdf2 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| pidigits       | 149 ms                                                      | 147 ms: 1.01x faster                                                        |
| float          | 54.4 ms                                                     | 61.0 ms: 1.12x slower                                                       |
| nbody          | 69.3 ms                                                     | 81.7 ms: 1.18x slower                                                       |
| Geometric mean | (ref)                                                       | 1.10x slower                                                                |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231117-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-badfdf2 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_dna      | 121 ms                                                      | 119 ms: 1.02x faster                                                        |
| regex_effbot   | 1.52 ms                                                     | 1.59 ms: 1.05x slower                                                       |
| regex_compile  | 90.8 ms                                                     | 96.9 ms: 1.07x slower                                                       |
| regex_v8       | 13.7 ms                                                     | 14.9 ms: 1.09x slower                                                       |
| Geometric mean | (ref)                                                       | 1.05x slower                                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231117-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-badfdf2 |
|----------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| json_dumps           | 7.90 ms                                                     | 5.65 ms: 1.40x faster                                                       |
| pickle_pure_python   | 207 us                                                      | 187 us: 1.11x faster                                                        |
| unpickle_pure_python | 152 us                                                      | 146 us: 1.04x faster                                                        |
| xml_etree_parse      | 94.5 ms                                                     | 91.8 ms: 1.03x faster                                                       |
| xml_etree_process    | 37.0 ms                                                     | 37.5 ms: 1.01x slower                                                       |
| pickle_dict          | 17.8 us                                                     | 18.3 us: 1.03x slower                                                       |
| unpickle_list        | 2.57 us                                                     | 2.65 us: 1.03x slower                                                       |
| json_loads           | 12.9 us                                                     | 13.5 us: 1.04x slower                                                       |
| xml_etree_generate   | 52.2 ms                                                     | 54.9 ms: 1.05x slower                                                       |
| xml_etree_iterparse  | 63.0 ms                                                     | 67.2 ms: 1.07x slower                                                       |
| unpickle             | 7.82 us                                                     | 8.41 us: 1.08x slower                                                       |
| pickle               | 6.53 us                                                     | 7.03 us: 1.08x slower                                                       |
| tomli_loads          | 1.42 sec                                                    | 1.62 sec: 1.14x slower                                                      |
| pickle_list          | 2.68 us                                                     | 3.27 us: 1.22x slower                                                       |
| Geometric mean       | (ref)                                                       | 1.01x slower                                                                |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231117-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-badfdf2 |
|------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| python_startup         | 18.8 ms                                                     | 19.6 ms: 1.04x slower                                                       |
| python_startup_no_site | 15.5 ms                                                     | 17.7 ms: 1.14x slower                                                       |
| Geometric mean         | (ref)                                                       | 1.09x slower                                                                |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231117-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-badfdf2 |
|-----------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| mako      | 7.55 ms                                                     | 7.99 ms: 1.06x slower                                                       |

All benchmarks:
===============

| Benchmark                  | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231117-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-badfdf2 |
|----------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| typing_runtime_protocols   | 320 us                                                      | 79.4 us: 4.03x faster                                                       |
| generators                 | 34.0 ms                                                     | 21.3 ms: 1.60x faster                                                       |
| json_dumps                 | 7.90 ms                                                     | 5.65 ms: 1.40x faster                                                       |
| asyncio_tcp                | 614 ms                                                      | 459 ms: 1.34x faster                                                        |
| unpack_sequence            | 47.0 ns                                                     | 37.7 ns: 1.24x faster                                                       |
| richards_super             | 37.9 ms                                                     | 31.7 ms: 1.19x faster                                                       |
| logging_silent             | 70.7 ns                                                     | 60.2 ns: 1.17x faster                                                       |
| sqlglot_parse              | 939 us                                                      | 812 us: 1.16x faster                                                        |
| sympy_sum                  | 100.0 ms                                                    | 87.1 ms: 1.15x faster                                                       |
| async_tree_none            | 314 ms                                                      | 273 ms: 1.15x faster                                                        |
| asyncio_tcp_ssl            | 2.02 sec                                                    | 1.80 sec: 1.13x faster                                                      |
| raytrace                   | 211 ms                                                      | 187 ms: 1.13x faster                                                        |
| sqlite_synth               | 1.79 us                                                     | 1.59 us: 1.13x faster                                                       |
| sqlglot_transpile          | 1.15 ms                                                     | 1.02 ms: 1.12x faster                                                       |
| pickle_pure_python         | 207 us                                                      | 187 us: 1.11x faster                                                        |
| spectral_norm              | 69.9 ms                                                     | 63.3 ms: 1.10x faster                                                       |
| mdp                        | 1.73 sec                                                    | 1.57 sec: 1.10x faster                                                      |
| coroutines                 | 14.7 ms                                                     | 13.4 ms: 1.09x faster                                                       |
| richards                   | 30.8 ms                                                     | 28.3 ms: 1.09x faster                                                       |
| deepcopy                   | 242 us                                                      | 224 us: 1.08x faster                                                        |
| async_tree_cpu_io_mixed    | 495 ms                                                      | 461 ms: 1.07x faster                                                        |
| sqlglot_normalize          | 191 ms                                                      | 178 ms: 1.07x faster                                                        |
| sympy_str                  | 184 ms                                                      | 172 ms: 1.07x faster                                                        |
| deepcopy_reduce            | 2.07 us                                                     | 1.96 us: 1.06x faster                                                       |
| async_tree_memoization     | 367 ms                                                      | 349 ms: 1.05x faster                                                        |
| unpickle_pure_python       | 152 us                                                      | 146 us: 1.04x faster                                                        |
| chameleon                  | 5.35 ms                                                     | 5.13 ms: 1.04x faster                                                       |
| async_tree_none_tg         | 299 ms                                                      | 289 ms: 1.03x faster                                                        |
| sqlglot_optimize           | 35.1 ms                                                     | 33.9 ms: 1.03x faster                                                       |
| deepcopy_memo              | 25.5 us                                                     | 24.7 us: 1.03x faster                                                       |
| xml_etree_parse            | 94.5 ms                                                     | 91.8 ms: 1.03x faster                                                       |
| async_tree_cpu_io_mixed_tg | 503 ms                                                      | 489 ms: 1.03x faster                                                        |
| async_tree_memoization_tg  | 380 ms                                                      | 370 ms: 1.03x faster                                                        |
| async_tree_io_tg           | 795 ms                                                      | 777 ms: 1.02x faster                                                        |
| async_tree_io              | 753 ms                                                      | 739 ms: 1.02x faster                                                        |
| sympy_integrate            | 13.7 ms                                                     | 13.5 ms: 1.02x faster                                                       |
| regex_dna                  | 121 ms                                                      | 119 ms: 1.02x faster                                                        |
| sympy_expand               | 299 ms                                                      | 294 ms: 1.02x faster                                                        |
| tornado_http               | 89.9 ms                                                     | 88.9 ms: 1.01x faster                                                       |
| logging_simple             | 6.60 us                                                     | 6.53 us: 1.01x faster                                                       |
| pidigits                   | 149 ms                                                      | 147 ms: 1.01x faster                                                        |
| scimark_lu                 | 62.3 ms                                                     | 61.9 ms: 1.01x faster                                                       |
| logging_format             | 7.06 us                                                     | 7.02 us: 1.01x faster                                                       |
| xml_etree_process          | 37.0 ms                                                     | 37.5 ms: 1.01x slower                                                       |
| docutils                   | 1.59 sec                                                    | 1.62 sec: 1.02x slower                                                      |
| dulwich_log                | 44.1 ms                                                     | 44.9 ms: 1.02x slower                                                       |
| gc_traversal               | 1.46 ms                                                     | 1.50 ms: 1.03x slower                                                       |
| pickle_dict                | 17.8 us                                                     | 18.3 us: 1.03x slower                                                       |
| pprint_pformat             | 1.06 sec                                                    | 1.10 sec: 1.03x slower                                                      |
| pprint_safe_repr           | 519 ms                                                      | 536 ms: 1.03x slower                                                        |
| unpickle_list              | 2.57 us                                                     | 2.65 us: 1.03x slower                                                       |
| bench_mp_pool              | 61.1 ms                                                     | 63.2 ms: 1.04x slower                                                       |
| create_gc_cycles           | 706 us                                                      | 733 us: 1.04x slower                                                        |
| python_startup             | 18.8 ms                                                     | 19.6 ms: 1.04x slower                                                       |
| json_loads                 | 12.9 us                                                     | 13.5 us: 1.04x slower                                                       |
| go                         | 98.8 ms                                                     | 103 ms: 1.05x slower                                                        |
| regex_effbot               | 1.52 ms                                                     | 1.59 ms: 1.05x slower                                                       |
| xml_etree_generate         | 52.2 ms                                                     | 54.9 ms: 1.05x slower                                                       |
| meteor_contest             | 75.0 ms                                                     | 79.2 ms: 1.06x slower                                                       |
| mako                       | 7.55 ms                                                     | 7.99 ms: 1.06x slower                                                       |
| xml_etree_iterparse        | 63.0 ms                                                     | 67.2 ms: 1.07x slower                                                       |
| regex_compile              | 90.8 ms                                                     | 96.9 ms: 1.07x slower                                                       |
| unpickle                   | 7.82 us                                                     | 8.41 us: 1.08x slower                                                       |
| 2to3                       | 207 ms                                                      | 223 ms: 1.08x slower                                                        |
| pickle                     | 6.53 us                                                     | 7.03 us: 1.08x slower                                                       |
| coverage                   | 43.0 ms                                                     | 46.3 ms: 1.08x slower                                                       |
| pathlib                    | 69.4 ms                                                     | 75.0 ms: 1.08x slower                                                       |
| crypto_pyaes               | 48.2 ms                                                     | 52.2 ms: 1.08x slower                                                       |
| scimark_monte_carlo        | 44.6 ms                                                     | 48.5 ms: 1.09x slower                                                       |
| regex_v8                   | 13.7 ms                                                     | 14.9 ms: 1.09x slower                                                       |
| nqueens                    | 66.1 ms                                                     | 72.2 ms: 1.09x slower                                                       |
| scimark_sor                | 76.4 ms                                                     | 83.6 ms: 1.09x slower                                                       |
| deltablue                  | 2.63 ms                                                     | 2.92 ms: 1.11x slower                                                       |
| pyflate                    | 305 ms                                                      | 339 ms: 1.11x slower                                                        |
| float                      | 54.4 ms                                                     | 61.0 ms: 1.12x slower                                                       |
| tomli_loads                | 1.42 sec                                                    | 1.62 sec: 1.14x slower                                                      |
| python_startup_no_site     | 15.5 ms                                                     | 17.7 ms: 1.14x slower                                                       |
| scimark_fft                | 181 ms                                                      | 212 ms: 1.17x slower                                                        |
| nbody                      | 69.3 ms                                                     | 81.7 ms: 1.18x slower                                                       |
| fannkuch                   | 248 ms                                                      | 298 ms: 1.20x slower                                                        |
| pickle_list                | 2.68 us                                                     | 3.27 us: 1.22x slower                                                       |
| telco                      | 3.93 ms                                                     | 4.85 ms: 1.23x slower                                                       |
| mypy2                      | 226 ms                                                      | 296 ms: 1.31x slower                                                        |
| async_generators           | 181 ms                                                      | 237 ms: 1.31x slower                                                        |
| hexiom                     | 4.51 ms                                                     | 6.11 ms: 1.35x slower                                                       |
| scimark_sparse_mat_mult    | 2.59 ms                                                     | 3.69 ms: 1.43x slower                                                       |
| Geometric mean             | (ref)                                                       | 1.01x faster                                                                |

Benchmark hidden because not significant (6): dask, comprehensions, chaos, bench_thread_pool, json, pycparser
Ignored benchmarks (10) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift


# HPT report

- Reliability score: 55.27% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
