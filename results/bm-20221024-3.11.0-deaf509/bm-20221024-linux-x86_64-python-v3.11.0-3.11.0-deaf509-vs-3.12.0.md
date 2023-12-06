
# Results vs. 3.12.0

- fork: python
- ref: v3.11.0
- machine: linux-x86_64
- commit hash: deaf509
- commit date: 2022-10-24
- overall geometric mean: 1.03x slower
- HPT reliability: 55.85%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| 2to3           | 274 ms                                                 | 266 ms: 1.03x faster                                   |
| chameleon      | 7.41 ms                                                | 6.86 ms: 1.08x faster                                  |
| docutils       | 2.75 sec                                               | 2.69 sec: 1.02x faster                                 |
| tornado_http   | 101 ms                                                 | 97.7 ms: 1.03x faster                                  |
| Geometric mean | (ref)                                                  | 1.04x faster                                           |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 |
|----------------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| async_tree_cpu_io_mixed    | 724 ms                                                 | 750 ms: 1.04x slower                                   |
| async_tree_cpu_io_mixed_tg | 725 ms                                                 | 764 ms: 1.05x slower                                   |
| async_tree_memoization_tg  | 574 ms                                                 | 627 ms: 1.09x slower                                   |
| async_tree_none_tg         | 447 ms                                                 | 490 ms: 1.09x slower                                   |
| async_tree_io_tg           | 1.19 sec                                               | 1.30 sec: 1.10x slower                                 |
| async_tree_memoization     | 580 ms                                                 | 640 ms: 1.10x slower                                   |
| async_tree_none            | 475 ms                                                 | 532 ms: 1.12x slower                                   |
| async_tree_io              | 1.16 sec                                               | 1.31 sec: 1.12x slower                                 |
| Geometric mean             | (ref)                                                  | 1.09x slower                                           |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| float          | 83.3 ms                                                | 78.9 ms: 1.06x faster                                  |
| nbody          | 92.2 ms                                                | 91.6 ms: 1.01x faster                                  |
| pidigits       | 187 ms                                                 | 190 ms: 1.02x slower                                   |
| Geometric mean | (ref)                                                  | 1.01x faster                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| regex_compile  | 148 ms                                                 | 141 ms: 1.05x faster                                   |
| regex_effbot   | 3.57 ms                                                | 3.45 ms: 1.04x faster                                  |
| regex_dna      | 209 ms                                                 | 204 ms: 1.02x faster                                   |
| regex_v8       | 22.7 ms                                                | 22.9 ms: 1.01x slower                                  |
| Geometric mean | (ref)                                                  | 1.02x faster                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 |
|----------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| unpickle             | 15.8 us                                                | 13.9 us: 1.14x faster                                  |
| xml_etree_generate   | 88.7 ms                                                | 80.4 ms: 1.10x faster                                  |
| xml_etree_process    | 61.2 ms                                                | 56.5 ms: 1.08x faster                                  |
| pickle_pure_python   | 326 us                                                 | 319 us: 1.02x faster                                   |
| pickle               | 11.2 us                                                | 11.1 us: 1.01x faster                                  |
| pickle_list          | 4.67 us                                                | 4.65 us: 1.01x faster                                  |
| tomli_loads          | 2.30 sec                                               | 2.31 sec: 1.01x slower                                 |
| xml_etree_parse      | 159 ms                                                 | 163 ms: 1.02x slower                                   |
| xml_etree_iterparse  | 106 ms                                                 | 109 ms: 1.03x slower                                   |
| unpickle_list        | 5.04 us                                                | 5.22 us: 1.03x slower                                  |
| json_loads           | 28.4 us                                                | 29.4 us: 1.04x slower                                  |
| pickle_dict          | 33.5 us                                                | 34.8 us: 1.04x slower                                  |
| unpickle_pure_python | 230 us                                                 | 241 us: 1.05x slower                                   |
| json_dumps           | 10.6 ms                                                | 13.5 ms: 1.27x slower                                  |
| Geometric mean       | (ref)                                                  | 1.01x slower                                           |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 |
|------------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| python_startup_no_site | 6.92 ms                                                | 6.09 ms: 1.14x faster                                  |
| python_startup         | 9.53 ms                                                | 8.69 ms: 1.10x faster                                  |
| Geometric mean         | (ref)                                                  | 1.12x faster                                           |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 |
|-----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| mako            | 11.5 ms                                                | 10.8 ms: 1.06x faster                                  |
| django_template | 35.0 ms                                                | 33.8 ms: 1.04x faster                                  |
| Geometric mean  | (ref)                                                  | 1.05x faster                                           |

All benchmarks:
===============

