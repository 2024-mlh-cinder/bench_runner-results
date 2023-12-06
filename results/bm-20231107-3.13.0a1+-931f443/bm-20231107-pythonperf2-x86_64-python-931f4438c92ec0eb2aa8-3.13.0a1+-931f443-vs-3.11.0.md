
# Results vs. 3.11.0

- fork: python
- ref: 931f4438c92ec0eb2aa8
- machine: linux-x86_64
- commit hash: 931f443
- commit date: 2023-11-07
- overall geometric mean: 1.07x faster \*
- HPT reliability: 99.97%
- HPT 99th percentile: 1.01x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231107-pythonperf2-x86_64-python-931f4438c92ec0eb2aa8-3.13.0a1+-931f443 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| 2to3           | 286 ms                                                       | 290 ms: 1.01x slower                                                         |
| chameleon      | 7.42 ms                                                      | 7.24 ms: 1.03x faster                                                        |
| docutils       | 2.87 sec                                                     | 2.82 sec: 1.02x faster                                                       |
| tornado_http   | 125 ms                                                       | 119 ms: 1.05x faster                                                         |
| Geometric mean | (ref)                                                        | 1.02x faster                                                                 |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231107-pythonperf2-x86_64-python-931f4438c92ec0eb2aa8-3.13.0a1+-931f443 |
|----------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| async_tree_none            | 529 ms                                                       | 432 ms: 1.22x faster                                                         |
| async_tree_memoization     | 648 ms                                                       | 547 ms: 1.19x faster                                                         |
| async_tree_io              | 1.19 sec                                                     | 1.08 sec: 1.10x faster                                                       |
| async_tree_cpu_io_mixed    | 762 ms                                                       | 699 ms: 1.09x faster                                                         |
| async_tree_none_tg         | 482 ms                                                       | 444 ms: 1.08x faster                                                         |
| async_tree_io_tg           | 1.17 sec                                                     | 1.10 sec: 1.07x faster                                                       |
| async_tree_memoization_tg  | 605 ms                                                       | 570 ms: 1.06x faster                                                         |
| async_tree_cpu_io_mixed_tg | 760 ms                                                       | 717 ms: 1.06x faster                                                         |
| Geometric mean             | (ref)                                                        | 1.11x faster                                                                 |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231107-pythonperf2-x86_64-python-931f4438c92ec0eb2aa8-3.13.0a1+-931f443 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| nbody          | 95.8 ms                                                      | 85.0 ms: 1.13x faster                                                        |
| float          | 76.0 ms                                                      | 79.1 ms: 1.04x slower                                                        |
| pidigits       | 251 ms                                                       | 265 ms: 1.05x slower                                                         |
| Geometric mean | (ref)                                                        | 1.01x faster                                                                 |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231107-pythonperf2-x86_64-python-931f4438c92ec0eb2aa8-3.13.0a1+-931f443 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| regex_compile  | 157 ms                                                       | 146 ms: 1.08x faster                                                         |
| regex_effbot   | 3.42 ms                                                      | 3.61 ms: 1.06x slower                                                        |
| regex_v8       | 23.7 ms                                                      | 25.2 ms: 1.06x slower                                                        |
| regex_dna      | 226 ms                                                       | 253 ms: 1.12x slower                                                         |
| Geometric mean | (ref)                                                        | 1.04x slower                                                                 |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231107-pythonperf2-x86_64-python-931f4438c92ec0eb2aa8-3.13.0a1+-931f443 |
|----------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| json_dumps           | 13.5 ms                                                      | 10.3 ms: 1.31x faster                                                        |
| json_loads           | 29.0 us                                                      | 24.3 us: 1.19x faster                                                        |
| xml_etree_parse      | 159 ms                                                       | 147 ms: 1.08x faster                                                         |
| pickle_pure_python   | 318 us                                                       | 310 us: 1.03x faster                                                         |
| unpickle_pure_python | 236 us                                                       | 231 us: 1.02x faster                                                         |
| xml_etree_iterparse  | 106 ms                                                       | 104 ms: 1.02x faster                                                         |
| tomli_loads          | 2.27 sec                                                     | 2.35 sec: 1.03x slower                                                       |
| pickle_dict          | 31.8 us                                                      | 33.0 us: 1.04x slower                                                        |
| pickle               | 9.77 us                                                      | 10.2 us: 1.04x slower                                                        |
| xml_etree_process    | 56.1 ms                                                      | 58.7 ms: 1.05x slower                                                        |
| unpickle_list        | 4.47 us                                                      | 4.71 us: 1.05x slower                                                        |
| xml_etree_generate   | 80.5 ms                                                      | 86.7 ms: 1.08x slower                                                        |
| unpickle             | 13.2 us                                                      | 14.8 us: 1.12x slower                                                        |
| pickle_list          | 3.89 us                                                      | 4.41 us: 1.13x slower                                                        |
| Geometric mean       | (ref)                                                        | 1.00x faster                                                                 |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231107-pythonperf2-x86_64-python-931f4438c92ec0eb2aa8-3.13.0a1+-931f443 |
|------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| python_startup         | 10.8 ms                                                      | 12.8 ms: 1.18x slower                                                        |
| python_startup_no_site | 7.78 ms                                                      | 11.3 ms: 1.45x slower                                                        |
| Geometric mean         | (ref)                                                        | 1.31x slower                                                                 |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231107-pythonperf2-x86_64-python-931f4438c92ec0eb2aa8-3.13.0a1+-931f443 |
|-----------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| mako      | 11.0 ms                                                      | 10.2 ms: 1.07x faster                                                        |

