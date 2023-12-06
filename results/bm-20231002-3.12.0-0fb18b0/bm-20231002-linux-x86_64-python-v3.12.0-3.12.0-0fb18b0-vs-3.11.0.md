
# Results vs. 3.11.0

- fork: python
- ref: v3.12.0
- machine: linux-x86_64
- commit hash: 0fb18b0
- commit date: 2023-10-02
- overall geometric mean: 1.03x faster
- HPT reliability: 55.85%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| 2to3           | 266 ms                                                 | 274 ms: 1.03x slower                                   |
| chameleon      | 6.86 ms                                                | 7.41 ms: 1.08x slower                                  |
| docutils       | 2.69 sec                                               | 2.75 sec: 1.02x slower                                 |
| tornado_http   | 97.7 ms                                                | 101 ms: 1.03x slower                                   |
| Geometric mean | (ref)                                                  | 1.04x slower                                           |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 |
|----------------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| async_tree_io              | 1.31 sec                                               | 1.16 sec: 1.12x faster                                 |
| async_tree_none            | 532 ms                                                 | 475 ms: 1.12x faster                                   |
| async_tree_memoization     | 640 ms                                                 | 580 ms: 1.10x faster                                   |
| async_tree_io_tg           | 1.30 sec                                               | 1.19 sec: 1.10x faster                                 |
| async_tree_none_tg         | 490 ms                                                 | 447 ms: 1.09x faster                                   |
| async_tree_memoization_tg  | 627 ms                                                 | 574 ms: 1.09x faster                                   |
| async_tree_cpu_io_mixed_tg | 764 ms                                                 | 725 ms: 1.05x faster                                   |
| async_tree_cpu_io_mixed    | 750 ms                                                 | 724 ms: 1.04x faster                                   |
| Geometric mean             | (ref)                                                  | 1.09x faster                                           |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| pidigits       | 190 ms                                                 | 187 ms: 1.02x faster                                   |
| nbody          | 91.6 ms                                                | 92.2 ms: 1.01x slower                                  |
| float          | 78.9 ms                                                | 83.3 ms: 1.06x slower                                  |
| Geometric mean | (ref)                                                  | 1.01x slower                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| regex_v8       | 22.9 ms                                                | 22.7 ms: 1.01x faster                                  |
| regex_dna      | 204 ms                                                 | 209 ms: 1.02x slower                                   |
| regex_effbot   | 3.45 ms                                                | 3.57 ms: 1.04x slower                                  |
| regex_compile  | 141 ms                                                 | 148 ms: 1.05x slower                                   |
| Geometric mean | (ref)                                                  | 1.02x slower                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 |
|----------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| json_dumps           | 13.5 ms                                                | 10.6 ms: 1.27x faster                                  |
| unpickle_pure_python | 241 us                                                 | 230 us: 1.05x faster                                   |
| pickle_dict          | 34.8 us                                                | 33.5 us: 1.04x faster                                  |
| json_loads           | 29.4 us                                                | 28.4 us: 1.04x faster                                  |
| unpickle_list        | 5.22 us                                                | 5.04 us: 1.03x faster                                  |
| xml_etree_iterparse  | 109 ms                                                 | 106 ms: 1.03x faster                                   |
| xml_etree_parse      | 163 ms                                                 | 159 ms: 1.02x faster                                   |
| tomli_loads          | 2.31 sec                                               | 2.30 sec: 1.01x faster                                 |
| pickle_list          | 4.65 us                                                | 4.67 us: 1.01x slower                                  |
| pickle               | 11.1 us                                                | 11.2 us: 1.01x slower                                  |
| pickle_pure_python   | 319 us                                                 | 326 us: 1.02x slower                                   |
| xml_etree_process    | 56.5 ms                                                | 61.2 ms: 1.08x slower                                  |
| xml_etree_generate   | 80.4 ms                                                | 88.7 ms: 1.10x slower                                  |
| unpickle             | 13.9 us                                                | 15.8 us: 1.14x slower                                  |
| Geometric mean       | (ref)                                                  | 1.01x faster                                           |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 |
|------------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| python_startup         | 8.69 ms                                                | 9.53 ms: 1.10x slower                                  |
| python_startup_no_site | 6.09 ms                                                | 6.92 ms: 1.14x slower                                  |
| Geometric mean         | (ref)                                                  | 1.12x slower                                           |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 |
|-----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| django_template | 33.8 ms                                                | 35.0 ms: 1.04x slower                                  |
| mako            | 10.8 ms                                                | 11.5 ms: 1.06x slower                                  |
| Geometric mean  | (ref)                                                  | 1.05x slower                                           |

All benchmarks:
===============

