
# Results vs. base

- fork: faster-cpython
- ref: tier_2_exponential_b
- machine: linux-x86_64
- commit hash: eda8b06
- commit date: 2023-11-01
- overall geometric mean: 1.06x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.02x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231102-pythonperf2-x86_64-python-4fe22c73770fe86b01ef-3.13.0a1+-4fe22c7 | bm-20231101-pythonperf2-x86_64-faster%2dcpython-tier_2_exponential_b-3.13.0a1+-eda8b06 |
|----------------|:----------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------:|
| 2to3           | 291 ms                                                                       | 308 ms: 1.06x slower                                                                   |
| docutils       | 2.83 sec                                                                     | 2.94 sec: 1.04x slower                                                                 |
| tornado_http   | 118 ms                                                                       | 123 ms: 1.04x slower                                                                   |
| Geometric mean | (ref)                                                                        | 1.03x slower                                                                           |

Benchmark hidden because not significant (1): chameleon

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231102-pythonperf2-x86_64-python-4fe22c73770fe86b01ef-3.13.0a1+-4fe22c7 | bm-20231101-pythonperf2-x86_64-faster%2dcpython-tier_2_exponential_b-3.13.0a1+-eda8b06 |
|----------------------------|:----------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------:|
| async_tree_io              | 1.08 sec                                                                     | 1.10 sec: 1.02x slower                                                                 |
| async_tree_cpu_io_mixed    | 699 ms                                                                       | 712 ms: 1.02x slower                                                                   |
| async_tree_cpu_io_mixed_tg | 716 ms                                                                       | 731 ms: 1.02x slower                                                                   |
| async_tree_io_tg           | 1.09 sec                                                                     | 1.12 sec: 1.03x slower                                                                 |
| async_tree_memoization     | 546 ms                                                                       | 562 ms: 1.03x slower                                                                   |
| async_tree_none            | 433 ms                                                                       | 447 ms: 1.03x slower                                                                   |
| async_tree_none_tg         | 438 ms                                                                       | 460 ms: 1.05x slower                                                                   |
| Geometric mean             | (ref)                                                                        | 1.02x slower                                                                           |

