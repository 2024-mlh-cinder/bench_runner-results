
# Results vs. 3.12.0

- fork: python
- ref: 6dfb8fe0236718e9afc8
- machine: linux-x86_64
- commit hash: 6dfb8fe
- commit date: 2023-10-30
- overall geometric mean: 1.02x slower
- HPT reliability: 99.41%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231030-pythonperf2-x86_64-python-6dfb8fe0236718e9afc8-3.13.0a1+-6dfb8fe |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| 2to3           | 285 ms                                                       | 297 ms: 1.04x slower                                                         |
| chameleon      | 7.27 ms                                                      | 7.54 ms: 1.04x slower                                                        |
| docutils       | 2.89 sec                                                     | 2.88 sec: 1.00x faster                                                       |
| tornado_http   | 122 ms                                                       | 120 ms: 1.02x faster                                                         |
| Geometric mean | (ref)                                                        | 1.02x slower                                                                 |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231030-pythonperf2-x86_64-python-6dfb8fe0236718e9afc8-3.13.0a1+-6dfb8fe |
|----------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| async_tree_none            | 459 ms                                                       | 435 ms: 1.06x faster                                                         |
| async_tree_memoization     | 554 ms                                                       | 548 ms: 1.01x faster                                                         |
| async_tree_none_tg         | 440 ms                                                       | 443 ms: 1.01x slower                                                         |
| async_tree_cpu_io_mixed_tg | 706 ms                                                       | 716 ms: 1.01x slower                                                         |
| async_tree_io              | 1.06 sec                                                     | 1.08 sec: 1.03x slower                                                       |
| async_tree_io_tg           | 1.07 sec                                                     | 1.10 sec: 1.03x slower                                                       |
| async_tree_memoization_tg  | 554 ms                                                       | 574 ms: 1.04x slower                                                         |
| Geometric mean             | (ref)                                                        | 1.00x slower                                                                 |

Benchmark hidden because not significant (1): async_tree_cpu_io_mixed

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231030-pythonperf2-x86_64-python-6dfb8fe0236718e9afc8-3.13.0a1+-6dfb8fe |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| float          | 81.6 ms                                                      | 78.4 ms: 1.04x faster                                                        |
| Geometric mean | (ref)                                                        | 1.00x faster                                                                 |

Benchmark hidden because not significant (2): pidigits, nbody

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231030-pythonperf2-x86_64-python-6dfb8fe0236718e9afc8-3.13.0a1+-6dfb8fe |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| regex_effbot   | 3.61 ms                                                      | 3.53 ms: 1.02x faster                                                        |
| regex_compile  | 145 ms                                                       | 148 ms: 1.02x slower                                                         |
| regex_dna      | 240 ms                                                       | 249 ms: 1.04x slower                                                         |
| regex_v8       | 24.4 ms                                                      | 25.5 ms: 1.05x slower                                                        |
| Geometric mean | (ref)                                                        | 1.02x slower                                                                 |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231030-pythonperf2-x86_64-python-6dfb8fe0236718e9afc8-3.13.0a1+-6dfb8fe |
|----------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| unpickle             | 15.3 us                                                      | 14.5 us: 1.05x faster                                                        |
| unpickle_list        | 4.65 us                                                      | 4.51 us: 1.03x faster                                                        |
| pickle_dict          | 32.0 us                                                      | 31.8 us: 1.01x faster                                                        |
| xml_etree_generate   | 85.3 ms                                                      | 85.7 ms: 1.00x slower                                                        |
| xml_etree_parse      | 147 ms                                                       | 148 ms: 1.01x slower                                                         |
| tomli_loads          | 2.17 sec                                                     | 2.21 sec: 1.02x slower                                                       |
| pickle_pure_python   | 319 us                                                       | 325 us: 1.02x slower                                                         |
| json_loads           | 24.3 us                                                      | 24.8 us: 1.02x slower                                                        |
| pickle               | 10.0 us                                                      | 10.4 us: 1.03x slower                                                        |
| xml_etree_iterparse  | 104 ms                                                       | 107 ms: 1.04x slower                                                         |
| pickle_list          | 4.22 us                                                      | 4.41 us: 1.05x slower                                                        |
| json_dumps           | 10.3 ms                                                      | 10.8 ms: 1.05x slower                                                        |
| unpickle_pure_python | 210 us                                                       | 223 us: 1.06x slower                                                         |
| Geometric mean       | (ref)                                                        | 1.01x slower                                                                 |

