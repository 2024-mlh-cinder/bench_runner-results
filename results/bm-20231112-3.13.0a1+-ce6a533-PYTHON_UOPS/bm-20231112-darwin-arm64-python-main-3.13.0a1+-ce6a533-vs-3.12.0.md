
# Results vs. 3.12.0

- fork: python
- ref: main
- machine: darwin-arm64
- commit hash: ce6a533
- commit date: 2023-11-12
- overall geometric mean: 1.09x slower \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.03x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231112-darwin-arm64-python-main-3.13.0a1+-ce6a533 |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| 2to3           | 171 ms                                                 | 186 ms: 1.09x slower                                   |
| chameleon      | 4.51 ms                                                | 5.01 ms: 1.11x slower                                  |
| docutils       | 1.54 sec                                               | 1.55 sec: 1.00x slower                                 |
| Geometric mean | (ref)                                                  | 1.05x slower                                           |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231112-darwin-arm64-python-main-3.13.0a1+-ce6a533 |
|----------------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| async_tree_none            | 262 ms                                                 | 270 ms: 1.03x slower                                   |
| async_tree_cpu_io_mixed    | 525 ms                                                 | 542 ms: 1.03x slower                                   |
| async_tree_cpu_io_mixed_tg | 535 ms                                                 | 559 ms: 1.05x slower                                   |
| async_tree_io_tg           | 673 ms                                                 | 709 ms: 1.05x slower                                   |
| async_tree_io              | 669 ms                                                 | 729 ms: 1.09x slower                                   |
| async_tree_memoization_tg  | 320 ms                                                 | 353 ms: 1.10x slower                                   |
| async_tree_none_tg         | 254 ms                                                 | 282 ms: 1.11x slower                                   |
| async_tree_memoization     | 309 ms                                                 | 346 ms: 1.12x slower                                   |
| Geometric mean             | (ref)                                                  | 1.07x slower                                           |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231112-darwin-arm64-python-main-3.13.0a1+-ce6a533 |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| pidigits       | 282 ms                                                 | 283 ms: 1.00x slower                                   |
| float          | 58.1 ms                                                | 75.9 ms: 1.31x slower                                  |
| nbody          | 68.5 ms                                                | 98.8 ms: 1.44x slower                                  |
| Geometric mean | (ref)                                                  | 1.24x slower                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231112-darwin-arm64-python-main-3.13.0a1+-ce6a533 |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| regex_dna      | 153 ms                                                 | 149 ms: 1.03x faster                                   |
| regex_effbot   | 2.59 ms                                                | 2.56 ms: 1.01x faster                                  |
| regex_v8       | 15.7 ms                                                | 17.0 ms: 1.09x slower                                  |
| regex_compile  | 75.6 ms                                                | 93.2 ms: 1.23x slower                                  |
| Geometric mean | (ref)                                                  | 1.07x slower                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231112-darwin-arm64-python-main-3.13.0a1+-ce6a533 |
|----------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| unpickle_list        | 3.24 us                                                | 3.13 us: 1.04x faster                                  |
| unpickle             | 9.25 us                                                | 9.17 us: 1.01x faster                                  |
| pickle_dict          | 18.0 us                                                | 18.1 us: 1.00x slower                                  |
| xml_etree_parse      | 109 ms                                                 | 110 ms: 1.01x slower                                   |
| json_dumps           | 6.46 ms                                                | 6.56 ms: 1.02x slower                                  |
| xml_etree_process    | 38.7 ms                                                | 40.0 ms: 1.03x slower                                  |
| xml_etree_generate   | 55.9 ms                                                | 59.2 ms: 1.06x slower                                  |
| pickle_pure_python   | 188 us                                                 | 201 us: 1.06x slower                                   |
| xml_etree_iterparse  | 74.6 ms                                                | 82.1 ms: 1.10x slower                                  |
| unpickle_pure_python | 145 us                                                 | 177 us: 1.23x slower                                   |
| tomli_loads          | 1.39 sec                                               | 2.05 sec: 1.48x slower                                 |
| Geometric mean       | (ref)                                                  | 1.06x slower                                           |

Benchmark hidden because not significant (3): pickle_list, json_loads, pickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231112-darwin-arm64-python-main-3.13.0a1+-ce6a533 |
|------------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| python_startup         | 11.9 ms                                                | 12.2 ms: 1.03x slower                                  |
| python_startup_no_site | 9.71 ms                                                | 10.9 ms: 1.12x slower                                  |
| Geometric mean         | (ref)                                                  | 1.07x slower                                           |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231112-darwin-arm64-python-main-3.13.0a1+-ce6a533 |
|-----------|:------------------------------------------------------:|:------------------------------------------------------:|
| mako      | 7.53 ms                                                | 10.5 ms: 1.40x slower                                  |