All benchmarks:
===============

| Benchmark                  | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231107-pythonperf2-x86_64-python-931f4438c92ec0eb2aa8-3.13.0a1+-931f443 |
|----------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| typing_runtime_protocols   | 527 us                                                       | 121 us: 4.37x faster                                                         |
| asyncio_tcp                | 752 ms                                                       | 368 ms: 2.04x faster                                                         |
| asyncio_tcp_ssl            | 3.09 sec                                                     | 1.58 sec: 1.95x faster                                                       |
| generators                 | 56.4 ms                                                      | 35.2 ms: 1.60x faster                                                        |
| comprehensions             | 24.8 us                                                      | 16.3 us: 1.52x faster                                                        |
| json_dumps                 | 13.5 ms                                                      | 10.3 ms: 1.31x faster                                                        |
| coroutines                 | 27.9 ms                                                      | 22.4 ms: 1.24x faster                                                        |
| mypy2                      | 449 ms                                                       | 364 ms: 1.24x faster                                                         |
| sympy_sum                  | 184 ms                                                       | 150 ms: 1.23x faster                                                         |
| async_tree_none            | 529 ms                                                       | 432 ms: 1.22x faster                                                         |
| json_loads                 | 29.0 us                                                      | 24.3 us: 1.19x faster                                                        |
| async_tree_memoization     | 648 ms                                                       | 547 ms: 1.19x faster                                                         |
| chaos                      | 71.6 ms                                                      | 60.8 ms: 1.18x faster                                                        |
| sympy_str                  | 336 ms                                                       | 288 ms: 1.17x faster                                                         |
| scimark_lu                 | 115 ms                                                       | 99.5 ms: 1.16x faster                                                        |
| fannkuch                   | 457 ms                                                       | 396 ms: 1.16x faster                                                         |
| crypto_pyaes               | 81.8 ms                                                      | 71.6 ms: 1.14x faster                                                        |
| raytrace                   | 308 ms                                                       | 270 ms: 1.14x faster                                                         |
| sympy_expand               | 550 ms                                                       | 485 ms: 1.14x faster                                                         |
| nbody                      | 95.8 ms                                                      | 85.0 ms: 1.13x faster                                                        |
| richards_super             | 65.2 ms                                                      | 58.3 ms: 1.12x faster                                                        |
| nqueens                    | 99.2 ms                                                      | 88.9 ms: 1.12x faster                                                        |
| sympy_integrate            | 25.6 ms                                                      | 23.0 ms: 1.11x faster                                                        |
| sqlglot_parse              | 1.55 ms                                                      | 1.40 ms: 1.11x faster                                                        |
| async_tree_io              | 1.19 sec                                                     | 1.08 sec: 1.10x faster                                                       |
| deltablue                  | 4.03 ms                                                      | 3.66 ms: 1.10x faster                                                        |
| json                       | 5.59 ms                                                      | 5.10 ms: 1.10x faster                                                        |
| async_tree_cpu_io_mixed    | 762 ms                                                       | 699 ms: 1.09x faster                                                         |
| logging_simple             | 7.21 us                                                      | 6.64 us: 1.09x faster                                                        |
| async_tree_none_tg         | 482 ms                                                       | 444 ms: 1.08x faster                                                         |
| xml_etree_parse            | 159 ms                                                       | 147 ms: 1.08x faster                                                         |
| hexiom                     | 6.97 ms                                                      | 6.46 ms: 1.08x faster                                                        |
| regex_compile              | 157 ms                                                       | 146 ms: 1.08x faster                                                         |
| sqlglot_transpile          | 1.94 ms                                                      | 1.80 ms: 1.08x faster                                                        |
| gc_traversal               | 4.06 ms                                                      | 3.78 ms: 1.08x faster                                                        |
| mako                       | 11.0 ms                                                      | 10.2 ms: 1.07x faster                                                        |
| logging_silent             | 102 ns                                                       | 95.0 ns: 1.07x faster                                                        |
| sqlglot_normalize          | 122 ms                                                       | 114 ms: 1.07x faster                                                         |
| deepcopy                   | 389 us                                                       | 365 us: 1.07x faster                                                         |
| async_tree_io_tg           | 1.17 sec                                                     | 1.10 sec: 1.07x faster                                                       |
| async_tree_memoization_tg  | 605 ms                                                       | 570 ms: 1.06x faster                                                         |
| async_tree_cpu_io_mixed_tg | 760 ms                                                       | 717 ms: 1.06x faster                                                         |
| mdp                        | 2.72 sec                                                     | 2.57 sec: 1.06x faster                                                       |
| logging_format             | 7.83 us                                                      | 7.42 us: 1.05x faster                                                        |
| bench_thread_pool          | 1.02 ms                                                      | 967 us: 1.05x faster                                                         |
| tornado_http               | 125 ms                                                       | 119 ms: 1.05x faster                                                         |
| deepcopy_reduce            | 3.37 us                                                      | 3.24 us: 1.04x faster                                                        |
| spectral_norm              | 94.0 ms                                                      | 90.6 ms: 1.04x faster                                                        |
| create_gc_cycles           | 1.59 ms                                                      | 1.55 ms: 1.03x faster                                                        |
| pickle_pure_python         | 318 us                                                       | 310 us: 1.03x faster                                                         |
| chameleon                  | 7.42 ms                                                      | 7.24 ms: 1.03x faster                                                        |
| sqlglot_optimize           | 59.2 ms                                                      | 57.8 ms: 1.02x faster                                                        |
| unpickle_pure_python       | 236 us                                                       | 231 us: 1.02x faster                                                         |
| scimark_monte_carlo        | 70.6 ms                                                      | 69.2 ms: 1.02x faster                                                        |
| deepcopy_memo              | 37.3 us                                                      | 36.6 us: 1.02x faster                                                        |
| xml_etree_iterparse        | 106 ms                                                       | 104 ms: 1.02x faster                                                         |
| docutils                   | 2.87 sec                                                     | 2.82 sec: 1.02x faster                                                       |
| meteor_contest             | 130 ms                                                       | 129 ms: 1.01x faster                                                         |
| pprint_pformat             | 1.63 sec                                                     | 1.62 sec: 1.01x faster                                                       |
| dulwich_log                | 68.3 ms                                                      | 67.9 ms: 1.01x faster                                                        |
| 2to3                       | 286 ms                                                       | 290 ms: 1.01x slower                                                         |
| pprint_safe_repr           | 780 ms                                                       | 792 ms: 1.02x slower                                                         |
| go                         | 166 ms                                                       | 170 ms: 1.03x slower                                                         |
| pathlib                    | 19.1 ms                                                      | 19.7 ms: 1.03x slower                                                        |
| tomli_loads                | 2.27 sec                                                     | 2.35 sec: 1.03x slower                                                       |
| pickle_dict                | 31.8 us                                                      | 33.0 us: 1.04x slower                                                        |
| scimark_sparse_mat_mult    | 4.04 ms                                                      | 4.20 ms: 1.04x slower                                                        |
| float                      | 76.0 ms                                                      | 79.1 ms: 1.04x slower                                                        |
| pickle                     | 9.77 us                                                      | 10.2 us: 1.04x slower                                                        |
| xml_etree_process          | 56.1 ms                                                      | 58.7 ms: 1.05x slower                                                        |
| unpickle_list              | 4.47 us                                                      | 4.71 us: 1.05x slower                                                        |
| pidigits                   | 251 ms                                                       | 265 ms: 1.05x slower                                                         |
| regex_effbot               | 3.42 ms                                                      | 3.61 ms: 1.06x slower                                                        |
| regex_v8                   | 23.7 ms                                                      | 25.2 ms: 1.06x slower                                                        |
| richards                   | 49.9 ms                                                      | 53.2 ms: 1.07x slower                                                        |
| sqlite_synth               | 2.49 us                                                      | 2.65 us: 1.07x slower                                                        |
| scimark_fft                | 281 ms                                                       | 300 ms: 1.07x slower                                                         |
| xml_etree_generate         | 80.5 ms                                                      | 86.7 ms: 1.08x slower                                                        |
| pyflate                    | 453 ms                                                       | 505 ms: 1.11x slower                                                         |
| async_generators           | 322 ms                                                       | 359 ms: 1.12x slower                                                         |
| regex_dna                  | 226 ms                                                       | 253 ms: 1.12x slower                                                         |
| unpickle                   | 13.2 us                                                      | 14.8 us: 1.12x slower                                                        |
| pickle_list                | 3.89 us                                                      | 4.41 us: 1.13x slower                                                        |
| unpack_sequence            | 44.9 ns                                                      | 52.2 ns: 1.16x slower                                                        |
| telco                      | 6.91 ms                                                      | 8.05 ms: 1.17x slower                                                        |
| python_startup             | 10.8 ms                                                      | 12.8 ms: 1.18x slower                                                        |
| coverage                   | 66.6 ms                                                      | 81.5 ms: 1.22x slower                                                        |
| scimark_sor                | 109 ms                                                       | 146 ms: 1.33x slower                                                         |
| python_startup_no_site     | 7.78 ms                                                      | 11.3 ms: 1.45x slower                                                        |
| Geometric mean             | (ref)                                                        | 1.07x faster                                                                 |

Benchmark hidden because not significant (3): pycparser, asyncio_websockets, bench_mp_pool
Ignored benchmarks (12) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, dask, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift


# HPT report

- Reliability score: 99.97% likely to be faster
- 90% likely to have a speedup of 1.02x
- 95% likely to have a speedup of 1.02x
- 99% likely to have a speedup of 1.01x
