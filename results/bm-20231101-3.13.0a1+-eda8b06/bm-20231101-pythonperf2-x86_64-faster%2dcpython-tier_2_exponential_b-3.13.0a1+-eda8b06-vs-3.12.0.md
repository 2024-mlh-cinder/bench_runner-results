
# Results vs. 3.12.0

- fork: faster-cpython
- ref: tier_2_exponential_b
- machine: linux-x86_64
- commit hash: eda8b06
- commit date: 2023-11-01
- overall geometric mean: 1.07x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.02x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231101-pythonperf2-x86_64-faster%2dcpython-tier_2_exponential_b-3.13.0a1+-eda8b06 |
|----------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------------------:|
| 2to3           | 285 ms                                                       | 308 ms: 1.08x slower                                                                   |
| chameleon      | 7.27 ms                                                      | 7.43 ms: 1.02x slower                                                                  |
| docutils       | 2.89 sec                                                     | 2.94 sec: 1.02x slower                                                                 |
| Geometric mean | (ref)                                                        | 1.03x slower                                                                           |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231101-pythonperf2-x86_64-faster%2dcpython-tier_2_exponential_b-3.13.0a1+-eda8b06 |
|----------------------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------------------:|
| async_tree_none            | 459 ms                                                       | 447 ms: 1.03x faster                                                                   |
| async_tree_cpu_io_mixed    | 704 ms                                                       | 712 ms: 1.01x slower                                                                   |
| async_tree_memoization     | 554 ms                                                       | 562 ms: 1.01x slower                                                                   |
| async_tree_memoization_tg  | 554 ms                                                       | 573 ms: 1.03x slower                                                                   |
| async_tree_cpu_io_mixed_tg | 706 ms                                                       | 731 ms: 1.04x slower                                                                   |
| async_tree_io              | 1.06 sec                                                     | 1.10 sec: 1.04x slower                                                                 |
| async_tree_io_tg           | 1.07 sec                                                     | 1.12 sec: 1.04x slower                                                                 |
| async_tree_none_tg         | 440 ms                                                       | 460 ms: 1.05x slower                                                                   |
| Geometric mean             | (ref)                                                        | 1.02x slower                                                                           |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231101-pythonperf2-x86_64-faster%2dcpython-tier_2_exponential_b-3.13.0a1+-eda8b06 |
|----------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------------------:|
| pidigits       | 264 ms                                                       | 265 ms: 1.00x slower                                                                   |
| nbody          | 88.2 ms                                                      | 110 ms: 1.25x slower                                                                   |
| float          | 81.6 ms                                                      | 103 ms: 1.27x slower                                                                   |
| Geometric mean | (ref)                                                        | 1.17x slower                                                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231101-pythonperf2-x86_64-faster%2dcpython-tier_2_exponential_b-3.13.0a1+-eda8b06 |
|----------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------------------:|
| regex_effbot   | 3.61 ms                                                      | 3.47 ms: 1.04x faster                                                                  |
| regex_v8       | 24.4 ms                                                      | 24.5 ms: 1.00x slower                                                                  |
| regex_dna      | 240 ms                                                       | 243 ms: 1.01x slower                                                                   |
| regex_compile  | 145 ms                                                       | 174 ms: 1.20x slower                                                                   |
| Geometric mean | (ref)                                                        | 1.04x slower                                                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231101-pythonperf2-x86_64-faster%2dcpython-tier_2_exponential_b-3.13.0a1+-eda8b06 |
|----------------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------------------:|
| unpickle             | 15.3 us                                                      | 14.4 us: 1.06x faster                                                                  |
| pickle_pure_python   | 319 us                                                       | 315 us: 1.01x faster                                                                   |
| pickle               | 10.0 us                                                      | 9.98 us: 1.01x faster                                                                  |
| json_loads           | 24.3 us                                                      | 24.5 us: 1.01x slower                                                                  |
| xml_etree_process    | 58.3 ms                                                      | 58.9 ms: 1.01x slower                                                                  |
| xml_etree_generate   | 85.3 ms                                                      | 86.6 ms: 1.02x slower                                                                  |
| xml_etree_parse      | 147 ms                                                       | 149 ms: 1.02x slower                                                                   |
| json_dumps           | 10.3 ms                                                      | 10.6 ms: 1.04x slower                                                                  |
| xml_etree_iterparse  | 104 ms                                                       | 110 ms: 1.06x slower                                                                   |
| unpickle_pure_python | 210 us                                                       | 248 us: 1.18x slower                                                                   |
| tomli_loads          | 2.17 sec                                                     | 2.78 sec: 1.28x slower                                                                 |
| Geometric mean       | (ref)                                                        | 1.04x slower                                                                           |

