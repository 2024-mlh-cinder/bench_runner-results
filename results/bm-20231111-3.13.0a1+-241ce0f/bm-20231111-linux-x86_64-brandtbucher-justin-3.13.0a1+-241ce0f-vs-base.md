
# Results vs. base

- fork: brandtbucher
- ref: justin
- machine: linux-x86_64
- commit hash: 241ce0f
- commit date: 2023-11-11
- overall geometric mean: 1.04x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.02x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231111-linux-x86_64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f | bm-20231111-linux-x86_64-brandtbucher-justin-3.13.0a1+-241ce0f |
|----------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------:|
| 2to3           | 261 ms                                                                 | 275 ms: 1.05x slower                                           |
| chameleon      | 6.96 ms                                                                | 7.37 ms: 1.06x slower                                          |
| docutils       | 2.59 sec                                                               | 2.64 sec: 1.02x slower                                         |
| tornado_http   | 94.4 ms                                                                | 96.8 ms: 1.03x slower                                          |
| Geometric mean | (ref)                                                                  | 1.04x slower                                                   |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231111-linux-x86_64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f | bm-20231111-linux-x86_64-brandtbucher-justin-3.13.0a1+-241ce0f |
|----------------------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------:|
| async_tree_none_tg         | 455 ms                                                                 | 460 ms: 1.01x slower                                           |
| async_tree_io              | 1.18 sec                                                               | 1.20 sec: 1.01x slower                                         |
| async_tree_io_tg           | 1.22 sec                                                               | 1.24 sec: 1.02x slower                                         |
| async_tree_memoization_tg  | 594 ms                                                                 | 606 ms: 1.02x slower                                           |
| async_tree_none            | 435 ms                                                                 | 446 ms: 1.02x slower                                           |
| async_tree_cpu_io_mixed_tg | 738 ms                                                                 | 757 ms: 1.03x slower                                           |
| async_tree_cpu_io_mixed    | 709 ms                                                                 | 729 ms: 1.03x slower                                           |
| async_tree_memoization     | 559 ms                                                                 | 576 ms: 1.03x slower                                           |
| Geometric mean             | (ref)                                                                  | 1.02x slower                                                   |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231111-linux-x86_64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f | bm-20231111-linux-x86_64-brandtbucher-justin-3.13.0a1+-241ce0f |
|----------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------:|
| pidigits       | 188 ms                                                                 | 188 ms: 1.00x slower                                           |
| float          | 81.1 ms                                                                | 88.9 ms: 1.10x slower                                          |
| nbody          | 88.2 ms                                                                | 101 ms: 1.15x slower                                           |
| Geometric mean | (ref)                                                                  | 1.08x slower                                                   |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231111-linux-x86_64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f | bm-20231111-linux-x86_64-brandtbucher-justin-3.13.0a1+-241ce0f |
|----------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------:|
| regex_dna      | 212 ms                                                                 | 212 ms: 1.00x faster                                           |
| regex_effbot   | 3.61 ms                                                                | 3.62 ms: 1.00x slower                                          |
| regex_compile  | 134 ms                                                                 | 143 ms: 1.07x slower                                           |
| Geometric mean | (ref)                                                                  | 1.02x slower                                                   |

Benchmark hidden because not significant (1): regex_v8

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231111-linux-x86_64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f | bm-20231111-linux-x86_64-brandtbucher-justin-3.13.0a1+-241ce0f |
|----------------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------:|
| pickle_list          | 5.03 us                                                                | 4.80 us: 1.05x faster                                          |
| pickle_dict          | 33.9 us                                                                | 32.9 us: 1.03x faster                                          |
| pickle               | 11.3 us                                                                | 11.4 us: 1.01x slower                                          |
| xml_etree_parse      | 158 ms                                                                 | 160 ms: 1.01x slower                                           |
| xml_etree_process    | 59.0 ms                                                                | 59.9 ms: 1.02x slower                                          |
| json_dumps           | 10.3 ms                                                                | 10.5 ms: 1.02x slower                                          |
| xml_etree_generate   | 85.8 ms                                                                | 87.4 ms: 1.02x slower                                          |
| pickle_pure_python   | 303 us                                                                 | 309 us: 1.02x slower                                           |
| unpickle             | 14.6 us                                                                | 15.1 us: 1.03x slower                                          |
| xml_etree_iterparse  | 105 ms                                                                 | 110 ms: 1.05x slower                                           |
| unpickle_pure_python | 219 us                                                                 | 231 us: 1.05x slower                                           |
| tomli_loads          | 2.14 sec                                                               | 2.29 sec: 1.07x slower                                         |
| unpickle_list        | 5.30 us                                                                | 5.68 us: 1.07x slower                                          |
| Geometric mean       | (ref)                                                                  | 1.02x slower                                                   |

