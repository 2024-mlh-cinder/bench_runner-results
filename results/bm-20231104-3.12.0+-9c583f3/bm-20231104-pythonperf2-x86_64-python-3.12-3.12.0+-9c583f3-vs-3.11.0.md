
# Results vs. 3.11.0

- fork: python
- ref: 3.12
- machine: linux-x86_64
- commit hash: 9c583f3
- commit date: 2023-11-04
- overall geometric mean: 1.07x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.02x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231104-pythonperf2-x86_64-python-3.12-3.12.0+-9c583f3 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------:|
| chameleon      | 7.42 ms                                                      | 7.25 ms: 1.02x faster                                      |
| docutils       | 2.87 sec                                                     | 2.85 sec: 1.01x faster                                     |
| tornado_http   | 125 ms                                                       | 120 ms: 1.04x faster                                       |
| Geometric mean | (ref)                                                        | 1.02x faster                                               |

Benchmark hidden because not significant (1): 2to3

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231104-pythonperf2-x86_64-python-3.12-3.12.0+-9c583f3 |
|----------------------------|:------------------------------------------------------------:|:----------------------------------------------------------:|
| async_tree_memoization     | 648 ms                                                       | 553 ms: 1.17x faster                                       |
| async_tree_none            | 529 ms                                                       | 458 ms: 1.15x faster                                       |
| async_tree_io              | 1.19 sec                                                     | 1.06 sec: 1.13x faster                                     |
| async_tree_none_tg         | 482 ms                                                       | 437 ms: 1.10x faster                                       |
| async_tree_io_tg           | 1.17 sec                                                     | 1.07 sec: 1.10x faster                                     |
| async_tree_memoization_tg  | 605 ms                                                       | 551 ms: 1.10x faster                                       |
| async_tree_cpu_io_mixed    | 762 ms                                                       | 704 ms: 1.08x faster                                       |
| async_tree_cpu_io_mixed_tg | 760 ms                                                       | 706 ms: 1.08x faster                                       |
| Geometric mean             | (ref)                                                        | 1.11x faster                                               |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231104-pythonperf2-x86_64-python-3.12-3.12.0+-9c583f3 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------:|
| nbody          | 95.8 ms                                                      | 83.2 ms: 1.15x faster                                      |
| float          | 76.0 ms                                                      | 77.7 ms: 1.02x slower                                      |
| pidigits       | 251 ms                                                       | 264 ms: 1.05x slower                                       |
| Geometric mean | (ref)                                                        | 1.02x faster                                               |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231104-pythonperf2-x86_64-python-3.12-3.12.0+-9c583f3 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------:|
| regex_compile  | 157 ms                                                       | 139 ms: 1.13x faster                                       |
| regex_v8       | 23.7 ms                                                      | 24.2 ms: 1.02x slower                                      |
| regex_effbot   | 3.42 ms                                                      | 3.50 ms: 1.02x slower                                      |
| regex_dna      | 226 ms                                                       | 244 ms: 1.08x slower                                       |
| Geometric mean | (ref)                                                        | 1.00x faster                                               |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231104-pythonperf2-x86_64-python-3.12-3.12.0+-9c583f3 |
|----------------------|:------------------------------------------------------------:|:----------------------------------------------------------:|
| json_dumps           | 13.5 ms                                                      | 10.2 ms: 1.32x faster                                      |
| json_loads           | 29.0 us                                                      | 24.4 us: 1.19x faster                                      |
| unpickle_pure_python | 236 us                                                       | 210 us: 1.12x faster                                       |
| xml_etree_parse      | 159 ms                                                       | 148 ms: 1.07x faster                                       |
| xml_etree_iterparse  | 106 ms                                                       | 104 ms: 1.02x faster                                       |
| tomli_loads          | 2.27 sec                                                     | 2.23 sec: 1.02x faster                                     |
| pickle_pure_python   | 318 us                                                       | 324 us: 1.02x slower                                       |
| pickle_dict          | 31.8 us                                                      | 32.6 us: 1.03x slower                                      |
| xml_etree_process    | 56.1 ms                                                      | 58.2 ms: 1.04x slower                                      |
| pickle               | 9.77 us                                                      | 10.2 us: 1.05x slower                                      |
| unpickle_list        | 4.47 us                                                      | 4.75 us: 1.06x slower                                      |
| xml_etree_generate   | 80.5 ms                                                      | 86.0 ms: 1.07x slower                                      |
| unpickle             | 13.2 us                                                      | 14.9 us: 1.13x slower                                      |
| pickle_list          | 3.89 us                                                      | 4.57 us: 1.17x slower                                      |
| Geometric mean       | (ref)                                                        | 1.01x faster                                               |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231104-pythonperf2-x86_64-python-3.12-3.12.0+-9c583f3 |
|------------------------|:------------------------------------------------------------:|:----------------------------------------------------------:|
| python_startup         | 10.8 ms                                                      | 11.7 ms: 1.08x slower                                      |
| python_startup_no_site | 7.78 ms                                                      | 8.63 ms: 1.11x slower                                      |
| Geometric mean         | (ref)                                                        | 1.09x slower                                               |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231104-pythonperf2-x86_64-python-3.12-3.12.0+-9c583f3 |
|-----------------|:------------------------------------------------------------:|:----------------------------------------------------------:|
| mako            | 11.0 ms                                                      | 9.98 ms: 1.10x faster                                      |
| django_template | 40.4 ms                                                      | 38.7 ms: 1.04x faster                                      |
| Geometric mean  | (ref)                                                        | 1.07x faster                                               |

