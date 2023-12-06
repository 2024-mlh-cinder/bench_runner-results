
# Results vs. 3.11.0

- fork: brandtbucher
- ref: justin
- machine: linux-x86_64
- commit hash: d65308a
- commit date: 2023-11-08
- overall geometric mean: 1.04x faster \*
- HPT reliability: 77.85%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231108-linux-x86_64-brandtbucher-justin-3.13.0a1+-d65308a |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| 2to3           | 266 ms                                                 | 270 ms: 1.01x slower                                           |
| chameleon      | 6.86 ms                                                | 7.18 ms: 1.05x slower                                          |
| docutils       | 2.69 sec                                               | 2.66 sec: 1.01x faster                                         |
| tornado_http   | 97.7 ms                                                | 96.7 ms: 1.01x faster                                          |
| Geometric mean | (ref)                                                  | 1.01x slower                                                   |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231108-linux-x86_64-brandtbucher-justin-3.13.0a1+-d65308a |
|----------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| async_tree_none            | 532 ms                                                 | 448 ms: 1.19x faster                                           |
| async_tree_memoization     | 640 ms                                                 | 572 ms: 1.12x faster                                           |
| async_tree_io              | 1.31 sec                                               | 1.19 sec: 1.10x faster                                         |
| async_tree_none_tg         | 490 ms                                                 | 464 ms: 1.06x faster                                           |
| async_tree_io_tg           | 1.30 sec                                               | 1.24 sec: 1.05x faster                                         |
| async_tree_cpu_io_mixed    | 750 ms                                                 | 721 ms: 1.04x faster                                           |
| async_tree_memoization_tg  | 627 ms                                                 | 604 ms: 1.04x faster                                           |
| async_tree_cpu_io_mixed_tg | 764 ms                                                 | 751 ms: 1.02x faster                                           |
| Geometric mean             | (ref)                                                  | 1.07x faster                                                   |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231108-linux-x86_64-brandtbucher-justin-3.13.0a1+-d65308a |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| pidigits       | 190 ms                                                 | 195 ms: 1.03x slower                                           |
| nbody          | 91.6 ms                                                | 94.2 ms: 1.03x slower                                          |
| float          | 78.9 ms                                                | 82.0 ms: 1.04x slower                                          |
| Geometric mean | (ref)                                                  | 1.03x slower                                                   |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231108-linux-x86_64-brandtbucher-justin-3.13.0a1+-d65308a |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| regex_compile  | 141 ms                                                 | 140 ms: 1.01x faster                                           |
| regex_effbot   | 3.45 ms                                                | 3.59 ms: 1.04x slower                                          |
| regex_dna      | 204 ms                                                 | 223 ms: 1.09x slower                                           |
| regex_v8       | 22.9 ms                                                | 25.8 ms: 1.13x slower                                          |
| Geometric mean | (ref)                                                  | 1.06x slower                                                   |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231108-linux-x86_64-brandtbucher-justin-3.13.0a1+-d65308a |
|----------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| json_dumps           | 13.5 ms                                                | 10.5 ms: 1.28x faster                                          |
| tomli_loads          | 2.31 sec                                               | 2.04 sec: 1.13x faster                                         |
| pickle_pure_python   | 319 us                                                 | 299 us: 1.07x faster                                           |
| unpickle_pure_python | 241 us                                                 | 227 us: 1.06x faster                                           |
| json_loads           | 29.4 us                                                | 27.9 us: 1.06x faster                                          |
| xml_etree_parse      | 163 ms                                                 | 158 ms: 1.03x faster                                           |
| pickle_dict          | 34.8 us                                                | 34.3 us: 1.02x faster                                          |
| xml_etree_iterparse  | 109 ms                                                 | 107 ms: 1.01x faster                                           |
| pickle               | 11.1 us                                                | 11.6 us: 1.05x slower                                          |
| xml_etree_process    | 56.5 ms                                                | 60.4 ms: 1.07x slower                                          |
| pickle_list          | 4.65 us                                                | 4.97 us: 1.07x slower                                          |
| xml_etree_generate   | 80.4 ms                                                | 87.1 ms: 1.08x slower                                          |
| unpickle             | 13.9 us                                                | 15.2 us: 1.09x slower                                          |
| Geometric mean       | (ref)                                                  | 1.02x faster                                                   |

Benchmark hidden because not significant (1): unpickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231108-linux-x86_64-brandtbucher-justin-3.13.0a1+-d65308a |
|------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| python_startup         | 8.69 ms                                                | 10.4 ms: 1.19x slower                                          |
| python_startup_no_site | 6.09 ms                                                | 9.07 ms: 1.49x slower                                          |
| Geometric mean         | (ref)                                                  | 1.33x slower                                                   |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231108-linux-x86_64-brandtbucher-justin-3.13.0a1+-d65308a |
|-----------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| mako      | 10.8 ms                                                | 11.4 ms: 1.05x slower                                          |

