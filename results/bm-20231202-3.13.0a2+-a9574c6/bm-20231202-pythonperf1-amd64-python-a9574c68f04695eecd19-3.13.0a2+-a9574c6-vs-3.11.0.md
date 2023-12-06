
# Results vs. 3.11.0

- fork: python
- ref: a9574c68f04695eecd19
- machine: windows-amd64
- commit hash: a9574c6
- commit date: 2023-12-02
- overall geometric mean: 1.03x faster \*
- HPT reliability: 97.38%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231202-pythonperf1-amd64-python-a9574c68f04695eecd19-3.13.0a2+-a9574c6 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| 2to3           | 207 ms                                                      | 217 ms: 1.05x slower                                                        |
| chameleon      | 5.35 ms                                                     | 5.17 ms: 1.04x faster                                                       |
| tornado_http   | 89.9 ms                                                     | 88.0 ms: 1.02x faster                                                       |
| Geometric mean | (ref)                                                       | 1.00x faster                                                                |

Benchmark hidden because not significant (1): docutils

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231202-pythonperf1-amd64-python-a9574c68f04695eecd19-3.13.0a2+-a9574c6 |
|----------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| async_tree_none            | 314 ms                                                      | 270 ms: 1.16x faster                                                        |
| async_tree_cpu_io_mixed    | 495 ms                                                      | 459 ms: 1.08x faster                                                        |
| async_tree_memoization     | 367 ms                                                      | 346 ms: 1.06x faster                                                        |
| async_tree_none_tg         | 299 ms                                                      | 287 ms: 1.04x faster                                                        |
| async_tree_cpu_io_mixed_tg | 503 ms                                                      | 487 ms: 1.03x faster                                                        |
| async_tree_memoization_tg  | 380 ms                                                      | 369 ms: 1.03x faster                                                        |
| async_tree_io_tg           | 795 ms                                                      | 778 ms: 1.02x faster                                                        |
| async_tree_io              | 753 ms                                                      | 738 ms: 1.02x faster                                                        |
| Geometric mean             | (ref)                                                       | 1.05x faster                                                                |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231202-pythonperf1-amd64-python-a9574c68f04695eecd19-3.13.0a2+-a9574c6 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| pidigits       | 149 ms                                                      | 147 ms: 1.01x faster                                                        |
| nbody          | 69.3 ms                                                     | 74.2 ms: 1.07x slower                                                       |
| Geometric mean | (ref)                                                       | 1.02x slower                                                                |

Benchmark hidden because not significant (1): float

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231202-pythonperf1-amd64-python-a9574c68f04695eecd19-3.13.0a2+-a9574c6 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_compile  | 90.8 ms                                                     | 86.5 ms: 1.05x faster                                                       |
| regex_dna      | 121 ms                                                      | 121 ms: 1.01x faster                                                        |
| regex_effbot   | 1.52 ms                                                     | 1.59 ms: 1.05x slower                                                       |
| regex_v8       | 13.7 ms                                                     | 15.4 ms: 1.12x slower                                                       |
| Geometric mean | (ref)                                                       | 1.03x slower                                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231202-pythonperf1-amd64-python-a9574c68f04695eecd19-3.13.0a2+-a9574c6 |
|----------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| json_dumps           | 7.90 ms                                                     | 5.74 ms: 1.38x faster                                                       |
| unpickle_pure_python | 152 us                                                      | 135 us: 1.13x faster                                                        |
| pickle_pure_python   | 207 us                                                      | 194 us: 1.07x faster                                                        |
| unpickle_list        | 2.57 us                                                     | 2.60 us: 1.01x slower                                                       |
| xml_etree_iterparse  | 63.0 ms                                                     | 64.8 ms: 1.03x slower                                                       |
| json_loads           | 12.9 us                                                     | 13.4 us: 1.04x slower                                                       |
| pickle_dict          | 17.8 us                                                     | 18.5 us: 1.04x slower                                                       |
| unpickle             | 7.82 us                                                     | 8.23 us: 1.05x slower                                                       |
| xml_etree_process    | 37.0 ms                                                     | 39.0 ms: 1.05x slower                                                       |
| pickle               | 6.53 us                                                     | 7.03 us: 1.08x slower                                                       |
| pickle_list          | 2.68 us                                                     | 2.88 us: 1.08x slower                                                       |
| tomli_loads          | 1.42 sec                                                    | 1.54 sec: 1.08x slower                                                      |
| xml_etree_generate   | 52.2 ms                                                     | 57.0 ms: 1.09x slower                                                       |
| Geometric mean       | (ref)                                                       | 1.00x slower                                                                |

