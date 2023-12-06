
# Results vs. 3.11.0

- fork: brandtbucher
- ref: justin_no_stubs
- machine: linux-x86_64
- commit hash: 925f140
- commit date: 2023-11-20
- overall geometric mean: 1.04x faster \*
- HPT reliability: 79.98%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-pythonperf2-x86_64-brandtbucher-justin_no_stubs-3.13.0a1+-925f140 |
|----------------|:------------------------------------------------------------:|:-----------------------------------------------------------------------------:|
| 2to3           | 286 ms                                                       | 301 ms: 1.05x slower                                                          |
| chameleon      | 7.42 ms                                                      | 7.50 ms: 1.01x slower                                                         |
| tornado_http   | 125 ms                                                       | 120 ms: 1.04x faster                                                          |
| Geometric mean | (ref)                                                        | 1.01x slower                                                                  |

Benchmark hidden because not significant (1): docutils

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-pythonperf2-x86_64-brandtbucher-justin_no_stubs-3.13.0a1+-925f140 |
|----------------------------|:------------------------------------------------------------:|:-----------------------------------------------------------------------------:|
| async_tree_none            | 529 ms                                                       | 436 ms: 1.21x faster                                                          |
| async_tree_memoization     | 648 ms                                                       | 547 ms: 1.18x faster                                                          |
| async_tree_io              | 1.19 sec                                                     | 1.08 sec: 1.10x faster                                                        |
| async_tree_none_tg         | 482 ms                                                       | 444 ms: 1.09x faster                                                          |
| async_tree_cpu_io_mixed    | 762 ms                                                       | 702 ms: 1.09x faster                                                          |
| async_tree_io_tg           | 1.17 sec                                                     | 1.10 sec: 1.07x faster                                                        |
| async_tree_memoization_tg  | 605 ms                                                       | 571 ms: 1.06x faster                                                          |
| async_tree_cpu_io_mixed_tg | 760 ms                                                       | 720 ms: 1.06x faster                                                          |
| Geometric mean             | (ref)                                                        | 1.11x faster                                                                  |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-pythonperf2-x86_64-brandtbucher-justin_no_stubs-3.13.0a1+-925f140 |
|----------------|:------------------------------------------------------------:|:-----------------------------------------------------------------------------:|
| float          | 76.0 ms                                                      | 79.1 ms: 1.04x slower                                                         |
| pidigits       | 251 ms                                                       | 265 ms: 1.06x slower                                                          |
| Geometric mean | (ref)                                                        | 1.03x slower                                                                  |

Benchmark hidden because not significant (1): nbody

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-pythonperf2-x86_64-brandtbucher-justin_no_stubs-3.13.0a1+-925f140 |
|----------------|:------------------------------------------------------------:|:-----------------------------------------------------------------------------:|
| regex_compile  | 157 ms                                                       | 149 ms: 1.05x faster                                                          |
| regex_effbot   | 3.42 ms                                                      | 3.49 ms: 1.02x slower                                                         |
| regex_v8       | 23.7 ms                                                      | 25.4 ms: 1.07x slower                                                         |
| regex_dna      | 226 ms                                                       | 244 ms: 1.08x slower                                                          |
| Geometric mean | (ref)                                                        | 1.03x slower                                                                  |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-pythonperf2-x86_64-brandtbucher-justin_no_stubs-3.13.0a1+-925f140 |
|----------------------|:------------------------------------------------------------:|:-----------------------------------------------------------------------------:|
| json_dumps           | 13.5 ms                                                      | 10.8 ms: 1.25x faster                                                         |
| json_loads           | 29.0 us                                                      | 25.6 us: 1.13x faster                                                         |
| xml_etree_parse      | 159 ms                                                       | 147 ms: 1.08x faster                                                          |
| unpickle_pure_python | 236 us                                                       | 222 us: 1.07x faster                                                          |
| pickle_pure_python   | 318 us                                                       | 311 us: 1.02x faster                                                          |
| xml_etree_iterparse  | 106 ms                                                       | 105 ms: 1.01x faster                                                          |
| pickle_dict          | 31.8 us                                                      | 32.3 us: 1.02x slower                                                         |
| pickle               | 9.77 us                                                      | 10.0 us: 1.03x slower                                                         |
| unpickle_list        | 4.47 us                                                      | 4.65 us: 1.04x slower                                                         |
| xml_etree_process    | 56.1 ms                                                      | 58.9 ms: 1.05x slower                                                         |
| xml_etree_generate   | 80.5 ms                                                      | 85.6 ms: 1.06x slower                                                         |
| pickle_list          | 3.89 us                                                      | 4.40 us: 1.13x slower                                                         |
| unpickle             | 13.2 us                                                      | 15.1 us: 1.15x slower                                                         |
| Geometric mean       | (ref)                                                        | 1.01x faster                                                                  |

