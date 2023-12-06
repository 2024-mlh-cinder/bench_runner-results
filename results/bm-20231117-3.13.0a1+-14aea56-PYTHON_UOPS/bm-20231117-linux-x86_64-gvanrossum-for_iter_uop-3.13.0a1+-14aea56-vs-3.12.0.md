
# Results vs. 3.12.0

- fork: gvanrossum
- ref: for_iter_uop
- machine: linux-x86_64
- commit hash: 14aea56
- commit date: 2023-11-17
- overall geometric mean: 1.12x slower \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.06x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231117-linux-x86_64-gvanrossum-for_iter_uop-3.13.0a1+-14aea56 |
|----------------|:------------------------------------------------------:|:------------------------------------------------------------------:|
| 2to3           | 274 ms                                                 | 301 ms: 1.10x slower                                               |
| chameleon      | 7.41 ms                                                | 7.84 ms: 1.06x slower                                              |
| docutils       | 2.75 sec                                               | 2.79 sec: 1.01x slower                                             |
| tornado_http   | 101 ms                                                 | 104 ms: 1.03x slower                                               |
| Geometric mean | (ref)                                                  | 1.05x slower                                                       |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231117-linux-x86_64-gvanrossum-for_iter_uop-3.13.0a1+-14aea56 |
|----------------------------|:------------------------------------------------------:|:------------------------------------------------------------------:|
| async_tree_none            | 475 ms                                                 | 468 ms: 1.02x faster                                               |
| async_tree_cpu_io_mixed    | 724 ms                                                 | 742 ms: 1.02x slower                                               |
| async_tree_memoization     | 580 ms                                                 | 596 ms: 1.03x slower                                               |
| async_tree_cpu_io_mixed_tg | 725 ms                                                 | 768 ms: 1.06x slower                                               |
| async_tree_io              | 1.16 sec                                               | 1.24 sec: 1.06x slower                                             |
| async_tree_io_tg           | 1.19 sec                                               | 1.27 sec: 1.07x slower                                             |
| async_tree_memoization_tg  | 574 ms                                                 | 613 ms: 1.07x slower                                               |
| async_tree_none_tg         | 447 ms                                                 | 485 ms: 1.08x slower                                               |
| Geometric mean             | (ref)                                                  | 1.05x slower                                                       |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231117-linux-x86_64-gvanrossum-for_iter_uop-3.13.0a1+-14aea56 |
|----------------|:------------------------------------------------------:|:------------------------------------------------------------------:|
| pidigits       | 187 ms                                                 | 199 ms: 1.06x slower                                               |
| float          | 83.3 ms                                                | 123 ms: 1.48x slower                                               |
| nbody          | 92.2 ms                                                | 159 ms: 1.73x slower                                               |
| Geometric mean | (ref)                                                  | 1.39x slower                                                       |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231117-linux-x86_64-gvanrossum-for_iter_uop-3.13.0a1+-14aea56 |
|----------------|:------------------------------------------------------:|:------------------------------------------------------------------:|
| regex_effbot   | 3.57 ms                                                | 3.63 ms: 1.02x slower                                              |
| regex_dna      | 209 ms                                                 | 220 ms: 1.06x slower                                               |
| regex_v8       | 22.7 ms                                                | 26.1 ms: 1.15x slower                                              |
| regex_compile  | 148 ms                                                 | 176 ms: 1.19x slower                                               |
| Geometric mean | (ref)                                                  | 1.10x slower                                                       |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231117-linux-x86_64-gvanrossum-for_iter_uop-3.13.0a1+-14aea56 |
|----------------------|:------------------------------------------------------:|:------------------------------------------------------------------:|
| unpickle             | 15.8 us                                                | 15.1 us: 1.05x faster                                              |
| pickle_pure_python   | 326 us                                                 | 315 us: 1.04x faster                                               |
| pickle_dict          | 33.5 us                                                | 33.2 us: 1.01x faster                                              |
| json_loads           | 28.4 us                                                | 28.2 us: 1.01x faster                                              |
| json_dumps           | 10.6 ms                                                | 10.5 ms: 1.01x faster                                              |
| pickle               | 11.2 us                                                | 11.3 us: 1.01x slower                                              |
| unpickle_list        | 5.04 us                                                | 5.40 us: 1.07x slower                                              |
| pickle_list          | 4.67 us                                                | 5.03 us: 1.08x slower                                              |
| xml_etree_process    | 61.2 ms                                                | 67.0 ms: 1.09x slower                                              |
| xml_etree_generate   | 88.7 ms                                                | 98.2 ms: 1.11x slower                                              |
| unpickle_pure_python | 230 us                                                 | 262 us: 1.14x slower                                               |
| xml_etree_iterparse  | 106 ms                                                 | 122 ms: 1.15x slower                                               |
| tomli_loads          | 2.30 sec                                               | 3.30 sec: 1.44x slower                                             |
| Geometric mean       | (ref)                                                  | 1.06x slower                                                       |

