
# Results vs. 3.11.0

- fork: python
- ref: main
- machine: darwin-arm64
- commit hash: ce6a533
- commit date: 2023-11-12
- overall geometric mean: 1.10x slower \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.04x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231112-darwin-arm64-python-main-3.13.0a1+-ce6a533 |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| 2to3           | 155 ms                                                 | 186 ms: 1.20x slower                                   |
| chameleon      | 4.17 ms                                                | 5.01 ms: 1.20x slower                                  |
| docutils       | 1.46 sec                                               | 1.55 sec: 1.06x slower                                 |
| Geometric mean | (ref)                                                  | 1.12x slower                                           |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231112-darwin-arm64-python-main-3.13.0a1+-ce6a533 |
|----------------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| async_tree_memoization     | 361 ms                                                 | 346 ms: 1.04x faster                                   |
| async_tree_none            | 282 ms                                                 | 270 ms: 1.04x faster                                   |
| async_tree_io_tg           | 734 ms                                                 | 709 ms: 1.04x faster                                   |
| async_tree_none_tg         | 280 ms                                                 | 282 ms: 1.01x slower                                   |
| async_tree_cpu_io_mixed_tg | 554 ms                                                 | 559 ms: 1.01x slower                                   |
| async_tree_io              | 705 ms                                                 | 729 ms: 1.03x slower                                   |
| async_tree_cpu_io_mixed    | 522 ms                                                 | 542 ms: 1.04x slower                                   |
| Geometric mean             | (ref)                                                  | 1.01x faster                                           |

Benchmark hidden because not significant (1): async_tree_memoization_tg

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231112-darwin-arm64-python-main-3.13.0a1+-ce6a533 |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| pidigits       | 281 ms                                                 | 283 ms: 1.01x slower                                   |
| float          | 55.4 ms                                                | 75.9 ms: 1.37x slower                                  |
| nbody          | 68.7 ms                                                | 98.8 ms: 1.44x slower                                  |
| Geometric mean | (ref)                                                  | 1.26x slower                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231112-darwin-arm64-python-main-3.13.0a1+-ce6a533 |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| regex_dna      | 149 ms                                                 | 149 ms: 1.00x faster                                   |
| regex_effbot   | 2.46 ms                                                | 2.56 ms: 1.04x slower                                  |
| regex_v8       | 15.3 ms                                                | 17.0 ms: 1.11x slower                                  |
| regex_compile  | 73.9 ms                                                | 93.2 ms: 1.26x slower                                  |
| Geometric mean | (ref)                                                  | 1.10x slower                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231112-darwin-arm64-python-main-3.13.0a1+-ce6a533 |
|----------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| json_dumps           | 7.58 ms                                                | 6.56 ms: 1.15x faster                                  |
| pickle_pure_python   | 211 us                                                 | 201 us: 1.05x faster                                   |
| xml_etree_parse      | 107 ms                                                 | 110 ms: 1.03x slower                                   |
| pickle               | 7.22 us                                                | 7.44 us: 1.03x slower                                  |
| pickle_dict          | 17.0 us                                                | 18.1 us: 1.06x slower                                  |
| pickle_list          | 2.67 us                                                | 2.88 us: 1.08x slower                                  |
| unpickle_pure_python | 163 us                                                 | 177 us: 1.09x slower                                   |
| unpickle             | 8.32 us                                                | 9.17 us: 1.10x slower                                  |
| json_loads           | 15.8 us                                                | 17.6 us: 1.12x slower                                  |
| unpickle_list        | 2.77 us                                                | 3.13 us: 1.13x slower                                  |
| xml_etree_process    | 34.0 ms                                                | 40.0 ms: 1.18x slower                                  |
| xml_etree_iterparse  | 68.2 ms                                                | 82.1 ms: 1.20x slower                                  |
| xml_etree_generate   | 46.8 ms                                                | 59.2 ms: 1.26x slower                                  |
| tomli_loads          | 1.30 sec                                               | 2.05 sec: 1.57x slower                                 |
| Geometric mean       | (ref)                                                  | 1.11x slower                                           |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231112-darwin-arm64-python-main-3.13.0a1+-ce6a533 |
|------------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| python_startup         | 11.4 ms                                                | 12.2 ms: 1.08x slower                                  |
| python_startup_no_site | 9.15 ms                                                | 10.9 ms: 1.19x slower                                  |
| Geometric mean         | (ref)                                                  | 1.13x slower                                           |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231112-darwin-arm64-python-main-3.13.0a1+-ce6a533 |
|-----------|:------------------------------------------------------:|:------------------------------------------------------:|
| mako      | 8.22 ms                                                | 10.5 ms: 1.28x slower                                  |

