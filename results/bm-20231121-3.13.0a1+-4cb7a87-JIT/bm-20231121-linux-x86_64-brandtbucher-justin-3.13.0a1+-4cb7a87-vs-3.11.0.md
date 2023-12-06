
# Results vs. 3.11.0

- fork: brandtbucher
- ref: justin
- machine: linux-x86_64
- commit hash: 4cb7a87
- commit date: 2023-11-21
- overall geometric mean: 1.03x faster \*
- HPT reliability: 64.85%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231121-linux-x86_64-brandtbucher-justin-3.13.0a1+-4cb7a87 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| 2to3           | 266 ms                                                 | 274 ms: 1.03x slower                                           |
| chameleon      | 6.86 ms                                                | 7.19 ms: 1.05x slower                                          |
| docutils       | 2.69 sec                                               | 2.63 sec: 1.02x faster                                         |
| tornado_http   | 97.7 ms                                                | 96.8 ms: 1.01x faster                                          |
| Geometric mean | (ref)                                                  | 1.01x slower                                                   |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231121-linux-x86_64-brandtbucher-justin-3.13.0a1+-4cb7a87 |
|----------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| async_tree_none            | 532 ms                                                 | 444 ms: 1.20x faster                                           |
| async_tree_memoization     | 640 ms                                                 | 567 ms: 1.13x faster                                           |
| async_tree_io              | 1.31 sec                                               | 1.20 sec: 1.09x faster                                         |
| async_tree_none_tg         | 490 ms                                                 | 462 ms: 1.06x faster                                           |
| async_tree_io_tg           | 1.30 sec                                               | 1.24 sec: 1.05x faster                                         |
| async_tree_cpu_io_mixed    | 750 ms                                                 | 717 ms: 1.05x faster                                           |
| async_tree_memoization_tg  | 627 ms                                                 | 608 ms: 1.03x faster                                           |
| async_tree_cpu_io_mixed_tg | 764 ms                                                 | 749 ms: 1.02x faster                                           |
| Geometric mean             | (ref)                                                  | 1.08x faster                                                   |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231121-linux-x86_64-brandtbucher-justin-3.13.0a1+-4cb7a87 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| pidigits       | 190 ms                                                 | 187 ms: 1.02x faster                                           |
| float          | 78.9 ms                                                | 84.7 ms: 1.07x slower                                          |
| nbody          | 91.6 ms                                                | 98.2 ms: 1.07x slower                                          |
| Geometric mean | (ref)                                                  | 1.04x slower                                                   |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231121-linux-x86_64-brandtbucher-justin-3.13.0a1+-4cb7a87 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| regex_compile  | 141 ms                                                 | 142 ms: 1.00x slower                                           |
| regex_effbot   | 3.45 ms                                                | 3.51 ms: 1.02x slower                                          |
| regex_v8       | 22.9 ms                                                | 24.4 ms: 1.07x slower                                          |
| regex_dna      | 204 ms                                                 | 218 ms: 1.07x slower                                           |
| Geometric mean | (ref)                                                  | 1.04x slower                                                   |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231121-linux-x86_64-brandtbucher-justin-3.13.0a1+-4cb7a87 |
|----------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| json_dumps           | 13.5 ms                                                | 10.7 ms: 1.26x faster                                          |
| tomli_loads          | 2.31 sec                                               | 2.15 sec: 1.08x faster                                         |
| unpickle_list        | 5.22 us                                                | 4.94 us: 1.06x faster                                          |
| pickle_pure_python   | 319 us                                                 | 302 us: 1.05x faster                                           |
| unpickle_pure_python | 241 us                                                 | 229 us: 1.05x faster                                           |
| json_loads           | 29.4 us                                                | 28.2 us: 1.05x faster                                          |
| xml_etree_parse      | 163 ms                                                 | 159 ms: 1.03x faster                                           |
| pickle_dict          | 34.8 us                                                | 34.4 us: 1.01x faster                                          |
| xml_etree_iterparse  | 109 ms                                                 | 109 ms: 1.01x slower                                           |
| pickle               | 11.1 us                                                | 11.4 us: 1.03x slower                                          |
| xml_etree_process    | 56.5 ms                                                | 60.6 ms: 1.07x slower                                          |
| xml_etree_generate   | 80.4 ms                                                | 88.2 ms: 1.10x slower                                          |
| unpickle             | 13.9 us                                                | 15.4 us: 1.11x slower                                          |
| pickle_list          | 4.65 us                                                | 5.20 us: 1.12x slower                                          |
| Geometric mean       | (ref)                                                  | 1.01x faster                                                   |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231121-linux-x86_64-brandtbucher-justin-3.13.0a1+-4cb7a87 |
|------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| python_startup         | 8.69 ms                                                | 10.5 ms: 1.21x slower                                          |
| python_startup_no_site | 6.09 ms                                                | 9.16 ms: 1.50x slower                                          |
| Geometric mean         | (ref)                                                  | 1.35x slower                                                   |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231121-linux-x86_64-brandtbucher-justin-3.13.0a1+-4cb7a87 |
|-----------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| mako      | 10.8 ms                                                | 12.3 ms: 1.13x slower                                          |

