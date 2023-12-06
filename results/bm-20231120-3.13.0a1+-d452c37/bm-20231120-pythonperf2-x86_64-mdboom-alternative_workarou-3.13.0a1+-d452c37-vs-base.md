
# Results vs. base

- fork: mdboom
- ref: alternative_workarou
- machine: linux-x86_64
- commit hash: d452c37
- commit date: 2023-11-20
- overall geometric mean: 1.01x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231120-pythonperf2-x86_64-python-8deb8bc2e5af0e229df8-3.13.0a1+-8deb8bc | bm-20231120-pythonperf2-x86_64-mdboom-alternative_workarou-3.13.0a1+-d452c37 |
|----------------|:----------------------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| 2to3           | 291 ms                                                                       | 292 ms: 1.00x slower                                                         |
| chameleon      | 7.39 ms                                                                      | 7.58 ms: 1.03x slower                                                        |
| docutils       | 2.81 sec                                                                     | 2.84 sec: 1.01x slower                                                       |
| Geometric mean | (ref)                                                                        | 1.01x slower                                                                 |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231120-pythonperf2-x86_64-python-8deb8bc2e5af0e229df8-3.13.0a1+-8deb8bc | bm-20231120-pythonperf2-x86_64-mdboom-alternative_workarou-3.13.0a1+-d452c37 |
|----------------------------|:----------------------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| async_tree_io_tg           | 1.08 sec                                                                     | 1.09 sec: 1.01x slower                                                       |
| async_tree_io              | 1.07 sec                                                                     | 1.08 sec: 1.01x slower                                                       |
| async_tree_none_tg         | 436 ms                                                                       | 441 ms: 1.01x slower                                                         |
| async_tree_cpu_io_mixed_tg | 704 ms                                                                       | 712 ms: 1.01x slower                                                         |
| async_tree_cpu_io_mixed    | 685 ms                                                                       | 696 ms: 1.02x slower                                                         |
| async_tree_memoization     | 536 ms                                                                       | 545 ms: 1.02x slower                                                         |
| async_tree_none            | 425 ms                                                                       | 432 ms: 1.02x slower                                                         |
| async_tree_memoization_tg  | 553 ms                                                                       | 570 ms: 1.03x slower                                                         |
| Geometric mean             | (ref)                                                                        | 1.02x slower                                                                 |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231120-pythonperf2-x86_64-python-8deb8bc2e5af0e229df8-3.13.0a1+-8deb8bc | bm-20231120-pythonperf2-x86_64-mdboom-alternative_workarou-3.13.0a1+-d452c37 |
|----------------|:----------------------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| pidigits       | 266 ms                                                                       | 267 ms: 1.00x slower                                                         |
| float          | 78.5 ms                                                                      | 79.7 ms: 1.02x slower                                                        |
| nbody          | 85.1 ms                                                                      | 87.6 ms: 1.03x slower                                                        |
| Geometric mean | (ref)                                                                        | 1.02x slower                                                                 |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231120-pythonperf2-x86_64-python-8deb8bc2e5af0e229df8-3.13.0a1+-8deb8bc | bm-20231120-pythonperf2-x86_64-mdboom-alternative_workarou-3.13.0a1+-d452c37 |
|----------------|:----------------------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| regex_effbot   | 3.51 ms                                                                      | 3.58 ms: 1.02x slower                                                        |
| regex_compile  | 141 ms                                                                       | 145 ms: 1.03x slower                                                         |
| regex_v8       | 24.8 ms                                                                      | 25.6 ms: 1.03x slower                                                        |
| regex_dna      | 242 ms                                                                       | 252 ms: 1.04x slower                                                         |
| Geometric mean | (ref)                                                                        | 1.03x slower                                                                 |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231120-pythonperf2-x86_64-python-8deb8bc2e5af0e229df8-3.13.0a1+-8deb8bc | bm-20231120-pythonperf2-x86_64-mdboom-alternative_workarou-3.13.0a1+-d452c37 |
|----------------------|:----------------------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| pickle_dict          | 33.1 us                                                                      | 32.0 us: 1.03x faster                                                        |
| json_loads           | 25.5 us                                                                      | 25.3 us: 1.01x faster                                                        |
| json_dumps           | 10.7 ms                                                                      | 10.6 ms: 1.01x faster                                                        |
| unpickle_pure_python | 222 us                                                                       | 224 us: 1.01x slower                                                         |
| xml_etree_process    | 58.5 ms                                                                      | 58.8 ms: 1.01x slower                                                        |
| xml_etree_parse      | 148 ms                                                                       | 150 ms: 1.02x slower                                                         |
| pickle_pure_python   | 302 us                                                                       | 309 us: 1.02x slower                                                         |
| tomli_loads          | 2.18 sec                                                                     | 2.28 sec: 1.05x slower                                                       |
| Geometric mean       | (ref)                                                                        | 1.00x slower                                                                 |

