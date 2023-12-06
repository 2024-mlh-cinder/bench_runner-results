
# Results vs. base

- fork: iritkatriel
- ref: gen_yf
- machine: linux-x86_64
- commit hash: 309abda
- commit date: 2023-11-02
- overall geometric mean: 1.01x slower \*
- HPT reliability: 98.55%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231102-linux-x86_64-python-6a0d7b43df12ab4426ba-3.13.0a1+-6a0d7b4 | bm-20231102-linux-x86_64-iritkatriel-gen_yf-3.13.0a1+-309abda |
|----------------|:----------------------------------------------------------------------:|:-------------------------------------------------------------:|
| 2to3           | 262 ms                                                                 | 264 ms: 1.01x slower                                          |
| docutils       | 2.59 sec                                                               | 2.60 sec: 1.00x slower                                        |
| Geometric mean | (ref)                                                                  | 1.00x slower                                                  |

Benchmark hidden because not significant (2): chameleon, tornado_http

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231102-linux-x86_64-python-6a0d7b43df12ab4426ba-3.13.0a1+-6a0d7b4 | bm-20231102-linux-x86_64-iritkatriel-gen_yf-3.13.0a1+-309abda |
|----------------------------|:----------------------------------------------------------------------:|:-------------------------------------------------------------:|
| async_tree_cpu_io_mixed    | 704 ms                                                                 | 713 ms: 1.01x slower                                          |
| async_tree_cpu_io_mixed_tg | 735 ms                                                                 | 744 ms: 1.01x slower                                          |
| Geometric mean             | (ref)                                                                  | 1.00x slower                                                  |

Benchmark hidden because not significant (6): async_tree_io_tg, async_tree_none_tg, async_tree_memoization_tg, async_tree_io, async_tree_none, async_tree_memoization

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231102-linux-x86_64-python-6a0d7b43df12ab4426ba-3.13.0a1+-6a0d7b4 | bm-20231102-linux-x86_64-iritkatriel-gen_yf-3.13.0a1+-309abda |
|----------------|:----------------------------------------------------------------------:|:-------------------------------------------------------------:|
| pidigits       | 195 ms                                                                 | 187 ms: 1.04x faster                                          |
| float          | 80.5 ms                                                                | 81.7 ms: 1.02x slower                                         |
| nbody          | 88.5 ms                                                                | 91.3 ms: 1.03x slower                                         |
| Geometric mean | (ref)                                                                  | 1.00x slower                                                  |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231102-linux-x86_64-python-6a0d7b43df12ab4426ba-3.13.0a1+-6a0d7b4 | bm-20231102-linux-x86_64-iritkatriel-gen_yf-3.13.0a1+-309abda |
|----------------|:----------------------------------------------------------------------:|:-------------------------------------------------------------:|
| regex_v8       | 25.6 ms                                                                | 25.5 ms: 1.01x faster                                         |
| regex_dna      | 215 ms                                                                 | 217 ms: 1.01x slower                                          |
| regex_effbot   | 3.61 ms                                                                | 3.68 ms: 1.02x slower                                         |
| Geometric mean | (ref)                                                                  | 1.00x slower                                                  |

Benchmark hidden because not significant (1): regex_compile

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231102-linux-x86_64-python-6a0d7b43df12ab4426ba-3.13.0a1+-6a0d7b4 | bm-20231102-linux-x86_64-iritkatriel-gen_yf-3.13.0a1+-309abda |
|----------------------|:----------------------------------------------------------------------:|:-------------------------------------------------------------:|
| xml_etree_iterparse  | 107 ms                                                                 | 105 ms: 1.02x faster                                          |
| unpickle_pure_python | 218 us                                                                 | 215 us: 1.01x faster                                          |
| json_loads           | 27.6 us                                                                | 27.8 us: 1.00x slower                                         |
| unpickle_list        | 5.16 us                                                                | 5.19 us: 1.01x slower                                         |
| tomli_loads          | 2.15 sec                                                               | 2.17 sec: 1.01x slower                                        |
| xml_etree_parse      | 158 ms                                                                 | 159 ms: 1.01x slower                                          |
| xml_etree_generate   | 85.3 ms                                                                | 86.2 ms: 1.01x slower                                         |
| pickle_list          | 5.05 us                                                                | 5.11 us: 1.01x slower                                         |
| xml_etree_process    | 58.5 ms                                                                | 59.3 ms: 1.01x slower                                         |
| pickle               | 11.2 us                                                                | 11.5 us: 1.03x slower                                         |
| pickle_dict          | 33.7 us                                                                | 36.0 us: 1.07x slower                                         |
| unpickle             | 14.6 us                                                                | 15.8 us: 1.08x slower                                         |
| Geometric mean       | (ref)                                                                  | 1.02x slower                                                  |

