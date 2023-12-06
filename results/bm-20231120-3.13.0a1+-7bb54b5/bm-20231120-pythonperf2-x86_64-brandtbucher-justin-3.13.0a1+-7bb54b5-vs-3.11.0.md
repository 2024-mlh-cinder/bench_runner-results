
# Results vs. 3.11.0

- fork: brandtbucher
- ref: justin
- machine: linux-x86_64
- commit hash: 7bb54b5
- commit date: 2023-11-20
- overall geometric mean: 1.03x faster \*
- HPT reliability: 81.66%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-pythonperf2-x86_64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|----------------|:------------------------------------------------------------:|:--------------------------------------------------------------------:|
| 2to3           | 286 ms                                                       | 302 ms: 1.06x slower                                                 |
| chameleon      | 7.42 ms                                                      | 7.53 ms: 1.01x slower                                                |
| tornado_http   | 125 ms                                                       | 122 ms: 1.03x faster                                                 |
| Geometric mean | (ref)                                                        | 1.01x slower                                                         |

Benchmark hidden because not significant (1): docutils

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-pythonperf2-x86_64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|----------------------------|:------------------------------------------------------------:|:--------------------------------------------------------------------:|
| async_tree_none            | 529 ms                                                       | 441 ms: 1.20x faster                                                 |
| async_tree_memoization     | 648 ms                                                       | 554 ms: 1.17x faster                                                 |
| async_tree_io              | 1.19 sec                                                     | 1.09 sec: 1.10x faster                                               |
| async_tree_none_tg         | 482 ms                                                       | 447 ms: 1.08x faster                                                 |
| async_tree_cpu_io_mixed    | 762 ms                                                       | 708 ms: 1.08x faster                                                 |
| async_tree_io_tg           | 1.17 sec                                                     | 1.10 sec: 1.06x faster                                               |
| async_tree_cpu_io_mixed_tg | 760 ms                                                       | 720 ms: 1.06x faster                                                 |
| async_tree_memoization_tg  | 605 ms                                                       | 578 ms: 1.05x faster                                                 |
| Geometric mean             | (ref)                                                        | 1.10x faster                                                         |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-pythonperf2-x86_64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|----------------|:------------------------------------------------------------:|:--------------------------------------------------------------------:|
| nbody          | 95.8 ms                                                      | 94.4 ms: 1.01x faster                                                |
| pidigits       | 251 ms                                                       | 265 ms: 1.06x slower                                                 |
| float          | 76.0 ms                                                      | 81.0 ms: 1.07x slower                                                |
| Geometric mean | (ref)                                                        | 1.04x slower                                                         |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-pythonperf2-x86_64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|----------------|:------------------------------------------------------------:|:--------------------------------------------------------------------:|
| regex_compile  | 157 ms                                                       | 150 ms: 1.05x faster                                                 |
| regex_effbot   | 3.42 ms                                                      | 3.57 ms: 1.05x slower                                                |
| regex_dna      | 226 ms                                                       | 240 ms: 1.06x slower                                                 |
| regex_v8       | 23.7 ms                                                      | 25.5 ms: 1.08x slower                                                |
| Geometric mean | (ref)                                                        | 1.03x slower                                                         |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-pythonperf2-x86_64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|----------------------|:------------------------------------------------------------:|:--------------------------------------------------------------------:|
| json_dumps           | 13.5 ms                                                      | 10.8 ms: 1.25x faster                                                |
| json_loads           | 29.0 us                                                      | 25.7 us: 1.13x faster                                                |
| xml_etree_parse      | 159 ms                                                       | 148 ms: 1.07x faster                                                 |
| unpickle_pure_python | 236 us                                                       | 227 us: 1.04x faster                                                 |
| pickle_pure_python   | 318 us                                                       | 316 us: 1.01x faster                                                 |
| tomli_loads          | 2.27 sec                                                     | 2.29 sec: 1.01x slower                                               |
| pickle               | 9.77 us                                                      | 9.99 us: 1.02x slower                                                |
| pickle_dict          | 31.8 us                                                      | 33.3 us: 1.05x slower                                                |
| unpickle_list        | 4.47 us                                                      | 4.69 us: 1.05x slower                                                |
| xml_etree_process    | 56.1 ms                                                      | 59.7 ms: 1.06x slower                                                |
| xml_etree_generate   | 80.5 ms                                                      | 86.8 ms: 1.08x slower                                                |
| pickle_list          | 3.89 us                                                      | 4.24 us: 1.09x slower                                                |
| unpickle             | 13.2 us                                                      | 14.9 us: 1.13x slower                                                |
| Geometric mean       | (ref)                                                        | 1.00x slower                                                         |

