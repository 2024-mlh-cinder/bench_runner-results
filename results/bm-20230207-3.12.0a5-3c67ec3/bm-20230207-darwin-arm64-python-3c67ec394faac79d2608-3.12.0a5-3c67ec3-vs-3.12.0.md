
# Results vs. 3.12.0

- fork: python
- ref: 3c67ec394faac79d2608
- machine: darwin-arm64
- commit hash: 3c67ec3
- commit date: 2023-02-07
- overall geometric mean: 1.03x slower
- HPT reliability: 75.67%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0 | bm-20230207-darwin-arm64-python-3c67ec394faac79d2608-3.12.0a5-3c67ec3 |
|----------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| 2to3           | 170 ms                                                              | 166 ms: 1.02x faster                                                  |
| chameleon      | 4.51 ms                                                             | 4.69 ms: 1.04x slower                                                 |
| docutils       | 1.53 sec                                                            | 1.48 sec: 1.03x faster                                                |
| Geometric mean | (ref)                                                               | 1.00x slower                                                          |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0 | bm-20230207-darwin-arm64-python-3c67ec394faac79d2608-3.12.0a5-3c67ec3 |
|----------------------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| async_tree_cpu_io_mixed    | 520 ms                                                              | 533 ms: 1.02x slower                                                  |
| async_tree_cpu_io_mixed_tg | 530 ms                                                              | 555 ms: 1.05x slower                                                  |
| async_tree_memoization     | 306 ms                                                              | 336 ms: 1.10x slower                                                  |
| async_tree_memoization_tg  | 316 ms                                                              | 351 ms: 1.11x slower                                                  |
| async_tree_io_tg           | 664 ms                                                              | 739 ms: 1.11x slower                                                  |
| async_tree_none_tg         | 252 ms                                                              | 281 ms: 1.12x slower                                                  |
| async_tree_none            | 258 ms                                                              | 290 ms: 1.12x slower                                                  |
| async_tree_io              | 659 ms                                                              | 753 ms: 1.14x slower                                                  |
| Geometric mean             | (ref)                                                               | 1.10x slower                                                          |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0 | bm-20230207-darwin-arm64-python-3c67ec394faac79d2608-3.12.0a5-3c67ec3 |
|----------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| float          | 58.0 ms                                                             | 57.5 ms: 1.01x faster                                                 |
| pidigits       | 282 ms                                                              | 281 ms: 1.00x faster                                                  |
| nbody          | 68.8 ms                                                             | 68.5 ms: 1.00x faster                                                 |
| Geometric mean | (ref)                                                               | 1.01x faster                                                          |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0 | bm-20230207-darwin-arm64-python-3c67ec394faac79d2608-3.12.0a5-3c67ec3 |
|----------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| regex_effbot   | 2.58 ms                                                             | 2.45 ms: 1.05x faster                                                 |
| regex_dna      | 152 ms                                                              | 147 ms: 1.03x faster                                                  |
| regex_v8       | 15.6 ms                                                             | 15.3 ms: 1.02x faster                                                 |
| regex_compile  | 75.8 ms                                                             | 76.0 ms: 1.00x slower                                                 |
| Geometric mean | (ref)                                                               | 1.03x faster                                                          |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0 | bm-20230207-darwin-arm64-python-3c67ec394faac79d2608-3.12.0a5-3c67ec3 |
|----------------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| xml_etree_generate   | 55.8 ms                                                             | 48.7 ms: 1.15x faster                                                 |
| unpickle_list        | 3.20 us                                                             | 2.85 us: 1.12x faster                                                 |
| xml_etree_parse      | 106 ms                                                              | 95.0 ms: 1.12x faster                                                 |
| json_loads           | 17.3 us                                                             | 15.7 us: 1.10x faster                                                 |
| unpickle             | 9.26 us                                                             | 8.50 us: 1.09x faster                                                 |
| pickle_dict          | 18.1 us                                                             | 16.8 us: 1.07x faster                                                 |
| json_dumps           | 6.48 ms                                                             | 6.08 ms: 1.07x faster                                                 |
| pickle_list          | 2.89 us                                                             | 2.72 us: 1.06x faster                                                 |
| xml_etree_process    | 38.6 ms                                                             | 37.1 ms: 1.04x faster                                                 |
| pickle               | 7.35 us                                                             | 7.09 us: 1.04x faster                                                 |
| xml_etree_iterparse  | 74.2 ms                                                             | 71.9 ms: 1.03x faster                                                 |
| tomli_loads          | 1.40 sec                                                            | 1.38 sec: 1.02x faster                                                |
| unpickle_pure_python | 144 us                                                              | 161 us: 1.11x slower                                                  |
| pickle_pure_python   | 189 us                                                              | 214 us: 1.13x slower                                                  |
| Geometric mean       | (ref)                                                               | 1.05x faster                                                          |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0 | bm-20230207-darwin-arm64-python-3c67ec394faac79d2608-3.12.0a5-3c67ec3 |
|------------------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| python_startup_no_site | 9.90 ms                                                             | 9.55 ms: 1.04x faster                                                 |
| python_startup         | 12.1 ms                                                             | 11.8 ms: 1.03x faster                                                 |
| Geometric mean         | (ref)                                                               | 1.03x faster                                                          |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0 | bm-20230207-darwin-arm64-python-3c67ec394faac79d2608-3.12.0a5-3c67ec3 |
|-----------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| mako            | 7.52 ms                                                             | 6.94 ms: 1.08x faster                                                 |
| django_template | 21.8 ms                                                             | 22.5 ms: 1.03x slower                                                 |
| Geometric mean  | (ref)                                                               | 1.02x faster                                                          |

