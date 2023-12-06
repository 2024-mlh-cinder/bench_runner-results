
# Results vs. 3.12.0

- fork: brandtbucher
- ref: justin
- machine: darwin-arm64
- commit hash: 7a7e995
- commit date: 2023-11-15
- overall geometric mean: 1.05x slower \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.02x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231115-darwin-arm64-brandtbucher-justin-3.13.0a1+-7a7e995 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| 2to3           | 171 ms                                                 | 183 ms: 1.07x slower                                           |
| chameleon      | 4.51 ms                                                | 4.92 ms: 1.09x slower                                          |
| docutils       | 1.54 sec                                               | 1.55 sec: 1.01x slower                                         |
| tornado_http   | 70.7 ms                                                | 76.3 ms: 1.08x slower                                          |
| Geometric mean | (ref)                                                  | 1.06x slower                                                   |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231115-darwin-arm64-brandtbucher-justin-3.13.0a1+-7a7e995 |
|----------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| async_tree_cpu_io_mixed    | 525 ms                                                 | 539 ms: 1.03x slower                                           |
| async_tree_cpu_io_mixed_tg | 535 ms                                                 | 553 ms: 1.03x slower                                           |
| async_tree_io_tg           | 673 ms                                                 | 700 ms: 1.04x slower                                           |
| async_tree_memoization_tg  | 320 ms                                                 | 342 ms: 1.07x slower                                           |
| async_tree_none_tg         | 254 ms                                                 | 275 ms: 1.08x slower                                           |
| async_tree_io              | 669 ms                                                 | 729 ms: 1.09x slower                                           |
| async_tree_memoization     | 309 ms                                                 | 338 ms: 1.09x slower                                           |
| Geometric mean             | (ref)                                                  | 1.05x slower                                                   |

Benchmark hidden because not significant (1): async_tree_none

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231115-darwin-arm64-brandtbucher-justin-3.13.0a1+-7a7e995 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| pidigits       | 282 ms                                                 | 283 ms: 1.00x slower                                           |
| float          | 58.1 ms                                                | 60.0 ms: 1.03x slower                                          |
| nbody          | 68.5 ms                                                | 83.5 ms: 1.22x slower                                          |
| Geometric mean | (ref)                                                  | 1.08x slower                                                   |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231115-darwin-arm64-brandtbucher-justin-3.13.0a1+-7a7e995 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| regex_dna      | 153 ms                                                 | 150 ms: 1.01x faster                                           |
| regex_effbot   | 2.59 ms                                                | 2.58 ms: 1.01x faster                                          |
| regex_v8       | 15.7 ms                                                | 17.0 ms: 1.09x slower                                          |
| regex_compile  | 75.6 ms                                                | 83.2 ms: 1.10x slower                                          |
| Geometric mean | (ref)                                                  | 1.04x slower                                                   |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231115-darwin-arm64-brandtbucher-justin-3.13.0a1+-7a7e995 |
|----------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| pickle_dict          | 18.0 us                                                | 18.1 us: 1.00x slower                                          |
| unpickle             | 9.25 us                                                | 9.35 us: 1.01x slower                                          |
| pickle               | 7.42 us                                                | 7.51 us: 1.01x slower                                          |
| json_loads           | 17.6 us                                                | 17.9 us: 1.01x slower                                          |
| json_dumps           | 6.46 ms                                                | 6.69 ms: 1.04x slower                                          |
| unpickle_list        | 3.24 us                                                | 3.37 us: 1.04x slower                                          |
| pickle_pure_python   | 188 us                                                 | 206 us: 1.09x slower                                           |
| tomli_loads          | 1.39 sec                                               | 1.53 sec: 1.10x slower                                         |
| xml_etree_generate   | 55.9 ms                                                | 62.5 ms: 1.12x slower                                          |
| xml_etree_process    | 38.7 ms                                                | 44.5 ms: 1.15x slower                                          |
| xml_etree_iterparse  | 74.6 ms                                                | 88.5 ms: 1.19x slower                                          |
| unpickle_pure_python | 145 us                                                 | 179 us: 1.24x slower                                           |
| xml_etree_parse      | 109 ms                                                 | 140 ms: 1.29x slower                                           |
| Geometric mean       | (ref)                                                  | 1.09x slower                                                   |

Benchmark hidden because not significant (1): pickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231115-darwin-arm64-brandtbucher-justin-3.13.0a1+-7a7e995 |
|------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| python_startup         | 11.9 ms                                                | 11.9 ms: 1.00x faster                                          |
| python_startup_no_site | 9.71 ms                                                | 10.4 ms: 1.08x slower                                          |
| Geometric mean         | (ref)                                                  | 1.03x slower                                                   |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231115-darwin-arm64-brandtbucher-justin-3.13.0a1+-7a7e995 |
|-----------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| mako      | 7.53 ms                                                | 7.96 ms: 1.06x slower                                          |

