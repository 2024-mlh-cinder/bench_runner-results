
# Results vs. base

- fork: iritkatriel
- ref: gen_yf
- machine: linux-x86_64
- commit hash: 0b37841
- commit date: 2023-11-02
- overall geometric mean: 1.01x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231102-linux-x86_64-python-6a0d7b43df12ab4426ba-3.13.0a1+-6a0d7b4 | bm-20231102-linux-x86_64-iritkatriel-gen_yf-3.13.0a1+-0b37841 |
|----------------|:----------------------------------------------------------------------:|:-------------------------------------------------------------:|
| 2to3           | 262 ms                                                                 | 264 ms: 1.01x slower                                          |
| chameleon      | 6.95 ms                                                                | 7.06 ms: 1.02x slower                                         |
| docutils       | 2.59 sec                                                               | 2.61 sec: 1.00x slower                                        |
| Geometric mean | (ref)                                                                  | 1.01x slower                                                  |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231102-linux-x86_64-python-6a0d7b43df12ab4426ba-3.13.0a1+-6a0d7b4 | bm-20231102-linux-x86_64-iritkatriel-gen_yf-3.13.0a1+-0b37841 |
|----------------------------|:----------------------------------------------------------------------:|:-------------------------------------------------------------:|
| async_tree_io_tg           | 1.23 sec                                                               | 1.23 sec: 1.01x slower                                        |
| async_tree_io              | 1.18 sec                                                               | 1.19 sec: 1.01x slower                                        |
| async_tree_memoization_tg  | 595 ms                                                                 | 602 ms: 1.01x slower                                          |
| async_tree_cpu_io_mixed    | 704 ms                                                                 | 717 ms: 1.02x slower                                          |
| async_tree_cpu_io_mixed_tg | 735 ms                                                                 | 750 ms: 1.02x slower                                          |
| Geometric mean             | (ref)                                                                  | 1.01x slower                                                  |

Benchmark hidden because not significant (3): async_tree_none, async_tree_none_tg, async_tree_memoization

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231102-linux-x86_64-python-6a0d7b43df12ab4426ba-3.13.0a1+-6a0d7b4 | bm-20231102-linux-x86_64-iritkatriel-gen_yf-3.13.0a1+-0b37841 |
|----------------|:----------------------------------------------------------------------:|:-------------------------------------------------------------:|
| pidigits       | 195 ms                                                                 | 195 ms: 1.00x slower                                          |
| float          | 80.5 ms                                                                | 82.3 ms: 1.02x slower                                         |
| Geometric mean | (ref)                                                                  | 1.01x slower                                                  |

Benchmark hidden because not significant (1): nbody

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231102-linux-x86_64-python-6a0d7b43df12ab4426ba-3.13.0a1+-6a0d7b4 | bm-20231102-linux-x86_64-iritkatriel-gen_yf-3.13.0a1+-0b37841 |
|----------------|:----------------------------------------------------------------------:|:-------------------------------------------------------------:|
| regex_effbot   | 3.61 ms                                                                | 3.57 ms: 1.01x faster                                         |
| regex_dna      | 215 ms                                                                 | 215 ms: 1.00x slower                                          |
| regex_v8       | 25.6 ms                                                                | 25.8 ms: 1.01x slower                                         |
| Geometric mean | (ref)                                                                  | 1.00x faster                                                  |

Benchmark hidden because not significant (1): regex_compile

Benchmarks with tag 'serialize':
================================

| Benchmark          | bm-20231102-linux-x86_64-python-6a0d7b43df12ab4426ba-3.13.0a1+-6a0d7b4 | bm-20231102-linux-x86_64-iritkatriel-gen_yf-3.13.0a1+-0b37841 |
|--------------------|:----------------------------------------------------------------------:|:-------------------------------------------------------------:|
| json_dumps         | 10.5 ms                                                                | 10.5 ms: 1.01x slower                                         |
| pickle_pure_python | 294 us                                                                 | 296 us: 1.01x slower                                          |
| json_loads         | 27.6 us                                                                | 27.9 us: 1.01x slower                                         |
| xml_etree_generate | 85.3 ms                                                                | 86.5 ms: 1.01x slower                                         |
| xml_etree_process  | 58.5 ms                                                                | 59.4 ms: 1.02x slower                                         |
| xml_etree_parse    | 158 ms                                                                 | 161 ms: 1.02x slower                                          |
| pickle             | 11.2 us                                                                | 11.5 us: 1.03x slower                                         |
| pickle_dict        | 33.7 us                                                                | 35.2 us: 1.04x slower                                         |
| unpickle           | 14.6 us                                                                | 15.8 us: 1.09x slower                                         |
| Geometric mean     | (ref)                                                                  | 1.02x slower                                                  |

