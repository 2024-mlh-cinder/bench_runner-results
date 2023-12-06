
# Results vs. 3.12.0

- fork: python
- ref: main
- machine: linux-x86_64
- commit hash: ce6a533
- commit date: 2023-11-12
- overall geometric mean: 1.07x slower \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.02x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231112-linux-x86_64-python-main-3.13.0a1+-ce6a533 |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| 2to3           | 274 ms                                                 | 295 ms: 1.08x slower                                   |
| chameleon      | 7.41 ms                                                | 7.58 ms: 1.02x slower                                  |
| docutils       | 2.75 sec                                               | 2.73 sec: 1.01x faster                                 |
| tornado_http   | 101 ms                                                 | 102 ms: 1.02x slower                                   |
| Geometric mean | (ref)                                                  | 1.03x slower                                           |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231112-linux-x86_64-python-main-3.13.0a1+-ce6a533 |
|----------------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| async_tree_none            | 475 ms                                                 | 467 ms: 1.02x faster                                   |
| async_tree_cpu_io_mixed    | 724 ms                                                 | 746 ms: 1.03x slower                                   |
| async_tree_memoization     | 580 ms                                                 | 598 ms: 1.03x slower                                   |
| async_tree_io              | 1.16 sec                                               | 1.23 sec: 1.06x slower                                 |
| async_tree_cpu_io_mixed_tg | 725 ms                                                 | 773 ms: 1.07x slower                                   |
| async_tree_io_tg           | 1.19 sec                                               | 1.27 sec: 1.07x slower                                 |
| async_tree_memoization_tg  | 574 ms                                                 | 614 ms: 1.07x slower                                   |
| async_tree_none_tg         | 447 ms                                                 | 479 ms: 1.07x slower                                   |
| Geometric mean             | (ref)                                                  | 1.05x slower                                           |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231112-linux-x86_64-python-main-3.13.0a1+-ce6a533 |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| pidigits       | 187 ms                                                 | 197 ms: 1.05x slower                                   |
| float          | 83.3 ms                                                | 112 ms: 1.34x slower                                   |
| nbody          | 92.2 ms                                                | 132 ms: 1.43x slower                                   |
| Geometric mean | (ref)                                                  | 1.26x slower                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231112-linux-x86_64-python-main-3.13.0a1+-ce6a533 |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| regex_effbot   | 3.57 ms                                                | 3.78 ms: 1.06x slower                                  |
| regex_dna      | 209 ms                                                 | 223 ms: 1.07x slower                                   |
| regex_compile  | 148 ms                                                 | 166 ms: 1.12x slower                                   |
| regex_v8       | 22.7 ms                                                | 26.1 ms: 1.15x slower                                  |
| Geometric mean | (ref)                                                  | 1.10x slower                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231112-linux-x86_64-python-main-3.13.0a1+-ce6a533 |
|----------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| unpickle             | 15.8 us                                                | 14.8 us: 1.07x faster                                  |
| pickle_pure_python   | 326 us                                                 | 310 us: 1.05x faster                                   |
| json_loads           | 28.4 us                                                | 27.8 us: 1.02x faster                                  |
| xml_etree_process    | 61.2 ms                                                | 59.9 ms: 1.02x faster                                  |
| unpickle_list        | 5.04 us                                                | 4.98 us: 1.01x faster                                  |
| xml_etree_generate   | 88.7 ms                                                | 87.8 ms: 1.01x faster                                  |
| xml_etree_parse      | 159 ms                                                 | 158 ms: 1.01x faster                                   |
| json_dumps           | 10.6 ms                                                | 10.7 ms: 1.01x slower                                  |
| pickle_dict          | 33.5 us                                                | 34.6 us: 1.03x slower                                  |
| pickle               | 11.2 us                                                | 11.6 us: 1.03x slower                                  |
| pickle_list          | 4.67 us                                                | 4.84 us: 1.04x slower                                  |
| xml_etree_iterparse  | 106 ms                                                 | 114 ms: 1.08x slower                                   |
| unpickle_pure_python | 230 us                                                 | 247 us: 1.08x slower                                   |
| tomli_loads          | 2.30 sec                                               | 3.17 sec: 1.38x slower                                 |
| Geometric mean       | (ref)                                                  | 1.03x slower                                           |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231112-linux-x86_64-python-main-3.13.0a1+-ce6a533 |
|------------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| python_startup         | 9.53 ms                                                | 10.4 ms: 1.09x slower                                  |
| python_startup_no_site | 6.92 ms                                                | 9.08 ms: 1.31x slower                                  |
| Geometric mean         | (ref)                                                  | 1.20x slower                                           |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231112-linux-x86_64-python-main-3.13.0a1+-ce6a533 |
|-----------|:------------------------------------------------------:|:------------------------------------------------------:|
| mako      | 11.5 ms                                                | 15.8 ms: 1.38x slower                                  |

