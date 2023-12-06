
# Results vs. 3.11.0

- fork: python
- ref: 3c67ec394faac79d2608
- machine: darwin-arm64
- commit hash: 3c67ec3
- commit date: 2023-02-07
- overall geometric mean: 1.04x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.01x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-darwin-arm64-python-deaf509e8fc6e0363bd6-3.11.0-deaf509 | bm-20230207-darwin-arm64-python-3c67ec394faac79d2608-3.12.0a5-3c67ec3 |
|----------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| 2to3           | 154 ms                                                              | 166 ms: 1.08x slower                                                  |
| chameleon      | 4.21 ms                                                             | 4.69 ms: 1.12x slower                                                 |
| docutils       | 1.43 sec                                                            | 1.48 sec: 1.04x slower                                                |
| html5lib       | 33.3 ms                                                             | 34.6 ms: 1.04x slower                                                 |
| Geometric mean | (ref)                                                               | 1.06x slower                                                          |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20221024-darwin-arm64-python-deaf509e8fc6e0363bd6-3.11.0-deaf509 | bm-20230207-darwin-arm64-python-3c67ec394faac79d2608-3.12.0a5-3c67ec3 |
|----------------------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| async_tree_memoization     | 353 ms                                                              | 336 ms: 1.05x faster                                                  |
| async_tree_cpu_io_mixed_tg | 548 ms                                                              | 555 ms: 1.01x slower                                                  |
| async_tree_none_tg         | 277 ms                                                              | 281 ms: 1.02x slower                                                  |
| async_tree_io_tg           | 723 ms                                                              | 739 ms: 1.02x slower                                                  |
| async_tree_cpu_io_mixed    | 516 ms                                                              | 533 ms: 1.03x slower                                                  |
| async_tree_none            | 277 ms                                                              | 290 ms: 1.05x slower                                                  |
| async_tree_io              | 691 ms                                                              | 753 ms: 1.09x slower                                                  |
| Geometric mean             | (ref)                                                               | 1.02x slower                                                          |

Benchmark hidden because not significant (1): async_tree_memoization_tg

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-darwin-arm64-python-deaf509e8fc6e0363bd6-3.11.0-deaf509 | bm-20230207-darwin-arm64-python-3c67ec394faac79d2608-3.12.0a5-3c67ec3 |
|----------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| pidigits       | 280 ms                                                              | 281 ms: 1.00x slower                                                  |
| float          | 55.1 ms                                                             | 57.5 ms: 1.04x slower                                                 |
| Geometric mean | (ref)                                                               | 1.02x slower                                                          |

