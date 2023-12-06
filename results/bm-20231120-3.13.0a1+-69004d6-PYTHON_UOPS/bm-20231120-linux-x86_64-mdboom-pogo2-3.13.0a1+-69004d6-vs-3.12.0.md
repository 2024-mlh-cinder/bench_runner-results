
# Results vs. 3.12.0

- fork: mdboom
- ref: pogo2
- machine: linux-x86_64
- commit hash: 69004d6
- commit date: 2023-11-20
- overall geometric mean: 1.11x slower \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.05x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-linux-x86_64-mdboom-pogo2-3.13.0a1+-69004d6 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| 2to3           | 274 ms                                                 | 300 ms: 1.09x slower                                    |
| chameleon      | 7.41 ms                                                | 7.79 ms: 1.05x slower                                   |
| docutils       | 2.75 sec                                               | 2.77 sec: 1.01x slower                                  |
| tornado_http   | 101 ms                                                 | 103 ms: 1.03x slower                                    |
| Geometric mean | (ref)                                                  | 1.04x slower                                            |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-linux-x86_64-mdboom-pogo2-3.13.0a1+-69004d6 |
|----------------------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| async_tree_none            | 475 ms                                                 | 467 ms: 1.02x faster                                    |
| async_tree_cpu_io_mixed    | 724 ms                                                 | 737 ms: 1.02x slower                                    |
| async_tree_memoization     | 580 ms                                                 | 594 ms: 1.02x slower                                    |
| async_tree_cpu_io_mixed_tg | 725 ms                                                 | 764 ms: 1.05x slower                                    |
| async_tree_memoization_tg  | 574 ms                                                 | 606 ms: 1.05x slower                                    |
| async_tree_io              | 1.16 sec                                               | 1.24 sec: 1.06x slower                                  |
| async_tree_io_tg           | 1.19 sec                                               | 1.27 sec: 1.07x slower                                  |
| async_tree_none_tg         | 447 ms                                                 | 477 ms: 1.07x slower                                    |
| Geometric mean             | (ref)                                                  | 1.04x slower                                            |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-linux-x86_64-mdboom-pogo2-3.13.0a1+-69004d6 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| pidigits       | 187 ms                                                 | 191 ms: 1.02x slower                                    |
| float          | 83.3 ms                                                | 120 ms: 1.44x slower                                    |
| nbody          | 92.2 ms                                                | 170 ms: 1.85x slower                                    |
| Geometric mean | (ref)                                                  | 1.39x slower                                            |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-linux-x86_64-mdboom-pogo2-3.13.0a1+-69004d6 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| regex_effbot   | 3.57 ms                                                | 3.61 ms: 1.01x slower                                   |
| regex_dna      | 209 ms                                                 | 224 ms: 1.07x slower                                    |
| regex_v8       | 22.7 ms                                                | 24.7 ms: 1.09x slower                                   |
| regex_compile  | 148 ms                                                 | 174 ms: 1.17x slower                                    |
| Geometric mean | (ref)                                                  | 1.09x slower                                            |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-linux-x86_64-mdboom-pogo2-3.13.0a1+-69004d6 |
|----------------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| pickle_pure_python   | 326 us                                                 | 310 us: 1.05x faster                                    |
| json_loads           | 28.4 us                                                | 28.2 us: 1.01x faster                                   |
| pickle_dict          | 33.5 us                                                | 33.4 us: 1.00x faster                                   |
| pickle               | 11.2 us                                                | 11.3 us: 1.01x slower                                   |
| json_dumps           | 10.6 ms                                                | 10.7 ms: 1.01x slower                                   |
| unpickle_list        | 5.04 us                                                | 5.18 us: 1.03x slower                                   |
| pickle_list          | 4.67 us                                                | 4.93 us: 1.06x slower                                   |
| xml_etree_process    | 61.2 ms                                                | 65.8 ms: 1.07x slower                                   |
| xml_etree_generate   | 88.7 ms                                                | 96.7 ms: 1.09x slower                                   |
| unpickle_pure_python | 230 us                                                 | 258 us: 1.12x slower                                    |
| xml_etree_iterparse  | 106 ms                                                 | 124 ms: 1.17x slower                                    |
| tomli_loads          | 2.30 sec                                               | 3.17 sec: 1.38x slower                                  |
| Geometric mean       | (ref)                                                  | 1.06x slower                                            |