Benchmark hidden because not significant (1): xml_etree_process

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231030-pythonperf2-x86_64-python-6dfb8fe0236718e9afc8-3.13.0a1+-6dfb8fe |
|------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| python_startup         | 11.7 ms                                                      | 12.8 ms: 1.10x slower                                                        |
| python_startup_no_site | 8.67 ms                                                      | 11.3 ms: 1.30x slower                                                        |
| Geometric mean         | (ref)                                                        | 1.20x slower                                                                 |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231030-pythonperf2-x86_64-python-6dfb8fe0236718e9afc8-3.13.0a1+-6dfb8fe |
|-----------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| mako      | 10.1 ms                                                      | 10.4 ms: 1.03x slower                                                        |

All benchmarks:
===============

| Benchmark                  | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231030-pythonperf2-x86_64-python-6dfb8fe0236718e9afc8-3.13.0a1+-6dfb8fe |
|----------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| comprehensions             | 21.8 us                                                      | 16.7 us: 1.31x faster                                                        |
| crypto_pyaes               | 82.4 ms                                                      | 72.5 ms: 1.14x faster                                                        |
| unpack_sequence            | 54.5 ns                                                      | 49.3 ns: 1.11x faster                                                        |
| raytrace                   | 301 ms                                                       | 280 ms: 1.08x faster                                                         |
| scimark_sparse_mat_mult    | 4.49 ms                                                      | 4.19 ms: 1.07x faster                                                        |
| bench_mp_pool              | 4.96 ms                                                      | 4.63 ms: 1.07x faster                                                        |
| sympy_sum                  | 163 ms                                                       | 153 ms: 1.07x faster                                                         |
| async_tree_none            | 459 ms                                                       | 435 ms: 1.06x faster                                                         |
| unpickle                   | 15.3 us                                                      | 14.5 us: 1.05x faster                                                        |
| sympy_str                  | 305 ms                                                       | 290 ms: 1.05x faster                                                         |
| float                      | 81.6 ms                                                      | 78.4 ms: 1.04x faster                                                        |
| generators                 | 37.3 ms                                                      | 36.0 ms: 1.04x faster                                                        |
| chaos                      | 64.1 ms                                                      | 61.9 ms: 1.03x faster                                                        |
| unpickle_list              | 4.65 us                                                      | 4.51 us: 1.03x faster                                                        |
| sqlglot_normalize          | 119 ms                                                       | 116 ms: 1.03x faster                                                         |
| nqueens                    | 90.1 ms                                                      | 87.6 ms: 1.03x faster                                                        |
| sympy_integrate            | 24.0 ms                                                      | 23.4 ms: 1.03x faster                                                        |
| regex_effbot               | 3.61 ms                                                      | 3.53 ms: 1.02x faster                                                        |
| asyncio_tcp                | 380 ms                                                       | 372 ms: 1.02x faster                                                         |
| sqlite_synth               | 2.72 us                                                      | 2.66 us: 1.02x faster                                                        |
| coroutines                 | 23.1 ms                                                      | 22.6 ms: 1.02x faster                                                        |
| tornado_http               | 122 ms                                                       | 120 ms: 1.02x faster                                                         |
| scimark_monte_carlo        | 69.5 ms                                                      | 68.7 ms: 1.01x faster                                                        |
| async_tree_memoization     | 554 ms                                                       | 548 ms: 1.01x faster                                                         |
| spectral_norm              | 93.9 ms                                                      | 93.0 ms: 1.01x faster                                                        |
| mdp                        | 2.56 sec                                                     | 2.53 sec: 1.01x faster                                                       |
| deepcopy_reduce            | 3.41 us                                                      | 3.39 us: 1.01x faster                                                        |
| sympy_expand               | 492 ms                                                       | 488 ms: 1.01x faster                                                         |
| scimark_fft                | 303 ms                                                       | 301 ms: 1.01x faster                                                         |
| pickle_dict                | 32.0 us                                                      | 31.8 us: 1.01x faster                                                        |
| docutils                   | 2.89 sec                                                     | 2.88 sec: 1.00x faster                                                       |
| mypy2                      | 365 ms                                                       | 366 ms: 1.00x slower                                                         |
| xml_etree_generate         | 85.3 ms                                                      | 85.7 ms: 1.00x slower                                                        |
| asyncio_tcp_ssl            | 1.57 sec                                                     | 1.58 sec: 1.01x slower                                                       |
| sqlglot_transpile          | 1.80 ms                                                      | 1.82 ms: 1.01x slower                                                        |
| async_tree_none_tg         | 440 ms                                                       | 443 ms: 1.01x slower                                                         |
| sqlglot_optimize           | 58.4 ms                                                      | 58.8 ms: 1.01x slower                                                        |
| xml_etree_parse            | 147 ms                                                       | 148 ms: 1.01x slower                                                         |
| json                       | 5.17 ms                                                      | 5.23 ms: 1.01x slower                                                        |
| deepcopy                   | 371 us                                                       | 376 us: 1.01x slower                                                         |
| scimark_lu                 | 98.6 ms                                                      | 99.8 ms: 1.01x slower                                                        |
| logging_simple             | 6.64 us                                                      | 6.73 us: 1.01x slower                                                        |
| async_tree_cpu_io_mixed_tg | 706 ms                                                       | 716 ms: 1.01x slower                                                         |
| tomli_loads                | 2.17 sec                                                     | 2.21 sec: 1.02x slower                                                       |
| meteor_contest             | 126 ms                                                       | 129 ms: 1.02x slower                                                         |
| pickle_pure_python         | 319 us                                                       | 325 us: 1.02x slower                                                         |
| regex_compile              | 145 ms                                                       | 148 ms: 1.02x slower                                                         |
| json_loads                 | 24.3 us                                                      | 24.8 us: 1.02x slower                                                        |
| logging_format             | 7.29 us                                                      | 7.45 us: 1.02x slower                                                        |
| typing_runtime_protocols   | 150 us                                                       | 154 us: 1.02x slower                                                         |
| async_tree_io              | 1.06 sec                                                     | 1.08 sec: 1.03x slower                                                       |
| async_tree_io_tg           | 1.07 sec                                                     | 1.10 sec: 1.03x slower                                                       |
| async_generators           | 385 ms                                                       | 395 ms: 1.03x slower                                                         |
| pprint_safe_repr           | 808 ms                                                       | 828 ms: 1.03x slower                                                         |
| mako                       | 10.1 ms                                                      | 10.4 ms: 1.03x slower                                                        |
| pickle                     | 10.0 us                                                      | 10.4 us: 1.03x slower                                                        |
| deepcopy_memo              | 36.6 us                                                      | 37.8 us: 1.03x slower                                                        |
| pprint_pformat             | 1.64 sec                                                     | 1.70 sec: 1.03x slower                                                       |
| xml_etree_iterparse        | 104 ms                                                       | 107 ms: 1.04x slower                                                         |
| regex_dna                  | 240 ms                                                       | 249 ms: 1.04x slower                                                         |
| async_tree_memoization_tg  | 554 ms                                                       | 574 ms: 1.04x slower                                                         |
| chameleon                  | 7.27 ms                                                      | 7.54 ms: 1.04x slower                                                        |
| 2to3                       | 285 ms                                                       | 297 ms: 1.04x slower                                                         |
| logging_silent             | 93.3 ns                                                      | 97.4 ns: 1.04x slower                                                        |
| regex_v8                   | 24.4 ms                                                      | 25.5 ms: 1.05x slower                                                        |
| pickle_list                | 4.22 us                                                      | 4.41 us: 1.05x slower                                                        |
| pathlib                    | 18.7 ms                                                      | 19.7 ms: 1.05x slower                                                        |
| json_dumps                 | 10.3 ms                                                      | 10.8 ms: 1.05x slower                                                        |
| unpickle_pure_python       | 210 us                                                       | 223 us: 1.06x slower                                                         |
| dulwich_log                | 64.9 ms                                                      | 69.1 ms: 1.06x slower                                                        |
| hexiom                     | 5.97 ms                                                      | 6.45 ms: 1.08x slower                                                        |
| fannkuch                   | 362 ms                                                       | 397 ms: 1.10x slower                                                         |
| python_startup             | 11.7 ms                                                      | 12.8 ms: 1.10x slower                                                        |
| telco                      | 7.16 ms                                                      | 8.08 ms: 1.13x slower                                                        |
| go                         | 149 ms                                                       | 170 ms: 1.14x slower                                                         |
| deltablue                  | 3.24 ms                                                      | 3.71 ms: 1.15x slower                                                        |
| pyflate                    | 442 ms                                                       | 510 ms: 1.15x slower                                                         |
| richards_super             | 50.8 ms                                                      | 60.2 ms: 1.18x slower                                                        |
| richards                   | 45.1 ms                                                      | 54.4 ms: 1.21x slower                                                        |
| coverage                   | 66.3 ms                                                      | 82.9 ms: 1.25x slower                                                        |
| python_startup_no_site     | 8.67 ms                                                      | 11.3 ms: 1.30x slower                                                        |
| scimark_sor                | 107 ms                                                       | 145 ms: 1.35x slower                                                         |
| Geometric mean             | (ref)                                                        | 1.02x slower                                                                 |

Benchmark hidden because not significant (10): async_tree_cpu_io_mixed, gc_traversal, sqlglot_parse, create_gc_cycles, xml_etree_process, pidigits, pycparser, asyncio_websockets, bench_thread_pool, nbody
Ignored benchmarks (6) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, dask, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 99.41% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
