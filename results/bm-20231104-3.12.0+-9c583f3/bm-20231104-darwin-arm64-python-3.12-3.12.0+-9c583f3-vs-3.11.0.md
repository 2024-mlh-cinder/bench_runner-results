
# Results vs. 3.11.0

- fork: python
- ref: 3.12
- machine: darwin-arm64
- commit hash: 9c583f3
- commit date: 2023-11-04
- overall geometric mean: 1.00x faster \*
- HPT reliability: 95.95%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231104-darwin-arm64-python-3.12-3.12.0+-9c583f3 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------:|
| 2to3           | 155 ms                                                 | 170 ms: 1.09x slower                                 |
| chameleon      | 4.17 ms                                                | 4.56 ms: 1.09x slower                                |
| docutils       | 1.46 sec                                               | 1.50 sec: 1.03x slower                               |
| Geometric mean | (ref)                                                  | 1.05x slower                                         |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231104-darwin-arm64-python-3.12-3.12.0+-9c583f3 |
|----------------------------|:------------------------------------------------------:|:----------------------------------------------------:|
| async_tree_memoization     | 361 ms                                                 | 310 ms: 1.16x faster                                 |
| async_tree_memoization_tg  | 357 ms                                                 | 321 ms: 1.11x faster                                 |
| async_tree_io_tg           | 734 ms                                                 | 665 ms: 1.10x faster                                 |
| async_tree_none_tg         | 280 ms                                                 | 255 ms: 1.10x faster                                 |
| async_tree_none            | 282 ms                                                 | 263 ms: 1.07x faster                                 |
| async_tree_io              | 705 ms                                                 | 662 ms: 1.06x faster                                 |
| async_tree_cpu_io_mixed_tg | 554 ms                                                 | 534 ms: 1.04x faster                                 |
| async_tree_cpu_io_mixed    | 522 ms                                                 | 527 ms: 1.01x slower                                 |
| Geometric mean             | (ref)                                                  | 1.08x faster                                         |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231104-darwin-arm64-python-3.12-3.12.0+-9c583f3 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------:|
| pidigits       | 281 ms                                                 | 283 ms: 1.01x slower                                 |
| float          | 55.4 ms                                                | 56.7 ms: 1.02x slower                                |
| Geometric mean | (ref)                                                  | 1.01x slower                                         |

Benchmark hidden because not significant (1): nbody

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231104-darwin-arm64-python-3.12-3.12.0+-9c583f3 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------:|
| regex_dna      | 149 ms                                                 | 149 ms: 1.00x faster                                 |
| regex_compile  | 73.9 ms                                                | 74.3 ms: 1.00x slower                                |
| regex_v8       | 15.3 ms                                                | 15.7 ms: 1.02x slower                                |
| regex_effbot   | 2.46 ms                                                | 2.58 ms: 1.05x slower                                |
| Geometric mean | (ref)                                                  | 1.02x slower                                         |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231104-darwin-arm64-python-3.12-3.12.0+-9c583f3 |
|----------------------|:------------------------------------------------------:|:----------------------------------------------------:|
| json_dumps           | 7.58 ms                                                | 6.32 ms: 1.20x faster                                |
| unpickle_pure_python | 163 us                                                 | 143 us: 1.14x faster                                 |
| pickle_pure_python   | 211 us                                                 | 188 us: 1.12x faster                                 |
| pickle               | 7.22 us                                                | 7.33 us: 1.02x slower                                |
| xml_etree_parse      | 107 ms                                                 | 110 ms: 1.03x slower                                 |
| pickle_dict          | 17.0 us                                                | 17.9 us: 1.05x slower                                |
| tomli_loads          | 1.30 sec                                               | 1.39 sec: 1.07x slower                               |
| pickle_list          | 2.67 us                                                | 2.93 us: 1.10x slower                                |
| xml_etree_iterparse  | 68.2 ms                                                | 75.1 ms: 1.10x slower                                |
| unpickle             | 8.32 us                                                | 9.31 us: 1.12x slower                                |
| json_loads           | 15.8 us                                                | 17.7 us: 1.12x slower                                |
| xml_etree_process    | 34.0 ms                                                | 38.8 ms: 1.14x slower                                |
| unpickle_list        | 2.77 us                                                | 3.22 us: 1.17x slower                                |
| xml_etree_generate   | 46.8 ms                                                | 55.9 ms: 1.19x slower                                |
| Geometric mean       | (ref)                                                  | 1.04x slower                                         |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231104-darwin-arm64-python-3.12-3.12.0+-9c583f3 |
|------------------------|:------------------------------------------------------:|:----------------------------------------------------:|
| python_startup         | 11.4 ms                                                | 12.5 ms: 1.10x slower                                |
| python_startup_no_site | 9.15 ms                                                | 10.3 ms: 1.13x slower                                |
| Geometric mean         | (ref)                                                  | 1.12x slower                                         |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231104-darwin-arm64-python-3.12-3.12.0+-9c583f3 |
|-----------------|:------------------------------------------------------:|:----------------------------------------------------:|
| mako            | 8.22 ms                                                | 7.24 ms: 1.14x faster                                |
| django_template | 19.8 ms                                                | 21.2 ms: 1.07x slower                                |
| Geometric mean  | (ref)                                                  | 1.03x faster                                         |

