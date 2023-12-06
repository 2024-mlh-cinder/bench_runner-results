
# Results vs. 3.11.0

- fork: mdboom
- ref: collect_tier2_stats
- machine: linux-x86_64
- commit hash: 3d16eaf
- commit date: 2023-11-02
- overall geometric mean: 1.01x faster \*
- HPT reliability: 88.93%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231102-linux-x86_64-mdboom-collect_tier2_stats-3.13.0a1+-3d16eaf |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| 2to3           | 266 ms                                                 | 282 ms: 1.06x slower                                                  |
| chameleon      | 6.86 ms                                                | 7.14 ms: 1.04x slower                                                 |
| docutils       | 2.69 sec                                               | 2.71 sec: 1.01x slower                                                |
| Geometric mean | (ref)                                                  | 1.03x slower                                                          |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231102-linux-x86_64-mdboom-collect_tier2_stats-3.13.0a1+-3d16eaf |
|----------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| async_tree_none            | 532 ms                                                 | 454 ms: 1.17x faster                                                  |
| async_tree_memoization     | 640 ms                                                 | 582 ms: 1.10x faster                                                  |
| async_tree_io              | 1.31 sec                                               | 1.21 sec: 1.09x faster                                                |
| async_tree_none_tg         | 490 ms                                                 | 467 ms: 1.05x faster                                                  |
| async_tree_io_tg           | 1.30 sec                                               | 1.25 sec: 1.05x faster                                                |
| async_tree_memoization_tg  | 627 ms                                                 | 607 ms: 1.03x faster                                                  |
| async_tree_cpu_io_mixed    | 750 ms                                                 | 727 ms: 1.03x faster                                                  |
| async_tree_cpu_io_mixed_tg | 764 ms                                                 | 749 ms: 1.02x faster                                                  |
| Geometric mean             | (ref)                                                  | 1.07x faster                                                          |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231102-linux-x86_64-mdboom-collect_tier2_stats-3.13.0a1+-3d16eaf |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| pidigits       | 190 ms                                                 | 196 ms: 1.03x slower                                                  |
| float          | 78.9 ms                                                | 97.0 ms: 1.23x slower                                                 |
| nbody          | 91.6 ms                                                | 113 ms: 1.24x slower                                                  |
| Geometric mean | (ref)                                                  | 1.16x slower                                                          |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231102-linux-x86_64-mdboom-collect_tier2_stats-3.13.0a1+-3d16eaf |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| regex_effbot   | 3.45 ms                                                | 3.44 ms: 1.00x faster                                                 |
| regex_dna      | 204 ms                                                 | 212 ms: 1.04x slower                                                  |
| regex_v8       | 22.9 ms                                                | 24.9 ms: 1.09x slower                                                 |
| regex_compile  | 141 ms                                                 | 158 ms: 1.12x slower                                                  |
| Geometric mean | (ref)                                                  | 1.06x slower                                                          |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231102-linux-x86_64-mdboom-collect_tier2_stats-3.13.0a1+-3d16eaf |
|----------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| json_dumps           | 13.5 ms                                                | 10.6 ms: 1.27x faster                                                 |
| json_loads           | 29.4 us                                                | 27.9 us: 1.06x faster                                                 |
| pickle_pure_python   | 319 us                                                 | 303 us: 1.05x faster                                                  |
| unpickle_list        | 5.22 us                                                | 5.02 us: 1.04x faster                                                 |
| xml_etree_parse      | 163 ms                                                 | 159 ms: 1.02x faster                                                  |
| unpickle_pure_python | 241 us                                                 | 237 us: 1.02x faster                                                  |
| pickle_dict          | 34.8 us                                                | 34.4 us: 1.01x faster                                                 |
| xml_etree_iterparse  | 109 ms                                                 | 111 ms: 1.02x slower                                                  |
| pickle               | 11.1 us                                                | 11.6 us: 1.04x slower                                                 |
| xml_etree_process    | 56.5 ms                                                | 59.9 ms: 1.06x slower                                                 |
| tomli_loads          | 2.31 sec                                               | 2.47 sec: 1.07x slower                                                |
| unpickle             | 13.9 us                                                | 15.0 us: 1.08x slower                                                 |
| pickle_list          | 4.65 us                                                | 5.07 us: 1.09x slower                                                 |
| xml_etree_generate   | 80.4 ms                                                | 88.0 ms: 1.09x slower                                                 |
| Geometric mean       | (ref)                                                  | 1.00x slower                                                          |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231102-linux-x86_64-mdboom-collect_tier2_stats-3.13.0a1+-3d16eaf |
|------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| python_startup         | 8.69 ms                                                | 10.3 ms: 1.19x slower                                                 |
| python_startup_no_site | 6.09 ms                                                | 9.00 ms: 1.48x slower                                                 |
| Geometric mean         | (ref)                                                  | 1.32x slower                                                          |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231102-linux-x86_64-mdboom-collect_tier2_stats-3.13.0a1+-3d16eaf |
|-----------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| mako      | 10.8 ms                                                | 13.7 ms: 1.26x slower                                                 |

