
# Results vs. 3.12.0

- fork: python
- ref: fa84e5fe0a3bd8e77c33
- machine: darwin-arm64
- commit hash: fa84e5f
- commit date: 2023-11-11
- overall geometric mean: 1.00x faster \*
- HPT reliability: 71.52%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231111-darwin-arm64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| 2to3           | 171 ms                                                 | 171 ms: 1.00x slower                                                   |
| chameleon      | 4.51 ms                                                | 4.66 ms: 1.03x slower                                                  |
| docutils       | 1.54 sec                                               | 1.48 sec: 1.04x faster                                                 |
| Geometric mean | (ref)                                                  | 1.00x faster                                                           |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231111-darwin-arm64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f |
|----------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| async_tree_none            | 262 ms                                                 | 253 ms: 1.04x faster                                                   |
| async_tree_io_tg           | 673 ms                                                 | 686 ms: 1.02x slower                                                   |
| async_tree_cpu_io_mixed_tg | 535 ms                                                 | 545 ms: 1.02x slower                                                   |
| async_tree_memoization_tg  | 320 ms                                                 | 333 ms: 1.04x slower                                                   |
| async_tree_io              | 669 ms                                                 | 702 ms: 1.05x slower                                                   |
| async_tree_none_tg         | 254 ms                                                 | 267 ms: 1.05x slower                                                   |
| async_tree_memoization     | 309 ms                                                 | 330 ms: 1.07x slower                                                   |
| Geometric mean             | (ref)                                                  | 1.03x slower                                                           |

Benchmark hidden because not significant (1): async_tree_cpu_io_mixed

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231111-darwin-arm64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| float          | 58.1 ms                                                | 57.0 ms: 1.02x faster                                                  |
| pidigits       | 282 ms                                                 | 282 ms: 1.00x slower                                                   |
| nbody          | 68.5 ms                                                | 77.4 ms: 1.13x slower                                                  |
| Geometric mean | (ref)                                                  | 1.04x slower                                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231111-darwin-arm64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| regex_dna      | 153 ms                                                 | 149 ms: 1.03x faster                                                   |
| regex_effbot   | 2.59 ms                                                | 2.56 ms: 1.01x faster                                                  |
| regex_compile  | 75.6 ms                                                | 76.3 ms: 1.01x slower                                                  |
| regex_v8       | 15.7 ms                                                | 16.9 ms: 1.08x slower                                                  |
| Geometric mean | (ref)                                                  | 1.01x slower                                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231111-darwin-arm64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f |
|----------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| unpickle_list        | 3.24 us                                                | 3.13 us: 1.03x faster                                                  |
| unpickle             | 9.25 us                                                | 9.14 us: 1.01x faster                                                  |
| pickle               | 7.42 us                                                | 7.37 us: 1.01x faster                                                  |
| pickle_dict          | 18.0 us                                                | 17.9 us: 1.01x faster                                                  |
| json_dumps           | 6.46 ms                                                | 6.45 ms: 1.00x faster                                                  |
| xml_etree_parse      | 109 ms                                                 | 110 ms: 1.01x slower                                                   |
| xml_etree_iterparse  | 74.6 ms                                                | 75.9 ms: 1.02x slower                                                  |
| xml_etree_process    | 38.7 ms                                                | 39.7 ms: 1.03x slower                                                  |
| xml_etree_generate   | 55.9 ms                                                | 57.7 ms: 1.03x slower                                                  |
| pickle_pure_python   | 188 us                                                 | 197 us: 1.04x slower                                                   |
| unpickle_pure_python | 145 us                                                 | 156 us: 1.08x slower                                                   |
| tomli_loads          | 1.39 sec                                               | 1.56 sec: 1.12x slower                                                 |
| Geometric mean       | (ref)                                                  | 1.02x slower                                                           |

Benchmark hidden because not significant (2): pickle_list, json_loads

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231111-darwin-arm64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f |
|------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| python_startup         | 11.9 ms                                                | 11.8 ms: 1.01x faster                                                  |
| python_startup_no_site | 9.71 ms                                                | 10.5 ms: 1.08x slower                                                  |
| Geometric mean         | (ref)                                                  | 1.04x slower                                                           |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231111-darwin-arm64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f |
|-----------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| mako      | 7.53 ms                                                | 7.49 ms: 1.00x faster                                                  |

All benchmarks:
===============

