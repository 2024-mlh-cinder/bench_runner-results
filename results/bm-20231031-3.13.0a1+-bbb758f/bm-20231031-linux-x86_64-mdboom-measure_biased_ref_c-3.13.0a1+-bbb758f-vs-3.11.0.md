
# Results vs. 3.11.0

- fork: mdboom
- ref: measure_biased_ref_c
- machine: linux-x86_64
- commit hash: bbb758f
- commit date: 2023-10-31
- overall geometric mean: 1.04x slower \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.02x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231031-linux-x86_64-mdboom-measure_biased_ref_c-3.13.0a1+-bbb758f |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| 2to3           | 266 ms                                                 | 285 ms: 1.07x slower                                                   |
| chameleon      | 6.86 ms                                                | 7.47 ms: 1.09x slower                                                  |
| docutils       | 2.69 sec                                               | 2.83 sec: 1.05x slower                                                 |
| tornado_http   | 97.7 ms                                                | 106 ms: 1.09x slower                                                   |
| Geometric mean | (ref)                                                  | 1.07x slower                                                           |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231031-linux-x86_64-mdboom-measure_biased_ref_c-3.13.0a1+-bbb758f |
|----------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| async_tree_none            | 532 ms                                                 | 493 ms: 1.08x faster                                                   |
| async_tree_memoization     | 640 ms                                                 | 634 ms: 1.01x faster                                                   |
| async_tree_io              | 1.31 sec                                               | 1.36 sec: 1.04x slower                                                 |
| async_tree_cpu_io_mixed    | 750 ms                                                 | 780 ms: 1.04x slower                                                   |
| async_tree_none_tg         | 490 ms                                                 | 527 ms: 1.08x slower                                                   |
| async_tree_cpu_io_mixed_tg | 764 ms                                                 | 823 ms: 1.08x slower                                                   |
| async_tree_memoization_tg  | 627 ms                                                 | 678 ms: 1.08x slower                                                   |
| async_tree_io_tg           | 1.30 sec                                               | 1.42 sec: 1.09x slower                                                 |
| Geometric mean             | (ref)                                                  | 1.04x slower                                                           |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231031-linux-x86_64-mdboom-measure_biased_ref_c-3.13.0a1+-bbb758f |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| pidigits       | 190 ms                                                 | 188 ms: 1.01x faster                                                   |
| float          | 78.9 ms                                                | 90.6 ms: 1.15x slower                                                  |
| nbody          | 91.6 ms                                                | 111 ms: 1.21x slower                                                   |
| Geometric mean | (ref)                                                  | 1.11x slower                                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231031-linux-x86_64-mdboom-measure_biased_ref_c-3.13.0a1+-bbb758f |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| regex_effbot   | 3.45 ms                                                | 3.48 ms: 1.01x slower                                                  |
| regex_dna      | 204 ms                                                 | 209 ms: 1.02x slower                                                   |
| regex_compile  | 141 ms                                                 | 149 ms: 1.05x slower                                                   |
| regex_v8       | 22.9 ms                                                | 25.2 ms: 1.10x slower                                                  |
| Geometric mean | (ref)                                                  | 1.05x slower                                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231031-linux-x86_64-mdboom-measure_biased_ref_c-3.13.0a1+-bbb758f |
|----------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| json_dumps           | 13.5 ms                                                | 11.2 ms: 1.20x faster                                                  |
| pickle_dict          | 34.8 us                                                | 31.6 us: 1.10x faster                                                  |
| unpickle_pure_python | 241 us                                                 | 243 us: 1.01x slower                                                   |
| unpickle_list        | 5.22 us                                                | 5.36 us: 1.03x slower                                                  |
| xml_etree_iterparse  | 109 ms                                                 | 112 ms: 1.03x slower                                                   |
| pickle               | 11.1 us                                                | 11.5 us: 1.04x slower                                                  |
| pickle_pure_python   | 319 us                                                 | 333 us: 1.04x slower                                                   |
| xml_etree_parse      | 163 ms                                                 | 170 ms: 1.05x slower                                                   |
| json_loads           | 29.4 us                                                | 30.8 us: 1.05x slower                                                  |
| pickle_list          | 4.65 us                                                | 4.94 us: 1.06x slower                                                  |
| unpickle             | 13.9 us                                                | 15.5 us: 1.12x slower                                                  |
| xml_etree_process    | 56.5 ms                                                | 64.6 ms: 1.14x slower                                                  |
| xml_etree_generate   | 80.4 ms                                                | 93.6 ms: 1.16x slower                                                  |
| Geometric mean       | (ref)                                                  | 1.03x slower                                                           |

