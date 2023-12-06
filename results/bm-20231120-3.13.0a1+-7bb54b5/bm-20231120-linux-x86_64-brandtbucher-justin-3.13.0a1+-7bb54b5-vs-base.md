
# Results vs. base

- fork: brandtbucher
- ref: justin
- machine: linux-x86_64
- commit hash: 7bb54b5
- commit date: 2023-11-20
- overall geometric mean: 1.03x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.02x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231120-linux-x86_64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 | bm-20231120-linux-x86_64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|----------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------:|
| 2to3           | 265 ms                                                                 | 274 ms: 1.04x slower                                           |
| chameleon      | 6.97 ms                                                                | 7.12 ms: 1.02x slower                                          |
| docutils       | 2.60 sec                                                               | 2.65 sec: 1.02x slower                                         |
| tornado_http   | 95.3 ms                                                                | 96.9 ms: 1.02x slower                                          |
| Geometric mean | (ref)                                                                  | 1.02x slower                                                   |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231120-linux-x86_64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 | bm-20231120-linux-x86_64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|----------------------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------:|
| async_tree_io_tg           | 1.23 sec                                                               | 1.24 sec: 1.01x slower                                         |
| async_tree_io              | 1.19 sec                                                               | 1.20 sec: 1.01x slower                                         |
| async_tree_cpu_io_mixed    | 708 ms                                                                 | 720 ms: 1.02x slower                                           |
| async_tree_cpu_io_mixed_tg | 737 ms                                                                 | 750 ms: 1.02x slower                                           |
| async_tree_memoization     | 564 ms                                                                 | 574 ms: 1.02x slower                                           |
| async_tree_none_tg         | 455 ms                                                                 | 464 ms: 1.02x slower                                           |
| async_tree_memoization_tg  | 596 ms                                                                 | 610 ms: 1.02x slower                                           |
| async_tree_none            | 437 ms                                                                 | 448 ms: 1.02x slower                                           |
| Geometric mean             | (ref)                                                                  | 1.02x slower                                                   |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231120-linux-x86_64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 | bm-20231120-linux-x86_64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|----------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------:|
| pidigits       | 187 ms                                                                 | 195 ms: 1.04x slower                                           |
| float          | 81.2 ms                                                                | 86.6 ms: 1.07x slower                                          |
| nbody          | 91.1 ms                                                                | 101 ms: 1.11x slower                                           |
| Geometric mean | (ref)                                                                  | 1.07x slower                                                   |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231120-linux-x86_64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 | bm-20231120-linux-x86_64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|----------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------:|
| regex_v8       | 25.6 ms                                                                | 24.6 ms: 1.04x faster                                          |
| regex_effbot   | 3.54 ms                                                                | 3.60 ms: 1.02x slower                                          |
| regex_dna      | 215 ms                                                                 | 221 ms: 1.03x slower                                           |
| regex_compile  | 135 ms                                                                 | 142 ms: 1.05x slower                                           |
| Geometric mean | (ref)                                                                  | 1.01x slower                                                   |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231120-linux-x86_64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 | bm-20231120-linux-x86_64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|----------------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------:|
| pickle_list          | 5.28 us                                                                | 5.00 us: 1.06x faster                                          |
| pickle               | 11.6 us                                                                | 11.4 us: 1.02x faster                                          |
| pickle_dict          | 35.9 us                                                                | 35.7 us: 1.01x faster                                          |
| xml_etree_parse      | 158 ms                                                                 | 160 ms: 1.01x slower                                           |
| pickle_pure_python   | 302 us                                                                 | 305 us: 1.01x slower                                           |
| json_dumps           | 10.4 ms                                                                | 10.5 ms: 1.01x slower                                          |
| tomli_loads          | 2.13 sec                                                               | 2.20 sec: 1.03x slower                                         |
| unpickle_list        | 5.14 us                                                                | 5.32 us: 1.03x slower                                          |
| xml_etree_process    | 59.0 ms                                                                | 61.1 ms: 1.04x slower                                          |
| xml_etree_iterparse  | 106 ms                                                                 | 110 ms: 1.04x slower                                           |
| xml_etree_generate   | 86.3 ms                                                                | 89.8 ms: 1.04x slower                                          |
| unpickle_pure_python | 220 us                                                                 | 232 us: 1.05x slower                                           |
| unpickle             | 14.6 us                                                                | 15.9 us: 1.09x slower                                          |
| Geometric mean       | (ref)                                                                  | 1.02x slower                                                   |

