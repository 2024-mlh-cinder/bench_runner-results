
# Results vs. 3.12.0

- fork: brandtbucher
- ref: justin
- machine: linux-x86_64
- commit hash: 7bb54b5
- commit date: 2023-11-20
- overall geometric mean: 1.03x slower \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.01x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-pythonperf2-x86_64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|----------------|:------------------------------------------------------------:|:--------------------------------------------------------------------:|
| 2to3           | 285 ms                                                       | 300 ms: 1.06x slower                                                 |
| chameleon      | 7.27 ms                                                      | 7.58 ms: 1.04x slower                                                |
| docutils       | 2.89 sec                                                     | 2.88 sec: 1.01x faster                                               |
| Geometric mean | (ref)                                                        | 1.02x slower                                                         |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-pythonperf2-x86_64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|----------------------------|:------------------------------------------------------------:|:--------------------------------------------------------------------:|
| async_tree_none            | 459 ms                                                       | 439 ms: 1.05x faster                                                 |
| async_tree_none_tg         | 440 ms                                                       | 446 ms: 1.01x slower                                                 |
| async_tree_cpu_io_mixed_tg | 706 ms                                                       | 719 ms: 1.02x slower                                                 |
| async_tree_io              | 1.06 sec                                                     | 1.08 sec: 1.03x slower                                               |
| async_tree_io_tg           | 1.07 sec                                                     | 1.10 sec: 1.03x slower                                               |
| async_tree_memoization_tg  | 554 ms                                                       | 575 ms: 1.04x slower                                                 |
| Geometric mean             | (ref)                                                        | 1.01x slower                                                         |

