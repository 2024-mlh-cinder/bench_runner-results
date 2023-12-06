
# Results vs. 3.12.0

- fork: python
- ref: b861ba4a8247af8159df
- machine: darwin-arm64
- commit hash: b861ba4
- commit date: 2023-04-04
- overall geometric mean: 1.03x slower
- HPT reliability: 93.96%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0 | bm-20230404-darwin-arm64-python-b861ba4a8247af8159df-3.12.0a7-b861ba4 |
|----------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| 2to3           | 170 ms                                                              | 170 ms: 1.00x slower                                                  |
| chameleon      | 4.51 ms                                                             | 4.73 ms: 1.05x slower                                                 |
| docutils       | 1.53 sec                                                            | 1.51 sec: 1.02x faster                                                |
| Geometric mean | (ref)                                                               | 1.01x slower                                                          |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0 | bm-20230404-darwin-arm64-python-b861ba4a8247af8159df-3.12.0a7-b861ba4 |
|----------------------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| async_tree_cpu_io_mixed_tg | 530 ms                                                              | 548 ms: 1.03x slower                                                  |
| async_tree_cpu_io_mixed    | 520 ms                                                              | 537 ms: 1.03x slower                                                  |
| async_tree_memoization     | 306 ms                                                              | 325 ms: 1.06x slower                                                  |
| async_tree_none_tg         | 252 ms                                                              | 271 ms: 1.08x slower                                                  |
| async_tree_memoization_tg  | 316 ms                                                              | 343 ms: 1.09x slower                                                  |
| async_tree_io_tg           | 664 ms                                                              | 721 ms: 1.09x slower                                                  |
| async_tree_none            | 258 ms                                                              | 288 ms: 1.12x slower                                                  |
| async_tree_io              | 659 ms                                                              | 740 ms: 1.12x slower                                                  |
| Geometric mean             | (ref)                                                               | 1.08x slower                                                          |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0 | bm-20230404-darwin-arm64-python-b861ba4a8247af8159df-3.12.0a7-b861ba4 |
|----------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| nbody          | 68.8 ms                                                             | 64.0 ms: 1.08x faster                                                 |
| float          | 58.0 ms                                                             | 54.3 ms: 1.07x faster                                                 |
| pidigits       | 282 ms                                                              | 282 ms: 1.00x faster                                                  |
| Geometric mean | (ref)                                                               | 1.05x faster                                                          |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0 | bm-20230404-darwin-arm64-python-b861ba4a8247af8159df-3.12.0a7-b861ba4 |
|----------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| regex_effbot   | 2.58 ms                                                             | 2.46 ms: 1.05x faster                                                 |
| regex_v8       | 15.6 ms                                                             | 15.2 ms: 1.03x faster                                                 |
| regex_dna      | 152 ms                                                              | 148 ms: 1.02x faster                                                  |
| regex_compile  | 75.8 ms                                                             | 78.7 ms: 1.04x slower                                                 |
| Geometric mean | (ref)                                                               | 1.02x faster                                                          |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0 | bm-20230404-darwin-arm64-python-b861ba4a8247af8159df-3.12.0a7-b861ba4 |
|----------------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| unpickle_list        | 3.20 us                                                             | 2.70 us: 1.19x faster                                                 |
| xml_etree_generate   | 55.8 ms                                                             | 49.6 ms: 1.12x faster                                                 |
| unpickle             | 9.26 us                                                             | 8.39 us: 1.10x faster                                                 |
| json_loads           | 17.3 us                                                             | 15.8 us: 1.10x faster                                                 |
| json_dumps           | 6.48 ms                                                             | 6.01 ms: 1.08x faster                                                 |
| xml_etree_parse      | 106 ms                                                              | 98.6 ms: 1.08x faster                                                 |
| pickle_list          | 2.89 us                                                             | 2.76 us: 1.05x faster                                                 |
| pickle_dict          | 18.1 us                                                             | 17.3 us: 1.04x faster                                                 |
| pickle               | 7.35 us                                                             | 7.16 us: 1.03x faster                                                 |
| xml_etree_iterparse  | 74.2 ms                                                             | 73.5 ms: 1.01x faster                                                 |
| xml_etree_process    | 38.6 ms                                                             | 39.0 ms: 1.01x slower                                                 |
| tomli_loads          | 1.40 sec                                                            | 1.43 sec: 1.02x slower                                                |
| pickle_pure_python   | 189 us                                                              | 206 us: 1.09x slower                                                  |
| unpickle_pure_python | 144 us                                                              | 158 us: 1.09x slower                                                  |
| Geometric mean       | (ref)                                                               | 1.04x faster                                                          |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0 | bm-20230404-darwin-arm64-python-b861ba4a8247af8159df-3.12.0a7-b861ba4 |
|------------------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| python_startup_no_site | 9.90 ms                                                             | 9.57 ms: 1.04x faster                                                 |
| python_startup         | 12.1 ms                                                             | 11.8 ms: 1.03x faster                                                 |
| Geometric mean         | (ref)                                                               | 1.03x faster                                                          |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0 | bm-20230404-darwin-arm64-python-b861ba4a8247af8159df-3.12.0a7-b861ba4 |
|-----------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| mako            | 7.52 ms                                                             | 7.17 ms: 1.05x faster                                                 |
| django_template | 21.8 ms                                                             | 22.2 ms: 1.01x slower                                                 |
| Geometric mean  | (ref)                                                               | 1.02x faster                                                          |

