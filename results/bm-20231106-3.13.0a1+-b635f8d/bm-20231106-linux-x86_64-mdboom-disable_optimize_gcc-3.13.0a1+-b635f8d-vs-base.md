
# Results vs. base

- fork: mdboom
- ref: disable_optimize_gcc
- machine: linux-x86_64
- commit hash: b635f8d
- commit date: 2023-11-06
- overall geometric mean: 1.11x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.05x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231107-linux-x86_64-python-a077b2fbb88f5192bb47-3.13.0a1+-a077b2f | bm-20231106-linux-x86_64-mdboom-disable_optimize_gcc-3.13.0a1+-b635f8d |
|----------------|:----------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| 2to3           | 261 ms                                                                 | 289 ms: 1.11x slower                                                   |
| chameleon      | 6.96 ms                                                                | 8.49 ms: 1.22x slower                                                  |
| docutils       | 2.58 sec                                                               | 2.72 sec: 1.05x slower                                                 |
| tornado_http   | 94.9 ms                                                                | 98.9 ms: 1.04x slower                                                  |
| Geometric mean | (ref)                                                                  | 1.10x slower                                                           |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231107-linux-x86_64-python-a077b2fbb88f5192bb47-3.13.0a1+-a077b2f | bm-20231106-linux-x86_64-mdboom-disable_optimize_gcc-3.13.0a1+-b635f8d |
|----------------------------|:----------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| async_tree_cpu_io_mixed_tg | 741 ms                                                                 | 770 ms: 1.04x slower                                                   |
| async_tree_io              | 1.19 sec                                                               | 1.24 sec: 1.04x slower                                                 |
| async_tree_io_tg           | 1.23 sec                                                               | 1.28 sec: 1.04x slower                                                 |
| async_tree_memoization_tg  | 598 ms                                                                 | 622 ms: 1.04x slower                                                   |
| async_tree_cpu_io_mixed    | 711 ms                                                                 | 742 ms: 1.04x slower                                                   |
| async_tree_none_tg         | 458 ms                                                                 | 480 ms: 1.05x slower                                                   |
| async_tree_none            | 440 ms                                                                 | 464 ms: 1.05x slower                                                   |
| async_tree_memoization     | 566 ms                                                                 | 597 ms: 1.05x slower                                                   |
| Geometric mean             | (ref)                                                                  | 1.04x slower                                                           |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231107-linux-x86_64-python-a077b2fbb88f5192bb47-3.13.0a1+-a077b2f | bm-20231106-linux-x86_64-mdboom-disable_optimize_gcc-3.13.0a1+-b635f8d |
|----------------|:----------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| pidigits       | 187 ms                                                                 | 188 ms: 1.01x slower                                                   |
| float          | 80.5 ms                                                                | 89.5 ms: 1.11x slower                                                  |
| nbody          | 94.2 ms                                                                | 125 ms: 1.33x slower                                                   |
| Geometric mean | (ref)                                                                  | 1.14x slower                                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231107-linux-x86_64-python-a077b2fbb88f5192bb47-3.13.0a1+-a077b2f | bm-20231106-linux-x86_64-mdboom-disable_optimize_gcc-3.13.0a1+-b635f8d |
|----------------|:----------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| regex_effbot   | 3.57 ms                                                                | 3.50 ms: 1.02x faster                                                  |
| regex_dna      | 218 ms                                                                 | 217 ms: 1.01x faster                                                   |
| regex_v8       | 23.9 ms                                                                | 24.5 ms: 1.02x slower                                                  |
| regex_compile  | 133 ms                                                                 | 150 ms: 1.12x slower                                                   |
| Geometric mean | (ref)                                                                  | 1.03x slower                                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231107-linux-x86_64-python-a077b2fbb88f5192bb47-3.13.0a1+-a077b2f | bm-20231106-linux-x86_64-mdboom-disable_optimize_gcc-3.13.0a1+-b635f8d |
|----------------------|:----------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| unpickle_list        | 5.30 us                                                                | 5.31 us: 1.00x slower                                                  |
| pickle_list          | 4.89 us                                                                | 4.92 us: 1.01x slower                                                  |
| json_loads           | 27.7 us                                                                | 28.0 us: 1.01x slower                                                  |
| pickle_dict          | 32.9 us                                                                | 33.5 us: 1.02x slower                                                  |
| xml_etree_parse      | 159 ms                                                                 | 163 ms: 1.03x slower                                                   |
| json_dumps           | 10.5 ms                                                                | 10.9 ms: 1.04x slower                                                  |
| xml_etree_iterparse  | 105 ms                                                                 | 113 ms: 1.08x slower                                                   |
| xml_etree_generate   | 85.8 ms                                                                | 96.0 ms: 1.12x slower                                                  |
| tomli_loads          | 2.14 sec                                                               | 2.46 sec: 1.15x slower                                                 |
| xml_etree_process    | 59.0 ms                                                                | 68.9 ms: 1.17x slower                                                  |
| unpickle_pure_python | 219 us                                                                 | 258 us: 1.18x slower                                                   |
| pickle_pure_python   | 298 us                                                                 | 357 us: 1.20x slower                                                   |
| Geometric mean       | (ref)                                                                  | 1.07x slower                                                           |

