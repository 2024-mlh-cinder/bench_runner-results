
# Results vs. 3.12.0

- fork: python
- ref: 8deb8bc2e5af0e229df8
- machine: linux-x86_64
- commit hash: 8deb8bc
- commit date: 2023-11-20
- overall geometric mean: 1.03x faster \*
- HPT reliability: 99.96%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-linux-x86_64-python-8deb8bc2e5af0e229df8-3.13.0a1+-8deb8bc |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| 2to3           | 274 ms                                                 | 264 ms: 1.04x faster                                                   |
| chameleon      | 7.41 ms                                                | 7.02 ms: 1.06x faster                                                  |
| docutils       | 2.75 sec                                               | 2.61 sec: 1.06x faster                                                 |
| tornado_http   | 101 ms                                                 | 94.8 ms: 1.06x faster                                                  |
| Geometric mean | (ref)                                                  | 1.05x faster                                                           |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-linux-x86_64-python-8deb8bc2e5af0e229df8-3.13.0a1+-8deb8bc |
|----------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| async_tree_none            | 475 ms                                                 | 439 ms: 1.08x faster                                                   |
| async_tree_memoization     | 580 ms                                                 | 565 ms: 1.03x faster                                                   |
| async_tree_cpu_io_mixed    | 724 ms                                                 | 710 ms: 1.02x faster                                                   |
| async_tree_cpu_io_mixed_tg | 725 ms                                                 | 739 ms: 1.02x slower                                                   |
| async_tree_none_tg         | 447 ms                                                 | 457 ms: 1.02x slower                                                   |
| async_tree_io              | 1.16 sec                                               | 1.20 sec: 1.03x slower                                                 |
| async_tree_io_tg           | 1.19 sec                                               | 1.23 sec: 1.03x slower                                                 |
| async_tree_memoization_tg  | 574 ms                                                 | 597 ms: 1.04x slower                                                   |
| Geometric mean             | (ref)                                                  | 1.00x slower                                                           |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-linux-x86_64-python-8deb8bc2e5af0e229df8-3.13.0a1+-8deb8bc |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| float          | 83.3 ms                                                | 82.1 ms: 1.02x faster                                                  |
| nbody          | 92.2 ms                                                | 90.8 ms: 1.01x faster                                                  |
| pidigits       | 187 ms                                                 | 195 ms: 1.04x slower                                                   |
| Geometric mean | (ref)                                                  | 1.00x slower                                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-linux-x86_64-python-8deb8bc2e5af0e229df8-3.13.0a1+-8deb8bc |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| regex_compile  | 148 ms                                                 | 135 ms: 1.10x faster                                                   |
| regex_dna      | 209 ms                                                 | 217 ms: 1.04x slower                                                   |
| regex_effbot   | 3.57 ms                                                | 3.72 ms: 1.04x slower                                                  |
| regex_v8       | 22.7 ms                                                | 25.5 ms: 1.12x slower                                                  |
| Geometric mean | (ref)                                                  | 1.03x slower                                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-linux-x86_64-python-8deb8bc2e5af0e229df8-3.13.0a1+-8deb8bc |
|----------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| unpickle             | 15.8 us                                                | 14.3 us: 1.10x faster                                                  |
| pickle_pure_python   | 326 us                                                 | 304 us: 1.07x faster                                                   |
| tomli_loads          | 2.30 sec                                               | 2.17 sec: 1.06x faster                                                 |
| unpickle_pure_python | 230 us                                                 | 220 us: 1.04x faster                                                   |
| pickle_dict          | 33.5 us                                                | 32.4 us: 1.03x faster                                                  |
| xml_etree_process    | 61.2 ms                                                | 59.5 ms: 1.03x faster                                                  |
| xml_etree_generate   | 88.7 ms                                                | 86.7 ms: 1.02x faster                                                  |
| pickle               | 11.2 us                                                | 11.0 us: 1.02x faster                                                  |
| json_dumps           | 10.6 ms                                                | 10.5 ms: 1.01x faster                                                  |
| json_loads           | 28.4 us                                                | 28.2 us: 1.01x faster                                                  |
| unpickle_list        | 5.04 us                                                | 5.10 us: 1.01x slower                                                  |
| pickle_list          | 4.67 us                                                | 4.92 us: 1.05x slower                                                  |
| Geometric mean       | (ref)                                                  | 1.02x faster                                                           |

Benchmark hidden because not significant (2): xml_etree_parse, xml_etree_iterparse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-linux-x86_64-python-8deb8bc2e5af0e229df8-3.13.0a1+-8deb8bc |
|------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| python_startup         | 9.53 ms                                                | 10.3 ms: 1.08x slower                                                  |
| python_startup_no_site | 6.92 ms                                                | 8.97 ms: 1.30x slower                                                  |
| Geometric mean         | (ref)                                                  | 1.19x slower                                                           |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-linux-x86_64-python-8deb8bc2e5af0e229df8-3.13.0a1+-8deb8bc |
|-----------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| mako      | 11.5 ms                                                | 11.6 ms: 1.01x slower                                                  |

