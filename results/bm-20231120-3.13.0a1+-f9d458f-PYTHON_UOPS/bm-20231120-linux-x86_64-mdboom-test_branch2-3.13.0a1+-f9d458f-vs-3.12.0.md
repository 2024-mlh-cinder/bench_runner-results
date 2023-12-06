
# Results vs. 3.12.0

- fork: mdboom
- ref: test_branch2
- machine: linux-x86_64
- commit hash: f9d458f
- commit date: 2023-11-20
- overall geometric mean: 1.08x slower \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.04x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-linux-x86_64-mdboom-test_branch2-3.13.0a1+-f9d458f |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| 2to3           | 274 ms                                                 | 295 ms: 1.08x slower                                           |
| chameleon      | 7.41 ms                                                | 7.47 ms: 1.01x slower                                          |
| tornado_http   | 101 ms                                                 | 103 ms: 1.02x slower                                           |
| Geometric mean | (ref)                                                  | 1.02x slower                                                   |

Benchmark hidden because not significant (1): docutils

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-linux-x86_64-mdboom-test_branch2-3.13.0a1+-f9d458f |
|----------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| async_tree_none            | 475 ms                                                 | 464 ms: 1.03x faster                                           |
| async_tree_cpu_io_mixed    | 724 ms                                                 | 733 ms: 1.01x slower                                           |
| async_tree_memoization     | 580 ms                                                 | 587 ms: 1.01x slower                                           |
| async_tree_io              | 1.16 sec                                               | 1.21 sec: 1.04x slower                                         |
| async_tree_io_tg           | 1.19 sec                                               | 1.24 sec: 1.05x slower                                         |
| async_tree_cpu_io_mixed_tg | 725 ms                                                 | 762 ms: 1.05x slower                                           |
| async_tree_memoization_tg  | 574 ms                                                 | 607 ms: 1.06x slower                                           |
| async_tree_none_tg         | 447 ms                                                 | 478 ms: 1.07x slower                                           |
| Geometric mean             | (ref)                                                  | 1.03x slower                                                   |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-linux-x86_64-mdboom-test_branch2-3.13.0a1+-f9d458f |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| pidigits       | 187 ms                                                 | 197 ms: 1.05x slower                                           |
| float          | 83.3 ms                                                | 115 ms: 1.38x slower                                           |
| nbody          | 92.2 ms                                                | 141 ms: 1.53x slower                                           |
| Geometric mean | (ref)                                                  | 1.31x slower                                                   |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-linux-x86_64-mdboom-test_branch2-3.13.0a1+-f9d458f |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| regex_effbot   | 3.57 ms                                                | 3.69 ms: 1.03x slower                                          |
| regex_dna      | 209 ms                                                 | 218 ms: 1.05x slower                                           |
| regex_compile  | 148 ms                                                 | 169 ms: 1.14x slower                                           |
| regex_v8       | 22.7 ms                                                | 25.9 ms: 1.14x slower                                          |
| Geometric mean | (ref)                                                  | 1.09x slower                                                   |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-linux-x86_64-mdboom-test_branch2-3.13.0a1+-f9d458f |
|----------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| unpickle             | 15.8 us                                                | 14.5 us: 1.09x faster                                          |
| pickle_pure_python   | 326 us                                                 | 307 us: 1.06x faster                                           |
| json_loads           | 28.4 us                                                | 28.2 us: 1.01x faster                                          |
| pickle_dict          | 33.5 us                                                | 33.7 us: 1.01x slower                                          |
| unpickle_list        | 5.04 us                                                | 5.09 us: 1.01x slower                                          |
| pickle               | 11.2 us                                                | 11.6 us: 1.03x slower                                          |
| xml_etree_process    | 61.2 ms                                                | 64.5 ms: 1.05x slower                                          |
| xml_etree_generate   | 88.7 ms                                                | 94.5 ms: 1.07x slower                                          |
| pickle_list          | 4.67 us                                                | 5.11 us: 1.09x slower                                          |
| unpickle_pure_python | 230 us                                                 | 252 us: 1.10x slower                                           |
| xml_etree_iterparse  | 106 ms                                                 | 118 ms: 1.12x slower                                           |
| tomli_loads          | 2.30 sec                                               | 2.97 sec: 1.29x slower                                         |
| Geometric mean       | (ref)                                                  | 1.04x slower                                                   |

