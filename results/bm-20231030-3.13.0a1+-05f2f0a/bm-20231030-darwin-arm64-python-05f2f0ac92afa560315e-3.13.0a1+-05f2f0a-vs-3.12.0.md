
# Results vs. 3.12.0

- fork: python
- ref: 05f2f0ac92afa560315e
- machine: darwin-arm64
- commit hash: 05f2f0a
- commit date: 2023-10-30
- overall geometric mean: 1.01x faster
- HPT reliability: 80.09%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231030-darwin-arm64-python-05f2f0ac92afa560315e-3.13.0a1+-05f2f0a |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| 2to3           | 171 ms                                                 | 170 ms: 1.01x faster                                                   |
| chameleon      | 4.51 ms                                                | 4.63 ms: 1.03x slower                                                  |
| docutils       | 1.54 sec                                               | 1.49 sec: 1.04x faster                                                 |
| Geometric mean | (ref)                                                  | 1.01x faster                                                           |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231030-darwin-arm64-python-05f2f0ac92afa560315e-3.13.0a1+-05f2f0a |
|----------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| async_tree_none            | 262 ms                                                 | 251 ms: 1.04x faster                                                   |
| async_tree_io_tg           | 673 ms                                                 | 677 ms: 1.01x slower                                                   |
| async_tree_cpu_io_mixed_tg | 535 ms                                                 | 541 ms: 1.01x slower                                                   |
| async_tree_memoization_tg  | 320 ms                                                 | 329 ms: 1.03x slower                                                   |
| async_tree_io              | 669 ms                                                 | 696 ms: 1.04x slower                                                   |
| async_tree_none_tg         | 254 ms                                                 | 265 ms: 1.04x slower                                                   |
| async_tree_memoization     | 309 ms                                                 | 327 ms: 1.06x slower                                                   |
| Geometric mean             | (ref)                                                  | 1.02x slower                                                           |

Benchmark hidden because not significant (1): async_tree_cpu_io_mixed

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231030-darwin-arm64-python-05f2f0ac92afa560315e-3.13.0a1+-05f2f0a |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| float          | 58.1 ms                                                | 54.4 ms: 1.07x faster                                                  |
| pidigits       | 282 ms                                                 | 283 ms: 1.00x slower                                                   |
| nbody          | 68.5 ms                                                | 70.4 ms: 1.03x slower                                                  |
| Geometric mean | (ref)                                                  | 1.01x faster                                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231030-darwin-arm64-python-05f2f0ac92afa560315e-3.13.0a1+-05f2f0a |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| regex_dna      | 153 ms                                                 | 151 ms: 1.01x faster                                                   |
| regex_compile  | 75.6 ms                                                | 75.3 ms: 1.00x faster                                                  |
| regex_effbot   | 2.59 ms                                                | 2.60 ms: 1.00x slower                                                  |
| regex_v8       | 15.7 ms                                                | 16.9 ms: 1.08x slower                                                  |
| Geometric mean | (ref)                                                  | 1.02x slower                                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231030-darwin-arm64-python-05f2f0ac92afa560315e-3.13.0a1+-05f2f0a |
|----------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| unpickle_list        | 3.24 us                                                | 3.13 us: 1.03x faster                                                  |
| unpickle             | 9.25 us                                                | 9.12 us: 1.02x faster                                                  |
| pickle               | 7.42 us                                                | 7.31 us: 1.01x faster                                                  |
| json_loads           | 17.6 us                                                | 17.5 us: 1.01x faster                                                  |
| json_dumps           | 6.46 ms                                                | 6.44 ms: 1.00x faster                                                  |
| xml_etree_process    | 38.7 ms                                                | 38.9 ms: 1.00x slower                                                  |
| xml_etree_parse      | 109 ms                                                 | 110 ms: 1.01x slower                                                   |
| xml_etree_iterparse  | 74.6 ms                                                | 75.9 ms: 1.02x slower                                                  |
| pickle_pure_python   | 188 us                                                 | 193 us: 1.02x slower                                                   |
| xml_etree_generate   | 55.9 ms                                                | 57.1 ms: 1.02x slower                                                  |
| unpickle_pure_python | 145 us                                                 | 155 us: 1.07x slower                                                   |
| tomli_loads          | 1.39 sec                                               | 1.54 sec: 1.11x slower                                                 |
| Geometric mean       | (ref)                                                  | 1.01x slower                                                           |

