
# Results vs. 3.11.0

- fork: brandtbucher
- ref: justin
- machine: darwin-arm64
- commit hash: 241ce0f
- commit date: 2023-11-11
- overall geometric mean: 1.03x slower \*
- HPT reliability: 99.89%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231111-darwin-arm64-brandtbucher-justin-3.13.0a1+-241ce0f |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| 2to3           | 155 ms                                                 | 178 ms: 1.15x slower                                           |
| chameleon      | 4.17 ms                                                | 4.74 ms: 1.13x slower                                          |
| docutils       | 1.46 sec                                               | 1.51 sec: 1.04x slower                                         |
| Geometric mean | (ref)                                                  | 1.08x slower                                                   |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231111-darwin-arm64-brandtbucher-justin-3.13.0a1+-241ce0f |
|----------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| async_tree_none            | 282 ms                                                 | 254 ms: 1.11x faster                                           |
| async_tree_memoization     | 361 ms                                                 | 332 ms: 1.09x faster                                           |
| async_tree_memoization_tg  | 357 ms                                                 | 334 ms: 1.07x faster                                           |
| async_tree_io_tg           | 734 ms                                                 | 689 ms: 1.07x faster                                           |
| async_tree_none_tg         | 280 ms                                                 | 268 ms: 1.04x faster                                           |
| async_tree_cpu_io_mixed_tg | 554 ms                                                 | 546 ms: 1.01x faster                                           |
| async_tree_cpu_io_mixed    | 522 ms                                                 | 528 ms: 1.01x slower                                           |
| Geometric mean             | (ref)                                                  | 1.05x faster                                                   |

Benchmark hidden because not significant (1): async_tree_io

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231111-darwin-arm64-brandtbucher-justin-3.13.0a1+-241ce0f |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| pidigits       | 281 ms                                                 | 282 ms: 1.00x slower                                           |
| float          | 55.4 ms                                                | 58.3 ms: 1.05x slower                                          |
| nbody          | 68.7 ms                                                | 82.2 ms: 1.20x slower                                          |
| Geometric mean | (ref)                                                  | 1.08x slower                                                   |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231111-darwin-arm64-brandtbucher-justin-3.13.0a1+-241ce0f |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| regex_dna      | 149 ms                                                 | 149 ms: 1.00x slower                                           |
| regex_effbot   | 2.46 ms                                                | 2.56 ms: 1.04x slower                                          |
| regex_compile  | 73.9 ms                                                | 79.0 ms: 1.07x slower                                          |
| regex_v8       | 15.3 ms                                                | 16.9 ms: 1.10x slower                                          |
| Geometric mean | (ref)                                                  | 1.05x slower                                                   |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231111-darwin-arm64-brandtbucher-justin-3.13.0a1+-241ce0f |
|----------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| json_dumps           | 7.58 ms                                                | 6.67 ms: 1.14x faster                                          |
| pickle_pure_python   | 211 us                                                 | 200 us: 1.05x faster                                           |
| unpickle_pure_python | 163 us                                                 | 162 us: 1.01x faster                                           |
| pickle               | 7.22 us                                                | 7.45 us: 1.03x slower                                          |
| xml_etree_parse      | 107 ms                                                 | 111 ms: 1.03x slower                                           |
| pickle_dict          | 17.0 us                                                | 17.9 us: 1.05x slower                                          |
| pickle_list          | 2.67 us                                                | 2.85 us: 1.07x slower                                          |
| tomli_loads          | 1.30 sec                                               | 1.39 sec: 1.07x slower                                         |
| unpickle             | 8.32 us                                                | 9.11 us: 1.09x slower                                          |
| json_loads           | 15.8 us                                                | 17.6 us: 1.12x slower                                          |
| xml_etree_iterparse  | 68.2 ms                                                | 76.3 ms: 1.12x slower                                          |
| unpickle_list        | 2.77 us                                                | 3.14 us: 1.13x slower                                          |
| xml_etree_process    | 34.0 ms                                                | 40.0 ms: 1.18x slower                                          |
| xml_etree_generate   | 46.8 ms                                                | 58.1 ms: 1.24x slower                                          |
| Geometric mean       | (ref)                                                  | 1.06x slower                                                   |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231111-darwin-arm64-brandtbucher-justin-3.13.0a1+-241ce0f |
|------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| python_startup         | 11.4 ms                                                | 11.7 ms: 1.03x slower                                          |
| python_startup_no_site | 9.15 ms                                                | 10.3 ms: 1.13x slower                                          |
| Geometric mean         | (ref)                                                  | 1.08x slower                                                   |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231111-darwin-arm64-brandtbucher-justin-3.13.0a1+-241ce0f |
|-----------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| mako      | 8.22 ms                                                | 7.63 ms: 1.08x faster                                          |

