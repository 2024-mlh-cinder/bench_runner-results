
# Results vs. 3.12.0

- fork: faster-cpython
- ref: tier_2_exponential_b
- machine: linux-x86_64
- commit hash: bf453f8
- commit date: 2023-11-02
- overall geometric mean: 1.07x slower \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.02x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231102-pythonperf2-x86_64-faster%2dcpython-tier_2_exponential_b-3.13.0a1+-bf453f8 |
|----------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------------------:|
| 2to3           | 285 ms                                                       | 308 ms: 1.08x slower                                                                   |
| chameleon      | 7.27 ms                                                      | 7.72 ms: 1.06x slower                                                                  |
| docutils       | 2.89 sec                                                     | 2.95 sec: 1.02x slower                                                                 |
| Geometric mean | (ref)                                                        | 1.04x slower                                                                           |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231102-pythonperf2-x86_64-faster%2dcpython-tier_2_exponential_b-3.13.0a1+-bf453f8 |
|----------------------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------------------:|
| async_tree_none            | 459 ms                                                       | 450 ms: 1.02x faster                                                                   |
| async_tree_memoization     | 554 ms                                                       | 565 ms: 1.02x slower                                                                   |
| async_tree_cpu_io_mixed    | 704 ms                                                       | 720 ms: 1.02x slower                                                                   |
| async_tree_none_tg         | 440 ms                                                       | 458 ms: 1.04x slower                                                                   |
| async_tree_cpu_io_mixed_tg | 706 ms                                                       | 735 ms: 1.04x slower                                                                   |
| async_tree_io_tg           | 1.07 sec                                                     | 1.12 sec: 1.04x slower                                                                 |
| async_tree_io              | 1.06 sec                                                     | 1.10 sec: 1.04x slower                                                                 |
| async_tree_memoization_tg  | 554 ms                                                       | 578 ms: 1.04x slower                                                                   |
| Geometric mean             | (ref)                                                        | 1.03x slower                                                                           |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231102-pythonperf2-x86_64-faster%2dcpython-tier_2_exponential_b-3.13.0a1+-bf453f8 |
|----------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------------------:|
| pidigits       | 264 ms                                                       | 266 ms: 1.00x slower                                                                   |
| float          | 81.6 ms                                                      | 103 ms: 1.26x slower                                                                   |
| nbody          | 88.2 ms                                                      | 115 ms: 1.30x slower                                                                   |
| Geometric mean | (ref)                                                        | 1.18x slower                                                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231102-pythonperf2-x86_64-faster%2dcpython-tier_2_exponential_b-3.13.0a1+-bf453f8 |
|----------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------------------:|
| regex_effbot   | 3.61 ms                                                      | 3.48 ms: 1.04x faster                                                                  |
| regex_dna      | 240 ms                                                       | 247 ms: 1.03x slower                                                                   |
| regex_v8       | 24.4 ms                                                      | 25.8 ms: 1.06x slower                                                                  |
| regex_compile  | 145 ms                                                       | 174 ms: 1.21x slower                                                                   |
| Geometric mean | (ref)                                                        | 1.06x slower                                                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231102-pythonperf2-x86_64-faster%2dcpython-tier_2_exponential_b-3.13.0a1+-bf453f8 |
|----------------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------------------:|
| unpickle             | 15.3 us                                                      | 14.6 us: 1.05x faster                                                                  |
| pickle_dict          | 32.0 us                                                      | 31.8 us: 1.01x faster                                                                  |
| xml_etree_process    | 58.3 ms                                                      | 59.1 ms: 1.01x slower                                                                  |
| pickle_pure_python   | 319 us                                                       | 324 us: 1.01x slower                                                                   |
| xml_etree_generate   | 85.3 ms                                                      | 86.9 ms: 1.02x slower                                                                  |
| unpickle_list        | 4.65 us                                                      | 4.75 us: 1.02x slower                                                                  |
| json_dumps           | 10.3 ms                                                      | 10.5 ms: 1.02x slower                                                                  |
| xml_etree_parse      | 147 ms                                                       | 152 ms: 1.03x slower                                                                   |
| xml_etree_iterparse  | 104 ms                                                       | 113 ms: 1.09x slower                                                                   |
| unpickle_pure_python | 210 us                                                       | 243 us: 1.16x slower                                                                   |
| tomli_loads          | 2.17 sec                                                     | 2.83 sec: 1.30x slower                                                                 |
| Geometric mean       | (ref)                                                        | 1.04x slower                                                                           |

Benchmark hidden because not significant (3): pickle, json_loads, pickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231102-pythonperf2-x86_64-faster%2dcpython-tier_2_exponential_b-3.13.0a1+-bf453f8 |
|------------------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------------------:|
| python_startup         | 11.7 ms                                                      | 12.9 ms: 1.10x slower                                                                  |
| python_startup_no_site | 8.67 ms                                                      | 11.4 ms: 1.31x slower                                                                  |
| Geometric mean         | (ref)                                                        | 1.20x slower                                                                           |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231102-pythonperf2-x86_64-faster%2dcpython-tier_2_exponential_b-3.13.0a1+-bf453f8 |
|-----------|:------------------------------------------------------------:|:--------------------------------------------------------------------------------------:|
| mako      | 10.1 ms                                                      | 14.2 ms: 1.41x slower                                                                  |

