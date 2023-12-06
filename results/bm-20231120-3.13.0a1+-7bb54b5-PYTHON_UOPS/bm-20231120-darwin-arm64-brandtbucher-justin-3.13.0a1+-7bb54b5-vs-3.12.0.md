
# Results vs. 3.12.0

- fork: brandtbucher
- ref: justin
- machine: darwin-arm64
- commit hash: 7bb54b5
- commit date: 2023-11-20
- overall geometric mean: 1.03x slower \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.02x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-darwin-arm64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| 2to3           | 171 ms                                                 | 181 ms: 1.06x slower                                           |
| chameleon      | 4.51 ms                                                | 4.88 ms: 1.08x slower                                          |
| docutils       | 1.54 sec                                               | 1.53 sec: 1.01x faster                                         |
| tornado_http   | 70.7 ms                                                | 74.1 ms: 1.05x slower                                          |
| Geometric mean | (ref)                                                  | 1.04x slower                                                   |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-darwin-arm64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|----------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| async_tree_none            | 262 ms                                                 | 257 ms: 1.02x faster                                           |
| async_tree_cpu_io_mixed_tg | 535 ms                                                 | 545 ms: 1.02x slower                                           |
| async_tree_io_tg           | 673 ms                                                 | 689 ms: 1.02x slower                                           |
| async_tree_memoization_tg  | 320 ms                                                 | 337 ms: 1.05x slower                                           |
| async_tree_io              | 669 ms                                                 | 707 ms: 1.06x slower                                           |
| async_tree_none_tg         | 254 ms                                                 | 270 ms: 1.06x slower                                           |
| async_tree_memoization     | 309 ms                                                 | 332 ms: 1.07x slower                                           |
| Geometric mean             | (ref)                                                  | 1.03x slower                                                   |

Benchmark hidden because not significant (1): async_tree_cpu_io_mixed

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-darwin-arm64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| pidigits       | 282 ms                                                 | 282 ms: 1.00x faster                                           |
| float          | 58.1 ms                                                | 58.3 ms: 1.00x slower                                          |
| nbody          | 68.5 ms                                                | 81.7 ms: 1.19x slower                                          |
| Geometric mean | (ref)                                                  | 1.06x slower                                                   |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-darwin-arm64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| regex_dna      | 153 ms                                                 | 149 ms: 1.03x faster                                           |
| regex_effbot   | 2.59 ms                                                | 2.56 ms: 1.01x faster                                          |
| regex_v8       | 15.7 ms                                                | 17.0 ms: 1.09x slower                                          |
| regex_compile  | 75.6 ms                                                | 83.5 ms: 1.10x slower                                          |
| Geometric mean | (ref)                                                  | 1.04x slower                                                   |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-darwin-arm64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|----------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| unpickle_list        | 3.24 us                                                | 3.11 us: 1.04x faster                                          |
| unpickle             | 9.25 us                                                | 9.04 us: 1.02x faster                                          |
| json_loads           | 17.6 us                                                | 17.3 us: 1.02x faster                                          |
| pickle_dict          | 18.0 us                                                | 17.9 us: 1.01x faster                                          |
| pickle               | 7.42 us                                                | 7.47 us: 1.01x slower                                          |
| json_dumps           | 6.46 ms                                                | 6.55 ms: 1.01x slower                                          |
| pickle_list          | 2.89 us                                                | 2.96 us: 1.02x slower                                          |
| xml_etree_iterparse  | 74.6 ms                                                | 76.8 ms: 1.03x slower                                          |
| xml_etree_generate   | 55.9 ms                                                | 58.4 ms: 1.04x slower                                          |
| xml_etree_process    | 38.7 ms                                                | 40.9 ms: 1.06x slower                                          |
| pickle_pure_python   | 188 us                                                 | 204 us: 1.08x slower                                           |
| tomli_loads          | 1.39 sec                                               | 1.51 sec: 1.09x slower                                         |
| unpickle_pure_python | 145 us                                                 | 165 us: 1.14x slower                                           |
| Geometric mean       | (ref)                                                  | 1.03x slower                                                   |

Benchmark hidden because not significant (1): xml_etree_parse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-darwin-arm64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| python_startup         | 11.9 ms                                                | 12.3 ms: 1.04x slower                                          |
| python_startup_no_site | 9.71 ms                                                | 10.9 ms: 1.12x slower                                          |
| Geometric mean         | (ref)                                                  | 1.08x slower                                                   |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-darwin-arm64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|-----------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| mako      | 7.53 ms                                                | 7.96 ms: 1.06x slower                                          |