Benchmark hidden because not significant (1): nbody

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-darwin-arm64-python-deaf509e8fc6e0363bd6-3.11.0-deaf509 | bm-20230207-darwin-arm64-python-3c67ec394faac79d2608-3.12.0a5-3c67ec3 |
|----------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| regex_dna      | 149 ms                                                              | 147 ms: 1.02x faster                                                  |
| regex_v8       | 15.4 ms                                                             | 15.3 ms: 1.01x faster                                                 |
| regex_effbot   | 2.45 ms                                                             | 2.45 ms: 1.00x faster                                                 |
| regex_compile  | 73.5 ms                                                             | 76.0 ms: 1.03x slower                                                 |
| Geometric mean | (ref)                                                               | 1.00x slower                                                          |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-darwin-arm64-python-deaf509e8fc6e0363bd6-3.11.0-deaf509 | bm-20230207-darwin-arm64-python-3c67ec394faac79d2608-3.12.0a5-3c67ec3 |
|----------------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| json_dumps           | 7.58 ms                                                             | 6.08 ms: 1.25x faster                                                 |
| xml_etree_parse      | 97.6 ms                                                             | 95.0 ms: 1.03x faster                                                 |
| pickle               | 7.17 us                                                             | 7.09 us: 1.01x faster                                                 |
| pickle_dict          | 17.0 us                                                             | 16.8 us: 1.01x faster                                                 |
| unpickle_pure_python | 162 us                                                              | 161 us: 1.01x faster                                                  |
| json_loads           | 15.5 us                                                             | 15.7 us: 1.01x slower                                                 |
| pickle_list          | 2.68 us                                                             | 2.72 us: 1.02x slower                                                 |
| unpickle             | 8.35 us                                                             | 8.50 us: 1.02x slower                                                 |
| pickle_pure_python   | 210 us                                                              | 214 us: 1.02x slower                                                  |
| xml_etree_generate   | 47.1 ms                                                             | 48.7 ms: 1.03x slower                                                 |
| unpickle_list        | 2.76 us                                                             | 2.85 us: 1.04x slower                                                 |
| tomli_loads          | 1.32 sec                                                            | 1.38 sec: 1.04x slower                                                |
| xml_etree_iterparse  | 67.5 ms                                                             | 71.9 ms: 1.07x slower                                                 |
| xml_etree_process    | 34.1 ms                                                             | 37.1 ms: 1.09x slower                                                 |
| Geometric mean       | (ref)                                                               | 1.00x slower                                                          |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-darwin-arm64-python-deaf509e8fc6e0363bd6-3.11.0-deaf509 | bm-20230207-darwin-arm64-python-3c67ec394faac79d2608-3.12.0a5-3c67ec3 |
|------------------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| python_startup_no_site | 9.37 ms                                                             | 9.55 ms: 1.02x slower                                                 |
| python_startup         | 11.5 ms                                                             | 11.8 ms: 1.02x slower                                                 |
| Geometric mean         | (ref)                                                               | 1.02x slower                                                          |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20221024-darwin-arm64-python-deaf509e8fc6e0363bd6-3.11.0-deaf509 | bm-20230207-darwin-arm64-python-3c67ec394faac79d2608-3.12.0a5-3c67ec3 |
|-----------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| mako            | 8.25 ms                                                             | 6.94 ms: 1.19x faster                                                 |
| genshi_xml      | 28.3 ms                                                             | 30.7 ms: 1.09x slower                                                 |
| genshi_text     | 14.5 ms                                                             | 16.3 ms: 1.13x slower                                                 |
| django_template | 19.6 ms                                                             | 22.5 ms: 1.15x slower                                                 |
| Geometric mean  | (ref)                                                               | 1.04x slower                                                          |

All benchmarks:
===============

