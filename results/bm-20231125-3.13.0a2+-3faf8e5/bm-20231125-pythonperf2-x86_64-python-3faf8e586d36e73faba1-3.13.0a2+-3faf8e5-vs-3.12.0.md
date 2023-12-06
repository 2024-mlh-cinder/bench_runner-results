
# Results vs. 3.12.0

- fork: python
- ref: 3faf8e586d36e73faba1
- machine: linux-x86_64
- commit hash: 3faf8e5
- commit date: 2023-11-25
- overall geometric mean: 1.00x slower \*
- HPT reliability: 59.31%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231125-pythonperf2-x86_64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| 2to3           | 285 ms                                                       | 290 ms: 1.02x slower                                                         |
| chameleon      | 7.27 ms                                                      | 7.59 ms: 1.04x slower                                                        |
| docutils       | 2.89 sec                                                     | 2.82 sec: 1.03x faster                                                       |
| tornado_http   | 122 ms                                                       | 119 ms: 1.02x faster                                                         |
| Geometric mean | (ref)                                                        | 1.00x slower                                                                 |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231125-pythonperf2-x86_64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|-------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| async_tree_none         | 459 ms                                                       | 434 ms: 1.06x faster                                                         |
| async_tree_memoization  | 554 ms                                                       | 542 ms: 1.02x faster                                                         |
| async_tree_cpu_io_mixed | 704 ms                                                       | 692 ms: 1.02x faster                                                         |
| async_tree_none_tg      | 440 ms                                                       | 439 ms: 1.00x faster                                                         |
| async_tree_io           | 1.06 sec                                                     | 1.07 sec: 1.01x slower                                                       |
| async_tree_io_tg        | 1.07 sec                                                     | 1.09 sec: 1.02x slower                                                       |
| Geometric mean          | (ref)                                                        | 1.01x faster                                                                 |

Benchmark hidden because not significant (2): async_tree_memoization_tg, async_tree_cpu_io_mixed_tg

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231125-pythonperf2-x86_64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| nbody          | 88.2 ms                                                      | 83.7 ms: 1.05x faster                                                        |
| pidigits       | 264 ms                                                       | 266 ms: 1.00x slower                                                         |
| Geometric mean | (ref)                                                        | 1.02x faster                                                                 |

Benchmark hidden because not significant (1): float

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231125-pythonperf2-x86_64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| regex_effbot   | 3.61 ms                                                      | 3.53 ms: 1.02x faster                                                        |
| regex_dna      | 240 ms                                                       | 235 ms: 1.02x faster                                                         |
| regex_compile  | 145 ms                                                       | 142 ms: 1.01x faster                                                         |
| regex_v8       | 24.4 ms                                                      | 25.1 ms: 1.03x slower                                                        |
| Geometric mean | (ref)                                                        | 1.01x faster                                                                 |

Benchmarks with tag 'serialize':
================================

| Benchmark           | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231125-pythonperf2-x86_64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|---------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| pickle_pure_python  | 319 us                                                       | 308 us: 1.04x faster                                                         |
| unpickle            | 15.3 us                                                      | 14.8 us: 1.04x faster                                                        |
| xml_etree_generate  | 85.3 ms                                                      | 84.1 ms: 1.01x faster                                                        |
| pickle              | 10.0 us                                                      | 10.2 us: 1.02x slower                                                        |
| tomli_loads         | 2.17 sec                                                     | 2.22 sec: 1.02x slower                                                       |
| xml_etree_iterparse | 104 ms                                                       | 107 ms: 1.03x slower                                                         |
| json_dumps          | 10.3 ms                                                      | 10.5 ms: 1.03x slower                                                        |
| unpickle_list       | 4.65 us                                                      | 4.79 us: 1.03x slower                                                        |
| json_loads          | 24.3 us                                                      | 25.3 us: 1.04x slower                                                        |
| pickle_list         | 4.22 us                                                      | 4.45 us: 1.05x slower                                                        |
| Geometric mean      | (ref)                                                        | 1.01x slower                                                                 |

Benchmark hidden because not significant (4): xml_etree_parse, pickle_dict, xml_etree_process, unpickle_pure_python

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231125-pythonperf2-x86_64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| python_startup         | 11.7 ms                                                      | 12.8 ms: 1.10x slower                                                        |
| python_startup_no_site | 8.67 ms                                                      | 11.2 ms: 1.30x slower                                                        |
| Geometric mean         | (ref)                                                        | 1.19x slower                                                                 |

