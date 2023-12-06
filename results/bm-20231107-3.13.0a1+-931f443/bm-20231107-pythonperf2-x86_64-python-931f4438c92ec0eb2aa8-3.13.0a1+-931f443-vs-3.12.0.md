
# Results vs. 3.12.0

- fork: python
- ref: 931f4438c92ec0eb2aa8
- machine: linux-x86_64
- commit hash: 931f443
- commit date: 2023-11-07
- overall geometric mean: 1.01x slower \*
- HPT reliability: 81.48%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231107-pythonperf2-x86_64-python-931f4438c92ec0eb2aa8-3.13.0a1+-931f443 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| 2to3           | 285 ms                                                       | 290 ms: 1.02x slower                                                         |
| chameleon      | 7.27 ms                                                      | 7.24 ms: 1.00x faster                                                        |
| docutils       | 2.89 sec                                                     | 2.82 sec: 1.02x faster                                                       |
| tornado_http   | 122 ms                                                       | 119 ms: 1.02x faster                                                         |
| Geometric mean | (ref)                                                        | 1.01x faster                                                                 |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231107-pythonperf2-x86_64-python-931f4438c92ec0eb2aa8-3.13.0a1+-931f443 |
|----------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| async_tree_none            | 459 ms                                                       | 432 ms: 1.06x faster                                                         |
| async_tree_memoization     | 554 ms                                                       | 547 ms: 1.01x faster                                                         |
| async_tree_none_tg         | 440 ms                                                       | 444 ms: 1.01x slower                                                         |
| async_tree_cpu_io_mixed_tg | 706 ms                                                       | 717 ms: 1.02x slower                                                         |
| async_tree_io              | 1.06 sec                                                     | 1.08 sec: 1.02x slower                                                       |
| async_tree_io_tg           | 1.07 sec                                                     | 1.10 sec: 1.03x slower                                                       |
| async_tree_memoization_tg  | 554 ms                                                       | 570 ms: 1.03x slower                                                         |
| Geometric mean             | (ref)                                                        | 1.00x slower                                                                 |

Benchmark hidden because not significant (1): async_tree_cpu_io_mixed

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231107-pythonperf2-x86_64-python-931f4438c92ec0eb2aa8-3.13.0a1+-931f443 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| float          | 81.6 ms                                                      | 79.1 ms: 1.03x faster                                                        |
| pidigits       | 264 ms                                                       | 265 ms: 1.00x slower                                                         |
| Geometric mean | (ref)                                                        | 1.02x faster                                                                 |

Benchmark hidden because not significant (1): nbody

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231107-pythonperf2-x86_64-python-931f4438c92ec0eb2aa8-3.13.0a1+-931f443 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| regex_compile  | 145 ms                                                       | 146 ms: 1.01x slower                                                         |
| regex_v8       | 24.4 ms                                                      | 25.2 ms: 1.03x slower                                                        |
| regex_dna      | 240 ms                                                       | 253 ms: 1.05x slower                                                         |
| Geometric mean | (ref)                                                        | 1.02x slower                                                                 |

Benchmark hidden because not significant (1): regex_effbot

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231107-pythonperf2-x86_64-python-931f4438c92ec0eb2aa8-3.13.0a1+-931f443 |
|----------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| unpickle             | 15.3 us                                                      | 14.8 us: 1.03x faster                                                        |
| pickle_pure_python   | 319 us                                                       | 310 us: 1.03x faster                                                         |
| json_dumps           | 10.3 ms                                                      | 10.3 ms: 1.00x slower                                                        |
| xml_etree_process    | 58.3 ms                                                      | 58.7 ms: 1.01x slower                                                        |
| unpickle_list        | 4.65 us                                                      | 4.71 us: 1.01x slower                                                        |
| pickle               | 10.0 us                                                      | 10.2 us: 1.02x slower                                                        |
| xml_etree_generate   | 85.3 ms                                                      | 86.7 ms: 1.02x slower                                                        |
| pickle_dict          | 32.0 us                                                      | 33.0 us: 1.03x slower                                                        |
| pickle_list          | 4.22 us                                                      | 4.41 us: 1.05x slower                                                        |
| tomli_loads          | 2.17 sec                                                     | 2.35 sec: 1.08x slower                                                       |
| unpickle_pure_python | 210 us                                                       | 231 us: 1.10x slower                                                         |
| Geometric mean       | (ref)                                                        | 1.02x slower                                                                 |