Benchmark hidden because not significant (6): xml_etree_iterparse, pickle_list, unpickle_list, xml_etree_generate, pickle, unpickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231120-pythonperf2-x86_64-python-8deb8bc2e5af0e229df8-3.13.0a1+-8deb8bc | bm-20231120-pythonperf2-x86_64-mdboom-alternative_workarou-3.13.0a1+-d452c37 |
|------------------------|:----------------------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| python_startup_no_site | 11.3 ms                                                                      | 11.3 ms: 1.00x slower                                                        |
| python_startup         | 12.8 ms                                                                      | 12.8 ms: 1.00x slower                                                        |
| Geometric mean         | (ref)                                                                        | 1.00x slower                                                                 |

Benchmarks with tag 'template':
===============================

Benchmark hidden because not significant (1): mako

All benchmarks:
===============

| Benchmark                  | bm-20231120-pythonperf2-x86_64-python-8deb8bc2e5af0e229df8-3.13.0a1+-8deb8bc | bm-20231120-pythonperf2-x86_64-mdboom-alternative_workarou-3.13.0a1+-d452c37 |
|----------------------------|:----------------------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| pyflate                    | 532 ms                                                                       | 508 ms: 1.05x faster                                                         |
| pickle_dict                | 33.1 us                                                                      | 32.0 us: 1.03x faster                                                        |
| scimark_lu                 | 102 ms                                                                       | 99.6 ms: 1.03x faster                                                        |
| scimark_monte_carlo        | 67.2 ms                                                                      | 66.5 ms: 1.01x faster                                                        |
| deltablue                  | 3.59 ms                                                                      | 3.56 ms: 1.01x faster                                                        |
| json_loads                 | 25.5 us                                                                      | 25.3 us: 1.01x faster                                                        |
| generators                 | 34.4 ms                                                                      | 34.2 ms: 1.01x faster                                                        |
| telco                      | 8.08 ms                                                                      | 8.03 ms: 1.01x faster                                                        |
| json_dumps                 | 10.7 ms                                                                      | 10.6 ms: 1.01x faster                                                        |
| dulwich_log                | 67.6 ms                                                                      | 67.2 ms: 1.01x faster                                                        |
| async_generators           | 363 ms                                                                       | 362 ms: 1.00x faster                                                         |
| python_startup_no_site     | 11.3 ms                                                                      | 11.3 ms: 1.00x slower                                                        |
| python_startup             | 12.8 ms                                                                      | 12.8 ms: 1.00x slower                                                        |
| pidigits                   | 266 ms                                                                       | 267 ms: 1.00x slower                                                         |
| sqlite_synth               | 2.71 us                                                                      | 2.72 us: 1.00x slower                                                        |
| 2to3                       | 291 ms                                                                       | 292 ms: 1.00x slower                                                         |
| meteor_contest             | 128 ms                                                                       | 128 ms: 1.00x slower                                                         |
| pathlib                    | 18.8 ms                                                                      | 18.8 ms: 1.00x slower                                                        |
| nqueens                    | 88.1 ms                                                                      | 88.5 ms: 1.00x slower                                                        |
| sympy_sum                  | 151 ms                                                                       | 152 ms: 1.00x slower                                                         |
| sympy_str                  | 289 ms                                                                       | 290 ms: 1.01x slower                                                         |
| unpickle_pure_python       | 222 us                                                                       | 224 us: 1.01x slower                                                         |
| xml_etree_process          | 58.5 ms                                                                      | 58.8 ms: 1.01x slower                                                        |
| hexiom                     | 6.39 ms                                                                      | 6.44 ms: 1.01x slower                                                        |
| mypy2                      | 363 ms                                                                       | 366 ms: 1.01x slower                                                         |
| richards                   | 52.2 ms                                                                      | 52.7 ms: 1.01x slower                                                        |
| go                         | 168 ms                                                                       | 169 ms: 1.01x slower                                                         |
| sqlglot_optimize           | 57.8 ms                                                                      | 58.3 ms: 1.01x slower                                                        |
| async_tree_io_tg           | 1.08 sec                                                                     | 1.09 sec: 1.01x slower                                                       |
| logging_simple             | 6.55 us                                                                      | 6.62 us: 1.01x slower                                                        |
| sympy_expand               | 490 ms                                                                       | 495 ms: 1.01x slower                                                         |
| async_tree_io              | 1.07 sec                                                                     | 1.08 sec: 1.01x slower                                                       |
| scimark_sparse_mat_mult    | 4.15 ms                                                                      | 4.20 ms: 1.01x slower                                                        |
| sympy_integrate            | 22.8 ms                                                                      | 23.0 ms: 1.01x slower                                                        |
| async_tree_none_tg         | 436 ms                                                                       | 441 ms: 1.01x slower                                                         |
| sqlglot_transpile          | 1.78 ms                                                                      | 1.80 ms: 1.01x slower                                                        |
| async_tree_cpu_io_mixed_tg | 704 ms                                                                       | 712 ms: 1.01x slower                                                         |
| docutils                   | 2.81 sec                                                                     | 2.84 sec: 1.01x slower                                                       |
| spectral_norm              | 90.8 ms                                                                      | 92.0 ms: 1.01x slower                                                        |
| sqlglot_normalize          | 114 ms                                                                       | 115 ms: 1.01x slower                                                         |
| sqlglot_parse              | 1.37 ms                                                                      | 1.39 ms: 1.01x slower                                                        |
| mdp                        | 2.49 sec                                                                     | 2.53 sec: 1.01x slower                                                       |
| async_tree_cpu_io_mixed    | 685 ms                                                                       | 696 ms: 1.02x slower                                                         |
| async_tree_memoization     | 536 ms                                                                       | 545 ms: 1.02x slower                                                         |
| float                      | 78.5 ms                                                                      | 79.7 ms: 1.02x slower                                                        |
| async_tree_none            | 425 ms                                                                       | 432 ms: 1.02x slower                                                         |
| logging_silent             | 95.6 ns                                                                      | 97.2 ns: 1.02x slower                                                        |
| xml_etree_parse            | 148 ms                                                                       | 150 ms: 1.02x slower                                                         |
| scimark_fft                | 303 ms                                                                       | 308 ms: 1.02x slower                                                         |
| richards_super             | 57.5 ms                                                                      | 58.6 ms: 1.02x slower                                                        |
| regex_effbot               | 3.51 ms                                                                      | 3.58 ms: 1.02x slower                                                        |
| pickle_pure_python         | 302 us                                                                       | 309 us: 1.02x slower                                                         |
| crypto_pyaes               | 69.7 ms                                                                      | 71.2 ms: 1.02x slower                                                        |
| fannkuch                   | 378 ms                                                                       | 386 ms: 1.02x slower                                                         |
| typing_runtime_protocols   | 123 us                                                                       | 126 us: 1.02x slower                                                         |
| comprehensions             | 16.3 us                                                                      | 16.7 us: 1.02x slower                                                        |
| raytrace                   | 264 ms                                                                       | 271 ms: 1.02x slower                                                         |
| chameleon                  | 7.39 ms                                                                      | 7.58 ms: 1.03x slower                                                        |
| deepcopy_reduce            | 3.24 us                                                                      | 3.33 us: 1.03x slower                                                        |
| pprint_pformat             | 1.61 sec                                                                     | 1.66 sec: 1.03x slower                                                       |
| regex_compile              | 141 ms                                                                       | 145 ms: 1.03x slower                                                         |
| deepcopy_memo              | 36.6 us                                                                      | 37.6 us: 1.03x slower                                                        |
| pprint_safe_repr           | 791 ms                                                                       | 814 ms: 1.03x slower                                                         |
| nbody                      | 85.1 ms                                                                      | 87.6 ms: 1.03x slower                                                        |
| regex_v8                   | 24.8 ms                                                                      | 25.6 ms: 1.03x slower                                                        |
| async_tree_memoization_tg  | 553 ms                                                                       | 570 ms: 1.03x slower                                                         |
| unpack_sequence            | 46.4 ns                                                                      | 48.0 ns: 1.03x slower                                                        |
| logging_format             | 7.11 us                                                                      | 7.38 us: 1.04x slower                                                        |
| deepcopy                   | 357 us                                                                       | 371 us: 1.04x slower                                                         |
| regex_dna                  | 242 ms                                                                       | 252 ms: 1.04x slower                                                         |
| tomli_loads                | 2.18 sec                                                                     | 2.28 sec: 1.05x slower                                                       |
| coverage                   | 79.7 ms                                                                      | 85.4 ms: 1.07x slower                                                        |
| Geometric mean             | (ref)                                                                        | 1.01x slower                                                                 |

Benchmark hidden because not significant (21): bench_mp_pool, xml_etree_iterparse, bench_thread_pool, scimark_sor, pickle_list, unpickle_list, chaos, coroutines, xml_etree_generate, json, pickle, asyncio_tcp, tornado_http, pycparser, asyncio_tcp_ssl, unpickle, asyncio_websockets, dask, create_gc_cycles, gc_traversal, mako


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