All benchmarks:
===============

| Benchmark                  | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231112-linux-x86_64-python-main-3.13.0a1+-ce6a533 |
|----------------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| typing_runtime_protocols   | 153 us                                                 | 126 us: 1.21x faster                                   |
| gc_traversal               | 4.28 ms                                                | 3.80 ms: 1.13x faster                                  |
| generators                 | 32.5 ms                                                | 29.6 ms: 1.10x faster                                  |
| coroutines                 | 23.5 ms                                                | 21.6 ms: 1.08x faster                                  |
| sympy_sum                  | 167 ms                                                 | 155 ms: 1.08x faster                                   |
| unpack_sequence            | 54.2 ns                                                | 50.5 ns: 1.07x faster                                  |
| unpickle                   | 15.8 us                                                | 14.8 us: 1.07x faster                                  |
| pickle_pure_python         | 326 us                                                 | 310 us: 1.05x faster                                   |
| sqlglot_normalize          | 112 ms                                                 | 109 ms: 1.03x faster                                   |
| asyncio_tcp                | 506 ms                                                 | 493 ms: 1.03x faster                                   |
| json_loads                 | 28.4 us                                                | 27.8 us: 1.02x faster                                  |
| xml_etree_process          | 61.2 ms                                                | 59.9 ms: 1.02x faster                                  |
| deepcopy_reduce            | 3.23 us                                                | 3.16 us: 1.02x faster                                  |
| async_tree_none            | 475 ms                                                 | 467 ms: 1.02x faster                                   |
| spectral_norm              | 115 ms                                                 | 113 ms: 1.02x faster                                   |
| sympy_str                  | 296 ms                                                 | 292 ms: 1.01x faster                                   |
| unpickle_list              | 5.04 us                                                | 4.98 us: 1.01x faster                                  |
| deepcopy                   | 363 us                                                 | 358 us: 1.01x faster                                   |
| xml_etree_generate         | 88.7 ms                                                | 87.8 ms: 1.01x faster                                  |
| docutils                   | 2.75 sec                                               | 2.73 sec: 1.01x faster                                 |
| logging_simple             | 6.38 us                                                | 6.33 us: 1.01x faster                                  |
| xml_etree_parse            | 159 ms                                                 | 158 ms: 1.01x faster                                   |
| async_generators           | 459 ms                                                 | 457 ms: 1.01x faster                                   |
| sqlglot_parse              | 1.35 ms                                                | 1.35 ms: 1.00x slower                                  |
| sqlglot_optimize           | 54.8 ms                                                | 55.0 ms: 1.00x slower                                  |
| logging_format             | 7.10 us                                                | 7.15 us: 1.01x slower                                  |
| json_dumps                 | 10.6 ms                                                | 10.7 ms: 1.01x slower                                  |
| dulwich_log                | 68.7 ms                                                | 69.5 ms: 1.01x slower                                  |
| raytrace                   | 308 ms                                                 | 312 ms: 1.01x slower                                   |
| asyncio_tcp_ssl            | 1.78 sec                                               | 1.81 sec: 1.02x slower                                 |
| bench_thread_pool          | 845 us                                                 | 859 us: 1.02x slower                                   |
| logging_silent             | 108 ns                                                 | 109 ns: 1.02x slower                                   |
| tornado_http               | 101 ms                                                 | 102 ms: 1.02x slower                                   |
| mypy2                      | 351 ms                                                 | 357 ms: 1.02x slower                                   |
| sympy_integrate            | 21.2 ms                                                | 21.7 ms: 1.02x slower                                  |
| create_gc_cycles           | 1.45 ms                                                | 1.48 ms: 1.02x slower                                  |
| chameleon                  | 7.41 ms                                                | 7.58 ms: 1.02x slower                                  |
| sympy_expand               | 476 ms                                                 | 487 ms: 1.02x slower                                   |
| sqlite_synth               | 2.83 us                                                | 2.91 us: 1.03x slower                                  |
| async_tree_cpu_io_mixed    | 724 ms                                                 | 746 ms: 1.03x slower                                   |
| async_tree_memoization     | 580 ms                                                 | 598 ms: 1.03x slower                                   |
| pickle_dict                | 33.5 us                                                | 34.6 us: 1.03x slower                                  |
| pickle                     | 11.2 us                                                | 11.6 us: 1.03x slower                                  |
| pickle_list                | 4.67 us                                                | 4.84 us: 1.04x slower                                  |
| scimark_sor                | 129 ms                                                 | 134 ms: 1.04x slower                                   |
| pidigits                   | 187 ms                                                 | 197 ms: 1.05x slower                                   |
| crypto_pyaes               | 83.6 ms                                                | 87.8 ms: 1.05x slower                                  |
| pathlib                    | 18.9 ms                                                | 20.0 ms: 1.06x slower                                  |
| regex_effbot               | 3.57 ms                                                | 3.78 ms: 1.06x slower                                  |
| async_tree_io              | 1.16 sec                                               | 1.23 sec: 1.06x slower                                 |
| async_tree_cpu_io_mixed_tg | 725 ms                                                 | 773 ms: 1.07x slower                                   |
| mdp                        | 2.57 sec                                               | 2.74 sec: 1.07x slower                                 |
| async_tree_io_tg           | 1.19 sec                                               | 1.27 sec: 1.07x slower                                 |
| async_tree_memoization_tg  | 574 ms                                                 | 614 ms: 1.07x slower                                   |
| regex_dna                  | 209 ms                                                 | 223 ms: 1.07x slower                                   |
| async_tree_none_tg         | 447 ms                                                 | 479 ms: 1.07x slower                                   |
| deepcopy_memo              | 39.7 us                                                | 42.6 us: 1.07x slower                                  |
| xml_etree_iterparse        | 106 ms                                                 | 114 ms: 1.08x slower                                   |
| unpickle_pure_python       | 230 us                                                 | 247 us: 1.08x slower                                   |
| 2to3                       | 274 ms                                                 | 295 ms: 1.08x slower                                   |
| pprint_safe_repr           | 765 ms                                                 | 832 ms: 1.09x slower                                   |
| python_startup             | 9.53 ms                                                | 10.4 ms: 1.09x slower                                  |
| meteor_contest             | 110 ms                                                 | 120 ms: 1.09x slower                                   |
| pycparser                  | 1.17 sec                                               | 1.28 sec: 1.10x slower                                 |
| pprint_pformat             | 1.55 sec                                               | 1.71 sec: 1.10x slower                                 |
| scimark_monte_carlo        | 74.6 ms                                                | 83.3 ms: 1.12x slower                                  |
| regex_compile              | 148 ms                                                 | 166 ms: 1.12x slower                                   |
| chaos                      | 67.5 ms                                                | 76.2 ms: 1.13x slower                                  |
| richards                   | 46.0 ms                                                | 52.8 ms: 1.15x slower                                  |
| regex_v8                   | 22.7 ms                                                | 26.1 ms: 1.15x slower                                  |
| richards_super             | 51.9 ms                                                | 60.5 ms: 1.17x slower                                  |
| scimark_fft                | 381 ms                                                 | 460 ms: 1.21x slower                                   |
| pyflate                    | 471 ms                                                 | 574 ms: 1.22x slower                                   |
| go                         | 140 ms                                                 | 172 ms: 1.23x slower                                   |
| telco                      | 7.18 ms                                                | 8.89 ms: 1.24x slower                                  |
| comprehensions             | 20.9 us                                                | 26.7 us: 1.27x slower                                  |
| coverage                   | 75.1 ms                                                | 96.6 ms: 1.29x slower                                  |
| scimark_sparse_mat_mult    | 5.33 ms                                                | 6.93 ms: 1.30x slower                                  |
| python_startup_no_site     | 6.92 ms                                                | 9.08 ms: 1.31x slower                                  |
| nqueens                    | 86.2 ms                                                | 114 ms: 1.32x slower                                   |
| float                      | 83.3 ms                                                | 112 ms: 1.34x slower                                   |
| fannkuch                   | 410 ms                                                 | 554 ms: 1.35x slower                                   |
| tomli_loads                | 2.30 sec                                               | 3.17 sec: 1.38x slower                                 |
| mako                       | 11.5 ms                                                | 15.8 ms: 1.38x slower                                  |
| nbody                      | 92.2 ms                                                | 132 ms: 1.43x slower                                   |
| deltablue                  | 3.71 ms                                                | 5.43 ms: 1.46x slower                                  |
| hexiom                     | 6.54 ms                                                | 10.9 ms: 1.67x slower                                  |
| Geometric mean             | (ref)                                                  | 1.07x slower                                           |

Benchmark hidden because not significant (5): json, scimark_lu, asyncio_websockets, bench_mp_pool, sqlglot_transpile
Ignored benchmarks (6) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, dask, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.04x
- 95% likely to have a slowdown of 1.03x
- 99% likely to have a slowdown of 1.02x
