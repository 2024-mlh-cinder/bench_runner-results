
# Results vs. 3.12.0

- fork: python
- ref: main
- machine: darwin-arm64
- commit hash: 66bea25
- commit date: 2023-10-29
- overall geometric mean: 1.01x faster
- HPT reliability: 63.55%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231029-darwin-arm64-python-main-3.13.0a1+-66bea25 |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| 2to3           | 171 ms                                                 | 170 ms: 1.01x faster                                   |
| chameleon      | 4.51 ms                                                | 4.64 ms: 1.03x slower                                  |
| docutils       | 1.54 sec                                               | 1.49 sec: 1.04x faster                                 |
| Geometric mean | (ref)                                                  | 1.01x faster                                           |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231029-darwin-arm64-python-main-3.13.0a1+-66bea25 |
|----------------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| async_tree_none            | 262 ms                                                 | 249 ms: 1.05x faster                                   |
| async_tree_io_tg           | 673 ms                                                 | 677 ms: 1.01x slower                                   |
| async_tree_cpu_io_mixed_tg | 535 ms                                                 | 541 ms: 1.01x slower                                   |
| async_tree_memoization_tg  | 320 ms                                                 | 328 ms: 1.03x slower                                   |
| async_tree_io              | 669 ms                                                 | 693 ms: 1.04x slower                                   |
| async_tree_none_tg         | 254 ms                                                 | 264 ms: 1.04x slower                                   |
| async_tree_memoization     | 309 ms                                                 | 326 ms: 1.05x slower                                   |
| Geometric mean             | (ref)                                                  | 1.01x slower                                           |

Benchmark hidden because not significant (1): async_tree_cpu_io_mixed

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231029-darwin-arm64-python-main-3.13.0a1+-66bea25 |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| float          | 58.1 ms                                                | 54.7 ms: 1.06x faster                                  |
| pidigits       | 282 ms                                                 | 283 ms: 1.00x slower                                   |
| nbody          | 68.5 ms                                                | 70.8 ms: 1.03x slower                                  |
| Geometric mean | (ref)                                                  | 1.01x faster                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231029-darwin-arm64-python-main-3.13.0a1+-66bea25 |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| regex_dna      | 153 ms                                                 | 149 ms: 1.03x faster                                   |
| regex_effbot   | 2.59 ms                                                | 2.58 ms: 1.00x faster                                  |
| regex_compile  | 75.6 ms                                                | 75.7 ms: 1.00x slower                                  |
| regex_v8       | 15.7 ms                                                | 16.8 ms: 1.07x slower                                  |
| Geometric mean | (ref)                                                  | 1.01x slower                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231029-darwin-arm64-python-main-3.13.0a1+-66bea25 |
|----------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| unpickle_list        | 3.24 us                                                | 3.16 us: 1.02x faster                                  |
| json_loads           | 17.6 us                                                | 17.4 us: 1.01x faster                                  |
| unpickle             | 9.25 us                                                | 9.20 us: 1.01x faster                                  |
| pickle_dict          | 18.0 us                                                | 18.0 us: 1.00x slower                                  |
| pickle               | 7.42 us                                                | 7.48 us: 1.01x slower                                  |
| xml_etree_process    | 38.7 ms                                                | 39.3 ms: 1.02x slower                                  |
| xml_etree_parse      | 109 ms                                                 | 111 ms: 1.02x slower                                   |
| xml_etree_iterparse  | 74.6 ms                                                | 76.4 ms: 1.02x slower                                  |
| xml_etree_generate   | 55.9 ms                                                | 57.3 ms: 1.03x slower                                  |
| pickle_pure_python   | 188 us                                                 | 193 us: 1.03x slower                                   |
| unpickle_pure_python | 145 us                                                 | 157 us: 1.08x slower                                   |
| tomli_loads          | 1.39 sec                                               | 1.53 sec: 1.10x slower                                 |
| Geometric mean       | (ref)                                                  | 1.02x slower                                           |

Benchmark hidden because not significant (2): pickle_list, json_dumps

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231029-darwin-arm64-python-main-3.13.0a1+-66bea25 |
|------------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| python_startup         | 11.9 ms                                                | 12.5 ms: 1.05x slower                                  |
| python_startup_no_site | 9.71 ms                                                | 11.0 ms: 1.13x slower                                  |
| Geometric mean         | (ref)                                                  | 1.09x slower                                           |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231029-darwin-arm64-python-main-3.13.0a1+-66bea25 |
|-----------|:------------------------------------------------------:|:------------------------------------------------------:|
| mako      | 7.53 ms                                                | 7.34 ms: 1.03x faster                                  |

