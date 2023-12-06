
# Results vs. 3.11.0

- fork: brandtbucher
- ref: justin
- machine: linux-x86_64
- commit hash: 7bb54b5
- commit date: 2023-11-20
- overall geometric mean: 1.03x faster \*
- HPT reliability: 62.55%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-linux-x86_64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| 2to3           | 266 ms                                                 | 273 ms: 1.03x slower                                           |
| chameleon      | 6.86 ms                                                | 7.11 ms: 1.04x slower                                          |
| docutils       | 2.69 sec                                               | 2.66 sec: 1.01x faster                                         |
| tornado_http   | 97.7 ms                                                | 96.5 ms: 1.01x faster                                          |
| Geometric mean | (ref)                                                  | 1.01x slower                                                   |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-linux-x86_64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|----------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| async_tree_none            | 532 ms                                                 | 443 ms: 1.20x faster                                           |
| async_tree_memoization     | 640 ms                                                 | 571 ms: 1.12x faster                                           |
| async_tree_io              | 1.31 sec                                               | 1.20 sec: 1.09x faster                                         |
| async_tree_none_tg         | 490 ms                                                 | 458 ms: 1.07x faster                                           |
| async_tree_io_tg           | 1.30 sec                                               | 1.23 sec: 1.06x faster                                         |
| async_tree_cpu_io_mixed    | 750 ms                                                 | 718 ms: 1.04x faster                                           |
| async_tree_memoization_tg  | 627 ms                                                 | 602 ms: 1.04x faster                                           |
| async_tree_cpu_io_mixed_tg | 764 ms                                                 | 747 ms: 1.02x faster                                           |
| Geometric mean             | (ref)                                                  | 1.08x faster                                                   |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-linux-x86_64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| pidigits       | 190 ms                                                 | 188 ms: 1.01x faster                                           |
| float          | 78.9 ms                                                | 85.0 ms: 1.08x slower                                          |
| nbody          | 91.6 ms                                                | 100 ms: 1.09x slower                                           |
| Geometric mean | (ref)                                                  | 1.05x slower                                                   |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-linux-x86_64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| regex_effbot   | 3.45 ms                                                | 3.63 ms: 1.05x slower                                          |
| regex_dna      | 204 ms                                                 | 216 ms: 1.06x slower                                           |
| regex_v8       | 22.9 ms                                                | 24.3 ms: 1.06x slower                                          |
| Geometric mean | (ref)                                                  | 1.04x slower                                                   |

Benchmark hidden because not significant (1): regex_compile

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-linux-x86_64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|----------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| json_dumps           | 13.5 ms                                                | 10.6 ms: 1.27x faster                                          |
| tomli_loads          | 2.31 sec                                               | 2.21 sec: 1.05x faster                                         |
| json_loads           | 29.4 us                                                | 28.4 us: 1.04x faster                                          |
| unpickle_pure_python | 241 us                                                 | 232 us: 1.04x faster                                           |
| pickle_pure_python   | 319 us                                                 | 309 us: 1.03x faster                                           |
| pickle_dict          | 34.8 us                                                | 34.0 us: 1.02x faster                                          |
| xml_etree_parse      | 163 ms                                                 | 160 ms: 1.01x faster                                           |
| xml_etree_iterparse  | 109 ms                                                 | 110 ms: 1.01x slower                                           |
| unpickle_list        | 5.22 us                                                | 5.28 us: 1.01x slower                                          |
| pickle               | 11.1 us                                                | 11.2 us: 1.01x slower                                          |
| pickle_list          | 4.65 us                                                | 4.89 us: 1.05x slower                                          |
| xml_etree_process    | 56.5 ms                                                | 61.0 ms: 1.08x slower                                          |
| xml_etree_generate   | 80.4 ms                                                | 89.1 ms: 1.11x slower                                          |
| unpickle             | 13.9 us                                                | 15.5 us: 1.12x slower                                          |
| Geometric mean       | (ref)                                                  | 1.00x faster                                                   |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-linux-x86_64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| python_startup         | 8.69 ms                                                | 10.4 ms: 1.20x slower                                          |
| python_startup_no_site | 6.09 ms                                                | 9.10 ms: 1.49x slower                                          |
| Geometric mean         | (ref)                                                  | 1.34x slower                                                   |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-linux-x86_64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|-----------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| mako      | 10.8 ms                                                | 12.4 ms: 1.15x slower                                          |

All benchmarks:
===============

