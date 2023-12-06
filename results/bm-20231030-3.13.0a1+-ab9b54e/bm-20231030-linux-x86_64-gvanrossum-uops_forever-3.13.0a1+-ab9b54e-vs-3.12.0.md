
# Results vs. 3.12.0

- fork: gvanrossum
- ref: uops_forever
- machine: linux-x86_64
- commit hash: ab9b54e
- commit date: 2023-10-30
- overall geometric mean: 1.04x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.01x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231030-linux-x86_64-gvanrossum-uops_forever-3.13.0a1+-ab9b54e |
|----------------|:------------------------------------------------------:|:------------------------------------------------------------------:|
| 2to3           | 274 ms                                                 | 290 ms: 1.06x slower                                               |
| chameleon      | 7.41 ms                                                | 7.46 ms: 1.01x slower                                              |
| tornado_http   | 101 ms                                                 | 102 ms: 1.02x slower                                               |
| Geometric mean | (ref)                                                  | 1.02x slower                                                       |

Benchmark hidden because not significant (1): docutils

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231030-linux-x86_64-gvanrossum-uops_forever-3.13.0a1+-ab9b54e |
|----------------------------|:------------------------------------------------------:|:------------------------------------------------------------------:|
| async_tree_none            | 475 ms                                                 | 457 ms: 1.04x faster                                               |
| async_tree_memoization     | 580 ms                                                 | 585 ms: 1.01x slower                                               |
| async_tree_cpu_io_mixed_tg | 725 ms                                                 | 751 ms: 1.04x slower                                               |
| async_tree_io              | 1.16 sec                                               | 1.21 sec: 1.04x slower                                             |
| async_tree_io_tg           | 1.19 sec                                               | 1.25 sec: 1.05x slower                                             |
| async_tree_none_tg         | 447 ms                                                 | 471 ms: 1.05x slower                                               |
| async_tree_memoization_tg  | 574 ms                                                 | 621 ms: 1.08x slower                                               |
| Geometric mean             | (ref)                                                  | 1.03x slower                                                       |

Benchmark hidden because not significant (1): async_tree_cpu_io_mixed

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231030-linux-x86_64-gvanrossum-uops_forever-3.13.0a1+-ab9b54e |
|----------------|:------------------------------------------------------:|:------------------------------------------------------------------:|
| pidigits       | 187 ms                                                 | 196 ms: 1.05x slower                                               |
| float          | 83.3 ms                                                | 95.9 ms: 1.15x slower                                              |
| nbody          | 92.2 ms                                                | 110 ms: 1.19x slower                                               |
| Geometric mean | (ref)                                                  | 1.13x slower                                                       |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231030-linux-x86_64-gvanrossum-uops_forever-3.13.0a1+-ab9b54e |
|----------------|:------------------------------------------------------:|:------------------------------------------------------------------:|
| regex_dna      | 209 ms                                                 | 215 ms: 1.03x slower                                               |
| regex_compile  | 148 ms                                                 | 162 ms: 1.09x slower                                               |
| regex_v8       | 22.7 ms                                                | 25.9 ms: 1.14x slower                                              |
| Geometric mean | (ref)                                                  | 1.07x slower                                                       |

Benchmark hidden because not significant (1): regex_effbot

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231030-linux-x86_64-gvanrossum-uops_forever-3.13.0a1+-ab9b54e |
|----------------------|:------------------------------------------------------:|:------------------------------------------------------------------:|
| unpickle             | 15.8 us                                                | 14.8 us: 1.06x faster                                              |
| pickle_pure_python   | 326 us                                                 | 312 us: 1.05x faster                                               |
| json_loads           | 28.4 us                                                | 27.6 us: 1.03x faster                                              |
| xml_etree_process    | 61.2 ms                                                | 60.0 ms: 1.02x faster                                              |
| xml_etree_generate   | 88.7 ms                                                | 87.7 ms: 1.01x faster                                              |
| unpickle_list        | 5.04 us                                                | 5.14 us: 1.02x slower                                              |
| unpickle_pure_python | 230 us                                                 | 240 us: 1.05x slower                                               |
| pickle_dict          | 33.5 us                                                | 35.1 us: 1.05x slower                                              |
| xml_etree_iterparse  | 106 ms                                                 | 111 ms: 1.05x slower                                               |
| tomli_loads          | 2.30 sec                                               | 2.46 sec: 1.07x slower                                             |
| pickle_list          | 4.67 us                                                | 5.02 us: 1.07x slower                                              |
| Geometric mean       | (ref)                                                  | 1.01x slower                                                       |