Benchmark hidden because not significant (1): xml_etree_parse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231202-pythonperf1-amd64-python-a9574c68f04695eecd19-3.13.0a2+-a9574c6 |
|------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| python_startup         | 18.8 ms                                                     | 20.1 ms: 1.07x slower                                                       |
| python_startup_no_site | 15.5 ms                                                     | 18.0 ms: 1.16x slower                                                       |
| Geometric mean         | (ref)                                                       | 1.11x slower                                                                |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231202-pythonperf1-amd64-python-a9574c68f04695eecd19-3.13.0a2+-a9574c6 |
|-----------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| mako      | 7.55 ms                                                     | 6.93 ms: 1.09x faster                                                       |

All benchmarks:
===============

| Benchmark                  | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231202-pythonperf1-amd64-python-a9574c68f04695eecd19-3.13.0a2+-a9574c6 |
|----------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| typing_runtime_protocols   | 320 us                                                      | 79.2 us: 4.04x faster                                                       |
| generators                 | 34.0 ms                                                     | 23.1 ms: 1.47x faster                                                       |
| comprehensions             | 15.6 us                                                     | 11.1 us: 1.41x faster                                                       |
| json_dumps                 | 7.90 ms                                                     | 5.74 ms: 1.38x faster                                                       |
| asyncio_tcp                | 614 ms                                                      | 460 ms: 1.34x faster                                                        |
| raytrace                   | 211 ms                                                      | 172 ms: 1.23x faster                                                        |
| deltablue                  | 2.63 ms                                                     | 2.21 ms: 1.19x faster                                                       |
| sympy_sum                  | 100.0 ms                                                    | 85.2 ms: 1.17x faster                                                       |
| async_tree_none            | 314 ms                                                      | 270 ms: 1.16x faster                                                        |
| sqlite_synth               | 1.79 us                                                     | 1.58 us: 1.14x faster                                                       |
| sqlglot_parse              | 939 us                                                      | 829 us: 1.13x faster                                                        |
| chaos                      | 46.8 ms                                                     | 41.3 ms: 1.13x faster                                                       |
| logging_silent             | 70.7 ns                                                     | 62.5 ns: 1.13x faster                                                       |
| mdp                        | 1.73 sec                                                    | 1.53 sec: 1.13x faster                                                      |
| unpickle_pure_python       | 152 us                                                      | 135 us: 1.13x faster                                                        |
| sympy_str                  | 184 ms                                                      | 164 ms: 1.12x faster                                                        |
| richards_super             | 37.9 ms                                                     | 33.9 ms: 1.12x faster                                                       |
| unpack_sequence            | 47.0 ns                                                     | 42.4 ns: 1.11x faster                                                       |
| spectral_norm              | 69.9 ms                                                     | 63.2 ms: 1.11x faster                                                       |
| mako                       | 7.55 ms                                                     | 6.93 ms: 1.09x faster                                                       |
| asyncio_tcp_ssl            | 2.02 sec                                                    | 1.87 sec: 1.08x faster                                                      |
| sqlglot_transpile          | 1.15 ms                                                     | 1.06 ms: 1.08x faster                                                       |
| async_tree_cpu_io_mixed    | 495 ms                                                      | 459 ms: 1.08x faster                                                        |
| sympy_integrate            | 13.7 ms                                                     | 12.8 ms: 1.07x faster                                                       |
| pickle_pure_python         | 207 us                                                      | 194 us: 1.07x faster                                                        |
| go                         | 98.8 ms                                                     | 92.8 ms: 1.06x faster                                                       |
| hexiom                     | 4.51 ms                                                     | 4.24 ms: 1.06x faster                                                       |
| crypto_pyaes               | 48.2 ms                                                     | 45.3 ms: 1.06x faster                                                       |
| sympy_expand               | 299 ms                                                      | 281 ms: 1.06x faster                                                        |
| async_tree_memoization     | 367 ms                                                      | 346 ms: 1.06x faster                                                        |
| scimark_monte_carlo        | 44.6 ms                                                     | 42.3 ms: 1.05x faster                                                       |
| regex_compile              | 90.8 ms                                                     | 86.5 ms: 1.05x faster                                                       |
| async_tree_none_tg         | 299 ms                                                      | 287 ms: 1.04x faster                                                        |
| dulwich_log                | 44.1 ms                                                     | 42.4 ms: 1.04x faster                                                       |
| chameleon                  | 5.35 ms                                                     | 5.17 ms: 1.04x faster                                                       |
| scimark_lu                 | 62.3 ms                                                     | 60.3 ms: 1.03x faster                                                       |
| scimark_sparse_mat_mult    | 2.59 ms                                                     | 2.50 ms: 1.03x faster                                                       |
| deepcopy_memo              | 25.5 us                                                     | 24.7 us: 1.03x faster                                                       |
| async_tree_cpu_io_mixed_tg | 503 ms                                                      | 487 ms: 1.03x faster                                                        |
| nqueens                    | 66.1 ms                                                     | 64.2 ms: 1.03x faster                                                       |
| async_tree_memoization_tg  | 380 ms                                                      | 369 ms: 1.03x faster                                                        |
| tornado_http               | 89.9 ms                                                     | 88.0 ms: 1.02x faster                                                       |
| async_tree_io_tg           | 795 ms                                                      | 778 ms: 1.02x faster                                                        |
| async_tree_io              | 753 ms                                                      | 738 ms: 1.02x faster                                                        |
| richards                   | 30.8 ms                                                     | 30.3 ms: 1.02x faster                                                       |
| deepcopy                   | 242 us                                                      | 239 us: 1.02x faster                                                        |
| coroutines                 | 14.7 ms                                                     | 14.5 ms: 1.01x faster                                                       |
| logging_simple             | 6.60 us                                                     | 6.53 us: 1.01x faster                                                       |
| pidigits                   | 149 ms                                                      | 147 ms: 1.01x faster                                                        |
| sqlglot_normalize          | 191 ms                                                      | 190 ms: 1.01x faster                                                        |
| logging_format             | 7.06 us                                                     | 7.02 us: 1.01x faster                                                       |
| regex_dna                  | 121 ms                                                      | 121 ms: 1.01x faster                                                        |
| pprint_safe_repr           | 519 ms                                                      | 523 ms: 1.01x slower                                                        |
| deepcopy_reduce            | 2.07 us                                                     | 2.09 us: 1.01x slower                                                       |
| fannkuch                   | 248 ms                                                      | 251 ms: 1.01x slower                                                        |
| unpickle_list              | 2.57 us                                                     | 2.60 us: 1.01x slower                                                       |
| scimark_fft                | 181 ms                                                      | 186 ms: 1.03x slower                                                        |
| gc_traversal               | 1.46 ms                                                     | 1.49 ms: 1.03x slower                                                       |
| sqlglot_optimize           | 35.1 ms                                                     | 36.0 ms: 1.03x slower                                                       |
| xml_etree_iterparse        | 63.0 ms                                                     | 64.8 ms: 1.03x slower                                                       |
| json_loads                 | 12.9 us                                                     | 13.4 us: 1.04x slower                                                       |
| pickle_dict                | 17.8 us                                                     | 18.5 us: 1.04x slower                                                       |
| regex_effbot               | 1.52 ms                                                     | 1.59 ms: 1.05x slower                                                       |
| 2to3                       | 207 ms                                                      | 217 ms: 1.05x slower                                                        |
| unpickle                   | 7.82 us                                                     | 8.23 us: 1.05x slower                                                       |
| xml_etree_process          | 37.0 ms                                                     | 39.0 ms: 1.05x slower                                                       |
| create_gc_cycles           | 706 us                                                      | 744 us: 1.06x slower                                                        |
| bench_mp_pool              | 61.1 ms                                                     | 64.6 ms: 1.06x slower                                                       |
| python_startup             | 18.8 ms                                                     | 20.1 ms: 1.07x slower                                                       |
| nbody                      | 69.3 ms                                                     | 74.2 ms: 1.07x slower                                                       |
| pickle                     | 6.53 us                                                     | 7.03 us: 1.08x slower                                                       |
| pickle_list                | 2.68 us                                                     | 2.88 us: 1.08x slower                                                       |
| scimark_sor                | 76.4 ms                                                     | 82.5 ms: 1.08x slower                                                       |
| tomli_loads                | 1.42 sec                                                    | 1.54 sec: 1.08x slower                                                      |
| xml_etree_generate         | 52.2 ms                                                     | 57.0 ms: 1.09x slower                                                       |
| coverage                   | 43.0 ms                                                     | 47.3 ms: 1.10x slower                                                       |
| regex_v8                   | 13.7 ms                                                     | 15.4 ms: 1.12x slower                                                       |
| pathlib                    | 69.4 ms                                                     | 79.6 ms: 1.15x slower                                                       |
| python_startup_no_site     | 15.5 ms                                                     | 18.0 ms: 1.16x slower                                                       |
| pycparser                  | 705 ms                                                      | 851 ms: 1.21x slower                                                        |
| telco                      | 3.93 ms                                                     | 4.81 ms: 1.22x slower                                                       |
| async_generators           | 181 ms                                                      | 240 ms: 1.33x slower                                                        |
| mypy2                      | 226 ms                                                      | 426 ms: 1.88x slower                                                        |
| Geometric mean             | (ref)                                                       | 1.03x faster                                                                |

Benchmark hidden because not significant (9): xml_etree_parse, dask, pyflate, pprint_pformat, meteor_contest, float, docutils, json, bench_thread_pool
Ignored benchmarks (10) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift


# HPT report

- Reliability score: 97.38% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
