
# Results vs. 3.11.0

- fork: brandtbucher
- ref: justin_no_ghccc
- machine: linux-x86_64
- commit hash: fb676a6
- commit date: 2023-11-08
- overall geometric mean: 1.03x faster \*
- HPT reliability: 76.44%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231108-linux-x86_64-brandtbucher-justin_no_ghccc-3.13.0a1+-fb676a6 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| 2to3           | 266 ms                                                 | 273 ms: 1.03x slower                                                    |
| chameleon      | 6.86 ms                                                | 7.32 ms: 1.07x slower                                                   |
| docutils       | 2.69 sec                                               | 2.65 sec: 1.02x faster                                                  |
| tornado_http   | 97.7 ms                                                | 96.8 ms: 1.01x faster                                                   |
| Geometric mean | (ref)                                                  | 1.02x slower                                                            |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231108-linux-x86_64-brandtbucher-justin_no_ghccc-3.13.0a1+-fb676a6 |
|----------------------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| async_tree_none            | 532 ms                                                 | 447 ms: 1.19x faster                                                    |
| async_tree_memoization     | 640 ms                                                 | 567 ms: 1.13x faster                                                    |
| async_tree_io              | 1.31 sec                                               | 1.18 sec: 1.11x faster                                                  |
| async_tree_none_tg         | 490 ms                                                 | 456 ms: 1.07x faster                                                    |
| async_tree_io_tg           | 1.30 sec                                               | 1.22 sec: 1.07x faster                                                  |
| async_tree_memoization_tg  | 627 ms                                                 | 598 ms: 1.05x faster                                                    |
| async_tree_cpu_io_mixed    | 750 ms                                                 | 724 ms: 1.04x faster                                                    |
| async_tree_cpu_io_mixed_tg | 764 ms                                                 | 745 ms: 1.03x faster                                                    |
| Geometric mean             | (ref)                                                  | 1.08x faster                                                            |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231108-linux-x86_64-brandtbucher-justin_no_ghccc-3.13.0a1+-fb676a6 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| pidigits       | 190 ms                                                 | 188 ms: 1.01x faster                                                    |
| float          | 78.9 ms                                                | 86.8 ms: 1.10x slower                                                   |
| nbody          | 91.6 ms                                                | 103 ms: 1.12x slower                                                    |
| Geometric mean | (ref)                                                  | 1.07x slower                                                            |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231108-linux-x86_64-brandtbucher-justin_no_ghccc-3.13.0a1+-fb676a6 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| regex_dna      | 204 ms                                                 | 215 ms: 1.05x slower                                                    |
| regex_effbot   | 3.45 ms                                                | 3.77 ms: 1.09x slower                                                   |
| regex_v8       | 22.9 ms                                                | 25.4 ms: 1.11x slower                                                   |
| Geometric mean | (ref)                                                  | 1.06x slower                                                            |

Benchmark hidden because not significant (1): regex_compile

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231108-linux-x86_64-brandtbucher-justin_no_ghccc-3.13.0a1+-fb676a6 |
|----------------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| json_dumps           | 13.5 ms                                                | 10.6 ms: 1.27x faster                                                   |
| tomli_loads          | 2.31 sec                                               | 2.16 sec: 1.07x faster                                                  |
| json_loads           | 29.4 us                                                | 27.7 us: 1.06x faster                                                   |
| pickle_pure_python   | 319 us                                                 | 303 us: 1.05x faster                                                    |
| pickle_dict          | 34.8 us                                                | 33.3 us: 1.04x faster                                                   |
| unpickle_pure_python | 241 us                                                 | 231 us: 1.04x faster                                                    |
| unpickle_list        | 5.22 us                                                | 5.07 us: 1.03x faster                                                   |
| xml_etree_parse      | 163 ms                                                 | 159 ms: 1.02x faster                                                    |
| pickle_list          | 4.65 us                                                | 4.83 us: 1.04x slower                                                   |
| pickle               | 11.1 us                                                | 11.6 us: 1.05x slower                                                   |
| xml_etree_process    | 56.5 ms                                                | 60.0 ms: 1.06x slower                                                   |
| xml_etree_generate   | 80.4 ms                                                | 87.1 ms: 1.08x slower                                                   |
| unpickle             | 13.9 us                                                | 15.1 us: 1.09x slower                                                   |
| Geometric mean       | (ref)                                                  | 1.02x faster                                                            |

Benchmark hidden because not significant (1): xml_etree_iterparse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231108-linux-x86_64-brandtbucher-justin_no_ghccc-3.13.0a1+-fb676a6 |
|------------------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| python_startup         | 8.69 ms                                                | 10.4 ms: 1.20x slower                                                   |
| python_startup_no_site | 6.09 ms                                                | 9.12 ms: 1.50x slower                                                   |
| Geometric mean         | (ref)                                                  | 1.34x slower                                                            |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231108-linux-x86_64-brandtbucher-justin_no_ghccc-3.13.0a1+-fb676a6 |
|-----------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| mako      | 10.8 ms                                                | 12.1 ms: 1.12x slower                                                   |

