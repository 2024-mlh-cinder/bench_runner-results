
# Results vs. 3.12.0

- fork: python
- ref: 48dfd74a9db9d4aa9c6f
- machine: linux-x86_64
- commit hash: 48dfd74
- commit date: 2023-11-28
- overall geometric mean: 1.01x slower \*
- HPT reliability: 78.78%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231128-pythonperf2-x86_64-python-48dfd74a9db9d4aa9c6f-3.13.0a2+-48dfd74 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| 2to3           | 285 ms                                                       | 290 ms: 1.02x slower                                                         |
| chameleon      | 7.27 ms                                                      | 7.44 ms: 1.02x slower                                                        |
| docutils       | 2.89 sec                                                     | 2.80 sec: 1.03x faster                                                       |
| tornado_http   | 122 ms                                                       | 117 ms: 1.04x faster                                                         |
| Geometric mean | (ref)                                                        | 1.01x faster                                                                 |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231128-pythonperf2-x86_64-python-48dfd74a9db9d4aa9c6f-3.13.0a2+-48dfd74 |
|-------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| async_tree_none         | 459 ms                                                       | 428 ms: 1.07x faster                                                         |
| async_tree_memoization  | 554 ms                                                       | 540 ms: 1.02x faster                                                         |
| async_tree_cpu_io_mixed | 704 ms                                                       | 695 ms: 1.01x faster                                                         |
| async_tree_none_tg      | 440 ms                                                       | 436 ms: 1.01x faster                                                         |
| async_tree_io           | 1.06 sec                                                     | 1.07 sec: 1.01x slower                                                       |
| async_tree_io_tg        | 1.07 sec                                                     | 1.08 sec: 1.01x slower                                                       |
| Geometric mean          | (ref)                                                        | 1.01x faster                                                                 |

Benchmark hidden because not significant (2): async_tree_memoization_tg, async_tree_cpu_io_mixed_tg

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231128-pythonperf2-x86_64-python-48dfd74a9db9d4aa9c6f-3.13.0a2+-48dfd74 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| float          | 81.6 ms                                                      | 77.9 ms: 1.05x faster                                                        |
| pidigits       | 264 ms                                                       | 265 ms: 1.00x slower                                                         |
| Geometric mean | (ref)                                                        | 1.03x faster                                                                 |

Benchmark hidden because not significant (1): nbody

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231128-pythonperf2-x86_64-python-48dfd74a9db9d4aa9c6f-3.13.0a2+-48dfd74 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| regex_effbot   | 3.61 ms                                                      | 3.52 ms: 1.03x faster                                                        |
| regex_compile  | 145 ms                                                       | 143 ms: 1.01x faster                                                         |
| regex_dna      | 240 ms                                                       | 244 ms: 1.02x slower                                                         |
| regex_v8       | 24.4 ms                                                      | 25.3 ms: 1.04x slower                                                        |
| Geometric mean | (ref)                                                        | 1.00x slower                                                                 |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231128-pythonperf2-x86_64-python-48dfd74a9db9d4aa9c6f-3.13.0a2+-48dfd74 |
|----------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| unpickle             | 15.3 us                                                      | 14.5 us: 1.06x faster                                                        |
| pickle_pure_python   | 319 us                                                       | 303 us: 1.06x faster                                                         |
| xml_etree_generate   | 85.3 ms                                                      | 83.8 ms: 1.02x faster                                                        |
| unpickle_list        | 4.65 us                                                      | 4.58 us: 1.01x faster                                                        |
| xml_etree_process    | 58.3 ms                                                      | 57.9 ms: 1.01x faster                                                        |
| unpickle_pure_python | 210 us                                                       | 210 us: 1.00x slower                                                         |
| pickle               | 10.0 us                                                      | 10.1 us: 1.01x slower                                                        |
| xml_etree_parse      | 147 ms                                                       | 149 ms: 1.01x slower                                                         |
| tomli_loads          | 2.17 sec                                                     | 2.21 sec: 1.02x slower                                                       |
| pickle_dict          | 32.0 us                                                      | 32.7 us: 1.02x slower                                                        |
| xml_etree_iterparse  | 104 ms                                                       | 107 ms: 1.03x slower                                                         |
| json_dumps           | 10.3 ms                                                      | 10.6 ms: 1.03x slower                                                        |
| json_loads           | 24.3 us                                                      | 25.3 us: 1.04x slower                                                        |
| pickle_list          | 4.22 us                                                      | 4.47 us: 1.06x slower                                                        |
| Geometric mean       | (ref)                                                        | 1.01x slower                                                                 |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231128-pythonperf2-x86_64-python-48dfd74a9db9d4aa9c6f-3.13.0a2+-48dfd74 |
|------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| python_startup         | 11.7 ms                                                      | 12.8 ms: 1.10x slower                                                        |
| python_startup_no_site | 8.67 ms                                                      | 11.2 ms: 1.30x slower                                                        |
| Geometric mean         | (ref)                                                        | 1.19x slower                                                                 |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231128-pythonperf2-x86_64-python-48dfd74a9db9d4aa9c6f-3.13.0a2+-48dfd74 |
|-----------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| mako      | 10.1 ms                                                      | 10.3 ms: 1.02x slower                                                        |

