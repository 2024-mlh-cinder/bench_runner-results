
# Results vs. 3.12.0

- fork: mdboom
- ref: pogo2
- machine: darwin-arm64
- commit hash: 69004d6
- commit date: 2023-11-20
- overall geometric mean: 1.09x slower \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.04x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-darwin-arm64-mdboom-pogo2-3.13.0a1+-69004d6 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| 2to3           | 171 ms                                                 | 183 ms: 1.08x slower                                    |
| chameleon      | 4.51 ms                                                | 5.06 ms: 1.12x slower                                   |
| docutils       | 1.54 sec                                               | 1.55 sec: 1.00x slower                                  |
| tornado_http   | 70.7 ms                                                | 74.2 ms: 1.05x slower                                   |
| Geometric mean | (ref)                                                  | 1.06x slower                                            |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-darwin-arm64-mdboom-pogo2-3.13.0a1+-69004d6 |
|----------------------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| async_tree_none            | 262 ms                                                 | 265 ms: 1.01x slower                                    |
| async_tree_cpu_io_mixed    | 525 ms                                                 | 535 ms: 1.02x slower                                    |
| async_tree_cpu_io_mixed_tg | 535 ms                                                 | 553 ms: 1.03x slower                                    |
| async_tree_io_tg           | 673 ms                                                 | 702 ms: 1.04x slower                                    |
| async_tree_io              | 669 ms                                                 | 719 ms: 1.08x slower                                    |
| async_tree_memoization_tg  | 320 ms                                                 | 346 ms: 1.08x slower                                    |
| async_tree_none_tg         | 254 ms                                                 | 278 ms: 1.09x slower                                    |
| async_tree_memoization     | 309 ms                                                 | 342 ms: 1.10x slower                                    |
| Geometric mean             | (ref)                                                  | 1.06x slower                                            |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-darwin-arm64-mdboom-pogo2-3.13.0a1+-69004d6 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| pidigits       | 282 ms                                                 | 283 ms: 1.00x slower                                    |
| float          | 58.1 ms                                                | 72.9 ms: 1.26x slower                                   |
| nbody          | 68.5 ms                                                | 97.7 ms: 1.42x slower                                   |
| Geometric mean | (ref)                                                  | 1.22x slower                                            |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-darwin-arm64-mdboom-pogo2-3.13.0a1+-69004d6 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| regex_dna      | 153 ms                                                 | 149 ms: 1.02x faster                                    |
| regex_effbot   | 2.59 ms                                                | 2.56 ms: 1.01x faster                                   |
| regex_v8       | 15.7 ms                                                | 17.0 ms: 1.09x slower                                   |
| regex_compile  | 75.6 ms                                                | 90.8 ms: 1.20x slower                                   |
| Geometric mean | (ref)                                                  | 1.06x slower                                            |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-darwin-arm64-mdboom-pogo2-3.13.0a1+-69004d6 |
|----------------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| unpickle_list        | 3.24 us                                                | 3.15 us: 1.03x faster                                   |
| json_loads           | 17.6 us                                                | 17.2 us: 1.02x faster                                   |
| unpickle             | 9.25 us                                                | 9.08 us: 1.02x faster                                   |
| xml_etree_parse      | 109 ms                                                 | 107 ms: 1.02x faster                                    |
| pickle               | 7.42 us                                                | 7.34 us: 1.01x faster                                   |
| pickle_dict          | 18.0 us                                                | 17.9 us: 1.00x faster                                   |
| json_dumps           | 6.46 ms                                                | 6.62 ms: 1.02x slower                                   |
| pickle_list          | 2.89 us                                                | 2.98 us: 1.03x slower                                   |
| pickle_pure_python   | 188 us                                                 | 204 us: 1.08x slower                                    |
| xml_etree_process    | 38.7 ms                                                | 42.7 ms: 1.10x slower                                   |
| xml_etree_iterparse  | 74.6 ms                                                | 82.9 ms: 1.11x slower                                   |
| xml_etree_generate   | 55.9 ms                                                | 62.3 ms: 1.11x slower                                   |
| unpickle_pure_python | 145 us                                                 | 175 us: 1.21x slower                                    |
| tomli_loads          | 1.39 sec                                               | 1.81 sec: 1.30x slower                                  |
| Geometric mean       | (ref)                                                  | 1.06x slower                                            |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-darwin-arm64-mdboom-pogo2-3.13.0a1+-69004d6 |
|------------------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| python_startup         | 11.9 ms                                                | 12.2 ms: 1.02x slower                                   |
| python_startup_no_site | 9.71 ms                                                | 10.7 ms: 1.10x slower                                   |
| Geometric mean         | (ref)                                                  | 1.06x slower                                            |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-darwin-arm64-mdboom-pogo2-3.13.0a1+-69004d6 |
|-----------|:------------------------------------------------------:|:-------------------------------------------------------:|
| mako      | 7.53 ms                                                | 10.7 ms: 1.42x slower                                   |

