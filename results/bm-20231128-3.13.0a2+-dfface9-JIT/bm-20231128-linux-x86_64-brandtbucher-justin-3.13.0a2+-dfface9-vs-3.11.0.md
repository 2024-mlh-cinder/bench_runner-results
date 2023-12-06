
# Results vs. 3.11.0

- fork: brandtbucher
- ref: justin
- machine: linux-x86_64
- commit hash: dfface9
- commit date: 2023-11-28
- overall geometric mean: 1.02x faster \*
- HPT reliability: 68.20%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231128-linux-x86_64-brandtbucher-justin-3.13.0a2+-dfface9 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| 2to3           | 266 ms                                                 | 273 ms: 1.03x slower                                           |
| chameleon      | 6.86 ms                                                | 7.19 ms: 1.05x slower                                          |
| docutils       | 2.69 sec                                               | 2.67 sec: 1.01x faster                                         |
| tornado_http   | 97.7 ms                                                | 97.0 ms: 1.01x faster                                          |
| Geometric mean | (ref)                                                  | 1.02x slower                                                   |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231128-linux-x86_64-brandtbucher-justin-3.13.0a2+-dfface9 |
|----------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| async_tree_none            | 532 ms                                                 | 443 ms: 1.20x faster                                           |
| async_tree_memoization     | 640 ms                                                 | 568 ms: 1.13x faster                                           |
| async_tree_io              | 1.31 sec                                               | 1.20 sec: 1.09x faster                                         |
| async_tree_none_tg         | 490 ms                                                 | 460 ms: 1.07x faster                                           |
| async_tree_io_tg           | 1.30 sec                                               | 1.23 sec: 1.06x faster                                         |
| async_tree_cpu_io_mixed    | 750 ms                                                 | 714 ms: 1.05x faster                                           |
| async_tree_cpu_io_mixed_tg | 764 ms                                                 | 746 ms: 1.02x faster                                           |
| async_tree_memoization_tg  | 627 ms                                                 | 616 ms: 1.02x faster                                           |
| Geometric mean             | (ref)                                                  | 1.08x faster                                                   |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231128-linux-x86_64-brandtbucher-justin-3.13.0a2+-dfface9 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| pidigits       | 190 ms                                                 | 196 ms: 1.03x slower                                           |
| nbody          | 91.6 ms                                                | 98.4 ms: 1.07x slower                                          |
| float          | 78.9 ms                                                | 84.9 ms: 1.08x slower                                          |
| Geometric mean | (ref)                                                  | 1.06x slower                                                   |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231128-linux-x86_64-brandtbucher-justin-3.13.0a2+-dfface9 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| regex_compile  | 141 ms                                                 | 143 ms: 1.01x slower                                           |
| regex_effbot   | 3.45 ms                                                | 3.71 ms: 1.08x slower                                          |
| regex_dna      | 204 ms                                                 | 222 ms: 1.09x slower                                           |
| regex_v8       | 22.9 ms                                                | 26.0 ms: 1.14x slower                                          |
| Geometric mean | (ref)                                                  | 1.08x slower                                                   |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231128-linux-x86_64-brandtbucher-justin-3.13.0a2+-dfface9 |
|----------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| json_dumps           | 13.5 ms                                                | 10.6 ms: 1.27x faster                                          |
| tomli_loads          | 2.31 sec                                               | 2.15 sec: 1.07x faster                                         |
| unpickle_list        | 5.22 us                                                | 4.96 us: 1.05x faster                                          |
| json_loads           | 29.4 us                                                | 28.1 us: 1.05x faster                                          |
| unpickle_pure_python | 241 us                                                 | 231 us: 1.05x faster                                           |
| pickle_pure_python   | 319 us                                                 | 305 us: 1.04x faster                                           |
| xml_etree_parse      | 163 ms                                                 | 161 ms: 1.01x faster                                           |
| xml_etree_iterparse  | 109 ms                                                 | 110 ms: 1.02x slower                                           |
| pickle_dict          | 34.8 us                                                | 36.4 us: 1.05x slower                                          |
| pickle               | 11.1 us                                                | 11.6 us: 1.05x slower                                          |
| xml_etree_process    | 56.5 ms                                                | 61.1 ms: 1.08x slower                                          |
| pickle_list          | 4.65 us                                                | 5.05 us: 1.09x slower                                          |
| xml_etree_generate   | 80.4 ms                                                | 88.6 ms: 1.10x slower                                          |
| unpickle             | 13.9 us                                                | 15.7 us: 1.13x slower                                          |
| Geometric mean       | (ref)                                                  | 1.00x faster                                                   |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231128-linux-x86_64-brandtbucher-justin-3.13.0a2+-dfface9 |
|------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| python_startup         | 8.69 ms                                                | 10.4 ms: 1.20x slower                                          |
| python_startup_no_site | 6.09 ms                                                | 9.11 ms: 1.50x slower                                          |
| Geometric mean         | (ref)                                                  | 1.34x slower                                                   |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231128-linux-x86_64-brandtbucher-justin-3.13.0a2+-dfface9 |
|-----------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| mako      | 10.8 ms                                                | 12.2 ms: 1.13x slower                                          |