Benchmark hidden because not significant (3): xml_etree_parse, json_loads, xml_etree_iterparse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231107-pythonperf2-x86_64-python-931f4438c92ec0eb2aa8-3.13.0a1+-931f443 |
|------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| python_startup         | 11.7 ms                                                      | 12.8 ms: 1.09x slower                                                        |
| python_startup_no_site | 8.67 ms                                                      | 11.3 ms: 1.30x slower                                                        |
| Geometric mean         | (ref)                                                        | 1.19x slower                                                                 |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231107-pythonperf2-x86_64-python-931f4438c92ec0eb2aa8-3.13.0a1+-931f443 |
|-----------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| mako      | 10.1 ms                                                      | 10.2 ms: 1.02x slower                                                        |

All benchmarks:
===============

| Benchmark                  | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231107-pythonperf2-x86_64-python-931f4438c92ec0eb2aa8-3.13.0a1+-931f443 |
|----------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| comprehensions             | 21.8 us                                                      | 16.3 us: 1.34x faster                                                        |
| typing_runtime_protocols   | 150 us                                                       | 121 us: 1.25x faster                                                         |
| crypto_pyaes               | 82.4 ms                                                      | 71.6 ms: 1.15x faster                                                        |
| raytrace                   | 301 ms                                                       | 270 ms: 1.11x faster                                                         |
| sympy_sum                  | 163 ms                                                       | 150 ms: 1.08x faster                                                         |
| async_generators           | 385 ms                                                       | 359 ms: 1.07x faster                                                         |
| scimark_sparse_mat_mult    | 4.49 ms                                                      | 4.20 ms: 1.07x faster                                                        |
| bench_mp_pool              | 4.96 ms                                                      | 4.64 ms: 1.07x faster                                                        |
| async_tree_none            | 459 ms                                                       | 432 ms: 1.06x faster                                                         |
| generators                 | 37.3 ms                                                      | 35.2 ms: 1.06x faster                                                        |
| sympy_str                  | 305 ms                                                       | 288 ms: 1.06x faster                                                         |
| chaos                      | 64.1 ms                                                      | 60.8 ms: 1.05x faster                                                        |
| deepcopy_reduce            | 3.41 us                                                      | 3.24 us: 1.05x faster                                                        |
| sqlglot_normalize          | 119 ms                                                       | 114 ms: 1.05x faster                                                         |
| unpack_sequence            | 54.5 ns                                                      | 52.2 ns: 1.04x faster                                                        |
| sympy_integrate            | 24.0 ms                                                      | 23.0 ms: 1.04x faster                                                        |
| spectral_norm              | 93.9 ms                                                      | 90.6 ms: 1.04x faster                                                        |
| unpickle                   | 15.3 us                                                      | 14.8 us: 1.03x faster                                                        |
| float                      | 81.6 ms                                                      | 79.1 ms: 1.03x faster                                                        |
| asyncio_tcp                | 380 ms                                                       | 368 ms: 1.03x faster                                                         |
| pickle_pure_python         | 319 us                                                       | 310 us: 1.03x faster                                                         |
| coroutines                 | 23.1 ms                                                      | 22.4 ms: 1.03x faster                                                        |
| sqlite_synth               | 2.72 us                                                      | 2.65 us: 1.02x faster                                                        |
| docutils                   | 2.89 sec                                                     | 2.82 sec: 1.02x faster                                                       |
| tornado_http               | 122 ms                                                       | 119 ms: 1.02x faster                                                         |
| pprint_safe_repr           | 808 ms                                                       | 792 ms: 1.02x faster                                                         |
| create_gc_cycles           | 1.58 ms                                                      | 1.55 ms: 1.02x faster                                                        |
| deepcopy                   | 371 us                                                       | 365 us: 1.02x faster                                                         |
| pprint_pformat             | 1.64 sec                                                     | 1.62 sec: 1.02x faster                                                       |
| sympy_expand               | 492 ms                                                       | 485 ms: 1.01x faster                                                         |
| json                       | 5.17 ms                                                      | 5.10 ms: 1.01x faster                                                        |
| nqueens                    | 90.1 ms                                                      | 88.9 ms: 1.01x faster                                                        |
| pycparser                  | 1.29 sec                                                     | 1.28 sec: 1.01x faster                                                       |
| async_tree_memoization     | 554 ms                                                       | 547 ms: 1.01x faster                                                         |
| scimark_fft                | 303 ms                                                       | 300 ms: 1.01x faster                                                         |
| sqlglot_optimize           | 58.4 ms                                                      | 57.8 ms: 1.01x faster                                                        |
| sqlglot_parse              | 1.41 ms                                                      | 1.40 ms: 1.01x faster                                                        |
| scimark_monte_carlo        | 69.5 ms                                                      | 69.2 ms: 1.01x faster                                                        |
| mypy2                      | 365 ms                                                       | 364 ms: 1.00x faster                                                         |
| chameleon                  | 7.27 ms                                                      | 7.24 ms: 1.00x faster                                                        |
| pidigits                   | 264 ms                                                       | 265 ms: 1.00x slower                                                         |
| json_dumps                 | 10.3 ms                                                      | 10.3 ms: 1.00x slower                                                        |
| asyncio_tcp_ssl            | 1.57 sec                                                     | 1.58 sec: 1.01x slower                                                       |
| mdp                        | 2.56 sec                                                     | 2.57 sec: 1.01x slower                                                       |
| xml_etree_process          | 58.3 ms                                                      | 58.7 ms: 1.01x slower                                                        |
| regex_compile              | 145 ms                                                       | 146 ms: 1.01x slower                                                         |
| scimark_lu                 | 98.6 ms                                                      | 99.5 ms: 1.01x slower                                                        |
| async_tree_none_tg         | 440 ms                                                       | 444 ms: 1.01x slower                                                         |
| unpickle_list              | 4.65 us                                                      | 4.71 us: 1.01x slower                                                        |
| pickle                     | 10.0 us                                                      | 10.2 us: 1.02x slower                                                        |
| async_tree_cpu_io_mixed_tg | 706 ms                                                       | 717 ms: 1.02x slower                                                         |
| xml_etree_generate         | 85.3 ms                                                      | 86.7 ms: 1.02x slower                                                        |
| mako                       | 10.1 ms                                                      | 10.2 ms: 1.02x slower                                                        |
| logging_format             | 7.29 us                                                      | 7.42 us: 1.02x slower                                                        |
| 2to3                       | 285 ms                                                       | 290 ms: 1.02x slower                                                         |
| meteor_contest             | 126 ms                                                       | 129 ms: 1.02x slower                                                         |
| logging_silent             | 93.3 ns                                                      | 95.0 ns: 1.02x slower                                                        |
| gc_traversal               | 3.70 ms                                                      | 3.78 ms: 1.02x slower                                                        |
| async_tree_io              | 1.06 sec                                                     | 1.08 sec: 1.02x slower                                                       |
| async_tree_io_tg           | 1.07 sec                                                     | 1.10 sec: 1.03x slower                                                       |
| async_tree_memoization_tg  | 554 ms                                                       | 570 ms: 1.03x slower                                                         |
| regex_v8                   | 24.4 ms                                                      | 25.2 ms: 1.03x slower                                                        |
| pickle_dict                | 32.0 us                                                      | 33.0 us: 1.03x slower                                                        |
| dulwich_log                | 64.9 ms                                                      | 67.9 ms: 1.05x slower                                                        |
| pickle_list                | 4.22 us                                                      | 4.41 us: 1.05x slower                                                        |
| pathlib                    | 18.7 ms                                                      | 19.7 ms: 1.05x slower                                                        |
| regex_dna                  | 240 ms                                                       | 253 ms: 1.05x slower                                                         |
| hexiom                     | 5.97 ms                                                      | 6.46 ms: 1.08x slower                                                        |
| tomli_loads                | 2.17 sec                                                     | 2.35 sec: 1.08x slower                                                       |
| fannkuch                   | 362 ms                                                       | 396 ms: 1.09x slower                                                         |
| python_startup             | 11.7 ms                                                      | 12.8 ms: 1.09x slower                                                        |
| unpickle_pure_python       | 210 us                                                       | 231 us: 1.10x slower                                                         |
| telco                      | 7.16 ms                                                      | 8.05 ms: 1.13x slower                                                        |
| deltablue                  | 3.24 ms                                                      | 3.66 ms: 1.13x slower                                                        |
| pyflate                    | 442 ms                                                       | 505 ms: 1.14x slower                                                         |
| go                         | 149 ms                                                       | 170 ms: 1.14x slower                                                         |
| richards_super             | 50.8 ms                                                      | 58.3 ms: 1.15x slower                                                        |
| richards                   | 45.1 ms                                                      | 53.2 ms: 1.18x slower                                                        |
| coverage                   | 66.3 ms                                                      | 81.5 ms: 1.23x slower                                                        |
| python_startup_no_site     | 8.67 ms                                                      | 11.3 ms: 1.30x slower                                                        |
| scimark_sor                | 107 ms                                                       | 146 ms: 1.36x slower                                                         |
| Geometric mean             | (ref)                                                        | 1.01x slower                                                                 |

Benchmark hidden because not significant (11): nbody, async_tree_cpu_io_mixed, sqlglot_transpile, xml_etree_parse, logging_simple, regex_effbot, deepcopy_memo, json_loads, asyncio_websockets, xml_etree_iterparse, bench_thread_pool
Ignored benchmarks (6) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, dask, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 81.48% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