All benchmarks:
===============

| Benchmark                  | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-darwin-arm64-mdboom-pogo2-3.13.0a1+-69004d6 |
|----------------------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| asyncio_websockets         | 545 ms                                                 | 409 ms: 1.33x faster                                    |
| pathlib                    | 29.3 ms                                                | 23.9 ms: 1.23x faster                                   |
| raytrace                   | 246 ms                                                 | 207 ms: 1.19x faster                                    |
| typing_runtime_protocols   | 90.8 us                                                | 80.6 us: 1.13x faster                                   |
| generators                 | 28.3 ms                                                | 25.5 ms: 1.11x faster                                   |
| bench_mp_pool              | 46.3 ms                                                | 44.8 ms: 1.03x faster                                   |
| unpickle_list              | 3.24 us                                                | 3.15 us: 1.03x faster                                   |
| json_loads                 | 17.6 us                                                | 17.2 us: 1.02x faster                                   |
| regex_dna                  | 153 ms                                                 | 149 ms: 1.02x faster                                    |
| unpickle                   | 9.25 us                                                | 9.08 us: 1.02x faster                                   |
| xml_etree_parse            | 109 ms                                                 | 107 ms: 1.02x faster                                    |
| regex_effbot               | 2.59 ms                                                | 2.56 ms: 1.01x faster                                   |
| pickle                     | 7.42 us                                                | 7.34 us: 1.01x faster                                   |
| create_gc_cycles           | 704 us                                                 | 699 us: 1.01x faster                                    |
| sqlglot_parse              | 897 us                                                 | 892 us: 1.01x faster                                    |
| pickle_dict                | 18.0 us                                                | 17.9 us: 1.00x faster                                   |
| gc_traversal               | 2.40 ms                                                | 2.40 ms: 1.00x faster                                   |
| docutils                   | 1.54 sec                                               | 1.55 sec: 1.00x slower                                  |
| dulwich_log                | 30.4 ms                                                | 30.5 ms: 1.00x slower                                   |
| pidigits                   | 282 ms                                                 | 283 ms: 1.00x slower                                    |
| sqlglot_transpile          | 1.08 ms                                                | 1.08 ms: 1.01x slower                                   |
| logging_simple             | 3.69 us                                                | 3.72 us: 1.01x slower                                   |
| logging_format             | 3.99 us                                                | 4.03 us: 1.01x slower                                   |
| async_tree_none            | 262 ms                                                 | 265 ms: 1.01x slower                                    |
| dask                       | 228 ms                                                 | 231 ms: 1.01x slower                                    |
| async_tree_cpu_io_mixed    | 525 ms                                                 | 535 ms: 1.02x slower                                    |
| deepcopy_reduce            | 2.05 us                                                | 2.09 us: 1.02x slower                                   |
| python_startup             | 11.9 ms                                                | 12.2 ms: 1.02x slower                                   |
| json_dumps                 | 6.46 ms                                                | 6.62 ms: 1.02x slower                                   |
| async_generators           | 306 ms                                                 | 314 ms: 1.03x slower                                    |
| pickle_list                | 2.89 us                                                | 2.98 us: 1.03x slower                                   |
| asyncio_tcp_ssl            | 1.26 sec                                               | 1.30 sec: 1.03x slower                                  |
| async_tree_cpu_io_mixed_tg | 535 ms                                                 | 553 ms: 1.03x slower                                    |
| coroutines                 | 18.1 ms                                                | 18.8 ms: 1.04x slower                                   |
| deepcopy                   | 225 us                                                 | 234 us: 1.04x slower                                    |
| mdp                        | 1.66 sec                                               | 1.73 sec: 1.04x slower                                  |
| async_tree_io_tg           | 673 ms                                                 | 702 ms: 1.04x slower                                    |
| tornado_http               | 70.7 ms                                                | 74.2 ms: 1.05x slower                                   |
| sympy_expand               | 249 ms                                                 | 263 ms: 1.06x slower                                    |
| sympy_str                  | 151 ms                                                 | 160 ms: 1.06x slower                                    |
| sympy_sum                  | 79.5 ms                                                | 84.8 ms: 1.07x slower                                   |
| pycparser                  | 670 ms                                                 | 719 ms: 1.07x slower                                    |
| 2to3                       | 171 ms                                                 | 183 ms: 1.08x slower                                    |
| async_tree_io              | 669 ms                                                 | 719 ms: 1.08x slower                                    |
| go                         | 107 ms                                                 | 115 ms: 1.08x slower                                    |
| sqlglot_normalize          | 188 ms                                                 | 203 ms: 1.08x slower                                    |
| sqlite_synth               | 1.59 us                                                | 1.72 us: 1.08x slower                                   |
| sympy_integrate            | 11.3 ms                                                | 12.2 ms: 1.08x slower                                   |
| async_tree_memoization_tg  | 320 ms                                                 | 346 ms: 1.08x slower                                    |
| pickle_pure_python         | 188 us                                                 | 204 us: 1.08x slower                                    |
| regex_v8                   | 15.7 ms                                                | 17.0 ms: 1.09x slower                                   |
| logging_silent             | 68.3 ns                                                | 74.3 ns: 1.09x slower                                   |
| bench_thread_pool          | 492 us                                                 | 535 us: 1.09x slower                                    |
| richards_super             | 34.9 ms                                                | 38.1 ms: 1.09x slower                                   |
| async_tree_none_tg         | 254 ms                                                 | 278 ms: 1.09x slower                                    |
| python_startup_no_site     | 9.71 ms                                                | 10.7 ms: 1.10x slower                                   |
| comprehensions             | 15.8 us                                                | 17.3 us: 1.10x slower                                   |
| deepcopy_memo              | 24.6 us                                                | 27.1 us: 1.10x slower                                   |
| sqlglot_optimize           | 34.7 ms                                                | 38.2 ms: 1.10x slower                                   |
| scimark_lu                 | 71.5 ms                                                | 78.9 ms: 1.10x slower                                   |
| xml_etree_process          | 38.7 ms                                                | 42.7 ms: 1.10x slower                                   |
| richards                   | 31.1 ms                                                | 34.4 ms: 1.10x slower                                   |
| async_tree_memoization     | 309 ms                                                 | 342 ms: 1.10x slower                                    |
| xml_etree_iterparse        | 74.6 ms                                                | 82.9 ms: 1.11x slower                                   |
| xml_etree_generate         | 55.9 ms                                                | 62.3 ms: 1.11x slower                                   |
| crypto_pyaes               | 52.0 ms                                                | 58.2 ms: 1.12x slower                                   |
| chameleon                  | 4.51 ms                                                | 5.06 ms: 1.12x slower                                   |
| meteor_contest             | 73.3 ms                                                | 83.3 ms: 1.14x slower                                   |
| chaos                      | 44.8 ms                                                | 51.9 ms: 1.16x slower                                   |
| scimark_sor                | 94.3 ms                                                | 110 ms: 1.16x slower                                    |
| pyflate                    | 329 ms                                                 | 389 ms: 1.18x slower                                    |
| regex_compile              | 75.6 ms                                                | 90.8 ms: 1.20x slower                                   |
| unpickle_pure_python       | 145 us                                                 | 175 us: 1.21x slower                                    |
| nqueens                    | 60.2 ms                                                | 73.2 ms: 1.21x slower                                   |
| pprint_safe_repr           | 491 ms                                                 | 601 ms: 1.22x slower                                    |
| pprint_pformat             | 1.00 sec                                               | 1.24 sec: 1.24x slower                                  |
| scimark_monte_carlo        | 50.1 ms                                                | 61.9 ms: 1.24x slower                                   |
| coverage                   | 37.9 ms                                                | 47.6 ms: 1.26x slower                                   |
| float                      | 58.1 ms                                                | 72.9 ms: 1.26x slower                                   |
| telco                      | 3.79 ms                                                | 4.89 ms: 1.29x slower                                   |
| tomli_loads                | 1.39 sec                                               | 1.81 sec: 1.30x slower                                  |
| fannkuch                   | 265 ms                                                 | 363 ms: 1.37x slower                                    |
| scimark_sparse_mat_mult    | 3.14 ms                                                | 4.39 ms: 1.40x slower                                   |
| scimark_fft                | 198 ms                                                 | 279 ms: 1.41x slower                                    |
| mako                       | 7.53 ms                                                | 10.7 ms: 1.42x slower                                   |
| nbody                      | 68.5 ms                                                | 97.7 ms: 1.42x slower                                   |
| deltablue                  | 2.58 ms                                                | 3.84 ms: 1.49x slower                                   |
| spectral_norm              | 74.6 ms                                                | 115 ms: 1.55x slower                                    |
| hexiom                     | 4.25 ms                                                | 6.61 ms: 1.55x slower                                   |
| Geometric mean             | (ref)                                                  | 1.09x slower                                            |

Benchmark hidden because not significant (4): unpack_sequence, asyncio_tcp, json, mypy2
Ignored benchmarks (5) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.05x
- 95% likely to have a slowdown of 1.05x
- 99% likely to have a slowdown of 1.04x
