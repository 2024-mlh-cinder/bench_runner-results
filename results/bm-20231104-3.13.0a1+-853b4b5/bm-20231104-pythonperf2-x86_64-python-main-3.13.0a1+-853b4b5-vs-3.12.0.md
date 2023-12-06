
# Results vs. 3.12.0

- fork: python
- ref: main
- machine: linux-x86_64
- commit hash: 853b4b5
- commit date: 2023-11-04
- overall geometric mean: 1.01x slower \*
- HPT reliability: 97.45%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231104-pythonperf2-x86_64-python-main-3.13.0a1+-853b4b5 |
|----------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| 2to3           | 285 ms                                                       | 292 ms: 1.03x slower                                         |
| chameleon      | 7.27 ms                                                      | 7.49 ms: 1.03x slower                                        |
| docutils       | 2.89 sec                                                     | 2.83 sec: 1.02x faster                                       |
| tornado_http   | 122 ms                                                       | 119 ms: 1.02x faster                                         |
| Geometric mean | (ref)                                                        | 1.00x slower                                                 |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231104-pythonperf2-x86_64-python-main-3.13.0a1+-853b4b5 |
|----------------------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| async_tree_none            | 459 ms                                                       | 439 ms: 1.05x faster                                         |
| async_tree_none_tg         | 440 ms                                                       | 448 ms: 1.02x slower                                         |
| async_tree_cpu_io_mixed_tg | 706 ms                                                       | 723 ms: 1.02x slower                                         |
| async_tree_io              | 1.06 sec                                                     | 1.09 sec: 1.03x slower                                       |
| async_tree_io_tg           | 1.07 sec                                                     | 1.11 sec: 1.03x slower                                       |
| async_tree_memoization_tg  | 554 ms                                                       | 576 ms: 1.04x slower                                         |
| Geometric mean             | (ref)                                                        | 1.01x slower                                                 |

Benchmark hidden because not significant (2): async_tree_memoization, async_tree_cpu_io_mixed

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231104-pythonperf2-x86_64-python-main-3.13.0a1+-853b4b5 |
|----------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| pidigits       | 264 ms                                                       | 265 ms: 1.00x slower                                         |
| Geometric mean | (ref)                                                        | 1.01x faster                                                 |

Benchmark hidden because not significant (2): nbody, float

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231104-pythonperf2-x86_64-python-main-3.13.0a1+-853b4b5 |
|----------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| regex_effbot   | 3.61 ms                                                      | 3.49 ms: 1.03x faster                                        |
| regex_dna      | 240 ms                                                       | 237 ms: 1.02x faster                                         |
| regex_v8       | 24.4 ms                                                      | 25.1 ms: 1.03x slower                                        |
| Geometric mean | (ref)                                                        | 1.00x faster                                                 |

Benchmark hidden because not significant (1): regex_compile

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231104-pythonperf2-x86_64-python-main-3.13.0a1+-853b4b5 |
|----------------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| unpickle             | 15.3 us                                                      | 14.3 us: 1.07x faster                                        |
| json_loads           | 24.3 us                                                      | 24.1 us: 1.01x faster                                        |
| pickle               | 10.0 us                                                      | 10.1 us: 1.00x slower                                        |
| xml_etree_process    | 58.3 ms                                                      | 58.6 ms: 1.00x slower                                        |
| pickle_dict          | 32.0 us                                                      | 32.4 us: 1.01x slower                                        |
| unpickle_list        | 4.65 us                                                      | 4.73 us: 1.02x slower                                        |
| json_dumps           | 10.3 ms                                                      | 10.4 ms: 1.02x slower                                        |
| xml_etree_iterparse  | 104 ms                                                       | 106 ms: 1.03x slower                                         |
| tomli_loads          | 2.17 sec                                                     | 2.23 sec: 1.03x slower                                       |
| pickle_list          | 4.22 us                                                      | 4.44 us: 1.05x slower                                        |
| unpickle_pure_python | 210 us                                                       | 241 us: 1.15x slower                                         |
| Geometric mean       | (ref)                                                        | 1.02x slower                                                 |

