
# Results vs. 3.12.0

- fork: python
- ref: 3b9d793efcfd2c00c14f
- machine: darwin-arm64
- commit hash: 3b9d793
- commit date: 2022-11-14
- overall geometric mean: 1.00x slower
- HPT reliability: 88.85%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0 | bm-20221114-darwin-arm64-python-3b9d793efcfd2c00c14f-3.12.0a2-3b9d793 |
|----------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| 2to3           | 170 ms                                                              | 160 ms: 1.06x faster                                                  |
| chameleon      | 4.51 ms                                                             | 4.29 ms: 1.05x faster                                                 |
| docutils       | 1.53 sec                                                            | 1.43 sec: 1.07x faster                                                |
| Geometric mean | (ref)                                                               | 1.04x faster                                                          |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0 | bm-20221114-darwin-arm64-python-3b9d793efcfd2c00c14f-3.12.0a2-3b9d793 |
|----------------------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| async_tree_cpu_io_mixed_tg | 530 ms                                                              | 539 ms: 1.02x slower                                                  |
| async_tree_none_tg         | 252 ms                                                              | 262 ms: 1.04x slower                                                  |
| async_tree_io_tg           | 664 ms                                                              | 703 ms: 1.06x slower                                                  |
| async_tree_memoization_tg  | 316 ms                                                              | 336 ms: 1.06x slower                                                  |
| async_tree_memoization     | 306 ms                                                              | 329 ms: 1.08x slower                                                  |
| async_tree_none            | 258 ms                                                              | 281 ms: 1.09x slower                                                  |
| async_tree_io              | 659 ms                                                              | 725 ms: 1.10x slower                                                  |
| Geometric mean             | (ref)                                                               | 1.06x slower                                                          |

Benchmark hidden because not significant (1): async_tree_cpu_io_mixed

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0 | bm-20221114-darwin-arm64-python-3b9d793efcfd2c00c14f-3.12.0a2-3b9d793 |
|----------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| float          | 58.0 ms                                                             | 56.0 ms: 1.04x faster                                                 |
| pidigits       | 282 ms                                                              | 280 ms: 1.01x faster                                                  |
| Geometric mean | (ref)                                                               | 1.01x faster                                                          |

Benchmark hidden because not significant (1): nbody

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0 | bm-20221114-darwin-arm64-python-3b9d793efcfd2c00c14f-3.12.0a2-3b9d793 |
|----------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| regex_effbot   | 2.58 ms                                                             | 2.44 ms: 1.06x faster                                                 |
| regex_v8       | 15.6 ms                                                             | 15.0 ms: 1.05x faster                                                 |
| regex_compile  | 75.8 ms                                                             | 72.7 ms: 1.04x faster                                                 |
| regex_dna      | 152 ms                                                              | 147 ms: 1.04x faster                                                  |
| Geometric mean | (ref)                                                               | 1.04x faster                                                          |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0 | bm-20221114-darwin-arm64-python-3b9d793efcfd2c00c14f-3.12.0a2-3b9d793 |
|----------------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| xml_etree_generate   | 55.8 ms                                                             | 46.0 ms: 1.21x faster                                                 |
| unpickle_list        | 3.20 us                                                             | 2.73 us: 1.17x faster                                                 |
| xml_etree_process    | 38.6 ms                                                             | 34.2 ms: 1.13x faster                                                 |
| xml_etree_parse      | 106 ms                                                              | 95.4 ms: 1.11x faster                                                 |
| json_loads           | 17.3 us                                                             | 15.6 us: 1.11x faster                                                 |
| unpickle             | 9.26 us                                                             | 8.39 us: 1.10x faster                                                 |
| pickle_list          | 2.89 us                                                             | 2.64 us: 1.09x faster                                                 |
| json_dumps           | 6.48 ms                                                             | 5.97 ms: 1.08x faster                                                 |
| xml_etree_iterparse  | 74.2 ms                                                             | 69.2 ms: 1.07x faster                                                 |
| pickle_dict          | 18.1 us                                                             | 17.1 us: 1.06x faster                                                 |
| pickle               | 7.35 us                                                             | 7.14 us: 1.03x faster                                                 |
| unpickle_pure_python | 144 us                                                              | 149 us: 1.03x slower                                                  |
| pickle_pure_python   | 189 us                                                              | 200 us: 1.06x slower                                                  |
| Geometric mean       | (ref)                                                               | 1.08x faster                                                          |

Benchmark hidden because not significant (1): tomli_loads

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0 | bm-20221114-darwin-arm64-python-3b9d793efcfd2c00c14f-3.12.0a2-3b9d793 |
|------------------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| python_startup         | 12.1 ms                                                             | 11.4 ms: 1.07x faster                                                 |
| python_startup_no_site | 9.90 ms                                                             | 9.43 ms: 1.05x faster                                                 |
| Geometric mean         | (ref)                                                               | 1.06x faster                                                          |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0 | bm-20221114-darwin-arm64-python-3b9d793efcfd2c00c14f-3.12.0a2-3b9d793 |
|-----------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| django_template | 21.8 ms                                                             | 19.7 ms: 1.11x faster                                                 |
| mako            | 7.52 ms                                                             | 7.55 ms: 1.00x slower                                                 |
| Geometric mean  | (ref)                                                               | 1.05x faster                                                          |