| Benchmark                  | bm-20221024-darwin-arm64-python-deaf509e8fc6e0363bd6-3.11.0-deaf509 | bm-20230207-darwin-arm64-python-3c67ec394faac79d2608-3.12.0a5-3c67ec3 |
|----------------------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| asyncio_tcp                | 664 ms                                                              | 437 ms: 1.52x faster                                                  |
| json_dumps                 | 7.58 ms                                                             | 6.08 ms: 1.25x faster                                                 |
| mako                       | 8.25 ms                                                             | 6.94 ms: 1.19x faster                                                 |
| asyncio_tcp_ssl            | 1.43 sec                                                            | 1.28 sec: 1.11x faster                                                |
| scimark_sparse_mat_mult    | 3.00 ms                                                             | 2.70 ms: 1.11x faster                                                 |
| gc_traversal               | 2.53 ms                                                             | 2.39 ms: 1.06x faster                                                 |
| async_tree_memoization     | 353 ms                                                              | 336 ms: 1.05x faster                                                  |
| mdp                        | 1.84 sec                                                            | 1.76 sec: 1.05x faster                                                |
| create_gc_cycles           | 714 us                                                              | 687 us: 1.04x faster                                                  |
| xml_etree_parse            | 97.6 ms                                                             | 95.0 ms: 1.03x faster                                                 |
| regex_dna                  | 149 ms                                                              | 147 ms: 1.02x faster                                                  |
| scimark_fft                | 186 ms                                                              | 183 ms: 1.01x faster                                                  |
| comprehensions             | 14.6 us                                                             | 14.5 us: 1.01x faster                                                 |
| pickle                     | 7.17 us                                                             | 7.09 us: 1.01x faster                                                 |
| typing_runtime_protocols   | 322 us                                                              | 319 us: 1.01x faster                                                  |
| pickle_dict                | 17.0 us                                                             | 16.8 us: 1.01x faster                                                 |
| unpickle_pure_python       | 162 us                                                              | 161 us: 1.01x faster                                                  |
| regex_v8                   | 15.4 ms                                                             | 15.3 ms: 1.01x faster                                                 |
| regex_effbot               | 2.45 ms                                                             | 2.45 ms: 1.00x faster                                                 |
| fannkuch                   | 247 ms                                                              | 246 ms: 1.00x faster                                                  |
| deepcopy_memo              | 28.7 us                                                             | 28.6 us: 1.00x faster                                                 |
| asyncio_websockets         | 408 ms                                                              | 409 ms: 1.00x slower                                                  |
| chaos                      | 48.2 ms                                                             | 48.4 ms: 1.00x slower                                                 |
| pidigits                   | 280 ms                                                              | 281 ms: 1.00x slower                                                  |
| telco                      | 3.17 ms                                                             | 3.18 ms: 1.01x slower                                                 |
| json                       | 2.77 ms                                                             | 2.79 ms: 1.01x slower                                                 |
| json_loads                 | 15.5 us                                                             | 15.7 us: 1.01x slower                                                 |
| async_tree_cpu_io_mixed_tg | 548 ms                                                              | 555 ms: 1.01x slower                                                  |
| hexiom                     | 4.55 ms                                                             | 4.61 ms: 1.01x slower                                                 |
| async_tree_none_tg         | 277 ms                                                              | 281 ms: 1.02x slower                                                  |
| pickle_list                | 2.68 us                                                             | 2.72 us: 1.02x slower                                                 |
| pycparser                  | 658 ms                                                              | 670 ms: 1.02x slower                                                  |
| unpickle                   | 8.35 us                                                             | 8.50 us: 1.02x slower                                                 |
| pickle_pure_python         | 210 us                                                              | 214 us: 1.02x slower                                                  |
| python_startup_no_site     | 9.37 ms                                                             | 9.55 ms: 1.02x slower                                                 |
| sympy_sum                  | 80.8 ms                                                             | 82.4 ms: 1.02x slower                                                 |
| async_tree_io_tg           | 723 ms                                                              | 739 ms: 1.02x slower                                                  |
| python_startup             | 11.5 ms                                                             | 11.8 ms: 1.02x slower                                                 |
| sympy_str                  | 144 ms                                                              | 148 ms: 1.02x slower                                                  |
| meteor_contest             | 75.3 ms                                                             | 77.2 ms: 1.03x slower                                                 |
| sympy_integrate            | 11.2 ms                                                             | 11.5 ms: 1.03x slower                                                 |
| sqlite_synth               | 1.36 us                                                             | 1.40 us: 1.03x slower                                                 |
| xml_etree_generate         | 47.1 ms                                                             | 48.7 ms: 1.03x slower                                                 |
| async_tree_cpu_io_mixed    | 516 ms                                                              | 533 ms: 1.03x slower                                                  |
| regex_compile              | 73.5 ms                                                             | 76.0 ms: 1.03x slower                                                 |
| unpack_sequence            | 32.3 ns                                                             | 33.4 ns: 1.03x slower                                                 |
| unpickle_list              | 2.76 us                                                             | 2.85 us: 1.04x slower                                                 |
| sqlalchemy_declarative     | 60.4 ms                                                             | 62.6 ms: 1.04x slower                                                 |
| docutils                   | 1.43 sec                                                            | 1.48 sec: 1.04x slower                                                |
| sympy_expand               | 236 ms                                                              | 245 ms: 1.04x slower                                                  |
| html5lib                   | 33.3 ms                                                             | 34.6 ms: 1.04x slower                                                 |
| bench_mp_pool              | 42.1 ms                                                             | 43.7 ms: 1.04x slower                                                 |
| float                      | 55.1 ms                                                             | 57.5 ms: 1.04x slower                                                 |
| deltablue                  | 2.69 ms                                                             | 2.81 ms: 1.04x slower                                                 |
| tomli_loads                | 1.32 sec                                                            | 1.38 sec: 1.04x slower                                                |
| async_tree_none            | 277 ms                                                              | 290 ms: 1.05x slower                                                  |
| thrift                     | 420 us                                                              | 443 us: 1.05x slower                                                  |
| bench_thread_pool          | 467 us                                                              | 495 us: 1.06x slower                                                  |
| deepcopy                   | 232 us                                                              | 246 us: 1.06x slower                                                  |
| xml_etree_iterparse        | 67.5 ms                                                             | 71.9 ms: 1.07x slower                                                 |
| crypto_pyaes               | 47.9 ms                                                             | 51.6 ms: 1.08x slower                                                 |
| 2to3                       | 154 ms                                                              | 166 ms: 1.08x slower                                                  |
| genshi_xml                 | 28.3 ms                                                             | 30.7 ms: 1.09x slower                                                 |
| xml_etree_process          | 34.1 ms                                                             | 37.1 ms: 1.09x slower                                                 |
| pprint_pformat             | 986 ms                                                              | 1.07 sec: 1.09x slower                                                |
| async_tree_io              | 691 ms                                                              | 753 ms: 1.09x slower                                                  |
| richards                   | 30.7 ms                                                             | 33.5 ms: 1.09x slower                                                 |
| async_generators           | 191 ms                                                              | 209 ms: 1.09x slower                                                  |
| pprint_safe_repr           | 480 ms                                                              | 524 ms: 1.09x slower                                                  |
| pyflate                    | 295 ms                                                              | 324 ms: 1.10x slower                                                  |
| deepcopy_reduce            | 1.96 us                                                             | 2.15 us: 1.10x slower                                                 |
| richards_super             | 36.7 ms                                                             | 40.4 ms: 1.10x slower                                                 |
| nqueens                    | 54.3 ms                                                             | 59.9 ms: 1.10x slower                                                 |
| go                         | 102 ms                                                              | 113 ms: 1.11x slower                                                  |
| raytrace                   | 205 ms                                                              | 229 ms: 1.11x slower                                                  |
| chameleon                  | 4.21 ms                                                             | 4.69 ms: 1.12x slower                                                 |
| sqlglot_optimize           | 29.6 ms                                                             | 33.1 ms: 1.12x slower                                                 |
| genshi_text                | 14.5 ms                                                             | 16.3 ms: 1.13x slower                                                 |
| logging_simple             | 3.45 us                                                             | 3.89 us: 1.13x slower                                                 |
| logging_format             | 3.73 us                                                             | 4.21 us: 1.13x slower                                                 |
| sqlglot_normalize          | 160 ms                                                              | 181 ms: 1.13x slower                                                  |
| django_template            | 19.6 ms                                                             | 22.5 ms: 1.15x slower                                                 |
| scimark_monte_carlo        | 45.7 ms                                                             | 52.9 ms: 1.16x slower                                                 |
| spectral_norm              | 69.4 ms                                                             | 81.8 ms: 1.18x slower                                                 |
| sqlglot_transpile          | 1.04 ms                                                             | 1.23 ms: 1.18x slower                                                 |
| sqlglot_parse              | 874 us                                                              | 1.05 ms: 1.20x slower                                                 |
| scimark_sor                | 74.4 ms                                                             | 90.7 ms: 1.22x slower                                                 |
| scimark_lu                 | 67.9 ms                                                             | 83.3 ms: 1.23x slower                                                 |
| coroutines                 | 16.4 ms                                                             | 20.6 ms: 1.26x slower                                                 |
| logging_silent             | 64.3 ns                                                             | 83.0 ns: 1.29x slower                                                 |
| generators                 | 29.0 ms                                                             | 38.6 ms: 1.33x slower                                                 |
| dask                       | 219 ms                                                              | 327 ms: 1.49x slower                                                  |
| Geometric mean             | (ref)                                                               | 1.04x slower                                                          |

Benchmark hidden because not significant (6): sqlalchemy_imperative, async_tree_memoization_tg, dulwich_log, nbody, pathlib, tornado_http
Ignored benchmarks (6) of results/bm-20221024-3.11.0-deaf509/bm-20221024-darwin-arm64-python-deaf509e8fc6e0363bd6-3.11.0-deaf509.json: aiohttp, coverage, flaskblogging, gunicorn, mypy2, pylint


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.02x
- 95% likely to have a slowdown of 1.02x
- 99% likely to have a slowdown of 1.01x
