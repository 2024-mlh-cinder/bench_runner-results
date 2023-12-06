
# Results vs. 3.11.0

- fork: python
- ref: 6dfb8fe0236718e9afc8
- machine: windows-amd64
- commit hash: 6dfb8fe
- commit date: 2023-10-30
- overall geometric mean: 1.03x faster
- HPT reliability: 86.18%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231030-pythonperf1-amd64-python-6dfb8fe0236718e9afc8-3.13.0a1+-6dfb8fe |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| 2to3           | 207 ms                                                      | 223 ms: 1.08x slower                                                        |
| chameleon      | 5.35 ms                                                     | 5.22 ms: 1.03x faster                                                       |
| docutils       | 1.59 sec                                                    | 1.64 sec: 1.03x slower                                                      |
| Geometric mean | (ref)                                                       | 1.02x slower                                                                |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231030-pythonperf1-amd64-python-6dfb8fe0236718e9afc8-3.13.0a1+-6dfb8fe |
|----------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| async_tree_none            | 314 ms                                                      | 278 ms: 1.13x faster                                                        |
| async_tree_cpu_io_mixed    | 495 ms                                                      | 465 ms: 1.06x faster                                                        |
| async_tree_cpu_io_mixed_tg | 503 ms                                                      | 485 ms: 1.04x faster                                                        |
| async_tree_memoization     | 367 ms                                                      | 355 ms: 1.03x faster                                                        |
| async_tree_none_tg         | 299 ms                                                      | 291 ms: 1.03x faster                                                        |
| async_tree_io_tg           | 795 ms                                                      | 780 ms: 1.02x faster                                                        |
| Geometric mean             | (ref)                                                       | 1.04x faster                                                                |

Benchmark hidden because not significant (2): async_tree_memoization_tg, async_tree_io

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231030-pythonperf1-amd64-python-6dfb8fe0236718e9afc8-3.13.0a1+-6dfb8fe |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| pidigits       | 149 ms                                                      | 147 ms: 1.01x faster                                                        |
| nbody          | 69.3 ms                                                     | 75.2 ms: 1.09x slower                                                       |
| Geometric mean | (ref)                                                       | 1.02x slower                                                                |

Benchmark hidden because not significant (1): float

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231030-pythonperf1-amd64-python-6dfb8fe0236718e9afc8-3.13.0a1+-6dfb8fe |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_dna      | 121 ms                                                      | 121 ms: 1.01x faster                                                        |
| regex_compile  | 90.8 ms                                                     | 92.5 ms: 1.02x slower                                                       |
| regex_effbot   | 1.52 ms                                                     | 1.61 ms: 1.06x slower                                                       |
| regex_v8       | 13.7 ms                                                     | 15.5 ms: 1.13x slower                                                       |
| Geometric mean | (ref)                                                       | 1.05x slower                                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231030-pythonperf1-amd64-python-6dfb8fe0236718e9afc8-3.13.0a1+-6dfb8fe |
|----------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| json_dumps           | 7.90 ms                                                     | 5.77 ms: 1.37x faster                                                       |
| unpickle_pure_python | 152 us                                                      | 140 us: 1.09x faster                                                        |
| pickle_pure_python   | 207 us                                                      | 200 us: 1.04x faster                                                        |
| xml_etree_parse      | 94.5 ms                                                     | 91.9 ms: 1.03x faster                                                       |
| pickle_dict          | 17.8 us                                                     | 18.2 us: 1.03x slower                                                       |
| xml_etree_iterparse  | 63.0 ms                                                     | 65.1 ms: 1.03x slower                                                       |
| unpickle_list        | 2.57 us                                                     | 2.67 us: 1.04x slower                                                       |
| unpickle             | 7.82 us                                                     | 8.14 us: 1.04x slower                                                       |
| pickle               | 6.53 us                                                     | 6.94 us: 1.06x slower                                                       |
| xml_etree_process    | 37.0 ms                                                     | 39.5 ms: 1.07x slower                                                       |
| json_loads           | 12.9 us                                                     | 13.8 us: 1.07x slower                                                       |
| pickle_list          | 2.68 us                                                     | 2.89 us: 1.08x slower                                                       |
| xml_etree_generate   | 52.2 ms                                                     | 56.9 ms: 1.09x slower                                                       |
| tomli_loads          | 1.42 sec                                                    | 1.56 sec: 1.10x slower                                                      |
| Geometric mean       | (ref)                                                       | 1.01x slower                                                                |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231030-pythonperf1-amd64-python-6dfb8fe0236718e9afc8-3.13.0a1+-6dfb8fe |
|------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| python_startup         | 18.8 ms                                                     | 19.8 ms: 1.05x slower                                                       |
| python_startup_no_site | 15.5 ms                                                     | 18.0 ms: 1.16x slower                                                       |
| Geometric mean         | (ref)                                                       | 1.11x slower                                                                |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231030-pythonperf1-amd64-python-6dfb8fe0236718e9afc8-3.13.0a1+-6dfb8fe |
|-----------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| mako      | 7.55 ms                                                     | 7.12 ms: 1.06x faster                                                       |

