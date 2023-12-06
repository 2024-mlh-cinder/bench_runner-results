
# Results vs. 3.11.0

- fork: faster-cpython
- ref: optimize_globals_to_
- machine: linux-x86_64
- commit hash: 30e5f4b
- commit date: 2023-11-04
- overall geometric mean: 1.07x faster \*
- HPT reliability: 99.74%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231104-pythonperf2-x86_64-faster%2dcpython-optimize_globals_to_-3.13.0a1+-30e5f4b |
|----------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------------------:|
| 2to3           | 286 ms                                                       | 292 ms: 1.02x slower                                                                   |
| docutils       | 2.87 sec                                                     | 2.82 sec: 1.02x faster                                                                 |
| tornado_http   | 125 ms                                                       | 120 ms: 1.04x faster                                                                   |
| Geometric mean | (ref)                                                        | 1.01x faster                                                                           |

Benchmark hidden because not significant (1): chameleon

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231104-pythonperf2-x86_64-faster%2dcpython-optimize_globals_to_-3.13.0a1+-30e5f4b |
|----------------------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------------------:|
| async_tree_none            | 529 ms                                                       | 430 ms: 1.23x faster                                                                   |
| async_tree_memoization     | 648 ms                                                       | 547 ms: 1.18x faster                                                                   |
| async_tree_io              | 1.19 sec                                                     | 1.07 sec: 1.11x faster                                                                 |
| async_tree_none_tg         | 482 ms                                                       | 440 ms: 1.10x faster                                                                   |
| async_tree_cpu_io_mixed    | 762 ms                                                       | 698 ms: 1.09x faster                                                                   |
| async_tree_io_tg           | 1.17 sec                                                     | 1.09 sec: 1.07x faster                                                                 |
| async_tree_cpu_io_mixed_tg | 760 ms                                                       | 713 ms: 1.07x faster                                                                   |
| async_tree_memoization_tg  | 605 ms                                                       | 573 ms: 1.06x faster                                                                   |
| Geometric mean             | (ref)                                                        | 1.11x faster                                                                           |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231104-pythonperf2-x86_64-faster%2dcpython-optimize_globals_to_-3.13.0a1+-30e5f4b |
|----------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------------------:|
| nbody          | 95.8 ms                                                      | 83.7 ms: 1.14x faster                                                                  |
| pidigits       | 251 ms                                                       | 264 ms: 1.05x slower                                                                   |
| float          | 76.0 ms                                                      | 80.0 ms: 1.05x slower                                                                  |
| Geometric mean | (ref)                                                        | 1.01x faster                                                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231104-pythonperf2-x86_64-faster%2dcpython-optimize_globals_to_-3.13.0a1+-30e5f4b |
|----------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------------------:|
| regex_compile  | 157 ms                                                       | 145 ms: 1.08x faster                                                                   |
| regex_effbot   | 3.42 ms                                                      | 3.47 ms: 1.02x slower                                                                  |
| regex_v8       | 23.7 ms                                                      | 24.4 ms: 1.03x slower                                                                  |
| regex_dna      | 226 ms                                                       | 241 ms: 1.07x slower                                                                   |
| Geometric mean | (ref)                                                        | 1.01x slower                                                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231104-pythonperf2-x86_64-faster%2dcpython-optimize_globals_to_-3.13.0a1+-30e5f4b |
|----------------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------------------:|
| json_dumps           | 13.5 ms                                                      | 10.3 ms: 1.30x faster                                                                  |
| json_loads           | 29.0 us                                                      | 24.3 us: 1.19x faster                                                                  |
| unpickle_pure_python | 236 us                                                       | 221 us: 1.07x faster                                                                   |
| xml_etree_parse      | 159 ms                                                       | 151 ms: 1.05x faster                                                                   |
| pickle_pure_python   | 318 us                                                       | 307 us: 1.04x faster                                                                   |
| tomli_loads          | 2.27 sec                                                     | 2.29 sec: 1.01x slower                                                                 |
| xml_etree_iterparse  | 106 ms                                                       | 108 ms: 1.02x slower                                                                   |
| xml_etree_process    | 56.1 ms                                                      | 57.8 ms: 1.03x slower                                                                  |
| unpickle_list        | 4.47 us                                                      | 4.63 us: 1.04x slower                                                                  |
| pickle               | 9.77 us                                                      | 10.1 us: 1.04x slower                                                                  |
| pickle_dict          | 31.8 us                                                      | 33.0 us: 1.04x slower                                                                  |
| xml_etree_generate   | 80.5 ms                                                      | 85.0 ms: 1.06x slower                                                                  |
| unpickle             | 13.2 us                                                      | 14.3 us: 1.09x slower                                                                  |
| pickle_list          | 3.89 us                                                      | 4.46 us: 1.14x slower                                                                  |
| Geometric mean       | (ref)                                                        | 1.01x faster                                                                           |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231104-pythonperf2-x86_64-faster%2dcpython-optimize_globals_to_-3.13.0a1+-30e5f4b |
|------------------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------------------:|
| python_startup         | 10.8 ms                                                      | 12.8 ms: 1.19x slower                                                                  |
| python_startup_no_site | 7.78 ms                                                      | 11.3 ms: 1.45x slower                                                                  |
| Geometric mean         | (ref)                                                        | 1.31x slower                                                                           |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231104-pythonperf2-x86_64-faster%2dcpython-optimize_globals_to_-3.13.0a1+-30e5f4b |
|-----------|:------------------------------------------------------------:|:--------------------------------------------------------------------------------------:|
| mako      | 11.0 ms                                                      | 10.2 ms: 1.08x faster                                                                  |

