
# Results vs. 3.11.0

- fork: gvanrossum
- ref: gil_counter
- machine: linux-x86_64
- commit hash: c681cde
- commit date: 2023-11-15
- overall geometric mean: 1.01x faster \*
- HPT reliability: 90.85%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231115-linux-x86_64-gvanrossum-gil_counter-3.13.0a1+-c681cde |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------:|
| 2to3           | 266 ms                                                 | 285 ms: 1.07x slower                                              |
| chameleon      | 6.86 ms                                                | 7.77 ms: 1.13x slower                                             |
| docutils       | 2.69 sec                                               | 2.70 sec: 1.00x slower                                            |
| Geometric mean | (ref)                                                  | 1.05x slower                                                      |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231115-linux-x86_64-gvanrossum-gil_counter-3.13.0a1+-c681cde |
|----------------------------|:------------------------------------------------------:|:-----------------------------------------------------------------:|
| async_tree_none            | 532 ms                                                 | 444 ms: 1.20x faster                                              |
| async_tree_memoization     | 640 ms                                                 | 570 ms: 1.12x faster                                              |
| async_tree_io              | 1.31 sec                                               | 1.20 sec: 1.09x faster                                            |
| async_tree_none_tg         | 490 ms                                                 | 460 ms: 1.06x faster                                              |
| async_tree_io_tg           | 1.30 sec                                               | 1.23 sec: 1.06x faster                                            |
| async_tree_cpu_io_mixed    | 750 ms                                                 | 719 ms: 1.04x faster                                              |
| async_tree_memoization_tg  | 627 ms                                                 | 602 ms: 1.04x faster                                              |
| async_tree_cpu_io_mixed_tg | 764 ms                                                 | 750 ms: 1.02x faster                                              |
| Geometric mean             | (ref)                                                  | 1.08x faster                                                      |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231115-linux-x86_64-gvanrossum-gil_counter-3.13.0a1+-c681cde |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------:|
| pidigits       | 190 ms                                                 | 188 ms: 1.01x faster                                              |
| float          | 78.9 ms                                                | 83.4 ms: 1.06x slower                                             |
| nbody          | 91.6 ms                                                | 102 ms: 1.11x slower                                              |
| Geometric mean | (ref)                                                  | 1.05x slower                                                      |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231115-linux-x86_64-gvanrossum-gil_counter-3.13.0a1+-c681cde |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------:|
| regex_effbot   | 3.45 ms                                                | 3.61 ms: 1.05x slower                                             |
| regex_dna      | 204 ms                                                 | 216 ms: 1.06x slower                                              |
| regex_compile  | 141 ms                                                 | 151 ms: 1.07x slower                                              |
| regex_v8       | 22.9 ms                                                | 26.3 ms: 1.15x slower                                             |
| Geometric mean | (ref)                                                  | 1.08x slower                                                      |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231115-linux-x86_64-gvanrossum-gil_counter-3.13.0a1+-c681cde |
|----------------------|:------------------------------------------------------:|:-----------------------------------------------------------------:|
| json_dumps           | 13.5 ms                                                | 10.5 ms: 1.28x faster                                             |
| unpickle_list        | 5.22 us                                                | 4.93 us: 1.06x faster                                             |
| json_loads           | 29.4 us                                                | 28.3 us: 1.04x faster                                             |
| xml_etree_parse      | 163 ms                                                 | 159 ms: 1.03x faster                                              |
| xml_etree_iterparse  | 109 ms                                                 | 107 ms: 1.02x faster                                              |
| pickle_dict          | 34.8 us                                                | 34.3 us: 1.02x faster                                             |
| unpickle_pure_python | 241 us                                                 | 246 us: 1.02x slower                                              |
| pickle               | 11.1 us                                                | 11.6 us: 1.04x slower                                             |
| tomli_loads          | 2.31 sec                                               | 2.46 sec: 1.06x slower                                            |
| unpickle             | 13.9 us                                                | 14.9 us: 1.08x slower                                             |
| pickle_pure_python   | 319 us                                                 | 344 us: 1.08x slower                                              |
| xml_etree_process    | 56.5 ms                                                | 61.7 ms: 1.09x slower                                             |
| xml_etree_generate   | 80.4 ms                                                | 89.1 ms: 1.11x slower                                             |
| pickle_list          | 4.65 us                                                | 5.17 us: 1.11x slower                                             |
| Geometric mean       | (ref)                                                  | 1.01x slower                                                      |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231115-linux-x86_64-gvanrossum-gil_counter-3.13.0a1+-c681cde |
|------------------------|:------------------------------------------------------:|:-----------------------------------------------------------------:|
| python_startup         | 8.69 ms                                                | 10.4 ms: 1.19x slower                                             |
| python_startup_no_site | 6.09 ms                                                | 9.04 ms: 1.48x slower                                             |
| Geometric mean         | (ref)                                                  | 1.33x slower                                                      |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231115-linux-x86_64-gvanrossum-gil_counter-3.13.0a1+-c681cde |
|-----------|:------------------------------------------------------:|:-----------------------------------------------------------------:|
| mako      | 10.8 ms                                                | 12.0 ms: 1.11x slower                                             |