Benchmark hidden because not significant (1): xml_etree_parse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231117-linux-x86_64-gvanrossum-for_iter_uop-3.13.0a1+-14aea56 |
|------------------------|:------------------------------------------------------:|:------------------------------------------------------------------:|
| python_startup         | 9.53 ms                                                | 10.4 ms: 1.09x slower                                              |
| python_startup_no_site | 6.92 ms                                                | 9.07 ms: 1.31x slower                                              |
| Geometric mean         | (ref)                                                  | 1.20x slower                                                       |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231117-linux-x86_64-gvanrossum-for_iter_uop-3.13.0a1+-14aea56 |
|-----------|:------------------------------------------------------:|:------------------------------------------------------------------:|
| mako      | 11.5 ms                                                | 19.1 ms: 1.66x slower                                              |

All benchmarks:
===============

| Benchmark                  | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231117-linux-x86_64-gvanrossum-for_iter_uop-3.13.0a1+-14aea56 |
|----------------------------|:------------------------------------------------------:|:------------------------------------------------------------------:|
| typing_runtime_protocols   | 153 us                                                 | 130 us: 1.18x faster                                               |
| generators                 | 32.5 ms                                                | 29.7 ms: 1.09x faster                                              |
| coroutines                 | 23.5 ms                                                | 22.0 ms: 1.06x faster                                              |
| unpack_sequence            | 54.2 ns                                                | 50.9 ns: 1.06x faster                                              |
| unpickle                   | 15.8 us                                                | 15.1 us: 1.05x faster                                              |
| gc_traversal               | 4.28 ms                                                | 4.09 ms: 1.05x faster                                              |
| pickle_pure_python         | 326 us                                                 | 315 us: 1.04x faster                                               |
| asyncio_tcp                | 506 ms                                                 | 493 ms: 1.03x faster                                               |
| async_tree_none            | 475 ms                                                 | 468 ms: 1.02x faster                                               |
| deepcopy_reduce            | 3.23 us                                                | 3.18 us: 1.02x faster                                              |
| logging_simple             | 6.38 us                                                | 6.31 us: 1.01x faster                                              |
| pickle_dict                | 33.5 us                                                | 33.2 us: 1.01x faster                                              |
| json                       | 5.22 ms                                                | 5.18 ms: 1.01x faster                                              |
| json_loads                 | 28.4 us                                                | 28.2 us: 1.01x faster                                              |
| json_dumps                 | 10.6 ms                                                | 10.5 ms: 1.01x faster                                              |
| pickle                     | 11.2 us                                                | 11.3 us: 1.01x slower                                              |
| dask                       | 369 ms                                                 | 373 ms: 1.01x slower                                               |
| pathlib                    | 18.9 ms                                                | 19.1 ms: 1.01x slower                                              |
| docutils                   | 2.75 sec                                               | 2.79 sec: 1.01x slower                                             |
| create_gc_cycles           | 1.45 ms                                                | 1.47 ms: 1.01x slower                                              |
| regex_effbot               | 3.57 ms                                                | 3.63 ms: 1.02x slower                                              |
| asyncio_tcp_ssl            | 1.78 sec                                               | 1.81 sec: 1.02x slower                                             |
| sympy_sum                  | 167 ms                                                 | 171 ms: 1.02x slower                                               |
| async_tree_cpu_io_mixed    | 724 ms                                                 | 742 ms: 1.02x slower                                               |
| mypy2                      | 351 ms                                                 | 360 ms: 1.02x slower                                               |
| deepcopy                   | 363 us                                                 | 372 us: 1.03x slower                                               |
| scimark_lu                 | 120 ms                                                 | 124 ms: 1.03x slower                                               |
| dulwich_log                | 68.7 ms                                                | 70.6 ms: 1.03x slower                                              |
| async_generators           | 459 ms                                                 | 472 ms: 1.03x slower                                               |
| async_tree_memoization     | 580 ms                                                 | 596 ms: 1.03x slower                                               |
| tornado_http               | 101 ms                                                 | 104 ms: 1.03x slower                                               |
| bench_thread_pool          | 845 us                                                 | 877 us: 1.04x slower                                               |
| logging_silent             | 108 ns                                                 | 113 ns: 1.05x slower                                               |
| regex_dna                  | 209 ms                                                 | 220 ms: 1.06x slower                                               |
| sqlglot_transpile          | 1.68 ms                                                | 1.77 ms: 1.06x slower                                              |
| sqlite_synth               | 2.83 us                                                | 3.00 us: 1.06x slower                                              |
| chameleon                  | 7.41 ms                                                | 7.84 ms: 1.06x slower                                              |
| async_tree_cpu_io_mixed_tg | 725 ms                                                 | 768 ms: 1.06x slower                                               |
| pidigits                   | 187 ms                                                 | 199 ms: 1.06x slower                                               |
| async_tree_io              | 1.16 sec                                               | 1.24 sec: 1.06x slower                                             |
| sqlglot_parse              | 1.35 ms                                                | 1.44 ms: 1.07x slower                                              |
| async_tree_io_tg           | 1.19 sec                                               | 1.27 sec: 1.07x slower                                             |
| scimark_sor                | 129 ms                                                 | 138 ms: 1.07x slower                                               |
| async_tree_memoization_tg  | 574 ms                                                 | 613 ms: 1.07x slower                                               |
| unpickle_list              | 5.04 us                                                | 5.40 us: 1.07x slower                                              |
| pickle_list                | 4.67 us                                                | 5.03 us: 1.08x slower                                              |
| sympy_str                  | 296 ms                                                 | 319 ms: 1.08x slower                                               |
| sympy_integrate            | 21.2 ms                                                | 22.9 ms: 1.08x slower                                              |
| async_tree_none_tg         | 447 ms                                                 | 485 ms: 1.08x slower                                               |
| sqlglot_normalize          | 112 ms                                                 | 121 ms: 1.09x slower                                               |
| pycparser                  | 1.17 sec                                               | 1.27 sec: 1.09x slower                                             |
| mdp                        | 2.57 sec                                               | 2.80 sec: 1.09x slower                                             |
| python_startup             | 9.53 ms                                                | 10.4 ms: 1.09x slower                                              |
| xml_etree_process          | 61.2 ms                                                | 67.0 ms: 1.09x slower                                              |
| 2to3                       | 274 ms                                                 | 301 ms: 1.10x slower                                               |
| raytrace                   | 308 ms                                                 | 339 ms: 1.10x slower                                               |
| xml_etree_generate         | 88.7 ms                                                | 98.2 ms: 1.11x slower                                              |
| sympy_expand               | 476 ms                                                 | 528 ms: 1.11x slower                                               |
| deepcopy_memo              | 39.7 us                                                | 44.7 us: 1.13x slower                                              |
| sqlglot_optimize           | 54.8 ms                                                | 62.1 ms: 1.13x slower                                              |
| unpickle_pure_python       | 230 us                                                 | 262 us: 1.14x slower                                               |
| regex_v8                   | 22.7 ms                                                | 26.1 ms: 1.15x slower                                              |
| xml_etree_iterparse        | 106 ms                                                 | 122 ms: 1.15x slower                                               |
| richards                   | 46.0 ms                                                | 53.2 ms: 1.16x slower                                              |
| richards_super             | 51.9 ms                                                | 60.6 ms: 1.17x slower                                              |
| meteor_contest             | 110 ms                                                 | 129 ms: 1.18x slower                                               |
| pprint_safe_repr           | 765 ms                                                 | 905 ms: 1.18x slower                                               |
| regex_compile              | 148 ms                                                 | 176 ms: 1.19x slower                                               |
| pprint_pformat             | 1.55 sec                                               | 1.90 sec: 1.22x slower                                             |
| crypto_pyaes               | 83.6 ms                                                | 105 ms: 1.26x slower                                               |
| coverage                   | 75.1 ms                                                | 95.8 ms: 1.28x slower                                              |
| go                         | 140 ms                                                 | 181 ms: 1.29x slower                                               |
| telco                      | 7.18 ms                                                | 9.30 ms: 1.30x slower                                              |
| scimark_monte_carlo        | 74.6 ms                                                | 97.1 ms: 1.30x slower                                              |
| python_startup_no_site     | 6.92 ms                                                | 9.07 ms: 1.31x slower                                              |
| chaos                      | 67.5 ms                                                | 89.5 ms: 1.33x slower                                              |
| comprehensions             | 20.9 us                                                | 28.6 us: 1.37x slower                                              |
| pyflate                    | 471 ms                                                 | 645 ms: 1.37x slower                                               |
| fannkuch                   | 410 ms                                                 | 566 ms: 1.38x slower                                               |
| nqueens                    | 86.2 ms                                                | 120 ms: 1.39x slower                                               |
| tomli_loads                | 2.30 sec                                               | 3.30 sec: 1.44x slower                                             |
| float                      | 83.3 ms                                                | 123 ms: 1.48x slower                                               |
| scimark_sparse_mat_mult    | 5.33 ms                                                | 7.92 ms: 1.49x slower                                              |
| scimark_fft                | 381 ms                                                 | 581 ms: 1.53x slower                                               |
| mako                       | 11.5 ms                                                | 19.1 ms: 1.66x slower                                              |
| deltablue                  | 3.71 ms                                                | 6.38 ms: 1.72x slower                                              |
| nbody                      | 92.2 ms                                                | 159 ms: 1.73x slower                                               |
| hexiom                     | 6.54 ms                                                | 11.6 ms: 1.78x slower                                              |
| spectral_norm              | 115 ms                                                 | 209 ms: 1.82x slower                                               |
| Geometric mean             | (ref)                                                  | 1.12x slower                                                       |

Benchmark hidden because not significant (4): xml_etree_parse, bench_mp_pool, asyncio_websockets, logging_format
Ignored benchmarks (5) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.07x
- 95% likely to have a slowdown of 1.06x
- 99% likely to have a slowdown of 1.06x
