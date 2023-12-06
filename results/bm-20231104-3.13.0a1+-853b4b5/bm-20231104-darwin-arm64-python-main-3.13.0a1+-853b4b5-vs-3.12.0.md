
# Results vs. 3.12.0

- fork: python
- ref: main
- machine: darwin-arm64
- commit hash: 853b4b5
- commit date: 2023-11-04
- overall geometric mean: 1.00x slower \*
- HPT reliability: 76.91%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231104-darwin-arm64-python-main-3.13.0a1+-853b4b5 |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| 2to3           | 171 ms                                                 | 174 ms: 1.02x slower                                   |
| chameleon      | 4.51 ms                                                | 4.68 ms: 1.04x slower                                  |
| docutils       | 1.54 sec                                               | 1.50 sec: 1.03x faster                                 |
| Geometric mean | (ref)                                                  | 1.00x slower                                           |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231104-darwin-arm64-python-main-3.13.0a1+-853b4b5 |
|----------------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| async_tree_none            | 262 ms                                                 | 257 ms: 1.02x faster                                   |
| async_tree_cpu_io_mixed_tg | 535 ms                                                 | 547 ms: 1.02x slower                                   |
| async_tree_io_tg           | 673 ms                                                 | 692 ms: 1.03x slower                                   |
| async_tree_memoization_tg  | 320 ms                                                 | 337 ms: 1.05x slower                                   |
| async_tree_io              | 669 ms                                                 | 710 ms: 1.06x slower                                   |
| async_tree_none_tg         | 254 ms                                                 | 271 ms: 1.06x slower                                   |
| async_tree_memoization     | 309 ms                                                 | 334 ms: 1.08x slower                                   |
| Geometric mean             | (ref)                                                  | 1.04x slower                                           |

Benchmark hidden because not significant (1): async_tree_cpu_io_mixed

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231104-darwin-arm64-python-main-3.13.0a1+-853b4b5 |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| float          | 58.1 ms                                                | 57.7 ms: 1.01x faster                                  |
| pidigits       | 282 ms                                                 | 282 ms: 1.00x slower                                   |
| nbody          | 68.5 ms                                                | 78.5 ms: 1.15x slower                                  |
| Geometric mean | (ref)                                                  | 1.04x slower                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231104-darwin-arm64-python-main-3.13.0a1+-853b4b5 |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| regex_dna      | 153 ms                                                 | 149 ms: 1.03x faster                                   |
| regex_effbot   | 2.59 ms                                                | 2.56 ms: 1.01x faster                                  |
| regex_compile  | 75.6 ms                                                | 76.2 ms: 1.01x slower                                  |
| regex_v8       | 15.7 ms                                                | 16.8 ms: 1.07x slower                                  |
| Geometric mean | (ref)                                                  | 1.01x slower                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231104-darwin-arm64-python-main-3.13.0a1+-853b4b5 |
|----------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| unpickle_list        | 3.24 us                                                | 3.11 us: 1.04x faster                                  |
| unpickle             | 9.25 us                                                | 9.15 us: 1.01x faster                                  |
| json_loads           | 17.6 us                                                | 17.5 us: 1.01x faster                                  |
| pickle_dict          | 18.0 us                                                | 17.9 us: 1.01x faster                                  |
| pickle               | 7.42 us                                                | 7.38 us: 1.00x faster                                  |
| pickle_list          | 2.89 us                                                | 2.92 us: 1.01x slower                                  |
| xml_etree_parse      | 109 ms                                                 | 110 ms: 1.01x slower                                   |
| json_dumps           | 6.46 ms                                                | 6.60 ms: 1.02x slower                                  |
| xml_etree_iterparse  | 74.6 ms                                                | 76.3 ms: 1.02x slower                                  |
| xml_etree_process    | 38.7 ms                                                | 39.8 ms: 1.03x slower                                  |
| xml_etree_generate   | 55.9 ms                                                | 57.8 ms: 1.03x slower                                  |
| pickle_pure_python   | 188 us                                                 | 199 us: 1.06x slower                                   |
| unpickle_pure_python | 145 us                                                 | 156 us: 1.08x slower                                   |
| tomli_loads          | 1.39 sec                                               | 1.56 sec: 1.12x slower                                 |
| Geometric mean       | (ref)                                                  | 1.02x slower                                           |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231104-darwin-arm64-python-main-3.13.0a1+-853b4b5 |
|------------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| python_startup         | 11.9 ms                                                | 13.0 ms: 1.09x slower                                  |
| python_startup_no_site | 9.71 ms                                                | 11.7 ms: 1.21x slower                                  |
| Geometric mean         | (ref)                                                  | 1.15x slower                                           |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231104-darwin-arm64-python-main-3.13.0a1+-853b4b5 |
|-----------|:------------------------------------------------------:|:------------------------------------------------------:|
| mako      | 7.53 ms                                                | 7.50 ms: 1.00x faster                                  |

