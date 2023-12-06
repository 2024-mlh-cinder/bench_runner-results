
# Results vs. 3.12.0

- fork: brandtbucher
- ref: justin
- machine: linux-x86_64
- commit hash: 7bb54b5
- commit date: 2023-11-20
- overall geometric mean: 1.04x slower \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.02x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-pythonperf2-x86_64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|----------------|:------------------------------------------------------------:|:--------------------------------------------------------------------:|
| 2to3           | 285 ms                                                       | 302 ms: 1.06x slower                                                 |
| chameleon      | 7.27 ms                                                      | 7.53 ms: 1.04x slower                                                |
| docutils       | 2.89 sec                                                     | 2.87 sec: 1.01x faster                                               |
| Geometric mean | (ref)                                                        | 1.02x slower                                                         |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-pythonperf2-x86_64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|----------------------------|:------------------------------------------------------------:|:--------------------------------------------------------------------:|
| async_tree_none            | 459 ms                                                       | 441 ms: 1.04x faster                                                 |
| async_tree_none_tg         | 440 ms                                                       | 447 ms: 1.02x slower                                                 |
| async_tree_cpu_io_mixed_tg | 706 ms                                                       | 720 ms: 1.02x slower                                                 |
| async_tree_io              | 1.06 sec                                                     | 1.09 sec: 1.03x slower                                               |
| async_tree_io_tg           | 1.07 sec                                                     | 1.10 sec: 1.03x slower                                               |
| async_tree_memoization_tg  | 554 ms                                                       | 578 ms: 1.04x slower                                                 |
| Geometric mean             | (ref)                                                        | 1.01x slower                                                         |

Benchmark hidden because not significant (2): async_tree_memoization, async_tree_cpu_io_mixed

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-pythonperf2-x86_64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|----------------|:------------------------------------------------------------:|:--------------------------------------------------------------------:|
| pidigits       | 264 ms                                                       | 265 ms: 1.00x slower                                                 |
| nbody          | 88.2 ms                                                      | 94.4 ms: 1.07x slower                                                |
| Geometric mean | (ref)                                                        | 1.02x slower                                                         |

Benchmark hidden because not significant (1): float

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-pythonperf2-x86_64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|----------------|:------------------------------------------------------------:|:--------------------------------------------------------------------:|
| regex_effbot   | 3.61 ms                                                      | 3.57 ms: 1.01x faster                                                |
| regex_dna      | 240 ms                                                       | 240 ms: 1.00x faster                                                 |
| regex_compile  | 145 ms                                                       | 150 ms: 1.03x slower                                                 |
| regex_v8       | 24.4 ms                                                      | 25.5 ms: 1.04x slower                                                |
| Geometric mean | (ref)                                                        | 1.02x slower                                                         |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-pythonperf2-x86_64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|----------------------|:------------------------------------------------------------:|:--------------------------------------------------------------------:|
| unpickle             | 15.3 us                                                      | 14.9 us: 1.03x faster                                                |
| pickle_pure_python   | 319 us                                                       | 316 us: 1.01x faster                                                 |
| pickle               | 10.0 us                                                      | 9.99 us: 1.01x faster                                                |
| xml_etree_parse      | 147 ms                                                       | 148 ms: 1.01x slower                                                 |
| unpickle_list        | 4.65 us                                                      | 4.69 us: 1.01x slower                                                |
| xml_etree_generate   | 85.3 ms                                                      | 86.8 ms: 1.02x slower                                                |
| xml_etree_process    | 58.3 ms                                                      | 59.7 ms: 1.02x slower                                                |
| xml_etree_iterparse  | 104 ms                                                       | 106 ms: 1.02x slower                                                 |
| pickle_dict          | 32.0 us                                                      | 33.3 us: 1.04x slower                                                |
| json_dumps           | 10.3 ms                                                      | 10.8 ms: 1.05x slower                                                |
| tomli_loads          | 2.17 sec                                                     | 2.29 sec: 1.06x slower                                               |
| json_loads           | 24.3 us                                                      | 25.7 us: 1.06x slower                                                |
| unpickle_pure_python | 210 us                                                       | 227 us: 1.08x slower                                                 |
| Geometric mean       | (ref)                                                        | 1.02x slower                                                         |

Benchmark hidden because not significant (1): pickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-pythonperf2-x86_64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|------------------------|:------------------------------------------------------------:|:--------------------------------------------------------------------:|
| python_startup         | 11.7 ms                                                      | 12.9 ms: 1.11x slower                                                |
| python_startup_no_site | 8.67 ms                                                      | 11.4 ms: 1.31x slower                                                |
| Geometric mean         | (ref)                                                        | 1.20x slower                                                         |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-pythonperf2-x86_64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|-----------|:------------------------------------------------------------:|:--------------------------------------------------------------------:|
| mako      | 10.1 ms                                                      | 11.0 ms: 1.10x slower                                                |