All benchmarks:
===============

| Benchmark                  | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-darwin-arm64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|----------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| asyncio_websockets         | 545 ms                                                 | 408 ms: 1.34x faster                                           |
| raytrace                   | 246 ms                                                 | 194 ms: 1.27x faster                                           |
| pathlib                    | 29.3 ms                                                | 24.2 ms: 1.21x faster                                          |
| typing_runtime_protocols   | 90.8 us                                                | 77.4 us: 1.17x faster                                          |
| comprehensions             | 15.8 us                                                | 13.9 us: 1.13x faster                                          |
| generators                 | 28.3 ms                                                | 25.6 ms: 1.11x faster                                          |
| asyncio_tcp                | 450 ms                                                 | 408 ms: 1.10x faster                                           |
| unpickle_list              | 3.24 us                                                | 3.11 us: 1.04x faster                                          |
| crypto_pyaes               | 52.0 ms                                                | 50.0 ms: 1.04x faster                                          |
| sqlglot_parse              | 897 us                                                 | 867 us: 1.03x faster                                           |
| regex_dna                  | 153 ms                                                 | 149 ms: 1.03x faster                                           |
| sqlglot_transpile          | 1.08 ms                                                | 1.05 ms: 1.02x faster                                          |
| logging_simple             | 3.69 us                                                | 3.61 us: 1.02x faster                                          |
| unpickle                   | 9.25 us                                                | 9.04 us: 1.02x faster                                          |
| async_tree_none            | 262 ms                                                 | 257 ms: 1.02x faster                                           |
| json_loads                 | 17.6 us                                                | 17.3 us: 1.02x faster                                          |
| logging_format             | 3.99 us                                                | 3.92 us: 1.02x faster                                          |
| regex_effbot               | 2.59 ms                                                | 2.56 ms: 1.01x faster                                          |
| docutils                   | 1.54 sec                                               | 1.53 sec: 1.01x faster                                         |
| pickle_dict                | 18.0 us                                                | 17.9 us: 1.01x faster                                          |
| create_gc_cycles           | 704 us                                                 | 700 us: 1.01x faster                                           |
| deltablue                  | 2.58 ms                                                | 2.57 ms: 1.00x faster                                          |
| gc_traversal               | 2.40 ms                                                | 2.40 ms: 1.00x faster                                          |
| pidigits                   | 282 ms                                                 | 282 ms: 1.00x faster                                           |
| scimark_monte_carlo        | 50.1 ms                                                | 50.1 ms: 1.00x slower                                          |
| float                      | 58.1 ms                                                | 58.3 ms: 1.00x slower                                          |
| chaos                      | 44.8 ms                                                | 45.0 ms: 1.01x slower                                          |
| pickle                     | 7.42 us                                                | 7.47 us: 1.01x slower                                          |
| deepcopy_reduce            | 2.05 us                                                | 2.06 us: 1.01x slower                                          |
| sympy_str                  | 151 ms                                                 | 153 ms: 1.01x slower                                           |
| json_dumps                 | 6.46 ms                                                | 6.55 ms: 1.01x slower                                          |
| dask                       | 228 ms                                                 | 231 ms: 1.01x slower                                           |
| sympy_sum                  | 79.5 ms                                                | 80.7 ms: 1.01x slower                                          |
| async_tree_cpu_io_mixed_tg | 535 ms                                                 | 545 ms: 1.02x slower                                           |
| pickle_list                | 2.89 us                                                | 2.96 us: 1.02x slower                                          |
| async_tree_io_tg           | 673 ms                                                 | 689 ms: 1.02x slower                                           |
| coroutines                 | 18.1 ms                                                | 18.6 ms: 1.03x slower                                          |
| mdp                        | 1.66 sec                                               | 1.71 sec: 1.03x slower                                         |
| xml_etree_iterparse        | 74.6 ms                                                | 76.8 ms: 1.03x slower                                          |
| deepcopy                   | 225 us                                                 | 232 us: 1.03x slower                                           |
| python_startup             | 11.9 ms                                                | 12.3 ms: 1.04x slower                                          |
| asyncio_tcp_ssl            | 1.26 sec                                               | 1.30 sec: 1.04x slower                                         |
| sqlite_synth               | 1.59 us                                                | 1.65 us: 1.04x slower                                          |
| async_generators           | 306 ms                                                 | 318 ms: 1.04x slower                                           |
| sympy_expand               | 249 ms                                                 | 260 ms: 1.04x slower                                           |
| sqlglot_normalize          | 188 ms                                                 | 196 ms: 1.04x slower                                           |
| xml_etree_generate         | 55.9 ms                                                | 58.4 ms: 1.04x slower                                          |
| tornado_http               | 70.7 ms                                                | 74.1 ms: 1.05x slower                                          |
| scimark_sparse_mat_mult    | 3.14 ms                                                | 3.31 ms: 1.05x slower                                          |
| async_tree_memoization_tg  | 320 ms                                                 | 337 ms: 1.05x slower                                           |
| async_tree_io              | 669 ms                                                 | 707 ms: 1.06x slower                                           |
| sympy_integrate            | 11.3 ms                                                | 12.0 ms: 1.06x slower                                          |
| mako                       | 7.53 ms                                                | 7.96 ms: 1.06x slower                                          |
| xml_etree_process          | 38.7 ms                                                | 40.9 ms: 1.06x slower                                          |
| go                         | 107 ms                                                 | 113 ms: 1.06x slower                                           |
| async_tree_none_tg         | 254 ms                                                 | 270 ms: 1.06x slower                                           |
| 2to3                       | 171 ms                                                 | 181 ms: 1.06x slower                                           |
| sqlglot_optimize           | 34.7 ms                                                | 36.8 ms: 1.06x slower                                          |
| richards_super             | 34.9 ms                                                | 37.1 ms: 1.06x slower                                          |
| pyflate                    | 329 ms                                                 | 350 ms: 1.06x slower                                           |
| deepcopy_memo              | 24.6 us                                                | 26.2 us: 1.07x slower                                          |
| pycparser                  | 670 ms                                                 | 717 ms: 1.07x slower                                           |
| async_tree_memoization     | 309 ms                                                 | 332 ms: 1.07x slower                                           |
| richards                   | 31.1 ms                                                | 33.4 ms: 1.07x slower                                          |
| bench_thread_pool          | 492 us                                                 | 529 us: 1.08x slower                                           |
| logging_silent             | 68.3 ns                                                | 73.6 ns: 1.08x slower                                          |
| meteor_contest             | 73.3 ms                                                | 79.1 ms: 1.08x slower                                          |
| chameleon                  | 4.51 ms                                                | 4.88 ms: 1.08x slower                                          |
| pickle_pure_python         | 188 us                                                 | 204 us: 1.08x slower                                           |
| regex_v8                   | 15.7 ms                                                | 17.0 ms: 1.09x slower                                          |
| scimark_lu                 | 71.5 ms                                                | 77.6 ms: 1.09x slower                                          |
| tomli_loads                | 1.39 sec                                               | 1.51 sec: 1.09x slower                                         |
| spectral_norm              | 74.6 ms                                                | 81.4 ms: 1.09x slower                                          |
| nqueens                    | 60.2 ms                                                | 65.8 ms: 1.09x slower                                          |
| pprint_safe_repr           | 491 ms                                                 | 537 ms: 1.09x slower                                           |
| pprint_pformat             | 1.00 sec                                               | 1.10 sec: 1.10x slower                                         |
| regex_compile              | 75.6 ms                                                | 83.5 ms: 1.10x slower                                          |
| python_startup_no_site     | 9.71 ms                                                | 10.9 ms: 1.12x slower                                          |
| scimark_fft                | 198 ms                                                 | 223 ms: 1.13x slower                                           |
| fannkuch                   | 265 ms                                                 | 299 ms: 1.13x slower                                           |
| scimark_sor                | 94.3 ms                                                | 108 ms: 1.14x slower                                           |
| unpickle_pure_python       | 145 us                                                 | 165 us: 1.14x slower                                           |
| nbody                      | 68.5 ms                                                | 81.7 ms: 1.19x slower                                          |
| telco                      | 3.79 ms                                                | 4.65 ms: 1.23x slower                                          |
| coverage                   | 37.9 ms                                                | 48.7 ms: 1.28x slower                                          |
| hexiom                     | 4.25 ms                                                | 5.77 ms: 1.36x slower                                          |
| Geometric mean             | (ref)                                                  | 1.03x slower                                                   |

Benchmark hidden because not significant (7): xml_etree_parse, json, dulwich_log, bench_mp_pool, unpack_sequence, async_tree_cpu_io_mixed, mypy2
Ignored benchmarks (5) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.02x
- 95% likely to have a slowdown of 1.02x
- 99% likely to have a slowdown of 1.02x