All benchmarks:
===============

| Benchmark                  | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231108-linux-x86_64-brandtbucher-justin_no_ghccc-3.13.0a1+-fb676a6 |
|----------------------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| typing_runtime_protocols   | 521 us                                                 | 119 us: 4.38x faster                                                    |
| generators                 | 76.5 ms                                                | 29.8 ms: 2.57x faster                                                   |
| asyncio_tcp                | 887 ms                                                 | 487 ms: 1.82x faster                                                    |
| asyncio_tcp_ssl            | 3.13 sec                                               | 1.80 sec: 1.74x faster                                                  |
| json_dumps                 | 13.5 ms                                                | 10.6 ms: 1.27x faster                                                   |
| mypy2                      | 427 ms                                                 | 350 ms: 1.22x faster                                                    |
| comprehensions             | 23.6 us                                                | 19.7 us: 1.20x faster                                                   |
| async_tree_none            | 532 ms                                                 | 447 ms: 1.19x faster                                                    |
| coroutines                 | 26.1 ms                                                | 22.5 ms: 1.16x faster                                                   |
| richards_super             | 61.2 ms                                                | 53.7 ms: 1.14x faster                                                   |
| async_tree_memoization     | 640 ms                                                 | 567 ms: 1.13x faster                                                    |
| sympy_sum                  | 170 ms                                                 | 153 ms: 1.12x faster                                                    |
| async_tree_io              | 1.31 sec                                               | 1.18 sec: 1.11x faster                                                  |
| sqlglot_parse              | 1.43 ms                                                | 1.30 ms: 1.11x faster                                                   |
| sympy_str                  | 299 ms                                                 | 274 ms: 1.09x faster                                                    |
| chaos                      | 71.4 ms                                                | 65.5 ms: 1.09x faster                                                   |
| logging_simple             | 6.24 us                                                | 5.75 us: 1.09x faster                                                   |
| sqlglot_transpile          | 1.75 ms                                                | 1.63 ms: 1.08x faster                                                   |
| raytrace                   | 306 ms                                                 | 284 ms: 1.08x faster                                                    |
| logging_format             | 6.83 us                                                | 6.35 us: 1.08x faster                                                   |
| async_tree_none_tg         | 490 ms                                                 | 456 ms: 1.07x faster                                                    |
| tomli_loads                | 2.31 sec                                               | 2.16 sec: 1.07x faster                                                  |
| async_tree_io_tg           | 1.30 sec                                               | 1.22 sec: 1.07x faster                                                  |
| sympy_expand               | 490 ms                                                 | 460 ms: 1.06x faster                                                    |
| gc_traversal               | 3.90 ms                                                | 3.67 ms: 1.06x faster                                                   |
| sqlglot_normalize          | 112 ms                                                 | 106 ms: 1.06x faster                                                    |
| json_loads                 | 29.4 us                                                | 27.7 us: 1.06x faster                                                   |
| mdp                        | 2.79 sec                                               | 2.64 sec: 1.06x faster                                                  |
| pickle_pure_python         | 319 us                                                 | 303 us: 1.05x faster                                                    |
| async_tree_memoization_tg  | 627 ms                                                 | 598 ms: 1.05x faster                                                    |
| unpack_sequence            | 43.3 ns                                                | 41.4 ns: 1.05x faster                                                   |
| pickle_dict                | 34.8 us                                                | 33.3 us: 1.04x faster                                                   |
| unpickle_pure_python       | 241 us                                                 | 231 us: 1.04x faster                                                    |
| sympy_integrate            | 21.4 ms                                                | 20.6 ms: 1.04x faster                                                   |
| async_tree_cpu_io_mixed    | 750 ms                                                 | 724 ms: 1.04x faster                                                    |
| richards                   | 48.9 ms                                                | 47.3 ms: 1.03x faster                                                   |
| unpickle_list              | 5.22 us                                                | 5.07 us: 1.03x faster                                                   |
| async_tree_cpu_io_mixed_tg | 764 ms                                                 | 745 ms: 1.03x faster                                                    |
| pycparser                  | 1.20 sec                                               | 1.17 sec: 1.02x faster                                                  |
| xml_etree_parse            | 163 ms                                                 | 159 ms: 1.02x faster                                                    |
| logging_silent             | 108 ns                                                 | 106 ns: 1.02x faster                                                    |
| sqlglot_optimize           | 55.2 ms                                                | 54.3 ms: 1.02x faster                                                   |
| docutils                   | 2.69 sec                                               | 2.65 sec: 1.02x faster                                                  |
| deepcopy                   | 360 us                                                 | 355 us: 1.01x faster                                                    |
| pidigits                   | 190 ms                                                 | 188 ms: 1.01x faster                                                    |
| json                       | 5.24 ms                                                | 5.16 ms: 1.01x faster                                                   |
| tornado_http               | 97.7 ms                                                | 96.8 ms: 1.01x faster                                                   |
| asyncio_websockets         | 556 ms                                                 | 552 ms: 1.01x faster                                                    |
| create_gc_cycles           | 1.48 ms                                                | 1.47 ms: 1.01x faster                                                   |
| deepcopy_reduce            | 3.14 us                                                | 3.16 us: 1.01x slower                                                   |
| crypto_pyaes               | 77.5 ms                                                | 78.2 ms: 1.01x slower                                                   |
| bench_thread_pool          | 833 us                                                 | 850 us: 1.02x slower                                                    |
| scimark_monte_carlo        | 71.8 ms                                                | 73.5 ms: 1.02x slower                                                   |
| dulwich_log                | 64.9 ms                                                | 66.6 ms: 1.03x slower                                                   |
| 2to3                       | 266 ms                                                 | 273 ms: 1.03x slower                                                    |
| deltablue                  | 3.80 ms                                                | 3.94 ms: 1.03x slower                                                   |
| fannkuch                   | 410 ms                                                 | 424 ms: 1.04x slower                                                    |
| go                         | 143 ms                                                 | 148 ms: 1.04x slower                                                    |
| pickle_list                | 4.65 us                                                | 4.83 us: 1.04x slower                                                   |
| meteor_contest             | 109 ms                                                 | 113 ms: 1.04x slower                                                    |
| scimark_sor                | 121 ms                                                 | 126 ms: 1.04x slower                                                    |
| pickle                     | 11.1 us                                                | 11.6 us: 1.05x slower                                                   |
| pathlib                    | 18.5 ms                                                | 19.3 ms: 1.05x slower                                                   |
| pprint_safe_repr           | 743 ms                                                 | 778 ms: 1.05x slower                                                    |
| deepcopy_memo              | 38.9 us                                                | 40.8 us: 1.05x slower                                                   |
| pprint_pformat             | 1.53 sec                                               | 1.60 sec: 1.05x slower                                                  |
| nqueens                    | 86.8 ms                                                | 91.4 ms: 1.05x slower                                                   |
| regex_dna                  | 204 ms                                                 | 215 ms: 1.05x slower                                                    |
| xml_etree_process          | 56.5 ms                                                | 60.0 ms: 1.06x slower                                                   |
| chameleon                  | 6.86 ms                                                | 7.32 ms: 1.07x slower                                                   |
| spectral_norm              | 105 ms                                                 | 112 ms: 1.07x slower                                                    |
| scimark_lu                 | 112 ms                                                 | 120 ms: 1.07x slower                                                    |
| sqlite_synth               | 2.58 us                                                | 2.79 us: 1.08x slower                                                   |
| xml_etree_generate         | 80.4 ms                                                | 87.1 ms: 1.08x slower                                                   |
| unpickle                   | 13.9 us                                                | 15.1 us: 1.09x slower                                                   |
| regex_effbot               | 3.45 ms                                                | 3.77 ms: 1.09x slower                                                   |
| float                      | 78.9 ms                                                | 86.8 ms: 1.10x slower                                                   |
| regex_v8                   | 22.9 ms                                                | 25.4 ms: 1.11x slower                                                   |
| hexiom                     | 6.74 ms                                                | 7.51 ms: 1.11x slower                                                   |
| mako                       | 10.8 ms                                                | 12.1 ms: 1.12x slower                                                   |
| nbody                      | 91.6 ms                                                | 103 ms: 1.12x slower                                                    |
| scimark_fft                | 342 ms                                                 | 385 ms: 1.12x slower                                                    |
| scimark_sparse_mat_mult    | 4.80 ms                                                | 5.50 ms: 1.15x slower                                                   |
| pyflate                    | 426 ms                                                 | 497 ms: 1.17x slower                                                    |
| coverage                   | 81.2 ms                                                | 96.0 ms: 1.18x slower                                                   |
| python_startup             | 8.69 ms                                                | 10.4 ms: 1.20x slower                                                   |
| async_generators           | 375 ms                                                 | 465 ms: 1.24x slower                                                    |
| telco                      | 6.72 ms                                                | 9.01 ms: 1.34x slower                                                   |
| python_startup_no_site     | 6.09 ms                                                | 9.12 ms: 1.50x slower                                                   |
| Geometric mean             | (ref)                                                  | 1.03x faster                                                            |

Benchmark hidden because not significant (3): xml_etree_iterparse, bench_mp_pool, regex_compile
Ignored benchmarks (13) of results/bm-20221024-3.11.0-deaf509/bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift


# HPT report

- Reliability score: 76.44% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