Benchmark hidden because not significant (1): async_tree_memoization_tg

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231102-pythonperf2-x86_64-python-4fe22c73770fe86b01ef-3.13.0a1+-4fe22c7 | bm-20231101-pythonperf2-x86_64-faster%2dcpython-tier_2_exponential_b-3.13.0a1+-eda8b06 |
|----------------|:----------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------:|
| pidigits       | 265 ms                                                                       | 265 ms: 1.00x slower                                                                   |
| nbody          | 87.6 ms                                                                      | 110 ms: 1.26x slower                                                                   |
| float          | 79.3 ms                                                                      | 103 ms: 1.30x slower                                                                   |
| Geometric mean | (ref)                                                                        | 1.18x slower                                                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231102-pythonperf2-x86_64-python-4fe22c73770fe86b01ef-3.13.0a1+-4fe22c7 | bm-20231101-pythonperf2-x86_64-faster%2dcpython-tier_2_exponential_b-3.13.0a1+-eda8b06 |
|----------------|:----------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------:|
| regex_v8       | 25.3 ms                                                                      | 24.5 ms: 1.04x faster                                                                  |
| regex_effbot   | 3.50 ms                                                                      | 3.47 ms: 1.01x faster                                                                  |
| regex_dna      | 234 ms                                                                       | 243 ms: 1.04x slower                                                                   |
| regex_compile  | 145 ms                                                                       | 174 ms: 1.20x slower                                                                   |
| Geometric mean | (ref)                                                                        | 1.04x slower                                                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231102-pythonperf2-x86_64-python-4fe22c73770fe86b01ef-3.13.0a1+-4fe22c7 | bm-20231101-pythonperf2-x86_64-faster%2dcpython-tier_2_exponential_b-3.13.0a1+-eda8b06 |
|----------------------|:----------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------:|
| unpickle_list        | 4.77 us                                                                      | 4.61 us: 1.03x faster                                                                  |
| pickle_list          | 4.38 us                                                                      | 4.24 us: 1.03x faster                                                                  |
| pickle               | 10.2 us                                                                      | 9.98 us: 1.02x faster                                                                  |
| unpickle             | 14.6 us                                                                      | 14.4 us: 1.01x faster                                                                  |
| pickle_pure_python   | 317 us                                                                       | 315 us: 1.00x faster                                                                   |
| json_loads           | 24.3 us                                                                      | 24.5 us: 1.00x slower                                                                  |
| xml_etree_process    | 58.1 ms                                                                      | 58.9 ms: 1.01x slower                                                                  |
| pickle_dict          | 31.5 us                                                                      | 32.0 us: 1.02x slower                                                                  |
| xml_etree_generate   | 85.1 ms                                                                      | 86.6 ms: 1.02x slower                                                                  |
| json_dumps           | 10.4 ms                                                                      | 10.6 ms: 1.02x slower                                                                  |
| xml_etree_parse      | 146 ms                                                                       | 149 ms: 1.02x slower                                                                   |
| xml_etree_iterparse  | 105 ms                                                                       | 110 ms: 1.05x slower                                                                   |
| unpickle_pure_python | 221 us                                                                       | 248 us: 1.12x slower                                                                   |
| tomli_loads          | 2.21 sec                                                                     | 2.78 sec: 1.26x slower                                                                 |
| Geometric mean       | (ref)                                                                        | 1.03x slower                                                                           |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231102-pythonperf2-x86_64-python-4fe22c73770fe86b01ef-3.13.0a1+-4fe22c7 | bm-20231101-pythonperf2-x86_64-faster%2dcpython-tier_2_exponential_b-3.13.0a1+-eda8b06 |
|------------------------|:----------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------:|
| python_startup         | 12.8 ms                                                                      | 12.9 ms: 1.01x slower                                                                  |
| python_startup_no_site | 11.3 ms                                                                      | 11.4 ms: 1.01x slower                                                                  |
| Geometric mean         | (ref)                                                                        | 1.01x slower                                                                           |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231102-pythonperf2-x86_64-python-4fe22c73770fe86b01ef-3.13.0a1+-4fe22c7 | bm-20231101-pythonperf2-x86_64-faster%2dcpython-tier_2_exponential_b-3.13.0a1+-eda8b06 |
|-----------|:----------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------:|
| mako      | 10.2 ms                                                                      | 14.3 ms: 1.41x slower                                                                  |

All benchmarks:
===============