All benchmarks:
===============

| Benchmark                  | bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0 | bm-20221114-darwin-arm64-python-3b9d793efcfd2c00c14f-3.12.0a2-3b9d793 |
|----------------------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| async_generators           | 306 ms                                                              | 203 ms: 1.51x faster                                                  |
| xml_etree_generate         | 55.8 ms                                                             | 46.0 ms: 1.21x faster                                                 |
| telco                      | 3.79 ms                                                             | 3.15 ms: 1.20x faster                                                 |
| scimark_sparse_mat_mult    | 3.14 ms                                                             | 2.64 ms: 1.19x faster                                                 |
| unpickle_list              | 3.20 us                                                             | 2.73 us: 1.17x faster                                                 |
| sqlite_synth               | 1.60 us                                                             | 1.42 us: 1.13x faster                                                 |
| xml_etree_process          | 38.6 ms                                                             | 34.2 ms: 1.13x faster                                                 |
| json                       | 3.11 ms                                                             | 2.79 ms: 1.12x faster                                                 |
| sqlglot_optimize           | 34.3 ms                                                             | 30.7 ms: 1.12x faster                                                 |
| raytrace                   | 245 ms                                                              | 220 ms: 1.12x faster                                                  |
| sqlglot_normalize          | 186 ms                                                              | 167 ms: 1.11x faster                                                  |
| xml_etree_parse            | 106 ms                                                              | 95.4 ms: 1.11x faster                                                 |
| json_loads                 | 17.3 us                                                             | 15.6 us: 1.11x faster                                                 |
| bench_mp_pool              | 46.8 ms                                                             | 42.2 ms: 1.11x faster                                                 |
| django_template            | 21.8 ms                                                             | 19.7 ms: 1.11x faster                                                 |
| unpickle                   | 9.26 us                                                             | 8.39 us: 1.10x faster                                                 |
| pickle_list                | 2.89 us                                                             | 2.64 us: 1.09x faster                                                 |
| bench_thread_pool          | 503 us                                                              | 463 us: 1.09x faster                                                  |
| json_dumps                 | 6.48 ms                                                             | 5.97 ms: 1.08x faster                                                 |
| xml_etree_iterparse        | 74.2 ms                                                             | 69.2 ms: 1.07x faster                                                 |
| python_startup             | 12.1 ms                                                             | 11.4 ms: 1.07x faster                                                 |
| docutils                   | 1.53 sec                                                            | 1.43 sec: 1.07x faster                                                |
| scimark_lu                 | 71.4 ms                                                             | 67.0 ms: 1.07x faster                                                 |
| scimark_fft                | 198 ms                                                              | 186 ms: 1.06x faster                                                  |
| 2to3                       | 170 ms                                                              | 160 ms: 1.06x faster                                                  |
| pathlib                    | 24.4 ms                                                             | 23.1 ms: 1.06x faster                                                 |
| deepcopy_reduce            | 2.03 us                                                             | 1.92 us: 1.06x faster                                                 |
| crypto_pyaes               | 51.8 ms                                                             | 49.0 ms: 1.06x faster                                                 |
| regex_effbot               | 2.58 ms                                                             | 2.44 ms: 1.06x faster                                                 |
| pickle_dict                | 18.1 us                                                             | 17.1 us: 1.06x faster                                                 |
| chameleon                  | 4.51 ms                                                             | 4.29 ms: 1.05x faster                                                 |
| spectral_norm              | 74.6 ms                                                             | 70.9 ms: 1.05x faster                                                 |
| python_startup_no_site     | 9.90 ms                                                             | 9.43 ms: 1.05x faster                                                 |
| logging_simple             | 3.70 us                                                             | 3.53 us: 1.05x faster                                                 |
| sympy_expand               | 250 ms                                                              | 238 ms: 1.05x faster                                                  |
| regex_v8                   | 15.6 ms                                                             | 15.0 ms: 1.05x faster                                                 |
| logging_format             | 3.98 us                                                             | 3.82 us: 1.04x faster                                                 |
| regex_compile              | 75.8 ms                                                             | 72.7 ms: 1.04x faster                                                 |
| dulwich_log                | 29.8 ms                                                             | 28.7 ms: 1.04x faster                                                 |
| logging_silent             | 67.8 ns                                                             | 65.2 ns: 1.04x faster                                                 |
| float                      | 58.0 ms                                                             | 56.0 ms: 1.04x faster                                                 |
| regex_dna                  | 152 ms                                                              | 147 ms: 1.04x faster                                                  |
| sympy_str                  | 151 ms                                                              | 146 ms: 1.03x faster                                                  |
| pickle                     | 7.35 us                                                             | 7.14 us: 1.03x faster                                                 |
| create_gc_cycles           | 702 us                                                              | 683 us: 1.03x faster                                                  |
| richards                   | 31.0 ms                                                             | 30.2 ms: 1.03x faster                                                 |
| pprint_safe_repr           | 492 ms                                                              | 483 ms: 1.02x faster                                                  |
| nqueens                    | 59.6 ms                                                             | 58.8 ms: 1.01x faster                                                 |
| pycparser                  | 667 ms                                                              | 660 ms: 1.01x faster                                                  |
| sympy_integrate            | 11.3 ms                                                             | 11.2 ms: 1.01x faster                                                 |
| pidigits                   | 282 ms                                                              | 280 ms: 1.01x faster                                                  |
| fannkuch                   | 262 ms                                                              | 260 ms: 1.01x faster                                                  |
| pprint_pformat             | 1.00 sec                                                            | 998 ms: 1.00x faster                                                  |
| gc_traversal               | 2.40 ms                                                             | 2.39 ms: 1.00x faster                                                 |
| pyflate                    | 328 ms                                                              | 329 ms: 1.00x slower                                                  |
| mako                       | 7.52 ms                                                             | 7.55 ms: 1.00x slower                                                 |
| deepcopy                   | 224 us                                                              | 225 us: 1.01x slower                                                  |
| comprehensions             | 15.7 us                                                             | 15.9 us: 1.01x slower                                                 |
| async_tree_cpu_io_mixed_tg | 530 ms                                                              | 539 ms: 1.02x slower                                                  |
| deltablue                  | 2.59 ms                                                             | 2.67 ms: 1.03x slower                                                 |
| unpickle_pure_python       | 144 us                                                              | 149 us: 1.03x slower                                                  |
| meteor_contest             | 72.9 ms                                                             | 75.6 ms: 1.04x slower                                                 |
| async_tree_none_tg         | 252 ms                                                              | 262 ms: 1.04x slower                                                  |
| sqlglot_transpile          | 1.07 ms                                                             | 1.12 ms: 1.04x slower                                                 |
| mdp                        | 1.67 sec                                                            | 1.74 sec: 1.04x slower                                                |
| sympy_sum                  | 79.1 ms                                                             | 82.6 ms: 1.04x slower                                                 |
| scimark_monte_carlo        | 50.0 ms                                                             | 52.5 ms: 1.05x slower                                                 |
| richards_super             | 34.9 ms                                                             | 36.7 ms: 1.05x slower                                                 |
| async_tree_io_tg           | 664 ms                                                              | 703 ms: 1.06x slower                                                  |
| pickle_pure_python         | 189 us                                                              | 200 us: 1.06x slower                                                  |
| coroutines                 | 18.2 ms                                                             | 19.3 ms: 1.06x slower                                                 |
| async_tree_memoization_tg  | 316 ms                                                              | 336 ms: 1.06x slower                                                  |
| sqlglot_parse              | 895 us                                                              | 954 us: 1.07x slower                                                  |
| async_tree_memoization     | 306 ms                                                              | 329 ms: 1.08x slower                                                  |
| go                         | 106 ms                                                              | 115 ms: 1.08x slower                                                  |
| async_tree_none            | 258 ms                                                              | 281 ms: 1.09x slower                                                  |
| scimark_sor                | 93.8 ms                                                             | 103 ms: 1.10x slower                                                  |
| deepcopy_memo              | 24.6 us                                                             | 27.1 us: 1.10x slower                                                 |
| async_tree_io              | 659 ms                                                              | 725 ms: 1.10x slower                                                  |
| chaos                      | 44.6 ms                                                             | 49.7 ms: 1.11x slower                                                 |
| asyncio_tcp_ssl            | 1.26 sec                                                            | 1.43 sec: 1.13x slower                                                |
| hexiom                     | 4.24 ms                                                             | 4.83 ms: 1.14x slower                                                 |
| unpack_sequence            | 28.7 ns                                                             | 33.8 ns: 1.18x slower                                                 |
| generators                 | 28.6 ms                                                             | 36.6 ms: 1.28x slower                                                 |
| dask                       | 224 ms                                                              | 320 ms: 1.43x slower                                                  |
| asyncio_tcp                | 419 ms                                                              | 658 ms: 1.57x slower                                                  |
| typing_runtime_protocols   | 90.6 us                                                             | 325 us: 3.59x slower                                                  |
| Geometric mean             | (ref)                                                               | 1.00x slower                                                          |

Benchmark hidden because not significant (5): asyncio_websockets, tomli_loads, nbody, tornado_http, async_tree_cpu_io_mixed
Ignored benchmarks (6) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0.json: aiohttp, coverage, gunicorn, mypy2, sqlalchemy_declarative, sqlalchemy_imperative
Ignored benchmarks (4) of results/bm-20221114-3.12.0a2-3b9d793/bm-20221114-darwin-arm64-python-3b9d793efcfd2c00c14f-3.12.0a2-3b9d793.json: genshi_text, genshi_xml, html5lib, thrift


# HPT report

- Reliability score: 88.85% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
