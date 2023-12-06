
# Results vs. 3.11.0

- fork: brandtbucher
- ref: justin
- machine: linux-x86_64
- commit hash: 241ce0f
- commit date: 2023-11-11
- overall geometric mean: 1.04x faster \*
- HPT reliability: 85.52%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231111-pythonperf2-x86_64-brandtbucher-justin-3.13.0a1+-241ce0f |
|----------------|:------------------------------------------------------------:|:--------------------------------------------------------------------:|
| 2to3           | 286 ms                                                       | 300 ms: 1.05x slower                                                 |
| chameleon      | 7.42 ms                                                      | 7.65 ms: 1.03x slower                                                |
| tornado_http   | 125 ms                                                       | 120 ms: 1.04x faster                                                 |
| Geometric mean | (ref)                                                        | 1.01x slower                                                         |

Benchmark hidden because not significant (1): docutils

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231111-pythonperf2-x86_64-brandtbucher-justin-3.13.0a1+-241ce0f |
|----------------------------|:------------------------------------------------------------:|:--------------------------------------------------------------------:|
| async_tree_none            | 529 ms                                                       | 445 ms: 1.19x faster                                                 |
| async_tree_memoization     | 648 ms                                                       | 556 ms: 1.17x faster                                                 |
| async_tree_io              | 1.19 sec                                                     | 1.09 sec: 1.09x faster                                               |
| async_tree_cpu_io_mixed    | 762 ms                                                       | 708 ms: 1.08x faster                                                 |
| async_tree_none_tg         | 482 ms                                                       | 449 ms: 1.07x faster                                                 |
| async_tree_io_tg           | 1.17 sec                                                     | 1.11 sec: 1.06x faster                                               |
| async_tree_cpu_io_mixed_tg | 760 ms                                                       | 723 ms: 1.05x faster                                                 |
| async_tree_memoization_tg  | 605 ms                                                       | 582 ms: 1.04x faster                                                 |
| Geometric mean             | (ref)                                                        | 1.09x faster                                                         |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231111-pythonperf2-x86_64-brandtbucher-justin-3.13.0a1+-241ce0f |
|----------------|:------------------------------------------------------------:|:--------------------------------------------------------------------:|
| nbody          | 95.8 ms                                                      | 98.3 ms: 1.03x slower                                                |
| pidigits       | 251 ms                                                       | 265 ms: 1.05x slower                                                 |
| float          | 76.0 ms                                                      | 82.7 ms: 1.09x slower                                                |
| Geometric mean | (ref)                                                        | 1.06x slower                                                         |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231111-pythonperf2-x86_64-brandtbucher-justin-3.13.0a1+-241ce0f |
|----------------|:------------------------------------------------------------:|:--------------------------------------------------------------------:|
| regex_compile  | 157 ms                                                       | 150 ms: 1.05x faster                                                 |
| regex_effbot   | 3.42 ms                                                      | 3.51 ms: 1.03x slower                                                |
| regex_dna      | 226 ms                                                       | 237 ms: 1.05x slower                                                 |
| regex_v8       | 23.7 ms                                                      | 25.4 ms: 1.07x slower                                                |
| Geometric mean | (ref)                                                        | 1.03x slower                                                         |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231111-pythonperf2-x86_64-brandtbucher-justin-3.13.0a1+-241ce0f |
|----------------------|:------------------------------------------------------------:|:--------------------------------------------------------------------:|
| json_dumps           | 13.5 ms                                                      | 10.4 ms: 1.29x faster                                                |
| json_loads           | 29.0 us                                                      | 24.4 us: 1.19x faster                                                |
| xml_etree_parse      | 159 ms                                                       | 145 ms: 1.10x faster                                                 |
| unpickle_pure_python | 236 us                                                       | 222 us: 1.06x faster                                                 |
| pickle_pure_python   | 318 us                                                       | 309 us: 1.03x faster                                                 |
| xml_etree_iterparse  | 106 ms                                                       | 104 ms: 1.02x faster                                                 |
| pickle_dict          | 31.8 us                                                      | 32.7 us: 1.03x slower                                                |
| pickle               | 9.77 us                                                      | 10.3 us: 1.05x slower                                                |
| xml_etree_process    | 56.1 ms                                                      | 59.2 ms: 1.06x slower                                                |
| tomli_loads          | 2.27 sec                                                     | 2.43 sec: 1.07x slower                                               |
| xml_etree_generate   | 80.5 ms                                                      | 85.9 ms: 1.07x slower                                                |
| unpickle_list        | 4.47 us                                                      | 4.79 us: 1.07x slower                                                |
| unpickle             | 13.2 us                                                      | 14.7 us: 1.12x slower                                                |
| pickle_list          | 3.89 us                                                      | 4.42 us: 1.14x slower                                                |
| Geometric mean       | (ref)                                                        | 1.00x faster                                                         |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231111-pythonperf2-x86_64-brandtbucher-justin-3.13.0a1+-241ce0f |
|------------------------|:------------------------------------------------------------:|:--------------------------------------------------------------------:|
| python_startup         | 10.8 ms                                                      | 12.9 ms: 1.19x slower                                                |
| python_startup_no_site | 7.78 ms                                                      | 11.4 ms: 1.46x slower                                                |
| Geometric mean         | (ref)                                                        | 1.32x slower                                                         |