Benchmark hidden because not significant (3): unpickle_list, pickle_dict, pickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231101-pythonperf2-x86_64-faster%2dcpython-tier_2_exponential_b-3.13.0a1+-eda8b06 |
|------------------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------------------:|
| python_startup         | 11.7 ms                                                      | 12.9 ms: 1.10x slower                                                                  |
| python_startup_no_site | 8.67 ms                                                      | 11.4 ms: 1.31x slower                                                                  |
| Geometric mean         | (ref)                                                        | 1.20x slower                                                                           |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231101-pythonperf2-x86_64-faster%2dcpython-tier_2_exponential_b-3.13.0a1+-eda8b06 |
|-----------|:------------------------------------------------------------:|:--------------------------------------------------------------------------------------:|
| mako      | 10.1 ms                                                      | 14.3 ms: 1.42x slower                                                                  |

All benchmarks:
===============

| Benchmark                  | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231101-pythonperf2-x86_64-faster%2dcpython-tier_2_exponential_b-3.13.0a1+-eda8b06 |
|----------------------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------------------:|
| typing_runtime_protocols   | 150 us                                                       | 131 us: 1.14x faster                                                                   |
| bench_mp_pool              | 4.96 ms                                                      | 4.50 ms: 1.10x faster                                                                  |
| unpack_sequence            | 54.5 ns                                                      | 50.7 ns: 1.07x faster                                                                  |
| crypto_pyaes               | 82.4 ms                                                      | 77.2 ms: 1.07x faster                                                                  |
| unpickle                   | 15.3 us                                                      | 14.4 us: 1.06x faster                                                                  |
| generators                 | 37.3 ms                                                      | 35.3 ms: 1.06x faster                                                                  |
| regex_effbot               | 3.61 ms                                                      | 3.47 ms: 1.04x faster                                                                  |
| sympy_sum                  | 163 ms                                                       | 157 ms: 1.04x faster                                                                   |
| async_tree_none            | 459 ms                                                       | 447 ms: 1.03x faster                                                                   |
| spectral_norm              | 93.9 ms                                                      | 91.5 ms: 1.03x faster                                                                  |
| asyncio_tcp                | 380 ms                                                       | 371 ms: 1.02x faster                                                                   |
| coroutines                 | 23.1 ms                                                      | 22.7 ms: 1.02x faster                                                                  |
| sqlglot_normalize          | 119 ms                                                       | 117 ms: 1.02x faster                                                                   |
| pickle_pure_python         | 319 us                                                       | 315 us: 1.01x faster                                                                   |
| deepcopy_reduce            | 3.41 us                                                      | 3.37 us: 1.01x faster                                                                  |
| pickle                     | 10.0 us                                                      | 9.98 us: 1.01x faster                                                                  |
| sqlite_synth               | 2.72 us                                                      | 2.70 us: 1.01x faster                                                                  |
| async_generators           | 385 ms                                                       | 383 ms: 1.01x faster                                                                   |
| regex_v8                   | 24.4 ms                                                      | 24.5 ms: 1.00x slower                                                                  |
| pidigits                   | 264 ms                                                       | 265 ms: 1.00x slower                                                                   |
| sympy_str                  | 305 ms                                                       | 306 ms: 1.00x slower                                                                   |
| json                       | 5.17 ms                                                      | 5.20 ms: 1.01x slower                                                                  |
| json_loads                 | 24.3 us                                                      | 24.5 us: 1.01x slower                                                                  |
| logging_format             | 7.29 us                                                      | 7.35 us: 1.01x slower                                                                  |
| xml_etree_process          | 58.3 ms                                                      | 58.9 ms: 1.01x slower                                                                  |
| gc_traversal               | 3.70 ms                                                      | 3.74 ms: 1.01x slower                                                                  |
| regex_dna                  | 240 ms                                                       | 243 ms: 1.01x slower                                                                   |
| async_tree_cpu_io_mixed    | 704 ms                                                       | 712 ms: 1.01x slower                                                                   |
| asyncio_tcp_ssl            | 1.57 sec                                                     | 1.60 sec: 1.01x slower                                                                 |
| async_tree_memoization     | 554 ms                                                       | 562 ms: 1.01x slower                                                                   |
| xml_etree_generate         | 85.3 ms                                                      | 86.6 ms: 1.02x slower                                                                  |
| docutils                   | 2.89 sec                                                     | 2.94 sec: 1.02x slower                                                                 |
| create_gc_cycles           | 1.58 ms                                                      | 1.60 ms: 1.02x slower                                                                  |
| xml_etree_parse            | 147 ms                                                       | 149 ms: 1.02x slower                                                                   |
| deepcopy                   | 371 us                                                       | 379 us: 1.02x slower                                                                   |
| chameleon                  | 7.27 ms                                                      | 7.43 ms: 1.02x slower                                                                  |
| sqlglot_optimize           | 58.4 ms                                                      | 59.9 ms: 1.03x slower                                                                  |
| sympy_integrate            | 24.0 ms                                                      | 24.6 ms: 1.03x slower                                                                  |
| bench_thread_pool          | 956 us                                                       | 985 us: 1.03x slower                                                                   |
| mdp                        | 2.56 sec                                                     | 2.64 sec: 1.03x slower                                                                 |
| logging_simple             | 6.64 us                                                      | 6.86 us: 1.03x slower                                                                  |
| async_tree_memoization_tg  | 554 ms                                                       | 573 ms: 1.03x slower                                                                   |
| async_tree_cpu_io_mixed_tg | 706 ms                                                       | 731 ms: 1.04x slower                                                                   |
| async_tree_io              | 1.06 sec                                                     | 1.10 sec: 1.04x slower                                                                 |
| sqlglot_parse              | 1.41 ms                                                      | 1.46 ms: 1.04x slower                                                                  |
| json_dumps                 | 10.3 ms                                                      | 10.6 ms: 1.04x slower                                                                  |
| sqlglot_transpile          | 1.80 ms                                                      | 1.88 ms: 1.04x slower                                                                  |
| mypy2                      | 365 ms                                                       | 381 ms: 1.04x slower                                                                   |
| async_tree_io_tg           | 1.07 sec                                                     | 1.12 sec: 1.04x slower                                                                 |
| async_tree_none_tg         | 440 ms                                                       | 460 ms: 1.05x slower                                                                   |
| sympy_expand               | 492 ms                                                       | 519 ms: 1.06x slower                                                                   |
| pycparser                  | 1.29 sec                                                     | 1.37 sec: 1.06x slower                                                                 |
| logging_silent             | 93.3 ns                                                      | 98.5 ns: 1.06x slower                                                                  |
| xml_etree_iterparse        | 104 ms                                                       | 110 ms: 1.06x slower                                                                   |
| chaos                      | 64.1 ms                                                      | 68.4 ms: 1.07x slower                                                                  |
| scimark_lu                 | 98.6 ms                                                      | 106 ms: 1.07x slower                                                                   |
| meteor_contest             | 126 ms                                                       | 136 ms: 1.08x slower                                                                   |
| pathlib                    | 18.7 ms                                                      | 20.2 ms: 1.08x slower                                                                  |
| scimark_monte_carlo        | 69.5 ms                                                      | 75.3 ms: 1.08x slower                                                                  |
| 2to3                       | 285 ms                                                       | 308 ms: 1.08x slower                                                                   |
| dulwich_log                | 64.9 ms                                                      | 70.5 ms: 1.09x slower                                                                  |
| python_startup             | 11.7 ms                                                      | 12.9 ms: 1.10x slower                                                                  |
| pprint_safe_repr           | 808 ms                                                       | 906 ms: 1.12x slower                                                                   |
| scimark_fft                | 303 ms                                                       | 343 ms: 1.13x slower                                                                   |
| pprint_pformat             | 1.64 sec                                                     | 1.86 sec: 1.13x slower                                                                 |
| telco                      | 7.16 ms                                                      | 8.15 ms: 1.14x slower                                                                  |
| deepcopy_memo              | 36.6 us                                                      | 42.4 us: 1.16x slower                                                                  |
| richards_super             | 50.8 ms                                                      | 59.1 ms: 1.16x slower                                                                  |
| fannkuch                   | 362 ms                                                       | 425 ms: 1.17x slower                                                                   |
| richards                   | 45.1 ms                                                      | 53.2 ms: 1.18x slower                                                                  |
| scimark_sparse_mat_mult    | 4.49 ms                                                      | 5.30 ms: 1.18x slower                                                                  |
| unpickle_pure_python       | 210 us                                                       | 248 us: 1.18x slower                                                                   |
| comprehensions             | 21.8 us                                                      | 26.1 us: 1.20x slower                                                                  |
| regex_compile              | 145 ms                                                       | 174 ms: 1.20x slower                                                                   |
| coverage                   | 66.3 ms                                                      | 80.2 ms: 1.21x slower                                                                  |
| go                         | 149 ms                                                       | 182 ms: 1.22x slower                                                                   |
| pyflate                    | 442 ms                                                       | 545 ms: 1.23x slower                                                                   |
| nqueens                    | 90.1 ms                                                      | 112 ms: 1.25x slower                                                                   |
| nbody                      | 88.2 ms                                                      | 110 ms: 1.25x slower                                                                   |
| float                      | 81.6 ms                                                      | 103 ms: 1.27x slower                                                                   |
| tomli_loads                | 2.17 sec                                                     | 2.78 sec: 1.28x slower                                                                 |
| python_startup_no_site     | 8.67 ms                                                      | 11.4 ms: 1.31x slower                                                                  |
| mako                       | 10.1 ms                                                      | 14.3 ms: 1.42x slower                                                                  |
| scimark_sor                | 107 ms                                                       | 152 ms: 1.43x slower                                                                   |
| deltablue                  | 3.24 ms                                                      | 5.41 ms: 1.67x slower                                                                  |
| hexiom                     | 5.97 ms                                                      | 9.99 ms: 1.67x slower                                                                  |
| Geometric mean             | (ref)                                                        | 1.07x slower                                                                           |

Benchmark hidden because not significant (6): unpickle_list, pickle_dict, asyncio_websockets, pickle_list, raytrace, tornado_http
Ignored benchmarks (6) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, dask, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.03x
- 95% likely to have a slowdown of 1.03x
- 99% likely to have a slowdown of 1.02x