All benchmarks:
===============

| Benchmark                  | bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0 | bm-20230404-darwin-arm64-python-b861ba4a8247af8159df-3.12.0a7-b861ba4 |
|----------------------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| sqlite_synth               | 1.60 us                                                             | 1.34 us: 1.20x faster                                                 |
| unpickle_list              | 3.20 us                                                             | 2.70 us: 1.19x faster                                                 |
| async_generators           | 306 ms                                                              | 260 ms: 1.18x faster                                                  |
| scimark_sparse_mat_mult    | 3.14 ms                                                             | 2.72 ms: 1.16x faster                                                 |
| telco                      | 3.79 ms                                                             | 3.27 ms: 1.16x faster                                                 |
| xml_etree_generate         | 55.8 ms                                                             | 49.6 ms: 1.12x faster                                                 |
| scimark_fft                | 198 ms                                                              | 177 ms: 1.12x faster                                                  |
| json                       | 3.11 ms                                                             | 2.80 ms: 1.11x faster                                                 |
| unpickle                   | 9.26 us                                                             | 8.39 us: 1.10x faster                                                 |
| json_loads                 | 17.3 us                                                             | 15.8 us: 1.10x faster                                                 |
| raytrace                   | 245 ms                                                              | 223 ms: 1.10x faster                                                  |
| json_dumps                 | 6.48 ms                                                             | 6.01 ms: 1.08x faster                                                 |
| nbody                      | 68.8 ms                                                             | 64.0 ms: 1.08x faster                                                 |
| xml_etree_parse            | 106 ms                                                              | 98.6 ms: 1.08x faster                                                 |
| float                      | 58.0 ms                                                             | 54.3 ms: 1.07x faster                                                 |
| regex_effbot               | 2.58 ms                                                             | 2.46 ms: 1.05x faster                                                 |
| mako                       | 7.52 ms                                                             | 7.17 ms: 1.05x faster                                                 |
| pickle_list                | 2.89 us                                                             | 2.76 us: 1.05x faster                                                 |
| sqlalchemy_declarative     | 65.4 ms                                                             | 62.6 ms: 1.04x faster                                                 |
| pickle_dict                | 18.1 us                                                             | 17.3 us: 1.04x faster                                                 |
| sqlglot_optimize           | 34.3 ms                                                             | 33.0 ms: 1.04x faster                                                 |
| python_startup_no_site     | 9.90 ms                                                             | 9.57 ms: 1.04x faster                                                 |
| scimark_sor                | 93.8 ms                                                             | 90.7 ms: 1.03x faster                                                 |
| mdp                        | 1.67 sec                                                            | 1.62 sec: 1.03x faster                                                |
| regex_v8                   | 15.6 ms                                                             | 15.2 ms: 1.03x faster                                                 |
| bench_mp_pool              | 46.8 ms                                                             | 45.4 ms: 1.03x faster                                                 |
| sqlglot_normalize          | 186 ms                                                              | 181 ms: 1.03x faster                                                  |
| python_startup             | 12.1 ms                                                             | 11.8 ms: 1.03x faster                                                 |
| pickle                     | 7.35 us                                                             | 7.16 us: 1.03x faster                                                 |
| regex_dna                  | 152 ms                                                              | 148 ms: 1.02x faster                                                  |
| dulwich_log                | 29.8 ms                                                             | 29.3 ms: 1.02x faster                                                 |
| docutils                   | 1.53 sec                                                            | 1.51 sec: 1.02x faster                                                |
| sympy_expand               | 250 ms                                                              | 246 ms: 1.01x faster                                                  |
| xml_etree_iterparse        | 74.2 ms                                                             | 73.5 ms: 1.01x faster                                                 |
| meteor_contest             | 72.9 ms                                                             | 72.3 ms: 1.01x faster                                                 |
| fannkuch                   | 262 ms                                                              | 260 ms: 1.01x faster                                                  |
| bench_thread_pool          | 503 us                                                              | 498 us: 1.01x faster                                                  |
| create_gc_cycles           | 702 us                                                              | 698 us: 1.01x faster                                                  |
| pidigits                   | 282 ms                                                              | 282 ms: 1.00x faster                                                  |
| 2to3                       | 170 ms                                                              | 170 ms: 1.00x slower                                                  |
| deepcopy_reduce            | 2.03 us                                                             | 2.04 us: 1.00x slower                                                 |
| sympy_str                  | 151 ms                                                              | 152 ms: 1.01x slower                                                  |
| pyflate                    | 328 ms                                                              | 332 ms: 1.01x slower                                                  |
| xml_etree_process          | 38.6 ms                                                             | 39.0 ms: 1.01x slower                                                 |
| crypto_pyaes               | 51.8 ms                                                             | 52.4 ms: 1.01x slower                                                 |
| pycparser                  | 667 ms                                                              | 676 ms: 1.01x slower                                                  |
| django_template            | 21.8 ms                                                             | 22.2 ms: 1.01x slower                                                 |
| scimark_monte_carlo        | 50.0 ms                                                             | 51.1 ms: 1.02x slower                                                 |
| nqueens                    | 59.6 ms                                                             | 61.1 ms: 1.02x slower                                                 |
| tomli_loads                | 1.40 sec                                                            | 1.43 sec: 1.02x slower                                                |
| pprint_safe_repr           | 492 ms                                                              | 505 ms: 1.03x slower                                                  |
| pprint_pformat             | 1.00 sec                                                            | 1.03 sec: 1.03x slower                                                |
| sqlalchemy_imperative      | 6.92 ms                                                             | 7.13 ms: 1.03x slower                                                 |
| async_tree_cpu_io_mixed_tg | 530 ms                                                              | 548 ms: 1.03x slower                                                  |
| async_tree_cpu_io_mixed    | 520 ms                                                              | 537 ms: 1.03x slower                                                  |
| regex_compile              | 75.8 ms                                                             | 78.7 ms: 1.04x slower                                                 |
| asyncio_tcp_ssl            | 1.26 sec                                                            | 1.31 sec: 1.04x slower                                                |
| sympy_integrate            | 11.3 ms                                                             | 11.8 ms: 1.04x slower                                                 |
| chameleon                  | 4.51 ms                                                             | 4.73 ms: 1.05x slower                                                 |
| deepcopy                   | 224 us                                                              | 236 us: 1.05x slower                                                  |
| logging_format             | 3.98 us                                                             | 4.21 us: 1.06x slower                                                 |
| logging_simple             | 3.70 us                                                             | 3.93 us: 1.06x slower                                                 |
| async_tree_memoization     | 306 ms                                                              | 325 ms: 1.06x slower                                                  |
| deltablue                  | 2.59 ms                                                             | 2.77 ms: 1.07x slower                                                 |
| async_tree_none_tg         | 252 ms                                                              | 271 ms: 1.08x slower                                                  |
| chaos                      | 44.6 ms                                                             | 48.1 ms: 1.08x slower                                                 |
| spectral_norm              | 74.6 ms                                                             | 80.5 ms: 1.08x slower                                                 |
| comprehensions             | 15.7 us                                                             | 17.0 us: 1.08x slower                                                 |
| hexiom                     | 4.24 ms                                                             | 4.60 ms: 1.08x slower                                                 |
| async_tree_memoization_tg  | 316 ms                                                              | 343 ms: 1.09x slower                                                  |
| sympy_sum                  | 79.1 ms                                                             | 85.9 ms: 1.09x slower                                                 |
| async_tree_io_tg           | 664 ms                                                              | 721 ms: 1.09x slower                                                  |
| pickle_pure_python         | 189 us                                                              | 206 us: 1.09x slower                                                  |
| unpickle_pure_python       | 144 us                                                              | 158 us: 1.09x slower                                                  |
| go                         | 106 ms                                                              | 117 ms: 1.10x slower                                                  |
| async_tree_none            | 258 ms                                                              | 288 ms: 1.12x slower                                                  |
| async_tree_io              | 659 ms                                                              | 740 ms: 1.12x slower                                                  |
| deepcopy_memo              | 24.6 us                                                             | 27.9 us: 1.14x slower                                                 |
| richards                   | 31.0 ms                                                             | 35.3 ms: 1.14x slower                                                 |
| logging_silent             | 67.8 ns                                                             | 77.7 ns: 1.15x slower                                                 |
| sqlglot_transpile          | 1.07 ms                                                             | 1.24 ms: 1.15x slower                                                 |
| unpack_sequence            | 28.7 ns                                                             | 33.6 ns: 1.17x slower                                                 |
| coroutines                 | 18.2 ms                                                             | 21.4 ms: 1.18x slower                                                 |
| scimark_lu                 | 71.4 ms                                                             | 84.7 ms: 1.19x slower                                                 |
| sqlglot_parse              | 895 us                                                              | 1.07 ms: 1.19x slower                                                 |
| richards_super             | 34.9 ms                                                             | 42.3 ms: 1.21x slower                                                 |
| generators                 | 28.6 ms                                                             | 35.4 ms: 1.24x slower                                                 |
| typing_runtime_protocols   | 90.6 us                                                             | 392 us: 4.32x slower                                                  |
| Geometric mean             | (ref)                                                               | 1.03x slower                                                          |

Benchmark hidden because not significant (7): dask, asyncio_websockets, gc_traversal, pathlib, tornado_http, asyncio_tcp, mypy2
Ignored benchmarks (3) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0.json: aiohttp, coverage, gunicorn
Ignored benchmarks (4) of results/bm-20230404-3.12.0a7-b861ba4/bm-20230404-darwin-arm64-python-b861ba4a8247af8159df-3.12.0a7-b861ba4.json: genshi_text, genshi_xml, html5lib, thrift


# HPT report

- Reliability score: 93.96% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
