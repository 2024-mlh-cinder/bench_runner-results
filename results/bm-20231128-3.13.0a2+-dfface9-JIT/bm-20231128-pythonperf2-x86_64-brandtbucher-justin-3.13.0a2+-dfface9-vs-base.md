
# Results vs. base

- fork: brandtbucher
- ref: justin
- machine: linux-x86_64
- commit hash: dfface9
- commit date: 2023-11-28
- overall geometric mean: 1.04x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.02x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231128-pythonperf2-x86_64-python-48dfd74a9db9d4aa9c6f-3.13.0a2+-48dfd74 | bm-20231128-pythonperf2-x86_64-brandtbucher-justin-3.13.0a2+-dfface9 |
|----------------|:----------------------------------------------------------------------------:|:--------------------------------------------------------------------:|
| 2to3           | 290 ms                                                                       | 301 ms: 1.04x slower                                                 |
| chameleon      | 7.44 ms                                                                      | 7.71 ms: 1.04x slower                                                |
| docutils       | 2.80 sec                                                                     | 2.86 sec: 1.02x slower                                               |
| tornado_http   | 117 ms                                                                       | 120 ms: 1.02x slower                                                 |
| Geometric mean | (ref)                                                                        | 1.03x slower                                                         |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231128-pythonperf2-x86_64-python-48dfd74a9db9d4aa9c6f-3.13.0a2+-48dfd74 | bm-20231128-pythonperf2-x86_64-brandtbucher-justin-3.13.0a2+-dfface9 |
|----------------------------|:----------------------------------------------------------------------------:|:--------------------------------------------------------------------:|
| async_tree_cpu_io_mixed_tg | 709 ms                                                                       | 722 ms: 1.02x slower                                                 |
| async_tree_cpu_io_mixed    | 695 ms                                                                       | 708 ms: 1.02x slower                                                 |
| async_tree_io_tg           | 1.08 sec                                                                     | 1.11 sec: 1.02x slower                                               |
| async_tree_io              | 1.07 sec                                                                     | 1.09 sec: 1.02x slower                                               |
| async_tree_memoization     | 540 ms                                                                       | 557 ms: 1.03x slower                                                 |
| async_tree_none_tg         | 436 ms                                                                       | 450 ms: 1.03x slower                                                 |
| async_tree_none            | 428 ms                                                                       | 443 ms: 1.03x slower                                                 |
| async_tree_memoization_tg  | 553 ms                                                                       | 580 ms: 1.05x slower                                                 |
| Geometric mean             | (ref)                                                                        | 1.03x slower                                                         |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231128-pythonperf2-x86_64-python-48dfd74a9db9d4aa9c6f-3.13.0a2+-48dfd74 | bm-20231128-pythonperf2-x86_64-brandtbucher-justin-3.13.0a2+-dfface9 |
|----------------|:----------------------------------------------------------------------------:|:--------------------------------------------------------------------:|
| float          | 77.9 ms                                                                      | 80.9 ms: 1.04x slower                                                |
| nbody          | 85.2 ms                                                                      | 104 ms: 1.22x slower                                                 |
| Geometric mean | (ref)                                                                        | 1.08x slower                                                         |

