
# Results vs. 3.12.0

- fork: mdboom
- ref: measure_biased_ref_c
- machine: linux-x86_64
- commit hash: bbb758f
- commit date: 2023-10-31
- overall geometric mean: 1.08x slower \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.03x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231031-linux-x86_64-mdboom-measure_biased_ref_c-3.13.0a1+-bbb758f |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| 2to3           | 274 ms                                                 | 285 ms: 1.04x slower                                                   |
| chameleon      | 7.41 ms                                                | 7.47 ms: 1.01x slower                                                  |
| docutils       | 2.75 sec                                               | 2.83 sec: 1.03x slower                                                 |
| tornado_http   | 101 ms                                                 | 106 ms: 1.06x slower                                                   |
| Geometric mean | (ref)                                                  | 1.03x slower                                                           |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231031-linux-x86_64-mdboom-measure_biased_ref_c-3.13.0a1+-bbb758f |
|----------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| async_tree_none            | 475 ms                                                 | 493 ms: 1.04x slower                                                   |
| async_tree_cpu_io_mixed    | 724 ms                                                 | 780 ms: 1.08x slower                                                   |
| async_tree_memoization     | 580 ms                                                 | 634 ms: 1.09x slower                                                   |
| async_tree_cpu_io_mixed_tg | 725 ms                                                 | 823 ms: 1.14x slower                                                   |
| async_tree_io              | 1.16 sec                                               | 1.36 sec: 1.17x slower                                                 |
| async_tree_none_tg         | 447 ms                                                 | 527 ms: 1.18x slower                                                   |
| async_tree_memoization_tg  | 574 ms                                                 | 678 ms: 1.18x slower                                                   |
| async_tree_io_tg           | 1.19 sec                                               | 1.42 sec: 1.20x slower                                                 |
| Geometric mean             | (ref)                                                  | 1.13x slower                                                           |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231031-linux-x86_64-mdboom-measure_biased_ref_c-3.13.0a1+-bbb758f |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| pidigits       | 187 ms                                                 | 188 ms: 1.00x slower                                                   |
| float          | 83.3 ms                                                | 90.6 ms: 1.09x slower                                                  |
| nbody          | 92.2 ms                                                | 111 ms: 1.20x slower                                                   |
| Geometric mean | (ref)                                                  | 1.09x slower                                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231031-linux-x86_64-mdboom-measure_biased_ref_c-3.13.0a1+-bbb758f |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| regex_effbot   | 3.57 ms                                                | 3.48 ms: 1.03x faster                                                  |
| regex_compile  | 148 ms                                                 | 149 ms: 1.00x slower                                                   |
| regex_v8       | 22.7 ms                                                | 25.2 ms: 1.11x slower                                                  |
| Geometric mean | (ref)                                                  | 1.02x slower                                                           |

Benchmark hidden because not significant (1): regex_dna

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231031-linux-x86_64-mdboom-measure_biased_ref_c-3.13.0a1+-bbb758f |
|----------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| pickle_dict          | 33.5 us                                                | 31.6 us: 1.06x faster                                                  |
| unpickle             | 15.8 us                                                | 15.5 us: 1.02x faster                                                  |
| tomli_loads          | 2.30 sec                                               | 2.31 sec: 1.01x slower                                                 |
| pickle_pure_python   | 326 us                                                 | 333 us: 1.02x slower                                                   |
| pickle               | 11.2 us                                                | 11.5 us: 1.02x slower                                                  |
| xml_etree_generate   | 88.7 ms                                                | 93.6 ms: 1.05x slower                                                  |
| xml_etree_process    | 61.2 ms                                                | 64.6 ms: 1.06x slower                                                  |
| pickle_list          | 4.67 us                                                | 4.94 us: 1.06x slower                                                  |
| unpickle_pure_python | 230 us                                                 | 243 us: 1.06x slower                                                   |
| xml_etree_iterparse  | 106 ms                                                 | 112 ms: 1.06x slower                                                   |
| unpickle_list        | 5.04 us                                                | 5.36 us: 1.06x slower                                                  |
| json_dumps           | 10.6 ms                                                | 11.2 ms: 1.06x slower                                                  |
| xml_etree_parse      | 159 ms                                                 | 170 ms: 1.07x slower                                                   |
| json_loads           | 28.4 us                                                | 30.8 us: 1.09x slower                                                  |
| Geometric mean       | (ref)                                                  | 1.04x slower                                                           |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231031-linux-x86_64-mdboom-measure_biased_ref_c-3.13.0a1+-bbb758f |
|------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| python_startup         | 9.53 ms                                                | 10.8 ms: 1.14x slower                                                  |
| python_startup_no_site | 6.92 ms                                                | 9.31 ms: 1.35x slower                                                  |
| Geometric mean         | (ref)                                                  | 1.24x slower                                                           |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231031-linux-x86_64-mdboom-measure_biased_ref_c-3.13.0a1+-bbb758f |
|-----------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| mako      | 11.5 ms                                                | 12.7 ms: 1.10x slower                                                  |