Benchmark hidden because not significant (2): pickle_dict, pickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231030-darwin-arm64-python-05f2f0ac92afa560315e-3.13.0a1+-05f2f0a |
|------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| python_startup         | 11.9 ms                                                | 12.8 ms: 1.08x slower                                                  |
| python_startup_no_site | 9.71 ms                                                | 11.5 ms: 1.18x slower                                                  |
| Geometric mean         | (ref)                                                  | 1.13x slower                                                           |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231030-darwin-arm64-python-05f2f0ac92afa560315e-3.13.0a1+-05f2f0a |
|-----------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| mako      | 7.53 ms                                                | 7.34 ms: 1.03x faster                                                  |

All benchmarks:
===============

| Benchmark                  | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231030-darwin-arm64-python-05f2f0ac92afa560315e-3.13.0a1+-05f2f0a |
|----------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| raytrace                   | 246 ms                                                 | 172 ms: 1.43x faster                                                   |
| comprehensions             | 15.8 us                                                | 11.5 us: 1.38x faster                                                  |
| generators                 | 28.3 ms                                                | 24.6 ms: 1.15x faster                                                  |
| sqlglot_parse              | 897 us                                                 | 790 us: 1.14x faster                                                   |
| chaos                      | 44.8 ms                                                | 40.0 ms: 1.12x faster                                                  |
| sqlglot_transpile          | 1.08 ms                                                | 962 us: 1.12x faster                                                   |
| deltablue                  | 2.58 ms                                                | 2.32 ms: 1.11x faster                                                  |
| scimark_monte_carlo        | 50.1 ms                                                | 44.9 ms: 1.11x faster                                                  |
| crypto_pyaes               | 52.0 ms                                                | 46.7 ms: 1.11x faster                                                  |
| unpack_sequence            | 28.4 ns                                                | 26.1 ns: 1.09x faster                                                  |
| sympy_sum                  | 79.5 ms                                                | 73.4 ms: 1.08x faster                                                  |
| sympy_str                  | 151 ms                                                 | 141 ms: 1.08x faster                                                   |
| float                      | 58.1 ms                                                | 54.4 ms: 1.07x faster                                                  |
| spectral_norm              | 74.6 ms                                                | 70.3 ms: 1.06x faster                                                  |
| sympy_integrate            | 11.3 ms                                                | 10.8 ms: 1.05x faster                                                  |
| logging_format             | 3.99 us                                                | 3.80 us: 1.05x faster                                                  |
| go                         | 107 ms                                                 | 102 ms: 1.05x faster                                                   |
| logging_simple             | 3.69 us                                                | 3.54 us: 1.04x faster                                                  |
| nqueens                    | 60.2 ms                                                | 57.7 ms: 1.04x faster                                                  |
| async_tree_none            | 262 ms                                                 | 251 ms: 1.04x faster                                                   |
| docutils                   | 1.54 sec                                               | 1.49 sec: 1.04x faster                                                 |
| deepcopy_reduce            | 2.05 us                                                | 1.98 us: 1.03x faster                                                  |
| unpickle_list              | 3.24 us                                                | 3.13 us: 1.03x faster                                                  |
| sqlglot_normalize          | 188 ms                                                 | 182 ms: 1.03x faster                                                   |
| sympy_expand               | 249 ms                                                 | 241 ms: 1.03x faster                                                   |
| deepcopy_memo              | 24.6 us                                                | 23.8 us: 1.03x faster                                                  |
| bench_thread_pool          | 492 us                                                 | 478 us: 1.03x faster                                                   |
| mdp                        | 1.66 sec                                               | 1.61 sec: 1.03x faster                                                 |
| scimark_sparse_mat_mult    | 3.14 ms                                                | 3.06 ms: 1.03x faster                                                  |
| sqlglot_optimize           | 34.7 ms                                                | 33.8 ms: 1.03x faster                                                  |
| coroutines                 | 18.1 ms                                                | 17.7 ms: 1.03x faster                                                  |
| logging_silent             | 68.3 ns                                                | 66.6 ns: 1.03x faster                                                  |
| mako                       | 7.53 ms                                                | 7.34 ms: 1.03x faster                                                  |
| bench_mp_pool              | 46.3 ms                                                | 45.2 ms: 1.02x faster                                                  |
| scimark_lu                 | 71.5 ms                                                | 69.9 ms: 1.02x faster                                                  |
| deepcopy                   | 225 us                                                 | 221 us: 1.02x faster                                                   |
| async_generators           | 306 ms                                                 | 301 ms: 1.02x faster                                                   |
| unpickle                   | 9.25 us                                                | 9.12 us: 1.02x faster                                                  |
| pickle                     | 7.42 us                                                | 7.31 us: 1.01x faster                                                  |
| regex_dna                  | 153 ms                                                 | 151 ms: 1.01x faster                                                   |
| json_loads                 | 17.6 us                                                | 17.5 us: 1.01x faster                                                  |
| create_gc_cycles           | 704 us                                                 | 698 us: 1.01x faster                                                   |
| 2to3                       | 171 ms                                                 | 170 ms: 1.01x faster                                                   |
| regex_compile              | 75.6 ms                                                | 75.3 ms: 1.00x faster                                                  |
| json_dumps                 | 6.46 ms                                                | 6.44 ms: 1.00x faster                                                  |
| scimark_fft                | 198 ms                                                 | 197 ms: 1.00x faster                                                   |
| pidigits                   | 282 ms                                                 | 283 ms: 1.00x slower                                                   |
| regex_effbot               | 2.59 ms                                                | 2.60 ms: 1.00x slower                                                  |
| dulwich_log                | 30.4 ms                                                | 30.5 ms: 1.00x slower                                                  |
| pprint_safe_repr           | 491 ms                                                 | 493 ms: 1.00x slower                                                   |
| xml_etree_process          | 38.7 ms                                                | 38.9 ms: 1.00x slower                                                  |
| async_tree_io_tg           | 673 ms                                                 | 677 ms: 1.01x slower                                                   |
| meteor_contest             | 73.3 ms                                                | 73.8 ms: 1.01x slower                                                  |
| async_tree_cpu_io_mixed_tg | 535 ms                                                 | 541 ms: 1.01x slower                                                   |
| pyflate                    | 329 ms                                                 | 333 ms: 1.01x slower                                                   |
| xml_etree_parse            | 109 ms                                                 | 110 ms: 1.01x slower                                                   |
| sqlite_synth               | 1.59 us                                                | 1.61 us: 1.01x slower                                                  |
| xml_etree_iterparse        | 74.6 ms                                                | 75.9 ms: 1.02x slower                                                  |
| typing_runtime_protocols   | 90.8 us                                                | 92.7 us: 1.02x slower                                                  |
| pickle_pure_python         | 188 us                                                 | 193 us: 1.02x slower                                                   |
| xml_etree_generate         | 55.9 ms                                                | 57.1 ms: 1.02x slower                                                  |
| pycparser                  | 670 ms                                                 | 686 ms: 1.02x slower                                                   |
| chameleon                  | 4.51 ms                                                | 4.63 ms: 1.03x slower                                                  |
| nbody                      | 68.5 ms                                                | 70.4 ms: 1.03x slower                                                  |
| asyncio_tcp_ssl            | 1.26 sec                                               | 1.29 sec: 1.03x slower                                                 |
| richards_super             | 34.9 ms                                                | 35.9 ms: 1.03x slower                                                  |
| async_tree_memoization_tg  | 320 ms                                                 | 329 ms: 1.03x slower                                                   |
| async_tree_io              | 669 ms                                                 | 696 ms: 1.04x slower                                                   |
| async_tree_none_tg         | 254 ms                                                 | 265 ms: 1.04x slower                                                   |
| richards                   | 31.1 ms                                                | 32.4 ms: 1.04x slower                                                  |
| fannkuch                   | 265 ms                                                 | 279 ms: 1.05x slower                                                   |
| async_tree_memoization     | 309 ms                                                 | 327 ms: 1.06x slower                                                   |
| unpickle_pure_python       | 145 us                                                 | 155 us: 1.07x slower                                                   |
| hexiom                     | 4.25 ms                                                | 4.58 ms: 1.08x slower                                                  |
| regex_v8                   | 15.7 ms                                                | 16.9 ms: 1.08x slower                                                  |
| python_startup             | 11.9 ms                                                | 12.8 ms: 1.08x slower                                                  |
| scimark_sor                | 94.3 ms                                                | 103 ms: 1.09x slower                                                   |
| tomli_loads                | 1.39 sec                                               | 1.54 sec: 1.11x slower                                                 |
| python_startup_no_site     | 9.71 ms                                                | 11.5 ms: 1.18x slower                                                  |
| coverage                   | 37.9 ms                                                | 46.1 ms: 1.22x slower                                                  |
| telco                      | 3.79 ms                                                | 4.74 ms: 1.25x slower                                                  |
| Geometric mean             | (ref)                                                  | 1.01x faster                                                           |

Benchmark hidden because not significant (11): tornado_http, mypy2, asyncio_tcp, json, async_tree_cpu_io_mixed, pickle_dict, pprint_pformat, asyncio_websockets, pathlib, gc_traversal, pickle_list
Ignored benchmarks (6) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, dask, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 80.09% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