Benchmark hidden because not significant (5): unpickle_pure_python, pickle_list, tomli_loads, unpickle_list, xml_etree_iterparse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231102-linux-x86_64-python-6a0d7b43df12ab4426ba-3.13.0a1+-6a0d7b4 | bm-20231102-linux-x86_64-iritkatriel-gen_yf-3.13.0a1+-0b37841 |
|------------------------|:----------------------------------------------------------------------:|:-------------------------------------------------------------:|
| python_startup         | 10.3 ms                                                                | 10.3 ms: 1.00x slower                                         |
| python_startup_no_site | 8.98 ms                                                                | 8.99 ms: 1.00x slower                                         |
| Geometric mean         | (ref)                                                                  | 1.00x slower                                                  |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231102-linux-x86_64-python-6a0d7b43df12ab4426ba-3.13.0a1+-6a0d7b4 | bm-20231102-linux-x86_64-iritkatriel-gen_yf-3.13.0a1+-0b37841 |
|-----------|:----------------------------------------------------------------------:|:-------------------------------------------------------------:|
| mako      | 10.9 ms                                                                | 11.4 ms: 1.04x slower                                         |

All benchmarks:
===============

| Benchmark                  | bm-20231102-linux-x86_64-python-6a0d7b43df12ab4426ba-3.13.0a1+-6a0d7b4 | bm-20231102-linux-x86_64-iritkatriel-gen_yf-3.13.0a1+-0b37841 |
|----------------------------|:----------------------------------------------------------------------:|:-------------------------------------------------------------:|
| scimark_sparse_mat_mult    | 4.91 ms                                                                | 4.52 ms: 1.09x faster                                         |
| telco                      | 8.42 ms                                                                | 8.19 ms: 1.03x faster                                         |
| sqlite_synth               | 2.83 us                                                                | 2.79 us: 1.01x faster                                         |
| regex_effbot               | 3.61 ms                                                                | 3.57 ms: 1.01x faster                                         |
| nqueens                    | 79.8 ms                                                                | 79.0 ms: 1.01x faster                                         |
| typing_runtime_protocols   | 116 us                                                                 | 115 us: 1.01x faster                                          |
| asyncio_tcp_ssl            | 1.80 sec                                                               | 1.79 sec: 1.01x faster                                        |
| python_startup             | 10.3 ms                                                                | 10.3 ms: 1.00x slower                                         |
| python_startup_no_site     | 8.98 ms                                                                | 8.99 ms: 1.00x slower                                         |
| regex_dna                  | 215 ms                                                                 | 215 ms: 1.00x slower                                          |
| pidigits                   | 195 ms                                                                 | 195 ms: 1.00x slower                                          |
| dulwich_log                | 65.6 ms                                                                | 65.9 ms: 1.00x slower                                         |
| docutils                   | 2.59 sec                                                               | 2.61 sec: 1.00x slower                                        |
| deepcopy                   | 346 us                                                                 | 348 us: 1.01x slower                                          |
| async_tree_io_tg           | 1.23 sec                                                               | 1.23 sec: 1.01x slower                                        |
| json_dumps                 | 10.5 ms                                                                | 10.5 ms: 1.01x slower                                         |
| sympy_sum                  | 146 ms                                                                 | 147 ms: 1.01x slower                                          |
| pycparser                  | 1.20 sec                                                               | 1.21 sec: 1.01x slower                                        |
| regex_v8                   | 25.6 ms                                                                | 25.8 ms: 1.01x slower                                         |
| pickle_pure_python         | 294 us                                                                 | 296 us: 1.01x slower                                          |
| async_tree_io              | 1.18 sec                                                               | 1.19 sec: 1.01x slower                                        |
| sympy_expand               | 449 ms                                                                 | 453 ms: 1.01x slower                                          |
| 2to3                       | 262 ms                                                                 | 264 ms: 1.01x slower                                          |
| json_loads                 | 27.6 us                                                                | 27.9 us: 1.01x slower                                         |
| raytrace                   | 273 ms                                                                 | 275 ms: 1.01x slower                                          |
| sympy_integrate            | 19.3 ms                                                                | 19.5 ms: 1.01x slower                                         |
| create_gc_cycles           | 1.46 ms                                                                | 1.47 ms: 1.01x slower                                         |
| async_generators           | 446 ms                                                                 | 449 ms: 1.01x slower                                          |
| hexiom                     | 6.08 ms                                                                | 6.14 ms: 1.01x slower                                         |
| sqlglot_transpile          | 1.59 ms                                                                | 1.61 ms: 1.01x slower                                         |
| bench_thread_pool          | 807 us                                                                 | 815 us: 1.01x slower                                          |
| comprehensions             | 16.2 us                                                                | 16.4 us: 1.01x slower                                         |
| async_tree_memoization_tg  | 595 ms                                                                 | 602 ms: 1.01x slower                                          |
| deltablue                  | 3.29 ms                                                                | 3.33 ms: 1.01x slower                                         |
| coverage                   | 94.6 ms                                                                | 95.7 ms: 1.01x slower                                         |
| chaos                      | 60.7 ms                                                                | 61.4 ms: 1.01x slower                                         |
| logging_format             | 6.38 us                                                                | 6.47 us: 1.01x slower                                         |
| pprint_pformat             | 1.49 sec                                                               | 1.51 sec: 1.01x slower                                        |
| richards_super             | 53.7 ms                                                                | 54.4 ms: 1.01x slower                                         |
| xml_etree_generate         | 85.3 ms                                                                | 86.5 ms: 1.01x slower                                         |
| mdp                        | 2.53 sec                                                               | 2.57 sec: 1.01x slower                                        |
| deepcopy_memo              | 37.8 us                                                                | 38.3 us: 1.02x slower                                         |
| chameleon                  | 6.95 ms                                                                | 7.06 ms: 1.02x slower                                         |
| sqlglot_optimize           | 53.0 ms                                                                | 53.9 ms: 1.02x slower                                         |
| xml_etree_process          | 58.5 ms                                                                | 59.4 ms: 1.02x slower                                         |
| sqlglot_normalize          | 105 ms                                                                 | 107 ms: 1.02x slower                                          |
| logging_simple             | 5.87 us                                                                | 5.97 us: 1.02x slower                                         |
| async_tree_cpu_io_mixed    | 704 ms                                                                 | 717 ms: 1.02x slower                                          |
| go                         | 140 ms                                                                 | 143 ms: 1.02x slower                                          |
| xml_etree_parse            | 158 ms                                                                 | 161 ms: 1.02x slower                                          |
| scimark_sor                | 123 ms                                                                 | 125 ms: 1.02x slower                                          |
| pprint_safe_repr           | 726 ms                                                                 | 740 ms: 1.02x slower                                          |
| fannkuch                   | 388 ms                                                                 | 396 ms: 1.02x slower                                          |
| async_tree_cpu_io_mixed_tg | 735 ms                                                                 | 750 ms: 1.02x slower                                          |
| float                      | 80.5 ms                                                                | 82.3 ms: 1.02x slower                                         |
| sympy_str                  | 266 ms                                                                 | 273 ms: 1.02x slower                                          |
| spectral_norm              | 108 ms                                                                 | 110 ms: 1.03x slower                                          |
| crypto_pyaes               | 70.3 ms                                                                | 72.2 ms: 1.03x slower                                         |
| pickle                     | 11.2 us                                                                | 11.5 us: 1.03x slower                                         |
| coroutines                 | 22.1 ms                                                                | 22.8 ms: 1.03x slower                                         |
| logging_silent             | 101 ns                                                                 | 105 ns: 1.04x slower                                          |
| generators                 | 29.1 ms                                                                | 30.2 ms: 1.04x slower                                         |
| pickle_dict                | 33.7 us                                                                | 35.2 us: 1.04x slower                                         |
| mako                       | 10.9 ms                                                                | 11.4 ms: 1.04x slower                                         |
| gc_traversal               | 3.64 ms                                                                | 3.81 ms: 1.05x slower                                         |
| unpickle                   | 14.6 us                                                                | 15.8 us: 1.09x slower                                         |
| unpack_sequence            | 42.2 ns                                                                | 48.2 ns: 1.14x slower                                         |
| Geometric mean             | (ref)                                                                  | 1.01x slower                                                  |

Benchmark hidden because not significant (25): scimark_monte_carlo, nbody, unpickle_pure_python, regex_compile, pickle_list, scimark_lu, richards, tomli_loads, scimark_fft, json, unpickle_list, bench_mp_pool, asyncio_websockets, asyncio_tcp, xml_etree_iterparse, deepcopy_reduce, meteor_contest, async_tree_none, pathlib, async_tree_none_tg, pyflate, mypy2, sqlglot_parse, tornado_http, async_tree_memoization


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
