
# Results vs. 3.12.0

- fork: python
- ref: 1a969b4f55f92a17bec8
- machine: linux-x86_64
- commit hash: 1a969b4
- commit date: 2023-11-19
- overall geometric mean: 1.01x slower \*
- HPT reliability: 71.14%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231119-pythonperf2-x86_64-python-1a969b4f55f92a17bec8-3.13.0a1+-1a969b4 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| 2to3           | 285 ms                                                       | 293 ms: 1.03x slower                                                         |
| chameleon      | 7.27 ms                                                      | 7.58 ms: 1.04x slower                                                        |
| docutils       | 2.89 sec                                                     | 2.82 sec: 1.03x faster                                                       |
| tornado_http   | 122 ms                                                       | 118 ms: 1.03x faster                                                         |
| Geometric mean | (ref)                                                        | 1.00x slower                                                                 |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                 | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231119-pythonperf2-x86_64-python-1a969b4f55f92a17bec8-3.13.0a1+-1a969b4 |
|---------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| async_tree_none           | 459 ms                                                       | 433 ms: 1.06x faster                                                         |
| async_tree_cpu_io_mixed   | 704 ms                                                       | 693 ms: 1.02x faster                                                         |
| async_tree_memoization    | 554 ms                                                       | 545 ms: 1.02x faster                                                         |
| async_tree_none_tg        | 440 ms                                                       | 438 ms: 1.01x faster                                                         |
| async_tree_io             | 1.06 sec                                                     | 1.08 sec: 1.02x slower                                                       |
| async_tree_io_tg          | 1.07 sec                                                     | 1.09 sec: 1.02x slower                                                       |
| async_tree_memoization_tg | 554 ms                                                       | 569 ms: 1.03x slower                                                         |
| Geometric mean            | (ref)                                                        | 1.00x faster                                                                 |

Benchmark hidden because not significant (1): async_tree_cpu_io_mixed_tg

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231119-pythonperf2-x86_64-python-1a969b4f55f92a17bec8-3.13.0a1+-1a969b4 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| nbody          | 88.2 ms                                                      | 83.7 ms: 1.05x faster                                                        |
| pidigits       | 264 ms                                                       | 265 ms: 1.00x slower                                                         |
| Geometric mean | (ref)                                                        | 1.02x faster                                                                 |

Benchmark hidden because not significant (1): float

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231119-pythonperf2-x86_64-python-1a969b4f55f92a17bec8-3.13.0a1+-1a969b4 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| regex_effbot   | 3.61 ms                                                      | 3.49 ms: 1.03x faster                                                        |
| regex_compile  | 145 ms                                                       | 145 ms: 1.01x slower                                                         |
| regex_v8       | 24.4 ms                                                      | 25.2 ms: 1.03x slower                                                        |
| regex_dna      | 240 ms                                                       | 251 ms: 1.04x slower                                                         |
| Geometric mean | (ref)                                                        | 1.01x slower                                                                 |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231119-pythonperf2-x86_64-python-1a969b4f55f92a17bec8-3.13.0a1+-1a969b4 |
|----------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| unpickle             | 15.3 us                                                      | 14.2 us: 1.08x faster                                                        |
| pickle_pure_python   | 319 us                                                       | 309 us: 1.03x faster                                                         |
| pickle_dict          | 32.0 us                                                      | 32.2 us: 1.00x slower                                                        |
| pickle               | 10.0 us                                                      | 10.1 us: 1.00x slower                                                        |
| json_dumps           | 10.3 ms                                                      | 10.5 ms: 1.02x slower                                                        |
| xml_etree_parse      | 147 ms                                                       | 151 ms: 1.03x slower                                                         |
| xml_etree_iterparse  | 104 ms                                                       | 107 ms: 1.03x slower                                                         |
| json_loads           | 24.3 us                                                      | 25.2 us: 1.04x slower                                                        |
| pickle_list          | 4.22 us                                                      | 4.39 us: 1.04x slower                                                        |
| tomli_loads          | 2.17 sec                                                     | 2.29 sec: 1.06x slower                                                       |
| unpickle_pure_python | 210 us                                                       | 229 us: 1.09x slower                                                         |
| Geometric mean       | (ref)                                                        | 1.01x slower                                                                 |

Benchmark hidden because not significant (3): xml_etree_process, unpickle_list, xml_etree_generate

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231119-pythonperf2-x86_64-python-1a969b4f55f92a17bec8-3.13.0a1+-1a969b4 |
|------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| python_startup         | 11.7 ms                                                      | 12.8 ms: 1.10x slower                                                        |
| python_startup_no_site | 8.67 ms                                                      | 11.2 ms: 1.29x slower                                                        |
| Geometric mean         | (ref)                                                        | 1.19x slower                                                                 |