Benchmark hidden because not significant (2): pickle_pure_python, json_dumps

Benchmarks with tag 'startup':
==============================

| Benchmark      | bm-20231102-linux-x86_64-python-6a0d7b43df12ab4426ba-3.13.0a1+-6a0d7b4 | bm-20231102-linux-x86_64-iritkatriel-gen_yf-3.13.0a1+-309abda |
|----------------|:----------------------------------------------------------------------:|:-------------------------------------------------------------:|
| python_startup | 10.3 ms                                                                | 10.3 ms: 1.00x faster                                         |
| Geometric mean | (ref)                                                                  | 1.00x faster                                                  |

Benchmark hidden because not significant (1): python_startup_no_site

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231102-linux-x86_64-python-6a0d7b43df12ab4426ba-3.13.0a1+-6a0d7b4 | bm-20231102-linux-x86_64-iritkatriel-gen_yf-3.13.0a1+-309abda |
|-----------|:----------------------------------------------------------------------:|:-------------------------------------------------------------:|
| mako      | 10.9 ms                                                                | 11.4 ms: 1.05x slower                                         |

All benchmarks:
===============

| Benchmark                  | bm-20231102-linux-x86_64-python-6a0d7b43df12ab4426ba-3.13.0a1+-6a0d7b4 | bm-20231102-linux-x86_64-iritkatriel-gen_yf-3.13.0a1+-309abda |
|----------------------------|:----------------------------------------------------------------------:|:-------------------------------------------------------------:|
| pidigits                   | 195 ms                                                                 | 187 ms: 1.04x faster                                          |
| pyflate                    | 466 ms                                                                 | 452 ms: 1.03x faster                                          |
| pycparser                  | 1.20 sec                                                               | 1.17 sec: 1.03x faster                                        |
| scimark_sparse_mat_mult    | 4.91 ms                                                                | 4.79 ms: 1.03x faster                                         |
| meteor_contest             | 109 ms                                                                 | 106 ms: 1.02x faster                                          |
| nqueens                    | 79.8 ms                                                                | 78.3 ms: 1.02x faster                                         |
| xml_etree_iterparse        | 107 ms                                                                 | 105 ms: 1.02x faster                                          |
| scimark_lu                 | 115 ms                                                                 | 114 ms: 1.02x faster                                          |
| scimark_monte_carlo        | 68.5 ms                                                                | 67.5 ms: 1.02x faster                                         |
| unpickle_pure_python       | 218 us                                                                 | 215 us: 1.01x faster                                          |
| telco                      | 8.42 ms                                                                | 8.31 ms: 1.01x faster                                         |
| logging_simple             | 5.87 us                                                                | 5.82 us: 1.01x faster                                         |
| deepcopy_reduce            | 3.08 us                                                                | 3.06 us: 1.01x faster                                         |
| sqlglot_parse              | 1.28 ms                                                                | 1.28 ms: 1.01x faster                                         |
| sympy_expand               | 449 ms                                                                 | 447 ms: 1.01x faster                                          |
| typing_runtime_protocols   | 116 us                                                                 | 115 us: 1.01x faster                                          |
| regex_v8                   | 25.6 ms                                                                | 25.5 ms: 1.01x faster                                         |
| hexiom                     | 6.08 ms                                                                | 6.05 ms: 1.01x faster                                         |
| asyncio_tcp_ssl            | 1.80 sec                                                               | 1.79 sec: 1.00x faster                                        |
| asyncio_tcp                | 483 ms                                                                 | 482 ms: 1.00x faster                                          |
| sqlglot_normalize          | 105 ms                                                                 | 105 ms: 1.00x faster                                          |
| python_startup             | 10.3 ms                                                                | 10.3 ms: 1.00x faster                                         |
| deepcopy                   | 346 us                                                                 | 347 us: 1.00x slower                                          |
| async_generators           | 446 ms                                                                 | 448 ms: 1.00x slower                                          |
| docutils                   | 2.59 sec                                                               | 2.60 sec: 1.00x slower                                        |
| json_loads                 | 27.6 us                                                                | 27.8 us: 1.00x slower                                         |
| bench_thread_pool          | 807 us                                                                 | 811 us: 1.01x slower                                          |
| unpickle_list              | 5.16 us                                                                | 5.19 us: 1.01x slower                                         |
| tomli_loads                | 2.15 sec                                                               | 2.17 sec: 1.01x slower                                        |
| xml_etree_parse            | 158 ms                                                                 | 159 ms: 1.01x slower                                          |
| 2to3                       | 262 ms                                                                 | 264 ms: 1.01x slower                                          |
| comprehensions             | 16.2 us                                                                | 16.3 us: 1.01x slower                                         |
| chaos                      | 60.7 ms                                                                | 61.2 ms: 1.01x slower                                         |
| logging_format             | 6.38 us                                                                | 6.44 us: 1.01x slower                                         |
| regex_dna                  | 215 ms                                                                 | 217 ms: 1.01x slower                                          |
| pathlib                    | 18.9 ms                                                                | 19.1 ms: 1.01x slower                                         |
| xml_etree_generate         | 85.3 ms                                                                | 86.2 ms: 1.01x slower                                         |
| fannkuch                   | 388 ms                                                                 | 392 ms: 1.01x slower                                          |
| pickle_list                | 5.05 us                                                                | 5.11 us: 1.01x slower                                         |
| crypto_pyaes               | 70.3 ms                                                                | 71.2 ms: 1.01x slower                                         |
| async_tree_cpu_io_mixed    | 704 ms                                                                 | 713 ms: 1.01x slower                                          |
| async_tree_cpu_io_mixed_tg | 735 ms                                                                 | 744 ms: 1.01x slower                                          |
| generators                 | 29.1 ms                                                                | 29.5 ms: 1.01x slower                                         |
| raytrace                   | 273 ms                                                                 | 277 ms: 1.01x slower                                          |
| go                         | 140 ms                                                                 | 142 ms: 1.01x slower                                          |
| xml_etree_process          | 58.5 ms                                                                | 59.3 ms: 1.01x slower                                         |
| float                      | 80.5 ms                                                                | 81.7 ms: 1.02x slower                                         |
| regex_effbot               | 3.61 ms                                                                | 3.68 ms: 1.02x slower                                         |
| deepcopy_memo              | 37.8 us                                                                | 38.4 us: 1.02x slower                                         |
| create_gc_cycles           | 1.46 ms                                                                | 1.49 ms: 1.02x slower                                         |
| deltablue                  | 3.29 ms                                                                | 3.37 ms: 1.02x slower                                         |
| spectral_norm              | 108 ms                                                                 | 110 ms: 1.02x slower                                          |
| pickle                     | 11.2 us                                                                | 11.5 us: 1.03x slower                                         |
| nbody                      | 88.5 ms                                                                | 91.3 ms: 1.03x slower                                         |
| coroutines                 | 22.1 ms                                                                | 22.8 ms: 1.03x slower                                         |
| scimark_fft                | 363 ms                                                                 | 376 ms: 1.04x slower                                          |
| logging_silent             | 101 ns                                                                 | 105 ns: 1.04x slower                                          |
| mako                       | 10.9 ms                                                                | 11.4 ms: 1.05x slower                                         |
| gc_traversal               | 3.64 ms                                                                | 3.82 ms: 1.05x slower                                         |
| pickle_dict                | 33.7 us                                                                | 36.0 us: 1.07x slower                                         |
| unpickle                   | 14.6 us                                                                | 15.8 us: 1.08x slower                                         |
| unpack_sequence            | 42.2 ns                                                                | 53.9 ns: 1.28x slower                                         |
| Geometric mean             | (ref)                                                                  | 1.01x slower                                                  |

Benchmark hidden because not significant (30): richards, regex_compile, coverage, json, pickle_pure_python, sqlglot_transpile, bench_mp_pool, pprint_pformat, scimark_sor, asyncio_websockets, python_startup_no_site, sqlite_synth, sympy_integrate, async_tree_io_tg, sympy_sum, dulwich_log, mdp, sqlglot_optimize, async_tree_none_tg, chameleon, richards_super, sympy_str, mypy2, async_tree_memoization_tg, async_tree_io, async_tree_none, json_dumps, pprint_safe_repr, async_tree_memoization, tornado_http


# HPT report

- Reliability score: 98.55% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
