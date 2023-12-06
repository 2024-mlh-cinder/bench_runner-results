
# Results vs. 3.11.0

- fork: python
- ref: main
- machine: linux-x86_64
- commit hash: 853b4b5
- commit date: 2023-11-04
- overall geometric mean: 1.07x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.01x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231104-linux-x86_64-python-main-3.13.0a1+-853b4b5 |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| 2to3           | 266 ms                                                 | 262 ms: 1.01x faster                                   |
| docutils       | 2.69 sec                                               | 2.59 sec: 1.04x faster                                 |
| tornado_http   | 97.7 ms                                                | 95.2 ms: 1.03x faster                                  |
| Geometric mean | (ref)                                                  | 1.02x faster                                           |

Benchmark hidden because not significant (1): chameleon

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231104-linux-x86_64-python-main-3.13.0a1+-853b4b5 |
|----------------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| async_tree_none            | 532 ms                                                 | 439 ms: 1.21x faster                                   |
| async_tree_memoization     | 640 ms                                                 | 565 ms: 1.13x faster                                   |
| async_tree_io              | 1.31 sec                                               | 1.19 sec: 1.10x faster                                 |
| async_tree_none_tg         | 490 ms                                                 | 458 ms: 1.07x faster                                   |
| async_tree_io_tg           | 1.30 sec                                               | 1.24 sec: 1.05x faster                                 |
| async_tree_cpu_io_mixed    | 750 ms                                                 | 711 ms: 1.05x faster                                   |
| async_tree_memoization_tg  | 627 ms                                                 | 600 ms: 1.05x faster                                   |
| async_tree_cpu_io_mixed_tg | 764 ms                                                 | 743 ms: 1.03x faster                                   |
| Geometric mean             | (ref)                                                  | 1.09x faster                                           |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231104-linux-x86_64-python-main-3.13.0a1+-853b4b5 |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| nbody          | 91.6 ms                                                | 90.5 ms: 1.01x faster                                  |
| pidigits       | 190 ms                                                 | 195 ms: 1.02x slower                                   |
| float          | 78.9 ms                                                | 81.5 ms: 1.03x slower                                  |
| Geometric mean | (ref)                                                  | 1.02x slower                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231104-linux-x86_64-python-main-3.13.0a1+-853b4b5 |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| regex_compile  | 141 ms                                                 | 134 ms: 1.05x faster                                   |
| regex_effbot   | 3.45 ms                                                | 3.53 ms: 1.02x slower                                  |
| regex_v8       | 22.9 ms                                                | 24.3 ms: 1.06x slower                                  |
| regex_dna      | 204 ms                                                 | 222 ms: 1.09x slower                                   |
| Geometric mean | (ref)                                                  | 1.03x slower                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231104-linux-x86_64-python-main-3.13.0a1+-853b4b5 |
|----------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| json_dumps           | 13.5 ms                                                | 10.4 ms: 1.30x faster                                  |
| unpickle_pure_python | 241 us                                                 | 218 us: 1.10x faster                                   |
| tomli_loads          | 2.31 sec                                               | 2.12 sec: 1.09x faster                                 |
| pickle_pure_python   | 319 us                                                 | 295 us: 1.08x faster                                   |
| json_loads           | 29.4 us                                                | 27.5 us: 1.07x faster                                  |
| xml_etree_iterparse  | 109 ms                                                 | 105 ms: 1.04x faster                                   |
| xml_etree_parse      | 163 ms                                                 | 159 ms: 1.03x faster                                   |
| unpickle_list        | 5.22 us                                                | 5.19 us: 1.01x faster                                  |
| pickle_dict          | 34.8 us                                                | 36.1 us: 1.04x slower                                  |
| pickle               | 11.1 us                                                | 11.5 us: 1.04x slower                                  |
| xml_etree_process    | 56.5 ms                                                | 59.1 ms: 1.05x slower                                  |
| xml_etree_generate   | 80.4 ms                                                | 86.6 ms: 1.08x slower                                  |
| unpickle             | 13.9 us                                                | 15.3 us: 1.10x slower                                  |
| pickle_list          | 4.65 us                                                | 5.24 us: 1.13x slower                                  |
| Geometric mean       | (ref)                                                  | 1.02x faster                                           |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231104-linux-x86_64-python-main-3.13.0a1+-853b4b5 |
|------------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| python_startup         | 8.69 ms                                                | 10.3 ms: 1.19x slower                                  |
| python_startup_no_site | 6.09 ms                                                | 8.97 ms: 1.47x slower                                  |
| Geometric mean         | (ref)                                                  | 1.32x slower                                           |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231104-linux-x86_64-python-main-3.13.0a1+-853b4b5 |
|-----------|:------------------------------------------------------:|:------------------------------------------------------:|
| mako      | 10.8 ms                                                | 11.1 ms: 1.02x slower                                  |