All benchmarks:
===============

| Benchmark                  | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231102-linux-x86_64-mdboom-collect_tier2_stats-3.13.0a1+-3d16eaf |
|----------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| typing_runtime_protocols   | 521 us                                                 | 128 us: 4.06x faster                                                  |
| generators                 | 76.5 ms                                                | 29.7 ms: 2.57x faster                                                 |
| asyncio_tcp                | 887 ms                                                 | 490 ms: 1.81x faster                                                  |
| asyncio_tcp_ssl            | 3.13 sec                                               | 1.80 sec: 1.74x faster                                                |
| json_dumps                 | 13.5 ms                                                | 10.6 ms: 1.27x faster                                                 |
| mypy2                      | 427 ms                                                 | 356 ms: 1.20x faster                                                  |
| async_tree_none            | 532 ms                                                 | 454 ms: 1.17x faster                                                  |
| coroutines                 | 26.1 ms                                                | 22.5 ms: 1.16x faster                                                 |
| sympy_sum                  | 170 ms                                                 | 155 ms: 1.10x faster                                                  |
| async_tree_memoization     | 640 ms                                                 | 582 ms: 1.10x faster                                                  |
| async_tree_io              | 1.31 sec                                               | 1.21 sec: 1.09x faster                                                |
| richards_super             | 61.2 ms                                                | 57.7 ms: 1.06x faster                                                 |
| sqlglot_parse              | 1.43 ms                                                | 1.36 ms: 1.06x faster                                                 |
| json_loads                 | 29.4 us                                                | 27.9 us: 1.06x faster                                                 |
| pickle_pure_python         | 319 us                                                 | 303 us: 1.05x faster                                                  |
| sympy_str                  | 299 ms                                                 | 284 ms: 1.05x faster                                                  |
| logging_format             | 6.83 us                                                | 6.49 us: 1.05x faster                                                 |
| logging_simple             | 6.24 us                                                | 5.95 us: 1.05x faster                                                 |
| async_tree_none_tg         | 490 ms                                                 | 467 ms: 1.05x faster                                                  |
| raytrace                   | 306 ms                                                 | 293 ms: 1.05x faster                                                  |
| async_tree_io_tg           | 1.30 sec                                               | 1.25 sec: 1.05x faster                                                |
| comprehensions             | 23.6 us                                                | 22.5 us: 1.04x faster                                                 |
| sqlglot_transpile          | 1.75 ms                                                | 1.69 ms: 1.04x faster                                                 |
| unpickle_list              | 5.22 us                                                | 5.02 us: 1.04x faster                                                 |
| async_tree_memoization_tg  | 627 ms                                                 | 607 ms: 1.03x faster                                                  |
| sqlglot_normalize          | 112 ms                                                 | 109 ms: 1.03x faster                                                  |
| chaos                      | 71.4 ms                                                | 69.2 ms: 1.03x faster                                                 |
| async_tree_cpu_io_mixed    | 750 ms                                                 | 727 ms: 1.03x faster                                                  |
| mdp                        | 2.79 sec                                               | 2.71 sec: 1.03x faster                                                |
| sympy_expand               | 490 ms                                                 | 479 ms: 1.02x faster                                                  |
| json                       | 5.24 ms                                                | 5.12 ms: 1.02x faster                                                 |
| xml_etree_parse            | 163 ms                                                 | 159 ms: 1.02x faster                                                  |
| async_tree_cpu_io_mixed_tg | 764 ms                                                 | 749 ms: 1.02x faster                                                  |
| unpickle_pure_python       | 241 us                                                 | 237 us: 1.02x faster                                                  |
| sympy_integrate            | 21.4 ms                                                | 21.0 ms: 1.02x faster                                                 |
| pickle_dict                | 34.8 us                                                | 34.4 us: 1.01x faster                                                 |
| deepcopy                   | 360 us                                                 | 356 us: 1.01x faster                                                  |
| logging_silent             | 108 ns                                                 | 107 ns: 1.01x faster                                                  |
| asyncio_websockets         | 556 ms                                                 | 552 ms: 1.01x faster                                                  |
| crypto_pyaes               | 77.5 ms                                                | 77.0 ms: 1.01x faster                                                 |
| create_gc_cycles           | 1.48 ms                                                | 1.47 ms: 1.01x faster                                                 |
| regex_effbot               | 3.45 ms                                                | 3.44 ms: 1.00x faster                                                 |
| gc_traversal               | 3.90 ms                                                | 3.91 ms: 1.00x slower                                                 |
| docutils                   | 2.69 sec                                               | 2.71 sec: 1.01x slower                                                |
| bench_thread_pool          | 833 us                                                 | 841 us: 1.01x slower                                                  |
| sqlglot_optimize           | 55.2 ms                                                | 55.7 ms: 1.01x slower                                                 |
| xml_etree_iterparse        | 109 ms                                                 | 111 ms: 1.02x slower                                                  |
| pidigits                   | 190 ms                                                 | 196 ms: 1.03x slower                                                  |
| dulwich_log                | 64.9 ms                                                | 67.3 ms: 1.04x slower                                                 |
| scimark_monte_carlo        | 71.8 ms                                                | 74.4 ms: 1.04x slower                                                 |
| regex_dna                  | 204 ms                                                 | 212 ms: 1.04x slower                                                  |
| chameleon                  | 6.86 ms                                                | 7.14 ms: 1.04x slower                                                 |
| fannkuch                   | 410 ms                                                 | 427 ms: 1.04x slower                                                  |
| pickle                     | 11.1 us                                                | 11.6 us: 1.04x slower                                                 |
| meteor_contest             | 109 ms                                                 | 114 ms: 1.05x slower                                                  |
| pathlib                    | 18.5 ms                                                | 19.5 ms: 1.06x slower                                                 |
| richards                   | 48.9 ms                                                | 51.7 ms: 1.06x slower                                                 |
| 2to3                       | 266 ms                                                 | 282 ms: 1.06x slower                                                  |
| xml_etree_process          | 56.5 ms                                                | 59.9 ms: 1.06x slower                                                 |
| scimark_sor                | 121 ms                                                 | 130 ms: 1.07x slower                                                  |
| tomli_loads                | 2.31 sec                                               | 2.47 sec: 1.07x slower                                                |
| scimark_lu                 | 112 ms                                                 | 120 ms: 1.07x slower                                                  |
| pprint_safe_repr           | 743 ms                                                 | 794 ms: 1.07x slower                                                  |
| deepcopy_memo              | 38.9 us                                                | 41.6 us: 1.07x slower                                                 |
| pprint_pformat             | 1.53 sec                                               | 1.65 sec: 1.08x slower                                                |
| spectral_norm              | 105 ms                                                 | 114 ms: 1.08x slower                                                  |
| unpickle                   | 13.9 us                                                | 15.0 us: 1.08x slower                                                 |
| regex_v8                   | 22.9 ms                                                | 24.9 ms: 1.09x slower                                                 |
| pickle_list                | 4.65 us                                                | 5.07 us: 1.09x slower                                                 |
| xml_etree_generate         | 80.4 ms                                                | 88.0 ms: 1.09x slower                                                 |
| sqlite_synth               | 2.58 us                                                | 2.85 us: 1.11x slower                                                 |
| nqueens                    | 86.8 ms                                                | 96.5 ms: 1.11x slower                                                 |
| go                         | 143 ms                                                 | 160 ms: 1.12x slower                                                  |
| regex_compile              | 141 ms                                                 | 158 ms: 1.12x slower                                                  |
| scimark_fft                | 342 ms                                                 | 395 ms: 1.16x slower                                                  |
| scimark_sparse_mat_mult    | 4.80 ms                                                | 5.60 ms: 1.17x slower                                                 |
| coverage                   | 81.2 ms                                                | 94.8 ms: 1.17x slower                                                 |
| pyflate                    | 426 ms                                                 | 506 ms: 1.19x slower                                                  |
| python_startup             | 8.69 ms                                                | 10.3 ms: 1.19x slower                                                 |
| async_generators           | 375 ms                                                 | 456 ms: 1.22x slower                                                  |
| float                      | 78.9 ms                                                | 97.0 ms: 1.23x slower                                                 |
| nbody                      | 91.6 ms                                                | 113 ms: 1.24x slower                                                  |
| telco                      | 6.72 ms                                                | 8.37 ms: 1.25x slower                                                 |
| mako                       | 10.8 ms                                                | 13.7 ms: 1.26x slower                                                 |
| deltablue                  | 3.80 ms                                                | 4.85 ms: 1.27x slower                                                 |
| hexiom                     | 6.74 ms                                                | 8.94 ms: 1.33x slower                                                 |
| unpack_sequence            | 43.3 ns                                                | 59.9 ns: 1.38x slower                                                 |
| python_startup_no_site     | 6.09 ms                                                | 9.00 ms: 1.48x slower                                                 |
| Geometric mean             | (ref)                                                  | 1.01x faster                                                          |

Benchmark hidden because not significant (4): deepcopy_reduce, bench_mp_pool, tornado_http, pycparser
Ignored benchmarks (13) of results/bm-20221024-3.11.0-deaf509/bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift


# HPT report

- Reliability score: 88.93% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