All benchmarks:
===============

| Benchmark                  | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231029-darwin-arm64-python-main-3.13.0a1+-66bea25 |
|----------------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| raytrace                   | 246 ms                                                 | 172 ms: 1.43x faster                                   |
| comprehensions             | 15.8 us                                                | 11.5 us: 1.37x faster                                  |
| generators                 | 28.3 ms                                                | 24.9 ms: 1.14x faster                                  |
| sqlglot_parse              | 897 us                                                 | 789 us: 1.14x faster                                   |
| chaos                      | 44.8 ms                                                | 39.9 ms: 1.12x faster                                  |
| sqlglot_transpile          | 1.08 ms                                                | 965 us: 1.12x faster                                   |
| deltablue                  | 2.58 ms                                                | 2.32 ms: 1.11x faster                                  |
| crypto_pyaes               | 52.0 ms                                                | 46.7 ms: 1.11x faster                                  |
| scimark_monte_carlo        | 50.1 ms                                                | 45.1 ms: 1.11x faster                                  |
| sympy_sum                  | 79.5 ms                                                | 73.4 ms: 1.08x faster                                  |
| sympy_str                  | 151 ms                                                 | 141 ms: 1.07x faster                                   |
| unpack_sequence            | 28.4 ns                                                | 26.5 ns: 1.07x faster                                  |
| float                      | 58.1 ms                                                | 54.7 ms: 1.06x faster                                  |
| spectral_norm              | 74.6 ms                                                | 70.4 ms: 1.06x faster                                  |
| async_tree_none            | 262 ms                                                 | 249 ms: 1.05x faster                                   |
| nqueens                    | 60.2 ms                                                | 57.4 ms: 1.05x faster                                  |
| sympy_integrate            | 11.3 ms                                                | 10.8 ms: 1.05x faster                                  |
| go                         | 107 ms                                                 | 103 ms: 1.04x faster                                   |
| logging_simple             | 3.69 us                                                | 3.56 us: 1.04x faster                                  |
| docutils                   | 1.54 sec                                               | 1.49 sec: 1.04x faster                                 |
| mdp                        | 1.66 sec                                               | 1.61 sec: 1.03x faster                                 |
| coroutines                 | 18.1 ms                                                | 17.6 ms: 1.03x faster                                  |
| logging_format             | 3.99 us                                                | 3.87 us: 1.03x faster                                  |
| bench_thread_pool          | 492 us                                                 | 478 us: 1.03x faster                                   |
| sympy_expand               | 249 ms                                                 | 242 ms: 1.03x faster                                   |
| sqlglot_normalize          | 188 ms                                                 | 183 ms: 1.03x faster                                   |
| regex_dna                  | 153 ms                                                 | 149 ms: 1.03x faster                                   |
| logging_silent             | 68.3 ns                                                | 66.6 ns: 1.03x faster                                  |
| bench_mp_pool              | 46.3 ms                                                | 45.1 ms: 1.03x faster                                  |
| scimark_sparse_mat_mult    | 3.14 ms                                                | 3.07 ms: 1.03x faster                                  |
| mako                       | 7.53 ms                                                | 7.34 ms: 1.03x faster                                  |
| unpickle_list              | 3.24 us                                                | 3.16 us: 1.02x faster                                  |
| sqlglot_optimize           | 34.7 ms                                                | 33.9 ms: 1.02x faster                                  |
| deepcopy_memo              | 24.6 us                                                | 24.1 us: 1.02x faster                                  |
| async_generators           | 306 ms                                                 | 300 ms: 1.02x faster                                   |
| deepcopy_reduce            | 2.05 us                                                | 2.01 us: 1.02x faster                                  |
| scimark_lu                 | 71.5 ms                                                | 70.4 ms: 1.01x faster                                  |
| json                       | 3.02 ms                                                | 2.98 ms: 1.01x faster                                  |
| json_loads                 | 17.6 us                                                | 17.4 us: 1.01x faster                                  |
| deepcopy                   | 225 us                                                 | 223 us: 1.01x faster                                   |
| unpickle                   | 9.25 us                                                | 9.20 us: 1.01x faster                                  |
| 2to3                       | 171 ms                                                 | 170 ms: 1.01x faster                                   |
| regex_effbot               | 2.59 ms                                                | 2.58 ms: 1.00x faster                                  |
| create_gc_cycles           | 704 us                                                 | 701 us: 1.00x faster                                   |
| scimark_fft                | 198 ms                                                 | 197 ms: 1.00x faster                                   |
| regex_compile              | 75.6 ms                                                | 75.7 ms: 1.00x slower                                  |
| pidigits                   | 282 ms                                                 | 283 ms: 1.00x slower                                   |
| pickle_dict                | 18.0 us                                                | 18.0 us: 1.00x slower                                  |
| async_tree_io_tg           | 673 ms                                                 | 677 ms: 1.01x slower                                   |
| pickle                     | 7.42 us                                                | 7.48 us: 1.01x slower                                  |
| pprint_pformat             | 1.00 sec                                               | 1.01 sec: 1.01x slower                                 |
| typing_runtime_protocols   | 90.8 us                                                | 91.6 us: 1.01x slower                                  |
| meteor_contest             | 73.3 ms                                                | 74.2 ms: 1.01x slower                                  |
| async_tree_cpu_io_mixed_tg | 535 ms                                                 | 541 ms: 1.01x slower                                   |
| xml_etree_process          | 38.7 ms                                                | 39.3 ms: 1.02x slower                                  |
| xml_etree_parse            | 109 ms                                                 | 111 ms: 1.02x slower                                   |
| pyflate                    | 329 ms                                                 | 334 ms: 1.02x slower                                   |
| pprint_safe_repr           | 491 ms                                                 | 499 ms: 1.02x slower                                   |
| sqlite_synth               | 1.59 us                                                | 1.63 us: 1.02x slower                                  |
| xml_etree_iterparse        | 74.6 ms                                                | 76.4 ms: 1.02x slower                                  |
| xml_etree_generate         | 55.9 ms                                                | 57.3 ms: 1.03x slower                                  |
| pickle_pure_python         | 188 us                                                 | 193 us: 1.03x slower                                   |
| async_tree_memoization_tg  | 320 ms                                                 | 328 ms: 1.03x slower                                   |
| pycparser                  | 670 ms                                                 | 689 ms: 1.03x slower                                   |
| chameleon                  | 4.51 ms                                                | 4.64 ms: 1.03x slower                                  |
| asyncio_tcp_ssl            | 1.26 sec                                               | 1.29 sec: 1.03x slower                                 |
| nbody                      | 68.5 ms                                                | 70.8 ms: 1.03x slower                                  |
| async_tree_io              | 669 ms                                                 | 693 ms: 1.04x slower                                   |
| async_tree_none_tg         | 254 ms                                                 | 264 ms: 1.04x slower                                   |
| richards_super             | 34.9 ms                                                | 36.3 ms: 1.04x slower                                  |
| python_startup             | 11.9 ms                                                | 12.5 ms: 1.05x slower                                  |
| async_tree_memoization     | 309 ms                                                 | 326 ms: 1.05x slower                                   |
| richards                   | 31.1 ms                                                | 33.0 ms: 1.06x slower                                  |
| fannkuch                   | 265 ms                                                 | 283 ms: 1.07x slower                                   |
| regex_v8                   | 15.7 ms                                                | 16.8 ms: 1.07x slower                                  |
| hexiom                     | 4.25 ms                                                | 4.59 ms: 1.08x slower                                  |
| unpickle_pure_python       | 145 us                                                 | 157 us: 1.08x slower                                   |
| scimark_sor                | 94.3 ms                                                | 103 ms: 1.10x slower                                   |
| tomli_loads                | 1.39 sec                                               | 1.53 sec: 1.10x slower                                 |
| python_startup_no_site     | 9.71 ms                                                | 11.0 ms: 1.13x slower                                  |
| telco                      | 3.79 ms                                                | 4.61 ms: 1.22x slower                                  |
| coverage                   | 37.9 ms                                                | 46.6 ms: 1.23x slower                                  |
| Geometric mean             | (ref)                                                  | 1.01x faster                                           |

Benchmark hidden because not significant (10): asyncio_tcp, tornado_http, mypy2, async_tree_cpu_io_mixed, pickle_list, json_dumps, asyncio_websockets, dulwich_log, gc_traversal, pathlib
Ignored benchmarks (6) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, dask, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 63.55% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
