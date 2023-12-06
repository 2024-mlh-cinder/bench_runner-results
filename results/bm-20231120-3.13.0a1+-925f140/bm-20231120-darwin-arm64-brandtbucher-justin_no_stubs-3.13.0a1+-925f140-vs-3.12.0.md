
# Results vs. 3.12.0

- fork: brandtbucher
- ref: justin_no_stubs
- machine: darwin-arm64
- commit hash: 925f140
- commit date: 2023-11-20
- overall geometric mean: 1.03x slower \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.01x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-darwin-arm64-brandtbucher-justin_no_stubs-3.13.0a1+-925f140 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| 2to3           | 171 ms                                                 | 181 ms: 1.06x slower                                                    |
| chameleon      | 4.51 ms                                                | 4.86 ms: 1.08x slower                                                   |
| docutils       | 1.54 sec                                               | 1.53 sec: 1.01x faster                                                  |
| tornado_http   | 70.7 ms                                                | 73.6 ms: 1.04x slower                                                   |
| Geometric mean | (ref)                                                  | 1.04x slower                                                            |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-darwin-arm64-brandtbucher-justin_no_stubs-3.13.0a1+-925f140 |
|----------------------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| async_tree_none            | 262 ms                                                 | 256 ms: 1.02x faster                                                    |
| async_tree_cpu_io_mixed_tg | 535 ms                                                 | 544 ms: 1.02x slower                                                    |
| async_tree_io_tg           | 673 ms                                                 | 687 ms: 1.02x slower                                                    |
| async_tree_memoization_tg  | 320 ms                                                 | 335 ms: 1.05x slower                                                    |
| async_tree_io              | 669 ms                                                 | 706 ms: 1.06x slower                                                    |
| async_tree_none_tg         | 254 ms                                                 | 269 ms: 1.06x slower                                                    |
| async_tree_memoization     | 309 ms                                                 | 332 ms: 1.07x slower                                                    |
| Geometric mean             | (ref)                                                  | 1.03x slower                                                            |

Benchmark hidden because not significant (1): async_tree_cpu_io_mixed

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-darwin-arm64-brandtbucher-justin_no_stubs-3.13.0a1+-925f140 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| pidigits       | 282 ms                                                 | 282 ms: 1.00x faster                                                    |
| float          | 58.1 ms                                                | 58.6 ms: 1.01x slower                                                   |
| nbody          | 68.5 ms                                                | 81.5 ms: 1.19x slower                                                   |
| Geometric mean | (ref)                                                  | 1.06x slower                                                            |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-darwin-arm64-brandtbucher-justin_no_stubs-3.13.0a1+-925f140 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| regex_dna      | 153 ms                                                 | 148 ms: 1.03x faster                                                    |
| regex_effbot   | 2.59 ms                                                | 2.57 ms: 1.01x faster                                                   |
| regex_v8       | 15.7 ms                                                | 17.1 ms: 1.09x slower                                                   |
| regex_compile  | 75.6 ms                                                | 83.3 ms: 1.10x slower                                                   |
| Geometric mean | (ref)                                                  | 1.04x slower                                                            |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-darwin-arm64-brandtbucher-justin_no_stubs-3.13.0a1+-925f140 |
|----------------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| unpickle_list        | 3.24 us                                                | 3.11 us: 1.04x faster                                                   |
| json_loads           | 17.6 us                                                | 17.4 us: 1.02x faster                                                   |
| unpickle             | 9.25 us                                                | 9.11 us: 1.02x faster                                                   |
| xml_etree_parse      | 109 ms                                                 | 108 ms: 1.01x faster                                                    |
| pickle_dict          | 18.0 us                                                | 17.9 us: 1.01x faster                                                   |
| pickle_list          | 2.89 us                                                | 2.93 us: 1.01x slower                                                   |
| json_dumps           | 6.46 ms                                                | 6.56 ms: 1.01x slower                                                   |
| xml_etree_iterparse  | 74.6 ms                                                | 76.8 ms: 1.03x slower                                                   |
| xml_etree_process    | 38.7 ms                                                | 40.7 ms: 1.05x slower                                                   |
| xml_etree_generate   | 55.9 ms                                                | 58.8 ms: 1.05x slower                                                   |
| pickle_pure_python   | 188 us                                                 | 206 us: 1.09x slower                                                    |
| tomli_loads          | 1.39 sec                                               | 1.52 sec: 1.10x slower                                                  |
| unpickle_pure_python | 145 us                                                 | 167 us: 1.15x slower                                                    |
| Geometric mean       | (ref)                                                  | 1.03x slower                                                            |

