
# Results vs. base

- fork: python
- ref: 8deb8bc2e5af0e229df8
- machine: linux-x86_64
- commit hash: 8deb8bc
- commit date: 2023-11-20
- overall geometric mean: 1.00x faster
- HPT reliability: 50.08%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231120-pythonperf2-x86_64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 | bm-20231120-pythonperf2-x86_64-python-8deb8bc2e5af0e229df8-3.13.0a1+-8deb8bc |
|----------------|:----------------------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| chameleon      | 7.33 ms                                                                      | 7.39 ms: 1.01x slower                                                        |
| docutils       | 2.82 sec                                                                     | 2.81 sec: 1.00x faster                                                       |
| Geometric mean | (ref)                                                                        | 1.00x slower                                                                 |

Benchmark hidden because not significant (2): 2to3, tornado_http

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231120-pythonperf2-x86_64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 | bm-20231120-pythonperf2-x86_64-python-8deb8bc2e5af0e229df8-3.13.0a1+-8deb8bc |
|----------------------------|:----------------------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| async_tree_cpu_io_mixed    | 696 ms                                                                       | 685 ms: 1.01x faster                                                         |
| async_tree_cpu_io_mixed_tg | 712 ms                                                                       | 704 ms: 1.01x faster                                                         |
| async_tree_none_tg         | 434 ms                                                                       | 436 ms: 1.00x slower                                                         |
| Geometric mean             | (ref)                                                                        | 1.00x faster                                                                 |

Benchmark hidden because not significant (5): async_tree_memoization, async_tree_none, async_tree_io, async_tree_io_tg, async_tree_memoization_tg

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231120-pythonperf2-x86_64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 | bm-20231120-pythonperf2-x86_64-python-8deb8bc2e5af0e229df8-3.13.0a1+-8deb8bc |
|----------------|:----------------------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| pidigits       | 265 ms                                                                       | 266 ms: 1.00x slower                                                         |
| Geometric mean | (ref)                                                                        | 1.00x faster                                                                 |

Benchmark hidden because not significant (2): float, nbody

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231120-pythonperf2-x86_64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 | bm-20231120-pythonperf2-x86_64-python-8deb8bc2e5af0e229df8-3.13.0a1+-8deb8bc |
|----------------|:----------------------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| regex_v8       | 24.9 ms                                                                      | 24.8 ms: 1.00x faster                                                        |
| regex_compile  | 142 ms                                                                       | 141 ms: 1.00x faster                                                         |
| regex_dna      | 240 ms                                                                       | 242 ms: 1.01x slower                                                         |
| regex_effbot   | 3.47 ms                                                                      | 3.51 ms: 1.01x slower                                                        |
| Geometric mean | (ref)                                                                        | 1.00x slower                                                                 |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231120-pythonperf2-x86_64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 | bm-20231120-pythonperf2-x86_64-python-8deb8bc2e5af0e229df8-3.13.0a1+-8deb8bc |
|----------------------|:----------------------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| unpickle_pure_python | 225 us                                                                       | 222 us: 1.01x faster                                                         |
| pickle_pure_python   | 307 us                                                                       | 302 us: 1.01x faster                                                         |
| xml_etree_parse      | 146 ms                                                                       | 148 ms: 1.01x slower                                                         |
| unpickle_list        | 4.60 us                                                                      | 4.66 us: 1.01x slower                                                        |
| json_dumps           | 10.5 ms                                                                      | 10.7 ms: 1.01x slower                                                        |
| pickle_list          | 4.40 us                                                                      | 4.47 us: 1.02x slower                                                        |
| tomli_loads          | 2.14 sec                                                                     | 2.18 sec: 1.02x slower                                                       |
| xml_etree_iterparse  | 105 ms                                                                       | 107 ms: 1.02x slower                                                         |
| pickle               | 9.99 us                                                                      | 10.2 us: 1.02x slower                                                        |
| xml_etree_process    | 57.4 ms                                                                      | 58.5 ms: 1.02x slower                                                        |
| xml_etree_generate   | 83.6 ms                                                                      | 85.3 ms: 1.02x slower                                                        |
| pickle_dict          | 32.4 us                                                                      | 33.1 us: 1.02x slower                                                        |
| unpickle             | 14.4 us                                                                      | 15.0 us: 1.04x slower                                                        |
| Geometric mean       | (ref)                                                                        | 1.01x slower                                                                 |