All benchmarks:
===============

| Benchmark                  | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231115-darwin-arm64-brandtbucher-justin-3.13.0a1+-7a7e995 |
|----------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| raytrace                   | 246 ms                                                 | 193 ms: 1.28x faster                                           |
| typing_runtime_protocols   | 90.8 us                                                | 78.3 us: 1.16x faster                                          |
| comprehensions             | 15.8 us                                                | 14.0 us: 1.13x faster                                          |
| generators                 | 28.3 ms                                                | 26.3 ms: 1.08x faster                                          |
| sqlglot_parse              | 897 us                                                 | 858 us: 1.05x faster                                           |
| sqlglot_transpile          | 1.08 ms                                                | 1.04 ms: 1.03x faster                                          |
| crypto_pyaes               | 52.0 ms                                                | 50.6 ms: 1.03x faster                                          |
| sympy_sum                  | 79.5 ms                                                | 77.5 ms: 1.03x faster                                          |
| logging_simple             | 3.69 us                                                | 3.61 us: 1.02x faster                                          |
| bench_mp_pool              | 46.3 ms                                                | 45.3 ms: 1.02x faster                                          |
| logging_format             | 3.99 us                                                | 3.91 us: 1.02x faster                                          |
| regex_dna                  | 153 ms                                                 | 150 ms: 1.01x faster                                           |
| sympy_str                  | 151 ms                                                 | 150 ms: 1.01x faster                                           |
| regex_effbot               | 2.59 ms                                                | 2.58 ms: 1.01x faster                                          |
| python_startup             | 11.9 ms                                                | 11.9 ms: 1.00x faster                                          |
| pidigits                   | 282 ms                                                 | 283 ms: 1.00x slower                                           |
| pickle_dict                | 18.0 us                                                | 18.1 us: 1.00x slower                                          |
| create_gc_cycles           | 704 us                                                 | 708 us: 1.00x slower                                           |
| docutils                   | 1.54 sec                                               | 1.55 sec: 1.01x slower                                         |
| scimark_monte_carlo        | 50.1 ms                                                | 50.5 ms: 1.01x slower                                          |
| asyncio_websockets         | 545 ms                                                 | 550 ms: 1.01x slower                                           |
| chaos                      | 44.8 ms                                                | 45.2 ms: 1.01x slower                                          |
| unpickle                   | 9.25 us                                                | 9.35 us: 1.01x slower                                          |
| spectral_norm              | 74.6 ms                                                | 75.5 ms: 1.01x slower                                          |
| pickle                     | 7.42 us                                                | 7.51 us: 1.01x slower                                          |
| json_loads                 | 17.6 us                                                | 17.9 us: 1.01x slower                                          |
| gc_traversal               | 2.40 ms                                                | 2.43 ms: 1.01x slower                                          |
| deltablue                  | 2.58 ms                                                | 2.62 ms: 1.01x slower                                          |
| json                       | 3.02 ms                                                | 3.09 ms: 1.02x slower                                          |
| unpack_sequence            | 28.4 ns                                                | 29.1 ns: 1.02x slower                                          |
| sqlglot_normalize          | 188 ms                                                 | 193 ms: 1.02x slower                                           |
| sympy_expand               | 249 ms                                                 | 255 ms: 1.02x slower                                           |
| async_tree_cpu_io_mixed    | 525 ms                                                 | 539 ms: 1.03x slower                                           |
| dulwich_log                | 30.4 ms                                                | 31.3 ms: 1.03x slower                                          |
| float                      | 58.1 ms                                                | 60.0 ms: 1.03x slower                                          |
| mdp                        | 1.66 sec                                               | 1.72 sec: 1.03x slower                                         |
| async_tree_cpu_io_mixed_tg | 535 ms                                                 | 553 ms: 1.03x slower                                           |
| dask                       | 228 ms                                                 | 235 ms: 1.03x slower                                           |
| sqlite_synth               | 1.59 us                                                | 1.64 us: 1.03x slower                                          |
| coroutines                 | 18.1 ms                                                | 18.8 ms: 1.04x slower                                          |
| json_dumps                 | 6.46 ms                                                | 6.69 ms: 1.04x slower                                          |
| sqlglot_optimize           | 34.7 ms                                                | 35.9 ms: 1.04x slower                                          |
| asyncio_tcp_ssl            | 1.26 sec                                               | 1.30 sec: 1.04x slower                                         |
| sympy_integrate            | 11.3 ms                                                | 11.8 ms: 1.04x slower                                          |
| async_tree_io_tg           | 673 ms                                                 | 700 ms: 1.04x slower                                           |
| unpickle_list              | 3.24 us                                                | 3.37 us: 1.04x slower                                          |
| deepcopy                   | 225 us                                                 | 234 us: 1.04x slower                                           |
| async_generators           | 306 ms                                                 | 321 ms: 1.05x slower                                           |
| bench_thread_pool          | 492 us                                                 | 519 us: 1.05x slower                                           |
| mako                       | 7.53 ms                                                | 7.96 ms: 1.06x slower                                          |
| scimark_sparse_mat_mult    | 3.14 ms                                                | 3.33 ms: 1.06x slower                                          |
| richards_super             | 34.9 ms                                                | 37.1 ms: 1.06x slower                                          |
| pyflate                    | 329 ms                                                 | 352 ms: 1.07x slower                                           |
| async_tree_memoization_tg  | 320 ms                                                 | 342 ms: 1.07x slower                                           |
| deepcopy_memo              | 24.6 us                                                | 26.3 us: 1.07x slower                                          |
| pycparser                  | 670 ms                                                 | 719 ms: 1.07x slower                                           |
| 2to3                       | 171 ms                                                 | 183 ms: 1.07x slower                                           |
| python_startup_no_site     | 9.71 ms                                                | 10.4 ms: 1.08x slower                                          |
| meteor_contest             | 73.3 ms                                                | 79.0 ms: 1.08x slower                                          |
| go                         | 107 ms                                                 | 115 ms: 1.08x slower                                           |
| tornado_http               | 70.7 ms                                                | 76.3 ms: 1.08x slower                                          |
| richards                   | 31.1 ms                                                | 33.6 ms: 1.08x slower                                          |
| async_tree_none_tg         | 254 ms                                                 | 275 ms: 1.08x slower                                           |
| scimark_lu                 | 71.5 ms                                                | 77.4 ms: 1.08x slower                                          |
| regex_v8                   | 15.7 ms                                                | 17.0 ms: 1.09x slower                                          |
| async_tree_io              | 669 ms                                                 | 729 ms: 1.09x slower                                           |
| nqueens                    | 60.2 ms                                                | 65.6 ms: 1.09x slower                                          |
| chameleon                  | 4.51 ms                                                | 4.92 ms: 1.09x slower                                          |
| pickle_pure_python         | 188 us                                                 | 206 us: 1.09x slower                                           |
| async_tree_memoization     | 309 ms                                                 | 338 ms: 1.09x slower                                           |
| logging_silent             | 68.3 ns                                                | 74.9 ns: 1.10x slower                                          |
| pprint_pformat             | 1.00 sec                                               | 1.10 sec: 1.10x slower                                         |
| regex_compile              | 75.6 ms                                                | 83.2 ms: 1.10x slower                                          |
| tomli_loads                | 1.39 sec                                               | 1.53 sec: 1.10x slower                                         |
| pprint_safe_repr           | 491 ms                                                 | 542 ms: 1.10x slower                                           |
| scimark_fft                | 198 ms                                                 | 220 ms: 1.11x slower                                           |
| xml_etree_generate         | 55.9 ms                                                | 62.5 ms: 1.12x slower                                          |
| scimark_sor                | 94.3 ms                                                | 108 ms: 1.14x slower                                           |
| xml_etree_process          | 38.7 ms                                                | 44.5 ms: 1.15x slower                                          |
| fannkuch                   | 265 ms                                                 | 311 ms: 1.18x slower                                           |
| xml_etree_iterparse        | 74.6 ms                                                | 88.5 ms: 1.19x slower                                          |
| nbody                      | 68.5 ms                                                | 83.5 ms: 1.22x slower                                          |
| unpickle_pure_python       | 145 us                                                 | 179 us: 1.24x slower                                           |
| telco                      | 3.79 ms                                                | 4.79 ms: 1.26x slower                                          |
| coverage                   | 37.9 ms                                                | 48.7 ms: 1.28x slower                                          |
| xml_etree_parse            | 109 ms                                                 | 140 ms: 1.29x slower                                           |
| hexiom                     | 4.25 ms                                                | 5.89 ms: 1.39x slower                                          |
| Geometric mean             | (ref)                                                  | 1.05x slower                                                   |

Benchmark hidden because not significant (6): asyncio_tcp, async_tree_none, deepcopy_reduce, pathlib, pickle_list, mypy2
Ignored benchmarks (5) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.03x
- 95% likely to have a slowdown of 1.03x
- 99% likely to have a slowdown of 1.02x
