
# Results vs. 3.11.0

- fork: faster-cpython
- ref: tier_2_exponential_b
- machine: linux-x86_64
- commit hash: 9c6f64f
- commit date: 2023-11-02
- overall geometric mean: 1.02x faster \*
- HPT reliability: 50.62%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231102-pythonperf2-x86_64-faster%2dcpython-tier_2_exponential_b-3.13.0a1+-9c6f64f |
|----------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------------------:|
| 2to3           | 286 ms                                                       | 307 ms: 1.07x slower                                                                   |
| chameleon      | 7.42 ms                                                      | 7.50 ms: 1.01x slower                                                                  |
| docutils       | 2.87 sec                                                     | 2.98 sec: 1.04x slower                                                                 |
| Geometric mean | (ref)                                                        | 1.03x slower                                                                           |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231102-pythonperf2-x86_64-faster%2dcpython-tier_2_exponential_b-3.13.0a1+-9c6f64f |
|----------------------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------------------:|
| async_tree_none            | 529 ms                                                       | 443 ms: 1.19x faster                                                                   |
| async_tree_memoization     | 648 ms                                                       | 559 ms: 1.16x faster                                                                   |
| async_tree_io              | 1.19 sec                                                     | 1.10 sec: 1.09x faster                                                                 |
| async_tree_cpu_io_mixed    | 762 ms                                                       | 709 ms: 1.07x faster                                                                   |
| async_tree_none_tg         | 482 ms                                                       | 452 ms: 1.07x faster                                                                   |
| async_tree_memoization_tg  | 605 ms                                                       | 571 ms: 1.06x faster                                                                   |
| async_tree_io_tg           | 1.17 sec                                                     | 1.11 sec: 1.06x faster                                                                 |
| async_tree_cpu_io_mixed_tg | 760 ms                                                       | 725 ms: 1.05x faster                                                                   |
| Geometric mean             | (ref)                                                        | 1.09x faster                                                                           |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231102-pythonperf2-x86_64-faster%2dcpython-tier_2_exponential_b-3.13.0a1+-9c6f64f |
|----------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------------------:|
| pidigits       | 251 ms                                                       | 265 ms: 1.06x slower                                                                   |
| nbody          | 95.8 ms                                                      | 105 ms: 1.09x slower                                                                   |
| float          | 76.0 ms                                                      | 97.3 ms: 1.28x slower                                                                  |
| Geometric mean | (ref)                                                        | 1.14x slower                                                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231102-pythonperf2-x86_64-faster%2dcpython-tier_2_exponential_b-3.13.0a1+-9c6f64f |
|----------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------------------:|
| regex_effbot   | 3.42 ms                                                      | 3.57 ms: 1.05x slower                                                                  |
| regex_dna      | 226 ms                                                       | 241 ms: 1.06x slower                                                                   |
| regex_compile  | 157 ms                                                       | 170 ms: 1.08x slower                                                                   |
| regex_v8       | 23.7 ms                                                      | 25.7 ms: 1.09x slower                                                                  |
| Geometric mean | (ref)                                                        | 1.07x slower                                                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231102-pythonperf2-x86_64-faster%2dcpython-tier_2_exponential_b-3.13.0a1+-9c6f64f |
|----------------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------------------:|
| json_dumps           | 13.5 ms                                                      | 10.6 ms: 1.27x faster                                                                  |
| json_loads           | 29.0 us                                                      | 24.1 us: 1.20x faster                                                                  |
| xml_etree_parse      | 159 ms                                                       | 147 ms: 1.08x faster                                                                   |
| pickle_pure_python   | 318 us                                                       | 315 us: 1.01x faster                                                                   |
| pickle_dict          | 31.8 us                                                      | 32.1 us: 1.01x slower                                                                  |
| unpickle_pure_python | 236 us                                                       | 240 us: 1.02x slower                                                                   |
| unpickle_list        | 4.47 us                                                      | 4.64 us: 1.04x slower                                                                  |
| xml_etree_iterparse  | 106 ms                                                       | 110 ms: 1.04x slower                                                                   |
| pickle               | 9.77 us                                                      | 10.2 us: 1.05x slower                                                                  |
| xml_etree_process    | 56.1 ms                                                      | 59.0 ms: 1.05x slower                                                                  |
| xml_etree_generate   | 80.5 ms                                                      | 87.4 ms: 1.09x slower                                                                  |
| pickle_list          | 3.89 us                                                      | 4.41 us: 1.13x slower                                                                  |
| unpickle             | 13.2 us                                                      | 15.0 us: 1.14x slower                                                                  |
| tomli_loads          | 2.27 sec                                                     | 2.66 sec: 1.17x slower                                                                 |
| Geometric mean       | (ref)                                                        | 1.01x slower                                                                           |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231102-pythonperf2-x86_64-faster%2dcpython-tier_2_exponential_b-3.13.0a1+-9c6f64f |
|------------------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------------------:|
| python_startup         | 10.8 ms                                                      | 12.9 ms: 1.19x slower                                                                  |
| python_startup_no_site | 7.78 ms                                                      | 11.4 ms: 1.46x slower                                                                  |
| Geometric mean         | (ref)                                                        | 1.32x slower                                                                           |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231102-pythonperf2-x86_64-faster%2dcpython-tier_2_exponential_b-3.13.0a1+-9c6f64f |
|-----------|:------------------------------------------------------------:|:--------------------------------------------------------------------------------------:|
| mako      | 11.0 ms                                                      | 13.3 ms: 1.21x slower                                                                  |

