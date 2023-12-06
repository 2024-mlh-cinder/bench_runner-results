
# Results vs. 3.12.0

- fork: python
- ref: 72f00f420afaba3bc873
- machine: darwin-arm64
- commit hash: 72f00f4
- commit date: 2022-05-30
- overall geometric mean: 1.01x faster
- HPT reliability: 99.95%
- HPT 99th percentile: 1.01x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0 | bm-20220530-darwin-arm64-python-72f00f420afaba3bc873-3.11.0b2-72f00f4 |
|----------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| 2to3           | 170 ms                                                              | 153 ms: 1.11x faster                                                  |
| chameleon      | 4.51 ms                                                             | 4.32 ms: 1.05x faster                                                 |
| docutils       | 1.53 sec                                                            | 1.42 sec: 1.07x faster                                                |
| Geometric mean | (ref)                                                               | 1.06x faster                                                          |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0 | bm-20220530-darwin-arm64-python-72f00f420afaba3bc873-3.11.0b2-72f00f4 |
|----------------------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| async_tree_cpu_io_mixed    | 520 ms                                                              | 514 ms: 1.01x faster                                                  |
| async_tree_cpu_io_mixed_tg | 530 ms                                                              | 548 ms: 1.03x slower                                                  |
| async_tree_io              | 659 ms                                                              | 688 ms: 1.04x slower                                                  |
| async_tree_none            | 258 ms                                                              | 278 ms: 1.08x slower                                                  |
| async_tree_memoization_tg  | 316 ms                                                              | 341 ms: 1.08x slower                                                  |
| async_tree_none_tg         | 252 ms                                                              | 273 ms: 1.08x slower                                                  |
| async_tree_io_tg           | 664 ms                                                              | 721 ms: 1.09x slower                                                  |
| async_tree_memoization     | 306 ms                                                              | 363 ms: 1.19x slower                                                  |
| Geometric mean             | (ref)                                                               | 1.07x slower                                                          |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0 | bm-20220530-darwin-arm64-python-72f00f420afaba3bc873-3.11.0b2-72f00f4 |
|----------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| float          | 58.0 ms                                                             | 54.4 ms: 1.07x faster                                                 |
| nbody          | 68.8 ms                                                             | 65.5 ms: 1.05x faster                                                 |
| pidigits       | 282 ms                                                              | 280 ms: 1.01x faster                                                  |
| Geometric mean | (ref)                                                               | 1.04x faster                                                          |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0 | bm-20220530-darwin-arm64-python-72f00f420afaba3bc873-3.11.0b2-72f00f4 |
|----------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| regex_effbot   | 2.58 ms                                                             | 2.22 ms: 1.16x faster                                                 |
| regex_dna      | 152 ms                                                              | 147 ms: 1.03x faster                                                  |
| regex_compile  | 75.8 ms                                                             | 73.8 ms: 1.03x faster                                                 |
| regex_v8       | 15.6 ms                                                             | 15.2 ms: 1.03x faster                                                 |
| Geometric mean | (ref)                                                               | 1.06x faster                                                          |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0 | bm-20220530-darwin-arm64-python-72f00f420afaba3bc873-3.11.0b2-72f00f4 |
|----------------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| xml_etree_generate   | 55.8 ms                                                             | 46.7 ms: 1.19x faster                                                 |
| unpickle_list        | 3.20 us                                                             | 2.80 us: 1.14x faster                                                 |
| xml_etree_process    | 38.6 ms                                                             | 33.9 ms: 1.14x faster                                                 |
| json_loads           | 17.3 us                                                             | 15.4 us: 1.13x faster                                                 |
| unpickle             | 9.26 us                                                             | 8.23 us: 1.13x faster                                                 |
| pickle_dict          | 18.1 us                                                             | 16.1 us: 1.12x faster                                                 |
| pickle_list          | 2.89 us                                                             | 2.59 us: 1.11x faster                                                 |
| xml_etree_iterparse  | 74.2 ms                                                             | 66.9 ms: 1.11x faster                                                 |
| xml_etree_parse      | 106 ms                                                              | 97.2 ms: 1.09x faster                                                 |
| tomli_loads          | 1.40 sec                                                            | 1.30 sec: 1.07x faster                                                |
| pickle               | 7.35 us                                                             | 7.03 us: 1.04x faster                                                 |
| pickle_pure_python   | 189 us                                                              | 194 us: 1.03x slower                                                  |
| unpickle_pure_python | 144 us                                                              | 151 us: 1.04x slower                                                  |
| json_dumps           | 6.48 ms                                                             | 7.58 ms: 1.17x slower                                                 |
| Geometric mean       | (ref)                                                               | 1.07x faster                                                          |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0 | bm-20220530-darwin-arm64-python-72f00f420afaba3bc873-3.11.0b2-72f00f4 |
|------------------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| python_startup_no_site | 9.90 ms                                                             | 9.31 ms: 1.06x faster                                                 |
| python_startup         | 12.1 ms                                                             | 11.4 ms: 1.06x faster                                                 |
| Geometric mean         | (ref)                                                               | 1.06x faster                                                          |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0 | bm-20220530-darwin-arm64-python-72f00f420afaba3bc873-3.11.0b2-72f00f4 |
|-----------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| django_template | 21.8 ms                                                             | 19.8 ms: 1.10x faster                                                 |
| mako            | 7.52 ms                                                             | 8.11 ms: 1.08x slower                                                 |
| Geometric mean  | (ref)                                                               | 1.01x faster                                                          |