All benchmarks:
===============

| Benchmark                  | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231104-pythonperf2-x86_64-python-3.12-3.12.0+-9c583f3 |
|----------------------------|:------------------------------------------------------------:|:----------------------------------------------------------:|
| typing_runtime_protocols   | 527 us                                                       | 122 us: 4.31x faster                                       |
| asyncio_tcp                | 752 ms                                                       | 378 ms: 1.99x faster                                       |
| asyncio_tcp_ssl            | 3.09 sec                                                     | 1.58 sec: 1.96x faster                                     |
| generators                 | 56.4 ms                                                      | 36.5 ms: 1.54x faster                                      |
| json_dumps                 | 13.5 ms                                                      | 10.2 ms: 1.32x faster                                      |
| fannkuch                   | 457 ms                                                       | 348 ms: 1.32x faster                                       |
| richards_super             | 65.2 ms                                                      | 51.3 ms: 1.27x faster                                      |
| deltablue                  | 4.03 ms                                                      | 3.29 ms: 1.22x faster                                      |
| coroutines                 | 27.9 ms                                                      | 23.2 ms: 1.20x faster                                      |
| json_loads                 | 29.0 us                                                      | 24.4 us: 1.19x faster                                      |
| comprehensions             | 24.8 us                                                      | 21.0 us: 1.18x faster                                      |
| async_tree_memoization     | 648 ms                                                       | 553 ms: 1.17x faster                                       |
| hexiom                     | 6.97 ms                                                      | 5.97 ms: 1.17x faster                                      |
| scimark_lu                 | 115 ms                                                       | 98.9 ms: 1.17x faster                                      |
| async_tree_none            | 529 ms                                                       | 458 ms: 1.15x faster                                       |
| chaos                      | 71.6 ms                                                      | 62.1 ms: 1.15x faster                                      |
| nbody                      | 95.8 ms                                                      | 83.2 ms: 1.15x faster                                      |
| sympy_sum                  | 184 ms                                                       | 161 ms: 1.15x faster                                       |
| gc_traversal               | 4.06 ms                                                      | 3.55 ms: 1.14x faster                                      |
| regex_compile              | 157 ms                                                       | 139 ms: 1.13x faster                                       |
| async_tree_io              | 1.19 sec                                                     | 1.06 sec: 1.13x faster                                     |
| sympy_expand               | 550 ms                                                       | 489 ms: 1.12x faster                                       |
| unpickle_pure_python       | 236 us                                                       | 210 us: 1.12x faster                                       |
| sqlglot_parse              | 1.55 ms                                                      | 1.38 ms: 1.12x faster                                      |
| richards                   | 49.9 ms                                                      | 44.7 ms: 1.12x faster                                      |
| sympy_str                  | 336 ms                                                       | 301 ms: 1.11x faster                                       |
| go                         | 166 ms                                                       | 149 ms: 1.11x faster                                       |
| logging_silent             | 102 ns                                                       | 91.8 ns: 1.11x faster                                      |
| nqueens                    | 99.2 ms                                                      | 89.6 ms: 1.11x faster                                      |
| mako                       | 11.0 ms                                                      | 9.98 ms: 1.10x faster                                      |
| async_tree_none_tg         | 482 ms                                                       | 437 ms: 1.10x faster                                       |
| async_tree_io_tg           | 1.17 sec                                                     | 1.07 sec: 1.10x faster                                     |
| async_tree_memoization_tg  | 605 ms                                                       | 551 ms: 1.10x faster                                       |
| json                       | 5.59 ms                                                      | 5.11 ms: 1.09x faster                                      |
| sqlglot_transpile          | 1.94 ms                                                      | 1.79 ms: 1.09x faster                                      |
| sympy_integrate            | 25.6 ms                                                      | 23.6 ms: 1.09x faster                                      |
| async_tree_cpu_io_mixed    | 762 ms                                                       | 704 ms: 1.08x faster                                       |
| async_tree_cpu_io_mixed_tg | 760 ms                                                       | 706 ms: 1.08x faster                                       |
| xml_etree_parse            | 159 ms                                                       | 148 ms: 1.07x faster                                       |
| mdp                        | 2.72 sec                                                     | 2.54 sec: 1.07x faster                                     |
| sqlalchemy_imperative      | 19.9 ms                                                      | 18.7 ms: 1.07x faster                                      |
| bench_thread_pool          | 1.02 ms                                                      | 959 us: 1.06x faster                                       |
| deepcopy                   | 389 us                                                       | 368 us: 1.06x faster                                       |
| dask                       | 417 ms                                                       | 394 ms: 1.06x faster                                       |
| dulwich_log                | 68.3 ms                                                      | 64.9 ms: 1.05x faster                                      |
| sqlglot_normalize          | 122 ms                                                       | 116 ms: 1.05x faster                                       |
| logging_simple             | 7.21 us                                                      | 6.91 us: 1.04x faster                                      |
| django_template            | 40.4 ms                                                      | 38.7 ms: 1.04x faster                                      |
| pycparser                  | 1.28 sec                                                     | 1.23 sec: 1.04x faster                                     |
| tornado_http               | 125 ms                                                       | 120 ms: 1.04x faster                                       |
| raytrace                   | 308 ms                                                       | 297 ms: 1.04x faster                                       |
| logging_format             | 7.83 us                                                      | 7.61 us: 1.03x faster                                      |
| spectral_norm              | 94.0 ms                                                      | 91.3 ms: 1.03x faster                                      |
| coverage                   | 66.6 ms                                                      | 64.9 ms: 1.03x faster                                      |
| pyflate                    | 453 ms                                                       | 442 ms: 1.02x faster                                       |
| scimark_monte_carlo        | 70.6 ms                                                      | 68.9 ms: 1.02x faster                                      |
| chameleon                  | 7.42 ms                                                      | 7.25 ms: 1.02x faster                                      |
| xml_etree_iterparse        | 106 ms                                                       | 104 ms: 1.02x faster                                       |
| tomli_loads                | 2.27 sec                                                     | 2.23 sec: 1.02x faster                                     |
| sqlglot_optimize           | 59.2 ms                                                      | 58.0 ms: 1.02x faster                                      |
| deepcopy_memo              | 37.3 us                                                      | 36.5 us: 1.02x faster                                      |
| docutils                   | 2.87 sec                                                     | 2.85 sec: 1.01x faster                                     |
| meteor_contest             | 130 ms                                                       | 130 ms: 1.00x faster                                       |
| pathlib                    | 19.1 ms                                                      | 19.4 ms: 1.01x slower                                      |
| deepcopy_reduce            | 3.37 us                                                      | 3.42 us: 1.02x slower                                      |
| pickle_pure_python         | 318 us                                                       | 324 us: 1.02x slower                                       |
| gunicorn                   | 986 us                                                       | 1.00 ms: 1.02x slower                                      |
| float                      | 76.0 ms                                                      | 77.7 ms: 1.02x slower                                      |
| regex_v8                   | 23.7 ms                                                      | 24.2 ms: 1.02x slower                                      |
| pprint_safe_repr           | 780 ms                                                       | 798 ms: 1.02x slower                                       |
| regex_effbot               | 3.42 ms                                                      | 3.50 ms: 1.02x slower                                      |
| pickle_dict                | 31.8 us                                                      | 32.6 us: 1.03x slower                                      |
| sqlalchemy_declarative     | 155 ms                                                       | 159 ms: 1.03x slower                                       |
| xml_etree_process          | 56.1 ms                                                      | 58.2 ms: 1.04x slower                                      |
| aiohttp                    | 984 us                                                       | 1.02 ms: 1.04x slower                                      |
| scimark_fft                | 281 ms                                                       | 294 ms: 1.04x slower                                       |
| pickle                     | 9.77 us                                                      | 10.2 us: 1.05x slower                                      |
| pidigits                   | 251 ms                                                       | 264 ms: 1.05x slower                                       |
| unpickle_list              | 4.47 us                                                      | 4.75 us: 1.06x slower                                      |
| xml_etree_generate         | 80.5 ms                                                      | 86.0 ms: 1.07x slower                                      |
| python_startup             | 10.8 ms                                                      | 11.7 ms: 1.08x slower                                      |
| scimark_sparse_mat_mult    | 4.04 ms                                                      | 4.35 ms: 1.08x slower                                      |
| regex_dna                  | 226 ms                                                       | 244 ms: 1.08x slower                                       |
| telco                      | 6.91 ms                                                      | 7.59 ms: 1.10x slower                                      |
| sqlite_synth               | 2.49 us                                                      | 2.74 us: 1.10x slower                                      |
| python_startup_no_site     | 7.78 ms                                                      | 8.63 ms: 1.11x slower                                      |
| unpickle                   | 13.2 us                                                      | 14.9 us: 1.13x slower                                      |
| pickle_list                | 3.89 us                                                      | 4.57 us: 1.17x slower                                      |
| unpack_sequence            | 44.9 ns                                                      | 53.9 ns: 1.20x slower                                      |
| async_generators           | 322 ms                                                       | 390 ms: 1.21x slower                                       |
| bench_mp_pool              | 4.63 ms                                                      | 5.86 ms: 1.27x slower                                      |
| Geometric mean             | (ref)                                                        | 1.07x faster                                               |

Benchmark hidden because not significant (7): asyncio_websockets, scimark_sor, pprint_pformat, 2to3, crypto_pyaes, create_gc_cycles, mypy2
Ignored benchmarks (6) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509.json: flaskblogging, genshi_text, genshi_xml, html5lib, pylint, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.03x
- 95% likely to have a speedup of 1.03x
- 99% likely to have a speedup of 1.02x
