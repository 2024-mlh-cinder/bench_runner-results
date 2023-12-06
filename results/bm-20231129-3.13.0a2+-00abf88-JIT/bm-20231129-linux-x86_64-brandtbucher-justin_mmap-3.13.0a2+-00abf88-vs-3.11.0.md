
# Results vs. 3.11.0

- fork: brandtbucher
- ref: justin_mmap
- machine: linux-x86_64
- commit hash: 00abf88
- commit date: 2023-11-29
- overall geometric mean: 1.01x faster \*
- HPT reliability: 86.05%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231129-linux-x86_64-brandtbucher-justin_mmap-3.13.0a2+-00abf88 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------------:|
| 2to3           | 266 ms                                                 | 277 ms: 1.04x slower                                                |
| chameleon      | 6.86 ms                                                | 7.08 ms: 1.03x slower                                               |
| Geometric mean | (ref)                                                  | 1.02x slower                                                        |

Benchmark hidden because not significant (2): docutils, tornado_http

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231129-linux-x86_64-brandtbucher-justin_mmap-3.13.0a2+-00abf88 |
|----------------------------|:------------------------------------------------------:|:-------------------------------------------------------------------:|
| async_tree_none            | 532 ms                                                 | 442 ms: 1.20x faster                                                |
| async_tree_memoization     | 640 ms                                                 | 574 ms: 1.11x faster                                                |
| async_tree_io              | 1.31 sec                                               | 1.19 sec: 1.10x faster                                              |
| async_tree_none_tg         | 490 ms                                                 | 458 ms: 1.07x faster                                                |
| async_tree_io_tg           | 1.30 sec                                               | 1.23 sec: 1.06x faster                                              |
| async_tree_cpu_io_mixed    | 750 ms                                                 | 713 ms: 1.05x faster                                                |
| async_tree_memoization_tg  | 627 ms                                                 | 606 ms: 1.03x faster                                                |
| async_tree_cpu_io_mixed_tg | 764 ms                                                 | 741 ms: 1.03x faster                                                |
| Geometric mean             | (ref)                                                  | 1.08x faster                                                        |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231129-linux-x86_64-brandtbucher-justin_mmap-3.13.0a2+-00abf88 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------------:|
| pidigits       | 190 ms                                                 | 188 ms: 1.01x faster                                                |
| float          | 78.9 ms                                                | 85.5 ms: 1.08x slower                                               |
| nbody          | 91.6 ms                                                | 101 ms: 1.11x slower                                                |
| Geometric mean | (ref)                                                  | 1.06x slower                                                        |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231129-linux-x86_64-brandtbucher-justin_mmap-3.13.0a2+-00abf88 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------------:|
| regex_compile  | 141 ms                                                 | 146 ms: 1.03x slower                                                |
| regex_effbot   | 3.45 ms                                                | 3.73 ms: 1.08x slower                                               |
| regex_dna      | 204 ms                                                 | 222 ms: 1.09x slower                                                |
| regex_v8       | 22.9 ms                                                | 26.0 ms: 1.14x slower                                               |
| Geometric mean | (ref)                                                  | 1.08x slower                                                        |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231129-linux-x86_64-brandtbucher-justin_mmap-3.13.0a2+-00abf88 |
|----------------------|:------------------------------------------------------:|:-------------------------------------------------------------------:|
| json_dumps           | 13.5 ms                                                | 10.6 ms: 1.27x faster                                               |
| json_loads           | 29.4 us                                                | 28.1 us: 1.05x faster                                               |
| tomli_loads          | 2.31 sec                                               | 2.22 sec: 1.04x faster                                              |
| pickle_pure_python   | 319 us                                                 | 307 us: 1.04x faster                                                |
| unpickle_pure_python | 241 us                                                 | 233 us: 1.03x faster                                                |
| xml_etree_parse      | 163 ms                                                 | 159 ms: 1.02x faster                                                |
| unpickle_list        | 5.22 us                                                | 5.11 us: 1.02x faster                                               |
| pickle_dict          | 34.8 us                                                | 35.6 us: 1.02x slower                                               |
| xml_etree_iterparse  | 109 ms                                                 | 111 ms: 1.02x slower                                                |
| pickle               | 11.1 us                                                | 11.7 us: 1.06x slower                                               |
| pickle_list          | 4.65 us                                                | 5.05 us: 1.09x slower                                               |
| xml_etree_process    | 56.5 ms                                                | 61.4 ms: 1.09x slower                                               |
| xml_etree_generate   | 80.4 ms                                                | 89.4 ms: 1.11x slower                                               |
| unpickle             | 13.9 us                                                | 15.5 us: 1.12x slower                                               |
| Geometric mean       | (ref)                                                  | 1.00x slower                                                        |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231129-linux-x86_64-brandtbucher-justin_mmap-3.13.0a2+-00abf88 |
|------------------------|:------------------------------------------------------:|:-------------------------------------------------------------------:|
| python_startup         | 8.69 ms                                                | 10.5 ms: 1.20x slower                                               |
| python_startup_no_site | 6.09 ms                                                | 9.13 ms: 1.50x slower                                               |
| Geometric mean         | (ref)                                                  | 1.34x slower                                                        |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231129-linux-x86_64-brandtbucher-justin_mmap-3.13.0a2+-00abf88 |
|-----------|:------------------------------------------------------:|:-------------------------------------------------------------------:|
| mako      | 10.8 ms                                                | 12.3 ms: 1.14x slower                                               |