All benchmarks:
===============

| Benchmark                  | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231108-linux-x86_64-brandtbucher-justin-3.13.0a1+-d65308a |
|----------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| typing_runtime_protocols   | 521 us                                                 | 121 us: 4.30x faster                                           |
| generators                 | 76.5 ms                                                | 30.9 ms: 2.48x faster                                          |
| asyncio_tcp                | 887 ms                                                 | 488 ms: 1.82x faster                                           |
| asyncio_tcp_ssl            | 3.13 sec                                               | 1.80 sec: 1.74x faster                                         |
| json_dumps                 | 13.5 ms                                                | 10.5 ms: 1.28x faster                                          |
| comprehensions             | 23.6 us                                                | 18.5 us: 1.27x faster                                          |
| mypy2                      | 427 ms                                                 | 350 ms: 1.22x faster                                           |
| async_tree_none            | 532 ms                                                 | 448 ms: 1.19x faster                                           |
| richards_super             | 61.2 ms                                                | 52.0 ms: 1.18x faster                                          |
| coroutines                 | 26.1 ms                                                | 22.4 ms: 1.17x faster                                          |
| tomli_loads                | 2.31 sec                                               | 2.04 sec: 1.13x faster                                         |
| chaos                      | 71.4 ms                                                | 63.3 ms: 1.13x faster                                          |
| async_tree_memoization     | 640 ms                                                 | 572 ms: 1.12x faster                                           |
| sympy_sum                  | 170 ms                                                 | 153 ms: 1.11x faster                                           |
| sqlglot_parse              | 1.43 ms                                                | 1.29 ms: 1.11x faster                                          |
| async_tree_io              | 1.31 sec                                               | 1.19 sec: 1.10x faster                                         |
| sympy_str                  | 299 ms                                                 | 273 ms: 1.10x faster                                           |
| logging_simple             | 6.24 us                                                | 5.74 us: 1.09x faster                                          |
| sqlglot_transpile          | 1.75 ms                                                | 1.62 ms: 1.08x faster                                          |
| raytrace                   | 306 ms                                                 | 283 ms: 1.08x faster                                           |
| logging_format             | 6.83 us                                                | 6.35 us: 1.08x faster                                          |
| sympy_expand               | 490 ms                                                 | 459 ms: 1.07x faster                                           |
| pickle_pure_python         | 319 us                                                 | 299 us: 1.07x faster                                           |
| sqlglot_normalize          | 112 ms                                                 | 106 ms: 1.06x faster                                           |
| unpickle_pure_python       | 241 us                                                 | 227 us: 1.06x faster                                           |
| json_loads                 | 29.4 us                                                | 27.9 us: 1.06x faster                                          |
| async_tree_none_tg         | 490 ms                                                 | 464 ms: 1.06x faster                                           |
| crypto_pyaes               | 77.5 ms                                                | 73.4 ms: 1.06x faster                                          |
| async_tree_io_tg           | 1.30 sec                                               | 1.24 sec: 1.05x faster                                         |
| richards                   | 48.9 ms                                                | 46.6 ms: 1.05x faster                                          |
| sympy_integrate            | 21.4 ms                                                | 20.4 ms: 1.05x faster                                          |
| async_tree_cpu_io_mixed    | 750 ms                                                 | 721 ms: 1.04x faster                                           |
| async_tree_memoization_tg  | 627 ms                                                 | 604 ms: 1.04x faster                                           |
| logging_silent             | 108 ns                                                 | 105 ns: 1.03x faster                                           |
| xml_etree_parse            | 163 ms                                                 | 158 ms: 1.03x faster                                           |
| deltablue                  | 3.80 ms                                                | 3.71 ms: 1.03x faster                                          |
| deepcopy                   | 360 us                                                 | 351 us: 1.03x faster                                           |
| gc_traversal               | 3.90 ms                                                | 3.82 ms: 1.02x faster                                          |
| sqlglot_optimize           | 55.2 ms                                                | 54.2 ms: 1.02x faster                                          |
| async_tree_cpu_io_mixed_tg | 764 ms                                                 | 751 ms: 1.02x faster                                           |
| pickle_dict                | 34.8 us                                                | 34.3 us: 1.02x faster                                          |
| deepcopy_reduce            | 3.14 us                                                | 3.10 us: 1.01x faster                                          |
| json                       | 5.24 ms                                                | 5.17 ms: 1.01x faster                                          |
| create_gc_cycles           | 1.48 ms                                                | 1.46 ms: 1.01x faster                                          |
| docutils                   | 2.69 sec                                               | 2.66 sec: 1.01x faster                                         |
| xml_etree_iterparse        | 109 ms                                                 | 107 ms: 1.01x faster                                           |
| regex_compile              | 141 ms                                                 | 140 ms: 1.01x faster                                           |
| tornado_http               | 97.7 ms                                                | 96.7 ms: 1.01x faster                                          |
| asyncio_websockets         | 556 ms                                                 | 552 ms: 1.01x faster                                           |
| mdp                        | 2.79 sec                                               | 2.82 sec: 1.01x slower                                         |
| 2to3                       | 266 ms                                                 | 270 ms: 1.01x slower                                           |
| nqueens                    | 86.8 ms                                                | 88.5 ms: 1.02x slower                                          |
| deepcopy_memo              | 38.9 us                                                | 39.8 us: 1.02x slower                                          |
| scimark_sor                | 121 ms                                                 | 124 ms: 1.02x slower                                           |
| bench_thread_pool          | 833 us                                                 | 853 us: 1.02x slower                                           |
| pidigits                   | 190 ms                                                 | 195 ms: 1.03x slower                                           |
| spectral_norm              | 105 ms                                                 | 108 ms: 1.03x slower                                           |
| pprint_safe_repr           | 743 ms                                                 | 764 ms: 1.03x slower                                           |
| nbody                      | 91.6 ms                                                | 94.2 ms: 1.03x slower                                          |
| go                         | 143 ms                                                 | 147 ms: 1.03x slower                                           |
| dulwich_log                | 64.9 ms                                                | 66.9 ms: 1.03x slower                                          |
| pprint_pformat             | 1.53 sec                                               | 1.58 sec: 1.03x slower                                         |
| pathlib                    | 18.5 ms                                                | 19.2 ms: 1.04x slower                                          |
| float                      | 78.9 ms                                                | 82.0 ms: 1.04x slower                                          |
| regex_effbot               | 3.45 ms                                                | 3.59 ms: 1.04x slower                                          |
| hexiom                     | 6.74 ms                                                | 7.04 ms: 1.04x slower                                          |
| chameleon                  | 6.86 ms                                                | 7.18 ms: 1.05x slower                                          |
| meteor_contest             | 109 ms                                                 | 114 ms: 1.05x slower                                           |
| pickle                     | 11.1 us                                                | 11.6 us: 1.05x slower                                          |
| mako                       | 10.8 ms                                                | 11.4 ms: 1.05x slower                                          |
| scimark_lu                 | 112 ms                                                 | 119 ms: 1.06x slower                                           |
| xml_etree_process          | 56.5 ms                                                | 60.4 ms: 1.07x slower                                          |
| pickle_list                | 4.65 us                                                | 4.97 us: 1.07x slower                                          |
| scimark_fft                | 342 ms                                                 | 369 ms: 1.08x slower                                           |
| sqlite_synth               | 2.58 us                                                | 2.79 us: 1.08x slower                                          |
| xml_etree_generate         | 80.4 ms                                                | 87.1 ms: 1.08x slower                                          |
| regex_dna                  | 204 ms                                                 | 223 ms: 1.09x slower                                           |
| unpickle                   | 13.9 us                                                | 15.2 us: 1.09x slower                                          |
| regex_v8                   | 22.9 ms                                                | 25.8 ms: 1.13x slower                                          |
| pyflate                    | 426 ms                                                 | 490 ms: 1.15x slower                                           |
| coverage                   | 81.2 ms                                                | 94.5 ms: 1.16x slower                                          |
| python_startup             | 8.69 ms                                                | 10.4 ms: 1.19x slower                                          |
| async_generators           | 375 ms                                                 | 459 ms: 1.22x slower                                           |
| unpack_sequence            | 43.3 ns                                                | 53.2 ns: 1.23x slower                                          |
| telco                      | 6.72 ms                                                | 8.27 ms: 1.23x slower                                          |
| python_startup_no_site     | 6.09 ms                                                | 9.07 ms: 1.49x slower                                          |
| Geometric mean             | (ref)                                                  | 1.04x faster                                                   |

Benchmark hidden because not significant (6): scimark_sparse_mat_mult, scimark_monte_carlo, fannkuch, bench_mp_pool, unpickle_list, pycparser
Ignored benchmarks (13) of results/bm-20221024-3.11.0-deaf509/bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift


# HPT report

- Reliability score: 77.85% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