Benchmark hidden because not significant (2): unpickle, pickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231107-linux-x86_64-python-a077b2fbb88f5192bb47-3.13.0a1+-a077b2f | bm-20231106-linux-x86_64-mdboom-disable_optimize_gcc-3.13.0a1+-b635f8d |
|------------------------|:----------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| python_startup_no_site | 8.92 ms                                                                | 9.06 ms: 1.02x slower                                                  |
| python_startup         | 10.2 ms                                                                | 10.4 ms: 1.02x slower                                                  |
| Geometric mean         | (ref)                                                                  | 1.02x slower                                                           |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231107-linux-x86_64-python-a077b2fbb88f5192bb47-3.13.0a1+-a077b2f | bm-20231106-linux-x86_64-mdboom-disable_optimize_gcc-3.13.0a1+-b635f8d |
|-----------|:----------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| mako      | 11.3 ms                                                                | 13.4 ms: 1.19x slower                                                  |

All benchmarks:
===============

| Benchmark                  | bm-20231107-linux-x86_64-python-a077b2fbb88f5192bb47-3.13.0a1+-a077b2f | bm-20231106-linux-x86_64-mdboom-disable_optimize_gcc-3.13.0a1+-b635f8d |
|----------------------------|:----------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| regex_effbot               | 3.57 ms                                                                | 3.50 ms: 1.02x faster                                                  |
| regex_dna                  | 218 ms                                                                 | 217 ms: 1.01x faster                                                   |
| asyncio_tcp_ssl            | 1.79 sec                                                               | 1.80 sec: 1.00x slower                                                 |
| unpickle_list              | 5.30 us                                                                | 5.31 us: 1.00x slower                                                  |
| pickle_list                | 4.89 us                                                                | 4.92 us: 1.01x slower                                                  |
| pidigits                   | 187 ms                                                                 | 188 ms: 1.01x slower                                                   |
| create_gc_cycles           | 1.46 ms                                                                | 1.47 ms: 1.01x slower                                                  |
| json_loads                 | 27.7 us                                                                | 28.0 us: 1.01x slower                                                  |
| asyncio_tcp                | 483 ms                                                                 | 490 ms: 1.01x slower                                                   |
| python_startup_no_site     | 8.92 ms                                                                | 9.06 ms: 1.02x slower                                                  |
| python_startup             | 10.2 ms                                                                | 10.4 ms: 1.02x slower                                                  |
| pickle_dict                | 32.9 us                                                                | 33.5 us: 1.02x slower                                                  |
| regex_v8                   | 23.9 ms                                                                | 24.5 ms: 1.02x slower                                                  |
| json                       | 5.15 ms                                                                | 5.27 ms: 1.02x slower                                                  |
| pycparser                  | 1.19 sec                                                               | 1.22 sec: 1.02x slower                                                 |
| sqlite_synth               | 2.79 us                                                                | 2.86 us: 1.02x slower                                                  |
| xml_etree_parse            | 159 ms                                                                 | 163 ms: 1.03x slower                                                   |
| dulwich_log                | 65.9 ms                                                                | 68.0 ms: 1.03x slower                                                  |
| async_tree_cpu_io_mixed_tg | 741 ms                                                                 | 770 ms: 1.04x slower                                                   |
| async_tree_io              | 1.19 sec                                                               | 1.24 sec: 1.04x slower                                                 |
| async_tree_io_tg           | 1.23 sec                                                               | 1.28 sec: 1.04x slower                                                 |
| mypy2                      | 340 ms                                                                 | 354 ms: 1.04x slower                                                   |
| json_dumps                 | 10.5 ms                                                                | 10.9 ms: 1.04x slower                                                  |
| async_tree_memoization_tg  | 598 ms                                                                 | 622 ms: 1.04x slower                                                   |
| tornado_http               | 94.9 ms                                                                | 98.9 ms: 1.04x slower                                                  |
| async_tree_cpu_io_mixed    | 711 ms                                                                 | 742 ms: 1.04x slower                                                   |
| sympy_sum                  | 147 ms                                                                 | 154 ms: 1.04x slower                                                   |
| mdp                        | 2.60 sec                                                               | 2.72 sec: 1.04x slower                                                 |
| telco                      | 8.26 ms                                                                | 8.64 ms: 1.05x slower                                                  |
| async_tree_none_tg         | 458 ms                                                                 | 480 ms: 1.05x slower                                                   |
| docutils                   | 2.58 sec                                                               | 2.72 sec: 1.05x slower                                                 |
| meteor_contest             | 108 ms                                                                 | 114 ms: 1.05x slower                                                   |
| async_tree_none            | 440 ms                                                                 | 464 ms: 1.05x slower                                                   |
| async_tree_memoization     | 566 ms                                                                 | 597 ms: 1.05x slower                                                   |
| coverage                   | 94.6 ms                                                                | 101 ms: 1.06x slower                                                   |
| sympy_integrate            | 19.3 ms                                                                | 20.6 ms: 1.07x slower                                                  |
| async_generators           | 444 ms                                                                 | 473 ms: 1.07x slower                                                   |
| bench_thread_pool          | 822 us                                                                 | 878 us: 1.07x slower                                                   |
| pathlib                    | 18.8 ms                                                                | 20.2 ms: 1.08x slower                                                  |
| xml_etree_iterparse        | 105 ms                                                                 | 113 ms: 1.08x slower                                                   |
| sympy_str                  | 266 ms                                                                 | 290 ms: 1.09x slower                                                   |
| sympy_expand               | 448 ms                                                                 | 489 ms: 1.09x slower                                                   |
| crypto_pyaes               | 70.7 ms                                                                | 78.2 ms: 1.11x slower                                                  |
| 2to3                       | 261 ms                                                                 | 289 ms: 1.11x slower                                                   |
| float                      | 80.5 ms                                                                | 89.5 ms: 1.11x slower                                                  |
| sqlglot_optimize           | 53.1 ms                                                                | 59.4 ms: 1.12x slower                                                  |
| xml_etree_generate         | 85.8 ms                                                                | 96.0 ms: 1.12x slower                                                  |
| scimark_lu                 | 113 ms                                                                 | 127 ms: 1.12x slower                                                   |
| scimark_fft                | 368 ms                                                                 | 414 ms: 1.12x slower                                                   |
| regex_compile              | 133 ms                                                                 | 150 ms: 1.12x slower                                                   |
| spectral_norm              | 110 ms                                                                 | 123 ms: 1.12x slower                                                   |
| sqlglot_transpile          | 1.59 ms                                                                | 1.79 ms: 1.13x slower                                                  |
| gc_traversal               | 3.82 ms                                                                | 4.30 ms: 1.13x slower                                                  |
| typing_runtime_protocols   | 114 us                                                                 | 130 us: 1.13x slower                                                   |
| pyflate                    | 465 ms                                                                 | 528 ms: 1.14x slower                                                   |
| sqlglot_parse              | 1.27 ms                                                                | 1.46 ms: 1.14x slower                                                  |
| scimark_monte_carlo        | 67.8 ms                                                                | 77.8 ms: 1.15x slower                                                  |
| tomli_loads                | 2.14 sec                                                               | 2.46 sec: 1.15x slower                                                 |
| scimark_sparse_mat_mult    | 4.85 ms                                                                | 5.60 ms: 1.15x slower                                                  |
| sqlglot_normalize          | 104 ms                                                                 | 121 ms: 1.16x slower                                                   |
| xml_etree_process          | 59.0 ms                                                                | 68.9 ms: 1.17x slower                                                  |
| unpickle_pure_python       | 219 us                                                                 | 258 us: 1.18x slower                                                   |
| go                         | 140 ms                                                                 | 165 ms: 1.18x slower                                                   |
| deepcopy_reduce            | 3.10 us                                                                | 3.66 us: 1.18x slower                                                  |
| mako                       | 11.3 ms                                                                | 13.4 ms: 1.19x slower                                                  |
| fannkuch                   | 399 ms                                                                 | 474 ms: 1.19x slower                                                   |
| raytrace                   | 271 ms                                                                 | 324 ms: 1.20x slower                                                   |
| pickle_pure_python         | 298 us                                                                 | 357 us: 1.20x slower                                                   |
| pprint_safe_repr           | 731 ms                                                                 | 878 ms: 1.20x slower                                                   |
| pprint_pformat             | 1.48 sec                                                               | 1.78 sec: 1.20x slower                                                 |
| richards_super             | 54.7 ms                                                                | 66.0 ms: 1.21x slower                                                  |
| chaos                      | 59.8 ms                                                                | 72.2 ms: 1.21x slower                                                  |
| nqueens                    | 78.6 ms                                                                | 95.1 ms: 1.21x slower                                                  |
| comprehensions             | 16.4 us                                                                | 19.9 us: 1.21x slower                                                  |
| chameleon                  | 6.96 ms                                                                | 8.49 ms: 1.22x slower                                                  |
| deepcopy                   | 343 us                                                                 | 420 us: 1.22x slower                                                   |
| logging_silent             | 103 ns                                                                 | 126 ns: 1.23x slower                                                   |
| richards                   | 47.6 ms                                                                | 58.8 ms: 1.23x slower                                                  |
| deepcopy_memo              | 37.9 us                                                                | 47.0 us: 1.24x slower                                                  |
| hexiom                     | 6.12 ms                                                                | 7.66 ms: 1.25x slower                                                  |
| logging_format             | 6.29 us                                                                | 7.92 us: 1.26x slower                                                  |
| logging_simple             | 5.77 us                                                                | 7.30 us: 1.26x slower                                                  |
| generators                 | 29.6 ms                                                                | 37.8 ms: 1.28x slower                                                  |
| coroutines                 | 21.7 ms                                                                | 28.5 ms: 1.32x slower                                                  |
| deltablue                  | 3.28 ms                                                                | 4.32 ms: 1.32x slower                                                  |
| nbody                      | 94.2 ms                                                                | 125 ms: 1.33x slower                                                   |
| scimark_sor                | 122 ms                                                                 | 169 ms: 1.39x slower                                                   |
| unpack_sequence            | 44.8 ns                                                                | 75.8 ns: 1.69x slower                                                  |
| Geometric mean             | (ref)                                                                  | 1.11x slower                                                           |

Benchmark hidden because not significant (4): unpickle, pickle, bench_mp_pool, asyncio_websockets


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.06x
- 95% likely to have a slowdown of 1.05x
- 99% likely to have a slowdown of 1.05x