Benchmark hidden because not significant (1): tomli_loads

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231031-linux-x86_64-mdboom-measure_biased_ref_c-3.13.0a1+-bbb758f |
|------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| python_startup         | 8.69 ms                                                | 10.8 ms: 1.25x slower                                                  |
| python_startup_no_site | 6.09 ms                                                | 9.31 ms: 1.53x slower                                                  |
| Geometric mean         | (ref)                                                  | 1.38x slower                                                           |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231031-linux-x86_64-mdboom-measure_biased_ref_c-3.13.0a1+-bbb758f |
|-----------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| mako      | 10.8 ms                                                | 12.7 ms: 1.17x slower                                                  |

All benchmarks:
===============

| Benchmark                  | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231031-linux-x86_64-mdboom-measure_biased_ref_c-3.13.0a1+-bbb758f |
|----------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| typing_runtime_protocols   | 521 us                                                 | 157 us: 3.32x faster                                                   |
| generators                 | 76.5 ms                                                | 30.2 ms: 2.54x faster                                                  |
| asyncio_tcp                | 887 ms                                                 | 484 ms: 1.83x faster                                                   |
| asyncio_tcp_ssl            | 3.13 sec                                               | 1.78 sec: 1.75x faster                                                 |
| comprehensions             | 23.6 us                                                | 17.6 us: 1.33x faster                                                  |
| json_dumps                 | 13.5 ms                                                | 11.2 ms: 1.20x faster                                                  |
| pickle_dict                | 34.8 us                                                | 31.6 us: 1.10x faster                                                  |
| async_tree_none            | 532 ms                                                 | 493 ms: 1.08x faster                                                   |
| gc_traversal               | 3.90 ms                                                | 3.62 ms: 1.08x faster                                                  |
| richards_super             | 61.2 ms                                                | 57.0 ms: 1.07x faster                                                  |
| coroutines                 | 26.1 ms                                                | 24.4 ms: 1.07x faster                                                  |
| sympy_sum                  | 170 ms                                                 | 161 ms: 1.06x faster                                                   |
| chaos                      | 71.4 ms                                                | 68.3 ms: 1.04x faster                                                  |
| deltablue                  | 3.80 ms                                                | 3.65 ms: 1.04x faster                                                  |
| sqlglot_parse              | 1.43 ms                                                | 1.39 ms: 1.03x faster                                                  |
| sympy_str                  | 299 ms                                                 | 291 ms: 1.03x faster                                                   |
| mdp                        | 2.79 sec                                               | 2.72 sec: 1.02x faster                                                 |
| sqlglot_transpile          | 1.75 ms                                                | 1.73 ms: 1.01x faster                                                  |
| sympy_expand               | 490 ms                                                 | 484 ms: 1.01x faster                                                   |
| create_gc_cycles           | 1.48 ms                                                | 1.46 ms: 1.01x faster                                                  |
| pidigits                   | 190 ms                                                 | 188 ms: 1.01x faster                                                   |
| async_tree_memoization     | 640 ms                                                 | 634 ms: 1.01x faster                                                   |
| sympy_integrate            | 21.4 ms                                                | 21.3 ms: 1.00x faster                                                  |
| asyncio_websockets         | 556 ms                                                 | 559 ms: 1.01x slower                                                   |
| unpickle_pure_python       | 241 us                                                 | 243 us: 1.01x slower                                                   |
| hexiom                     | 6.74 ms                                                | 6.80 ms: 1.01x slower                                                  |
| raytrace                   | 306 ms                                                 | 309 ms: 1.01x slower                                                   |
| regex_effbot               | 3.45 ms                                                | 3.48 ms: 1.01x slower                                                  |
| logging_simple             | 6.24 us                                                | 6.32 us: 1.01x slower                                                  |
| logging_format             | 6.83 us                                                | 6.92 us: 1.01x slower                                                  |
| regex_dna                  | 204 ms                                                 | 209 ms: 1.02x slower                                                   |
| crypto_pyaes               | 77.5 ms                                                | 79.3 ms: 1.02x slower                                                  |
| unpickle_list              | 5.22 us                                                | 5.36 us: 1.03x slower                                                  |
| sqlglot_normalize          | 112 ms                                                 | 115 ms: 1.03x slower                                                   |
| xml_etree_iterparse        | 109 ms                                                 | 112 ms: 1.03x slower                                                   |
| pickle                     | 11.1 us                                                | 11.5 us: 1.04x slower                                                  |
| async_tree_io              | 1.31 sec                                               | 1.36 sec: 1.04x slower                                                 |
| pycparser                  | 1.20 sec                                               | 1.24 sec: 1.04x slower                                                 |
| async_tree_cpu_io_mixed    | 750 ms                                                 | 780 ms: 1.04x slower                                                   |
| richards                   | 48.9 ms                                                | 51.0 ms: 1.04x slower                                                  |
| pickle_pure_python         | 319 us                                                 | 333 us: 1.04x slower                                                   |
| logging_silent             | 108 ns                                                 | 113 ns: 1.05x slower                                                   |
| xml_etree_parse            | 163 ms                                                 | 170 ms: 1.05x slower                                                   |
| json_loads                 | 29.4 us                                                | 30.8 us: 1.05x slower                                                  |
| deepcopy                   | 360 us                                                 | 378 us: 1.05x slower                                                   |
| meteor_contest             | 109 ms                                                 | 114 ms: 1.05x slower                                                   |
| regex_compile              | 141 ms                                                 | 149 ms: 1.05x slower                                                   |
| docutils                   | 2.69 sec                                               | 2.83 sec: 1.05x slower                                                 |
| sqlglot_optimize           | 55.2 ms                                                | 58.0 ms: 1.05x slower                                                  |
| pickle_list                | 4.65 us                                                | 4.94 us: 1.06x slower                                                  |
| pprint_pformat             | 1.53 sec                                               | 1.63 sec: 1.07x slower                                                 |
| 2to3                       | 266 ms                                                 | 285 ms: 1.07x slower                                                   |
| async_tree_none_tg         | 490 ms                                                 | 527 ms: 1.08x slower                                                   |
| deepcopy_memo              | 38.9 us                                                | 41.9 us: 1.08x slower                                                  |
| json                       | 5.24 ms                                                | 5.64 ms: 1.08x slower                                                  |
| pprint_safe_repr           | 743 ms                                                 | 800 ms: 1.08x slower                                                   |
| async_tree_cpu_io_mixed_tg | 764 ms                                                 | 823 ms: 1.08x slower                                                   |
| go                         | 143 ms                                                 | 154 ms: 1.08x slower                                                   |
| scimark_monte_carlo        | 71.8 ms                                                | 77.5 ms: 1.08x slower                                                  |
| dulwich_log                | 64.9 ms                                                | 70.2 ms: 1.08x slower                                                  |
| async_tree_memoization_tg  | 627 ms                                                 | 678 ms: 1.08x slower                                                   |
| deepcopy_reduce            | 3.14 us                                                | 3.39 us: 1.08x slower                                                  |
| pathlib                    | 18.5 ms                                                | 20.1 ms: 1.09x slower                                                  |
| chameleon                  | 6.86 ms                                                | 7.47 ms: 1.09x slower                                                  |
| async_tree_io_tg           | 1.30 sec                                               | 1.42 sec: 1.09x slower                                                 |
| tornado_http               | 97.7 ms                                                | 106 ms: 1.09x slower                                                   |
| scimark_lu                 | 112 ms                                                 | 123 ms: 1.10x slower                                                   |
| regex_v8                   | 22.9 ms                                                | 25.2 ms: 1.10x slower                                                  |
| scimark_sparse_mat_mult    | 4.80 ms                                                | 5.35 ms: 1.11x slower                                                  |
| fannkuch                   | 410 ms                                                 | 457 ms: 1.12x slower                                                   |
| unpickle                   | 13.9 us                                                | 15.5 us: 1.12x slower                                                  |
| scimark_sor                | 121 ms                                                 | 137 ms: 1.13x slower                                                   |
| xml_etree_process          | 56.5 ms                                                | 64.6 ms: 1.14x slower                                                  |
| float                      | 78.9 ms                                                | 90.6 ms: 1.15x slower                                                  |
| xml_etree_generate         | 80.4 ms                                                | 93.6 ms: 1.16x slower                                                  |
| mako                       | 10.8 ms                                                | 12.7 ms: 1.17x slower                                                  |
| unpack_sequence            | 43.3 ns                                                | 50.7 ns: 1.17x slower                                                  |
| mypy2                      | 427 ms                                                 | 500 ms: 1.17x slower                                                   |
| pyflate                    | 426 ms                                                 | 503 ms: 1.18x slower                                                   |
| scimark_fft                | 342 ms                                                 | 405 ms: 1.18x slower                                                   |
| sqlite_synth               | 2.58 us                                                | 3.11 us: 1.21x slower                                                  |
| nbody                      | 91.6 ms                                                | 111 ms: 1.21x slower                                                   |
| spectral_norm              | 105 ms                                                 | 127 ms: 1.21x slower                                                   |
| python_startup             | 8.69 ms                                                | 10.8 ms: 1.25x slower                                                  |
| bench_thread_pool          | 833 us                                                 | 1.04 ms: 1.25x slower                                                  |
| async_generators           | 375 ms                                                 | 492 ms: 1.31x slower                                                   |
| telco                      | 6.72 ms                                                | 9.04 ms: 1.35x slower                                                  |
| python_startup_no_site     | 6.09 ms                                                | 9.31 ms: 1.53x slower                                                  |
| coverage                   | 81.2 ms                                                | 723 ms: 8.91x slower                                                   |
| Geometric mean             | (ref)                                                  | 1.04x slower                                                           |

Benchmark hidden because not significant (3): tomli_loads, bench_mp_pool, nqueens
Ignored benchmarks (13) of results/bm-20221024-3.11.0-deaf509/bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.03x
- 95% likely to have a slowdown of 1.03x
- 99% likely to have a slowdown of 1.02x