All benchmarks:
===============

| Benchmark                  | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231115-linux-x86_64-gvanrossum-gil_counter-3.13.0a1+-c681cde |
|----------------------------|:------------------------------------------------------:|:-----------------------------------------------------------------:|
| typing_runtime_protocols   | 521 us                                                 | 117 us: 4.45x faster                                              |
| generators                 | 76.5 ms                                                | 32.1 ms: 2.38x faster                                             |
| asyncio_tcp                | 887 ms                                                 | 494 ms: 1.79x faster                                              |
| asyncio_tcp_ssl            | 3.13 sec                                               | 1.80 sec: 1.74x faster                                            |
| comprehensions             | 23.6 us                                                | 18.2 us: 1.30x faster                                             |
| json_dumps                 | 13.5 ms                                                | 10.5 ms: 1.28x faster                                             |
| async_tree_none            | 532 ms                                                 | 444 ms: 1.20x faster                                              |
| mypy2                      | 427 ms                                                 | 357 ms: 1.20x faster                                              |
| async_tree_memoization     | 640 ms                                                 | 570 ms: 1.12x faster                                              |
| sympy_sum                  | 170 ms                                                 | 153 ms: 1.12x faster                                              |
| coroutines                 | 26.1 ms                                                | 23.6 ms: 1.11x faster                                             |
| async_tree_io              | 1.31 sec                                               | 1.20 sec: 1.09x faster                                            |
| logging_simple             | 6.24 us                                                | 5.74 us: 1.09x faster                                             |
| mdp                        | 2.79 sec                                               | 2.58 sec: 1.08x faster                                            |
| logging_format             | 6.83 us                                                | 6.34 us: 1.08x faster                                             |
| chaos                      | 71.4 ms                                                | 66.6 ms: 1.07x faster                                             |
| gc_traversal               | 3.90 ms                                                | 3.64 ms: 1.07x faster                                             |
| async_tree_none_tg         | 490 ms                                                 | 460 ms: 1.06x faster                                              |
| sympy_str                  | 299 ms                                                 | 281 ms: 1.06x faster                                              |
| async_tree_io_tg           | 1.30 sec                                               | 1.23 sec: 1.06x faster                                            |
| unpickle_list              | 5.22 us                                                | 4.93 us: 1.06x faster                                             |
| sympy_expand               | 490 ms                                                 | 467 ms: 1.05x faster                                              |
| async_tree_cpu_io_mixed    | 750 ms                                                 | 719 ms: 1.04x faster                                              |
| async_tree_memoization_tg  | 627 ms                                                 | 602 ms: 1.04x faster                                              |
| json_loads                 | 29.4 us                                                | 28.3 us: 1.04x faster                                             |
| sympy_integrate            | 21.4 ms                                                | 20.6 ms: 1.04x faster                                             |
| nqueens                    | 86.8 ms                                                | 84.6 ms: 1.03x faster                                             |
| xml_etree_parse            | 163 ms                                                 | 159 ms: 1.03x faster                                              |
| async_tree_cpu_io_mixed_tg | 764 ms                                                 | 750 ms: 1.02x faster                                              |
| xml_etree_iterparse        | 109 ms                                                 | 107 ms: 1.02x faster                                              |
| pickle_dict                | 34.8 us                                                | 34.3 us: 1.02x faster                                             |
| json                       | 5.24 ms                                                | 5.17 ms: 1.01x faster                                             |
| pidigits                   | 190 ms                                                 | 188 ms: 1.01x faster                                              |
| sqlglot_normalize          | 112 ms                                                 | 111 ms: 1.01x faster                                              |
| create_gc_cycles           | 1.48 ms                                                | 1.46 ms: 1.01x faster                                             |
| asyncio_websockets         | 556 ms                                                 | 551 ms: 1.01x faster                                              |
| deltablue                  | 3.80 ms                                                | 3.78 ms: 1.01x faster                                             |
| docutils                   | 2.69 sec                                               | 2.70 sec: 1.00x slower                                            |
| pathlib                    | 18.5 ms                                                | 18.7 ms: 1.01x slower                                             |
| sqlglot_parse              | 1.43 ms                                                | 1.46 ms: 1.02x slower                                             |
| sqlglot_transpile          | 1.75 ms                                                | 1.79 ms: 1.02x slower                                             |
| unpickle_pure_python       | 241 us                                                 | 246 us: 1.02x slower                                              |
| scimark_monte_carlo        | 71.8 ms                                                | 73.4 ms: 1.02x slower                                             |
| meteor_contest             | 109 ms                                                 | 112 ms: 1.03x slower                                              |
| sqlglot_optimize           | 55.2 ms                                                | 56.9 ms: 1.03x slower                                             |
| bench_thread_pool          | 833 us                                                 | 862 us: 1.03x slower                                              |
| crypto_pyaes               | 77.5 ms                                                | 80.3 ms: 1.04x slower                                             |
| pickle                     | 11.1 us                                                | 11.6 us: 1.04x slower                                             |
| deepcopy_reduce            | 3.14 us                                                | 3.28 us: 1.05x slower                                             |
| regex_effbot               | 3.45 ms                                                | 3.61 ms: 1.05x slower                                             |
| dulwich_log                | 64.9 ms                                                | 68.3 ms: 1.05x slower                                             |
| float                      | 78.9 ms                                                | 83.4 ms: 1.06x slower                                             |
| regex_dna                  | 204 ms                                                 | 216 ms: 1.06x slower                                              |
| tomli_loads                | 2.31 sec                                               | 2.46 sec: 1.06x slower                                            |
| fannkuch                   | 410 ms                                                 | 435 ms: 1.06x slower                                              |
| logging_silent             | 108 ns                                                 | 115 ns: 1.06x slower                                              |
| richards_super             | 61.2 ms                                                | 65.2 ms: 1.06x slower                                             |
| regex_compile              | 141 ms                                                 | 151 ms: 1.07x slower                                              |
| deepcopy                   | 360 us                                                 | 385 us: 1.07x slower                                              |
| 2to3                       | 266 ms                                                 | 285 ms: 1.07x slower                                              |
| unpickle                   | 13.9 us                                                | 14.9 us: 1.08x slower                                             |
| scimark_sparse_mat_mult    | 4.80 ms                                                | 5.17 ms: 1.08x slower                                             |
| pickle_pure_python         | 319 us                                                 | 344 us: 1.08x slower                                              |
| hexiom                     | 6.74 ms                                                | 7.27 ms: 1.08x slower                                             |
| pprint_pformat             | 1.53 sec                                               | 1.65 sec: 1.08x slower                                            |
| scimark_lu                 | 112 ms                                                 | 122 ms: 1.09x slower                                              |
| deepcopy_memo              | 38.9 us                                                | 42.3 us: 1.09x slower                                             |
| pprint_safe_repr           | 743 ms                                                 | 810 ms: 1.09x slower                                              |
| xml_etree_process          | 56.5 ms                                                | 61.7 ms: 1.09x slower                                             |
| pycparser                  | 1.20 sec                                               | 1.31 sec: 1.09x slower                                            |
| sqlite_synth               | 2.58 us                                                | 2.82 us: 1.09x slower                                             |
| xml_etree_generate         | 80.4 ms                                                | 89.1 ms: 1.11x slower                                             |
| mako                       | 10.8 ms                                                | 12.0 ms: 1.11x slower                                             |
| scimark_sor                | 121 ms                                                 | 135 ms: 1.11x slower                                              |
| nbody                      | 91.6 ms                                                | 102 ms: 1.11x slower                                              |
| pickle_list                | 4.65 us                                                | 5.17 us: 1.11x slower                                             |
| unpack_sequence            | 43.3 ns                                                | 48.3 ns: 1.12x slower                                             |
| scimark_fft                | 342 ms                                                 | 387 ms: 1.13x slower                                              |
| chameleon                  | 6.86 ms                                                | 7.77 ms: 1.13x slower                                             |
| go                         | 143 ms                                                 | 163 ms: 1.14x slower                                              |
| regex_v8                   | 22.9 ms                                                | 26.3 ms: 1.15x slower                                             |
| spectral_norm              | 105 ms                                                 | 123 ms: 1.17x slower                                              |
| richards                   | 48.9 ms                                                | 57.3 ms: 1.17x slower                                             |
| pyflate                    | 426 ms                                                 | 502 ms: 1.18x slower                                              |
| coverage                   | 81.2 ms                                                | 95.8 ms: 1.18x slower                                             |
| python_startup             | 8.69 ms                                                | 10.4 ms: 1.19x slower                                             |
| async_generators           | 375 ms                                                 | 452 ms: 1.20x slower                                              |
| telco                      | 6.72 ms                                                | 8.44 ms: 1.26x slower                                             |
| python_startup_no_site     | 6.09 ms                                                | 9.04 ms: 1.48x slower                                             |
| Geometric mean             | (ref)                                                  | 1.01x faster                                                      |

Benchmark hidden because not significant (3): raytrace, bench_mp_pool, tornado_http
Ignored benchmarks (13) of results/bm-20221024-3.11.0-deaf509/bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift


# HPT report

- Reliability score: 90.85% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
