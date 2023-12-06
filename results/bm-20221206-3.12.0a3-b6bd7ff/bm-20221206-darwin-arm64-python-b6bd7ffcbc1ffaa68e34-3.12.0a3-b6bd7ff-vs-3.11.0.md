
# Results vs. 3.11.0

- fork: python
- ref: b6bd7ffcbc1ffaa68e34
- machine: darwin-arm64
- commit hash: b6bd7ff
- commit date: 2022-12-06
- overall geometric mean: 1.05x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.02x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-darwin-arm64-python-deaf509e8fc6e0363bd6-3.11.0-deaf509 | bm-20221206-darwin-arm64-python-b6bd7ffcbc1ffaa68e34-3.12.0a3-b6bd7ff |
|----------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| 2to3           | 154 ms                                                              | 166 ms: 1.08x slower                                                  |
| chameleon      | 4.21 ms                                                             | 4.68 ms: 1.11x slower                                                 |
| docutils       | 1.43 sec                                                            | 1.48 sec: 1.04x slower                                                |
| html5lib       | 33.3 ms                                                             | 34.7 ms: 1.04x slower                                                 |
| Geometric mean | (ref)                                                               | 1.07x slower                                                          |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20221024-darwin-arm64-python-deaf509e8fc6e0363bd6-3.11.0-deaf509 | bm-20221206-darwin-arm64-python-b6bd7ffcbc1ffaa68e34-3.12.0a3-b6bd7ff |
|----------------------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| async_tree_memoization     | 353 ms                                                              | 333 ms: 1.06x faster                                                  |
| async_tree_cpu_io_mixed_tg | 548 ms                                                              | 553 ms: 1.01x slower                                                  |
| async_tree_io_tg           | 723 ms                                                              | 733 ms: 1.01x slower                                                  |
| async_tree_cpu_io_mixed    | 516 ms                                                              | 539 ms: 1.04x slower                                                  |
| async_tree_none            | 277 ms                                                              | 295 ms: 1.07x slower                                                  |
| async_tree_io              | 691 ms                                                              | 758 ms: 1.10x slower                                                  |
| Geometric mean             | (ref)                                                               | 1.02x slower                                                          |

Benchmark hidden because not significant (2): async_tree_memoization_tg, async_tree_none_tg

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-darwin-arm64-python-deaf509e8fc6e0363bd6-3.11.0-deaf509 | bm-20221206-darwin-arm64-python-b6bd7ffcbc1ffaa68e34-3.12.0a3-b6bd7ff |
|----------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| nbody          | 68.5 ms                                                             | 68.4 ms: 1.00x faster                                                 |
| pidigits       | 280 ms                                                              | 280 ms: 1.00x faster                                                  |
| float          | 55.1 ms                                                             | 57.6 ms: 1.05x slower                                                 |
| Geometric mean | (ref)                                                               | 1.01x slower                                                          |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-darwin-arm64-python-deaf509e8fc6e0363bd6-3.11.0-deaf509 | bm-20221206-darwin-arm64-python-b6bd7ffcbc1ffaa68e34-3.12.0a3-b6bd7ff |
|----------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| regex_v8       | 15.4 ms                                                             | 15.1 ms: 1.02x faster                                                 |
| regex_dna      | 149 ms                                                              | 147 ms: 1.01x faster                                                  |
| regex_compile  | 73.5 ms                                                             | 78.1 ms: 1.06x slower                                                 |
| Geometric mean | (ref)                                                               | 1.01x slower                                                          |