All benchmarks:
===============

| Benchmark                  | bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0 | bm-20220530-darwin-arm64-python-72f00f420afaba3bc873-3.11.0b2-72f00f4 |
|----------------------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| async_generators           | 306 ms                                                              | 191 ms: 1.60x faster                                                  |
| mypy2                      | 256 ms                                                              | 186 ms: 1.37x faster                                                  |
| scimark_sor                | 93.8 ms                                                             | 76.1 ms: 1.23x faster                                                 |
| raytrace                   | 245 ms                                                              | 200 ms: 1.23x faster                                                  |
| sqlite_synth               | 1.60 us                                                             | 1.31 us: 1.23x faster                                                 |
| xml_etree_generate         | 55.8 ms                                                             | 46.7 ms: 1.19x faster                                                 |
| telco                      | 3.79 ms                                                             | 3.17 ms: 1.19x faster                                                 |
| regex_effbot               | 2.58 ms                                                             | 2.22 ms: 1.16x faster                                                 |
| pyflate                    | 328 ms                                                              | 285 ms: 1.15x faster                                                  |
| unpickle_list              | 3.20 us                                                             | 2.80 us: 1.14x faster                                                 |
| sqlglot_normalize          | 186 ms                                                              | 163 ms: 1.14x faster                                                  |
| xml_etree_process          | 38.6 ms                                                             | 33.9 ms: 1.14x faster                                                 |
| scimark_monte_carlo        | 50.0 ms                                                             | 44.3 ms: 1.13x faster                                                 |
| sqlglot_optimize           | 34.3 ms                                                             | 30.4 ms: 1.13x faster                                                 |
| json_loads                 | 17.3 us                                                             | 15.4 us: 1.13x faster                                                 |
| unpickle                   | 9.26 us                                                             | 8.23 us: 1.13x faster                                                 |
| pickle_dict                | 18.1 us                                                             | 16.1 us: 1.12x faster                                                 |
| bench_mp_pool              | 46.8 ms                                                             | 41.6 ms: 1.12x faster                                                 |
| json                       | 3.11 ms                                                             | 2.79 ms: 1.12x faster                                                 |
| pickle_list                | 2.89 us                                                             | 2.59 us: 1.11x faster                                                 |
| xml_etree_iterparse        | 74.2 ms                                                             | 66.9 ms: 1.11x faster                                                 |
| 2to3                       | 170 ms                                                              | 153 ms: 1.11x faster                                                  |
| django_template            | 21.8 ms                                                             | 19.8 ms: 1.10x faster                                                 |
| logging_simple             | 3.70 us                                                             | 3.37 us: 1.10x faster                                                 |
| sqlalchemy_declarative     | 65.4 ms                                                             | 59.5 ms: 1.10x faster                                                 |
| logging_format             | 3.98 us                                                             | 3.63 us: 1.10x faster                                                 |
| crypto_pyaes               | 51.8 ms                                                             | 47.4 ms: 1.09x faster                                                 |
| nqueens                    | 59.6 ms                                                             | 54.7 ms: 1.09x faster                                                 |
| xml_etree_parse            | 106 ms                                                              | 97.2 ms: 1.09x faster                                                 |
| spectral_norm              | 74.6 ms                                                             | 68.4 ms: 1.09x faster                                                 |
| scimark_fft                | 198 ms                                                              | 183 ms: 1.08x faster                                                  |
| bench_thread_pool          | 503 us                                                              | 466 us: 1.08x faster                                                  |
| aiohttp                    | 1.18 ms                                                             | 1.10 ms: 1.08x faster                                                 |
| docutils                   | 1.53 sec                                                            | 1.42 sec: 1.07x faster                                                |
| tomli_loads                | 1.40 sec                                                            | 1.30 sec: 1.07x faster                                                |
| sympy_expand               | 250 ms                                                              | 233 ms: 1.07x faster                                                  |
| fannkuch                   | 262 ms                                                              | 244 ms: 1.07x faster                                                  |
| coroutines                 | 18.2 ms                                                             | 17.0 ms: 1.07x faster                                                 |
| float                      | 58.0 ms                                                             | 54.4 ms: 1.07x faster                                                 |
| scimark_sparse_mat_mult    | 3.14 ms                                                             | 2.95 ms: 1.07x faster                                                 |
| python_startup_no_site     | 9.90 ms                                                             | 9.31 ms: 1.06x faster                                                 |
| python_startup             | 12.1 ms                                                             | 11.4 ms: 1.06x faster                                                 |
| sympy_str                  | 151 ms                                                              | 143 ms: 1.06x faster                                                  |
| deepcopy_reduce            | 2.03 us                                                             | 1.93 us: 1.05x faster                                                 |
| pathlib                    | 24.4 ms                                                             | 23.2 ms: 1.05x faster                                                 |
| nbody                      | 68.8 ms                                                             | 65.5 ms: 1.05x faster                                                 |
| scimark_lu                 | 71.4 ms                                                             | 68.2 ms: 1.05x faster                                                 |
| chameleon                  | 4.51 ms                                                             | 4.32 ms: 1.05x faster                                                 |
| pickle                     | 7.35 us                                                             | 7.03 us: 1.04x faster                                                 |
| dulwich_log                | 29.8 ms                                                             | 28.7 ms: 1.04x faster                                                 |
| regex_dna                  | 152 ms                                                              | 147 ms: 1.03x faster                                                  |
| gunicorn                   | 1.22 ms                                                             | 1.18 ms: 1.03x faster                                                 |
| go                         | 106 ms                                                              | 103 ms: 1.03x faster                                                  |
| regex_compile              | 75.8 ms                                                             | 73.8 ms: 1.03x faster                                                 |
| regex_v8                   | 15.6 ms                                                             | 15.2 ms: 1.03x faster                                                 |
| dask                       | 224 ms                                                              | 219 ms: 1.02x faster                                                  |
| logging_silent             | 67.8 ns                                                             | 66.3 ns: 1.02x faster                                                 |
| sympy_integrate            | 11.3 ms                                                             | 11.1 ms: 1.02x faster                                                 |
| pprint_pformat             | 1.00 sec                                                            | 988 ms: 1.02x faster                                                  |
| pprint_safe_repr           | 492 ms                                                              | 485 ms: 1.01x faster                                                  |
| async_tree_cpu_io_mixed    | 520 ms                                                              | 514 ms: 1.01x faster                                                  |
| sympy_sum                  | 79.1 ms                                                             | 78.2 ms: 1.01x faster                                                 |
| pycparser                  | 667 ms                                                              | 660 ms: 1.01x faster                                                  |
| gc_traversal               | 2.40 ms                                                             | 2.38 ms: 1.01x faster                                                 |
| pidigits                   | 282 ms                                                              | 280 ms: 1.01x faster                                                  |
| meteor_contest             | 72.9 ms                                                             | 72.5 ms: 1.01x faster                                                 |
| asyncio_websockets         | 408 ms                                                              | 407 ms: 1.00x faster                                                  |
| sqlalchemy_imperative      | 6.92 ms                                                             | 6.97 ms: 1.01x slower                                                 |
| richards                   | 31.0 ms                                                             | 31.3 ms: 1.01x slower                                                 |
| create_gc_cycles           | 702 us                                                              | 711 us: 1.01x slower                                                  |
| deepcopy                   | 224 us                                                              | 228 us: 1.02x slower                                                  |
| pickle_pure_python         | 189 us                                                              | 194 us: 1.03x slower                                                  |
| async_tree_cpu_io_mixed_tg | 530 ms                                                              | 548 ms: 1.03x slower                                                  |
| mdp                        | 1.67 sec                                                            | 1.74 sec: 1.04x slower                                                |
| unpickle_pure_python       | 144 us                                                              | 151 us: 1.04x slower                                                  |
| async_tree_io              | 659 ms                                                              | 688 ms: 1.04x slower                                                  |
| generators                 | 28.6 ms                                                             | 30.0 ms: 1.05x slower                                                 |
| deltablue                  | 2.59 ms                                                             | 2.72 ms: 1.05x slower                                                 |
| chaos                      | 44.6 ms                                                             | 47.8 ms: 1.07x slower                                                 |
| async_tree_none            | 258 ms                                                              | 278 ms: 1.08x slower                                                  |
| async_tree_memoization_tg  | 316 ms                                                              | 341 ms: 1.08x slower                                                  |
| mako                       | 7.52 ms                                                             | 8.11 ms: 1.08x slower                                                 |
| hexiom                     | 4.24 ms                                                             | 4.58 ms: 1.08x slower                                                 |
| richards_super             | 34.9 ms                                                             | 37.8 ms: 1.08x slower                                                 |
| async_tree_none_tg         | 252 ms                                                              | 273 ms: 1.08x slower                                                  |
| async_tree_io_tg           | 664 ms                                                              | 721 ms: 1.09x slower                                                  |
| comprehensions             | 15.7 us                                                             | 17.2 us: 1.09x slower                                                 |
| deepcopy_memo              | 24.6 us                                                             | 27.8 us: 1.13x slower                                                 |
| asyncio_tcp_ssl            | 1.26 sec                                                            | 1.43 sec: 1.13x slower                                                |
| unpack_sequence            | 28.7 ns                                                             | 32.7 ns: 1.14x slower                                                 |
| json_dumps                 | 6.48 ms                                                             | 7.58 ms: 1.17x slower                                                 |
| async_tree_memoization     | 306 ms                                                              | 363 ms: 1.19x slower                                                  |
| sqlglot_transpile          | 1.07 ms                                                             | 1.30 ms: 1.21x slower                                                 |
| sqlglot_parse              | 895 us                                                              | 1.14 ms: 1.27x slower                                                 |
| asyncio_tcp                | 419 ms                                                              | 665 ms: 1.59x slower                                                  |
| coverage                   | 37.8 ms                                                             | 72.4 ms: 1.92x slower                                                 |
| typing_runtime_protocols   | 90.6 us                                                             | 326 us: 3.59x slower                                                  |
| Geometric mean             | (ref)                                                               | 1.01x faster                                                          |

Benchmark hidden because not significant (1): tornado_http
Ignored benchmarks (5) of results/bm-20220530-3.11.0b2-72f00f4/bm-20220530-darwin-arm64-python-72f00f420afaba3bc873-3.11.0b2-72f00f4.json: genshi_text, genshi_xml, html5lib, pylint, thrift


# HPT report

- Reliability score: 99.95% likely to be faster
- 90% likely to have a speedup of 1.02x
- 95% likely to have a speedup of 1.01x
- 99% likely to have a speedup of 1.01x