All benchmarks:
===============

| Benchmark                  | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231104-pythonperf2-x86_64-faster%2dcpython-optimize_globals_to_-3.13.0a1+-30e5f4b |
|----------------------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------------------:|
| typing_runtime_protocols   | 527 us                                                       | 122 us: 4.31x faster                                                                   |
| asyncio_tcp                | 752 ms                                                       | 369 ms: 2.04x faster                                                                   |
| asyncio_tcp_ssl            | 3.09 sec                                                     | 1.58 sec: 1.95x faster                                                                 |
| generators                 | 56.4 ms                                                      | 34.3 ms: 1.65x faster                                                                  |
| comprehensions             | 24.8 us                                                      | 16.4 us: 1.51x faster                                                                  |
| json_dumps                 | 13.5 ms                                                      | 10.3 ms: 1.30x faster                                                                  |
| coroutines                 | 27.9 ms                                                      | 22.6 ms: 1.23x faster                                                                  |
| async_tree_none            | 529 ms                                                       | 430 ms: 1.23x faster                                                                   |
| mypy2                      | 449 ms                                                       | 368 ms: 1.22x faster                                                                   |
| sympy_sum                  | 184 ms                                                       | 151 ms: 1.22x faster                                                                   |
| json_loads                 | 29.0 us                                                      | 24.3 us: 1.19x faster                                                                  |
| fannkuch                   | 457 ms                                                       | 384 ms: 1.19x faster                                                                   |
| async_tree_memoization     | 648 ms                                                       | 547 ms: 1.18x faster                                                                   |
| chaos                      | 71.6 ms                                                      | 61.0 ms: 1.17x faster                                                                  |
| sympy_str                  | 336 ms                                                       | 289 ms: 1.16x faster                                                                   |
| crypto_pyaes               | 81.8 ms                                                      | 70.7 ms: 1.16x faster                                                                  |
| gc_traversal               | 4.06 ms                                                      | 3.52 ms: 1.15x faster                                                                  |
| nbody                      | 95.8 ms                                                      | 83.7 ms: 1.14x faster                                                                  |
| raytrace                   | 308 ms                                                       | 271 ms: 1.14x faster                                                                   |
| nqueens                    | 99.2 ms                                                      | 88.0 ms: 1.13x faster                                                                  |
| scimark_lu                 | 115 ms                                                       | 102 ms: 1.13x faster                                                                   |
| sympy_integrate            | 25.6 ms                                                      | 22.9 ms: 1.12x faster                                                                  |
| sympy_expand               | 550 ms                                                       | 494 ms: 1.11x faster                                                                   |
| async_tree_io              | 1.19 sec                                                     | 1.07 sec: 1.11x faster                                                                 |
| richards_super             | 65.2 ms                                                      | 59.4 ms: 1.10x faster                                                                  |
| async_tree_none_tg         | 482 ms                                                       | 440 ms: 1.10x faster                                                                   |
| logging_simple             | 7.21 us                                                      | 6.60 us: 1.09x faster                                                                  |
| sqlglot_parse              | 1.55 ms                                                      | 1.42 ms: 1.09x faster                                                                  |
| async_tree_cpu_io_mixed    | 762 ms                                                       | 698 ms: 1.09x faster                                                                   |
| json                       | 5.59 ms                                                      | 5.13 ms: 1.09x faster                                                                  |
| hexiom                     | 6.97 ms                                                      | 6.41 ms: 1.09x faster                                                                  |
| mdp                        | 2.72 sec                                                     | 2.50 sec: 1.09x faster                                                                 |
| mako                       | 11.0 ms                                                      | 10.2 ms: 1.08x faster                                                                  |
| regex_compile              | 157 ms                                                       | 145 ms: 1.08x faster                                                                   |
| deepcopy                   | 389 us                                                       | 362 us: 1.07x faster                                                                   |
| async_tree_io_tg           | 1.17 sec                                                     | 1.09 sec: 1.07x faster                                                                 |
| logging_silent             | 102 ns                                                       | 95.1 ns: 1.07x faster                                                                  |
| logging_format             | 7.83 us                                                      | 7.30 us: 1.07x faster                                                                  |
| deltablue                  | 4.03 ms                                                      | 3.76 ms: 1.07x faster                                                                  |
| unpickle_pure_python       | 236 us                                                       | 221 us: 1.07x faster                                                                   |
| async_tree_cpu_io_mixed_tg | 760 ms                                                       | 713 ms: 1.07x faster                                                                   |
| sqlglot_transpile          | 1.94 ms                                                      | 1.83 ms: 1.06x faster                                                                  |
| bench_thread_pool          | 1.02 ms                                                      | 964 us: 1.06x faster                                                                   |
| scimark_monte_carlo        | 70.6 ms                                                      | 66.8 ms: 1.06x faster                                                                  |
| async_tree_memoization_tg  | 605 ms                                                       | 573 ms: 1.06x faster                                                                   |
| xml_etree_parse            | 159 ms                                                       | 151 ms: 1.05x faster                                                                   |
| sqlglot_normalize          | 122 ms                                                       | 116 ms: 1.05x faster                                                                   |
| tornado_http               | 125 ms                                                       | 120 ms: 1.04x faster                                                                   |
| spectral_norm              | 94.0 ms                                                      | 90.6 ms: 1.04x faster                                                                  |
| pickle_pure_python         | 318 us                                                       | 307 us: 1.04x faster                                                                   |
| deepcopy_reduce            | 3.37 us                                                      | 3.27 us: 1.03x faster                                                                  |
| docutils                   | 2.87 sec                                                     | 2.82 sec: 1.02x faster                                                                 |
| meteor_contest             | 130 ms                                                       | 128 ms: 1.01x faster                                                                   |
| sqlglot_optimize           | 59.2 ms                                                      | 58.5 ms: 1.01x faster                                                                  |
| tomli_loads                | 2.27 sec                                                     | 2.29 sec: 1.01x slower                                                                 |
| xml_etree_iterparse        | 106 ms                                                       | 108 ms: 1.02x slower                                                                   |
| regex_effbot               | 3.42 ms                                                      | 3.47 ms: 1.02x slower                                                                  |
| pycparser                  | 1.28 sec                                                     | 1.30 sec: 1.02x slower                                                                 |
| pathlib                    | 19.1 ms                                                      | 19.5 ms: 1.02x slower                                                                  |
| 2to3                       | 286 ms                                                       | 292 ms: 1.02x slower                                                                   |
| pprint_safe_repr           | 780 ms                                                       | 798 ms: 1.02x slower                                                                   |
| xml_etree_process          | 56.1 ms                                                      | 57.8 ms: 1.03x slower                                                                  |
| regex_v8                   | 23.7 ms                                                      | 24.4 ms: 1.03x slower                                                                  |
| bench_mp_pool              | 4.63 ms                                                      | 4.78 ms: 1.03x slower                                                                  |
| unpickle_list              | 4.47 us                                                      | 4.63 us: 1.04x slower                                                                  |
| pickle                     | 9.77 us                                                      | 10.1 us: 1.04x slower                                                                  |
| pickle_dict                | 31.8 us                                                      | 33.0 us: 1.04x slower                                                                  |
| go                         | 166 ms                                                       | 172 ms: 1.04x slower                                                                   |
| pidigits                   | 251 ms                                                       | 264 ms: 1.05x slower                                                                   |
| float                      | 76.0 ms                                                      | 80.0 ms: 1.05x slower                                                                  |
| xml_etree_generate         | 80.5 ms                                                      | 85.0 ms: 1.06x slower                                                                  |
| sqlite_synth               | 2.49 us                                                      | 2.64 us: 1.06x slower                                                                  |
| scimark_sparse_mat_mult    | 4.04 ms                                                      | 4.29 ms: 1.06x slower                                                                  |
| regex_dna                  | 226 ms                                                       | 241 ms: 1.07x slower                                                                   |
| richards                   | 49.9 ms                                                      | 53.7 ms: 1.08x slower                                                                  |
| scimark_fft                | 281 ms                                                       | 304 ms: 1.08x slower                                                                   |
| unpickle                   | 13.2 us                                                      | 14.3 us: 1.09x slower                                                                  |
| pyflate                    | 453 ms                                                       | 501 ms: 1.11x slower                                                                   |
| async_generators           | 322 ms                                                       | 363 ms: 1.13x slower                                                                   |
| pickle_list                | 3.89 us                                                      | 4.46 us: 1.14x slower                                                                  |
| unpack_sequence            | 44.9 ns                                                      | 51.5 ns: 1.15x slower                                                                  |
| telco                      | 6.91 ms                                                      | 8.06 ms: 1.17x slower                                                                  |
| python_startup             | 10.8 ms                                                      | 12.8 ms: 1.19x slower                                                                  |
| coverage                   | 66.6 ms                                                      | 81.4 ms: 1.22x slower                                                                  |
| scimark_sor                | 109 ms                                                       | 147 ms: 1.34x slower                                                                   |
| python_startup_no_site     | 7.78 ms                                                      | 11.3 ms: 1.45x slower                                                                  |
| Geometric mean             | (ref)                                                        | 1.07x faster                                                                           |

Benchmark hidden because not significant (6): create_gc_cycles, asyncio_websockets, dulwich_log, chameleon, deepcopy_memo, pprint_pformat
Ignored benchmarks (12) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, dask, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift


# HPT report

- Reliability score: 99.74% likely to be faster
- 90% likely to have a speedup of 1.02x
- 95% likely to have a speedup of 1.01x
- 99% likely to have a speedup of 1.00x