Benchmarks with tag 'template':
===============================

Benchmark hidden because not significant (1): mako

All benchmarks:
===============

| Benchmark                | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231125-pythonperf2-x86_64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|--------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| comprehensions           | 21.8 us                                                      | 16.5 us: 1.32x faster                                                        |
| typing_runtime_protocols | 150 us                                                       | 123 us: 1.22x faster                                                         |
| unpack_sequence          | 54.5 ns                                                      | 46.6 ns: 1.17x faster                                                        |
| crypto_pyaes             | 82.4 ms                                                      | 71.3 ms: 1.16x faster                                                        |
| bench_mp_pool            | 4.96 ms                                                      | 4.44 ms: 1.12x faster                                                        |
| raytrace                 | 301 ms                                                       | 276 ms: 1.09x faster                                                         |
| scimark_sparse_mat_mult  | 4.49 ms                                                      | 4.14 ms: 1.08x faster                                                        |
| sympy_sum                | 163 ms                                                       | 151 ms: 1.08x faster                                                         |
| async_generators         | 385 ms                                                       | 359 ms: 1.07x faster                                                         |
| generators               | 37.3 ms                                                      | 35.1 ms: 1.06x faster                                                        |
| sympy_str                | 305 ms                                                       | 288 ms: 1.06x faster                                                         |
| async_tree_none          | 459 ms                                                       | 434 ms: 1.06x faster                                                         |
| nbody                    | 88.2 ms                                                      | 83.7 ms: 1.05x faster                                                        |
| sympy_integrate          | 24.0 ms                                                      | 23.0 ms: 1.05x faster                                                        |
| deepcopy_reduce          | 3.41 us                                                      | 3.26 us: 1.04x faster                                                        |
| logging_format           | 7.29 us                                                      | 7.02 us: 1.04x faster                                                        |
| pickle_pure_python       | 319 us                                                       | 308 us: 1.04x faster                                                         |
| sqlglot_normalize        | 119 ms                                                       | 115 ms: 1.04x faster                                                         |
| unpickle                 | 15.3 us                                                      | 14.8 us: 1.04x faster                                                        |
| asyncio_tcp              | 380 ms                                                       | 367 ms: 1.04x faster                                                         |
| logging_simple           | 6.64 us                                                      | 6.42 us: 1.03x faster                                                        |
| deepcopy                 | 371 us                                                       | 359 us: 1.03x faster                                                         |
| pprint_safe_repr         | 808 ms                                                       | 783 ms: 1.03x faster                                                         |
| pprint_pformat           | 1.64 sec                                                     | 1.60 sec: 1.03x faster                                                       |
| docutils                 | 2.89 sec                                                     | 2.82 sec: 1.03x faster                                                       |
| tornado_http             | 122 ms                                                       | 119 ms: 1.02x faster                                                         |
| regex_effbot             | 3.61 ms                                                      | 3.53 ms: 1.02x faster                                                        |
| chaos                    | 64.1 ms                                                      | 62.6 ms: 1.02x faster                                                        |
| sqlglot_parse            | 1.41 ms                                                      | 1.38 ms: 1.02x faster                                                        |
| async_tree_memoization   | 554 ms                                                       | 542 ms: 1.02x faster                                                         |
| regex_dna                | 240 ms                                                       | 235 ms: 1.02x faster                                                         |
| coroutines               | 23.1 ms                                                      | 22.6 ms: 1.02x faster                                                        |
| async_tree_cpu_io_mixed  | 704 ms                                                       | 692 ms: 1.02x faster                                                         |
| spectral_norm            | 93.9 ms                                                      | 92.4 ms: 1.02x faster                                                        |
| nqueens                  | 90.1 ms                                                      | 88.7 ms: 1.02x faster                                                        |
| regex_compile            | 145 ms                                                       | 142 ms: 1.01x faster                                                         |
| sqlite_synth             | 2.72 us                                                      | 2.68 us: 1.01x faster                                                        |
| xml_etree_generate       | 85.3 ms                                                      | 84.1 ms: 1.01x faster                                                        |
| mdp                      | 2.56 sec                                                     | 2.52 sec: 1.01x faster                                                       |
| sqlglot_transpile        | 1.80 ms                                                      | 1.78 ms: 1.01x faster                                                        |
| deepcopy_memo            | 36.6 us                                                      | 36.2 us: 1.01x faster                                                        |
| sympy_expand             | 492 ms                                                       | 488 ms: 1.01x faster                                                         |
| pathlib                  | 18.7 ms                                                      | 18.6 ms: 1.01x faster                                                        |
| sqlglot_optimize         | 58.4 ms                                                      | 58.1 ms: 1.01x faster                                                        |
| async_tree_none_tg       | 440 ms                                                       | 439 ms: 1.00x faster                                                         |
| mypy2                    | 365 ms                                                       | 366 ms: 1.00x slower                                                         |
| pidigits                 | 264 ms                                                       | 266 ms: 1.00x slower                                                         |
| json                     | 5.17 ms                                                      | 5.20 ms: 1.01x slower                                                        |
| scimark_monte_carlo      | 69.5 ms                                                      | 70.1 ms: 1.01x slower                                                        |
| gc_traversal             | 3.70 ms                                                      | 3.74 ms: 1.01x slower                                                        |
| async_tree_io            | 1.06 sec                                                     | 1.07 sec: 1.01x slower                                                       |
| scimark_lu               | 98.6 ms                                                      | 100 ms: 1.02x slower                                                         |
| async_tree_io_tg         | 1.07 sec                                                     | 1.09 sec: 1.02x slower                                                       |
| pickle                   | 10.0 us                                                      | 10.2 us: 1.02x slower                                                        |
| 2to3                     | 285 ms                                                       | 290 ms: 1.02x slower                                                         |
| scimark_fft              | 303 ms                                                       | 310 ms: 1.02x slower                                                         |
| pycparser                | 1.29 sec                                                     | 1.32 sec: 1.02x slower                                                       |
| meteor_contest           | 126 ms                                                       | 129 ms: 1.02x slower                                                         |
| create_gc_cycles         | 1.58 ms                                                      | 1.61 ms: 1.02x slower                                                        |
| tomli_loads              | 2.17 sec                                                     | 2.22 sec: 1.02x slower                                                       |
| xml_etree_iterparse      | 104 ms                                                       | 107 ms: 1.03x slower                                                         |
| regex_v8                 | 24.4 ms                                                      | 25.1 ms: 1.03x slower                                                        |
| json_dumps               | 10.3 ms                                                      | 10.5 ms: 1.03x slower                                                        |
| unpickle_list            | 4.65 us                                                      | 4.79 us: 1.03x slower                                                        |
| json_loads               | 24.3 us                                                      | 25.3 us: 1.04x slower                                                        |
| chameleon                | 7.27 ms                                                      | 7.59 ms: 1.04x slower                                                        |
| dulwich_log              | 64.9 ms                                                      | 68.0 ms: 1.05x slower                                                        |
| logging_silent           | 93.3 ns                                                      | 98.1 ns: 1.05x slower                                                        |
| pickle_list              | 4.22 us                                                      | 4.45 us: 1.05x slower                                                        |
| fannkuch                 | 362 ms                                                       | 382 ms: 1.05x slower                                                         |
| hexiom                   | 5.97 ms                                                      | 6.42 ms: 1.07x slower                                                        |
| python_startup           | 11.7 ms                                                      | 12.8 ms: 1.10x slower                                                        |
| deltablue                | 3.24 ms                                                      | 3.58 ms: 1.11x slower                                                        |
| telco                    | 7.16 ms                                                      | 8.01 ms: 1.12x slower                                                        |
| go                       | 149 ms                                                       | 168 ms: 1.13x slower                                                         |
| pyflate                  | 442 ms                                                       | 504 ms: 1.14x slower                                                         |
| richards_super           | 50.8 ms                                                      | 59.6 ms: 1.17x slower                                                        |
| richards                 | 45.1 ms                                                      | 54.3 ms: 1.21x slower                                                        |
| coverage                 | 66.3 ms                                                      | 84.2 ms: 1.27x slower                                                        |
| python_startup_no_site   | 8.67 ms                                                      | 11.2 ms: 1.30x slower                                                        |
| scimark_sor              | 107 ms                                                       | 148 ms: 1.38x slower                                                         |
| Geometric mean           | (ref)                                                        | 1.00x slower                                                                 |

Benchmark hidden because not significant (12): float, dask, xml_etree_parse, pickle_dict, xml_etree_process, asyncio_tcp_ssl, mako, async_tree_memoization_tg, async_tree_cpu_io_mixed_tg, unpickle_pure_python, asyncio_websockets, bench_thread_pool
Ignored benchmarks (5) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 59.31% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