All benchmarks:
===============

| Benchmark                  | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-linux-x86_64-python-8deb8bc2e5af0e229df8-3.13.0a1+-8deb8bc |
|----------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| typing_runtime_protocols   | 153 us                                                 | 119 us: 1.29x faster                                                   |
| comprehensions             | 20.9 us                                                | 16.7 us: 1.26x faster                                                  |
| gc_traversal               | 4.28 ms                                                | 3.51 ms: 1.22x faster                                                  |
| unpack_sequence            | 54.2 ns                                                | 46.3 ns: 1.17x faster                                                  |
| crypto_pyaes               | 83.6 ms                                                | 72.3 ms: 1.16x faster                                                  |
| scimark_sparse_mat_mult    | 5.33 ms                                                | 4.63 ms: 1.15x faster                                                  |
| sympy_sum                  | 167 ms                                                 | 148 ms: 1.13x faster                                                   |
| logging_format             | 7.10 us                                                | 6.31 us: 1.12x faster                                                  |
| raytrace                   | 308 ms                                                 | 275 ms: 1.12x faster                                                   |
| deltablue                  | 3.71 ms                                                | 3.33 ms: 1.11x faster                                                  |
| chaos                      | 67.5 ms                                                | 60.9 ms: 1.11x faster                                                  |
| logging_simple             | 6.38 us                                                | 5.77 us: 1.11x faster                                                  |
| sympy_str                  | 296 ms                                                 | 268 ms: 1.11x faster                                                   |
| unpickle                   | 15.8 us                                                | 14.3 us: 1.10x faster                                                  |
| scimark_monte_carlo        | 74.6 ms                                                | 67.9 ms: 1.10x faster                                                  |
| regex_compile              | 148 ms                                                 | 135 ms: 1.10x faster                                                   |
| generators                 | 32.5 ms                                                | 29.7 ms: 1.09x faster                                                  |
| sympy_integrate            | 21.2 ms                                                | 19.5 ms: 1.08x faster                                                  |
| async_tree_none            | 475 ms                                                 | 439 ms: 1.08x faster                                                   |
| pickle_pure_python         | 326 us                                                 | 304 us: 1.07x faster                                                   |
| coroutines                 | 23.5 ms                                                | 22.0 ms: 1.07x faster                                                  |
| tornado_http               | 101 ms                                                 | 94.8 ms: 1.06x faster                                                  |
| scimark_lu                 | 120 ms                                                 | 114 ms: 1.06x faster                                                   |
| tomli_loads                | 2.30 sec                                               | 2.17 sec: 1.06x faster                                                 |
| deepcopy_reduce            | 3.23 us                                                | 3.05 us: 1.06x faster                                                  |
| docutils                   | 2.75 sec                                               | 2.61 sec: 1.06x faster                                                 |
| sqlglot_normalize          | 112 ms                                                 | 106 ms: 1.06x faster                                                   |
| chameleon                  | 7.41 ms                                                | 7.02 ms: 1.06x faster                                                  |
| sqlglot_parse              | 1.35 ms                                                | 1.28 ms: 1.05x faster                                                  |
| sqlglot_transpile          | 1.68 ms                                                | 1.59 ms: 1.05x faster                                                  |
| scimark_sor                | 129 ms                                                 | 123 ms: 1.05x faster                                                   |
| nqueens                    | 86.2 ms                                                | 82.1 ms: 1.05x faster                                                  |
| hexiom                     | 6.54 ms                                                | 6.23 ms: 1.05x faster                                                  |
| scimark_fft                | 381 ms                                                 | 364 ms: 1.05x faster                                                   |
| sympy_expand               | 476 ms                                                 | 455 ms: 1.05x faster                                                   |
| unpickle_pure_python       | 230 us                                                 | 220 us: 1.04x faster                                                   |
| dulwich_log                | 68.7 ms                                                | 66.0 ms: 1.04x faster                                                  |
| deepcopy                   | 363 us                                                 | 349 us: 1.04x faster                                                   |
| 2to3                       | 274 ms                                                 | 264 ms: 1.04x faster                                                   |
| asyncio_tcp                | 506 ms                                                 | 488 ms: 1.04x faster                                                   |
| pickle_dict                | 33.5 us                                                | 32.4 us: 1.03x faster                                                  |
| pathlib                    | 18.9 ms                                                | 18.3 ms: 1.03x faster                                                  |
| pprint_safe_repr           | 765 ms                                                 | 740 ms: 1.03x faster                                                   |
| deepcopy_memo              | 39.7 us                                                | 38.5 us: 1.03x faster                                                  |
| fannkuch                   | 410 ms                                                 | 398 ms: 1.03x faster                                                   |
| xml_etree_process          | 61.2 ms                                                | 59.5 ms: 1.03x faster                                                  |
| pprint_pformat             | 1.55 sec                                               | 1.51 sec: 1.03x faster                                                 |
| async_tree_memoization     | 580 ms                                                 | 565 ms: 1.03x faster                                                   |
| dask                       | 369 ms                                                 | 360 ms: 1.03x faster                                                   |
| async_generators           | 459 ms                                                 | 448 ms: 1.02x faster                                                   |
| xml_etree_generate         | 88.7 ms                                                | 86.7 ms: 1.02x faster                                                  |
| mypy2                      | 351 ms                                                 | 343 ms: 1.02x faster                                                   |
| pickle                     | 11.2 us                                                | 11.0 us: 1.02x faster                                                  |
| sqlglot_optimize           | 54.8 ms                                                | 53.7 ms: 1.02x faster                                                  |
| async_tree_cpu_io_mixed    | 724 ms                                                 | 710 ms: 1.02x faster                                                   |
| json                       | 5.22 ms                                                | 5.12 ms: 1.02x faster                                                  |
| float                      | 83.3 ms                                                | 82.1 ms: 1.02x faster                                                  |
| nbody                      | 92.2 ms                                                | 90.8 ms: 1.01x faster                                                  |
| bench_thread_pool          | 845 us                                                 | 834 us: 1.01x faster                                                   |
| json_dumps                 | 10.6 ms                                                | 10.5 ms: 1.01x faster                                                  |
| json_loads                 | 28.4 us                                                | 28.2 us: 1.01x faster                                                  |
| meteor_contest             | 110 ms                                                 | 109 ms: 1.00x faster                                                   |
| pyflate                    | 471 ms                                                 | 469 ms: 1.00x faster                                                   |
| asyncio_tcp_ssl            | 1.78 sec                                               | 1.79 sec: 1.00x slower                                                 |
| create_gc_cycles           | 1.45 ms                                                | 1.46 ms: 1.01x slower                                                  |
| mako                       | 11.5 ms                                                | 11.6 ms: 1.01x slower                                                  |
| unpickle_list              | 5.04 us                                                | 5.10 us: 1.01x slower                                                  |
| go                         | 140 ms                                                 | 142 ms: 1.01x slower                                                   |
| async_tree_cpu_io_mixed_tg | 725 ms                                                 | 739 ms: 1.02x slower                                                   |
| async_tree_none_tg         | 447 ms                                                 | 457 ms: 1.02x slower                                                   |
| logging_silent             | 108 ns                                                 | 110 ns: 1.02x slower                                                   |
| async_tree_io              | 1.16 sec                                               | 1.20 sec: 1.03x slower                                                 |
| async_tree_io_tg           | 1.19 sec                                               | 1.23 sec: 1.03x slower                                                 |
| regex_dna                  | 209 ms                                                 | 217 ms: 1.04x slower                                                   |
| async_tree_memoization_tg  | 574 ms                                                 | 597 ms: 1.04x slower                                                   |
| pidigits                   | 187 ms                                                 | 195 ms: 1.04x slower                                                   |
| regex_effbot               | 3.57 ms                                                | 3.72 ms: 1.04x slower                                                  |
| richards_super             | 51.9 ms                                                | 54.6 ms: 1.05x slower                                                  |
| pickle_list                | 4.67 us                                                | 4.92 us: 1.05x slower                                                  |
| richards                   | 46.0 ms                                                | 48.5 ms: 1.05x slower                                                  |
| mdp                        | 2.57 sec                                               | 2.74 sec: 1.07x slower                                                 |
| python_startup             | 9.53 ms                                                | 10.3 ms: 1.08x slower                                                  |
| regex_v8                   | 22.7 ms                                                | 25.5 ms: 1.12x slower                                                  |
| telco                      | 7.18 ms                                                | 8.32 ms: 1.16x slower                                                  |
| coverage                   | 75.1 ms                                                | 94.8 ms: 1.26x slower                                                  |
| python_startup_no_site     | 6.92 ms                                                | 8.97 ms: 1.30x slower                                                  |
| Geometric mean             | (ref)                                                  | 1.03x faster                                                           |

Benchmark hidden because not significant (7): xml_etree_parse, xml_etree_iterparse, asyncio_websockets, spectral_norm, bench_mp_pool, sqlite_synth, pycparser
Ignored benchmarks (5) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 99.96% likely to be faster
- 90% likely to have a speedup of 1.01x
- 95% likely to have a speedup of 1.01x
- 99% likely to have a speedup of 1.00x
