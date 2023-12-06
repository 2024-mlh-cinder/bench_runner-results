
# Results vs. 3.12.0

- fork: brandtbucher
- ref: justin
- machine: linux-x86_64
- commit hash: 241ce0f
- commit date: 2023-11-11
- overall geometric mean: 1.04x slower \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.01x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231111-pythonperf2-x86_64-brandtbucher-justin-3.13.0a1+-241ce0f |
|----------------|:------------------------------------------------------------:|:--------------------------------------------------------------------:|
| 2to3           | 285 ms                                                       | 300 ms: 1.06x slower                                                 |
| chameleon      | 7.27 ms                                                      | 7.65 ms: 1.05x slower                                                |
| docutils       | 2.89 sec                                                     | 2.87 sec: 1.01x faster                                               |
| tornado_http   | 122 ms                                                       | 120 ms: 1.01x faster                                                 |
| Geometric mean | (ref)                                                        | 1.02x slower                                                         |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231111-pythonperf2-x86_64-brandtbucher-justin-3.13.0a1+-241ce0f |
|----------------------------|:------------------------------------------------------------:|:--------------------------------------------------------------------:|
| async_tree_none            | 459 ms                                                       | 445 ms: 1.03x faster                                                 |
| async_tree_none_tg         | 440 ms                                                       | 449 ms: 1.02x slower                                                 |
| async_tree_cpu_io_mixed_tg | 706 ms                                                       | 723 ms: 1.02x slower                                                 |
| async_tree_io              | 1.06 sec                                                     | 1.09 sec: 1.03x slower                                               |
| async_tree_io_tg           | 1.07 sec                                                     | 1.11 sec: 1.03x slower                                               |
| async_tree_memoization_tg  | 554 ms                                                       | 582 ms: 1.05x slower                                                 |
| Geometric mean             | (ref)                                                        | 1.02x slower                                                         |

Benchmark hidden because not significant (2): async_tree_memoization, async_tree_cpu_io_mixed

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231111-pythonperf2-x86_64-brandtbucher-justin-3.13.0a1+-241ce0f |
|----------------|:------------------------------------------------------------:|:--------------------------------------------------------------------:|
| pidigits       | 264 ms                                                       | 265 ms: 1.00x slower                                                 |
| nbody          | 88.2 ms                                                      | 98.3 ms: 1.11x slower                                                |
| Geometric mean | (ref)                                                        | 1.04x slower                                                         |

Benchmark hidden because not significant (1): float

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231111-pythonperf2-x86_64-brandtbucher-justin-3.13.0a1+-241ce0f |
|----------------|:------------------------------------------------------------:|:--------------------------------------------------------------------:|
| regex_effbot   | 3.61 ms                                                      | 3.51 ms: 1.03x faster                                                |
| regex_dna      | 240 ms                                                       | 237 ms: 1.01x faster                                                 |
| regex_compile  | 145 ms                                                       | 150 ms: 1.04x slower                                                 |
| regex_v8       | 24.4 ms                                                      | 25.4 ms: 1.04x slower                                                |
| Geometric mean | (ref)                                                        | 1.01x slower                                                         |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231111-pythonperf2-x86_64-brandtbucher-justin-3.13.0a1+-241ce0f |
|----------------------|:------------------------------------------------------------:|:--------------------------------------------------------------------:|
| unpickle             | 15.3 us                                                      | 14.7 us: 1.04x faster                                                |
| pickle_pure_python   | 319 us                                                       | 309 us: 1.03x faster                                                 |
| xml_etree_parse      | 147 ms                                                       | 145 ms: 1.01x faster                                                 |
| xml_etree_generate   | 85.3 ms                                                      | 85.9 ms: 1.01x slower                                                |
| xml_etree_iterparse  | 104 ms                                                       | 104 ms: 1.01x slower                                                 |
| json_dumps           | 10.3 ms                                                      | 10.4 ms: 1.01x slower                                                |
| xml_etree_process    | 58.3 ms                                                      | 59.2 ms: 1.02x slower                                                |
| pickle               | 10.0 us                                                      | 10.3 us: 1.02x slower                                                |
| pickle_dict          | 32.0 us                                                      | 32.7 us: 1.02x slower                                                |
| unpickle_list        | 4.65 us                                                      | 4.79 us: 1.03x slower                                                |
| pickle_list          | 4.22 us                                                      | 4.42 us: 1.05x slower                                                |
| unpickle_pure_python | 210 us                                                       | 222 us: 1.06x slower                                                 |
| tomli_loads          | 2.17 sec                                                     | 2.43 sec: 1.12x slower                                               |
| Geometric mean       | (ref)                                                        | 1.02x slower                                                         |

