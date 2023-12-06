
# Results vs. base

- fork: brandtbucher
- ref: justin
- machine: linux-x86_64
- commit hash: 7bb54b5
- commit date: 2023-11-20
- overall geometric mean: 1.08x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.03x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231120-linux-x86_64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 | bm-20231120-linux-x86_64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|----------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------:|
| 2to3           | 297 ms                                                                 | 273 ms: 1.09x faster                                           |
| chameleon      | 7.50 ms                                                                | 7.11 ms: 1.05x faster                                          |
| docutils       | 2.76 sec                                                               | 2.66 sec: 1.04x faster                                         |
| tornado_http   | 103 ms                                                                 | 96.5 ms: 1.07x faster                                          |
| Geometric mean | (ref)                                                                  | 1.06x faster                                                   |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231120-linux-x86_64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 | bm-20231120-linux-x86_64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|----------------------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------:|
| async_tree_none            | 465 ms                                                                 | 443 ms: 1.05x faster                                           |
| async_tree_none_tg         | 478 ms                                                                 | 458 ms: 1.04x faster                                           |
| async_tree_memoization     | 592 ms                                                                 | 571 ms: 1.04x faster                                           |
| async_tree_io              | 1.24 sec                                                               | 1.20 sec: 1.03x faster                                         |
| async_tree_cpu_io_mixed    | 736 ms                                                                 | 718 ms: 1.02x faster                                           |
| async_tree_io_tg           | 1.26 sec                                                               | 1.23 sec: 1.02x faster                                         |
| async_tree_cpu_io_mixed_tg | 762 ms                                                                 | 747 ms: 1.02x faster                                           |
| Geometric mean             | (ref)                                                                  | 1.03x faster                                                   |

Benchmark hidden because not significant (1): async_tree_memoization_tg

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231120-linux-x86_64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 | bm-20231120-linux-x86_64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|----------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------:|
| nbody          | 140 ms                                                                 | 100 ms: 1.40x faster                                           |
| float          | 115 ms                                                                 | 85.0 ms: 1.36x faster                                          |
| pidigits       | 197 ms                                                                 | 188 ms: 1.05x faster                                           |
| Geometric mean | (ref)                                                                  | 1.26x faster                                                   |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231120-linux-x86_64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 | bm-20231120-linux-x86_64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|----------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------:|
| regex_compile  | 168 ms                                                                 | 141 ms: 1.19x faster                                           |
| regex_v8       | 26.2 ms                                                                | 24.3 ms: 1.08x faster                                          |
| regex_effbot   | 3.66 ms                                                                | 3.63 ms: 1.01x faster                                          |
| Geometric mean | (ref)                                                                  | 1.07x faster                                                   |

Benchmark hidden because not significant (1): regex_dna

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231120-linux-x86_64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 | bm-20231120-linux-x86_64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|----------------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------:|
| tomli_loads          | 2.95 sec                                                               | 2.21 sec: 1.34x faster                                         |
| xml_etree_iterparse  | 119 ms                                                                 | 110 ms: 1.08x faster                                           |
| unpickle_pure_python | 248 us                                                                 | 232 us: 1.07x faster                                           |
| xml_etree_process    | 64.9 ms                                                                | 61.0 ms: 1.06x faster                                          |
| xml_etree_generate   | 94.6 ms                                                                | 89.1 ms: 1.06x faster                                          |
| pickle_list          | 5.16 us                                                                | 4.89 us: 1.06x faster                                          |
| pickle               | 11.7 us                                                                | 11.2 us: 1.04x faster                                          |
| pickle_dict          | 35.1 us                                                                | 34.0 us: 1.03x faster                                          |
| json_dumps           | 10.7 ms                                                                | 10.6 ms: 1.01x faster                                          |
| json_loads           | 28.2 us                                                                | 28.4 us: 1.00x slower                                          |
| xml_etree_parse      | 159 ms                                                                 | 160 ms: 1.01x slower                                           |
| unpickle_list        | 5.17 us                                                                | 5.28 us: 1.02x slower                                          |
| unpickle             | 14.8 us                                                                | 15.5 us: 1.05x slower                                          |
| Geometric mean       | (ref)                                                                  | 1.04x faster                                                   |

Benchmark hidden because not significant (1): pickle_pure_python

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231120-linux-x86_64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 | bm-20231120-linux-x86_64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|------------------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------:|
| python_startup         | 10.4 ms                                                                | 10.4 ms: 1.01x slower                                          |
| python_startup_no_site | 9.05 ms                                                                | 9.10 ms: 1.01x slower                                          |
| Geometric mean         | (ref)                                                                  | 1.01x slower                                                   |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231120-linux-x86_64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 | bm-20231120-linux-x86_64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|-----------|:----------------------------------------------------------------------:|:--------------------------------------------------------------:|
| mako      | 17.4 ms                                                                | 12.4 ms: 1.40x faster                                          |