| Benchmark                  | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 |
|----------------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| unpack_sequence            | 54.2 ns                                                | 43.3 ns: 1.25x faster                                  |
| async_generators           | 459 ms                                                 | 375 ms: 1.22x faster                                   |
| unpickle                   | 15.8 us                                                | 13.9 us: 1.14x faster                                  |
| python_startup_no_site     | 6.92 ms                                                | 6.09 ms: 1.14x faster                                  |
| scimark_fft                | 381 ms                                                 | 342 ms: 1.11x faster                                   |
| scimark_sparse_mat_mult    | 5.33 ms                                                | 4.80 ms: 1.11x faster                                  |
| pyflate                    | 471 ms                                                 | 426 ms: 1.11x faster                                   |
| xml_etree_generate         | 88.7 ms                                                | 80.4 ms: 1.10x faster                                  |
| sqlite_synth               | 2.83 us                                                | 2.58 us: 1.10x faster                                  |
| python_startup             | 9.53 ms                                                | 8.69 ms: 1.10x faster                                  |
| gc_traversal               | 4.28 ms                                                | 3.90 ms: 1.10x faster                                  |
| spectral_norm              | 115 ms                                                 | 105 ms: 1.09x faster                                   |
| xml_etree_process          | 61.2 ms                                                | 56.5 ms: 1.08x faster                                  |
| chameleon                  | 7.41 ms                                                | 6.86 ms: 1.08x faster                                  |
| crypto_pyaes               | 83.6 ms                                                | 77.5 ms: 1.08x faster                                  |
| scimark_lu                 | 120 ms                                                 | 112 ms: 1.07x faster                                   |
| telco                      | 7.18 ms                                                | 6.72 ms: 1.07x faster                                  |
| scimark_sor                | 129 ms                                                 | 121 ms: 1.06x faster                                   |
| mako                       | 11.5 ms                                                | 10.8 ms: 1.06x faster                                  |
| dulwich_log                | 68.7 ms                                                | 64.9 ms: 1.06x faster                                  |
| float                      | 83.3 ms                                                | 78.9 ms: 1.06x faster                                  |
| regex_compile              | 148 ms                                                 | 141 ms: 1.05x faster                                   |
| sqlalchemy_declarative     | 147 ms                                                 | 141 ms: 1.04x faster                                   |
| scimark_monte_carlo        | 74.6 ms                                                | 71.8 ms: 1.04x faster                                  |
| logging_format             | 7.10 us                                                | 6.83 us: 1.04x faster                                  |
| gunicorn                   | 1.24 ms                                                | 1.20 ms: 1.04x faster                                  |
| django_template            | 35.0 ms                                                | 33.8 ms: 1.04x faster                                  |
| regex_effbot               | 3.57 ms                                                | 3.45 ms: 1.04x faster                                  |
| aiohttp                    | 1.15 ms                                                | 1.12 ms: 1.03x faster                                  |
| 2to3                       | 274 ms                                                 | 266 ms: 1.03x faster                                   |
| tornado_http               | 101 ms                                                 | 97.7 ms: 1.03x faster                                  |
| pprint_safe_repr           | 765 ms                                                 | 743 ms: 1.03x faster                                   |
| deepcopy_reduce            | 3.23 us                                                | 3.14 us: 1.03x faster                                  |
| docutils                   | 2.75 sec                                               | 2.69 sec: 1.02x faster                                 |
| pathlib                    | 18.9 ms                                                | 18.5 ms: 1.02x faster                                  |
| pickle_pure_python         | 326 us                                                 | 319 us: 1.02x faster                                   |
| logging_simple             | 6.38 us                                                | 6.24 us: 1.02x faster                                  |
| regex_dna                  | 209 ms                                                 | 204 ms: 1.02x faster                                   |
| deepcopy_memo              | 39.7 us                                                | 38.9 us: 1.02x faster                                  |
| sqlalchemy_imperative      | 18.5 ms                                                | 18.2 ms: 1.02x faster                                  |
| pprint_pformat             | 1.55 sec                                               | 1.53 sec: 1.02x faster                                 |
| bench_thread_pool          | 845 us                                                 | 833 us: 1.01x faster                                   |
| pickle                     | 11.2 us                                                | 11.1 us: 1.01x faster                                  |
| dask                       | 369 ms                                                 | 365 ms: 1.01x faster                                   |
| meteor_contest             | 110 ms                                                 | 109 ms: 1.01x faster                                   |
| nbody                      | 92.2 ms                                                | 91.6 ms: 1.01x faster                                  |
| deepcopy                   | 363 us                                                 | 360 us: 1.01x faster                                   |
| pickle_list                | 4.67 us                                                | 4.65 us: 1.01x faster                                  |
| raytrace                   | 308 ms                                                 | 306 ms: 1.00x faster                                   |
| asyncio_websockets         | 552 ms                                                 | 556 ms: 1.01x slower                                   |
| sqlglot_optimize           | 54.8 ms                                                | 55.2 ms: 1.01x slower                                  |
| sqlglot_normalize          | 112 ms                                                 | 112 ms: 1.01x slower                                   |
| sympy_integrate            | 21.2 ms                                                | 21.4 ms: 1.01x slower                                  |
| tomli_loads                | 2.30 sec                                               | 2.31 sec: 1.01x slower                                 |
| nqueens                    | 86.2 ms                                                | 86.8 ms: 1.01x slower                                  |
| logging_silent             | 108 ns                                                 | 108 ns: 1.01x slower                                   |
| sympy_str                  | 296 ms                                                 | 299 ms: 1.01x slower                                   |
| regex_v8                   | 22.7 ms                                                | 22.9 ms: 1.01x slower                                  |
| pidigits                   | 187 ms                                                 | 190 ms: 1.02x slower                                   |
| create_gc_cycles           | 1.45 ms                                                | 1.48 ms: 1.02x slower                                  |
| sympy_sum                  | 167 ms                                                 | 170 ms: 1.02x slower                                   |
| go                         | 140 ms                                                 | 143 ms: 1.02x slower                                   |
| xml_etree_parse            | 159 ms                                                 | 163 ms: 1.02x slower                                   |
| pycparser                  | 1.17 sec                                               | 1.20 sec: 1.02x slower                                 |
| deltablue                  | 3.71 ms                                                | 3.80 ms: 1.03x slower                                  |
| xml_etree_iterparse        | 106 ms                                                 | 109 ms: 1.03x slower                                   |
| hexiom                     | 6.54 ms                                                | 6.74 ms: 1.03x slower                                  |
| sympy_expand               | 476 ms                                                 | 490 ms: 1.03x slower                                   |
| unpickle_list              | 5.04 us                                                | 5.22 us: 1.03x slower                                  |
| async_tree_cpu_io_mixed    | 724 ms                                                 | 750 ms: 1.04x slower                                   |
| json_loads                 | 28.4 us                                                | 29.4 us: 1.04x slower                                  |
| pickle_dict                | 33.5 us                                                | 34.8 us: 1.04x slower                                  |
| sqlglot_transpile          | 1.68 ms                                                | 1.75 ms: 1.05x slower                                  |
| unpickle_pure_python       | 230 us                                                 | 241 us: 1.05x slower                                   |
| async_tree_cpu_io_mixed_tg | 725 ms                                                 | 764 ms: 1.05x slower                                   |
| chaos                      | 67.5 ms                                                | 71.4 ms: 1.06x slower                                  |
| richards                   | 46.0 ms                                                | 48.9 ms: 1.06x slower                                  |
| sqlglot_parse              | 1.35 ms                                                | 1.43 ms: 1.06x slower                                  |
| coverage                   | 75.1 ms                                                | 81.2 ms: 1.08x slower                                  |
| mdp                        | 2.57 sec                                               | 2.79 sec: 1.09x slower                                 |
| async_tree_memoization_tg  | 574 ms                                                 | 627 ms: 1.09x slower                                   |
| async_tree_none_tg         | 447 ms                                                 | 490 ms: 1.09x slower                                   |
| async_tree_io_tg           | 1.19 sec                                               | 1.30 sec: 1.10x slower                                 |
| async_tree_memoization     | 580 ms                                                 | 640 ms: 1.10x slower                                   |
| coroutines                 | 23.5 ms                                                | 26.1 ms: 1.11x slower                                  |
| async_tree_none            | 475 ms                                                 | 532 ms: 1.12x slower                                   |
| async_tree_io              | 1.16 sec                                               | 1.31 sec: 1.12x slower                                 |
| comprehensions             | 20.9 us                                                | 23.6 us: 1.13x slower                                  |
| richards_super             | 51.9 ms                                                | 61.2 ms: 1.18x slower                                  |
| mypy2                      | 351 ms                                                 | 427 ms: 1.22x slower                                   |
| json_dumps                 | 10.6 ms                                                | 13.5 ms: 1.27x slower                                  |
| asyncio_tcp                | 506 ms                                                 | 887 ms: 1.75x slower                                   |
| asyncio_tcp_ssl            | 1.78 sec                                               | 3.13 sec: 1.76x slower                                 |
| generators                 | 32.5 ms                                                | 76.5 ms: 2.36x slower                                  |
| typing_runtime_protocols   | 153 us                                                 | 521 us: 3.40x slower                                   |
| Geometric mean             | (ref)                                                  | 1.03x slower                                           |

Benchmark hidden because not significant (3): fannkuch, bench_mp_pool, json
Ignored benchmarks (7) of results/bm-20221024-3.11.0-deaf509/bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509.json: djangocms, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, thrift


# HPT report

- Reliability score: 55.85% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
