
# Results vs. 3.11.0

- fork: python
- ref: 3.12
- machine: linux-x86_64
- commit hash: 9c583f3
- commit date: 2023-11-04
- overall geometric mean: 1.03x faster \*
- HPT reliability: 64.97%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231104-linux-x86_64-python-3.12-3.12.0+-9c583f3 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------:|
| 2to3           | 266 ms                                                 | 273 ms: 1.03x slower                                 |
| chameleon      | 6.86 ms                                                | 7.27 ms: 1.06x slower                                |
| docutils       | 2.69 sec                                               | 2.71 sec: 1.01x slower                               |
| tornado_http   | 97.7 ms                                                | 99.2 ms: 1.02x slower                                |
| Geometric mean | (ref)                                                  | 1.03x slower                                         |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231104-linux-x86_64-python-3.12-3.12.0+-9c583f3 |
|----------------------------|:------------------------------------------------------:|:----------------------------------------------------:|
| async_tree_io              | 1.31 sec                                               | 1.17 sec: 1.12x faster                               |
| async_tree_none            | 532 ms                                                 | 477 ms: 1.11x faster                                 |
| async_tree_memoization     | 640 ms                                                 | 581 ms: 1.10x faster                                 |
| async_tree_memoization_tg  | 627 ms                                                 | 575 ms: 1.09x faster                                 |
| async_tree_io_tg           | 1.30 sec                                               | 1.20 sec: 1.09x faster                               |
| async_tree_none_tg         | 490 ms                                                 | 451 ms: 1.09x faster                                 |
| async_tree_cpu_io_mixed_tg | 764 ms                                                 | 726 ms: 1.05x faster                                 |
| async_tree_cpu_io_mixed    | 750 ms                                                 | 727 ms: 1.03x faster                                 |
| Geometric mean             | (ref)                                                  | 1.09x faster                                         |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231104-linux-x86_64-python-3.12-3.12.0+-9c583f3 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------:|
| pidigits       | 190 ms                                                 | 187 ms: 1.02x faster                                 |
| nbody          | 91.6 ms                                                | 90.3 ms: 1.01x faster                                |
| float          | 78.9 ms                                                | 84.1 ms: 1.07x slower                                |
| Geometric mean | (ref)                                                  | 1.01x slower                                         |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231104-linux-x86_64-python-3.12-3.12.0+-9c583f3 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------:|
| regex_v8       | 22.9 ms                                                | 22.9 ms: 1.00x slower                                |
| regex_compile  | 141 ms                                                 | 146 ms: 1.03x slower                                 |
| regex_dna      | 204 ms                                                 | 213 ms: 1.05x slower                                 |
| regex_effbot   | 3.45 ms                                                | 3.87 ms: 1.12x slower                                |
| Geometric mean | (ref)                                                  | 1.05x slower                                         |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231104-linux-x86_64-python-3.12-3.12.0+-9c583f3 |
|----------------------|:------------------------------------------------------:|:----------------------------------------------------:|
| json_dumps           | 13.5 ms                                                | 10.6 ms: 1.27x faster                                |
| pickle_dict          | 34.8 us                                                | 31.9 us: 1.09x faster                                |
| unpickle_pure_python | 241 us                                                 | 226 us: 1.07x faster                                 |
| json_loads           | 29.4 us                                                | 28.4 us: 1.04x faster                                |
| xml_etree_iterparse  | 109 ms                                                 | 106 ms: 1.03x faster                                 |
| xml_etree_parse      | 163 ms                                                 | 160 ms: 1.02x faster                                 |
| tomli_loads          | 2.31 sec                                               | 2.28 sec: 1.01x faster                               |
| pickle_pure_python   | 319 us                                                 | 323 us: 1.01x slower                                 |
| unpickle_list        | 5.22 us                                                | 5.36 us: 1.03x slower                                |
| pickle_list          | 4.65 us                                                | 5.01 us: 1.08x slower                                |
| xml_etree_process    | 56.5 ms                                                | 61.9 ms: 1.10x slower                                |
| xml_etree_generate   | 80.4 ms                                                | 89.6 ms: 1.11x slower                                |
| unpickle             | 13.9 us                                                | 16.1 us: 1.16x slower                                |
| Geometric mean       | (ref)                                                  | 1.00x faster                                         |

Benchmark hidden because not significant (1): pickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231104-linux-x86_64-python-3.12-3.12.0+-9c583f3 |
|------------------------|:------------------------------------------------------:|:----------------------------------------------------:|
| python_startup         | 8.69 ms                                                | 9.49 ms: 1.09x slower                                |
| python_startup_no_site | 6.09 ms                                                | 6.88 ms: 1.13x slower                                |
| Geometric mean         | (ref)                                                  | 1.11x slower                                         |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231104-linux-x86_64-python-3.12-3.12.0+-9c583f3 |
|-----------------|:------------------------------------------------------:|:----------------------------------------------------:|
| django_template | 33.8 ms                                                | 34.5 ms: 1.02x slower                                |
| mako            | 10.8 ms                                                | 11.5 ms: 1.07x slower                                |
| Geometric mean  | (ref)                                                  | 1.04x slower                                         |