Benchmark hidden because not significant (1): tomli_loads

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-pythonperf2-x86_64-brandtbucher-justin_no_stubs-3.13.0a1+-925f140 |
|------------------------|:------------------------------------------------------------:|:-----------------------------------------------------------------------------:|
| python_startup         | 10.8 ms                                                      | 12.9 ms: 1.19x slower                                                         |
| python_startup_no_site | 7.78 ms                                                      | 11.3 ms: 1.46x slower                                                         |
| Geometric mean         | (ref)                                                        | 1.32x slower                                                                  |

Benchmarks with tag 'template':
===============================

Benchmark hidden because not significant (1): mako

All benchmarks:
===============

| Benchmark                  | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-pythonperf2-x86_64-brandtbucher-justin_no_stubs-3.13.0a1+-925f140 |
|----------------------------|:------------------------------------------------------------:|:-----------------------------------------------------------------------------:|
| typing_runtime_protocols   | 527 us                                                       | 130 us: 4.06x faster                                                          |
| asyncio_tcp                | 752 ms                                                       | 368 ms: 2.04x faster                                                          |
| asyncio_tcp_ssl            | 3.09 sec                                                     | 1.57 sec: 1.96x faster                                                        |
| generators                 | 56.4 ms                                                      | 36.4 ms: 1.55x faster                                                         |
| json_dumps                 | 13.5 ms                                                      | 10.8 ms: 1.25x faster                                                         |
| comprehensions             | 24.8 us                                                      | 20.2 us: 1.23x faster                                                         |
| coroutines                 | 27.9 ms                                                      | 22.7 ms: 1.23x faster                                                         |
| async_tree_none            | 529 ms                                                       | 436 ms: 1.21x faster                                                          |
| mypy2                      | 449 ms                                                       | 378 ms: 1.19x faster                                                          |
| async_tree_memoization     | 648 ms                                                       | 547 ms: 1.18x faster                                                          |
| gc_traversal               | 4.06 ms                                                      | 3.45 ms: 1.18x faster                                                         |
| sympy_sum                  | 184 ms                                                       | 159 ms: 1.16x faster                                                          |
| richards_super             | 65.2 ms                                                      | 57.4 ms: 1.14x faster                                                         |
| json_loads                 | 29.0 us                                                      | 25.6 us: 1.13x faster                                                         |
| sympy_str                  | 336 ms                                                       | 300 ms: 1.12x faster                                                          |
| scimark_lu                 | 115 ms                                                       | 103 ms: 1.12x faster                                                          |
| fannkuch                   | 457 ms                                                       | 411 ms: 1.11x faster                                                          |
| async_tree_io              | 1.19 sec                                                     | 1.08 sec: 1.10x faster                                                        |
| sympy_expand               | 550 ms                                                       | 500 ms: 1.10x faster                                                          |
| logging_simple             | 7.21 us                                                      | 6.57 us: 1.10x faster                                                         |
| sqlglot_parse              | 1.55 ms                                                      | 1.42 ms: 1.10x faster                                                         |
| async_tree_none_tg         | 482 ms                                                       | 444 ms: 1.09x faster                                                          |
| async_tree_cpu_io_mixed    | 762 ms                                                       | 702 ms: 1.09x faster                                                          |
| xml_etree_parse            | 159 ms                                                       | 147 ms: 1.08x faster                                                          |
| raytrace                   | 308 ms                                                       | 285 ms: 1.08x faster                                                          |
| deltablue                  | 4.03 ms                                                      | 3.74 ms: 1.08x faster                                                         |
| logging_format             | 7.83 us                                                      | 7.30 us: 1.07x faster                                                         |
| async_tree_io_tg           | 1.17 sec                                                     | 1.10 sec: 1.07x faster                                                        |
| json                       | 5.59 ms                                                      | 5.24 ms: 1.07x faster                                                         |
| unpickle_pure_python       | 236 us                                                       | 222 us: 1.07x faster                                                          |
| deepcopy                   | 389 us                                                       | 367 us: 1.06x faster                                                          |
| async_tree_memoization_tg  | 605 ms                                                       | 571 ms: 1.06x faster                                                          |
| sympy_integrate            | 25.6 ms                                                      | 24.2 ms: 1.06x faster                                                         |
| async_tree_cpu_io_mixed_tg | 760 ms                                                       | 720 ms: 1.06x faster                                                          |
| sqlglot_transpile          | 1.94 ms                                                      | 1.84 ms: 1.05x faster                                                         |
| regex_compile              | 157 ms                                                       | 149 ms: 1.05x faster                                                          |
| tornado_http               | 125 ms                                                       | 120 ms: 1.04x faster                                                          |
| dask                       | 417 ms                                                       | 400 ms: 1.04x faster                                                          |
| bench_thread_pool          | 1.02 ms                                                      | 980 us: 1.04x faster                                                          |
| deepcopy_reduce            | 3.37 us                                                      | 3.28 us: 1.03x faster                                                         |
| logging_silent             | 102 ns                                                       | 99.3 ns: 1.03x faster                                                         |
| pickle_pure_python         | 318 us                                                       | 311 us: 1.02x faster                                                          |
| chaos                      | 71.6 ms                                                      | 70.4 ms: 1.02x faster                                                         |
| mdp                        | 2.72 sec                                                     | 2.67 sec: 1.02x faster                                                        |
| deepcopy_memo              | 37.3 us                                                      | 36.8 us: 1.01x faster                                                         |
| sqlglot_normalize          | 122 ms                                                       | 120 ms: 1.01x faster                                                          |
| xml_etree_iterparse        | 106 ms                                                       | 105 ms: 1.01x faster                                                          |
| dulwich_log                | 68.3 ms                                                      | 67.6 ms: 1.01x faster                                                         |
| pathlib                    | 19.1 ms                                                      | 19.3 ms: 1.01x slower                                                         |
| crypto_pyaes               | 81.8 ms                                                      | 82.4 ms: 1.01x slower                                                         |
| chameleon                  | 7.42 ms                                                      | 7.50 ms: 1.01x slower                                                         |
| meteor_contest             | 130 ms                                                       | 132 ms: 1.02x slower                                                          |
| pickle_dict                | 31.8 us                                                      | 32.3 us: 1.02x slower                                                         |
| richards                   | 49.9 ms                                                      | 50.9 ms: 1.02x slower                                                         |
| regex_effbot               | 3.42 ms                                                      | 3.49 ms: 1.02x slower                                                         |
| pickle                     | 9.77 us                                                      | 10.0 us: 1.03x slower                                                         |
| pycparser                  | 1.28 sec                                                     | 1.33 sec: 1.04x slower                                                        |
| sqlglot_optimize           | 59.2 ms                                                      | 61.4 ms: 1.04x slower                                                         |
| unpickle_list              | 4.47 us                                                      | 4.65 us: 1.04x slower                                                         |
| go                         | 166 ms                                                       | 172 ms: 1.04x slower                                                          |
| float                      | 76.0 ms                                                      | 79.1 ms: 1.04x slower                                                         |
| nqueens                    | 99.2 ms                                                      | 104 ms: 1.04x slower                                                          |
| xml_etree_process          | 56.1 ms                                                      | 58.9 ms: 1.05x slower                                                         |
| 2to3                       | 286 ms                                                       | 301 ms: 1.05x slower                                                          |
| pidigits                   | 251 ms                                                       | 265 ms: 1.06x slower                                                          |
| xml_etree_generate         | 80.5 ms                                                      | 85.6 ms: 1.06x slower                                                         |
| unpack_sequence            | 44.9 ns                                                      | 47.9 ns: 1.07x slower                                                         |
| regex_v8                   | 23.7 ms                                                      | 25.4 ms: 1.07x slower                                                         |
| pprint_pformat             | 1.63 sec                                                     | 1.76 sec: 1.08x slower                                                        |
| regex_dna                  | 226 ms                                                       | 244 ms: 1.08x slower                                                          |
| sqlite_synth               | 2.49 us                                                      | 2.73 us: 1.10x slower                                                         |
| pprint_safe_repr           | 780 ms                                                       | 860 ms: 1.10x slower                                                          |
| scimark_sparse_mat_mult    | 4.04 ms                                                      | 4.48 ms: 1.11x slower                                                         |
| hexiom                     | 6.97 ms                                                      | 7.78 ms: 1.12x slower                                                         |
| spectral_norm              | 94.0 ms                                                      | 106 ms: 1.13x slower                                                          |
| pickle_list                | 3.89 us                                                      | 4.40 us: 1.13x slower                                                         |
| scimark_monte_carlo        | 70.6 ms                                                      | 80.9 ms: 1.15x slower                                                         |
| unpickle                   | 13.2 us                                                      | 15.1 us: 1.15x slower                                                         |
| pyflate                    | 453 ms                                                       | 522 ms: 1.15x slower                                                          |
| python_startup             | 10.8 ms                                                      | 12.9 ms: 1.19x slower                                                         |
| telco                      | 6.91 ms                                                      | 8.22 ms: 1.19x slower                                                         |
| async_generators           | 322 ms                                                       | 383 ms: 1.19x slower                                                          |
| coverage                   | 66.6 ms                                                      | 80.8 ms: 1.21x slower                                                         |
| scimark_fft                | 281 ms                                                       | 364 ms: 1.29x slower                                                          |
| scimark_sor                | 109 ms                                                       | 147 ms: 1.34x slower                                                          |
| python_startup_no_site     | 7.78 ms                                                      | 11.3 ms: 1.46x slower                                                         |
| Geometric mean             | (ref)                                                        | 1.04x faster                                                                  |

Benchmark hidden because not significant (7): create_gc_cycles, mako, nbody, tomli_loads, docutils, asyncio_websockets, bench_mp_pool
Ignored benchmarks (11) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift


# HPT report

- Reliability score: 79.98% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
