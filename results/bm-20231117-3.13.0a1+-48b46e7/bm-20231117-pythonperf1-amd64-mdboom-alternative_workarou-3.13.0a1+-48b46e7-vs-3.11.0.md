
# Results vs. 3.11.0

- fork: mdboom
- ref: alternative_workarou
- machine: windows-amd64
- commit hash: 48b46e7
- commit date: 2023-11-17
- overall geometric mean: 1.10x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.05x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231117-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-48b46e7 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| chameleon      | 5.35 ms                                                     | 4.67 ms: 1.15x faster                                                       |
| docutils       | 1.59 sec                                                    | 1.53 sec: 1.04x faster                                                      |
| tornado_http   | 89.9 ms                                                     | 85.6 ms: 1.05x faster                                                       |
| Geometric mean | (ref)                                                       | 1.06x faster                                                                |

Benchmark hidden because not significant (1): 2to3

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231117-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-48b46e7 |
|----------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| async_tree_none            | 314 ms                                                      | 262 ms: 1.20x faster                                                        |
| async_tree_cpu_io_mixed    | 495 ms                                                      | 445 ms: 1.11x faster                                                        |
| async_tree_memoization     | 367 ms                                                      | 338 ms: 1.09x faster                                                        |
| async_tree_none_tg         | 299 ms                                                      | 277 ms: 1.08x faster                                                        |
| async_tree_memoization_tg  | 380 ms                                                      | 354 ms: 1.07x faster                                                        |
| async_tree_cpu_io_mixed_tg | 503 ms                                                      | 473 ms: 1.06x faster                                                        |
| async_tree_io_tg           | 795 ms                                                      | 756 ms: 1.05x faster                                                        |
| async_tree_io              | 753 ms                                                      | 724 ms: 1.04x faster                                                        |
| Geometric mean             | (ref)                                                       | 1.09x faster                                                                |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231117-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-48b46e7 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| float          | 54.4 ms                                                     | 51.0 ms: 1.07x faster                                                       |
| nbody          | 69.3 ms                                                     | 66.3 ms: 1.04x faster                                                       |
| pidigits       | 149 ms                                                      | 146 ms: 1.01x faster                                                        |
| Geometric mean | (ref)                                                       | 1.04x faster                                                                |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231117-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-48b46e7 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_compile  | 90.8 ms                                                     | 77.5 ms: 1.17x faster                                                       |
| regex_effbot   | 1.52 ms                                                     | 1.60 ms: 1.05x slower                                                       |
| regex_v8       | 13.7 ms                                                     | 15.3 ms: 1.12x slower                                                       |
| Geometric mean | (ref)                                                       | 1.00x slower                                                                |

Benchmark hidden because not significant (1): regex_dna

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231117-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-48b46e7 |
|----------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| json_dumps           | 7.90 ms                                                     | 5.48 ms: 1.44x faster                                                       |
| unpickle_pure_python | 152 us                                                      | 123 us: 1.24x faster                                                        |
| pickle_pure_python   | 207 us                                                      | 172 us: 1.20x faster                                                        |
| tomli_loads          | 1.42 sec                                                    | 1.37 sec: 1.04x faster                                                      |
| xml_etree_process    | 37.0 ms                                                     | 35.9 ms: 1.03x faster                                                       |
| xml_etree_parse      | 94.5 ms                                                     | 91.7 ms: 1.03x faster                                                       |
| unpickle_list        | 2.57 us                                                     | 2.63 us: 1.02x slower                                                       |
| pickle_dict          | 17.8 us                                                     | 18.5 us: 1.04x slower                                                       |
| json_loads           | 12.9 us                                                     | 13.5 us: 1.05x slower                                                       |
| pickle_list          | 2.68 us                                                     | 2.82 us: 1.05x slower                                                       |
| pickle               | 6.53 us                                                     | 6.95 us: 1.06x slower                                                       |
| unpickle             | 7.82 us                                                     | 8.45 us: 1.08x slower                                                       |
| Geometric mean       | (ref)                                                       | 1.04x faster                                                                |

Benchmark hidden because not significant (2): xml_etree_iterparse, xml_etree_generate

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231117-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-48b46e7 |
|------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| python_startup         | 18.8 ms                                                     | 19.5 ms: 1.04x slower                                                       |
| python_startup_no_site | 15.5 ms                                                     | 17.7 ms: 1.14x slower                                                       |
| Geometric mean         | (ref)                                                       | 1.09x slower                                                                |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231117-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-48b46e7 |
|-----------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| mako      | 7.55 ms                                                     | 6.36 ms: 1.19x faster                                                       |