Benchmark hidden because not significant (1): xml_etree_iterparse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-pythonperf2-x86_64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|------------------------|:------------------------------------------------------------:|:--------------------------------------------------------------------:|
| python_startup         | 10.8 ms                                                      | 12.9 ms: 1.19x slower                                                |
| python_startup_no_site | 7.78 ms                                                      | 11.4 ms: 1.46x slower                                                |
| Geometric mean         | (ref)                                                        | 1.32x slower                                                         |

Benchmarks with tag 'template':
===============================

Benchmark hidden because not significant (1): mako

All benchmarks:
===============

| Benchmark                  | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-pythonperf2-x86_64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|----------------------------|:------------------------------------------------------------:|:--------------------------------------------------------------------:|
| typing_runtime_protocols   | 527 us                                                       | 129 us: 4.07x faster                                                 |
| asyncio_tcp                | 752 ms                                                       | 366 ms: 2.05x faster                                                 |
| asyncio_tcp_ssl            | 3.09 sec                                                     | 1.57 sec: 1.96x faster                                               |
| generators                 | 56.4 ms                                                      | 36.0 ms: 1.56x faster                                                |
| json_dumps                 | 13.5 ms                                                      | 10.8 ms: 1.25x faster                                                |
| coroutines                 | 27.9 ms                                                      | 22.6 ms: 1.23x faster                                                |
| comprehensions             | 24.8 us                                                      | 20.3 us: 1.22x faster                                                |
| async_tree_none            | 529 ms                                                       | 441 ms: 1.20x faster                                                 |
| mypy2                      | 449 ms                                                       | 380 ms: 1.18x faster                                                 |
| async_tree_memoization     | 648 ms                                                       | 554 ms: 1.17x faster                                                 |
| richards_super             | 65.2 ms                                                      | 56.1 ms: 1.16x faster                                                |
| sympy_sum                  | 184 ms                                                       | 160 ms: 1.15x faster                                                 |
| json_loads                 | 29.0 us                                                      | 25.7 us: 1.13x faster                                                |
| scimark_lu                 | 115 ms                                                       | 104 ms: 1.11x faster                                                 |
| sympy_str                  | 336 ms                                                       | 302 ms: 1.11x faster                                                 |
| fannkuch                   | 457 ms                                                       | 414 ms: 1.10x faster                                                 |
| async_tree_io              | 1.19 sec                                                     | 1.09 sec: 1.10x faster                                               |
| logging_simple             | 7.21 us                                                      | 6.62 us: 1.09x faster                                                |
| sympy_expand               | 550 ms                                                       | 506 ms: 1.09x faster                                                 |
| logging_format             | 7.83 us                                                      | 7.20 us: 1.09x faster                                                |
| deltablue                  | 4.03 ms                                                      | 3.71 ms: 1.09x faster                                                |
| sqlglot_parse              | 1.55 ms                                                      | 1.43 ms: 1.09x faster                                                |
| async_tree_none_tg         | 482 ms                                                       | 447 ms: 1.08x faster                                                 |
| async_tree_cpu_io_mixed    | 762 ms                                                       | 708 ms: 1.08x faster                                                 |
| xml_etree_parse            | 159 ms                                                       | 148 ms: 1.07x faster                                                 |
| raytrace                   | 308 ms                                                       | 288 ms: 1.07x faster                                                 |
| deepcopy                   | 389 us                                                       | 366 us: 1.06x faster                                                 |
| async_tree_io_tg           | 1.17 sec                                                     | 1.10 sec: 1.06x faster                                               |
| async_tree_cpu_io_mixed_tg | 760 ms                                                       | 720 ms: 1.06x faster                                                 |
| sympy_integrate            | 25.6 ms                                                      | 24.4 ms: 1.05x faster                                                |
| json                       | 5.59 ms                                                      | 5.32 ms: 1.05x faster                                                |
| regex_compile              | 157 ms                                                       | 150 ms: 1.05x faster                                                 |
| bench_thread_pool          | 1.02 ms                                                      | 972 us: 1.05x faster                                                 |
| async_tree_memoization_tg  | 605 ms                                                       | 578 ms: 1.05x faster                                                 |
| sqlglot_transpile          | 1.94 ms                                                      | 1.86 ms: 1.04x faster                                                |
| mdp                        | 2.72 sec                                                     | 2.61 sec: 1.04x faster                                               |
| unpickle_pure_python       | 236 us                                                       | 227 us: 1.04x faster                                                 |
| gc_traversal               | 4.06 ms                                                      | 3.93 ms: 1.03x faster                                                |
| dask                       | 417 ms                                                       | 404 ms: 1.03x faster                                                 |
| logging_silent             | 102 ns                                                       | 99.0 ns: 1.03x faster                                                |
| tornado_http               | 125 ms                                                       | 122 ms: 1.03x faster                                                 |
| deepcopy_reduce            | 3.37 us                                                      | 3.31 us: 1.02x faster                                                |
| chaos                      | 71.6 ms                                                      | 70.3 ms: 1.02x faster                                                |
| nbody                      | 95.8 ms                                                      | 94.4 ms: 1.01x faster                                                |
| dulwich_log                | 68.3 ms                                                      | 67.7 ms: 1.01x faster                                                |
| pickle_pure_python         | 318 us                                                       | 316 us: 1.01x faster                                                 |
| deepcopy_memo              | 37.3 us                                                      | 37.1 us: 1.01x faster                                                |
| crypto_pyaes               | 81.8 ms                                                      | 81.3 ms: 1.01x faster                                                |
| pathlib                    | 19.1 ms                                                      | 19.1 ms: 1.00x faster                                                |
| tomli_loads                | 2.27 sec                                                     | 2.29 sec: 1.01x slower                                               |
| meteor_contest             | 130 ms                                                       | 132 ms: 1.01x slower                                                 |
| go                         | 166 ms                                                       | 168 ms: 1.01x slower                                                 |
| chameleon                  | 7.42 ms                                                      | 7.53 ms: 1.01x slower                                                |
| pickle                     | 9.77 us                                                      | 9.99 us: 1.02x slower                                                |
| pycparser                  | 1.28 sec                                                     | 1.33 sec: 1.03x slower                                               |
| nqueens                    | 99.2 ms                                                      | 103 ms: 1.04x slower                                                 |
| sqlglot_optimize           | 59.2 ms                                                      | 61.7 ms: 1.04x slower                                                |
| regex_effbot               | 3.42 ms                                                      | 3.57 ms: 1.05x slower                                                |
| pickle_dict                | 31.8 us                                                      | 33.3 us: 1.05x slower                                                |
| unpickle_list              | 4.47 us                                                      | 4.69 us: 1.05x slower                                                |
| pidigits                   | 251 ms                                                       | 265 ms: 1.06x slower                                                 |
| 2to3                       | 286 ms                                                       | 302 ms: 1.06x slower                                                 |
| regex_dna                  | 226 ms                                                       | 240 ms: 1.06x slower                                                 |
| xml_etree_process          | 56.1 ms                                                      | 59.7 ms: 1.06x slower                                                |
| float                      | 76.0 ms                                                      | 81.0 ms: 1.07x slower                                                |
| pprint_pformat             | 1.63 sec                                                     | 1.74 sec: 1.07x slower                                               |
| unpack_sequence            | 44.9 ns                                                      | 48.0 ns: 1.07x slower                                                |
| regex_v8                   | 23.7 ms                                                      | 25.5 ms: 1.08x slower                                                |
| spectral_norm              | 94.0 ms                                                      | 101 ms: 1.08x slower                                                 |
| scimark_sparse_mat_mult    | 4.04 ms                                                      | 4.35 ms: 1.08x slower                                                |
| xml_etree_generate         | 80.5 ms                                                      | 86.8 ms: 1.08x slower                                                |
| pickle_list                | 3.89 us                                                      | 4.24 us: 1.09x slower                                                |
| pprint_safe_repr           | 780 ms                                                       | 850 ms: 1.09x slower                                                 |
| sqlite_synth               | 2.49 us                                                      | 2.72 us: 1.09x slower                                                |
| scimark_monte_carlo        | 70.6 ms                                                      | 78.4 ms: 1.11x slower                                                |
| hexiom                     | 6.97 ms                                                      | 7.82 ms: 1.12x slower                                                |
| unpickle                   | 13.2 us                                                      | 14.9 us: 1.13x slower                                                |
| pyflate                    | 453 ms                                                       | 515 ms: 1.14x slower                                                 |
| python_startup             | 10.8 ms                                                      | 12.9 ms: 1.19x slower                                                |
| coverage                   | 66.6 ms                                                      | 79.9 ms: 1.20x slower                                                |
| telco                      | 6.91 ms                                                      | 8.36 ms: 1.21x slower                                                |
| async_generators           | 322 ms                                                       | 395 ms: 1.23x slower                                                 |
| scimark_fft                | 281 ms                                                       | 375 ms: 1.33x slower                                                 |
| scimark_sor                | 109 ms                                                       | 148 ms: 1.35x slower                                                 |
| python_startup_no_site     | 7.78 ms                                                      | 11.4 ms: 1.46x slower                                                |
| Geometric mean             | (ref)                                                        | 1.03x faster                                                         |

Benchmark hidden because not significant (8): create_gc_cycles, sqlglot_normalize, asyncio_websockets, richards, xml_etree_iterparse, docutils, mako, bench_mp_pool
Ignored benchmarks (11) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift


# HPT report

- Reliability score: 81.66% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
