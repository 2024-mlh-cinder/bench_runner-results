
# Results vs. 3.11.0

- fork: faster-cpython
- ref: tier_2_exponential_b
- machine: linux-x86_64
- commit hash: bff925c
- commit date: 2023-11-05
- overall geometric mean: 1.00x slower \*
- HPT reliability: 94.94%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231105-linux-x86_64-faster%2dcpython-tier_2_exponential_b-3.13.0a1+-bff925c |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| 2to3           | 266 ms                                                 | 283 ms: 1.06x slower                                                             |
| chameleon      | 6.86 ms                                                | 7.52 ms: 1.10x slower                                                            |
| docutils       | 2.69 sec                                               | 2.70 sec: 1.01x slower                                                           |
| tornado_http   | 97.7 ms                                                | 99.2 ms: 1.01x slower                                                            |
| Geometric mean | (ref)                                                  | 1.04x slower                                                                     |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231105-linux-x86_64-faster%2dcpython-tier_2_exponential_b-3.13.0a1+-bff925c |
|----------------------------|:------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| async_tree_none            | 532 ms                                                 | 452 ms: 1.18x faster                                                             |
| async_tree_memoization     | 640 ms                                                 | 577 ms: 1.11x faster                                                             |
| async_tree_io              | 1.31 sec                                               | 1.20 sec: 1.09x faster                                                           |
| async_tree_io_tg           | 1.30 sec                                               | 1.23 sec: 1.06x faster                                                           |
| async_tree_none_tg         | 490 ms                                                 | 464 ms: 1.06x faster                                                             |
| async_tree_memoization_tg  | 627 ms                                                 | 604 ms: 1.04x faster                                                             |
| async_tree_cpu_io_mixed    | 750 ms                                                 | 730 ms: 1.03x faster                                                             |
| async_tree_cpu_io_mixed_tg | 764 ms                                                 | 756 ms: 1.01x faster                                                             |
| Geometric mean             | (ref)                                                  | 1.07x faster                                                                     |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231105-linux-x86_64-faster%2dcpython-tier_2_exponential_b-3.13.0a1+-bff925c |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| pidigits       | 190 ms                                                 | 188 ms: 1.01x faster                                                             |
| float          | 78.9 ms                                                | 105 ms: 1.32x slower                                                             |
| nbody          | 91.6 ms                                                | 126 ms: 1.37x slower                                                             |
| Geometric mean | (ref)                                                  | 1.22x slower                                                                     |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231105-linux-x86_64-faster%2dcpython-tier_2_exponential_b-3.13.0a1+-bff925c |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| regex_effbot   | 3.45 ms                                                | 3.61 ms: 1.05x slower                                                            |
| regex_dna      | 204 ms                                                 | 215 ms: 1.05x slower                                                             |
| regex_compile  | 141 ms                                                 | 158 ms: 1.12x slower                                                             |
| regex_v8       | 22.9 ms                                                | 25.9 ms: 1.13x slower                                                            |
| Geometric mean | (ref)                                                  | 1.09x slower                                                                     |

Benchmarks with tag 'serialize':
================================

| Benchmark           | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231105-linux-x86_64-faster%2dcpython-tier_2_exponential_b-3.13.0a1+-bff925c |
|---------------------|:------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| json_dumps          | 13.5 ms                                                | 10.5 ms: 1.28x faster                                                            |
| json_loads          | 29.4 us                                                | 27.8 us: 1.06x faster                                                            |
| pickle_dict         | 34.8 us                                                | 33.1 us: 1.05x faster                                                            |
| xml_etree_parse     | 163 ms                                                 | 158 ms: 1.03x faster                                                             |
| pickle_pure_python  | 319 us                                                 | 314 us: 1.02x faster                                                             |
| pickle              | 11.1 us                                                | 11.2 us: 1.01x slower                                                            |
| xml_etree_iterparse | 109 ms                                                 | 111 ms: 1.02x slower                                                             |
| pickle_list         | 4.65 us                                                | 4.87 us: 1.05x slower                                                            |
| xml_etree_process   | 56.5 ms                                                | 59.2 ms: 1.05x slower                                                            |
| unpickle_list       | 5.22 us                                                | 5.53 us: 1.06x slower                                                            |
| unpickle            | 13.9 us                                                | 14.7 us: 1.06x slower                                                            |
| xml_etree_generate  | 80.4 ms                                                | 86.4 ms: 1.07x slower                                                            |
| tomli_loads         | 2.31 sec                                               | 2.57 sec: 1.11x slower                                                           |
| Geometric mean      | (ref)                                                  | 1.00x slower                                                                     |

