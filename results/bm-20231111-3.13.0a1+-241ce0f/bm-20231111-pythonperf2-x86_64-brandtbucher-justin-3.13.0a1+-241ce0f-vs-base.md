
# Results vs. base

- fork: brandtbucher
- ref: justin
- machine: linux-x86_64
- commit hash: 241ce0f
- commit date: 2023-11-11
- overall geometric mean: 1.03x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.01x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231111-pythonperf2-x86_64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f | bm-20231111-pythonperf2-x86_64-brandtbucher-justin-3.13.0a1+-241ce0f |
|----------------|:----------------------------------------------------------------------------:|:--------------------------------------------------------------------:|
| 2to3           | 292 ms                                                                       | 300 ms: 1.03x slower                                                 |
| chameleon      | 7.22 ms                                                                      | 7.65 ms: 1.06x slower                                                |
| docutils       | 2.84 sec                                                                     | 2.87 sec: 1.01x slower                                               |
| tornado_http   | 119 ms                                                                       | 120 ms: 1.01x slower                                                 |
| Geometric mean | (ref)                                                                        | 1.03x slower                                                         |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231111-pythonperf2-x86_64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f | bm-20231111-pythonperf2-x86_64-brandtbucher-justin-3.13.0a1+-241ce0f |
|----------------------------|:----------------------------------------------------------------------------:|:--------------------------------------------------------------------:|
| async_tree_io_tg           | 1.10 sec                                                                     | 1.11 sec: 1.01x slower                                               |
| async_tree_io              | 1.08 sec                                                                     | 1.09 sec: 1.01x slower                                               |
| async_tree_cpu_io_mixed_tg | 711 ms                                                                       | 723 ms: 1.02x slower                                                 |
| async_tree_memoization     | 546 ms                                                                       | 556 ms: 1.02x slower                                                 |
| async_tree_cpu_io_mixed    | 695 ms                                                                       | 708 ms: 1.02x slower                                                 |
| async_tree_none_tg         | 439 ms                                                                       | 449 ms: 1.02x slower                                                 |
| async_tree_none            | 433 ms                                                                       | 445 ms: 1.03x slower                                                 |
| async_tree_memoization_tg  | 561 ms                                                                       | 582 ms: 1.04x slower                                                 |
| Geometric mean             | (ref)                                                                        | 1.02x slower                                                         |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231111-pythonperf2-x86_64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f | bm-20231111-pythonperf2-x86_64-brandtbucher-justin-3.13.0a1+-241ce0f |
|----------------|:----------------------------------------------------------------------------:|:--------------------------------------------------------------------:|
| float          | 79.3 ms                                                                      | 82.7 ms: 1.04x slower                                                |
| nbody          | 84.7 ms                                                                      | 98.3 ms: 1.16x slower                                                |
| Geometric mean | (ref)                                                                        | 1.07x slower                                                         |

Benchmark hidden because not significant (1): pidigits

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231111-pythonperf2-x86_64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f | bm-20231111-pythonperf2-x86_64-brandtbucher-justin-3.13.0a1+-241ce0f |
|----------------|:----------------------------------------------------------------------------:|:--------------------------------------------------------------------:|
| regex_dna      | 244 ms                                                                       | 237 ms: 1.03x faster                                                 |
| regex_v8       | 25.7 ms                                                                      | 25.4 ms: 1.01x faster                                                |
| regex_effbot   | 3.43 ms                                                                      | 3.51 ms: 1.02x slower                                                |
| regex_compile  | 143 ms                                                                       | 150 ms: 1.05x slower                                                 |
| Geometric mean | (ref)                                                                        | 1.01x slower                                                         |

Benchmarks with tag 'serialize':
================================

