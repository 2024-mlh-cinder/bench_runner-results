
# Results vs. 3.11.0

- fork: brandtbucher
- ref: justin_registers
- machine: linux-x86_64
- commit hash: bfdeb03
- commit date: 2023-10-30
- overall geometric mean: 1.01x slower
- HPT reliability: 99.31%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231030-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-bfdeb03 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| 2to3           | 266 ms                                                 | 293 ms: 1.10x slower                                                    |
| chameleon      | 6.86 ms                                                | 7.47 ms: 1.09x slower                                                   |
| docutils       | 2.69 sec                                               | 2.76 sec: 1.03x slower                                                  |
| tornado_http   | 97.7 ms                                                | 99.7 ms: 1.02x slower                                                   |
| Geometric mean | (ref)                                                  | 1.06x slower                                                            |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231030-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-bfdeb03 |
|----------------------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| async_tree_none            | 532 ms                                                 | 457 ms: 1.17x faster                                                    |
| async_tree_memoization     | 640 ms                                                 | 583 ms: 1.10x faster                                                    |
| async_tree_io              | 1.31 sec                                               | 1.21 sec: 1.08x faster                                                  |
| async_tree_none_tg         | 490 ms                                                 | 471 ms: 1.04x faster                                                    |
| async_tree_io_tg           | 1.30 sec                                               | 1.26 sec: 1.04x faster                                                  |
| async_tree_cpu_io_mixed    | 750 ms                                                 | 725 ms: 1.03x faster                                                    |
| async_tree_memoization_tg  | 627 ms                                                 | 612 ms: 1.02x faster                                                    |
| async_tree_cpu_io_mixed_tg | 764 ms                                                 | 756 ms: 1.01x faster                                                    |
| Geometric mean             | (ref)                                                  | 1.06x faster                                                            |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231030-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-bfdeb03 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| pidigits       | 190 ms                                                 | 189 ms: 1.01x faster                                                    |
| nbody          | 91.6 ms                                                | 112 ms: 1.23x slower                                                    |
| float          | 78.9 ms                                                | 97.8 ms: 1.24x slower                                                   |
| Geometric mean | (ref)                                                  | 1.15x slower                                                            |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231030-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-bfdeb03 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| regex_dna      | 204 ms                                                 | 208 ms: 1.02x slower                                                    |
| regex_effbot   | 3.45 ms                                                | 3.58 ms: 1.04x slower                                                   |
| regex_v8       | 22.9 ms                                                | 25.0 ms: 1.09x slower                                                   |
| regex_compile  | 141 ms                                                 | 156 ms: 1.11x slower                                                    |
| Geometric mean | (ref)                                                  | 1.06x slower                                                            |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231030-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-bfdeb03 |
|----------------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| json_dumps           | 13.5 ms                                                | 10.6 ms: 1.27x faster                                                   |
| unpickle_list        | 5.22 us                                                | 4.95 us: 1.05x faster                                                   |
| json_loads           | 29.4 us                                                | 28.2 us: 1.05x faster                                                   |
| pickle_pure_python   | 319 us                                                 | 307 us: 1.04x faster                                                    |
| xml_etree_parse      | 163 ms                                                 | 160 ms: 1.02x faster                                                    |
| unpickle_pure_python | 241 us                                                 | 244 us: 1.01x slower                                                    |
| tomli_loads          | 2.31 sec                                               | 2.35 sec: 1.01x slower                                                  |
| pickle_dict          | 34.8 us                                                | 35.4 us: 1.02x slower                                                   |
| pickle               | 11.1 us                                                | 11.6 us: 1.04x slower                                                   |
| xml_etree_iterparse  | 109 ms                                                 | 114 ms: 1.05x slower                                                    |
| xml_etree_process    | 56.5 ms                                                | 60.6 ms: 1.07x slower                                                   |
| xml_etree_generate   | 80.4 ms                                                | 88.7 ms: 1.10x slower                                                   |
| unpickle             | 13.9 us                                                | 15.5 us: 1.12x slower                                                   |
| pickle_list          | 4.65 us                                                | 5.22 us: 1.12x slower                                                   |
| Geometric mean       | (ref)                                                  | 1.01x slower                                                            |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231030-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-bfdeb03 |
|------------------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| python_startup_no_site | 6.09 ms                                                | 7.10 ms: 1.17x slower                                                   |
| python_startup         | 8.69 ms                                                | 10.4 ms: 1.19x slower                                                   |
| Geometric mean         | (ref)                                                  | 1.18x slower                                                            |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231030-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-bfdeb03 |
|-----------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| mako      | 10.8 ms                                                | 12.4 ms: 1.15x slower                                                   |

