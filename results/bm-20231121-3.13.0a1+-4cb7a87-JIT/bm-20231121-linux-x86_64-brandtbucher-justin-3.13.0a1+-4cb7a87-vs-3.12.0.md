
# Results vs. 3.12.0

- fork: brandtbucher
- ref: justin
- machine: linux-x86_64
- commit hash: 4cb7a87
- commit date: 2023-11-21
- overall geometric mean: 1.00x slower \*
- HPT reliability: 67.51%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231121-linux-x86_64-brandtbucher-justin-3.13.0a1+-4cb7a87 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| 2to3           | 274 ms                                                 | 274 ms: 1.00x faster                                           |
| chameleon      | 7.41 ms                                                | 7.19 ms: 1.03x faster                                          |
| docutils       | 2.75 sec                                               | 2.63 sec: 1.05x faster                                         |
| tornado_http   | 101 ms                                                 | 96.8 ms: 1.04x faster                                          |
| Geometric mean | (ref)                                                  | 1.03x faster                                                   |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231121-linux-x86_64-brandtbucher-justin-3.13.0a1+-4cb7a87 |
|----------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| async_tree_none            | 475 ms                                                 | 444 ms: 1.07x faster                                           |
| async_tree_memoization     | 580 ms                                                 | 567 ms: 1.02x faster                                           |
| async_tree_io              | 1.16 sec                                               | 1.20 sec: 1.03x slower                                         |
| async_tree_none_tg         | 447 ms                                                 | 462 ms: 1.03x slower                                           |
| async_tree_cpu_io_mixed_tg | 725 ms                                                 | 749 ms: 1.03x slower                                           |
| async_tree_io_tg           | 1.19 sec                                               | 1.24 sec: 1.04x slower                                         |
| async_tree_memoization_tg  | 574 ms                                                 | 608 ms: 1.06x slower                                           |
| Geometric mean             | (ref)                                                  | 1.01x slower                                                   |

Benchmark hidden because not significant (1): async_tree_cpu_io_mixed

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231121-linux-x86_64-brandtbucher-justin-3.13.0a1+-4cb7a87 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| pidigits       | 187 ms                                                 | 187 ms: 1.00x slower                                           |
| float          | 83.3 ms                                                | 84.7 ms: 1.02x slower                                          |
| nbody          | 92.2 ms                                                | 98.2 ms: 1.07x slower                                          |
| Geometric mean | (ref)                                                  | 1.03x slower                                                   |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231121-linux-x86_64-brandtbucher-justin-3.13.0a1+-4cb7a87 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| regex_compile  | 148 ms                                                 | 142 ms: 1.04x faster                                           |
| regex_effbot   | 3.57 ms                                                | 3.51 ms: 1.02x faster                                          |
| regex_dna      | 209 ms                                                 | 218 ms: 1.04x slower                                           |
| regex_v8       | 22.7 ms                                                | 24.4 ms: 1.08x slower                                          |
| Geometric mean | (ref)                                                  | 1.01x slower                                                   |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231121-linux-x86_64-brandtbucher-justin-3.13.0a1+-4cb7a87 |
|----------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| pickle_pure_python   | 326 us                                                 | 302 us: 1.08x faster                                           |
| tomli_loads          | 2.30 sec                                               | 2.15 sec: 1.07x faster                                         |
| unpickle             | 15.8 us                                                | 15.4 us: 1.02x faster                                          |
| unpickle_list        | 5.04 us                                                | 4.94 us: 1.02x faster                                          |
| xml_etree_process    | 61.2 ms                                                | 60.6 ms: 1.01x faster                                          |
| json_loads           | 28.4 us                                                | 28.2 us: 1.01x faster                                          |
| xml_etree_generate   | 88.7 ms                                                | 88.2 ms: 1.01x faster                                          |
| xml_etree_parse      | 159 ms                                                 | 159 ms: 1.01x faster                                           |
| unpickle_pure_python | 230 us                                                 | 229 us: 1.00x faster                                           |
| json_dumps           | 10.6 ms                                                | 10.7 ms: 1.01x slower                                          |
| pickle               | 11.2 us                                                | 11.4 us: 1.02x slower                                          |
| pickle_dict          | 33.5 us                                                | 34.4 us: 1.03x slower                                          |
| xml_etree_iterparse  | 106 ms                                                 | 109 ms: 1.03x slower                                           |
| pickle_list          | 4.67 us                                                | 5.20 us: 1.11x slower                                          |
| Geometric mean       | (ref)                                                  | 1.00x faster                                                   |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231121-linux-x86_64-brandtbucher-justin-3.13.0a1+-4cb7a87 |
|------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| python_startup         | 9.53 ms                                                | 10.5 ms: 1.10x slower                                          |
| python_startup_no_site | 6.92 ms                                                | 9.16 ms: 1.32x slower                                          |
| Geometric mean         | (ref)                                                  | 1.21x slower                                                   |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231121-linux-x86_64-brandtbucher-justin-3.13.0a1+-4cb7a87 |
|-----------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| mako      | 11.5 ms                                                | 12.3 ms: 1.07x slower                                          |

