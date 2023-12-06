
# Results vs. 3.12.0

- fork: python
- ref: 3faf8e586d36e73faba1
- machine: darwin-arm64
- commit hash: 3faf8e5
- commit date: 2023-11-25
- overall geometric mean: 1.08x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.04x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0 | bm-20231125-darwin-arm64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|----------------|:-------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| 2to3           | 170 ms                                                              | 182 ms: 1.07x slower                                                   |
| chameleon      | 4.51 ms                                                             | 5.28 ms: 1.17x slower                                                  |
| docutils       | 1.53 sec                                                            | 1.55 sec: 1.01x slower                                                 |
| tornado_http   | 70.5 ms                                                             | 73.5 ms: 1.04x slower                                                  |
| Geometric mean | (ref)                                                               | 1.07x slower                                                           |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0 | bm-20231125-darwin-arm64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|----------------------------|:-------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| async_tree_none            | 258 ms                                                              | 264 ms: 1.02x slower                                                   |
| async_tree_cpu_io_mixed    | 520 ms                                                              | 535 ms: 1.03x slower                                                   |
| async_tree_cpu_io_mixed_tg | 530 ms                                                              | 553 ms: 1.04x slower                                                   |
| async_tree_io_tg           | 664 ms                                                              | 700 ms: 1.06x slower                                                   |
| async_tree_io              | 659 ms                                                              | 718 ms: 1.09x slower                                                   |
| async_tree_memoization_tg  | 316 ms                                                              | 346 ms: 1.09x slower                                                   |
| async_tree_none_tg         | 252 ms                                                              | 277 ms: 1.10x slower                                                   |
| async_tree_memoization     | 306 ms                                                              | 340 ms: 1.11x slower                                                   |
| Geometric mean             | (ref)                                                               | 1.07x slower                                                           |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0 | bm-20231125-darwin-arm64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|----------------|:-------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| pidigits       | 282 ms                                                              | 283 ms: 1.00x slower                                                   |
| float          | 58.0 ms                                                             | 70.6 ms: 1.22x slower                                                  |
| nbody          | 68.8 ms                                                             | 91.1 ms: 1.32x slower                                                  |
| Geometric mean | (ref)                                                               | 1.17x slower                                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0 | bm-20231125-darwin-arm64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|----------------|:-------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| regex_dna      | 152 ms                                                              | 152 ms: 1.00x slower                                                   |
| regex_effbot   | 2.58 ms                                                             | 2.60 ms: 1.01x slower                                                  |
| regex_v8       | 15.6 ms                                                             | 17.1 ms: 1.09x slower                                                  |
| regex_compile  | 75.8 ms                                                             | 89.9 ms: 1.19x slower                                                  |
| Geometric mean | (ref)                                                               | 1.07x slower                                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0 | bm-20231125-darwin-arm64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|----------------------|:-------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| unpickle_list        | 3.20 us                                                             | 3.14 us: 1.02x faster                                                  |
| unpickle             | 9.26 us                                                             | 9.11 us: 1.02x faster                                                  |
| pickle_dict          | 18.1 us                                                             | 17.9 us: 1.01x faster                                                  |
| pickle               | 7.35 us                                                             | 7.41 us: 1.01x slower                                                  |
| xml_etree_parse      | 106 ms                                                              | 108 ms: 1.02x slower                                                   |
| pickle_list          | 2.89 us                                                             | 2.95 us: 1.02x slower                                                  |
| json_dumps           | 6.48 ms                                                             | 6.64 ms: 1.02x slower                                                  |
| xml_etree_iterparse  | 74.2 ms                                                             | 81.5 ms: 1.10x slower                                                  |
| xml_etree_process    | 38.6 ms                                                             | 42.5 ms: 1.10x slower                                                  |
| pickle_pure_python   | 189 us                                                              | 210 us: 1.11x slower                                                   |
| xml_etree_generate   | 55.8 ms                                                             | 62.7 ms: 1.12x slower                                                  |
| tomli_loads          | 1.40 sec                                                            | 1.71 sec: 1.22x slower                                                 |
| unpickle_pure_python | 144 us                                                              | 178 us: 1.23x slower                                                   |
| Geometric mean       | (ref)                                                               | 1.06x slower                                                           |

Benchmark hidden because not significant (1): json_loads

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0 | bm-20231125-darwin-arm64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|------------------------|:-------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| python_startup         | 12.1 ms                                                             | 11.8 ms: 1.03x faster                                                  |
| python_startup_no_site | 9.90 ms                                                             | 10.4 ms: 1.05x slower                                                  |
| Geometric mean         | (ref)                                                               | 1.01x slower                                                           |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0 | bm-20231125-darwin-arm64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|-----------|:-------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| mako      | 7.52 ms                                                             | 9.81 ms: 1.30x slower                                                  |