All benchmarks:
===============

| Benchmark                  | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231111-darwin-arm64-brandtbucher-justin-3.13.0a1+-241ce0f |
|----------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| typing_runtime_protocols   | 323 us                                                 | 76.0 us: 4.24x faster                                          |
| asyncio_tcp                | 650 ms                                                 | 458 ms: 1.42x faster                                           |
| unpack_sequence            | 32.3 ns                                                | 26.9 ns: 1.20x faster                                          |
| generators                 | 29.2 ms                                                | 24.4 ms: 1.19x faster                                          |
| deepcopy_memo              | 28.9 us                                                | 25.3 us: 1.14x faster                                          |
| json_dumps                 | 7.58 ms                                                | 6.67 ms: 1.14x faster                                          |
| asyncio_tcp_ssl            | 1.44 sec                                               | 1.29 sec: 1.11x faster                                         |
| chaos                      | 48.2 ms                                                | 43.5 ms: 1.11x faster                                          |
| async_tree_none            | 282 ms                                                 | 254 ms: 1.11x faster                                           |
| comprehensions             | 14.7 us                                                | 13.2 us: 1.11x faster                                          |
| raytrace                   | 200 ms                                                 | 183 ms: 1.10x faster                                           |
| async_tree_memoization     | 361 ms                                                 | 332 ms: 1.09x faster                                           |
| mako                       | 8.22 ms                                                | 7.63 ms: 1.08x faster                                          |
| async_tree_memoization_tg  | 357 ms                                                 | 334 ms: 1.07x faster                                           |
| deltablue                  | 2.70 ms                                                | 2.53 ms: 1.07x faster                                          |
| async_tree_io_tg           | 734 ms                                                 | 689 ms: 1.07x faster                                           |
| sqlglot_parse              | 886 us                                                 | 832 us: 1.06x faster                                           |
| pickle_pure_python         | 211 us                                                 | 200 us: 1.05x faster                                           |
| deepcopy                   | 233 us                                                 | 223 us: 1.05x faster                                           |
| async_tree_none_tg         | 280 ms                                                 | 268 ms: 1.04x faster                                           |
| mdp                        | 1.73 sec                                               | 1.67 sec: 1.04x faster                                         |
| sqlglot_transpile          | 1.05 ms                                                | 1.01 ms: 1.03x faster                                          |
| create_gc_cycles           | 715 us                                                 | 699 us: 1.02x faster                                           |
| async_tree_cpu_io_mixed_tg | 554 ms                                                 | 546 ms: 1.01x faster                                           |
| unpickle_pure_python       | 163 us                                                 | 162 us: 1.01x faster                                           |
| richards_super             | 36.8 ms                                                | 36.7 ms: 1.00x faster                                          |
| regex_dna                  | 149 ms                                                 | 149 ms: 1.00x slower                                           |
| asyncio_websockets         | 544 ms                                                 | 545 ms: 1.00x slower                                           |
| pidigits                   | 281 ms                                                 | 282 ms: 1.00x slower                                           |
| gc_traversal               | 2.39 ms                                                | 2.40 ms: 1.01x slower                                          |
| async_tree_cpu_io_mixed    | 522 ms                                                 | 528 ms: 1.01x slower                                           |
| crypto_pyaes               | 48.1 ms                                                | 49.0 ms: 1.02x slower                                          |
| dulwich_log                | 29.9 ms                                                | 30.5 ms: 1.02x slower                                          |
| meteor_contest             | 74.9 ms                                                | 76.9 ms: 1.03x slower                                          |
| python_startup             | 11.4 ms                                                | 11.7 ms: 1.03x slower                                          |
| pickle                     | 7.22 us                                                | 7.45 us: 1.03x slower                                          |
| xml_etree_parse            | 107 ms                                                 | 111 ms: 1.03x slower                                           |
| scimark_monte_carlo        | 47.1 ms                                                | 48.8 ms: 1.04x slower                                          |
| logging_format             | 3.69 us                                                | 3.83 us: 1.04x slower                                          |
| go                         | 102 ms                                                 | 106 ms: 1.04x slower                                           |
| docutils                   | 1.46 sec                                               | 1.51 sec: 1.04x slower                                         |
| logging_simple             | 3.41 us                                                | 3.55 us: 1.04x slower                                          |
| regex_effbot               | 2.46 ms                                                | 2.56 ms: 1.04x slower                                          |
| spectral_norm              | 69.7 ms                                                | 72.8 ms: 1.04x slower                                          |
| pathlib                    | 28.5 ms                                                | 29.8 ms: 1.05x slower                                          |
| pickle_dict                | 17.0 us                                                | 17.9 us: 1.05x slower                                          |
| pycparser                  | 667 ms                                                 | 702 ms: 1.05x slower                                           |
| float                      | 55.4 ms                                                | 58.3 ms: 1.05x slower                                          |
| pickle_list                | 2.67 us                                                | 2.85 us: 1.07x slower                                          |
| tomli_loads                | 1.30 sec                                               | 1.39 sec: 1.07x slower                                         |
| bench_mp_pool              | 41.9 ms                                                | 44.7 ms: 1.07x slower                                          |
| regex_compile              | 73.9 ms                                                | 79.0 ms: 1.07x slower                                          |
| richards                   | 30.8 ms                                                | 32.9 ms: 1.07x slower                                          |
| scimark_sparse_mat_mult    | 3.01 ms                                                | 3.23 ms: 1.07x slower                                          |
| json                       | 2.77 ms                                                | 2.99 ms: 1.08x slower                                          |
| coroutines                 | 16.6 ms                                                | 18.0 ms: 1.08x slower                                          |
| bench_thread_pool          | 461 us                                                 | 502 us: 1.09x slower                                           |
| logging_silent             | 64.5 ns                                                | 70.5 ns: 1.09x slower                                          |
| unpickle                   | 8.32 us                                                | 9.11 us: 1.09x slower                                          |
| regex_v8                   | 15.3 ms                                                | 16.9 ms: 1.10x slower                                          |
| scimark_lu                 | 67.8 ms                                                | 75.1 ms: 1.11x slower                                          |
| json_loads                 | 15.8 us                                                | 17.6 us: 1.12x slower                                          |
| xml_etree_iterparse        | 68.2 ms                                                | 76.3 ms: 1.12x slower                                          |
| hexiom                     | 4.55 ms                                                | 5.11 ms: 1.12x slower                                          |
| pyflate                    | 297 ms                                                 | 335 ms: 1.13x slower                                           |
| python_startup_no_site     | 9.15 ms                                                | 10.3 ms: 1.13x slower                                          |
| unpickle_list              | 2.77 us                                                | 3.14 us: 1.13x slower                                          |
| chameleon                  | 4.17 ms                                                | 4.74 ms: 1.13x slower                                          |
| scimark_fft                | 187 ms                                                 | 213 ms: 1.14x slower                                           |
| 2to3                       | 155 ms                                                 | 178 ms: 1.15x slower                                           |
| nqueens                    | 54.6 ms                                                | 62.7 ms: 1.15x slower                                          |
| coverage                   | 41.4 ms                                                | 48.0 ms: 1.16x slower                                          |
| xml_etree_process          | 34.0 ms                                                | 40.0 ms: 1.18x slower                                          |
| sqlglot_normalize          | 160 ms                                                 | 188 ms: 1.18x slower                                           |
| sqlglot_optimize           | 29.6 ms                                                | 35.0 ms: 1.18x slower                                          |
| fannkuch                   | 247 ms                                                 | 293 ms: 1.18x slower                                           |
| nbody                      | 68.7 ms                                                | 82.2 ms: 1.20x slower                                          |
| sqlite_synth               | 1.35 us                                                | 1.63 us: 1.21x slower                                          |
| xml_etree_generate         | 46.8 ms                                                | 58.1 ms: 1.24x slower                                          |
| mypy2                      | 191 ms                                                 | 264 ms: 1.39x slower                                           |
| scimark_sor                | 75.2 ms                                                | 106 ms: 1.41x slower                                           |
| telco                      | 3.17 ms                                                | 4.63 ms: 1.46x slower                                          |
| async_generators           | 192 ms                                                 | 313 ms: 1.63x slower                                           |
| Geometric mean             | (ref)                                                  | 1.03x slower                                                   |

Benchmark hidden because not significant (3): deepcopy_reduce, tornado_http, async_tree_io
Ignored benchmarks (18) of results/bm-20221024-3.11.0-deaf509/bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, dask, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pprint_pformat, pprint_safe_repr, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 99.89% likely to be slow
- 90% likely to have a slowdown of 1.02x
- 95% likely to have a slowdown of 1.01x
- 99% likely to have a slowdown of 1.00x