| Benchmark                  | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 |
|----------------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| typing_runtime_protocols   | 521 us                                                 | 153 us: 3.40x faster                                   |
| generators                 | 76.5 ms                                                | 32.5 ms: 2.36x faster                                  |
| asyncio_tcp_ssl            | 3.13 sec                                               | 1.78 sec: 1.76x faster                                 |
| asyncio_tcp                | 887 ms                                                 | 506 ms: 1.75x faster                                   |
| json_dumps                 | 13.5 ms                                                | 10.6 ms: 1.27x faster                                  |
| mypy2                      | 427 ms                                                 | 351 ms: 1.22x faster                                   |
| richards_super             | 61.2 ms                                                | 51.9 ms: 1.18x faster                                  |
| comprehensions             | 23.6 us                                                | 20.9 us: 1.13x faster                                  |
| async_tree_io              | 1.31 sec                                               | 1.16 sec: 1.12x faster                                 |
| async_tree_none            | 532 ms                                                 | 475 ms: 1.12x faster                                   |
| coroutines                 | 26.1 ms                                                | 23.5 ms: 1.11x faster                                  |
| async_tree_memoization     | 640 ms                                                 | 580 ms: 1.10x faster                                   |
| async_tree_io_tg           | 1.30 sec                                               | 1.19 sec: 1.10x faster                                 |
| async_tree_none_tg         | 490 ms                                                 | 447 ms: 1.09x faster                                   |
| async_tree_memoization_tg  | 627 ms                                                 | 574 ms: 1.09x faster                                   |
| mdp                        | 2.79 sec                                               | 2.57 sec: 1.09x faster                                 |
| coverage                   | 81.2 ms                                                | 75.1 ms: 1.08x faster                                  |
| sqlglot_parse              | 1.43 ms                                                | 1.35 ms: 1.06x faster                                  |
| richards                   | 48.9 ms                                                | 46.0 ms: 1.06x faster                                  |
| chaos                      | 71.4 ms                                                | 67.5 ms: 1.06x faster                                  |
| async_tree_cpu_io_mixed_tg | 764 ms                                                 | 725 ms: 1.05x faster                                   |
| unpickle_pure_python       | 241 us                                                 | 230 us: 1.05x faster                                   |
| sqlglot_transpile          | 1.75 ms                                                | 1.68 ms: 1.05x faster                                  |
| pickle_dict                | 34.8 us                                                | 33.5 us: 1.04x faster                                  |
| json_loads                 | 29.4 us                                                | 28.4 us: 1.04x faster                                  |
| async_tree_cpu_io_mixed    | 750 ms                                                 | 724 ms: 1.04x faster                                   |
| unpickle_list              | 5.22 us                                                | 5.04 us: 1.03x faster                                  |
| sympy_expand               | 490 ms                                                 | 476 ms: 1.03x faster                                   |
| hexiom                     | 6.74 ms                                                | 6.54 ms: 1.03x faster                                  |
| xml_etree_iterparse        | 109 ms                                                 | 106 ms: 1.03x faster                                   |
| deltablue                  | 3.80 ms                                                | 3.71 ms: 1.03x faster                                  |
| pycparser                  | 1.20 sec                                               | 1.17 sec: 1.02x faster                                 |
| xml_etree_parse            | 163 ms                                                 | 159 ms: 1.02x faster                                   |
| go                         | 143 ms                                                 | 140 ms: 1.02x faster                                   |
| sympy_sum                  | 170 ms                                                 | 167 ms: 1.02x faster                                   |
| create_gc_cycles           | 1.48 ms                                                | 1.45 ms: 1.02x faster                                  |
| pidigits                   | 190 ms                                                 | 187 ms: 1.02x faster                                   |
| regex_v8                   | 22.9 ms                                                | 22.7 ms: 1.01x faster                                  |
| sympy_str                  | 299 ms                                                 | 296 ms: 1.01x faster                                   |
| logging_silent             | 108 ns                                                 | 108 ns: 1.01x faster                                   |
| nqueens                    | 86.8 ms                                                | 86.2 ms: 1.01x faster                                  |
| tomli_loads                | 2.31 sec                                               | 2.30 sec: 1.01x faster                                 |
| sympy_integrate            | 21.4 ms                                                | 21.2 ms: 1.01x faster                                  |
| sqlglot_normalize          | 112 ms                                                 | 112 ms: 1.01x faster                                   |
| sqlglot_optimize           | 55.2 ms                                                | 54.8 ms: 1.01x faster                                  |
| asyncio_websockets         | 556 ms                                                 | 552 ms: 1.01x faster                                   |
| raytrace                   | 306 ms                                                 | 308 ms: 1.00x slower                                   |
| pickle_list                | 4.65 us                                                | 4.67 us: 1.01x slower                                  |
| deepcopy                   | 360 us                                                 | 363 us: 1.01x slower                                   |
| nbody                      | 91.6 ms                                                | 92.2 ms: 1.01x slower                                  |
| meteor_contest             | 109 ms                                                 | 110 ms: 1.01x slower                                   |
| dask                       | 365 ms                                                 | 369 ms: 1.01x slower                                   |
| pickle                     | 11.1 us                                                | 11.2 us: 1.01x slower                                  |
| bench_thread_pool          | 833 us                                                 | 845 us: 1.01x slower                                   |
| pprint_pformat             | 1.53 sec                                               | 1.55 sec: 1.02x slower                                 |
| sqlalchemy_imperative      | 18.2 ms                                                | 18.5 ms: 1.02x slower                                  |
| deepcopy_memo              | 38.9 us                                                | 39.7 us: 1.02x slower                                  |
| regex_dna                  | 204 ms                                                 | 209 ms: 1.02x slower                                   |
| logging_simple             | 6.24 us                                                | 6.38 us: 1.02x slower                                  |
| pickle_pure_python         | 319 us                                                 | 326 us: 1.02x slower                                   |
| pathlib                    | 18.5 ms                                                | 18.9 ms: 1.02x slower                                  |
| docutils                   | 2.69 sec                                               | 2.75 sec: 1.02x slower                                 |
| deepcopy_reduce            | 3.14 us                                                | 3.23 us: 1.03x slower                                  |
| pprint_safe_repr           | 743 ms                                                 | 765 ms: 1.03x slower                                   |
| tornado_http               | 97.7 ms                                                | 101 ms: 1.03x slower                                   |
| 2to3                       | 266 ms                                                 | 274 ms: 1.03x slower                                   |
| aiohttp                    | 1.12 ms                                                | 1.15 ms: 1.03x slower                                  |
| regex_effbot               | 3.45 ms                                                | 3.57 ms: 1.04x slower                                  |
| django_template            | 33.8 ms                                                | 35.0 ms: 1.04x slower                                  |
| gunicorn                   | 1.20 ms                                                | 1.24 ms: 1.04x slower                                  |
| logging_format             | 6.83 us                                                | 7.10 us: 1.04x slower                                  |
| scimark_monte_carlo        | 71.8 ms                                                | 74.6 ms: 1.04x slower                                  |
| sqlalchemy_declarative     | 141 ms                                                 | 147 ms: 1.04x slower                                   |
| regex_compile              | 141 ms                                                 | 148 ms: 1.05x slower                                   |
| float                      | 78.9 ms                                                | 83.3 ms: 1.06x slower                                  |
| dulwich_log                | 64.9 ms                                                | 68.7 ms: 1.06x slower                                  |
| mako                       | 10.8 ms                                                | 11.5 ms: 1.06x slower                                  |
| scimark_sor                | 121 ms                                                 | 129 ms: 1.06x slower                                   |
| telco                      | 6.72 ms                                                | 7.18 ms: 1.07x slower                                  |
| scimark_lu                 | 112 ms                                                 | 120 ms: 1.07x slower                                   |
| crypto_pyaes               | 77.5 ms                                                | 83.6 ms: 1.08x slower                                  |
| chameleon                  | 6.86 ms                                                | 7.41 ms: 1.08x slower                                  |
| xml_etree_process          | 56.5 ms                                                | 61.2 ms: 1.08x slower                                  |
| spectral_norm              | 105 ms                                                 | 115 ms: 1.09x slower                                   |
| gc_traversal               | 3.90 ms                                                | 4.28 ms: 1.10x slower                                  |
| python_startup             | 8.69 ms                                                | 9.53 ms: 1.10x slower                                  |
| sqlite_synth               | 2.58 us                                                | 2.83 us: 1.10x slower                                  |
| xml_etree_generate         | 80.4 ms                                                | 88.7 ms: 1.10x slower                                  |
| pyflate                    | 426 ms                                                 | 471 ms: 1.11x slower                                   |
| scimark_sparse_mat_mult    | 4.80 ms                                                | 5.33 ms: 1.11x slower                                  |
| scimark_fft                | 342 ms                                                 | 381 ms: 1.11x slower                                   |
| python_startup_no_site     | 6.09 ms                                                | 6.92 ms: 1.14x slower                                  |
| unpickle                   | 13.9 us                                                | 15.8 us: 1.14x slower                                  |
| async_generators           | 375 ms                                                 | 459 ms: 1.22x slower                                   |
| unpack_sequence            | 43.3 ns                                                | 54.2 ns: 1.25x slower                                  |
| Geometric mean             | (ref)                                                  | 1.03x faster                                           |

Benchmark hidden because not significant (3): json, bench_mp_pool, fannkuch
Ignored benchmarks (7) of results/bm-20221024-3.11.0-deaf509/bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509.json: djangocms, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, thrift


# HPT report

- Reliability score: 55.85% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