All benchmarks:
===============

| Benchmark                  | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-pythonperf2-x86_64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|----------------------------|:------------------------------------------------------------:|:--------------------------------------------------------------------:|
| typing_runtime_protocols   | 150 us                                                       | 129 us: 1.16x faster                                                 |
| unpack_sequence            | 54.5 ns                                                      | 48.0 ns: 1.13x faster                                                |
| comprehensions             | 21.8 us                                                      | 20.3 us: 1.07x faster                                                |
| raytrace                   | 301 ms                                                       | 288 ms: 1.04x faster                                                 |
| async_tree_none            | 459 ms                                                       | 441 ms: 1.04x faster                                                 |
| asyncio_tcp                | 380 ms                                                       | 366 ms: 1.04x faster                                                 |
| generators                 | 37.3 ms                                                      | 36.0 ms: 1.04x faster                                                |
| scimark_sparse_mat_mult    | 4.49 ms                                                      | 4.35 ms: 1.03x faster                                                |
| deepcopy_reduce            | 3.41 us                                                      | 3.31 us: 1.03x faster                                                |
| unpickle                   | 15.3 us                                                      | 14.9 us: 1.03x faster                                                |
| coroutines                 | 23.1 ms                                                      | 22.6 ms: 1.02x faster                                                |
| sympy_sum                  | 163 ms                                                       | 160 ms: 1.02x faster                                                 |
| deepcopy                   | 371 us                                                       | 366 us: 1.01x faster                                                 |
| crypto_pyaes               | 82.4 ms                                                      | 81.3 ms: 1.01x faster                                                |
| logging_format             | 7.29 us                                                      | 7.20 us: 1.01x faster                                                |
| regex_effbot               | 3.61 ms                                                      | 3.57 ms: 1.01x faster                                                |
| sympy_str                  | 305 ms                                                       | 302 ms: 1.01x faster                                                 |
| pickle_pure_python         | 319 us                                                       | 316 us: 1.01x faster                                                 |
| docutils                   | 2.89 sec                                                     | 2.87 sec: 1.01x faster                                               |
| pickle                     | 10.0 us                                                      | 9.99 us: 1.01x faster                                                |
| regex_dna                  | 240 ms                                                       | 240 ms: 1.00x faster                                                 |
| asyncio_tcp_ssl            | 1.57 sec                                                     | 1.57 sec: 1.00x slower                                               |
| pidigits                   | 264 ms                                                       | 265 ms: 1.00x slower                                                 |
| xml_etree_parse            | 147 ms                                                       | 148 ms: 1.01x slower                                                 |
| unpickle_list              | 4.65 us                                                      | 4.69 us: 1.01x slower                                                |
| sympy_integrate            | 24.0 ms                                                      | 24.4 ms: 1.01x slower                                                |
| deepcopy_memo              | 36.6 us                                                      | 37.1 us: 1.01x slower                                                |
| async_tree_none_tg         | 440 ms                                                       | 447 ms: 1.02x slower                                                 |
| pathlib                    | 18.7 ms                                                      | 19.1 ms: 1.02x slower                                                |
| sqlglot_parse              | 1.41 ms                                                      | 1.43 ms: 1.02x slower                                                |
| xml_etree_generate         | 85.3 ms                                                      | 86.8 ms: 1.02x slower                                                |
| mdp                        | 2.56 sec                                                     | 2.61 sec: 1.02x slower                                               |
| async_tree_cpu_io_mixed_tg | 706 ms                                                       | 720 ms: 1.02x slower                                                 |
| sqlglot_normalize          | 119 ms                                                       | 122 ms: 1.02x slower                                                 |
| xml_etree_process          | 58.3 ms                                                      | 59.7 ms: 1.02x slower                                                |
| pycparser                  | 1.29 sec                                                     | 1.33 sec: 1.02x slower                                               |
| xml_etree_iterparse        | 104 ms                                                       | 106 ms: 1.02x slower                                                 |
| async_generators           | 385 ms                                                       | 395 ms: 1.03x slower                                                 |
| dask                       | 394 ms                                                       | 404 ms: 1.03x slower                                                 |
| async_tree_io              | 1.06 sec                                                     | 1.09 sec: 1.03x slower                                               |
| sympy_expand               | 492 ms                                                       | 506 ms: 1.03x slower                                                 |
| json                       | 5.17 ms                                                      | 5.32 ms: 1.03x slower                                                |
| sqlglot_transpile          | 1.80 ms                                                      | 1.86 ms: 1.03x slower                                                |
| async_tree_io_tg           | 1.07 sec                                                     | 1.10 sec: 1.03x slower                                               |
| regex_compile              | 145 ms                                                       | 150 ms: 1.03x slower                                                 |
| chameleon                  | 7.27 ms                                                      | 7.53 ms: 1.04x slower                                                |
| pickle_dict                | 32.0 us                                                      | 33.3 us: 1.04x slower                                                |
| meteor_contest             | 126 ms                                                       | 132 ms: 1.04x slower                                                 |
| mypy2                      | 365 ms                                                       | 380 ms: 1.04x slower                                                 |
| dulwich_log                | 64.9 ms                                                      | 67.7 ms: 1.04x slower                                                |
| regex_v8                   | 24.4 ms                                                      | 25.5 ms: 1.04x slower                                                |
| async_tree_memoization_tg  | 554 ms                                                       | 578 ms: 1.04x slower                                                 |
| json_dumps                 | 10.3 ms                                                      | 10.8 ms: 1.05x slower                                                |
| scimark_lu                 | 98.6 ms                                                      | 104 ms: 1.05x slower                                                 |
| pprint_safe_repr           | 808 ms                                                       | 850 ms: 1.05x slower                                                 |
| sqlglot_optimize           | 58.4 ms                                                      | 61.7 ms: 1.06x slower                                                |
| tomli_loads                | 2.17 sec                                                     | 2.29 sec: 1.06x slower                                               |
| json_loads                 | 24.3 us                                                      | 25.7 us: 1.06x slower                                                |
| pprint_pformat             | 1.64 sec                                                     | 1.74 sec: 1.06x slower                                               |
| logging_silent             | 93.3 ns                                                      | 99.0 ns: 1.06x slower                                                |
| gc_traversal               | 3.70 ms                                                      | 3.93 ms: 1.06x slower                                                |
| 2to3                       | 285 ms                                                       | 302 ms: 1.06x slower                                                 |
| nbody                      | 88.2 ms                                                      | 94.4 ms: 1.07x slower                                                |
| spectral_norm              | 93.9 ms                                                      | 101 ms: 1.08x slower                                                 |
| unpickle_pure_python       | 210 us                                                       | 227 us: 1.08x slower                                                 |
| mako                       | 10.1 ms                                                      | 11.0 ms: 1.10x slower                                                |
| chaos                      | 64.1 ms                                                      | 70.3 ms: 1.10x slower                                                |
| richards_super             | 50.8 ms                                                      | 56.1 ms: 1.10x slower                                                |
| python_startup             | 11.7 ms                                                      | 12.9 ms: 1.11x slower                                                |
| richards                   | 45.1 ms                                                      | 49.9 ms: 1.11x slower                                                |
| scimark_monte_carlo        | 69.5 ms                                                      | 78.4 ms: 1.13x slower                                                |
| go                         | 149 ms                                                       | 168 ms: 1.13x slower                                                 |
| nqueens                    | 90.1 ms                                                      | 103 ms: 1.14x slower                                                 |
| deltablue                  | 3.24 ms                                                      | 3.71 ms: 1.14x slower                                                |
| fannkuch                   | 362 ms                                                       | 414 ms: 1.15x slower                                                 |
| pyflate                    | 442 ms                                                       | 515 ms: 1.16x slower                                                 |
| telco                      | 7.16 ms                                                      | 8.36 ms: 1.17x slower                                                |
| coverage                   | 66.3 ms                                                      | 79.9 ms: 1.21x slower                                                |
| scimark_fft                | 303 ms                                                       | 375 ms: 1.24x slower                                                 |
| hexiom                     | 5.97 ms                                                      | 7.82 ms: 1.31x slower                                                |
| python_startup_no_site     | 8.67 ms                                                      | 11.4 ms: 1.31x slower                                                |
| scimark_sor                | 107 ms                                                       | 148 ms: 1.38x slower                                                 |
| Geometric mean             | (ref)                                                        | 1.04x slower                                                         |

Benchmark hidden because not significant (11): bench_mp_pool, float, logging_simple, tornado_http, sqlite_synth, async_tree_memoization, asyncio_websockets, create_gc_cycles, async_tree_cpu_io_mixed, pickle_list, bench_thread_pool
Ignored benchmarks (5) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.02x
- 95% likely to have a slowdown of 1.02x
- 99% likely to have a slowdown of 1.02x