Benchmark hidden because not significant (1): regex_effbot

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-darwin-arm64-python-deaf509e8fc6e0363bd6-3.11.0-deaf509 | bm-20221206-darwin-arm64-python-b6bd7ffcbc1ffaa68e34-3.12.0a3-b6bd7ff |
|----------------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| json_dumps           | 7.58 ms                                                             | 6.15 ms: 1.23x faster                                                 |
| unpickle_pure_python | 162 us                                                              | 160 us: 1.01x faster                                                  |
| xml_etree_parse      | 97.6 ms                                                             | 96.5 ms: 1.01x faster                                                 |
| pickle               | 7.17 us                                                             | 7.13 us: 1.00x faster                                                 |
| pickle_list          | 2.68 us                                                             | 2.67 us: 1.00x faster                                                 |
| unpickle_list        | 2.76 us                                                             | 2.75 us: 1.00x faster                                                 |
| pickle_dict          | 17.0 us                                                             | 17.0 us: 1.00x slower                                                 |
| xml_etree_generate   | 47.1 ms                                                             | 47.5 ms: 1.01x slower                                                 |
| unpickle             | 8.35 us                                                             | 8.45 us: 1.01x slower                                                 |
| pickle_pure_python   | 210 us                                                              | 213 us: 1.01x slower                                                  |
| json_loads           | 15.5 us                                                             | 15.8 us: 1.02x slower                                                 |
| xml_etree_iterparse  | 67.5 ms                                                             | 70.3 ms: 1.04x slower                                                 |
| xml_etree_process    | 34.1 ms                                                             | 36.4 ms: 1.07x slower                                                 |
| tomli_loads          | 1.32 sec                                                            | 1.51 sec: 1.14x slower                                                |
| Geometric mean       | (ref)                                                               | 1.00x slower                                                          |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-darwin-arm64-python-deaf509e8fc6e0363bd6-3.11.0-deaf509 | bm-20221206-darwin-arm64-python-b6bd7ffcbc1ffaa68e34-3.12.0a3-b6bd7ff |
|------------------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| python_startup         | 11.5 ms                                                             | 11.4 ms: 1.01x faster                                                 |
| python_startup_no_site | 9.37 ms                                                             | 9.48 ms: 1.01x slower                                                 |
| Geometric mean         | (ref)                                                               | 1.00x slower                                                          |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20221024-darwin-arm64-python-deaf509e8fc6e0363bd6-3.11.0-deaf509 | bm-20221206-darwin-arm64-python-b6bd7ffcbc1ffaa68e34-3.12.0a3-b6bd7ff |
|-----------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| mako            | 8.25 ms                                                             | 7.45 ms: 1.11x faster                                                 |
| genshi_xml      | 28.3 ms                                                             | 30.7 ms: 1.09x slower                                                 |
| genshi_text     | 14.5 ms                                                             | 15.9 ms: 1.10x slower                                                 |
| django_template | 19.6 ms                                                             | 21.9 ms: 1.12x slower                                                 |
| Geometric mean  | (ref)                                                               | 1.05x slower                                                          |

All benchmarks:
===============