Benchmark hidden because not significant (1): json_loads

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231120-linux-x86_64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 | bm-20231120-linux-x86_64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|------------------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------:|
| python_startup         | 10.3 ms                                                                | 10.5 ms: 1.02x slower                                          |
| python_startup_no_site | 8.93 ms                                                                | 9.14 ms: 1.02x slower                                          |
| Geometric mean         | (ref)                                                                  | 1.02x slower                                                   |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231120-linux-x86_64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 | bm-20231120-linux-x86_64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|-----------|:----------------------------------------------------------------------:|:--------------------------------------------------------------:|
| mako      | 11.4 ms                                                                | 12.4 ms: 1.09x slower                                          |

All benchmarks:
===============

| Benchmark                  | bm-20231120-linux-x86_64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 | bm-20231120-linux-x86_64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|----------------------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------:|
| unpack_sequence            | 51.2 ns                                                                | 44.3 ns: 1.16x faster                                          |
| pickle_list                | 5.28 us                                                                | 5.00 us: 1.06x faster                                          |
| richards_super             | 54.2 ms                                                                | 51.7 ms: 1.05x faster                                          |
| richards                   | 48.5 ms                                                                | 46.7 ms: 1.04x faster                                          |
| regex_v8                   | 25.6 ms                                                                | 24.6 ms: 1.04x faster                                          |
| pycparser                  | 1.21 sec                                                               | 1.17 sec: 1.04x faster                                         |
| pickle                     | 11.6 us                                                                | 11.4 us: 1.02x faster                                          |
| coroutines                 | 22.4 ms                                                                | 22.0 ms: 1.02x faster                                          |
| pickle_dict                | 35.9 us                                                                | 35.7 us: 1.01x faster                                          |
| generators                 | 29.6 ms                                                                | 29.8 ms: 1.00x slower                                          |
| dulwich_log                | 66.1 ms                                                                | 66.4 ms: 1.00x slower                                          |
| xml_etree_parse            | 158 ms                                                                 | 160 ms: 1.01x slower                                           |
| pickle_pure_python         | 302 us                                                                 | 305 us: 1.01x slower                                           |
| async_tree_io_tg           | 1.23 sec                                                               | 1.24 sec: 1.01x slower                                         |
| asyncio_tcp_ssl            | 1.79 sec                                                               | 1.81 sec: 1.01x slower                                         |
| asyncio_tcp                | 489 ms                                                                 | 494 ms: 1.01x slower                                           |
| scimark_sor                | 124 ms                                                                 | 125 ms: 1.01x slower                                           |
| dask                       | 361 ms                                                                 | 366 ms: 1.01x slower                                           |
| json_dumps                 | 10.4 ms                                                                | 10.5 ms: 1.01x slower                                          |
| async_tree_io              | 1.19 sec                                                               | 1.20 sec: 1.01x slower                                         |
| async_tree_cpu_io_mixed    | 708 ms                                                                 | 720 ms: 1.02x slower                                           |
| regex_effbot               | 3.54 ms                                                                | 3.60 ms: 1.02x slower                                          |
| tornado_http               | 95.3 ms                                                                | 96.9 ms: 1.02x slower                                          |
| async_tree_cpu_io_mixed_tg | 737 ms                                                                 | 750 ms: 1.02x slower                                           |
| async_tree_memoization     | 564 ms                                                                 | 574 ms: 1.02x slower                                           |
| logging_silent             | 108 ns                                                                 | 110 ns: 1.02x slower                                           |
| deepcopy_reduce            | 3.07 us                                                                | 3.13 us: 1.02x slower                                          |
| bench_thread_pool          | 835 us                                                                 | 852 us: 1.02x slower                                           |
| docutils                   | 2.60 sec                                                               | 2.65 sec: 1.02x slower                                         |
| async_tree_none_tg         | 455 ms                                                                 | 464 ms: 1.02x slower                                           |
| chameleon                  | 6.97 ms                                                                | 7.12 ms: 1.02x slower                                          |
| python_startup             | 10.3 ms                                                                | 10.5 ms: 1.02x slower                                          |
| async_tree_memoization_tg  | 596 ms                                                                 | 610 ms: 1.02x slower                                           |
| python_startup_no_site     | 8.93 ms                                                                | 9.14 ms: 1.02x slower                                          |
| async_tree_none            | 437 ms                                                                 | 448 ms: 1.02x slower                                           |
| scimark_fft                | 373 ms                                                                 | 384 ms: 1.03x slower                                           |
| tomli_loads                | 2.13 sec                                                               | 2.20 sec: 1.03x slower                                         |
| regex_dna                  | 215 ms                                                                 | 221 ms: 1.03x slower                                           |
| pathlib                    | 18.1 ms                                                                | 18.6 ms: 1.03x slower                                          |
| sqlglot_normalize          | 106 ms                                                                 | 109 ms: 1.03x slower                                           |
| mypy2                      | 341 ms                                                                 | 352 ms: 1.03x slower                                           |
| unpickle_list              | 5.14 us                                                                | 5.32 us: 1.03x slower                                          |
| xml_etree_process          | 59.0 ms                                                                | 61.1 ms: 1.04x slower                                          |
| 2to3                       | 265 ms                                                                 | 274 ms: 1.04x slower                                           |
| deepcopy                   | 348 us                                                                 | 361 us: 1.04x slower                                           |
| xml_etree_iterparse        | 106 ms                                                                 | 110 ms: 1.04x slower                                           |
| typing_runtime_protocols   | 117 us                                                                 | 121 us: 1.04x slower                                           |
| logging_format             | 6.20 us                                                                | 6.43 us: 1.04x slower                                          |
| deepcopy_memo              | 38.9 us                                                                | 40.3 us: 1.04x slower                                          |
| pprint_safe_repr           | 735 ms                                                                 | 764 ms: 1.04x slower                                           |
| xml_etree_generate         | 86.3 ms                                                                | 89.8 ms: 1.04x slower                                          |
| meteor_contest             | 107 ms                                                                 | 111 ms: 1.04x slower                                           |
| gc_traversal               | 3.79 ms                                                                | 3.95 ms: 1.04x slower                                          |
| logging_simple             | 5.63 us                                                                | 5.87 us: 1.04x slower                                          |
| pidigits                   | 187 ms                                                                 | 195 ms: 1.04x slower                                           |
| sqlglot_optimize           | 53.2 ms                                                                | 55.6 ms: 1.04x slower                                          |
| raytrace                   | 276 ms                                                                 | 288 ms: 1.04x slower                                           |
| sqlglot_transpile          | 1.58 ms                                                                | 1.65 ms: 1.05x slower                                          |
| sympy_expand               | 450 ms                                                                 | 471 ms: 1.05x slower                                           |
| async_generators           | 444 ms                                                                 | 465 ms: 1.05x slower                                           |
| sqlglot_parse              | 1.27 ms                                                                | 1.33 ms: 1.05x slower                                          |
| go                         | 144 ms                                                                 | 151 ms: 1.05x slower                                           |
| pprint_pformat             | 1.49 sec                                                               | 1.57 sec: 1.05x slower                                         |
| regex_compile              | 135 ms                                                                 | 142 ms: 1.05x slower                                           |
| unpickle_pure_python       | 220 us                                                                 | 232 us: 1.05x slower                                           |
| sympy_str                  | 267 ms                                                                 | 282 ms: 1.06x slower                                           |
| pyflate                    | 467 ms                                                                 | 498 ms: 1.07x slower                                           |
| float                      | 81.2 ms                                                                | 86.6 ms: 1.07x slower                                          |
| sympy_sum                  | 147 ms                                                                 | 157 ms: 1.07x slower                                           |
| scimark_sparse_mat_mult    | 5.02 ms                                                                | 5.39 ms: 1.07x slower                                          |
| sympy_integrate            | 19.4 ms                                                                | 20.9 ms: 1.07x slower                                          |
| chaos                      | 61.7 ms                                                                | 66.8 ms: 1.08x slower                                          |
| fannkuch                   | 397 ms                                                                 | 430 ms: 1.08x slower                                           |
| unpickle                   | 14.6 us                                                                | 15.9 us: 1.09x slower                                          |
| scimark_monte_carlo        | 69.4 ms                                                                | 75.7 ms: 1.09x slower                                          |
| mako                       | 11.4 ms                                                                | 12.4 ms: 1.09x slower                                          |
| crypto_pyaes               | 71.7 ms                                                                | 78.3 ms: 1.09x slower                                          |
| mdp                        | 2.57 sec                                                               | 2.82 sec: 1.09x slower                                         |
| nbody                      | 91.1 ms                                                                | 101 ms: 1.11x slower                                           |
| nqueens                    | 81.2 ms                                                                | 91.1 ms: 1.12x slower                                          |
| comprehensions             | 16.4 us                                                                | 19.3 us: 1.17x slower                                          |
| hexiom                     | 6.28 ms                                                                | 7.53 ms: 1.20x slower                                          |
| deltablue                  | 3.36 ms                                                                | 4.05 ms: 1.21x slower                                          |
| spectral_norm              | 114 ms                                                                 | 138 ms: 1.21x slower                                           |
| Geometric mean             | (ref)                                                                  | 1.03x slower                                                   |

Benchmark hidden because not significant (9): json, json_loads, telco, bench_mp_pool, create_gc_cycles, asyncio_websockets, sqlite_synth, scimark_lu, coverage


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.02x
- 95% likely to have a slowdown of 1.02x
- 99% likely to have a slowdown of 1.02x
