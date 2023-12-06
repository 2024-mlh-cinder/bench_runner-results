
# Results vs. 3.11.0

- fork: python
- ref: main
- machine: darwin-arm64
- commit hash: 853b4b5
- commit date: 2023-11-04
- overall geometric mean: 1.02x slower \*
- HPT reliability: 99.52%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231104-darwin-arm64-python-main-3.13.0a1+-853b4b5 |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| 2to3           | 155 ms                                                 | 174 ms: 1.12x slower                                   |
| chameleon      | 4.17 ms                                                | 4.68 ms: 1.12x slower                                  |
| docutils       | 1.46 sec                                               | 1.50 sec: 1.03x slower                                 |
| Geometric mean | (ref)                                                  | 1.06x slower                                           |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231104-darwin-arm64-python-main-3.13.0a1+-853b4b5 |
|----------------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| async_tree_none            | 282 ms                                                 | 257 ms: 1.10x faster                                   |
| async_tree_memoization     | 361 ms                                                 | 334 ms: 1.08x faster                                   |
| async_tree_io_tg           | 734 ms                                                 | 692 ms: 1.06x faster                                   |
| async_tree_memoization_tg  | 357 ms                                                 | 337 ms: 1.06x faster                                   |
| async_tree_none_tg         | 280 ms                                                 | 271 ms: 1.04x faster                                   |
| async_tree_cpu_io_mixed_tg | 554 ms                                                 | 547 ms: 1.01x faster                                   |
| async_tree_io              | 705 ms                                                 | 710 ms: 1.01x slower                                   |
| async_tree_cpu_io_mixed    | 522 ms                                                 | 530 ms: 1.01x slower                                   |
| Geometric mean             | (ref)                                                  | 1.04x faster                                           |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231104-darwin-arm64-python-main-3.13.0a1+-853b4b5 |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| pidigits       | 281 ms                                                 | 282 ms: 1.00x slower                                   |
| float          | 55.4 ms                                                | 57.7 ms: 1.04x slower                                  |
| nbody          | 68.7 ms                                                | 78.5 ms: 1.14x slower                                  |
| Geometric mean | (ref)                                                  | 1.06x slower                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231104-darwin-arm64-python-main-3.13.0a1+-853b4b5 |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| regex_dna      | 149 ms                                                 | 149 ms: 1.00x faster                                   |
| regex_compile  | 73.9 ms                                                | 76.2 ms: 1.03x slower                                  |
| regex_effbot   | 2.46 ms                                                | 2.56 ms: 1.04x slower                                  |
| regex_v8       | 15.3 ms                                                | 16.8 ms: 1.10x slower                                  |
| Geometric mean | (ref)                                                  | 1.04x slower                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231104-darwin-arm64-python-main-3.13.0a1+-853b4b5 |
|----------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| json_dumps           | 7.58 ms                                                | 6.60 ms: 1.15x faster                                  |
| pickle_pure_python   | 211 us                                                 | 199 us: 1.06x faster                                   |
| unpickle_pure_python | 163 us                                                 | 156 us: 1.04x faster                                   |
| pickle               | 7.22 us                                                | 7.38 us: 1.02x slower                                  |
| xml_etree_parse      | 107 ms                                                 | 110 ms: 1.03x slower                                   |
| pickle_dict          | 17.0 us                                                | 17.9 us: 1.05x slower                                  |
| pickle_list          | 2.67 us                                                | 2.92 us: 1.09x slower                                  |
| unpickle             | 8.32 us                                                | 9.15 us: 1.10x slower                                  |
| json_loads           | 15.8 us                                                | 17.5 us: 1.11x slower                                  |
| xml_etree_iterparse  | 68.2 ms                                                | 76.3 ms: 1.12x slower                                  |
| unpickle_list        | 2.77 us                                                | 3.11 us: 1.13x slower                                  |
| xml_etree_process    | 34.0 ms                                                | 39.8 ms: 1.17x slower                                  |
| tomli_loads          | 1.30 sec                                               | 1.56 sec: 1.20x slower                                 |
| xml_etree_generate   | 46.8 ms                                                | 57.8 ms: 1.23x slower                                  |
| Geometric mean       | (ref)                                                  | 1.07x slower                                           |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231104-darwin-arm64-python-main-3.13.0a1+-853b4b5 |
|------------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| python_startup         | 11.4 ms                                                | 13.0 ms: 1.15x slower                                  |
| python_startup_no_site | 9.15 ms                                                | 11.7 ms: 1.28x slower                                  |
| Geometric mean         | (ref)                                                  | 1.21x slower                                           |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231104-darwin-arm64-python-main-3.13.0a1+-853b4b5 |
|-----------|:------------------------------------------------------:|:------------------------------------------------------:|
| mako      | 8.22 ms                                                | 7.50 ms: 1.10x faster                                  |