| Benchmark                  | bm-20221024-darwin-arm64-python-deaf509e8fc6e0363bd6-3.11.0-deaf509 | bm-20221206-darwin-arm64-python-b6bd7ffcbc1ffaa68e34-3.12.0a3-b6bd7ff |
|----------------------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| json_dumps                 | 7.58 ms                                                             | 6.15 ms: 1.23x faster                                                 |
| scimark_sparse_mat_mult    | 3.00 ms                                                             | 2.65 ms: 1.13x faster                                                 |
| mako                       | 8.25 ms                                                             | 7.45 ms: 1.11x faster                                                 |
| gc_traversal               | 2.53 ms                                                             | 2.38 ms: 1.06x faster                                                 |
| async_tree_memoization     | 353 ms                                                              | 333 ms: 1.06x faster                                                  |
| create_gc_cycles           | 714 us                                                              | 682 us: 1.05x faster                                                  |
| mdp                        | 1.84 sec                                                            | 1.77 sec: 1.04x faster                                                |
| telco                      | 3.17 ms                                                             | 3.09 ms: 1.02x faster                                                 |
| regex_v8                   | 15.4 ms                                                             | 15.1 ms: 1.02x faster                                                 |
| regex_dna                  | 149 ms                                                              | 147 ms: 1.01x faster                                                  |
| unpickle_pure_python       | 162 us                                                              | 160 us: 1.01x faster                                                  |
| xml_etree_parse            | 97.6 ms                                                             | 96.5 ms: 1.01x faster                                                 |
| python_startup             | 11.5 ms                                                             | 11.4 ms: 1.01x faster                                                 |
| pickle                     | 7.17 us                                                             | 7.13 us: 1.00x faster                                                 |
| pickle_list                | 2.68 us                                                             | 2.67 us: 1.00x faster                                                 |
| unpickle_list              | 2.76 us                                                             | 2.75 us: 1.00x faster                                                 |
| nbody                      | 68.5 ms                                                             | 68.4 ms: 1.00x faster                                                 |
| pidigits                   | 280 ms                                                              | 280 ms: 1.00x faster                                                  |
| pickle_dict                | 17.0 us                                                             | 17.0 us: 1.00x slower                                                 |
| dulwich_log                | 29.2 ms                                                             | 29.4 ms: 1.01x slower                                                 |
| meteor_contest             | 75.3 ms                                                             | 75.9 ms: 1.01x slower                                                 |
| xml_etree_generate         | 47.1 ms                                                             | 47.5 ms: 1.01x slower                                                 |
| async_tree_cpu_io_mixed_tg | 548 ms                                                              | 553 ms: 1.01x slower                                                  |
| pathlib                    | 23.0 ms                                                             | 23.3 ms: 1.01x slower                                                 |
| unpickle                   | 8.35 us                                                             | 8.45 us: 1.01x slower                                                 |
| pickle_pure_python         | 210 us                                                              | 213 us: 1.01x slower                                                  |
| python_startup_no_site     | 9.37 ms                                                             | 9.48 ms: 1.01x slower                                                 |
| async_tree_io_tg           | 723 ms                                                              | 733 ms: 1.01x slower                                                  |
| json_loads                 | 15.5 us                                                             | 15.8 us: 1.02x slower                                                 |
| asyncio_tcp_ssl            | 1.43 sec                                                            | 1.46 sec: 1.02x slower                                                |
| typing_runtime_protocols   | 322 us                                                              | 329 us: 1.02x slower                                                  |
| json                       | 2.77 ms                                                             | 2.85 ms: 1.03x slower                                                 |
| docutils                   | 1.43 sec                                                            | 1.48 sec: 1.04x slower                                                |
| deepcopy                   | 232 us                                                              | 240 us: 1.04x slower                                                  |
| bench_thread_pool          | 467 us                                                              | 485 us: 1.04x slower                                                  |
| pycparser                  | 658 ms                                                              | 686 ms: 1.04x slower                                                  |
| html5lib                   | 33.3 ms                                                             | 34.7 ms: 1.04x slower                                                 |
| xml_etree_iterparse        | 67.5 ms                                                             | 70.3 ms: 1.04x slower                                                 |
| sympy_expand               | 236 ms                                                              | 246 ms: 1.04x slower                                                  |
| async_tree_cpu_io_mixed    | 516 ms                                                              | 539 ms: 1.04x slower                                                  |
| float                      | 55.1 ms                                                             | 57.6 ms: 1.05x slower                                                 |
| pprint_pformat             | 986 ms                                                              | 1.03 sec: 1.05x slower                                                |
| sqlite_synth               | 1.36 us                                                             | 1.43 us: 1.05x slower                                                 |
| sympy_sum                  | 80.8 ms                                                             | 85.0 ms: 1.05x slower                                                 |
| pprint_safe_repr           | 480 ms                                                              | 507 ms: 1.06x slower                                                  |
| deltablue                  | 2.69 ms                                                             | 2.83 ms: 1.06x slower                                                 |
| sympy_str                  | 144 ms                                                              | 153 ms: 1.06x slower                                                  |
| thrift                     | 420 us                                                              | 445 us: 1.06x slower                                                  |
| sympy_integrate            | 11.2 ms                                                             | 11.9 ms: 1.06x slower                                                 |
| raytrace                   | 205 ms                                                              | 218 ms: 1.06x slower                                                  |
| regex_compile              | 73.5 ms                                                             | 78.1 ms: 1.06x slower                                                 |
| deepcopy_reduce            | 1.96 us                                                             | 2.09 us: 1.07x slower                                                 |
| chaos                      | 48.2 ms                                                             | 51.4 ms: 1.07x slower                                                 |
| async_tree_none            | 277 ms                                                              | 295 ms: 1.07x slower                                                  |
| xml_etree_process          | 34.1 ms                                                             | 36.4 ms: 1.07x slower                                                 |
| crypto_pyaes               | 47.9 ms                                                             | 51.5 ms: 1.07x slower                                                 |
| 2to3                       | 154 ms                                                              | 166 ms: 1.08x slower                                                  |
| fannkuch                   | 247 ms                                                              | 267 ms: 1.08x slower                                                  |
| genshi_xml                 | 28.3 ms                                                             | 30.7 ms: 1.09x slower                                                 |
| async_generators           | 191 ms                                                              | 208 ms: 1.09x slower                                                  |
| hexiom                     | 4.55 ms                                                             | 4.97 ms: 1.09x slower                                                 |
| async_tree_io              | 691 ms                                                              | 758 ms: 1.10x slower                                                  |
| genshi_text                | 14.5 ms                                                             | 15.9 ms: 1.10x slower                                                 |
| logging_format             | 3.73 us                                                             | 4.10 us: 1.10x slower                                                 |
| logging_simple             | 3.45 us                                                             | 3.81 us: 1.10x slower                                                 |
| nqueens                    | 54.3 ms                                                             | 60.0 ms: 1.11x slower                                                 |
| chameleon                  | 4.21 ms                                                             | 4.68 ms: 1.11x slower                                                 |
| django_template            | 19.6 ms                                                             | 21.9 ms: 1.12x slower                                                 |
| sqlglot_optimize           | 29.6 ms                                                             | 33.1 ms: 1.12x slower                                                 |
| sqlglot_normalize          | 160 ms                                                              | 180 ms: 1.12x slower                                                  |
| richards                   | 30.7 ms                                                             | 34.7 ms: 1.13x slower                                                 |
| richards_super             | 36.7 ms                                                             | 41.5 ms: 1.13x slower                                                 |
| tomli_loads                | 1.32 sec                                                            | 1.51 sec: 1.14x slower                                                |
| spectral_norm              | 69.4 ms                                                             | 79.6 ms: 1.15x slower                                                 |
| pyflate                    | 295 ms                                                              | 340 ms: 1.15x slower                                                  |
| sqlglot_transpile          | 1.04 ms                                                             | 1.19 ms: 1.15x slower                                                 |
| go                         | 102 ms                                                              | 118 ms: 1.15x slower                                                  |
| sqlglot_parse              | 874 us                                                              | 1.02 ms: 1.17x slower                                                 |
| scimark_monte_carlo        | 45.7 ms                                                             | 53.6 ms: 1.17x slower                                                 |
| comprehensions             | 14.6 us                                                             | 17.3 us: 1.18x slower                                                 |
| scimark_lu                 | 67.9 ms                                                             | 81.7 ms: 1.20x slower                                                 |
| logging_silent             | 64.3 ns                                                             | 79.3 ns: 1.23x slower                                                 |
| coroutines                 | 16.4 ms                                                             | 20.5 ms: 1.25x slower                                                 |
| generators                 | 29.0 ms                                                             | 37.2 ms: 1.28x slower                                                 |
| scimark_sor                | 74.4 ms                                                             | 105 ms: 1.41x slower                                                  |
| dask                       | 219 ms                                                              | 331 ms: 1.51x slower                                                  |
| Geometric mean             | (ref)                                                               | 1.05x slower                                                          |

Benchmark hidden because not significant (9): async_tree_memoization_tg, asyncio_tcp, async_tree_none_tg, regex_effbot, deepcopy_memo, scimark_fft, asyncio_websockets, unpack_sequence, bench_mp_pool
Ignored benchmarks (9) of results/bm-20221024-3.11.0-deaf509/bm-20221024-darwin-arm64-python-deaf509e8fc6e0363bd6-3.11.0-deaf509.json: aiohttp, coverage, flaskblogging, gunicorn, mypy2, pylint, sqlalchemy_declarative, sqlalchemy_imperative, tornado_http


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.03x
- 95% likely to have a slowdown of 1.03x
- 99% likely to have a slowdown of 1.02x
