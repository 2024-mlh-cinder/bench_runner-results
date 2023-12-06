
# Results vs. base

- fork: brandtbucher
- ref: justin_mmap
- machine: linux-x86_64
- commit hash: 00abf88
- commit date: 2023-11-29
- overall geometric mean: 1.04x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.02x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231128-linux-x86_64-python-48dfd74a9db9d4aa9c6f-3.13.0a2+-48dfd74 | bm-20231129-linux-x86_64-brandtbucher-justin_mmap-3.13.0a2+-00abf88 |
|----------------|:----------------------------------------------------------------------:|:-------------------------------------------------------------------:|
| 2to3           | 264 ms                                                                 | 277 ms: 1.05x slower                                                |
| docutils       | 2.60 sec                                                               | 2.69 sec: 1.04x slower                                              |
| tornado_http   | 94.9 ms                                                                | 97.4 ms: 1.03x slower                                               |
| Geometric mean | (ref)                                                                  | 1.03x slower                                                        |

Benchmark hidden because not significant (1): chameleon

Benchmarks with tag 'asyncio':
==============================

| Benchmark                 | bm-20231128-linux-x86_64-python-48dfd74a9db9d4aa9c6f-3.13.0a2+-48dfd74 | bm-20231129-linux-x86_64-brandtbucher-justin_mmap-3.13.0a2+-00abf88 |
|---------------------------|:----------------------------------------------------------------------:|:-------------------------------------------------------------------:|
| async_tree_none_tg        | 453 ms                                                                 | 458 ms: 1.01x slower                                                |
| async_tree_io_tg          | 1.21 sec                                                               | 1.23 sec: 1.01x slower                                              |
| async_tree_memoization_tg | 590 ms                                                                 | 606 ms: 1.03x slower                                                |
| async_tree_memoization    | 558 ms                                                                 | 574 ms: 1.03x slower                                                |
| Geometric mean            | (ref)                                                                  | 1.01x slower                                                        |

Benchmark hidden because not significant (4): async_tree_cpu_io_mixed_tg, async_tree_io, async_tree_cpu_io_mixed, async_tree_none

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231128-linux-x86_64-python-48dfd74a9db9d4aa9c6f-3.13.0a2+-48dfd74 | bm-20231129-linux-x86_64-brandtbucher-justin_mmap-3.13.0a2+-00abf88 |
|----------------|:----------------------------------------------------------------------:|:-------------------------------------------------------------------:|
| pidigits       | 187 ms                                                                 | 188 ms: 1.00x slower                                                |
| float          | 81.5 ms                                                                | 85.5 ms: 1.05x slower                                               |
| nbody          | 91.8 ms                                                                | 101 ms: 1.10x slower                                                |
| Geometric mean | (ref)                                                                  | 1.05x slower                                                        |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231128-linux-x86_64-python-48dfd74a9db9d4aa9c6f-3.13.0a2+-48dfd74 | bm-20231129-linux-x86_64-brandtbucher-justin_mmap-3.13.0a2+-00abf88 |
|----------------|:----------------------------------------------------------------------:|:-------------------------------------------------------------------:|
| regex_v8       | 25.7 ms                                                                | 26.0 ms: 1.01x slower                                               |
| regex_effbot   | 3.62 ms                                                                | 3.73 ms: 1.03x slower                                               |
| regex_dna      | 215 ms                                                                 | 222 ms: 1.03x slower                                                |
| regex_compile  | 135 ms                                                                 | 146 ms: 1.08x slower                                                |
| Geometric mean | (ref)                                                                  | 1.04x slower                                                        |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231128-linux-x86_64-python-48dfd74a9db9d4aa9c6f-3.13.0a2+-48dfd74 | bm-20231129-linux-x86_64-brandtbucher-justin_mmap-3.13.0a2+-00abf88 |
|----------------------|:----------------------------------------------------------------------:|:-------------------------------------------------------------------:|
| unpickle_list        | 5.25 us                                                                | 5.11 us: 1.03x faster                                               |
| json_loads           | 28.5 us                                                                | 28.1 us: 1.01x faster                                               |
| pickle_list          | 5.10 us                                                                | 5.05 us: 1.01x faster                                               |
| xml_etree_parse      | 158 ms                                                                 | 159 ms: 1.01x slower                                                |
| json_dumps           | 10.5 ms                                                                | 10.6 ms: 1.01x slower                                               |
| pickle_pure_python   | 302 us                                                                 | 307 us: 1.02x slower                                                |
| xml_etree_generate   | 87.6 ms                                                                | 89.4 ms: 1.02x slower                                               |
| xml_etree_process    | 59.7 ms                                                                | 61.4 ms: 1.03x slower                                               |
| tomli_loads          | 2.15 sec                                                               | 2.22 sec: 1.03x slower                                              |
| pickle               | 11.1 us                                                                | 11.7 us: 1.05x slower                                               |
| xml_etree_iterparse  | 105 ms                                                                 | 111 ms: 1.06x slower                                                |
| pickle_dict          | 33.4 us                                                                | 35.6 us: 1.07x slower                                               |
| unpickle_pure_python | 216 us                                                                 | 233 us: 1.08x slower                                                |
| Geometric mean       | (ref)                                                                  | 1.02x slower                                                        |

