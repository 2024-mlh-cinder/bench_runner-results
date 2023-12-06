
# Results vs. 3.11.0

- fork: python
- ref: main
- machine: darwin-arm64
- commit hash: 66bea25
- commit date: 2023-10-29
- overall geometric mean: 1.00x slower
- HPT reliability: 91.89%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231029-darwin-arm64-python-main-3.13.0a1+-66bea25 |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| 2to3           | 155 ms                                                 | 170 ms: 1.09x slower                                   |
| chameleon      | 4.17 ms                                                | 4.64 ms: 1.11x slower                                  |
| docutils       | 1.46 sec                                               | 1.49 sec: 1.02x slower                                 |
| Geometric mean | (ref)                                                  | 1.05x slower                                           |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231029-darwin-arm64-python-main-3.13.0a1+-66bea25 |
|----------------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| async_tree_none            | 282 ms                                                 | 249 ms: 1.13x faster                                   |
| async_tree_memoization     | 361 ms                                                 | 326 ms: 1.11x faster                                   |
| async_tree_memoization_tg  | 357 ms                                                 | 328 ms: 1.09x faster                                   |
| async_tree_io_tg           | 734 ms                                                 | 677 ms: 1.08x faster                                   |
| async_tree_none_tg         | 280 ms                                                 | 264 ms: 1.06x faster                                   |
| async_tree_cpu_io_mixed_tg | 554 ms                                                 | 541 ms: 1.02x faster                                   |
| async_tree_io              | 705 ms                                                 | 693 ms: 1.02x faster                                   |
| Geometric mean             | (ref)                                                  | 1.06x faster                                           |

Benchmark hidden because not significant (1): async_tree_cpu_io_mixed

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231029-darwin-arm64-python-main-3.13.0a1+-66bea25 |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| float          | 55.4 ms                                                | 54.7 ms: 1.01x faster                                  |
| pidigits       | 281 ms                                                 | 283 ms: 1.01x slower                                   |
| nbody          | 68.7 ms                                                | 70.8 ms: 1.03x slower                                  |
| Geometric mean | (ref)                                                  | 1.01x slower                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231029-darwin-arm64-python-main-3.13.0a1+-66bea25 |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| regex_dna      | 149 ms                                                 | 149 ms: 1.00x faster                                   |
| regex_compile  | 73.9 ms                                                | 75.7 ms: 1.02x slower                                  |
| regex_effbot   | 2.46 ms                                                | 2.58 ms: 1.05x slower                                  |
| regex_v8       | 15.3 ms                                                | 16.8 ms: 1.10x slower                                  |
| Geometric mean | (ref)                                                  | 1.04x slower                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231029-darwin-arm64-python-main-3.13.0a1+-66bea25 |
|----------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| json_dumps           | 7.58 ms                                                | 6.46 ms: 1.17x faster                                  |
| pickle_pure_python   | 211 us                                                 | 193 us: 1.09x faster                                   |
| unpickle_pure_python | 163 us                                                 | 157 us: 1.04x faster                                   |
| xml_etree_parse      | 107 ms                                                 | 111 ms: 1.03x slower                                   |
| pickle               | 7.22 us                                                | 7.48 us: 1.04x slower                                  |
| pickle_dict          | 17.0 us                                                | 18.0 us: 1.06x slower                                  |
| pickle_list          | 2.67 us                                                | 2.89 us: 1.08x slower                                  |
| unpickle             | 8.32 us                                                | 9.20 us: 1.11x slower                                  |
| json_loads           | 15.8 us                                                | 17.4 us: 1.11x slower                                  |
| xml_etree_iterparse  | 68.2 ms                                                | 76.4 ms: 1.12x slower                                  |
| unpickle_list        | 2.77 us                                                | 3.16 us: 1.14x slower                                  |
| xml_etree_process    | 34.0 ms                                                | 39.3 ms: 1.15x slower                                  |
| tomli_loads          | 1.30 sec                                               | 1.53 sec: 1.17x slower                                 |
| xml_etree_generate   | 46.8 ms                                                | 57.3 ms: 1.22x slower                                  |
| Geometric mean       | (ref)                                                  | 1.06x slower                                           |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231029-darwin-arm64-python-main-3.13.0a1+-66bea25 |
|------------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| python_startup         | 11.4 ms                                                | 12.5 ms: 1.10x slower                                  |
| python_startup_no_site | 9.15 ms                                                | 11.0 ms: 1.20x slower                                  |
| Geometric mean         | (ref)                                                  | 1.15x slower                                           |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231029-darwin-arm64-python-main-3.13.0a1+-66bea25 |
|-----------|:------------------------------------------------------:|:------------------------------------------------------:|
| mako      | 8.22 ms                                                | 7.34 ms: 1.12x faster                                  |

