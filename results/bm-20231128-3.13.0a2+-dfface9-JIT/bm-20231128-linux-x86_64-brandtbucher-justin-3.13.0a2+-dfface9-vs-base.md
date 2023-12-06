
# Results vs. base

- fork: brandtbucher
- ref: justin
- machine: linux-x86_64
- commit hash: dfface9
- commit date: 2023-11-28
- overall geometric mean: 1.04x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.01x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231128-linux-x86_64-python-48dfd74a9db9d4aa9c6f-3.13.0a2+-48dfd74 | bm-20231128-linux-x86_64-brandtbucher-justin-3.13.0a2+-dfface9 |
|----------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------:|
| 2to3           | 264 ms                                                                 | 273 ms: 1.04x slower                                           |
| chameleon      | 7.06 ms                                                                | 7.19 ms: 1.02x slower                                          |
| docutils       | 2.60 sec                                                               | 2.67 sec: 1.03x slower                                         |
| tornado_http   | 94.9 ms                                                                | 97.0 ms: 1.02x slower                                          |
| Geometric mean | (ref)                                                                  | 1.03x slower                                                   |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                 | bm-20231128-linux-x86_64-python-48dfd74a9db9d4aa9c6f-3.13.0a2+-48dfd74 | bm-20231128-linux-x86_64-brandtbucher-justin-3.13.0a2+-dfface9 |
|---------------------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------:|
| async_tree_io             | 1.19 sec                                                               | 1.20 sec: 1.01x slower                                         |
| async_tree_cpu_io_mixed   | 706 ms                                                                 | 714 ms: 1.01x slower                                           |
| async_tree_io_tg          | 1.21 sec                                                               | 1.23 sec: 1.01x slower                                         |
| async_tree_none_tg        | 453 ms                                                                 | 460 ms: 1.02x slower                                           |
| async_tree_memoization    | 558 ms                                                                 | 568 ms: 1.02x slower                                           |
| async_tree_memoization_tg | 590 ms                                                                 | 616 ms: 1.04x slower                                           |
| Geometric mean            | (ref)                                                                  | 1.02x slower                                                   |

Benchmark hidden because not significant (2): async_tree_cpu_io_mixed_tg, async_tree_none

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231128-linux-x86_64-python-48dfd74a9db9d4aa9c6f-3.13.0a2+-48dfd74 | bm-20231128-linux-x86_64-brandtbucher-justin-3.13.0a2+-dfface9 |
|----------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------:|
| float          | 81.5 ms                                                                | 84.9 ms: 1.04x slower                                          |
| pidigits       | 187 ms                                                                 | 196 ms: 1.05x slower                                           |
| nbody          | 91.8 ms                                                                | 98.4 ms: 1.07x slower                                          |
| Geometric mean | (ref)                                                                  | 1.05x slower                                                   |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231128-linux-x86_64-python-48dfd74a9db9d4aa9c6f-3.13.0a2+-48dfd74 | bm-20231128-linux-x86_64-brandtbucher-justin-3.13.0a2+-dfface9 |
|----------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------:|
| regex_v8       | 25.7 ms                                                                | 26.0 ms: 1.01x slower                                          |
| regex_effbot   | 3.62 ms                                                                | 3.71 ms: 1.03x slower                                          |
| regex_dna      | 215 ms                                                                 | 222 ms: 1.03x slower                                           |
| regex_compile  | 135 ms                                                                 | 143 ms: 1.06x slower                                           |
| Geometric mean | (ref)                                                                  | 1.03x slower                                                   |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231128-linux-x86_64-python-48dfd74a9db9d4aa9c6f-3.13.0a2+-48dfd74 | bm-20231128-linux-x86_64-brandtbucher-justin-3.13.0a2+-dfface9 |
|----------------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------:|
| unpickle_list        | 5.25 us                                                                | 4.96 us: 1.06x faster                                          |
| json_loads           | 28.5 us                                                                | 28.1 us: 1.01x faster                                          |
| pickle_list          | 5.10 us                                                                | 5.05 us: 1.01x faster                                          |
| json_dumps           | 10.5 ms                                                                | 10.6 ms: 1.01x slower                                          |
| pickle_pure_python   | 302 us                                                                 | 305 us: 1.01x slower                                           |
| xml_etree_generate   | 87.6 ms                                                                | 88.6 ms: 1.01x slower                                          |
| xml_etree_parse      | 158 ms                                                                 | 161 ms: 1.02x slower                                           |
| xml_etree_process    | 59.7 ms                                                                | 61.1 ms: 1.02x slower                                          |
| pickle               | 11.1 us                                                                | 11.6 us: 1.04x slower                                          |
| xml_etree_iterparse  | 105 ms                                                                 | 110 ms: 1.05x slower                                           |
| unpickle_pure_python | 216 us                                                                 | 231 us: 1.07x slower                                           |
| pickle_dict          | 33.4 us                                                                | 36.4 us: 1.09x slower                                          |
| Geometric mean       | (ref)                                                                  | 1.02x slower                                                   |

