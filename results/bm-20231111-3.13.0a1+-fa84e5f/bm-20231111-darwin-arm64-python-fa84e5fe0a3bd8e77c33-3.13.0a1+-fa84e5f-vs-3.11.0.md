
# Results vs. 3.11.0

- fork: python
- ref: fa84e5fe0a3bd8e77c33
- machine: darwin-arm64
- commit hash: fa84e5f
- commit date: 2023-11-11
- overall geometric mean: 1.01x slower \*
- HPT reliability: 99.05%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231111-darwin-arm64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| 2to3           | 155 ms                                                 | 171 ms: 1.10x slower                                                   |
| chameleon      | 4.17 ms                                                | 4.66 ms: 1.12x slower                                                  |
| docutils       | 1.46 sec                                               | 1.48 sec: 1.02x slower                                                 |
| Geometric mean | (ref)                                                  | 1.05x slower                                                           |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231111-darwin-arm64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f |
|----------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| async_tree_none            | 282 ms                                                 | 253 ms: 1.12x faster                                                   |
| async_tree_memoization     | 361 ms                                                 | 330 ms: 1.09x faster                                                   |
| async_tree_memoization_tg  | 357 ms                                                 | 333 ms: 1.07x faster                                                   |
| async_tree_io_tg           | 734 ms                                                 | 686 ms: 1.07x faster                                                   |
| async_tree_none_tg         | 280 ms                                                 | 267 ms: 1.05x faster                                                   |
| async_tree_cpu_io_mixed_tg | 554 ms                                                 | 545 ms: 1.02x faster                                                   |
| async_tree_io              | 705 ms                                                 | 702 ms: 1.00x faster                                                   |
| async_tree_cpu_io_mixed    | 522 ms                                                 | 526 ms: 1.01x slower                                                   |
| Geometric mean             | (ref)                                                  | 1.05x faster                                                           |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231111-darwin-arm64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| pidigits       | 281 ms                                                 | 282 ms: 1.00x slower                                                   |
| float          | 55.4 ms                                                | 57.0 ms: 1.03x slower                                                  |
| nbody          | 68.7 ms                                                | 77.4 ms: 1.13x slower                                                  |
| Geometric mean | (ref)                                                  | 1.05x slower                                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231111-darwin-arm64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| regex_dna      | 149 ms                                                 | 149 ms: 1.00x faster                                                   |
| regex_compile  | 73.9 ms                                                | 76.3 ms: 1.03x slower                                                  |
| regex_effbot   | 2.46 ms                                                | 2.56 ms: 1.04x slower                                                  |
| regex_v8       | 15.3 ms                                                | 16.9 ms: 1.10x slower                                                  |
| Geometric mean | (ref)                                                  | 1.04x slower                                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231111-darwin-arm64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f |
|----------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| json_dumps           | 7.58 ms                                                | 6.45 ms: 1.18x faster                                                  |
| pickle_pure_python   | 211 us                                                 | 197 us: 1.07x faster                                                   |
| unpickle_pure_python | 163 us                                                 | 156 us: 1.04x faster                                                   |
| pickle               | 7.22 us                                                | 7.37 us: 1.02x slower                                                  |
| xml_etree_parse      | 107 ms                                                 | 110 ms: 1.03x slower                                                   |
| pickle_dict          | 17.0 us                                                | 17.9 us: 1.05x slower                                                  |
| pickle_list          | 2.67 us                                                | 2.88 us: 1.08x slower                                                  |
| unpickle             | 8.32 us                                                | 9.14 us: 1.10x slower                                                  |
| xml_etree_iterparse  | 68.2 ms                                                | 75.9 ms: 1.11x slower                                                  |
| json_loads           | 15.8 us                                                | 17.6 us: 1.12x slower                                                  |
| unpickle_list        | 2.77 us                                                | 3.13 us: 1.13x slower                                                  |
| xml_etree_process    | 34.0 ms                                                | 39.7 ms: 1.17x slower                                                  |
| tomli_loads          | 1.30 sec                                               | 1.56 sec: 1.20x slower                                                 |
| xml_etree_generate   | 46.8 ms                                                | 57.7 ms: 1.23x slower                                                  |
| Geometric mean       | (ref)                                                  | 1.06x slower                                                           |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231111-darwin-arm64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f |
|------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| python_startup         | 11.4 ms                                                | 11.8 ms: 1.04x slower                                                  |
| python_startup_no_site | 9.15 ms                                                | 10.5 ms: 1.15x slower                                                  |
| Geometric mean         | (ref)                                                  | 1.09x slower                                                           |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231111-darwin-arm64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f |
|-----------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| mako      | 8.22 ms                                                | 7.49 ms: 1.10x faster                                                  |

