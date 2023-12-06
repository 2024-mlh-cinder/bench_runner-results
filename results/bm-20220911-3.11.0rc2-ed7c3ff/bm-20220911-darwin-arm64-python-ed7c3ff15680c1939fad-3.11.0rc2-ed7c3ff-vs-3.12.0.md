
# Results vs. 3.12.0

- fork: python
- ref: ed7c3ff15680c1939fad
- machine: darwin-arm64
- commit hash: ed7c3ff
- commit date: 2022-09-11
- overall geometric mean: 1.02x faster
- HPT reliability: 99.93%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0 | bm-20220911-darwin-arm64-python-ed7c3ff15680c1939fad-3.11.0rc2-ed7c3ff |
|----------------|:-------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| 2to3           | 170 ms                                                              | 153 ms: 1.11x faster                                                   |
| chameleon      | 4.51 ms                                                             | 4.17 ms: 1.08x faster                                                  |
| docutils       | 1.53 sec                                                            | 1.43 sec: 1.07x faster                                                 |
| Geometric mean | (ref)                                                               | 1.07x faster                                                           |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0 | bm-20220911-darwin-arm64-python-ed7c3ff15680c1939fad-3.11.0rc2-ed7c3ff |
|----------------------------|:-------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| async_tree_cpu_io_mixed    | 520 ms                                                              | 515 ms: 1.01x faster                                                   |
| async_tree_cpu_io_mixed_tg | 530 ms                                                              | 547 ms: 1.03x slower                                                   |
| async_tree_io              | 659 ms                                                              | 690 ms: 1.05x slower                                                   |
| async_tree_none            | 258 ms                                                              | 277 ms: 1.07x slower                                                   |
| async_tree_io_tg           | 664 ms                                                              | 722 ms: 1.09x slower                                                   |
| async_tree_none_tg         | 252 ms                                                              | 275 ms: 1.09x slower                                                   |
| async_tree_memoization_tg  | 316 ms                                                              | 351 ms: 1.11x slower                                                   |
| async_tree_memoization     | 306 ms                                                              | 347 ms: 1.14x slower                                                   |
| Geometric mean             | (ref)                                                               | 1.07x slower                                                           |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0 | bm-20220911-darwin-arm64-python-ed7c3ff15680c1939fad-3.11.0rc2-ed7c3ff |
|----------------|:-------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| float          | 58.0 ms                                                             | 55.7 ms: 1.04x faster                                                  |
| pidigits       | 282 ms                                                              | 280 ms: 1.01x faster                                                   |
| nbody          | 68.8 ms                                                             | 68.4 ms: 1.01x faster                                                  |
| Geometric mean | (ref)                                                               | 1.02x faster                                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0 | bm-20220911-darwin-arm64-python-ed7c3ff15680c1939fad-3.11.0rc2-ed7c3ff |
|----------------|:-------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| regex_effbot   | 2.58 ms                                                             | 2.46 ms: 1.05x faster                                                  |
| regex_compile  | 75.8 ms                                                             | 73.6 ms: 1.03x faster                                                  |
| regex_dna      | 152 ms                                                              | 150 ms: 1.01x faster                                                   |
| regex_v8       | 15.6 ms                                                             | 15.5 ms: 1.01x faster                                                  |
| Geometric mean | (ref)                                                               | 1.02x faster                                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0 | bm-20220911-darwin-arm64-python-ed7c3ff15680c1939fad-3.11.0rc2-ed7c3ff |
|----------------------|:-------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| xml_etree_generate   | 55.8 ms                                                             | 46.7 ms: 1.19x faster                                                  |
| unpickle_list        | 3.20 us                                                             | 2.77 us: 1.16x faster                                                  |
| xml_etree_process    | 38.6 ms                                                             | 34.0 ms: 1.13x faster                                                  |
| json_loads           | 17.3 us                                                             | 15.5 us: 1.12x faster                                                  |
| unpickle             | 9.26 us                                                             | 8.37 us: 1.11x faster                                                  |
| xml_etree_iterparse  | 74.2 ms                                                             | 67.1 ms: 1.11x faster                                                  |
| xml_etree_parse      | 106 ms                                                              | 96.9 ms: 1.09x faster                                                  |
| pickle_list          | 2.89 us                                                             | 2.66 us: 1.09x faster                                                  |
| tomli_loads          | 1.40 sec                                                            | 1.31 sec: 1.07x faster                                                 |
| pickle_dict          | 18.1 us                                                             | 17.0 us: 1.07x faster                                                  |
| pickle               | 7.35 us                                                             | 7.17 us: 1.02x faster                                                  |
| pickle_pure_python   | 189 us                                                              | 210 us: 1.11x slower                                                   |
| unpickle_pure_python | 144 us                                                              | 163 us: 1.13x slower                                                   |
| json_dumps           | 6.48 ms                                                             | 7.56 ms: 1.17x slower                                                  |
| Geometric mean       | (ref)                                                               | 1.05x faster                                                           |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0 | bm-20220911-darwin-arm64-python-ed7c3ff15680c1939fad-3.11.0rc2-ed7c3ff |
|------------------------|:-------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| python_startup_no_site | 9.90 ms                                                             | 9.94 ms: 1.00x slower                                                  |
| Geometric mean         | (ref)                                                               | 1.00x faster                                                           |

