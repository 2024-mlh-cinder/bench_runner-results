
# Results vs. 3.11.0

- fork: python
- ref: a9574c68f04695eecd19
- machine: windows-amd64
- commit hash: a9574c6
- commit date: 2023-12-02
- overall geometric mean: 1.00x faster \*
- HPT reliability: 86.81%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231202-pythonperf1-amd64-python-a9574c68f04695eecd19-3.13.0a2+-a9574c6 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| 2to3           | 207 ms                                                      | 227 ms: 1.09x slower                                                        |
| chameleon      | 5.35 ms                                                     | 5.24 ms: 1.02x faster                                                       |
| docutils       | 1.59 sec                                                    | 1.65 sec: 1.04x slower                                                      |
| Geometric mean | (ref)                                                       | 1.03x slower                                                                |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231202-pythonperf1-amd64-python-a9574c68f04695eecd19-3.13.0a2+-a9574c6 |
|----------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| async_tree_none            | 314 ms                                                      | 276 ms: 1.13x faster                                                        |
| async_tree_cpu_io_mixed    | 495 ms                                                      | 467 ms: 1.06x faster                                                        |
| async_tree_memoization     | 367 ms                                                      | 356 ms: 1.03x faster                                                        |
| async_tree_none_tg         | 299 ms                                                      | 290 ms: 1.03x faster                                                        |
| async_tree_cpu_io_mixed_tg | 503 ms                                                      | 491 ms: 1.02x faster                                                        |
| async_tree_io_tg           | 795 ms                                                      | 785 ms: 1.01x faster                                                        |
| Geometric mean             | (ref)                                                       | 1.04x faster                                                                |

Benchmark hidden because not significant (2): async_tree_io, async_tree_memoization_tg

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231202-pythonperf1-amd64-python-a9574c68f04695eecd19-3.13.0a2+-a9574c6 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| pidigits       | 149 ms                                                      | 147 ms: 1.01x faster                                                        |
| float          | 54.4 ms                                                     | 57.6 ms: 1.06x slower                                                       |
| nbody          | 69.3 ms                                                     | 81.7 ms: 1.18x slower                                                       |
| Geometric mean | (ref)                                                       | 1.07x slower                                                                |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231202-pythonperf1-amd64-python-a9574c68f04695eecd19-3.13.0a2+-a9574c6 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_dna      | 121 ms                                                      | 119 ms: 1.02x faster                                                        |
| regex_compile  | 90.8 ms                                                     | 92.1 ms: 1.01x slower                                                       |
| regex_effbot   | 1.52 ms                                                     | 1.59 ms: 1.04x slower                                                       |
| regex_v8       | 13.7 ms                                                     | 19.5 ms: 1.42x slower                                                       |
| Geometric mean | (ref)                                                       | 1.10x slower                                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231202-pythonperf1-amd64-python-a9574c68f04695eecd19-3.13.0a2+-a9574c6 |
|----------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| json_dumps           | 7.90 ms                                                     | 5.86 ms: 1.35x faster                                                       |
| pickle_pure_python   | 207 us                                                      | 192 us: 1.08x faster                                                        |
| unpickle_pure_python | 152 us                                                      | 146 us: 1.04x faster                                                        |
| xml_etree_parse      | 94.5 ms                                                     | 93.1 ms: 1.02x faster                                                       |
| pickle_dict          | 17.8 us                                                     | 18.3 us: 1.03x slower                                                       |
| json_loads           | 12.9 us                                                     | 13.4 us: 1.04x slower                                                       |
| unpickle             | 7.82 us                                                     | 8.13 us: 1.04x slower                                                       |
| tomli_loads          | 1.42 sec                                                    | 1.49 sec: 1.05x slower                                                      |
| pickle               | 6.53 us                                                     | 6.89 us: 1.05x slower                                                       |
| xml_etree_iterparse  | 63.0 ms                                                     | 67.6 ms: 1.07x slower                                                       |
| xml_etree_process    | 37.0 ms                                                     | 39.8 ms: 1.08x slower                                                       |
| xml_etree_generate   | 52.2 ms                                                     | 57.3 ms: 1.10x slower                                                       |
| pickle_list          | 2.68 us                                                     | 3.10 us: 1.16x slower                                                       |
| Geometric mean       | (ref)                                                       | 1.01x slower                                                                |

Benchmark hidden because not significant (1): unpickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231202-pythonperf1-amd64-python-a9574c68f04695eecd19-3.13.0a2+-a9574c6 |
|------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| python_startup         | 18.8 ms                                                     | 20.5 ms: 1.09x slower                                                       |
| python_startup_no_site | 15.5 ms                                                     | 18.5 ms: 1.19x slower                                                       |
| Geometric mean         | (ref)                                                       | 1.14x slower                                                                |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231202-pythonperf1-amd64-python-a9574c68f04695eecd19-3.13.0a2+-a9574c6 |
|-----------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| mako      | 7.55 ms                                                     | 7.37 ms: 1.03x faster                                                       |