Benchmark hidden because not significant (3): pickle, xml_etree_parse, json_dumps

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231030-linux-x86_64-gvanrossum-uops_forever-3.13.0a1+-ab9b54e |
|------------------------|:------------------------------------------------------:|:------------------------------------------------------------------:|
| python_startup         | 9.53 ms                                                | 10.3 ms: 1.08x slower                                              |
| python_startup_no_site | 6.92 ms                                                | 9.00 ms: 1.30x slower                                              |
| Geometric mean         | (ref)                                                  | 1.19x slower                                                       |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231030-linux-x86_64-gvanrossum-uops_forever-3.13.0a1+-ab9b54e |
|-----------|:------------------------------------------------------:|:------------------------------------------------------------------:|
| mako      | 11.5 ms                                                | 13.2 ms: 1.15x slower                                              |

All benchmarks:
===============

| Benchmark                  | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231030-linux-x86_64-gvanrossum-uops_forever-3.13.0a1+-ab9b54e |
|----------------------------|:------------------------------------------------------:|:------------------------------------------------------------------:|
| gc_traversal               | 4.28 ms                                                | 3.50 ms: 1.22x faster                                              |
| unpack_sequence            | 54.2 ns                                                | 45.0 ns: 1.20x faster                                              |
| generators                 | 32.5 ms                                                | 30.4 ms: 1.07x faster                                              |
| sympy_sum                  | 167 ms                                                 | 157 ms: 1.06x faster                                               |
| unpickle                   | 15.8 us                                                | 14.8 us: 1.06x faster                                              |
| asyncio_tcp                | 506 ms                                                 | 477 ms: 1.06x faster                                               |
| pickle_pure_python         | 326 us                                                 | 312 us: 1.05x faster                                               |
| async_tree_none            | 475 ms                                                 | 457 ms: 1.04x faster                                               |
| sqlglot_normalize          | 112 ms                                                 | 108 ms: 1.04x faster                                               |
| sympy_str                  | 296 ms                                                 | 287 ms: 1.03x faster                                               |
| json_loads                 | 28.4 us                                                | 27.6 us: 1.03x faster                                              |
| coroutines                 | 23.5 ms                                                | 22.8 ms: 1.03x faster                                              |
| deepcopy_reduce            | 3.23 us                                                | 3.15 us: 1.02x faster                                              |
| xml_etree_process          | 61.2 ms                                                | 60.0 ms: 1.02x faster                                              |
| json                       | 5.22 ms                                                | 5.14 ms: 1.02x faster                                              |
| logging_silent             | 108 ns                                                 | 106 ns: 1.01x faster                                               |
| xml_etree_generate         | 88.7 ms                                                | 87.7 ms: 1.01x faster                                              |
| sqlglot_parse              | 1.35 ms                                                | 1.34 ms: 1.01x faster                                              |
| scimark_sor                | 129 ms                                                 | 128 ms: 1.01x faster                                               |
| deepcopy                   | 363 us                                                 | 360 us: 1.01x faster                                               |
| raytrace                   | 308 ms                                                 | 309 ms: 1.00x slower                                               |
| crypto_pyaes               | 83.6 ms                                                | 83.9 ms: 1.00x slower                                              |
| bench_thread_pool          | 845 us                                                 | 849 us: 1.00x slower                                               |
| chameleon                  | 7.41 ms                                                | 7.46 ms: 1.01x slower                                              |
| sqlite_synth               | 2.83 us                                                | 2.86 us: 1.01x slower                                              |
| sqlglot_optimize           | 54.8 ms                                                | 55.2 ms: 1.01x slower                                              |
| asyncio_tcp_ssl            | 1.78 sec                                               | 1.80 sec: 1.01x slower                                             |
| async_tree_memoization     | 580 ms                                                 | 585 ms: 1.01x slower                                               |
| spectral_norm              | 115 ms                                                 | 116 ms: 1.01x slower                                               |
| sympy_integrate            | 21.2 ms                                                | 21.5 ms: 1.01x slower                                              |
| dulwich_log                | 68.7 ms                                                | 69.7 ms: 1.01x slower                                              |
| mypy2                      | 351 ms                                                 | 357 ms: 1.02x slower                                               |
| sympy_expand               | 476 ms                                                 | 484 ms: 1.02x slower                                               |
| tornado_http               | 101 ms                                                 | 102 ms: 1.02x slower                                               |
| unpickle_list              | 5.04 us                                                | 5.14 us: 1.02x slower                                              |
| logging_format             | 7.10 us                                                | 7.29 us: 1.03x slower                                              |
| regex_dna                  | 209 ms                                                 | 215 ms: 1.03x slower                                               |
| scimark_monte_carlo        | 74.6 ms                                                | 77.1 ms: 1.03x slower                                              |
| async_tree_cpu_io_mixed_tg | 725 ms                                                 | 751 ms: 1.04x slower                                               |
| typing_runtime_protocols   | 153 us                                                 | 159 us: 1.04x slower                                               |
| async_tree_io              | 1.16 sec                                               | 1.21 sec: 1.04x slower                                             |
| async_generators           | 459 ms                                                 | 479 ms: 1.04x slower                                               |
| pathlib                    | 18.9 ms                                                | 19.8 ms: 1.05x slower                                              |
| pidigits                   | 187 ms                                                 | 196 ms: 1.05x slower                                               |
| unpickle_pure_python       | 230 us                                                 | 240 us: 1.05x slower                                               |
| meteor_contest             | 110 ms                                                 | 115 ms: 1.05x slower                                               |
| pickle_dict                | 33.5 us                                                | 35.1 us: 1.05x slower                                              |
| async_tree_io_tg           | 1.19 sec                                               | 1.25 sec: 1.05x slower                                             |
| async_tree_none_tg         | 447 ms                                                 | 471 ms: 1.05x slower                                               |
| xml_etree_iterparse        | 106 ms                                                 | 111 ms: 1.05x slower                                               |
| 2to3                       | 274 ms                                                 | 290 ms: 1.06x slower                                               |
| pprint_safe_repr           | 765 ms                                                 | 810 ms: 1.06x slower                                               |
| comprehensions             | 20.9 us                                                | 22.2 us: 1.06x slower                                              |
| tomli_loads                | 2.30 sec                                               | 2.46 sec: 1.07x slower                                             |
| pycparser                  | 1.17 sec                                               | 1.26 sec: 1.07x slower                                             |
| pickle_list                | 4.67 us                                                | 5.02 us: 1.07x slower                                              |
| deepcopy_memo              | 39.7 us                                                | 42.8 us: 1.08x slower                                              |
| pprint_pformat             | 1.55 sec                                               | 1.67 sec: 1.08x slower                                             |
| async_tree_memoization_tg  | 574 ms                                                 | 621 ms: 1.08x slower                                               |
| python_startup             | 9.53 ms                                                | 10.3 ms: 1.08x slower                                              |
| regex_compile              | 148 ms                                                 | 162 ms: 1.09x slower                                               |
| richards                   | 46.0 ms                                                | 50.5 ms: 1.10x slower                                              |
| richards_super             | 51.9 ms                                                | 57.0 ms: 1.10x slower                                              |
| scimark_sparse_mat_mult    | 5.33 ms                                                | 5.88 ms: 1.10x slower                                              |
| fannkuch                   | 410 ms                                                 | 455 ms: 1.11x slower                                               |
| chaos                      | 67.5 ms                                                | 75.0 ms: 1.11x slower                                              |
| pyflate                    | 471 ms                                                 | 528 ms: 1.12x slower                                               |
| mdp                        | 2.57 sec                                               | 2.88 sec: 1.12x slower                                             |
| nqueens                    | 86.2 ms                                                | 98.3 ms: 1.14x slower                                              |
| regex_v8                   | 22.7 ms                                                | 25.9 ms: 1.14x slower                                              |
| float                      | 83.3 ms                                                | 95.9 ms: 1.15x slower                                              |
| mako                       | 11.5 ms                                                | 13.2 ms: 1.15x slower                                              |
| scimark_fft                | 381 ms                                                 | 439 ms: 1.15x slower                                               |
| go                         | 140 ms                                                 | 166 ms: 1.18x slower                                               |
| telco                      | 7.18 ms                                                | 8.53 ms: 1.19x slower                                              |
| nbody                      | 92.2 ms                                                | 110 ms: 1.19x slower                                               |
| deltablue                  | 3.71 ms                                                | 4.61 ms: 1.24x slower                                              |
| coverage                   | 75.1 ms                                                | 94.2 ms: 1.25x slower                                              |
| python_startup_no_site     | 6.92 ms                                                | 9.00 ms: 1.30x slower                                              |
| hexiom                     | 6.54 ms                                                | 8.84 ms: 1.35x slower                                              |
| Geometric mean             | (ref)                                                  | 1.04x slower                                                       |

Benchmark hidden because not significant (12): logging_simple, sqlglot_transpile, pickle, xml_etree_parse, json_dumps, create_gc_cycles, asyncio_websockets, bench_mp_pool, async_tree_cpu_io_mixed, regex_effbot, docutils, scimark_lu
Ignored benchmarks (6) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, dask, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.02x
- 95% likely to have a slowdown of 1.02x
- 99% likely to have a slowdown of 1.01x
