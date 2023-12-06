
# Results vs. 3.12.0

- fork: iritkatriel
- ref: gen_yf
- machine: linux-x86_64
- commit hash: 0b37841
- commit date: 2023-11-02
- overall geometric mean: 1.03x faster
- HPT reliability: 99.87%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231102-linux-x86_64-iritkatriel-gen_yf-3.13.0a1+-0b37841 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| 2to3           | 274 ms                                                 | 264 ms: 1.04x faster                                          |
| chameleon      | 7.41 ms                                                | 7.06 ms: 1.05x faster                                         |
| docutils       | 2.75 sec                                               | 2.61 sec: 1.06x faster                                        |
| tornado_http   | 101 ms                                                 | 95.1 ms: 1.06x faster                                         |
| Geometric mean | (ref)                                                  | 1.05x faster                                                  |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231102-linux-x86_64-iritkatriel-gen_yf-3.13.0a1+-0b37841 |
|----------------------------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| async_tree_none            | 475 ms                                                 | 436 ms: 1.09x faster                                          |
| async_tree_memoization     | 580 ms                                                 | 565 ms: 1.03x faster                                          |
| async_tree_none_tg         | 447 ms                                                 | 456 ms: 1.02x slower                                          |
| async_tree_io              | 1.16 sec                                               | 1.19 sec: 1.02x slower                                        |
| async_tree_cpu_io_mixed_tg | 725 ms                                                 | 750 ms: 1.03x slower                                          |
| async_tree_io_tg           | 1.19 sec                                               | 1.23 sec: 1.04x slower                                        |
| async_tree_memoization_tg  | 574 ms                                                 | 602 ms: 1.05x slower                                          |
| Geometric mean             | (ref)                                                  | 1.00x slower                                                  |

Benchmark hidden because not significant (1): async_tree_cpu_io_mixed

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231102-linux-x86_64-iritkatriel-gen_yf-3.13.0a1+-0b37841 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| nbody          | 92.2 ms                                                | 88.0 ms: 1.05x faster                                         |
| float          | 83.3 ms                                                | 82.3 ms: 1.01x faster                                         |
| pidigits       | 187 ms                                                 | 195 ms: 1.04x slower                                          |
| Geometric mean | (ref)                                                  | 1.01x faster                                                  |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231102-linux-x86_64-iritkatriel-gen_yf-3.13.0a1+-0b37841 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| regex_compile  | 148 ms                                                 | 134 ms: 1.10x faster                                          |
| regex_dna      | 209 ms                                                 | 215 ms: 1.03x slower                                          |
| regex_v8       | 22.7 ms                                                | 25.8 ms: 1.14x slower                                         |
| Geometric mean | (ref)                                                  | 1.02x slower                                                  |

Benchmark hidden because not significant (1): regex_effbot

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231102-linux-x86_64-iritkatriel-gen_yf-3.13.0a1+-0b37841 |
|----------------------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| pickle_pure_python   | 326 us                                                 | 296 us: 1.10x faster                                          |
| tomli_loads          | 2.30 sec                                               | 2.15 sec: 1.07x faster                                        |
| unpickle_pure_python | 230 us                                                 | 217 us: 1.06x faster                                          |
| xml_etree_process    | 61.2 ms                                                | 59.4 ms: 1.03x faster                                         |
| xml_etree_generate   | 88.7 ms                                                | 86.5 ms: 1.03x faster                                         |
| json_loads           | 28.4 us                                                | 27.9 us: 1.02x faster                                         |
| json_dumps           | 10.6 ms                                                | 10.5 ms: 1.01x faster                                         |
| xml_etree_iterparse  | 106 ms                                                 | 107 ms: 1.01x slower                                          |
| xml_etree_parse      | 159 ms                                                 | 161 ms: 1.01x slower                                          |
| unpickle_list        | 5.04 us                                                | 5.15 us: 1.02x slower                                         |
| pickle               | 11.2 us                                                | 11.5 us: 1.03x slower                                         |
| pickle_dict          | 33.5 us                                                | 35.2 us: 1.05x slower                                         |
| pickle_list          | 4.67 us                                                | 5.04 us: 1.08x slower                                         |
| Geometric mean       | (ref)                                                  | 1.01x faster                                                  |

Benchmark hidden because not significant (1): unpickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231102-linux-x86_64-iritkatriel-gen_yf-3.13.0a1+-0b37841 |
|------------------------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| python_startup         | 9.53 ms                                                | 10.3 ms: 1.08x slower                                         |
| python_startup_no_site | 6.92 ms                                                | 8.99 ms: 1.30x slower                                         |
| Geometric mean         | (ref)                                                  | 1.19x slower                                                  |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231102-linux-x86_64-iritkatriel-gen_yf-3.13.0a1+-0b37841 |
|-----------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| mako      | 11.5 ms                                                | 11.4 ms: 1.01x faster                                         |

