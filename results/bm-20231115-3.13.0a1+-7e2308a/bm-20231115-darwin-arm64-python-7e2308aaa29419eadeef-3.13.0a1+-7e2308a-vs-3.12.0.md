
# Results vs. 3.12.0

- fork: python
- ref: 7e2308aaa29419eadeef
- machine: darwin-arm64
- commit hash: 7e2308a
- commit date: 2023-11-15
- overall geometric mean: 1.02x slower \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231115-darwin-arm64-python-7e2308aaa29419eadeef-3.13.0a1+-7e2308a |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| 2to3           | 171 ms                                                 | 178 ms: 1.04x slower                                                   |
| chameleon      | 4.51 ms                                                | 4.85 ms: 1.07x slower                                                  |
| docutils       | 1.54 sec                                               | 1.52 sec: 1.01x faster                                                 |
| Geometric mean | (ref)                                                  | 1.03x slower                                                           |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231115-darwin-arm64-python-7e2308aaa29419eadeef-3.13.0a1+-7e2308a |
|----------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| async_tree_cpu_io_mixed    | 525 ms                                                 | 534 ms: 1.02x slower                                                   |
| async_tree_cpu_io_mixed_tg | 535 ms                                                 | 552 ms: 1.03x slower                                                   |
| async_tree_io_tg           | 673 ms                                                 | 714 ms: 1.06x slower                                                   |
| async_tree_memoization_tg  | 320 ms                                                 | 341 ms: 1.07x slower                                                   |
| async_tree_none_tg         | 254 ms                                                 | 275 ms: 1.08x slower                                                   |
| async_tree_io              | 669 ms                                                 | 727 ms: 1.09x slower                                                   |
| async_tree_memoization     | 309 ms                                                 | 338 ms: 1.09x slower                                                   |
| Geometric mean             | (ref)                                                  | 1.05x slower                                                           |

Benchmark hidden because not significant (1): async_tree_none

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231115-darwin-arm64-python-7e2308aaa29419eadeef-3.13.0a1+-7e2308a |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| pidigits       | 282 ms                                                 | 283 ms: 1.00x slower                                                   |
| float          | 58.1 ms                                                | 59.9 ms: 1.03x slower                                                  |
| nbody          | 68.5 ms                                                | 79.6 ms: 1.16x slower                                                  |
| Geometric mean | (ref)                                                  | 1.06x slower                                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231115-darwin-arm64-python-7e2308aaa29419eadeef-3.13.0a1+-7e2308a |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| regex_dna      | 153 ms                                                 | 149 ms: 1.02x faster                                                   |
| regex_effbot   | 2.59 ms                                                | 2.56 ms: 1.01x faster                                                  |
| regex_compile  | 75.6 ms                                                | 78.7 ms: 1.04x slower                                                  |
| regex_v8       | 15.7 ms                                                | 17.0 ms: 1.08x slower                                                  |
| Geometric mean | (ref)                                                  | 1.02x slower                                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231115-darwin-arm64-python-7e2308aaa29419eadeef-3.13.0a1+-7e2308a |
|----------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| unpickle_list        | 3.24 us                                                | 3.12 us: 1.04x faster                                                  |
| unpickle             | 9.25 us                                                | 9.09 us: 1.02x faster                                                  |
| xml_etree_parse      | 109 ms                                                 | 108 ms: 1.01x faster                                                   |
| pickle               | 7.42 us                                                | 7.44 us: 1.00x slower                                                  |
| json_loads           | 17.6 us                                                | 17.8 us: 1.01x slower                                                  |
| json_dumps           | 6.46 ms                                                | 6.60 ms: 1.02x slower                                                  |
| pickle_list          | 2.89 us                                                | 2.96 us: 1.02x slower                                                  |
| xml_etree_iterparse  | 74.6 ms                                                | 77.6 ms: 1.04x slower                                                  |
| xml_etree_generate   | 55.9 ms                                                | 59.3 ms: 1.06x slower                                                  |
| xml_etree_process    | 38.7 ms                                                | 41.0 ms: 1.06x slower                                                  |
| pickle_pure_python   | 188 us                                                 | 202 us: 1.07x slower                                                   |
| unpickle_pure_python | 145 us                                                 | 162 us: 1.12x slower                                                   |
| tomli_loads          | 1.39 sec                                               | 1.60 sec: 1.15x slower                                                 |
| Geometric mean       | (ref)                                                  | 1.03x slower                                                           |

