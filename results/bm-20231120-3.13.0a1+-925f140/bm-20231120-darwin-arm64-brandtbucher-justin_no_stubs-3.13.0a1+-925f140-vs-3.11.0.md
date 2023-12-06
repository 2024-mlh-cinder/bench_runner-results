
# Results vs. 3.11.0

- fork: brandtbucher
- ref: justin_no_stubs
- machine: darwin-arm64
- commit hash: 925f140
- commit date: 2023-11-20
- overall geometric mean: 1.04x slower \*
- HPT reliability: 99.96%
- HPT 99th percentile: 1.01x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-darwin-arm64-brandtbucher-justin_no_stubs-3.13.0a1+-925f140 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| 2to3           | 155 ms                                                 | 181 ms: 1.16x slower                                                    |
| chameleon      | 4.17 ms                                                | 4.86 ms: 1.16x slower                                                   |
| docutils       | 1.46 sec                                               | 1.53 sec: 1.05x slower                                                  |
| Geometric mean | (ref)                                                  | 1.10x slower                                                            |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-darwin-arm64-brandtbucher-justin_no_stubs-3.13.0a1+-925f140 |
|----------------------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| async_tree_none            | 282 ms                                                 | 256 ms: 1.10x faster                                                    |
| async_tree_memoization     | 361 ms                                                 | 332 ms: 1.09x faster                                                    |
| async_tree_io_tg           | 734 ms                                                 | 687 ms: 1.07x faster                                                    |
| async_tree_memoization_tg  | 357 ms                                                 | 335 ms: 1.07x faster                                                    |
| async_tree_none_tg         | 280 ms                                                 | 269 ms: 1.04x faster                                                    |
| async_tree_cpu_io_mixed_tg | 554 ms                                                 | 544 ms: 1.02x faster                                                    |
| async_tree_cpu_io_mixed    | 522 ms                                                 | 527 ms: 1.01x slower                                                    |
| Geometric mean             | (ref)                                                  | 1.05x faster                                                            |

Benchmark hidden because not significant (1): async_tree_io

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-darwin-arm64-brandtbucher-justin_no_stubs-3.13.0a1+-925f140 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| float          | 55.4 ms                                                | 58.6 ms: 1.06x slower                                                   |
| nbody          | 68.7 ms                                                | 81.5 ms: 1.19x slower                                                   |
| Geometric mean | (ref)                                                  | 1.08x slower                                                            |

Benchmark hidden because not significant (1): pidigits

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-darwin-arm64-brandtbucher-justin_no_stubs-3.13.0a1+-925f140 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| regex_dna      | 149 ms                                                 | 148 ms: 1.00x faster                                                    |
| regex_effbot   | 2.46 ms                                                | 2.57 ms: 1.05x slower                                                   |
| regex_v8       | 15.3 ms                                                | 17.1 ms: 1.11x slower                                                   |
| regex_compile  | 73.9 ms                                                | 83.3 ms: 1.13x slower                                                   |
| Geometric mean | (ref)                                                  | 1.07x slower                                                            |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-darwin-arm64-brandtbucher-justin_no_stubs-3.13.0a1+-925f140 |
|----------------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| json_dumps           | 7.58 ms                                                | 6.56 ms: 1.15x faster                                                   |
| pickle_pure_python   | 211 us                                                 | 206 us: 1.02x faster                                                    |
| xml_etree_parse      | 107 ms                                                 | 108 ms: 1.01x slower                                                    |
| unpickle_pure_python | 163 us                                                 | 167 us: 1.02x slower                                                    |
| pickle               | 7.22 us                                                | 7.42 us: 1.03x slower                                                   |
| pickle_dict          | 17.0 us                                                | 17.9 us: 1.05x slower                                                   |
| unpickle             | 8.32 us                                                | 9.11 us: 1.10x slower                                                   |
| pickle_list          | 2.67 us                                                | 2.93 us: 1.10x slower                                                   |
| json_loads           | 15.8 us                                                | 17.4 us: 1.10x slower                                                   |
| unpickle_list        | 2.77 us                                                | 3.11 us: 1.12x slower                                                   |
| xml_etree_iterparse  | 68.2 ms                                                | 76.8 ms: 1.13x slower                                                   |
| tomli_loads          | 1.30 sec                                               | 1.52 sec: 1.17x slower                                                  |
| xml_etree_process    | 34.0 ms                                                | 40.7 ms: 1.20x slower                                                   |
| xml_etree_generate   | 46.8 ms                                                | 58.8 ms: 1.25x slower                                                   |
| Geometric mean       | (ref)                                                  | 1.08x slower                                                            |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-darwin-arm64-brandtbucher-justin_no_stubs-3.13.0a1+-925f140 |
|------------------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| python_startup         | 11.4 ms                                                | 12.7 ms: 1.12x slower                                                   |
| python_startup_no_site | 9.15 ms                                                | 11.1 ms: 1.22x slower                                                   |
| Geometric mean         | (ref)                                                  | 1.17x slower                                                            |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-darwin-arm64-brandtbucher-justin_no_stubs-3.13.0a1+-925f140 |
|-----------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| mako      | 8.22 ms                                                | 7.92 ms: 1.04x faster                                                   |