| Benchmark           | bm-20231111-pythonperf2-x86_64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f | bm-20231111-pythonperf2-x86_64-brandtbucher-justin-3.13.0a1+-241ce0f |
|---------------------|:----------------------------------------------------------------------------:|:--------------------------------------------------------------------:|
| pickle_pure_python  | 321 us                                                                       | 309 us: 1.04x faster                                                 |
| json_dumps          | 10.6 ms                                                                      | 10.4 ms: 1.02x faster                                                |
| xml_etree_iterparse | 106 ms                                                                       | 104 ms: 1.02x faster                                                 |
| json_loads          | 24.6 us                                                                      | 24.4 us: 1.01x faster                                                |
| xml_etree_parse     | 146 ms                                                                       | 145 ms: 1.01x faster                                                 |
| xml_etree_generate  | 85.5 ms                                                                      | 85.9 ms: 1.01x slower                                                |
| unpickle_list       | 4.76 us                                                                      | 4.79 us: 1.01x slower                                                |
| pickle              | 10.1 us                                                                      | 10.3 us: 1.01x slower                                                |
| pickle_list         | 4.36 us                                                                      | 4.42 us: 1.01x slower                                                |
| xml_etree_process   | 58.4 ms                                                                      | 59.2 ms: 1.02x slower                                                |
| unpickle            | 14.4 us                                                                      | 14.7 us: 1.02x slower                                                |
| tomli_loads         | 2.23 sec                                                                     | 2.43 sec: 1.09x slower                                               |
| Geometric mean      | (ref)                                                                        | 1.00x slower                                                         |

Benchmark hidden because not significant (2): unpickle_pure_python, pickle_dict

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231111-pythonperf2-x86_64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f | bm-20231111-pythonperf2-x86_64-brandtbucher-justin-3.13.0a1+-241ce0f |
|------------------------|:----------------------------------------------------------------------------:|:--------------------------------------------------------------------:|
| python_startup         | 12.8 ms                                                                      | 12.9 ms: 1.00x slower                                                |
| python_startup_no_site | 11.3 ms                                                                      | 11.4 ms: 1.01x slower                                                |
| Geometric mean         | (ref)                                                                        | 1.00x slower                                                         |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231111-pythonperf2-x86_64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f | bm-20231111-pythonperf2-x86_64-brandtbucher-justin-3.13.0a1+-241ce0f |
|-----------|:----------------------------------------------------------------------------:|:--------------------------------------------------------------------:|
| mako      | 10.1 ms                                                                      | 11.0 ms: 1.09x slower                                                |

All benchmarks:
===============

