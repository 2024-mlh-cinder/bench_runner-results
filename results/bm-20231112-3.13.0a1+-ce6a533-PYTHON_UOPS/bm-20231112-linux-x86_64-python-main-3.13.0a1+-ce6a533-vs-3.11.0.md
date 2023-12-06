
# Results vs. 3.11.0

- fork: python
- ref: main
- machine: linux-x86_64
- commit hash: ce6a533
- commit date: 2023-11-12
- overall geometric mean: 1.04x slower \*
- HPT reliability: 99.87%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231112-linux-x86_64-python-main-3.13.0a1+-ce6a533 |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| 2to3           | 266 ms                                                 | 295 ms: 1.11x slower                                   |
| chameleon      | 6.86 ms                                                | 7.58 ms: 1.10x slower                                  |
| docutils       | 2.69 sec                                               | 2.73 sec: 1.01x slower                                 |
| tornado_http   | 97.7 ms                                                | 102 ms: 1.05x slower                                   |
| Geometric mean | (ref)                                                  | 1.07x slower                                           |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231112-linux-x86_64-python-main-3.13.0a1+-ce6a533 |
|----------------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| async_tree_none            | 532 ms                                                 | 467 ms: 1.14x faster                                   |
| async_tree_memoization     | 640 ms                                                 | 598 ms: 1.07x faster                                   |
| async_tree_io              | 1.31 sec                                               | 1.23 sec: 1.06x faster                                 |
| async_tree_io_tg           | 1.30 sec                                               | 1.27 sec: 1.03x faster                                 |
| async_tree_none_tg         | 490 ms                                                 | 479 ms: 1.02x faster                                   |
| async_tree_memoization_tg  | 627 ms                                                 | 614 ms: 1.02x faster                                   |
| async_tree_cpu_io_mixed_tg | 764 ms                                                 | 773 ms: 1.01x slower                                   |
| Geometric mean             | (ref)                                                  | 1.04x faster                                           |

Benchmark hidden because not significant (1): async_tree_cpu_io_mixed

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231112-linux-x86_64-python-main-3.13.0a1+-ce6a533 |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| pidigits       | 190 ms                                                 | 197 ms: 1.03x slower                                   |
| float          | 78.9 ms                                                | 112 ms: 1.42x slower                                   |
| nbody          | 91.6 ms                                                | 132 ms: 1.44x slower                                   |
| Geometric mean | (ref)                                                  | 1.28x slower                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231112-linux-x86_64-python-main-3.13.0a1+-ce6a533 |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| regex_dna      | 204 ms                                                 | 223 ms: 1.09x slower                                   |
| regex_effbot   | 3.45 ms                                                | 3.78 ms: 1.09x slower                                  |
| regex_v8       | 22.9 ms                                                | 26.1 ms: 1.14x slower                                  |
| regex_compile  | 141 ms                                                 | 166 ms: 1.18x slower                                   |
| Geometric mean | (ref)                                                  | 1.13x slower                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231112-linux-x86_64-python-main-3.13.0a1+-ce6a533 |
|----------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| json_dumps           | 13.5 ms                                                | 10.7 ms: 1.26x faster                                  |
| json_loads           | 29.4 us                                                | 27.8 us: 1.06x faster                                  |
| unpickle_list        | 5.22 us                                                | 4.98 us: 1.05x faster                                  |
| pickle_pure_python   | 319 us                                                 | 310 us: 1.03x faster                                   |
| xml_etree_parse      | 163 ms                                                 | 158 ms: 1.03x faster                                   |
| pickle_dict          | 34.8 us                                                | 34.6 us: 1.01x faster                                  |
| unpickle_pure_python | 241 us                                                 | 247 us: 1.03x slower                                   |
| pickle_list          | 4.65 us                                                | 4.84 us: 1.04x slower                                  |
| pickle               | 11.1 us                                                | 11.6 us: 1.05x slower                                  |
| xml_etree_iterparse  | 109 ms                                                 | 114 ms: 1.05x slower                                   |
| xml_etree_process    | 56.5 ms                                                | 59.9 ms: 1.06x slower                                  |
| unpickle             | 13.9 us                                                | 14.8 us: 1.07x slower                                  |
| xml_etree_generate   | 80.4 ms                                                | 87.8 ms: 1.09x slower                                  |
| tomli_loads          | 2.31 sec                                               | 3.17 sec: 1.37x slower                                 |
| Geometric mean       | (ref)                                                  | 1.02x slower                                           |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231112-linux-x86_64-python-main-3.13.0a1+-ce6a533 |
|------------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| python_startup         | 8.69 ms                                                | 10.4 ms: 1.19x slower                                  |
| python_startup_no_site | 6.09 ms                                                | 9.08 ms: 1.49x slower                                  |
| Geometric mean         | (ref)                                                  | 1.33x slower                                           |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231112-linux-x86_64-python-main-3.13.0a1+-ce6a533 |
|-----------|:------------------------------------------------------:|:------------------------------------------------------:|
| mako      | 10.8 ms                                                | 15.8 ms: 1.46x slower                                  |