Benchmark hidden because not significant (1): json_loads

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231111-pythonperf2-x86_64-brandtbucher-justin-3.13.0a1+-241ce0f |
|------------------------|:------------------------------------------------------------:|:--------------------------------------------------------------------:|
| python_startup         | 11.7 ms                                                      | 12.9 ms: 1.10x slower                                                |
| python_startup_no_site | 8.67 ms                                                      | 11.4 ms: 1.31x slower                                                |
| Geometric mean         | (ref)                                                        | 1.20x slower                                                         |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231111-pythonperf2-x86_64-brandtbucher-justin-3.13.0a1+-241ce0f |
|-----------|:------------------------------------------------------------:|:--------------------------------------------------------------------:|
| mako      | 10.1 ms                                                      | 11.0 ms: 1.09x slower                                                |

All benchmarks:
===============

| Benchmark                  | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231111-pythonperf2-x86_64-brandtbucher-justin-3.13.0a1+-241ce0f |
|----------------------------|:------------------------------------------------------------:|:--------------------------------------------------------------------:|
| unpack_sequence            | 54.5 ns                                                      | 43.1 ns: 1.27x faster                                                |
| typing_runtime_protocols   | 150 us                                                       | 128 us: 1.18x faster                                                 |
| sympy_sum                  | 163 ms                                                       | 153 ms: 1.06x faster                                                 |
| raytrace                   | 301 ms                                                       | 285 ms: 1.05x faster                                                 |
| generators                 | 37.3 ms                                                      | 35.5 ms: 1.05x faster                                                |
| crypto_pyaes               | 82.4 ms                                                      | 78.5 ms: 1.05x faster                                                |
| unpickle                   | 15.3 us                                                      | 14.7 us: 1.04x faster                                                |
| sympy_str                  | 305 ms                                                       | 294 ms: 1.04x faster                                                 |
| deepcopy_reduce            | 3.41 us                                                      | 3.30 us: 1.03x faster                                                |
| pickle_pure_python         | 319 us                                                       | 309 us: 1.03x faster                                                 |
| async_tree_none            | 459 ms                                                       | 445 ms: 1.03x faster                                                 |
| asyncio_tcp                | 380 ms                                                       | 368 ms: 1.03x faster                                                 |
| spectral_norm              | 93.9 ms                                                      | 91.1 ms: 1.03x faster                                                |
| regex_effbot               | 3.61 ms                                                      | 3.51 ms: 1.03x faster                                                |
| create_gc_cycles           | 1.58 ms                                                      | 1.53 ms: 1.03x faster                                                |
| json                       | 5.17 ms                                                      | 5.08 ms: 1.02x faster                                                |
| xml_etree_parse            | 147 ms                                                       | 145 ms: 1.01x faster                                                 |
| regex_dna                  | 240 ms                                                       | 237 ms: 1.01x faster                                                 |
| coroutines                 | 23.1 ms                                                      | 22.7 ms: 1.01x faster                                                |
| sqlglot_normalize          | 119 ms                                                       | 118 ms: 1.01x faster                                                 |
| logging_format             | 7.29 us                                                      | 7.19 us: 1.01x faster                                                |
| tornado_http               | 122 ms                                                       | 120 ms: 1.01x faster                                                 |
| logging_simple             | 6.64 us                                                      | 6.56 us: 1.01x faster                                                |
| sqlite_synth               | 2.72 us                                                      | 2.69 us: 1.01x faster                                                |
| deepcopy                   | 371 us                                                       | 367 us: 1.01x faster                                                 |
| docutils                   | 2.89 sec                                                     | 2.87 sec: 1.01x faster                                               |
| sympy_integrate            | 24.0 ms                                                      | 23.9 ms: 1.01x faster                                                |
| pidigits                   | 264 ms                                                       | 265 ms: 1.00x slower                                                 |
| comprehensions             | 21.8 us                                                      | 21.9 us: 1.00x slower                                                |
| xml_etree_generate         | 85.3 ms                                                      | 85.9 ms: 1.01x slower                                                |
| asyncio_tcp_ssl            | 1.57 sec                                                     | 1.58 sec: 1.01x slower                                               |
| xml_etree_iterparse        | 104 ms                                                       | 104 ms: 1.01x slower                                                 |
| async_generators           | 385 ms                                                       | 389 ms: 1.01x slower                                                 |
| sympy_expand               | 492 ms                                                       | 498 ms: 1.01x slower                                                 |
| sqlglot_optimize           | 58.4 ms                                                      | 59.1 ms: 1.01x slower                                                |
| json_dumps                 | 10.3 ms                                                      | 10.4 ms: 1.01x slower                                                |
| sqlglot_transpile          | 1.80 ms                                                      | 1.83 ms: 1.01x slower                                                |
| xml_etree_process          | 58.3 ms                                                      | 59.2 ms: 1.02x slower                                                |
| async_tree_none_tg         | 440 ms                                                       | 449 ms: 1.02x slower                                                 |
| pickle                     | 10.0 us                                                      | 10.3 us: 1.02x slower                                                |
| pickle_dict                | 32.0 us                                                      | 32.7 us: 1.02x slower                                                |
| pycparser                  | 1.29 sec                                                     | 1.32 sec: 1.02x slower                                               |
| mdp                        | 2.56 sec                                                     | 2.61 sec: 1.02x slower                                               |
| async_tree_cpu_io_mixed_tg | 706 ms                                                       | 723 ms: 1.02x slower                                                 |
| logging_silent             | 93.3 ns                                                      | 95.6 ns: 1.02x slower                                                |
| bench_thread_pool          | 956 us                                                       | 980 us: 1.02x slower                                                 |
| mypy2                      | 365 ms                                                       | 374 ms: 1.03x slower                                                 |
| pprint_safe_repr           | 808 ms                                                       | 832 ms: 1.03x slower                                                 |
| unpickle_list              | 4.65 us                                                      | 4.79 us: 1.03x slower                                                |
| pprint_pformat             | 1.64 sec                                                     | 1.70 sec: 1.03x slower                                               |
| async_tree_io              | 1.06 sec                                                     | 1.09 sec: 1.03x slower                                               |
| async_tree_io_tg           | 1.07 sec                                                     | 1.11 sec: 1.03x slower                                               |
| deepcopy_memo              | 36.6 us                                                      | 37.9 us: 1.04x slower                                                |
| regex_compile              | 145 ms                                                       | 150 ms: 1.04x slower                                                 |
| regex_v8                   | 24.4 ms                                                      | 25.4 ms: 1.04x slower                                                |
| dulwich_log                | 64.9 ms                                                      | 68.0 ms: 1.05x slower                                                |
| pickle_list                | 4.22 us                                                      | 4.42 us: 1.05x slower                                                |
| async_tree_memoization_tg  | 554 ms                                                       | 582 ms: 1.05x slower                                                 |
| meteor_contest             | 126 ms                                                       | 133 ms: 1.05x slower                                                 |
| pathlib                    | 18.7 ms                                                      | 19.7 ms: 1.05x slower                                                |
| chameleon                  | 7.27 ms                                                      | 7.65 ms: 1.05x slower                                                |
| 2to3                       | 285 ms                                                       | 300 ms: 1.06x slower                                                 |
| gc_traversal               | 3.70 ms                                                      | 3.91 ms: 1.06x slower                                                |
| scimark_lu                 | 98.6 ms                                                      | 105 ms: 1.06x slower                                                 |
| unpickle_pure_python       | 210 us                                                       | 222 us: 1.06x slower                                                 |
| chaos                      | 64.1 ms                                                      | 68.0 ms: 1.06x slower                                                |
| scimark_monte_carlo        | 69.5 ms                                                      | 75.2 ms: 1.08x slower                                                |
| mako                       | 10.1 ms                                                      | 11.0 ms: 1.09x slower                                                |
| python_startup             | 11.7 ms                                                      | 12.9 ms: 1.10x slower                                                |
| nbody                      | 88.2 ms                                                      | 98.3 ms: 1.11x slower                                                |
| tomli_loads                | 2.17 sec                                                     | 2.43 sec: 1.12x slower                                               |
| richards                   | 45.1 ms                                                      | 50.9 ms: 1.13x slower                                                |
| telco                      | 7.16 ms                                                      | 8.16 ms: 1.14x slower                                                |
| scimark_fft                | 303 ms                                                       | 348 ms: 1.15x slower                                                 |
| pyflate                    | 442 ms                                                       | 507 ms: 1.15x slower                                                 |
| richards_super             | 50.8 ms                                                      | 58.8 ms: 1.16x slower                                                |
| nqueens                    | 90.1 ms                                                      | 104 ms: 1.16x slower                                                 |
| go                         | 149 ms                                                       | 174 ms: 1.17x slower                                                 |
| fannkuch                   | 362 ms                                                       | 428 ms: 1.18x slower                                                 |
| deltablue                  | 3.24 ms                                                      | 3.83 ms: 1.18x slower                                                |
| coverage                   | 66.3 ms                                                      | 82.4 ms: 1.24x slower                                                |
| bench_mp_pool              | 4.96 ms                                                      | 6.19 ms: 1.25x slower                                                |
| python_startup_no_site     | 8.67 ms                                                      | 11.4 ms: 1.31x slower                                                |
| hexiom                     | 5.97 ms                                                      | 8.19 ms: 1.37x slower                                                |
| scimark_sor                | 107 ms                                                       | 150 ms: 1.41x slower                                                 |
| Geometric mean             | (ref)                                                        | 1.04x slower                                                         |

Benchmark hidden because not significant (7): asyncio_websockets, json_loads, sqlglot_parse, async_tree_memoization, async_tree_cpu_io_mixed, float, scimark_sparse_mat_mult
Ignored benchmarks (6) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, dask, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.02x
- 95% likely to have a slowdown of 1.01x
- 99% likely to have a slowdown of 1.01x