All benchmarks:
===============

| Benchmark                  | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231030-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-bfdeb03 |
|----------------------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| typing_runtime_protocols   | 521 us                                                 | 159 us: 3.27x faster                                                    |
| generators                 | 76.5 ms                                                | 29.4 ms: 2.60x faster                                                   |
| asyncio_tcp                | 887 ms                                                 | 485 ms: 1.83x faster                                                    |
| asyncio_tcp_ssl            | 3.13 sec                                               | 1.80 sec: 1.74x faster                                                  |
| json_dumps                 | 13.5 ms                                                | 10.6 ms: 1.27x faster                                                   |
| mypy2                      | 427 ms                                                 | 364 ms: 1.17x faster                                                    |
| async_tree_none            | 532 ms                                                 | 457 ms: 1.17x faster                                                    |
| coroutines                 | 26.1 ms                                                | 23.0 ms: 1.13x faster                                                   |
| richards_super             | 61.2 ms                                                | 55.5 ms: 1.10x faster                                                   |
| async_tree_memoization     | 640 ms                                                 | 583 ms: 1.10x faster                                                    |
| async_tree_io              | 1.31 sec                                               | 1.21 sec: 1.08x faster                                                  |
| sqlglot_parse              | 1.43 ms                                                | 1.34 ms: 1.07x faster                                                   |
| unpickle_list              | 5.22 us                                                | 4.95 us: 1.05x faster                                                   |
| sqlglot_transpile          | 1.75 ms                                                | 1.68 ms: 1.05x faster                                                   |
| json_loads                 | 29.4 us                                                | 28.2 us: 1.05x faster                                                   |
| async_tree_none_tg         | 490 ms                                                 | 471 ms: 1.04x faster                                                    |
| pickle_pure_python         | 319 us                                                 | 307 us: 1.04x faster                                                    |
| async_tree_io_tg           | 1.30 sec                                               | 1.26 sec: 1.04x faster                                                  |
| async_tree_cpu_io_mixed    | 750 ms                                                 | 725 ms: 1.03x faster                                                    |
| sympy_sum                  | 170 ms                                                 | 166 ms: 1.03x faster                                                    |
| async_tree_memoization_tg  | 627 ms                                                 | 612 ms: 1.02x faster                                                    |
| sqlglot_normalize          | 112 ms                                                 | 110 ms: 1.02x faster                                                    |
| xml_etree_parse            | 163 ms                                                 | 160 ms: 1.02x faster                                                    |
| sympy_expand               | 490 ms                                                 | 482 ms: 1.02x faster                                                    |
| async_tree_cpu_io_mixed_tg | 764 ms                                                 | 756 ms: 1.01x faster                                                    |
| json                       | 5.24 ms                                                | 5.18 ms: 1.01x faster                                                   |
| crypto_pyaes               | 77.5 ms                                                | 76.8 ms: 1.01x faster                                                   |
| pidigits                   | 190 ms                                                 | 189 ms: 1.01x faster                                                    |
| logging_simple             | 6.24 us                                                | 6.21 us: 1.01x faster                                                   |
| asyncio_websockets         | 556 ms                                                 | 553 ms: 1.01x faster                                                    |
| sqlglot_optimize           | 55.2 ms                                                | 55.4 ms: 1.00x slower                                                   |
| unpickle_pure_python       | 241 us                                                 | 244 us: 1.01x slower                                                    |
| tomli_loads                | 2.31 sec                                               | 2.35 sec: 1.01x slower                                                  |
| deepcopy                   | 360 us                                                 | 365 us: 1.01x slower                                                    |
| gc_traversal               | 3.90 ms                                                | 3.96 ms: 1.01x slower                                                   |
| pickle_dict                | 34.8 us                                                | 35.4 us: 1.02x slower                                                   |
| create_gc_cycles           | 1.48 ms                                                | 1.50 ms: 1.02x slower                                                   |
| richards                   | 48.9 ms                                                | 49.8 ms: 1.02x slower                                                   |
| deepcopy_reduce            | 3.14 us                                                | 3.20 us: 1.02x slower                                                   |
| regex_dna                  | 204 ms                                                 | 208 ms: 1.02x slower                                                    |
| tornado_http               | 97.7 ms                                                | 99.7 ms: 1.02x slower                                                   |
| bench_thread_pool          | 833 us                                                 | 850 us: 1.02x slower                                                    |
| mdp                        | 2.79 sec                                               | 2.85 sec: 1.02x slower                                                  |
| docutils                   | 2.69 sec                                               | 2.76 sec: 1.03x slower                                                  |
| pathlib                    | 18.5 ms                                                | 19.1 ms: 1.04x slower                                                   |
| regex_effbot               | 3.45 ms                                                | 3.58 ms: 1.04x slower                                                   |
| logging_silent             | 108 ns                                                 | 113 ns: 1.04x slower                                                    |
| pickle                     | 11.1 us                                                | 11.6 us: 1.04x slower                                                   |
| meteor_contest             | 109 ms                                                 | 114 ms: 1.05x slower                                                    |
| xml_etree_iterparse        | 109 ms                                                 | 114 ms: 1.05x slower                                                    |
| sympy_integrate            | 21.4 ms                                                | 22.5 ms: 1.05x slower                                                   |
| chaos                      | 71.4 ms                                                | 75.3 ms: 1.05x slower                                                   |
| scimark_lu                 | 112 ms                                                 | 119 ms: 1.06x slower                                                    |
| dulwich_log                | 64.9 ms                                                | 69.4 ms: 1.07x slower                                                   |
| xml_etree_process          | 56.5 ms                                                | 60.6 ms: 1.07x slower                                                   |
| scimark_sor                | 121 ms                                                 | 130 ms: 1.07x slower                                                    |
| scimark_monte_carlo        | 71.8 ms                                                | 77.0 ms: 1.07x slower                                                   |
| go                         | 143 ms                                                 | 155 ms: 1.08x slower                                                    |
| deltablue                  | 3.80 ms                                                | 4.14 ms: 1.09x slower                                                   |
| chameleon                  | 6.86 ms                                                | 7.47 ms: 1.09x slower                                                   |
| sqlite_synth               | 2.58 us                                                | 2.81 us: 1.09x slower                                                   |
| regex_v8                   | 22.9 ms                                                | 25.0 ms: 1.09x slower                                                   |
| xml_etree_generate         | 80.4 ms                                                | 88.7 ms: 1.10x slower                                                   |
| 2to3                       | 266 ms                                                 | 293 ms: 1.10x slower                                                    |
| regex_compile              | 141 ms                                                 | 156 ms: 1.11x slower                                                    |
| deepcopy_memo              | 38.9 us                                                | 43.2 us: 1.11x slower                                                   |
| unpickle                   | 13.9 us                                                | 15.5 us: 1.12x slower                                                   |
| scimark_sparse_mat_mult    | 4.80 ms                                                | 5.36 ms: 1.12x slower                                                   |
| nqueens                    | 86.8 ms                                                | 97.2 ms: 1.12x slower                                                   |
| scimark_fft                | 342 ms                                                 | 384 ms: 1.12x slower                                                    |
| pickle_list                | 4.65 us                                                | 5.22 us: 1.12x slower                                                   |
| fannkuch                   | 410 ms                                                 | 463 ms: 1.13x slower                                                    |
| unpack_sequence            | 43.3 ns                                                | 49.0 ns: 1.13x slower                                                   |
| spectral_norm              | 105 ms                                                 | 119 ms: 1.13x slower                                                    |
| comprehensions             | 23.6 us                                                | 26.9 us: 1.14x slower                                                   |
| mako                       | 10.8 ms                                                | 12.4 ms: 1.15x slower                                                   |
| pprint_safe_repr           | 743 ms                                                 | 860 ms: 1.16x slower                                                    |
| python_startup_no_site     | 6.09 ms                                                | 7.10 ms: 1.17x slower                                                   |
| coverage                   | 81.2 ms                                                | 95.9 ms: 1.18x slower                                                   |
| python_startup             | 8.69 ms                                                | 10.4 ms: 1.19x slower                                                   |
| pprint_pformat             | 1.53 sec                                               | 1.82 sec: 1.19x slower                                                  |
| nbody                      | 91.6 ms                                                | 112 ms: 1.23x slower                                                    |
| float                      | 78.9 ms                                                | 97.8 ms: 1.24x slower                                                   |
| pyflate                    | 426 ms                                                 | 537 ms: 1.26x slower                                                    |
| telco                      | 6.72 ms                                                | 8.50 ms: 1.26x slower                                                   |
| async_generators           | 375 ms                                                 | 478 ms: 1.27x slower                                                    |
| hexiom                     | 6.74 ms                                                | 9.49 ms: 1.41x slower                                                   |
| Geometric mean             | (ref)                                                  | 1.01x slower                                                            |

Benchmark hidden because not significant (5): sympy_str, logging_format, raytrace, bench_mp_pool, pycparser
Ignored benchmarks (13) of results/bm-20221024-3.11.0-deaf509/bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift


# HPT report

- Reliability score: 99.31% likely to be slow
- 90% likely to have a slowdown of 1.01x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