All benchmarks:
===============

| Benchmark                  | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231104-linux-x86_64-python-main-3.13.0a1+-853b4b5 |
|----------------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| typing_runtime_protocols   | 521 us                                                 | 115 us: 4.54x faster                                   |
| generators                 | 76.5 ms                                                | 29.5 ms: 2.59x faster                                  |
| asyncio_tcp                | 887 ms                                                 | 484 ms: 1.83x faster                                   |
| asyncio_tcp_ssl            | 3.13 sec                                               | 1.79 sec: 1.75x faster                                 |
| comprehensions             | 23.6 us                                                | 15.9 us: 1.48x faster                                  |
| json_dumps                 | 13.5 ms                                                | 10.4 ms: 1.30x faster                                  |
| mypy2                      | 427 ms                                                 | 340 ms: 1.26x faster                                   |
| async_tree_none            | 532 ms                                                 | 439 ms: 1.21x faster                                   |
| chaos                      | 71.4 ms                                                | 59.8 ms: 1.19x faster                                  |
| coroutines                 | 26.1 ms                                                | 22.0 ms: 1.19x faster                                  |
| deltablue                  | 3.80 ms                                                | 3.25 ms: 1.17x faster                                  |
| sympy_sum                  | 170 ms                                                 | 146 ms: 1.16x faster                                   |
| raytrace                   | 306 ms                                                 | 268 ms: 1.14x faster                                   |
| sqlglot_parse              | 1.43 ms                                                | 1.26 ms: 1.14x faster                                  |
| async_tree_memoization     | 640 ms                                                 | 565 ms: 1.13x faster                                   |
| sympy_str                  | 299 ms                                                 | 265 ms: 1.13x faster                                   |
| hexiom                     | 6.74 ms                                                | 6.03 ms: 1.12x faster                                  |
| nqueens                    | 86.8 ms                                                | 77.7 ms: 1.12x faster                                  |
| sqlglot_transpile          | 1.75 ms                                                | 1.58 ms: 1.11x faster                                  |
| richards_super             | 61.2 ms                                                | 55.0 ms: 1.11x faster                                  |
| sympy_integrate            | 21.4 ms                                                | 19.3 ms: 1.11x faster                                  |
| unpickle_pure_python       | 241 us                                                 | 218 us: 1.10x faster                                   |
| crypto_pyaes               | 77.5 ms                                                | 70.3 ms: 1.10x faster                                  |
| async_tree_io              | 1.31 sec                                               | 1.19 sec: 1.10x faster                                 |
| sympy_expand               | 490 ms                                                 | 447 ms: 1.10x faster                                   |
| logging_simple             | 6.24 us                                                | 5.72 us: 1.09x faster                                  |
| tomli_loads                | 2.31 sec                                               | 2.12 sec: 1.09x faster                                 |
| logging_format             | 6.83 us                                                | 6.30 us: 1.08x faster                                  |
| pickle_pure_python         | 319 us                                                 | 295 us: 1.08x faster                                   |
| mdp                        | 2.79 sec                                               | 2.59 sec: 1.08x faster                                 |
| sqlglot_normalize          | 112 ms                                                 | 104 ms: 1.08x faster                                   |
| json_loads                 | 29.4 us                                                | 27.5 us: 1.07x faster                                  |
| async_tree_none_tg         | 490 ms                                                 | 458 ms: 1.07x faster                                   |
| gc_traversal               | 3.90 ms                                                | 3.67 ms: 1.06x faster                                  |
| scimark_monte_carlo        | 71.8 ms                                                | 67.5 ms: 1.06x faster                                  |
| async_tree_io_tg           | 1.30 sec                                               | 1.24 sec: 1.05x faster                                 |
| async_tree_cpu_io_mixed    | 750 ms                                                 | 711 ms: 1.05x faster                                   |
| regex_compile              | 141 ms                                                 | 134 ms: 1.05x faster                                   |
| deepcopy                   | 360 us                                                 | 344 us: 1.05x faster                                   |
| async_tree_memoization_tg  | 627 ms                                                 | 600 ms: 1.05x faster                                   |
| xml_etree_iterparse        | 109 ms                                                 | 105 ms: 1.04x faster                                   |
| docutils                   | 2.69 sec                                               | 2.59 sec: 1.04x faster                                 |
| sqlglot_optimize           | 55.2 ms                                                | 53.1 ms: 1.04x faster                                  |
| fannkuch                   | 410 ms                                                 | 396 ms: 1.04x faster                                   |
| logging_silent             | 108 ns                                                 | 105 ns: 1.04x faster                                   |
| pprint_pformat             | 1.53 sec                                               | 1.48 sec: 1.03x faster                                 |
| deepcopy_memo              | 38.9 us                                                | 37.6 us: 1.03x faster                                  |
| unpack_sequence            | 43.3 ns                                                | 41.9 ns: 1.03x faster                                  |
| async_tree_cpu_io_mixed_tg | 764 ms                                                 | 743 ms: 1.03x faster                                   |
| go                         | 143 ms                                                 | 139 ms: 1.03x faster                                   |
| tornado_http               | 97.7 ms                                                | 95.2 ms: 1.03x faster                                  |
| xml_etree_parse            | 163 ms                                                 | 159 ms: 1.03x faster                                   |
| pprint_safe_repr           | 743 ms                                                 | 724 ms: 1.03x faster                                   |
| json                       | 5.24 ms                                                | 5.12 ms: 1.02x faster                                  |
| deepcopy_reduce            | 3.14 us                                                | 3.08 us: 1.02x faster                                  |
| create_gc_cycles           | 1.48 ms                                                | 1.45 ms: 1.02x faster                                  |
| meteor_contest             | 109 ms                                                 | 107 ms: 1.02x faster                                   |
| 2to3                       | 266 ms                                                 | 262 ms: 1.01x faster                                   |
| nbody                      | 91.6 ms                                                | 90.5 ms: 1.01x faster                                  |
| richards                   | 48.9 ms                                                | 48.4 ms: 1.01x faster                                  |
| bench_thread_pool          | 833 us                                                 | 826 us: 1.01x faster                                   |
| asyncio_websockets         | 556 ms                                                 | 551 ms: 1.01x faster                                   |
| unpickle_list              | 5.22 us                                                | 5.19 us: 1.01x faster                                  |
| dulwich_log                | 64.9 ms                                                | 65.6 ms: 1.01x slower                                  |
| scimark_lu                 | 112 ms                                                 | 114 ms: 1.01x slower                                   |
| regex_effbot               | 3.45 ms                                                | 3.53 ms: 1.02x slower                                  |
| pathlib                    | 18.5 ms                                                | 18.9 ms: 1.02x slower                                  |
| mako                       | 10.8 ms                                                | 11.1 ms: 1.02x slower                                  |
| scimark_sparse_mat_mult    | 4.80 ms                                                | 4.92 ms: 1.02x slower                                  |
| pidigits                   | 190 ms                                                 | 195 ms: 1.02x slower                                   |
| float                      | 78.9 ms                                                | 81.5 ms: 1.03x slower                                  |
| pickle_dict                | 34.8 us                                                | 36.1 us: 1.04x slower                                  |
| pickle                     | 11.1 us                                                | 11.5 us: 1.04x slower                                  |
| xml_etree_process          | 56.5 ms                                                | 59.1 ms: 1.05x slower                                  |
| scimark_fft                | 342 ms                                                 | 361 ms: 1.05x slower                                   |
| pyflate                    | 426 ms                                                 | 451 ms: 1.06x slower                                   |
| regex_v8                   | 22.9 ms                                                | 24.3 ms: 1.06x slower                                  |
| xml_etree_generate         | 80.4 ms                                                | 86.6 ms: 1.08x slower                                  |
| regex_dna                  | 204 ms                                                 | 222 ms: 1.09x slower                                   |
| sqlite_synth               | 2.58 us                                                | 2.82 us: 1.09x slower                                  |
| unpickle                   | 13.9 us                                                | 15.3 us: 1.10x slower                                  |
| pickle_list                | 4.65 us                                                | 5.24 us: 1.13x slower                                  |
| coverage                   | 81.2 ms                                                | 95.7 ms: 1.18x slower                                  |
| python_startup             | 8.69 ms                                                | 10.3 ms: 1.19x slower                                  |
| async_generators           | 375 ms                                                 | 447 ms: 1.19x slower                                   |
| telco                      | 6.72 ms                                                | 8.31 ms: 1.24x slower                                  |
| python_startup_no_site     | 6.09 ms                                                | 8.97 ms: 1.47x slower                                  |
| Geometric mean             | (ref)                                                  | 1.07x faster                                           |

Benchmark hidden because not significant (5): chameleon, scimark_sor, spectral_norm, bench_mp_pool, pycparser
Ignored benchmarks (13) of results/bm-20221024-3.11.0-deaf509/bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.02x
- 95% likely to have a speedup of 1.02x
- 99% likely to have a speedup of 1.01x