All benchmarks:
===============

| Benchmark                  | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231112-darwin-arm64-python-main-3.13.0a1+-ce6a533 |
|----------------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| raytrace                   | 246 ms                                                 | 198 ms: 1.24x faster                                   |
| generators                 | 28.3 ms                                                | 24.7 ms: 1.15x faster                                  |
| typing_runtime_protocols   | 90.8 us                                                | 81.3 us: 1.12x faster                                  |
| unpack_sequence            | 28.4 ns                                                | 26.7 ns: 1.06x faster                                  |
| sqlglot_parse              | 897 us                                                 | 862 us: 1.04x faster                                   |
| unpickle_list              | 3.24 us                                                | 3.13 us: 1.04x faster                                  |
| bench_mp_pool              | 46.3 ms                                                | 44.9 ms: 1.03x faster                                  |
| sqlglot_transpile          | 1.08 ms                                                | 1.05 ms: 1.03x faster                                  |
| deepcopy_reduce            | 2.05 us                                                | 1.99 us: 1.03x faster                                  |
| regex_dna                  | 153 ms                                                 | 149 ms: 1.03x faster                                   |
| spectral_norm              | 74.6 ms                                                | 72.9 ms: 1.02x faster                                  |
| sympy_sum                  | 79.5 ms                                                | 78.0 ms: 1.02x faster                                  |
| regex_effbot               | 2.59 ms                                                | 2.56 ms: 1.01x faster                                  |
| unpickle                   | 9.25 us                                                | 9.17 us: 1.01x faster                                  |
| create_gc_cycles           | 704 us                                                 | 700 us: 1.01x faster                                   |
| gc_traversal               | 2.40 ms                                                | 2.40 ms: 1.00x faster                                  |
| logging_format             | 3.99 us                                                | 4.00 us: 1.00x slower                                  |
| coroutines                 | 18.1 ms                                                | 18.2 ms: 1.00x slower                                  |
| docutils                   | 1.54 sec                                               | 1.55 sec: 1.00x slower                                 |
| pidigits                   | 282 ms                                                 | 283 ms: 1.00x slower                                   |
| pickle_dict                | 18.0 us                                                | 18.1 us: 1.00x slower                                  |
| deepcopy                   | 225 us                                                 | 226 us: 1.00x slower                                   |
| sympy_str                  | 151 ms                                                 | 152 ms: 1.01x slower                                   |
| logging_simple             | 3.69 us                                                | 3.72 us: 1.01x slower                                  |
| xml_etree_parse            | 109 ms                                                 | 110 ms: 1.01x slower                                   |
| sqlglot_normalize          | 188 ms                                                 | 190 ms: 1.01x slower                                   |
| json_dumps                 | 6.46 ms                                                | 6.56 ms: 1.02x slower                                  |
| sqlglot_optimize           | 34.7 ms                                                | 35.3 ms: 1.02x slower                                  |
| dulwich_log                | 30.4 ms                                                | 30.9 ms: 1.02x slower                                  |
| async_generators           | 306 ms                                                 | 312 ms: 1.02x slower                                   |
| pathlib                    | 29.3 ms                                                | 30.0 ms: 1.02x slower                                  |
| python_startup             | 11.9 ms                                                | 12.2 ms: 1.03x slower                                  |
| sympy_expand               | 249 ms                                                 | 256 ms: 1.03x slower                                   |
| async_tree_none            | 262 ms                                                 | 270 ms: 1.03x slower                                   |
| async_tree_cpu_io_mixed    | 525 ms                                                 | 542 ms: 1.03x slower                                   |
| xml_etree_process          | 38.7 ms                                                | 40.0 ms: 1.03x slower                                  |
| asyncio_tcp_ssl            | 1.26 sec                                               | 1.30 sec: 1.03x slower                                 |
| bench_thread_pool          | 492 us                                                 | 514 us: 1.04x slower                                   |
| async_tree_cpu_io_mixed_tg | 535 ms                                                 | 559 ms: 1.05x slower                                   |
| async_tree_io_tg           | 673 ms                                                 | 709 ms: 1.05x slower                                   |
| logging_silent             | 68.3 ns                                                | 72.3 ns: 1.06x slower                                  |
| xml_etree_generate         | 55.9 ms                                                | 59.2 ms: 1.06x slower                                  |
| pickle_pure_python         | 188 us                                                 | 201 us: 1.06x slower                                   |
| sqlite_synth               | 1.59 us                                                | 1.69 us: 1.07x slower                                  |
| mdp                        | 1.66 sec                                               | 1.78 sec: 1.07x slower                                 |
| sympy_integrate            | 11.3 ms                                                | 12.2 ms: 1.07x slower                                  |
| pycparser                  | 670 ms                                                 | 721 ms: 1.08x slower                                   |
| 2to3                       | 171 ms                                                 | 186 ms: 1.09x slower                                   |
| regex_v8                   | 15.7 ms                                                | 17.0 ms: 1.09x slower                                  |
| async_tree_io              | 669 ms                                                 | 729 ms: 1.09x slower                                   |
| chaos                      | 44.8 ms                                                | 49.1 ms: 1.10x slower                                  |
| scimark_lu                 | 71.5 ms                                                | 78.4 ms: 1.10x slower                                  |
| xml_etree_iterparse        | 74.6 ms                                                | 82.1 ms: 1.10x slower                                  |
| richards_super             | 34.9 ms                                                | 38.5 ms: 1.10x slower                                  |
| async_tree_memoization_tg  | 320 ms                                                 | 353 ms: 1.10x slower                                   |
| async_tree_none_tg         | 254 ms                                                 | 282 ms: 1.11x slower                                   |
| chameleon                  | 4.51 ms                                                | 5.01 ms: 1.11x slower                                  |
| crypto_pyaes               | 52.0 ms                                                | 57.9 ms: 1.11x slower                                  |
| go                         | 107 ms                                                 | 119 ms: 1.11x slower                                   |
| deepcopy_memo              | 24.6 us                                                | 27.4 us: 1.12x slower                                  |
| async_tree_memoization     | 309 ms                                                 | 346 ms: 1.12x slower                                   |
| python_startup_no_site     | 9.71 ms                                                | 10.9 ms: 1.12x slower                                  |
| richards                   | 31.1 ms                                                | 35.0 ms: 1.12x slower                                  |
| meteor_contest             | 73.3 ms                                                | 83.8 ms: 1.14x slower                                  |
| scimark_monte_carlo        | 50.1 ms                                                | 57.3 ms: 1.14x slower                                  |
| scimark_sor                | 94.3 ms                                                | 109 ms: 1.15x slower                                   |
| pprint_safe_repr           | 491 ms                                                 | 579 ms: 1.18x slower                                   |
| pprint_pformat             | 1.00 sec                                               | 1.18 sec: 1.18x slower                                 |
| pyflate                    | 329 ms                                                 | 403 ms: 1.23x slower                                   |
| unpickle_pure_python       | 145 us                                                 | 177 us: 1.23x slower                                   |
| regex_compile              | 75.6 ms                                                | 93.2 ms: 1.23x slower                                  |
| coverage                   | 37.9 ms                                                | 47.5 ms: 1.25x slower                                  |
| comprehensions             | 15.8 us                                                | 19.9 us: 1.27x slower                                  |
| scimark_fft                | 198 ms                                                 | 258 ms: 1.30x slower                                   |
| float                      | 58.1 ms                                                | 75.9 ms: 1.31x slower                                  |
| nqueens                    | 60.2 ms                                                | 80.1 ms: 1.33x slower                                  |
| telco                      | 3.79 ms                                                | 5.07 ms: 1.34x slower                                  |
| mako                       | 7.53 ms                                                | 10.5 ms: 1.40x slower                                  |
| nbody                      | 68.5 ms                                                | 98.8 ms: 1.44x slower                                  |
| tomli_loads                | 1.39 sec                                               | 2.05 sec: 1.48x slower                                 |
| fannkuch                   | 265 ms                                                 | 396 ms: 1.50x slower                                   |
| deltablue                  | 2.58 ms                                                | 3.90 ms: 1.51x slower                                  |
| scimark_sparse_mat_mult    | 3.14 ms                                                | 4.98 ms: 1.58x slower                                  |
| hexiom                     | 4.25 ms                                                | 7.57 ms: 1.78x slower                                  |
| Geometric mean             | (ref)                                                  | 1.09x slower                                           |

Benchmark hidden because not significant (8): asyncio_tcp, json, pickle_list, json_loads, asyncio_websockets, pickle, tornado_http, mypy2
Ignored benchmarks (6) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, dask, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.04x
- 95% likely to have a slowdown of 1.04x
- 99% likely to have a slowdown of 1.03x