All benchmarks:
===============

| Benchmark                  | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231111-darwin-arm64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f |
|----------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| typing_runtime_protocols   | 323 us                                                 | 75.2 us: 4.29x faster                                                  |
| asyncio_tcp                | 650 ms                                                 | 451 ms: 1.44x faster                                                   |
| comprehensions             | 14.7 us                                                | 11.7 us: 1.25x faster                                                  |
| unpack_sequence            | 32.3 ns                                                | 26.5 ns: 1.22x faster                                                  |
| deepcopy_memo              | 28.9 us                                                | 24.4 us: 1.19x faster                                                  |
| generators                 | 29.2 ms                                                | 24.8 ms: 1.18x faster                                                  |
| json_dumps                 | 7.58 ms                                                | 6.45 ms: 1.18x faster                                                  |
| chaos                      | 48.2 ms                                                | 41.5 ms: 1.16x faster                                                  |
| async_tree_none            | 282 ms                                                 | 253 ms: 1.12x faster                                                   |
| raytrace                   | 200 ms                                                 | 180 ms: 1.11x faster                                                   |
| deltablue                  | 2.70 ms                                                | 2.42 ms: 1.11x faster                                                  |
| asyncio_tcp_ssl            | 1.44 sec                                               | 1.29 sec: 1.11x faster                                                 |
| sympy_sum                  | 81.6 ms                                                | 73.8 ms: 1.11x faster                                                  |
| mako                       | 8.22 ms                                                | 7.49 ms: 1.10x faster                                                  |
| async_tree_memoization     | 361 ms                                                 | 330 ms: 1.09x faster                                                   |
| async_tree_memoization_tg  | 357 ms                                                 | 333 ms: 1.07x faster                                                   |
| sqlglot_parse              | 886 us                                                 | 827 us: 1.07x faster                                                   |
| async_tree_io_tg           | 734 ms                                                 | 686 ms: 1.07x faster                                                   |
| pickle_pure_python         | 211 us                                                 | 197 us: 1.07x faster                                                   |
| mdp                        | 1.73 sec                                               | 1.63 sec: 1.07x faster                                                 |
| async_tree_none_tg         | 280 ms                                                 | 267 ms: 1.05x faster                                                   |
| deepcopy                   | 233 us                                                 | 222 us: 1.05x faster                                                   |
| unpickle_pure_python       | 163 us                                                 | 156 us: 1.04x faster                                                   |
| sqlglot_transpile          | 1.05 ms                                                | 1.01 ms: 1.04x faster                                                  |
| sympy_integrate            | 11.3 ms                                                | 10.9 ms: 1.04x faster                                                  |
| create_gc_cycles           | 715 us                                                 | 698 us: 1.02x faster                                                   |
| async_tree_cpu_io_mixed_tg | 554 ms                                                 | 545 ms: 1.02x faster                                                   |
| sympy_str                  | 144 ms                                                 | 143 ms: 1.01x faster                                                   |
| meteor_contest             | 74.9 ms                                                | 74.2 ms: 1.01x faster                                                  |
| deepcopy_reduce            | 1.98 us                                                | 1.96 us: 1.01x faster                                                  |
| crypto_pyaes               | 48.1 ms                                                | 47.8 ms: 1.01x faster                                                  |
| async_tree_io              | 705 ms                                                 | 702 ms: 1.00x faster                                                   |
| regex_dna                  | 149 ms                                                 | 149 ms: 1.00x faster                                                   |
| asyncio_websockets         | 544 ms                                                 | 545 ms: 1.00x slower                                                   |
| gc_traversal               | 2.39 ms                                                | 2.40 ms: 1.00x slower                                                  |
| pidigits                   | 281 ms                                                 | 282 ms: 1.00x slower                                                   |
| scimark_monte_carlo        | 47.1 ms                                                | 47.3 ms: 1.00x slower                                                  |
| async_tree_cpu_io_mixed    | 522 ms                                                 | 526 ms: 1.01x slower                                                   |
| dulwich_log                | 29.9 ms                                                | 30.1 ms: 1.01x slower                                                  |
| docutils                   | 1.46 sec                                               | 1.48 sec: 1.02x slower                                                 |
| pickle                     | 7.22 us                                                | 7.37 us: 1.02x slower                                                  |
| logging_format             | 3.69 us                                                | 3.77 us: 1.02x slower                                                  |
| logging_simple             | 3.41 us                                                | 3.49 us: 1.02x slower                                                  |
| go                         | 102 ms                                                 | 105 ms: 1.02x slower                                                   |
| xml_etree_parse            | 107 ms                                                 | 110 ms: 1.03x slower                                                   |
| float                      | 55.4 ms                                                | 57.0 ms: 1.03x slower                                                  |
| regex_compile              | 73.9 ms                                                | 76.3 ms: 1.03x slower                                                  |
| scimark_sparse_mat_mult    | 3.01 ms                                                | 3.11 ms: 1.03x slower                                                  |
| hexiom                     | 4.55 ms                                                | 4.71 ms: 1.03x slower                                                  |
| pprint_pformat             | 989 ms                                                 | 1.03 sec: 1.04x slower                                                 |
| pathlib                    | 28.5 ms                                                | 29.7 ms: 1.04x slower                                                  |
| spectral_norm              | 69.7 ms                                                | 72.6 ms: 1.04x slower                                                  |
| python_startup             | 11.4 ms                                                | 11.8 ms: 1.04x slower                                                  |
| regex_effbot               | 2.46 ms                                                | 2.56 ms: 1.04x slower                                                  |
| pycparser                  | 667 ms                                                 | 696 ms: 1.04x slower                                                   |
| sympy_expand               | 234 ms                                                 | 245 ms: 1.05x slower                                                   |
| pickle_dict                | 17.0 us                                                | 17.9 us: 1.05x slower                                                  |
| bench_mp_pool              | 41.9 ms                                                | 44.0 ms: 1.05x slower                                                  |
| pprint_safe_repr           | 479 ms                                                 | 505 ms: 1.05x slower                                                   |
| bench_thread_pool          | 461 us                                                 | 490 us: 1.06x slower                                                   |
| scimark_lu                 | 67.8 ms                                                | 72.2 ms: 1.07x slower                                                  |
| nqueens                    | 54.6 ms                                                | 58.3 ms: 1.07x slower                                                  |
| json                       | 2.77 ms                                                | 2.98 ms: 1.08x slower                                                  |
| pickle_list                | 2.67 us                                                | 2.88 us: 1.08x slower                                                  |
| scimark_fft                | 187 ms                                                 | 204 ms: 1.09x slower                                                   |
| logging_silent             | 64.5 ns                                                | 70.2 ns: 1.09x slower                                                  |
| richards                   | 30.8 ms                                                | 33.6 ms: 1.09x slower                                                  |
| unpickle                   | 8.32 us                                                | 9.14 us: 1.10x slower                                                  |
| regex_v8                   | 15.3 ms                                                | 16.9 ms: 1.10x slower                                                  |
| 2to3                       | 155 ms                                                 | 171 ms: 1.10x slower                                                   |
| coroutines                 | 16.6 ms                                                | 18.3 ms: 1.11x slower                                                  |
| xml_etree_iterparse        | 68.2 ms                                                | 75.9 ms: 1.11x slower                                                  |
| json_loads                 | 15.8 us                                                | 17.6 us: 1.12x slower                                                  |
| chameleon                  | 4.17 ms                                                | 4.66 ms: 1.12x slower                                                  |
| nbody                      | 68.7 ms                                                | 77.4 ms: 1.13x slower                                                  |
| unpickle_list              | 2.77 us                                                | 3.13 us: 1.13x slower                                                  |
| python_startup_no_site     | 9.15 ms                                                | 10.5 ms: 1.15x slower                                                  |
| pyflate                    | 297 ms                                                 | 341 ms: 1.15x slower                                                   |
| sqlglot_normalize          | 160 ms                                                 | 184 ms: 1.15x slower                                                   |
| sqlglot_optimize           | 29.6 ms                                                | 34.3 ms: 1.16x slower                                                  |
| xml_etree_process          | 34.0 ms                                                | 39.7 ms: 1.17x slower                                                  |
| fannkuch                   | 247 ms                                                 | 289 ms: 1.17x slower                                                   |
| coverage                   | 41.4 ms                                                | 48.4 ms: 1.17x slower                                                  |
| tomli_loads                | 1.30 sec                                               | 1.56 sec: 1.20x slower                                                 |
| sqlite_synth               | 1.35 us                                                | 1.62 us: 1.20x slower                                                  |
| xml_etree_generate         | 46.8 ms                                                | 57.7 ms: 1.23x slower                                                  |
| mypy2                      | 191 ms                                                 | 260 ms: 1.37x slower                                                   |
| scimark_sor                | 75.2 ms                                                | 105 ms: 1.40x slower                                                   |
| telco                      | 3.17 ms                                                | 4.69 ms: 1.48x slower                                                  |
| async_generators           | 192 ms                                                 | 300 ms: 1.56x slower                                                   |
| Geometric mean             | (ref)                                                  | 1.01x slower                                                           |

Benchmark hidden because not significant (2): tornado_http, richards_super
Ignored benchmarks (12) of results/bm-20221024-3.11.0-deaf509/bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, dask, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift


# HPT report

- Reliability score: 99.05% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
