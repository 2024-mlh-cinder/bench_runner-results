
# Results vs. 3.12.0

- fork: faster-cpython
- ref: likelihood_on_trace
- machine: linux-x86_64
- commit hash: 55d5c8d
- commit date: 2023-11-16
- overall geometric mean: 1.09x slower \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.03x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231116-pythonperf2-x86_64-faster%2dcpython-likelihood_on_trace-3.13.0a1+-55d5c8d |
|----------------|:------------------------------------------------------------:|:-------------------------------------------------------------------------------------:|
| 2to3           | 285 ms                                                       | 315 ms: 1.11x slower                                                                  |
| chameleon      | 7.27 ms                                                      | 7.98 ms: 1.10x slower                                                                 |
| docutils       | 2.89 sec                                                     | 2.94 sec: 1.02x slower                                                                |
| tornado_http   | 122 ms                                                       | 124 ms: 1.02x slower                                                                  |
| Geometric mean | (ref)                                                        | 1.06x slower                                                                          |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231116-pythonperf2-x86_64-faster%2dcpython-likelihood_on_trace-3.13.0a1+-55d5c8d |
|----------------------------|:------------------------------------------------------------:|:-------------------------------------------------------------------------------------:|
| async_tree_none            | 459 ms                                                       | 450 ms: 1.02x faster                                                                  |
| async_tree_cpu_io_mixed    | 704 ms                                                       | 715 ms: 1.01x slower                                                                  |
| async_tree_memoization     | 554 ms                                                       | 563 ms: 1.02x slower                                                                  |
| async_tree_memoization_tg  | 554 ms                                                       | 565 ms: 1.02x slower                                                                  |
| async_tree_cpu_io_mixed_tg | 706 ms                                                       | 729 ms: 1.03x slower                                                                  |
| async_tree_none_tg         | 440 ms                                                       | 454 ms: 1.03x slower                                                                  |
| async_tree_io              | 1.06 sec                                                     | 1.10 sec: 1.04x slower                                                                |
| async_tree_io_tg           | 1.07 sec                                                     | 1.12 sec: 1.04x slower                                                                |
| Geometric mean             | (ref)                                                        | 1.02x slower                                                                          |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231116-pythonperf2-x86_64-faster%2dcpython-likelihood_on_trace-3.13.0a1+-55d5c8d |
|----------------|:------------------------------------------------------------:|:-------------------------------------------------------------------------------------:|
| pidigits       | 264 ms                                                       | 267 ms: 1.01x slower                                                                  |
| float          | 81.6 ms                                                      | 105 ms: 1.29x slower                                                                  |
| nbody          | 88.2 ms                                                      | 115 ms: 1.31x slower                                                                  |
| Geometric mean | (ref)                                                        | 1.19x slower                                                                          |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231116-pythonperf2-x86_64-faster%2dcpython-likelihood_on_trace-3.13.0a1+-55d5c8d |
|----------------|:------------------------------------------------------------:|:-------------------------------------------------------------------------------------:|
| regex_effbot   | 3.61 ms                                                      | 3.52 ms: 1.03x faster                                                                 |
| regex_dna      | 240 ms                                                       | 244 ms: 1.02x slower                                                                  |
| regex_v8       | 24.4 ms                                                      | 26.2 ms: 1.07x slower                                                                 |
| regex_compile  | 145 ms                                                       | 176 ms: 1.21x slower                                                                  |
| Geometric mean | (ref)                                                        | 1.07x slower                                                                          |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231116-pythonperf2-x86_64-faster%2dcpython-likelihood_on_trace-3.13.0a1+-55d5c8d |
|----------------------|:------------------------------------------------------------:|:-------------------------------------------------------------------------------------:|
| unpickle             | 15.3 us                                                      | 14.6 us: 1.05x faster                                                                 |
| pickle_pure_python   | 319 us                                                       | 314 us: 1.02x faster                                                                  |
| pickle_dict          | 32.0 us                                                      | 31.7 us: 1.01x faster                                                                 |
| xml_etree_parse      | 147 ms                                                       | 148 ms: 1.01x slower                                                                  |
| unpickle_list        | 4.65 us                                                      | 4.74 us: 1.02x slower                                                                 |
| xml_etree_generate   | 85.3 ms                                                      | 87.0 ms: 1.02x slower                                                                 |
| pickle               | 10.0 us                                                      | 10.3 us: 1.02x slower                                                                 |
| json_dumps           | 10.3 ms                                                      | 10.6 ms: 1.03x slower                                                                 |
| json_loads           | 24.3 us                                                      | 25.2 us: 1.04x slower                                                                 |
| pickle_list          | 4.22 us                                                      | 4.53 us: 1.07x slower                                                                 |
| xml_etree_iterparse  | 104 ms                                                       | 114 ms: 1.10x slower                                                                  |
| unpickle_pure_python | 210 us                                                       | 254 us: 1.21x slower                                                                  |
| tomli_loads          | 2.17 sec                                                     | 3.02 sec: 1.39x slower                                                                |
| Geometric mean       | (ref)                                                        | 1.06x slower                                                                          |

