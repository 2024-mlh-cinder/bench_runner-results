
# Results vs. 3.12.0

- fork: faster-cpython
- ref: tier_2_exponential_b
- machine: linux-x86_64
- commit hash: 9c6f64f
- commit date: 2023-11-02
- overall geometric mean: 1.06x slower \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.02x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231102-pythonperf2-x86_64-faster%2dcpython-tier_2_exponential_b-3.13.0a1+-9c6f64f |
|----------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------------------:|
| 2to3           | 285 ms                                                       | 307 ms: 1.08x slower                                                                   |
| chameleon      | 7.27 ms                                                      | 7.50 ms: 1.03x slower                                                                  |
| docutils       | 2.89 sec                                                     | 2.98 sec: 1.03x slower                                                                 |
| tornado_http   | 122 ms                                                       | 124 ms: 1.02x slower                                                                   |
| Geometric mean | (ref)                                                        | 1.04x slower                                                                           |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231102-pythonperf2-x86_64-faster%2dcpython-tier_2_exponential_b-3.13.0a1+-9c6f64f |
|----------------------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------------------:|
| async_tree_none            | 459 ms                                                       | 443 ms: 1.04x faster                                                                   |
| async_tree_memoization     | 554 ms                                                       | 559 ms: 1.01x slower                                                                   |
| async_tree_cpu_io_mixed_tg | 706 ms                                                       | 725 ms: 1.03x slower                                                                   |
| async_tree_none_tg         | 440 ms                                                       | 452 ms: 1.03x slower                                                                   |
| async_tree_memoization_tg  | 554 ms                                                       | 571 ms: 1.03x slower                                                                   |
| async_tree_io_tg           | 1.07 sec                                                     | 1.11 sec: 1.04x slower                                                                 |
| async_tree_io              | 1.06 sec                                                     | 1.10 sec: 1.04x slower                                                                 |
| Geometric mean             | (ref)                                                        | 1.02x slower                                                                           |

Benchmark hidden because not significant (1): async_tree_cpu_io_mixed

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231102-pythonperf2-x86_64-faster%2dcpython-tier_2_exponential_b-3.13.0a1+-9c6f64f |
|----------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------------------:|
| pidigits       | 264 ms                                                       | 265 ms: 1.00x slower                                                                   |
| nbody          | 88.2 ms                                                      | 105 ms: 1.19x slower                                                                   |
| float          | 81.6 ms                                                      | 97.3 ms: 1.19x slower                                                                  |
| Geometric mean | (ref)                                                        | 1.12x slower                                                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231102-pythonperf2-x86_64-faster%2dcpython-tier_2_exponential_b-3.13.0a1+-9c6f64f |
|----------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------------------:|
| regex_effbot   | 3.61 ms                                                      | 3.57 ms: 1.01x faster                                                                  |
| regex_v8       | 24.4 ms                                                      | 25.7 ms: 1.05x slower                                                                  |
| regex_compile  | 145 ms                                                       | 170 ms: 1.18x slower                                                                   |
| Geometric mean | (ref)                                                        | 1.05x slower                                                                           |

Benchmark hidden because not significant (1): regex_dna

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231102-pythonperf2-x86_64-faster%2dcpython-tier_2_exponential_b-3.13.0a1+-9c6f64f |
|----------------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------------------:|
| unpickle             | 15.3 us                                                      | 15.0 us: 1.02x faster                                                                  |
| pickle_pure_python   | 319 us                                                       | 315 us: 1.02x faster                                                                   |
| json_loads           | 24.3 us                                                      | 24.1 us: 1.01x faster                                                                  |
| pickle_dict          | 32.0 us                                                      | 32.1 us: 1.00x slower                                                                  |
| xml_etree_process    | 58.3 ms                                                      | 59.0 ms: 1.01x slower                                                                  |
| pickle               | 10.0 us                                                      | 10.2 us: 1.02x slower                                                                  |
| xml_etree_generate   | 85.3 ms                                                      | 87.4 ms: 1.02x slower                                                                  |
| json_dumps           | 10.3 ms                                                      | 10.6 ms: 1.04x slower                                                                  |
| pickle_list          | 4.22 us                                                      | 4.41 us: 1.05x slower                                                                  |
| xml_etree_iterparse  | 104 ms                                                       | 110 ms: 1.06x slower                                                                   |
| unpickle_pure_python | 210 us                                                       | 240 us: 1.15x slower                                                                   |
| tomli_loads          | 2.17 sec                                                     | 2.66 sec: 1.22x slower                                                                 |
| Geometric mean       | (ref)                                                        | 1.04x slower                                                                           |