All benchmarks:
===============

| Benchmark                  | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231104-darwin-arm64-python-3.12-3.12.0+-9c583f3 |
|----------------------------|:------------------------------------------------------:|:----------------------------------------------------:|
| typing_runtime_protocols   | 323 us                                                 | 72.1 us: 4.48x faster                                |
| asyncio_tcp                | 650 ms                                                 | 468 ms: 1.39x faster                                 |
| json_dumps                 | 7.58 ms                                                | 6.32 ms: 1.20x faster                                |
| deepcopy_memo              | 28.9 us                                                | 24.8 us: 1.16x faster                                |
| async_tree_memoization     | 361 ms                                                 | 310 ms: 1.16x faster                                 |
| asyncio_tcp_ssl            | 1.44 sec                                               | 1.26 sec: 1.14x faster                               |
| chaos                      | 48.2 ms                                                | 42.1 ms: 1.14x faster                                |
| unpickle_pure_python       | 163 us                                                 | 143 us: 1.14x faster                                 |
| mako                       | 8.22 ms                                                | 7.24 ms: 1.14x faster                                |
| deltablue                  | 2.70 ms                                                | 2.40 ms: 1.12x faster                                |
| unpack_sequence            | 32.3 ns                                                | 28.8 ns: 1.12x faster                                |
| pickle_pure_python         | 211 us                                                 | 188 us: 1.12x faster                                 |
| generators                 | 29.2 ms                                                | 26.1 ms: 1.12x faster                                |
| async_tree_memoization_tg  | 357 ms                                                 | 321 ms: 1.11x faster                                 |
| async_tree_io_tg           | 734 ms                                                 | 665 ms: 1.10x faster                                 |
| coverage                   | 41.4 ms                                                | 37.5 ms: 1.10x faster                                |
| async_tree_none_tg         | 280 ms                                                 | 255 ms: 1.10x faster                                 |
| richards_super             | 36.8 ms                                                | 33.7 ms: 1.09x faster                                |
| scimark_monte_carlo        | 47.1 ms                                                | 43.2 ms: 1.09x faster                                |
| go                         | 102 ms                                                 | 94.7 ms: 1.08x faster                                |
| sqlglot_parse              | 886 us                                                 | 824 us: 1.07x faster                                 |
| async_tree_none            | 282 ms                                                 | 263 ms: 1.07x faster                                 |
| hexiom                     | 4.55 ms                                                | 4.25 ms: 1.07x faster                                |
| async_tree_io              | 705 ms                                                 | 662 ms: 1.06x faster                                 |
| mdp                        | 1.73 sec                                               | 1.64 sec: 1.06x faster                               |
| sqlglot_transpile          | 1.05 ms                                                | 999 us: 1.05x faster                                 |
| deepcopy                   | 233 us                                                 | 223 us: 1.04x faster                                 |
| sqlalchemy_imperative      | 7.17 ms                                                | 6.88 ms: 1.04x faster                                |
| async_tree_cpu_io_mixed_tg | 554 ms                                                 | 534 ms: 1.04x faster                                 |
| sympy_sum                  | 81.6 ms                                                | 78.7 ms: 1.04x faster                                |
| create_gc_cycles           | 715 us                                                 | 696 us: 1.03x faster                                 |
| meteor_contest             | 74.9 ms                                                | 73.0 ms: 1.03x faster                                |
| richards                   | 30.8 ms                                                | 30.1 ms: 1.02x faster                                |
| sympy_integrate            | 11.3 ms                                                | 11.2 ms: 1.01x faster                                |
| mypy2                      | 191 ms                                                 | 189 ms: 1.01x faster                                 |
| regex_dna                  | 149 ms                                                 | 149 ms: 1.00x faster                                 |
| asyncio_websockets         | 544 ms                                                 | 546 ms: 1.00x slower                                 |
| gc_traversal               | 2.39 ms                                                | 2.40 ms: 1.00x slower                                |
| comprehensions             | 14.7 us                                                | 14.7 us: 1.00x slower                                |
| regex_compile              | 73.9 ms                                                | 74.3 ms: 1.00x slower                                |
| pidigits                   | 281 ms                                                 | 283 ms: 1.01x slower                                 |
| pprint_pformat             | 989 ms                                                 | 996 ms: 1.01x slower                                 |
| async_tree_cpu_io_mixed    | 522 ms                                                 | 527 ms: 1.01x slower                                 |
| dask                       | 224 ms                                                 | 226 ms: 1.01x slower                                 |
| pickle                     | 7.22 us                                                | 7.33 us: 1.02x slower                                |
| pathlib                    | 28.5 ms                                                | 29.1 ms: 1.02x slower                                |
| regex_v8                   | 15.3 ms                                                | 15.7 ms: 1.02x slower                                |
| float                      | 55.4 ms                                                | 56.7 ms: 1.02x slower                                |
| deepcopy_reduce            | 1.98 us                                                | 2.03 us: 1.02x slower                                |
| xml_etree_parse            | 107 ms                                                 | 110 ms: 1.03x slower                                 |
| pprint_safe_repr           | 479 ms                                                 | 492 ms: 1.03x slower                                 |
| docutils                   | 1.46 sec                                               | 1.50 sec: 1.03x slower                               |
| sympy_str                  | 144 ms                                                 | 149 ms: 1.03x slower                                 |
| raytrace                   | 200 ms                                                 | 207 ms: 1.03x slower                                 |
| logging_format             | 3.69 us                                                | 3.85 us: 1.04x slower                                |
| logging_simple             | 3.41 us                                                | 3.57 us: 1.05x slower                                |
| regex_effbot               | 2.46 ms                                                | 2.58 ms: 1.05x slower                                |
| pickle_dict                | 17.0 us                                                | 17.9 us: 1.05x slower                                |
| aiohttp                    | 1.05 ms                                                | 1.11 ms: 1.05x slower                                |
| bench_thread_pool          | 461 us                                                 | 486 us: 1.05x slower                                 |
| fannkuch                   | 247 ms                                                 | 261 ms: 1.06x slower                                 |
| logging_silent             | 64.5 ns                                                | 68.1 ns: 1.06x slower                                |
| sympy_expand               | 234 ms                                                 | 247 ms: 1.06x slower                                 |
| scimark_sparse_mat_mult    | 3.01 ms                                                | 3.19 ms: 1.06x slower                                |
| gunicorn                   | 1.11 ms                                                | 1.18 ms: 1.06x slower                                |
| scimark_lu                 | 67.8 ms                                                | 71.8 ms: 1.06x slower                                |
| pyflate                    | 297 ms                                                 | 316 ms: 1.06x slower                                 |
| tomli_loads                | 1.30 sec                                               | 1.39 sec: 1.07x slower                               |
| scimark_fft                | 187 ms                                                 | 200 ms: 1.07x slower                                 |
| sqlalchemy_declarative     | 60.6 ms                                                | 64.9 ms: 1.07x slower                                |
| django_template            | 19.8 ms                                                | 21.2 ms: 1.07x slower                                |
| crypto_pyaes               | 48.1 ms                                                | 51.9 ms: 1.08x slower                                |
| json                       | 2.77 ms                                                | 2.99 ms: 1.08x slower                                |
| spectral_norm              | 69.7 ms                                                | 75.5 ms: 1.08x slower                                |
| bench_mp_pool              | 41.9 ms                                                | 45.7 ms: 1.09x slower                                |
| chameleon                  | 4.17 ms                                                | 4.56 ms: 1.09x slower                                |
| 2to3                       | 155 ms                                                 | 170 ms: 1.09x slower                                 |
| pickle_list                | 2.67 us                                                | 2.93 us: 1.10x slower                                |
| xml_etree_iterparse        | 68.2 ms                                                | 75.1 ms: 1.10x slower                                |
| python_startup             | 11.4 ms                                                | 12.5 ms: 1.10x slower                                |
| nqueens                    | 54.6 ms                                                | 60.5 ms: 1.11x slower                                |
| unpickle                   | 8.32 us                                                | 9.31 us: 1.12x slower                                |
| json_loads                 | 15.8 us                                                | 17.7 us: 1.12x slower                                |
| python_startup_no_site     | 9.15 ms                                                | 10.3 ms: 1.13x slower                                |
| xml_etree_process          | 34.0 ms                                                | 38.8 ms: 1.14x slower                                |
| scimark_sor                | 75.2 ms                                                | 86.6 ms: 1.15x slower                                |
| coroutines                 | 16.6 ms                                                | 19.1 ms: 1.15x slower                                |
| sqlglot_normalize          | 160 ms                                                 | 185 ms: 1.16x slower                                 |
| sqlglot_optimize           | 29.6 ms                                                | 34.3 ms: 1.16x slower                                |
| unpickle_list              | 2.77 us                                                | 3.22 us: 1.17x slower                                |
| sqlite_synth               | 1.35 us                                                | 1.59 us: 1.18x slower                                |
| telco                      | 3.17 ms                                                | 3.75 ms: 1.18x slower                                |
| xml_etree_generate         | 46.8 ms                                                | 55.9 ms: 1.19x slower                                |
| async_generators           | 192 ms                                                 | 303 ms: 1.58x slower                                 |
| Geometric mean             | (ref)                                                  | 1.00x faster                                         |

Benchmark hidden because not significant (4): tornado_http, dulwich_log, nbody, pycparser
Ignored benchmarks (6) of results/bm-20221024-3.11.0-deaf509/bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509.json: flaskblogging, genshi_text, genshi_xml, html5lib, pylint, thrift


# HPT report

- Reliability score: 95.95% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
