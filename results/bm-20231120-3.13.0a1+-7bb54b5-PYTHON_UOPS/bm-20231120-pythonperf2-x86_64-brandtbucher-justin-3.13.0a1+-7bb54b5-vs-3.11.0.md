
# Results vs. 3.11.0

- fork: brandtbucher
- ref: justin
- machine: linux-x86_64
- commit hash: 7bb54b5
- commit date: 2023-11-20
- overall geometric mean: 1.04x faster \*
- HPT reliability: 86.22%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-pythonperf2-x86_64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|----------------|:------------------------------------------------------------:|:--------------------------------------------------------------------:|
| 2to3           | 286 ms                                                       | 300 ms: 1.05x slower                                                 |
| chameleon      | 7.42 ms                                                      | 7.58 ms: 1.02x slower                                                |
| docutils       | 2.87 sec                                                     | 2.88 sec: 1.00x slower                                               |
| tornado_http   | 125 ms                                                       | 121 ms: 1.03x faster                                                 |
| Geometric mean | (ref)                                                        | 1.01x slower                                                         |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-pythonperf2-x86_64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|----------------------------|:------------------------------------------------------------:|:--------------------------------------------------------------------:|
| async_tree_none            | 529 ms                                                       | 439 ms: 1.20x faster                                                 |
| async_tree_memoization     | 648 ms                                                       | 550 ms: 1.18x faster                                                 |
| async_tree_io              | 1.19 sec                                                     | 1.08 sec: 1.10x faster                                               |
| async_tree_cpu_io_mixed    | 762 ms                                                       | 701 ms: 1.09x faster                                                 |
| async_tree_none_tg         | 482 ms                                                       | 446 ms: 1.08x faster                                                 |
| async_tree_io_tg           | 1.17 sec                                                     | 1.10 sec: 1.06x faster                                               |
| async_tree_cpu_io_mixed_tg | 760 ms                                                       | 719 ms: 1.06x faster                                                 |
| async_tree_memoization_tg  | 605 ms                                                       | 575 ms: 1.05x faster                                                 |
| Geometric mean             | (ref)                                                        | 1.10x faster                                                         |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-pythonperf2-x86_64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|----------------|:------------------------------------------------------------:|:--------------------------------------------------------------------:|
| float          | 76.0 ms                                                      | 79.1 ms: 1.04x slower                                                |
| pidigits       | 251 ms                                                       | 265 ms: 1.06x slower                                                 |
| Geometric mean | (ref)                                                        | 1.03x slower                                                         |

Benchmark hidden because not significant (1): nbody

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-pythonperf2-x86_64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|----------------|:------------------------------------------------------------:|:--------------------------------------------------------------------:|
| regex_compile  | 157 ms                                                       | 150 ms: 1.05x faster                                                 |
| regex_effbot   | 3.42 ms                                                      | 3.53 ms: 1.03x slower                                                |
| regex_dna      | 226 ms                                                       | 244 ms: 1.08x slower                                                 |
| regex_v8       | 23.7 ms                                                      | 25.7 ms: 1.09x slower                                                |
| Geometric mean | (ref)                                                        | 1.04x slower                                                         |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-pythonperf2-x86_64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|----------------------|:------------------------------------------------------------:|:--------------------------------------------------------------------:|
| json_dumps           | 13.5 ms                                                      | 10.8 ms: 1.25x faster                                                |
| json_loads           | 29.0 us                                                      | 25.3 us: 1.15x faster                                                |
| xml_etree_parse      | 159 ms                                                       | 143 ms: 1.11x faster                                                 |
| unpickle_pure_python | 236 us                                                       | 221 us: 1.07x faster                                                 |
| pickle_pure_python   | 318 us                                                       | 308 us: 1.03x faster                                                 |
| xml_etree_iterparse  | 106 ms                                                       | 105 ms: 1.01x faster                                                 |
| pickle_dict          | 31.8 us                                                      | 31.6 us: 1.00x faster                                                |
| unpickle_list        | 4.47 us                                                      | 4.54 us: 1.01x slower                                                |
| pickle               | 9.77 us                                                      | 10.2 us: 1.05x slower                                                |
| xml_etree_process    | 56.1 ms                                                      | 59.1 ms: 1.05x slower                                                |
| xml_etree_generate   | 80.5 ms                                                      | 86.1 ms: 1.07x slower                                                |
| unpickle             | 13.2 us                                                      | 14.7 us: 1.11x slower                                                |
| pickle_list          | 3.89 us                                                      | 4.48 us: 1.15x slower                                                |
| Geometric mean       | (ref)                                                        | 1.01x faster                                                         |