All benchmarks:
===============

| Benchmark                  | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231129-linux-x86_64-brandtbucher-justin_mmap-3.13.0a2+-00abf88 |
|----------------------------|:------------------------------------------------------:|:-------------------------------------------------------------------:|
| typing_runtime_protocols   | 521 us                                                 | 119 us: 4.36x faster                                                |
| generators                 | 76.5 ms                                                | 28.8 ms: 2.66x faster                                               |
| asyncio_tcp                | 887 ms                                                 | 489 ms: 1.81x faster                                                |
| asyncio_tcp_ssl            | 3.13 sec                                               | 1.79 sec: 1.74x faster                                              |
| json_dumps                 | 13.5 ms                                                | 10.6 ms: 1.27x faster                                               |
| comprehensions             | 23.6 us                                                | 19.5 us: 1.21x faster                                               |
| async_tree_none            | 532 ms                                                 | 442 ms: 1.20x faster                                                |
| coroutines                 | 26.1 ms                                                | 22.6 ms: 1.16x faster                                               |
| richards_super             | 61.2 ms                                                | 53.3 ms: 1.15x faster                                               |
| async_tree_memoization     | 640 ms                                                 | 574 ms: 1.11x faster                                                |
| async_tree_io              | 1.31 sec                                               | 1.19 sec: 1.10x faster                                              |
| sqlglot_parse              | 1.43 ms                                                | 1.32 ms: 1.08x faster                                               |
| logging_simple             | 6.24 us                                                | 5.82 us: 1.07x faster                                               |
| async_tree_none_tg         | 490 ms                                                 | 458 ms: 1.07x faster                                                |
| sqlglot_transpile          | 1.75 ms                                                | 1.65 ms: 1.06x faster                                               |
| sympy_sum                  | 170 ms                                                 | 160 ms: 1.06x faster                                                |
| async_tree_io_tg           | 1.30 sec                                               | 1.23 sec: 1.06x faster                                              |
| raytrace                   | 306 ms                                                 | 289 ms: 1.06x faster                                                |
| logging_format             | 6.83 us                                                | 6.45 us: 1.06x faster                                               |
| async_tree_cpu_io_mixed    | 750 ms                                                 | 713 ms: 1.05x faster                                                |
| json_loads                 | 29.4 us                                                | 28.1 us: 1.05x faster                                               |
| tomli_loads                | 2.31 sec                                               | 2.22 sec: 1.04x faster                                              |
| richards                   | 48.9 ms                                                | 46.9 ms: 1.04x faster                                               |
| pickle_pure_python         | 319 us                                                 | 307 us: 1.04x faster                                                |
| sympy_str                  | 299 ms                                                 | 288 ms: 1.04x faster                                                |
| unpickle_pure_python       | 241 us                                                 | 233 us: 1.03x faster                                                |
| async_tree_memoization_tg  | 627 ms                                                 | 606 ms: 1.03x faster                                                |
| async_tree_cpu_io_mixed_tg | 764 ms                                                 | 741 ms: 1.03x faster                                                |
| sympy_expand               | 490 ms                                                 | 479 ms: 1.02x faster                                                |
| xml_etree_parse            | 163 ms                                                 | 159 ms: 1.02x faster                                                |
| unpickle_list              | 5.22 us                                                | 5.11 us: 1.02x faster                                               |
| deepcopy                   | 360 us                                                 | 353 us: 1.02x faster                                                |
| chaos                      | 71.4 ms                                                | 70.1 ms: 1.02x faster                                               |
| pidigits                   | 190 ms                                                 | 188 ms: 1.01x faster                                                |
| sqlglot_normalize          | 112 ms                                                 | 111 ms: 1.01x faster                                                |
| create_gc_cycles           | 1.48 ms                                                | 1.46 ms: 1.01x faster                                               |
| sympy_integrate            | 21.4 ms                                                | 21.2 ms: 1.01x faster                                               |
| asyncio_websockets         | 556 ms                                                 | 551 ms: 1.01x faster                                                |
| logging_silent             | 108 ns                                                 | 109 ns: 1.01x slower                                                |
| pathlib                    | 18.5 ms                                                | 18.7 ms: 1.01x slower                                               |
| mdp                        | 2.79 sec                                               | 2.82 sec: 1.01x slower                                              |
| crypto_pyaes               | 77.5 ms                                                | 79.0 ms: 1.02x slower                                               |
| pycparser                  | 1.20 sec                                               | 1.22 sec: 1.02x slower                                              |
| bench_thread_pool          | 833 us                                                 | 852 us: 1.02x slower                                                |
| pickle_dict                | 34.8 us                                                | 35.6 us: 1.02x slower                                               |
| xml_etree_iterparse        | 109 ms                                                 | 111 ms: 1.02x slower                                                |
| meteor_contest             | 109 ms                                                 | 112 ms: 1.03x slower                                                |
| sqlglot_optimize           | 55.2 ms                                                | 56.7 ms: 1.03x slower                                               |
| regex_compile              | 141 ms                                                 | 146 ms: 1.03x slower                                                |
| scimark_sor                | 121 ms                                                 | 125 ms: 1.03x slower                                                |
| chameleon                  | 6.86 ms                                                | 7.08 ms: 1.03x slower                                               |
| scimark_lu                 | 112 ms                                                 | 116 ms: 1.03x slower                                                |
| dulwich_log                | 64.9 ms                                                | 67.5 ms: 1.04x slower                                               |
| 2to3                       | 266 ms                                                 | 277 ms: 1.04x slower                                                |
| pickle                     | 11.1 us                                                | 11.7 us: 1.06x slower                                               |
| go                         | 143 ms                                                 | 151 ms: 1.06x slower                                                |
| pprint_safe_repr           | 743 ms                                                 | 785 ms: 1.06x slower                                                |
| pprint_pformat             | 1.53 sec                                               | 1.62 sec: 1.06x slower                                              |
| gc_traversal               | 3.90 ms                                                | 4.16 ms: 1.07x slower                                               |
| fannkuch                   | 410 ms                                                 | 438 ms: 1.07x slower                                                |
| scimark_monte_carlo        | 71.8 ms                                                | 76.9 ms: 1.07x slower                                               |
| deltablue                  | 3.80 ms                                                | 4.10 ms: 1.08x slower                                               |
| regex_effbot               | 3.45 ms                                                | 3.73 ms: 1.08x slower                                               |
| float                      | 78.9 ms                                                | 85.5 ms: 1.08x slower                                               |
| nqueens                    | 86.8 ms                                                | 94.4 ms: 1.09x slower                                               |
| pickle_list                | 4.65 us                                                | 5.05 us: 1.09x slower                                               |
| xml_etree_process          | 56.5 ms                                                | 61.4 ms: 1.09x slower                                               |
| regex_dna                  | 204 ms                                                 | 222 ms: 1.09x slower                                                |
| sqlite_synth               | 2.58 us                                                | 2.83 us: 1.10x slower                                               |
| scimark_sparse_mat_mult    | 4.80 ms                                                | 5.28 ms: 1.10x slower                                               |
| nbody                      | 91.6 ms                                                | 101 ms: 1.11x slower                                                |
| xml_etree_generate         | 80.4 ms                                                | 89.4 ms: 1.11x slower                                               |
| unpickle                   | 13.9 us                                                | 15.5 us: 1.12x slower                                               |
| scimark_fft                | 342 ms                                                 | 384 ms: 1.12x slower                                                |
| regex_v8                   | 22.9 ms                                                | 26.0 ms: 1.14x slower                                               |
| mako                       | 10.8 ms                                                | 12.3 ms: 1.14x slower                                               |
| pyflate                    | 426 ms                                                 | 501 ms: 1.18x slower                                                |
| hexiom                     | 6.74 ms                                                | 7.94 ms: 1.18x slower                                               |
| coverage                   | 81.2 ms                                                | 96.2 ms: 1.18x slower                                               |
| python_startup             | 8.69 ms                                                | 10.5 ms: 1.20x slower                                               |
| async_generators           | 375 ms                                                 | 463 ms: 1.23x slower                                                |
| telco                      | 6.72 ms                                                | 8.51 ms: 1.27x slower                                               |
| spectral_norm              | 105 ms                                                 | 141 ms: 1.34x slower                                                |
| unpack_sequence            | 43.3 ns                                                | 58.1 ns: 1.34x slower                                               |
| python_startup_no_site     | 6.09 ms                                                | 9.13 ms: 1.50x slower                                               |
| mypy2                      | 427 ms                                                 | 870 ms: 2.04x slower                                                |
| Geometric mean             | (ref)                                                  | 1.01x faster                                                        |

Benchmark hidden because not significant (7): json, tornado_http, bench_mp_pool, deepcopy_reduce, docutils, deepcopy_memo, dask
Ignored benchmarks (12) of results/bm-20221024-3.11.0-deaf509/bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift


# HPT report

- Reliability score: 86.05% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
