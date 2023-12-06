
# Results vs. 3.12.0

- fork: python
- ref: 3d5d3f7af6498effbc60
- machine: darwin-arm64
- commit hash: 3d5d3f7
- commit date: 2023-01-10
- overall geometric mean: 1.02x faster
- HPT reliability: 99.97%
- HPT 99th percentile: 1.01x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0 | bm-20230110-darwin-arm64-python-3d5d3f7af6498effbc60-3.12.0a4-3d5d3f7 |
|----------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| 2to3           | 170 ms                                                              | 158 ms: 1.08x faster                                                  |
| chameleon      | 4.51 ms                                                             | 4.21 ms: 1.07x faster                                                 |
| docutils       | 1.53 sec                                                            | 1.41 sec: 1.08x faster                                                |
| Geometric mean | (ref)                                                               | 1.08x faster                                                          |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0 | bm-20230110-darwin-arm64-python-3d5d3f7af6498effbc60-3.12.0a4-3d5d3f7 |
|----------------------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| async_tree_cpu_io_mixed_tg | 530 ms                                                              | 543 ms: 1.02x slower                                                  |
| async_tree_memoization     | 306 ms                                                              | 322 ms: 1.06x slower                                                  |
| async_tree_none_tg         | 252 ms                                                              | 266 ms: 1.06x slower                                                  |
| async_tree_io_tg           | 664 ms                                                              | 710 ms: 1.07x slower                                                  |
| async_tree_memoization_tg  | 316 ms                                                              | 340 ms: 1.07x slower                                                  |
| async_tree_none            | 258 ms                                                              | 280 ms: 1.08x slower                                                  |
| async_tree_io              | 659 ms                                                              | 728 ms: 1.11x slower                                                  |
| Geometric mean             | (ref)                                                               | 1.06x slower                                                          |

Benchmark hidden because not significant (1): async_tree_cpu_io_mixed

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0 | bm-20230110-darwin-arm64-python-3d5d3f7af6498effbc60-3.12.0a4-3d5d3f7 |
|----------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| float          | 58.0 ms                                                             | 55.5 ms: 1.05x faster                                                 |
| nbody          | 68.8 ms                                                             | 67.7 ms: 1.02x faster                                                 |
| pidigits       | 282 ms                                                              | 280 ms: 1.01x faster                                                  |
| Geometric mean | (ref)                                                               | 1.02x faster                                                          |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0 | bm-20230110-darwin-arm64-python-3d5d3f7af6498effbc60-3.12.0a4-3d5d3f7 |
|----------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| regex_effbot   | 2.58 ms                                                             | 2.44 ms: 1.06x faster                                                 |
| regex_compile  | 75.8 ms                                                             | 72.1 ms: 1.05x faster                                                 |
| regex_v8       | 15.6 ms                                                             | 15.0 ms: 1.04x faster                                                 |
| regex_dna      | 152 ms                                                              | 147 ms: 1.03x faster                                                  |
| Geometric mean | (ref)                                                               | 1.05x faster                                                          |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0 | bm-20230110-darwin-arm64-python-3d5d3f7af6498effbc60-3.12.0a4-3d5d3f7 |
|----------------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| xml_etree_generate   | 55.8 ms                                                             | 46.9 ms: 1.19x faster                                                 |
| xml_etree_process    | 38.6 ms                                                             | 33.8 ms: 1.14x faster                                                 |
| unpickle_list        | 3.20 us                                                             | 2.81 us: 1.14x faster                                                 |
| json_loads           | 17.3 us                                                             | 15.5 us: 1.12x faster                                                 |
| json_dumps           | 6.48 ms                                                             | 5.84 ms: 1.11x faster                                                 |
| xml_etree_parse      | 106 ms                                                              | 96.4 ms: 1.10x faster                                                 |
| unpickle             | 9.26 us                                                             | 8.43 us: 1.10x faster                                                 |
| tomli_loads          | 1.40 sec                                                            | 1.28 sec: 1.09x faster                                                |
| pickle_list          | 2.89 us                                                             | 2.70 us: 1.07x faster                                                 |
| pickle_dict          | 18.1 us                                                             | 17.0 us: 1.06x faster                                                 |
| xml_etree_iterparse  | 74.2 ms                                                             | 70.0 ms: 1.06x faster                                                 |
| pickle               | 7.35 us                                                             | 6.98 us: 1.05x faster                                                 |
| unpickle_pure_python | 144 us                                                              | 137 us: 1.05x faster                                                  |
| pickle_pure_python   | 189 us                                                              | 190 us: 1.01x slower                                                  |
| Geometric mean       | (ref)                                                               | 1.09x faster                                                          |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0 | bm-20230110-darwin-arm64-python-3d5d3f7af6498effbc60-3.12.0a4-3d5d3f7 |
|------------------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| python_startup         | 12.1 ms                                                             | 11.4 ms: 1.06x faster                                                 |
| python_startup_no_site | 9.90 ms                                                             | 9.54 ms: 1.04x faster                                                 |
| Geometric mean         | (ref)                                                               | 1.05x faster                                                          |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0 | bm-20230110-darwin-arm64-python-3d5d3f7af6498effbc60-3.12.0a4-3d5d3f7 |
|-----------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| django_template | 21.8 ms                                                             | 20.8 ms: 1.05x faster                                                 |
| mako            | 7.52 ms                                                             | 7.76 ms: 1.03x slower                                                 |
| Geometric mean  | (ref)                                                               | 1.01x faster                                                          |