All benchmarks:
===============

| Benchmark                  | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231104-darwin-arm64-python-main-3.13.0a1+-853b4b5 |
|----------------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| raytrace                   | 246 ms                                                 | 180 ms: 1.36x faster                                   |
| comprehensions             | 15.8 us                                                | 11.8 us: 1.33x faster                                  |
| typing_runtime_protocols   | 90.8 us                                                | 74.2 us: 1.22x faster                                  |
| generators                 | 28.3 ms                                                | 24.4 ms: 1.16x faster                                  |
| crypto_pyaes               | 52.0 ms                                                | 48.0 ms: 1.09x faster                                  |
| sqlglot_parse              | 897 us                                                 | 828 us: 1.08x faster                                   |
| chaos                      | 44.8 ms                                                | 41.5 ms: 1.08x faster                                  |
| unpack_sequence            | 28.4 ns                                                | 26.5 ns: 1.07x faster                                  |
| sympy_sum                  | 79.5 ms                                                | 74.4 ms: 1.07x faster                                  |
| sqlglot_transpile          | 1.08 ms                                                | 1.01 ms: 1.07x faster                                  |
| deltablue                  | 2.58 ms                                                | 2.43 ms: 1.06x faster                                  |
| scimark_monte_carlo        | 50.1 ms                                                | 47.4 ms: 1.06x faster                                  |
| sympy_str                  | 151 ms                                                 | 144 ms: 1.05x faster                                   |
| sympy_integrate            | 11.3 ms                                                | 10.9 ms: 1.04x faster                                  |
| unpickle_list              | 3.24 us                                                | 3.11 us: 1.04x faster                                  |
| deepcopy_reduce            | 2.05 us                                                | 1.97 us: 1.04x faster                                  |
| docutils                   | 1.54 sec                                               | 1.50 sec: 1.03x faster                                 |
| nqueens                    | 60.2 ms                                                | 58.6 ms: 1.03x faster                                  |
| async_generators           | 306 ms                                                 | 298 ms: 1.03x faster                                   |
| regex_dna                  | 153 ms                                                 | 149 ms: 1.03x faster                                   |
| mdp                        | 1.66 sec                                               | 1.62 sec: 1.02x faster                                 |
| spectral_norm              | 74.6 ms                                                | 73.1 ms: 1.02x faster                                  |
| async_tree_none            | 262 ms                                                 | 257 ms: 1.02x faster                                   |
| go                         | 107 ms                                                 | 105 ms: 1.02x faster                                   |
| deepcopy                   | 225 us                                                 | 221 us: 1.02x faster                                   |
| logging_format             | 3.99 us                                                | 3.93 us: 1.02x faster                                  |
| logging_simple             | 3.69 us                                                | 3.64 us: 1.01x faster                                  |
| sqlglot_normalize          | 188 ms                                                 | 186 ms: 1.01x faster                                   |
| scimark_sparse_mat_mult    | 3.14 ms                                                | 3.10 ms: 1.01x faster                                  |
| unpickle                   | 9.25 us                                                | 9.15 us: 1.01x faster                                  |
| regex_effbot               | 2.59 ms                                                | 2.56 ms: 1.01x faster                                  |
| json_loads                 | 17.6 us                                                | 17.5 us: 1.01x faster                                  |
| json                       | 3.02 ms                                                | 3.00 ms: 1.01x faster                                  |
| dulwich_log                | 30.4 ms                                                | 30.2 ms: 1.01x faster                                  |
| sympy_expand               | 249 ms                                                 | 247 ms: 1.01x faster                                   |
| float                      | 58.1 ms                                                | 57.7 ms: 1.01x faster                                  |
| coroutines                 | 18.1 ms                                                | 18.0 ms: 1.01x faster                                  |
| pickle_dict                | 18.0 us                                                | 17.9 us: 1.01x faster                                  |
| pickle                     | 7.42 us                                                | 7.38 us: 1.00x faster                                  |
| create_gc_cycles           | 704 us                                                 | 701 us: 1.00x faster                                   |
| mako                       | 7.53 ms                                                | 7.50 ms: 1.00x faster                                  |
| sqlglot_optimize           | 34.7 ms                                                | 34.6 ms: 1.00x faster                                  |
| pidigits                   | 282 ms                                                 | 282 ms: 1.00x slower                                   |
| regex_compile              | 75.6 ms                                                | 76.2 ms: 1.01x slower                                  |
| pickle_list                | 2.89 us                                                | 2.92 us: 1.01x slower                                  |
| xml_etree_parse            | 109 ms                                                 | 110 ms: 1.01x slower                                   |
| sqlite_synth               | 1.59 us                                                | 1.62 us: 1.02x slower                                  |
| logging_silent             | 68.3 ns                                                | 69.6 ns: 1.02x slower                                  |
| meteor_contest             | 73.3 ms                                                | 74.7 ms: 1.02x slower                                  |
| 2to3                       | 171 ms                                                 | 174 ms: 1.02x slower                                   |
| json_dumps                 | 6.46 ms                                                | 6.60 ms: 1.02x slower                                  |
| async_tree_cpu_io_mixed_tg | 535 ms                                                 | 547 ms: 1.02x slower                                   |
| xml_etree_iterparse        | 74.6 ms                                                | 76.3 ms: 1.02x slower                                  |
| scimark_lu                 | 71.5 ms                                                | 73.3 ms: 1.03x slower                                  |
| async_tree_io_tg           | 673 ms                                                 | 692 ms: 1.03x slower                                   |
| pprint_pformat             | 1.00 sec                                               | 1.03 sec: 1.03x slower                                 |
| xml_etree_process          | 38.7 ms                                                | 39.8 ms: 1.03x slower                                  |
| asyncio_tcp_ssl            | 1.26 sec                                               | 1.29 sec: 1.03x slower                                 |
| xml_etree_generate         | 55.9 ms                                                | 57.8 ms: 1.03x slower                                  |
| scimark_fft                | 198 ms                                                 | 204 ms: 1.03x slower                                   |
| chameleon                  | 4.51 ms                                                | 4.68 ms: 1.04x slower                                  |
| pyflate                    | 329 ms                                                 | 341 ms: 1.04x slower                                   |
| pprint_safe_repr           | 491 ms                                                 | 510 ms: 1.04x slower                                   |
| pycparser                  | 670 ms                                                 | 698 ms: 1.04x slower                                   |
| async_tree_memoization_tg  | 320 ms                                                 | 337 ms: 1.05x slower                                   |
| fannkuch                   | 265 ms                                                 | 279 ms: 1.05x slower                                   |
| pickle_pure_python         | 188 us                                                 | 199 us: 1.06x slower                                   |
| async_tree_io              | 669 ms                                                 | 710 ms: 1.06x slower                                   |
| async_tree_none_tg         | 254 ms                                                 | 271 ms: 1.06x slower                                   |
| regex_v8                   | 15.7 ms                                                | 16.8 ms: 1.07x slower                                  |
| async_tree_memoization     | 309 ms                                                 | 334 ms: 1.08x slower                                   |
| unpickle_pure_python       | 145 us                                                 | 156 us: 1.08x slower                                   |
| python_startup             | 11.9 ms                                                | 13.0 ms: 1.09x slower                                  |
| richards_super             | 34.9 ms                                                | 38.3 ms: 1.10x slower                                  |
| hexiom                     | 4.25 ms                                                | 4.74 ms: 1.11x slower                                  |
| scimark_sor                | 94.3 ms                                                | 105 ms: 1.11x slower                                   |
| richards                   | 31.1 ms                                                | 34.9 ms: 1.12x slower                                  |
| tomli_loads                | 1.39 sec                                               | 1.56 sec: 1.12x slower                                 |
| nbody                      | 68.5 ms                                                | 78.5 ms: 1.15x slower                                  |
| python_startup_no_site     | 9.71 ms                                                | 11.7 ms: 1.21x slower                                  |
| telco                      | 3.79 ms                                                | 4.69 ms: 1.24x slower                                  |
| coverage                   | 37.9 ms                                                | 47.8 ms: 1.26x slower                                  |
| Geometric mean             | (ref)                                                  | 1.00x slower                                           |

Benchmark hidden because not significant (10): asyncio_tcp, tornado_http, bench_mp_pool, gc_traversal, bench_thread_pool, asyncio_websockets, deepcopy_memo, mypy2, pathlib, async_tree_cpu_io_mixed
Ignored benchmarks (6) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, dask, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 76.91% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
