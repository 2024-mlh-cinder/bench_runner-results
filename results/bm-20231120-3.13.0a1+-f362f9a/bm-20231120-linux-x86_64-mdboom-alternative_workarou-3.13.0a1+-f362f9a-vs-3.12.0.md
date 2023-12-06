
# Results vs. 3.12.0

- fork: mdboom
- ref: alternative_workarou
- machine: linux-x86_64
- commit hash: f362f9a
- commit date: 2023-11-20
- overall geometric mean: 1.03x faster \*
- HPT reliability: 99.98%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-linux-x86_64-mdboom-alternative_workarou-3.13.0a1+-f362f9a |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| 2to3           | 274 ms                                                 | 264 ms: 1.04x faster                                                   |
| chameleon      | 7.41 ms                                                | 6.93 ms: 1.07x faster                                                  |
| docutils       | 2.75 sec                                               | 2.60 sec: 1.06x faster                                                 |
| tornado_http   | 101 ms                                                 | 95.2 ms: 1.06x faster                                                  |
| Geometric mean | (ref)                                                  | 1.06x faster                                                           |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-linux-x86_64-mdboom-alternative_workarou-3.13.0a1+-f362f9a |
|----------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| async_tree_none            | 475 ms                                                 | 433 ms: 1.10x faster                                                   |
| async_tree_memoization     | 580 ms                                                 | 559 ms: 1.04x faster                                                   |
| async_tree_cpu_io_mixed    | 724 ms                                                 | 711 ms: 1.02x faster                                                   |
| async_tree_io              | 1.16 sec                                               | 1.18 sec: 1.01x slower                                                 |
| async_tree_none_tg         | 447 ms                                                 | 454 ms: 1.01x slower                                                   |
| async_tree_io_tg           | 1.19 sec                                               | 1.21 sec: 1.02x slower                                                 |
| async_tree_cpu_io_mixed_tg | 725 ms                                                 | 740 ms: 1.02x slower                                                   |
| async_tree_memoization_tg  | 574 ms                                                 | 591 ms: 1.03x slower                                                   |
| Geometric mean             | (ref)                                                  | 1.01x faster                                                           |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-linux-x86_64-mdboom-alternative_workarou-3.13.0a1+-f362f9a |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| nbody          | 92.2 ms                                                | 89.9 ms: 1.02x faster                                                  |
| float          | 83.3 ms                                                | 81.6 ms: 1.02x faster                                                  |
| pidigits       | 187 ms                                                 | 195 ms: 1.04x slower                                                   |
| Geometric mean | (ref)                                                  | 1.00x faster                                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-linux-x86_64-mdboom-alternative_workarou-3.13.0a1+-f362f9a |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| regex_compile  | 148 ms                                                 | 133 ms: 1.11x faster                                                   |
| regex_effbot   | 3.57 ms                                                | 3.64 ms: 1.02x slower                                                  |
| regex_dna      | 209 ms                                                 | 215 ms: 1.03x slower                                                   |
| regex_v8       | 22.7 ms                                                | 25.6 ms: 1.13x slower                                                  |
| Geometric mean | (ref)                                                  | 1.02x slower                                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-linux-x86_64-mdboom-alternative_workarou-3.13.0a1+-f362f9a |
|----------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| pickle_pure_python   | 326 us                                                 | 304 us: 1.07x faster                                                   |
| tomli_loads          | 2.30 sec                                               | 2.15 sec: 1.07x faster                                                 |
| unpickle_pure_python | 230 us                                                 | 221 us: 1.04x faster                                                   |
| xml_etree_generate   | 88.7 ms                                                | 86.6 ms: 1.03x faster                                                  |
| xml_etree_process    | 61.2 ms                                                | 60.1 ms: 1.02x faster                                                  |
| json_loads           | 28.4 us                                                | 28.1 us: 1.01x faster                                                  |
| json_dumps           | 10.6 ms                                                | 10.5 ms: 1.01x faster                                                  |
| pickle_dict          | 33.5 us                                                | 33.3 us: 1.01x faster                                                  |
| unpickle             | 15.8 us                                                | 15.9 us: 1.01x slower                                                  |
| pickle               | 11.2 us                                                | 11.4 us: 1.01x slower                                                  |
| unpickle_list        | 5.04 us                                                | 5.15 us: 1.02x slower                                                  |
| pickle_list          | 4.67 us                                                | 4.97 us: 1.06x slower                                                  |
| Geometric mean       | (ref)                                                  | 1.01x faster                                                           |