Benchmark hidden because not significant (1): pickle_dict

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231115-darwin-arm64-python-7e2308aaa29419eadeef-3.13.0a1+-7e2308a |
|------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| python_startup         | 11.9 ms                                                | 12.0 ms: 1.00x slower                                                  |
| python_startup_no_site | 9.71 ms                                                | 10.6 ms: 1.09x slower                                                  |
| Geometric mean         | (ref)                                                  | 1.05x slower                                                           |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231115-darwin-arm64-python-7e2308aaa29419eadeef-3.13.0a1+-7e2308a |
|-----------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| mako      | 7.53 ms                                                | 7.81 ms: 1.04x slower                                                  |

All benchmarks:
===============

| Benchmark                  | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231115-darwin-arm64-python-7e2308aaa29419eadeef-3.13.0a1+-7e2308a |
|----------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| raytrace                   | 246 ms                                                 | 192 ms: 1.28x faster                                                   |
| comprehensions             | 15.8 us                                                | 12.6 us: 1.25x faster                                                  |
| typing_runtime_protocols   | 90.8 us                                                | 77.9 us: 1.17x faster                                                  |
| generators                 | 28.3 ms                                                | 25.7 ms: 1.10x faster                                                  |
| crypto_pyaes               | 52.0 ms                                                | 49.3 ms: 1.06x faster                                                  |
| sqlglot_parse              | 897 us                                                 | 853 us: 1.05x faster                                                   |
| sympy_sum                  | 79.5 ms                                                | 76.0 ms: 1.05x faster                                                  |
| unpickle_list              | 3.24 us                                                | 3.12 us: 1.04x faster                                                  |
| deltablue                  | 2.58 ms                                                | 2.49 ms: 1.04x faster                                                  |
| bench_mp_pool              | 46.3 ms                                                | 44.7 ms: 1.03x faster                                                  |
| sqlglot_transpile          | 1.08 ms                                                | 1.04 ms: 1.03x faster                                                  |
| sympy_str                  | 151 ms                                                 | 147 ms: 1.03x faster                                                   |
| scimark_monte_carlo        | 50.1 ms                                                | 48.8 ms: 1.03x faster                                                  |
| regex_dna                  | 153 ms                                                 | 149 ms: 1.02x faster                                                   |
| pathlib                    | 29.3 ms                                                | 28.7 ms: 1.02x faster                                                  |
| unpickle                   | 9.25 us                                                | 9.09 us: 1.02x faster                                                  |
| docutils                   | 1.54 sec                                               | 1.52 sec: 1.01x faster                                                 |
| logging_format             | 3.99 us                                                | 3.95 us: 1.01x faster                                                  |
| chaos                      | 44.8 ms                                                | 44.3 ms: 1.01x faster                                                  |
| regex_effbot               | 2.59 ms                                                | 2.56 ms: 1.01x faster                                                  |
| xml_etree_parse            | 109 ms                                                 | 108 ms: 1.01x faster                                                   |
| pidigits                   | 282 ms                                                 | 283 ms: 1.00x slower                                                   |
| go                         | 107 ms                                                 | 107 ms: 1.00x slower                                                   |
| python_startup             | 11.9 ms                                                | 12.0 ms: 1.00x slower                                                  |
| pickle                     | 7.42 us                                                | 7.44 us: 1.00x slower                                                  |
| asyncio_websockets         | 545 ms                                                 | 547 ms: 1.00x slower                                                   |
| spectral_norm              | 74.6 ms                                                | 75.1 ms: 1.01x slower                                                  |
| async_generators           | 306 ms                                                 | 308 ms: 1.01x slower                                                   |
| mdp                        | 1.66 sec                                               | 1.68 sec: 1.01x slower                                                 |
| json_loads                 | 17.6 us                                                | 17.8 us: 1.01x slower                                                  |
| json                       | 3.02 ms                                                | 3.05 ms: 1.01x slower                                                  |
| scimark_sparse_mat_mult    | 3.14 ms                                                | 3.18 ms: 1.01x slower                                                  |
| async_tree_cpu_io_mixed    | 525 ms                                                 | 534 ms: 1.02x slower                                                   |
| dulwich_log                | 30.4 ms                                                | 30.9 ms: 1.02x slower                                                  |
| gc_traversal               | 2.40 ms                                                | 2.44 ms: 1.02x slower                                                  |
| deepcopy                   | 225 us                                                 | 229 us: 1.02x slower                                                   |
| json_dumps                 | 6.46 ms                                                | 6.60 ms: 1.02x slower                                                  |
| pickle_list                | 2.89 us                                                | 2.96 us: 1.02x slower                                                  |
| meteor_contest             | 73.3 ms                                                | 75.1 ms: 1.02x slower                                                  |
| dask                       | 228 ms                                                 | 233 ms: 1.02x slower                                                   |
| sqlglot_normalize          | 188 ms                                                 | 193 ms: 1.03x slower                                                   |
| deepcopy_memo              | 24.6 us                                                | 25.2 us: 1.03x slower                                                  |
| sqlite_synth               | 1.59 us                                                | 1.63 us: 1.03x slower                                                  |
| sqlglot_optimize           | 34.7 ms                                                | 35.7 ms: 1.03x slower                                                  |
| float                      | 58.1 ms                                                | 59.9 ms: 1.03x slower                                                  |
| async_tree_cpu_io_mixed_tg | 535 ms                                                 | 552 ms: 1.03x slower                                                   |
| sympy_expand               | 249 ms                                                 | 257 ms: 1.03x slower                                                   |
| create_gc_cycles           | 704 us                                                 | 729 us: 1.04x slower                                                   |
| mako                       | 7.53 ms                                                | 7.81 ms: 1.04x slower                                                  |
| xml_etree_iterparse        | 74.6 ms                                                | 77.6 ms: 1.04x slower                                                  |
| regex_compile              | 75.6 ms                                                | 78.7 ms: 1.04x slower                                                  |
| 2to3                       | 171 ms                                                 | 178 ms: 1.04x slower                                                   |
| asyncio_tcp_ssl            | 1.26 sec                                               | 1.31 sec: 1.05x slower                                                 |
| coroutines                 | 18.1 ms                                                | 19.1 ms: 1.05x slower                                                  |
| scimark_lu                 | 71.5 ms                                                | 75.3 ms: 1.05x slower                                                  |
| bench_thread_pool          | 492 us                                                 | 520 us: 1.06x slower                                                   |
| xml_etree_generate         | 55.9 ms                                                | 59.3 ms: 1.06x slower                                                  |
| xml_etree_process          | 38.7 ms                                                | 41.0 ms: 1.06x slower                                                  |
| async_tree_io_tg           | 673 ms                                                 | 714 ms: 1.06x slower                                                   |
| scimark_fft                | 198 ms                                                 | 210 ms: 1.06x slower                                                   |
| pprint_pformat             | 1.00 sec                                               | 1.06 sec: 1.06x slower                                                 |
| pyflate                    | 329 ms                                                 | 350 ms: 1.06x slower                                                   |
| async_tree_memoization_tg  | 320 ms                                                 | 341 ms: 1.07x slower                                                   |
| pycparser                  | 670 ms                                                 | 717 ms: 1.07x slower                                                   |
| pprint_safe_repr           | 491 ms                                                 | 527 ms: 1.07x slower                                                   |
| pickle_pure_python         | 188 us                                                 | 202 us: 1.07x slower                                                   |
| chameleon                  | 4.51 ms                                                | 4.85 ms: 1.07x slower                                                  |
| regex_v8                   | 15.7 ms                                                | 17.0 ms: 1.08x slower                                                  |
| async_tree_none_tg         | 254 ms                                                 | 275 ms: 1.08x slower                                                   |
| async_tree_io              | 669 ms                                                 | 727 ms: 1.09x slower                                                   |
| python_startup_no_site     | 9.71 ms                                                | 10.6 ms: 1.09x slower                                                  |
| async_tree_memoization     | 309 ms                                                 | 338 ms: 1.09x slower                                                   |
| logging_silent             | 68.3 ns                                                | 75.0 ns: 1.10x slower                                                  |
| richards_super             | 34.9 ms                                                | 38.5 ms: 1.10x slower                                                  |
| fannkuch                   | 265 ms                                                 | 294 ms: 1.11x slower                                                   |
| unpickle_pure_python       | 145 us                                                 | 162 us: 1.12x slower                                                   |
| richards                   | 31.1 ms                                                | 35.1 ms: 1.13x slower                                                  |
| scimark_sor                | 94.3 ms                                                | 108 ms: 1.14x slower                                                   |
| tomli_loads                | 1.39 sec                                               | 1.60 sec: 1.15x slower                                                 |
| nbody                      | 68.5 ms                                                | 79.6 ms: 1.16x slower                                                  |
| hexiom                     | 4.25 ms                                                | 4.99 ms: 1.17x slower                                                  |
| telco                      | 3.79 ms                                                | 4.63 ms: 1.22x slower                                                  |
| coverage                   | 37.9 ms                                                | 48.1 ms: 1.27x slower                                                  |
| Geometric mean             | (ref)                                                  | 1.02x slower                                                           |

Benchmark hidden because not significant (10): asyncio_tcp, async_tree_none, logging_simple, nqueens, unpack_sequence, pickle_dict, deepcopy_reduce, sympy_integrate, tornado_http, mypy2
Ignored benchmarks (5) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.01x
- 95% likely to have a slowdown of 1.01x
- 99% likely to have a slowdown of 1.00x