Benchmark hidden because not significant (2): unpickle_list, xml_etree_parse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231102-pythonperf2-x86_64-faster%2dcpython-tier_2_exponential_b-3.13.0a1+-9c6f64f |
|------------------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------------------:|
| python_startup         | 11.7 ms                                                      | 12.9 ms: 1.10x slower                                                                  |
| python_startup_no_site | 8.67 ms                                                      | 11.4 ms: 1.31x slower                                                                  |
| Geometric mean         | (ref)                                                        | 1.20x slower                                                                           |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231102-pythonperf2-x86_64-faster%2dcpython-tier_2_exponential_b-3.13.0a1+-9c6f64f |
|-----------|:------------------------------------------------------------:|:--------------------------------------------------------------------------------------:|
| mako      | 10.1 ms                                                      | 13.3 ms: 1.32x slower                                                                  |

All benchmarks:
===============

| Benchmark                  | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231102-pythonperf2-x86_64-faster%2dcpython-tier_2_exponential_b-3.13.0a1+-9c6f64f |
|----------------------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------------------:|
| typing_runtime_protocols   | 150 us                                                       | 131 us: 1.15x faster                                                                   |
| unpack_sequence            | 54.5 ns                                                      | 47.5 ns: 1.15x faster                                                                  |
| crypto_pyaes               | 82.4 ms                                                      | 74.9 ms: 1.10x faster                                                                  |
| bench_mp_pool              | 4.96 ms                                                      | 4.58 ms: 1.08x faster                                                                  |
| gc_traversal               | 3.70 ms                                                      | 3.49 ms: 1.06x faster                                                                  |
| raytrace                   | 301 ms                                                       | 286 ms: 1.05x faster                                                                   |
| generators                 | 37.3 ms                                                      | 35.6 ms: 1.05x faster                                                                  |
| deepcopy_reduce            | 3.41 us                                                      | 3.27 us: 1.04x faster                                                                  |
| async_tree_none            | 459 ms                                                       | 443 ms: 1.04x faster                                                                   |
| sympy_sum                  | 163 ms                                                       | 158 ms: 1.03x faster                                                                   |
| spectral_norm              | 93.9 ms                                                      | 91.4 ms: 1.03x faster                                                                  |
| asyncio_tcp                | 380 ms                                                       | 370 ms: 1.03x faster                                                                   |
| sqlglot_normalize          | 119 ms                                                       | 117 ms: 1.02x faster                                                                   |
| unpickle                   | 15.3 us                                                      | 15.0 us: 1.02x faster                                                                  |
| async_generators           | 385 ms                                                       | 378 ms: 1.02x faster                                                                   |
| pickle_pure_python         | 319 us                                                       | 315 us: 1.02x faster                                                                   |
| regex_effbot               | 3.61 ms                                                      | 3.57 ms: 1.01x faster                                                                  |
| coroutines                 | 23.1 ms                                                      | 22.8 ms: 1.01x faster                                                                  |
| json_loads                 | 24.3 us                                                      | 24.1 us: 1.01x faster                                                                  |
| sqlite_synth               | 2.72 us                                                      | 2.70 us: 1.01x faster                                                                  |
| pickle_dict                | 32.0 us                                                      | 32.1 us: 1.00x slower                                                                  |
| pidigits                   | 264 ms                                                       | 265 ms: 1.00x slower                                                                   |
| sympy_str                  | 305 ms                                                       | 307 ms: 1.01x slower                                                                   |
| async_tree_memoization     | 554 ms                                                       | 559 ms: 1.01x slower                                                                   |
| json                       | 5.17 ms                                                      | 5.23 ms: 1.01x slower                                                                  |
| xml_etree_process          | 58.3 ms                                                      | 59.0 ms: 1.01x slower                                                                  |
| asyncio_tcp_ssl            | 1.57 sec                                                     | 1.59 sec: 1.01x slower                                                                 |
| deepcopy                   | 371 us                                                       | 377 us: 1.02x slower                                                                   |
| tornado_http               | 122 ms                                                       | 124 ms: 1.02x slower                                                                   |
| pickle                     | 10.0 us                                                      | 10.2 us: 1.02x slower                                                                  |
| scimark_monte_carlo        | 69.5 ms                                                      | 71.0 ms: 1.02x slower                                                                  |
| xml_etree_generate         | 85.3 ms                                                      | 87.4 ms: 1.02x slower                                                                  |
| sympy_integrate            | 24.0 ms                                                      | 24.6 ms: 1.02x slower                                                                  |
| async_tree_cpu_io_mixed_tg | 706 ms                                                       | 725 ms: 1.03x slower                                                                   |
| async_tree_none_tg         | 440 ms                                                       | 452 ms: 1.03x slower                                                                   |
| docutils                   | 2.89 sec                                                     | 2.98 sec: 1.03x slower                                                                 |
| async_tree_memoization_tg  | 554 ms                                                       | 571 ms: 1.03x slower                                                                   |
| sqlglot_optimize           | 58.4 ms                                                      | 60.3 ms: 1.03x slower                                                                  |
| chameleon                  | 7.27 ms                                                      | 7.50 ms: 1.03x slower                                                                  |
| sqlglot_parse              | 1.41 ms                                                      | 1.45 ms: 1.03x slower                                                                  |
| async_tree_io_tg           | 1.07 sec                                                     | 1.11 sec: 1.04x slower                                                                 |
| json_dumps                 | 10.3 ms                                                      | 10.6 ms: 1.04x slower                                                                  |
| async_tree_io              | 1.06 sec                                                     | 1.10 sec: 1.04x slower                                                                 |
| sqlglot_transpile          | 1.80 ms                                                      | 1.87 ms: 1.04x slower                                                                  |
| pickle_list                | 4.22 us                                                      | 4.41 us: 1.05x slower                                                                  |
| mypy2                      | 365 ms                                                       | 382 ms: 1.05x slower                                                                   |
| pycparser                  | 1.29 sec                                                     | 1.36 sec: 1.05x slower                                                                 |
| chaos                      | 64.1 ms                                                      | 67.3 ms: 1.05x slower                                                                  |
| logging_silent             | 93.3 ns                                                      | 98.1 ns: 1.05x slower                                                                  |
| mdp                        | 2.56 sec                                                     | 2.69 sec: 1.05x slower                                                                 |
| regex_v8                   | 24.4 ms                                                      | 25.7 ms: 1.05x slower                                                                  |
| sympy_expand               | 492 ms                                                       | 521 ms: 1.06x slower                                                                   |
| xml_etree_iterparse        | 104 ms                                                       | 110 ms: 1.06x slower                                                                   |
| scimark_lu                 | 98.6 ms                                                      | 105 ms: 1.06x slower                                                                   |
| pathlib                    | 18.7 ms                                                      | 20.0 ms: 1.07x slower                                                                  |
| meteor_contest             | 126 ms                                                       | 135 ms: 1.07x slower                                                                   |
| 2to3                       | 285 ms                                                       | 307 ms: 1.08x slower                                                                   |
| dulwich_log                | 64.9 ms                                                      | 70.5 ms: 1.09x slower                                                                  |
| comprehensions             | 21.8 us                                                      | 23.7 us: 1.09x slower                                                                  |
| scimark_fft                | 303 ms                                                       | 332 ms: 1.09x slower                                                                   |
| pprint_safe_repr           | 808 ms                                                       | 887 ms: 1.10x slower                                                                   |
| python_startup             | 11.7 ms                                                      | 12.9 ms: 1.10x slower                                                                  |
| pprint_pformat             | 1.64 sec                                                     | 1.82 sec: 1.11x slower                                                                 |
| scimark_sparse_mat_mult    | 4.49 ms                                                      | 5.06 ms: 1.13x slower                                                                  |
| deepcopy_memo              | 36.6 us                                                      | 41.7 us: 1.14x slower                                                                  |
| unpickle_pure_python       | 210 us                                                       | 240 us: 1.15x slower                                                                   |
| telco                      | 7.16 ms                                                      | 8.25 ms: 1.15x slower                                                                  |
| richards_super             | 50.8 ms                                                      | 58.7 ms: 1.16x slower                                                                  |
| fannkuch                   | 362 ms                                                       | 418 ms: 1.16x slower                                                                   |
| richards                   | 45.1 ms                                                      | 52.5 ms: 1.17x slower                                                                  |
| regex_compile              | 145 ms                                                       | 170 ms: 1.18x slower                                                                   |
| nbody                      | 88.2 ms                                                      | 105 ms: 1.19x slower                                                                   |
| float                      | 81.6 ms                                                      | 97.3 ms: 1.19x slower                                                                  |
| go                         | 149 ms                                                       | 178 ms: 1.19x slower                                                                   |
| nqueens                    | 90.1 ms                                                      | 108 ms: 1.19x slower                                                                   |
| tomli_loads                | 2.17 sec                                                     | 2.66 sec: 1.22x slower                                                                 |
| pyflate                    | 442 ms                                                       | 547 ms: 1.24x slower                                                                   |
| coverage                   | 66.3 ms                                                      | 86.2 ms: 1.30x slower                                                                  |
| python_startup_no_site     | 8.67 ms                                                      | 11.4 ms: 1.31x slower                                                                  |
| mako                       | 10.1 ms                                                      | 13.3 ms: 1.32x slower                                                                  |
| scimark_sor                | 107 ms                                                       | 147 ms: 1.37x slower                                                                   |
| deltablue                  | 3.24 ms                                                      | 4.83 ms: 1.49x slower                                                                  |
| hexiom                     | 5.97 ms                                                      | 9.13 ms: 1.53x slower                                                                  |
| Geometric mean             | (ref)                                                        | 1.06x slower                                                                           |

Benchmark hidden because not significant (9): logging_simple, unpickle_list, xml_etree_parse, asyncio_websockets, create_gc_cycles, regex_dna, logging_format, async_tree_cpu_io_mixed, bench_thread_pool
Ignored benchmarks (6) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, dask, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.03x
- 95% likely to have a slowdown of 1.02x
- 99% likely to have a slowdown of 1.02x
