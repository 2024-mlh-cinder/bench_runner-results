
# Results vs. 3.12.0

- fork: brandtbucher
- ref: justin
- machine: darwin-arm64
- commit hash: 7bb54b5
- commit date: 2023-11-20
- overall geometric mean: 1.03x slower \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.01x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-darwin-arm64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| 2to3           | 171 ms                                                 | 181 ms: 1.06x slower                                           |
| chameleon      | 4.51 ms                                                | 4.89 ms: 1.08x slower                                          |
| docutils       | 1.54 sec                                               | 1.53 sec: 1.01x faster                                         |
| Geometric mean | (ref)                                                  | 1.04x slower                                                   |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-darwin-arm64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|----------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| async_tree_none            | 262 ms                                                 | 257 ms: 1.02x faster                                           |
| async_tree_cpu_io_mixed_tg | 535 ms                                                 | 544 ms: 1.02x slower                                           |
| async_tree_io_tg           | 673 ms                                                 | 688 ms: 1.02x slower                                           |
| async_tree_io              | 669 ms                                                 | 706 ms: 1.06x slower                                           |
| async_tree_memoization_tg  | 320 ms                                                 | 337 ms: 1.06x slower                                           |
| async_tree_none_tg         | 254 ms                                                 | 270 ms: 1.06x slower                                           |
| async_tree_memoization     | 309 ms                                                 | 332 ms: 1.07x slower                                           |
| Geometric mean             | (ref)                                                  | 1.03x slower                                                   |

Benchmark hidden because not significant (1): async_tree_cpu_io_mixed

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-darwin-arm64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| pidigits       | 282 ms                                                 | 282 ms: 1.00x faster                                           |
| float          | 58.1 ms                                                | 58.4 ms: 1.01x slower                                          |
| nbody          | 68.5 ms                                                | 81.4 ms: 1.19x slower                                          |
| Geometric mean | (ref)                                                  | 1.06x slower                                                   |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-darwin-arm64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| regex_dna      | 153 ms                                                 | 149 ms: 1.03x faster                                           |
| regex_effbot   | 2.59 ms                                                | 2.56 ms: 1.01x faster                                          |
| regex_v8       | 15.7 ms                                                | 17.0 ms: 1.08x slower                                          |
| regex_compile  | 75.6 ms                                                | 83.7 ms: 1.11x slower                                          |
| Geometric mean | (ref)                                                  | 1.04x slower                                                   |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-darwin-arm64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|----------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| unpickle_list        | 3.24 us                                                | 3.13 us: 1.03x faster                                          |
| unpickle             | 9.25 us                                                | 9.04 us: 1.02x faster                                          |
| json_loads           | 17.6 us                                                | 17.2 us: 1.02x faster                                          |
| xml_etree_parse      | 109 ms                                                 | 107 ms: 1.01x faster                                           |
| pickle_list          | 2.89 us                                                | 2.88 us: 1.00x faster                                          |
| pickle_dict          | 18.0 us                                                | 17.9 us: 1.00x faster                                          |
| xml_etree_iterparse  | 74.6 ms                                                | 76.6 ms: 1.03x slower                                          |
| json_dumps           | 6.46 ms                                                | 6.67 ms: 1.03x slower                                          |
| xml_etree_generate   | 55.9 ms                                                | 58.9 ms: 1.05x slower                                          |
| xml_etree_process    | 38.7 ms                                                | 40.8 ms: 1.05x slower                                          |
| pickle_pure_python   | 188 us                                                 | 204 us: 1.08x slower                                           |
| tomli_loads          | 1.39 sec                                               | 1.52 sec: 1.09x slower                                         |
| unpickle_pure_python | 145 us                                                 | 166 us: 1.15x slower                                           |
| Geometric mean       | (ref)                                                  | 1.03x slower                                                   |

Benchmark hidden because not significant (1): pickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-darwin-arm64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| python_startup         | 11.9 ms                                                | 11.6 ms: 1.03x faster                                          |
| python_startup_no_site | 9.71 ms                                                | 10.2 ms: 1.05x slower                                          |
| Geometric mean         | (ref)                                                  | 1.01x slower                                                   |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-darwin-arm64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|-----------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| mako      | 7.53 ms                                                | 7.92 ms: 1.05x slower                                          |

All benchmarks:
===============