All benchmarks:
===============

| Benchmark                  | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231104-linux-x86_64-python-3.12-3.12.0+-9c583f3 |
|----------------------------|:------------------------------------------------------:|:----------------------------------------------------:|
| typing_runtime_protocols   | 521 us                                                 | 121 us: 4.32x faster                                 |
| generators                 | 76.5 ms                                                | 32.8 ms: 2.33x faster                                |
| asyncio_tcp                | 887 ms                                                 | 509 ms: 1.74x faster                                 |
| asyncio_tcp_ssl            | 3.13 sec                                               | 1.80 sec: 1.74x faster                               |
| json_dumps                 | 13.5 ms                                                | 10.6 ms: 1.27x faster                                |
| richards_super             | 61.2 ms                                                | 51.1 ms: 1.20x faster                                |
| comprehensions             | 23.6 us                                                | 20.6 us: 1.15x faster                                |
| coroutines                 | 26.1 ms                                                | 23.1 ms: 1.13x faster                                |
| async_tree_io              | 1.31 sec                                               | 1.17 sec: 1.12x faster                               |
| async_tree_none            | 532 ms                                                 | 477 ms: 1.11x faster                                 |
| async_tree_memoization     | 640 ms                                                 | 581 ms: 1.10x faster                                 |
| pickle_dict                | 34.8 us                                                | 31.9 us: 1.09x faster                                |
| async_tree_memoization_tg  | 627 ms                                                 | 575 ms: 1.09x faster                                 |
| async_tree_io_tg           | 1.30 sec                                               | 1.20 sec: 1.09x faster                               |
| async_tree_none_tg         | 490 ms                                                 | 451 ms: 1.09x faster                                 |
| richards                   | 48.9 ms                                                | 45.3 ms: 1.08x faster                                |
| chaos                      | 71.4 ms                                                | 66.2 ms: 1.08x faster                                |
| coverage                   | 81.2 ms                                                | 75.4 ms: 1.08x faster                                |
| mdp                        | 2.79 sec                                               | 2.59 sec: 1.08x faster                               |
| unpickle_pure_python       | 241 us                                                 | 226 us: 1.07x faster                                 |
| hexiom                     | 6.74 ms                                                | 6.38 ms: 1.06x faster                                |
| async_tree_cpu_io_mixed_tg | 764 ms                                                 | 726 ms: 1.05x faster                                 |
| sqlglot_parse              | 1.43 ms                                                | 1.37 ms: 1.05x faster                                |
| nqueens                    | 86.8 ms                                                | 83.5 ms: 1.04x faster                                |
| deltablue                  | 3.80 ms                                                | 3.67 ms: 1.04x faster                                |
| sqlglot_transpile          | 1.75 ms                                                | 1.69 ms: 1.04x faster                                |
| json_loads                 | 29.4 us                                                | 28.4 us: 1.04x faster                                |
| sympy_sum                  | 170 ms                                                 | 165 ms: 1.03x faster                                 |
| gc_traversal               | 3.90 ms                                                | 3.78 ms: 1.03x faster                                |
| async_tree_cpu_io_mixed    | 750 ms                                                 | 727 ms: 1.03x faster                                 |
| sympy_integrate            | 21.4 ms                                                | 20.7 ms: 1.03x faster                                |
| xml_etree_iterparse        | 109 ms                                                 | 106 ms: 1.03x faster                                 |
| sympy_expand               | 490 ms                                                 | 478 ms: 1.03x faster                                 |
| logging_silent             | 108 ns                                                 | 106 ns: 1.02x faster                                 |
| sqlglot_normalize          | 112 ms                                                 | 110 ms: 1.02x faster                                 |
| go                         | 143 ms                                                 | 140 ms: 1.02x faster                                 |
| pidigits                   | 190 ms                                                 | 187 ms: 1.02x faster                                 |
| xml_etree_parse            | 163 ms                                                 | 160 ms: 1.02x faster                                 |
| tomli_loads                | 2.31 sec                                               | 2.28 sec: 1.01x faster                               |
| create_gc_cycles           | 1.48 ms                                                | 1.45 ms: 1.01x faster                                |
| nbody                      | 91.6 ms                                                | 90.3 ms: 1.01x faster                                |
| asyncio_websockets         | 556 ms                                                 | 551 ms: 1.01x faster                                 |
| sqlglot_optimize           | 55.2 ms                                                | 54.8 ms: 1.01x faster                                |
| regex_v8                   | 22.9 ms                                                | 22.9 ms: 1.00x slower                                |
| docutils                   | 2.69 sec                                               | 2.71 sec: 1.01x slower                               |
| pprint_pformat             | 1.53 sec                                               | 1.54 sec: 1.01x slower                               |
| bench_thread_pool          | 833 us                                                 | 841 us: 1.01x slower                                 |
| pycparser                  | 1.20 sec                                               | 1.21 sec: 1.01x slower                               |
| dask                       | 365 ms                                                 | 369 ms: 1.01x slower                                 |
| pickle_pure_python         | 319 us                                                 | 323 us: 1.01x slower                                 |
| deepcopy                   | 360 us                                                 | 365 us: 1.01x slower                                 |
| fannkuch                   | 410 ms                                                 | 416 ms: 1.01x slower                                 |
| tornado_http               | 97.7 ms                                                | 99.2 ms: 1.02x slower                                |
| pprint_safe_repr           | 743 ms                                                 | 757 ms: 1.02x slower                                 |
| django_template            | 33.8 ms                                                | 34.5 ms: 1.02x slower                                |
| pathlib                    | 18.5 ms                                                | 18.9 ms: 1.02x slower                                |
| aiohttp                    | 1.12 ms                                                | 1.14 ms: 1.02x slower                                |
| 2to3                       | 266 ms                                                 | 273 ms: 1.03x slower                                 |
| unpickle_list              | 5.22 us                                                | 5.36 us: 1.03x slower                                |
| sqlalchemy_imperative      | 18.2 ms                                                | 18.7 ms: 1.03x slower                                |
| scimark_monte_carlo        | 71.8 ms                                                | 74.0 ms: 1.03x slower                                |
| deepcopy_memo              | 38.9 us                                                | 40.2 us: 1.03x slower                                |
| regex_compile              | 141 ms                                                 | 146 ms: 1.03x slower                                 |
| gunicorn                   | 1.20 ms                                                | 1.24 ms: 1.04x slower                                |
| deepcopy_reduce            | 3.14 us                                                | 3.26 us: 1.04x slower                                |
| sqlalchemy_declarative     | 141 ms                                                 | 146 ms: 1.04x slower                                 |
| dulwich_log                | 64.9 ms                                                | 67.9 ms: 1.05x slower                                |
| regex_dna                  | 204 ms                                                 | 213 ms: 1.05x slower                                 |
| scimark_sparse_mat_mult    | 4.80 ms                                                | 5.04 ms: 1.05x slower                                |
| logging_simple             | 6.24 us                                                | 6.56 us: 1.05x slower                                |
| scimark_lu                 | 112 ms                                                 | 119 ms: 1.06x slower                                 |
| chameleon                  | 6.86 ms                                                | 7.27 ms: 1.06x slower                                |
| scimark_sor                | 121 ms                                                 | 129 ms: 1.06x slower                                 |
| logging_format             | 6.83 us                                                | 7.26 us: 1.06x slower                                |
| mako                       | 10.8 ms                                                | 11.5 ms: 1.07x slower                                |
| float                      | 78.9 ms                                                | 84.1 ms: 1.07x slower                                |
| telco                      | 6.72 ms                                                | 7.17 ms: 1.07x slower                                |
| spectral_norm              | 105 ms                                                 | 113 ms: 1.07x slower                                 |
| pickle_list                | 4.65 us                                                | 5.01 us: 1.08x slower                                |
| crypto_pyaes               | 77.5 ms                                                | 83.8 ms: 1.08x slower                                |
| scimark_fft                | 342 ms                                                 | 371 ms: 1.08x slower                                 |
| python_startup             | 8.69 ms                                                | 9.49 ms: 1.09x slower                                |
| xml_etree_process          | 56.5 ms                                                | 61.9 ms: 1.10x slower                                |
| pyflate                    | 426 ms                                                 | 470 ms: 1.10x slower                                 |
| sqlite_synth               | 2.58 us                                                | 2.87 us: 1.11x slower                                |
| xml_etree_generate         | 80.4 ms                                                | 89.6 ms: 1.11x slower                                |
| regex_effbot               | 3.45 ms                                                | 3.87 ms: 1.12x slower                                |
| python_startup_no_site     | 6.09 ms                                                | 6.88 ms: 1.13x slower                                |
| unpickle                   | 13.9 us                                                | 16.1 us: 1.16x slower                                |
| async_generators           | 375 ms                                                 | 452 ms: 1.20x slower                                 |
| unpack_sequence            | 43.3 ns                                                | 53.4 ns: 1.23x slower                                |
| Geometric mean             | (ref)                                                  | 1.03x faster                                         |

Benchmark hidden because not significant (7): sympy_str, raytrace, bench_mp_pool, meteor_contest, pickle, json, mypy2
Ignored benchmarks (7) of results/bm-20221024-3.11.0-deaf509/bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509.json: djangocms, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, thrift


# HPT report

- Reliability score: 64.97% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
