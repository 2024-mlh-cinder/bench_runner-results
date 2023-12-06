
# Results vs. 3.11.0

- fork: brandtbucher
- ref: justin
- machine: linux-x86_64
- commit hash: 7bb54b5
- commit date: 2023-11-20
- overall geometric mean: 1.02x faster \*
- HPT reliability: 63.27%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-linux-x86_64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| 2to3           | 266 ms                                                 | 274 ms: 1.03x slower                                           |
| chameleon      | 6.86 ms                                                | 7.12 ms: 1.04x slower                                          |
| docutils       | 2.69 sec                                               | 2.65 sec: 1.01x faster                                         |
| tornado_http   | 97.7 ms                                                | 96.9 ms: 1.01x faster                                          |
| Geometric mean | (ref)                                                  | 1.01x slower                                                   |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-linux-x86_64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|----------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| async_tree_none            | 532 ms                                                 | 448 ms: 1.19x faster                                           |
| async_tree_memoization     | 640 ms                                                 | 574 ms: 1.12x faster                                           |
| async_tree_io              | 1.31 sec                                               | 1.20 sec: 1.09x faster                                         |
| async_tree_none_tg         | 490 ms                                                 | 464 ms: 1.06x faster                                           |
| async_tree_io_tg           | 1.30 sec                                               | 1.24 sec: 1.05x faster                                         |
| async_tree_cpu_io_mixed    | 750 ms                                                 | 720 ms: 1.04x faster                                           |
| async_tree_memoization_tg  | 627 ms                                                 | 610 ms: 1.03x faster                                           |
| async_tree_cpu_io_mixed_tg | 764 ms                                                 | 750 ms: 1.02x faster                                           |
| Geometric mean             | (ref)                                                  | 1.07x faster                                                   |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-linux-x86_64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| pidigits       | 190 ms                                                 | 195 ms: 1.03x slower                                           |
| float          | 78.9 ms                                                | 86.6 ms: 1.10x slower                                          |
| nbody          | 91.6 ms                                                | 101 ms: 1.11x slower                                           |
| Geometric mean | (ref)                                                  | 1.08x slower                                                   |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-linux-x86_64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| regex_compile  | 141 ms                                                 | 142 ms: 1.01x slower                                           |
| regex_effbot   | 3.45 ms                                                | 3.60 ms: 1.04x slower                                          |
| regex_v8       | 22.9 ms                                                | 24.6 ms: 1.08x slower                                          |
| regex_dna      | 204 ms                                                 | 221 ms: 1.08x slower                                           |
| Geometric mean | (ref)                                                  | 1.05x slower                                                   |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-linux-x86_64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|----------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| json_dumps           | 13.5 ms                                                | 10.5 ms: 1.28x faster                                          |
| tomli_loads          | 2.31 sec                                               | 2.20 sec: 1.05x faster                                         |
| json_loads           | 29.4 us                                                | 28.0 us: 1.05x faster                                          |
| pickle_pure_python   | 319 us                                                 | 305 us: 1.05x faster                                           |
| unpickle_pure_python | 241 us                                                 | 232 us: 1.04x faster                                           |
| xml_etree_parse      | 163 ms                                                 | 160 ms: 1.02x faster                                           |
| xml_etree_iterparse  | 109 ms                                                 | 110 ms: 1.01x slower                                           |
| unpickle_list        | 5.22 us                                                | 5.32 us: 1.02x slower                                          |
| pickle_dict          | 34.8 us                                                | 35.7 us: 1.03x slower                                          |
| pickle               | 11.1 us                                                | 11.4 us: 1.03x slower                                          |
| pickle_list          | 4.65 us                                                | 5.00 us: 1.08x slower                                          |
| xml_etree_process    | 56.5 ms                                                | 61.1 ms: 1.08x slower                                          |
| xml_etree_generate   | 80.4 ms                                                | 89.8 ms: 1.12x slower                                          |
| unpickle             | 13.9 us                                                | 15.9 us: 1.15x slower                                          |
| Geometric mean       | (ref)                                                  | 1.00x slower                                                   |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-linux-x86_64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| python_startup         | 8.69 ms                                                | 10.5 ms: 1.21x slower                                          |
| python_startup_no_site | 6.09 ms                                                | 9.14 ms: 1.50x slower                                          |
| Geometric mean         | (ref)                                                  | 1.35x slower                                                   |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-linux-x86_64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|-----------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| mako      | 10.8 ms                                                | 12.4 ms: 1.15x slower                                          |

All benchmarks:
===============

