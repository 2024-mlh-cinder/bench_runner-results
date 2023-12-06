
# Results vs. 3.11.0

- fork: python
- ref: 3faf8e586d36e73faba1
- machine: darwin-arm64
- commit hash: 3faf8e5
- commit date: 2023-11-25
- overall geometric mean: 1.10x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.05x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-darwin-arm64-python-deaf509e8fc6e0363bd6-3.11.0-deaf509 | bm-20231125-darwin-arm64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|----------------|:-------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| 2to3           | 154 ms                                                              | 182 ms: 1.19x slower                                                   |
| chameleon      | 4.21 ms                                                             | 5.28 ms: 1.25x slower                                                  |
| docutils       | 1.43 sec                                                            | 1.55 sec: 1.08x slower                                                 |
| tornado_http   | 70.9 ms                                                             | 73.5 ms: 1.04x slower                                                  |
| Geometric mean | (ref)                                                               | 1.14x slower                                                           |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20221024-darwin-arm64-python-deaf509e8fc6e0363bd6-3.11.0-deaf509 | bm-20231125-darwin-arm64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|----------------------------|:-------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| async_tree_none            | 277 ms                                                              | 264 ms: 1.05x faster                                                   |
| async_tree_memoization     | 353 ms                                                              | 340 ms: 1.04x faster                                                   |
| async_tree_io_tg           | 723 ms                                                              | 700 ms: 1.03x faster                                                   |
| async_tree_cpu_io_mixed_tg | 548 ms                                                              | 553 ms: 1.01x slower                                                   |
| async_tree_cpu_io_mixed    | 516 ms                                                              | 535 ms: 1.04x slower                                                   |
| async_tree_io              | 691 ms                                                              | 718 ms: 1.04x slower                                                   |
| Geometric mean             | (ref)                                                               | 1.01x faster                                                           |

Benchmark hidden because not significant (2): async_tree_memoization_tg, async_tree_none_tg

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-darwin-arm64-python-deaf509e8fc6e0363bd6-3.11.0-deaf509 | bm-20231125-darwin-arm64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|----------------|:-------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| pidigits       | 280 ms                                                              | 283 ms: 1.01x slower                                                   |
| float          | 55.1 ms                                                             | 70.6 ms: 1.28x slower                                                  |
| nbody          | 68.5 ms                                                             | 91.1 ms: 1.33x slower                                                  |
| Geometric mean | (ref)                                                               | 1.20x slower                                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-darwin-arm64-python-deaf509e8fc6e0363bd6-3.11.0-deaf509 | bm-20231125-darwin-arm64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|----------------|:-------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| regex_dna      | 149 ms                                                              | 152 ms: 1.02x slower                                                   |
| regex_effbot   | 2.45 ms                                                             | 2.60 ms: 1.06x slower                                                  |
| regex_v8       | 15.4 ms                                                             | 17.1 ms: 1.11x slower                                                  |
| regex_compile  | 73.5 ms                                                             | 89.9 ms: 1.22x slower                                                  |
| Geometric mean | (ref)                                                               | 1.10x slower                                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-darwin-arm64-python-deaf509e8fc6e0363bd6-3.11.0-deaf509 | bm-20231125-darwin-arm64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|----------------------|:-------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| json_dumps           | 7.58 ms                                                             | 6.64 ms: 1.14x faster                                                  |
| pickle_pure_python   | 210 us                                                              | 210 us: 1.00x faster                                                   |
| pickle               | 7.17 us                                                             | 7.41 us: 1.03x slower                                                  |
| pickle_dict          | 17.0 us                                                             | 17.9 us: 1.05x slower                                                  |
| unpickle             | 8.35 us                                                             | 9.11 us: 1.09x slower                                                  |
| unpickle_pure_python | 162 us                                                              | 178 us: 1.10x slower                                                   |
| pickle_list          | 2.68 us                                                             | 2.95 us: 1.10x slower                                                  |
| xml_etree_parse      | 97.6 ms                                                             | 108 ms: 1.10x slower                                                   |
| json_loads           | 15.5 us                                                             | 17.4 us: 1.12x slower                                                  |
| unpickle_list        | 2.76 us                                                             | 3.14 us: 1.14x slower                                                  |
| xml_etree_iterparse  | 67.5 ms                                                             | 81.5 ms: 1.21x slower                                                  |
| xml_etree_process    | 34.1 ms                                                             | 42.5 ms: 1.25x slower                                                  |
| tomli_loads          | 1.32 sec                                                            | 1.71 sec: 1.30x slower                                                 |
| xml_etree_generate   | 47.1 ms                                                             | 62.7 ms: 1.33x slower                                                  |
| Geometric mean       | (ref)                                                               | 1.12x slower                                                           |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-darwin-arm64-python-deaf509e8fc6e0363bd6-3.11.0-deaf509 | bm-20231125-darwin-arm64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|------------------------|:-------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| python_startup         | 11.5 ms                                                             | 11.8 ms: 1.02x slower                                                  |
| python_startup_no_site | 9.37 ms                                                             | 10.4 ms: 1.11x slower                                                  |
| Geometric mean         | (ref)                                                               | 1.07x slower                                                           |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-darwin-arm64-python-deaf509e8fc6e0363bd6-3.11.0-deaf509 | bm-20231125-darwin-arm64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|-----------|:-------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| mako      | 8.25 ms                                                             | 9.81 ms: 1.19x slower                                                  |