All benchmarks:
===============

| Benchmark                  | bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0 | bm-20231125-darwin-arm64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|----------------------------|:-------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| raytrace                   | 245 ms                                                              | 199 ms: 1.23x faster                                                   |
| typing_runtime_protocols   | 90.6 us                                                             | 81.6 us: 1.11x faster                                                  |
| generators                 | 28.6 ms                                                             | 26.0 ms: 1.10x faster                                                  |
| bench_mp_pool              | 46.8 ms                                                             | 44.6 ms: 1.05x faster                                                  |
| sqlglot_parse              | 895 us                                                              | 867 us: 1.03x faster                                                   |
| python_startup             | 12.1 ms                                                             | 11.8 ms: 1.03x faster                                                  |
| json                       | 3.11 ms                                                             | 3.04 ms: 1.02x faster                                                  |
| unpickle_list              | 3.20 us                                                             | 3.14 us: 1.02x faster                                                  |
| sqlglot_transpile          | 1.07 ms                                                             | 1.05 ms: 1.02x faster                                                  |
| unpickle                   | 9.26 us                                                             | 9.11 us: 1.02x faster                                                  |
| pickle_dict                | 18.1 us                                                             | 17.9 us: 1.01x faster                                                  |
| create_gc_cycles           | 702 us                                                              | 703 us: 1.00x slower                                                   |
| regex_dna                  | 152 ms                                                              | 152 ms: 1.00x slower                                                   |
| logging_simple             | 3.70 us                                                             | 3.71 us: 1.00x slower                                                  |
| pidigits                   | 282 ms                                                              | 283 ms: 1.00x slower                                                   |
| gc_traversal               | 2.40 ms                                                             | 2.41 ms: 1.00x slower                                                  |
| regex_effbot               | 2.58 ms                                                             | 2.60 ms: 1.01x slower                                                  |
| pickle                     | 7.35 us                                                             | 7.41 us: 1.01x slower                                                  |
| logging_format             | 3.98 us                                                             | 4.02 us: 1.01x slower                                                  |
| docutils                   | 1.53 sec                                                            | 1.55 sec: 1.01x slower                                                 |
| xml_etree_parse            | 106 ms                                                              | 108 ms: 1.02x slower                                                   |
| pickle_list                | 2.89 us                                                             | 2.95 us: 1.02x slower                                                  |
| pathlib                    | 24.4 ms                                                             | 24.9 ms: 1.02x slower                                                  |
| async_generators           | 306 ms                                                              | 313 ms: 1.02x slower                                                   |
| async_tree_none            | 258 ms                                                              | 264 ms: 1.02x slower                                                   |
| json_dumps                 | 6.48 ms                                                             | 6.64 ms: 1.02x slower                                                  |
| dulwich_log                | 29.8 ms                                                             | 30.6 ms: 1.03x slower                                                  |
| async_tree_cpu_io_mixed    | 520 ms                                                              | 535 ms: 1.03x slower                                                   |
| mdp                        | 1.67 sec                                                            | 1.73 sec: 1.04x slower                                                 |
| asyncio_tcp_ssl            | 1.26 sec                                                            | 1.31 sec: 1.04x slower                                                 |
| dask                       | 224 ms                                                              | 233 ms: 1.04x slower                                                   |
| deepcopy_reduce            | 2.03 us                                                             | 2.11 us: 1.04x slower                                                  |
| tornado_http               | 70.5 ms                                                             | 73.5 ms: 1.04x slower                                                  |
| async_tree_cpu_io_mixed_tg | 530 ms                                                              | 553 ms: 1.04x slower                                                   |
| comprehensions             | 15.7 us                                                             | 16.5 us: 1.05x slower                                                  |
| python_startup_no_site     | 9.90 ms                                                             | 10.4 ms: 1.05x slower                                                  |
| async_tree_io_tg           | 664 ms                                                              | 700 ms: 1.06x slower                                                   |
| sympy_expand               | 250 ms                                                              | 264 ms: 1.06x slower                                                   |
| sympy_str                  | 151 ms                                                              | 160 ms: 1.06x slower                                                   |
| bench_thread_pool          | 503 us                                                              | 534 us: 1.06x slower                                                   |
| go                         | 106 ms                                                              | 113 ms: 1.07x slower                                                   |
| deepcopy                   | 224 us                                                              | 239 us: 1.07x slower                                                   |
| sqlite_synth               | 1.60 us                                                             | 1.71 us: 1.07x slower                                                  |
| sympy_sum                  | 79.1 ms                                                             | 84.8 ms: 1.07x slower                                                  |
| 2to3                       | 170 ms                                                              | 182 ms: 1.07x slower                                                   |
| crypto_pyaes               | 51.8 ms                                                             | 55.7 ms: 1.08x slower                                                  |
| pycparser                  | 667 ms                                                              | 719 ms: 1.08x slower                                                   |
| logging_silent             | 67.8 ns                                                             | 73.2 ns: 1.08x slower                                                  |
| sympy_integrate            | 11.3 ms                                                             | 12.3 ms: 1.08x slower                                                  |
| async_tree_io              | 659 ms                                                              | 718 ms: 1.09x slower                                                   |
| richards_super             | 34.9 ms                                                             | 38.0 ms: 1.09x slower                                                  |
| coroutines                 | 18.2 ms                                                             | 19.9 ms: 1.09x slower                                                  |
| regex_v8                   | 15.6 ms                                                             | 17.1 ms: 1.09x slower                                                  |
| async_tree_memoization_tg  | 316 ms                                                              | 346 ms: 1.09x slower                                                   |
| sqlglot_normalize          | 186 ms                                                              | 204 ms: 1.10x slower                                                   |
| xml_etree_iterparse        | 74.2 ms                                                             | 81.5 ms: 1.10x slower                                                  |
| richards                   | 31.0 ms                                                             | 34.1 ms: 1.10x slower                                                  |
| scimark_lu                 | 71.4 ms                                                             | 78.4 ms: 1.10x slower                                                  |
| async_tree_none_tg         | 252 ms                                                              | 277 ms: 1.10x slower                                                   |
| xml_etree_process          | 38.6 ms                                                             | 42.5 ms: 1.10x slower                                                  |
| pickle_pure_python         | 189 us                                                              | 210 us: 1.11x slower                                                   |
| async_tree_memoization     | 306 ms                                                              | 340 ms: 1.11x slower                                                   |
| sqlglot_optimize           | 34.3 ms                                                             | 38.2 ms: 1.11x slower                                                  |
| chaos                      | 44.6 ms                                                             | 49.7 ms: 1.11x slower                                                  |
| xml_etree_generate         | 55.8 ms                                                             | 62.7 ms: 1.12x slower                                                  |
| meteor_contest             | 72.9 ms                                                             | 82.0 ms: 1.12x slower                                                  |
| deepcopy_memo              | 24.6 us                                                             | 27.8 us: 1.13x slower                                                  |
| pyflate                    | 328 ms                                                              | 378 ms: 1.15x slower                                                   |
| scimark_sor                | 93.8 ms                                                             | 109 ms: 1.17x slower                                                   |
| chameleon                  | 4.51 ms                                                             | 5.28 ms: 1.17x slower                                                  |
| regex_compile              | 75.8 ms                                                             | 89.9 ms: 1.19x slower                                                  |
| nqueens                    | 59.6 ms                                                             | 71.9 ms: 1.20x slower                                                  |
| scimark_monte_carlo        | 50.0 ms                                                             | 60.3 ms: 1.21x slower                                                  |
| pprint_safe_repr           | 492 ms                                                              | 596 ms: 1.21x slower                                                   |
| float                      | 58.0 ms                                                             | 70.6 ms: 1.22x slower                                                  |
| tomli_loads                | 1.40 sec                                                            | 1.71 sec: 1.22x slower                                                 |
| pprint_pformat             | 1.00 sec                                                            | 1.23 sec: 1.22x slower                                                 |
| unpickle_pure_python       | 144 us                                                              | 178 us: 1.23x slower                                                   |
| coverage                   | 37.8 ms                                                             | 47.9 ms: 1.27x slower                                                  |
| telco                      | 3.79 ms                                                             | 4.86 ms: 1.28x slower                                                  |
| scimark_fft                | 198 ms                                                              | 256 ms: 1.29x slower                                                   |
| mako                       | 7.52 ms                                                             | 9.81 ms: 1.30x slower                                                  |
| fannkuch                   | 262 ms                                                              | 345 ms: 1.32x slower                                                   |
| nbody                      | 68.8 ms                                                             | 91.1 ms: 1.32x slower                                                  |
| scimark_sparse_mat_mult    | 3.14 ms                                                             | 4.30 ms: 1.37x slower                                                  |
| spectral_norm              | 74.6 ms                                                             | 104 ms: 1.40x slower                                                   |
| deltablue                  | 2.59 ms                                                             | 3.63 ms: 1.40x slower                                                  |
| hexiom                     | 4.24 ms                                                             | 6.31 ms: 1.49x slower                                                  |
| Geometric mean             | (ref)                                                               | 1.08x slower                                                           |

Benchmark hidden because not significant (5): asyncio_tcp, unpack_sequence, asyncio_websockets, json_loads, mypy2
Ignored benchmarks (5) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0.json: aiohttp, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.06x
- 95% likely to have a slowdown of 1.05x
- 99% likely to have a slowdown of 1.04x