Benchmark hidden because not significant (3): xml_etree_parse, xml_etree_generate, pickle_pure_python

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231104-pythonperf2-x86_64-python-main-3.13.0a1+-853b4b5 |
|------------------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| python_startup         | 11.7 ms                                                      | 12.8 ms: 1.10x slower                                        |
| python_startup_no_site | 8.67 ms                                                      | 11.3 ms: 1.30x slower                                        |
| Geometric mean         | (ref)                                                        | 1.20x slower                                                 |

Benchmarks with tag 'template':
===============================

Benchmark hidden because not significant (1): mako

All benchmarks:
===============

| Benchmark                  | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231104-pythonperf2-x86_64-python-main-3.13.0a1+-853b4b5 |
|----------------------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| comprehensions             | 21.8 us                                                      | 16.5 us: 1.32x faster                                        |
| typing_runtime_protocols   | 150 us                                                       | 121 us: 1.24x faster                                         |
| crypto_pyaes               | 82.4 ms                                                      | 72.0 ms: 1.14x faster                                        |
| unpack_sequence            | 54.5 ns                                                      | 49.9 ns: 1.09x faster                                        |
| scimark_sparse_mat_mult    | 4.49 ms                                                      | 4.12 ms: 1.09x faster                                        |
| raytrace                   | 301 ms                                                       | 278 ms: 1.08x faster                                         |
| sympy_sum                  | 163 ms                                                       | 151 ms: 1.08x faster                                         |
| unpickle                   | 15.3 us                                                      | 14.3 us: 1.07x faster                                        |
| async_generators           | 385 ms                                                       | 361 ms: 1.07x faster                                         |
| sympy_str                  | 305 ms                                                       | 288 ms: 1.06x faster                                         |
| sympy_integrate            | 24.0 ms                                                      | 22.9 ms: 1.05x faster                                        |
| sqlglot_normalize          | 119 ms                                                       | 114 ms: 1.05x faster                                         |
| async_tree_none            | 459 ms                                                       | 439 ms: 1.05x faster                                         |
| chaos                      | 64.1 ms                                                      | 61.4 ms: 1.04x faster                                        |
| coroutines                 | 23.1 ms                                                      | 22.1 ms: 1.04x faster                                        |
| deepcopy_reduce            | 3.41 us                                                      | 3.28 us: 1.04x faster                                        |
| spectral_norm              | 93.9 ms                                                      | 90.5 ms: 1.04x faster                                        |
| generators                 | 37.3 ms                                                      | 36.0 ms: 1.04x faster                                        |
| regex_effbot               | 3.61 ms                                                      | 3.49 ms: 1.03x faster                                        |
| sqlite_synth               | 2.72 us                                                      | 2.66 us: 1.02x faster                                        |
| tornado_http               | 122 ms                                                       | 119 ms: 1.02x faster                                         |
| docutils                   | 2.89 sec                                                     | 2.83 sec: 1.02x faster                                       |
| scimark_monte_carlo        | 69.5 ms                                                      | 68.4 ms: 1.02x faster                                        |
| asyncio_tcp                | 380 ms                                                       | 373 ms: 1.02x faster                                         |
| regex_dna                  | 240 ms                                                       | 237 ms: 1.02x faster                                         |
| json                       | 5.17 ms                                                      | 5.12 ms: 1.01x faster                                        |
| deepcopy                   | 371 us                                                       | 369 us: 1.01x faster                                         |
| sqlglot_optimize           | 58.4 ms                                                      | 58.0 ms: 1.01x faster                                        |
| json_loads                 | 24.3 us                                                      | 24.1 us: 1.01x faster                                        |
| scimark_fft                | 303 ms                                                       | 302 ms: 1.01x faster                                         |
| sympy_expand               | 492 ms                                                       | 490 ms: 1.00x faster                                         |
| mdp                        | 2.56 sec                                                     | 2.55 sec: 1.00x faster                                       |
| nqueens                    | 90.1 ms                                                      | 89.8 ms: 1.00x faster                                        |
| pidigits                   | 264 ms                                                       | 265 ms: 1.00x slower                                         |
| pickle                     | 10.0 us                                                      | 10.1 us: 1.00x slower                                        |
| xml_etree_process          | 58.3 ms                                                      | 58.6 ms: 1.00x slower                                        |
| mypy2                      | 365 ms                                                       | 367 ms: 1.01x slower                                         |
| asyncio_tcp_ssl            | 1.57 sec                                                     | 1.58 sec: 1.01x slower                                       |
| pprint_pformat             | 1.64 sec                                                     | 1.66 sec: 1.01x slower                                       |
| pickle_dict                | 32.0 us                                                      | 32.4 us: 1.01x slower                                        |
| pycparser                  | 1.29 sec                                                     | 1.32 sec: 1.02x slower                                       |
| unpickle_list              | 4.65 us                                                      | 4.73 us: 1.02x slower                                        |
| async_tree_none_tg         | 440 ms                                                       | 448 ms: 1.02x slower                                         |
| json_dumps                 | 10.3 ms                                                      | 10.4 ms: 1.02x slower                                        |
| meteor_contest             | 126 ms                                                       | 129 ms: 1.02x slower                                         |
| logging_simple             | 6.64 us                                                      | 6.80 us: 1.02x slower                                        |
| async_tree_cpu_io_mixed_tg | 706 ms                                                       | 723 ms: 1.02x slower                                         |
| logging_format             | 7.29 us                                                      | 7.47 us: 1.02x slower                                        |
| xml_etree_iterparse        | 104 ms                                                       | 106 ms: 1.03x slower                                         |
| 2to3                       | 285 ms                                                       | 292 ms: 1.03x slower                                         |
| tomli_loads                | 2.17 sec                                                     | 2.23 sec: 1.03x slower                                       |
| async_tree_io              | 1.06 sec                                                     | 1.09 sec: 1.03x slower                                       |
| regex_v8                   | 24.4 ms                                                      | 25.1 ms: 1.03x slower                                        |
| chameleon                  | 7.27 ms                                                      | 7.49 ms: 1.03x slower                                        |
| async_tree_io_tg           | 1.07 sec                                                     | 1.11 sec: 1.03x slower                                       |
| logging_silent             | 93.3 ns                                                      | 96.5 ns: 1.03x slower                                        |
| deepcopy_memo              | 36.6 us                                                      | 38.0 us: 1.04x slower                                        |
| async_tree_memoization_tg  | 554 ms                                                       | 576 ms: 1.04x slower                                         |
| scimark_lu                 | 98.6 ms                                                      | 103 ms: 1.05x slower                                         |
| pathlib                    | 18.7 ms                                                      | 19.7 ms: 1.05x slower                                        |
| pickle_list                | 4.22 us                                                      | 4.44 us: 1.05x slower                                        |
| dulwich_log                | 64.9 ms                                                      | 68.6 ms: 1.06x slower                                        |
| hexiom                     | 5.97 ms                                                      | 6.38 ms: 1.07x slower                                        |
| fannkuch                   | 362 ms                                                       | 392 ms: 1.08x slower                                         |
| python_startup             | 11.7 ms                                                      | 12.8 ms: 1.10x slower                                        |
| telco                      | 7.16 ms                                                      | 7.97 ms: 1.11x slower                                        |
| bench_mp_pool              | 4.96 ms                                                      | 5.61 ms: 1.13x slower                                        |
| deltablue                  | 3.24 ms                                                      | 3.69 ms: 1.14x slower                                        |
| unpickle_pure_python       | 210 us                                                       | 241 us: 1.15x slower                                         |
| go                         | 149 ms                                                       | 173 ms: 1.16x slower                                         |
| richards                   | 45.1 ms                                                      | 52.7 ms: 1.17x slower                                        |
| richards_super             | 50.8 ms                                                      | 59.7 ms: 1.17x slower                                        |
| coverage                   | 66.3 ms                                                      | 78.3 ms: 1.18x slower                                        |
| pyflate                    | 442 ms                                                       | 529 ms: 1.20x slower                                         |
| python_startup_no_site     | 8.67 ms                                                      | 11.3 ms: 1.30x slower                                        |
| scimark_sor                | 107 ms                                                       | 146 ms: 1.37x slower                                         |
| Geometric mean             | (ref)                                                        | 1.01x slower                                                 |

Benchmark hidden because not significant (16): nbody, float, xml_etree_parse, create_gc_cycles, bench_thread_pool, xml_etree_generate, sqlglot_parse, pickle_pure_python, regex_compile, pprint_safe_repr, async_tree_memoization, sqlglot_transpile, asyncio_websockets, async_tree_cpu_io_mixed, gc_traversal, mako
Ignored benchmarks (6) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, dask, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 97.45% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