All benchmarks:
===============

| Benchmark                  | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231112-linux-x86_64-python-main-3.13.0a1+-ce6a533 |
|----------------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| typing_runtime_protocols   | 521 us                                                 | 126 us: 4.12x faster                                   |
| generators                 | 76.5 ms                                                | 29.6 ms: 2.58x faster                                  |
| asyncio_tcp                | 887 ms                                                 | 493 ms: 1.80x faster                                   |
| asyncio_tcp_ssl            | 3.13 sec                                               | 1.81 sec: 1.73x faster                                 |
| json_dumps                 | 13.5 ms                                                | 10.7 ms: 1.26x faster                                  |
| coroutines                 | 26.1 ms                                                | 21.6 ms: 1.21x faster                                  |
| mypy2                      | 427 ms                                                 | 357 ms: 1.20x faster                                   |
| async_tree_none            | 532 ms                                                 | 467 ms: 1.14x faster                                   |
| sympy_sum                  | 170 ms                                                 | 155 ms: 1.10x faster                                   |
| async_tree_memoization     | 640 ms                                                 | 598 ms: 1.07x faster                                   |
| async_tree_io              | 1.31 sec                                               | 1.23 sec: 1.06x faster                                 |
| json_loads                 | 29.4 us                                                | 27.8 us: 1.06x faster                                  |
| sqlglot_parse              | 1.43 ms                                                | 1.35 ms: 1.06x faster                                  |
| unpickle_list              | 5.22 us                                                | 4.98 us: 1.05x faster                                  |
| sqlglot_transpile          | 1.75 ms                                                | 1.68 ms: 1.04x faster                                  |
| sqlglot_normalize          | 112 ms                                                 | 109 ms: 1.03x faster                                   |
| pickle_pure_python         | 319 us                                                 | 310 us: 1.03x faster                                   |
| async_tree_io_tg           | 1.30 sec                                               | 1.27 sec: 1.03x faster                                 |
| xml_etree_parse            | 163 ms                                                 | 158 ms: 1.03x faster                                   |
| gc_traversal               | 3.90 ms                                                | 3.80 ms: 1.03x faster                                  |
| sympy_str                  | 299 ms                                                 | 292 ms: 1.02x faster                                   |
| async_tree_none_tg         | 490 ms                                                 | 479 ms: 1.02x faster                                   |
| async_tree_memoization_tg  | 627 ms                                                 | 614 ms: 1.02x faster                                   |
| mdp                        | 2.79 sec                                               | 2.74 sec: 1.02x faster                                 |
| richards_super             | 61.2 ms                                                | 60.5 ms: 1.01x faster                                  |
| pickle_dict                | 34.8 us                                                | 34.6 us: 1.01x faster                                  |
| sympy_expand               | 490 ms                                                 | 487 ms: 1.01x faster                                   |
| asyncio_websockets         | 556 ms                                                 | 552 ms: 1.01x faster                                   |
| deepcopy                   | 360 us                                                 | 358 us: 1.01x faster                                   |
| sqlglot_optimize           | 55.2 ms                                                | 55.0 ms: 1.00x faster                                  |
| create_gc_cycles           | 1.48 ms                                                | 1.48 ms: 1.00x slower                                  |
| deepcopy_reduce            | 3.14 us                                                | 3.16 us: 1.01x slower                                  |
| logging_silent             | 108 ns                                                 | 109 ns: 1.01x slower                                   |
| async_tree_cpu_io_mixed_tg | 764 ms                                                 | 773 ms: 1.01x slower                                   |
| logging_simple             | 6.24 us                                                | 6.33 us: 1.01x slower                                  |
| docutils                   | 2.69 sec                                               | 2.73 sec: 1.01x slower                                 |
| sympy_integrate            | 21.4 ms                                                | 21.7 ms: 1.01x slower                                  |
| raytrace                   | 306 ms                                                 | 312 ms: 1.02x slower                                   |
| unpickle_pure_python       | 241 us                                                 | 247 us: 1.03x slower                                   |
| bench_thread_pool          | 833 us                                                 | 859 us: 1.03x slower                                   |
| pidigits                   | 190 ms                                                 | 197 ms: 1.03x slower                                   |
| pickle_list                | 4.65 us                                                | 4.84 us: 1.04x slower                                  |
| pickle                     | 11.1 us                                                | 11.6 us: 1.05x slower                                  |
| xml_etree_iterparse        | 109 ms                                                 | 114 ms: 1.05x slower                                   |
| logging_format             | 6.83 us                                                | 7.15 us: 1.05x slower                                  |
| tornado_http               | 97.7 ms                                                | 102 ms: 1.05x slower                                   |
| xml_etree_process          | 56.5 ms                                                | 59.9 ms: 1.06x slower                                  |
| unpickle                   | 13.9 us                                                | 14.8 us: 1.07x slower                                  |
| chaos                      | 71.4 ms                                                | 76.2 ms: 1.07x slower                                  |
| dulwich_log                | 64.9 ms                                                | 69.5 ms: 1.07x slower                                  |
| scimark_lu                 | 112 ms                                                 | 120 ms: 1.07x slower                                   |
| pycparser                  | 1.20 sec                                               | 1.28 sec: 1.07x slower                                 |
| spectral_norm              | 105 ms                                                 | 113 ms: 1.07x slower                                   |
| pathlib                    | 18.5 ms                                                | 20.0 ms: 1.08x slower                                  |
| richards                   | 48.9 ms                                                | 52.8 ms: 1.08x slower                                  |
| xml_etree_generate         | 80.4 ms                                                | 87.8 ms: 1.09x slower                                  |
| regex_dna                  | 204 ms                                                 | 223 ms: 1.09x slower                                   |
| deepcopy_memo              | 38.9 us                                                | 42.6 us: 1.09x slower                                  |
| regex_effbot               | 3.45 ms                                                | 3.78 ms: 1.09x slower                                  |
| meteor_contest             | 109 ms                                                 | 120 ms: 1.10x slower                                   |
| chameleon                  | 6.86 ms                                                | 7.58 ms: 1.10x slower                                  |
| scimark_sor                | 121 ms                                                 | 134 ms: 1.10x slower                                   |
| 2to3                       | 266 ms                                                 | 295 ms: 1.11x slower                                   |
| pprint_safe_repr           | 743 ms                                                 | 832 ms: 1.12x slower                                   |
| pprint_pformat             | 1.53 sec                                               | 1.71 sec: 1.12x slower                                 |
| sqlite_synth               | 2.58 us                                                | 2.91 us: 1.13x slower                                  |
| comprehensions             | 23.6 us                                                | 26.7 us: 1.13x slower                                  |
| crypto_pyaes               | 77.5 ms                                                | 87.8 ms: 1.13x slower                                  |
| regex_v8                   | 22.9 ms                                                | 26.1 ms: 1.14x slower                                  |
| scimark_monte_carlo        | 71.8 ms                                                | 83.3 ms: 1.16x slower                                  |
| unpack_sequence            | 43.3 ns                                                | 50.5 ns: 1.17x slower                                  |
| regex_compile              | 141 ms                                                 | 166 ms: 1.18x slower                                   |
| coverage                   | 81.2 ms                                                | 96.6 ms: 1.19x slower                                  |
| python_startup             | 8.69 ms                                                | 10.4 ms: 1.19x slower                                  |
| go                         | 143 ms                                                 | 172 ms: 1.21x slower                                   |
| async_generators           | 375 ms                                                 | 457 ms: 1.22x slower                                   |
| nqueens                    | 86.8 ms                                                | 114 ms: 1.31x slower                                   |
| telco                      | 6.72 ms                                                | 8.89 ms: 1.32x slower                                  |
| scimark_fft                | 342 ms                                                 | 460 ms: 1.34x slower                                   |
| pyflate                    | 426 ms                                                 | 574 ms: 1.35x slower                                   |
| fannkuch                   | 410 ms                                                 | 554 ms: 1.35x slower                                   |
| tomli_loads                | 2.31 sec                                               | 3.17 sec: 1.37x slower                                 |
| float                      | 78.9 ms                                                | 112 ms: 1.42x slower                                   |
| deltablue                  | 3.80 ms                                                | 5.43 ms: 1.43x slower                                  |
| nbody                      | 91.6 ms                                                | 132 ms: 1.44x slower                                   |
| scimark_sparse_mat_mult    | 4.80 ms                                                | 6.93 ms: 1.44x slower                                  |
| mako                       | 10.8 ms                                                | 15.8 ms: 1.46x slower                                  |
| python_startup_no_site     | 6.09 ms                                                | 9.08 ms: 1.49x slower                                  |
| hexiom                     | 6.74 ms                                                | 10.9 ms: 1.62x slower                                  |
| Geometric mean             | (ref)                                                  | 1.04x slower                                           |

Benchmark hidden because not significant (3): json, async_tree_cpu_io_mixed, bench_mp_pool
Ignored benchmarks (13) of results/bm-20221024-3.11.0-deaf509/bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift


# HPT report

- Reliability score: 99.87% likely to be slow
- 90% likely to have a slowdown of 1.01x
- 95% likely to have a slowdown of 1.01x
- 99% likely to have a slowdown of 1.00x