All benchmarks:
===============

| Benchmark                  | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-darwin-arm64-brandtbucher-justin_no_stubs-3.13.0a1+-925f140 |
|----------------------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| typing_runtime_protocols   | 323 us                                                 | 77.7 us: 4.15x faster                                                   |
| asyncio_tcp                | 650 ms                                                 | 393 ms: 1.65x faster                                                    |
| asyncio_websockets         | 544 ms                                                 | 408 ms: 1.33x faster                                                    |
| pathlib                    | 28.5 ms                                                | 24.3 ms: 1.17x faster                                                   |
| json_dumps                 | 7.58 ms                                                | 6.56 ms: 1.15x faster                                                   |
| generators                 | 29.2 ms                                                | 25.6 ms: 1.14x faster                                                   |
| unpack_sequence            | 32.3 ns                                                | 28.7 ns: 1.12x faster                                                   |
| deepcopy_memo              | 28.9 us                                                | 26.0 us: 1.11x faster                                                   |
| asyncio_tcp_ssl            | 1.44 sec                                               | 1.30 sec: 1.11x faster                                                  |
| async_tree_none            | 282 ms                                                 | 256 ms: 1.10x faster                                                    |
| async_tree_memoization     | 361 ms                                                 | 332 ms: 1.09x faster                                                    |
| chaos                      | 48.2 ms                                                | 44.8 ms: 1.08x faster                                                   |
| async_tree_io_tg           | 734 ms                                                 | 687 ms: 1.07x faster                                                    |
| async_tree_memoization_tg  | 357 ms                                                 | 335 ms: 1.07x faster                                                    |
| comprehensions             | 14.7 us                                                | 13.8 us: 1.06x faster                                                   |
| deltablue                  | 2.70 ms                                                | 2.57 ms: 1.05x faster                                                   |
| async_tree_none_tg         | 280 ms                                                 | 269 ms: 1.04x faster                                                    |
| mako                       | 8.22 ms                                                | 7.92 ms: 1.04x faster                                                   |
| raytrace                   | 200 ms                                                 | 193 ms: 1.04x faster                                                    |
| mdp                        | 1.73 sec                                               | 1.69 sec: 1.03x faster                                                  |
| pickle_pure_python         | 211 us                                                 | 206 us: 1.02x faster                                                    |
| create_gc_cycles           | 715 us                                                 | 700 us: 1.02x faster                                                    |
| sqlglot_parse              | 886 us                                                 | 868 us: 1.02x faster                                                    |
| async_tree_cpu_io_mixed_tg | 554 ms                                                 | 544 ms: 1.02x faster                                                    |
| deepcopy                   | 233 us                                                 | 230 us: 1.01x faster                                                    |
| sympy_sum                  | 81.6 ms                                                | 80.6 ms: 1.01x faster                                                   |
| regex_dna                  | 149 ms                                                 | 148 ms: 1.00x faster                                                    |
| gc_traversal               | 2.39 ms                                                | 2.39 ms: 1.00x slower                                                   |
| sqlglot_transpile          | 1.05 ms                                                | 1.05 ms: 1.01x slower                                                   |
| xml_etree_parse            | 107 ms                                                 | 108 ms: 1.01x slower                                                    |
| async_tree_cpu_io_mixed    | 522 ms                                                 | 527 ms: 1.01x slower                                                    |
| dulwich_log                | 29.9 ms                                                | 30.2 ms: 1.01x slower                                                   |
| unpickle_pure_python       | 163 us                                                 | 167 us: 1.02x slower                                                    |
| dask                       | 224 ms                                                 | 230 ms: 1.03x slower                                                    |
| pickle                     | 7.22 us                                                | 7.42 us: 1.03x slower                                                   |
| deepcopy_reduce            | 1.98 us                                                | 2.04 us: 1.03x slower                                                   |
| crypto_pyaes               | 48.1 ms                                                | 50.3 ms: 1.04x slower                                                   |
| regex_effbot               | 2.46 ms                                                | 2.57 ms: 1.05x slower                                                   |
| pickle_dict                | 17.0 us                                                | 17.9 us: 1.05x slower                                                   |
| docutils                   | 1.46 sec                                               | 1.53 sec: 1.05x slower                                                  |
| meteor_contest             | 74.9 ms                                                | 78.9 ms: 1.05x slower                                                   |
| sympy_integrate            | 11.3 ms                                                | 12.0 ms: 1.06x slower                                                   |
| float                      | 55.4 ms                                                | 58.6 ms: 1.06x slower                                                   |
| sympy_str                  | 144 ms                                                 | 153 ms: 1.06x slower                                                    |
| logging_simple             | 3.41 us                                                | 3.62 us: 1.06x slower                                                   |
| logging_format             | 3.69 us                                                | 3.92 us: 1.06x slower                                                   |
| scimark_monte_carlo        | 47.1 ms                                                | 50.1 ms: 1.06x slower                                                   |
| pycparser                  | 667 ms                                                 | 713 ms: 1.07x slower                                                    |
| richards                   | 30.8 ms                                                | 33.3 ms: 1.08x slower                                                   |
| json                       | 2.77 ms                                                | 3.03 ms: 1.09x slower                                                   |
| unpickle                   | 8.32 us                                                | 9.11 us: 1.10x slower                                                   |
| scimark_sparse_mat_mult    | 3.01 ms                                                | 3.30 ms: 1.10x slower                                                   |
| pickle_list                | 2.67 us                                                | 2.93 us: 1.10x slower                                                   |
| pprint_pformat             | 989 ms                                                 | 1.09 sec: 1.10x slower                                                  |
| json_loads                 | 15.8 us                                                | 17.4 us: 1.10x slower                                                   |
| sympy_expand               | 234 ms                                                 | 258 ms: 1.10x slower                                                    |
| pprint_safe_repr           | 479 ms                                                 | 532 ms: 1.11x slower                                                    |
| regex_v8                   | 15.3 ms                                                | 17.1 ms: 1.11x slower                                                   |
| python_startup             | 11.4 ms                                                | 12.7 ms: 1.12x slower                                                   |
| go                         | 102 ms                                                 | 114 ms: 1.12x slower                                                    |
| unpickle_list              | 2.77 us                                                | 3.11 us: 1.12x slower                                                   |
| coroutines                 | 16.6 ms                                                | 18.6 ms: 1.12x slower                                                   |
| regex_compile              | 73.9 ms                                                | 83.3 ms: 1.13x slower                                                   |
| xml_etree_iterparse        | 68.2 ms                                                | 76.8 ms: 1.13x slower                                                   |
| bench_mp_pool              | 41.9 ms                                                | 47.3 ms: 1.13x slower                                                   |
| logging_silent             | 64.5 ns                                                | 73.4 ns: 1.14x slower                                                   |
| bench_thread_pool          | 461 us                                                 | 529 us: 1.15x slower                                                    |
| scimark_lu                 | 67.8 ms                                                | 78.0 ms: 1.15x slower                                                   |
| chameleon                  | 4.17 ms                                                | 4.86 ms: 1.16x slower                                                   |
| 2to3                       | 155 ms                                                 | 181 ms: 1.16x slower                                                    |
| tomli_loads                | 1.30 sec                                               | 1.52 sec: 1.17x slower                                                  |
| pyflate                    | 297 ms                                                 | 349 ms: 1.18x slower                                                    |
| spectral_norm              | 69.7 ms                                                | 82.0 ms: 1.18x slower                                                   |
| nbody                      | 68.7 ms                                                | 81.5 ms: 1.19x slower                                                   |
| scimark_fft                | 187 ms                                                 | 223 ms: 1.19x slower                                                    |
| xml_etree_process          | 34.0 ms                                                | 40.7 ms: 1.20x slower                                                   |
| nqueens                    | 54.6 ms                                                | 65.4 ms: 1.20x slower                                                   |
| coverage                   | 41.4 ms                                                | 49.7 ms: 1.20x slower                                                   |
| fannkuch                   | 247 ms                                                 | 299 ms: 1.21x slower                                                    |
| python_startup_no_site     | 9.15 ms                                                | 11.1 ms: 1.22x slower                                                   |
| sqlglot_normalize          | 160 ms                                                 | 196 ms: 1.22x slower                                                    |
| sqlite_synth               | 1.35 us                                                | 1.66 us: 1.23x slower                                                   |
| sqlglot_optimize           | 29.6 ms                                                | 36.9 ms: 1.25x slower                                                   |
| xml_etree_generate         | 46.8 ms                                                | 58.8 ms: 1.25x slower                                                   |
| hexiom                     | 4.55 ms                                                | 5.78 ms: 1.27x slower                                                   |
| mypy2                      | 191 ms                                                 | 267 ms: 1.40x slower                                                    |
| scimark_sor                | 75.2 ms                                                | 108 ms: 1.44x slower                                                    |
| telco                      | 3.17 ms                                                | 4.75 ms: 1.50x slower                                                   |
| async_generators           | 192 ms                                                 | 316 ms: 1.64x slower                                                    |
| Geometric mean             | (ref)                                                  | 1.04x slower                                                            |

Benchmark hidden because not significant (4): richards_super, pidigits, async_tree_io, tornado_http
Ignored benchmarks (11) of results/bm-20221024-3.11.0-deaf509/bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift


# HPT report

- Reliability score: 99.96% likely to be slow
- 90% likely to have a slowdown of 1.03x
- 95% likely to have a slowdown of 1.02x
- 99% likely to have a slowdown of 1.01x