| Benchmark                  | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-linux-x86_64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|----------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| typing_runtime_protocols   | 521 us                                                 | 120 us: 4.34x faster                                           |
| generators                 | 76.5 ms                                                | 29.8 ms: 2.57x faster                                          |
| asyncio_tcp                | 887 ms                                                 | 489 ms: 1.81x faster                                           |
| asyncio_tcp_ssl            | 3.13 sec                                               | 1.80 sec: 1.73x faster                                         |
| json_dumps                 | 13.5 ms                                                | 10.6 ms: 1.27x faster                                          |
| comprehensions             | 23.6 us                                                | 19.3 us: 1.22x faster                                          |
| mypy2                      | 427 ms                                                 | 351 ms: 1.22x faster                                           |
| async_tree_none            | 532 ms                                                 | 443 ms: 1.20x faster                                           |
| coroutines                 | 26.1 ms                                                | 21.8 ms: 1.20x faster                                          |
| richards_super             | 61.2 ms                                                | 52.0 ms: 1.18x faster                                          |
| async_tree_memoization     | 640 ms                                                 | 571 ms: 1.12x faster                                           |
| async_tree_io              | 1.31 sec                                               | 1.20 sec: 1.09x faster                                         |
| sympy_sum                  | 170 ms                                                 | 156 ms: 1.09x faster                                           |
| sqlglot_parse              | 1.43 ms                                                | 1.32 ms: 1.08x faster                                          |
| chaos                      | 71.4 ms                                                | 66.3 ms: 1.08x faster                                          |
| logging_simple             | 6.24 us                                                | 5.80 us: 1.08x faster                                          |
| raytrace                   | 306 ms                                                 | 286 ms: 1.07x faster                                           |
| async_tree_none_tg         | 490 ms                                                 | 458 ms: 1.07x faster                                           |
| logging_format             | 6.83 us                                                | 6.39 us: 1.07x faster                                          |
| sqlglot_transpile          | 1.75 ms                                                | 1.65 ms: 1.07x faster                                          |
| sympy_str                  | 299 ms                                                 | 282 ms: 1.06x faster                                           |
| async_tree_io_tg           | 1.30 sec                                               | 1.23 sec: 1.06x faster                                         |
| tomli_loads                | 2.31 sec                                               | 2.21 sec: 1.05x faster                                         |
| sympy_expand               | 490 ms                                                 | 468 ms: 1.05x faster                                           |
| richards                   | 48.9 ms                                                | 46.8 ms: 1.04x faster                                          |
| async_tree_cpu_io_mixed    | 750 ms                                                 | 718 ms: 1.04x faster                                           |
| async_tree_memoization_tg  | 627 ms                                                 | 602 ms: 1.04x faster                                           |
| mdp                        | 2.79 sec                                               | 2.68 sec: 1.04x faster                                         |
| json_loads                 | 29.4 us                                                | 28.4 us: 1.04x faster                                          |
| unpickle_pure_python       | 241 us                                                 | 232 us: 1.04x faster                                           |
| pickle_pure_python         | 319 us                                                 | 309 us: 1.03x faster                                           |
| pycparser                  | 1.20 sec                                               | 1.16 sec: 1.03x faster                                         |
| sqlglot_normalize          | 112 ms                                                 | 109 ms: 1.03x faster                                           |
| sympy_integrate            | 21.4 ms                                                | 20.8 ms: 1.03x faster                                          |
| pickle_dict                | 34.8 us                                                | 34.0 us: 1.02x faster                                          |
| async_tree_cpu_io_mixed_tg | 764 ms                                                 | 747 ms: 1.02x faster                                           |
| deepcopy                   | 360 us                                                 | 353 us: 1.02x faster                                           |
| deepcopy_reduce            | 3.14 us                                                | 3.07 us: 1.02x faster                                          |
| pidigits                   | 190 ms                                                 | 188 ms: 1.01x faster                                           |
| xml_etree_parse            | 163 ms                                                 | 160 ms: 1.01x faster                                           |
| tornado_http               | 97.7 ms                                                | 96.5 ms: 1.01x faster                                          |
| docutils                   | 2.69 sec                                               | 2.66 sec: 1.01x faster                                         |
| json                       | 5.24 ms                                                | 5.19 ms: 1.01x faster                                          |
| create_gc_cycles           | 1.48 ms                                                | 1.46 ms: 1.01x faster                                          |
| asyncio_websockets         | 556 ms                                                 | 553 ms: 1.00x faster                                           |
| pathlib                    | 18.5 ms                                                | 18.6 ms: 1.01x slower                                          |
| sqlglot_optimize           | 55.2 ms                                                | 55.6 ms: 1.01x slower                                          |
| xml_etree_iterparse        | 109 ms                                                 | 110 ms: 1.01x slower                                           |
| unpickle_list              | 5.22 us                                                | 5.28 us: 1.01x slower                                          |
| pickle                     | 11.1 us                                                | 11.2 us: 1.01x slower                                          |
| logging_silent             | 108 ns                                                 | 110 ns: 1.02x slower                                           |
| meteor_contest             | 109 ms                                                 | 111 ms: 1.02x slower                                           |
| dulwich_log                | 64.9 ms                                                | 66.4 ms: 1.02x slower                                          |
| crypto_pyaes               | 77.5 ms                                                | 79.4 ms: 1.02x slower                                          |
| bench_thread_pool          | 833 us                                                 | 854 us: 1.03x slower                                           |
| 2to3                       | 266 ms                                                 | 273 ms: 1.03x slower                                           |
| pprint_pformat             | 1.53 sec                                               | 1.57 sec: 1.03x slower                                         |
| pprint_safe_repr           | 743 ms                                                 | 766 ms: 1.03x slower                                           |
| gc_traversal               | 3.90 ms                                                | 4.04 ms: 1.04x slower                                          |
| chameleon                  | 6.86 ms                                                | 7.11 ms: 1.04x slower                                          |
| deepcopy_memo              | 38.9 us                                                | 40.4 us: 1.04x slower                                          |
| scimark_sor                | 121 ms                                                 | 127 ms: 1.04x slower                                           |
| scimark_monte_carlo        | 71.8 ms                                                | 75.3 ms: 1.05x slower                                          |
| pickle_list                | 4.65 us                                                | 4.89 us: 1.05x slower                                          |
| regex_effbot               | 3.45 ms                                                | 3.63 ms: 1.05x slower                                          |
| scimark_lu                 | 112 ms                                                 | 119 ms: 1.05x slower                                           |
| regex_dna                  | 204 ms                                                 | 216 ms: 1.06x slower                                           |
| fannkuch                   | 410 ms                                                 | 434 ms: 1.06x slower                                           |
| go                         | 143 ms                                                 | 152 ms: 1.06x slower                                           |
| regex_v8                   | 22.9 ms                                                | 24.3 ms: 1.06x slower                                          |
| deltablue                  | 3.80 ms                                                | 4.06 ms: 1.07x slower                                          |
| float                      | 78.9 ms                                                | 85.0 ms: 1.08x slower                                          |
| xml_etree_process          | 56.5 ms                                                | 61.0 ms: 1.08x slower                                          |
| unpack_sequence            | 43.3 ns                                                | 46.9 ns: 1.08x slower                                          |
| nqueens                    | 86.8 ms                                                | 94.4 ms: 1.09x slower                                          |
| sqlite_synth               | 2.58 us                                                | 2.81 us: 1.09x slower                                          |
| nbody                      | 91.6 ms                                                | 100 ms: 1.09x slower                                           |
| scimark_sparse_mat_mult    | 4.80 ms                                                | 5.31 ms: 1.10x slower                                          |
| xml_etree_generate         | 80.4 ms                                                | 89.1 ms: 1.11x slower                                          |
| scimark_fft                | 342 ms                                                 | 382 ms: 1.12x slower                                           |
| unpickle                   | 13.9 us                                                | 15.5 us: 1.12x slower                                          |
| hexiom                     | 6.74 ms                                                | 7.60 ms: 1.13x slower                                          |
| mako                       | 10.8 ms                                                | 12.4 ms: 1.15x slower                                          |
| coverage                   | 81.2 ms                                                | 95.4 ms: 1.18x slower                                          |
| pyflate                    | 426 ms                                                 | 502 ms: 1.18x slower                                           |
| python_startup             | 8.69 ms                                                | 10.4 ms: 1.20x slower                                          |
| async_generators           | 375 ms                                                 | 464 ms: 1.24x slower                                           |
| telco                      | 6.72 ms                                                | 8.31 ms: 1.24x slower                                          |
| spectral_norm              | 105 ms                                                 | 137 ms: 1.30x slower                                           |
| python_startup_no_site     | 6.09 ms                                                | 9.10 ms: 1.49x slower                                          |
| Geometric mean             | (ref)                                                  | 1.03x faster                                                   |

Benchmark hidden because not significant (3): regex_compile, bench_mp_pool, dask
Ignored benchmarks (12) of results/bm-20221024-3.11.0-deaf509/bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift


# HPT report

- Reliability score: 62.55% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