All benchmarks:
===============

| Benchmark                  | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231030-pythonperf1-amd64-python-6dfb8fe0236718e9afc8-3.13.0a1+-6dfb8fe |
|----------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| typing_runtime_protocols   | 320 us                                                      | 98.7 us: 3.24x faster                                                       |
| generators                 | 34.0 ms                                                     | 23.3 ms: 1.46x faster                                                       |
| json_dumps                 | 7.90 ms                                                     | 5.77 ms: 1.37x faster                                                       |
| comprehensions             | 15.6 us                                                     | 11.4 us: 1.36x faster                                                       |
| asyncio_tcp                | 614 ms                                                      | 477 ms: 1.29x faster                                                        |
| unpack_sequence            | 47.0 ns                                                     | 38.7 ns: 1.21x faster                                                       |
| raytrace                   | 211 ms                                                      | 178 ms: 1.19x faster                                                        |
| deltablue                  | 2.63 ms                                                     | 2.22 ms: 1.19x faster                                                       |
| sqlite_synth               | 1.79 us                                                     | 1.57 us: 1.14x faster                                                       |
| mdp                        | 1.73 sec                                                    | 1.51 sec: 1.14x faster                                                      |
| sympy_sum                  | 100.0 ms                                                    | 88.3 ms: 1.13x faster                                                       |
| async_tree_none            | 314 ms                                                      | 278 ms: 1.13x faster                                                        |
| logging_silent             | 70.7 ns                                                     | 62.9 ns: 1.12x faster                                                       |
| richards_super             | 37.9 ms                                                     | 34.2 ms: 1.11x faster                                                       |
| spectral_norm              | 69.9 ms                                                     | 63.5 ms: 1.10x faster                                                       |
| sqlglot_parse              | 939 us                                                      | 860 us: 1.09x faster                                                        |
| unpickle_pure_python       | 152 us                                                      | 140 us: 1.09x faster                                                        |
| asyncio_tcp_ssl            | 2.02 sec                                                    | 1.86 sec: 1.09x faster                                                      |
| chaos                      | 46.8 ms                                                     | 43.1 ms: 1.08x faster                                                       |
| scimark_lu                 | 62.3 ms                                                     | 57.6 ms: 1.08x faster                                                       |
| crypto_pyaes               | 48.2 ms                                                     | 44.6 ms: 1.08x faster                                                       |
| sympy_str                  | 184 ms                                                      | 172 ms: 1.07x faster                                                        |
| nqueens                    | 66.1 ms                                                     | 61.9 ms: 1.07x faster                                                       |
| async_tree_cpu_io_mixed    | 495 ms                                                      | 465 ms: 1.06x faster                                                        |
| sqlglot_transpile          | 1.15 ms                                                     | 1.08 ms: 1.06x faster                                                       |
| mako                       | 7.55 ms                                                     | 7.12 ms: 1.06x faster                                                       |
| hexiom                     | 4.51 ms                                                     | 4.26 ms: 1.06x faster                                                       |
| scimark_monte_carlo        | 44.6 ms                                                     | 42.6 ms: 1.05x faster                                                       |
| sympy_integrate            | 13.7 ms                                                     | 13.1 ms: 1.05x faster                                                       |
| mypy2                      | 226 ms                                                      | 217 ms: 1.04x faster                                                        |
| scimark_sparse_mat_mult    | 2.59 ms                                                     | 2.49 ms: 1.04x faster                                                       |
| pickle_pure_python         | 207 us                                                      | 200 us: 1.04x faster                                                        |
| async_tree_cpu_io_mixed_tg | 503 ms                                                      | 485 ms: 1.04x faster                                                        |
| async_tree_memoization     | 367 ms                                                      | 355 ms: 1.03x faster                                                        |
| xml_etree_parse            | 94.5 ms                                                     | 91.9 ms: 1.03x faster                                                       |
| async_tree_none_tg         | 299 ms                                                      | 291 ms: 1.03x faster                                                        |
| chameleon                  | 5.35 ms                                                     | 5.22 ms: 1.03x faster                                                       |
| deepcopy_memo              | 25.5 us                                                     | 25.0 us: 1.02x faster                                                       |
| async_tree_io_tg           | 795 ms                                                      | 780 ms: 1.02x faster                                                        |
| scimark_fft                | 181 ms                                                      | 178 ms: 1.02x faster                                                        |
| bench_thread_pool          | 847 us                                                      | 833 us: 1.02x faster                                                        |
| richards                   | 30.8 ms                                                     | 30.3 ms: 1.02x faster                                                       |
| go                         | 98.8 ms                                                     | 97.3 ms: 1.02x faster                                                       |
| pidigits                   | 149 ms                                                      | 147 ms: 1.01x faster                                                        |
| coroutines                 | 14.7 ms                                                     | 14.5 ms: 1.01x faster                                                       |
| regex_dna                  | 121 ms                                                      | 121 ms: 1.01x faster                                                        |
| sympy_expand               | 299 ms                                                      | 297 ms: 1.00x faster                                                        |
| pyflate                    | 305 ms                                                      | 306 ms: 1.01x slower                                                        |
| scimark_sor                | 76.4 ms                                                     | 77.6 ms: 1.01x slower                                                       |
| deepcopy                   | 242 us                                                      | 246 us: 1.02x slower                                                        |
| regex_compile              | 90.8 ms                                                     | 92.5 ms: 1.02x slower                                                       |
| dulwich_log                | 44.1 ms                                                     | 45.0 ms: 1.02x slower                                                       |
| sqlglot_normalize          | 191 ms                                                      | 195 ms: 1.02x slower                                                        |
| meteor_contest             | 75.0 ms                                                     | 76.6 ms: 1.02x slower                                                       |
| pickle_dict                | 17.8 us                                                     | 18.2 us: 1.03x slower                                                       |
| create_gc_cycles           | 706 us                                                      | 725 us: 1.03x slower                                                        |
| pprint_safe_repr           | 519 ms                                                      | 535 ms: 1.03x slower                                                        |
| gc_traversal               | 1.46 ms                                                     | 1.50 ms: 1.03x slower                                                       |
| docutils                   | 1.59 sec                                                    | 1.64 sec: 1.03x slower                                                      |
| bench_mp_pool              | 61.1 ms                                                     | 63.1 ms: 1.03x slower                                                       |
| pprint_pformat             | 1.06 sec                                                    | 1.10 sec: 1.03x slower                                                      |
| xml_etree_iterparse        | 63.0 ms                                                     | 65.1 ms: 1.03x slower                                                       |
| logging_simple             | 6.60 us                                                     | 6.83 us: 1.03x slower                                                       |
| sqlglot_optimize           | 35.1 ms                                                     | 36.4 ms: 1.04x slower                                                       |
| logging_format             | 7.06 us                                                     | 7.33 us: 1.04x slower                                                       |
| unpickle_list              | 2.57 us                                                     | 2.67 us: 1.04x slower                                                       |
| unpickle                   | 7.82 us                                                     | 8.14 us: 1.04x slower                                                       |
| coverage                   | 43.0 ms                                                     | 44.9 ms: 1.04x slower                                                       |
| python_startup             | 18.8 ms                                                     | 19.8 ms: 1.05x slower                                                       |
| fannkuch                   | 248 ms                                                      | 263 ms: 1.06x slower                                                        |
| regex_effbot               | 1.52 ms                                                     | 1.61 ms: 1.06x slower                                                       |
| pickle                     | 6.53 us                                                     | 6.94 us: 1.06x slower                                                       |
| deepcopy_reduce            | 2.07 us                                                     | 2.21 us: 1.06x slower                                                       |
| xml_etree_process          | 37.0 ms                                                     | 39.5 ms: 1.07x slower                                                       |
| json_loads                 | 12.9 us                                                     | 13.8 us: 1.07x slower                                                       |
| 2to3                       | 207 ms                                                      | 223 ms: 1.08x slower                                                        |
| pickle_list                | 2.68 us                                                     | 2.89 us: 1.08x slower                                                       |
| nbody                      | 69.3 ms                                                     | 75.2 ms: 1.09x slower                                                       |
| xml_etree_generate         | 52.2 ms                                                     | 56.9 ms: 1.09x slower                                                       |
| tomli_loads                | 1.42 sec                                                    | 1.56 sec: 1.10x slower                                                      |
| regex_v8                   | 13.7 ms                                                     | 15.5 ms: 1.13x slower                                                       |
| pathlib                    | 69.4 ms                                                     | 79.7 ms: 1.15x slower                                                       |
| pycparser                  | 705 ms                                                      | 813 ms: 1.15x slower                                                        |
| python_startup_no_site     | 15.5 ms                                                     | 18.0 ms: 1.16x slower                                                       |
| telco                      | 3.93 ms                                                     | 4.77 ms: 1.21x slower                                                       |
| async_generators           | 181 ms                                                      | 238 ms: 1.32x slower                                                        |
| Geometric mean             | (ref)                                                       | 1.03x faster                                                                |

Benchmark hidden because not significant (5): float, tornado_http, async_tree_memoization_tg, async_tree_io, json
Ignored benchmarks (11) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, dask, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift


# HPT report

- Reliability score: 86.18% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
