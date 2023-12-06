
# Results vs. 3.12.0

- fork: brandtbucher
- ref: justin
- machine: linux-x86_64
- commit hash: 7bb54b5
- commit date: 2023-11-20
- overall geometric mean: 1.01x slower \*
- HPT reliability: 94.68%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-linux-x86_64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| chameleon      | 7.41 ms                                                | 7.12 ms: 1.04x faster                                          |
| docutils       | 2.75 sec                                               | 2.65 sec: 1.04x faster                                         |
| tornado_http   | 101 ms                                                 | 96.9 ms: 1.04x faster                                          |
| Geometric mean | (ref)                                                  | 1.03x faster                                                   |

Benchmark hidden because not significant (1): 2to3

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-linux-x86_64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|----------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| async_tree_none            | 475 ms                                                 | 448 ms: 1.06x faster                                           |
| async_tree_memoization     | 580 ms                                                 | 574 ms: 1.01x faster                                           |
| async_tree_cpu_io_mixed_tg | 725 ms                                                 | 750 ms: 1.03x slower                                           |
| async_tree_io              | 1.16 sec                                               | 1.20 sec: 1.04x slower                                         |
| async_tree_none_tg         | 447 ms                                                 | 464 ms: 1.04x slower                                           |
| async_tree_io_tg           | 1.19 sec                                               | 1.24 sec: 1.04x slower                                         |
| async_tree_memoization_tg  | 574 ms                                                 | 610 ms: 1.06x slower                                           |
| Geometric mean             | (ref)                                                  | 1.02x slower                                                   |

Benchmark hidden because not significant (1): async_tree_cpu_io_mixed

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-linux-x86_64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| float          | 83.3 ms                                                | 86.6 ms: 1.04x slower                                          |
| pidigits       | 187 ms                                                 | 195 ms: 1.04x slower                                           |
| nbody          | 92.2 ms                                                | 101 ms: 1.10x slower                                           |
| Geometric mean | (ref)                                                  | 1.06x slower                                                   |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-linux-x86_64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| regex_compile  | 148 ms                                                 | 142 ms: 1.04x faster                                           |
| regex_effbot   | 3.57 ms                                                | 3.60 ms: 1.01x slower                                          |
| regex_dna      | 209 ms                                                 | 221 ms: 1.06x slower                                           |
| regex_v8       | 22.7 ms                                                | 24.6 ms: 1.09x slower                                          |
| Geometric mean | (ref)                                                  | 1.03x slower                                                   |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-linux-x86_64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|----------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| pickle_pure_python   | 326 us                                                 | 305 us: 1.07x faster                                           |
| tomli_loads          | 2.30 sec                                               | 2.20 sec: 1.05x faster                                         |
| json_loads           | 28.4 us                                                | 28.0 us: 1.01x faster                                          |
| json_dumps           | 10.6 ms                                                | 10.5 ms: 1.01x faster                                          |
| xml_etree_generate   | 88.7 ms                                                | 89.8 ms: 1.01x slower                                          |
| unpickle_pure_python | 230 us                                                 | 232 us: 1.01x slower                                           |
| pickle               | 11.2 us                                                | 11.4 us: 1.02x slower                                          |
| xml_etree_iterparse  | 106 ms                                                 | 110 ms: 1.04x slower                                           |
| unpickle_list        | 5.04 us                                                | 5.32 us: 1.05x slower                                          |
| pickle_dict          | 33.5 us                                                | 35.7 us: 1.07x slower                                          |
| pickle_list          | 4.67 us                                                | 5.00 us: 1.07x slower                                          |
| Geometric mean       | (ref)                                                  | 1.01x slower                                                   |

Benchmark hidden because not significant (3): xml_etree_process, xml_etree_parse, unpickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-linux-x86_64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| python_startup         | 9.53 ms                                                | 10.5 ms: 1.10x slower                                          |
| python_startup_no_site | 6.92 ms                                                | 9.14 ms: 1.32x slower                                          |
| Geometric mean         | (ref)                                                  | 1.21x slower                                                   |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-linux-x86_64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|-----------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| mako      | 11.5 ms                                                | 12.4 ms: 1.08x slower                                          |