Benchmark hidden because not significant (2): tomli_loads, unpickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231128-linux-x86_64-python-48dfd74a9db9d4aa9c6f-3.13.0a2+-48dfd74 | bm-20231128-linux-x86_64-brandtbucher-justin-3.13.0a2+-dfface9 |
|------------------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------:|
| python_startup         | 10.3 ms                                                                | 10.4 ms: 1.01x slower                                          |
| python_startup_no_site | 8.98 ms                                                                | 9.11 ms: 1.02x slower                                          |
| Geometric mean         | (ref)                                                                  | 1.01x slower                                                   |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231128-linux-x86_64-python-48dfd74a9db9d4aa9c6f-3.13.0a2+-48dfd74 | bm-20231128-linux-x86_64-brandtbucher-justin-3.13.0a2+-dfface9 |
|-----------|:----------------------------------------------------------------------:|:--------------------------------------------------------------:|
| mako      | 11.6 ms                                                                | 12.2 ms: 1.05x slower                                          |

All benchmarks:
===============

| Benchmark                 | bm-20231128-linux-x86_64-python-48dfd74a9db9d4aa9c6f-3.13.0a2+-48dfd74 | bm-20231128-linux-x86_64-brandtbucher-justin-3.13.0a2+-dfface9 |
|---------------------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------:|
| unpickle_list             | 5.25 us                                                                | 4.96 us: 1.06x faster                                          |
| generators                | 29.8 ms                                                                | 28.7 ms: 1.04x faster                                          |
| richards_super            | 54.1 ms                                                                | 52.3 ms: 1.03x faster                                          |
| coverage                  | 95.5 ms                                                                | 93.9 ms: 1.02x faster                                          |
| telco                     | 8.42 ms                                                                | 8.29 ms: 1.02x faster                                          |
| json_loads                | 28.5 us                                                                | 28.1 us: 1.01x faster                                          |
| sqlite_synth              | 2.84 us                                                                | 2.80 us: 1.01x faster                                          |
| pickle_list               | 5.10 us                                                                | 5.05 us: 1.01x faster                                          |
| scimark_sor               | 124 ms                                                                 | 123 ms: 1.01x faster                                           |
| json                      | 5.16 ms                                                                | 5.12 ms: 1.01x faster                                          |
| create_gc_cycles          | 1.46 ms                                                                | 1.47 ms: 1.00x slower                                          |
| asyncio_tcp_ssl           | 1.78 sec                                                               | 1.79 sec: 1.00x slower                                         |
| scimark_fft               | 369 ms                                                                 | 371 ms: 1.01x slower                                           |
| logging_simple            | 5.80 us                                                                | 5.84 us: 1.01x slower                                          |
| json_dumps                | 10.5 ms                                                                | 10.6 ms: 1.01x slower                                          |
| deepcopy_memo             | 39.3 us                                                                | 39.6 us: 1.01x slower                                          |
| async_tree_io             | 1.19 sec                                                               | 1.20 sec: 1.01x slower                                         |
| pickle_pure_python        | 302 us                                                                 | 305 us: 1.01x slower                                           |
| regex_v8                  | 25.7 ms                                                                | 26.0 ms: 1.01x slower                                          |
| scimark_lu                | 115 ms                                                                 | 116 ms: 1.01x slower                                           |
| scimark_sparse_mat_mult   | 5.00 ms                                                                | 5.06 ms: 1.01x slower                                          |
| async_tree_cpu_io_mixed   | 706 ms                                                                 | 714 ms: 1.01x slower                                           |
| xml_etree_generate        | 87.6 ms                                                                | 88.6 ms: 1.01x slower                                          |
| pathlib                   | 18.0 ms                                                                | 18.3 ms: 1.01x slower                                          |
| python_startup            | 10.3 ms                                                                | 10.4 ms: 1.01x slower                                          |
| dask                      | 360 ms                                                                 | 365 ms: 1.01x slower                                           |
| async_tree_io_tg          | 1.21 sec                                                               | 1.23 sec: 1.01x slower                                         |
| dulwich_log               | 65.5 ms                                                                | 66.5 ms: 1.01x slower                                          |
| python_startup_no_site    | 8.98 ms                                                                | 9.11 ms: 1.02x slower                                          |
| async_tree_none_tg        | 453 ms                                                                 | 460 ms: 1.02x slower                                           |
| asyncio_tcp               | 486 ms                                                                 | 494 ms: 1.02x slower                                           |
| deepcopy                  | 349 us                                                                 | 355 us: 1.02x slower                                           |
| sqlglot_parse             | 1.28 ms                                                                | 1.30 ms: 1.02x slower                                          |
| xml_etree_parse           | 158 ms                                                                 | 161 ms: 1.02x slower                                           |
| async_tree_memoization    | 558 ms                                                                 | 568 ms: 1.02x slower                                           |
| raytrace                  | 279 ms                                                                 | 285 ms: 1.02x slower                                           |
| chameleon                 | 7.06 ms                                                                | 7.19 ms: 1.02x slower                                          |
| bench_thread_pool         | 832 us                                                                 | 848 us: 1.02x slower                                           |
| logging_format            | 6.32 us                                                                | 6.45 us: 1.02x slower                                          |
| xml_etree_process         | 59.7 ms                                                                | 61.1 ms: 1.02x slower                                          |
| sqlglot_transpile         | 1.59 ms                                                                | 1.63 ms: 1.02x slower                                          |
| tornado_http              | 94.9 ms                                                                | 97.0 ms: 1.02x slower                                          |
| coroutines                | 22.1 ms                                                                | 22.7 ms: 1.03x slower                                          |
| regex_effbot              | 3.62 ms                                                                | 3.71 ms: 1.03x slower                                          |
| logging_silent            | 105 ns                                                                 | 108 ns: 1.03x slower                                           |
| sympy_expand              | 457 ms                                                                 | 470 ms: 1.03x slower                                           |
| docutils                  | 2.60 sec                                                               | 2.67 sec: 1.03x slower                                         |
| sqlglot_normalize         | 107 ms                                                                 | 110 ms: 1.03x slower                                           |
| regex_dna                 | 215 ms                                                                 | 222 ms: 1.03x slower                                           |
| sqlglot_optimize          | 53.9 ms                                                                | 55.8 ms: 1.04x slower                                          |
| meteor_contest            | 108 ms                                                                 | 112 ms: 1.04x slower                                           |
| 2to3                      | 264 ms                                                                 | 273 ms: 1.04x slower                                           |
| float                     | 81.5 ms                                                                | 84.9 ms: 1.04x slower                                          |
| pickle                    | 11.1 us                                                                | 11.6 us: 1.04x slower                                          |
| async_tree_memoization_tg | 590 ms                                                                 | 616 ms: 1.04x slower                                           |
| async_generators          | 445 ms                                                                 | 465 ms: 1.05x slower                                           |
| sympy_str                 | 268 ms                                                                 | 280 ms: 1.05x slower                                           |
| pidigits                  | 187 ms                                                                 | 196 ms: 1.05x slower                                           |
| xml_etree_iterparse       | 105 ms                                                                 | 110 ms: 1.05x slower                                           |
| pprint_safe_repr          | 737 ms                                                                 | 775 ms: 1.05x slower                                           |
| mako                      | 11.6 ms                                                                | 12.2 ms: 1.05x slower                                          |
| gc_traversal              | 3.64 ms                                                                | 3.85 ms: 1.06x slower                                          |
| pprint_pformat            | 1.50 sec                                                               | 1.59 sec: 1.06x slower                                         |
| go                        | 142 ms                                                                 | 150 ms: 1.06x slower                                           |
| regex_compile             | 135 ms                                                                 | 143 ms: 1.06x slower                                           |
| fannkuch                  | 404 ms                                                                 | 429 ms: 1.06x slower                                           |
| sympy_integrate           | 19.5 ms                                                                | 20.7 ms: 1.06x slower                                          |
| unpickle_pure_python      | 216 us                                                                 | 231 us: 1.07x slower                                           |
| sympy_sum                 | 147 ms                                                                 | 157 ms: 1.07x slower                                           |
| nbody                     | 91.8 ms                                                                | 98.4 ms: 1.07x slower                                          |
| chaos                     | 61.8 ms                                                                | 66.4 ms: 1.08x slower                                          |
| pyflate                   | 456 ms                                                                 | 493 ms: 1.08x slower                                           |
| crypto_pyaes              | 71.4 ms                                                                | 78.0 ms: 1.09x slower                                          |
| pickle_dict               | 33.4 us                                                                | 36.4 us: 1.09x slower                                          |
| mdp                       | 2.54 sec                                                               | 2.80 sec: 1.10x slower                                         |
| scimark_monte_carlo       | 68.6 ms                                                                | 76.4 ms: 1.11x slower                                          |
| nqueens                   | 80.1 ms                                                                | 91.8 ms: 1.15x slower                                          |
| comprehensions            | 16.4 us                                                                | 19.3 us: 1.18x slower                                          |
| unpack_sequence           | 45.9 ns                                                                | 55.9 ns: 1.22x slower                                          |
| deltablue                 | 3.29 ms                                                                | 4.07 ms: 1.24x slower                                          |
| spectral_norm             | 111 ms                                                                 | 138 ms: 1.24x slower                                           |
| hexiom                    | 6.02 ms                                                                | 7.52 ms: 1.25x slower                                          |
| Geometric mean            | (ref)                                                                  | 1.04x slower                                                   |

Benchmark hidden because not significant (11): asyncio_websockets, deepcopy_reduce, pycparser, richards, bench_mp_pool, typing_runtime_protocols, tomli_loads, async_tree_cpu_io_mixed_tg, unpickle, async_tree_none, mypy2


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.01x
- 95% likely to have a slowdown of 1.01x
- 99% likely to have a slowdown of 1.01x