All benchmarks:
===============

| Benchmark                  | bm-20231120-linux-x86_64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 | bm-20231120-linux-x86_64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|----------------------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------:|
| deltablue                  | 5.80 ms                                                                | 4.06 ms: 1.43x faster                                          |
| nbody                      | 140 ms                                                                 | 100 ms: 1.40x faster                                           |
| mako                       | 17.4 ms                                                                | 12.4 ms: 1.40x faster                                          |
| scimark_fft                | 524 ms                                                                 | 382 ms: 1.37x faster                                           |
| float                      | 115 ms                                                                 | 85.0 ms: 1.36x faster                                          |
| hexiom                     | 10.3 ms                                                                | 7.60 ms: 1.35x faster                                          |
| comprehensions             | 26.0 us                                                                | 19.3 us: 1.35x faster                                          |
| tomli_loads                | 2.95 sec                                                               | 2.21 sec: 1.34x faster                                         |
| scimark_sparse_mat_mult    | 6.88 ms                                                                | 5.31 ms: 1.30x faster                                          |
| spectral_norm              | 169 ms                                                                 | 137 ms: 1.24x faster                                           |
| chaos                      | 82.0 ms                                                                | 66.3 ms: 1.24x faster                                          |
| pyflate                    | 601 ms                                                                 | 502 ms: 1.20x faster                                           |
| scimark_monte_carlo        | 90.0 ms                                                                | 75.3 ms: 1.20x faster                                          |
| regex_compile              | 168 ms                                                                 | 141 ms: 1.19x faster                                           |
| crypto_pyaes               | 93.8 ms                                                                | 79.4 ms: 1.18x faster                                          |
| fannkuch                   | 502 ms                                                                 | 434 ms: 1.16x faster                                           |
| raytrace                   | 326 ms                                                                 | 286 ms: 1.14x faster                                           |
| pprint_pformat             | 1.78 sec                                                               | 1.57 sec: 1.13x faster                                         |
| richards_super             | 58.8 ms                                                                | 52.0 ms: 1.13x faster                                          |
| nqueens                    | 107 ms                                                                 | 94.4 ms: 1.13x faster                                          |
| go                         | 170 ms                                                                 | 152 ms: 1.12x faster                                           |
| pprint_safe_repr           | 854 ms                                                                 | 766 ms: 1.11x faster                                           |
| richards                   | 51.7 ms                                                                | 46.8 ms: 1.10x faster                                          |
| meteor_contest             | 122 ms                                                                 | 111 ms: 1.10x faster                                           |
| logging_format             | 7.03 us                                                                | 6.39 us: 1.10x faster                                          |
| pycparser                  | 1.27 sec                                                               | 1.16 sec: 1.10x faster                                         |
| sqlglot_optimize           | 60.6 ms                                                                | 55.6 ms: 1.09x faster                                          |
| telco                      | 9.02 ms                                                                | 8.31 ms: 1.09x faster                                          |
| 2to3                       | 297 ms                                                                 | 273 ms: 1.09x faster                                           |
| sympy_str                  | 306 ms                                                                 | 282 ms: 1.08x faster                                           |
| xml_etree_iterparse        | 119 ms                                                                 | 110 ms: 1.08x faster                                           |
| sqlglot_normalize          | 118 ms                                                                 | 109 ms: 1.08x faster                                           |
| regex_v8                   | 26.2 ms                                                                | 24.3 ms: 1.08x faster                                          |
| logging_simple             | 6.24 us                                                                | 5.80 us: 1.08x faster                                          |
| typing_runtime_protocols   | 129 us                                                                 | 120 us: 1.08x faster                                           |
| sympy_expand               | 501 ms                                                                 | 468 ms: 1.07x faster                                           |
| sympy_integrate            | 22.2 ms                                                                | 20.8 ms: 1.07x faster                                          |
| unpack_sequence            | 49.9 ns                                                                | 46.9 ns: 1.07x faster                                          |
| deepcopy_memo              | 43.0 us                                                                | 40.4 us: 1.07x faster                                          |
| unpickle_pure_python       | 248 us                                                                 | 232 us: 1.07x faster                                           |
| sqlglot_parse              | 1.41 ms                                                                | 1.32 ms: 1.07x faster                                          |
| tornado_http               | 103 ms                                                                 | 96.5 ms: 1.07x faster                                          |
| xml_etree_process          | 64.9 ms                                                                | 61.0 ms: 1.06x faster                                          |
| xml_etree_generate         | 94.6 ms                                                                | 89.1 ms: 1.06x faster                                          |
| sympy_sum                  | 166 ms                                                                 | 156 ms: 1.06x faster                                           |
| dulwich_log                | 70.1 ms                                                                | 66.4 ms: 1.06x faster                                          |
| sqlglot_transpile          | 1.74 ms                                                                | 1.65 ms: 1.06x faster                                          |
| pickle_list                | 5.16 us                                                                | 4.89 us: 1.06x faster                                          |
| chameleon                  | 7.50 ms                                                                | 7.11 ms: 1.05x faster                                          |
| pidigits                   | 197 ms                                                                 | 188 ms: 1.05x faster                                           |
| async_tree_none            | 465 ms                                                                 | 443 ms: 1.05x faster                                           |
| deepcopy_reduce            | 3.22 us                                                                | 3.07 us: 1.05x faster                                          |
| sqlite_synth               | 2.95 us                                                                | 2.81 us: 1.05x faster                                          |
| scimark_lu                 | 124 ms                                                                 | 119 ms: 1.05x faster                                           |
| async_tree_none_tg         | 478 ms                                                                 | 458 ms: 1.04x faster                                           |
| pickle                     | 11.7 us                                                                | 11.2 us: 1.04x faster                                          |
| deepcopy                   | 366 us                                                                 | 353 us: 1.04x faster                                           |
| docutils                   | 2.76 sec                                                               | 2.66 sec: 1.04x faster                                         |
| async_tree_memoization     | 592 ms                                                                 | 571 ms: 1.04x faster                                           |
| async_tree_io              | 1.24 sec                                                               | 1.20 sec: 1.03x faster                                         |
| pickle_dict                | 35.1 us                                                                | 34.0 us: 1.03x faster                                          |
| mypy2                      | 361 ms                                                                 | 351 ms: 1.03x faster                                           |
| mdp                        | 2.75 sec                                                               | 2.68 sec: 1.03x faster                                         |
| async_tree_cpu_io_mixed    | 736 ms                                                                 | 718 ms: 1.02x faster                                           |
| async_tree_io_tg           | 1.26 sec                                                               | 1.23 sec: 1.02x faster                                         |
| async_tree_cpu_io_mixed_tg | 762 ms                                                                 | 747 ms: 1.02x faster                                           |
| logging_silent             | 112 ns                                                                 | 110 ns: 1.02x faster                                           |
| pathlib                    | 18.9 ms                                                                | 18.6 ms: 1.02x faster                                          |
| bench_thread_pool          | 866 us                                                                 | 854 us: 1.01x faster                                           |
| dask                       | 371 ms                                                                 | 366 ms: 1.01x faster                                           |
| asyncio_tcp_ssl            | 1.82 sec                                                               | 1.80 sec: 1.01x faster                                         |
| json_dumps                 | 10.7 ms                                                                | 10.6 ms: 1.01x faster                                          |
| regex_effbot               | 3.66 ms                                                                | 3.63 ms: 1.01x faster                                          |
| asyncio_tcp                | 491 ms                                                                 | 489 ms: 1.00x faster                                           |
| json_loads                 | 28.2 us                                                                | 28.4 us: 1.00x slower                                          |
| python_startup             | 10.4 ms                                                                | 10.4 ms: 1.01x slower                                          |
| async_generators           | 461 ms                                                                 | 464 ms: 1.01x slower                                           |
| python_startup_no_site     | 9.05 ms                                                                | 9.10 ms: 1.01x slower                                          |
| json                       | 5.16 ms                                                                | 5.19 ms: 1.01x slower                                          |
| xml_etree_parse            | 159 ms                                                                 | 160 ms: 1.01x slower                                           |
| generators                 | 29.6 ms                                                                | 29.8 ms: 1.01x slower                                          |
| coroutines                 | 21.5 ms                                                                | 21.8 ms: 1.02x slower                                          |
| unpickle_list              | 5.17 us                                                                | 5.28 us: 1.02x slower                                          |
| unpickle                   | 14.8 us                                                                | 15.5 us: 1.05x slower                                          |
| gc_traversal               | 3.67 ms                                                                | 4.04 ms: 1.10x slower                                          |
| Geometric mean             | (ref)                                                                  | 1.08x faster                                                   |

Benchmark hidden because not significant (8): async_tree_memoization_tg, scimark_sor, pickle_pure_python, bench_mp_pool, regex_dna, create_gc_cycles, asyncio_websockets, coverage


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.04x
- 95% likely to have a speedup of 1.04x
- 99% likely to have a speedup of 1.03x