All benchmarks:
===============

| Benchmark                  | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231102-pythonperf2-x86_64-faster%2dcpython-tier_2_exponential_b-3.13.0a1+-9c6f64f |
|----------------------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------------------:|
| typing_runtime_protocols   | 527 us                                                       | 131 us: 4.03x faster                                                                   |
| asyncio_tcp                | 752 ms                                                       | 370 ms: 2.03x faster                                                                   |
| asyncio_tcp_ssl            | 3.09 sec                                                     | 1.59 sec: 1.94x faster                                                                 |
| generators                 | 56.4 ms                                                      | 35.6 ms: 1.58x faster                                                                  |
| json_dumps                 | 13.5 ms                                                      | 10.6 ms: 1.27x faster                                                                  |
| coroutines                 | 27.9 ms                                                      | 22.8 ms: 1.22x faster                                                                  |
| json_loads                 | 29.0 us                                                      | 24.1 us: 1.20x faster                                                                  |
| async_tree_none            | 529 ms                                                       | 443 ms: 1.19x faster                                                                   |
| mypy2                      | 449 ms                                                       | 382 ms: 1.17x faster                                                                   |
| sympy_sum                  | 184 ms                                                       | 158 ms: 1.17x faster                                                                   |
| gc_traversal               | 4.06 ms                                                      | 3.49 ms: 1.16x faster                                                                  |
| async_tree_memoization     | 648 ms                                                       | 559 ms: 1.16x faster                                                                   |
| richards_super             | 65.2 ms                                                      | 58.7 ms: 1.11x faster                                                                  |
| scimark_lu                 | 115 ms                                                       | 105 ms: 1.10x faster                                                                   |
| sympy_str                  | 336 ms                                                       | 307 ms: 1.09x faster                                                                   |
| fannkuch                   | 457 ms                                                       | 418 ms: 1.09x faster                                                                   |
| crypto_pyaes               | 81.8 ms                                                      | 74.9 ms: 1.09x faster                                                                  |
| logging_simple             | 7.21 us                                                      | 6.63 us: 1.09x faster                                                                  |
| async_tree_io              | 1.19 sec                                                     | 1.10 sec: 1.09x faster                                                                 |
| xml_etree_parse            | 159 ms                                                       | 147 ms: 1.08x faster                                                                   |
| raytrace                   | 308 ms                                                       | 286 ms: 1.08x faster                                                                   |
| async_tree_cpu_io_mixed    | 762 ms                                                       | 709 ms: 1.07x faster                                                                   |
| logging_format             | 7.83 us                                                      | 7.32 us: 1.07x faster                                                                  |
| json                       | 5.59 ms                                                      | 5.23 ms: 1.07x faster                                                                  |
| sqlglot_parse              | 1.55 ms                                                      | 1.45 ms: 1.07x faster                                                                  |
| async_tree_none_tg         | 482 ms                                                       | 452 ms: 1.07x faster                                                                   |
| chaos                      | 71.6 ms                                                      | 67.3 ms: 1.06x faster                                                                  |
| async_tree_memoization_tg  | 605 ms                                                       | 571 ms: 1.06x faster                                                                   |
| sympy_expand               | 550 ms                                                       | 521 ms: 1.06x faster                                                                   |
| async_tree_io_tg           | 1.17 sec                                                     | 1.11 sec: 1.06x faster                                                                 |
| async_tree_cpu_io_mixed_tg | 760 ms                                                       | 725 ms: 1.05x faster                                                                   |
| comprehensions             | 24.8 us                                                      | 23.7 us: 1.05x faster                                                                  |
| sqlglot_normalize          | 122 ms                                                       | 117 ms: 1.05x faster                                                                   |
| bench_thread_pool          | 1.02 ms                                                      | 975 us: 1.05x faster                                                                   |
| sympy_integrate            | 25.6 ms                                                      | 24.6 ms: 1.04x faster                                                                  |
| logging_silent             | 102 ns                                                       | 98.1 ns: 1.04x faster                                                                  |
| sqlglot_transpile          | 1.94 ms                                                      | 1.87 ms: 1.04x faster                                                                  |
| deepcopy                   | 389 us                                                       | 377 us: 1.03x faster                                                                   |
| deepcopy_reduce            | 3.37 us                                                      | 3.27 us: 1.03x faster                                                                  |
| spectral_norm              | 94.0 ms                                                      | 91.4 ms: 1.03x faster                                                                  |
| pickle_pure_python         | 318 us                                                       | 315 us: 1.01x faster                                                                   |
| mdp                        | 2.72 sec                                                     | 2.69 sec: 1.01x faster                                                                 |
| scimark_monte_carlo        | 70.6 ms                                                      | 71.0 ms: 1.01x slower                                                                  |
| chameleon                  | 7.42 ms                                                      | 7.50 ms: 1.01x slower                                                                  |
| pickle_dict                | 31.8 us                                                      | 32.1 us: 1.01x slower                                                                  |
| unpickle_pure_python       | 236 us                                                       | 240 us: 1.02x slower                                                                   |
| sqlglot_optimize           | 59.2 ms                                                      | 60.3 ms: 1.02x slower                                                                  |
| dulwich_log                | 68.3 ms                                                      | 70.5 ms: 1.03x slower                                                                  |
| unpickle_list              | 4.47 us                                                      | 4.64 us: 1.04x slower                                                                  |
| docutils                   | 2.87 sec                                                     | 2.98 sec: 1.04x slower                                                                 |
| meteor_contest             | 130 ms                                                       | 135 ms: 1.04x slower                                                                   |
| xml_etree_iterparse        | 106 ms                                                       | 110 ms: 1.04x slower                                                                   |
| regex_effbot               | 3.42 ms                                                      | 3.57 ms: 1.05x slower                                                                  |
| pickle                     | 9.77 us                                                      | 10.2 us: 1.05x slower                                                                  |
| pathlib                    | 19.1 ms                                                      | 20.0 ms: 1.05x slower                                                                  |
| xml_etree_process          | 56.1 ms                                                      | 59.0 ms: 1.05x slower                                                                  |
| richards                   | 49.9 ms                                                      | 52.5 ms: 1.05x slower                                                                  |
| pidigits                   | 251 ms                                                       | 265 ms: 1.06x slower                                                                   |
| unpack_sequence            | 44.9 ns                                                      | 47.5 ns: 1.06x slower                                                                  |
| pycparser                  | 1.28 sec                                                     | 1.36 sec: 1.06x slower                                                                 |
| regex_dna                  | 226 ms                                                       | 241 ms: 1.06x slower                                                                   |
| go                         | 166 ms                                                       | 178 ms: 1.07x slower                                                                   |
| 2to3                       | 286 ms                                                       | 307 ms: 1.07x slower                                                                   |
| regex_compile              | 157 ms                                                       | 170 ms: 1.08x slower                                                                   |
| xml_etree_generate         | 80.5 ms                                                      | 87.4 ms: 1.09x slower                                                                  |
| nqueens                    | 99.2 ms                                                      | 108 ms: 1.09x slower                                                                   |
| sqlite_synth               | 2.49 us                                                      | 2.70 us: 1.09x slower                                                                  |
| regex_v8                   | 23.7 ms                                                      | 25.7 ms: 1.09x slower                                                                  |
| nbody                      | 95.8 ms                                                      | 105 ms: 1.09x slower                                                                   |
| pprint_pformat             | 1.63 sec                                                     | 1.82 sec: 1.12x slower                                                                 |
| deepcopy_memo              | 37.3 us                                                      | 41.7 us: 1.12x slower                                                                  |
| pickle_list                | 3.89 us                                                      | 4.41 us: 1.13x slower                                                                  |
| unpickle                   | 13.2 us                                                      | 15.0 us: 1.14x slower                                                                  |
| pprint_safe_repr           | 780 ms                                                       | 887 ms: 1.14x slower                                                                   |
| tomli_loads                | 2.27 sec                                                     | 2.66 sec: 1.17x slower                                                                 |
| async_generators           | 322 ms                                                       | 378 ms: 1.18x slower                                                                   |
| scimark_fft                | 281 ms                                                       | 332 ms: 1.18x slower                                                                   |
| python_startup             | 10.8 ms                                                      | 12.9 ms: 1.19x slower                                                                  |
| telco                      | 6.91 ms                                                      | 8.25 ms: 1.19x slower                                                                  |
| deltablue                  | 4.03 ms                                                      | 4.83 ms: 1.20x slower                                                                  |
| pyflate                    | 453 ms                                                       | 547 ms: 1.21x slower                                                                   |
| mako                       | 11.0 ms                                                      | 13.3 ms: 1.21x slower                                                                  |
| scimark_sparse_mat_mult    | 4.04 ms                                                      | 5.06 ms: 1.25x slower                                                                  |
| float                      | 76.0 ms                                                      | 97.3 ms: 1.28x slower                                                                  |
| coverage                   | 66.6 ms                                                      | 86.2 ms: 1.29x slower                                                                  |
| hexiom                     | 6.97 ms                                                      | 9.13 ms: 1.31x slower                                                                  |
| scimark_sor                | 109 ms                                                       | 147 ms: 1.34x slower                                                                   |
| python_startup_no_site     | 7.78 ms                                                      | 11.4 ms: 1.46x slower                                                                  |
| Geometric mean             | (ref)                                                        | 1.02x faster                                                                           |

Benchmark hidden because not significant (4): bench_mp_pool, create_gc_cycles, tornado_http, asyncio_websockets
Ignored benchmarks (12) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, dask, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift


# HPT report

- Reliability score: 50.62% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