All benchmarks:
===============

| Benchmark                  | bm-20221024-darwin-arm64-python-deaf509e8fc6e0363bd6-3.11.0-deaf509 | bm-20231125-darwin-arm64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|----------------------------|:-------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| typing_runtime_protocols   | 322 us                                                              | 81.6 us: 3.94x faster                                                  |
| asyncio_tcp                | 664 ms                                                              | 405 ms: 1.64x faster                                                   |
| json_dumps                 | 7.58 ms                                                             | 6.64 ms: 1.14x faster                                                  |
| unpack_sequence            | 32.3 ns                                                             | 28.6 ns: 1.13x faster                                                  |
| generators                 | 29.0 ms                                                             | 26.0 ms: 1.12x faster                                                  |
| asyncio_tcp_ssl            | 1.43 sec                                                            | 1.31 sec: 1.09x faster                                                 |
| mdp                        | 1.84 sec                                                            | 1.73 sec: 1.06x faster                                                 |
| gc_traversal               | 2.53 ms                                                             | 2.41 ms: 1.05x faster                                                  |
| async_tree_none            | 277 ms                                                              | 264 ms: 1.05x faster                                                   |
| async_tree_memoization     | 353 ms                                                              | 340 ms: 1.04x faster                                                   |
| deepcopy_memo              | 28.7 us                                                             | 27.8 us: 1.03x faster                                                  |
| async_tree_io_tg           | 723 ms                                                              | 700 ms: 1.03x faster                                                   |
| raytrace                   | 205 ms                                                              | 199 ms: 1.03x faster                                                   |
| create_gc_cycles           | 714 us                                                              | 703 us: 1.02x faster                                                   |
| sqlglot_parse              | 874 us                                                              | 867 us: 1.01x faster                                                   |
| pickle_pure_python         | 210 us                                                              | 210 us: 1.00x faster                                                   |
| asyncio_websockets         | 408 ms                                                              | 409 ms: 1.00x slower                                                   |
| async_tree_cpu_io_mixed_tg | 548 ms                                                              | 553 ms: 1.01x slower                                                   |
| pidigits                   | 280 ms                                                              | 283 ms: 1.01x slower                                                   |
| sqlglot_transpile          | 1.04 ms                                                             | 1.05 ms: 1.02x slower                                                  |
| regex_dna                  | 149 ms                                                              | 152 ms: 1.02x slower                                                   |
| python_startup             | 11.5 ms                                                             | 11.8 ms: 1.02x slower                                                  |
| deepcopy                   | 232 us                                                              | 239 us: 1.03x slower                                                   |
| chaos                      | 48.2 ms                                                             | 49.7 ms: 1.03x slower                                                  |
| pickle                     | 7.17 us                                                             | 7.41 us: 1.03x slower                                                  |
| richards_super             | 36.7 ms                                                             | 38.0 ms: 1.04x slower                                                  |
| tornado_http               | 70.9 ms                                                             | 73.5 ms: 1.04x slower                                                  |
| async_tree_cpu_io_mixed    | 516 ms                                                              | 535 ms: 1.04x slower                                                   |
| async_tree_io              | 691 ms                                                              | 718 ms: 1.04x slower                                                   |
| dulwich_log                | 29.2 ms                                                             | 30.6 ms: 1.05x slower                                                  |
| sympy_sum                  | 80.8 ms                                                             | 84.8 ms: 1.05x slower                                                  |
| pickle_dict                | 17.0 us                                                             | 17.9 us: 1.05x slower                                                  |
| bench_mp_pool              | 42.1 ms                                                             | 44.6 ms: 1.06x slower                                                  |
| regex_effbot               | 2.45 ms                                                             | 2.60 ms: 1.06x slower                                                  |
| dask                       | 219 ms                                                              | 233 ms: 1.06x slower                                                   |
| logging_simple             | 3.45 us                                                             | 3.71 us: 1.07x slower                                                  |
| deepcopy_reduce            | 1.96 us                                                             | 2.11 us: 1.08x slower                                                  |
| logging_format             | 3.73 us                                                             | 4.02 us: 1.08x slower                                                  |
| pathlib                    | 23.0 ms                                                             | 24.9 ms: 1.08x slower                                                  |
| docutils                   | 1.43 sec                                                            | 1.55 sec: 1.08x slower                                                 |
| meteor_contest             | 75.3 ms                                                             | 82.0 ms: 1.09x slower                                                  |
| unpickle                   | 8.35 us                                                             | 9.11 us: 1.09x slower                                                  |
| pycparser                  | 658 ms                                                              | 719 ms: 1.09x slower                                                   |
| sympy_integrate            | 11.2 ms                                                             | 12.3 ms: 1.09x slower                                                  |
| unpickle_pure_python       | 162 us                                                              | 178 us: 1.10x slower                                                   |
| json                       | 2.77 ms                                                             | 3.04 ms: 1.10x slower                                                  |
| pickle_list                | 2.68 us                                                             | 2.95 us: 1.10x slower                                                  |
| xml_etree_parse            | 97.6 ms                                                             | 108 ms: 1.10x slower                                                   |
| sympy_str                  | 144 ms                                                              | 160 ms: 1.11x slower                                                   |
| regex_v8                   | 15.4 ms                                                             | 17.1 ms: 1.11x slower                                                  |
| python_startup_no_site     | 9.37 ms                                                             | 10.4 ms: 1.11x slower                                                  |
| go                         | 102 ms                                                              | 113 ms: 1.11x slower                                                   |
| richards                   | 30.7 ms                                                             | 34.1 ms: 1.11x slower                                                  |
| sympy_expand               | 236 ms                                                              | 264 ms: 1.12x slower                                                   |
| json_loads                 | 15.5 us                                                             | 17.4 us: 1.12x slower                                                  |
| comprehensions             | 14.6 us                                                             | 16.5 us: 1.13x slower                                                  |
| logging_silent             | 64.3 ns                                                             | 73.2 ns: 1.14x slower                                                  |
| unpickle_list              | 2.76 us                                                             | 3.14 us: 1.14x slower                                                  |
| bench_thread_pool          | 467 us                                                              | 534 us: 1.14x slower                                                   |
| scimark_lu                 | 67.9 ms                                                             | 78.4 ms: 1.15x slower                                                  |
| coverage                   | 41.4 ms                                                             | 47.9 ms: 1.16x slower                                                  |
| crypto_pyaes               | 47.9 ms                                                             | 55.7 ms: 1.16x slower                                                  |
| 2to3                       | 154 ms                                                              | 182 ms: 1.19x slower                                                   |
| mako                       | 8.25 ms                                                             | 9.81 ms: 1.19x slower                                                  |
| xml_etree_iterparse        | 67.5 ms                                                             | 81.5 ms: 1.21x slower                                                  |
| coroutines                 | 16.4 ms                                                             | 19.9 ms: 1.21x slower                                                  |
| regex_compile              | 73.5 ms                                                             | 89.9 ms: 1.22x slower                                                  |
| pprint_safe_repr           | 480 ms                                                              | 596 ms: 1.24x slower                                                   |
| pprint_pformat             | 986 ms                                                              | 1.23 sec: 1.25x slower                                                 |
| xml_etree_process          | 34.1 ms                                                             | 42.5 ms: 1.25x slower                                                  |
| chameleon                  | 4.21 ms                                                             | 5.28 ms: 1.25x slower                                                  |
| sqlite_synth               | 1.36 us                                                             | 1.71 us: 1.26x slower                                                  |
| sqlglot_normalize          | 160 ms                                                              | 204 ms: 1.27x slower                                                   |
| pyflate                    | 295 ms                                                              | 378 ms: 1.28x slower                                                   |
| float                      | 55.1 ms                                                             | 70.6 ms: 1.28x slower                                                  |
| sqlglot_optimize           | 29.6 ms                                                             | 38.2 ms: 1.29x slower                                                  |
| tomli_loads                | 1.32 sec                                                            | 1.71 sec: 1.30x slower                                                 |
| scimark_monte_carlo        | 45.7 ms                                                             | 60.3 ms: 1.32x slower                                                  |
| nqueens                    | 54.3 ms                                                             | 71.9 ms: 1.32x slower                                                  |
| nbody                      | 68.5 ms                                                             | 91.1 ms: 1.33x slower                                                  |
| xml_etree_generate         | 47.1 ms                                                             | 62.7 ms: 1.33x slower                                                  |
| deltablue                  | 2.69 ms                                                             | 3.63 ms: 1.35x slower                                                  |
| scimark_fft                | 186 ms                                                              | 256 ms: 1.37x slower                                                   |
| hexiom                     | 4.55 ms                                                             | 6.31 ms: 1.39x slower                                                  |
| fannkuch                   | 247 ms                                                              | 345 ms: 1.40x slower                                                   |
| mypy2                      | 187 ms                                                              | 267 ms: 1.43x slower                                                   |
| scimark_sparse_mat_mult    | 3.00 ms                                                             | 4.30 ms: 1.44x slower                                                  |
| scimark_sor                | 74.4 ms                                                             | 109 ms: 1.47x slower                                                   |
| spectral_norm              | 69.4 ms                                                             | 104 ms: 1.50x slower                                                   |
| telco                      | 3.17 ms                                                             | 4.86 ms: 1.53x slower                                                  |
| async_generators           | 191 ms                                                              | 313 ms: 1.63x slower                                                   |
| Geometric mean             | (ref)                                                               | 1.10x slower                                                           |

Benchmark hidden because not significant (2): async_tree_memoization_tg, async_tree_none_tg
Ignored benchmarks (11) of results/bm-20221024-3.11.0-deaf509/bm-20221024-darwin-arm64-python-deaf509e8fc6e0363bd6-3.11.0-deaf509.json: aiohttp, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.07x
- 95% likely to have a slowdown of 1.06x
- 99% likely to have a slowdown of 1.05x