| Benchmark                  | bm-20231111-pythonperf2-x86_64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f | bm-20231111-pythonperf2-x86_64-brandtbucher-justin-3.13.0a1+-241ce0f |
|----------------------------|:----------------------------------------------------------------------------:|:--------------------------------------------------------------------:|
| unpack_sequence            | 50.8 ns                                                                      | 43.1 ns: 1.18x faster                                                |
| richards                   | 55.8 ms                                                                      | 50.9 ms: 1.10x faster                                                |
| create_gc_cycles           | 1.63 ms                                                                      | 1.53 ms: 1.06x faster                                                |
| richards_super             | 61.5 ms                                                                      | 58.8 ms: 1.05x faster                                                |
| pickle_pure_python         | 321 us                                                                       | 309 us: 1.04x faster                                                 |
| regex_dna                  | 244 ms                                                                       | 237 ms: 1.03x faster                                                 |
| json_dumps                 | 10.6 ms                                                                      | 10.4 ms: 1.02x faster                                                |
| logging_format             | 7.33 us                                                                      | 7.19 us: 1.02x faster                                                |
| xml_etree_iterparse        | 106 ms                                                                       | 104 ms: 1.02x faster                                                 |
| generators                 | 35.9 ms                                                                      | 35.5 ms: 1.01x faster                                                |
| deepcopy                   | 372 us                                                                       | 367 us: 1.01x faster                                                 |
| json                       | 5.14 ms                                                                      | 5.08 ms: 1.01x faster                                                |
| json_loads                 | 24.6 us                                                                      | 24.4 us: 1.01x faster                                                |
| xml_etree_parse            | 146 ms                                                                       | 145 ms: 1.01x faster                                                 |
| asyncio_websockets         | 390 ms                                                                       | 387 ms: 1.01x faster                                                 |
| regex_v8                   | 25.7 ms                                                                      | 25.4 ms: 1.01x faster                                                |
| logging_simple             | 6.61 us                                                                      | 6.56 us: 1.01x faster                                                |
| pyflate                    | 510 ms                                                                       | 507 ms: 1.01x faster                                                 |
| sqlite_synth               | 2.69 us                                                                      | 2.69 us: 1.00x faster                                                |
| asyncio_tcp_ssl            | 1.58 sec                                                                     | 1.58 sec: 1.00x slower                                               |
| python_startup             | 12.8 ms                                                                      | 12.9 ms: 1.00x slower                                                |
| logging_silent             | 95.3 ns                                                                      | 95.6 ns: 1.00x slower                                                |
| xml_etree_generate         | 85.5 ms                                                                      | 85.9 ms: 1.01x slower                                                |
| sqlglot_transpile          | 1.82 ms                                                                      | 1.83 ms: 1.01x slower                                                |
| spectral_norm              | 90.6 ms                                                                      | 91.1 ms: 1.01x slower                                                |
| unpickle_list              | 4.76 us                                                                      | 4.79 us: 1.01x slower                                                |
| python_startup_no_site     | 11.3 ms                                                                      | 11.4 ms: 1.01x slower                                                |
| sqlglot_normalize          | 117 ms                                                                       | 118 ms: 1.01x slower                                                 |
| pathlib                    | 19.6 ms                                                                      | 19.7 ms: 1.01x slower                                                |
| scimark_sor                | 149 ms                                                                       | 150 ms: 1.01x slower                                                 |
| async_tree_io_tg           | 1.10 sec                                                                     | 1.11 sec: 1.01x slower                                               |
| pickle                     | 10.1 us                                                                      | 10.3 us: 1.01x slower                                                |
| dulwich_log                | 67.2 ms                                                                      | 68.0 ms: 1.01x slower                                                |
| tornado_http               | 119 ms                                                                       | 120 ms: 1.01x slower                                                 |
| sympy_expand               | 492 ms                                                                       | 498 ms: 1.01x slower                                                 |
| docutils                   | 2.84 sec                                                                     | 2.87 sec: 1.01x slower                                               |
| async_tree_io              | 1.08 sec                                                                     | 1.09 sec: 1.01x slower                                               |
| pickle_list                | 4.36 us                                                                      | 4.42 us: 1.01x slower                                                |
| xml_etree_process          | 58.4 ms                                                                      | 59.2 ms: 1.02x slower                                                |
| sympy_sum                  | 151 ms                                                                       | 153 ms: 1.02x slower                                                 |
| sympy_str                  | 289 ms                                                                       | 294 ms: 1.02x slower                                                 |
| async_tree_cpu_io_mixed_tg | 711 ms                                                                       | 723 ms: 1.02x slower                                                 |
| async_tree_memoization     | 546 ms                                                                       | 556 ms: 1.02x slower                                                 |
| async_tree_cpu_io_mixed    | 695 ms                                                                       | 708 ms: 1.02x slower                                                 |
| mypy2                      | 366 ms                                                                       | 374 ms: 1.02x slower                                                 |
| async_tree_none_tg         | 439 ms                                                                       | 449 ms: 1.02x slower                                                 |
| meteor_contest             | 130 ms                                                                       | 133 ms: 1.02x slower                                                 |
| unpickle                   | 14.4 us                                                                      | 14.7 us: 1.02x slower                                                |
| regex_effbot               | 3.43 ms                                                                      | 3.51 ms: 1.02x slower                                                |
| async_tree_none            | 433 ms                                                                       | 445 ms: 1.03x slower                                                 |
| coroutines                 | 22.2 ms                                                                      | 22.7 ms: 1.03x slower                                                |
| 2to3                       | 292 ms                                                                       | 300 ms: 1.03x slower                                                 |
| telco                      | 7.94 ms                                                                      | 8.16 ms: 1.03x slower                                                |
| typing_runtime_protocols   | 124 us                                                                       | 128 us: 1.03x slower                                                 |
| go                         | 169 ms                                                                       | 174 ms: 1.03x slower                                                 |
| deepcopy_memo              | 36.7 us                                                                      | 37.9 us: 1.03x slower                                                |
| mdp                        | 2.53 sec                                                                     | 2.61 sec: 1.03x slower                                               |
| pprint_pformat             | 1.64 sec                                                                     | 1.70 sec: 1.03x slower                                               |
| async_tree_memoization_tg  | 561 ms                                                                       | 582 ms: 1.04x slower                                                 |
| pprint_safe_repr           | 801 ms                                                                       | 832 ms: 1.04x slower                                                 |
| sympy_integrate            | 23.0 ms                                                                      | 23.9 ms: 1.04x slower                                                |
| pycparser                  | 1.27 sec                                                                     | 1.32 sec: 1.04x slower                                               |
| float                      | 79.3 ms                                                                      | 82.7 ms: 1.04x slower                                                |
| regex_compile              | 143 ms                                                                       | 150 ms: 1.05x slower                                                 |
| raytrace                   | 271 ms                                                                       | 285 ms: 1.05x slower                                                 |
| scimark_lu                 | 98.6 ms                                                                      | 105 ms: 1.06x slower                                                 |
| chameleon                  | 7.22 ms                                                                      | 7.65 ms: 1.06x slower                                                |
| deltablue                  | 3.60 ms                                                                      | 3.83 ms: 1.07x slower                                                |
| fannkuch                   | 400 ms                                                                       | 428 ms: 1.07x slower                                                 |
| async_generators           | 359 ms                                                                       | 389 ms: 1.08x slower                                                 |
| scimark_sparse_mat_mult    | 4.19 ms                                                                      | 4.55 ms: 1.08x slower                                                |
| tomli_loads                | 2.23 sec                                                                     | 2.43 sec: 1.09x slower                                               |
| mako                       | 10.1 ms                                                                      | 11.0 ms: 1.09x slower                                                |
| chaos                      | 61.4 ms                                                                      | 68.0 ms: 1.11x slower                                                |
| scimark_monte_carlo        | 67.7 ms                                                                      | 75.2 ms: 1.11x slower                                                |
| crypto_pyaes               | 70.6 ms                                                                      | 78.5 ms: 1.11x slower                                                |
| gc_traversal               | 3.49 ms                                                                      | 3.91 ms: 1.12x slower                                                |
| scimark_fft                | 308 ms                                                                       | 348 ms: 1.13x slower                                                 |
| nbody                      | 84.7 ms                                                                      | 98.3 ms: 1.16x slower                                                |
| nqueens                    | 89.6 ms                                                                      | 104 ms: 1.17x slower                                                 |
| hexiom                     | 6.45 ms                                                                      | 8.19 ms: 1.27x slower                                                |
| bench_mp_pool              | 4.82 ms                                                                      | 6.19 ms: 1.28x slower                                                |
| comprehensions             | 16.3 us                                                                      | 21.9 us: 1.34x slower                                                |
| Geometric mean             | (ref)                                                                        | 1.03x slower                                                         |

Benchmark hidden because not significant (9): coverage, asyncio_tcp, unpickle_pure_python, pidigits, pickle_dict, sqlglot_optimize, deepcopy_reduce, sqlglot_parse, bench_thread_pool


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.01x
- 95% likely to have a slowdown of 1.01x
- 99% likely to have a slowdown of 1.01x
