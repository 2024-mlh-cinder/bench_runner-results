
# Results vs. 3.11.0

- fork: python
- ref: 6dfb8fe0236718e9afc8
- machine: linux-x86_64
- commit hash: 6dfb8fe
- commit date: 2023-10-30
- overall geometric mean: 1.05x faster
- HPT reliability: 98.93%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231030-pythonperf2-x86_64-python-6dfb8fe0236718e9afc8-3.13.0a1+-6dfb8fe |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| 2to3           | 286 ms                                                       | 297 ms: 1.04x slower                                                         |
| chameleon      | 7.42 ms                                                      | 7.54 ms: 1.02x slower                                                        |
| docutils       | 2.87 sec                                                     | 2.88 sec: 1.00x slower                                                       |
| tornado_http   | 125 ms                                                       | 120 ms: 1.04x faster                                                         |
| Geometric mean | (ref)                                                        | 1.00x slower                                                                 |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231030-pythonperf2-x86_64-python-6dfb8fe0236718e9afc8-3.13.0a1+-6dfb8fe |
|----------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| async_tree_none            | 529 ms                                                       | 435 ms: 1.22x faster                                                         |
| async_tree_memoization     | 648 ms                                                       | 548 ms: 1.18x faster                                                         |
| async_tree_io              | 1.19 sec                                                     | 1.08 sec: 1.10x faster                                                       |
| async_tree_cpu_io_mixed    | 762 ms                                                       | 699 ms: 1.09x faster                                                         |
| async_tree_none_tg         | 482 ms                                                       | 443 ms: 1.09x faster                                                         |
| async_tree_io_tg           | 1.17 sec                                                     | 1.10 sec: 1.07x faster                                                       |
| async_tree_cpu_io_mixed_tg | 760 ms                                                       | 716 ms: 1.06x faster                                                         |
| async_tree_memoization_tg  | 605 ms                                                       | 574 ms: 1.05x faster                                                         |
| Geometric mean             | (ref)                                                        | 1.11x faster                                                                 |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231030-pythonperf2-x86_64-python-6dfb8fe0236718e9afc8-3.13.0a1+-6dfb8fe |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| nbody          | 95.8 ms                                                      | 91.3 ms: 1.05x faster                                                        |
| float          | 76.0 ms                                                      | 78.4 ms: 1.03x slower                                                        |
| pidigits       | 251 ms                                                       | 264 ms: 1.05x slower                                                         |
| Geometric mean | (ref)                                                        | 1.01x slower                                                                 |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231030-pythonperf2-x86_64-python-6dfb8fe0236718e9afc8-3.13.0a1+-6dfb8fe |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| regex_compile  | 157 ms                                                       | 148 ms: 1.06x faster                                                         |
| regex_effbot   | 3.42 ms                                                      | 3.53 ms: 1.03x slower                                                        |
| regex_v8       | 23.7 ms                                                      | 25.5 ms: 1.08x slower                                                        |
| regex_dna      | 226 ms                                                       | 249 ms: 1.10x slower                                                         |
| Geometric mean | (ref)                                                        | 1.04x slower                                                                 |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231030-pythonperf2-x86_64-python-6dfb8fe0236718e9afc8-3.13.0a1+-6dfb8fe |
|----------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| json_dumps           | 13.5 ms                                                      | 10.8 ms: 1.25x faster                                                        |
| json_loads           | 29.0 us                                                      | 24.8 us: 1.17x faster                                                        |
| xml_etree_parse      | 159 ms                                                       | 148 ms: 1.07x faster                                                         |
| unpickle_pure_python | 236 us                                                       | 223 us: 1.06x faster                                                         |
| tomli_loads          | 2.27 sec                                                     | 2.21 sec: 1.03x faster                                                       |
| pickle_dict          | 31.8 us                                                      | 31.8 us: 1.00x slower                                                        |
| unpickle_list        | 4.47 us                                                      | 4.51 us: 1.01x slower                                                        |
| xml_etree_iterparse  | 106 ms                                                       | 107 ms: 1.01x slower                                                         |
| pickle_pure_python   | 318 us                                                       | 325 us: 1.02x slower                                                         |
| xml_etree_process    | 56.1 ms                                                      | 58.3 ms: 1.04x slower                                                        |
| pickle               | 9.77 us                                                      | 10.4 us: 1.06x slower                                                        |
| xml_etree_generate   | 80.5 ms                                                      | 85.7 ms: 1.07x slower                                                        |
| unpickle             | 13.2 us                                                      | 14.5 us: 1.10x slower                                                        |
| pickle_list          | 3.89 us                                                      | 4.41 us: 1.13x slower                                                        |
| Geometric mean       | (ref)                                                        | 1.01x faster                                                                 |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231030-pythonperf2-x86_64-python-6dfb8fe0236718e9afc8-3.13.0a1+-6dfb8fe |
|------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| python_startup         | 10.8 ms                                                      | 12.8 ms: 1.19x slower                                                        |
| python_startup_no_site | 7.78 ms                                                      | 11.3 ms: 1.45x slower                                                        |
| Geometric mean         | (ref)                                                        | 1.31x slower                                                                 |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231030-pythonperf2-x86_64-python-6dfb8fe0236718e9afc8-3.13.0a1+-6dfb8fe |
|-----------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| mako      | 11.0 ms                                                      | 10.4 ms: 1.06x faster                                                        |