Benchmark hidden because not significant (1): python_startup

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0 | bm-20220911-darwin-arm64-python-ed7c3ff15680c1939fad-3.11.0rc2-ed7c3ff |
|-----------------|:-------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| django_template | 21.8 ms                                                             | 19.8 ms: 1.10x faster                                                  |
| mako            | 7.52 ms                                                             | 8.22 ms: 1.09x slower                                                  |
| Geometric mean  | (ref)                                                               | 1.01x faster                                                           |

All benchmarks:
===============

| Benchmark                  | bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0 | bm-20220911-darwin-arm64-python-ed7c3ff15680c1939fad-3.11.0rc2-ed7c3ff |
|----------------------------|:-------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| async_generators           | 306 ms                                                              | 191 ms: 1.60x faster                                                   |
| mypy2                      | 256 ms                                                              | 187 ms: 1.37x faster                                                   |
| scimark_sor                | 93.8 ms                                                             | 74.8 ms: 1.25x faster                                                  |
| xml_etree_generate         | 55.8 ms                                                             | 46.7 ms: 1.19x faster                                                  |
| telco                      | 3.79 ms                                                             | 3.18 ms: 1.19x faster                                                  |
| raytrace                   | 245 ms                                                              | 206 ms: 1.19x faster                                                   |
| sqlite_synth               | 1.60 us                                                             | 1.36 us: 1.18x faster                                                  |
| sqlglot_normalize          | 186 ms                                                              | 160 ms: 1.16x faster                                                   |
| sqlglot_optimize           | 34.3 ms                                                             | 29.5 ms: 1.16x faster                                                  |
| unpickle_list              | 3.20 us                                                             | 2.77 us: 1.16x faster                                                  |
| xml_etree_process          | 38.6 ms                                                             | 34.0 ms: 1.13x faster                                                  |
| json                       | 3.11 ms                                                             | 2.75 ms: 1.13x faster                                                  |
| bench_mp_pool              | 46.8 ms                                                             | 41.8 ms: 1.12x faster                                                  |
| json_loads                 | 17.3 us                                                             | 15.5 us: 1.12x faster                                                  |
| pyflate                    | 328 ms                                                              | 294 ms: 1.12x faster                                                   |
| gunicorn                   | 1.22 ms                                                             | 1.10 ms: 1.11x faster                                                  |
| coroutines                 | 18.2 ms                                                             | 16.4 ms: 1.11x faster                                                  |
| unpickle                   | 9.26 us                                                             | 8.37 us: 1.11x faster                                                  |
| 2to3                       | 170 ms                                                              | 153 ms: 1.11x faster                                                   |
| xml_etree_iterparse        | 74.2 ms                                                             | 67.1 ms: 1.11x faster                                                  |
| django_template            | 21.8 ms                                                             | 19.8 ms: 1.10x faster                                                  |
| bench_thread_pool          | 503 us                                                              | 457 us: 1.10x faster                                                   |
| nqueens                    | 59.6 ms                                                             | 54.3 ms: 1.10x faster                                                  |
| xml_etree_parse            | 106 ms                                                              | 96.9 ms: 1.09x faster                                                  |
| pickle_list                | 2.89 us                                                             | 2.66 us: 1.09x faster                                                  |
| chameleon                  | 4.51 ms                                                             | 4.17 ms: 1.08x faster                                                  |
| sqlalchemy_declarative     | 65.4 ms                                                             | 60.5 ms: 1.08x faster                                                  |
| crypto_pyaes               | 51.8 ms                                                             | 48.1 ms: 1.08x faster                                                  |
| spectral_norm              | 74.6 ms                                                             | 69.2 ms: 1.08x faster                                                  |
| comprehensions             | 15.7 us                                                             | 14.6 us: 1.07x faster                                                  |
| logging_simple             | 3.70 us                                                             | 3.45 us: 1.07x faster                                                  |
| docutils                   | 1.53 sec                                                            | 1.43 sec: 1.07x faster                                                 |
| tomli_loads                | 1.40 sec                                                            | 1.31 sec: 1.07x faster                                                 |
| logging_format             | 3.98 us                                                             | 3.72 us: 1.07x faster                                                  |
| pickle_dict                | 18.1 us                                                             | 17.0 us: 1.07x faster                                                  |
| scimark_fft                | 198 ms                                                              | 186 ms: 1.07x faster                                                   |
| sympy_expand               | 250 ms                                                              | 235 ms: 1.06x faster                                                   |
| fannkuch                   | 262 ms                                                              | 247 ms: 1.06x faster                                                   |
| scimark_monte_carlo        | 50.0 ms                                                             | 47.2 ms: 1.06x faster                                                  |
| aiohttp                    | 1.18 ms                                                             | 1.12 ms: 1.06x faster                                                  |
| logging_silent             | 67.8 ns                                                             | 64.4 ns: 1.05x faster                                                  |
| scimark_lu                 | 71.4 ms                                                             | 67.9 ms: 1.05x faster                                                  |
| regex_effbot               | 2.58 ms                                                             | 2.46 ms: 1.05x faster                                                  |
| scimark_sparse_mat_mult    | 3.14 ms                                                             | 3.00 ms: 1.05x faster                                                  |
| sympy_str                  | 151 ms                                                              | 144 ms: 1.05x faster                                                   |
| float                      | 58.0 ms                                                             | 55.7 ms: 1.04x faster                                                  |
| pathlib                    | 24.4 ms                                                             | 23.4 ms: 1.04x faster                                                  |
| go                         | 106 ms                                                              | 102 ms: 1.04x faster                                                   |
| sqlglot_transpile          | 1.07 ms                                                             | 1.03 ms: 1.04x faster                                                  |
| deepcopy_reduce            | 2.03 us                                                             | 1.97 us: 1.03x faster                                                  |
| pprint_safe_repr           | 492 ms                                                              | 477 ms: 1.03x faster                                                   |
| regex_compile              | 75.8 ms                                                             | 73.6 ms: 1.03x faster                                                  |
| pprint_pformat             | 1.00 sec                                                            | 977 ms: 1.03x faster                                                   |
| pickle                     | 7.35 us                                                             | 7.17 us: 1.02x faster                                                  |
| sqlglot_parse              | 895 us                                                              | 874 us: 1.02x faster                                                   |
| dask                       | 224 ms                                                              | 220 ms: 1.02x faster                                                   |
| sympy_integrate            | 11.3 ms                                                             | 11.2 ms: 1.01x faster                                                  |
| dulwich_log                | 29.8 ms                                                             | 29.5 ms: 1.01x faster                                                  |
| async_tree_cpu_io_mixed    | 520 ms                                                              | 515 ms: 1.01x faster                                                   |
| regex_dna                  | 152 ms                                                              | 150 ms: 1.01x faster                                                   |
| pidigits                   | 282 ms                                                              | 280 ms: 1.01x faster                                                   |
| gc_traversal               | 2.40 ms                                                             | 2.38 ms: 1.01x faster                                                  |
| regex_v8                   | 15.6 ms                                                             | 15.5 ms: 1.01x faster                                                  |
| richards                   | 31.0 ms                                                             | 30.8 ms: 1.01x faster                                                  |
| nbody                      | 68.8 ms                                                             | 68.4 ms: 1.01x faster                                                  |
| asyncio_websockets         | 408 ms                                                              | 407 ms: 1.00x faster                                                   |
| python_startup_no_site     | 9.90 ms                                                             | 9.94 ms: 1.00x slower                                                  |
| create_gc_cycles           | 702 us                                                              | 712 us: 1.01x slower                                                   |
| generators                 | 28.6 ms                                                             | 29.0 ms: 1.02x slower                                                  |
| sympy_sum                  | 79.1 ms                                                             | 81.0 ms: 1.02x slower                                                  |
| meteor_contest             | 72.9 ms                                                             | 75.0 ms: 1.03x slower                                                  |
| async_tree_cpu_io_mixed_tg | 530 ms                                                              | 547 ms: 1.03x slower                                                   |
| deltablue                  | 2.59 ms                                                             | 2.68 ms: 1.04x slower                                                  |
| mdp                        | 1.67 sec                                                            | 1.74 sec: 1.04x slower                                                 |
| sqlalchemy_imperative      | 6.92 ms                                                             | 7.19 ms: 1.04x slower                                                  |
| deepcopy                   | 224 us                                                              | 233 us: 1.04x slower                                                   |
| async_tree_io              | 659 ms                                                              | 690 ms: 1.05x slower                                                   |
| richards_super             | 34.9 ms                                                             | 36.8 ms: 1.05x slower                                                  |
| hexiom                     | 4.24 ms                                                             | 4.54 ms: 1.07x slower                                                  |
| async_tree_none            | 258 ms                                                              | 277 ms: 1.07x slower                                                   |
| chaos                      | 44.6 ms                                                             | 48.2 ms: 1.08x slower                                                  |
| async_tree_io_tg           | 664 ms                                                              | 722 ms: 1.09x slower                                                   |
| async_tree_none_tg         | 252 ms                                                              | 275 ms: 1.09x slower                                                   |
| coverage                   | 37.8 ms                                                             | 41.3 ms: 1.09x slower                                                  |
| mako                       | 7.52 ms                                                             | 8.22 ms: 1.09x slower                                                  |
| async_tree_memoization_tg  | 316 ms                                                              | 351 ms: 1.11x slower                                                   |
| pickle_pure_python         | 189 us                                                              | 210 us: 1.11x slower                                                   |
| unpickle_pure_python       | 144 us                                                              | 163 us: 1.13x slower                                                   |
| unpack_sequence            | 28.7 ns                                                             | 32.3 ns: 1.13x slower                                                  |
| asyncio_tcp_ssl            | 1.26 sec                                                            | 1.44 sec: 1.14x slower                                                 |
| async_tree_memoization     | 306 ms                                                              | 347 ms: 1.14x slower                                                   |
| deepcopy_memo              | 24.6 us                                                             | 28.7 us: 1.17x slower                                                  |
| json_dumps                 | 6.48 ms                                                             | 7.56 ms: 1.17x slower                                                  |
| asyncio_tcp                | 419 ms                                                              | 661 ms: 1.58x slower                                                   |
| typing_runtime_protocols   | 90.6 us                                                             | 322 us: 3.55x slower                                                   |
| Geometric mean             | (ref)                                                               | 1.02x faster                                                           |

Benchmark hidden because not significant (3): python_startup, pycparser, tornado_http
Ignored benchmarks (6) of results/bm-20220911-3.11.0rc2-ed7c3ff/bm-20220911-darwin-arm64-python-ed7c3ff15680c1939fad-3.11.0rc2-ed7c3ff.json: flaskblogging, genshi_text, genshi_xml, html5lib, pylint, thrift


# HPT report

- Reliability score: 99.93% likely to be faster
- 90% likely to have a speedup of 1.01x
- 95% likely to have a speedup of 1.01x
- 99% likely to have a speedup of 1.00x
