
# Results vs. 3.12.0

- fork: mdboom
- ref: alternative_workarou
- machine: darwin-arm64
- commit hash: d452c37
- commit date: 2023-11-20
- overall geometric mean: 1.01x slower \*
- HPT reliability: 98.71%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-darwin-arm64-mdboom-alternative_workarou-3.13.0a1+-d452c37 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| 2to3           | 171 ms                                                 | 174 ms: 1.02x slower                                                   |
| chameleon      | 4.51 ms                                                | 4.86 ms: 1.08x slower                                                  |
| docutils       | 1.54 sec                                               | 1.51 sec: 1.02x faster                                                 |
| Geometric mean | (ref)                                                  | 1.02x slower                                                           |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-darwin-arm64-mdboom-alternative_workarou-3.13.0a1+-d452c37 |
|----------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| async_tree_none            | 262 ms                                                 | 254 ms: 1.03x faster                                                   |
| async_tree_cpu_io_mixed_tg | 535 ms                                                 | 543 ms: 1.02x slower                                                   |
| async_tree_io_tg           | 673 ms                                                 | 686 ms: 1.02x slower                                                   |
| async_tree_memoization_tg  | 320 ms                                                 | 334 ms: 1.04x slower                                                   |
| async_tree_io              | 669 ms                                                 | 703 ms: 1.05x slower                                                   |
| async_tree_none_tg         | 254 ms                                                 | 268 ms: 1.05x slower                                                   |
| async_tree_memoization     | 309 ms                                                 | 331 ms: 1.07x slower                                                   |
| Geometric mean             | (ref)                                                  | 1.03x slower                                                           |

Benchmark hidden because not significant (1): async_tree_cpu_io_mixed

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-darwin-arm64-mdboom-alternative_workarou-3.13.0a1+-d452c37 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| pidigits       | 282 ms                                                 | 282 ms: 1.00x faster                                                   |
| float          | 58.1 ms                                                | 58.4 ms: 1.01x slower                                                  |
| nbody          | 68.5 ms                                                | 79.2 ms: 1.16x slower                                                  |
| Geometric mean | (ref)                                                  | 1.05x slower                                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-darwin-arm64-mdboom-alternative_workarou-3.13.0a1+-d452c37 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| regex_dna      | 153 ms                                                 | 149 ms: 1.03x faster                                                   |
| regex_effbot   | 2.59 ms                                                | 2.58 ms: 1.00x faster                                                  |
| regex_compile  | 75.6 ms                                                | 78.9 ms: 1.04x slower                                                  |
| regex_v8       | 15.7 ms                                                | 16.9 ms: 1.08x slower                                                  |
| Geometric mean | (ref)                                                  | 1.02x slower                                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-darwin-arm64-mdboom-alternative_workarou-3.13.0a1+-d452c37 |
|----------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| unpickle_list        | 3.24 us                                                | 3.14 us: 1.03x faster                                                  |
| json_loads           | 17.6 us                                                | 17.4 us: 1.01x faster                                                  |
| xml_etree_parse      | 109 ms                                                 | 108 ms: 1.01x faster                                                   |
| unpickle             | 9.25 us                                                | 9.15 us: 1.01x faster                                                  |
| pickle_dict          | 18.0 us                                                | 17.9 us: 1.01x faster                                                  |
| pickle               | 7.42 us                                                | 7.37 us: 1.01x faster                                                  |
| pickle_list          | 2.89 us                                                | 2.94 us: 1.01x slower                                                  |
| json_dumps           | 6.46 ms                                                | 6.59 ms: 1.02x slower                                                  |
| xml_etree_iterparse  | 74.6 ms                                                | 76.8 ms: 1.03x slower                                                  |
| xml_etree_generate   | 55.9 ms                                                | 58.2 ms: 1.04x slower                                                  |
| xml_etree_process    | 38.7 ms                                                | 40.4 ms: 1.05x slower                                                  |
| pickle_pure_python   | 188 us                                                 | 205 us: 1.09x slower                                                   |
| unpickle_pure_python | 145 us                                                 | 161 us: 1.11x slower                                                   |
| tomli_loads          | 1.39 sec                                               | 1.58 sec: 1.14x slower                                                 |
| Geometric mean       | (ref)                                                  | 1.03x slower                                                           |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-darwin-arm64-mdboom-alternative_workarou-3.13.0a1+-d452c37 |
|------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| python_startup         | 11.9 ms                                                | 12.3 ms: 1.03x slower                                                  |
| python_startup_no_site | 9.71 ms                                                | 10.8 ms: 1.12x slower                                                  |
| Geometric mean         | (ref)                                                  | 1.07x slower                                                           |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-darwin-arm64-mdboom-alternative_workarou-3.13.0a1+-d452c37 |
|-----------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| mako      | 7.53 ms                                                | 7.79 ms: 1.04x slower                                                  |