All benchmarks:
===============

| Benchmark                  | bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0 | bm-20230110-darwin-arm64-python-3d5d3f7af6498effbc60-3.12.0a4-3d5d3f7 |
|----------------------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| async_generators           | 306 ms                                                              | 200 ms: 1.53x faster                                                  |
| xml_etree_generate         | 55.8 ms                                                             | 46.9 ms: 1.19x faster                                                 |
| scimark_sparse_mat_mult    | 3.14 ms                                                             | 2.66 ms: 1.18x faster                                                 |
| sqlite_synth               | 1.60 us                                                             | 1.36 us: 1.18x faster                                                 |
| raytrace                   | 245 ms                                                              | 208 ms: 1.18x faster                                                  |
| telco                      | 3.79 ms                                                             | 3.22 ms: 1.18x faster                                                 |
| sqlglot_optimize           | 34.3 ms                                                             | 30.0 ms: 1.14x faster                                                 |
| xml_etree_process          | 38.6 ms                                                             | 33.8 ms: 1.14x faster                                                 |
| unpickle_list              | 3.20 us                                                             | 2.81 us: 1.14x faster                                                 |
| sqlglot_normalize          | 186 ms                                                              | 165 ms: 1.13x faster                                                  |
| scimark_sor                | 93.8 ms                                                             | 83.4 ms: 1.12x faster                                                 |
| json_loads                 | 17.3 us                                                             | 15.5 us: 1.12x faster                                                 |
| json                       | 3.11 ms                                                             | 2.79 ms: 1.12x faster                                                 |
| json_dumps                 | 6.48 ms                                                             | 5.84 ms: 1.11x faster                                                 |
| logging_simple             | 3.70 us                                                             | 3.34 us: 1.11x faster                                                 |
| logging_format             | 3.98 us                                                             | 3.60 us: 1.11x faster                                                 |
| bench_mp_pool              | 46.8 ms                                                             | 42.5 ms: 1.10x faster                                                 |
| xml_etree_parse            | 106 ms                                                              | 96.4 ms: 1.10x faster                                                 |
| unpickle                   | 9.26 us                                                             | 8.43 us: 1.10x faster                                                 |
| bench_thread_pool          | 503 us                                                              | 460 us: 1.09x faster                                                  |
| pyflate                    | 328 ms                                                              | 301 ms: 1.09x faster                                                  |
| tomli_loads                | 1.40 sec                                                            | 1.28 sec: 1.09x faster                                                |
| scimark_fft                | 198 ms                                                              | 182 ms: 1.08x faster                                                  |
| sympy_expand               | 250 ms                                                              | 230 ms: 1.08x faster                                                  |
| docutils                   | 1.53 sec                                                            | 1.41 sec: 1.08x faster                                                |
| 2to3                       | 170 ms                                                              | 158 ms: 1.08x faster                                                  |
| fannkuch                   | 262 ms                                                              | 244 ms: 1.08x faster                                                  |
| chameleon                  | 4.51 ms                                                             | 4.21 ms: 1.07x faster                                                 |
| scimark_monte_carlo        | 50.0 ms                                                             | 46.8 ms: 1.07x faster                                                 |
| pickle_list                | 2.89 us                                                             | 2.70 us: 1.07x faster                                                 |
| python_startup             | 12.1 ms                                                             | 11.4 ms: 1.06x faster                                                 |
| pickle_dict                | 18.1 us                                                             | 17.0 us: 1.06x faster                                                 |
| xml_etree_iterparse        | 74.2 ms                                                             | 70.0 ms: 1.06x faster                                                 |
| scimark_lu                 | 71.4 ms                                                             | 67.3 ms: 1.06x faster                                                 |
| logging_silent             | 67.8 ns                                                             | 63.9 ns: 1.06x faster                                                 |
| regex_effbot               | 2.58 ms                                                             | 2.44 ms: 1.06x faster                                                 |
| spectral_norm              | 74.6 ms                                                             | 70.6 ms: 1.06x faster                                                 |
| dulwich_log                | 29.8 ms                                                             | 28.2 ms: 1.06x faster                                                 |
| pathlib                    | 24.4 ms                                                             | 23.1 ms: 1.05x faster                                                 |
| pickle                     | 7.35 us                                                             | 6.98 us: 1.05x faster                                                 |
| unpickle_pure_python       | 144 us                                                              | 137 us: 1.05x faster                                                  |
| sympy_str                  | 151 ms                                                              | 144 ms: 1.05x faster                                                  |
| regex_compile              | 75.8 ms                                                             | 72.1 ms: 1.05x faster                                                 |
| django_template            | 21.8 ms                                                             | 20.8 ms: 1.05x faster                                                 |
| float                      | 58.0 ms                                                             | 55.5 ms: 1.05x faster                                                 |
| deepcopy_reduce            | 2.03 us                                                             | 1.94 us: 1.05x faster                                                 |
| regex_v8                   | 15.6 ms                                                             | 15.0 ms: 1.04x faster                                                 |
| nqueens                    | 59.6 ms                                                             | 57.2 ms: 1.04x faster                                                 |
| coroutines                 | 18.2 ms                                                             | 17.5 ms: 1.04x faster                                                 |
| richards                   | 31.0 ms                                                             | 29.8 ms: 1.04x faster                                                 |
| python_startup_no_site     | 9.90 ms                                                             | 9.54 ms: 1.04x faster                                                 |
| pycparser                  | 667 ms                                                              | 643 ms: 1.04x faster                                                  |
| regex_dna                  | 152 ms                                                              | 147 ms: 1.03x faster                                                  |
| deltablue                  | 2.59 ms                                                             | 2.51 ms: 1.03x faster                                                 |
| crypto_pyaes               | 51.8 ms                                                             | 50.4 ms: 1.03x faster                                                 |
| pprint_pformat             | 1.00 sec                                                            | 977 ms: 1.03x faster                                                  |
| meteor_contest             | 72.9 ms                                                             | 71.1 ms: 1.03x faster                                                 |
| pprint_safe_repr           | 492 ms                                                              | 480 ms: 1.02x faster                                                  |
| create_gc_cycles           | 702 us                                                              | 686 us: 1.02x faster                                                  |
| sympy_integrate            | 11.3 ms                                                             | 11.1 ms: 1.02x faster                                                 |
| nbody                      | 68.8 ms                                                             | 67.7 ms: 1.02x faster                                                 |
| pidigits                   | 282 ms                                                              | 280 ms: 1.01x faster                                                  |
| go                         | 106 ms                                                              | 106 ms: 1.01x faster                                                  |
| gc_traversal               | 2.40 ms                                                             | 2.38 ms: 1.01x faster                                                 |
| pickle_pure_python         | 189 us                                                              | 190 us: 1.01x slower                                                  |
| deepcopy                   | 224 us                                                              | 227 us: 1.01x slower                                                  |
| mdp                        | 1.67 sec                                                            | 1.70 sec: 1.02x slower                                                |
| async_tree_cpu_io_mixed_tg | 530 ms                                                              | 543 ms: 1.02x slower                                                  |
| mako                       | 7.52 ms                                                             | 7.76 ms: 1.03x slower                                                 |
| sympy_sum                  | 79.1 ms                                                             | 81.7 ms: 1.03x slower                                                 |
| richards_super             | 34.9 ms                                                             | 36.0 ms: 1.03x slower                                                 |
| unpack_sequence            | 28.7 ns                                                             | 30.2 ns: 1.05x slower                                                 |
| async_tree_memoization     | 306 ms                                                              | 322 ms: 1.06x slower                                                  |
| async_tree_none_tg         | 252 ms                                                              | 266 ms: 1.06x slower                                                  |
| comprehensions             | 15.7 us                                                             | 16.6 us: 1.06x slower                                                 |
| sqlglot_transpile          | 1.07 ms                                                             | 1.15 ms: 1.07x slower                                                 |
| async_tree_io_tg           | 664 ms                                                              | 710 ms: 1.07x slower                                                  |
| async_tree_memoization_tg  | 316 ms                                                              | 340 ms: 1.07x slower                                                  |
| async_tree_none            | 258 ms                                                              | 280 ms: 1.08x slower                                                  |
| hexiom                     | 4.24 ms                                                             | 4.66 ms: 1.10x slower                                                 |
| sqlglot_parse              | 895 us                                                              | 985 us: 1.10x slower                                                  |
| async_tree_io              | 659 ms                                                              | 728 ms: 1.11x slower                                                  |
| chaos                      | 44.6 ms                                                             | 49.5 ms: 1.11x slower                                                 |
| deepcopy_memo              | 24.6 us                                                             | 27.7 us: 1.13x slower                                                 |
| generators                 | 28.6 ms                                                             | 35.1 ms: 1.23x slower                                                 |
| dask                       | 224 ms                                                              | 309 ms: 1.38x slower                                                  |
| typing_runtime_protocols   | 90.6 us                                                             | 320 us: 3.53x slower                                                  |
| Geometric mean             | (ref)                                                               | 1.02x faster                                                          |

Benchmark hidden because not significant (4): asyncio_tcp_ssl, asyncio_websockets, async_tree_cpu_io_mixed, asyncio_tcp
Ignored benchmarks (7) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0.json: aiohttp, coverage, gunicorn, mypy2, sqlalchemy_declarative, sqlalchemy_imperative, tornado_http
Ignored benchmarks (4) of results/bm-20230110-3.12.0a4-3d5d3f7/bm-20230110-darwin-arm64-python-3d5d3f7af6498effbc60-3.12.0a4-3d5d3f7.json: genshi_text, genshi_xml, html5lib, thrift


# HPT report

- Reliability score: 99.97% likely to be faster
- 90% likely to have a speedup of 1.02x
- 95% likely to have a speedup of 1.02x
- 99% likely to have a speedup of 1.01x
