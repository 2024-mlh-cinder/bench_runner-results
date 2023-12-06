
# Results vs. 3.12.0

- fork: faster-cpython
- ref: optimize_globals_to_
- machine: linux-x86_64
- commit hash: 30e5f4b
- commit date: 2023-11-04
- overall geometric mean: 1.01x slower \*
- HPT reliability: 77.85%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231104-pythonperf2-x86_64-faster%2dcpython-optimize_globals_to_-3.13.0a1+-30e5f4b |
|----------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------------------:|
| 2to3           | 285 ms                                                       | 292 ms: 1.03x slower                                                                   |
| chameleon      | 7.27 ms                                                      | 7.41 ms: 1.02x slower                                                                  |
| docutils       | 2.89 sec                                                     | 2.82 sec: 1.03x faster                                                                 |
| tornado_http   | 122 ms                                                       | 120 ms: 1.02x faster                                                                   |
| Geometric mean | (ref)                                                        | 1.00x slower                                                                           |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231104-pythonperf2-x86_64-faster%2dcpython-optimize_globals_to_-3.13.0a1+-30e5f4b |
|----------------------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------------------:|
| async_tree_none            | 459 ms                                                       | 430 ms: 1.07x faster                                                                   |
| async_tree_memoization     | 554 ms                                                       | 547 ms: 1.01x faster                                                                   |
| async_tree_cpu_io_mixed_tg | 706 ms                                                       | 713 ms: 1.01x slower                                                                   |
| async_tree_io              | 1.06 sec                                                     | 1.07 sec: 1.01x slower                                                                 |
| async_tree_io_tg           | 1.07 sec                                                     | 1.09 sec: 1.02x slower                                                                 |
| async_tree_memoization_tg  | 554 ms                                                       | 573 ms: 1.03x slower                                                                   |
| Geometric mean             | (ref)                                                        | 1.00x faster                                                                           |

Benchmark hidden because not significant (2): async_tree_cpu_io_mixed, async_tree_none_tg

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231104-pythonperf2-x86_64-faster%2dcpython-optimize_globals_to_-3.13.0a1+-30e5f4b |
|----------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------------------:|
| nbody          | 88.2 ms                                                      | 83.7 ms: 1.05x faster                                                                  |
| pidigits       | 264 ms                                                       | 264 ms: 1.00x faster                                                                   |
| Geometric mean | (ref)                                                        | 1.03x faster                                                                           |

Benchmark hidden because not significant (1): float

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231104-pythonperf2-x86_64-faster%2dcpython-optimize_globals_to_-3.13.0a1+-30e5f4b |
|----------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------------------:|
| regex_effbot   | 3.61 ms                                                      | 3.47 ms: 1.04x faster                                                                  |
| regex_dna      | 240 ms                                                       | 241 ms: 1.00x slower                                                                   |
| Geometric mean | (ref)                                                        | 1.01x faster                                                                           |

Benchmark hidden because not significant (2): regex_v8, regex_compile

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231104-pythonperf2-x86_64-faster%2dcpython-optimize_globals_to_-3.13.0a1+-30e5f4b |
|----------------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------------------:|
| unpickle             | 15.3 us                                                      | 14.3 us: 1.07x faster                                                                  |
| pickle_pure_python   | 319 us                                                       | 307 us: 1.04x faster                                                                   |
| xml_etree_process    | 58.3 ms                                                      | 57.8 ms: 1.01x faster                                                                  |
| xml_etree_generate   | 85.3 ms                                                      | 85.0 ms: 1.00x faster                                                                  |
| json_dumps           | 10.3 ms                                                      | 10.3 ms: 1.01x slower                                                                  |
| pickle               | 10.0 us                                                      | 10.1 us: 1.01x slower                                                                  |
| xml_etree_parse      | 147 ms                                                       | 151 ms: 1.03x slower                                                                   |
| pickle_dict          | 32.0 us                                                      | 33.0 us: 1.03x slower                                                                  |
| xml_etree_iterparse  | 104 ms                                                       | 108 ms: 1.04x slower                                                                   |
| unpickle_pure_python | 210 us                                                       | 221 us: 1.05x slower                                                                   |
| tomli_loads          | 2.17 sec                                                     | 2.29 sec: 1.06x slower                                                                 |
| pickle_list          | 4.22 us                                                      | 4.46 us: 1.06x slower                                                                  |
| Geometric mean       | (ref)                                                        | 1.01x slower                                                                           |