Benchmark hidden because not significant (1): unpickle_pure_python

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231105-linux-x86_64-faster%2dcpython-tier_2_exponential_b-3.13.0a1+-bff925c |
|------------------------|:------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| python_startup         | 8.69 ms                                                | 10.3 ms: 1.18x slower                                                            |
| python_startup_no_site | 6.09 ms                                                | 8.96 ms: 1.47x slower                                                            |
| Geometric mean         | (ref)                                                  | 1.32x slower                                                                     |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231105-linux-x86_64-faster%2dcpython-tier_2_exponential_b-3.13.0a1+-bff925c |
|-----------|:------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| mako      | 10.8 ms                                                | 14.4 ms: 1.33x slower                                                            |

All benchmarks:
===============

| Benchmark                  | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231105-linux-x86_64-faster%2dcpython-tier_2_exponential_b-3.13.0a1+-bff925c |
|----------------------------|:------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| typing_runtime_protocols   | 521 us                                                 | 124 us: 4.19x faster                                                             |
| generators                 | 76.5 ms                                                | 29.6 ms: 2.59x faster                                                            |
| asyncio_tcp                | 887 ms                                                 | 490 ms: 1.81x faster                                                             |
| asyncio_tcp_ssl            | 3.13 sec                                               | 1.81 sec: 1.73x faster                                                           |
| json_dumps                 | 13.5 ms                                                | 10.5 ms: 1.28x faster                                                            |
| mypy2                      | 427 ms                                                 | 354 ms: 1.21x faster                                                             |
| coroutines                 | 26.1 ms                                                | 22.2 ms: 1.18x faster                                                            |
| async_tree_none            | 532 ms                                                 | 452 ms: 1.18x faster                                                             |
| sympy_sum                  | 170 ms                                                 | 153 ms: 1.11x faster                                                             |
| async_tree_memoization     | 640 ms                                                 | 577 ms: 1.11x faster                                                             |
| sqlglot_parse              | 1.43 ms                                                | 1.31 ms: 1.09x faster                                                            |
| async_tree_io              | 1.31 sec                                               | 1.20 sec: 1.09x faster                                                           |
| richards_super             | 61.2 ms                                                | 56.3 ms: 1.09x faster                                                            |
| gc_traversal               | 3.90 ms                                                | 3.64 ms: 1.07x faster                                                            |
| sqlglot_transpile          | 1.75 ms                                                | 1.64 ms: 1.07x faster                                                            |
| sympy_str                  | 299 ms                                                 | 282 ms: 1.06x faster                                                             |
| json_loads                 | 29.4 us                                                | 27.8 us: 1.06x faster                                                            |
| async_tree_io_tg           | 1.30 sec                                               | 1.23 sec: 1.06x faster                                                           |
| sqlglot_normalize          | 112 ms                                                 | 106 ms: 1.06x faster                                                             |
| async_tree_none_tg         | 490 ms                                                 | 464 ms: 1.06x faster                                                             |
| pickle_dict                | 34.8 us                                                | 33.1 us: 1.05x faster                                                            |
| async_tree_memoization_tg  | 627 ms                                                 | 604 ms: 1.04x faster                                                             |
| xml_etree_parse            | 163 ms                                                 | 158 ms: 1.03x faster                                                             |
| async_tree_cpu_io_mixed    | 750 ms                                                 | 730 ms: 1.03x faster                                                             |
| sympy_expand               | 490 ms                                                 | 479 ms: 1.02x faster                                                             |
| pickle_pure_python         | 319 us                                                 | 314 us: 1.02x faster                                                             |
| sqlglot_optimize           | 55.2 ms                                                | 54.3 ms: 1.02x faster                                                            |
| deepcopy                   | 360 us                                                 | 355 us: 1.01x faster                                                             |
| sympy_integrate            | 21.4 ms                                                | 21.1 ms: 1.01x faster                                                            |
| pidigits                   | 190 ms                                                 | 188 ms: 1.01x faster                                                             |
| async_tree_cpu_io_mixed_tg | 764 ms                                                 | 756 ms: 1.01x faster                                                             |
| comprehensions             | 23.6 us                                                | 23.3 us: 1.01x faster                                                            |
| create_gc_cycles           | 1.48 ms                                                | 1.46 ms: 1.01x faster                                                            |
| json                       | 5.24 ms                                                | 5.19 ms: 1.01x faster                                                            |
| asyncio_websockets         | 556 ms                                                 | 551 ms: 1.01x faster                                                             |
| logging_simple             | 6.24 us                                                | 6.20 us: 1.01x faster                                                            |
| raytrace                   | 306 ms                                                 | 304 ms: 1.01x faster                                                             |
| mdp                        | 2.79 sec                                               | 2.79 sec: 1.00x slower                                                           |
| docutils                   | 2.69 sec                                               | 2.70 sec: 1.01x slower                                                           |
| pickle                     | 11.1 us                                                | 11.2 us: 1.01x slower                                                            |
| richards                   | 48.9 ms                                                | 49.6 ms: 1.01x slower                                                            |
| tornado_http               | 97.7 ms                                                | 99.2 ms: 1.01x slower                                                            |
| xml_etree_iterparse        | 109 ms                                                 | 111 ms: 1.02x slower                                                             |
| logging_format             | 6.83 us                                                | 6.97 us: 1.02x slower                                                            |
| bench_thread_pool          | 833 us                                                 | 854 us: 1.02x slower                                                             |
| pycparser                  | 1.20 sec                                               | 1.24 sec: 1.04x slower                                                           |
| pickle_list                | 4.65 us                                                | 4.87 us: 1.05x slower                                                            |
| regex_effbot               | 3.45 ms                                                | 3.61 ms: 1.05x slower                                                            |
| chaos                      | 71.4 ms                                                | 74.8 ms: 1.05x slower                                                            |
| xml_etree_process          | 56.5 ms                                                | 59.2 ms: 1.05x slower                                                            |
| regex_dna                  | 204 ms                                                 | 215 ms: 1.05x slower                                                             |
| unpickle_list              | 5.22 us                                                | 5.53 us: 1.06x slower                                                            |
| unpickle                   | 13.9 us                                                | 14.7 us: 1.06x slower                                                            |
| dulwich_log                | 64.9 ms                                                | 69.0 ms: 1.06x slower                                                            |
| spectral_norm              | 105 ms                                                 | 112 ms: 1.06x slower                                                             |
| 2to3                       | 266 ms                                                 | 283 ms: 1.06x slower                                                             |
| pathlib                    | 18.5 ms                                                | 19.7 ms: 1.07x slower                                                            |
| meteor_contest             | 109 ms                                                 | 116 ms: 1.07x slower                                                             |
| xml_etree_generate         | 80.4 ms                                                | 86.4 ms: 1.07x slower                                                            |
| scimark_lu                 | 112 ms                                                 | 121 ms: 1.08x slower                                                             |
| pprint_safe_repr           | 743 ms                                                 | 801 ms: 1.08x slower                                                             |
| pprint_pformat             | 1.53 sec                                               | 1.65 sec: 1.08x slower                                                           |
| deepcopy_memo              | 38.9 us                                                | 42.0 us: 1.08x slower                                                            |
| scimark_sor                | 121 ms                                                 | 132 ms: 1.09x slower                                                             |
| chameleon                  | 6.86 ms                                                | 7.52 ms: 1.10x slower                                                            |
| sqlite_synth               | 2.58 us                                                | 2.83 us: 1.10x slower                                                            |
| tomli_loads                | 2.31 sec                                               | 2.57 sec: 1.11x slower                                                           |
| crypto_pyaes               | 77.5 ms                                                | 86.3 ms: 1.11x slower                                                            |
| scimark_monte_carlo        | 71.8 ms                                                | 80.3 ms: 1.12x slower                                                            |
| regex_compile              | 141 ms                                                 | 158 ms: 1.12x slower                                                             |
| nqueens                    | 86.8 ms                                                | 97.9 ms: 1.13x slower                                                            |
| regex_v8                   | 22.9 ms                                                | 25.9 ms: 1.13x slower                                                            |
| unpack_sequence            | 43.3 ns                                                | 49.0 ns: 1.13x slower                                                            |
| fannkuch                   | 410 ms                                                 | 468 ms: 1.14x slower                                                             |
| go                         | 143 ms                                                 | 164 ms: 1.15x slower                                                             |
| coverage                   | 81.2 ms                                                | 94.7 ms: 1.17x slower                                                            |
| python_startup             | 8.69 ms                                                | 10.3 ms: 1.18x slower                                                            |
| async_generators           | 375 ms                                                 | 454 ms: 1.21x slower                                                             |
| pyflate                    | 426 ms                                                 | 543 ms: 1.27x slower                                                             |
| deltablue                  | 3.80 ms                                                | 4.90 ms: 1.29x slower                                                            |
| scimark_fft                | 342 ms                                                 | 442 ms: 1.29x slower                                                             |
| telco                      | 6.72 ms                                                | 8.73 ms: 1.30x slower                                                            |
| scimark_sparse_mat_mult    | 4.80 ms                                                | 6.31 ms: 1.31x slower                                                            |
| float                      | 78.9 ms                                                | 105 ms: 1.32x slower                                                             |
| mako                       | 10.8 ms                                                | 14.4 ms: 1.33x slower                                                            |
| hexiom                     | 6.74 ms                                                | 9.19 ms: 1.36x slower                                                            |
| nbody                      | 91.6 ms                                                | 126 ms: 1.37x slower                                                             |
| python_startup_no_site     | 6.09 ms                                                | 8.96 ms: 1.47x slower                                                            |
| Geometric mean             | (ref)                                                  | 1.00x slower                                                                     |

Benchmark hidden because not significant (4): deepcopy_reduce, unpickle_pure_python, bench_mp_pool, logging_silent
Ignored benchmarks (13) of results/bm-20221024-3.11.0-deaf509/bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift


# HPT report

- Reliability score: 94.94% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
