
# Results vs. 3.12.0

- fork: brandtbucher
- ref: justin
- machine: linux-x86_64
- commit hash: d65308a
- commit date: 2023-11-08
- overall geometric mean: 1.01x faster \*
- HPT reliability: 82.70%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231108-linux-x86_64-brandtbucher-justin-3.13.0a1+-d65308a |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| 2to3           | 274 ms                                                 | 270 ms: 1.02x faster                                           |
| chameleon      | 7.41 ms                                                | 7.18 ms: 1.03x faster                                          |
| docutils       | 2.75 sec                                               | 2.66 sec: 1.03x faster                                         |
| tornado_http   | 101 ms                                                 | 96.7 ms: 1.04x faster                                          |
| Geometric mean | (ref)                                                  | 1.03x faster                                                   |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231108-linux-x86_64-brandtbucher-justin-3.13.0a1+-d65308a |
|----------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| async_tree_none            | 475 ms                                                 | 448 ms: 1.06x faster                                           |
| async_tree_memoization     | 580 ms                                                 | 572 ms: 1.01x faster                                           |
| async_tree_io              | 1.16 sec                                               | 1.19 sec: 1.02x slower                                         |
| async_tree_none_tg         | 447 ms                                                 | 464 ms: 1.04x slower                                           |
| async_tree_cpu_io_mixed_tg | 725 ms                                                 | 751 ms: 1.04x slower                                           |
| async_tree_io_tg           | 1.19 sec                                               | 1.24 sec: 1.04x slower                                         |
| async_tree_memoization_tg  | 574 ms                                                 | 604 ms: 1.05x slower                                           |
| Geometric mean             | (ref)                                                  | 1.01x slower                                                   |

Benchmark hidden because not significant (1): async_tree_cpu_io_mixed

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231108-linux-x86_64-brandtbucher-justin-3.13.0a1+-d65308a |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| float          | 83.3 ms                                                | 82.0 ms: 1.02x faster                                          |
| nbody          | 92.2 ms                                                | 94.2 ms: 1.02x slower                                          |
| pidigits       | 187 ms                                                 | 195 ms: 1.04x slower                                           |
| Geometric mean | (ref)                                                  | 1.02x slower                                                   |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231108-linux-x86_64-brandtbucher-justin-3.13.0a1+-d65308a |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| regex_compile  | 148 ms                                                 | 140 ms: 1.06x faster                                           |
| regex_effbot   | 3.57 ms                                                | 3.59 ms: 1.01x slower                                          |
| regex_dna      | 209 ms                                                 | 223 ms: 1.07x slower                                           |
| regex_v8       | 22.7 ms                                                | 25.8 ms: 1.14x slower                                          |
| Geometric mean | (ref)                                                  | 1.04x slower                                                   |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231108-linux-x86_64-brandtbucher-justin-3.13.0a1+-d65308a |
|----------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| tomli_loads          | 2.30 sec                                               | 2.04 sec: 1.12x faster                                         |
| pickle_pure_python   | 326 us                                                 | 299 us: 1.09x faster                                           |
| unpickle             | 15.8 us                                                | 15.2 us: 1.04x faster                                          |
| json_loads           | 28.4 us                                                | 27.9 us: 1.02x faster                                          |
| xml_etree_generate   | 88.7 ms                                                | 87.1 ms: 1.02x faster                                          |
| xml_etree_process    | 61.2 ms                                                | 60.4 ms: 1.01x faster                                          |
| unpickle_pure_python | 230 us                                                 | 227 us: 1.01x faster                                           |
| json_dumps           | 10.6 ms                                                | 10.5 ms: 1.01x faster                                          |
| xml_etree_parse      | 159 ms                                                 | 158 ms: 1.01x faster                                           |
| xml_etree_iterparse  | 106 ms                                                 | 107 ms: 1.02x slower                                           |
| pickle_dict          | 33.5 us                                                | 34.3 us: 1.02x slower                                          |
| pickle               | 11.2 us                                                | 11.6 us: 1.03x slower                                          |
| unpickle_list        | 5.04 us                                                | 5.24 us: 1.04x slower                                          |
| pickle_list          | 4.67 us                                                | 4.97 us: 1.06x slower                                          |
| Geometric mean       | (ref)                                                  | 1.01x faster                                                   |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231108-linux-x86_64-brandtbucher-justin-3.13.0a1+-d65308a |
|------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| python_startup         | 9.53 ms                                                | 10.4 ms: 1.09x slower                                          |
| python_startup_no_site | 6.92 ms                                                | 9.07 ms: 1.31x slower                                          |
| Geometric mean         | (ref)                                                  | 1.19x slower                                                   |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231108-linux-x86_64-brandtbucher-justin-3.13.0a1+-d65308a |
|-----------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| mako      | 11.5 ms                                                | 11.4 ms: 1.01x faster                                          |

