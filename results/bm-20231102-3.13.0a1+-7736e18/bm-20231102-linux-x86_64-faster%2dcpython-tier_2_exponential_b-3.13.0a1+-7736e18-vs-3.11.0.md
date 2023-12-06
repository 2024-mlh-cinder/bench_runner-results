
# Results vs. 3.11.0

- fork: faster-cpython
- ref: tier_2_exponential_b
- machine: linux-x86_64
- commit hash: 7736e18
- commit date: 2023-11-02
- overall geometric mean: 1.01x faster \*
- HPT reliability: 89.29%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231102-linux-x86_64-faster%2dcpython-tier_2_exponential_b-3.13.0a1+-7736e18 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| 2to3           | 266 ms                                                 | 279 ms: 1.05x slower                                                             |
| chameleon      | 6.86 ms                                                | 7.09 ms: 1.03x slower                                                            |
| docutils       | 2.69 sec                                               | 2.71 sec: 1.01x slower                                                           |
| Geometric mean | (ref)                                                  | 1.02x slower                                                                     |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231102-linux-x86_64-faster%2dcpython-tier_2_exponential_b-3.13.0a1+-7736e18 |
|----------------------------|:------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| async_tree_none            | 532 ms                                                 | 452 ms: 1.18x faster                                                             |
| async_tree_memoization     | 640 ms                                                 | 579 ms: 1.10x faster                                                             |
| async_tree_io              | 1.31 sec                                               | 1.21 sec: 1.08x faster                                                           |
| async_tree_none_tg         | 490 ms                                                 | 469 ms: 1.04x faster                                                             |
| async_tree_io_tg           | 1.30 sec                                               | 1.25 sec: 1.04x faster                                                           |
| async_tree_cpu_io_mixed    | 750 ms                                                 | 725 ms: 1.03x faster                                                             |
| async_tree_memoization_tg  | 627 ms                                                 | 612 ms: 1.02x faster                                                             |
| async_tree_cpu_io_mixed_tg | 764 ms                                                 | 753 ms: 1.01x faster                                                             |
| Geometric mean             | (ref)                                                  | 1.06x faster                                                                     |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231102-linux-x86_64-faster%2dcpython-tier_2_exponential_b-3.13.0a1+-7736e18 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| pidigits       | 190 ms                                                 | 196 ms: 1.03x slower                                                             |
| nbody          | 91.6 ms                                                | 110 ms: 1.20x slower                                                             |
| float          | 78.9 ms                                                | 96.2 ms: 1.22x slower                                                            |
| Geometric mean | (ref)                                                  | 1.15x slower                                                                     |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231102-linux-x86_64-faster%2dcpython-tier_2_exponential_b-3.13.0a1+-7736e18 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| regex_dna      | 204 ms                                                 | 211 ms: 1.04x slower                                                             |
| regex_effbot   | 3.45 ms                                                | 3.73 ms: 1.08x slower                                                            |
| regex_compile  | 141 ms                                                 | 157 ms: 1.11x slower                                                             |
| regex_v8       | 22.9 ms                                                | 25.7 ms: 1.12x slower                                                            |
| Geometric mean | (ref)                                                  | 1.09x slower                                                                     |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231102-linux-x86_64-faster%2dcpython-tier_2_exponential_b-3.13.0a1+-7736e18 |
|----------------------|:------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| json_dumps           | 13.5 ms                                                | 10.7 ms: 1.26x faster                                                            |
| pickle_dict          | 34.8 us                                                | 32.7 us: 1.07x faster                                                            |
| json_loads           | 29.4 us                                                | 27.7 us: 1.06x faster                                                            |
| pickle_pure_python   | 319 us                                                 | 310 us: 1.03x faster                                                             |
| unpickle_list        | 5.22 us                                                | 5.09 us: 1.03x faster                                                            |
| xml_etree_parse      | 163 ms                                                 | 159 ms: 1.02x faster                                                             |
| unpickle_pure_python | 241 us                                                 | 239 us: 1.01x faster                                                             |
| pickle               | 11.1 us                                                | 11.2 us: 1.01x slower                                                            |
| xml_etree_iterparse  | 109 ms                                                 | 111 ms: 1.02x slower                                                             |
| xml_etree_process    | 56.5 ms                                                | 59.9 ms: 1.06x slower                                                            |
| unpickle             | 13.9 us                                                | 14.9 us: 1.07x slower                                                            |
| tomli_loads          | 2.31 sec                                               | 2.49 sec: 1.07x slower                                                           |
| xml_etree_generate   | 80.4 ms                                                | 87.0 ms: 1.08x slower                                                            |
| pickle_list          | 4.65 us                                                | 5.10 us: 1.10x slower                                                            |
| Geometric mean       | (ref)                                                  | 1.00x faster                                                                     |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231102-linux-x86_64-faster%2dcpython-tier_2_exponential_b-3.13.0a1+-7736e18 |
|------------------------|:------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| python_startup         | 8.69 ms                                                | 10.3 ms: 1.19x slower                                                            |
| python_startup_no_site | 6.09 ms                                                | 9.00 ms: 1.48x slower                                                            |
| Geometric mean         | (ref)                                                  | 1.32x slower                                                                     |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231102-linux-x86_64-faster%2dcpython-tier_2_exponential_b-3.13.0a1+-7736e18 |
|-----------|:------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| mako      | 10.8 ms                                                | 14.0 ms: 1.29x slower                                                            |