Benchmarks with tag 'template':
===============================

Benchmark hidden because not significant (1): mako

All benchmarks:
===============

| Benchmark                  | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231111-pythonperf2-x86_64-brandtbucher-justin-3.13.0a1+-241ce0f |
|----------------------------|:------------------------------------------------------------:|:--------------------------------------------------------------------:|
| typing_runtime_protocols   | 527 us                                                       | 128 us: 4.12x faster                                                 |
| asyncio_tcp                | 752 ms                                                       | 368 ms: 2.04x faster                                                 |
| asyncio_tcp_ssl            | 3.09 sec                                                     | 1.58 sec: 1.95x faster                                               |
| generators                 | 56.4 ms                                                      | 35.5 ms: 1.59x faster                                                |
| json_dumps                 | 13.5 ms                                                      | 10.4 ms: 1.29x faster                                                |
| coroutines                 | 27.9 ms                                                      | 22.7 ms: 1.22x faster                                                |
| sympy_sum                  | 184 ms                                                       | 153 ms: 1.21x faster                                                 |
| mypy2                      | 449 ms                                                       | 374 ms: 1.20x faster                                                 |
| json_loads                 | 29.0 us                                                      | 24.4 us: 1.19x faster                                                |
| async_tree_none            | 529 ms                                                       | 445 ms: 1.19x faster                                                 |
| async_tree_memoization     | 648 ms                                                       | 556 ms: 1.17x faster                                                 |
| sympy_str                  | 336 ms                                                       | 294 ms: 1.14x faster                                                 |
| comprehensions             | 24.8 us                                                      | 21.9 us: 1.13x faster                                                |
| richards_super             | 65.2 ms                                                      | 58.8 ms: 1.11x faster                                                |
| sympy_expand               | 550 ms                                                       | 498 ms: 1.11x faster                                                 |
| scimark_lu                 | 115 ms                                                       | 105 ms: 1.10x faster                                                 |
| json                       | 5.59 ms                                                      | 5.08 ms: 1.10x faster                                                |
| sqlglot_parse              | 1.55 ms                                                      | 1.41 ms: 1.10x faster                                                |
| logging_simple             | 7.21 us                                                      | 6.56 us: 1.10x faster                                                |
| xml_etree_parse            | 159 ms                                                       | 145 ms: 1.10x faster                                                 |
| async_tree_io              | 1.19 sec                                                     | 1.09 sec: 1.09x faster                                               |
| logging_format             | 7.83 us                                                      | 7.19 us: 1.09x faster                                                |
| raytrace                   | 308 ms                                                       | 285 ms: 1.08x faster                                                 |
| async_tree_cpu_io_mixed    | 762 ms                                                       | 708 ms: 1.08x faster                                                 |
| async_tree_none_tg         | 482 ms                                                       | 449 ms: 1.07x faster                                                 |
| sympy_integrate            | 25.6 ms                                                      | 23.9 ms: 1.07x faster                                                |
| fannkuch                   | 457 ms                                                       | 428 ms: 1.07x faster                                                 |
| logging_silent             | 102 ns                                                       | 95.6 ns: 1.07x faster                                                |
| unpickle_pure_python       | 236 us                                                       | 222 us: 1.06x faster                                                 |
| deepcopy                   | 389 us                                                       | 367 us: 1.06x faster                                                 |
| sqlglot_transpile          | 1.94 ms                                                      | 1.83 ms: 1.06x faster                                                |
| async_tree_io_tg           | 1.17 sec                                                     | 1.11 sec: 1.06x faster                                               |
| chaos                      | 71.6 ms                                                      | 68.0 ms: 1.05x faster                                                |
| async_tree_cpu_io_mixed_tg | 760 ms                                                       | 723 ms: 1.05x faster                                                 |
| deltablue                  | 4.03 ms                                                      | 3.83 ms: 1.05x faster                                                |
| regex_compile              | 157 ms                                                       | 150 ms: 1.05x faster                                                 |
| unpack_sequence            | 44.9 ns                                                      | 43.1 ns: 1.04x faster                                                |
| crypto_pyaes               | 81.8 ms                                                      | 78.5 ms: 1.04x faster                                                |
| bench_thread_pool          | 1.02 ms                                                      | 980 us: 1.04x faster                                                 |
| mdp                        | 2.72 sec                                                     | 2.61 sec: 1.04x faster                                               |
| async_tree_memoization_tg  | 605 ms                                                       | 582 ms: 1.04x faster                                                 |
| gc_traversal               | 4.06 ms                                                      | 3.91 ms: 1.04x faster                                                |
| tornado_http               | 125 ms                                                       | 120 ms: 1.04x faster                                                 |
| create_gc_cycles           | 1.59 ms                                                      | 1.53 ms: 1.04x faster                                                |
| sqlglot_normalize          | 122 ms                                                       | 118 ms: 1.04x faster                                                 |
| spectral_norm              | 94.0 ms                                                      | 91.1 ms: 1.03x faster                                                |
| pickle_pure_python         | 318 us                                                       | 309 us: 1.03x faster                                                 |
| deepcopy_reduce            | 3.37 us                                                      | 3.30 us: 1.02x faster                                                |
| xml_etree_iterparse        | 106 ms                                                       | 104 ms: 1.02x faster                                                 |
| deepcopy_memo              | 37.3 us                                                      | 37.9 us: 1.02x slower                                                |
| meteor_contest             | 130 ms                                                       | 133 ms: 1.02x slower                                                 |
| richards                   | 49.9 ms                                                      | 50.9 ms: 1.02x slower                                                |
| nbody                      | 95.8 ms                                                      | 98.3 ms: 1.03x slower                                                |
| regex_effbot               | 3.42 ms                                                      | 3.51 ms: 1.03x slower                                                |
| pathlib                    | 19.1 ms                                                      | 19.7 ms: 1.03x slower                                                |
| pickle_dict                | 31.8 us                                                      | 32.7 us: 1.03x slower                                                |
| chameleon                  | 7.42 ms                                                      | 7.65 ms: 1.03x slower                                                |
| pycparser                  | 1.28 sec                                                     | 1.32 sec: 1.03x slower                                               |
| pprint_pformat             | 1.63 sec                                                     | 1.70 sec: 1.04x slower                                               |
| regex_dna                  | 226 ms                                                       | 237 ms: 1.05x slower                                                 |
| go                         | 166 ms                                                       | 174 ms: 1.05x slower                                                 |
| pickle                     | 9.77 us                                                      | 10.3 us: 1.05x slower                                                |
| 2to3                       | 286 ms                                                       | 300 ms: 1.05x slower                                                 |
| nqueens                    | 99.2 ms                                                      | 104 ms: 1.05x slower                                                 |
| pidigits                   | 251 ms                                                       | 265 ms: 1.05x slower                                                 |
| xml_etree_process          | 56.1 ms                                                      | 59.2 ms: 1.06x slower                                                |
| tomli_loads                | 2.27 sec                                                     | 2.43 sec: 1.07x slower                                               |
| scimark_monte_carlo        | 70.6 ms                                                      | 75.2 ms: 1.07x slower                                                |
| xml_etree_generate         | 80.5 ms                                                      | 85.9 ms: 1.07x slower                                                |
| pprint_safe_repr           | 780 ms                                                       | 832 ms: 1.07x slower                                                 |
| unpickle_list              | 4.47 us                                                      | 4.79 us: 1.07x slower                                                |
| regex_v8                   | 23.7 ms                                                      | 25.4 ms: 1.07x slower                                                |
| sqlite_synth               | 2.49 us                                                      | 2.69 us: 1.08x slower                                                |
| float                      | 76.0 ms                                                      | 82.7 ms: 1.09x slower                                                |
| unpickle                   | 13.2 us                                                      | 14.7 us: 1.12x slower                                                |
| pyflate                    | 453 ms                                                       | 507 ms: 1.12x slower                                                 |
| scimark_sparse_mat_mult    | 4.04 ms                                                      | 4.55 ms: 1.13x slower                                                |
| pickle_list                | 3.89 us                                                      | 4.42 us: 1.14x slower                                                |
| hexiom                     | 6.97 ms                                                      | 8.19 ms: 1.17x slower                                                |
| telco                      | 6.91 ms                                                      | 8.16 ms: 1.18x slower                                                |
| python_startup             | 10.8 ms                                                      | 12.9 ms: 1.19x slower                                                |
| async_generators           | 322 ms                                                       | 389 ms: 1.21x slower                                                 |
| scimark_fft                | 281 ms                                                       | 348 ms: 1.24x slower                                                 |
| coverage                   | 66.6 ms                                                      | 82.4 ms: 1.24x slower                                                |
| bench_mp_pool              | 4.63 ms                                                      | 6.19 ms: 1.34x slower                                                |
| scimark_sor                | 109 ms                                                       | 150 ms: 1.37x slower                                                 |
| python_startup_no_site     | 7.78 ms                                                      | 11.4 ms: 1.46x slower                                                |
| Geometric mean             | (ref)                                                        | 1.04x faster                                                         |

Benchmark hidden because not significant (5): asyncio_websockets, dulwich_log, sqlglot_optimize, mako, docutils
Ignored benchmarks (12) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, dask, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift


# HPT report

- Reliability score: 85.52% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