All benchmarks:
===============

| Benchmark                  | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231029-darwin-arm64-python-main-3.13.0a1+-66bea25 |
|----------------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| typing_runtime_protocols   | 323 us                                                 | 91.6 us: 3.52x faster                                  |
| asyncio_tcp                | 650 ms                                                 | 425 ms: 1.53x faster                                   |
| comprehensions             | 14.7 us                                                | 11.5 us: 1.28x faster                                  |
| unpack_sequence            | 32.3 ns                                                | 26.5 ns: 1.22x faster                                  |
| chaos                      | 48.2 ms                                                | 39.9 ms: 1.21x faster                                  |
| deepcopy_memo              | 28.9 us                                                | 24.1 us: 1.20x faster                                  |
| generators                 | 29.2 ms                                                | 24.9 ms: 1.17x faster                                  |
| json_dumps                 | 7.58 ms                                                | 6.46 ms: 1.17x faster                                  |
| raytrace                   | 200 ms                                                 | 172 ms: 1.16x faster                                   |
| deltablue                  | 2.70 ms                                                | 2.32 ms: 1.16x faster                                  |
| async_tree_none            | 282 ms                                                 | 249 ms: 1.13x faster                                   |
| sqlglot_parse              | 886 us                                                 | 789 us: 1.12x faster                                   |
| mako                       | 8.22 ms                                                | 7.34 ms: 1.12x faster                                  |
| asyncio_tcp_ssl            | 1.44 sec                                               | 1.29 sec: 1.11x faster                                 |
| sympy_sum                  | 81.6 ms                                                | 73.4 ms: 1.11x faster                                  |
| async_tree_memoization     | 361 ms                                                 | 326 ms: 1.11x faster                                   |
| pickle_pure_python         | 211 us                                                 | 193 us: 1.09x faster                                   |
| async_tree_memoization_tg  | 357 ms                                                 | 328 ms: 1.09x faster                                   |
| sqlglot_transpile          | 1.05 ms                                                | 965 us: 1.09x faster                                   |
| async_tree_io_tg           | 734 ms                                                 | 677 ms: 1.08x faster                                   |
| mdp                        | 1.73 sec                                               | 1.61 sec: 1.08x faster                                 |
| async_tree_none_tg         | 280 ms                                                 | 264 ms: 1.06x faster                                   |
| sympy_integrate            | 11.3 ms                                                | 10.8 ms: 1.05x faster                                  |
| deepcopy                   | 233 us                                                 | 223 us: 1.04x faster                                   |
| scimark_monte_carlo        | 47.1 ms                                                | 45.1 ms: 1.04x faster                                  |
| unpickle_pure_python       | 163 us                                                 | 157 us: 1.04x faster                                   |
| crypto_pyaes               | 48.1 ms                                                | 46.7 ms: 1.03x faster                                  |
| async_tree_cpu_io_mixed_tg | 554 ms                                                 | 541 ms: 1.02x faster                                   |
| sympy_str                  | 144 ms                                                 | 141 ms: 1.02x faster                                   |
| create_gc_cycles           | 715 us                                                 | 701 us: 1.02x faster                                   |
| async_tree_io              | 705 ms                                                 | 693 ms: 1.02x faster                                   |
| richards_super             | 36.8 ms                                                | 36.3 ms: 1.02x faster                                  |
| float                      | 55.4 ms                                                | 54.7 ms: 1.01x faster                                  |
| meteor_contest             | 74.9 ms                                                | 74.2 ms: 1.01x faster                                  |
| regex_dna                  | 149 ms                                                 | 149 ms: 1.00x faster                                   |
| asyncio_websockets         | 544 ms                                                 | 545 ms: 1.00x slower                                   |
| pidigits                   | 281 ms                                                 | 283 ms: 1.01x slower                                   |
| go                         | 102 ms                                                 | 103 ms: 1.01x slower                                   |
| gc_traversal               | 2.39 ms                                                | 2.40 ms: 1.01x slower                                  |
| hexiom                     | 4.55 ms                                                | 4.59 ms: 1.01x slower                                  |
| spectral_norm              | 69.7 ms                                                | 70.4 ms: 1.01x slower                                  |
| deepcopy_reduce            | 1.98 us                                                | 2.01 us: 1.01x slower                                  |
| dulwich_log                | 29.9 ms                                                | 30.4 ms: 1.02x slower                                  |
| scimark_sparse_mat_mult    | 3.01 ms                                                | 3.07 ms: 1.02x slower                                  |
| pprint_pformat             | 989 ms                                                 | 1.01 sec: 1.02x slower                                 |
| docutils                   | 1.46 sec                                               | 1.49 sec: 1.02x slower                                 |
| regex_compile              | 73.9 ms                                                | 75.7 ms: 1.02x slower                                  |
| nbody                      | 68.7 ms                                                | 70.8 ms: 1.03x slower                                  |
| logging_silent             | 64.5 ns                                                | 66.6 ns: 1.03x slower                                  |
| pycparser                  | 667 ms                                                 | 689 ms: 1.03x slower                                   |
| xml_etree_parse            | 107 ms                                                 | 111 ms: 1.03x slower                                   |
| pathlib                    | 28.5 ms                                                | 29.5 ms: 1.03x slower                                  |
| pickle                     | 7.22 us                                                | 7.48 us: 1.04x slower                                  |
| sympy_expand               | 234 ms                                                 | 242 ms: 1.04x slower                                   |
| bench_thread_pool          | 461 us                                                 | 478 us: 1.04x slower                                   |
| scimark_lu                 | 67.8 ms                                                | 70.4 ms: 1.04x slower                                  |
| pprint_safe_repr           | 479 ms                                                 | 499 ms: 1.04x slower                                   |
| logging_simple             | 3.41 us                                                | 3.56 us: 1.04x slower                                  |
| regex_effbot               | 2.46 ms                                                | 2.58 ms: 1.05x slower                                  |
| logging_format             | 3.69 us                                                | 3.87 us: 1.05x slower                                  |
| nqueens                    | 54.6 ms                                                | 57.4 ms: 1.05x slower                                  |
| scimark_fft                | 187 ms                                                 | 197 ms: 1.06x slower                                   |
| pickle_dict                | 17.0 us                                                | 18.0 us: 1.06x slower                                  |
| coroutines                 | 16.6 ms                                                | 17.6 ms: 1.06x slower                                  |
| richards                   | 30.8 ms                                                | 33.0 ms: 1.07x slower                                  |
| bench_mp_pool              | 41.9 ms                                                | 45.1 ms: 1.08x slower                                  |
| json                       | 2.77 ms                                                | 2.98 ms: 1.08x slower                                  |
| pickle_list                | 2.67 us                                                | 2.89 us: 1.08x slower                                  |
| 2to3                       | 155 ms                                                 | 170 ms: 1.09x slower                                   |
| regex_v8                   | 15.3 ms                                                | 16.8 ms: 1.10x slower                                  |
| python_startup             | 11.4 ms                                                | 12.5 ms: 1.10x slower                                  |
| unpickle                   | 8.32 us                                                | 9.20 us: 1.11x slower                                  |
| json_loads                 | 15.8 us                                                | 17.4 us: 1.11x slower                                  |
| chameleon                  | 4.17 ms                                                | 4.64 ms: 1.11x slower                                  |
| xml_etree_iterparse        | 68.2 ms                                                | 76.4 ms: 1.12x slower                                  |
| pyflate                    | 297 ms                                                 | 334 ms: 1.12x slower                                   |
| coverage                   | 41.4 ms                                                | 46.6 ms: 1.13x slower                                  |
| fannkuch                   | 247 ms                                                 | 283 ms: 1.14x slower                                   |
| unpickle_list              | 2.77 us                                                | 3.16 us: 1.14x slower                                  |
| sqlglot_normalize          | 160 ms                                                 | 183 ms: 1.14x slower                                   |
| sqlglot_optimize           | 29.6 ms                                                | 33.9 ms: 1.15x slower                                  |
| xml_etree_process          | 34.0 ms                                                | 39.3 ms: 1.15x slower                                  |
| tomli_loads                | 1.30 sec                                               | 1.53 sec: 1.17x slower                                 |
| python_startup_no_site     | 9.15 ms                                                | 11.0 ms: 1.20x slower                                  |
| sqlite_synth               | 1.35 us                                                | 1.63 us: 1.21x slower                                  |
| xml_etree_generate         | 46.8 ms                                                | 57.3 ms: 1.22x slower                                  |
| mypy2                      | 191 ms                                                 | 258 ms: 1.35x slower                                   |
| scimark_sor                | 75.2 ms                                                | 103 ms: 1.37x slower                                   |
| telco                      | 3.17 ms                                                | 4.61 ms: 1.46x slower                                  |
| async_generators           | 192 ms                                                 | 300 ms: 1.56x slower                                   |
| Geometric mean             | (ref)                                                  | 1.00x slower                                           |

Benchmark hidden because not significant (2): tornado_http, async_tree_cpu_io_mixed
Ignored benchmarks (12) of results/bm-20221024-3.11.0-deaf509/bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, dask, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift


# HPT report

- Reliability score: 91.89% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