All benchmarks:
===============

| Benchmark                  | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231117-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-48b46e7 |
|----------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| typing_runtime_protocols   | 320 us                                                      | 73.6 us: 4.35x faster                                                       |
| generators                 | 34.0 ms                                                     | 20.2 ms: 1.68x faster                                                       |
| comprehensions             | 15.6 us                                                     | 9.92 us: 1.57x faster                                                       |
| json_dumps                 | 7.90 ms                                                     | 5.48 ms: 1.44x faster                                                       |
| deltablue                  | 2.63 ms                                                     | 1.98 ms: 1.33x faster                                                       |
| richards_super             | 37.9 ms                                                     | 28.8 ms: 1.32x faster                                                       |
| raytrace                   | 211 ms                                                      | 161 ms: 1.31x faster                                                        |
| logging_silent             | 70.7 ns                                                     | 54.0 ns: 1.31x faster                                                       |
| asyncio_tcp                | 614 ms                                                      | 471 ms: 1.30x faster                                                        |
| sqlglot_parse              | 939 us                                                      | 741 us: 1.27x faster                                                        |
| unpack_sequence            | 47.0 ns                                                     | 37.6 ns: 1.25x faster                                                       |
| sympy_sum                  | 100.0 ms                                                    | 80.2 ms: 1.25x faster                                                       |
| unpickle_pure_python       | 152 us                                                      | 123 us: 1.24x faster                                                        |
| hexiom                     | 4.51 ms                                                     | 3.64 ms: 1.24x faster                                                       |
| chaos                      | 46.8 ms                                                     | 38.0 ms: 1.23x faster                                                       |
| mdp                        | 1.73 sec                                                    | 1.41 sec: 1.22x faster                                                      |
| pickle_pure_python         | 207 us                                                      | 172 us: 1.20x faster                                                        |
| sqlglot_transpile          | 1.15 ms                                                     | 955 us: 1.20x faster                                                        |
| go                         | 98.8 ms                                                     | 82.4 ms: 1.20x faster                                                       |
| async_tree_none            | 314 ms                                                      | 262 ms: 1.20x faster                                                        |
| richards                   | 30.8 ms                                                     | 25.7 ms: 1.20x faster                                                       |
| sympy_str                  | 184 ms                                                      | 154 ms: 1.20x faster                                                        |
| mako                       | 7.55 ms                                                     | 6.36 ms: 1.19x faster                                                       |
| nqueens                    | 66.1 ms                                                     | 56.1 ms: 1.18x faster                                                       |
| regex_compile              | 90.8 ms                                                     | 77.5 ms: 1.17x faster                                                       |
| crypto_pyaes               | 48.2 ms                                                     | 41.3 ms: 1.17x faster                                                       |
| scimark_lu                 | 62.3 ms                                                     | 53.5 ms: 1.17x faster                                                       |
| sqlite_synth               | 1.79 us                                                     | 1.56 us: 1.15x faster                                                       |
| chameleon                  | 5.35 ms                                                     | 4.67 ms: 1.15x faster                                                       |
| sympy_integrate            | 13.7 ms                                                     | 12.1 ms: 1.13x faster                                                       |
| spectral_norm              | 69.9 ms                                                     | 61.9 ms: 1.13x faster                                                       |
| sympy_expand               | 299 ms                                                      | 265 ms: 1.13x faster                                                        |
| deepcopy_memo              | 25.5 us                                                     | 22.6 us: 1.13x faster                                                       |
| sqlglot_normalize          | 191 ms                                                      | 170 ms: 1.12x faster                                                        |
| coroutines                 | 14.7 ms                                                     | 13.1 ms: 1.12x faster                                                       |
| deepcopy                   | 242 us                                                      | 218 us: 1.11x faster                                                        |
| async_tree_cpu_io_mixed    | 495 ms                                                      | 445 ms: 1.11x faster                                                        |
| scimark_monte_carlo        | 44.6 ms                                                     | 40.2 ms: 1.11x faster                                                       |
| dulwich_log                | 44.1 ms                                                     | 40.0 ms: 1.10x faster                                                       |
| pprint_pformat             | 1.06 sec                                                    | 966 ms: 1.10x faster                                                        |
| pprint_safe_repr           | 519 ms                                                      | 474 ms: 1.09x faster                                                        |
| pyflate                    | 305 ms                                                      | 279 ms: 1.09x faster                                                        |
| logging_simple             | 6.60 us                                                     | 6.04 us: 1.09x faster                                                       |
| logging_format             | 7.06 us                                                     | 6.48 us: 1.09x faster                                                       |
| scimark_sparse_mat_mult    | 2.59 ms                                                     | 2.38 ms: 1.09x faster                                                       |
| async_tree_memoization     | 367 ms                                                      | 338 ms: 1.09x faster                                                        |
| sqlglot_optimize           | 35.1 ms                                                     | 32.3 ms: 1.08x faster                                                       |
| deepcopy_reduce            | 2.07 us                                                     | 1.92 us: 1.08x faster                                                       |
| async_tree_none_tg         | 299 ms                                                      | 277 ms: 1.08x faster                                                        |
| async_tree_memoization_tg  | 380 ms                                                      | 354 ms: 1.07x faster                                                        |
| float                      | 54.4 ms                                                     | 51.0 ms: 1.07x faster                                                       |
| async_tree_cpu_io_mixed_tg | 503 ms                                                      | 473 ms: 1.06x faster                                                        |
| scimark_fft                | 181 ms                                                      | 171 ms: 1.06x faster                                                        |
| fannkuch                   | 248 ms                                                      | 234 ms: 1.06x faster                                                        |
| asyncio_tcp_ssl            | 2.02 sec                                                    | 1.91 sec: 1.06x faster                                                      |
| meteor_contest             | 75.0 ms                                                     | 70.9 ms: 1.06x faster                                                       |
| async_tree_io_tg           | 795 ms                                                      | 756 ms: 1.05x faster                                                        |
| tornado_http               | 89.9 ms                                                     | 85.6 ms: 1.05x faster                                                       |
| dask                       | 262 ms                                                      | 251 ms: 1.04x faster                                                        |
| nbody                      | 69.3 ms                                                     | 66.3 ms: 1.04x faster                                                       |
| async_tree_io              | 753 ms                                                      | 724 ms: 1.04x faster                                                        |
| docutils                   | 1.59 sec                                                    | 1.53 sec: 1.04x faster                                                      |
| tomli_loads                | 1.42 sec                                                    | 1.37 sec: 1.04x faster                                                      |
| xml_etree_process          | 37.0 ms                                                     | 35.9 ms: 1.03x faster                                                       |
| xml_etree_parse            | 94.5 ms                                                     | 91.7 ms: 1.03x faster                                                       |
| pidigits                   | 149 ms                                                      | 146 ms: 1.01x faster                                                        |
| scimark_sor                | 76.4 ms                                                     | 77.5 ms: 1.01x slower                                                       |
| unpickle_list              | 2.57 us                                                     | 2.63 us: 1.02x slower                                                       |
| gc_traversal               | 1.46 ms                                                     | 1.49 ms: 1.03x slower                                                       |
| bench_mp_pool              | 61.1 ms                                                     | 62.9 ms: 1.03x slower                                                       |
| python_startup             | 18.8 ms                                                     | 19.5 ms: 1.04x slower                                                       |
| pickle_dict                | 17.8 us                                                     | 18.5 us: 1.04x slower                                                       |
| json_loads                 | 12.9 us                                                     | 13.5 us: 1.05x slower                                                       |
| regex_effbot               | 1.52 ms                                                     | 1.60 ms: 1.05x slower                                                       |
| pickle_list                | 2.68 us                                                     | 2.82 us: 1.05x slower                                                       |
| create_gc_cycles           | 706 us                                                      | 745 us: 1.06x slower                                                        |
| coverage                   | 43.0 ms                                                     | 45.6 ms: 1.06x slower                                                       |
| pickle                     | 6.53 us                                                     | 6.95 us: 1.06x slower                                                       |
| pathlib                    | 69.4 ms                                                     | 74.6 ms: 1.08x slower                                                       |
| unpickle                   | 7.82 us                                                     | 8.45 us: 1.08x slower                                                       |
| regex_v8                   | 13.7 ms                                                     | 15.3 ms: 1.12x slower                                                       |
| python_startup_no_site     | 15.5 ms                                                     | 17.7 ms: 1.14x slower                                                       |
| telco                      | 3.93 ms                                                     | 4.57 ms: 1.16x slower                                                       |
| mypy2                      | 226 ms                                                      | 284 ms: 1.25x slower                                                        |
| async_generators           | 181 ms                                                      | 228 ms: 1.26x slower                                                        |
| Geometric mean             | (ref)                                                       | 1.10x faster                                                                |

Benchmark hidden because not significant (7): json, xml_etree_iterparse, bench_thread_pool, 2to3, regex_dna, xml_etree_generate, pycparser
Ignored benchmarks (10) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.06x
- 95% likely to have a speedup of 1.05x
- 99% likely to have a speedup of 1.05x