All benchmarks:
===============

| Benchmark                  | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-linux-x86_64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|----------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| typing_runtime_protocols   | 153 us                                                 | 121 us: 1.26x faster                                           |
| unpack_sequence            | 54.2 ns                                                | 44.3 ns: 1.22x faster                                          |
| logging_format             | 7.10 us                                                | 6.43 us: 1.10x faster                                          |
| generators                 | 32.5 ms                                                | 29.8 ms: 1.09x faster                                          |
| logging_simple             | 6.38 us                                                | 5.87 us: 1.09x faster                                          |
| comprehensions             | 20.9 us                                                | 19.3 us: 1.09x faster                                          |
| gc_traversal               | 4.28 ms                                                | 3.95 ms: 1.08x faster                                          |
| pickle_pure_python         | 326 us                                                 | 305 us: 1.07x faster                                           |
| raytrace                   | 308 ms                                                 | 288 ms: 1.07x faster                                           |
| coroutines                 | 23.5 ms                                                | 22.0 ms: 1.07x faster                                          |
| crypto_pyaes               | 83.6 ms                                                | 78.3 ms: 1.07x faster                                          |
| sympy_sum                  | 167 ms                                                 | 157 ms: 1.07x faster                                           |
| async_tree_none            | 475 ms                                                 | 448 ms: 1.06x faster                                           |
| sympy_str                  | 296 ms                                                 | 282 ms: 1.05x faster                                           |
| tomli_loads                | 2.30 sec                                               | 2.20 sec: 1.05x faster                                         |
| regex_compile              | 148 ms                                                 | 142 ms: 1.04x faster                                           |
| chameleon                  | 7.41 ms                                                | 7.12 ms: 1.04x faster                                          |
| docutils                   | 2.75 sec                                               | 2.65 sec: 1.04x faster                                         |
| tornado_http               | 101 ms                                                 | 96.9 ms: 1.04x faster                                          |
| dulwich_log                | 68.7 ms                                                | 66.4 ms: 1.04x faster                                          |
| scimark_sor                | 129 ms                                                 | 125 ms: 1.03x faster                                           |
| deepcopy_reduce            | 3.23 us                                                | 3.13 us: 1.03x faster                                          |
| asyncio_tcp                | 506 ms                                                 | 494 ms: 1.02x faster                                           |
| scimark_lu                 | 120 ms                                                 | 118 ms: 1.02x faster                                           |
| sqlglot_normalize          | 112 ms                                                 | 109 ms: 1.02x faster                                           |
| json                       | 5.22 ms                                                | 5.13 ms: 1.02x faster                                          |
| sqlglot_transpile          | 1.68 ms                                                | 1.65 ms: 1.02x faster                                          |
| sqlglot_parse              | 1.35 ms                                                | 1.33 ms: 1.02x faster                                          |
| sympy_integrate            | 21.2 ms                                                | 20.9 ms: 1.02x faster                                          |
| pathlib                    | 18.9 ms                                                | 18.6 ms: 1.01x faster                                          |
| json_loads                 | 28.4 us                                                | 28.0 us: 1.01x faster                                          |
| chaos                      | 67.5 ms                                                | 66.8 ms: 1.01x faster                                          |
| sympy_expand               | 476 ms                                                 | 471 ms: 1.01x faster                                           |
| async_tree_memoization     | 580 ms                                                 | 574 ms: 1.01x faster                                           |
| json_dumps                 | 10.6 ms                                                | 10.5 ms: 1.01x faster                                          |
| mypy2                      | 351 ms                                                 | 352 ms: 1.00x slower                                           |
| regex_effbot               | 3.57 ms                                                | 3.60 ms: 1.01x slower                                          |
| bench_thread_pool          | 845 us                                                 | 852 us: 1.01x slower                                           |
| scimark_fft                | 381 ms                                                 | 384 ms: 1.01x slower                                           |
| scimark_sparse_mat_mult    | 5.33 ms                                                | 5.39 ms: 1.01x slower                                          |
| pprint_pformat             | 1.55 sec                                               | 1.57 sec: 1.01x slower                                         |
| xml_etree_generate         | 88.7 ms                                                | 89.8 ms: 1.01x slower                                          |
| unpickle_pure_python       | 230 us                                                 | 232 us: 1.01x slower                                           |
| async_generators           | 459 ms                                                 | 465 ms: 1.01x slower                                           |
| sqlglot_optimize           | 54.8 ms                                                | 55.6 ms: 1.01x slower                                          |
| richards                   | 46.0 ms                                                | 46.7 ms: 1.01x slower                                          |
| scimark_monte_carlo        | 74.6 ms                                                | 75.7 ms: 1.01x slower                                          |
| asyncio_tcp_ssl            | 1.78 sec                                               | 1.81 sec: 1.01x slower                                         |
| deepcopy_memo              | 39.7 us                                                | 40.3 us: 1.01x slower                                          |
| pickle                     | 11.2 us                                                | 11.4 us: 1.02x slower                                          |
| meteor_contest             | 110 ms                                                 | 111 ms: 1.02x slower                                           |
| create_gc_cycles           | 1.45 ms                                                | 1.48 ms: 1.02x slower                                          |
| logging_silent             | 108 ns                                                 | 110 ns: 1.02x slower                                           |
| async_tree_cpu_io_mixed_tg | 725 ms                                                 | 750 ms: 1.03x slower                                           |
| async_tree_io              | 1.16 sec                                               | 1.20 sec: 1.04x slower                                         |
| xml_etree_iterparse        | 106 ms                                                 | 110 ms: 1.04x slower                                           |
| async_tree_none_tg         | 447 ms                                                 | 464 ms: 1.04x slower                                           |
| float                      | 83.3 ms                                                | 86.6 ms: 1.04x slower                                          |
| async_tree_io_tg           | 1.19 sec                                               | 1.24 sec: 1.04x slower                                         |
| pidigits                   | 187 ms                                                 | 195 ms: 1.04x slower                                           |
| fannkuch                   | 410 ms                                                 | 430 ms: 1.05x slower                                           |
| unpickle_list              | 5.04 us                                                | 5.32 us: 1.05x slower                                          |
| nqueens                    | 86.2 ms                                                | 91.1 ms: 1.06x slower                                          |
| pyflate                    | 471 ms                                                 | 498 ms: 1.06x slower                                           |
| regex_dna                  | 209 ms                                                 | 221 ms: 1.06x slower                                           |
| async_tree_memoization_tg  | 574 ms                                                 | 610 ms: 1.06x slower                                           |
| pickle_dict                | 33.5 us                                                | 35.7 us: 1.07x slower                                          |
| pickle_list                | 4.67 us                                                | 5.00 us: 1.07x slower                                          |
| go                         | 140 ms                                                 | 151 ms: 1.07x slower                                           |
| mako                       | 11.5 ms                                                | 12.4 ms: 1.08x slower                                          |
| regex_v8                   | 22.7 ms                                                | 24.6 ms: 1.09x slower                                          |
| deltablue                  | 3.71 ms                                                | 4.05 ms: 1.09x slower                                          |
| mdp                        | 2.57 sec                                               | 2.82 sec: 1.10x slower                                         |
| python_startup             | 9.53 ms                                                | 10.5 ms: 1.10x slower                                          |
| nbody                      | 92.2 ms                                                | 101 ms: 1.10x slower                                           |
| hexiom                     | 6.54 ms                                                | 7.53 ms: 1.15x slower                                          |
| telco                      | 7.18 ms                                                | 8.35 ms: 1.16x slower                                          |
| spectral_norm              | 115 ms                                                 | 138 ms: 1.20x slower                                           |
| coverage                   | 75.1 ms                                                | 96.2 ms: 1.28x slower                                          |
| python_startup_no_site     | 6.92 ms                                                | 9.14 ms: 1.32x slower                                          |
| Geometric mean             | (ref)                                                  | 1.01x slower                                                   |

Benchmark hidden because not significant (13): dask, async_tree_cpu_io_mixed, sqlite_synth, pycparser, deepcopy, richards_super, xml_etree_process, pprint_safe_repr, 2to3, asyncio_websockets, bench_mp_pool, xml_etree_parse, unpickle
Ignored benchmarks (5) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 94.68% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