Benchmark hidden because not significant (1): unpickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231128-linux-x86_64-python-48dfd74a9db9d4aa9c6f-3.13.0a2+-48dfd74 | bm-20231129-linux-x86_64-brandtbucher-justin_mmap-3.13.0a2+-00abf88 |
|------------------------|:----------------------------------------------------------------------:|:-------------------------------------------------------------------:|
| python_startup         | 10.3 ms                                                                | 10.5 ms: 1.01x slower                                               |
| python_startup_no_site | 8.98 ms                                                                | 9.13 ms: 1.02x slower                                               |
| Geometric mean         | (ref)                                                                  | 1.02x slower                                                        |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231128-linux-x86_64-python-48dfd74a9db9d4aa9c6f-3.13.0a2+-48dfd74 | bm-20231129-linux-x86_64-brandtbucher-justin_mmap-3.13.0a2+-00abf88 |
|-----------|:----------------------------------------------------------------------:|:-------------------------------------------------------------------:|
| mako      | 11.6 ms                                                                | 12.3 ms: 1.06x slower                                               |

All benchmarks:
===============

| Benchmark                 | bm-20231128-linux-x86_64-python-48dfd74a9db9d4aa9c6f-3.13.0a2+-48dfd74 | bm-20231129-linux-x86_64-brandtbucher-justin_mmap-3.13.0a2+-00abf88 |
|---------------------------|:----------------------------------------------------------------------:|:-------------------------------------------------------------------:|
| generators                | 29.8 ms                                                                | 28.8 ms: 1.03x faster                                               |
| unpickle_list             | 5.25 us                                                                | 5.11 us: 1.03x faster                                               |
| richards_super            | 54.1 ms                                                                | 53.3 ms: 1.01x faster                                               |
| json_loads                | 28.5 us                                                                | 28.1 us: 1.01x faster                                               |
| richards                  | 47.4 ms                                                                | 46.9 ms: 1.01x faster                                               |
| pickle_list               | 5.10 us                                                                | 5.05 us: 1.01x faster                                               |
| deepcopy_memo             | 39.3 us                                                                | 39.0 us: 1.01x faster                                               |
| asyncio_websockets        | 554 ms                                                                 | 551 ms: 1.00x faster                                                |
| pidigits                  | 187 ms                                                                 | 188 ms: 1.00x slower                                                |
| asyncio_tcp               | 486 ms                                                                 | 489 ms: 1.00x slower                                                |
| asyncio_tcp_ssl           | 1.78 sec                                                               | 1.79 sec: 1.01x slower                                              |
| deepcopy_reduce           | 3.12 us                                                                | 3.14 us: 1.01x slower                                               |
| coverage                  | 95.5 ms                                                                | 96.2 ms: 1.01x slower                                               |
| scimark_lu                | 115 ms                                                                 | 116 ms: 1.01x slower                                                |
| pycparser                 | 1.21 sec                                                               | 1.22 sec: 1.01x slower                                              |
| xml_etree_parse           | 158 ms                                                                 | 159 ms: 1.01x slower                                                |
| scimark_sor               | 124 ms                                                                 | 125 ms: 1.01x slower                                                |
| regex_v8                  | 25.7 ms                                                                | 26.0 ms: 1.01x slower                                               |
| deepcopy                  | 349 us                                                                 | 353 us: 1.01x slower                                                |
| json                      | 5.16 ms                                                                | 5.22 ms: 1.01x slower                                               |
| async_tree_none_tg        | 453 ms                                                                 | 458 ms: 1.01x slower                                                |
| python_startup            | 10.3 ms                                                                | 10.5 ms: 1.01x slower                                               |
| json_dumps                | 10.5 ms                                                                | 10.6 ms: 1.01x slower                                               |
| async_tree_io_tg          | 1.21 sec                                                               | 1.23 sec: 1.01x slower                                              |
| pickle_pure_python        | 302 us                                                                 | 307 us: 1.02x slower                                                |
| python_startup_no_site    | 8.98 ms                                                                | 9.13 ms: 1.02x slower                                               |
| xml_etree_generate        | 87.6 ms                                                                | 89.4 ms: 1.02x slower                                               |
| dask                      | 360 ms                                                                 | 367 ms: 1.02x slower                                                |
| logging_format            | 6.32 us                                                                | 6.45 us: 1.02x slower                                               |
| coroutines                | 22.1 ms                                                                | 22.6 ms: 1.02x slower                                               |
| bench_thread_pool         | 832 us                                                                 | 852 us: 1.02x slower                                                |
| tornado_http              | 94.9 ms                                                                | 97.4 ms: 1.03x slower                                               |
| xml_etree_process         | 59.7 ms                                                                | 61.4 ms: 1.03x slower                                               |
| async_tree_memoization_tg | 590 ms                                                                 | 606 ms: 1.03x slower                                                |
| async_tree_memoization    | 558 ms                                                                 | 574 ms: 1.03x slower                                                |
| dulwich_log               | 65.5 ms                                                                | 67.5 ms: 1.03x slower                                               |
| regex_effbot              | 3.62 ms                                                                | 3.73 ms: 1.03x slower                                               |
| meteor_contest            | 108 ms                                                                 | 112 ms: 1.03x slower                                                |
| regex_dna                 | 215 ms                                                                 | 222 ms: 1.03x slower                                                |
| tomli_loads               | 2.15 sec                                                               | 2.22 sec: 1.03x slower                                              |
| sqlglot_parse             | 1.28 ms                                                                | 1.32 ms: 1.03x slower                                               |
| raytrace                  | 279 ms                                                                 | 289 ms: 1.04x slower                                                |
| pathlib                   | 18.0 ms                                                                | 18.7 ms: 1.04x slower                                               |
| sqlglot_transpile         | 1.59 ms                                                                | 1.65 ms: 1.04x slower                                               |
| docutils                  | 2.60 sec                                                               | 2.69 sec: 1.04x slower                                              |
| logging_silent            | 105 ns                                                                 | 109 ns: 1.04x slower                                                |
| sqlglot_normalize         | 107 ms                                                                 | 111 ms: 1.04x slower                                                |
| async_generators          | 445 ms                                                                 | 463 ms: 1.04x slower                                                |
| scimark_fft               | 369 ms                                                                 | 384 ms: 1.04x slower                                                |
| sympy_expand              | 457 ms                                                                 | 479 ms: 1.05x slower                                                |
| float                     | 81.5 ms                                                                | 85.5 ms: 1.05x slower                                               |
| pickle                    | 11.1 us                                                                | 11.7 us: 1.05x slower                                               |
| 2to3                      | 264 ms                                                                 | 277 ms: 1.05x slower                                                |
| sqlglot_optimize          | 53.9 ms                                                                | 56.7 ms: 1.05x slower                                               |
| scimark_sparse_mat_mult   | 5.00 ms                                                                | 5.28 ms: 1.06x slower                                               |
| xml_etree_iterparse       | 105 ms                                                                 | 111 ms: 1.06x slower                                                |
| mako                      | 11.6 ms                                                                | 12.3 ms: 1.06x slower                                               |
| go                        | 142 ms                                                                 | 151 ms: 1.07x slower                                                |
| pprint_safe_repr          | 737 ms                                                                 | 785 ms: 1.07x slower                                                |
| pickle_dict               | 33.4 us                                                                | 35.6 us: 1.07x slower                                               |
| sympy_str                 | 268 ms                                                                 | 288 ms: 1.07x slower                                                |
| pprint_pformat            | 1.50 sec                                                               | 1.62 sec: 1.07x slower                                              |
| unpickle_pure_python      | 216 us                                                                 | 233 us: 1.08x slower                                                |
| regex_compile             | 135 ms                                                                 | 146 ms: 1.08x slower                                                |
| fannkuch                  | 404 ms                                                                 | 438 ms: 1.09x slower                                                |
| sympy_integrate           | 19.5 ms                                                                | 21.2 ms: 1.09x slower                                               |
| sympy_sum                 | 147 ms                                                                 | 160 ms: 1.09x slower                                                |
| pyflate                   | 456 ms                                                                 | 501 ms: 1.10x slower                                                |
| nbody                     | 91.8 ms                                                                | 101 ms: 1.10x slower                                                |
| crypto_pyaes              | 71.4 ms                                                                | 79.0 ms: 1.11x slower                                               |
| mdp                       | 2.54 sec                                                               | 2.82 sec: 1.11x slower                                              |
| scimark_monte_carlo       | 68.6 ms                                                                | 76.9 ms: 1.12x slower                                               |
| chaos                     | 61.8 ms                                                                | 70.1 ms: 1.13x slower                                               |
| gc_traversal              | 3.64 ms                                                                | 4.16 ms: 1.14x slower                                               |
| nqueens                   | 80.1 ms                                                                | 94.4 ms: 1.18x slower                                               |
| comprehensions            | 16.4 us                                                                | 19.5 us: 1.19x slower                                               |
| deltablue                 | 3.29 ms                                                                | 4.10 ms: 1.25x slower                                               |
| unpack_sequence           | 45.9 ns                                                                | 58.1 ns: 1.27x slower                                               |
| spectral_norm             | 111 ms                                                                 | 141 ms: 1.27x slower                                                |
| hexiom                    | 6.02 ms                                                                | 7.94 ms: 1.32x slower                                               |
| Geometric mean            | (ref)                                                                  | 1.04x slower                                                        |

Benchmark hidden because not significant (13): create_gc_cycles, bench_mp_pool, sqlite_synth, typing_runtime_protocols, async_tree_cpu_io_mixed_tg, async_tree_io, chameleon, logging_simple, unpickle, async_tree_cpu_io_mixed, telco, async_tree_none, mypy2


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.02x
- 95% likely to have a slowdown of 1.02x
- 99% likely to have a slowdown of 1.02x