| Benchmark                  | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-darwin-arm64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|----------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| asyncio_websockets         | 545 ms                                                 | 409 ms: 1.33x faster                                           |
| raytrace                   | 246 ms                                                 | 194 ms: 1.27x faster                                           |
| pathlib                    | 29.3 ms                                                | 23.8 ms: 1.23x faster                                          |
| typing_runtime_protocols   | 90.8 us                                                | 77.5 us: 1.17x faster                                          |
| comprehensions             | 15.8 us                                                | 13.9 us: 1.13x faster                                          |
| asyncio_tcp                | 450 ms                                                 | 398 ms: 1.13x faster                                           |
| generators                 | 28.3 ms                                                | 25.6 ms: 1.11x faster                                          |
| crypto_pyaes               | 52.0 ms                                                | 50.1 ms: 1.04x faster                                          |
| unpickle_list              | 3.24 us                                                | 3.13 us: 1.03x faster                                          |
| sqlglot_parse              | 897 us                                                 | 868 us: 1.03x faster                                           |
| regex_dna                  | 153 ms                                                 | 149 ms: 1.03x faster                                           |
| logging_simple             | 3.69 us                                                | 3.60 us: 1.03x faster                                          |
| python_startup             | 11.9 ms                                                | 11.6 ms: 1.03x faster                                          |
| unpickle                   | 9.25 us                                                | 9.04 us: 1.02x faster                                          |
| json_loads                 | 17.6 us                                                | 17.2 us: 1.02x faster                                          |
| sqlglot_transpile          | 1.08 ms                                                | 1.05 ms: 1.02x faster                                          |
| logging_format             | 3.99 us                                                | 3.90 us: 1.02x faster                                          |
| async_tree_none            | 262 ms                                                 | 257 ms: 1.02x faster                                           |
| bench_mp_pool              | 46.3 ms                                                | 45.4 ms: 1.02x faster                                          |
| xml_etree_parse            | 109 ms                                                 | 107 ms: 1.01x faster                                           |
| regex_effbot               | 2.59 ms                                                | 2.56 ms: 1.01x faster                                          |
| docutils                   | 1.54 sec                                               | 1.53 sec: 1.01x faster                                         |
| create_gc_cycles           | 704 us                                                 | 699 us: 1.01x faster                                           |
| pickle_list                | 2.89 us                                                | 2.88 us: 1.00x faster                                          |
| pickle_dict                | 18.0 us                                                | 17.9 us: 1.00x faster                                          |
| deltablue                  | 2.58 ms                                                | 2.57 ms: 1.00x faster                                          |
| dulwich_log                | 30.4 ms                                                | 30.3 ms: 1.00x faster                                          |
| gc_traversal               | 2.40 ms                                                | 2.39 ms: 1.00x faster                                          |
| pidigits                   | 282 ms                                                 | 282 ms: 1.00x faster                                           |
| scimark_monte_carlo        | 50.1 ms                                                | 50.0 ms: 1.00x faster                                          |
| chaos                      | 44.8 ms                                                | 45.1 ms: 1.01x slower                                          |
| float                      | 58.1 ms                                                | 58.4 ms: 1.01x slower                                          |
| sympy_str                  | 151 ms                                                 | 152 ms: 1.01x slower                                           |
| sympy_sum                  | 79.5 ms                                                | 80.4 ms: 1.01x slower                                          |
| async_tree_cpu_io_mixed_tg | 535 ms                                                 | 544 ms: 1.02x slower                                           |
| mdp                        | 1.66 sec                                               | 1.69 sec: 1.02x slower                                         |
| async_tree_io_tg           | 673 ms                                                 | 688 ms: 1.02x slower                                           |
| xml_etree_iterparse        | 74.6 ms                                                | 76.6 ms: 1.03x slower                                          |
| coroutines                 | 18.1 ms                                                | 18.6 ms: 1.03x slower                                          |
| deepcopy                   | 225 us                                                 | 232 us: 1.03x slower                                           |
| json_dumps                 | 6.46 ms                                                | 6.67 ms: 1.03x slower                                          |
| async_generators           | 306 ms                                                 | 317 ms: 1.04x slower                                           |
| asyncio_tcp_ssl            | 1.26 sec                                               | 1.30 sec: 1.04x slower                                         |
| sympy_expand               | 249 ms                                                 | 259 ms: 1.04x slower                                           |
| sqlite_synth               | 1.59 us                                                | 1.66 us: 1.05x slower                                          |
| sqlglot_normalize          | 188 ms                                                 | 197 ms: 1.05x slower                                           |
| scimark_sparse_mat_mult    | 3.14 ms                                                | 3.30 ms: 1.05x slower                                          |
| sympy_integrate            | 11.3 ms                                                | 11.9 ms: 1.05x slower                                          |
| mako                       | 7.53 ms                                                | 7.92 ms: 1.05x slower                                          |
| xml_etree_generate         | 55.9 ms                                                | 58.9 ms: 1.05x slower                                          |
| python_startup_no_site     | 9.71 ms                                                | 10.2 ms: 1.05x slower                                          |
| xml_etree_process          | 38.7 ms                                                | 40.8 ms: 1.05x slower                                          |
| richards_super             | 34.9 ms                                                | 36.9 ms: 1.06x slower                                          |
| async_tree_io              | 669 ms                                                 | 706 ms: 1.06x slower                                           |
| async_tree_memoization_tg  | 320 ms                                                 | 337 ms: 1.06x slower                                           |
| go                         | 107 ms                                                 | 114 ms: 1.06x slower                                           |
| 2to3                       | 171 ms                                                 | 181 ms: 1.06x slower                                           |
| async_tree_none_tg         | 254 ms                                                 | 270 ms: 1.06x slower                                           |
| sqlglot_optimize           | 34.7 ms                                                | 36.8 ms: 1.06x slower                                          |
| pyflate                    | 329 ms                                                 | 350 ms: 1.06x slower                                           |
| deepcopy_memo              | 24.6 us                                                | 26.1 us: 1.06x slower                                          |
| pycparser                  | 670 ms                                                 | 715 ms: 1.07x slower                                           |
| richards                   | 31.1 ms                                                | 33.2 ms: 1.07x slower                                          |
| async_tree_memoization     | 309 ms                                                 | 332 ms: 1.07x slower                                           |
| meteor_contest             | 73.3 ms                                                | 78.8 ms: 1.08x slower                                          |
| logging_silent             | 68.3 ns                                                | 73.5 ns: 1.08x slower                                          |
| bench_thread_pool          | 492 us                                                 | 530 us: 1.08x slower                                           |
| chameleon                  | 4.51 ms                                                | 4.89 ms: 1.08x slower                                          |
| regex_v8                   | 15.7 ms                                                | 17.0 ms: 1.08x slower                                          |
| scimark_lu                 | 71.5 ms                                                | 77.5 ms: 1.08x slower                                          |
| pickle_pure_python         | 188 us                                                 | 204 us: 1.08x slower                                           |
| nqueens                    | 60.2 ms                                                | 65.6 ms: 1.09x slower                                          |
| spectral_norm              | 74.6 ms                                                | 81.4 ms: 1.09x slower                                          |
| tomli_loads                | 1.39 sec                                               | 1.52 sec: 1.09x slower                                         |
| pprint_safe_repr           | 491 ms                                                 | 538 ms: 1.10x slower                                           |
| pprint_pformat             | 1.00 sec                                               | 1.11 sec: 1.11x slower                                         |
| regex_compile              | 75.6 ms                                                | 83.7 ms: 1.11x slower                                          |
| fannkuch                   | 265 ms                                                 | 299 ms: 1.13x slower                                           |
| scimark_fft                | 198 ms                                                 | 224 ms: 1.13x slower                                           |
| scimark_sor                | 94.3 ms                                                | 108 ms: 1.14x slower                                           |
| unpickle_pure_python       | 145 us                                                 | 166 us: 1.15x slower                                           |
| nbody                      | 68.5 ms                                                | 81.4 ms: 1.19x slower                                          |
| telco                      | 3.79 ms                                                | 4.76 ms: 1.25x slower                                          |
| coverage                   | 37.9 ms                                                | 48.3 ms: 1.27x slower                                          |
| hexiom                     | 4.25 ms                                                | 5.79 ms: 1.36x slower                                          |
| Geometric mean             | (ref)                                                  | 1.03x slower                                                   |

Benchmark hidden because not significant (8): json, pickle, unpack_sequence, deepcopy_reduce, async_tree_cpu_io_mixed, dask, mypy2, tornado_http
Ignored benchmarks (5) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.02x
- 95% likely to have a slowdown of 1.02x
- 99% likely to have a slowdown of 1.01x
