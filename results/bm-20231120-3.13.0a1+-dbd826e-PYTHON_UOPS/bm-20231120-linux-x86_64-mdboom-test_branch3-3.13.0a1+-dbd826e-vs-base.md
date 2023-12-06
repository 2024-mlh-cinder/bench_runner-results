
# Results vs. base

- fork: mdboom
- ref: test_branch3
- machine: linux-x86_64
- commit hash: dbd826e
- commit date: 2023-11-20
- overall geometric mean: 1.04x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.01x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231120-linux-x86_64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 | bm-20231120-linux-x86_64-mdboom-test_branch3-3.13.0a1+-dbd826e |
|----------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------:|
| 2to3           | 297 ms                                                                 | 288 ms: 1.03x faster                                           |
| chameleon      | 7.50 ms                                                                | 7.46 ms: 1.01x faster                                          |
| docutils       | 2.76 sec                                                               | 2.72 sec: 1.01x faster                                         |
| tornado_http   | 103 ms                                                                 | 99.1 ms: 1.04x faster                                          |
| Geometric mean | (ref)                                                                  | 1.02x faster                                                   |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231120-linux-x86_64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 | bm-20231120-linux-x86_64-mdboom-test_branch3-3.13.0a1+-dbd826e |
|----------------------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------:|
| async_tree_none            | 465 ms                                                                 | 452 ms: 1.03x faster                                           |
| async_tree_io              | 1.24 sec                                                               | 1.21 sec: 1.02x faster                                         |
| async_tree_none_tg         | 478 ms                                                                 | 468 ms: 1.02x faster                                           |
| async_tree_memoization     | 592 ms                                                                 | 581 ms: 1.02x faster                                           |
| async_tree_cpu_io_mixed    | 736 ms                                                                 | 725 ms: 1.02x faster                                           |
| async_tree_cpu_io_mixed_tg | 762 ms                                                                 | 752 ms: 1.01x faster                                           |
| async_tree_io_tg           | 1.26 sec                                                               | 1.25 sec: 1.01x faster                                         |
| Geometric mean             | (ref)                                                                  | 1.01x faster                                                   |

Benchmark hidden because not significant (1): async_tree_memoization_tg

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231120-linux-x86_64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 | bm-20231120-linux-x86_64-mdboom-test_branch3-3.13.0a1+-dbd826e |
|----------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------:|
| nbody          | 140 ms                                                                 | 112 ms: 1.26x faster                                           |
| float          | 115 ms                                                                 | 94.4 ms: 1.22x faster                                          |
| pidigits       | 197 ms                                                                 | 196 ms: 1.00x faster                                           |
| Geometric mean | (ref)                                                                  | 1.16x faster                                                   |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231120-linux-x86_64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 | bm-20231120-linux-x86_64-mdboom-test_branch3-3.13.0a1+-dbd826e |
|----------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------:|
| regex_v8       | 26.2 ms                                                                | 24.5 ms: 1.07x faster                                          |
| regex_compile  | 168 ms                                                                 | 160 ms: 1.05x faster                                           |
| regex_effbot   | 3.66 ms                                                                | 3.57 ms: 1.02x faster                                          |
| regex_dna      | 216 ms                                                                 | 217 ms: 1.01x slower                                           |
| Geometric mean | (ref)                                                                  | 1.03x faster                                                   |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231120-linux-x86_64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 | bm-20231120-linux-x86_64-mdboom-test_branch3-3.13.0a1+-dbd826e |
|----------------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------:|
| tomli_loads          | 2.95 sec                                                               | 2.51 sec: 1.17x faster                                         |
| xml_etree_iterparse  | 119 ms                                                                 | 114 ms: 1.04x faster                                           |
| xml_etree_process    | 64.9 ms                                                                | 63.1 ms: 1.03x faster                                          |
| unpickle_pure_python | 248 us                                                                 | 241 us: 1.03x faster                                           |
| xml_etree_generate   | 94.6 ms                                                                | 92.6 ms: 1.02x faster                                          |
| json_dumps           | 10.7 ms                                                                | 10.7 ms: 1.00x faster                                          |
| pickle_list          | 5.16 us                                                                | 5.20 us: 1.01x slower                                          |
| json_loads           | 28.2 us                                                                | 28.5 us: 1.01x slower                                          |
| pickle_pure_python   | 309 us                                                                 | 313 us: 1.01x slower                                           |
| pickle_dict          | 35.1 us                                                                | 35.5 us: 1.01x slower                                          |
| Geometric mean       | (ref)                                                                  | 1.02x faster                                                   |