Benchmark hidden because not significant (1): tomli_loads

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-pythonperf2-x86_64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|------------------------|:------------------------------------------------------------:|:--------------------------------------------------------------------:|
| python_startup         | 10.8 ms                                                      | 12.9 ms: 1.19x slower                                                |
| python_startup_no_site | 7.78 ms                                                      | 11.3 ms: 1.46x slower                                                |
| Geometric mean         | (ref)                                                        | 1.32x slower                                                         |

Benchmarks with tag 'template':
===============================

Benchmark hidden because not significant (1): mako

All benchmarks:
===============

| Benchmark                  | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-pythonperf2-x86_64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|----------------------------|:------------------------------------------------------------:|:--------------------------------------------------------------------:|
| typing_runtime_protocols   | 527 us                                                       | 130 us: 4.04x faster                                                 |
| asyncio_tcp                | 752 ms                                                       | 369 ms: 2.04x faster                                                 |
| asyncio_tcp_ssl            | 3.09 sec                                                     | 1.57 sec: 1.96x faster                                               |
| generators                 | 56.4 ms                                                      | 35.7 ms: 1.58x faster                                                |
| json_dumps                 | 13.5 ms                                                      | 10.8 ms: 1.25x faster                                                |
| comprehensions             | 24.8 us                                                      | 20.2 us: 1.23x faster                                                |
| coroutines                 | 27.9 ms                                                      | 22.8 ms: 1.22x faster                                                |
| async_tree_none            | 529 ms                                                       | 439 ms: 1.20x faster                                                 |
| gc_traversal               | 4.06 ms                                                      | 3.42 ms: 1.19x faster                                                |
| mypy2                      | 449 ms                                                       | 381 ms: 1.18x faster                                                 |
| async_tree_memoization     | 648 ms                                                       | 550 ms: 1.18x faster                                                 |
| sympy_sum                  | 184 ms                                                       | 159 ms: 1.16x faster                                                 |
| json_loads                 | 29.0 us                                                      | 25.3 us: 1.15x faster                                                |
| richards_super             | 65.2 ms                                                      | 57.0 ms: 1.14x faster                                                |
| sympy_str                  | 336 ms                                                       | 301 ms: 1.12x faster                                                 |
| scimark_lu                 | 115 ms                                                       | 103 ms: 1.12x faster                                                 |
| xml_etree_parse            | 159 ms                                                       | 143 ms: 1.11x faster                                                 |
| fannkuch                   | 457 ms                                                       | 413 ms: 1.11x faster                                                 |
| async_tree_io              | 1.19 sec                                                     | 1.08 sec: 1.10x faster                                               |
| sympy_expand               | 550 ms                                                       | 504 ms: 1.09x faster                                                 |
| logging_simple             | 7.21 us                                                      | 6.61 us: 1.09x faster                                                |
| deltablue                  | 4.03 ms                                                      | 3.69 ms: 1.09x faster                                                |
| sqlglot_parse              | 1.55 ms                                                      | 1.42 ms: 1.09x faster                                                |
| async_tree_cpu_io_mixed    | 762 ms                                                       | 701 ms: 1.09x faster                                                 |
| async_tree_none_tg         | 482 ms                                                       | 446 ms: 1.08x faster                                                 |
| json                       | 5.59 ms                                                      | 5.23 ms: 1.07x faster                                                |
| unpickle_pure_python       | 236 us                                                       | 221 us: 1.07x faster                                                 |
| raytrace                   | 308 ms                                                       | 288 ms: 1.07x faster                                                 |
| async_tree_io_tg           | 1.17 sec                                                     | 1.10 sec: 1.06x faster                                               |
| async_tree_cpu_io_mixed_tg | 760 ms                                                       | 719 ms: 1.06x faster                                                 |
| bench_thread_pool          | 1.02 ms                                                      | 966 us: 1.06x faster                                                 |
| sympy_integrate            | 25.6 ms                                                      | 24.3 ms: 1.06x faster                                                |
| deepcopy                   | 389 us                                                       | 369 us: 1.05x faster                                                 |
| sqlglot_transpile          | 1.94 ms                                                      | 1.84 ms: 1.05x faster                                                |
| async_tree_memoization_tg  | 605 ms                                                       | 575 ms: 1.05x faster                                                 |
| logging_format             | 7.83 us                                                      | 7.46 us: 1.05x faster                                                |
| regex_compile              | 157 ms                                                       | 150 ms: 1.05x faster                                                 |
| logging_silent             | 102 ns                                                       | 97.7 ns: 1.04x faster                                                |
| mdp                        | 2.72 sec                                                     | 2.61 sec: 1.04x faster                                               |
| create_gc_cycles           | 1.59 ms                                                      | 1.54 ms: 1.04x faster                                                |
| dask                       | 417 ms                                                       | 403 ms: 1.03x faster                                                 |
| pickle_pure_python         | 318 us                                                       | 308 us: 1.03x faster                                                 |
| tornado_http               | 125 ms                                                       | 121 ms: 1.03x faster                                                 |
| chaos                      | 71.6 ms                                                      | 69.6 ms: 1.03x faster                                                |
| unpack_sequence            | 44.9 ns                                                      | 43.9 ns: 1.02x faster                                                |
| sqlglot_normalize          | 122 ms                                                       | 120 ms: 1.02x faster                                                 |
| deepcopy_reduce            | 3.37 us                                                      | 3.32 us: 1.01x faster                                                |
| pathlib                    | 19.1 ms                                                      | 18.9 ms: 1.01x faster                                                |
| deepcopy_memo              | 37.3 us                                                      | 36.9 us: 1.01x faster                                                |
| xml_etree_iterparse        | 106 ms                                                       | 105 ms: 1.01x faster                                                 |
| pickle_dict                | 31.8 us                                                      | 31.6 us: 1.00x faster                                                |
| docutils                   | 2.87 sec                                                     | 2.88 sec: 1.00x slower                                               |
| meteor_contest             | 130 ms                                                       | 132 ms: 1.01x slower                                                 |
| unpickle_list              | 4.47 us                                                      | 4.54 us: 1.01x slower                                                |
| go                         | 166 ms                                                       | 168 ms: 1.02x slower                                                 |
| nqueens                    | 99.2 ms                                                      | 101 ms: 1.02x slower                                                 |
| chameleon                  | 7.42 ms                                                      | 7.58 ms: 1.02x slower                                                |
| pycparser                  | 1.28 sec                                                     | 1.32 sec: 1.03x slower                                               |
| regex_effbot               | 3.42 ms                                                      | 3.53 ms: 1.03x slower                                                |
| sqlglot_optimize           | 59.2 ms                                                      | 61.6 ms: 1.04x slower                                                |
| float                      | 76.0 ms                                                      | 79.1 ms: 1.04x slower                                                |
| bench_mp_pool              | 4.63 ms                                                      | 4.82 ms: 1.04x slower                                                |
| pickle                     | 9.77 us                                                      | 10.2 us: 1.05x slower                                                |
| 2to3                       | 286 ms                                                       | 300 ms: 1.05x slower                                                 |
| xml_etree_process          | 56.1 ms                                                      | 59.1 ms: 1.05x slower                                                |
| pidigits                   | 251 ms                                                       | 265 ms: 1.06x slower                                                 |
| pprint_pformat             | 1.63 sec                                                     | 1.74 sec: 1.06x slower                                               |
| xml_etree_generate         | 80.5 ms                                                      | 86.1 ms: 1.07x slower                                                |
| regex_dna                  | 226 ms                                                       | 244 ms: 1.08x slower                                                 |
| regex_v8                   | 23.7 ms                                                      | 25.7 ms: 1.09x slower                                                |
| spectral_norm              | 94.0 ms                                                      | 102 ms: 1.09x slower                                                 |
| pprint_safe_repr           | 780 ms                                                       | 852 ms: 1.09x slower                                                 |
| sqlite_synth               | 2.49 us                                                      | 2.74 us: 1.10x slower                                                |
| unpickle                   | 13.2 us                                                      | 14.7 us: 1.11x slower                                                |
| hexiom                     | 6.97 ms                                                      | 7.80 ms: 1.12x slower                                                |
| scimark_monte_carlo        | 70.6 ms                                                      | 79.0 ms: 1.12x slower                                                |
| scimark_sparse_mat_mult    | 4.04 ms                                                      | 4.59 ms: 1.14x slower                                                |
| pyflate                    | 453 ms                                                       | 520 ms: 1.15x slower                                                 |
| pickle_list                | 3.89 us                                                      | 4.48 us: 1.15x slower                                                |
| python_startup             | 10.8 ms                                                      | 12.9 ms: 1.19x slower                                                |
| telco                      | 6.91 ms                                                      | 8.29 ms: 1.20x slower                                                |
| async_generators           | 322 ms                                                       | 388 ms: 1.21x slower                                                 |
| coverage                   | 66.6 ms                                                      | 81.8 ms: 1.23x slower                                                |
| scimark_fft                | 281 ms                                                       | 364 ms: 1.29x slower                                                 |
| scimark_sor                | 109 ms                                                       | 148 ms: 1.36x slower                                                 |
| python_startup_no_site     | 7.78 ms                                                      | 11.3 ms: 1.46x slower                                                |
| Geometric mean             | (ref)                                                        | 1.04x faster                                                         |

Benchmark hidden because not significant (7): asyncio_websockets, crypto_pyaes, dulwich_log, tomli_loads, mako, nbody, richards
Ignored benchmarks (11) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift


# HPT report

- Reliability score: 86.22% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