All benchmarks:
===============

| Benchmark                  | bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0 | bm-20230207-darwin-arm64-python-3c67ec394faac79d2608-3.12.0a5-3c67ec3 |
|----------------------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| async_generators           | 306 ms                                                              | 209 ms: 1.46x faster                                                  |
| telco                      | 3.79 ms                                                             | 3.18 ms: 1.19x faster                                                 |
| scimark_sparse_mat_mult    | 3.14 ms                                                             | 2.70 ms: 1.16x faster                                                 |
| sqlite_synth               | 1.60 us                                                             | 1.40 us: 1.15x faster                                                 |
| xml_etree_generate         | 55.8 ms                                                             | 48.7 ms: 1.15x faster                                                 |
| unpickle_list              | 3.20 us                                                             | 2.85 us: 1.12x faster                                                 |
| json                       | 3.11 ms                                                             | 2.79 ms: 1.12x faster                                                 |
| xml_etree_parse            | 106 ms                                                              | 95.0 ms: 1.12x faster                                                 |
| json_loads                 | 17.3 us                                                             | 15.7 us: 1.10x faster                                                 |
| unpickle                   | 9.26 us                                                             | 8.50 us: 1.09x faster                                                 |
| comprehensions             | 15.7 us                                                             | 14.5 us: 1.09x faster                                                 |
| mako                       | 7.52 ms                                                             | 6.94 ms: 1.08x faster                                                 |
| scimark_fft                | 198 ms                                                              | 183 ms: 1.08x faster                                                  |
| pickle_dict                | 18.1 us                                                             | 16.8 us: 1.07x faster                                                 |
| raytrace                   | 245 ms                                                              | 229 ms: 1.07x faster                                                  |
| bench_mp_pool              | 46.8 ms                                                             | 43.7 ms: 1.07x faster                                                 |
| json_dumps                 | 6.48 ms                                                             | 6.08 ms: 1.07x faster                                                 |
| fannkuch                   | 262 ms                                                              | 246 ms: 1.06x faster                                                  |
| pickle_list                | 2.89 us                                                             | 2.72 us: 1.06x faster                                                 |
| regex_effbot               | 2.58 ms                                                             | 2.45 ms: 1.05x faster                                                 |
| pathlib                    | 24.4 ms                                                             | 23.2 ms: 1.05x faster                                                 |
| sqlalchemy_declarative     | 65.4 ms                                                             | 62.6 ms: 1.04x faster                                                 |
| xml_etree_process          | 38.6 ms                                                             | 37.1 ms: 1.04x faster                                                 |
| python_startup_no_site     | 9.90 ms                                                             | 9.55 ms: 1.04x faster                                                 |
| sqlglot_optimize           | 34.3 ms                                                             | 33.1 ms: 1.04x faster                                                 |
| pickle                     | 7.35 us                                                             | 7.09 us: 1.04x faster                                                 |
| scimark_sor                | 93.8 ms                                                             | 90.7 ms: 1.03x faster                                                 |
| regex_dna                  | 152 ms                                                              | 147 ms: 1.03x faster                                                  |
| xml_etree_iterparse        | 74.2 ms                                                             | 71.9 ms: 1.03x faster                                                 |
| docutils                   | 1.53 sec                                                            | 1.48 sec: 1.03x faster                                                |
| python_startup             | 12.1 ms                                                             | 11.8 ms: 1.03x faster                                                 |
| sqlglot_normalize          | 186 ms                                                              | 181 ms: 1.03x faster                                                  |
| 2to3                       | 170 ms                                                              | 166 ms: 1.02x faster                                                  |
| regex_v8                   | 15.6 ms                                                             | 15.3 ms: 1.02x faster                                                 |
| sympy_str                  | 151 ms                                                              | 148 ms: 1.02x faster                                                  |
| create_gc_cycles           | 702 us                                                              | 687 us: 1.02x faster                                                  |
| dulwich_log                | 29.8 ms                                                             | 29.2 ms: 1.02x faster                                                 |
| sympy_expand               | 250 ms                                                              | 245 ms: 1.02x faster                                                  |
| bench_thread_pool          | 503 us                                                              | 495 us: 1.02x faster                                                  |
| tomli_loads                | 1.40 sec                                                            | 1.38 sec: 1.02x faster                                                |
| pyflate                    | 328 ms                                                              | 324 ms: 1.01x faster                                                  |
| float                      | 58.0 ms                                                             | 57.5 ms: 1.01x faster                                                 |
| gc_traversal               | 2.40 ms                                                             | 2.39 ms: 1.00x faster                                                 |
| pidigits                   | 282 ms                                                              | 281 ms: 1.00x faster                                                  |
| crypto_pyaes               | 51.8 ms                                                             | 51.6 ms: 1.00x faster                                                 |
| nbody                      | 68.8 ms                                                             | 68.5 ms: 1.00x faster                                                 |
| regex_compile              | 75.8 ms                                                             | 76.0 ms: 1.00x slower                                                 |
| nqueens                    | 59.6 ms                                                             | 59.9 ms: 1.00x slower                                                 |
| asyncio_tcp_ssl            | 1.26 sec                                                            | 1.28 sec: 1.01x slower                                                |
| sympy_integrate            | 11.3 ms                                                             | 11.5 ms: 1.02x slower                                                 |
| async_tree_cpu_io_mixed    | 520 ms                                                              | 533 ms: 1.02x slower                                                  |
| django_template            | 21.8 ms                                                             | 22.5 ms: 1.03x slower                                                 |
| chameleon                  | 4.51 ms                                                             | 4.69 ms: 1.04x slower                                                 |
| sympy_sum                  | 79.1 ms                                                             | 82.4 ms: 1.04x slower                                                 |
| async_tree_cpu_io_mixed_tg | 530 ms                                                              | 555 ms: 1.05x slower                                                  |
| mdp                        | 1.67 sec                                                            | 1.76 sec: 1.05x slower                                                |
| logging_simple             | 3.70 us                                                             | 3.89 us: 1.05x slower                                                 |
| logging_format             | 3.98 us                                                             | 4.21 us: 1.06x slower                                                 |
| deepcopy_reduce            | 2.03 us                                                             | 2.15 us: 1.06x slower                                                 |
| sqlalchemy_imperative      | 6.92 ms                                                             | 7.32 ms: 1.06x slower                                                 |
| scimark_monte_carlo        | 50.0 ms                                                             | 52.9 ms: 1.06x slower                                                 |
| meteor_contest             | 72.9 ms                                                             | 77.2 ms: 1.06x slower                                                 |
| go                         | 106 ms                                                              | 113 ms: 1.07x slower                                                  |
| pprint_safe_repr           | 492 ms                                                              | 524 ms: 1.07x slower                                                  |
| pprint_pformat             | 1.00 sec                                                            | 1.07 sec: 1.07x slower                                                |
| richards                   | 31.0 ms                                                             | 33.5 ms: 1.08x slower                                                 |
| deltablue                  | 2.59 ms                                                             | 2.81 ms: 1.08x slower                                                 |
| chaos                      | 44.6 ms                                                             | 48.4 ms: 1.08x slower                                                 |
| hexiom                     | 4.24 ms                                                             | 4.61 ms: 1.09x slower                                                 |
| deepcopy                   | 224 us                                                              | 246 us: 1.10x slower                                                  |
| spectral_norm              | 74.6 ms                                                             | 81.8 ms: 1.10x slower                                                 |
| async_tree_memoization     | 306 ms                                                              | 336 ms: 1.10x slower                                                  |
| async_tree_memoization_tg  | 316 ms                                                              | 351 ms: 1.11x slower                                                  |
| async_tree_io_tg           | 664 ms                                                              | 739 ms: 1.11x slower                                                  |
| unpickle_pure_python       | 144 us                                                              | 161 us: 1.11x slower                                                  |
| async_tree_none_tg         | 252 ms                                                              | 281 ms: 1.12x slower                                                  |
| async_tree_none            | 258 ms                                                              | 290 ms: 1.12x slower                                                  |
| coroutines                 | 18.2 ms                                                             | 20.6 ms: 1.13x slower                                                 |
| pickle_pure_python         | 189 us                                                              | 214 us: 1.13x slower                                                  |
| async_tree_io              | 659 ms                                                              | 753 ms: 1.14x slower                                                  |
| sqlglot_transpile          | 1.07 ms                                                             | 1.23 ms: 1.14x slower                                                 |
| richards_super             | 34.9 ms                                                             | 40.4 ms: 1.16x slower                                                 |
| deepcopy_memo              | 24.6 us                                                             | 28.6 us: 1.16x slower                                                 |
| unpack_sequence            | 28.7 ns                                                             | 33.4 ns: 1.16x slower                                                 |
| scimark_lu                 | 71.4 ms                                                             | 83.3 ms: 1.17x slower                                                 |
| sqlglot_parse              | 895 us                                                              | 1.05 ms: 1.18x slower                                                 |
| logging_silent             | 67.8 ns                                                             | 83.0 ns: 1.22x slower                                                 |
| generators                 | 28.6 ms                                                             | 38.6 ms: 1.35x slower                                                 |
| dask                       | 224 ms                                                              | 327 ms: 1.46x slower                                                  |
| typing_runtime_protocols   | 90.6 us                                                             | 319 us: 3.52x slower                                                  |
| Geometric mean             | (ref)                                                               | 1.03x slower                                                          |

Benchmark hidden because not significant (4): asyncio_websockets, pycparser, tornado_http, asyncio_tcp
Ignored benchmarks (4) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0.json: aiohttp, coverage, gunicorn, mypy2
Ignored benchmarks (4) of results/bm-20230207-3.12.0a5-3c67ec3/bm-20230207-darwin-arm64-python-3c67ec394faac79d2608-3.12.0a5-3c67ec3.json: genshi_text, genshi_xml, html5lib, thrift


# HPT report

- Reliability score: 75.67% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