Benchmark hidden because not significant (1): pidigits

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231128-pythonperf2-x86_64-python-48dfd74a9db9d4aa9c6f-3.13.0a2+-48dfd74 | bm-20231128-pythonperf2-x86_64-brandtbucher-justin-3.13.0a2+-dfface9 |
|----------------|:----------------------------------------------------------------------------:|:--------------------------------------------------------------------:|
| regex_v8       | 25.3 ms                                                                      | 24.7 ms: 1.02x faster                                                |
| regex_effbot   | 3.52 ms                                                                      | 3.51 ms: 1.00x faster                                                |
| regex_dna      | 244 ms                                                                       | 246 ms: 1.01x slower                                                 |
| regex_compile  | 143 ms                                                                       | 149 ms: 1.04x slower                                                 |
| Geometric mean | (ref)                                                                        | 1.00x slower                                                         |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231128-pythonperf2-x86_64-python-48dfd74a9db9d4aa9c6f-3.13.0a2+-48dfd74 | bm-20231128-pythonperf2-x86_64-brandtbucher-justin-3.13.0a2+-dfface9 |
|----------------------|:----------------------------------------------------------------------------:|:--------------------------------------------------------------------:|
| pickle_list          | 4.47 us                                                                      | 4.26 us: 1.05x faster                                                |
| pickle               | 10.1 us                                                                      | 9.95 us: 1.02x faster                                                |
| xml_etree_iterparse  | 107 ms                                                                       | 106 ms: 1.01x faster                                                 |
| pickle_pure_python   | 303 us                                                                       | 306 us: 1.01x slower                                                 |
| pickle_dict          | 32.7 us                                                                      | 33.1 us: 1.01x slower                                                |
| json_loads           | 25.3 us                                                                      | 25.6 us: 1.01x slower                                                |
| xml_etree_process    | 57.9 ms                                                                      | 58.8 ms: 1.02x slower                                                |
| xml_etree_parse      | 149 ms                                                                       | 151 ms: 1.02x slower                                                 |
| tomli_loads          | 2.21 sec                                                                     | 2.25 sec: 1.02x slower                                               |
| json_dumps           | 10.6 ms                                                                      | 10.8 ms: 1.02x slower                                                |
| xml_etree_generate   | 83.8 ms                                                                      | 86.3 ms: 1.03x slower                                                |
| unpickle_list        | 4.58 us                                                                      | 4.82 us: 1.05x slower                                                |
| unpickle             | 14.5 us                                                                      | 15.4 us: 1.06x slower                                                |
| unpickle_pure_python | 210 us                                                                       | 236 us: 1.12x slower                                                 |
| Geometric mean       | (ref)                                                                        | 1.02x slower                                                         |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231128-pythonperf2-x86_64-python-48dfd74a9db9d4aa9c6f-3.13.0a2+-48dfd74 | bm-20231128-pythonperf2-x86_64-brandtbucher-justin-3.13.0a2+-dfface9 |
|------------------------|:----------------------------------------------------------------------------:|:--------------------------------------------------------------------:|
| python_startup         | 12.8 ms                                                                      | 12.9 ms: 1.01x slower                                                |
| python_startup_no_site | 11.2 ms                                                                      | 11.4 ms: 1.01x slower                                                |
| Geometric mean         | (ref)                                                                        | 1.01x slower                                                         |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231128-pythonperf2-x86_64-python-48dfd74a9db9d4aa9c6f-3.13.0a2+-48dfd74 | bm-20231128-pythonperf2-x86_64-brandtbucher-justin-3.13.0a2+-dfface9 |
|-----------|:----------------------------------------------------------------------------:|:--------------------------------------------------------------------:|
| mako      | 10.3 ms                                                                      | 11.1 ms: 1.08x slower                                                |

All benchmarks:
===============

