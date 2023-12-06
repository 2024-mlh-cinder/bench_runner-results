
# Results vs. 3.11.0

- fork: brandtbucher
- ref: justin
- machine: linux-x86_64
- commit hash: 7a7e995
- commit date: 2023-11-15
- overall geometric mean: 1.03x faster \*
- HPT reliability: 69.95%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231115-linux-x86_64-brandtbucher-justin-3.13.0a1+-7a7e995 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| 2to3           | 266 ms                                                 | 272 ms: 1.02x slower                                           |
| chameleon      | 6.86 ms                                                | 7.34 ms: 1.07x slower                                          |
| docutils       | 2.69 sec                                               | 2.65 sec: 1.01x faster                                         |
| tornado_http   | 97.7 ms                                                | 96.5 ms: 1.01x faster                                          |
| Geometric mean | (ref)                                                  | 1.02x slower                                                   |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231115-linux-x86_64-brandtbucher-justin-3.13.0a1+-7a7e995 |
|----------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| async_tree_none            | 532 ms                                                 | 442 ms: 1.20x faster                                           |
| async_tree_memoization     | 640 ms                                                 | 569 ms: 1.12x faster                                           |
| async_tree_io              | 1.31 sec                                               | 1.20 sec: 1.09x faster                                         |
| async_tree_none_tg         | 490 ms                                                 | 461 ms: 1.06x faster                                           |
| async_tree_io_tg           | 1.30 sec                                               | 1.23 sec: 1.06x faster                                         |
| async_tree_cpu_io_mixed    | 750 ms                                                 | 715 ms: 1.05x faster                                           |
| async_tree_memoization_tg  | 627 ms                                                 | 603 ms: 1.04x faster                                           |
| async_tree_cpu_io_mixed_tg | 764 ms                                                 | 744 ms: 1.03x faster                                           |
| Geometric mean             | (ref)                                                  | 1.08x faster                                                   |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231115-linux-x86_64-brandtbucher-justin-3.13.0a1+-7a7e995 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| pidigits       | 190 ms                                                 | 195 ms: 1.03x slower                                           |
| nbody          | 91.6 ms                                                | 97.3 ms: 1.06x slower                                          |
| float          | 78.9 ms                                                | 86.5 ms: 1.10x slower                                          |
| Geometric mean | (ref)                                                  | 1.06x slower                                                   |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231115-linux-x86_64-brandtbucher-justin-3.13.0a1+-7a7e995 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| regex_compile  | 141 ms                                                 | 141 ms: 1.00x faster                                           |
| regex_effbot   | 3.45 ms                                                | 3.56 ms: 1.03x slower                                          |
| regex_dna      | 204 ms                                                 | 214 ms: 1.05x slower                                           |
| regex_v8       | 22.9 ms                                                | 25.7 ms: 1.12x slower                                          |
| Geometric mean | (ref)                                                  | 1.05x slower                                                   |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231115-linux-x86_64-brandtbucher-justin-3.13.0a1+-7a7e995 |
|----------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| json_dumps           | 13.5 ms                                                | 10.6 ms: 1.27x faster                                          |
| pickle_pure_python   | 319 us                                                 | 305 us: 1.05x faster                                           |
| unpickle_pure_python | 241 us                                                 | 231 us: 1.04x faster                                           |
| json_loads           | 29.4 us                                                | 28.2 us: 1.04x faster                                          |
| tomli_loads          | 2.31 sec                                               | 2.23 sec: 1.04x faster                                         |
| xml_etree_parse      | 163 ms                                                 | 158 ms: 1.03x faster                                           |
| pickle_dict          | 34.8 us                                                | 34.2 us: 1.02x faster                                          |
| unpickle_list        | 5.22 us                                                | 5.36 us: 1.03x slower                                          |
| pickle_list          | 4.65 us                                                | 4.90 us: 1.05x slower                                          |
| xml_etree_process    | 56.5 ms                                                | 60.0 ms: 1.06x slower                                          |
| unpickle             | 13.9 us                                                | 14.9 us: 1.08x slower                                          |
| xml_etree_generate   | 80.4 ms                                                | 87.8 ms: 1.09x slower                                          |
| Geometric mean       | (ref)                                                  | 1.01x faster                                                   |

Benchmark hidden because not significant (2): xml_etree_iterparse, pickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231115-linux-x86_64-brandtbucher-justin-3.13.0a1+-7a7e995 |
|------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| python_startup         | 8.69 ms                                                | 10.4 ms: 1.20x slower                                          |
| python_startup_no_site | 6.09 ms                                                | 9.10 ms: 1.49x slower                                          |
| Geometric mean         | (ref)                                                  | 1.34x slower                                                   |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231115-linux-x86_64-brandtbucher-justin-3.13.0a1+-7a7e995 |
|-----------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| mako      | 10.8 ms                                                | 12.3 ms: 1.13x slower                                          |