Benchmark hidden because not significant (1): pickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-darwin-arm64-brandtbucher-justin_no_stubs-3.13.0a1+-925f140 |
|------------------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| python_startup         | 11.9 ms                                                | 12.7 ms: 1.06x slower                                                   |
| python_startup_no_site | 9.71 ms                                                | 11.1 ms: 1.15x slower                                                   |
| Geometric mean         | (ref)                                                  | 1.11x slower                                                            |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-darwin-arm64-brandtbucher-justin_no_stubs-3.13.0a1+-925f140 |
|-----------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| mako      | 7.53 ms                                                | 7.92 ms: 1.05x slower                                                   |

All benchmarks:
===============

| Benchmark                  | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-darwin-arm64-brandtbucher-justin_no_stubs-3.13.0a1+-925f140 |
|----------------------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| asyncio_websockets         | 545 ms                                                 | 408 ms: 1.34x faster                                                    |
| raytrace                   | 246 ms                                                 | 193 ms: 1.27x faster                                                    |
| pathlib                    | 29.3 ms                                                | 24.3 ms: 1.21x faster                                                   |
| typing_runtime_protocols   | 90.8 us                                                | 77.7 us: 1.17x faster                                                   |
| asyncio_tcp                | 450 ms                                                 | 393 ms: 1.15x faster                                                    |
| comprehensions             | 15.8 us                                                | 13.8 us: 1.14x faster                                                   |
| generators                 | 28.3 ms                                                | 25.6 ms: 1.11x faster                                                   |
| unpickle_list              | 3.24 us                                                | 3.11 us: 1.04x faster                                                   |
| crypto_pyaes               | 52.0 ms                                                | 50.3 ms: 1.03x faster                                                   |
| sqlglot_parse              | 897 us                                                 | 868 us: 1.03x faster                                                    |
| regex_dna                  | 153 ms                                                 | 148 ms: 1.03x faster                                                    |
| async_tree_none            | 262 ms                                                 | 256 ms: 1.02x faster                                                    |
| sqlglot_transpile          | 1.08 ms                                                | 1.05 ms: 1.02x faster                                                   |
| logging_simple             | 3.69 us                                                | 3.62 us: 1.02x faster                                                   |
| logging_format             | 3.99 us                                                | 3.92 us: 1.02x faster                                                   |
| json_loads                 | 17.6 us                                                | 17.4 us: 1.02x faster                                                   |
| unpickle                   | 9.25 us                                                | 9.11 us: 1.02x faster                                                   |
| xml_etree_parse            | 109 ms                                                 | 108 ms: 1.01x faster                                                    |
| docutils                   | 1.54 sec                                               | 1.53 sec: 1.01x faster                                                  |
| regex_effbot               | 2.59 ms                                                | 2.57 ms: 1.01x faster                                                   |
| pickle_dict                | 18.0 us                                                | 17.9 us: 1.01x faster                                                   |
| create_gc_cycles           | 704 us                                                 | 700 us: 1.01x faster                                                    |
| dulwich_log                | 30.4 ms                                                | 30.2 ms: 1.01x faster                                                   |
| deltablue                  | 2.58 ms                                                | 2.57 ms: 1.00x faster                                                   |
| gc_traversal               | 2.40 ms                                                | 2.39 ms: 1.00x faster                                                   |
| pidigits                   | 282 ms                                                 | 282 ms: 1.00x faster                                                    |
| sympy_str                  | 151 ms                                                 | 153 ms: 1.01x slower                                                    |
| float                      | 58.1 ms                                                | 58.6 ms: 1.01x slower                                                   |
| pickle_list                | 2.89 us                                                | 2.93 us: 1.01x slower                                                   |
| unpack_sequence            | 28.4 ns                                                | 28.7 ns: 1.01x slower                                                   |
| sympy_sum                  | 79.5 ms                                                | 80.6 ms: 1.01x slower                                                   |
| mdp                        | 1.66 sec                                               | 1.69 sec: 1.01x slower                                                  |
| json_dumps                 | 6.46 ms                                                | 6.56 ms: 1.01x slower                                                   |
| async_tree_cpu_io_mixed_tg | 535 ms                                                 | 544 ms: 1.02x slower                                                    |
| async_tree_io_tg           | 673 ms                                                 | 687 ms: 1.02x slower                                                    |
| deepcopy                   | 225 us                                                 | 230 us: 1.02x slower                                                    |
| coroutines                 | 18.1 ms                                                | 18.6 ms: 1.03x slower                                                   |
| xml_etree_iterparse        | 74.6 ms                                                | 76.8 ms: 1.03x slower                                                   |
| async_generators           | 306 ms                                                 | 316 ms: 1.03x slower                                                    |
| sympy_expand               | 249 ms                                                 | 258 ms: 1.03x slower                                                    |
| asyncio_tcp_ssl            | 1.26 sec                                               | 1.30 sec: 1.04x slower                                                  |
| tornado_http               | 70.7 ms                                                | 73.6 ms: 1.04x slower                                                   |
| sqlglot_normalize          | 188 ms                                                 | 196 ms: 1.04x slower                                                    |
| sqlite_synth               | 1.59 us                                                | 1.66 us: 1.05x slower                                                   |
| async_tree_memoization_tg  | 320 ms                                                 | 335 ms: 1.05x slower                                                    |
| scimark_sparse_mat_mult    | 3.14 ms                                                | 3.30 ms: 1.05x slower                                                   |
| xml_etree_process          | 38.7 ms                                                | 40.7 ms: 1.05x slower                                                   |
| xml_etree_generate         | 55.9 ms                                                | 58.8 ms: 1.05x slower                                                   |
| mako                       | 7.53 ms                                                | 7.92 ms: 1.05x slower                                                   |
| richards_super             | 34.9 ms                                                | 36.8 ms: 1.05x slower                                                   |
| sympy_integrate            | 11.3 ms                                                | 12.0 ms: 1.06x slower                                                   |
| async_tree_io              | 669 ms                                                 | 706 ms: 1.06x slower                                                    |
| async_tree_none_tg         | 254 ms                                                 | 269 ms: 1.06x slower                                                    |
| 2to3                       | 171 ms                                                 | 181 ms: 1.06x slower                                                    |
| deepcopy_memo              | 24.6 us                                                | 26.0 us: 1.06x slower                                                   |
| pyflate                    | 329 ms                                                 | 349 ms: 1.06x slower                                                    |
| python_startup             | 11.9 ms                                                | 12.7 ms: 1.06x slower                                                   |
| pycparser                  | 670 ms                                                 | 713 ms: 1.06x slower                                                    |
| sqlglot_optimize           | 34.7 ms                                                | 36.9 ms: 1.06x slower                                                   |
| go                         | 107 ms                                                 | 114 ms: 1.07x slower                                                    |
| richards                   | 31.1 ms                                                | 33.3 ms: 1.07x slower                                                   |
| async_tree_memoization     | 309 ms                                                 | 332 ms: 1.07x slower                                                    |
| logging_silent             | 68.3 ns                                                | 73.4 ns: 1.07x slower                                                   |
| bench_thread_pool          | 492 us                                                 | 529 us: 1.08x slower                                                    |
| chameleon                  | 4.51 ms                                                | 4.86 ms: 1.08x slower                                                   |
| meteor_contest             | 73.3 ms                                                | 78.9 ms: 1.08x slower                                                   |
| pprint_safe_repr           | 491 ms                                                 | 532 ms: 1.08x slower                                                    |
| pprint_pformat             | 1.00 sec                                               | 1.09 sec: 1.08x slower                                                  |
| nqueens                    | 60.2 ms                                                | 65.4 ms: 1.09x slower                                                   |
| regex_v8                   | 15.7 ms                                                | 17.1 ms: 1.09x slower                                                   |
| pickle_pure_python         | 188 us                                                 | 206 us: 1.09x slower                                                    |
| scimark_lu                 | 71.5 ms                                                | 78.0 ms: 1.09x slower                                                   |
| tomli_loads                | 1.39 sec                                               | 1.52 sec: 1.10x slower                                                  |
| spectral_norm              | 74.6 ms                                                | 82.0 ms: 1.10x slower                                                   |
| regex_compile              | 75.6 ms                                                | 83.3 ms: 1.10x slower                                                   |
| scimark_fft                | 198 ms                                                 | 223 ms: 1.13x slower                                                    |
| fannkuch                   | 265 ms                                                 | 299 ms: 1.13x slower                                                    |
| scimark_sor                | 94.3 ms                                                | 108 ms: 1.15x slower                                                    |
| python_startup_no_site     | 9.71 ms                                                | 11.1 ms: 1.15x slower                                                   |
| unpickle_pure_python       | 145 us                                                 | 167 us: 1.15x slower                                                    |
| nbody                      | 68.5 ms                                                | 81.5 ms: 1.19x slower                                                   |
| telco                      | 3.79 ms                                                | 4.75 ms: 1.25x slower                                                   |
| coverage                   | 37.9 ms                                                | 49.7 ms: 1.31x slower                                                   |
| hexiom                     | 4.25 ms                                                | 5.78 ms: 1.36x slower                                                   |
| Geometric mean             | (ref)                                                  | 1.03x slower                                                            |

Benchmark hidden because not significant (9): deepcopy_reduce, chaos, scimark_monte_carlo, pickle, async_tree_cpu_io_mixed, json, dask, bench_mp_pool, mypy2
Ignored benchmarks (5) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.02x
- 95% likely to have a slowdown of 1.02x
- 99% likely to have a slowdown of 1.01x