| Benchmark                  | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-linux-x86_64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|----------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| typing_runtime_protocols   | 521 us                                                 | 121 us: 4.29x faster                                           |
| generators                 | 76.5 ms                                                | 29.8 ms: 2.57x faster                                          |
| asyncio_tcp                | 887 ms                                                 | 494 ms: 1.80x faster                                           |
| asyncio_tcp_ssl            | 3.13 sec                                               | 1.81 sec: 1.73x faster                                         |
| json_dumps                 | 13.5 ms                                                | 10.5 ms: 1.28x faster                                          |
| comprehensions             | 23.6 us                                                | 19.3 us: 1.22x faster                                          |
| mypy2                      | 427 ms                                                 | 352 ms: 1.21x faster                                           |
| coroutines                 | 26.1 ms                                                | 22.0 ms: 1.19x faster                                          |
| async_tree_none            | 532 ms                                                 | 448 ms: 1.19x faster                                           |
| richards_super             | 61.2 ms                                                | 51.7 ms: 1.18x faster                                          |
| async_tree_memoization     | 640 ms                                                 | 574 ms: 1.12x faster                                           |
| async_tree_io              | 1.31 sec                                               | 1.20 sec: 1.09x faster                                         |
| sympy_sum                  | 170 ms                                                 | 157 ms: 1.09x faster                                           |
| sqlglot_parse              | 1.43 ms                                                | 1.33 ms: 1.08x faster                                          |
| chaos                      | 71.4 ms                                                | 66.8 ms: 1.07x faster                                          |
| logging_simple             | 6.24 us                                                | 5.87 us: 1.06x faster                                          |
| sqlglot_transpile          | 1.75 ms                                                | 1.65 ms: 1.06x faster                                          |
| raytrace                   | 306 ms                                                 | 288 ms: 1.06x faster                                           |
| logging_format             | 6.83 us                                                | 6.43 us: 1.06x faster                                          |
| sympy_str                  | 299 ms                                                 | 282 ms: 1.06x faster                                           |
| async_tree_none_tg         | 490 ms                                                 | 464 ms: 1.06x faster                                           |
| tomli_loads                | 2.31 sec                                               | 2.20 sec: 1.05x faster                                         |
| async_tree_io_tg           | 1.30 sec                                               | 1.24 sec: 1.05x faster                                         |
| json_loads                 | 29.4 us                                                | 28.0 us: 1.05x faster                                          |
| richards                   | 48.9 ms                                                | 46.7 ms: 1.05x faster                                          |
| pickle_pure_python         | 319 us                                                 | 305 us: 1.05x faster                                           |
| async_tree_cpu_io_mixed    | 750 ms                                                 | 720 ms: 1.04x faster                                           |
| sympy_expand               | 490 ms                                                 | 471 ms: 1.04x faster                                           |
| unpickle_pure_python       | 241 us                                                 | 232 us: 1.04x faster                                           |
| async_tree_memoization_tg  | 627 ms                                                 | 610 ms: 1.03x faster                                           |
| sqlglot_normalize          | 112 ms                                                 | 109 ms: 1.03x faster                                           |
| pycparser                  | 1.20 sec                                               | 1.17 sec: 1.03x faster                                         |
| sympy_integrate            | 21.4 ms                                                | 20.9 ms: 1.02x faster                                          |
| json                       | 5.24 ms                                                | 5.13 ms: 1.02x faster                                          |
| xml_etree_parse            | 163 ms                                                 | 160 ms: 1.02x faster                                           |
| async_tree_cpu_io_mixed_tg | 764 ms                                                 | 750 ms: 1.02x faster                                           |
| docutils                   | 2.69 sec                                               | 2.65 sec: 1.01x faster                                         |
| tornado_http               | 97.7 ms                                                | 96.9 ms: 1.01x faster                                          |
| asyncio_websockets         | 556 ms                                                 | 552 ms: 1.01x faster                                           |
| create_gc_cycles           | 1.48 ms                                                | 1.48 ms: 1.00x slower                                          |
| regex_compile              | 141 ms                                                 | 142 ms: 1.01x slower                                           |
| sqlglot_optimize           | 55.2 ms                                                | 55.6 ms: 1.01x slower                                          |
| xml_etree_iterparse        | 109 ms                                                 | 110 ms: 1.01x slower                                           |
| pathlib                    | 18.5 ms                                                | 18.6 ms: 1.01x slower                                          |
| mdp                        | 2.79 sec                                               | 2.82 sec: 1.01x slower                                         |
| crypto_pyaes               | 77.5 ms                                                | 78.3 ms: 1.01x slower                                          |
| gc_traversal               | 3.90 ms                                                | 3.95 ms: 1.01x slower                                          |
| logging_silent             | 108 ns                                                 | 110 ns: 1.01x slower                                           |
| unpickle_list              | 5.22 us                                                | 5.32 us: 1.02x slower                                          |
| dulwich_log                | 64.9 ms                                                | 66.4 ms: 1.02x slower                                          |
| bench_thread_pool          | 833 us                                                 | 852 us: 1.02x slower                                           |
| unpack_sequence            | 43.3 ns                                                | 44.3 ns: 1.02x slower                                          |
| meteor_contest             | 109 ms                                                 | 111 ms: 1.02x slower                                           |
| pickle_dict                | 34.8 us                                                | 35.7 us: 1.03x slower                                          |
| pidigits                   | 190 ms                                                 | 195 ms: 1.03x slower                                           |
| pprint_pformat             | 1.53 sec                                               | 1.57 sec: 1.03x slower                                         |
| pickle                     | 11.1 us                                                | 11.4 us: 1.03x slower                                          |
| pprint_safe_repr           | 743 ms                                                 | 764 ms: 1.03x slower                                           |
| scimark_sor                | 121 ms                                                 | 125 ms: 1.03x slower                                           |
| 2to3                       | 266 ms                                                 | 274 ms: 1.03x slower                                           |
| deepcopy_memo              | 38.9 us                                                | 40.3 us: 1.04x slower                                          |
| chameleon                  | 6.86 ms                                                | 7.12 ms: 1.04x slower                                          |
| regex_effbot               | 3.45 ms                                                | 3.60 ms: 1.04x slower                                          |
| scimark_lu                 | 112 ms                                                 | 118 ms: 1.05x slower                                           |
| fannkuch                   | 410 ms                                                 | 430 ms: 1.05x slower                                           |
| nqueens                    | 86.8 ms                                                | 91.1 ms: 1.05x slower                                          |
| scimark_monte_carlo        | 71.8 ms                                                | 75.7 ms: 1.05x slower                                          |
| go                         | 143 ms                                                 | 151 ms: 1.06x slower                                           |
| deltablue                  | 3.80 ms                                                | 4.05 ms: 1.06x slower                                          |
| pickle_list                | 4.65 us                                                | 5.00 us: 1.08x slower                                          |
| regex_v8                   | 22.9 ms                                                | 24.6 ms: 1.08x slower                                          |
| regex_dna                  | 204 ms                                                 | 221 ms: 1.08x slower                                           |
| xml_etree_process          | 56.5 ms                                                | 61.1 ms: 1.08x slower                                          |
| sqlite_synth               | 2.58 us                                                | 2.82 us: 1.09x slower                                          |
| float                      | 78.9 ms                                                | 86.6 ms: 1.10x slower                                          |
| nbody                      | 91.6 ms                                                | 101 ms: 1.11x slower                                           |
| xml_etree_generate         | 80.4 ms                                                | 89.8 ms: 1.12x slower                                          |
| hexiom                     | 6.74 ms                                                | 7.53 ms: 1.12x slower                                          |
| scimark_sparse_mat_mult    | 4.80 ms                                                | 5.39 ms: 1.12x slower                                          |
| scimark_fft                | 342 ms                                                 | 384 ms: 1.12x slower                                           |
| mako                       | 10.8 ms                                                | 12.4 ms: 1.15x slower                                          |
| unpickle                   | 13.9 us                                                | 15.9 us: 1.15x slower                                          |
| pyflate                    | 426 ms                                                 | 498 ms: 1.17x slower                                           |
| coverage                   | 81.2 ms                                                | 96.2 ms: 1.18x slower                                          |
| python_startup             | 8.69 ms                                                | 10.5 ms: 1.21x slower                                          |
| async_generators           | 375 ms                                                 | 465 ms: 1.24x slower                                           |
| telco                      | 6.72 ms                                                | 8.35 ms: 1.24x slower                                          |
| spectral_norm              | 105 ms                                                 | 138 ms: 1.31x slower                                           |
| python_startup_no_site     | 6.09 ms                                                | 9.14 ms: 1.50x slower                                          |
| Geometric mean             | (ref)                                                  | 1.02x faster                                                   |

Benchmark hidden because not significant (4): deepcopy_reduce, bench_mp_pool, deepcopy, dask
Ignored benchmarks (12) of results/bm-20221024-3.11.0-deaf509/bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift


# HPT report

- Reliability score: 63.27% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