Benchmark hidden because not significant (2): xml_etree_parse, json_dumps

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-linux-x86_64-mdboom-test_branch2-3.13.0a1+-f9d458f |
|------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| python_startup         | 9.53 ms                                                | 10.4 ms: 1.09x slower                                          |
| python_startup_no_site | 6.92 ms                                                | 9.00 ms: 1.30x slower                                          |
| Geometric mean         | (ref)                                                  | 1.19x slower                                                   |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-linux-x86_64-mdboom-test_branch2-3.13.0a1+-f9d458f |
|-----------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| mako      | 11.5 ms                                                | 17.2 ms: 1.50x slower                                          |

All benchmarks:
===============

| Benchmark                  | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-linux-x86_64-mdboom-test_branch2-3.13.0a1+-f9d458f |
|----------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| typing_runtime_protocols   | 153 us                                                 | 123 us: 1.25x faster                                           |
| gc_traversal               | 4.28 ms                                                | 3.81 ms: 1.12x faster                                          |
| generators                 | 32.5 ms                                                | 29.4 ms: 1.11x faster                                          |
| unpickle                   | 15.8 us                                                | 14.5 us: 1.09x faster                                          |
| unpack_sequence            | 54.2 ns                                                | 50.8 ns: 1.07x faster                                          |
| pickle_pure_python         | 326 us                                                 | 307 us: 1.06x faster                                           |
| coroutines                 | 23.5 ms                                                | 22.2 ms: 1.06x faster                                          |
| asyncio_tcp                | 506 ms                                                 | 490 ms: 1.03x faster                                           |
| logging_simple             | 6.38 us                                                | 6.20 us: 1.03x faster                                          |
| scimark_sor                | 129 ms                                                 | 126 ms: 1.03x faster                                           |
| async_tree_none            | 475 ms                                                 | 464 ms: 1.03x faster                                           |
| deepcopy_reduce            | 3.23 us                                                | 3.16 us: 1.02x faster                                          |
| logging_format             | 7.10 us                                                | 7.00 us: 1.01x faster                                          |
| sympy_sum                  | 167 ms                                                 | 165 ms: 1.01x faster                                           |
| json_loads                 | 28.4 us                                                | 28.2 us: 1.01x faster                                          |
| pickle_dict                | 33.5 us                                                | 33.7 us: 1.01x slower                                          |
| create_gc_cycles           | 1.45 ms                                                | 1.46 ms: 1.01x slower                                          |
| chameleon                  | 7.41 ms                                                | 7.47 ms: 1.01x slower                                          |
| unpickle_list              | 5.04 us                                                | 5.09 us: 1.01x slower                                          |
| json                       | 5.22 ms                                                | 5.27 ms: 1.01x slower                                          |
| scimark_lu                 | 120 ms                                                 | 122 ms: 1.01x slower                                           |
| async_tree_cpu_io_mixed    | 724 ms                                                 | 733 ms: 1.01x slower                                           |
| async_tree_memoization     | 580 ms                                                 | 587 ms: 1.01x slower                                           |
| asyncio_tcp_ssl            | 1.78 sec                                               | 1.81 sec: 1.01x slower                                         |
| logging_silent             | 108 ns                                                 | 109 ns: 1.01x slower                                           |
| dulwich_log                | 68.7 ms                                                | 69.9 ms: 1.02x slower                                          |
| tornado_http               | 101 ms                                                 | 103 ms: 1.02x slower                                           |
| mypy2                      | 351 ms                                                 | 359 ms: 1.02x slower                                           |
| sympy_str                  | 296 ms                                                 | 304 ms: 1.03x slower                                           |
| bench_thread_pool          | 845 us                                                 | 868 us: 1.03x slower                                           |
| pickle                     | 11.2 us                                                | 11.6 us: 1.03x slower                                          |
| regex_effbot               | 3.57 ms                                                | 3.69 ms: 1.03x slower                                          |
| async_tree_io              | 1.16 sec                                               | 1.21 sec: 1.04x slower                                         |
| sqlglot_transpile          | 1.68 ms                                                | 1.74 ms: 1.04x slower                                          |
| sympy_integrate            | 21.2 ms                                                | 22.1 ms: 1.04x slower                                          |
| async_tree_io_tg           | 1.19 sec                                               | 1.24 sec: 1.05x slower                                         |
| regex_dna                  | 209 ms                                                 | 218 ms: 1.05x slower                                           |
| sqlglot_parse              | 1.35 ms                                                | 1.42 ms: 1.05x slower                                          |
| sqlite_synth               | 2.83 us                                                | 2.98 us: 1.05x slower                                          |
| async_tree_cpu_io_mixed_tg | 725 ms                                                 | 762 ms: 1.05x slower                                           |
| raytrace                   | 308 ms                                                 | 324 ms: 1.05x slower                                           |
| xml_etree_process          | 61.2 ms                                                | 64.5 ms: 1.05x slower                                          |
| pidigits                   | 187 ms                                                 | 197 ms: 1.05x slower                                           |
| async_tree_memoization_tg  | 574 ms                                                 | 607 ms: 1.06x slower                                           |
| sympy_expand               | 476 ms                                                 | 504 ms: 1.06x slower                                           |
| xml_etree_generate         | 88.7 ms                                                | 94.5 ms: 1.07x slower                                          |
| sqlglot_normalize          | 112 ms                                                 | 119 ms: 1.07x slower                                           |
| async_tree_none_tg         | 447 ms                                                 | 478 ms: 1.07x slower                                           |
| deepcopy_memo              | 39.7 us                                                | 42.5 us: 1.07x slower                                          |
| 2to3                       | 274 ms                                                 | 295 ms: 1.08x slower                                           |
| pycparser                  | 1.17 sec                                               | 1.27 sec: 1.08x slower                                         |
| python_startup             | 9.53 ms                                                | 10.4 ms: 1.09x slower                                          |
| pickle_list                | 4.67 us                                                | 5.11 us: 1.09x slower                                          |
| unpickle_pure_python       | 230 us                                                 | 252 us: 1.10x slower                                           |
| sqlglot_optimize           | 54.8 ms                                                | 60.7 ms: 1.11x slower                                          |
| richards                   | 46.0 ms                                                | 51.2 ms: 1.11x slower                                          |
| meteor_contest             | 110 ms                                                 | 123 ms: 1.12x slower                                           |
| xml_etree_iterparse        | 106 ms                                                 | 118 ms: 1.12x slower                                           |
| richards_super             | 51.9 ms                                                | 58.3 ms: 1.12x slower                                          |
| crypto_pyaes               | 83.6 ms                                                | 93.9 ms: 1.12x slower                                          |
| pprint_safe_repr           | 765 ms                                                 | 861 ms: 1.13x slower                                           |
| mdp                        | 2.57 sec                                               | 2.91 sec: 1.13x slower                                         |
| regex_compile              | 148 ms                                                 | 169 ms: 1.14x slower                                           |
| regex_v8                   | 22.7 ms                                                | 25.9 ms: 1.14x slower                                          |
| pprint_pformat             | 1.55 sec                                               | 1.79 sec: 1.16x slower                                         |
| fannkuch                   | 410 ms                                                 | 490 ms: 1.19x slower                                           |
| scimark_monte_carlo        | 74.6 ms                                                | 89.2 ms: 1.20x slower                                          |
| go                         | 140 ms                                                 | 171 ms: 1.22x slower                                           |
| chaos                      | 67.5 ms                                                | 82.8 ms: 1.23x slower                                          |
| telco                      | 7.18 ms                                                | 8.92 ms: 1.24x slower                                          |
| pyflate                    | 471 ms                                                 | 592 ms: 1.26x slower                                           |
| comprehensions             | 20.9 us                                                | 26.3 us: 1.26x slower                                          |
| coverage                   | 75.1 ms                                                | 94.7 ms: 1.26x slower                                          |
| nqueens                    | 86.2 ms                                                | 110 ms: 1.27x slower                                           |
| tomli_loads                | 2.30 sec                                               | 2.97 sec: 1.29x slower                                         |
| python_startup_no_site     | 6.92 ms                                                | 9.00 ms: 1.30x slower                                          |
| scimark_fft                | 381 ms                                                 | 525 ms: 1.38x slower                                           |
| float                      | 83.3 ms                                                | 115 ms: 1.38x slower                                           |
| scimark_sparse_mat_mult    | 5.33 ms                                                | 7.47 ms: 1.40x slower                                          |
| spectral_norm              | 115 ms                                                 | 169 ms: 1.47x slower                                           |
| mako                       | 11.5 ms                                                | 17.2 ms: 1.50x slower                                          |
| nbody                      | 92.2 ms                                                | 141 ms: 1.53x slower                                           |
| deltablue                  | 3.71 ms                                                | 5.73 ms: 1.55x slower                                          |
| hexiom                     | 6.54 ms                                                | 10.3 ms: 1.57x slower                                          |
| Geometric mean             | (ref)                                                  | 1.08x slower                                                   |

Benchmark hidden because not significant (9): docutils, xml_etree_parse, asyncio_websockets, deepcopy, bench_mp_pool, json_dumps, pathlib, dask, async_generators
Ignored benchmarks (5) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.04x
- 95% likely to have a slowdown of 1.04x
- 99% likely to have a slowdown of 1.04x