Benchmark hidden because not significant (2): unpickle_list, json_loads

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231104-pythonperf2-x86_64-faster%2dcpython-optimize_globals_to_-3.13.0a1+-30e5f4b |
|------------------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------------------:|
| python_startup         | 11.7 ms                                                      | 12.8 ms: 1.10x slower                                                                  |
| python_startup_no_site | 8.67 ms                                                      | 11.3 ms: 1.30x slower                                                                  |
| Geometric mean         | (ref)                                                        | 1.20x slower                                                                           |

Benchmarks with tag 'template':
===============================

Benchmark hidden because not significant (1): mako

All benchmarks:
===============

| Benchmark                  | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231104-pythonperf2-x86_64-faster%2dcpython-optimize_globals_to_-3.13.0a1+-30e5f4b |
|----------------------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------------------:|
| comprehensions             | 21.8 us                                                      | 16.4 us: 1.33x faster                                                                  |
| typing_runtime_protocols   | 150 us                                                       | 122 us: 1.23x faster                                                                   |
| crypto_pyaes               | 82.4 ms                                                      | 70.7 ms: 1.17x faster                                                                  |
| raytrace                   | 301 ms                                                       | 271 ms: 1.11x faster                                                                   |
| generators                 | 37.3 ms                                                      | 34.3 ms: 1.09x faster                                                                  |
| sympy_sum                  | 163 ms                                                       | 151 ms: 1.07x faster                                                                   |
| unpickle                   | 15.3 us                                                      | 14.3 us: 1.07x faster                                                                  |
| async_tree_none            | 459 ms                                                       | 430 ms: 1.07x faster                                                                   |
| async_generators           | 385 ms                                                       | 363 ms: 1.06x faster                                                                   |
| unpack_sequence            | 54.5 ns                                                      | 51.5 ns: 1.06x faster                                                                  |
| sympy_str                  | 305 ms                                                       | 289 ms: 1.05x faster                                                                   |
| nbody                      | 88.2 ms                                                      | 83.7 ms: 1.05x faster                                                                  |
| gc_traversal               | 3.70 ms                                                      | 3.52 ms: 1.05x faster                                                                  |
| chaos                      | 64.1 ms                                                      | 61.0 ms: 1.05x faster                                                                  |
| sympy_integrate            | 24.0 ms                                                      | 22.9 ms: 1.05x faster                                                                  |
| scimark_sparse_mat_mult    | 4.49 ms                                                      | 4.29 ms: 1.05x faster                                                                  |
| deepcopy_reduce            | 3.41 us                                                      | 3.27 us: 1.04x faster                                                                  |
| scimark_monte_carlo        | 69.5 ms                                                      | 66.8 ms: 1.04x faster                                                                  |
| regex_effbot               | 3.61 ms                                                      | 3.47 ms: 1.04x faster                                                                  |
| pickle_pure_python         | 319 us                                                       | 307 us: 1.04x faster                                                                   |
| spectral_norm              | 93.9 ms                                                      | 90.6 ms: 1.04x faster                                                                  |
| sqlite_synth               | 2.72 us                                                      | 2.64 us: 1.03x faster                                                                  |
| sqlglot_normalize          | 119 ms                                                       | 116 ms: 1.03x faster                                                                   |
| asyncio_tcp                | 380 ms                                                       | 369 ms: 1.03x faster                                                                   |
| docutils                   | 2.89 sec                                                     | 2.82 sec: 1.03x faster                                                                 |
| deepcopy                   | 371 us                                                       | 362 us: 1.02x faster                                                                   |
| nqueens                    | 90.1 ms                                                      | 88.0 ms: 1.02x faster                                                                  |
| mdp                        | 2.56 sec                                                     | 2.50 sec: 1.02x faster                                                                 |
| coroutines                 | 23.1 ms                                                      | 22.6 ms: 1.02x faster                                                                  |
| tornado_http               | 122 ms                                                       | 120 ms: 1.02x faster                                                                   |
| pprint_safe_repr           | 808 ms                                                       | 798 ms: 1.01x faster                                                                   |
| async_tree_memoization     | 554 ms                                                       | 547 ms: 1.01x faster                                                                   |
| xml_etree_process          | 58.3 ms                                                      | 57.8 ms: 1.01x faster                                                                  |
| json                       | 5.17 ms                                                      | 5.13 ms: 1.01x faster                                                                  |
| pprint_pformat             | 1.64 sec                                                     | 1.63 sec: 1.01x faster                                                                 |
| xml_etree_generate         | 85.3 ms                                                      | 85.0 ms: 1.00x faster                                                                  |
| pidigits                   | 264 ms                                                       | 264 ms: 1.00x faster                                                                   |
| regex_dna                  | 240 ms                                                       | 241 ms: 1.00x slower                                                                   |
| sympy_expand               | 492 ms                                                       | 494 ms: 1.01x slower                                                                   |
| asyncio_tcp_ssl            | 1.57 sec                                                     | 1.58 sec: 1.01x slower                                                                 |
| mypy2                      | 365 ms                                                       | 368 ms: 1.01x slower                                                                   |
| json_dumps                 | 10.3 ms                                                      | 10.3 ms: 1.01x slower                                                                  |
| pickle                     | 10.0 us                                                      | 10.1 us: 1.01x slower                                                                  |
| async_tree_cpu_io_mixed_tg | 706 ms                                                       | 713 ms: 1.01x slower                                                                   |
| sqlglot_parse              | 1.41 ms                                                      | 1.42 ms: 1.01x slower                                                                  |
| sqlglot_transpile          | 1.80 ms                                                      | 1.83 ms: 1.01x slower                                                                  |
| async_tree_io              | 1.06 sec                                                     | 1.07 sec: 1.01x slower                                                                 |
| meteor_contest             | 126 ms                                                       | 128 ms: 1.02x slower                                                                   |
| async_tree_io_tg           | 1.07 sec                                                     | 1.09 sec: 1.02x slower                                                                 |
| deepcopy_memo              | 36.6 us                                                      | 37.3 us: 1.02x slower                                                                  |
| chameleon                  | 7.27 ms                                                      | 7.41 ms: 1.02x slower                                                                  |
| logging_silent             | 93.3 ns                                                      | 95.1 ns: 1.02x slower                                                                  |
| 2to3                       | 285 ms                                                       | 292 ms: 1.03x slower                                                                   |
| xml_etree_parse            | 147 ms                                                       | 151 ms: 1.03x slower                                                                   |
| pickle_dict                | 32.0 us                                                      | 33.0 us: 1.03x slower                                                                  |
| async_tree_memoization_tg  | 554 ms                                                       | 573 ms: 1.03x slower                                                                   |
| scimark_lu                 | 98.6 ms                                                      | 102 ms: 1.04x slower                                                                   |
| xml_etree_iterparse        | 104 ms                                                       | 108 ms: 1.04x slower                                                                   |
| pathlib                    | 18.7 ms                                                      | 19.5 ms: 1.04x slower                                                                  |
| dulwich_log                | 64.9 ms                                                      | 68.0 ms: 1.05x slower                                                                  |
| unpickle_pure_python       | 210 us                                                       | 221 us: 1.05x slower                                                                   |
| tomli_loads                | 2.17 sec                                                     | 2.29 sec: 1.06x slower                                                                 |
| pickle_list                | 4.22 us                                                      | 4.46 us: 1.06x slower                                                                  |
| fannkuch                   | 362 ms                                                       | 384 ms: 1.06x slower                                                                   |
| hexiom                     | 5.97 ms                                                      | 6.41 ms: 1.07x slower                                                                  |
| python_startup             | 11.7 ms                                                      | 12.8 ms: 1.10x slower                                                                  |
| telco                      | 7.16 ms                                                      | 8.06 ms: 1.13x slower                                                                  |
| pyflate                    | 442 ms                                                       | 501 ms: 1.13x slower                                                                   |
| go                         | 149 ms                                                       | 172 ms: 1.16x slower                                                                   |
| deltablue                  | 3.24 ms                                                      | 3.76 ms: 1.16x slower                                                                  |
| richards_super             | 50.8 ms                                                      | 59.4 ms: 1.17x slower                                                                  |
| richards                   | 45.1 ms                                                      | 53.7 ms: 1.19x slower                                                                  |
| coverage                   | 66.3 ms                                                      | 81.4 ms: 1.23x slower                                                                  |
| python_startup_no_site     | 8.67 ms                                                      | 11.3 ms: 1.30x slower                                                                  |
| scimark_sor                | 107 ms                                                       | 147 ms: 1.38x slower                                                                   |
| Geometric mean             | (ref)                                                        | 1.01x slower                                                                           |

Benchmark hidden because not significant (17): bench_mp_pool, float, async_tree_cpu_io_mixed, logging_simple, unpickle_list, async_tree_none_tg, asyncio_websockets, scimark_fft, regex_v8, json_loads, logging_format, sqlglot_optimize, create_gc_cycles, regex_compile, bench_thread_pool, pycparser, mako
Ignored benchmarks (6) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, dask, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 77.85% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