Benchmark hidden because not significant (2): async_tree_memoization, async_tree_cpu_io_mixed

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-pythonperf2-x86_64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|----------------|:------------------------------------------------------------:|:--------------------------------------------------------------------:|
| float          | 81.6 ms                                                      | 79.1 ms: 1.03x faster                                                |
| pidigits       | 264 ms                                                       | 265 ms: 1.00x slower                                                 |
| nbody          | 88.2 ms                                                      | 96.3 ms: 1.09x slower                                                |
| Geometric mean | (ref)                                                        | 1.02x slower                                                         |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-pythonperf2-x86_64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|----------------|:------------------------------------------------------------:|:--------------------------------------------------------------------:|
| regex_effbot   | 3.61 ms                                                      | 3.53 ms: 1.02x faster                                                |
| regex_dna      | 240 ms                                                       | 244 ms: 1.02x slower                                                 |
| regex_compile  | 145 ms                                                       | 150 ms: 1.04x slower                                                 |
| regex_v8       | 24.4 ms                                                      | 25.7 ms: 1.05x slower                                                |
| Geometric mean | (ref)                                                        | 1.02x slower                                                         |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-pythonperf2-x86_64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|----------------------|:------------------------------------------------------------:|:--------------------------------------------------------------------:|
| unpickle             | 15.3 us                                                      | 14.7 us: 1.05x faster                                                |
| pickle_pure_python   | 319 us                                                       | 308 us: 1.04x faster                                                 |
| xml_etree_parse      | 147 ms                                                       | 143 ms: 1.03x faster                                                 |
| unpickle_list        | 4.65 us                                                      | 4.54 us: 1.02x faster                                                |
| pickle_dict          | 32.0 us                                                      | 31.6 us: 1.01x faster                                                |
| xml_etree_generate   | 85.3 ms                                                      | 86.1 ms: 1.01x slower                                                |
| xml_etree_iterparse  | 104 ms                                                       | 105 ms: 1.01x slower                                                 |
| xml_etree_process    | 58.3 ms                                                      | 59.1 ms: 1.01x slower                                                |
| pickle               | 10.0 us                                                      | 10.2 us: 1.02x slower                                                |
| json_loads           | 24.3 us                                                      | 25.3 us: 1.04x slower                                                |
| tomli_loads          | 2.17 sec                                                     | 2.28 sec: 1.05x slower                                               |
| unpickle_pure_python | 210 us                                                       | 221 us: 1.05x slower                                                 |
| json_dumps           | 10.3 ms                                                      | 10.8 ms: 1.05x slower                                                |
| pickle_list          | 4.22 us                                                      | 4.48 us: 1.06x slower                                                |
| Geometric mean       | (ref)                                                        | 1.01x slower                                                         |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-pythonperf2-x86_64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|------------------------|:------------------------------------------------------------:|:--------------------------------------------------------------------:|
| python_startup         | 11.7 ms                                                      | 12.9 ms: 1.10x slower                                                |
| python_startup_no_site | 8.67 ms                                                      | 11.3 ms: 1.31x slower                                                |
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
| unpack_sequence            | 54.5 ns                                                      | 43.9 ns: 1.24x faster                                                |
| typing_runtime_protocols   | 150 us                                                       | 130 us: 1.15x faster                                                 |
| gc_traversal               | 3.70 ms                                                      | 3.42 ms: 1.08x faster                                                |
| comprehensions             | 21.8 us                                                      | 20.2 us: 1.08x faster                                                |
| unpickle                   | 15.3 us                                                      | 14.7 us: 1.05x faster                                                |
| async_tree_none            | 459 ms                                                       | 439 ms: 1.05x faster                                                 |
| generators                 | 37.3 ms                                                      | 35.7 ms: 1.04x faster                                                |
| raytrace                   | 301 ms                                                       | 288 ms: 1.04x faster                                                 |
| pickle_pure_python         | 319 us                                                       | 308 us: 1.04x faster                                                 |
| float                      | 81.6 ms                                                      | 79.1 ms: 1.03x faster                                                |
| asyncio_tcp                | 380 ms                                                       | 369 ms: 1.03x faster                                                 |
| create_gc_cycles           | 1.58 ms                                                      | 1.54 ms: 1.03x faster                                                |
| deepcopy_reduce            | 3.41 us                                                      | 3.32 us: 1.03x faster                                                |
| xml_etree_parse            | 147 ms                                                       | 143 ms: 1.03x faster                                                 |
| unpickle_list              | 4.65 us                                                      | 4.54 us: 1.02x faster                                                |
| sympy_sum                  | 163 ms                                                       | 159 ms: 1.02x faster                                                 |
| regex_effbot               | 3.61 ms                                                      | 3.53 ms: 1.02x faster                                                |
| sympy_str                  | 305 ms                                                       | 301 ms: 1.02x faster                                                 |
| coroutines                 | 23.1 ms                                                      | 22.8 ms: 1.01x faster                                                |
| pickle_dict                | 32.0 us                                                      | 31.6 us: 1.01x faster                                                |
| crypto_pyaes               | 82.4 ms                                                      | 81.7 ms: 1.01x faster                                                |
| deepcopy                   | 371 us                                                       | 369 us: 1.01x faster                                                 |
| docutils                   | 2.89 sec                                                     | 2.88 sec: 1.01x faster                                               |
| pidigits                   | 264 ms                                                       | 265 ms: 1.00x slower                                                 |
| sqlglot_normalize          | 119 ms                                                       | 120 ms: 1.01x slower                                                 |
| async_generators           | 385 ms                                                       | 388 ms: 1.01x slower                                                 |
| pathlib                    | 18.7 ms                                                      | 18.9 ms: 1.01x slower                                                |
| deepcopy_memo              | 36.6 us                                                      | 36.9 us: 1.01x slower                                                |
| xml_etree_generate         | 85.3 ms                                                      | 86.1 ms: 1.01x slower                                                |
| sympy_integrate            | 24.0 ms                                                      | 24.3 ms: 1.01x slower                                                |
| json                       | 5.17 ms                                                      | 5.23 ms: 1.01x slower                                                |
| sqlglot_parse              | 1.41 ms                                                      | 1.42 ms: 1.01x slower                                                |
| xml_etree_iterparse        | 104 ms                                                       | 105 ms: 1.01x slower                                                 |
| xml_etree_process          | 58.3 ms                                                      | 59.1 ms: 1.01x slower                                                |
| async_tree_none_tg         | 440 ms                                                       | 446 ms: 1.01x slower                                                 |
| regex_dna                  | 240 ms                                                       | 244 ms: 1.02x slower                                                 |
| pickle                     | 10.0 us                                                      | 10.2 us: 1.02x slower                                                |
| pycparser                  | 1.29 sec                                                     | 1.32 sec: 1.02x slower                                               |
| async_tree_cpu_io_mixed_tg | 706 ms                                                       | 719 ms: 1.02x slower                                                 |
| mdp                        | 2.56 sec                                                     | 2.61 sec: 1.02x slower                                               |
| sqlglot_transpile          | 1.80 ms                                                      | 1.84 ms: 1.02x slower                                                |
| logging_format             | 7.29 us                                                      | 7.46 us: 1.02x slower                                                |
| dask                       | 394 ms                                                       | 403 ms: 1.02x slower                                                 |
| sympy_expand               | 492 ms                                                       | 504 ms: 1.02x slower                                                 |
| async_tree_io              | 1.06 sec                                                     | 1.08 sec: 1.03x slower                                               |
| async_tree_io_tg           | 1.07 sec                                                     | 1.10 sec: 1.03x slower                                               |
| regex_compile              | 145 ms                                                       | 150 ms: 1.04x slower                                                 |
| async_tree_memoization_tg  | 554 ms                                                       | 575 ms: 1.04x slower                                                 |
| json_loads                 | 24.3 us                                                      | 25.3 us: 1.04x slower                                                |
| meteor_contest             | 126 ms                                                       | 132 ms: 1.04x slower                                                 |
| mypy2                      | 365 ms                                                       | 381 ms: 1.04x slower                                                 |
| chameleon                  | 7.27 ms                                                      | 7.58 ms: 1.04x slower                                                |
| scimark_lu                 | 98.6 ms                                                      | 103 ms: 1.05x slower                                                 |
| logging_silent             | 93.3 ns                                                      | 97.7 ns: 1.05x slower                                                |
| tomli_loads                | 2.17 sec                                                     | 2.28 sec: 1.05x slower                                               |
| dulwich_log                | 64.9 ms                                                      | 68.2 ms: 1.05x slower                                                |
| unpickle_pure_python       | 210 us                                                       | 221 us: 1.05x slower                                                 |
| json_dumps                 | 10.3 ms                                                      | 10.8 ms: 1.05x slower                                                |
| regex_v8                   | 24.4 ms                                                      | 25.7 ms: 1.05x slower                                                |
| pprint_safe_repr           | 808 ms                                                       | 852 ms: 1.05x slower                                                 |
| sqlglot_optimize           | 58.4 ms                                                      | 61.6 ms: 1.05x slower                                                |
| 2to3                       | 285 ms                                                       | 300 ms: 1.06x slower                                                 |
| pprint_pformat             | 1.64 sec                                                     | 1.74 sec: 1.06x slower                                               |
| pickle_list                | 4.22 us                                                      | 4.48 us: 1.06x slower                                                |
| chaos                      | 64.1 ms                                                      | 69.6 ms: 1.09x slower                                                |
| spectral_norm              | 93.9 ms                                                      | 102 ms: 1.09x slower                                                 |
| nbody                      | 88.2 ms                                                      | 96.3 ms: 1.09x slower                                                |
| mako                       | 10.1 ms                                                      | 11.0 ms: 1.10x slower                                                |
| python_startup             | 11.7 ms                                                      | 12.9 ms: 1.10x slower                                                |
| richards                   | 45.1 ms                                                      | 50.2 ms: 1.11x slower                                                |
| nqueens                    | 90.1 ms                                                      | 101 ms: 1.12x slower                                                 |
| richards_super             | 50.8 ms                                                      | 57.0 ms: 1.12x slower                                                |
| go                         | 149 ms                                                       | 168 ms: 1.13x slower                                                 |
| scimark_monte_carlo        | 69.5 ms                                                      | 79.0 ms: 1.14x slower                                                |
| deltablue                  | 3.24 ms                                                      | 3.69 ms: 1.14x slower                                                |
| fannkuch                   | 362 ms                                                       | 413 ms: 1.14x slower                                                 |
| telco                      | 7.16 ms                                                      | 8.29 ms: 1.16x slower                                                |
| pyflate                    | 442 ms                                                       | 520 ms: 1.18x slower                                                 |
| scimark_fft                | 303 ms                                                       | 364 ms: 1.20x slower                                                 |
| coverage                   | 66.3 ms                                                      | 81.8 ms: 1.23x slower                                                |
| python_startup_no_site     | 8.67 ms                                                      | 11.3 ms: 1.31x slower                                                |
| hexiom                     | 5.97 ms                                                      | 7.80 ms: 1.31x slower                                                |
| scimark_sor                | 107 ms                                                       | 148 ms: 1.39x slower                                                 |
| Geometric mean             | (ref)                                                        | 1.03x slower                                                         |

Benchmark hidden because not significant (10): bench_mp_pool, async_tree_memoization, tornado_http, logging_simple, async_tree_cpu_io_mixed, asyncio_tcp_ssl, asyncio_websockets, sqlite_synth, bench_thread_pool, scimark_sparse_mat_mult
Ignored benchmarks (5) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.01x
- 95% likely to have a slowdown of 1.01x
- 99% likely to have a slowdown of 1.01x