Benchmark hidden because not significant (4): unpickle_list, pickle, xml_etree_parse, unpickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231120-linux-x86_64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 | bm-20231120-linux-x86_64-mdboom-test_branch3-3.13.0a1+-dbd826e |
|------------------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------:|
| python_startup_no_site | 9.05 ms                                                                | 9.05 ms: 1.00x slower                                          |
| python_startup         | 10.4 ms                                                                | 10.4 ms: 1.00x slower                                          |
| Geometric mean         | (ref)                                                                  | 1.00x slower                                                   |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231120-linux-x86_64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 | bm-20231120-linux-x86_64-mdboom-test_branch3-3.13.0a1+-dbd826e |
|-----------|:----------------------------------------------------------------------:|:--------------------------------------------------------------:|
| mako      | 17.4 ms                                                                | 14.5 ms: 1.20x faster                                          |

All benchmarks:
===============

| Benchmark                  | bm-20231120-linux-x86_64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 | bm-20231120-linux-x86_64-mdboom-test_branch3-3.13.0a1+-dbd826e |
|----------------------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------:|
| nbody                      | 140 ms                                                                 | 112 ms: 1.26x faster                                           |
| float                      | 115 ms                                                                 | 94.4 ms: 1.22x faster                                          |
| mako                       | 17.4 ms                                                                | 14.5 ms: 1.20x faster                                          |
| deltablue                  | 5.80 ms                                                                | 4.87 ms: 1.19x faster                                          |
| tomli_loads                | 2.95 sec                                                               | 2.51 sec: 1.17x faster                                         |
| comprehensions             | 26.0 us                                                                | 22.2 us: 1.17x faster                                          |
| hexiom                     | 10.3 ms                                                                | 8.90 ms: 1.16x faster                                          |
| scimark_fft                | 524 ms                                                                 | 463 ms: 1.13x faster                                           |
| scimark_monte_carlo        | 90.0 ms                                                                | 80.1 ms: 1.12x faster                                          |
| pyflate                    | 601 ms                                                                 | 543 ms: 1.11x faster                                           |
| scimark_sparse_mat_mult    | 6.88 ms                                                                | 6.23 ms: 1.10x faster                                          |
| nqueens                    | 107 ms                                                                 | 97.0 ms: 1.10x faster                                          |
| unpack_sequence            | 49.9 ns                                                                | 46.0 ns: 1.09x faster                                          |
| chaos                      | 82.0 ms                                                                | 75.6 ms: 1.08x faster                                          |
| spectral_norm              | 169 ms                                                                 | 156 ms: 1.08x faster                                           |
| crypto_pyaes               | 93.8 ms                                                                | 86.6 ms: 1.08x faster                                          |
| fannkuch                   | 502 ms                                                                 | 464 ms: 1.08x faster                                           |
| regex_v8                   | 26.2 ms                                                                | 24.5 ms: 1.07x faster                                          |
| pprint_pformat             | 1.78 sec                                                               | 1.69 sec: 1.06x faster                                         |
| pycparser                  | 1.27 sec                                                               | 1.20 sec: 1.06x faster                                         |
| raytrace                   | 326 ms                                                                 | 309 ms: 1.05x faster                                           |
| pprint_safe_repr           | 854 ms                                                                 | 812 ms: 1.05x faster                                           |
| regex_compile              | 168 ms                                                                 | 160 ms: 1.05x faster                                           |
| deepcopy_memo              | 43.0 us                                                                | 41.1 us: 1.05x faster                                          |
| telco                      | 9.02 ms                                                                | 8.64 ms: 1.04x faster                                          |
| logging_silent             | 112 ns                                                                 | 108 ns: 1.04x faster                                           |
| meteor_contest             | 122 ms                                                                 | 118 ms: 1.04x faster                                           |
| go                         | 170 ms                                                                 | 163 ms: 1.04x faster                                           |
| xml_etree_iterparse        | 119 ms                                                                 | 114 ms: 1.04x faster                                           |
| tornado_http               | 103 ms                                                                 | 99.1 ms: 1.04x faster                                          |
| typing_runtime_protocols   | 129 us                                                                 | 124 us: 1.04x faster                                           |
| sympy_integrate            | 22.2 ms                                                                | 21.4 ms: 1.04x faster                                          |
| sqlglot_optimize           | 60.6 ms                                                                | 58.6 ms: 1.03x faster                                          |
| sympy_str                  | 306 ms                                                                 | 296 ms: 1.03x faster                                           |
| sympy_sum                  | 166 ms                                                                 | 161 ms: 1.03x faster                                           |
| 2to3                       | 297 ms                                                                 | 288 ms: 1.03x faster                                           |
| async_tree_none            | 465 ms                                                                 | 452 ms: 1.03x faster                                           |
| xml_etree_process          | 64.9 ms                                                                | 63.1 ms: 1.03x faster                                          |
| scimark_lu                 | 124 ms                                                                 | 120 ms: 1.03x faster                                           |
| richards_super             | 58.8 ms                                                                | 57.2 ms: 1.03x faster                                          |
| unpickle_pure_python       | 248 us                                                                 | 241 us: 1.03x faster                                           |
| async_tree_io              | 1.24 sec                                                               | 1.21 sec: 1.02x faster                                         |
| regex_effbot               | 3.66 ms                                                                | 3.57 ms: 1.02x faster                                          |
| async_tree_none_tg         | 478 ms                                                                 | 468 ms: 1.02x faster                                           |
| xml_etree_generate         | 94.6 ms                                                                | 92.6 ms: 1.02x faster                                          |
| sqlglot_normalize          | 118 ms                                                                 | 115 ms: 1.02x faster                                           |
| deepcopy_reduce            | 3.22 us                                                                | 3.15 us: 1.02x faster                                          |
| sympy_expand               | 501 ms                                                                 | 491 ms: 1.02x faster                                           |
| sqlglot_parse              | 1.41 ms                                                                | 1.38 ms: 1.02x faster                                          |
| async_tree_memoization     | 592 ms                                                                 | 581 ms: 1.02x faster                                           |
| sqlite_synth               | 2.95 us                                                                | 2.89 us: 1.02x faster                                          |
| richards                   | 51.7 ms                                                                | 50.8 ms: 1.02x faster                                          |
| sqlglot_transpile          | 1.74 ms                                                                | 1.71 ms: 1.02x faster                                          |
| async_tree_cpu_io_mixed    | 736 ms                                                                 | 725 ms: 1.02x faster                                           |
| logging_simple             | 6.24 us                                                                | 6.15 us: 1.01x faster                                          |
| deepcopy                   | 366 us                                                                 | 361 us: 1.01x faster                                           |
| docutils                   | 2.76 sec                                                               | 2.72 sec: 1.01x faster                                         |
| mypy2                      | 361 ms                                                                 | 357 ms: 1.01x faster                                           |
| async_tree_cpu_io_mixed_tg | 762 ms                                                                 | 752 ms: 1.01x faster                                           |
| pathlib                    | 18.9 ms                                                                | 18.7 ms: 1.01x faster                                          |
| async_tree_io_tg           | 1.26 sec                                                               | 1.25 sec: 1.01x faster                                         |
| bench_thread_pool          | 866 us                                                                 | 858 us: 1.01x faster                                           |
| logging_format             | 7.03 us                                                                | 6.98 us: 1.01x faster                                          |
| dulwich_log                | 70.1 ms                                                                | 69.6 ms: 1.01x faster                                          |
| chameleon                  | 7.50 ms                                                                | 7.46 ms: 1.01x faster                                          |
| pidigits                   | 197 ms                                                                 | 196 ms: 1.00x faster                                           |
| json_dumps                 | 10.7 ms                                                                | 10.7 ms: 1.00x faster                                          |
| asyncio_tcp_ssl            | 1.82 sec                                                               | 1.81 sec: 1.00x faster                                         |
| python_startup_no_site     | 9.05 ms                                                                | 9.05 ms: 1.00x slower                                          |
| python_startup             | 10.4 ms                                                                | 10.4 ms: 1.00x slower                                          |
| generators                 | 29.6 ms                                                                | 29.7 ms: 1.01x slower                                          |
| json                       | 5.16 ms                                                                | 5.18 ms: 1.01x slower                                          |
| regex_dna                  | 216 ms                                                                 | 217 ms: 1.01x slower                                           |
| pickle_list                | 5.16 us                                                                | 5.20 us: 1.01x slower                                          |
| json_loads                 | 28.2 us                                                                | 28.5 us: 1.01x slower                                          |
| pickle_pure_python         | 309 us                                                                 | 313 us: 1.01x slower                                           |
| create_gc_cycles           | 1.46 ms                                                                | 1.48 ms: 1.01x slower                                          |
| pickle_dict                | 35.1 us                                                                | 35.5 us: 1.01x slower                                          |
| mdp                        | 2.75 sec                                                               | 2.82 sec: 1.02x slower                                         |
| gc_traversal               | 3.67 ms                                                                | 3.83 ms: 1.04x slower                                          |
| coroutines                 | 21.5 ms                                                                | 22.7 ms: 1.06x slower                                          |
| Geometric mean             | (ref)                                                                  | 1.04x faster                                                   |

Benchmark hidden because not significant (12): dask, coverage, unpickle_list, async_generators, asyncio_websockets, bench_mp_pool, asyncio_tcp, pickle, xml_etree_parse, scimark_sor, unpickle, async_tree_memoization_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.01x
- 95% likely to have a speedup of 1.01x
- 99% likely to have a speedup of 1.01x