All benchmarks:
===============

| Benchmark                  | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231115-linux-x86_64-brandtbucher-justin-3.13.0a1+-7a7e995 |
|----------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| typing_runtime_protocols   | 521 us                                                 | 122 us: 4.29x faster                                           |
| generators                 | 76.5 ms                                                | 29.2 ms: 2.62x faster                                          |
| asyncio_tcp                | 887 ms                                                 | 496 ms: 1.79x faster                                           |
| asyncio_tcp_ssl            | 3.13 sec                                               | 1.80 sec: 1.74x faster                                         |
| json_dumps                 | 13.5 ms                                                | 10.6 ms: 1.27x faster                                          |
| mypy2                      | 427 ms                                                 | 350 ms: 1.22x faster                                           |
| comprehensions             | 23.6 us                                                | 19.3 us: 1.22x faster                                          |
| async_tree_none            | 532 ms                                                 | 442 ms: 1.20x faster                                           |
| coroutines                 | 26.1 ms                                                | 21.9 ms: 1.20x faster                                          |
| richards_super             | 61.2 ms                                                | 52.8 ms: 1.16x faster                                          |
| sympy_sum                  | 170 ms                                                 | 150 ms: 1.13x faster                                           |
| async_tree_memoization     | 640 ms                                                 | 569 ms: 1.12x faster                                           |
| sqlglot_parse              | 1.43 ms                                                | 1.30 ms: 1.10x faster                                          |
| sympy_str                  | 299 ms                                                 | 273 ms: 1.09x faster                                           |
| async_tree_io              | 1.31 sec                                               | 1.20 sec: 1.09x faster                                         |
| chaos                      | 71.4 ms                                                | 65.8 ms: 1.09x faster                                          |
| sqlglot_transpile          | 1.75 ms                                                | 1.62 ms: 1.08x faster                                          |
| raytrace                   | 306 ms                                                 | 287 ms: 1.07x faster                                           |
| logging_simple             | 6.24 us                                                | 5.85 us: 1.07x faster                                          |
| async_tree_none_tg         | 490 ms                                                 | 461 ms: 1.06x faster                                           |
| mdp                        | 2.79 sec                                               | 2.63 sec: 1.06x faster                                         |
| async_tree_io_tg           | 1.30 sec                                               | 1.23 sec: 1.06x faster                                         |
| sympy_expand               | 490 ms                                                 | 463 ms: 1.06x faster                                           |
| logging_format             | 6.83 us                                                | 6.46 us: 1.06x faster                                          |
| sqlglot_normalize          | 112 ms                                                 | 107 ms: 1.05x faster                                           |
| async_tree_cpu_io_mixed    | 750 ms                                                 | 715 ms: 1.05x faster                                           |
| pickle_pure_python         | 319 us                                                 | 305 us: 1.05x faster                                           |
| unpickle_pure_python       | 241 us                                                 | 231 us: 1.04x faster                                           |
| json_loads                 | 29.4 us                                                | 28.2 us: 1.04x faster                                          |
| richards                   | 48.9 ms                                                | 46.9 ms: 1.04x faster                                          |
| sympy_integrate            | 21.4 ms                                                | 20.5 ms: 1.04x faster                                          |
| async_tree_memoization_tg  | 627 ms                                                 | 603 ms: 1.04x faster                                           |
| tomli_loads                | 2.31 sec                                               | 2.23 sec: 1.04x faster                                         |
| async_tree_cpu_io_mixed_tg | 764 ms                                                 | 744 ms: 1.03x faster                                           |
| xml_etree_parse            | 163 ms                                                 | 158 ms: 1.03x faster                                           |
| gc_traversal               | 3.90 ms                                                | 3.82 ms: 1.02x faster                                          |
| deepcopy                   | 360 us                                                 | 353 us: 1.02x faster                                           |
| sqlglot_optimize           | 55.2 ms                                                | 54.1 ms: 1.02x faster                                          |
| pickle_dict                | 34.8 us                                                | 34.2 us: 1.02x faster                                          |
| docutils                   | 2.69 sec                                               | 2.65 sec: 1.01x faster                                         |
| tornado_http               | 97.7 ms                                                | 96.5 ms: 1.01x faster                                          |
| logging_silent             | 108 ns                                                 | 107 ns: 1.01x faster                                           |
| json                       | 5.24 ms                                                | 5.18 ms: 1.01x faster                                          |
| asyncio_websockets         | 556 ms                                                 | 552 ms: 1.01x faster                                           |
| crypto_pyaes               | 77.5 ms                                                | 77.1 ms: 1.01x faster                                          |
| regex_compile              | 141 ms                                                 | 141 ms: 1.00x faster                                           |
| create_gc_cycles           | 1.48 ms                                                | 1.48 ms: 1.01x slower                                          |
| meteor_contest             | 109 ms                                                 | 110 ms: 1.01x slower                                           |
| pycparser                  | 1.20 sec                                               | 1.21 sec: 1.01x slower                                         |
| bench_thread_pool          | 833 us                                                 | 845 us: 1.01x slower                                           |
| scimark_sor                | 121 ms                                                 | 124 ms: 1.02x slower                                           |
| 2to3                       | 266 ms                                                 | 272 ms: 1.02x slower                                           |
| pidigits                   | 190 ms                                                 | 195 ms: 1.03x slower                                           |
| dulwich_log                | 64.9 ms                                                | 66.6 ms: 1.03x slower                                          |
| unpickle_list              | 5.22 us                                                | 5.36 us: 1.03x slower                                          |
| deepcopy_memo              | 38.9 us                                                | 40.1 us: 1.03x slower                                          |
| scimark_monte_carlo        | 71.8 ms                                                | 74.0 ms: 1.03x slower                                          |
| regex_effbot               | 3.45 ms                                                | 3.56 ms: 1.03x slower                                          |
| go                         | 143 ms                                                 | 149 ms: 1.05x slower                                           |
| scimark_lu                 | 112 ms                                                 | 118 ms: 1.05x slower                                           |
| nqueens                    | 86.8 ms                                                | 90.9 ms: 1.05x slower                                          |
| spectral_norm              | 105 ms                                                 | 110 ms: 1.05x slower                                           |
| regex_dna                  | 204 ms                                                 | 214 ms: 1.05x slower                                           |
| fannkuch                   | 410 ms                                                 | 430 ms: 1.05x slower                                           |
| deltablue                  | 3.80 ms                                                | 4.00 ms: 1.05x slower                                          |
| pickle_list                | 4.65 us                                                | 4.90 us: 1.05x slower                                          |
| pprint_pformat             | 1.53 sec                                               | 1.62 sec: 1.06x slower                                         |
| xml_etree_process          | 56.5 ms                                                | 60.0 ms: 1.06x slower                                          |
| nbody                      | 91.6 ms                                                | 97.3 ms: 1.06x slower                                          |
| chameleon                  | 6.86 ms                                                | 7.34 ms: 1.07x slower                                          |
| pprint_safe_repr           | 743 ms                                                 | 798 ms: 1.07x slower                                           |
| unpickle                   | 13.9 us                                                | 14.9 us: 1.08x slower                                          |
| sqlite_synth               | 2.58 us                                                | 2.80 us: 1.09x slower                                          |
| xml_etree_generate         | 80.4 ms                                                | 87.8 ms: 1.09x slower                                          |
| float                      | 78.9 ms                                                | 86.5 ms: 1.10x slower                                          |
| scimark_fft                | 342 ms                                                 | 383 ms: 1.12x slower                                           |
| regex_v8                   | 22.9 ms                                                | 25.7 ms: 1.12x slower                                          |
| hexiom                     | 6.74 ms                                                | 7.59 ms: 1.13x slower                                          |
| mako                       | 10.8 ms                                                | 12.3 ms: 1.13x slower                                          |
| scimark_sparse_mat_mult    | 4.80 ms                                                | 5.45 ms: 1.14x slower                                          |
| unpack_sequence            | 43.3 ns                                                | 49.9 ns: 1.15x slower                                          |
| coverage                   | 81.2 ms                                                | 94.7 ms: 1.17x slower                                          |
| python_startup             | 8.69 ms                                                | 10.4 ms: 1.20x slower                                          |
| pyflate                    | 426 ms                                                 | 513 ms: 1.20x slower                                           |
| async_generators           | 375 ms                                                 | 461 ms: 1.23x slower                                           |
| telco                      | 6.72 ms                                                | 8.44 ms: 1.26x slower                                          |
| python_startup_no_site     | 6.09 ms                                                | 9.10 ms: 1.49x slower                                          |
| Geometric mean             | (ref)                                                  | 1.03x faster                                                   |

Benchmark hidden because not significant (6): xml_etree_iterparse, dask, deepcopy_reduce, pathlib, bench_mp_pool, pickle
Ignored benchmarks (12) of results/bm-20221024-3.11.0-deaf509/bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift


# HPT report

- Reliability score: 69.95% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
