
# Results vs. 3.11.0

- fork: python
- ref: 05f2f0ac92afa560315e
- machine: darwin-arm64
- commit hash: 05f2f0a
- commit date: 2023-10-30
- overall geometric mean: 1.00x slower
- HPT reliability: 92.79%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231030-darwin-arm64-python-05f2f0ac92afa560315e-3.13.0a1+-05f2f0a |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| 2to3           | 155 ms                                                 | 170 ms: 1.09x slower                                                   |
| chameleon      | 4.17 ms                                                | 4.63 ms: 1.11x slower                                                  |
| docutils       | 1.46 sec                                               | 1.49 sec: 1.02x slower                                                 |
| Geometric mean | (ref)                                                  | 1.05x slower                                                           |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231030-darwin-arm64-python-05f2f0ac92afa560315e-3.13.0a1+-05f2f0a |
|----------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| async_tree_none            | 282 ms                                                 | 251 ms: 1.12x faster                                                   |
| async_tree_memoization     | 361 ms                                                 | 327 ms: 1.10x faster                                                   |
| async_tree_memoization_tg  | 357 ms                                                 | 329 ms: 1.08x faster                                                   |
| async_tree_io_tg           | 734 ms                                                 | 677 ms: 1.08x faster                                                   |
| async_tree_none_tg         | 280 ms                                                 | 265 ms: 1.06x faster                                                   |
| async_tree_cpu_io_mixed_tg | 554 ms                                                 | 541 ms: 1.02x faster                                                   |
| async_tree_io              | 705 ms                                                 | 696 ms: 1.01x faster                                                   |
| Geometric mean             | (ref)                                                  | 1.06x faster                                                           |

Benchmark hidden because not significant (1): async_tree_cpu_io_mixed

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231030-darwin-arm64-python-05f2f0ac92afa560315e-3.13.0a1+-05f2f0a |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| float          | 55.4 ms                                                | 54.4 ms: 1.02x faster                                                  |
| pidigits       | 281 ms                                                 | 283 ms: 1.00x slower                                                   |
| nbody          | 68.7 ms                                                | 70.4 ms: 1.02x slower                                                  |
| Geometric mean | (ref)                                                  | 1.00x slower                                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231030-darwin-arm64-python-05f2f0ac92afa560315e-3.13.0a1+-05f2f0a |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| regex_dna      | 149 ms                                                 | 151 ms: 1.01x slower                                                   |
| regex_compile  | 73.9 ms                                                | 75.3 ms: 1.02x slower                                                  |
| regex_effbot   | 2.46 ms                                                | 2.60 ms: 1.06x slower                                                  |
| regex_v8       | 15.3 ms                                                | 16.9 ms: 1.10x slower                                                  |
| Geometric mean | (ref)                                                  | 1.05x slower                                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231030-darwin-arm64-python-05f2f0ac92afa560315e-3.13.0a1+-05f2f0a |
|----------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| json_dumps           | 7.58 ms                                                | 6.44 ms: 1.18x faster                                                  |
| pickle_pure_python   | 211 us                                                 | 193 us: 1.09x faster                                                   |
| unpickle_pure_python | 163 us                                                 | 155 us: 1.05x faster                                                   |
| pickle               | 7.22 us                                                | 7.31 us: 1.01x slower                                                  |
| xml_etree_parse      | 107 ms                                                 | 110 ms: 1.03x slower                                                   |
| pickle_dict          | 17.0 us                                                | 18.0 us: 1.05x slower                                                  |
| pickle_list          | 2.67 us                                                | 2.90 us: 1.09x slower                                                  |
| unpickle             | 8.32 us                                                | 9.12 us: 1.10x slower                                                  |
| json_loads           | 15.8 us                                                | 17.5 us: 1.11x slower                                                  |
| xml_etree_iterparse  | 68.2 ms                                                | 75.9 ms: 1.11x slower                                                  |
| unpickle_list        | 2.77 us                                                | 3.13 us: 1.13x slower                                                  |
| xml_etree_process    | 34.0 ms                                                | 38.9 ms: 1.14x slower                                                  |
| tomli_loads          | 1.30 sec                                               | 1.54 sec: 1.18x slower                                                 |
| xml_etree_generate   | 46.8 ms                                                | 57.1 ms: 1.22x slower                                                  |
| Geometric mean       | (ref)                                                  | 1.06x slower                                                           |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231030-darwin-arm64-python-05f2f0ac92afa560315e-3.13.0a1+-05f2f0a |
|------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| python_startup         | 11.4 ms                                                | 12.8 ms: 1.13x slower                                                  |
| python_startup_no_site | 9.15 ms                                                | 11.5 ms: 1.26x slower                                                  |
| Geometric mean         | (ref)                                                  | 1.19x slower                                                           |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231030-darwin-arm64-python-05f2f0ac92afa560315e-3.13.0a1+-05f2f0a |
|-----------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| mako      | 8.22 ms                                                | 7.34 ms: 1.12x faster                                                  |