All benchmarks:
===============

| Benchmark                  | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231102-linux-x86_64-faster%2dcpython-tier_2_exponential_b-3.13.0a1+-7736e18 |
|----------------------------|:------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| typing_runtime_protocols   | 521 us                                                 | 125 us: 4.19x faster                                                             |
| generators                 | 76.5 ms                                                | 29.6 ms: 2.58x faster                                                            |
| asyncio_tcp                | 887 ms                                                 | 493 ms: 1.80x faster                                                             |
| asyncio_tcp_ssl            | 3.13 sec                                               | 1.80 sec: 1.74x faster                                                           |
| json_dumps                 | 13.5 ms                                                | 10.7 ms: 1.26x faster                                                            |
| mypy2                      | 427 ms                                                 | 354 ms: 1.21x faster                                                             |
| async_tree_none            | 532 ms                                                 | 452 ms: 1.18x faster                                                             |
| coroutines                 | 26.1 ms                                                | 22.3 ms: 1.17x faster                                                            |
| sympy_sum                  | 170 ms                                                 | 153 ms: 1.11x faster                                                             |
| async_tree_memoization     | 640 ms                                                 | 579 ms: 1.10x faster                                                             |
| gc_traversal               | 3.90 ms                                                | 3.57 ms: 1.09x faster                                                            |
| async_tree_io              | 1.31 sec                                               | 1.21 sec: 1.08x faster                                                           |
| sqlglot_parse              | 1.43 ms                                                | 1.34 ms: 1.07x faster                                                            |
| pickle_dict                | 34.8 us                                                | 32.7 us: 1.07x faster                                                            |
| sympy_str                  | 299 ms                                                 | 281 ms: 1.06x faster                                                             |
| richards_super             | 61.2 ms                                                | 57.6 ms: 1.06x faster                                                            |
| json_loads                 | 29.4 us                                                | 27.7 us: 1.06x faster                                                            |
| comprehensions             | 23.6 us                                                | 22.2 us: 1.06x faster                                                            |
| raytrace                   | 306 ms                                                 | 289 ms: 1.06x faster                                                             |
| logging_format             | 6.83 us                                                | 6.45 us: 1.06x faster                                                            |
| logging_simple             | 6.24 us                                                | 5.94 us: 1.05x faster                                                            |
| sqlglot_normalize          | 112 ms                                                 | 107 ms: 1.05x faster                                                             |
| sqlglot_transpile          | 1.75 ms                                                | 1.67 ms: 1.05x faster                                                            |
| chaos                      | 71.4 ms                                                | 68.2 ms: 1.05x faster                                                            |
| async_tree_none_tg         | 490 ms                                                 | 469 ms: 1.04x faster                                                             |
| async_tree_io_tg           | 1.30 sec                                               | 1.25 sec: 1.04x faster                                                           |
| async_tree_cpu_io_mixed    | 750 ms                                                 | 725 ms: 1.03x faster                                                             |
| sympy_expand               | 490 ms                                                 | 476 ms: 1.03x faster                                                             |
| pickle_pure_python         | 319 us                                                 | 310 us: 1.03x faster                                                             |
| deepcopy_reduce            | 3.14 us                                                | 3.05 us: 1.03x faster                                                            |
| crypto_pyaes               | 77.5 ms                                                | 75.5 ms: 1.03x faster                                                            |
| unpickle_list              | 5.22 us                                                | 5.09 us: 1.03x faster                                                            |
| xml_etree_parse            | 163 ms                                                 | 159 ms: 1.02x faster                                                             |
| async_tree_memoization_tg  | 627 ms                                                 | 612 ms: 1.02x faster                                                             |
| deepcopy                   | 360 us                                                 | 353 us: 1.02x faster                                                             |
| sympy_integrate            | 21.4 ms                                                | 21.0 ms: 1.02x faster                                                            |
| json                       | 5.24 ms                                                | 5.15 ms: 1.02x faster                                                            |
| async_tree_cpu_io_mixed_tg | 764 ms                                                 | 753 ms: 1.01x faster                                                             |
| sqlglot_optimize           | 55.2 ms                                                | 54.5 ms: 1.01x faster                                                            |
| unpickle_pure_python       | 241 us                                                 | 239 us: 1.01x faster                                                             |
| create_gc_cycles           | 1.48 ms                                                | 1.47 ms: 1.01x faster                                                            |
| asyncio_websockets         | 556 ms                                                 | 552 ms: 1.01x faster                                                             |
| bench_thread_pool          | 833 us                                                 | 835 us: 1.00x slower                                                             |
| docutils                   | 2.69 sec                                               | 2.71 sec: 1.01x slower                                                           |
| pickle                     | 11.1 us                                                | 11.2 us: 1.01x slower                                                            |
| scimark_monte_carlo        | 71.8 ms                                                | 72.9 ms: 1.02x slower                                                            |
| mdp                        | 2.79 sec                                               | 2.84 sec: 1.02x slower                                                           |
| xml_etree_iterparse        | 109 ms                                                 | 111 ms: 1.02x slower                                                             |
| pycparser                  | 1.20 sec                                               | 1.22 sec: 1.02x slower                                                           |
| fannkuch                   | 410 ms                                                 | 420 ms: 1.02x slower                                                             |
| pidigits                   | 190 ms                                                 | 196 ms: 1.03x slower                                                             |
| richards                   | 48.9 ms                                                | 50.4 ms: 1.03x slower                                                            |
| chameleon                  | 6.86 ms                                                | 7.09 ms: 1.03x slower                                                            |
| dulwich_log                | 64.9 ms                                                | 67.2 ms: 1.03x slower                                                            |
| regex_dna                  | 204 ms                                                 | 211 ms: 1.04x slower                                                             |
| 2to3                       | 266 ms                                                 | 279 ms: 1.05x slower                                                             |
| meteor_contest             | 109 ms                                                 | 115 ms: 1.06x slower                                                             |
| scimark_lu                 | 112 ms                                                 | 119 ms: 1.06x slower                                                             |
| xml_etree_process          | 56.5 ms                                                | 59.9 ms: 1.06x slower                                                            |
| deepcopy_memo              | 38.9 us                                                | 41.4 us: 1.06x slower                                                            |
| pathlib                    | 18.5 ms                                                | 19.7 ms: 1.07x slower                                                            |
| spectral_norm              | 105 ms                                                 | 112 ms: 1.07x slower                                                             |
| unpickle                   | 13.9 us                                                | 14.9 us: 1.07x slower                                                            |
| tomli_loads                | 2.31 sec                                               | 2.49 sec: 1.07x slower                                                           |
| regex_effbot               | 3.45 ms                                                | 3.73 ms: 1.08x slower                                                            |
| xml_etree_generate         | 80.4 ms                                                | 87.0 ms: 1.08x slower                                                            |
| pprint_safe_repr           | 743 ms                                                 | 804 ms: 1.08x slower                                                             |
| scimark_sor                | 121 ms                                                 | 132 ms: 1.08x slower                                                             |
| pprint_pformat             | 1.53 sec                                               | 1.67 sec: 1.10x slower                                                           |
| pickle_list                | 4.65 us                                                | 5.10 us: 1.10x slower                                                            |
| nqueens                    | 86.8 ms                                                | 95.9 ms: 1.10x slower                                                            |
| regex_compile              | 141 ms                                                 | 157 ms: 1.11x slower                                                             |
| go                         | 143 ms                                                 | 159 ms: 1.11x slower                                                             |
| sqlite_synth               | 2.58 us                                                | 2.88 us: 1.11x slower                                                            |
| regex_v8                   | 22.9 ms                                                | 25.7 ms: 1.12x slower                                                            |
| unpack_sequence            | 43.3 ns                                                | 49.4 ns: 1.14x slower                                                            |
| scimark_sparse_mat_mult    | 4.80 ms                                                | 5.51 ms: 1.15x slower                                                            |
| coverage                   | 81.2 ms                                                | 93.5 ms: 1.15x slower                                                            |
| scimark_fft                | 342 ms                                                 | 398 ms: 1.16x slower                                                             |
| python_startup             | 8.69 ms                                                | 10.3 ms: 1.19x slower                                                            |
| nbody                      | 91.6 ms                                                | 110 ms: 1.20x slower                                                             |
| deltablue                  | 3.80 ms                                                | 4.58 ms: 1.20x slower                                                            |
| pyflate                    | 426 ms                                                 | 514 ms: 1.21x slower                                                             |
| async_generators           | 375 ms                                                 | 455 ms: 1.21x slower                                                             |
| float                      | 78.9 ms                                                | 96.2 ms: 1.22x slower                                                            |
| telco                      | 6.72 ms                                                | 8.37 ms: 1.25x slower                                                            |
| mako                       | 10.8 ms                                                | 14.0 ms: 1.29x slower                                                            |
| hexiom                     | 6.74 ms                                                | 8.74 ms: 1.30x slower                                                            |
| python_startup_no_site     | 6.09 ms                                                | 9.00 ms: 1.48x slower                                                            |
| Geometric mean             | (ref)                                                  | 1.01x faster                                                                     |

Benchmark hidden because not significant (3): logging_silent, bench_mp_pool, tornado_http
Ignored benchmarks (13) of results/bm-20221024-3.11.0-deaf509/bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift


# HPT report

- Reliability score: 89.29% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