All benchmarks:
===============

| Benchmark                  | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231202-pythonperf1-amd64-python-a9574c68f04695eecd19-3.13.0a2+-a9574c6 |
|----------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| typing_runtime_protocols   | 320 us                                                      | 83.4 us: 3.84x faster                                                       |
| generators                 | 34.0 ms                                                     | 22.4 ms: 1.51x faster                                                       |
| json_dumps                 | 7.90 ms                                                     | 5.86 ms: 1.35x faster                                                       |
| asyncio_tcp                | 614 ms                                                      | 484 ms: 1.27x faster                                                        |
| mdp                        | 1.73 sec                                                    | 1.43 sec: 1.21x faster                                                      |
| unpack_sequence            | 47.0 ns                                                     | 38.9 ns: 1.21x faster                                                       |
| comprehensions             | 15.6 us                                                     | 13.2 us: 1.18x faster                                                       |
| raytrace                   | 211 ms                                                      | 184 ms: 1.15x faster                                                        |
| logging_silent             | 70.7 ns                                                     | 62.2 ns: 1.14x faster                                                       |
| async_tree_none            | 314 ms                                                      | 276 ms: 1.13x faster                                                        |
| sqlite_synth               | 1.79 us                                                     | 1.59 us: 1.13x faster                                                       |
| richards_super             | 37.9 ms                                                     | 33.6 ms: 1.13x faster                                                       |
| sympy_sum                  | 100.0 ms                                                    | 89.8 ms: 1.11x faster                                                       |
| asyncio_tcp_ssl            | 2.02 sec                                                    | 1.83 sec: 1.11x faster                                                      |
| sqlglot_parse              | 939 us                                                      | 849 us: 1.11x faster                                                        |
| pickle_pure_python         | 207 us                                                      | 192 us: 1.08x faster                                                        |
| deepcopy_memo              | 25.5 us                                                     | 23.8 us: 1.07x faster                                                       |
| sympy_str                  | 184 ms                                                      | 173 ms: 1.06x faster                                                        |
| async_tree_cpu_io_mixed    | 495 ms                                                      | 467 ms: 1.06x faster                                                        |
| sqlglot_transpile          | 1.15 ms                                                     | 1.08 ms: 1.06x faster                                                       |
| scimark_lu                 | 62.3 ms                                                     | 59.5 ms: 1.05x faster                                                       |
| unpickle_pure_python       | 152 us                                                      | 146 us: 1.04x faster                                                        |
| chaos                      | 46.8 ms                                                     | 45.0 ms: 1.04x faster                                                       |
| async_tree_memoization     | 367 ms                                                      | 356 ms: 1.03x faster                                                        |
| sympy_expand               | 299 ms                                                      | 290 ms: 1.03x faster                                                        |
| async_tree_none_tg         | 299 ms                                                      | 290 ms: 1.03x faster                                                        |
| richards                   | 30.8 ms                                                     | 30.0 ms: 1.03x faster                                                       |
| go                         | 98.8 ms                                                     | 96.3 ms: 1.03x faster                                                       |
| mako                       | 7.55 ms                                                     | 7.37 ms: 1.03x faster                                                       |
| dulwich_log                | 44.1 ms                                                     | 43.0 ms: 1.02x faster                                                       |
| async_tree_cpu_io_mixed_tg | 503 ms                                                      | 491 ms: 1.02x faster                                                        |
| chameleon                  | 5.35 ms                                                     | 5.24 ms: 1.02x faster                                                       |
| coroutines                 | 14.7 ms                                                     | 14.4 ms: 1.02x faster                                                       |
| regex_dna                  | 121 ms                                                      | 119 ms: 1.02x faster                                                        |
| deepcopy                   | 242 us                                                      | 239 us: 1.02x faster                                                        |
| xml_etree_parse            | 94.5 ms                                                     | 93.1 ms: 1.02x faster                                                       |
| async_tree_io_tg           | 795 ms                                                      | 785 ms: 1.01x faster                                                        |
| pidigits                   | 149 ms                                                      | 147 ms: 1.01x faster                                                        |
| sympy_integrate            | 13.7 ms                                                     | 13.6 ms: 1.01x faster                                                       |
| logging_simple             | 6.60 us                                                     | 6.57 us: 1.01x faster                                                       |
| regex_compile              | 90.8 ms                                                     | 92.1 ms: 1.01x slower                                                       |
| crypto_pyaes               | 48.2 ms                                                     | 49.0 ms: 1.02x slower                                                       |
| sqlglot_normalize          | 191 ms                                                      | 195 ms: 1.02x slower                                                        |
| dask                       | 262 ms                                                      | 268 ms: 1.02x slower                                                        |
| deepcopy_reduce            | 2.07 us                                                     | 2.12 us: 1.02x slower                                                       |
| pickle_dict                | 17.8 us                                                     | 18.3 us: 1.03x slower                                                       |
| meteor_contest             | 75.0 ms                                                     | 77.6 ms: 1.04x slower                                                       |
| docutils                   | 1.59 sec                                                    | 1.65 sec: 1.04x slower                                                      |
| json_loads                 | 12.9 us                                                     | 13.4 us: 1.04x slower                                                       |
| unpickle                   | 7.82 us                                                     | 8.13 us: 1.04x slower                                                       |
| scimark_sor                | 76.4 ms                                                     | 79.5 ms: 1.04x slower                                                       |
| bench_thread_pool          | 847 us                                                      | 882 us: 1.04x slower                                                        |
| regex_effbot               | 1.52 ms                                                     | 1.59 ms: 1.04x slower                                                       |
| deltablue                  | 2.63 ms                                                     | 2.76 ms: 1.05x slower                                                       |
| tomli_loads                | 1.42 sec                                                    | 1.49 sec: 1.05x slower                                                      |
| gc_traversal               | 1.46 ms                                                     | 1.53 ms: 1.05x slower                                                       |
| pickle                     | 6.53 us                                                     | 6.89 us: 1.05x slower                                                       |
| pprint_pformat             | 1.06 sec                                                    | 1.12 sec: 1.06x slower                                                      |
| sqlglot_optimize           | 35.1 ms                                                     | 37.1 ms: 1.06x slower                                                       |
| float                      | 54.4 ms                                                     | 57.6 ms: 1.06x slower                                                       |
| pprint_safe_repr           | 519 ms                                                      | 549 ms: 1.06x slower                                                        |
| pyflate                    | 305 ms                                                      | 325 ms: 1.07x slower                                                        |
| create_gc_cycles           | 706 us                                                      | 753 us: 1.07x slower                                                        |
| xml_etree_iterparse        | 63.0 ms                                                     | 67.6 ms: 1.07x slower                                                       |
| xml_etree_process          | 37.0 ms                                                     | 39.8 ms: 1.08x slower                                                       |
| python_startup             | 18.8 ms                                                     | 20.5 ms: 1.09x slower                                                       |
| 2to3                       | 207 ms                                                      | 227 ms: 1.09x slower                                                        |
| xml_etree_generate         | 52.2 ms                                                     | 57.3 ms: 1.10x slower                                                       |
| fannkuch                   | 248 ms                                                      | 273 ms: 1.10x slower                                                        |
| coverage                   | 43.0 ms                                                     | 47.3 ms: 1.10x slower                                                       |
| scimark_monte_carlo        | 44.6 ms                                                     | 49.8 ms: 1.12x slower                                                       |
| bench_mp_pool              | 61.1 ms                                                     | 68.5 ms: 1.12x slower                                                       |
| hexiom                     | 4.51 ms                                                     | 5.08 ms: 1.13x slower                                                       |
| scimark_fft                | 181 ms                                                      | 207 ms: 1.14x slower                                                        |
| pathlib                    | 69.4 ms                                                     | 79.9 ms: 1.15x slower                                                       |
| pickle_list                | 2.68 us                                                     | 3.10 us: 1.16x slower                                                       |
| spectral_norm              | 69.9 ms                                                     | 81.5 ms: 1.17x slower                                                       |
| nbody                      | 69.3 ms                                                     | 81.7 ms: 1.18x slower                                                       |
| scimark_sparse_mat_mult    | 2.59 ms                                                     | 3.08 ms: 1.19x slower                                                       |
| python_startup_no_site     | 15.5 ms                                                     | 18.5 ms: 1.19x slower                                                       |
| telco                      | 3.93 ms                                                     | 4.73 ms: 1.20x slower                                                       |
| async_generators           | 181 ms                                                      | 245 ms: 1.35x slower                                                        |
| regex_v8                   | 13.7 ms                                                     | 19.5 ms: 1.42x slower                                                       |
| mypy2                      | 226 ms                                                      | 439 ms: 1.94x slower                                                        |
| Geometric mean             | (ref)                                                       | 1.00x faster                                                                |

Benchmark hidden because not significant (8): json, pycparser, async_tree_io, async_tree_memoization_tg, logging_format, unpickle_list, nqueens, tornado_http
Ignored benchmarks (10) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift


# HPT report

- Reliability score: 86.81% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
