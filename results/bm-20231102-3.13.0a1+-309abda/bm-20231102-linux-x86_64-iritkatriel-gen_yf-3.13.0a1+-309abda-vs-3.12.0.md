
# Results vs. 3.12.0

- fork: iritkatriel
- ref: gen_yf
- machine: linux-x86_64
- commit hash: 309abda
- commit date: 2023-11-02
- overall geometric mean: 1.03x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231102-linux-x86_64-iritkatriel-gen_yf-3.13.0a1+-309abda |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| 2to3           | 274 ms                                                 | 264 ms: 1.04x faster                                          |
| chameleon      | 7.41 ms                                                | 6.96 ms: 1.06x faster                                         |
| docutils       | 2.75 sec                                               | 2.60 sec: 1.06x faster                                        |
| tornado_http   | 101 ms                                                 | 95.1 ms: 1.06x faster                                         |
| Geometric mean | (ref)                                                  | 1.05x faster                                                  |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231102-linux-x86_64-iritkatriel-gen_yf-3.13.0a1+-309abda |
|----------------------------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| async_tree_none            | 475 ms                                                 | 437 ms: 1.09x faster                                          |
| async_tree_memoization     | 580 ms                                                 | 563 ms: 1.03x faster                                          |
| async_tree_cpu_io_mixed    | 724 ms                                                 | 713 ms: 1.02x faster                                          |
| async_tree_io              | 1.16 sec                                               | 1.18 sec: 1.02x slower                                        |
| async_tree_none_tg         | 447 ms                                                 | 455 ms: 1.02x slower                                          |
| async_tree_cpu_io_mixed_tg | 725 ms                                                 | 744 ms: 1.03x slower                                          |
| async_tree_io_tg           | 1.19 sec                                               | 1.23 sec: 1.03x slower                                        |
| async_tree_memoization_tg  | 574 ms                                                 | 597 ms: 1.04x slower                                          |
| Geometric mean             | (ref)                                                  | 1.00x slower                                                  |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231102-linux-x86_64-iritkatriel-gen_yf-3.13.0a1+-309abda |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| float          | 83.3 ms                                                | 81.7 ms: 1.02x faster                                         |
| nbody          | 92.2 ms                                                | 91.3 ms: 1.01x faster                                         |
| pidigits       | 187 ms                                                 | 187 ms: 1.00x faster                                          |
| Geometric mean | (ref)                                                  | 1.01x faster                                                  |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231102-linux-x86_64-iritkatriel-gen_yf-3.13.0a1+-309abda |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| regex_compile  | 148 ms                                                 | 134 ms: 1.10x faster                                          |
| regex_effbot   | 3.57 ms                                                | 3.68 ms: 1.03x slower                                         |
| regex_dna      | 209 ms                                                 | 217 ms: 1.04x slower                                          |
| regex_v8       | 22.7 ms                                                | 25.5 ms: 1.13x slower                                         |
| Geometric mean | (ref)                                                  | 1.02x slower                                                  |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231102-linux-x86_64-iritkatriel-gen_yf-3.13.0a1+-309abda |
|----------------------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| pickle_pure_python   | 326 us                                                 | 293 us: 1.11x faster                                          |
| unpickle_pure_python | 230 us                                                 | 215 us: 1.07x faster                                          |
| tomli_loads          | 2.30 sec                                               | 2.17 sec: 1.06x faster                                        |
| xml_etree_process    | 61.2 ms                                                | 59.3 ms: 1.03x faster                                         |
| xml_etree_generate   | 88.7 ms                                                | 86.2 ms: 1.03x faster                                         |
| json_loads           | 28.4 us                                                | 27.8 us: 1.02x faster                                         |
| json_dumps           | 10.6 ms                                                | 10.5 ms: 1.01x faster                                         |
| xml_etree_iterparse  | 106 ms                                                 | 105 ms: 1.01x faster                                          |
| unpickle_list        | 5.04 us                                                | 5.19 us: 1.03x slower                                         |
| pickle               | 11.2 us                                                | 11.5 us: 1.03x slower                                         |
| pickle_dict          | 33.5 us                                                | 36.0 us: 1.08x slower                                         |
| pickle_list          | 4.67 us                                                | 5.11 us: 1.09x slower                                         |
| Geometric mean       | (ref)                                                  | 1.01x faster                                                  |