All benchmarks:
===============

| Benchmark                  | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231030-darwin-arm64-python-05f2f0ac92afa560315e-3.13.0a1+-05f2f0a |
|----------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| typing_runtime_protocols   | 323 us                                                 | 92.7 us: 3.48x faster                                                  |
| asyncio_tcp                | 650 ms                                                 | 447 ms: 1.45x faster                                                   |
| comprehensions             | 14.7 us                                                | 11.5 us: 1.28x faster                                                  |
| unpack_sequence            | 32.3 ns                                                | 26.1 ns: 1.24x faster                                                  |
| deepcopy_memo              | 28.9 us                                                | 23.8 us: 1.21x faster                                                  |
| chaos                      | 48.2 ms                                                | 40.0 ms: 1.21x faster                                                  |
| generators                 | 29.2 ms                                                | 24.6 ms: 1.19x faster                                                  |
| json_dumps                 | 7.58 ms                                                | 6.44 ms: 1.18x faster                                                  |
| raytrace                   | 200 ms                                                 | 172 ms: 1.17x faster                                                   |
| deltablue                  | 2.70 ms                                                | 2.32 ms: 1.16x faster                                                  |
| async_tree_none            | 282 ms                                                 | 251 ms: 1.12x faster                                                   |
| sqlglot_parse              | 886 us                                                 | 790 us: 1.12x faster                                                   |
| mako                       | 8.22 ms                                                | 7.34 ms: 1.12x faster                                                  |
| asyncio_tcp_ssl            | 1.44 sec                                               | 1.29 sec: 1.12x faster                                                 |
| sympy_sum                  | 81.6 ms                                                | 73.4 ms: 1.11x faster                                                  |
| async_tree_memoization     | 361 ms                                                 | 327 ms: 1.10x faster                                                   |
| pickle_pure_python         | 211 us                                                 | 193 us: 1.09x faster                                                   |
| sqlglot_transpile          | 1.05 ms                                                | 962 us: 1.09x faster                                                   |
| async_tree_memoization_tg  | 357 ms                                                 | 329 ms: 1.08x faster                                                   |
| async_tree_io_tg           | 734 ms                                                 | 677 ms: 1.08x faster                                                   |
| mdp                        | 1.73 sec                                               | 1.61 sec: 1.07x faster                                                 |
| async_tree_none_tg         | 280 ms                                                 | 265 ms: 1.06x faster                                                   |
| deepcopy                   | 233 us                                                 | 221 us: 1.06x faster                                                   |
| unpickle_pure_python       | 163 us                                                 | 155 us: 1.05x faster                                                   |
| sympy_integrate            | 11.3 ms                                                | 10.8 ms: 1.05x faster                                                  |
| scimark_monte_carlo        | 47.1 ms                                                | 44.9 ms: 1.05x faster                                                  |
| crypto_pyaes               | 48.1 ms                                                | 46.7 ms: 1.03x faster                                                  |
| richards_super             | 36.8 ms                                                | 35.9 ms: 1.03x faster                                                  |
| sympy_str                  | 144 ms                                                 | 141 ms: 1.03x faster                                                   |
| create_gc_cycles           | 715 us                                                 | 698 us: 1.02x faster                                                   |
| async_tree_cpu_io_mixed_tg | 554 ms                                                 | 541 ms: 1.02x faster                                                   |
| float                      | 55.4 ms                                                | 54.4 ms: 1.02x faster                                                  |
| meteor_contest             | 74.9 ms                                                | 73.8 ms: 1.01x faster                                                  |
| async_tree_io              | 705 ms                                                 | 696 ms: 1.01x faster                                                   |
| asyncio_websockets         | 544 ms                                                 | 545 ms: 1.00x slower                                                   |
| go                         | 102 ms                                                 | 102 ms: 1.00x slower                                                   |
| hexiom                     | 4.55 ms                                                | 4.58 ms: 1.00x slower                                                  |
| pidigits                   | 281 ms                                                 | 283 ms: 1.00x slower                                                   |
| gc_traversal               | 2.39 ms                                                | 2.40 ms: 1.01x slower                                                  |
| spectral_norm              | 69.7 ms                                                | 70.3 ms: 1.01x slower                                                  |
| pprint_pformat             | 989 ms                                                 | 1.00 sec: 1.01x slower                                                 |
| pickle                     | 7.22 us                                                | 7.31 us: 1.01x slower                                                  |
| regex_dna                  | 149 ms                                                 | 151 ms: 1.01x slower                                                   |
| scimark_sparse_mat_mult    | 3.01 ms                                                | 3.06 ms: 1.02x slower                                                  |
| regex_compile              | 73.9 ms                                                | 75.3 ms: 1.02x slower                                                  |
| dulwich_log                | 29.9 ms                                                | 30.5 ms: 1.02x slower                                                  |
| docutils                   | 1.46 sec                                               | 1.49 sec: 1.02x slower                                                 |
| nbody                      | 68.7 ms                                                | 70.4 ms: 1.02x slower                                                  |
| pathlib                    | 28.5 ms                                                | 29.3 ms: 1.03x slower                                                  |
| pycparser                  | 667 ms                                                 | 686 ms: 1.03x slower                                                   |
| pprint_safe_repr           | 479 ms                                                 | 493 ms: 1.03x slower                                                   |
| xml_etree_parse            | 107 ms                                                 | 110 ms: 1.03x slower                                                   |
| scimark_lu                 | 67.8 ms                                                | 69.9 ms: 1.03x slower                                                  |
| logging_format             | 3.69 us                                                | 3.80 us: 1.03x slower                                                  |
| logging_silent             | 64.5 ns                                                | 66.6 ns: 1.03x slower                                                  |
| sympy_expand               | 234 ms                                                 | 241 ms: 1.03x slower                                                   |
| bench_thread_pool          | 461 us                                                 | 478 us: 1.04x slower                                                   |
| logging_simple             | 3.41 us                                                | 3.54 us: 1.04x slower                                                  |
| richards                   | 30.8 ms                                                | 32.4 ms: 1.05x slower                                                  |
| pickle_dict                | 17.0 us                                                | 18.0 us: 1.05x slower                                                  |
| scimark_fft                | 187 ms                                                 | 197 ms: 1.06x slower                                                   |
| regex_effbot               | 2.46 ms                                                | 2.60 ms: 1.06x slower                                                  |
| nqueens                    | 54.6 ms                                                | 57.7 ms: 1.06x slower                                                  |
| coroutines                 | 16.6 ms                                                | 17.7 ms: 1.07x slower                                                  |
| bench_mp_pool              | 41.9 ms                                                | 45.2 ms: 1.08x slower                                                  |
| json                       | 2.77 ms                                                | 3.00 ms: 1.08x slower                                                  |
| pickle_list                | 2.67 us                                                | 2.90 us: 1.09x slower                                                  |
| 2to3                       | 155 ms                                                 | 170 ms: 1.09x slower                                                   |
| unpickle                   | 8.32 us                                                | 9.12 us: 1.10x slower                                                  |
| regex_v8                   | 15.3 ms                                                | 16.9 ms: 1.10x slower                                                  |
| chameleon                  | 4.17 ms                                                | 4.63 ms: 1.11x slower                                                  |
| json_loads                 | 15.8 us                                                | 17.5 us: 1.11x slower                                                  |
| xml_etree_iterparse        | 68.2 ms                                                | 75.9 ms: 1.11x slower                                                  |
| coverage                   | 41.4 ms                                                | 46.1 ms: 1.11x slower                                                  |
| pyflate                    | 297 ms                                                 | 333 ms: 1.12x slower                                                   |
| python_startup             | 11.4 ms                                                | 12.8 ms: 1.13x slower                                                  |
| fannkuch                   | 247 ms                                                 | 279 ms: 1.13x slower                                                   |
| unpickle_list              | 2.77 us                                                | 3.13 us: 1.13x slower                                                  |
| sqlglot_normalize          | 160 ms                                                 | 182 ms: 1.14x slower                                                   |
| sqlglot_optimize           | 29.6 ms                                                | 33.8 ms: 1.14x slower                                                  |
| xml_etree_process          | 34.0 ms                                                | 38.9 ms: 1.14x slower                                                  |
| tomli_loads                | 1.30 sec                                               | 1.54 sec: 1.18x slower                                                 |
| sqlite_synth               | 1.35 us                                                | 1.61 us: 1.20x slower                                                  |
| xml_etree_generate         | 46.8 ms                                                | 57.1 ms: 1.22x slower                                                  |
| python_startup_no_site     | 9.15 ms                                                | 11.5 ms: 1.26x slower                                                  |
| mypy2                      | 191 ms                                                 | 257 ms: 1.35x slower                                                   |
| scimark_sor                | 75.2 ms                                                | 103 ms: 1.37x slower                                                   |
| telco                      | 3.17 ms                                                | 4.74 ms: 1.49x slower                                                  |
| async_generators           | 192 ms                                                 | 301 ms: 1.57x slower                                                   |
| Geometric mean             | (ref)                                                  | 1.00x slower                                                           |

Benchmark hidden because not significant (3): tornado_http, deepcopy_reduce, async_tree_cpu_io_mixed
Ignored benchmarks (12) of results/bm-20221024-3.11.0-deaf509/bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, dask, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift


# HPT report

- Reliability score: 92.79% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