All benchmarks:
===============

| Benchmark                  | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231102-pythonperf2-x86_64-faster%2dcpython-tier_2_exponential_b-3.13.0a1+-bf453f8 |
|----------------------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------------------:|
| unpack_sequence            | 54.5 ns                                                      | 40.5 ns: 1.35x faster                                                                  |
| typing_runtime_protocols   | 150 us                                                       | 132 us: 1.14x faster                                                                   |
| crypto_pyaes               | 82.4 ms                                                      | 75.9 ms: 1.09x faster                                                                  |
| bench_mp_pool              | 4.96 ms                                                      | 4.58 ms: 1.08x faster                                                                  |
| raytrace                   | 301 ms                                                       | 283 ms: 1.06x faster                                                                   |
| unpickle                   | 15.3 us                                                      | 14.6 us: 1.05x faster                                                                  |
| sympy_sum                  | 163 ms                                                       | 157 ms: 1.04x faster                                                                   |
| regex_effbot               | 3.61 ms                                                      | 3.48 ms: 1.04x faster                                                                  |
| spectral_norm              | 93.9 ms                                                      | 91.1 ms: 1.03x faster                                                                  |
| deepcopy_reduce            | 3.41 us                                                      | 3.32 us: 1.03x faster                                                                  |
| async_tree_none            | 459 ms                                                       | 450 ms: 1.02x faster                                                                   |
| coroutines                 | 23.1 ms                                                      | 22.6 ms: 1.02x faster                                                                  |
| asyncio_tcp                | 380 ms                                                       | 373 ms: 1.02x faster                                                                   |
| async_generators           | 385 ms                                                       | 380 ms: 1.01x faster                                                                   |
| sqlglot_normalize          | 119 ms                                                       | 118 ms: 1.01x faster                                                                   |
| generators                 | 37.3 ms                                                      | 37.0 ms: 1.01x faster                                                                  |
| pickle_dict                | 32.0 us                                                      | 31.8 us: 1.01x faster                                                                  |
| sympy_str                  | 305 ms                                                       | 306 ms: 1.00x slower                                                                   |
| pidigits                   | 264 ms                                                       | 266 ms: 1.00x slower                                                                   |
| sqlite_synth               | 2.72 us                                                      | 2.74 us: 1.01x slower                                                                  |
| xml_etree_process          | 58.3 ms                                                      | 59.1 ms: 1.01x slower                                                                  |
| json                       | 5.17 ms                                                      | 5.24 ms: 1.01x slower                                                                  |
| asyncio_tcp_ssl            | 1.57 sec                                                     | 1.59 sec: 1.01x slower                                                                 |
| pickle_pure_python         | 319 us                                                       | 324 us: 1.01x slower                                                                   |
| pycparser                  | 1.29 sec                                                     | 1.32 sec: 1.02x slower                                                                 |
| xml_etree_generate         | 85.3 ms                                                      | 86.9 ms: 1.02x slower                                                                  |
| docutils                   | 2.89 sec                                                     | 2.95 sec: 1.02x slower                                                                 |
| unpickle_list              | 4.65 us                                                      | 4.75 us: 1.02x slower                                                                  |
| async_tree_memoization     | 554 ms                                                       | 565 ms: 1.02x slower                                                                   |
| async_tree_cpu_io_mixed    | 704 ms                                                       | 720 ms: 1.02x slower                                                                   |
| deepcopy                   | 371 us                                                       | 380 us: 1.02x slower                                                                   |
| sympy_integrate            | 24.0 ms                                                      | 24.6 ms: 1.02x slower                                                                  |
| json_dumps                 | 10.3 ms                                                      | 10.5 ms: 1.02x slower                                                                  |
| sqlglot_optimize           | 58.4 ms                                                      | 60.0 ms: 1.03x slower                                                                  |
| regex_dna                  | 240 ms                                                       | 247 ms: 1.03x slower                                                                   |
| sqlglot_parse              | 1.41 ms                                                      | 1.45 ms: 1.03x slower                                                                  |
| bench_thread_pool          | 956 us                                                       | 985 us: 1.03x slower                                                                   |
| scimark_monte_carlo        | 69.5 ms                                                      | 71.8 ms: 1.03x slower                                                                  |
| xml_etree_parse            | 147 ms                                                       | 152 ms: 1.03x slower                                                                   |
| create_gc_cycles           | 1.58 ms                                                      | 1.63 ms: 1.03x slower                                                                  |
| sqlglot_transpile          | 1.80 ms                                                      | 1.87 ms: 1.04x slower                                                                  |
| async_tree_none_tg         | 440 ms                                                       | 458 ms: 1.04x slower                                                                   |
| async_tree_cpu_io_mixed_tg | 706 ms                                                       | 735 ms: 1.04x slower                                                                   |
| async_tree_io_tg           | 1.07 sec                                                     | 1.12 sec: 1.04x slower                                                                 |
| async_tree_io              | 1.06 sec                                                     | 1.10 sec: 1.04x slower                                                                 |
| mypy2                      | 365 ms                                                       | 381 ms: 1.04x slower                                                                   |
| logging_simple             | 6.64 us                                                      | 6.94 us: 1.04x slower                                                                  |
| async_tree_memoization_tg  | 554 ms                                                       | 578 ms: 1.04x slower                                                                   |
| logging_format             | 7.29 us                                                      | 7.62 us: 1.05x slower                                                                  |
| mdp                        | 2.56 sec                                                     | 2.69 sec: 1.05x slower                                                                 |
| regex_v8                   | 24.4 ms                                                      | 25.8 ms: 1.06x slower                                                                  |
| chaos                      | 64.1 ms                                                      | 67.8 ms: 1.06x slower                                                                  |
| sympy_expand               | 492 ms                                                       | 521 ms: 1.06x slower                                                                   |
| scimark_lu                 | 98.6 ms                                                      | 104 ms: 1.06x slower                                                                   |
| chameleon                  | 7.27 ms                                                      | 7.72 ms: 1.06x slower                                                                  |
| logging_silent             | 93.3 ns                                                      | 99.2 ns: 1.06x slower                                                                  |
| gc_traversal               | 3.70 ms                                                      | 3.95 ms: 1.07x slower                                                                  |
| dulwich_log                | 64.9 ms                                                      | 69.8 ms: 1.07x slower                                                                  |
| pathlib                    | 18.7 ms                                                      | 20.2 ms: 1.08x slower                                                                  |
| 2to3                       | 285 ms                                                       | 308 ms: 1.08x slower                                                                   |
| meteor_contest             | 126 ms                                                       | 137 ms: 1.08x slower                                                                   |
| xml_etree_iterparse        | 104 ms                                                       | 113 ms: 1.09x slower                                                                   |
| python_startup             | 11.7 ms                                                      | 12.9 ms: 1.10x slower                                                                  |
| pprint_safe_repr           | 808 ms                                                       | 895 ms: 1.11x slower                                                                   |
| pprint_pformat             | 1.64 sec                                                     | 1.82 sec: 1.11x slower                                                                 |
| scimark_fft                | 303 ms                                                       | 342 ms: 1.13x slower                                                                   |
| telco                      | 7.16 ms                                                      | 8.23 ms: 1.15x slower                                                                  |
| fannkuch                   | 362 ms                                                       | 417 ms: 1.15x slower                                                                   |
| comprehensions             | 21.8 us                                                      | 25.3 us: 1.16x slower                                                                  |
| unpickle_pure_python       | 210 us                                                       | 243 us: 1.16x slower                                                                   |
| deepcopy_memo              | 36.6 us                                                      | 42.6 us: 1.16x slower                                                                  |
| scimark_sparse_mat_mult    | 4.49 ms                                                      | 5.27 ms: 1.17x slower                                                                  |
| richards_super             | 50.8 ms                                                      | 60.1 ms: 1.18x slower                                                                  |
| richards                   | 45.1 ms                                                      | 53.6 ms: 1.19x slower                                                                  |
| coverage                   | 66.3 ms                                                      | 79.2 ms: 1.19x slower                                                                  |
| go                         | 149 ms                                                       | 179 ms: 1.20x slower                                                                   |
| regex_compile              | 145 ms                                                       | 174 ms: 1.21x slower                                                                   |
| pyflate                    | 442 ms                                                       | 538 ms: 1.22x slower                                                                   |
| nqueens                    | 90.1 ms                                                      | 111 ms: 1.23x slower                                                                   |
| float                      | 81.6 ms                                                      | 103 ms: 1.26x slower                                                                   |
| nbody                      | 88.2 ms                                                      | 115 ms: 1.30x slower                                                                   |
| tomli_loads                | 2.17 sec                                                     | 2.83 sec: 1.30x slower                                                                 |
| python_startup_no_site     | 8.67 ms                                                      | 11.4 ms: 1.31x slower                                                                  |
| scimark_sor                | 107 ms                                                       | 150 ms: 1.40x slower                                                                   |
| mako                       | 10.1 ms                                                      | 14.2 ms: 1.41x slower                                                                  |
| deltablue                  | 3.24 ms                                                      | 5.32 ms: 1.64x slower                                                                  |
| hexiom                     | 5.97 ms                                                      | 9.82 ms: 1.64x slower                                                                  |
| Geometric mean             | (ref)                                                        | 1.07x slower                                                                           |

Benchmark hidden because not significant (5): pickle, asyncio_websockets, json_loads, pickle_list, tornado_http
Ignored benchmarks (6) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, dask, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.03x
- 95% likely to have a slowdown of 1.03x
- 99% likely to have a slowdown of 1.02x