Benchmarks with tag 'template':
===============================

Benchmark hidden because not significant (1): mako

All benchmarks:
===============

| Benchmark                 | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231119-pythonperf2-x86_64-python-1a969b4f55f92a17bec8-3.13.0a1+-1a969b4 |
|---------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| comprehensions            | 21.8 us                                                      | 16.7 us: 1.30x faster                                                        |
| unpack_sequence           | 54.5 ns                                                      | 44.1 ns: 1.24x faster                                                        |
| typing_runtime_protocols  | 150 us                                                       | 127 us: 1.19x faster                                                         |
| crypto_pyaes              | 82.4 ms                                                      | 70.4 ms: 1.17x faster                                                        |
| raytrace                  | 301 ms                                                       | 268 ms: 1.12x faster                                                         |
| generators                | 37.3 ms                                                      | 34.3 ms: 1.09x faster                                                        |
| sympy_sum                 | 163 ms                                                       | 150 ms: 1.09x faster                                                         |
| unpickle                  | 15.3 us                                                      | 14.2 us: 1.08x faster                                                        |
| async_generators          | 385 ms                                                       | 362 ms: 1.06x faster                                                         |
| async_tree_none           | 459 ms                                                       | 433 ms: 1.06x faster                                                         |
| chaos                     | 64.1 ms                                                      | 60.4 ms: 1.06x faster                                                        |
| scimark_sparse_mat_mult   | 4.49 ms                                                      | 4.24 ms: 1.06x faster                                                        |
| sympy_str                 | 305 ms                                                       | 288 ms: 1.06x faster                                                         |
| nbody                     | 88.2 ms                                                      | 83.7 ms: 1.05x faster                                                        |
| sympy_integrate           | 24.0 ms                                                      | 22.9 ms: 1.05x faster                                                        |
| coroutines                | 23.1 ms                                                      | 22.2 ms: 1.04x faster                                                        |
| spectral_norm             | 93.9 ms                                                      | 90.4 ms: 1.04x faster                                                        |
| deepcopy_reduce           | 3.41 us                                                      | 3.29 us: 1.04x faster                                                        |
| regex_effbot              | 3.61 ms                                                      | 3.49 ms: 1.03x faster                                                        |
| pickle_pure_python        | 319 us                                                       | 309 us: 1.03x faster                                                         |
| tornado_http              | 122 ms                                                       | 118 ms: 1.03x faster                                                         |
| sqlglot_normalize         | 119 ms                                                       | 116 ms: 1.03x faster                                                         |
| scimark_monte_carlo       | 69.5 ms                                                      | 67.4 ms: 1.03x faster                                                        |
| pprint_pformat            | 1.64 sec                                                     | 1.60 sec: 1.03x faster                                                       |
| pprint_safe_repr          | 808 ms                                                       | 786 ms: 1.03x faster                                                         |
| docutils                  | 2.89 sec                                                     | 2.82 sec: 1.03x faster                                                       |
| mdp                       | 2.56 sec                                                     | 2.50 sec: 1.02x faster                                                       |
| logging_simple            | 6.64 us                                                      | 6.50 us: 1.02x faster                                                        |
| sqlite_synth              | 2.72 us                                                      | 2.66 us: 1.02x faster                                                        |
| logging_format            | 7.29 us                                                      | 7.16 us: 1.02x faster                                                        |
| async_tree_cpu_io_mixed   | 704 ms                                                       | 693 ms: 1.02x faster                                                         |
| pathlib                   | 18.7 ms                                                      | 18.5 ms: 1.02x faster                                                        |
| async_tree_memoization    | 554 ms                                                       | 545 ms: 1.02x faster                                                         |
| pycparser                 | 1.29 sec                                                     | 1.28 sec: 1.01x faster                                                       |
| asyncio_tcp               | 380 ms                                                       | 375 ms: 1.01x faster                                                         |
| nqueens                   | 90.1 ms                                                      | 89.3 ms: 1.01x faster                                                        |
| async_tree_none_tg        | 440 ms                                                       | 438 ms: 1.01x faster                                                         |
| sqlglot_optimize          | 58.4 ms                                                      | 58.1 ms: 1.01x faster                                                        |
| mypy2                     | 365 ms                                                       | 366 ms: 1.00x slower                                                         |
| pidigits                  | 264 ms                                                       | 265 ms: 1.00x slower                                                         |
| pickle_dict               | 32.0 us                                                      | 32.2 us: 1.00x slower                                                        |
| pickle                    | 10.0 us                                                      | 10.1 us: 1.00x slower                                                        |
| regex_compile             | 145 ms                                                       | 145 ms: 1.01x slower                                                         |
| json                      | 5.17 ms                                                      | 5.20 ms: 1.01x slower                                                        |
| deepcopy                  | 371 us                                                       | 374 us: 1.01x slower                                                         |
| sqlglot_transpile         | 1.80 ms                                                      | 1.82 ms: 1.01x slower                                                        |
| meteor_contest            | 126 ms                                                       | 128 ms: 1.01x slower                                                         |
| gc_traversal              | 3.70 ms                                                      | 3.74 ms: 1.01x slower                                                        |
| scimark_fft               | 303 ms                                                       | 307 ms: 1.01x slower                                                         |
| asyncio_websockets        | 386 ms                                                       | 393 ms: 1.02x slower                                                         |
| async_tree_io             | 1.06 sec                                                     | 1.08 sec: 1.02x slower                                                       |
| async_tree_io_tg          | 1.07 sec                                                     | 1.09 sec: 1.02x slower                                                       |
| json_dumps                | 10.3 ms                                                      | 10.5 ms: 1.02x slower                                                        |
| create_gc_cycles          | 1.58 ms                                                      | 1.61 ms: 1.02x slower                                                        |
| async_tree_memoization_tg | 554 ms                                                       | 569 ms: 1.03x slower                                                         |
| 2to3                      | 285 ms                                                       | 293 ms: 1.03x slower                                                         |
| xml_etree_parse           | 147 ms                                                       | 151 ms: 1.03x slower                                                         |
| xml_etree_iterparse       | 104 ms                                                       | 107 ms: 1.03x slower                                                         |
| regex_v8                  | 24.4 ms                                                      | 25.2 ms: 1.03x slower                                                        |
| deepcopy_memo             | 36.6 us                                                      | 37.8 us: 1.03x slower                                                        |
| logging_silent            | 93.3 ns                                                      | 96.6 ns: 1.04x slower                                                        |
| dulwich_log               | 64.9 ms                                                      | 67.3 ms: 1.04x slower                                                        |
| json_loads                | 24.3 us                                                      | 25.2 us: 1.04x slower                                                        |
| pickle_list               | 4.22 us                                                      | 4.39 us: 1.04x slower                                                        |
| chameleon                 | 7.27 ms                                                      | 7.58 ms: 1.04x slower                                                        |
| regex_dna                 | 240 ms                                                       | 251 ms: 1.04x slower                                                         |
| scimark_lu                | 98.6 ms                                                      | 103 ms: 1.05x slower                                                         |
| fannkuch                  | 362 ms                                                       | 380 ms: 1.05x slower                                                         |
| tomli_loads               | 2.17 sec                                                     | 2.29 sec: 1.06x slower                                                       |
| hexiom                    | 5.97 ms                                                      | 6.39 ms: 1.07x slower                                                        |
| unpickle_pure_python      | 210 us                                                       | 229 us: 1.09x slower                                                         |
| python_startup            | 11.7 ms                                                      | 12.8 ms: 1.10x slower                                                        |
| deltablue                 | 3.24 ms                                                      | 3.55 ms: 1.10x slower                                                        |
| telco                     | 7.16 ms                                                      | 8.07 ms: 1.13x slower                                                        |
| go                        | 149 ms                                                       | 168 ms: 1.13x slower                                                         |
| richards_super            | 50.8 ms                                                      | 58.0 ms: 1.14x slower                                                        |
| pyflate                   | 442 ms                                                       | 513 ms: 1.16x slower                                                         |
| richards                  | 45.1 ms                                                      | 52.3 ms: 1.16x slower                                                        |
| coverage                  | 66.3 ms                                                      | 82.7 ms: 1.25x slower                                                        |
| python_startup_no_site    | 8.67 ms                                                      | 11.2 ms: 1.29x slower                                                        |
| scimark_sor               | 107 ms                                                       | 145 ms: 1.35x slower                                                         |
| Geometric mean            | (ref)                                                        | 1.01x slower                                                                 |

Benchmark hidden because not significant (12): float, xml_etree_process, unpickle_list, asyncio_tcp_ssl, sympy_expand, xml_etree_generate, bench_thread_pool, sqlglot_parse, dask, async_tree_cpu_io_mixed_tg, mako, bench_mp_pool
Ignored benchmarks (5) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 71.14% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