| Benchmark                  | bm-20231102-pythonperf2-x86_64-python-4fe22c73770fe86b01ef-3.13.0a1+-4fe22c7 | bm-20231101-pythonperf2-x86_64-faster%2dcpython-tier_2_exponential_b-3.13.0a1+-eda8b06 |
|----------------------------|:----------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------:|
| bench_mp_pool              | 4.91 ms                                                                      | 4.50 ms: 1.09x faster                                                                  |
| unpack_sequence            | 52.8 ns                                                                      | 50.7 ns: 1.04x faster                                                                  |
| regex_v8                   | 25.3 ms                                                                      | 24.5 ms: 1.04x faster                                                                  |
| unpickle_list              | 4.77 us                                                                      | 4.61 us: 1.03x faster                                                                  |
| pickle_list                | 4.38 us                                                                      | 4.24 us: 1.03x faster                                                                  |
| coverage                   | 82.4 ms                                                                      | 80.2 ms: 1.03x faster                                                                  |
| pickle                     | 10.2 us                                                                      | 9.98 us: 1.02x faster                                                                  |
| create_gc_cycles           | 1.63 ms                                                                      | 1.60 ms: 1.02x faster                                                                  |
| richards                   | 54.0 ms                                                                      | 53.2 ms: 1.01x faster                                                                  |
| logging_format             | 7.46 us                                                                      | 7.35 us: 1.01x faster                                                                  |
| unpickle                   | 14.6 us                                                                      | 14.4 us: 1.01x faster                                                                  |
| richards_super             | 59.9 ms                                                                      | 59.1 ms: 1.01x faster                                                                  |
| regex_effbot               | 3.50 ms                                                                      | 3.47 ms: 1.01x faster                                                                  |
| generators                 | 35.6 ms                                                                      | 35.3 ms: 1.01x faster                                                                  |
| telco                      | 8.20 ms                                                                      | 8.15 ms: 1.01x faster                                                                  |
| pickle_pure_python         | 317 us                                                                       | 315 us: 1.00x faster                                                                   |
| sqlite_synth               | 2.71 us                                                                      | 2.70 us: 1.00x faster                                                                  |
| pidigits                   | 265 ms                                                                       | 265 ms: 1.00x slower                                                                   |
| spectral_norm              | 91.1 ms                                                                      | 91.5 ms: 1.00x slower                                                                  |
| json_loads                 | 24.3 us                                                                      | 24.5 us: 1.00x slower                                                                  |
| python_startup             | 12.8 ms                                                                      | 12.9 ms: 1.01x slower                                                                  |
| python_startup_no_site     | 11.3 ms                                                                      | 11.4 ms: 1.01x slower                                                                  |
| json                       | 5.16 ms                                                                      | 5.20 ms: 1.01x slower                                                                  |
| asyncio_tcp_ssl            | 1.58 sec                                                                     | 1.60 sec: 1.01x slower                                                                 |
| xml_etree_process          | 58.1 ms                                                                      | 58.9 ms: 1.01x slower                                                                  |
| asyncio_tcp                | 366 ms                                                                       | 371 ms: 1.01x slower                                                                   |
| pickle_dict                | 31.5 us                                                                      | 32.0 us: 1.02x slower                                                                  |
| xml_etree_generate         | 85.1 ms                                                                      | 86.6 ms: 1.02x slower                                                                  |
| async_tree_io              | 1.08 sec                                                                     | 1.10 sec: 1.02x slower                                                                 |
| async_tree_cpu_io_mixed    | 699 ms                                                                       | 712 ms: 1.02x slower                                                                   |
| deepcopy                   | 372 us                                                                       | 379 us: 1.02x slower                                                                   |
| json_dumps                 | 10.4 ms                                                                      | 10.6 ms: 1.02x slower                                                                  |
| async_tree_cpu_io_mixed_tg | 716 ms                                                                       | 731 ms: 1.02x slower                                                                   |
| xml_etree_parse            | 146 ms                                                                       | 149 ms: 1.02x slower                                                                   |
| pycparser                  | 1.34 sec                                                                     | 1.37 sec: 1.02x slower                                                                 |
| async_tree_io_tg           | 1.09 sec                                                                     | 1.12 sec: 1.03x slower                                                                 |
| async_tree_memoization     | 546 ms                                                                       | 562 ms: 1.03x slower                                                                   |
| sqlglot_transpile          | 1.82 ms                                                                      | 1.88 ms: 1.03x slower                                                                  |
| async_tree_none            | 433 ms                                                                       | 447 ms: 1.03x slower                                                                   |
| pathlib                    | 19.5 ms                                                                      | 20.2 ms: 1.03x slower                                                                  |
| deepcopy_reduce            | 3.26 us                                                                      | 3.37 us: 1.03x slower                                                                  |
| dulwich_log                | 68.2 ms                                                                      | 70.5 ms: 1.03x slower                                                                  |
| sqlglot_normalize          | 113 ms                                                                       | 117 ms: 1.04x slower                                                                   |
| regex_dna                  | 234 ms                                                                       | 243 ms: 1.04x slower                                                                   |
| sqlglot_parse              | 1.41 ms                                                                      | 1.46 ms: 1.04x slower                                                                  |
| bench_thread_pool          | 948 us                                                                       | 985 us: 1.04x slower                                                                   |
| async_generators           | 369 ms                                                                       | 383 ms: 1.04x slower                                                                   |
| mypy2                      | 366 ms                                                                       | 381 ms: 1.04x slower                                                                   |
| tornado_http               | 118 ms                                                                       | 123 ms: 1.04x slower                                                                   |
| docutils                   | 2.83 sec                                                                     | 2.94 sec: 1.04x slower                                                                 |
| sqlglot_optimize           | 57.5 ms                                                                      | 59.9 ms: 1.04x slower                                                                  |
| xml_etree_iterparse        | 105 ms                                                                       | 110 ms: 1.05x slower                                                                   |
| logging_silent             | 94.1 ns                                                                      | 98.5 ns: 1.05x slower                                                                  |
| async_tree_none_tg         | 438 ms                                                                       | 460 ms: 1.05x slower                                                                   |
| mdp                        | 2.51 sec                                                                     | 2.64 sec: 1.05x slower                                                                 |
| sympy_sum                  | 149 ms                                                                       | 157 ms: 1.05x slower                                                                   |
| meteor_contest             | 129 ms                                                                       | 136 ms: 1.06x slower                                                                   |
| scimark_sor                | 144 ms                                                                       | 152 ms: 1.06x slower                                                                   |
| scimark_lu                 | 100 ms                                                                       | 106 ms: 1.06x slower                                                                   |
| 2to3                       | 291 ms                                                                       | 308 ms: 1.06x slower                                                                   |
| typing_runtime_protocols   | 124 us                                                                       | 131 us: 1.06x slower                                                                   |
| sympy_expand               | 489 ms                                                                       | 519 ms: 1.06x slower                                                                   |
| go                         | 171 ms                                                                       | 182 ms: 1.07x slower                                                                   |
| sympy_str                  | 287 ms                                                                       | 306 ms: 1.07x slower                                                                   |
| gc_traversal               | 3.50 ms                                                                      | 3.74 ms: 1.07x slower                                                                  |
| pyflate                    | 502 ms                                                                       | 545 ms: 1.08x slower                                                                   |
| sympy_integrate            | 22.7 ms                                                                      | 24.6 ms: 1.08x slower                                                                  |
| fannkuch                   | 390 ms                                                                       | 425 ms: 1.09x slower                                                                   |
| crypto_pyaes               | 70.6 ms                                                                      | 77.2 ms: 1.09x slower                                                                  |
| raytrace                   | 272 ms                                                                       | 303 ms: 1.11x slower                                                                   |
| chaos                      | 61.1 ms                                                                      | 68.4 ms: 1.12x slower                                                                  |
| unpickle_pure_python       | 221 us                                                                       | 248 us: 1.12x slower                                                                   |
| deepcopy_memo              | 37.3 us                                                                      | 42.4 us: 1.13x slower                                                                  |
| pprint_safe_repr           | 795 ms                                                                       | 906 ms: 1.14x slower                                                                   |
| pprint_pformat             | 1.62 sec                                                                     | 1.86 sec: 1.14x slower                                                                 |
| scimark_fft                | 293 ms                                                                       | 343 ms: 1.17x slower                                                                   |
| scimark_monte_carlo        | 63.2 ms                                                                      | 75.3 ms: 1.19x slower                                                                  |
| regex_compile              | 145 ms                                                                       | 174 ms: 1.20x slower                                                                   |
| nbody                      | 87.6 ms                                                                      | 110 ms: 1.26x slower                                                                   |
| tomli_loads                | 2.21 sec                                                                     | 2.78 sec: 1.26x slower                                                                 |
| nqueens                    | 87.5 ms                                                                      | 112 ms: 1.28x slower                                                                   |
| float                      | 79.3 ms                                                                      | 103 ms: 1.30x slower                                                                   |
| scimark_sparse_mat_mult    | 4.06 ms                                                                      | 5.30 ms: 1.30x slower                                                                  |
| mako                       | 10.2 ms                                                                      | 14.3 ms: 1.41x slower                                                                  |
| deltablue                  | 3.63 ms                                                                      | 5.41 ms: 1.49x slower                                                                  |
| hexiom                     | 6.46 ms                                                                      | 9.99 ms: 1.55x slower                                                                  |
| comprehensions             | 16.4 us                                                                      | 26.1 us: 1.59x slower                                                                  |
| Geometric mean             | (ref)                                                                        | 1.06x slower                                                                           |

Benchmark hidden because not significant (5): chameleon, asyncio_websockets, logging_simple, async_tree_memoization_tg, coroutines


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.03x
- 95% likely to have a slowdown of 1.03x
- 99% likely to have a slowdown of 1.02x