All benchmarks:
===============

| Benchmark                  | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-darwin-arm64-mdboom-alternative_workarou-3.13.0a1+-d452c37 |
|----------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| asyncio_websockets         | 545 ms                                                 | 409 ms: 1.33x faster                                                   |
| raytrace                   | 246 ms                                                 | 189 ms: 1.30x faster                                                   |
| comprehensions             | 15.8 us                                                | 12.6 us: 1.25x faster                                                  |
| pathlib                    | 29.3 ms                                                | 24.3 ms: 1.21x faster                                                  |
| typing_runtime_protocols   | 90.8 us                                                | 75.9 us: 1.20x faster                                                  |
| generators                 | 28.3 ms                                                | 25.6 ms: 1.11x faster                                                  |
| sqlglot_parse              | 897 us                                                 | 851 us: 1.05x faster                                                   |
| crypto_pyaes               | 52.0 ms                                                | 49.4 ms: 1.05x faster                                                  |
| sympy_sum                  | 79.5 ms                                                | 75.6 ms: 1.05x faster                                                  |
| sqlglot_transpile          | 1.08 ms                                                | 1.03 ms: 1.04x faster                                                  |
| bench_mp_pool              | 46.3 ms                                                | 44.5 ms: 1.04x faster                                                  |
| deltablue                  | 2.58 ms                                                | 2.49 ms: 1.04x faster                                                  |
| scimark_monte_carlo        | 50.1 ms                                                | 48.5 ms: 1.03x faster                                                  |
| unpickle_list              | 3.24 us                                                | 3.14 us: 1.03x faster                                                  |
| async_tree_none            | 262 ms                                                 | 254 ms: 1.03x faster                                                   |
| chaos                      | 44.8 ms                                                | 43.5 ms: 1.03x faster                                                  |
| sympy_str                  | 151 ms                                                 | 147 ms: 1.03x faster                                                   |
| regex_dna                  | 153 ms                                                 | 149 ms: 1.03x faster                                                   |
| docutils                   | 1.54 sec                                               | 1.51 sec: 1.02x faster                                                 |
| unpack_sequence            | 28.4 ns                                                | 27.9 ns: 1.02x faster                                                  |
| logging_simple             | 3.69 us                                                | 3.64 us: 1.02x faster                                                  |
| logging_format             | 3.99 us                                                | 3.93 us: 1.02x faster                                                  |
| json_loads                 | 17.6 us                                                | 17.4 us: 1.01x faster                                                  |
| dulwich_log                | 30.4 ms                                                | 30.0 ms: 1.01x faster                                                  |
| sympy_integrate            | 11.3 ms                                                | 11.2 ms: 1.01x faster                                                  |
| xml_etree_parse            | 109 ms                                                 | 108 ms: 1.01x faster                                                   |
| unpickle                   | 9.25 us                                                | 9.15 us: 1.01x faster                                                  |
| mdp                        | 1.66 sec                                               | 1.65 sec: 1.01x faster                                                 |
| pickle_dict                | 18.0 us                                                | 17.9 us: 1.01x faster                                                  |
| create_gc_cycles           | 704 us                                                 | 700 us: 1.01x faster                                                   |
| pickle                     | 7.42 us                                                | 7.37 us: 1.01x faster                                                  |
| gc_traversal               | 2.40 ms                                                | 2.39 ms: 1.01x faster                                                  |
| go                         | 107 ms                                                 | 107 ms: 1.00x faster                                                   |
| regex_effbot               | 2.59 ms                                                | 2.58 ms: 1.00x faster                                                  |
| pidigits                   | 282 ms                                                 | 282 ms: 1.00x faster                                                   |
| float                      | 58.1 ms                                                | 58.4 ms: 1.01x slower                                                  |
| scimark_sparse_mat_mult    | 3.14 ms                                                | 3.16 ms: 1.01x slower                                                  |
| nqueens                    | 60.2 ms                                                | 60.7 ms: 1.01x slower                                                  |
| spectral_norm              | 74.6 ms                                                | 75.3 ms: 1.01x slower                                                  |
| deepcopy_reduce            | 2.05 us                                                | 2.08 us: 1.01x slower                                                  |
| pickle_list                | 2.89 us                                                | 2.94 us: 1.01x slower                                                  |
| async_tree_cpu_io_mixed_tg | 535 ms                                                 | 543 ms: 1.02x slower                                                   |
| sqlglot_normalize          | 188 ms                                                 | 191 ms: 1.02x slower                                                   |
| sympy_expand               | 249 ms                                                 | 254 ms: 1.02x slower                                                   |
| async_tree_io_tg           | 673 ms                                                 | 686 ms: 1.02x slower                                                   |
| json_dumps                 | 6.46 ms                                                | 6.59 ms: 1.02x slower                                                  |
| 2to3                       | 171 ms                                                 | 174 ms: 1.02x slower                                                   |
| sqlglot_optimize           | 34.7 ms                                                | 35.5 ms: 1.03x slower                                                  |
| meteor_contest             | 73.3 ms                                                | 75.4 ms: 1.03x slower                                                  |
| python_startup             | 11.9 ms                                                | 12.3 ms: 1.03x slower                                                  |
| deepcopy                   | 225 us                                                 | 232 us: 1.03x slower                                                   |
| xml_etree_iterparse        | 74.6 ms                                                | 76.8 ms: 1.03x slower                                                  |
| deepcopy_memo              | 24.6 us                                                | 25.3 us: 1.03x slower                                                  |
| asyncio_tcp_ssl            | 1.26 sec                                               | 1.29 sec: 1.03x slower                                                 |
| coroutines                 | 18.1 ms                                                | 18.8 ms: 1.03x slower                                                  |
| mako                       | 7.53 ms                                                | 7.79 ms: 1.04x slower                                                  |
| xml_etree_generate         | 55.9 ms                                                | 58.2 ms: 1.04x slower                                                  |
| async_tree_memoization_tg  | 320 ms                                                 | 334 ms: 1.04x slower                                                   |
| regex_compile              | 75.6 ms                                                | 78.9 ms: 1.04x slower                                                  |
| xml_etree_process          | 38.7 ms                                                | 40.4 ms: 1.05x slower                                                  |
| scimark_lu                 | 71.5 ms                                                | 74.8 ms: 1.05x slower                                                  |
| bench_thread_pool          | 492 us                                                 | 516 us: 1.05x slower                                                   |
| async_tree_io              | 669 ms                                                 | 703 ms: 1.05x slower                                                   |
| pyflate                    | 329 ms                                                 | 346 ms: 1.05x slower                                                   |
| sqlite_synth               | 1.59 us                                                | 1.67 us: 1.05x slower                                                  |
| async_tree_none_tg         | 254 ms                                                 | 268 ms: 1.05x slower                                                   |
| pycparser                  | 670 ms                                                 | 710 ms: 1.06x slower                                                   |
| scimark_fft                | 198 ms                                                 | 210 ms: 1.06x slower                                                   |
| pprint_pformat             | 1.00 sec                                               | 1.07 sec: 1.07x slower                                                 |
| pprint_safe_repr           | 491 ms                                                 | 525 ms: 1.07x slower                                                   |
| async_tree_memoization     | 309 ms                                                 | 331 ms: 1.07x slower                                                   |
| logging_silent             | 68.3 ns                                                | 73.2 ns: 1.07x slower                                                  |
| chameleon                  | 4.51 ms                                                | 4.86 ms: 1.08x slower                                                  |
| regex_v8                   | 15.7 ms                                                | 16.9 ms: 1.08x slower                                                  |
| pickle_pure_python         | 188 us                                                 | 205 us: 1.09x slower                                                   |
| fannkuch                   | 265 ms                                                 | 288 ms: 1.09x slower                                                   |
| richards_super             | 34.9 ms                                                | 38.4 ms: 1.10x slower                                                  |
| unpickle_pure_python       | 145 us                                                 | 161 us: 1.11x slower                                                   |
| python_startup_no_site     | 9.71 ms                                                | 10.8 ms: 1.12x slower                                                  |
| richards                   | 31.1 ms                                                | 34.8 ms: 1.12x slower                                                  |
| scimark_sor                | 94.3 ms                                                | 107 ms: 1.13x slower                                                   |
| tomli_loads                | 1.39 sec                                               | 1.58 sec: 1.14x slower                                                 |
| nbody                      | 68.5 ms                                                | 79.2 ms: 1.16x slower                                                  |
| hexiom                     | 4.25 ms                                                | 4.97 ms: 1.17x slower                                                  |
| coverage                   | 37.9 ms                                                | 47.5 ms: 1.25x slower                                                  |
| telco                      | 3.79 ms                                                | 4.76 ms: 1.26x slower                                                  |
| Geometric mean             | (ref)                                                  | 1.01x slower                                                           |

Benchmark hidden because not significant (7): asyncio_tcp, mypy2, json, async_generators, dask, async_tree_cpu_io_mixed, tornado_http
Ignored benchmarks (5) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 98.71% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