Benchmark hidden because not significant (2): xml_etree_parse, xml_etree_iterparse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-linux-x86_64-mdboom-alternative_workarou-3.13.0a1+-f362f9a |
|------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| python_startup         | 9.53 ms                                                | 10.4 ms: 1.09x slower                                                  |
| python_startup_no_site | 6.92 ms                                                | 9.03 ms: 1.31x slower                                                  |
| Geometric mean         | (ref)                                                  | 1.19x slower                                                           |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-linux-x86_64-mdboom-alternative_workarou-3.13.0a1+-f362f9a |
|-----------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| mako      | 11.5 ms                                                | 11.4 ms: 1.01x faster                                                  |

All benchmarks:
===============

| Benchmark                  | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-linux-x86_64-mdboom-alternative_workarou-3.13.0a1+-f362f9a |
|----------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| typing_runtime_protocols   | 153 us                                                 | 116 us: 1.32x faster                                                   |
| comprehensions             | 20.9 us                                                | 16.5 us: 1.27x faster                                                  |
| unpack_sequence            | 54.2 ns                                                | 45.3 ns: 1.20x faster                                                  |
| gc_traversal               | 4.28 ms                                                | 3.64 ms: 1.18x faster                                                  |
| crypto_pyaes               | 83.6 ms                                                | 72.3 ms: 1.16x faster                                                  |
| logging_format             | 7.10 us                                                | 6.23 us: 1.14x faster                                                  |
| sympy_sum                  | 167 ms                                                 | 147 ms: 1.13x faster                                                   |
| logging_simple             | 6.38 us                                                | 5.68 us: 1.12x faster                                                  |
| raytrace                   | 308 ms                                                 | 275 ms: 1.12x faster                                                   |
| regex_compile              | 148 ms                                                 | 133 ms: 1.11x faster                                                   |
| deltablue                  | 3.71 ms                                                | 3.33 ms: 1.11x faster                                                  |
| sympy_str                  | 296 ms                                                 | 267 ms: 1.11x faster                                                   |
| chaos                      | 67.5 ms                                                | 61.1 ms: 1.11x faster                                                  |
| async_tree_none            | 475 ms                                                 | 433 ms: 1.10x faster                                                   |
| scimark_monte_carlo        | 74.6 ms                                                | 68.4 ms: 1.09x faster                                                  |
| sympy_integrate            | 21.2 ms                                                | 19.5 ms: 1.09x faster                                                  |
| generators                 | 32.5 ms                                                | 30.0 ms: 1.08x faster                                                  |
| scimark_sparse_mat_mult    | 5.33 ms                                                | 4.97 ms: 1.07x faster                                                  |
| pickle_pure_python         | 326 us                                                 | 304 us: 1.07x faster                                                   |
| coroutines                 | 23.5 ms                                                | 21.8 ms: 1.07x faster                                                  |
| tomli_loads                | 2.30 sec                                               | 2.15 sec: 1.07x faster                                                 |
| chameleon                  | 7.41 ms                                                | 6.93 ms: 1.07x faster                                                  |
| nqueens                    | 86.2 ms                                                | 80.7 ms: 1.07x faster                                                  |
| sqlglot_parse              | 1.35 ms                                                | 1.27 ms: 1.06x faster                                                  |
| hexiom                     | 6.54 ms                                                | 6.18 ms: 1.06x faster                                                  |
| sqlglot_normalize          | 112 ms                                                 | 105 ms: 1.06x faster                                                   |
| sympy_expand               | 476 ms                                                 | 450 ms: 1.06x faster                                                   |
| docutils                   | 2.75 sec                                               | 2.60 sec: 1.06x faster                                                 |
| tornado_http               | 101 ms                                                 | 95.2 ms: 1.06x faster                                                  |
| sqlglot_transpile          | 1.68 ms                                                | 1.59 ms: 1.06x faster                                                  |
| deepcopy_reduce            | 3.23 us                                                | 3.08 us: 1.05x faster                                                  |
| deepcopy                   | 363 us                                                 | 346 us: 1.05x faster                                                   |
| pprint_safe_repr           | 765 ms                                                 | 732 ms: 1.05x faster                                                   |
| dulwich_log                | 68.7 ms                                                | 65.9 ms: 1.04x faster                                                  |
| scimark_sor                | 129 ms                                                 | 124 ms: 1.04x faster                                                   |
| pprint_pformat             | 1.55 sec                                               | 1.49 sec: 1.04x faster                                                 |
| 2to3                       | 274 ms                                                 | 264 ms: 1.04x faster                                                   |
| asyncio_tcp                | 506 ms                                                 | 486 ms: 1.04x faster                                                   |
| deepcopy_memo              | 39.7 us                                                | 38.2 us: 1.04x faster                                                  |
| unpickle_pure_python       | 230 us                                                 | 221 us: 1.04x faster                                                   |
| scimark_lu                 | 120 ms                                                 | 116 ms: 1.04x faster                                                   |
| pathlib                    | 18.9 ms                                                | 18.2 ms: 1.04x faster                                                  |
| async_tree_memoization     | 580 ms                                                 | 559 ms: 1.04x faster                                                   |
| async_generators           | 459 ms                                                 | 443 ms: 1.04x faster                                                   |
| scimark_fft                | 381 ms                                                 | 368 ms: 1.03x faster                                                   |
| meteor_contest             | 110 ms                                                 | 107 ms: 1.03x faster                                                   |
| fannkuch                   | 410 ms                                                 | 399 ms: 1.03x faster                                                   |
| mypy2                      | 351 ms                                                 | 342 ms: 1.03x faster                                                   |
| sqlglot_optimize           | 54.8 ms                                                | 53.4 ms: 1.03x faster                                                  |
| xml_etree_generate         | 88.7 ms                                                | 86.6 ms: 1.03x faster                                                  |
| nbody                      | 92.2 ms                                                | 89.9 ms: 1.02x faster                                                  |
| json                       | 5.22 ms                                                | 5.10 ms: 1.02x faster                                                  |
| logging_silent             | 108 ns                                                 | 105 ns: 1.02x faster                                                   |
| dask                       | 369 ms                                                 | 361 ms: 1.02x faster                                                   |
| float                      | 83.3 ms                                                | 81.6 ms: 1.02x faster                                                  |
| xml_etree_process          | 61.2 ms                                                | 60.1 ms: 1.02x faster                                                  |
| async_tree_cpu_io_mixed    | 724 ms                                                 | 711 ms: 1.02x faster                                                   |
| spectral_norm              | 115 ms                                                 | 113 ms: 1.02x faster                                                   |
| json_loads                 | 28.4 us                                                | 28.1 us: 1.01x faster                                                  |
| bench_thread_pool          | 845 us                                                 | 836 us: 1.01x faster                                                   |
| mako                       | 11.5 ms                                                | 11.4 ms: 1.01x faster                                                  |
| json_dumps                 | 10.6 ms                                                | 10.5 ms: 1.01x faster                                                  |
| pyflate                    | 471 ms                                                 | 468 ms: 1.01x faster                                                   |
| pickle_dict                | 33.5 us                                                | 33.3 us: 1.01x faster                                                  |
| asyncio_tcp_ssl            | 1.78 sec                                               | 1.79 sec: 1.00x slower                                                 |
| create_gc_cycles           | 1.45 ms                                                | 1.46 ms: 1.00x slower                                                  |
| unpickle                   | 15.8 us                                                | 15.9 us: 1.01x slower                                                  |
| async_tree_io              | 1.16 sec                                               | 1.18 sec: 1.01x slower                                                 |
| pickle                     | 11.2 us                                                | 11.4 us: 1.01x slower                                                  |
| async_tree_none_tg         | 447 ms                                                 | 454 ms: 1.01x slower                                                   |
| async_tree_io_tg           | 1.19 sec                                               | 1.21 sec: 1.02x slower                                                 |
| regex_effbot               | 3.57 ms                                                | 3.64 ms: 1.02x slower                                                  |
| unpickle_list              | 5.04 us                                                | 5.15 us: 1.02x slower                                                  |
| async_tree_cpu_io_mixed_tg | 725 ms                                                 | 740 ms: 1.02x slower                                                   |
| richards                   | 46.0 ms                                                | 47.1 ms: 1.02x slower                                                  |
| richards_super             | 51.9 ms                                                | 53.3 ms: 1.03x slower                                                  |
| async_tree_memoization_tg  | 574 ms                                                 | 591 ms: 1.03x slower                                                   |
| regex_dna                  | 209 ms                                                 | 215 ms: 1.03x slower                                                   |
| pycparser                  | 1.17 sec                                               | 1.21 sec: 1.03x slower                                                 |
| pidigits                   | 187 ms                                                 | 195 ms: 1.04x slower                                                   |
| mdp                        | 2.57 sec                                               | 2.72 sec: 1.06x slower                                                 |
| pickle_list                | 4.67 us                                                | 4.97 us: 1.06x slower                                                  |
| python_startup             | 9.53 ms                                                | 10.4 ms: 1.09x slower                                                  |
| regex_v8                   | 22.7 ms                                                | 25.6 ms: 1.13x slower                                                  |
| telco                      | 7.18 ms                                                | 8.37 ms: 1.17x slower                                                  |
| coverage                   | 75.1 ms                                                | 96.3 ms: 1.28x slower                                                  |
| python_startup_no_site     | 6.92 ms                                                | 9.03 ms: 1.31x slower                                                  |
| Geometric mean             | (ref)                                                  | 1.03x faster                                                           |

Benchmark hidden because not significant (6): xml_etree_parse, asyncio_websockets, bench_mp_pool, go, xml_etree_iterparse, sqlite_synth
Ignored benchmarks (5) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 99.98% likely to be faster
- 90% likely to have a speedup of 1.01x
- 95% likely to have a speedup of 1.01x
- 99% likely to have a speedup of 1.00x