| Benchmark                  | bm-20231128-pythonperf2-x86_64-python-48dfd74a9db9d4aa9c6f-3.13.0a2+-48dfd74 | bm-20231128-pythonperf2-x86_64-brandtbucher-justin-3.13.0a2+-dfface9 |
|----------------------------|:----------------------------------------------------------------------------:|:--------------------------------------------------------------------:|
| unpack_sequence            | 57.4 ns                                                                      | 44.8 ns: 1.28x faster                                                |
| scimark_sparse_mat_mult    | 4.51 ms                                                                      | 4.29 ms: 1.05x faster                                                |
| pickle_list                | 4.47 us                                                                      | 4.26 us: 1.05x faster                                                |
| richards                   | 52.4 ms                                                                      | 50.1 ms: 1.04x faster                                                |
| richards_super             | 58.3 ms                                                                      | 56.3 ms: 1.04x faster                                                |
| regex_v8                   | 25.3 ms                                                                      | 24.7 ms: 1.02x faster                                                |
| pickle                     | 10.1 us                                                                      | 9.95 us: 1.02x faster                                                |
| create_gc_cycles           | 1.60 ms                                                                      | 1.58 ms: 1.02x faster                                                |
| xml_etree_iterparse        | 107 ms                                                                       | 106 ms: 1.01x faster                                                 |
| dulwich_log                | 67.4 ms                                                                      | 67.1 ms: 1.01x faster                                                |
| regex_effbot               | 3.52 ms                                                                      | 3.51 ms: 1.00x faster                                                |
| regex_dna                  | 244 ms                                                                       | 246 ms: 1.01x slower                                                 |
| go                         | 172 ms                                                                       | 173 ms: 1.01x slower                                                 |
| asyncio_websockets         | 386 ms                                                                       | 389 ms: 1.01x slower                                                 |
| pathlib                    | 18.8 ms                                                                      | 18.9 ms: 1.01x slower                                                |
| pickle_pure_python         | 303 us                                                                       | 306 us: 1.01x slower                                                 |
| python_startup             | 12.8 ms                                                                      | 12.9 ms: 1.01x slower                                                |
| pickle_dict                | 32.7 us                                                                      | 33.1 us: 1.01x slower                                                |
| dask                       | 396 ms                                                                       | 400 ms: 1.01x slower                                                 |
| json_loads                 | 25.3 us                                                                      | 25.6 us: 1.01x slower                                                |
| logging_silent             | 97.2 ns                                                                      | 98.6 ns: 1.01x slower                                                |
| python_startup_no_site     | 11.2 ms                                                                      | 11.4 ms: 1.01x slower                                                |
| xml_etree_process          | 57.9 ms                                                                      | 58.8 ms: 1.02x slower                                                |
| xml_etree_parse            | 149 ms                                                                       | 151 ms: 1.02x slower                                                 |
| tomli_loads                | 2.21 sec                                                                     | 2.25 sec: 1.02x slower                                               |
| sqlglot_parse              | 1.38 ms                                                                      | 1.40 ms: 1.02x slower                                                |
| async_tree_cpu_io_mixed_tg | 709 ms                                                                       | 722 ms: 1.02x slower                                                 |
| async_tree_cpu_io_mixed    | 695 ms                                                                       | 708 ms: 1.02x slower                                                 |
| tornado_http               | 117 ms                                                                       | 120 ms: 1.02x slower                                                 |
| sqlite_synth               | 2.69 us                                                                      | 2.74 us: 1.02x slower                                                |
| json                       | 5.12 ms                                                                      | 5.22 ms: 1.02x slower                                                |
| telco                      | 8.17 ms                                                                      | 8.33 ms: 1.02x slower                                                |
| async_tree_io_tg           | 1.08 sec                                                                     | 1.11 sec: 1.02x slower                                               |
| pyflate                    | 506 ms                                                                       | 517 ms: 1.02x slower                                                 |
| docutils                   | 2.80 sec                                                                     | 2.86 sec: 1.02x slower                                               |
| json_dumps                 | 10.6 ms                                                                      | 10.8 ms: 1.02x slower                                                |
| async_tree_io              | 1.07 sec                                                                     | 1.09 sec: 1.02x slower                                               |
| xml_etree_generate         | 83.8 ms                                                                      | 86.3 ms: 1.03x slower                                                |
| coverage                   | 79.0 ms                                                                      | 81.3 ms: 1.03x slower                                                |
| logging_simple             | 6.37 us                                                                      | 6.56 us: 1.03x slower                                                |
| deltablue                  | 3.62 ms                                                                      | 3.73 ms: 1.03x slower                                                |
| scimark_lu                 | 100 ms                                                                       | 103 ms: 1.03x slower                                                 |
| async_tree_memoization     | 540 ms                                                                       | 557 ms: 1.03x slower                                                 |
| coroutines                 | 22.1 ms                                                                      | 22.8 ms: 1.03x slower                                                |
| mdp                        | 2.52 sec                                                                     | 2.59 sec: 1.03x slower                                               |
| sqlglot_transpile          | 1.77 ms                                                                      | 1.83 ms: 1.03x slower                                                |
| async_tree_none_tg         | 436 ms                                                                       | 450 ms: 1.03x slower                                                 |
| sympy_expand               | 486 ms                                                                       | 502 ms: 1.03x slower                                                 |
| async_tree_none            | 428 ms                                                                       | 443 ms: 1.03x slower                                                 |
| deepcopy_memo              | 36.6 us                                                                      | 37.8 us: 1.03x slower                                                |
| logging_format             | 7.14 us                                                                      | 7.40 us: 1.04x slower                                                |
| chameleon                  | 7.44 ms                                                                      | 7.71 ms: 1.04x slower                                                |
| float                      | 77.9 ms                                                                      | 80.9 ms: 1.04x slower                                                |
| regex_compile              | 143 ms                                                                       | 149 ms: 1.04x slower                                                 |
| 2to3                       | 290 ms                                                                       | 301 ms: 1.04x slower                                                 |
| sympy_str                  | 287 ms                                                                       | 300 ms: 1.04x slower                                                 |
| async_generators           | 364 ms                                                                       | 381 ms: 1.05x slower                                                 |
| pycparser                  | 1.27 sec                                                                     | 1.32 sec: 1.05x slower                                               |
| scimark_sor                | 145 ms                                                                       | 152 ms: 1.05x slower                                                 |
| sqlglot_normalize          | 115 ms                                                                       | 121 ms: 1.05x slower                                                 |
| async_tree_memoization_tg  | 553 ms                                                                       | 580 ms: 1.05x slower                                                 |
| unpickle_list              | 4.58 us                                                                      | 4.82 us: 1.05x slower                                                |
| sympy_integrate            | 22.9 ms                                                                      | 24.2 ms: 1.06x slower                                                |
| deepcopy_reduce            | 3.20 us                                                                      | 3.38 us: 1.06x slower                                                |
| unpickle                   | 14.5 us                                                                      | 15.4 us: 1.06x slower                                                |
| sympy_sum                  | 149 ms                                                                       | 158 ms: 1.06x slower                                                 |
| meteor_contest             | 126 ms                                                                       | 134 ms: 1.06x slower                                                 |
| sqlglot_optimize           | 58.1 ms                                                                      | 61.8 ms: 1.06x slower                                                |
| deepcopy                   | 356 us                                                                       | 380 us: 1.07x slower                                                 |
| mako                       | 10.3 ms                                                                      | 11.1 ms: 1.08x slower                                                |
| pprint_safe_repr           | 797 ms                                                                       | 864 ms: 1.08x slower                                                 |
| typing_runtime_protocols   | 121 us                                                                       | 132 us: 1.08x slower                                                 |
| bench_mp_pool              | 4.57 ms                                                                      | 4.98 ms: 1.09x slower                                                |
| pprint_pformat             | 1.63 sec                                                                     | 1.78 sec: 1.09x slower                                               |
| fannkuch                   | 380 ms                                                                       | 420 ms: 1.10x slower                                                 |
| gc_traversal               | 3.54 ms                                                                      | 3.92 ms: 1.11x slower                                                |
| raytrace                   | 262 ms                                                                       | 292 ms: 1.11x slower                                                 |
| spectral_norm              | 90.5 ms                                                                      | 102 ms: 1.12x slower                                                 |
| unpickle_pure_python       | 210 us                                                                       | 236 us: 1.12x slower                                                 |
| crypto_pyaes               | 71.3 ms                                                                      | 81.3 ms: 1.14x slower                                                |
| scimark_fft                | 313 ms                                                                       | 364 ms: 1.16x slower                                                 |
| nqueens                    | 89.0 ms                                                                      | 104 ms: 1.17x slower                                                 |
| hexiom                     | 6.44 ms                                                                      | 7.72 ms: 1.20x slower                                                |
| chaos                      | 60.2 ms                                                                      | 72.1 ms: 1.20x slower                                                |
| comprehensions             | 16.6 us                                                                      | 20.2 us: 1.22x slower                                                |
| nbody                      | 85.2 ms                                                                      | 104 ms: 1.22x slower                                                 |
| scimark_monte_carlo        | 66.1 ms                                                                      | 82.1 ms: 1.24x slower                                                |
| Geometric mean             | (ref)                                                                        | 1.04x slower                                                         |

Benchmark hidden because not significant (6): asyncio_tcp, generators, pidigits, asyncio_tcp_ssl, bench_thread_pool, mypy2


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.02x
- 95% likely to have a slowdown of 1.02x
- 99% likely to have a slowdown of 1.02x