Benchmark hidden because not significant (1): json_loads

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231111-linux-x86_64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f | bm-20231111-linux-x86_64-brandtbucher-justin-3.13.0a1+-241ce0f |
|------------------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------:|
| python_startup         | 10.3 ms                                                                | 10.4 ms: 1.01x slower                                          |
| python_startup_no_site | 9.02 ms                                                                | 9.11 ms: 1.01x slower                                          |
| Geometric mean         | (ref)                                                                  | 1.01x slower                                                   |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231111-linux-x86_64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f | bm-20231111-linux-x86_64-brandtbucher-justin-3.13.0a1+-241ce0f |
|-----------|:----------------------------------------------------------------------:|:--------------------------------------------------------------:|
| mako      | 11.4 ms                                                                | 12.5 ms: 1.09x slower                                          |

All benchmarks:
===============

| Benchmark                  | bm-20231111-linux-x86_64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f | bm-20231111-linux-x86_64-brandtbucher-justin-3.13.0a1+-241ce0f |
|----------------------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------:|
| gc_traversal               | 4.04 ms                                                                | 3.82 ms: 1.06x faster                                          |
| pickle_list                | 5.03 us                                                                | 4.80 us: 1.05x faster                                          |
| pickle_dict                | 33.9 us                                                                | 32.9 us: 1.03x faster                                          |
| coverage                   | 96.1 ms                                                                | 95.2 ms: 1.01x faster                                          |
| richards_super             | 54.3 ms                                                                | 53.8 ms: 1.01x faster                                          |
| create_gc_cycles           | 1.48 ms                                                                | 1.47 ms: 1.01x faster                                          |
| regex_dna                  | 212 ms                                                                 | 212 ms: 1.00x faster                                           |
| pidigits                   | 188 ms                                                                 | 188 ms: 1.00x slower                                           |
| regex_effbot               | 3.61 ms                                                                | 3.62 ms: 1.00x slower                                          |
| asyncio_tcp                | 482 ms                                                                 | 486 ms: 1.01x slower                                           |
| python_startup             | 10.3 ms                                                                | 10.4 ms: 1.01x slower                                          |
| pickle                     | 11.3 us                                                                | 11.4 us: 1.01x slower                                          |
| asyncio_tcp_ssl            | 1.78 sec                                                               | 1.80 sec: 1.01x slower                                         |
| xml_etree_parse            | 158 ms                                                                 | 160 ms: 1.01x slower                                           |
| spectral_norm              | 112 ms                                                                 | 113 ms: 1.01x slower                                           |
| json                       | 5.13 ms                                                                | 5.18 ms: 1.01x slower                                          |
| python_startup_no_site     | 9.02 ms                                                                | 9.11 ms: 1.01x slower                                          |
| async_tree_none_tg         | 455 ms                                                                 | 460 ms: 1.01x slower                                           |
| pathlib                    | 19.0 ms                                                                | 19.3 ms: 1.01x slower                                          |
| generators                 | 28.8 ms                                                                | 29.1 ms: 1.01x slower                                          |
| pycparser                  | 1.16 sec                                                               | 1.18 sec: 1.01x slower                                         |
| sqlglot_optimize           | 53.3 ms                                                                | 54.0 ms: 1.01x slower                                          |
| async_tree_io              | 1.18 sec                                                               | 1.20 sec: 1.01x slower                                         |
| coroutines                 | 22.0 ms                                                                | 22.4 ms: 1.01x slower                                          |
| sqlglot_normalize          | 105 ms                                                                 | 107 ms: 1.02x slower                                           |
| xml_etree_process          | 59.0 ms                                                                | 59.9 ms: 1.02x slower                                          |
| async_tree_io_tg           | 1.22 sec                                                               | 1.24 sec: 1.02x slower                                         |
| deepcopy                   | 343 us                                                                 | 349 us: 1.02x slower                                           |
| json_dumps                 | 10.3 ms                                                                | 10.5 ms: 1.02x slower                                          |
| xml_etree_generate         | 85.8 ms                                                                | 87.4 ms: 1.02x slower                                          |
| pickle_pure_python         | 303 us                                                                 | 309 us: 1.02x slower                                           |
| async_tree_memoization_tg  | 594 ms                                                                 | 606 ms: 1.02x slower                                           |
| docutils                   | 2.59 sec                                                               | 2.64 sec: 1.02x slower                                         |
| dulwich_log                | 65.5 ms                                                                | 66.9 ms: 1.02x slower                                          |
| deepcopy_reduce            | 3.04 us                                                                | 3.11 us: 1.02x slower                                          |
| deepcopy_memo              | 38.4 us                                                                | 39.3 us: 1.02x slower                                          |
| sympy_str                  | 268 ms                                                                 | 274 ms: 1.02x slower                                           |
| bench_thread_pool          | 828 us                                                                 | 848 us: 1.02x slower                                           |
| sympy_expand               | 450 ms                                                                 | 460 ms: 1.02x slower                                           |
| async_tree_none            | 435 ms                                                                 | 446 ms: 1.02x slower                                           |
| tornado_http               | 94.4 ms                                                                | 96.8 ms: 1.03x slower                                          |
| async_tree_cpu_io_mixed_tg | 738 ms                                                                 | 757 ms: 1.03x slower                                           |
| mypy2                      | 339 ms                                                                 | 349 ms: 1.03x slower                                           |
| sqlglot_parse              | 1.27 ms                                                                | 1.31 ms: 1.03x slower                                          |
| sqlglot_transpile          | 1.58 ms                                                                | 1.63 ms: 1.03x slower                                          |
| async_tree_cpu_io_mixed    | 709 ms                                                                 | 729 ms: 1.03x slower                                           |
| scimark_lu                 | 114 ms                                                                 | 118 ms: 1.03x slower                                           |
| async_tree_memoization     | 559 ms                                                                 | 576 ms: 1.03x slower                                           |
| unpickle                   | 14.6 us                                                                | 15.1 us: 1.03x slower                                          |
| sympy_sum                  | 147 ms                                                                 | 151 ms: 1.03x slower                                           |
| telco                      | 8.29 ms                                                                | 8.58 ms: 1.04x slower                                          |
| async_generators           | 445 ms                                                                 | 461 ms: 1.04x slower                                           |
| xml_etree_iterparse        | 105 ms                                                                 | 110 ms: 1.05x slower                                           |
| raytrace                   | 275 ms                                                                 | 288 ms: 1.05x slower                                           |
| logging_simple             | 5.69 us                                                                | 5.95 us: 1.05x slower                                          |
| pprint_safe_repr           | 733 ms                                                                 | 769 ms: 1.05x slower                                           |
| typing_runtime_protocols   | 116 us                                                                 | 121 us: 1.05x slower                                           |
| 2to3                       | 261 ms                                                                 | 275 ms: 1.05x slower                                           |
| logging_format             | 6.21 us                                                                | 6.53 us: 1.05x slower                                          |
| scimark_fft                | 364 ms                                                                 | 383 ms: 1.05x slower                                           |
| meteor_contest             | 109 ms                                                                 | 114 ms: 1.05x slower                                           |
| unpickle_pure_python       | 219 us                                                                 | 231 us: 1.05x slower                                           |
| pprint_pformat             | 1.49 sec                                                               | 1.57 sec: 1.05x slower                                         |
| chameleon                  | 6.96 ms                                                                | 7.37 ms: 1.06x slower                                          |
| sympy_integrate            | 19.3 ms                                                                | 20.6 ms: 1.07x slower                                          |
| tomli_loads                | 2.14 sec                                                               | 2.29 sec: 1.07x slower                                         |
| regex_compile              | 134 ms                                                                 | 143 ms: 1.07x slower                                           |
| unpickle_list              | 5.30 us                                                                | 5.68 us: 1.07x slower                                          |
| scimark_monte_carlo        | 68.5 ms                                                                | 74.4 ms: 1.09x slower                                          |
| mdp                        | 2.55 sec                                                               | 2.77 sec: 1.09x slower                                         |
| scimark_sor                | 121 ms                                                                 | 131 ms: 1.09x slower                                           |
| mako                       | 11.4 ms                                                                | 12.5 ms: 1.09x slower                                          |
| go                         | 140 ms                                                                 | 152 ms: 1.09x slower                                           |
| float                      | 81.1 ms                                                                | 88.9 ms: 1.10x slower                                          |
| crypto_pyaes               | 71.3 ms                                                                | 78.5 ms: 1.10x slower                                          |
| chaos                      | 60.2 ms                                                                | 66.5 ms: 1.10x slower                                          |
| pyflate                    | 468 ms                                                                 | 518 ms: 1.11x slower                                           |
| nqueens                    | 81.7 ms                                                                | 93.5 ms: 1.15x slower                                          |
| fannkuch                   | 394 ms                                                                 | 453 ms: 1.15x slower                                           |
| nbody                      | 88.2 ms                                                                | 101 ms: 1.15x slower                                           |
| unpack_sequence            | 46.1 ns                                                                | 54.2 ns: 1.17x slower                                          |
| scimark_sparse_mat_mult    | 4.68 ms                                                                | 5.61 ms: 1.20x slower                                          |
| deltablue                  | 3.29 ms                                                                | 4.14 ms: 1.26x slower                                          |
| hexiom                     | 6.17 ms                                                                | 7.80 ms: 1.26x slower                                          |
| comprehensions             | 16.4 us                                                                | 20.9 us: 1.28x slower                                          |
| Geometric mean             | (ref)                                                                  | 1.04x slower                                                   |

Benchmark hidden because not significant (7): sqlite_synth, regex_v8, json_loads, bench_mp_pool, asyncio_websockets, logging_silent, richards


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.02x
- 95% likely to have a slowdown of 1.02x
- 99% likely to have a slowdown of 1.02x