All benchmarks:
===============

| Benchmark                  | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231102-linux-x86_64-iritkatriel-gen_yf-3.13.0a1+-0b37841 |
|----------------------------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| typing_runtime_protocols   | 153 us                                                 | 115 us: 1.34x faster                                          |
| comprehensions             | 20.9 us                                                | 16.4 us: 1.28x faster                                         |
| scimark_sparse_mat_mult    | 5.33 ms                                                | 4.52 ms: 1.18x faster                                         |
| crypto_pyaes               | 83.6 ms                                                | 72.2 ms: 1.16x faster                                         |
| sympy_sum                  | 167 ms                                                 | 147 ms: 1.14x faster                                          |
| unpack_sequence            | 54.2 ns                                                | 48.2 ns: 1.12x faster                                         |
| gc_traversal               | 4.28 ms                                                | 3.81 ms: 1.12x faster                                         |
| raytrace                   | 308 ms                                                 | 275 ms: 1.12x faster                                          |
| deltablue                  | 3.71 ms                                                | 3.33 ms: 1.11x faster                                         |
| regex_compile              | 148 ms                                                 | 134 ms: 1.10x faster                                          |
| pickle_pure_python         | 326 us                                                 | 296 us: 1.10x faster                                          |
| chaos                      | 67.5 ms                                                | 61.4 ms: 1.10x faster                                         |
| logging_format             | 7.10 us                                                | 6.47 us: 1.10x faster                                         |
| scimark_monte_carlo        | 74.6 ms                                                | 68.1 ms: 1.10x faster                                         |
| nqueens                    | 86.2 ms                                                | 79.0 ms: 1.09x faster                                         |
| async_tree_none            | 475 ms                                                 | 436 ms: 1.09x faster                                          |
| sympy_integrate            | 21.2 ms                                                | 19.5 ms: 1.09x faster                                         |
| sympy_str                  | 296 ms                                                 | 273 ms: 1.09x faster                                          |
| generators                 | 32.5 ms                                                | 30.2 ms: 1.07x faster                                         |
| logging_simple             | 6.38 us                                                | 5.97 us: 1.07x faster                                         |
| tomli_loads                | 2.30 sec                                               | 2.15 sec: 1.07x faster                                        |
| hexiom                     | 6.54 ms                                                | 6.14 ms: 1.07x faster                                         |
| unpickle_pure_python       | 230 us                                                 | 217 us: 1.06x faster                                          |
| tornado_http               | 101 ms                                                 | 95.1 ms: 1.06x faster                                         |
| docutils                   | 2.75 sec                                               | 2.61 sec: 1.06x faster                                        |
| scimark_fft                | 381 ms                                                 | 362 ms: 1.05x faster                                          |
| sympy_expand               | 476 ms                                                 | 453 ms: 1.05x faster                                          |
| chameleon                  | 7.41 ms                                                | 7.06 ms: 1.05x faster                                         |
| deepcopy_reduce            | 3.23 us                                                | 3.08 us: 1.05x faster                                         |
| nbody                      | 92.2 ms                                                | 88.0 ms: 1.05x faster                                         |
| sqlglot_parse              | 1.35 ms                                                | 1.29 ms: 1.05x faster                                         |
| asyncio_tcp                | 506 ms                                                 | 483 ms: 1.05x faster                                          |
| scimark_lu                 | 120 ms                                                 | 115 ms: 1.05x faster                                          |
| sqlglot_normalize          | 112 ms                                                 | 107 ms: 1.04x faster                                          |
| sqlglot_transpile          | 1.68 ms                                                | 1.61 ms: 1.04x faster                                         |
| deepcopy                   | 363 us                                                 | 348 us: 1.04x faster                                          |
| dulwich_log                | 68.7 ms                                                | 65.9 ms: 1.04x faster                                         |
| 2to3                       | 274 ms                                                 | 264 ms: 1.04x faster                                          |
| spectral_norm              | 115 ms                                                 | 110 ms: 1.04x faster                                          |
| deepcopy_memo              | 39.7 us                                                | 38.3 us: 1.04x faster                                         |
| bench_thread_pool          | 845 us                                                 | 815 us: 1.04x faster                                          |
| fannkuch                   | 410 ms                                                 | 396 ms: 1.03x faster                                          |
| scimark_sor                | 129 ms                                                 | 125 ms: 1.03x faster                                          |
| pprint_safe_repr           | 765 ms                                                 | 740 ms: 1.03x faster                                          |
| mypy2                      | 351 ms                                                 | 340 ms: 1.03x faster                                          |
| xml_etree_process          | 61.2 ms                                                | 59.4 ms: 1.03x faster                                         |
| coroutines                 | 23.5 ms                                                | 22.8 ms: 1.03x faster                                         |
| async_tree_memoization     | 580 ms                                                 | 565 ms: 1.03x faster                                          |
| pprint_pformat             | 1.55 sec                                               | 1.51 sec: 1.03x faster                                        |
| xml_etree_generate         | 88.7 ms                                                | 86.5 ms: 1.03x faster                                         |
| logging_silent             | 108 ns                                                 | 105 ns: 1.03x faster                                          |
| json                       | 5.22 ms                                                | 5.10 ms: 1.02x faster                                         |
| async_generators           | 459 ms                                                 | 449 ms: 1.02x faster                                          |
| json_loads                 | 28.4 us                                                | 27.9 us: 1.02x faster                                         |
| sqlglot_optimize           | 54.8 ms                                                | 53.9 ms: 1.02x faster                                         |
| sqlite_synth               | 2.83 us                                                | 2.79 us: 1.01x faster                                         |
| float                      | 83.3 ms                                                | 82.3 ms: 1.01x faster                                         |
| meteor_contest             | 110 ms                                                 | 109 ms: 1.01x faster                                          |
| mako                       | 11.5 ms                                                | 11.4 ms: 1.01x faster                                         |
| pyflate                    | 471 ms                                                 | 468 ms: 1.01x faster                                          |
| json_dumps                 | 10.6 ms                                                | 10.5 ms: 1.01x faster                                         |
| asyncio_tcp_ssl            | 1.78 sec                                               | 1.79 sec: 1.00x slower                                        |
| xml_etree_iterparse        | 106 ms                                                 | 107 ms: 1.01x slower                                          |
| xml_etree_parse            | 159 ms                                                 | 161 ms: 1.01x slower                                          |
| create_gc_cycles           | 1.45 ms                                                | 1.47 ms: 1.01x slower                                         |
| go                         | 140 ms                                                 | 143 ms: 1.02x slower                                          |
| async_tree_none_tg         | 447 ms                                                 | 456 ms: 1.02x slower                                          |
| unpickle_list              | 5.04 us                                                | 5.15 us: 1.02x slower                                         |
| async_tree_io              | 1.16 sec                                               | 1.19 sec: 1.02x slower                                        |
| pickle                     | 11.2 us                                                | 11.5 us: 1.03x slower                                         |
| regex_dna                  | 209 ms                                                 | 215 ms: 1.03x slower                                          |
| async_tree_cpu_io_mixed_tg | 725 ms                                                 | 750 ms: 1.03x slower                                          |
| pycparser                  | 1.17 sec                                               | 1.21 sec: 1.04x slower                                        |
| async_tree_io_tg           | 1.19 sec                                               | 1.23 sec: 1.04x slower                                        |
| pidigits                   | 187 ms                                                 | 195 ms: 1.04x slower                                          |
| richards                   | 46.0 ms                                                | 48.1 ms: 1.04x slower                                         |
| async_tree_memoization_tg  | 574 ms                                                 | 602 ms: 1.05x slower                                          |
| richards_super             | 51.9 ms                                                | 54.4 ms: 1.05x slower                                         |
| pickle_dict                | 33.5 us                                                | 35.2 us: 1.05x slower                                         |
| pickle_list                | 4.67 us                                                | 5.04 us: 1.08x slower                                         |
| python_startup             | 9.53 ms                                                | 10.3 ms: 1.08x slower                                         |
| regex_v8                   | 22.7 ms                                                | 25.8 ms: 1.14x slower                                         |
| telco                      | 7.18 ms                                                | 8.19 ms: 1.14x slower                                         |
| coverage                   | 75.1 ms                                                | 95.7 ms: 1.27x slower                                         |
| python_startup_no_site     | 6.92 ms                                                | 8.99 ms: 1.30x slower                                         |
| Geometric mean             | (ref)                                                  | 1.03x faster                                                  |

Benchmark hidden because not significant (7): async_tree_cpu_io_mixed, asyncio_websockets, regex_effbot, bench_mp_pool, mdp, pathlib, unpickle
Ignored benchmarks (6) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, dask, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 99.87% likely to be faster
- 90% likely to have a speedup of 1.01x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