All benchmarks:
===============

| Benchmark                  | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231031-linux-x86_64-mdboom-measure_biased_ref_c-3.13.0a1+-bbb758f |
|----------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| comprehensions             | 20.9 us                                                | 17.6 us: 1.19x faster                                                  |
| gc_traversal               | 4.28 ms                                                | 3.62 ms: 1.18x faster                                                  |
| generators                 | 32.5 ms                                                | 30.2 ms: 1.08x faster                                                  |
| unpack_sequence            | 54.2 ns                                                | 50.7 ns: 1.07x faster                                                  |
| pickle_dict                | 33.5 us                                                | 31.6 us: 1.06x faster                                                  |
| crypto_pyaes               | 83.6 ms                                                | 79.3 ms: 1.05x faster                                                  |
| asyncio_tcp                | 506 ms                                                 | 484 ms: 1.04x faster                                                   |
| sympy_sum                  | 167 ms                                                 | 161 ms: 1.04x faster                                                   |
| regex_effbot               | 3.57 ms                                                | 3.48 ms: 1.03x faster                                                  |
| logging_format             | 7.10 us                                                | 6.92 us: 1.02x faster                                                  |
| unpickle                   | 15.8 us                                                | 15.5 us: 1.02x faster                                                  |
| sympy_str                  | 296 ms                                                 | 291 ms: 1.02x faster                                                   |
| deltablue                  | 3.71 ms                                                | 3.65 ms: 1.02x faster                                                  |
| logging_simple             | 6.38 us                                                | 6.32 us: 1.01x faster                                                  |
| regex_compile              | 148 ms                                                 | 149 ms: 1.00x slower                                                   |
| sympy_integrate            | 21.2 ms                                                | 21.3 ms: 1.00x slower                                                  |
| raytrace                   | 308 ms                                                 | 309 ms: 1.00x slower                                                   |
| pidigits                   | 187 ms                                                 | 188 ms: 1.00x slower                                                   |
| create_gc_cycles           | 1.45 ms                                                | 1.46 ms: 1.01x slower                                                  |
| tomli_loads                | 2.30 sec                                               | 2.31 sec: 1.01x slower                                                 |
| chameleon                  | 7.41 ms                                                | 7.47 ms: 1.01x slower                                                  |
| nqueens                    | 86.2 ms                                                | 87.0 ms: 1.01x slower                                                  |
| asyncio_websockets         | 552 ms                                                 | 559 ms: 1.01x slower                                                   |
| chaos                      | 67.5 ms                                                | 68.3 ms: 1.01x slower                                                  |
| sympy_expand               | 476 ms                                                 | 484 ms: 1.02x slower                                                   |
| pickle_pure_python         | 326 us                                                 | 333 us: 1.02x slower                                                   |
| dulwich_log                | 68.7 ms                                                | 70.2 ms: 1.02x slower                                                  |
| scimark_lu                 | 120 ms                                                 | 123 ms: 1.02x slower                                                   |
| pickle                     | 11.2 us                                                | 11.5 us: 1.02x slower                                                  |
| typing_runtime_protocols   | 153 us                                                 | 157 us: 1.02x slower                                                   |
| docutils                   | 2.75 sec                                               | 2.83 sec: 1.03x slower                                                 |
| sqlglot_parse              | 1.35 ms                                                | 1.39 ms: 1.03x slower                                                  |
| sqlglot_transpile          | 1.68 ms                                                | 1.73 ms: 1.03x slower                                                  |
| sqlglot_normalize          | 112 ms                                                 | 115 ms: 1.03x slower                                                   |
| async_tree_none            | 475 ms                                                 | 493 ms: 1.04x slower                                                   |
| 2to3                       | 274 ms                                                 | 285 ms: 1.04x slower                                                   |
| scimark_monte_carlo        | 74.6 ms                                                | 77.5 ms: 1.04x slower                                                  |
| hexiom                     | 6.54 ms                                                | 6.80 ms: 1.04x slower                                                  |
| coroutines                 | 23.5 ms                                                | 24.4 ms: 1.04x slower                                                  |
| meteor_contest             | 110 ms                                                 | 114 ms: 1.04x slower                                                   |
| deepcopy                   | 363 us                                                 | 378 us: 1.04x slower                                                   |
| pprint_safe_repr           | 765 ms                                                 | 800 ms: 1.05x slower                                                   |
| deepcopy_reduce            | 3.23 us                                                | 3.39 us: 1.05x slower                                                  |
| pprint_pformat             | 1.55 sec                                               | 1.63 sec: 1.05x slower                                                 |
| deepcopy_memo              | 39.7 us                                                | 41.9 us: 1.05x slower                                                  |
| logging_silent             | 108 ns                                                 | 113 ns: 1.05x slower                                                   |
| xml_etree_generate         | 88.7 ms                                                | 93.6 ms: 1.05x slower                                                  |
| xml_etree_process          | 61.2 ms                                                | 64.6 ms: 1.06x slower                                                  |
| pickle_list                | 4.67 us                                                | 4.94 us: 1.06x slower                                                  |
| unpickle_pure_python       | 230 us                                                 | 243 us: 1.06x slower                                                   |
| tornado_http               | 101 ms                                                 | 106 ms: 1.06x slower                                                   |
| sqlglot_optimize           | 54.8 ms                                                | 58.0 ms: 1.06x slower                                                  |
| mdp                        | 2.57 sec                                               | 2.72 sec: 1.06x slower                                                 |
| pycparser                  | 1.17 sec                                               | 1.24 sec: 1.06x slower                                                 |
| xml_etree_iterparse        | 106 ms                                                 | 112 ms: 1.06x slower                                                   |
| unpickle_list              | 5.04 us                                                | 5.36 us: 1.06x slower                                                  |
| pathlib                    | 18.9 ms                                                | 20.1 ms: 1.06x slower                                                  |
| scimark_sor                | 129 ms                                                 | 137 ms: 1.06x slower                                                   |
| json_dumps                 | 10.6 ms                                                | 11.2 ms: 1.06x slower                                                  |
| scimark_fft                | 381 ms                                                 | 405 ms: 1.06x slower                                                   |
| pyflate                    | 471 ms                                                 | 503 ms: 1.07x slower                                                   |
| xml_etree_parse            | 159 ms                                                 | 170 ms: 1.07x slower                                                   |
| async_generators           | 459 ms                                                 | 492 ms: 1.07x slower                                                   |
| async_tree_cpu_io_mixed    | 724 ms                                                 | 780 ms: 1.08x slower                                                   |
| json                       | 5.22 ms                                                | 5.64 ms: 1.08x slower                                                  |
| json_loads                 | 28.4 us                                                | 30.8 us: 1.09x slower                                                  |
| float                      | 83.3 ms                                                | 90.6 ms: 1.09x slower                                                  |
| async_tree_memoization     | 580 ms                                                 | 634 ms: 1.09x slower                                                   |
| go                         | 140 ms                                                 | 154 ms: 1.10x slower                                                   |
| sqlite_synth               | 2.83 us                                                | 3.11 us: 1.10x slower                                                  |
| richards_super             | 51.9 ms                                                | 57.0 ms: 1.10x slower                                                  |
| mako                       | 11.5 ms                                                | 12.7 ms: 1.10x slower                                                  |
| spectral_norm              | 115 ms                                                 | 127 ms: 1.11x slower                                                   |
| richards                   | 46.0 ms                                                | 51.0 ms: 1.11x slower                                                  |
| regex_v8                   | 22.7 ms                                                | 25.2 ms: 1.11x slower                                                  |
| fannkuch                   | 410 ms                                                 | 457 ms: 1.11x slower                                                   |
| async_tree_cpu_io_mixed_tg | 725 ms                                                 | 823 ms: 1.14x slower                                                   |
| python_startup             | 9.53 ms                                                | 10.8 ms: 1.14x slower                                                  |
| async_tree_io              | 1.16 sec                                               | 1.36 sec: 1.17x slower                                                 |
| async_tree_none_tg         | 447 ms                                                 | 527 ms: 1.18x slower                                                   |
| async_tree_memoization_tg  | 574 ms                                                 | 678 ms: 1.18x slower                                                   |
| async_tree_io_tg           | 1.19 sec                                               | 1.42 sec: 1.20x slower                                                 |
| nbody                      | 92.2 ms                                                | 111 ms: 1.20x slower                                                   |
| bench_thread_pool          | 845 us                                                 | 1.04 ms: 1.23x slower                                                  |
| telco                      | 7.18 ms                                                | 9.04 ms: 1.26x slower                                                  |
| python_startup_no_site     | 6.92 ms                                                | 9.31 ms: 1.35x slower                                                  |
| mypy2                      | 351 ms                                                 | 500 ms: 1.43x slower                                                   |
| coverage                   | 75.1 ms                                                | 723 ms: 9.63x slower                                                   |
| Geometric mean             | (ref)                                                  | 1.08x slower                                                           |

Benchmark hidden because not significant (4): bench_mp_pool, regex_dna, asyncio_tcp_ssl, scimark_sparse_mat_mult
Ignored benchmarks (6) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, dask, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.04x
- 95% likely to have a slowdown of 1.03x
- 99% likely to have a slowdown of 1.03x