All benchmarks:
===============

| Benchmark                  | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231128-linux-x86_64-brandtbucher-justin-3.13.0a2+-dfface9 |
|----------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| typing_runtime_protocols   | 521 us                                                 | 119 us: 4.37x faster                                           |
| generators                 | 76.5 ms                                                | 28.7 ms: 2.66x faster                                          |
| asyncio_tcp                | 887 ms                                                 | 494 ms: 1.79x faster                                           |
| asyncio_tcp_ssl            | 3.13 sec                                               | 1.79 sec: 1.75x faster                                         |
| json_dumps                 | 13.5 ms                                                | 10.6 ms: 1.27x faster                                          |
| comprehensions             | 23.6 us                                                | 19.3 us: 1.22x faster                                          |
| async_tree_none            | 532 ms                                                 | 443 ms: 1.20x faster                                           |
| richards_super             | 61.2 ms                                                | 52.3 ms: 1.17x faster                                          |
| coroutines                 | 26.1 ms                                                | 22.7 ms: 1.15x faster                                          |
| async_tree_memoization     | 640 ms                                                 | 568 ms: 1.13x faster                                           |
| sqlglot_parse              | 1.43 ms                                                | 1.30 ms: 1.10x faster                                          |
| async_tree_io              | 1.31 sec                                               | 1.20 sec: 1.09x faster                                         |
| sympy_sum                  | 170 ms                                                 | 157 ms: 1.08x faster                                           |
| sqlglot_transpile          | 1.75 ms                                                | 1.63 ms: 1.08x faster                                          |
| raytrace                   | 306 ms                                                 | 285 ms: 1.08x faster                                           |
| tomli_loads                | 2.31 sec                                               | 2.15 sec: 1.07x faster                                         |
| chaos                      | 71.4 ms                                                | 66.4 ms: 1.07x faster                                          |
| logging_simple             | 6.24 us                                                | 5.84 us: 1.07x faster                                          |
| sympy_str                  | 299 ms                                                 | 280 ms: 1.07x faster                                           |
| async_tree_none_tg         | 490 ms                                                 | 460 ms: 1.07x faster                                           |
| async_tree_io_tg           | 1.30 sec                                               | 1.23 sec: 1.06x faster                                         |
| logging_format             | 6.83 us                                                | 6.45 us: 1.06x faster                                          |
| unpickle_list              | 5.22 us                                                | 4.96 us: 1.05x faster                                          |
| async_tree_cpu_io_mixed    | 750 ms                                                 | 714 ms: 1.05x faster                                           |
| json_loads                 | 29.4 us                                                | 28.1 us: 1.05x faster                                          |
| unpickle_pure_python       | 241 us                                                 | 231 us: 1.05x faster                                           |
| pickle_pure_python         | 319 us                                                 | 305 us: 1.04x faster                                           |
| sympy_expand               | 490 ms                                                 | 470 ms: 1.04x faster                                           |
| richards                   | 48.9 ms                                                | 47.3 ms: 1.03x faster                                          |
| sympy_integrate            | 21.4 ms                                                | 20.7 ms: 1.03x faster                                          |
| async_tree_cpu_io_mixed_tg | 764 ms                                                 | 746 ms: 1.02x faster                                           |
| json                       | 5.24 ms                                                | 5.12 ms: 1.02x faster                                          |
| sqlglot_normalize          | 112 ms                                                 | 110 ms: 1.02x faster                                           |
| async_tree_memoization_tg  | 627 ms                                                 | 616 ms: 1.02x faster                                           |
| deepcopy                   | 360 us                                                 | 355 us: 1.01x faster                                           |
| gc_traversal               | 3.90 ms                                                | 3.85 ms: 1.01x faster                                          |
| pathlib                    | 18.5 ms                                                | 18.3 ms: 1.01x faster                                          |
| xml_etree_parse            | 163 ms                                                 | 161 ms: 1.01x faster                                           |
| deepcopy_reduce            | 3.14 us                                                | 3.11 us: 1.01x faster                                          |
| tornado_http               | 97.7 ms                                                | 97.0 ms: 1.01x faster                                          |
| docutils                   | 2.69 sec                                               | 2.67 sec: 1.01x faster                                         |
| asyncio_websockets         | 556 ms                                                 | 552 ms: 1.01x faster                                           |
| create_gc_cycles           | 1.48 ms                                                | 1.47 ms: 1.01x faster                                          |
| logging_silent             | 108 ns                                                 | 108 ns: 1.00x faster                                           |
| mdp                        | 2.79 sec                                               | 2.80 sec: 1.00x slower                                         |
| crypto_pyaes               | 77.5 ms                                                | 78.0 ms: 1.01x slower                                          |
| regex_compile              | 141 ms                                                 | 143 ms: 1.01x slower                                           |
| scimark_sor                | 121 ms                                                 | 123 ms: 1.01x slower                                           |
| pycparser                  | 1.20 sec                                               | 1.21 sec: 1.01x slower                                         |
| sqlglot_optimize           | 55.2 ms                                                | 55.8 ms: 1.01x slower                                          |
| xml_etree_iterparse        | 109 ms                                                 | 110 ms: 1.02x slower                                           |
| bench_thread_pool          | 833 us                                                 | 848 us: 1.02x slower                                           |
| deepcopy_memo              | 38.9 us                                                | 39.6 us: 1.02x slower                                          |
| dulwich_log                | 64.9 ms                                                | 66.5 ms: 1.02x slower                                          |
| 2to3                       | 266 ms                                                 | 273 ms: 1.03x slower                                           |
| pidigits                   | 190 ms                                                 | 196 ms: 1.03x slower                                           |
| meteor_contest             | 109 ms                                                 | 112 ms: 1.03x slower                                           |
| scimark_lu                 | 112 ms                                                 | 116 ms: 1.04x slower                                           |
| pprint_pformat             | 1.53 sec                                               | 1.59 sec: 1.04x slower                                         |
| pprint_safe_repr           | 743 ms                                                 | 775 ms: 1.04x slower                                           |
| pickle_dict                | 34.8 us                                                | 36.4 us: 1.05x slower                                          |
| fannkuch                   | 410 ms                                                 | 429 ms: 1.05x slower                                           |
| pickle                     | 11.1 us                                                | 11.6 us: 1.05x slower                                          |
| chameleon                  | 6.86 ms                                                | 7.19 ms: 1.05x slower                                          |
| go                         | 143 ms                                                 | 150 ms: 1.05x slower                                           |
| scimark_sparse_mat_mult    | 4.80 ms                                                | 5.06 ms: 1.05x slower                                          |
| nqueens                    | 86.8 ms                                                | 91.8 ms: 1.06x slower                                          |
| scimark_monte_carlo        | 71.8 ms                                                | 76.4 ms: 1.06x slower                                          |
| deltablue                  | 3.80 ms                                                | 4.07 ms: 1.07x slower                                          |
| nbody                      | 91.6 ms                                                | 98.4 ms: 1.07x slower                                          |
| regex_effbot               | 3.45 ms                                                | 3.71 ms: 1.08x slower                                          |
| float                      | 78.9 ms                                                | 84.9 ms: 1.08x slower                                          |
| xml_etree_process          | 56.5 ms                                                | 61.1 ms: 1.08x slower                                          |
| scimark_fft                | 342 ms                                                 | 371 ms: 1.08x slower                                           |
| sqlite_synth               | 2.58 us                                                | 2.80 us: 1.09x slower                                          |
| pickle_list                | 4.65 us                                                | 5.05 us: 1.09x slower                                          |
| regex_dna                  | 204 ms                                                 | 222 ms: 1.09x slower                                           |
| xml_etree_generate         | 80.4 ms                                                | 88.6 ms: 1.10x slower                                          |
| hexiom                     | 6.74 ms                                                | 7.52 ms: 1.12x slower                                          |
| mako                       | 10.8 ms                                                | 12.2 ms: 1.13x slower                                          |
| unpickle                   | 13.9 us                                                | 15.7 us: 1.13x slower                                          |
| regex_v8                   | 22.9 ms                                                | 26.0 ms: 1.14x slower                                          |
| coverage                   | 81.2 ms                                                | 93.9 ms: 1.16x slower                                          |
| pyflate                    | 426 ms                                                 | 493 ms: 1.16x slower                                           |
| python_startup             | 8.69 ms                                                | 10.4 ms: 1.20x slower                                          |
| telco                      | 6.72 ms                                                | 8.29 ms: 1.23x slower                                          |
| async_generators           | 375 ms                                                 | 465 ms: 1.24x slower                                           |
| unpack_sequence            | 43.3 ns                                                | 55.9 ns: 1.29x slower                                          |
| spectral_norm              | 105 ms                                                 | 138 ms: 1.31x slower                                           |
| python_startup_no_site     | 6.09 ms                                                | 9.11 ms: 1.50x slower                                          |
| mypy2                      | 427 ms                                                 | 861 ms: 2.02x slower                                           |
| Geometric mean             | (ref)                                                  | 1.02x faster                                                   |

Benchmark hidden because not significant (2): dask, bench_mp_pool
Ignored benchmarks (12) of results/bm-20221024-3.11.0-deaf509/bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift


# HPT report

- Reliability score: 68.20% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