All benchmarks:
===============

| Benchmark                  | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231104-darwin-arm64-python-main-3.13.0a1+-853b4b5 |
|----------------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| typing_runtime_protocols   | 323 us                                                 | 74.2 us: 4.35x faster                                  |
| asyncio_tcp                | 650 ms                                                 | 429 ms: 1.52x faster                                   |
| comprehensions             | 14.7 us                                                | 11.8 us: 1.24x faster                                  |
| unpack_sequence            | 32.3 ns                                                | 26.5 ns: 1.22x faster                                  |
| generators                 | 29.2 ms                                                | 24.4 ms: 1.20x faster                                  |
| deepcopy_memo              | 28.9 us                                                | 24.6 us: 1.17x faster                                  |
| chaos                      | 48.2 ms                                                | 41.5 ms: 1.16x faster                                  |
| json_dumps                 | 7.58 ms                                                | 6.60 ms: 1.15x faster                                  |
| raytrace                   | 200 ms                                                 | 180 ms: 1.11x faster                                   |
| asyncio_tcp_ssl            | 1.44 sec                                               | 1.29 sec: 1.11x faster                                 |
| deltablue                  | 2.70 ms                                                | 2.43 ms: 1.11x faster                                  |
| async_tree_none            | 282 ms                                                 | 257 ms: 1.10x faster                                   |
| sympy_sum                  | 81.6 ms                                                | 74.4 ms: 1.10x faster                                  |
| mako                       | 8.22 ms                                                | 7.50 ms: 1.10x faster                                  |
| async_tree_memoization     | 361 ms                                                 | 334 ms: 1.08x faster                                   |
| sqlglot_parse              | 886 us                                                 | 828 us: 1.07x faster                                   |
| mdp                        | 1.73 sec                                               | 1.62 sec: 1.07x faster                                 |
| async_tree_io_tg           | 734 ms                                                 | 692 ms: 1.06x faster                                   |
| async_tree_memoization_tg  | 357 ms                                                 | 337 ms: 1.06x faster                                   |
| pickle_pure_python         | 211 us                                                 | 199 us: 1.06x faster                                   |
| deepcopy                   | 233 us                                                 | 221 us: 1.06x faster                                   |
| unpickle_pure_python       | 163 us                                                 | 156 us: 1.04x faster                                   |
| sympy_integrate            | 11.3 ms                                                | 10.9 ms: 1.04x faster                                  |
| sqlglot_transpile          | 1.05 ms                                                | 1.01 ms: 1.04x faster                                  |
| async_tree_none_tg         | 280 ms                                                 | 271 ms: 1.04x faster                                   |
| create_gc_cycles           | 715 us                                                 | 701 us: 1.02x faster                                   |
| async_tree_cpu_io_mixed_tg | 554 ms                                                 | 547 ms: 1.01x faster                                   |
| crypto_pyaes               | 48.1 ms                                                | 48.0 ms: 1.00x faster                                  |
| deepcopy_reduce            | 1.98 us                                                | 1.97 us: 1.00x faster                                  |
| meteor_contest             | 74.9 ms                                                | 74.7 ms: 1.00x faster                                  |
| regex_dna                  | 149 ms                                                 | 149 ms: 1.00x faster                                   |
| asyncio_websockets         | 544 ms                                                 | 545 ms: 1.00x slower                                   |
| pidigits                   | 281 ms                                                 | 282 ms: 1.00x slower                                   |
| gc_traversal               | 2.39 ms                                                | 2.40 ms: 1.00x slower                                  |
| async_tree_io              | 705 ms                                                 | 710 ms: 1.01x slower                                   |
| scimark_monte_carlo        | 47.1 ms                                                | 47.4 ms: 1.01x slower                                  |
| dulwich_log                | 29.9 ms                                                | 30.2 ms: 1.01x slower                                  |
| async_tree_cpu_io_mixed    | 522 ms                                                 | 530 ms: 1.01x slower                                   |
| pickle                     | 7.22 us                                                | 7.38 us: 1.02x slower                                  |
| docutils                   | 1.46 sec                                               | 1.50 sec: 1.03x slower                                 |
| go                         | 102 ms                                                 | 105 ms: 1.03x slower                                   |
| regex_compile              | 73.9 ms                                                | 76.2 ms: 1.03x slower                                  |
| xml_etree_parse            | 107 ms                                                 | 110 ms: 1.03x slower                                   |
| scimark_sparse_mat_mult    | 3.01 ms                                                | 3.10 ms: 1.03x slower                                  |
| pathlib                    | 28.5 ms                                                | 29.5 ms: 1.03x slower                                  |
| hexiom                     | 4.55 ms                                                | 4.74 ms: 1.04x slower                                  |
| pprint_pformat             | 989 ms                                                 | 1.03 sec: 1.04x slower                                 |
| richards_super             | 36.8 ms                                                | 38.3 ms: 1.04x slower                                  |
| float                      | 55.4 ms                                                | 57.7 ms: 1.04x slower                                  |
| regex_effbot               | 2.46 ms                                                | 2.56 ms: 1.04x slower                                  |
| pycparser                  | 667 ms                                                 | 698 ms: 1.05x slower                                   |
| spectral_norm              | 69.7 ms                                                | 73.1 ms: 1.05x slower                                  |
| pickle_dict                | 17.0 us                                                | 17.9 us: 1.05x slower                                  |
| sympy_expand               | 234 ms                                                 | 247 ms: 1.06x slower                                   |
| pprint_safe_repr           | 479 ms                                                 | 510 ms: 1.06x slower                                   |
| logging_format             | 3.69 us                                                | 3.93 us: 1.06x slower                                  |
| bench_thread_pool          | 461 us                                                 | 492 us: 1.07x slower                                   |
| logging_simple             | 3.41 us                                                | 3.64 us: 1.07x slower                                  |
| nqueens                    | 54.6 ms                                                | 58.6 ms: 1.07x slower                                  |
| logging_silent             | 64.5 ns                                                | 69.6 ns: 1.08x slower                                  |
| json                       | 2.77 ms                                                | 3.00 ms: 1.08x slower                                  |
| scimark_lu                 | 67.8 ms                                                | 73.3 ms: 1.08x slower                                  |
| coroutines                 | 16.6 ms                                                | 18.0 ms: 1.09x slower                                  |
| bench_mp_pool              | 41.9 ms                                                | 45.6 ms: 1.09x slower                                  |
| scimark_fft                | 187 ms                                                 | 204 ms: 1.09x slower                                   |
| pickle_list                | 2.67 us                                                | 2.92 us: 1.09x slower                                  |
| unpickle                   | 8.32 us                                                | 9.15 us: 1.10x slower                                  |
| regex_v8                   | 15.3 ms                                                | 16.8 ms: 1.10x slower                                  |
| json_loads                 | 15.8 us                                                | 17.5 us: 1.11x slower                                  |
| xml_etree_iterparse        | 68.2 ms                                                | 76.3 ms: 1.12x slower                                  |
| chameleon                  | 4.17 ms                                                | 4.68 ms: 1.12x slower                                  |
| 2to3                       | 155 ms                                                 | 174 ms: 1.12x slower                                   |
| unpickle_list              | 2.77 us                                                | 3.11 us: 1.13x slower                                  |
| fannkuch                   | 247 ms                                                 | 279 ms: 1.13x slower                                   |
| richards                   | 30.8 ms                                                | 34.9 ms: 1.13x slower                                  |
| nbody                      | 68.7 ms                                                | 78.5 ms: 1.14x slower                                  |
| python_startup             | 11.4 ms                                                | 13.0 ms: 1.15x slower                                  |
| pyflate                    | 297 ms                                                 | 341 ms: 1.15x slower                                   |
| coverage                   | 41.4 ms                                                | 47.8 ms: 1.16x slower                                  |
| sqlglot_normalize          | 160 ms                                                 | 186 ms: 1.16x slower                                   |
| sqlglot_optimize           | 29.6 ms                                                | 34.6 ms: 1.17x slower                                  |
| xml_etree_process          | 34.0 ms                                                | 39.8 ms: 1.17x slower                                  |
| tomli_loads                | 1.30 sec                                               | 1.56 sec: 1.20x slower                                 |
| sqlite_synth               | 1.35 us                                                | 1.62 us: 1.20x slower                                  |
| xml_etree_generate         | 46.8 ms                                                | 57.8 ms: 1.23x slower                                  |
| python_startup_no_site     | 9.15 ms                                                | 11.7 ms: 1.28x slower                                  |
| mypy2                      | 191 ms                                                 | 261 ms: 1.37x slower                                   |
| scimark_sor                | 75.2 ms                                                | 105 ms: 1.40x slower                                   |
| telco                      | 3.17 ms                                                | 4.69 ms: 1.48x slower                                  |
| async_generators           | 192 ms                                                 | 298 ms: 1.55x slower                                   |
| Geometric mean             | (ref)                                                  | 1.02x slower                                           |

Benchmark hidden because not significant (2): tornado_http, sympy_str
Ignored benchmarks (12) of results/bm-20221024-3.11.0-deaf509/bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, dask, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift


# HPT report

- Reliability score: 99.52% likely to be slow
- 90% likely to have a slowdown of 1.01x
- 95% likely to have a slowdown of 1.01x
- 99% likely to have a slowdown of 1.00x