All benchmarks:
===============

| Benchmark                  | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231108-linux-x86_64-brandtbucher-justin-3.13.0a1+-d65308a |
|----------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| typing_runtime_protocols   | 153 us                                                 | 121 us: 1.27x faster                                           |
| crypto_pyaes               | 83.6 ms                                                | 73.4 ms: 1.14x faster                                          |
| comprehensions             | 20.9 us                                                | 18.5 us: 1.13x faster                                          |
| tomli_loads                | 2.30 sec                                               | 2.04 sec: 1.12x faster                                         |
| gc_traversal               | 4.28 ms                                                | 3.82 ms: 1.12x faster                                          |
| scimark_sparse_mat_mult    | 5.33 ms                                                | 4.77 ms: 1.12x faster                                          |
| logging_format             | 7.10 us                                                | 6.35 us: 1.12x faster                                          |
| logging_simple             | 6.38 us                                                | 5.74 us: 1.11x faster                                          |
| sympy_sum                  | 167 ms                                                 | 153 ms: 1.10x faster                                           |
| pickle_pure_python         | 326 us                                                 | 299 us: 1.09x faster                                           |
| raytrace                   | 308 ms                                                 | 283 ms: 1.09x faster                                           |
| sympy_str                  | 296 ms                                                 | 273 ms: 1.09x faster                                           |
| chaos                      | 67.5 ms                                                | 63.3 ms: 1.07x faster                                          |
| spectral_norm              | 115 ms                                                 | 108 ms: 1.06x faster                                           |
| async_tree_none            | 475 ms                                                 | 448 ms: 1.06x faster                                           |
| regex_compile              | 148 ms                                                 | 140 ms: 1.06x faster                                           |
| sqlglot_normalize          | 112 ms                                                 | 106 ms: 1.06x faster                                           |
| generators                 | 32.5 ms                                                | 30.9 ms: 1.05x faster                                          |
| coroutines                 | 23.5 ms                                                | 22.4 ms: 1.05x faster                                          |
| scimark_monte_carlo        | 74.6 ms                                                | 71.5 ms: 1.04x faster                                          |
| sqlglot_parse              | 1.35 ms                                                | 1.29 ms: 1.04x faster                                          |
| deepcopy_reduce            | 3.23 us                                                | 3.10 us: 1.04x faster                                          |
| tornado_http               | 101 ms                                                 | 96.7 ms: 1.04x faster                                          |
| scimark_sor                | 129 ms                                                 | 124 ms: 1.04x faster                                           |
| unpickle                   | 15.8 us                                                | 15.2 us: 1.04x faster                                          |
| sympy_integrate            | 21.2 ms                                                | 20.4 ms: 1.04x faster                                          |
| sympy_expand               | 476 ms                                                 | 459 ms: 1.04x faster                                           |
| sqlglot_transpile          | 1.68 ms                                                | 1.62 ms: 1.04x faster                                          |
| asyncio_tcp                | 506 ms                                                 | 488 ms: 1.04x faster                                           |
| docutils                   | 2.75 sec                                               | 2.66 sec: 1.03x faster                                         |
| deepcopy                   | 363 us                                                 | 351 us: 1.03x faster                                           |
| chameleon                  | 7.41 ms                                                | 7.18 ms: 1.03x faster                                          |
| scimark_fft                | 381 ms                                                 | 369 ms: 1.03x faster                                           |
| dulwich_log                | 68.7 ms                                                | 66.9 ms: 1.03x faster                                          |
| logging_silent             | 108 ns                                                 | 105 ns: 1.03x faster                                           |
| json_loads                 | 28.4 us                                                | 27.9 us: 1.02x faster                                          |
| xml_etree_generate         | 88.7 ms                                                | 87.1 ms: 1.02x faster                                          |
| unpack_sequence            | 54.2 ns                                                | 53.2 ns: 1.02x faster                                          |
| 2to3                       | 274 ms                                                 | 270 ms: 1.02x faster                                           |
| float                      | 83.3 ms                                                | 82.0 ms: 1.02x faster                                          |
| sqlite_synth               | 2.83 us                                                | 2.79 us: 1.02x faster                                          |
| xml_etree_process          | 61.2 ms                                                | 60.4 ms: 1.01x faster                                          |
| async_tree_memoization     | 580 ms                                                 | 572 ms: 1.01x faster                                           |
| mako                       | 11.5 ms                                                | 11.4 ms: 1.01x faster                                          |
| sqlglot_optimize           | 54.8 ms                                                | 54.2 ms: 1.01x faster                                          |
| unpickle_pure_python       | 230 us                                                 | 227 us: 1.01x faster                                           |
| json                       | 5.22 ms                                                | 5.17 ms: 1.01x faster                                          |
| json_dumps                 | 10.6 ms                                                | 10.5 ms: 1.01x faster                                          |
| xml_etree_parse            | 159 ms                                                 | 158 ms: 1.01x faster                                           |
| regex_effbot               | 3.57 ms                                                | 3.59 ms: 1.01x slower                                          |
| create_gc_cycles           | 1.45 ms                                                | 1.46 ms: 1.01x slower                                          |
| bench_thread_pool          | 845 us                                                 | 853 us: 1.01x slower                                           |
| asyncio_tcp_ssl            | 1.78 sec                                               | 1.80 sec: 1.01x slower                                         |
| richards                   | 46.0 ms                                                | 46.6 ms: 1.01x slower                                          |
| pathlib                    | 18.9 ms                                                | 19.2 ms: 1.02x slower                                          |
| xml_etree_iterparse        | 106 ms                                                 | 107 ms: 1.02x slower                                           |
| pprint_pformat             | 1.55 sec                                               | 1.58 sec: 1.02x slower                                         |
| nbody                      | 92.2 ms                                                | 94.2 ms: 1.02x slower                                          |
| pickle_dict                | 33.5 us                                                | 34.3 us: 1.02x slower                                          |
| async_tree_io              | 1.16 sec                                               | 1.19 sec: 1.02x slower                                         |
| nqueens                    | 86.2 ms                                                | 88.5 ms: 1.03x slower                                          |
| pycparser                  | 1.17 sec                                               | 1.20 sec: 1.03x slower                                         |
| pickle                     | 11.2 us                                                | 11.6 us: 1.03x slower                                          |
| async_tree_none_tg         | 447 ms                                                 | 464 ms: 1.04x slower                                           |
| async_tree_cpu_io_mixed_tg | 725 ms                                                 | 751 ms: 1.04x slower                                           |
| unpickle_list              | 5.04 us                                                | 5.24 us: 1.04x slower                                          |
| meteor_contest             | 110 ms                                                 | 114 ms: 1.04x slower                                           |
| pyflate                    | 471 ms                                                 | 490 ms: 1.04x slower                                           |
| pidigits                   | 187 ms                                                 | 195 ms: 1.04x slower                                           |
| async_tree_io_tg           | 1.19 sec                                               | 1.24 sec: 1.04x slower                                         |
| go                         | 140 ms                                                 | 147 ms: 1.05x slower                                           |
| async_tree_memoization_tg  | 574 ms                                                 | 604 ms: 1.05x slower                                           |
| pickle_list                | 4.67 us                                                | 4.97 us: 1.06x slower                                          |
| regex_dna                  | 209 ms                                                 | 223 ms: 1.07x slower                                           |
| hexiom                     | 6.54 ms                                                | 7.04 ms: 1.08x slower                                          |
| python_startup             | 9.53 ms                                                | 10.4 ms: 1.09x slower                                          |
| mdp                        | 2.57 sec                                               | 2.82 sec: 1.10x slower                                         |
| regex_v8                   | 22.7 ms                                                | 25.8 ms: 1.14x slower                                          |
| telco                      | 7.18 ms                                                | 8.27 ms: 1.15x slower                                          |
| coverage                   | 75.1 ms                                                | 94.5 ms: 1.26x slower                                          |
| python_startup_no_site     | 6.92 ms                                                | 9.07 ms: 1.31x slower                                          |
| Geometric mean             | (ref)                                                  | 1.01x faster                                                   |

Benchmark hidden because not significant (11): scimark_lu, async_tree_cpu_io_mixed, mypy2, pprint_safe_repr, asyncio_websockets, deltablue, fannkuch, async_generators, bench_mp_pool, richards_super, deepcopy_memo
Ignored benchmarks (6) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, dask, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 82.70% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