All benchmarks:
===============

| Benchmark                  | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231121-linux-x86_64-brandtbucher-justin-3.13.0a1+-4cb7a87 |
|----------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| typing_runtime_protocols   | 153 us                                                 | 118 us: 1.30x faster                                           |
| gc_traversal               | 4.28 ms                                                | 3.67 ms: 1.17x faster                                          |
| logging_format             | 7.10 us                                                | 6.41 us: 1.11x faster                                          |
| generators                 | 32.5 ms                                                | 29.4 ms: 1.10x faster                                          |
| comprehensions             | 20.9 us                                                | 19.2 us: 1.09x faster                                          |
| logging_simple             | 6.38 us                                                | 5.86 us: 1.09x faster                                          |
| raytrace                   | 308 ms                                                 | 284 ms: 1.08x faster                                           |
| pickle_pure_python         | 326 us                                                 | 302 us: 1.08x faster                                           |
| sympy_sum                  | 167 ms                                                 | 156 ms: 1.07x faster                                           |
| tomli_loads                | 2.30 sec                                               | 2.15 sec: 1.07x faster                                         |
| crypto_pyaes               | 83.6 ms                                                | 78.1 ms: 1.07x faster                                          |
| async_tree_none            | 475 ms                                                 | 444 ms: 1.07x faster                                           |
| sympy_str                  | 296 ms                                                 | 279 ms: 1.06x faster                                           |
| coroutines                 | 23.5 ms                                                | 22.2 ms: 1.05x faster                                          |
| docutils                   | 2.75 sec                                               | 2.63 sec: 1.05x faster                                         |
| regex_compile              | 148 ms                                                 | 142 ms: 1.04x faster                                           |
| tornado_http               | 101 ms                                                 | 96.8 ms: 1.04x faster                                          |
| deepcopy_reduce            | 3.23 us                                                | 3.11 us: 1.04x faster                                          |
| dulwich_log                | 68.7 ms                                                | 66.2 ms: 1.04x faster                                          |
| deepcopy                   | 363 us                                                 | 350 us: 1.04x faster                                           |
| chameleon                  | 7.41 ms                                                | 7.19 ms: 1.03x faster                                          |
| scimark_sparse_mat_mult    | 5.33 ms                                                | 5.19 ms: 1.03x faster                                          |
| sqlglot_parse              | 1.35 ms                                                | 1.32 ms: 1.02x faster                                          |
| sqlglot_transpile          | 1.68 ms                                                | 1.64 ms: 1.02x faster                                          |
| unpickle                   | 15.8 us                                                | 15.4 us: 1.02x faster                                          |
| sympy_integrate            | 21.2 ms                                                | 20.7 ms: 1.02x faster                                          |
| pathlib                    | 18.9 ms                                                | 18.5 ms: 1.02x faster                                          |
| asyncio_tcp                | 506 ms                                                 | 494 ms: 1.02x faster                                           |
| async_tree_memoization     | 580 ms                                                 | 567 ms: 1.02x faster                                           |
| sqlglot_normalize          | 112 ms                                                 | 109 ms: 1.02x faster                                           |
| scimark_lu                 | 120 ms                                                 | 118 ms: 1.02x faster                                           |
| unpickle_list              | 5.04 us                                                | 4.94 us: 1.02x faster                                          |
| sympy_expand               | 476 ms                                                 | 467 ms: 1.02x faster                                           |
| regex_effbot               | 3.57 ms                                                | 3.51 ms: 1.02x faster                                          |
| deepcopy_memo              | 39.7 us                                                | 39.0 us: 1.02x faster                                          |
| sqlite_synth               | 2.83 us                                                | 2.80 us: 1.01x faster                                          |
| xml_etree_process          | 61.2 ms                                                | 60.6 ms: 1.01x faster                                          |
| scimark_fft                | 381 ms                                                 | 377 ms: 1.01x faster                                           |
| json_loads                 | 28.4 us                                                | 28.2 us: 1.01x faster                                          |
| chaos                      | 67.5 ms                                                | 67.0 ms: 1.01x faster                                          |
| xml_etree_generate         | 88.7 ms                                                | 88.2 ms: 1.01x faster                                          |
| json                       | 5.22 ms                                                | 5.19 ms: 1.01x faster                                          |
| xml_etree_parse            | 159 ms                                                 | 159 ms: 1.01x faster                                           |
| unpickle_pure_python       | 230 us                                                 | 229 us: 1.00x faster                                           |
| 2to3                       | 274 ms                                                 | 274 ms: 1.00x faster                                           |
| pidigits                   | 187 ms                                                 | 187 ms: 1.00x slower                                           |
| logging_silent             | 108 ns                                                 | 108 ns: 1.01x slower                                           |
| sqlglot_optimize           | 54.8 ms                                                | 55.2 ms: 1.01x slower                                          |
| json_dumps                 | 10.6 ms                                                | 10.7 ms: 1.01x slower                                          |
| bench_thread_pool          | 845 us                                                 | 852 us: 1.01x slower                                           |
| asyncio_tcp_ssl            | 1.78 sec                                               | 1.80 sec: 1.01x slower                                         |
| create_gc_cycles           | 1.45 ms                                                | 1.47 ms: 1.01x slower                                          |
| richards_super             | 51.9 ms                                                | 52.7 ms: 1.01x slower                                          |
| pprint_safe_repr           | 765 ms                                                 | 777 ms: 1.02x slower                                           |
| meteor_contest             | 110 ms                                                 | 112 ms: 1.02x slower                                           |
| float                      | 83.3 ms                                                | 84.7 ms: 1.02x slower                                          |
| mdp                        | 2.57 sec                                               | 2.61 sec: 1.02x slower                                         |
| pickle                     | 11.2 us                                                | 11.4 us: 1.02x slower                                          |
| pickle_dict                | 33.5 us                                                | 34.4 us: 1.03x slower                                          |
| pprint_pformat             | 1.55 sec                                               | 1.59 sec: 1.03x slower                                         |
| scimark_monte_carlo        | 74.6 ms                                                | 76.7 ms: 1.03x slower                                          |
| richards                   | 46.0 ms                                                | 47.4 ms: 1.03x slower                                          |
| async_tree_io              | 1.16 sec                                               | 1.20 sec: 1.03x slower                                         |
| async_tree_none_tg         | 447 ms                                                 | 462 ms: 1.03x slower                                           |
| async_tree_cpu_io_mixed_tg | 725 ms                                                 | 749 ms: 1.03x slower                                           |
| xml_etree_iterparse        | 106 ms                                                 | 109 ms: 1.03x slower                                           |
| async_tree_io_tg           | 1.19 sec                                               | 1.24 sec: 1.04x slower                                         |
| regex_dna                  | 209 ms                                                 | 218 ms: 1.04x slower                                           |
| fannkuch                   | 410 ms                                                 | 431 ms: 1.05x slower                                           |
| async_tree_memoization_tg  | 574 ms                                                 | 608 ms: 1.06x slower                                           |
| unpack_sequence            | 54.2 ns                                                | 57.4 ns: 1.06x slower                                          |
| pyflate                    | 471 ms                                                 | 500 ms: 1.06x slower                                           |
| go                         | 140 ms                                                 | 149 ms: 1.06x slower                                           |
| nbody                      | 92.2 ms                                                | 98.2 ms: 1.07x slower                                          |
| mako                       | 11.5 ms                                                | 12.3 ms: 1.07x slower                                          |
| nqueens                    | 86.2 ms                                                | 92.6 ms: 1.07x slower                                          |
| regex_v8                   | 22.7 ms                                                | 24.4 ms: 1.08x slower                                          |
| deltablue                  | 3.71 ms                                                | 4.05 ms: 1.09x slower                                          |
| python_startup             | 9.53 ms                                                | 10.5 ms: 1.10x slower                                          |
| pickle_list                | 4.67 us                                                | 5.20 us: 1.11x slower                                          |
| hexiom                     | 6.54 ms                                                | 7.59 ms: 1.16x slower                                          |
| telco                      | 7.18 ms                                                | 8.46 ms: 1.18x slower                                          |
| spectral_norm              | 115 ms                                                 | 137 ms: 1.19x slower                                           |
| coverage                   | 75.1 ms                                                | 95.6 ms: 1.27x slower                                          |
| python_startup_no_site     | 6.92 ms                                                | 9.16 ms: 1.32x slower                                          |
| Geometric mean             | (ref)                                                  | 1.00x slower                                                   |

Benchmark hidden because not significant (8): async_tree_cpu_io_mixed, scimark_sor, dask, async_generators, pycparser, asyncio_websockets, bench_mp_pool, mypy2
Ignored benchmarks (5) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 67.51% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