Benchmark hidden because not significant (1): xml_etree_process

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231116-pythonperf2-x86_64-faster%2dcpython-likelihood_on_trace-3.13.0a1+-55d5c8d |
|------------------------|:------------------------------------------------------------:|:-------------------------------------------------------------------------------------:|
| python_startup         | 11.7 ms                                                      | 12.9 ms: 1.10x slower                                                                 |
| python_startup_no_site | 8.67 ms                                                      | 11.4 ms: 1.31x slower                                                                 |
| Geometric mean         | (ref)                                                        | 1.20x slower                                                                          |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231116-pythonperf2-x86_64-faster%2dcpython-likelihood_on_trace-3.13.0a1+-55d5c8d |
|-----------|:------------------------------------------------------------:|:-------------------------------------------------------------------------------------:|
| mako      | 10.1 ms                                                      | 15.9 ms: 1.58x slower                                                                 |

All benchmarks:
===============

| Benchmark                  | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231116-pythonperf2-x86_64-faster%2dcpython-likelihood_on_trace-3.13.0a1+-55d5c8d |
|----------------------------|:------------------------------------------------------------:|:-------------------------------------------------------------------------------------:|
| typing_runtime_protocols   | 150 us                                                       | 138 us: 1.09x faster                                                                  |
| generators                 | 37.3 ms                                                      | 34.6 ms: 1.08x faster                                                                 |
| gc_traversal               | 3.70 ms                                                      | 3.47 ms: 1.07x faster                                                                 |
| bench_mp_pool              | 4.96 ms                                                      | 4.70 ms: 1.05x faster                                                                 |
| unpickle                   | 15.3 us                                                      | 14.6 us: 1.05x faster                                                                 |
| unpack_sequence            | 54.5 ns                                                      | 52.0 ns: 1.05x faster                                                                 |
| raytrace                   | 301 ms                                                       | 287 ms: 1.05x faster                                                                  |
| coroutines                 | 23.1 ms                                                      | 22.1 ms: 1.04x faster                                                                 |
| sympy_sum                  | 163 ms                                                       | 157 ms: 1.03x faster                                                                  |
| deepcopy_reduce            | 3.41 us                                                      | 3.30 us: 1.03x faster                                                                 |
| spectral_norm              | 93.9 ms                                                      | 91.0 ms: 1.03x faster                                                                 |
| regex_effbot               | 3.61 ms                                                      | 3.52 ms: 1.03x faster                                                                 |
| async_tree_none            | 459 ms                                                       | 450 ms: 1.02x faster                                                                  |
| sqlglot_normalize          | 119 ms                                                       | 117 ms: 1.02x faster                                                                  |
| asyncio_tcp                | 380 ms                                                       | 373 ms: 1.02x faster                                                                  |
| pickle_pure_python         | 319 us                                                       | 314 us: 1.02x faster                                                                  |
| async_generators           | 385 ms                                                       | 380 ms: 1.01x faster                                                                  |
| pickle_dict                | 32.0 us                                                      | 31.7 us: 1.01x faster                                                                 |
| json                       | 5.17 ms                                                      | 5.20 ms: 1.01x slower                                                                 |
| logging_simple             | 6.64 us                                                      | 6.69 us: 1.01x slower                                                                 |
| xml_etree_parse            | 147 ms                                                       | 148 ms: 1.01x slower                                                                  |
| pidigits                   | 264 ms                                                       | 267 ms: 1.01x slower                                                                  |
| deepcopy                   | 371 us                                                       | 376 us: 1.01x slower                                                                  |
| logging_format             | 7.29 us                                                      | 7.39 us: 1.01x slower                                                                 |
| asyncio_tcp_ssl            | 1.57 sec                                                     | 1.60 sec: 1.01x slower                                                                |
| async_tree_cpu_io_mixed    | 704 ms                                                       | 715 ms: 1.01x slower                                                                  |
| tornado_http               | 122 ms                                                       | 124 ms: 1.02x slower                                                                  |
| docutils                   | 2.89 sec                                                     | 2.94 sec: 1.02x slower                                                                |
| regex_dna                  | 240 ms                                                       | 244 ms: 1.02x slower                                                                  |
| async_tree_memoization     | 554 ms                                                       | 563 ms: 1.02x slower                                                                  |
| sympy_str                  | 305 ms                                                       | 310 ms: 1.02x slower                                                                  |
| unpickle_list              | 4.65 us                                                      | 4.74 us: 1.02x slower                                                                 |
| xml_etree_generate         | 85.3 ms                                                      | 87.0 ms: 1.02x slower                                                                 |
| async_tree_memoization_tg  | 554 ms                                                       | 565 ms: 1.02x slower                                                                  |
| pickle                     | 10.0 us                                                      | 10.3 us: 1.02x slower                                                                 |
| sqlglot_optimize           | 58.4 ms                                                      | 59.7 ms: 1.02x slower                                                                 |
| sqlite_synth               | 2.72 us                                                      | 2.78 us: 1.02x slower                                                                 |
| bench_thread_pool          | 956 us                                                       | 984 us: 1.03x slower                                                                  |
| async_tree_cpu_io_mixed_tg | 706 ms                                                       | 729 ms: 1.03x slower                                                                  |
| async_tree_none_tg         | 440 ms                                                       | 454 ms: 1.03x slower                                                                  |
| json_dumps                 | 10.3 ms                                                      | 10.6 ms: 1.03x slower                                                                 |
| dask                       | 394 ms                                                       | 407 ms: 1.04x slower                                                                  |
| json_loads                 | 24.3 us                                                      | 25.2 us: 1.04x slower                                                                 |
| mypy2                      | 365 ms                                                       | 380 ms: 1.04x slower                                                                  |
| async_tree_io              | 1.06 sec                                                     | 1.10 sec: 1.04x slower                                                                |
| sqlglot_parse              | 1.41 ms                                                      | 1.47 ms: 1.04x slower                                                                 |
| async_tree_io_tg           | 1.07 sec                                                     | 1.12 sec: 1.04x slower                                                                |
| sympy_integrate            | 24.0 ms                                                      | 25.1 ms: 1.04x slower                                                                 |
| sqlglot_transpile          | 1.80 ms                                                      | 1.88 ms: 1.04x slower                                                                 |
| pathlib                    | 18.7 ms                                                      | 19.6 ms: 1.05x slower                                                                 |
| pycparser                  | 1.29 sec                                                     | 1.36 sec: 1.05x slower                                                                |
| crypto_pyaes               | 82.4 ms                                                      | 87.3 ms: 1.06x slower                                                                 |
| mdp                        | 2.56 sec                                                     | 2.71 sec: 1.06x slower                                                                |
| regex_v8                   | 24.4 ms                                                      | 26.2 ms: 1.07x slower                                                                 |
| sympy_expand               | 492 ms                                                       | 527 ms: 1.07x slower                                                                  |
| logging_silent             | 93.3 ns                                                      | 100 ns: 1.07x slower                                                                  |
| pickle_list                | 4.22 us                                                      | 4.53 us: 1.07x slower                                                                 |
| scimark_lu                 | 98.6 ms                                                      | 107 ms: 1.09x slower                                                                  |
| meteor_contest             | 126 ms                                                       | 138 ms: 1.09x slower                                                                  |
| chameleon                  | 7.27 ms                                                      | 7.98 ms: 1.10x slower                                                                 |
| dulwich_log                | 64.9 ms                                                      | 71.4 ms: 1.10x slower                                                                 |
| xml_etree_iterparse        | 104 ms                                                       | 114 ms: 1.10x slower                                                                  |
| pprint_safe_repr           | 808 ms                                                       | 891 ms: 1.10x slower                                                                  |
| python_startup             | 11.7 ms                                                      | 12.9 ms: 1.10x slower                                                                 |
| 2to3                       | 285 ms                                                       | 315 ms: 1.11x slower                                                                  |
| pprint_pformat             | 1.64 sec                                                     | 1.82 sec: 1.11x slower                                                                |
| chaos                      | 64.1 ms                                                      | 72.2 ms: 1.13x slower                                                                 |
| deepcopy_memo              | 36.6 us                                                      | 42.3 us: 1.16x slower                                                                 |
| scimark_monte_carlo        | 69.5 ms                                                      | 82.4 ms: 1.18x slower                                                                 |
| telco                      | 7.16 ms                                                      | 8.53 ms: 1.19x slower                                                                 |
| richards_super             | 50.8 ms                                                      | 60.8 ms: 1.20x slower                                                                 |
| coverage                   | 66.3 ms                                                      | 79.8 ms: 1.20x slower                                                                 |
| richards                   | 45.1 ms                                                      | 54.2 ms: 1.20x slower                                                                 |
| unpickle_pure_python       | 210 us                                                       | 254 us: 1.21x slower                                                                  |
| regex_compile              | 145 ms                                                       | 176 ms: 1.21x slower                                                                  |
| go                         | 149 ms                                                       | 185 ms: 1.25x slower                                                                  |
| float                      | 81.6 ms                                                      | 105 ms: 1.29x slower                                                                  |
| pyflate                    | 442 ms                                                       | 575 ms: 1.30x slower                                                                  |
| nbody                      | 88.2 ms                                                      | 115 ms: 1.31x slower                                                                  |
| nqueens                    | 90.1 ms                                                      | 118 ms: 1.31x slower                                                                  |
| python_startup_no_site     | 8.67 ms                                                      | 11.4 ms: 1.31x slower                                                                 |
| scimark_fft                | 303 ms                                                       | 401 ms: 1.32x slower                                                                  |
| comprehensions             | 21.8 us                                                      | 29.6 us: 1.36x slower                                                                 |
| tomli_loads                | 2.17 sec                                                     | 3.02 sec: 1.39x slower                                                                |
| scimark_sor                | 107 ms                                                       | 150 ms: 1.41x slower                                                                  |
| fannkuch                   | 362 ms                                                       | 526 ms: 1.45x slower                                                                  |
| deltablue                  | 3.24 ms                                                      | 4.78 ms: 1.48x slower                                                                 |
| mako                       | 10.1 ms                                                      | 15.9 ms: 1.58x slower                                                                 |
| scimark_sparse_mat_mult    | 4.49 ms                                                      | 7.23 ms: 1.61x slower                                                                 |
| hexiom                     | 5.97 ms                                                      | 11.0 ms: 1.85x slower                                                                 |
| Geometric mean             | (ref)                                                        | 1.09x slower                                                                          |

Benchmark hidden because not significant (3): create_gc_cycles, xml_etree_process, asyncio_websockets
Ignored benchmarks (5) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.03x
- 95% likely to have a slowdown of 1.03x
- 99% likely to have a slowdown of 1.03x