All benchmarks:
===============

| Benchmark                  | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231121-linux-x86_64-brandtbucher-justin-3.13.0a1+-4cb7a87 |
|----------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| typing_runtime_protocols   | 521 us                                                 | 118 us: 4.42x faster                                           |
| generators                 | 76.5 ms                                                | 29.4 ms: 2.60x faster                                          |
| asyncio_tcp                | 887 ms                                                 | 494 ms: 1.79x faster                                           |
| asyncio_tcp_ssl            | 3.13 sec                                               | 1.80 sec: 1.74x faster                                         |
| json_dumps                 | 13.5 ms                                                | 10.7 ms: 1.26x faster                                          |
| comprehensions             | 23.6 us                                                | 19.2 us: 1.23x faster                                          |
| mypy2                      | 427 ms                                                 | 352 ms: 1.21x faster                                           |
| async_tree_none            | 532 ms                                                 | 444 ms: 1.20x faster                                           |
| coroutines                 | 26.1 ms                                                | 22.2 ms: 1.18x faster                                          |
| richards_super             | 61.2 ms                                                | 52.7 ms: 1.16x faster                                          |
| async_tree_memoization     | 640 ms                                                 | 567 ms: 1.13x faster                                           |
| async_tree_io              | 1.31 sec                                               | 1.20 sec: 1.09x faster                                         |
| sympy_sum                  | 170 ms                                                 | 156 ms: 1.09x faster                                           |
| sqlglot_parse              | 1.43 ms                                                | 1.32 ms: 1.09x faster                                          |
| tomli_loads                | 2.31 sec                                               | 2.15 sec: 1.08x faster                                         |
| raytrace                   | 306 ms                                                 | 284 ms: 1.08x faster                                           |
| sqlglot_transpile          | 1.75 ms                                                | 1.64 ms: 1.07x faster                                          |
| sympy_str                  | 299 ms                                                 | 279 ms: 1.07x faster                                           |
| mdp                        | 2.79 sec                                               | 2.61 sec: 1.07x faster                                         |
| logging_simple             | 6.24 us                                                | 5.86 us: 1.07x faster                                          |
| logging_format             | 6.83 us                                                | 6.41 us: 1.07x faster                                          |
| gc_traversal               | 3.90 ms                                                | 3.67 ms: 1.07x faster                                          |
| chaos                      | 71.4 ms                                                | 67.0 ms: 1.07x faster                                          |
| async_tree_none_tg         | 490 ms                                                 | 462 ms: 1.06x faster                                           |
| unpickle_list              | 5.22 us                                                | 4.94 us: 1.06x faster                                          |
| async_tree_io_tg           | 1.30 sec                                               | 1.24 sec: 1.05x faster                                         |
| pickle_pure_python         | 319 us                                                 | 302 us: 1.05x faster                                           |
| unpickle_pure_python       | 241 us                                                 | 229 us: 1.05x faster                                           |
| sympy_expand               | 490 ms                                                 | 467 ms: 1.05x faster                                           |
| json_loads                 | 29.4 us                                                | 28.2 us: 1.05x faster                                          |
| async_tree_cpu_io_mixed    | 750 ms                                                 | 717 ms: 1.05x faster                                           |
| richards                   | 48.9 ms                                                | 47.4 ms: 1.03x faster                                          |
| sympy_integrate            | 21.4 ms                                                | 20.7 ms: 1.03x faster                                          |
| async_tree_memoization_tg  | 627 ms                                                 | 608 ms: 1.03x faster                                           |
| deepcopy                   | 360 us                                                 | 350 us: 1.03x faster                                           |
| sqlglot_normalize          | 112 ms                                                 | 109 ms: 1.03x faster                                           |
| xml_etree_parse            | 163 ms                                                 | 159 ms: 1.03x faster                                           |
| docutils                   | 2.69 sec                                               | 2.63 sec: 1.02x faster                                         |
| pycparser                  | 1.20 sec                                               | 1.17 sec: 1.02x faster                                         |
| async_tree_cpu_io_mixed_tg | 764 ms                                                 | 749 ms: 1.02x faster                                           |
| pidigits                   | 190 ms                                                 | 187 ms: 1.02x faster                                           |
| pickle_dict                | 34.8 us                                                | 34.4 us: 1.01x faster                                          |
| tornado_http               | 97.7 ms                                                | 96.8 ms: 1.01x faster                                          |
| deepcopy_reduce            | 3.14 us                                                | 3.11 us: 1.01x faster                                          |
| json                       | 5.24 ms                                                | 5.19 ms: 1.01x faster                                          |
| create_gc_cycles           | 1.48 ms                                                | 1.47 ms: 1.01x faster                                          |
| asyncio_websockets         | 556 ms                                                 | 552 ms: 1.01x faster                                           |
| logging_silent             | 108 ns                                                 | 108 ns: 1.00x faster                                           |
| regex_compile              | 141 ms                                                 | 142 ms: 1.00x slower                                           |
| xml_etree_iterparse        | 109 ms                                                 | 109 ms: 1.01x slower                                           |
| crypto_pyaes               | 77.5 ms                                                | 78.1 ms: 1.01x slower                                          |
| regex_effbot               | 3.45 ms                                                | 3.51 ms: 1.02x slower                                          |
| dulwich_log                | 64.9 ms                                                | 66.2 ms: 1.02x slower                                          |
| bench_thread_pool          | 833 us                                                 | 852 us: 1.02x slower                                           |
| meteor_contest             | 109 ms                                                 | 112 ms: 1.02x slower                                           |
| 2to3                       | 266 ms                                                 | 274 ms: 1.03x slower                                           |
| pickle                     | 11.1 us                                                | 11.4 us: 1.03x slower                                          |
| go                         | 143 ms                                                 | 149 ms: 1.04x slower                                           |
| pprint_pformat             | 1.53 sec                                               | 1.59 sec: 1.04x slower                                         |
| pprint_safe_repr           | 743 ms                                                 | 777 ms: 1.05x slower                                           |
| chameleon                  | 6.86 ms                                                | 7.19 ms: 1.05x slower                                          |
| scimark_lu                 | 112 ms                                                 | 118 ms: 1.05x slower                                           |
| fannkuch                   | 410 ms                                                 | 431 ms: 1.05x slower                                           |
| scimark_sor                | 121 ms                                                 | 128 ms: 1.06x slower                                           |
| deltablue                  | 3.80 ms                                                | 4.05 ms: 1.07x slower                                          |
| nqueens                    | 86.8 ms                                                | 92.6 ms: 1.07x slower                                          |
| regex_v8                   | 22.9 ms                                                | 24.4 ms: 1.07x slower                                          |
| regex_dna                  | 204 ms                                                 | 218 ms: 1.07x slower                                           |
| scimark_monte_carlo        | 71.8 ms                                                | 76.7 ms: 1.07x slower                                          |
| float                      | 78.9 ms                                                | 84.7 ms: 1.07x slower                                          |
| nbody                      | 91.6 ms                                                | 98.2 ms: 1.07x slower                                          |
| xml_etree_process          | 56.5 ms                                                | 60.6 ms: 1.07x slower                                          |
| scimark_sparse_mat_mult    | 4.80 ms                                                | 5.19 ms: 1.08x slower                                          |
| sqlite_synth               | 2.58 us                                                | 2.80 us: 1.09x slower                                          |
| xml_etree_generate         | 80.4 ms                                                | 88.2 ms: 1.10x slower                                          |
| scimark_fft                | 342 ms                                                 | 377 ms: 1.10x slower                                           |
| unpickle                   | 13.9 us                                                | 15.4 us: 1.11x slower                                          |
| pickle_list                | 4.65 us                                                | 5.20 us: 1.12x slower                                          |
| hexiom                     | 6.74 ms                                                | 7.59 ms: 1.13x slower                                          |
| mako                       | 10.8 ms                                                | 12.3 ms: 1.13x slower                                          |
| pyflate                    | 426 ms                                                 | 500 ms: 1.17x slower                                           |
| coverage                   | 81.2 ms                                                | 95.6 ms: 1.18x slower                                          |
| python_startup             | 8.69 ms                                                | 10.5 ms: 1.21x slower                                          |
| async_generators           | 375 ms                                                 | 459 ms: 1.22x slower                                           |
| telco                      | 6.72 ms                                                | 8.46 ms: 1.26x slower                                          |
| spectral_norm              | 105 ms                                                 | 137 ms: 1.30x slower                                           |
| unpack_sequence            | 43.3 ns                                                | 57.4 ns: 1.33x slower                                          |
| python_startup_no_site     | 6.09 ms                                                | 9.16 ms: 1.50x slower                                          |
| Geometric mean             | (ref)                                                  | 1.03x faster                                                   |

Benchmark hidden because not significant (5): pathlib, sqlglot_optimize, bench_mp_pool, deepcopy_memo, dask
Ignored benchmarks (12) of results/bm-20221024-3.11.0-deaf509/bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift


# HPT report

- Reliability score: 64.85% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