All benchmarks:
===============

| Benchmark                  | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231030-pythonperf2-x86_64-python-6dfb8fe0236718e9afc8-3.13.0a1+-6dfb8fe |
|----------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| typing_runtime_protocols   | 527 us                                                       | 154 us: 3.43x faster                                                         |
| asyncio_tcp                | 752 ms                                                       | 372 ms: 2.02x faster                                                         |
| asyncio_tcp_ssl            | 3.09 sec                                                     | 1.58 sec: 1.95x faster                                                       |
| generators                 | 56.4 ms                                                      | 36.0 ms: 1.57x faster                                                        |
| comprehensions             | 24.8 us                                                      | 16.7 us: 1.49x faster                                                        |
| json_dumps                 | 13.5 ms                                                      | 10.8 ms: 1.25x faster                                                        |
| coroutines                 | 27.9 ms                                                      | 22.6 ms: 1.23x faster                                                        |
| mypy2                      | 449 ms                                                       | 366 ms: 1.23x faster                                                         |
| async_tree_none            | 529 ms                                                       | 435 ms: 1.22x faster                                                         |
| sympy_sum                  | 184 ms                                                       | 153 ms: 1.21x faster                                                         |
| async_tree_memoization     | 648 ms                                                       | 548 ms: 1.18x faster                                                         |
| json_loads                 | 29.0 us                                                      | 24.8 us: 1.17x faster                                                        |
| sympy_str                  | 336 ms                                                       | 290 ms: 1.16x faster                                                         |
| chaos                      | 71.6 ms                                                      | 61.9 ms: 1.16x faster                                                        |
| scimark_lu                 | 115 ms                                                       | 99.8 ms: 1.15x faster                                                        |
| fannkuch                   | 457 ms                                                       | 397 ms: 1.15x faster                                                         |
| nqueens                    | 99.2 ms                                                      | 87.6 ms: 1.13x faster                                                        |
| crypto_pyaes               | 81.8 ms                                                      | 72.5 ms: 1.13x faster                                                        |
| sympy_expand               | 550 ms                                                       | 488 ms: 1.13x faster                                                         |
| sqlglot_parse              | 1.55 ms                                                      | 1.41 ms: 1.11x faster                                                        |
| gc_traversal               | 4.06 ms                                                      | 3.68 ms: 1.10x faster                                                        |
| raytrace                   | 308 ms                                                       | 280 ms: 1.10x faster                                                         |
| async_tree_io              | 1.19 sec                                                     | 1.08 sec: 1.10x faster                                                       |
| sympy_integrate            | 25.6 ms                                                      | 23.4 ms: 1.09x faster                                                        |
| async_tree_cpu_io_mixed    | 762 ms                                                       | 699 ms: 1.09x faster                                                         |
| async_tree_none_tg         | 482 ms                                                       | 443 ms: 1.09x faster                                                         |
| deltablue                  | 4.03 ms                                                      | 3.71 ms: 1.08x faster                                                        |
| richards_super             | 65.2 ms                                                      | 60.2 ms: 1.08x faster                                                        |
| hexiom                     | 6.97 ms                                                      | 6.45 ms: 1.08x faster                                                        |
| mdp                        | 2.72 sec                                                     | 2.53 sec: 1.07x faster                                                       |
| logging_simple             | 7.21 us                                                      | 6.73 us: 1.07x faster                                                        |
| xml_etree_parse            | 159 ms                                                       | 148 ms: 1.07x faster                                                         |
| json                       | 5.59 ms                                                      | 5.23 ms: 1.07x faster                                                        |
| sqlglot_transpile          | 1.94 ms                                                      | 1.82 ms: 1.07x faster                                                        |
| async_tree_io_tg           | 1.17 sec                                                     | 1.10 sec: 1.07x faster                                                       |
| regex_compile              | 157 ms                                                       | 148 ms: 1.06x faster                                                         |
| async_tree_cpu_io_mixed_tg | 760 ms                                                       | 716 ms: 1.06x faster                                                         |
| mako                       | 11.0 ms                                                      | 10.4 ms: 1.06x faster                                                        |
| unpickle_pure_python       | 236 us                                                       | 223 us: 1.06x faster                                                         |
| async_tree_memoization_tg  | 605 ms                                                       | 574 ms: 1.05x faster                                                         |
| sqlglot_normalize          | 122 ms                                                       | 116 ms: 1.05x faster                                                         |
| logging_format             | 7.83 us                                                      | 7.45 us: 1.05x faster                                                        |
| nbody                      | 95.8 ms                                                      | 91.3 ms: 1.05x faster                                                        |
| logging_silent             | 102 ns                                                       | 97.4 ns: 1.05x faster                                                        |
| bench_thread_pool          | 1.02 ms                                                      | 974 us: 1.05x faster                                                         |
| tornado_http               | 125 ms                                                       | 120 ms: 1.04x faster                                                         |
| deepcopy                   | 389 us                                                       | 376 us: 1.04x faster                                                         |
| tomli_loads                | 2.27 sec                                                     | 2.21 sec: 1.03x faster                                                       |
| scimark_monte_carlo        | 70.6 ms                                                      | 68.7 ms: 1.03x faster                                                        |
| meteor_contest             | 130 ms                                                       | 129 ms: 1.01x faster                                                         |
| spectral_norm              | 94.0 ms                                                      | 93.0 ms: 1.01x faster                                                        |
| sqlglot_optimize           | 59.2 ms                                                      | 58.8 ms: 1.01x faster                                                        |
| pickle_dict                | 31.8 us                                                      | 31.8 us: 1.00x slower                                                        |
| docutils                   | 2.87 sec                                                     | 2.88 sec: 1.00x slower                                                       |
| deepcopy_reduce            | 3.37 us                                                      | 3.39 us: 1.00x slower                                                        |
| unpickle_list              | 4.47 us                                                      | 4.51 us: 1.01x slower                                                        |
| pycparser                  | 1.28 sec                                                     | 1.30 sec: 1.01x slower                                                       |
| dulwich_log                | 68.3 ms                                                      | 69.1 ms: 1.01x slower                                                        |
| xml_etree_iterparse        | 106 ms                                                       | 107 ms: 1.01x slower                                                         |
| deepcopy_memo              | 37.3 us                                                      | 37.8 us: 1.01x slower                                                        |
| chameleon                  | 7.42 ms                                                      | 7.54 ms: 1.02x slower                                                        |
| pickle_pure_python         | 318 us                                                       | 325 us: 1.02x slower                                                         |
| go                         | 166 ms                                                       | 170 ms: 1.03x slower                                                         |
| pathlib                    | 19.1 ms                                                      | 19.7 ms: 1.03x slower                                                        |
| float                      | 76.0 ms                                                      | 78.4 ms: 1.03x slower                                                        |
| regex_effbot               | 3.42 ms                                                      | 3.53 ms: 1.03x slower                                                        |
| scimark_sparse_mat_mult    | 4.04 ms                                                      | 4.19 ms: 1.04x slower                                                        |
| xml_etree_process          | 56.1 ms                                                      | 58.3 ms: 1.04x slower                                                        |
| 2to3                       | 286 ms                                                       | 297 ms: 1.04x slower                                                         |
| pprint_pformat             | 1.63 sec                                                     | 1.70 sec: 1.04x slower                                                       |
| pidigits                   | 251 ms                                                       | 264 ms: 1.05x slower                                                         |
| pickle                     | 9.77 us                                                      | 10.4 us: 1.06x slower                                                        |
| pprint_safe_repr           | 780 ms                                                       | 828 ms: 1.06x slower                                                         |
| xml_etree_generate         | 80.5 ms                                                      | 85.7 ms: 1.07x slower                                                        |
| sqlite_synth               | 2.49 us                                                      | 2.66 us: 1.07x slower                                                        |
| scimark_fft                | 281 ms                                                       | 301 ms: 1.07x slower                                                         |
| regex_v8                   | 23.7 ms                                                      | 25.5 ms: 1.08x slower                                                        |
| richards                   | 49.9 ms                                                      | 54.4 ms: 1.09x slower                                                        |
| unpack_sequence            | 44.9 ns                                                      | 49.3 ns: 1.10x slower                                                        |
| regex_dna                  | 226 ms                                                       | 249 ms: 1.10x slower                                                         |
| unpickle                   | 13.2 us                                                      | 14.5 us: 1.10x slower                                                        |
| pyflate                    | 453 ms                                                       | 510 ms: 1.13x slower                                                         |
| pickle_list                | 3.89 us                                                      | 4.41 us: 1.13x slower                                                        |
| telco                      | 6.91 ms                                                      | 8.08 ms: 1.17x slower                                                        |
| python_startup             | 10.8 ms                                                      | 12.8 ms: 1.19x slower                                                        |
| async_generators           | 322 ms                                                       | 395 ms: 1.23x slower                                                         |
| coverage                   | 66.6 ms                                                      | 82.9 ms: 1.24x slower                                                        |
| scimark_sor                | 109 ms                                                       | 145 ms: 1.32x slower                                                         |
| python_startup_no_site     | 7.78 ms                                                      | 11.3 ms: 1.45x slower                                                        |
| Geometric mean             | (ref)                                                        | 1.05x faster                                                                 |

Benchmark hidden because not significant (3): create_gc_cycles, asyncio_websockets, bench_mp_pool
Ignored benchmarks (12) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, dask, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift


# HPT report

- Reliability score: 98.93% likely to be faster
- 90% likely to have a speedup of 1.02x
- 95% likely to have a speedup of 1.01x
- 99% likely to have a speedup of 1.00x