Benchmark hidden because not significant (2): xml_etree_parse, unpickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-linux-x86_64-mdboom-pogo2-3.13.0a1+-69004d6 |
|------------------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| python_startup         | 9.53 ms                                                | 10.4 ms: 1.09x slower                                   |
| python_startup_no_site | 6.92 ms                                                | 9.08 ms: 1.31x slower                                   |
| Geometric mean         | (ref)                                                  | 1.20x slower                                            |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-linux-x86_64-mdboom-pogo2-3.13.0a1+-69004d6 |
|-----------|:------------------------------------------------------:|:-------------------------------------------------------:|
| mako      | 11.5 ms                                                | 18.4 ms: 1.60x slower                                   |

All benchmarks:
===============

| Benchmark                  | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-linux-x86_64-mdboom-pogo2-3.13.0a1+-69004d6 |
|----------------------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| gc_traversal               | 4.28 ms                                                | 3.51 ms: 1.22x faster                                   |
| typing_runtime_protocols   | 153 us                                                 | 129 us: 1.19x faster                                    |
| unpack_sequence            | 54.2 ns                                                | 49.3 ns: 1.10x faster                                   |
| generators                 | 32.5 ms                                                | 29.6 ms: 1.10x faster                                   |
| pickle_pure_python         | 326 us                                                 | 310 us: 1.05x faster                                    |
| coroutines                 | 23.5 ms                                                | 22.4 ms: 1.05x faster                                   |
| asyncio_tcp                | 506 ms                                                 | 491 ms: 1.03x faster                                    |
| async_tree_none            | 475 ms                                                 | 467 ms: 1.02x faster                                    |
| json                       | 5.22 ms                                                | 5.14 ms: 1.02x faster                                   |
| logging_simple             | 6.38 us                                                | 6.31 us: 1.01x faster                                   |
| deepcopy_reduce            | 3.23 us                                                | 3.20 us: 1.01x faster                                   |
| json_loads                 | 28.4 us                                                | 28.2 us: 1.01x faster                                   |
| pickle_dict                | 33.5 us                                                | 33.4 us: 1.00x faster                                   |
| pickle                     | 11.2 us                                                | 11.3 us: 1.01x slower                                   |
| docutils                   | 2.75 sec                                               | 2.77 sec: 1.01x slower                                  |
| sympy_sum                  | 167 ms                                                 | 169 ms: 1.01x slower                                    |
| create_gc_cycles           | 1.45 ms                                                | 1.47 ms: 1.01x slower                                   |
| regex_effbot               | 3.57 ms                                                | 3.61 ms: 1.01x slower                                   |
| json_dumps                 | 10.6 ms                                                | 10.7 ms: 1.01x slower                                   |
| asyncio_tcp_ssl            | 1.78 sec                                               | 1.80 sec: 1.01x slower                                  |
| deepcopy                   | 363 us                                                 | 368 us: 1.01x slower                                    |
| dulwich_log                | 68.7 ms                                                | 69.7 ms: 1.01x slower                                   |
| async_generators           | 459 ms                                                 | 467 ms: 1.02x slower                                    |
| async_tree_cpu_io_mixed    | 724 ms                                                 | 737 ms: 1.02x slower                                    |
| pidigits                   | 187 ms                                                 | 191 ms: 1.02x slower                                    |
| async_tree_memoization     | 580 ms                                                 | 594 ms: 1.02x slower                                    |
| tornado_http               | 101 ms                                                 | 103 ms: 1.03x slower                                    |
| unpickle_list              | 5.04 us                                                | 5.18 us: 1.03x slower                                   |
| mypy2                      | 351 ms                                                 | 361 ms: 1.03x slower                                    |
| scimark_lu                 | 120 ms                                                 | 124 ms: 1.03x slower                                    |
| bench_thread_pool          | 845 us                                                 | 875 us: 1.04x slower                                    |
| sqlite_synth               | 2.83 us                                                | 2.96 us: 1.04x slower                                   |
| chameleon                  | 7.41 ms                                                | 7.79 ms: 1.05x slower                                   |
| async_tree_cpu_io_mixed_tg | 725 ms                                                 | 764 ms: 1.05x slower                                    |
| async_tree_memoization_tg  | 574 ms                                                 | 606 ms: 1.05x slower                                    |
| pickle_list                | 4.67 us                                                | 4.93 us: 1.06x slower                                   |
| sqlglot_transpile          | 1.68 ms                                                | 1.77 ms: 1.06x slower                                   |
| logging_silent             | 108 ns                                                 | 114 ns: 1.06x slower                                    |
| sympy_str                  | 296 ms                                                 | 313 ms: 1.06x slower                                    |
| sympy_expand               | 476 ms                                                 | 504 ms: 1.06x slower                                    |
| scimark_sor                | 129 ms                                                 | 137 ms: 1.06x slower                                    |
| async_tree_io              | 1.16 sec                                               | 1.24 sec: 1.06x slower                                  |
| async_tree_io_tg           | 1.19 sec                                               | 1.27 sec: 1.07x slower                                  |
| sqlglot_parse              | 1.35 ms                                                | 1.44 ms: 1.07x slower                                   |
| async_tree_none_tg         | 447 ms                                                 | 477 ms: 1.07x slower                                    |
| sympy_integrate            | 21.2 ms                                                | 22.7 ms: 1.07x slower                                   |
| regex_dna                  | 209 ms                                                 | 224 ms: 1.07x slower                                    |
| xml_etree_process          | 61.2 ms                                                | 65.8 ms: 1.07x slower                                   |
| pycparser                  | 1.17 sec                                               | 1.26 sec: 1.08x slower                                  |
| sqlglot_normalize          | 112 ms                                                 | 121 ms: 1.08x slower                                    |
| mdp                        | 2.57 sec                                               | 2.80 sec: 1.09x slower                                  |
| xml_etree_generate         | 88.7 ms                                                | 96.7 ms: 1.09x slower                                   |
| regex_v8                   | 22.7 ms                                                | 24.7 ms: 1.09x slower                                   |
| raytrace                   | 308 ms                                                 | 336 ms: 1.09x slower                                    |
| 2to3                       | 274 ms                                                 | 300 ms: 1.09x slower                                    |
| python_startup             | 9.53 ms                                                | 10.4 ms: 1.09x slower                                   |
| unpickle_pure_python       | 230 us                                                 | 258 us: 1.12x slower                                    |
| sqlglot_optimize           | 54.8 ms                                                | 62.0 ms: 1.13x slower                                   |
| deepcopy_memo              | 39.7 us                                                | 45.4 us: 1.14x slower                                   |
| meteor_contest             | 110 ms                                                 | 127 ms: 1.16x slower                                    |
| richards                   | 46.0 ms                                                | 53.4 ms: 1.16x slower                                   |
| richards_super             | 51.9 ms                                                | 60.2 ms: 1.16x slower                                   |
| xml_etree_iterparse        | 106 ms                                                 | 124 ms: 1.17x slower                                    |
| regex_compile              | 148 ms                                                 | 174 ms: 1.17x slower                                    |
| pprint_safe_repr           | 765 ms                                                 | 928 ms: 1.21x slower                                    |
| crypto_pyaes               | 83.6 ms                                                | 103 ms: 1.24x slower                                    |
| pprint_pformat             | 1.55 sec                                               | 1.93 sec: 1.24x slower                                  |
| go                         | 140 ms                                                 | 177 ms: 1.26x slower                                    |
| telco                      | 7.18 ms                                                | 9.06 ms: 1.26x slower                                   |
| coverage                   | 75.1 ms                                                | 95.2 ms: 1.27x slower                                   |
| python_startup_no_site     | 6.92 ms                                                | 9.08 ms: 1.31x slower                                   |
| chaos                      | 67.5 ms                                                | 89.4 ms: 1.32x slower                                   |
| pyflate                    | 471 ms                                                 | 632 ms: 1.34x slower                                    |
| fannkuch                   | 410 ms                                                 | 551 ms: 1.34x slower                                    |
| comprehensions             | 20.9 us                                                | 28.6 us: 1.36x slower                                   |
| scimark_monte_carlo        | 74.6 ms                                                | 103 ms: 1.38x slower                                    |
| tomli_loads                | 2.30 sec                                               | 3.17 sec: 1.38x slower                                  |
| nqueens                    | 86.2 ms                                                | 120 ms: 1.39x slower                                    |
| float                      | 83.3 ms                                                | 120 ms: 1.44x slower                                    |
| scimark_sparse_mat_mult    | 5.33 ms                                                | 7.94 ms: 1.49x slower                                   |
| scimark_fft                | 381 ms                                                 | 567 ms: 1.49x slower                                    |
| mako                       | 11.5 ms                                                | 18.4 ms: 1.60x slower                                   |
| deltablue                  | 3.71 ms                                                | 6.30 ms: 1.70x slower                                   |
| hexiom                     | 6.54 ms                                                | 11.5 ms: 1.76x slower                                   |
| spectral_norm              | 115 ms                                                 | 205 ms: 1.78x slower                                    |
| nbody                      | 92.2 ms                                                | 170 ms: 1.85x slower                                    |
| Geometric mean             | (ref)                                                  | 1.11x slower                                            |

Benchmark hidden because not significant (7): pathlib, bench_mp_pool, xml_etree_parse, asyncio_websockets, logging_format, dask, unpickle
Ignored benchmarks (5) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.06x
- 95% likely to have a slowdown of 1.06x
- 99% likely to have a slowdown of 1.05x