All benchmarks:
===============

| Benchmark                | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231128-pythonperf2-x86_64-python-48dfd74a9db9d4aa9c6f-3.13.0a2+-48dfd74 |
|--------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| comprehensions           | 21.8 us                                                      | 16.6 us: 1.32x faster                                                        |
| typing_runtime_protocols | 150 us                                                       | 121 us: 1.24x faster                                                         |
| crypto_pyaes             | 82.4 ms                                                      | 71.3 ms: 1.16x faster                                                        |
| raytrace                 | 301 ms                                                       | 262 ms: 1.15x faster                                                         |
| sympy_sum                | 163 ms                                                       | 149 ms: 1.09x faster                                                         |
| bench_mp_pool            | 4.96 ms                                                      | 4.57 ms: 1.08x faster                                                        |
| generators               | 37.3 ms                                                      | 34.7 ms: 1.07x faster                                                        |
| async_tree_none          | 459 ms                                                       | 428 ms: 1.07x faster                                                         |
| deepcopy_reduce          | 3.41 us                                                      | 3.20 us: 1.07x faster                                                        |
| chaos                    | 64.1 ms                                                      | 60.2 ms: 1.06x faster                                                        |
| sympy_str                | 305 ms                                                       | 287 ms: 1.06x faster                                                         |
| async_generators         | 385 ms                                                       | 364 ms: 1.06x faster                                                         |
| unpickle                 | 15.3 us                                                      | 14.5 us: 1.06x faster                                                        |
| pickle_pure_python       | 319 us                                                       | 303 us: 1.06x faster                                                         |
| scimark_monte_carlo      | 69.5 ms                                                      | 66.1 ms: 1.05x faster                                                        |
| sympy_integrate          | 24.0 ms                                                      | 22.9 ms: 1.05x faster                                                        |
| float                    | 81.6 ms                                                      | 77.9 ms: 1.05x faster                                                        |
| gc_traversal             | 3.70 ms                                                      | 3.54 ms: 1.05x faster                                                        |
| deepcopy                 | 371 us                                                       | 356 us: 1.04x faster                                                         |
| logging_simple           | 6.64 us                                                      | 6.37 us: 1.04x faster                                                        |
| coroutines               | 23.1 ms                                                      | 22.1 ms: 1.04x faster                                                        |
| tornado_http             | 122 ms                                                       | 117 ms: 1.04x faster                                                         |
| spectral_norm            | 93.9 ms                                                      | 90.5 ms: 1.04x faster                                                        |
| sqlglot_normalize        | 119 ms                                                       | 115 ms: 1.04x faster                                                         |
| asyncio_tcp              | 380 ms                                                       | 367 ms: 1.04x faster                                                         |
| docutils                 | 2.89 sec                                                     | 2.80 sec: 1.03x faster                                                       |
| regex_effbot             | 3.61 ms                                                      | 3.52 ms: 1.03x faster                                                        |
| async_tree_memoization   | 554 ms                                                       | 540 ms: 1.02x faster                                                         |
| pycparser                | 1.29 sec                                                     | 1.27 sec: 1.02x faster                                                       |
| sqlglot_parse            | 1.41 ms                                                      | 1.38 ms: 1.02x faster                                                        |
| logging_format           | 7.29 us                                                      | 7.14 us: 1.02x faster                                                        |
| sqlglot_transpile        | 1.80 ms                                                      | 1.77 ms: 1.02x faster                                                        |
| xml_etree_generate       | 85.3 ms                                                      | 83.8 ms: 1.02x faster                                                        |
| mdp                      | 2.56 sec                                                     | 2.52 sec: 1.02x faster                                                       |
| unpickle_list            | 4.65 us                                                      | 4.58 us: 1.01x faster                                                        |
| async_tree_cpu_io_mixed  | 704 ms                                                       | 695 ms: 1.01x faster                                                         |
| pprint_safe_repr         | 808 ms                                                       | 797 ms: 1.01x faster                                                         |
| sympy_expand             | 492 ms                                                       | 486 ms: 1.01x faster                                                         |
| nqueens                  | 90.1 ms                                                      | 89.0 ms: 1.01x faster                                                        |
| regex_compile            | 145 ms                                                       | 143 ms: 1.01x faster                                                         |
| async_tree_none_tg       | 440 ms                                                       | 436 ms: 1.01x faster                                                         |
| sqlite_synth             | 2.72 us                                                      | 2.69 us: 1.01x faster                                                        |
| json                     | 5.17 ms                                                      | 5.12 ms: 1.01x faster                                                        |
| pprint_pformat           | 1.64 sec                                                     | 1.63 sec: 1.01x faster                                                       |
| xml_etree_process        | 58.3 ms                                                      | 57.9 ms: 1.01x faster                                                        |
| sqlglot_optimize         | 58.4 ms                                                      | 58.1 ms: 1.01x faster                                                        |
| asyncio_tcp_ssl          | 1.57 sec                                                     | 1.57 sec: 1.00x faster                                                       |
| meteor_contest           | 126 ms                                                       | 126 ms: 1.00x faster                                                         |
| unpickle_pure_python     | 210 us                                                       | 210 us: 1.00x slower                                                         |
| pidigits                 | 264 ms                                                       | 265 ms: 1.00x slower                                                         |
| pickle                   | 10.0 us                                                      | 10.1 us: 1.01x slower                                                        |
| async_tree_io            | 1.06 sec                                                     | 1.07 sec: 1.01x slower                                                       |
| async_tree_io_tg         | 1.07 sec                                                     | 1.08 sec: 1.01x slower                                                       |
| xml_etree_parse          | 147 ms                                                       | 149 ms: 1.01x slower                                                         |
| regex_dna                | 240 ms                                                       | 244 ms: 1.02x slower                                                         |
| create_gc_cycles         | 1.58 ms                                                      | 1.60 ms: 1.02x slower                                                        |
| scimark_lu               | 98.6 ms                                                      | 100 ms: 1.02x slower                                                         |
| 2to3                     | 285 ms                                                       | 290 ms: 1.02x slower                                                         |
| tomli_loads              | 2.17 sec                                                     | 2.21 sec: 1.02x slower                                                       |
| pickle_dict              | 32.0 us                                                      | 32.7 us: 1.02x slower                                                        |
| chameleon                | 7.27 ms                                                      | 7.44 ms: 1.02x slower                                                        |
| mako                     | 10.1 ms                                                      | 10.3 ms: 1.02x slower                                                        |
| xml_etree_iterparse      | 104 ms                                                       | 107 ms: 1.03x slower                                                         |
| json_dumps               | 10.3 ms                                                      | 10.6 ms: 1.03x slower                                                        |
| scimark_fft              | 303 ms                                                       | 313 ms: 1.03x slower                                                         |
| regex_v8                 | 24.4 ms                                                      | 25.3 ms: 1.04x slower                                                        |
| dulwich_log              | 64.9 ms                                                      | 67.4 ms: 1.04x slower                                                        |
| json_loads               | 24.3 us                                                      | 25.3 us: 1.04x slower                                                        |
| logging_silent           | 93.3 ns                                                      | 97.2 ns: 1.04x slower                                                        |
| fannkuch                 | 362 ms                                                       | 380 ms: 1.05x slower                                                         |
| unpack_sequence          | 54.5 ns                                                      | 57.4 ns: 1.05x slower                                                        |
| pickle_list              | 4.22 us                                                      | 4.47 us: 1.06x slower                                                        |
| hexiom                   | 5.97 ms                                                      | 6.44 ms: 1.08x slower                                                        |
| python_startup           | 11.7 ms                                                      | 12.8 ms: 1.10x slower                                                        |
| deltablue                | 3.24 ms                                                      | 3.62 ms: 1.12x slower                                                        |
| telco                    | 7.16 ms                                                      | 8.17 ms: 1.14x slower                                                        |
| pyflate                  | 442 ms                                                       | 506 ms: 1.15x slower                                                         |
| richards_super           | 50.8 ms                                                      | 58.3 ms: 1.15x slower                                                        |
| go                       | 149 ms                                                       | 172 ms: 1.15x slower                                                         |
| richards                 | 45.1 ms                                                      | 52.4 ms: 1.16x slower                                                        |
| coverage                 | 66.3 ms                                                      | 79.0 ms: 1.19x slower                                                        |
| python_startup_no_site   | 8.67 ms                                                      | 11.2 ms: 1.30x slower                                                        |
| scimark_sor              | 107 ms                                                       | 145 ms: 1.36x slower                                                         |
| mypy2                    | 365 ms                                                       | 859 ms: 2.35x slower                                                         |
| Geometric mean           | (ref)                                                        | 1.01x slower                                                                 |

Benchmark hidden because not significant (9): nbody, async_tree_memoization_tg, asyncio_websockets, deepcopy_memo, pathlib, async_tree_cpu_io_mixed_tg, scimark_sparse_mat_mult, dask, bench_thread_pool
Ignored benchmarks (5) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 78.78% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