Benchmark hidden because not significant (2): xml_etree_parse, unpickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231102-linux-x86_64-iritkatriel-gen_yf-3.13.0a1+-309abda |
|------------------------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| python_startup         | 9.53 ms                                                | 10.3 ms: 1.08x slower                                         |
| python_startup_no_site | 6.92 ms                                                | 8.98 ms: 1.30x slower                                         |
| Geometric mean         | (ref)                                                  | 1.18x slower                                                  |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231102-linux-x86_64-iritkatriel-gen_yf-3.13.0a1+-309abda |
|-----------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| mako      | 11.5 ms                                                | 11.4 ms: 1.01x faster                                         |

All benchmarks:
===============

| Benchmark                  | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231102-linux-x86_64-iritkatriel-gen_yf-3.13.0a1+-309abda |
|----------------------------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| typing_runtime_protocols   | 153 us                                                 | 115 us: 1.33x faster                                          |
| comprehensions             | 20.9 us                                                | 16.3 us: 1.28x faster                                         |
| crypto_pyaes               | 83.6 ms                                                | 71.2 ms: 1.17x faster                                         |
| sympy_sum                  | 167 ms                                                 | 147 ms: 1.14x faster                                          |
| gc_traversal               | 4.28 ms                                                | 3.82 ms: 1.12x faster                                         |
| scimark_sparse_mat_mult    | 5.33 ms                                                | 4.79 ms: 1.11x faster                                         |
| raytrace                   | 308 ms                                                 | 277 ms: 1.11x faster                                          |
| pickle_pure_python         | 326 us                                                 | 293 us: 1.11x faster                                          |
| sympy_str                  | 296 ms                                                 | 267 ms: 1.11x faster                                          |
| scimark_monte_carlo        | 74.6 ms                                                | 67.5 ms: 1.11x faster                                         |
| regex_compile              | 148 ms                                                 | 134 ms: 1.10x faster                                          |
| chaos                      | 67.5 ms                                                | 61.2 ms: 1.10x faster                                         |
| logging_format             | 7.10 us                                                | 6.44 us: 1.10x faster                                         |
| generators                 | 32.5 ms                                                | 29.5 ms: 1.10x faster                                         |
| nqueens                    | 86.2 ms                                                | 78.3 ms: 1.10x faster                                         |
| deltablue                  | 3.71 ms                                                | 3.37 ms: 1.10x faster                                         |
| logging_simple             | 6.38 us                                                | 5.82 us: 1.10x faster                                         |
| sympy_integrate            | 21.2 ms                                                | 19.3 ms: 1.10x faster                                         |
| async_tree_none            | 475 ms                                                 | 437 ms: 1.09x faster                                          |
| hexiom                     | 6.54 ms                                                | 6.05 ms: 1.08x faster                                         |
| unpickle_pure_python       | 230 us                                                 | 215 us: 1.07x faster                                          |
| sympy_expand               | 476 ms                                                 | 447 ms: 1.06x faster                                          |
| chameleon                  | 7.41 ms                                                | 6.96 ms: 1.06x faster                                         |
| sqlglot_normalize          | 112 ms                                                 | 105 ms: 1.06x faster                                          |
| scimark_lu                 | 120 ms                                                 | 114 ms: 1.06x faster                                          |
| tomli_loads                | 2.30 sec                                               | 2.17 sec: 1.06x faster                                        |
| tornado_http               | 101 ms                                                 | 95.1 ms: 1.06x faster                                         |
| sqlglot_parse              | 1.35 ms                                                | 1.28 ms: 1.06x faster                                         |
| docutils                   | 2.75 sec                                               | 2.60 sec: 1.06x faster                                        |
| sqlglot_transpile          | 1.68 ms                                                | 1.59 ms: 1.06x faster                                         |
| scimark_sor                | 129 ms                                                 | 122 ms: 1.06x faster                                          |
| deepcopy_reduce            | 3.23 us                                                | 3.06 us: 1.05x faster                                         |
| pprint_safe_repr           | 765 ms                                                 | 728 ms: 1.05x faster                                          |
| asyncio_tcp                | 506 ms                                                 | 482 ms: 1.05x faster                                          |
| dulwich_log                | 68.7 ms                                                | 65.7 ms: 1.05x faster                                         |
| deepcopy                   | 363 us                                                 | 347 us: 1.05x faster                                          |
| fannkuch                   | 410 ms                                                 | 392 ms: 1.05x faster                                          |
| spectral_norm              | 115 ms                                                 | 110 ms: 1.04x faster                                          |
| bench_thread_pool          | 845 us                                                 | 811 us: 1.04x faster                                          |
| pyflate                    | 471 ms                                                 | 452 ms: 1.04x faster                                          |
| pprint_pformat             | 1.55 sec                                               | 1.49 sec: 1.04x faster                                        |
| 2to3                       | 274 ms                                                 | 264 ms: 1.04x faster                                          |
| meteor_contest             | 110 ms                                                 | 106 ms: 1.03x faster                                          |
| deepcopy_memo              | 39.7 us                                                | 38.4 us: 1.03x faster                                         |
| mypy2                      | 351 ms                                                 | 340 ms: 1.03x faster                                          |
| sqlglot_optimize           | 54.8 ms                                                | 53.1 ms: 1.03x faster                                         |
| xml_etree_process          | 61.2 ms                                                | 59.3 ms: 1.03x faster                                         |
| xml_etree_generate         | 88.7 ms                                                | 86.2 ms: 1.03x faster                                         |
| async_tree_memoization     | 580 ms                                                 | 563 ms: 1.03x faster                                          |
| coroutines                 | 23.5 ms                                                | 22.8 ms: 1.03x faster                                         |
| async_generators           | 459 ms                                                 | 448 ms: 1.03x faster                                          |
| json                       | 5.22 ms                                                | 5.10 ms: 1.02x faster                                         |
| logging_silent             | 108 ns                                                 | 105 ns: 1.02x faster                                          |
| json_loads                 | 28.4 us                                                | 27.8 us: 1.02x faster                                         |
| float                      | 83.3 ms                                                | 81.7 ms: 1.02x faster                                         |
| async_tree_cpu_io_mixed    | 724 ms                                                 | 713 ms: 1.02x faster                                          |
| scimark_fft                | 381 ms                                                 | 376 ms: 1.01x faster                                          |
| mdp                        | 2.57 sec                                               | 2.54 sec: 1.01x faster                                        |
| nbody                      | 92.2 ms                                                | 91.3 ms: 1.01x faster                                         |
| json_dumps                 | 10.6 ms                                                | 10.5 ms: 1.01x faster                                         |
| mako                       | 11.5 ms                                                | 11.4 ms: 1.01x faster                                         |
| xml_etree_iterparse        | 106 ms                                                 | 105 ms: 1.01x faster                                          |
| unpack_sequence            | 54.2 ns                                                | 53.9 ns: 1.00x faster                                         |
| pidigits                   | 187 ms                                                 | 187 ms: 1.00x faster                                          |
| asyncio_tcp_ssl            | 1.78 sec                                               | 1.79 sec: 1.01x slower                                        |
| pathlib                    | 18.9 ms                                                | 19.1 ms: 1.01x slower                                         |
| go                         | 140 ms                                                 | 142 ms: 1.01x slower                                          |
| async_tree_io              | 1.16 sec                                               | 1.18 sec: 1.02x slower                                        |
| async_tree_none_tg         | 447 ms                                                 | 455 ms: 1.02x slower                                          |
| create_gc_cycles           | 1.45 ms                                                | 1.49 ms: 1.02x slower                                         |
| async_tree_cpu_io_mixed_tg | 725 ms                                                 | 744 ms: 1.03x slower                                          |
| unpickle_list              | 5.04 us                                                | 5.19 us: 1.03x slower                                         |
| regex_effbot               | 3.57 ms                                                | 3.68 ms: 1.03x slower                                         |
| pickle                     | 11.2 us                                                | 11.5 us: 1.03x slower                                         |
| async_tree_io_tg           | 1.19 sec                                               | 1.23 sec: 1.03x slower                                        |
| richards_super             | 51.9 ms                                                | 53.8 ms: 1.04x slower                                         |
| richards                   | 46.0 ms                                                | 47.8 ms: 1.04x slower                                         |
| async_tree_memoization_tg  | 574 ms                                                 | 597 ms: 1.04x slower                                          |
| regex_dna                  | 209 ms                                                 | 217 ms: 1.04x slower                                          |
| pickle_dict                | 33.5 us                                                | 36.0 us: 1.08x slower                                         |
| python_startup             | 9.53 ms                                                | 10.3 ms: 1.08x slower                                         |
| pickle_list                | 4.67 us                                                | 5.11 us: 1.09x slower                                         |
| regex_v8                   | 22.7 ms                                                | 25.5 ms: 1.13x slower                                         |
| telco                      | 7.18 ms                                                | 8.31 ms: 1.16x slower                                         |
| coverage                   | 75.1 ms                                                | 94.3 ms: 1.26x slower                                         |
| python_startup_no_site     | 6.92 ms                                                | 8.98 ms: 1.30x slower                                         |
| Geometric mean             | (ref)                                                  | 1.03x faster                                                  |

Benchmark hidden because not significant (6): sqlite_synth, bench_mp_pool, asyncio_websockets, xml_etree_parse, pycparser, unpickle
Ignored benchmarks (6) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, dask, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.01x
- 95% likely to have a speedup of 1.01x
- 99% likely to have a speedup of 1.00x