Benchmark hidden because not significant (1): json_loads

Benchmarks with tag 'startup':
==============================

Benchmark hidden because not significant (2): python_startup, python_startup_no_site

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231120-pythonperf2-x86_64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 | bm-20231120-pythonperf2-x86_64-python-8deb8bc2e5af0e229df8-3.13.0a1+-8deb8bc |
|-----------|:----------------------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| mako      | 10.3 ms                                                                      | 10.2 ms: 1.01x faster                                                        |

All benchmarks:
===============

| Benchmark                  | bm-20231120-pythonperf2-x86_64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 | bm-20231120-pythonperf2-x86_64-python-8deb8bc2e5af0e229df8-3.13.0a1+-8deb8bc |
|----------------------------|:----------------------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| unpack_sequence            | 52.6 ns                                                                      | 46.4 ns: 1.13x faster                                                        |
| scimark_sparse_mat_mult    | 4.32 ms                                                                      | 4.15 ms: 1.04x faster                                                        |
| coverage                   | 82.2 ms                                                                      | 79.7 ms: 1.03x faster                                                        |
| raytrace                   | 272 ms                                                                       | 264 ms: 1.03x faster                                                         |
| crypto_pyaes               | 71.6 ms                                                                      | 69.7 ms: 1.03x faster                                                        |
| generators                 | 35.3 ms                                                                      | 34.4 ms: 1.03x faster                                                        |
| logging_format             | 7.26 us                                                                      | 7.11 us: 1.02x faster                                                        |
| richards_super             | 58.6 ms                                                                      | 57.5 ms: 1.02x faster                                                        |
| sqlglot_parse              | 1.40 ms                                                                      | 1.37 ms: 1.02x faster                                                        |
| scimark_fft                | 308 ms                                                                       | 303 ms: 1.02x faster                                                         |
| comprehensions             | 16.6 us                                                                      | 16.3 us: 1.02x faster                                                        |
| sqlglot_transpile          | 1.80 ms                                                                      | 1.78 ms: 1.02x faster                                                        |
| async_tree_cpu_io_mixed    | 696 ms                                                                       | 685 ms: 1.01x faster                                                         |
| unpickle_pure_python       | 225 us                                                                       | 222 us: 1.01x faster                                                         |
| pickle_pure_python         | 307 us                                                                       | 302 us: 1.01x faster                                                         |
| mako                       | 10.3 ms                                                                      | 10.2 ms: 1.01x faster                                                        |
| richards                   | 52.9 ms                                                                      | 52.2 ms: 1.01x faster                                                        |
| scimark_monte_carlo        | 68.0 ms                                                                      | 67.2 ms: 1.01x faster                                                        |
| async_tree_cpu_io_mixed_tg | 712 ms                                                                       | 704 ms: 1.01x faster                                                         |
| pathlib                    | 19.0 ms                                                                      | 18.8 ms: 1.01x faster                                                        |
| chaos                      | 60.8 ms                                                                      | 60.1 ms: 1.01x faster                                                        |
| typing_runtime_protocols   | 124 us                                                                       | 123 us: 1.01x faster                                                         |
| asyncio_tcp                | 370 ms                                                                       | 368 ms: 1.01x faster                                                         |
| logging_silent             | 96.2 ns                                                                      | 95.6 ns: 1.01x faster                                                        |
| dulwich_log                | 67.9 ms                                                                      | 67.6 ms: 1.01x faster                                                        |
| telco                      | 8.11 ms                                                                      | 8.08 ms: 1.00x faster                                                        |
| regex_v8                   | 24.9 ms                                                                      | 24.8 ms: 1.00x faster                                                        |
| sympy_integrate            | 22.9 ms                                                                      | 22.8 ms: 1.00x faster                                                        |
| regex_compile              | 142 ms                                                                       | 141 ms: 1.00x faster                                                         |
| mypy2                      | 364 ms                                                                       | 363 ms: 1.00x faster                                                         |
| sqlglot_optimize           | 57.9 ms                                                                      | 57.8 ms: 1.00x faster                                                        |
| docutils                   | 2.82 sec                                                                     | 2.81 sec: 1.00x faster                                                       |
| asyncio_tcp_ssl            | 1.57 sec                                                                     | 1.57 sec: 1.00x faster                                                       |
| mdp                        | 2.50 sec                                                                     | 2.49 sec: 1.00x faster                                                       |
| pidigits                   | 265 ms                                                                       | 266 ms: 1.00x slower                                                         |
| spectral_norm              | 90.4 ms                                                                      | 90.8 ms: 1.00x slower                                                        |
| go                         | 167 ms                                                                       | 168 ms: 1.00x slower                                                         |
| async_tree_none_tg         | 434 ms                                                                       | 436 ms: 1.00x slower                                                         |
| deltablue                  | 3.57 ms                                                                      | 3.59 ms: 1.01x slower                                                        |
| meteor_contest             | 127 ms                                                                       | 128 ms: 1.01x slower                                                         |
| pprint_pformat             | 1.61 sec                                                                     | 1.61 sec: 1.01x slower                                                       |
| regex_dna                  | 240 ms                                                                       | 242 ms: 1.01x slower                                                         |
| pprint_safe_repr           | 786 ms                                                                       | 791 ms: 1.01x slower                                                         |
| hexiom                     | 6.35 ms                                                                      | 6.39 ms: 1.01x slower                                                        |
| sympy_str                  | 287 ms                                                                       | 289 ms: 1.01x slower                                                         |
| chameleon                  | 7.33 ms                                                                      | 7.39 ms: 1.01x slower                                                        |
| xml_etree_parse            | 146 ms                                                                       | 148 ms: 1.01x slower                                                         |
| deepcopy_reduce            | 3.21 us                                                                      | 3.24 us: 1.01x slower                                                        |
| dask                       | 392 ms                                                                       | 396 ms: 1.01x slower                                                         |
| fannkuch                   | 374 ms                                                                       | 378 ms: 1.01x slower                                                         |
| unpickle_list              | 4.60 us                                                                      | 4.66 us: 1.01x slower                                                        |
| sympy_sum                  | 149 ms                                                                       | 151 ms: 1.01x slower                                                         |
| regex_effbot               | 3.47 ms                                                                      | 3.51 ms: 1.01x slower                                                        |
| async_generators           | 358 ms                                                                       | 363 ms: 1.01x slower                                                         |
| json_dumps                 | 10.5 ms                                                                      | 10.7 ms: 1.01x slower                                                        |
| json                       | 5.13 ms                                                                      | 5.21 ms: 1.02x slower                                                        |
| deepcopy_memo              | 36.0 us                                                                      | 36.6 us: 1.02x slower                                                        |
| pickle_list                | 4.40 us                                                                      | 4.47 us: 1.02x slower                                                        |
| tomli_loads                | 2.14 sec                                                                     | 2.18 sec: 1.02x slower                                                       |
| xml_etree_iterparse        | 105 ms                                                                       | 107 ms: 1.02x slower                                                         |
| pickle                     | 9.99 us                                                                      | 10.2 us: 1.02x slower                                                        |
| xml_etree_process          | 57.4 ms                                                                      | 58.5 ms: 1.02x slower                                                        |
| xml_etree_generate         | 83.6 ms                                                                      | 85.3 ms: 1.02x slower                                                        |
| pickle_dict                | 32.4 us                                                                      | 33.1 us: 1.02x slower                                                        |
| scimark_lu                 | 99.9 ms                                                                      | 102 ms: 1.02x slower                                                         |
| unpickle                   | 14.4 us                                                                      | 15.0 us: 1.04x slower                                                        |
| pyflate                    | 506 ms                                                                       | 532 ms: 1.05x slower                                                         |
| Geometric mean             | (ref)                                                                        | 1.00x faster                                                                 |

Benchmark hidden because not significant (26): async_tree_memoization, pycparser, float, async_tree_none, coroutines, async_tree_io, deepcopy, json_loads, asyncio_websockets, async_tree_io_tg, async_tree_memoization_tg, python_startup, python_startup_no_site, nbody, 2to3, nqueens, sqlglot_normalize, logging_simple, sympy_expand, sqlite_synth, gc_traversal, create_gc_cycles, scimark_sor, bench_thread_pool, tornado_http, bench_mp_pool


# HPT report

- Reliability score: 50.08% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