| Benchmark                  | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231111-darwin-arm64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f |
|----------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| raytrace                   | 246 ms                                                 | 180 ms: 1.37x faster                                                   |
| comprehensions             | 15.8 us                                                | 11.7 us: 1.35x faster                                                  |
| typing_runtime_protocols   | 90.8 us                                                | 75.2 us: 1.21x faster                                                  |
| generators                 | 28.3 ms                                                | 24.8 ms: 1.14x faster                                                  |
| crypto_pyaes               | 52.0 ms                                                | 47.8 ms: 1.09x faster                                                  |
| sqlglot_parse              | 897 us                                                 | 827 us: 1.08x faster                                                   |
| chaos                      | 44.8 ms                                                | 41.5 ms: 1.08x faster                                                  |
| sympy_sum                  | 79.5 ms                                                | 73.8 ms: 1.08x faster                                                  |
| unpack_sequence            | 28.4 ns                                                | 26.5 ns: 1.07x faster                                                  |
| sqlglot_transpile          | 1.08 ms                                                | 1.01 ms: 1.07x faster                                                  |
| deltablue                  | 2.58 ms                                                | 2.42 ms: 1.07x faster                                                  |
| sympy_str                  | 151 ms                                                 | 143 ms: 1.06x faster                                                   |
| scimark_monte_carlo        | 50.1 ms                                                | 47.3 ms: 1.06x faster                                                  |
| logging_format             | 3.99 us                                                | 3.77 us: 1.06x faster                                                  |
| logging_simple             | 3.69 us                                                | 3.49 us: 1.06x faster                                                  |
| bench_mp_pool              | 46.3 ms                                                | 44.0 ms: 1.05x faster                                                  |
| deepcopy_reduce            | 2.05 us                                                | 1.96 us: 1.04x faster                                                  |
| sympy_integrate            | 11.3 ms                                                | 10.9 ms: 1.04x faster                                                  |
| docutils                   | 1.54 sec                                               | 1.48 sec: 1.04x faster                                                 |
| async_tree_none            | 262 ms                                                 | 253 ms: 1.04x faster                                                   |
| unpickle_list              | 3.24 us                                                | 3.13 us: 1.03x faster                                                  |
| nqueens                    | 60.2 ms                                                | 58.3 ms: 1.03x faster                                                  |
| spectral_norm              | 74.6 ms                                                | 72.6 ms: 1.03x faster                                                  |
| regex_dna                  | 153 ms                                                 | 149 ms: 1.03x faster                                                   |
| go                         | 107 ms                                                 | 105 ms: 1.02x faster                                                   |
| mdp                        | 1.66 sec                                               | 1.63 sec: 1.02x faster                                                 |
| sqlglot_normalize          | 188 ms                                                 | 184 ms: 1.02x faster                                                   |
| async_generators           | 306 ms                                                 | 300 ms: 1.02x faster                                                   |
| float                      | 58.1 ms                                                | 57.0 ms: 1.02x faster                                                  |
| sympy_expand               | 249 ms                                                 | 245 ms: 1.02x faster                                                   |
| deepcopy                   | 225 us                                                 | 222 us: 1.01x faster                                                   |
| json                       | 3.02 ms                                                | 2.98 ms: 1.01x faster                                                  |
| unpickle                   | 9.25 us                                                | 9.14 us: 1.01x faster                                                  |
| scimark_sparse_mat_mult    | 3.14 ms                                                | 3.11 ms: 1.01x faster                                                  |
| sqlglot_optimize           | 34.7 ms                                                | 34.3 ms: 1.01x faster                                                  |
| regex_effbot               | 2.59 ms                                                | 2.56 ms: 1.01x faster                                                  |
| dulwich_log                | 30.4 ms                                                | 30.1 ms: 1.01x faster                                                  |
| create_gc_cycles           | 704 us                                                 | 698 us: 1.01x faster                                                   |
| deepcopy_memo              | 24.6 us                                                | 24.4 us: 1.01x faster                                                  |
| python_startup             | 11.9 ms                                                | 11.8 ms: 1.01x faster                                                  |
| pickle                     | 7.42 us                                                | 7.37 us: 1.01x faster                                                  |
| pickle_dict                | 18.0 us                                                | 17.9 us: 1.01x faster                                                  |
| mako                       | 7.53 ms                                                | 7.49 ms: 1.00x faster                                                  |
| bench_thread_pool          | 492 us                                                 | 490 us: 1.00x faster                                                   |
| json_dumps                 | 6.46 ms                                                | 6.45 ms: 1.00x faster                                                  |
| gc_traversal               | 2.40 ms                                                | 2.40 ms: 1.00x faster                                                  |
| pidigits                   | 282 ms                                                 | 282 ms: 1.00x slower                                                   |
| 2to3                       | 171 ms                                                 | 171 ms: 1.00x slower                                                   |
| xml_etree_parse            | 109 ms                                                 | 110 ms: 1.01x slower                                                   |
| regex_compile              | 75.6 ms                                                | 76.3 ms: 1.01x slower                                                  |
| coroutines                 | 18.1 ms                                                | 18.3 ms: 1.01x slower                                                  |
| scimark_lu                 | 71.5 ms                                                | 72.2 ms: 1.01x slower                                                  |
| meteor_contest             | 73.3 ms                                                | 74.2 ms: 1.01x slower                                                  |
| xml_etree_iterparse        | 74.6 ms                                                | 75.9 ms: 1.02x slower                                                  |
| async_tree_io_tg           | 673 ms                                                 | 686 ms: 1.02x slower                                                   |
| async_tree_cpu_io_mixed_tg | 535 ms                                                 | 545 ms: 1.02x slower                                                   |
| sqlite_synth               | 1.59 us                                                | 1.62 us: 1.02x slower                                                  |
| pprint_pformat             | 1.00 sec                                               | 1.03 sec: 1.02x slower                                                 |
| xml_etree_process          | 38.7 ms                                                | 39.7 ms: 1.03x slower                                                  |
| pprint_safe_repr           | 491 ms                                                 | 505 ms: 1.03x slower                                                   |
| logging_silent             | 68.3 ns                                                | 70.2 ns: 1.03x slower                                                  |
| scimark_fft                | 198 ms                                                 | 204 ms: 1.03x slower                                                   |
| asyncio_tcp_ssl            | 1.26 sec                                               | 1.29 sec: 1.03x slower                                                 |
| chameleon                  | 4.51 ms                                                | 4.66 ms: 1.03x slower                                                  |
| xml_etree_generate         | 55.9 ms                                                | 57.7 ms: 1.03x slower                                                  |
| pycparser                  | 670 ms                                                 | 696 ms: 1.04x slower                                                   |
| pyflate                    | 329 ms                                                 | 341 ms: 1.04x slower                                                   |
| async_tree_memoization_tg  | 320 ms                                                 | 333 ms: 1.04x slower                                                   |
| pickle_pure_python         | 188 us                                                 | 197 us: 1.04x slower                                                   |
| async_tree_io              | 669 ms                                                 | 702 ms: 1.05x slower                                                   |
| async_tree_none_tg         | 254 ms                                                 | 267 ms: 1.05x slower                                                   |
| richards_super             | 34.9 ms                                                | 36.8 ms: 1.05x slower                                                  |
| async_tree_memoization     | 309 ms                                                 | 330 ms: 1.07x slower                                                   |
| regex_v8                   | 15.7 ms                                                | 16.9 ms: 1.08x slower                                                  |
| richards                   | 31.1 ms                                                | 33.6 ms: 1.08x slower                                                  |
| python_startup_no_site     | 9.71 ms                                                | 10.5 ms: 1.08x slower                                                  |
| unpickle_pure_python       | 145 us                                                 | 156 us: 1.08x slower                                                   |
| fannkuch                   | 265 ms                                                 | 289 ms: 1.09x slower                                                   |
| hexiom                     | 4.25 ms                                                | 4.71 ms: 1.11x slower                                                  |
| scimark_sor                | 94.3 ms                                                | 105 ms: 1.12x slower                                                   |
| tomli_loads                | 1.39 sec                                               | 1.56 sec: 1.12x slower                                                 |
| nbody                      | 68.5 ms                                                | 77.4 ms: 1.13x slower                                                  |
| telco                      | 3.79 ms                                                | 4.69 ms: 1.24x slower                                                  |
| coverage                   | 37.9 ms                                                | 48.4 ms: 1.28x slower                                                  |
| Geometric mean             | (ref)                                                  | 1.00x faster                                                           |

Benchmark hidden because not significant (8): tornado_http, pickle_list, json_loads, asyncio_websockets, async_tree_cpu_io_mixed, asyncio_tcp, mypy2, pathlib
Ignored benchmarks (6) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, dask, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 71.52% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