All benchmarks:
===============

| Benchmark                  | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231112-darwin-arm64-python-main-3.13.0a1+-ce6a533 |
|----------------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| typing_runtime_protocols   | 323 us                                                 | 81.3 us: 3.97x faster                                  |
| asyncio_tcp                | 650 ms                                                 | 438 ms: 1.48x faster                                   |
| unpack_sequence            | 32.3 ns                                                | 26.7 ns: 1.21x faster                                  |
| generators                 | 29.2 ms                                                | 24.7 ms: 1.18x faster                                  |
| json_dumps                 | 7.58 ms                                                | 6.56 ms: 1.15x faster                                  |
| asyncio_tcp_ssl            | 1.44 sec                                               | 1.30 sec: 1.11x faster                                 |
| deepcopy_memo              | 28.9 us                                                | 27.4 us: 1.05x faster                                  |
| pickle_pure_python         | 211 us                                                 | 201 us: 1.05x faster                                   |
| sympy_sum                  | 81.6 ms                                                | 78.0 ms: 1.05x faster                                  |
| async_tree_memoization     | 361 ms                                                 | 346 ms: 1.04x faster                                   |
| async_tree_none            | 282 ms                                                 | 270 ms: 1.04x faster                                   |
| async_tree_io_tg           | 734 ms                                                 | 709 ms: 1.04x faster                                   |
| deepcopy                   | 233 us                                                 | 226 us: 1.03x faster                                   |
| sqlglot_parse              | 886 us                                                 | 862 us: 1.03x faster                                   |
| create_gc_cycles           | 715 us                                                 | 700 us: 1.02x faster                                   |
| raytrace                   | 200 ms                                                 | 198 ms: 1.01x faster                                   |
| regex_dna                  | 149 ms                                                 | 149 ms: 1.00x faster                                   |
| asyncio_websockets         | 544 ms                                                 | 545 ms: 1.00x slower                                   |
| gc_traversal               | 2.39 ms                                                | 2.40 ms: 1.00x slower                                  |
| deepcopy_reduce            | 1.98 us                                                | 1.99 us: 1.01x slower                                  |
| pidigits                   | 281 ms                                                 | 283 ms: 1.01x slower                                   |
| async_tree_none_tg         | 280 ms                                                 | 282 ms: 1.01x slower                                   |
| async_tree_cpu_io_mixed_tg | 554 ms                                                 | 559 ms: 1.01x slower                                   |
| chaos                      | 48.2 ms                                                | 49.1 ms: 1.02x slower                                  |
| mdp                        | 1.73 sec                                               | 1.78 sec: 1.03x slower                                 |
| xml_etree_parse            | 107 ms                                                 | 110 ms: 1.03x slower                                   |
| pickle                     | 7.22 us                                                | 7.44 us: 1.03x slower                                  |
| async_tree_io              | 705 ms                                                 | 729 ms: 1.03x slower                                   |
| dulwich_log                | 29.9 ms                                                | 30.9 ms: 1.04x slower                                  |
| async_tree_cpu_io_mixed    | 522 ms                                                 | 542 ms: 1.04x slower                                   |
| regex_effbot               | 2.46 ms                                                | 2.56 ms: 1.04x slower                                  |
| spectral_norm              | 69.7 ms                                                | 72.9 ms: 1.05x slower                                  |
| richards_super             | 36.8 ms                                                | 38.5 ms: 1.05x slower                                  |
| pathlib                    | 28.5 ms                                                | 30.0 ms: 1.05x slower                                  |
| sympy_str                  | 144 ms                                                 | 152 ms: 1.06x slower                                   |
| pickle_dict                | 17.0 us                                                | 18.1 us: 1.06x slower                                  |
| docutils                   | 1.46 sec                                               | 1.55 sec: 1.06x slower                                 |
| bench_mp_pool              | 41.9 ms                                                | 44.9 ms: 1.07x slower                                  |
| sympy_integrate            | 11.3 ms                                                | 12.2 ms: 1.07x slower                                  |
| python_startup             | 11.4 ms                                                | 12.2 ms: 1.08x slower                                  |
| pickle_list                | 2.67 us                                                | 2.88 us: 1.08x slower                                  |
| pycparser                  | 667 ms                                                 | 721 ms: 1.08x slower                                   |
| logging_format             | 3.69 us                                                | 4.00 us: 1.08x slower                                  |
| json                       | 2.77 ms                                                | 3.01 ms: 1.09x slower                                  |
| unpickle_pure_python       | 163 us                                                 | 177 us: 1.09x slower                                   |
| logging_simple             | 3.41 us                                                | 3.72 us: 1.09x slower                                  |
| sympy_expand               | 234 ms                                                 | 256 ms: 1.10x slower                                   |
| coroutines                 | 16.6 ms                                                | 18.2 ms: 1.10x slower                                  |
| unpickle                   | 8.32 us                                                | 9.17 us: 1.10x slower                                  |
| regex_v8                   | 15.3 ms                                                | 17.0 ms: 1.11x slower                                  |
| bench_thread_pool          | 461 us                                                 | 514 us: 1.11x slower                                   |
| json_loads                 | 15.8 us                                                | 17.6 us: 1.12x slower                                  |
| meteor_contest             | 74.9 ms                                                | 83.8 ms: 1.12x slower                                  |
| logging_silent             | 64.5 ns                                                | 72.3 ns: 1.12x slower                                  |
| unpickle_list              | 2.77 us                                                | 3.13 us: 1.13x slower                                  |
| richards                   | 30.8 ms                                                | 35.0 ms: 1.14x slower                                  |
| coverage                   | 41.4 ms                                                | 47.5 ms: 1.15x slower                                  |
| scimark_lu                 | 67.8 ms                                                | 78.4 ms: 1.16x slower                                  |
| go                         | 102 ms                                                 | 119 ms: 1.17x slower                                   |
| xml_etree_process          | 34.0 ms                                                | 40.0 ms: 1.18x slower                                  |
| python_startup_no_site     | 9.15 ms                                                | 10.9 ms: 1.19x slower                                  |
| sqlglot_normalize          | 160 ms                                                 | 190 ms: 1.19x slower                                   |
| sqlglot_optimize           | 29.6 ms                                                | 35.3 ms: 1.19x slower                                  |
| pprint_pformat             | 989 ms                                                 | 1.18 sec: 1.19x slower                                 |
| 2to3                       | 155 ms                                                 | 186 ms: 1.20x slower                                   |
| chameleon                  | 4.17 ms                                                | 5.01 ms: 1.20x slower                                  |
| crypto_pyaes               | 48.1 ms                                                | 57.9 ms: 1.20x slower                                  |
| xml_etree_iterparse        | 68.2 ms                                                | 82.1 ms: 1.20x slower                                  |
| pprint_safe_repr           | 479 ms                                                 | 579 ms: 1.21x slower                                   |
| scimark_monte_carlo        | 47.1 ms                                                | 57.3 ms: 1.22x slower                                  |
| sqlite_synth               | 1.35 us                                                | 1.69 us: 1.26x slower                                  |
| regex_compile              | 73.9 ms                                                | 93.2 ms: 1.26x slower                                  |
| xml_etree_generate         | 46.8 ms                                                | 59.2 ms: 1.26x slower                                  |
| mako                       | 8.22 ms                                                | 10.5 ms: 1.28x slower                                  |
| pyflate                    | 297 ms                                                 | 403 ms: 1.36x slower                                   |
| comprehensions             | 14.7 us                                                | 19.9 us: 1.36x slower                                  |
| float                      | 55.4 ms                                                | 75.9 ms: 1.37x slower                                  |
| scimark_fft                | 187 ms                                                 | 258 ms: 1.38x slower                                   |
| mypy2                      | 191 ms                                                 | 268 ms: 1.41x slower                                   |
| nbody                      | 68.7 ms                                                | 98.8 ms: 1.44x slower                                  |
| scimark_sor                | 75.2 ms                                                | 109 ms: 1.45x slower                                   |
| deltablue                  | 2.70 ms                                                | 3.90 ms: 1.45x slower                                  |
| nqueens                    | 54.6 ms                                                | 80.1 ms: 1.47x slower                                  |
| tomli_loads                | 1.30 sec                                               | 2.05 sec: 1.57x slower                                 |
| telco                      | 3.17 ms                                                | 5.07 ms: 1.60x slower                                  |
| fannkuch                   | 247 ms                                                 | 396 ms: 1.60x slower                                   |
| async_generators           | 192 ms                                                 | 312 ms: 1.62x slower                                   |
| scimark_sparse_mat_mult    | 3.01 ms                                                | 4.98 ms: 1.65x slower                                  |
| hexiom                     | 4.55 ms                                                | 7.57 ms: 1.66x slower                                  |
| Geometric mean             | (ref)                                                  | 1.10x slower                                           |

Benchmark hidden because not significant (3): async_tree_memoization_tg, sqlglot_transpile, tornado_http
Ignored benchmarks (12) of results/bm-20221024-3.11.0-deaf509/bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, dask, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.05x
- 95% likely to have a slowdown of 1.05x
- 99% likely to have a slowdown of 1.04x
